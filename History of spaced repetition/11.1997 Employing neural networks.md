# 1997: Employing neural networks

# 1997:使用神经网络

[TOC=2,5]

## Neural Networks: Budding interest

## 神经网络:萌芽中的兴趣

In the mid-1980s, I read Michael Arbib's "*Brains, Machines and Mathematics*". It consolidated my view of the brain as an efficient computing machine.

For anyone with an interest in how the brain works, and this is almost everyone, neural networks are naturally fascinating. While studying computer science (1985-1990), I gained a new, computational perspective of the brain and the neural networks. As neural networks have an uncanny capacity to do their own modelling, it may seem natural to employ them to study memory data to provide answers on how memory works. However, neural networks have one major shortcoming, they do not easily share their findings. It is a bit like the problem with the brain itself, it can do magic things and yet it is hard to say what is actually happening inside. It is fun to write neural network software, I dabbled in that in 1989. It is a bit less fun to see a neural network in action.

上世纪80年代中期，我读了迈克尔•阿尔比布(Michael Arbib)的《大脑、机器和数学》(*Brains, Machines and Mathematics*)。它巩固了我认为大脑是一台高效计算机器的观点。

对于任何对大脑如何工作感兴趣的人来说，神经网络自然是令人着迷的。在学习计算机科学(1985-1990)的过程中，我对大脑和神经网络有了一个新的、计算的视角。由于神经网络具有不可思议的建模能力，利用它们来研究记忆数据以提供记忆如何工作的答案似乎是很自然的事情。然而，神经网络有一个主要的缺点，他们不容易分享他们的发现。这有点像大脑本身的问题，它可以做一些神奇的事情，但很难说里面到底发生了什么。写神经网络软件很有趣，我在1989年就涉猎过。看到一个神经网络起作用就没那么有趣了。

