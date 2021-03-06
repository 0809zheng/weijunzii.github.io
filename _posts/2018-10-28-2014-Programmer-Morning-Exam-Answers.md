---
layout: post
title: '初级程序员 2014 上半年上午试题答案'
subtitle: '哭了'
date: 2018-10-28
author: 伪君子
categories: 技术，编程
cover: ''
tags: 题

---

* content
{:toc}
1、D
2、A
[ 解析 ] 在 Word 编辑状态下， 当鼠标指针移到图片上变成 “$\updownarrow$ ”表示图形在垂直方向上进行缩放；当鼠标指针到图片上变成 “ $\longleftrightarrow$ ”表示图形在水平方向上进行缩放；当鼠标指针移到图片上“$\swarrow$ ”变成 “$\searrow$ ”  表示图形在水平和垂直两个方向上进行缩放。

若用户选择了表格中的一行，并执行了表格菜单中的 “删除列 ”命令，即要删除所选行对应的列，这意味着整个表格被删除。
3、 D
4、B
[ 解析 ] 本题考查 Excel 基本概念方面的知识。

Excel 规定公式以等号 (=) 开头，选项 A 和选项 C 没有 “=”故不正确。选项 B 是错误的，因为函数 COUNT的格式为： COUNT(参数 1，参数 2，⋯⋯) ，其功能是求各参数中数值型参数和包含数值的单元格个数， 所以公式 “ =COUNT(g3:g12," ＜60")" 中 G3:G12 单元格保存了 10 个数值， 而参数 “＜60”为非数值型参数， 故 COUNT计算结果等于 10 ，显然不正确。选项 D 是正确的，因为函数 COUNTIF 的格式为： COUNTIF( 取值范围，条件式 ) ，其功能是计算某区域内满足条件的单元格个数，选项 D 是计算 G3:G12 单元格区域中小于 60 分的单元格的个数，结果等于 1。

IF 函数的格式为 IF( 条件式，值 1，值 2) ，若满足条件，则结果返回值 1，否则，返回值 2。IF 函数可以嵌套使用，最多可嵌套 7 层。本题在 H3 单元格输入选项 B“ =IF(G3＞=85," 优秀 ",IF(G3 ＞=60," 及格 "," 不及格 ")) ”的含义为： 如果 G3 单元格的值＞ =85 ，则在 H3 单元格填写 " 优秀 ", 否则如果 G3＞=60 ，则在 H3 单元格填写 " 及格 ", 否则填写 " 不及格 ") 。

5、A
[ 解析 ] 本题考查收发电子邮件地址格式方面的基础知识。

电子邮件地址格式是用户名和域名之间用符号 “@”分隔。

6、D
[ 解析 ] 本题考查计算机系统基础知识。

设机器字长为 8，对于数值 0，其原码表示为 [+0] 原 =00000000 ，[-0] 原 =10000000 ；其反码表示为 [+0]反 =00000000，[-0]反 =11111111；其补码表示为 [+0]补 =00000000，[-0] 补 =00000000 ；若偏移量为 $2^7$，则0 的移码表示为 [+0]移 =10000000 ， [-0] 移=10000000 。因此，在补码和移码表示中， 0 仅用一个编码。

7、B
[ 解析 ] 本题考查计算机系统基础知识。

程序计数器 (PC) 用于存放指令的地址。 当程序顺序执行时， 每取出一条指令， PC 内容自动增加一个值，指向下一条要取的指令。当程序出现转移时，则将转移地址送入 PC，然后由 PC 指出新的指令地址。

通用寄存器组是 CPU 中的一组工作寄存器，运算时用于暂存操作数或地址。在程序中使用通用寄存器可以减少访问内存的次数，提高运算速度。

累加器是一个数据寄存器，在运算过程中暂时存放操作数和中间运算结果，不能用于长时间地保存一个数据。
8、A
[ 解析 ] 本题考查计算机系统基础知识。

CPU 与 I/O 设备交换数据时常见的控制方式有程序查询方式、中断方式、 DMA方式和通道方式等。 在程序查询方式下， CPU执行指令查询外设的状态， 在外设准备好的情况下才输入或输出数据。 在中断方式下， 是外设准备好接收或发送数据时发出中断请求， CPU无需主动查询外设的状态。在 DMA 方式下，数据传送过程是直接在内存和外设间进行的，不需要 CPU 执行程序来进行数据传送。

9、B
[ 解析 ] 本题考查计算机系统基础知识。

