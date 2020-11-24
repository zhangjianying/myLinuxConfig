# myLinuxConfig
基于linux上的杂七杂八配置文件





## 内核

### xanmod

地址: https://www.xanmod.org/

Features

* Each CPU has its own runqueue.
* NORMAL runqueue is a linked list of sched_entities (instead of RB-Tree).
* RT and other runqueues are just the same as the CFS's.
* A task gets preempted when any task in the runqueue has a higher HRRN.
* Wake up tasks preempt currently running tasks if its HRRN value is higher.
* Designed for desktop usage since it is about responsiveness.



> 已经按官网在deepin v20 上升级内核成功.比较稳定.但是5.9内核不适配 VMWEARE.因此需要使用VMWARE的时候需要重启到5.4内核

