基于FPGA的四位二进制乘法器的设计

最后修改日期：2024/1/31

实验目的：
(1)熟练应用基于 FPGA 的数字系统设计方法;
(2)熟练使用 VerilogHDL 进行硬件描述;
(3)熟练进行功能仿真及硬件调试。
(4)重点:熟练应用基于 FPGA 的数字系统设计方法
(5)通过项目范例进行实践,对设计的每个环节进行练习,通过不断的实践达到熟练掌握的目的。

实验要求：
乘法器系统需求描述如下
1.用时序电路实现一个二进制正整数乘法器;
2.该乘法器使用二进制乘法算法进行乘法运算;
3.该系统可以进行两个 4 位二进制数的乘法运算,并给出计算结果
4.输人输出接口定义

用时序电路实现二进制正整数乘法器。

使用二进制乘法算法进行乘法运算：
该系统具有一下功能：

（a)两个4位的输入端口，输入乘数和被乘数:Q,R；
（b)一个8位输出端口，输出乘积:P；
（c) 一个系统级状态信号,DONE,表示一次乘法运算已经完成；
（d）一个控制信号，START，启动一次乘法运算；
（e)一个控制信号，RESET，启动系统复位。
