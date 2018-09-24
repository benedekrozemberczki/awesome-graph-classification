# Awesome Graph Embedding And Representation Learning Papers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of important graph embedding, classification and representation learning papers with implementations.

The task is to learn features and representations of graphs from a graph database. These are later used for supervised learning.
<p align="center">
  <img width="460" src="atlas.png">
</p>

# Paper References with the implementation(s)
## (Implicit) Factorization machines

- **Anonymous Walk Embeddings (ICML 2018)**
  - Sergey Ivanov, Evgeny Burnaev
  - [[paper]](https://arxiv.org/pdf/1805.11921.pdf)
  - [[Python Reference]](https://github.com/nd7141/AWE)

- **Graph2vec (MLGWorkshop 2017)**
  - Narayanan, Annamalai and Chandramohan, Mahinthan and Chen, Lihui and Liu, Yang and Saminathan, Santhoshkumar
  - [[paper]](https://arxiv.org/abs/1707.05005)
  - [[Python High Performance]](https://github.com/benedekrozemberczki/graph2vec)
  - [[Python Reference]](https://github.com/MLDroid/graph2vec_tf)

- **Subgraph2vec (MLGWorkshop 2016)**
  - Narayanan, Annamalai and Chandramohan, Mahinthan and Chen, Lihui and Liu, Yang and Saminathan, Santhoshkumar
  - [[paper]](https://arxiv.org/abs/1606.08928)
  - [[Python High Performance]](https://github.com/MLDroid/subgraph2vec_gensim)
  - [[Python Reference]](https://github.com/MLDroid/subgraph2vec_tf)
  
- **Deep Graph Kernels (KDD 2015)**
  - Yanardag, Pinar and Vishwanathan, SVN
  - [[paper]](https://dl.acm.org/citation.cfm?id=2783417)
  - [[Python Reference]](https://github.com/pankajk/Deep-Graph-Kernels)

## Spectral and Statistical Fingerprints
 
- **NetLSD (KDD 2018)**
  - Tsitsulin, Anton and Mottin, Davide and Karras, Panagiotis and Bronstein, Alex and Muller, Emmanuel
  - [[paper]](https://arxiv.org/abs/1805.10712)
  - [[Python Reference]](https://github.com/xgfs/NetLSD)
  
- **Hunt For The Unique, Stable, Sparse And Fast Feature Learning On Graphs (NIPS 2017)**
  - Saurabh Verma and Zhi-Li Zhang
  - [[paper]](https://papers.nips.cc/paper/6614-hunt-for-the-unique-stable-sparse-and-fast-feature-learning-on-graphs.pdf)
  - [[Python Reference]](https://github.com/vermaMachineLearning/FGSD)
  
- **NetSimile: A Scalable Approach to Size-Independent Network Similarity (arXiv 2012)**
  - Michele Berlingerio, Danai Koutra, Tina Eliassi-Rad, Christos Faloutsos
  - [[paper]](https://arxiv.org/abs/1209.2684)
  - [[Python]](https://github.com/kristyspatel/Netsimile)
  
 ## Deep Learning
 
- **Deeply Learning Molecular Structure-Property Relationships Using Graph Attention Neural Network (2018)**
  - Seongok Ryu, Jaechang Lim, Woo Youn Kim    
  - [[paper]](https://arxiv.org/abs/1805.10988)
  - [[Python Reference]](https://github.com/SeongokRyu/Molecular-GAT)
  
- **Edge Attention-based Multi-Relational Graph Convolutional Networks (2018)**
  - Chao Shang, Qinqing Liu, Ko-Shin Chen, Jiangwen Sun, Jin Lu, Jinfeng Yi, Jinbo Bi  
  - [[paper]](https://arxiv.org/abs/1802.04944v1)
  - [[Python Reference]](https://github.com/Luckick/EAGCN)
  
- **Commonsense Knowledge Aware Conversation Generation with Graph Attention (IJCAI-ECAI 2018)**
  - Hao Zhou, Tom Yang, Minlie Huang, Haizhou Zhao, Jingfang Xu, Xiaoyan Zhu
  - [[paper]](http://coai.cs.tsinghua.edu.cn/hml/media/files/2018_commonsense_ZhouHao_3_TYVQ7Iq.pdf)
  - [[Python Reference]](https://github.com/tuxchow/ccm)
  
- **An End-to-End Deep Learning Architecture for Graph Classification (AAAI 2018)**
  - Zhang, Muhan and Cui, Zhicheng and Neumann, Marion and Chen, Yixin
  - [[paper]](https://www.cse.wustl.edu/~muhan/papers/AAAI_2018_DGCNN.pdf)
  - [[Python Tensorflow Reference]](https://github.com/muhanzhang/DGCNN)    
  - [[Python Pytorch Reference]](https://github.com/muhanzhang/pytorch_DGCNN)
  
- **Graph Classification Using Structural Attention (KDD 2018)**
  - Lee, John Boaz and Rossi, Ryan and Kong, Xiangnan
  - [[paper]](http://ryanrossi.com/pubs/KDD18-graph-attention-model.pdf)
  
- **SGR: Self-Supervised Spectral Graph Representation Learning (KDD DLDay 2018)**
  - Anton Tsitsulin, Davide Mottin, Panagiotis Karra, Alex Bronstein, Emmanueal Müller
  -[[paper]](https://arxiv.org/abs/1807.02839)
  -[[Python Reference]](http://mott.in/publications/others/sgr/)
  
- **Deep Learning with Topological Signatures (NIPS 2017)**
  - DHofer, Christoph and Kwitt, Roland and Niethammer, Marc and Uhl, Andreas
  - [[paper]](https://arxiv.org/abs/1707.04041)
  - [[Python Reference]](https://github.com/c-hofer/nips2017)
  
- **Graph Classification with 2D Convolutional Neural Networks (2017)**
  - Tixier, Antoine J-P and Nikolentzos, Giannis and Meladianos, Polykarpos and Vazirgiannis, Michalis
  - [[paper]](https://arxiv.org/abs/1708.02218)
  - [[Python Reference]](https://github.com/Tixierae/graph_2D_CNN)
  
- **Semi-supervised Learning of Hierarchical Representations of Molecules Using Neural Message Passing(2017)**
  - Hai Nguyen, Shin-ichi Maeda, Kenta Oono
  - [[paper]](https://arxiv.org/pdf/1711.10168.pdf)
  - [[Python Reference]](https://github.com/pfnet-research/hierarchical-molecular-learning)
  
- **Kernel Graph Convolutional Neural Networks (2017)**
  - Nikolentzos, Giannis and Meladianos, Polykarpos and Tixier, Antoine Jean-Pierre and Skianis, Konstantinos and Vazirgiannis, Michalis
  - [[paper]](https://arxiv.org/pdf/1710.10689.pdf)
  - [[Python Reference]](https://github.com/giannisnik/cnn-graph-classification)
  
- **Deep Topology Classification: A New Approach For Massive Graph Classification (IEEE Big Data 2016)**
  - Bonner, Stephen and Brennan, John and Theodoropoulos, Georgios and McGough, S and Kureshi, I
  - [[paper]](https://ieeexplore.ieee.org/document/7840988/)
  - [[Python Reference]](https://github.com/sbonner0/DeepTopologyClassification)
  
- **Convolutional Networks on Graphs for Learning Molecular Fingerprints (NIPS 2015)**
  - Duvenaud, David K and Maclaurin, Dougal and Iparraguirre, Jorge and Bombarell, Rafael and Hirzel, Timothy and Aspuru-Guzik, Alan and Adams, Ryan P
  - [[paper]](https://papers.nips.cc/paper/5954-convolutional-networks-on-graphs-for-learning-molecular-fingerprints.pdf)
  - [[Python Reference]](https://github.com/fllinares/neural_fingerprints_tf)
  
 ## Kernel Methods
 
- **Message Passing Graph Kernels (2018)**
  - Giannis Nikolentzos, Michalis Vazirgiannis
  - [[paper]](https://arxiv.org/pdf/1808.02510.pdf)
  - [[python Reference]](https://github.com/giannisnik/message_passing_graph_kernels)

- **Matching Node Embeddings for Graph Similarity (AAAI 2017)**
  - Nikolentzos, Giannis and Meladianos, Polykarpos and Vazirgiannis, Michalis
  - [[paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14494)
  - [[Matlab Reference]](http://www.db-net.aueb.gr/nikolentzos/code/matchingnodes.zip)
  
- **Global Weisfeiler-Lehman Graph Kernels (2017)**
  - Morris, Christopher and Kersting, Kristian and Mutzel, Petra
  - [[paper]](https://arxiv.org/pdf/1703.02379.pdf)
  - [[C++ Reference]](https://github.com/chrsmrrs/glocalwl)
  
- **On Valid Optimal Assignment Kernels and Applications to Graph Classification (2016)**
  - Kriege, Nils M and Giscard, Pierre-Louis and Wilson, Richard
  - [[paper]](https://arxiv.org/pdf/1606.01141.pdf)
  - [[Java Reference]](https://github.com/nlskrg/optimal_assignment_kernels)
  
- **Efficient Comparison of Massive Graphs Through The Use Of ‘Graph Fingerprints’ (MLGWorkshop 2016)**
  - Bonner, Stephen and Brennan, John and Theodoropoulos, G and Kureshi, I and McGough, AS
  - [[paper]](http://dro.dur.ac.uk/19773/1/19773.pdf?DDD10+lzdh59+d700tmt)    
  - [[python Reference]](https://github.com/sbonner0/GraphFingerprintComparison)

- **The Multiscale Laplacian Graph Kernel (NIPS 2016)**
  - Kondor, Risi and Pan, Horace
  - [[paper]](https://arxiv.org/abs/1603.06186)
  - [[C++ Reference]](https://github.com/horacepan/MLGkernel) 
  
- **Faster Kernels for Graphs with Continuous Attributes (ICDM 2016)**
  - Morris, Christopher and Kriege, Nils M and Kersting, Kristian and Mutzel, Petra
  - [[paper]](https://arxiv.org/abs/1610.00064)
  - [[python Reference]](https://github.com/chrsmrrs/hashgraphkernel)
  
- **Propagation Kernels: Efficient Graph Kernels From Propagated Information (Machine Learning 2016)**
  - Neumann, Marion and Garnett, Roman and Bauckhage, Christian and Kersting, Kristian
  - [[paper]](https://link.springer.com/article/10.1007/s10994-015-5517-9)
  - [[matlab Reference]](https://github.com/marionmari/propagation_kernels)
  
- **Halting Random Walk Kernels (NIPS 2015)**
  - Sugiyama, Mahito and Borgwardt, Karsten
  - [[paper]](https://pdfs.semanticscholar.org/79ba/8bcfbf9496834fdc22a1f7c96d26d776cd6c.pdf)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels) 

- **Scalable Kernels for Graphs with Continuous Attributes (NIPS 2013)**
  - Feragen, Aasa and Kasenburg, Niklas and Petersen, Jens and de Bruijne, Marleen and Borgwardt, Karsten
  - [[paper]](https://papers.nips.cc/paper/5155-scalable-kernels-for-graphs-with-continuous-attributes.pdf)
  
- **Subgraph Matching Kernels for Attributed Graphs (ICML 2012)**
  - Nils Kriege and Petra Mutzel
  - [[paper]](https://arxiv.org/abs/1206.6483)
  - [[python Reference]](https://github.com/mockingbird2/GraphKernelBenchmark)  
  
- **Nested Subtree Hash Kernels for Large-Scale Graph Classification over Streams (ICDM 2012)**
  - Bin Li, Xingquan Zhu, Lianhua Chi, Chengqi Zhang
  - [[paper]](https://ieeexplore.ieee.org/document/6413884/)
  - [[python Reference]](https://github.com/benedekrozemberczki/NestedSubtreeHash)  
  
- **Weisfeiler-Lehman Graph Kernels (JMLR 2011)**
  - Shervashidze, Nino and Schweitzer, Pascal and Leeuwen, Erik Jan van and Mehlhorn, Kurt and Borgwardt, Karsten M
  - [[paper]](http://www.jmlr.org/papers/volume12/shervashidze11a/shervashidze11a.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)  

- **Fast Neighborhood Subgraph Pairwise Distance Kernel (ICML 2010)**
  - Fast neighborhood subgraph pairwise distance Kernel
  - [[paper]](https://icml.cc/Conferences/2010/papers/347.pdf)
  - [[C++ Reference]](www.bioinf.uni-freiburg.de/~costa/EDeNcpp.tgz)
  - [[python Reference]](https://github.com/fabriziocosta/EDeN)

- **A Linear-time Graph Kernel (ICDM 2009)**
  - Hido, Shohei and Kashima, Hisashi
  - [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5360243)  
  - [[python Reference]](https://github.com/hgascon/adagio)
  
- **Weisfeiler-Lehman Subtree Kernels (NIPS 2009)**
  - Shervashidze, Nino and Schweitzer, Pascal and Leeuwen, Erik Jan van and Mehlhorn, Kurt and Borgwardt, Karsten M
  - [[paper]](http://papers.nips.cc/paper/3813-fast-subtree-kernels-on-graphs.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels) 
  
- **Fast Computation of Graph Kernels (NIPS 2006)**
  - Borgwardt, Karsten M and Schraudolph, Nicol N and Vishwanathan, SVN
  - [[paper]](http://www.dbs.ifi.lmu.de/Publikationen/Papers/VisBorSch06.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)
  
- **Shortest-Path Kernels on Graphs (ICDM 2005)**
  - Borgwardt, Karsten M and Kriegel, Hans-Peter
  - [[paper]](https://www.ethz.ch/content/dam/ethz/special-interest/bsse/borgwardt-lab/documents/papers/BorKri05.pdf)
  - [[C++ Reference]](https://github.com/KitwareMedical/ITKTubeTK)
  
- **Cyclic Pattern Kernels For Predictive Graph Mining (KDD 2004)**
  - Horvath, Tamas and Gartner, Thomas and Wrobel, Stefan
  - [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.332.6158&rep=rep1&type=pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  
- **Extensions of Marginalized Graph Kernels (ICML 2004)**
  - Mahe, Pierre and Ueda, Nobuhisa and Akutsu, Tatsuya and Perret, Jean-Luc and Vert, Jean-Philippe
  - [[paper]](http://members.cbio.mines-paristech.fr/~jvert/publi/04icml/icmlMod.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
  
- **Marginalized Kernels Between Labeled Graphs (ICML 2003)**
  - Kashima, Hisashi and Tsuda, Koji and Inokuchi, Akihiro
  - [[paper]](https://pdfs.semanticscholar.org/2dfd/92c808487049ab4c9b45db77e9055b9da5a2.pdf)
  - [[python Reference]](https://github.com/jajupmochi/py-graph)
