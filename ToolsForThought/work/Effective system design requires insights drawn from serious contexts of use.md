# 有效的系统设计需要从真刀真枪的使用情境汲取洞见

原文：[Effective system design requires insights drawn from serious contexts of use (andymatuschak.org)](https://notes.andymatuschak.org/z3H98n8DGZmu8XArqHZVsckyWvbTe8wK4kAt2)

粗制而成的原型很不错：由此能开展粗糙的迭代和快速评估。但是，许多重要的洞见，只有依托于真刀真枪的创造性问题才能够涌现，这些问题与原型系统本身无关。这是[实践出洞见](https://notes.andymatuschak.org/z7YyAp683VNbTmDG4hx9QFpf5urwxZJpsycS6)提出的一个关键主张。

听起来像是标准做法：系统当然需要经过评估！但大多数系统设计者并不认真对待「真刀真枪」：[工具制作者通常缺乏与真刀真枪的使用环境的联系](https://notes.andymatuschak.org/zs5uUEv9iJH7JuAmsCChxBEMP2zW6CRbiAWE)。

观察你的理论（由系统表示）与现实互动的方式，可以产生一些见解，有助于进一步完善理论。这些见解的特点依赖于系统的使用环境。如果系统没有被认真使用，那么这些见解将更像是纯粹的理论家所能看到的。那些是在没有实际建立系统的情况下可能的。

皮克斯是一个很好的例子，它创造了真刀真枪的使用环境，反过来又推动了系统设计：[皮克斯的电影和技术发展是耦合的飞轮](https://notes.andymatuschak.org/z45gUHaD2DcqH3zMWhwHaXESZLCWWk6tHLDi6)。

共同的挑战：

- [优秀的工具制造者往往不是优秀的工具使用者，反之亦然](https://notes.andymatuschak.org/zagVn3aaVDFhU4JhGCntgs88oHMJSpzu7ar)

- [研究思想工具的团体需要足够的能力来建立适合认真工作的原型](https://notes.andymatuschak.org/z7Rdcpa64TtUx6s5dNtLgZpFR6G3G6YpoD4ks)

相关理论：

- [强大的赋能环境通常作为副产品产生于在追求其自身内在意义的项目时](https://notes.andymatuschak.org/z4N6d29XL2PZXCa64HPcxA64RGWDb6Cagc1gs)

- [创制环境极大程度受作者的动机塑造](https://notes.andymatuschak.org/z34mYTEEEQcrywWkoNnz1Fzr8NmwaDsVRNgTK)

- [强大的赋能环境注重专家的使用](https://notes.andymatuschak.org/z8jg7T3YhvyXiEpy4humYAioLUEjnrdZgwHYs)

------

## 参考文献

Matuschak, A., & Nielsen, M. (2019).我们如何才能开发变革性的思想工具？2019年12月2日，取自https://numinous.productions/ttft

> 具体来说：假设你想为X学科（比如X=微分几何）建立工具。除非你深入地参与该学科的实践，否则要建立好的工具将是非常困难的。这很像试图为木工建造新的工具，而自己却没有实际做任何木工工作。这也许是像 **Mathematica** 这样的工具运作良好的部分原因--主要设计者Stephen Wolfram对数学和物理学有真正的研究兴趣。当然，并不是*Mathematica*的所有部分都工作得同样好；有些部分感觉像是玩具，而且看起来很可能是那些*没有被公司内部认真使用的部分。

Brooks, F. P., Jr.(1994).The Computer Scientist as Toolsmith II [ACM Allen Newell Award Lecture](https://notes.andymatuschak.org/z3H98n8DGZmu8XArqHZVsckyWvbTe8wK4kAt2).SIGGRAPH。

> 它让我们瞄准了相关的问题，而不仅仅是练习或玩具规模的问题。

> 它使我们对成功和失败保持诚实，这样我们就不会轻易欺骗自己。

> 它使我们面对*整个*问题，而不仅仅是简单的或数学的部分。例如，在计算几何学中，我们不能回避相邻的点三联体或共面的点四联体的情况。我们不能假设条件不好的情况。

> 面对整个问题反过来又迫使我们学习或发展新的计算机科学，往往是在我们原本不会涉及的领域。

> 除了这些，从那些发现蛋白质如何工作，或设计潜艇，或在纳米尺度上进行制造的人的肩膀上看过去，只是普通的乐趣。

[Python Tutor 在学术界建立可扩展和可持续研究软件的设计指南。In The 34th Annual ACM Symposium on User Interface Software and Technology (pp. 1235-1251).计算机协会](https://notes.andymatuschak.org/Guo%2C_P._(2021)._千万用户和十年后)

> 基于软件的研究人员经常努力建立包含高层次想法的系统，这些想法很可能会被推广，因为这些想法会使学术论文更有说服力。然而，我们认为，试图过于笼统实际上阻碍了规模和可持续性。为了建立持久的软件，使其能够有机地发展一个庞大的用户群，我们必须从具体的方面入手。

>

> 2009年我们创造了 Python Tutor 网站，目标非常具体：为学生和导师（比如我们自己）提供一种方便的方式，逐步浏览Python代码并查看变量的值。