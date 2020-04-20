## 20.4.17 
命令提示符：
> + 在命令行里 cd + 几个首字母 再按下 tab 键就可以自动补全
> + 返回上一级目录：cd + .. 
> + 退回到最根目录：cd + / 
> + 清屏：clear 

+ Java语言的跨平台性：指的是Java不区分操作系统。
To be specific, 任何语言写成的软件都需要运行在操作系统上，然而用Java编写的软件可以运行在任何的操作系统上，这就成为跨平台特性。 
> 
+ JVM：Java Virtual Machine，Java的虚拟机，是Java语言可以在不同的操作系统上运行，起到解释翻译的作业。
+ JRE：Java Runtime Environment，是Java运行时的环境，里面包括JVM和运行所需要的核心类库。（运行）
+ JDK：Java Development Kit，Java程序开发的工具包。（开发）
 
 Java源程序通过编译器变成了java字节码文件，然后再到JVM里面去运行。


> + javac + 文件名.java：将指定文件进行编译 
+ 编译过后就会生成一个 .class 结尾的文件
> + java + 文件名（不加后缀）：表示直接执行java文件，其实**真正运行的是那个编译之后的class后缀的文件**，但是此时不要写后缀，因为这里需要写的是类名称。

当Java源文件改变之后，就要重新进行编译，编译之后新的.class文件就会覆盖原来的.class文件。



