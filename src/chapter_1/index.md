# Introduction to Vectors

线性代数的核心是两个运算——均作用于向量。向量相加得到 \\(\boldsymbol{v}+\boldsymbol{w}\\)。与数字 \\(c\\) 和 \\(d\\) 分别相乘得到 \\(c \boldsymbol{v}\\) 和 \\(d \boldsymbol{w}\\)。组合两种运算 (\\(c \boldsymbol{v}\\) 与 \\(d \boldsymbol{w}\\) 相加) 得到 ***线性组合*** \\(c \boldsymbol{v} + d \boldsymbol{w}\\)。

> **线性组合** \\(\qquad c\boldsymbol{v}+d\boldsymbol{w}=c \begin{bmatrix}1\\\\1\end{bmatrix}+d \begin{bmatrix}2\\\\3\end{bmatrix}=\begin{bmatrix}c+2d\\\\c+3d\end{bmatrix}\\)

**例子**\\(\qquad \boldsymbol{v}+\boldsymbol{w}=\begin{bmatrix}1\\\\1\end{bmatrix}+\begin{bmatrix}2\\\\3\end{bmatrix}=\begin{bmatrix}3\\\\4\end{bmatrix}是\ c=d=1\ 时的线性组合\\)

线性组合在这个主题中非常重要！有时我们想要一个特定的组合，选取 \\(c=2\\) 和 \\(d=1\\) 将会得到 \\(c \boldsymbol{v}+d \boldsymbol{w}=(4,\ 5)\\)。其他时候我们想要 \\(\boldsymbol{v}\\) 和 \\(\boldsymbol{w}\\) 的*所有线性组合* (通过 \\(c\\) 和 \\(d\\) 所有的取值)。

\\(c\boldsymbol{v}\\) 生成的所有向量均位于一条直线上。当 \\(w\\) 不在该直线上时, \\(c \boldsymbol{v}+d \boldsymbol{w}\\) 的**线性组合**将**充满整个二维平面**。 给定四维空间的四个向量 \\(\boldsymbol{u},\boldsymbol{v},\boldsymbol{w},\boldsymbol{z}\\)，其线性组合 \\(c \boldsymbol{u}+d \boldsymbol{v}+e \boldsymbol{w}+f \boldsymbol{z}\\) 可能填满整个空间——但不总是如此。这些向量及其线性组合也可能位于一个平面或一条直线上。

第一章解释了这些中心思想，之后的一切都建立在这些思想之上。我们从二维和三维向量开始，它们画起来是容易理解的，然后我们转向更高的维度。线性代数真正深刻的特点是它能够十分自然的拓展到 \\(n\\) 维空间。你心中关于线性代数的图像完全正确，尽管绘制十维向量是不可能的。

本章是梦开始的地方 (进入 \\(n\\) 维线性空间)。首先是 1.1 和 1.2 节的向量运算，然后 1.3 节概述了三个基本思想。

[***1.1 向量加法 \\(\boldsymbol{v}+\boldsymbol{w}\\) 及线性组合 \\(c \boldsymbol{v}+d \boldsymbol{w}\\)。***](./section_1.md)

[***1.2 两个向量的点积 \\(\boldsymbol{v} \cdot \boldsymbol{w}\\) 及长度 \\(||\boldsymbol{v}||=\sqrt{\boldsymbol{v} \cdot \\boldsymbol{v} }\\)。***](./section_2.md)

[***1.3 矩阵 \\(A\\)，线性方程组 \\(A \boldsymbol{x}=\boldsymbol{b}\\)，解 \\(\boldsymbol{x}=A^{-1}\boldsymbol{b}\\)。***](./section_3.md)

