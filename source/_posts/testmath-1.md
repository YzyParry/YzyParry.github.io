---
title: testmath
date: 2025-04-01 20:29:28
tags:
mathjax: true
---

看起来用 [mathjax](https://www.mathjax.org/) 就可以渲染数学公式了

需要 `npm install hexo-filter-mathjax`，然后在标题信息里备注 `mathjax: true`

$$
\begin{align}
A=\left[\begin{matrix}
\alpha&l^T\\
l&\widetilde{A}
\end{matrix}\right]&=
\left[\begin{matrix}
\sqrt \alpha&0\\
\frac{l}{\sqrt\alpha}&I_{n-1}
\end{matrix}\right]
\left[\begin{matrix}
1&0\\
0&\widetilde{A}-\frac{ll^T}{\sqrt{\alpha}}
\end{matrix}\right]
\left[\begin{matrix}
\sqrt\alpha&\frac{l^T}{\sqrt\alpha}\\
0&I_{n-1}
\end{matrix}\right]\\
&=
\left[\begin{matrix}
\sqrt \alpha&0\\
\frac{l}{\sqrt\alpha}&I_{n-1}
\end{matrix}\right]
\left[\begin{matrix}
1&0\\
0&\widetilde{L}
\end{matrix}\right]
\left[\begin{matrix}
1&0\\
0&\widetilde{L}^T
\end{matrix}\right]
\left[\begin{matrix}
\sqrt\alpha&\frac{l^T}{\sqrt\alpha}\\
0&I_{n-1}
\end{matrix}\right]\\
&=
\left[\begin{matrix}
\sqrt \alpha&0\\
\frac{l}{\sqrt\alpha}&\widetilde{L}
\end{matrix}\right]
\left[\begin{matrix}
\sqrt\alpha&\frac{l^T}{\sqrt\alpha}\\
0&\widetilde{L}^T
\end{matrix}\right]\\
\end{align}
$$
