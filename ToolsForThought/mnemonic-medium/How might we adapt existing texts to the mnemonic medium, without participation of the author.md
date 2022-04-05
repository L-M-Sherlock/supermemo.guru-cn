# 没有作者参与时，我们如何将现有文本转化为助记媒介？

原文：[How might we adapt existing texts to the mnemonic medium, without participation of the author? (andymatuschak.org)](https://notes.andymatuschak.org/zvG5X4scr9mGCnR52dtkPGeHLBUntANhBvf)

[普及助记媒介似乎需要网络出版的普及](https://notes.andymatuschak.org/zLbzDQF4MLSUEgDKu16i2h9q1ea8jC5crTV)。此外，许多重要的书籍根本没有任何数字形式；许多人更喜欢硬拷贝书籍和电子墨水阅读器。技术受众将在很长一段时间内继续使用PDF。那[有声书](https://notes.andymatuschak.org/zhjve4ix3DcGqVGZn3a7FCP7bZTvzVR99fd)和视频呢？如果我们能在不牺牲现有媒介力量的情况下，将现有媒介「抬升」成助记媒介，那将是非常强大的。

下面的这些方法实际上都不是好的，但是也许对它们的迭代可能是好的呢？

## 「伴读」APP

你面前有一本打开的纸质书；你把手机放在它旁边，打开“记忆伴侣”应用程序。您扫描图书的条形码，它会显示一个目录表(可能出于法律原因进行了部分编辑)和页码选择器。你告诉应用程序你正在阅读第312页。屏幕上显示了一堆问题和一个大标题，上面写着：“在第314页的分隔处回答这些问题。”你开始阅读纸质书，突出显示和粘贴注释，然后在适当的地方用撞击提交问题。应用程序将移动到下一个断点，您可以继续阅读。

这种方法是一件巨大的杂物。它要求读者记住他们应该在哪里停下来，监控这一点，并在两种媒体之间来回切换。听起来很痛苦。我怀疑合规率会比Quantum Country低得多。

但这是一种非常灵活的方法，基本上可以适用于任何先前的媒体形式。它不需要作者/出版商合作，问题可以来自不同的制作人(相关：[有声读物是在各种各样的商业models](https://notes.andymatuschak.org/zbdNE8WLUE8SgBKvUgd8TCdQnmTj6CjJ94B)).下制作的

另外，分销渠道很糟糕：阅读一本书的人必须决定单独寻找周围的其他材料，检查我们的应用程序以获得支持，并可能为这些材料单独付费。在Twitter上对一本书/PDF的讨论并不会将人们引向这个同伴。没有任何有意义的网络效应。

## 网页图书浏览器扩展页面

对于已经在线托管的图书(如[由Numbers](https://notes.andymatuschak.org/zXBk7GLFDaxgd6oMsRd5Jdr17dnCtik3MQ8))，提供的[细胞生物学])，可以通过浏览器扩展来扩充它们。我不喜欢这样--这对用户来说是一个巨大的要求。如果我们可以将页面包装在IFRAME中并跨域操作它，那会很好，但是当然没有浏览器会允许这样做。

## 内容转换代理

通过添加额外的`<script>`标签，“非透明”web代理可以重新服务目标网页。至少对于新用户使用模式而言，这是一种实现与基于浏览器扩展的解决方案相同的结果的轻量级方法。您可以制作一个可链接的URL！

[Hypothes.is](https://notes.andymatuschak.org/z24wddcuZTB2YvHTA4LkZ759DhydyufhrzCh)使用其中的一种方法来使其可共享链接工作：via.subthe.is注入目标url。

此…实际上看起来挺可行的！

#实施注意事项

甚至还有一篇W3C文章！https://www.w3.org/TR/ct-guidelines/(这是“工作组说明”，而不是批准的文件)。

```

如果代理更改了响应，则：

1.必须增加警告214应用转换的HTTP头字段；

```

请参阅[警告codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Warning).

```

代理**应该**通过在包含URI“http://www.w3.org/ns/ct”的via HTTP报头字段中包含注释来指示它们转换内容的能力。

```

注意链接重写的安全问题：重写代理可能会意外地使两个不同的站点同源(即代理的站点)。这可能会引入漏洞。另外：

```

强烈建议不要截取HTTPS链路的做法。

如果代理重写HTTPS链接，它必须告知用户这样做的安全影响，并且必须提供绕过它并直接与服务器通信的选项。

..。

转发来自服务器的响应时，代理必须通知用户无效的服务器证书。

```

现在基本上所有的链接都是HTTPS，所以这或多或少相当于“不要重写链接”！或者至少：要“极其”小心。

另请参阅HTTP1.1RFC的[对中间transformations](https://datatracker.ietf.org/doc/html/rfc7230#section-5.7.2).的评论

```

转换200(OK)响应的有效载荷的代理还可以通过将响应状态代码更改为203(非权威信息)来进一步通知下游接收者已经应用了转换。

```

另请参阅此初步文档[内容转换横向1.0](https://www.w3.org/TR/2009/NOTE-ct-landscape-20091027/#d0e276)

## 自定义 PDF / EPUB 阅读器

我们可以制作自己的 PDF 或 EPUB 阅读器应用程序，将这些元素内联到现有的媒体形式中。或者它可能是一个基于 Web 的查看器，书签样式：在任何 PDF URL 前面加上 [“http://mnemonic.com”](http://mnemonic.xn--com-9o0a/)，以便以这种形式阅读它，等等。

在 DRM 仍然无处不在的情况下，为 EPUB 做这件事并不是真正可行的。合法购买的电子书无法在我们的阅读器中打开。因此，为电子书这样做需要我们成为一家电子书商店。真恶心。

这将是一项繁重的工作。这里的分销渠道问题很大。

老实说，处理PDF的一个更好的方法可能是通过无数的「PDF 到网页」工具中的一种。获取学术文档；将其转换为网络出版物；**然后**对其进行增强（例如，通过[把任意一个网页转化成助记媒介](https://notes.andymatuschak.org/z2hABbXxq3dz9XQ6bWrqLyModyC5EC2MXxNA)）。

## AR 眼镜

如果我们将来都戴AR眼镜，我们可以用各种有趣的方式神奇地增强书籍。太远了以至于不能认真考虑？如果有关苹果2022年推出眼镜的传言属实，AR覆盖可能很快就会成为相当主流的…