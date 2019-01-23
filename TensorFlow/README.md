# TensorFlow
===

### 基础知识
- 提供了一种解决机器学习问题的高校方法。
> - 机器学习在计算机视觉、语音识别、语言翻译和健康医疗等领域。

#### windows下环境安装VS
- 下载：https://visualstudio.microsoft.com/zh-hans/thank-you-downloading-visual-studio/?sku=Community&rel=15
- 

#### windows下环境安装TensorFlow
>
1. 安装python：www.python.org，3.5.3，Windows x86-64 executable installer，
2. 安装numpy库: pip3 install numpy 
3. 安装pandas库: pip3 install pandas
* 安装最新的显卡驱动：http://www.nvidia.cn/Download/index.aspx?lang=cn；
* CUDA安装:https://jingyan.baidu.com/article/29697b9132e72eab21de3c76.html;仅支持NVIDIA显卡,英伟官网下载CUDA，然后安装。C:\Users\ADMINI~1\AppData\Local\Temp\CUDA；windows/8
* CUDNN安装:http://www.cnblogs.com/hzm12/p/6422701.html
* https://blog.csdn.net/qq_34106574/article/details/80691105

- 使用Python3.4+（https://www.ython.org）,
- TensorFlow 0.12(https://www.tensorflow.org),
- 可以在CPU上跑，在GPU上跑得更快，Nvidia Tesla/Nvidia Pascal，
- 为了运行GPU，需要下载Nvidia Cuda Toolkit（https://developer.nividia.com/cuda-downloads）v5.x
- 依赖python的包：Scipy、Numpy、Scikit-Learn 

#### 算法的一般流程
>
1. 导入/生成样本数据集
- 转换和归一化数据集（转换数据格式以满足TensorFlow，机器学习算法期待的数据样本是归一化的数据，TensorFlow具有内建函数来归一化数据）
- 划分样本数据集为训练样本集、测试样本集和验证样本集
- 设计及其学习参数
- 初始化变量和占位符：通过占位符获取数据，指定数据大小和数据类型，初始化变量和占位符
- 定义模型结构
- 声明损失函数： 说明预测值和实际值的差距。
- 初始化模型和训练模型
- 评估机器学习模型
- 调优超参数
- 发布/预测结果

#### 工作原理
>

#### 声明张量
>
- TensorFlow的主要数据结构是张量，它用来操作计算图。可以把变量或者占位符声明为张量。
- 只有把张亮复制给一个变量挥着占位符，TensorFlow才会把此张量增加到计算图。
- my_val = tf.Variable(tf.zere([row_dim, col_dim]))；该函数封装张量作为变量。
- tf.convert_to_tensor()将任意数组转换为Python列表或者将常量转换为一个张量

#### 张量类型
>
1. 固定张量
2. 相似形状张量
3. 序列张量
4. 随机张量



#### 占位符和变量的用法
>
- 计算图的关键工具是占位符和变量
- 变量是TensorFlow机器学习算法的参数
- TensorFlow维护这边变量的状态来优化机器学习算法
- 占位符是TensorFlow对象，用于表示输入输出数据格式
- 占位符允许传输指定类型和形状的数据，并依赖计算图的计算结果


#### 矩阵的使用
>
- 创建矩阵
- 加减
- 乘法
- 转置
- 逆矩阵
- 矩阵分解
- 矩阵的特征值和特征向量
 
#### 声明计算操作


#### 实现激励函数
>
- 激励函数是使用所有神经网络算法的必备‘神器’
- 目的：调节权重和误差
- TensorFlow中，激励函数的作用是在张量上的非线性操作
- 为了计算图归一化返回结果而进行的非线性操作部分

#### 读取数据源
>
- 通过TensorFlow和Python访问各种数据源


#### 计算图的操作
>
- 123

#### TensorFlow的嵌入Layer

#### TensorFlow的多层Layer
>
- 在一个计算图中进行多个操作，连接创博数据的多层Layer


#### TensorFlow实现损失函数

#### 实现方向创博

#### 实现随机训练和批量驯良

#### 实现模型评估


### 线性回归


### 支持向量机


### 最近邻域法


### 神经网络算法


### 自然语言处理


###  卷积神经网络



### 递归神经网络


### Demo
>

===

#作者利用业余时间写的，码字不易，觉得不错可以请我喝杯茶。

![my-logo.png](http://m.qpic.cn/psb?/V13wPQGu1WsR3d/7EZYVY6YKSdhaCsPFIqLou2laqOK*7qrxkKFP1GaOXw!/b/dFIBAAAAAAAA&bo=4QBSAQAAAAARB4I!&rf=viewer_4)
![my-logo.png](http://m.qpic.cn/psb?/V13wPQGu1WsR3d/n4XEA4NusddLVrFcilRR4OP3NdNs2AfksfIMvWHlzIQ!/b/dLkAAAAAAAAA&bo=DgFvAQAAAAARF0E!&rf=viewer_4)

# 谢谢！





