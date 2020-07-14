| Datasets       |         R-1          |         R-2          |         R-L          |  WMD  | BERT-S |                           Methods                            |
| -------------- | :------------------: | :------------------: | :------------------: | :---: | :----: | :----------------------------------------------------------: |
| CNN/DM         | 43.77<br />**44.41** | 20.85<br />**20.86** | **40.67**<br />40.55 |   -   |   -    | [DISCOBERT W.GR&GC](./paper/2020.acl-main.451.pdf)<br />[MATCHSUM (ROBERTa-base)](./paper/2004.08795.pdf) |
| Gigaword       |        40.89         |        19.11         |        37.60         | 34.39 | 62.74  |              [best-abs](./paper/1911.10390.pdf)              |
| DUC2004        |        31.00         |        11.11         |        26.94         | 26.71 | 57.99  |             [SemSUM](./paper/AAAI-JinH.7203.pdf)             |
| NewSroom       |        45.93         |        24.14         |        42.51         |   -   | 66.20  |              [best-abs](./paper/1911.10390.pdf)              |
| WEBMERGE       |                      |                      |                      |       |        |                                                              |
| XSUM           |        24.86         |         4.58         |        18.31         |   -   |   -    |        [MATCHSUM (Sel = 1,2)](./paper/2004.08795.pdf)        |
| New York Times |        50.00         |        30.38         |        42.70         |   -   |   -    |      [DISCOBERT W.GR&GC](./paper/2020.acl-main.451.pdf)      |
| MSR-ATC        |        33.82         |        17.08         |        30.62         | 17.14 | 56.19  |             [SemSUM](./paper/AAAI-JinH.7203.pdf)             |
| Reddit         |        25.09         |         6.17         |        20.13         |   -   |   -    |        [MATCHSUM (Sel = 1,2)](./paper/2004.08795.pdf)        |



## 2020

>#### SIGIR 2020: [Large Scale Abstractive Multi-Review Summarization (LSARS) via Aspect Alignment](./paper/AAAI-LiH.902.pdf)  
>> Author: Haoran Li, Peng Yuan, Song Xu, Youzheng Wu, Xiaodong He, Bowen Zhou


>#### SIGIR 2020: [Evaluation of Cross Domain Text Summarization](./paper/SIGIR2020_Submission_Liam.pdf)  
>> Author: Liam Scanlon, Shiwei Zhang, Xiuzhen Zhang, Mark Sanderson
>> Dataset: CNN/DailyMail
>> Score: 
>>
>> | Model                           |  R-1  |  R-2  |  R-L  |
>> | :------------------------------ | :---: | :---: | :---: |
>> | Pointer Gernerator              | 39.53 | 17.28 | 36.38 |
>> | Inconsistency Loss(IL)          | 40.68 | 17.97 | 37.13 |
>> | rnn-ext + abs + RL + rerank(RL) | 40.88 | 17.80 | 38.54 |


>#### SIGIR 2020: [Multi-Modal Summary Generation using Multi-Objective Optimization](./paper/2005.09252.pdf)  
>> Author: Anubhav Jangra, Sriparna Saha, Mohammad Hasanuzzaman, Adam Jatowt
>> Dataset: Private Dataset
>> Score:


>#### AAAI 2020: [Aspect-Aware Multimodal Summarization for Chinese E-Commerce Products](./paper/AAAI-LiH.902.pdf)  
>> Author: Haoran Li, Peng Yuan, Song Xu, Youzheng Wu, Xiaodong He, Bowen Zhou
>>
>> Dataset: CEPSUM (A new dataset from JD.com)
>> Score:  
>>
>> | Methods                 | Home Appliances<br>R-1        R-2        R-L | Clothing<br>R-1        R-2        R-L | Cases&Bags<br>R-1        R-2        R-L |
>> | :---------------------- | :------------------------------------------: | :-----------------------------------: | :-------------------------------------: |
>> | MMPG                    |          32.88     11.88      21.96          |        30.73    10.29    21.25        |         32.69    11.78    22.27         |
>> | MMPG+Aspect             |          33.97     12.43      22.21          |        31.81    10.87    21.32        |         33.67    12.44    22.31         |
>> | MMPG+Aspect+Consistency |          34.36     12.52      22.35          |        31.93    11.09    21.54        |         33.78    12.51    22.43         |

> #### AAAI 2020: [Document Summarization with VHTM:Variational Hierarchical Topic-Aware Mechanism](./paper/AAAI-FuX.1070.pdf)  
> > Author: Xiyan Fu, Jun Wang, Jinghan Zhang, Jinmao Wei, Zhenglu Yang 
> > Dataset: CNN/DM
> > Score:
>> | Model |  R-1  |  R-2  |  R-L  |
>> | :---: | :---: | :---: | :---: |
>> | VHTM  | 40.57 | 18.05 | 37.18 |
>>

