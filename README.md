# 洗衣机控制程序与模拟

#### 介绍
基于89C52单片机的洗衣机控制程序与Proteus模拟。

基本功能：
模式一：标准洗涤
模式二：快速洗涤
模式三：单独启动模式一、二中的某一阶段

--szz2021.09.06--
此程序目前存在亿点点bug，由于按键检测时间过短，导致仿真时无法准确实现对按键的检测。
修改建议：在按键检测时加一个延时和锁定（即不抬起按键便不继续执行程序），但我懒得改了┓( ´∀` )┏。

--szz2021.09.07--
改了上次的bug，并增加了计时器。