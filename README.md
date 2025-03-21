# Beginner Markdown Course

## Introduction to Markdown

![Markdown logo](img/markdown-512.png)

![link_to_gitHub_example](github_profile_img/link_to_gitHub_example.png)

Markdown was created by [John Gruber in 2004](https://daringfireball.net/projects/markdown/) and is a lightweight markup language that allows you to format text using simple syntax. It is commonly used for documentation, README files, blogs, and more.

### Why Use Markdown?
- Easy to learn and use
- Plain text formatting
- Compatible with various platforms
- Widely used in programming and documentation

## Basic Markdown Syntax

### Headings
Use `#` for headings. The number of `#` symbols determines the heading level.
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
```markdown
- Item 1
- Item 2
  - Sub-item 1
  - Sub-item 2
```
#### Ordered List:
```markdown
1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2
```

### Links
```markdown
[Link Text](https://example.com)
```

### Images
```markdown
![Alt Text](https://example.com/image.jpg)
```

### Code Blocks
#### Inline Code:
Use backticks (`) for inline code: `` `inline code` ``

#### Code Blocks:
Use triple backticks for code blocks:

```
<html>Hello World</html>
```


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
```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```

### Task Lists
```markdown
- [x] Completed Task
- [ ] Incomplete Task
```

### Escaping Characters
Use `\` before special characters:
```markdown
\*Not Italic\*
```