---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

![bg right:40% 80%](images/markdown-3979921343.png)

# **Markdown**

The complete hands-on course

Mohit Kumar 
https://mohitkr.com/

---
# **About this course** 

- Markdown is easiest way to write formatted documents on internet
- This quick course covers handson Markdown
- Projects 
  - Create webpages 
  - Presentations 
  - Notes 
  - Use tools to convert to Markdown

---

# **About the instructor** 

![bg right:40% 80%](images/IMG_20221223_121712~3.jpg)

- 13+ Years of experience in Telecom, Cloud and DevOps with 9+ Years of corporate training experience
- 50+ Corporate trainings & 5K+ students in Udemy
- Reach out for any support at 
  - https://mohitkr.com
  
---

# **How to get best out of this course** 

- Follow along course - watch videos and practice
- Go slow and make sure you perform hands-on
- If you are busy, watch 1 video or 1 section per day.
- Perform excercises and attempt all the quiz

---
# **Sections**

- Module 1: Introduction to Markdown
- Module 2: Text formatting and styling
- Module 3: Lists and Tables
- Module 4: Links and Images
- Module 5: Code Blocks and Syntax Highlighting
- Module 6: Advanced Markdown Techniques
- Module 7: Markdown and Accessibility
- Module 8: What's  next?


---
# **Course Conclusion**

By the end of this course, you will be able to create 
- professional-looking documents and web pages using Markdown
- understand how to use Markdown in popular tools
- able to create accessible documents

This course will equip you with the skills needed to master Markdown and provide a solid foundation for learning other programming languages.

---

# **Feedback**

Please reach out to discord for any support and discussion related to the course.

https://mohitkr.com/
---

<!---
 What is Markdown?
    Why use Markdown?
    Basic syntax and formatting
    Writing your first Markdown document
-->

# **What is Markdown?** 

- A lightweight markup language
- Used to format plain text for the web
- Designed to be easy to read and write
- Uses simple syntax to create HTML content
- Compatible with many text editors and platforms
- Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages

---
# **Why use Markdown?**

- Easy to learn and write
- Allows for fast formatting of plain text
- Produces clean, consistent HTML code
- Works across many platforms and tools
- Promotes focus on content rather than formatting
- Markdown can be used for everything. People use it to create websites, documents, notes, books, presentations, email messages, and technical documentation.


---

# **Writing your markdown document**

- Write in any text file 
- Save the file as ".md"
- Use the markdown preview plugin with code editors
- Use online markdown editor - https://dillinger.io/
- Download and install markdown plugin for vscode

---

# **Working with Markdown**

- Turn markdown to website - https://blot.im/
- Jekyll, a popular static site generator
- Obsidian - a note taking app


---
<!--- 
- Headings and subheadings
- Paragraphs and line breaks
- Bold and italic text
- Blockquotes and horizontal rules

-->

# **Text Formatting & Styling**

- Headings & Subheadings
- Paragraphs & Line breaks
- Bold and Italic texts
- Blockquotes & Horizontal rules 

---

## Headings & Subheadings
Headings are denoted by a # symbol followed by the heading text.

`# Heading 1`
# Heading 1
`## Heading 2`
## Heading 2
`### Heading 3`
### Heading 3

---

## Headings & Subheadings

`#### Heading 4`  
#### Heading 4
`##### Heading 5`
##### Heading 5
`###### Heading 6`
###### Heading 6

---

## Paragraphs
```
Paragraphs are created by simply typing your text. Leave a blank line between each paragraph.

This is a paragraph. 

This is another paragraph.
```
Paragraphs are created by simply typing your text. Leave a blank line between each paragraph.

This is a paragraph. 

This is another paragraph.

---
## Emphasis


To add emphasis to your text, use `*asterisks*` or `_underscores_.`

This text is `*italic*` - *italic*.

This text is `**bold**` - **bold**.

This text is `***bold and italic***` - ***bold and italic***.

---
## Blockquotes

To create a blockquote, use the greater than symbol (>) followed by the text.

```
> "Be the change you wish to see in the world." 
> ― Mahatma Gandhi
```
> "Be the change you wish to see in the world." 
> ― Mahatma Gandhi

---

## Strikethrough

To add strikethrough to text, use two tilde symbols (~~) on either side of the text.

~~This text is strikethrough.~~



 
---

## Escape Characters

To include special characters, such as asterisks or underscores, use a backslash (\) before the character.
```
\* Asterisks \*
```
```
\_ Underscores \_
```

---

## Horizontal Rule


To create a horizontal rule, use three asterisks `(***)` or hyphens `(---)` on a line by themselves.

---

## Emoji

To add an emoji, use a colon (:) followed by the emoji name.

This is a smiley face emoji :smiley: :smile: :heart: :rocket:

---


## References

To add references to your document, use the square brackets [] syntax followed by a reference label in square brackets [] at the bottom of the document.

This is a reference [^1].

[^1]: This is the reference text.

---
 

## Footnotes

To create a footnote, use the square brackets [] syntax with a caret (^) followed by the footnote text in parentheses ().

This is a sentence with a footnote[^1].

[^1]: This is the footnote text.

--- 
 
## Unordered Lists


Unordered lists are created with a dash `(-)`, asterisk `(*)` or plus sign `(+)` followed by a space.


```
- Item 1
- Item 2
- Item 3
```
- Item 1
- Item 2
- Item 3


---

## Ordered Lists

Ordered lists are created with a number followed by a period.

```
1. Item 1
2. Item 2
3. Item 3
```
1. Item 1
2. Item 2
3. Item 3

