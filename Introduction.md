## Introduction

我们所知道的机器学习大致类似于给定一些输入然后得到我们想要的输出。其中需要找到一些符合要求的函数式来对我们的输入进行处理。

### Supervised Learning

1. 简而言之，就是我们是有理想的输出预期的，提供给机器有label的资料进行学习，叫做supervised learning，该种情况下训练结果可以评估模型的好坏，即一个loss值，在错误率的基础上进行演变计算得到。
2. 接下来就是我们期望机器找出loss最小的函式

### Reinforcement Learning

* 如果让supervised learning来训练alphago的话，就相当于每种情况下，你告诉它应该怎么下。
* 以alphago为例子，强化学习就是机器随便下棋，在多次尝试之中逐渐找到取胜的方法，当然我们也可以进行supervised learning和reinforce learning进行结合。
* 所以说reinforce learning就是一种非监督学习，不给数据上标签的那种。

### 寻找函式

* 选定一个函式的范围，即函数搜寻的范围，比如像最开始就只选择线性的函式。
* 常见的搜寻范围网络有RNN和CNN。
* 函式寻找算法：gradient descent
* 可解释ai，对抗攻击（针对机器做出变动），以及network compression
* Anomaly detection：如何知道自己不知道。
* Transfer Learning：在自己的测试资料上跑的准确率很高，但是在其他数据上面跑准确率非常低。
* Meta Learning : teach machine to learn by themselves.通常来说花费时间是比较长的。
* life long learning：使机器进行持续性学习。

[课程主页](http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML20.html)

老师说完全可以在家自学。

课程以作业为规划，每一行就是一个作业，每个作业都具有实例。