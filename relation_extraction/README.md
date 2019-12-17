# Repo-SVAIGBA
Repository of SVAIGBA


This is the paper list and conclustion of Pengyuan Zeng.

The important read paper is concluded here.

1.ACL 2019: Chinese Relation Extraction with Multi-Grained Information and External Linguistic Knowledge
Authors: Ziran Li1;2 , Ning Ding1;2, Zhiyuan Liu2;3;4, Hai-Tao Zheng1;2y , Ying Shen5
Organization: 1Tsinghua Shenzhen International Graduate School, Tsinghua University

Code and Datasets: https://github.com/thunlp/Chinese_NRE.

Conclusion of this article: A good baseline for none-BERT based model. Results runned on our machine can be viewed here: https://docs.qq.com/doc/DWWxNakNFQXJucm5Z

Aim: 主要解决中文任务中的不同分词方式造成多义，和词本身的多义问题

Innovation  1:字词混合嵌入：对于在词表中的词，其末尾的字向量嵌入由字和词向量加权组成，权重由网络训练得到。目的是更好地完成基于关系抽取的分词任务

Innovation  2:多义词混合嵌入：如果词表对应不止一个sense，则把所有词的向量都考虑进来，加权组成，权重由网络训练得到。目的是区分多义。





2.ACL 2019: Exploiting Entity BIO Tag Embeddings and Multi-task Learning for Relation Extraction with Imbalanced Data
Authors: Wei Ye1*y, Bo Li1;3*, Rui Xie1;2, Zhonghao Sheng1;2, Long Chen1;2 and Shikun Zhang1
Organization: 1National Engineering Research Center for Software Engineering, Peking University

Code and Datasets: not available

Conclusion of this article: A good baseline for none-BERT based model.

Aim: 主要解决数据集中正负例不平衡的问题（无关实体对>>有关实体对）

INNOVATIONS	 1：除了分类任务，同时额外训练一个二分类模型，判断是否存在关系：原因：在ACE 2005中文集中,“ there are 4.9 entities and 1.34 relation mentions in a sentence on average. ”，负例与正例比为20：1，即无关实体对 远多于 有关实体对，导致在错误率上FN占比例>60%。

INNOVATIONS  2：加入BIO向量特征，即实体的边界。并阐述了其在不同模型中的通用性，与相对位置向量作用类似。





3.ACL 2019: Entity-Relation Extraction as Multi-turn Question Answering
Authors: Xiaoya Li, Fan Yin, Zijun Sun, Xiayu Li , Arianna Yuan;~, Duo Chai, Mingxin Zhou and Jiwei Li;|
Organization: School of Information, Renmin University of China

Code: not available

Datasets: ACE04, ACE05 and CoNLL04 datasets. ACE05 is available, CoNLL04路径：/data/checan/RE/multihead/data/CoNLL04

Conclusion of this article: Use multi-turn Q&A mode to extract multi-entities relationship. Such task is specially trained for certain goal. such as in RESUME. 

4.ACL 2019: Neural Relation Extraction for Knowledge Base Enrichment (基于维基语料库的英文关系抽取）
Authors: Bayu Distiawan Trisedya1, Gerhard Weikum2, Jianzhong Qi1, Rui Zhang1
Organization:The University of Melbourne, Australia

Code and Datasets: http://www.ruizhang.info/GKB/gkb.htm. 

Conclusion of this article: 用文法过滤的方法去除了远监督数据集中的无用语料。 直接抽出三元组。


#.ACL 2019: On Evaluating Embedding Models for Knowledge Base Completion
Authors:Yanjie Wang et.al,
Organizations: University of Mannheim Mannheim, Germany

Code: not available,