随机存储器 (RAM) 分为静态随机存储器 (SRAM) 和动态随机存储器 (DRAM) 两类。其中，SRAM速度快，不需要刷新操作，缺点是集成度低价格高，在主板上不能作为用量较大的主存。 DRAM是最为常见的内存储器，采用电容存储，其数据只能保持很短的时间，每隔一段时间需要刷新充电 1 次，否则内部的数据会丢失。

对于可编程的只读存储器 (Programmable Read Only Memory ， PROM)，其内容可 以 由 用 户 一 次 性 地 写 入 ， 写 入 后 不 能 再 修 改 。 可 擦 除 可 编 程 只 读 存 储 器(ErasableProgrammable Read Only Memory ， EPROM)的内容既可以读出，也可以由用户写入， 写入后还可以修改。 常见的改写方法是先用紫外线照射 15 ～20 分钟以擦去所有信息，然后再用特殊的电子设备写入信息。

10 、C
11 、B
[ 解析 ] 本题考查应试者计算机性能评价方面的基础知识。

计算机的时钟频率直接反映了机器的速度，通常主频越高其速度越快。但是，相同频率、不同体系结构的机器， 其速度可能会相差很多倍， 因此还需要用其他方法来测定机器性能。

通常所说的计算机运算速度 ( 平均运算速度 ) 是指每秒钟所能执行的指令条数，一般用“百万条指令 / 秒 ”(MIPS，Million Instruction Per Second) 来描述。

12 、A
[ 解析 ] 本题考查知识产权基本知识。

侵害知识产权的行为主要表现形式为剽窃、篡改、仿冒等，这些行为施加影响的对象是作者、创造者的思想内容 ( 思想表现形式 ) 与其物化载体无关。擅自将他人的软件复制出售的行为涉及的是软件开发者的思想表现形式，该行为是侵犯软件著作权行为。侵害有形财产所有权的行为主要表现为侵占、 毁损等，这些行为往往直接作用于 “物体 ”本身， 如将他人的财物毁坏， 强占他人的财物等。 将他人的软件光盘占为己有涉及的物体本身，即软件的物化载体，该行为是侵犯有形财产所有权的行为。

13 、D
[ 解析 ] 本题考查知识产权基本知识。

商标是生产经营者在其商品或服务上所使用的，由文字、图形、字母、数字、三维标志和颜色，以及上述要素的组合构成，用以识别不同生产者或经营者所生产、制造、加工、拣选、 经销的商品或者提供的服务的可视性标志。 己使用商标是用于商品、 商品包装、 容器以及商品交易书上， 或者用于广告宣传、 展览及其他商业活动中的商标。 注册商标是经商标局核准注册的商标， 商标所有人只有依法将自己的商标注册后， 商标注册人享有商标专用权，受法律保护。 未注册商标是指未经商标局核准注册而自行使用的商标， 其商标所有人不享有法律赋予的专用权， 不能得到法律的保护。 一般情况下， 使用在某种商品或服务上的商标是否申请注册完全由商标使用人自行决定， 实行自愿注册。 但对与人民生活关系密切的少数商品实行强制注册，如对人用药品，必须申请商标注册，未经核准注册的，不得在市场销售。

14 、A
15 、D
[ 解析 ] 本题考查考生多媒体基础知识。

表现媒体是指进行信息输入和输出的媒体，如键盘、鼠标、话筒，以及显示器、打印机、喇叭等。传输媒体是指传输表示媒体的物理介质，如电缆、光缆、电磁波等。表示媒体指传输感觉媒体的中介媒体，即用于数据交换的编码，如图像编码、文本编码和声音编码等； 存储媒体是指用于存储表示媒体的物理介质， 如硬盘、软盘、磁盘、光盘、ROM及 RAM等。

16 、B
[ 解析 ] 本题考查多媒体基础知识。

矢量图是用一系列计算机指令来描述一幅图的内容，即通过指令描述构成一幅图的所有直线、曲线、圆、圆弧、矩形等图元的位臵、维数和形状，也可以用更为复杂的形式表示图像中的曲面、光照、材质等效果。矢量图法实质上是用数学的方式 ( 算法和特征 ) 来描述一幅图形图像， 在处理图形图像时根据图元对应的数学表达式进行编辑和处理。 在屏幕上显示一幅图形图像时， 首先要解释这些指令， 然后将描述图形图像的指令转换成屏幕上显示的形状和颜色。位图 ( 点阵图 ) 、灰度图是采用像素来描述一幅图形图像。

17 、A
[ 解析 ] 本题考查计算机病毒的基础知识。

