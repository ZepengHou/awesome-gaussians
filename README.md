# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-09-20 00:49:24

## 📰 Latest Updates

🔧 **[2025-06-26] HTTP 301 Redirect Issue Completely Resolved!** 
- Implemented multi-layer fallback strategy to thoroughly solve network compatibility issues

🔧 **[2025-06-26] Configurable Search Keywords Feature Added!**
- You can now customize search keywords by modifying `data/search_config.json`
- Support for different search scopes: abstract-only, title-only, or both
- Flexible keyword configuration for targeted paper collection

- View detailed updates: [News.md](News.md) 📋

---

## Categories

- [3DGS Surveys](#3dgs-surveys) (20 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (260 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (331 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (383 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (72 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (311 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (72 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (412 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (164 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (18 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (113 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (152 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (195 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: semantic, lighting, nerf, gaussian splatting, understanding, ar, segmentation, high-fidelity, survey, compact, 3d gaussian  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: semantic, robotics, nerf, gaussian splatting, understanding, ar, survey, 3d gaussian, efficient  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: robotics, nerf, gaussian splatting, ar, survey, 3d gaussian, human  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: vr, robotics, nerf, gaussian splatting, ar, sparse-view, survey, geometry, 3d gaussian, motion, 3d reconstruction  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v2)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Hanspeter Pfister, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v2.pdf)  
  Keywords: vr, robotics, lighting, nerf, fast, gaussian splatting, ar, survey, 3d gaussian, dynamic, human, 3d reconstruction, slam  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: nerf, outdoor, gaussian splatting, ar, high-fidelity, survey, face, 3d gaussian, dynamic, autonomous driving, efficient  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: vr, robotics, nerf, neural rendering, gaussian splatting, ar, high-fidelity, survey, autonomous driving, 3d gaussian, 3d reconstruction  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: semantic, neural rendering, gaussian splatting, understanding, ar, segmentation, high-fidelity, survey, 3d gaussian, outdoor, 3d reconstruction, efficient  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: semantic, nerf, gaussian splatting, ar, localization, slam, segmentation, mapping, survey, 3d gaussian, efficient  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: gaussian splatting, understanding, ar, survey, 4d, 3d gaussian, dynamic, motion, body  

### Acceleration

*Showing the latest 50 out of 260 papers*

- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, 3d gaussian  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, fast, gaussian splatting, ar, sparse-view, segmentation, geometry, 3d gaussian, motion  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: fast, gaussian splatting, ar, mapping, deformation, human, avatar, efficient  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, nerf, gaussian splatting, ar, relightable, illumination, geometry, compact, 3d gaussian, outdoor, efficient, head  
- **[SVR-GS: Spatially Variant Regularization for Probabilistic Masks in 3D
  Gaussian Splatting](https://arxiv.org/abs/2509.11116v1)**  
  Authors: Ashkan Taghipour, Vahid Naghshin, Benjamin Southwell, Farid Boussaid, Hamid Laga, Mohammed Bennamoun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11116v1.pdf)  
  Keywords: vr, robotics, fast, nerf, gaussian splatting, ar, 3d gaussian, efficient  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: ray tracing, fast, gaussian splatting, ar, 4d, dynamic  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: semantic, fast, gaussian splatting, understanding, ar, segmentation, high-fidelity  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, real-time rendering, fast, gaussian splatting, ar, compact, 3d gaussian, efficient  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, real-time rendering, fast, animation, gaussian splatting, ar, lightweight, high-fidelity, geometry, face, deformation, head  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: semantic, fast, neural rendering, gaussian splatting, ar, segmentation, face, 4d, human, avatar  

### Applications

*Showing the latest 50 out of 994 papers*

- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, high-fidelity, face, 3d gaussian, human, avatar  
- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: gaussian splatting, ar, face, 3d gaussian, human, efficient  
- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, geometry, 3d gaussian, efficient  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, mapping, high-fidelity, 3d gaussian, autonomous driving, slam  
- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, 3d gaussian  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: gaussian splatting, ar, face, efficient, 3d gaussian, slam  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, gaussian splatting, ar, 3d gaussian, dynamic, head  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Beyond Averages: Open-Vocabulary 3D Scene Understanding with Gaussian
  Splatting and Bag of Embeddings](https://arxiv.org/abs/2509.12938v1)**  
  Authors: Abdalla Arafa, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12938v1.pdf)  
  Keywords: vr, semantic, robotics, gaussian splatting, understanding, ar, segmentation, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 331 papers*

- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, high-fidelity, face, 3d gaussian, human, avatar  
- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: gaussian splatting, ar, face, 3d gaussian, human, efficient  
- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, 3d gaussian  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: gaussian splatting, ar, face, efficient, 3d gaussian, slam  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, gaussian splatting, ar, 3d gaussian, dynamic, head  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, high-fidelity, face, dynamic  
- **[Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.12138v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12138v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, face  
- **[A Controllable 3D Deepfake Generation Framework with Gaussian Splatting](https://arxiv.org/abs/2509.11624v1)**  
  Authors: Wending Liu, Siyun Liang, Huy H. Nguyen, Isao Echizen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11624v1.pdf)  
  Keywords: gaussian splatting, ar, face, 3d gaussian, dynamic, head  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: fast, gaussian splatting, ar, mapping, deformation, human, avatar, efficient  

### Dynamic Scene

*Showing the latest 50 out of 383 papers*

- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, gaussian splatting, ar, 3d gaussian, dynamic, head  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, high-fidelity, face, dynamic  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, fast, gaussian splatting, ar, sparse-view, segmentation, geometry, 3d gaussian, motion  
- **[A Controllable 3D Deepfake Generation Framework with Gaussian Splatting](https://arxiv.org/abs/2509.11624v1)**  
  Authors: Wending Liu, Siyun Liang, Huy H. Nguyen, Isao Echizen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11624v1.pdf)  
  Keywords: gaussian splatting, ar, face, 3d gaussian, dynamic, head  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: fast, gaussian splatting, ar, mapping, deformation, human, avatar, efficient  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: ray tracing, fast, gaussian splatting, ar, 4d, dynamic  
- **[T2Bs: Text-to-Character Blendshapes via Video Generation](https://arxiv.org/abs/2509.10678v1)**  
  Authors: Jiahao Luo, Chaoyang Wang, Michael Vasilkovsky, Vladislav Shakhrai, Di Liu, Peiye Zhuang, Sergey Tulyakov, Peter Wonka, Hsin-Ying Lee, James Davis, Jian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10678v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 4d, 3d gaussian, deformation, motion, head  
- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v3)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v3.pdf)  
  Keywords: gaussian splatting, ar, dynamic, motion, large scene  
- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, face, 3d gaussian, dynamic, efficient  

### Few-shot

*Showing the latest 50 out of 72 papers*

- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, fast, gaussian splatting, ar, sparse-view, segmentation, geometry, 3d gaussian, motion  
- **[AD-GS: Alternating Densification for Sparse-Input 3D Gaussian Splatting](https://arxiv.org/abs/2509.11003v1)**  
  Authors: Gurutva Patle, Nilay Girgaonkar, Nagabhushan Somraj, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11003v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, sparse-view  
- **[${C}^{3}$-GS: Learning Context-aware, Cross-dimension, Cross-scale
  Feature for Generalizable Gaussian Splatting](https://arxiv.org/abs/2508.20754v1)**  
  Authors: Yuxi Hu, Jun Zhang, Kuangyi Chen, Zhe Zhang, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20754v1.pdf)  
  Keywords: sparse view, ar, gaussian splatting, lightweight, geometry  
- **[MeshSplat: Generalizable Sparse-View Surface Reconstruction via Gaussian
  Splatting](https://arxiv.org/abs/2508.17811v1)**  
  Authors: Hanzhi Chang, Ruijie Zhu, Wenjie Chang, Mulin Yu, Yanzhe Liang, Jiahao Lu, Zhuoyuan Li, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17811v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanzhichang.github.io/meshsplat_web)  
  Keywords: ar, gaussian splatting, geometry, face, sparse-view  
- **[Enhancing Novel View Synthesis from extremely sparse views with SfM-free
  3D Gaussian Splatting Framework](https://arxiv.org/abs/2508.15457v1)**  
  Authors: Zongqi He, Hanmin Li, Kin-Chung Chan, Yushen Zuo, Hao Xie, Zhe Xiao, Jun Xiao, Kin-Man Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15457v1.pdf)  
  Keywords: sparse view, gaussian splatting, ar, sparse-view, geometry, 3d gaussian, motion  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: relighting, lighting, sparse view, gaussian splatting, ar, geometry, face, 3d gaussian, outdoor, autonomous driving  
- **[Quantifying and Alleviating Co-Adaptation in Sparse-View 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.12720v2)**  
  Authors: Kangjie Chen, Yingji Zhong, Zhihao Li, Jiaqi Lin, Youyu Chen, Minghan Qin, Haoqian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12720v2.pdf)  
  Keywords: gaussian splatting, understanding, ar, lightweight, 3d gaussian, sparse-view  