>#### AAAI 2020: [TemPEST: Soft Template-based Personalized EDM Subject Generation Through Collaborative Summarization](./paper/AAAI-ChenY.1087.pdf)  
>> Author: Yu-Hsiu Chen, Pin-Yu Chen, Hong-Han Shuai, Wen-Chih Peng
>> Dataset: KKday (A new dataset from KKday.com)
>> Score:
>>
>> | Models |  B-1  |  B-2  |  B-3  | B-4  |  R-1  |  R-L  |
>> | :---: | :---: | :---: | :---: |:---: | :---: | :---: |
>> | TemPEST  | 24.36 | 5.31 | 3.15 |1.97 | 65.47 | 8.33 |

>#### AAAI 2020: [Multimodal Summarization with Guidance of Multimodal Reference](./paper/AAAI-ZhuJ.1133.pdf)  
>> Author: Junnan Zhu, Yu Zhou, Jiajun Zhang, Haoran Li, Chengqing Zong, hangliang Li 
>> Dataset: MSMO
>> Score:
>>
>> | Models      | R-1   | R-2   | R-L   | M_sim | IP    |  IPR  | IPO   | MR    | MRR   | MRO   | AE    | AE++  |
>> | ----------- | ----- | ----- | ----- | ----- | ----- | :---: | ----- | ----- | ----- | ----- | ----- | ----- |
>> | MOF(PR_ENC) | 41.05 | 18.29 | 37.74 | 26.23 | 62.63 | 67.85 | -     | 57.13 | 59.26 | -     | 66.52 | 68.68 |
>> | MOF(PR_DEC) | 41.20 | 18.33 | 37.80 | 26.38 | 65.45 | 68.62 | -     | 58.38 | 59.58 | -     | 67.02 | 69.66 |
>> | MOF(OR_ENC) | 41.16 | 18.35 | 37.85 | 26.15 | 63.55 |   -   | 68.76 | 57.66 | -     | 59.55 | 66.69 | 69.04 |
>> | MOF(OR_DEC) | 40.95 | 18.12 | 37.75 | 26.30 | 64.00 |   -   | 71.78 | 58.16 | -     | 60.58 | 66.76 | 69.24 |

>#### AAAI 2020: [Keywords-Guided Abstractive Sentence Summarization](./paper/AAAI-LiH.1493.pdf)  
>> Author: Haoran Li, Junnan Zhu, Jiajun Zhang, Chengqing Zong, Xiaodong He 
>> Github: None
>> Dataset: English Gigaword dataset
>> Score:
>>
>> | Method                                                       | R-1                         | R-2                         | R-L                         |
>> | ------------------------------------------------------------ | --------------------------- | --------------------------- | --------------------------- |
>> | S2S-Sentence                                                 | 45.09                       | 23.58                       | 42.37                       |
>> | S2S-Keywords                                                 | 44.85                       | 20.54                       | 41.61                       |
>> | S2S-Sentence&Keywords                                        | 46.14                       | 24.07                       | 43.30                       |
>> | Self-Selective Concat<br />Self-Selective Gated<br />Self-Selective Hier | 46.23<br />46.44<br />46.51 | 24.13<br />24.31<br />24.32 | 43.26<br />43.44<br />43.45 |
>> | Keywords-Selective Concat<br />Keywords-Selective Gated<br />Keywords-Selective Hier | 46.32<br />46.70<br />46.72 | 24.11<br />24.48<br />24.50 | 43.38<br />43.59<br />43.81 |
>> | Co-Selective Concat<br />Co-Selective Gated<br />Co-Selective Hier | 46.53<br />46.71<br />46.80 | 24.15<br />24.53<br />27.75 | 43.24<br />43.63<br />43.83 |
>> | Co-Selective Concat + PG<br />Co-Selective Gated + PG<br />Co-Selective Hier+ PG | 46.68<br />46.91<br />46.93 | 24.33<br />24.61<br />24.83 | 43.31<br />43.71<br />43.92 |
>> | Co-Selective Concat + DuakPG<br />Co-Selective Gated+ DuakPG<br />Co-Selective Hier+ DuakPG | 47.05<br />47.13<br />47.14 | 24.39<br />24.87<br />25.06 | 43.77<br />44.34<br />44.39 |

