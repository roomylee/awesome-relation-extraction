# Awesome Relation Extraction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of resources dedicated to Relation Extraction, inspired by [awesome-nlp](https://github.com/keon/awesome-nlp) and [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision).


## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [Supervised Approaches](#supervised-approaches)
	* [Distant Supervision Approaches](#distant-supervision-approaches)
* [Datasets](#datasets)
* [Lectures](#lectures)
* [Systems](systems)


## Research Trends and Surveys
* [NLP progress: Relationship Extraction](https://nlpprogress.com/english/relationship_extraction.html)
* [A Survey of Deep Learning Methods for Relation Extraction](https://arxiv.org/abs/1705.03645) (Kumar, 2017)
* [A Survey on Relation Extraction](http://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction-Slides.pdf) (Bach and Badaskar, 2017)
* [Relation Extraction: A Survey](https://arxiv.org/abs/1712.05191) (Pawar et al., 2017)
* [A Review on Entity Relation Extraction](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8269916) (Zhang et al., 2017)
* [A Review of Relation Extraction](http://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction.pdf) (Bach et al., 2007)
* [Review of Relation Extraction Methods: What is New Out There?](http://pers-www.wlv.ac.uk/~in0988/documents/aist-final.pdf) (Konstantinova et al., 2014)
* [100 Best Github: Relation Extraction](http://meta-guide.com/software-meta-guide/100-best-github-relation-extraction)


## Papers

### Supervised Approaches
#### CNN-based Models
* Convolution Neural Network for Relation Extraction [[paper]](https://link.springer.com/chapter/10.1007/978-3-642-53917-6_21) [[review]](/relation_extraction/Relation_Neural_Network_for_Relation_Extraction.md)
	* ChunYang Liu, WenBo Sun, WenHan Chao and WanXiang Che
	* ADMA 2013
* Relation Classification via Convolutional Deep Neural Network [[paper]](http://www.aclweb.org/anthology/C14-1220) [[review]](/relation_extraction/Relation_Classification_via_Convolutional_Deep_Neural_Network.md)
	* Daojian Zeng, Kang Liu, Siwei Lai, Guangyou Zhou and Jun Zhao
	* COLING 2014
* Relation Extraction: Perspective from Convolutional Neural Networks [[paper]](http://www.cs.nyu.edu/~thien/pubs/vector15.pdf) [[review]](/relation_extraction/Relation_Extraction-Perspective_from_Convolutional_Neural_Networks.md)
	* Thien Huu Nguyen and Ralph Grishman
	* NAACL 2015
* Classifying Relations by Ranking with Convolutional Neural Networks [[paper]](https://arxiv.org/abs/1504.06580)
	* Cicero Nogueira dos Santos, Bing Xiang and Bowen Zhou
	* ACL 2015
* Attention-Based Convolutional Neural Network for Semantic Relation Extraction [[paper]](http://www.aclweb.org/anthology/C16-1238)
	* Yatian Shen and Xuanjing Huang
	* COLING 2016
* Relation Classification via Multi-Level Attention CNNs [[paper]](http://aclweb.org/anthology/P16-1123)
	* Linlin Wang, Zhu Cao, Gerard de Melo and Zhiyuan Liu
	* ACL 2016
* MIT at SemEval-2017 Task 10: Relation Extraction with Convolutional Neural Networks [[paper]](https://aclanthology.info/pdf/S/S17/S17-2171.pdf)
	* Ji Young Lee, Franck Dernoncourt and Peter Szolovits
	* SemEval 2017

#### RNN-based Models
* Bidirectional Long Short-Term Memory Networks for Relation Classification [[paper]](http://www.aclweb.org/anthology/Y15-1009)
	* Shu Zhang, Dequan Zheng, Xinchen Hu and Ming Yang
	* PACLIC 2015
* End-to-End Relation Extraction using LSTMs on Sequences and Tree Structure [[paper]](https://arxiv.org/abs/1601.00770)
	* Makoto Miwa and Mohit Bansal
	* ACL 2016
* Attention-Based Bidirectional Long Short-Term Memory Networks for Relation Classification [[paper]](http://anthology.aclweb.org/P16-2034)
	* Peng Zhou, Wei Shi, Jun Tian, Zhenyu Qi, Bingchen Li, Hongwei Hao and Bo Xu
	* ACL 2016
* Semantic Relation Classification via Hierarchical Recurrent Neural Network with Attention [[paper]](http://www.aclweb.org/anthology/C16-1119)
	* Minguang Xiao and Cong Liu
	* COLING 2016
* Semantic Relation Classification via Bidirectional LSTM Networks with Entity-aware Attention using Latent Entity Typing [[paper]]()
	* Joohong Lee, Sangwoo Seo and Yong Suk Choi
	* summitted to SDM 2018

#### Etc.



### Distant Supervision Approaches
* Distant supervision for relation extraction without labeled data [[paper]](https://web.stanford.edu/~jurafsky/mintz.pdf) [[review]](/relation_extraction/Distant_supervision_for_relation_extraction_without_labeled_data.md)
	* Mike Mintz, Steven Bills, Rion Snow and Dan Jurafsky
	* ACL 2009
* Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks [[paper]](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP203.pdf) [[review]](/relation_extraction/Distant_Supervision_for_Relation_Extraction_via_Piecewise_Convolutional_Neural_Networks.md)
	* Daojian Zeng, Kang Liu, Yubo Chen and Jun Zhao
	* EMNLP 2015
* Relation Extraction with Multi-instance Multi-label Convolutional Neural Networks [[paper]](https://pdfs.semanticscholar.org/8731/369a707046f3f8dd463d1fd107de31d40a24.pdf) [[review]](/relation_extraction/Relation_Extraction_with_Multi-instance_Multi-label_Convolutional_Neural_Networks.md)
	* Xiaotian Jiang, Quan Wang, Peng Li, Bin Wang
	* COLING 2016
* Incorporating Relation Paths in Neural Relation Extraction [[paper]](http://aclweb.org/anthology/D17-1186) [[review]](/relation_extraction/Incorporating_Relation_Paths_in_Neural_Relation_Extraction.md)
	* Wenyuan Zeng, Yankai Lin, Zhiyuan Liu and Maosong Sun
	* EMNLP 2017
* Neural Relation Extraction with Selective Attention over Instances [[paper]](http://www.aclweb.org/anthology/P16-1200)
	* Yankai Lin, Shiqi Shen, Zhiyuan Liu, Huanbo Luan and Maosong Sun
	* ACL 2017
* Learning local and global contexts using a convolutional recurrent network model for relation classification in biomedical text [[paper]](http://www.aclweb.org/anthology/K17-1032) [[code]](https://github.com/desh2608/crnn-relation-classification)
	* Desh Raj, Sunil Kumar Sahu and Ashish Anan
	* CoNLL 2017


### Miscellaneous
* A neural joint model for entity and relation extraction from biomedical text[[paper]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1609-9)
	* Fei Li, Meishan Zhang, Guohong Fu and Donghong Ji
	* BMC bioinformatics 2017
* End-to-End Neural Relation Extraction with Global Optimization [[paper]](http://aclweb.org/anthology/D17-1182)
	* Meishan Zhang, Yue Zhang and Guohong Fu
	* EMNLP 2017
* Adversarial Training for Relation Extraction [[paper]](https://people.eecs.berkeley.edu/~russell/papers/emnlp17-relation.pdf)
	* Yi Wu, David Bamman and Stuart Russell
	* EMNLP 2017
* Joint Extraction of Entities and Relations Using Reinforcement Learning and Deep Learning [[paper]](https://www.hindawi.com/journals/cin/2017/7643065/)
	* Yuntian Feng, Hongjun Zhang, Wenning Hao, and Gang Chen
	* Journal of Computational Intelligence and Neuroscience 2017
* Jointly Extracting Relations with Class Ties via Effective Deep Ranking [[paper]](http://aclweb.org/anthology/P17-1166)
	* Hai Ye, Wenhan Chao, Zhunchen Luo and Zhoujun Li
	* ACL 2017


[Back to Top](#contents)


## Datasets
* SemEval-2010 Task 8 [[paper]](http://www.aclweb.org/anthology/S10-1006) [[download]](https://docs.google.com/leaf?id=0B_jQiLugGTAkMDQ5ZjZiMTUtMzQ1Yy00YWNmLWJlZDYtOWY1ZDMwY2U4YjFk&sort=name&layout=list&num=50)
	* Multi-Way Classification of Semantic Relations Between Pairs of Nominals
* New York Times (NYT) Corpus [[paper]](http://www.riedelcastro.org//publications/papers/riedel10modeling.pdf) [[download]](https://catalog.ldc.upenn.edu/LDC2008T19)
	* This dataset was generated by aligning *Freebase* relations with the NYT corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.

[Back to Top](#contents)


## Lectures
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


## Contributing
Please feel free to make *[pull requests](https://github.com/roomylee/awesome-relation-extraction/pulls)*.