- **[Toward Human-Robot Teaming: Learning Handover Behaviors from 3D Scenes](https://arxiv.org/abs/2508.09855v1)**  
  Authors: Yuekun Wu, Yik Lung Pang, Andrea Cavallaro, Changjae Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09855v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, human  
- **[GSFixer: Improving 3D Gaussian Splatting with Reference-Guided Video
  Diffusion Priors](https://arxiv.org/abs/2508.09667v1)**  
  Authors: Xingyilang Yin, Qi Zhang, Jiahao Chang, Ying Feng, Qingnan Fan, Xi Yang, Chi-Man Pun, Huaqi Zhang, Xiaodong Cun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09667v1.pdf)  
  Keywords: semantic, sparse view, gaussian splatting, ar, geometry, 3d gaussian, sparse-view, 3d reconstruction  

### Geometry Reconstruction

*Showing the latest 50 out of 311 papers*

- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, geometry, 3d gaussian, efficient  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, fast, gaussian splatting, ar, sparse-view, segmentation, geometry, 3d gaussian, motion  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, nerf, gaussian splatting, ar, relightable, illumination, geometry, compact, 3d gaussian, outdoor, efficient, head  
- **[AD-GS: Alternating Densification for Sparse-Input 3D Gaussian Splatting](https://arxiv.org/abs/2509.11003v1)**  
  Authors: Gurutva Patle, Nilay Girgaonkar, Nagabhushan Somraj, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11003v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, sparse-view  
- **[T2Bs: Text-to-Character Blendshapes via Video Generation](https://arxiv.org/abs/2509.10678v1)**  
  Authors: Jiahao Luo, Chaoyang Wang, Michael Vasilkovsky, Vladislav Shakhrai, Di Liu, Peiye Zhuang, Sergey Tulyakov, Peter Wonka, Hsin-Ying Lee, James Davis, Jian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10678v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 4d, 3d gaussian, deformation, motion, head  
- **[On the Geometric Accuracy of Implicit and Primitive-based
  Representations Derived from View Rendering Constraints](https://arxiv.org/abs/2509.10241v2)**  
  Authors: Elias De Smijter, Renaud Detry, Christophe De Vleeschouwer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10241v2.pdf)  
  Keywords: robotics, lighting, gaussian splatting, ar, geometry, compact  
- **[SplatFill: 3D Scene Inpainting via Depth-Guided Gaussian Splatting](https://arxiv.org/abs/2509.07809v1)**  
  Authors: Mahtab Dahaghin, Milind G. Padalkar, Matteo Toso, Alessio Del Bue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07809v1.pdf)  
  Keywords: nerf, ar, gaussian splatting, geometry, 3d gaussian  
- **[HairGS: Hair Strand Reconstruction based on 3D Gaussian Splatting](https://arxiv.org/abs/2509.07774v1)**  
  Authors: Yimin Pan, Matthias Nießner, Tobias Kirschstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07774v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimin-pan.github.io/hair-gs/)  
  Keywords: gaussian splatting, geometry, 3d gaussian, human, efficient  
- **[DiGS: Accurate and Complete Surface Reconstruction from 3D Gaussians via
  Direct SDF Learning](https://arxiv.org/abs/2509.07493v1)**  
  Authors: Wenzhi Guo, Bing Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07493v1.pdf)  
  Keywords: nerf, gaussian splatting, ar, geometry, face, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 72 papers*

- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, nerf, gaussian splatting, ar, relightable, illumination, geometry, compact, 3d gaussian, outdoor, efficient, head  
- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v3)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v3.pdf)  
  Keywords: gaussian splatting, ar, dynamic, motion, large scene  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, large scene  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: ar, gaussian splatting, localization, 3d gaussian, outdoor  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: relighting, lighting, sparse view, gaussian splatting, ar, geometry, face, 3d gaussian, outdoor, autonomous driving  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: lighting, gaussian splatting, understanding, ar, illumination, 3d gaussian, outdoor, 3d reconstruction  
- **[Online 3D Gaussian Splatting Modeling with Novel View Selection](https://arxiv.org/abs/2508.14014v2)**  
  Authors: Byeonggwon Lee, Junkyu Park, Khang Truong Giang, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14014v2.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, outdoor, slam  
- **[InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2508.12015v1)**  
  Authors: Hongyuan Liu, Haochen Yu, Jianfei Jiang, Qiankun Liu, Jiansheng Chen, Huimin Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12015v1.pdf)  
  Keywords: outdoor, gaussian splatting, understanding, ar, lightweight, segmentation, 3d gaussian, dynamic, autonomous driving  
- **[Remove360: Benchmarking Residuals After Object Removal in 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.11431v1)**  
  Authors: Simona Kocour, Assia Benbihi, Torsten Sattler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.11431v1.pdf)  
  Keywords: semantic, gaussian splatting, understanding, ar, geometry, face, 3d gaussian, outdoor, 3d reconstruction  
