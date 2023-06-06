# Professor Gao said I don't work hard
## 大模型时代，普通人的科研何去何从
### 王晋东不在家
1. 新的分析和评测

大模型时代显然需要新的分析和评测方法。不同于以往以公开测试集为准的机器学习，大模型现在可以将所有的公开数据集全部吃下（即overfit）。因此，不宜采用传统方式进行评测。可以思考：

更有难度、更符合人类标准的评测集是什么样的？
大模型的边界在哪里、什么样的数据可以测出来？
小模型和大模型到底有什么区别、仅仅是benchmark得分不同吗？
如何公平地评测不同大模型的能力？
到底何为”AGI“?如今的评测是否是AGI评测？

2. 新的理论和方法

大模型对于做理论和基础研究的科研人员是个毁灭性的打击。原因很简单：深度学习理论在目前也无法很好地分析多层神经网络、更不必说更大、更不开源的黑盒大模型了。因此，理论研究人员可能会出现”巧妇难为无米之炊“的情形、不知道自己还能做什么。

但笔者认为，基础理论、数学、统计、概率等基础学科的重要性仍然无需多言，但需要结合大模型进行一些探索和突破。例如：

为什么CLIP仅采用image-text pair进行对比学习、泛化能力就很好？
如果是训练数据重要，那为何400M数据的CLIP和2B数据的Laion-CLIP在长尾数据上并没差太多？
数据、模型、算法、优化，哪个更重要？
如何加速大模型的训练，如从数据筛选、优化器更新的角度？

3. 更好的人与AI协同

既然打不过，那索性就加入。我们可以将大模型看作一次大的技术革命、一种新的人机交互方式。那么，此刻的你我就处于这种新的人机交互、人与AI协同的革命前夜，应该多去思考如何利用大模型的能力来做出更多变革：

如何提高写Prompt的能力、最好是自动写好的Prompt？
CV、NLP、Audio都有大模型，如何利用这些模型进行更好的多模态信息融合？
如何设计下一代人-AI协同交互的用户界面？
如何将大模型快速轻量地部署于端侧设备？

如何更轻量地微调大模型以服务于下游小数据领域？

4. 找大模型的短板

不得不说目前的大模型并不完美、其问题多多。笔者也在年初”卷“了一周、搞出了第一个ChatGPT的鲁棒性评测。我们发现大部分大模型其实对于对抗攻击并不鲁棒、其抗干扰能全力亟待提升。因此，一个自然的研究方向便是”找茬“：

大模型的OOD能力是不是够了？有大模型不需要OOD了？
大模型的长尾是不是做的很好了？这个笔者探索过了：显然不太行—Exploring vision-language models for imbalanced learning.
如何使大模型免受prompt injection、prompt leakage等攻击？
大模型生成内容如何判别是hallucination还是真的？

5. 更负责任、社会化的AI技术

新的技术革命需要新的社会变革，而变革的过程可能是充满荆棘的。好的研究视野应该放眼全社会、做出更负责任和更社会化的AI研究（Responsible AI, or societal AI），方可确保技术不被滥用、更好地服务人类：

如何进行有效的value alignment使AI准确地满足人的价值观？
如何对AI生成的内容进行有效监管使其实不被滥用？
如何分析生成式AI对教育、生产力、社会、心理学等诸多层面的影响？
新技术应该是”有温度“的：如何引导”前人“更加无痛地完成新技术的更迭？
此类问题的每一个都值得深入探讨。值得一提的是，笔者所在的研究组——微软亚洲研究院社会计算组的大部分研究人员均在做相关研究。也期待未来有更多的合作者加入进来一起合作。社会化问题任重而道远，需要跨学科、全社会的长期密切交流合作。
### 李沐团队:
- efficient (PEFT:parameter efficient fine tuning)
- existing stuff (pretrained model) new direction
- plug and play(即插即用)
- dataset, evaluation and survey
# How to write a weekly report
论文十问由沈向洋博士提出，鼓励大家带着这十个问题去阅读论文，用有用的信息构建认知模型。写出自己的十问回答，还有机会在当前页面展示哦。
Q1论文试图解决什么问题？
Q2这是否是一个新的问题？
Q3这篇文章要验证一个什么科学假设？
Q4有哪些相关研究？如何归类？谁是这一课题在领域内值得关注的研究员？
Q5论文中提到的解决方案之关键是什么？
Q6论文中的实验是如何设计的？
Q7用于定量评估的数据集是什么？代码有没有开源？
Q8论文中的实验及结果有没有很好地支持需要验证的科学假设？
Q9这篇论文到底有什么贡献？
Q10下一步呢？有什么工作可以继续深入？
## last week
1. Monday (May 29th, 2023):
   - Attend Ant Interview.
   - Prepare your final cheet sheet.
