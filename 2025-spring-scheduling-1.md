# 2025年春夏季开源操作系统训练营：第一阶段

- [OS 导学视频](https://opencamp.cn/os2edu/camp/2025spring/stage/0?tab=video)
- [第一阶段学习：Rustlings Rust编程教程](https://classroom.github.com/a/S8vP0lDr)
- Online Ranking （训练营在线排行榜）
  - [第一阶段排行：Rust Lang](https://opencamp.cn/os2edu/camp/2025spring/stage/1?tab=rank)

- [常见问题解答](./QA.md)
- [Learning Resource](./relatedinfo.md) (学习资源汇总)

欢迎在校学生/工程师在2025年春季参加清华大学、阿图教育等共同举办的**2025年春夏季开源操作系统训练营**活动（2025.3.30~2025.6.22）。训练营结束后，表现突出的同学将获得训练营优秀证书，部分优秀同学将得到前往**清华科技园、泉城实验室线下实习**的机会。鼓励同学继续以开源社区的方式参与到企业/科研院所的操作系统实习/实践/工作/学习等相关的活动。

## 目标：

**培养具有开源思想的合作者，搭建开源合作平台。**

**探索把现代系统语言Rust和灵活开放的系统结构RISC-V带入到操作系统的架构与设计的创新中来，思考未来的操作系统应该是什么样。**

## 宗旨：

**希望本活动的组织，能为操作系统爱好者提供一个活跃的开源社区环境，为对Rust、RISC-V和操作系统感兴趣的人士营造一个平等的学习与交流空间，吸引更多对操作系统感兴趣的人士参与。**

## 相关信息：

- [参加往届 OS 训练营学生的 Blog](https://rcore-os.github.io/blog/)，鼓励参加2025 OS训练营的同学把自己在学习过程中的感悟/收获等写成blog，生成pr，并提交到 <https://github.com/rcore-os/blog> 上，让更多人看到你的进步！**提交博客pr是第二、三、四阶段的必要要求**。
- **注意** 为及时了解和指导同学的学习和实践情况并推动学生相互帮助，鼓励学生把每周学习实践的过程记录（Markdown格式）放在github上自己的公开repo中。可参见[参考实例](https://github.com/GCYYfun/DailySchedule)和[2020年每日学习汇总](https://github.com/rcore-os/rCore-Tutorial/issues/18 ) 。请参加实习的同学把记录每天的进展的git repo网址 更新到[2025年OS训练营同学的每日学习情况汇总](https://github.com/LearningOS/rust-based-os-comp2025/issues/1) 中。要求每位同学在自己的git repo中记录自己的每周进展，其他同学也可以参考学习。
- **注意** 常见问题详见 [训练营常见问题](https://docs.qq.com/doc/DWFV2eWdaZktvaWVo)，如果有问题可以在 [问答论坛](https://opencamp.cn/os2edu/bbs) 和微信群中进行提问。


# 2025春夏季开源操作系统训练营第一阶段环境配置与学习资料

前提条件：要求有基本数据结构，算法基础，相对了解或熟悉C语言等编程.

## 自学基础知识

   - [阅读书籍/课程/视频等资源汇总](https://github.com/rcore-os/rCore/wiki/study-resource-of-system-programming-in-RUST)
   - 推荐：[Rust语言圣经(Rust教程 Rust Course和配套练习)](https://course.rs/)
   - 推荐：[半小时快速了解Rust](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)
   - 推荐：[Rust速查表（cheatsheet）](https://cheats.rs/) 该项目不仅提供了基础的语法速查，还有执行顺序详解和编写时需要关注的注意事项。项目还包含了示例代码（EX）、书籍（BK）、标准（STD）等相关资料的扩展。
   - 推荐：[清华计算机系大一学生2022暑期课程：Rust程序设计训练（有课程视频）](https://lab.cs.tsinghua.edu.cn/rust/)

## 课程实验: Rustlings 训练

   - [点我创建课程实验仓库](https://classroom.github.com/a/S8vP0lDr)，采用Github Classroom模式的Rustling小练习，点击上述链接，形成自己的练习用repo。请记住您的 github 仓库名称，格式一般为 `LearningOS/2025s-rcore-${YourGithubName}`。

   - 要求：**必须完成** 。完成所有练习后，将本地修改提交到上一步创建的 git 仓库上，CI 会进行自动评测。要求小练习全部通过GithubClassroom的CI自动评测。

   - [学习系列视频：Rust中文社群线上学习室--通过 Rustlings 学 Rust](https://space.bilibili.com/24917186/video)

### 实验环境配置和快速上手

   1. 在网络浏览器中用自己的 github id 登录 github.com。

   2. 接收 [Rust-lang Lab Test based on Rustlings 的github classroom在线邀请](https://classroom.github.com/a/S8vP0lDr)  ，根据提示一路选择OK即可。

   3. 完成第二步后，你的rustings实验练习 的 github repository 会被自动建立好，点击此github repository的链接，就可看到你要完成的实验了。

   4. 请参考您的仓库中的 README（示例[README](https://github.com/LearningOS/rustling-classroom-2025s-rustling-25S-template/blob/main/README.md)）开始进行 rustlings 的环境配置和实验。

   5. 提交。当做完部分或所有练习之后，执行 ``git add; git commit -m "$Your commit message"; git push`` 命令，把更新提交到GithubClassroom的CI进行自动评测。你可以在github仓库页面的actions页面，看到你的CI提交结果，或者在排行榜上面查看自己的评分。
   
   6. 上述步骤有任何问题都可以找助教。


## 自学编程（可选，非必须要求）

   - （Option）[32 Rust Quizes](https://dtolnay.github.io/rust-quiz/1)

     - 要求：小练习全部通过。（**非必须完成**）

   - （Option）[exercisms.io 快速练习(88+道题目的中文详细描述)](http://llever.com/exercism-rust-zh/index.html)

     - 要求：大部分练习会做或能读懂。（**非必须完成**）
     - [exercism.io官方站点](https://exercism.io/)

### 自学Risc-v系统结构（大约2~7天）

**第二阶段**的操作系统的课程实验基于 RISC-V 架构。推荐同学在完成 Rust 语言的基本学习后，参考下面资料，预习 Risc-v 架构的内容。

前提条件：要求有基本计算机组成原理，计算机系统结构基础。

阅读《计算机组成与设计（RISC-V版）》第一、二章，可以在整体结构上对 RISC-V 体系建立基本认知。再进行后面的学习比较有效果。

#### 自学材料和练习要求:

1. 阅读书籍和在线课程

   - 自学[PPT for RISC-V特权指令级架构](https://content.riscv.org/wp-content/uploads/2018/05/riscv-privileged-BCN.v7-2.pdf)
   - 自学[RISC-V手册：一本开源指令集的指南](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf) 重点是第10章
   - （Option）自学[RISC-V特权指令级规范](https://riscv.org/technical/specifications/) 重点是与OS相关的特权硬件访问的规范内容（Privileged Spec）
   - （Option）自学[RISC-V汇编手册](https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md)
   - （Option）[计算机组成与设计：RISC-V 教材](https://item.jd.com/12887758.html) 这是完整的课程教材，不要求全部看完，请根据自己的需求选择。
   - （Option）[计算机组成与设计：RISC-V 浙大在线课程](http://www.icourse163.org/course/ZJU-1452997167) 这是完整的一门课，不要求全部看完，请根据自己的需求选择。

2. 其他参考学习信息

   - （Option）[Berkeley CS61C: Great Ideas in Computer Architecture (Machine Structures)](http://www-inst.eecs.berkeley.edu/~cs61c/sp18/)

   > Option的含义是：如果有足够的时间建议看看，否则在后续要用到时或需要查询进一步信息时再查阅这些内容。

3. 通过要求

   - 掌握RUST编程，理解RISC-V与OS相关的硬件特性（中断，异常，系统调用，寄存器，特权级，MMU...）。

One More Thing：当你看到这，感觉第一阶段还没开始，还在想下一步要干啥时，我们的建议是：**Just Do It NOW!**
