# Galería de ejemplos con Tikz

****
![](./img/arcosCirculos.png)

  * [arcosCirculos.pgf](https://github.com/richmon43/ejemplosTikz/blob/master/img/arcosCirculos.pgf)

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
  \draw[color = green, dashed] (A) node[below left, black] {$-f(x)$} -- %
    (B) node[right, black] {$f(x)$} -- (C) node[above, black] {$g(x)$};
\end{tikzpicture}
```

****