详见：[TSNE-目前最好的降维方法](https://www.cnblogs.com/bonelee/p/7849867.html)

## 流形学习

流形学习（Manifold Learning）：

<font color="red">假设数据是均匀采样于一个高维欧氏空间中的低维流形，流形学习就是从高维采样数据中恢复低维流形结构，即找到高维空间中的低维流形，并求出相应的嵌入映射，以实现维数约简或者数据可视化。它是从观测到的现象中去寻找事物的本质，找到产生数据的内在规律</font>

简单理解，流形学习就是降维，讲到2或3维就可以将数据可视化，对数据分布有直观了解。

t-SNE算是一种比较新、比较好的一种流形学习方法（降维方法）。由深度学习大牛Hinton和lvdmaaten在2008年提出。

sklearn中提供了十几种流形学习方法，结果各有好坏，t-SNE总体上最优，但计算复杂度也是越高的。且使用PCA初始化，更稳定。

本文是一个书写数字示例代码。

![数字图像](https://github.com/pengpeg/t-SNE/blob/master/temp/digits.png)

![t-SNE降维图像](https://github.com/pengpeg/t-SNE/blob/master/temp/tSNE.png)