- **[Multi-view Normal and Distance Guidance Gaussian Splatting for Surface
  Reconstruction](https://arxiv.org/abs/2508.07701v2)**  
  Authors: Bo Jia, Yanan Guo, Ying Chang, Benkui Zhang, Ying Xie, Kangning Du, Lin Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.07701v2.pdf)  
  Keywords: gaussian splatting, ar, geometry, face, 3d gaussian, outdoor  

### Model Compression

*Showing the latest 50 out of 412 papers*

- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: gaussian splatting, ar, face, 3d gaussian, human, efficient  
- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, geometry, 3d gaussian, efficient  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: gaussian splatting, ar, face, efficient, 3d gaussian, slam  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, gaussian splatting, ar, 3d gaussian, dynamic, head  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, high-fidelity, face, dynamic  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: fast, gaussian splatting, ar, mapping, deformation, human, avatar, efficient  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, nerf, gaussian splatting, ar, relightable, illumination, geometry, compact, 3d gaussian, outdoor, efficient, head  
- **[SVR-GS: Spatially Variant Regularization for Probabilistic Masks in 3D
  Gaussian Splatting](https://arxiv.org/abs/2509.11116v1)**  
  Authors: Ashkan Taghipour, Vahid Naghshin, Benjamin Southwell, Farid Boussaid, Hamid Laga, Mohammed Bennamoun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11116v1.pdf)  
  Keywords: vr, robotics, fast, nerf, gaussian splatting, ar, 3d gaussian, efficient  

### Quality Enhancement

*Showing the latest 50 out of 164 papers*

- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, high-fidelity, face, 3d gaussian, human, avatar  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, mapping, high-fidelity, 3d gaussian, autonomous driving, slam  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: animation, ar, lightweight, high-fidelity, geometry, 3d gaussian, body, avatar, efficient  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, high-fidelity, face, dynamic  
- **[Toward Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.05216v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05216v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, face, 3d gaussian  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: semantic, fast, gaussian splatting, understanding, ar, segmentation, high-fidelity  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, real-time rendering, fast, gaussian splatting, ar, compact, 3d gaussian, efficient  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, real-time rendering, fast, animation, gaussian splatting, ar, lightweight, high-fidelity, geometry, face, deformation, head  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: fast, gaussian splatting, ar, high-fidelity, geometry, compact, 3d gaussian, 3d reconstruction  
- **[SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00800v1.pdf)  
  Keywords: semantic, nerf, gaussian splatting, understanding, ar, high-fidelity, 3d gaussian, 3d reconstruction  

### Ray Tracing

- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: ray tracing, fast, gaussian splatting, ar, 4d, dynamic  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: relighting, lighting, ray tracing, nerf, gaussian splatting, ar, illumination, high-fidelity, reflection, geometry, face, 3d gaussian  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: global illumination, relighting, lighting, outdoor, gaussian splatting, ar, relightable, illumination, face, 3d gaussian, dynamic, shadow  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: lighting, gaussian splatting, ar, face, 3d gaussian, dynamic, path tracing  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, gaussian splatting, ar, relightable, geometry, ray marching, face, 3d gaussian, efficient  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: real-time rendering, ray tracing, gaussian splatting, ar, high-fidelity, efficient  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v2)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v2.pdf)  
  Keywords: relighting, lighting, ray tracing, fast, gaussian splatting, ar, relightable, geometry, human, avatar, shadow  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: relighting, efficient rendering, lighting, ray tracing, gaussian splatting, ar, efficient, 3d gaussian, acceleration  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: animation, gaussian splatting, ar, ray marching, compact, 3d gaussian, efficient, dynamic, acceleration  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: global illumination, real-time rendering, lighting, ray tracing, gaussian splatting, ar, illumination, face, 3d gaussian, efficient  

