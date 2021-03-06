# ML-and-DL
self-learning

## Author
wangzhong

## 目录
* ### basic-model
    * 机器学习手写算法和实战，如线性回归，LR,SVM,KMEANS等
    * 异常检测实战和推荐算法实战等
    * 吴恩达机器学习作业
* ### math
    * 算法数学原理推导
* ### papers
    * 阅读过的经典论文
    * [深度学习巨头Lecun论文主页](http://yann.lecun.com/exdb/publis/index.html)
* ### python-dask
    * dask分布式计算框架教程和使用
* ### pytorch
    * basic-operate: pytorch简单基础操作和操作导图
--- 
## 注意！
>数学公式推导的md文件用typora写的，
如果无法正常显示，请用typora打开查看
---

## 更新日志

### 2020.12.13更新
* 增加线性回归基于pytorch的demo练习
    1. 可以让模型和数据在GPU上进行训练
    2. 通过torch.optim生成迭代器进行权重优化
---

### 2020.12.09更新
* 增加pytorch自动求导机制练习
---
### 2020.12.04更新
* 增加pytorch使用模块
    1. pytorch简单基础操作
    2. pytorch基础操作导图
    3. windows配置cuda+cudnn+pytorch查看GPU版是否安装成功
---
### 2020.11.28更新
* 增加论文模块
---
### 2020.11.26更新
* 手写推荐算法
    1. 应用场景为用户推荐电影
    2. 对一个新用户，随机给部分电影打分，初始化权重
    3. 训练之后预测新用户给所有电影的打分，从而推荐电影
---
### 2020.11.24更新
* 异常检测手写算法
    1. 多元正态密度函数
    2. 选取最佳阈值epsilon
---
### 2020.11.21更新
* math增加PCA算法步骤和原理
* 增加PCA算法
    1. 手写PCA，并计算降维后剩余方差，进行简单实战
    2. sklearn库的PCA实战
    3. 使用PCA对照片进行降维显示
---
### 2020.11.19更新
* 线性回归茅台股价预测
    1. 基于天数单特征预测，效果极差
    2. 根据股票多特征预测，准确率97%
    3. 数据集来自tushare三方库
---
### 2020.11.18更新（2）
* 部分代码增加注释，方便查看是哪个项目的代码
* 优化kmeans代码
* 线性回归boston房价预测实战
    1. 数据和标准化来自sklearn库
    2. train集和test集切分来自sklearn库
    3. 模型也是直接调用sklearn库
---
### 2020.11.18更新
* 优化项目模块结构
* dask分布式计算框架教程和实战
---
### 2020.11.17更新
* 更新疫情预测实战
    1. 使用sklearn的linear model进行简单预测
    2. 使用sklearn多项式函数进行预测（随着degree增加会过拟合）
---
### 2020.11.08更新
* 更新无监督模型kmeans手写代码
    1. 手写kmeans算法
    2. 讨论随机初始点选取的影响
    3. 用kmeans对图片进行压缩
    4. 用sklearn的Kmeans进行模型训练
---
### 2020.11.01更新
* 更新SVM算法的代码，非手写，使用sklearn，主要是熟悉工具的使用
    1. 线性SVM
    2. 非线性SVM，RBF核函数，了解gamma超参数的意义
    3. 确认C和gamma的最优参数
    4. 用SVM进行垃圾邮件分类
---
### 2020.10.27更新
* 更新方差和偏差代码
    1. 随着样本的增加更新训练集和验证集误差，高偏差
    2. 随着多项式数目增加，出现高方差
    3. 加入正则化，选取最佳正则化
    4. 用最佳lambda和测试集查看泛化能力
---
### 2020.10.24更新
* 增加线性回归相关公式推导，md和pdf两个格式
---
### 2020.10.23更新
* back propagation为手写反向传播识别手写数字
---
### 2020.10.22更新
* neural network为体验神经网络的推算流程，已给定weights，使用***forward propagation***得到最后的决策曲线。
---
### 2020.10.19更新
* linear regression为手写线性回归并画出决策曲线
* logistic regression为手写逻辑回归并画出决策曲线，用***scipy***进行迭代得到theta，另外用logistic手写一对多分类，识别1到10的数字。
