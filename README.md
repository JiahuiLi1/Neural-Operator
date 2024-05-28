# Neural-Operator
This is a collection of research papers on neural operators. 

## Update Log

- **[2024.05.18]** We update the ICML 2023 and ICLR 2023 paper list of neural operator.
- **[2024.05.15]** We update the NeurIPS 2023 paper list of neural operator.
- **[2024.05.10]** We release the awesome neural operator.

## Table of Contents
- [Classification of neural operator networks](#classification-of-neural-operator-networks)
- [Papers](#papers)
  - [Sub-journal of nature](#sub-journal-of-nature)
  - [ICLR 2024](#iclr-2024)
  - [ICML 2024](#icml-2024)
  - [JMLR 2024](#jmlr-2024)
  - [NeurIPS 2023](#neurips-2023)
  - [ICML 2023](#icml-2023)
  - [ICLR 2023](#iclr-2023)
  - [NeurIPS 2022](#neurips-2022)
  - [ICML 2022](#icml-2022)
  - [ICLR 2022](#iclr-2022)
  - [NeurIPS 2021](#neurips-2021)
  - [ICLR 2021](#iclr-2021)
  - [ICML 2021](#icml-2021)
  - [JMLR 2021](#jmlr-2021)
  - [Other](#other)
- [Tutorial](#tutorial)
- [Codebase](#codebase)
- [Contributing](#contributing)

## Classification of neural operator networks
We’ll start this section with a disclaimer:

## Papers
### Sub-journal of nature

<details>
<summary>Toggle</summary>

  - [Neural operators for accelerating scientific simulations and design](https://www.nature.com/articles/s42254-024-00712-5)
    - Kamyar Azizzadenesheli, Nikola Kovachki, Zongyi Li, Miguel Liu-Schiaffini, Jean Kossaifi & Anima Anandkumar
    - Key: dyna architecture
    - ExpEnv: None

  - [Adaptive physics-informed neural operator for coarse-grained non-equilibrium flows](https://www.nature.com/articles/s41598-023-41039-y)
    - Ivan Zanardi, SimoneVenturi  & Marco Panesi
    - Key: The framework combines dimensionality reduction and neural operators; hierarchical and adaptive deep learning strategy 
    - ExpEnv: Te code used in the current study is available from the corresponding author upon reasonable request.

</details>


### ICLR 2024

<details>
<summary>Toggle</summary>

  - [Title]()
    - 
    - Key: 
    - ExpEnv: 
  
</details>


### ICML 2024

<details>
<summary>Toggle</summary>

  - [Transolver: A Fast Transformer Solver for PDEs on General Geometries](https://arxiv.org/pdf/2402.02366)
    - Haixu Wu, Huakun Luo, Haowen Wang, Jianmin Wang, Mingsheng Long
    - Key: Physics-Attention; Transformer
    - ExpEnv: None
  
</details>


### JMLR 2024
<details>
<summary>Toggle</summary>

  - [Text]()
    - 
    - Key: 
    - ExpEnv: None
  
</details>


### NeurIPS 2023

<details>
<summary>Toggle</summary>
<ul>
  
  <li>
    <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/dc35c593e61f6df62db541b976d09dcf-Paper-Conference.pdf">Representation Equivalent Neural Operators: a Framework for Alias-free Operator Learning</a>
    <ul>
      <li>Francesca Bartolucci, Emmanuel de Bézenac, Bogdan Raonic, Roberto Molinaro, Siddhartha Mishra, Rima Alaifari</li>
      <li>Key: operator learning; Representation equivalent Neural Operators (ReNO); the concept of operator aliasing</li>
      <li>ExpEnv: <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/dc35c593e61f6df62db541b976d09dcf-Supplemental-Conference.pdf"> Supplemental</a>
    </ul>
  </li>
  
  <li>
    <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/70518ea42831f02afc3a2828993935ad-Paper-Conference.pdf">Geometry-Informed Neural Operator for Large-Scale 3D PDEs</a>
    <ul>
      <li>Zongyi Li, Nikola Kovachki, Chris Choy, Boyi Li, Jean Kossaifi, Shourya Otta, Mohammad Amin Nabian, Maximilian Stadler, Christian Hundt, Kamyar Azizzadenesheli, Animashree Anandkumar</li>
      <li>Key: geometry-informed neural operator (GINO)</li>
      <li>ExpEnv: <a href="https://openreview.net/forum?id=86dXbqT5Ua">Codes</a></li>
    </ul>
  </li>

  <li>
  <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/f3c1951b34f7f55ffaecada7fde6bd5a-Paper-Conference.pdf">Convolutional Neural Operators for robust and accurate learning of PDEs</a>
  <ul>
    <li>Bogdan Raonic, Roberto Molinaro, Tim De Ryck, Tobias Rohner, Francesca Bartolucci, Rima Alaifari, Siddhartha Mishra, Emmanuel de Bézenac</li>
    <li>Key: convolutional neural operators (CNOs)</li>
    <li>ExpEnv: <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/f3c1951b34f7f55ffaecada7fde6bd5a-Supplemental-Conference.pdf">Supplemental</a></li>
  </ul>
  </li>

  <li>
  <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/940a7634dab556b67af15bacd337f7db-Paper-Conference.pdf">Domain Agnostic Fourier Neural Operators</a>
  <ul>
    <li>Ning Liu, Siavash Jafarzadeh, Yue Yu</li>
    <li>Key: convolutional neural operators (CNOs)</li>
    <li>ExpEnv: <a href="https://github.com/ningliu-iga/DAFNO">Codes</a>;<a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/940a7634dab556b67af15bacd337f7db-Supplemental-Conference.pdf">Supplemental </li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/d899a31938c7838965b589d9b14a5ca6-Paper-Conference.pdf">ASPEN: Breaking Operator Barriers for Efficient Parallelization of Deep Neural Networks</a>
  <ul>
    <li>Jongseok Park, Kyungmin Bin, Gibum Park, Sangtae Ha, Kyunghan Lee</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://github.com/cakeng/ASPEN
  </ul>">Codes</a></li>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/b40d5797756800c97f3d525c2e4c8357-Paper-Conference.pdf">Globally injective and bijective neural operators</a>
  <ul>
    <li>Takashi Furuya, Michael Puthawala, Matti Lassas, Maarten V. de Hoop</li>
    <li>Key: Fredholm theory and Leray-Schauder degree  theory</li>
    <li>ExpEnv: None</li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/32cc61322f1e2f56f989d29ccc7cfbb7-Paper-Conference.pdf">Deep Equilibrium Based Neural Operators for Steady-State PDEs</a>
  <ul>
    <li>Tanya Marwah, Ashwini Pokle, J. Zico Kolter, Zachary Lipton, Jianfeng Lu, Andrej Risteski</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://github.com/risteskilab/deq-neural-operators">Codes; <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/32cc61322f1e2f56f989d29ccc7cfbb7-Supplemental-Conference.pdf">Supplemental</a></li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/c362fbc0d182c6b4b8dadb90177239e4-Paper-Conference.pdf">Equivariant Neural Operator Learning with Graphon Convolution</a>
  <ul>
    <li>Chaoran Cheng, Jian Peng</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://github.com/ccr-cheng/InfGCN-pytorch">Codes; <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/c362fbc0d182c6b4b8dadb90177239e4-Supplemental-Conference.pdf">Supplemental</a></li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/57d7e7e1593ad1ab6818c258fa5654ce-Paper-Conference.pdf">Training neural operators to preserve invariant measures of chaotic attractors</a>
  <ul>
    <li>Ruoxi Jiang, Peter Y. Lu, Elena Orlova, Rebecca Willett</li>
    <li>Key: </li>
    <li>ExpEnv: href="https://github.com/roxie62/neural_operators_for_chaos">Codes</li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/948d8ba4e30c8c3a800cf436b31f376e-Paper-Conference.pdf">DeepPCR: Parallelizing Sequential Operations in Neural Networks</a>
  <ul>
    <li>Federico Danieli, Miguel Sarabia, Xavier Suau Cuadros, Pau Rodriguez, Luca Zappella</li>
    <li>Key: </li>
    <li>ExpEnv: None</li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2023/file/df54302388bbc145aacaa1a54a4a5933-Paper-Conference.pdf">Operator Learning with Neural Fields: Tackling PDEs on General Geometries</a>
  <ul>
    <li>Louis Serrano, Lise Le Boudec, Armand Kassaï Koupaï, Thomas X Wang, Yuan Yin, Jean-Noël Vittaut, Patrick Gallinari</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://papers.nips.cc/paper_files/paper/2023/file/df54302388bbc145aacaa1a54a4a5933-Supplemental-Conference.pdf">Supplemental</a></li>
  </ul>
  </li>
</ul>

 - [text]()
    - 
    - Key: 
    - ExpEnv: []()


</details>


### ICML 2023
<details>
<summary>Toggle</summary>

  - [Variational Autoencoding Neural Operators](https://proceedings.mlr.press/v202/seidman23a/seidman23a.pdf)
    - Jacob H. Seidman · Georgios Kissas · George J. Pappas · Paris Perdikaris
    - Key: Variational Autoencoding Neural Operators (VANO)
    - ExpEnv: [Poster](https://icml.cc/media/PosterPDFs/ICML%202023/23841.png?t=1690223752.947732)

  - [Group Equivariant Fourier Neural Operators for Partial Differential Equations](https://proceedings.mlr.press/v202/helwig23a/helwig23a.pdf)
    - Jacob Helwig · Xuan Zhang · Cong Fu · Jerry Kurtin · Stephan Wojtowytsch · Shuiwang Ji
    - Key: Fourier neural operators (FNOs) in the frequency domain
    - ExpEnv: [Poster](https://icml.cc/media/PosterPDFs/ICML%202023/23875.png?t=1690367726.8107066); [Codes](https://github.com/divelab/AIRS)

  - [GNOT: A General Neural Operator Transformer for Operator Learning](https://proceedings.mlr.press/v202/hao23c/hao23c.pdf)
    - Zhongkai Hao · Zhengyi Wang · Hang Su · Chengyang Ying · Yinpeng Dong · LIU SONGMING · Ze Cheng · Jian Song · Jun Zhu
    - Key: general neural operator transformer (GNOT)
    - ExpEnv: [Poster](https://icml.cc/media/PosterPDFs/ICML%202023/23985.png?t=1687699316.6204455); [Codes](https://github.com/thu-ml/GNOT)

  - [Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere](https://icml.cc/virtual/2023/poster/23618)
    - Zhongkai Hao · Zhengyi Wang · Hang Su · Chengyang Ying · Yinpeng Dong · LIU SONGMING · Ze Cheng · Jian Song · Jun Zhu
    - Key: Spherical FNOs (SFNOs)
    - ExpEnv: [Poster](https://icml.cc/media/PosterPDFs/ICML%202023/23618.png?t=1687551230.861696);


</details>

### ICLR 2023
<details>
<summary>Toggle</summary>

  - [Factorized Fourier Neural Operators](https://openreview.net/forum?id=tmIiMPl4IPa)
    - Alasdair Tran, Alexander Mathews, Lexing Xie, Cheng Soon Ong
    - Key: fourier transform, fourier operators, pde, navier stokes
    - ExpEnv: [Poster](https://iclr.cc/media/PosterPDFs/ICLR%202023/10680.png?t=1682231612.5224264); [Codes](https://github.com/alasdairtran/fourierflow)

  - [Equivariant Hypergraph Diffusion Neural Operators](https://openreview.net/forum?id=RiTjKoscnNd)
    - Peihao Wang, Shenghao Yang, Yunyu Liu, Zhangyang Wang, Pan Li
    - Key: Hypergraph Neural Network, Hypergraph Diffusion, Equivariant Network
    - ExpEnv: [Poster](https://iclr.cc/media/PosterPDFs/ICLR%202023/11538.png?t=1681877335.71331); [Codes](https://github.com/Graph-COM/ED-HNN)

  - [Koopman Neural Operator Forecaster for Time-series with Temporal Distributional Shifts](https://openreview.net/forum?id=kUmdmHxK5N)
    - Rui Wang, Yihe Dong, Sercan O Arik, Rose Yu
    - Key: Time series forecasting, Temporal distributional shifts, Koopman Theory
    - ExpEnv: [Poster](https://iclr.cc/media/PosterPDFs/ICLR%202023/11432.png?t=1682008054.8302052);


</details>

### NeurIPS 2022
<details>
<summary>Toggle</summary>
<ul>
  
  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2022/file/5ddfb189c022a317ff1c72e6639079de-Paper-Conference.pdf">NeurOLight: A Physics-Agnostic Neural Operator Enabling Parametric Photonic Device Simulation</a>
  <ul>
    <li>Jiaqi Gu, Zhengqi Gao, Chenghao Feng, Hanqing Zhu, Ray Chen, Duane Boning, David Pan</li>
    <li>Key: </li>
    <li>ExpEnv: none</li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2022/file/6cdd4ce9330025967dd1ed0bed3010f5-Paper-Conference.pdf">Operative dimensions in unconstrained connectivity of recurrent neural networks</a>
  <ul>
    <li>Jiaqi Gu, Zhengqi Gao, Chenghao Feng, Hanqing Zhu, Ray Chen, Duane Boning, David Pan</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://gitlab.com/neuroinf/operativeDimensions">operativeDimensions</a></li>
  </ul>
  </li>


</ul>
</details>

### ICML 2022
<details>
<summary>Toggle</summary>

  - []()
    - 
    - Key: 
    - ExpEnv: 


</details>

### ICLR 2022
<details>
<summary>Toggle</summary>

  - [Efficient Token Mixing for Transformers via Adaptive Fourier Neural Operators](https://openreview.net/forum?id=EXHG-A3jlM)
    - John Guibas, Morteza Mardani, Zongyi Li, Andrew Tao, Anima Anandkumar, Bryan Catanzaro
    - Key: self attention, linear complexity, high-resolution inputs, operator learning, Fourier transform
    - ExpEnv: None


</details>

### NeurIPS 2021
<details>
<summary>Toggle</summary>
<ul>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2021/file/eaa1da31f7991743d18dadcf5fd1336f-Paper.pdf">Faster Neural Network Training with Approximate Tensor Operations</a>
  <ul>
    <li>Menachem Adelman, Kfir Levy, Ido Hakimi, Mark Silberstein</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://openreview.net/forum?id=Rz-hPxb6ODl">Reviews And Public Comment</a></li>
  </ul>
  </li>

  <li>
  <a href="https://papers.nips.cc/paper_files/paper/2021/file/84fdbc3ac902561c00871c9b0c226756-Paper.pdf">Rethinking Neural Operations for Diverse Tasks</a>
  <ul>
    <li>Nicholas Roberts, Mikhail Khodak, Tri Dao, Liam Li, Christopher Ré, Ameet Talwalkar</li>
    <li>Key: </li>
    <li>ExpEnv: <a href="https://openreview.net/forum?id=je4ymjfb5LC">Reviews And Public Comment</a></li>
  </ul>
  </li>


</ul>
</details>

### ICLR 2021
<details>
<summary>Toggle</summary>

  - [Fourier Neural Operator for Parametric Partial Differential Equations](https://openreview.net/forum?id=c8P9NQVtmnO)
    - Zongyi Li, Nikola Borislavov Kovachki, Kamyar Azizzadenesheli, Burigede liu, Kaushik Bhattacharya, Andrew Stuart, Anima Anandkumar
    - Key: Partial differential equation, Fourier transform, Neural operators
    - ExpEnv: [Codes](https://github.com/neuraloperator/neuraloperator)



</details>

### ICML 2021
<details>
<summary>Toggle</summary>
<ul>
  <li>Paper Title</li>
  <li>Author1, Author2, and Author3</li>
  <li>Key: Key insights</li>
  <li>ExpEnv: Experiment environment</li>
</ul>
</details>


### JMLR 2021
<details>
<summary>Toggle</summary>

  - [Neural Operator: Learning Maps Between Function Spaces](https://arxiv.org/abs/2108.08481)
    - Nikola Kovachki, Zongyi Li, Burigede Liu, Kamyar Azizzadenesheli, Kaushik Bhattacharya, Andrew Stuart, Anima Anandkumar
    - Key: Deep Learning, Operator Learning, Discretization-Invariance, Partial Differential
Equations, Navier-Stokes Equation
    - ExpEnv: [Codes](https://github.com/neuraloperator/neuraloperator)
  
</details>


### Other
<details>
<summary>Toggle</summary>
<ul>
  <li>Paper Title</li>
  <li>Author1, Author2, and Author3</li>
  <li>Key: Key insights</li>
  <li>ExpEnv: Experiment environment</li>
</ul>
</details>

## Tutorial
<details>
<summary>Toggle</summary>
<ul>
  <li>Details about the tutorial.</li>
</ul>
</details>

## Codebase
<details>
<summary>Toggle</summary>
<ul>
  <li>Details about the codebase.</li>
</ul>
</details>

## Contributing
<details>
<summary>Toggle</summary>
<ul>
  <li>Details about contributing.</li>
</ul>
</details>