---



## Task Lists

To create a task list, use the dash (-) symbol followed by brackets [] containing the task description and another set of brackets [] containing the task completion status.
```
- [x] Task 1 is complete
- [ ] Task 2 is incomplete
- [ ] Task 3 is incomplete
```
---


## Definition Lists

To create a definition list, use a term on one line, followed by a colon (:), and the definition on the next line.

Term 1
: Definition 1

Term 2
: Definition 2

---
## Definition Lists with Links

Definition lists with complex content: You can create more complex content in definition lists by using Markdown syntax within the definition. For example:

Term 1
: Definition 1 with *emphasis* and [links][1].

[1]: http://www.example.com/


---


## Spoiler text


<details>
<summary>Click to reveal</summary>

This is the hidden text.

</details>

```
<details>
<summary>Click to reveal</summary>

This is the hidden text.

</details>

```

---
## Tables

To create a table, use vertical bars (|) to separate columns and hyphens (-) to separate the header row from the content.

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |

---

## Formatting inside tables

| Name         | Age | Favorite Color |
| ------------ | --- | -------------- |
| John Doe     | 35  | **Blue**       |
| Jane Smith   | 27  | Green          |
| Bob Johnson  | 42  | Red            |

---

## Multi Line tables

Multi-line tables: You can create multi-line tables by using the HTML <br> tag to insert line breaks within table cells. For example:

<!-- ```
| Column 1 | Column 2          |
| -------- | -----------------|
| Line 1   | This is line 1.   |
|          | This is line 2.   |
| Line 2   | This is line 3.<br>This is line 4. |

``` -->
| Column 1 | Column 2          |
| -------- | -----------------|
| Line 1   | This is line 1.   |
|          | This is line 2.   |
| Line 2   | This is line 3.<br>This is line 4. |

---

## Tables with alignment

Tables with alignment: You can create tables with alignment in Markdown using the syntax :--- for left alignment, ---: for right alignment, and :---: for center alignment. For example:

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| 1            |     2          |             3 |
| 4            |     5          |             6 |

<!-- | Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| 1            |     2          |             3 |
| 4            |     5          |             6 | -->
---
 
## Links

To create a link, use brackets `[]` to enclose the link text, followed by parentheses `()` containing the URL.

```[Link to My websit](https://www.mohitkr.com)```

[Link to My website](https://www.mohitkr.com)

You can also add a title for the link by adding it in quotes after the URL.


---

## More Links 

Links with reference-style labels: You can create links with reference-style labels in Markdown by defining a reference link and then using it in the text. For example:

Here is a link to [Google][1].

[1]: http://www.google.com/


---

## Images

To add an image, use an exclamation mark (!), followed by brackets [] containing the alt text, and parentheses () containing the image URL.

``` html

![Image alt text](image-url-here)
```
You can also specify a title for the image by adding it in quotes after the URL.

``` html
![Image alt text](image-url-here "Image title")
```
---

## Links on Images

To add a Link on an image you can enclose the link onto an Image

``` html
[![alt text](image_url)](link_url)
```

---

## Inline Code

To include code within a sentence, use single backticks (`).

Use the `print()` function to display output in Python.

---

## Block Code

To create a block of code, use four spaces before each line of code.

    def add(x, y):
        return x + y

---

 
## Using custom style
```
<style>
h4 {
    color: blue;
    font-family: Arial;
}
blockquote {
    background-color: #f999;
}

</style>
```
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
---


# Introduction to Accessibility

- The WHO estimates that 15% of the world's population (more than 1 billion people) have an accessibility need. 

- When documentation is written with accessibility in mind, it improves the overall experience for all readers.

- Accessibility is the design and creation of digital content that can be used and understood by all individuals, including those with disabilities.

---


# Assistive Technology

- Assistive technologies are hardware and software tools designed to help individuals with disabilities
- Examples of assistive technologies include screen readers, magnifiers, speech recognition software, and alternative input devices like joysticks or switches.
- Assistive technologies can be used to help individuals with a wide range of disabilities, including visual, auditory, motor, and cognitive impairments. 


---

# Tips and Tricks

- Avoid bias and harm when discussing disability and accessibility
- Use a screen reader to test your documentation
- Ensure that your documentation can be accessed using only a keyboard
- Use semantic HTML tagging and native elements over custom styles.
- Avoid unnecessary font formatting and line breaks.

---

# Tips and Tricks (contd.)

- Explicitly document any specialized accessibility features in your product.
- Follow capitalization guidelines and avoid excessive punctuation. 
- Use "and" instead of "&" in headings, text, and navigation.
- It's okay to use "&" for technical purposes in code.


---

# Best practices

- Use semantic HTML tagging to provide structure and meaning to your content. Use headings (#, ##, ###, etc.) to organize your content into sections and sub-sections. 

- Use lists (*, -, 1., etc.) to break up large blocks of text and create clear, structured content.

- Use alternative text (alt text) to describe images in your Markdown content.



---

# Best practices(contd. 1)

- Use descriptive link text that clearly communicates the destination of the link. 

- Avoid using generic text like "click here" or "read more." Instead, use descriptive text that accurately reflects the destination of the link.

- Provide clear instructions and context for interactive elements like forms and buttons. 


---

# Best practices (contd. 2)

- Use labels to identify form fields, and provide instructions or hints to help users understand how to interact with the elements.

- Use high-contrast colors for text and background, and avoid using color alone to convey meaning. 

- Consider the reading order of your content. Use heading tags (h1, h2, etc.) to create a logical reading order for your content.