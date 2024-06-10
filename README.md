# CIBHash
本仓库是机器学习课程期末作业的复现代码，包含了 Cifar10 和 NUSWIDE 两个数据集的处理代码。其中前者代码是官方Github仓库提供的；由于官方未提供NUSWIDE数据集的处理代码，所以此数据集的处理代码是我们自己编写的，详细处理逻辑请参考实验报告PDF.

我们还替换了`forward()`的激活函数，将ST直通估计器更换为`SoftSignFunction`时观察到模型准确率有不少提升。

为了方便在Colab上运行，我们将py文件转换成了notebook文件。



参考：

1. https://github.com/zexuanqiu/CIBHash
2. https://github.com/Huenao/DPCHash_Baselines
