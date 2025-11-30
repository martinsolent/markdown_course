# Beginner Markdown Course

## Introduction to Markdown

![Markdown logo](img/markdown-512.png)

Markdown was created by [John Gruber in 2004](https://daringfireball.net/projects/markdown/) and is a lightweight markup language that allows you to format text using simple syntax. It is commonly used for documentation, README files, blogs, and more.

### Why Use Markdown?
- Easy to learn and use
- Plain text formatting
- Compatible with various platforms
- Widely used in programming and documentation

***

### Core Markdown References

1.  **[Daring Fireball – Markdown Project](hhttps://daringfireball.net/projects/markdown/)**
    *   Introduces Markdown as a lightweight markup language for writing web content.
    *   Philosophy: readable plain text that converts to valid HTML.
    *   Syntax uses intuitive punctuation (e.g., `#` for headers, `*` for emphasis).
    *   Supports inline HTML for advanced formatting.
    *   Free, open-source under BSD-style license.

2.  **[Daring Fireball – Markdown Basics](https://daringfireball.net/projects/markdown/basics)**
    *   Quick-start guide with examples of headings, paragraphs, blockquotes, lists, and emphasis.
    *   Two header styles: Setext (`===` or `---`) and ATX (`#`).
    *   Lists: unordered (`*`, `+`, `-`) and ordered (numbers).
    *   Emphasis: `*italic*`, `**bold**`.
    *   Includes link to “Dingus” tool for live conversion. 


3.  **[Markdown Guide Website](https://www.markdownguide.org/)**
    *   Comprehensive, beginner-friendly resource.
    *   Covers **basic syntax** (headings, lists, links, images) and **extended syntax** (tables, footnotes, task lists).
    *   Includes cheat sheets and best practices.
    *   Open-source, CC BY-SA license. 

    
4.  **[GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)**
    *   Quick reference for GitHub Flavored Markdown (GFM).
    *   Includes headers, emphasis, lists, links, images, code blocks, tables, and footnotes.
    *   Shows syntax and rendered output side by side.
    *   Useful for README files and documentation. 
    


***

### GUI Markdown Generators

**[Typora (Paid, All Platforms)](https://www.typora.io/)**
    * WYSIWYG live preview (no split pane).
    * Exports to PDF, Word, HTML.
    * Supports math, diagrams, tables.
    * One-time license: $14.99.
    * Best for writers who want distraction-free editing. 

**[MarkdownPad (Free, Windows)](http://markdownpad.com)**
    * Real-time HTML preview.
    * Customizable themes and CSS.
    * Export to HTML and PDF.
    * Pro version adds advanced features like tables and auto-save



**[StackEdit (Free, Online)](https://stackedit.io/)**
    *   Browser-based editor with live preview.
    *   Sync with Google Drive, Dropbox, GitHub.
    *   Supports LaTeX, UML diagrams, and publishing to blogs.
    *   Works offline after initial load.
    

**[Markon (Free, Online)](https://metaory.github.io/markon/)**
    *   Minimalist, distraction-free Markdown editor.
    *   Focused on simplicity and local editing.
    *   Ideal for quick notes and clean UI. 
  

***

### **Extra Mentions**

[geekflare.com](https://geekflare.com/dev/best-markdown-editors/)


*   Other GUI tools: **HackMD**, **Dillinger**, **Mark Text** (open-source), **Obsidian** (knowledge management).
*   Many support extended syntax, export options, and collaboration features. 
***

## Basic Markdown Syntax

### Headings
Use `#` for headings. The number of `#` symbols determines the heading level.

# Heading 1
## Heading 2
### Heading 3

```markdown
# Heading 1
## Heading 2
### Heading 3
```



### Bold and Italics
- **Bold:** `**bold text**` or `__bold text__`
- *Italic:* `*italic text*` or `_italic text_`
- ***Bold and Italic:*** `***bold and italic text***`

### Lists
#### Unordered List:

- Item 1
- Item 2
  - Sub-item 1
  - Sub-item 2

```markdown
- Item 1
- Item 2
  - Sub-item 1
  - Sub-item 2
```
#### Ordered List:

1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2

```markdown
1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2
```

### Links

[Link Text](#)

```markdown
[Link Text](https://example.com)
```

### Images
```markdown
![Alt Text](https://example.com/image.jpg)
```

### Code Blocks
#### Inline Code:
Use backticks for `` `inline code:` `` will show: `inline code:`

#### Code Blocks:
**Instructions:** Use triple backticks for code blocks:

````markdown
```
<html>Hello World</html>
```
````
**Will display this:**

```
<html>Hello World</html>
```


**To show this:**

````markdown
```
<html>Hello World</html>
```
````

**You need to type this:**

`````markdown
````markdown
```
<html>Hello World</html>
```
````
`````

**Why 4 backticks and "markdown"?**
- **4 backticks:** When showing code that contains 3 backticks, you need to use 4 backticks (or more) to wrap the outer code block
- **"markdown":** This tells the system what language the code is written in for proper syntax highlighting





### Blockquotes
Use `>` for blockquotes:
```markdown
> This is a blockquote.
```

### Horizontal Line
Use three dashes or asterisks:
```markdown
---
```

### Commenting
In Markdown, there is no official comment syntax, but you can use HTML comments to add comments that will not be displayed in the rendered output.

### Markdown Comment Syntax:
```markdown
<!-- This is a comment in Markdown -->
```

Since Markdown supports inline HTML, anything inside `<!-- -->` will be ignored in the output.

## Advanced Markdown

### Tables

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```

### Task Lists

- [ ] Completed Task
- [x] Incomplete Task

```markdown
- [x] Completed Task
- [ ] Incomplete Task
```

### Escaping Characters
Use `\` before special characters:
```markdown
\*Not Italic\*
```