文件型计算机病毒感染可执行文件 ( 包括 EXE 和 COM文件 ) 。一旦直接或间接地执行了这些受计算机病毒感染的程序， 计算机病毒就会按照编制者的意图对系统进行破坏， 这些计算机病毒还可细分为：驻留型计算机病毒、主动型计算机病毒、覆盖型计算机病毒、伴随型计算机病毒。

18 、B
[ 解析 ] 本题考查木马程序的基础知识。

木马程序一般分为服务器端 (Server) 和客户端 (Client) ，服务器端是攻击者传到目标机器上的部分， 用来在目标机上监听等待客户端连接过来。 客户端是用来控制目标机器的部分，放在攻击者的机器上。木马 (Trojans) 程序常被伪装成工具程序或游戏，一旦用户打开了带有特洛伊木马程序的邮件附件或从网上直接下载， 或执行了这些程序之后， 当你连接到互联网上时，这个程序就会通知黑客用户的 IP 地址及被预先设定的端口。黑客在收到这些资料后， 再利用这个潜伏其中的程序， 就可以恣意修改用户的计算机设定、 复制任何文件、窥视用户整个硬盘内的资料等，从而达到控制用户的计算机的目的。现在有许多这样的程序，国外的此类软件有 Back Office 、Netbus 等，国内的此类软件有 Netspy 、 YAI 、SubSeven 、冰河、 “广外女生 ”等。 Sniffer 是一种基于被动侦听原理的网络分析软件。 使用这种软件， 可以监视网络的状态、 数据流动情况以及网络上传输的信息，其不属于木马程序。 

20 、A
[ 解析 ] 本题考查数据表示基础知识。
  $2^{7}+2^{5}+2^{2}+2^{0}$=10000000+100000+100+1=10100101，表示为十六进制为 A5，在十进制情况下为 165 ，即 128+32+4+1 。

21 、B
[ 解析 ] 本题考查逻辑运算基础知识。

显然，符合题目描述的运算是 X+Y。

22 、D
[ 解析 ] 本题考查计算机系统基础知识。

如果一个作业的部分内容装入主存便可开始启动运行，其余部分暂时留在磁盘上，需要时再装入主存。 这样就可以有效地利用主存空间。 从用户角度看， 该系统所具有的主存容量将比实际主存容量大得多， 这样的存储器称为虚拟存储器。 虚拟存储器是为了扩大主存容量而采用的一种设计方法， 其容量是由计算机的地址结构决定的， 实现虚拟存储器既需要硬件，也需要软件。

23 、D
24 、B
[ 解析 ] 本题考查应试者 Windows 操作系统方面的基础知识。

在 Windows 系统中的文件名最长可达 255 个字符；文件名中可以使用大写或小写字母，系统会保留创建文件时所使用的大小写字母， 但文件名不区分大小写。 例如， 用户创建的文件名为 “ license.doc ”，当用户修改此文件并另存为 “ LICENSE.doc ”时，系统仍然将文件保存为 “ license.doc ”。

25 、A
[ 解析 ] 本题考查操作系统文件管理方面的基础知识。

操作系统文件管理中为了实现 “按名存取 ”，系统必须为每个文件设臵用于描述和控制
文件的数据结构， 它至少要包括文件名和存放文件的物理地址， 这个数据结构称为文件控制
块(FCB) ，文件控制块的有序集合称为文件目录。 换句话说， 文件目录是由文件控制块组成
的，专门用于文件的检索。

26 、B
[ 解析 ] 本题考查操作系统进程管理方面的基础知识。

在操作系统进程管理中，进程调度方式是指某进程正在运行，当有更高优先级的进程到来时如何分配 CPU。调度方式分为可剥夺和不可剥夺两种。 可剥夺式是指当有更高优先级的进程到来时，强行将正在运行进程的 CPU 分配给高优先级的进程；不可剥夺式是指当有更高优先级的进程到来时，必须等待正在运行进程自动释放占用的 CPU，然后将 CPU 分配给高优先级的进程。

27 、C
[ 解析 ] 本题考查操作系统存储管理方面的基础知识。

在请求分页系统中，当访问的页面不在主存时会产生一个缺页中断，缺页中断与一般中断的主要区别是缺页中断是在指令执行期间产生并进行处理的， 而一般中断是在一条指令执行完，下一条指令开始执行前进行处理的。 缺页中断在一条指令执行期间可能会产生多次，每当发生缺页中断并进行处理后，将返回到被中断指令开始重新执行。

29 、B
[ 解析 ] 本题考查程序语言基础知识。

