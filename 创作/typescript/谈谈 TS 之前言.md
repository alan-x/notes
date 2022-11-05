# 漫谈 TS 之前言

## 概述

最近在重新学习 TypeScript，打算将学习的一些思考沉淀下来，所以决定先来水一篇，整理一下我学习过程中涉及到的资料。


## 资料

### 网站：官网

官网的地址：[https://www.typescriptlang.org/](https://www.typescriptlang.org/)。

官网有两个地方有干货：

- 第一个是它的 [Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)，非常详尽，看完基本 TS 算是入门。

- 第二个是它的 [Blog](https://devblogs.microsoft.com/typescript/)，新的功能一般都会在博客上发公告，并且这些公告中会说明更新功能的前因后果和思考。


### 书：《Typescript Deep Dive》

这本书的地址：[《Typescript Deep Dive》](https://basarat.gitbook.io/typescript/)。

这是一本开源的电子书，深入讲解了 Typescript 的基础能力、类型系统等，并讨论了一些深度的话题，比如 [Nominal Typing](https://basarat.gitbook.io/typescript/main-1/nominaltyping)。

这里推荐阅读英文原版，因为翻译的质量层次不一，比如，我也翻译过这本书--[typescript-deep-dive](https://github.com/alan-x/standard-and-book-translation-notes/tree/master/typescript-deep-dive)，就和机翻差不多。其次，该电子书一直在更新，可能会存在一定的滞后性。

### 书：《编程与类型系统》

这本书需要自己去买了：[《编程和类型系统》](http://product.dangdang.com/29190836.html)

与其说这本书是介绍 Typescript 的，不如说是介绍类型系统的，只是正好用了 TS 作为示例语言。通过这本书，不但能够了解 TS 类型系统的细节，还能对编程领域的类型系统有一定了解，一举两得，干得漂亮。



### 源码：microsoft/TypeScript

源码地址：[TypeScript](https://github.com/microsoft/TypeScript)

源码就不用说了，最终要是要去看实现的，希望这个系列不会烂尾，可以有这么一天。

这个仓库除了源码之外，还有一个有价值的东西，那就是[《TypeScript Language Specification》](https://github.com/microsoft/TypeScript/blob/main/doc/TypeScript%20Language%20Specification%20-%20ARCHIVED.pdf)。

它完整定义了整个 TypeScript 的规范，在后期这个文档应该是分析 TypeScript 不可或缺的材料。