# 2005: Stability increase function

# 2005:稳定性增强功能

[TOC=2,5]

## Why a simple idea could not materialize?

## 为什么一个简单的想法不能实现?

A perfect mathematical description of long-term memory is just about a corner. It may seem amazing today, but despite its simplicity, it took three long decades of starts and stops before a good model could emerge. In human endeavor, science is often a side effect of human curiosity while other burning projects often receive priority. The problem with science and invention is that they are blind and unpredictable. The uncovered truths show their power and value years after the discovery. A moral of the story is that all governments and companies should spare no resources for good science. Science is a bit like [SuperMemo](https://supermemo.guru/wiki/SuperMemo), today it seems like the reward is little, but in the long-term, the benefits can be stunning.

长期记忆的完美数学描述只是一个角落。这在今天看起来可能很神奇，但是尽管它很简单，在一个好的模型出现之前，它经历了漫长的30年的起起伏伏。在人类的努力中，科学往往是人类好奇心的一个副作用，而其他燃烧的项目往往得到优先考虑。科学和发明的问题在于它们是盲目和不可预测的。这些被揭露的真相在被发现数年后显示了它们的力量和价值。这个故事的寓意是，所有的政府和公司都应该不遗余力地为优秀的科学研究提供资源。科学有点像[SuperMemo](https://supermemo.guru/wiki/SuperMemo)，今天似乎回报很少，但从长远来看，好处可能是惊人的。

Today we can almost perfectly describe memory with the toolset employed in [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17). The only limit on further progress in understanding memory is the imagination, availability of time, and the ability to pose the right questions. We have all the tools, and we have a lot of data. We even have a nice portion of data combined with sleep logs that can now add a new dimension to the model: [homeostatic](https://supermemo.guru/wiki/Homeostatic) readiness for learning, [homeostatic](https://supermemo.guru/wiki/Homeostatic) fatigue, and even the [circadian](https://supermemo.guru/wiki/Circadian) factor.

SuperMemo story shows that if you have an idea, you should put it to life (unless you have another better idea). The problem with ideas is that they may often seem a fraction as attractive as they are. I plotted my first [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve) in [1984](https://supermemo.guru/wiki/Hermann_Ebbinghaus_(1885)_and_spaced_repetition_(1985)), I forgot about it within a few months and recalled the fact 34 years later at the time when my whole life revolves around forgetting curves. Imagine the surprise! When I came up with the first [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) algorithm, it took me over 2 years before I decided to recruit the first user. Without [Tomasz Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn), SuperMemo for Windows might have arrived 2-3 years later. Without [Janusz Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski), vital big data: repetition history record in SuperMemo might have been delayed by 1-2 years. When [incremental reading](https://supermemo.guru/wiki/Incremental_reading) came to life in 2000, only I knew it was a monumental thing. However, it took me quite a while to appreciate the extent of that fact. Today, I know [neural creativity](https://supermemo.guru/wiki/Neural_creativity) is a breakthrough tool, but I am still using it half-heartedly and not as often as its simpler alternative: [subset review](https://supermemo.guru/wiki/Subset_review).

今天，我们几乎可以用[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)中的工具集来完美地描述内存。进一步理解记忆的唯一限制是想象力、时间的可用性和提出正确问题的能力。我们拥有所有的工具和大量的数据。我们甚至有一个很好的部分数据结合睡眠日志,现在可以向模型中添加一个新维度:[稳态](https://supermemo.guru/wiki/Homeostatic)准备学习,[稳态](https://supermemo.guru/wiki/Homeostatic)疲劳,甚至[生理](https://supermemo.guru/wiki/Circadian)的因素。

SuperMemo的故事表明，如果你有一个想法，你应该把它付诸实践(除非你有另一个更好的想法)。创意的问题在于，它们往往看起来只是吸引力的一小部分。我第一次绘制[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve) [1984](https://supermemo.guru/wiki/Hermann_Ebbinghaus_ (1885) _and_spaced_repetition_(1985)),我忘记了它在几个月内,回忆事实时34年后一生围绕着遗忘曲线。想象的惊喜!当我想出第一个[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)算法时，我花了两年多时间才决定招募第一个用户。如果没有[Tomasz Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn)， Windows的超级备忘录可能会在2-3年后才出现。如果没有[Janusz Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)，重要的大数据:SuperMemo中的重复历史记录可能会推迟1-2年。当[渐进式阅读](https://supermemo.guru/wiki/Incremental_reading)在2000年问世时，只有我知道它是一件具有里程碑意义的事情。然而，我花了很长时间才意识到这一点。今天，我知道[神经创造力](https://supermemo.guru/wiki/Neural_creativity)是一个突破性的工具，但我仍在半心半意地使用它，不像它的更简单的选择:[子集审查](https://supermemo.guru/wiki/Subset_review)。

### 1990: First hint

### 1990年:第一个提示

[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) was in the making for nearly a quarter of a century. While preparing materials for this article, in my archive, I found a picture of a matrix named "new strength" with rows marked as "strength" and columns marked as "durability". These were the original names for [stability](https://supermemo.guru/wiki/Stability) and [retrievability](https://supermemo.guru/wiki/Retrievability) used in the years 1988-1990. Like an old fossil, the paper tells me that the idea of Algorithm SM-17 must have been born around 1990.

[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)已经酝酿了近四分之一个世纪。在准备这篇文章的材料时，在我的档案中，我发现了一张名为“新强度”矩阵的图片，其中行被标记为“强度”，列被标记为“耐久性”。这是1988-1990年使用的[stability](https://supermemo.guru/wiki/Stability)和[retrievability](https://supermemo.guru/wiki/Retrievability)的原始名称。这篇论文就像一块古老的化石，告诉我SM-17算法的想法一定是在1990年左右诞生的。

[![A "new strength" matrix with rows marked as "strength" (stability) and columns marked as "durability" (retrievability)](https://supermemo.guru/images/thumb/f/f5/New_strength_matrix.jpg/300px-New_strength_matrix.jpg)](https://supermemo.guru/wiki/File:New_strength_matrix.jpg)

> ***Figure:** A picture of a matrix named "new strength" with rows marked as "strength" and columns marked as "durability". These were the original names for stability and retrievability used in the years 1988-1990. The paper suggests that the idea of Algorithm SM-17 must have been born around 1990.*
>
> ***图片：**一张名为“新强度”矩阵的图片，其中行被标记为“强度”，列被标记为“耐久性”。这是1988-1990年用于稳定和可回收性的最初名称。本文认为SM-17算法的思想一定是在1990年左右产生的*

From the very early beginnings of the [two component model of memory](https://supermemo.guru/wiki/Two_components_of_memory), I wanted to build an algorithm around it. My motivation was always half-hearted. [SuperMemo](https://supermemo.guru/wiki/SuperMemo) worked well enough to make this just a neat theoretical exercise. However, today I see that the algorithm provides data for a model that can answer many questions about memory. Some of those questions have actually never been asked (e.g. about subcomponents of [stability](https://supermemo.guru/wiki/Stability)). This is also similar to [SuperMemo](https://supermemo.guru/wiki/SuperMemo) itself. It has always struggled because its value is hard to appreciate in theory. Practical effects are what changes the mind of good students most easily.

从早期的[内存的两个组件模型](https://supermemo.guru/wiki/Two_components_of_memory)开始，我就想围绕它构建一个算法。我的动机总是三心二意的。[SuperMemo](https://supermemo.guru/wiki/SuperMemo)运行良好，足以使这只是一个整洁的理论练习。然而，今天我看到算法为一个可以回答许多关于内存问题的模型提供了数据。其中一些问题实际上从未被问过(例如关于[稳定性](https://supermemo.guru/wiki/Stability)的子组件)。这也类似于[SuperMemo](https://supermemo.guru/wiki/SuperMemo)本身。它一直在挣扎，因为它的价值在理论上很难被欣赏。实践效果是最容易改变好学生思想的。

### 1993: Distraction

### 1993:分心

In 1993, my own thinking was an inhibitor of progress. Further explorations of the algorithm were secondary. They would not benefit the user that much. Memory modelling was pure blue sky research. See: [Futility of fine-tuning the algorithm](https://supermemo.guru/wiki/Neural_networks_in_spaced_repetition#Futility_of_the_fine-tuning_the_spaced_repetition_algorithm). At that time, it was [Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski) who would push hardest for progress. He kept complaining that "*SuperMemo keeps leaking Nobel Prize value data*". He screamed at me with words verging on abuse: "*implement repetition histories now!*". It was simply a battle of priorities. We had a [new Windows version of SuperMemo](https://supermemo.guru/wiki/SuperMemo_7), the arrival of audio data, the arrival of CD-ROM technology, the arrival of solid competition, incl. Young Digital Poland who beat us to the title of the first software on CD-ROM in Poland by a month or so. We still cherish the claim to the first Windows CD-ROM in Poland. First [SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7) CD-ROM title was actually still produced in the US, but the contents were made entirely in Poland. It was naturally hosted by 100% pure Polish [SuperMemo](https://supermemo.guru/wiki/SuperMemo).

1993年，我自己的想法阻碍了进步。算法的进一步探索是次要的。它们不会给用户带来那么多好处。记忆建模是纯蓝天研究。参见:[微调算法无效](https://supermemo.guru/wiki/Neural_networks_in_spaced_repetition#Futility_of_the_fine-tuning_the_spaced_repetition_algorithm)。在那个时候，是[Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)最努力推动进步。他一直抱怨“*SuperMemo不断泄露诺贝尔奖价值数据*”。他对我大喊大叫，几乎是骂人:“*现在就开始重复历史吧!*”。这只是一场优先权的斗争。我们有一个新的Windows版本的[SuperMemo](https://supermemo.guru/wiki/SuperMemo_7),音频数据的到来,cd - rom技术的到来,坚实的竞争的到来,包括年轻的数字。波兰击败我们的标题第一个软件光盘在波兰的一个月左右。我们仍然珍视在波兰获得第一张Windows CD-ROM光盘的权利。首先，《超级备忘录7》(https://supermemo.guru/wiki/SuperMemo_7)的光盘实际上仍在美国生产，但内容完全在波兰生产。它自然是由100%纯波兰[SuperMemo](https://supermemo.guru/wiki/SuperMemo)。

### 1996: Venture capital

### 1996:风险资本

In February 1996, all obstacles have been cleared, and [SuperMemo](https://supermemo.guru/wiki/SuperMemo) finally started collecting full repetition history data (at that time, it was still added only as an option to prevent clogging lesser systems little unused data). My own repetition history data now reaches largely back to 1992-1993. This is possible due to the fact that all [items](https://supermemo.guru/wiki/Item) in February 1996 still had their last repetition easily derived from the then current interval. I even have quite a number of histories dating back to 1987. In my OCD for data, I recorded the progress of some specific [items](https://supermemo.guru/wiki/Item) manually, and was later able to complete repetition histories by manual editing. My own data is now, therefore, the longest spanning repetition history data in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) in existence. 30 years of data with a massive coverage for 22-25 years of learning. This is a goldmine.

在1996年2月，所有的障碍都被清除了，并且[SuperMemo](https://supermemo.guru/wiki/SuperMemo)最终开始收集完整的重复历史数据(在那时，它仍然只是一个选项，以防止堵塞较少的系统，很少使用的数据)。我自己的重复历史数据现在主要追溯到1992-1993年。这是可能的，因为所有的[项目](https://supermemo.guru/wiki/Item)在1996年2月仍然有他们的最后一次重复很容易从当时的当前间隔。我甚至有相当多的历史可以追溯到1987年。在我的OCD for data中，我手动记录了一些特定的[items](https://supermemo.guru/wiki/Item)的进程，之后通过手动编辑完成了重复历史记录。因此，我自己的数据现在是[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)中最长的跨越重复历史数据。30年的数据覆盖了22-25年的学习。这是一个金矿。

On Sep 29, 1996, Sunday, in the evening, I devoted two hours to sketching up the new algorithm based on the [two component model of memory](https://supermemo.guru/wiki/Two_component_model_of_memory). It all seemed very simple, and requiring little work. SuperMemo has just started collecting repetition histories, so I should have plenty of data at hand. Our focus switched from multimedia courses, like Cross Country, to easier projects, like [Advanced English](https://supermemo.guru/wiki/Advanced_English). It was a good moment, it seemed. Unfortunately, the next day, we got a call from Antek Szepieniec who talked to investors in America with a dream to make [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) the first Polish company at NASDAQ. He excitedly prophesied his belief that there is a good chance for an injection of a few million dollars into our efforts from venture capital. That instantly tossed me into new roles and new jobs. Of bad things, this has delayed [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) by two decades. Of good things, the concept of Hypermedia SuperMemo, aka [Knowledge Machine](https://supermemo.guru/wiki/Knowledge_Machine), aka [incremental reading](https://supermemo.guru/wiki/Incremental_reading) has gained a great deal of momentum in terms of theory and design. Practice trumped science again.

1996年9月29日，星期日的晚上，我花了两个小时来草拟基于[记忆的双成分模型](https://supermemo.guru/wiki/Two_component_model_of_memory)的新算法。一切似乎都很简单，不用费什么力气。SuperMemo刚刚开始收集重复历史记录，所以我手头应该有足够的数据。我们的注意力从像越野这样的多媒体课程转向了更简单的项目，比如[高级英语](https://supermemo.guru/wiki/Advanced_English)。这似乎是一个美好的时刻。不幸的是，第二天，我们接到了来自Antek Szepieniec的电话，他与美国的投资者进行了交谈，他的梦想是让[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)成为纳斯达克的第一家波兰公司。他兴奋地预言，他相信我们很有可能从风险投资中获得几百万美元的投资。这让我立刻得到了新的角色和工作。糟糕的是，这将[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)推迟了20年。超媒体超级备忘录[Hypermedia SuperMemo](https://supermemo.guru/wiki/Knowledge_Machine)，即“知识机器”、“增量式阅读”(https://supermemo.guru/wiki/Incremental_reading)的概念在理论和设计上获得了巨大的发展势头。实践再次战胜了科学。

### 2005: Theoretical approach

### 2005:理论方法

In 2000, with [incremental reading](https://supermemo.guru/wiki/Incremental_reading), and then 2006 with [priority queue](https://supermemo.guru/wiki/Priority_queue), the need for the delay of repetitions, and the need for early review increased dramatically. This called for huge departures from the [optimum spacing](https://supermemo.guru/wiki/Spaced_repetition). The old [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) could not cope with that effectively. The function of [optimum intervals](https://supermemo.guru/wiki/Optimum_interval) had to be expanded into the dimension of time (i.e. [retrievability](https://supermemo.guru/wiki/Retrievability)). We needed a [stability increase](https://supermemo.guru/wiki/Stability_increase) function.

One of the very interesting dynamics of progress in science is that the dendritic explorations of reality often require a critical brain mass to push a new idea through. In 2005, [Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak) and others were largely out of the loop busy with promoting [SuperMemo](https://supermemo.guru/wiki/SuperMemo) as a business. I was on the way to a major breakthrough in [incremental reading](https://supermemo.guru/wiki/Incremental_reading): handling overload. With the emergence of Wikipedia, it suddenly appeared that importing tons of knowledge requires little effort, but low-priority knowledge can easily overwhelm high-priority knowledge by sheer volume. Thus richness undermines the quality of knowledge. My solution to the problem was to employ the [priority queue](https://supermemo.guru/wiki/Priority_queue). It was to be implemented only in 2006. In the meantime, [Gorzelanczyk](https://supermemo.guru/wiki/Edward_Gorzelanczyk) and [Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski) were busy with their own science projects.

在2000年，有了[增量阅读](https://supermemo.guru/wiki/Incremental_reading)，然后在2006年有了[优先队列](https://supermemo.guru/wiki/Priority_queue)，对重复的延迟和对早期审查的需求急剧增加。这需要极大地偏离[最佳间隔](https://supermemo.guru/wiki/Spaced_repetition)。旧的[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)不能有效地处理这个问题。[最优区间](https://supermemo.guru/wiki/Optimum_interval)的功能必须扩展到时间维度(即[可检索性](https://supermemo.guru/wiki/Retrievability))。我们需要一个[稳定性增加](https://supermemo.guru/wiki/Stability_increase)函数。

科学发展中一个非常有趣的动态现象是，对现实的树突状探索通常需要一个关键的大脑团来推动一个新想法通过。2005年，[Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)和其他一些公司忙于将[SuperMemo](https://supermemo.guru/wiki/SuperMemo)推广为一项业务，基本上没有参与其中。我即将在[增量阅读](https://supermemo.guru/wiki/Incremental_reading)方面取得重大突破:处理过载。随着维基百科(Wikipedia)的出现，人们突然意识到，输入大量的知识几乎不需要什么努力，但是低优先级的知识很容易就会因为数量太多而压倒高优先级的知识。因此，知识的丰富性削弱了知识的质量。我的解决方案是使用[优先队列](https://supermemo.guru/wiki/Priority_queue)。2006年才开始实施。与此同时，[Gorzelanczyk](https://supermemo.guru/wiki/Edward_Gorzelanczyk)和[Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)忙于他们自己的科学项目。

Gorzelanczyk used to attend a cybernetics conference in Cracow powered by my early inspiration: [Prof. Ryszard Tadeusiewicz](https://pl.wikipedia.org/wiki/Ryszard_Tadeusiewicz). For his presentation in 2005, Gorzelanczyk suggested we update our memory model. With the deluge of new data in molecular biology, a decade since the last formulation could make a world of difference. I thought that my ideas for finding the formula for building [memory stability](https://supermemo.guru/wiki/Memory_stability) would make a good complement. This initial spark soon gained momentum in exchanges with Murakowski. Without those three brains (i.e. Wozniak, Gorzelanczyk, Murakowski), working in concert, and whipping up the excitement, the next obvious step would not have been made. Using the tools first employed in the [model of intermittent learning in 1990](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula), I decided to find out the function for [stability increase](https://supermemo.guru/wiki/Stability_increase). Once my computer started churning data, interesting titbits of information kept flowing serially. The job was to take just a few evenings. In the end, it took half the winter.

在我早期的灵感的推动下，Gorzelanczyk曾在克拉科夫参加一个控制论会议。[Ryszard Tadeusiewicz教授](https://pl.wikipedia.org/wiki/Ryszard_Tadeusiewicz)。在2005年的演讲中，Gorzelanczyk建议我们更新我们的内存模型。随着分子生物学领域新数据的大量涌现，自上一种配方问世十年以来，情况可能会大不相同。我认为我关于寻找构建[记忆稳定性](https://supermemo.guru/wiki/Memory_stability)的公式的想法将是一个很好的补充。这最初的火花很快在与村上春树的交流中获得了动力。如果没有这三个人(沃兹尼亚克、格泽兰茨克、村上春花)的通力合作，没有他们的激情，就不可能有下一步。使用[1990年的间歇学习模型](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula)中首次使用的工具，我决定找出[stability increase](https://supermemo.guru/wiki/Stability_increase)的函数。一旦我的电脑开始处理大量的数据，有趣的信息就会源源不断地出现。这项工作只需要几个晚上。最后，花了半个冬天。

### 2013: Big picture re-awakening

### 2013年:大画面重新觉醒

Like in 2005, in 2013, the critical brain mass had to build up to push the new solutions through. However, I must give most credit to [Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak). It was he who tipped the scales. With a never-ending battle for the recognition of [SuperMemo](https://supermemo.guru/wiki/SuperMemo)'s leadership and pioneering claims, he demanded we go on with the project and sent me for a short creative vacation to complete it. It was to be just one winter project, and it turned out to be two years, and it still consumes a lot of my time.

On Nov 09, 2014, we took a 26 km walk to discuss the new algorithm. Walktalking is our [best form of brainstorming](https://supermemo.guru/wiki/How_to_solve_any_problem%3F) that always brings great fruits. Next day, we met in a swimming pool joined with Leszek Lewoc, worshipper of big data, who always has a great deal of fantastic ideas (I first met Lewoc in 1996, and his wife was probably writing a thesis about language learning, incl. SuperMemo, as early as in 1992). Simple conclusions from that brainstorming time were to use the [two component model of memory](https://supermemo.guru/wiki/Two_component_model_of_memory) to simplify the approach to the algorithm, simplify the terminology, and make it more human-friendly (no more [A-Factors](https://supermemo.guru/wiki/A-Factor), [U-Factors](https://supermemo.guru/wiki/U-Factor), [R-Factors](https://supermemo.guru/wiki/R-Factor), etc.).

就像在2005年和2013年一样，关键的大脑体积必须建立起来，以推动新的解决方案通过。然而，我必须把大部分功劳归于[Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)。是他改变了局面。为了获得[SuperMemo](https://supermemo.guru/wiki/SuperMemo)的领导地位和先驱性声明的认可，他进行了一场永无休止的战斗，他要求我们继续这个项目，并让我用一个短暂的创意假期来完成它。这本来只是一个冬季项目，结果却花了两年时间，但它仍然占用了我很多时间。

2014年11月9日，我们步行26公里讨论新算法。步行交谈是我们头脑风暴的最佳形式，它总是能带来巨大的成果。(https://supermemo.guru/wiki/How_to_solve_any_problem%3F)第二天，我们在游泳池里遇到了Leszek Lewoc，他是大数据的崇拜者，总是有很多奇妙的想法(我第一次遇见Lewoc是在1996年，他的妻子可能早在1992年就在写一篇关于语言学习的论文，包括SuperMemo)。简单的结论,头脑风暴时间使用(两个组件模型的内存)(https://supermemo.guru/wiki/Two_component_model_of_memory)来简化方法算法,简化的术语,使其更人性化(没有一个[A-因素](https://supermemo.guru/wiki/A-Factor), [U-Factors](https://supermemo.guru/wiki/U-Factor), [r个因子](https://supermemo.guru/wiki/R-Factor),等等)。

## Increase in memory stability with rehearsal

## 通过预演提高记忆的稳定性

To understand [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17), it is helpful to understand the calculations used to figure out the formula for the [increase in memory stability](https://supermemo.guru/wiki/Stability_increase). In 2005, our goal was to find the function of stability increase for any valid level of [R](https://supermemo.guru/wiki/Retrievability) and [S](https://supermemo.guru/wiki/Stability): *SInc*=*f*(R,S). The goals and tools were pretty similar to those used in the quest to build the [model of intermittent learning](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula) (1990).

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

Until 2005, we were not able to formulate a universal formula that would link a repetition with an .[Repetition spacing](https://supermemo.guru/wiki/Spaced_repetition)algorithms were based on a general understanding of how stability increases when so-called optimum inter-repetition intervals are used (defined as intervals that produce a known recall rate that usually exceeds 90%). The term*optimum interval*is used for interval's applicability in learning. The said repetition spacing algorithms also allow for determining an accurate stability increase function for optimum intervals in a matrix form. However, little has been known about the increase in stability for low retrievability levels (i.e. when intervals are not*optimum* , we can now attempt to fill in this gap. Although SuperMemo has been designed to apply the optimum intervals in learning, in real-life situations, users are often forced to delay repetitions for various reasons (such as holiday, illness, etc.). This provides for a substantial dose of repetitions with lower[retrievability](https://supermemo.guru/wiki/Retrievability)in nearly every body of learning material. In addition, in 2002, SuperMemo introduced the concept of a mid-interval repetition that makes it possible to shorten inter-repetition intervals. Although the proportion of mid-interval repetitions in any body of data is very small, for sufficiently large data samples, the number of repetition cases with very low and very high retrievability should make it possible to generalize the finding on the increase in memory stability from the retrievability of 0.9 to the full retrievability range.We have developed a two-step procedure that was used to propose a symbolic formula for the increase in stability for different[retrievability](https://supermemo.guru/wiki/Retrievability)levels in**data sets characterized by low and uniform difficulty**(so-called well-formulated knowledge data sets that are easy to retain in memory). Well-formulated and uniform learning material makes it easy to distill a pure process of long-term memory consolidation through rehearsal. As discussed elsewhere in this article, ill-formulated knowledge results in superposition of independent consolidation processes and is unsuitable for the presented analysis.

为了理解[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)，理解用来得出[增加内存稳定性](https://supermemo.guru/wiki/Stability_increase)公式的计算是有帮助的。在2005年，我们的目标是找到任何有效水平的[R](https://supermemo.guru/wiki/Retrievability)和[S](https://supermemo.guru/wiki/Stability)的稳定性增长函数:*SInc*=*f*(R,S)。这些目标和工具与在探索中用于构建[间歇学习模型](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula)的目标和工具非常相似(1990)。

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

直到2005年,我们无法制定一个通用公式,将重复的链接。[重复间隔](https://supermemo.guru/wiki/Spaced_repetition)算法是基于一般的理解如何稳定增加使用所谓的最佳inter-repetition间隔时(定义为间隔产生一个已知的召回率,通常超过90%)。最优区间*一词用于表示区间在学习中的适用性。所述重复间隔算法还允许以矩阵形式确定精确的最优间隔的稳定性增加函数。然而，对于低可回收性水平的稳定性的增加，我们知之甚少(例如，当间隔不是“最佳”时，我们现在可以尝试填补这个空白。虽然SuperMemo被设计成在学习中应用最佳间隔，但在现实生活中，用户经常因为各种原因(如假期、疾病等)被迫推迟重复学习。这提供了大量的重复和较低的[检索能力](https://supermemo.guru/wiki/Retrievability)几乎每一个学习材料的身体。此外，SuperMemo在2002年引入了中间重复的概念，这使得缩短重复间隔成为可能。虽然mid-interval重复在任何身体的数据的比例非常小,足够大的样本数据,重复用例的数量非常低和非常高的可回收性应该能够概括这一发现内存的增加稳定范围从0.9到完整的可回收性的可恢复性。我们开发了一个两步过程,提出一个象征性的公式用于稳定的增加对不同(可恢复性)(https://supermemo.guru/wiki/Retrievability)水平在* *数据集的特点是低和统一的难度* *(所谓的编制知识很容易保留在内存中数据集)。组织严密、内容统一的学习材料，便于通过排演提炼出一个纯粹的长期记忆巩固过程。正如本文其他部分所讨论的，表述不当的知识会导致独立合并过程的叠加，不适合本文的分析。

### Two-step computation

### 两步计算

In SuperMemo 17, it is possible to run through the full record of repetition history to collect [stability increase](https://supermemo.guru/wiki/Stability_increase) data. This makes it possible to plot a graphic representation of the *SInc[]* matrix. That matrix may then be used in an effort to find a symbolic approximation of the function of [stability increase](https://supermemo.guru/wiki/Stability_increase). The same reasoning was used in 2005. The procedure was much simpler though. This can then be used to better understand [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17):

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

The two-step procedure for determining the function of the increase in memory stability :

在SuperMemo 17中，可以通过完整的重复历史记录来收集[stability increase](https://supermemo.guru/wiki/Stability_increase)数据。这使得绘制*SInc[]*矩阵的图形表示成为可能。然后，这个矩阵可能会被用于寻找[稳定性增加](https://supermemo.guru/wiki/Stability_increase)函数的符号近似值。2005年也采用了同样的理由。不过，这个过程要简单得多。这可以用来更好地理解[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17):

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

确定增加的记忆稳定性的函数的两步程序:

### Computing stability increase

### 计算稳定增加

The matrix of [stability increase](https://supermemo.guru/wiki/Stability_increase) (*SInc[]*) was computed in **Step 1**. In 2005, we could take any initial hypothetical plausible value of *SInc*. Today, as we know the approximate nature of the function, we can speed up the process and make it non-iterative (see [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)).

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

Let us define a procedure for computing stability of memory for a given rehearsal pattern. This procedure can be used to compute stability on the basis of known grades scored in learning (practical variant) and to compute stability on the basis of repetition timing only (theoretical variant). The only difference between the two is that the practical variant allows of the correction of stability as a result of stochastic forgetting reflected by failing grades.

矩阵[stability increase](https://supermemo.guru/wiki/Stability_increase) (*SInc[]*)在**步骤1**中计算。在2005年，我们可以取任何一个初始的似是而非的值*SInc*。今天，当我们知道这个函数的近似性质时，我们可以加速这个过程并使其非迭代化(参见[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17))。

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

让我们定义一个用于计算给定排练模式的内存稳定性的过程。此程序可用于计算稳定性的基础上已知的分数在学习(实践变体)和计算稳定性的基础上的重复计时(理论变体)。两者之间的唯一区别是，实用变量允许校正稳定性，这是不及格所反映的随机遗忘的结果。

In the following passages we will use the following notation:

- S(t) - memory stability at time t
- S[r] - memory stability after the rth repetition (e.g. with S[1] standing for memory stability after learning a new piece of knowledge)
- R(S,t) - memory retrievability for stability S and time t (we know that R=exp-k*t/S and that k=ln(10/9))
- *SInc*(R,S) - increase in stability as a result of a rehearsal for retrievability R and stability S such that *SInc*(R(S,t),S(t))=S(t*)/S(t')=S[r]/S[r-1] (where: t' and t* stand for the time of rehearsal as taken before and after memory consolidation with t*-t' being indistinguishable from zero)*

在下面的段落中，我们将使用以下的符号:

- S(t) - t时刻的记忆稳定性

- S[r] -第一次重复后的记忆稳定性(例如，S[1]代表学习新知识后的记忆稳定性)

- R(S,t) -稳定性S和时间t的记忆检索能力(我们知道R=ex -k*t/S, k=ln(10/9))

- * SInc * (R, S) -增加稳定的可恢复性的彩排R和稳定S这样* SInc * (R (S, t), S (t)) = S (t *) / S (t) =年代[R] / S (r1)(地点:t, t *代表前后彩排的时间记忆的巩固和t * - t的区别零)*

Our goal is to find the function of stability increase for any valid level of R and S: *SInc*=*f*(R,S).

If we take any plausible initial value of *SInc*(R,S), and use S[1]=S1, where S1 is the stability derived from the memory decay function after the first-contact review (for optimum inter-repetition interval), then for each repetition history we can compute S using the following iteration:

我们的目标是找到R和S的任意有效水平的稳定性增长函数:*SInc*=*f*(R,S)。

如果取任意一个似是而非的初值*SInc*(R,S)，用S[1]=S1，其中S1是第一次接触检查后记忆衰减函数的稳定性(对于最佳重复间隔)，那么对于每个重复历史，我们可以使用以下迭代计算S:

```
r:=1;
S[r]:=S1
repeat
  t:=Interval[r]; // where: Interval[r] is taken from a learning process (practical variant) or from the investigated review pattern (theoretical variant)
  Pass:=(Grade[r]>=3); // where: Grade[r] is the grade after the r-th interval (practical variant) or 4 (theoretical variant)
  R:=Ret(S[r],t);
  if Pass then
     S[r+1]:=S[r]*SInc[R,S[r]]
     r:=r+1;
 else begin
    r:=1;
    S[r]:=S1;
    end;
 until (r is the last repetition)
```

In , we can use the first-interval graph to determine S, which is progressively shorter after each failing grade.

We start the iterative process with a hypothetical initial value of matrix *SInc[R,S]*, e.g. with all entries arbitrarily set to [E-Factor](https://supermemo.guru/wiki/E-Factor) as in [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2).

We can then keep using the above procedure on the existing repetition history data to compute a new value of *SInc[R,S]* that provides a lesser [deviation](https://supermemo.guru/wiki/Deviation) from grades scored in the actual learning process (we use differences *R-Pass* for the purpose).

在中，我们可以使用第一个区间图来确定S, S在每次不及格之后会逐渐变短。

我们以一个假设的矩阵*SInc[R,S]*的初始值开始迭代过程，例如，将所有条目任意设置为[E-Factor](https://supermemo.guru/wiki/E-Factor) (https://supermemo.guru/wiki/Algorithm_SM-2)。

然后，我们可以继续对现有的重复历史数据使用上面的过程来计算一个新的值*SInc[R,S]*，它提供了一个较小的[偏差](https://supermemo.guru/wiki/Deviation)从实际学习过程中得到的分数(我们使用差异*R- pass *的目的)。

Incremental improvements are possible if we observe that:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

- if Pass=true and S[r]<Interval[r] then *SInc[R,S[r-1]]* entry is underestimated (and can be corrected towards Interval[r]/S[r]**SInc[R,S[r-1]]*)
- if Pass=false and S[r]>Interval[r] then *SInc[R,S[r-1]]* entry is overestimated

如果我们观察到:

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

- 如果Pass=true,S[r]

- 如果Pass=false,S[r]>Interval[r]，则*SInc[r,S[r-1]]*项被高估

We can iterate over *SInc[]* to bring its value closer and closer to the alignment with grades scored in the learning process.

This approach makes it possible to arrive at the same final    

In [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17), instead of the above bang-bang incremental approach, we use actual [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) to provide a better estimate of [retrievability](https://supermemo.guru/wiki/Retrievability), which can then be used to correct the estimated [stability](https://supermemo.guru/wiki/Stability). The ultimate stability estimate combines the theoretical prediction of [retrievability](https://supermemo.guru/wiki/Retrievability), actual [recall](https://supermemo.guru/wiki/Recall) taken from [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) (weighted for the availability of data), and the actual grade combined with the interval as in the above reasoning. By combining those three sources of information, [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) can provide stability/interval estimates without the need to iterate over the *SInc[]* matrix over and over again.

我们可以对*SInc[]*进行迭代，使其价值与学习过程中的分数越来越接近。

这种方法使我们有可能得到相同的结果

在[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17),而不是上面的继电器式控制增量的方法,我们使用实际[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)提供一个更好的估计[可恢复性](https://supermemo.guru/wiki/Retrievability),然后可以用来正确估计[稳定](https://supermemo.guru/wiki/Stability)。最终稳定估计相结合的理论预测[可恢复性](https://supermemo.guru/wiki/Retrievability),实际[召回](https://supermemo.guru/wiki/Recall)从[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)(加权)数据的可用性,和实际的年级结合区间在上面的推理。通过结合这三个信息源，[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)可以提供稳定性/区间估计，而不需要反复迭代*SInc[]*矩阵。

### Symbolic formula for stability increase

### 增加稳定性的符号公式

After many iterations, we obtain a value of *SInc* that minimizes the error. The procedure is convergent. With the matrix of [stability increase](https://supermemo.guru/wiki/Stability_increase) available, we can look for a symbolic formula expressing the increase in stability.

经过多次迭代，我们得到了一个使误差最小化的值*SInc*。这个过程是收敛的。随着[稳定性增加](https://supermemo.guru/wiki/Stability_increase)矩阵的可用，我们可以寻找一个表示稳定性增加的符号公式。

#### Dependence of stability increase on S

#### 稳定性对S的依赖增加

Predictably, *SInc* decreases with an increase in *S*. This phenomenon, named [stabilization decay](https://supermemo.guru/wiki/Stabilization_decay) can now be inspected in [SuperMemo for Windows](https://supermemo.guru/wiki/SuperMemo_for_Windows). Here are the original findings from 2005:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

In Step 2, we will use the   .

We can now use any gradient descent algorithm to evaluate symbolic candidates for SInc that provide the best fit to the matrix SInc derived above.

可以预见，*SInc*随着*S*的增加而减少。这个现象被命名为[decay](https://supermemo.guru/wiki/ization_decay)，现在可以在[SuperMemo for Windows](https://supermemo.guru/wiki/SuperMemo_for_Windows)中查看。以下是2005年的原始调查结果:

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

在步骤2中，我们将使用。

我们现在可以使用任何梯度下降算法来计算SInc的符号候选值，这些候选值提供了对上述矩阵SInc的最佳拟合。

When inspecting the SInc matrix, we immediately see that SInc as a function of S for constant R is excellently described with a negative power function as in the exemplary data set below:

当考察SInc矩阵时，我们立刻发现，对于R为常数时，SInc作为S的函数，用一个负幂函数来描述是很好的，如下例数据集所示:

[![SInc as a function of S for constant R is excellently described with a negative power function](https://supermemo.guru/images/0/0e/SInc-vs-S.gif)](https://supermemo.guru/wiki/File:SInc-vs-S.gif)

Which is even more clear in the log-log version of the same graph:

这一点在同一张图的log-log版本中更加明显:

[![Log(SInc)-vs-log(S).gif](https://supermemo.guru/images/4/4e/Log%28SInc%29-vs-log%28S%29.gif)](https://supermemo.guru/wiki/File:Log(SInc)-vs-log(S).gif)

The conclusion on the        关于

#### Dependence of stability increase on R

#### 稳定性对R的依赖增加

As predicted by the [spacing effect](https://supermemo.guru/wiki/Spacing_effect), *SInc* is greater for lower levels of *R*. Note, however, that the procedure used in 2005 might have introduced an artifact: the survival of a memory trace over time would linearly contribute to the new stability estimate. This is problematic due to the stochastic nature of [forgetting](https://supermemo.guru/wiki/Forgetting). Longer survival of memories may then be a matter of chance. In [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17), more evidence is used to estimate stability, and the *survival interval* is weighed up with all other pieces of evidence.

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

When we look for the function reflecting the relationship of       . That conclusion should have a major impact on learning strategies.

正如[间隔效应](https://supermemo.guru/wiki/Spacing_effect)所预测的，*R*水平越低，*SInc*越高。但是，请注意，2005年使用的过程可能引入了一个工件:随着时间的推移，内存跟踪的存活期将对新的稳定性估计值做出线性贡献。这是有问题的，因为[遗忘](https://supermemo.guru/wiki/forget)是随机的。更长时间的记忆可能是偶然的。在[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)中，使用更多的证据来估计稳定性，并将*生存区间*与所有其他证据进行权衡。

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

当我们寻找函数反映的关系时。这个结论应该会对学习策略产生重大影响。

[![SInc as a function of R for constant S can be quite well approximated with a negative exponential function](https://supermemo.guru/images/2/29/SInc-vs-R.gif)](https://supermemo.guru/wiki/File:SInc-vs-R.gif)

And the semi-log version of the same graph with a linear approximation trendline intercept set at 1:

和半对数版本的同一图与线性近似趋势线截距设为1:

[![SInc-vs-log(R).gif](https://supermemo.guru/images/b/b2/SInc-vs-log%28R%29.gif)](https://supermemo.guru/wiki/File:SInc-vs-log(R).gif)

Interestingly, stability increase for retrievability of 100% may be less than 1. Some molecular research indicates increased lability of memories at review time. This is one more piece of evidence that repetitive cramming can hurt you not only by costing you extra time.

有趣的是，100%的可回收性的稳定性增加可能小于1。一些分子研究表明复习时记忆能力增强。这是另一个证据，反复的抽筋不仅会浪费你额外的时间，还会伤害你。

#### Dependence of stability increase on retrievability (2018)

#### 稳定性增加对可回收性的依赖(2018)

Despite all the algorithmic differences and artifacts, the dependence of [stability increase](https://supermemo.guru/wiki/Stability_increase) on [retrievability](https://supermemo.guru/wiki/Retrievability) for [well-formulated knowledge](https://supermemo.guru/wiki/20_rules) is almost identical with that derived from data produced 13 years later by [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17).

Recall that in [SuperMemo](https://supermemo.guru/wiki/SuperMemo), we use [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) to provide a better estimate of [retrievability](https://supermemo.guru/wiki/Retrievability). This is then used to correct the estimated [stability](https://supermemo.guru/wiki/Stability). By combining several sources of information, [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) can provide more accurate [stability](https://supermemo.guru/wiki/Stability) estimates. There is still the old artifact of the survival of a memory trace that would linearly contribute to the new stability. This artifact can be weighed out parametrically. However, each time [SuperMemo](https://supermemo.guru/wiki/SuperMemo) tries to do that, its performance metrics drop.

Despite all the improvements, and much larger data sets (esp. for low R), the dependence of [stability increase](https://supermemo.guru/wiki/Stability_increase) on [retrievability](https://supermemo.guru/wiki/Retrievability) for easy items seems set in stone.

尽管算法差异和工件,的依赖[稳定增加](https://supermemo.guru/wiki/Stability_increase)[可恢复性](https://supermemo.guru/wiki/Retrievability)上[编制知识](https://supermemo.guru/wiki/20_rules)是几乎相同的,来源于生产13年后的数据[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)。

回想一下，在[SuperMemo](https://supermemo.guru/wiki/SuperMemo)中，我们使用[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)来更好地估计[可检索性](https://supermemo.guru/wiki/Retrievability)。然后用它来修正估计的[稳定性](https://supermemo.guru/wiki/Stability)。通过合并多个信息源，[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)可以提供更准确的[稳定性](https://supermemo.guru/wiki/Stability)估计。仍然存在着旧的人为的记忆痕迹，它会线性地增加新的稳定性。这个工件可以用参数法称出重量。然而，每当[SuperMemo](https://supermemo.guru/wiki/SuperMemo)试图这样做时，它的性能指标就会下降。

尽管所有的改进，以及更大的数据集(特别是低R)，[稳定性增加](https://supermemo.guru/wiki/Stability_increase)对[可检索性](https://supermemo.guru/wiki/Retrievability)的依赖似乎是固定不变的。	

This perfect picture collapses when we add [difficult](https://supermemo.guru/wiki/Difficulty) knowledge into the mix. This is partly due to reducing the *long survival* artifact mentioned above. For that reason, new SuperMemos do not rely on this seemingly well-confirmed memory formula:

当我们将[困难](https://supermemo.guru/wiki/difficult)知识添加到混合中时，这幅完美的图画就崩塌了。这部分是由于减少了上面提到的*长生存期*工件。出于这个原因，新的超级备忘录并不依赖于这个似乎得到充分证实的记忆公式:

[![Stability increase for easy knowledge at different retrievability levels](https://supermemo.guru/images/thumb/d/dc/Stability_increase_as_a_function_of_memory_retrievability_for_easy_knowledge.png/600px-Stability_increase_as_a_function_of_memory_retrievability_for_easy_knowledge.png)](https://supermemo.guru/wiki/File:Stability_increase_as_a_function_of_memory_retrievability_for_easy_knowledge.png)

> ***Figure:** The strength of long-term memory depends on the timing of review. For well-formulated knowledge, long delays in review produce large increase in memory stability. Optimum review should balance that increase with the probability of forgetting. In the presented graph, the relationship between stability increase and the logarithm of retrievability (log(R)) is linear. Log(R) expresses time. Nearly 27,000 repetitions have been used to plot this graph. Observed memory stability before review spanned from 2 days to 110 days. Maximum increase in stability of nearly 10-fold was observed for lowest levels of retrievability. The stability increase matrix was generated with Algorithm SM-17 in SuperMemo 17*
>
> ***图片：**长期记忆的强度取决于复习的时间。对于结构良好的知识，复习的长时间延迟会大大增加记忆的稳定性。最佳复习应该在增加遗忘率和增加遗忘率之间取得平衡。在本图中，稳定性的增加与可检索性的对数(log(R))呈线性关系。Log (R)表达的时间。这幅图已经重复了将近27000次。复查前观察到的记忆稳定性从2天到110天不等。在可回收性最低的情况下，稳定性增加了近10倍。用算法SM-17在SuperMemo 17*中生成稳定性增加矩阵

### Memory stability increase formula

### 记忆稳定性增加公式

With the matrix of [stability increase](https://supermemo.guru/wiki/Stabilization) at hand, we could look for a symbolic expression of stability increase. The equation found in 2005 will later be referred to as *Eqn. SInc2005*. Note that formulas used in [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) differ:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

For constant knowledge difficulty, we applied two-dimensional surface-fitting to obtain the symbolic formula for . We have used a modified Levenberg-Marquardt algorithm with a number of possible symbolic function candidates that might accurately describe*SInc*as a function of S and R. The algorithm has been enhanced with a persistent random-restart loop to ensure that the global maxima be found. We have obtained the best results with the following formula(Eqn. SInc2005)

有了[稳定增长](https://supermemo.guru/wiki/)矩阵在手，我们可以寻找稳定增长的符号表达式。2005年发现的这个方程后来被称为*Eqn。SInc2005 *。注意，在[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)中使用的公式有所不同:

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

对于常知识难度，我们利用二维曲面拟合得到我们使用了一个改进的Levenberg-Marquardt算法，该算法有许多可能的符号函数候选项，这些候选项可能准确地将*SInc*描述为S和r的函数。我们用以下公式(Eqn)得到了最好的结果。SInc2005)

> *SInc*=*a*S*-b**e*c*R+*d*
>
> where:
>
> - *SInc* - increase in memory stability as a result of a successful repetition (quotient of stability S before and after the repetition)
> - R - retrievability of memory at the moment of repetition expressed as the probability of recall in percent
> - S - stability of memory before the repetition expressed as an interval generating R=0.9
> - *a*, *b*, *c*, *d* - parameters that may differ slightly for different data sets
> - e - base of the natural logarithm
>
> *SInc*=*a*S*-b**e*c*R+*d*
>
> 上式中：
>
> - *SInc* -由于成功的重复而增加的记忆稳定性(重复前后稳定性的商数)
> - R -重复时记忆的可检索性，用回忆的概率百分比表示
>
> - S -记忆稳定性在重复之前表示为一个间隔，产生R=0.9
>
> - *a*， *b*， *c*， *d* -参数可能略有不同的数据集
>
> - e -自然对数的底数

The parameters *a*, *b*, *c*, *d* would vary slightly for different data sets, and this might reflect user-knowledge interaction variability (i.e. different sets of learning material presented to different users may result in a different distribution of difficulty as well as with different grading criteria that may all affect the ultimate measurement).

For illustration, an average value of ,*b* ,*d*taken from several data sets has been found to be:*a=76* ,*c=-0.031* , with*c*varying little from set to set, and with*a*and*d*showing relatively higher variance. See the example:[How to use the formula for computing memory stability?](http://supermemopedia.com/wiki/How_to_use_the_formula_for_computing_me
mory_stability?)

b参数* *,* *,* *,* d *将为不同的数据集略有不同,这可能反映出user-knowledge交互变化(即不同的学习材料提交给不同的用户可能会导致不同的难度分布以及不同的评分标准,所有可能影响最终的测量)。

为说明，取几个数据集的平均值，*b*，*d*分别为:*a=76*，*c=-0.031*，*c *各集变化不大，* a*，*d*的方差较大。参见示例:[如何使用计算内存稳定性的公式?](

## Conclusions derived from stability increase formula

## 由稳定性增加公式得出结论

The above formula for [stability increase](https://supermemo.guru/wiki/Stability_increase) differs slightly from later findings. For example, it seems to underestimate the decline in [stability increase](https://supermemo.guru/wiki/Stability_increase) with S (low *b*). However, it can be used to derive a great deal of interesting conclusions.

以上关于[稳定性增加](https://supermemo.guru/wiki/Stability_increase)的公式与后来的发现略有不同。例如，它似乎低估了S(低*b*)的[稳定性下降](https://supermemo.guru/wiki/Stability_increase)。然而，它可以用来得出大量有趣的结论。

### Linear increase in value of review over time

### 随着时间的推移，评审值呈线性增长

Due to the [spacing effect](https://supermemo.guru/wiki/Spacing_effect) the potential for an increase in [memory stability](https://supermemo.guru/wiki/Memory_stability) keeps growing over time in nearly linear fashion:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

由于[空间效应](https://supermemo.guru/wiki/Spacing_effect)，增加[内存稳定性](https://supermemo.guru/wiki/Memory_stability)的潜力随着时间的推移几乎呈线性增长:

档案警告:[为何使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

The above formula produced     ).

以上公式制作)。

[![The graph of changes of SInc in time. This graph was generated for S=240 using Eqn. SInc2005](https://supermemo.guru/images/d/d0/SInc-vs-time.gif)](https://supermemo.guru/wiki/File:SInc-vs-time.gif)

> ***Figure:** The graph of changes of SInc in time. This graph was generated for S=240 using Eqn. SInc2005.*
>
> ***图片：**SInc随时间的变化曲线。这个图是使用Eqn为S=240生成的。SInc2005。*

The nearly linear dependence of        的近似线性相关  

### Expected increase in memory stability

### 预期提高内存稳定性

Optimization of learning may use various criteria. We may optimize for a specific [recall](https://supermemo.guru/wiki/Recall) level or for maximization of the [increase in memory stability](https://supermemo.guru/wiki/Stability_increase). In both cases, it is helpful to understand the expected level of [stability increase](https://supermemo.guru/wiki/Stability_increase).

优化学习可以使用各种标准。我们可以优化特定的[收回](https://supermemo.guru/wiki/Recall)级别，或者优化[增加内存稳定性](https://supermemo.guru/wiki/Stability_increase)级别。在这两种情况下，了解[稳定性增加](https://supermemo.guru/wiki/Stability_increase)的预期级别是有帮助的。

Let's define the expected value of the increase in memory stability as:

我们将增加的内存稳定性的期望值定义为:

> E(*SInc*)=*SInc**R
>
> where:
>
> - R - retrievability
> - *SInc* - increase in stability
> - E(*SInc*) - expected probabilistic increase in stability (i.e. the increase defined by *SInc* and diminished by the possibility forgetting)
>
> E(*SInc*)=*SInc**R
>
> 上式中：
>
> - R -可回收性
> - *SInc* -增加稳定性
>
> - E(*SInc*) -稳定性增加的期望概率(即增加由*SInc*定义，减少由可能性遗忘)

The formula for [stability increase](https://supermemo.guru/wiki/Stability_increase) derived in 2005 produced a major surprise. We used to claim that the best speed of learning can be achieved with the [forgetting index](https://supermemo.guru/wiki/Forgetting_index) of 30-40%. Eqn [SInc2005](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#SInc2005) seemed to indicate that very low [retention](https://supermemo.guru/wiki/Retention) can bring pretty good memory effects. Due to the scarcity of low-R data back in 2005, those conclusions need to be taken with caution:

2005年推导出的“稳定增长”公式(https://supermemo.guru/wiki/Stability_increase)让人大吃一惊。我们曾经声称，最好的学习速度可以通过30-40%的[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)来实现。Eqn [2005](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#SInc2005)似乎表明，非常低的[保留率](https://supermemo.guru/wiki/Retention)可以带来很好的记忆效果。由于2005年低r数据的缺乏，这些结论需要谨慎对待:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

From Eqn  *SInc**a**-b**c*R*d**ESInc*

档案警告:为什么使用literal archives?

从Eqn *Slnca-b**cRd* *ESlnc*

[![Expected increase in memory stability E(SInc) as a function of retrievability R for stability S](https://supermemo.guru/images/c/ca/Consolidation_curve_E%28Sinc%29%3Df%28R%29_%282005%29.gif)](https://supermemo.guru/wiki/File:Consolidation_curve_E(Sinc)%3Df(R)_(2005).gif)

> ***Figure:** **Consolidation curve:** Expected increase in memory stability* E(SInc) *as a function of retrievability R for stability S derived from Eqn (SInc2005). Using the terminology known to users of SuperMemo, the maximum expected increase in memory stability for short intervals occurs for the forgetting index equal to 60%! This also means that the maximum forgetting index allowed in SuperMemo (20%) results in the expected increase in stability that is nearly 80% less than the maximum possible (if we were only ready to sacrifice high retention)*
>
> ***图:** **整合曲线:**内存稳定性的预期增加* E(SInc) * Eqn稳定性的可检索性R(自2005年起)的函数。使用SuperMemo用户所知道的术语，短期内记忆稳定性的最大预期增长发生在遗忘指数等于60%的时候!这也意味着SuperMemo中允许的最大遗忘指数(20%)将导致稳定性的预期增加，这比可能的最大值少了近80%(如果我们只准备牺牲高留存)*

[![Expected increase in memory stability E(SInc) as a function of retrievability R and S based on Eqn SInc2005](https://supermemo.guru/images/thumb/2/27/E%28SInc%29_as_function_of_R_for_S.jpg/600px-E%28SInc%29_as_function_of_R_for_S.jpg)](https://supermemo.guru/wiki/File:E(SInc)_as_function_of_R_for_S.jpg)

> ***Figure:** Expected increase in memory stability E(SInc) as a function of retrievability R and stability S as derived from Eqn SInc2005*
>
> **图:**自2005年以来，从Eqn得到的内存稳定性E(SInc)随可检索性R和稳定性S的预期增加*

### Memory complexity in spaced repetition

### 记忆在间隔重复中的复杂性

Memory [stability](https://supermemo.guru/wiki/Stability) in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) depends on the quality of review which depends on [memory complexity](https://supermemo.guru/wiki/Memory_complexity). As early as in 1984, I used that principle in my own learning in what later became known as the **minimum information principle**. For effective review, knowledge associations need to be simple (even if knowledge itself is complex). [Items](https://supermemo.guru/wiki/Item) may build a complex structure, but individual memories subject to review should be [atomic](https://supermemo.guru/wiki/Atomic_memory). In 2005, we found a formula that governs the review of complex memories.

记忆[稳定性](https://supermemo.guru/wiki/Stability)在[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)取决于审查的质量，这取决于[记忆的复杂性](https://supermemo.guru/wiki/Memory_complexity)。早在1984年，我就在自己的学习中使用了这个原则，后来被称为“最小信息原则”。为了有效的复习，知识关联需要简单(即使知识本身是复杂的)。[项目](https://supermemo.guru/wiki/Item)可以构建一个复杂的结构，但个人记忆的审查应该是[原子](https://supermemo.guru/wiki/Atomic_memory)。在2005年，我们发现了一个控制复杂记忆的公式。

Georgios Zonnios was once an inquisitive teen user of [SuperMemo](https://supermemo.guru/wiki/SuperMemo). Today, he is an education innovator, and a rich creative contributor to many of ideas behind SuperMemo (incl. [Neurostatistical Model of Memory](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory). He noticed:

[Stability](https://supermemo.guru/wiki/Stability) in the formula for stability of complex items is like resistance in an electronic circuit: many parallel resistors allow of leaks in the current

Incidentally, in the early days of [incremental reading](https://supermemo.guru/wiki/Incremental_reading), Zonnios independently arrived at the concept of [incremental writing](https://supermemo.guru/wiki/Incremental_writing), which today may seem like an obvious step in employing the tools of [incremental reading](https://supermemo.guru/wiki/Incremental_reading) in [creativity](https://supermemo.guru/wiki/Creativity). This article has also been written by means of [incremental writing](https://supermemo.guru/wiki/Incremental_writing).

This is how memories for complex items have been described and analyzed in 2005:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

Georgios Zonnios曾经是一个好奇的青少年用户[SuperMemo](https://supermemo.guru/wiki/SuperMemo)。如今，他是一名教育创新者，也是SuperMemo[包括:记忆的神经统计模型](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory)背后许多想法的富有创造力的贡献者。他注意到:

[稳定性](https://supermemo.guru/wiki/Stability)复杂物品稳定性的公式就像电子电路中的电阻:许多并联电阻允许电流中的泄漏

顺便说一句,在早期的增量阅读(https://supermemo.guru/wiki/Incremental_reading),独立Zonnios抵达的概念[增量写](https://supermemo.guru/wiki/Incremental_writing),现在似乎是一个明显的一步使用的工具[增量阅读](https://supermemo.guru/wiki/Incremental_reading)[创造力](https://supermemo.guru/wiki/Creativity)。本文也是通过[增量式写作](https://supermemo.guru/wiki/Incremental_writing)编写的。

在2005年，人们是这样描述和分析复杂物品的记忆的:

档案警告:[为何使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

The    

- increased [interference](https://supermemo.guru/wiki/Interference) with other pieces of information
- difficulty in uniform stimulation of memory trace sub-components at review time

The

- 增加对其他信息的[干扰](https://supermemo.guru/wiki/Interference)

- 难以在复习时均匀刺激记忆痕迹子成分

Both effects can be counteracted with the application of [appropriate representation of knowledge](https://supermemo.guru/wiki/20_rules) in the learning process.

Let us see how [complexity](https://supermemo.guru/wiki/Complexity) of knowledge affects the build up of [memory stability](https://supermemo.guru/wiki/Memory_stability).

Imagine we would like to learn the following: *Marie Sklodowska-Curie was a sole winner of the 1911 Nobel Prize for Chemistry.* We can take two approaches: one in which knowledge is kept complex, and one with easy formulations. In a complex variant, a double [cloze](https://supermemo.guru/wiki/Cloze) might have been formulated for the purpose of learning the name of Marie Curie and the year in which she received the Nobel Prize.

这两种效果都可以通过在学习过程中应用[适当的知识表示](https://supermemo.guru/wiki/20_rules)来抵消。

让我们看看知识的[复杂性](https://supermemo.guru/wiki/)如何影响[记忆稳定性](https://supermemo.guru/wiki/Memory_stability)的建立。

*玛丽·斯克洛道夫斯卡-居里是1911年诺贝尔化学奖的唯一得主。我们可以采取两种方法:一种是保持知识的复杂性，另一种是简化公式。在一个复杂的变体中，双[cloze](https://supermemo.guru/wiki/Cloze)可能是为了学习玛丽·居里的名字和她获得诺贝尔奖的年份而形成的。

> *Q: [...] was a sole winner of the [...] Nobel Prize for Chemistry*
>
> *A: Marie Sklodowska-Curie, 1911*	
>
> *Q*问:[…]是[…]的唯一赢家。诺贝尔化学奖
>
> *A:玛丽·斯克洛道夫斯卡-居里，1911年*

In a simple variant, this double cloze would be split and the Polish maiden name would be made optional and used to create a third cloze:

在一个简单的变体中，这个双完形填空将被拆分，而波兰娘家姓将成为可选项，并用于创建第三个完形填空:

> *Q: [...] was a sole winner of the 1911 Nobel Prize for Chemistry*
> *A: Marie (Sklodowska-)Curie*
>
> *Q: Marie Sklodowska-Curie was a sole winner of the [...](year) Nobel Prize for Chemistry*
> *A: 1911*
>
> *Q: Marie [...]-Curie was a sole winner of the 1911 Nobel Prize for Chemistry*
> *A: Sklodowska*
>
> *Q*: [...他是1911年诺贝尔化学奖的唯一得主
>
> *A*：居里夫人
>
> *Q*: Marie Sklodowska-Curie是诺贝尔化学奖的唯一获奖者
>
> *A*: 1911年
>
> *Q*:玛丽[..]居里是1911年诺贝尔化学奖的唯一得主
>
> *A*: Sklodowska

In addition, in the simple variant, a thorough approach to learning would require formulating yet two cloze deletions, as Marie Curie was also a winner of 1903 Nobel Prize for Physics (as well as other awards):

此外，在简单的变体中，一个彻底的学习方法需要形成两个完形填空的删除，因为玛丽·居里也是1903年诺贝尔物理学奖(以及其他奖项)的得主:

> *Q: Marie Sklodowska-Curie was a sole winner of the 1911 Nobel Prize for [...]*
> *A: Chemistry*
>
> *Q: Marie Sklodowska-Curie was a sole winner of the 1911 [...]*
> *A: Nobel Prize (for Chemistry)*
>
> *Q*:玛丽·斯克洛道夫斯卡-居里是1911年诺贝尔奖的唯一得主
>
> *A*:化学
>
> *Q*:玛丽·斯克洛道夫斯卡-居里是1911年诺贝尔和平奖的唯一得主
>
> *A*:诺贝尔化学奖

Let us now consider the original composite double [cloze](https://supermemo.guru/wiki/Cloze). For the sake of argument, let's assume that remembering the year 1911, and the name *Curie* is equally difficult. The [retrievability](https://supermemo.guru/wiki/Retrievability) of the composite memory trace (i.e. the entire double cloze) will be a product of the retrievability for its subtraces. This comes from the general rule that memory traces, in most cases, are largely independent. Although [forgetting](https://supermemo.guru/wiki/Forgetting) one trace may increase the probability of forgetting the other, in a vast majority of cases, as proved by experience, separate and different questions pertaining to the same subject can carry an entirely independent learning process, in which recall and forgetting are entirely unpredictable. Let us see how treating probabilities of recall as independent events affects the [stability](https://supermemo.guru/wiki/Stability) of a composite memory trace:

现在让我们考虑最初的复合双拼[cloze](https://supermemo.guru/wiki/Cloze)。为了便于讨论，让我们假设记住1911年和“居里”这个名字同样困难。复合内存跟踪的[retrievability](https://supermemo.guru/wiki/Retrievability)将是其子跟踪的可检索性的产物。这源于一个普遍规律:在大多数情况下，记忆痕迹在很大程度上是独立的。尽管[遗忘](https://supermemo.guru/wiki/Forgetting)一个跟踪可能会增加忘记了其他的可能性,在绝大多数情况下,经验证明,独立和不同的问题属于同一主题可以携带一个完全独立的学习过程,回忆和遗忘是完全不可预测的。让我们看看如何处理概率召回作为独立的事件影响[稳定性](https://supermemo.guru/wiki/Stability)的复合记忆跟踪:

> (9.1) R=Ra*Rb
>
> where:
>
> - R - [retrievability](https://supermemo.guru/wiki/Retrievability) of a binary composite memory trace
> - Ra and Rb - [retrievability](https://supermemo.guru/wiki/Retrievability) of two independent memory trace subcomponents (subtraces): a and b
>
> (9.2) R=exp-kt/Sa*exp-kt/Sb=exp-kt/S
>
> where:
>
> - t - time
> - k - ln(10/9)
> - S - [stability](https://supermemo.guru/wiki/Stability) of the composite memory trace
> - Sa and Sb - stabilities of memory subtraces a and b
>
> (9.3) -kt/S=-kt/Sa-kt/Sb=-kt(1/Sa+1/Sb)
>
> (9.4) S=Sa*Sb/(Sa+Sb)
>
>
>
> (9.1) R=Ra*Rb
>
> 上式中：
>
> - R - [retrievability](https://supermemo.guru/wiki/Retrievability)的复合记忆跟踪
> - Ra和Rb -[可检索性](https://supermemo.guru/wiki/Retrievability)两个独立的内存跟踪子组件(子跟踪):a和b
>
> (9.2) R=exp-kt/Sa*exp-kt/Sb=exp-kt/S
>
> 上式中：
>
> - t -时间
> - k - ln(10/9)
>
> - [稳定](https://supermemo.guru/wiki/Stability)合成记忆痕迹
>
> - a和b存储单元的Sa和Sb稳定性
>
> (9.3) -kt/S=-kt/Sa-kt/Sb=-kt(1/Sa+1/Sb)
>
> (9.4) S=Sa*Sb/(Sa+Sb)

We used the Eqn. (9.4) in further analysis of composite memory traces. We expected, that if initially, the [stability](https://supermemo.guru/wiki/Stability) of memory subtraces Sa and Sb differed substantially, subsequent [repetitions](https://supermemo.guru/wiki/Repetition), optimized for maximizing S (i.e. with the criterion R=0.9) might weaken the [stability](https://supermemo.guru/wiki/Stability) of subcomponents due to sub-optimal timing of review. We showed this not to be the case. Substabilities tend to converge in the learning process!

我们用的是Eqn。(9.4)进一步分析复合记忆痕迹。我们预期,如果最初的内存[稳定](https://supermemo.guru/wiki/Stability) subtraces Sa和某人大大不同,随后[重复](https://supermemo.guru/wiki/Repetition),优化了最大化年代与标准(即R = 0.9)可能会削弱[稳定](https://supermemo.guru/wiki/Stability)的子组件由于最优时间复习。我们证明了事实并非如此。在学习的过程中，事物往往会趋于一致!

[![Value of keeping memories simple](https://supermemo.guru/images/thumb/5/5a/Memory_stability_for_complex_memories_and_memory_subtraces.png/400px-Memory_stability_for_complex_memories_and_memory_subtraces.png)](https://supermemo.guru/wiki/File:Memory_stability_for_complex_memories_and_memory_subtraces.png)

> ***Figure:** Keeping memories simple in learning is essential (see: Minimum information principle). Complex models of knowledge can be represented by simple memories. Simplicity improves memory retention in the long run. The impact of simplicity on the stability of memory is an important contribution of two component model of memory to proving the need for the existence of grandmother cells. Human intelligence depends on a system of concept maps, which in turn owe their stability to the simplicity of individual memories*
>
> ***图:**学习时保持记忆简单是很重要的(参见:最小信息原则)。简单的记忆可以代表复杂的知识模型。从长远来看，简单性可以提高记忆力。简单性对记忆稳定性的影响是双组分记忆模型对证明祖母细胞存在必要性的重要贡献。人类的智能依赖于一个概念地图系统，而这个系统的稳定性又归功于个人记忆的简单性*

[Stability](https://supermemo.guru/wiki/Stability) of [complex](https://supermemo.guru/wiki/Complexity) memories can be derived from substabilities of [atomic memories](https://supermemo.guru/wiki/Atomic_memory)

The fact that memory traces for complex memories contribute to the difficulty in retaining knowledge in the long-term is a hint that the neocortex cannot possibly use connectionist approach to storing memories. This is an important new argument for the existence of neurons called [grandmother cells](https://supermemo.guru/wiki/Grandmother_cell) (for more see: [The truth about grandmother cells](https://supermemo.guru/wiki/The_truth_about_grandmother_cells)).

[稳定](https://supermemo.guru/wiki/Stability)的[复杂](https://supermemo.guru/wiki/Complexity)的记忆可以从[原子记忆的本质](https://supermemo.guru/wiki/Atomic_memory)

复杂记忆的记忆痕迹导致长期记忆的困难，这一事实暗示了大脑皮层不可能使用连接主义方法来存储记忆。这是关于神经元存在的一个重要的新论点，叫做[祖母细胞](https://supermemo.guru/wiki/Grandmother_cell)(更多信息请参见:[祖母细胞的真相](https://supermemo.guru/wiki/The_truth_about_grandmother_cells))。

### Convergence of sub-stabilities for composite memory traces

### 复合记忆痕迹子稳定性的收敛性

It was easy to simulate the behavior of complex memories in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition). Their substabilities tend to converge. This leads to inefficient review and a slow buildup of stability. Today we can show that at a certain level of complexity, it is no longer possible to build memory stability for long-term [retention](https://supermemo.guru/wiki/Retention). In short, there is no way to remember a book other than just re-reading it endlessly. This is a futile process.

在[间隔重复]中很容易模拟复杂记忆的行为(https://supermemo.guru/wiki/Spaced_repetition)。它们的相对性趋于一致。这导致了低效的审查和缓慢的稳定性积累。今天，我们可以证明，在一定程度的复杂性下，建立长期的内存稳定性是不可能的(https://supermemo.guru/wiki/Retention)。简而言之，要记住一本书，只能不断地重读。这是一个徒劳的过程。

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

If we generate a double-cloze, we are not really sure if a single repetition generates a uniform activation of both memory circuits responsible for storing the two distinct pieces of knowledge. Let us assume that the first repetition is the only differentiating factor for the two memory traces, and that the rest of the learning process proceeds along the formulas presented above.

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

如果我们生成一个双完形填空，我们就不能确定一次重复是否会导致两个负责存储不同知识的记忆回路的统一激活。让我们假设第一次重复是两种记忆痕迹的唯一区别因素，而学习过程的其余部分是按照上面的公式进行的。

To investigate the behavior of stability of memory subtraces under a rehearsal pattern optimized for composite stability with the criterion R=0.9, let us take the following:

- Sa=1
- Sb=30
- S=Sa*Sb/(Sa+Sb) (from Eqn. 9.4)
- *SInc*=*a*S*-b**e*c*R+*d* (from Eqn. [SInc2005](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#SInc2005))
- composite memory trace is consolidated through rehearsal with R=0.9 so that both subtraces are equally well re-consolidated (i.e. the review of the composite trace is to result in no neglect of subtraces)

为了研究在R=0.9准则下，优化组合稳定性的预演模式下，记忆子痕迹的稳定性行为，我们取:

- Sa) = 1

- 某人= 30

- S=Sa*Sb/(Sa+Sb)(出自Eqn. 9.4)

- *SInc*=*a*S*-b* e*c*R+*d*(来自Eqn)[SInc2005](https://supermemo.guru/wiki/History_of_spaced_repetition_(印刷)# SInc2005))

- 通过使用R=0.9来合并复合内存跟踪，以便对两个子跟踪进行同样好的重新合并(即，对复合跟踪的检查不会导致对子跟踪的忽略)

As can be seen in the following figure, memory stability for the composite trace will always be less than the stability for individual subtraces; however, the stabilities of subtraces converge.

从下图可以看出，复合跟踪的内存稳定性总是小于单个子跟踪的内存稳定性;然而，子轨迹的稳定性收敛。

[![Convergence of stability for memory sub-traces rehearsed with the same review pattern optimized for the entire composite memory trace (i.e. review occurs when the composite retrievability reaches 0.9)](https://supermemo.guru/images/a/a0/Stabil4.gif)](https://supermemo.guru/wiki/File:Stabil4.gif)

> ***Figure:** Convergence of stability for memory sub-traces rehearsed with the same review pattern optimized for the entire composite memory trace (i.e. review occurs when the composite retrievability reaches 0.9). The horizontal axis represents the number of reviews, while the vertical axis shows the logarithm of stability. Blue and red lines correspond with the stability of two sub-traces which substantially differed in stability after the original learning. The black line corresponds with the composite stability (S=Sa\*Sb/(Sa+Sb)). The disparity between Sa and Sb self-corrects if each review results in a uniform activation of the underlying synaptic structure.*
>
> ***图:**使用为整个复合内存跟踪优化的相同审查模式排练的内存子跟踪的稳定性收敛性(即当复合可检索性达到0.9时进行审查)。横轴表示评论的数量，纵轴表示稳定性的对数。蓝线和红线对应两个子轨迹的稳定性，这两个子轨迹在原始学习后的稳定性上有很大的不同。黑线对应的是复合稳定性(S=Sa\*Sb/(Sa+Sb))。如果每次检查都导致了底层突触结构的一致激活，那么Sa和Sb之间的差异就会自我纠正

### Composite stability increase

### 复合稳定性增加

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

Let us now figure out how much  aand S? If we assume the identical stimulation of memory subtraces, and denote SInc bas*i*

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

现在我们算出多少a和S?如果我们假设记忆的刺激是相同的，则表示SInc是bas*i*

> SInca=SIncb=*i*
>
> Sa[r]=Sa[r-1]**i*
> Sb[r]=Sb[r-1]**i*
>
> S[r]=Sa[r]*Sb[r]/(Sa[r]+Sb[r])=
> =Sa[r-1]*Sb[r-1]**i*2/(Sa[r-1]**i*+Sb[r-1]**i*)=
> =*i**(Sa[r-1]*Sb[r-1])/(Sa[r-1]+Sb[r-1)=*i**S[r-1]

In other words:

换言之：

> (11.1) SInc=*i*=SInca=SIncb

The above demonstrates that with the presented model, the increase in memory stability is independent of the complexity of knowledge assuming equal re-consolidation of memory subtraces

**Composite stability increase is the same as the increase in stability of sub-traces**

上述结果表明，在假设记忆子轨迹重新整合的情况下，记忆稳定性的提高与知识的复杂性无关

**复合稳定性的增加与子轨迹稳定性的增加相同**