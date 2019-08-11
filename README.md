# FreePLC
FreePLC是一款基于Beremiz的开放式中小型PLC方案，主要针对以下几种应用场景设计：
1. 设计生产PLC模块 
2. 为产品提供二次编程的功能 

能为用户提供如下服务：
1. 开放的PC端编译环境，支持IEC61131多种工业编程语言
2. 开放的底层代码，用户可以将自己的算法无缝整合
3. 完整的参考模板，即使没有嵌入式软件开发经验也可以使用默认模板生产PLC模块
4. 用户自定义外设接口，可以根据自身需要定制PLC为专用控制器
5. 通讯接口使用[OpenModbus](https://github.com/FreePLC/OpenModbus)可外接Modbus从站设备

方案分为两部分内容：

1. PLC编译环境：[FreePLC IDE](https://github.com/FreePLC/FreePLC_IDE)，由python编写，提供IEC61131多种语言开发环境
2. PLC硬件模块：主芯片基于NXP KV44系列，硬件模块提供参考原理及PCB文件，固件分为3个部分：

    (1). [FreePLC_Bootloader](https://github.com/FreePLC/FreePLC_Bootloader)(开源)
    (2). FreePLC_Rts(固化到芯片)
    (3). [FreePLC_UserCustome](https://github.com/FreePLC/FreePLC_UserCustome)(开源)


###########################################################################################

写在最后：
    希望能通过本方案帮助到更多的人结识更多的朋友，支持国产PLC振兴，下一步计划选择国产M23内核
    由于该方案通过业余时间支持，有许多不足的地方，大家一起逐步完善，为了能坚持并继续做下去Rts部分代码并未开源，希望大家理解

###########################################################################################
