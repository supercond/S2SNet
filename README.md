# S2SNet

This is the repo for S2SNet: A Pretrained Neural Network for Superconductivity Discovery

Superconductivity allows electrical current to flow without any energy loss, and thus making solids superconducting is a grand goal of physics, material science, and electrical engineering. More than 16 Nobel Laureates have been awarded for their contribution in superconductivity research. Superconductors are valuable  for sustainable development goals (SDGs), such as climate change mitigation, affordable and clean energy, industry, innovation and infrastructure, and so on. However, a unified physics theory explaining all superconductivity mechanism is still unknown. It is believed that superconductivity is microscopically due to not only molecular compositions but also the geometric crystal structure. Hence a new dataset, S2S, containing both crystal structures and superconducting critical temperature, is built upon SuperCon and Material Project. Based on this new dataset, we propose a novel model, S2SNet, which utilizes the attention mechanism for superconductivity prediction. To overcome the shortage of data, S2SNet is pre-trained on the whole Material Project dataset with Masked-Language Modeling (MLM). S2SNet makes a new state-of-the-art, with out-of-sample accuracy of 92\% and Area Under Curve (AUC) of 0.92.

## Citation
```
@inproceedings{DBLP:conf/ijcai/LiuYZX22,
  author    = {Ke Liu, Kaifan Yang, Jiahong Zhang, Renjun Xu},
  title     = {Semi-supervised User Profiling with Heterogeneous Graph Attention
               Networks},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-22}},
  year      = {2022}
}
```