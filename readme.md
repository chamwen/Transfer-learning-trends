# Trends of transfer learning

[![](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)
[![](https://img.shields.io/github/last-commit/chamwen/Transfer-learning-trends)](https://github.com/chamwen/Transfer-learning-trends/commits/master)

The resources focus on the latest papers in arXiv, some useful sources, the excellent scholars, and most importantly, the trends of transfer learning from top conferences and journals. You are welcome to pull any requests as you will. I'll sort out the content soon.

- [Trends of transfer learning](#trends-of-transfer-learning)
  * [New papers in arXiv](#new-papers-in-arXiv)
  * [Useful websites](#useful-websites)
  * [Other githubs](#other-githubs)
  * [Excellent Scholars](#excellent-scholars)
  * [Trend papers](#trend-papers)
    * [Year 2020](#year-2020)
    * [Year 2019](#year-2019)

## New papers in arXiv

- [Topic: transfer learning](http://arxitics.com/search?q=transfer%20learning&sort=updated#1904.01376/abstract)
- [Topic: domain adaptation](http://arxitics.com/search?q=domain%20adaptation&sort=updated)
- [Topic: domain generalization](http://arxitics.com/search?q=domain%20generalization&sort=updated)

## Useful websites

- [Computer Vision Foundation](https://openaccess.thecvf.com/menu)
- [Paperswithcode (friendly for reproduction)](https://www.paperswithcode.com/task/transfer-learning/latest)
- [VALSE 2020 Panel 迁移学习：他山之石，可以攻玉](https://b23.tv/JyX0z2)
- [ICCV19: Domain Adaptation Oral Session Video](https://www.youtube.com/watch?v=9Sx2qWKGzlc)

## Other githubs

- [Transfer Learning](https://github.com/jindongwang/transferlearning)
- [Awesome Domain Adaptation](https://github.com/zhaoxin94/awsome-domain-adaptation#distance-based-methods)
- [Awesome Transfer Learning](https://github.com/artix41/awesome-transfer-learning)
- [Materials for transfer learning](https://github.com/dududuAA/Transfer-learning-materials)

## Excellent scholars

|Scholar|Scholar|Scholar|
| :--: | :--: | :--: |
|[Qiang Yang](http://home.cse.ust.hk/~qyang/)|[Sinno Jialin Pan NTU](https://www.ntu.edu.sg/home/sinnopan/index.html)|[龙明盛 清华大学](http://ise.thss.tsinghua.edu.cn/~mlong/)|
|[Boqing Gong Google](http://boqinggong.info/index.html)|[庄福振 中科院计算所](http://www.intsci.ac.cn/users/fzzhuang/index.html)|[李文 ETH](http://www.vision.ee.ethz.ch/~liwenw/)|
|[张宇 南方科技大学](https://yuzhanghk.github.io/)|[张磊 重庆大学](http://www.leizhang.tk/)|[Lixin Duan Amazon](http://www.lxduan.info/)|
|[Sheng Li  Univ. of Georgia](http://cobweb.cs.uga.edu/~shengli/)|[Zhengming Ding Purdue Univ.](http://allanding.net/)|[Judy Hoffman Georgia Tech](https://www.cc.gatech.edu/~judy/)|
|[Meina Kan ICT, CAS](http://vipl.ict.ac.cn/homepage/mnkan/index.html)|[Kate Saenko Boston Univ.](http://ai.bu.edu/ksaenko.html)|[Jian Liang NUS](https://liangjian.xyz/)|
|[Mingkui Tan SCUT](https://tanmingkui.github.io/)|[Kuniaki Saito Boston Univ.](http://cs-people.bu.edu/keisaito/)|[Jing Zhang Beihang Univ.](https://hellojing89.github.io/)|
|[Jindong Wang Microsoft Research](http://jd92.wang/)|[Zhao Han CMU](https://www.cs.cmu.edu/~hzhao1/)|[Hao Lu HUST](https://sites.google.com/site/poppinace/)|

## Trend papers

### Year 2020

| Title | Conf./Journal | Code | Keywords | Benefit |
| ----  | :--: | :--: | :--: | ---- |
|LEEP: A New Measure to Evaluate Transferability of Learned Representations ([paper](https://arxiv.org/pdf/2002.12462.pdf))|ICML 2020||new metric for transferability|negative transfer|
|Label-Noise Robust Domain Adaptation ([paper](https://proceedings.icml.cc/book/3555.pdf))|ICML2020||label noise||
|Estimating Generalization under Distribution Shifts via Domain-Invariant Representations ([paper](http://people.csail.mit.edu/stefje/papers/chuang_icml20.pdf))|ICML 2020|[code](https://github.com/chingyaoc/estimating-generalization)|new theory|**recommend**|
|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation ([paper](https://arxiv.org/abs/2002.08546))|ICML 2020|[code](https://github.com/tim-learn/SHOT)|source-free DA |**new trend**|
|Graph Optimal Transport for Cross-Domain Alignment ([paper](https://arxiv.org/pdf/2006.14744v2.pdf))|ICML 2020||optimal transport| connection with GCN |
|Understanding Self-Training for Gradual Domain Adaptation ([paper](https://proceedings.icml.cc/book/4289.pdf))|ICML 2020||gradual DA|**new trend**|
|Continuously Indexed Domain Adaptation ([paper](https://proceedings.icml.cc/book/3462.pdf))|ICML 2020||domain index distribution|new direction|
|Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation ([paper](https://arxiv.org/pdf/2006.04996.pdf))|ICML 2020|[code](https://github.com/xiangdal/implicit_alignment)|Implicit alignment|**recommend**|
|Self-supervised Label Augmentation via Input Transformations ([paper](https://proceedings.icml.cc/book/3568.pdf))|ICML 2020|[code](https://github.com/hankook/SLA)|self-supervised|ideas can be used to many tasks|
|Open Compound Domain Adaptation ([paper](https://liuziwei7.github.io/projects/CompoundDomain.html))|CVPR 2020|[code](https://github.com/zhmiao/OpenCompoundDomainAdaptation-OCDA)|real life open compound transfer|**new trend**|
|Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective ([paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jamal_Rethinking_Class-Balanced_Methods_for_Long-Tailed_Visual_Recognition_From_a_Domain_CVPR_2020_paper.pdf))|CVPR 2020||DA in long-tailed data|**new trend**|
|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering ([paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf))|CVPR 2020|[code](https://github.com/huitangtang/SRDC-CVPR2020)|cluster||
|Model Adaptation: Unsupervised Domain Adaptation without Source Data ([paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.pdf))|CVPR 2020||privacy|**new problem**|
|Towards Inheritable Models for Open-Set Domain Adaptation ([paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Kundu_Towards_Inheritable_Models_for_Open-Set_Domain_Adaptation_CVPR_2020_paper.html))|CVPR 2020|[code](https://sites.google.com/view/inheritune)|open set DA||
|Extending and Analyzing Self-Supervised Learning Across Domains ([paper](https://arxiv.org/pdf/2004.11992.pdf))|ECCV 2020||self-supervised||
|Collaborative Graph Convolutional Networks: Unsupervised Learning Meets Semi-Supervised Learning ([paper](https://aaai.org/Papers/AAAI/2020GB/AAAI-HuiB.2513.pdf))|AAAI 2020 ||GCN||
|Discriminative Adversarial Domain Adaptation ([paper](https://arxiv.org/abs/1911.12036))|AAAI 2020|[code](https://github.com/huitangtang/DADA-AAAI2020)| discriminative information|**recommend**|
|Multi-Source Distilling Domain Adaptation ([paper](https://arxiv.org/abs/1911.11554))|AAAI 2020||multi-source||
|Unsupervised Domain Adaptive Graph Convolutional Networks ([paper](https://shiruipan.github.io/publication/www-2020-wu/))|WWW 2020||GCN+DA||
|Visualizing Transfer Learning ([paper](https://arxiv.org/abs/2007.07628))|WHI 2020|[code](http://35.158.68.186/lucid.html)|visualize properties|interesting|
|A survey on domain adaptation theory: Learning bounds and theoretical guarantees ([paper](https://arxiv.org/pdf/2004.11829.pdf))|arXiv 2020||theory|**recommend**|
|Do Adversarially Robust ImageNet Models Transfer Better? ([paper](https://arxiv.org/pdf/2007.08489.pdf))|arXiv 2020|[code](https://github.com/Microsoft/robust-models-transfer)|transferability|good question|

### Year 2019

| Title | Conf./Journal | Code | Keywords | Benefit |
| ----  | :--: | :--: | :--: | ---- |
|Catastrophic Forgetting Meets Negative Transfer: Batch Spectral Shrinkage for Safe Transfer Learning ([paper](https://papers.nips.cc/paper/8466-catastrophic-forgetting-meets-negative-transfer-batch-spectral-shrinkage-for-safe-transfer-learning))|NIPS 2019||negative and safe TL|**recommend**|
|Transferable Normalization: Towards Improving Transferability of Deep Neural Networks ([paper](https://papers.nips.cc/paper/8470-transferable-normalization-towards-improving-transferability-of-deep-neural-networks))|NIPS 2019|[code](http://github.com/thuml/TransNorm)|new normalization||
|On the Value of Target Data in Transfer Learning ([paper](https://papers.nips.cc/paper/9179-on-the-value-of-target-data-in-transfer-learning))|NIPS 2019||sampling costs|**recommend**|
|Learning search spaces for Bayesian optimization: Another view of hyperparameter transfer learning ([paper](https://papers.nips.cc/paper/9438-learning-search-spaces-for-bayesian-optimization-another-view-of-hyperparameter-transfer-learning))|NIPS 2019||Bayesian optimization||
|Learning classifiers for target domain with limited or no labels ([paper](http://proceedings.mlr.press/v97/zhu19d.html))|ICML 2019|[code](https://github.com/pengkaizhu/LDVA)|zero/few shot learning||
|Learning What and Where to Transfer ([paper](http://proceedings.mlr.press/v97/jang19b/jang19b.pdf))|ICML 2019||meta-TL|**new trend**|
|On Learning Invariant Representation for Domain Adaptation ([paper](http://proceedings.mlr.press/v97/zhao19a/zhao19a.pdf))|ICML 2019||theory||
|Do better ImageNet models transfer better? ([paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Kornblith_Do_Better_ImageNet_Models_Transfer_Better_CVPR_2019_paper.html))|CVPR 2019||transferability|good question|
|Transferable Curriculum for Weakly-Supervised Domain Adaptation ([paper](https://caozhangjie.github.io/files/TCL19.pdf))|AAAI 2019||curriculum learning+DA||
|Parameter Transfer Unit for Deep Neural Networks ([paper](https://arxiv.org/abs/1804.08613))|PAKDD 2019||new unit|good idea|

### Contact

- **Wen Zhang** - wenzn9 [at] gmail.com

If you are interested in contributing to this repository, welcome to contact me by e-mail.