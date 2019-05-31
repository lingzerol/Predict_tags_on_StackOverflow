# Predict_tags_on_StackOverflow
从StackOverflow中获取标题和标签，并对标题进行TF-IDF的转换，转换成为一个向量，并带入神经网络中进行训练，并预测对应标题的标签。

功能
----
将会采用sklearn中的OneVsRestClassifier和LogisticRegression来建立神经网络，将转化后的数据，用于训练模型，并使用sklearn中的模型评估函数对test数据及逆行评估，并得到准确率。

程序效果
-------
>roc曲线  
>[!Image](https://raw.githubusercontent.com/lingzerol/Predict_tags_on_StackOverflow/master/Program_performance/roc.png)

>准确率
>[!Image](https://raw.githubusercontent.com/lingzerol/Predict_tags_on_StackOverflow/master/Program_performance/accuracy.PNG)