>#### AAAI 2020: [Weakly-Supervised Opinion Summarization by Leveraging External Information](./paper/1911.09844.pdf)  
>> Author: Chao Zhao Snigdha Chaturvedi 
>> Dataset: OPOSUM
>> Score:
>>
>> | Methods       | R-1  | R-2  |
>> | ------------- | :--: | :--: |
>> | ASPMENSUM     | 46.6 | 25.7 |
>> | w/o filtering | 48.0 | 28.7 |
>> | w/o Relevance | 41.5 | 20.5 |
>> | w/o Sentiment | 40.5 | 18.2 |
>> | w/o ILP       | 46.2 | 25.1 |
>>
>> 

>#### AAAI 2020: [Be Relevant, Non-redundant, Timely: Deep Reinforcement Learning for Real-time Event Summarization](./paper/AAAI-YangM.3953.pdf)  
>> Author: Min Yang, Chengming Li, Fei Sun, Zhou Zhao, Ying Shen, Chenglin Wu 
>> Dataset: TREC-RTS-16, TREC-RTS-17
>> Scores: 
>> Event summarization results on TREC-RTS-16
>> | Method    | EG-0  | nCG-0 | EG-1  | nCG-1 | GMP    | Latency |
>> | --------- | ----- | ----- | ----- | ----- | ------ | ------- |
>> | DRES      | 0.087 | 0.102 | 0.308 | 0.315 | -0.080 | 72264   |
>> | DRES+Bert | 0.089 | 0.105 | 0.306 | 0.311 | -0.078 | 71983   |
>>
>> Event summarization results on TREC-RTS-17
>> | Method    | EG-0  | nCG-0 | EG-1  | nCG-1 | GMP    | Latency |
>> | --------- | ----- | ----- | ----- | ----- | ------ | ------- |
>> | DRES      | 0.086 | 0.075 | 0.302 | 0.278 | -0.056 | 35319   |
>> | DRES+Bert | 0.085 | 0.077 | 0.298 | 0.283 | -0.061 | 35362   |

>#### AAAI 2020: [MultiSumm: Towards a Unified Model for Multi-Lingual Abstractive Summarization](./paper/AAAI-CaoY.7050.pdf)  
>> Author: Yue Cao, Xiaojun Wan, Jin-ge Yao,Dian Yu
>> Dataset: A multi-lingual Dataset ( Monolingual Dataset, Machine Translation Dataset, Gigaword Dataset and LCSTS dataset, Dataset Construction for Bosnian and Croatian and contained)
>> Scores:
>>
>> | Method    | Metric  | Rich-Resource<br />                         De              En              Es               Fr              Zh | Low-Resource<br />                   Bs           Hr |
>> | --------- | ------- | ------------------------------------------------------------ | ---------------------------------------------------- |
>> | MultiSumm | Rouge-1 | 43.41        36.87         31.18        27.20         35.71  | 22.47     23.04                                      |
>> | MultiSumm | Rouge-2 | 21.86        17.96         12.24        11.78         21.86  | 8.35       8.75                                      |
>> | MultiSumm | Rouge-L | 39.77        33.07         26.22        23.57         33.61  | 19.42     19.63                                      |
>>

>#### AAAI 2020: [SemSUM: Semantic Dependency Guided Neural Abstractive Summarization](./paper/AAAI-JinH.7203.pdf)  
>> Author: Hanqi Jin, Tianming Wang,Xiaojun Wan
>> Dataset: Gigaword, DUC2004, MSR-ATC
>> Score:
>>
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the Gigaword test set
>>
>> | Model                             | RG-1  | RG-2  | RG-L  | WMD   | BERT  |
>> | --------------------------------- | ----- | ----- | ----- | ----- | ----- |
>> | MASS(Song et al. 2019)            | 38.73 | 19.71 | 35.96 | 34.28 | 61.56 |
>> | BiSET(Wang, Quan, and Wang 2019b) | 39.11 | 19.78 | 16.87 | 33.79 | 61.24 |
>> | **SemSUM**                        | 38.89 | 19.75 | 36.09 | 34.39 | 61.56 |
>>
>> ROUGE recall, WMD unigram and BERTScore F1 evaluation on the DUC2004 test set
>>
>> | Model      | RG-1  | RG-2  | RG-L  | WMD   | BERT  |
>> | ---------- | ----- | ----- | ----- | ----- | ----- |
>> | **SemSUM** | 31.00 | 11.11 | 26.94 | 26.71 | 57.99 |
>> 
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the MSR-ATC test set
>>
>> | Model      | RG-1  | RG-2  | RG-L  | WMD   | BERT  |
>> | ---------- | ----- | ----- | ----- | ----- | ----- |
>> | **SemSUM** | 33.82 | 17.08 | 30.62 | 17.14 | 56.19 |

