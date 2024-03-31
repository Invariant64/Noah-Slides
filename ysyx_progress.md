# ysyx 进度汇报

ysyx_23060207-雷昊川

----

### 预学习答辩 --> 2024-03-03

* NEMU
  * 实现部分指令, 使cpu-test中的测试通过(涉及klib的除外)
  * 实现klib中string相关函数和sprintf
    * cpu-test中剩余的测试通过
  * 实现iringbuf, mtrace, ftrace
* NPC
  * 学习scala, chisel语法, 配置相关环境
  * 使用chisel实现 "最简单的处理器"
    * addi, ebreak
    * 部分模块测试

----

### 2024-03-03 --> 2024-03-17

* NEMU
  * 修复bug
* NPC
  * NPC与NEMU的差分测试
  * NPC的基础设施(功能同NEMU)
    * sdb
    * trace
  * 实现部分指令
    * 所有cpu-test中的测试和差分测试通过

----

### 2024-03-17 --> 2024-03-31

* NEMU
  * PA2.3
    * 实现IOE, 运行演示程序
  * PA3.1
  * PA4.1
    * 启动RT-Thread
* NPC
  * 实现IOE 运行红白机模拟器(VGA)




