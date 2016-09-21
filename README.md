算法学习笔记

# 算法学习笔记

## 工具
可视化工具： [http://visualgo.net/](http://visualgo.net/)

## 算法列举
### 排序算法

- 交换排序算法
    - 冒泡排序
    - 插入排序
    - 选择排序
    - 希尔排序
    - 快排
    - 归并排序
    - 堆排序
- 线性排序算法
    - 计数排序算法
    - 基数排序算法
    - 桶排序算法

### 树
- 二分查找树
- 伸展树
- AVL树
- 红黑树
- 哈夫曼树
- B-树
- B+树
- B*树
- R树
- Treap树
- 后缀树
### 堆
- 二叉堆
- 左倾堆
- 斜堆
- 二项堆
- 裴波那契堆
### 哈希表

### 图
- 搜索算法
    - 广度优先
    - 深度优先

### 数字图像

### 数学
- 求根![sqrt](http://www.sciweavers.org/tex2img.php?eq=%7B%5Csqrt+x%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=)
    - 二分法
    - 牛顿法
- 平方根倒数速算法

### 机器学习
- 数学基础
    - 微积分与概率论  Taylor展式、梯度下降和牛顿法初步、Jensen不等式、常见分布与共轭分布
    - 数理统计与参数估计 切比雪夫不等式、大数定理、中心极限定理、矩估计、极大似然估计
    - 矩阵和线性代数 特征向量、对称矩阵对角化、线性方程
    - 凸优化 凸集、凸函数、凸优化、KKT条件

- 回归 最小二乘法、高斯分布、梯度下降、过拟合、Logistic回归 实践示例：线性回归、Logistic回归实现和分析
- 梯度下降算法剖析 自适应学习率、拟牛顿、LBFGS 实践示例：自适应学习率代码实现和参数调试分析
- 最大熵模型 熵、相对熵、信息增益、最大熵模型、IIS
- 聚类 K-means/K-Medoid/密度聚类/谱聚类 实践示例：K-means、谱聚类代码实现和参数调试分析
- 推荐系统 协同过滤、隐语义模型pLSA/SVD、随机游走Random Walk 实践示例：协同过滤代码实现和参数调试分析
- 决策树和随机森林 ID3、C4.5、CART、Bagging、GBDT 实践案例：使用随机森林进行数据分类 [含代码实现和参数调试分析]
- Adaboost Adaboost、前向分步算法
- SVM 线性可分支持向量机、线性支持向量机、非线性支持向量机、SMO 实践案例: 使用SVM进行数据分类 [含代码实现和参数调试分析]
- 贝叶斯网络 朴素贝叶斯、有向分离、马尔科夫模型/HMM/pLSA
- EM算法 GMM、pLSA、HMM 实践案例：分解男女身高、图像分割
- 主题模型 pLSA、共轭先验分布、LDA 实践案例：使用LDA进行文档聚类 [含代码实现和参数调试分析]
- 采样与变分 MCMC/KL(p||q)与KL(q||p)
- 隐马尔科夫模型HMM 概率计算问题、参数学习问题、状态预测问题 实践案例：使用HMM进行中文分词 [含代码实现和参数调试分析]
- 条件随机场CRF 概率无向图模型、MRF、线性链CRF
- 人工神经网络 BP算法、CNN、RNN
- 预习
    ```
        《高等数学·上下册》； 《概率论与数理统计·浙大版》、《数理统计学简史·陈希孺》； 《矩阵分析与应用·张贤达》； 《凸优化(Convex Optimization) · Stephen Boyd & Lieven Vandenberghe著》； 《统计学习方法·李航》； 《Pattern Recognition And Machine Learning · Christopher M. Bishop著》，简称PRML；
    ```
### 海量数据处理
- Hash映射/分而治之
- Bitmap
- Bloom filter(布隆过滤器)
- 双层桶划分
- Trie树
- 数据库索引
- 倒排索引(Inverted Index)
- 外排序
- simhash算法
- 分布处理之Mapreduce
<!--
## 使用
1. clone 或者下载该项目
1. 使用Atom打开， 安装[amWiki](https://github.com/TevinLi/amWiki)插件
1. 点击Atom菜单
    ```
    1. amWiki文库 > - 本地web服务器 > 启动本地静态web服务器
    2. 打开library/首页.md
    3. amWiki文库 > - 本地web服务器 > 在浏览器打开当前页
    ```
-->
