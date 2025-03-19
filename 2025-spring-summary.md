# 2025 年春夏季操作系统训练营信息汇总

## 时间表

总时间：2025 年 3 月 30 日～2025 年 6 月 22 日，共 12 周

- 第一阶段（2周）：2025/3/30～2025/4/13，讲授 Rust 编程语言 & Rustlings 强化训练 

- 第二阶段（3周）：2025/4/14～2025/5/4，讲授 rCore Tutorial OS 

- 第三阶段（3周）：2025/5/5～2025/5/25 ，讲授组件化操作系统 ArceOS 设计

- 第四阶段（4周）：2025/5/26～2025/6/22，项目实习，共有 3 个选题方向

## 前置准备

### 知识储备

建议同学们有一定的编程语言基础。如果从未接触过编程语言，直接上手 Rust 可能稍有复杂，可以考虑先学习 C 语言等内容，培养编程思维。



对于操作系统不需要额外的知识储备，我们将从零基础开始进行介绍。



### 配置准备

- 请保证您拥有一个 Github 账号，如果没有可以临时注册一个

- 请在训练营平台上完善自己的 Github 账号
  - 在训练营网站 https://opencamp.cn 上进行登陆
  - 点击右上角 `个人中心` 按钮，进入个人中心
  - 点击 `编辑个人信息`，或者访问https://opencamp.cn/my/edit，找到 `GithubName` 栏目，添加您的 Github 账号
- 开发环境最好是 Linux 环境，后续可能会上线 Github Classroom 支持

## 第一阶段学习

### 阶段介绍

本阶段是 Rust 编程语言学习，我们将在课堂上讲解 Rust 语言，并提供了 Rustlings 强化训练，帮助大家了解、学习 Rust 这一门新兴但热门的语言。



### 课程资料

- 课堂入口：https://opencamp.cn/os2edu/camp/2025spring/stage/1
  - `学习视频`可以查看每次课堂的回放录屏和相关的课程文件
  - `晋级榜单`可以查看自己的作业得分和当前所有人的晋级情况

