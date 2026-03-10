---
title: "Math Research(p-adic geometry and BSD conjecture)"
date: 2026-03-09T18:00:00+08:00
description: "Plan for study and research"
featured_image: "/images/notebook.jpg"
categories: "Plan"
---



## 第一阶段

1. 分析主线：数学分析
    1. baby rudin：只看前九章

    2. 基本分析讲义：复习概念
    3. 重点：一致收敛，极限交换，隐函数定理

2. ^拓扑流形主线：
    1. 点集拓扑：GTM 202前四章
    2. 微分流形：Loring W. Tu《An Introduction to Manifolds》
        1. 重点：切空间、微分形式、Stokes 定理，de Rham 上同调
3. 代数主线：
    1. ^线性代数：Hoffman & Kunze《Linear Algebra》
    2. 抽象代数：李文威《代数学方法》

---

## 第二阶段

1. 分析主线：^实分析（Folland） + 复分析（Ahlfors）
2. 代数主线：交换代数
    1. Atiyah（精读并做完所有习题）

    2. Matsumura《Commutative Ring Theory》
3. p-adic Numbers：Fernando Q. Gouvêa《p-adic Numbers: An Introduction》

---

## 第三阶段

1. 黎曼曲面：Rick Miranda 《Algebraic Curves and Riemann Surfaces》
3. ^代数拓扑：Hatcher《代数拓扑》前三章
4. 同调代数：
    1. Weibel《同调代数导论》
    2. 导出范畴与三角范畴：
        1. Gelfand & Manin 《Methods of Homological Algebra》
        2. 案头字典： Kashiwara & Schapira 《Categories and Sheaves》前六章

    3. 同调交换代数与局部上同调
        1. Iyengar, Leuschke, et al. 《Twenty-Four Hours of Local Cohomology》<全书按讲座（Hours）编排，极度推荐前 15 讲>


---

## 第四阶段

1. 代数几何：
    1. Shafarevich：Basic Algebraic Geometry 1 前三章
    2. Hartshorne（GTM52）
        1. 精读Ch1-4，跳过Ch5
    3. Liu Qing 《Algebraic Geometry and Arithmetic Curves》
        1. 略读Ch 1 - Ch 7，重点精读Ch 8 - Ch 10
2. 代数数论与类域论：
    1. Neukirch
    2. J.-P. Serre《Local Fields》
    3. J.-P. Serre《Linear Representations of Finite Groups》
    4. Cassels & Fröhlich
        1. Tate's thesis：Ramakrishnan & Valenza, *Fourier Analysis on Number Fields* (GTM 186)

---

## 第五阶段

1. $L$ 函数、模形式与自守形式：
    1. ^L函数：大幅略读，只需记住公理化框架即可
        1. Harold Davenport《Multiplicative Number Theory》
            1. 目标：彻底掌握泊松求和公式（Poisson Summation Formula），广义 Gauss 和
            2. 章节：Ch6-9，Ch14
        2. *Iwaniec & Kowalski《Analytic Number Theory》
            1. 目标：Gamma 因子与整体架构，建立对更一般的整体 $L$ 函数（Global $L$-functions）的宏观认知
            2. Chapter 5：复习 Gamma 函数的极点分布和 Stirling 公式
            3. Chapter 14.1 - 14.2：熟悉现代文献中对于整体 $L$ 函数的标准化定义，不需要深究证明，只需记住公理化框架
    2. 模形式：Diamond & Shurman《A First Course in Modular Forms》
    3. Adéle语言与自守表示：（Jacquet-Langlands 对应）
        1. Goldfeld & Hundley《Automorphic Representations and L-Functions for the General Linear Group》（第一卷）
            1. Ch 1-4，6，8，11
        2. Bump《Automorphic Forms and Representations》 （Ch3-4）
            1. Ch 3.1 - 3.4，Ch 4.4
        3. *Cogdell 的《Lectures on L-functions...》：关于 $GL_n$ 和 $L$-函数的繁杂分析
2. 椭圆曲线：Silverman
    1. 《The Arithmetic of Elliptic Curves》
    2. 《Advanced Topic of Arithmetic of Elliptic Curves》
        1. 重点关注 CM，Tate Curve，Néron 模型，Height Functions章节

    3. 拓展-计算算术几何：J.E. Cremona《Algorithms for Modular Elliptic Curves》
        1. 在学习 Silverman 的椭圆曲线 时，同步学习使用 SageMath 或 Magma 进行实操计算
        1. 建议加上 Pari/GP
