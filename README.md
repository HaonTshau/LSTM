# tensorflow版本

如果在tf2下使用了tf1的API。
解决方式:
使用

import tensorflow.compat.v1 as tf <br />
tf.disable_v2_behavior()

替换

import tensorflow as tf


# conda
conda create -n lstm python=3.7

# 依赖库
安装python的依赖库： <br />
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple [package]
- tensorflow==2.0.0
- numpy==1.19.3
- pandas==1.1.4
- requests==2.24.0
- beautifulsoup4=4.7.1  (bs4)


# 数据采集：
collect_csv     :   爬取数据到csv，生成ssq.txt





# 数据清洗：
process         :   处理文件ssq.txt,对数据进行清洗预览功能;

# 模型创建（模型训练和生成）：
LSTM_train      :   训练数据
（通过修改status的值去训练哪个球的模型；事先这里七个球都训练好了，后续觉得哪个球的准确率不高，可以自行修改模型）
模型预测：
LSTM_pre        :   模型预测

最终生成的data_pre.csv为结果输出；






如果实现财富自由，请酌情打赏一下作者，作者很穷的。

 ![image](ef7421254938d28b324734b6d130eb1.jpg) 
 ![image](b541dae4f200847f33c04c25fdc3912.jpg)