>#### AAAI 2020: [Controlling the Amount of Verbatim Copying in Abstractive Summarization](./paper/1911.10390.pdf)  
>> Author: Kaiqiang Song, Bingqing Wang,Zhe Feng, Liu Ren, Fei Liu
>> Dataset: Gigaword dataset, Newsroom dataset
>> Score:
>> Summarization results on the Gigaword test set
>>
>> | Model                  | RG-1  | RG-2  | RG-L  | Bert-S |
>> | ---------------------- | ----- | ----- | ----- | ------ |
>> | Beam + BPNorm (c=0.55) | 39.19 | 20.38 | 36.69 | 61.46  |
>> | Beam + SBWR(r=0.25)    | 39.08 | 20.47 | 36.68 | 61.51  |
<<<<<<< HEAD
>> 
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the NewSroom test set
=======
>>
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the Gigaword test set
>>>>>>> c76cea841924194b18283bc2ea242b1a588e4cee
>>
>> | Model    | RG-1  | RG-2  | RG-L  | Bert-S |
>> | -------- | ----- | ----- | ----- | ------ |
>> | pure-ext | 43.21 | 21.81 | 40.05 | 63.68  |
>> | best-abs | 45.93 | 24.14 | 42.51 | 66.20  |
>>
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the Gigaword test set
>>
>> | Model    | RG-1  | RG-2  | RG-L  | Bert-S |
>> | -------- | ----- | ----- | ----- | ------ |
>> | pure-ext | 39.44 | 19.32 | 36.10 | 61.00  |
>> | best-abs | 40.89 | 19.11 | 37.60 | 62.74  |


>#### AAAI 2020: [Joint Parsing and Generation for Abstractive Summarization](./paper/1911.10389.pdf)  
>> Author: Kaiqiang Song, Logan Lebanoff, Qipeng Guo,Xipeng Qiu, Xiangyang Xue, Chen Li, Dong Yu, Fei Liu
>> Dataset: Gigaword, NewSroom, CNN/DM, WEBMERGE
>> Scores:
>>
>> Summarization on Gigaword dataset
>>
>> | Methods       | R-1   | R-2   | R-L   |
>> | ------------- | ----- | ----- | ----- |
>> | GenParse-Base | 35.21 | 17.10 | 32.88 |
>> | GenParse-Full | 36.61 | 18.85 | 34.33 |
>>
>> Summarization results on Newsroom, CNN/DM-R, and WebMerge datasets.
>>
>> | Dataset  | System                           | Rouge-1<br />R            R              F           | Rouge-2<br />P                R           F          | Rouge-L<br />R              R            F           |
>> | -------- | -------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
>> | NEWSROOM | GenParse-Base<br />GenParse-Full | 41.88    36.00    37.65<br />45.17    39.77    41.06 | 20.04    16.90    17.70<br />23.48    20.17    20.89 | 38.73    33.33    34.84<br />41.82    36.81    38.01 |
>> | CNN/DM   | GenParse-Base<br />GenParse-Full | 48.24    46.52    46.46<br />50.15    53.11    50.49 | 31.44    29.62    29.82<br />34.51    35.99    34.38 | 45.43    43.72    43.71<br />47.33    50.00    47.60 |
>> | WEBMERGE | GenParse-Base<br />GenParse-Full | 37.79    35.86    36.23<br />62.26    54.69    57.24 | 12.63    11.99    12.09<br />32.10    28.41    29.58 | 28.87    27.59    27.77<br />48.13    42.54    44.41 |
>>


>#### AAAI 2020: [Copy or Rewrite: Hybrid Summarization withHierarchical Reinforcement Learning](./paper/AAAI-XiaoL.9028.pdf)  
>> Author: Liqiang Xiao, Lu Wang, Hao He, Yaohui Jin
>> Datasets: CNN/DM
>> Scores:
>>
>> | Models                                    |  R-1  |  R-2  |  R-L  | METEOR |
>> | ----------------------------------------- | :---: | :---: | :---: | :----: |
>> | Rewrite + EXT-RL                          | 40.73 | 17.85 | 38.26 | 19.05  |
>> | Copy + EXT-RL                             | 41.48 | 18.75 | 37.79 | 21.71  |
>> | Copy/Rewrite + Unbalanced Marker + EXT-RL | 42.10 | 18.91 | 38.87 | 20.69  |
>> | Copy/Rewrite + History + EXT-RL           | 41.98 | 18.96 | 38.83 | 21.91  |
>> | Copy/Rewrite + History + INDEPENDENT-RL   | 42.21 | 18.91 | 38.94 | 21.16  |
>> | Copy/Rewrite + History + HRL              | 42.46 | 19.10 | 39.19 | 21.88  |
>> | Copy/Rewrite + History + HRL + BERT       | 42.92 | 19.43 | 39.35 | 22.12  |
>>

