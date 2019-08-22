# Neural-Networks-for-Sentiment-Analysis

数据为来自Rotten Tomatoes的文本影评，将使用两种模型来解决情感文本分析。训练集测试集划分为:80/10/10 train/dev/test。   
使用方法:  
(1)feedforward “deep averaging” network --> 要求acc超过74%  
(2)RNN or CNN-based model --> 要求acc超过76%  

### 斯坦福大学教程:
https://nlp.stanford.edu/sentiment/
传统做法是对句子中positive和negative的词计数来得到句子情感分类，但现在用Recursive Neural Network来对整个句子进行分析。
#### 论文:
[Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank](https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)  
数据为由215,154个phase组成的parse trees的11,855个句子,label:1 正向; 0 负向  
