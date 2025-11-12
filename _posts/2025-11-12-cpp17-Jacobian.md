---
title: "雅可比矩阵"
layout: single
mathjax: true
categories:
  - 数值优化
tags:
  - 最小二乘
  - 数值优化
---

一、雅可比矩阵的基本定义
      对于一个向量值函数    
      $$
        f: \mathbb{R}^n \rightarrow \mathbb{R}^m
      $$
      定义：
      $$
        \mathbf{y} =f(\mathbf{x})=\begin{bmatrix}  f1​(x)\\f2​(x)\\ . \\ . \\ . \\ fm​(x)​ \\ \end{bmatrix}, \mathbf{x}=\begin{bmatrix}  x_1, x_2, ...,x_n\end{bmatrix}^T
      $$
      则其雅可比矩阵（Jacobian Matrix）定义为：
      $$
        \mathbf{J}(\mathbf{x}) =\frac{\partial{\mathbf{y}}}{\partial{\mathbf{x}}}=\begin{bmatrix}  \frac{\partial{f_1​}}{\partial{x_1}} \quad  ...  \quad\frac{\partial{f_1​}} {\partial{x_n}}  \\  . \\ . \\.​ \\ 
        \frac{\partial{f_m​}}{\partial{x_1}} \quad  ...  \quad\frac{\partial{f_m​}} {\partial{x_n}}  
        \end{bmatrix}_{m×n}
      $$