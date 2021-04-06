# An Updating Survey for Bayesian Deep Learning (BDL)

This is an updating survey for Bayesian Deep Learning (BDL), an constantly updated and extended version for the manuscript, '[A Survey on Bayesian Deep Learning](http://wanghao.in/paper/CSUR20_BDL.pdf)', published in [**ACM Computing Surveys**](https://dl.acm.org/doi/10.1145/3409383) 2020.<br>

Bayesian deep learning is a powerful framework for designing models across a wide range of applications. See our [**Nature Medicine** paper](https://www.nature.com/articles/s41591-021-01273-1.pdf) for a possible application on healthcare. 

## Contents

* [Survey](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#survey)
* [BDL and Recommender Systems](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-recommender-systems)
* [BDL and Domain Adaptation](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-domain-adaptation)
* [BDL and Healthcare](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-healthcare)
* [BDL and Natural Language Processing (NLP)](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-nlp)
* [BDL and Computer Vision (CV)](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-computer-vision)
* [BDL and Control](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-control)
* [BDL and Graphs (Link Prediction, Graph Neural Networks, etc.)](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-graphs-link-prediction-graph-neural-networks-etc)
* [BDL and Topic Modeling](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-topic-modeling)
* [BDL and Speech Recognition/Synthesis](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-speech-recognitionsynthesis)
* [BDL and Forecasting (Time Series Analysis)](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-forecasting-time-series-analysis)
* [BDL as a Framework (Miscellaneous)](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-as-a-framework-miscellaneous)
* [Bayesian/Probabilistic Neural Networks as Building Blocks of BDL](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bayesianprobabilistic-neural-networks-as-building-blocks-of-bdl)


## Survey

A Survey on Bayesian Deep Learning<br>
by Wang et al., ACM Computing Surveys (CSUR) 2020<br>
[[PDF]](http://wanghao.in/paper/CSUR20_BDL.pdf) [[Blog]](http://wanghao.in/BDL.html) [[BDL Framework in 2016]](http://wanghao.in/paper/TKDE16_BDL.pdf)

<p align="center">
<img src="./BDL_Table.png" alt="" data-canonical-src="./BDL_Table.png" width="930" height="580"/>
</p>

## BDL and Recommender Systems

Collaborative Deep Learning for Recommender Systems<br>
by Wang et al., KDD 2015<br>
[[PDF]](http://wanghao.in/paper/KDD15_CDL.pdf) [[Project Page]](http://wanghao.in/CDL.htm) [[2014 Arxiv Version]](https://arxiv.org/abs/1409.2944) [[Code]](https://github.com/js05212/CDL) [[MXNet Code]](https://github.com/js05212/MXNet-for-CDL) [[TensorFlow Code]](https://github.com/js05212/CollaborativeDeepLearning-TensorFlow) [[Dataset A]](https://github.com/js05212/citeulike-a) [[Dataset B]](https://github.com/js05212/citeulike-t) [[Jupyter Notebook]](https://github.com/js05212/MXNet-for-CDL/blob/master/collaborative-dl.ipynb) [[Slides]](http://wanghao.in/slides/CDL_slides.pdf) [[Slides (Long)]](http://wanghao.in/slides/CDL_slides_long.pdf)

Collaborative Recurrent Autoencoder: Recommend while Learning to Fill in the Blanks<br>
by Wang et al., NIPS 2016<br>
[[PDF]](https://arxiv.org/abs/1611.00454)

Collaborative Knowledge Base Embedding for Recommender Systems<br>
by Zhang et al., KDD 2016<br>
[[PDF]](https://dl.acm.org/citation.cfm?id=2939673)

Collaborative Deep Ranking: A Hybrid Pair-Wise Recommendation Algorithm with Implicit Feedback<br>
by Ying et al., PAKDD 2016<br>
[[PDF]](https://link.springer.com/chapter/10.1007/978-3-319-31750-2_44)

Collaborative Variational Autoencoder for Recommender Systems<br>
by Li et al., KDD 2017<br>
[[PDF]](https://www.kdd.org/kdd2017/papers/view/collaborative-variational-autoencoder-for-recommender-systems)

Variational Autoencoders for Collaborative Filtering<br>
by Liang et al., WWW 2018<br>
[[PDF]](https://arxiv.org/abs/1802.05814)

Probabilistic Metric Learning with Adaptive Margin for Top-K Recommendation<br>
by Ma et al., KDD 2020<br>
[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403147)

## BDL and Domain Adaptation
Continuously Indexed Domain Adaptation<br>
by Wang et al., ICML 2020<br>
[[PDF]](http://wanghao.in/paper/ICML20_CIDA.pdf) 

## BDL and Healthcare

Electronic Health Record Analysis via Deep Poisson Factor Models<br>
by Henao et al., JMLR 2016<br>
[[PDF]](http://www.jmlr.org/papers/volume17/15-429/15-429.pdf)

Structured Inference Networks for Nonlinear State Space Models<br>
by Krishnan et al., AAAI 2017<br>
[[PDF]](https://arxiv.org/pdf/1609.09869.pdf)

Black Box FDR<br>
by Tansey et al., ICML 2018<br>
[[PDF]](https://arxiv.org/abs/1806.03143)

Bidirectional Inference Networks: A Class of Deep Bayesian Networks for Health Profiling<br>
by Wang et al., AAAI 2019<br>
[[PDF]](https://arxiv.org/pdf/1902.02037)

Sampling-free Uncertainty Estimation in Gated Recurrent Units with Applications to Normative Modeling in Neuroimaging<br>
by Hwang et al., UAI 2019<br>
[[PDF]](http://auai.org/uai2019/proceedings/papers/296.pdf)

Neural Jump Stochastic Differential Equations<br>
by Jia et al., NIPS 2019<br>
[[PDF]](https://arxiv.org/pdf/1905.10403.pdf)

Towards Interpretable Clinical Diagnosis with Bayesian Network Ensembles Stacked on Entity-Aware CNNs<br>
by Chen et al., ACL 2020<br>
[[PDF]](https://www.aclweb.org/anthology/2020.acl-main.286.pdf)

Continuously Indexed Domain Adaptation<br>
by Wang et al., ICML 2020<br>
[[PDF]](http://wanghao.in/paper/ICML20_CIDA.pdf) [Cross Referenced in [BDL and Domain Adaptation](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-domain-adaptation)]

## BDL and NLP

Sequence to Better Sequence: Continuous Revision of Combinatorial Structures<br>
by Mueller et al., ICML 2017<br>
[[PDF]](http://proceedings.mlr.press/v70/mueller17a.html)

QuaSE: Sequence Editing under Quantifiable Guidance<br>
by Liao et al., EMNLP 2018<br>
[[PDF]](https://arxiv.org/pdf/1804.07007.pdf)

Dispersed Exponential Family Mixture VAEs for Interpretable Text Generation<br>
by Shi et al., ICML 2020<br>
[[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/3242-Paper.pdf)

Towards Interpretable Clinical Diagnosis with Bayesian Network Ensembles Stacked on Entity-Aware CNNs<br>
by Chen et al., ACL 2020<br>
[[PDF]](https://www.aclweb.org/anthology/2020.acl-main.286.pdf) [Cross Referenced in [BDL and Healthcare](https://github.com/js05212/BayesianDeepLearning-Survey/blob/master/README.md#bdl-and-healthcare)]

## BDL and Computer Vision
Attend, Infer, Repeat: Fast Scene Understanding with Generative Models<br>
by Eslami et al., NIPS 2016<br>
[[PDF]](https://arxiv.org/abs/1603.08575)

Efficient Inference in Occlusion-aware Generative Models of Images<br>
by Huang et al., ICLR 2016<br>
[[PDF]](https://arxiv.org/abs/1511.06362)

Sequential Attend, Infer, Repeat: Generative Modelling of Moving Objects<br>
by Kosiorek et al., NIPS 2018<br>
[[PDF]](https://arxiv.org/abs/1806.01794)

Gaussian Process Prior Variational Autoencoders<br>
by Casale et al., NIPS 2018<br>
[[PDF]](https://arxiv.org/pdf/1810.11738.pdf)

Spatially Invariant Unsupervised Object Detection with Convolutional Neural Networks<br>
by Crawford et al., AAAI 2019<br>
[[PDF]](https://www.aaai.org/ojs/index.php/AAAI/article/view/4216)

Faster Attend-Infer-Repeat with Tractable Probabilistic Models<br>
by Stelzner et al., ICML 2019<br>
[[PDF]](http://proceedings.mlr.press/v97/stelzner19a.html)

Asynchronous Temporal Fields for Action Recognition<br>
by Sigurdsson et al., CVPR 2017<br>
[[PDF]](https://arxiv.org/pdf/1612.06371.pdf)

Generalizing Eye Tracking with Bayesian Adversarial Learning<br>
by Wang et al., CVPR 2019<br>
[[PDF]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Generalizing_Eye_Tracking_With_Bayesian_Adversarial_Learning_CVPR_2019_paper.pdf)

Sequential Neural Processes<br>
by Singh et al., NIPS 2019<br>
[[PDF]](http://papers.nips.cc/paper/9214-sequential-neural-processes.pdf)

 Being Bayesian about Categorical Probability<br>
 by Joo et al., ICML 2020<br>
 [[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/3560-Paper.pdf)
 
 Generative Neurosymbolic Machines<br>
 by Jiang et al., NIPS 2020<br>
 [[PDF]](https://arxiv.org/pdf/2010.12152.pdf)

## BDL and Control

Embed to Control: A Locally Linear Latent Dynamics Model for Control from Raw Images<br>
by Watter et al., NIPS 2015<br>
[[PDF]](https://arxiv.org/abs/1506.07365)

Deep Variational Bayes Filters: Unsupervised Learning of State Space Models from Raw Data<br>
by Karl et al., ICLR 2017<br>
[[PDF]](https://arxiv.org/pdf/1605.06432.pdf)

Probabilistic Recurrent State-Space Models<br>
by Doerr et al., ICML 2018<br>
[[PDF]](http://proceedings.mlr.press/v80/doerr18a/doerr18a.pdf)

Learning Latent Dynamics for Planning from Pixels<br>
by Hafner et al., ICML 2019<br>
[[PDF]](https://arxiv.org/pdf/1811.04551.pdf)

## BDL and Graphs (Link Prediction, Graph Neural Networks, Knowledge Graphs, etc.)

Relational Deep Learning: A Deep Latent Variable Model for Link Prediction<br>
by Wang et al., AAAI 2017<br>
[[PDF]](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14346/14463)

Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs<br>
by Trivedi et al., ICML 2017<br>
[[PDF]](https://arxiv.org/pdf/1705.05742.pdf)

Graphite: Iterative Generative Modeling of Graphs<br>
by Grover et al., ICML 2019<br>
[[PDF]](https://arxiv.org/pdf/1803.10459.pdf)

Relational Variational Autoencoder for Link Prediction with Multimedia Data<br>
by Li et al., ACM MM 2017<br>
[[PDF]](https://dl.acm.org/citation.cfm?id=3126774)

Stochastic Blockmodels meet Graph Neural Networks<br>
by Mehta et al., ICML 2019<br>
[[PDF]](https://arxiv.org/pdf/1905.05738.pdf)

Scalable Deep Generative Modeling for Sparse Graphs<br>
by Dai et al., ICML 2020<br>
[[PDF]](https://arxiv.org/pdf/2006.15502.pdf)

PGM-Explainer: Probabilistic Graphical Model Explanations for Graph Neural Networks<br>
by Vu et al., NIPS 2020<br>
[[PDF]](https://arxiv.org/pdf/2010.05788.pdf)

Dirichlet Graph Variational Autoencoder<br>
by Li et al., NIPS 2020<br>
[[PDF]](https://arxiv.org/pdf/2010.04408.pdf)

Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs<br>
by Ren et al., NIPS 2020<br>
[[PDF]](https://arxiv.org/pdf/2010.11465.pdf)

## BDL and Topic Modeling

Relational Stacked Denoising Autoencoder for Tag Recommendation<br>
by Wang et al., AAAI 2015<br>
[[PDF]](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/download/9350/9980)

Scalable Deep Poisson Factor Analysis for Topic Modeling<br>
by Gan et al., ICML 2015<br>
[[PDF]](http://proceedings.mlr.press/v37/gan15.html)

Deep Latent Dirichlet Allocation with Topic-layer-adaptive Stochastic Gradient Riemannian MCMC<br>
by Cong et al., ICML 2017<br>
[[PDF]](https://dl.acm.org/citation.cfm?id=3305471)

Deep Unfolding for Topic Models<br>
by Chien et al., TPAMI 2017<br>
[[PDF]](https://ieeexplore.ieee.org/abstract/document/7869412/)

Neural Relational Topic Models for Scientific Article Analysis<br>
by Bai et al., CIKM 2018<br>
[[PDF]](https://dl.acm.org/citation.cfm?id=3271696)

Dirichlet Belief Networks for Topic Structure Learning<br>
by Zhao et al., NIPS 2018<br>
[[PDF]](http://papers.nips.cc/paper/8020-dirichlet-belief-networks-for-topic-structure-learning)

Deep Relational Topic Modeling via Graph Poisson Gamma Belief Network<br>
by Wang et al., NIPS 2020<br>
[[PDF]](https://proceedings.neurips.cc//paper/2020/hash/05ee45de8d877c3949760a94fa691533-Abstract.html)

## BDL and Speech Recognition/Synthesis

Unsupervised Learning of Disentangled and Interpretable Representations from Sequential Data<br>
by Hsu et al., NIPS 2017<br>
[[PDF]](https://arxiv.org/pdf/1709.07902.pdf)

Scalable Factorized Hierarchical Variational Autoencoder Training<br>
by Hsu et al., Interspeech 2018<br>
[[PDF]](https://arxiv.org/pdf/1804.03201.pdf)

Hierarchical Generative Modeling for Controllable Speech Synthesis<br>
by Hsu et al., ICLR 2019<br>
[[PDF]](https://arxiv.org/pdf/1810.07217.pdf)

Recurrent Poisson Process Unit for Speech Recognition<br>
by Huang et al., AAAI 2019<br>
[[PDF]](https://pdfs.semanticscholar.org/4970/fa3189cd9a9c817ba72082e2f3d5fc9a7df1.pdf)

Deep Graph Random Process for Relational-thinking-based Speech Recognition<br>
by Huang et al., ICML 2020<br>
[[PDF]](http://wanghao.in/paper/ICML20_DGP.pdf)

## BDL and Forecasting (Time Series Analysis)

DeepAR: Probabilistic Forecasting with Autoregressive Recurrent Networks<br>
by Salinas et al., 2017<br>
[[PDF]](https://arxiv.org/pdf/1704.04110.pdf)

Deep State Space Models for Time Series Forecasting<br>
by Rangapuram et al., NIPS 2018<br>
[[PDF]](https://papers.nips.cc/paper/8004-deep-state-space-models-for-time-series-forecasting.pdf)

Deep Factors for Forecasting<br>
by Wang et al., ICML 2019<br>
[[PDF]](https://arxiv.org/pdf/1905.12417.pdf)

Probabilistic Forecasting with Spline Quantile Function RNNs<br>
by Gasthaus et al., AISTATS 2019<br>
[[PDF]](http://proceedings.mlr.press/v89/gasthaus19a/gasthaus19a.pdf)

Adversarial Attacks on Probabilistic Autoregressive Forecasting Models<br>
by Dang-Nhu et al., ICML 2020<br>
[[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/526-Paper.pdf)

## BDL as a Framework (Miscellaneous)

Towards Bayesian Deep Learning: A Framework and Some Existing Methods<br>
by Wang et al., TKDE 2016<br>
[[PDF]](https://arxiv.org/abs/1608.06884)

Composing Graphical Models with Neural Networks for Structured Representations and Fast Inference<br>
by Johnson et al., NIPS 2016<br>
[[PDF]](https://arxiv.org/abs/1603.06277)

## Bayesian/Probabilistic Neural Networks as Building Blocks of BDL

Learning Stochastic Feedforward Networks<br>
by Neal et al., Technical Report 1990<br>
[[PDF]](https://www.cs.toronto.edu/~hinton/absps/sff.pdf)

A Practical Bayesian Framework for Backprop Networks<br>
by MacKay et al., Neural Computation 1992<br>
[[PDF]](https://pdfs.semanticscholar.org/b0f2/433c088591d265891231f1c22424047f1bc1.pdf)

Keeping Neural Networks Simple by Minimizing the Description Length of the Weights<br>
by Hinton et al., COLT 1993<br>
[[PDF]](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.44.3435)

Practical Variational Inference for Neural Networks<br>
by Alex Graves, NIPS 2011<br>
[[PDF]](https://papers.nips.cc/paper/4329-practical-variational-inference-for-neural-networks)

Auto-Encoding Variational Bayes<br>
by Kingma et al., ArXiv 2014<br>
[[PDF]](https://arxiv.org/pdf/1312.6114.pdf)

Deep Exponential Families<br>
by Ranganath et al., AISTATS 2015<br>
[[PDF]](https://arxiv.org/abs/1411.2581)

Weight Uncertainty in Neural Networks<br>
by Blundell et al., ICML 2015<br>
[[PDF]](https://arxiv.org/abs/1505.05424)

Probabilistic Backpropagation for Scalable Learning of Bayesian Neural Networks<br>
by Hernandez-Lobato et al., ICML 2015<br>
[[PDF]](http://proceedings.mlr.press/v37/hernandez-lobatoc15.pdf)

Variational Dropout and the Local Reparameterization Trick<br>
by Kingma et al., NIPS 2015<br>
[[PDF]](https://arxiv.org/pdf/1506.02557.pdf)

The Poisson Gamma Belief Network<br>
by Zhou et al., NIPS 2015<br>
[[PDF]](http://papers.nips.cc/paper/5645-the-poisson-gamma-belief-network)

Deep Poisson Factor Modeling<br>
by Henao et al., NIPS 2015<br>
[[PDF]](http://papers.nips.cc/paper/5786-deep-poisson-factor-modeling)

Natural-Parameter Networks: A Class of Probabilistic Neural Networks<br>
by Wang et al., NIPS 2016<br>
[[PDF]](http://wanghao.in/paper/NIPS16_NPN.pdf) [[Project Page]](https://github.com/js05212/NPN) [[Code]](https://github.com/js05212/NPN)

Adversarial Variational Bayes: Unifying Variational Autoencoders and Generative Adversarial Networks<br>
by Mescheder et al., ICML 2017<br>
[[PDF]](https://arxiv.org/pdf/1701.04722.pdf)

Stick-Breaking Variational Autoencoders<br>
by Nalisnick et al., ICLR 2017<br>
[[PDF]](https://openreview.net/forum?id=S1jmAotxg)

Bayesian GAN<br>
by Saatchi et al, NIPS 2017<br>
[[PDF]](https://arxiv.org/abs/1705.09558)

Neural Expectation Maximization<br>
by Greff et al., NIPS 2017<br>
[[PDF]](https://papers.nips.cc/paper/7246-neural-expectation-maximization.pdf)

Lightweight Probabilistic Deep Networks<br>
by Gast et al., CVPR 2018<br>
[[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/html/Gast_Lightweight_Probabilistic_Deep_CVPR_2018_paper.html)

Feed-forward Propagation in Probabilistic Neural Networks with Categorical and Max Layers<br>
by Shekhovtsov et al., ICLR 2018<br>
[[PDF]](https://openreview.net/forum?id=SkMuPjRcKQ)

Glow: Generative Flow with Invertible 1x1 Convolutions<br>
by Kingma et al., NIPS 2018<br>
[[PDF]](https://papers.nips.cc/paper/8224-glow-generative-flow-with-invertible-1x1-convolutions.pdf)

ProbGAN: Towards Probabilistic GAN with Theoretical Guarantees<br>
by He et al., ICLR 2019<br>
[[PDF]](http://wanghao.in/paper/ICLR19_ProbGAN.pdf) [[Project Page]](https://github.com/hehaodele/ProbGAN)

Sampling-free Epistemic Uncertainty Estimation Using Approximated Variance Propagation<br>
by Postels et al., ICCV 2019<br>
[[PDF]](https://arxiv.org/abs/1908.00598)

Efficient and Scalable Bayesian Neural Nets with Rank-1 Factors<br>
by Dusenberry et al., ICML 2020<br>
[[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/5657-Paper.pdf)

Neural Clustering Processes<br>
by Pakman et al., ICML 2020<br>
[[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/3997-Paper.pdf)

Being Bayesian, Even Just a Bit, Fixes Overconfidence in ReLU Networks<br>
by Kristiadi et al., ICML 2020<br>
[[PDF]](https://proceedings.icml.cc/static/paper_files/icml/2020/780-Paper.pdf)

Activation-level Uncertainty in Deep Neural Networks<br>
by Morales-Alvarez et al., ICLR 2021<br>
[[PDF]](https://openreview.net/pdf/6d7935927e30fe5bf2be87f8e871229560145392.pdf)
