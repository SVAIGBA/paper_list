| Datasets       |         R-1          |         R-2          |         R-L          |                            Methods                            |
| :--------------: | :------------------: | :------------------: | :------------------: | :----------------------------------------------------------: |
| CNN/DM         | 43.77<br />**44.41** | 20.85<br />**20.86** | **40.67**<br />40.55 | [DISCOBERT W.GR&GC](./paper/2020.acl-main.451.pdf)<br />[MATCHSUM (ROBERTa-base)](./paper/2004.08795.pdf) |
| Gigaword       |        40.89         |        19.11         |        37.60         |              [best-abs](./paper/1911.10390.pdf)              |
| DUC2004        |        31.00         |        11.11         |        26.94         |              [SemSUM](./paper/AAAI-JinH.7203.pdf)             |
| NewSroom       |        45.93         |        24.14         |        42.51         |              [best-abs](./paper/1911.10390.pdf)              |
| XSUM           |        24.86         |         4.58         |        18.31         |        [MATCHSUM (Sel = 1,2)](./paper/2004.08795.pdf)        |
| New York Times |        50.00         |        30.38         |        42.70         |      [DISCOBERT W.GR&GC](./paper/2020.acl-main.451.pdf)      |
| MSR-ATC        |        33.82         |        17.08         |        30.62         |             [SemSUM](./paper/AAAI-JinH.7203.pdf)             |
| Reddit         |        25.09         |         6.17         |        20.13         |        [MATCHSUM (Sel = 1,2)](./paper/2004.08795.pdf)        |



## 2020

>#### EMNLP 2020: [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](./paper/2020-Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward.pdf)  
>> Author: Luyang Huang, Lingfei Wu, Lu Wang1
>>
>> Dataset: CNN/Daily Mail,New York Times
>> Score:  
>> | Model |  CNN/DM<br> R-1        R-2        R-L|
>> | :---: | :---: | :---: | :---: |
>> |ASGARD-SEG +R<sub>rouge</sub>+R<sub>close</sub>|   43.81   20.22   40.37 |
>> | Model | NYT<br> R-1        R-2        R-L|
>> | :---: | :---: | :---: | :---: |
>> |ASGARD-SEG +R<sub>rouge</sub>+R<sub>close</sub>|   51.29   34.97   48.26 |



>#### EMNLP 2020: [Better Highlighting: Creating Sub-Sentence Summary Highlights](./paper/2020-Better Highlighting Creating Sub-Sentence Summary Highlights.pdf)  
>> Author: Sangwoo Cho, Kaiqiang Song, Chen Li,Dong Yu, Hassan Foroosh, Fei Liu
>>
>> Dataset: DUC-04 
>> Score:  
>> | Model |  R-1        R-2        R-SU4|
>> | :---: | :---: | :---: | :---: |
>> | HL-TreeSegs  |   39.18   10.30   14.37 |
>> | HL-XLNetSegs  |   39.26    10.70   14.47|

>#### EMNLP 2020: [Multi-Fact Correction in Abstractive Text Summarization](./paper/2020-Multi-Fact Correction in Abstractive Text Summarization.pdf)  
>> Author: Yue Dong, Shuohang Wang, Zhe Gan, Yu Cheng, Jackie Chi Kit Cheung,  Jingjing Liu
>>
>> Dataset: CNN/DailyMail
>> Score:  
>> | Model |  QGQA  |  FactCC sent  |  R-1        R-2        R-L|
>> | :---: | :---: | :---: | :---: |:---: |:---: |
>> | QA-Span  |   75.94   |   80.97  |   41.75   19.27   38.81 |
>> | Auto-regressive |   75.19    |   79.89  |   41.68  19.16   38.74 |

>#### EMNLP 2020: [Evaluating the Factual Consistency of Abstractive Text Summarization](./paper/2020-emnlp-Evaluating the Factual Consistency of Abstractive Text Summarization.pdf)  
>> Author: Wojciech Krys ́cin ́ski, Bryan McCann, Caiming Xiong, Richard Socher
>>
>> Dataset: CNN/DailyMail
>> Score:  
>> | Model |  Incorrect  |  $\Delta$  |
>> | :---: | :---: | :---: | :---: |
>> | FactCC  | 30.0% |  -20.0 |
>>