COBOL 是面向事务处理的语言， XML 即可扩展标记语言， PROLOG 是逻辑式语言， LISP 是函数式语言。 Python 可称为通用的脚本语言。

30 、A
[ 解析 ] 本题考查程序语言基础知识。

程序语言的控制成分提供运算的控制逻辑，已经证明程序的控制结构可分为顺序、选择( 或分支 ) 和循环结构三种。

31 、C
[ 解析 ] 本题考查程序语言翻译基础知识。

一般情况下，编译程序的工作过程可以分为词法分析、语法分析、语义分析、中间代码生成、代码优化和目标代码生成等 6 个阶段，还需要有错误处理和符号表管理。其中，语法分析的任务是在词法分析的基础上， 根据语言的语法规则将单词符号序列分解成各类语法单位，如 “表达式 ”、“语句 ”和“程序 ”等。如果源程序中没有语法错误，语法分析后就能正确地构造出其语法树；否则就指出语法错误，并给出相应的诊断信息。 词法分析和语法分析本质上都是对源程序的结构进行分析。

32 、D
[ 解析 ] 本题考查程序语言基础知识。

内存空间在逻辑上可以划分为代码区和数据区两大部分，其中，数据区又可分为静态数据区、栈区和堆区。代码区存放指令，运行过程中不能修改。一般情况下，全局变量的存储单元位于静态数据区， 局部变量的存储单元存放在栈区， 根据需要动态申请和释放的动态变量的存储空间在堆区。

33 、A
[ 解析 ] 本题考查 C 语言知识。

在 C 程序中，以#开头的命令称为预处理命令， 对源程序编译之前就处理该类命令。 

34 、C
35 、D
[ 解析 ] 本题考查程序语言基础知识。

正规式 (ab|c) 表示的正规集为 {ab ，c} ，正规式 (0|1|2) 表示的正规集为 {0 ，1，2} ，
将 {ab ，c) 与 {0 ，1，2) 进行连接运算后的正规集为 {ab0 ，ab1 ，ab2 ，c0 ，c1 ，c2} ，
因此该正规集有 6 个元素， c0 属于该集合。

36 、A
[ 解析 ] 本题考查数据结构知识。

线性表采用单链表存储时，每个元素用一个结点表示，结点中的指针域指出后继元素所在结点，存取元素时只能从头指针出发顺序地查找元素， 可根据需要动态申请和释放结点，也不要求结点的存储地址连续。 在单链表上插入和删除元素只需要修改逻辑上相关的元素所在结点的指针域，而不需要移动元素。

37 、C
[ 解析 ] 本题考查数据结构基础知识。

栈和队列是运算受限的线性表， 栈的特点是后入先出， 即只能在表尾插入和删除元素。队列的特点是先进先出， 也就是只能在表尾插入元素，而在表头删除元素。 因此， 一个序列经过一个初始为空的队列后，元素的排列次序不变。在使用栈时， 只要栈不空，就可以进行出栈操作，因此，一个序列经过一个初始为空的栈后，元素的排列次序可能发生变化。

38 、A
[ 解析 ] 本题考查数据结构基础知识。

串的模式匹配是指模式串在主串中的定位运算，即模式串在主串中首次出现的位置。

39 、C
[ 解析 ] 本题考查数据结构基础知识。

对于矩阵，压缩存储的含义是为多个值相同的元素只分配一个存储单元，对零元素不分配存储单元。 如果矩阵的零元素有规律地分布， 则可将其非零元素压缩存储在一维数组中，并建立起每个非零元素在矩阵中的位臵与其在一维数组中的位臵之间的对应关系。

40 、C
[ 解析 ] 本题考查数据结构基础知识。

