# Markdown Cheat Sheet

## Table of contents

* [Basic Syntax](#basic-syntax)
  + [Headings](#headings)
  + [Paragraphs](#paragraphs)
  + [Line Breaks](#line-breaks)
  + [Emphasis](#emphasis)
  + [Blockquotes](#blockquotes)
  + [Lists](#lists)
  + [Code](#code)
  + [Code Blocks](#code-blocks)
  + [Horizontal Rule](#horizontal-rule)
  + [Link](#link)
  + [Image](#image)
  + [Escaping Characters](#escaping-characters)
* [Extended Syntax](#extended-syntax)
  + [Table](#table)
  + [Fenced Code Block](#fenced-code-block)
  + [Footnote](#footnote)
  + [Superscript](#superscript)
  + [Subscript](#subscript)
  + [Heading ID](#heading-id)
  + [Definition List](#definition-list)
  + [Strikethrough](#strikethrough)
  + [Task List](#task-list)
  + [Emoji](#emoji)
* [References](#references)

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
Here's a sentence with a footnote 1. [^1]
Here's a sentence with a footnote 2. [^2]

[^1]: This is the footnote 1.
[^2]: This is the footnote 2.
```

```html
Here's a sentence with a footnote 1. <sup id="sup1">[[1]](#footnote1)</sup>
Here's a sentence with a footnote 2. <sup id="sup2">[[2]](#footnote2)</sup>

<!-- footer -->

***

<span id="footnote1">1</span>: This is the footnote 1. [↩](#sup1)
<span id="footnote2">2</span>: This is the footnote 2. [↩](#sup2)
```

Here's a sentence with a footnote 1. <sup id="sup1">[[1]](#footnote1)</sup>  
Here's a sentence with a footnote 2. <sup id="sup2">[[2]](#footnote2)</sup>

### Superscript

```md
(x + 1)^2^ = x^2^ + 2x + 1
```

```html
(x + 1)<sup>2</sup> = x<sup>2</sup> + 2x + 1
```

(x + 1)<sup>2</sup> = x<sup>2</sup> + 2x + 1

### Subscript

```md
y = log~2~(x)
```

```html
y = log<sub>2</sub>(x)
```

y = log<sub>2</sub>(x)

### Heading ID

```md
#### My Great Heading {#heading-id}

[Heading ID](#heading-id)
```

#### My Great Heading {#heading-id}

[Heading ID](#heading-id)

### Definition List

```md
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

```html
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>

### Strikethrough

```md
~~The world is flat.~~
```

~~The world is flat.~~

### Task List

```md
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

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

***

<span id="footnote1">1</span>: This is the footnote 1. [&#8617;](#sup1)  
<span id="footnote2">2</span>: This is the footnote 2. [&#8617;](#sup2)