- 学习资料：

  - 往年的训练营课程回放：https://opencamp.cn/os2edu/camp/2024fall/stage/1

  - 推荐：[Rust语言圣经(Rust教程 Rust Course和配套练习)](https://course.rs/)

  - 推荐：[半小时快速了解Rust](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)

  - 推荐：[Rust速查表（cheatsheet）](https://cheats.rs/) 该项目不仅提供了基础的语法速查，还有执行顺序详解和编写时需要关注的注意事项。项目还包含了示例代码（EX）、书籍（BK）、标准（STD）等相关资料的扩展。

  - 推荐：[清华计算机系大一学生2022暑期课程：Rust程序设计训练（有课程视频）](https://lab.cs.tsinghua.edu.cn/rust/)

  - 欢迎联系阿图教育，加入学习群和大家一起讨论

    ![img](https://opencamp.cn/_next/image?url=https%3A%2F%2Foss.opencamp.cn%2Ffile%2F20250314%2F20250314_534313.jpg&w=828&q=75)

- Rustlings 训练作业

  - 仓库创建链接：https://classroom.github.com/a/S8vP0lDr

  - 点击该链接，接受邀请之后即可创建一个属于你的 Rustlings 训练仓库

  - 在该仓库上进行提交，便会通过 CICD 来 评分并且同步在比赛平台的排行榜：https://opencamp.cn/os2edu/camp/2025spring/stage/1?tab=rank

  - 如何开始训练：参考[春夏季第一阶段公告](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/2025-spring-scheduling-1.md) 进行环境配置和训练

### 晋级条件

排行榜【晋级榜单链接】：https://opencamp.cn/os2edu/camp/2024fall/stage/1?tab=rank

1. 完成110道Rustling编程题，排行榜达到满分 110 分

2. 然后**将含本次训练营分数的自己的个人中心界面（ https://opencamp.cn/my ）截图发给群内阿图教育账号**，由老师拉进群。一个示例如下：

   ![img](https://ssl.cdn.maodouketang.com/FqPjreit1li_0LXjeL4ErHvqsHwX)

> 补充：**如果在个人中心没有找到训练营成绩**，请进入 https://opencamp.cn/my/edit 后，在 GithubName 一栏填写自己在 GitHub 的用户名。提交后，还需要在您的 Rustlings 重新产生一个新的提交，才能覆盖掉之前的成绩。

## 第二阶段学习

### 阶段介绍

本阶段开始我们将会讲授 rCore-Tutoril-OS。它是由清华大学开发的、使用 Rust 编写的教学用内核。我们将会从这个内核开始，一步步带领大家熟悉内核、了解内核，上手内核的开发过程。



### 课程资料

- 课堂入口：https://opencamp.cn/os2edu/camp/2025spring/stage/2
  - `学习视频`可以查看每次课堂的回放录屏和相关的课程文件
  - `晋级榜单`可以查看自己的作业得分和当前所有人的晋级情况
- rCore 训练
  - 仓库创建链接：https://classroom.github.com/a/pTgmDIG6
  - 点击该链接，接受邀请之后即可创建一个属于你的 rCore 训练仓库
  - 在该仓库上进行提交，便会通过 CICD 来 评分并且同步在比赛平台的排行榜：https://opencamp.cn/os2edu/camp/2025spring/stage/2?tab=rank
  - 请按照 [rCore 实验指导书](https://learningos.cn/rCore-Camp-Guide-2025S/)： 进行环境配置和实验。

- 学习资料：

  - 往年的训练营课程回放：https://opencamp.cn/os2edu/camp/2024fall/stage/2

  - rCore 实验指导书：https://learningos.cn/rCore-Camp-Guide-2025S/

    > 注意：https://rcore-os.cn/rCore-Tutorial-Book-v3/index.html 是一部更加详细的指导书，但它里面所用的内核版本以及作业内容不是本次训练营的目标。同学们可以参考该指导书进行扩展学习，但是代码和任务仍然以 https://learningos.cn/rCore-Camp-Guide-2025S 为准



### 晋级条件

晋级需要满足如下条件：

1. 完成全部5个实验，获得**满分500分**。需要完成的 5 个 rCore 实验分别在【3/4/5/6/8】5个章节的`chapterX 练习`部分，如第 3 章的练习位于 [这里](https://learningos.cn/rCore-Camp-Guide-2025S/chapter3/5exercise.html/)。必须按指导书【要求的文件名】添加实验报告后才会通过测试。
2. 提交学习博客PR。可以参考[参加往届 OS 训练营学生的 Blog](https://rcore-os.github.io/blog/)，鼓励参加2025 OS训练营的同学把自己在学习过程中的感悟/收获等写成blog，生成pr，并提交到 https://github.com/rcore-os/blog 上，让更多人看到你的进步！**提交博客pr是第二、三、四阶段的必要要求**。
3. 发送截图信息给老师（同第一阶段）



### 参考资料

进入第二阶段，之前的组队仍然可以继续，如果之前没有组队也欢迎这个阶段新建组队。第三阶段会根据项目实习导师要求，不同导师可能要求不同，届时不再以组队方式进行学习。

- 对于第一节课的学习，可以参考以下学习记录：https://mp.weixin.qq.com/s/hLsKow_Zj_NEuNXZhCe5Vg

- 对于第二节课的学习，可以参考：https://mp.weixin.qq.com/s/RbT6Yt88EsTglkheHEUgIQ
- 对于整个阶段的学习记录也可以参考：https://unruliness.notion.site/Rust-and-rcore-OS-c089695a75e44f54bb387dc23db97ff6

大家可以多多写记录进行分享。

## 第三阶段学习

TODO


## 参考资料

- 训练营 Github 主页：https://github.com/LearningOS

- 提问方式：

  - 问答论坛：https://opencamp.cn/os2edu/bbs，欢迎大家积极发帖讨论
  - 在微信群中提问，如果长时间未得到回复可以手动 at 负责人
  - **注意：**有任何疑问，请优先查看 [常见问题](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/QA.md)，确认常见问题列表中不存在您的问题，再通过微信群@助教以及【问答论坛】等方式提问， 常见问题列表会随着训练营的推进不断补充完善，感谢大家的参与和支持！

  