>#### AAAI 2020: [Convolutional Hierarchical Attention Network for Query-Focused Video Summarization](./paper/2002.03740.pdf)  
>> Author: Shuwen Xiao, Zhou Zhao, Zijian Zhang, Xiaohui Yan, Min Yang

>#### AAAI 2020: [Narrative Planning Model Acquisition from Text Summaries and Descriptions](./paper/AAAI-HaytonT.6762.pdf)  
>> Author: Thomas Hayton, Julie Porteous, Joao F. Ferreira, Alan Lindsay

>#### ACL 2020: [Asking and Answering Questions to Evaluate the Factual Consistency of Summaries](./paper/2004.04228.pdf)  
>> Author: Paulus, Romain, Caiming Xiong, and Richard Socher 
>> Datasets: CNN/DM, XSUM
>> Scores: 
>>
>> | Metric    | CNN/DM | XSUM  |
>> | --------- | ------ | ----- |
>> | ROUGE-1   | 28.74  | 13.22 |
>> | ROUGE-2   | 17.72  | 8.95  |
>> | ROUGE-L   | 24.09  | 8.86  |
>> | METEOR    | 26.65  | 10.03 |
>> | BLEU-1    | 29.68  | 11.76 |
>> | BLEU-2    | 26.65  | 11.68 |
>> | BLEU-3    | 23.96  | 8.41  |
>> | BLEU-4    | 21.45  | 5.64  |
>> | BERTScore | 27.63  | 2.51  |
>> | QAGS      | 54.53  | 17.49 |

>#### ACL 2020: [Attend, Translate and Summarize: An Efficient Method for Neural Cross-Lingual Summarization](./paper/2020.acl-main.121.pdf)  
>> Author: Junnan Zhu, Yu Zhou, Jiajun Zhang and Chengqing Zong
>> Datasets: En2ZhSum, Zh2EnSum
>> Score: 
>> Rouge F1 Scores and MoverScore scores on Zh2EnSum test set
>> | Methods | Model | R-1   | R-2   | R-L   | MVS   |
>> | ------- | ----- | ----- | ----- | ----- | ----- |
>> | ATS     | Naive | 40.40 | 23.82 | 36.63 | 21.86 |
>> | ATS     | Equal | 40.10 | 23.36 | 36.22 | 21.41 |
>> | ATS     | Adapt | 40.86 | 24.12 | 36.97 | 22.15 |
>>
>> Rouge F1 Scores and MoverScore scores on En2ZhSum test set
<<<<<<< HEAD
>> 
=======
>>
>>>>>>> c76cea841924194b18283bc2ea242b1a588e4cee
>> | Methods | Model | R-1   | R-2   | R-L   |
>> | ------- | ----- | ----- | ----- | ----- |
>> | ATS     | Naive | 40.19 | 21.84 | 36.46 |
>> | ATS     | Equal | 39.98 | 21.63 | 36.29 |
>> | ATS     | Adapt | 40.47 | 22.21 | 36.89 |

>#### ACL 2020: [Discourse-Aware Neural Extractive Text Summarization](./paper/2020.acl-main.451.pdf)  
>> Author: Jiacheng Xu, Zhe Gan, Yu Cheng and Jingjing Liu
>> Datasets: CNN/DM, New York Times
>> Scores:
>>
>> Results on the test set of the CNNDM dataset.
>> | Methods           | R-1   | R-2   | R-L   |
>> | ----------------- | ----- | ----- | ----- |
>> | DISCOBERT W.GC    | 43.58 | 20.64 | 40.42 |
>> | DISCOBERT W.GR    | 43.68 | 20.71 | 40.54 |
>> | DISCOBERT W.GR&GC | 43.77 | 20.85 | 40.67 |
>>
>> Results on the test set of the NYT dataset
>> 
>> | Methods           |  R-1  |  R-2  |  R-L  |
>> | ----------------- | :---: | :---: | :---: |
>> | DISCOBERT W.GC    | 49.79 | 30.18 | 42.48 |
>> | DISCOBERT W.GR    | 49.86 | 30.25 | 42.55 |
>> | DISCOBERT W.GR&GC | 50.00 | 30.38 | 42.70 |
>>

