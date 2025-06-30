# Comprehensive Markdown Template

## Table of Contents
- [Headings](#headings)
- [Text Formatting](#text-formatting)
- [Lists](#lists)
- [Tables](#tables)
- [Links and Images](#links-and-images)
- [Code](#code)
- [Blockquotes](#blockquotes)
- [Horizontal Rules](#horizontal-rules)

## Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Text Formatting

This is **bold text** and this is *italic text*.

You can also use __bold__ and _italic_ with underscores.

This is ***bold and italic*** text.

~~This text is strikethrough~~

This is `inline code`.

## Lists

### Unordered Lists
- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
    - Double nested item
- Item 3

### Ordered Lists
1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item

### Task Lists
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task

## Tables

| Name | Age | City | Occupation |
|------|-----|------|------------|
| John Doe | 30 | New York | Developer |
| Jane Smith | 25 | London | Designer |
| Bob Johnson | 35 | Tokyo | Manager |

### Table with Alignment

| Left Aligned | Center Aligned | Right Aligned |
|:-------------|:--------------:|--------------:|
| Left | Center | Right |
| Text | Text | Text |
| More | More | More |

## Links and Images

### Links
- [External link](https://www.example.com)
- [Link with title](https://www.example.com "Example Website")
- [Reference link][reference]
- [Internal link](#headings)

[reference]: https://www.example.com

### Images
![Alt text for image](https://via.placeholder.com/150x100 "Image Title")

## Code

### Inline Code
Use the `print()` function to display output.

### Code Blocks

```python
def hello_world():
    print("Hello, World!")
    return "Success"

# Call the function
result = hello_world()
```

```javascript
function greetUser(name) {
    console.log(`Hello, ${name}!`);
    return true;
}

greetUser("World");
```

```bash
# Shell commands
ls -la
cd /path/to/directory
echo "Hello from terminal"
```

## Blockquotes

> This is a blockquote.
> It can span multiple lines.

> ### Blockquote with heading
> This blockquote contains a heading and **formatted text**.
> 
> > This is a nested blockquote.

## Horizontal Rules

---

***

___

## Additional Features

### Line Breaks
This is the first line.  
This is the second line (two spaces at end of previous line).

This is a new paragraph.

### Escape Characters
\*This text is not italic\*
\`This is not code\`

### HTML Elements (if supported)
<details>
<summary>Click to expand</summary>

This content is hidden by default and can be expanded.

</details>

### Footnotes
This text has a footnote[^1].

[^1]: This is the footnote content.

### Definition Lists
Term 1
: Definition 1

Term 2
: Definition 2a
: Definition 2b

---

*This template demonstrates the most commonly used markdown features. Not all markdown parsers support every feature shown above.*