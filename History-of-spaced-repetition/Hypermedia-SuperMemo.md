# 1995: Hypermedia SuperMemo

# 1995：超级媒体SuperMemo 

[TOC=2,5]

## Birth of Algorithm SM-8 in a mountain hut

## 算法SM-8诞生于山间小屋

In 1995, [SuperMemo](https://supermemo.guru/wiki/SuperMemo) was rewritten from grounds up and it was a great opportunity to implement a new [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) algorithm based on the data collected in 4 years of the use of [Algorithm SM-6](https://supermemo.guru/wiki/Algorithm_SM-6).

In March 1995, at CeBIT in Hannover, we saw a new fantastic development environment from Borland: Delphi. It has lifted the old Borland Pascal to a new level, and opened dozens of development opportunities for [SuperMemo](https://supermemo.guru/wiki/SuperMemo). We decided to redesign the program along the lines depicted in my [PhD dissertation](https://supermemo.guru/wiki/Economics_of_learning). In addition to [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition), we wanted to have knowledge structure and hypermedia. Instead of a mass of [items](https://supermemo.guru/wiki/Item), the users would be able to build a [knowledge tree](https://supermemo.guru/wiki/Knowledge_tree). Instead of the old template made of a question, answer, picture, and sound, we wanted to have all possible component types that could be mixed up into new hypermedia forms for expressing knowledge. There was also a dream of programmable SuperMemo in which developers could write their own procedures for any form of training, incl. procedural training, touch typing, or solving quadratic equations. At the same time, we have collected a lot of data that indicated that the algorithm used in [SuperMemo](https://supermemo.guru/wiki/SuperMemo) could be improved. For example, the mathematical nature of the [matrix of optimal factors](https://supermemo.guru/wiki/OF_matrix) has become pretty obvious.

1995年,[SuperMemo](https://supermemo.guru/wiki/SuperMemo)被重写的理由,这是一个很好的机会来实现一种新的[记忆](https://supermemo.guru/wiki/Spaced_repetition)算法的基础上,在4年的使用收集的数据[算法SM-6)](https://supermemo.guru/wiki/Algorithm_SM-6)。

1995年3月，在汉诺威的CeBIT上，我们看到了来自Borland的一个全新的开发环境:Delphi。它将原来的Borland Pascal提升到了一个新的水平，并为[SuperMemo](https://supermemo.guru/wiki/SuperMemo)打开了几十个开发机会。我们决定按照我的[博士论文](https://supermemo.guru/wiki/Economics_of_learning)中描述的路线重新设计程序。除了[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)，我们想要有知识结构和超媒体。用户将能够构建一个[知识树](https://supermemo.guru/wiki/Item)，而不是大量的[项目](https://supermemo.guru/wiki/Knowledge_tree)。我们不希望使用由问题、答案、图片和声音组成的旧模板，而是希望将所有可能的组件类型混合到新的超媒体表单中，以表达知识。还有一个可编程的SuperMemo的梦想，开发人员可以为任何形式的培训编写自己的程序，包括程序性培训、触摸打字或解二次方程。与此同时，我们收集了大量的数据表明，在[SuperMemo](https://supermemo.guru/wiki/SuperMemo)中使用的算法可以得到改进。例如，最优因子矩阵(https://supermemo.guru/wiki/OF_matrix)的数学性质已经变得相当明显。

In May 1995, I took my Pentium PC to a remote mountain hut in southern Poland to work on those ideas. That was a period of 100 days of total isolation interrupted only by a short visit from [Krzysztof Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak) during which we re-synchronized our vision for future [SuperMemo](https://supermemo.guru/wiki/SuperMemo). By September 1995, the new algorithm was ready, and I tested it on my own data. Back in Poznan, I started gradually moving all my learning process from multiple [collections](https://supermemo.guru/wiki/Collection) in [SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7) to the new environment nicknamed *"Genius"*. Genius became [SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8) only two years later when the new program could finally include all functionality that was originally available in SuperMemo 7.

The most important data that helped develop Algorithm SM-8 were [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) and [OF matrix](https://supermemo.guru/wiki/OF_matrix) data collected with [SuperMemo 6](https://supermemo.guru/wiki/SuperMemo_6) and [SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7). This data took away a great deal of guesswork from the algorithm. The work was pretty easy in comparison to [Algorithm SM-17 (2014-2016)](https://supermemo.guru/wiki/Algorithm_SM-17) when I had mountains of repetition histories to process, and the requirements for precision and [good metrics](https://supermemo.guru/wiki/Universal_metric) have tripled. While Algorithm SM-17 took two years to develop, Algorithm SM-8 was designed, implemented, and well-tested in mere 100 days.

1995年5月，我带着我的奔腾(Pentium)电脑到波兰南部一个偏远的山间小屋去研究这些想法。那是一段完全隔离的100天，只有来自[Krzysztof Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)的短暂访问打断了我们，在此期间，我们重新同步了未来的愿景[SuperMemo](https://supermemo.guru/wiki/SuperMemo)。到1995年9月，新算法已经准备就绪，我用自己的数据对它进行了测试。回到波兹南后，我开始逐步将我的学习过程从[SuperMemo 7]中的多个[collection](https://supermemo.guru/wiki/Collection)转移到昵称为“Genius”的新环境中。天才变成了[SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8)只有两年后，当新的程序终于可以包括所有的功能，原来在SuperMemo 7。

帮助开发算法sm8的最重要的数据是[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)和[矩阵](https://supermemo.guru/wiki/OF_matrix)用[SuperMemo 6](https://supermemo.guru/wiki/SuperMemo_6)和[SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7)收集的数据。这些数据消除了对算法的大量猜测。与[Algorithm SM-17 (2014-2016)](https://supermemo.guru/wiki/Algorithm_SM-17)相比，这项工作非常简单，因为我有大量的重复历史记录要处理，而对精度和[好的度量](https://supermemo.guru/wiki/Universal_metric)的要求增加了两倍。算法SM-17的开发耗时两年，而算法SM-8的设计、实现和测试仅用了100天。

The main ideas behind Algorithm SM-8:

- precise mathematical determination of the [OF matrix](https://supermemo.guru/wiki/OF_matrix) based on live approximations. Instead of matrix smoothing known from [SuperMemo 5](https://supermemo.guru/wiki/SuperMemo_5), I wanted to know the exact mathematical function that could describe the matrix, and perform live updates. It was easy to determine that a negative power function would determine [OF](https://supermemo.guru/wiki/O-Factor)=f(RepNo) (which is an expression of [SInc](https://supermemo.guru/wiki/Stability_increase)=f(S)) in today's terms). A bit more guesswork went into the impact of [difficulty](https://supermemo.guru/wiki/Difficulty) on [SInc](https://supermemo.guru/wiki/Stability_increase). I opted for a linear approximation of the function mapping difficulty ([A-Factor](https://supermemo.guru/wiki/A-Factor)) to the decay constant for SInc (D-Factor), which expressed the decline in [stability increase](https://supermemo.guru/wiki/Stability_increase) with stability/interval. That linear bet has survived to this day. It was a good guess.
- with a good definition of the OF matrix, I could provide a precise definition of item [difficulty](https://supermemo.guru/wiki/Difficulty): instead of a fluid [E-Factor](https://supermemo.guru/wiki/E-Factor) that could be manually controlled by [grades](https://supermemo.guru/wiki/Grade) at the whim of the user, I wanted to have an absolute difficulty [A-factor](https://supermemo.guru/wiki/A-factor), which was defined as the [stability increase](https://supermemo.guru/wiki/Stability_increase) after the first [repetition](https://supermemo.guru/wiki/Repetition) timed for [R](https://supermemo.guru/wiki/Retrievability)=0.9. This made it possible for [SuperMemo](https://supermemo.guru/wiki/SuperMemo) to adjust item difficulty with each repetition by correcting the fit of item's performance with the expected performance based on the [OF matrix](https://supermemo.guru/wiki/OF_matrix)
- faster determination of startup [difficulty](https://supermemo.guru/wiki/Difficulty) by correlating the first [grade](https://supermemo.guru/wiki/Grade) with the [A-factor](https://supermemo.guru/wiki/A-factor). This is a weak mechanism of little significance, as shown by the fact that even with multi-repetition histories, item difficulty is still a hazy concept. In that context, users should be reminded that the best approach is to formulate items well, and just keep them easy
- approximating the first post-[lapse](https://supermemo.guru/wiki/Lapse) interval by an exponential fit based on the number of memory lapses. The biggest value of that approach was to abolish a myth that reducing the length of intervals in case of a memory lapse could speed up learning. Some authors of software based on [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) opted for such a solution, which has been proven wrong. This erroneous approach is also known in variants of the [Leitner system](https://supermemo.guru/wiki/Leitner_system), which has been used, among others, in [Duolingo](https://supermemo.guru/wiki/Duolingo)
- the idea to correlate [grades](https://supermemo.guru/wiki/Grade) with the [forgetting index](https://supermemo.guru/wiki/Forgetting_index) was a failure and did not contribute to improving the algorithm. That truth transpired slowly. It took nearly a decade to come to the ultimate verdict: grades correlate poorly with the forgetting index. The intuition born with [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) is only weakly correct

算法SM-8背后的主要思想:

- 精确的数学确定[的矩阵](https://supermemo.guru/wiki/OF_matrix)基于现场近似。我想知道能够描述矩阵的精确数学函数，并执行实时更新，而不是从[SuperMemo 5](https://supermemo.guru/wiki/SuperMemo_5)中了解矩阵平滑。很容易确定一个负幂函数将决定(https://supermemo.guru/wiki/O-Factor)=f(RepNo)(这是一个表达式的[SInc](https://supermemo.guru/wiki/Stability_increase)=f(S)在今天的条件)。关于[难度](https://supermemo.guru/wiki/Difficulty)对[SInc](https://supermemo.guru/wiki/Stability_increase)的影响，还有一些猜测。我选择将函数映射困难([a - factor](https://supermemo.guru/wiki/A-Factor))与SInc (D-Factor)的衰减常数进行线性近似，D-Factor表示随着稳定性/时间间隔的增加(https://supermemo.guru/wiki/Stability_increase)的下降。这种线性押注一直延续至今。这是一个很好的猜测。

- 有了矩阵的良好定义，我可以提供一个精确的项目[难度]定义(https://supermemo.guru/wiki/Difficulty):代替液体(E-Factor) (https://supermemo.guru/wiki/E-Factor),可以手动控制(成绩)(https://supermemo.guru/wiki/Grade)在用户的心血来潮,我想有一个绝对的困难(因素)(https://supermemo.guru/wiki/A-factor),它被定义为[稳定增加](https://supermemo.guru/wiki/Stability_increase)在第一次[重复](https://supermemo.guru/wiki/Repetition)的[R](https://supermemo.guru/wiki/Retrievability) = 0.9。这使得[SuperMemo](https://supermemo.guru/wiki/SuperMemo)可以根据[of matrix](https://supermemo.guru/wiki/OF_matrix)

- 通过将第一个等级(https://supermemo.guru/wiki/Grade)与第一个等级(https://supermemo.guru/wiki/Grade)与第一个等级(https://supermemo.guru/wiki/A-factor)相关联，更快地确定启动[难度](https://supermemo.guru/wiki/A-factor)。这是一种意义不大的弱机制，即使有多次重复的历史，项目难度仍然是一个模糊的概念。在这种情况下，应该提醒用户，最好的方法是很好地规划项目，并让它们保持简单

- 近似的第一个后[流逝](https://supermemo.guru/wiki/失效)间隔指数拟合的基础上的记忆失误的数量。这种方法最大的价值在于打破了一个神话，即在记忆缺失的情况下缩短间隔时间可以加速学习。一些基于[Algorithm SM-2]的软件作者(https://supermemo.guru/wiki/Algorithm_SM-2)选择了这种解决方案，但事实证明这种方法是错误的。这种错误的方法在[Leitner system](https://supermemo.guru/wiki/Leitner_system)的变体中也很常见，在[Duolingo](https://supermemo.guru/wiki/Duolingo)中也使用了这种方法。

- 将[等级](https://supermemo.guru/wiki/Grade)与[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)联系起来的想法是失败的，对改进算法没有帮助。真相慢慢浮出水面。最终的结论花了将近10年的时间:分数与遗忘指数的相关性很差。天生的直觉[算法SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)仅仅是微弱正确的

Interestingly, Algorithm SM-8 did not require full repetition history for elements. Full repetition histories were to be implemented only in February 1996. The advantage was an easier implementation. The disadvantage came with the fact that once the user intervened manually in the learning process, the algorithm had no record of that intervention, and could not defend itself from a possible inflow of incorrect data. Naturally, only full repetition history record made it possible to implement [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) two decades later.

有趣的是，算法SM-8并不要求元素具有完整的重复历史。完整的重复记录只能在1996年2月执行。其优点是更容易实现。缺点是，一旦用户在学习过程中手动干预，算法就没有干预记录，并且无法保护自己免受可能的错误数据流入。当然，只有完整的重复历史记录才有可能在20年后实现[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)。

My first "live" repetition in Algorithm SM-8 on my own data took place on Aug 16, 1995, Wed. For the test, I "sacrificed" a small 100 item collection with mnemonic peg list for memorizing numbers. Over the next two years, I gradually converted all my other collections to work with the new algorithm and in the new SuperMemo environment. In 1997, all my knowledge have finally been integrated into a single well-structured database. In 1995-1997, we called such a database a "knowledge system". Today we just call it a [collection](https://supermemo.guru/wiki/Collection) (as in a collection of pieces of knowledge).

To this day, the core of the algorithm born in 1995 runs in [SuperMemo 17](https://supermemo.guru/wiki/SuperMemo_17) in the background, and the user can still choose intervals based on that old algorithm in case he is unhappy with propositions of [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17).

我在算法SM-8中对我自己的数据的第一次“现场”重复发生在1995年8月16日(周三)。在接下来的两年里，我逐渐地将我所有的其他集合转换为使用新的算法和新的SuperMemo环境。1997年，我所有的知识终于集成到一个结构良好的数据库中。在1995-1997年，我们称这样的数据库为“知识系统”。今天我们称它为[集合](https://supermemo.guru/wiki/Collection)(就像知识的集合一样)。

直到今天,出生于1995年的核心算法运行在[SuperMemo 17](https://supermemo.guru/wiki/SuperMemo_17)的背景,和用户仍然可以选择间隔基于旧算法,以防他不满命题[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)。

## Absolute item difficulty

## 绝对项困难

In SuperMemo 1.0 through SuperMemo 3.0, [E-Factors](https://supermemo.guru/wiki/E-Factor) were defined in the same way as [O-Factors](https://supermemo.guru/wiki/O-Factor) (i.e. the ratio of successive intervals). They were an approximate measure of item [difficulty](https://supermemo.guru/wiki/Difficulty) (the higher the E-Factor, the easier the item). However, the [spaced repetition optimization](https://supermemo.guru/wiki/Algorithm_SM-2) would force E-factors to correspond with [stability increase](https://supermemo.guru/wiki/Stability_increase) which drops with [stability](https://supermemo.guru/wiki/Stability). In other words, by definition, in [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2), [items](https://supermemo.guru/wiki/Item) would be tagged as more and more "difficult" as they were subject to successive repetitions. This is a bit counter-intuitive and users never seemed to notice.

在SuperMemo 1.0到SuperMemo 3.0中，[E-Factors](https://supermemo.guru/wiki/E-Factor)的定义与[O-Factors](https://supermemo.guru/wiki/O-Factor)(即连续区间的比值)的定义相同。它们是项目[难度](https://supermemo.guru/wiki/Difficulty)的近似度量(E-Factor越高，项目越容易)。然而，[间隔重复优化](https://supermemo.guru/wiki/Algorithm_SM-2)将迫使电子因素与[稳定性增加](https://supermemo.guru/wiki/Stability_increase)相对应，而[稳定性](https://supermemo.guru/wiki/m_sm -2)将使电子因素与[稳定性](https://supermemo.guru/wiki/Stability)相对应。换句话说，根据定义，在[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)中，[items](https://supermemo.guru/wiki/Item)将被标记为越来越“难”，因为它们需要进行连续的重复。这有点违反直觉，用户似乎从未注意到。

Starting with SuperMemo 4.0, E-Factors were used to index the matrix of O-Factors. They were still used to reflect item difficulty. They were still used to compute O-Factors. However, they could differ from O-Factors and thus make for a better reflection of difficulty.

从SuperMemo 4.0开始，E-Factors被用来索引O-Factors的矩阵。它们仍然用来反映项目难度。它们仍然被用来计算o因子。然而，它们可能与o因子不同，因此有助于更好地反映难度。

In SuperMemo 4 through SuperMemo 7, difficulty of material in a given database would shape the relationship between O-Factors and E-Factors. For example, in an easy collection, the starting-point O-Factor (i.e. the one corresponding with the first repetition and the assumed starting [difficulty](https://supermemo.guru/wiki/Difficulty)) would be relatively high. As performance in repetitions determines E-Factors, items of the same difficulty in an easy collection would naturally have a lower E-Factor than the exactly same items in a difficult collection. This all changed in [SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8) where [A-Factors](https://supermemo.guru/wiki/A-Factor) where introduced. A-Factors are "bound" to the second row of the O-Factor matrix. This makes them an absolute measure of item difficulty. Their value **does not depend on the content of the collection**. For example, you know that if A-Factor is 1.5, the third repetition will take place in an interval that is 50% longer than the first interval.

在SuperMemo 4到SuperMemo 7中，给定数据库中材料的难度会影响o因素和e因素之间的关系。例如，在一个简单的集合中，起始点O-Factor(即与第一次重复相对应的O-Factor和假定的起始[难度](https://supermemo.guru/wiki/难度)会相对较高。由于重复的性能决定了e因子，所以在容易收集的相同难度的项目中，e因子的值自然会比在困难收集的相同项目中低。这一切都改变了在[SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8)那里[A-Factors](https://supermemo.guru/wiki/A-Factor)介绍。a因子“绑定”到o因子矩阵的第二行。这使得它们成为项目难度的绝对度量。它们的值**不依赖于集合**的内容。例如，你知道如果a因素是1.5，那么第三次重复的间隔时间比第一次间隔时间长50%。

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

[A-Factor](https://supermemo.guru/wiki/A-Factor) is a number associated with every [element](https://supermemo.guru/wiki/Element) in a [collection](https://supermemo.guru/wiki/Collection). A-Factor determines how much [intervals](https://supermemo.guru/wiki/Interval) increase in the learning process. The higher the A-Factor, the faster the intervals increase. A-Factors reflect item [difficulty](https://supermemo.guru/wiki/Difficulty). The higher the A-Factor the easier the [item](https://supermemo.guru/wiki/Item). The most difficult items have A-Factors equal to 1.2. A-Factor is defined as the quotient of the second [optimum interval](https://supermemo.guru/wiki/Optimum_interval) and the first optimum interval used in repetitions

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

[a - factor](https://supermemo.guru/wiki/A-Factor)是一个与[collection](https://supermemo.guru/wiki/Collection)中的每个[element](https://supermemo.guru/wiki/Element)相关联的数字。a因素决定了学习过程中[interval](https://supermemo.guru/wiki/Interval)增加了多少。a因子越高，间隔增加越快。a -因素反映项目[难度](https://supermemo.guru/wiki/难度)。a因素越高，[项目]越容易(https://supermemo.guru/wiki/Item)。最难的题的a因子等于1。2。a因子定义为第二个[最佳间隔](https://supermemo.guru/wiki/Optimum_interval)和第一个用于重复的最佳间隔的商

## Post-lapse interval

## Post-lapse间隔

Post-lapse interval approximation in Algorithm SM-8 abolished two myths:

- shortening intervals after a lapse is a good idea (this idea was advocated multiple times in the years 1991-2000)
- the first interval should always be 1 day (as in some older SuperMemo solutions)

SM-8算法中的延时间隔近似值消除了两个误区:

- 缩短间隔时间是一个好主意(这个主意在1991-2000年被多次提倡)

- 第一个间隔应该总是1天(在一些老的SuperMemo解决方案中)

In the graph presented below, we can see that with successive lapses, the optimum post-lapse interval keeps getting slightly shorter. This expresses nothing else but the fact that those high-lapse counts are reached only by badly formulated items, or items that are really hard to remember for their semantic nature or knowledge interference. For memories starting with Lapse=10, I suggested a term "[toxic](https://supermemo.guru/wiki/Toxic_memory)" to express their impact on the learning process. If the brain rejected a piece of information that many times, we should get a message: this knowledge is badly formulated or has become toxic for other reasons (e.g. stress associated with learning, e.g at school).

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

在下面的图表中，我们可以看到，随着连续的失误，最佳的后脱出间隔时间变得越来越短。这只说明了一个事实，即那些高偏差计数只有通过表述糟糕的项目，或那些由于语义性质或知识干扰而很难记住的项目才能达到。对于记忆，从记忆失效=10开始，我提出了一个术语“[toxic](https://supermemo.guru/wiki/Toxic_memory)”来表达它们对学习过程的影响。如果大脑多次拒绝一条信息，我们就会得到这样的信息:这条信息表达得很糟糕，或者由于其他原因(例如，与学习相关的压力，如压力、压力、压力)而变得有害。g在学校)。

档案警告:[为何使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**First interval**   

**第一间隔**

[![SuperMemo: Tools : Statistics : Analysis : Graphs : First Interval shows you exponential regression curve that approximates the length of the first interval for different numbers of memory lapses](https://supermemo.guru/images/thumb/c/c7/First_interval.jpg/800px-First_interval.jpg)](https://supermemo.guru/wiki/File:First_interval.jpg)

> ***Figure**: In the graph above, which includes data from over 130,000 repetitions, newly memorized items are optimally repeated after seven days. However, the items that have been forgotten 10 times (which is rare in SuperMemo) will require an interval of two days. (Due to logarithmic scaling, the size of the circle is not linearly proportional to the data sample; the number of repetition cases for Lapses=0 is by far larger than for Lapses=10, as can be seen in **Distributions : Lapses**)*
>
> ***图片：**在上面的图表中，包含了13万多次重复的数据，新记忆的项目最好在七天之后重复。然而，忘记10次的项目(在SuperMemo中很少见)需要两天的间隔时间。(由于对数缩放，圆的大小与数据样本不成线性比例;失误=0的重复次数远远大于失误=10的重复次数，可以在**分布中看到:失误**)*

## First grade vs. A-Factor

## 一年级vs. A-因素

Correlating the first grade with the estimated item difficulty was to help classify items by difficulty at the entry to the learning process. The correlation appears to be weak and is highly dependent on user's grading system. For some users, there is virtually no correlation (picture #1). For others, the correlation is good enough to cover the full range of difficulty (A-factor) (picture #2).

将一年级与估计的项目难度联系起来，是为了帮助在进入学习过程时根据难度对项目进行分类。相关性似乎很弱，并且高度依赖于用户的评分系统。对于一些用户，几乎没有相关性(图1)。对其他人来说，这种相关性足以覆盖所有难度(a因素)(图2)。

[![SuperMemo: Tools : Analysis : Graphs : First Grade vs. A-Factor correlates the first grade obtained by an item with the ultimate estimation of its A-Factor value](https://supermemo.guru/images/thumb/2/2a/First_Grade_vs_A-Factor_All.jpg/800px-First_Grade_vs_A-Factor_All.jpg)](https://supermemo.guru/wiki/File:First_Grade_vs_A-Factor_All.jpg)

[![SuperMemo: Tools : Analysis : Graphs : First Grade vs. A-Factor correlates the first grade obtained by an item with the ultimate estimation of its A-Factor value](https://supermemo.guru/images/thumb/9/96/First_Grade_vs_A-Factor_Molie.jpg/800px-First_Grade_vs_A-Factor_Molie.jpg)](https://supermemo.guru/wiki/File:First_Grade_vs_A-Factor_Molie.jpg)

In addition, in Algorithm SM-11 derived from Algorithm SM-8, the user was allowed to execute premature repetitions. Those repetitions would account for the [spacing effect](https://supermemo.guru/wiki/Spacing_effect), however, they would still contribute to the graph and overestimate the grade for difficult items. With extensive use of [incremental reading](https://supermemo.guru/wiki/Incremental_reading), this would flatten the graph.

[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) does not use grade-difficulty correlation and derives difficulty from the entire repetition history. Practice shows that even then the estimate is hard to make and the good practice of learning is to keep all items easy (i.e. in the accepted mnemonic fit with the rest of the student's knowledge).

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

此外，在由算法SM-8衍生而来的算法SM-11中，允许用户进行过早的重复。这些重复可以解释[间隔效应](https://supermemo.guru/wiki/Spacing_effect)，然而，它们仍然会对图有贡献，并且会高估困难项目的分数。随着[增量阅读](https://supermemo.guru/wiki/Incremental_reading)的广泛使用，这将使图表变得扁平。

[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)不使用等级-难度相关，而是从整个重复历史中获取难度。实践表明，即使这样，也很难做出估计，而良好的学习实践是让所有的项目都很容易(即在可接受的记忆范围内符合学生的其他知识)。

档案警告:[为何使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**First Grade vs. A-Factor** - G-AF graph correlates the first grade obtained by an item with the ultimate estimation of its A-Factor value. At each repetition, the current element's old A-Factor estimation is removed from the graph and the new estimation is added. This graph is used by [Algorithm SM-15](https://supermemo.guru/wiki/Algorithm_SM-15) to quickly estimate the first value of A-Factor at the moment when all we know about an element is the first grade it has scored in its first repetition.

**一年级vs. A-因素**  G-AF图将项目获得的一级与a因素值的最终估计相关联。在每次重复时，将当前元素的旧a因素估计从图中删除，并添加新的估计。这个图被[Algorithm SM-15](https://supermemo.guru/wiki/Algorithm_SM-15)用来快速估计一个因素的第一个值，当我们只知道一个元素在第一次重复中得到的分数时。

## Grade vs. Forgetting Index

## 等级与遗忘指数

By correlating grades with the expected forgetting index (predicted [retrievability](https://supermemo.guru/wiki/Retrievability)), I hoped to be able to compute the estimated forgetting index (post-repetition estimate of the actual [retrievability](https://supermemo.guru/wiki/Retrievability)). This correlation appeared to be weak due to the fact that all users tend to deploy their own grading systems, which is often inconsistent. The grade and R correlation comes primarily from the fact that complex items get worse grades and tend to be forgotten faster (at least at the beginning). In that sense, grades provide a better reflection of [complexity](https://supermemo.guru/wiki/Complexity) than a reflection of [retrievability](https://supermemo.guru/wiki/Retrievability).

In the picture below, the entire range of the expected forgetting index seems to fall around the grade 3.

通过将成绩与预期遗忘指数(predicted [retrievability](https://supermemo.guru/wiki/Retrievability)相关联，我希望能够计算出估计遗忘指数(post-repetition estimate of the actual [retrievability](https://supermemo.guru/wiki/Retrievability))。这种相关性似乎很弱，因为所有用户都倾向于部署自己的评分系统，而这往往是不一致的。分数和R之间的相关性主要来自于这样一个事实:复杂的项目分数越低，越容易被遗忘(至少在开始的时候)。从这个意义上说，分数反映了[复杂性](https://supermemo.guru/wiki/Complexity)，而反映了[可检索性](https://supermemo.guru/wiki/Retrievability)。

在下面的图片中，预期遗忘指数的整个范围似乎在3级左右。

[![SuperMemo: Tools : Statistics : Analysis : Graphs : Grade vs. Forgetting Index graph](https://supermemo.guru/images/thumb/6/6d/Grade_vs_Forgetting_Index.jpg/800px-Grade_vs_Forgetting_Index.jpg)](https://supermemo.guru/wiki/File:Grade_vs_Forgetting_Index.jpg)

For Grade<=3 we can read the maximum estimated forgetting index, and for Grade>=4 we can read the minimum estimated forgetting index. In that light, two grade systems would have the exact same effect on the algorithm as the six grade system.

For other users, the curve might even peak at some levels of the expected forgetting index as if grading reflected a wish to remember items that are really hard to remember (lenient grading).

[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) makes an extensive use of retrievability estimated after the repetition, however, it derives it from sheer recall data and the expected retrievability. Grade-retrievability correlations are also collected, however, their weight is negligible.

对于等级<=3，我们可以读取最大估计遗忘指数;对于等级>=4，我们可以读取最小估计遗忘指数。在这种情况下，两级系统对算法的影响与六级系统完全相同。

对于其他用户，曲线甚至可能在预期遗忘指数的某些水平达到峰值，就好像评分反映了他们想要记住那些很难记住的东西的愿望(评分宽松)。

[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)大量使用了重复后估计的可检索性，但是，它是从纯粹的召回数据和预期的可检索性中获得的。也收集了等级可检索相关性，但是它们的权重可以忽略不计。

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**Grade vs. Forgetting Index**          , you would arrive at the FI-G graph. This graph is used to compute an[estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)that is, in turn, used to normalize grades (for delayed or advanced repetitions) and estimate the new value of item's A-Factor. The grade is computed using the formula:*Grade=expA\*FI+B*

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**分数与遗忘指数**，得到FI-G图。此图用于计算[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)，该索引反过来用于标准化分数(对于延迟或高级重复)并估计项目的A-Factor的新值。使用公式计算等级:* grade =expA\*FI+B*

The FI-G graph is updated after each repetition by using the expected forgetting index and actual grade scores. The expected forgetting index can easily be derived from the interval used between repetitions and the optimum interval computed from the OF matrix. The higher the value of the expected forgetting index, the lower the grade. From the grade and the FI-G graph, we can compute the estimated forgetting index which corresponds to the post-repetition estimation of the forgetting probability of the just-repeated item at the hypothetical pre-repetition stage. Because of the stochastic nature of forgetting and recall, the same item might or might not be recalled depending on the current overall cognitive status of the brain; even if the strength and retrievability of memories of all contributing synapses is/was identical! This way we can speak about the pre-repetition recall probability of an item that has just been recalled (or not). This probability is expressed by the estimated forgetting index.

每次重复后，使用预期遗忘指数和实际成绩更新FI-G图。从重复之间的间隔和从矩阵中计算出的最佳间隔可以很容易地得到期望遗忘指数。预期遗忘指数越高，分数越低。根据年级和FI-G图，我们可以计算出估计的遗忘指数，它对应于在假设的重复前阶段对刚刚重复的项目的遗忘概率的重复后估计。由于遗忘和回忆的随机性，同一件事可能会被回忆，也可能不会被回忆，这取决于大脑当前的整体认知状态;即使所有突触的记忆强度和可恢复性是相同的!通过这种方式，我们可以谈论重复前的召回概率，即刚刚被召回(或没有被召回)的物品。这个概率用估计遗忘指数来表示。

## Algorithm SM-15

## 算法 SM-15

Algorithm SM-8 has been improved over years and evolved into Algorithm SM-11 (2002) and then Algorithm SM-15 (2011). Here I only present the latest version: Algorithm SM-15 (used in SuperMemo 15, SuperMemo 16, and as backup in SuperMemo 17).

算法SM-8经过多年的改进，先后演化为算法SM-11(2002)和算法SM-15(2011)。这里我只介绍最新的版本:算法SM-15(在SuperMemo 15中使用，SuperMemo 16中使用，在SuperMemo 17中作为备份)。

The key improvements added to Algorithm SM-8 over two decades were:

- improved stability indexing: instead of using repetition numbers, as of SuperMemo 8 (1997), the algorithm used the concept of "[repetition category](https://supermemo.guru/wiki/Repetition_category)" which roughly translates to [stability](https://supermemo.guru/wiki/Stability)
- tolerance for advanced and delayed repetitions, as of SuperMemo 11 (2002): a heuristic has been added to account for the [spacing effect](https://supermemo.guru/wiki/Spacing_effect)
- extending the representation of time in U-Factors from 60 days to 15 years (2011)
- correcting [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve) data for repetition delay beyond the original U-Factor span (2011)

算法SM-8在过去20年的主要改进是:

- 改进的稳定性索引:从SuperMemo 8(1997)开始，该算法不再使用重复编号，而是使用“[重复类别](https://supermemo.guru/wiki/Repetition_category)”的概念，这大致可以翻译为[稳定性](https://supermemo.guru/wiki/Stability)。

- 在SuperMemo 11(2002)中对高级和延迟重复的容忍:在[间隔效应]中增加了一个启发式(https://supermemo.guru/wiki/Spacing_effect)

- 将U-Factors的时间表示从60天延长到15年(2011年)

- 修正[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)超过原始u -因素跨度的重复延迟数据(2011)

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

Algorithm SM-15 begins the effort to compute the optimum inter-repetition intervals by storing the recall record of individual items (i.e. grades scored in learning). This record is used to estimate the current strength of a given memory trace, and the difficulty of the underlying piece of knowledge (item). The item difficulty expresses the complexity of memories, and reflects the effort needed to produce unambiguous and stable memory traces. SuperMemo takes the  

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

算法SM-15通过存储单个条目的回忆记录(即学习成绩)，开始计算最佳重复间隔。此记录用于估计给定内存跟踪的当前强度和基础知识(项目)的难度。项目难度表达了记忆的复杂性，反映了产生清晰、稳定的记忆痕迹所需要付出的努力。SuperMemo的

**Important!** Algorithm SM-15 is used only to compute the intervals between repetitions of items. Topics are reviewed at intervals computed with an entirely different algorithm (not described here). The timing of topic review is optimized with the view to managing the reading sequence and is not aimed at aiding memory. Long-term memories are formed in SuperMemo primarily with the help of items, which are reviewed along the schedule computed by Algorithm SM-15.

**重要!**算法SM-15仅用于计算项目重复之间的间隔。主题以完全不同的算法计算的时间间隔进行复习(这里没有描述)。主题复习的时机是为了管理阅读顺序而优化的，而不是为了帮助记忆。在SuperMemo中形成的长期记忆主要是在项目的帮助下形成的，这些项目是按照算法SM-15计算的时间表进行复习的。

This is a more detailed description of the Algorithm SM-15:

这是对算法SM-15的更详细的描述:

1. Optimum interval

   : Inter-repetition intervals are computed using the following formula:

   最优区间

   :重复间隔时间按下式计算:

   > I(1)=OF[1,L+1]
   >
   > I(n)=I(n-1)*OF[n,AF]
   >
   > where:
   >
   > - OF - matrix of optimal factors, which is modified in the course of repetitions
   > - OF[1,L+1] - value of the OF matrix entry taken from the first row and the L+1 column
   > - OF[n,AF] - value of the OF matrix entry that corresponds with the n-th repetition, and with item difficulty AF
   > - L - number of times a given item has been forgotten (from "[memory **L**apses](https://supermemo.guru/wiki/Lapse)")
   > - AF - number that reflects absolute difficulty of a given item (from "[**A**bsolute difficulty **F**actor](https://supermemo.guru/wiki/A-Factor)")
   > - I(n) - n-th inter-repetition interval for a given item
   >
   > I(1)=OF[1,L+1]
   >
   > I(n)=I(n-1)*OF[n,AF]
   >
   > 上式中：
   >
   > - OF -矩阵的最优因子，在重复的过程中进行修正
   > - OF[1,L+1] -从第一行和L+1列中提取的矩阵项的值
   >
   > - OF[n,AF] -对应第n次重复的矩阵条目的值，与条目难度AF相关
   >
   > - L -某件物品被遗忘的次数(来自“[memory **L**apses](https://supermemo.guru/wiki/Lapse)”)
   >
   > - AF -反映给定项目绝对难度的数字(来自“[**A**bsolute难度**F**actor](https://supermemo.guru/wiki/A-Factor)”)
   >
   > - I(n) -第n次重复间隔

2. Advanced repetitions

   : Because of possible advancement in executing repetitions (e.g. forced review before an exam), the actual optimum factor (OF) used to compute the optimum interval is decremented by

    

   dOF

    

   using formulas that account for the spacing effect in learning:

   先进的重复



   :由于在执行重复操作时可能会有进步(例如在考试前进行强制复习)，因此用来计算最佳间隔的实际最优因子(of)减少了

   景深

   使用公式，说明间距效应在学习:

   > *dOF*=dOFmax**a*/(thalf+*a*)
   >
   > dOFmax=(OF-1)*(OI+thalf-1)/(OI-1)
   >
   > where:
   >
   > - *dOF* - decrement to OF resulting from the *spacing effect*
   > - *a* - advancement of the repetition in days as compared with the optimum schedule (note that there is no change to OF if *a*=0, i.e. the repetition takes time at optimum time)
   > - dOFmax - asymptotic limit on *dOF* for infinite *a* (note that for a=OI-1 the decrement will be OF-1 which corresponds to no increase in inter-repetition interval)
   > - thalf - advancement at which there is half the expected increase to [synaptic stability](http://super-memory.com/english/2vm.htm) as a result of a repetition (presently this value corresponds roughly to 60% of the length of the optimum interval for well-structured material)
   > - OF - optimum factor (i.e. OF[n,AF] for the n-th interval and a given value of AF)
   > - OI - [optimum interval](https://supermemo.guru/wiki/Optimum_interval) (as derived from the OF matrix)
   >
   > *dOF*=dOFmax**a*/(thalf+*a*)
   >
   > dOFmax=(OF-1)*(OI+thalf-1)/(OI-1)
   >
   > 上式中：
   >
   > - *dOF* -由*间距效应*导致的*减量
   > - *a* -与最佳时间表相比，重复的天数增加了(请注意，如果*a*=0，则没有变化，即重复需要在最佳时间内完成)
   >
   > - dOFmax -无限*a*的*dOF*的渐近极限
   >
   > - thalf -由于重复(目前这个值大约相当于结构良好材料的最佳间隔长度的60%)，[突触稳定性](http://supermemory.com/english/2vm.htm)的预期增长的一半
   >
   > - 最优因子(即[n,AF]对于第n个区间和给定的AF值)
   >
   > - OI -[最优区间](https://supermemo.guru/wiki/Optimum_interval)(源自矩阵)

3. **Delayed repetitions**: Because of possible delays in executing repetitions, the OF matrix is not actually indexed with repetitions but with repetition categories. For example if the 5-th repetition is delayed, OF matrix is used to compute the [repetition category](https://supermemo.guru/wiki/Repetition_category), i.e. the theoretical value of the repetition number that corresponds with the interval used before the repetition. The [repetition category](https://supermemo.guru/wiki/Repetition_category) may, for example, assume the value 5.3 and we will arrive at I(5)=I(4)*OF[5.3,AF] where OF[5.3,AF] has a intermediate value derived from OF[5,AF] and OF[6,AF]

   **延迟重复**:由于执行重复可能会出现延迟，因此矩阵实际上不是用重复索引的，而是用重复类别索引的。例如，如果第5次重复被延迟，则使用OF矩阵来计算[重复类别](https://supermemo.guru/wiki/Repetition_category)，即与重复之前使用的间隔相对应的重复次数的理论值。例如，[重复类别](https://supermemo.guru/wiki/Repetition_category)可以假设值为5.3，我们将得到I(5)=I(4)*OF[5.3,AF]，其中[5.3,AF]的中间值源自[5,AF]和[6,AF]

4. **Matrix of optimum intervals**: SuperMemo does not store the matrix of optimum intervals as in some earlier versions. Instead it keeps a matrix of optimal factors that can be converted to the matrix of optimum intervals (as in the formula from Point 1). The matrix of optimal factors OF used in Point 1 has been derived from the mathematical model of forgetting and from similar matrices built on data collected in years of repetitions in collections created by a number of users. Its initial setting corresponds with values found for a less-than-average student. During repetitions, upon collecting more and more data about the student's memory, the matrix is gradually modified to make it approach closely the actual student's memory properties. After years of repetitions, new data can be fed back to generate more accurate initial OF matrix. In SuperMemo 17, this matrix can be viewed in 3D with **Tools : Statistics : Analysis : 3-D Graphs : O-Factor Matrix**

   **最佳间隔矩阵**:SuperMemo不像一些早期版本那样存储最佳间隔矩阵。相反,它使一个矩阵的最优因素转换为矩阵的最优间隔从点(如公式1)。用于点1的矩阵最优因素已经被来自遗忘和相似矩阵的数学模型建立在多年来收集的数据重复的集合创建的用户数量。它的初始值对应于低于平均水平的学生。在重复的过程中，在收集到越来越多的关于学生记忆的数据后，逐步对矩阵进行修改，使其更接近学生实际的记忆属性。经过多年的重复，可以反馈新的数据，生成更准确的初始矩阵。在SuperMemo 17中，可以使用**工具在3D中查看这个矩阵:统计:分析:3D图形:O-Factor矩阵**

5. **Item difficulty**: The absolute item difficulty factor ([A-Factor](https://supermemo.guru/wiki/A-Factor)), denoted AF in Point 1, expresses the difficulty of an item (the higher it is, the easier the item). It is worth noting that AF=OF[2,AF]. In other words, AF denotes the optimum interval increase factor after the second repetition. This is also equivalent with the highest interval increase factor for a given item. Unlike [E-Factors](https://supermemo.guru/wiki/E-Factor) in [Algorithm SM-6](https://supermemo.guru/wiki/Algorithm_SM-6) employed in SuperMemo 6 and SuperMemo 7, [A-Factors](https://supermemo.guru/wiki/A-Factor) express absolute item difficulty and do not depend on the difficulty of other items in the same collection of study material

   **项目难度**:项目的绝对难度系数([A-Factor](https://supermemo.guru/wiki/A-Factor)，记为第1点AF，表示项目难度(越高越容易)。值得注意的是AF=OF[2,AF]。即AF为第二次重复后的最佳间隔增加因子。这也等价于给定项目的最高间隔增长因子。与[[E-Factors] (https://supermemo.guru/wiki/E-Factor)不同算法SM-6) (https://supermemo.guru/wiki/Algorithm_SM-6)受雇于SuperMemo 6和SuperMemo 7,(一个因素)(https://supermemo.guru/wiki/A-Factor)表达绝对项困难和不依赖于其他项目的难度在同一个集合的研究材料

6. **Deriving OF matrix from RF matrix**: Optimum values of the entries of the OF matrix are derived through a sequence of approximation procedures from the RF matrix which is defined in the same way as the OF matrix (see Point 1), with the exception that its values are taken from the real learning process of the student for who the optimization is run. Initially, matrices OF and RF are identical; however, entries of the RF matrix are modified with each repetition, and a new value of the OF matrix is computed from the RF matrix by using approximation procedures. This effectively produces the OF matrix as a smoothed up form of the RF matrix. In simple terms, the RF matrix at any given moment corresponds to its best-fit value derived from the learning process; however, each entry is considered a best-fit entry on its own, i.e. in abstraction from the values of other RF entries. At the same time, the OF matrix is considered a best-fit as a whole. In other words, the RF matrix is computed entry by entry during repetitions, while the OF matrix is a smoothed copy of the RF matrix

   **从射频矩阵矩阵的推导**:最优值矩阵的条目的属性是通过一系列的近似过程从射频矩阵相同的方式定义的矩阵(见第1点),除了它的值是来自学生的实际学习过程优化运行。最初，矩阵和RF是相同的;然而，每一次重复都会对RF矩阵的项进行修改，并使用近似程序从RF矩阵计算出新的矩阵值。这有效地产生了作为一个平滑形式的射频矩阵的矩阵。简而言之，任何给定时刻的RF矩阵对应于从学习过程中得到的最佳拟合值;但是，每个条目都被认为是最合适的条目，即从其他RF条目的值中抽象出来的。同时，OF矩阵作为一个整体被认为是最合适的。换句话说，RF矩阵是在重复过程中逐项计算的，而OF矩阵是RF矩阵的平滑复制

7. Forgetting curves

   : Individual entries of the RF matrix are computed from

    

   forgetting curves

    

   approximated for each entry individually. Each

    

   forgetting curve

    

   corresponds with a different value of the repetition number and a different value of

    

   A-Factor

    

   (or memory lapses in the case of the first repetition). The value of the RF matrix entry corresponds to the moment in time where the forgetting curve passes the knowledge retention point derived from the

    

   requested forgetting index

   . For example, for the first repetition of a new item, if the

    

   forgetting index

    

   equals 10%, and after four days the

    

   knowledge retention

    

   indicated by the

    

   forgetting curve

    

   drops below 90% value, the value of RF[1,1] is taken as four. This means that all items entering the learning process will be repeated after four days (assuming that the matrices OF and RF do not differ at the first row of the first column). This satisfies the main premise of SuperMemo, that the repetition should take place at the moment when the forgetting probability equals 100% minus the

    

   forgetting index

    

   stated as percentage. In SuperMemo 17,

    

   forgetting curves

    

   can be viewed with

    

   [Tools](http://help.supermemo.org/wiki/Tools_menu) : [Statistics](http://help.supermemo.org/wiki/Tools_menu#Statistics) : [Analysis](http://help.supermemo.org/wiki/Analysis) : [Forgetting Curves](http://help.supermemo.org/wiki/Analysis#Forgetting_Curves)

    

   (or in 3-D with

    

   [Tools](http://help.supermemo.org/wiki/Tools_menu) : [Statistics](http://help.supermemo.org/wiki/Tools_menu#Statistics) : [Analysis](http://help.supermemo.org/wiki/Analysis) : [3-D Curves](http://help.supermemo.org/wiki/Analysis#3-D_Curves)

   ):

   遗忘曲线

   :计算RF矩阵的各个元素

   遗忘曲线

   对每一项分别取近似值。每一个

   遗忘曲线

   对应不同的重复次数值和不同的值

   一个因素

   (如果是第一次重复，记忆就会衰退)。的值对应遗忘曲线通过的知识保留点的时刻

   要求忘记指数



   。例如，对于新项的第一次重复，如果

   忘记指数

   等于10%四天之后

   知识保留

   所示

   遗忘曲线

   当值降至90%以下时，取RF[1,1]的值为4。这意味着所有进入学习过程的项目将在四天之后重复(假设矩阵和RF在第一列的第一行没有不同)。这满足了SuperMemo的主要前提，即重复应该发生在遗忘概率等于100%减去

   忘记指数

   百分数表示。SuperMemo 17,

   遗忘曲线

   可以用

   [工具](http://help.supermemo.org/wiki/Tools_menu):[统计](http://help.supermemo.org/wiki/Tools_menu#统计):[分析](http://help.supermemo.org/wiki/Analysis):[遗忘曲线](http://help.supermemo.org/wiki/analysis#forgetting_curves)

   (或在3-D与

   [工具](http://help.supermemo.org/wiki/Tools_menu):[统计](http://help.supermemo.org/wiki/Tools_menu#统计):[分析](http://help.supermemo.org/wiki/Analysis):[三维曲线](http://help.supermemo.org/wiki/Analysis#3-D_Curves)

   ):

   [![Uniform forgetting curve for a single memory stability and item difficulty level](https://supermemo.guru/images/thumb/4/46/Forgetting_curves.jpg/800px-Forgetting_curves.jpg)](https://supermemo.guru/wiki/File:Forgetting_curves.jpg)

   > ***Figure**: **Tools : Statistics : Analysis : Forgetting Curves** for 20 repetition number categories multiplied by 20 A-Factor categories. In the picture, blue circles represent data collected during repetitions. The larger the circle, the greater the number of repetitions recorded. The red curve corresponds with the best-fit forgetting curve obtained by exponential regression. For ill-structured material the forgetting curve is crooked, i.e. not exactly exponential. The horizontal aqua line corresponds with the requested forgetting index, while the vertical green line shows the moment in time in which the approximated forgetting curve intersects with the requested forgetting index line. This moment in time determines the value of the relevant R-Factor, and indirectly, the value of the optimum interval. For the first repetition, R-Factor corresponds with the first optimum interval. The values of O-Factor and R-Factor are displayed at the top of the graph. They are followed by the number of repetition cases used to plot the graph (i.e. 21,303). At the beginning of the learning process, there is no repetition history and no repetition data to compute R-Factors. It will take some time before your first forgetting curves are plotted. For that reason, the initial value of the RF matrix is taken from the model of a less-than-average student. The model of average student is not used because the convergence from poorer student parameters upwards is faster than the convergence in the opposite direction. The **Deviation** parameter displayed at the top tells you how well the negatively exponential curve fits the data. The lesser the deviation, the better the fit. The deviation is computed as a square root of the average of squared differences (as used in the method of least squares).*
   >
   > ***图**:**工具:统计:分析:遗忘曲线**对于20个重复次数类别乘以20个a因素类别。在图中，蓝色的圆圈代表在重复过程中收集的数据。圆圈越大，重复的次数越多。红色曲线对应指数回归得到的最佳拟合遗忘曲线。对于结构不良的材料，遗忘曲线是弯曲的，即不完全是指数型的。水平的aqua线对应被请求的遗忘指数，垂直的绿线表示近似的遗忘曲线与被请求的遗忘指数线相交的时刻。这一时刻决定了相关r因子的值，间接决定了最佳区间的值。对于第一次重复，r因子对应于第一次最佳间隔。O-Factor和R-Factor的值显示在图的顶部。然后是用于绘制图形的重复用例的数量(即21,303个)。在学习过程的开始，没有重复的历史和重复的数据来计算r因子。要画出你的第一个遗忘曲线需要一些时间。因此，RF矩阵的初始值取自一个低于平均水平的学生的模型。由于穷学生参数向上的收敛速度快于相反方向的收敛速度，故不采用普通学生的收敛模型。顶部显示的**Deviation**参数告诉您负指数曲线与数据的吻合程度。偏差越小，拟合越好。偏差的计算方法为差异平方和的平均值的平方根(在最小二乘法中使用)

   [![SuperMemo: Exemplary 3-D graph of forgetting curves for A-Factor=3.6](https://supermemo.guru/images/thumb/5/52/AFactor_3D_Curve.jpg/800px-AFactor_3D_Curve.jpg)](https://supermemo.guru/wiki/File:AFactor_3D_Curve.jpg)

   > ***Figure:** 3D representation of the family of forgetting curves for a single item difficulty and varying memory stability levels (normalized for U-Factor).
   >
   > ***图**:单项难度和不同记忆稳定性水平的遗忘曲线族的三维表示(U-Factor归一化)。

   [![A cumulative normalized forgetting curve for all registered repetition cases in a single collection](https://supermemo.guru/images/thumb/2/21/Cumulative_forgetting_curve.jpg/800px-Cumulative_forgetting_curve.jpg)](https://supermemo.guru/wiki/File:Cumulative_forgetting_curve.jpg)

   > **Figure:** *Cumulative forgetting curve for learning material of mixed complexity, and mixed stability. The graph is obtained by superposition of 400 forgetting curves normalized for the decay constant of 0.003567, which corresponds with recall of 70% at 100% of the presented time span (i.e. R=70% on the right edge of the graph). 401,828 repetition cases have been included in the graph. Individual curves are represented by yellow data points. Cumulative curve is represented by blue data points that show the average recall for all 400 curves. The size of circles corresponds with the size of data samples.*
   >
   > ***图：**混合复杂度、混合稳定性学习材料的累积遗忘曲线。这个图是通过400条归一化衰减常数为0.003567的遗忘曲线叠加得到的，在100%的时间跨度内对应70%的回忆率(即图右边缘的R=70%)。图中包括了401,828例重复病例。个别曲线由黄色数据点表示。累积曲线由蓝色数据点表示，这些数据点表示所有400条曲线的平均召回率。圆的大小与数据样本的大小相对应。*

8. Deriving OF matrix from the forgetting curves

   : The OF matrix is derived from the RF matrix by:

   从遗忘曲线中导出矩阵

   : OF矩阵由RF矩阵推导得到:

   1. fixed-point power approximation of the [R-Factor](https://supermemo.guru/wiki/R-Factor) decline along the RF matrix columns (the fixed point corresponds to second repetition at which the approximation curve passes through the [A-Factor](https://supermemo.guru/wiki/A-Factor) value),

      R-Factor](https://supermemo.guru/wiki/R-Factor)沿RF矩阵列下降的定点功率近似值(该固定点对应于近似值曲线通过[A-Factor]时的第二次重复(https://supermemo.guru/wiki/A-Factor)值)，

   2. for all columns, computing D-Factor which expresses the decay constant of the power approximation,

      对于所有列，计算表示幂近似衰减常数的d因子，

   3. linear regression of D-Factor change across the RF matrix columns, and

      d因子在RF矩阵列上的变化的线性回归

   4. deriving the entire OF matrix from the slope and intercept of the straight line that makes up the best fit in the D-Factor graph. The exact formulas used in this final step go beyond the scope of this illustration.

      从构成d因子图中最佳拟合的直线的斜率和截距推导出整个矩阵。最后一步中使用的确切公式超出了本文的范围。

   Note that the first row of the OF matrix is computed in a different way. It corresponds to the best-fit exponential curve obtained from the first row of the RF matrix. All the above steps are passed after each repetition. In other words, the theoretically optimum value of the OF matrix is updated as soon as new forgetting curve data is collected, i.e. at the moment, during the repetition, when the student, by providing a grade, states the correct recall or wrong recall (i.e. forgetting) (in

   注意，矩阵的第一行的计算方法不同。它对应于从RF矩阵的第一行得到的最佳拟合指数曲线。以上所有步骤都是在每次重复之后进行的。换句话说，当收集到新的遗忘曲线数据时，即在重复的时刻，即在重复的过程中，当学生通过提供分数来陈述正确的回忆或错误的回忆(即遗忘)时，更新矩阵的理论最优值(In)

    

   Algorithm SM-6

   , a separate procedure Approximate had to be used to find the best-fit OF matrix, and the OF matrix used at repetitions might differ substantially from its best-fit value)

   算法SM-6

   ，必须使用一个单独的近似过程来寻找矩阵的最佳拟合，而重复使用的矩阵可能与其最佳拟合值有很大的差异。

9. **Item difficulty**: The initial value of [A-Factor](https://supermemo.guru/wiki/A-Factor) is derived from the first grade obtained by the item, and the correlation graph of the first grade and [A-Factor](https://supermemo.guru/wiki/A-Factor) ([G-AF graph](http://help.supermemo.org/wiki/Analysis#First_Grade_vs._A-Factor)). This graph is updated after each repetition in which a new [A-Factor](https://supermemo.guru/wiki/A-Factor) value is estimated and correlated with the item's first grade. Subsequent approximations of the real [A-Factor](https://supermemo.guru/wiki/A-Factor) value are done after each repetition by using grades, OF matrix, and a correlation graph that shows the correspondence of the grade with the expected forgetting index ([FI-G graph](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index)). The grade used to compute the initial [A-Factor](https://supermemo.guru/wiki/A-Factor) is normalized, i.e. adjusted for the difference between the actually used interval and the optimum interval for the forgetting index equal 10%

   **项目难度**:(因素)的初始值(https://supermemo.guru/wiki/A-Factor)是来自一年级获得的项目,和一年级的相关图[因素](https://supermemo.guru/wiki/A-Factor) ([G-AF图](http://help.supermemo.org/wiki/Analysis # First_Grade_vs._A-Factor))。此图在每次重复之后更新，其中一个新的[a - factor](https://supermemo.guru/wiki/A-Factor)值被估计并与项目的一级相关。随后近似真实的[因素](https://supermemo.guru/wiki/A-Factor)值完成每次重复利用的成绩后,矩阵,和相关图表显示对应年级的预期忘记指数([FI-G图](http://help.supermemo.org/wiki/Analysis # Grade_vs._Forgetting_Index))。用于计算初始[a -因素](https://supermemo.guru/wiki/a-factor)的分数被归一化，即调整为实际使用的时间间隔与遗忘指数的最佳时间间隔之差为10%

10. **Grades vs. expected forgetting index correlation**: The FI-G graph is updated after each repetition by using the [expected forgetting index](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index) and actual grade scores. The [expected forgetting index](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index) can easily be derived from the interval used between repetitions and the [optimum interval](https://supermemo.guru/wiki/Optimum_interval) computed from the OF matrix. The higher the value of the [expected forgetting index](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index), the lower the grade. From the grade and the FI-G graph (see: [FI-G graph](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index) in **Tools : Statistics : Analysis : Graphs**), we can compute the [estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index) which corresponds to the post-repetition estimation of the forgetting probability of the just-repeated item at the hypothetical pre-repetition stage. Because of the stochastic nature of forgetting and recall, the same item might or might not be recalled depending on the current overall cognitive status of the brain; even if the strength and retrievability of memories of all contributing synapses is/was identical! This way we can speak about the pre-repetition recall probability of an item that has just been recalled (or not). This probability is expressed by the [estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)

    **分数与预期遗忘指数的相关性**:每次重复使用[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)和实际分数更新fig图。[期望遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)可以很容易地从重复和[最优间隔](https://supermemo.guru/wiki/Optimum_interval)之间的间隔中得到。[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)值越高，分数越低。从年级和FI-G图(见:[FI-G图](http://help.supermemo.org/wiki/Analysis Grade_vs._Forgetting_Index) * *工具:统计:分析:图* *),我们可以计算[估计忘记指数](http://help.supermemo.org/wiki/Forgetting_index estimated_forgetting_index)对应于post-repetition忘记重复项的概率的估计假设pre-repetition阶段。由于遗忘和回忆的随机性，同一件事可能会被回忆，也可能不会被回忆，这取决于大脑当前的整体认知状态;即使所有突触的记忆强度和可恢复性是相同的!通过这种方式，我们可以谈论重复前的召回概率，即刚刚被召回(或没有被召回)的物品。这个概率用[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)

11. **Computing A-Factors**: From (1) the [estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index), (2) length of the interval and (3) the OF matrix, we can easily compute the most accurate value of [A-Factor](https://supermemo.guru/wiki/A-Factor). Note that [A-Factor](https://supermemo.guru/wiki/A-Factor) serves as an index to the OF matrix, while the [estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index) allows one to find the column of the OF matrix for which the [optimum interval](https://supermemo.guru/wiki/Optimum_interval) corresponds with the actually used interval corrected for the deviation of the [estimated forgetting index](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index) from the [requested forgetting index](http://help.supermemo.org/wiki/Forgetting_index#requested_forgetting_index). At each repetition, a weighted average is taken of the old [A-Factor](https://supermemo.guru/wiki/A-Factor) and the new estimated value of the [A-Factor](https://supermemo.guru/wiki/A-Factor). The newly obtained [A-Factor](https://supermemo.guru/wiki/A-Factor) is used in indexing the OF matrix when computing the new optimum inter-repetition interval

    **计算a -因素**:从(1)[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)，(2)区间长度和(3)矩阵，我们可以很容易地计算出最准确的[a -因素]值(https://supermemo.guru/wiki/a -因素)。注意[A-Factor](https://supermemo.guru/wiki/A-Factor)是OF矩阵的索引，而[估计忘记指数](http://help.supermemo.org/wiki/Forgetting_index estimated_forgetting_index)允许一个人找到的矩阵的列[最优区间](https://supermemo.guru/wiki/Optimum_interval)符合实际使用间隔纠正偏差的[估计忘记指数](http://help.supermemo.org/wiki/Forgetting_index estimated_forgetting_index)(要求遗忘指数(http://help.supermemo.org/wiki/Forgetting_index # requested_forgetting_index)。每次重复时，对旧的[a - factor](https://supermemo.guru/wiki/A-Factor)和[a - factor]的新估计值进行加权平均(https://supermemo.guru/wiki/A-Factor)。在计算新的最优重复间隔时，将新得到的[A-Factor](https://supermemo.guru/wiki/A-Factor)用于矩阵的索引

To sum it up. Repetitions result in computing a set of parameters characterizing the memory of the student: RF matrix, , and[FI-G graph](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index)   , which in turn is used in computing the optimum inter-repetition interval for items of different difficulty () and different number of repetitions (or[memory lapses](https://supermemo.guru/wiki/Lapse)in the case of the first repetition). Initially, all student’s memory parameters are taken as for a less-than-average student (less-than average yields faster convergence than average or more-than-average), while all[A-Factors](https://supermemo.guru/wiki/A-Factor)are assumed to be equal (unknown)

总结一下。重复导致计算的一组参数描述学生的记忆:RF矩阵,,,[FI-G图](http://help.supermemo.org/wiki/Analysis # Grade_vs._Forgetting_Index),进而用于计算最优inter-repetition间隔不同难度的项目()和不同数量的重复(或[记忆缺失](https://supermemo.guru/wiki/Lapse)的第一个重复)。一开始，所有学生的内存参数都被当作低于平均水平的学生(低于平均水平比平均水平收敛得更快，或者高于平均水平)，而所有[a - factor](https://supermemo.guru/wiki/A-Factor)被假定为相等(未知)