# first-c-app
第一个c/c++ 项目

# 搭建环境（参考网站https://www.jianshu.com/p/8933ebdac814）
1. 安装mingw-w64：http://www.mingw.org/ 点击下载页面的 mingw-get-setup.exe连接进行下载，双击安装。安装完会生成桌面图标，可以通过该桌面程序管理管理组件安装和更新，删除
2. 配置环境变量 Path变量中添加条目C:\MinGW\bin；C:\MinGW为上面的安装目录，自定义安装可能不同；通过gcc -v 命令查看安装是否成功（MinGW安装并导入文件后，其中包含了C与C++这两个编译环境，测试语句分别为gcc --h与g++ --h）C++程序，记住后缀为.ccp；如果你不清楚头文件路径，可以使用命令打印头文件的路径：gcc -v -E -x c++ -
