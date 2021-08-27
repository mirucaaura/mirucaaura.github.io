---
title: "Weak Strong Convergence"
description: ""
date: 2021-08-27T20:10:00+09:00
tags: ["math"]
katex: math
draft: false
---

「有限次元ユークリッド空間上の点列は弱収束するならば強収束する」ことを示す．

まず，弱収束と強収束の定義を確認しておく．弱収束は無限次元空間において一般的な点列の収束（強収束のこと）を議論することが必ずしも妖異ではないためによく考えられる概念である．以下ではヒルベルト空間における弱収束の定義を述べる．

ヒルベルト空間 $\mathcal{H}$ 上の点列 $(x_n)\_{n\in\mathbb{N}}$ とある点 $x\in\mathcal{H}$ について，任意に固定された $y\in\mathcal{H}$ に対して
$$
\lim_{n\to\infty} \left< x_n - x, y \right> = 0
$$
が成り立つとき，点列 $(x_n)\_{n\in\mathbb{N}}$ は $x$ に弱収束するという．

また，強収束は次のように定義される．

ノルム空間 $X$ 上の列 $(x_n)\_{n\in\mathbb{N}}$ に対して，ある点 $x\in X$ が存在し
$$
\lim_{n\to\infty} \\| x_n - x \\| = 0
$$
が成り立つとき，点列 $(x_n)\_{n\in\mathbb{N}}$ は $x$ に強収束するという．

以下，命題に対する証明を与える．

有限次元ユークリッド空間 $\mathbb{R}^N$ 上の点列 $(x\_n)\_{n\in\mathbb{N}} \subset \mathbb{R}^N$ が点 $x \in \mathbb{R}^N$ に弱収束することを仮定する．いま，$x\_n = (a\_{1}\^{(n)}, a\_{2}\^{(n)}, \dots, a\_{N}\^{(n)})\^\top$ および，$x = (a\_1, a\_2, \dots, a\_N)\^\top$ とするとき，任意の $i=1,2,\dots,N$ に対して
$$
0 = \lim_{n\to\infty} \left< x_n - x, e_i \right> =  \lim_{n\to\infty} (a\_{i}\^\{(n)} - a\_i)
$$
が成り立つ．ここで，$e\_i = (\underbrace{0,\dots,0}\_{i-1},1,0,\dots,0)\^\top$ である．したがって，任意の $i=1,2,\dots,N$ に対して
$$
\lim_{n\to\infty} a\_{i}\^\{(n)} = a\_i
$$
が成り立つ．よって，
$$
\lim\_{n\to\infty} \\|x_n - x\\| = \lim\_{n\to\infty} \sum\_{i=1}\^{N} \left(a\_{i}\^{(n)} - a\_i\right)\^2 = 0
$$
となり，点列 $(x\_n)\_{n\in\mathbb{N}}$ は $x$ に強収束する．