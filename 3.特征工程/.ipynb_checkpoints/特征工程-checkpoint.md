### 特征工程

![10](https://github.com/Zoenamed/Learn-Data-mining/blob/master/img/10.png)


1.什么是特征工程？

根据模型和实际意义将数据规整成可供模型使用的特征（就像做菜时，先要将买来的菜洗净、切好备用一样）

2.特征工程步骤？

- 数据理解：EDA了解数据

- 数据清洗：特征变换、处理缺失值、异常值、其他

- 特征构造（对不好直接当作特征但又含有一定信息量的数据进行进一步转换处理）：统计量特征、时间特征、地理信息、非线性变换、数据分桶、特征组合

- 特征筛选（降低噪声、平滑预测能力和计算复杂度，增强模型预测性能）：

  过滤式、包裹式、嵌入式

- 解决类别不平衡问题：

  > 类别不平衡问题：类别少的话提供的信息太少，没有学会如何判别少数类

3.重点步骤详细介绍
![mindmap](https://github.com/Zoenamed/Learn-Data-mining/blob/master/img/11.png)

4. [code](https://github.com/Zoenamed/Learn-Data-mining/blob/master/3.%E7%89%B9%E5%BE%81%E5%B7%A5%E7%A8%8B/Task3%20%E7%89%B9%E5%BE%81%E5%B7%A5%E7%A8%8B.ipynb)

5.补充（ 转于ApacheCN）：


（1）特征选择 —— 也叫特征子集选择（FSS，Feature Subset Selection）。

指从已有的 M 个特征（Feature）中选择 N 个特征使得系统的特定指标最优化，是从原始特征中选择出一些最有效特征以降低数据集维度的过程，是提高算法性能的一个重要手段，也是模式识别中关键的数据预处理步骤。


（2）特征提取 —— 特征提取是计算机视觉和图像处理中的一个概念。

指的是使用计算机提取图像信息，决定每个图像的点是否属于一个图像特征。特征提取的结果是把图像上的点分为不同的子集，这些子集往往属于孤立的点，连续的曲线或者连续的区域。

挂一张大佬的图
![12](https://github.com/Zoenamed/Learn-Data-mining/blob/master/img/12.jpg)

```{.python .input}

```
