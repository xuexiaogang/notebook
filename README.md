# zjuchenyuan's Notebook

My notebook about technology, for lookup and share

# 目录

## [Python](Python.md)
>* [语言勾勒QuickStart](quickstart.html)
>* 设置pip源
>* 反弹shell 获得tty
>* requests使用多IP请求
>* [Python多线程模板](code/MultiThread_Template.py)
>* http.server（BaseHTTPServer）并发性改善
>* 无root权限安装Python
>* 中文输出乱码问题解决
>* pycodestyle检查代码风格
>* 生成随机字符串
>* 别对大的list循环使用in，应该改用set
>* 解决Python.h: No such file or directory
>* 二进制字符串转普通字符串
>* 十六进制字符串转bytes字符串
>* 用Python3写PAT心得
>* 用requests进行post
>* 通过tkinter获取/修改剪贴板
>* 符号数与无符号数转换
>* 使用signal.SIGALRM在限定时间后退出进程
>* 捕捉用户的Ctrl+C
>* 使用signal.SIGALRM实现定时器
>* 使用pdb进行调试
>* [机器学习-决策树](code/decisiontree.py)
>* 使用Python开发阿里云函数计算后端服务
>* 修复Linux下gbk编码的文件名

## [BAT 批处理](BAT.md)
>* 快速打开cmd
>* 并列语句语法
>* 循环for
>* 结束进程taskkill
>* 内存整理free
>* 睡一会SleepX
>* 判断文件夹存在
>* 创建硬链接mklink或者fsutil hardlink create
>* 端口转发
>* [保持RVPN不断开](code/RVPNKeepAlive.bat)
>* vpn静态路由配置
>* 进入休眠
>* 快速进入系统代理设置，不用打开IE

## [C 语言](C.md)
>* 关于Dev C++
>* 输入的问题，建议用gets和sscanf
>* C++用sstream代替sprintf
>* g++省略拷贝构造函数的问题
>* [数据结构]树的遍历
>* 对一个const的vector使用迭代器要用const_iterator
>* 小心未初始化的变量
>* 获取文件大小
>* 题目解析 (结构指针、结构数组...)

## [CDN](CDN.md)
>* ·UPYUN 又拍云
>*    管理文件可以用FTP，UpyunManager，Upx
>*    python规则刷新，python调用官方API进行URL刷新
>*    使用upyun提供的webp功能节省流量
>* ·Qiniu 七牛
>*    使用qshell上传文件夹

## [cURL](cURL.md)
>* 模拟浏览器请求
>* 基本教程
>* 还可以循环哟

## [Developer](Developer.md)
>* 保持技术精进
>* 如何明智地向程序员提问

## [Docker](Docker.md)
>* 安装
>* 加速镜像下载
>* 旧版本卸载
>* 获得容器的ip
>* 导入导出容器
>* 解决iptables failed问题
>* 迁移Docker文件夹到其他硬盘
>* 解决debian等容器没有ifconfig的问题
>* 设置容器低权限用户运行
>* 设置容器/etc/resolv.conf和/etc/hosts
>* 容器限制参数设置
>* 快速部署ftp
>* 快速部署wordpress

## [Favorites](Favorites.md)
>* Intel i386 手册 及 勘误
>* ASCII字符图案生成
>* 解释Shell命令每个参数
>* 安全会议的排名 建议读的论文
>* [More Links](Links.md)
>* Git Emoji

## [Git](Git.md)
>* 立即使用
>* git clone加速 --depth 1
>* [git push加速](code/ssgit.txt)
>* git push免密码
>* bash工作环境(别名,自动完成,dirty提示)设置
>* 好玩的命令们
>* gitignore负向选择
>* 补上commit漏掉的文件 --amend
>* 密码泄露查作者 blame
>* 文件一次性改太多了，拆成多次提交 add -p
>* 本地忽略一些个人的修改
>* 本地创建branch后push操作git push -u

## [Github Project Recommendation](GithubProjectRecommendation.md)
>* 视频下载you-get
>* 记忆手段Anki
>* 在线评测OnlineJudge
>* Python也能用来解方程sympy
>* 让网站链接秒开InstantClick

## [Java](Java.md)
>* 一些Java与C++的不同之处
>* 异常处理中的资源释放问题
>* JVM启动时的内存参数
>* [修复Struts2的S2-045漏洞](S2-045.md)

