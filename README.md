# Awesome Relation Extraction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of resources dedicated to Relation Extraction, inspired by [awesome-nlp](https://github.com/keon/awesome-nlp) and [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision).


## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [Supervised Approaches](#supervised-approaches)
	* [Distant Supervision Approaches](#distant-supervision-approaches)
* [Datasets](#datasets)
* [Videos and Lectures](#videos-and-lectures)
* [Systems](systems)


## Research Trends and Surveys
* [NLP progress: Relationship Extraction](https://nlpprogress.com/english/relationship_extraction.html)
* [A Survey of Deep Learning Methods for Relation Extraction](https://arxiv.org/abs/1705.03645) (Kumar, 2017)
* [A Survey on Relation Extraction](http://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction-Slides.pdf) (Bach and Badaskar, 2017)
* [Relation Extraction: A Survey](https://arxiv.org/abs/1712.05191) (Pawar et al., 2017)
* [A Review on Entity Relation Extraction](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8269916) (Zhang et al., 2017)
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

	
	

### Distant Supervision Approaches
* **Distant supervision for relation extraction without labeled data** (ACL 2009), M Mintz et al. **[[review]](/relation_extraction/Distant_supervision_for_relation_extraction_without_labeled_data.md)** [[paper]](https://web.stanford.edu/~jurafsky/mintz.pdf)
* **Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks** (EMNLP 2015), D Zeng et al. **[[review]](/relation_extraction/Distant_Supervision_for_Relation_Extraction_via_Piecewise_Convolutional_Neural_Networks.md)** [[paper]](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP203.pdf)
* **Relation Extraction with Multi-instance Multi-label Convolutional Neural Networks** (COLING 2016), X Jiang et al. **[[review]](/relation_extraction/Relation_Extraction_with_Multi-instance_Multi-label_Convolutional_Neural_Networks.md)** [[paper]](https://pdfs.semanticscholar.org/8731/369a707046f3f8dd463d1fd107de31d40a24.pdf)
* **Incorporating Relation Paths in Neural Relation Extraction** (EMNLP 2017), W Zeng et al. **[[review]](/relation_extraction/Incorporating_Relation_Paths_in_Neural_Relation_Extraction.md)** [[paper]](http://aclweb.org/anthology/D17-1186)


### Miscellaneous

* **End-to-End Neural Relation Extraction with Global Optimization** (EMNLP 2017), M Zhang et al. [[paper]](https://pdfs.semanticscholar.org/0359/cde335fadcfe6f3407722c1a8cc620d0fe8c.pdf)
* **Adversarial Training for Relation Extraction** (EMNLP 2017), Y Wu et al. [[paper]](https://people.eecs.berkeley.edu/~russell/papers/emnlp17-relation.pdf)
* **Joint Extraction of Entities and Relations Using Reinforcement Learning and Deep Learning** (Journal of Computational Intelligence and Neuroscience 2017), Y Feng et al. [[paper]](https://www.hindawi.com/journals/cin/2017/7643065/)
* **A simple neural network module for relational reasoning** (arXiv 2017), A Santoro et al. [[paper]](https://arxiv.org/abs/1706.01427)
* **Reasoning With Neural Tensor Networks for Knowledge Base Completion** (NIPS 2013), Richard Socher et al. [[paper]](https://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion.pdf)
* **Recent Trends in Deep Learning Based Natural Language Processing** (arXiv 2017), T Young et al. [[paper]](https://arxiv.org/abs/1708.02709)
* **A Review of Relation Extraction** (Literature review for Language and Statistics II 2 2007), N Bach et al. [[paper]](http://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction.pdf)
* **A Systematic Exploration of the Feature Space for Relation Extraction** (NAACL 2007), J Jiang et al. [[paper]](http://sifaka.cs.uiuc.edu/czhai/pub/hlt07-rel.pdf)
* **Jointly Extracting Relations with Class Ties via Effective Deep Ranking** (arXiv 2016), H Ye et al. [[paper]](https://arxiv.org/abs/1612.07602)
* **A neural joint model for entity and relation extraction from biomedical text** (BMC bioinformatics 18.1 2017), F Li et al. [[paper]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1609-9)

[Back to Top](#contents)


## Datasets


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


## Contributing
Please feel free to make *[pull requests](https://github.com/roomylee/awesome-relation-extraction/pulls)*.
