# 1995 年：超媒体 SuperMemo

## SM-8 算法在山间小屋中诞生

1995 年，[SuperMemo](https://supermemo.guru/wiki/SuperMemo) 重写。这是个好时机，可以利用 [SM-6 算法](https://supermemo.guru/wiki/Algorithm_SM-6)采用后四年以来的数据，实现新的[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)算法。

1995 年 3 月，在汉诺威的 CeBIT 展会上，我们看到了 Borland 开发的全新开发环境：Delphi。它与旧的 Borland Pascal 完全不可同日而语 ，并为 [SuperMemo](https://supermemo.guru/wiki/SuperMemo) 开启了数十个开发机会。我们决定按照我的[博士论文](https://supermemo.guru/wiki/Economics_of_learning)中描绘的思路重新设计程序。不仅能实现[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)之外，我们还想加入知识结构和超媒体。[项目](https://supermemo.guru/wiki/Item)不会是一团乱麻，用户将能够建立[知识树](https://supermemo.guru/wiki/Knowledge_tree)。告别只有问题、答案、图片、声音的模板，我们希望掌握所有可能的组件类型，这些组件可以聚合成新的超媒体形式来更好表达知识。还有一个梦想，那就是可编程的 SuperMemo，其中开发者编写自己的程序来实现各种各样的练习，包括程序练习、盲打练习或者解一元二次方程。于此同时，我们收集了很多数据，这些数据表明 [SuperMemo](https://supermemo.guru/wiki/SuperMemo) 中使用的算法可以得到改进。例如，[最优系数矩阵](https://supermemo.guru/wiki/OF_matrix)的数学性质已经相当明显。

1995 年 5月，我带上我的奔腾电脑，前往波兰南部一处偏远的山上小屋去研究这些想法。那是完全与世隔绝的 100 天，只有[Krzysztof Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak) 的一次简短拜访打断了我，其间我和他重新同步了对未来 [SuperMemo](https://supermemo.guru/wiki/SuperMemo) 的设想。到 1995 年 9 月，新的算法已经就绪，我在自己的数据上测试了这个算法。回到波兹南后，我开始逐步将我所有的学习过程从 [SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7) 中的多个[集合](https://supermemo.guru/wiki/Collection)转移到开发出的新环境，我亲切地称为「Genius」。两年后，直到新程序终于可以包含 SuperMemo 7 中的所有功能了，Genius 才成为 [SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8)。

开发 SM-8 算法中，最重要的数据是[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)和 [OF 矩阵](https://supermemo.guru/wiki/OF_matrix)数据，通过 [SuperMemo 6](https://supermemo.guru/wiki/SuperMemo_6) 和 [SuperMemo 7](https://supermemo.guru/wiki/SuperMemo_7) 收集可得。这些数据减少了算法中的猜测成分。开发 SM-8 算法与开发 [SM-17 算法（2014-2016）](https://supermemo.guru/wiki/Algorithm_SM-17) 相比是相当轻松了，开发 SM-17 算法时我有庞大如山的间隔重复历史数据需要处理，而且对精度和[优良指标](https://supermemo.guru/wiki/Universal_metric)的要求也增加了两倍。SM-17 算法光开发就花了整整两年，然而 SM-8 算法从设计，实现，到充分测试仅用了 100 天。

算法 SM-8 的主要想法：

- 基于实时近似实现精确求解 [OF 矩阵](https://supermemo.guru/wiki/OF_matrix)。为描述矩阵，我想找出精准的数学函数，并对矩阵进行实时更新，而不是使用 [SuperMemo 5](https://supermemo.guru/wiki/SuperMemo_5) 以来的矩阵平滑手段。很容易确定有一个负指数幂函数决定了 [OF](https://supermemo.guru/wiki/O-Factor)=f(RepNo) （用今天的术语就是 [Slnc](https://supermemo.guru/wiki/Stability_increase)(https://supermemo.guru/wiki/Stability_increase)=f(S)）在确定[难度](https://supermemo.guru/wiki/Difficulty)对 [Slnc](https://supermemo.guru/wiki/Stability_increase)(https://supermemo.guru/wiki/Stability_increase) 的影响上有更多的猜测成分。将项目难度（[A-系数](https://supermemo.guru/wiki/A-Factor)）映射到 Slnc（D-系数）的函数描述了随着稳定性/间隔增加，[稳定性增长](https://supermemo.guru/wiki/Stability_increase)减少，对于这个函数我使用了线性近似。这个近似沿用到了今天。是个好猜测。

有了对 OF 矩阵的良好定义，我就可以精确定义项目[难度](https://supermemo.guru/wiki/Difficulty)了： [E-系数](https://supermemo.guru/wiki/E-Factor)变化不定，按用户心思由[评分](https://supermemo.guru/wiki/Grade)手动控制，相比之下，我希望让难度绝对不变，于是便有 [A-系数](https://supermemo.guru/wiki/A-factor)，定义为稳定性设为 R=0.9 时第一次[重复](https://supermemo.guru/wiki/Repetition)后的[稳定性增长](https://supermemo.guru/wiki/Retrievability) 。这样设定后，[SuperMemo](https://supermemo.guru/wiki/SuperMemo) 每次重复便有可能调整项目难度，方法是按照 [OF 矩阵](https://supermemo.guru/wiki/OF_matrix)得到的预期表现，修正对项目表现的拟合。

- 将第一次[评分](https://supermemo.guru/wiki/Difficulty)与 [A-系数](https://supermemo.guru/wiki/Grade)联系起来，从而更快确定初始[难度](https://supermemo.guru/wiki/A-factor)。这个机制不很有用，也不太重要，因为即便有更多重复历史，项目难度也是很模糊的概念。这样看来，用户需要注意的是，好好表述每个项目，保证每个项目都很简单才是上策。

- 基于遗忘次数进行指数拟合，来近似确定[遗忘](https://supermemo.guru/wiki/Lapse)后第一个间隔。这种方法的最大价值，是破除一个迷思，即记忆遗忘之后，缩短间隔能够提高学习速度。有些基于 [SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) 算法的软件的作者选择缩短间隔，但这种做法已证实是错的。一些基于 [Leitner 系统](https://supermemo.guru/wiki/Leitner_system)变体的软件中也有使用这个做法，如 [Duolingo](https://supermemo.guru/wiki/Duolingo).  

- 将[评分](https://supermemo.guru/wiki/Grade)与[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)关联起来的做法是无效的，对改进算法也无益。真相很久之后才被揭露。最后断言花了十年才得出：评分和遗忘指数的联系非常微弱。基于 [SM-2 算法](https://supermemo.guru/wiki/Algorithm_SM-2)的直觉只对了一点点

有趣的是，SM-8 算法并不需要元素有完整的间隔重复历史。记录完整重复历史的功能在 1996 年 2 月才实现。不要求完整历史的好处是容易时间，缺点是，一旦用户在学习过程中进行了手动干预，算法就没有这种干预的记录，也就无法防御不正确数据的输入。二十年后 [SM-17 算法]的实现，当然也仰仗于完整的间隔重复历史。

1995 年 8 月 16 日，星期三，我在算法 SM-8 中对自己的数据进行了第一次「实地」间隔重复学习。为了这次测试，我「贡献」了一个小型集合，含有 100 个项目，主要是数字的助记挂钩。在接下来的两年里，我逐渐将我所有的其他集合适配到新算法和新的 SuperMemo 环境。在 1997 年，我的所有知识终于被整合到单独一个结构良好的数据库中。从 1995 年到 1997 年，这种数据库称为「知识系统」。今天，我们只称作[集合](https://supermemo.guru/wiki/Collection)（如知识集合）。

时至今日，这 1995 年诞生的算法的核心仍在 [SuperMemo 17](https://supermemo.guru/wiki/SuperMemo_17) 中默默运行。用户如果对 [SM-17 算法](https://supermemo.guru/wiki/Algorithm_SM-17)建议的间隔不满意，仍可根据该旧算法选择间隔。

## 绝对项目难度

从 SuperMemo 1.0 到 SuperMemo 3.0，[E-系数](https://supermemo.guru/wiki/E-Factor)和 [O-系数](https://supermemo.guru/wiki/O-Factor) 定义相同（即连续间隔的比率）。这两个系数用于近似衡量项目[难度](https://supermemo.guru/wiki/Difficulty)（E-系数越高，项目越容易）。然而，[间隔重复优化](https://supermemo.guru/wiki/Algorithm_SM-2) 会迫使 E-系数对应上[稳定性增长](https://supermemo.guru/wiki/Stability_increase)，可后者会随着[稳定性](https://supermemo.guru/wiki/Stability)而下降。换句话说，[算法 SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) 中，从定义上[项目](https://supermemo.guru/wiki/Item)会被标记为越来越「难」，因为它们会被连续重复。这有点违反直觉，而用户似乎从未注意到。

从 SuperMemo 4.0 开始，E-系数被用于索引 O-系数的矩阵。E-系数仍然用来反映项目的难度，以及计算 O-系数。然而，它们可以与 O-系数不同，从而更好地反映难度。

从 SuperMemo 4 到 SuperMemo 7，给定一个数据库，其中材料的难度会决定 O-系数和 E-系数的关系。比如，在简单的集合中，初始 O-系数（也就是第一次重复和假定的初始[难度](https://supermemo.guru/wiki/Difficulty)的O-系数）会相对较高。屡次重复的表现决定了 E-系数，那么即使在简单集合中项目的 E-系数，也会低于在困难集合中的相同难度的项目。在 [SuperMemo 8](https://supermemo.guru/wiki/SuperMemo_8) 引入 [A-系数](https://supermemo.guru/wiki/Collection)(https://supermemo.guru/wiki/A-Factor)后，一切都改变了。A-系数是「绑定」到 O-系数矩阵的第二行上的。这样 [A-系数](https://supermemo.guru/wiki/Collection)(https://supermemo.guru/wiki/A-Factor)便是项目难度的绝对衡量指标。**A系数的值不因集合内容而变化。**比如，如果 A 系数是 1.5, 那么第三次重复前的间隔，就会比第一个间隔长 50%.

存档警告：[为什么使用文字档案？](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

[A-系数](https://supermemo.guru/wiki/A-Factor)是与[集合](https://supermemo.guru/wiki/Collection)中每个[元素](https://supermemo.guru/wiki/Element)相关的数字。A-系数决定了在学习过程中，[间隔](https://supermemo.guru/wiki/Interval)变大的程度。A-系数越高，间隔的增加就越快。A-系数反映了项目的[难度](https://supermemo.guru/wiki/Difficulty)。A-系数越高，[项目](https://supermemo.guru/wiki/Item)越容易。最难的项目的 A-系数等于 1.2。A-系数被定义为第二个[最优间隔](https://supermemo.guru/wiki/Optimum_interval)和第一个最优间隔的比值。

## 遗忘后的间隔

SM-8 算法中的遗忘后间隔近似法否定了两个迷思：

- 缩短遗忘后的间隔是个好主意（这个想法在 1991-2000 年期间被多次提出过）

- 第一个间隔应该总是 1 天（一些旧的 SuperMemo 解决方案如此）

在下面的图表中，我们可以看到，如果连续遗忘，最优的遗忘后间隔不断变短。这无非说明，较高的遗忘次数，仅仅来自表述得很差劲的项目，或者那些语义上难以记忆，或者有其他干扰知识的项目。对于以 Lapse=10 开始的记忆，我建议用「[有毒](https://supermemo.guru/wiki/Toxic_memory)」这个术语来表达它们对学习过程的影响。如果大脑拒绝记忆一个信息那么多次，我们应该明白：这个知识的表述很糟糕，或者由于其他原因（例如与学习有关的压力，如在学校）而变得有毒。

存档警告：[为什么使用文字档案？](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**首个间隔** - 第一次重复后的第一次间隔的长度，取决于某个项目被遗忘的次数。注意，这里的第一次重复是指遗忘后的第一次重复，而**不是**项目创建以来的第一次重复。换句话说，一个重复了两次的项目在被遗忘后，其重复次数将等于 1 而不等于 3。首个间隔画成图线，得到了指数回归曲线，这条曲线近似描述了不同次数的记忆错误（包括与新记忆的项目相对应的零错误类别）对应的第一区间长度。在下图中，蓝色圆圈对应于学习过程中收集的数据（圆圈越大，记录的重复次数越多）。

[![SuperMemo: Tools : Statistics : Analysis : Graphs : First Interval shows you exponential regression curve that approximates the length of the first interval for different numbers of memory lapses](https://supermemo.guru/images/thumb/c/c7/First_interval.jpg/800px-First_interval.jpg)](https://supermemo.guru/wiki/File:First_interval.jpg)

> 图注：上图涵盖了了超过 130,000 次重复的数据，根据这张图，新记忆的项目在 7 天后重复是最理想的。然而，遗忘了 10 次的项目（这在 SuperMemo 中是很少见的）需要 2 天间隔之后出现。(由于按对数缩放，圆圈的大小与数据样本并不成正比；Lapses=0 的重复情况远远大于 Lapses=10 的情况，这一点在**[分布](http://help.supermemo.org/wiki/Analysis#Distributions) : [Lapses](http://help.supermemo.org/wiki/Analysis#Lapses)**中可以看出)

## 首次评分与 A-系数的关系

将首次评分与预估项目难度相关联的做法，是为了刚开始学习时，对项目按难度进行分类。这种相关性似乎很弱，而且极其依赖于用户心中的评分系统。对于一些用户来说，两者几乎没有相关性可言（图片#1）。对其他用户来说，两者相关性足够强，能覆盖全部的难度范围（A-系数）（图片#2）。

[![SuperMemo: Tools : Analysis : Graphs : First Grade vs. A-Factor correlates the first grade obtained by an item with the ultimate estimation of its A-Factor value](https://supermemo.guru/images/thumb/2/2a/First_Grade_vs_A-Factor_All.jpg/800px-First_Grade_vs_A-Factor_All.jpg)](https://supermemo.guru/wiki/File:First_Grade_vs_A-Factor_All.jpg)

[![SuperMemo: Tools : Analysis : Graphs : First Grade vs. A-Factor correlates the first grade obtained by an item with the ultimate estimation of its A-Factor value](https://supermemo.guru/images/thumb/9/96/First_Grade_vs_A-Factor_Molie.jpg/800px-First_Grade_vs_A-Factor_Molie.jpg)](https://supermemo.guru/wiki/File:First_Grade_vs_A-Factor_Molie.jpg)

此外，从算法 SM-8 发展而来的 SM-11 算法，允许用户提早重复。这些重复对于[间隔效应](https://supermemo.guru/wiki/Spacing_effect) 有作用，但是，它们仍然被归入图标数据中，并使得困难项目的评分被高估。若[渐进阅读](https://supermemo.guru/wiki/Incremental_reading)得到广泛使用，图线将更加平缓。

[SM-17 算法](https://supermemo.guru/wiki/Algorithm_SM-17)不将评分与难度关联，而是根据整个重复历史计算难度。实践表明，即使这样做，估计难度也很困难，因而学习的好做法是让所有项目都足够简单（用公认的记忆法的说法就是，与学生的其他知识相契合）。

存档警告：[为什么使用文字档案？](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**首次评分与 A-系数** - G-AF 图将项目的首次评分与其 A-系数的最终估计值联系起来。在每次重复时，当前元素过往的 A-系数估计值被从图中删除，并添加新的估计值。[SM-15 算法](https://supermemo.guru/wiki/Algorithm_SM-15)用这个图来快速估计 A-系数的第一个值，此时只有首次重复中得到的首个评分是已知的。

## 评分 vs. 遗忘指数

通过将评分与预期的遗忘指数（预测的[可提取性](https://supermemo.guru/wiki/Retrievability)）相关联，我希望能估计出遗忘指数（实际[可提取性](https://supermemo.guru/wiki/Retrievability)的重复后估计）。这种相关性似乎很弱，因为所有用户自己都有一套评分准则，而这套准则往往前后不一致。评分和可提取性的关联可归因于这个事实：复杂的项目评分更差，而且往往遗忘得更快（至少在开始时）。在这个意义上，评分更好地反映了[复杂性](https://supermemo.guru/wiki/Complexity)，而非[可提取性](https://supermemo.guru/wiki/Retrievability)。

如下图所示，预期遗忘指数的整个范围似乎都落在 3 分左右。

[![SuperMemo: Tools : Statistics : Analysis : Graphs : Grade vs. Forgetting Index graph](https://supermemo.guru/images/thumb/6/6d/Grade_vs_Forgetting_Index.jpg/800px-Grade_vs_Forgetting_Index.jpg)](https://supermemo.guru/wiki/File:Grade_vs_Forgetting_Index.jpg)

对于评分 <=3，我们可以读取最大的估计遗忘指数，对于评分 >=4，我们可以读取最小的估计遗忘指数。从这个角度来看，两个等级系统对算法的影响与六个等级系统完全相同。

对于其他用户来说，预期遗忘指数的某些取值下，评分曲线甚至可能达到峰值，就好像评分反映了记住棘手项目的愿望（宽松的评分）。

[SM-17 算法](https://supermemo.guru/wiki/Algorithm_SM-17) 大范围使用了可提取性，是在重复后估计的。然而，可提取性是根据大量的召回数据和预期的可提取性计算出来的。评分与可提取性的相关性数据也有所收集，但是这两者的相关性可以忽略不计。

存档警告：[为什么使用文字档案？](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

**评分与遗忘指数** - FI-G 图将[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)与重复评分联系起来。你需要了解[算法 SM-15](https://supermemo.guru/wiki/Algorithm_SM-15) 才能理解这个图。你可以想象，[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)图的纵轴上可能使用平均评分而不是[保留率](https://supermemo.guru/wiki/Retention)。把平均评分与[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)相关联，就会得到 FI-G 图。这个图表是用来计算[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)的，而估计遗忘指数又用来对评分进行归一化处理（对于延迟或提前的重复），并估计项目的 A-系数的新值。评分是用如下公式计算出来的：*Grade=expA/*FI+B*，其中 A 和 B 是对复重复期间收集的原始数据进行指数回归的参数。

每次重复后，根据预期遗忘指数和实际评分来更新 FI-G 图。预期遗忘指数可以很容易地从重复间隔，和从 OF 矩阵中计算出的最佳间隔中计算出。预期遗忘指数的值越高，评分就越低。利用评分和 FI-G 图，我们可以计算出估计遗忘指数，即在完成项目重复后，估算得出的项目重复之前的遗忘概率。由于遗忘和回忆的随机性，同一个项目或许能回忆起来，或许回忆不起来，这取决于大脑当前的整体认知状态；即使所有贡献记忆的突触的记忆强度和可提取性是/以前是相同的！这样，我们就可以谈论一个刚刚回忆（或未被回忆）的项目的重复前回忆概率。这个概率由估计遗忘指数表示。

## SM-15 算法

SM-8 算法经过多年的改进，演变成 SM-11 算法（2002），然后是 SM-15 算法（2011）。这里我只介绍最新的版本：SM-15 算法（在 SuperMemo 15、SuperMemo 16 中使用，并作为 SuperMemo 17 的备份算法）。

二十年来， SM-8 算法得到的关键改进有：

- 稳定性索引改善：从 SuperMemo 8 (1997) 开始，算法不再使用重复次数，而是使用「[重复类别](https://supermemo.guru/wiki/Repetition_category)」的概念，大致相当于[稳定性](https://supermemo.guru/wiki/Stability)

- 容许提前重复和延迟重复，从 SuperMemo 11 (2002) 开始：使用一种启发式方法将[间隔效应](https://supermemo.guru/wiki/Spacing_effect)纳入考虑

- 将 U-系数中的时间表示从 60 天延长到 15 年（2011）

- 根据超过原 U-系数范围的重复推迟，纠正[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)数据（2011）

存档警告：[为什么使用文字档案？](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

为能计算最优重复间隔，SM-15 算法储存了单个项目的回忆记录（即学习中的评分），将其用来估计某个记忆轨迹的当前强度，以及项目背后的知识（项目）的难度。项目难度反映了记忆的复杂性，以及在脑中留下稳定而不模糊的记忆所需的精力。SuperMemo 将[目标回忆率](https://supermemo.guru/wiki/Forgetting_index)作为优化标准（如 95%），来计算出满足这一标准的间隔。最优间隔的函数以矩阵表示（OF 矩阵），并根据学习过程的结果随时修改。尽管满足优化标准是相对容易的，但算法的复杂性来自于在已知的记忆模型下，收敛速度最大化的需要。

**重要！**SM-15 算法仅用于计算项目重复的时间间隔。主题的复习时间间隔是用完全不同的算法计算的（这里不做描述）。主题复习的时间是为了管理阅读顺序而优化的，而非为了提升记忆。在 SuperMemo 中，长期记忆主要是借助项目形成的，这些项目是按照 SM-15 算法计算的时间表来复习的。

对 SM-15 算法更详细的描述如下：

1. 最优间隔：使用以下公式计算重复间隔：

   > I(1)=OF[1,L+1]

   >

   > I(n)=I(n-1)*OF[n,AF]

   >

   > 其中：

   >

   > - OF - 最优系数矩阵，在重复过程中有所修改

   > - OF[1,L+1] - 第一行和 L+1 列上的 OF 矩阵元素的值

   > - OF[n,AF] - 与第 n 次重复对应的 OF 矩阵元素的值，项目难度为 AF

   > - L - 某一项目被遗忘的次数（取自「[memory **L**apses](https://supermemo.guru/wiki/Lapse)」

   > - AF - 反映某一项目绝对难度的数字（取自「[**A**bsolute difficulty **F**actor](https://supermemo.guru/wiki/A-Factor)」）

   > - I(n) - 某一项目的第 n 个重复间隔

2. 提前重复：由于重复可能提前（如考试前的强制复习），用于计算最优间隔的实际最佳系数（OF）要减去 dOF，利用考虑到学习中间隔效应的公式：

   > *dOF*=dOFmax**a*/(thalf+*a*)

   >

   > dOFmax=(OF-1)*(OI+thalf-1)/(OI-1)

   >

   > 其中：

   >

   > - *dOF* - **[间隔效应](https://supermemo.guru/wiki/Spacing_effect)**引发的 OF 下降

   > - *a* - 与最优安排相比，重复时机提前的天数（注意，如果 *a*=0，则 OF 没有变化，也就是说，重复时间与最优安排吻合）

   > - dOF_max - *a* 趋向于无限时 *dOF* 的近似极限（注意，对于 a=OI-1，下降量将是 OF-1，相当于重复间隔不增加）

   > - t_half - 复习后[突触稳定性](http://super-memory.com/english/2vm.htm)达到预期增长一半的复习提前天数（目前这个值大约相当于最优间隔长度的 60%，如果材料结构良好）。

   > - OF - 最优系数（即 OF[n,AF]，在第 n 个间隔给定 AF 的值）

   > - OI - [最优间隔](https://supermemo.guru/wiki/Optimum_interval)（从 OF 矩阵中计算出）

3. **延迟重复**：由于在重复时可能出现延迟，OF 矩阵的索引实际上不是重复，而是重复类别。例如，如果第 5 次重复是延迟的，OF 矩阵被用来计算[重复类别](https://supermemo.guru/wiki/Repetition_category)，即与重复前使用的间隔对应的重复次数的理论值。例如若[重复类别](https://supermemo.guru/wiki/Repetition_category)取 5.3，便有 I(5)=I(4)*OF[5.3,AF]，其中 OF[5.3,AF] 是从 OF[5,AF] 和 OF[6,AF] 得出的中间值

4. **最优间隔矩阵**：SuperMemo 并不存储最优间隔矩阵，虽然部分早期版本有存。作为替代，SuperMemo 记录最优系数矩阵，由此可以转换为最优间隔矩阵（由第 1 点中的公式）。第 1 点中使用的最优系数矩阵来自遗忘的数学模型和类似的矩阵，这些矩阵的数据来自一些集合多年重复练习数据。其初始设置按照水平中下的学生取值。在重复过程中，随着学生记忆的数据越来越多，矩阵逐步得到修改，进而更接近实际学生的记忆属性。经过多年的重复，新数据可以反过来用于生成更准确的初始 OF 矩阵。在SuperMemo 17中，这个矩阵可以通过**[工具](http://help.supermemo.org/wiki/Tools_menu)：[统计](http://help.supermemo.org/wiki/Tools_menu#Statistics)：[分析](http://help.supermemo.org/wiki/Analysis)：[3-D图表](http://help.supermemo.org/wiki/Analysis#3-D_Graphs)：O-系数矩阵**以 3D 方式查看。

5. **项目难度**：绝对项目难度系数（[A-系数](https://supermemo.guru/wiki/A-Factor)），在第 1 点中表示为 AF，表示一个项目的难度（AF 越高，项目越容易）。值得注意的是，AF=OF[2,AF]。换句话说，AF 表示第二次重复后的最优间隔增长系数。这也等同于给定项目的最高间隔增长系数。与 SuperMemo 6 和 SuperMemo 7 中使用的[算法 SM-6](https://supermemo.guru/wiki/Algorithm_SM-6) 中的 [E-系数](https://supermemo.guru/wiki/E-Factor) 不同，[A-系数](https://supermemo.guru/wiki/A-Factor)表示绝对的项目难度，不依赖同一学习材料集合中其他项目的难度。

6. **从 RF 矩阵中计算出 OF 矩阵**：OF 矩阵元素的最优值是通过一些近似流程从 RF 矩阵中得出的，RF 矩阵的定义与 OF 矩阵大体相同（见第 1 点），只不过 RF 矩阵的值取自真实学习过程。一开始，OF 矩阵和 RF 矩阵是相同的；然而 RF 矩阵中的项在每次重复时都会被修改，OF 矩阵的新值是通过使用近似程序从 RF 矩阵计算出来的。OF 矩阵实际上是 RF 矩阵的平滑形式。简单地说，RF 矩阵在任何给定的时刻都对应于从学习过程中得到的最优拟合值；然而，每个元素被认为本身上就是最优拟合元素，即从其他 RF 元素的值中抽象出来。同时，OF 矩阵被认为是整体上是最佳匹配的。换句话说，在重复过程中，RF 矩阵是逐条计算的，而 OF 矩阵是 RF 矩阵的一个平滑副本。

7. **遗忘曲线**：RF 矩阵的各个元素是根据每个元素的[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)单独近似计算出来的。每条[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)都对应着不同的重复次数和 [A-系数](https://supermemo.guru/wiki/A-Factor)值（或在第一次重复的情况下的遗忘次数）。RF 矩阵元素的值与遗忘曲线通过[目标遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#requested_forgetting_index)得出的知识保留点的时间点相对应。例如，对于一个新项目的第一次重复，如果[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)等于 10%，四天后[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)所表示的[知识保留率](https://supermemo.guru/wiki/Retention)下降到 90% 以下，那么 RF[1,1] 的值就取为 4。这意味着所有进入学习过程的项目将在四天后被重复使用（假设矩阵 OF 和 RF 在第一列的第一行没有差异）。这满足了 SuperMemo 的主要前提，即当遗忘概率等于 100% 减去以百分比表示的[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)时，就应该进行重复。在 SuperMemo 17 中，[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)可以用**[工具](http://help.supermemo.org/wiki/Tools_menu)：[统计](http://help.supermemo.org/wiki/Tools_menu#Statistics)：[分析](http://help.supermemo.org/wiki/Analysis)：[遗忘曲线](http://help.supermemo.org/wiki/Analysis#Forgetting_Curves)**（或用**[工具](http://help.supermemo.org/wiki/Tools_menu)：[统计](http://help.supermemo.org/wiki/Tools_menu#Statistics)：[分析](http://help.supermemo.org/wiki/Analysis)：[三维曲线](http://help.supermemo.org/wiki/Analysis#3-D_Curves)**）查看。

   [![Uniform forgetting curve for a single memory stability and item difficulty level](https://supermemo.guru/images/thumb/4/46/Forgetting_curves.jpg/800px-Forgetting_curves.jpg)](https://supermemo.guru/wiki/File:Forgetting_curves.jpg)

      > 图：[工具](http://help.supermemo.org/wiki/Tools_menu) : [统计](http://help.supermemo.org/wiki/Tools_menu#Statistics) : [分析](http://help.supermemo.org/wiki/Analysis) : [遗忘曲线](http://help.supermemo.org/wiki/Analysis#Forgetting_Curves)为 20 个重复次数类别乘以 20 个A-系数类别。在图片中，蓝色圆圈代表在重复过程中收集的数据。圆圈越大，记录的重复次数就越多。红色曲线对应的是通过指数回归得到的最佳拟合[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)。对于结构不良的材料，[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)是弯弯曲曲的，即不完全是指数型的。水平的水蓝色线条与要求的遗忘指数相对应，而垂直的绿色线条表示近似的[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)与要求的遗忘指数线相交的时间点。这个时间点决定了相关的 [R-系数](https://supermemo.guru/wiki/R-Factor)的大小，并间接决定了[最优间隔](https://supermemo.guru/wiki/Optimum_interval)的取值。对于第一次重复，[R-系数](https://supermemo.guru/wiki/R-Factor)与第一个[最优间隔](https://supermemo.guru/wiki/Optimum_interval)相对应。[O-系数](https://supermemo.guru/wiki/O-Factor)和 [R-系数](https://supermemo.guru/wiki/R-Factor)的值显示在图表的顶部。它们后面是用于绘制图表的重复案例的数量（即 21,303）。在学习过程的开始，没有重复的历史，也没有重复的数据来计算 [R-系数](https://supermemo.guru/wiki/R-Factor)。在你的第一个[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)绘制出来之前，需要一些时间。据此，射频矩阵的初始值取自一个低于平均水平的学生的模型。不使用平均学生的模型是因为从较差的学生参数向上收敛的速度比相反方向的收敛要快。显示在顶部的**偏差**参数告诉你负指数曲线对数据的拟合程度。偏差越小，拟合效果越好。偏差是以平方差的平均数的平方根计算的（如最小二乘法中所用）。

   [![SuperMemo: Exemplary 3-D graph of forgetting curves for A-Factor=3.6](https://supermemo.guru/images/thumb/5/52/AFactor_3D_Curve.jpg/800px-AFactor_3D_Curve.jpg)](https://supermemo.guru/wiki/File:AFactor_3D_Curve.jpg)

   > 图：单一条目难度和不同记忆稳定性水平下的遗忘曲线族的三维表示（对 U-系数进行归一化）。

   [![A cumulative normalized forgetting curve for all registered repetition cases in a single collection](https://supermemo.guru/images/thumb/2/21/Cumulative_forgetting_curve.jpg/800px-Cumulative_forgetting_curve.jpg)](https://supermemo.guru/wiki/File:Cumulative_forgetting_curve.jpg)

   > 图： 混合[复杂性](https://supermemo.guru/wiki/Complexity)与混合[稳定性](https://supermemo.guru/wiki/Stability)的学习材料的叠加[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)。该图是通过叠加 400 条遗忘曲线得到的，其归一化后的衰减常数为 0.003567，这相当于在呈现的时间跨度的 100% 时回忆率为 70%（即图中右边缘的 [R](https://supermemo.guru/wiki/Retrievability)=70%）。图中包括了 401,828 个重复的案例。单个曲线用黄色数据点表示。累积曲线由蓝色数据点表示，显示所有 400 条曲线的平均回忆率。圆圈的大小与数据样本的大小相对应。

8. 从遗忘曲线计算出 OF 矩阵：OF 矩阵是由 RF 矩阵推导出来的：

   1. 沿 RF 矩阵每一列的 [R-系数](https://supermemo.guru/wiki/R-Factor)下降的定点幂近似（定点对应于近似曲线通过 [A-系数](https://supermemo.guru/wiki/A-Factor)值的第二次重复），

2. 对于所有列，计算 D-系数，这个系数表示幂近似的衰减常数，

   3. D-系数在整个 RF 矩阵列中的变化的线性回归，以及

   4. 找出D-系数图中拟合最佳的直线，利用它们的斜率和截距，计算出整个 OF 矩阵。在这最后一步中使用的确切公式超出了本说明的范围。

   注意，OF 矩阵的第一行的计算方式有所不同。第一行对应从 RF 矩阵第一行得到的最优拟合指数曲线。每次重复后都会进行一遍上述流程。换句话说，一旦收集到新的遗忘曲线数据，理论上最佳的 OF 矩阵值就会被更新，即在重复期间，一旦当学生提供评分，说明回忆正确还是错误（即遗忘）（在[ SM-6 算法](https://supermemo.guru/wiki/Algorithm_SM-6) 中，必须使用单独的近似程序 Approximate 来寻找最契合的 OF 矩阵，而且重复时使用的 OF 矩阵可能与它的最优拟合值有很大差别）

9. **项目难度**：[A-系数](https://supermemo.guru/wiki/A-Factor)的初始值通过该项目的首次评分，以及首次评分与 [A-系数](https://supermemo.guru/wiki/A-Factor)的相关图（[G-AF 图](http://help.supermemo.org/wiki/Analysis#First_Grade_vs._A-Factor)）计算得出。该图在每次重复后被更新，同时会计算新的 [A-系数](https://supermemo.guru/wiki/A-Factor)近似值，并将其与项目的首次评分相关联。每次重复后，还会进一步计算真实的 [A-系数](https://supermemo.guru/wiki/A-Factor)值的近似值，综合运用评分、OF 矩阵和显示评分与预期遗忘指数对应关系的相关图（[FI-G 图](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index)）等。用于计算初始 [A-系数](https://supermemo.guru/wiki/A-Factor)的评分需经过归一化，即根据实际使用的间隔和目标为 10% 遗忘指数的最佳间隔之间的差异进行调整

10. **评分与预期遗忘指数的相关性**：FI-G 图在每次重复后，根据[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)和实际评分来更新。[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)可以很容易地从重复之间使用的间隔和从 OF 矩阵计算的[最优间隔](https://supermemo.guru/wiki/Optimum_interval)中得出。[预期遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#expected_forgetting_index)的值越高，评分就越低。从评分和 FI-G 图（见：**[工具](http://help.supermemo.org/wiki/Tools_menu)：[统计](http://help.supermemo.org/wiki/Tools_menu#Statistics)：[分析](http://help.supermemo.org/wiki/Analysis)：[图表](http://help.supermemo.org/wiki/Analysis#Graphs)**中的 [FI-G 图](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index)），我们可以计算出[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)，它相当于在假设的重复前阶段，对刚刚重复的条目的遗忘概率的重复后估计。由于遗忘和回忆的随机性，同一个条目可能被回忆，也可能不被回忆，这取决于大脑当前的整体认知状态；即使所有贡献突触的记忆强度和可检索性是/是相同的这样，我们就可以谈论一个刚刚被回忆（或未被回忆）的条目的重复前回忆概率。这个概率用[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)表示。

11. **计算 A-系数**：从（1）[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)，（2）间隔长度和（3）OF 矩阵，我们可以很容易地计算出 [A-系数](https://supermemo.guru/wiki/A-Factor)的最准确值。请注意，[A-系数](https://supermemo.guru/wiki/A-Factor)相当于 OF 矩阵的索引，而利用[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)，便能在 OF 矩阵找出一列，使得[最优间隔](https://supermemo.guru/wiki/Optimum_interval)相当于实际使用的间隔，该间隔已针对[估计遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#estimated_forgetting_index)距离[期望遗忘指数](http://help.supermemo.org/wiki/Forgetting_index#requested_forgetting_index)的偏差进行修正。在每次重复时，计算旧的 [A-系数](https://supermemo.guru/wiki/A-Factor)和新的 [A-系数](https://supermemo.guru/wiki/A-Factor)的估计值的加权平均。在计算新的最优重复间隔时，新得到的 [A-系数](https://supermemo.guru/wiki/A-Factor)被用于 OF 矩阵的索引

总结一下。重复的结果是计算出一套参数表征学生记忆：RF 矩阵，[G-AF 图](http://help.supermemo.org/wiki/Analysis#First_Grade_vs._A-Factor)，以及 [FI-G 图](http://help.supermemo.org/wiki/Analysis#Grade_vs._Forgetting_Index)。它们还用于计算各个项目的 [A-系数](https://supermemo.guru/wiki/A-Factor)，以刻画所学材料的难度。对 RF 矩阵进行平滑处理可得出 [OF 矩阵](https://supermemo.guru/wiki/OF_matrix)，并由此计算不同难度（[A-系数](https://supermemo.guru/wiki/A-Factor)），和适用不同重复次数的项目的最优重复间隔（或在第一次重复的情况下的[遗忘次数](https://supermemo.guru/wiki/Lapse)）。一开始，所有学生的记忆参数都按照水平中下的学生取值（比按照水平中等或中上的学生取值收敛得更快），而所有 [A-系数](https://supermemo.guru/wiki/A-Factor)都被假定为相等（未知）。