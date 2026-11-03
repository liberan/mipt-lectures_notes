```tikz
%x
\begin{document}
\begin{tikzpicture}[scale=2.4, >=stealth]
 %Декартова система
 \draw[->, very thick] (-0.2,0) -- (5.4,0);
 \draw[<-, very thick] (1,2.4) -- (1,-1.2);
 \draw[very thick] (0,-0.05) -- (0,0.05);
 \draw[very thick] (2,-0.05) -- (2,0.05);
 \draw[very thick] (3,-0.05) -- (3,0.05);
 \draw[very thick] (4,-0.05) -- (4,0.05);
 \draw[very thick] (5,-0.05) -- (5,0.05);
 \draw[very thick] (0.95,1) -- (1.05,1);
 \draw[very thick] (0.95,2) -- (1.05,2);
 \draw[very thick] (0.95,-1) -- (1.05,-1);
 \fill (0,0) circle (1pt) node[below] {$-1$};
\end{tikzpicture}
\end{document}
```