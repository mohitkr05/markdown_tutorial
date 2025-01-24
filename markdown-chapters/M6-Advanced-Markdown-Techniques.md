---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

### Module 6

# Advanced Markdown Techniques

---

## Using custom style

<style>
h4 {
    color: blue;
    font-family: Arial;
}
blockquote {
    background-color: #f999;
}

</style>

#### Custom style is cool


> This is a blockquote.
<!-- 
```
<style>
h1 {
    color: blue;
    font-family: Arial;
}
</style>
```
```
# This is a heading.
```
<style>
blockquote {
    background-color: #f999;
}
</style>

> This is a blockquote.

<style>
img {
    border: 1px solid black;
    padding: 5px;
}
</style>

![Example image](https://example.com/image.jpg)

<style>
p {
    font-size: 18px;
    color: green;
}
</style>

This is a paragraph of text.
<style>
pre {
    background-color: #f0f0f0;
    padding: 10px;
}
</style> -->


---

## Create an Image grid

``` css
.image-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 20px;
}
```

``` html
<div class="image-grid">
    ![Image 1](image1.jpg)
    ![Image 2](image2.jpg)
    ![Image 3](image3.jpg)
    ![Image 4](image4.jpg)
</div>
```

---

## Custom CSS for code blocks

<style>
  .language-javascript {
    background-color: #000;
    color: #333;
    font-family: Consolas, monospace;
    font-size: 14px;
    padding: 10px;
    border: 1px solid #ccc;
  }

  .language-python {
  background-color: #000;
  color: #fff;
  font-family: "Courier New", Courier, monospace;
  font-size: 50px;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  overflow: none;
}

</style>

```python
def helloworld():
  print ("hello world")

```

---

## Math

To include math equations, use the dollar sign ($) symbol to enclose the equation.

This is an inline equation: $y = mx + b$

This is a centered equation:

$$
y = \frac{1}{x}
$$

The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.


---

## Superscripts and Subscripts

To add superscripts, use the caret (^) symbol, and to add subscripts, use the underscore (_) symbol.

H<sub>2</sub>O is water.

E = mc<sup>2</sup>

---

## Videos

To add a video, use the `<video>` HTML tag and specify the source file using the `src` attribute.

<video width="320" height="240" controls>
  <source src="video-url-here" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

# Basic Syntax and Formatting

## Audio

To add audio, use the `<audio>` HTML tag and specify the source file using the `src` attribute.

<audio controls>
  <source src="audio-url-here" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>



---

## Metadata

- Some Markdown processors support metadata such as author names, dates, and tags. 
- This can be useful for organizing and categorizing your Markdown documents. 
- The syntax for metadata varies depending on the processor you are using, so be sure to consult the documentation for your specific processor.

---

## Nested Blockquotes

Nested blockquotes: You can nest blockquotes in Markdown by adding additional > symbols. For example:

> This is a blockquote.
>
> > This is a nested blockquote.
