# Awesome Privacy Protection Papers

A curated list of awesome privacy protection papers.

## Contents

- [Policy Brief](#policy-brief)
- [Survey](#survey)
- [Differential Privacy Basic Techniques](#differential-privacy-basic-techniques)
- [Differentially Private Framework](#differentially-private-framework)
- [Differentially Private Benchmark](#differentially-private-benchmark)
- [Differentially Private Data Publishing and Analysis](#differentially-private-data-publishing-and-analysis)
- [Differentially Private Frequent Itemset Mining](#differentially-private-frequent-itemset-mining)
- [Differentially Private Graph Data](#differentially-private-graph-data)
- [Differentially Private Image Data](#differentially-private-image-data)
- [Differentially Private Recommender Systems](#differentially-private-recommender-systems)
- [Differentially Private Streaming Data](#differentially-private-streaming-data)
- [Large-Scale Optimization](#large-scale-optimization)
- [Secure Data Publishing and Mining](#secure-data-publishing-and-mining)
- [Searchable Encryption](#searchable-encryption)

**Legend**:

| :ledger: | :memo: | :keyboard: | :camera: | :floppy_disk: |
| :-: | :-: |  :-: |  :-: |  :-: | 
| PDF<br>Files | Notes | Code | Slides | Other<br>Supplementaries |

---

#### Policy Brief
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|  | China's Social Credit System: A Mark of Progress or a Threat to Privacy? | Martin Chorzempa, Paul Triolo, Samm Sacks |  | 2018 | [:ledger:](https://piie.com/publications/policy-briefs/chinas-social-credit-system-mark-progress-or-threat-privacy) | / | [:floppy_disk:](http://www.yuandiancredit.com/h-nd-2945.html) |

[:top:](#contents)

#### Survey
| Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Federated Machine Learning: Concept and Applications | Qiang Yang, Yang Liu, Tianjian Chen, Yongxin Tong | TIST | 2019 | [:ledger:](https://arxiv.org/abs/1902.04885) | [:memo:](notes/figures/SFL.png) | [:floppy_disk:](https://mp.weixin.qq.com/s/6QKyE3jIOwBK_2rcG-Vtiw) |
| Differentially Private Data Publishing and Analysis: A Survey | Tianqing Zhu, Gang Li, Wanlei Zhou, Philip S. Yu | TKDE | 2017 | [:ledger:](https://ieeexplore.ieee.org/abstract/document/7911185) | | |
| Privacy for Recommender Systems: Tutorial Abstract | Bart P. Knijnenburg, Shlomo Berkovsky | RecSys | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3109935) | | [:camera:](https://www.dropbox.com/s/55sdr62pqmpr20p/privacy-tutorial.pdf) |
| Privacy in Location-Based Services: State-of-the-Art and Research Directions | Mohamed F. Mokbel | MDM | 2007 | [:ledger:](https://ieeexplore.ieee.org/abstract/document/4417152) | | [:camera:](https://www-users.cs.umn.edu/~mokbel/tutorials/MDM07-Privacy.ppt) |

[:top:](#contents)

#### Differential Privacy Basic Techniques
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| SVT-S | Understanding the Sparse Vector Technique for Differential Privacy | Min Lyu, Dong Su, Ninghui Li | VLDB | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3055331) | | |

[:top:](#contents)

#### Differentially Private Framework
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| <img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" />KTELO | <img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" />KTELO: A Framework for Defining Differentially-Private Computations | Dan Zhang, Ryan McKenna, Ios Kotsogiannis, Michael Hay, Ashwin Machanavajjhala, Gerome Miklau | SIGMOD | 2018 | [:ledger:](https://dl.acm.org/citation.cfm?id=3196921) | | [:keyboard:](https://github.com/ektelo/ektelo) |

- [ ] PINQ: `Frank McSherry: Privacy integrated queries: an extensible platform for privacy-preserving data analysis. SIGMOD Conference 2009: 19-30`; `Davide Proserpio, Sharon Goldberg, Frank McSherry: Calibrating Data to Sensitivity in Private Data Analysis. PVLDB 7(8): 637-648 (2014)`
- [ ] Fuzz: `Marco Gaboardi, Andreas Haeberlen, Justin Hsu, Arjun Narayan, Benjamin C. Pierce: Linear dependent types for differential privacy. POPL 2013: 357-370`
- [ ] PrivInfer: `Gilles Barthe, Gian Pietro Farina, Marco Gaboardi, Emilio Jesús Gallego Arias, Andy Gordon, Justin Hsu, Pierre-Yves Strub: Differentially Private Bayesian Programming. ACM Conference on Computer and Communications Security 2016: 68-79`
- [ ] LightDP: `Danfeng Zhang, Daniel Kifer: LightDP: towards automating differential privacy proofs. POPL 2017: 888-901`

[:top:](#contents)

#### Differentially Private Benchmark

- [ ] DPBench: `Michael Hay, Ashwin Machanavajjhala, Gerome Miklau, Yan Chen, Dan Zhang: Principled Evaluation of Differentially Private Algorithms using DPBench. SIGMOD Conference 2016: 139-154`

[:top:](#contents)

#### Differentially Private Data Publishing and Analysis
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |

- [ ] `| | Differentially private data publishing for data analysis | Dong Su | | 2016 | [:ledger:](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=2220&context=open_access_dissertations) | | |`
- [ ] `| JTree | Differentially Private High-Dimensional Data Publication via Sampling-Based Inference | Rui Chen, Qian Xiao, Yu Zhang, Jianliang Xu | KDD | 2015 | [:ledger:](https://www.comp.hkbu.edu.hk/~xujl/Papers/kdd15.pdf) | | |`
- [ ] `| NoisyCut | Top-k frequent itemsets via differentially private FP-trees | Jaewoo Lee, Christopher W. Clifton | KDD | 2014 | [:ledger:](https://cybersecurity.uga.edu/publications/VI_KDD2014.pdf) | | |`
- [ ] `| PTT<br>k-RecursiveMedians | Differentially Private Algorithms for Empirical Machine Learning | Ben Stoddard, Yan Chen, Ashwin Machanavajjhala | CoRR | 2014 | [:ledger:](https://arxiv.org/pdf/1411.5428.pdf) | | |`

[:top:](#contents)

#### Differentially Private Frequent Itemset Mining
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Diff-FPM | Mining frequent graph patterns with differential privacy | Entong Shen, Ting Yu | KDD | 2013 | [:ledger:](https://dl.acm.org/citation.cfm?doid=2487575.2487601) | | |

- [ ] `| PrivBasis | PrivBasis: Frequent Itemset Mining with Differential Privacy | Ninghui Li, Wahbeh H. Qardaji, Dong Su, Jianneng Cao | PVLDB | 2012 | [:ledger:](https://dl.acm.org/citation.cfm?id=2350251) | | [:keyboard:](https://github.com/DongSuIBM/PrivBasis) |`

[:top:](#contents)

#### Differentially Private Graph Data
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| GSN-DP | Geo-social network publication based on differential privacy | Xiaochun Wang, Yidong Li | FCS | 2018 | [:ledger:](http://journal.hep.com.cn/fcs/EN/10.1007/s11704-018-8075-z) |  [:memo:](notes/2019-2-25-gsn-dp.md) | [:camera:](http://academic.hep.com.cn/fileup/2095-2228/SUPPL/20181115103924.zip) |

[:top:](#contents)

#### Differentially Private Image Data
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| BEMK | 面向人脸图像发布的差分隐私保护 | 张啸剑, 付聪聪, 孟小峰 | JIG | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2018&filename=ZGTB201809004) | [:memo:](notes/figures/BEMK.png) |  |

[:top:](#contents)

#### Differentially Private Recommender Systems

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| GD-DR | Privacy Enhanced Matrix Factorization for Recommendation with Local Differential Privacy | Hyejin Shin, Sungwook Kim, Junbum Shin, Xiaokui Xiao | TKDE | 2018 | [:ledger:](https://ieeexplore.ieee.org/document/8290673) | [:memo:](notes/2019-3-7-gd-dr.pdf) | |
| PrivSR | Personalized Privacy-Preserving Social Recommendation | Xuying Meng, Suhang Wang, Kai Shu, Jundong Li, Bo Chen, Huan Liu, Yujun Zhang | AAAI | 2018 | [:ledger:](http://www.public.asu.edu/~jundongl/paper/AAAI18_PrivSR.pdf) | [:memo:](notes/2018-11-21-privsr.md) | [:floppy_disk:](https://raw.githubusercontent.com/mxyenguing/PrivSR/854300602172d2e4d6d66810479f64134c0b55ed/appendix.pdf) |
| DMF | Privacy Preserving Point-of-Interest Recommendation Using Decentralized Matrix Factorization | Chaochao Chen, Ziqi Liu, Peilin Zhao, Jun Zhou, Xiaolong Li | AAAI | 2018 | [:ledger:](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16123) | [:memo:](https://mp.weixin.qq.com/s/JrUQupsoKqpwfd4bnYfwFA) | |
| DPMF | Differentially Private Matrix Factorization | Jingyu Hua, Chang Xia, Sheng Zhong | IJCAI | 2015 | [:ledger:](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/viewPaper/11228) | [:memo:](notes/2018-11-23-dpmf.md) | |

[:top:](#contents)

#### Differentially Private Streaming Data

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| PeGaSus | PeGaSus: Data-Adaptive Differentially Private Stream Processing | Yan Chen, Ashwin Machanavajjhala, Michael Hay, Gerome Miklau | CCS | 2017 | [:ledger:](https://dl.acm.org/citation.cfm?id=3134102) | [:memo:](notes/2018-11-29-pegasus.md) | |

- [ ] `| CCDPSD | 异方差加噪下差分隐私流数据发布一致性优化算法 | 孙岚, 康健, 吴英杰, 张立群 | 清华大学学报 | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/11.2223.N.20180921.0900.001.html) | | |`
- [ ] `| | 面向实时数据流的差分隐私直方图发布技术 | 杨庚, 夏春婷, 白云璐 | 南京邮电大学学报 | 2018 | [:ledger:](http://kns.cnki.net/KCMS/detail/detail.aspx?dbname=CJFDLAST2018&filename=NJYD201802014) | | |`
- [ ] `| PrivTree | PrivTree: A Differentially Private Algorithm for Hierarchical Decompositions | Jun Zhang, Xiaokui Xiao, Xing Xie | SIGMOD | 2016 | [:ledger:](http://delivery.acm.org/10.1145/2890000/2882928/p155-zhang.pdf) | | |`

[:top:](#contents)

#### Large-Scale Optimization
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| AGD+ | On Acceleration with Noise-Corrupted Gradients | Michael Cohen, Jelena Diakonikolas, Lorenzo Orecchia | ICML | 2018 | [:ledger:](http://proceedings.mlr.press/v80/cohen18a/cohen18a.pdf) |  | [:floppy_disk:](http://proceedings.mlr.press/v80/cohen18a/cohen18a-supp.pdf) |

- [ ] `Olivier Devolder, François Glineur, Yurii Nesterov: First-order methods of smooth convex optimization with inexact oracle. Math. Program. 146(1-2): 37-75 (2014)`
- [ ] `Alexandre d'Aspremont: Smooth Optimization with Approximate Gradient. SIAM Journal on Optimization 19(3): 1171-1183 (2008)`

[:top:](#contents)

#### Secure Data Publishing and Mining
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Efficient privacy-preserving temporal and spacial data aggregation for smart grid communications | Xiaolei Dong, Jun Zhou, Zhenfu Cao | Concurrency | 2016 | [:ledger:](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.3570) | [:memo:](notes/figures/EPPDA.png) | |

[:top:](#contents)

#### Searchable Encryption
| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| SPiRiT | Secure Search on Encrypted Data via Multi-Ring Sketch | Adi Akavia, Dan Feldman, Hayim Shaul | CCS | 2018 | [:ledger:](https://dl.acm.org/citation.cfm?doid=3243734.3243810) | [:memo:](notes/2019-1-25-spirit.pdf) | |
| CPABKS | Secure and Efficient Attribute-Based Encryption with Keyword Search | Haijiang Wang, Xiaolei Dong, Zhenfu Cao, Dongmei Li | CJ | 2018 | [:ledger:](https://academic.oup.com/comjnl/article/61/8/1133/4975828) | [:memo:](notes/2019-2-20-cpabks.md) | |

[:top:](#contents)