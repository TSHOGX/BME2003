# BME2003

这个实验的类别应该属于 subsequent memory effects (SMEs)，搜这个关键词可以搜出很多，目的是为了解码记忆过程中的神经活动

数据处理过程可以这么搞：


降噪

* 调整基准线
* 可以选择去除眨眼转头之类的误差，太麻烦就算了
* 增幅信号
    * CSP 提高两个类别之间的功率差
* 带通滤波 找到范围（问老师


分类

* 直接扔到网络中学习
* 分离频率之后直接扔
* 分离频带，学习振幅差异（Using Single-trial EEG to Predict and Analyze Subsequent Memory）


解释

* 就是说和机器学习任务不同的是需要对结果进行生物学上的分析，许多paper的大部分内容都是在分析，可以问问老师需不需要



else

* theta (3 to 8 Hz), alpha (10 to 14 Hz), beta (16 to 26 Hz), low gamma (28 to 42 Hz) and high gamma (44 to 100 Hz)
