# dogs-vs-cats

## 简介

kaggle计算机视觉经典赛题，利用深度学习网络，根据图片区分猫和狗。赛题地址在[这里](https://www.kaggle.com/c/dogs-vs-cats) 。

```
Author:yudake
date:2018/2/25
```

开发环境：

- python2.x；
- tensorflow-gpu版；
- open-cv
- 其他相关类库，程序内会有提及。

目标：根据图片区分猫和狗。

模型效果：最终准确率在

## 模型

- 输入：经过调整为相同大小的图片；
- 输出：分类结果。

## 数据

![graph](https://github.com/yudake/dogs-vs-cats/blob/master/images/dogs-vs-cats_graph.png?raw=true)

测试集：训练集中的1000张图片。

交叉验证集：剩余训练集中的5%的数据。

训练集：剩余数据。

## 准确率

![准确率](https://github.com/yudake/dogs-vs-cats/blob/master/images/dogs-vs-cats_accuracy.png?raw=true)

可以发现，在训练集上的平均准确率在80%左右，而且可以发现准确率仍在上升。

测试集的准确率为77%。受硬件制约，我们只训练了10个epoch。如果继续训练，可能准确率会增加。