## [JavaScript](JavaScript.md)
>* 使用本地存储localStorage
>* [随机字符串生成](http://py3.io/p.html)
>* 异常
>* 使用phantomjs爬取网页
>* jQuery绑定"变为可见"事件
>* 读取GET参数

## [Jekyll](Jekyll.md)
>* 碰到过的坑
>* 配置代码高亮并显示行号
>* 解决Github Metadata Warning
>* 安装Jekyll

## [Linux-setup](Linux-setup.md)
>* [网络加速privoxy](code/ssprivoxy.txt)
>* 配置有线静态IP
>* 使用ifconfig修改ip后记得要重新配route
>* 配置apt源以加速国内环境下apt速度
>* 单网卡获得多个IP
>* 锐速安装
>* 解决apt依赖问题
>* UnixBench性能评测
>* 清除内存缓存
>* 使用iptables封ip
>* iptables只允许特定IP访问某端口
>* 无root权限使用screen
>* screen的用法
>* 两条iptables实现端口转发，暴露内网端口
>* 保护重要系统文件防止被删chattr +i
>* 时区设置
>* 查看CPU核心个数
>* 非交互式添加用户
>* 简单OpenVPN配置
>* 时区时间设置
>* 快速地格式化大分区ext4

## [Linux-SSH](Linux-SSH.md)
>* 客户端不同服务器使用不同的id_rsa
>* 换个端口开启一个临时的sshd
>* ssh反向代理
>* 启用SSH密钥登录后两步验证

## [Linux-cli](Linux-cli.md)
>* 查看内置命令的帮助
>* grep搜索帮助文档
>* 帮助文本的grep 用2>&1
>* 各种解压命令
>* 当前目录文件全文搜索
>* 统计当前文件夹代码行数
>* 查看给定文件列表的文件大小
>* wget慢慢下载
>* touch修改时间戳
>* 去掉Ubuntu默认情况下ls的颜色
>* 换行方式修改
>* iodine--使用DNS传输数据
>* 远程控制Windows
>* 统计以特定字符串开头的文件数目
>* hexdump查看字符内部编码
>* 子目录大小排序
>* 安装ffmpeg
>* 修改readonly的变量
>* 永久等待 sleep infinity
>* zmap扫描整个网段特定开放端口
>* 对ip列表批量测试redis未授权漏洞
>* 使用ImageMagick对图像进行裁剪
>* 查找0字节的文件并删除
>* 用vim去除\r换行符 :set ff=unix
>* watch持续观察命令输出
>* 树莓派2上编译Truecrypt 7.1a，使用make -j5 -l4加速编译
>* scp目录断点续传
>* 使用wget代替scp传输文件夹 避免无谓的加密性能损失（适用于树莓派）

## [Linux-backup](Linux-backup.md)
>* 一个良好安全的备份计划至关重要

## [MySQL](MySQL.md)
>* 查看表结构 desc
>* MERGE存储引擎
>* 删除表的冗余
>* 修改表 alter table
>* [将中文转为拼音的函数](code/pinyin.sql)
>* 从路径URL获取文件名称
>* 查询优化--explain发现出现了using filesort；内存表索引的选择
>* 内存表The table is full的解决
>* replace函数替换文本
>* 简单的split功能，文本转数字
>* mysqld配置参数调优
>* 支持emoji，从utf8升级到utf8mb4

## [Nginx](Nginx.md)
>* Nginx思考题
>* 普通资源允许POST
>* 不带后缀的文件当成php执行
>* 获得Let's encrypt免费https证书
>* 配置安全的https
>* 反向代理之替换网页、JS中的文本
>* root与alias的区别
>* 在bash on win10上使用Nginx
>* Nginx允许列目录

## [PHP](PHP.md)
>* 显示错误信息
>* 全页面iframe

## [Ubuntu桌面版](Ubuntu.md)
>* 安装Google拼音后用上云候选功能

## [VirtualBox](Linux-VirtualBox.md)
>* 下载安装，一定记得安装额外包
>* 创建虚拟机，设置虚拟机选项
>* 启动虚拟机
>* 远程控制虚拟机

## [WinSoftware](WindowsSoftware.md)
>* Emeditor
>* Everything
>* Sysinternals Utilities
>* CLOC代码统计利器
>* U盘安装原版系统盘
>* WinRAR
>* BurpSuite
>* BEncode Editor
>* Win10 Windows照片查看器

