# GenAI4Drug

Repository for the survey paper "A Survey of Generative AI for \textit{de novo} Drug Discovery: New Frontiers in Molecule and Protein Design".

<p align="center">
Xiangru Tang<sup>1</sup>*, Howard Dai<sup>1</sup>*, Elizabeth Knight<sup>1</sup>*, Yunyang Li<sup>1</sup>, Fang Wu<sup>2</sup>, Tianxiao Li<sup>1</sup>, Mark Gerstein<sup>1</sup>
</p> 

<p align="center">
1. Yale University, New Haven; 2. Tsinghua University, China<br>
 (*: Equal Contribution)
</p> 


<p align="center">
  <br>
  <!-- <img src="Survey (1)-03.png" alt="generative AI for drug design" width="500"> -->
  <img src="Survey (1)-03.png" alt="generative AI for drug design">
</p>

An overview of topics covered in our paper. Sections highlighted in blue can be found in the main text, while purple sections are extended sections found in the appendix.  

Below is an organized list of referenced papers, with links to full texts.

# Technical Background 


INSERT TABLE W/ TECH PAPERS

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)  

# Molecule Design 

## Target-Agnostic Generation


### Datasets
* **Quantum chemistry structures and properties of 134 kilo molecules** (QM9)   
 Raghunathan Ramakrishnan, Pavlo O. Dral, Matthias Rupp, O. Anatole von Lilienfeld     
 [Scientific Data (2014)](https://www.nature.com/articles/sdata201422)

* **GEOM, energy-annotated molecular conformations for property prediction and molecular generation** (GEOM)   
Simon Axelrod, Rafael Gómez-Bombarelli   
 [Scientific Data (2022)](https://www.nature.com/articles/s41597-022-01288-4)  


### Metrics

* **Quantifying the chemical beauty of drugs** (QED)    
  G Richard Bickerton, Gaia V Paolini, Jérémy Besnard, Sorel Muresan, Andrew L Hopkins    
  [Nature Chemistry (2012)](https://pubmed.ncbi.nlm.nih.gov/22270643/)


### Models

* **Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules** (CVAE)   
 Rafael Gómez-Bombarelli, Jennifer N. Wei, David Duvenaud, JoséMiguel Hernández-Lobato, BenjamínSánchez-Lengeling, Dennis Sheberla, Jorge Aguilera-Iparraguirre, Timothy D. Hirzel, Ryan P. Adams, and Alán Aspuru-Guzik    
[ACS Central Science (2018)](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00572)

* **Grammar Variational Autoencoder** (GVAE)   
 Matt J. Kusner, Brooks Paige, José Miguel Hernández-Lobato    
[ICML 2017](https://proceedings.mlr.press/v70/kusner17a.html?ref=https://githubhelp.com)

* **Syntax-Directed Variational Autoencoder for Structured Data** (SD-VAE)   
 Hanjun Dai, Yingtao Tian, Bo Dai, Steven Skiena, Le Song    
[ICLR 2018](https://arxiv.org/abs/1802.08786)

* **Junction Tree Variational Autoencoder for Molecular Graph Generation** (JT-VAE)   
 Wengong Jin, Regina Barzilay, Tommi Jaakkola    
[ICML 2018](https://proceedings.mlr.press/v80/jin18a.html)

* **E(n) Equivariant Normalizing Flows** (E-NF)   
 Victor Garcia Satorras, Emiel Hoogeboom, Fabian Fuchs, Ingmar Posner, Max Welling    
[NeurIPS 2021](https://proceedings.neurips.cc/paper_files/paper/2021/hash/21b5680d80f75a616096f2e791affac6-Abstract.html)

* **Symmetry-adapted generation of 3d point sets for the targeted discovery of molecules** (G-SchNet)   
 Niklas Gebauer, Michael Gastegger, Kristof Schütt    
[NeurIPS 2019](https://proceedings.neurips.cc/paper/2019/hash/a4d8e2a7e0d0c102339f97716d2fdfb6-Abstract.html)

* **Equivariant Diffusion for Molecule Generation in 3D** (EDM)   
 Emiel Hoogeboom, Vı́ctor Garcia Satorras, Clément Vignac, Max Welling     
[ICML 2022](https://proceedings.mlr.press/v162/hoogeboom22a.html)

* **Geometry-Complete Diffusion for 3D Molecule Generation and Optimization** (GCDM)   
 Alex Morehead, Jianlin Cheng     
[arXiv:2302.04313 (2023)](https://arxiv.org/abs/2302.04313)

* **MDM: Molecular Diffusion Model for 3D Molecule Generation** (MDM)   
 Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong     
[AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25639)

* **Geometric Latent Diffusion Models for 3D Molecule Generation** (GeoLDM)   
 Minkai Xu, Alexander S Powers, Ron O. Dror, Stefano Ermon, Jure Leskovec    
[ICML 2023](https://proceedings.mlr.press/v202/xu23n.html)

* **Learning Joint 2D & 3D Diffusion Models for Complete Molecule Generation** (JODO)   
 Han Huang, Leilei Sun, Bowen Du, Weifeng Lv       
[arXiv:2305.12347 (2023)](https://arxiv.org/abs/2305.12347)

* **MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation** (MiDi)   
 Clement Vignac, Nagham Osman, Laura Toni, Pascal Frossard           
 [arXiv:2302.09048 (2023)](https://arxiv.org/abs/2302.09048)



## Target-Aware Generation


### Datasets

* **Three-Dimensional Convolutional Neural Networks and a Cross-Docked Data Set for Structure-Based Drug Design** (CrossDocked2020)   
 Paul G. Francoeur, Tomohide Masuda, Jocelyn Sunseri, Andrew Jia, Richard B. Iovanisci, Ian Snyder, David R. Koes    
[ACS JCIM 2020](https://pubs.acs.org/doi/full/10.1021/acs.jcim.0c00411)

* **ZINC20—A Free Ultralarge-Scale Chemical Database for Ligand Discovery** (ZINC20)   
 John J. Irwin, Khanh G. Tang, Jennifer Young, Chinzorig Dandarchuluun, Benjamin R. Wong, Munkhzul Khurelbaatar, Yurii S. Moroz, John Mayfield, Roger A. Sayle     
[ACS JCIM 2020](https://pubs.acs.org/doi/full/10.1021/acs.jcim.0c00675)

* **Binding MOAD (Mother Of All Databases)** (Binding MOAD)   
 Liegi Hu, Mark L. Benson, Richard D. Smith, Michael G. Lerner, Heather A. Carlson      
[Proteins 2005](https://onlinelibrary.wiley.com/doi/full/10.1002/prot.20512)


### Metrics

* **AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading** (Vina AutoDock)   
 Oleg Trott, Arthur J. Olson     
[JCC 2010](https://onlinelibrary.wiley.com/doi/full/10.1002/jcc.21334)

* **Quantifying the chemical beauty of drugs** (QED)
  G Richard Bickerton, Gaia V Paolini, Jérémy Besnard, Sorel Muresan, Andrew L Hopkins    
  [Nature Chemistry (2012)](https://pubmed.ncbi.nlm.nih.gov/22270643/)

* **Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions** (SAScore)   
 Peter Ertl, Ansgar Schuffenhauer 
[Journal of Cheminformatics 2009](https://link.springer.com/article/10.1186/1758-2946-1-8)


### Models





* **DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins** (DrugGPT)   
Yuesen Li, Chengyi Gao, Xin Song, Xiangyu Wang, Yungang Xu, Suxia Han     
[bioRxiv (2023)](https://www.biorxiv.org/content/10.1101/2023.06.29.543848v1.abstract)

* **Generating 3D Molecular Structures Conditional on a Receptor Binding Site with Deep Generative Models** (LiGAN)   
 Tomohide Masuda, Matthew Ragoza, David Ryan Koes       
 [arXiv:2010.14442 (2020)](https://arxiv.org/abs/2010.14442)

* **Pocket2Mol: Efficient Molecular Sampling Based on 3D Protein Pockets** (Pocket2Mol)   
 Xingang Peng, Shitong Luo, Jiaqi Guan, Qi Xie, Jian Peng, Jianzhu Ma      
[ICML 2022](https://proceedings.mlr.press/v162/peng22b.html)

* **A 3D Generative Model for Structure-Based Drug Design** 
  Shitong Luo, Jiaqi Guan, Jianzhu Ma, Jian Peng        
[NeurIPS 2021](https://proceedings.neurips.cc/paper_files/paper/2021/hash/314450613369e0ee72d0da7f6fee773c-Abstract.html)

* **3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction** (TargetDiff)
  Jiaqi Guan, Wesley Wei Qian, Xingang Peng, Yufeng Su, Jian Peng, Jianzhu Ma     
  [ICLR 2023](https://arxiv.org/abs/2303.03543)

* **Structure-based Drug Design with Equivariant Diffusion Models** (DiffSBDD)   
 Arne Schneuing, Yuanqi Du, Charles Harris, Arian Jamasb, Ilia Igashov, Weitao Du, Tom Blundell, Pietro Lió, Carla Gomes, Max Welling, Michael Bronstein, Bruno Correia     
  [arXiv:2210.13695 (2022)](https://arxiv.org/abs/2210.13695)  


## Conformation Generation


### Datasets

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)


### Metrics

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)  

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)


### Models

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)  

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)

* **Paper Title** (Model name)   
 Author1, Author2, ...   
Conference (Year)


# Protein Design


## Representation Learning (appendix)

### Datasets

### Metrics

### Models


## Structure Prediction

### Datasets

### Metrics

### Models


## Generation 

### Datasets

### Metrics

### Models




# Antibody Design (appendix)


## Representation Learning (appendix)

### Datasets

### Metrics

### Models


## Structure Prediction

### Datasets

### Metrics

### Models


## CDR Generation 

### Datasets

### Metrics

### Models
