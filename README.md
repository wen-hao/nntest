# nntest

任务：使用神经网络检测视频中的车辆和行人

代码运行环境：anaconda navigator（jupyter notebook）

数据包：

import os

import numpy

import time

from PIL import Image

（ptv代码运行需要额外导入cv2）

------------------------------------------------------------------------------------------------
nn    神经网络的相关函数

sys   使用神经网络对图片进行处理

ptv   将图片合成视频

data 数据集（行人数据集 60_Daimler Pedestrian Detection Benchmark  车辆数据集Cardata）

res,resr,resc 处理后的图片

NNr 行人网络模型

NNc 车辆网络模型
