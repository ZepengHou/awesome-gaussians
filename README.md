# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-03-10 01:08:42

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

- [3DGS Surveys](#3dgs-surveys) (18 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (229 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (336 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (401 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (78 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (370 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (63 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (220 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (22 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (134 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (151 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (232 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, efficient, localization, mapping, gaussian splatting, face, slam, motion, survey, tracking  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, gaussian splatting, survey  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: ar, 3d gaussian, efficient, geometry, gaussian splatting, survey, nerf  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, compact, compression, gaussian splatting, 3d reconstruction, survey, high-fidelity  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: ar, 3d gaussian, localization, robotics, understanding, mapping, gaussian splatting, slam, survey, semantic, nerf  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: ar, 3d gaussian, localization, efficient, robotics, mapping, gaussian splatting, slam, survey, high-fidelity, semantic  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: fast, ar, 4d, 3d gaussian, geometry, gaussian splatting, motion, survey, nerf  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: ar, animation, 3d gaussian, real-time rendering, efficient, avatar, efficient rendering, gaussian splatting, 3d reconstruction, face, lighting, survey  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: ar, efficient, understanding, human, lightweight, gaussian splatting, survey, nerf  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: neural rendering, fast, ar, 3d gaussian, efficient, understanding, gaussian splatting, slam, survey, nerf  

### Acceleration

*Showing the latest 50 out of 229 papers*

- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: fast, ar, 3d gaussian, sparse-view, gaussian splatting  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  
- **[GloSplat: Joint Pose-Appearance Optimization for Faster and More Accurate 3D Reconstruction](https://arxiv.org/abs/2603.04847v1)**  
  Authors: Tianyu Xiong, Rui Li, Linjie Li, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04847v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, gaussian splatting, 3d reconstruction, motion, nerf  
- **[Generalized non-exponential Gaussian splatting](https://arxiv.org/abs/2603.02887v2)**  
  Authors: Sébastien Speierer, Adrian Jarabo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02887v2.pdf)  
  Keywords: fast, ar, 3d gaussian, gaussian splatting  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: fast, illumination, relightable, 3d gaussian, ar, outdoor, reflection, gaussian splatting, 3d reconstruction, relighting, lighting, nerf  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, sparse view, sparse-view, geometry, gaussian splatting, semantic  
- **[Prune Wisely, Reconstruct Sharply: Compact 3D Gaussian Splatting via Adaptive Pruning and Difference-of-Gaussian Primitives](https://arxiv.org/abs/2602.24136v1)**  
  Authors: Haoran Wang, Guoxi Huang, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24136v1.pdf)  
  Keywords: ar, 3d gaussian, real-time rendering, efficient, compact, gaussian splatting  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, geometry, gaussian splatting, 3d reconstruction, face, lighting, high-fidelity  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: fast, ar, 3d gaussian, outdoor, lightweight, gaussian splatting, face, lighting, semantic  

### Applications

*Showing the latest 50 out of 995 papers*

- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: ar, 3d gaussian, localization, geometry, gaussian splatting, slam, high-fidelity  
- **[ColonSplat: Reconstruction of Peristaltic Motion in Colonoscopy with Dynamic Gaussian Splatting](https://arxiv.org/abs/2603.06860v1)**  
  Authors: Weronika Smolak-Dyżewska, Joanna Kaleta, Diego Dall'Alba, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wmito.github.io/ColonSplat)  
  Keywords: ar, dynamic, deformation, gaussian splatting, 3d reconstruction, motion  
- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: fast, ar, 3d gaussian, sparse-view, gaussian splatting  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, 3d reconstruction, face, urban scene  
- **[VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction](https://arxiv.org/abs/2603.06210v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06210v1.pdf)  
  Keywords: ar, 3d gaussian, understanding, autonomous driving, geometry, gaussian splatting, head, semantic  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, efficient, geometry, gaussian splatting, face, high-fidelity, nerf  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, geometry, gaussian splatting  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, reflection, geometry, gaussian splatting, face  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  

### Avatar Generation

*Showing the latest 50 out of 336 papers*

- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, 3d reconstruction, face, urban scene  
- **[VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction](https://arxiv.org/abs/2603.06210v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06210v1.pdf)  
  Keywords: ar, 3d gaussian, understanding, autonomous driving, geometry, gaussian splatting, head, semantic  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, efficient, geometry, gaussian splatting, face, high-fidelity, nerf  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, reflection, geometry, gaussian splatting, face  
- **[LiftAvatar: Kinematic-Space Completion for Expression-Controlled 3D Gaussian Avatar Animation](https://arxiv.org/abs/2603.02129v1)**  
  Authors: Hualiang Wei, Shunran Jia, Jialun Liu, Wenhui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02129v1.pdf)  
  Keywords: ar, animation, 3d gaussian, efficient, avatar, gaussian splatting, head, high-fidelity  
- **[FLICKER: A Fine-Grained Contribution-Aware Accelerator for Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2603.01158v1)**  
  Authors: Wenhui Ou, Zhuoyu Wu, Yipu Zhang, Dongjun Wu, Freddy Ziyang Hong, Chik Patrick Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01158v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, head, vr  
- **[D-REX: Differentiable Real-to-Sim-to-Real Engine for Learning Dexterous Grasping](https://arxiv.org/abs/2603.01151v1)**  
  Authors: Haozhe Lou, Mingtong Zhang, Haoran Geng, Hanyang Zhou, Sicheng He, Zhiyuan Gao, Siheng Zhao, Jiageng Mao, Pieter Abbeel, Jitendra Malik, Daniel Seita, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01151v1.pdf)  
  Keywords: human, high-fidelity, dynamic, ar  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, understanding, segmentation, gaussian splatting, head, tracking  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, geometry, gaussian splatting, 3d reconstruction, face, lighting, high-fidelity  

### Dynamic Scene

*Showing the latest 50 out of 401 papers*

- **[ColonSplat: Reconstruction of Peristaltic Motion in Colonoscopy with Dynamic Gaussian Splatting](https://arxiv.org/abs/2603.06860v1)**  
  Authors: Weronika Smolak-Dyżewska, Joanna Kaleta, Diego Dall'Alba, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wmito.github.io/ColonSplat)  
  Keywords: ar, dynamic, deformation, gaussian splatting, 3d reconstruction, motion  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  
- **[GloSplat: Joint Pose-Appearance Optimization for Faster and More Accurate 3D Reconstruction](https://arxiv.org/abs/2603.04847v1)**  
  Authors: Tianyu Xiong, Rui Li, Linjie Li, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04847v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, gaussian splatting, 3d reconstruction, motion, nerf  
- **[DSA-SRGS: Super-Resolution Gaussian Splatting for Dynamic Sparse-View DSA Reconstruction](https://arxiv.org/abs/2603.04770v1)**  
  Authors: Shiyu Zhang, Zhicong Wu, Huangxuan Zhao, Zhentao Liu, Lei Chen, Yong Luo, Lefei Zhang, Zhiming Cui, Ziwen Ke, Bo Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04770v1.pdf)  
  Keywords: ar, 4d, dynamic, sparse-view, gaussian splatting  
- **[LiftAvatar: Kinematic-Space Completion for Expression-Controlled 3D Gaussian Avatar Animation](https://arxiv.org/abs/2603.02129v1)**  
  Authors: Hualiang Wei, Shunran Jia, Jialun Liu, Wenhui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02129v1.pdf)  
  Keywords: ar, animation, 3d gaussian, efficient, avatar, gaussian splatting, head, high-fidelity  
- **[D-REX: Differentiable Real-to-Sim-to-Real Engine for Learning Dexterous Grasping](https://arxiv.org/abs/2603.01151v1)**  
  Authors: Haozhe Lou, Mingtong Zhang, Haoran Geng, Hanyang Zhou, Sicheng He, Zhiyuan Gao, Siheng Zhao, Jiageng Mao, Pieter Abbeel, Jitendra Malik, Daniel Seita, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01151v1.pdf)  
  Keywords: human, high-fidelity, dynamic, ar  
- **[Decoupling Motion and Geometry in 4D Gaussian Splatting](https://arxiv.org/abs/2603.00952v1)**  
  Authors: Yi Zhang, Yulei Kang, Jian-Fang Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00952v1.pdf)  
  Keywords: ar, 4d, dynamic, deformation, geometry, gaussian splatting, motion, high-fidelity  
- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v2)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: ar, 4d, 3d gaussian, dynamic, geometry, motion, high-fidelity  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v2)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v2.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting, lighting, nerf  

### Few-shot

*Showing the latest 50 out of 78 papers*

- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: fast, ar, 3d gaussian, sparse-view, gaussian splatting  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, geometry, gaussian splatting  
- **[DSA-SRGS: Super-Resolution Gaussian Splatting for Dynamic Sparse-View DSA Reconstruction](https://arxiv.org/abs/2603.04770v1)**  
  Authors: Shiyu Zhang, Zhicong Wu, Huangxuan Zhao, Zhentao Liu, Lei Chen, Yong Luo, Lefei Zhang, Zhiming Cui, Ziwen Ke, Bo Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04770v1.pdf)  
  Keywords: ar, 4d, dynamic, sparse-view, gaussian splatting  
- **[Multimodal-Prior-Guided Importance Sampling for Hierarchical Gaussian Splatting in Sparse-View Novel View Synthesis](https://arxiv.org/abs/2603.02866v1)**  
  Authors: Kaiqiang Xiong, Zhanke Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02866v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting, semantic  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, sparse view, sparse-view, geometry, gaussian splatting, semantic  
- **[HeroGS: Hierarchical Guidance for Robust 3D Gaussian Splatting under Sparse Views](https://arxiv.org/abs/2603.01099v2)**  
  Authors: Jiashu Li, Xumeng Han, Zhaoyang Wei, Zipeng Wang, Kuiran Wang, Guorong Li, Zhenjun Han, Jianbin Jiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01099v2.pdf)  
  Keywords: ar, 3d gaussian, sparse view, sparse-view, geometry, gaussian splatting, high-fidelity  
- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: ar, 3d gaussian, sparse view, gaussian splatting, 3d reconstruction  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: ar, 3d gaussian, efficient, sparse-view, compression, gaussian splatting, head  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, sparse-view, deformation, geometry, gaussian splatting, motion  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: ar, 3d gaussian, real-time rendering, sparse-view, gaussian splatting, motion, nerf  

### Geometry Reconstruction

*Showing the latest 50 out of 370 papers*

- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: ar, 3d gaussian, localization, geometry, gaussian splatting, slam, high-fidelity  
- **[ColonSplat: Reconstruction of Peristaltic Motion in Colonoscopy with Dynamic Gaussian Splatting](https://arxiv.org/abs/2603.06860v1)**  
  Authors: Weronika Smolak-Dyżewska, Joanna Kaleta, Diego Dall'Alba, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wmito.github.io/ColonSplat)  
  Keywords: ar, dynamic, deformation, gaussian splatting, 3d reconstruction, motion  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, 3d reconstruction, face, urban scene  
- **[VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction](https://arxiv.org/abs/2603.06210v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06210v1.pdf)  
  Keywords: ar, 3d gaussian, understanding, autonomous driving, geometry, gaussian splatting, head, semantic  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, efficient, geometry, gaussian splatting, face, high-fidelity, nerf  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, geometry, gaussian splatting  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, reflection, geometry, gaussian splatting, face  
- **[GloSplat: Joint Pose-Appearance Optimization for Faster and More Accurate 3D Reconstruction](https://arxiv.org/abs/2603.04847v1)**  
  Authors: Tianyu Xiong, Rui Li, Linjie Li, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04847v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, gaussian splatting, 3d reconstruction, motion, nerf  
- **[VIRGi: View-dependent Instant Recoloring of 3D Gaussians Splats](https://arxiv.org/abs/2603.02986v1)**  
  Authors: Alessio Mazzucchelli, Ivan Ojeda-Martin, Fernando Rivas-Manzaneque, Elena Garces, Adrian Penate-Sanchez, Francesc Moreno-Noguer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02986v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, segmentation, gaussian splatting, 3d reconstruction  

### Large Scene

*Showing the latest 50 out of 63 papers*

- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, 3d reconstruction, face, urban scene  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: fast, illumination, relightable, 3d gaussian, ar, outdoor, reflection, gaussian splatting, 3d reconstruction, relighting, lighting, nerf  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: fast, ar, 3d gaussian, outdoor, lightweight, gaussian splatting, face, lighting, semantic  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: neural rendering, ar, 3d gaussian, outdoor, efficient, gaussian splatting, 3d reconstruction, high-fidelity, nerf, vr  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, 3d gaussian, localization, outdoor, geometry, mapping, gaussian splatting, head, lighting, semantic  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, real-time rendering, outdoor, autonomous driving, global illumination, gaussian splatting, lighting, nerf  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v2)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v2.pdf)  
  Keywords: illumination, ar, relightable, 3d gaussian, dynamic, outdoor, lightweight, geometry, gaussian splatting, lighting, high-fidelity  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: ar, large scene, 3d gaussian, efficient, gaussian splatting, head  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, autonomous driving, geometry, gaussian splatting, motion, semantic, urban scene  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: ar, 3d gaussian, outdoor, compression, segmentation, gaussian splatting, semantic, vr  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, efficient, geometry, gaussian splatting, face, high-fidelity, nerf  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, reflection, geometry, gaussian splatting, face  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  
- **[GloSplat: Joint Pose-Appearance Optimization for Faster and More Accurate 3D Reconstruction](https://arxiv.org/abs/2603.04847v1)**  
  Authors: Tianyu Xiong, Rui Li, Linjie Li, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04847v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, gaussian splatting, 3d reconstruction, motion, nerf  
- **[VIRGi: View-dependent Instant Recoloring of 3D Gaussians Splats](https://arxiv.org/abs/2603.02986v1)**  
  Authors: Alessio Mazzucchelli, Ivan Ojeda-Martin, Fernando Rivas-Manzaneque, Elena Garces, Adrian Penate-Sanchez, Francesc Moreno-Noguer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02986v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, segmentation, gaussian splatting, 3d reconstruction  
- **[LiftAvatar: Kinematic-Space Completion for Expression-Controlled 3D Gaussian Avatar Animation](https://arxiv.org/abs/2603.02129v1)**  
  Authors: Hualiang Wei, Shunran Jia, Jialun Liu, Wenhui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02129v1.pdf)  
  Keywords: ar, animation, 3d gaussian, efficient, avatar, gaussian splatting, head, high-fidelity  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, sparse view, sparse-view, geometry, gaussian splatting, semantic  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: illumination, ar, ray tracing, efficient, global illumination, reflection, gaussian splatting, relighting, lighting  
- **[ArtiFixer: Enhancing and Extending 3D Reconstruction with Auto-Regressive Diffusion Models](https://arxiv.org/abs/2603.00492v1)**  
  Authors: Riccardo de Lutio, Tobias Fischer, Yen-Yu Chang, Yuxuan Zhang, Jay Zhangjie Wu, Xuanchi Ren, Tianchang Shen, Katarina Tothova, Zan Gojcic, Haithem Turki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00492v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, gaussian splatting, 3d reconstruction  
- **[Station2Radar: query conditioned gaussian splatting for precipitation field](https://arxiv.org/abs/2603.00418v1)**  
  Authors: Doyi Kim, Minseok Seo, Changick Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00418v1.pdf)  
  Keywords: ar, gaussian splatting, efficient  

### Quality Enhancement

*Showing the latest 50 out of 220 papers*

- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: ar, 3d gaussian, localization, geometry, gaussian splatting, slam, high-fidelity  
- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, efficient, geometry, gaussian splatting, face, high-fidelity, nerf  
- **[LiftAvatar: Kinematic-Space Completion for Expression-Controlled 3D Gaussian Avatar Animation](https://arxiv.org/abs/2603.02129v1)**  
  Authors: Hualiang Wei, Shunran Jia, Jialun Liu, Wenhui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02129v1.pdf)  
  Keywords: ar, animation, 3d gaussian, efficient, avatar, gaussian splatting, head, high-fidelity  
- **[D-REX: Differentiable Real-to-Sim-to-Real Engine for Learning Dexterous Grasping](https://arxiv.org/abs/2603.01151v1)**  
  Authors: Haozhe Lou, Mingtong Zhang, Haoran Geng, Hanyang Zhou, Sicheng He, Zhiyuan Gao, Siheng Zhao, Jiageng Mao, Pieter Abbeel, Jitendra Malik, Daniel Seita, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01151v1.pdf)  
  Keywords: human, high-fidelity, dynamic, ar  
- **[HeroGS: Hierarchical Guidance for Robust 3D Gaussian Splatting under Sparse Views](https://arxiv.org/abs/2603.01099v2)**  
  Authors: Jiashu Li, Xumeng Han, Zhaoyang Wei, Zipeng Wang, Kuiran Wang, Guorong Li, Zhenjun Han, Jianbin Jiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01099v2.pdf)  
  Keywords: ar, 3d gaussian, sparse view, sparse-view, geometry, gaussian splatting, high-fidelity  
- **[Decoupling Motion and Geometry in 4D Gaussian Splatting](https://arxiv.org/abs/2603.00952v1)**  
  Authors: Yi Zhang, Yulei Kang, Jian-Fang Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00952v1.pdf)  
  Keywords: ar, 4d, dynamic, deformation, geometry, gaussian splatting, motion, high-fidelity  
- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v2)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: ar, 4d, 3d gaussian, dynamic, geometry, motion, high-fidelity  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, geometry, segmentation, gaussian splatting, motion, high-fidelity  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, geometry, gaussian splatting, 3d reconstruction, face, lighting, high-fidelity  
- **[M-Gaussian: An Magnetic Gaussian Framework for Efficient Multi-Stack MRI Reconstruction](https://arxiv.org/abs/2603.00145v1)**  
  Authors: Kangyuan Zheng, Xuan Cai, Jiangqi Wang, Guixing Fu, Zhuoshuo Li, Yazhou Chen, Xinting Ge, Liangqiong Qu, Mengting Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00145v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, high quality, gaussian splatting, motion  

### Ray Tracing

- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: illumination, ar, ray tracing, efficient, global illumination, reflection, gaussian splatting, relighting, lighting  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, real-time rendering, outdoor, autonomous driving, global illumination, gaussian splatting, lighting, nerf  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: illumination, ar, efficient, global illumination, shadow, geometry, gaussian splatting, relighting, lighting  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: ar, ray tracing, 3d gaussian, gaussian splatting  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: ar, understanding, lightweight, path tracing, gaussian splatting, head, medical, vr  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: ar, ray tracing, 3d gaussian, efficient, acceleration, gaussian splatting, head  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, ray marching, efficient rendering, sparse-view, shadow, gaussian splatting, 3d reconstruction  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: fast, ar, ray tracing, 3d gaussian, understanding, geometry, gaussian splatting, 3d reconstruction, motion  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: ar, ray tracing, relightable, geometry, gaussian splatting, 3d reconstruction, relighting, lighting  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: fast, ar, ray tracing, 3d gaussian, gaussian splatting, face, nerf  

### Relighting

*Showing the latest 50 out of 134 papers*

- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, efficient, reflection, geometry, gaussian splatting, face  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: fast, illumination, relightable, 3d gaussian, ar, outdoor, reflection, gaussian splatting, 3d reconstruction, relighting, lighting, nerf  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: illumination, ar, ray tracing, efficient, global illumination, reflection, gaussian splatting, relighting, lighting  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v2)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v2.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting, lighting, nerf  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, geometry, gaussian splatting, 3d reconstruction, face, lighting, high-fidelity  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: fast, ar, 3d gaussian, outdoor, lightweight, gaussian splatting, face, lighting, semantic  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: illumination, ar, 3d gaussian, dynamic, efficient, localization, lightweight, segmentation, mapping, gaussian splatting, slam, motion, semantic, tracking  
- **[WildGHand: Learning Anti-Perturbation Gaussian Hand Avatars from Monocular In-the-Wild Videos](https://arxiv.org/abs/2602.20556v1)**  
  Authors: Hanhui Li, Xuan Huang, Wanquan Liu, Yuhao Cheng, Long Chen, Yiqiang Yan, Xiaodan Liang, Chenqiang Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20556v1.pdf)  
  Keywords: illumination, ar, 3d gaussian, dynamic, avatar, gaussian splatting, motion, high-fidelity  
- **[Augmented Radiance Field: A General Framework for Enhanced Gaussian Splatting](https://arxiv.org/abs/2602.19916v1)**  
  Authors: Yixin Yang, Bojian Wu, Yang Zhou, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19916v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaoxinyyx.github.io/augs.)  
  Keywords: ar, 3d gaussian, real-time rendering, reflection, gaussian splatting, nerf  
- **[DefenseSplat: Enhancing the Robustness of 3D Gaussian Splatting via Frequency-Aware Filtering](https://arxiv.org/abs/2602.19323v1)**  
  Authors: Yiran Qiao, Yiren Lu, Yunlai Zhou, Rui Yang, Linlin Hou, Yu Yin, Jing Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19323v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, 3d reconstruction, lighting, high-fidelity  

### SLAM

*Showing the latest 50 out of 151 papers*

- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: ar, 3d gaussian, localization, geometry, gaussian splatting, slam, high-fidelity  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: fast, ar, 3d gaussian, robotics, autonomous driving, geometry, gaussian splatting, head, motion, tracking  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  
- **[SR3R: Rethinking Super-Resolution 3D Reconstruction With Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2602.24020v1)**  
  Authors: Xiang Feng, Xiangbo Wang, Tieshi Zhong, Chengkai Wang, Yiting Zhao, Tianxiang Xu, Zhenzhong Kuang, Feiwei Qin, Xuefei Yin, Yanming Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24020v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, mapping, gaussian splatting, 3d reconstruction  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, understanding, segmentation, gaussian splatting, head, tracking  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting, 3d reconstruction, slam, nerf  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: illumination, ar, 3d gaussian, dynamic, efficient, localization, lightweight, segmentation, mapping, gaussian splatting, slam, motion, semantic, tracking  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, localization, mapping, gaussian splatting, 3d reconstruction, slam, motion, semantic, tracking  
- **[NRGS-SLAM: Monocular Non-Rigid SLAM for Endoscopy via Deformation-Aware 3D Gaussian Splatting](https://arxiv.org/abs/2602.17182v1)**  
  Authors: Jiwei Shan, Zeyu Cai, Yirui Li, Yongbo Chen, Lijun Han, Yun-hui Liu, Hesheng Wang, Shing Shin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17182v1.pdf)  
  Keywords: ar, 3d gaussian, localization, efficient, deformation, mapping, gaussian splatting, slam, motion, tracking  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, fast, 4d, 3d gaussian, dynamic, efficient, ar, gaussian splatting, motion, tracking  

### Scene Understanding

*Showing the latest 50 out of 232 papers*

- **[VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction](https://arxiv.org/abs/2603.06210v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06210v1.pdf)  
  Keywords: ar, 3d gaussian, understanding, autonomous driving, geometry, gaussian splatting, head, semantic  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: ar, dynamic, efficient, efficient rendering, segmentation, gaussian splatting, tracking  
- **[VIRGi: View-dependent Instant Recoloring of 3D Gaussians Splats](https://arxiv.org/abs/2603.02986v1)**  
  Authors: Alessio Mazzucchelli, Ivan Ojeda-Martin, Fernando Rivas-Manzaneque, Elena Garces, Adrian Penate-Sanchez, Francesc Moreno-Noguer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02986v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, segmentation, gaussian splatting, 3d reconstruction  
- **[Multimodal-Prior-Guided Importance Sampling for Hierarchical Gaussian Splatting in Sparse-View Novel View Synthesis](https://arxiv.org/abs/2603.02866v1)**  
  Authors: Kaiqiang Xiong, Zhanke Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02866v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting, semantic  
- **[OnlineX: Unified Online 3D Reconstruction and Understanding with Active-to-Stable State Evolution](https://arxiv.org/abs/2603.02134v2)**  
  Authors: Chong Xia, Fangfu Liu, Yule Wang, Yize Pang, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02134v2.pdf)  
  Keywords: ar, 3d gaussian, robotics, understanding, geometry, gaussian splatting, 3d reconstruction, semantic, vr  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: fast, ar, 3d gaussian, efficient, sparse view, sparse-view, geometry, gaussian splatting, semantic  
- **[Zero-Shot Robotic Manipulation via 3D Gaussian Splatting-Enhanced Multimodal Retrieval-Augmented Generation](https://arxiv.org/abs/2603.00500v1)**  
  Authors: Zilong Xie, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.00500v1.pdf)  
  Keywords: ar, 3d gaussian, understanding, gaussian splatting, semantic  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: ar, 4d, 3d gaussian, dynamic, efficient, understanding, segmentation, gaussian splatting, head, tracking  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, geometry, segmentation, gaussian splatting, motion, high-fidelity  
- **[BetterScene: 3D Scene Synthesis with Representation-Aligned Generative Model](https://arxiv.org/abs/2602.22596v1)**  
  Authors: Yuci Han, Charles Toth, John E. Anderson, William J. Shuart, Alper Yilmaz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22596v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, semantic  



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