>#### EMNLP 2020: [PALM Pre-training an Autoencoding&Autoregressive Language Modelfor Context-conditioned Generation](./paper/2020-PALM Pre-training an Autoencoding&Autoregressive Language Modelfor Context-conditioned Generation.pdf) 
>> Author: Bin Bi, Chenliang Li, Chen Wu, Ming Yan,Wei Wang, Songfang Huang, Fei Huang, Luo Si
>>
>> Dataset: CNN/DailyMail,Gigaword
>> Score: 
>>  | Methods                 | CNN/DailyMail<br>R-1        R-2        R-L | Gigaword<br>R-1        R-2        R-L |
>> | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
>> | PALM                    |          42.71   19.97     39.71          |        38.75   19.79   35.98        |
>> | PALM(LARGE)                    |         44.30   21.12     41.41          |        39.45   20.37   36.75        |

>#### EMNLP 2020: [Pre-training for Abstractive Document Summarization by Reinstating Source Text](./paper/2020-Pre-training for Abstractive Document Summarization byReinstating Source Text.pdf)  
>> Author: Yanyan Zou, Xingxing Zhang, Wei Lu,Furu Wei, Ming Zhou
>>
>> Dataset: CNN/DailyMail
>> Score:  
>> | Model |  R-1  |  R-2  |  R-L  |
>> | :---: | :---: | :---: | :---: |
>> | STEP  | 44.03 | 21.13 | 41.20 |
>>

>#### AAAI 2020: [Keywords-Guided Abstractive Sentence Summarization](./paper/2020-Keywords-Guided Abstractive Sentence Summarization.pdf)  
>> Author: Haoran Li, Junnan Zhu, Jiajun Zhang, Chengqing Zong, Xiaodong He
>>
>> Dataset: Gigaword
>> Score:  
>>
>> | Model |  R-1        R-2        R-L|
>> | :---: | :---: | :---: | :---: |
>> | Co- Selective  Hier+DualPG  |  47.14   25.06  44.39 |

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
>>
>> Dataset: Gigaword dataset, Newsroom dataset
>> Score:
>> Summarization results on the Gigaword test set
>>
>> | Model                  | RG-1  | RG-2  | RG-L  | Bert-S |
>> | ---------------------- | ----- | ----- | ----- | ------ |
>> | Beam + BPNorm (c=0.55) | 39.19 | 20.38 | 36.69 | 61.46  |
>> | Beam + SBWR(r=0.25)    | 39.08 | 20.47 | 36.68 | 61.51  |
>> 
>> ROUGE F1 and BERTScore F1 evaluation on the NewSroom test set
>>
>> | Model    | RG-1  | RG-2  | RG-L  | Bert-S |
>> | -------- | ----- | ----- | ----- | ------ |
>> | pure-ext | 43.21 | 21.81 | 40.05 | 63.68 |
>> | best-abs | 45.93 | 24.14 | 42.51 | 66.20 |
>> ROUGE F1, WMD unigram and BERTScore F1 evaluation on the NewSroom test set
>> | Model    | RG-1  | RG-2  | RG-L  | Bert-S |
>> | -------- | ----- | ----- | ----- | ------ |
>> | pure-ext | 43.21 | 21.81 | 40.05 | 63.68  |
>> | best-abs | 45.93 | 24.14 | 42.51 | 66.20  |
>>
>> ROUGE F1 and BERTScore F1 evaluation on the Gigaword test set
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

