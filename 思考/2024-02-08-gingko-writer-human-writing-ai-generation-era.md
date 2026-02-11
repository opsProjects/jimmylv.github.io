---
layout: post
title: Gingko Writer：在 AI 随便生成 20 万字的时代，"生而为人"该如何写作？
categories: [思考]
tags: [写作, 卡片写作, Gingko, AI, RoamResearch, Timestripe]
published: True
---

> 这篇文章是使用 Gingko Writer 所写的，题图中 Gingko 的布局跟 Timestripe 视图是我思考的"引子"，从而开篇穿插了一大段「目标与执行」在 AI 背景下的关系重建。但重点依然是，Gingko 如何更好地围绕目标 Output 写作输出呢？让你的想法"写"出来，"放"到位。当然最后，别忘了人与 AI 在情感上的最大不同。
>
> P.S. 这篇文章是由一个真实的人写的，来自真实大脑所激发的想法和创造力。我希望你使用 AI 自动总结这篇文章时，不会过度"模糊化"。

## 始于"目标"，忠于执行

在重度（每天多次）使用 Roam Research 和 Timestripe 数年之后，最近又重逢 Gingko Writer 的布局和交互，真的是深得我心。我才意识到，原来 Timestripe 这个我用了2年多的目标管理软件，似乎也可以用Gingko就能完全替代了？