3. 代数群与伽罗瓦表示：
    1. 李代数与代数群：
        1. ^Humphreys《Introduction to Lie Algebras and Representation Theory》
            1. 直接阅读前三章（尤其是第 III 部分的 Root Systems），不要沉迷于后面的表示论计算

        2. Milne《Algebraic Groups》

    2. 伽罗瓦表示与形变理论：
        1. Galois Representations：
            1. J.-P. Serre《Galois Cohomology》
            2. Fontaine & Ouyang《Theory of p-adic Galois Representations》
            3. 案头字典：Neukirch, Schmidt, Wingberg《Cohomology of Number Fields》
            
        2. Galois形变理论（Deformation Theory）：
            1. Gouvêa《Deformations of Galois Representations》
        
        3. 模性提升定理：
            1. Darmon, Diamond, Taylor (DDT), "Fermat's Last Theorem"，第一章
            2. Toby Gee: Modularity Lifting Theorems - Notes for Arizona Winter School (AWS 2013)
            3. 补充：Cornell, Silverman, Stevens《Modular Forms and Fermat's Last Theorem》
        
    3. 高阶几何语言：
        1. Etale Cohomology：Milne《Lecture on Etale Cohomology》
        2. *广义拓扑与代数栈：Martin Olsson《Algebraic Spaces and Stacks》前几章
        3. Abelian Varieties：Milne《Abelian Varieties》
        4. *Shimura Varieties：Milne《Introduction to Shimura Varieties》
    
4. *代数 K 理论
    1. 入门：Milnor《Introduction to Algebraic K-Theory》
    2. 案头字典：Weibel《The K-book: An Introduction to Algebraic K-theory》
        1. 重点阅读前三章（$K_0, K_1, K_2$）和介绍 Quillen K-理论基本性质的章节


---

## 第六阶段：BSD猜想

1. 岩泽理论与Euler Systems

    1. 岩泽理论
        1. L. Washington《Introduction to Cyclotomic Fields》
        2. Greenberg 讲义：《Introduction to Iwasawa Theory for Elliptic Curves》
    2. Gross-Zagier 公式 和 Kolyvagin 欧拉系统：
        1. 核心：Darmon《Rational Points on Modular Elliptic Curves》
        2. Gross-Zagier 原始论文《Heegner points and derivatives of $L$-series》
        3. 补充阅读：
            1. Karl Rubin：Euler Systems (Annals of Mathematics Studies, 147)
            2. Gross 的综述文章《Kolyvagin's work on modular elliptic curves》
    3. Kato's Euler Systems
        1. 先读 A. J. Scholl 的文章 ：Kato's Euler systems and p-adic L-functions
        2. Kato关于 Euler 系统的论文：Kato, K. (2004). *p-adic Hodge theory and values of zeta functions of modular forms*. (Astérisque).
2. 特征簇

    1. p-进模形式与 Hida 理论
        1. 几何模形式：*p-adic properties of modular schemes and modular forms*
        2. Hida 理论：Haruzo Hida《Elementary Theory of L-values and $\mu$-adic Forms》
    2. Eigencurve
        1. **核心文献**：Coleman & Mazur "The Eigencurve" 
3. 岩泽主猜想 (Iwasawa Main Conjectures)：
    1. Skinner, C., & Urban, E. (2014). *The Iwasawa main conjectures for GL2*. (Inventiones mathematicae)
4. BSD 猜想综述
    1. wiles ICM：BSD简述
    2. wiles BSD2018：https://www.youtube.com/watch?v=1WYlP-B9nPI
5. 补充：Bertolini-Darmon 的一系列论文

    1. 核心：反气旋岩泽主猜想 (Anticyclotomic Iwasawa Main Conjecture)
        1. "Iwasawa's Main Conjecture for Elliptic Curves over Anticyclotomic $\mathbb{Z}_p$-extensions" (Annals of Mathematics, 2005).
    2. $p$-adic Gross-Zagier 公式
        1. "Heegner points on Mumford-Tate curves" (Inventiones mathematicae, 1997).
        2. "The p-adic L-functions of modular elliptic curves" (2014 综述 或相关早期论文).
    3. Stark-Heegner 点 (Darmon Points)
6. 补充：$p$-adic Langlands
    1.  Euler Systems 和 岩泽主猜想，现在很多前沿工作（例如 Skinner-Urban 的工作，或者基于高维簇的 Euler Systems）都深度依赖于 Galois 形变空间与 Hecke 代数的同构
    2. 核心：Matthew Emerton，Toby Gee，Eugen Hellmann 综述讲义："An introduction to the categorical p-adic Langlands program”
        1. 讲座视频：https://www.youtube.com/watch?v=kxktJUAZDHI
7. 补充：(Hot Topics around BSD)
    1. Bipartite Euler Systems / Kolyvagin Systems：这是 Mazur 和 Rubin 后来对 Euler System 的代数化公理化，极大地简化了 Kato 时代的繁杂。建议阅读 Barry Mazur 和 Karl Rubin 的相关文章。
    2. 高维情况的 Euler Systems：如 Loeffler-Zerbes 等人利用 $p$-adic 几何在更高维群上构造 Euler Systems，证明了各种新的 BSD 情况，这是近十年的显学。
    3. BSD 的 $p$-adic 版本：即 $p$-adic BSD 猜想（Mazur-Tate-Teitelbaum 猜想），它与例外零点（Exceptional Zeros）和 $\mathcal{L}$-不变量有关。这是当前 $p$-adic 几何和数论交汇的最前沿

---

## 第七阶段：p-adic几何