>#### ACL 2020: [Heterogeneous Graph Neural Networks for Extractive Document Summarization](./paper/2004.12393.pdf)  
>> Author: Danqing Wang, Pengfei Liu, Yining Zheng, Xipeng Qiu and Xuanjing Huang
>> Datasets: CNNDM NYT50 Milti-News
>> Scores: 
>>
>> Performance comparison of the models on CNNDM dataset.
>>
>> | Model            | R-1   | R-2   | R-L   |
>> | ---------------- | ----- | ----- | ----- |
>> | Ext-BiLSTM       | 41.59 | 19.03 | 38.04 |
>> | Ext-Transformer  | 41.33 | 18.83 | 37.65 |
>> | HSG              | 42.31 | 19.51 | 38.74 |
>> | HSG+Tri-Blocking | 42.95 | 19.76 | 39.23 |
>>
>> Performance comparison of the models on NYT50 dataset.
>>
>> | Model            | R-1   | R-2   | R-L   |
>> | ---------------- | ----- | ----- | ----- |
>> | Ext-BiLSTM       | 46.32 | 25.84 | 42.16 |
>> | Ext-Transformer  | 45.07 | 24.72 | 40.85 |
>> | HSG              | 46.89 | 26.26 | 42.58 |
>> | HSG+Tri-Blocking | 46.57 | 25.94 | 42.25 |
>>
>> Performance comparison of the models on Multi-News dataset.
>>
>> | Model             | R-1   | R-2   | R-L   |
>> | ----------------- | ----- | ----- | ----- |
>> | HSG               | 45.66 | 16.22 | 41.80 |
>> | HSG+Tri-Blocking  | 44.92 | 15.59 | 40.89 |
>> | HDSG              | 46.05 | 16.35 | 42.08 |
>> | HDSG+Tri-Blocking | 45.55 | 15.78 | 41.29 |

>#### ACL 2020: [Jointly Learning to Align and Summarize for Neural Cross-Lingual Summarization](./paper/2020.acl-main.554.pdf)  
>> Author: Yue Cao, Hui Liu and Xiaojun Wan
>> Datasets: Gigaword DUC2004 LCSTS CNNDM
>> Scores:
>> Notice: *g* means gigaword dataset, *d* means DUC2004 and so on.
>>
>> | model | g_R1  | g_R2  | g_RL  | d_R1  | d_R2 | d_RL  | l_R1  | l_R2  | l_RL  | c_R1  | c_R2  | c_Rl  |
>> | ----- | ----- | ----- | ----- | ----- | ---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
>> | ours  | 32.04 | 13.60 | 27.91 | 27.25 | 8.71 | 23.36 | 40.97 | 23.20 | 36.96 | 39.12 | 16.76 | 33.86 |

>#### ACL 2020: [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](./paper/2005.01159.pdf)  
>> Author: Luyang Huang, Lingfei Wu and Lu Wang

>#### ACL 2020: [Leveraging Graph to Improve Abstractive Multi-Document Summarization](./paper/2005.10043.pdf)  
>> Author: Wei Li, Xinyan Xiao, Jiachen Liu, Hua Wu, Haifeng Wang and Junping Du
>> Datasets: WikiSum Multi-News
>> Scores:
>> Performance of models on WikiSum dataset
>>
>> | Model            | R-1   | R-2   | R-L   |
>> | ---------------- | ----- | ----- | ----- |
>> | GraphSum         | 42.63 | 27.70 | 36.97 |
>> | GraphSum+RoBERTa | 42.99 | 27.83 | 37.36 |
>>
>> Performance of models on Multi-News datasets
>>
>> | Models                   | R-1   | R-2   | R-L   |
>> | ------------------------ | ----- | ----- | ----- |
>> | GraphSum                 | 45.02 | 16.69 | 22.50 |
>> | G.S.(Similarity)+RoBERTa | 45.93 | 17.33 | 23.33 |
>> | G.S.(Topic)+RoBERTa      | 46.07 | 17.42 | 23.21 |
>> | G.S.(Discourse)+RoBERTa  | 45.87 | 17.56 | 23.39 |

>#### ACL 2020: [MATINF: A Jointly Labeled Large-Scale Dataset for Classification, Question Answering and Summarization](./paper/2004.12302.pdf)  
>> Author: Canwen Xu, Jiaxin Pei, Hongtao Wu, Yiyu Liu and Chenliang Li
>> Contribution: released a new dataset

>#### ACL 2020: [Multi-Granularity Interaction Network for Extractive and Abstractive Multi-Document Summarization](./paper/2020.acl-main.556.pdf)  
>> Author: Hanqi Jin, Tianming Wang and Xiaojun Wan
>> Dataset: Multi-News dataset
>> Scores:
>>
>> | Models     | R-1   | R-2   | R-L   |
>> | ---------- | ----- | ----- | ----- |
>> | MGSum-ext  | 44.75 | 15.75 | 19.30 |
>> | MGSum-abs  | 46.00 | 16.81 | 20.09 |
>> | oracle ext | 49.02 | 29.78 | 29.19 |

