# Markdown Cheat Sheet

## Basic Syntax

### Heading

```md
# H1

## H2

### H3

#### H4

##### H5

###### H6
```

# H1

## H2

### H3

#### H4

##### H5

###### H6

### Bold

```md
**bold text**
```

**bold text**

### Italic

```md
_italicozed text_
```

_italicozed text_

### Blockquote

```md
> blockquote
```

> blockquote

### Ordered List

```md
1. First Item
2. Second Item
3. Third Item
```

1. First Item
2. Second Item
3. Third Item

### Unordered List

```md
- First Item
- Second Item
- Third Item
```

- First Item
- Second Item
- Third Item

### Code

```md
`code`
```

`code`

### Horizontal Rule

```md
---
```

---

### Link

```md
[title](https://www.example.com)
```

[title](https://www.example.com)

### Image

```md
![alt text](image.jpg)
```

<img width="30%" src="image.png" alt="alt text"></img>

## Extended Syntax

### Table

```md
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Fenced Code Block

```md
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

```md
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

```md
#### My Great Heading {#heading-id}

[Heading ID](#heading-id)
```

#### My Great Heading {#heading-id}

[Heading ID](#heading-id)

### Definition List

```md
term
: definition
```

term
: definition

### Strikethrough

```md
~~The world is flat.~~
```

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media