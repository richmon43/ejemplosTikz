---
title: "Tikz Galleria"
author: "Richar Mora"
output:
  html_document:
    css: style.css
    keep_md: true
    toc: true
    number_sections: false
---

Esta es una colección de graficos usando el paquete Tikz, la galería oficial se puede encontrar en [TeXample.net](http://www.texample.net/tikz/examples/), pero hay varios aportes de usuarios que se han propuesto mostrarlos usando esta libreria que se ha vuelto muy popular entre la comunidad de LaTeX.

****

![](./img/fig02.pdf)

  * [fig01.pdf](https://github.com/richmon43/ejemplosTikz/blob/master/tikz/fig01.pdf)

```tex
\begin{tikzpicture}
  \draw[blue] (0, 0) -- (4, 0);
  \draw[blue] (0, 0) -- (-3, -3);
  \draw[blue] (0, 0) -- (0, 4);
  \draw[red] (0, 0) circle (3cm);
  \draw[blue] (-3, 0) arc(-180:0:3cm and 1cm);
  \draw[blue, dashed] (3, 0) arc (0:180: 3cm and 1cm);
  \node[fill = green, green, circle, draw, inner sep = 1pt] (A) at (210:3) {};
  \node[fill = green, green, circle, draw, inner sep = 1pt] (B) at (60:3) {};
  \node[fill = green, green, circle, draw, inner sep = 1pt] (C) at (120:3cm and 1cm) {};
  \draw[color = green, dashed] (A) node[below left, black] {$-f(x)$} -- (B) node[right, black] {$f(x)$} -- (C) node[above, black] {$g(x)$};
\end{tikzpicture}
```
****

![](./img/fig02.jpg)

  * [fig02.tikz](https://github.com/richmon43/ejemplosTikz/blob/master/tikz/fig01.tikz)

```tex
\begin{tikzpicture}
  \draw[blue] (0, 0) -- (4, 0);
  \draw[blue] (0, 0) -- (-3, -3);
  \draw[blue] (0, 0) -- (0, 4);
  \draw[red] (0, 0) circle (3cm);
  \draw[blue] (-3, 0) arc(-180:0:3cm and 1cm);
  \draw[blue, dashed] (3, 0) arc (0:180: 3cm and 1cm);
  \node[fill = green, green, circle, draw, inner sep = 1pt] (A) at (210:3) {};
  \node[fill = green, green, circle, draw, inner sep = 1pt] (B) at (60:3) {};
  \node[fill = green, green, circle, draw, inner sep = 1pt] (C) at (120:3cm and 1cm) {};
  \draw[color = green, dashed] (A) node[below left, black] {$-f(x)$} -- (B) node[right, black] {$f(x)$} -- (C) node[above, black] {$g(x)$};
\end{tikzpicture}
```
****