>#### ACL 2020: [On Faithfulness and Factuality in Abstractive Summarization](./paper/2005.01619.pdf)  
>> Author: Joshua Maynez, Shashi Narayan, Bernd Bohnet and Ryan McDonald
>> Dataset: XSum
>> Scores:
>>
>> | Models  | R-1   | R-2   | R-L   | BERTScoreBERTS2S |
>> | ------- | ----- | ----- | ----- | ---------------- |
>> | BERTS2S | 38.42 | 16.96 | 31.27 | 78.85            |


>#### ACL 2020: [Screenplay Summarization Using Latent Narrative Structure](./paper/2004.12727.pdf)  
>> Pinelopi Papalampidi, Frank Keller, Lea Frermann and Mirella Lapata

>#### ACL 2020: [Unsupervised Opinion Summarization as Copycat-Review Generation](./paper/1911.02247.pdf)  
>> Author: Arthur Bražinskas, Mirella Lapata and Ivan Titov
>> Dataset: Yelp Amazon


>#### ACL 2020: [Unsupervised Opinion Summarization with Noising and Denoising](./paper/2004.10150.pdf)  
>> Author: Reinald Kim Amplayo and Mirella Lapata
>> Dataset: CNNDM 
>> Scores: 
>>
>> | Model     | R-1   | R-2   | R-L   |
>> | --------- | ----- | ----- | ----- |
>> | EDUSum+RL | 40.89 | 18.30 | 37.79 |
>> | EDUSum    | 41.40 | 18.03 | 38.79 |

>#### ACL 2020: [A Large-Scale Multi-Document Summarization Dataset from the Wikipedia Current Events Portal](./paper/2020.acl-main.120.pdf)  
>> Author: Demian Gholipour Ghalandari, Chris Hokamp, Nghia The Pham, John Glover and Georgiana Ifrim
>> Contribution: released a new dataset

>#### ACL 2020: [Attend to Medical Ontologies: Content Selection for Clinical Abstractive Summarization](./paper/2005.00163.pdf)  
>> Author: Sajad Sotudeh Gharebagh, Nazli Goharian and Ross Filice
>> Dataset: MIMIC-CXR Open-I
>> Scores:
>> performance of the model on MIMIC-CXR dataset
>>
>> | Model | R-1   | R-2   | R-L   |
>> | ----- | ----- | ----- | ----- |
>> | ours  | 53.57 | 40.78 | 51.81 |
>>
>> performance of the model on Open-I dataset
>>
>> | Model | R-1   | R-2   | R-L   |
>> | ----- | ----- | ----- | ----- |
>> | ours  | 40.88 | 24.44 | 40.37 |

>#### ACL 2020: [Composing Elementary Discourse Units in Abstractive Summarization](./paper/2020.acl-main.551.pdf)  
>> Author: Zhenwen Li, Wenhao Wu and Sujian Li
>> Dataset: Yelp Amazon
>> Scores:
>>
>> | Models                      | R-1   | R-2  | R-L   |
>> | --------------------------- | ----- | ---- | ----- |
>> | Copycat (on Yelp dataset)   | 29.47 | 5.26 | 18.09 |
>> | Copycat (on Amazon dataset) | 31.97 | 5.81 | 20.16 |

>#### ACL 2020: [Exploring Content Selection in Summarization of Novel Chapters](./paper/2005.01840.pdf)  
>> Faisal Ladhak, Bryan Li, Yaser Al-Onaizan and Kathy McKeown

>#### ACL 2020: [Fact-based Content Weighting for Evaluating Abstractive Summarisation](./paper/2020.acl-main.455.pdf)  
>> Xinnuo Xu, Ondřej Dušek, Jingyi Li, Verena Rieser and Ioannis Konstas

>#### ACL 2020: [OpinionDigest: A Simple Framework for Opinion Summarization](./paper/2005.01901.pdf)  
>> Author: Yoshihiko Suhara, Xiaolan Wang, Stefanos Angelidis and Wang-Chiew Tan
>> Dataset: YELP
>> Scores:
>>
>> | Model         | R1    | R2   | RL    |
>> | ------------- | ----- | ---- | ----- |
>> | OPINIONDIGEST | 29.30 | 5.77 | 18.56 |
>>
>> 

