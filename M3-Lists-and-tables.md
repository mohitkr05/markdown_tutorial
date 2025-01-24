---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

# Module 3

## Lists & Tables

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
## Definition Lists

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
