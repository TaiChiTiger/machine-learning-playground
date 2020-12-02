# 机器学习游乐场-机器学习洞察2 （Machine Learning From Scratch - Machine Learning Insight 2）[App](http://39.98.239.104:8505/)
机器学习游乐场是一个对模型进行交互式可视化的应用程序。

## 结构
遵循常用机器学习分类方法，现在该程序完成了5个部分，如下图。

<p align="center">
<kbd><img title="分类" src="https://github.com/TaiChiTiger/machine-learning-playground/blob/master/images/types_of_ml.jpg"></kbd><br/>
<kbd><img title="分类" src="https://github.com/TaiChiTiger/machine-learning-playground/blob/master/images/ml_tasks.jpg"></kbd><br/>
</p>

这5个部分分别对应5个子程序，点击下面的[App](http://39.98.239.104:8505/)可进入。需要说明的是，目前这些程序存放在阿里云，服务器的配置较低，访问和运算速度都很慢，请耐心等待。

**监督学习**

- [分类](https://github.com/TaiChiTiger/machine-learning-playground/tree/master/classification) [App](http://39.98.239.104:8506/)：用由生成模型生成混合数据集，比较40多个分类模型，如逻辑回归、支持向量机和各类集成方法等

- [回归](https://github.com/TaiChiTiger/machine-learning-playground/tree/master/regression)：用一维合成的非线性数据集，比较回归模型，如逻辑回归、支持向量机和各类集成方法等，目前正在开发中

**无监督学习**

- [聚类](https://github.com/TaiChiTiger/machine-learning-playground/tree/master/clustering)：用合成数据集，如团状数据、圆形数据和月牙形数据等，比较不同的聚类技术，如K均值、高斯混合和层次聚类等

- [降维](https://github.com/TaiChiTiger/machine-learning-playgrounds/tree/master/dimensionality-reduction)：用手写数字识别数据集，比较不同的降维技术，如PCA、Isomap和自编码等

- [异常值探测](https://github.com/TaiChiTiger/machine-learning-playground/tree/master/outlier-detection)：用合成数据集，如单聚类数据、等方差数据和变方差数据等，比较不同的异常值探测技术，如单类支持向量机、局部离群因子和Restricted Boltzmann Machine等

## 特点
- 所见即所得：可手动调节模型的主要参数，观察误差、决策边界和验证曲线等信息的变化。同时，提供丰富的图形以增强直觉
- 自动调优参数：包括格网搜索、TPE采样和贝叶斯优化三种自动调优方法，并解释每种方法的优化过程
- 尽可能地包含所有模型：开发这个程序的初衷更多是为了教育目的和研究兴趣，所以如果时间允许的话，我将尽可能地展示整个机器学习模型图景
- 支持移动端访问：在移动端的访问与操作和PC端的相同，方便随时查看。这是由于程序采用了[Streamlit](https://www.streamlit.io/)作为前端，感谢这个产品
## 示例
以随机森林模型为例：

手动调优：
<kbd><img title="例子" src="https://github.com/TaiChiTiger/machine-learning-playground/blob/master/images/manual_tuning.gif"></kbd><br/>

自动调优：
<kbd><img title="例子" src="https://github.com/TaiChiTiger/machine-learning-playground/blob/master/images/automatic-tuning.gif"></kbd><br/>

## 参考
- [Tensorflow Playground](http://playground.tensorflow.org/)
- The Element of Statistical Learning: [Website](https://web.stanford.edu/~hastie/ElemStatLearn/), [Amazon](https://www.amazon.com/-/zh/Elements-Statistical-Learning-Prediction-Statistics/dp/0387848576/ref=sr_1_1?__mk_zh_CN=%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BD%91%E7%AB%99&dchild=1&keywords=The+Element+of+Statistical+Learning&qid=1597809496&sr=8-1)
- [scikit-learn文档](https://scikit-learn.org/stable/user_guide.html)
- [Streamlit文档](https://docs.streamlit.io/en/stable/)
## 计划