>#### ACL 2020: [Self-Attention Guided Copy Mechanism for Abstractive Summarization](./paper/2020.acl-main.125.pdf)  
>> Author: Song Xu, Haoran Li, Peng Yuan, Youzheng Wu, Xiaodong He and Bowen Zhou
>> Dataset: CNNDM Gigaword
>> Scores:
>> Performance tested on the CNNDM
>>
>> | Model              | R1    | R2    | RL    |
>> | ------------------ | ----- | ----- | ----- |
>> | SAGCopy Outdegree  | 42.53 | 19.92 | 39.44 |
>> | SAGCopy Indegree-1 | 42.30 | 19.75 | 39.23 |
>> | SAGCopy Indegree-2 | 42.56 | 19.89 | 39.40 |
>> | SAGCopy Indegree-3 | 42.34 | 19.72 | 39.29 |
>>
>> Performance tested on the Gigaword
>>
>> | Model              | R1    | R2    | RL    |
>> | ------------------ | ----- | ----- | ----- |
>> | SAGCopy Outdegree  | 38.86 | 19.91 | 36.06 |
>> | SAGCopy Indegree-1 | 38.84 | 20.39 | 36.27 |
>> | SAGCopy Indegree-2 | 38.70 | 20.16 | 36.09 |
>> | SAGCopy Indegree-3 | 38.69 | 19.83 | 35.98 |
>>
>> 

>#### ACL 2020: [SUPERT: Towards New Frontiers in Unsupervised Evaluation Metrics for Multi-Document Summarization](./paper/2005.03724.pdf)  
>> Author: Yang Gao, Wei Zhao and Steffen Eger
>> Dataset: TAC08 TAC09
>> Scores:
>>
>> | Model  | TAC08_R1 | TAC08_R2 | TAC08_RL | TAC09_R1 | TAC09_R2 | TAC09_RL |
>> | ------ | -------- | -------- | -------- | -------- | -------- | -------- |
>> | NTD_SP | 37.6     | 10.2     | 29.6     | 38.0     | 10.3     | 19.4     |
>>
>> 

>#### ACL 2020: [Understanding Points of Correspondence between Sentences for Abstractive Summarization](./paper/2006.05621.pdf)  
>> Logan Lebanoff, John Muchovej, Franck Dernoncourt, Doo Soon Kim, Lidan Wang, Walter Chang and Fei Liu

## 2019
>#### ACL 2019: [Improving the Similarity Measure of Determinantal Point Processes for Extractive Multi-Document Summarization](./paper/P19-1098.pdf)  
>> Author: Sangwoo Cho,  Logan Lebanoff ,  Hassan Foroosh,  Fei Liu

>#### ACL 2019: [Global Optimization under Length Constraint for Neural Text Summarization](./paper/P19-1099.pdf)  
>> Takuya Makino | Tomoya Iwakura | Hiroya Takamura | Manabu Okumura

>#### ACL 2019: [Searching for Effective Neural Extractive Summarization: What Works and What’s Next](./paper/P19-1100.pdf)  
>> Author: Ming Zhong | Pengfei Liu | Danqing Wang | Xipeng Qiu | Xuanjing Huang

>#### ACL 2019: [Multi-News: A Large-Scale Multi-Document Summarization Dataset and Abstractive Hierarchical Model](./paper/P19-1102.pdf)  
>> Alexander Fabbri | Irene Li | Tianwei She | Suyi Li | Dragomir Radev

>#### ACL 2019: [TalkSumm: A Dataset and Scalable Annotation Method for Scientific Paper Summarization Based on Conference Talks](./paper/P19-1204.pdf)  
>> Guy Lev | Michal Shmueli-Scheuer | Jonathan Herzig | Achiya Jerbi | David Konopnicki

>#### ACL 2019: [Improving the Similarity Measure of Determinantal Point Processes for Extractive Multi-Document Summarization](./paper/P19-1205.pdf)  
>> Yongjian You | Weijia Jia | Tianyi Liu | Wenmian Yang

