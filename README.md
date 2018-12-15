# ANN
## 1.第一次更新
一个简单的神经网络模型，包含了神经网络各种基本的功能。主要参考吴恩达的cs231n课程
ANN模型主要由以下几个类依次拼接而成
### Data
主要功能是提供数据的批处理操作
### FullyConnect
ANN模型的主要部分之一:
主要完成了以下功能
a.对数据进行线性变换
b.数据的反向传播
FulllyConnect封装了如下的优化算法:
Gradient descent/
Monmentum/
RMSprop/
Adam/
提供了两种正则化方法:
L2正则化/
drop-out正则化
以及
batch-normal归一化
### Sigmoid,Relu1,Relu,Tanh主要功能如下
a.数据的非线性变换
b.反向传播
### QuadraticLoss
a.计算损失熵函数
b.反向传播
### Accuracy
计算准确率
### ANN
使用上述各部分搭建一个人工神经网络模块
