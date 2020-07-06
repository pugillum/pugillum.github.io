class: center, middle

# Remark
A presentation about a presentation tool

---
class: center, middle

# How it works
---

### 1. Content, layout and styling in markdown


```markdown
    ---
    class: center, middle
    # .white[Cover slide]
    background-image: url(images/slides/background.jpg)
    background-size: contain
    ---
    
    # **meme**
    ![](images/slides/meme.jpg)
    
    ---
    # This
    1. Has 
    2. A
    3. List
    4. Mindblowing stuff, eh?
    ---
```
---

### 2. Create an HTML file
```html
<!DOCTYPE html>
<html>

  <head>
    <style type="text/css">
      /* Here be styles */ 
    </style>
  </head>

  <body>
    <script src="remark.js"></script>
    <script>
       var slideshow = remark.create({
            sourceUrl: 'slides.md'
       });
    </script>
  </body>
</html>
```

???

Styles allow you to play around with the look and feel
Link in the remark.js library
The markdown can added directly into the HTML or linked

---

### 3. Open your file
- directly in browser, or
- using something like `http.server`

---
class: center, middle
background-image: url(images/slides/background.jpg)
background-size: contain

# .white[Cover slide]

---
# Slide with **meme**
![](images/slides/meme.jpg)

---
# This

1. .red[has]
--

2. .orange[a]
--

3. .yellow[list]
--

4. .green[using]
--

5. .blue[incremental]
--

6. .indigo[slides]
--

7. which could get annoying if overused...

---
class: center, middle
layout: true

---

# Presentation mode (the P key)

???

# And look you can add some notes too

---

# Cloning (the C key)

---
layout: true

---
## Some other nice features
- comments
- template slides
- slide properties
- inline CSS
- syntax highlighting
- slide linking
- events
- timers


---
# But wait, there's more!

---

## Code formatting and highlighting
```python
def add_some_numbers(a,b):
*   a = random.randint(1,10)
*   b = random.randint(10,100)
    return a + b
```

---

class: nord-dark, center, middle

# Dark Mode

<small>For those serious moments</small>

---

## LaTex Support

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$


---

## Table sample

.st.noborder.st-hline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

.st.st-hline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

.column-2.column-norule[

.st.st-allline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| .nord11[Strawberry] | .nord11[$1]  | .nord11[7]    |
]

.st.st-vline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

]

---

## Columns

.column-2.font-sm.mb-xs[
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
]

.column-3.font-sm.mb-xs[
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
]

---

## Video

<video width="100%" height="420" controls>
    <source src="static/funny.mp4" type="video/mp4">
</video>

---

# I like because
- Simple
- Markdown
- Can host on your blog
- HTML and CSS
- It's free

---

# It works on a tablet or phone

