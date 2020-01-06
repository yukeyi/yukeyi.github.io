---
layout: archive
title: "Projects"
permalink: /publications/
author_profile: true
---

<b>Attention Based End-To-End Speech-To-Text Translator [[link]](https://www.kaggle.com/c/11785-s19-hw4p2/)</b> <br>
Implemented a encoder-decoder model with attention mechanism, boosting with techniques like pooling BiLSTM, Teacher forcing rate scheduler, Beam search.  
Achieved 7.5 Levenshtein distance on Wall Street Journal dataset, ranked 1st among 166 people.

<b>Generative Adversarial Networks for Ink-and-Wash Style Transfer [[paper]](https://www.overleaf.com/3811229797mzqngypqfszf)</b> <br>
Built a pipeline for image style transfer task, from web scraping, data cropping and augmentation to loss function design, model training, monitoring and selection.  
Proposed effective loss functions customized for generating Ink-and-Wash style pictures.

<b>Medical Image Segmentation with Self-Supervised Learning [[code]](https://github.com/yukeyi/MCDS-Capstone)</b> <br>
Implemented 2D\&3D UNet, achieved reported dice score on HVSMR 2016 and Cardiac Atlas Dataset.
Tuned a registration model for 3D deformed heart slices. Trained a feature map embedding by doing distance learning between corresponding patches to improve segmentation results.  

<b>High Performance Web Service for Data Retrieval [[link]](https://theproject.zone)</b> <br>
Implemented Extract, Transform and Load(ETL) on more than 1TB Twitter data.  
Orchestrated Undertow frontend and MySQL backend server using AWS(Terraform,S3,RDS,LightSail)  
Develop data analysis APIs supported by user intimacy ranking and document similarity retrieval system.  
Optimized the whole system with Connection Pool(DBCP) / MultiIndex / Elastic Load Balancer(ELB) / Precomputation. Improved throughput from 500+ to 8000+ RPS.  

<b>Self-Adaptive Game-Setting Adjustment System [[code]](https://github.com/yukeyi/Self-adaption-game-system)</b> <br>
Developed a back-end manipulation system, providing dynamic real-time game setting. Enhanced user engagement by 48$\%$ during simulation test.  
Kernel is designed based on a proposed value-based RL algorithm, which enable exploration offline.  

<b>Fast and Accurate Text Classification with Reinforcement Learning [[paper]](https://github.com/yukeyi/ICLR-2018-Paper)</b> <br>
Speed up text-classification's inference process, maintaining the same accuracy.  
Trained a model by jointly optimizing policy module and neural classifier. Realized dynamic selection of whether stop reading or which semantic unit to read given current context.  
Attained 2x-4x speedup on various scales' datasets.  

<b>Robust Name Variant Retrieval [[paper]](https://www.overleaf.com/project/5d48dac8fcd2b0180d10ae42)</b> <br>
Extracted a name pair dataset(140K pairs) from raw user query log with Hadoop Pig and crowdsourcing.  
Trained a name embedding using Siamese LSTM \& Transformer, achieved 0.99+ NDCG, 0.95+ AP name similarity ranking score, boosting with pretrained character-level masked language model.  
Built a name variant retrieval system using name embedding, replaced cluster based method.  

<b>Enhancing Machine Translation with Dynamic Loss Function</b> <br>
Improved Tensor2Tensor baseline by implementing self-paced learning.  
Reimplemented and test performance of various structured prediction losses on NMT task.   
Trained a Learning-to-Teach model with reinforcement learning, realized dynamic loss selection for each training batch. Achieved a higher BLEU score on IWSLT 2014 than any single loss benchmark.  

<b>Investigating Meta-Learning Algorithms for Low-Resource Natural Language Understanding Tasks [[paper]](https://www.aclweb.org/anthology/D19-1112.pdf)</b> <br>
To be finished.

