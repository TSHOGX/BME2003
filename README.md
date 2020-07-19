# BME2003

这个实验的类别应该属于 subsequent memory effects (SMEs)，搜这个关键词可以搜出很多，目的是为了解码记忆过程中的神经活动

数据处理过程可以这么搞：


降噪

* 交流电 50Hz
* 头皮肌肉 机电信号
* 电阻和电导 低频
* 调整基准线
* 可以选择去除眨眼转头之类的误差，太麻烦就算了
* 增幅信号
    * CSP 提高两个类别之间的功率差
* 带通滤波 找到范围（问老师


分类

* 特征提取
    * 分离频率，学习振幅差异（Using Single-trial EEG to Predict and Analyze Subsequent Memory）
    * 最好有更多分类价值高和稳定度高的特征
* 分类算法
    * KNN
    * CNN


解释

* 就是说和机器学习任务不同的是需要对结果进行生物学上的分析，许多paper的大部分内容都是在分析，可以问问老师需不需要



else

* theta (3 to 8 Hz), alpha (10 to 14 Hz), beta (16 to 26 Hz), low gamma (28 to 42 Hz) and high gamma (44 to 100 Hz)
* 频率刺激会从功能脑区扩散


问题

滤波之后的明显起伏是测量误差还是可以作为输入特征的区别
我们是否应该
KNN的输入
标签的对应问题


提取3-4秒再做比较

特征：fft之后的y作为一个N维数组，放入KNN做比较，必然会有维度灾难，可以先PCA降维