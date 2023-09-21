---
marp: true
theme: unibe
size: 16:9
paginate: true
footer: ''
header: '![ ]() [&#9635;](#1 "")'
---

# Headline
### Author(s)
Location, Date

<!-- deckslide only style -->
<style scoped>
  /* centered headline */
  section {justify-content: center;}
  /* display header image */
  header img {display: block;}
</style>

---

## Section 1

Math
$$
\mathbf{A} \mathbf{x} = \mathbf{b}; \quad
\mathbf{A} =
\begin{bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
\end{bmatrix}
; \quad
\mathbf{x} = 
\begin{bmatrix}
x_1 \\
x_2 \\
\end{bmatrix}
; \quad
\mathbf{b} =
\begin{bmatrix}
b_{1} \\
b_{2} \\
\end{bmatrix}
$$

Code
```python
for x in "banana":
  print(x)
```

Table - https://www.tablesgenerator.com/markdown_tables
| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |

---

## Section 2

- `...` from surrounded backticks ```...```
- *italic* from `*italic*`
- **bold** from `**bold**`
- ~~strikethrough~~ from `~~strikethrough~~`
- > blockquote from `>`
- [source link](https://www.website.com) from `[source link](http://www.website.com)`
- and some fancy emojis :shit: from `:shit:` using words surrounded by colons

an emoji compilation for markdown is found below

https://gist.github.com/rxaviers/7360908

---

## HTML/CSS flavour

<style scoped>
  p, ul, li, blockquote{
    font-size: 78%;
  }
</style>

<style scoped>
  header img {
    display: block;
  }
</style>

<style scoped>
    section {
        display: block;
    }
    table {
        width: max-content;
        float: right;
    }
</style>

<br>

##### add header image on this slide:
```html
<style scoped>
  header img {
    display: block;
  }
</style>
```

<br>

##### set font-size for this slide:
```html
<style scoped>
  p, ul, li, blockquote, code{
    font-size: 78%;
  }
</style>
```