2. Tuesday (May 30th, 2023):
   - Prepare your final cheet sheet.
   - My thinking really took another major shift. I won't write what exactly it is. But it will be implemented in my actions.
   - chat with sheng brother, zhao sister.
3. Wednesday (May 31st, 2023):
   - Prepare your final cheet sheet.
4. Thursday (June 1st, 2023):
   - Read the article given by Mr. Gao.
   - Take the algorithm test
   - Watch Inuyasha anime
5. Friday (June 2nd, 2023):
   - Watch Inuyasha anime
   - Reject Jinshida HR's Chinese resume request
6. Saturday (June 3rd, 2023):
   - Accompany Senior Sister Shao to play in Shanghai
7. Sunday (June 4th, 2023):
   - Accompany Senior Sister Shao to play in Wuxi
   - complete oj
## this week
1. Monday (June 5th, 2023):
   - I watched the video explanation of the history of the Jin Dynasty.
   - Wang, a student from the School of Life Sciences, came to guide the work. 
2. Tuesday (June 6th, 2023):
   - watch Apple Worldwide Developers Conference.
   - Apply for an account connected to the Internet in SHIC.
   - Install the Nvidia driver on debian
   - Immediately contact Junior Brother Lian and tell him that I am going to start learning analog electronics. make a plan first.
   - Anyway, I'm free now, let's take the TOEFL. make a plan first. Let English be my working and living language.
   - The 6 free swimming sessions in the 2023 Spring Semester Campus Card will end on June 18 (including the day).


重启模电数电学习计划，搭乘学弟的便车。一点小小建议。拿我自己来说，因为我本质上还是做锂电池的SOC计算和均衡等等的控制策略的，我不需要像底层或者硬件的人那么了解电路，所以模数电我都是浅尝辄止，工作够用。后来工作后发现通讯协议还有信号处理反而用得多一点。你可以先弄弄清除你哪里有学各种电的需求还有要了解到什么程度，再去安排时间，这个我就给不了意见了.



打算找张托福的卷子。托福变了：自7月26日起，托福新考法的考试时长、考试内容均有调整。智师兄用的只是考满分。我现在想学的是托福，GRE、新概念3、4都往后放，甚至说，我有必要学新概念吗？

1.  Wednesday (June 7th, 2023):
   - Either write something worth reading or do something worth writing.
2.  Thursday (June 8th, 2023):
   - Either write something worth reading or do something worth writing.
3.  Friday (June 9th, 2023):
   - Write a weekly report.
   - Go to Wuxi for a meeting. Meet Brother Yang.
4.  Saturday (June 10th, 2023):
   - Either write something worth reading or do something worth writing.
5.  Sunday (June 11th, 2023):
   - Either write something worth reading or do something worth writing.



JavaScript，Vue，react，nodejs，nextjs，stable diffusion。
https://developer.mozilla.org/en-US/docs/Learn
可以直接学 vue
https://vuejs.org/
不好意思，上周没给您交待一下后续。周老板让我考虑一下，可以先做前后端，然后他觉得我做得不错的话，可以继续做算法的维护。去实习的话，可以远程，一天三百块钱。
这几项技术确实是有点难度的。我打算这周先学点，这周末再找周老板聊一下，看能不能开始去承担工作。
其中涉及到的数据库、网络、异步、多线程编程是最有用的知识.

   - 向强者学习：师姐的闺蜜在证券，淼，颜大哥，menova，张勃礼.
   - Investigate the composition of the creators of the major self-media platforms（中国社会各阶级分析）
   - The final exam will be on June 1, 2023 from 1-3pm in room 102 in the Teaching Center.

