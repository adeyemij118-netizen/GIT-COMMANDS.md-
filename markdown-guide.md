# Markdown Syntax Guide

Markdown is a lightweight markup language used to format text. Files containing Markdown commonly use the `.md` extension.

## 1. Headings

Use the `#` symbol to create headings. The number of `#` symbols determines the heading level.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

Rendered result:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

---

## 2. Paragraphs

Write normal text as a paragraph. Leave a blank line between paragraphs.

```markdown
This is the first paragraph.

This is the second paragraph.
```

---

## 3. Bold and Italic Text

### Bold

Use two asterisks or two underscores around text:

```markdown
**This text is bold**
__This text is also bold__
```

### Italic

Use one asterisk or one underscore:

```markdown
*This text is italic*
_This text is also italic_
```

### Bold and italic

```markdown
***This text is bold and italic***
```

---

## 4. Ordered Lists

Use numbers followed by a period.

```markdown
1. Install Git
2. Create a repository
3. Add your files
4. Commit your changes
```

Rendered result:

1. Install Git
2. Create a repository
3. Add your files
4. Commit your changes

---

## 5. Unordered Lists

Use `-`, `*`, or `+` to create bullet points.

```markdown
- Git
- GitHub
- Markdown
- Visual Studio Code
```

Rendered result:

- Git
- GitHub
- Markdown
- Visual Studio Code

### Nested list

```markdown
- Frontend
  - HTML
  - CSS
  - JavaScript
- Backend
  - Go
  - PostgreSQL
```

---

## 6. Links

Use the following syntax:

```markdown
[GitHub](https://github.com)
```

Rendered result:

[GitHub](https://github.com)

---

## 7. Images

Use an exclamation mark followed by the image's alternative text and URL:

```markdown
![Git Logo](https://example.com/git-logo.png)
```

The general syntax is:

```text
![Alternative text](image-url)
```

---

## 8. Code Blocks

Use three backticks before and after a block of code.

### Without a language

````markdown
```
git status
git add .
git commit -m "Initial commit"
```
````

### With syntax highlighting

Specify the programming language immediately after the opening backticks.

````markdown
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
````

---

## 9. Tables

Use pipes (`|`) to create columns and hyphens (`-`) to separate the header from the table body.

```markdown
| Command | Description |
|---------|-------------|
| git init | Creates a repository |
| git status | Shows repository status |
| git commit | Saves staged changes |
```

Rendered result:

| Command | Description |
|---------|-------------|
| `git init` | Creates a repository |
| `git status` | Shows repository status |
| `git commit` | Saves staged changes |

---

## 10. Blockquotes

Use the `>` symbol.

```markdown
> This is a blockquote.
```

Rendered result:

> This is a blockquote.

You can create multiple lines:

```markdown
> Git is a distributed version control system.
> It helps developers track changes to their code.
```

---

## 11. Horizontal Lines

Use three or more hyphens, asterisks, or underscores.

```markdown
---
```

Rendered result:

---

You can also use:

```markdown
***
```

or:

```markdown
___
```

---

## Quick Reference

| Syntax | Purpose |
|--------|---------|
| `# Heading` | Heading |
| `**text**` | Bold |
| `*text*` | Italic |
| `1. item` | Ordered list |
| `- item` | Unordered list |
| `[text](url)` | Link |
| `![alt](url)` | Image |
| `` `code` `` | Inline code |
| `> quote` | Blockquote |
| `---` | Horizontal line |
| ` ``` ` | Code block |
| `\|` | Table separator |
