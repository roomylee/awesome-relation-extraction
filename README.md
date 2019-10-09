# Awesome Relation Extraction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![awesome_re](https://user-images.githubusercontent.com/15166794/47858006-62aa7400-de2e-11e8-82d3-165f66aaaec4.png)

A curated list of awesome resources dedicated to Relation Extraction, inspired by [awesome-nlp](https://github.com/keon/awesome-nlp) and [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision).

**Contributing**: Please feel free to make *[pull requests](https://github.com/roomylee/awesome-relation-extraction/pulls)*.

## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [Supervised Approaches](#supervised-approaches)
	* [Distant Supervision Approaches](#distant-supervision-approaches)
	* [Language Models](#language-models)
* [Datasets](#datasets)
* [Videos and Lectures](#videos-and-lectures)
* [Systems](#systems)


## Research Trends and Surveys
* [NLP progress: Relationship Extraction](https://nlpprogress.com/english/relationship_extraction.html)
* [A Survey of Deep Learning Methods for Relation Extraction](https://arxiv.org/abs/1705.03645) (Kumar, 2017)
* [A Survey on Relation Extraction](https://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction.pdf) (Bach and Badaskar, 2017)
* [Relation Extraction: A Survey](https://arxiv.org/abs/1712.05191) (Pawar et al., 2017)
* [A Review on Entity Relation Extraction](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8269916) (Zhang et al., 2017)
* [Review of Relation Extraction Methods: What is New Out There?](http://pers-www.wlv.ac.uk/~in0988/documents/aist-final.pdf) (Konstantinova et al., 2014)
* [100 Best Github: Relation Extraction](http://meta-guide.com/software-meta-guide/100-best-github-relation-extraction)


## Papers

### Supervised Approaches
#### CNN-based Models
* Convolution Neural Network for Relation Extraction [[paper]](https://link.springer.com/chapter/10.1007/978-3-642-53917-6_21) [[code]](https://github.com/roomylee/cnn-relation-extraction) [[review]](/relation_extraction/Relation_Neural_Network_for_Relation_Extraction.md)
	* ChunYang Liu, WenBo Sun, WenHan Chao and WanXiang Che
	* ADMA 2013
* Relation Classification via Convolutional Deep Neural Network [[paper]](http://www.aclweb.org/anthology/C14-1220) [[code]](https://github.com/roomylee/cnn-relation-extraction) [[review]](/relation_extraction/Relation_Classification_via_Convolutional_Deep_Neural_Network.md)
	* Daojian Zeng, Kang Liu, Siwei Lai, Guangyou Zhou and Jun Zhao
	* COLING 2014
* Relation Extraction: Perspective from Convolutional Neural Networks [[paper]](http://www.cs.nyu.edu/~thien/pubs/vector15.pdf) [[code]](https://github.com/roomylee/cnn-relation-extraction) [[review]](/relation_extraction/Relation_Extraction-Perspective_from_Convolutional_Neural_Networks.md)
	* Thien Huu Nguyen and Ralph Grishman
	* NAACL 2015
* Classifying Relations by Ranking with Convolutional Neural Networks [[paper]](https://arxiv.org/abs/1504.06580) [[code]](https://github.com/pratapbhanu/CRCNN)
	* Cicero Nogueira dos Santos, Bing Xiang and Bowen Zhou
	* ACL 2015
* Attention-Based Convolutional Neural Network for Semantic Relation Extraction [[paper]](http://www.aclweb.org/anthology/C16-1238)
	* Yatian Shen and Xuanjing Huang
	* COLING 2016
* Relation Classification via Multi-Level Attention CNNs [[paper]](http://aclweb.org/anthology/P16-1123) [[code]](https://github.com/lawlietAi/relation-classification-via-attention-model)
	* Linlin Wang, Zhu Cao, Gerard de Melo and Zhiyuan Liu
	* ACL 2016
* MIT at SemEval-2017 Task 10: Relation Extraction with Convolutional Neural Networks [[paper]](https://aclanthology.info/pdf/S/S17/S17-2171.pdf)
	* Ji Young Lee, Franck Dernoncourt and Peter Szolovits
	* SemEval 2017

#### RNN-based Models
* Relation Classification via Recurrent Neural Network [[paper]](https://arxiv.org/abs/1508.01006)
	* Dongxu Zhang and Dong Wang
	* arXiv 2015
* Bidirectional Long Short-Term Memory Networks for Relation Classification [[paper]](http://www.aclweb.org/anthology/Y15-1009)
	* Shu Zhang, Dequan Zheng, Xinchen Hu and Ming Yang
	* PACLIC 2015
* End-to-End Relation Extraction using LSTMs on Sequences and Tree Structure [[paper]](https://arxiv.org/abs/1601.00770)
	* Makoto Miwa and Mohit Bansal
	* ACL 2016
* Attention-Based Bidirectional Long Short-Term Memory Networks for Relation Classification [[paper]](http://anthology.aclweb.org/P16-2034) [[code]](https://github.com/SeoSangwoo/Attention-Based-BiLSTM-relation-extraction)
	* Peng Zhou, Wei Shi, Jun Tian, Zhenyu Qi, Bingchen Li, Hongwei Hao and Bo Xu
	* ACL 2016
* Semantic Relation Classification via Hierarchical Recurrent Neural Network with Attention [[paper]](http://www.aclweb.org/anthology/C16-1119)
	* Minguang Xiao and Cong Liu
	* COLING 2016
* Semantic Relation Classification via Bidirectional LSTM Networks with Entity-aware Attention using Latent Entity Typing [[paper]](https://arxiv.org/abs/1901.08163) [[code]](https://github.com/roomylee/entity-aware-relation-classification)
	* Joohong Lee, Sangwoo Seo and Yong Suk Choi
	* arXiv 2019

#### Dependency-based Models
* Semantic Compositionality through Recursive Matrix-Vector Spaces [[paper]](http://aclweb.org/anthology/D12-1110) [[code]](https://github.com/pratapbhanu/MVRNN)
	* Richard Socher, Brody Huval, Christopher D. Manning and Andrew Y. Ng
	* EMNLP-CoNLL 2012
* Factor-based Compositional Embedding Models [[paper]](https://www.cs.cmu.edu/~mgormley/papers/yu+gormley+dredze.nipsw.2014.pdf)
	* Mo Yu, Matthw R. Gormley and Mark Dredze
	* NIPS Workshop on Learning Semantics 2014
* A Dependency-Based Neural Network for Relation Classification [[paper]](http://www.aclweb.org/anthology/P15-2047)
	* Yang Liu, Furu Wei, Sujian Li, Heng Ji, Ming Zhou and Houfeng Wang
	* ACL 2015
* Classifying Relations via Long Short Term Memory Networks along Shortest Dependency Path [[paper]](https://arxiv.org/abs/1508.03720) [[code]](https://github.com/Sshanu/Relation-Classification)
	* Xu Yan, Lili Mou, Ge Li, Yunchuan Chen, Hao Peng and Zhi Jin
	* EMNLP 2015
* Semantic Relation Classification via Convolutional Neural Networks with Simple Negative Sampling [[paper]](https://www.aclweb.org/anthology/D/D15/D15-1062.pdf)
	* Kun Xu, Yansong Feng, Songfang Huang and Dongyan Zhao
	* EMNLP 2015
* Improved Relation Classification by Deep Recurrent Neural Networks with Data Augmentation [[paper]](https://arxiv.org/abs/1601.03651)
	* Yan Xu, Ran Jia, Lili Mou, Ge Li, Yunchuan Chen, Yangyang Lu and Zhi Jin
	* COLING 2016
* Bidirectional Recurrent Convolutional Neural Network for Relation Classification [[paper]](http://www.aclweb.org/anthology/P16-1072)
	* Rui Cai, Xiaodong Zhang and Houfeng Wang
	* ACL 2016
* Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning [[paper]](https://arxiv.org/abs/1808.06738)
	* Tianyi Liu, Xinsong Zhang, Wanhao Zhou, Weijia Jia
	* EMNLP 2018
	


### Distant Supervision Approaches
* Distant supervision for relation extraction without labeled data [[paper]](https://web.stanford.edu/~jurafsky/mintz.pdf) [[review]](/relation_extraction/Distant_supervision_for_relation_extraction_without_labeled_data.md)
	* Mike Mintz, Steven Bills, Rion Snow and Dan Jurafsky
	* ACL 2009
* Knowledge-Based Weak Supervision for Information Extraction of Overlapping Relations [[paper]](http://www.aclweb.org/anthology/P11-1055) [[code]](http://aiweb.cs.washington.edu/ai/raphaelh/mr/)
	* Raphael Hoffmann, Congle Zhang, Xiao Ling, Luke Zettlemoyer and Daniel S. Weld
	* ACL 2011
* Multi-instance Multi-label Learning for Relation Extraction [[paper]](http://www.aclweb.org/anthology/D12-1042) [[code]](https://nlp.stanford.edu/software/mimlre.shtml)
	* Mihai Surdeanu, Julie Tibshirani, Ramesh Nallapati and Christopher D. Manning
	* EMNLP-CoNLL 2012
* Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks [[paper]](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP203.pdf) [[review]](/relation_extraction/Distant_Supervision_for_Relation_Extraction_via_Piecewise_Convolutional_Neural_Networks.md) [[code]](https://github.com/nicolay-r/sentiment-pcnn)
	* Daojian Zeng, Kang Liu, Yubo Chen and Jun Zhao
	* EMNLP 2015
* Relation Extraction with Multi-instance Multi-label Convolutional Neural Networks [[paper]](https://pdfs.semanticscholar.org/8731/369a707046f3f8dd463d1fd107de31d40a24.pdf) [[review]](/relation_extraction/Relation_Extraction_with_Multi-instance_Multi-label_Convolutional_Neural_Networks.md) [[code]](https://github.com/may-/cnn-re-tf)
	* Xiaotian Jiang, Quan Wang, Peng Li, Bin Wang
	* COLING 2016
* Incorporating Relation Paths in Neural Relation Extraction [[paper]](http://aclweb.org/anthology/D17-1186) [[review]](/relation_extraction/Incorporating_Relation_Paths_in_Neural_Relation_Extraction.md)
	* Wenyuan Zeng, Yankai Lin, Zhiyuan Liu and Maosong Sun
	* EMNLP 2017
* Neural Relation Extraction with Selective Attention over Instances [[paper]](http://www.aclweb.org/anthology/P16-1200) [[code]](https://github.com/thunlp/OpenNRE/)
	* Yankai Lin, Shiqi Shen, Zhiyuan Liu, Huanbo Luan and Maosong Sun
	* ACL 2017
* Learning local and global contexts using a convolutional recurrent network model for relation classification in biomedical text [[paper]](http://www.aclweb.org/anthology/K17-1032) [[code]](https://github.com/desh2608/crnn-relation-classification) [[code]](https://github.com/kwonmha/Convolutional-Recurrent-Neural-Networks-for-Relation-Extraction)
	* Desh Raj, Sunil Kumar Sahu and Ashish Anan
	* CoNLL 2017
	
* Hierarchical Relation Extraction with Coarse-to-Fine Grained Attention[[paper]](https://aclweb.org/anthology/D18-1247)[[code]](https://github.com/thunlp/HNRE)
	* Xu Han, Pengfei Yu∗, Zhiyuan Liu, Maosong Sun, Peng Li
	* EMNLP 2018
* RESIDE: Improving Distantly-Supervised Neural Relation Extraction using Side Information [[paper]](http://malllabiisc.github.io/publications/papers/reside_emnlp18.pdf) [[code]](https://github.com/malllabiisc/RESIDE)
	* Shikhar Vashishth, Rishabh Joshi, Sai Suman Prayaga, Chiranjib Bhattacharyya and Partha Talukdar
	* EMNLP 2018
	
	
### Language Models

* Enriching Pre-trained Language Model with Entity Information for Relation Classification [[paper]](https://arxiv.org/pdf/1905.08284.pdf)
    * Shanchan Wu, Yifan He
    * arXiv 2019

### Few-Shot Learning Approaches
* FewRel: A Large-Scale Supervised Few-Shot Relation Classification Dataset with State-of-the-Art Evaluation [[paper]](https://arxiv.org/abs/1810.10147) [[website]](http://zhuhao.me/fewrel) [[code]](https://github.com/ProKil/FewRel)
	* Xu Han, Hao Zhu, Pengfei Yu, Ziyun Wang, Yuan Yao, Zhiyuan Liu, Maosong Sun
	* EMNLP 2018


### Miscellaneous
* Jointly Extracting Relations with Class Ties via Effective Deep Ranking [[paper]](http://aclweb.org/anthology/P17-1166)
	* Hai Ye, Wenhan Chao, Zhunchen Luo and Zhoujun Li
	* ACL 2017
* End-to-End Neural Relation Extraction with Global Optimization [[paper]](http://aclweb.org/anthology/D17-1182)
	* Meishan Zhang, Yue Zhang and Guohong Fu
	* EMNLP 2017
* Adversarial Training for Relation Extraction [[paper]](https://people.eecs.berkeley.edu/~russell/papers/emnlp17-relation.pdf)
	* Yi Wu, David Bamman and Stuart Russell
	* EMNLP 2017
* A neural joint model for entity and relation extraction from biomedical text[[paper]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1609-9)
	* Fei Li, Meishan Zhang, Guohong Fu and Donghong Ji
	* BMC bioinformatics 2017
* Joint Extraction of Entities and Relations Using Reinforcement Learning and Deep Learning [[paper]](https://www.hindawi.com/journals/cin/2017/7643065/)
	* Yuntian Feng, Hongjun Zhang, Wenning Hao, and Gang Chen
	* Journal of Computational Intelligence and Neuroscience 2017

[Back to Top](#contents)


## Datasets
* SemEval-2010 Task 8 [[paper]](http://www.aclweb.org/anthology/S10-1006) [[download]](https://docs.google.com/leaf?id=0B_jQiLugGTAkMDQ5ZjZiMTUtMzQ1Yy00YWNmLWJlZDYtOWY1ZDMwY2U4YjFk&sort=name&layout=list&num=50)
	* Multi-Way Classification of Semantic Relations Between Pairs of Nominals
* New York Times (NYT) Corpus [[paper]](http://www.riedelcastro.org//publications/papers/riedel10modeling.pdf) [[download]](https://catalog.ldc.upenn.edu/LDC2008T19)
	* This dataset was generated by aligning *Freebase* relations with the NYT corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.
* FewRel: Few-Shot Relation Classification Dataset [[paper]](https://arxiv.org/abs/1810.10147) [[Website]](http://zhuhao.me/fewrel)
	* This dataset is a supervised few-shot relation classification dataset. The corpus is Wikipedia and the knowledge base used to annotate the corpus is Wikidata.

For state of the art results check out [nlpprogress.com on relation extraction](https://nlpprogress.com/english/relationship_extraction.html)

[Back to Top](#contents)


## Videos and Lectures
* [Stanford University: CS124](https://web.stanford.edu/class/cs124/), Dan Jurafsky
	* (Video) [Week 5: Relation Extraction and Question](https://www.youtube.com/watch?v=5SUzf6252_0&list=PLaZQkZp6WhWyszpcteV4LFgJ8lQJ5WIxK&ab_channel=FromLanguagestoInformation)
* [Washington University: CSE517](https://courses.cs.washington.edu/courses/cse517/), Luke Zettlemoyer
	* (Slide) [Relation Extraction 1](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtraction.pdf)
	* (Slide) [Relation Extraction 2](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtractionII.pdf)
* [New York University: CSCI-GA.2590](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/), Ralph Grishman
	* (Slide) [Relation Extraction: Rule-based Approaches](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/DependencyPaths.pdf)
* [Michigan University: Coursera](https://ai.umich.edu/portfolio/natural-language-processing/), Dragomir R. Radev
	* (Video) [Lecture 48: Relation Extraction](https://www.youtube.com/watch?v=TbrlRei_0h8&ab_channel=ArtificialIntelligence-AllinOne)
* [Virginia University: CS6501-NLP](http://web.cs.ucla.edu/~kwchang/teaching/NLP16/), Kai-Wei Chang
	* (Slide) [Lecture 24: Relation Extraction](http://web.cs.ucla.edu/~kwchang/teaching/NLP16/slides/24-relation.pdf)


[Back to Top](#contents)


## Systems
* [DeepDive](http://deepdive.stanford.edu/)
* [Stanford Relation Extractor](https://nlp.stanford.edu/software/relationExtractor.html)

[Back to Top](#contents)


## License
[![license](https://camo.githubusercontent.com/60561947585c982aee67ed3e3b25388184cc0aa3/687474703a2f2f6d6972726f72732e6372656174697665636f6d6d6f6e732e6f72672f70726573736b69742f627574746f6e732f38387833312f7376672f63632d7a65726f2e737667)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Joohong Lee](https://roomylee.github.io/) has waived all copyright and related or neighboring rights to this work.
