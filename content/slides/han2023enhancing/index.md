---
title: "Sample Presentation"
output:
  revealjs::revealjs_presentation
revealjs:
  theme: black
  transition: slide
  center: true
slides:
  theme: white  # Reveal JS theme name
  highlight_style: github  # Highlight JS theme name
---

# Introduction to HugoBlox

## What is HugoBlox?

- HugoBlox is a presentation framework.
- It combines **Hugo** and **Reveal.js**.
- Write slides in **Markdown**!

---

# Slide Layouts

## Text Slide

- You can create slides with simple text.
- Each slide is separated by a `---`.
- **Markdown** formatting works as usual!

## Bullet Points

- Easy to create bullet points
- Supports nested lists:
  - Like this one
  - And this one!

---

# Adding Code

```python
def greet():
    print("Hello, world!")
