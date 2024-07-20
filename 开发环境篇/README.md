# 开发工具与环境

## 运行时环境与包管理器

### Java

**【平台】**

Windows,Linux

**【简介】**

你东方大国的赛博基建混凝土，jvm。说实话我是碰都不碰，除了做Android和玩MC

**【版本】**

要根据实际需求安装Java版本，尤其是JDK。Linux下还有个OpenJDK。说实话现在JVM虚拟机实现挺多的。JDK和JRE似乎不是一个东西。本人Java开发经验为0，错误之处还请大佬commit

**【获取】**

已验证✔[Official offline Windows Installer Java8 ](https://www.java.com/en/download/)

已验证✔[Official offline Windows Installer JDK22 ](https://download.oracle.com/java/22/latest/jdk-22_windows-x64_bin.exe)

已验证✔[Official offline Linux Deb JDK22 ](https://download.oracle.com/java/22/latest/jdk-22_linux-x64_bin.deb)

### Python3

**【平台】**

Windows,Linux

**【简介】**

Python3运行时环境，我知道你要说miniconda永远的神，但是没有pip和conda源也没啥用.至于那么多包和依赖咋办，我推荐用venv打包带走.

**【版本】**

推荐python3>=3.8。忘了从哪个版本开始支持hint特性了，还有协程。主流Linux发行版基本都自带Python3

**【获取】**
已验证✔[Official offline Windows Installer V3.12.4 ](https://www.python.org/ftp/python/3.12.4/python-3.12.4-amd64.exe)

### NodeJS

**【平台】**

Windows,Linux

**【简介】**

内置大V8，全栈的神，从网站到移动端.伟大，无需多言。自带NPM包管理器。如何保存一个Node环境在Cheatsheet（Todo）中会有详细说明

**【版本】**

要装就装最新的。那个NVM这样的Node管理器在没有网的时候也不好使，就不考虑了

**【获取】**
已验证✔[Official offline Windows Installer V20.15.1 ](https://nodejs.org/dist/v20.15.1/node-v20.15.1-x64.msi)

### PHP


**【平台】**

Windows,Linux

**【简介】**

站点专精，一大票国内的CMS都用的这玩意。后面会整理一些常见的CMS包，方便快速上线，还有thinkphp这样的框架。不过据说PHP多线程基本没有，性能很差，不知道是不是真的。

**【版本】**

根据目标CMS或框架选择PHP版本。

**【获取】**
已验证✔[Official offline Linux tar gz archive V8.3.9](https://www.php.net/distributions/php-8.3.9.tar.gz)

已验证✔[Official offline Windows Zip Archive (Thread Safe) V8.3.9 ](https://windows.php.net/downloads/releases/php-8.3.9-Win32-vs16-x64.zip)

## 编译工具

### MinGW

**【平台】**

Windows,Linux

**【简介】**

Windows平台下的GCC编译器/ToolChain

**【版本】**

要装就装最新的。

**【获取】**

已验证✔[Zipped Binary Archive Github Release](https://github.com/brechtsanders/winlibs_mingw/releases/download/14.1.0posix-18.1.8-12.0.0-ucrt-r3/winlibs-x86_64-posix-seh-gcc-14.1.0-llvm-18.1.8-mingw-w64ucrt-12.0.0-r3.zip)

### Build-essential

**【平台】**

Linux

**【简介】**

Linux新系统apt update后第一个装的东西

**【版本】**

要装就装最新的

**【获取】**

阿巴阿巴

### Rust Tool chain

**【平台】**

Windows，Linux

**【简介】**

Rust lang的编译器，rust本身有一套带编译器包管理器等的完整工具链。编译出来的东西内存安全，不需要自己考虑垃圾回收，编译阶段就会警告出什么问题，还能直接编译成WebAssembly挂在大V8上跑，什么都好，就是太难学了。没啥开发经验，欢迎大佬commit纠错补充

**【版本】**

要装就装最新的

**【获取】**

已验证✔[Official offline Windows Installer ](https://static.rust-lang.org/rustup/dist/x86_64-pc-windows-msvc/rustup-init.exe)

未验证❌(可下载✔)[Official offline Linux Binary ](https://static.rust-lang.org/rustup/dist/x86_64-unknown-linux-gnu/rustup-init)

### GO lang

**【平台】**

Windows,Linux

**【简介】**

Google开发的一个语言，有梗说Google为了照顾不会写C++的员工开发了这个语言。不过这玩意确实有一些很Nice的特性，各个领域都有见到身影。比如C2（）。不过我曾经编译过Go写的项目，居然直接import源上的包，编译的时候自动下载。6

**【版本】**

要装就装最新的。

**【获取】**

已验证✔[Official offline Windows Installer V1.22.5 ](https://golang.google.cn/dl/go1.22.5.windows-amd64.msi)

已验证✔[Official offline Linux tar ](https://golang.google.cn/dl/go1.22.5.linux-amd64.tar.gz)
