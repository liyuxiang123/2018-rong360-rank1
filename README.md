# 2018-rong360-rank1

具体答辩PPT见：
https://zhuanlan.zhihu.com/p/51927257

融360——多金融场景下的模型训练 top1解决方案
======================================

1)	平台环境：linux Ubuntu 16.04
2)	编程语言及版本

	Python 3.6.3
	
	Catboost 0.9.1.1
	
	Lightgbm 2.1.1
	
	Numpy 1.14.2
	
	Pandas 0.23.0
	
	scikit-learn 0.19.1
	
	scipy 0.19.1
	
	xgboost 0.72

3)  因数据量太大只提交了代码，复现请将数据拷贝到相应文件夹下.
4)  依次执行model1.py、model2.py、融合.py就可以在result_sub得到最终的result.txt结果。
5)  fee.txt 这个文本是统计了不同特征下的nunique,我们自主设置阈值决定类别和连续特征的阈值。