>#### ACL 2019: [Unsupervised Neural Single-Document Summarization of Reviews via Learning Latent Discourse Structure and its Ranking](./paper/P19-1206.pdf)  
>> Author: Masaru Isonuma | Junichiro Mori | Ichiro Sakata

>#### ACL 2019: [BiSET: Bi-directional Selective Encoding with Template for Abstractive Summarization](./paper/P19-1207.pdf.pdf)  
>> Author: Kai Wang | Xiaojun Quan | Rui Wang

>#### ACL 2019: [Scoring Sentence Singletons and Pairs for Abstractive Summarization](./paper/P19-1209.pdf)  
>> Author: Logan Lebanoff | Kaiqiang Song | Franck Dernoncourt | Doo Soon Kim | Seokhwan Kim | Walter Chang | Fei Liu

>#### ACL 2019: [Keep Meeting Summaries on Topic: Abstractive Multi-Modal Meeting Summarization](./paper/P19-1210.pdf)  
>> Author: Manling Li | Lingyu Zhang | Heng Ji | Richard J. Radke

>#### ACL 2019: [BIGPATENT: A Large-Scale Dataset for Abstractive and Coherent Summarization](./paper/P19-1212.pdf)  
>> Author: Eva Sharma | Chen Li | Lu Wang

>#### ACL 2019: [Self-Supervised Learning for Contextualized Extractive Summarization](./paper/P19-1214.pdf)  
>> Author: Hong Wang | Xin Wang | Wenhan Xiong | Mo Yu | Xiaoxiao Guo | Shiyu Chang | William Yang Wang

>#### ACL 2019: [On the Summarization of Consumer Health Questions](./paper/P19-1215.pdf)  
>> Author: Asma Ben Abacha | Dina Demner-Fushman

>#### ACL 2019: [Zero-Shot Cross-Lingual Abstractive Sentence Summarization through Teaching Generation and Attention](./paper/P19-1305.pdf)  
>> Author: Xiangyu Duan | Mingming Yin | Min Zhang | Boxing Chen | Weihua Luo

>#### ACL 2019: [HighRES: Highlight-based Reference-less Evaluation of Summarization](./paper/P19-1330.pdf)  
>> Author: Hardy Hardy | Shashi Narayan | Andreas Vlachos

>#### ACL 2019: [HIBERT: Document Level Pre-training of Hierarchical Bidirectional Transformers for Document Summarization](./paper/P19-1499.pdf)  
>> Author: Xingxing Zhang | Furu Wei | Ming Zhou

>#### ACL 2019: [Hierarchical Transformers for Multi-Document Summarization](./paper/P19-1500.pdf)  
>> Author: Yang Liu | Mirella Lapata

>#### ACL 2019: [Abstractive Text Summarization Based on Deep Learning and Semantic Content Generalization](./paper/P19-1501.pdf)  
>> Author: Panagiotis Kouris | Georgios Alexandridis | Andreas Stafylopatis

>#### ACL 2019: [Studying Summarization Evaluation Metrics in the Appropriate Scoring Range](./paper/P19-1502.pdf)  
>> Author: Maxime Peyrard

>#### ACL 2019: [Simple Unsupervised Summarization by Contextual Matching](./paper/P19-1503.pdf)  
>> Author: Jiawei Zhou | Alexander Rush

>#### ACL 2019: [Sentence Centrality Revisited for Unsupervised Summarization](./paper/P19-1628.pdf)  
>> Author: Hao Zheng | Mirella Lapata

>#### ACL 2019: [Inducing Document Structure for Aspect-based Summarization](./paper/P19-1630.pdf)  
>> Author: Lea Frermann | Alexandre Klementiev

>#### ACL 2019: [Multimodal Abstractive Summarization for How2 Videos](./paper/P19-1659.pdf)  
>> Author: Shruti Palaskar | Jindřich Libovický | Spandana Gella | Florian Metze

>#### AAAI 2019: [DeepChannel: Salience Estimation by Contrastive Learning for Extractive DocumentSummarization](./paper/4679-Article-Text-7718-1-10-20190707.pdf) 
>> Author: Jiaxin Shi; Chen Liang ; Lei Hou ; Juanzi Li;Hanwang Zhang;Zhiyuan Liu