>#### ACL 2020: [Discrete Optimization for Unsupervised Sentence Summarization with Word-Level Extraction](./paper/2005.01791.pdf)  
>> Author: Raphael Schumann, Lili Mou, Yao Lu, Olga Vechtomova and Katja Markert
>> Datasets: DUC2004, Gigaword
>> Scores:
>>
>> Results for headline generation on the Gigaword test set.
>>
>> |           Model            |      Data       | Len D |  R-1  |  R-2  |  R-L  |
>> | :------------------------: | :-------------: | :---: | :---: | :---: | :---: |
>> |        hc_article_8        |     article     |   8   | 23.09 | 7.50  | 21.29 |
>> |         hc_title_8         |      title      |   8   | 26.32 | 9.63  | 24.19 |
>> |       hc_article_10        |     article     |  10   | 24.44 | 8.01  | 22.21 |
>> | hc_article_10 + twitter_10 | article+twitter |  10   | 28.26 | 10.42 | 25.43 |
>> |        hc_title_10         |      title      |  10   | 27.52 | 10.27 | 24.91 |
>> |   hc_title_10+billon_10    |  title+billon   |  10   | 28.80 | 10.66 | 25.82 |
>> |       hc_article_50p       |     article     |  50%  | 25.58 | 8.44  | 22.66 |
>> |        hc_title_50p        |      title      |  50%  | 27.05 | 9.75  | 23.89 |
>> 
>> Results for headline generation on the DUC2004 test set.
>>
>> |         Model         |  R-1  |  R-2  |  R-L  |
>> | :-------------------: | :---: | :---: | :---: |
>> | HC_article_13 |24.21 | 6.63 | 21.24 |
>> | HC_title_13 | 26.04 | 8.06 | 22.90 |
>> | HC_title + twitter_13 | 27.41 | 8.76 | 23.89 |

>#### ACL 2020: [Examining the State-of-the-Art in News Timeline Summarization](./paper/2005.10107.pdf)  
>> Author: Demian Gholipour Ghalandari and Georgiana Ifrim
>> Datasets: T17 Dataset, CRISIS Dataset, ENTITIES Dataset
>> Scores:
>>
>> |                  | T-17      | T-17 | T-17 | CRISIS | CRISIS | CRISIS | ENTITIES | ENTITIES | ENTITIES |
>> | :--------------: | :----------: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
>> | Method           | AR1-F | AR2-F | Date-F1 | AR1-F | AR2-F | Date-F1 | AR1-F | AR2-F | Date-F1 |
>> | DATEWISE         | 0.12 | 0.035 | 0.544 | 0.089 | 0.026 | 0.295 | 0.057 | 0.017 | 0.205 |
>> | DATEWISE(titles) | - | - | - | 0.072 | 0.016 | 0.287 | 0.057 | 0.017 | 0.194 |
>>

>#### ACL 2020: [Extractive Summarization as Text Matching](./paper/2004.08795.pdf)  
>> Author: Ming Zhong, Pengfei Liu, Yiran Chen, Danqing Wang, Xipeng Qiu and Xuanjing Huang
>> Datasets: CNN/DM, Reddit, XSUM, WikiHow, PubMed and Multi-News
>> Scores: 
>>
>> Results on CNN/DM test set
>>
>> | Model                   | R-1   | R-2   | R-L   |
>> | ----------------------- | ----- | ----- | ----- |
>> | BERT EXT                | 42.73 | 20.13 | 39.20 |
>> | BERT EXT + Tri-Blocking | 43.18 | 20.16 | 39.56 |
>> | MATCHSUM (BERT-base)    | 44.22 | 20.62 | 40.38 |
>> | MATCHSUM (ROBERTa-base) | 44.41 | 20.86 | 40.55 |
>>
>> Results on test sets of Reddit 
>>
>> | Model                | R-1   | R-2  | R-L   |
>> | -------------------- | ----- | ---- | ----- |
>> | BERT EXT (num = 1)   | 21.99 | 5.21 | 16.99 |
>> | BERT EXT (num = 2)   | 23.86 | 5.85 | 19.11 |
>> | MATCHSUM (Sel = 1)   | 22.87 | 5.15 | 17.40 |
>> | MATCHSUM (Sel = 2)   | 24.90 | 5.91 | 20.03 |
>> | MATCHSUM (Sel = 1,2) | 25.09 | 6.17 | 20.13 |
>>
>> Results on test sets of XSUM
>>
>> | Model                | R-1   | R-2  | R-L   |
>> | -------------------- | ----- | ---- | ----- |
>> | BERT EXT (num = 1)   | 22.53 | 4.36 | 16.23 |
>> | BERT EXT (num = 2)   | 22.86 | 4.48 | 17.16 |
>> | MATCHSUM (Sel = 1)   | 23.35 | 4.46 | 16.71 |
>> | MATCHSUM (Sel = 2)   | 24.48 | 4.58 | 18.31 |
>> | MATCHSUM (Sel = 1,2) | 24.86 | 4.66 | 18.41 |
>>
>> Results on test sets of WikiHow, PubMed and Multi-News
>>
>> ​																						 			WikiHow	                                          PubMed                                         Multi- News
>>
>> | Model                | R-1   | R-2  | R-L   | R-1   | R-2   | R-L   | R-1   | R-2   | R-1   |
>> | -------------------- | ----- | ---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
>> | BERTEXT              | 30.31 | 8.71 | 28.24 | 41.05 | 14.88 | 36.57 | 45.80 | 16.42 | 41.53 |
>> | + 3gram-Blocking     | 30.37 | 8.45 | 28.28 | 38.81 | 13.62 | 34.52 | 44.94 | 15.47 | 40.63 |
>> | + 4gram-Blocking     | 30.40 | 8.67 | 28.32 | 40.29 | 14.37 | 35.88 | 45.86 | 16.23 | 41.57 |
>> | MATCHSUM (BERT-base) | 31.85 | 8.98 | 29.58 | 41.21 | 14.91 | 36.75 | 46.20 | 16.51 | 41.89 |
>>
>> 

