---
typora-root-url: assets
---

![58442283930](/1584422839300-1584422841462.png)

##### 1.1

处理器 内存 输入/输出模块  系统总线
##### 1.2
用户可见寄存器：优先使用这些寄存器，可以使机器语言或者汇编语言的程序员减少对主存储器的访问次数。对高级语言而言，由优化编译器负责决定把哪些变量应该分配给主存储器。一些高级语言，如C语言，允许程序言建议编译器把哪些变量保存在寄存器中。
控制和状态寄存器：用以控制处理器的操作，且主要被具有特权的操作系统例程使用，以控制程序的执行。
##### 1.3 
![58442211059](/1584422898647-1584422899926.png)
取到的指令放在处理器的指令寄存器中。指令中包括确定处理器将要执行处理将要执行的操作的位，处理器解释指令并执行对应的操作。
4类： 
- 处理器-存储器
- 处理器 -I/O模块
- 数据处理
- 控制 
##### 1.4 
所有计算机都提供允许其他模块（I/O、存储器）中断处理器正常处理过程的机制
##### 1.5 
一、定义中断优先级   二、队列结构，先进先出，不得插队
##### 1.6
价格、容量、访问时间
![58442213218](/1584423136632-1584423137628.png)

##### 1.7
比主存小而快的存储器，用以协调主存跟处理器，作为最近存储地址的缓冲区

![58442287269](/1584422872699-1584422873940.png)

* * *
查找本地备份（以槽为存储单位），没有则查主存。
查找过程中就涉及到“映射函数”与“置换算法（LRU）”=》命中率-》空间局部性

##### 1.8
- 多核计算机指将两个或多个处理器组装在同一块硅上的计算器。每个核上通常有一块独立处理器。
- ![58442264952](/1584422649520.png)

##### 1.9 
空间局部性是指最近被访问的元素的周围的元素在不久的将来可能会被访问。临时局部性（即时间局部性）是指最近被访问的元素在不久的将来可能会被再次访问。 


##### 1.10
空间局部性是指最近被访问的元素的周围的元素在不久的将来可能会被访问。临时局部性（即时间局部性）是指最近被访问的元素在不久的将来可能会被再次访问。 