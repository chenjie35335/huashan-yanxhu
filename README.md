Huashan-yanxhu
=======================

这是一个Loongarch 32位标准指令集架构的乱序双发射CPU,将作为第九届龙芯杯的参赛作品。

## 预想架构

![alt text](image.png)

## Getting Started

目前只支持生成verilog代码，后续的功能会逐步添加，生成verilog的命令如下:
```bash
make verilog
```

## 开发计划

* **当前-3月15日** 
完成CPU设计实战所给样例的前20条指令以及额外的乘法和除法指令，以完成整体架构设计
* **3月15日-4月1日**
添加csr、同步进行访存接口的修改和分支预测
* **4月1日-4月15日**
添加cache、添加其他指令、接入chiplab和功能测试和性能测试
* **4月15日-5月1日**
接入TLB

* **5月1日-6月1日** 
仿真启动linux开始

* **6月1日-7月1日**
上板启动linux

* **7月1日-决赛**
外设+优化

## Reference

我们主要参考的样例CPU有

* 一生一芯计划CPU zhoushan

  [Zhoushan Core](https://github.com/OSCPU-Zhoushan/Zhoushan)

* 中科大本科生毕设 Zircon
