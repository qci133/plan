# 学习笔记

## Book

1. InfoGAN 大概的工作原理没有看懂。为何能得到具有明确物理含义的 code?
2. Super Resolution 如何工作的？

## Video of Machine Learning.
1. ML Lecture 1: Regression - Demo 中改进的梯度下降是什么方法？是不是 Adagrad？为什么效果好了这么多？

2. ML Lecture 10: Convolutional Neural Network 中，Deep Style 如何定义 Hidden Output 与目标图像B的风格相似（correlation 如何定义）？又如何定义与目标图像A的内容相似？

3. ML Lecture 11: Deep Learning 为何有效？Bengio [从理论动机上讲了很多 insight](http://videolectures.net/deeplearning2015_bengio_theoretical_motivations/), [物理解释](https://www.youtube.com/watch?v=5MdSE-N0bxs), [化学解释](https://www.youtube.com/watch?v=kibKHIPbxiU)。

4. ML Lecture 13: Unsupervised Learning - Linear Methods 中，1:29:00 开始的矩阵分解需要仔细再学习一遍，与 Latent semantic analysis (LSA) 很有关系。

5. ML Lecture 14: Unsupervised Learning - Word Embedding 中，总体的原理是什么，如何得到分布式的表示的？0:39:00 开始讲到的 Bag of Word 不考虑词序的缺点，后续提到考虑词序的几个优化模型要看一下。

6. ML Lecture 15: Unsupervised Learning - Neighbor Embedding 中, 06:30 的 LLE 没看懂，`w_{ij}` 是否为点之间的距离？

7. ML Lecture 16: Unsupervised Learning - Auto-encoder 的编码器和解码器的 Layer 是否需要对称？此外，在 00:14:20 的 Text Retrieval 中，网络的输入是什么？还是 Bag of word 吗？那岂不是仍然没有语义信息了？此外，收缩自编码器的收缩有什么作用？

8. ML Lecture 17: Unsupervised Learning - Deep Generative Model (Part I) 中的 PixelRNN 如何做？原理是什么？

9. ML Lecture 18: Unsupervised Learning - Deep Generative Model (Part II) 中的 VAE 数学原理（00:28:00）没有看懂。

10. ML Lecture 19: Transfer Learning 中的 Multitask Learning 模型共用部分 Layer，如何写程序？另外，00:57:57 时提到，将动物的 attributes 用 word embedding 方法处理，但是原始的 word embedding 利用了上下文信息才能构建出来，这些动物图片没有上下文信息，如何构建 word embedding? 另外，假设能构建该 word embedding，01:02:00 时的 loss function 用到了 minmax，如和训练？

11. ML Lecture 24: Structured Learning - Sequence Labeling 中的 HMM 模型，用到的 Vertibi Algorithm 不懂。

12. ML Lecture 26: Recurrent Neeural Network (Part II) 中，00:28:50 提到的影评的感情色彩判断，如何做样本的标签？是不是要整句话读完才能做反向传播？还是每读一个词就能反向传播一次？