### Relighting

*Showing the latest 50 out of 113 papers*

- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, efficient rendering, lighting, nerf, gaussian splatting, ar, relightable, illumination, geometry, compact, 3d gaussian, outdoor, efficient, head  
- **[On the Geometric Accuracy of Implicit and Primitive-based
  Representations Derived from View Rendering Constraints](https://arxiv.org/abs/2509.10241v2)**  
  Authors: Elias De Smijter, Renaud Detry, Christophe De Vleeschouwer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10241v2.pdf)  
  Keywords: robotics, lighting, gaussian splatting, ar, geometry, compact  
- **[DreamLifting: A Plug-in Module Lifting MV Diffusion Models for 3D Asset
  Generation](https://arxiv.org/abs/2509.07435v1)**  
  Authors: Ze-Xin Yin, Jiaxiong Qiu, Liu Liu, Xinjie Wang, Wei Sui, Zhizhong Su, Jian Yang, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07435v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zx-yin.github.io/dreamlifting/.)  
  Keywords: gaussian splatting, ar, relightable, lightweight, geometry, efficient  
- **[ColorGS: High-fidelity Surgical Scene Reconstruction with Colored
  Gaussian Splatting](https://arxiv.org/abs/2508.18696v1)**  
  Authors: Qun Ji, Peng Li, Mingqiang Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18696v1.pdf)  
  Keywords: vr, real-time rendering, lighting, nerf, gaussian splatting, ar, high-fidelity, 3d gaussian, deformation, dynamic, motion, efficient  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, lighting, neural rendering, gaussian splatting, ar, localization, high-fidelity, efficient  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: relighting, lighting, sparse view, gaussian splatting, ar, geometry, face, 3d gaussian, outdoor, autonomous driving  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: relighting, lighting, ray tracing, nerf, gaussian splatting, ar, illumination, high-fidelity, reflection, geometry, face, 3d gaussian  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: lighting, gaussian splatting, understanding, ar, illumination, 3d gaussian, outdoor, 3d reconstruction  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: semantic, lighting, nerf, gaussian splatting, understanding, ar, segmentation, high-fidelity, survey, compact, 3d gaussian  
- **[HumanGenesis: Agent-Based Geometric and Generative Modeling for
  Synthetic Human Dynamics](https://arxiv.org/abs/2508.09858v1)**  
  Authors: Weiqi Li, Zehao Zhang, Liang Lin, Guangrun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09858v1.pdf)  
  Keywords: gaussian splatting, ar, reflection, face, 4d, 3d gaussian, deformation, dynamic, motion, human  

### SLAM

*Showing the latest 50 out of 152 papers*

- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, mapping, high-fidelity, 3d gaussian, autonomous driving, slam  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: gaussian splatting, ar, face, efficient, 3d gaussian, slam  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: fast, gaussian splatting, ar, mapping, deformation, human, avatar, efficient  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: gaussian splatting, understanding, ar, mapping, efficient, slam  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: gaussian splatting, ar, localization, tracking, mapping, high-fidelity, efficient, dynamic, slam  
- **[AGS: Accelerating 3D Gaussian Splatting SLAM via CODEC-Assisted Frame
  Covisibility Detection](https://arxiv.org/abs/2509.00433v1)**  
  Authors: Houshu He, Naifeng Jing, Li Jiang, Xiaoyao Liang, Zhuoran Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00433v1.pdf)  
  Keywords: gaussian splatting, acceleration, localization, ar, tracking, slam, mapping, 3d gaussian, efficient  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: animation, fast, gaussian splatting, ar, tracking, high-fidelity, face, 3d gaussian, avatar, head  
