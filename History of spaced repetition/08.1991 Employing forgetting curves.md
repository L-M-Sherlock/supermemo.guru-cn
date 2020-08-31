# 1991: Employing forgetting curves

# 使用遗忘曲线

[TOC=2,5]

## Painful birth of SuperMemo World (1991)

## SuperMemo世界的痛苦诞生(1991)

1991 was the most important year since the birth of [SuperMemo](https://supermemo.guru/wiki/SuperMemo). It was a year of big decisions, stress, drama, discovery, and hard work. At the start of the year, there were three greatest believers in SuperMemo: [Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak), [Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski) and [myself](https://supermemo.guru/wiki/Piotr_Wozniak). We were all in the same spot in our lives: transitioning from the years of unconcern at the university to the uncertainty of independent adulthood. By default, we all dreamt of big science in the US: Biedalak dreamt of artificial intelligence, Murakowski of quantum physics, and I wanted to crack the secrets of [molecular memory](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory). In retrospect, graduate students from Eastern Bloc with good transcripts, good standardized test results, and rock-solid recommendations are pretty welcome in the US. Things get more complex if they demand full financial support. I did not have a penny. Moreover, eager Easterners were often treated as dutiful labor. Zeal for their own projects, and great ideas might have been less welcome. I will never know. The three believers had all different visions for [SuperMemo](https://supermemo.guru/wiki/SuperMemo).

1991年是自[SuperMemo](https://supermemo.guru/wiki/SuperMemo)诞生以来最重要的一年。这是充满重大决定、压力、戏剧性、发现和努力工作的一年。年初的时候，有三个超级备忘录最伟大的信徒:[Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)， [Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)和[我自己](https://supermemo.guru/wiki/Piotr_Wozniak)。我们都处在人生的同一个阶段:从大学里无忧无虑的日子过渡到独立的成年期的不确定性。默认情况下，我们都梦想着美国的大科学:比达拉克梦想着人工智能，Murakowski梦想着量子物理学，而我想要破解[分子记忆](https://supermemo.guru/wiki/Neurostatistical_Model_of_Memory)的秘密。现在回想起来，来自东欧国家的研究生成绩优异，标准化考试成绩优异，推荐信坚如磐石，在美国很受欢迎。如果需要全面的财政支持，事情就会变得更加复杂。我一分钱也没有。此外，热心的东部人常常被视为尽职的劳动者。对自己项目的热情和伟大的想法可能不那么受欢迎。我永远不会知道。这三位信徒对[SuperMemo](https://supermemo.guru/wiki/SuperMemo)有不同的看法。

On Jan 3, 1991, I started the implementation of the new [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) algorithm for [SuperMemo 6](https://supermemo.guru/wiki/SuperMemo_6). On the same day, Murakowski left for London where he would pursue his educational dreams while trying to sell [SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2). He would not sell via a distribution channel or in a shop. He would just go from person to person, explain the merits of the program, and hopefully collect a few bucks to keep the hope going.

1991年1月3日，我开始执行新的[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)算法[SuperMemo 6](https://supermemo.guru/wiki/SuperMemo_6)。就在同一天，村上春树前往伦敦，在那里他将一边追求自己的教育梦想，一边试图出售自己的[SuperMemo] (https://supermemo.guru/wiki/SuperMemo_2)。他不会通过分销渠道或商店销售。他只是一个接一个地介绍这个项目的优点，希望能赚到一些钱，让这个希望继续下去。

In the meantime, Biedalak and I met regularly for a 10 km jogging that would be combined with winter swimming and a [brainstorming](https://supermemo.guru/wiki/Brainstorming) session on the way back home (we called it *walktalking*). We mostly spoke of studying in the US and selling [SuperMemo](https://supermemo.guru/wiki/SuperMemo). More and more frequently, the idea of [our own company](https://supermemo.guru/wiki/SuperMemo_World) started coming up in discussions.

I started my work over the new [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) algorithm with some ideas that would change SuperMemo for ever. [Algorithm SM-6](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#Algorithm_SM-6) used in SuperMemo 6 was a breakthrough that would power further development over the next 25 years. It would re-employ the simple experimental procedure that led to [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) in [1985](https://supermemo.guru/wiki/Birth_of_SuperMemo) but would do it in an automated manner. It would collect performance data, and choose the best time for review: it would plot the user's [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve). This would also mean that the user would be able to decide the acceptable probability of [forgetting](https://supermemo.guru/wiki/Forgetting) for every single item (i.e. the optimum level of retention-workload tradeoff).

与此同时，在回家的路上，比达拉克和我定期见面，一起慢跑10公里，同时进行冬泳和头脑风暴(https://supermemo.guru/wiki/)。我们主要谈论的是在美国学习和销售[SuperMemo](https://supermemo.guru/wiki/SuperMemo)。越来越频繁地，[我们自己的公司](https://supermemo.guru/wiki/SuperMemo_World)的想法开始出现在讨论中。

我开始了我的工作在新的[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)算法与一些想法，将改变SuperMemo永远。在SuperMemo 6中使用的算法SM-6是一个突破，它将为未来25年的进一步发展提供动力。它将在[1985](https://supermemo.guru/wiki/Birth_of_SuperMemo)重新使用导致[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)的简单实验过程，但将以自动化的方式进行。它将收集性能数据，并选择最佳的复习时间:它将绘制用户的[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)。这也意味着用户可以决定每一项的可接受的[遗忘](https://supermemo.guru/wiki/forget)(概率即保留-工作负载折衷的最佳水平)。

At that time, I was still bound to 360 kB floppy diskettes ([5.25 in](https://en.wikipedia.org/wiki/Floppy_disk#5¼-inch_floppy_disk)). For that reason, SuperMemo still could not keep all repetition histories that would fully replicate the [1985](https://supermemo.guru/wiki/Birth_of_SuperMemo) approach on a massive scale. However, on Jan 6, 1990, I had a simple idea: I could just collect data about the [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) for classes of [items](https://supermemo.guru/wiki/Item) of different [difficulty](https://supermemo.guru/wiki/Difficulty) and [stability](https://supermemo.guru/wiki/Stability). Instead of the full record, I would only update the approximation of how many items in a given class are [retained](https://supermemo.guru/wiki/Retention) in memory at a given time (i.e. at a given level of [retrievability](https://supermemo.guru/wiki/Retrievability)). That idea survives at the core of [SuperMemo](https://supermemo.guru/wiki/SuperMemo) to this day. Even with the full record of repetition histories today, SuperMemo still instantly knows the expected [retrievability](https://supermemo.guru/wiki/Retrievability) of items in a given class.

在那个时候,我还是会360 kB软盘([5.25](https://en.wikipedia.org/wiki/Floppy_disk # 5¼-inch_floppy_disk))。由于这个原因，SuperMemo仍然不能保留所有的重复历史，这些重复历史将完全复制[1985](https://supermemo.guru/wiki/Birth_of_SuperMemo)方法。然而,在1990年1月6日,我有一个简单的想法:我可以收集数据的[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)类[项目](https://supermemo.guru/wiki/Item)的不同[困难](https://supermemo.guru/wiki/Difficulty)和[稳定](https://supermemo.guru/wiki/Stability)。代替完整的记录，我将只更新给定类中在给定时间(即在给定级别的[可检索性](https://supermemo.guru/wiki/Retention)中有多少项被[保留](https://supermemo.guru/wiki/Retrievability)的近似值。这个想法一直存在于[SuperMemo](https://supermemo.guru/wiki/SuperMemo)的核心，直到今天。即使有了今天重复历史的完整记录，SuperMemo仍然能够立即知道给定类中项目的预期[retrievability](https://supermemo.guru/wiki/Retrievability)。

At the crossroads in life, I was finally free from school. There is a powerful emotion that millions of teens and young adults face in their lives: a traumatic move from a slave called "pupil" or "student", to the freedom of becoming an "unemployed adult". The psychological shakeup can be even more dramatic if one turns from a "[good student](https://supermemo.guru/wiki/Dangers_of_being_a_Straight_A_student)" to an "unemployed 28-year-old living with his mom". Like a lightswitch: the whole world seems to change from cheerful support to a gloomy-faced condemnation mixed up with pity.

I kept learning, and worked on new ideas for [SuperMemo](https://supermemo.guru/wiki/SuperMemo) in the atmosphere of freedom mixed up with uncertainty. For me, uncertainty is an energizer. However, on Feb 12, 1991, I learned that my mom was diagnosed with terminal cancer. To the mix of freedom and uncertainty, it added the sense of gloom. For me again, gloom can also be an energizer. I tripled my learning with focus on cancer in hope of finding out some magic therapy on my own. This shows the positive impact of unreasonable optimism on productivity. It also shows that crazy optimism can help survive difficult times. By working harder, I could dispel the gloom. High productivity is a sure anti-depressant. My hard work left no room for dark thoughts. I was confident, I would cure my mom!

在人生的十字路口，我终于从学校解脱出来了。数以百万计的青少年在他们的生活中面临着一种强烈的情感:从一个被称为“学生”或“学生”的奴隶到自由成为“失业的成年人”的痛苦的转变。如果一个人从“[好学生](https://supermemo.guru/wiki/dangers_of_being_a_line_a_student)”转变为“28岁的失业青年，与母亲同住”，他的心理变化可能会更加剧烈。就像一盏灯的开关:整个世界似乎从愉快的支持变成了一种掺杂着怜悯的阴郁的谴责。



我不断学习，在充满不确定性的自由氛围中，为[SuperMemo](https://supermemo.guru/wiki/SuperMemo)研究新的想法。对我来说，不确定性是一种激励。然而，在1991年2月12日，我得知我的母亲被诊断出癌症晚期。在自由和不确定的混合中，它增加了阴郁的感觉。对我来说，忧郁也是一种激励。我把我的学习重点放在癌症上，希望自己能找到一些神奇的疗法。这显示了不合理的乐观主义对生产力的积极影响。它还表明，疯狂的乐观主义有助于度过困难时期。通过更努力地工作，我可以驱散忧郁。高效率是一种有效的抗抑郁剂。我的辛勤工作没有给我留下任何阴暗的思想空间。我很有信心，我会治好我妈妈的!

Incidentally, at the moment of my mom's diagnosis, I was also writing a program to simulate the optimum behavior of memory in response to the environment. This was to prove mathematically that the [two component model of memory](https://supermemo.guru/wiki/Two_component_model_of_memory) was optimum for survival. When I learned about my mom's diagnosis, I threw that effort out of my schedule to learn about cancer. I never completed that program, and that idea still lives in limbo pushed away by other projects.

On Mar 6, 1991, during one of our jogging-cum-brainstorming days with [Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak), someone tossed up the name *SuperMemo World*. Little did we know that four months later that would be the name of our company that has survived 27 years today.

顺便说一句，在我妈妈确诊的那一刻，我也在写一个程序来模拟记忆对环境的最佳反应。这是为了从数学上证明[记忆的双组分模型](https://supermemo.guru/wiki/Two_component_model_of_memory)是最适合生存的。当我得知我妈妈的诊断结果时，我把学习癌症的努力从我的日程中剔除了。我从来没有完成那个项目，那个想法仍然被其他项目搁置。

1991年3月6日，在我们与[Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)进行一次慢跑兼头脑风暴的日子里，有人想出了一个名字*SuperMemo World*。我们几乎不知道，四个月后，我们公司的名字就变成了今天这个公司已经存在了27年。

On Mar 12, 1991, I made my first [repetitions](https://supermemo.guru/wiki/Repetition) with the new algorithm in SuperMemo 6 while my mom rested on her deathbed. A week later, she died peacefully in sleep at the young age of 70. In similar circumstances, the usual picture involves family meetings, mourning, funeral, and a whole host of traditions with roots in religion that I could never accept as rational. Instead, 9 hours after my mom's death, I worked on a better method for a fast approximation of the [OF matrix](https://supermemo.guru/wiki/OF_matrix). In that work, I capitalized on the job I once did for ZX Spectrum. I would employ linear regression along the [difficulty](https://supermemo.guru/wiki/Difficulty) columns of the matrix, and negative exponential regression along the [repetition](https://supermemo.guru/wiki/Repetition) rows. Years later, I found that power regression is more appropriate for the latter. Only [Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8) developed four years later would make a full use of those ideas. However, I mention it mostly to illustrate how hard work, and productivity can work great as a remedy against gloom and possible depression. At that time, I discovered that the impact of an emotional trauma follows a [circadian](https://supermemo.guru/wiki/Circadian) curve. I would work hard in the morning, but the gloom would keep creeping back to my mind in the evening. [Sleep](https://supermemo.guru/wiki/Sleep) would be the liberation, and the best anti-depressant. From those early days, I am a firm believer in the idea that sleep and learning carry a [solution to the problem of depression](https://supermemo.guru/wiki/Learning_and_depression), however, I never truly had a chance to work on it. It would help if I suffered a bit myself, but either I have some good resilience endowment, or, more likely, I instinctively employ the tools of good sleep and high productivity at hard times. Ever since [Sapolsky](https://en.wikipedia.org/wiki/Robert_Sapolsky) called depression the "worst disease in the world", I wanted to find a prescription for preventing depression. I sense there is a simple formula. Perhaps that naive childlike optimism itself is part of the solution?

1991年3月12日，当我妈妈躺在病床上休息的时候，我用SuperMemo 6中的新算法进行了我的第一次[重复](https://supermemo.guru/wiki/Repetition)。一周后，她在睡梦中平静地去世，享年70岁。在类似的情况下，通常的画面包括家庭聚会、哀悼、葬礼，以及一大堆根植于宗教的传统，而我永远无法接受这些传统是理性的。相反，在我母亲去世9个小时后，我找到了一种更好的方法，可以快速逼近[of matrix](https://supermemo.guru/wiki/OF_matrix)。在这项工作中，我利用了我曾经为ZX Spectrum做过的工作。我将使用线性回归沿着[困难](https://supermemo.guru/wiki/Difficulty)列的矩阵，和负指数回归沿着[重复](https://supermemo.guru/wiki/Repetition)行。几年后，我发现权力回归更适合后者。只有在四年后开发的[Algorithm SM-8](https://supermemo.guru/wiki/Algorithm_SM-8)才能充分利用这些思想。然而，我提到它主要是为了说明努力工作和提高工作效率是如何有助于消除忧郁和可能的抑郁的。那时，我发现情感创伤的影响遵循一个[昼夜节律](https://supermemo.guru/wiki/Circadian)曲线。早上我会努力工作，但到了晚上，忧郁又会不断地爬上我的心头。[睡眠](https://supermemo.guru/wiki/Sleep)是一种解放，也是最好的抗抑郁药。从早期开始，我就坚信睡眠和学习可以解决抑郁的问题，然而，我从来没有真正的机会去解决这个问题。如果我自己受点苦或许会有所帮助，但我要么拥有良好的适应力天赋，要么(更有可能的是)在困难时期本能地利用好睡眠和高效率的工具。自从[Sapolsky](https://en.wikipedia.org/wiki/Robert_Sapolsky)把抑郁症称为“世界上最糟糕的疾病”以来，我就想找到预防抑郁症的处方。我觉得有一个简单的公式。也许这种天真幼稚的乐观主义本身就是解决方案的一部分?

On Apr 13, 1991, we decided that [SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2) should be released as freeware. We hoped it might educate potential users abroad about the power of [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition). However, initially, we had to send out diskettes with free SuperMemo at our own cost. Only in 1993, we uploaded SuperMemo to a local BBS called "Onkonet". It would take some more years before we could upload future versions to Simtel and freeware sites. That freeware idea had an interesting side effect: by the end of the year, it was clear: people would start using the program and then give up. This was a hint of an inherent problem with [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition): poor motivation resulting from poor skills would produce a high drop out rate. We also heard that others would try to sell SuperMemo 2 as if this was a commercial product.

在1991年4月13日，我们决定[SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2)应该作为免费软件发布。我们希望它能让国外的潜在用户了解[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)的力量。然而，一开始，我们不得不自费送出带有SuperMemo的免费磁盘。直到1993年，我们才把SuperMemo上传到当地一个叫做“Onkonet”的BBS上。我们还需要几年的时间才能把未来的版本上传到Simtel和免费软件网站上。免费软件的想法产生了一个有趣的副作用:到今年年底，很明显:人们会开始使用这个程序，然后放弃。这暗示了[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)的一个固有问题:技能差导致的动机差会导致高辍学率。我们还听说有些人试图把SuperMemo 2当成商业产品来销售。

On May 2, 1991, I implemented the option for setting the requested [forgetting index](https://supermemo.guru/wiki/Forgetting_index) in SuperMemo 6. On July 5, 1991, [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) was born. One of the first investments was a PC with a hard disk that would finally help me move away from the slow era of floppy disks.

On Nov 23, 1991: SuperMemo was announced as the finalist of *Software for Europe* competition. This saved [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World). This also gave [spaced repetition](https://supermemo.guru/wiki/Spaced_repetition) a good start.

1991年5月2日，我实现了在SuperMemo 6中设置请求的[遗忘索引](https://supermemo.guru/wiki/Forgetting_index)的选项。1991年7月5日，[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)诞生。第一批投资之一是有硬盘的个人电脑，这将最终帮助我摆脱软盘的缓慢时代。

1991年11月23日:SuperMemo被宣布为欧洲软件大赛的决赛。这保存了[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)。这也给了[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)一个好的开始。

## Slow start of commercial SuperMemo

## SuperMemo缓慢的商业化起步

When we set up [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) with [Krzysztof Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak) on Jul 5, 1991, the future looked so bright we needed to buy shades. The earth is populated with highly intelligent people who all need to learn things. This whole human population was our market. The only problem was how to convince all those smart people that two poor students educated behind the Iron Curtain got anything of value to offer. We could not have used the web for that job. [SuperMemo](https://supermemo.guru/wiki/SuperMemo) is older than the web itself. We could not afford advertising for lack of capital. There was no venture capital culture in Poland in 1991. All we could do is put the first few copies of SuperMemo in file folders and place them on shelves of nearby computer shops. As we aimed at global domination, we did not even have a manual in Polish. Instead of first sales, we had a long summer of silence and creeping doubts.

当我们在1991年7月5日与[Krzysztof Biedalak](https://supermemo.guru/wiki/SuperMemo_World)一起建立了[SuperMemo World](https://supermemo.guru/wiki/Krzysztof_Biedalak)的时候，未来看起来如此光明，我们需要购买墨镜。地球上有很多非常聪明的人，他们都需要学习。这整个人口就是我们的市场。唯一的问题是如何说服那些聪明人，让他们相信两个在铁幕后面受教育的穷学生能提供任何有价值的东西。我们不可能利用网络来完成这项工作。[SuperMemo](https://supermemo.guru/wiki/SuperMemo)比网络本身还要古老。由于缺乏资金，我们不能做广告。1991年，波兰还没有风险投资文化。我们所能做的就是把最初的几份SuperMemo放在文件夹里，放在附近电脑商店的货架上。由于我们的目标是在全球占据主导地位，我们甚至没有波兰语的手册。我们没有进行第一次销售，而是经历了一个漫长的沉默和令人毛骨悚然的怀疑的夏天。

[![The "box" uses in selling SuperMemo 5 for DOS](https://supermemo.guru/images/thumb/6/62/SuperMemo-5-for-DOS-box.png/600px-SuperMemo-5-for-DOS-box.png)](https://supermemo.guru/wiki/File:SuperMemo-5-for-DOS-box.png)

> ***Figure:** In 1991, we delivered the first copies of SuperMemo 5 for DOS to shops in Poznan (Poland) in pink folders with a sticker. The manual did not include a translation to Polish. Amazingly, we found a few buyers. The first sale took place some time between September 9 and 11, 1991 in the computer shop Axe Prim, which no longer exists (the picture is a reconstruction on the basis of original folders and stickers)*
>
> ***图片：**1991年，我们把第一批DOS超级备忘录(SuperMemo 5 for DOS)用带贴纸的粉红色文件夹寄给了波兰波兹南(Poznan)的商店。手册中没有包含波兰语的翻译。令人惊讶的是，我们找到了一些买家。第一次出售发生在1991年9月9日至11日之间，地点是电脑商店Axe Prim，现在已经不存在了(图片是在原有文件夹和贴纸的基础上重建的)*

Why was it hard to sell the first copy? I can reconstruct the scenario from the words of one of our first customers who actually visited a shop and had a look at the first SuperMemo displayed in public. On a shelf with computer programs, along with shiny boxes from Microsoft, he noticed a shabby folder with enticing words: "***Your breakthrough speed-learning software***". He picked up the folder and opened a manual, which was a stack of poorly xeroxed pages in English. With lofty words, he read a story that defied belief. It was all too good to be true. Faster learning, great retention, new scientific method, a little cost in time, etc. He did not contemplate an investment, the package was pretty costly (around $100, which was a lot in Poland 1991), however, he approached the salesperson to find out who the people behind SuperMemo were. The owner of the shop knew SuperMemo pretty well and explained. The story started looking credible. The customer never forgot the episode. A few months later, he heard of SuperMemo from some local journal and became one of the first paying customers. His registration coupon arrived in January 1992, and the history of his upgrades says he stayed with SuperMemo for decades and now his son is one of the regular customers.

为什么第一本很难卖?我可以从我们的第一批顾客的话语中重建这个场景，他们实际去了一家商店，并看到了第一个公开展示的SuperMemo。在一个放着电脑程序的架子上，还有一些微软(Microsoft)闪闪发光的盒子，他注意到一个破旧的文件夹，上面写着一些诱人的话:“***你那突破性的快速学习软件***”。他拿起文件夹，打开了一本手册，那是一叠复印得很差的英文手册。他用崇高的语言，读了一篇与信仰相悖的故事。这一切好得令人难以置信。学习速度快，记忆力好，有新的科学方法，时间成本低等等。他没有考虑过投资，因为这个套餐非常昂贵(大约100美元，这在1991年的波兰是一大笔钱)，然而，他找到销售人员，想知道SuperMemo背后的人是谁。店主很了解SuperMemo，并解释道。故事开始显得可信。这位顾客永远不会忘记这段插曲。几个月后，他从当地的一家杂志上听说了SuperMemo，并成为了第一批付费用户之一。他的登记优惠券在1992年1月到达，他的升级历史表明，他在SuperMemo呆了几十年，现在他的儿子是常客之一。

However, back in summer 1991, we had no sales and by fall, everyone except for myself started having serious doubts. Not about SuperMemo, but about the viability of the business.

It should help to know how we have met. With [Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak), we were friends since forever. I attended a school with his brother, we lived 200 meters apart, and passed exams for the same year of computer science at the [University of Technology in Poznan](https://en.wikipedia.org/wiki/Poznań_University_of_Technology). I cannot say how I convinced Biedalak that SuperMemo is great. We have just been too close, and he has always been in the circle. This part was easy. [Tomek Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn) was one of the first great believers in SuperMemo. He was also a great programmer, and a great inspiration. He grasped the idea instantly. He wrote two versions of SuperMemo himself: for Atari 800 in 1988, and for Atari ST in 1989. In January 1989, he even sold 10 copies of SuperMemo 2 using an advert in one of the computer journals: Komputer. I presume, he did not recover the invested money or he would sure try the trick again. Upon graduation, Kuehn already had his own business: a computer shop. This shop was also one of the first to present SuperMemo to its customers. His partner and a friend was [Marczello Georgiew](https://supermemo.guru/wiki/Marczello_Georgiew) who did not need much convincing either. Georgiew joined the team. Last but not least, I met [Janusz Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski) during GRE exams in Budapest in 1990. A great mathematical mind, he might be the fastest convert to SuperMemo ever. During our train trip back to Poland, I mentioned SuperMemo. He was instantly captivated. A few days later, he was already an enthusiastic user of [SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2) (as of Jun 13, 1990). In our company rap anthem, we sang "*we are the guys who sell SuperMemo*". It was very hard to convince people that [SuperMemo](https://supermemo.guru/wiki/SuperMemo) works, but the guys on the team have always been enthusiastic.

然而，在1991年的夏天，我们没有销售，到了秋天，除了我，每个人都开始有严重的怀疑。不是关于SuperMemo，而是关于业务的生存能力。

知道我们是怎么认识的应该会有帮助。与[Biedalak](https://supermemo.guru/wiki/Krzysztof_Biedalak)，我们是永远的朋友。我参加了一个学校和他的兄弟,我们相隔200米,通过考试的一年计算机科学[波兹南科技大学](https://en.wikipedia.org/wiki/Poznań_University_of_Technology)。我不能说我是如何说服比达拉克相信超级备忘录是伟大的。我们只是太亲近了，他一直都在圈子里。这部分很简单。[Tomek Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn)是最早相信超级备忘录的人之一。他也是一个伟大的程序员，也是一个伟大的灵感。他立刻领会了这个意思。他自己写了两个版本的SuperMemo: 1988年为Atari 800, 1989年为Atari ST。1989年1月，他甚至在计算机杂志《Komputer》上刊登广告，卖出了10本SuperMemo 2。我想，他没有收回投资的钱，否则他肯定会再试一次。毕业时，库恩已经有了自己的生意:一家电脑店。这家商店也是最早向顾客展示SuperMemo的商店之一。他的搭档和朋友是[Marczello Georgiew](https://supermemo.guru/wiki/Marczello_Georgiew)，他也不需要太多的说服。乔治加入了这个团队。最后但并非最不重要的是，我在1990年布达佩斯的GRE考试期间认识了[Janusz Murakowski](https://supermemo.guru/wiki/Janusz_Murakowski)。一个伟大的数学头脑，他可能是最快的转换到SuperMemo有史以来。在我们回波兰的火车旅行中，我提到了SuperMemo。他一下子就被迷住了。几天后，他已经是[SuperMemo 2]的狂热用户(1990年6月13日)。在我们公司的说唱歌曲中，我们唱的是“*我们是销售SuperMemo的人*”。很难让人们相信[SuperMemo](https://supermemo.guru/wiki/SuperMemo)是有效的，但是团队里的人一直都很热情。

By November 1991, the enthusiasm was thawing. If we continued without success, we would have gradually lost the team in proportion to their involvement and passion. With a few more months, the company might have died. SuperMemo would not have died. I would certainly look for a buyer, or continue one way or another. I was too tied to the product. I used it myself, and all my knowledge was invested in my databases. I might have thought of returning to the idea of a PhD in the US. In the same way as I was able to combine work at the university in the Netherlands in 1989 with programming "after hours", I would probably continue until some breakthrough, e.g. on the web. Perhaps it would be an open source product? Luckily, Dr Wojciech Makalowski of the Department of Biopolymer Biochemistry suggested we submit SuperMemo for *Software for Europe* competition. By some miraculous stroke of good luck, we qualified for the final, and this was instantly noticed by the Polish media, esp. computer journals. As of that point, SuperMemo had an easy ride with the Polish press that became more and more intrigued. [Andrzej Horodenski](https://supermemo.guru/wiki/Andrzej_Horodenski) was [the first journalist to write about SuperMemo](http://www.super-memory.com/articles/horod.htm) (Computer World 1992). [Pawel Wimmer was the second](https://supermemo.guru/wiki/Pawel_Wimmer:_Praising_SuperMemo._Ex_Occidente_lux). Wimmer remained faithful to this very day, and he actually used [SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2), which he probably received from [Tomasz Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn) at the time of his KOMPUTER journal advert in 1989.

1.5 years after being set up, [SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) had finally become profitable. Not bad.

[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World) was a fantastic set up from the getgo. We had no injection of venture capital in Poland in 1991, so we had to pull ourselves by our own bootstraps by selling, what others considered to be "snake oil". We might have easily failed, but we survived by the sheer power of passion, belief, and a big stroke of good luck.

到1991年11月，这种热情开始消退。如果我们继续不成功，我们就会逐渐失去这个团队，因为他们的参与和热情。再过几个月，公司可能就完蛋了。超级备忘录是不会死的。我当然会寻找一个买家，或继续这样或那样。我太沉迷于产品了。我自己使用它，我所有的知识都投入到我的数据库中。我可能会考虑回美国读博士。就像1989年我在荷兰大学的工作和“业余时间”的编程结合起来一样，我可能会继续工作直到一些突破，比如在网络上。也许它会是一个开源产品?幸运的是，生物聚合物生物化学系的沃伊切赫·马卡洛夫斯基博士建议我们提交SuperMemo，用于欧洲软件竞赛。由于奇迹般的好运，我们进入了决赛，这立刻引起了波兰媒体，特别是计算机杂志的注意。从那时起，SuperMemo在波兰媒体的关注下变得越来越有趣。[Andrzej Horodenski](https://supermemo.guru/wiki/Andrzej_Horodenski)是[第一个写关于超级备忘录的记者](http://www.super-memory.com/articles/horod.htm) (Computer World 1992)。(https://supermemo.guru/wiki/Pawel_Wimmer:_Praising_SuperMemo._Ex_Occidente_lux)直到今天，Wimmer仍然保持着他的忠诚，他在1989年的《KOMPUTER journal》广告中使用了[SuperMemo 2](https://supermemo.guru/wiki/SuperMemo_2)，这可能是他从[Tomasz Kuehn](https://supermemo.guru/wiki/Tomasz_Kuehn)那里收到的。

成立1.5年后，[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)终于开始盈利了。不坏。

[SuperMemo World](https://supermemo.guru/wiki/SuperMemo_World)是一个奇妙的设置从getgo。1991年，我们在波兰没有得到风险投资的注入，所以我们只能靠出售自己的产品来维持生存，而其他人认为这是“蛇油”。我们可能很容易失败，但我们靠着激情、信念和好运的力量活了下来。

## Origins of Algorithm SM-6

## 算法SM-6的起源

Algorithm SM-6 was first used in SuperMemo 6 (1991), however, it kept evolving in SuperMemo 7 (1992). There has never been the SM-7 version despite multiple changes introduced in the Windows version. Most notably, as of 1994, the exponential function was used to approximate [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) in SuperMemo 7 for Windows. [OF matrix](https://supermemo.guru/wiki/OF_matrix) approximations have also been improved over time.

算法SM-6最早在SuperMemo 6(1991)中使用，但在SuperMemo 7(1992)中不断演进。尽管在Windows版本中引入了多个更改，但从未有过SM-7版本。最值得注意的是，在1994年，指数函数被用来近似[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)。[OF matrix](https://supermemo.guru/wiki/OF_matrix)近似值也随着时间得到了改进。

[![SuperMemo 7 for Windows (1992) displaying a forgetting curve based on averages](https://supermemo.guru/images/thumb/a/a9/Forgetting_curve_in_SuperMemo_7.png/710px-Forgetting_curve_in_SuperMemo_7.png)](https://supermemo.guru/wiki/File:Forgetting_curve_in_SuperMemo_7.png)

> ***Figure:** SuperMemo 7 for Windows was written in 1992. As of Sep 03, 1992, it was able to display user's forgetting curve graph. The horizontal axis labeled U-Factor corresponded with days in this particular graph. The kinks between days 14 and 20 were one of the reasons it was difficult to determine the nature of forgetting. Old erroneous hypotheses were hard to falsify. Until the day 13, forgetting seemed nearly linear and might also provide a good exponential fit. It took two more years of data collecting to find answers (source: SuperMemo 7: User's Guide)*
>
> ***图片：** SuperMemo 7是1992年为Windows编写的。从1992年9月3日开始，它可以显示用户的遗忘曲线。标记为U-Factor的横轴与该图中的天数对应。第14天和第20天之间的纠结是很难确定遗忘性质的原因之一。旧的错误假设很难证伪。直到第13天，遗忘看起来几乎是线性的，也可能提供一个良好的指数拟合。为了找到答案，他们又花了两年多的时间收集数据



[![SuperMemo 7 for Windows (1994) displaying a forgetting curve approximated with the exponential function](https://supermemo.guru/images/f/f5/Forgetting_curve_approximated_with_exponential_function_%281994%29.gif)](https://supermemo.guru/wiki/File:Forgetting_curve_approximated_with_exponential_function_(1994).gif)

> ***Figure:** SuperMemo 7 for Windows (1994) displaying a forgetting curve approximated with an exponential function. Vertical axis represents recall in percent. Horizontal axis corresponds with time represented by U-Factor. With 21,000 repetition cases, the curve finally looks regular enough to hypothesize about the underlying cause of forgetting*
>
> ***图片：** SuperMemo 7 for Windows(1994)显示了一个近似于指数函数的遗忘曲线。纵轴代表召回率。横轴表示时间，U-Factor表示时间。在21000个重复的案例中，这条曲线看起来足够规则，可以用来假设遗忘的潜在原因*

The most important new job of Algorithm SM-6 was to collect data on the rate of forgetting. [Forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) make it easy to accurately determine [optimum intervals](https://supermemo.guru/wiki/Optimum_interval). This eliminated the need for a slow and inaccurate bang-bang approach of Algorithm SM-5:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

This text was part of: "*Economics of Learning*" by [Piotr Wozniak](https://supermemo.guru/wiki/Piotr_Wozniak) (1995)

算法SM-6最重要的新工作是收集关于遗忘率的数据。[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)使准确确定[最佳间隔](https://supermemo.guru/wiki/Optimum_interval)变得容易。这消除了对SM-5算法的缓慢和不准确的“砰砰”方法的需要:

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

本文是[Piotr Wozniak](https://supermemo.guru/wiki/Piotr_Wozniak) 的《*学习经济学》的一部分(1995)

In [Algorithm SM-5](https://supermemo.guru/wiki/Algorithm_SM-5), the process of determining the value of a single entry of the matrix of optimal factors looked as follows (see before):

1. Set the initial value to an average optimal factor value (OF) obtained in previous experiments
2. If the grade produced by the entry in question was (1) greater than the desired value then increase the value of OF, (2) less than the desired value then decrease OF, or (3) equal the desired value then do not change OF

在[Algorithm SM-5](https://supermemo.guru/wiki/Algorithm_SM-5)中，确定最优因子矩阵中单个条目的值的过程如下(见前):

1. 将初始值设为之前实验得到的平均最优因子值(OF)
2. 如果该题项产生的分数是(1)大于期望值，则增加的值为，(2)小于期望值，则减少，或(3)等于期望值，则不改变

The above approach shows that the optimum value of OF could be reached only after a great number of repetitions, and what is worst, the greater the ordinal number of a repetition, the longer it would take to execute the modification-verification cycle (i.e. the cycle in which an OF entry is changed, and verified upon scheduling another repetition with a correspondingly long interval).

上面的方法表明,之后才可以达到最优值的大量重复,什么是最坏的情况下,重复的序数越大,时间越长,需要执行modification-verification周期(即改变的周期中,一个条目,并验证调度相应的另一个重复长间隔)。

**Introducing the concept of the forgetting index** **介绍遗忘指数的概念**

The novelty of Algorithm SM-6 is to approximate the slope of the [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve) corresponding to a given entry of the matrix of optimal factors, and compute the new value of the relevant optimal factor directly from the approximated curve. In other words, no modification-verification cycle is necessary in Algorithm SM-6 because of establishing the deterministic relationship between the forgetting curve and the optimum inter-repetition interval. The modification of the optimal factor occurs immediately after a repetition upon approximating the new forgetting curve derived from data that include the grade provided in the recent response. This modification not only made it possible to greatly accelerate the process of determining the optimum values of the matrix of optimal factors, but also provided a means for establishing the desired level of knowledge [retention](https://supermemo.guru/wiki/Retention) that will be reached in the course of the learning process (see an exemplary [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve)).

算法SM-6的新颖之处在于对最优因子矩阵中给定条目对应的[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)的斜率进行近似处理，并直接从近似曲线中计算出相关最优因子的新值。也就是说，在SM-6算法中，由于建立了遗忘曲线和最优重复间隔之间的确定性关系，所以不需要修改-验证循环。从最近的答复中所提供的分数的数据得出的新的遗忘曲线，经过一次重复之后，立即对最佳因素进行修改。这一修改不仅能大大加快的过程中确定最优的最佳值矩阵的因素,但也提供了一种方法来建立所需的水平的知识[保留](https://supermemo.guru/wiki/Retention)将达到课程的学习过程(见一个模范[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)。

The desired level of knowledge [retention](https://supermemo.guru/wiki/Retention) is determined by the proportion of [items](https://supermemo.guru/wiki/Item) that are not remembered at [repetitions](https://supermemo.guru/wiki/Repetition). This proportion is called the [forgetting index](https://supermemo.guru/wiki/Forgetting_index) (items are classified as remembered or forgotten on the basis of [grades](https://supermemo.guru/wiki/Grade) provided by the student in self-assessment of his or her progress).

所需的知识水平[retention](https://supermemo.guru/wiki/Retention)是由[items](https://supermemo.guru/wiki/Item)在[repetitions](https://supermemo.guru/wiki/Repetition)时未被记住的比例(https://supermemo.guru/wiki/Repetition)决定的。这一比例被称为[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)(根据学生对自己进步的自我评估提供的[成绩](https://supermemo.guru/wiki/Grade)将项目分类为记忆或遗忘)。



[![An exemplary forgetting curve plotted in the course of repetitions (over 40,000 repetition cases recorded](https://supermemo.guru/images/thumb/0/08/Forgetting_curve_in_SuperMemo_8.jpg/600px-Forgetting_curve_in_SuperMemo_8.jpg)](https://supermemo.guru/wiki/File:Forgetting_curve_in_SuperMemo_8.jpg)

> ***Figure:** An exemplary forgetting curve plotted by SuperMemo 8 in the course of repetitions (over 40,000 repetition cases recorded). R-Factor indicates that exponential regression points to the optimum interval of 7.146 days. This is then smoothed up via the OF matrix to 6.176 days. SuperMemo would use the first interval of 6 days in this case (if to ignore random dispersal)*
>
> ***图片**：在重复的过程中，SuperMemo 8绘制了一条典型的遗忘曲线(记录了超过40000例重复)。r因子表明指数回归指向7.146天的最优区间。然后这是平滑的通过矩阵的6.176天。SuperMemo将在这种情况下使用6天的第一个间隔(如果忽略随机散布)*

In the figure presented above, the lapse of time is represented by the [interval](https://supermemo.guru/wiki/Interval) in days. The vertical axis represents knowledge [retention](https://supermemo.guru/wiki/Retention) stated as percentage. The horizontal line located at the retention level of 90% determines the requested [forgetting index](https://supermemo.guru/wiki/Forgetting_index), i.e. the desired proportion of items that should be forgotten at the moment of repetition. The optimum interval will then naturally come at the cross-section of the requested forgetting index line with the [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve). In the example above, the [optimum interval](https://supermemo.guru/wiki/Optimum_interval) equals seven days. The presented forgetting curve has been plotted on the basis of 40489 recorded repetition cases. See later in the text for explanation of the values [R-Factor](https://supermemo.guru/wiki/R-Factor) (RF), [O-Factor](https://supermemo.guru/wiki/O-Factor) (OF), etc.

Because of the highly irregular nature of the matrix of optimal factors computed directly from the , in Algorithm SM-6, the matrix used in[spacing repetitions](https://supermemo.guru/wiki/Spaced_repetition)represents a smoothed version of the so-called matrix of retention factors (matrix RF), which is derived directly from forgetting curves corresponding to particular entries of the[matrix OF](https://supermemo.guru/wiki/OF_matrix)

在上图中，以天为单位的[interval](https://supermemo.guru/wiki/Interval)表示时间的流逝。纵轴代表知识[保留率](https://supermemo.guru/wiki/Retention)，以百分比表示。保持水平为90%的水平线决定了被请求的[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)，即在重复时应该被遗忘的项目的期望比例。最佳时间间隔自然会出现在请求的遗忘指数与[遗忘曲线]的横截面上(https://supermemo.guru/wiki/Forgetting_curve)。在上面的例子中，[最佳时间间隔](https://supermemo.guru/wiki/Optimum_interval)等于七天。根据40489例重复记录，绘制了遗忘曲线。有关[R-Factor](https://supermemo.guru/wiki/R-Factor) (RF)、[O-Factor](https://supermemo.guru/wiki/O-Factor) (of)等值的解释，请参阅后面的文本。

因为高度不规则的性质矩阵的最优因素直接计算,算法SM-6,使用的矩阵[间隔重复](https://supermemo.guru/wiki/Spaced_repetition)是一个平滑的所谓的保留因子矩阵(矩阵RF),这是直接来自遗忘曲线对应于特定的条目(矩阵)(

## Algorithm SM-6

## 算法 SM-6

The description of the algorithm below is taken with some clarifications from my [PhD Thesis](https://supermemo.guru/wiki/Economics_of_learning), and refers to the status quo for 1994:

Archive warning: [Why use literal archives?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

以下算法的描述来自我的[PhD Thesis](https://supermemo.guru/wiki/Economics_of_learning)中的一些说明，并参考了1994年的现状:

档案警告:[为什么使用文字档案?](https://supermemo.guru/wiki/Why_use_literal_archives%3F)

This text was part of: "*Economics of Learning*" by [Piotr Wozniak](https://supermemo.guru/wiki/Piotr_Wozniak) (1995)

1. The learned knowledge is split into smallest possible pieces called items
2. Items are formulated in the question-answer form
3. Items are memorized by means of a self-paced drop-out technique, i.e., by responding to the asked questions as long as it takes to provide all correct answers
4. After memorizing an item, the first repetition is scheduled after an interval that is the same for all of the items. Its value is determined by the desired level of knowledge retention, which in turn can be converted into an interval by using an average [forgetting curve](https://supermemo.guru/wiki/Forgetting_curve) taken from an average database of an average student ([Wozniak 1994a](https://supermemo.guru/wiki/ANE1994)). The desired retention is specified by means of the so-called [forgetting index](https://supermemo.guru/wiki/Forgetting_index), which corresponds to the proportion of items forgotten at repetitions (to learn how to compute retention from the forgetting index, and vice versa). Note, that the first interval may be randomly shortened or lengthened for the sake of speeding up the optimization process (varying intervals increase the accuracy of approximating the forgetting curve).
5. The first interval is computed as for an average student and an average database. However, as soon as the recorded value of the forgetting index deviates from the requested level, the length of the first interval is modified accordingly. The new value of the interval is derived from the approximation of the negatively exponential forgetting curve plotted in the course of repetition. With each repetition score recorded, the plot becomes more and more accurate and the used value of the optimum inter-repetition interval settles at the point that ensures the selected level of knowledge retention. After each repetition, the student produces a grade, which determines the accuracy and easiness of reproducing the correct answer.
6. On the basis of the grades, items are classified into difficulty categories. Their difficulty is reestimated in each successive repetition. The difficulty of each item is characterized by the earlier mentioned [E-factors](https://supermemo.guru/wiki/E-Factor) (E stands for "easiness"). E-factors are equal to 2.5 for all items on the entry to the learning process, and modified after subsequent repetitions. For example, grades above four result in slightly increasing the E-factor (good grades indicate easy items), while grades below four reduce the E-factor. Historically, E-factors were used to determine how many times intervals should increase in successive repetitions of items of a given difficulty. At present, E-factors are only used to index the matrices of optimal factors and retention factors, and may bear little relevance to the actual interval increase.
7. Different optimal intervals are applied to items of different difficulty.
8. Different intervals are applied to items that have been repeated a different number of times.
9. The function of optimal intervals is constantly modified in order to produce the desired knowledge retention determined by the forgetting index. In other words, the algorithm will detect how well the student copes with repetitions and adjust the length of inter-repetition intervals accordingly.
10. The function of optimal intervals is represented as the matrix of optimal factors, OF-matrix in short, defined as follows:
11. Matrix of optimal factors is produced by smoothing the so-called **matrix of retention factors**, RF matrix in short. Matrix of retention factors is defined in the same way as the [matrix of optimal factors](https://supermemo.guru/wiki/OF_matrix).
12. Entries of the matrix of retention factors are intended to estimate the values of the entries of the matrix of optimal factors. Each optimal factor corresponds to an optimal interval that produces the desired retention at repetition (determined by the requested forgetting index). Each entry of the matrix of retention factors corresponds to a different value of E-factor and repetition number
13. Entries of the matrix of retention factors, called **R-factors**, are computed from [forgetting curves](https://supermemo.guru/wiki/Forgetting_curve) whose shape is sketched on the basis of the history of repetitions
14. The lapse of time on the forgetting curve graph is measured by the so-called **U-factor**, which is the ratio of the current and the previous interval, except for the first repetition where U-factor equals the interval in days (as in [Figure](https://supermemo.guru/wiki/History_of_spaced_repetition_(print)#forgetting_curve_in_SM8)). The record of repetitions makes it possible to compute retention for different values of U-factor. The graph of the retention plotted versus the lapse of time (U-factor) represents a forgetting curve. The cross-section of the forgetting curve with the desired retention level determines the optimum R-factor, which, upon smoothing the matrix of retention factors, yields the optimum O-factor
15. Each difficulty category and repetition number has its own record of repetitions used to sketch a separate forgetting curve. In other words, different intervals will be used for items of different difficulty, and for items repeated a different number of times.
16. Intervals used in learning, including the first interval, are slightly dispersed round the optimal value in order to increase the accuracy of forgetting curve sketching, and consequently, to increase the convergence rate of the optimization procedure. By slightly dispersing intervals, the approximation of the forgetting curve will use a more scattered set of points on the graph

这篇文章是[Piotr Wozniak]的“学习经济学”的一部分(https://supermemo.guru/wiki/Piotr_Wozniak) (1995)

1. 所学的知识被分解成尽可能小的片段，称为项目
2. 项目是在问答形式中制定的
3. 项目是通过一种自定步速的退出技术来记忆的。，只要回答了所问的问题，就可以提供所有正确答案
4. 在记住一个项目之后，第一次重复安排在一个对所有项目都相同的间隔之后。其价值是由知识保留所需的水平,进而可以转化为一个区间通过使用平均(遗忘曲线)(https://supermemo.guru/wiki/Forgetting_curve)从平均的平均学生数据库(沃兹尼亚克(1994)(https://supermemo.guru/wiki/ANE1994))。所需的保留是通过所谓的[遗忘指数](https://supermemo.guru/wiki/Forgetting_index)来指定的，它对应于在重复时忘记的项目的比例(学习如何从遗忘指数计算保留，反之亦然)。注意，为了加快优化过程，第一个区间可以随机缩短或延长(变化的区间增加了遗忘曲线逼近的准确性)。
5. 第一个时间间隔是针对一个普通学生和一个普通数据库计算的。但是，一旦遗忘指数的记录值偏离了所请求的水平，第一个间隔的长度就会相应地进行修改。新的时间间隔值是由在重复过程中绘制的负指数遗忘曲线的近似值得到的。随着每一个重复分数的记录，情节变得越来越准确，最佳重复间隔的使用值稳定在确保所选择的知识保留水平的点上。每重复一次，学生就会得到一个分数，这个分数决定了复述正确答案的准确性和难易程度。
6. 根据等级，项目被划分为难度类别。他们的困难是在每一次连续的重复中重新估计的。每个项目的难度都有前面提到的[E-factors](https://supermemo.guru/wiki/E-Factor) (E代表“容易”)。在学习过程中，所有条目的e -factor等于2.5，并在随后的重复中进行修改。例如，4分以上的成绩会导致e -因素略有增加(好成绩表示容易项目)，而4分以下的成绩则会降低e -因素。历史上，电子因素被用来决定在一个给定难度的项目的连续重复中间隔应该增加多少次。目前，e因子仅用于对最优因子和保留因子的矩阵进行索引，与实际的区间增长相关性不大。
7. 不同难度的项目采用不同的最优区间。
8. 对重复次数不同的项应用不同的间隔。
9. 通过对最优区间函数的不断修正，得到由遗忘指数确定的知识保留度。换句话说，该算法将检测学生处理重复的能力，并相应地调整重复间隔的长度。
10. 最优区间的函数表示为最优因子的矩阵，简而言之，矩阵的定义如下:
11. 通过平滑所谓的保留因子**矩阵，得到最优因子矩阵，简称RF矩阵。保留因子矩阵与[最佳因子矩阵]定义方法相同(https://supermemo.guru/wiki/OF_matrix)。
12. 保留因子矩阵的项是用来估计最优因子矩阵的项的值。每个最优因素对应一个最优区间，该区间在重复时产生所需的记忆(由请求的遗忘指数决定)。保留因子矩阵的每一项对应不同的e因子值和重复次数
13. 保留因子矩阵的条目，称为** r -factor **，由[遗忘曲线](https://supermemo.guru/wiki/Forgetting_curve)计算，其形状基于重复的历史*
14. *时间的流逝的遗忘曲线图表是衡量所谓的* *的u值* *,这是当前和过去的比例区间,除了第一个重复的u值=天的间隔(如(图)(https://supermemo.guru/wiki/History_of_spaced_repetition_(印刷)# forgetting_curve_in_SM8))。重复次数的记录使计算U-factor不同值的保留率成为可能。保留率随时间流逝(u -因素)的曲线图代表遗忘曲线。遗忘曲线的截面与期望的保留水平决定了最优的r因子，通过平滑保留因子矩阵，得到最优的o因子
15. 每个难度类别和重复次数都有自己的重复记录，用来绘制一个单独的遗忘曲线。换句话说，不同难度的项目和重复不同次数的项目将使用不同的音程。
16. 为了提高遗忘曲线作图的准确性，从而提高优化过程的收敛速度，将学习中使用的区间，包括第一个区间，略微分散在最优值周围。通过稍微分散的时间间隔，遗忘曲线的近似将使用图上更分散的点集