>#### AAAI 2019: [ScisummNet: A Large Annotated Corpus and Content-Impact Models for Scientific PaperSummarization with Citation Networks](./paper/4727-Article-Text-7766-2-10-20190721.pdf)  
>> Author: Michihiro Yasunaga ; Jungo Kasai;Rui Zhang ;Alexander R Fabbri ;Irene Li ; Dan Friedman Dragomir Radev 

>#### AAAI 2019: [Exploring Human Reading Cognition for Abstractive Text Summarization](./paper/4724-Article-Text-7763-1-10-20190707.pdf)  
>> Author: Min Yang ; Qiang Qu (SIAT); Zhou Zhao ;Xiaojun Chen ; Ying Shen; Wenting Tu 

>#### AAAI 2019: [Generating Character Descriptions for Automatic Summarization of Fiction](./paper/4738-Article-Text-7777-1-10-20190707.pdf)  
>> Author: Weiwei Zhang; Jackie Chi Kit Cheung; Joel Oren 

>#### AAAI 2019: [Towards Personalized Review Summarization via User-aware Sequence Network](./paper/4640-Article-Text-7679-1-10-20190707.pdf)  
>> Author: Junjie Li ; Haoran Li ; Chengqing Zong 

>#### EMNLP 2019: [An Entity-Driven Framework for Abstractive Summarization](./paper/EMNLP2019_sharma_huang_hu_wang.pdf)  
>> Author: Eva Sharma, Luyang Huang, Zhe Hu and Lu Wang

>#### EMNLP 2019: [Answers Unite! Unsupervised Metrics for Reinforced Summarization Models](./paper/D19-1320.pdf)  
>> Author: Thomas Scialom, Sylvain Lamprier, Benjamin Piwowarski and Jacopo Staiano

>#### EMNLP 2019: [Attribute-aware Sequence Network for Review Summarization](./paper/D19-1297.pdf)  
>> Author: Wenbo Wang, Yang Gao, Heyan Huang and Yuxiang Zhou

>#### EMNLP 2019: [Concept Pointer Network for Abstractive Summarization](./paper/D19-1304.pdf)  
>> Author: Eva Sharma, Luyang Huang, Zhe Hu and Lu Wang

>#### EMNLP 2019: [Contrastive Attention Mechanism for Abstractive Sentence Summarization](./paper/D19-1301.pdf)  
>> Author: Xiangyu Duan, Hongfei Yu, Mingming Yin, Min Zhang, Weihua Luo and Yue Zhang

>#### EMNLP 2019: [Extractive Summarization of Long Documents by Combining Global and Local Context](./paper/D19-1298.pdf)  
>> Author: Wen Xiao and Giuseppe Carenini

>#### EMNLP 2019: [How to Write Summaries with Patterns? Learning towards Abstractive Summarization through Prototype Editing](./paper/1909.08837.pdf)  
>> Author: Shen Gao, Xiuying Chen, Piji Li, Zhangming Chan, Dongyan Zhao and Rui Yan

>#### EMNLP 2019: [Improving Latent Alignment in Text Summarization by Generalizing the Pointer Generator](./paper/D19-1390.pdf)  
>> Author: Xiaoyu Shen, Yang Zhao, Hui Su and Dietrich Klakow

>#### EMNLP 2019: [NCLS: Neural Cross-Lingual Summarization](./paper/D19-1302.pdf)
>> Author: Junnan Zhu, Qian Wang, Yining Wang, Yu Zhou, Jiajun Zhang, Shaonan Wang and Chengqing Zong

>#### EMNLP 2019: [Neural Extractive Text Summarization with Syntactic Compression](./paper/D19-1324.pdf)  
>> Author: Wojciech Kryscinski, Nitish Shirish Keskar, Bryan McCann, Caiming Xiong and Richard Socher

>#### EMNLP 2019: [Neural Text Summarization: A Critical Evaluation](./paper/D19-1051.pdf)  
>> Author: Eva Sharma, Luyang Huang, Zhe Hu and Lu Wang

>#### EMNLP 2019: [Reading Like HER: Human Reading Inspired Extractive Summarization](./paper/D19-1300.pdf)  
>> Author: Ling Luo, Xiang Ao, Yan Song, Feiyang Pan, Min Yang and Qing He

