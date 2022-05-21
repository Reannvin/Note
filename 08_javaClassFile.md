# 关于Java Class文件结构

首先要说明的一点是，Java并非唯一能将Java文件编译成Class文件的编译器，Jython，scala，Jruby和Groovy均可。

Class文件包含虚拟机指令，符号表，辅助信息。其中两种数据结构分别是表和无符号数。

类似于C++的Struct Classfile

struct Classfile{
  Fieldref fieldref;
  
}
