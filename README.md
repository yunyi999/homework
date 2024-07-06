# homework

云计算论文代码实现及结果
论文：《More Identifiable yet Equally Performant Transformers for Text Classification》
作者：Rishabh Bhardwaj1, Navonil Majumder1, Soujanya Poria1, Eduard Hovy
url：https://aclanthology.org/2021.acl-long.94/
主要参考：https://github.com/declare-lab/identifiable-transformers
实验环境：python3.9.19+pandas1.1.5,pytoech1.8.1+cu111,torchtext0.9.1
所选数据集： Processed data download https://www.kaggle.com/datasets/tanishqdublish/text-classification-documentation/data

如何运行分类器？
declare@lab:~$ python text_classifier.py -dataset data.csv
注意：随意将data.csv替换为您选择的文本分类问题，无论是情绪、新闻主题、评论等。

data.csv （格式）应该是两列，带有标签的列的标题是“label”，文本是“text”。
