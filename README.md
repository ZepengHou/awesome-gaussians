# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-09-23 00:51:22

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
- [Acceleration](#acceleration) (258 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (331 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (383 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (71 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (311 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (72 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (413 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (163 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (18 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (115 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (152 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (197 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: nerf, understanding, high-fidelity, 3d gaussian, ar, lighting, semantic, gaussian splatting, segmentation, compact, survey  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: nerf, understanding, robotics, 3d gaussian, ar, semantic, gaussian splatting, efficient, survey  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: nerf, robotics, 3d gaussian, ar, gaussian splatting, human, survey  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: nerf, robotics, 3d reconstruction, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, vr, survey  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v2)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Hanspeter Pfister, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v2.pdf)  
  Keywords: nerf, robotics, 3d reconstruction, slam, 3d gaussian, ar, lighting, gaussian splatting, dynamic, human, fast, vr, survey  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: nerf, efficient, autonomous driving, outdoor, high-fidelity, 3d gaussian, ar, face, gaussian splatting, dynamic, survey  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: nerf, robotics, autonomous driving, 3d reconstruction, high-fidelity, 3d gaussian, ar, gaussian splatting, vr, neural rendering, survey  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: understanding, 3d reconstruction, outdoor, high-fidelity, 3d gaussian, ar, semantic, gaussian splatting, efficient, segmentation, neural rendering, survey  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: nerf, mapping, slam, 3d gaussian, ar, localization, semantic, gaussian splatting, efficient, segmentation, survey  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: understanding, motion, 3d gaussian, 4d, ar, dynamic, gaussian splatting, body, survey  

### Acceleration

*Showing the latest 50 out of 258 papers*

- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, ar, gaussian splatting, efficient, fast, lighting  
- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, gaussian splatting, efficient, fast  
- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, fast  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, fast, segmentation  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: mapping, ar, gaussian splatting, efficient, human, fast, deformation, avatar  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: nerf, illumination, efficient, outdoor, efficient rendering, 3d gaussian, ar, geometry, head, gaussian splatting, relightable, relighting, compact, lighting  
- **[SVR-GS: Spatially Variant Regularization for Probabilistic Masks in 3D
  Gaussian Splatting](https://arxiv.org/abs/2509.11116v1)**  
  Authors: Ashkan Taghipour, Vahid Naghshin, Benjamin Southwell, Farid Boussaid, Hamid Laga, Mohammed Bennamoun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11116v1.pdf)  
  Keywords: nerf, robotics, 3d gaussian, ar, gaussian splatting, efficient, fast, vr  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: 4d, ar, dynamic, gaussian splatting, fast, ray tracing  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: understanding, high-fidelity, ar, semantic, gaussian splatting, fast, segmentation  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: real-time rendering, high quality, 3d gaussian, ar, gaussian splatting, efficient, fast, compact  

### Applications

*Showing the latest 50 out of 995 papers*

- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, ar, gaussian splatting, efficient, fast, lighting  
- **[Zero-Shot Visual Grounding in 3D Gaussians via View Retrieval](https://arxiv.org/abs/2509.15871v1)**  
  Authors: Liwei Liao, Xufeng Li, Xiaoyun Zheng, Boning Liu, Feng Gao, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15871v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, gaussian splatting, vr  
- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: reflection, 3d gaussian, ar, face, gaussian splatting  
- **[FingerSplat: Contactless Fingerprint 3D Reconstruction and Generation
  based on 3D Gaussian Splatting](https://arxiv.org/abs/2509.15648v1)**  
  Authors: Yuwei Jia, Yutang Lu, Zhe Cui, Fei Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15648v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, recognition, ar, gaussian splatting  
- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, gaussian splatting, efficient, fast  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v1)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v1.pdf)  
  Keywords: nerf, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, semantic  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, face, gaussian splatting, semantic, human, avatar  
- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, efficient, human  
- **[Causal Reasoning Elicits Controllable 3D Scene Generation](https://arxiv.org/abs/2509.15249v1)**  
  Authors: Shen Chen, Ruiyu Zhao, Jiale Zhou, Zongkai Wu, Jenq-Neng Hwang, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15249v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, gaussian splatting  
- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, geometry, gaussian splatting, efficient  

### Avatar Generation

*Showing the latest 50 out of 331 papers*

- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: reflection, 3d gaussian, ar, face, gaussian splatting  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, face, gaussian splatting, semantic, human, avatar  
- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, efficient, human  
- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, fast  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, slam, efficient  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, 3d gaussian, ar, head, dynamic, gaussian splatting  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, geometry, body, efficient, lightweight, animation, avatar  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: high-fidelity, ar, face, dynamic, gaussian splatting, lightweight  
- **[Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.12138v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12138v1.pdf)  
  Keywords: ar, 3d gaussian, face, gaussian splatting  
- **[A Controllable 3D Deepfake Generation Framework with Gaussian Splatting](https://arxiv.org/abs/2509.11624v1)**  
  Authors: Wending Liu, Siyun Liang, Huy H. Nguyen, Isao Echizen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11624v1.pdf)  
  Keywords: 3d gaussian, ar, head, face, dynamic, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 383 papers*

- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, ar, gaussian splatting, efficient, fast, lighting  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v1)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v1.pdf)  
  Keywords: nerf, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, semantic  
