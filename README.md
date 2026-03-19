# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-03-19 01:18:15

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

- [3DGS Surveys](#3dgs-surveys) (19 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (234 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (342 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (397 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (369 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (63 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (425 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (223 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (26 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (132 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (147 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (233 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: survey, ar, gaussian splatting, ray tracing, mapping, 3d gaussian  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, ar, efficient, gaussian splatting, tracking, motion, face, mapping, localization, dynamic, slam, 3d gaussian  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, ar, gaussian splatting, robotics, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, ar, efficient, gaussian splatting, nerf, geometry, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: survey, ar, efficient, gaussian splatting, compact, 3d reconstruction, high-fidelity, compression, 4d, dynamic, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: survey, ar, understanding, gaussian splatting, nerf, mapping, localization, semantic, slam, robotics, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: survey, ar, efficient, gaussian splatting, high-fidelity, mapping, localization, semantic, slam, robotics, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: survey, ar, gaussian splatting, nerf, motion, 4d, geometry, fast, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: real-time rendering, survey, ar, avatar, lighting, efficient, gaussian splatting, animation, 3d reconstruction, face, efficient rendering, 3d gaussian  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: survey, ar, efficient, understanding, gaussian splatting, nerf, lightweight, human  

### Acceleration

*Showing the latest 50 out of 234 papers*

- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, 4d, fast, dynamic  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: real-time rendering, ar, ray marching, efficient, gaussian splatting, high-fidelity, 3d gaussian  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, tracking, 3d reconstruction, motion, fast, dynamic, 3d gaussian  
- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: ar, gaussian splatting, fast, semantic, 3d gaussian  
- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: ar, gaussian splatting, motion, 4d, deformation, fast, dynamic, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, high-fidelity, motion, 4d, deformation, semantic, dynamic  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, compact, geometry, 3d gaussian  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, face, geometry, fast, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: ar, avatar, efficient, gaussian splatting, high-fidelity, motion, human, face, fast, segmentation, 3d gaussian  

### Applications

*Showing the latest 50 out of 996 papers*

- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, sparse-view, geometry, semantic, segmentation, 3d gaussian  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: survey, ar, gaussian splatting, ray tracing, mapping, 3d gaussian  
- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, 4d, fast, dynamic  
- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, avatar, gaussian splatting, animation, high-fidelity, human, face, 3d gaussian  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting, geometry, localization, 3d gaussian  
- **[Leveling3D: Leveling Up 3D Reconstruction with Feed-Forward 3D Gaussian Splatting and Geometry-Aware Generation](https://arxiv.org/abs/2603.16211v1)**  
  Authors: Yiming Huang, Baixiang Huang, Beilei Cui, Chi Kit Ng, Long Bai, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16211v1.pdf)  
  Keywords: ar, gaussian splatting, lightweight, 3d reconstruction, geometry, 3d gaussian  
- **[NanoGS: Training-Free Gaussian Splat Simplification](https://arxiv.org/abs/2603.16103v1)**  
  Authors: Butian Xiong, Rong Liu, Tiantian Zhou, Meida Chen, Zhiwen Fan, Andrew Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://saliteta.github.io/NanoGS/.)  
  Keywords: ar, efficient, compact, lightweight, high-fidelity, compression, 3d gaussian  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: real-time rendering, ar, ray marching, efficient, gaussian splatting, high-fidelity, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 342 papers*

- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, avatar, gaussian splatting, animation, high-fidelity, human, face, 3d gaussian  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[KGS-GCN: Enhancing Sparse Skeleton Sensing via Kinematics-Driven Gaussian Splatting and Probabilistic Topology for Action Recognition](https://arxiv.org/abs/2603.16943v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Liping Zhang, Jie Li, Jiaxin Gao, Wenbo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16943v1.pdf)  
  Keywords: recognition, ar, gaussian splatting, human, semantic, dynamic  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, head, 3d reconstruction, dynamic  
- **[In-Field 3D Wheat Head Instance Segmentation From TLS Point Clouds Using Deep Learning Without Manual Labels](https://arxiv.org/abs/2603.14309v1)**  
  Authors: Tomislav Medic, Liangliang Nan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14309v1.pdf)  
  Keywords: ar, gaussian splatting, head, segmentation, 3d gaussian  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, relighting, high-fidelity, face, reflection, 3d gaussian  
- **[Spectral Defense Against Resource-Targeting Attack in 3D Gaussian Splatting](https://arxiv.org/abs/2603.12796v1)**  
  Authors: Yang Chen, Yi Yu, Jiaming He, Yueqi Duan, Zheng Zhu, Yap-Peng Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12796v1.pdf)  
  Keywords: gaussian splatting, ar, face, 3d gaussian  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, face, body  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, face, geometry, fast, 3d gaussian  

### Dynamic Scene

*Showing the latest 50 out of 397 papers*

- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, 4d, fast, dynamic  
- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, avatar, gaussian splatting, animation, high-fidelity, human, face, 3d gaussian  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[KGS-GCN: Enhancing Sparse Skeleton Sensing via Kinematics-Driven Gaussian Splatting and Probabilistic Topology for Action Recognition](https://arxiv.org/abs/2603.16943v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Liping Zhang, Jie Li, Jiaxin Gao, Wenbo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16943v1.pdf)  
  Keywords: recognition, ar, gaussian splatting, human, semantic, dynamic  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, tracking, 3d reconstruction, motion, fast, dynamic, 3d gaussian  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, head, 3d reconstruction, dynamic  
- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: ar, gaussian splatting, motion, 4d, deformation, fast, dynamic, 3d gaussian  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: ar, lighting, efficient, gaussian splatting, motion, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, high-fidelity, motion, 4d, deformation, semantic, dynamic  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: ar, avatar, efficient, gaussian splatting, high-fidelity, motion, human, face, fast, segmentation, 3d gaussian  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, sparse-view, geometry, semantic, segmentation, 3d gaussian  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: ar, efficient, understanding, gaussian splatting, 3d reconstruction, high-fidelity, sparse view, 3d gaussian  
- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, fast, 3d gaussian  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, geometry, 3d gaussian  
- **[DSA-SRGS: Super-Resolution Gaussian Splatting for Dynamic Sparse-View DSA Reconstruction](https://arxiv.org/abs/2603.04770v1)**  
  Authors: Shiyu Zhang, Zhicong Wu, Huangxuan Zhao, Zhentao Liu, Lei Chen, Yong Luo, Lefei Zhang, Zhiming Cui, Ziwen Ke, Bo Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04770v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, 4d, dynamic  
- **[Multimodal-Prior-Guided Importance Sampling for Hierarchical Gaussian Splatting in Sparse-View Novel View Synthesis](https://arxiv.org/abs/2603.02866v1)**  
  Authors: Kaiqiang Xiong, Zhanke Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02866v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, semantic, 3d gaussian  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, sparse-view, sparse view, geometry, fast, semantic, 3d gaussian  
- **[HeroGS: Hierarchical Guidance for Robust 3D Gaussian Splatting under Sparse Views](https://arxiv.org/abs/2603.01099v2)**  
  Authors: Jiashu Li, Xumeng Han, Zhaoyang Wei, Zipeng Wang, Kuiran Wang, Guorong Li, Zhenjun Han, Jianbin Jiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01099v2.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, sparse-view, sparse view, geometry, 3d gaussian  
- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, sparse view, 3d gaussian  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: ar, efficient, gaussian splatting, head, sparse-view, compression, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 369 papers*

- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, sparse-view, geometry, semantic, segmentation, 3d gaussian  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting, geometry, localization, 3d gaussian  
- **[Leveling3D: Leveling Up 3D Reconstruction with Feed-Forward 3D Gaussian Splatting and Geometry-Aware Generation](https://arxiv.org/abs/2603.16211v1)**  
  Authors: Yiming Huang, Baixiang Huang, Beilei Cui, Chi Kit Ng, Long Bai, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16211v1.pdf)  
  Keywords: ar, gaussian splatting, lightweight, 3d reconstruction, geometry, 3d gaussian  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[GeoNVS: Geometry Grounded Video Diffusion for Novel View Synthesis](https://arxiv.org/abs/2603.14965v1)**  
  Authors: Minjun Kang, Inkyu Shin, Taeyeop Lee, Myungchul Kim, In So Kweon, Kuk-Jin Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14965v1.pdf)  
  Keywords: geometry, ar, 3d gaussian  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, tracking, 3d reconstruction, motion, fast, dynamic, 3d gaussian  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, head, 3d reconstruction, dynamic  
- **[S2GS: Streaming Semantic Gaussian Splatting for Online Scene Understanding and Reconstruction](https://arxiv.org/abs/2603.14232v1)**  
  Authors: Renhe Zhang, Yuyang Tan, Jingyu Gong, Zhizhong Zhang, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14232v1.pdf)  
  Keywords: ar, understanding, gaussian splatting, lightweight, geometry, semantic, segmentation, 3d gaussian  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, compact, geometry, 3d gaussian  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: ar, efficient, understanding, gaussian splatting, 3d reconstruction, high-fidelity, sparse view, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 63 papers*

- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting, geometry, localization, 3d gaussian  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, urban scene, face, geometry, 3d gaussian  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: outdoor, ar, lighting, gaussian splatting, nerf, 3d reconstruction, relighting, reflection, fast, illumination, 3d gaussian, relightable  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: outdoor, ar, lighting, gaussian splatting, lightweight, face, fast, semantic, 3d gaussian  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, nerf, neural rendering, 3d reconstruction, high-fidelity, vr, 3d gaussian  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: outdoor, ar, lighting, gaussian splatting, head, mapping, geometry, localization, semantic, 3d gaussian  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: real-time rendering, outdoor, ar, global illumination, lighting, gaussian splatting, nerf, autonomous driving, illumination, 3d gaussian  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v2)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v2.pdf)  
  Keywords: outdoor, ar, lighting, gaussian splatting, lightweight, high-fidelity, geometry, dynamic, illumination, 3d gaussian, relightable  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, large scene, head, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 425 papers*

- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, 4d, fast, dynamic  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[Leveling3D: Leveling Up 3D Reconstruction with Feed-Forward 3D Gaussian Splatting and Geometry-Aware Generation](https://arxiv.org/abs/2603.16211v1)**  
  Authors: Yiming Huang, Baixiang Huang, Beilei Cui, Chi Kit Ng, Long Bai, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16211v1.pdf)  
  Keywords: ar, gaussian splatting, lightweight, 3d reconstruction, geometry, 3d gaussian  
- **[NanoGS: Training-Free Gaussian Splat Simplification](https://arxiv.org/abs/2603.16103v1)**  
  Authors: Butian Xiong, Rong Liu, Tiantian Zhou, Meida Chen, Zhiwen Fan, Andrew Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://saliteta.github.io/NanoGS/.)  
  Keywords: ar, efficient, compact, lightweight, high-fidelity, compression, 3d gaussian  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: real-time rendering, ar, ray marching, efficient, gaussian splatting, high-fidelity, 3d gaussian  
- **[LiDAR-EVS: Enhance Extrapolated View Synthesis for 3D Gaussian Splatting with Pseudo-LiDAR Supervision](https://arxiv.org/abs/2603.14763v1)**  
  Authors: Yiming Huang, Xin Kang, Sipeng Zhang, Hongliang Ren, Weihua Zhang, Junjie Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14763v1.pdf)  
  Keywords: ar, gaussian splatting, lightweight, neural rendering, autonomous driving, 3d gaussian  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, head, 3d reconstruction, dynamic  
- **[S2GS: Streaming Semantic Gaussian Splatting for Online Scene Understanding and Reconstruction](https://arxiv.org/abs/2603.14232v1)**  
  Authors: Renhe Zhang, Yuyang Tan, Jingyu Gong, Zhizhong Zhang, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14232v1.pdf)  
  Keywords: ar, understanding, gaussian splatting, lightweight, geometry, semantic, segmentation, 3d gaussian  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: ar, lighting, efficient, gaussian splatting, motion, 3d gaussian  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: real-time rendering, ar, efficient, gaussian splatting, compact, geometry, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 223 papers*

- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, avatar, gaussian splatting, animation, high-fidelity, human, face, 3d gaussian  
- **[NanoGS: Training-Free Gaussian Splat Simplification](https://arxiv.org/abs/2603.16103v1)**  
  Authors: Butian Xiong, Rong Liu, Tiantian Zhou, Meida Chen, Zhiwen Fan, Andrew Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://saliteta.github.io/NanoGS/.)  
  Keywords: ar, efficient, compact, lightweight, high-fidelity, compression, 3d gaussian  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: real-time rendering, ar, ray marching, efficient, gaussian splatting, high-fidelity, 3d gaussian  
- **[NavGSim: High-Fidelity Gaussian Splatting Simulator for Large-Scale Navigation](https://arxiv.org/abs/2603.15186v1)**  
  Authors: Jiahang Liu, Yuanxing Duan, Jiazhao Zhang, Minghan Li, Shaoan Wang, Zhizheng Zhang, He Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15186v1.pdf)  
  Keywords: ar, understanding, gaussian splatting, high-fidelity, 3d gaussian  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, relighting, high-fidelity, face, reflection, 3d gaussian  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, face, body  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, high-fidelity, motion, 4d, deformation, semantic, dynamic  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: ar, efficient, understanding, gaussian splatting, 3d reconstruction, high-fidelity, sparse view, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: ar, avatar, efficient, gaussian splatting, high-fidelity, motion, human, face, fast, segmentation, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, tracking, localization, high-fidelity, face, mapping, fast, slam, 3d gaussian  

### Ray Tracing

- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: survey, ar, gaussian splatting, ray tracing, mapping, 3d gaussian  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: real-time rendering, ar, ray marching, efficient, gaussian splatting, high-fidelity, 3d gaussian  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ray casting, ar, efficient, gaussian splatting, geometry, fast, robotics, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ar, efficient, gaussian splatting, lightweight, face, ray tracing, reflection, geometry, fast  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ar, global illumination, lighting, efficient, gaussian splatting, relighting, ray tracing, reflection, illumination  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: real-time rendering, outdoor, ar, global illumination, lighting, gaussian splatting, nerf, autonomous driving, illumination, 3d gaussian  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: ar, global illumination, lighting, efficient, gaussian splatting, relighting, shadow, geometry, illumination  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, 3d gaussian  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: medical, ar, understanding, gaussian splatting, lightweight, head, vr, path tracing  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, head, ray tracing, acceleration, 3d gaussian  

### Relighting

*Showing the latest 50 out of 132 papers*

- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, tracking, 3d reconstruction, motion, fast, dynamic, 3d gaussian  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, relighting, high-fidelity, face, reflection, 3d gaussian  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: ar, lighting, efficient, gaussian splatting, motion, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ar, efficient, gaussian splatting, lightweight, face, ray tracing, reflection, geometry, fast  
- **[3DGS-HPC: Distractor-free 3D Gaussian Splatting with Hybrid Patch-wise Classification](https://arxiv.org/abs/2603.07587v1)**  
  Authors: Jiahao Chen, Yipeng Qin, Ganlong Zhao, Xin Li, Wenping Wang, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07587v1.pdf)  
  Keywords: ar, gaussian splatting, shadow, semantic, 3d gaussian  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, face, reflection, geometry, illumination, 3d gaussian  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: outdoor, ar, lighting, gaussian splatting, nerf, 3d reconstruction, relighting, reflection, fast, illumination, 3d gaussian, relightable  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ar, global illumination, lighting, efficient, gaussian splatting, relighting, ray tracing, reflection, illumination  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v2)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v2.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, dynamic, 3d gaussian  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: ar, lighting, efficient, gaussian splatting, 3d reconstruction, high-fidelity, face, geometry, fast, 3d gaussian  

### SLAM

*Showing the latest 50 out of 147 papers*

- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: survey, ar, gaussian splatting, ray tracing, mapping, 3d gaussian  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: outdoor, ar, efficient, gaussian splatting, tracking, head, dynamic, slam  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting, geometry, localization, 3d gaussian  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf, tracking, 3d reconstruction, motion, fast, dynamic, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, tracking, localization, high-fidelity, face, mapping, fast, slam, 3d gaussian  
- **[X-GS: An Extensible Open Framework for Perceiving and Thinking via 3D Gaussian Splatting](https://arxiv.org/abs/2603.09632v2)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09632v2.pdf)  
  Keywords: ar, gaussian splatting, face, semantic, slam, 3d gaussian  
- **[Improving Continual Learning for Gaussian Splatting based Environments Reconstruction on Commercial Off-the-Shelf Edge Devices](https://arxiv.org/abs/2603.08499v1)**  
  Authors: Ivan Zaino, Matteo Risso, Daniele Jahier Pagliari, Miguel de Prado, Toon Van de Maele, Alessio Burrello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08499v1.pdf)  
  Keywords: ar, compact, gaussian splatting, slam, robotics  
- **[HDR-NSFF: High Dynamic Range Neural Scene Flow Fields](https://arxiv.org/abs/2603.08313v1)**  
  Authors: Shin Dong-Yeon, Kim Jun-Seong, Kwon Byung-Ki, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08313v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shin-dong-yeon.github.io/HDR-NSFF/)  
  Keywords: ar, gaussian splatting, motion, 4d, semantic, geometry, dynamic, mapping  
- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, geometry, localization, slam, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 233 papers*

- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, sparse-view, geometry, semantic, segmentation, 3d gaussian  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: ar, avatar, tracking, head, geometry, fast, semantic  
- **[NavGSim: High-Fidelity Gaussian Splatting Simulator for Large-Scale Navigation](https://arxiv.org/abs/2603.15186v1)**  
  Authors: Jiahang Liu, Yuanxing Duan, Jiazhao Zhang, Minghan Li, Shaoan Wang, Zhizheng Zhang, He Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15186v1.pdf)  
  Keywords: ar, understanding, gaussian splatting, high-fidelity, 3d gaussian  
- **[KGS-GCN: Enhancing Sparse Skeleton Sensing via Kinematics-Driven Gaussian Splatting and Probabilistic Topology for Action Recognition](https://arxiv.org/abs/2603.16943v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Liping Zhang, Jie Li, Jiaxin Gao, Wenbo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16943v1.pdf)  
  Keywords: recognition, ar, gaussian splatting, human, semantic, dynamic  
- **[In-Field 3D Wheat Head Instance Segmentation From TLS Point Clouds Using Deep Learning Without Manual Labels](https://arxiv.org/abs/2603.14309v1)**  
  Authors: Tomislav Medic, Liangliang Nan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14309v1.pdf)  
  Keywords: ar, gaussian splatting, head, segmentation, 3d gaussian  
- **[S2GS: Streaming Semantic Gaussian Splatting for Online Scene Understanding and Reconstruction](https://arxiv.org/abs/2603.14232v1)**  
  Authors: Renhe Zhang, Yuyang Tan, Jingyu Gong, Zhizhong Zhang, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14232v1.pdf)  
  Keywords: ar, understanding, gaussian splatting, lightweight, geometry, semantic, segmentation, 3d gaussian  
- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: ar, gaussian splatting, fast, semantic, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, high-fidelity, motion, 4d, deformation, semantic, dynamic  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: ar, efficient, understanding, gaussian splatting, 3d reconstruction, high-fidelity, sparse view, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: ar, avatar, efficient, gaussian splatting, high-fidelity, motion, human, face, fast, segmentation, 3d gaussian  



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