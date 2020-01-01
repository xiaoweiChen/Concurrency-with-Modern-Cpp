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

To write this book in English, I started a request in my English blog: www.ModernesCpp.com and received a much higher response than I expected. About 50 people wanted to proofread my book. Special thanks to all of you, including my daughter Juliette, who improved my layout and my son Marius, who was the first proofreader. Here are the names in alphabetic order : NikosAthanasiou, RobertBadea, JoeDas, Jonas Devlieghere, Randy Hormann, Lasse Natvig, Erik Newton, Ian Reeve, Bart Vandewoestyne, Dafydd Walters, Andrzej Warzynski, and Enrico Zschemisch.

I’ve worked as a software architect, team lead and instructor for about 20 years. In my spare time, I enjoy writing articles on topics such as C++, Python and Haskell, and also enjoy speaking at conferences. In 2016 I decided to work for myself. I organise and lead seminars about modern C++ and Python.

I began Concurrency With Modern C++ in Oberstdorf while getting a new hip joint. Formally, it was a total endoprosthesis of my left hip joint. I wrote the first half of this book during my stay in the clinic and the rehabilitation clinic. To be honest, writing a book helped me a lot during this challenging period.

## 本书相关

* github翻译地址：
* gitbook在线阅读：