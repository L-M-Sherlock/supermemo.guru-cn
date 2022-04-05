# 助记媒介可以扩展到个人笔记上

原文：[The mnemonic medium can be extended to one’s personal notes (andymatuschak.org)](https://notes.andymatuschak.org/z5ARNXtS5VxteskEW91S1yYTgAcLABNXsZuJE)

使用[间隔重复记忆系统](https://notes.andymatuschak.org/z4eXdSMJFv2qVGXSUEKH4vdcHBrLHcFY1ZGfC)的过程中，你会写笔记来记录你所学习、观察和思考的内容。不幸的是，[现有的间隔重复系统不鼓励常青笔记](https://notes.andymatuschak.org/zZuqUv3XNEFsimMmHszLF87Pr5vTraLjL5Y)。记忆系统对于记住所写内容并持续琢磨很有帮助，但对于基于想法进一步思考并无太大功效。[常青笔记](https://notes.andymatuschak.org/z4SDCZQeRo4xFEQ8H4qrSqd68ucpgE6LU155C)系统有助于逐步完善想法，但对于记住这些笔记并持续琢磨没有太大用处（除了[常青笔记的维护近似于间隔重复](https://notes.andymatuschak.org/z6yfTwYekzvBkVjeH7WBUrSAJhyGTMYDAyYW7)的效果之外）。因此，你陷入了一个困局，要么在两个不同的系统中混乱地重复劳动，要么放弃其中某一个系统的好处。

[助记媒介](https://notes.andymatuschak.org/z4rRX3qwSSJRsEkdXKwH2shamgHNeRthrMLiF)针对散文解决了这个问题。[间隔重复卡片通常是原子化的，而助记媒介为其赋予结构](https://notes.andymatuschak.org/z5YjgWTaYfhWLrEbysgmDfFRcZ1yxgLeBeZac)。我们可以如法炮制，在个人的笔记系统内部，就地为间隔重复卡片赋予结构。我们可以将其称为{**个人助记媒介**}。

例如，想象一下在个人笔记中{用大括号包裹一段内容}，即可创建{挖空}卡片。

或者像这样制作传统的双面卡片：

问：如果一个人只在 Anki 中做笔记，他可能会遇到什么重大限制？

答：（例如，在写笔记时难以偶遇惊喜，没有办法轻松地逐步完善笔记，笔记之间的联系有限，难以「通读」某个主题下的笔记，等等）

- [Anki 下「草创」卡片和修订卡片比较困难](https://notes.andymatuschak.org/z5tAH4GmnBiQ45M9DZSNSwp4tMWa3u5bgyKrY)

## 实现

这个想法的类似版本有以下几个实现：

- 外部 SRS 导入器

  - [我的个人助记媒介实现](https://notes.andymatuschak.org/z4mAF1uBV96r72e4NjLcDaujEyTPGiUQJEj8C)

  - [Obisidan *to* Anki](https://github.com/Pseudonium/Obsidian_to_Anki)。需要手动完成一些步骤。

  - [Ankify](https://github.com/kangruixiang/Ankify)，需要手动完成一些步骤——不适合后台自动运行。

- 使用软件集成的 SRS

  - [RemNote](https://notes.andymatuschak.org/z6jecLFTkHG5MCFDvhwsd2p8YWykaHr6ZkHTi)，一个日益完善的网络应用程序

  - [Mochi](https://notes.andymatuschak.org/zxAXSEQidXeYW2XFBj9ftGxz1kTNtV4fXjhZ)，其互动淡化写散文笔记

  - [org-fc](https://www.leonrische.me/fc/index.html)， org-mode 的不错实现

  - [TiddlyRemember](https://github.com/sobjornstad/TiddlyRemember)，使用一些自定义标记与 TiddlyWiki 同步；需要手动同步，[Soren Bjornstad](https://notes.andymatuschak.org/zzfor7LXCY9JBRjFmMaeLw5zV69GM2dSDQA) 编写

------

## 参考文献

Nielsen, M. (2018). *Augmenting Long-term Memory*. http://augmentingcognition.com/ltm.html

> 我开始识别开放问题，这些问题是我希望得到答案，但似乎尚未被解答的。我发现了一些充满可能性的技巧和观察，但我还不知道其重要性。有时，我还发现我自认为是整个领域的盲点。我也会在 Anki 中对所有这些内容设问。于是 Anki 成为支持我创造性研究的媒介。此时 Anki 暴露出一些缺点，因为 Anki 设计时并没有考虑到支持创造性工作——比如说， 对于草稿空间中长时间的自由探索活动，Anki 先天不足。