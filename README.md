# nmls-os-kernel
------
## 只是一个简单的内核小玩具
## 支持：
* 物理内存管理
* 分页管理
* 虚拟化
* 内核级多线程
* 内核调试函数库（内核扩展使用）
* 一小部分基础驱动程序
* 中断系统
## 不支持：
* 用户态
* 大部分驱动（键盘鼠标图形驱动等）
* 硬中断控制
* 文件系统与磁盘管理
## 简单使用：
在linux环境下确保安装qemu gcc nasm （注意要为qemu定义符号链接 这样可以在makefile脚本中直接使用qemu打开模拟器）
制作一个名为floppy.img(也可以修改makefile脚本自定义名称)
运行命令 make 进行编译后 再运行 make run 开启qemu虚拟机并装载运行kernel
## 进一步计划：
期末时间充裕时再进行此项目的扩展（图形驱动 软中断库 基础c语言言库 用户态等）
------