- **[Causal Reasoning Elicits Controllable 3D Scene Generation](https://arxiv.org/abs/2509.15249v1)**  
  Authors: Shen Chen, Ruiyu Zhao, Jiale Zhou, Zongkai Wu, Jenq-Neng Hwang, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15249v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, gaussian splatting  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, 3d gaussian, ar, head, dynamic, gaussian splatting  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, geometry, body, efficient, lightweight, animation, avatar  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: high-fidelity, ar, face, dynamic, gaussian splatting, lightweight  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, fast, segmentation  
- **[A Controllable 3D Deepfake Generation Framework with Gaussian Splatting](https://arxiv.org/abs/2509.11624v1)**  
  Authors: Wending Liu, Siyun Liang, Huy H. Nguyen, Isao Echizen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11624v1.pdf)  
  Keywords: 3d gaussian, ar, head, face, dynamic, gaussian splatting  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: mapping, ar, gaussian splatting, efficient, human, fast, deformation, avatar  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: 4d, ar, dynamic, gaussian splatting, fast, ray tracing  

### Few-shot

*Showing the latest 50 out of 71 papers*

- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v1)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v1.pdf)  
  Keywords: nerf, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, semantic  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, fast, segmentation  
- **[AD-GS: Alternating Densification for Sparse-Input 3D Gaussian Splatting](https://arxiv.org/abs/2509.11003v1)**  
  Authors: Gurutva Patle, Nilay Girgaonkar, Nagabhushan Somraj, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11003v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, sparse-view, gaussian splatting  
- **[${C}^{3}$-GS: Learning Context-aware, Cross-dimension, Cross-scale
  Feature for Generalizable Gaussian Splatting](https://arxiv.org/abs/2508.20754v1)**  
  Authors: Yuxi Hu, Jun Zhang, Kuangyi Chen, Zhe Zhang, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20754v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, lightweight, sparse view  
- **[MeshSplat: Generalizable Sparse-View Surface Reconstruction via Gaussian
  Splatting](https://arxiv.org/abs/2508.17811v1)**  
  Authors: Hanzhi Chang, Ruijie Zhu, Wenjie Chang, Mulin Yu, Yanzhe Liang, Jiahao Lu, Zhuoyuan Li, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17811v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanzhichang.github.io/meshsplat_web)  
  Keywords: ar, geometry, face, sparse-view, gaussian splatting  
- **[Enhancing Novel View Synthesis from extremely sparse views with SfM-free
  3D Gaussian Splatting Framework](https://arxiv.org/abs/2508.15457v1)**  
  Authors: Zongqi He, Hanmin Li, Kin-Chung Chan, Yushen Zuo, Hao Xie, Zhe Xiao, Jun Xiao, Kin-Man Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15457v1.pdf)  
  Keywords: motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, sparse view  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, outdoor, 3d gaussian, ar, geometry, face, gaussian splatting, relighting, sparse view, lighting  
- **[Quantifying and Alleviating Co-Adaptation in Sparse-View 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.12720v3)**  
  Authors: Kangjie Chen, Yingji Zhong, Zhihao Li, Jiaqi Lin, Youyu Chen, Minghan Qin, Haoqian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12720v3.pdf)  
  Keywords: understanding, 3d gaussian, ar, sparse-view, gaussian splatting, lightweight  
- **[Toward Human-Robot Teaming: Learning Handover Behaviors from 3D Scenes](https://arxiv.org/abs/2508.09855v1)**  
  Authors: Yuekun Wu, Yik Lung Pang, Andrea Cavallaro, Changjae Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09855v1.pdf)  
  Keywords: human, sparse-view, gaussian splatting, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 311 papers*

- **[FingerSplat: Contactless Fingerprint 3D Reconstruction and Generation
  based on 3D Gaussian Splatting](https://arxiv.org/abs/2509.15648v1)**  
  Authors: Yuwei Jia, Yutang Lu, Zhe Cui, Fei Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15648v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, recognition, ar, gaussian splatting  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v1)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v1.pdf)  
  Keywords: nerf, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, semantic  
- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, geometry, gaussian splatting, efficient  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, geometry, body, efficient, lightweight, animation, avatar  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, fast, segmentation  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: nerf, illumination, efficient, outdoor, efficient rendering, 3d gaussian, ar, geometry, head, gaussian splatting, relightable, relighting, compact, lighting  
- **[AD-GS: Alternating Densification for Sparse-Input 3D Gaussian Splatting](https://arxiv.org/abs/2509.11003v1)**  
  Authors: Gurutva Patle, Nilay Girgaonkar, Nagabhushan Somraj, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11003v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, sparse-view, gaussian splatting  
- **[T2Bs: Text-to-Character Blendshapes via Video Generation](https://arxiv.org/abs/2509.10678v1)**  
  Authors: Jiahao Luo, Chaoyang Wang, Michael Vasilkovsky, Vladislav Shakhrai, Di Liu, Peiye Zhuang, Sergey Tulyakov, Peter Wonka, Hsin-Ying Lee, James Davis, Jian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10678v1.pdf)  
  Keywords: motion, 3d gaussian, 4d, ar, geometry, head, gaussian splatting, deformation  
- **[On the Geometric Accuracy of Implicit and Primitive-based
  Representations Derived from View Rendering Constraints](https://arxiv.org/abs/2509.10241v2)**  
  Authors: Elias De Smijter, Renaud Detry, Christophe De Vleeschouwer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10241v2.pdf)  
  Keywords: robotics, ar, geometry, gaussian splatting, compact, lighting  
- **[SplatFill: 3D Scene Inpainting via Depth-Guided Gaussian Splatting](https://arxiv.org/abs/2509.07809v1)**  
  Authors: Mahtab Dahaghin, Milind G. Padalkar, Matteo Toso, Alessio Del Bue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07809v1.pdf)  
  Keywords: nerf, 3d gaussian, ar, geometry, gaussian splatting  

### Large Scene

*Showing the latest 50 out of 72 papers*

- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: nerf, illumination, efficient, outdoor, efficient rendering, 3d gaussian, ar, geometry, head, gaussian splatting, relightable, relighting, compact, lighting  
- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v3)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v3.pdf)  
  Keywords: motion, ar, dynamic, gaussian splatting, large scene  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: ar, 3d gaussian, large scene, gaussian splatting  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: outdoor, 3d gaussian, ar, gaussian splatting, localization  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, outdoor, 3d gaussian, ar, geometry, face, gaussian splatting, relighting, sparse view, lighting  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: illumination, understanding, 3d reconstruction, outdoor, 3d gaussian, ar, gaussian splatting, lighting  
- **[Online 3D Gaussian Splatting Modeling with Novel View Selection](https://arxiv.org/abs/2508.14014v2)**  
  Authors: Byeonggwon Lee, Junkyu Park, Khang Truong Giang, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14014v2.pdf)  
  Keywords: outdoor, 3d gaussian, ar, gaussian splatting, slam  
- **[InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2508.12015v1)**  
  Authors: Hongyuan Liu, Haochen Yu, Jianfei Jiang, Qiankun Liu, Jiansheng Chen, Huimin Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12015v1.pdf)  
  Keywords: autonomous driving, understanding, outdoor, 3d gaussian, ar, dynamic, gaussian splatting, lightweight, segmentation  
- **[Remove360: Benchmarking Residuals After Object Removal in 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.11431v1)**  
  Authors: Simona Kocour, Assia Benbihi, Torsten Sattler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.11431v1.pdf)  
  Keywords: understanding, 3d reconstruction, outdoor, 3d gaussian, ar, geometry, face, gaussian splatting, semantic  
- **[Multi-view Normal and Distance Guidance Gaussian Splatting for Surface
  Reconstruction](https://arxiv.org/abs/2508.07701v2)**  
  Authors: Bo Jia, Yanan Guo, Ying Chang, Benkui Zhang, Ying Xie, Kangning Du, Lin Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.07701v2.pdf)  
  Keywords: outdoor, 3d gaussian, ar, geometry, face, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 413 papers*

- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, ar, gaussian splatting, efficient, fast, lighting  
- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, gaussian splatting, efficient, fast  
- **[RealMirror: A Comprehensive, Open-Source Vision-Language-Action Platform
  for Embodied AI](https://arxiv.org/abs/2509.14687v1)**  
  Authors: Cong Tai, Zhaoyu Zheng, Haixu Long, Hansheng Wu, Haodong Xiang, Zhengbin Long, Jun Xiong, Rong Shi, Shizhuang Zhang, Gang Qiu, He Wang, Ruifeng Li, Jun Huang, Bin Chang, Shuai Feng, Tao Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14687v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://terminators2025.github.io/RealMirror.github.io)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, efficient, human  
- **[Perception-Integrated Safety Critical Control via Analytic Collision
  Cone Barrier Functions on 3D Gaussian Splatting](https://arxiv.org/abs/2509.14421v1)**  
  Authors: Dario Tscholl, Yashwanth Nakka, Brian Gunter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14421v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, geometry, gaussian splatting, efficient  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, slam, efficient  
- **[Improving 3D Gaussian Splatting Compression by Scene-Adaptive Lattice
  Vector Quantization](https://arxiv.org/abs/2509.13482v1)**  
  Authors: Hao Xu, Xiaolin Wu, Xi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13482v1.pdf)  
  Keywords: compression, 3d gaussian, ar, head, dynamic, gaussian splatting  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, geometry, body, efficient, lightweight, animation, avatar  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: high-fidelity, ar, face, dynamic, gaussian splatting, lightweight  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: mapping, ar, gaussian splatting, efficient, human, fast, deformation, avatar  

### Quality Enhancement

*Showing the latest 50 out of 163 papers*

- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, gaussian splatting, efficient, fast  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, face, gaussian splatting, semantic, human, avatar  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: mapping, robotics, autonomous driving, high-fidelity, 3d gaussian, ar, gaussian splatting, slam  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, geometry, body, efficient, lightweight, animation, avatar  
- **[Effective Gaussian Management for High-fidelity Object Reconstruction](https://arxiv.org/abs/2509.12742v1)**  
  Authors: Jiateng Liu, Hao Gao, Jiu-Cheng Xie, Chi-Man Pun, Jian Xiong, Haolun Li, Feng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12742v1.pdf)  
  Keywords: high-fidelity, ar, face, dynamic, gaussian splatting, lightweight  
- **[Toward Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.05216v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05216v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, face, gaussian splatting  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: understanding, high-fidelity, ar, semantic, gaussian splatting, fast, segmentation  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: real-time rendering, high quality, 3d gaussian, ar, gaussian splatting, efficient, fast, compact  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: real-time rendering, vr, high-fidelity, ar, geometry, head, face, gaussian splatting, lightweight, fast, deformation, animation  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: 3d reconstruction, high-fidelity, 3d gaussian, ar, geometry, gaussian splatting, fast, compact  

### Ray Tracing

- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: 4d, ar, dynamic, gaussian splatting, fast, ray tracing  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: nerf, illumination, reflection, high-fidelity, 3d gaussian, ar, geometry, face, gaussian splatting, relighting, ray tracing, lighting  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: shadow, illumination, outdoor, 3d gaussian, ar, global illumination, face, gaussian splatting, relightable, dynamic, relighting, lighting  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: 3d gaussian, ar, path tracing, face, gaussian splatting, dynamic, lighting  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: efficient, efficient rendering, 3d gaussian, ar, geometry, face, gaussian splatting, relightable, relighting, ray marching, lighting  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: real-time rendering, high-fidelity, ar, gaussian splatting, efficient, ray tracing  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v2)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v2.pdf)  
  Keywords: shadow, relighting, ar, geometry, gaussian splatting, relightable, human, fast, ray tracing, avatar, lighting  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: efficient rendering, ray tracing, 3d gaussian, ar, gaussian splatting, efficient, relighting, acceleration, lighting  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: compact, 3d gaussian, ar, gaussian splatting, dynamic, acceleration, animation, ray marching, efficient  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: real-time rendering, illumination, 3d gaussian, ar, global illumination, face, gaussian splatting, efficient, ray tracing, lighting  

### Relighting

*Showing the latest 50 out of 115 papers*

- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, ar, gaussian splatting, efficient, fast, lighting  
- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: reflection, 3d gaussian, ar, face, gaussian splatting  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: nerf, illumination, efficient, outdoor, efficient rendering, 3d gaussian, ar, geometry, head, gaussian splatting, relightable, relighting, compact, lighting  
- **[On the Geometric Accuracy of Implicit and Primitive-based
  Representations Derived from View Rendering Constraints](https://arxiv.org/abs/2509.10241v2)**  
  Authors: Elias De Smijter, Renaud Detry, Christophe De Vleeschouwer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10241v2.pdf)  
  Keywords: robotics, ar, geometry, gaussian splatting, compact, lighting  
- **[DreamLifting: A Plug-in Module Lifting MV Diffusion Models for 3D Asset
  Generation](https://arxiv.org/abs/2509.07435v1)**  
  Authors: Ze-Xin Yin, Jiaxiong Qiu, Liu Liu, Xinjie Wang, Wei Sui, Zhizhong Su, Jian Yang, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07435v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zx-yin.github.io/dreamlifting/.)  
  Keywords: relightable, ar, geometry, gaussian splatting, efficient, lightweight  
- **[ColorGS: High-fidelity Surgical Scene Reconstruction with Colored
  Gaussian Splatting](https://arxiv.org/abs/2508.18696v1)**  
  Authors: Qun Ji, Peng Li, Mingqiang Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18696v1.pdf)  
  Keywords: real-time rendering, nerf, efficient, motion, high-fidelity, 3d gaussian, ar, gaussian splatting, dynamic, vr, deformation, lighting  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, high-fidelity, ar, localization, gaussian splatting, efficient, neural rendering, lighting  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, outdoor, 3d gaussian, ar, geometry, face, gaussian splatting, relighting, sparse view, lighting  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: nerf, illumination, reflection, high-fidelity, 3d gaussian, ar, geometry, face, gaussian splatting, relighting, ray tracing, lighting  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: illumination, understanding, 3d reconstruction, outdoor, 3d gaussian, ar, gaussian splatting, lighting  

### SLAM

*Showing the latest 50 out of 152 papers*

- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: mapping, robotics, autonomous driving, high-fidelity, 3d gaussian, ar, gaussian splatting, slam  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, slam, efficient  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: mapping, ar, gaussian splatting, efficient, human, fast, deformation, avatar  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: mapping, understanding, ar, gaussian splatting, slam, efficient  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: mapping, high-fidelity, tracking, ar, localization, dynamic, slam, gaussian splatting, efficient  
- **[AGS: Accelerating 3D Gaussian Splatting SLAM via CODEC-Assisted Frame
  Covisibility Detection](https://arxiv.org/abs/2509.00433v1)**  
  Authors: Houshu He, Naifeng Jing, Li Jiang, Xiaoyao Liang, Zhuoran Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00433v1.pdf)  
  Keywords: mapping, 3d gaussian, tracking, ar, localization, gaussian splatting, slam, acceleration, efficient  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, tracking, ar, head, face, gaussian splatting, fast, animation, avatar  
- **[PseudoMapTrainer: Learning Online Mapping without HD Maps](https://arxiv.org/abs/2508.18788v1)**  
  Authors: Christian Löwens, Thorben Funke, Jingchao Xie, Alexandru Paul Condurache  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18788v1.pdf)  
  Keywords: mapping, ar, face, gaussian splatting, semantic, segmentation  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: outdoor, 3d gaussian, ar, gaussian splatting, localization  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, high-fidelity, ar, localization, gaussian splatting, efficient, neural rendering, lighting  

### Scene Understanding

*Showing the latest 50 out of 197 papers*

- **[FingerSplat: Contactless Fingerprint 3D Reconstruction and Generation
  based on 3D Gaussian Splatting](https://arxiv.org/abs/2509.15648v1)**  
  Authors: Yuwei Jia, Yutang Lu, Zhe Cui, Fei Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15648v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, recognition, ar, gaussian splatting  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v1)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v1.pdf)  
  Keywords: nerf, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, semantic  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, ar, face, gaussian splatting, semantic, human, avatar  
