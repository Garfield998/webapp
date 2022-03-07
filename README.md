### ex1

**格式化输出信息：**

- %s 代表string字符串
- %d 有符号整数(十进制)，帮助检验数字类型
- %f 浮点数字(用小数点符号)
- %r 不管什么都打印出来

**raw_input()在python3中不再使用**

**Git简单指令**

- git add .
- git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）
- git push -u origin master  （注：此操作目的是把本地仓库push到github上面，此步骤需要你输入帐号和密码）

### ex2

- close – 关闭文件。跟你编辑器的 文件->保存.. 一个意思
- read – 读取文件内容。你可以把结果赋给一个变量
- readline – 读取文本文件中的一行
- truncate – 清空文件，请小心使用该命令
- write(stuff) – 将 stuff 写入文件

#### 遇到的问题

1. **open打开文件用a+的方式，read的时候读取不到文件，打印为空**

   以 a+ 追加方式打开，则是因为光标被放在了文本末尾，无论是用哪种方式读取 read() 、readline() 或者 readlines() ，都是以当前光标所在的位置往下读，所以只能读到空字符。

   可以用seek(0, 0) 将光标移动到文档开头

### ex3
   面向对象程序设计（Object Oriented Programming，OOP）是一种计算机编程架构。OOP的一条基本原则是计算机程序由单个能够起到子程序作用的单元或对象组合而成。OOP达到了软件工程的三个主要目标：重用性、灵活性和扩展性。OOP=对象+类+继承+多态+消息，其中核心概念是类和对象。
#### split()

`str.split(str="", num=string.count(str))`

- str -- 分隔符，默认为所有的空字符，包括空格、换行(\n)、制表符(\t)等。
- num -- 分割次数。默认为 -1, 即分隔所有。

#### pop()

pop() 函数用于移除列表中的一个元素（默认最后一个元素），并且返回该元素的值。

`list.pop([index=-1])`

- index -- 可选参数，要移除列表元素的索引值，不能超过列表总长度，默认为 index=-1，删除最后一个列表值。

