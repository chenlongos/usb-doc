# Rust 编写 ArceOS USB驱动


1. 完成 PCIe 主桥的初始化工作，使得 PCIe 主桥可以正常工作


2. PCIe 主桥枚举连接到总线上的设备，发现 USB 3.0 主机控制器设备

3. 对发现的USB3.0主机控制器分配内存空间

4. USB 3.0 主机控制器的初始化，使得主机控制器可以正常工作
 
5. USB主机控制器枚举和检测插入的 USB 设备

6. 创建适当的数据结构和数据通路来管理和处理 USB 设备的连接和通信
   
7. 实现具体的USB设备驱动程序

8. 完成技术需求，撰写技术文档

