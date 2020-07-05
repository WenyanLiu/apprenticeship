# Apprenticeship

This part of my life is called "The Pursuit of Doctorate". Here is my blog about learning process.

## Diving In

- [Privacy protection](#awesome-privacy-protection-research-materials
)

- [Federated learning](#awesome-federated-learning-research-materials)

- [Fairness](#awesome-fairness-research-materials)

- [Blockchain](#awesome-blockchain-research-materials)

- [Others](#other-awesome-research-materials)

---

**Legend**:

| :ledger: | :memo: | :keyboard: | :camera: | :floppy_disk: |
| :-: | :-: |  :-: |  :-: |  :-: | 
| PDF<br>Files | Notes | Code | Slides | Other<br>Supplementaries |

---

### Awesome Privacy Protection Research Materials

A curated list of awesome privacy protection research materials.

- [Books](#books)

Courses:
- [Tutorial](#tutorial)

Papers:
- [Policy Brief](#policy-brief)
- [Survey](#survey)
- [Basic Techniques](#basic-techniques)
- [Private Framework](#private-framework)
- [Private Benchmark](#private-benchmark)
- Private Data Publishing
    - [Transaction Data Publishing](#transaction-data-publishing)
    - [Streaming Data Publishing](#streaming-data-publishing)
    - [Graph Data Publishing](#graph-data-publishing)
    - [Image Data Publishing](#image-data-publishing)
- Private Data Analysis
    - [Private Learning](#private-learning)
    - [Frequent Itemset Mining](#frequent-itemset-mining)
    - [Recommender Systems](#recommender-systems)
    - [Survival Analysis](#survival-analysis)
- [Cryptography](#cryptography)
    - [Encrypted Database](#encrypted-database)
    - [Searchable Encryption](#searchable-encryption)

[:top:](#diving-in)

#### Books

| Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 数据库系统概论 | 王珊, 萨师煊 | 高等教育出版社 | 2014 | | [:memo:](notes/figures/数据库安全性.png) | |

- [ ] `| The Algorithmic Foundations of Differential Privacy | Cynthia Dwork, Aaron Roth | TCS | 2014 | [:ledger:](https://www.nowpublishers.com/article/Details/TCS-042) |  | [:floppy_disk:](http://www.cis.upenn.edu/~aaroth/courses/privacyF11.html) |`

- [ ] `Jordi Soria-Comas, Josep Domingo-Ferrer: Optimal data-independent noise for differential privacy. Inf. Sci. 250: 200-214 (2013)`
- [ ] `Tianqing Zhu, Gang Li, Wanlei Zhou, Philip S. Yu: Differential Privacy and Applications. Advances in Information Security 69, Springer 2017, ISBN 978-3-319-62002-2, pp. 1-222`
- [ ] `Ninghui Li, Min Lyu, Dong Su, Weining Yang: Differential Privacy: From Theory to Practice. Synthesis Lectures on Information Security, Privacy, & Trust, Morgan & Claypool Publishers 2016, pp. 1-138`

[:top:](#awesome-privacy-protection-research-materials)

#### Tutorial
| | Instructors | Institution | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |

- [ ] `| The Algorithmic Foundations of Data Privacy | Aaron Roth | Penn | Fall 2011 | [:ledger:](http://www.cis.upenn.edu/~aaroth/courses/privacyF11.html) |  | [:floppy_disk:](https://www.nowpublishers.com/article/Details/TCS-042) |`

[:top:](#awesome-privacy-protection-research-materials)

#### Policy Brief

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|  | China's Social Credit System: A Mark of Progress or a Threat to Privacy? | Martin Chorzempa, Paul Triolo, Samm Sacks |  | 2018 | [:ledger:](https://piie.com/publications/policy-briefs/chinas-social-credit-system-mark-progress-or-threat-privacy) | / | [:floppy_disk:](http://www.yuandiancredit.com/h-nd-2945.html) |

[:top:](#awesome-privacy-protection-research-materials)

#### Survey

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Differentially Private Data Publishing and Analysis: A Survey | Tianqing Zhu, Gang Li, Wanlei Zhou, Philip S. Yu | TKDE | 2017 | [:ledger:](https://ieeexplore.ieee.org/abstract/document/7911185) | | |
| | Privacy for Recommender Systems: Tutorial Abstract | Bart P. Knijnenburg, Shlomo Berkovsky | RecSys | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3109935) | | [:camera:](https://www.dropbox.com/s/55sdr62pqmpr20p/privacy-tutorial.pdf) |
| | Privacy in Location-Based Services: State-of-the-Art and Research Directions | Mohamed F. Mokbel | MDM | 2007 | [:ledger:](https://ieeexplore.ieee.org/abstract/document/4417152) | | [:camera:](https://www-users.cs.umn.edu/~mokbel/tutorials/MDM07-Privacy.ppt) |

[:top:](#awesome-privacy-protection-research-materials)

#### Basic Techniques

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| SVT-S | Understanding the Sparse Vector Technique for Differential Privacy | Min Lyu, Dong Su, Ninghui Li | VLDB | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3055331) | | |

[:top:](#awesome-privacy-protection-research-materials)

#### Private Framework

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| <img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" />KTELO | <img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" />KTELO: A Framework for Defining Differentially-Private Computations | Dan Zhang, Ryan McKenna, Ios Kotsogiannis, Michael Hay, Ashwin Machanavajjhala, Gerome Miklau | SIGMOD | 2018 | [:ledger:](https://dl.acm.org/citation.cfm?id=3196921) | | [:keyboard:](https://github.com/ektelo/ektelo) |

- [ ] PINQ: `Frank McSherry: Privacy integrated queries: an extensible platform for privacy-preserving data analysis. SIGMOD Conference 2009: 19-30`; `Davide Proserpio, Sharon Goldberg, Frank McSherry: Calibrating Data to Sensitivity in Private Data Analysis. PVLDB 7(8): 637-648 (2014)`
- [ ] Fuzz: `Marco Gaboardi, Andreas Haeberlen, Justin Hsu, Arjun Narayan, Benjamin C. Pierce: Linear dependent types for differential privacy. POPL 2013: 357-370`
- [ ] PrivInfer: `Gilles Barthe, Gian Pietro Farina, Marco Gaboardi, Emilio Jesús Gallego Arias, Andy Gordon, Justin Hsu, Pierre-Yves Strub: Differentially Private Bayesian Programming. ACM Conference on Computer and Communications Security 2016: 68-79`
- [ ] LightDP: `Danfeng Zhang, Daniel Kifer: LightDP: towards automating differential privacy proofs. POPL 2017: 888-901`

[:top:](#awesome-privacy-protection-research-materials)

#### Private Benchmark

- [ ] DPBench: `Michael Hay, Ashwin Machanavajjhala, Gerome Miklau, Yan Chen, Dan Zhang: Principled Evaluation of Differentially Private Algorithms using DPBench. SIGMOD Conference 2016: 139-154`

[:top:](#awesome-privacy-protection-research-materials)

#### Private Data Publishing

- [ ] `| | Differentially private data publishing for data analysis | Dong Su | | 2016 | [:ledger:](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=2220&context=open_access_dissertations) | | |`
- [ ] `| JTree | Differentially Private High-Dimensional Data Publication via Sampling-Based Inference | Rui Chen, Qian Xiao, Yu Zhang, Jianliang Xu | KDD | 2015 | [:ledger:](https://www.comp.hkbu.edu.hk/~xujl/Papers/kdd15.pdf) | | |`
- [ ] `| NoisyCut | Top-k frequent itemsets via differentially private FP-trees | Jaewoo Lee, Christopher W. Clifton | KDD | 2014 | [:ledger:](https://cybersecurity.uga.edu/publications/VI_KDD2014.pdf) | | |`
- [ ] `| PTT<br>k-RecursiveMedians | Differentially Private Algorithms for Empirical Machine Learning | Ben Stoddard, Yan Chen, Ashwin Machanavajjhala | CoRR | 2014 | [:ledger:](https://arxiv.org/pdf/1411.5428.pdf) | | |`

##### Transaction Data Publishing

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| PATE-GAN | PATE-GAN: Generating Synthetic Data with Differential Privacy Guarantees | James Jordon, Jinsung Yoon, Mihaela van der Schaar | ICLR | 2019 | [:ledger:](https://openreview.net/forum?id=S1zk9iRqF7) | | |
| Liancheng | Privacy as a Service: Publishing Data and Models | Ashish Dandekar, Debabrota Basu, Thomas Kister, Geong Sen Poh, Jia Xu, Stéphane Bressan | DASFAA | 2019 | [:ledger:](https://link.springer.com/chapter/10.1007%2F978-3-030-18590-9_86) | | |
| | A Data Publishing System Based on Privacy Preservation | Zhihui Wang, Yun Zhu, Xuchen Zhou | DASFAA | 2019 | [:ledger:](https://link.springer.com/chapter/10.1007%2F978-3-030-18590-9_85) | |
| | Approximate Query Processing using Deep Generative Models | Saravanan Thirumuruganathan, Shohedul Hasan, Nick Koudas, Gautam Das | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1903.10000) | | |
| G-PATE | Scalable Differentially Private Generative Student Model via PATE | Yunhui Long, Suxin Lin, Zhuolin Yang, Carl A. Gunter, Bo Li | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1906.09338) | | |
| DP-GAN-DNN | POSTER: A Unified Framework of Differentially Private Synthetic Data Release with Generative Adversarial Network | Pei-Hsuan Lu, Chia-Mu Yu | CCS | 2017  | [:ledger:](https://dl.acm.org/citation.cfm?doid=3133956.3138823) | | [:keyboard:](https://goo.gl/94qyQz) |
| PrivBayes | PrivBayes: Private Data Release via Bayesian Networks | Jun Zhang, Graham Cormode, Cecilia M. Procopiuc, Divesh Srivastava, Xiaokui Xiao | TODS<br>SIGMOD | 2017<br>2014 | [:ledger:](https://dl.acm.org/citation.cfm?doid=3155316.3134428)<br>[:ledger:](https://dl.acm.org/citation.cfm?doid=2588555.2588573) | | [:keyboard:](http://sourceforge.net/projects/privbayes/)<br>[:camera:](http://junzhangntu.weebly.com/uploads/1/2/3/6/12362230/2014.06_sigmod.pptx)[:camera:](http://junzhangntu.weebly.com/uploads/1/2/3/6/12362230/2014.06_sigmod_-_poster_v3.pdf) |
| | Efficient privacy-preserving temporal and spacial data aggregation for smart grid communications | Xiaolei Dong, Jun Zhou, Zhenfu Cao | Concurrency | 2016 | [:ledger:](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.3570) | [:memo:](notes/figures/EPPDA.png) | |

[:top:](#awesome-privacy-protection-research-materials)

##### Streaming Data Publishing

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| PeGaSus | PeGaSus: Data-Adaptive Differentially Private Stream Processing | Yan Chen, Ashwin Machanavajjhala, Michael Hay, Gerome Miklau | CCS | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3134102) | [:memo:](notes/2018-11-29-pegasus.md) | |

- [ ] `| CCDPSD | 异方差加噪下差分隐私流数据发布一致性优化算法 | 孙岚, 康健, 吴英杰, 张立群 | 清华大学学报 | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/11.2223.N.20180921.0900.001.html) | | |`
- [ ] `| | 面向实时数据流的差分隐私直方图发布技术 | 杨庚, 夏春婷, 白云璐 | 南京邮电大学学报 | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/detail.aspx?dbname=CJFDLAST2018&filename=NJYD201802014) | | |`
- [ ] `| PrivTree | PrivTree: A Differentially Private Algorithm for Hierarchical Decompositions | Jun Zhang, Xiaokui Xiao, Xing Xie | SIGMOD | 2016 | [:ledger:](http://delivery.acm.org/10.1145/2890000/2882928/p155-zhang.pdf) | | |`

[:top:](#awesome-privacy-protection-research-materials)

##### Graph Data Publishing

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| GSN-DP | Geo-social network publication based on differential privacy | Xiaochun Wang, Yidong Li | FCS | 2018 | [:ledger:](http://journal.hep.com.cn/fcs/EN/10.1007/s11704-018-8075-z) |  [:memo:](notes/2019-2-25-gsn-dp.md) | [:camera:](http://academic.hep.com.cn/fileup/2095-2228/SUPPL/20181115103924.zip) |

[:top:](#awesome-privacy-protection-research-materials)

##### Image Data Publishing

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| RPM| Random permutation Maxout transform for cancellable facial template protection | Andrew Beng Jin Teoh, Sejung Cho, Jihyeon Kim | MTA | 2018 | [:ledger:](https://doi.org/10.1007/s11042-018-5956-y) | [:memo:](notes/2019-5-29-rpm.pdf) | |
| BEMK | 面向人脸图像发布的差分隐私保护 | 张啸剑, 付聪聪, 孟小峰 | JIG | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2018&filename=ZGTB201809004) | [:memo:](notes/figures/BEMK.png) |  |
| DPGAN | Differentially Private Generative Adversarial Network | Liyang Xie, Kaixiang Lin, Shu Wang, Fei Wang, Jiayu Zhou | CoRR | 2018 | [:ledger:](https://arxiv.org/abs/1802.06739) | | [:keyboard:](https://github.com/illidanlab/dpgan) |

[:top:](#awesome-privacy-protection-research-materials)

#### Private Data Analysis

##### Private Learning

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Differentially Private Meta-Learning | 	Jeffrey Li, Mikhail Khodak, Sebastian Caldas, Ameet Talwalkar | ICLR | 2020 | [:ledger:](https://openreview.net/pdf?id=rJgqMRVYvr) | [:memo:](https://openreview.net/forum?id=rJgqMRVYvr) | |
| AdaClip | AdaCliP: Adaptive Clipping for Private SGD | Venkatadheeraj Pichapati, Ananda Theertha Suresh, Felix X. Yu, Sashank J. Reddi, Sanjiv Kumar | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1908.07643) | | |
| | Differentially Private Learning with Adaptive Clipping | Om Thakkar, Galen Andrew, H. Brendan McMahan | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1905.03871) | | |
| DP-FedAvg | Learning Differentially Private Recurrent Language Models | H. Brendan McMahan, Daniel Ramage, Kunal Talwar, Li Zhang | ICLR | 2018 | [:ledger:](https://openreview.net/pdf?id=BJ0hF1Z0b) | [:memo:](https://openreview.net/forum?id=BJ0hF1Z0b&noteId=BJ0hF1Z0b) | |
| | Differentially Private Federated Learning: A Client Level Perspective | Robin C. Geyer, Tassilo Klein, Moin Nabi | CoRR | 2017 | [:ledger:](https://arxiv.org/abs/1712.07557) | | [:keyboard:](https://github.com/SAP/machine-learning-diff-private-federated-learning)<br>[:floppy_disk:](https://openreview.net/forum?id=SkVRTj0cYQ) |
| DPSGD | Deep Learning with Differential Privacy | Martín Abadi, Andy Chu, Ian J. Goodfellow, H. Brendan McMahan, Ilya Mironov, Kunal Talwar, Li Zhang | CCS | 2016 | [:ledger:](https://dl.acm.org/citation.cfm?doid=2976749.2978318) | | [:floppy_disk:](https://arxiv.org/pdf/1607.00133.pdf)<br>[:keyboard:](https://github.com/tensorflow/privacy) |

[:top:](#awesome-privacy-protection-research-materials)

##### Frequent Itemset Mining

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Diff-FPM | Mining frequent graph patterns with differential privacy | Entong Shen, Ting Yu | KDD | 2013 | [:ledger:](https://dl.acm.org/citation.cfm?doid=2487575.2487601) | | [:camera:](https://www.dropbox.com/s/mwl88v6txc89ah9/KDD2013-slides.pdf) |

- [ ] `| PrivBasis | PrivBasis: Frequent Itemset Mining with Differential Privacy | Ninghui Li, Wahbeh H. Qardaji, Dong Su, Jianneng Cao | PVLDB | 2012 | [:ledger:](https://dl.acm.org/citation.cfm?id=2350251) | | [:keyboard:](https://github.com/DongSuIBM/PrivBasis) |`

[:top:](#awesome-privacy-protection-research-materials)

##### Recommender Systems

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| FedMF | Secure Federated Matrix Factorization | Di Chai, Leye Wang, Kai Chen, Qiang Yang | FML | 2019 | [:ledger:](https://arxiv.org/abs/1906.05108) | [:memo:](https://mp.weixin.qq.com/s/F6HvZeaPpQKmhKIxMFqBaQ) | [:keyboard:](https://github.com/Di-Chai/FedMF) |
| GD-DR | Privacy Enhanced Matrix Factorization for Recommendation with Local Differential Privacy | Hyejin Shin, Sungwook Kim, Junbum Shin, Xiaokui Xiao | TKDE | 2018 | [:ledger:](https://ieeexplore.ieee.org/document/8290673) | [:memo:](notes/2019-3-7-gd-dr.pdf) | |
| PrivSR | Personalized Privacy-Preserving Social Recommendation | Xuying Meng, Suhang Wang, Kai Shu, Jundong Li, Bo Chen, Huan Liu, Yujun Zhang | AAAI | 2018 | [:ledger:](http://www.public.asu.edu/~jundongl/paper/AAAI18_PrivSR.pdf) | [:memo:](notes/2018-11-21-privsr.md) | [:floppy_disk:](https://raw.githubusercontent.com/mxyenguing/PrivSR/854300602172d2e4d6d66810479f64134c0b55ed/appendix.pdf) |
| DMF | Privacy Preserving Point-of-Interest Recommendation Using Decentralized Matrix Factorization | Chaochao Chen, Ziqi Liu, Peilin Zhao, Jun Zhou, Xiaolong Li | AAAI | 2018 | [:ledger:](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16123) | [:memo:](https://mp.weixin.qq.com/s/JrUQupsoKqpwfd4bnYfwFA) | |
| EpicRec | EpicRec: Towards Practical Differentially Private Framework for Personalized Recommendation | Yilin Shen, Hongxia Jin | CCS | 2016 | [:ledger:](https://dl.acm.org/doi/10.1145/2976749.2978316) | | |
| DPMF | Differentially Private Matrix Factorization | Jingyu Hua, Chang Xia, Sheng Zhong | IJCAI | 2015 | [:ledger:](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/viewPaper/11228) | [:memo:](notes/2018-11-23-dpmf.md) | |
| DP-UnP3R | Privacy-Preserving Personalized Recommendation: An Instance-Based Approach via Differential Privacy | Yilin Shen, Hongxia Jin | ICDM | 2014 | [:ledger:](https://ieeexplore.ieee.org/document/7023371) | | |

[:top:](#awesome-privacy-protection-research-materials)

##### Survival Analysis

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Differentially Private Survival Function Estimation | Lovedeep Gondara, Ke Wang | CoRR | 2019 | [:ledger:](https://openreview.net/forum?id=ryx_Y6EYwH) | | [:keyboard:](https://bit.ly/2kNHC1J) | 

[:top:](#awesome-privacy-protection-research-materials)

#### Cryptography

##### Encrypted Database

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| CryptZip | Sa Wang, Yiwen Shao, Yungang Bao | Practices of backuping homomorphically encrypted databases | FCS | 2019 | [:ledger:](http://journal.hep.com.cn/fcs/EN/10.1007/s11704-019-8394-8) | | [:camera:](http://academic.hep.com.cn/fileup/2095-2228/SUPPL/20190326093134.pdf) |

[:top:](#awesome-privacy-protection-research-materials)

##### Searchable Encryption

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| SPiRiT | Secure Search on Encrypted Data via Multi-Ring Sketch | Adi Akavia, Dan Feldman, Hayim Shaul | CCS | 2018 | [:ledger:](https://dl.acm.org/citation.cfm?doid=3243734.3243810) | [:memo:](notes/2019-1-25-spirit.pdf) | |
| CPABKS | Secure and Efficient Attribute-Based Encryption with Keyword Search | Haijiang Wang, Xiaolei Dong, Zhenfu Cao, Dongmei Li | CJ | 2018 | [:ledger:](https://academic.oup.com/comjnl/article/61/8/1133/4975828) | [:memo:](notes/2019-2-20-cpabks.md) | |

[:top:](#awesome-privacy-protection-research-materials)

### Awesome Federated Learning Research Materials

A curated list of awesome federated learning research materials.

Courses:
- [Tutorial](#tutorial-1)

Papers:
- [Survey](#survey-1)
- Algorithm
    - [Communication](#communication)
    - [Aggregation](#aggregation)
    - [Application](#application)
- [System](#system)

[:top:](#diving-in)

#### Tutorial
| | Instructors | Institution | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| GDPR, Data Shortage and AI | Qiang Yang | HKUST | 2019 | | | [:camera:](https://videos.videoken.com/index.php/videos/aaai-2019-videos-invited-talk-qiang-yang-hkust-gdpr-data-shortage-and-ai/) |

[:top:](#awesome-federated-learning-research-materials)

#### Survey

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Federated Machine Learning: Concept and Applications | Qiang Yang, Yang Liu, Tianjian Chen, Yongxin Tong | TIST | 2019 | [:ledger:](https://arxiv.org/abs/1902.04885) | [:memo:](notes/figures/SFL.png) | [:floppy_disk:](https://mp.weixin.qq.com/s/6QKyE3jIOwBK_2rcG-Vtiw) |
| | Federated Learning | Florian Hartmann | | 2018 | [:ledger:](http://www.mi.fu-berlin.de/inf/groups/ag-ti/theses/master_finished/hartmann_florian/index.html) | | [:keyboard:](https://github.com/florian/federated-learning-addon)[:keyboard:](https://github.com/mozilla/telemetry-streaming/tree/master/src/main/scala/com/mozilla/telemetry/learning/federated)[:keyboard:](https://github.com/florian/federated-learning) |

[:top:](#awesome-federated-learning-research-materials)

#### Algorithm

##### Communication

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Efficient and Robust Asynchronous Federated Learning with Stragglers | Ming Chen, Bingcheng Mao, Tianyi Ma | CoRR | 2020 | [:ledger:](https://openreview.net/forum?id=B1lL9grYDS) | | |

[:top:](#awesome-federated-learning-research-materials)

##### Aggregation

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| q-FedAvg | Fair Resource Allocation in Federated Learning | Tian Li, Maziar Sanjabi, Virginia Smith | ICLR | 2020 | [:ledger:](https://openreview.net/forum?id=ByexElSYDr) | | |
| AFL | Agnostic Federated Learning | Mehryar Mohri, Gary Sivek, Ananda Theertha Suresh | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/mohri19a/mohri19a.pdf) | | [:floppy_disk:](http://proceedings.mlr.press/v97/mohri19a/mohri19a-supp.pdf)<br>[:camera:](https://icml.cc/Conferences/2019/ScheduleMultitrack?event=5038) |
| FedAvg | Communication-Efficient Learning of Deep Networks from Decentralized Data | Brendan McMahan, Eider Moore, Daniel Ramage, Seth Hampson, Blaise Agüera y Arcas | AISTATS | 2017 | [:ledger:](http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf) | | [:floppy_disk:](http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a-supp.pdf) |

[:top:](#awesome-federated-learning-research-materials)

##### Application

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Federated CIFG | Federated Learning for Mobile Keyboard Prediction | Andrew Hard, Kanishka Rao, Rajiv Mathews, Françoise Beaufays, Sean Augenstein, Hubert Eichner, Chloé Kiddon, Daniel Ramage | CoRR | 2018 | [:ledger:](https://arxiv.org/abs/1811.03604) | | [:floppy_disk:](https://mp.weixin.qq.com/s/fgV8wHd2lQEngzZGXteXTw)|
| | Federated Meta-Learning for Recommendation | Fei Chen, Zhenhua Dong, Zhenguo Li, Xiuqiang He | CoRR | 2018 | [:ledger:](https://arxiv.org/abs/1802.07876) | | |

[:top:](#awesome-federated-learning-research-materials)

#### System

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Towards Federated Learning at Scale: System Design | Keith Bonawitz, Hubert Eichner, Wolfgang Grieskamp, Dzmitry Huba, Alex Ingerman, Vladimir Ivanov, Chloé Kiddon, Jakub Konecný, Stefano Mazzocchi, H. Brendan McMahan, Timon Van Overveldt, David Petrou, Daniel Ramage, Jason Roselander | SysML | 2019 | [:ledger:](https://arxiv.org/abs/1902.01046) | | |

[:top:](#awesome-federated-learning-research-materials)

### Awesome Fairness Research Materials

A curated list of awesome fairness research materials.

Courses:
- [Tutorial](#tutorial-2)
- [Causal Fairness](#causal-fairness)

Papers:
- [Survey](#survey-2)
- [Statistical Fairness](#statistical-fairness)
- [Causal Fairness](#causal-fairness-1)
- [Resource Allocation](#resource-allocation)
- [Others](#others)
    - [Stability](#stability)

[:top:](#diving-in)

#### Tutorial
| | Instructors | Institution | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Fairness-Aware Machine Learning: Practical Challenges and Lessons Learned | Sarah Bird, Ben Hutchinson, Krishnaram Kenthapadi, Emre Kıcıman, Margaret Mitchell | Microsoft<br>Google<br>LinkedIn | KDD 2019 | | [:memo:](https://engineering.linkedin.com/blog/2019/fairness-privacy-transparency-by-design) | [:camera:](https://www.slideshare.net/KrishnaramKenthapadi/fairnessaware-machine-learning-practical-challenges-and-lessons-learned-kdd-2019-tutorial) |
| Challenges of incorporating algorithmic fairness into industry practice | Henriette Cramer, Ken Holstein, Jenn Wortman Vaughan, Hal Daumé III, Miroslav Dudík, Hanna Wallach, Sravana Reddy, Jean Garcia-Gathright | Microsoft Research | ACM FAccT 2019 | | | [:camera:](https://drive.google.com/file/d/1rUQkVS0NzSH3IEqZDsczSxBbhYHbjamN/view) |

[:top:](#awesome-fairness-research-materials)

#### Causal Fairness
| | Instructors | Institution | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Counterfactual reasoning in algorithmic fairness | Ricardo Silva | UCL<br>Alan Turing Institute | FairWare @ ICSE 2018 | | | [:camera:](http://fairware.cs.umass.edu/slides/silva.pdf) |
| Fairness in Machine Learning and Its Causal Aspects | Ricardo Silva | UCL<br>Alan Turing Institute | 2017 | | | [:camera:](http://www.homepages.ucl.ac.uk/~ucgtrbd/talks/counterfactual_fairness_talk.pdf) |

[:top:](#awesome-fairness-research-materials)

#### Survey

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | A Survey on Bias and Fairness in Machine Learning | Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, Aram Galstyan | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1908.09635) | | |
| | The Frontiers of Fairness in Machine Learning | Alexandra Chouldechova, Aaron Roth | CoRR | 2018 | [:ledger:](https://arxiv.org/pdf/1810.08810.pdf) | | |

[:top:](#awesome-fairness-research-materials)

#### Statistical Fairness

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| CFair | Conditional Learning of Fair Representations | Han Zhao, Amanda Coston, Tameem Adel, Geoffrey J. Gordon | ICLR | 2020 | [:ledger:](https://openreview.net/pdf?id=Hkekl0NFPr) | [:memo:](https://mp.weixin.qq.com/s/ig6jSvcW4_91FehlfN-O7A) | [:memo:](https://openreview.net/forum?id=Hkekl0NFPr) |
| Fairness warnings<br>fair-MAML | Fairness warnings and fair-MAML: learning fairly with minimal data | Dylan Slack, Sorelle A. Friedler, Emile Givental | FAT* | 2020 | [:ledger:](https://dl.acm.org/doi/abs/10.1145/3351095.3372839) | | [:memo:](https://dylanslacks.website/reviews/fairwarnfairmaml.txt)[:camera:](https://dylanslacks.website/assets/fairwarn-fairmaml-fat*.pdf)[:camera:](https://www.youtube.com/watch?v=QRbckrBzGE8&list=PLXA0IWa3BpHkaM6uJauBdtkR3Hp4rePfp)[:keyboard:](https://github.com/dylan-slack/fairness-warnings-fair-maml) |
| AdvDebias | Inherent Tradeoffs in Learning Fair Representations | Han Zhao, Geoffrey J. Gordon | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9698-inherent-tradeoffs-in-learning-fair-representations.pdf) | [:memo:](https://mp.weixin.qq.com/s/d1PJNo6ObkUtUfAPr3gSeg) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114-metareview.html)[:camera:](https://www.cs.cmu.edu/~hzhao1/papers/NIPS2019/fairness_poster.pdf)[:camera:](https://www.cs.cmu.edu/~hzhao1/papers/NIPS2019/fairness_slides.pdf)[:keyboard:](http://papers.nips.cc/paper/9698-inherent-tradeoffs-in-learning-fair-representations-supplemental.zip) |
| Random Repair | Obtaining Fairness using Optimal Transport Theory | Paula Gordaliza, Eustasio del Barrio, Fabrice Gamboa, Jean-Michel Loubes | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/gordaliza19a/gordaliza19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/gordaliza19a/gordaliza19a-supp.pdf)[:keyboard:](https://github.com/JMLToulouse/FairLearning)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-12-00-4857-obtaining_fairn.pdf) |
| FFVAE | Flexibly Fair Representation Learning by Disentanglement | Elliot Creager, David Madras, Jörn-Henrik Jacobsen, Marissa A. Weis, Kevin Swersky, Toniann Pitassi, Richard S. Zemel | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/creager19a/creager19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/creager19a/creager19a-supp.pdf)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-25-4853-flexibly_fair_r.pdf) |
| DP-postprocessing<br>DP-oracle-learner | Differentially Private Fair Learning | Matthew Jagielski, Michael J. Kearns, Jieming Mao, Alina Oprea, Aaron Roth, Saeed Sharifi-Malvajerdi, Jonathan Ullman | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/jagielski19a/jagielski19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/jagielski19a/jagielski19a-supp.pdf)[:camera:](https://slideslive.com/38916902/fairness?t=2645) |
| Fair Regression | Fair Regression: Quantitative Definitions and Reduction-Based Algorithms | Alekh Agarwal, Miroslav Dudík, Zhiwei Steven Wu | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/agarwal19d/agarwal19d.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/agarwal19d/agarwal19d-supp.pdf)[:keyboard:](https://github.com/steven7woo/fair_regression)[:keyboard:](https://github.com/fairlearn/fairlearn)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-30-4854-fair_regression.pdf) |
| Pairwise Fairness | Fairness in Recommendation Ranking through Pairwise Comparisons | Alex Beutel, Jilin Chen, Tulsee Doshi, Hai Qian, Li Wei, Yi Wu, Lukasz Heldt, Zhe Zhao, Lichan Hong, Ed H. Chi, Cristos Goodrow | KDD | 2019 | [:ledger:](https://dl.acm.org/citation.cfm?doid=3292500.3330745) | [:memo:](https://mp.weixin.qq.com/s/QJeOBXG6sIGb6ML6v8T8CQ) | [:camera:](https://www.kdd.org/kdd2019/accepted-papers/view/fairness-in-recommendation-ranking-through-pairwise-comparisons) |
| Strong Demographic Parity | Wasserstein Fair Classification | Ray Jiang, Aldo Pacchiano, Tom Stepleton, Heinrich Jiang, Silvia Chiappa | UAI | 2019 | [:ledger:](http://auai.org/uai2019/proceedings/papers/315.pdf) | | [:ledger:](http://auai.org/uai2019/proceedings/supplements/315_supplement.pdf)[:keyboard:](https://github.com/deepmind/wasserstein_fairness) |
| | Exploring Human Gender Stereotypes with Word Association Test | Yupei Du, Yuanbin Wu, Man Lan | EMNLP | 2019 | [:ledger:](https://yupei-du.github.io/papers/graph-bias.pdf) | | [:keyboard:](https://github.com/Yupei-Du/bias-in-wat) |
| AVD Penalizers<br>SD Penalizers | Penalizing Unfairness in Binary Classification | Yahav Bechavod, Katrina Ligett | CoRR | 2017 | [:ledger:](https://arxiv.org/abs/1707.00044) | | [:keyboard:](https://github.com/jjgold012/lab-project-fairness) |
| Equalized Odds | Equality of Opportunity in Supervised Learning | Moritz Hardt, Eric Price, Nati Srebro | NIPS | 2016 | [:ledger:](http://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning) | | [:ledger:](https://arxiv.org/abs/1610.02413)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips29/reviews/1654.html) |

[:top:](#awesome-fairness-research-materials)

#### Causal Fairness

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Counterfactual Privilege | Making Decisions that Reduce Discriminatory Impacts | 	Matt J. Kusner, Chris Russell, Joshua R. Loftus, Ricardo Silva | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/kusner19a/kusner19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/kusner19a/kusner19a-supp.pdf)[:keyboard:](https://github.com/mkusner/reducing_discriminatory_impact)<br>[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-12-15-4860-making_decision.pdf)[:camera:](https://www.dropbox.com/s/p2pnf5uiurd699d/MDRDI_2019.pdf) |
| Fair K<br>Fair Add | Counterfactual Fairness | Matt J. Kusner, Joshua R. Loftus, Chris Russell, Ricardo Silva | NIPS | 2017 | [:ledger:](http://papers.nips.cc/paper/6995-counterfactual-fairness) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/2152.html) | [:ledger:](http://papers.nips.cc/paper/6995-counterfactual-fairness-supplemental.zip)[:keyboard:](https://github.com/mkusner/counterfactual-fairness)[:camera:](http://mkusner.github.io/posters/CF_Poster.pdf)[:camera:](https://www.facebook.com/nipsfoundation/videos/1554741734617060/) |
| Multi-World Fairness | When Worlds Collide: Integrating Different Counterfactual Assumptions in Fairness | Chris Russell, Matt J. Kusner, Joshua R. Loftus, Ricardo Silva | NIPS | 2017 | [:ledger:](http://papers.nips.cc/paper/7220-when-worlds-collide-integrating-different-counterfactual-assumptions-in-fairness) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/3209.html) | [:camera:](https://drive.google.com/file/d/1YWV5PIzjNyapVvI5gUsKFcUttzEkcVt-/view) |

[:top:](#awesome-fairness-research-materials)

#### Resource Allocation

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Fair decision making using privacy-protected data | David Pujol, Ryan McKenna, Satya Kuppam, Michael Hay, Ashwin Machanavajjhala, Gerome Miklau | FAT* | 2020 | [:ledger:](https://dl.acm.org/doi/abs/10.1145/3351095.3372872) | | [:camera:](https://www.youtube.com/watch?v=ZsG7OA0sG6I&list=PLXA0IWa3BpHkaM6uJauBdtkR3Hp4rePfp&index=53)[:camera:](https://slideslive.com/38923327/invited-talk-fair-decision-making-using-privacyprotected-data) |
| DPSGD-F | Removing Disparate Impact of Differentially Private Stochastic Gradient Descent on Model Accuracy | Depeng Xu, Wei Du, Xintao Wu | CoRR | 2020 | [:ledger:](https://arxiv.org/abs/2003.03699) | | |
| FEN | Learning Fairness in Multi-Agent Systems | Jiechuan Jiang, Zongqing Lu | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9537-learning-fairness-in-multi-agent-systems.pdf) | | [:ledger:](http://papers.nips.cc/paper/9537-learning-fairness-in-multi-agent-systems-supplemental.zip)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755-metareview.html)[:keyboard:](https://github.com/PKU-AI-Edge/FEN) |
| | Differential Privacy Has Disparate Impact on Model Accuracy | Eugene Bagdasaryan, Omid Poursaeed, Vitaly Shmatikov | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9681-differential-privacy-has-disparate-impact-on-model-accuracy.pdf) | | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969-metareview.html)[:camera:](https://github.com/ebagdasa/differential-privacy-vs-fairness/blob/master/poster/neurips_diffprivacy_fairness.pdf)[:keyboard:](https://github.com/ebagdasa/differential-privacy-vs-fairness) |
| DC<br>Maximin | Group-Fairness in Influence Maximization | Alan Tsang, Bryan Wilder, Eric Rice, Milind Tambe, Yair Zick | IJCAI | 2019 | [:ledger:](https://www.ijcai.org/Proceedings/2019/831) | | [:memo:](https://arxiv.org/abs/1903.00967)[:keyboard:](https://github.com/bwilder0/fair_influmax_code_release) |
| TREE01 | Fairness without Harm: Decoupled Classifiers with Preference Guarantees | Berk Ustun, Yang Liu, David C. Parkes | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/ustun19a/ustun19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/ustun19a/ustun19a-supp.pdf)[:keyboard:](https://github.com/ustunb/dcptree)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-35-4855-fairness_withou.pdf) |
| Greedy Capture<br>Local Capture | Proportionally Fair Clustering | Xingyu Chen, Brandon Fain, Liang Lyu, Kamesh Munagala | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/chen19d.html) | | [:memo:](https://arxiv.org/abs/1905.03674)[:keyboard:](https://github.com/DukeXY/Proportionally-Fair-Clustering)[:camera:](https://slideslive.com/38917643/fairness) |
| GF1A/B | Group Fairness for the Allocation of Indivisible Goods | Vincent Conitzer, Rupert Freeman, Nisarg Shah, Jennifer Wortman Vaughan | AAAI | 2019 | [:ledger:](https://www.aaai.org/ojs/index.php/AAAI/article/view/4010) | | [:memo:](https://users.cs.duke.edu/~conitzer/group-fairness-full.pdf) |
| FULTR | Fair Learning-to-Rank from Implicit Feedback | Himank Yadav, Zhengxiao Du, Thorsten Joachims | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1911.08054) | | |

[:top:](#awesome-fairness-research-materials)

#### Others

##### Stability

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Stable-Fair | Stable and Fair Classification | Lingxiao Huang, Nisheeth K. Vishnoi | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/huang19e.html) | | [:memo:](http://proceedings.mlr.press/v97/huang19e.html) |

[:top:](#awesome-fairness-research-materials)

### Awesome Blockchain Research Materials

A curated list of awesome blockchain research materials.

- [Survey](#survey-3)
- [Network Layer](#network-layer)

[:top:](#diving-in)

#### Survey
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Yellow Paper | Ethereum: A Secure Decentralised Generalised Transaction Ledger | Dr. Gavin Wood | | | [:ledger:](https://ethereum.github.io/yellowpaper/paper.pdf) | | |
| 黄皮书 | 以太坊：一种安全去中心化的通用交易账本 | 崔广斌, 高天露 | | | [:ledger:](https://github.com/yuange1024/ethereum_yellowpaper/blob/master/ethereum_yellow_paper_cn.pdf) | | |
| | Untangling Blockchain: A Data Processing View of Blockchain Systems | Tien Tuan Anh Dinh, Rui Liu, Meihui Zhang, Gang Chen, Beng Chin Ooi, Ji Wang | TKDE | 2018 | [:ledger:](https://ieeexplore.ieee.org/abstract/document/8246573) | | [:floppy_disk:](http://www.mzhtechnologies.com/paper/mzh_blockchain_whitepaper_pub.pdf) |
| | 区块链隐私保护研究综述 | 祝烈煌, 高峰, 沈蒙, 李艳东, 郑宝昆, 毛洪亮, 吴震 | 计算机研究与发展 | 2017 | [:ledger:](http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2017&filename=JFYZ201710006) | | |

[:top:](#awesome-blockchain-research-materials)

#### Network Layer
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| BlockFL | On-Device Federated Learning via Blockchain and its Latency Analysis | Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim | CoRR | 2018 | [:ledger:](https://arxiv.org/abs/1808.03949) | | |

[:top:](#awesome-blockchain-research-materials)

### Other Awesome Research Materials

A curated list of awesome research materials.

- [Artificial Intelligence](#artificial-intelligence)
- [Large-Scale Optimization](#large-scale-optimization)
- [Combinatorial optimization](#combinatorial-optimization)

[:top:](#diving-in)

#### Artificial Intelligence
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Meta-Learning in Neural Networks: A Survey | Timothy M. Hospedales, Antreas Antoniou, Paul Micaelli, Amos J. Storkey | CoRR | 2020 | [:ledger:](https://arxiv.org/abs/2004.05439) | [:memo:](https://zhuanlan.zhihu.com/p/133159617) | |
| | AI Governance in 2019 a Year in Review | Qian Shi, Hui Li, Brian Tse, John Hopcroft, Stuart Russell, Caroline Jeanmaire, Qiang Yang, Pascale Fung, Roman Yampolskiy, Allan Dafoe, Markus Anderljung, Gillian K. Hadfield, Jun Su, Thilo Hagendorff, Petra Ahrweiler, Robin Williams, Colin Allen, Poon King Wang, Ferran Jarabo Carbonell, Xiaohong Wang, Qingfeng Yang, Qi Yin, Don Wright, Miles Brundage, Jack Clark, Irene Solaiman, Gretchen Krueger, Seán Ó hÉigeartaigh, Helen Toner, Millie Liu, Steve Hoffman, Irakli Beridze, Wendell Wallach, Cyrus Hodes, Nicolas Miailhe, Jessica Cussins Newman, Dingding Chen, Eva Kaili, Francesca Rossi, Charlotte Stix, Angela Daly, Danit Gal, Arisa Ema, Goh Yihan, Nydia Remolina, Urvashi Aneja, Ying Fu, Zhiyun Zhao, Xiuquan Li, Weiwen Duan, Qun Luan, Rui Guo, Yingchun Wang |Shanghai Institute for Science of Science | 2020 | [:ledger:](https://n1.sinaimg.cn/tech/f34884a9/20200501/GlobalAIGovernancein2019.pdf) | [:memo:](https://mp.weixin.qq.com/s/e3iXM17g3ug1JiwCZd-9cA) | |
| Meta-Weight-Net| Meta-Weight-Net: Learning an Explicit Mapping For Sample Weighting | Jun Shu, Qi Xie, Lixuan Yi, Qian Zhao, Sanping Zhou, Zongben Xu, Deyu Meng | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/8467-meta-weight-net-learning-an-explicit-mapping-for-sample-weighting.pdf) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/1107.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/1107-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/1107-metareview.html) | [:ledger:](http://papers.nips.cc/paper/8467-meta-weight-net-learning-an-explicit-mapping-for-sample-weighting-supplemental.zip)[:keyboard:](https://github.com/xjtushujun/meta-weight-net) |
| | Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI | Alejandro Barredo Arrieta, Natalia Díaz Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador García, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1910.10045) | [:memo:](https://mp.weixin.qq.com/s/kJW-EM20C5JEQIKNtBYVtA) | |

[:top:](#other-awesome-research-materials)

#### Large-Scale Optimization
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| BDA | A Generic First-Order Algorithmic Framework for Bi-Level Programming Beyond Lower-Level Singleton | Risheng Liu, Pan Mu, Xiaoming Yuan, Shangzhi Zeng, Jin Zhang | ICML | 2020 | [:ledger:](https://arxiv.org/abs/2006.04045) | | |
| AGD+ | On Acceleration with Noise-Corrupted Gradients | Michael Cohen, Jelena Diakonikolas, Lorenzo Orecchia | ICML | 2018 | [:ledger:](http://proceedings.mlr.press/v80/cohen18a/cohen18a.pdf) |  | [:floppy_disk:](http://proceedings.mlr.press/v80/cohen18a/cohen18a-supp.pdf) |

- [ ] `Olivier Devolder, François Glineur, Yurii Nesterov: First-order methods of smooth convex optimization with inexact oracle. Math. Program. 146(1-2): 37-75 (2014)`
- [ ] `Alexandre d'Aspremont: Smooth Optimization with Approximate Gradient. SIAM Journal on Optimization 19(3): 1171-1183 (2008)`

[:top:](#other-awesome-research-materials)

#### Combinatorial optimization
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| GSLS | Optimizing top-k retrieval: submodularity analysis and search strategies | Chaofeng Sha, Keqiang Wang, Dell Zhang, Xiaoling Wang, Aoying Zhou | FCS<br>WAIM | 2016<br>2014 | [:ledger:](https://link.springer.com/article/10.1007%2Fs11704-015-5222-7)<br>[:ledger:](https://doi.org/10.1007/978-3-319-08010-9_3) | | |
| SubmEP | Ensemble Pruning: A Submodular Function Maximization Perspective | Chaofeng Sha, Keqiang Wang, Xiaoling Wang, Aoying Zhou | DASFAA | 2014 | [:ledger:](https://link.springer.com/chapter/10.1007%2F978-3-319-05813-9_1) | | |

[:top:](#other-awesome-research-materials)


Join discussion in [issues](https://github.com/WenyanLiu/apprenticeship/issues).
