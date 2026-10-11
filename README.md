# 大模型与具身智能数学基础：教材推荐与学习顺序

针对你前面的大模型（LLM）与具身智能（Embodied AI）学习路线，我建议把数学基础分成 7 个部分：线性代数、微积分与矩阵微分、概率统计、最优化、信息论、随机过程、几何与李群。

其中，学习 CS336、CS285 和 VLA 所需的数学并不完全相同：

- 大模型（LLM）： 重点是线性代数、矩阵微积分、概率论、信息论和优化理论。
- 具身智能（Embodied AI）： 除了上述基础，还要重点学习随机过程、马尔可夫决策过程、三维几何和李群。
- 科研进阶： 需要进一步掌握随机优化、概率建模、动力系统和机器人几何。

## 一、最推荐的 3 本入门教材

如果只想先选择三本，我推荐下面这组：

[Free Shipping! Mathematics for Machine Learning, (Paperback) - Walmart.com - Walmart.com](https://images.openai.com/static-rsc-4/gW5z9vH3ekrQxRliclq66trOzu1XVXmppY3ro15VwKNVRvFxKL1UgPhSofUfkjr03Kz5XduLfmxF6zfx2nr99EanVtyAY3xhlyxn-VerWI8kPho71j1jWgwM3IM9eEkcoc5Nuc4jsb4UTRirBJK9dwqUZm6SPRjv2sIICrCHQEk?purpose=inline)

1\. Mathematics for Machine Learning

Deisenroth、Faisal、Ong · Cambridge University Press · 2020

最推荐的第一本

机器学习数学的综合入门教材，包括线性代数、解析几何、矩阵分解、向量微积分、概率分布和连续优化。

[官方主页及免费 PDF](https://mml-book.com/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://mml-book.com\&sz=32)

Mathematics for Machine Learning



[People ask me about getting started with data science all the time. So I came up with three paths fo... - 🔥Kareem Carr 🔥 | Rattibha](https://images.openai.com/static-rsc-4/jyQqzkIh6AoZV-sInMZYLmBlKhuysxdCLw9PMze-M7agaei6j6R6YlKmAnyk-iRgpJ3wCKX85lSw0jPpg_vTlPW2klGn0ERCm6dpm-G-r6UnFWDWO315qtuocQZTMKkUDB5CdReapogFVI2Qi5n4tgAOUhx3WEB-zNTDAO3Uco0?purpose=inline)

2\. Introduction to Probability

Joseph K. Blitzstein、Jessica Hwang · 第二版

概率论首选

非常适合建立条件概率、随机变量、期望、条件期望和贝叶斯推断的直觉，为生成模型、概率学习与强化学习打基础。

[Harvard Stat 110：免费教材与视频](https://stat110.hsites.harvard.edu/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://stat110.hsites.harvard.edu\&sz=32)

Statistics 110: Probability



[Convex Optimization - ISBN13:9780521833783 - 澜瑞外文-网上购买外文原版进口图书 LANREE](https://images.openai.com/static-rsc-4/BIMvIbkuy-hmLx6J7W-FRMoFeDe0vV5m7O3B6AN-bowj4ujUnhN7RAb0lWaUCm6t-24co4-1AoRa5XU5wLRv874XxXWFL9DP8FD2vXLBTekTqnwitqbf1bXuEDJAYhSagiArgN-b8CTdBSKSoT_3km3xT0EmC8lyOYbYJ136T-k?purpose=inline)

3\. Convex Optimization

Stephen Boyd、Lieven Vandenberghe · Cambridge University Press

优化理论首选

系统讲解凸集、凸函数、对偶理论、KKT 条件以及数值优化方法，数学推导严谨，也适合控制与机器人研究。

[Stanford 官方免费 PDF 与课件](https://web.stanford.edu/~boyd/cvxbook/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://web.stanford.edu\&sz=32)

Boyd and Vandenberghe



这三本书不是要求全部逐页读完。《Mathematics for Machine Learning》作为数学总纲，其余教材用于专题深入，效率最高。

## 二、按照 7 个数学方向选择教材

### 1. 线性代数：Linear Algebra

重要程度：LLM ★★★★★ · 具身智能 ★★★★★

[Introduction to Linear Algebra: Sixth Edition](https://images.openai.com/static-rsc-4/fJdmNThV-aFg0FXKpXjUhnDmRlE4Y-o_gwkJex9Jpym9GCHn-dI4LAj6xmOj_HGDM9tnmK0w9bhsXrVY7-4Lh9LZtzI68NPjRO-Y7tWtR7qNPiPpA2vZlEU-c1JuXykcD0RCJgoOWGbVg_QGShYCqlaDi9Z0PK-7f2XNg6zkZH0?purpose=inline)

Introduction to Linear Algebra

Gilbert Strang · 第六版，2023

推荐作为系统学习线性代数的主教材。配合 MIT 18.06 课程，尤其适合建立对矩阵、线性变换、特征值和奇异值分解的直观理解。

[出版社及教材信息](https://wellesleycambridge.com/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://wellesleycambridge.com\&sz=32)

wellesleycambridge.com



[Introduction to Applied Linear Algebra – Vectors, Matrices, and Least Squares](https://images.openai.com/static-rsc-4/c84_PimapRdpO9cy0tC903iuZosoUIXMDfQ6l1eONmM6Cy4DosqO9cElsE2GXPpzrEUCPK_fYUcWWdIqsahD4IvRgH7v6FDE1hrZ-tVgcKGtjwecKRcah39fnHEhu-CNqciB5QHxj9NWtZXbP9iTpQu_-e1X0VzhiHtzSfVDaVA?purpose=inline)

Introduction to Applied Linear Algebra

Stephen Boyd、Lieven Vandenberghe

更偏工程应用，包括向量、矩阵、最小二乘和数值计算。适合希望将线性代数直接应用到机器学习和机器人算法中的学习者。

[Stanford 官方免费 PDF](https://web.stanford.edu/~boyd/vmls/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.web.stanford.edu\&sz=32)

Vectors, Matrices, and Least Squares



重点掌握： 向量空间、线性映射、矩阵乘法、正交投影、特征值分解、SVD、矩阵范数、正定矩阵。

对应的典型问题是：

\\[ Q=XW_Q,\quad K=XW_K,\quad V=XW_V \\]

以及为什么 Attention 使用矩阵 \\(QK^\top\\) 来计算相关性。

建议选择 Strang 或 Boyd 的一本作为主教材，另一本文献用于查缺补漏。

### 2. 微积分、向量微积分与矩阵微分

重要程度：LLM ★★★★★ · 具身智能 ★★★★★

这一部分我不建议重新完整学习一遍高等数学，而是重点补充多变量微积分、Jacobian、Hessian 和矩阵微分。

[Understanding Deep Learning Book By Simon Jd Prince, ('tc') | Indigo](https://images.openai.com/static-rsc-4/_gQyQLbAfvLhdDPtDLQvzDjACWOAmfC9bL6CpRtIy6Dug9SkfMarugwE9X3z7IZnVl0pb512twHUSI7hToq3ir3AHwmdw4EtE1IaOhwBW6LTJle73je7WMPgCeWoucRnFD9uJVs0qfGv0qYk5M05A2mVhleylGodg0yQzx4XSzg?purpose=inline)

Understanding Deep Learning

Simon J. D. Prince · MIT Press，2023

这是一本深度学习教材，而不是纯数学教材，但它非常适合把导数、梯度和链式法则应用到神经网络训练。

重点阅读第 5～7 章：损失函数、模型训练、梯度与初始化。

[官方免费 PDF、练习与代码](https://udlbook.github.io/udlbook/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://udlbook.github.io\&sz=32)

udlbook.github.io



另外，把前面推荐的《Mathematics for Machine Learning》第 5 章 Vector Calculus 作为数学理论部分。

需要达到的能力包括能够独立推导：

\\[ \nabla_x(x^\top Ax)=(A+A^\top)x \\]

以及复合函数求导：

\\[ \frac{\partial\mathcal L}{\partial W} = \frac{\partial\mathcal L}{\partial y} \frac{\partial y}{\partial W} \\]

这里的符号表示示意性的链式求导，具体矩阵形式取决于采用的 Jacobian 布局约定。

学习目标： 能够不依赖 PyTorch Autograd，手动计算一个 MLP 的反向传播梯度。

### 3. 概率论与数理统计

重要程度：LLM ★★★★★ · 具身智能 ★★★★★

基础阶段使用前面介绍的 Blitzstein 与 Hwang 的《Introduction to Probability》。

进一步推荐：

[Probabilistic Machine Learning by Kevin P. Murphy (Hardback) - Penguin Books Australia](https://images.openai.com/static-rsc-4/v9y4Y1i0LZLSHSUvN1ae6eGcYcOlf5eA47KGsPaWdUgXAz3rRhP-kKCjCgjyyaUTNgu27KhdoGCc35TUkjDRa0cB0QV5itGraye80Xsa88hvzr6fcIQLIIT-Bi5kIE9dNwn7u-XEqlgDSWaI6pQeRIWMVES-upF8E3bZMVNIt5w?purpose=inline)

Probabilistic Machine Learning: An Introduction

Kevin P. Murphy · MIT Press，2022

从概率建模和贝叶斯决策的角度讲解机器学习。包含概率分布、概率推断、优化与神经网络等内容，非常适合进阶。

[官方免费 PDF、代码及练习](https://probml.github.io/book1)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://probml.github.io\&sz=32)

probml.github.io



重点掌握： 随机变量、联合分布、条件分布、高斯分布、多元高斯分布、贝叶斯公式、MLE、MAP、期望、方差和协方差。

尤其要熟练掌握贝叶斯公式：

\\[ p(\theta\mid D)= \frac{p(D\mid\theta)p(\theta)}{p(D)} \\]

以及多元高斯分布：

\\[ p(x)=\frac{1}{(2\pi)^{d/2}|\Sigma|^{1/2}} \exp\left[ -\frac12(x-\mu)^\top\Sigma^{-1}(x-\mu) \right] \\]

这些知识不仅用于生成模型，也会在机器人状态估计、高斯过程、世界模型和不确定性建模中大量出现。

### 4. 最优化理论：Optimization

重要程度：LLM ★★★★★ · 具身智能 ★★★★☆

前面推荐的 Boyd《Convex Optimization》是理论主教材。

如果之后希望进一步理解数值优化，可以增加：

Numerical Optimization，作者 Jorge Nocedal、Stephen J. Wright。

该书更偏数值算法，包括线搜索、信赖域、拟牛顿法和约束优化，适合数学及优化理论基础较好的学习者。

建议学习两层内容：

| 第一层：理论基础    | 第二层：深度学习应用         |
| ----------- | ------------------ |
| 凸集、凸函数      | 神经网络损失函数的非凸性       |
| 无约束优化       | SGD、Momentum、AdamW |
| 约束优化、KKT    | 机器人安全约束            |
| Lagrange 对偶 | 约束强化学习             |
| 梯度法、牛顿法     | 深度学习优化器            |
| 优化收敛性       | 学习率、训练稳定性          |

需要注意：凸优化教材不会完整覆盖 AdamW、学习率 Warmup 等现代大模型训练方法。这些内容应在之后学习 CS336 时补充。

### 5. 信息论：Information Theory

重要程度：LLM ★★★★★ · 具身智能 ★★★☆☆

["Elements of Information Theory" von Thomas M. Cover Buch auf Englisch - bücher.de](https://images.openai.com/static-rsc-4/z1sG6lALKgw5xNGwHsCok7sUg2zi7Vz27ze2MrIiFdJShgCahvikOIQwXofRSM8g7Okha1dUx-qS-UJeiQAliwbw6UGBydeQG6rcyyz9EOJzQCfQ9aR-IdIoPx0KroAj9RdZWjJHQLz1zegaigFpzz66aflYX9k4OHVLpldswVo?purpose=inline)

Elements of Information Theory

Thomas M. Cover、Joy A. Thomas · 第二版

信息论经典教材，建议先阅读第 2 章关于熵、相对熵、互信息的内容，其余部分根据研究需要再深入。

[Wiley 官方教材主页](https://onlinelibrary.wiley.com/doi/book/10.1002/047174882X)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://onlinelibrary.wiley.com\&sz=32)

Wiley Online Books



重点掌握三个数学概念：

信息熵

\\[ H(X)=-\sum_xp(x)\log p(x) \\]

交叉熵

\\[ H(p,q)=-\sum_xp(x)\log q(x) \\]

KL 散度

\\[ D\_{\mathrm{KL}}(p\\|q) = \sum_xp(x)\log\frac{p(x)}{q(x)} \\]

需要理解它们之间的关系：

\\[ H(p,q)=H(p)+D\_{\mathrm{KL}}(p\\|q) \\]

这一部分直接对应大语言模型训练中的交叉熵损失，以及变分推断、生成模型和分布对齐方法。

### 6. 随机过程与马尔可夫决策过程

重要程度：LLM ★★★☆☆ · 具身智能 ★★★★★

[Reinforcement Learning, second edition by Richard S. Sutton - Penguin Books Australia](https://images.openai.com/static-rsc-4/vUw2hs6UkQDxM3Wldo6IvljKjcSEbeSO1SUBQCLJjLOAT52xlsicEutCQIJdv6fSyZtBSFhCEEGo7FIWysxh7rlIdDymCeA646yQh91KpSipPwaHsCVLdD7FxGd0Fw0sxXKnXdTRhgqERCdRMRVAw3rOKNv33QqPPXj3VDS6wbs?purpose=inline)

Reinforcement Learning: An Introduction

Richard S. Sutton、Andrew G. Barto · 第二版，2018

这是强化学习教材，不是完整的随机过程教材，但非常适合以机器人学习为目标，掌握 MDP、价值函数、Bellman 方程和策略学习的数学基础。

[MIT Press 官方教材主页](https://mitpress.mit.edu/9780262039246/reinforcement-learning/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://mitpress.mit.edu\&sz=32)

MIT Press



建议重点阅读第 3～6 章：

| 章节        | 内容         |
| --------- | ---------- |
| Chapter 3 | 有限马尔可夫决策过程 |
| Chapter 4 | 动态规划       |
| Chapter 5 | 蒙特卡洛方法     |
| Chapter 6 | 时序差分学习     |

这里需要掌握的核心对象是：

\\[ \mathcal M=(\mathcal S,\mathcal A,P,R,\gamma) \\]

分别表示状态空间、动作空间、状态转移概率、奖励函数和折扣因子。

对于之后学习 CS285，这部分知识非常重要。

如果需要严格研究马尔可夫链、随机微分方程或者连续时间随机过程，则应再补充专门的随机过程教材。

### 7. 几何学、李群与李代数

重要程度：LLM ★★☆☆☆ · 具身智能 ★★★★★

[Free Shipping! Modern Robotics: Mechanics, Planning, and Control, (Hardcover) - Walmart.com - Walmart.com](https://images.openai.com/static-rsc-4/FKNEasGvlVgZ8YfNdyuIjHrchAwYbpbj4NUgcuM2tWqVM50fpJ0_9uowXrcYM58wq9lDoV_T_0Ynj7bE5jMCoU3QLNnIU9_-CRcKyqjmBNI2SW4tmNXJ3xyb5HHRsOmJwRsRASW7829X33LtczKAuDzBfB9kPpciS132bs3qwCU?purpose=inline)

Modern Robotics: Mechanics, Planning, and Control

Kevin M. Lynch、Frank C. Park · 2017

首先学习第 2～5 章，理解构型空间、刚体运动、正运动学与速度运动学。

[官方免费教材及视频](https://modernrobotics.northwestern.edu/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://hades.mech.northwestern.edu\&sz=32)

Northwestern Mechatronics Wiki



[State Estimation for Robotics : Second Edition (Hardcover, 2 Revised edition) | Timothy D. Barfoot | 알라딘](https://images.openai.com/static-rsc-4/xS6nv7j4jtRL4IsO6Fucwz5z5828kVDdHM5ezvE_QcpQIprEJhvJz-cQ-FozeH4auMnNka5WkEN22OFtYNxKSuGsVBqGKd2m1-nYiHMImC9IxR6s0zbcb9fkHlZGC_xDZ_tXrE9HFbZ1TqsbWsFFqIBrI6GomdoXrCJbvkRBYfo?purpose=inline)

State Estimation for Robotics

Timothy D. Barfoot · 第二版，2024

进阶教材，系统联系机器人状态估计、概率模型与几何，适合研究三维空间定位、位姿估计和多传感器融合。

[作者主页及教材资源](https://asrl.utias.utoronto.ca/~tdb/)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://asrl.utias.utoronto.ca\&sz=32)

asrl.utias.utoronto.ca



需要重点掌握：

\\[ SO(3)=\\{R\in\mathbb R^{3\times3}:R^\top R=I,\det R=1\\} \\]

以及齐次变换矩阵：

\\[ T= \begin{bmatrix} R&p\\\ 0&1 \end{bmatrix} \in SE(3) \\]

这部分能够将抽象的数学概念直接连接到机器人位置、姿态、运动控制和三维视觉。

## 三、数学基础教材完整推荐表

| 数学领域      | 推荐主教材                                   | 进阶教材                                   | 优先级    |
| --------- | --------------------------------------- | -------------------------------------- | ------ |
| 综合数学      | Mathematics for Machine Learning        | Understanding Deep Learning            | 必须     |
| 线性代数      | Introduction to Linear Algebra          | Introduction to Applied Linear Algebra | 必须     |
| 微积分与矩阵微分  | Mathematics for Machine Learning 第 5 章  | Understanding Deep Learning 第 5～7 章    | 必须     |
| 概率统计      | Introduction to Probability             | Probabilistic Machine Learning         | 必须     |
| 最优化理论     | Convex Optimization                     | Numerical Optimization                 | 必须     |
| 信息论       | Elements of Information Theory          | 后续按研究课题深入                              | LLM 必须 |
| 随机过程与 MDP | Reinforcement Learning: An Introduction | 专题随机过程教材                               | 具身必修   |
| 三维几何与李群   | Modern Robotics                         | State Estimation for Robotics          | 具身必修   |

这里列出的“必须”是指对应知识必须掌握，而不是必须完整通读每一本书。

## 四、推荐的 12 周数学基础学习计划

如果已有高等数学、线性代数基础，可以按照下面的学习安排执行。

12 周学习清单

0/7 个模块完成

第 1～2 周：线性代数

教材：MML 第 2～4 章 + Strang / Boyd 选读

实践：实现 SVD、PCA，理解 Attention 矩阵计算

第 3～4 周：微积分与矩阵微分

教材：MML 第 5 章 + UDL 第 5～7 章

实践：手动推导并编程实现反向传播

第 5～6 周：概率统计

教材：Introduction to Probability + Murphy 选读

实践：实现高斯分布、最大似然估计、贝叶斯更新

第 7～8 周：最优化

教材：MML 第 7 章 + Boyd 相关章节

实践：实现 SGD、Momentum、Adam，理解 KKT

第 9 周：信息论

教材：Elements of Information Theory 第 2 章

实践：实现交叉熵和 KL 散度

第 10 周：MDP 与随机过程基础

教材：Sutton & Barto 第 3～4 章

实践：实现有限状态 MDP 和价值迭代

第 11～12 周：几何与李群

教材：Modern Robotics 第 2～5 章

实践：实现三维旋转、位姿变换和机械臂正运动学

## 五、我的学习建议

你之前已经接触过微分博弈、Lyapunov 理论以及高斯过程等知识，因此无需按照零基础的路线重新学习全部数学。

更有效的方式是以 《Mathematics for Machine Learning》为主线，补充矩阵微分、概率建模和优化理论。进入具身智能后，再重点学习《Modern Robotics》中关于 \\(SO(3)\\)、\\(SE(3)\\)、Jacobian 和机械臂运动学的内容。

最终可以用四个能力判断数学基础是否足够扎实：

- 能够独立推导 Transformer 中 Attention、Softmax 和交叉熵的梯度。
- 能够推导多元高斯分布、贝叶斯后验与最大似然估计。
- 能够理解梯度优化、约束优化和基本强化学习数学。
- 能够利用矩阵和李群表达机器人三维位姿与运动学。

不需要等到所有数学教材都学完才开始 CS336。 完成线性代数、矩阵微分、概率和优化的核心部分后，就可以同步学习 CS224N、CS336；随机过程和机器人几何可以在之后学习 CS285 与 MIT Robotic Manipulation 时继续深化。
