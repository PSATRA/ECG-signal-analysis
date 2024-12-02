cnn
rnn lstm window
attention transformer multi-head window
dropout
脱敏
降噪 PL 
上次组会CSOT中的内容
互信息，部分卷积层之间
有类别不平衡问题，可以校准/数据增强变换 SMOTE 数据增强 欠采样 过采样（smote）两阶段学习
dropout减轻过拟合
交叉验证
非周期，减少NLP相关
检查多余打印和注释
TODO
傅里叶
early stop
仅特征提取不做标签预测可以使用testing data
多种方法投票：对于每个数据用不同方法预测一次，然后投票，取熵最小的分布填入sample.csv
很多特征 信息增益和决策树/随机森林筛选
cnn和attention顺序
核函数svm

model
363.1 16 20
398.0 256 50
337.2 256 100

减少层数？

rnn非常必要，800/500 且模型收敛快，初期准确率高
cnn: 5e-4 100 256 1/32/64/128 467.6
cnn: 5e-4 100 256 1/32 410.2
cnn: 5e-4 50 256 1/32 502.8
cnn: drop0.5 5e-4 100 256 1/32 