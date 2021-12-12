A baseline implementation of Graph Conjoint Attention Networks (CATs) for semi-supervised node classification, that has been proposed in our paper:

Tiantian He, Yew-Soon Ong, and Lu Bai, "Learning Conjoint Attentions for Graph Neural Nets," NeurIPS 2021.

Requirements:
Python (>=3.8)
PyTorch (>=1.8.1)
DGL (0.6.1)

Some preliminary results (As there are no pre/post process or early stopping control and different GPU/CUDA platforms are used, the results might be slightly different from those reported in the paper):
Cora: ~0.849, Cite: ~0.726, Pubmed: ~0.834