- **[PseudoMapTrainer: Learning Online Mapping without HD Maps](https://arxiv.org/abs/2508.18788v1)**  
  Authors: Christian Löwens, Thorben Funke, Jingchao Xie, Alexandru Paul Condurache  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18788v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, mapping, segmentation, face  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: ar, gaussian splatting, localization, 3d gaussian, outdoor  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, lighting, neural rendering, gaussian splatting, ar, localization, high-fidelity, efficient  

### Scene Understanding

*Showing the latest 50 out of 195 papers*

- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, high-fidelity, face, 3d gaussian, human, avatar  
- **[Beyond Averages: Open-Vocabulary 3D Scene Understanding with Gaussian
  Splatting and Bag of Embeddings](https://arxiv.org/abs/2509.12938v1)**  
  Authors: Abdalla Arafa, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12938v1.pdf)  
  Keywords: vr, semantic, robotics, gaussian splatting, understanding, ar, segmentation, 3d gaussian  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, fast, gaussian splatting, ar, sparse-view, segmentation, geometry, 3d gaussian, motion  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: gaussian splatting, understanding, ar, mapping, efficient, slam  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: semantic, fast, gaussian splatting, understanding, ar, segmentation, high-fidelity  
- **[SSGaussian: Semantic-Aware and Structure-Preserving 3D Style Transfer](https://arxiv.org/abs/2509.04379v1)**  
  Authors: Jimin Xu, Bosheng Qin, Tao Jin, Zhou Zhao, Zhenhui Ye, Jun Yu, Fei Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04379v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jm-xu.github.io/SSGaussian)  
  Keywords: 3d gaussian, ar, semantic, gaussian splatting  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, efficient, head  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: semantic, fast, neural rendering, gaussian splatting, ar, segmentation, face, 4d, human, avatar  
- **[SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00800v1.pdf)  
  Keywords: semantic, nerf, gaussian splatting, understanding, ar, high-fidelity, 3d gaussian, 3d reconstruction  
- **[MarkSplatter: Generalizable Watermarking for 3D Gaussian Splatting Model
  via Splatter Image Structure](https://arxiv.org/abs/2509.00757v1)**  
  Authors: Xiufeng Huang, Ziyuan Luo, Qi Song, Ruofei Wang, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00757v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kevinhuangxf.github.io/marksplatter.)  
  Keywords: ar, gaussian splatting, segmentation, 3d gaussian, efficient  



## Classic Papers
- **[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)** (SIGGRAPH 2023)  
  Authors: Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, George Drettakis  
  Code: 🔗 [GitHub](https://github.com/graphdeco-inria/gaussian-splatting)  
  Keywords: Real-time Rendering, Neural Rendering, Point-based Graphics

## Open Source Projects
- [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Original implementation of 3D Gaussian Splatting
- [taichi-3d-gaussian-splatting](https://github.com/wanmeihuali/taichi-3d-gaussian-splatting) - 3D Gaussian Splatting implemented in Taichi

## Applications
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering Demo](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) - Online Demo

## Tutorials & Blogs
- [Introduction to 3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Official Tutorial

## 📋 Project Features

### 🛠️ Core Features
- **Configurable Search System**: Customize search keywords through `data/search_config.json` for targeted paper collection
- **Automated Paper Collection**: Daily automatic crawling of latest Gaussian Splatting related papers
- **Intelligent Classification System**: Automatically categorize papers into different topics (Acceleration, Applications, Dynamic Scenes, etc.)
- **Flexible Search Scopes**: Support for abstract-only, title-only, or combined searches
- **Cross-Platform Compatibility**: Support for Windows/Linux/macOS with automatic environment detection

### 🛠️ Technical Features
- **Robust Error Handling**: Multi-layer retry and fallback strategies ensure stable operation
- **GitHub Actions Integration**: Automated CI/CD workflows
- **Real-time Update Mechanism**: Daily automatic paper data updates
- **Detailed Logging**: Comprehensive logging for debugging and monitoring

### 📚 Documentation System
- **User Guides**: Detailed configuration and usage instructions
- **Update Logs**: [News.md](News.md) - Records all important updates
- **Validation Reports**: Automated testing and validation results

## 🚀 Quick Start

### Customize Search Keywords
Edit `data/search_config.json` to target specific research areas:

```json
{
  "search_config": {
    "both_abstract_and_title": [
      "gaussian splatting",
      "3d gaussian",
      "neural rendering"
    ],
    "abstract_only": [
      "volumetric rendering",
      "point cloud reconstruction"
    ],
    "title_only": [
      "real-time rendering",
      "3D reconstruction"
    ]
  }
}
```

### Run the Crawler
```bash
# Basic usage
python scripts/arxiv_crawler.py

# Custom number of papers
python scripts/arxiv_crawler.py --max-results 200

# Validate configuration
python scripts/validate_search_config.py
```

## Contribution Guidelines
Feel free to submit Pull Requests to improve this list! Please follow these formats:
- Paper entry format: `**[Paper Title](link)** - Brief description`
- Project entry format: `[Project Name](link) - Project description`

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 