The algebraic approach to [SuperMemo](https://supermemo.guru/wiki/SuperMemo) outstripped neural networks for two reasons: (1) my questions about memory always seemed too simple to involve neural networks, and (2) networks need data, which need learning, which needs an algorithm, which needs answering simple questions. In this chicken-and-egg race, my brain was always a step ahead of what I might figure out from available data with a neural network.

The superiority of the algebraic approach is obvious if you consider that the optimum interval can be found by just plotting a forgetting curve and employing regression to find the point where recall drops below 90%. This was even more extreme in my [1985 experiment](https://supermemo.guru/wiki/The_birthday_of_spaced_repetition:_July_31,_1985) where my "forgetting curve" was made of just 5 points. I was able to pick the one I just liked most. That was a pre-school exercise. No big guns needed.

In 1990, when working on the [model of intermittent learning](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula), I came closest to employing neural networks. After a 7-hour-long discussion with [Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski) on July 6, 1990, we concluded that a neural network could provide some answers. However, my computer was already churning data using algebraic hill-climbing methods. In essence, this is similar to feature extraction in neural networks. Once I got my answers, that motivation has been taken away. I did not need better computation. I needed better data.

[SuperMemo](https://supermemo.guru/wiki/SuperMemo)的代数方法超越了神经网络，原因有二:(1)我提出的关于记忆的问题似乎太简单，不可能涉及神经网络;(2)网络需要数据，需要学习;(2)网络需要算法;(3)网络需要回答简单的问题。在这场鸡生蛋还是蛋生鸡的竞赛中，我的大脑总是比我通过神经网络从现有数据中得出的结论领先一步。

代数方法的优势是显而易见的，如果你认为最优的区间可以通过绘制遗忘曲线和使用回归找到点，回忆下降到90%以下。这在我的[1985年实验](https://supermemo.guru/wiki/The_birthday_of_spaced_repetition:_July_31，_1985)中更为极端，我的“遗忘曲线”只有5个点。我可以选择一个我最喜欢的。那是一个学前训练。不需要什么大人物。

1990年，在研究[间歇学习模型](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula)时，我最接近于使用神经网络。1990年7月6日，在与[Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)进行了7小时的讨论后，我们得出结论:神经网络可以提供一些答案。然而，我的电脑已经在使用代数爬山法处理大量数据了。本质上，这类似于神经网络中的特征提取。一旦我得到了答案，这种动力就消失了。我不需要更好的计算。我需要更好的数据。

Nevertheless, in the mid-1990s, we had more and more questions about the adaptability of the algorithm, and the possibility of employing neural networks. Those questions were primarily raised by those who do not understand [SuperMemo](https://supermemo.guru/wiki/SuperMemo) much. The model behind SuperMemo is simple, the optimization tools are simple, and they work pretty well to our satisfaction. The very first computational approach, [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2), is used to this day. Its adoption has actually reached [millions](https://supermemo.guru/wiki/Exponential_adoption_of_spaced_repetition). Human dissatisfaction with memory usually comes from unreasonable expectations that are built via school [curricula](https://supermemo.guru/wiki/Curricula). Unhappiness also comes from our poor ability to [formulate knowledge for healthy consumption](https://supermemo.guru/wiki/20_rules). This last habit is also perpetuated by the push for [cramming](https://supermemo.guru/wiki/Cramming) that we bring from school. SuperMemo algorithms cannot remedy that dissatisfaction with learning. They have always performed well, and the last 30 years delivered progress that can be measured mathematically, but which does not easily translate into an increase in the [pleasure of learning](https://supermemo.guru/wiki/Pleasure_of_learning). To many users, neural networks seemed like a magic pill that could change things for the better.

然而，在20世纪90年代中期，我们对算法的适应性和使用神经网络的可能性提出了越来越多的问题。这些问题主要是由那些不懂的人提出的。[SuperMemo](https://supermemo.guru/wiki/SuperMemo)背后的模型很简单，优化工具也很简单，而且它们的工作效果也让我们很满意。第一个计算方法[Algorithm SM-2](https://supermemo.guru/wiki/algorithm_sm2)一直沿用至今。它的应用已经达到了[数百万](https://supermemo.guru/wiki/Exponential_adoption_of_spaced_repetition)次。人类对记忆的不满通常来自于通过学校[课程](https://supermemo.guru/wiki/)建立的不合理的期望。不快乐也来自于我们缺乏健康消费的知识(https://supermemo.guru/wiki/20_rules)。这最后一个习惯也是由我们从学校带来的[填塞](https://supermemo.guru/wiki/Cramming)推动的。SuperMemo算法无法弥补这种学习上的不足。它们一直表现良好，过去30年取得了可以用数学衡量的进步，但这并不容易转化为[学习的乐趣](https://supermemo.guru/wiki/Pleasure_of_learning)的增加。对许多用户来说，神经网络就像一粒神奇的药丸，可以让事情变得更好。

## Push for neural networks

## 推动神经网络

In the 1990s, mail to [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) often included hints that the neural network approach would be superior. Even a decade of use of [SuperMemo](https://supermemo.guru/wiki/SuperMemo) would not prevent a student from writing a set of false assertions:

在20世纪90年代，寄到[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)的邮件中经常包含神经网络方法更优越的暗示。即使使用[SuperMemo](https://supermemo.guru/wiki/SuperMemo)十年也不能阻止学生写出一组错误的断言:

> SuperMemo doesn't take different user abilities and needs into account. Instead, it assumes that every learner is a "bad learner". As such each learner will have the same repetition interval. Its underlying algorithm is hardwired, which might not be very efficient if you are a better/different learner. [...] Neural networks take into account that there exist very different types of learners who need different optimum repetition intervals. When reviewing new words and by "telling" the programme how well/bad they did the learner reveal more and more which type of learner they really are. After this feedback the programme is able to adapt and optimise the underlying repetition intervals if necessary
>
> SuperMemo没有考虑不同用户的能力和需求。相反，它假设每个学习者都是“糟糕的学习者”。因此，每个学习者将有相同的重复间隔。它的底层算法是硬连接的，如果你是一个更好的/不同的学习者，它可能不是很有效。[…神经网络考虑到存在非常不同类型的学习者，他们需要不同的最佳重复间隔。在复习新单词时，通过“告诉”节目这些单词的好坏，学习者会越来越多地揭示出他们到底是哪种类型的学习者。在这个反馈之后，如果有必要，程序能够调整和优化潜在的重复间隔

Those words indicate lack of understanding of [SuperMemo](https://supermemo.guru/wiki/SuperMemo). SuperMemo does not use a "bad student model". It only starts from shorter intervals before collecting first data about student's memory. The choice of shorter intervals comes from a faster convergence towards the optimum. In other words, SuperMemo adapts to individual students, and the "less than average student model" might be attributed to the starting point before any data is collected. Before training, neural network would also need to assume some model to make sure the scheduling is not entirely unpredictable.

这些话表明人们对[SuperMemo](https://supermemo.guru/wiki/SuperMemo)缺乏理解。SuperMemo并没有使用“坏学生模型”。在收集关于学生记忆的第一个数据之前，它只从更短的间隔开始。较短区间的选择来自于更快地向最优收敛。换句话说，SuperMemo适用于个别学生，“低于平均水平的学生模型”可能是在收集任何数据之前的起点。在训练之前，神经网络还需要假设某种模型，以确保调度不是完全不可预测的。

In SuperMemo, the average student model is used only as an initial condition in the process of finding the model of the actual student's memory.

In a finite-dimensional trajectory optimization, convergence is fastest for a good initial state guess. Although it is not the case in SuperMemo due to its simple 3-dimensional nature of the function of [optimum intervals](https://supermemo.guru/wiki/Optimum_interval), in general case, the search for solutions may fail and the optimization will not work. Unlike the univalent matrices used in older SuperMemos for research purposes, a neural network algorithm would produce chaos without pre-training. This is why prior learning data are used to update the average or less-than-average student model used in SuperMemo for the maximum speed of convergence.

在SuperMemo中，一般的学生模型只作为寻找实际学生记忆模型的初始条件。

在有限维轨迹优化中，对于一个好的初始状态猜测，收敛速度是最快的。虽然在SuperMemo中不是这样的，因为它的函数的简单的三维性质[最优区间](https://supermemo.guru/wiki/Optimum_interval)，在一般情况下，搜索解决方案可能会失败，优化不会工作。与以前用于研究目的的单价矩阵不同，神经网络算法在没有预先训练的情况下会产生混乱。这就是为什么使用先验学习数据来更新SuperMemo中使用的平均或低于平均的学生模型，以获得最大的收敛速度。

Note that this average student approach is even less significant in [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) due to the use of best-fit approximations for multiple parameters and functions in the learning process (e.g. item difficulty, stability increase function, etc.). This means that SuperMemo will always make the best of available data (using our current best knowledge of memory models).

The approximate shape of the [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve) has been known for over a century now (see: [Error of Ebbinghaus forgetting curve](https://supermemo.guru/wiki/Error_of_Ebbinghaus_forgetting_curve)). SuperMemo collects precise data on the shape of forgetting curves for [items](https://supermemo.guru/wiki/Item) of different [difficulty](https://supermemo.guru/wiki/Difficulty) and different memory [stability](https://supermemo.guru/wiki/Stability). From forgetting curves, SuperMemo easily derives the [optimum interval](https://supermemo.guru/wiki/Optimum_interval). The data comes from only one student and each repetition contributes to the precision of the computation. In other words, with every minute you spend with SuperMemo, the program knows you better and better. Moreover, it knows you well enough after a month or two. You never need to worry about the efficiency of the algorithm.

请注意，在[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)中，由于在学习过程中使用了多个参数和函数的最佳拟合近似(如项目难度、稳定性增加函数等)，这种平均的学生方法甚至更不重要。这意味着SuperMemo将会充分利用现有的数据(利用我们目前对内存模型的最佳了解)。

[遗忘曲线的大致形状](https://supermemo.guru/wiki/Forgetting_curve)到现在已经有一个多世纪的历史了(参见:[艾宾浩斯遗忘曲线的误差](https://supermemo.guru/wiki/Error_of_Ebbinghaus_forgetting_curve)。SuperMemo针对不同难度的[items](https://supermemo.guru/wiki/Item) 和不同[难度](https://supermemo.guru/wiki/Difficulty)的memory [stability](https://supermemo.guru/wiki/Stability)收集精确的遗忘曲线形状数据。从遗忘曲线，SuperMemo很容易得出[最优区间](https://supermemo.guru/wiki/Optimum_interval)。数据只来自一名学生，每一次重复都有助于提高计算的精度。换句话说，随着你在SuperMemo上花费的每一分钟，程序会越来越了解你。而且，它在一两个月后就对你很了解了。你永远不必担心算法的效率。

There is an aura of mystique around neural networks. They are supposed to reveal hidden properties of the studied phenomena. It is easy to forget that networks can fail easily when they are fed with wrong information or with some vital information missing. This was the case with the only functional neural network used in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition): [MemAid by David Calinski](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#David_Calinski_and_FullRecall).

The error in the design of MemAid network came from using Interval + Repetition Count on the input to represent the status of memory, while these two variables do not correspond with the [Stability](https://supermemo.guru/wiki/Stability) : [Retrievability](https://supermemo.guru/wiki/Retrievability) pair. Stability and Retrievability have been [proven necessary to represent the status of a long-term memory trace](https://supermemo.guru/wiki/Two_components_of_memory). In other words, the network does not get all the information it needs to compute the [optimum interval](https://supermemo.guru/wiki/Optimum_interval). A better design would code the entire [repetition history](https://supermemo.guru/wiki/Repetition_history), e.g. with the use of stability and retrievability variables. Full repetition history is needed to account for the [spacing effect](https://supermemo.guru/wiki/Spacing_effect) of massed presentation or a significant boost in stability for passing grades in delayed repetitions. Calinski's design would, however, meet basic requirements for learning in "optimum" intervals with few departures from the rules of spaced repetition (as much as [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)).

神经网络有一种神秘的光环。它们应该揭示所研究现象的隐藏特性。人们很容易忘记，当向网络提供错误信息或一些重要信息缺失时，网络很容易崩溃。这是在[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)中唯一使用的功能性神经网络: [MemAid by David Calinski](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#David_Calinski_and_FullRecall)。

MemAid网络的误差在设计来自使用间隔+重复依靠输入代表记忆的状态,而这两个变量不符合[稳定](https://supermemo.guru/wiki/Stability):[可恢复性](https://supermemo.guru/wiki/Retrievability)。稳定性和可检索性已经被证明是表示长期内存跟踪状态的必要条件(https://supermemo.guru/wiki/Two_components_of_memory)。换句话说，网络没有获得计算[最佳间隔]所需的所有信息(https://supermemo.guru/wiki/Optimum_interval)。一个更好的设计应该编码整个[重复历史](https://supermemo.guru/wiki/Repetition_history)，例如使用稳定性和可检索性变量。需要完整的重复历史记录来解释[间隔效应](https://supermemo.guru/wiki/Spacing_effect)的大量演示或在延迟重复中通过分数的稳定性的显著提高。然而，Calinski的设计将满足“最佳”间隔学习的基本要求，几乎不偏离间隔重复的规则(和[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)一样多)。

## Is SuperMemo inflexible?

## SuperMemo死板吗?

It is not true that SuperMemo is prejudiced while a neural network is not. Nothing prevents the optimization matrices in SuperMemo to depart from the memory model and produce an unexpected result. It is true that over years, with more and more knowledge of how memory works, the algorithm used in SuperMemo has been armed with restrictions and customized sub-algorithms. None of these were a result of a wild guess though. The progression of "prejudice" in SuperMemo algorithms is only a reflection of findings from the previous years. The same would inevitably affect any neural network implementation if it wanted to maximize its performance.

SuperMemo有偏见，而神经网络没有偏见，这是不正确的。没有什么能阻止SuperMemo中的优化矩阵脱离内存模型并产生意外结果。的确，多年来，随着对内存工作原理的了解越来越多，SuperMemo中使用的算法已经配备了限制和定制的子算法。但这些都不是胡乱猜测的结果。SuperMemo算法中“偏见”的发展只是前几年研究结果的反映。如果想要最大限度地提高神经网络的性能，这将不可避免地影响任何神经网络的实现。

It is also not true that the original pre-set values of optimization matrices in SuperMemo are a form of prejudice. These are an equivalent of pre-training in a neural network. A neural network that has not been pre-trained will also be slower to converge onto the optimum model. This is why SuperMemo is "pre-trained" with the model of an average student.

The rate of interval increase is determined by the matrix of optimum intervals and is by no means constant. Moreover, the matrix of optimum intervals changes in time depending on the user's performance. You may have an impression of a fixed or rigid algorithm only after months or years of use (the speed of change is inversely proportional to the available learning data). This convergence reflects the invariability of the human memory system. It does not matter if you use the algebraic or neural approach to the optimization problem. In the end, you will arrive at the spaced repetition function that reflects the true properties of your memory. In that light, the speed of convergence should be held as a benchmark of the algorithm's quality. In other words, the faster the interval function becomes "fixed", the better.

在SuperMemo中优化矩阵的原始预置值也不是偏见的一种形式。这相当于神经网络中的预训练。未经过预训练的神经网络也会较慢地收敛到最优模型。这就是为什么SuperMemo会以普通学生的模式进行“预培训”。

区间增长率是由最优区间矩阵决定的，决不是常数。此外，最佳间隔矩阵随时间的变化取决于用户的性能。只有在使用了几个月或几年之后，您才会对固定的或严格的算法产生印象(变化的速度与可用的学习数据成反比)。这种趋同反映了人类记忆系统的不变性。不管你用代数方法还是神经方法来求解最优化问题。最后，你会得到反映你记忆真实性质的间隔重复函数。因此，收敛速度应该作为算法质量的一个基准。换句话说，区间函数变得“固定”越快越好。

Finally, there is another area where neural networks must either use the existing knowledge of memory models (i.e. carry a dose of prejudice) or lose out on efficiency. The experimental neural network SuperMemo, MemAid, as well as FullRecall have all exhibited an inherent weakness. The network achieves the stability when the intervals produce a desired effect (e.g. specific level of the measured forgetting index). Each time the network departs from the optimum model it is fed with a heuristic guess on the value of the optimum interval depending on the grade scored during repetitions (e.g. grade=5 would correspond with [130% of the optimum interval in SuperMemo NN](http://super-memory.com/english/ol/nn_train.htm) or [120% in MemAid](http://memaid.sourceforge.net/docs/ann.html)). The algebraic SuperMemo, on the other hand, can compute a difficulty estimate, use the accurate retention measurement, and produce an accurate adjustment of the value of the [stability increase](https://supermemo.guru/wiki/Stability_increase) matrix. In other words, it does not guess on the [optimal interval](https://supermemo.guru/wiki/Optimal_interval). It computes its exact value for that particular repetition. The adjustments to the memory matrices are weighted and produce a stable non-oscillating convergence. In other words, it is the memory model that makes it possible to eliminate the guess factor. With that respect, the algebraic SuperMemo is less prejudiced than the neural network SuperMemo.

最后，在另一个领域，神经网络必须要么利用现有的记忆模型知识(即带有偏见)，要么失去效率。实验神经网络SuperMemo、MemAid以及FullRecall都显示出了一个固有的弱点。当间隔产生期望的效果时(如被测遗忘指数的具体水平)，网络达到稳定。每次网络偏离最优模型与启发式猜测美联储的价值最优区间根据年级得分在重复(比如= 5年级将符合[130%的最优区间SuperMemo NN](http://super-memory.com/english/ol/nn_train.htm)或MemAid [120%](http://memaid.sourceforge.net/docs/ann.html))。另一方面，代数SuperMemo可以计算一个难度估计，使用精确的保留度度量，并对[stability increase](https://supermemo.guru/wiki/Stability_increase)的值进行精确调整。换句话说，它不会猜测[最佳间隔](https://supermemo.guru/wiki/Optimal_interval)。它为特定的重复计算它的确切值。对存储矩阵进行加权调整，得到一个稳定的非振荡收敛。换句话说，正是内存模型使得消除猜测因素成为可能。在这方面，代数的超级备忘录比神经网络的超级备忘录更少偏见。

## Futility of fine-tuning the spaced repetition algorithm

## 微调间隔重复算法是徒劳的

[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) is a major step forward, however, many users will not notice the improvement and stick with the older algorithms. This perception problem led to the "[SM3+ myth](https://supermemo.guru/wiki/SM3%2B_myth)", which I tried to dispel in this [article](https://supermemo.guru/wiki/First_fast-converging_spaced_repetition_algorithm:_Algorithm_SM-5). At the same time, the value of the new algorithm for further progress in research is astronomical. In other words, there is a big dissonance between practical needs and theoretical needs. My words in an interview for Enter, 1994, still ring true:

[算法SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)是一个重要的进步，然而，许多用户不会注意到改进，并坚持使用旧的算法。这个感知问题导致了“[SM3+神话](https://supermemo.guru/wiki/SM3%2B_myth)”(https://supermemo.guru/wiki/First_fast-converging_spaced_repetition_algorithm: _algorithm_mc -5)。同时，新算法的价值对于进一步的研究进展是天文数字。换句话说，实践需求和理论需求之间存在很大的不协调。我在1994年Enter的一次采访中说过的话，现在听起来仍然正确:

> We have already seen that evolution speaks for SuperMemo, findings in the field of psychology coincide with the method, and that facts of molecular biology and conclusions coming from Wozniak's model seem to go hand in hand. Here is the time to see how the described mechanisms have been put to work in the program itself. In the course of repetitions, SuperMemo plots the forgetting curve for the student and schedules the repetition at the moment where the retention, i.e. proportion of remembered knowledge, drops to a previously defined level. In other words, SuperMemo checks how much you remember after a week and if you remember less than desired it asks you to make repetitions in intervals less than one week long. Otherwise, it checks the retention after a longer period and increases the intervals accordingly. A little kink to this simple picture comes from the fact that items of different difficulty have to be repeated at different intervals, and that the intervals increase as the learning process proceeds. Moreover, the optimum inter-repetition intervals have to be known for an average individual, and these must be used before the program can collect data about the real student. There must be obviously the whole mathematical apparatus involved to put the whole machinery at work. All in all, Wozniak says that there have been at least 30 days in his life when he had an impression that the algorithms used in SuperMemo have significantly been upgraded. Each of the cases seemed to be a major breakthrough. The whole development process was just a long succession of trials and errors, testing, improving, implementing new ideas, etc. Unfortunately, those good days are over. There have not been any breakthrough improvement to the algorithm since 1991. Some comfort may come from the fact that since then the software started developing rapidly providing the user with new options and solutions. Can SuperMemo then be yet better, faster, more effective? Wozniak is pessimistic. Any further fine-tuning of the algorithms, applying artificial intelligence or neural networks would be drowned in the noise of interference. After all, we do not learn in isolation from the world. When the program schedules the next repetition in 365 days, and the fact is recalled by chance at an earlier time, SuperMemo has no way of knowing about the accidental recollection and will execute the repetition at the previously planned moment. This is not optimal, but it cannot be remedied by improving the algorithm. Improving SuperMemo now is like fine tuning a radio receiver in a noisy car assembly hall. The guys at SuperMemo World are now less focused on science. In their view, after the scientific invention, the time has come for the social invention of SuperMemo.
>
> 我们已经看到，进化为SuperMemo说话，心理学领域的发现与方法一致，分子生物学的事实与沃兹尼亚克的模型得出的结论似乎是相辅相成的。现在是时候看看所描述的机制是如何在程序本身中发挥作用的。在重复的过程中，SuperMemo为学生绘制了遗忘曲线，并在记忆的比例，即记忆的知识下降到之前定义的水平时安排了重复。换句话说，SuperMemo会检查你一周后记住了多少，如果你记得的比期望的少，它会要求你每隔不到一周重复一次。否则，它会在较长一段时间后检查保留率，并相应地增加时间间隔。这个简单的图片有一点奇怪，因为不同难度的项目必须以不同的间隔重复，而且间隔随着学习过程的进行而增加。此外，对于一个普通的个体来说，最佳的重复间隔必须是已知的，并且在程序收集真实学生的数据之前必须使用这些间隔。显然，要使整个机器运转起来，必须涉及整个数学仪器。总而言之，沃兹尼亚克说，在他的一生中，至少有30天的时间里，他觉得SuperMemo中使用的算法有了显著的升级。每一个案例似乎都是一个重大突破。整个开发过程就是一长串的试验和错误、测试、改进、实现新思想等等。不幸的是，那些好日子已经过去了。自1991年以来，该算法没有任何突破性的改进。从那时起，软件开始快速开发，为用户提供了新的选择和解决方案，这可能会让人感到些许安慰。那么SuperMemo还能做得更好、更快、更有效吗?沃兹尼亚克是悲观的。任何对算法的进一步微调，应用人工智能或神经网络，都将淹没在干扰的噪音中。毕竟，我们不能孤立地学习。当程序在365天内安排下一次重复，并且这个事实在更早的时间被偶然回忆起，SuperMemo无法知道这个偶然的回忆，它将在之前计划的时刻执行重复。这不是最优的，但是不能通过改进算法来弥补。现在改进SuperMemo就像在嘈杂的汽车装配大厅里微调收音机一样。SuperMemo World的人现在不那么关注科学了。在他们看来，在科学发明之后，社会发明超级备忘录的时代已经到来。

## Dreger's Neural Network Project

## Dreger的神经网络项目

On May 20, 1997, my net buddy from the pre-web [BBS](https://en.wikipedia.org/wiki/Bulletin_board_system) era, Bartek Dreger, came up with a great idea. He would also write his Master's Thesis about SuperMemo at Institute of Computer Science at Poznan University of Technology. That would be 8 years after my [own](https://supermemo.guru/wiki/Master's_Thesis), except he would use neural networks to see how they performed. Despite being nearly two decades younger, his plan was to try this project in the same great Weglarz operation research team I mention often elsewhere in this text. As early as in 1990, Dr Nawrocki came up with the idea to use neural networks to improve SuperMemo. The great mind of Prof. Roman Slowinski was to be the supervisor. This could really work.

1997年5月20日，我的网络伙伴Bartek Dreger提出了一个好主意。他还将在波兹南理工大学计算机科学研究所(Institute of Computer Science at Poznan University of Technology)撰写关于SuperMemo的硕士论文。这比我的论文晚了8年(https://supermemo.guru/wiki/Master’s thesis)，只不过他会用神经网络来观察它们的表现。尽管他比我年轻将近20岁，但他的计划是在我在本文其他地方经常提到的Weglarz运营研究团队中尝试这个项目。早在1990年，Nawrocki博士就提出了利用神经网络改进SuperMemo的想法。罗曼·斯洛文斯基教授的伟大思想将成为导师。这真的有用。

By June 1997, another of my net buddies, Piotr Wierzejewski, joined the project. Then 3 more computer science students climbed aboard. It was a lovely team of five young brains with a combined age of 100. Soon the project was extended by the idea of on-line SuperMemo nicknamed: WebSorb (for the absorption of knowledge from the web). As it often happens in enthusiastic young teams, we started putting too much on the plate, and in the end, only a fraction of the goals has been attained. Only the on-line SuperMemo idea kept evolving and branching out in a meandering fashion with several mini-projects born and dying (e.g. [e-SuperMemo](http://super-memory.com/archive/english/ol/e-supermemo.htm), Quizer, Super-Memorizer, Memorathoner, etc.) until the emergence of [3GEMs](http://super-memory.com/archive/english/company/3gems.htm) that became [supermemo.net](https://supermemo.guru/wiki/SuperMemo.com) that ultimately evolved into today's [supermemo.com](http://supermemo.com/).

1997年6月，我的另一位网友Piotr Wierzejewski加入了这个项目。然后又有3名计算机专业的学生上了飞机。这是一个可爱的团队，5个年轻的大脑，年龄加起来有100岁。很快，这个项目被一个叫做“网上超级备忘录”的概念所扩展:“网上超级备忘录”(即从网上吸收知识)。就像在充满激情的年轻团队中经常发生的那样，我们开始把太多的精力放在工作上，最后，只有一小部分的目标实现了。只有在线SuperMemo理念不断发展和拓展蜿蜒的方式有一些小型项目出生和死亡(例如e-SuperMemo (http://super-memory.com/archive/english/ol/e-supermemo.htm),测试,Super-Memorizer, Memorathoner,等等)到[3GEMs](http://super-memory.com/archive/english/company/3gems.htm)的出现,成为[supermemo.net](https://supermemo.guru/wiki/SuperMemo.com),最终演变成今天的[supermemo.com](http://supermemo.com/)。

The greatest advantage of youth in similar projects is creativity and passion. The greatest obstacle is schooling, and later, other obligations, including having children. This fantastic brain trust fell victim to the ages old problem of school: converting a project born in passion into a project that became a school chore with deadlines, reports, tests, exams, and grades. As explained [here](https://supermemo.guru/wiki/SuperMemo_1.0_for_DOS_(1987)), SuperMemo was also born in that risky school environment. The key to success is the fight for freedom. Bondage destroys passions. The idea of [SuperMemo](https://supermemo.guru/wiki/SuperMemo) survived the pressure of schooling because of my [push for educational freedom](https://supermemo.guru/wiki/How_I_invented_perfect_schooling).

在类似的项目中，年轻人最大的优势是创造力和激情。最大的障碍是上学，然后是其他义务，包括生儿育女。这个奇妙的智囊团成了学校老问题的牺牲品:把一个在激情中诞生的项目变成一个有截止日期、报告、测试、考试和分数的学校杂务。正如所解释的[那样](https://supermemo.guru/wiki/SuperMemo_1.0_for_DOS_(1987))， SuperMemo也是在这种危险的学校环境中诞生的。成功的关键是为自由而战。束缚了激情。[SuperMemo](https://supermemo.guru/wiki/SuperMemo)经受住了学校教育的压力，因为我[推动教育自由](https://supermemo.guru/wiki/how_i_invented_perfect_schools)。

## Neural Network SuperMemo : Why memory model is essential for SuperMemo algorithms

## 神经网络SuperMemo:为什么记忆模型是超级备忘录算法的关键

Feature extraction proposed for [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) neural networks is based on a well-proven existence of two components of long-term memory described [here](https://supermemo.guru/wiki/Two_component_model_of_memory).

[The two memory variables](https://supermemo.guru/wiki/Two_component_model_of_memory) are sufficient to represent the status of an [atomic memory trace](https://supermemo.guru/wiki/Complexity) in learning. Those variables make it possible to compute [optimum intervals](https://supermemo.guru/wiki/Optimum_interval), and account for the [spacing effect](https://supermemo.guru/wiki/Spacing_effect). The function of the [increase in memory stability](https://supermemo.guru/wiki/Stability_increase) for delayed repetitions is also known. For those reasons, a simple optimization algorithm makes it easy to determine optimum repetition spacing in [SuperMemo](https://supermemo.guru/wiki/SuperMemo). A neural network would need to code the full repetition history for each item and the most obvious coding choices are memory [stability](https://supermemo.guru/wiki/Stability) (S) and memory [retrievability](https://supermemo.guru/wiki/Retrievability) (R). In other words, the same basic assumptions must underlie the design of repetition spacing algorithms whether they are algebraic or neural. Needless to say, the algebraic solution is easy and fast. It converges fast. It requires no pre-training (memory model is encapsulated in the [matrix of optimum intervals](https://supermemo.guru/wiki/OF_matrix) or the [matrix of stability increase](https://supermemo.guru/wiki/Stability_increase)).

为[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)提出的特征提取神经网络是基于长期记忆的两个组件的充分证明存在的描述[这里](https://supermemo.guru/wiki/Two_component_model_of_memory)。

[这两个内存变量](https://supermemo.guru/wiki/Two_component_model_of_memory)足以表示[原子内存跟踪](https://supermemo.guru/wiki/Complexity)在学习中的状态。这些变量使计算[最佳间隔](https://supermemo.guru/wiki/Optimum_interval)成为可能，并解释[间隔效应](https://supermemo.guru/wiki/Spacing_effect)。我们还知道延迟重复的[增加记忆稳定性](https://supermemo.guru/wiki/Stability_increase)的作用。基于这些原因，一个简单的优化算法可以很容易地确定[SuperMemo](https://supermemo.guru/wiki/SuperMemo)中的最佳重复间距。神经网络需要代码的完整重复历史和最明显的编码每一项选择是内存[稳定](https://supermemo.guru/wiki/Stability) (S)和内存[可恢复性](https://supermemo.guru/wiki/Retrievability) (R)。换句话说,相同的基本假设构成的设计必须重复间隔算法是否代数或神经。不用说，代数解既简单又快速。它是收敛快。它不需要预先训练(记忆模型封装在[最佳间隔矩阵](https://supermemo.guru/wiki/OF_matrix)或[稳定性增加矩阵](https://supermemo.guru/wiki/Stability_increase))。

A neural network working with full repetition histories will produce the same outcomes as a hill-climbing algorithm employed in building [stability](https://supermemo.guru/wiki/Stability) of memory. Algorithmic hill-climbing is simply a better/faster tool for the job. It will carry the same limitations as neural networks, i.e. the answers will be as good as the questions posed.

一个具有完整重复历史的神经网络将产生与爬山算法相同的结果，后者用于构建记忆的[稳定性](https://supermemo.guru/wiki/Stability)。算法爬山只是一个更好/更快的工作工具。它将具有与神经网络相同的局限性，即答案将与提出的问题一样好。

## Neural Network SuperMemo: Design

## 神经网络SuperMemo:设计

With Bartek Dreger we designed a simple ANN system for handling the [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) problem (Dec 1997). Note that this project would not be possible without the expertise of Dr Krzysztof Krawiec who was helpful in polishing the design:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

The repetition spacing problem consists in computing optimum inter-repetition intervals in the process of human learning. The intervals are computed for individual pieces of information (later called items) and for a given individual. The entire input data are grades obtained by the student in repetitions of items in the learning process. This problem has until now be most effectively solved by means of a successive series of algorithms known commercially as     , Poland. Wozniak’s[model of memory](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory)used in developing the most recent version of the algorithm () cannot be considered as the ultimate algebraic description of human long-term memory. Most notably, the relationship between the complexity of the synaptic pattern and item difficulty is not well understood. More light on this relationship might be shed once a neural network is employed to provide adequate mapping between the memory status, grading and the item difficulty.

Using Wozniak’s model of two components of long-term memory we postulate that the following neural network solution might result in fast convergence and high repetition spacing accuracy.

与Bartek Dreger合作，我们设计了一个简单的ANN系统来处理[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)问题(1997年12月)。请注意，如果没有Krzysztof Krawiec博士的专业知识，这个项目是不可能完成的。

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

重复间隔问题是指在人类学习过程中计算最优的重复间隔。间隔是为单个信息片段(后来称为项目)和给定个体计算的。整个输入的数据都是学生在学习过程中通过项目的重复得到的分数。到目前为止，这个问题最有效的解决方法是一系列在商业上被称为“波兰”的连续算法。Wozniak的[记忆模型](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory)用于开发最新版本的算法()，不能被认为是人类长期记忆的最终代数描述。最值得注意的是，突触模式的复杂性和项目难度之间的关系还没有被很好地理解。一旦使用神经网络在记忆状态、评分和试题难度之间提供足够的映射，这种关系可能会得到更多的了解。

利用沃兹尼亚克的长期记忆两部分模型，我们假设如下的神经网络解决方案可能会导致快速收敛和高重复间隔精度。

The two memory variables needed to describe the state of a given engram are retrievability (R) and stability (S) of memory ([Wozniak, Gorzelanczyk, Murakowski, 1995](http://super-memory.com/english/2vm.htm)). The following equation relates R and S:

描述给定engram状态所需的两个内存变量是可检索性(R)和内存稳定性(S) ([Wozniak, Gorzelanczyk, Murakowski, 1995](http://hypermemory.com/english/2vm.htm))。R和S的关系式如下:

> (1) R=e-k/S*t
>
> where:
>
> - k is a constant k是常数
> - t is time t是时间

By using Eqn (1) we conclude about changes of retrievability in time at a given stability, as well as we can determine the optimum inter-repetition interval for given stability and given forgetting index.

利用Eqn(1)得出了在给定稳定性下可检索性随时间的变化，并确定了给定稳定性下的最佳重复间隔和给定遗忘指数。

The exact algebraic shape of the function that describes the change of stability upon a repetition is not known. However, experimental data indicate that stability usually increases from 1.3 to 3 times for properly timed repetitions and depends on item difficulty (the greater the difficulty the lower the increase). By providing the approximation of the optimum repetition spacing taken from experimental data as produced by optimization matrices of [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8), the neural network can be pre-trained to compute the [stability function](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula):

描述重复时稳定性变化的函数的确切的代数形状是未知的。然而，实验数据表明，在适当的时间内，稳定性通常会从1.3倍增加到3倍，这取决于项目难度(难度越大，增加的难度越低)。通过提供最佳的近似重复间隔从实验数据由优化矩阵的[算法SM-8](https://supermemo.guru/wiki/Algorithm_SM-8),可以pre-trained神经网络计算[稳定的功能](https://supermemo.guru/wiki/Search_for_a_universal_memory_formula):

> (2) Si+1=fs(R,Si,D,G)
>
> where:
>
> - Si is stability after the i-th repetition
> - R is retrievability before repetition
> - D is item difficulty
> - G is grade given in the i-th repetition
>
> (2) Si+1=fs(R,Si,D,G)
>
> 上式中：
>
> - Si是第i次重复后的稳定性
> - R是重复之前的可检索性
>
> - D是项目难度
>
> - G是第i次重复的分数

The stability function is the first function to be determined by the neural network. The second one is the item difficulty function with analogous input parameters:

稳定性函数是神经网络要确定的第一个函数。第二个是输入参数类似的项难度函数:

> (3) Di+1=fd(R,S,Di,G)
>
> where:
>
> - Di is item difficulty approximation after the i-th repetition
> - R is retrievability before repetition
> - S is stability after the i-th repetition
> - G is grade given in the i-th repetition
>
> (3) Di+1=fd(R,S,Di,G)
>
> 上式中：
>
> - Di是第i次重复后的项目难度近似值
> - R是重复之前的可检索性
>
> - S是第i次重复后的稳定性
>
> - G是第i次重复的分数

Consequently, a neural network with four inputs (D, R, S and G) and two outputs (S and D) can be used to encapsulate the entire knowledge needed to compute inter-repetition intervals (see: [Implementation of the repetition spacing neural network](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Neural_Network_SuperMemo:_Implementation)).

因此,神经网络有四个输入(D, R, S, G)和两个输出(S和D)可以用来封装整个知识需要计算inter-repetition间隔(见:[实施重复间隔神经网络](https://supermemo.guru/wiki/History_of_spaced_repetition_(印刷)# Neural_Network_SuperMemo: _Implementation))。

The following approach will be taken in order to verify the feasibility of the aforementioned approach:

将采取下列办法来证实上述办法的可行性:

1. [Pretraining](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Pretraining) of the neural network will be done on the basis of approximated S and D functions derived from functions used in [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) and experimental data collected thereof
2. Such a pretrained network will be implemented as a [SuperMemo Plug-In DLL](http://super-memory.com/archive/english/algplug.htm) that will replace standard [sm8opt.dll](http://super-memory.com/english/sm8opt.htm) used by SuperMemo 8 for Windows. The teaching of the network will continue in a real learning process in alpha testing of the neural network DLL. A procedure designed specifically for the purpose of the experiment will be used to provide cumulative results and a resultant neural network. The procedure will use neural networks used in alpha testing for training the network that will take part in beta-testing. The alpha-testing networks will be fed with a matrix of input parameters and their output will be used in as training data for the resultant network
3. In the last step, beta-testing of the neural network will be open to all volunteers over the Internet directly from the SuperMemo Website. The volunteers will only be asked to submit their resultant networks for the final stage of the experiment in which the ultimate network will be developed. Again, the beta-testing networks will all be used to train the resultant network. Future users of neural network SuperMemo (if the project appears successful) will obtain a network with a fair understanding of the human memory and able to further refine its reactions to the interference of the learning process with day-to-day activities of a particular student and particular study material.

1. 神经网络的[预训练](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#预训练)将基于[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)中使用的函数的近似S和D函数及其收集的实验数据

2. 这样一个预先训练好的网络将被实现为一个[SuperMemo插件DLL](http://super-memory.com/archive/english/algplug.htm)，它将取代SuperMemo 8用于Windows的标准[sm8opt.dll](http://super-memory.com/english/sm8opt.htm)。在神经网络DLL的alpha测试中，网络的教学将继续在真实的学习过程中进行。一个专门为实验目的设计的程序将被用来提供累积的结果和一个合成的神经网络。该程序将使用用于阿尔法测试的神经网络来训练将参与贝塔测试的网络。阿尔法测试网络将得到输入参数矩阵，其输出将作为最终网络的训练数据

3. 在最后一步，神经网络的beta测试将直接从SuperMemo网站向所有志愿者开放。志愿者只被要求在实验的最后阶段提交他们的合成网络，最终网络将被开发出来。同样，所有的beta测试网络都将用于训练最终的网络。神经网络SuperMemo的未来用户(如果该项目看来成功的话)将获得一个对人类记忆有公平理解的网络，并能够进一步细化其对学习过程干扰特定学生和特定学习材料的日常活动的反应。

The major problem in all spacing algorithms is the delay between comparing the output of the function of optimum intervals with the result of applying a given inter-repetition interval in practise. On each repetition, the state of the network from the previous repetition must be remembered in order to generate the new state of the network. In practise, this equates to storing an enormous number of network states in-between repetitions.

所有间隔算法的主要问题是，在实际应用中，将最优间隔函数的输出结果与给定的重复间隔的结果进行比较存在延迟。在每次重复时，必须记住先前重复的网络状态，以便生成网络的新状态。在实践中，这相当于在重复之间存储了大量的网络状态。

Luckily, Wozniak’s model implies that functions S and D are time-independent (interestingly, they are also likely to be user-independent!); therefore, the following approach may be taken for simplifying the procedure:

幸运的是，Wozniak的模型暗示了函数S和D是与时间无关的(有趣的是，它们也可能是与用户无关的!);因此，可以采取下列办法来简化程序:

|         Time moment         |      T1       |          T2           |          T3           |
| :-------------------------: | :-----------: | :-------------------: | :-------------------: |
|          Decision           | I1N1O1=N1(I1) |     I2N2O2=N2(I2)     |     I3N3O3=N3(I3)     |
| Result of previous decision |               |     O*1E1=O*1-O1      |     O*2E2=O*2-O2      |
|   Evaluation for teaching   |               | O'1=N2(I1)E'1=O*1-O'1 | O'2=N3(I2)E'2=O*2-O'2 |

Where:

- Ei is an Error bound with Oi (see [error correction for memory stability](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Stability) and [error correction for item difficulty](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Difficulty))
- E'i is an Error bound with O'i
- Ii are input data at Ti
- Ni is the network state at Ti
- Oi is an output decision of Ni being given Ii, that is the decision after i-th repetition made at Ti
- O*i is an optimum output decision, that should be obtained at Ti instead of Oi; it can be computed from the grade and Oi (the grade indicates how Oi should have changed to obtain better approximation)
- O'i is an output decision of Ni+1 given Ii, that is the decision after i-th repetition that would be made at Ti+1
- Ti is time of the i-th repetition of a given item

上表中：

- Ei是与Oi绑定的错误(参见[内存稳定性错误更正](https://supermemo.guru/wiki/History_of_spaced_repetition_(打印)#稳定性错误更正)和[项目难度错误更正](https://supermemo.guru/wiki/History_of_spaced_repetition_(打印)#难度错误更正))

- E'i是O'i的误差界

- Ii是Ti的输入数据

- Ni是Ti处的网络状态

- Oi是一个输出决定的Ni被给予Ii，这是后i重复在Ti的决定

- O*i是最优的输出决策，应该在Ti而不是Oi时获得;它可以从年级和Oi中计算出来(年级表示Oi应该如何变化以获得更好的近似值)

- O'i是一个输出决定的Ni+1给定的Ii，这是第i次重复后的决定，将在Ti+1

- Ti是某一特定项目第i次重复的时间



The above approach requires only Ii-1 to be stored for each item between repetitions taking place at Ti-1 and Ti with substantial saving to the amount of data stored during the learning process (E'i is as valuable for training as Ei). This way the proposed solution is comparable for its space complexity with the [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)! Only one (current) state of the neural network has to be remembered throughout the process.

对于Ti-1和Ti之间的重复，上述方法只需要存储Ii-1，从而大大节省了在学习过程中存储的数据量(E'i对于培训的价值与Ei相同)。通过这种方式，我们提出的解决方案在空间复杂度上可以与[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)相媲美!整个过程中只需要记住神经网络的一个(当前)状态。

These are the present implementation assumptions for the discussed project:

- neural network: unidirectional, layered, with resilient back-propagation; an input layer with four neurons, an output layer with two neurons, and two hidden layers (15 neurons each)

- item difficulty interpretation: same as in [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8), i.e. defined by [A-Factor](https://supermemo.guru/wiki/A-Factor)
- each item stores: Last repetition date, [Stability](https://supermemo.guru/wiki/Stability) (at last repetition), [Retrievability](https://supermemo.guru/wiki/Retrievability) (at last repetition), [Item difficulty](https://supermemo.guru/wiki/Complexity), Last grade
- default [forgetting index](https://supermemo.guru/wiki/Forgetting_index): 10%
- [network DLL input](http://super-memory.com/archive/english/algplug.htm) (at each repetition): item number and the current grade
- [network DLL output](http://super-memory.com/archive/english/algplug.htm) (at each repetition): next repetition date
- neural network DLL implementation language: C++
- neural network DLL shell, SuperMemo 98 for Windows (same as the 32-bit [SM8OPT.DLL](http://super-memory.com/english/sm8opt.htm) shell)

这些是所讨论项目目前的执行假设:

- -神经网络:单向，分层，有弹性的反向传播;一个有四个神经元的输入层，一个有两个神经元的输出层和两个隐藏层(每个15个神经元)
- 项目难度解释:与[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)相同，即由[A-Factor](https://supermemo.guru/wiki/A-Factor)定义。
- 每个项目存储:最后重复日期，[稳定性](https://supermemo.guru/wiki/Stability)(最后重复)，[可检索性)](https://supermemo.guru/wiki/Retrievability)(最后重复)，(项目难度)(https://supermemo.guru/wiki/Complexity)，最后等级
- 默认[遗忘索引](https://supermemo.guru/wiki/Forgetting_index): 10%
- [网络DLL输入](http://super-memory.com/archive/english/algplug.htm)(每次重复时):项目编号和当前等级
- [网络DLL输出](http://super-memory.com/archive/english/algplug.htm)(每次重复时):下次重复日期
- 神经网络DLL实现语言:c++
- 神经网络DLL shell, SuperMemo 98 for Windows(与32位[SM8OPT.DLL](http://super-memory.com/english/sm8opt.htm) shell相同)

## Neural Network SuperMemo: Implementation

## 神经网络SuperMemo:实现

The network has practically been given the [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) algorithm on a silver platter. Its only role would be to fine-tune the performance over time. This is exactly what all [SuperMemo](https://supermemo.guru/wiki/SuperMemo) algorithms do as of [Algorithm SM-5](https://supermemo.guru/wiki/Algorithm_SM-5). In that sense, the design did not ask the network for a discovery. It asked for improvements upon the discovery. The model was wired in into the design.

这个网络实际上已经被赋予了[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)算法。它唯一的作用是随着时间的推移对性能进行微调。这正是所有[SuperMemo](https://supermemo.guru/wiki/SuperMemo)算法在[Algorithm SM-5](https://supermemo.guru/wiki/Algorithm_SM-5)中所做的。从这个意义上说，设计并没有要求网络进行发现。它要求改进这一发现。模型与设计紧密相连。

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

档案警告:为什么使用literal archives?

**Basic assumption** **基本猜测**

The state of memory will be described with only two variables: retrievability (R) and stability (S) ([Wozniak, Gorzelanczyk, Murakowski, 1995](http://super-memory.com/english/2vm.htm)). The following equation relates R and S:

只有两个变量可以描述记忆状态:可检索性(R)和稳定性(S) ([Wozniak, Gorzelanczyk, Murakowski, 1995](http://supermemory.com/english/2vm.htm))。R和S的关系式如下:

> (1) R=e-k/S*t
>
> where:
>
> - k is a constant
> - t is time
>
> (1) R=e-k/S*t
>
> 上式中：
>
> - k是常数
> - t是时间

For simplicity, we will set k=1 to univocally define stability.

为了简单起见，我们将k=1设为单独定义稳定性。

**Input and output** **输入和输出**

The following functions are to be determined by the network:

以下功能由网络决定:

> (2) Si+1=fs(R, Si, D, G)
>
> (3) Di+1=fd(R, S, Di, G)

The neural network is supposed to generate stability (S) and item difficulty (D) on the output given R, S, D and G on the input:

假设输入R、S、D、G，神经网络对输出产生稳定性(S)和项难度(D):

> (4) (Ri, Si, Di, Gi) => (Di+1,Si+1)
>
> where:
>
> - Ri is retrievability before the i-th repetition
> - Si is stability before the i-th repetition
> - Si+1 is stability after the i-th repetition
> - Di is item difficulty before the i-th repetition
> - Di+1 is item difficulty after the i-th repetition
> - Gi is grade given in the i-th repetition
>
> 上式中：
>
> - Ri是第i次重复之前的可检索性
>
> - Si是第i次重复之前的稳定性
> - Si+1是第i次重复后的稳定性
> - Di是第i次重复之前的项目难度
> - Di+1是第i次重复后的项目难度
> - Gi是在第i次重复中给出的分数

**Error correction for difficulty D** **难度D的错误更正**

Target difficulty will be defined as in [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) as the ratio between second and first intervals. The [neural network plug-in](http://super-memory.com/archive/english/algplug.htm) (NN.DLL) will record this value for all individual items and use it in training the network:

目标难度将被定义为[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)中第二和第一间隔的比值。[神经网络插件](http://supermemory.com/archive/english/algplug.htm) (NN.DLL)将记录所有单独项目的这个值，并将其用于训练网络:

> (5) Do=I2/I1
>
> where:
>
> - Do is guiding difficulty used in error correction (the higher the Do, the less the difficulty)
> - I1 is the first optimum interval computed for the item in question (same for all items)
> - I2 is the second optimum interval computed for the item
>
> (5) Do=I2/I1
>
> 上式中：
>
> - Do是用于纠错的引导难度(Do越高，难度越小)
> - I1是为所述项目计算的第一个最优区间(所有项目相同)
>
> - I2是计算出的第二个最优区间

Important! The optimum intervals I1 and I2 are not the ones proposed by the network before its verification but the ones used in error correction after the proposed interval had already been executed and verified (see [error correction for stability S](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Stability))!

The initial value of difficulty will be set to 3.5, i.e. D1=3.5. This is for similarity with Algorithm SM-8 only. As initial difficulty is not known, it cannot be used to determine the first interval. After scoring the first grade the error correction is still impossible due to the fact that second optimum interval is not known. Once it is known, Do can be used for error correction of D on the output.

重要!最优间隔I1和I2的网络之前提出的验证,但用于纠错后提出的区间已经执行和验证(见[纠错稳定S](https://supermemo.guru/wiki/History_of_spaced_repetition_(印刷)#稳定))!

难度的初值设为3.5，即D1=3.5。这只是为了与算法SM-8的相似性。由于初始难度未知，所以不能用来确定第一个区间。在获得一年级分数后，由于不知道第二最佳间隔，仍然不可能进行误差校正。一旦知道了，就可以使用Do对输出的D进行纠错。

To avoid convergence problems in the network, the following formula will be used to determine the correct output on D:

为了避免网络中的收敛问题，下面的公式将用于确定D上正确的输出:

> (6) Dopt=0.9*Di+0.1*Do
>
> where:
>
> - Dopt is difficulty used in error correction after the i-th repetition
> - Di is difficulty before the i-th repetition
> - Do is guiding difficulty from Eqn (5)
>
> (6) Dopt=0.9*Di+0.1*Do
>
> 上式中：
>
> - Dopt是第i次重复后的错误校正的难点
>
> - 困难在重复之前
>
> - Do从Eqn(5)引导难度
>
>

The convergence factor of 0.9 in Eqn (6) is arbitrary and may change depending on the network performance.

Eqn(6)中的收敛系数0.9是任意的，可能会随着网络性能的变化而变化。

**Error correction for stability S** **稳定的错误纠正**

The following formula, derived from Eqn (1) for forgetting index equal 10% and k=1, makes it easy to convert stability and the optimum interval: I=-ln(0.9)*S

由Eqn(1)推导出的遗忘指数为10%，k=1的公式可以方便地转换稳定性和最佳区间:I=-ln(0.9)*S

In the optimum case, the network should generate the requested forgetting index for each repetition. Variable forgetting index can easily be used once the stability S is known (see Eqn (1)). For simplicity then we will use forgetting index equal 10% in further analysis.

在最佳情况下，网络应该为每次重复生成请求的遗忘指数。一旦稳定性S已知，就可以方便地使用变量遗忘指数(Eqn(1))。为了简单起见，我们将在进一步的分析中使用遗忘指数= 10%。

To accelerate the convergence, the network will measure forgetting index for 25 classes of repetitions. These classes are set by (1) five difficulty categories: 1-1.5, 1.5-2.5, 2.5-3.5, 3.5-5, and over 5, and (2) five interval categories: 1-5, 5-20, 20-100, 100-500 and over 500 days. We will denote the forgetting index measurements for these categories as FI(Dm,In). Additionally, the overall forgetting index FItot will be measured and used in stability error correction.

为了加快收敛速度，该网络将测量25类重复的遗忘指数。(1)分1-1.5、1.5-2.5、2.5-3.5、3.5-5及以上五个难度等级，(2)分1-5、5-20、20-100、100-500及500天以上五个音程等级。我们将这些类别的遗忘指数度量表示为FI(Dm,In)。此外，还将测量整体遗忘指数FItot，并将其用于稳定性误差校正。

The ultimate goal is to reach the forgetting index of 10% in all categories. The following formula will be used in error correction for stability:

最终目标是在所有类别中达到10%的遗忘指数。下面的公式将用于误差校正的稳定性:

> (7) FIopt(m,n)=(10*FItot+Cases(m,n)*FI(m,n))/(10+Cases(m,n))
>
> where:
>
> - FIopt(m,n) is forgetting index used in error correction after a repetition belonging to category (m,n)
> - FItot is the overall forgetting index measured in repetitions
> - Cases(m,n) is the number of repetition cases used to measure the forgetting index in category (m,n)
>
> (7) FIopt(m,n)=(10*FItot+Cases(m,n)*FI(m,n))/(10+Cases(m,n))
>
> 上式中：
>
> - FIopt(m,n)是属于类别(m,n)的重复后用于纠错的遗忘索引。
> - FItot是以重复次数衡量的整体遗忘指数
>
> - 用例(m,n)是用来衡量类目(m,n)遗忘指数的重复用例数

The formula in Eqn (7) is supposed to shift the weight on error correction from the overall forgetting index to forgetting index recorded in given categories as soon as the number of cases in individual categories increases. Obviously, for Cases(m,n)=0, we have FIopt(m,n)=FItot. For Cases(m,n)=10 the weights for overall and category FI balance, and for a large number of cases, FIopt(m,n) is approaching FI(m,n).

Eqn(7)中的公式应该是当个别类别的病例数增加时，将错误纠正的权重从总体遗忘指数转移到给定类别的遗忘指数。显然，对于(m,n)=0的情况，我们有FIopt(m,n)=FItot。对于case (m,n)=10为总体和类别FI平衡的权重，对于大量的case, FIopt(m,n)正在接近FI(m,n)。

The following table illustrates the assumed relationship between FIopt(m,n), grades and the interval correction applied:

下表给出了FIopt(m,n)、等级与所应用的间隔校正之间的假设关系:

|     Grade      |       0       |       1       |       2       |       3       |       4       |       5       |
| :------------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| FIopt(m,n)>10% |      40%      |      60%      |      80%      | no correction | no correction | no correction |
| FIopt(m,n)=10% | no correction | no correction | no correction | no correction | no correction | no correction |
| FIopt(m,n)<10% | no correction | no correction | no correction |     110%      |     120%      |     130%      |

In [SuperMemo](https://supermemo.guru/wiki/SuperMemo), grades less than 3 are interpreted as forgetting, while grades equal 3 or more are understood as sufficient recall. That is why no correction is used for passing grades in case of satisfactory FI, and no correction is used for failing grades if FI is greater than requested. An exemplary correction for an excessive forgetting rate and grade=2 for applied interval of 10 days would be 80%. Consequently, the network will be instructed to assume Interval=8 as correct. Correct stability would then be derived from S=-8/ln(0.9) and used in error correction. The values of interval corrections are arbitrary but shall not undermine the convergence of the network. In case of unlikely stability problems, the corrections might be reduced (note that the environmental noise in the learning process will dramatically exceed the impact of ineffectively choosing the correction factors!). Similar corrections used to be applied in successive SuperMemo algorithms with encouraging results.

在[SuperMemo](https://supermemo.guru/wiki/SuperMemo)中，低于3分被解释为遗忘，高于3分被理解为足够的回忆。这就是为什么在FI满意的情况下，通过的分数不需要修正，如果FI大于要求，不及格的分数不需要修正。对于应用间隔10天的过度遗忘率和等级=2的示例性校正为80%。因此，网络将被指示假定Interval=8是正确的。然后从S=-8/ln(0.9)推导出正确的稳定性，并用于误差校正。区间修正的值是任意的，但不会破坏网络的收敛性。在不太可能出现的稳定性问题时，修正可能会减少(注意，学习过程中的环境噪声将大大超过没有有效选择修正因子的影响!)类似的修正也被应用于后续的SuperMemo算法中，得到了令人鼓舞的结果。

**Border conditions** **边界条件**

The following additional constraints will be imposed on the neural network to accelerate the convergence:

- interval increase in two successive repetition must be at least 1.1 (consequently, difficulty cannot be less than 1.1)
- interval increase cannot surpass 8 after the first repetition, and 4 in later repetitions
- the first interval must fall between 1 and 40 days
- difficulty measure cannot exceed 8

为加快收敛速度，神经网络将加入以下额外约束:

- 两个连续重复的间隔增加必须至少1.1(因此，难度不能小于1.1)

- 第一次重复不能超过8次，以后重复不能超过4次

- 第一个间隔必须在1至40天之间

- 难度测量不能超过8

These conditions will not prejudice the network as they have been proven beyond reasonable doubt as true in the practice of using SuperMemo and its implementations over the last ten years.

这些条件不会对网络造成损害，因为在过去10年使用SuperMemo及其实现的实践中，这些条件已经被毫无疑问地证明是正确的。

**Pretraining**  **Pretraining**

In the pretraining stage, the following form of Eqns (2) and (3) will be used:

在培训前阶段，将使用以下Eqns(2)和(3)形式:

> (8) Di+1:=Di+(0.1-(5-G)*(0.08+(5-G)*0.02))
>
> (9) Si+1:=Si*Di*(0.5+1/i)

With D1=3.5 and S1=-3/ln(0.9).

Eqn (8) has been derived from [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) (see E-Factor equation). Eqn (9) has been roughly derived from Matrix OF in [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8). D1=3.5 corresponds with the same setting in Algorithm SM-8. S1=-3/ln(0.9) corresponds with the first interval of 3 days and forgetting index 10%. The value of 3 days is close to an average across a wide spectrum of students and difficulty of the learning material.

Pretraining will also use border conditions mentioned in the previous paragraph.

There were multiple problems with the neural network, implementation, bugs, convergence, interference, and the like. The only way to effectively study the network was to plug it in real SuperMemo and see how it works on real data. I came up with an idea of plug-in algorithms in a DLL. We could study algorithmic variants in the same shell. We tried out [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2), [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) and now a neural network was to do the same. Unfortunately, that DLL implementation proved a step too far. Once the enthusiastic kids graduated, they soon dispersed, found jobs elsewhere, got married, and I never had a chance to try the plug-in in my own learning in my favorite shell, which was SuperMemo 9 at that time (aka SuperMemo 98).

Neural network SuperMemo was a student project with a sole intent to verify the viability of neural networks in spaced repetition. Needless to say, neural networks are a viable tool. Moreover, all imaginable valid optimization tools, given sufficient refinement, are bound to produce similar results to those currently accomplished by SuperMemo. In other words, as long as the learning program is able to quickly converge to the optimum model and produce the desired level of knowledge retention, the optimization tool used to accomplish the goal is of secondary importance.

Considering the number of problems at earlier stages, I doubt that successful plug-in would change my thinking about neural networks. I am a programmer and a tinkerer, I like to see what I create. Neural network appeared too black boxy to me. As for the team, they are all successful in their careers today. The kids have contributed to some other SuperMemo efforts later on. Youth is creative, youth is unpredictable, and I am glad we took on the project.

D1=3.5, S1=-3/ln(0.9)。

Eqn(8)是由[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)(参见E-Factor equation)推导出来的。Eqn(9)大致是由in [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)中的矩阵得到的。D1=3.5对应于算法SM-8中的相同设置。S1=-3/ln(0.9)对应第一个3天间隔，遗忘指数10%。3天的价值接近于一个广泛的范围内的学生和学习材料的难度的平均值。

培训前还将利用前一段所述的边界条件。

神经网络有很多问题，实现、bug、收敛、干扰等等。有效地研究这个网络的唯一方法是把它插入真实的SuperMemo中，看看它是如何处理真实数据的。我提出了在DLL中使用插件算法的想法。我们可以在同一个shell中研究算法变量。我们尝试了[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)，[算法SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)，现在一个神经网络也在做同样的事情。不幸的是，DLL实现被证明太过了。一旦热情的孩子们毕业了，他们很快就散去了，在其他地方找到了工作，结婚了，而我从来没有机会在我自己最喜欢的shell中尝试插件，那是SuperMemo 9(也就是SuperMemo 98)。

神经网络SuperMemo是一个学生项目，唯一的目的是验证神经网络在间隔重复中的可行性。不用说，神经网络是一个可行的工具。此外，所有可以想象得到的有效的优化工具，如果经过足够的细化，一定会产生与SuperMemo类似的结果。换句话说，只要学习程序能够快速地收敛到最优模型并产生所需的知识保留水平，用于实现目标的优化工具就是次要的。

考虑到早期阶段的问题数量，我怀疑成功的插件是否会改变我对神经网络的看法。我是一个程序员和修补匠，我喜欢看到我创造的东西。神经网络在我看来太黑了。至于这个团队，他们今天在事业上都很成功。后来，孩子们还为SuperMemo做出了贡献。青春是有创造力的，青春是不可预测的，我很高兴我们接受了这个项目。

## David Calinski and FullRecall

## David Calinski和FullRecall

David Calinski (b. 1981) was one of the early youthful SuperMemo enthusiasts in the 1990s. He showed rich interest in accelerated learning, psychology, psychiatry, and beyond.

I quickly recognized his talents and was hoping to recruit him in some SuperMemo projects, incl. SuperMemo for Linux, however, many a genius like to walk alone. At some point, he switched from SuperMemo to his own application (FullRecall, see later), and from that point on, he would not abandon his project.

David Calinski (b. 1981)是20世纪90年代早期年轻的超级备忘录爱好者之一。他对速成学习、心理学、精神病学等学科表现出浓厚的兴趣。

我很快就发现了他的才能，并希望能让他参与一些SuperMemo项目，包括Linux的SuperMemo。在某个时候，他从SuperMemo切换到了他自己的应用程序(FullRecall，见下文)，从那时起，他不会放弃他的项目。

Our discussions about neural networks started in 2001. David was a fan of SuperMemo, however, he also admitted to have never truly studied the algorithm. This led to a criticism:

我们对神经网络的讨论始于2001年。David是SuperMemo的粉丝，但是他也承认自己从来没有真正研究过这个算法。这招致了批评:

> I don't know the exact details of SM algorithm(s) (I never was much interested in it), but important here is the main idea. Algorithm in SM gets some data (e.g. number of repetitions, difficulty of item, current grade, etc. etc.) and returns next optimal interval it calculated. This algorithm, even if it's "smart" and corrects itself somehow, will be still dumb - it won't correct itself more than was designed for.
>
> 我不知道SM算法的具体细节(我从来没有对它很感兴趣)，但重要的是这里的主要思想。SM中的算法获取一些数据(如重复次数、项目难度、当前等级等)，并返回它计算的下一个最优区间。这个算法，即使它是“聪明的”，并以某种方式纠正自己，仍然是愚蠢的——它不会比设计的更多地纠正自己。

He is right, [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) is inherently bound to the [two component model of long-term memory](https://supermemo.guru/wiki/Two_component_model_of_long-term_memory), however, this is a happy marriage. The bond can only be broken by counter-evidence that hasn't come in three decades thus far.

他是对的，[Algorithm smo -17](https://supermemo.guru/wiki/Algorithm_SM-17)与[two component model of long-term memory](https://supermemo.guru/wiki/Two_component_model_of_long-term_memory)是有内在联系的，但这是一段幸福的婚姻。这种联系只能通过30年来从未出现过的反证据来打破。

David's stance is entirely justifiable. It is all about modelling and prior knowledge. For David, [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) was complex. Neural networks seem like a simple way to take away the complexity. To me, my own algorithm is as simple as the multiplication table. That modelling difference often leads to cognitive divergence and this is a good thing. Without those differences, we would know much less about neural networks in spaced repetition today!

戴维的立场完全有道理。这都是关于建模和先验知识。对于David来说，[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)非常复杂。神经网络似乎是一种消除复杂性的简单方法。对我来说，我自己的算法就像乘法表一样简单。这种建模上的差异常常导致认知上的分歧，这是一件好事。如果没有这些区别，我们今天对间隔重复的神经网络的了解就会少得多!

I wrote to David in 2004: *"Further improvements to the algorithm used in SuperMemo are not likely to result in further acceleration of learning. However, there is still scope for improvement for handling unusual cases such as dramatically delayed repetitions, massed presentation, handling items whose contents changed, handling semantic connections between items, etc. Interestingly, the greatest progress in the algorithm is likely to come from a better definition of the model of human long-term memory. In particular, the function describing changes in memory stability for different levels of retrievability is becoming better understood. This could dramatically simplify the algorithm. Simpler models require fewer variables and this simplifies the optimization. The algorithm based on stability and retrievability of memory traces could also result in better handling of items with low retrievability. However, as unusual item cases in the learning process form a minority, and testing a new algorithm would take several years, it is not clear if such an implementation will ever be undertaken"*.

我在2004年给David写信说:“SuperMemo中使用的算法的进一步改进不太可能进一步加速学习。但是，在处理一些不寻常的情况时，如严重延迟的重复、大量的表示、处理内容改变的项、处理项之间的语义连接等，还有改进的余地。有趣的是，该算法的最大进步可能来自于对人类长期记忆模型的更好定义。特别是，描述不同可检索性级别的内存稳定性变化的函数正得到更好的理解。这将极大地简化算法。更简单的模型需要更少的变量，这简化了优化。该算法基于记忆轨迹的稳定性和可检索性，可以更好地处理可检索性较低的项。然而，由于在学习过程中不寻常的项目案例占少数，而且测试一个新算法需要几年时间，因此不清楚是否会进行这样的实现”*。

David developed his own neural network, MemAid. Later he converted it into a commercial product. The move from free to commercial was hard as users tend to prefer a drop in prices, for obvious reasons. Despite all ups and downs, David persisted, and his DIY tinkerer and passion for science and programming always gave him an upper hand. Like Anki, he tried to keep his program cross-platform which imposed some limits and demands on simplicity. In his words: *"I love speed and lack of borders, lack of dependency on just one solution, system, computer, etc."*

戴维开发了自己的神经网络MemAid。后来他把它变成了一个商业产品。从免费到商业化的转变是困难的，因为用户倾向于选择降价，原因显而易见。尽管经历了起起落落，大卫还是坚持了下来，他的DIY工匠和对科学和编程的热情总是让他占了上风。像Anki一样，他试图保持他的程序跨平台，这对简单性提出了一些限制和要求。用他的话来说:“我喜欢速度和没有边界，不依赖于一个解决方案、系统、计算机等。”

Today FullRecall is free. See the [changelong](http://fullrecall.com/changelog).

今天FullRecall是免费的。看到[changelong](http://fullrecall.com/changelog)。

[![ANN interval distribution (in FullRecall)](https://supermemo.guru/images/f/f1/ANN_interval_distribution.jpg)](https://supermemo.guru/wiki/File:ANN_interval_distribution.jpg)

> ***Figure:** Interval distribution in FullRecall. Repetitions scheduled with the help of a neural network*
>
> ***图片：**全召回中的区间分布。在神经网络的帮助下安排重复

The open-source [MemAid project](http://memaid.sourceforge.net/) closed in 2006, but FullRecall continued. So did another project inspired by MemAid: [Mnemosyne](https://supermemo.guru/wiki/Mnemosyne). Mnemosyne, however, opted for their own version of [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2). To this day, Mnemosyne generates data that can be used by spaced repetition enthusiasts or researchers at [The Mnemosyne Project](https://mnemosyne-proj.org/).

开源项目[MemAid项目](http://memaid.sourceforge.net/)于2006年关闭，但完整的召回仍在继续。还有一个受MemAid启发的项目:[Mnemosyne](https://supermemo.guru/wiki/Mnemosyne)。然而，Mnemosyne选择了他们自己的版本[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)。时至今日，Mnemosyne生成的数据还可以被间隔重复记忆的爱好者或研究人员在[Mnemosyne项目](https://mnemosyne-proj.org/)中使用。

Like Calinski, Peter Bienstman is skeptical of newer algorithms: *"SuperMemo now uses SM-11. However, we are a bit skeptical that the huge complexity of the newer SM algorithms provides for a statistically relevant benefit. But, that is one of the facts we hope to find out with our data collection."*

像Calinski一样，Peter Bienstman对新的算法表示怀疑:“SuperMemo现在使用SM-11。然而，我们有点怀疑，新的SM算法的巨大复杂性是否提供了统计相关的好处。但是，这是我们希望通过数据收集找到的事实之一。

*"Statistically relevant benefit"* depends on the criteria. For users, the actual algorithm may be secondary. For research, [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) is a goldmine (as much as data that all programs like Mnemosyne can generate).

*“统计上相关的福利”*视乎准则而定。对于用户来说，实际的算法可能是次要的。对于研究来说，[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)是一座金矿(就像所有像Mnemosyne这样的程序可以生成的数据一样多)。

## Why is the neural network in FullRecall flawed?

## 为什么完全回忆中的神经网络有缺陷?

[The two memory variables](https://supermemo.guru/wiki/Two_component_model_of_memory) are both necessary and sufficient to represent an [atomic memory](https://supermemo.guru/wiki/Atomic_memory) in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition). Moreover, the two variables can be used to account for the [spacing effect](https://supermemo.guru/wiki/Spacing_effect) in massed presentation. They can also explain the benefit of high [forgetting index](https://supermemo.guru/wiki/Forgetting_index) for long-term [retention](https://supermemo.guru/wiki/Retention) as discussed here. Those two variables of long-term memory which we named: [stability](https://supermemo.guru/wiki/Stability) and [retrievability](https://supermemo.guru/wiki/Retrievability) are necessary to represent the status of memory. Any neural network that wants to find patterns in the relationship between spacing and recall must receive the full status of memory on its input otherwise it won't ever compute the optimum spacing. That status may have a form of the full [history of repetitions](https://supermemo.guru/wiki/History_of_repetitions). It may also be the [stability](https://supermemo.guru/wiki/Stability) : [retrievability](https://supermemo.guru/wiki/Retrievability) pair (if it can be computed). It may also be any other code over the history of repetitions from which the status of memory can be computed.

[两个内存变量](https://supermemo.guru/wiki/Two_component_model_of_memory)是必要的和充分的，以表示[间隔重复][原子内存](https://supermemo.guru/wiki/Atomic_memory) (https://supermemo.guru/wiki/Spaced_repetition)。此外，这两个变量可以用来解释[间距效应](https://supermemo.guru/wiki/Spacing_effect)在大规模演示中。他们也可以解释高[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)对长期[记忆](https://supermemo.guru/wiki/Retention)的好处。我们将长期记忆的两个变量命名为:[stability](https://supermemo.guru/wiki/Stability)和[retrievability](https://supermemo.guru/wiki/Retrievability)，这两个变量代表了记忆的状态。任何神经网络想要找到记忆间隔和回忆之间的关系模式，都必须在输入时接收到记忆的全部状态，否则就无法计算出最佳的记忆间隔。这个状态可能有一个完整的[历史的重复](https://supermemo.guru/wiki/History_of_repetitions)。也可能是[stability](https://supermemo.guru/wiki/Stability): [retrievability](https://supermemo.guru/wiki/Retrievability)对(如果可以计算的话)。它也可以是在重复的历史上的任何其他代码，从那里可以计算内存的状态。

The design of the FullRecall network does not meet those criteria:

- input: last_interval_computed_by_ann [0-2048 days] (zero if this is not a review, but a first presentation)
- input: real_interval_since_last_review [0-2048 days] (same comment as above)
- input: number_of_repetitions_of_an_item_so_far [0-128]
- input: current_grade [0-5, 5 is the best]
- output that ANN gives us: new_interval [0-2048]

FullRecall网络的设计不符合这些标准:

- 输入:last_interval_computed_by_ann[0-2048天]
- 输入:real_interval_since_last_review[0-2048天](与上面相同的评论)
- 输入:number_of_repetitions_of_an_item_so_far [0-128]
- 输入:current_grade[0- 5,5是最好的]
- ANN给出的输出:new_interval [0-2048]

Neither interval nor repetitions count can reflect memory stability or retrievability. You can obtain high repetition counts in massed presentation subject to spacing effect with a negligible increase in memory stability. At the same time, long intervals for suboptimum schedules may result in low values for both stability and retrievability. In short, for the same interval, the status of memory will depend on the distribution of repetitions in time.

This can be shown with an example: for 10 repetitions, and 1000 days, 9 repetitions in 9 days combined with 991 day interval will produce stability approaching zero (assuming no interference). At the same time, for the same pair of inputs, optimally spaced repetition can bring retrievability of nearly 100% and stability that allows of optimum intervals close to 1000 days.

间隔和重复计数都不能反映记忆的稳定性和可检索性。在受间隔效应影响的情况下，你可以在大量的演示中获得高重复次数，而在内存稳定性方面的提高可以忽略不计。同时，次优调度的长时间间隔可能导致稳定性和可检索性值较低。简而言之，对于相同的时间间隔，记忆的状态将取决于重复在时间上的分布。

这可以通过一个例子来说明:在10次重复和1000天的情况下，9天重复9次，再加上991天的间隔，将产生接近于零的稳定性(假设没有干扰)。同时，对于同一对输入，最佳间隔重复可以带来接近100%的可检索性和稳定性，允许最佳间隔接近1000天。

The only scenario where the network might perform well is where the user adheres precisely to the optimum spaced repetition schedule. This, in turn, can only come from a network that has been pre-trained, e.g. with [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2). In this scenario, the network will be unstable and won't converge on the optimum due to the fact that all departures from the optimum schedule, incl. those caused by network error will shift the state of the network away from the original state in which it was still able to compute memory status from its inputs.

网络可能表现良好的唯一情况是用户精确地遵守最佳间隔重复计划。反过来，这只能来自一个预先训练过的网络，例如使用[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)。在这种情况下,网络会不稳定,不会对最优收敛因为所有偏离最优时间表,包括那些由于网络错误将网络从原始状态的状态中,它还能计算出内存状态的输入。

Stability and retrievability are sufficient in the idealized case for a unitary monosynaptic association. In real life, the semantic network involved in the association is likely to involve a number of such ideal unitary memories. This is why SuperMemo uses the concept of absolute item difficulty. In [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17), the absolute item difficulty is determined by the maximum increase in memory [stability](https://supermemo.guru/wiki/Stability) for the first optimally scheduled review at the default [forgetting index](https://supermemo.guru/wiki/Forgetting_index) of 10%. The FullRecall network does not receive any reliable measure of item difficulty either. This will compound the network's inefficiency.

在理想的情况下，稳定性和可检索性对于单式单突触联想来说是足够的。在现实生活中，这种联想所涉及的语义网络很可能包含许多这样的理想的单一记忆。这就是为什么SuperMemo使用了绝对难度的概念。在[算法SM-17] (https://supermemo.guru/wiki/Algorithm_SM-17),绝对项困难是由最大增加内存[稳定](https://supermemo.guru/wiki/Stability)在默认为第一最优计划审查[忘记指数](https://supermemo.guru/wiki/Forgetting_index)的10%。全召回网络也不接受任何可靠的项目难度测量。这将加剧网络的低效率。

The FullRecall network is said to work pretty well, according to user reports. In the light of the present analysis, the network might employ well-chosen boundary conditions, however, this would be equivalent to returning to [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2) employed in older versions of SuperMemo. Needless to say, that old SuperMemo algorithm is more biased and less plastic than newer matrix-based algebraic versions employed in SuperMemo.

根据用户报告，FullRecall网络据说工作得很好。根据目前的分析，这个网络可能会使用经过挑选的边界条件，但是，这就相当于回到旧版本SuperMemo中使用的[Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)。不用说，与SuperMemo中使用的更新的基于矩阵的代数版本相比，旧的SuperMemo算法更有偏倚，也更可靠。

If the FullRecall network is pre-trained, e.g. with the help of [Algorithm SM-2](https://supermemo.guru/wiki/Algorithm_SM-2), and the student sticks rigorously to his or her repetition, the network might work ok as the interval correlates well with memory stability, esp. if the information is enhanced by the number of repetitions. However, without appropriate boundary conditions, in [incremental reading](https://supermemo.guru/wiki/Incremental_reading), the network would certainly fail as it might receive false memory status information. Depending on the scenario, the same Repetitions : Interval pair may occur for Stability=0 and for maximum stability corresponding with lifetime memories. Similarly, the retrievability may also vary in the 0-1 range for the same input pair in the network. For example, frequent subset review before an exam followed by a longer break in learning (e.g. caused by overflow) may correspond with very low stability and retrievability despite providing the same input as a correctly executed series of spaced reviews in the same period (with high stability and retrievability above 0.9). In [incremental reading](https://supermemo.guru/wiki/Incremental_reading), overload, auto-postpone, item advance, subset review, and spacing effect would be invisible to the network.

如果pre-trained FullRecall网络,例如[算法SM-2](https://supermemo.guru/wiki/Algorithm_SM-2)的帮助下,和学生坚持严格他或她重复,网络可能工作好间隔与记忆密切相关的稳定性,特别是如果信息增强的重复的数量。但是，如果没有适当的边界条件，在[incremental reading](https://supermemo.guru/wiki/Incremental_reading)中，网络肯定会失败，因为它可能接收到错误的内存状态信息。根据不同的场景，可能会出现相同的重复:对于稳定性=0和与终身记忆对应的最大稳定性，可能会出现间隔对。同样，对于网络中的相同输入对，可检索性也可能在0-1范围内变化。例如,频繁的子集审查考试之后再休息之前在学习(如溢出造成的)可能与非常低的稳定和可恢复性尽管提供相同的输入作为正确执行一系列同期间隔的评论(具有高稳定性和可恢复性上图0.9)。在[增量阅读](https://supermemo.guru/wiki/Incremental_reading)中，过载、自动延迟、项目提前、子集审查和间隔效应对网络来说是不可见的。

Assuming good design, the flaws of FullRecall will then only show in intermitted learning, which may trigger boundary conditions. It should not detract from the value of the software itself. It is only to emphasize that neural network design is not easy, and may turn out inferior. It may even be inferior in comparison to older, allegedly less plastic, algebraic algorithms.

假设设计良好，完整回忆的缺陷只会在间断学习中出现，从而触发边界条件。它不应该减损软件本身的价值。只是要强调，神经网络的设计是不容易的，而且可能会变得较差。它甚至可能不如旧的、据说不那么灵活的代数算法。

In short, FullRecall inputs do not reflect all necessary information needed for computing optimum intervals. In particular, repetition count is a very poor measure of memory stability or retrievability. A better approach would be to code the entire[history of repetitions](https://supermemo.guru/wiki/History_of_repetitions) or compute the status of memory with the use of [stability](https://supermemo.guru/wiki/Stability) and [retrievability](https://supermemo.guru/wiki/Retrievability) variables. Both stability and retrievability must be computable from the network input.

简而言之，完全回忆输入不能反映计算最佳间隔所需的所有必要信息。特别是，重复计数是一个很差的衡量记忆稳定性或检索能力。一个更好的方法是整个历史的重复代码(https://supermemo.guru/wiki/History_of_repetitions)或计算内存使用的状态[稳定](https://supermemo.guru/wiki/Stability)和[可恢复性](https://supermemo.guru/wiki/Retrievability)变量。稳定性和可检索性都必须能够从网络输入中计算出来。

## Future of neural networks in SuperMemo

## SuperMemo中神经网络的未来

In our discussions with Calinski (in 2001), I summarized my reservations and vowed to continue on the same old "conservative" path. 17 years later, I am glad. There has not been much progress in the area of employing neural networks in spaced repetition. It might be the fact that SuperMemo itself is an inhibitor of progress. In the meantime, however, [Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17) has revealed further potential for improvements in [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) and understanding human memory. Time permitting, there will still be progress.

在我们与卡利斯基(2001年)的讨论中，我总结了我的保留意见，发誓要继续走老路。17年后，我很高兴。在使用神经网络进行间隔重复的领域中，还没有太多的进展。这可能是因为SuperMemo本身就是一个阻碍进步的因素。然而，与此同时，[Algorithm SM-17](https://supermemo.guru/wiki/Algorithm_SM-17)揭示了进一步改进[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)和理解人类记忆的潜力。如果时间允许，还是会有进步的。

SuperMemo will continue with its algebraic algorithms for the following reasons:

- **Known model**: Neural networks are superior in cases where we do not know the underlying model of the mapped phenomena. The model of forgetting is well-known and makes it easy to fine-tune the algebraic optimization methods used in computing inter-repetition intervals. The well-known model also makes SuperMemo resistant to unbalanced datasets, which might plague neural networks, esp. in initial stages of learning. Last but not least, the validity of the [two component model of memory](https://supermemo.guru/wiki/Two_component_model_of_memory) has been proven in many ways and giving up the model while designing the network, in the name of stemming prejudice, would be wasteful. Such approach may have a research value only
- **Overlearning**: Due to case-weighted change in array values, optimization arrays used in SuperMemo are not subject to "overlearning". No pretraining is needed, as the approximate shape of the function of optimal intervals is known in advance. There is no data representation problem, as all kinky data input will be "weighed out" in time
- **Equivalence**: Mathematically speaking, for continuous functions, n-input networks are equivalent to n-dimensional arrays in mapping functions with n arguments, except for the "argument resolution problem". The scope of argument resolution problem, i.e. the finite number of argument value ranges, is strongly function dependent. A short peek at the optimization arrays displayed by SuperMemo indicates that the "argument resolution" is far better than what is actually needed for this particular type of function, esp. in the light of the substantial "noise" in data. Hill-climbing algorithms used in SuperMemo are reminiscent of the algorithms aimed at reweighing the networks
- **Research**: The use of matrices in SuperMemo makes it easy to see "memory in action". Neural networks are not that well-observable. They do not effectively reveal their findings. You cannot see how a single forgetting curve affects the function of optimum intervals. This means that the black-box nature of neural networks makes them less interesting as a memory research tool
- **Convergence**: The complexity of the algorithm does not result from the complexity of the memory model. Most of the complexity comes from the use of tools that are supposed to speed up the convergence of the optimization procedure without jeopardizing its stability. This fine-tuning is only possible due to our good knowledge of the underlying memory model, as well as actual learning data collected over years that help us precisely determine best approximation function for individual components of the model
- **Forgetting curve**: The only way to determine the [optimum interval](https://supermemo.guru/wiki/Optimum_interval) for a given [forgetting index](https://supermemo.guru/wiki/Forgetting_index) is to know the (approximate) forgetting curve for a given [difficulty](https://supermemo.guru/wiki/Difficulty) class and memory [stability](https://supermemo.guru/wiki/Stability). If a neural network does not attempt to map the forgetting curve, it will always oscillate around the value of the optimum interval (with good grades increasing that value, and bad grades decreasing it). Due to data noise, this is only a theoretical problem. However, it illustrates the power of the symbolic representation of stability-retrievability-difficulty-time relationship instead of a virtually infinite number of possible forgetting curve data sets. If the neural network does not use a weighted mapping of the forgetting curve, it will never converge. In other words, it will keep oscillating around the optimum model. If the neural network weighs in the status history and/or employs the forgetting curve, it will take the same approach as the present SuperMemo algorithm, which was to be obviated by the network in the first place

SuperMemo将继续其代数算法，原因如下:

- **已知模型**:神经网络在我们不知道映射现象的底层模型的情况下是优越的。遗忘模型是众所周知的，它使计算重复间隔的代数优化方法易于调整。这个著名的模型还使SuperMemo抵抗不平衡的数据集，这些数据集可能会困扰神经网络，特别是在学习的初始阶段。最后但并非最不重要的是，[内存的双组件模型](https://supermemo.guru/wiki/Two_component_model_of_memory)的有效性已经在许多方面得到了证明，在设计网络时，以消除偏见的名义放弃该模型，将是一种浪费。这种方法可能只有研究价值
- **过度学习**:由于数组值的大小写变化，SuperMemo中使用的优化数组不属于“过度学习”。不需要预训练，因为最优区间函数的近似形状是预先知道的。没有数据表示的问题，因为所有的扭结数据输入将“权衡”的时间

- **等价**:从数学上讲，对于连续函数，除了“参数解析问题”外，n-输入网络等价于映射函数中有n个参数的n维数组。参数解析问题的范围，即有限数量的参数值范围，是与函数密切相关的。稍微看一下SuperMemo显示的优化数组，就会发现“参数解析”比这种特殊类型的函数实际需要的参数解析要好得多，特别是考虑到数据中大量的“噪音”。SuperMemo中使用的爬山算法让人联想到旨在重新衡量网络的算法

- **研究**:矩阵在SuperMemo中的使用，使它很容易看到“行动中的记忆”。神经网络不是那么容易观察到的。他们没有有效地揭示他们的发现。你看不出一条遗忘曲线是如何影响最佳间隔函数的。这意味着，作为记忆研究工具，神经网络的黑箱特性让它们变得不那么有趣了

- **收敛性**:算法的复杂度不取决于内存模型的复杂度。大部分的复杂性来自于工具的使用，这些工具被认为可以加速优化过程的收敛，而又不会破坏其稳定性。这种微调是可能的，因为我们对底层的记忆模型的良好知识，以及多年来收集的实际学习数据，帮助我们精确地确定模型的各个组件的最佳逼近函数

- **遗忘曲线**:确定的唯一方法[最优区间](https://supermemo.guru/wiki/Optimum_interval)对于一个给定的[忘记指数](https://supermemo.guru/wiki/Forgetting_index)是知道的(近似)遗忘曲线对于一个给定的[困难](https://supermemo.guru/wiki/Difficulty)类和内存[稳定](https://supermemo.guru/wiki/Stability)。如果一个神经网络不尝试去映射遗忘曲线，它将总是在最佳区间的值附近振荡(好的分数增加这个值，坏的分数减少它)。由于数据噪声，这只是一个理论问题。然而，它展示了稳定-可恢复-困难-时间关系的符号表示法的力量，而不是几乎无限数量的可能的遗忘曲线数据集。如果神经网络不使用遗忘曲线的加权映射，它将永远不会收敛。换句话说，它会在最优模型周围持续振荡。如果神经网络考虑状态历史和/或使用遗忘曲线，它将采用与当前SuperMemo算法相同的方法，而SuperMemo算法在一开始就被神经网络所排除

In sum, neural networks could be used to compute the intervals, but they do not seem to be the best tool in terms of computing power, research value, stability, and, most of all, the speed of convergence. When designing an optimum neural network, we run into similar difficulties as in designing the algebraic optimization procedure. In the end, the same boundary conditions that are set in "classic" [SuperMemo](https://supermemo.guru/wiki/SuperMemo) will also show up, sooner or later, in the network design (as can be seen in: [Neural Network SuperMemo](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Neural_Network_SuperMemo:_Design)).

总之，神经网络可以用来计算区间，但在计算能力、研究价值、稳定性以及最重要的收敛速度方面，它们似乎不是最好的工具。在设计最优神经网络时，我们遇到了与设计代数优化过程类似的困难。最后,同样的边界条件设置的“经典”[SuperMemo](https://supermemo.guru/wiki/SuperMemo)也将出现,或早或晚,在网络设计(我们可以看到:[神经网络SuperMemo](https://supermemo.guru/wiki/History_of_spaced_repetition_(印刷)# Neural_Network_SuperMemo: _Design))。

As with all function approximations, the choice of the tool, and minor algorithmic adjustments can make a world of difference in the speed of convergence and the accuracy of mapping. Neural networks could find use in mapping the lesser known accessory functions that are used to speed up the convergence of the algebraic algorithm. For example, to this day, [item difficulty](https://supermemo.guru/wiki/Complexity) estimate problem has not been fully cracked. We simply tell users to keep their knowledge simple, which is a universal recommendation from any educator aware of mnemonic limits of human memory.

与所有的函数近似一样，工具的选择和小的算法调整可以在收敛速度和映射精度上产生巨大的差异。神经网络可以用于映射较少为人所知的辅助函数，这些辅助函数用于加速代数算法的收敛。例如，直到今天，[项目难度](https://supermemo.guru/wiki/Complexity)的评估问题还没有完全解决。我们只是简单地告诉用户保持他们的知识简单，这是一个普遍的建议，从任何教育工作者意识到人类记忆的记忆极限。