>#### ACL 2020: [Facet-Aware Evaluation for Extractive Summarization](./paper/1908.10383.pdf)  
>> Author: Yuning Mao, Liyuan Liu, Qi Zhu, Xiang Ren and Jiawei Han
>> Datasets: CNN/DM
>> Scores:
>>
>> Performance comparison of extractive methods under ROUGE F1 and Facet-Aware Recall (FAR).
>>
>> | Method        | R-1  | R-2  | R-L  | FAR  |
>> | ------------- | ---- | ---- | ---- | ---- |
>> | Lead-3        | 41.9 | 19.6 | 34.8 | 50.6 |
>> | FastRL(E)     | 41.6 | 20.3 | 35.5 | 50.8 |
>> | BanditSum     | 42.7 | 20.2 | 35.8 | 44.7 |
>> | NeuSum        | 42.7 | 22.1 | 36.4 | 51.2 |
>> | Refresh       | 42.8 | 20.3 | 39.3 | 51.3 |
>> | UnifiedSum(E) | 42.6 | 20.1 | 35.5 | 54.8 |
>> | Oracle        | 53.8 | 32.1 | 48.1 | 84.8 |
>>
>> ROUGE-1 F1 of extractive and abstractive methods on noisy (N), low abstraction (L), high abstraction (H), and high quality (L + H) samples
>>
>> The first 6 methods belong to Extractive Summarization, and the rest are Abstractive.
>>
>> | Method          | N    | L    | H    | L+H  |
>> | --------------- | ---- | ---- | ---- | ---- |
>> | Lead-3          | 34.1 | 41.9 | 24.9 | 38.9 |
>> | FastRL(E)       | 33.5 | 41.6 | 31.2 | 39.8 |
>> | BanditSum       | 35.3 | 42.7 | 34.1 | 41.2 |
>> | NeuSum          | 34.9 | 42.7 | 30.7 | 40.6 |
>> | Refresh         | 35.7 | 42.8 | 32.2 | 40.9 |
>> | UnifiedSum(E)   | 34.2 | 42.6 | 31.3 | 40.6 |
>> | PG              | 32.6 | 40.6 | 27.5 | 38.2 |
>> | FastRL(E+A)     | 35.1 | 40.8 | 29.9 | 38.8 |
>> | UnifiedSum(E+A) | 34.2 | 42.4 | 29.2 | 40.1 |

>#### ACL 2020: [FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization](./paper/2005.03754.pdf)  
>> Esin Durmus, He He and Mona Diab

>#### ACL 2020: [From Arguments to Key Points: Towards Automatic Argument Summarization](./paper/2005.01619.pdf)  
>> Roy Bar-Haim, Lilach Eden, Roni Friedman, Yoav Kantor, Dan Lahav and Noam Slonim

>#### ACL 2020: [Heterogeneous Graph Neural Networks for Extractive Document Summarization](./paper/2004.12393.pdf)  
>> Danqing Wang, Pengfei Liu, Yining Zheng, Xipeng Qiu and Xuanjing Huang

>#### ACL 2020: [Jointly Learning to Align and Summarize for Neural Cross-Lingual Summarization](./paper/2020.acl-main.554.pdf)  
>> Yue Cao, Hui Liu and Xiaojun Wan