- **[Beyond Averages: Open-Vocabulary 3D Scene Understanding with Gaussian
  Splatting and Bag of Embeddings](https://arxiv.org/abs/2509.12938v1)**  
  Authors: Abdalla Arafa, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12938v1.pdf)  
  Keywords: robotics, understanding, 3d gaussian, ar, semantic, gaussian splatting, vr, segmentation  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, motion, 3d gaussian, ar, geometry, sparse-view, gaussian splatting, fast, segmentation  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: mapping, understanding, ar, gaussian splatting, slam, efficient  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v2)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Simon Boche, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v2.pdf)  
  Keywords: understanding, high-fidelity, ar, semantic, gaussian splatting, fast, segmentation  
- **[SSGaussian: Semantic-Aware and Structure-Preserving 3D Style Transfer](https://arxiv.org/abs/2509.04379v1)**  
  Authors: Jimin Xu, Bosheng Qin, Tao Jin, Zhou Zhao, Zhenhui Ye, Jun Yu, Fei Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04379v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jm-xu.github.io/SSGaussian)  
  Keywords: ar, 3d gaussian, semantic, gaussian splatting  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: ar, head, semantic, gaussian splatting, efficient  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: 4d, ar, face, gaussian splatting, semantic, human, fast, segmentation, neural rendering, avatar  



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