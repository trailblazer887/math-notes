## 第三章 微分中值定理及其应用
1. 可导 $\ne$ 导函数连续\
例如
$$
f(x) =
\begin{cases}
x^2 sin(\frac{1}{x}) & x \ne 0 \\
0 & x = 0
\end{cases}
$$
此时$f_{+}(0) = f_{-}(0) = f(0)$，即$f(x)$在 $0$ 处可导\
但是其导函数
$$
f(x) = 
\begin{cases}
2x sin(\frac{1}{x}) - cos(\frac{1}{x}) & x \ne 0 \\
0 & x = 0
\end{cases}
$$
在趋近于 $0$ 时， $lim_{x \to 0}{f(x)}$ 却不存在(**上下震荡**)，即导函数在 $0$ 处不连续