1. 非阿基米德解析几何基础
    1. 刚性几何：快速熟悉经典例子
        1. 大纲：Conrad《Several approaches to non-archimedean geometry》
        2. Bosch《Lectures on Formal and Rigid Geometry》
        3. 补充阅读/案头字典：Peter Schneider《Nonarchimedean Functional Analysis》
    2. Adic Spaces：Torsten Wedhorn《Adic Spaces》
2. p-adic Hodge：
    1. 快速建立经典直觉：
        1. C. Peters & J. Steenbrink《Mixed Hodge Structures》前两章
        2. A. Huber & S. Müller-Stach《Periods and Nori Motives》前三章
        3. 补充阅读：P. Deligne "Théorie de Hodge II" (Publications Mathématiques de l'IHÉS, 1971)<Sections 1 & 2>
    2. Brinon-Conrad 讲义《CMI Summer School Notes on $p$-adic Hodge Theory》
3. *$\infty$-范畴与高阶代数：Markus Land 《Introduction to Infinity-Categories》
4. Perfectoid Spaces：(Scholze)
    1. Bhatt 的讲义
        1. Lecture notes for a class on perfectoid spaces（密歇根大学研究生课程讲义，讲基础拓扑建立过程）
        2. The Hodge-Tate decomposition via perfectoid spaces（亚利桑那冬校讲义，展示如何使用Perfectoid Spaces）
    2. Scholze & Weinstein《Berkeley Lectures on p-adic Geometry》
    3. Scholze原始论文
5. Fargues-Fontaine 曲线
    1. 入门综述：Fargues "Geometrization of the local Langlands correspondence: an overview"
    2. 终极专著：Fargues & Fontaine《Courbes et fibrés vectoriels en théorie de Hodge p-adique》
6. Prismatic Cohomology/Diamonds
    1. 基础工具：导出代数与 δ-环
        1. Derived Commutative Algebra：Bhargav Bhatt 的讲义《Notes on derived algebraic geometry》
        2. δ-环 (δ-rings) 与 Witt 向量：Joyal 的经典论文 《δ-anneaux et vecteurs de Witt》
    2. *动机补充：q-形变与 de Rham 上同调
        1. *Scholze 的论文：Canonical q-de Rham Cohomology*
    3. 核心过渡桥梁：BMS 三部曲
        1. BMS1: *Integral p-adic Hodge Theory*
            1. 首次利用完美空间的局部性质，在不需要“好复叠”假设的情况下，硬核地构建了整系数的 $p$-进 Hodge 理论。这是理论的破局点
        2. BMS2: Topological Hochschild Homology and Integral p-adic Hodge Theory
            1. 将算术几何与代数拓扑深度融合，发现 BMS1 中的核心复形可以通过拓扑循环同调 (TC) 和拓扑 Hochschild 同调 (THH) 极其自然地计算出来
        3. BS: Prisms and Prismatic Cohomology
            1. **前置讲义（极度推荐）：** 直接读原始论文极易迷失。强烈建议先读 Bhatt 在哥伦比亚大学的讲义，或者 ARGOS 讨论班（Bonn 大学）关于 Prismatic Cohomology 的讲义
            2. 经过前两篇论文在拓扑和几何上的艰难摸索，他们最终发现可以抛弃复杂的代数拓扑，直接回到最纯粹的交换代数。通过引入带有 Frobenius 提升的 $\delta$-环，他们给出了“棱柱 (Prism)”极其精简的公理化定义，从而完美统一了所有的 $p$-进上同调理论


---

## 第八阶段：未来拓展

1. Perfectoid Spaces，Condensed Mathematics ，Prismatic Cohomology/Diamonds
    1. 详见“从Perfectoid到Condensed & Prismatic”
2. Arakelov 几何与算术 GGP 猜想
    1. 详见“Arakelov几何学习计划”
3. Motivic Cohomology，Beilinson 猜想（Regulators）
    1. 详见“Motivic Cohomology，Beilinson 猜想（Regulators）”
4. 局部朗兰兹对应（未定稿）
    1. Langlands综述：
        1. "An Elementary Introduction to the Langlands Program"
        2. 《An Introduction to the Langlands Program》
    1. 详见“局部朗兰兹对应”
5. 其他：详见“学习路线补充”




---





# 学习建议

1. 黑盒化能力：重点关注定理的使用场景，适用条件，结论，输入/输出
2. 阅读论文：
    1. 核心能力是读懂前沿论文，建议提前引入原始文献阅读
    2. 阅读论文时重点关注作者是如何利用不同工具解决问题，以及==尝试自行解决论文里的某个引理或小节。==
    3. 艰深的工具可以黑盒化，不要陷入细节
3. ArXiv 预印本，讨论班讲义（Lecture Notes），学术会议视频
    1. 跟踪 arXiv 上的 math.NT (数论) 和 math.AG (代数几何)
    2. 寻找 Bhargav Bhatt, Peter Scholze, Laurent Fargues, Matthew Emerton, David Hansen 等人的最新讲义和录像
    3. 暑期学校与讨论班讲义：学者的个人主页，Arizona Winter School (AWS) 的讲义和视频， MSRI/SLMath 或 IAS 的暑期学校录像
4. The Stacks Project
5. 重视计算实验
