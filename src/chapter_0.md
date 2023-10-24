# 学习指南

本次实习项目共有三个阶段，前两个阶段各包含五个实验内容（实验开始前，请先阅读每阶段的相关知识），第三阶段为自己动手实践环节

* 第一阶段主要了解树莓派以及如何在树莓派上运行ArceOS
  
  * 实验一为编译环境，消耗时间较久，大概需要几个小时
  
  * 实验二、三为在模拟环境运行ArceOS，每个实验大概需要半小时左右
 
  * 实验四、五为在树莓派主板上运行ArceOS，每个实验大概需要一小时左右

* 第二阶段主要用Rust写树莓派串口驱动，共包含五个实验内容

  * 实验一为驱动 UART0 串口，大概需要一个小时左右
    
  * 实验二为用串口驱动小车，大概需要一个小时左右
 
  * 实验三为驱动另一串口，大概需要二到三个小时左右
 
  * 实验四与实验三类似
 
  * 实验五为通过初始串口发出指令，由另一串口驱动小车，大概需要三到四个小时

* 第三阶段为用Rust写树莓派USB驱动，可以使用USB来驱动小车，可以分为以下几步

  *  USB初始化，可以读取USB设备ID
 
  *  支持USB设备中断和定时器功能
 
  *  实现与USB设备进行通信的协议
 
  *  设计实现数据处理/指令发送模块
 
  *  完成技术需求，撰写技术总结文档
   