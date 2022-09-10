# 油气人工智能基础<br />
---
# 聚类算法<br />
## 划分聚类 — K-means<br />
定义：K-means算法是通过**均值**进行数据点的聚类，而且是以**距离**作为数据集样本相似性的指标，我在编写的时候采用的是欧式距离.由于是随机生成初始聚类点，所以初始点的生成会影响聚类结果.<br />
## 层次聚类 — Agnes(AGglomerative NESting)<br />
定义：它先将数据集的每个样本看作是一个初始簇，然后在算法中运行的每一步找出**距离最近**的两个簇进行合并，该过程持续进行，知道达到预设的聚类簇的个数<br />
## 模型聚类 — GMM(Gaussian Mixture Model)<br />
定义：涉及**EM**算法以及**多维高斯分布**，算法原理还没太搞懂.<br />
## 密度聚类 — DBSCAN(Density-Based Spatial Clustering of Applications with Noise)<br />
定义：密度聚类算法从样本的密度角度来考虑样本之间的可连接性，并给予可连接样本不断拓展其聚类簇的大小并最终获得结果，DBSCAN算法不需要提前设定聚类数k，其通过“邻域参数”( $\epsilon$ , $MinPts$ )来刻画样本分布的紧密程度<br />

---
# 特征提取算法<br />
## 主成分分析 — PCA<br />
定义：PCA(Principal Component Analysis),即主成分分析,是一种统计学方法.通过正交变换将数据转化到新的坐标基中，从而将原本可能的变量投影转换为线性无关的变量.如果变换后的维度小于变换前的维度，就可以对数据进行压缩，达到降维的效果<br />
## 核主成分分析 — KPCA<br />
定义：<br />
## 线性判别分析 — LDA<br />
定义：<br />
## 核Fisher判别分析 — KFD<br />
定义：<br />

---