>#### EMNLP 2019: [Subtopic-Driven Multi-Document Summarization](./paper/D08-1080.pdf)  
>> Author: Xin Zheng, Aixin Sun, Jing Li and Karthik Muthuswamy

>#### EMNLP 2019: [Summary Cloze: A New Task for Content Selection in Topic-Focused Summarization](./paper/D19-1386.pdf)  
>> Author: Daniel Deutsch and Dan Roth

>#### EMNLP 2019: [Text Summarization with Pretrained Encoders](./paper/D19-1387.pdf)  
>> Author: Yang Liu and Mirella Lapata

>#### EMNLP 2019: [Unsupervised Sentence Summarization using the Information Bottleneck Principle](./paper/D19-1389.pdf)  
>> Author: Peter West, Ari Holtzman, Jan Buys and Yejin Choi

>#### EMNLP 2019: [Abstract Text Summarization: A Low Resource Challenge](./paper/D19-1616.pdf)  
>> Author: Shantipriya Parida and Petr Motlicek

>#### EMNLP 2019: [Attention Optimization for Abstractive Document Summarization](./paper/D19-1117.pdf)  
>> Author: Min Gui, Junfeng Tian, Rui Wang and Zhenglu Yang

>#### EMNLP 2019: [Countering the effects of lead bias in news summarization via multi-stage training and auxiliary losses](./paper/D19-1620.pdf)  
>> Author: Matt Grenander, Yue Dong, Jackie Chi Kit Cheung and Annie Louis

>#### EMNLP 2019: [Deep Reinforcement Learning with Distributional Semantic Rewards for Abstractive Summarization](./paper/D19-1623.pdf)  
>> Author: Siyao Li, Deren Lei, Pengda Qin and William Yang Wang

>#### EMNLP 2019: [The Feasibility of Embedding Based Automatic Evaluation for Single Document Summarization](./paper/D19-1116.pdf)  
>> Author: Simeng Sun and Ani Nenkova

>#### NACCL 2019: [Keyphrase Generation: A Text Summarization Struggle](./paper/N19-1070.pdf)  
>> Author: Erion Çano | Ondřej Bojar

>#### NACCL 2019: [Fast Concept Mention Grouping for Concept Map-based Multi-Document Summarization](./paper/N19-1074.pdf)  
>> Author: Tobias Falke | Iryna Gurevych

>#### NACCL 2019: [Single Document Summarization as Tree Induction](./paper/N19-1173.pdf)  
>> Author: Yang Liu | Ivan Titov | Mirella Lapata

>#### NACCL 2019: [A Robust Abstractive System for Cross-Lingual Summarization](./paper/N19-1204.pdf)  
>> Author: Jessica Ouyang | Boya Song | Kathy McKeown

>#### NACCL 2019: [Abstractive Summarization of Reddit Posts with Multi-level Memory Networks](./paper/N19-1260.pdf)  
>> Author: Byeongchang Kim | Hyunwoo Kim | Gunhee Kim

>#### NACCL 2019: [Guiding Extractive Summarization with Question-Answering Rewards](./paper/N19-1264.pdf)  
>> Author: Kristjan Arumae | Fei Liu

>#### NACCL 2019: [Question Answering as an Automatic Evaluation Metric for News Article Summarization](./paper/N19-1395.pdf)  
>> Author: Matan Eyal | Tal Baumel | Michael Elhadad

>#### NACCL 2019: [LeafNATS: An Open-Source Toolkit and Live Demo System for Neural Abstractive Text Summarization](./paper/N19-4012.pdf)  
>> Author: Tian Shi | Ping Wang | Chandan K. Reddy


## 2018

>#### ICLR 2018: [A deep reinforced model for abstractive summarization](./paper/1705.04304.pdf)  
>> Paulus, Romain, Caiming Xiong, and Richard Socher  

>#### ACL 2018: [Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting](./paper/1805.11080.pdf)  
>> Yen-Chun Chen, Mohit Bansal

>#### EMNLP 2018: [Improving Abstraction in Text Summarization](./paper/1808.07913.pdf)  
>> Wojciech Kryściński, Romain Paulus, Caiming Xiong, Richard Socher

