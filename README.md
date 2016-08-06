# 无监督学习论文列表

## 参考来源
- [Most Cited Deep Learning Papers # Unsupervised | Github](https://github.com/terryum/awesome-deep-learning-papers#unsupervised)
- [从OpenAI看深度学习研究前沿 | 知乎专栏](https://zhuanlan.zhihu.com/p/20924929?f3fb8ead20=2fe7890562ecdbf5998ce5a6c0a1ba08)
- [Generative Models | OpenAI博客](https://openai.com/blog/generative-models/)
- [A Path to Unsupervised Learning through Adversarial Networks](https://code.facebook.com/posts/1587249151575490/a-path-to-unsupervised-learning-through-adversarial-networks/)
- [Generative Adversarial Networks（GAN）的现有工作 | 程序媛的日常](http://chuansong.me/n/317902651864)

## 目录
- [生成对抗网络Generative Adversarial Network](#生成对抗网络generative-adversarial-network)
- [变分自编码机Variation Auto Encoder](#变分自编码机Variation Auto Encoder)
- [Pixel RNN类模型](#Pixel RNN类模型)
- [自编码机Auto Encoder](#自编码机Auto Encoder)
- [梯子网络Ladder Network](#梯子网络Ladder Network)
- [其他](#其他)

### 生成对抗网络Generative Adversarial Network

**Generative Adversarial Net**
- Goodfellow的GAN开山之作

**Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks**（[代码](https://github.com/Newmu/dcgan_code)）
- 生成房间图片
- 戴眼镜男人－不戴眼镜男人＋不戴眼镜女人＝戴眼镜女人
- 从一张人脸渐变到另一张人脸

“这篇论文的提出看似并没有很大创新，但其实它的开源代码现在被使用和借鉴的频率最高……这些工程性的突破无疑是更多人选择 DCGAN 这一工作作为 base 的重要原因”

**Improved Techniques for Training GANs**（[代码](https://github.com/openai/improved-gan)）
- 改变架构，解决GAN训练不稳定的问题
- 半监督学习，少量标注样本，效果比Ladder Network还好一些

**InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets**（[代码](https://github.com/openai/InfoGAN)）
- 对representation code空间施加一些要求，使其更具结构化，而非混沌一团
- 结果在representation向量的单个维度上获得了非常好的可解释性，例如渐变一个维度的数值，生成的人脸图谱从“抬头姿态”到“低头姿态”渐变，非常像流形学习里面的一些例子

### 变分自编码机Variation Auto Encoder

### Pixel RNN类模型

### 自编码机Auto Encoder

### 梯子网络Ladder Network

**From neural PCA to deep unsupervised learning**
- 提出Ladder架构，但还未做半监督学习

**Semi-Supervised Learning with Ladder Network**
- 半监督学习，MNIST用100个标注数据达到约99%，CIFAR用4000个标注数据达到约80%

**Deconstructing the Ladder Network Architecture**
- 深入挖掘Ladder Network的原理

### 其他

**Towards Principled Unsupervised Learning**
- 用GAN做半监督学习的论文中所定义的新的损失函数与这篇提出的Output Distribution Matching (ODM) cost有紧密联系
