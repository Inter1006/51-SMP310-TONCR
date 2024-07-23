### 51-SMP310
SMP310针式打印机头51单片机驱动程序<br />
这个fork存在的目的是为了模拟NCR3125笔计算机的附加组件:一个针式打印机，从而避免模拟的机器在启动过程中因检测不到打印机而陷入死循环<br />

## 📥如何使用
void printerStitch(unsigned char str)   直接控制上部8针<br />
void printChar(unsigned char chr)       打印一个字符（自己画的字体，包括换行，@替换为黑方块）<br />
printStr(char *str)                     打印一个字符串<br />

## ℹ关于
四年前的老老老屑作，大概不会继续做支持！<br />
特别感谢351Workshop的原项目！！！

<br /><br /><br /><br />
Copyright 351Workshop 2022-2024
Modified by Inter1006
