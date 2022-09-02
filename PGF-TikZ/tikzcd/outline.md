# tikzcd ouline
## getting started
To load this package in $\LaTeX$, type
```tex
\usepackage{tikz-cd}
```
### Creating a diagram
```tex
\begin{tikzcd}[<options>]
<environment contents>
\end{tikzcd}
```
### Inserting arrows
Inside the {tikzcd} environment, the following synonymous commands are provided to produce arrows.
```tex
\arrow[<options>]
\ar[<options>]
```
#### example
```tex
\begin{tikzcd}                                    
 A \arrow[rd] \arrow[r, "\phi"] & B  \\
				& C
\end{tikzcd}                                      

```
tikzcd는 array 사이에 arrow를 그리는 macro?
