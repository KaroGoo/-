# 创青春技术创新


# NLG的6个步骤：

*  内容确定 – Content Determination

*  文本结构 – Text Structuring

* 句子聚合 – Sentence Aggregation

* 语法化 – Lexicalisation

* 参考表达式生成 – Referring Expression Generation|REG

* 语言实现 – Linguistic Realisation

想要深入了解NLG，可以看看这篇文章[《一文看懂自然语言生成 – NLG（6个实现步骤+3个典型应用)》](https://easyai.tech/ai-definition/nlg/)

# 深度学习的 NLP 流程
* 中文语料预处理 4 个步骤（下文详解）
  * [中文分词](https://easyai.tech/ai-definition/tokenization/) – Chinese Word Segmentation
  * [词性标注](https://easyai.tech/ai-definition/part-of-speech/) – Parts of Speech
  * [命名实体识别](https://easyai.tech/ai-definition/ner/) – NER
  * [去除停用词]
* 设计模型
* 模型训练


## 中文*分词*工具

[Hanlp](https://github.com/hankcs/HanLP)

[Stanford 分词](https://github.com/stanfordnlp/CoreNLP)

[ansj 分词器](https://github.com/NLPchina/ansj_seg)

[哈工大 LTP](https://github.com/HIT-SCIR/ltp)

**词性标注工具推荐**


Jieba
“结巴”中文分词：做最好的 Python 中文分词组件，可以进行词性标注。
[Github地址](https://github.com/fxsjy/jieba)

**命名体识别*NER*工具推荐**

 [Hanlp](https://github.com/hankcs/pyhanlp)	HanLP是一系列模型与算法组成的NLP工具包，由大快搜索主导并完全开源，目标是普及自然语言处理在生产环境中的应用。支持命名实体识别。
 
 [Crfsuite](https://github.com/yuquanle/StudyForNLP/blob/master/NLPbasic/NER.ipynb)	可以载入自己的数据集去训练CRF实体识别模型。	
