# Markdown Cheat Sheet

## Basic Syntax

### Headings

```md
# Heading level 1

Heading level 1
===============

## Heading level 2

Heading level 2
---------------

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6
```

```html
<h1>Heading level 1</h1>

<h1>Heading level 1</h1>

<h2>Heading level 2</h2>

<h2>Heading level 2</h2>

<h3>Heading level 3</h3>

<h4>Heading level 4</h4>

<h5>Heading level 5</h5>

<h6>Heading level 6</h6>
```

# Heading level 1

Heading level 1
===============

## Heading level 2

Heading level 2
---------------

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

### Paragraphs

```md
I really like using Markdown.

I think I'll use it to format all of my documents from now on.
```

```html
<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>
```

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

### Line Breaks

To create a line break (`<br>`), end a line with two or more spaces, and then type return.

```md
This is the first line.  
And this is the second line.
```

```html
<p>This is the first line.<br>
And this is the second line.</p>
```

This is the first line.  
And this is the second line.

### Emphasis

#### Bold

```md
**bold text**

__bold text__
```

```html
<strong>bold text</strong>

<strong>bold text</strong>
```

**bold text**

__bold text__

#### Italic

```md
*italicozed text*

_italicozed text_
```

```html
*italicozed text*

_italicozed text_
```

*italicozed text*

_italicozed text_

#### Bold and Italic

```md
This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.
```

```html
This text is <strong><em>really important</em></strong>.

This text is <strong><em>really important</em></strong>.

This text is <strong><em>really important</em></strong>.

This text is <strong><em>really important</em></strong>.
```

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

### Blockquotes

```md
> blockquote
```

> blockquote

#### Blockquotes with Multiple Paragraphs

```md
> Blockquotes with Multiple Paragraphs
>
> Blockquotes with Multiple Paragraphs
```

> Blockquotes with Multiple Paragraphs
>
> Blockquotes with Multiple Paragraphs

#### Nested Blockquotes

```md
> Nested Blockquotes
>
>> Nested Blockquotes
```

> Nested Blockquotes
>
>> Nested Blockquotes

#### Blockquotes with Other Elements

```md
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

### Lists

#### Ordered List

```md
1. First Item
2. Second Item
3. Third Item
```

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

1. First Item
2. Second Item
3. Third Item

#### Unordered List

```md
- First Item
- Second Item
- Third Item
```

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

- First Item
- Second Item
- Third Item

### Code

```md
`code`
```

`code`

### Code Blocks

indent every line of the block by at least four spaces or one tab.

```md
    <html>
      <head>
      </head>
    </html>
```

    <html>
      <head>
      </head>
    </html>

### Horizontal Rule

```md
***

---

_________________
```

***

---

_________________

### Link

```md
[link](https://www.example.com)
```

[link](https://www.example.com)

### Image

```md
![alt text](image.jpg)
```

<img width="30%" src="image.png" alt="alt text"></img>

### Escaping Characters

```md
\* Without the backslash, this would be a bullet in an unordered list.
```

\* Without the backslash, this would be a bullet in an unordered list.

## Extended Syntax

Not all Markdown applications support extended syntax elements.

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

#### Alignment

```md
| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |
```

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

### Fenced Code Block

<pre>
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
</pre>

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

### Emoji

```md
:smile:
:laughing:
:stuck_out_tongue_closed_eyes:
```

:smile:
:laughing:
:stuck_out_tongue_closed_eyes:

## References

[Markdown Guide](https://www.markdownguide.org/)