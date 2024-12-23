![image](https://github.com/user-attachments/assets/e3a77a95-a540-4497-9ab1-e8280e866add)![image](https://github.com/user-attachments/assets/fc28e0b9-7202-4eb5-b70d-bb2b6770d2cb)![image](https://github.com/user-attachments/assets/dcabb6d0-18b8-46d8-9104-6e5ac7a8a59c)[stars-img]: https://img.shields.io/github/stars/LIANGKE23/Awesome-Knowledge-Graph-Reasoning?color=yellow
[stars-url]: https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning/stargazers
[fork-img]: https://img.shields.io/github/forks/LIANGKE23/Awesome-Knowledge-Graph-Reasoning?color=lightblue&label=fork
[fork-url]: https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning/network/members
[AKGR-url]: https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning

# AKGR: Awesome Knowledge Graph Reasoning

AKGR is a collection of knowledge graph reasoning works, including papers, codes and datasets :fire:. Any problems, please contact liangke200694@126.com or liangke200694@gmail.com. Any other interesting papers or codes are welcome. If you find this repository useful to your research or work, it is really appreciated to star this repository.:heart:

[![GitHub stars][stars-img]][stars-url]
[![GitHub forks][fork-img]][fork-url]

<div  align="center">    
    <img src="./logo_new.png" width=100% />
</div>


🌻  If the corresponding survey paper is also useful for you, please cite here: 
```
@ARTICLE{10577554,
  author={Liang, Ke and Meng, Lingyuan and Liu, Meng and Liu, Yue and Tu, Wenxuan and Wang, Siwei and Zhou, Sihang and Liu, Xinwang and Sun, Fuchun and He, Kunlun},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
  title={A Survey of Knowledge Graph Reasoning on Graph Types: Static, Dynamic, and Multi-Modal}, 
  year={2024},
  volume={},
  number={},
  pages={1-20},
  doi={10.1109/TPAMI.2024.3417451}}

```

# Bookmarks <span id="bookmarks"></span>
- [Survey Papers](#survey-papers-)
- [Datasets](#datasets-)  :fire:
- - [Static Knowledge Graphs](#static-knowledge-graphs-)
- - - [Transductive Datasets](#transductive-datasets-) 
- - - [Inductive Datasets](#inductive-datasets-)
- - [Temporal Knowledge Graphs](#temporal-knowledge-graphs-) 
- - [Multi-Modal Knowledge Graphs](#multi-modal-knowledge-graphs-)
- [Static Knowledge Graph Reasoning](#static-knowledge-graph-reasoning-)
- - [Translational Models](#translational-models-)
- - [Tensor Decompositional Models](#tensor-decompositional-models-)
- - [Neural Network Models](#neural-network-models-)
- - - [Traditional Neural Network Models](#traditonal-neural-network-models-)
- - - [Convolutional Neural Network Models](#convolutional-neural-network-models-)
- - - [Graph Neural Network Models](#graph-neural-network-models-)
- - - [Transformer Models](#transformer-models-)
- - [Path-based Models](#path-based-models-)
- - [Rule-based Models](#rule-based-models-)
- [Temporal Knowledge Graph Reasoning](#temporal-knowledge-graph-reasoning-)
- - [RNN-based Models](#rnn-based-models-)
- - - [Quadruple-based Models](#quadruple-based-models-)
- - - [Path-based Models](#path-based-models-)
- - - [Graph-based Models](#graph-based-models-)
- - [RNN-agnostic Models](#rnn-agnostic-models-)
- - - [Time-Vector Guided Models](#time-vector-guided-models-)
- - - [Time-Operation Guided Models](#time-operation-guided-models-)
- [Multi-Modal Knowledge Graph Reasoning](#multi-modal-knowledge-graph-reasoning-)
- - [Transformer-agnostic Models](#transformer-agnostic-models-)
- - [Transformer-based Models](#transformer-based-models-)
- [Useful Libararies](#useful-libararies-)




## Survey Papers <span id="survey-papers-"></span>
| **Year**   | **Title**                                                                                     |  **Venue**    |                                       **Paper**                                            | **Code** |
| ---- |----------------------------------------------------------------------------------|:--------:|:---------------------------------------------------------------------------------:|:----:|
| 2024  | **A Survey of Knowledge Graph Reasoning on Graph Types: Static, Dynamic, and Multimodal (Ours)**   |  TPAMI    |                   [Link](https://arxiv.org/pdf/2212.05767.pdf)                    | [Link](https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning)     |
| 2023  | **Unifying Large Language Models and Knowledge Graphs: A Roadmap**  |  arXiv    |                   [Link](https://arxiv.org/abs/2306.08302)                    | [Link](https://github.com/RManLuo/Awesome-LLM-KG)  |
| 2023  | **A Survey on Temporal Knowledge Graph Completion: Taxonomy, Progress, and Prospects**  |  arXiv    |                   [Link](https://arxiv.org/pdf/2308.02457)                    | [Link](https://github.com/jiapuwang/Awesome-TKGC)  |
| 2023  | **Generalizing to Unseen Elements: A Survey on Knowledge Extrapolation for Knowledge Graphs**  |  arXiv    |                   [Link](https://arxiv.org/pdf/2302.01859.pdf)                    | -     |
| 2022  | **Knowledge Graph Reasoning with Logics and Embeddings: Survey and Perspective**  |  arXiv    |                   [Link](https://arxiv.org/pdf/2202.07412.pdf)                    |  -   |
| 2022  | **An Overview of Knowledge Graph Reasoning: Key Technologies and Applications**  |  Journal of Sensor and Actuator Networks    |                   [Link](https://www.mdpi.com/2224-2708/11/4/78/pdf)                    |  -   |
| 2021  | **Neural, symbolic and neural-symbolic reasoning on knowledge graphs**  |  Open AI    |                   [Link](https://www.sciencedirect.com/science/article/pii/S2666651021000061)                    |  -   |
| 2020  | **Hybrid reasoning in knowledge graphs: Combing symbolic reasoning and statistical reasoning**  |  Semantic Web   |                   [Link](http://www.semantic-web-journal.net/system/files/swj2287.pdf)                    |  -   |
| 2020   | **A Review: Knowledge Reasoning over Knowledge Graph**                            |  ESWA      |       [Link](https://www.sciencedirect.com/science/article/pii/S0957417419306669) | -    |

[Back](#bookmarks-)

# Datasets <span id="datasets-"></span>
##  Static KGR Datasets  <span id="static-knowledge-graphs-"></span>
###  Transductive Datasets  <span id="transductive-datasets-"></span>
|                                                 Dataset                                                 | # Entities | # Relations | # Train Triplets | # Val. Triplets | # Test Triplets |                                             # Description                                              |
|:-------------------------------------------------------------------------------------------------------:|:----------:|:-----------:|:----------------:|:---------------:|:---------------:|:------------------------------------------------------------------------------------------------------:|
|     [ATOMIC](https://drive.google.com/file/d/1fSzWoza9kzs_Am2NPVLa5E0wzYzQIdrw/view?usp=share_link)     |   309515   |      9      |      610536      |      87700      |      87701      |                              [Link](https://arxiv.org/pdf/1811.00146.pdf)                              |   
|   [Countries](https://drive.google.com/file/d/1l7dorRj_ftCLoFTJbkggB3eZ0Vw4TaCM/view?usp=share_link)    |    271     |      2      |       1110       |       24        |       24        |              [Link](https://www.aaai.org/ocs/index.php/SSS/SSS15/paper/view/10257/10026)               |  
|    [CoDEX-S](https://drive.google.com/file/d/1T14sLxN8-HkCN1SteZCCzwleBQJagYeF/view?usp=share_link)     |   2034 	   |     42      |      32888       |      3654       |      3656       |                              [Link](https://arxiv.org/pdf/2009.07810.pdf)                              | 
|    [CoDEX-M](https://drive.google.com/file/d/14APu4U1-FtWjkSJ2RmpS4_AjzrLVwAoX/view?usp=share_link)     |   17050    |     51      |      185584      |      20620      |      20622      |                              [Link](https://arxiv.org/pdf/2009.07810.pdf)                              | 
|    [CoDEX-L](https://drive.google.com/file/d/1PKgbpuJ6JtDxk11TJH0kCq4LiBDOIt73/view?usp=share_link)     |   77951    |     69      |      551193      |      30622      |      30622      |                              [Link](https://arxiv.org/pdf/2009.07810.pdf)                              | 
|                        [ConceptNet](https://github.com/commonsense/conceptnet5)                         |  28370083  |     36      |     27259933     |     3407492     |     3407492     |                              [Link](https://arxiv.org/pdf/1612.03975.pdf)                              |  
| [ConceptNet100K](https://drive.google.com/file/d/1KS_VHu5L3Jl28DF5dWegUfpFg9o-6Wga/view?usp=share_link) |   78334    |     34      |      100000      |      1200       |      1200       |                        [Link](https://aclanthology.org/2021.emnlp-main.657.pdf)                        |
|   [DBpedia50](https://drive.google.com/file/d/1-j7bQYUP8YplUoeJgFQlTTT_fzJ9-5eq/view?usp=share_link)    |   49900    |     654     |      32388       |       399       |      10969      |                              [Link](https://arxiv.org/pdf/1711.03438.pdf)                              |
|   [DBpedia500](https://drive.google.com/file/d/1wKSjDQjB5E2g8De22NzdQOzIX2IZARW0/view?usp=share_link)   |   517475   |     654     |     3102677      |      10000      |     1155937     |                              [Link](https://arxiv.org/pdf/1711.03438.pdf)                              |   
|     [DB100K](https://drive.google.com/file/d/1qxgVU-2EdFRT8q2qoZcRLT9pnb4vwRtk/view?usp=share_link)     |   99604    |     470     |      597482      |      49997      |      50000      |                              [Link](https://arxiv.org/abs/1805.02408.pdf)                              |  
|     [FAMILY](https://drive.google.com/file/d/14_hrPmJjU8Sh74hSbKADrQ0FpVJYUFeg/view?usp=share_link)     |    3007    |     12      |      23483       |      2038       |      2835       |                    [Link](https://homes.cs.washington.edu/~pedrod/papers/mlc07.pdf)                    |   
|      [FB13](https://drive.google.com/file/d/13uNhAF5DrIoC8P-3T60v93eUUY08I7eP/view?usp=share_link)      |   75043    |     13      |      316232      |      11816      |      47464      |     [Link](https://papers.nips.cc/paper/2013/hash/b337e84de8752b27eda3a12363109e80-Abstract.html)      |
|     [FB122](https://drive.google.com/file/d/1pgXZEeAMoV8xUi9G6dC7NtTE1UKM9xPz/view?usp=share_link)      |    9738    |     122     |      91638       |      9595       |      11243      |                             [Link](https://aclanthology.org/D16-1019.pdf)                              |  
|     [FB15k](https://drive.google.com/file/d/1dAJ19TelcMDPCmCcrlAgKw3M9bN-SGas/view?usp=share_link)      |   14951    |    1345     |      483142      |      50000      |      59071      | [Link](https://www.aclweb.org/anthology/W15-4007/) |   
|     [FB20k](https://drive.google.com/file/d/1GIEc0ltFr-cAA--PHsfW1iXJJ1mUu6n2/view?usp=share_link)      |   19923    |    1345     |      472860      |      48991      |      90149      |                              [Link](https://arxiv.org/pdf/1711.03438.pdf)                              |   
|     [FB24k](https://drive.google.com/file/d/1gENQMFLk_aiK7RgmFsbsOpZyt0jHiPC2/view?usp=share_link)      |   23634    |    673     |      402493      |      -     |      21067      |                              [Link](https://www.ijcai.org/Proceedings/16/Papers/407.pdf)                              |
|   [FB15K-237](https://drive.google.com/file/d/1SYVUTXnRVwyeFcbqbzl-fO-oUDfbhnSi/view?usp=share_link)    |   14541    |     237     |      272115      |      17535      |      20466      |                           [Link](https://arxiv.org/pdf/1703.06103.pdf)                           |  
|  [FB60K-NYT10](https://drive.google.com/file/d/1JDSSCNAPMmNVKsZL8VjOZ4aEH29RE1J-/view?usp=share_link)   |   69514    |    1327     |      268280      |      8765       |      8918       |                              [Link](https://arxiv.org/pdf/1909.00230.pdf)                              |
|                    [Hetionet](https://github.com/hetio/hetionet/tree/master/hetnet)                     |   47031    |     24      |     1800157      |     225020      |     225020      |                              [Link](https://doi.org/10.7554/eLife.26726)                               |  
|      [Kinship](https://drive.google.com/file/d/1Px46EtYVjD7wTT3leqaTpHjK7eBKgdII/view?usp=sharing)      |    104     |     25      |       8544       |      1068       |      1074       |                      [Link](https://www.aaai.org/Papers/AAAI/2006/AAAI06-061.pdf)                      | 
|    [Location](https://drive.google.com/file/d/1UfghdNxZRKoS0s9cuLfQvZ2FoiWogXEJ/view?usp=share_link)    |    445     |      5      |       384        |       65        |       65        |                        [Link](https://www.ijcai.org/proceedings/2020/0413.pdf)                         |   
|     [Nation](https://drive.google.com/file/d/140ERPY0FwMY8QAay6CsBalbyghaHsyfD/view?usp=share_link)     |     14     |     55      |       1592       |       199       |       201       |                           [Link](https://github.com/ZhenfengLei/KGDatasets)                            |   
|    [NELL23K](https://drive.google.com/file/d/15ZeGGS3P66OeDmPFnEv85QFs4fnbRBkO/view?usp=share_link)     |    22925    |     200     |      25445       |      4961       |      4952       |                  [Link](https://arxiv.org/pdf/2010.01899.pdf)                                          |  
|    [NELL-995](https://drive.google.com/file/d/1_nHUdjz8OARdX3IPc52qoFnB0TRbjvXQ/view?usp=share_link)    |   75492    |     200     |      126176      |      5000       |      5000       |                              [Link](https://arxiv.org/pdf/1707.06690.pdf)                              |   
|  [OpenBioLink](https://drive.google.com/file/d/1RjIwopVY81k_tZDH4bh1-faehTlcwHYP/view?usp=share_link)   |   184765   |     28      |     4192002      |     188394      |     183011      |                         [Link](https://doi.org/10.1093/bioinformatics/btaa274)                         |
|  [ogbl-biokg](https://proceedings.neurips.cc/paper/2020/file/fb60d411a5c5b72b2e7d3527cfc84fd0-Paper.pdf)   |   93773    |     51      |       4762678    |      162886      |      162780       |                             [Link]()                              | 
|   [ogbl-wikikg2](https://proceedings.neurips.cc/paper/2020/file/fb60d411a5c5b72b2e7d3527cfc84fd0-Paper.pdf)   |   2500604   |     535    |      16109182    |      429456     |     598543      |                             [Link]()                              |
|  [OpenBG500](https://drive.google.com/file/d/1pD_icqV-lLbCXN2rfBaq-Y5i_XcKVCzM/view?usp=sharing)   |   249743    |     500      |       1242550    |      5000      |      5000       |                             [Link](https://arxiv.org/pdf/2209.15214.pdf)                              | 
|   [OpenBG500-L](https://drive.google.com/file/d/1DZZRqc8Yl9mfO66cOS8IKCuim_Bw2oOM/view?usp=sharing)   |   2782223    |     500    |      47410032    |      10000     |     10000      |                             [Link](https://arxiv.org/pdf/2209.15214.pdf)                              |
|     [Sport](https://drive.google.com/file/d/1SgOf4NY8idt6CT0pGKw3kc0DqDvlW4i2/view?usp=share_link)      |    1039    |      4      |       1349       |       358       |       358       |                        [Link](https://www.ijcai.org/proceedings/2020/0413.pdf)                         |
|      [Toy](https://drive.google.com/file/d/1_aX5cAAfWoXqvD1IPDO5_OjIcscv-Hs0/view?usp=share_link)       |    280     |     112     |       4565       |       109       |       152       |                                [Link](https://github.com/uma-pi1/kge/)                                 | 
|      [UMLS](https://drive.google.com/file/d/1OE2h81_7gqUGeY3Eew814G2Huo3xtleG/view?usp=share_link)      |    135     |     46      |       5216       |       652       |       661       |                        [Link](https://www.nlm.nih.gov/research/umls/index.html)                        |  
|  [UMLS-PubMed](https://drive.google.com/file/d/1l2qvFu_x8vvBO11WA6O4HIspImgVKahK/view?usp=share_link)   |   59226    |     443     |     2030841      |      8756       |      8689       |                              [Link](https://arxiv.org/pdf/1909.00230.pdf)                              | 
|   [WD-singer](https://drive.google.com/file/d/1G3_kJXp_iceyTj-a2bM-6ndORAAdHfiK/view?usp=share_link)    |   10282    |     135     |      16142       |      2163       |      2203       |                              [Link](https://arxiv.org/pdf/2010.01899.pdf)                              |
|      [WN11](https://drive.google.com/file/d/1tiKeiOkFfA85jrdwJ7aCdzH-3VzTRIAV/view?usp=share_link)      |   38696    |     11      |      110361      |      5212       |      21035      |     [Link](https://papers.nips.cc/paper/2013/hash/b337e84de8752b27eda3a12363109e80-Abstract.html)      |  
|      [WN18](https://drive.google.com/file/d/10Oh3j2DSFkxgcBiciJGx5bk1WVW-fG4l/view?usp=share_link)      |   40943    |     18      |      141442      |      5000       |      5000       |                                [Link](https://arxiv.org/pdf/1703.06103.pdf)                                 |  
|     [WN18RR](https://drive.google.com/file/d/1ifs9T09CVgkSGd7syDq3EuHpmK9jnot2/view?usp=share_link)     |   40943    |     11      |      86835       |      2924       |      2824       |                           [Link](https://arxiv.org/pdf/1811.04441.pdf)                           | 
|   [wikidata5m](https://drive.google.com/file/d/1f8o8Gi12VQLQ5Tg8umdVYSyOqN9aeB8N/view?usp=share_link)   |  4594485   |     822     |     20614279     |      5163       |      5163       |                     [Link](https://deepgraphlearning.github.io/project/wikidata5m)                     |  
|    [YAGO3-10](https://drive.google.com/file/d/1SbNyBv_U_rCNJCBeIwgd2EiBxJZE4bPi/view?usp=share_link)    |   123182   |     37      |     1079040      |      4978       |      4982       |         [Link](http://service.tsi.telecom-paristech.fr/cgi-bin//valipub_download.cgi?dId=284)          |  
|     [YAGO37](https://drive.google.com/file/d/1Nrz7cg543w7CrdFrpxXwZF5UNw9HMs0t/view?usp=share_link)     |   123189   |     37      |      420623      |      50000      |      50000      |                              [Link](https://arxiv.org/pdf/1711.11231.pdf)                              | 
|   [M-/YAGO39K](https://drive.google.com/file/d/1IOWoa84luYMUEuk0YJOZ3MCtTx6TIWqP/view?usp=share_link)   |   85484    |     39      |      354997      |      9341       |      9364       |                             [Link](https://aclanthology.org/D18-1222.pdf)                              | 

[Back](#bookmarks-)

###  Inductive Datasets  <span id="inductive-datasets-"></span>
<table>
<thead>
  <tr>
    <th colspan="2">Dataset</th>
    <th># Entities<br></th>
    <th># Relations</th>
    <th># Train Triplets<br></th>
    <th># Val. Triplets<br></th>
    <th># Test. Triplets<br></th>
    <th># Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2" align="center"><a href="https://drive.google.com/file/d/17mNlNNYJkL2GejlgtUSeOxWQkuiz7YoJ/view?usp=share_link"> WN18RRv1 </a></td>
    <td align="center">train-graph</td>
    <td align="center">2746</td>
    <td align="center">9</td>
    <td align="center">5410</td>
   <td align="center">626</td>
    <td align="center">638</td>
    <td align="center" rowspan="24"> <a href="http://proceedings.mlr.press/v119/teru20a/teru20a-supp.pdf"> Link </a></td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">922</td>
    <td align="center">9</td>
    <td align="center">1618</td>
    <td align="center">181</td>
    <td align="center">184</td>
  </tr>
  <tr>
    <td rowspan="2" align="center"><a href="https://drive.google.com/file/d/1J7CaqaLx3ZEyUA9j9eyvdZoWaws9hzGq/view?usp=share_link"> WN18RRv2 </a></td>
    <td align="center">train-graph</td>
    <td align="center">6954</td>
    <td align="center">10</td>
    <td align="center">15262</td>
    <td align="center">1837</td>
    <td align="center">1868</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">2923</td>
    <td align="center">10</td>
    <td align="center">4011</td>
    <td align="center">407</td>
    <td align="center">437</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/1a2auqD9VJ9_J2EshcZsR6_pjsXXa30HS/view?usp=share_link"> WN18RRv3 </a></td>
    <td align="center">train-graph</td>
    <td align="center">12078</td>
    <td align="center">11</td>
    <td align="center">25901</td>
    <td align="center">3097</td>
    <td align="center">3152</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">5084</td>
    <td align="center">11</td>
    <td align="center">6327</td>
    <td align="center">534</td>
    <td align="center">601</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/11rjf3vpwIKi5AQkSSXNeBF8yGShrOPa5/view?usp=share_link"> WN18RRv4 </a></td>
    <td align="center">train-graph</td>
    <td align="center">3861</td>
    <td align="center">9</td>
    <td align="center">7940</td>
   <td align="center">934</td>
    <td align="center">968</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">7208</td>
    <td align="center">9</td>
    <td align="center">12334</td>
    <td align="center">1394</td>
    <td align="center">1429</td>
  </tr>
  <tr>
    <td align="center"  rowspan="2"><a href="https://drive.google.com/file/d/1vjul-zXFavPLBku9lLbhajMwm_t0de83/view?usp=share_link"> FB15k237v1 </a></td>
     <td align="center">train-graph</td>
     <td align="center">2000</td>
     <td align="center">183</td>
     <td align="center">4245</td>
     <td align="center">485</td>
     <td align="center">492</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">1500</td>
    <td align="center">146</td>
    <td align="center">1993</td>
    <td align="center">202</td>
    <td align="center">201</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/15st6MwSe4wgH0pZArXaP_mO5Hj4mmRNs/view?usp=share_link"> FB15k237v2 </a></td>
    <td align="center">train-graph</td>
    <td align="center">3000</td>
    <td align="center">203</td>
    <td align="center">9739</td>
    <td align="center">1166</td>
    <td align="center">1180</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">2000</td>
    <td align="center">176</td>
    <td align="center">4145</td>
    <td align="center">469</td>
    <td align="center">478</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/1N-D8lrj6mmhYtzoh2N4VFRi_vX0Ub7BU/view?usp=share_link"> FB15k237v3 </a></td>
    <td align="center">train-graph</td>
    <td align="center">4000</td>
    <td align="center">218</td>
    <td align="center">17986</td>
    <td align="center">2194</td>
    <td align="center">2214</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
   <td align="center">3000</td>
    <td align="center">187</td>
   <td align="center">7406</td>
    <td align="center">866</td>
    <td align="center">865</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/1EXROw3QUncukmYSI-fjpCctuWpxye4s0/view?usp=share_link"> FB15k237v4 </a></td>
    <td align="center">train-graph</td>
    <td align="center">5000</td>
    <td align="center">222</td>
    <td align="center">27203</td>
   <td align="center">3352</td>
    <td align="center">3361</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">3500</td>
   <td align="center">204</td>
    <td align="center">11714</td>
    <td align="center">1416</td>
   <td align="center">1424</td>
  </tr>
  <tr>
<td align="center" rowspan="2"><a href="https://drive.google.com/file/d/16JjvM1FYPo3tmDTpqaZ1fSs0qdoR3ywN/view?usp=share_link"> NELL995v1 </a></td>
    <td align="center">train-graph</td>
    <td align="center">10915</td>
    <td align="center">14</td>
    <td align="center">4687</td>
    <td align="center">414</td>
    <td align="center">435</td>
  </tr>
  <tr>
     <td align="center">ind-test-graph</td>
     <td align="center">225</td>
     <td align="center">14</td>
     <td align="center">833</td>
     <td align="center">97</td>
     <td align="center">96</td>
  </tr>
  <tr>
<td align="center" rowspan="2"><a href="https://drive.google.com/file/d/1ddWh3l2Bx4ppb-BysBiFtg2MGnbFZJ16/view?usp=share_link"> NELL995v2 </a></td>
     <td align="center">train-graph</td>
     <td align="center">2564</td>
     <td align="center">88</td>
     <td align="center">8219</td>
     <td align="center">922</td>
     <td align="center">968</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">4937</td>
    <td align="center">79</td>
    <td align="center">4586</td>
    <td align="center">455</td>
    <td align="center">476</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/1KGoi1VB5W5vNlIvU0Kmbcr9ha9i7-_9D/view?usp=share_link"> NELL995v3 </a></td>
    <td align="center">train-graph</td>
    <td align="center">4647</td>
   <td align="center">142</td>
    <td align="center">16393</td>
    <td align="center">1851</td>
    <td align="center">1873</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph</td>
    <td align="center">4921</td>
   <td align="center">122</td>
    <td align="center">8048</td>
    <td align="center">811</td>
    <td align="center">809</td>
  </tr>
  <tr>
    <td align="center" rowspan="2"><a href="https://drive.google.com/file/d/12cPRA1ICVn0Cd3VgjNg1aQODkOM_TZrT/view?usp=share_link"> NELL995v4 </a></td>
    <td align="center" >train-graph</td>
    <td align="center" >2092</td>
    <td align="center" >77</td>
    <td align="center" >7546</td>
    <td align="center" >876</td>
    <td align="center" >867</td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph</td>
    <td align="center" >3294</td>
    <td align="center" >61</td>
    <td align="center" >7073</td>
    <td align="center" >716</td>
    <td align="center" >731</td>
  </tr>
  <tr>
     <td align="center" rowspan="6"><a href="https://drive.google.com/file/d/1W6Y5JIsk72x8Qsw7RGNH2V1pxeHhrwRJ/view?usp=share_link"> WN-MBE </a></td>
    <td align="center" >train-graph</td>
    <td align="center" >19361</td>
    <td align="center" >11</td>
    <td align="center" >35426</td>
    <td align="center" >8858</td>
    <td align="center" >-</td>
    <td align="center"  rowspan="24"><br><br><a href="https://arxiv.org/pdf/2208.10378.pdf"> Link </a></td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph-1</td>
    <td align="center" >3723</td>
    <td align="center" >11</td>
    <td align="center" >5678</td>
    <td align="center" >-</td>
    <td align="center" >1352</td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph-2</td>
    <td align="center" >4122</td>
    <td align="center" >11</td>
    <td align="center" >6730</td>
    <td align="center" >-</td>
    <td align="center" >1874</td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph-3</td>
    <td align="center" >4300</td>
    <td align="center" >11</td>
    <td align="center" >7545</td>
    <td align="center" >-</td>
    <td align="center" >2054</td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph-4</td>
    <td align="center" >4467</td>
    <td align="center" >11</td>
    <td align="center" >8623</td>
    <td align="center" >-</td>
    <td align="center" >2493</td>
  </tr>
  <tr>
    <td align="center" >ind-test-graph-5</td>
    <td align="center" >4514</td>
    <td align="center" >11</td>
    <td align="center" >9608</td>
    <td align="center" >-</td>
    <td align="center" >2762</td>
  </tr>
  <tr>
    <td align="center"  rowspan="6"><a href="https://drive.google.com/file/d/1D36P45Cu3TxpilkMf0vOVAXA7dVC6YLv/view?usp=share_link"> FB-MBE </a></td>
    <td align="center">train-graph</td>
     <td align="center">7203</td>
     <td align="center">237</td>
     <td align="center">125769</td>
     <td align="center">31442</td>
     <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-1</td>
    <td align="center">1458</td>
    <td align="center">237</td>
   <td align="center">18394</td>
    <td align="center">-</td>
    <td align="center">9240</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-2</td>
    <td align="center">1461</td>
    <td align="center">237</td>
    <td align="center">19120</td>
    <td align="center">-</td>
   <td align="center">9669</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-3</td>
    <td align="center">1467</td>
    <td align="center">237</td>
   <td align="center">19740</td>
   <td align="center">-</td>
    <td align="center">9887</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-4</td>
    <td align="center">1467</td>
    <td align="center">237</td>
    <td align="center">22455</td>
    <td align="center">-</td>
    <td align="center">11127</td>
  </tr>
  <tr>
   <td align="center">ind-test-graph-5</td>
    <td align="center">1471</td>
    <td align="center">237</td>
    <td align="center">22214</td>
    <td align="center">-</td>
    <td align="center">11059</td>
  </tr>
  <tr>
    <td align="center" rowspan="6"><a href="https://drive.google.com/file/d/1Z15dbTO6SnOHZIjHq0jo8zJ6USx2B9P3/view?usp=share_link"> NELL-MBE </a></td>
    <td align="center">train-graph</td>
    <td align="center">33348</td>
    <td align="center">200</td>
    <td align="center">88814</td>
    <td align="center">22203</td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-1</td>
    <td align="center">34488</td>
    <td align="center">3200</td>
    <td align="center">34496</td>
    <td align="center">-</td>
    <td align="center">3853</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-2</td>
    <td align="center">36031</td>
    <td align="center">3200</td>
    <td align="center">35411</td>
    <td align="center">-</td>
    <td align="center">31059</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-3</td>
    <td align="center">37660</td>
    <td align="center">3200</td>
    <td align="center">36543</td>
    <td align="center">-</td>
    <td align="center">31277</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-4</td>
    <td align="center">39056</td>
    <td align="center">3200</td>
    <td align="center">37667</td>
    <td align="center">-</td>
    <td align="center">31427</td>
  </tr>
  <tr>
    <td align="center">ind-test-graph-5</td>
    <td align="center">310616</td>
    <td align="center">3200</td>
    <td align="center">38876</td>
    <td align="center">-</td>
    <td align="center">31595</td>
  </tr>
</tbody>
</table>

[Back](#bookmarks-)

##  Temporal KGR Datasets <span id="temporal-knowledge-graphs-"></span>
|                                                  Dataset                                                  | # Entities | # Relations | # Timestamps | # Train Triplets | # Val. Triplets | # Test Triplets |                             # Description                             |  
|:---------------------------------------------------------------------------------------------------------:|:----------:|:-----------:|:------------:|:----------------:|:---------------:|:---------------:|:---------------------------------------------------------------------:|
|   [DBpedia-3SP](https://drive.google.com/file/d/1yikfCUs1ALRa8g4fa06oi1lHJxPeNwoA/view?usp=share_link)    |   66967    |     968     |      3       |      103211      |      3000       |        -        |             [Link](https://arxiv.org/pdf/1910.06708.pdf)              |
|      [GDELT](https://drive.google.com/file/d/1yikfCUs1ALRa8g4fa06oi1lHJxPeNwoA/view?usp=share_link)       |    7691    |     240     |     8925     |     1033270      |     238765      |     305241      |      [Link](https://dl.acm.org/doi/pdf/10.1145/3511808.3557233)       |   
|   [GDELT-small](https://drive.google.com/file/d/1gINiR7pkEZE-pR_6PLLlSisf6_iibXkw/view?usp=share_link)    |    500     |     20      |     366     |     2735685      |     341961      |     341961      | [Link](https://github.com/JiapengWu/Time-Aware-Incremental-Embedding) | 
|    [GDELT-m10](https://drive.google.com/file/d/1xSZ5CSxWYpNWENzKYCwCkCCNxlss1_Sf/view?usp=share_link)     |     50     |     20      |      30      |      221132      |      27608      |      27926      |       [Link](https://aclanthology.org/2021.emnlp-main.639.pdf)        | 
|      [IMDB-13-3SP](https://drive.google.com/file/d/1bjDpNayHLgk0QEPaes_IHNhW-7qVh4Sr/view?usp=share_link) |  3244455   |     14      |      3       |     7913773      |      10000      |        -        |             [Link](https://arxiv.org/pdf/1910.06708.pdf)              | 
|    [IMDB-30SP](https://drive.google.com/file/d/10d2EVP-DyhMUI9zol4-X1RMlzSEE5vgY/view?usp=share_link)     |   243148   |     14      |      30      |      621096      |      3000       |      3000       |             [Link](https://arxiv.org/pdf/1910.06708.pdf)              | 
|    [ICSES05-15](https://drive.google.com/file/d/1weZpSpxI94AI9pPkAzeR7hN5lWKVw_BL/view?usp=share_link)    |   10488    |     251     |     4017     |      386962      |      46092      |      46275      |      [Link](https://iclr.cc/virtual/2021/poster/3378)                 |  
|    [ICEWS11-14](https://drive.google.com/file/d/1_PIzO1IvJFZqHRDniHzvCbIA5K0B_1aa/view?usp=share_link)    |    6738    |     235     |     1461     |      118766      |      14859      |      14756      |       [Link](https://aclanthology.org/2021.emnlp-main.639.pdf)        | 
|     [ICSES14](https://drive.google.com/file/d/1v6SDvtR8ybqlyiH9OTlK0s3mdDOq-rTO/view?usp=share_link)      |    7128    |     230     |     365      |      63685       |      13823      |      13222      |           [Link](https://iclr.cc/virtual/2021/poster/3378)            |  
|   [ICEWS14-Plus](https://drive.google.com/file/d/1769lI90wR9rNVC663Sy2wpDAB9W78WR_/view?usp=share_link)   |    7128    |     230     |     365      |      72826       |      8941       |      8963       |       [Link](https://aclanthology.org/2021.emnlp-main.639.pdf)        | 
|     [ICEWS18](https://drive.google.com/file/d/1u0iJKOGzHvqLGJVT23MxcPlztxdvvTWh/view?usp=share_link)      |   23033    |     256     |     7272     |      373018      |      45995      |      49545      |           [Link](https://iclr.cc/virtual/2021/poster/3378)            |  
|   [YAGO11k/YOGA](https://drive.google.com/file/d/1FpXZXOo9j4uVz-hH-RpFimjz85_oC2Dm/view?usp=share_link)   |   10623    |     10      |     189      |      161540      |      19523      |      20026      |        [Link](https://aclanthology.org/D18-1225.pdf)         |   
|     [YAGO-3SP](https://drive.google.com/file/d/1R9ntsxbEzplqHp4Gd14l1nwLQ7LaxQEI/view?usp=share_link)     |   27009    |     37      |      3       |      124757      |        3000     |      3000       |             [Link](https://arxiv.org/pdf/1910.06708.pdf)              |   
|     [YAGO15k](https://drive.google.com/file/d/1tDl-Mx089oWqLFicLREe677SzaDwLASn/view?usp=share_link)      |   15403    |     34      |     198      |      110441      |      13815      |      13800      |             [Link](https://aclanthology.org/D18-1516.pdf)             |  
|     [YAGO1830](https://drive.google.com/file/d/1fo5j8cLzrwQRs4IDX2qZPm4vtsbnXWrx/view?usp=share_link)     |   10038    |     10      |     205      |      51205       |      10973      |      10973      |           [Link](https://iclr.cc/virtual/2021/poster/3378)            |  
| [WIKI/Wikidata12k](https://drive.google.com/file/d/1T-uYa24G4qyaE_dC-Hh6gzCEWo1EuxNo/view?usp=share_link) |   12554    |     24      |     232      |     2735685      |     341961      |     341961      |        [Link](https://aclanthology.org/D18-1225.pdf)         |   
|   [Wikidata11k](https://drive.google.com/file/d/1mEHg0xYnEoQ-5_BhbhbWxsdM6GZs9BF3/view?usp=share_link)    |   11134    |     95      |     328      |      242844      |      28748      |      14283      |             [Link](https://arxiv.org/pdf/2012.10595.pdf)              |
|   [Wikidata-big](https://drive.google.com/file/d/1Wk7ztpQx9syUrZ6eb2yNjrVdvLR_hhBr/view?usp=share_link)   |   125726   |     203     |     1700     |      323635      |      5000       |      5000       |             [Link](https://arxiv.org/pdf/2112.05785.pdf)              | 

[Back](#bookmarks-)


##  Multi-Modal KGR Datasets <span id="multi-modal-knowledge-graphs-"></span>
<table>
<thead>
  <tr>
    <th colspan="2">Dataset</th>
    <th># Modality </th>
    <th># Entities</th>
    <th># Relations</th>
    <th># Train Triplets</th>
    <th>#&nbsp;Val. Triplets</th>
    <th>#&nbsp;Test. Triplets</th>
    <th>#&nbsp;Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="center" colspan="2" rowspan="3"><a href="https://drive.google.com/file/d/1Gv15F4si9ngJAiNEgw0x3oYgPlt2WfBh/view?usp=share_link">FB-IMG-TXT</a></td>
    <td align="center" >KG</td>
    <td align="center" >11757</td>
    <td align="center" rowspan="3">1231</td>
    <td align="center" rowspan="3">285850</td>
    <td align="center" rowspan="3">34863</td>
    <td align="center" rowspan="3">29580</td>
    <td align="center" rowspan="3"><a href="https://aclanthology.org/S18-2027.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >11757</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >1175700</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="2"><a href="https://drive.google.com/file/d/1ez-uaC-QtkT5LGfZJHVEE0OMWXMXABon/view?usp=sharing">FB15k-237-IMG</a></td>
    <td align="center" >KG</td>
    <td align="center" >14541</td>
    <td align="center" rowspan="2">237</td>
    <td align="center" rowspan="2">272115</td>
    <td align="center" rowspan="2">17535</td>
    <td align="center" rowspan="2">20466</td>
    <td align="center" rowspan="2"><a href="https://arxiv.org/pdf/2205.02357.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >145410</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="2"><a href="https://imgpedia.dcc.uchile.cl/">IMGpedia</a></td>
    <td align="center" >KG</td>
    <td align="center" >14765300</td>
    <td align="center" rowspan="2">442959000</td>
    <td align="center" rowspan="2">3119207705</td>
    <td align="center" rowspan="2">-</td>
    <td align="center" rowspan="2">-</td>
    <td align="center" rowspan="2"><a href="http://sferrada.com/pdf/imgpediaISWC17.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >44295900</td>
  </tr>
  <tr>
    <td align="center" rowspan="9"><a href="https://drive.google.com/file/d/1AA7BIpP3VJm2fsbKa4fOxGTtZXjOERm8/view?usp=share_link">MMKG</a></td>
    <td align="center" rowspan="3">MMKG-FB15k</td>
    <td align="center" >KG</td>
    <td align="center" >14951</td>
    <td align="center" rowspan="3">1345</td>
    <td align="center" >592213</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
    <td align="center" rowspan="9"><a href="https://arxiv.org/pdf/1903.05485.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >Numeric Literal</td>
    <td align="center" >29395</td>
    <td align="center" >29395</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >13444</td>
    <td align="center" >13444</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" rowspan="3">MMKG-DB15k</td>
    <td align="center" >KG</td>
    <td align="center" >14777</td>
    <td align="center" rowspan="3">279</td>
    <td align="center" >99028</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" >Numeric Literal</td>
    <td align="center" >46121</td>
    <td align="center" >46121</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >12841</td>
    <td align="center" >12841</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" rowspan="3">MMKG-Yago15k</td>
    <td align="center" >KG</td>
    <td align="center" >15283</td>
    <td align="center" rowspan="3">32</td>
    <td align="center" >122886</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" >Numeric Literal</td>
    <td align="center" >48405</td>
    <td align="center" >48405</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >11194</td>
    <td align="center" >11194</td>
    <td align="center" >-</td>
    <td align="center" >-</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="3">MKG-Wikipedia</td>
    <td align="center" >KG</td>
    <td align="center" >15000</td>
    <td align="center" rowspan="3">169</td>
    <td align="center" rowspan="3">34196</td>
    <td align="center" rowspan="3">4274</td>
    <td align="center" rowspan="3">4276</td>
    <td align="center" rowspan="6"><a href="https://dl.acm.org/doi/abs/10.1145/3503161.3548388">Link</a></td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >14123</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >14463</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="3">MKG-YAGO</td>
    <td align="center" >KG</td>
    <td align="center" >15000</td>
    <td align="center" rowspan="3">28</td>
    <td align="center" rowspan="3">21310</td>
    <td align="center" rowspan="3">2663</td>
    <td align="center" rowspan="3">2665</td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >12305</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >14244</td>
  </tr>
 <tr>
    <td align="center" colspan="2" rowspan="3"><a href="https://drive.google.com/file/d/1jg4YcFgOfgjUJCnxBjw9w-6ID8VS_L-X/view?usp=sharing
">OpenBG-IMG</a></td>
    <td align="center" >KG</td>
    <td align="center" >27910</td>
    <td align="center" rowspan="3">136</td>
    <td align="center" rowspan="3">230087</td>
    <td align="center" rowspan="3">5000</td>
    <td align="center" rowspan="3">14675</td>
    <td align="center" rowspan="3"><a href="https://arxiv.org/pdf/2209.15214.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >27910</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >14718</td>
  </tr>
  <tr>
  <tr>
    <td align="center" colspan="2" rowspan="2"><a href="https://github.com/wangmengsd/richpedia">RichPedia</a></td>
    <td align="center" >KG</td>
    <td align="center" >29985</td>
    <td align="center" rowspan="2">3</td>
    <td align="center" rowspan="2">119669570</td>
    <td align="center" rowspan="2">-</td>
    <td align="center" rowspan="2">-</td>
    <td align="center" rowspan="2"><a href="https://link.springer.com/chapter/10.1007/978-3-030-41407-8_9">Link</a></td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >2914770</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="3"><a href="https://drive.google.com/file/d/1NF7i5GWdbii5sD7o_-fWK0KkGQcanmHd/view?usp=share_link">WN9-IMG-TXT</a></td>
    <td align="center" >KG</td>
    <td align="center" >6555</td>
    <td align="center" rowspan="3">9</td>
    <td align="center" rowspan="3">11741</td>
    <td align="center" rowspan="3">1319</td>
    <td align="center" rowspan="3">1337</td>
    <td align="center" rowspan="3"><a href="https://arxiv.org/pdf/1609.07028.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >6555</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >63225</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="2"><a href="https://drive.google.com/file/d/1ez-uaC-QtkT5LGfZJHVEE0OMWXMXABon/view?usp=sharing">WN18-IMG</a></td>
    <td align="center" >KG</td>
    <td align="center" >40943</td>
    <td align="center" rowspan="2">18</td>
    <td align="center" rowspan="2">141442</td>
    <td align="center" rowspan="2">5000</td>
    <td align="center" rowspan="2">5000</td>
    <td align="center" rowspan="2"><a href="https://arxiv.org/pdf/2205.02357.pdf">Link</a></td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >145410</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="4"><a href="https://github.com/pouyapez/mkbe/tree/master/datasets/Movielens-100k%20plus">MovieLens-100k plus</a></td>
    <td align="center" >KG</td>
    <td align="center" >2625</td>
    <td align="center" rowspan="4">13</td>
    <td align="center" rowspan="4">100000</td>
    <td align="center" rowspan="4">-</td>
    <td align="center" rowspan="4">-</td>
    <td align="center" rowspan="8"><a href="https://arxiv.org/pdf/1809.01341">Link</a></td>
  </tr>
  <tr>
    <td align="center" >Numerical</td>
    <td align="center" >2625</td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >1682</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >1651</td>
  </tr>
  <tr>
    <td align="center" colspan="2" rowspan="4"><a href="https://github.com/pouyapez/mkbe/tree/master/datasets/YAGO-10%20plus">Yago-10 plus</a></td>
    <td align="center" >KG</td>
    <td align="center" >123182</td>
    <td align="center" rowspan="4">45</td>
    <td align="center" rowspan="4">1079040</td>
    <td align="center" rowspan="4">-</td>
    <td align="center" rowspan="4">-</td>
    
  </tr>
  <tr>
    <td align="center" >Numerical</td>
    <td align="center" >111406</td>
  </tr>
  <tr>
    <td align="center" >TXT</td>
    <td align="center" >107326</td>
  </tr>
  <tr>
    <td align="center" >IMG</td>
    <td align="center" >61246</td>
  </tr>
</tbody>
</table>

[Back](#bookmarks-)

## Static Knowledge Graph Reasoning <span id="static-knowledge-graph-reasoning-"></span> 
### Translational Models <span id="translational-models-"></span> 
| **Year** |    **Model**   |                                                          **Title**                                                          | **Venue** | **Scenario** |                                               **Paper**                                               |                                                             **Code**                                                             |
|:--------:|:--------------:|:---------------------------------------------------------------------------------------------------------------------------:|:---------:|:------------:|:-----------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------:|
| 2024     | **GoldE**     |                  **Generalizing Knowledge Graph Embedding with Universal Orthogonal Parameterization**                   |   ICML    | Transductive |                      [Link](https://openreview.net/pdf?id=Sv4u9PtvT5)                    |                         [Link](https://github.com/rui9812/GoldE)   |    
| 2023     | **CompoundE3D**     |                  **Knowledge Graph Embedding with 3D Compound Geometric Transformations**                   |   arXiv    | Transductive |                      [Link](https://arxiv.org/pdf/2304.00378.pdf)                      |                          -    |    
| 2023     | **EXPRESSIVE**     |                  **EXPRESSIVE: A SPATIO-FUNCTIONAL EMBEDDING FOR KNOWLEDGE GRAPH COMPLETION**                   |   ICLR    | Transductive |                      [Link](https://openreview.net/pdf?id=xkev3_np08z)                      |                                                                [Link](https://github.com/AleksVap/ExpressivE)                                                                |                                            
| 2022     | **DualDE**     |                  **DualDE: Dually Distilling Knowledge Graph Embedding for Faster and Cheaper Reasoning**                   |   WSDM    | Transductive |                      [Link](https://dl.acm.org/doi/abs/10.1145/3488560.3498437)                       |                                                                -                                                                 |
| 2022     | **TripleRE**   |                            **TripleRE: Knowledge Graph Embeddings via Tripled Relation Vectors**                            |   arXiv   | Transductive |                             [Link](https://arxiv.org/pdf/2209.08271.pdf)                              |                                                                -                                                                 |
| 2022     | **InterHT**    |                    **InterHT: Knowledge Graph Embeddings by Interaction between Head and Tail Entities**                    |   arXiv   | Transductive |                             [Link](https://arxiv.org/pdf/2202.04897.pdf)                              |                                                                -                                                                 |
| 2022     | **HousE**      |                           **HousE: Knowledge Graph Embedding with Householder Parameterization**                            |   ICML    | Transductive |                             [Link](https://arxiv.org/pdf/2202.07919.pdf)                              |                                              [Link](https://github.com/anrep/HousE)                                              |
| 2022     | **ReflectE**  |                                 **Knowledge graph embedding by reflection transformation**                                  |    KBS    | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0950705121010418?via%3Dihub)       |                                                                -                                                                 |
| 2022     | **DensE**      |    **DensE: An enhanced non-commutative representation for knowledge graph embedding with adaptive semantic hierarchy**     |    NC     | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0925231221019342?via%3Dihub)       |                                                                -                                                                 |
| 2022     | **StructurE**  |                         **Structural context-based knowledge graph embedding for link prediction**                          |    NC     | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0925231221016192?via%3Dihub)       |                                                                -                                                                 |
| 2021     | **HA-RotatE**  |                  **Hierarchical-aware relation rotational knowledge graph embedding for link prediction**                   |    NC     | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0925231221008560?via%3Dihub)       |                                                                -                                                                 |
| 2021     | **PairRE**     |                             **PairRE: Knowledge Graph Embeddings via Paired Relation Vectors**                              |    ACL    | Transductive |                          [link](https://aclanthology.org/2021.acl-long.336/)                          |                    [link](https://github.com/alipay/KnowledgeGraphEmbeddingsViaPairedRelationVectors_PairRE)                     |
| 2021     | **CyclE**     |                       **Cycle or Minkowski: Which is More Appropriate for Knowledge Graph Embedding**                       |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3459637.3482245)                         |                                                                -                                                                 |
| 2021     | **MöbiusE**    |                                    **MöbiusE: Knowledge Graph Embedding on Möbius Ring**                                    |    KBS    | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0950705121004445?via%3Dihub)       |                    [link](https://www.sciencedirect.com/science/article/abs/pii/S0950705121004445?via%3Dihub)                    |
| 2021     | **5*E**        |                              **5* Knowledge Graph Embeddings with Projective Transformations**                              |   AAAI    | Transductive |                    [link](https://ojs.aaai.org/index.php/AAAI/article/view/17095)                     |                                                                -                                                                 |
| 2021     | **BiQUE**      |                                  **BiQUE: Biquaternionic Embeddings of Knowledge Graphs**                                   |   EMNLP   | Transductive |                         [link](https://aclanthology.org/2021.emnlp-main.657/)                         |                                            [link](https://github.com/guojiapub/BiQUE)                                            |
| 2021     | **HBE**        |                        **Hyperbolic Hierarchy-Aware Knowledge Graph Embedding for Link Prediction**                         |   EMNLP   | Transductive |                       [link](https://aclanthology.org/2021.findings-emnlp.251/)                       |                                                                -                                                                 |
| 2021     | **RotL**       | **Hyperbolic Geometry is Not Necessary: Lightweight Euclidean-Based Models for Low-Dimensional Knowledge Graph Embeddings** |   EMNLP   | Transductive |                       [link](https://aclanthology.org/2021.findings-emnlp.42/)                        |                                                                -                                                                 |
| 2021     | **GrpKG**      |              **Knowledge Graph Representation Learning as Groupoid: Unifying TransE, RotatE, QuatE, ComplEx**               |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3459637.3482442)                         |                                                                -                                                                 |
| 2021     | **MQuadE**     |                                  **MQuadE: a Unified Model for Knowledge Fact Embedding**                                   |    WWW    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3442381.3449879)                         |                                                                -                                                                 |
| 2020     | **ConnectE**   |                            **Knowledge graph entity typing via learning connecting embeddings**                             |    KBS    | Transductive |      [link](https://www.sciencedirect.com/science/article/abs/pii/S0950705120301921?via%3Dihub)       |                                                                -                                                                 |
| 2020     | **MAKR**       |                            **An asymmetric knowledge representation learning in manifold space**                            |    IS     | Transductive |                           [link](https://doi.org/10.1016/j.ins.2020.04.036)                           |                                                                -                                                                 |
| 2020     | **HAKE**      |                         **Learning Hierarchy-Aware Knowledge Graph Embeddings for Link Prediction**                         |   AAAI    | Transductive |                     [link](https://aaai.org/ojs/index.php/AAAI/article/view/5701)                     |                                         [link](https://github.com/MIRALab-USTC/KGE-HAKE)                                         |
| 2020     | **BoxE**      |                                **BoxE: A Box Embedding Model for Knowledge Base Completion**                                |  NeurIPS  | Transductive | [link](https://proceedings.NeurIPS.cc/paper/2020/hash/6dbbe6abe5f14af882ff977fc3f35501-Abstract.html) |                                                                -                                                                 |
| 2020     | **OTE**        |                **Orthogonal Relation Transforms with Graph Context Modeling for Knowledge Graph Embedding**                 |    ACL    | Transductive |                      [link](https://www.aclweb.org/anthology/2020.acl-main.241/)                      |                             [link](https://github.com/JD-AI-Research-Silicon-Valley/KGEmbedding-OTE)                             |
| 2020     | **TransRHS**   |          **TransRHS: A Representation Learning Method for Knowledge Graphs with Relation Hierarchical Structure**           |   IJCAI   | Transductive |                            [link](https://doi.org/10.24963/ijcai.2020/413)                            |                                          [link](https://github.com/tjuzhangfx/TransRHS)                                          |
| 2020     | **MDE**        |                        **MDE: Multiple Distance Embeddings for Link Prediction in Knowledge Graphs**                        |   ECAI    | Transductive |                          [link](http://ebooks.iospress.nl/publication/55043)                          |                                             [link](https://github.com/mlwin-de/MDE)                                              |
| 2020     | **AprilE**     |                     **AprilE: Attention with Pseudo Residual Connection for Knowledge Graph Embedding**                     |  COLING   | Transductive |                     [link](https://www.aclweb.org/anthology/2020.coling-main.44/)                     |                                                                -                                                                 |
| 2020     | **RatE**       |                      **RatE: Relation-Adaptive Translating Embedding for Knowledge Graph Completion**                       |  COLING   | Transductive |                     [link](https://www.aclweb.org/anthology/2020.coling-main.48/)                     |                                                                -                                                                 |
| 2020     | **Rotate3D**   |         **Rotate3D: Representing Relations as Rotations in Three-Dimensional Space for Knowledge Graph Embedding**          |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3340531.3411889)                         | [link](https://github.com/gao-xiao-bai/Rotate3D-Representing-Relations-as-Rotations-in-Three-Dimensional-Space-for-KG-Embedding) |
| 2020     | **LineaRE**    |                       **LineaRE: Simple but Powerful Knowledge Graph Embedding for Link Prediction**                        |   ICDM    | Transductive |                         [link](https://ieeexplore.ieee.org/document/9338434)                          |                                          [Link](https://github.com/pengyanhui/LineaRE)                                           |
| 2020     | **GeomE**      |                                    **Knowledge Graph Embeddings in Geometric Algebras**                                     |  COLING   | Transductive |                     [link](https://www.aclweb.org/anthology/2020.coling-main.46/)                     |                                                                -                                                                 |
| 2020     | **SpacEss**    |                      **Fantastic Knowledge Graph Embeddings and How to Find the Right Space for Them**                      |   ISWC    | Transductive |               [link](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_25)                |                                                                -                                                                 |
| 2020     | **HyperKG**    |                           **Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion**                           |   ESWC    | Transductive |                         [link](https://doi.org/10.1007/978-3-030-49461-2_12)                          |                                         [link](https://github.com/prokolyvakis/hyperkg)                                          |
| 2019     | **RotatE**     |                        **RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space**                        |   ICLR    | Transductive |                          [link](https://openreview.net/forum?id=HkgEQnRqYQ)                           |                               [link](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding)                               |
| 2019     | **TransGate**  |                             **TransGate: Knowledge Graph Embedding with Shared Gate Structure**                             |   AAAI    | Transductive |                     [link](https://aaai.org/ojs/index.php/AAAI/article/view/4169)                     |                                                                -                                                                 |
| 2019     | **TransMS**    |                 **TransMS: Knowledge Graph Embedding for Complex Relations by Multidirectional Semantics**                  |   IJCAI   | Transductive |                          [link](https://www.ijcai.org/proceedings/2019/268)                           |                                                                -                                                                 |
| 2019     | **TransW**     |                                **Composing Knowledge Graph Embeddings via Word Embeddings**                                 |   arXiv   | Inductive |                             [link](https://arxiv.org/pdf/1909.03794.pdf)                              |                                                                -                                                                 |
| 2019     | **MuRP**       |                                       **Multi-relational Poincaré Graph Embeddings**                                        |  NeurIPS  | Transductive |          [link](http://papers.nips.cc/paper/8696-multi-relational-poincare-graph-embeddings)          |                                  [link](https://github.com/ibalazevic/multirelational-poincare)                                  |
| 2018     | **TransAt**   |          **Translating Embeddings for Knowledge Graph Completion with Relation Attention Mechanism**                        |   IJCAI   | Transductive |                          [link](https://www.ijcai.org/proceedings/2018/596)                           |                                          [link](https://github.com/ZJULearning/TransAt)                                          |
| 2018     | **TorusE**     |                                    **TorusE: Knowledge Graph Embedding on a Lie Group**                                     |   AAAI    | Transductive |                      [Link](https://arxiv.org/pdf/1711.05435.pdf)                                     |                                            [link](https://github.com/TakumaE/TorusE)                                             |
| 2018     | **TransC**    |                          **Differentiating Concepts and Instances for Knowledge Graph Embedding**                           |   EMNLP   | Transductive |                          [link](https://www.aclweb.org/anthology/D18-1222/)                           |                                           [link](https://github.com/davidlvxin/TransC)                                           |
| 2017     | **puTransE**   |            **Non-Parametric Estimation of Multiple Embeddings for Link Prediction on Dynamic Knowledge Graphs**             |   AAAI    | Transductive |                  [link](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14524)                  |                                                                -                                                                 |
| 2017     | **ITransF**    |                         **An Interpretable Knowledge Transfer Model for Knowledge Base Completion**                         |    ACL    | Transductive |                          [link](https://www.aclweb.org/anthology/P17-1088/)                           |                                                                -                                                                 |
| 2017     | **CombinE**    |                 **Representation Learning of Large-Scale Knowledge Graphs via Entity Feature Combinations**                 |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3132847.3132961)                         |                                                                -                                                                 |
| 2017     | **Trans-RS**   |                           **Learning Knowledge Embeddings by Combining Limit-based Scoring Loss**                           |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/3132847.3132939)                         |                                                                -                                                                 |
| 2016     | **TransA**    |                               **Locally Adaptive Translation for Knowledge Graph Embedding**                                |   AAAI    | Transductive |             [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12018/11694)             |                                                                -                                                                 |
| 2016     | **TranSparse** |                             **Knowledge Graph Completion with Adaptive Sparse Transfer Matrix**                             |   AAAI    | Transductive |             [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/11982/11693)             |                                                                -                                                                 |
| 2016     | **TransG**     |                                **TransG: A Generative Model for Knowledge Graph Embedding**                                 |    ACL    | Transductive |                          [link](https://www.aclweb.org/anthology/P16-1219/)                           |                                         [link](https://github.com/BookmanHan/Embedding)                                          |
| 2016     | **ManifoldE**  |                   **From One Point to a Manifold: Knowledge Graph Embedding for Precise Link Prediction**                   |   IJCAI   | Transductive |                             [link](http://www.ijcai.org/Abstract/16/190)                              |                                         [link](https://github.com/BookmanHan/Embedding)                                          |
| 2016     | **FT**         |                                    **Knowledge Graph Embedding by Flexible Translation**                                    |    KR     | Transductive |                  [link](https://www.aaai.org/ocs/index.php/KR/KR16/paper/view/12887)                  |                                                [link](http://ml.knu.ac.kr/lppKE)                                                 |
| 2016     | **lppTrans**   |                 **A Translation-Based Knowledge Graph Embedding Preserving Logical Property of Relations**                  | NAACL-HLT | Transductive |                           [link](https://www.aclweb.org/anthology/N16-1105)                           |                                        [link](https://www.aclweb.org/anthology/N16-1105)                                         |
| 2016     | **STransE**    |                    **STransE: A Novel Embedding Model of Entities and Relationships in Knowledge Bases**                    | NAACL-HLT | Transductive |                          [link](https://www.aclweb.org/anthology/N16-1054/)                           |                                         [link](https://github.com/datquocnguyen/STransE)                                         |
| 2015     | **TransD**     |                                  **Knowledge Graph Embedding via Dynamic Mapping Matrix**                                   |    ACL    | Transductive |                             [link](https://aclanthology.org/P15-1067.pdf)                             |                                                                -                                                                 |
| 2015     | **TransR**     |                         **Learning Entity and Relation Embeddings for Knowledge Graph Completion**                          |   AAAI    | Transductive |                 [link](https://linyankai.github.io/publications/aaai2015_transr.pdf)                  |                                     [link](https://github.com/mrlyk423/relation_extraction)                                      |
| 2015     | **RTransE**    |                                        **Composing Relationships with Translations**                                        |   EMNLP   | Transductive |                             [link](https://aclanthology.org/D15-1034.pdf)                             |                                             [link](https://github.com/glorotxa/SME)                                              |
| 2015     | **KG2E**      |                             **Learning to Represent Knowledge Graphs with Gaussian Embedding**                              |   CIKM    | Transductive |                        [link](https://dl.acm.org/doi/10.1145/2806416.2806502)                         |                                                                -                                                                 |
| 2014     | **TransM**     |                      **Transition-based Knowledge Graph Embedding with Relational Mapping Properties**                      |  PACLIC   | Transductive |                             [link](https://aclanthology.org/Y14-1039.pdf)                             |                                                                -                                                                 |
| 2014     | **TransH**     |                                 **Knowledge Graph Embedding by Translating on Hyperplanes**                                 |   AAAI    | Transductive |                [link](https://ojs.aaai.org/index.php/AAAI/article/download/8870/8729)                 |                                                                -                                                                 |
| 2013     | **TransE**     |                                **Translating Embeddings for Modeling Multi-relational Data**                                |  NeurIPS  | Transductive |   [link](https://proceedings.NeurIPS.cc/paper/2013/file/1cecc7a77928ca8133fa24680a88d2f9-Paper.pdf)   |                                                                -                                                                 |

[Back](#bookmarks-)

### Tensor Decompositional Models <span id="tensor-decompositional-models-"></span>
| **Year** |  **Model**  |                                            **Title**                                            | **Venue** | **Scenario** |                                               **Paper**                                               |                        **Code**                         |
|:--------:|:------------:|:-----------------------------------------------------------------------------------------------:|:---------:|:------------:|:-----------------------------------------------------------------------------------------------------:|:-------------------------------------------------------:|
|   2024   |    **NestE**    |                  **NestE: Modeling Nested Relational Structures for Knowledge Graph Reasoning**                   |   AAAI    | Transductive |                      [Link](https://ojs.aaai.org/index.php/AAAI/article/download/28772/29482)                      |                                                                 [Link](https://github.com/xiongbo010/NestE)                                                                 |    
|   2024   |   **CompilE**    |                  **Modeling Knowledge Graphs with Composite Reasoning**                   |   AAAI    | Transductive |                      [Link](https://ojs.aaai.org/index.php/AAAI/article/download/28675/29311)                      |                                                                  [Link](https://github.com/zlq147/CompilE)                                                                  |
| 2022     | **QuatRE**   | **QuatRE: Relation-Aware Quaternions for Knowledge Graph Embeddings**                           | WWW       | Transductive | [Link](https://arxiv.org/pdf/2009.12517.pdf)                                                          |     [Link](https://github.com/daiquocnguyen/QuatRE)     |
| 2022     | **GIE**      | **Geometry Interaction Knowledge Graph Embeddings**                                             | AAAI      | Transductive | [Link](https://www.aaai.org/AAAI22Papers/AAAI-11284.CaoZ.pdf)                                         |         [Link](https://github.com/Lion-ZS/GIE)          |
| 2021     | **HopfE**    | **HopfE: Knowledge Graph Representation Learning using Inverse Hopf Fibrations**                | CIKM      | Transductive | [link](https://dl.acm.org/doi/10.1145/3459637.3482263)                                                |         [link](https://github.com/ansonb/HopfE)         |
| 2021     | **DualE**    | **Dual Quaternion Knowledge Graph Embeddings**                                                  | AAAI      | Transductive | [link](https://ojs.aaai.org/index.php/AAAI/article/view/16850)                                        |        [link](https://github.com/Lion-ZS/DualE)         |
| 2020     | **SEEK**     | **SEEK: Segmented Embedding of Knowledge Graphs**                                               | ACL       | Transductive | [Link](https://www.aclweb.org/anthology/2020.acl-main.358/)                                           |        [Link](https://github.com/Wentao-Xu/SEEK)        |
| 2020     | **LowFER**   | **LowFER: Low-rank Bilinear Pooling for Link Prediction**                                       | ICML      | Transductive | [Link](http://proceedings.mlr.press/v119/amin20a)                                                     |        [Link](https://github.com/suamin/LowFER)         |
| 2020     | **B-CP**     | **A Greedy Bit-flip Training Algorithm for Binarized Knowledge Graph Embeddings**               | EMNLP     | Transductive | [Link](https://www.aclweb.org/anthology/2020.findings-emnlp.10/)                                      |                            -                            |
| 2020     | **BTDE**     | **BTDE: Block Term Decomposition Embedding for Link Prediction in Knowledge Graph**             | ECAI      | Transductive | [Link](http://ebooks.iospress.nl/publication/54966)                                                   |                            -                            |
| 2020     | **MEI**     | **Multi-Partition Embedding Interaction with Block Term Format for Knowledge Graph Completion** | ECAI      | Transductive | [Link](http://ebooks.iospress.nl/publication/54979)                                                   |  [Link](https://github.com/tranhungnghiep/AnalyzeKGE)   |
| 2019     | **QuatE**    | **Quaternion Knowledge Graph Embeddings**                                                       | NeurIPS   | Transductive | [Link](http://papers.nips.cc/paper/8541-quaternion-knowledge-graph-embeddings)                        |      [Link](https://github.com/cheungdaven/QuatE)       |
| 2019     | **DihEdral** | **Relation Embedding with Dihedral Group in Knowledge Graph**                                   | ACL       | Transductive | [Link](https://www.aclweb.org/anthology/P19-1026/)                                                    |                            -                            |
| 2019     | **TuckER**   | **TuckER: Tensor Factorization for Knowledge Graph Completion**                                 | EMNLP     | Transductive | [Link](https://www.aclweb.org/anthology/D19-1522/)                                                    |      [Link](https://github.com/ibalazevic/TuckER)       |
| 2019     | **CrossE**   | **Interaction Embeddings for Prediction and Explanation in Knowledge Graphs**                   | WSDM      | Transductive | [Link](https://dl.acm.org/doi/10.1145/3289600.3291014)                                                |       [Link](https://github.com/wencolani/CrossE)       |
| 2018     | **HOLEX**    | **Expanding Holographic Embeddings for Knowledge Completion**                                   | NeurIPS   | Transductive | [Link](https://proceedings.NeurIPS.cc/paper/2018/hash/dd28e50635038e9cf3a648c2dd17ad0a-Abstract.html) |                            -                            |
| 2018     | **SimplE**   | **SimplE Embedding for Link Prediction in Knowledge Graphs**                                    | NeurIPS   | Transductive | [Link](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs)     |       [Link](https://github.com/Mehran-k/SimplE)        |
| 2017     | **ANALOGY**  | **Analogical Inference for Multi-relational Embeddings**                                        | ICML      | Transductive | [Link](http://proceedings.mlr.press/v70/liu17d.html)                                                  |        [Link](https://github.com/quark0/ANALOGY)        |
| 2016     | **HolE**    | **Holographic Embeddings of Knowledge Graphs**                                                  | AAAI      | Transductive | [Link](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12484)                               | [Link](https://github.com/mnick/holographic-embeddings) |
| 2016     | **ComplEx**  | **Complex Embeddings for Simple Link Prediction**                                               | ICML      | Transductive | [Link](http://proceedings.mlr.press/v48/trouillon16.html)                                              |        [Link](https://github.com/ttrouill/complex)      |
| 2015     | **DISTMULT** | **Embedding Entities and Relations for Learning and Inference in Knowledge Bases**              | ICLR      | Transductive | [Link](https://arxiv.org/abs/1412.6575)                                                               |                            -                            |
| 2011     | **RESCAL**   | **A Three-Way Model for Collective Learning on Multi-Relational Data**                          | ICML      | Transductive | [Link](https://icml.cc/2011/papers/438_icmlpaper.pdf)                                                 |       [Link](https://github.com/mnick/scikit-kge)       |

[Back](#bookmarks-)

### Neural Network Models <span id="neural-network-models-"></span>
#### Tranditional NN Models <span id="traditonal-neural-network-models-"></span>
| **Year** | **Model** | **Title**                                                                       | **Venue**        | **Scenario** | **Paper**                                                                                                    |                **Code**                |
|----------|-----------|---------------------------------------------------------------------------------|------------------|--------------|--------------------------------------------------------------------------------------------------------------|:--------------------------------------:|
| 2024     | **LAFA** | **LAFA: Multimodal Knowledge Graph Completion with Link Aware Fusion and Aggregation**                  | AAAI             | Transductive | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28732)                                                                 | [Link]() |
| 2017     | **ProjE** | **ProjE: Embedding Projection for Knowledge Graph Completion**                  | AAAI             | Transductive | [Link](https://arxiv.org/pdf/1611.05425.pdf)                                                                 | [Link](https://github.com/bxshi/ProjE) |
| 2016     | **NAM**   | **Probabilistic Reasoning via Deep Learning: Neural Association Models**        | arXiv            | Transductive | [Link](https://arxiv.org/pdf/1603.07704.pdf)                                                                 |                   -                    |
| 2013     | **SME**   | **A semantic matching energy function for learning with multi-relational data** | Machine Learning | Transductive | [Link](https://arxiv.org/pdf/1301.3485)                                                                      |                   -                    |
| 2013     | **NTN**   | **Reasoning With Neural Tensor Networks for Knowledge Base Completion**         | NeurIPS          | Transductive | [Link](http://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion) |                   -                    |

[Back](#bookmarks-)

#### CNN Models <span id="convolutional-neural-network-models-"></span>
| **Year** | **Model Name** |                                                 **Title**                                                | **Venue** | **Scenario** |                                               **Paper**                                               |                     **Code**                     |
|:--------:|:--------------:|:--------------------------------------------------------------------------------------------------------:|:---------:|:------------:|:-----------------------------------------------------------------------------------------------------:|:------------------------------------------------:|
|   2023   | **ConvRot**       | **Knowledge graph embedding by relational rotation and complex convolution for link prediction**      | Expert Syst Appl   | Transductive | [Link](https://www.sciencedirect.com/science/article/pii/S0957417422021406) |         [Link](https://github.com/lnthanhhcmus/ConvRot)        |
|   2021   | **ConE**       | **ConE: Cone Embeddings for Multi-Hop Reasoning over Knowledge Graphs**                                  | NeurIPS   | Transductive | [Link](https://proceedings.NeurIPS.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html) |                        -                         |
| 2021     | **ConEx**      | **Convolutional Complex Knowledge Graph Embeddings**                                                     | ESWC      | Transductive |               [Link](https://link.springer.com/chapter/10.1007%2F978-3-030-77385-4_24)                |  [Link](https://github.com/Jean-KOUAGOU/ConEx)   |
| 2020     | **InteractE**  | **InteractE: Improving Convolution-based Knowledge Graph Embeddings by Increasing Feature Interactions** | AAAI      | Transductive |                     [Link](https://aaai.org/ojs/index.php/AAAI/article/view/5694)                     | [Link](https://github.com/malllabiisc/InteractE) |
| 2019     | **ConvR**      | **Adaptive Convolution for Multi-Relational Learning**                                                   | NAACL-HLT | Transductive |                          [Link](https://www.aclweb.org/anthology/N19-1103/)                           |                        -                         |
| 2019     | **HypER**      | **Hypernetwork Knowledge Graph Embeddings**                                                              | ICANN     | Transductive |                             [Link](https://arxiv.org/pdf/1808.07018.pdf)                              |                        -                         |
| 2018     | **ConvKB**     | **A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network**          | NAACL-HLT | Transductive |                          [Link](https://www.aclweb.org/anthology/N18-2053/)                           | [Link](https://github.com/daiquocnguyen/ConvKB)  |
| 2018     | **ConvE**      | **Convolutional 2D Knowledge Graph Embeddings**                                                          | AAAI      | Transductive |                       [Link](https://arxiv.org/pdf/1707.01476.pdf)                                    |   [Link](https://github.com/TimDettmers/ConvE)   |

[Back](#bookmarks-)

#### GNN Models <span id="graph-neural-network-models-"></span>
 |**Year** | **Model**     | **Title**                                                                                                       | **Venue**    | **Scenario**    | **Paper**                                                                                                                                                          | **Code**                                                              |
|----------|---------------|-----------------------------------------------------------------------------------------------------------------|--------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
|   2024   |   **HyRel**    | **RHKH: Relational Hypergraph Neural Network for Link Prediction on N-ary Knowledge Hypergraph**      |       ACM MM       | Transductive | [Link](https://openreview.net/attachment?id=8iKQctHLL7&name=pdf) |                    [Link](-)                      |
|   2024   |   **HyRel**    | **Generalize to Fully Unseen Graphs: Learn Transferable Hyper-Relation Structures for Inductive Link Prediction**      |       ACM MM       | Transductive | [Link](https://openreview.net/attachment?id=rIu1efxaLg&name=pdf) |                    [Link](https://github.com/hncps6/HyRel)                      |
|   2024   |   **MGTCA**    | **Mixed Geometry Message and Trainable Convolutional Attention Network for Knowledge Graph Completion**      |       AAAI       | Transductive | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/28745/29434) |                        -                         |
|   2024   |   **MINES**    | **MINES: Message Intercommunication for Inductive Relation Reasoning over Neighbor-Enhanced Subgraphs**      |       AAAI       | Inductive | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/28935/29778) |                        -                         |
| 2023 | **C-MPNN** | **A Theory of Link Prediction via Relational Weisfeiler-Leman on Knowledge Graphs** | NeurIPS |   Inductive  | [Link](https://arxiv.org/pdf/2302.02209.pdf) |     [Link](https://github.com/HxyScotthuang/CMPNN)    |
| 2023     | **AdaProp**      | **AdaProp: Learning Adaptive Propagation for Graph Neural Network based Knowledge Graph Reasoning**                                   | KDD        | Inductive       | [Link](https://arxiv.org/pdf/2205.15319.pdf)                                                                                                                       | [Link](https://github.com/LARS-research/AdaProp)                                 |
| 2023     | **InGram**      | **InGram: Inductive Knowledge Graph Embedding via Relation Graphs**                                   | ICML        | Inductive       | [Link](https://arxiv.org/abs/2305.19987)                                                                                                                       | [Link](https://github.com/bdi-lab/InGram)                                 |
| 2023     | **REPORT**      | **Inductive Relation Prediction from Relational Paths and Context with Hierarchical Transformer**                                   | arXiv        | Inductive       | [Link](https://arxiv.org/pdf/2304.00215.pdf)                                                                                                                       | -                                 |
| 2023     | **DEKG-ILP**      | **Disconnected Emerging Knowledge Graph Oriented Inductive Link Prediction**                                   | ICDE        | Inductive       | [Link](https://arxiv.org/pdf/2209.01397.pdf)                                                                                                                       | [Link](https://github.com/Ninecl/DEKG-ILP)                                 |
| 2023     | **RMPI**      | **Relational Message Passing for Fully Inductive Knowledge Graph Completion**                                   | ICDE        | Inductive       | [Link](https://arxiv.org/pdf/2210.03994.pdf)                                                                                                                       | [Link](https://github.com/zjukg/RMPI)                                 |
| 2023     | **TransEQ**      | **TWO BIRDS, ONE STONE: AN EQUIVALENT TRANSFORMATION FOR HYPER-RELATIONAL KNOWLEDGE GRAPH MODELING**                          | arXiv         | Transductive    | [Link](https://openreview.net/pdf?id=e3U6bGsfcA)                                                                                                                       |                       -                         |
| 2022     | **LogCo**      | **Inductive Relation Prediction with Logical Reasoning Using Contrastive Representations**                                   | EMNLP        | Inductive       | [Link](https://aclanthology.org/2022.emnlp-main.286.pdf)                                                                                                                       | [Link](https://github.com/pyd418/LogCo)                                |
| 2022     | **NoGE**      | **Node Co-occurrence based Graph Neural Networks for Knowledge Graph Link Prediction**                          | WSDM         | Transductive    | [Link](https://arxiv.org/pdf/2104.07396.pdf)                                                                                                                       |        -                        |
| 2022     | **SGI**       | **Subgraph Representation Learning with Hard Negative Samples for Inductive Link Prediction**                   | ICASSP       | Inductive       | [Link](https://ieeexplore.ieee.org/document/9747485)                                                                                                               | -                                                                     |
| 2022     | **RED-GNN**   | **Knowledge Graph Reasoning with Relational Digraph**                                                           | WWW          | Inductive       | [Link](https://arxiv.org/pdf/2108.06040.pdf)                                                                                                                       | [Link](https://github.com/AutoML-Research/RED-GNN)                    |
| 2022     | **ConGLR**    | **Incorporating Context Graph with Logical Reasoning for Inductive Relation Prediction**                        | SIGIR        | Inductive       | [Link](https://dl.acm.org/doi/10.1145/3477495.3531996)                                                                                                             | -                                                                     |
| 2022     | **CFAG**      | **Exploring Relational Semantics for Inductive Knowledge Graph Completion**                                     | AAAI         | Inductive       | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20337)                                                                                                     | -                                                                     |
| 2022     | **IKGE**      | **Open-world knowledge graph completion for unseen entities and relations via attentive feature aggregation**   | IS           | Inductive       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S002002552101207X?via%3Dihub)                                                                         | -                                                                     |
| 2022     | **MorsE**     | **Meta-Knowledge Transfer for Inductive Knowledge Graph Embedding**                                             | SIGIR        | Inductive       | [Link](https://dl.acm.org/doi/10.1145/3477495.3531757)                                                                                                             | [Link](https://github.com/zjukg/MorsE)                                |
| 2022     | **BERTRL**    | **Inductive Relation Prediction by BERT**                                                                       | AAAI         | Inductive       | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20537/20296)                                                                                               | [Link](https://github.com/zhw12/BERTRL)                               |
| 2022     | **CBGNN**     | **CYCLE REPRESENTATION LEARNING FOR INDUCTIVE RELATION PREDICTION**                                             | ICLR Worshop | Inductive       | [Link](https://openreview.net/pdf?id=SYUMkBZk6gq)                                                                                                                  | -                                                                     |
| 2022     | **SNRI**      | **Subgraph Neighboring Relations Infomax for Inductive Link Prediction**                                     | IJCAI        | Inductive       | [Link](https://arxiv.org/pdf/2208.00850.pdf)                                                                                                                       | [Link](https://github.com/Tebmer/SNRI)                                |
| 2022     | **TEMP**      | **Type-aware Embeddings for Multi-Hop Reasoning over Knowledge Graphs**                                         | arXiv        | Inductive       | [Link](https://arxiv.org/pdf/2205.00782.pdf)                                                                                                                       | [Link](https://github.com/zhiweihu1103/QE-TEMP)                       |
| 2022     | **Meta-iKG**  | **Subgraph-aware Few-Shot Inductive Link Prediction via Meta-Learning**                                         | TKDE         | Inductive       | [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9780162)                                                                                           | -                                                                     |
| 2022     | **CSR**       | **Few-shot Relational Reasoning via Connection Subgraph Pretraining**                                           | NeurIPS      | Inductive       | [Link](https://arxiv.org/pdf/2210.06722.pdf)                                                                                                                       | [Link](https://github.com/snap-stanford/csr)                          |
| 2021     | **KE-GCN**    | **Knowledge Embedding Based Graph Convolutional Network**                                                       | WWW          | Transductive    | [Link](https://arxiv.org/pdf/2006.07331.pdf)                                                                                                                       | [Link](https://github.com/PlusRoss/KE-GCN)                            |
| 2021     | **DisenKGAT** | **DisenKGAT: Knowledge Graph Embedding with Disentangled Graph Attention Network**                              | CIKM         | Transductive    | [Link](https://arxiv.org/pdf/2108.09628.pdf)                                                                                                                       | [Link](https://github.com/junkangwu/DisenKGAT)                        |
| 2021     | **M2GNN**     | **Mixed-Curvature Multi-Relational Graph Neural Network for Knowledge Graph Completion**                        | WWW          | Transductive    | [Link](https://assets.amazon.science/0c/9d/51d98f1040b1bfa7dc52d1015750/mixed-curvature-multi-relational-graph-neural-network-for-knowledge-graph-completion.pdf)  | -                                                                     |
| 2021     | **HRFN**      | **Meta-Learning Based Hyper-Relation Feature Modeling for Out-of-Knowledge-Base Embedding**                     | CIKM         | Inductive       | [Link](https://dl.acm.org/doi/abs/10.1145/3459637.3482367)                                                                                                         | -                                                                     |
| 2021     | **GEN**       | **Learning to Extrapolate Knowledge: Transductive Few-shot Out-of-Graph Link Prediction**                       | NeurIPS      | Inductive       | [Link](https://arxiv.org/pdf/2006.06648.pdf)                                                                                                                       | [Link](https://github.com/JinheonBaek/GEN)                            |
| 2021     | **SRGCN**     | **SRGCN: Graph-based multi-hop reasoning on knowledge graphs**                                                  | NC           | Transductive    | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0925231221007530)                                                                                    | -                                                                     |
| 2021     | **TRAR**      | **Target relational attention-oriented knowledge graph reasoning**                                              | NC           | Transductive    | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0925231221009668)                                                                                    | -                                                                     |
| 2021     | **KompaRe**   | **KompaRe: A Knowledge Graph Comparative Reasoning System**                                                     | KDD          | Transductive    | [Link](https://dl.acm.org/doi/10.1145/3447548.3467128)                                                                                                             | -                                                                     |
| 2021     | **INDIGO**    | **INDIGO: GNN-Based Inductive Knowledge Graph Completion Using Pair-Wise Encoding**                             | NeurIPS      | Inductive       | [Link](https://proceedings.NeurIPS.cc/paper/2021/file/0fd600c953cde8121262e322ef09f70e-Paper.pdf)                                                                  | -                                                                     |
| 2021     | **NBF-Net**   | **Neural Bellman-Ford Networks: A General Graph Neural Network Framework for Link Prediction**                  | NeurIPS      | Inductive       | [Link](https://arxiv.org/pdf/2106.06935.pdf)                                                                                                                       | [Link](https://github.com/DeepGraphLearning/NBFNet)                   |
| 2021     | **CoMPILE**   | **Communicative Message Passing for Inductive Relation Reasoning**                                              | AAAI         | Inductive       | [Link](https://arxiv.org/pdf/2012.08911.pdf)                                                                                                                       | [Link](https://github.com/TmacMai/CoMPILE_Inductive_Knowledge_Graph)  |
| 2021     | **TACT**      | **Topology-Aware Correlations Between Relations for Inductive Link Prediction in Knowledge Graphs**             | AAAI         | Inductive       | [Link](https://arxiv.org/pdf/2103.03642.pdf)                                                                                                                       | [Link](https://github.com/MIRALab-USTC/KG-TACT)                       |
| 2021     | **RPC-IR**    | **Learning First-Order Rules with Relational Path Contrast for Inductive Relation Reasoning**                   | TNNLS        | Inductive       | [Link](https://arxiv.org/pdf/2110.08810.pdf)                                                                                                                       | -                                                                     |
| 2020     | **DPMPN**     | **Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning**                       | ICLR         | Transductive    | [Link](https://arxiv.org/pdf/1909.11334.pdf)                                                                                                                       | [Link](https://github.com/anonymousauthor123/DPMPN)                   |
| 2020     | **RGHAT**     | **Relational Graph Neural Network with Hierarchical Attention for Knowledge Graph Completion**                  | AAAI         | Transductive    | [Link](https://ojs.aaai.org//index.php/AAAI/article/view/6508)                                                                                                     | -                                                                     |
| 2020     | **GAEAT**     | **GAEAT: Graph Auto-Encoder Attention Networks for Knowledge Graph Completion**                                 | cikm         | Transductive    | [Link](https://dl.acm.org/doi/10.1145/3340531.3412148)                                                                                                             | -                                                                     |
| 2020     | **COMPGCN**   | **Composition-based Multi-Relational Graph Convolutional Networks**                                             | ICLR         | Transductive    | [Link](https://arxiv.org/pdf/1911.03082.pdf)                                                                                                                       | [Link](https://github.com/malllabiisc/CompGCN)                        |
| 2020     | **GraIL**     | **Inductive Relation Prediction by Subgraph Reasoning**                                                         | ICML         | Inductive       | [Link](http://proceedings.mlr.press/v119/teru20a.html)                                                                                                             | [Link](https://github.com/kkteru/grail)                               |
| 2019     | **M-GNN**     | **Robust Embedding with Multi-Level Structures for Link Prediction**                                            | IJCAI        | Transductive    | [Link](https://www.ijcai.org/proceedings/2019/0728.pdf)                                                                                                            | -                                                                     |
| 2019     | **SACN**      | **End-to-End Structure-Aware Convolutional Networks for Knowledge Base Completion**                             | AAAI         | Transductive    | [Link](https://ojs.aaai.org//index.php/AAAI/article/view/4164)                                                                                                     | [Link](https://github.com/JD-AI-Research-Silicon-Valley/SACN)         |
| 2019     | **A2N**       | **A2N: Attending to Neighbors for Knowledge Graph Inference**                                                   | ACL          | Transductive    | [Link](https://aclanthology.org/P19-1431.pdf)                                                                                                                      | -                                                                     |
| 2019     | **KBGAT**     | **Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs**                             | ACL          | Transductive    | [Link](https://aclanthology.org/P19-1466.pdf)                                                                                                                      | [Link](https://github.com/deepakn97/relationPrediction)               |
| 2019     | **TransGCN**  | **TransGCN: Coupling Transformation Assumptions with Graph Convolutional Networks for Link Prediction**         | K-CAP        | Transductive    | [Link](https://dl.acm.org/doi/pdf/10.1145/3360901.3364441)                                                                                                         | -                                                                     |
| 2019     | **LAN**       | **Logic Attention Based Neighborhood Aggregation for Inductive Knowledge Graph Embedding**                      | AAAI         | Inductive       | [Link](https://arxiv.org/pdf/1811.01399.pdf)                                                                                                                       | [Link](https://github.com/wangpf3/LAN)                                |
| 2018     | **RGCN**      | **Modeling Relational Data with Graph Convolutional Networks**                                                  | ESWC         | Transductive    | [Link](https://arxiv.org/pdf/1703.06103.pdf)                                                                                                                       | [Link](https://github.com/thiviyanT/torch-rgcn)                       |
| 2017     | **-**         | **Knowledge Transfer for Out-of-Knowledge-Base Entities: A Graph Neural Network Approach**                      | IJCAI        | Inductive       | [Link](https://arxiv.org/pdf/1706.05674.pdf)                                                                                                                       | [Link](https://github.com/takuo-h/GNN-for-OOKB)                       |

[Back](#bookmarks-)

#### Transformer Models <span id="transformer-models-"></span>
|**Year** | **Model**     | **Title**                                                                                                       | **Venue**    | **Scenario**    | **Paper**                                                                                                                                                          | **Code**                                                              |
|----------|---------------|-----------------------------------------------------------------------------------------------------------------|--------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| 2024     | **PMD**      | **Progressive Distillation Based on Masked Generation Feature Method for Knowledge Graph Completion**                                   |  AAAI   | Inductive       | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28680)          | [Link](https://github.com/cyjie429/PMD)                           |
| 2024     | **KnowFormer**      | **KnowFormer: Revisiting Transformers for Knowledge Graph Reasoning**                                   |  ICML   | Inductive       | [Link]([https://arxiv.org/pdf/2303.15682.pdf](https://openreview.net/pdf?id=EncFNR3hxM))                                                                                                                       | -                              |
| 2023     | **iHT**      | **Pre-training Transformers for Knowledge Graph Completion**                                   |  arXiv   | Inductive       | [Link](https://arxiv.org/pdf/2303.15682.pdf)                                                                                                                       | -                              |
| 2023     | **LambdaKG**      | **LambdaKG: A Library for Pre-trained Language Model-Based Knowledge Graph Embeddings**                                   |  arXiv   | Transductive       | [Link](https://arxiv.org/abs/2210.00305)                                                                                                                       | [Link](https://zjunlp.github.io/project/promptkg/)                                 |
| 2022     | **Ruleformer**      | **Ruleformer: Context-aware Rule Mining over Knowledge Graph**                                   | COLING        | Transductive       | [Link](https://aclanthology.org/2022.coling-1.225.pdf)                                                                                                                       | [Link](https://github.com/zjukg/ruleformer)                                 |
| 2022     | **kgTransformer**      | **Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries**                                   | KDD        | Inductive       | [Link](http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf)                                                                                                                       | [Link](https://github.com/THUDM/kgTransformer)                                 |
| 2022     | **Kformer**      | **Kformer: Knowledge Injection in Transformer Feed-Forward Layers**                                   | NLPCC        | Transductive       | [Link](https://arxiv.org/pdf/2201.05742.pdf)                                                                                                                       | [Link](https://github.com/zjunlp/Kformer)                                 |
|   2022   |      **TET**      | **Transformer-based Entity Typing in Knowledge Graphs**                                          |   EMNLP   |                                    [Link](https://aclanthology.org/2022.emnlp-main.402.pdf)                                   | [Link](https://github.com/zhiweihu1103/ET-TET)                              |
| 2022     | **KPGT**      | **KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction**                                   | COLING        | Transductive       | [Link](https://arxiv.org/pdf/2206.03364.pdf)                                                                                                                       | -                                |
|   2021   |     **HittER**     | **HittER: Hierarchical Transformers for Knowledge Graph Embeddings**                                          |   EMNLP   |                                    [Link](https://arxiv.org/pdf/2008.12813.pdf)                                   | [Link](https://github.com/sanxing-chen/HittER)                              |
| 2020     | **-**      | **Multi-Task Learning for Knowledge Graph Completion with Pre-trained Language Models**                                   | COLING        | Transductive       | [Link](https://aclanthology.org/2020.coling-main.153.pdf)                                                                                                                       | -                                |
| 2020     | **CoKE**      | **CoKE: Contextualized Knowledge Graph Embedding**                                   | arXiv        | Transductive       | [Link](https://arxiv.org/pdf/1911.02168.pdf)                                                                                                                       | [Link](https://github.com/PaddlePaddle/Research/tree/master/KG/CoKE)                                 |
| 2020     | **KG-BERT**      | **KG-BERT: BERT for knowledge graph completion**                                   | AAAI        | Transductive       | [Link](https://arxiv.org/pdf/1909.03193.pdf)                                                                                                                       | [Link](https://github.com/yao8839836/kg-bert)                                 |
|   2020   |     **CODEX**      | **CoDEx: A Comprehensive Knowledge Graph Completion Benchmark**                                          |   EMNLP    |                             [Link](https://aclanthology.org/2020.emnlp-main.669.pdf)                                   | [Link](https://bit.ly/2EPbrJs)                                                        |
|   2019   | **ATOMIC** | **ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning**                                          |    AAAI    |                                    [Link](https://arxiv.org/pdf/1811.00146.pdf)                                   | [Link](https://maartensap.com/atomic/)                              |
|   2023   | **KG-R3** | **A Retrieve-and-Read Framework for Knowledge Graph Link Prediction**                                          |    CIKM    | Transductive                                                                      | [Link](https://arxiv.org/pdf/2212.09724.pdf)                              |[Link](https://github.com/OSU-NLP-Group/KG-R3/)

[Back](#bookmarks-)


### Path-based Models <span id="path-based-models-"></span>
| **Year** | **Model**     | **Title**                                                                                                        | **Venue**        | **Scenario** | **Paper**                                                          |                        **Code**                       |
|----------|---------------|------------------------------------------------------------------------------------------------------------------|------------------|--------------|--------------------------------------------------------------------|:-----------------------------------------------------:|
| 2023 | **AstarNet** |  **AstarNet: A Scalable Path-based Reasoning Approach for Knowledge Graphs** | NeurIPS | Transductive |   [Link](https://arxiv.org/pdf/2206.04798.pdf)   | [Link](https://github.com/DeepGraphLearning/AStarNet) |
| 2022     | **CURL**      | **Learning to Walk with Dual Agents for Knowledge Graph Reasoning**                                              | AAAI             | Transductive | [Link](https://arxiv.org/pdf/2112.12876.pdf)                       | [Link](https://github.com/RutgersDM/DKGR/tree/master) |
| 2019     | **CPL**       | **Collaborative policy learning for open knowledge graph reasoning**                                             | EMNLP            | Transductive | [Link](https://arxiv.org/pdf/1909.00230.pdf)                       | [Link](https://github.com/shanzhenren/CPL)            |
| 2018     | **DIVA**      | **Variational Knowledge Graph Reasoning**                                                                        | NAACL            | Transductive | [Link](https://arxiv.org/pdf/1803.06581.pdf)                       | -                                                     |
| 2018     | **MINERVA**   | **Go for a Walk and Arrive at the Answer: Reasoning Over Paths in Knowledge Bases using Reinforcement Learning** | ICLR             | Transductive | [Link](https://arxiv.org/pdf/1711.05851.pdf)                       | [Link](https://github.com/shehzaadzd/MINERVA)         |
| 2018     | **Multi-Hop** | **Multi-Hop Knowledge Graph Reasoning with Reward Shaping**                                                      | EMNLP            | Transductive | [Link](https://arxiv.org/pdf/1808.10568.pdf)                       | [Link](https://github.com/salesforce/MultiHopKG)      |
| 2018     | **M-Walk**    | **M-Walk: Learning to walk over graphs using monte carlo tree search**                                           | NeurIPS          | Transductive | [Link](https://arxiv.org/pdf/1802.04394.pdf)                       | [Link](https://github.com/yelongshen/GraphWalk)       |
| 2017     | **LogSumExp** | **Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks**                       | EACL             | Transductive | [Link](https://aclanthology.org/E17-1013.pdf)                      | [Link](https://rajarshd.github.io/ChainsofReasoning/) |
| 2017     | **DeepPath**  | **DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning**                                      | EMNLP            | Transductive | [Link](https://arxiv.org/pdf/1707.06690.pdf)                       | [Link](https://github.com/xwhan/DeepPath)             |
| 2015     | **RNNPRA**    | **Compositional Vector Space Models for Knowledge Base Completion**                                              | AAAI             | Transductive | [Link](https://arxiv.org/pdf/1504.06662.pdf)                       | -                                                     |
| 2014     | **ProPPR**    | **Incorporating Vector Space Similarity in Random Walk Inference over Knowledge Bases**                          | EMNLP            | Transductive | [Link](https://emnlp2014.org/papers/pdf/EMNLP2014044.pdf)          | -                                                     |
| 2010     | **PRA**       | **Relational retrieval using a combination of path-constrained random walks**                                    | Machine Learning | Transductive | [Link](https://www.cs.cmu.edu/~wcohen/postscript/ecml-2010-ni.pdf) | -                                                     |

[Back](#bookmarks-)

### Rule-based Models <span id="rule-based-models-"></span>
| **Year** | **Model**         | **Title**                                                                                       | **Venue** | **Scenario** | **Paper**                                                                                                                          |                        **Code**                        |
|----------|-------------------|-------------------------------------------------------------------------------------------------|-----------|--------------|------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------:|
| 2024     | **FIT**           | **RETHINKING COMPLEX QUERIES ON KNOWLEDGE GRAPHS WITH NEURAL LINK PREDICTORS** | ICLR                    | Transductive |  [Link](https://openreview.net/pdf?id=1BmveEMNbG) |                    [Link](-)                   |
| 2023   | **DiffLogic** | **Differentiable Neuro-Symbolic Reasoning on Large-Scale Knowledge Graphs** | NeurIPS | Inductive |  [Link](https://openreview.net/pdf?id=bETvUctiTR) |                    [Link](-)                   |
| 2023     | **NCRL** | **NEURAL COMPOSITIONAL RULE LEARNING FOR KNOWLEDGE GRAPH REASONING**                              | ICLR      | Inductive    | [Link](https://openreview.net/pdf?id=F8VKQyDgRVj)                                                                                   | [Link](https://github.com/vivian1993/NCRL.git)                                                   |
| 2023     | **RulE** | **Neural-Symbolic Knowledge Graph Reasoning with Rule Embedding**                              | arXiv      | Inductive    | [Link](https://openreview.net/pdf?id=UBSPGUwjNV)                                                                                   | [Link](https://github.com/XiaojuanTang/RulE)                                                   |
| 2023 |  **LSTK** | **Learning from Both Structural and Textual Knowledge for Inductive Knowledge Graph Completion** |         NeurIPS         |   Inductive  |                 [Link](https://openreview.net/pdf?id=j7x9wW3tCf)                |        [Link](https://github.com/qikunxun/LSTK)       |
| 2022 |   **RF**   |      **Dynamic knowledge graph reasoning based on deep reinforcement learning**     | Knowledge-Based Systems | Transductive | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0950705122000697) |                        [Link]()                       |
| 2022     | **RLogic** | **RLogic: Recursive Logical Rule Learning from Knowledge Graphs**                              | KDD      | Inductive    | [Link](https://web.cs.ucla.edu/~yzsun/papers/2022_KDD_RLogic.pdf)                                                                                   | -                                                     |
| 2021     | **RNNLOGIC** | **RNNLOGIC: LEARNING LOGIC RULES FOR REASONING ON KNOWLEDGE GRAPHS**                              | ICLR      | Inductive    | [Link](https://arxiv.org/pdf/2010.04029.pdf)                                                                                   | [Link](https://github.com/DeepGraphLearning/RNNLogic)                                                      |
| 2020     | **Neural-Num-LP** | **Differentiable learning of numerical rules in knowledge graphs**                              | ICLR      | Inductive    | [Link](https://openreview.net/pdf?id=rJleKgrKwS)                                                                                   | -                                                      |
| 2020     | **ExpressGNN**    | **Efficient probabilistic logic reasoning with graph neural networks**                          | ICLR      | Inductive    | [Link](https://arxiv.org/pdf/2001.11850.pdf)                                                                                       | [Link](https://github.com/expressGNN/ExpressGNN)       |
| 2019     | **IterE**         | **Iteratively learning embeddings and rules for knowledge graph reasoning,**                    | WWW       | Inductive    | [Link](https://arxiv.org/pdf/1903.08948.pdf)                                                                                       | [Link](https://github.com/wencolani/IterE)             |
| 2019     | **pLogicNet**     | **Probabilistic logic neural networks for reasoning**                                           | NeurIPS   | Inductive    | [Link](https://proceedings.NeurIPS.cc/paper/2019/file/13e5ebb0fa112fe1b31a1067962d74a7-Paper.pdf)                                  | [Link](https://github.com/DeepGraphLearning/pLogicNet) |
| 2019     | **DRUM**          | **DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs**                             | NeurIPS   | Inductive    | [Link](https://arxiv.org/pdf/1911.00055.pdf)                                                                                       | [Link](https://github.com/alisadeghian/DRUM)           |
| 2019     | **RLvLR**         | **An Embedding-based Approach to Rule Learning in Knowledge Graphs**                            | TKDE      | Inductive    | [Link](https://research-repository.griffith.edu.au/bitstream/handle/10072/387994/Ghiasnezhad%20Omran254156Accepted.pdf?sequence=5) | -                                                      |
| 2018     | **RuleN**         | **Fine-Grained Evaluation of Rule- and Embedding-Based Systems for Knowledge Graph Completion** | ISWC      | Inductive    | [Link](https://link.springer.com/chapter/10.1007/978-3-030-00671-6_1)                                                              | -                                                      |
| 2018     | **RUGE**          | **Knowledge graph embedding with iterative guidance from soft rules**                           | AAAI      | Inductive    | [Link](https://arxiv.org/pdf/1711.11231.pdf)                                                                                       | [Link](https://github.com/iieir-km/RUGE)               |
| 2017     | **NTP**           | **End-to-end differentiable proving**                                                           | NeurIPS   | Inductive    | [Link](https://arxiv.org/pdf/1705.11040.pdf)                                                                                       | -                                                      |
| 2017     | **NeuralLP**      | **Differentiable learning of logical rules for knowledge base reasoning**                       | NeurIPS   | Inductive    | [Link](https://arxiv.org/pdf/1702.08367.pdf)                                                                                       | [Link](https://github.com/fanyangxyz/Neural-LP)        |
| 2016     | **KALE**          | **Jointly embedding knowledge graphs and logical rules**                                        | EMNLP     | Inductive    | [Link](https://aclanthology.org/D16-1019.pdf)                                                                                      | [Link](https://aclanthology.org/D16-1019/)             |
| 2013     | **AMIE**          | **AMIE: association rule mining under incomplete evidence in ontological knowledge bases**      | WWW       | Inductive    | [Link](https://resources.mpi-inf.mpg.de/yago-naga/amie/amie.pdf)                                                                   | [Link](https://github.com/lajus/amie)                  |

[Back](#bookmarks-)

## Temporal Knowledge Graph Reasoning <span id="temporal-knowledge-graph-reasoning-"></span>
### Evaluation Papers <span id="rnn-based-models-"></span> 
| **Year** | **Title** | **Venue** |  **Scenario**  | **Paper** | **Code** | 
|:--------:|:----------------:|:--------------------------------------------------------------------------------------------------------------------------------:|:----------------------:|:-------------:|:-------------:|
| 2022 | **On the Evaluation of Methods for Temporal Knowledge Graph Forecasting** |  NeurIPS | Extrapolation | [Link](https://openreview.net/pdf?id=J_SNklR-KR) | [Link](https://github.com/nec-research/TKG-Forecasting-Evaluation) | 


### RNN-based Models <span id="rnn-based-models-"></span>
#### Quadruple-based Models <span id="quadruple-based-models-"></span>
| **Year** |    **Model**     |                                                            **Title**                                                             |       **Venue**        |  **Scenario** |                                         **Paper**                                          |                                **Code**                                |
|:--------:|:----------------:|:--------------------------------------------------------------------------------------------------------------------------------:|:----------------------:|:-------------:|:------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2024 |     **ECEformer**    |                 **Transformer-based Reasoning for Learning Evolutionary Chain of Events on Temporal Knowledge Graph**                 |  SIGIR | Extrapolation |        [Link](https://arxiv.org/pdf/2405.00352)       |                      [Link](-)   
| 2024 |     **TEILP**    |                 **TEILP: Time Prediction over Knowledge Graphs via Logical Reasoning**                 |  AAAI | Interpolation |        [Link](https://arxiv.org/pdf/2312.15816.pdf)       |                      [Link](https://github.com/xiongsiheng/TEILP)   
| 2023 |     **TILP**    |                 **TILP: DIFFERENTIABLE LEARNING OF TEMPORAL LOGICAL RULES ON KNOWLEDGE GRAPHS**                 |  ICLR | Interpolation |        [Link](https://openreview.net/pdf?id=_X12NmQKvX)       |                      [Link](https://github.com/xiongsiheng/TILP)                     |
| 2022 |    **EvoKG**    |    **EvoKG: Jointly Modeling Event Time and Network Structure for Reasoning over Temporal Knowledge Graphs**    |  WSDM | Extrapolation |     [Link](https://dl.acm.org/doi/10.1145/3488560.3498451)    |    [Link](https://github.com/NamyongPark/EvoKG)    |
| 2021 |    **Tpmod**    |              **TPmod: A Tendency-Guided Prediction Model for Temporal Knowledge Graph Completion**              |  TKDD | Interpolation |         [Link](https://dl.acm.org/doi/10.1145/3443687)        |      [Link](https://github.com/DMKE-Lab/TPmod)     |
| 2021 |     **HIP**     | **HIP Network: Historical Information Passing Network for Extrapolation Reasoning on Temporal Knowledge Graph** | IJCAI | Extrapolation |       [Link](https://www.ijcai.org/proceedings/2021/264)      | [Link](https://github.com/Yongquan-He/HIP-network) |
| 2020 |     **TeMP**    |                    **TeMP: Temporal Message Passing for Temporal Knowledge Graph Completion**                   | EMNLP | Interpolation | [Link](https://www.aclweb.org/anthology/2020.emnlp-main.462/) |      [Link](https://github.com/JiapengWu/TeMP)     |
| 2018 |   **TTransE**   |                      **Learning Sequence Encoders for Temporal Knowledge Graph Completion**                     | EMNLP | Interpolation |          [Link](https://arxiv.org/pdf/1809.03202.pdf)         |      [Link](https://github.com/mniepert/mmkb)      |
| 2018 | **TA-DISTMULT** |                      **Learning Sequence Encoders for Temporal Knowledge Graph Completion**                     | EMNLP | Interpolation |          [Link](https://arxiv.org/pdf/1809.03202.pdf)         |                      [Link](-)                     |
| 2018 |  **TA-TransE**  |                      **Learning Sequence Encoders for Temporal Knowledge Graph Completion**                     | EMNLP | Interpolation |          [Link](https://arxiv.org/pdf/1809.03202.pdf)         |                      [Link](-)                     |
| 2017 | **Know-Evolve** |                      **Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs**                      |  ICML | Extrapolation |    [Link](http://proceedings.mlr.press/v70/trivedi17a.html)   |                      [Link](-)        |         

[Back](#bookmarks-)

#### Path-based Models <span id="path-based-models-"></span>
| **Year** |    **Model**     |                                                            **Title**                                                             |       **Venue**        |  **Scenario** |                                         **Paper**                                          |                                **Code**                                |
|:--------:|:----------------:|:--------------------------------------------------------------------------------------------------------------------------------:|:----------------------:|:-------------:|:------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2024 |     **TILR**    |                 **Temporal inductive logic reasoning**                 | IJCAI  | Interpolation |        [Link](https://arxiv.org/pdf/2206.05051.pdf)       |      [Link](-)                
| 2022 |     **ExKGR**    |             **ExKGR: Explainable Multi-hop Reasoning for Evolving Knowledge Graph**             |         DASFAA         | Interpolation |           [Link](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_11)           | [Link](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_10) |
| 2021 | **TimeTraveler** |        **TimeTraveler: Reinforcement Learning for Temporal Knowledge Graph Forecasting**        |          EMNLP         | Extrapolation |                    [Link](https://aclanthology.org/2021.emnlp-main.655/)                   |                [Link](https://github.com/JHL-HUST/TITer)               |
| 2021 |    **CluSTeR**   | **Search from History and Reason for Future: Two-stage Reasoning on Temporal Knowledge Graphs** |           ACL          | Extrapolation |                     [Link](https://aclanthology.org/2021.acl-long.365/)                    |                                [Link](-)                               |
| 2021 |     **Tpath**    |   **Multi-hop reasoning over paths in temporal knowledge graphs using reinforcement learning**  | Applied Soft Computing	 | Interpolation | [Link](https://www.sciencedirect.com/science/article/abs/pii/S1568494621000673?via%3Dihub) |                                [Link](-)                               |
| 2020 |    **DacKGR**    |   **Dynamic Anticipation and Completion for Multi-Hop Reasoning over Sparse Knowledge Graph**   |          EMNLP         | Interpolation |                        [Link](https://arxiv.org/pdf/2010.01899.pdf)                        |                [Link](https://github.com/THU-KEG/DacKGR) | 

[Back](#bookmarks-)

#### Graph-based Models <span id="graph-based-models-"></span>
| **Year** |    **Model**     |                                                            **Title**                                                             |       **Venue**        |  **Scenario** |                                         **Paper**                                          |                                **Code**                                |
|:--------:|:----------------:|:--------------------------------------------------------------------------------------------------------------------------------:|:----------------------:|:-------------:|:------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
|   2024   |     **IncDE**      |                               **Towards Continual Knowledge Graph Embedding via Incremental Distillation**                                |     AAAI     | - |    [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28722)    |               [Link](https://github.com/seukgcode/IncDE)           |
|   2023   |     **HGLS**      |                               **Learning Long- and Short-term Representations for Temporal Knowledge Graph Reasoning**                                |     WWW     | Extrapolation |    [Link](https://dl.acm.org/doi/pdf/10.1145/3543507.3583242)    |               [Link](https://github.com/CRIPAC-DIG/HGLS)           |
| 2023 | **LOGAE-TKG** |                                **Logistics Audience Expansion via Temporal Knowledge Graph**                                |  CIKM  | Interpolation |                                                          [Link](https://dl.acm.org/doi/pdf/10.1145/3583780.3614695)                                                         |                  [Link](-)                  |
| 2023 |   **LogCL**   |                  **Local-Global History-aware Contrastive Learning for Temporal Knowledge Graph Reasoning**                 |  ICDE  | Interpolation |                                                                 [Link](https://arxiv.org/pdf/2312.01601.pdf)                                                                |                  [Link](-)                  |
| 2023 |   **RETIA**   |               **RETIA: Relation-Entity Twin-Interact Aggregation for Temporal Knowledge Graph Extrapolation**               |  ICDE  | Extrapolation | [Link](https://opus.lib.uts.edu.au/bitstream/10453/166395/3/RETIA%20relation-entity%20twin-interact%20aggregation%20for%20temporal%20knowledge%20graph%20extrapolation.pdf) | [Link](https://github.com/CGCL-codes/RETIA) |
| 2023 |    **RPC**    |              **Learn from Relational Correlations and Periodic Events for Temporal Knowledge Graph Reasoning**              |  SIGIR | Extrapolation |                                                          [Link](https://dl.acm.org/doi/abs/10.1145/3539618.3591711)                                                         |                  [Link](-)                  |
| 2023 |  **HiSMatch** |                     **HiSMatch: Historical Structure Matching based Temporal Knowledge Graph Reasoning**                    |  arXiv | Extrapolation |                                                                 [Link](https://arxiv.org/pdf/2210.09708.pdf)                                                                |                  [Link](-)                  |
| 2022 |   **TiRGN**   | **TiRGN: Time-Guided Recurrent Graph Network with Local-Global Historical Patterns for Temporal Knowledge Graph Reasoning** |  IJCAI | Extrapolation |                                                           [Link](https://www.ijcai.org/proceedings/2022/0299.pdf)                                                           |  [Link](https://github.com/Liyyy2122/TiRGN) |
| 2022 |   **TRHyTE**  |                   **TRHyTE: Temporal Knowledge Graph Embedding Based on Temporal-Relational Hyperplanes**                   | DASFAA | Interpolation |                                                    [Link](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_10)                                                   |                  [Link](-)                  |
| 2021 |   **RE-GCN**  |                     **Temporal Knowledge Graph Reasoning Based on Evolutional Representation Learning**                     |  SIGIR | Extrapolation |                                                            [Link](https://dl.acm.org/doi/10.1145/3404835.3462963)                                                           |  [Link](https://github.com/Lee-zix/RE-GCN)  |
| 2020 | **EvolveGCN** |                           **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs**                           |  AAAI  | Extrapolation |                                                        [Link](https://ojs.aaai.org//index.php/AAAI/article/view/5984)                                                       |   [Link](https://github.com/IBM/EvolveGCN)  |
| 2020 |   **RE-NET**  |                **Recurrent Event Network: Autoregressive Structure Inferenceover Temporal Knowledge Graphs**                |  EMNLP | Extrapolation |                                                        [Link](https://www.aclweb.org/anthology/2020.emnlp-main.541/)                                                        |  [Link](https://github.com/INK-USC/RE-Net)  |

[Back](#bookmarks-)

### RNN-agnostic Models <span id="rnn-agnostic-models-"></span>
#### Time-Vector Guided Models <span id="time-vector-guided-models-"></span>
| **Year** |         **Model**         |                                                                    **Title**                                                                     | **Venue** |  **Scenario** |                           **Paper**                            |                                **Code**                                 |
|:--------:|:-------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:---------:|:-------------:|:--------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2024 |     **IME**     |                 **IME: Integrating Multi-curvature Shared and Specific Embedding for Temporal Knowledge Graph Completion**                 |    WWW    | Extrapolation |        [Link](https://arxiv.org/pdf/2403.19881)       |                         -                          |
|   2023   |        **DREAM**        |                              **DREAM: Adaptive Reinforcement Learning based on Attention Mechanism for Temporal Knowledge Graph Reasoning**                               |   SIGIR    | Extrapolation |   [Link](https://arxiv.org/pdf/2304.03984.pdf)   |           -           |
|   2022   |        **TLT-KGE**        |                              **Along the Time: Timeline-traced Embedding for Temporal Knowledge Graph Completion**                               |   CIKM    | Interpolation |   [Link](https://dl.acm.org/doi/pdf/10.1145/3511808.3557233)   |              [Link](https://github.com/zhangfw123/TLT-KGE)              |
|   2022   |        **TempoQR**        |                                          **TempoQR: Temporal Question Reasoning over Knowledge Graphs**                                          |   AAAI    | Interpolation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20526) |                [Link](https://github.com/cmavro/TempoQR)                |
|   2022   |         **BoxTE**         |                                           **Temporal Knowledge Graph Completion Using Box Embeddings**                                           |   AAAI    | Interpolation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20746) |                                    [Link](https://github.com/JohannesMessner/BoxTE)                                    |
|   2022   |       **TuckERTNT**       |                   **Tucker decomposition-based temporal knowledge graph completion**                   |    KBS    | Interpolation | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0950705121010303?via%3Dihub) |                                    -                                    |
|   2022   |  **RotateQVS**   | **RotateQVS: Representing Temporal Information as Rotations in Quaternion Vector Space for Temporal Knowledge Graph Completion** |          ACL           | Interpolation |                    [Link](https://aclanthology.org/2022.acl-long.402/)                     |                                   -                                    |
|   2021   |        **ChronoR**        |                                          **ChronoR: Rotation Based Temporal Knowledge Graph Embedding**                                          |   AAAI    | Interpolation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/16802) |                                    -                                    |
|   2021   |         **DBKGE**         |                                          **Learning Dynamic Embeddings for Temporal Knowledge Graphs**                                           |   WSDM    | Interpolation |          [Link](https://dl.acm.org/doi/abs/10.1145/3437963.3441741)          |                                    -                                    |
|   2021   |        **CyGNet**         |                      **Learning from History: Modeling Temporal Knowledge Graphs with Sequential Copy-Generation Networks**                      |   AAAI    | Extrapolation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/16604) |               [Link](https://github.com/CunchaoZ/CyGNet)                |
|   2021   |         **T-GAP**         |                              **Learning to Walk across Time for Interpretable Temporal Knowledge Graph Completion**                              |   SIGIR   | Interpolation |          [Link](https://arxiv.org/pdf/2012.10595.pdf)          |            [Link](https://github.com/anonymoususer99/T-GAP)             |
|   2021   |           **-**           | **Time-dependent Entity Embedding is not All You Need: A Re-evaluation of Temporal Knowledge Graph Completion Models under a Unified Framework** |   EMNLP   | Interpolation |     [Link](https://aclanthology.org/2021.emnlp-main.639/)      |                                    -                                    |
|   2021   |         **xERTE**         |                                 **Explainable Subgraph Reasoning for Forecasting on Temporal Knowledge Graphs**                                  |   ICLR    | Extrapolation |        [Link](https://iclr.cc/virtual/2021/poster/3378)        |             [Link](https://github.com/TemporalKGTeam/xERTE)             |
|   2020   |           **-**           |                                  **Towards Temporal Knowledge Graph Embeddings with Arbitrary Time Precision**                                   |   CIKM    | Interpolation |     [Link](https://dl.acm.org/doi/10.1145/3340531.3412028)     |                [Link](https://gitlab.com/jleblay/tokei)                 |
|   2020   |      **TNTComplEx**       |                                         **Tensor Decompositions for Temporal Knowledge Base Completion**                                         |   ICLR    | Interpolation |       [Link](https://openreview.net/forum?id=rke2P1BFwS)       |            [Link](https://github.com/facebookresearch/tkbc)             |
|   2018   |           **-**           |                                                  **Deriving Validity Time in Knowledge Graph**                                                   |    WWW    | Interpolation |   [Link](https://dl.acm.org/doi/pdf/10.1145/3184558.3191639)   |                                    -                                    |

[Back](#bookmarks-)

#### Time-Operation Guided Models <span id="time-operation-guided-models-"></span>
| **Year** |         **Model**         |                                               **Title**                                                | **Venue** |  **Scenario** |                                         **Paper**                                          |                                **Code**                                 |
|:--------:|:-------------------------:|:------------------------------------------------------------------------------------------------------:|:---------:|:-------------:|:------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
|   2024   |         **HGE**         |              **HGE: Embedding Temporal Knowledge Graphs in a Product Space of Heterogeneous Geometric Subspaces**              |   AAAI    | Interpolation |                        [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28739)                        |                                    [Link](https://github.com/NacyNiko/HGE)                            |
|   2024   |         **IncDE**         |              **Towards Continual Knowledge Graph Embedding via Incremental Distillation**              |   AAAI    | Extrapolation |                        [Link](https://ojs.aaai.org/index.php/AAAI/article/download/28722/29396)                        |                                    -                                    |
| 2024 |    **TEILP**    |                 **TEILP: Time Prediction over Knowledge Graphs via Logical Reasoning**                 |   AAAI    | Interpolation |        [Link](https://arxiv.org/pdf/2312.15816.pdf)       |    [Link](https://github.com/xiongsiheng/TEILP)    |
|   2023   |         **CENET**         |              **Temporal Knowledge Graph Reasoning with Historical Contrastive Learnings**              |   AAAI    | Extrapolation |                        [Link](https://arxiv.org/pdf/2211.10904.pdf)                        |                                    -                                    |
|   2022   |         **GHT**         |              **Graph Hawkes Transformer for Extrapolated Reasoning on Temporal Knowledge Graphs**              |   ACL    | Extrapolation |                        [Link](https://aclanthology.org/2022.emnlp-main.507.pdf)                        |                                    -                                    |
|   2022   |        **DA-Net**         |           **DA-Net: Distributed Attention Network for Temporal Knowledge Graph Reasonings**            |   CIKM    | Extrapolation |                 [Link](https://dl.acm.org/doi/pdf/10.1145/3511808.3557280)                 |                                    -                                    |
|   2022   |       **MetaTKGR**        |        **Learning to Sample and Aggregate: Few-shot Reasoning over Temporal Knowledge Graphs**         |   arXiv   | Extrapolation |                        [Link](https://arxiv.org/pdf/2210.08654.pdf)                        |                                    -                                    |
|   2022   |         **rGalT**         |       **Modeling Precursors for Temporal Knowledge Graph Reasoning via Auto-encoder Structure**        |   IJCAI   | Extrapolation |                  [Link](https://www.ijcai.org/proceedings/2022/0284.pdf)                   |                                    -                                    |
|   2022   |         **FILT**          |      **Few-Shot Inductive Learning on Temporal Knowledge Graphs using Concept-Aware Information**      |   AKBC    | Interpolation |                        [Link](https://arxiv.org/pdf/2211.08169.pdf)                        |                                    -                                    |
|   2022   |       **TKGC-AGP**        |          **Temporal Knowledge Graph Completion with Approximated Gaussian Process Embedding**          |  COLING   | Interpolation |                   [Link](https://aclanthology.org/2022.coling-1.416.pdf)                   |                                    -                                    |
|   2022   |        **Tlogic**         |       **TLogic: Temporal Logical Rules for Explainable Link Forecasting on Temporal Knowledge**        |   AAAI    | Extrapolation |               [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20330)               |              [Link](https://github.com/liu-yushan/TLogic)               |
|   2022   |         **DKGE**          |                           **Efficiently embedding dynamic knowledge graphs**                           |    KBS    | Interpolation |                        [Link](https://arxiv.org/pdf/1910.06708.pdf)                        |                 [Link](https://github.com/lienwc/DKGE/)                 |
|   2022   |          **CEN**          |            **Complex Evolutional Pattern Learning for Temporal Knowledge Graph Reasoning**             |    ACL    | Extrapolation |                    [Link](https://aclanthology.org/2022.acl-short.32/)                     |                 [Link](https://github.com/lee-zix/cen)                  |
|   2021   |         **TPRec**         |                                       **Time-aware Path Reasoning on Knowledge Graph for Recommendations**                                       |   TOIS    | Extrapolation |          [Link](https://arxiv.org/pdf/2108.02634.pdf)          |                                    -                                    |
|   2021   |           **-**           |             **Spatial-Temporal Attention Network for Temporal Knowledge Graph Completion**             |  DASFAA   | Interpolation |          [Link](https://link.springer.com/chapter/10.1007%2F978-3-030-73194-6_15)          |                                    -                                    |
|   2021   |          **TIE**          |                             **TIE: A Framework for Embedding-based Incremental Temporal Knowledge Graph Completion**                             |   SIGIR   | Interpolation |          [Link](https://arxiv.org/pdf/2104.08419.pdf)          |  [Link](https://github.com/JiapengWu/Time-Aware-Incremental-Embedding)  |
|   2021   |         **TeLM**          | **Temporal Knowledge Graph Completion using a Linear Temporal Regularizer and Multivector Embeddings** |   NAACL   | Interpolation |               [Link](https://www.aclweb.org/anthology/2021.naacl-main.202/)                |               [Link](https://github.com/soledad921/TeLM)                |
|   2021   |     **RTFE**      |                 **RTFE: A Recursive Temporal Fact Embedding Framework for Temporal Knowledge Graph Completion**                  |         NAACL          | Interpolation |               [Link](https://www.aclweb.org/anthology/2021.naacl-main.451/)                |                                   -                                    |
| 2021     | **TANGO**      | **Learning Neural Ordinary Equations for Forecasting Future Links on Temporal Knowledge Graphs**                                              | EMNLP           | Extrapolation    | [Link](https://aclanthology.org/2021.emnlp-main.658.pdf)                                                                                    | [Link](https://github.com/TemporalKGTeam/TANGO)                                   |
|   2020   |        **DyERNIE**        |                     **DyERNIE: Dynamic Evolution of Riemannian Manifold Embeddings for Temporal Knowledge Graph Completion**                     |   EMNLP   | Interpolation | [Link](https://www.aclweb.org/anthology/2020.emnlp-main.593/)  |                                    -                                    |
|   2020   |           **-**           |               **Explainable Link Prediction for Emerging Entities in Knowledge Graphs**                |   ISWC    | Interpolation |          [Link](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_3)           | [Link](https://github.com/kingsaint/InductiveExplainableLinkPrediction) |
|   2020   |         **TDGNN**         |            **Continuous-Time Link Prediction via Temporal Dependent Graph Neural Network**             |    WWW    | Extrapolation |                   [Link](https://dl.acm.org/doi/10.1145/3366423.3380073)                   |               [Link](https://github.com/Leo-Q-316/TDGNN)                |
|   2020   |           **-**           |      **Evaluating the Calibration of Knowledge Graph Embeddings for Trustworthy Link Prediction**      |   EMNLP   | Extrapolation |               [Link](https://www.aclweb.org/anthology/2020.emnlp-main.667/)                |                                    -                                    |
|   2020   |         **ATiSE**         |            **Temporal Knowledge Graph Completion Based on Time Series Gaussian Embedding**             |   ISWC    | Interpolation |                        [Link](https://arxiv.org/pdf/1911.07893.pdf)                        |               [Link](https://github.com/soledad921/ATISE)               |
|   2020   | **Diachronic embeddings** |                                         **Diachronic Embedding for Temporal Knowledge Graph Completion**                                         |   AAAI    | Interpolation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/5815)  |             [Link](https://github.com/BorealisAI/DE-SimplE)             |
|   2020   |         **TeRo**          |                 **TeRo: A Time-aware Knowledge Graph Embedding via Temporal Rotation**                 |  COLING   | Interpolation |               [Link](https://www.aclweb.org/anthology/2020.coling-main.139/)               |               [Link](https://github.com/soledad921/ATISE)               |
|   2019   |         **DyRep**         |                        **DyRep: Learning Representations over Dynamic Graphs**                         |   ICLR    | Extrapolation |                      [Link](https://openreview.net/pdf?id=HyePrhR5KX)                      |                                    -                                    |
|   2018   |         **HyTE**          |                 **HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding**                  |   EMNLP   | Interpolation |           [Link](https://aclanthology.org/D18-1225/?ref=https://githubhelp.com)            |                                    -                                    |
|   2018   |    **ChronoTranslate**    |                           **Temporal reasoning over event knowledge graphs**                           |   KBCOM   | Interpolation |  [Link](https://dsr.cise.ufl.edu/wp-content/uploads/2018/01/TemporalReasoning_KBCOM.pdf)   |                                    -                                    |

[Back](#bookmarks-)

## Multi-Modal Knowledge Graph Reasoning <span id="multi-modal-knowledge-graph-reasoning-"></span>
## Transformer-agnostic Model <span id="transformer-agnostic-models-"></span>
| **Year** |     **Model**     |                                                              **Title**                                                             | **Venue**  |                                                    **Paper**                                                     |                         **Code**                         |
|:--------:|:-----------------:|:----------------------------------------------------------------------------------------------------------------------------------:|:---------:|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------:|
| 2023     | **--**         | **Multimodal Biological Knowledge Graph Completion via Triple Co-attention Mechanism**                                          | ICDE      |                                    [Link](-)                                   |-                               |
| 2022     | **MMKGR**         | **MMKGR: Multi-hop Multi-modal Knowledge Graph Reasoning**                                          | arXiv      |                                 [Link](https://arxiv.org/pdf/2209.01416.pdf)                                   |-                                        |
| 2022 | **MMKRL**    | **MMKRL: A robust embedding approach for multi-modal knowledge graph representation learning**     | Applied Intelligence |  [Link](https://link.springer.com/article/10.1007/s10489-021-02693-9)                                                                                                                                                            | - |
| 2022 | **MKGRL-MS** | **Multi-modal knowledge graphs representation learning via multi-headed self-attention**           | Information Fusion   | [Link](https://reader.elsevier.com/reader/sd/pii/S1566253522000689?token=BA1BC39D1F5D417A6DE735FD502EDA556302D37D34B7EAC817593413590B9F118F77E5BF89AB0AF65F0EB175E8431FA3&originRegion=us-east-1&originCreation=20221126040616) | - |
| 2022 | **ZSMMKG**   | **Improving Zero-Shot Phrase Grounding via Reasoning on External Knowledge and Spatial Relations** | AAAI                 |  [Link](https://ojs.aaai.org/index.php/AAAI/article/view/20123)                                                                                                                                                                    | - |
| 2022     | **OTKGE**         | **OTKGE: Multi-modal Knowledge Graph Embeddings via Optimal Transport**                                          | NeurIPS      |                                 [Link](https://openreview.net/pdf?id=gbXqMdxsZIP)                                   | [Link](https://github.com/Lion-ZS/OTKGE)                                            |
| 2022     | **MM-RNS**         | **Relation-enhanced Negative Sampling for Multimodal Knowledge Graph Completion**                                          | MM      |                                   [Link](https://dl.acm.org/doi/pdf/10.1145/3503161.3548388)                                   | -                                             |
| 2022     | **CKGC**         | **Cross-modal Knowledge Graph Contrastive Learning for Machine Learning Method Recommendation**                                          | MM      |                                  [Link](https://github.com/ZihengZZH/awesome-multimodal-knowledge-graph/blob/master/paper/cao2022cross.pdf)                                   | -                                             |
| 2022     | **MoSE**         | **MoSE: Modality Split and Ensemble for Multimodal Knowledge Graph Completion**                                          | EMNLP      |                              [Link](https://arxiv.org/pdf/2210.08821.pdf)                                   |[Link](https://github.com/OreOZhao/MoSE4MKGC)                                                  |
| 2022     | **MCLEA**         | **Multi-modal Contrastive Representation Learning for Entity Alignment**                                          | COLING      |                              [Link](https://aclanthology.org/2022.coling-1.227.pdf)                                   | [Link](https://github.com/lzxlin/MCLEA)                                                |
| 2021     | **-**         | **Explicit Knowledge Incorporation for Visual Reasoning**                                          | CVPR      |                                  [Link](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Explicit_Knowledge_Incorporation_for_Visual_Reasoning_CVPR_2021_paper.pdf)                                   | -                                                     |
| 2021     | **EVA**         | **Visual Pivoting for (Unsupervised) Entity Alignment**                                          | AAAI      |                                 [Link](https://arxiv.org/pdf/2009.13603.pdf)                                   | [Link](http://cogcomp.org/page/publication_view/927)                                                      |
| 2021     | **HMEA**          | **Multi-modal Entity Alignment in Hyperbolic Space**                                                                               | arXiv     |                               [Link](https://arxiv.org/pdf/2106.03619.pdf)                                   | -                                                        |
| 2021     | **RSME**         | **Is Visual Context Really Helpful for Knowledge Graph? A Representation Learning Perspective**                                          | MM      |                                  [Link](https://dl.acm.org/doi/abs/10.1145/3474085.3475470)                                   | [Link](https://github.com/wangmengsd/RSME)                                                     |
| 2020     | **MKGAT**         | **Multi-modal Knowledge Graphs for Recommender Systems**                                                                           | CIKM      |                         [Link](https://zheng-kai.com/paper/cikm_2020_sun.pdf)                               | -                                                        |
| 2020     | **Mucko**         | **Mucko: Multi-Layer Cross-Modal Knowledge Reasoning for Fact-based Visual Question Answering**                                    | IJCAI     |                      [Link](https://www.ijcai.org/proceedings/2020/0153.pdf)                              | [Link](https://github.com/astro-zihao/mucko)             |
| 2020     | **GRUC**          | **Cross-modal Knowledge Reasoning for Knowledge-based Visual Question Answering**                                                  | PR        |                               [Link](https://arxiv.org/pdf/2009.00145.pdf)                                   | -                                                        |
| 2020     | **-**             | **Do Dogs have Whiskers? A New Knowledge Base of hasPart Relations**                                                               | arXiv     |                                [Link](https://arxiv.org/pdf/2006.07510.pdf)                                   | -                                                        |
| 2020     | **MMEA**          | **MMEA: Entity Alignment for Multi-modal Knowledge Graph**                                                                         | ICKSEM    |               [Link](http://home.ustc.edu.cn/~liyichen/assets/files/LiyiChen_KSEM20.pdf)                    | -                                                        |
| 2020     | **MRCGN**         | **End-to-End Entity Classification on Multimodal Knowledge Graphs**                                                                | arXiv     |                                [Link](https://arxiv.org/pdf/2003.12383.pdf)                                   | [Link](https://gitlab.com/wxwilcke/mrgcn)                |
| 2019     | **GQA**           | **GQA: A New Dataset for Real-World Visual Reasoning and Compositional Question Answering**                                        | CVPR      |                                 [Link](https://arxiv.org/pdf/1902.09506.pdf)                                   | [Link](https://cs.stanford.edu/people/dorarad/gqa/)      |
| 2019     | **VSUA**           | **Aligning Linguistic Words and Visual Semantic Units for Image Captioning**                                        | MM      |                               [Link](https://arxiv.org/pdf/1908.02127.pdf)                                   | [Link](https://github.com/ltguo19/VSUA-Captioning)      |
| 2019     | **KVQA**          | **KVQA: Knowledge-Aware Visual Question Answering**                                                                             | AAAI      |                    [Link](https://ojs.aaai.org/index.php/AAAI/article/view/4915)                           | [Link](http://malllabiisc.github.io/resources/kvqa/)     |
| 2019     | **-**             | **Answering Visual-Relational Queries in Web-Extracted Knowledge Graphs**                                                          | AKBC      |                              [Link](https://arxiv.org/pdf/1709.02314.pdf)                                   | [Link](https://github.com/nle-ml/mmkb.git)               |
| 2019     | **-**             | **MMKG: Multi-Modal Knowledge Graphs**                                                                                             | ESWC      |                               [Link](https://arxiv.org/pdf/1903.05485.pdf)                                   | [Link](https://github.com/nle-ml/mmkb)                   |
| 2019     | **MKRL**          | **Knowledge representation learning with entity descriptions, hierarchical types, and textual relations**                                                                                | Information Processing & Management     |                               [Link](https://www.sciencedirect.com/science/article/abs/pii/S0306457318303698)                                   |-         |
| 2019     | **TransAE**          | **Multimodal Data Enhanced Representation Learning for Knowledge Graphs**                                                                                | ACL     |                              [Link](https://ieeexplore.ieee.org/abstract/document/8852079)                                   |[Link](https://github.com/UKPLab/)           |
| 2018     | **MKBE**          | **Embedding Multimodal Relational Data for Knowledge Base Completion**                                                             | ACL       |                          [Link](https://aclanthology.org/D18-1359.pdf)                                   | [Link](https://github.com/pouyapez/mkbe)                 |
| 2018     | **MTRL**             | **A multimodal translation-based approach for knowledge graph representation learning**                                            | SEM      |                               [Link](https://aclanthology.org/S18-2027.pdf)                                   | [Link](https://github.com/UKPLab/starsem18-multimodalKB) |
| 2018     | **KR-AMD**          | **Representation learning of knowledge graphs with entity attributes and multimedia descriptions**                                                                                | BigMM     |                                  [Link](https://ieeexplore-ieee-org-s.libyc.nudt.edu.cn/stamp/stamp.jsp?tp=&arnumber=8499179)                                   |-          |
| 2017     | **KB-VQA**        | **Explicit Knowledge-based Reasoning for Visual Question Answering**                                                               | IJCAI     |                               [Link](https://arxiv.org/pdf/1511.02570.pdf)                                   | -                                                        |
| 2017     | **KBLRN**         | **KBLRN: End-to-End Learning of Knowledge Base Representations with Latent, Relational, and Numerical Features**                   | AUAI      |                       [Link](http://www.auai.org/uai2018/proceedings/papers/149.pdf)                          | -                                                        |
| 2016     | **IKRL**          | **Image-embodied Knowledge Representation Learning**                                                                               | IJCAI     |                              [Link](https://arxiv.org/pdf/1609.07028.pdf)                                   | [Link](https://github.com/thunlp/IKRL)                   |
| 2016     | **DKRL**          | **Representation Learning of Knowledge Graphs with Entity Descriptions**                                                            | AAAI      |                  [Link](https://ojs.aaai.org/index.php/AAAI/article/view/10329/10188)                       | [Link](https://github.com/xrb92/DKRL)                    |
| 2016     | **CKE**           | **Collaborative Knowledge Base Embedding for Recommender Systems**                                                  | SIGKDD    | [Link](https://www.kdd.org/kdd2016/subtopic/view/collaborative-knowledge-base-embedding-for-recommender-systems)  | -                                                         |     
 

[Back](#bookmarks-)

## Transformer-based Model <span id="transformer-based-models-"></span>
| **Year** |     **Model**     |                                                              **Title**                                                             | **Venue** |                                                    **Paper**                                                     |                         **Code**                         |
|:--------:|:-----------------:|:----------------------------------------------------------------------------------------------------------------------------------:|:---------:|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------:|
| 2023 |  **AIR**  |        **AspectMMKG: A Multi-modal Knowledge Graph with Aspect-aware Entities**        |           CIKM          |                     [Link](https://arxiv.org/abs/2308.04992)                    | [Link](https://github.com/thezjd/aspectmmkg) |
| 2023 | **SGMPT** | **Structure Guided Multi-modal Pre-trained Transformer for Knowledge Graph Reasoning** |          ArXiv          |                     [Link](https://arxiv.org/abs/2307.03591)                    |                   [Link](-)                  |
|   2023   |      **IMF**      | **IMF: Interactive Multimodal Fusion Model for Link Prediction**                                          |    WWW    |                                    [Link](https://arxiv.org/pdf/2303.10816.pdf)                                   | [Link](https://github.com/HestiaSky/IMF-Pytorch)                              |
|   2022   | **DRAGON**         | **Deep Bidirectional Language-Knowledge Graph Pretraining**                                          | NeurIPS      |                              [Link](https://arxiv.org/pdf/2210.09338.pdf)                                 |[Link](https://github.com/michiyasunaga/dragon)                                      |
| 2022     | **MuKEA**         | **MuKEA: Multimodal Knowledge Extraction and Accumulation for Knowledge-based Visual Question Answering**                                          | CVPR      |                                  [Link](https://openaccess.thecvf.com/content/CVPR2022/papers/Ding_MuKEA_Multimodal_Knowledge_Extraction_and_Accumulation_for_Knowledge-Based_Visual_Question_CVPR_2022_paper.pdf)                                   | [Link](https://github.com/AndersonStra/MuKEA)                                              |
| 2022     | **MSNEA**         | **Multi-modal Siamese Network for Entity Alignment**                                          | KDD      |                           [Link](https://dl.acm.org/doi/abs/10.1145/3534678.3539244)                                   | [Link](https://github.com/liyichen-cly/MSNEA)                                              |
| 2022     | **HRGAT**         | **Hyper-node Relational Graph Attention Network for Multi-modal Knowledge Graph Completion**                                          | ACM Transactions on Multimedia Computing, Communications, and Applications      |                              [Link](https://dl.acm.org/doi/pdf/10.1145/3545573)                                   | [Link](https://github.com/broliang/HRGAT)                                                  |
|   2022   |     **KPGT**      | **KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction**                                          |    KDD    |                                    [Link](https://arxiv.org/pdf/2206.03364.pdf)                                   | [Link](https://github.com/lihan97/KPGT)                              |
|   2022   | **MKGformer**         | **Hybrid Transformer with Multi-level Fusion for Multimodal Knowledge Graph Completion**                                          | SIGIR      |                              [Link](https://arxiv.org/pdf/2205.02357.pdf)                                   | [Link](https://github.com/zjunlp/MKGformer)                                              |
|   2022   |      **MarT**      | **Multimodal Analogical Reasoning over Knowledge Graphs**                                          |   ICLR    |                                    [Link](https://arxiv.org/pdf/2210.00312.pdf)                                   |[Link](https://github.com/zjunlp/MKG_Analogy)                                |
|   2022   | **Knowledge-CLIP** | **Contrastive Language-Image Pre-Training with Knowledge Graphs**                                          |  NeurIPS  |                                    [Link](https://openreview.net/pdf?id=4T3kbrzfeR)                                   |-                                        |
|   2022   |      **TMEG**      | **Modeling Temporal-Modal Entity Graph for Procedural Multimodal Machine Comprehension**                                          |    ACL    |                              [Link](https://arxiv.org/pdf/2204.02566.pdf)                                   | -                                               |
|   2022   |     **VBKGC**      | **Knowledge Graph Completion with Pre-trained Multimodal Transformer and Twins Negative Sampling**                                          |    KDD    |                              [Link](https://arxiv.org/pdf/2209.07084)                                   |-                                                 |
|   2021   |     **Krisp**      | **Krisp: Integrating implicit and symbolic knowledge for open domain knowledge-based vqa**                                          |   CVPR    |                             [Link](https://arxiv.org/pdf/2012.11014.pdf)                                   | -                                                        |


[Back](#bookmarks-)


# Useful Libararies <span id="useful-libararies-"></span>
- LibKGE [code](https://github.com/uma-pi1/kge)
- OpenKE [code](https://github.com/thunlp/OpenKE)
- PyKEEN [code](https://github.com/pykeen/pykeen)
- Pykg2vec [code](https://github.com/Sujit-O/pykg2vec)
- GraphVite [code](https://github.com/DeepGraphLearning/graphvite)
- Scikit-KGE [code](https://github.com/mnick/scikit-kge)
- AmpliGraph [code](https://github.com/Accenture/AmpliGraph)
- Awesome-LLM-KG [code](https://github.com/RManLuo/Awesome-LLM-KG)
- KG-Tutorials [code](https://github.com/heathersherry/Knowledge-Graph-Tutorials-and-Papers)

[Back](#bookmarks-)
