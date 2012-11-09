Bkuilib - 基于金山开源项目的界面库[3.30更新]
本帖最后由 cntrump 于 2011-4-22 00:50 编辑


随着金山开源项目的增多, 界面库的结构也趋向于稳定.
现在的界面技术比较火的就是 DirectUI, 然而高深的技术总是掌握在大公司手里.
对于我等小菜, 只能把期望寄托在卫士的主界面上了. 毕竟它是有码的.

现在只是简单地从 oss 中剥离出了卫士.并取名叫 Bkuilib
长远的目标是做成一个独立开源的界面库, 以帮助加快 UI 的开发.

https://bitbucket.org/cntrump/ok.bkuilib

    hg clone https://cntrump@bitbucket.org/cntrump/ok.bkuilib

复制代码
开发环境是 VS2005 sp1 + sdk6.0 (或以上)
欢迎各位兄弟加入.

附加说明:
如果 VS2005 sp1 使用高版本的 SDK 编译时出现错误提示:
fatal error LNK1103: 调试信息损坏；请重新编译模块
请打上微软官方提供的补丁:
https://connect.microsoft.com/Vi ... px?DownloadID=18623

sdk 7.1 下载:
http://www.microsoft.com/downloa ... 5-b44b-543dc8c33a20

=====================
更新说明：
2011-03-30
改动：
1. 去除多余的库，仅保留与界面相关的库。
2. 将导致编译出现警告的函数改为安全的函数。
3. 调整一些头文件的存放目录。

目录结构：
bkuilib - 界面库文件
SkinTest - 用于测试界面库的项目

使用方法：
请先参考 SkinTest 示例项目。

依赖的第三方库：
WTL 8.0 或以上版本
TinyXML 2.6.1

编译环境：
VS 2005 sp1 + sdk 6.1

by cntrump

#########################################################################

http://bbs.code.ijinshan.com/viewthread.php?tid=949&extra=page%3D1%26amp%3Bfilter%3Ddigest
