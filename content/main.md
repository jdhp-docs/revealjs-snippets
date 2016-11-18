<!---
This is a comment block.
-->

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

There's a speaker view. It includes a timer, preview of the upcoming slide as well as your speaker notes.

Press the `S` key to try it out.

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

## Images

![Logo](figs/logos/python/python.svg)

<img src="figs/logos/python/python.svg" width="300">

---

## Maths

Inlin maths: $x \lt y$

`\(\int_a^b f(x)dx\)`

$$\int_a^b f(x)dx$$

$$V(x) = \max_{a \in \Gamma (x) } \{ F(x,a) + \beta V(T(x,a)) \}$$ 

---

## Maths

Equation array:
$$
\\begin{eqnarray}
    y & = & \cos(x) \\\\
      & = & \sin \left\( x + \frac{\pi}{2} \right\) \\\\
\\end{eqnarray}
$$

Matrices:
$$
\\begin{array}{cc}
  a & b \\\\
  c & c
\\end{array}
$$

Systems of equation array:
$$
f(n) = \\left\\{
\\begin{array}{ll}
    n/2      & \\text{if $n$ is even}\\\\
    -(n+1)/2 & \\text{if $n$ is odd}
\\end{array} \\right.
$$

See [there](http://stackoverflow.com/questions/18860693/mathjax-multi-line-equation-rendering-issue#comment27933447_18860693) and
and [there](http://docs.mathjax.org/en/latest/tex.html#tex-and-latex-in-html-documents) for explanations about the doubled slashes

---

## Code

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
