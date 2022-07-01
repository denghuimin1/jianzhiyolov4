﻿本程序为结构化剪枝YOLOV4的程序。
其中：
1、cfg文件夹中是不同剪枝比例的网络结构。
2、logs文件夹中是模型训练产生的过程文件。
4、output文件夹是模型的检测输出。
5、layer_prune是卷积层剪枝的代码。
6、layer_channel_prune是卷积层和通道一起剪枝的代码。
7、训练集要放在VOCdevkit中。
8、train.py、teat.py分别是训练、测试程序。
9、weights文件夹中存放训练好的权重文件。
10、data文家中存放数据集的具体分类，哪些图片是训练集，哪些是测试集。
11、class,names中是船舶目标的具体名字。