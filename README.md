# Beginner Markdown Course

## Introduction to Markdown

![Markdown logo](img/markdown-512.png)

Markdown was created by [John Gruber in 2004](https://daringfireball.net/projects/markdown/) and is a lightweight markup language that allows you to format text using simple syntax. It is commonly used for documentation, README files, blogs, and more.

### Why Use Markdown?
- Easy to learn and use
- Plain text formatting
- Compatible with various platforms
- Widely used in programming and documentation

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
