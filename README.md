## Papers on Recommendation System and Computational Advertising System



### Survey

surveys on recommendation system and computational advertising system

* [Deep Learning based Recommender System A Survey and New Perspectives](https://arxiv.org/abs/1707.07435)



### Embedding

* word2vec
* item2vec
* listing2vec
* node2vec
* id2vec based on WDL
* cf2vec based on NCF

| Model       | Conference | Paper                                                        |
| ----------- | ---------- | ------------------------------------------------------------ |
| word2vec | arxiv'13   | [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf); [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/pdf/1310.4546.pdf) [**Google**] |
| item2vec | arxiv'16   | [Item2Vec: Neural Item Embedding for Collaborative Filtering](https://arxiv.org/ftp/arxiv/papers/1603/1603.04259.pdf)|
| node2vec | KDD'16   | [node2vec: Scalable Feature Learning for Networks](https://cs.stanford.edu/people/jure/pubs/node2vec-kdd16.pdf) |
| Youtube Recall-DNN | RecSys'16| [Deep Neural Networks for YouTube Recommendations](https://ai.google/research/pubs/pub45530) [**Google**]|
| NCF | WWW'17   | [Neural Collaborative Filtering](https://www.comp.nus.edu.sg/~xiangnan/papers/ncf.pdf) |
| Listing emb | KDD'18 | [Real-time Personalization using Embeddings for Search Ranking at Airbnb](https://www.kdd.org/kdd2018/accepted-papers/view/real-time-personalization-using-embeddings-for-search-ranking-at-airbnb) [**Airbnb**] |
| Product emb | arxiv'19   | [Large-scale Collaborative Filtering with Product Embeddings](https://arxiv.org/abs/1901.04321) [**Amazon**] |
| DeepCF | AAAI'19 | [DeepCF: A Unified Framework of Representation Learning and Matching Function Learning in Recommender System](https://arxiv.org/abs/1901.04704) |




### CTR Model

various CTR prediction models for RS

* Tree-based series
* FTRL series
* FM series
* Deep series

| Model     | Conference | Paper                                                        |
| --------- | ---------- | ------------------------------------------------------------ |
| LR        | WWW'07     | [Predicting Clicks: Estimating the Click-Through Rate for New Ads](https://dl.acm.org/citation.cfm?id=1242643) [**Microsoft**] |
| FM        | ICDM'10    | [Factorization Machines](https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf) |
| FTRL      | KDD'13     | [Ad Click Prediction: a View from the Trenches](https://www.researchgate.net/publication/262412214_Ad_click_prediction_a_view_from_the_trenches) [**Google**] |
| GBDT+LR   | ADKDD'14   | [Practical Lessons from Predicting Clicks on Ads at Facebook](https://dl.acm.org/citation.cfm?id=2648589) [**Facebook**] |
| CCPM      | CIKM'15    | [A Convolutional Click Prediction Model](http://www.escience.cn/system/download/73676) |
| FFM       | RecSys'16  | [Field-aware Factorization Machines for CTR Prediction](https://dl.acm.org/citation.cfm?id=2959134) [**Criteo**] |
| DNN       | RecSys'16  | [Deep Neural Networks for YouTube Recommendations](http://art.yale.edu/file_columns/0001/1132/covington.pdf) [**Google**] |
| Wide&Deep | DLRS'16    | [Wide & Deep Learning for Recommender Systems](https://arxiv.org/pdf/1606.07792.pdf) [**Google**] |
| FNN       | ECIR'16    | [Deep Learning over Multi-field Categorical Data: A Case Study on User Response Prediction](https://arxiv.org/abs/1601.02376) [**RayCloud**] |
| PNN       | ICDM'16    | [Product-based Neural Networks for User Response Prediction](https://arxiv.org/pdf/1611.00144.pdf) |
| Youtube Rank-DNN    | RecSys'16   | [Deep Neural Networks for YouTube Recommendations](https://ai.google/research/pubs/pub45530), [**Google**] |
| DeepFM    | IJCAI'17   | [DeepFM: A Factorization-Machine based Neural Network for CTR Prediction](https://arxiv.org/abs/1703.04247), [**Huawei**] |
| NFM       | SIGIR'17   | [Neural Factorization Machines for Sparse Predictive Analytics](https://dl.acm.org/citation.cfm?id=3080777) |
| AFM       | IJCAI'17   | [Attentional Factorization Machines: Learning the Weight of Feature Interactions via Attention Networks](http://www.ijcai.org/proceedings/2017/0435.pdf) |
| DCN       | ADKDD'17   | [Deep & Cross Network for Ad Click Predictions](https://arxiv.org/abs/1708.05123) [**Google**] |
| xDeepFM   | KDD'18     | [xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems](https://arxiv.org/pdf/1803.05170.pdf) [**Microsoft**] |
| DIN   | KDD'18     | [Deep Interest Network for Click-Through Rate Prediction](https://arxiv.org/pdf/1706.06978.pdf) [**Alibaba**] |
| FwFM      | WWW'18     | [Field-weighted Factorization Machines for Click-Through Rate Prediction in Display Advertising](https://arxiv.org/pdf/1806.03514.pdf) [**Oath, TouchPal, LinkedIn, Ablibaba**] |
| FPE   | RecSys'18   | [Field-aware Probabilistic Embedding Neural Network for CTR Prediction](https://dl.acm.org/citation.cfm?id=3240396) |
| AutoInt   | arxiv'18   | [AutoInt: Automatic Feature Interaction Learning via Self-Attentive Neural Networks](https://arxiv.org/abs/1810.11921) |
| SASRec | ICDM'18 | [Self-Attentive Sequential Recommendation](https://arxiv.org/abs/1808.09781) |
| IFM   | AAAI'19   | [Interaction-aware Factorization Machines for Recommender Systems](https://arxiv.org/abs/1902.09757) [**Tencent**]|



### DRL based

* Deep Reinforcement Learning based Recommendation Systems


| Conference | Paper                                                        |
| ---------- | ------------------------------------------------------------ |
| WWW'18   | [DRN：A Deep Reinforcement Learning Framework for News Recommendation](https://dl.acm.org/citation.cfm?id=3185994) [**MSRA**]|
| RecSys'18 | [Deep Reinforcement Learning for Page-wise Recommendations](https://dl.acm.org/cita tion.cfm?id=3240374) [**JD**] |
| Arxiv'17 | [Deep Reinforcement Learning for List-wise Recommendations](https://arxiv.org/abs/1801.00209) [**JD**] |
| KDD'18 | [Stabilizing Reinforcement Learning in Dynamic Environment with Application to Online Recommendation](https://arxiv.org/abs/1801.00209) |
| KDD'18 | [Reinforcement Learning to Rank in E-Commerce Search Engine: Formalization, Analysis, and Application](https://dl.acm.org/citation.cfm?id=3219846) |
|  | https://tech.meituan.com/2018/11/15/reinforcement-learning-in-mt-recommend-system.html [**Meituan**] |



### Evaluations

evaluation methods for RS

* Predicting Online Performance of News Recommender Systems Through Richer Evaluation Metrics
* RecSys2018 tutorial



### Interpretability

interpretation methods for ML models

* PDP
* ICE
* SHAP
* LIME
* RETAIN
* LRP



### System

Recommendation related system references

* 



### Allocations

hashing function for flow allocations

* 



### Computational Ad

for computational advertising systems

* 



## Reference

* 《计算广告论文、学习资料、业界分享》https://github.com/wzhe06/Ad-papers
* 《Must-read papers on Recommender System》https://github.com/hongleizhang/RSPapers
* 《A review and evaluation of CTR prediction models》https://github.com/anyai/deepCTR
