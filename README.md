# BME2003


Task:

* 多试几个pair，搞成高纬度input
* 画各种图，展示filter过程，试着能不能找到频率刺激从功能脑区扩散的样子
* 画热成像图
* else: CNN PCA 多跑几次，计算平均正确率





这个实验的类别应该属于 subsequent memory effects (SMEs)，搜这个关键词可以搜出很多，目的是为了解码记忆过程中的神经活动


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

* 就是说和机器学习任务不同的是需要对结果进行生物学上的分析，许多paper的大部分内容都是在分析



Original matrix: T * Hz * 19
* Hz: 3 period for alpha beta gama
* alpha: Alp * T (period is a continent plot, choose the max one)