若深度为 k 的二叉树有 $2^k$-1 个结点， 则称其为满二叉树。 满二叉树中每层上的结点数达到最大值。可以对满二叉树中的结点进行连续编号，约定编号从根结点起，自上而下、自左至右依次进行。深度为 k、有 n 个结点的二叉树，当且仅当其每一个结点都与深度为 k的满二叉树中编号为 1～n 的结点一一对应时， 称之为完全二叉树。 高度为 3 满二叉树如下图(a) 所示，具有 6 个结点的完全二叉树如下图 (b) 所示，下图 (c) 则不是完全二叉树。
![](https://upload-images.jianshu.io/upload_images/2989110-e31477f0a9974b51.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
从上图中可知，在完全二叉树中，除最后一层结点数不满以外，其余层的结点数都达到最大值。若完全二叉树有 25 个结点，则其前 4 层结点数为 15(1+2+4+8) ，第 5 层上就有 10 个结点 ( 即 25-10) ，尚未超过该层最多 16 个结点的上限， 因此该二叉树的高度为 5。

41 、C
[ 解析 ] 本题考查数据结构基础知识。

根据二叉排序树的定义，当新来的元素大于根结点的关键码时，应将其插入根结点的右子树中， 当新来的元素小于根结点的关键码时， 应将其插入根结点的左子树中， 在子树上同样如此。 由于 45 大于 23 ，因此将其插入结点 31 的右子树中，又由于 45 大于 31 、小于91 、小于 61 ，因此最后将其作为 61 的左子树加入该二叉树中。

42 、B
[ 解析 ] 本题考查数据结构基础知识。

由于数组一旦被定义，就不再有元素的增减变化，因此对数组通常进行的两种基本操作为读取和修改，也就是给定一组下标，读取或修改其对应的数据元素值。

43 、D
[ 解析 ] 本题考查数据结构基础知识。

从题图中可知，顶点 A、B、C、D、E 的编号为 1～ 5，因此顶点 A 的邻接表中的两个结点表示：存在顶点 A 至顶点 B 的弧且权值为 5，存在顶点 A 至顶点 D 的弧且权值为 8，再考查顶点 B 只有一个邻接顶点 E，因此该图为有向图，有 7 条弧，如下图所示。
![](https://upload-images.jianshu.io/upload_images/2989110-3b5adfd5c71ace93.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
若在有向图中， 每对顶点之间都存在路径， 则是强连通图。 上图不是强连通图， 例如，顶点 C 至 B 有路径，反之则没有路径。在有向图中，顶点的入度是以该顶点为终点的有向边的数目，而顶点的出度指以该顶点为起点的有向边的数目。对于顶点 B，其出度为 1，而入度为 3

44 、A
45 、B
[ 解析 ] 本题考查面向对象的基本知识。

继承是父类和子类之间共享数据和方法的机制。这是类之间的一种关系，在定义和实现一个类的时候， 可以在一个已经存在的类的基础上来进行， 把这个已经存在的类所定义的内容作为自己的内容， 并加入若干新的内容， 即子类比父类更加具体化。 

封装是一种信息隐蔽技术，其主要目的是对象的使用者和生产者分离，是对象的定义和实现分开。多态(polymorphism) 是不同的对象收到同一消息可以进行不同的响应， 产生完全不同的结果，用户可以发送一个通用的消息， 而实现细节则由接收对象自行决定， 使得同一个消息就可以调用不同的方法， 即一个对象具有多种形态。 

覆盖是一个名称多个含义， 即同一个方法名称，带有不同的参数个数或类型。 交通工具是泛指各类交通工具， 而汽车是一种交通工具， 且具有自己的特性。 因此，继承关系最适合表达这些类的设计，在继承交通工具的基础上， 设计汽车类，添加自己特有的行为，设计出子类。

46 、D
47 、C
[ 解析 ] 本题考查面向对象的基本知识。

继承是父类和子类之间共享数据和方法的机制。这是类之间的一种关系，在定义和实现一个类的时候， 可以在一个已经存在的类的基础上来进行， 把这个已经存在的类所定义的内容作为自己的内容， 并加入若干新的内容， 即子类比父类更加具体化。 

封装是一种信息隐蔽技术，其主要目的是对象的使用者和生产者分离，是对象的定义和实现分开。多态(polymorphism) 是不同的对象收到同一消息可以进行不同的响应， 产生完全不同的结果，用户可以发送一个通用的消息， 而实现细节则由接收对象自行决定， 使得同一个消息就可以调用不同的方法， 即一个对象具有多种形态。 

覆盖是一个名称多个含义， 即同一个方法名称，带有不同的参数个数或类型。 

48 、A
[ 解析 ] 本题考查 UML 建模的基本知识。

UML 中序列图、通信图、活动图和交互概览图都用于建模系统动态方面。序列图描述以时间顺序组织的对象之间的交互动态视图， 通信图强调收发消息的对象的结构组织。 交互概览图描述交互 ( 特别是关注控制流 ) ，但是抽象掉了消息和生命线。序列图、通信图和交互概览图都是交互图。 活动图是一种特殊的状态图， 它展现了在系统内从一个活动到另一个活动的流程。

49 、A
50 、B
[ 解析 ] 本题考查结构化分析和设计方法的基础知识。

数据流图从数据传递和加工的角度，以图形的方式刻画数据流从输入到输出的移动变换过程，其基础是功能分解。 在结构化分析过程中， 一般采用分层的数据流图来对功能建模，从顶层数据流图开始，逐层分解。一个待开发的软件系统的顶层数据流图只有一个加工。模块独立性是创建良好设计的一个重要原则，一般采用模块间的耦合和模块的内聚两个准则来进行度量。 

内聚是模块功能强度的度量， 一个模块内部各个元素之间的联系越紧密，则它的内聚性就越高， 模块独立性就越强。 一般来说模块内聚性由低到高有巧合内聚、 逻辑内聚、时间内聚、过程内聚、通信内聚、信息内聚和功能内聚七种类型。若一个模块把几种相关的功能组合在一起， 每次被调用时， 由传送给模块的判定参数来确定该模块应执行哪一种功能， 则该模块的内聚类型为逻辑内聚。 若一个模块内的处理是相关的， 而且必须以特定次序执行， 则称这个模块为过程内聚模块。 信息内聚模块完成多个功能， 各个功能都在同一数据结构上操作， 每一项功能有一个唯一的入口点。 若一个模块中各个部分都是完成某一个具体功能必不可少的组成部分，则该模块为功能内聚模块。

51 、C
[ 解析 ] 本题考查软件测试的基础知识。

黑盒测试也称为功能测试，在完全不考虑软件的内部结构和特性的情况下，测试软件
的外部特性。黑盒测试主要是为了发现以下几类错误：
①是否有错误的功能或遗漏的功能 ?
②界面是否有误 ?输入是否正确 ?输出是否正确 ?
③是否有数据结构或外部数据库访问错误 ?
④性能是否能够接受 ?
⑤是否有初始化或终止性错误 ?

52 、A
[ 解析 ] 本题考查软件工程的基础知识。

一般来说，软件开发中的错误越早发现，修改的成本越小。在维护阶段，发现越早期的错误，修改和维护的成本就越大。 因此，从维护成本上说， 需求阶段的错误维护代价最高，然后依次是概要设计阶段、 详细设计阶段和编码阶段。 这从另一方面提示开发人员提高每一阶段的开发质量，并重视阶段制品的评审工作。

53 、D
[ 解析 ] 本题考查软件工程 ( 程序员素质 ) 基础知识。

编程是一项强脑力劳动，从构思设计到写代码需要专心细致地做工作。人在疲劳、烦心时，思路也不会清晰，编程容易出错。而且，程序出错后的检查纠错很麻烦，隐蔽的错误更会严重影响应用效果， 甚至会造成很大损失。所以，此时还不如放下编程，先做些事务性工作，等人的状态休整好了，再做编程，效果会更好。

最近几年的实践表明， “先写测试方案再编程 ”的测试驱动开发是切实可行的，也有利
于提高软件的质量。由于专业程序员需要注重实现细节，常常对自己经过反复思考获得的算法实现逻辑非
常自信，常常表现出自负、固执和内向，特别是多人共同编程时，常会产生争执。因此，强调协作精神是非常重要的。

软件开发过程中， 由于各种技术因素十分复杂， 拖延工期很常见。 用户要求按期交付，经理则常来催促。 专业程序员应向经理如实说明拖延工期的原因， 解释软件测试等因素的复杂性和不确定性， 这些因素不是增加人力和加班所能解决的， 如实说明赶工期的危害性。 专业程序员应根据经验估计，经过最大努力最快能在什么时间交付，由经理再仔细考虑决策。一味听从经理安排， 可能事与愿违， 有时不得不减少测试，降低软件质量， 造成更大的应用问题。据统计，大部分用户催促交付，不过是强调合同的重要性，即使真的按期交付，也会放在那里一段时间，等待投入使用。

54 、D
[ 解析 ] 本题考查软件工程 ( 应用软件特点 ) 基础知识。

企业管理、电子政务、电子商务等应用中，科学计算量不大，重点是按流程进行规范
处理，在处理过程中特别强调人机交互， 因此，弱计算、 强流程、 多交互是这些应用的特点。

55 、A
[ 解析 ] 本题考查软件工程 ( 软件开发 ) 基础知识。

软件设计要根据用户需求进行。有些开发者故意扩大需求，希望软件能更通用些，应用领域更广些， 软件生命期更长远些，但其结果是，软件的复杂性增加了， 测试也难以充分进行， 软件质量反而下降，交付期也不得不延长， 用户反而不满意。还不如按照用户近期的切实需求进行开发，待应用一段时间后，再考虑升级版本，拓展应用。

软件开发者对所开发软件的功能肯定是非常熟悉的， 但对其实际运行的性能 ( 例如响应时间，并发用户数量的影响等 ) 可能不太了解。大部分性能可以通过测试来了解。测试得越充分，对性能的了解程度也就越高，发现的问题也就需要想办法来解决。很明显， 软件越复杂则维护越困难， 因此，尽量保持简洁是软件设计的一条重要原则。

正常情况下，软件应用期 ( 需要维护的时期 ) 远超实现期，所以，降低维护成本比降低实现成本更重要。

56 、D
[ 解析 ] 本题考查软件工程 ( 用户界面设计 ) 基础知识。

影响软件响应速度的因素有多项，计算机和软件处理事务的速度显然是重要的一项，但处理优先级的安排也是有影响的。 如果响应用户要求的优先级不高， 计算机快速处理自己的要求后， 没有立即将结果返回给自己， 又转去处理其他用户的要求， 那么响应速度也是慢的。

用户对常用操作的习惯很重要，此时他们不大会去查看操作说明书。如果常用的某个操作不符合用户习惯， 用户就会埋怨。 如果按习惯操作得不到效果， 甚至产生其他非预料的后果，那用户就会骂软件，甚至卸载该软件了。

在 Windows 系统中，为实现忙光标显示 ( 此时同时再做处理 ) ，需要在处理结束后取消忙光标，因此，需要采用进程内的并行机制，需要采用多线程编程方法。

系统对用户点击鼠标的响应时间预计在秒级 ( 例如 1 秒是正常的 ) 。用户对系统显示的反应也需要 1 秒时间。但用户拖动鼠标来移动对象时，实际上系统需要连续很多次做响应动作， 每次的响应时间应该在 0.1 秒左右， 否则用户不能感到对象在跟着鼠标而移动。 0.1 秒也称为感知 “瞬间 ”。

58 、D
[ 解析 ] 本题考查数据库关系运算方面的基础知识。

自然连接是一种特殊的等值连接，它要求两个关系中进行比较的分量必须是相同的属性组， 并且在结果集中将重复属性列去掉。 一般连接是从关系的水平方向运算， 而自然连接不仅要从关系的水平方向， 还要从关系的垂直方向运算。 因为自然连接要去掉重复属性， 如果没有重复属性，那么自然连接就转化为笛卡儿积。题中表 1 和表 2 具有相同的属性课程号，进行等值连接后，去掉重复属性列得到表 3。

若关系中的某一属性或属性组的值能唯一的标识一个元组，则称该属性或属性组为主键。从表 3 可见 “课程号、学生号 ”才能唯一决定表中的每一行，因此 “课程号、学生号 ”是表 3 的主键。

59 、C
[ 解析 ] 本题考查数据库 E-R 模型方面的基本概念。

根据题意，若一名职工仅属于一个部门，一个部门有多名职工，意味着部门 DEP 和职工 EMP 实体集之间是一对多的联系，记为 1:n 。一个职工可以参加多个项目，一个项目可以由多个职工参加，那么意味着 EMP与 PROJ 之间的联系类型为多对多的联系记为 m:n 。

60 、C 
61 、 A
62 、B
[ 解析 ] 本题考查对 SQL 语言的掌握程度。

根据题意，查询不同部门中担任 “项目主管 ”的职工的平均薪资，需要先按 “部门名 ”进行分组，然后再按条件职位 =' 项目主管 ' 进行选取，因此正确的 SELECT 语句如下：

SELECT 部门名 ,AVG( 薪资 ) AS 平均薪资
FROM EMP
GROUP BY 部门名
HAVING 职位 =' 项目主管 '

第 3 小题正确的答案是选项 B，因为插入语句的基本格式如下：
INSERT INTO 基本表名 ( 字段名 [, 字段名 ]...)
VALUES( 常量 [, 常量 ]...); 查询语句

从上可见，选项 C 和 D 显然是不正确的。选项 A 也是不正确的，因为按照 SELECT 语句的语法，字符串插入时，需要用单引号括起，可在选项 A 中“黄晓华 ”和“研发部 ”明显是字符串，但是却没有用单引号括起。

63 、D
[ 解析 ] 本题考查数学应用 ( 排列组合 ) 基本能力。

当 n=3 时，除 3 位全 0 或全 1 外，其他情况都是不含连续 3 位数字相同，因此F(n)=8-2=6 。当 n=4 时，除 0001 、1000 、0000 、1110 、0111 、 1111 外，其他情况都不含连续 3 位数字相同，因此 F(n)=16-6=10 。
供选答案 A、B、C、D 中，对于 n=1 ～4，F(n) 的值如下：
| F(n) | A    | B    | C    | D    |
| ---- | ---- | ---- | ---- | ---- |
| n=1  | 2    | 2    |      |      |
| n=2  | 4    | 4    | 4    |      |
| n=3  | 6    | 8    | 10   | 6    |
| n=4  | 8    | 14   | 12   | 10   |

因此，可以选出公式 D 是正确的。

当 n=5 时，除 000** 、1000* 、01000 、11000 ； 111** 、0111* 、00111 、10111外，其他情况都是不含连续 3 位数字相同，因此， F(n)=32-16=16 。

进一步计算表明， n≥3 时， n 位二进制数中不含连续三位数字相同的数中，末两位数字不同的数有 F(n-1) 个，末两位数字相同的数有 F(n-2) 个。

64 、A
[ 解析 ] 本题考查数学应用 ( 数据处理 ) 基本能力。

设 2012 年一季度和二季度的销售额分别是 a 和 b，则 2013 年一季度和二季度的销售额增加量分别是 0.04a 和 0.06b 。根据己知条件， 0.04a=0.06b ，即 a=1.5b ，因此，2013 年 上 半 年 的 销 售 额 比 2012 年 同 期 增 加 的 比 例 为(0.04a+0.06b)/(a+b)=0.04.8=4.8% 

65 、B
[ 解析 ] 本题考查数学应用 ( 线性方程组求解 ) 基本能力。

设计算期望时间的三个权分别为 a、b、c ，其中 a+b+c=1 ，即期望时间 =a* 乐观估计 +b* 最可能估计 +c* 悲观估计由题中的项目 1 和 2 可知： a+3b+11c=4 ，a+1.5b+14c=3.5 ，由于 a+b+c=1 ，所以 a=1/6 ，b=4/6 ，c=1/6 。从而，项目 3 的期望时间为 3/6+6.25*4/6+11/6=6.5 。

66 、A
[ 解析 ] 本题考查 Internet 应用中网页访问的相关问题。

若出现 IP 地址设臵错误或默认网关设臵错误， 会导致不能访问 Internet ，访问不到页面，不会出现页面中出现乱码的情况。若 DNS 服务器设臵错误，要么采用域名访问，结果是访问不到页面；要么采用 IP 地址访问，都不会有页面中出现乱码的情况。

67 、C
[ 解析 ] 本题考查 Windows 的网络命令。

```net view``` 命令用于显示计算机共享资源列表，带选项使用本命令显示前域或工作组
计算机列表。

```nbtstat ```显示基于 TCP/IP 的 NetBIOS(NetBT) 协议统计资料、本地计算机和远程
计算机的 NetBIOS 名称表和 NetBIOS 名称缓存。 nbtstat-r 显示 NetBIOS 名称解析统
计资料。

```netstat``` 是控制台命令，是一个监控 TCP/IP 网络的非常有用的工具，它可以显示路
由表、实际的网络连接以及每一个网络接口设备的状态信息。 netstat 用于显示与 IP 、TCP、
UDP 和 ICMP 协议相关的统计数据，一般用于检验本机各端口的网络连接情况。

```nslookup ```是一个监测网络中 DNS服务器是否能正确实现域名解析的命令行工具。
根据图示信息，答案为 C。

68 、C
[ 解析 ] 本题考查 HTML 的基础知识。

在 HTML 中，＜ u＞＜ /u ＞标记定义在页面中显示文字为带下划线样式，＜ i ＞＜ /i ＞标记定义在页面中显示文字为斜体字样式 , ＜b＞＜ /b ＞标记定义在页面中显示文字为加粗样式。＜ pre ＞＜ /pre ＞标记的作用是可定义预格式化的文本。被包围在 pre 标记中的文本通常会保留空格和换行符，而文本也会呈现为等宽字体。 

69 、 B
70 、A
[ 解析 ] 在 TCP/IP 协议栈中， ARP 协议的作用是由 IP 地址查找对应的 MAC地址， RARP
协议的作用正好相反，是由 MAC地址查找对应的 IP 地址。

71 、C
[ 解析 ] 处理机做调度工作时，操作系统调度的软件基本单位是进程或线程。

72 、D
[ 解析 ] 存取系统的秘密途径称为后门。

73 、B
[ 解析 ] 低层的类 ( 也称子类或派生类 ) 从高层类 ( 也称为超类或基类 ) 中继承了状态和行为。

74 、A
[ 解析 ] 电子商务非常类似于因特网上的市场。

75 、C
[ 解析 ] 大数据是增长得非常大的数据集，以至用现有的数据库管理工具也难以奏效