
# 2024年秋冬季开源操作系统训练营：第三阶段

## [项目基础阶段 - 组件化操作系统](https://opencamp.cn/os2edu/camp/2024fall/stage/3)

- [新闻与纪要](./news.md)
- [常见问题解答](./QA.md)
- [Learning Resource](./relatedinfo.md) (训练营学习资源)
- [直播教室](https://opencamp.cn/os2edu/camp/2024fall/stage/3)
- [视频回放与课件](https://opencamp.cn/os2edu/camp/2024fall/stage/3?tab=video)

## 第三阶段主要安排

### 课程内容

第三阶段是第四阶段的准备阶段，主要为大家介绍组件化操作系统的基本思想与结构。

项目核心 project：[ArceOS 组件化内核](https://github.com/arceos-org/)

核心思想：Combining Various Operating Systems Using OS-Reusable Components

在三周时间内为大家带来9次线上课程，介绍组件化 unikernel、宏内核与 hypervisor 三部分内容。


### 参考资料

#### 课程背景

- [基于泛型独立组件构建各种领域OS](https://github.com/chyyuu/thoughts/blob/main/tangram-oskits.md)
- [rCore Tutorial Kernel组件化初步探索](https://github.com/rcore-os/rCore-Tutorial-in-single-workspace)
- [ArceOS: unikernel架构的组件化操作系统内核的初步探索](https://github.com/LearningOS/os-lectures/blob/master/oslabs/biglabs-list-2023.md)
- [贾越凯博士论文的第四章:“unikernel架构ArceOS内核的设计与实现”](https://github.com/rcore-os/arceos/wiki/docs/main-20240524-62-91.pdf)

#### 课程参考
- ArceOS 相关项目地址
  - unikernel 项目主仓库 [arceos-org/arceos](https://github.com/arceos-org/arceos)
  - 宏内核项目主仓库 [arceos-org/starry-next](https://github.com/arceos-org/starry-next)
  - hypervisor项目主仓库 [arceos-hypervisor/arceos-umhv](https://github.com/arceos-hypervisor/arceos-umhv/)
  - 基于 ArceOS unikernel 实现的宏内核 [Starry-OS](https://github.com/Starry-OS/), 
    - 2024年全国大学生计算机系统能力大赛-操作系统设计赛(全国)-OS功能挑战赛道 一等奖作品
- 往届参考书
  - [简明 ArceOS Tutorial Book](https://rcore-os.cn/arceos-tutorial-book/) (部分代码结构已更新，仅供参考)
- 往届课程视频&课件
  - ArceOS unikernel 相关
    - [2024春夏季开源操作系统训练营-项目一:ArceOS 单内核 Unikernel](https://opencamp.cn/os2edu/camp/2024spring/stage/3?tab=video)
    - [2023秋冬季开源操作系统训练营-项目一:ArceOS 单内核 Unikernel](https://opencamp.cn/os2edu/camp/2023fall/stage/2?tab=video)
    - [2023春夏季开源操作系统训练营：第三阶段 ArceOS](https://opencamp.cn/os2edu/camp/2023spring/stage/2?tab=video)
  - ArceOS 宏内核相关
    - [2024春夏季开源操作系统训练营-项目二:ArceOS 宏内核](https://opencamp.cn/os2edu/camp/2024spring/stage/4?tab=video)
    - [2023秋冬季开源操作系统训练营-项目二:ArceOS 宏内核](https://opencamp.cn/os2edu/camp/2023fall/stage/3?tab=video)
  - ArceOS hypervisor 相关
    - [2024春夏季开源操作系统训练营-项目四:Hypervisor虚拟化](https://opencamp.cn/os2edu/camp/2024spring/stage/6?tab=video)
    - [2023秋冬季开源操作系统训练营-项目四:Hypervisor虚拟化](https://opencamp.cn/os2edu/camp/2023fall/stage/5?tab=video)
    - [视频合集·从零开始用 Rust 语言实现一个 x86 hypervisor](https://space.bilibili.com/3493135044840333/channel/collectiondetail?sid=1118442&spm_id_from=333.788.0.0)
        - 对应课件：[RVM-Tutorial/wiki](https://github.com/equation314/RVM-Tutorial/wiki)
  
- 参考书
  - [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)
  - [深入了解计算机系统](https://hansimov.gitbook.io/csapp/)
  - [RISC-V Reader中文版](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf)
  - [rCore Tutorial Book v3](https://learningos.github.io/rCore-Tutorial-Book-v3/)


### 总体学习要求和成绩考核方式

#### 关于晋级问题

第三阶段是第四阶段的准备阶段，原则上不淘汰，但仍需要在12月1日之前提交本阶段的总结 Blog，按要求提交即可晋级。

#### 关于实验题目
三阶段所有实验，目的都是帮助大家学习和巩固，同学们自行决定是否去做，不是晋级条件。
包括两类实验：
1. 每节课程都附带课后实验，对于这类实验，鼓励同学们自由讨论解决办法。完成情况不做考查。
2. 根据课程进度会发布挑战性的实验题目，要求独立完成，参与者按照完成顺序排名。
    排名仅作为结营评优参考。具体题目与规则到时公布。


**注:** 第四阶段各个选题方向的导师可能会根据第三阶段的完成情况为大家分配项目任务，请有意选择第四阶段相关选题的同学着重完成第三阶段的相关内容，希望大家通过第三阶段的学习可以为第四阶段的项目实操打下一个好的基础。


### 训练营剩余各阶段起止时间
* 第三阶段（3周）2024/11/11 ~ 2024/11/29 	组件化操作系统 
* 第四阶段（3周）2024/12/2 ~ 2024/12/22	项目实习，4个选题方向
    * [ArceOS单内核Unikernel](https://opencamp.cn/os2edu/camp/2024fall/stage/4)
    * [ArceOS宏内核](https://opencamp.cn/os2edu/camp/2024fall/stage/5)
    * [Hypervisor虚拟化](https://opencamp.cn/os2edu/camp/2024fall/stage/6)
    * [基于协程异步机制的操作系统/驱动](https://opencamp.cn/os2edu/camp/2024fall/stage/7)


### 关于学习记录与 总结 Blog

每个阶段结束后需要写总结报告，第三阶段需要完成本阶段的 Blog,请参照[2024 秋冬季训练营常见问题](https://opencamp.cn/os2edu/bbs/1382)第19问。

- [学习记录的标杆1](https://github.com/LearningOS/record)，浙江大学本科生徐文浩的2020开源操作系统训练营的过程记录，是大家学习的榜样，供大家学习参考。
- [学习记录的标杆2](https://kiprey.github.io/tags/uCore/)：湖南大学本科生肖政杭的自学ucore for x86的过程记录，是大家学习的榜样，供大家学习参考。

One More Thing：当你看到这，还在想下一步要干啥时，我们的建议是：**Just Do It NOW!**

同时，欢迎大家参与 rCore 组织的 [discussions](https://github.com/orgs/rcore-os/discussions) 中的各种os模块化相关的探索性质的小项目
