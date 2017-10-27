---
layout: page
title: Resources
permalink: /resource
name: 3
---
### Related readings:
THe following handouts and write-ups are related to the course:
- [Language Model (Michael Collins)](http://www.cs.columbia.edu/~mcollins/lm-spring2013.pdf)
- [HMM & Tagging (Michael Collins)](http://www.cs.columbia.edu/~mcollins/hmms-spring2013.pdf)
- [Log linear model (Michael Collins)](http://www.cs.columbia.edu/~mcollins/loglinear.pdf)
- [MEMM (Michael Collins)](http://www.cs.columbia.edu/~mcollins/fall2014-loglineartaggers.pdf)
- [CRF (Michael Collins)](http://www.cs.columbia.edu/~mcollins/crf.pdf)
- [Multi-class classification (Chih-Jen Lin)](https://www.csie.ntu.edu.tw/~cjlin/papers/multisvm.pdf)
- [Neural Network (Yoav Goldberg)](http://u.cs.biu.ac.il/~yogo/nnlp.pdf)

### Papers:
The [ACL anthology](http://aclweb.org/anthology-new/) has a large collection of NLP papers. 


# Software packages/ Libraries
The following is an incomplete list of software packages and libraries for developing NLP systems. 

### Python
There are many off-the-shelf NLP Python libraries are useful
- [NLTK](http://www.nltk.org/)
- [SpyCy](https://spacy.io/)
- [GenSim](https://radimrehurek.com/gensim/)

Some machine learning systems may be helpful as well:
- [Pytorch](http://pytorch.org/)
- [Tensorflow](https://www.tensorflow.org/)
- [DyNet](https://github.com/clab/dynet)
- [Scikit learn](http://scikit-learn.org/stable/)

### Java/Scala
Several state-of-the-art systems are built in Java
- [Stanford coreNLP Pipline](http://stanfordnlp.github.io/CoreNLP/)
- [Illinois NLP packages](https://cogcomp.cs.illinois.edu/page/software/), [Demo](http://cogcomp.cs.illinois.edu/curator/demo/)
- [Berkley NLP software](http://nlp.cs.berkeley.edu/software.shtml)
- [Twitter NLP toolkit](https://github.com/aritter/twitter_nlp)
Some declarative learning libraries
- [Wolfe](http://www.wolfe.ml/)
- [Saul](https://github.com/IllinoisCogComp/saul)
- [Dyna](https://github.com/nwf/dyna)

### C/C++
Large-scale learning libraries:
- [Liblinear](https://www.csie.ntu.edu.tw/~cjlin/liblinear/)
- [Vowpal Wabbit](www.hunch.net/~vw)
- [CMU cnn library](https://github.com/clab/cnn) and its [NLP applications](https://github.com/clab)


### Suggested Papers (More papers will be added)

The following are suggested papers for presentations and writing critical review reports. 

#### Language Models

- Yee Whye Teh, "A hierarchical Bayesian language model based on Pitman-Yor processes." ACL 2006 ([PDF](http://www.aclweb.org/anthology/P06-1124.pdf)).
- Yoshua Bengio, Rejean Ducharme, Pascal Vincent, Christian Jauvin, "A Neural Probability Language Model." JMLR 2003 ([PDF](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)).
- Yoom Kim, Yacine Jernite, David Sontag, Alexander M. Rush, "Character-Aware Neural Language Models". AAAI 2015 ([PDF](https://arxiv.org/pdf/1508.06615v4.pdf)).
- Brian Roark, Murat Saraclar, Michael Collins, Mark Johnson, "Discriminative Language Modeling with Conditional Random Fields and the Perceptron Algorithm". ACL 2004 ([PDF](http://www.aclweb.org/anthology/P04-1007.pdf)).

#### Parsing
- Yoav Goldberg, Joakim Nivre, "Training Deterministic Parsers with Non-Deterministic Oracles." TACL 2013 ([PDF](http://www.aclweb.org/anthology/Q/Q13/Q13-1033.pdf))
- Danqi Chen, Christopher D. Manning, "A Fast and Accurate Dependency Parser using Neural Networks." EMNLP 2014 ([PDF](http://cs.stanford.edu/people/danqi/papers/emnlp2014.pdf))
- Andre F. T. Martins,  Noah A. Smith, Eric P. Xing. "Turbo Parsers: Dependency Parsing by Approximate Variational Inference" EMNLP 2010. ([PDF](https://www.cs.cmu.edu/~afm/Home_files/emnlp2010.pdf))
- Yoav Goldberg, Michael Elhadad, "An Efficient Algorithm for Easy-First Non-Directional Dependency Parsing." NAACL 2010 ([PDF](http://www.aclweb.org/anthology/N10-1115))
- Dan Klein, Christopher D. Manning, "Accurate Unlexicalized Parsing." ACL 2003 ([PDF](https://people.eecs.berkeley.edu/~klein/papers/unlexicalized-parsing.pdf))


#### Information Extraction 
- T. Mitchell, W. Cohen, E. Hruschka, P. Talukdar, J. Betteridge, A. Carlson, B. Dalvi, M. Gardner, B. Kisiel, J. Krishnamurthy, N. Lao, K. Mazaitis, T. Mohamed, N. Nakashole, E. Platanios, A. Ritter, M. Samadi, B. Settles, R. Wang, D. Wijaya, A. Gupta, X. Chen, A. Saparov, M. Greaves, J. Welling. Never-Ending Language Learning. AAAI 2015.
- S. Riedel, L. Yao, B. M. Marlin and A. McCallum. "Relation Extraction with Matrix Factorization and Universal Schemas". NAACL 2013. ([PDF](http://www.aclweb.org/anthology/N13-1008))
- S. Singh, T. Rocktaschel and S. Riedel. "Towards Combined Matrix and Tensor Factorization for Universal Schema Relation Extraction". NAACL 2015. ([PDF](http://sameersingh.org/files/papers/mftf-vsm15.pdf))
- Michele Banko, Michael J Cafarella, Stephen Soderland, Matt Broadhead and Oren Etzioni. "Open Information Extraction from the Web".  IJCAI 2007. ([PDF](http://www.aaai.org/Papers/IJCAI/2007/IJCAI07-429.pdf))
- Mike Mintz, Steven Bills, Rion Snow, Dan Jurafsky. "Distant supervision for relation extraction without labeled data." ACL 2009. ([PDF](http://web.stanford.edu/~jurafsky/mintz.pdf))
- Panupong Pasupat, Percy Liang. "Zero-shot entity extraction from web pages." ACL 2014. ([PDF](http://cs.stanford.edu/~pliang/papers/extraction-acl2014.pdf))
#### Question Answering / Semantic Parsing
- Jonathan Berant, Vivek Srikumar, Pei-Chun Chen, Abby Vander Linden, Brittany Harding, Brad Huang, Peter Clark and Christopher D. Manning. "Modeling Biological Processes for Reading Comprehension." EMNLP 14 ([PDF](http://nlp.stanford.edu/pubs/berant-srikumar-manning-emnlp14.pdf))
- Scott Wen-tau Yih, Ming-Wei Chang, Xiaodong He, Jianfeng Gao, "Semantic Parsing via Staged Query Graph Generation: Question Answering with Knowledge Base". ACL 2015 ([PDF](http://www.aclweb.org/anthology/P15-1128))
- Percy Liang, Michael I. Jordan, Dan Klein, "Learning dependency-based compositional semantics." ACL 2011. ([PDF](http://cs.stanford.edu/~pliang/papers/dcs-acl2011.pdf))
- Jonathan Berant, Percy Liang. "Imitation learning of agenda-based semantic parsers." TACL 2015 ([PDF](http://cs.stanford.edu/~pliang/papers/agenda-tacl2015.pdf))


#### Semantic Role Labeling
- Kristina Toutanova, Aria Haghigh, Christopher D. Manning. "Joint Learning Improves Semantic Role Labeling." ACL 2005 ([PDF](http://www.aclweb.org/anthology/P05-1073))
- Vivek Srikumar, Dan Roth "A Joint Model for Extended Semantic Role Labeling". ACL 2011([PDF](http://www.aclweb.org/anthology/D11-1012))
- Daniel Gildea, Daniel Jurafsky, "Automatic Labeling of Semantic Roles". ACL 2000([PDF](http://www.aclweb.org/anthology/P00-1065))

#### Corefernece Resolution
- Karthik Raghunathan, Heeyoung Lee, Sudarshan Rangarajan, Nathanael Chambers, Mihai Surdeanu, Dan Jurafsky, Christopher Manning. "A Multi-Pass Sieve for Coreference Resolution". EMNLP 2010 ([PDF](http://www.aclweb.org/anthology/D10-1048))
- Greg Durrett and Dan Klein. "Easy Victories and Uphill Battles in Coreference Resolution." EMNLP 2013. ([PDF](http://www.eecs.berkeley.edu/~gdurrett/papers/durrett-klein-emnlp2013.pdf))
- Kai-Wei Chang Rajhan Samdani, Dan Roth. "A Constrained Latent Variable Model for Coreference Resolution" EMNLP 2013. ([PDF](http://www.aclweb.org/website/old_anthology/D/D13/D13-1057.pdf))
- Sam Wiseman, Alexander M. Rush, and Stuart M. Shieber. "Learning Global Features for Coreference Resolution" NAACL 2016. ([PDF](http://nlp.seas.harvard.edu/papers/corefmain.pdf))


#### Name Entity Recognition / Entity Linking
- Alan Ritter, Sam Clark, Mausam and Oren Etzioni. "Named Entity Recognition in Tweets: An Experimental Study". EMNLP 2011 ([PDF](https://homes.cs.washington.edu/~mausam/papers/emnlp11.pdf))
- Lev Ratinov,  Dan Roth. "Design Challenges and Misconceptions in Named Entity Recognition". CoNLL 2009 ([PDF](http://www.cs.brandeis.edu/~marc/misc/proceedings/naacl-hlt-2009/CoNLL/pdf/CoNLL19.pdf))
- Andrea Moro, Alessandro Raganato, Roberto Navigli. "Entity Linking meets Word Sense Disambiguation: A Unified Approach". TACL 2014 ([PDF](https://transacl.org/ojs/index.php/tacl/article/download/291/47))
- Greg Durrett and Dan Klein. "A Joint Model for Entity Analysis: Coreference, Typing, and Linking". TACL 2014 ([PDF](http://nlp.cs.berkeley.edu/pubs/Durrett-Klein_2014_Joint_paper.pdf))
- Xiao Ling, Sameer Singh, and Daniel S. Weld. "Design Challenges for Entity Linking". TACL 2015 ([PDF](http://sameersingh.org/files/papers/entitylinking-tacl15.pdf))
- Parag Singla and Pedro Domingos. "Entity Resolution with Markov Logic". ICDM 2006 ([PDF](http://homes.cs.washington.edu/~pedrod/papers/icdm06.pdf))


#### Word Embeddings
- Jeffrey Pennington, Richard Socher and Christopher D. Manning. "Glove: Global Vectors for Word Representation". EMNLP 2014. ([PDF](http://nlp.stanford.edu/projects/glove/glove.pdf)).
- Manaal Faruqui Jesse Dodge Sujay K. Jauhar, Chris Dyer Eduard Hovy Noah A. Smith. "Retrofitting Word Vectors to Semantic Lexicons". NAACL 2015. ([PDF](https://www.cs.cmu.edu/~hovy/papers/15HLT-retrofitting-word-vectors.pdf))
- Omer Levy, Yoav Goldberg. "Neural Word Embedding as Implicit Matrix Factorization". NIPS 2014. ([PDF](https://papers.nips.cc/paper/5477-neural-word-embedding-as-implicit-matrix-factorization.pdf))

#### Machine Translation 
- Philipp Koehn, Franz Josef Och, Daniel Marcu. "Statistical Phrase-Based Translation."  NAACL 2003. ([PDF](http://www.aclweb.org/anthology/N03-1017))
- Ilya Sutskever, Oriol Vinyals, Quoc V. Le. "Sequence to Sequence Learning with Neural Networks". NIPS 2014. 
- Dzmitry Bahdanau, KyungHyun Cho and Yoshua Bengio. "Neural machine translation by jointly learning to align and translate". ICLR 2015. ([PDF](https://arxiv.org/pdf/1409.0473v7.pdf))

#### Word Alignment / Paragraph 
- Regina Barzilay and Lillian Lee. "Learning to Paraphrase: An Unsupervised Approach Using Multiple-Sequence Alignment". NAACL 2003. ([PDF](http://www.cs.cornell.edu/home/llee/papers/statpar.pdf))
- Colin Bannard and Chris Callison-Burch. "Paraphrasing with Bilingual Parallel Corpora.". ACL 2005.  ([PDF](https://www.cs.jhu.edu/~ccb/publications/paraphrasing-with-bilingual-parallel-corpora.pdf))
- Socher, R. and Huang, E.H., and Pennington, J. and Ng, A.Y., and Manning, C.D. " Dynamic pooling and unfolding recursive autoencoders for paraphrase detection". NIPS 2011 ([PDF](http://www.socher.org/uploads/Main/SocherHuangPenningtonNgManning_NIPS2011.pdf))

#### Others
- P. Liang, H. Daume, and D. Klein. "Structure Compilation: Trading Structure for Features". ICML 2008. ([PDF](https://cs.stanford.edu/~pliang/papers/structure-icml2008.pdf))
- Nate Kushman, Yoav Artzi, Luke Zettlemoyer, and Regina Barzilay. "Learning to Automatically Solve Algebra Word Problems". ACL 2014 ([PDF](https://people.csail.mit.edu/regina/my_papers/wp.pdf))
- Pedro Domingos, Matthew Richardson. "Markov Logic: A Unifying Framework for Statistical Relational Learning"
