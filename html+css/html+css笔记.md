* 课程设计
  * 没有ppt
  * 用的是书本
    * 《css权威指南》&《the book of css3》
    * 《eloquent javascript》《JS编程精解》
  * 书本没有的内容，大多数都md的讲稿
  * 计算机网络
  * 算法
  * 基础
  * 课程是面向零基础的，所以一开始的**部分内容**对**一些**同学来说会过于简单

* 你免费在平台上播，为什么我要花钱听？

* 软件安装
  * Chrome&FireFox
    * https://www.google.cn/chrome/
  * VSCode
    * https://code.visualstudio.com/Download
  * git
    * https://git-scm.com/downloads
  * Node.js
    * https://nodejs.org/en/download/

* 设置搜索引擎为bing.com

* 前端已死?
  * 前端死了没?
  * 前端什么时候死?
  * 前端死到什么程度了?
* 多个角度看待
  * 这个话从哪里传出来的
  * 前端后端人数差不多,后端死没死?
  * 在校大学生
  * 会有人像十几年前的我一样对前端感兴趣
  * 大学计算机教育质量有因为“前端已死”而变好吗？
  * 未来的高手只能由现在已经存在的从业者成长而来吗?
  * 约400w从业者
  * 从业人员混杂,上下限差距非常巨大