![Timestripe Timeline View](https://cdnfile.sspai.com/editor/u_/cn1enptb34ten0fq3cag)

Timestripe 的界面设计和细节，可以参考 @Miobowl 所写的这篇 [Timestripe：什么样的待办软件才是最贴近生活的人生规划器 - 少数派](https://sspai.com/post/83944)

Telegram、Timestripe、Roam Research、Readwise Reader，对我来说分别是灵感（idea 数据）、目标（goal 数据）、笔记（note 数据）、资料（refs 数据）的集合，由此可见，我还缺少了一个系统性的输出工具，即写作（opus 数据）。

![Roam Research Sidebar](https://cdnfile.sspai.com/editor/u_/cn1enqdb34tenbpc03a0)

我在 Timestripe 设置了每日目标，然后通过日历同步到 Zapier 或 n8n，然后自动触发任务执行并汇总到 Roam Research，从而我可以在 Daily Notes 当中校对目标的结果并推进下一步，日拱一卒。我在之前的[直播](https://www.bilibili.com/video/BV1YM4y1Y7Rm?t=1273.0)分享过一个 Import Google Calendar 的 `[[roam/js]]` 插件，所以Timestripe 里面安排的目标都会**手动** pull 到 Roam Research 里面，每天一次就够了。后续对于目标的修改和完成的记录也是发生在 Roam Research，我的过程笔记 notes 都在Roam Research。

![OKRs Visualization](https://cdnfile.sspai.com/2024/02/07/4a36abf4fde3350027bca2858f6d7dc1.png)

这里面其实暗合了 OKRs 的思路。只有当我将人生、年月季度的 Objective 自上而下拆分到每一天的执行，然后自下而上的输入（Roam Research 过程笔记），才是有可能真正去实现目标。我需要思考的如何去**执行目标之下的任务**，而且更应该思考如何**更好地完成目标而非任务本身**。

## 任务的"执行"交由 AI

围绕目标之后的输入 Input 和输出 Output，让我收获了更有价值的成就感。但大语言模型的到来，破坏了这种获得感，LLM 天生擅长于"文字游戏"，AIGC 内容生成在输出端以降维打击之势碾压了人类。在频繁使用 ChatGPT 等 AI 工具之后，不自觉会把人类的弱点跟 AI 的优点对比，直面人本身的弱点的同时，还需要直面 AI 本身强于人的优点。这个过程那是真的难受，于是真正"作为人"的写作需要另外的工具。

对了，由于 Timestripe 我还彻底弃用了 Things3，我发现我没有管任务了，因为我的核心思考是：AI 时代 task 不重要了，至少 task 不应该是"人"来主导执行。在操作层面上，顶多在 Timestripe 里面记录一个 subgoal 子目标，而非 task。

所以，我更多的是在考虑如何将 Timestripe 的目标与 AI 联动，AI Agent 现在的规划能力偏弱，在核心领域人类的任务拆解能力尚处于绝对优势。

![AI Agent Workflow](https://cdnfile.sspai.com/2024/02/07/f8c0116422f323dcd1af11550301c300.png)

可以说，今后人的价值就在于做好任务拆解，把任务的颗粒度控制在合适的大小，AI是能够批量化、自动化高质量完成的；与此同时，在人机协同的和谐配合之后，对于个人来说，构建知识库、以及快速构建知识库的能力很重要。基于知识库的 RAG，以及如何调取 API、RPA 等第三方软硬件能力。

我之前转发过 @Yangyi 一条很酷的 [Tweet](https://twitter.com/YangyixxVvvv/status/1751404989262836223)，也许可以开一个课程：《基于 LLM 与 RAG 的 AI 时代超级个体》（感兴趣的朋友可以评论或私信我了，众筹众筹 🐶），围绕软件和媒体，通过 AI Agent 自动化 build & sell，打造闭环，赋能个体 🤣

**杠杆率最高的：** 开发超级酷的 AI 应用
**杠杆率第二高的：** 做贼有意思的视频

![Skyline's Xiaohongshu GPTs](https://cdnfile.sspai.com/editor/u_/cn1enrlb34tenbpc03b0)

另外一方面，当 OpenAI 的 GPTs 可以让每一个都轻松构建私人助理，那么知识库的**质量**就尤为重要了，甚至是直接决定了后续 RAG 或 Workflow 执行流程的质量，而非单纯的 prompt 就能教会 LLM 那大学生水平的大脑。@Skyline 的实践经验在于：人工**来**把控源头的精确，而让 AI **去**负责细节的调控。

1. 精确获取高质量的官方信息源，而非玄学小红书运营防雷内容
2. 加入高质量的付费内容，将实战专家的可验证规模化经验作为补充

## 回归正题：Gingko 让想法"写"出来，"放"到位

Gingko 官网的 Slogan 是 Let Your Writing Flow，也就是让你的想法自由地流淌到位。

> Let your ideas flow freely into place，自然而然地形成，流动到妙手偶得的位置。

> "文章本天成，妙手偶得之。" —— 南宋陆游《文章》

![Gingko Flow View](https://cdnfile.sspai.com/editor/u_/cn1enqlb34ten5sgivo0)

张玉新老师在群里说推广 TB 很有成就感，于是又推广了一下小众的 Gingko，他在人生尺度的记录，从逻辑维度看，都在 TheBrain 中；从时间看，都在 Gingko。建议看看张玉新老师的记录示例 [https://gingkoapp.com/2021-pub](https://gingkoapp.com/2021-pub) 和关于《学习之道》的分享 [https://gingkoapp.com/art-of-learning](https://gingkoapp.com/art-of-learning) ，从而感受一下 Gingko到底是算什么形式？大纲？列表？卡片？可能只有对着屏幕边画边说，才能讲清楚。

Gingko 主要是在你面对一项重大的写作项目（比如论文、专栏、出书等），或者试图将生活的各个方面都整合在一起时，问题在于：你会如何进行组织呢？

你可能会在纸上先写一个最简单的列表？或者是用一个数字化笔记，比如在 Roam Research 从大纲开始写层级？或者说，拿起一叠纸质索引卡？先随便写，然后再自由组合起来？

**那么，为什么不同时选择上述所有的选项呢？** Gingko 创造了一个简洁界面，让你可以同时使用列表、大纲和卡片。这带来了自由，你可以从任何一种形式开始，灵感闪现一张卡片，或者深度思考几条核心观点，又或者发现了卡片之后的关联关系。这种自由和专注，形成了 Flow。

![Gingko Writing Demo](https://cdnfile.sspai.com/2024/02/07/de86788129677bb39d18626582cabba3.gif)

就像我作为程序员，特别偏好于使用键盘快捷键，而在 Gingko 当中卡片的导航、链接和展示都可以纯键盘实现，再次保障了 Flow 的流淳。

作为软件工程师的Patrick也提到，这是曾经遇到的唯一一种写作方式，它让自己能够一次性将所有想法表达出来，并同时保持有条不紊。我觉得这比 Emacs 或 Vim 模式下的诸多扩展，多了一层可视化的思维展开。

## Gingko 对于其他写作模式的融合

Gingko 作者，开篇就提到了"攻读博士学位很痛苦。"为什么？对于任何写过论文、小说或其他大作品的人来说，（组块）大小在保持专注力方面很重要。我尝试了各种文字处理软件、大纲工具、思维导图、维基和tiddlywikis……**但是发现没有任何工具能够组织我需要写的所有内容，随着内容越来越多，立马会变得令人不知所措**。

**思维导图的价值** 在于一致性放置（思维在空间推理方面很擅长），也就是将相关概念或主题以一致的方式放置在图的特定位置可以帮助大脑更容易地理解它们之间的关系。

**大纲的价值** 在于层次结构的力量，也就是将主题和子主题层层分解，有助于将信息分成可管理的部分。并且在 Roam Research 这类软件当中，可以非常自由调整父子主题的位置，即指代了层级和同级的关系，并且还能轻松合并同类项。Roam Research 还可以同层级展开或折叠节点，在深入某个局部的同时，保持对整体结构的鸟瞰。

**TiddlyWikis 的价值** 在于通过使用卡片或内容块来获得专注。慢慢地，使用一个卡片的层次结构的想法开始形成，而且不隐藏任何卡片。每个卡片或内容块都可以视为一个独立的单元，用户可以直观地将其组织和排列。当你专注于一个个小的信息单元，而不必同时处理大量的内容，这种分块的方式有助于减少认知负荷，更容易专注于当前的写作任务或主题。

![Gingko Card Organization](https://cdnfile.sspai.com/2024/02/07/article/239ba12885720adbe2d56c12f3d4dc32)

Gingko 在 UI 设计上是通过灰度来高亮正在编辑的卡片及其左侧的父级卡片，**但同时也会显示其他所有层级的内容**，只不过会降低灰度从而弱化存在感；

更重要的是，会自动将当前编辑内容始终处于屏幕的最中间，就像《使命召唤》游戏中的飞机轰炸视角但始终瞄准，从而极大提高了专注度。Gingko Writer 能够让你自动做到总是在写小组块内容，即"卡片"，这是取得进展的唯一途径：

* **Break your work into small chunks.** 将你的工作分成小块。
* **Focus on one at a time.** 一次只专注于一个。

## 让 Gingko 专注于写作输出

就如同 Gingko 重构后的新网址 (writer) 一样，[https://gingkowriter.com](https://gingkowriter.com) 我目前也是让 Gingko 专注于写作输出 (writing)，跟 Roam Research 的过程笔记作为输入，简直绝配！这篇文章的创作就是一次试验罢了，想法和资料的整理在 Roam Research，但是结构成品是在 Gingko，写起来非常愉快。

Gingko 跟 Roam Research 比还差一个 card ref，如果也能直接"穿针引线"的话，那简直就是绝，但我觉得可以互为补充。Roam Research 强于记录，但是写作输出则是另外一条逻辑，Roam Research 反而过于发散而无法专注。写作应该化网状为线性，根据 Gingko 作者的初心（写论文），我觉得 Gingko 在系统性输出上会更友好。

![Abandoned Roam Column](https://cdnfile.sspai.com/2024/02/07/bf0d798bf1adf11c2ca6ebc10d91351a.png)

也不确定，反正我之前在Roam Research尝试写专栏文章（此处愧对 @Sainho 少数派编辑），单篇篇幅动辄就是几万字了，没法看，最后导致我直接放弃咯 🤣

Roam Research 的灵活度与发散主要体现在 block ref（块引用），block embed（块嵌入）用得飞起，结果就是上下文插入过多，主线就不够清晰了，大纲 Outliner 这种其实也不适合项目或任务管理，甚至也不适合写作（成品输出），我现在也很少 all in one 甚至杜绝 all in one Roam Research。或者说，已经断了执念all in one 任意一款软件啦，哈哈哈

群友 @赣中 在讨论很多 APP 的功能视图都能在 Roam Research 实现，包括 Timestripe和 Gingko，我之前做的「[Roam卡片式主题](https://github.com/JimmyLv/styled-roam)」灵感就来自于 Gingko；但是 Roam 不固化 Pattern，终端用户是没法用的。就像你要开发个应用，你把字段设计好了，存 DB 数据库里了，然后你跟用户说你会写 SQL 吧，你自己查吧，应用层面的 UI 咱就不做了。

其实对于工具的选择还是因人而异，Roam Research 的根基 pattern 就是 outliner，这是我用得最顺手的 pattern（模式），也许跟每个人的大脑偏好有关：

**基础层级：**
* 有些人的pattern可能是folder
* 有些人的pattern可能是tags
* 有些人的pattern可能是mindmap

**更高阶的：**
* 有些人的pattern可能是TheBrain的父子兄
* 有些人的pattern可能是Excalidraw自由白板
* 有些人的pattern可能是纸笔，自带边界限制

![Heptabase Pattern](https://cdnfile.sspai.com/2024/02/07/5599fcac757949bf27b48806e6a0aa00.png)

Heptabase 原名 Project Meta，就是你所说的定义好字段，然后推出一堆的 Meta Apps（现在官方也有3、4个咯），本质上就是结构化数据之上的pattern，即应用。

## 以"人"为本，实践出"喜欢"

如果要说"最"喜欢的某种 pattern，那其实就只能选一种，但凡宣称所有 pattern 都支持的，可以灵活供选择的都是骗子。或者说，在最合适的场景下，应该选择最合适的 pattern 吧！或者换个角度来说，"人"相较于 AI 所能探寻的情绪价值是更重要的，"喜欢"本身就需要实践和时间。越用越喜欢的工具，哪怕忍受它的各种问题，一定是因为它那 20% 最特别的地方吸引了最独特品味的你。

哪怕是 Gingko，也有不同的用户用在不同的场景中，衍生出了不同的 pattern。大家可以看看官网中的 [Examples - Gingko App](https://gingkoapp.com/p/examples/) 里面有论文写作，也有 GTD 的示例。

![Full-Screen Editing](https://cdnfile.sspai.com/2024/02/07/6e6a36b08b50556d8108323c5995c648.png)

最后，总结一下在写这篇文章时，使用 Gingko 的几个严重问题：

1. 无法插入图片（不支持任何附件，纯 Markdown 语法）
2. 如果使用 md `![]()` 插入图片，拖拽就会失效（由于图片显示时的尺寸刷新问题)

当然，使用 Gingko 也有几个爽点：

1. focused 的感觉真的强，特别是淡化其他卡片和居中当前卡片的显示效果
2. 移动+合并卡片等快捷键，使用Alt+方向键，真的舒服，卡片在指尖流动！
3. 全屏编辑的效果，Shift+Enter，让人瞬间 focus 的同时保留了上下文。

那么，朋友们！等我先实践一波：Input 都放 Roam Research、Output 都在 Gingko，看看我能不能疯狂输出几篇文章？也欢迎留言与我交流，这篇文章的可读性，是否会比我之前的文章更好一些呢？

**相关阅读：**
* [序章：为什么都 2023 年了，我还在用 Roam Research 写笔记？](https://sspai.com/post/80910)
* [年度征文 | 超越效率：10x 提升阅读体验后，我有哪些反思？](https://sspai.com/post/78124)
* [年度征文 | 我是如何艰难地克服「效率成瘾」的？](https://sspai.com/post/71518)
* [思想，在树上生长：树状结构 VS 网状结构，如何搭建你的知识体系？](https://sspai.com/post/66033)
