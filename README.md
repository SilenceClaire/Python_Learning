###课程作业 

这部分是有关机器学习线性回归闭式解和随机梯度下降两个算法的作业。
其中参考了其他的开源算法代码，线性回归使用的是LIBSVM Data中的Housing数据，包含506个样本，每个样本有13个属性。
链接如下：https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/regression.html#housing
###步骤
###### 线性回归的闭式解相关实验过程：
###### 1.读取实验数据，使用sklearn库的load_svmlight_file函数读取数据。
###### 2.将数据集切分为训练集和验证集，本次实验不切分测试集。使用train_test_split函数切分数据集。
###### 3.选取一个Loss函数，计算训练集的Loss函数值，记为loss。
###### 4.获取闭式解的公式
###### 5.通过闭式解得到参数W的值，更新参数W。
###### 6.在训练集上测试并获得Loss函数值loss_train，在验证集上获得Loss函数值loss_val。
###### 输出Loss，loss_train和loss_val的值。
###### 线性回归和随机梯度下降
###### 1.读取实验数据，使用sklearn库的load_svmlight_file函数读取数据。
###### 2.将数据集切分为训练集和验证集，本次实验不切分测试集。使用train_test_split函数切分数据集。
###### 3.线性模型参数初始化，可以考虑全零初始化，随机初始化或者正态分布初始化。
###### 4.选择Loss函数及对其求导
###### 5.随机选取训练集中的一个样本，求得该样本对Loss函数的梯度G。
###### 6.取梯度G的负方向，记为D。
###### 7.更新模型参数。
###### 8.在训练集上测试并得到Loss函数值loss_train，在验证集上测试并得到Loss函数值loss_val。
###### 9.重复步骤5-8若干次，输出loss_train和loss_val的值。
