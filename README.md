# Awesome C++
汇集最有用的C++资源

## 编程规范
[C++ Core Guidelines](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines):C++标准委员会发布的编程规范。    
[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html):Google发布的编程规范。     
[LLVM Coding Standards](http://llvm.org/docs/CodingStandards.html):LLVM发布的编程规范。    

## Cheatsheet速查表
[C++17/14/11](https://github.com/AnthonyCalandra/modern-cpp-features): 现代C++语言和库特性的速查表。     

## 构建系统
[CMake](http://www.cmake.org/): 跨平台的免费开源软件,用于管理软件使用独立编译的方法进行构建的过程。最新版本是[v3.10.0](https://cmake.org/files/v3.10/cmake-3.10.0.zip)。       
[Ninja](https://github.com/ninja-build/ninja): 注重速度的小型构件工具，最新版本是v1.7.2。    

## 包管理
[qpm](http://www.qpm.io/): 跨平台的Qt包管理工具,可将包依赖直接编译到二进制文件里，支持Windows、MacOS、Linux，最新版本是v0.10.0。   

## 开发库
[Boost](http://www.boost.org/): Boost库是一个可移植、提供源代码的C++库，作为标准库的后备，是C++标准化进程的开发引擎之一。 Boost库由C++标准委员会库工作组成员发起，其中有些内容有望成为下一代C++标准库内容。Boost由于其对跨平台的强调，对标准C++的强调，与编写平台无关。大部分boost库功能的使用只需包括相应头文件即可，少数(如正则表达式库，文件系统库等)需要链接库。最新版本是[v1.65.1](https://dl.bintray.com/boostorg/release/1.65.1/source/boost_1_65_1.zip)。   

## 界面框架
[Qt](https://www.qt.io/): 跨平台的整套开源UI框架,使用范围广泛，用户众多。最新版本是v5.10.0。       
[WTL](https://sourceforge.net/projects/wtl/): 由微软的ATL(Active Template Library) 小组开发，主要是基于 ATL 对Win32API 的封装。从 2.0 后，功能逐步完善，成为了一个完整的支持窗口的框架(windows framework)。相对于MFC来说，各个类之间依赖小，比较灵活，扩展也灵活，库本身也很小很轻量级，编译出来的exe也小得多。流行的DirectUI技术就是基于WTL编写的。最新版本是v9.1。     

## Web框架
[CppCMS](http://cppcms.com/): 高性能的C++ Web框架，最新版本是v1.0.5，更新较慢。     
[Wt](https://github.com/kdeforche/wt): 一个C++ Web开发框架。 版本号已更新到v3.3.6，最近一次发布日期是2016.7.13。  
[Crow](https://github.com/ipkn/crow): 一个C++微型Web框架，灵感来自于Python Flask，Github上Star数量较多，不过更新速度较慢。  
[Tufão](https://github.com/vinipsmaker/tufao): 基于Qt的一个异步Web开发框架， 版本号已更新到v1.4.1，作者已经做好了v1.5的开发计划。  
[TreeFrog](https://github.com/treefrogframework/treefrog-framework): 一个高性能 C++ MVC web开发框架。 也是基于Qt的一个C++ Web框架，版本号已更新到v1.15.0，最近一次发布日期是2017.1.23。

## SIP客户端
[MicroSIP](http://www.microsip.org/): Windows平台基于PJSIP栈的可移植开源SIP电话. 版本号已更新到v3.11.0，最近一次发布日期是2016.2.06。

## 网络传输工具
[NitroShare](https://github.com/nitroshare/nitroshare-desktop): 一个跨平台的网络文件传输工具，可以运行于 Linux， Windows 和 MacOS X 系统，设置容易，无需配置，易于使用；支持在本地网络上自动发现运行着 Nitroshare 设备的能力；安全性上支持可选的 TLS (传输层安全协议Transport Layer Security) 编码传输方式；支持网络高速传输功能；支持文件和目录（Windows 上的文件夹）传输；支持对发送文件、连接设备等这些的桌面通知功能。当前版本号v0.3.3，最近一次发布日期是2016.7.15。

## BT下载工具
[Transmission-Qt](https://sourceforge.net/projects/trqtw/): 一个跨平台的图形化BT下载工具，可以运行于 Linux， Windows 和 MacOS X 系统。当前版本号v2.84.9，最近一次发布日期是2016.9.18。   

## 远程过程调用RPC
[Thrift](https://github.com/apache/thrift/): Facebook主导开发的RPC框架，已贡献给Apache，使用者较多。当前版本号v0.10.0，最近一次发布日期是2017.1.7。   
[libjson-rpc-cpp](https://github.com/cinemast/libjson-rpc-cpp/): 一个跨平台的基于JSON-RPC的C++框架，完全兼容JSON-RPC 2.0和1.0 。当前版本号v0.7.0，最近一次发布日期是2016.8.10。   

## 对象关系映射ORM
[QuickModel](https://github.com/danielfranca/quickmodel/): Qt/QML的一个简单易用的ORM库，主要目标是在SQLite上提供一层非常简便的ORM层。   
[QmlSql](https://github.com/JosephMillsAtWork/QmlSql/): 提供用于连接数据库进行SQL查询的辅助对象，基于GNU版权发布。  

## SNMP
[SNMP++](http://www.agentpp.com/download.html): 一个官方应用的SNMP协议类库，当前版本号[v3.3.9](http://www.agentpp.com/download/snmp++-3.3.9.tar.gz)。   

## Windows 安装程序开发工具
[NSIS](http://nsis.sourceforge.net/): 流行的开源Windows平台安装程序开发工具，代码托管在[SourceForge](https://sourceforge.net/p/nsis/code/HEAD/tree/NSIS/trunk/Source/)，国内有粉丝论坛[www.nsisfans.com](http://www.nsisfans.com)，当前版本号[v3.0.1](https://sourceforge.net/projects/nsis/files/latest/download?source=files)。  

## 大数据处理
[Thrill](http://project-thrill.org/): C++开发的分布式大数据处理框架，代码托管在[Github](https://github.com/thrill/thrill)，发布时间不长，效果待观察。  

## 机器学习
[DMLC](http://dmlc.ml/): 国人开发的机器学习系统，代码托管在[Github](https://github.com/dmlc)，集成了XGBoost、MXNET及Minerva等机器学习库与rabit和参数服务器等系统组件。  

# 监控工具
[netdata](https://my-netdata.io/): C开发的分布式实时的系统性能和健康监控工具，可运行在Linux、FreeBSD和macOS平台，代码托管在[Github](https://github.com/firehol/netdata)，当前版本是[v1.6.0](https://github.com/firehol/netdata/releases/latest)。  

[bmon](https://github.com/tgraf/bmon): C开发的宽带监控和网速评估工具，可运行在Linux和macOS平台，代码托管在[Github](https://github.com/tgraf/bmon)，当前版本是[v4.0](https://github.com/tgraf/bmon/archive/v4.0.zip)。  

[Stacer](https://github.com/oguzhaninan/Stacer): Linux系统监控和优化工具，当前版本是[v1.0.8](https://github.com/oguzhaninan/Stacer/archive/v1.0.8.zip)。  

## GIS
[QGIS](http://www.qgis.org/): QGIS由Gary Sherman于2002年开始开发，并于2004年成为开源地理空间基金会的一个孵化项目。版本1.0于2009年1月发布。QGIS以C++写成，它的GUI使用了Qt库。QGIS允许集成使用C++ 或Python写成的插件。除了Qt之外，QGIS需要的依赖还包括GEOS和SQLite。同时也推荐安装GDAL、GRASS GIS、PostGIS和PostgreSQL。QGIS是一个多平台的应用，可以在多种操作系统上运行，包括Mac OS X、Linux、UNIX和Microsoft Windows。最新版本是[v2.18.6](http://qgis.org/downloads/qgis-latest.tar.bz2)。     

## 文件系统
[FastDFS](https://github.com/happyfish100/fastdfs/): FastDFS是一款C开发的开源的、分布式文件系统（Distributed File System），由淘宝开发平台部资深架构师余庆开发。作为一个分布式文件系统，它对文件进行管理，功能包括：文件存储、文件同步、文件访问（文件上传、文件下载）等，解决了大容量存储和负载均衡的问题，特别适合中小文件（建议范围：4KB < file_size <500MB），对以文件为载体的在线服务，如相册网站、视频网站等等具有显著的效果。最新版本是[v5.10](https://github.com/happyfish100/fastdfs/archive/V5.10.zip)。     

## 机器视觉
[OpenCV](http://opencv.org/): OpenCV是一个基于BSD许可（开源）发行的跨平台计算机视觉库，可以运行在Linux、Windows、Android和Mac OS操作系统上。它轻量级而且高效——由一系列C函数和少量C++类构成，同时提供了Python、Ruby、MATLAB等语言的接口，实现了图像处理和计算机视觉方面的很多通用算法。OpenCV用C++语言编写，它的主要接口也是C++语言，但是依然保留了大量的C语言接口。该库也有大量的Python, Java and MATLAB/OCTAVE (版本2.5)的接口。最新版本是[v3.3.1](https://github.com/opencv/opencv/archive/3.3.1.zip)。     

[OpenBR](http://openbiometrics.org/): OpenBR是一个通用的生物测定学开源框架，支持Windows, Mac OS X, Linux平台，基于Apache 2.0许可发布，基于Qt和OpenCV，使用CMake构建系统。最新版本是[v1.1.0](https://github.com/biometrics/openbr/archive/v1.1.0.zip)。

## 语音识别
[Kaldi](http://kaldi-asr.org/): Kaldi是一个基于Apache许可（开源）发行的跨平台语音识别库，可以运行在Linux、Windows、Android和Mac OS操作系统上。代码托管在[Github](https://github.com/kaldi-asr/kaldi)。    

## OCR识别
[Tesseract](https://github.com/tesseract-ocr/): Tesseract是一个开源的OCR识别引擎，最初由HP开发，后开源交给Google继续支持开发和更新。代码托管在[Github](https://github.com/tesseract-ocr/)，最新版本是[v3.05.01](https://github.com/tesseract-ocr/tesseract/archive/3.05.01.zip)。   

## 网络库
[LibHTTP](https://www.libhttp.org/): LibHTTP是一个MIT许可的库，用C实现了一个带有websocket功能的HTTP / HTTPS服务器。该库还包括客户端连接到其他服务器的功能。LibHTTP库基于Mongoose(MIT)/Civetweb家族的HTTP服务器，并与这些服务器共享代码，尽管函数调用之间的兼容性是无法保证的。代码托管在[Github](https://github.com/lammertb/libhttp)，最新版本是[v1.8](https://github.com/lammertb/libhttp/archive/v1.8.zip)。   

[libtins](https://github.com/mfontanini/libtins/): Libtins是一个高级和多平台网络数据包嗅探和制作C++库，最新版本是[v3.5](https://github.com/mfontanini/libtins/archive/v3.5.zip)。   

[JSON for Modern C++](https://github.com/nlohmann/json/): JSON for Modern C++是一个由德国大牛 nlohmann编写的在C++下使用的JSON库。整个代码由一个头文件组成 json.hpp，没有子项目，没有依赖关系，没有复杂的构建系统，使用起来非常方便。使用C++ 11标准编写，使用json像使用 STL 容器一样，STL和json容器之间可以相互转换。所有类都经过严格的单元测试，覆盖了100%的代码，包括所有特殊的行为。此外，还检查了 Valgrind 是否有内存泄漏。为了保持高质量，该项目遵循核心基础设施倡议(CII)的最佳实践，最新版本是[v3.0.0](https://github.com/nlohmann/json/archive/v3.0.0.zip)。

## 网络代理
[Nuster](https://github.com/jiangwenyuan/nuster/): Nuster是用C实现的一个基于HAProxy的Web缓存代理服务器，最新版本是[v1.7.9.1](https://github.com/jiangwenyuan/nuster/archive/v1.7.9.1.zip)。   

## 分析工具
[MTuner](https://github.com/milostosic/MTuner): MTuner是用于Windows，PS4，PS3等的C / C ++内存分析器和内存泄漏查找器。MTuner利用一种新颖的内存分析和分析方法，保持基于时间的记录操作历史。 通过对整个数据集进行查询，可以对您的软件的内存相关行为提供独特的见解。，最新版本是[v4.0.7](https://github.com/milostosic/MTuner/archive/v4.0.7.zip)。    

## 数据库工具
[FastoNoSQL](https://github.com/fastogt/fastonosql): FastoNoSQL是跨平台的NoSQL数据库图形化管理工具，支持Redis, Memcached, SSDB, LevelDB, RocksDB, UnQLite, LMDB, UpscaleDB, ForestDB。最新版本是[ v1.14.0](https://github.com/fastogt/fastonosql/archive/v1.14.0.zip)。   