王航给了一堆文献。
王航转发了白老师的竞赛消息。和他讨论一下后续。
把sam模型finetune一下，最后几层。就随机sample几十张来finetune就行。

## next week
1. Monday (June 5th, 2023):
   - Either write something worth reading or do something worth writing.
2. Tuesday (June 6th, 2023):
   - Either write something worth reading or do something worth writing.
3. Wednesday (June 7th, 2023):
   - Either write something worth reading or do something worth writing.
4. Thursday (June 8th, 2023):
   - Either write something worth reading or do something worth writing.
5. Friday (June 9th, 2023):
   - Either write something worth reading or do something worth writing.
6. Saturday (June 10th, 2023):
   - Either write something worth reading or do something worth writing.
7. Sunday (June 11th, 2023):
   - Either write something worth reading or do something worth writing.
## the week after next week
```
1. Monday (June 12th, 2023):
   - Either write something worth reading or do something worth writing.
2. Tuesday (June 13th, 2023):
   - Either write something worth reading or do something worth writing.
3. Wednesday (June 14th, 2023):
   - Either write something worth reading or do something worth writing.
4. Thursday (June 15th, 2023):
   - Either write something worth reading or do something worth writing.
5. Friday (June 16th, 2023):
   - Either write something worth reading or do something worth writing.
6. Saturday (June 17th, 2023):
   - Either write something worth reading or do something worth writing.
7. Sunday (June 18th, 2023):
   - Either write something worth reading or do something worth writing.
```
Can you write in this style for the next week? I hope you also wrap the content with code blocks. No need to write about festivals and events.

