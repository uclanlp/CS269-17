---
layout: page17
title: Speakers
permalink: /ICML17/speakers/
name: 6
---

## [David Sontag](http://clinicalml.org/) (MIT)

#### Title: Deep Markov models

#### Abstract:
Gaussian state space models have been used for decades as generative
models of sequential data. They admit an intuitive probabilistic
interpretation, have a simple functional form, and enjoy widespread
adoption. We introduce a unified algorithm to efficiently learn a
broad class of linear and non-linear state space models, including
variants where the emission and transition distributions are modeled
by deep neural networks. Our learning algorithm simultaneously learns
a compiled inference network and the generative model, leveraging a
structured variational approximation parameterized by recurrent neural
networks to mimic the posterior distribution. We apply the learning
algorithm to both synthetic and real-world datasets, demonstrating its
scalability and versatility. We find that using the structured
approximation to the posterior results in models with significantly
higher held-out likelihood.

Joint work with Rahul Krishnan and Uri Shalit.

## [Ryan Adams](http://people.seas.harvard.edu/~rpa/) (Harvard)

#### Title: Building Probabilistic Structure into Massively Parameterized Models

#### Abstract:
Scientific applications of machine learning typically involve the identification of interpretable structure from high-dimensional observations.  It is often challenging, however, to balance the flexibility required for high dimensional problems against the parsimonious structure that helps us model physical reality.  I view this challenge through the lens of semiparametric modeling, in which a massively-parameterized function approximator is coupled to a compact and interpretable probabilistic model.  Of particular interest in this vein is the merging of deep neural networks with graphical models containing latent variables, which enables each component to play to its strengths.  I will discuss several different classes of such models, and various applications, in areas such as astronomy, chemistry, neuroscience, and sports analytics.

## [Sujith Ravi](http://sravi.org/) (Google)

#### Title: Neural Graph Learning

#### Abstract: 
Recent machine learning advances have enabled us to build intelligent systems that understand semantics from speech, natural language text and images. While great progress has been made in many AI fields, building scalable intelligent systems from "scratch" still remains a daunting challenge for many applications.To overcome this, we exploit the power of graph algorithms since they offer a simple elegant way to express different types of relationships observed in data and can concisely encode structure underlying a problem. In this talk I will focus on “How can we combine the flexibility of graphs with the power of machine learning?”

I will describe how we address these challenges and design efficient algorithms by employing graph-based machine learning as a computing mechanism to solve real-world prediction tasks. Our graph-based machine learning framework can operate at large scale and easily handle massive graphs (containing billions of vertices and trillions of edges) and make predictions over billions of output labels while achieving O(1) space complexity per vertex. In particular, we combine graph learning with deep neural networks to power a number of machine intelligence applications, including Smart Reply, image recognition and video summarization to tackle complex language understanding and computer vision problems. l will also introduce some of our latest research and share results on “neural graph learning”, a new joint optimization framework for combing graph learning with deep neural network models.


## [Dhruv Batra](https://www.cc.gatech.edu/~dbatra/index.html) (Georgia Tech and Facebook AI Research)

#### Title: Sequence-Level Training of Neural Models for Visual Dialog

#### Abstract:

Neural sequence models (and their deep/hierarchical variants) have seen widespread adoption across a range of AI applications (machine translation, dialog systems, image captioning, visual question answering, etc). In this talk, I will introduce first introduce a new AI talk — Visual Dialog — which requires an AI agent to hold a meaningful dialog with humans in natural, conversational language about visual content. Specifically, given an image, a dialog history, and a question about the image, the agent has to ground the question in image, infer context from history, and answer the question accurately.
Using this application as a backdrop, I will discuss approaches for sequence-level training of neural models that optimize high-order downstream task-specific objectives.


## Wang Ling (Google)
#### Title: Text Generation via Program Induction

#### Abstract: 

Many language generation and understanding tasks require the production of arbitrary functions. I will present a language generation approach, where the text is generated by executing a program that is induced automatically from the model. Crucially, this approach allows arbitrary functions to be incorporated in the generation process, granting additional generalization capabilities for the model. I will describe the inference challenges that emerge from marginalizing over all possible programs that can generate the observed text, and present two scenarios where the model can be applied. Firstly, I show that the model can be used to generate code from natural language descriptions. Secondly, I will use the model to solve and explain algebraic math problems.



