# Concurrency with Modern C++

* 作者：Rainer Grimm
* 译者：陈晓伟
* 原文发布时间：2019年03月19日

## 本书概述

每个专业C++开发者应该知晓的并发性。

本书是一场关于C++并发的旅程。

* C++11和C++14创建了并发和并行的基础件。

* C++17中，将标准模板库(STL)的大部分算法并行化。这意味着大多数基于STL的算法可以串行、并行或向量化执行。

* The concurrency story in C++ goes on. With C++20/23 we can hope for extended futures, coroutines, transactions, and more.
* C++的并发之旅并没有停止。C++20/23，可以期待增强版future、协程([coroutines](https://en.cppreference.com/w/cpp/language/coroutines))、事件性内存([transactional_memory](https://en.cppreference.com/w/cpp/language/transactional_memory))等等。

本书解释了C++中的并发性，并提供了许多代码示例。因此，可以将理论与实践相结合。

因为这本书与并发相关，所以我展示了很多容易出错的地方，并展示避免或解决它们的方案。

## 书与作者

这本书使用英语完成。在写书之前，我在我的英文博客www.ModernesCpp.com发布了要写这本书的消息，并得到了很多人的回复。有大概有50多个人要帮我校对。特别感谢我的闺女Juliette，对本书的布局进行升华；还有我的儿子，你是本书的第一个审阅者哦。当然，还有很多很多人 : NikosAthanasiou, RobertBadea, JoeDas, Jonas Devlieghere, Randy Hormann, Lasse Natvig, Erik Newton, Ian Reeve, Bart Vandewoestyne, Dafydd Walters, Andrzej Warzynski, 以及Enrico Zschemisch。

我已经做了20多年的软件架构师、团队带头人和讲师。在业余时间，我喜欢关于C++、Python和Haskell的文章。2016年时，我决定为自己工作。我会组织关于C++和Python的研讨会。

在Oberstdorf时，我换了一个新的髋关节义肢。本书的前半部分是在诊所期间所写。说实话，在这段时期充满挑战，也对我写书有很大帮助。

## 本书相关

* github翻译地址：
* gitbook在线阅读：