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
4. 安装最新的显卡驱动：http://www.nvidia.cn/Download/index.aspx?lang=cn；
5. CUDA安装:https://jingyan.baidu.com/article/29697b9132e72eab21de3c76.html;仅支持NVIDIA显卡,英伟官网下载CUDA，然后安装。nvcc -V 验证是否Ok；C:\Users\ADMINI~1\AppData\Local\Temp\CUDA；windows/8
6. CUDNN安装:
下载：https://pan.baidu.com/s/1aW89xEfaieY-9dvgAApiEw
解压后拷贝到
https://developer.nvidia.com/cudnn
http://www.cnblogs.com/hzm12/p/6422701.html
* https://blog.csdn.net/qq_34106574/article/details/80691105
* https://blog.csdn.net/m0_37638031/article/details/78896818

- pip3 install tensorflow-gpu
- pip install opencv_python-3.2.0-cp35-cp35m-win_amd64.whl

>
CUDA:Compute Unified Device Architecture，显卡厂商英伟达推出的运算平台。通用并行计算架构，该架构使用GPU能够解决复杂的计算问题。包含CUDA指令集架构（ISA）以及GPU内部的并行计算引擎。
CUDNN:是专门针对Deep Learning框架设计的一套GPU计算加速方案，目前支持的DL库包括Caffe，ConvNet, Torch7等。

- 使用Python3.4+（https://www.ython.org）,
- TensorFlow 0.12(https://www.tensorflow.org),
- 可以在CPU上跑，在GPU上跑得更快，Nvidia Tesla/Nvidia Pascal，
- 为了运行GPU，需要下载Nvidia Cuda Toolkit（https://developer.nividia.com/cuda-downloads）v5.x
- 依赖python的包：Scipy、Numpy、Scikit-Learn 

#### 例子
>
- https://www.cnblogs.com/wuyida/p/6300207.html

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
- 在一个计算图中进行多个操作，连接传播数据的多层Layer


#### TensorFlow实现损失函数
>
- 度量模型输出与目标值间的差距
- L2正则损失函数（欧拉损失函数）
- L1正则损失函数(绝对值损失函数)
- Psedu-Huber损失函数
- 分类损失函数
- Hinge损失函数
- 两类交叉熵损失函数
- Sigmoid交叉熵损失函数
- 加权交叉熵损失函数
- Softmax交叉熵损失函数
- 稀疏Softmax交叉熵损失函数


#### 实现反向传播
>
- 维护操作状态和基于反向传播自动地更新模型变量

#### 实现随机训练和批量驯良

#### 实现创建分类器
>
- 创建一个iris数据集的分类器

#### 实现模型评估
>
- 在训练模型过程中，模型评估能洞察模型算法，给出提示信息来调试、提高或者改变整个模型。


### 线性回归
>
- 线性回归算法是统计分析、机器学习和科学计算中最重要的算法之一
- 


### 支持向量机


### 最近邻域法


### 神经网络算法


### 自然语言处理


###  卷积神经网络



### 递归神经网络


### Demo
>

===

# 谢谢！





