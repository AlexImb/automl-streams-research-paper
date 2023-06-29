# AutoML Techniques for Data Streams

## Abstract

> Automated Machine Learning (AutoML) techniques benefitted from tremendous research progress recently. These developments and the continuous-growing demand for machine learning experts led to the development of numerous AutoML tools. Industry applications of machine learning on streaming data become more popular due to the increasing adoption of real-time streaming in IoT, microservices architectures, web analytics, and other fields. However, the AutoML tools assume that the entire training dataset is available upfront and that the underlying data distribution does not change over time. These assumptions do not hold in a data-stream-mining setting where an unbounded stream of data cannot be stored and is likely to manifest concept drift. This research surveys the state- of-the-art open-source AutoML tools, applies them to real and synthetic streamed data, and measures how their per- formance changes over time. For comparative purposes, batch, batch incremental and instance incremental estimators are applied and compared. Moreover, a meta-learning technique for online algorithm selection based on meta-feature extraction is proposed and compared, while model replacement and continual AutoML techniques are discussed. The results show that off-the-shelf AutoML tools can provide satisfactory results but in the presence of concept drift, detection or adaptation techniques have to be applied to maintain the predictive accuracy over time.

## Paper

https://arxiv.org/abs/2106.07317

```bibtex
@article{DBLP:journals/corr/abs-2106-07317,
  author       = {Alexandru{-}Ionut Imbrea},
  title        = {Automated Machine Learning Techniques for Data Streams},
  journal      = {CoRR},
  volume       = {abs/2106.07317},
  year         = {2021},
  url          = {https://arxiv.org/abs/2106.07317},
  eprinttype    = {arXiv},
  eprint       = {2106.07317},
  timestamp    = {Wed, 16 Jun 2021 10:42:19 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2106-07317.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
