# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-03-17 01:14:37

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
- [Acceleration](#acceleration) (233 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (339 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (399 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (80 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (371 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (62 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (422 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (220 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (24 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (134 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (233 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: dynamic, slam, efficient, gaussian splatting, motion, mapping, tracking, ar, survey, localization, face, 3d gaussian  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: gaussian splatting, robotics, ar, survey, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: nerf, geometry, efficient, gaussian splatting, ar, survey, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: compression, dynamic, 4d, efficient, gaussian splatting, compact, high-fidelity, ar, 3d reconstruction, survey, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: nerf, slam, gaussian splatting, mapping, robotics, semantic, ar, survey, localization, understanding, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: slam, efficient, gaussian splatting, mapping, high-fidelity, robotics, semantic, ar, survey, localization, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: nerf, geometry, fast, 4d, gaussian splatting, motion, ar, survey, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: animation, efficient, avatar, gaussian splatting, lighting, efficient rendering, real-time rendering, ar, 3d reconstruction, survey, face, 3d gaussian  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: nerf, efficient, human, gaussian splatting, lightweight, ar, survey, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: nerf, understanding, slam, fast, efficient, gaussian splatting, ar, survey, neural rendering, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 233 papers*

- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: fast, gaussian splatting, semantic, ar, 3d gaussian  
- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: dynamic, fast, 4d, gaussian splatting, motion, ar, deformation, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, motion, high-fidelity, semantic, real-time rendering, ar, deformation  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: geometry, efficient, compact, gaussian splatting, real-time rendering, ar, 3d gaussian  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, ar, face, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: slam, fast, efficient, gaussian splatting, mapping, high-fidelity, tracking, ar, localization, face, 3d gaussian  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ray casting, geometry, fast, efficient, gaussian splatting, robotics, ar, 3d gaussian  
- **[SGI: Structured 2D Gaussians for Efficient and Compact Large Image Representation](https://arxiv.org/abs/2603.07789v2)**  
  Authors: Zixuan Pan, Kaiyuan Tang, Jun Xia, Yifan Qin, Lin Gu, Chaoli Wang, Jianxu Chen, Yiyu Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07789v2.pdf)  
  Keywords: fast, efficient, gaussian splatting, compact, efficient rendering, lightweight, ar, compression  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, fast, efficient, reflection, gaussian splatting, ray tracing, lightweight, ar, face  

### Applications

*Showing the latest 50 out of 996 papers*

- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: face, reflection, gaussian splatting, lighting, high-fidelity, ar, relighting, 3d gaussian  
- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: fast, gaussian splatting, semantic, ar, 3d gaussian  
- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: dynamic, fast, 4d, gaussian splatting, motion, ar, deformation, 3d gaussian  
- **[Spectral Defense Against Resource-Targeting Attack in 3D Gaussian Splatting](https://arxiv.org/abs/2603.12796v1)**  
  Authors: Yang Chen, Yi Yu, Jiaming He, Yueqi Duan, Zheng Zhu, Yap-Peng Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12796v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, ar  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: efficient, gaussian splatting, motion, lighting, ar, 3d gaussian  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, body, ar, face  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, motion, high-fidelity, semantic, real-time rendering, ar, deformation  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: geometry, efficient, compact, gaussian splatting, real-time rendering, ar, 3d gaussian  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, ar, face, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 339 papers*

- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: face, reflection, gaussian splatting, lighting, high-fidelity, ar, relighting, 3d gaussian  
- **[Spectral Defense Against Resource-Targeting Attack in 3D Gaussian Splatting](https://arxiv.org/abs/2603.12796v1)**  
  Authors: Yang Chen, Yi Yu, Jiaming He, Yueqi Duan, Zheng Zhu, Yap-Peng Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12796v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, ar  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, body, ar, face  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, ar, face, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: slam, fast, efficient, gaussian splatting, mapping, high-fidelity, tracking, ar, localization, face, 3d gaussian  
- **[X-GS: An Extensible Open Framework for Perceiving and Thinking via 3D Gaussian Splatting](https://arxiv.org/abs/2603.09632v2)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09632v2.pdf)  
  Keywords: slam, gaussian splatting, semantic, ar, face, 3d gaussian  
- **[SurgCalib: Gaussian Splatting-Based Hand-Eye Calibration for Robot-Assisted Minimally Invasive Surgery](https://arxiv.org/abs/2603.08983v1)**  
  Authors: Zijian Wu, Shuojue Yang, Yu Chung Lee, Eitan Prisman, Yueming Jin, Septimiu E. Salcudean  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08983v1.pdf)  
  Keywords: vr, gaussian splatting, face, ar  
- **[DynamicVGGT: Learning Dynamic Point Maps for 4D Scene Reconstruction in Autonomous Driving](https://arxiv.org/abs/2603.08254v1)**  
  Authors: Zhuolin He, Jing Li, Guanghao Li, Xiaolei Chen, Jiacheng Tang, Siyang Zhang, Zhounan Jin, Feipeng Cai, Bin Li, Jian Pu, Jia Cai, Xiangyang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08254v1.pdf)  
  Keywords: autonomous driving, dynamic, geometry, 4d, efficient, gaussian splatting, motion, head, ar, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, fast, efficient, reflection, gaussian splatting, ray tracing, lightweight, ar, face  

### Dynamic Scene

*Showing the latest 50 out of 399 papers*

- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: dynamic, fast, 4d, gaussian splatting, motion, ar, deformation, 3d gaussian  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: efficient, gaussian splatting, motion, lighting, ar, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, motion, high-fidelity, semantic, real-time rendering, ar, deformation  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[ProGS: Towards Progressive Coding for 3D Gaussian Splatting](https://arxiv.org/abs/2603.09703v1)**  
  Authors: Zhiye Tang, Lingzhuo Liu, Shengjie Jiao, Qiudan Zhang, Junhui Hou, You Yang, Xu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09703v1.pdf)  
  Keywords: dynamic, efficient, gaussian splatting, ar, compression, 3d gaussian  
- **[DiffWind: Physics-Informed Differentiable Modeling of Wind-Driven Object Dynamics](https://arxiv.org/abs/2603.09668v1)**  
  Authors: Yuanhang Lei, Boming Zhao, Zesong Yang, Xingxuan Li, Tao Cheng, Haocheng Peng, Ru Zhang, Yang Yang, Siyuan Huang, Yujun Shen, Ruizhen Hu, Hujun Bao, Zhaopeng Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09668v1.pdf)  
  Keywords: dynamic, gaussian splatting, motion, ar, deformation, 3d gaussian  
- **[HDR-NSFF: High Dynamic Range Neural Scene Flow Fields](https://arxiv.org/abs/2603.08313v1)**  
  Authors: Shin Dong-Yeon, Kim Jun-Seong, Kwon Byung-Ki, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08313v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shin-dong-yeon.github.io/HDR-NSFF/)  
  Keywords: dynamic, geometry, 4d, gaussian splatting, motion, mapping, semantic, ar  
- **[DynamicVGGT: Learning Dynamic Point Maps for 4D Scene Reconstruction in Autonomous Driving](https://arxiv.org/abs/2603.08254v1)**  
  Authors: Zhuolin He, Jing Li, Guanghao Li, Xiaolei Chen, Jiacheng Tang, Siyang Zhang, Zhounan Jin, Feipeng Cai, Bin Li, Jian Pu, Jia Cai, Xiangyang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08254v1.pdf)  
  Keywords: autonomous driving, dynamic, geometry, 4d, efficient, gaussian splatting, motion, head, ar, 3d gaussian  
- **[EmbedTalk: Triplane-Free Talking Head Synthesis using Embedding-Driven Gaussian Deformation](https://arxiv.org/abs/2603.07604v1)**  
  Authors: Arpita Saggar, Jonathan C. Darling, Duygu Sarikaya, David C. Hogg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07604v1.pdf)  
  Keywords: 4d, gaussian splatting, motion, compact, head, ar, deformation, 3d gaussian  
- **[ReconDrive: Fast Feed-Forward 4D Gaussian Splatting for Autonomous Driving Scene Reconstruction](https://arxiv.org/abs/2603.07552v1)**  
  Authors: Haibao Yu, Kuntao Xiao, Jiahang Wang, Ruiyang Hao, Yuxin Huang, Guoran Hu, Haifang Qin, Bowen Jing, Yuntian Bo, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07552v1.pdf)  
  Keywords: autonomous driving, dynamic, fast, 4d, gaussian splatting, motion, high-fidelity, head, ar  

### Few-shot

*Showing the latest 50 out of 80 papers*

- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: fast, gaussian splatting, sparse-view, ar, 3d gaussian  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: geometry, gaussian splatting, sparse-view, ar, 3d gaussian  
- **[DSA-SRGS: Super-Resolution Gaussian Splatting for Dynamic Sparse-View DSA Reconstruction](https://arxiv.org/abs/2603.04770v1)**  
  Authors: Shiyu Zhang, Zhicong Wu, Huangxuan Zhao, Zhentao Liu, Lei Chen, Yong Luo, Lefei Zhang, Zhiming Cui, Ziwen Ke, Bo Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04770v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, sparse-view, ar  
- **[Multimodal-Prior-Guided Importance Sampling for Hierarchical Gaussian Splatting in Sparse-View Novel View Synthesis](https://arxiv.org/abs/2603.02866v1)**  
  Authors: Kaiqiang Xiong, Zhanke Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02866v1.pdf)  
  Keywords: gaussian splatting, sparse-view, semantic, ar, 3d gaussian  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, sparse-view, semantic, sparse view, ar, 3d gaussian  
- **[HeroGS: Hierarchical Guidance for Robust 3D Gaussian Splatting under Sparse Views](https://arxiv.org/abs/2603.01099v2)**  
  Authors: Jiashu Li, Xumeng Han, Zhaoyang Wei, Zipeng Wang, Kuiran Wang, Guorong Li, Zhenjun Han, Jianbin Jiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01099v2.pdf)  
  Keywords: geometry, gaussian splatting, sparse-view, high-fidelity, sparse view, ar, 3d gaussian  
- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, 3d reconstruction, 3d gaussian  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: efficient, gaussian splatting, sparse-view, head, ar, compression, 3d gaussian  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: dynamic, geometry, gaussian splatting, motion, sparse-view, ar, deformation, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 371 papers*

- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: geometry, efficient, compact, gaussian splatting, real-time rendering, ar, 3d gaussian  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, ar, face, 3d gaussian  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ray casting, geometry, fast, efficient, gaussian splatting, robotics, ar, 3d gaussian  
- **[HDR-NSFF: High Dynamic Range Neural Scene Flow Fields](https://arxiv.org/abs/2603.08313v1)**  
  Authors: Shin Dong-Yeon, Kim Jun-Seong, Kwon Byung-Ki, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08313v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shin-dong-yeon.github.io/HDR-NSFF/)  
  Keywords: dynamic, geometry, 4d, gaussian splatting, motion, mapping, semantic, ar  
- **[DynamicVGGT: Learning Dynamic Point Maps for 4D Scene Reconstruction in Autonomous Driving](https://arxiv.org/abs/2603.08254v1)**  
  Authors: Zhuolin He, Jing Li, Guanghao Li, Xiaolei Chen, Jiacheng Tang, Siyang Zhang, Zhounan Jin, Feipeng Cai, Bin Li, Jian Pu, Jia Cai, Xiangyang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08254v1.pdf)  
  Keywords: autonomous driving, dynamic, geometry, 4d, efficient, gaussian splatting, motion, head, ar, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, fast, efficient, reflection, gaussian splatting, ray tracing, lightweight, ar, face  
- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: slam, geometry, gaussian splatting, high-fidelity, ar, localization, 3d gaussian  
- **[ColonSplat: Reconstruction of Peristaltic Motion in Colonoscopy with Dynamic Gaussian Splatting](https://arxiv.org/abs/2603.06860v1)**  
  Authors: Weronika Smolak-Dyżewska, Joanna Kaleta, Diego Dall'Alba, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wmito.github.io/ColonSplat)  
  Keywords: dynamic, gaussian splatting, motion, ar, 3d reconstruction, deformation  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: geometry, gaussian splatting, urban scene, ar, 3d reconstruction, face, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 62 papers*

- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: geometry, gaussian splatting, urban scene, ar, 3d reconstruction, face, 3d gaussian  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: outdoor, nerf, fast, relightable, illumination, gaussian splatting, reflection, lighting, ar, 3d reconstruction, relighting, 3d gaussian  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: outdoor, fast, gaussian splatting, lighting, lightweight, semantic, ar, face, 3d gaussian  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: outdoor, nerf, efficient, gaussian splatting, high-fidelity, ar, 3d reconstruction, vr, neural rendering, 3d gaussian  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: outdoor, geometry, gaussian splatting, mapping, lighting, head, semantic, ar, localization, 3d gaussian  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: autonomous driving, global illumination, nerf, outdoor, illumination, gaussian splatting, lighting, real-time rendering, ar, 3d gaussian  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v2)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v2.pdf)  
  Keywords: outdoor, dynamic, geometry, illumination, relightable, gaussian splatting, high-fidelity, lighting, lightweight, ar, 3d gaussian  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: efficient, gaussian splatting, head, large scene, ar, 3d gaussian  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: autonomous driving, dynamic, geometry, 4d, efficient, gaussian splatting, motion, urban scene, semantic, ar, 3d gaussian  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: outdoor, gaussian splatting, segmentation, semantic, ar, compression, vr, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 422 papers*

- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: efficient, gaussian splatting, motion, lighting, ar, 3d gaussian  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: geometry, efficient, compact, gaussian splatting, real-time rendering, ar, 3d gaussian  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[PolGS++: Physically-Guided Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://arxiv.org/abs/2603.10801v1)**  
  Authors: Yufei Han, Chu Zhou, Youwei Lyu, Qi Chen, Si Li, Boxin Shi, Yunpeng Jia, Heng Guo, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10801v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, ar, face, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[ReCoSplat: Autoregressive Feed-Forward Gaussian Splatting Using Render-and-Compare](https://arxiv.org/abs/2603.09968v1)**  
  Authors: Freeman Cheng, Botao Ye, Xueting Li, Junqi You, Fangneng Zhan, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09968v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://freemancheng.com/ReCoSplat)  
  Keywords: gaussian splatting, ar, compression  
- **[GSStream: 3D Gaussian Splatting based Volumetric Scene Streaming System](https://arxiv.org/abs/2603.09718v1)**  
  Authors: Zhiye Tang, Qiudan Zhang, Lei Zhang, Junhui Hou, You Yang, Xu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09718v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://youtu.be/3WEe8PN8yvA.)  
  Keywords: efficient, compact, gaussian splatting, ar, 3d gaussian  
- **[ProGS: Towards Progressive Coding for 3D Gaussian Splatting](https://arxiv.org/abs/2603.09703v1)**  
  Authors: Zhiye Tang, Lingzhuo Liu, Shengjie Jiao, Qiudan Zhang, Junhui Hou, You Yang, Xu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09703v1.pdf)  
  Keywords: dynamic, efficient, gaussian splatting, ar, compression, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: slam, fast, efficient, gaussian splatting, mapping, high-fidelity, tracking, ar, localization, face, 3d gaussian  
- **[DenoiseSplat: Feed-Forward Gaussian Splatting for Noisy 3D Scene Reconstruction](https://arxiv.org/abs/2603.09291v1)**  
  Authors: Fuzhen Jiang, Zhuoran Li, Yinlin Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09291v1.pdf)  
  Keywords: nerf, gaussian splatting, robotics, lightweight, ar, vr, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 220 papers*

- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: face, reflection, gaussian splatting, lighting, high-fidelity, ar, relighting, 3d gaussian  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, body, ar, face  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, motion, high-fidelity, semantic, real-time rendering, ar, deformation  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: slam, fast, efficient, gaussian splatting, mapping, high-fidelity, tracking, ar, localization, face, 3d gaussian  
- **[ReconDrive: Fast Feed-Forward 4D Gaussian Splatting for Autonomous Driving Scene Reconstruction](https://arxiv.org/abs/2603.07552v1)**  
  Authors: Haibao Yu, Kuntao Xiao, Jiahang Wang, Ruiyang Hao, Yuxin Huang, Guoran Hu, Haifang Qin, Bowen Jing, Yuntian Bo, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07552v1.pdf)  
  Keywords: autonomous driving, dynamic, fast, 4d, gaussian splatting, motion, high-fidelity, head, ar  
- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: slam, geometry, gaussian splatting, high-fidelity, ar, localization, 3d gaussian  
- **[FTSplat: Feed-forward Triangle Splatting Network](https://arxiv.org/abs/2603.05932v1)**  
  Authors: Xiong Jinlin, Li Can, Shen Jiawei, Qi Zhigang, Sun Lei, Zhao Dongyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05932v1.pdf)  
  Keywords: nerf, geometry, efficient, gaussian splatting, high-fidelity, robotics, ar, face, 3d gaussian  
- **[LiftAvatar: Kinematic-Space Completion for Expression-Controlled 3D Gaussian Avatar Animation](https://arxiv.org/abs/2603.02129v1)**  
  Authors: Hualiang Wei, Shunran Jia, Jialun Liu, Wenhui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02129v1.pdf)  
  Keywords: efficient, avatar, gaussian splatting, high-fidelity, head, ar, 3d gaussian, animation  

### Ray Tracing

- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ray casting, geometry, fast, efficient, gaussian splatting, robotics, ar, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, fast, efficient, reflection, gaussian splatting, ray tracing, lightweight, ar, face  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: global illumination, illumination, efficient, reflection, gaussian splatting, ray tracing, lighting, ar, relighting  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: autonomous driving, global illumination, nerf, outdoor, illumination, gaussian splatting, lighting, real-time rendering, ar, 3d gaussian  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: global illumination, geometry, illumination, efficient, gaussian splatting, lighting, ar, shadow, relighting  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: gaussian splatting, ray tracing, 3d gaussian, ar  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: gaussian splatting, head, lightweight, medical, ar, path tracing, understanding, vr  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: efficient, gaussian splatting, ray tracing, head, ar, 3d gaussian, acceleration  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, efficient, gaussian splatting, sparse-view, ray marching, efficient rendering, shadow, ar, 3d reconstruction, 3d gaussian  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: geometry, fast, gaussian splatting, motion, ray tracing, ar, 3d reconstruction, understanding, 3d gaussian  

### Relighting

*Showing the latest 50 out of 134 papers*

- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: face, reflection, gaussian splatting, lighting, high-fidelity, ar, relighting, 3d gaussian  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: efficient, gaussian splatting, motion, lighting, ar, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, fast, efficient, reflection, gaussian splatting, ray tracing, lightweight, ar, face  
- **[3DGS-HPC: Distractor-free 3D Gaussian Splatting with Hybrid Patch-wise Classification](https://arxiv.org/abs/2603.07587v1)**  
  Authors: Jiahao Chen, Yipeng Qin, Ganlong Zhao, Xin Li, Wenping Wang, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07587v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, shadow, 3d gaussian  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: geometry, illumination, efficient, reflection, gaussian splatting, ar, face, 3d gaussian  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: outdoor, nerf, fast, relightable, illumination, gaussian splatting, reflection, lighting, ar, 3d reconstruction, relighting, 3d gaussian  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: global illumination, illumination, efficient, reflection, gaussian splatting, ray tracing, lighting, ar, relighting  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v2)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v2.pdf)  
  Keywords: nerf, dynamic, gaussian splatting, lighting, ar, 3d gaussian  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: geometry, fast, efficient, gaussian splatting, high-fidelity, lighting, ar, 3d reconstruction, face, 3d gaussian  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: outdoor, fast, gaussian splatting, lighting, lightweight, semantic, ar, face, 3d gaussian  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: slam, fast, efficient, gaussian splatting, mapping, high-fidelity, tracking, ar, localization, face, 3d gaussian  
- **[X-GS: An Extensible Open Framework for Perceiving and Thinking via 3D Gaussian Splatting](https://arxiv.org/abs/2603.09632v2)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09632v2.pdf)  
  Keywords: slam, gaussian splatting, semantic, ar, face, 3d gaussian  
- **[Improving Continual Learning for Gaussian Splatting based Environments Reconstruction on Commercial Off-the-Shelf Edge Devices](https://arxiv.org/abs/2603.08499v1)**  
  Authors: Ivan Zaino, Matteo Risso, Daniele Jahier Pagliari, Miguel de Prado, Toon Van de Maele, Alessio Burrello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08499v1.pdf)  
  Keywords: slam, compact, gaussian splatting, robotics, ar  
- **[HDR-NSFF: High Dynamic Range Neural Scene Flow Fields](https://arxiv.org/abs/2603.08313v1)**  
  Authors: Shin Dong-Yeon, Kim Jun-Seong, Kwon Byung-Ki, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08313v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shin-dong-yeon.github.io/HDR-NSFF/)  
  Keywords: dynamic, geometry, 4d, gaussian splatting, motion, mapping, semantic, ar  
- **[MipSLAM: Alias-Free Gaussian Splatting SLAM](https://arxiv.org/abs/2603.06989v1)**  
  Authors: Yingzhao Li, Yan Li, Shixiong Tian, Yanjie Liu, Lijun Zhao, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06989v1.pdf)  
  Keywords: slam, geometry, gaussian splatting, high-fidelity, ar, localization, 3d gaussian  
- **[Transforming Omnidirectional RGB-LiDAR data into 3D Gaussian Splatting](https://arxiv.org/abs/2603.06061v1)**  
  Authors: Semin Bae, Hansol Lim, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06061v1.pdf)  
  Keywords: autonomous driving, geometry, fast, gaussian splatting, motion, robotics, head, tracking, ar, 3d gaussian  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: dynamic, efficient, gaussian splatting, efficient rendering, tracking, ar, segmentation  
- **[SR3R: Rethinking Super-Resolution 3D Reconstruction With Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2602.24020v1)**  
  Authors: Xiang Feng, Xiangbo Wang, Tieshi Zhong, Chengkai Wang, Yiting Zhao, Tianxiang Xu, Zhenzhong Kuang, Feiwei Qin, Xuefei Yin, Yanming Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24020v1.pdf)  
  Keywords: geometry, gaussian splatting, mapping, ar, 3d reconstruction, 3d gaussian  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: dynamic, 4d, efficient, gaussian splatting, head, tracking, ar, segmentation, understanding, 3d gaussian  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: nerf, dynamic, slam, gaussian splatting, ar, 3d reconstruction, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 233 papers*

- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: fast, gaussian splatting, semantic, ar, 3d gaussian  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, motion, high-fidelity, semantic, real-time rendering, ar, deformation  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: efficient, gaussian splatting, high-fidelity, sparse view, ar, 3d reconstruction, understanding, 3d gaussian  
- **[SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning](https://arxiv.org/abs/2603.10446v2)**  
  Authors: Jianhe Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10446v2.pdf)  
  Keywords: fast, efficient, avatar, gaussian splatting, motion, high-fidelity, human, ar, segmentation, face, 3d gaussian  
- **[X-GS: An Extensible Open Framework for Perceiving and Thinking via 3D Gaussian Splatting](https://arxiv.org/abs/2603.09632v2)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09632v2.pdf)  
  Keywords: slam, gaussian splatting, semantic, ar, face, 3d gaussian  
- **[HDR-NSFF: High Dynamic Range Neural Scene Flow Fields](https://arxiv.org/abs/2603.08313v1)**  
  Authors: Shin Dong-Yeon, Kim Jun-Seong, Kwon Byung-Ki, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08313v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shin-dong-yeon.github.io/HDR-NSFF/)  
  Keywords: dynamic, geometry, 4d, gaussian splatting, motion, mapping, semantic, ar  
- **[Holi-Spatial: Evolving Video Streams into Holistic 3D Spatial Intelligence](https://arxiv.org/abs/2603.07660v1)**  
  Authors: Yuanyuan Gao, Hao Li, Yifei Liu, Xinhao Ji, Yuning Gong, Yuanjun Liao, Fangfu Liu, Manyuan Zhang, Yuchen Yang, Dan Xu, Xue Yang, Huaxi Huang, Hongjie Zhang, Ziwei Liu, Xiao Sun, Dingwen Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07660v1.pdf)  
  Keywords: human, gaussian splatting, semantic, ar, understanding, 3d gaussian  
- **[3DGS-HPC: Distractor-free 3D Gaussian Splatting with Hybrid Patch-wise Classification](https://arxiv.org/abs/2603.07587v1)**  
  Authors: Jiahao Chen, Yipeng Qin, Ganlong Zhao, Xin Li, Wenping Wang, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07587v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, shadow, 3d gaussian  
- **[VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction](https://arxiv.org/abs/2603.06210v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06210v1.pdf)  
  Keywords: autonomous driving, geometry, gaussian splatting, head, semantic, ar, understanding, 3d gaussian  
- **[GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins](https://arxiv.org/abs/2603.05108v1)**  
  Authors: Yichen Cai, Paul Jansonnie, Cristiana de Farias, Oleg Arenz, Jan Peters  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05108v1.pdf)  
  Keywords: dynamic, efficient, gaussian splatting, efficient rendering, tracking, ar, segmentation  



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