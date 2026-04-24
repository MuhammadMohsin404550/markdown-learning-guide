# Complete Markdown Learning Guide

A comprehensive guide to learning Markdown with practical examples and code snippets. Perfect for beginners who want to master Markdown formatting!

## Table of Contents

1. [Headings](#1-headings)
2. [Block of Words (Blockquotes)](#2-block-of-words)
3. [Line Breaks](#3-line-breaks)
4. [Combining Heading and Blockquotes](#4-combining-heading-and-blockquotes)
5. [Text Formatting (Bold, Italic)](#5-text-formatting)
6. [Bullet Points and Lists](#6-bullet-points-and-lists)
7. [Horizontal Rules](#7-horizontal-rules)
8. [Links and Hyperlinks](#8-links-and-hyperlinks)
9. [Adding Images](#9-adding-images)
10. [Code and Code Blocks](#10-code-and-code-blocks)
11. [Tables](#11-tables)

---

## 1. Headings

Markdown supports 6 levels of headings using the `#` symbol:

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

Headings can only go up to 6 levels in Markdown (`#` to `######`)

---

## 2. Block of Words

Blockquotes are used to highlight special text or quotes. Use the `>` symbol:

```markdown
> This is special text in Markdown.
>
> This is second line.
```

You can use `>` on each line or leave blank lines with `>` for spacing.

---

## 3. Line Breaks

There are two methods to create line breaks:

### Method 1: Using Two Spaces at the End of a Line

```markdown
This is first line.  
This is second line.
```

### Method 2: Using Backslash (\)

```markdown
This is first line.\
This is second line.
```

Both methods create a line break without starting a new paragraph.

---

## 4. Combining Heading and Blockquotes

You can combine different elements together:

```markdown
> ## Heading 2 Inside a Blockquote
>
> This is text inside a blockquote with a heading!
```

---

## 5. Text Formatting

### Bold Text

```markdown
**Bold Text**
__Bold Text__
```

### Italic Text

```markdown
*Italic Text*
_Italic Text_
```

### Bold and Italic

```markdown
***Bold and Italic***
___Bold and Italic___
```

---

## 6. Bullet Points and Lists

### Unordered Lists

Use `-`, `*`, or `+` to create bullet points:

```markdown
- Day 1
- Day 2
- Day 3
  - Nested Item (Day 3a)
    - Sub-nested Item
- Day 4
```

### Ordered Lists

Use numbers followed by a period:

```markdown
1. Day 1
2. Day 2
3. Day 3
   1. Sub-item 3a
   2. Sub-item 3b
4. Day 4
```

---

## 7. Horizontal Rules

Create horizontal rules to separate sections using `---`, `***`, or `___`:

```markdown
This is Page 1.

---

This is Page 2.
```

---

## 8. Links and Hyperlinks

### Method 1: Inline Links

```markdown
[My LinkedIn](https://www.linkedin.com/in/muhammadmohsin404550/)
```

### Method 2: Automatic Links

```markdown
<https://www.linkedin.com/in/muhammadmohsin404550/>
```

Note: Include `https://` for proper link functionality.

### Method 3: Reference Links

```markdown
[Linkedin Profile Link]: https://www.linkedin.com/in/muhammadmohsin404550/

To see my profile [Click Here][Linkedin Profile Link]
```

---

## 9. Adding Images

### Local Images

Store images in the same folder as your Markdown file:

```markdown
![Alt Text](image.jpeg)
```

### Images from URLs

```markdown
![Alt Text]([https://example.com/image.jpg](https://media.licdn.com/dms/image/v2/D5603AQGeqr1MGZHJyA/profile-displayphoto-scale_200_200/B56Zrk_5QiLwAY-/0/1764778548643?e=1778716800&v=beta&t=UHaWXEDBDke8bhSh6TAaAk-RqafKUu9iMELqdEHty4Q))
```

Note: Always provide descriptive alt text for accessibility.

---

## 10. Code and Code Blocks

### Inline Code

Use backticks for code snippets within text:

```markdown
To print a string use `print("Hello World")`
```

### Code Blocks

Use triple backticks with language specification for syntax highlighting:

#### Python Example

```markdown
\`\`\`python
x = 5 + 6
y = 4 + 8
z = x + y
print(z)
\`\`\`
```

#### R Example

```markdown
\`\`\`r
x = 5 + 6
y = 4 + 8
z = x + y
print(z)
\`\`\`
```

#### JavaScript Example

```markdown
\`\`\`javascript
let x = 5 + 6;
let y = 4 + 8;
let z = x + y;
console.log(z);
\`\`\`
```

---

## 11. Tables

### Basic Table

```markdown
| Species | sepal_length | petal_length |
|---------|-------------|-------------|
| setosa | 5.1 | 1.4 |
| versicolor | 7.0 | 4.7 |
| virginica | 6.5 | 5.1 |
```

### Left Aligned

```markdown
| Species | sepal_length | petal_length |
|:--------|:------------|:------------|
| setosa | 5.1 | 1.4 |
| versicolor | 7.0 | 4.7 |
| virginica | 6.5 | 5.1 |
```

### Right Aligned

```markdown
| Species | sepal_length | petal_length |
|--------:|-------------|-------------|
| setosa | 5.1 | 1.4 |
| versicolor | 7.0 | 4.7 |
| virginica | 6.5 | 5.1 |
```

### Center Aligned

```markdown
| Species | sepal_length | petal_length |
|:-------:|:----------:|:----------:|
| setosa | 5.1 | 1.4 |
| versicolor | 7.0 | 4.7 |
| virginica | 6.5 | 5.1 |
```

---

## Tips and Best Practices

1. Always use consistent formatting - Choose one style for bold/italic and stick with it
2. Use proper alt text - Make images accessible for screen readers
3. Include code language - Specify language in code blocks for syntax highlighting
4. Use headers hierarchically - Don't skip heading levels
5. Test your markdown - Preview before publishing
6. Use blockquotes for emphasis - Highlight important notes and tips

---

## Additional Resources

- GitHub Markdown Guide: https://guides.github.com/features/mastering-markdown/
- CommonMark Specification: https://spec.commonmark.org/
- Markdown Cheat Sheet: https://www.markdownguide.org/cheat-sheet/

---

## Contributing

Feel free to add more examples or improve this guide! You can create issues or submit pull requests with improvements.

---

Happy Learning! Master Markdown and create beautiful documentation.
