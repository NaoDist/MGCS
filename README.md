# MGCS

《Exploring Multi-granularity Contextual Semantics for Fully Inductive Knowledge Graph Completion》

Code structure：
Data: All datasets used in this work, including training, validation, and test sets

Script: Code for this work, which contains training and testing scripts



## Requirements:
- [huggingface transformer 3.3.1](https://github.com/huggingface/transformers)
- [pytorch 1.5.0](https://pytorch.org/)
- networkx 2.5
- tqdm
- numpy
- sklearn
- ipdb

How to train:

1. python script/train.py


How to test:

1. python script/test.py

More details can be found in the code, please contact us if you have any questions!


## Baselines
We use code provided by authors for baselines in our experiments.
RuleN is a ruled-based method. Detailed instructions can be found [here](http://web.informatik.uni-mannheim.de/RuleN/).
GraIL is subgraph reasoning method. Detailed instructions can be found [here](https://github.com/kkteru/grail).
