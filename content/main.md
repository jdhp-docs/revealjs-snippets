<!---
This is a comment block.
-->

## About Reveal.js

Official ressources:
* https://github.com/hakimel/reveal.js
* http://lab.hakim.se/reveal-js/
* [Some examples](https://github.com/hakimel/reveal.js/tree/master/test)

Some slides are taken from the
[Reveal.js official demo](http://lab.hakim.se/reveal-js/)
(by Hakim El Hattab)

---

## About this demo

* [Source code](https://github.com/jdhp-docs/revealjs-snippets)
* [Online version](http://www.jdhp.org/docs/revealjs_snippets/main.html)

---

## Fullscreen

Press `f` to switch to the full screen mode.

Press `Escape` to quit full screen mode.

---

## Overview mode

Press `ESC` or `o` to enter the slide overview.

Hold down alt and click on any element to zoom in on it using zoom.js.
Alt + click anywhere to zoom back out.

---

## Speaker View

There's a speaker view. It includes a timer, preview of the upcoming slide as
well as your speaker notes.

Press the `S` key to try it out.

With some browers, it may not work at the first
attempt... If it's your case, be sure your browser
accept the popup and press several times on the
's' key...

~~

Here are speaker notes...

---

## Vertical slides

Use the Space key to navigate through all slides

Hello

--

## Vertical slides

How

--

## Vertical slides

Are

--

## Vertical slides

You ?

---

## Emphasis

Emphasis (aka italics): with *asterisks* or _underscores_

Strong emphasis (aka bold): with **asterisks** or __underscores__

Combined emphasis: with **asterisks and _underscores_**

Strikethrough: with two tildes ~~scratch this~~

---

## Horizontal rule

Hello

***

World

---

## Blockquotes

As Descartes said:

> Cogito,
> ergo sum

---

## Unordered lists

- Item 1
  - Unordered subitem 1
  - Unordered subitem 2
- Item 2
  1. Ordered subitem 1
  2. Ordered subitem 2
- Item 3

---

## Ordered lists

1. Item 1
  - Unordered subitem 1
  - Unordered subitem 2
2. Item 2
  1. Ordered subitem 1
  2. Ordered subitem 2
3. Item 3

---

## Links

[JDHP](http://www.jdhp.org)

---

## SVG images (1:1)

![Logo](figs/logos/python/python.svg)

---

## SVG images (width=300px)

<img src="figs/logos/python/python.svg" width="300">

---

## SVG images (width=100%)

<img src="figs/logos/python/python.svg" width="100%">

---

## SVG images (height=100%)

<img src="figs/logos/python/python.svg" height="100%">

---

## PNG images (1:1)

![Logo](figs/plot2d.py.png)

---

## PNG images (width=300px)

<img src="figs/plot2d.py.png" width="300">

---

## PNG images (width=50%)

<img src="figs/plot2d.py.png" width="50%">

---

## PNG images (height=100%)

<img src="figs/plot2d.py.png" height="100%">

---

## Maths

Inline maths with `$\LaTeX$` : `$x \lt y$` 

`\(\int_a^b f(x)dx\)`

`$$\int_a^b f(x)dx$$`

`$$V(x) = \max_{a \in \Gamma (x) } \{ F(x,a) + \beta V(T(x,a)) \}$$`

---

## Maths

### Equation array

`$$
\begin{eqnarray*}
    \mbox{Expectation of N} & = & \sum_{i=1}^{n} \mathbb{E}(Z_i) \\
                            & = & \sum_{i=1}^{n} \frac{\gamma}{d^{\beta/2}} \frac{ c(d)^\beta }{i^{\alpha\beta}} \\
                            & = & \frac{\gamma}{d^{\beta/2}} c(d)^\beta \sum_{i=1}^{n} \frac{1}{i^{\alpha\beta}} \\
                            & = & z
\end{eqnarray*}
$$`

---

## Maths

### Arrays

`$$
\begin{array}{cc}
  a & b \\
  c & c
\end{array}
$$`

---

## Maths

### Matrices

`$$
A=
\begin{pmatrix}
    a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
    a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
    \vdots  & \vdots  & \ddots & \vdots  \\
    a_{m,1} & a_{m,2} & \cdots & a_{m,n}
\end{pmatrix}
$$`

---

## Maths

### Matrices

`$$
A=
\begin{bmatrix}
    a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
    a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
    \vdots  & \vdots  & \ddots & \vdots  \\
    a_{m,1} & a_{m,2} & \cdots & a_{m,n}
\end{bmatrix}
$$`

---

## Maths

### Mathematical programming

`$$
\begin{align}
    \max        & \quad z = 4 x_1 + 7 x_2    \notag \\
    \text{s.t.} & \quad 3 x_1 + 5 x_2 \leq 6 \label{constraint1}\\
                & \quad   x_1 + 2 x_2 \leq 8 \label{constraint2}\\
                & \quad   x_1, x_2 \geq 0    \notag
\end{align}
$$`

---

## Maths

### Systems of equation array

`$$
f(n) = \left\{
\begin{array}{ll}
    n/2      & \text{if $n$ is even} \\
    -(n+1)/2 & \text{if $n$ is odd}
\end{array} \right.
$$`

---

## `$\LaTeX$` fonts

### mathbb

`$$
\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`

### mathbf

`$$
\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathbf{abcdefghijklmnopqrstuvwxyz}
$$`

### mathtt

`$$
\mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathtt{abcdefghijklmnopqrstuvwxyz}
$$`

---

## `$\LaTeX$` fonts

### mathrm

`$$
\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathrm{abcdefghijklmnopqrstuvwxyz}
$$`

### mathsf

`$$
\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathsf{abcdefghijklmnopqrstuvwxyz}
$$`

---

## `$\LaTeX$` fonts

### mathcal

`$$
\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathcal{abcdefghijklmnopqrstuvwxyz}
$$`

### mathfrak

`$$
\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}
$$`
`$$
\mathfrak{abcdefghijklmnopqrstuvwxyz}
$$`

---

## Algorithms

<img src="figs/algo.tex.png" width="75%">

---

## Source code

Python:
```python
for text in ("Hello", "world"):
    print(text)
```

Shell:
```sh
echo "Hello world"
```

C:
```c
printf("%s", "Hello world\n");
```

Code syntax highlighting courtesy of [highlight.js](http://softwaremaniacs.org/soft/highlight/en/description/)

---

## Verbatim

<pre>

         .--.
        |o_o |
        |:_/ |
       //   \ \
      (|     | )
      /'\_   _/`\
      \___)=(___/

</pre>

---

## Inline code

Inline `code` has `back-ticks around` it.

---

## Tables

| Title 1        | Title 2        | Title 3        |
| -------------- |:--------------:| --------------:|
| This column is | This column is | This column is |
| right-aligned  | centered       | left-aligned   |
| 1              | 1              | 1              |
| *2*            | ~~2~~          | 2              |
| **3**          | 3              | 3              |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional ([source](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).

---

## Inline HTML

<dl>
    <dt>Foo</dt>
    <dd>blablabla</dd>

    <dt>Bar</dt>
    <dd>blablabla</dd>
</dl>