>#### ACL 2020: [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](./paper/2005.01159.pdf)  
>> Luyang Huang, Lingfei Wu and Lu Wang

>#### ACL 2020: [Leveraging Graph to Improve Abstractive Multi-Document Summarization](./paper/2005.10043.pdf)  
>> Wei Li, Xinyan Xiao, Jiachen Liu, Hua Wu, Haifeng Wang and Junping Du

>#### ACL 2020: [MATINF: A Jointly Labeled Large-Scale Dataset for Classification, Question Answering and Summarization](./paper/2004.12302.pdf)  
>> Canwen Xu, Jiaxin Pei, Hongtao Wu, Yiyu Liu and Chenliang Li

>#### ACL 2020: [Multi-Granularity Interaction Network for Extractive and Abstractive Multi-Document Summarization](./paper/2020.acl-main.556.pdf)  
>> Hanqi Jin, Tianming Wang and Xiaojun Wan

>#### ACL 2020: [On Faithfulness and Factuality in Abstractive Summarization](./paper/2005.01619.pdf)  
>> Joshua Maynez, Shashi Narayan, Bernd Bohnet and Ryan McDonald

>#### ACL 2020: [Screenplay Summarization Using Latent Narrative Structure](./paper/2004.12727.pdf)  
>> Pinelopi Papalampidi, Frank Keller, Lea Frermann and Mirella Lapata

>#### ACL 2020: [Unsupervised Opinion Summarization as Copycat-Review Generation](./paper/1911.02247.pdf)  
>> Arthur Bražinskas, Mirella Lapata and Ivan Titov

>#### ACL 2020: [Unsupervised Opinion Summarization with Noising and Denoising](./paper/2004.10150.pdf)  
>> Reinald Kim Amplayo and Mirella Lapata

>#### ACL 2020: [A Large-Scale Multi-Document Summarization Dataset from the Wikipedia Current Events Portal](./paper/2020.acl-main.120.pdf)  
>> Demian Gholipour Ghalandari, Chris Hokamp, Nghia The Pham, John Glover and Georgiana Ifrim

>#### ACL 2020: [Attend to Medical Ontologies: Content Selection for Clinical Abstractive Summarization](./paper/2005.00163.pdf)  
>> Sajad Sotudeh Gharebagh, Nazli Goharian and Ross Filice

>#### ACL 2020: [Composing Elementary Discourse Units in Abstractive Summarization](./paper/2020.acl-main.551.pdf)  
>> Zhenwen Li, Wenhao Wu and Sujian Li

>#### ACL 2020: [Exploring Content Selection in Summarization of Novel Chapters](./paper/2005.01840.pdf)  
>> Faisal Ladhak, Bryan Li, Yaser Al-Onaizan and Kathy McKeown

>#### ACL 2020: [Fact-based Content Weighting for Evaluating Abstractive Summarisation](./paper/2020.acl-main.455.pdf)  
>> Xinnuo Xu, Ondřej Dušek, Jingyi Li, Verena Rieser and Ioannis Konstas

>#### ACL 2020: [OpinionDigest: A Simple Framework for Opinion Summarization](./paper/2005.01901.pdf)  
>> Yoshihiko Suhara, Xiaolan Wang, Stefanos Angelidis and Wang-Chiew Tan

>#### ACL 2020: [Self-Attention Guided Copy Mechanism for Abstractive Summarization](./paper/2020.acl-main.125.pdf)  
>> Song Xu, Haoran Li, Peng Yuan, Youzheng Wu, Xiaodong He and Bowen Zhou

>#### ACL 2020: [SUPERT: Towards New Frontiers in Unsupervised Evaluation Metrics for Multi-Document Summarization](./paper/2005.03724.pdf)  
>> Yang Gao, Wei Zhao and Steffen Eger

>#### ACL 2020: [Understanding Points of Correspondence between Sentences for Abstractive Summarization](./paper/2006.05621.pdf)  
>> Logan Lebanoff, John Muchovej, Franck Dernoncourt, Doo Soon Kim, Lidan Wang, Walter Chang and Fei Liu


## 2018

>#### ICLR 2018: [A deep reinforced model for abstractive summarization](./paper/1705.04304.pdf)  
>> Paulus, Romain, Caiming Xiong, and Richard Socher  

>#### ACL 2018: [Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting](./paper/1805.11080.pdf)  
>> Yen-Chun Chen, Mohit Bansal

>#### EMNLP 2018: [Improving Abstraction in Text Summarization](./paper/1808.07913.pdf)  
>> Wojciech Kryściński, Romain Paulus, Caiming Xiong, Richard Socher

