# Awesome Graph Embedding And Representation Learning Papers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of important graph embedding, classification and representation learning papers with implementations.

The task is to learn features and representations of graphs from a graph database. These are later used for supervised learning.

<img src="atlas.png" width="480">

# Paper References with the implementation(s)
## (Implicit) Factorization machines

- **Graph2vec (MLGWorkshop 2017)**
  - graph2vec: Learning Distributed Representations of Graphs
  - [[paper]](https://arxiv.org/abs/1707.05005)
  - [[Python High Performance]](https://github.com/benedekrozemberczki/graph2vec)
  - [[Python Reference]](https://github.com/MLDroid/graph2vec_tf)

- **Subgraph2vec (MLGWorkshop 2016)**
  - subgraph2vec: Learning Distributed Representations of Rooted Sub-graphs from Large Graphs
  - [[paper]](https://arxiv.org/abs/1606.08928)
  - [[Python High Performance]](https://github.com/MLDroid/subgraph2vec_gensim)
  - [[Python Reference]](https://github.com/MLDroid/subgraph2vec_tf)
  
- **Deep Graph Kernels (KDD 2015)**
  - Deep Graph Kernels
  - [[paper]](https://dl.acm.org/citation.cfm?id=2783417)
  - [[Python Reference]](https://github.com/pankajk/Deep-Graph-Kernels)
  
- **Matching Node Embeddings for Graph Similarity (AAAI 2017)**
  - Matching Node Embeddings for Graph Similarity
  - [[paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14494)
  - [[Matlab Reference]](http://www.db-net.aueb.gr/nikolentzos/code/matchingnodes.zip)

  
## Spectral Methods
 
- **NetLSD (KDD 2018)**
  - NetLSD: Hearing the Shape of a Graph
  - [[paper]](https://arxiv.org/abs/1805.10712)
  - [[Python Reference]](https://github.com/xgfs/NetLSD)
  
 ## Deep Learning
 
- **Graph Classification with 2D Convolutional Neural Networks (2017)**
  - Graph Classification with 2D Convolutional Neural Networks
  - [[paper]](https://arxiv.org/abs/1708.02218)
  - [[Python Reference]](https://github.com/Tixierae/graph_2D_CNN)
  
- **Kernel Graph Convolutional Neural Networks (2017)**
  - Kernel Graph Convolutional Neural Networks
  - [[paper]](https://arxiv.org/pdf/1710.10689.pdf)
  - [[Python Reference]](https://github.com/giannisnik/cnn-graph-classification)
  
- **Convolutional Networks on Graphs for Learning Molecular Fingerprints (NIPS 2015)**
  - Convolutional Networks on Graphs for Learning Molecular Fingerprints
  - [[paper]](https://papers.nips.cc/paper/5954-convolutional-networks-on-graphs-for-learning-molecular-fingerprints.pdf)
  - [[Python Reference]](https://github.com/fllinares/neural_fingerprints_tf)
  
- **Deep Learning with Topological Signatures (NIPS 2017)**
  - Deep Learning with Topological Signatures
  - [[paper]](https://arxiv.org/abs/1707.04041)
  - [[Python Reference]](https://github.com/c-hofer/nips2017)
 
- **Graph Classification Using Structural Attention (KDD 2018)**
  - Graph Classification Using Structural Attention
  - [[paper]](http://ryanrossi.com/pubs/KDD18-graph-attention-model.pdf)
  
 ## Kernel Methods
 
- **Global Weisfeiler-Lehman Graph Kernels (2017)**
  - Global Weisfeiler-Lehman Graph Kernels
  - [[paper]](https://arxiv.org/pdf/1703.02379.pdf)
  - [[C++ Reference]](https://github.com/chrsmrrs/glocalwl)
  
- **On Valid Optimal Assignment Kernels and Applications to Graph Classification (2016)**
  - On Valid Optimal Assignment Kernels and Applications to Graph Classification
  - [[paper]](https://arxiv.org/pdf/1606.01141.pdf)
  - [[Java Reference]](https://github.com/nlskrg/optimal_assignment_kernels)
  
- **Shortest-Path Kernels on Graphs (ICDM 2005)**
  - Shortest-Path Kernels on Graphs
  - [[paper]](https://www.ethz.ch/content/dam/ethz/special-interest/bsse/borgwardt-lab/documents/papers/BorKri05.pdf)
  - [[C++ Reference]](https://github.com/KitwareMedical/ITKTubeTK)
  
  
- **Fast Neighborhood Subgraph Pairwise Distance Kernel (ICML 2010)**
  - Fast neighborhood subgraph pairwise distance Kernel
  - [[paper]](https://icml.cc/Conferences/2010/papers/347.pdf)
  - [[C++ Reference]](www.bioinf.uni-freiburg.de/~costa/EDeNcpp.tgz)
  - [[python Reference]](https://github.com/fabriziocosta/EDeN)
  
  
- **Cyclic Pattern Kernels For Predictive Graph Mining (KDD 2004)**
  - Cyclic Pattern Kernels For Predictive Graph Mining
  - [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.332.6158&rep=rep1&type=pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  
- **Extensions of Marginalized Graph Kernels (ICML 2004)**
  - Extensions of Marginalized Graph Kernels
  - [[paper]](http://members.cbio.mines-paristech.fr/~jvert/publi/04icml/icmlMod.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  
- **Marginalized Kernels Between Labeled Graphs (ICML 2003)**
  - Marginalized Kernels Between Labeled Graphs 
  - [[paper]](https://pdfs.semanticscholar.org/2dfd/92c808487049ab4c9b45db77e9055b9da5a2.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  
- **Random Walk Kernels (NIPS 2006)**
  - Fast Computation of Graph Kernels
  - [[paper]](http://www.dbs.ifi.lmu.de/Publikationen/Papers/VisBorSch06.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)
  
- **Weisfeiler-Lehman Subtree Kernels(NIPS 2009)**
  - Fast subtree kernels on graphs
  - [[paper]](http://papers.nips.cc/paper/3813-fast-subtree-kernels-on-graphs.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)  


- **Weisfeiler-Lehman Graph Kernels (JMLR 2011)**
  - Weisfeiler-Lehman Graph Kernels
  - [[paper]](http://www.jmlr.org/papers/volume12/shervashidze11a/shervashidze11a.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)  

