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

  * [fig02.tikz](https://github.com/richmon43/ejemplosTikz/tree/master/img/fig02.tikz)

```tex
\begin{tikzpicture}
  \begin{axis}[xlabel={Abril 2021}, ylabel={unidades}, grid=major, legend entries={$y=a$,$y=b$,$y=c$,$y=d$}, legend style={font=\footnotesize, rounded corners=2pt, at={(0.3,0.95)}}]
    \addplot table [x=dia, y=a, col sep=comma] {fig02.csv};
    \addplot table [x=dia, y=b, col sep=comma] {fig02.csv};
    \addplot table [x=dia, y=c, col sep=comma] {fig02.csv};
    \addplot table [x=dia, y=d, col sep=comma] {fig02.csv};
  \end{axis}
\end{tikzpicture}
```
****

![](./img/fig01.pdf)

  * [fig02.tikz](https://github.com/richmon43/ejemplosTikz/tree/master/img/fig01.tikz)

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
