# Deep Learning for Video Retrieval by Natural Language

Videos are everywhere. Video retrieval, i.e., finding videos that meet the information need of a specific user, is important for a wide range of applications including communication, education, entertainment, business, security etc. Among multiple ways of expressing the information need, a natural-language text is the most intuitive to start a retrieval process. For instance, to find video shots showing ``a person in front of a blackboard talking or writing in a classroom``. Such a query can be submitted easily, by typing or speech recognition, to a video retrieval system. Given a video as a sequence of frames and a query as a sequence of words, a fundamental problem in video retrieval by natural language is ***how to properly associate visual and linguistic information presented in sequential order***.

This page maintains an (incomplete) list of state-of-the-art open-source methods and datasets, with the [TRECVID](https://trecvid.nist.gov/) Ad-hoc Video Search (AVS) benchmark evaluation as the test bed. 

## Open-source methods
* [W2VV, T-MM'18](https://github.com/danieljf24/w2vv)
* [W2VV++, ACMMM'19](https://github.com/li-xirong/w2vvpp)
* [Dual Encoding, CVPR'19](https://github.com/danieljf24/dual_encoding)

## Datasets

* [Datasets for AVS](https://github.com/li-xirong/avs)


## Leaderboard

### TRECVID 2016 AVS

| Method | infAP |
|:-- | ---:|
| Dual Encoding (Dong et al. CVPR'19) | 0.159 |
| W2VV++ (Li et al. MM'19) | 0.151 |
| VSE++ (Faghri et al. BMVC'18, *produced by Li et al. MM'19*)  | 0.123 |  
| VideoStory (Habibian et al. PAMI'16) | 0.087 |
| Markatopoulou et al. ICMR'17 | 0.064 |
| Le et al. TRECVID'16 | 0.054 |
| Markatopoulou et al. TRECVID'16 | 0.051 |
| W2VV (Dong et al. T-MM'18, *produced by Li et al. MM'19*) | 0.050 |


### TRECVID 2017 AVS

| Method | infAP |
|:-- | ---:|
| W2VV++ (Li et al. MM'19) | 0.213 | 
| Dual Encoding (Dong et al. CVPR'19)  | 0.208 |
| Snoek et al. TRECVID'17 | 0.206 |
| Ueki et al. TRECVID'17  | 0.159 |
| VSE++ (Faghri et al. BMVC'18, *produced by Li et al. MM'19*)  | 0.154 |
| VideoStory (Habibian et al. PAMI'17)  | 0.150 |
| Nguyen et al. TRECVID'17 | 0.120 | 
| W2VV (Dong et al. T-MM'18, *produced by Li et al. MM'19*) | 0.081 |

### TRECVID 2018 AVS

| Method | infAP |
|:-- | ---:|
| Dual Encoding (Dong et al. CVPR'19)  | 0.126 |
| Li et al. TRECVID'18 | 0.121 |
| W2VV++ (Li et al. MM'19) | 0.106 | 
| Huang et al. TRECVID'18 | 0.087 |
| Bastan et al. TRECVID'18 | 0.082 |
| VSE++ (Faghri et al. BMVC'18, *produced by Li et al. MM'19*)  | 0.074 |

### TRECVID 2019 AVS

work in progress ...

## References

+ [Bastan et al. TRECVID'18] M. Bastan, X. Shi, J. Gu, Z. Heng, C. Zhuo, D. Sng, and A. Kot. NTU ROSE Lab at TRECVID 2018: Ad-hoc Video Search and Video to Text. TRECVID 2018
+ [Dong et al. CVPR'19] J. Dong, X. Li, C. Xu, S. Ji, Y. He, G. Yang, and X. Wang. Dual Encoding for
Zero-Example Video Retrieval. CVPR 2019
+ [Dong et al. TMM'18] J. Dong, X. Li, and C. Snoek. PredictingVisualFeaturesfromTextfor
Image and Video Caption Retrieval. T-MM 20, 12 (2018), 3377–3388
+ [Faghri et al. BMVC'18] F. Faghri, D. J. Fleet, J. R. Kiros, and S. Fidler. VSE++: Improving Visual-
Semantic Embeddings with Hard Negatives. BMVC 2018
+ [Habibian et al. T-PAMI'17] A. Habibian, T. Mensink, and C. G. M. Snoek. Video2vec Embeddings
Recognize Events When Examples Are Scarce. T-PAMI 39, 10 (2017), 2089–2103
+ [Huang et al. TRECVID'18] P.-Y. Huang, J. Liang, V. Vaibhav, X. Chang, and A. Hauptmann. Informedia@TRECVID 2018: Ad-hoc Video Search with Discrete and Continuous Representations. TRECVID 2018
+ [Le et al. TRECVID'16] D.-D. Le, S.Phan, V.-T. Nguyen, B. Renoust, T. Nguyen, V.-N. Hoang, T. Ngo, M.-T. Tran, Y. Watanabe, M. Klinkigt, et al. NII-HITACHI-UIT at TRECVID 2016. TRECVID 2016
+ [Li et al. MM'19] X. Li, C. Xu, G. Yang, Z. Chen, and J. Dong. W2VV++: Fully Deep Learning for Ad-hoc Video Search, ACMMM 2019
+ [Li et al. TRECVID'18] X. Li, J. Dong, C. Xu, J. Cao, X. Wang, G. Yang. Renmin University of China and Zhejiang Gongshang University at TRECVID 2018: Deep Cross-Modal Embeddings for Video-Text Retrieval. TRECVID 2018
+ [Markatopoulou et al. ICMR'17] F. Markatopoulou, D. Galanopoulos, V. Mezaris, and I. Patras. Query and Keyframe Representations for Ad-hoc Video Search. ICMR 2017
+ [Markatopoulou et al. TRECVID'16] F. Markatopoulou, A.Moumtzidou, D.Galanopoulos, T.Mironidis, V.Kaltsa, A. Ioannidou, S. Symeonidis, K. Avgerinakis, S. Andreadis, et al. ITI-CERTH Participation in TRECVID 2016. TRECVID 2016
+ [Snoek et al. TRECVID'17] C. G. M. Snoek, X. Li, C. Xu, and D. C. Koelma. University of Amsterdam and Renmin University at TRECVID 2017: Searching Video, Detecting Events and Describing Video. TRECVID 2017
