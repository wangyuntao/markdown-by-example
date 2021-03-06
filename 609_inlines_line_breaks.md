# 换行

连续多行文本（中间没有空行）的实际显示效果并不是多行，而是以空格分隔各小行的一个大行，这叫做软换行。

如果想要将其显示成多行，可以在行尾（最后一行除外）加两个及其以上的空格，或加一个反斜杠（\\），这样多行文本就可以正常显示，这叫做硬换行。

软换行的具体写法：

> 第一行  
> 第二行  
> 第三行

软换行的实际效果：

> 第一行
> 第二行
> 第三行

硬换行的具体写法：

> 第一行（后面还有两个空格）  
> 第二行\\  
> 第三行

硬换行的实际效果：

> 第一行（后面还有两个空格）  
> 第二行\
> 第三行

注意事项：

硬换行要求行尾有两个及其以上的空格。

如果行尾只有一个空格或者没有空格都是软换行。

一行结尾和下一行开始之间的空格在实际显示中会被替换为一个空格或一个换行符。

硬换行的语法只适用于[inline](300_blocks_and_inlines.md)形式的多行文字（除了inline的代码），而不适用于[block](300_blocks_and_inlines.md)形式的多行文字。