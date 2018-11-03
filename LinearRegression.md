# 线性回归

## 背景介绍
给定一个大小为n的数据集$${y_i,x_{i1},...,x_{id}}^n_{i=1}$$，其中$$x_{i1},…,x_{id}$$是第i个样本d个属性上的取值，yi是该样本待预测的目标。线性回归模型假设目标yi可以被属性间的线性组合描述，即

$$y_i=ω_1x_{i1}+ω_2x_{i2}+…+ω_dx_{id}+b,i=1,…,n$$

初看起来，这个假设实在过于简单了，变量间的真实关系很难是线性的。但由于线性回归模型有形式简单和易于建模分析的优点，它在实际问题中得到了大量的应用。很多经典的统计学习、机器学习书籍[2,3,4]也选择对线性模型独立成章重点讲解。

## 房价预测PaddlePaddle-fluid版代码：
https://github.com/PaddlePaddle/book/blob/develop/01.fit_a_line/train.py