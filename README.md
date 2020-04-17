# Pytorch_ZeroToALL
Pytorch 学习笔记，入门，基础，算法模型，论文代码，深度学习，......

在2020年4月17日给自己挖下这个坑，一边工作，一边学习，一边记录和整理，希望能在2020年完成这个坑.....

注意：在其中会引用大量参考资料，如侵权或引起不快请联系QQ：845743718



目录：

[toc]

# 1. 安装与配置

## 1.1 安装

pytorch主要运行深度学习模型，往往需要GPU的支持来提高运行速度，我就在windows10安装GPU版本的pytorch.

### 1.1.1 anaconda安装

### 1.1.2 新建conda环境

### 1.1.3 下载和安装NVIDIA驱动

### 1.1.4 安装cuda

### 1.1.5 安装 cudnn

### 1.1.6 安装pytorch

## 1.2 配置

### 1.2.1 安装pycharm

### 1.2.2 安装jupyter notebook

### 1.2.3 使用google colab

# 2. 入门

## 2.1 基础知识

### 2.2.2 张量（Tensor）

Tensor是pytorch中最基本的操作对象。

1. tensor的不同数据类型：

| 数据类型           | 数据类型   |
| ------------------ | ---------- |
| torch.FloatTensor  | 32位浮点型 |
| torch.DoubleTensor | 64位浮点型 |
| torch.ShortTensor  | 16位整型   |
| torch.IntTensor    | 32位整型   |
| torch.LongTensor   | 64位整型   |

2. tensor的定义

   ```python
   a = torch.Tensor([[2,3],[4,8],[7,9]]) 
   print(a,a.size())
   ```

   输出：

   ![image-20200417140136283](https://raw.githubusercontent.com/shaodongheng/RepositoryName/cloudimage/img/image-20200417140136283.png)

   

   

   



## 2.2 多层全连接神经网络



# 参考资料

[1]《深度学习入门之Pytorch》，廖星宇 编著

[2] https://github.com/zergtant/pytorch-handbook/blob/master