# 暂且搁置：
1. 李沐讲的alpha fold再看看，我还不会。人家都玩过了。
2. learn to use pdb、gdb.
3. 听了高老师发的cvpr广东会议，中山大学刘祖浩的异常检测听起来不错，一会去看看论文和代码。
4. 武给我了解决gcc问题的log文件，我去研究一下，看看能不能解决glibc. 还有tensorboard的新的理解。
5. 上次选的programming language,先上GitHub找solution。
6. 子明：对 跑实验耗时长 先看看论文。确定差不多要做了 就跑跑看具体效果。
7. 什么是vae？
8. https://www.zhihu.com/question/356351510
9. stylegan，，，gan家族。
10. 去看看陈浩的博客，
11. 快找到杨说的pytorch实战，过一遍。武的也过一遍。
12. 我之前居然还有 games 101的想法。我开的坑也太多了吧。
13. 魏：eccv+cvpr论文大礼包，看完bilibili霹雳啥的视频。
14. 看完上学期的课件。再看周师兄的发回来的cs231n的代码。
16. 异常检测 | MemAE模型复现与思考 - 阿尔法杨NJU的文章 - 知乎
https://zhuanlan.zhihu.com/p/344615097
https://www.sciencedirect.com/book/9780128238189/anomaly-detection-and-complex-event-processing-over-iot-data-streams
https://medium.com/@jelkhoury880/introduction-to-anomaly-detection-methods-part-i-b1a2f389ffcb
1. Professor  Gao gave me three articles。分子生成确实是一个不错的方向。
2.  Watch the movie：the way of Water, The Lord of the Rings.
3.  [向这位小兄弟学习cpp](https://07xiaohei.com/)

## 每天我想问的问题，应该问谁？
要不厌其烦地去问:chatgpt、晋老师、厉老师、306师兄们。
你给老师的周报中只写自己干了啥、学了啥，这些都不重要，你试着写下自己一周有啥思考、科研进度咋样是不是on track。学那么多没用，重要的是多思考。研究生就这几年，一定要得专注自己的精力。每周坚持看点paper。

要dig in code，代码实验不是voodoo，要会调试代码，知道运行到哪里报的错，为什么报错。比如这个错误，字面意思已经告诉你了它不识别mp4后缀文件，说明没有装或者没有正确安装视频解码包，所以你装一个ffmpeg就好了。所以他不是个bug，更不“神奇”，只是你比较菜（没有批评你的意思，刚开始都这样）。
学会用pdb.set_trace()和基础的print()定位错误，并且理解错误哈。

# 知道什么暂时不该做
1. 政治助教实习
下学期徐的助教，已经联系了：陈茂华老师。利用当助教的机会，研究一下数据库签到如何实现。
2. Cousera上的课程感觉都不够深入。
想专攻一个领域，还是要起码好好地深入读一本教材，这样能带着你思考，让你知道整个学科的众多方法是如何基于某种逻辑原则建立起来的。

后面不用刷那么多课了，原理理解透了就行，尽快在组里找一个project参与进去，没啥想法可以来跟董思勋做人体动作识别，刚开始，正需要labor work。这学期一定投出去一片论文，不然真掉队了，而且第二年你还可能要去企业？这学期你得有点想法和规划了。

3. 暑假去中医药大学当保安?看看夏怎么安排？

4. 简历上写的MySQL也不会，酉矩阵分解得继续理解
学一门北大的量子计算，直接看看课后习题
http://scholar.pku.edu.cn/xiaoyuan/classes/QIQC

第十 canvas.net 没有量子计算内容 但是有很多大学发布的内容 免费
第九 crash course 中小学生 适合科普 关于量子的内容不多 免费
第八 khan academy 可汗学院 白嫖福音 适合各类人群 量子的内容多一点
第七 udemy和codeacademy 专业系统 后者主要教人写代码 前者还有商务设计市场等等 无法白嫖 可蹲优惠活动
第六 coursera brilliant edx 内容专业 与知名大学合作 前者的结业证书可写到简历上 brilliant有些收费 针对性较强
第五 linkedin learning 针对上班族 以视频为主 结业证书可以写到网站简历 免费
第四 github和arxiv 前者开源代码社区 后者是科学家的社区 是可以将学术论文上传的公开文档库 都免费 可获取前沿专业信息
第三 ms learn 有up的量子学习模块 免费
第二 量子学习个性化定制网站 up开发的（up好厉害！） 也有up发布和收集的各类资料 网站特点是因材施教 全部免费 量子计算针对性高
第一 简单来说就是谁做的好谁就是第一
## 赵老师的指点
注意研究方向的收敛，聚焦解决具体的且具有挑战的工程问题。

一周精读一篇论文，顶级会议，顶级期刊，ccf中国计算机协会，对国际期刊有排名，看a类，，有精力再看b，，，找计算机体系结构，嵌入式计算，，，，三五篇摘要粗读
找最相关的论文，近三年的，先看去年的
b类
TECS ACM Transactions on Embedded Computing Systems 
JSA Journal of Systems Architecture: Embedded Software Design
HiPEAC
International Conference on High Performance and Embedded 
Architectures and Compilers
RTAS
Real-Time and Embedded Technology and Applications 
Symposium
## 晋老师：
http://devplatform.cambricon.com:30080/server

先熟悉MLU270-Pytorch模型移植流程（量化、逐层、融合、生成离线）以及相关接口使用，具体可以参考https://developer.cambricon.com/index/document/down.html?ddd=9中“寒武纪 PyTorch 用户手册”、熟悉离线部署代码（docker开发环境中example目录），

可选用YOLOv5进行练手：https://developer.cambricon.com/index/curriculum/expdetails/id/10/classid/8.html。
## 王大哥的箴言：
不可能面面俱到，好比说，
情景一，去了大厂，华为，中芯，不可能面面俱到地干。只会让你干一个点。
情景二，你去了小厂，那就可能出现，你什么都干，那就需要你什么都懂，什么都干。
当前的矛盾，嵌入式智能计算，我个人感觉，它是偏软的。先把知识架构架起来。
一，你不是科班出身；她是科班出身，模拟电子技术，单片机是优势。先去架起来，知识架构，哪个知识点不会再去补。她的优势是学了四年，知识架构起来了。
我现在最着急的是把知识架构架起来。再去看学项目的过程中，不会什么学什么。
硬件的浅尝辙止；
你嵌入式、Linux系统搞清楚；找一个开发板，先大概搞清楚框架。
搞清楚fpga，让你验证个东西，你能验证。
你最起码得会一个算法。
不要对什么东西抗拒，可能以后会有用；看完之后，太基础的东西是好，但是要动手；可以从实际经验出发。
这么讲，你到底想去做什么，可能为时尚早，随着认知加深，
你的经历可能会改变你的看法。项目的附加值是最高的。