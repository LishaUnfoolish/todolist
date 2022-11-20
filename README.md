
---
# **Todo table:**
- ==ToDo-List==
- ==[markdown颜色对应表](https://blog.csdn.net/qq_43732429/article/details/108034518)==
- ==<font color=red size=2>ToDo</font>,红色代表是在家里做的==
- ==<font color=Green size=2>ToDo</font>,绿色代表是在公司做的==
---


| ToDo | 序号 | 任务名 | 任务描述 | - |
| --- | --- | --- | --- | --- |
|  × | 1 | io_uring | 学习linux新的io驱动模型 | [c++20的协程实现的io_uring库](https://github.com/CarterLi/liburing4cpp) |
|  <font color=Green size=2>DONE</font> | 2 | ==evpp== | 学习一下C++的新特性,将evpp封装成自己的程序 | [share项目第34.evencpp](https://gitee.com/lixiaoxmm/share/tree/master/34.eventpp) [自己封装的](https://gitee.com/lixiaoxmm/eventpp_self.git)|
|  × | 3 | libasio | c++23要将它加入标准库,提前学习一下 | [libasio Github链接](https://github.com/dnybz/libasio) |
|  × | 4 | c++11-17的变化表格 | 表格一个一个知识点看一下,结合bilibili视频来看 | [c++11-17特性图](https://blog.csdn.net/tkokof1/article/details/82527370)<br> [新特性讲的挺好是视频](https://www.bilibili.com/video/BV1ku411X73q)<br>  [模板检查,记录一下](https://qa.1r1g.com/sf/ask/457382901/?lastactivity)|
|  × | 5 | workflow框架学习 | 找个开源的程序学习一下,我们的感知模块有用到这个思想,有用到DAG的数据结构(最好是找一个c++17以上写的)| |
|  × | 6 | ==DAG数据结构和可视化== |学习一下DAG很多地方有用到,结合==egypt+graphviz==可视化c++软件流程和cyber节点可视化|==**++笔记在<<共享笔记->1.百度阿波罗->5.linux下graphviz>>文件夹下面,里面有各种教程++**== <br>[在线可视化转换](http://dreampuf.github.io/GraphvizOnline/#digraph%20first2%7B%0D%0Aa%3B%0D%0Ab%3B%0D%0Ac%3B%0D%0Ad%3B%0D%0Aa-%3Eb%3B%0D%0Ab-%3Ed%3B%0D%0Ac-%3Ed%3B%0D%0A%7D) |
|  <font color=red size=2>DONE</font> | 7 | ==CyberCmake== |自己在家封装的==cyber==框架,后续还要裁剪去掉没用的开源依赖,做成开源库开源出去|[自己的CyberCmake库-todo](https://gitee.com/lixiaoxmm/cyber-cmake.git) |
|  × | 8 |==cuda==库异构加速学习| 有空的时候学习一下cuda编程,补一下知识盲区
|  × | 9 |c++提效工具可以学习| 公众号分享的c++提效文章,有空可以学习一下|[C++提效网站](https://mp.weixin.qq.com/s/i0waRFSdUJnTsINaI7YLCQ) <br> [c++ 模板特性查找手册](https://cloud.tencent.com/developer/section/1012623)
|  × | 10 |==程序员书籍<br>(全英文)==| 程序有关的所有书籍在这里都能找到下|[程序员书籍仓库-全英文](https://leanpub.com/)
|  × | 11 |==c++的在线编程网站<br>(用来学习)==|在线编程网站,可以用来测试程序,带有汇编和自动展开功能,用来学习新特性原理很有用|[c++可视化工具](https://pythontutor.com/cpp.html#mode=display)[c++在线编程网站](https://cppinsights.io//) [demo 程序演示](https://note.youdao.com/) <br>[所有的在线c++网站有空可以看看](https://www.jb51.net/article/197290.htm)<br> [cppinsights 编译安装](https://www.jianshu.com/p/450b628b7f58)<br> [cpp转汇编](https://godbolt.org)<br>  [cpp在线编译测试网站](http://coliru.stacked-crooked.com/)
|  <font color=red size=2>DONE</font> | 12 | ==cyber_xmake== |自己在家封装的==cyber==框架,后续还要裁剪去掉没用的开源依赖,做成开源库开源出去|[自己的cyber_xmake库-todo](https://gitee.com/lixiaoxmm/cyber_xmake) |
|  × | 13 | meson | 学习一下Meson看一下用来做c++构建 | [meson教程网站](https://www.techgrow.cn/posts/68d93948.html) <br> [cmake和meson的范例](https://guileen.github.io/2021/01/08/cpp-build-systems/)|
|  × | 14 | 正则表达式 | 正则表达式的学习网站 | [正则表达式学习网站](https://mp.weixin.qq.com/s/MP2a-EXTpuyZ03PpedyA_Al)|
|  × | 15 | docker | docker的使用 | docker run -i -t ubuntu:14.04 /bin/bash <br>docker run -i -t --name "private_container" ubuntu:14.04 /bin/bash<br>[docker的使用](https://www.cnblogs.com/klb561/p/14040705.html)<br>[使用nsenter进入Docker容器脚本](https://www.tuicool.com/articles/eYnUBrR)<br>[Docker中容器的备份、恢复和迁移](https://www.cnblogs.com/boshen-hzb/p/6373549.html)|
|  × | 16 | 开源的DDS代码 | 开源的dds代码 | [1.知乎关于RMW的适配和解释](https://zhuanlan.zhihu.com/p/353268445)<br>[2.eclipse-iceoryx(c++,rust,web零拷贝)](https://github.com/eclipse-iceoryx/iceoryx)<br>[3.eclipse-cyclonedds支持c,c++,python](https://github.com/eclipse-cyclonedds)<br>[4.eProsima FastRTPS](https://github.com/eProsima/Fast-DDS.git)<br>[5.RTI Connext,RTI Connext动态实现](https://github.com/rticommunity)<br>[6.ADLINK Opensplice](https://github.com/ADLINK-IST)<br>[7.micro-ROS(嵌入式小系统的ros)](https://github.com/micro-ROS)<br>[8.ecal](https://zhuanlan.zhihu.com/p/474528122?utm_source=wechat_session&utm_medium=social&utm_oi=950859626095284224&utm_campaign=shareopn)|
|  × | 17 | gdb coredump的实用工具Backward-cpp |bomblab gdb练习库,以后段错误可以直接用这个库,打印信息比较多 |[C++的全链路追踪](https://github.com/TomaszAugustyn/call-stack-logger) [使用教程](https://zhuanlan.zhihu.com/p/397148839) [库使用教程](https://blog.csdn.net/xiangxianghehe/article/details/103111237)[库](https://github.com/LishaUnfoolish/backward-cpp) |
|  × | 18 | 数据结构与算法网页 | 数据结构与算法网页可视化 | [visualgo](https://visualgo.net/zh) [基于C++模板实现的数据结构源代码](https://github.com/LishaUnfoolish/Data-Structure)|
|  × | 19| c++20协程 | c++23要将它加入标准库,提前学习一下 | [阿里封装的c++20协程库](https://github.com/alibaba/async_simple)<br>[协程库](https://github.com/owent/libcopp)<br>[腾讯协程库](https://github.com/Tencent/libco)<br>[libcoro C++20 linux coroutine library](https://github.com/jbaldwin/libcoro)|
|  × | 20| rust | rust code book里面有大量优秀的代码参考 | [1.rusty-book](https://github.com/rustlang-cn/rusty-book) [c++rust对比](https://zhuanlan.zhihu.com/p/75385189?utm_source=wechat_session&utm_medium=social&utm_oi=950859626095284224&utm_campaign=shareopn) <br> [2.rustdesk-公司也在用的远程桌面开源工具](https://github.com/LishaUnfoolish/rustdesk)|
|  × | 21| 记录一下vim的配置 | 记录配置 | [直接使用B站大佬的配置](https://github.com/archibate/vimrc) |
|  × | 22| 记录一下vscode neovim的配置 | vscode和vim可以用一样的配置文件,但是可以通过 <br> if !exists('g:vscode') <br>这个字段来进行判断| [参考这个来改配置,记住不要直接用他的,会导致系统起不来]( https://github.com/sisrfeng/dot_file.git) |
|  × | 23 | benchmark开源库-header only |用现代C++测试工具链：doctest+FakeIt+nanobench, 可以完美地替代gtest/gmock和google bench，没有任何依赖，无需安装，直接包含头文件就可以用，非常容易集成和使用，是时候抛弃google test和google bench了<br>[现代C++测试工具链](https://mp.weixin.qq.com/s/jYGi-xNHbKmlgZh1VvgaEg) |[doctest](https://github.com/doctest/doctest/blob/master/doc/markdown/benchmarks.md)<br> [FakeIt](https://github.com/eranpeer/Fake) <br>[nanobench](https://github.com/martinus/nanobench)|
|  DONE | 24 | 函数式库 | 函数式库 |https://github.com/PacktPublishing/LearningCPPFunctionalProgramming|
|  todo | 25 | 引擎库 | c++引擎库 |[envtt引擎库，学习c++内存分配器](https://github.com/doctest/doctest/blob/master/doc/markdown/benchmarks.md)|
|  × | 26 | cgraph| c++cgraph pipeline |[牛逼的popeline库](https://github.com/vsklad/cgraph)|
|  × | 27 | Image-Processing-Node-Editor | python写的界面，算法仿真用的 |https://github.com/Kazuhito00/Image-Processing-Node-Editor|
|  × | 28 | coost | 轻量的boost库，带协程，可用于嵌入式|https://github.com/idealvin/coost|
|  × | 29 | 代码阅读神器 | [1.C++阅码神器cpptree.pl和calltree.pl的使用](https://zhuanlan.zhihu.com/p/339910341?utm_campaign=shareopn&utm_medium=social&utm_oi=950859626095284224&utm_psn=1546260881885081600&utm_source=wechat_session)<br>[2.开源免费的源码阅读神器 Sourcetrail](https://zhuanlan.zhihu.com/p/96685579)|
|  todo | 30 | 编译器 | 1.[AI编译器MegCC源码](https://github.com/MegEngine/MegCC)---------[MegCC介绍](https://mp.weixin.qq.com/s/_8kSUwIZHjZDnlw7_XTBWA)<br>[2.源码安装clang和llvm](https://csstormq.github.io/blog/LLVM%20%E4%B9%8B%20Clang%20%E7%AF%87%EF%BC%881%EF%BC%89%EF%BC%9A%E5%A6%82%E4%BD%95%E4%BB%8E%E6%BA%90%E7%A0%81%E6%9E%84%E5%BB%BA%E5%B9%B6%E5%AE%89%E8%A3%85%20Clang)|
|  × | 31 | 哈希容器 | 用作graph的哈希容器| [1.hopscotch-map](https://github.com/Tessil/hopscotch-map/tree/master/include/tsl)->[文档](https://www.5axxw.com/wiki/content/fcbrfj)<br> [2.jq_dense_hash_map](https://github.com/Jiwan/dense_hash_map)->[文档](https://jguegant.github.io/blogs/tech/dense-hash-map.html#dense-hash-map)<br>|
|  × | 31 | 现代c++库收集 | 1.[STX-c++封装成rust的类似语法](https://github.com/lamarrr/STX)<br>[2.c++20 windows版本很全的demo](https://github.com/rutura/The-C-20-Masterclass-Source-Code/tree/main/49.Modules/48.8ExportImport/ExportImport)<br>[3.c++20综合指南很少见带module的](https://github.com/utilForever/modern-cpp-next)|
---
https://www.cnblogs.com/kevin-ying/p/14534708.html github访问慢的问题
https://www.apiref.com/cpp-zh/cpp/ c++手册
---

---
# **详细笔记:**
- ==序号跟Todo table对应==
---
## 1. 额外的链接备份
[1.xmake安装](https://zhuanlan.zhihu.com/p/91068266)
## 2. 
| 时间序号 | todo | 备注 |
| --- | --- | --- |
| 20220309 | <font color=Green size=2>ToDo</font> | 开始将Callback类拆分出来,封装成自己的函数 |


    
## 3.
## 4. 
## 5. 
## 6.
## 7. 
| 时间序号 | todo | 备注 |
| --- | --- | --- |
| 20220309 | <font color=red size=2>ToDo</font> | 解决fastrtps依赖xml库安装报错的问题 |
## 8. 
## 9. 
## 10. 
## 11. 
## 12. 
## 13.
## 14.
## 15.
重新安装wsl:
0,代理源:
    1.sudo vim /etc/hosts
    2.  199.232.28.133 raw.githubusercontent.com
        192.30.255.112 www.github.com
        192.30.255.112 github.com
1.[Windows使用WSL2安装Docker](https://www.jianshu.com/p/c27255ede45f)

2.**注意:更新源之前先把自带的源更新一下:sudo apt-get update -y && sudo apt-get upgrade -y**
[更新源](https://blog.csdn.net/weixin_44161471/article/details/115354959)


```
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
#################################
deb http://mirrors.aliyun.com/ubuntu/ xenial main
deb-src http://mirrors.aliyun.com/ubuntu/ xenial main
deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-updates main
deb http://mirrors.aliyun.com/ubuntu/ xenial universe
deb-src http://mirrors.aliyun.com/ubuntu/ xenial universe
deb http://mirrors.aliyun.com/ubuntu/ xenial-updates universe
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-updates universe
deb http://mirrors.aliyun.com/ubuntu/ xenial-security main
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-security main
deb http://mirrors.aliyun.com/ubuntu/ xenial-security universe
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-security universe

############
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-updates main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-backports main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-security main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-security main restricted universe multiverse

```



3.[Docker 安装 Ubuntu](https://www.runoob.com/docker/docker-install-ubuntu.html)


sudo service docker start 

docker拉镜像代理:docker push dockerproxy.com/library/

下面自己写的docker启动脚本start_docker表示默认启动ubuntu镜像用户名为lixiao ,start_docker xxx yyy 表示启动xxx镜像后的名字,yyy为空默认是启动ubuntu镜像
例如:start_docker 另外取的名字 ubuntu:22.04
```
#!/bin/sh
image_name="ubuntu"
if [ -z "$2" ]; then
    image_name="ubuntu"
else
    image_name=$2
fi

start() {
    docker_name=$(docker ps | grep $1 | awk '{print $1}')
    if [ -z $docker_name ]; then
        docker_name=$(docker ps -a | grep $1 | awk '{print $1}')
        if [ -z $docker_name ]; then
            docker run -ti --name $1 -v /root:/root $image_name /bin/bash
            exit 0
        fi
        docker start $1
        docker run -ti --name $1 -v /root:/root $image_name /bin/bash
        exit 0
    fi

    if [ -e $(dirname "$0")/nsenter ]; then
        # with boot2docker, nsenter is not in the PATH but it is in the same folder
        NSENTER=$(dirname "$0")/nsenter
    else
        NSENTER=nsenter
    fi
    if [ -z "$1" ]; then
        echo "Usage: $(basename "$0") CONTAINER [COMMAND [ARG]...]"
        echo ""
        echo "Enters the Docker CONTAINER and executes the specified COMMAND."
        echo "If COMMAND is not specified, runs an interactive shell in CONTAINER."
    else
        PID=$(docker inspect --format "{{.State.Pid}}" "$1")
        if [ -z "$PID" ]; then
            exit 1
        fi
        shift
        OPTS="--target $PID --mount --uts --ipc --net --pid --"
        if [ -z "$1" ]; then
            # No command given.
            # Use su to clear all host environment variables except for TERM,
            # initialize the environment variables HOME, SHELL, USER, LOGNAME, PATH,
            # and start a login shell.
            "$NSENTER" $OPTS su - root
        else
            # Use env to clear all host environment variables.
            "$NSENTER" $OPTS env --ignore-environment -- "$@"
        fi
    fi
}
sudo /etc/init.d/docker start

if [ -z "$1" ]; then
    start 'lixiao'
    exit 1
fi
start $1
```

docker 环境安装测试cyber
```
自己的docker
apt-get update
apt-get -y install make vim pip sudo git wget curl pkg-config autoconf automake libtool g++ unzip gnutls-bin lsb-release cmake(cmake 选6-32)
apt-get -y llvm clang clang++

安装python2
apt update
apt-get -y install python python2-dev python-protobuf
apt-get -y install libasio-dev libtinyxml2-dev libssl-dev zlib1g-dev

1.安装protobuf
protobuf3.5.1下载地址
https://download.csdn.net/download/qq_35066464/12689304
unzip protobuf-3.5.1.1.zip
cd protobuf-3.5.1.1
./autogen.sh
./configure
make
make check
sudo make install
sudo ldconfig

2.安装fastCDR
fast-CDR下载地址
https://download.csdn.net/download/qq_35066464/12689294
mkdir Fast-CDR/build && cd Fast-CDR
cmake ..;make -j128;make install

3.安装fastrtps
fastrtps下载地址
https://download.csdn.net/download/qq_35066464/12689296
1.修改cmake文件
找到add_subdirectory(examples)注释
2.编译
cmake -DCMAKE_INSTALL_PREFIX=/usr/local -DBUILD_SHARED_LIBS=ON ..
make -j128;make install
=========上面是自己docker=======================


```

```
docker 里面的ubuntu中文支持
ubuntu中文支持，及中文乱码问题
状况：所用的Linux系统不支持中文，遇见中文就zz了。ORZ…

目标：使系统/服务器支持中文，能够正常显示。

首先，安装中文支持包language-pack-zh-hans：

1.sudo apt-get install language-pack-zh-hans
 

2.然后，修改/etc/environment（在文件的末尾追加）：

LANG="zh_CN.UTF-8"
LANGUAGE="zh_CN:zh:en_US:en"
 

3.再修改/var/lib/locales/supported.d/local(没有这个文件就新建，同样在末尾追加)：

en_US.UTF-8 UTF-8
zh_CN.UTF-8 UTF-8
zh_CN.GBK GBK
zh_CN GB2312
 

最后，执行命令：

4.sudo locale-gen
对于中文乱码是空格的情况，安装中文字体解决。

5.sudo apt-get install fonts-droid-fallback ttf-wqy-zenhei ttf-wqy-microhei fonts-arphic-ukai fonts-arphic-uming
以上，问题解决，中文显示正常。:)

原文链接：https://blog.csdn.net/weixin_39792252/article/details/80415550

```


备份:
1.保存镜像docker commit 保存的名字 保存后的名字
2.保存为tar:docker save -o ~/container-backup.tar container-backup
3.恢复docker load -i ~/container-backup.tar

## 16.
## 17.
cmake添加步骤:
https://www.bilibili.com/video/BV1kP4y1K7Eo?p=1&share_medium=android&share_plat=android&share_session_id=96ec7b03-033e-4e9c-9699-79aae9f213f3&share_source=WEIXIN&share_tag=s_i&timestamp=1649247888&unique_k=1XHbYKu 视频
1.通过git clone https://github.com/LishaUnfoolish/backward-cpp.git下载项目到自己项目的根文件夹里,然后删除backward-cpp里面的.git
2.在主CMakeFileList.txt添加:
add_subdirectory(backward-cpp)
target_executable(main main.cpp) // 自己的东西,根据实际情况写
target_sources(main PUBLIC ${BACKWARD_ENABLE})
add_backward(main)
或者:
1.以Ubuntu为例，安装方法很简单，首先安装第三方库
    sudo apt-get install libdw-dev

2.随后下载头文件并拷贝到系统目录
    wget https://raw.githubusercontent.com/bombela/backward-cpp/master/backward.hpp
    sudo mv backward.hpp /usr/include
3.然后在CMakeLists中添加target_link
    target_link_libraries(dw_test
            dw
            )
4.最后在主程序中添加
#define BACKWARD_HAS_DW 1
#include "backward.hpp"
namespace backward{
    backward::SignalHandling sh;
}
即可。

5.我们写一段测试代码

#include<stdio.h>
#include<stdlib.h>
#define BACKWARD_HAS_DW 1
#include "backward.hpp"
namespace backward{
    backward::SignalHandling sh;
}
int main(){
    char *c = "hello world";
    c[1] = 'H';
}


## 22.

```
if !exists('g:vscode') 
  "
  " .vimrc used by a naive C++ coder: github.com/archibate
  "
  " I manage plugins using vim-plug (already bundled in my .vim folder):
  " https://github.com/junegunn/vim-plug
  "
  " IMPORTANT: Simply put this .vimrc and .vim to your home folder won't work
  " immediately. You need to run
  "
  " :PlugInstall
  "
  " when you launch Vim for the first time.
  " This will initialize all the plugins, otherwise they will not shows up.
  "
  " Scroll to the end of this file to see my plugin list.
  " Comment or uncomment some of them as you wish.
  "
  "
  " Key maps
  " --------
  "
  " Z    - equivalent to :wq, save and exit current window
  " Q    - equivalent to :wa! then :qa!, save and exit all windows
  " H    - equivalent to ^, goto start of line
  " L    - equivalent to $, goto end of line
  " kj   - equivalent to <ESC>, exit insert mode
  "
  " g1   - switch the 1st tab
  " g2   - switch the 2nd tab
  " g3   - switch the 3rd tab
  " ...
  "
  " <F1> - save and switch to last used tab
  " <F2> - save and switch to previous tab
  " <F3> - save and switch to next tab
  " <F4> - save all opened files
  "
  " gci  - comment/uncomment selected code (visual mode)
  "
  " <F8>     - start shell in fullscreen (equivalent to :sh)
  " <F9>     - toggle project file tree window (:NERDTreeToggle)
  "
  " <F5>     - build and run current CMake project
  " <F6>     - build current CMake project, but don't run
  " <F7>     - run current file as a single script (.c .cpp .py)
  " <S-F7>   - configure current CMake project (via ccmake)
  " <F10>    - toggle compile error window (equivalent to :QFix)
  " <F12>    - search for required-from-here (useful for errors)
  "
  " <C-t>    - toggle built-in terminal
  " <C-\>    - enter normal mode in terminal (to select text)
  " i or a   - get back to insert mode in terminal
  " <C-w> w  - switch out of terminal window (back to editor)
  " <C-w> "" - paste from vim clipboard to terminal
  "
  "
  " Build and Run
  " =============
  "
  " For build and run projects, I use the plugin 'asynctasks.vim'.
  "
  " By default <F5> will build the CMake project, and run the target named 'main'.
  " This is defined in the '~/.vim/tasks.ini', which is bundled in my '.vim':
  "
  " [+]
  " build_type=Release
  " build_target=main
  " build_dir=build
  " build_generator=Ninja
  " run_target="$(VIM:build_dir)/$(VIM:build_target)"
  " build_options=--parallel
  " build_configs=
  "
  " [project-build]
  " command=cmake -G "$(VIM:build_generator)" -B "$(VIM:build_dir)" -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=ON -DCMAKE_BUILD_TYPE="$(VIM:build_type)" $(VIM:build_configs) && cmake --build "$(VIM:build_dir)" --target "$(VIM:build_target)" --config "$(VIM:build_type)" $(VIM:build_options)
  " output=quickfix
  " cwd=$(VIM_ROOT)
  "
  " [project-run]
  " command=$(VIM:run_target)
  " output=quickfix
  " cwd=$(VIM_ROOT)
  "
  " You can create a file named '.tasks' locally in the root of your project to
  " override the default rules and variables, customized for your project, e.g.:
  "
  " [+]
  " build_type=Debug
  " build_target=zeno_pybind_module
  " build_generator=Unix Makefiles
  " run_target=python my_start_script.py
  "
  " May also use the :AsyncTaskEdit to create the '.tasks' file in project root.
  " It will recognize the first directory containing '.tasks' or '.git' as root.
  "
  " See https://github.com/skywind3000/asynctasks.vim/blob/master/README-cn.md
  "
  "
  " Auto completion
  " ===============
  "
  " For auto-completion, I use the plugin 'coc.nvim', recommended by my students.
  " Although 'coc.nvim' sounds like a NeoVim plugin, it works well in Vim too.
  "
  " IMPORTANT: Even after running :PlugInstall, auto-completion still won't work.
  " You need the follow the below instructions carefully to set it up as well.
  "
  " To make 'coc.nvim' work at all, you need to first install Node.js:
  "
  " $ pacman -S nodejs          # Arch Linux
  " $ apt install nodejs        # Ubuntu
  " $ brew install -g node      # MacOS
  " $ node --version            # check if installation succeed
  "
  "
  " For C++ developers
  " ------------------
  "
  " To make 'coc.nvim' work for C++, you need to install 'ccls'.
  " First, run this command in Vim to enable 'ccls' in 'coc.nvim':
  "
  " :CocInstall coc-ccls
  "
  " Second, you need to install 'ccls' to your system.
  " Arch Linux could install from their package manager:
  "
  " $ sudo pacman -S ccls
  " $ ccls --version
  "
  " Ubuntu and MacOS could build ccls from source (tested on clang-13):
  "
  " $ git clone --depth=1 --recursive https://github.com/MaskRay/ccls.git
  " $ cmake -B build -DCMAKE_BUILD_TYPE=Release -DCMAKE_CXX_COMPILER=clang++
  " $ cmake --build build --parallel 4
  " $ sudo cmake --build build --target install
  " $ ccls --version
  "
  " Now create a C++ file to test if auto-completion works, say:
  "
  " $ vim /tmp/test.cpp
  "
  " If it complains an error: 'extension "coc-ccls" doesn't contain main file'
  " Don't worry, I meet this error too. Fix it by executing:
  "
  " $ cd ~/.config/coc/extensions/node_modules/coc-ccls/
  " $ ln -s node_modules/ws/lib/ ./
  "
  " Now restart Vim and the error is gone, and another error occurs:
  "
  " [coc.nvim] Server languageserver.ccls failed to start: Error: invalid params
  " of initialize: expected array for /workspaceFolders
  "
  " This means it doesn't find the 'compile_commands.json' of your project.
  " This file contains information like compiler flags, include directories which
  " are required by 'ccls' for providing auto-completion.
  "
  " If your project is CMake, simply set CMAKE_EXPORT_COMPILE_COMMANDS to ON:
  "
  " $ cd MyProject/
  " $ cmake -B build -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=ON
  " $ vim MySourceFile.cpp
  "
  " CMake will automatically create the file 'build/compile_commands.json'.
  " 'ccls' will recognize it. Now restart Vim, and auto-completion should work.
  " If you use other build systems, search Bing: 'Bazel compile_commands.json'
  "
  " If you are using my <F5> key mapping to build your CMake project, then the
  " '-DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=ON' is automatically added, no worry.
  "
  " Note that the build directory must be 'build', otherwise ccls won't find it.
  "
  " Also try run :CocConfig to open the ~/.vim/coc-settings.json file. This file
  " is already bundled in my .vim folder, containing a C/C++ configuration.
  "
  "
  " For Python developers
  " ---------------------
  "
  " To make 'coc.nvim' work for Python, you need 'pyright'.
  " First, run this command in Vim to enable 'pyright' in 'coc.nvim':
  "
  " :CocInstall coc-pyright
  "
  " For more details (e.g. work with Conda), see their official document:
  " https://github.com/fannheyward/coc-pyright
  "
  " For other languages support of 'coc.nvim', see their official support list:
  "
  " https://github.com/neoclide/coc.nvim/wiki/Language-servers#ccobjective-c
  "
  "
  " Key maps
  " --------
  "
  " <c-space> - trigger completion (in insert mode)
  " <tab>     - next completion (in insert mode)
  " <s-tab>   - previous completion (in insert mode)
  "
  " gd - goto definition
  " gD - goto type definition
  " gc - goto declaration
  " gC - goto implementation
  " gr - goto references
  " gR - rename current symbol under cursor
  " gq - format selected code (visual mode)
  " gf - goto file path under cursor (no line number)
  " gF - goto file path under cursor (with line number)
  " K  - show documentation of symbol under cursor
  "
  " gaga - show code actions on current line
  " gaq  - quick fix error on current line
  "
  " vif  - select current function scope (inner)
  " vaf  - select current function scope (outer)
  " vic  - select current class scope (inner)
  " vac  - select current class scope (outer)
  "
  "
  " Fuzzy find
  " ==========
  "
  " For fuzzy find, I use the plugin 'LeaderF'. It uses the Unix command
  " line tools 'rg'. So make sure you have installed it first:
  "
  " $ pacman -S ripgrep                  # Arch Linux
  " $ apt-get install ripgrep            # Ubuntu
  " $ brew install ripgrep               # MacOS
  " $ rg --version                       # check if installation succeed
  "
  "
  " Key maps
  " --------
  "
  " gff - fuzzy find file names in project directory
  " gfb - fuzzy find file names in all opened files
  " gfm - fuzzy find most-recently-used opened files
  " gf: - fuzzy find runned ex-commands (:) in history
  " gf/ - fuzzy find searched strings (/) in history
  " gfx - fuzzy find vim ex-commands (including plugins)
  " gfj - fuzzy find in vim jump history (related to Ctrl-I Ctrl-O)
  " gfl - fuzzy find string in current opened file
  " gft - fuzzy find tags in current opened file
  " gfi - fuzzy find string under cursor in current file (may visual)
  " gfa - fuzzy find string under cursor in project directory (may visual)
  "
  " <C-J> - select next fuzzy candidate (in fuzzy find window)
  " <C-K> - select previous fuzzy candidate (in fuzzy find window)
  " <CR>  - open current selected candidate (double click will work too)
  " <TAB> - switch between normal mode / insert mode (in fuzzy find window)
  " p     - peek the current selected candidate in popup window
  " v     - open current selected candidate in vertical splitted window
  " x     - open current selected candidate in horizontal splitted window
  " Q     - add current selected candidate to quickfix list
  " L     - add current selected candidate to location list
  " d     - delete current selected candidate
  "

  set nocompatible
  set encoding=utf-8
  set et ts=4 sts=4 sw=4
  set fdm=syntax fdl=100
  set nu ru ls=2
  set hls is si
  set cinoptions=j1,(0,ws,Ws,g0
  set formatoptions-=cro
  set timeout nottimeout ttimeoutlen=10
  set mouse=a
  set listchars=tab:▸\ ,trail:⋅,extends:❯,precedes:❮
  set showbreak=↪
  set list
  "set noek
  "set rulerformat=%55(%{strftime('%a\ %b\ %e\ %I:%M\ %p')}\ %5l,%-6(%c%V%)\ %P%)
  "set switchbuf=usetab
  set undofile
  if has('nvim')
      set undodir=/tmp/nvim//,.
      set backupdir=/tmp/nvim//,.
      set directory=/tmp/nvim//,.
  else
      set undodir=/tmp//,.
      set backupdir=/tmp//,.
      set directory=/tmp//,.
  endif
  "set bg=dark


  syntax on
  filetype on
  filetype plugin on
  filetype indent on

  "let g:mapleader = ' '
  "let g:mapleader = ','
  let g:mapleader = 'g'

  nnoremap <silent> <F1> :wa<CR>:b#<CR>
  nnoremap <silent> <F2> :wa<CR>:bp<CR>
  nnoremap <silent> <F3> :wa<CR>:bn<CR>
  nnoremap <silent> <F4> :wa<CR>
  inoremap <silent> <F1> <ESC>
  inoremap <silent> <F2> <ESC>:wa<CR>:bp<CR>
  inoremap <silent> <F3> <ESC>:wa<CR>:bn<CR>
  inoremap <silent> <F4> <ESC>:wa<CR>
  inoremap <silent> <F8> <ESC>:wa<CR>:sh<CR><CR>
  nnoremap <F5> :AsyncTasks project-build project-run<CR>
  nnoremap <F6> :AsyncTask project-build<CR>
  nnoremap <F7> :AsyncTasks file-build file-run<CR>
  if has('nvim')
      nnoremap <F19> :AsyncTask project-config<CR>
  else
      nnoremap <S-F7> :AsyncTask project-config<CR>
  endif
  nnoremap <silent> <F8> :wa<CR>:sh<CR><CR>
  nnoremap <silent> <F9> :wa<CR>:NERDTreeToggle<CR><C-w>l:Vista!!<CR><C-w>h
  nnoremap <silent> <F10> :wa<CR>:QFix<CR>
  nnoremap <silent> <F12> /required from here<CR>
  "nnoremap <silent> <C-k> <C-w>k:q<CR>
  "nnoremap <silent> <C-j> <C-w>j
  inoremap kj <ESC>
  "inoremap <DEL> <ESC>
  "nnoremap <DEL> <ESC>
  "vnoremap <DEL> <ESC>

  nnoremap Z ZZ
  nnoremap Q :wa!<CR>:qa!<CR>
  nnoremap H ^
  nnoremap L $
  vnoremap H ^
  vnoremap L $
  "nnoremap z zz
  "vnoremap z zz
  "nnoremap <CR> O<ESC>cc<ESC>j

  tnoremap <C-\> <C-\><C-n>
  if !has('nvim')
      tnoremap <ScrollWheelUp> <C-\><C-n><ScrollWheelUp>
      tnoremap <ScrollWheelDown> <C-\><C-n><ScrollWheelDown>
  endif

  vnoremap Z :w !xsel -ib<CR><CR>
  " MacOS user should use this:
  "vnoremap Z :w !pbcopy<CR><CR>

  " no longer used vimspector:
  "nmap <S-F3> <Plug>VimspectorStop
  "nmap <S-F4> <Plug>VimspectorRestart
  "nmap <S-F5> <Plug>VimspectorContinue
  "nmap <S-F6> <Plug>VimspectorPause
  "nmap <S-F8> <Plug>VimspectorRunToCursor
  "nmap <C-S-F8> <Plug>VimspectorAddFunctionBreakpoint
  "nmap <S-F9> <Plug>VimspectorToggleBreakpoint
  "nmap <C-S-F9> <Plug>VimspectorToggleConditionalBreakpoint
  "nmap <S-F10> <Plug>VimspectorStepOver
  "nmap <S-F11> <Plug>VimspectorStepInfo
  "nmap <S-F12> <Plug>VimspectorStepOut
  "nmap <LEADER>= <Plug>VimspectorBalloonEval
  "xmap <LEADER>= <Plug>VimspectorBalloonEval
  "let g:ycm_semantic_triggers = {'VimspectorPrompt': ['.', '->', ':', '<']}
  "let g:cmake_vimspector_support = 1
  "let g:cmake_vimspector_default_configuration = {
  "\ 'adapter': 'vscode-cpptools',
  "\ 'configuration': {
    "\ 'type': '',
    "\ 'request': 'launch',
    "\ 'cwd': '${workspaceRoot}',
    "\ 'Mimode': '',
    "\ 'args': [],
    "\ 'program': '',
    "\ "setupCommands": [
    "\ {
    "\ "description": "Enable pretty-printing for gdb",
    "\ "text": "-enable-pretty-printing",
    "\ "ignoreFailures": 'true',
    "\ }
    "\ ],
    "\ }
  "\ }

  " rid annoying swap prompts:
  autocmd SwapExists * let v:swapchoice = "e"

  " goto last location on open:
  autocmd BufReadPost * if line("'\"") > 1 && line("'\"") <= line("$") | exe "normal! g'\"" | endif

  " open NERDTree on vim start:
  "autocmd VimEnter * NERDTree | wincmd p
  "autocmd BufEnter * if tabpagenr('$') == 1 && winnr('$') == 1 && exists('b:NERDTree') && b:NERDTree.isTabTree() | quit | endif

  " no longer used cmake4vim:
  "let g:cmake_usr_args = '-GNinja'
  "let g:cmake_build_target = 'main'
  "let g:cmake_build_type = 'Release'
  "let g:cmake_compile_commands = 1
  "let g:cmake_build_path_pattern = ["%s/build", "getcwd()"]

  " no longer used YouCompleteMe:
  "let g:ycm_confirm_extra_conf = 0
  "let g:ycm_error_symbol = '✗'
  "let g:ycm_warning_symbol = '⚠'
  "let g:ycm_filetype_whitelist = {"c": 1, "cpp": 1, "python": 1}
  "let g:ycm_min_num_of_chars_for_completion = 2
  "let g:ycm_show_diagnostics_ui = 1
  "let g:ycm_key_invoke_completion = '<c-z>'
  "let g:ycm_enable_diagnostic_signs = 0
  "let g:ycm_enable_diagnostic_highlighting = 1
  ""let g:ycm_show_diagnostics_ui = 0
  ""let g:ycm_key_list_select_completion = ['<TAB>']
  ""let g:ycm_key_list_previous_completion = []

  " no longer used ultisnips:
  "let g:UltiSnipsExpandTrigger="<c-s>"
  "let g:UltiSnipsJumpForwardTrigger="<tab>"
  "let g:UltiSnipsJumpBackwardTrigger="<s-tab>"
  "let g:UltiSnipsEditSplit="vertical"

  " no longer used vim-cpp-modern:
  "let g:cpp_attributes_highlight = 1
  "let g:cpp_member_highlight = 1

  " for vim-airline:
  let g:airline#extensions#coc#enabled = 1
  let g:airline#extensions#tabline#enabled = 1
  let g:airline#extensions#tabline#left_alt_sep = '|'
  let g:airline#extensions#tabline#buffer_nr_show = 0
  let g:airline#extensions#tabline#formatter = 'default'
  let g:airline#extensions#keymap#enabled = 1
  let g:airline#extensions#tabline#buffer_idx_mode = 1
  " 设置切换tab的快捷键 <\> + <i> 切换到第i个 tab
  nmap <silent> <leader>1 <Plug>AirlineSelectTab1
  nmap <silent> <leader>2 <Plug>AirlineSelectTab2
  nmap <silent> <leader>3 <Plug>AirlineSelectTab3
  nmap <silent> <leader>4 <Plug>AirlineSelectTab4
  nmap <silent> <leader>5 <Plug>AirlineSelectTab5
  nmap <silent> <leader>6 <Plug>AirlineSelectTab6
  nmap <silent> <leader>7 <Plug>AirlineSelectTab7
  nmap <silent> <leader>8 <Plug>AirlineSelectTab8
  nmap <silent> <leader>9 <Plug>AirlineSelectTab9
  "nmap <silent> <leader>1 :tab1<CR>
  "nmap <silent> <leader>2 :tab2<CR>
  "nmap <silent> <leader>3 :tab3<CR>
  "nmap <silent> <leader>4 :tab4<CR>
  "nmap <silent> <leader>5 :tab5<CR>
  "nmap <silent> <leader>6 :tab6<CR>
  "nmap <silent> <leader>7 :tab7<CR>
  "nmap <silent> <leader>8 :tab8<CR>
  "nmap <silent> <leader>9 :tab9<CR>
  "cabbrev o tab drop
  "cabbrev e tabe
  "cabbrev m tabm
  "cabbrev a tab ball
  "autocmd BufReadPost * tab ball

  " no longer used vim-terminal-help:

  "let g:terminal_key = '<c-=>'
  "let g:terminal_default_mapping = 1

  "inoremap ÏF <ESC>A
  "inoremap ÏH <ESC>I
  "nnoremap ÏH ^
  "nnoremap ÏF $
  "vnoremap ÏH ^
  "vnoremap ÏF $

  " no longer used YouCompleteMe:
  "nnoremap <LEADER><LEADER> :YcmCompleter GoTo<CR>
  "nnoremap <LEADER>[ :YcmCompleter GoToDefinitionElseDeclaration<CR>
  "nnoremap <LEADER>d :YcmCompleter GetDoc<CR>
  "nnoremap <LEADER>r :YcmCompleter RefactorRename<SPACE>
  "nnoremap <LEADER>f :YcmCompleter FixIt<CR>1
  "nnoremap <LEADER>y :call ToggleYcmDiagnostics()<CR><CR>:wa<CR>:e<CR>
  "func! ToggleYcmDiagnostics()
      "let g:ycm_show_diagnostics_ui = !g:ycm_show_diagnostics_ui
      "YcmRestartServer
  "endfunc

  " no longer used vim-ctrlspace:
  "if has('nvim')
      "let g:CtrlSpaceDefaultMappingKey = "<C-space> "
  "endif

  "let g:CtrlSpaceLoadLastWorkspaceOnStart = 1
  "let g:CtrlSpaceSaveWorkspaceOnSwitch = 1
  "let g:CtrlSpaceSaveWorkspaceOnExit = 1
  "if executable('rg')
      "let g:CtrlSpaceGlobCommand = 'rg --color=never --files'
  "elseif executable('ag')
      "let g:CtrlSpaceGlobCommand = 'ag -l --nocolor -g ""'
  "endif
  "nnoremap <silent><C-p> :CtrlSpace O<CR>

  " no longer used fzf.vim:
  "nnoremap <silent> <space>f :Files<CR>
  "nnoremap <silent> <space>g :GFiles<CR>
  "nnoremap <silent> <space>s :GFiles?<CR>
  "nnoremap <silent> <space>b :Buffers<CR>
  "nnoremap <silent> <space>a :Ag<CR>
  "nnoremap <silent> <space>r :Rg<CR>
  "nnoremap <silent> <space>l :Lines<CR>
  "nnoremap <silent> <space>o :BLines<CR>
  "nnoremap <silent> <space>h :History<CR>
  "nnoremap <silent> <space>: :History:<CR>
  "nnoremap <silent> <space>/ :History/<CR>
  "nnoremap <silent> <space>c :Commits<CR>
  "nnoremap <silent> <space>x :Commands<CR>
  "nnoremap <silent> <space>w :Windows<CR>
  "nnoremap <silent> <space>m :Maps<CR>

  "nmap <leader><tab> <plug>(fzf-maps-n)
  "xmap <leader><tab> <plug>(fzf-maps-x)
  "omap <leader><tab> <plug>(fzf-maps-o)

  "imap <c-x><c-k> <plug>(fzf-complete-word)
  "imap <c-x><c-f> <plug>(fzf-complete-path)
  "imap <c-x><c-l> <plug>(fzf-complete-line)

  " for LeaderF:

  let g:Lf_WindowPosition = 'popup'
  let g:Lf_PreviewInPopup = 1
  let g:Lf_PreviewCode = 1
  "let g:Lf_StlSeparator = { 'left': "\ue0b0", 'right': "\ue0b2", 'font': "DejaVu Sans Mono for Powerline" }
  "let g:Lf_PreviewResult = {'Function': 0, 'BufTag': 0 }

  let g:Lf_ShortcutF = "<leader>ff"
  "noremap <leader>ff :<C-U><C-R>=printf("Leaderf file %s", "")<CR><CR>
  noremap <leader>fb :<C-U><C-R>=printf("Leaderf buffer %s", "")<CR><CR>
  noremap <leader>fm :<C-U><C-R>=printf("Leaderf mru %s", "")<CR><CR>
  noremap <leader>ft :<C-U><C-R>=printf("Leaderf bufTag %s", "")<CR><CR>
  noremap <leader>fl :<C-U><C-R>=printf("Leaderf line %s", "")<CR><CR>
  noremap <leader>fx :<C-U><C-R>=printf("Leaderf command %s", "")<CR><CR>
  noremap <leader>f: :<C-U><C-R>=printf("Leaderf cmdHistory %s", "")<CR><CR>
  noremap <leader>f/ :<C-U><C-R>=printf("Leaderf searchHistory %s", "")<CR><CR>
  noremap <leader>fw :<C-U><C-R>=printf("Leaderf window %s", "")<CR><CR>
  noremap <leader>fj :<C-U><C-R>=printf("Leaderf jumps %s", "")<CR><CR>

  noremap <leader>fi :<C-U><C-R>=printf("Leaderf! rg --current-buffer -e %s", expand("<cword>"))<CR><CR>
  noremap <leader>fa :<C-U><C-R>=printf("Leaderf! rg -e %s", expand("<cword>"))<CR><CR>
  xnoremap <leader>fi :<C-U><C-R>=printf("Leaderf! rg --current-buffer -F -e %s", leaderf#Rg#visual())<CR><CR>
  xnoremap <leader>fa :<C-U><C-R>=printf("Leaderf! rg -F -e %s", leaderf#Rg#visual())<CR><CR>
  noremap <leader>fr :<C-U>Leaderf! rg --recall<CR>

  " should use `Leaderf gtags --update` first
  "let g:Lf_GtagsAutoGenerate = 0
  "let g:Lf_Gtagslabel = 'native-pygments'
  "noremap <leader>fr :<C-U><C-R>=printf("Leaderf! gtags -r %s --auto-jump", expand("<cword>"))<CR><CR>
  "noremap <leader>fd :<C-U><C-R>=printf("Leaderf! gtags -d %s --auto-jump", expand("<cword>"))<CR><CR>
  "noremap <leader>fo :<C-U><C-R>=printf("Leaderf! gtags --recall %s", "")<CR><CR>
  "noremap <leader>fn :<C-U><C-R>=printf("Leaderf gtags --next %s", "")<CR><CR>
  "noremap <leader>fp :<C-U><C-R>=printf("Leaderf gtags --previous %s", "")<CR><CR>

  " for coc.nvim:
  "let g:coc_global_extensions = ['coc-ccls', 'coc-pyright', 'coc-json', 'coc-git']

  " BEGIN_COC_NVIM {{{
  " References: https://github.com/neoclide/coc.nvim#example-vim-configuration

  set nohidden
  set nobackup
  set nowritebackup
  set updatetime=300
  set cmdheight=1
  set shortmess+=c

  " Always show the signcolumn, otherwise it would shift the text each time
  " diagnostics appear/become resolved.
  if has("nvim-0.5.0") || has("patch-8.1.1564")
    set signcolumn=number
  else
    set signcolumn=yes
  endif

  " Use tab for trigger completion with characters ahead and navigate.
  " NOTE: Use command ':verbose imap <tab>' to make sure tab is not mapped by
  " other plugin before putting this into your config.
  inoremap <silent><expr> <TAB>
        \ pumvisible() ? "\<C-n>" :
        \ <SID>check_back_space() ? "\<TAB>" :
        \ coc#refresh()
  inoremap <expr><S-TAB> pumvisible() ? "\<C-p>" : "\<C-h>"

  function! s:check_back_space() abort
    let col = col('.') - 1
    return !col || getline('.')[col - 1]  =~# '\s'
  endfunction

  " Use <c-space> to trigger completion.
  if has('nvim')
    inoremap <silent><expr> <c-space> pumvisible() ? coc#_select_confirm() : coc#refresh()
  else
    inoremap <silent><expr> <c-@> pumvisible() ? coc#_select_confirm() : coc#refresh()
  endif

  " Make <CR> auto-select the first completion item and notify coc.nvim to
  " format on enter, <cr> could be remapped by other vim plugin
  "inoremap <silent><expr> <cr> pumvisible() ? coc#_select_confirm()
                                "\: "\<C-g>u\<CR>\<c-r>=coc#on_enter()\<CR>"
  "inoremap <silent><expr> <space> pumvisible() ? (<SID>check_back_space() ? "\<space>" : coc#_select_confirm()) : "\<space>"

  " Use `[g` and `]g` to navigate diagnostics
  " Use `:CocDiagnostics` to get all diagnostics of current buffer in location list.
  nmap <silent> <leader>l[ <Plug>(coc-diagnostic-prev)
  nmap <silent> <leader>l] <Plug>(coc-diagnostic-next)


  " GoTo code navigation.
  nmap <silent> <leader>d <Plug>(coc-definition)
  nmap <silent> <leader>D <Plug>(coc-type-definition)
  nmap <silent> <leader>c <Plug>(coc-declaration)
  nmap <silent> <leader>C <Plug>(coc-implementation)
  nmap <silent> <leader>r <Plug>(coc-references)

  " Use K to show documentation in preview window.
  nnoremap <silent> K :call <SID>show_documentation()<CR>

  function! s:show_documentation()
    if (index(['vim','help'], &filetype) >= 0)
      execute 'h '.expand('<cword>')
    elseif (coc#rpc#ready())
      call CocActionAsync('doHover')
    else
      execute '!' . &keywordprg . " " . expand('<cword>')
    endif
  endfunction

  " Highlight the symbol and its references when holding the cursor.
  autocmd CursorHold * silent call CocActionAsync('highlight')

  " Symbol renaming.
  nmap <leader>R <Plug>(coc-rename)

  " Formatting selected code.
  xmap <leader>q <Plug>(coc-format-selected)
  "nmap <leader>q <Plug>(coc-format-selected)
  nnoremap <leader>q :Format<CR>

  " Restart CoC
  "nmap <silent> <leader>t :CocRestart<CR><CR>

  augroup mygroup
    autocmd!
    " Setup formatexpr specified filetype(s).
    autocmd FileType typescript,json setl formatexpr=CocAction('formatSelected')
    " Update signature help on jump placeholder.
    autocmd User CocJumpPlaceholder call CocActionAsync('showSignatureHelp')
  augroup end

  " Applying codeAction to the selected region.
  " Example: `<leader>aap` for current paragraph
  xmap <leader>a  <Plug>(coc-codeaction-selected)
  nmap <leader>a  <Plug>(coc-codeaction-selected)

  " Remap keys for applying codeAction to the current buffer.
  nmap <leader>ac <Plug>(coc-codeaction)
  " Apply AutoFix to problem on the current line.
  nmap <leader>aq  <Plug>(coc-fix-current)

  " Run the Code Lens action on the current line.
  nmap <leader>al <Plug>(coc-codelens-action)

  " Map function and class text objects
  " NOTE: Requires 'textDocument.documentSymbol' support from the language server.
  xmap if <Plug>(coc-funcobj-i)
  omap if <Plug>(coc-funcobj-i)
  xmap af <Plug>(coc-funcobj-a)
  omap af <Plug>(coc-funcobj-a)
  xmap ic <Plug>(coc-classobj-i)
  omap ic <Plug>(coc-classobj-i)
  xmap ac <Plug>(coc-classobj-a)
  omap ac <Plug>(coc-classobj-a)

  " Remap <C-f> and <C-b> for scroll float windows/popups.
  if has('nvim-0.4.0') || has('patch-8.2.0750')
    nnoremap <silent><nowait><expr> <C-f> coc#float#has_scroll() ? coc#float#scroll(1) : "\<C-f>"
    nnoremap <silent><nowait><expr> <C-b> coc#float#has_scroll() ? coc#float#scroll(0) : "\<C-b>"
    inoremap <silent><nowait><expr> <C-f> coc#float#has_scroll() ? "\<c-r>=coc#float#scroll(1)\<cr>" : "\<Right>"
    inoremap <silent><nowait><expr> <C-b> coc#float#has_scroll() ? "\<c-r>=coc#float#scroll(0)\<cr>" : "\<Left>"
    vnoremap <silent><nowait><expr> <C-f> coc#float#has_scroll() ? coc#float#scroll(1) : "\<C-f>"
    vnoremap <silent><nowait><expr> <C-b> coc#float#has_scroll() ? coc#float#scroll(0) : "\<C-b>"
  endif

  " Use CTRL-S for selections ranges.
  " Requires 'textDocument/selectionRange' support of language server.
  nmap <silent> <C-s> <Plug>(coc-range-select)
  xmap <silent> <C-s> <Plug>(coc-range-select)

  " Add `:Format` command to format current buffer.
  command! -nargs=0 Format    :call CocActionAsync('format')

  " Add `:Fold` command to fold current buffer.
  command! -nargs=? Fold      :call CocAction('fold', <f-args>)

  " Add `:OR` command for organize imports of the current buffer.
  command! -nargs=0 OrgImport :call CocActionAsync('runCommand', 'editor.action.organizeImport')

  " Add (Neo)Vim's native statusline support.
  " NOTE: Please see `:h coc-status` for integrations with external plugins that
  " provide custom statusline: lightline.vim, vim-airline.
  set statusline^=%{coc#status()}%{get(b:,'coc_current_function','')}

  " Mappings for CoCList
  " Using CocList
  " Show all diagnostics
  nnoremap <silent> <leader>la  :<C-u>CocList diagnostics<cr>
  " Manage extensions
  nnoremap <silent> <leader>le  :<C-u>CocList extensions<cr>
  " Show commands
  nnoremap <silent> <leader>lc  :<C-u>CocList commands<cr>
  " Find symbol of current document
  nnoremap <silent> <leader>lo  :<C-u>CocList outline<cr>
  " Search workspace symbols
  nnoremap <silent> <leader>ls  :<C-u>CocList -I symbols<cr>
  " Do default action for next item.
  nnoremap <silent> <leader>lj  :<C-u>CocNext<CR>
  " Do default action for previous item.
  nnoremap <silent> <leader>lk  :<C-u>CocPrev<CR>
  " Resume latest coc list
  nnoremap <silent> <leader>lp  :<C-u>CocListResume<CR>
  " Show git status
  nnoremap <silent> <leader>lg  :<C-u>CocList --normal gstatus<CR>

  " }}} END_COC_NVIM

  " for coc-snippets:

  let g:coc_snippet_next = '<tab>'

  " for vim-floaterm:

  let g:floaterm_wintype = 'split'
  let g:floaterm_position = 'botright'
  let g:floaterm_height = 12

  "let g:floaterm_keymap_new    = '<F1>'
  "let g:floaterm_keymap_prev   = '<F2>'
  "let g:floaterm_keymap_next   = '<F3>'
  let g:floaterm_keymap_toggle = '<C-t>'

  " for asynctasks.vim:

  let g:asyncrun_open = 6
  let g:asynctasks_term_pos = 'floaterm_reuse'
  let g:asynctasks_term_rows = 6
  let g:asynctasks_term_cols = 50
  let g:asynctasks_term_reuse = 1
  let g:asynctasks_term_focus = 0
  let g:asyncrun_rootmarks = ['.tasks', '.git/']

  function! AsyncTaskMultiple(first, ...)
      if len(a:000) >= 1
          if a:first == 0
              cclose
          endif
          let l:tmp = ""
          for task in a:000[1:]
              let l:tmp .= "'".l:task."',"
          endfor
          let l:tmp = l:tmp[:-1]
          let g:asyncrun_exit = "if g:asyncrun_code == 0 | call AsyncTaskMultiple(0, ".l:tmp.") | else | call AsyncTaskMultiple(0) | endif"
          exec "AsyncTask ".a:000[0]
      else
          let g:asyncrun_exit = ""
      endif
  endfunction
  command! -nargs=+ AsyncTasks   :call AsyncTaskMultiple(1, <f-args>)

  " for incsearch.vim

  map /  <Plug>(incsearch-forward)
  map ?  <Plug>(incsearch-backward)
  map g/ <Plug>(incsearch-stay)

  set hlsearch
  let g:incsearch#auto_nohlsearch = 1
  map n  <Plug>(incsearch-nohl-n)
  map N  <Plug>(incsearch-nohl-N)
  map *  <Plug>(incsearch-nohl-*)
  map #  <Plug>(incsearch-nohl-#)
  map g* <Plug>(incsearch-nohl-g*)
  map g# <Plug>(incsearch-nohl-g#)

  function! s:noregexp(pattern) abort
    return '\V' . escape(a:pattern, '\')
  endfunction

  function! s:incsconfig() abort
    return {'converters': [function('s:noregexp')]}
  endfunction

  noremap <silent><expr> z/ incsearch#go(<SID>incsconfig())

  " begin plugin list

  call plug#begin()

  "Plug 'vim-scripts/surround.vim'
  Plug 'scrooloose/nerdtree', {'on': 'NERDTreeToggle'}
  Plug 'archibate/QFixToggle', {'on': 'QFix'}
  Plug 'tpope/vim-fugitive'
  "Plug 'bfrg/vim-cpp-modern', {'for': 'cpp'}
  Plug 'vim-scripts/vim-airline'
  "Plug 'cskeeters/vim-smooth-scroll'
  Plug 'tikhomirov/vim-glsl', {'for': 'glsl'}
  "Plug 'junegunn/vim-slash'
  "Plug 'vim-scripts/a.vim', {'for': ['c', 'cpp', 'cuda']}
  Plug 'machakann/vim-swap'
  Plug 'preservim/nerdcommenter'
  "Plug 'preservim/vimux'
  "Plug 'peterhoeg/vim-qml', {'for': 'qml'}
  "Plug 'SirVer/ultisnips'
  "Plug 'honza/vim-snippets'
  "Plug 'neoclide/coc-snippets'
  Plug 'jackguo380/vim-lsp-cxx-highlight'
  Plug 'mbbill/undotree', {'on': 'UndoTreeToggle'}
  "Plug 'ilyachur/cmake4vim', {'on': ['CMake', 'CMakeBuild', 'CMakeInfo', 'CMakeRun']}
  "Plug 'puremourning/vimspector'
  "Plug 'ctrlpvim/ctrlp.vim', {'on': ['CtrlP']}
  "Plug 'ycm-core/YouCompleteMe', {'do': './install.py --clang-completer', 'for': ['c', 'cpp', 'python']}
  Plug 'neoclide/coc.nvim', {'branch': 'release'}
  "Plug 'junegunn/fzf', { 'do': { -> fzf#install() } }
  "Plug 'junegunn/fzf.vim'
  Plug 'skywind3000/asynctasks.vim'
  Plug 'skywind3000/asyncrun.vim'
  "Plug 'skywind3000/vim-terminal-help'
  "Plug 'aben20807/vim-runner'
  "Plug 'christoomey/vim-tmux-runner'
  "Plug 'viniciusgerevini/tmux-runner.vim'
  "Plug 'vim-ctrlspace/vim-ctrlspace'
  Plug 'haya14busa/incsearch.vim'
  Plug 'voldikss/vim-floaterm'
  Plug 'findango/vim-mdx', {'for': 'mdx'}
  Plug 'Yggdroot/LeaderF', { 'do': ':LeaderfInstallCExtension' }
  Plug 'liuchengxu/vista.vim', {'on': 'Vista!!'}

  call plug#end()

  if filereadable(".vim_localrc")
          source .vim_localrc
  endif
else
  nnoremap Z ZZ
  nnoremap Q :wa!<CR>:qa!<CR>
  nnoremap H ^
  nnoremap L $
  nnoremap cw vex
  "lisha add
endif




```
