---
title: （译）使用开源项目，该做什么，不该做什么
date: 2016-04-24 20:16:52
categories:
- Developer
tags:
- Open Source
---

>这篇文章写于2007年，作者以Drupal为例讲如何使用开源项目，里面的观点到现在依然具有指导意义，讲得太好忍不住尝试翻译了一把，如有纰漏，还望指正。
>
>作者：[Laura Scott](http://pingv.com/about/people/laura-scott)
>译者：[Consen](http://consen.github.io/about)
>原文链接：[How to use open source (and how not to)](http://pingv.com/blog/laura/200702/how-to-use-open-source-and-how-not-to)

对于一个基于web的项目，走开源之路可以说是一种愉快且划算的方式。然而，如果你不懂开源的主要注意事项(dos and don'ts)，一个自由免费的开源网站很快就会变成昂贵棘手的负担。

随着开源软件变得越来越流行，越来越贴切非技术性人群和组织的需求。我们认为我们有必要提供一些基础背景介绍，对于一个web平台使用开源项目时，该做什么，不该做什么。

<!-- more -->

请往下读。。。

是商业方法，不是信仰
--------------------
It's a business methodology, not a religion

忘掉编程理想主义者夜以继日编写代码然后拱手相让这种形象。真正的开源世界是一个丰富且充满活力的经济领域，而且仍在发展壮大。采用免费的开源软件如Drupal是一种商业选择，有清晰明确的效益和成本。总的来说，作为一种商业方法，开源有它明显的优势。

有利的一面：

* 你拥有代码（遵循GPL协议）。
* 它是免费的。
* 你是自由的，自由去更改代码，自由去添加新功能，自由让任何人加入替你做事。

随之而来的是责任。你拥有运行你网站的代码，所以你得负责维护。但是你不需要支付任何专利软件许可费用，当然也不会有专利软件供应商来给你维护代码，意味着你需要自己维护网站，或者让其他人替你维护。

即使你不打算实现新的功能，你仍需要考虑周期性安全更新[Security advisories](https://www.drupal.org/security)（所有软件都要经历更新，开源软件也不例外）。

开源的真正绝妙之处，在于你不是在单枪匹马作战。。。

是社区，不是应用软件
--------------------
It's a community, not an application

和大多数开源项目一样，Drupal鲜活地展现出许许多多开发者的利益，他们相互共享协作代码，为了个人或集体的利益。你有成千上万的人在同一代码库上工作，排查相同的问题。当一个开发者解决了一个问题，整个社区成员都会受益。

**开源平台的整体理念不是有免费的代码可以获取，而是平台背后充满活力遍布全球的社区开发者，他们使其进化，成长，不断完善代码库，未来几年你都可以从中获益。**

这就意味着，尽管Drupal本身主要是一个网站内容管理的软件应用，然而明智的商业举措不是简简单单地把代码下载下来然后按照你的方式运行，而是要加入队伍成为社区一员。。。或者至少对项目保持关注，跟上进展。

结果就是，你不仅仅获取到了现在的Drupal，未来的Drupal同样属于你，你拿到的不仅仅是免费的应用软件，还有免费的升级更新。你拥有遍布世界各地的Drupal社区成员为你的代码库开发模块、代码升级和主题技术（developing modules and code upgrades and theming techniques），所有一切都供你使用，只要你跟上步伐。

只要你。。。

不更改核心代码
--------------
Don't hack the core

一旦你改了核心代码，即更改了系统基础程序代码，你创建了一个“分支”("fork", 加了引号，可能作者是想表达走了一条岔路），这是原有系统的一个变体而且是唯一的。尽管这种更改可能是诱人的，毕竟，这可能是一种更改特性和功能相对简单的方法（你拥有代码，有更改核心内容的任何权利），冒险走这条路的最终结局可能这是一个代价相当惨重的决策，因为你更改了核心代码，你变得孤立，又开始单枪匹马作战。

开源并不仅仅是一份静态代码，像成熟的果实等待采摘，更多是一个开源社区，你要加入，参与，并从中获益。如果你更改了核心代码，你实际上把你排除在社区之外。你将原地踏步，孤身一人，然而开源社区却在继续前行。

实际情况就是，没有一大帮开发者熟悉你独有的分支，你将不得不面对独自维护代码的现实。每一个bug修复，每一个安全更新，每一次变更，你都需要雇佣开发者去为你做（或者你自己做，如果你有技术和时间去做这样的努力）。

有很多方法修改Drupal来满足你的需要，但是更改核心代码并不是正确的方法。

这并不是说仅仅获取开源软件并切一个自己的分支一直走下去是邪恶的（"evil"）-- 有些人会有那样的主张 -- 但宁要切一个自己的分支，一开始就不会有看起来很明显的结果。

这样想一想。。。

是矢量，不是一个点
------------------
It's a vector, not a point

换句话说，开源项目在*前进*（"move"）。它们不是静止的。今天的Drupal和一个月前的Drupal比已经不同了。一年前的Drupal对于今天的Drupal用户来说几乎是陌生的。那是因为Drupal -- 总体来说所有开源项目 -- 在持续发展和完善。

![open source vector diamond](http://7xtc3e.com2.z0.glb.clouddn.com/how-to-use-open-source-and-how-not-to/open-source-vector-diamond-2.png)

这张示意图说明了这一点。把蓝色菱形区域看成是开发者在一个项目上的活跃度。当社区快要发布一个新版本时全球活跃度增加。一旦版本发布出去，开发还会持续一段时间，但随后开始停止，因为下一个更新、更好的版本在准备中。

由于每一个版本会被更新的版本替代，开发者的注意力不断转向新的事物。当这些发生时，使用老版本的人最终会依赖着越来越不受关注的代码，意味着不仅仅是更少的新模块，还有更少的bug修复，更少的安全关注。。。直到最终一个老版本越来越糟没有任何社区支持。在那时，你独自一人。。。

。。。除非你跟上来，做着必要的周期性更新。

好消息是更新会很容易，只要你的网站使用社区模块而且你的代码没有被更改（hacked, 见上)。

但是如果你的网站想要一些新功能，一些现有的Drupal核心和模块无法满足你需要的功能，怎么办？如果你不更改核心代码，是不是就意味着你不能定制Drupal？

根本不是这样。。。

模块化和重载
------------
Modularize and Override

Drupal是一个开放、可扩展的CMS，不更改核心代码不切分支就可添加新功能。你可以创建（或许已经为你创建好了）自定义模块，获得你要的功能，通过模板重载（template overrides），加上CSS样式，为你专有的网站，创建你期望的界面外观。

让我们假设你已经为你的网站创建了一些伟大的全新自定义模块。自然的诱惑是你把它当成专有的，秘密的。毕竟，难道不是你花钱做的模块让你的网站变得特别吗？

不见得。我来解释一下，因为到此，我们在采用开源的商业方法上迈向了另外重要的一步。。。

不要保密代码
------------
Don't keep custom code secret

抛开任何开源web软件平台，看看基于那些平台建立的各种各样的站点。你会发现少许站点如日中天，一部分站点发展很好，还有一大部分站点步履蹒跚（外加一大部分失败品，尽管可能你甚至没见过它们）。

很明显代码本身并没有成就一个网站，否则他们会同等成功。你的网站在于你创建的内容，你培养的社区，你从事的话题。否则所有运行Scoop的网站都会以同样的方式取得成功，所有运行Plone的网站都是一模一样的，等等。

**代码之于你的网站，就如字体之于一部小说，电影票之于一部电影：是一种到达目的地的方法，但它并不是目的地。**这不是一种宗教信仰（一些老的媒体和web 1.0之流会这么说）而是一种经济决策。这是在选择走一条路：**社区提供工具，你提供内容。**

因为你想要你的网站拥有的是*关注*(attention)。

正如[Michael H. Goldhaber的解释](http://goldhaber.org/blog/2006/08/30/the-attention-economy-hypothesis-in-brief/):

> 最先如此标准化大量生产的商品之一是金钱本身（以硬币的形式）。现在，金钱日益追随注意力。那些拥有大量注意力的人很容易获得金钱，只要他们想要。那些很少获得关注的人很难赚钱。

[Wandering Stan](http://wanderingstan.com/2007-01-08/google_and_the_third_age_of_computing)用这个例子做了阐释:

> * IBM卖给你硬件换取金钱。
> * Microsoft卖给你软件换取金钱。
> * Google把所有的东西给你免费用，但是把你的注意力卖给了广告商。

换句话说，代码本身不是网站。所以为什么要把代码变成秘密？**为什么不把你的代码分享出去，让社区帮你维护和改善它？**

当你自己开发了一些自定义代码（或者雇佣公司帮你做的），然后把代码私有起来，你就踏上了那条岔路，随之而来的是太多附加的压力和责任（见上）。

值得问下自己：把那个绝妙的自定义模块回馈给社区真的对你的网站有害吗？真的有可能其他人拿了你的自定义模块然后把你从谷歌地图上踢出局吗？

另外一方面，难道其他开发者给你的模块修复bug、打安全补丁和添加新功能，这样不好吗？你自己的网站不会从中受益吗？

重点在下面
----------
The bottom line is the bottom line

总结一下，重点来了，给你的web项目带来福利还是麻烦取决于你如何使用开源项目，记住：

1. 如果你更改核心代码，你最终会付出更大的代价。
2. 如果你不更新，你最终会付出更大的代价。
3. 如果你保密自定义模块，你最终会付出更大代价。
4. 反过来，如果你顺应潮流，忠于社区，尽所能回馈社区，开源之路会是一段愉快的旅程。

这是一个简单的商业选择，值得任何着手（或升级）基于web项目的人考虑。

[本文最初发表于2007年2月21日]
