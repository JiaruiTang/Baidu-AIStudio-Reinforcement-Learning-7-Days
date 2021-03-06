# Baidu AIStudio Reinforcement Learning 7 Days 百度AIStudio强化学习7日训练营

作为滞留在美国的留学生，暑假已经开始半个月了。无所事事很多天后，朋友给我推荐了Baidu AiStudio的强化学习7日训练营课程。题主过去一年主修的是机器学习，对于强化学习知之甚少，这门课旨在帮助初学者快速入门，正好满足了我的需求。接下来按照课程提纲说一说这七天的课程感悟：

1. 预习课程

课程开始前，助教老师们就开始忙碌起来了，连续4天在微信群里发布预习作业，帮助大家打好基础，为后面的课程做充分的准备。预习作业的主要内容有：

什么是深度学习
必备数学知识
Python快速入门
PaddlePaddle快速入门
AiStudio基本操作
对于有机器学习基础的题主来说，除了PaddlePaddle要仔细研究一下，其余的预习课程都是对以前知识的巩固，完成相对轻松。

2. 强化学习初印象

第一节课比较基础，介绍了强化学习的基本概念、应用和核心知识。老师通过生物课上大家熟知的人类学习的知识引入强化学习的概念，非常生动。第一天的作业是搭建环境，成功运行PARL。虽然只有三个block的代码，但是对于第一次接触的我来说，还是花费了一些时间。幸运的是，课程的讨论区帮助很大，通过翻阅大家的讨论，我最终解决了搭建过程中出现的问题。

3. 基于表格型方法求解RL

这一天正式开始学习RL的具体算法，从最简单的Q表格开始。作业是小乌龟走迷宫，第一次成功地跑通代码，看到小乌龟不停地学习着，最终找到不掉进悬崖走通迷宫的路线时特别的激动。课上视频讲解代码非常清楚，让写作业轻松了不少。

4. 基于神经网络方法求解RL

这一天难度开始上升，从比较容易理解的表格算法进化到了稍微抽象的函数逼近、DQN，但是整体算法框架还是和之前的表格型方法相近，老师讲得也非常易于理解。这一次的作业是让小车爬坡，看到讨论区里好多小伙伴遇到reward难以提高的问题，我比较幸运，跑了两次就达到要求了。

5. Policy Gradient

这一天的算法对我来说有点难度，视频反复看了好多遍才大致理解。作业是乒乓球Pong，这次作业有两个很让人痛苦的地方：
一是运行非常慢——100个episode要20分钟左右；
二是调参很有技巧性——使reward大于0没有花费我很长时间。但是我尝试了很多参数，至今还没能达到reward大于10这个目标。
希望未来我能寻找到更加有效的调参的方法来提升结果。

6. 连续动作空间求解RL——DDPG算法

这个算法整体来说有些抽象，也是花费了很多时间来理解学习，可能课程结束之后还要再看看学霸笔记加深理解。大作业“飞行器悬浮控制任务”非常有意思，但也有一些难度。看着自己的飞行器一点一点调整着平衡飞起来很有成就感。

总的来说，这7天的课程里，内容很扎实，科科老师讲解得很生动也非常清楚。唯一有一些遗憾的就是最后两个作业对调参能力有一定要求，我对模型的理解还不够透彻，这使得我的模型训练速度极慢、难以收敛，希望未来加深了对强化学习的学习后，能重新回来更轻松地解决这些问题。

非常开心在这个不平凡的暑假遇到可爱的科科老师，感谢老师和助教们在这7天里的带领和帮助。在短而精的7天集训中，题主收获颇丰，成功入门强化学习。
