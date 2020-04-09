# 代码说明

只要有合适的编译器，就可以编译并运行所有示例源码。这里要说明一下，只有在必要时，我才在源文件中使用`using namespace std`。

## 运行程序

编译和运行本书中C++11和C++14的例子并不难。任何支持新标准的C++编译器都可以编译这些例子。[GCC]( https://gcc.gnu.org/) 和[clang]( https://clang.llvm.org/) 编译器，必须指定C++标准，以及要链接的线程库。 例如，GCC的g++编译器使用以下命令行创建一个名为thread的可执行程序:

> g++ -std=c++14 -pthread thread.cpp -o thread.

* -std=c++14: 使用C++14标准。
* -pthread: 使用pthread库作为后端，对多线程进行支持。
* thread.cpp: 源码文件。
*  -o thread: 可执行程序名。

同样的命令行也适用于clang++编译器。Microsoft Visual Studio 17 C++编译器也支持C++ 14。

如果没有合适的C++编译器使用，那么可以使用在线编译器。比如：Arne Mertz博客提供的[C++ Online Compiler](https://arne-mertz.de/2017/05/online-compilers)。

C++ 17和C++ 20/23的故事比较复杂。我安装了[HPX (High Performance ParalleX)](http://stellar.cct.lsu.edu/projects/hpx/)框架，这是个C++通用运行时系统，适用于任何规模的并行和分布式应用。HPX已经实现了C++ 17并行的STL和C++ 20/23的许多并发特性。可参考“未来：C++ 20/23”一章中相应的内容和代码。

