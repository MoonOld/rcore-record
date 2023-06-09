# rcore-record
keep the record

## 4月4日
前几天一直有点事情，从今天开始吧。  
今天主要复习了一遍rustlings，然后布置好了环境。  
rustlings大概完成了一半左右，明天大概会出去和朋友玩，所以明天应该够呛能完成。  
不得不说再次完成rustlings的过程还是碰到了一些问题，对rust只能说有一个简单的了解，有许多方面还是有着不足的。  

## 4月5日
今天完成了rustlings，把一些比较重要的问题记录下来了。  
计划明天把这些问题写成博客详细学习一下，然后继续学习RISC-V指令集。

## 4月7日
今天更新完了rustlings的一些疑问，也翻阅了不少rust源码，在设计上是有更深一步的认识的。[博客链接](https://moonold.github.io/posts/lab/rcore/rustlings/)  

然后开始阅读了[RISC-V手册](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf)，里面讲的东西实在涉略过广，我个人的指令集理解已经退化到了课内X86复杂指令设计都不太记得了，看得有些头昏脑胀。晚上勉强看完第二章RV32I，可能要考虑一下换资料或者尽可能读一些RISC-V本身的内容避免过度联想。

## 4月17日
不知不觉过了十天了，我忙着驾校、也写了点别的东西。看完了RISC-V手册正文，也搭好了环境，是时候出发了。

## 4月18日
今天遇到了一些问题，是Qemu版本过高和RustSBI不适配的问题，通过源码编译Qemu7.0的办法解决了，明天更新一下踩坑记录。

## 4月19日
今日又遇到了MacOS的自带grep带来的问题，已经提交过程于[Discussion](https://github.com/LearningOS/rust-based-os-comp2023/discussions/179).
今天把Ch1的代码基本看完了，并且做了注释，Ch2也快看完Tutorial了，要尽快整理一下产出。

## 4月20日
今天看完了Ch2代码，也看完了Slides，Tutorial中提出的sscratch内容改为系统栈顶的时机，应当是__restore过程中sret上一行，csrrw指令将原sp中系统栈写入sscratch。
今天把之前去拍的照片的图修完了，应该有更多时间去做rcore了。