* 练习打字
  * 标准键位,两个食指分别放在f和j上
  * 双拼 https://api.ihint.me/shuang/
  * 标点符号
  * 全半角
    * ！ ! ( （
    * 打字效率跟学习效率息息相关

* 为什么用课本而不是自己做ppt?

* 几篇文章
  * 提问的智慧 https://lug.ustc.edu.cn/wiki/doc/smart-questions/
  * 花十年学编程 http://daiyuwen.freeshell.org/gb/misc/21-days-cn.html
  * 花两年面试一个人 https://www.cnblogs.com/zwblog/articles/5322423.html

* 数学知识回顾（略）
  * 坐标系，函数，集合，数列，映射，导数
* 二进制
  * 二进制的转换
* 二进制与十六进制
* 二进制竖式加法

* 计算机为什么要使用二进制?
  * 一个原因是误差（也有其它原因）
  * 为什么是二进制而不是三进制或其它进制呢？
    * 二进制足够简单
    * 二进制足够使用
    * 数学中的已经存在的理论基础：布尔代数为基础 命题逻辑
  * 二进制真的够用吗？
  * 比特，字节，字，双字,  K, M,G,T,P
  * bit, byte, word, dword,KB,MB,GB,TB,PB
  * 数字信号 与 模拟信号
  * 模拟信号：把设备里读出来的物理量直接使用
    * 适合远距离传输
  * 数字信号：如果把模拟信号的大小/高低/强弱按01来理解，就是数字信号
    * 适合近距离传输
  * Modem 调制 解调 器 就是做这种信号之间转换的（光纤 调制 解调 器）
    * 传统猫
    * 光猫

* 编码
  * 数值的表示（先略）
  * 文字的表示与编码
    * ascii
    * eascii
    * GB2312/GBK 国标&国标扩展码
    * unicode 万国码,只是为全球每个国家的每个字符指定了唯一编号
  * 图片的表示以及图片格式介绍
    * 计算机中颜色的表示
      * RRGGBB
    * bmp
    * png比较适合存储屏幕截图,无损压缩,支持256级的透明
    * jpg比较适合存现实世界的照片(颜色是渐变的),有损压缩,肉眼一般看不出来
      * 可以想象,各种图片格式的文件头(也就是文件最前面的一些字节)都会直接保存图片的分辨率
      * 不支持透明
    * gif
      * 动图,gif图片往往尺寸比较小
      * 每张图只有256种颜色
      * 支持两级透明
      * 但是这256种颜色是从1670w色中选取的
        * 图片尺寸小需要的颜色数量自然就少
        * 可以节省存储空间
          * 它是通过**颜色表**来实现的
          * 实际图片的内容存储时一个像素点只需要一个字节而不是三个字节
      * 它只动图的第一张画面存储的是完整的内容,后续存储的是相对于前一张画面变化的内容
        * 视频文件也是这样的
    * 编码的两个重要指标
      * 要能还原出原始信息
      * 要尽量节省空间
    * psd
      * PhotoShop的**工程文件**,它里面存储了对这个图片所有操作
      * 包括操作记录,图层,图层的名字,文字,文字的字体
      * 这种文件往往特别大,一般都在100M以上
      * 这种文件肯定不会用在网页上
      * 浏览器就不认识这种格式的图片文件
    * webp
      * 相对来讲比较新的格式,由谷歌发明
      * 有损压缩
      * 比jpg效果要好:
        * 同一张图片,文件大小相同,webp画质更好
        * 同一张图片,画质相同,webp文件更小
      * 支持透明
  * 文本文件与二进制文件
    * txt, py, js, html, c, java, cpp, css, log, ini,
  * 文件原始内容的查看
    * WinHex
    * Binary Viewer
    * xxd命令


* 命令行（Command Line）
  * 不同系统命令行的区别
    * windows(CMD,PowerShell)
    * linux/mac/wsl(bash,zsh)
    * 安卓 / Termux (bash,zsh)
  * 不要恐惧命令行，其实只是软件的展示形式不一样
    * 其实命令行里有各种各样的软件
      * 工具软件
        * 编辑器（vi）
        * 磁盘空间分析（ncdu,df）
        * 聊天（weechat）
        * 流量监控（nload）
        * 任务管理器（htop）
        * 多窗口（tmux）
        * 下载工具（curl,wget）
        * 版本管理（git）
        * 文件哈希/指纹计算（md5，sha1等）
      * 游戏
        * nudoku数独
        * pacman吃豆人
        * npush推箱子
        * sssnake贪吃蛇
        * 2048
        * tetris俄罗斯广场
      * 搞怪软件等
        * sl 小火车
        * cmatrix 黑客帝国数字雨
        * cbonsai -S 画盆景
        * pipes.sh 画管道
  * 命令行的基本操作与理解
    * 两个**重要概念**
      * 当前工作目录
      * 路径列表
        * 当我们在命令行里输入一个ls命令时,其实它会去查找一个叫ls.exe(windows上)的程序并执行它,它不会在整个电脑里全局搜索,而是只在特定的一些文件夹内搜索
          * 这些特定的文件夹就叫做路径列表
    * 命令的选项/参数
      * -l --long
      * -h --help
      * -m --mode  -m autopilot
  * 常用命令
    * ls  list
      * 列出当前文件夹的内容
      * -l 详细信息
      * -h 给人看,文件大小会选择合适的单位,必须跟-l一起用
      * -a 显示所有文件夹,包括隐藏文件,其实就是以.开头的文件
    * cat
      * concatenate 拼接
      * 它接收多个文件名做为参数
      * 输出所有文件的内容
      * 当只接一个文件名做为参数时相当于显示这个文件的内容,一般就是这么用的
    * cp  copy
      * 复制一个文件
      * cp  a.txt  b.txt
    * mv   move
      * 移动一个文件
      * mv   a.txt   b.txt
      * mv  a.txt    文件夹1
    * rm   remove
      * 删除一个文件
      * 删除文件夹
        * rm -r 文件夹名称
          * -r 表示递归删除
    * mkdir
      * 创建文件夹
      * mkdir  文件夹名
    * rmdir
      * 删除文件夹
      * 它只能删除空文件夹
        * 非空就会报错,说文件非空,不给删
    * cd  change directory
      * 改变当前工作目录
      * 命令行的路径中,~一般代表用户主目录,类似于"我的文档"文件夹
      * 空着运行运行该命令是直接进入~文件夹
      * cd 相对路径   进入到相对路径所对应的文件夹中
        * 什么是相对路径
          * 即相对于某个基准文件夹的路径
          * 不以盘符或/开头就是相对路径,在命令行中一般就是相对于当前工作目录
            * 如何计算呢?
              * 直接把当前工作目录与该相对路径拼接,拼接时注意是拼接位置要增加一个斜杠
            * 注意绝对路径(以/开头)就不用拼了
          * 相对路径中有两个特殊符号
            * .. 表示上一层文件夹
            * .  表示当前文件夹
            * 在实际操作中,.直接删掉,..与其左边的项"中和/抵消"(当..左边没有项的时候,只删它自己)
    * pwd print working directory
      * 输出当前工作目录的完整路径
    * touch
      * 创建一个空文件
        * touch a.txt
      * 如果文件存在的话,更新文件的最后修改时间
    * echo
      * 输出内容
    * which
      * 可以告诉我们某个命令具体对应哪个文件
    * date
      * 查看日期
    * split
      * 把一个大文件给拆成多个小文件
    * exit
      * 退出命令行


  * 命令行快捷键
    * ctrl+L 清屏
      * clear命令也可以
    * ctrl+A 将光标移动到最前面
    * ctrl+E 将光标移动到最后面
    * ctrl+C 强行停止当前正在运行的命令
      * 能够对绝大多数命令行程序生效
    * ctrl+R 搜索命令历史
    * 按上下键可以切换最近输入过的命令是很重要
    * tab 自动补全
  * 报错

  * 几个运算符
  * 导向运算 |
  * 输出运算 >
  * 追加运算 >>

  * 命令行脚本文件




  * markdown语言（乐子词：markdown程序员）
  * 标记语言
  * 标题 #
  * 段落
  * 列表 *
  * 链接 []()
  * 图片 ![]()
  * 加粗 **
  * 引用 >
  * 水平分隔 ---
  * 代码块  ```
    * 行内代码   `aaa`
  * 表格
    * | a | b | c |
    * |:---:|:---:|:---:|
    * | 1 | 2 | 3 |
  * 看着这个页面 https://github.com/facebook/react
    * 写出它的md源代码
* html（Hyper Text Markup Language）
  * 标记方式不同
    * 但是与数学公式中括号的嵌套方式相同
      * 即树状结构
        * 书的目录
        * 公司组织架构
        * 空间的嵌套
        * 数学公式
        * 编程语言（programming Language）的语法规则
      * 如果从一个合法的树状结构中提取（去掉）一个合法的树状结构，留下来的依然是一个合法的树状结构
      * 如果对应到html语言中，则是从一段合法的html嵌套中提取出一小段合法的html嵌套，则保留下来的依然是合法的嵌套结构
  * 属性的写法
    * 布尔属性
  * 自闭合的写法
  * 先抄写一个html页面
    * https://csszengarden.com/ 这个页面的源代码
  * 后续讲解各种标签




* git
  * git不是git bash
    * git bash是命令行程序的一个运行环境
      * git/ls/pwd/nudoku/...都是要在命令行环境下运行的
      * linux自带命令行环境的
      * windows只自带自己的系统的命令行环境，不能直接使用linux的
        * 但是linux系统的命令行环境更流行
          * 所以我们在windows上装一个软件来模拟/提供类linux的命令行环境
  * git也不是github
    * git是一个软件
    * github是一个网站
  * 它是一个命令行软件
  * 版本控制
    * 论文.doc
    * 论文修改版.doc
    * 论文-修改版2.doc
    * 论文-最终修改版.doc
    * 论文-最终再也不改版2.doc
  * 所有命令现场写
    * git init 初始化当前工作目录为一个git仓库(或者说是我们将用git来管理这个文件夹里的文件版本)
    * git add file1 file2 file3 将文件添加到暂存区,可以一次性添加多个文件
    * git add . 把当前文件夹中所有的文件都添加到暂存区
    * git status 查看当前仓库的状态,可以看到暂存区状态,工作目录状态
    * git config --global user.email "you@example.com"
    * git config --global user.name "Your Name"
    * git commit -m "对这次提交的描述"
    * git diff 显示工作目录与暂存区的差异
    * git diff --cached 显示暂存区与最近的一次提交之间的差异
    * git log 查看提交记录/日志
      * 保存代码时在最后一行额外加一个回车可以减少git diff信息的噪音
    * git commit -a -m "woiefjowiefj" -a 表示先添加所有文件后再提交
      * 基本等价于
      * git add .
      * git commit -m "owijfe"
    * git的暂存区可以实现一次性修改多个文件但分多次提交
      * 在修改的多个文件从业务逻辑上是不一样的时候,应该分开提交
    * git add -p 一段一段添加,git会区分出同一个文件中不同部分的变更,每一部分可以分别添加到暂存区
    * git restore file 将文件从暂存区取出放入工作目录,替换同名文件
    * git restore --staged <file> 将文件unstage,即add的还原操作(其实是将文件从最近一次提交中取出来放入暂存区)
    * git commit --amend -m "修改了论文的末尾"
      * 如果最近的一次提交出来了纰漏,则可以通过--amend来进行修复,它会把你最后一次的提交删掉,用这个提交来替代
    * git config --global alias.ci commit 创建全局git命令别名commit就可以用ci替代了
    * git config --global alias.st status
  * 去注册一个github.com网站的账号,用户名不要用数字开头,用字母开头
    * git保存/管理的是**变更**,变更包括:
    * 内容的增加、删除
    * 文件的删除
    * 文件自身改名
    * 文件位置移动
    * 等
  * 将代码推到github或其它类似网站
    * 推送到本机的另一个文件夹
  * git remote add origin git@github.com/xieranmaya/git2024.git
    * 为当前文件夹的仓库添加远程仓库
      * origin是为该远程仓库起的名字
      * 后面一长串是远程仓库的实际地址
  * git remote set-url origin NEW_URL
    * 设置某个远程仓库的地址(在地址填错或需要修改地址的情况下使用)
      * origin是需要修改地址的远程仓库的名字
  * git remote remove origin
    * 删掉某个远程仓库
  * git push origin master
    * 将master分支的历史推送到origin这个远程仓库中
  * git push -u origin master
    * 推的同时设置master与origin仓库的关联关系
    * 后续不需要再每次指定仓库和分支了,只需要用git push就可以了
  * git push
    * 将当前分支推送到与其关联的远程仓库里

  * 首次push的过程中可能出现的报错或输出
    ```
    The authenticity of host 'github.com (20.205.243.166)' can't be established.ECDSA key fingerprint is sHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgufQM.Are you sure you want to continue connecting (yes/no/[fingerprint])?y
    Please type 'yes' , 'no’ or the fingerprint: yes
    ```
    意思是远程服务器身份无法确认,通过出示远程服务器的指纹问你是否确认跟这个服务器建立连接
    ```
    warning: Permanently added 'github.com,20.205.243.166’(ECDSA) to the 1ist of known hosts.
    ```
    在你输入完yes后,系统会将该服务及其指纹存到当前计算机上,未来如果该服务器的指纹不是这个,那么就会报错并且拒绝连接

    ```
    git@github.com: Permission denied (pub1ickey) .fatal:could not read from remote repository.
    Please make sure you have the correct access rightsand the repository exists.
    ```
    github无法确认目前推送者的身份,所以告诉你没有权限
    解决方案是在自己电脑上生成一对公私钥,并将公钥传到github网站自己的账号里
      Settings - SSH & PGP Keys菜单下

    ```
      git push
      fatal: The current branch master has no upstream branch.
      To push the current branch and set the remote as upstream,use
    ```
      当前分支没有关联的远程仓库,所以无法push
      要么push时指定远程仓库的完整地址
      要关先为当前分支关联一个远程仓库
  * git pull 把远程那些你本机没有的"变更"拉取到本机并且合并到相应的文件中
  * vi编辑器,命令行里编辑器
    * 两个主要模式:
      * 常规模式(浏览模式)
        * 按Esc进入
      * 编辑模式
        * 按i进入
      * 命令模式
        * 按:进入
          * 进入之后再输入具体的命令,但是命令全是一个字母
          * :w 存盘
          * :q 退出,但如果对文件做了修改则不能退出
          * :q! 强制退出
          * :wq 先存盘再退出
  * vimtutor   vi编辑器的自带教程命令
  * 用vscode管理git仓库
  * GitHub Pages 服务
    * 某个仓库如果开启了pages服务
    * 则访仓库的文件可以在  USERNAME.github.io/REPO_NAME/FILE_PATH 访问到
    * xieranmaya.github.io/git2024/page.html 访问到
  * ssh-keygen 生成公私钥对，一路回车就行了，生成好放在~/.ssh文件夹里面
  * 作业:
    * 把你那天抄写的html页面和md页面
    * 分别让它们能够在以下两个地址访问到
      * https://USERNAME.github.io/miao/css-zen-garden.html
      * https://USERNAME.github.io/miao/react.md
  * git init --bare 创建一个裸仓库,即没有工作目录的仓库,仅相当于普通仓库里的.git文件夹
    * 然后当前文件夹的路径就可以做为一远程仓库的地址供其它本地仓库来推送代码
  * git  clone  地址  目标文件夹
    * 将远程地址对应的创建克隆到本地的目标文件夹
      * 会克隆其所有的历史记录




* 介绍常用html标签
  * doctype 文档类型,其实它不是标签,而是一声明,类似于"文件头"
  * html 根标签
  * head 页面的元信息(meta info 页面的自身的信息)
  * title 页面的标题,内部只能有纯文本,不能再有标签
  * meta
    * <meta name="" content="">
      * name是meta信息的名字
      * content是meta该名字对应的meta信息的值
    * <meta name="charset"  content="UTF-8"> 设置页面的编码方式
    * <meta name="keywords" content="小米手机,小米14,小米14 Pro"> 设置这个页面的关键词,方便搜索引擎
      * 搜索引擎的原理:
        * 它是将全球所有的页面都下载回去了
        * 每次用户搜索的时候都是他在自己的服务器上搜索的
  * body 页面中需要显示的内容都放进这个标签里
  * a
    * target 设置链接在新窗口还是在当前窗口打开
      * _self 在当前窗口打开
      * _blank 在新窗口打开
    * href 设置链接目标
      * 可以填写完整地址
      * 可以填写mailto:xxxx@qq.com
      * 可以填写tel:1243123
      * 可以填写相对路径  ./foo/bar/baz.html
        * 相对路径相对于当前这句代码所在文件的文件夹
          * 即地址栏中?号前面最后一个斜杠及其之前的东西

          https://output.jsbin.com/qozugulujo/foo/bar/baz.html
        * 注意:在网页里,地址栏往往是一个文件的路径
        * 而在命令行里,工作目录一定是一个文件夹,就算它后面没有斜杠
        * 而相对路径永远是相对于文件夹来计算的而不是相对于文件

  * p 段落
  * img  图片,,自闭合标签
    * src="" 设置图片地址
    * alt="" 设置图片的替换文字,在图片加载失败时显示
    * width="" 设置图片的宽度
    * height="" 高度
  * h1,h2,h3,h4,h5,h6
    * 一般来讲,一个页面最好只有一个一级标题
  * strong/em/i/u/b/
  * 块级标签
    * 自动占满一整行的空间
    * h123456,p,ul/ol/li
  * 行内标签
    * 能够跟其它普通文字在同一行
    * strong/em/i/u,a,img
  * ul/ol(unordered list,   ordered list, 无序列表,有序列表)
    * li(list item,列表项)
    * ul/ol里必须只能直接放li标签,不能放别的标签
    * li里就可以随意书写标签了
  * dl/dt/dd
  * br,hr 自闭合标签
  * div
  * span

  * 标签的通用属性/全局属性(即可以用在每个标签上的属性)
    * class 标签的分类,每个标签可以有多个分类,用空格隔开
    * id 标签的唯一id,类似于身份证号码,每个标签的id必须唯一,不能与其它标签的id重复
    * title 鼠标悬浮时的工具提示
    * lang 设置这个标签内文字的语言
    * style 设置标签的样式

  * a标签
      * anchor, 锚
      * 语义是一个链接，链接地址写在  href（Hyperlink REFerence）属性里
          * 可以链接到的类型非常多，而且一般来说是可扩展的
              * 绝对网址，fullpath
                  * `<a href="https://jd.com/">京东</a>`
              * 页内特定位置跳转地址
                  * `<a href="#pos1"></a>`
                  * 例：https://html.spec.whatwg.org/multipage/grouping-content.html#the-dl-element
              * 其它页特定位置跳转地址
                  * `<a href="http://jd.com/#footer"></a>`
              * 这个在书目的章节跳转在使用的比较多
              * 相对路径
                  * <a href="https://baidu.com/">baidu</a>
                  * <a href="a.html">baidu</a>

                  * `<a href=".././../a/b/../index.html"></a>`
                  * `<a href="./index.html"></a>`
                  * `<a href="../index.html"></a>`
                    * http://a.com/a/b/c.html
                      * http://a.com/a/b/index.html
                      * http://a.com/a/index.html
                  * `<a href="/index.html"></a>`
                    * http://a.com/a/b/lkj/adsfa/sdf/c.html
                    * http://a.com/index.html
              * 电子邮件
                  * `<a href="mailto:aaa@bbb.com"></a>`
                  * `<a href="mailto:aaa@bbb.com?title=1&subject=2&content=3"></a>`
                    * 需要在电脑安装邮件客户端
              * 电话号码　tel:18611075877
                * 主要用在手机页面上
              * QQ/taobao 临时会话
                * tencent://temp-chat?QQ=285696737
                * thunder://ghjk;adfklasdhfkweuhfasdlfk
              * 等等等等
                  - thunder://LKDJOIE7436239/
              * 空的href属性 href=""  href="."
                  * 链接到当前页面
                      * 所以仅以#开头的值是中转到当前页面的特定位置
                  * <img src="">
                  * 类似的，如果一个img标签的src属性为空，也将对应当前页面地址
                      * https://www.nczonline.net/blog/2009/11/30/empty-image-src-can-destroy-your-site/
      * target属性
          * 可以指定在哪个窗口打开链接
              * 几个特殊值,关键字
                  * _blank，链接在空白的窗口显示，也就相当于新打开一个窗口了
                  * _self，其实这个是默认值，就是在当前窗体打开
                  * _parent，链接在父窗体显示
                  * _top，链接在顶层窗体显示
              * 自定义值
                  * shopingcart，要求不能以_开头，出处：https://www.w3.org/TR/html-markup/datatypes.html#common.data.browsing-context-name-def
                  * 这点等讲到iframe等标签时再说
                      - _parent
                      - _top这两个属性也是需要讲到iframe时再提起

      * 在html5中，还有一个download属性
        `
          * 表示点击这个链接将下载链接对应的文件，而不是跳转到目标页面，下载的文件名以download属性的值来命名
              * `<a href="xxx/jianai.pdf" download="简爱.pdf">点我下截《简爱》完整版</a>`
              * 只能触发下载自己网站上的资源，只能在真正的网址上使用，即url以http开头
              * 问题，如果同时有target=“_blank”，又有download属性，它如何行为呢？
                  * 请自行测试
              * 为什么要有这个属性呢？传统浏览器中，要触发下载，需要服务端的支持，给出特定的http头才会触发浏览器下载而不是打开对应的内容
                  * 这个属性的出现可以让点击下载完全由前端来完成
  * p 段落
  * img  图片,,自闭合标签
    * src="" 设置图片地址
    * alt="" 设置图片的替换文字,在图片加载失败时显示
    * width="" 设置图片的宽度
    * height="" 高度
  * h1,h2,h3,h4,h5,h6
    * 一般来讲,一个页面最好只有一个一级标题
  * strong/em/i/u/b/
  * 块级标签
    * 自动占满一整行的空间
    * h123456,p,ul/ol/li
  * 行内标签
    * 能够跟其它普通文字在同一行
    * strong/em/i/u,a,img
  * ul/ol(unordered list,   ordered list, 无序列表,有序列表)
    * li(list item,列表项)
    * ul/ol里必须只能直接放li标签,不能放别的标签
    * li里就可以随意书写标签了
  * dl/dt/dd
  * br,hr 自闭合标签
  * div
  * span

  * 标签的通用属性/全局属性(即可以用在每个标签上的属性)
    * class 标签的分类,每个标签可以有多个分类,用空格隔开
    * id 标签的唯一id,类似于身份证号码,每个标签的id必须唯一,不能与其它标签的id重复
    * title 鼠标悬浮时的工具提示
    * lang 设置这个标签内文字的语言
    * style 设置标签的样式

  * a标签
      * anchor, 锚
      * 语义是一个链接，链接地址写在  href（Hyperlink REFerence）属性里
          * 可以链接到的类型非常多，而且一般来说是可扩展的
              * 绝对网址，fullpath
                  * `<a href="https://jd.com/">京东</a>`
              * 页内特定位置跳转地址
                  * `<a href="#pos1"></a>`
                  * 例：https://html.spec.whatwg.org/multipage/grouping-content.html#the-dl-element
              * 其它页特定位置跳转地址
                  * `<a href="http://jd.com/#footer"></a>`
              * 这个在书目的章节跳转在使用的比较多
              * 相对路径
                  * <a href="https://baidu.com/">baidu</a>
                  * <a href="a.html">baidu</a>

                  * `<a href=".././../a/b/../index.html"></a>`
                  * `<a href="./index.html"></a>`
                  * `<a href="../index.html"></a>`
                    * http://a.com/a/b/c.html
                      * http://a.com/a/b/index.html
                      * http://a.com/a/index.html
                  * `<a href="/index.html"></a>`
                    * http://a.com/a/b/lkj/adsfa/sdf/c.html
                    * http://a.com/index.html
              * 电子邮件
                  * `<a href="mailto:aaa@bbb.com"></a>`
                  * `<a href="mailto:aaa@bbb.com?title=1&subject=2&content=3"></a>`
                    * 需要在电脑安装邮件客户端
              * 电话号码　tel:18611075877
                * 主要用在手机页面上
              * QQ/taobao 临时会话
                * tencent://temp-chat?QQ=285696737
                * thunder://ghjk;adfklasdhfkweuhfasdlfk
              * 等等等等
                  - thunder://LKDJOIE7436239/
              * 空的href属性 href=""  href="."
                  * 链接到当前页面
                      * 所以仅以#开头的值是中转到当前页面的特定位置
                  * <img src="">
                  * 类似的，如果一个img标签的src属性为空，也将对应当前页面地址
                      * https://www.nczonline.net/blog/2009/11/30/empty-image-src-can-destroy-your-site/
      * target属性
          * 可以指定在哪个窗口打开链接
              * 几个特殊值,关键字
                  * _blank，链接在空白的窗口显示，也就相当于新打开一个窗口了
                  * _self，其实这个是默认值，就是在当前窗体打开
                  * _parent，链接在父窗体显示
                  * _top，链接在顶层窗体显示
              * 自定义值
                  * shopingcart，要求不能以_开头，出处：https://www.w3.org/TR/html-markup/datatypes.html#common.data.browsing-context-name-def
                  * 这点等讲到iframe等标签时再说
                      - _parent
                      - _top这两个属性也是需要讲到iframe时再提起

      * 在html5中，还有一个download属性
        `
          * 表示点击这个链接将下载链接对应的文件，而不是跳转到目标页面，下载的文件名以download属性的值来命名
              * `<a href="xxx/jianai.pdf" download="简爱.pdf">点我下截《简爱》完整版</a>`
              * 只能触发下载自己网站上的资源，只能在真正的网址上使用，即url以http开头
              * 问题，如果同时有target=“_blank”，又有download属性，它如何行为呢？
                  * 请自行测试
              * 为什么要有这个属性呢？传统浏览器中，要触发下载，需要服务端的支持，给出特定的http头才会触发浏览器下载而不是打开对应的内容
                  * 这个属性的出现可以让点击下载完全由前端来完成
  * p 段落
  * img  图片,,自闭合标签
    * src="" 设置图片地址
    * alt="" 设置图片的替换文字,在图片加载失败时显示
    * width="" 设置图片的宽度
    * height="" 高度
  * h1,h2,h3,h4,h5,h6
    * 一般来讲,一个页面最好只有一个一级标题
  * strong/em/i/u/b/
  * 块级标签
    * 自动占满一整行的空间
    * h123456,p,ul/ol/li
  * 行内标签
    * 能够跟其它普通文字在同一行
    * strong/em/i/u,a,img
  * ul/ol(unordered list,   ordered list, 无序列表,有序列表)
    * li(list item,列表项)
    * ul/ol里必须只能直接放li标签,不能放别的标签
    * li里就可以随意书写标签了
  * dl/dt/dd
  * br,hr 自闭合标签
  * div
  * span

  * 标签的通用属性/全局属性(即可以用在每个标签上的属性)
    * class 标签的分类,每个标签可以有多个分类,用空格隔开
    * id 标签的唯一id,类似于身份证号码,每个标签的id必须唯一,不能与其它标签的id重复
    * title 鼠标悬浮时的工具提示
    * lang 设置这个标签内文字的语言
    * style 设置标签的样式

  * a标签页内跳转

  * form 表单
    * form元素
      * action属性 表单提交的地址
      * target属性 表单在当前窗口还是在新窗口提交,同a标签的这个属性

      https://www.example.com/mono/register?username=fwef&password=wefwef&realname=werwer

      https://www.example.com/mono/register?username=xr&password=123456&realname=xieran


      https://www.bing.com/search?q=foo&PC=U316&FORM=CHROMN

    * button
    * input
      * type=text,number,email,range,color,file,radio,checkbox
      * reset,submit
    * label
    * fieldset
    * legend
    * textarea
    * select
      * option
      * optgroup
    * progress

  * 表单标签
  - form标签
    - input
      - https://www.google.com.hk/search?q=invalid+inentity+escape+in+regular+expression
      - https://stackoverflow.com/questions/36953775/firefox-error-unable-to-check-input-because-the-pattern-is-not-a-valid-regexp
      - https://www.fxsitecompat.com/en-CA/docs/2016/input-pattern-now-sets-u-flag-for-regular-expressions/
      - https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/Input
    * 属性
      + action
        * 表单提交的地址
      + target
        * 行为类似a标签的target
      + method
        * 表单提交方式
          - get
            + 将表单字段拼成querystring
              * 什么是querystring？
                - http://abc.com/?a=1&b=2&c=3
          - post
            * 这个等学到http再说
      + enctype，编码方式
        * 在讲到http的时候再谈
  - input
    + type属性的各项值
      * text
        - 文本
      * password
        - 密码
      * checkbox
        - 复选框
        - 以name相同分组
        - checked属性表示默认选中
      * radio
        - 单选框
        - 剩余同上
      * file
        - accept
          + 可以接受的文件类型
          + `<input type="file" name="" id="" accept="image/*,text/*">`
          * MIME Type 媒体类型 Multipurpose Internet Mail Extensiion
          + `<input type="file" name="" id="" accept=".jpg,.png,.gif,.jpeg,.webp,.exe" value="c:/user/xieran/desktop/a.pdf">`
          * http://wwww.a.com/favicon.ico
        - 安全问题
        - multiple
          + 是否支持多选文件
        * .txt  text/plain
        * .js   application/javascript
        * .css  text/css
        * .html text/html
        * .png  image/png
        * .jpg  image/jpeg
        * .gif  image/gif
      * hidden
        - 隐藏的输入域
        - value设置其值
        - name设置名字
      * 为以下四个值时，都表现为按钮的样式，按钮上的文字需要用value属性来设置
      * image
        - 从功能上讲是一个表单提交按钮
        - 从形态上看是一个图片
        - 此时需要使用src属性指定图片的地址
        - 现在基本上不这么用，之所以有这个用法，是以前不用js时想做出漂亮的按钮时，需要这么用
        - 在html5中，可以在这种标签上给定width跟height，类似img标签相应的属性，src，alt
      * button
      * submit
        - 单击时会触发表单的提交
      * reset
        - 单击时会重置表单为初始状态
      * **以下为html5新增属性值**
      * number
        - 输入数字
        * e,.,-
        * -3.14e-8
      * email
        - multiple
        - 使用半角逗号分隔每个地址
      * date
      * datetime-local
      * time
      * week
      * month
      * url
        * protocal://user:password@domain:port/a/b/c/d.html?a=b&c=d#sldjfoiwjeofij
        * 百度.中国
      * tel
      * range
        - min，4
        - max，10
        - step，2
      * color
        - value将返回十六进制颜色#abcdef
      * 不能识别的值，当做text来处理

      * input的其它属性
        - value
          + 为按钮形态时设置上面的文字
          + 为输入框时设置里面的默认内容
            * datetime-local
              * https://zh.wikipedia.org/wiki/ISO_8601
          - name
            + 很重要，表单提交时，这个域/字段/框/FormControl的名字
            + 同时，在radio和checkbox阵列里，name相同的元素被分在一组里
          - disabled
            + 无值的属性
            + 禁用这个输入域
          - required
            + 设置这个输入域为必填项
            + 不填的话无法用**正常手段**触发表单提交
          - maxlength
            + 为文本输入框时设置输入的最大长度
          - minlength
            + 同上，但为设置最小长度
            + 不过兼容性不太好，不少浏览器没有实现
              * 有点矛盾，不填的时候是空的，当然会非法
          - placeholder
            + 占位符
            + 提示性文字，一旦输入内容就消失
          - autofocus
            + 自动获得焦点，即页面加载完后光标自动在这个元素内
          - tabindex
            + 按tab键在不同输入域之间跳转时的顺序
            + 会往顺序更大的元素跳
            + 为-1的话会跳过那个元素
  - button
      + type属性
          * 不写type属性的话，默认为submit
              - 即：无type的button的type属性默认为submit
          * `<button type="reset/button/submit">Submit</button>`
          * button
              - 常规按钮，功能上与input[type="button"]一样
          * submit
              - 提交按钮，功能上与input[type="submit"]一样
          * reset
              - 重置按钮，功能上与input[type="reset"]一样
      + 与`<input type="button" name="b" value="lksjdf">`的区别
          * input的button只能在按钮上显示纯文字
          * 而button标签可以在按钮上显示其它内容比如图片（即嵌套其它标签），文字也可以设置不同颜色等
  - label 标签
      + 一般与checkbox及radio一起用，以扩大这两个按钮的可点击区域，提升用户体验。当然，也可以跟其它元素一起用，不过一般没必要（比较典型的是与input:file一起用）
      - for属性
          + 为想要被扩大点击区域的元素的id，不带井号
          - 细节：在ie8及以下不能用于displaynone的表单元素，可能是因为 not focusable
          - 表单元素嵌套在label的时候可以不用for属性
            ```html
            <form action="">
              有for的用法
              <label for="oneid">One</label>

              <input onclick type="text" id="oneid">

              不用for的用法
              <label>
                <input type="checkbox"> 男
              </label>
            </form>
            ```
      - 如下怎么算呢？
        ```html
        <input id="a">
        <label for="a"> lllll
          <input type="text">
        </label>
        ```

      - 典型的坑，两次点击，等学了js后再谈
  - select name="sel"
      + 下拉选择框
      + 属性
          * multiple
              - 无值属性，表示多选，多选时就不是下拉的样式了
      + 另外此标签在不同的系统里面样式差别很大，而且它的样式一般来说是取自系统自带的，所以很难被css控制
          * 所以一些对 ui 要求比较高的网站都选择用其它元素模拟下拉框
              - 例：小米路由器
      + size属性控制默认显示的数量，也即它的尺寸
  * option
      * value
          - 选择了该项目后它所属的select元素的值
      * selected
          - 默认被选中
      * disabled
          - 表示该项被禁用
      * hidden
          - 表示该项被隐藏
      - 以上三个属性均无值
  * optgroup // hgroup  colgroup
      - 给option分组
      - 用label属性表示这个分组的名字
      - 无法被选中，只选择option
      - 有一个disabled属性，如果设置了这个属性，整组标签都会被禁用
      ```html
      <select>
          <option value="1">1</option>
          <optgroup label="这是一个分组" disabled hidden>
              <option value="01">01</option>
              <option value="02">02</option>
              <option value="03">03</option>
              <option value="04">04</option>
              <option value="05">05</option>
          </optgroup>
      </select>
      ```
      - 兼容性不确定，因为我没用过mac。。。。

  - textarea
      + 多行文本输入框
      + 两个特殊属性
          * rows="3" 行
          * cols="20" 列  column
        + 不过现在也不常用，一般都用css来控制了
  - fieldset 字段组 用来把 一组 输入域 放在一起的。
      + field就是字段的意思，就是说一个表单输入域（输入框）
      + 这个标签用来给输入域分组，所以叫set
          * set本来就是组的意思
      + 如果只是分组，完全可以用div等标签
          * 那这个标签有什么用呢？
          * fieldset有个disabled属性，如果它有了这个属性，其内的所有输入域都将被禁用，类似optgroup
              - 在某些场景下是非常好用的
  - legend
      + 只能作为 field set 的子元素，用来标识这组输入域的名字，基本上没有其它用处
          * 而且在有了css之后，这个标签基本也没有用武之地了



  * html实体 html entity （转义符）
    * &nbsp; non-breaking space 160号空格
    * &amp; &符  ampersand
    * &copy; 版权符
    * &lt; 小于号 lettle then
    * &gt; 大于号 greater then
    * &quot; 双引号 quote
    * &apos; 单引号
    * &#x61; 用字符的十六进制
    * &#97; 用字符编号的十进制,所以这一行同上一行
    * 实际上每个符号都可以用转义符表示
  * html对空白字符的忽略
    * pre标签
  * 标签能否任意嵌套？
    * 标签的分类与嵌套原则
    * https://developer.mozilla.org/zh-CN/docs/Web/HTML/Content_categories
    * https://validator.w3.org/
  * 语义标签 html5中新增的
    * section <div class="wrapper container content"></div>
    * article <div class="article"></div>
    * aside   <div class="sidebar"></div>
    * main    <div class="main"></div>
    * header <div class="header"></div>
    * footer <div class="footer"></div>
    * nav    <div class="nav"></div>


  * table表格
      - 这个标签以前经常用于做布局
          + 什么是布局？即页面大区块的排列和摆放
          + 为什么呢？因为table都是方方正正格子，了解后很容易控制
              * 语义很差
              * 可读性很差
              * 可维护性也很差 maintainable
              * 可访问性
          + 但现在有了 css 之后，基本上只用table来显示数据，即表格本来的作用
          + 熟悉 DIV+CSS 布局 JD Job Description
      * caption
          - 表格标题
      * thead
          - 表头
          - 做为table的直接子元素
          - 只能有一个
          - 只有一个的情况下，即使出现在tbody的后面，其内容也会显示在tbody的前面
          - 非要写多个的话，第一个以外的会当做tbody来处理
      * tbody
          - 表格主体
          - 做为table的直接子元素
          - 可以有多个
      * tfoot
          - 表尾
          - 做为table的直接子元素
          - 只能有一个
          - 只有一个的情况即使出现在tbody的前面面，它的行也出现在tbody的后面
          - 非要写多个的话，第一个以外的会当做tbody来处理
      * tr
          - table row cell
          - 表格行
          - 可以直接做为table的子元素，会被放入创建的tbody里面
          - 或者做为上面三个标签(thead/tbody/tfoot)的子元素
      * th
          - table header cell
          - 用在表头单元格
          - 文字默认为加粗
          - id用于被td元素引用以表示td所属的标题是哪一个
              + 看例子
      * td
          - table data，表格数据单元格
          - headers
              + 表格头，值为某th的id，以表示这个数据的名称
                  * 方便读屏软件
              + headers的值可以是多个以空格分隔的th标签的id的值，用法可能是th或td单元格跨行或跨列了
          - 跨行跨列的单元格
              + col span 跨列
              + row span 跨行
              + 错误的示范：
              + http://www.splaybow.com/html-table-rowspan-colspan.shtml
          - http://jsbin.com/nikifi/edit?html,output
          - http://jsbin.com/yehecez/edit?html,output
          - http://jsbin.com/susomoh/1/edit?html,output
      * col/colgroup 标签
          - colgroup
              + 用来分组col标签
              + span属性，表示选择多列表格
              + 有span时，不可再有子的col元素
              + 大部分属性同col元素
          - col
              + 用来设置表格列的属性和样式
              + span属性，表示选择多少列表格列，默认为1
          - 可以单独使用，也可以被colgroup分组
            ```html
            <table>
                <caption>表格标题</caption>
                <col>
                <col>
                <colgroup></colgroup>
                <colgroup></colgroup>
                <colgroup bgcolor=red>
                    <col>
                    <col bgcolor=navy>
                </colgroup>
                <tbody>
                  <tr bgcolor="red">
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                  </tr>
                </tbody>
            </table>
            ```
          - 必须出现在caption后面，thead/tbody前面
          - 很多属性不支持了
              + 而w3schools上面还列着
              - http://www.w3school.com.cn/tiy/t.asp?f=html_col_test
      * 其它
      * border-spacing CSS属性, spacing是重合的
      * cellspacing=0
      * tr或者td tr th不能有其它并列标签,否则会识别错误
          * 有些元素的 position:relative 无效，见下
          * https://stackoverflow.com/questions/6746175/html-tr-tag-and-positionrelative
          * box-shadow 也不支持某些类型的元素
          * https://stackoverflow.com/questions/10874985/box-shadow-on-table-row-not-appearing-on-certain-browsers

  * marquee

  * canvas
  * iframe
    * inline frame
    * name属性
  * script
    * 当浏览器不支持以上标签时的写法
      * fallback 退化方案
  * style
  * sub/sup
  * code,pre
  * video(src= controls)
  * audio(src= controls)
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element

  * 可访问性
    * role 与 aria-*
    * role是用来设置元素当前在扮演什么类型的角色的
    * aria-*="owiejf"是用来表示当前角色的状态的
      * aria  Accessable Rich Internet App 可访问的富互联网应用
  * 语义化
    * 用正确的，合适的标签来标记相应的内容
  * Dev Tools 开发工具初探





  * 浏览器介绍（略）
  * Chrome
  * FireFox

* css
  * html默认几乎没有什么样式
    * 古老的html中可以通过增加一些属性来增加一点有限的样式
      *
        ```
        <body link="aqua"
              a(ctive)link="red"
              v(isited)link="grey"
              background="bg.jpg"
              bgcolor="yellow"
              leftmargin="10%"
              bottommargin="100"
              text="green">
        ```
  * 但这种做法能控制的样式非常少
    * 而且如果想把某个样式给到多个元素，要重复写
  * 不能使用各种长度单位
  * 总之从各种角度来说都比较原始
  * 而css能解决上面的所有问题(CSS To The Rescue)
    * 虽然解决了上面的问题,但是它也带来了新的问题
      * 由于样式控制更细，必然也更难，所以不太好学
      * 不好维护，所以有各种方案的尝试(BEM,Tailwind,scoped)
        * 什么叫好不好维护/可维护性？
          * 也就是易修改性
      * 所以说，**没有银弹(No Silver Bullet)**

* CSS 全称 Cascade Style Sheet，层叠样式表
  * 更多类型的样式
  * 更复杂且灵活的布局
  * Desgined for UI(User Interface)，专为UI开发设计
  * 层叠，继承
  * 为未来设计（未来的浏览器都支持）
* CSS初探
  * 想要让页面中所有的段落（p）设置为红色并且字号为24像素
    ```css
      p {
        color: red;
        font-size: 24px;
      }
    ```
  * 上面的代码可以细拆为:
  * 选择器，规则块，单条规则，属性名，属性值

  * 元素（即html标签）的层级关系
    * 父子
    * 兄弟
    * 后代与祖先
  * 替换元素与非替换元素 replaced element vs non-replaced element
    * img, input, video, audio, iframe, canvas替换元素,元素本身只是占位的
      * 实际内容是换成了其它的东西
      * 展示时,替换元素的内部不再有其它元素了
    * p, div, span, strong 等普通元素,里面只有文字,即为非替换元素
      * 非替换元素的展示无需下载资源,所有的要素都在标签之间
  * 元素的显示角色(原话叫角色,可能翻译为"显示方式"会更合适)(不是role与aria-*里的这个role)
    * 块级元素
    * 行内元素
    * 可以通过display属性改变元素的显示方式(布局方式)
      * 实际上元素的显示方式远不止上面这两个了
  * 如果让css在html元素上生效
    * style标签
      * `<style>p {color:red;}</style>`
    * link标签
      * `<link rel="stylesheet" href="print.css">`
    * 内联样式
      * `<div style="color:red;font-size:45px;"></div>`
  * css代码的注释
    * /* ... */, 快捷键Ctrl + /, 但这种注释在内联样式中不太好写
    * css虽然只支持这一种注释风格，但是利用css的解析规则，我们可以有很多方式注释它
      * 如果这一行解析不成功，浏览器会直接忽略它
      * 所以以任意破坏这一行的内容开头就可以了
        * `//color:red;`
        * `colors: red;`
  * 选择器
    * 基本规则
      * span,a ｛
        声明/属性:值;
        color: red;
        font-size: 24px;
        margin: red;
      ｝声明块
      * selector {
        prop:value;
        prop1:value1;}
      * 对应书本图片：p24页
  * 声明与关键词
    * 声明中的属性必须是css所支持的属性，否则将会被浏览器忽略
    ```css
      div {
        center: yes;
        center: yes;
        颜色: 高级黑;
        color: 100;
        colour: red;
        font-size: red;
        font-size: red;
        font-is-large: true;
      }
    ```
    * 声明的值也必须是**对应属性所支持的**，否则整条声明同样是无效的
    * DevTools 中可以看到以下提示
        * unknown property
        * invalid value
  * 各种选择器
    * 标签/元素选择器 element selector
      * `element {rules}`
      * div {}  p {} span {}  abc {}
      * * {color: red;}
      * <div></div>
      * <abc></abc>
    * 类选择器与id选择器
      * <div class="foo error def ghi"></div>
      * <p class="foo error "></p>
      * 类选择器
        * div.foo
        * .foo
        * .foo.error.ghi
        * .foo
        * *::selection
        * *:target
        * 简写为   .classname
        * 复合 类选择器
          * p.class1.class2
            * <p class="class1 class2 lsdkfj lksdfj"></p>
          * p.a.a {color: red;}
          * p.a {color: blue;}
          * ie7之前不支持这种
            * 只会有最后一个类生效
              * p.a.b 相当于 p.b ; p35页
        * id选择器
          * <p id="thep"> </p>
          * #thep {color: red;}
          * #th#ep
          * [id="th ep"]
          * 不存在复合id选择器。。。因为一个元素只能有一个id
          * 而且id选择器是不按空格分隔的
          * p.a.b.c#foo
          * #thevalueofid {a:b;}
          * p,P {color:red;}
          * span {color:yellow}
        * 用id还是用class选择器
          * id是一次性的，只出现一次
          * class是多处可用，可以复用的
          * 另外id选择器是不支持空格分隔的id列表的，不像class，p36页
          * id选择器优先级更高
          * 大小写敏感的，.p,.P是不一样的。但有些老浏览器不敏感
          * #p,#P
          * .error {color:red;}
    * 属性选择器
        * 7种属性选择器
        * 存在某属性
          * [attr] {}
        * 存在多个属性，chaining
          * p[attr1][attr2]
          * [attr1][attr2]
        * 属性名与值同时匹配
          * p[attr="abc"]
          * p[class="abc def"] vs p.abc 不一样 p41页
          * .class2 .class2 {
          * }
        * 空格分隔的属性值列表
          * [attr~="abc"]
          * .abc == [class~="abc"]
          * 这个有什么作用呢？它可以用在任何属性上面而不是只在class属性上面
        * 属性值不区分大小写
          * <a href=".PDF"></a>
          * [attr~="abc" i], case insenstive
          * .a.b {}
          * [class~="a"][class~="b"] {}
        * 值以指定内容开头
          * [attr^="abc"] caret
          * 应用：为所有email链接加上特定的样式
          * a[href^="mailto:"]
          * a[href^="tel:"]
          * a[href$=".doc"i]
        * 值以指定内容结束
          * [attr$='abc']
          * 应用：为所有不同类型的下载链接加上不同的样式，如pdf文件加上其对应的图标
        * 值的任何位置包含指定内容
          * [href*='.google.'] {color: red;}
          * <a href="http://www.baidu.com/l.google.akdf/adsfal"></a>
          * 应用：选择某个域名的链接；不过强度不够，因为无法保证链接的其它部分不出现host中的内容。
        * 属性值前缀选择器
          * [lang|='zh']
          * 选择attr值 为abc 或者 以“abc-”开头 的元素
          * [lang|="zh"]
          * 应用：选择语言：<html lang="en"><html lang="en-US">
          * p43页
        * 让属性值不区分大小写,在方括号结束前加一个i [role="foo" i]
      ```
        /* 选中有href属性的所有元素 */
        [role] {
          border: 8px solid red;
        }

        /* 选中role属性为banner的所有元素 */
        [role="banner" i] {
          background-color: tan;
        }

        [lang="en-us" i] {

        }

        /* 选中role属性的值以ba开头的元素 */
        [role^="ba"] {

        }
        /* 选中role属性的值以ba开头的元素 */
        [role$="ba"] {

        }

        /* 选中role属性中间出现过ba的元素 */
        [role*="cat"] {

        }

        /* 选中role属性中有cat这个单词的元素 */
        [role~="cat"] {

        }

        /* 选中role属性是cat或以cat-开头,其实是用来做语言选择器的 */
        [role|="en"] {

        }
      ```
    * 选择器的作业
        * 给定一个文档，用不同的选择器实现不同的位置的文字样子不一样。。。
        
  * 选择器组合
    * 同时满多个条件的元素才被选中
    * div#foo.bar.baz[title^="baa"]
    * 注意连接时中间是没有空格的
  * 与文档结构有关的选择器组合
    * 以下示例中A或B可以代表一个组合选择器即可能是p也可能是.foo也可能是p.foo#bar[attr]
    * 后代选择器
      * A B {}
        * 满足条件A的元素里面满足条件B的元素
    * 子元素选择器
      * A > B {}
        * 满足条件A的元素的子元素中满足条件B的元素
    * 毗邻选择器
      * A + B {}
        * 满足条件A的元素内后面满足条件B的元素
    * 兄弟选择器
      * A ~ B {}
        * 满足条件A的元素后续兄弟中满足条件B的元素
    * A, B {xxx} 选中A选择器与B选择器选中的元素的并集
      * 等价于
      * A {xxx} B {XXX}

  * 伪类选择器(通过隐含的信息来选中元素)
    * 交互伪类
      * :hover 鼠标悬浮的元素
      * :active 鼠标按下去(还没松手)的元素
      * :focus 焦点所在元素
    * 链接伪类
      * :link 所的未访问过的链接(注意a标签不一定是链接,只有有href属性的a标签才是链接)
      * :visited 所的已访问过的链接
    * 隐含条件伪类
      * :first-child 匹配任何元素的第一个子元素
      * :last-child 匹配任何元素的最后一个子元素
      * :nth-child(odd/even/3n+5)
      * :nth-last-child(odd/even/3n+5)
      * :empty 选中内容为空的元素,元素之间连空格都不能有,只能有一对空标签
      * :not(条件) 选中不满"条件"的元素
    * 表单交互伪类
      * input:not(:checked)  input:checked
      * :checked 选中被checked的元素 <input  type="checkbox">
      * :enabled 选中被启用的表单元素
      * :disabled 选中被禁用的表单元素
        * :not(:disabled) 选中被禁用的表单元素以外的所有元素
      * :valid/:invalid 选中填写正确/不正确的表单元素
      * :required/:optional 选中必须填写的/可选填写的表单元素
  * 选择器的优先级
    ```
    选择器的优先级是一个由四个数字组成的四元组(也有地方说是三元组)(即四个信息放在一块组成的一个整体)

    这个四元组是可以比较大小的
    如何比较?
    从两个四元组的第一个元素开始比较,如相同就比较下一对,如果不同就出结果了
    (1,2,3,1)
    (1,5,9,9)

    如何通过一个选择器得到表示其优先级的四元组?

    ```
    * 当两个不同的选择器选中同一个元素时,但设置的样式不一样,哪个生效呢?
    * 取决于选择器的优先级
    * 优先级的定义，四个数(四元组,也有说三元组的)
      * (0，4，4，29)
    * 不同类型的选择器会在这个四元组的不同位置上加一
    * 选择器的连接符不记如优先级的计算
      * A B {} 与 A > B {} 优先级一样
    * *{}选择器的优先级为(0,0,0,0)
    * 继承来的样式没有优先级
      * 没有优先级与(0,0,0,0)是不一样的,它比(0,0,0,0)还要低
    * !important
      * 有!important的永远比没有!important的优先级高
        * 都有!important的就比较选择器的优先级

  * 层叠样式
    * 用户自定义important样式
    * 网站作者important样式 authored style
    * 网站作者作者普通样式
    * 用户自定义普通样式 Custom.css
    * 默认样式，浏览器内置样式，User Agent Style
    * 优先级一样的话，按出现的顺序排列，后出现的优先级更高
      * 所以是 link visited focus hover active
      * :link:hover /0 0 2 0/
      * 不过在这几个伪类上分别写完全不同的属性时，顺序就不重要了
      * 重要的是写相同的属性，这时就要考虑优先级的问题了
      * LV HA  VL HA 没有太大区别，因为很明显，V和L不会同时匹配
    * 不来自CSS的样式
      * 如font标签的html属性带来的样式 <font size color face></font>
        * 可以想象它的优先级为0000并且出现在作者样式的开头(所以比继承来的要高)
        * 会被作者样式和读者样式覆盖，但不会被默认样式覆盖
        * p75页
      * <font color="red">aa</font>
      * <style>* {color: green;}</style>



* css里用到的值与单位
    * 数字(次/个数，顺序，系数/倍数)
        - line-height: 2.2;   /* 220% */
        - animation-iteration-count: 2;
        - zoom: 2.588888888;
        - zoom: .588888888;
        - column-count: 2;
        - z-index: 5;
        - order: 8;
    * 百分比
        - width/height: 60%;
        - top/left/right/bottom: 50%;
        - margin-top: 25%;
        - font-size: 200%;
        - line-height: 150%;
        - vertical-align: 40%;
        - color: rgb(40%, 50%, 70%)
        - color: rgb(255 * 40%, 127, 255 * 70%)
    * 百分比与纯数字不可互换
    * 颜色(R G B)
        * color: red;
        * red/blue/green/tan/brown/teal/grey/maroon/silver/yellow/aqua/lime/
        * lightgreen/lightpink/lightblue/darkblue
            * 事实上大部分时候都用不到这些颜色，写demo的时候可以用来炫技
        * hex color
          * #RRGGBB
          * #RRGGBBAA
        #03558f   #0358f
        * #HHHHHH #(0-255)(0-255)(0-255) -> 16700000
        * #abc -> #aabbcc
        * #f30 -> #ff3300
        * #abcd - #aabbccdd
        * hexa #ff00ff80
        * #456 -> #445566
        * #XYZ -> #XXYYZZ
        * #XYZA -> #XXYYZZAA
        * rgb(120,60,200)       sin(3.14) log(2,32) = 5
        * rgb(0-255, 10, 0-255)
        * rgb(0-255, 10, 0-255, 0.5)
        * rgb(r%,g%,0-100%, 0.6)
        * rgb(r%,g%,0-100%, 60%)
        * rgba(r,g,b,0 -> 1)
        * 色彩空间(色彩的数学模型)   色域(屏幕能显示的颜色范围)
        * CMYK (Cyan magenta Yellow black)
        * 色域 屏幕能够显示的色彩范围
        * hsl（色相hue，饱和度saturate，明度light）
        * hsla（色相，饱和度，明度，0-1）
        * hexa rgba
        * web safe 颜色，216种
        - 是在早期大家的电脑都只支持256种颜色时，选出的大部分浏览器与操作系统都支持的216种颜色
            * 6的3次方，即r，g，b分别有6阶可选
        - https://websafecolors.info/learn
        - gif 图片也只有 256
        * p83
    * 长度
        * 绝对长度单位/物理长度单位
            * in(ch) 英寸
            * cm 厘米 centimeters
            * mm 毫米 millimeters
            * -moz-mm
            * pt point 72分之一inch
            * pc pica 6分之一inch
            * 存在的问题
                * 大部分时候不准，取绝于你的分辨率以及系统设置
                    - 于是用的也很少
                * 但在打印的时候可以比较准
            * Surface Studio
        * 相对长度单位
            * px，CSS像素
                * 很多人以为这是个绝对长度单位，其实并不是。但在设计中，大多数时候被认为是绝对长度（p89页）
                * 指定图片的大小一般肯定是用这个，要不然图片会被变形拉伸，因为图片的尺寸大多数时候是以px来丈量的
                * 另一个坑，在ie7之前的浏览器，放大时以px指定的文字不会放大，不过已经不在考虑范围了
            * em
                * 【当前元素】font-size的大小
                  * 用在font-size上取父元素的字号
                  * 用在其它属性上取自己的字号
                  ```css
                  <div class="foo">
                    <p></p>
                  </div>
                  div>div>div>div>div

                  .foo {
                      font-size: 30px;
                  }
                  p {
                    width: 10em;//
                    font-size: 1.5em;//45px
                    xfont-size: 150%;
                  }
                  ```
            * rem
                - root element's em
                - 灵活的布局
                - html 元素（根元素）的字号
                - html {font-size: 2em;}
                - p {width: 20rem;       }
            * ex
                * x字符的高度
                * 几乎没啥用处
                * 有些浏览器会把它计算成 0.5em
            * ch，0字符的宽度
                * l w
            * vw/vh
                - viewport width
                - 1vw 视口宽度的100之一
                - viewport height
                - 1vh 视口高度的100之一
                * 包含滚动条
            * vmax/vmin
                - vmax = max(1vw, 1vh)视口宽或者高较大的那一个的100之一
                - vmin = min(1vw, 1vh)视口宽或者高较小的那一个的100之一
            * 百分比
              * 关键在于基于哪个尺寸
            * 计算值
              * 注意运算符两边一定要打空格
              * 它可以混合单位运算(就是拿那个单位单独放在这个属性上时的尺寸去参与运算)
              * width: calc(2 * 30em - 40%);
              * width: calc(10px * 10 - 5%)
              * width: calc(10px * 10px / 10px)
              * width: calc(500px - 2em)
            * line-height: calc(2 * 3)
            * 1km - 10mm
    * 角度
        - degree 角度 45° 90deg
        sin(pi/4)
        - radian 弧度：3.14rad = 180deg     90deg => pi/2
        - turn -》   1turn = 360deg = 6.28rad
        * 30deg
        * transform: rotate(180deg);
        * transform: rotate(3.141592653589793238462643383279rad);
    * 时间
        * 1s
        * 1.2s
        * 0.2s
        * .2s
        * .3s
        * 1ms
        * 1s = 1000ms
    * hz 频率单位
        * 5hz
    * URL
        * import url("aaa.css");
        * background-image: url(a.png);
        * url(path)
        * url(protocol://server/pathname)
        * url(protocol://a:b@server/pathname?a=b&c=d)
        * url(/../../abc.jpg)
        * 相对路径相对于【这句代码】所在的文件所在的文件夹
        * 相对路径，绝对路径等，一个话题
    * css关键字
        * width: 300px;
        * display: block;
        * display: none block inline inline-block table table-cell ;
        * background-color: currentColor;
        * font-size: inherit;
        * border-style: solid/dotted/dashed/ridge;
        * none，注意跟0不一样
        * inherit/reset/initial/unset
        * 如果一个属性接受关键字，这些关键字则专门指定为该属性的关键字
        * 如果两个属性接受同一个关键字，这两个关键字的行为很多时候是不一样的
            * 比如说，normal，在给letter-spacing与font-style时意义完全不同
                * letter-spacing: normal
                * font-style: normal
    * 字符串
        * content: 'ffoo\6211oo'  "wosdf  iejf -=owiejf"   "jowiejfo";
    * 取属性的值
        * content: attr(href);
        * transform: rotate(30deg) skew(50deg) matrix(1,2,3,4,5,6);



* 第五章 字体
    * 字体族
        * serif 衬线字体
        * sans-serif 非衬线字体
            * 什么是衬线？
        * monospace 等宽字体
    * 字体
      * 使用通用字体族
          * body {font-family: sans-serif;}
          * 以上代码中，浏览器将自动选择一款没有衬线的字体
      * 使用指定的字体
          * h1 {font-family: "MicroSoft YaHei";}
              * 如果用户的电脑上安装了这款字体，那么该页面上的h1将会用这个字体
          * 但是，有时候用户的浏览器并不一定安装了这个字体
              * 这时可以指定降级（fallback）方案:
              * h1 {font-family: "Helvetica", "微软雅黑", sans-serif;}
          * 一般来说，最好提供一个字体族名称做为最后的退化方案
      * 字体名称里面有特殊字符时
          * 使用引号（quotation marks）引起来
              * 单双均可，需要配对
                  * 但注意在html标签的style标签里面的时候要跟外层的引号匹配，还是配对问题
          * 另外，字体族必须不能加引号，它们算是关键字而不是字体值（字符串）
              * 加了引号就成指定的字体名称而不是字体族了
    * 字重
        * 一般来说，一些系列字体都会预定义一些不同字重的字体
            * 如Zurich字体
              * Zurich Extra Black
              * Zurich Black
              * Zurich Bold
              * Zurich
              * Zurich Light
            * 于是可以这么用
                * p {font-family: 'Zurich Black'}
                * div {font-family: 'Zurich Light'}
                * strong {font-family: 'Zurich Bold'}
            * 但是
                1. 上面的写法很繁琐
                2. 很多字体**不一定**预定义了这么多种不同的内置字重，或者用户不一定安装了所有这些字体
                    * 这意味着可能会使用退化字体
                    * 也有可能你写的名字不一定存在
                3. 很多可能就只有一种
                    * 这种情况下浏览器可能会自行计算出比如粗体的样子
          * 解决方案是只指定主字体名称，然后指定font-weight，由浏览器来选择具体字重的字体文件，或者计算出来
          * font-weight
            * normal 普通
            * bold 粗体
            * bolder 更粗 `<h1> bar <span>foo</span></h1>`
            * lighter 更细
            * 100 - 900
            * inherit
            * Bolder
                * 让字体变的更粗
            * Lighter
                * 让字体变的更细
    * 字号 font-size
        * （所谓的）绝对大小关键字
            * xx-small  = 12
            * x-small  ==  14
            * small  =  15
            * font-size: medium;  = 18
            * large
            * x-large
            * xx-large
        * 根据规范，一个绝对大小与相邻的绝对大小的缩放因子是1.5以及0.66
            * 比如说如果medium是10px
            * 那large就是15px
            * small就是6.66px
            * 但
              * 不同浏览器设置的缩放因子可能并不一样
                * 而且，这个值是开发者没办法更改的
              * medium的大小也是不确定的
              * 所以这几个关键字基本上没什么用武之地
        * 百分比单位
            - 相对于父元素的大小，也即继承过来的值
            - 跟em的效果几乎是一样的
                + 120%跟1.2em几乎一样
            - 使用这种单位可能会产生意想不到的效果
              ```html
              <style>
                  span {
                    font-size: 150%;
                  }
                  em {
                    font-size: 1.5em;
                  }
              </style>
              <span>
              a(24) <em>abc(19.2)</em>
                <span>b(36)
                    <span>c(54)
                        <span>d()
                            <span>a span</span>
                        </span>
                    </span>
                </span>
              </span>
              ```
            - 字会越来越小。。。
        * font-size的继承
            - 总是继承的是**计算后**的值，而不是**书写时**的值
            * div>p>span
            * div {font-size: 10px;}
            * p {font-size: 120%;}
            * span {font-size: 120%;} -> 14.4px
        * 长度单位
            * 绝对单位如cm，pt等可能不是你想要的
                * 不同的系统可能显示效果不一致
            * 所以大多数页面中选择px等单位
                * 能够“最大程度的”保证设计的高度还原
                * 但存在的一些问题是，老版本的浏览器在放大页面或字体的时候，无法放大以px指定大小的字体
                * 现代浏览器无此问题
    * font-style与font-variants
        * font-family: "Consolas";
        * font-style
            * normal
                * 文字**是正**的，即垂直的
            * italic
            * oblique
            * 上面两个都是斜体，但是有啥区别呢？
                * italic是另一个专门设计好的斜体字体
                    * 比如正常字体是 Roboto
                    * 则italic字体可能会是 Roboto Italic，Roboto Cursive
                * 而oblique则是在正体的文字基础上变幻出来的一个斜体字
                    * 而oblique则一般会map到Roboto Slanted，Roboto Incline， Roboto Oblique
            * 此处细节较多，建议看书本p115页
        * font-variant
            * normal，默认
            * small-caps
                + 把小写字母显示成小号的大写字母
                + 有些字体专门为小写字母设计了这种样式，而不是单纯的把大写字母显示的小一点。
                    * 当字体没有提供这种样式的时候，浏览器当然就是把大写字母缩小了
            * 与 text-transform: uppercase
                * 这个规则是把所有的文字显示成大写
                * the quick-brown fox
                * capitalize -> The Quick-Brown Fox
                子属性
        - 字体属性的简写
        - font: ;
        - font-style:;
        - font-weight:;
        - border SHORT HAND
        - border-style/width/color;
        - border-left/right/top/botoom
        - border-left/right/top/bottom-style/widht/color;
        - margin   margin-left/right/top/bottom;
        - transition transition-duration/timing-funciton/property....
        - border-radius
        * font 属性 short hand
            - font: bold normal  30px 宋体, 'yahei', serif;

            font: [<font-style> || <font-variant> || <font-weight>] <font-size>[ / <line-height>] <font-family>;

            font-style: italic | oblique;

            - font: small-caps bold 20px / 1.2em     宋体, serif;
            - 前三个的顺序不重要
                + border:red  solid 1px;
            - 如果前三个的随便哪一个值为normal，则可以省略
            - line-height可以省略，但如果出现，必须加/并且出现在fz的后面
            - fz跟ff必须出现，而且顺序也是这个顺序，不能乱
            - font: 25px/1.2 "宋体" ;
            - font: 25px "宋体";
            - font: 120%/1.2 "宋体";
            - font: small-caps 120% / 1.2 "宋体";
            - p121页


* 第六章 文字与排版
    - 文字缩进 text-indent
        + 以前是怎么做的呢，放张白色的图片在段落前面。。。
            * 也有说有一个非标准的spacer标签，p128页
        + text-indent: 2em
        + text-indent: 5%；百分比相对于元素自身的宽度
            * 一般很少用百分比
        + 应用
            * 用text-indent: -99999px来把标签里的文字隐藏，然后用背景图片“替换”标签内容
            * -2em这种可以实现首行悬挂
            * 2em则可以实现首行缩进
        + 本属性只适用于块级元素，不适用于行内元素
    - 文字水平对齐 text-align，text-align-last
        + left
        + right
        + center
        + justify
            * 两端对齐
            * 不同行文字之间的空白可能就不一样了
            * 在有长单词的行中显得比较明显
                - css 并不支持在打断长单词时自动加上连字符-
                    + 据说原因是因为不同的语言的连字符不一样
                        * p133页
            * 脑洞：单行文字两端对齐
        + 与center元素作用不一样，center会把整个元素都居中，而text-align只居中文字
            * http://jsbin.com/senefeg/1/edit?html,css,output
    - 文字在垂直方向的对齐 vertical-align
        + line-height
            * content-area
            * inline-box
            * p135页，图
            * 取值
                - 长度
                - 百分比
                - 以及inherit
                    + 取非纯数值时，继承的是计算结果
                        * 即取inherit时，也是得到的计算后的结果
                - 纯数值
                    + 取纯数值时，继承的是书写数值
                    + p137页
            * 应用：单行文字垂直居中
                - 坑点，无法让lh总是等于元素的高度
                - 其它
                    + 多行文字垂直居中
                        * http://www.zhangxinxu.com/wordpress/2009/08/%E5%A4%A7%E5%B0%8F%E4%B8%8D%E5%9B%BA%E5%AE%9A%E7%9A%84%E5%9B%BE%E7%89%87%E3%80%81%E5%A4%9A%E8%A1%8C%E6%96%87%E5%AD%97%E7%9A%84%E6%B0%B4%E5%B9%B3%E5%9E%82%E7%9B%B4%E5%B1%85%E4%B8%AD/
                    + flex等实现方式
        + vertical-align
            * 这个属性适用于【内行块元素,行内替换元素】
                - img
                - input
                - 替换元素等
                - 而不是给块级元素用的
            * 取值
                - 关键字
                    + baseline
                        * 默认值
                        * 让元素的基线与其父元素行框的基线对齐
                        * 如果一个元素没有基线，如img，input，则让其底部与外面的文字对齐。即使行框没有文字也是一样。是p138-139页
                            - 应用：图片跟文字底部对不齐
                    + sub
                        * 元素的baseline（或底部）会比父该行文字的basline低
                        * 但低多少，标准并没有说。。。
                    + super
                        * 同上，元素的baseline比该行内容的baseline要高
                        * 标准同样没有规定高多少。。
                    + bottom
                        * 目标元素的底部跟这一行的底部对齐
                    + top
                        * 目标元素的顶部跟这一行的顶部对齐
                    + text-top
                    + text-bottom
                        * 元素的顶/底部与文字的顶/底部对齐
                    + middle
                        * 并不是垂直居中
                        * 而是把【元素的中间】与baseline上面0.5ex（即四分之一em）对齐。。。
                    + 百分比
                        * 相对于自己的 line-height
                        * 把其 baseline 向上或向下移动计算出来的值
                    + 固定长度值
                        * 按指定的数值上移或下移元素
                        * 上下移动元素并不会让其与其它行的内容重叠，而是会增加行框的高度
                - 在作用于表格元素时
                    + 只有 baseline，top，middle，bottom 有效，其它无效
                        * 将在表格布局一章说到
        + word-spacing
            * 控制单词间的间隔
                - 注意中文文字之间不是word space，而是letter space
                    + p144页
            * 其值是添加到本身空格间的值，而不是设置了多少，单词间就间隔多少
            * 取值
                - normal
                    + 相当于写成0
                - 长度单位
                    + 写成多少，单词间的间隔就是空格的宽度加这个值
                    + 可以为负值
        + letter-spacing
            * 改变字母间的间隔
                - 对于汉语，则是改变文字之间的间隔
            * 取值
                - normal
                    + 相当于设置为0
                - 长度值
                    + 增加或减少字母间的距离
        + word-spacing，letter-spacing 与 text-align：justify
            * letter-spacing:normal与text-align:justify一起用时，字母间的距离可能会被改变
            * 但如果给了letter-spacing一个指定的值的话，则justify就不会影响它了
            * http://jsbin.com/pasekej/1/edit?html,css,output

        + text-transform
            * uppercase
                - 所有字母变成大写
            * lowercase
                - 所有字母变成小写
            * capitalize
                - 每个单词的首字母大写
                    + 值得注意的是
                    + heading-one可能被转换成下面两种
                        * Heading-One
                        * Heading-one
            * 本属性的效果先于font-variant执行
            * none
                - 默认，as authored
            * inherit
            * 应用
                * 有些网站的优惠券是全大写的，或者Windows的激活码什么的
                * 输入的时候有些用户可能会觉得是要输入大写还是小写
                * 这时就可以使用text-transform来实现不按shift就输入大写
                * 来源：在本来生活网上买东西时用优惠券时想到的

        * div#foo{
            font-size: 40px;
            font: 24px/1.2 sanif;
        }
        + text-decoration:  overline underline;
            * underline
                - 下划线
            * overline
                - 上划线
            * line-through
                - 删除线
            * blink
                - 不支持了
            * 值得注意的是子元素没有办法去掉由父元素留下的各种线
            * 另外线的位置，粗细，样式都不能指定
                - 有其它解决方案，用背景图片
                - http://jsbin.com/yacobev/1/edit?html,css,output
            * https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-decoration
            *   text-decoration:   ;;
            *   text-decoration-line: line-through;
                text-decoration-thickness: initial;
                text-decoration-style: dashed/dotted/solid/wavy;
                text-decoration-color: red;
        + text-shadow
            * 文字阴影
            * 取值：
                *   水平偏移 垂直偏移 模糊半径 颜色, 下一组;
                * 颜色可以出现在最前或者最后，也可以省略，默认跟文字同色
                * 模糊半径可以不写，则为0
                * 可以用逗号写多组阴影
                https://flow.org
        + box-shadow
            * 与上类似
            * 取值
                - 水平偏移 垂直偏移 模糊半径 扩散半径 颜色 是否内阴影(inset),下一组;
                - 两个半径都可以不写，默认都为0
                - 颜色同上

        + white-space
            * 指定如何处理空格与换行，以及自动换行
            * p155表格
            * https://developer.mozilla.org/zh-CN/docs/Web/CSS/white-space
        + word-break
            * 指定单词如何折行
            * https://developer.mozilla.org/zh-CN/docs/Web/CSS/word-break
        + overflow-wrap
            * 以前叫 word-wrap，是早期ie浏览器引入的一个属性
                - 题外话：ie在文字排印方面的css支持很好，可惜很多浏览器一直不跟进
            * https://developer.mozilla.org/zh-CN/docs/Web/CSS/word-wrap
            * http://www.cnblogs.com/2050/archive/2012/08/10/2632256.html
        + direction
            * ltr
                - left to right
            * rtl
                - right to left
        + unicode-bidi: bi directional;
            * ZWJ Zero Width Joiner
            * 感叹号X喵唔~:xxxx
            * username撤回了消息
            * username = 并亲了你一口?xx
            * xx撤回了消息并亲了你一口
            * https://www.zhihu.com/question/43621727


* 盒模型，box model
    - 盒模型是什么
    - margin外边距
        + 可以为负值
        + 垂直margin会合并
        + 垂直margin在有些情况下会超出到父元素之外
        + 值的复制
            * margin: a; -> a a a a
            * margin: a b; -> a b a b
            * margin: a b c; -> a b c b
            * margin: a b c d; -> a b c d
            * padding同理
        + margin-left/right/top/bottom
    - border
        + border-width: 3px 5px 2px ;
            * 边框宽度
        + border-color: red green;
            * 默认为color的值
        + border-style: solid dotted dashed double;
            * solid
            * dotted
            * 其它
        + 所有边框可以写在一个属性里面
            * border: style color width;顺序任意
            * border: none
        + 也可以单独设置某一边的边框
            * border-left/top/bottom/right: style color width;
        + 甚至可以完全分开设置任意一边的任意一个属性
            * border-left-width/color/style
        + 画三角形
            * http://jsbin.com/nasolud/1/edit?css,output
    - padding
        + 内边距，不能为负值
        + 背景颜色会显示在padding上面
    - content
        + 内容区域
    - width
        + block类型的元素会占满父元素的水平内容区域
        + 更严格的说，是 margin-left,border-left-width,padding-left,width,padding-right,border-right-width,marign-right 加起来正好等于父元素内容水平宽度
            * http://jsbin.com/pakege/1/edit?html,css,output
    - box-sizing
        + 宽度的计算方式
            * border-box
            * content-box
            * 没有margin/padding-box
            * 但另一个属性支持这两个选项
        + doctype
            * 在ie低版本下，如果不声明doctype的话，默认为border-box模型
    - display
        + none
        + inline
        + block
        + inline-block
            * img
            * 从外面看是inline的，从里面看是block的
        + table类/list类
    - height
        + 非定位元素写百分比是无效的
            * 原因：它的高度会影响父元素，而父元素被它撑高后又会反过来影响它，逻辑上就不成立
        + 定位元素写百分比是相对于其定位祖先，而非直接父元素
            * 应用：做出类似选择父元素的功能
                - http://jsbin.com/rofugib/1/edit?html,css,output
    - 定位
        + position
            * static
                - 在哪就在哪，默认值
            * relative
                - 相对于自己本身的位置做偏移
            * absolute
                - 相对于离自己最近的一个定位了的（position属性不会static）祖先元素做定位
            * fixed
                - 相对于浏览器窗口进行定位
                - 应用：回到顶部
                - 应用：固定搜索栏
            * sticky
                - obslated
        + top，left，right，bottom
            * 定位了但是没指定这几个值的任意一个，元素会在原来的位置，与之后的内容重合
            * 定位原点是padding box
            * 比百分比时，以父元素宽度为基准值
        + 各种应用：
    - 案例：级联菜单
        + http://jsbin.com/hedozaq/1/edit?html,css,output
    - 案例：slider
        + http://jsbin.com/tijiqi/1/edit?html,css
        + http://jsbin.com/tijiqi/2/edit?html,css
        + http://jsbin.com/tijiqi/3/edit?html,css


* 第七章 基本视觉格式化(布局) basic visual formatting
  * 什么是格式化(formatting)
    * 其实就是布局，是元素怎么摆放，有多宽，有多高
  * 基本框，即每个元素产生的矩形区域
    * 块元素是一个
    * 行内元素可能是多个
  * 包含块 containing block
    * 每个元素的最近的块级祖先就是这个元素的包含块
      * 更明确的说：是该块级祖先的content-box
  * 常规流 Normal Flow
    * 也叫正常流
      * 指文档内容从上到下从左到右的排布方式，一个跟着一个
    * 翻译为"文档流"是错误的(至少是容易让人混淆的)
      * 因为js中也个概念叫文档流(document flow)，但跟这个完全不一样
  * 替换元素，非替换元素，块级元素，行内元素，根元素的概念
  * **块元素的布局**
    * 水平方向
      * 水平方向的七个宽度之和等于包含块的宽度
      * 但是里面有三个可以为auto，很多灵活的应用都是基于这个
        * margin-left,margin-right,width
      * 并且margin不仅可以为auto还可以为负（其它的五个不行）
        * 好在负值至少是明确指定的值，比auto的要简单
        * 为0是对齐包含块的左边缘，为正是向中心方向偏，为负则是向反方向
      * 各种auto的情况
        * 一个auto
          * 值被计算出来
        * 两个auto
          * 如果有一个在宽度（width）上，则另一个相当于0
          * 如果有都在margin上，则平分，结果就是元素会在包含块中居中
        * 三个auto
          * 相当于两个margin为0
        * 零个auto
          * 当所有的值加起来不等于包含块的宽度时，元素就过分受限了
            * margin-right被重置为auto
        * 以上所有的auto计算中，margin-left不会自动计算为负值
          * 如果被计算为负值，则会用0替代
          * 除非自己指定为负值
          * 而在文字书写方向从右向左时，margin-right不会计算为负值
        * 应用：
          * 定宽居中
            * width设置为某个值，margin左右设定为auto
          * 两边固定留白，宽度占剩余空间
      * 值为百分比时（宽度，margin都可以写百分比）
        * 跟写长度没有什么区别，基于包含块的宽度（多数时候是父元素的内容区域的宽度）
      * 对于替换元素来说，相当于宽度被提前指定了，其它同非替换元素
        * 宽度写auto是由替换元素的“源”来指定宽度
        * 如果只指定某一个维的尺寸，另一个维会被自动按比例计算出来
          * 即保持了内容的原始比例


    * 垂直方向
      * 也有三个属性可以设置为auto（margin-top/bottom，height）
        * 但是垂直方向margin为auto时相当于0，情况就简单很多了
          * 当前布局是这样,有些其它布局模型里不是这样
      * height为auto时元素的高度是由内容撑开
            *水平方向是包含块决定自己的宽度/垂直方向是子元素(内容)决定自己的高度
        * 分两种情况
          * 元素没有边框也没有内边距时
            * 高度是从最高元素的border-box(不是margin-box)的最高点到最低元素的border-box的最低点
              * 即margin是在外面的
              * 而且子元素的margin成为包含块元素的margin
              * 这就是所谓的外边距合并/margin重叠
            * 但当元素有边框或内边距时或元素触发BFC时，则是能把子元素的margin也包住
          * 当块元素的两个margin在垂直方向上碰到一起的时候，会发生合并
            * 可能出现在相邻的兄弟元素上
            * 可能出现在父子(即上文提到的子元素的margin跑到父元素外面,成为父元素的margin)，爷孙元素上
            * 也可能出现在表兄弟上
            * 也可能出现在叔侄元素之间
            * 自己的上下margin之间
          * 合并时保留绝对值较大者
            * 如果有负的
              * 负值与负值合并(保留绝对值较大者)
              * 正值与正值合并(保留绝对值较大者)
              * 然后正负再抵消
          * BFC 块级格式化上下文 Block Formatting Context
            * 简单来说就是元素形成了小宇宙,内外互不影响
              * 里面的东西不会跑出去,就算跑出去也不会影响外面的布局
            * 多数时候元素的内外本来就互不影响,但还是有少数时候会影响
              * 比如margin超出去,或者下文中行内块元素的基线等
              * 这时触发bfc就可以让元素彻底形成小宇宙
            * 如何触发BFC?
              * overflow:hidden;看起来会让元素把超出的东西隐藏,但当height为auto时,就不会有东西超出去,所以overflow:hidden真想隐藏元素时,都是元素要有定高(只讨论高度)
              * display: flow-root; 比较新的display值,触发bfc,其它方面还是跟块元素一样
              * 定位元素
              * 行内块元素
              * 表单元格元素
      * 高度不为auto时
        * 为固定值
          * 元素的高度就是指定的值
          * 其它元素感知到的它的高度也是这个值
            * 即:如果有内容超出，超出的部分会被别的元素忽略而只考虑该外层元素设置的大小
        * 为百分比, 高度设置为百分比,如果生效,是基于包含块的高度的
            * 只有包含块的高度不为auto时才生效
              * 为什么？因为会形成逻辑冲突:父子元素的高度相互依赖,即为冲突
            * 不生效时相当于auto
            * 包含块也同理，**有可能产生包含块写了高度但实际无效导致当前元素的也无效**
              * 也就是说包含块的百分比高度有效时,其子元素的百分比高度才会有效,否则都会无效
      * 垂直方向上的margin和padding也可以写成百分比
        * 该百分比基于谁?
          * 是基于包含块的宽度
        * 该百分比会不会生效?
          * 会生效,因为不会再形成相互依赖的关系进而产生逻辑冲突了
        * 应用:宽高比固定的元素
      * 列表项（ul，ol，li，dl，dt，dd）的布局
        * 其实就是ul与li都是块元素，只不过ul有一个默认的左内/外边距
        * 以及li有一个项目标号，但它可以不影响布局（也可以影响）


  * ==行内元素的布局==
    * 行内元素有目前两种:inline,inline-block,inline-xxx
    * 行内元素(注意是inline不是inline-block)的垂直布局时是不考虑垂直height,padding,border和margin的，height无效，其它此时只起到装饰作用
      * 水平方向上的属性除width则都具有正常的布局效果
    * 行内元素的布局模式:
      * 先确定每个元素的布局框，然后一个个元素横向排列，空间不够就折行
      * 可以通过vertical-align属性微调元素在那一行的垂直位置
    * 行内布局的基本术语
      * 匿名文本（可以认为匿名文本是按行被行内标签包裹的）
        * 直接被块级标签包裹的文字
        * 或者说没有直接被行内元素（inline）包裹的文字
      * em框(字号框)
        * 其高度由font-size决定
      * 内容区(多个字的框组成的)，content area
        * 注意不是指content-box
      * 行间距
        * 其值的大小是行高减去字号
      * **行内框**
        * 行内布局最重要的就是确定元素的行内框
        * 行内框即是每个行内元素（包括行内块元素）的布局框
      * **行框**
        * 包裹那一行所有行内框的最小框
      * 基线
        * 实际上是文字才有的概念，其它元素没有
        * 贴着字母x底部的那条线
        * 跟em框的相对位置是取决于字体的，不同字体是不一样的
    * 行内布局的过程:
      * 确定每个行内元素的布局框（即行内框）
        * 对于匿名文本,就是其行高(line-height)框,注意不是字号!
          * 字号框是在行高框里垂直居中的
        * 对于被行内元素包裹的文字,也是行高,注意不是字号!
        * 对于行内替换元素（img, button, inline-block),是其margin-box
        * 对于行内块元素,是其margin-box
      * line-height属性用于设置行高，设置在块元素上也是对其内的文字生效
        * 可以指定百分比，px，em，纯数值等，百分比和纯数值时是相对于字号的
        * 默认值为normal，也不是一个固定值，而由字体决定，不同的字体最终生效的值不一样，一般在1.1到1.3之间
      * 然后将元素水平排列,让它们所有的基线对齐
      * 然后在垂直方向上微调,基于vertical-align的值，这个属性只能给到**行内元素**，给块元素没有效果，而是会对其内的行内元素生效（后续表单元格也可以给）
        * baseline 默认值
          * 该元素的基线与该行匿名文本的基线对齐
        * super
          * 元素向上移动一定的距离，具体是多少，没说
        * sub
          * 元素向下移动一定的距离，具体是多少，没说
        * top 元素的行内框顶部对齐行框顶部
        * bottom 元素的行内框底部对齐行框底部
        * middle 行内框中心对齐匿名文本x的中心,并一定是在行框中居中
          * 但如果匿名文本的x中心正好在行框的中心就是了,如匿名文本的字号为0时
        * text-top 底部对齐匿名文本em框顶部
        * text-bottom 底部对齐匿名文本em框底部
          * 实际上以前并不是实测结果
          * 实测结果是对齐行高为normal时文字的布局框的上下
        * 百分比
          * 基于行高的，正值向上，负值向下
        * 长度值
          * 正值向上，负值向下
      * 然后包裹一行中所有元素的最小框即为**行框**
      * 每一行都是如此
      * 所有的行框垂直堆叠之后将包含块撑大

    * 行内块元素
      * 元素自己的位置相当于是行内布局,此时把该元素当成一个图片就好了,不用考虑里面
      * 元素里面的内容认为自己在一个块元素里
        * 也就是说它是它内部元素的包含块
      * 另一个说法是:从外面看是行内元素,或类似于行内替换元素,从里面看是块元素
      * 行内块元素是有盒模型的，可以设置宽高，在行内的布局块也是margin-box
    * 一些需要说明的情况
      * 行内元素的底色框是由什么决定的?
        * 是由默认行高决定的,我们改不了,除非把它改成inline-block元素
        * 它不是元素的布局框
        * 如果不通过padding，border则我们无法单独改变它的高度
        * 文字的选区色块也不能做为任何参考
      * 不存在的字符,只要行存在（行里有内容行就会存在）,那一行就会存在一个匿名文本（只是它不会画再来），所以行高至少也是设置的line-height的值而不是那一行**实际存在**的最小元素
      * 虽然文字的布局框是基于行高的,但其基线是基于字号和字体的
      * 行内块元素的基线
        * 有文字时是最后一行文字的底部,但触发BFC后是布局框底部
        * 没有文字时是布局框(margin-box)的底部
        * 所以如果注意就会造成布局看起来很乱的情况
          * 需要将行内块元素的基线“调整”到其底部，通过触发它的BFC
      * 布局时空间不够肯定是会折行的,就算那一行只少一个像素,也会造成内容的折行
      * 字号大小不一样时由于默认是基线对齐，即使行高相同，文字也对不齐，因为字号的不同导致基线在布局框的不同位置
        * 缩放行高问题，即行高使用纯数值声明，这样一来继承的是书写值而非计算值
      * 空格的问题以及如何消除
      * 垂直绝对居中的问题
        * 让匿名文本字号为零，或者让那一行不存在匿名文本



* 第九章：颜色与背景
  * color
    * 颜色 前景色（与之对应的则是背景色）
      * 一般画图工具中都有类似对应的图标
    * 默认为黑色
    * 会被子元素继承
      * 所以设定一个元素的颜色，其子元素都将是这个颜色
        * 这是很明显的(#333)
    * 会做为border，text/box-shadow的默认值
      * text-shadow: 2px 3px 3px;
      * box-shadow: 5px 10px 5px ;
      * border: 10px solid;
    * css3的currentColor
      * 用在其它属性上比如bgc上，或者linear-gradient等
  * background
    * background-color
      * 背景色
        * 默认值为 transparent  ，即透明
      * 不继承
        * 否则会有奇怪的效果，比如如果设置了semi透明颜色，而且又继承的话。。
    * background-image
      * url()
      * 默认从padding box开始渲染（画）的
      * 背景图片无法从网页上直接复制
    * background-size
      * https://developer.mozilla.org/en-US/docs/Web/CSS/background-size#Browser_compatibility
      * 百分比
        * 图片从哪个盒子开始平铺，那么百分比就基于哪个盒子的宽高
      * contain 图片由无穷小放大到正好被元素包围
      * cover 图片由无穷大缩小到正好覆盖元素
      * object-fit
        * img
        * video等
      * 如果attachment为fixed，背景区为浏览器可视区（即视口），不包括滚动条。不能为负值。
    * background-repeat
      * background-repeat
        * repeat
        * repeat-x/y
        * no-repeat
    * background-origin css3
      * content-box
      * padding-box
      * border-box
      * 与box-sizing的关键字是对应的
    * background-attachment
      * scroll 背景图片相对于元素自身不动
      * local  背景图片相对于元素的内容不动，有滚动条才能看出与前者的区别
      * fixed  背景图片相对于视口不动
        * 为此值时bg-size的百分比以浏览器窗口的大小来计算
        * 可以用来做视差滚动
        * http://www.mi.com/xiaoyi/?cfrom=list
    * background-position
      * background-position-x/y
      * 雪碧图，css sprite
      * 0 0
      * center 200px
      * 100px
      * 0px 10px 相对于左上角
      * 50% 30% 相对于左上角
      * top left /// right bottom 让图片处于某个角落
      * top 20px right 50px   相对于右上角，往元素中心水平偏50px，垂直偏移20px
      * calc(100% - 50px) 从最右往多偏移50px
    * background-clip
      * xx-box
      * 平铺以后再裁剪
      * 连背景颜色一起裁剪到所设置的盒子
    * -webkit-background-clip
      * text  裁到只剩文字经过的区域
    * css3 多背景
      * 分开写，合并写
    * background: <bg-img> <bg-repeat> <bg-origin>  <bg-size> / <bt-pos> , <bg-img> <bg-repeat> <bg-origin> <bg-clip>, <bg-img> <bg-repeat> <bg-origin> <bg-clip> bg-color;
    * 应用
      * 伪元素里的图片，
      * css sprite
      * 动画，菜单，小米网首页logo动画
      * 视差滚动：小蚁摄像机页面效果，Nike活动页面效果
      * 多背景做花纹


* 定位布局
  * 定位布局通过直接指定元素的位置来实现布局
  * 某些定位元素会脱离常规流/正常流
    * 脱离常规流是什么意思？
      * 即其它元素感知不到它们
      * 或者说其它元素当它们不存在
        * 在不指定位置时，它们自己还是以原来的起点为起点
      * 有这个对比，常规流才更好理解，常规流中的元素都能被周围的元素感知到
        * 如父元素、后续的元素等
  * 定位元素的包含块
    * 固定定位：视口
    * 绝对定位：最近的定位祖先（的padding-box，而不是content-box）
    * 相对定位：保持原来的包含块
    * sticky定位：动态变化
    * 不定位：保持原来的包含块
  * 定位元素的布局块：是其margin-box
  * 定位元素自动触发BFC，即里面的margin不会跑出去
  * 定位布局通过position属性触发
  * 有多种定位方式：
    * 固定定位 fixed
      * 脱离常规流，将视口当成自己的包含块
    * 绝对定位 absolute
      * 脱离常规流，把最近的定位祖先（即position不为默认值static）的padding-box当成自己的包含块
        * 当找不到定位祖先时，相对于页面的第一屏定位，即第一屏是它的包含块
      * 一定确定好包含块，剩下的就跟fixed定位差不多了
    * 相对定位 relative
      * 没有脱离常规流，相对于自身原来的位置偏移
      * 如果不指定位置，它就还跟原来一样
    * 粘黏定位 sticky
    * 不定位 static
  * 如果不通过方位属性指定方位，元素在原来的位置，起点也在原来的起点
  * z-index，元素重叠时调整覆盖顺序
    * 只能用在定位元素上，在其它元素上无效（目前）
    * 由于表示的是顺序，所以只能是整数，可以为负
      * 为负时会跑到未定位元素的下方（被未定位元素覆盖）
    * 父元素定位时子元素无法通过z调整到被父元素覆盖
    * z越大元素越能覆盖其它元素，当z相同时，后面的元素盖住前面的元素
  * 定位中的margin：auto和width：auto以及top/left/right/bottom:auto;
    * 两对边的margin：auto时，会平分，垂直方向也会
      * 即可以通过这个手段让元素居中
    * width为auto元素可能被方位属性的指定而拉伸
    * 方位为auto时相应的方向上元素的位置是保持原来的位置
  * 什么时候用定位？
    * 基本上，如果页面中有元素发生了明显的重叠，那么肯定要用到定位。
  * 什么时候不用定位？
    * 元素没有重叠并且后面跟着前面，删除一些元素希望后面的自动向前补位的也不用



* 第八章 padding border margin
  * width
  * height
  * margin vs padding
    * padding区域能看到背景
  * border-style
    * solid,dashed,dotted,double,groove,ridge,outset,inset,hidden,none
    * border-color
    * border-width
    * border-top: red 2px double;
    * border-top-color: blue;
  * border-radius 边框圆角
    * 从左上开始顺时针旋转
    * border-radius: 20px;
    * border-radius: 10px 20px;
    * border-top-left-radius: 30px 15px;
  * border-image;
    * border-image-repeat: space / round;
    * border-image-slice: 84; 注意不能有单位

    * border-image: url(https://tse3-mm.cn.bing.net/th/id/OIP-C.MQvb8oSoGjRT0wKwgw8z6gAAAA?rs=1&pid=ImgDetMain);
    * border-image-slice: 78 [fill]; 图片的裁剪
    * border-image-repeat: round/stretch/space/repeat;  边框图片的重复
    * border-image-width: 40px; 边框图片的宽度,默认跟边框宽度一样,所以如果不设置这个属性就要设置边框宽度了
    * border-image-outset: 7px; 图片向外扩散一定的量,只能为正

  * max-width 设置元素的最大宽度
    * 当width:auto的计算结果大于max-width时,元素的宽度取max-width的大小
  * min-width
    * 当width:auto的计算结果小于min-width时,元素的宽度取min-width的大小
  * max-height
  * min-height
  * visibility:visible,hidden,collapse
    * 设置元素的可见性
    * 元素不可见时位置还是保留的!
  * display: none;
    * 元素完全消失,脱离常规流且不可见
  * opacity 元素的透明度 取值0-1或0%-100%
  * overflow: hidden,auto,visible,scroll
    * overflow-x:;
    * overflow-y:;

* 关于元素的宽度
  * 会比最宽的一个单词要宽
  * 又不会被内容自动撑到比自己的包含块还宽



* 表格布局
  * 表的编排
    * 可以认为有虚拟的分隔线，单元格要么由最小的格子形成，要么由多个最小的格子组合成矩形
  * 表格布局的特点
    * 同一行高度相同
    * 同一列宽度相同
  * 布局方式:行内,块级,定位,浮动,弹性,表格,网格
  * 表格元素的display值
    * table: table,inline-table 块级表,行内表
    * caption: table-caption
    * td: table-cell
    * tr: table-row
    * tbody: table-row-group
    * thead: table-header-group
    * tfoot: table-footer-group
    * col: table-column
    * colgroup: table-column-group
    * 只要愿意,用其它元素按与表格相同的嵌套方式并设置相同的display也可以显示成表格
  * 以行为主的编排,行有对应的标签,但列没有
  * 抽象的列标签只能控制4个样式,同时不能指定交互效果如hover
    * border
    * background
    * width
    * visibility
  * 匿名表对象,css对表格布局元素的自动补全
    * html对table系列标签也会补全
  * 表格元素的层次
    * 单元格,行,行组,列,列组,表
  * 标题
    * 标题的位置 caption-side: top/bottom;
  * 边框模型,合并与分开
    * border-collapse
      * 分隔 separate
        * 分隔时,只有table和td可以设置边框,其它表格元素都不能设置边框
        * border-spacing: x y;
        * empty-cell: show/hide
      * 合并 collapse
        * 合并规则: "最有意思的胜出(most intersting)"
          * 最粗的优先
          * 粗细相同相同看边框样式
            * double>solid>dashed>dotted
          * 样式也相同,只有颜色不同,看来源,层次越高越优先
          * none优先级最低,别的元素在这里设置了边框就显示它的
          * hidden优先级最高,只要这里设置了hidden就没边框
  * 表的大小
    * table-layout: auto/fixed;
  * 对齐
    * vertical-align用在表单格(td,th)上的效果
      * top,bottom,middle,baseline


* 缓动
  * 元素的样式发生变化时不是突变,而是缓慢变到目标样式
  * transition
  * transition-duration 缓动的时间
  * transition-timing-function
    * 控制缓如果随时间进行
    * ease 先慢后快再慢
    * ease-in 先快后慢
    * ease-out 先慢后快
    * linear 匀速
    * steps(n) 步进式
    * steps(n,start) = step-start(n)
    * steps(n,end) = step-end(n)
    * cubic-bezier(.34,.34,.52,.95)
  * transition-delay
    * 缓动延迟一会儿再开始执行
    * 可以为负值,相当于直接从中间开始
    * 相当于看电影时提前到还是迟到了,负值相当于迟到
  * transition-property
    * 哪些属性需要执行缓动
    * 一般只有数值或带单位的数值可以执行缓动
    * 也有个别非数值属性可以执行
      * visibility
  * 多个属性使用不同的方式缓动
    * transition: width 1s, height 2s 2s linear;
    * 等价于下面
    * transition-property: width, height;
    * transition-duration: 1s, 2s;
    * transition-delay: 0s, 2s;
    * transition-timing-function: ease, linear;
  * 缓动的去程与回程使用不一样的缓方式
    * 在div{}和div:hover{}里分别指定不同的transition属性即可



* 浮动布局
  * 浮动是一种外部布局，即它决定的是元素自己的位置，而是其内的元素如何摆放
    * 相比之下，table就属于内部布局
    * 定位是一种外部布局
    * grid、flex都属于内部布局
  * 浮动元素同时处于常规流内与常规流外
    * 即有些元素能感知到它而有些元素感知不到它
      * 块元素感知不到它
      * 行内元素能够感知到它(在块元素里面的元素也能感知)
      * **可以通过一些手段让它能感知到**
        * 什么手段?
  * 浮动元素无需设置display:inline-block等，行内元素浮动时自动变为块框
    * 此时display只改变元素元素的内部布局
    * 外部布局由浮动来决定
  * 浮动这个词如何理解？
  * 浮动与定位一起使用
    * 支持相对定位
      * 相对定位是相对于浮动之后的位置去偏移
    * 不支持与绝对和固定定位一起使用
      * 一起使用时定位优先,完全脱离常规流
  * float:left/right/none;  触发浮动
  * 浮动元素的包含块：同块元素，即最近的块级祖先框
  * 浮动元素的摆放
    * 左浮动不能在左边超出,右浮动不能在右边超出
    * 不能超过其原始包含块的高度
    * 不能超过其原始所在行框
    * 不能高过其包含块
    * 不能高过其前面的块元素的底部
    * 不能高过它前面的浮动元素
    * 不重叠>高>两边
  * 浮动元素的负margin
    * 布局框不是可视区域,而是margin-box
  * 浮动元素与其它元素的覆盖关系
    * 行内盖浮动
    * 浮动盖块级
    * 定位的在最上面（不设置z-index的情况下）
    * 同类型后面盖前面
  * 清除浮动
    * 元素下移以避开相应方向上的浮动元素
    * clear: left/right/both/none;
    * 只能用在块框上（浮动元素也可以用）
  * 闭合浮动
    * 元素变大(往往是变高)以包裹其内的所有浮动元素以避免影响其它元素
    * 一般通过触发bfc实现
      * overflow: hidden;
      * display: flow-root;
      * float: left; 一般不使用这种办法，因为它会让该自身也浮动，又带了其包含需要闭合浮动的问题
    * 也可以借助清除浮动实现
      * 在需要闭合浮动的元素最后加一个块元素并且清除该块元素的浮动，该块元素下移就会撑大需要闭合浮动的元素
  * 浮动的一般应用
    * 横向布局（类似行内块）
      * 没有行内的那些间隙了，但又有新的问题，浮动的闭合
    * 左边（或左右）定宽，右边占据剩余空间
      * 触发bfc的元素是通过变窄（在宽度为auto的情况下）来避开外部浮动元素对其内部的影响的
        * 不能变窄时，类似于clearr:both;，即下移
    * 一些常见的布局（小米产品列表，instagram等）

  * 什么时候后面的元素能影响前面的元素？


* flexbox 弹性盒模型
  * 大号的行内布局,可以方便的创建横/纵向排列的布局
  * 但专为布局而设计，之前的布局方式中可能遇到的问题基本上都不存在
    * 如行内布局水平方向的空格,垂直方向的基线底部留白
    * 浮动的不闭合
    * 尺寸计算也更为灵活
  * 默认摆放方式类似于行内布局，水平排列，空间不够就折行，不同行之间没有关系
  * 可以通过设置主轴，交叉轴的方向来改变排布方向,但99%的情况都是从左往右,折行时从上往下
    * 但一共可以设置八种排布方向
  * 为了方便讲解,我们先只考虑向右排列,向下折行的
  * 通过display: flex/inline-flex;触发弹性盒模型
    * 触发弹性盒模型的元素称为flex container,flex容器
    * 其内的子元素称为flex item,flex子元素,flex子元素不能浮动(无效,但可以定位)(浮动只能存在于块级布局上下文里,无法存在于flex布局上下文或grid布局上下文)
      * flex子元素内默认为块框
  * flex块级弹性盒,inline-flex行内弹性盒,定位弹性盒(+position),浮动弹性盒(+float)
  * 应用于flex container的属性
    * flex-direction: row/column(-reverse);设置主轴方向,或者说设置元素的主要排布方向
    * flex-wrap: wrap/wrap-reverse/nowrap;设置交叉轴(侧轴)的方向,或者说空间不够向哪个方向去折行
    * flex-flow以上两个属性的简写
    * justify-content:;元素在行中的水平分布,左,右,中,space-between,space-around,space-evenly
    * align-content:;所有的行在整个包含块的垂直方向的分布/只有一行时无效,只有一行的时候元素的高度就是那个行
    * align-items:;每行的元素在那一行的垂直位置
    * gap; 设置**元素之间**的间隙
  * 应用于flex item的属性
    * align-self:;应用于flex子元素,用于设置这个元素在行中的垂直位置;与align-items的区别是它只设置一个,而后者批量设置所有子元素
    * order:;改变元素的显示顺序,order越大越在后面,order相同按元素在html中的顺序显示,order默认为0

    * 以下为空间分配相关的属性
    * flex-grow;扩张系数(纯数),设置一行中多余的水平空间如何分配,仅在一行有多余空间时生效
    * flex-shrink;收缩系数(纯数),当空间不够时每个元素怎么收缩,仅在元素超出包含块时生效(即元素不折行,因为一旦折就不会有元素在行中超出,除非这行只有一个元素且它还比包含块长).需要乘以主轴方向上的基础尺寸之后做为收缩权重
      * 由上面的规则可知grow跟shrink只有一个会生效
    * flex-basis;设置元素的基础宽度/高度(取决于主轴的方向,即flex-direction)
      * 即主轴水平时相当于width
      * 主轴垂直时这个属性相当于height
      * 但是它还是受max/min-width/height影响的
      * 当两个都设置的时候,不为auto的那个生效,都不为auto时在flex上下文里是flex-basis生效
    * flex;一次性设置上面三个属性,前一个数代表grow,后一个数代表shrink
      * flex: auto;
      * flex: none;
      * flex: 1;
      * flex: 0;
    * 如果有grow,则这一行就没有额外的空间来进行justify-content了
    * 先根据元素的基础宽度将元素分在每一行,然后在这个结果上对元素进行grow或shrink(所以grow和shrink不会改变元素在哪一行),然后如果有额外空间才会justity-content;
    * g和s它们都是在主轴上生效的,交叉轴由于是一个次要的轴,所以分的话只平分
  * 一些需要讨论的问题
    * 嵌套flex布局
    * flex容器中的匿名文本
      * 连续的匿名文本可以当成一整个flex子元素,但由于元素没有标签,不能为其设置flex相关属性如align-self,grow,shrink等,但是可以通过给父元素设置相关的属性来影响它
        * 可以利用这个来实现双向居中
    * flex容器中的浮动元素
      * flex上下文里不能存在浮动元素,设置浮动无效
    * margin为auto时的情况
      * flex上下文中auto的margin会尽量大且均等分配
      * 空间分配的优先级:gap>grow>margin>justify-content
    * 弹性盒模型中的overflow
    * 横向无法撑开包含块(后续的grid算是解决了这个问题)
  * 案例
    * 小米产品列表
    * 主页大图旁边的产品子菜单
    * instgram布局(无法实现)
  * 作业
    * qq邮箱与oald布局
    * flex froggy





* 伪元素
  * 每个元素内都有一前一后两个隐藏元素(自闭合标签没有)
  * 通过类似这种选择器span::before, span::after选中
    * 选择器严格来说应该是双冒号,但由于历史遗留原因,单冒号也是可以的,但实际上单冒号是伪类的选择器
  * 伪类与伪元素的区别
    * 伪类是实际元素的隐含是状态
    * 伪元素是每个元素前后多个出的隐藏元素
  * 伪元素选择器的后面不能再出现其它选择器了:
    * span::before p {} 这是无意义的,因为伪元素里面肯定没有其它元素了
    * 伪元素不能被:hover匹配
      * span::before:hover 是无效的
      * span:hover::before 这种写法是有效的,表示span被hover时它的伪元素的样式
    * 伪元素选择器本身不计优先级,伪元素样式冲突时看其前序选择器的优先级
  * 不设置内容时它们不出现
    * content属性设置内容，只能给伪元素设置，普通元素无效
      * content: 'woeifj';
      * content: attr(attr-name); 取标签的属性值做为其内容,但不注意不能取标签之间的字做为其内容,只能取属性值
      * content: url(xxx.png); 将图片做为其内容,一般不使用,因为无法设置图片的样式,如果真要用图片,一般是使用background-image来设置伪元素的背景图片
    * 伪元素只在css中存在，在js中不存在，内部的文字也无法选中
  * 内容可以设置为文本，图片但一般只设置为图片
  * 什么时候用
    * 一系列类似元素统一装饰性样式(即不需要交互)，但该样式需要添加额外元素时，即可用伪元素
      * 一般只有装饰性效果使用,可交互效果不使用,因为伪元素不可交互,文字也不可选中
    * 或者是有时为了省去添加一个元素这种操作时使用
* 列表
  * list-style-type: none/circle/square/disc/number 设置项目标号的样式
  * list-style-image: url(xxx.png);用图片来做为项目标号;无法调整和改变图片的大小对齐等,所以一般不使用/可以用伪元素来替代
  * list-style-position: inside/outside;设置项目标号的位置
  * list-style 以上三个属性的简写
* 媒体查询,我们可以根据显示在不同设备上(屏幕还是打印)/窗口的宽度/高度(的范围)/比例/(手机)屏幕方向/像素比例等来启用或禁用一段css代码
  * 根据屏幕的宽度来让页面的布局发生变化
  * @media (max-width: 200px) { 最大生效宽度为200px,即窗口宽度小于等于200时生效 }
  * @media (min-width: 300px) {}
  * 由于上面的写法有点违反直觉,所以现在也支持:
    * @media (width >= 200px) {}
    * @media (height < 5000px) {}
  * @media (width: 200px) {当且仅当窗口宽度为200px时生效}
  * @media (xx) and (yyy) {两个条件同时满足时生效}
  * @media print {打印时生效(如可以在这里去掉背景)}
  * @media screen {显示在屏幕上时生效(如可以在这里去掉背景)}
  * 包在media query里的代码优先级计算方式不变
  * 可以借助这个特性实现响应式页面
* css变量，也称css自定义属性,即属性名可以随意自己定义,需要以--开头,不区分大小写
  * 会自动继承
  * 通过var(--variable-name)引用，可以参与运算
* 选择器嵌套/less/sass
  * 内层的选择器必须以符号开头(~+>*:[.#),不能以字母开头(即标签选择器),sass/less无此限制
  * 内层选择器以&开头时,它与外层选择的连接是没有空格的



* TailwindCSS
  * 类似物：unocss，windi css
  * 传统css写法：
    * 定义html，想类名，在css里为类名写样式
    * 想类名很烦，写出来的css又不好维护
  * tailwind
    * 直接在html的类名中使用工具类名，每个工具类名带来一个方面的样式
    * 不用费劲起类名了
    * 相同的类名可以复用
    * 再也不用维护css代码
  * 为什么不直接使用内联css？
    * 内联无法实现hover，focus等交互效果以及动画等
    * 无法实现响应式
    * 设计不受限制（不受设计语言的限制，但tw可以让设计受限制）
  * 可维护性会比css好吗？
    * 配合一些工具（批量编辑，组件化等）后，会
* 如何安装
  * 最简单的方式：直接引入它的js
    * 用到什么类名，生成什么类名，所以不会出现css文件过大的问题
      * 如果是把你可能用到的类名全部事件生成好，文件大小将会是天文数字，甚至有些效果是完不成的
  * 其它方式官网也有讲
* 小试牛刀
  * 一个全宽文字居中效果
  * 实现一个邮箱布局
  * 实现tw官网示例
  * 实现一个oald布局
  * 实现小米官网产品列表
* hover，focus等
  * hover，focus，active
  * first,last,odd,even
  * required,invalid,disabled
  * 基于祖先的状态进行样式化
    * 给祖先加上group类名，然后在后代中使用group-hover:xxx来在祖先被hover时执行xxx效果
  * 基于前一个元素的状态加样式
    * 前peer后peer-hover:text-xl
  * 自定义类名修饰符
    * [&.foo]:mx-5 当元素有foo类名时应用mx-5效果
    * [&_p]:mt-4
* 响应式
  * sm,md,lg,xl修饰符
* 深色模式
  * dark修饰符
  * 跟随系统vs自行指定
    * @media (prefers-color-scheme: dark/light) {  div {} }
* 工具类
  * 需要时在文档找


* web字体
  * 以往的font-family只能使用用户电脑上装了的字体
    * 这个局限是非常大的，用户不一定安装了你指定的字体
      * 不过可以指定fallback字体
        * font-family: A, B, C, D, serif;
  * css3的这个特性可以让你加载线上字体
    ```
    /* 定义 */



    @font-face {
      写相对路径的时候是相对这句代码所在的文件的文件夹
      src: url(path/to/the/font/file.ttf/eot/woff/otf);
      font-family: TheName;
      font-weight: normal;
      font-style: italic;
    }
    @font-face {
      写相对路径的时候是相对这句代码所在的文件的文件夹
      src: url(path/to/the/font/file.ttf/eot/woff/otf);
      font-family: TheName;
      font-weight: bold;
    }

    /* 使用 */
    div {
      font-family: TheName;
      font-weight: normal;
    }
    ```
  * 中文字体一般不使用在线字体，因为中文字太多字体文件太大
  * 英文字体在线的用的多,因为英文字体字形少,体积就小
    * 谷歌在线字体
  * 但这个特性现在一般用来做在字体图标
    * 文字可以长成各种样子，自然也可以长成图标的样子
    * 加载个在线字体，但这个字体里面的一些字被设计成特殊的样子
  * 与css sprite相比有什么好处
    * 矢量图,放大也清晰
    * 文件更小(因为是矢量图,不是存每个点的颜色,而是存组成图形的线条的贝塞尔曲线的点)
    * 维护时不用担心冲突
    * 可以变颜色(因为是文字)
  * 缺点:
    * 图标整体是单一颜色(但这个颜色可以变化),但足够使用了
    * 修改字体时不如图片容易,但有工具
  * fontawesome
  * 阿里巴巴矢量图标库
  * 字体子集
    * 页面里用到哪些字,就只把这些字的形状写进字体文件
      * 就可以极大的缩小字体文件的大小了
    * 坏处就是页面一次上线只能显示固定的那些字(如产品介绍页面,曾经小米的某个手机的主页就用过)
    * 另一个替代方案就是图片





* 选择器
  * :nth-of-type 某种标签类型中的第n个(将子元素**按标签**分类,每个类别中的第n个)
  * :not(expr) 选中不匹配expr的元素
  * :has(selector) 选中后代中有能满足selector的元素,这个选择器非常强大
    * 可以去看我写的一篇知乎文章
    * 表格列高亮
    * 可以根据里面的元素来确定外面的元素
    * 可以根据后面的元素来确定前面的元素
  * :target 选中页面中当前的目标元素,即页面内滚动时,滚动到的元素,即id的值跟地址中#后面的内容一样的元素
  * :root 选中根元素,一般来说就是html元素了,但网页的根元素可以不是html(不常用)
  * :empty 选中空元素(里面啥也不能有,连空格都不能有)
  * :checked {...} 选中被check的表单元素
  * :disabled {...} 选中被禁用的表单元素
  * :enabled {...} 选中被启用的表单元素
  * :required {...} 选中必填项的表单元素
  * :optional {...} 选中选填项的表单元素
  * :valid {...}   选中填写正确的表单元素
  * :invalid {...} 选中未填写正确的表单元素
  * ::first-line {...} 第一行文字,只能设置文字以及不改变布局的属性,不能改变布局,可以想成是第一文字被标签包起来了
  * ::first-letter {...} 第一个字母,可以改变布局
  * ::marker 列项的前面的标记符
  * ::scrollbar 元素内的滚动条
  * ::placeholder 文本框内的占位提示文字
  * ::selection 被鼠标选中的文字,只能改变文字属性
  * ::after {...}
  * ::before {...}


* grid布局
  * grid是二维布局。其实表格也是二维布局
  * 布局模型：
    * 类似表格，同一行高度相同，同一列宽度相同
    * 将父元素按网格的形式分成区块
    * grid container 网格窗口
    * grid line：分隔空间使用的线
    * grid cell：由线分出来的一个最小的块
    * grid track：一行或一列cell的集合体
    * grid area：由多个最小的块组合成的矩形
    * grid item：放置在area中的grid子元素
      * grid item默认占一个cell,也可以设置成多个
  * grid布局上下文里也不能出现浮动元素
  * grid容器内的连续匿名文本会成为一个grid子元素
  * 适用于grid container的css属性
    * display: grid/inline-grid
    * grid-template-columns: 20% 60% 20%;
    * grid-template-columns: 1fr 1fr 1fr;
    * grid-template-columns: 20% 60% 20%;
    * grid-template-rows: 60px auto 5em;
    * gap 网格间隙
  * 适用于grid item的属性
    * grid-column-start/end: 2;
    * grid-row-start/end: 2;
    * grid-column: 2 / 3;
    * grid-row: 1 / span 3;
    * z-index在grid布局里可以直接使用
    * justify-content/align-content/align-items
  * 重复
    * grid-template-columns: 1fr repeat(11, 10px 1fr);重复11次后面这个东西
  * grid-template-areas: 'a b c';给区域命名
  * 然后就可以用区域的名称来指定grid item的位置了
  * grid-template: grid-template-columns / grid-template-rows;
    * 一个属性设置行和列的模板
  * 隐式grid:当行或列用完时,自动增加的行或列的高或宽
    * grid-auto-columns: 1fr;
    * grid-auto-rows: 80px;
  * grid-auto-flow: row/column  [dense];元素的填充方向,从左往右/从上往下再折行
    * 加个dense的作用是稠密填充
      * 本来一定是按顺序填充
      * 但加个dense的话前面的空位会填前面
  * grid中的对齐,跟flex中使用的几乎是同一组属性控制的,效果也类似
    *
      justify-content: start; 批量调整cell在grid窗口中的水平位置
      justify-items: center; 批量调整grid子元素在cell中的位置
      align-content: space-between; 批量调整cell在grid窗口中的垂直位置
      align-items: center; 批量调整cell在grid窗口中的水平位置
      place-items: ; 一个属性直接设置justify-items和align-items

      align-self: ; 设定子元素在cell中的垂直位置
      justify-self: ;设定子元素在cell中的水平位置
  * 案例:
    * 实现几个常见布局
    * inst https://jsbin.com/yutasicuho/edit?html,css,output
    * 小米产品列表 https://jsbin.com/quqoriguho/1/edit?html,css,output
    * 小米轮播图菜单 https://jsbin.com/zulujahuqi/1/edit?html,css,output
    * 邮箱 https://jsbin.com/cazadicela/1/edit?html,css,output
    * oald https://jsbin.com/yutasicuho/edit?html,css,output



* 2d&3d
  * 23d变换不影响布局
  * 它是在布局结束后对元素生成的图片进行变换
  * 如果元素因为变换移动走了，原位置是保留的，与其它元素重叠时，默认变换过的元素在上层，除非其它元素设置了z-index
  * 只能进行**线性变换**
    * 什么叫线性变换？
      * 把元素想象成一个弹性膜，那么膜的每个位置受到的力是一样的
      * 元素不可能被变了厚度
  * 变换使用一个单一属性进行
  * transform: 变换1 变换2 变换3；
  * 变换的原点（不动点）通过transform-origin: top left;属性设置
    * 默认为元素的中心点
    * 关于不动点的解释及扩展
  * 后续的变换是在前面变换的结果上进行的
    * 如果变换改变了元素的坐标系统，那么后续也是在这个被修改后的坐标系统变换
  * 23d变换的性能问题
    * 在可能的情况下,现代浏览浏览器都是使用显卡进行的变换，且由于变换不影响布局（则无需重新计算布局）
    * 所以性能比通过布局或定位实现的动画效果还要流畅
    * 另外由于布局不存在亚像素（小于一个像素）但图形变换存在，动画会更细腻
  * 支持的变换操作：
    * rotate(角度) 旋转
    * skewx/y() 倾斜
    * scale(),scalex/y() 缩放
    * translate(),translatex/y() 平移
    * matrix() 矩阵变换
  * 变换在执行缓动的时候,如果变换函数序列不一致,将直接从起点用最快的速度变到终点(实际上是两个矩阵变换之间进行缓动)
    * 但是当缓函数序列一致的时候,即方式和数量一致但参数不一致的时候
      * 或一方比另一方多,但前面的全是一样的变换方式
      * 变换是将所有这些函数一一对应进行缓动
  * 双向居中(绝对居中)方案总结
    * https://jsbin.com/nozojudete/3/edit?html,css,output
    * 双向居中方案中至少要有一个元素的某一个维度是不定宽或高的 或者是宽高在一定范围内修改时依然能居中,才能算是一个方案,没有最好的方案,只有最合适的
  * 建议:每行代码都写注释


* 移动端布局
  *   <meta name="viewport" content="width=device-width, initial-scale=1.0">
  * 上面的标签只被手机浏览器识别,电脑上的浏览器会忽略它(打开模拟手机时除外)
  * 如果没有这个标签,手机浏览器在显示网页的时候就会认为自己是一个电脑网页
  *  因为老旧的网站里都没有这个标签,手机为了正确显示它,认为它极有可能是为电脑设计的,所以把宽度设置为电脑浏览器的典型宽度,目前最典型的宽度为980
* 
  * 在给电脑设计页面的时候,不用考虑用户电脑浏览器的宽度,因为电脑屏幕足够宽,并且我们假设用户在全屏使用的,而且页面的主体宽度往往不如屏幕宽的
  * 所以设计电脑网页时,主体内容往往是宽,或只有两个宽度,通过media query切换
  * 因为电脑屏幕足够宽,我们用不完
* 
  * 手机屏幕本就很小,我们是有必要将屏幕空间用完的(手机上的app也都是这么做的)
  * 但是,默认情况下,手机浏览器为网页设置的视口宽度是不一样的,即device-width的具体值是不一样的,往往屏幕越大它的值也越大
  * 这就意味着我们面对着不同的窗口宽度,并且设计的网页还要将窗口宽度占满
* 
  * 额外补充:手机浏览器总能通过缩放显示页面的全貌,即如果有内容超出正常的视口,页面是可以捏合缩小以显示全貌的
* 
* 
  * 我们希望的是,所有的用户手机浏览器的宽度是一样的
  *    <meta name="viewport" content="width=, initial-scale=1.0">
  * 现在可以通过在viewport声明中设置width=一个数值(注意不要带单位)来直接设定手机浏览器绘制页面时的宽口宽度,也即是初始包含块的宽度.202406测试的结果是一些手机不能设置的太小,设置的* 太小会被重置
  * 相当于我们回到了 面对同样的浏览器宽度的情况
  * 这样一来,设计和实现页面就非常容易了
  * a tale of two viewport
* 
  * 但是
  *   1. 如果把不同大小的屏幕都设计为相同的浏览器宽度,则会造成页面中同一个按钮在不同手机上大小不一样
  *   甚至在小手机上小的太厉害以至于不好点到,字也可能过小
* 
* 
  *   2. 一些老旧的手机甚至不支持把width写成数值,只能写成device-width,这是它唯一可选的值
  *   我们又回到了面对不同宽度的手机的情况了.
  *   实际上,到4202年,这种情况真的不多见了
  *   (小米5是支持写数值的,2016年上半年发布的手机,距今8年)
* 
  *   这种时候我们还是希望我面对的是相同的浏览器宽度.
  *   解决方案: 100vw任何时候都是屏幕的宽度,不管实际上窗口的宽度是多少
  *   这时单位又统一起来了
  *   (刚刚是不管手机屏幕有多大,我们都用400px做为统一的单位)
  *   区别是,400px的这个值我们可以任意设置
  *   但100vw这个值是固定的
* 
* 
* 
  *   设计师给的设计图,往往宽度是设计师自己手机的屏幕的物理像素的宽度
  *   (设计师不一定懂技术,懂可能也不懂到这些细节)
* 
  *   无论如何,设计图宽度肯定不会是100,典型的值(宽度)是720或1080或1000
* 
  *   我希望设计图宽度为X时,图总是铺满手机屏幕的
  *   即图里的X长度应该等于100vw
  *   我们需要找一个单位
  *   X单位=100vw
  *   而rem正是这个可以灵活缩放的单位
  *   于是Xrem=100vw
  *   1rem = 100vw / X
  *   于是 html { font-size: calc(100vw / X);   }
  *   这样设置后设计稿中测量出来的尺寸直接加上rem单位即写进代码
  *   (实际上任何时候我们都希望测量出来的值加上单位就可以直接写进代码了)
* 
  *   但是,不支持width写成任意值的浏览器可能不支持calc或vw单位
  *   很多浏览器并不支持小于12px的字号,而上述公式计算出来的结果大概率是小于12像素的
  *   所以我们还需要对该公式乘以100(乘以10不保险),以及可能要通过js来完成这个calc的操作(读取屏幕宽度并除以设计稿宽度)
  *   乘完100后,设计稿里量出来的值就要除以100了,这个好办,移动一下小数点就可以了
* 
* 
* 
  *   最后的问题:
  *   让一个设计稿通过缩放的方式显示在不同大的手机上是正确的做法吗?
  *   应该说在屏幕分布范围比较大的时候,是不合理的,也是不应该的
  *   我们应该做的是让不同大小的屏幕有着不同的设计,至少字要够看
  *   所以实际上最正确的做法是永远使用device-width
  *   但这会让实现成本增加(在屏幕大小都差不多的时候几乎是零成本)
  *   所以很多公司选择直接写死手机浏览器窗口宽度为一个固定值

 
* 计数器
* value & sizing
* -webkit-前缀
* 回流与重绘
  * reflow/relayout vs repaint
  * reflow/relayout: 重新计算布局
    * 当页面发生一些变化，浏览器需要针对这个页面重新计算它的布局，就叫relayout，重新计算之后再画出页面
      * relayout是包含repaint的
  * repaint
    * 页面发生另一些变化如颜色，浏览器不需要重新计算布局（因为没有元素的布局发生变化）则不用重新计算布局，直接修改相应的颜色等就可以画出变化后的页面
  * relayout需要重新计算布局，所以更耗时，而repaint不用重新计算布局，而是可以复用以前的布局计算结果，只需要重新应用颜色，所以耗时更短
  * 在实现一些页面效果的时候，如果能通过仅触发repaint来实现就不要触发relayout，可以节省时间，提高页面的响应速度
  * 实现让元素移动的效果：
    * 选择使用transform > 选择使用定位 > 选择使用margin
    * 浏览器是足够聪明到不需要计算所有元素的布局的，只需要计算必要的元素
* FOUC FOUT
  * Flash Of Unstyled Content 未样式化的元素的闪烁
    * 在曾经的ie浏览器里只要用了@import的css语法，不管网速有多快，都是必闪无疑
      * 解决办法是不使用@import；直接把css写在页面内的style标签里（这样一来浏览器只要下载那一个页面的代码，页面就能看了）
  * Flash Of Unstyled Text
    * 在使用web字体的时候出现的，web字体文件还没下载下来，文字显示的是用户电脑上的文字，字体下载好后显示的是web字体的样式



* 小米页面作业 *
* 高级轮播图 *
* 公转不自转作业 *
* clock  *
* hover切换 *



* 3d cube 作业
* ios checkbox
* 小米某活动页面侧边栏,菜单文字双色
