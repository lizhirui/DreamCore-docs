该处理器是一款RISC-V乱序超标量核，该处理核具有以下特性：

* 指令集为RV32IM
* 取指宽度为4
* 译码宽度为4
* 重命名宽度为4
* 寄存器读取宽度为4
* 发射宽度为2
* 写回宽度为8
* 退休宽度为4
* 支持64项ROB
* 支持256项Checkpoint
* 拥有GShare+Local混合预测器以及256项返回栈，同时具有面向call型和普通非条件分支指令的地址预测支持
* 支持16项Store Buffer
* 带有一个1MB的支持并行指令Fetch和数据Read/Write的TCM
* 带有CLINT及UART Controller