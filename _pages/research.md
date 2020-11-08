---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
- /research/
- /research.html
---

Adviser: Professor Wei Wang &Yizhou Sun | Department of CS | UCLA       <span style="float:right;">Aug. 2019 – Mar. 2020</span>  
Project: Fast Adaptation for Cold-start Collaborative Filtering with Meta-learning
* I proposed a novel meta-learning paradigm, named MetaCF, that aims to learn an accurate collaborative filtering model that can be well-generalized for fast adaptions on fresh users with limited interactions;
* I designed a dynamic subgraph sampling that accounts for the dynamic arrival of fresh users and stabilizes the adaption procedure by optimizing the learning rates for adaption in a fine-grained manner. We also incorporated potential interactions to benefit the collaborative filtering models and alleviate the data sparsity problem.
* The paper, which I’m the first author, has been accepted by ICDM 2020 as a long paper.


Adviser: Vice Dean Xiangnan He | USTC & Jinfeng Yi | JD AI Research       <span style="float:right;">Feb. 2020 – June 2020</span>  
Project: Eliminating Popularity Bias in Recommender System via Counterfactual Reasoning
* The general aim of the recommender system is to provide personalized suggestions to users, which is opposed to suggesting popular items; however, the normal training paradigm, i.e., fitting a recommender model to recover the user behavior data with pointwise or pairwise loss, makes the model biased towards popular items;
* In this work, I explored the popularity bias issue from a novel and fundamental perspective --- cause-effect. I identified that popularity bias lies in the direct effect from the item node to the ranking score, such that an item's intrinsic property is the cause of mistakenly assigning it a higher ranking score;
* I am the first to formulate the causal graph for recommendation and proposed a model-agnostic counterfactual reasoning framework that trains a recommender model according to the causal graph via a multi-task training schema and performs counterfactual inference to eliminate bias;
* The paper has been submitted to WWW as the first author. 


Adviser: Professor Zhangyang Wang | Department of ECE | UT-Austin        <span style="float:right;">Jan. 2020 – May. 2020</span>  
Project: AR-Stock: Deep Augmented Relational Stock Prediction
* I proposed to extend the traditional graph neural network to accurately predict stock trends by leveraging the rich information in the stock knowledge graph;
* I designed a geometric augmentation approach to discover hidden long-range dependencies between stocks. Also, I leveraged self-supervised learning to facilitate GCN training and to enforce global and local graph structure awareness. 


Adviser: Professor Qi Liu & Professor Enhong Chen | CS | USTC            <span style="float:right;">May. 2019 – July. 2019</span>  
Project: Unpaired Multimodal Neural Machine Translation via Reinforcement Learning	
* To resolve the data scarcity problem for low resource language pairs in machine translation, I designed a translation model with the image description dataset which is much easier to obtain but harder to use than traditional multi-lingual dataset;
* Designed a novel reward function for reinforcement learning based on the image caption model to capture the consistency between the language and images;
* The paper has been submitted to DASFAA as the co-first author and a patent is obtained.


Adviser: Dr. Ruirui Li & Dr. Oguz Elibol | Amazon Alexa           <span style="float:right;">Aug 2020-present</span>  
Project: Adversarial Self-supervised Learning for Speaker Identification
* I introduced both frame-mask and frequency-mask based self-supervised reconstruction tasks to enhance the training of speaker identification task in the context of multi-task learning;
* I designed the adversarial loss to enhance the self-supervision reconstruction, to improve the identification accuracy.
