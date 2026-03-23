# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-03-23 01:18:50

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
- [Acceleration](#acceleration) (232 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (342 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (397 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (80 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (373 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (61 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (424 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (225 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (26 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (134 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (149 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (236 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: ray tracing, ar, 3d gaussian, survey, gaussian splatting, mapping  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, ar, efficient, 3d gaussian, face, survey, gaussian splatting, tracking, dynamic, mapping, localization, slam  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, 3d gaussian, survey, gaussian splatting, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: ar, efficient, 3d gaussian, geometry, nerf, gaussian splatting, survey  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: ar, 3d reconstruction, high-fidelity, compact, efficient, 3d gaussian, 4d, survey, gaussian splatting, dynamic, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: ar, understanding, 3d gaussian, nerf, gaussian splatting, survey, localization, mapping, robotics, semantic, slam  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: ar, high-fidelity, efficient, 3d gaussian, survey, gaussian splatting, localization, mapping, robotics, semantic, slam  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: motion, ar, 3d gaussian, 4d, geometry, nerf, gaussian splatting, survey, fast  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, avatar, real-time rendering, 3d gaussian, face, survey, gaussian splatting, animation, lighting, efficient rendering  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: ar, efficient, lightweight, understanding, human, nerf, gaussian splatting, survey  

### Acceleration

*Showing the latest 50 out of 232 papers*

- **[Fourier Splatting: Generalized Fourier encoded primitives for scalable radiance fields](https://arxiv.org/abs/2603.19834v1)**  
  Authors: Mihnea-Bogdan Jurca, Bert Van hauwermeiren, Adrian Munteanu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19834v1.pdf)  
  Keywords: ar, high-fidelity, efficient, real-time rendering, 3d gaussian, gaussian splatting  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: ar, efficient, real-time rendering, 4d, gaussian splatting, dynamic, fast  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: semantic, ar, avatar, head, geometry, tracking, fast  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, high-fidelity, efficient, ray marching, real-time rendering, 3d gaussian, gaussian splatting  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, 3d gaussian, nerf, gaussian splatting, tracking, dynamic, lighting, fast  
- **[Scene Generation at Absolute Scale: Utilizing Semantic and Geometric Guidance From Text for Accurate and Interpretable 3D Indoor Scene Generation](https://arxiv.org/abs/2603.13910v1)**  
  Authors: Stefan Ainetter, Thomas Deixelberger, Edoardo A. Dominici, Philipp Drescher, Konstantinos Vardis, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13910v1.pdf)  
  Keywords: ar, semantic, 3d gaussian, gaussian splatting, fast  
- **[RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://arxiv.org/abs/2603.13783v1)**  
  Authors: Xuezhen Wang, Li Ma, Yulin Shen, Zeyu Wang, Pedro V. Sander  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.13783v1.pdf)  
  Keywords: motion, ar, deformation, 3d gaussian, 4d, gaussian splatting, dynamic, fast  
- **[Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting](https://arxiv.org/abs/2603.11543v1)**  
  Authors: Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11543v1.pdf)  
  Keywords: motion, ar, high-fidelity, deformation, real-time rendering, 4d, gaussian splatting, dynamic, semantic  
- **[Mobile-GS: Real-time Gaussian Splatting for Mobile Devices](https://arxiv.org/abs/2603.11531v1)**  
  Authors: Xiaobiao Du, Yida Wang, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11531v1.pdf)  
  Keywords: ar, compact, efficient, real-time rendering, 3d gaussian, geometry, gaussian splatting  

### Applications

*Showing the latest 50 out of 996 papers*

- **[Fourier Splatting: Generalized Fourier encoded primitives for scalable radiance fields](https://arxiv.org/abs/2603.19834v1)**  
  Authors: Mihnea-Bogdan Jurca, Bert Van hauwermeiren, Adrian Munteanu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19834v1.pdf)  
  Keywords: ar, high-fidelity, efficient, real-time rendering, 3d gaussian, gaussian splatting  
- **[HUGE-Bench: A Benchmark for High-Level UAV Vision-Language-Action Tasks](https://arxiv.org/abs/2603.19822v1)**  
  Authors: Jingyu Guo, Ziye Chen, Ziwen Li, Zhengqing Gao, Jiaxin Huang, Hanlue Zhang, Fengming Huang, Yu Yao, Tongliang Liu, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19822v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, lighting, semantic  
- **[StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention](https://arxiv.org/abs/2603.19552v1)**  
  Authors: Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19552v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://streetforward.github.io.)  
  Keywords: motion, ar, high-fidelity, efficient, 3d gaussian, geometry, gaussian splatting, dynamic, autonomous driving  
- **[Matryoshka Gaussian Splatting](https://arxiv.org/abs/2603.19234v2)**  
  Authors: Zhilin Guo, Boqiao Zhang, Hakan Aktas, Kyle Fogarty, Jeffrey Hu, Nursena Koprucu Aslan, Wenzhao Li, Canberk Baykal, Albert Miao, Josef Bengtson, Chenliang Zhou, Weihao Xia, Cristina Nader Vasconcelos, Cengiz Oztireli  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19234v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar  
- **[Reconstruction Matters: Learning Geometry-Aligned BEV Representation through 3D Gaussian Splatting](https://arxiv.org/abs/2603.19193v1)**  
  Authors: Yiren Lu, Xin Ye, Burhaneddin Yaman, Jingru Luo, Zhexiao Xiong, Liu Ren, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19193v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, understanding, 3d gaussian, geometry, gaussian splatting, autonomous driving, semantic, segmentation  
- **[GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137v1)**  
  Authors: Yiren Lu, Yi Du, Disheng Liu, Yunlai Zhou, Chen Wang, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19137v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, geometry, gaussian splatting, semantic  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[From ex(p) to poly: Gaussian Splatting with Polynomial Kernels](https://arxiv.org/abs/2603.18707v1)**  
  Authors: Joerg H. Mueller, Martin Winter, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18707v1.pdf)  
  Keywords: gaussian splatting, ar  
- **[OnlinePG: Online Open-Vocabulary Panoptic Mapping with 3D Gaussian Splatting](https://arxiv.org/abs/2603.18510v1)**  
  Authors: Hongjia Zhai, Qi Zhang, Xiaokun Pan, Xiyu Zhang, Yitong Dong, Huaqi Zhang, Dan Xu, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18510v1.pdf)  
  Keywords: ar, understanding, efficient, 3d gaussian, gaussian splatting, mapping, semantic  
- **[Inst4DGS: Instance-Decomposed 4D Gaussian Splatting with Multi-Video Label Permutation Learning](https://arxiv.org/abs/2603.18402v1)**  
  Authors: Yonghan Lee, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18402v1.pdf)  
  Keywords: motion, ar, 4d, tracking, gaussian splatting, dynamic, segmentation  

### Avatar Generation

*Showing the latest 50 out of 342 papers*

- **[Semantic Segmentation and Depth Estimation for Real-Time Lunar Surface Mapping Using 3D Gaussian Splatting](https://arxiv.org/abs/2603.18218v1)**  
  Authors: Guillem Casadesus Vila, Adam Dai, Grace Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18218v1.pdf)  
  Keywords: ar, understanding, 3d gaussian, face, gaussian splatting, mapping, lighting, semantic, segmentation, slam  
- **[CrowdGaussian: Reconstructing High-Fidelity 3D Gaussians for Human Crowd from a Single Image](https://arxiv.org/abs/2603.17779v1)**  
  Authors: Yizheng Song, Yiyu Zhuang, Qipeng Xu, Haixiang Wang, Jiahe Zhu, Jing Tian, Siyu Zhu, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17779v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, human, geometry, gaussian splatting  
- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, high-fidelity, avatar, 3d gaussian, human, face, gaussian splatting, animation  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, efficient, head, tracking, gaussian splatting, dynamic, outdoor, slam  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: semantic, ar, avatar, head, geometry, tracking, fast  
- **[KGS-GCN: Enhancing Sparse Skeleton Sensing via Kinematics-Driven Gaussian Splatting and Probabilistic Topology for Action Recognition](https://arxiv.org/abs/2603.16943v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Liping Zhang, Jie Li, Jiaxin Gao, Wenbo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16943v1.pdf)  
  Keywords: recognition, ar, human, gaussian splatting, dynamic, semantic  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, head, gaussian splatting, dynamic  
- **[In-Field 3D Wheat Head Instance Segmentation From TLS Point Clouds Using Deep Learning Without Manual Labels](https://arxiv.org/abs/2603.14309v1)**  
  Authors: Tomislav Medic, Liangliang Nan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14309v1.pdf)  
  Keywords: ar, head, 3d gaussian, gaussian splatting, segmentation  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, reflection, face, gaussian splatting, lighting, relighting  
- **[Spectral Defense Against Resource-Targeting Attack in 3D Gaussian Splatting](https://arxiv.org/abs/2603.12796v1)**  
  Authors: Yang Chen, Yi Yu, Jiaming He, Yueqi Duan, Zheng Zhu, Yap-Peng Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, face  

### Dynamic Scene

*Showing the latest 50 out of 397 papers*

- **[StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention](https://arxiv.org/abs/2603.19552v1)**  
  Authors: Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19552v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://streetforward.github.io.)  
  Keywords: motion, ar, high-fidelity, efficient, 3d gaussian, geometry, gaussian splatting, dynamic, autonomous driving  
- **[Reconstruction Matters: Learning Geometry-Aligned BEV Representation through 3D Gaussian Splatting](https://arxiv.org/abs/2603.19193v1)**  
  Authors: Yiren Lu, Xin Ye, Burhaneddin Yaman, Jingru Luo, Zhexiao Xiong, Liu Ren, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19193v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, understanding, 3d gaussian, geometry, gaussian splatting, autonomous driving, semantic, segmentation  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[Inst4DGS: Instance-Decomposed 4D Gaussian Splatting with Multi-Video Label Permutation Learning](https://arxiv.org/abs/2603.18402v1)**  
  Authors: Yonghan Lee, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18402v1.pdf)  
  Keywords: motion, ar, 4d, tracking, gaussian splatting, dynamic, segmentation  
- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: ar, efficient, real-time rendering, 4d, gaussian splatting, dynamic, fast  
- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, high-fidelity, avatar, 3d gaussian, human, face, gaussian splatting, animation  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, efficient, head, tracking, gaussian splatting, dynamic, outdoor, slam  
- **[KGS-GCN: Enhancing Sparse Skeleton Sensing via Kinematics-Driven Gaussian Splatting and Probabilistic Topology for Action Recognition](https://arxiv.org/abs/2603.16943v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Liping Zhang, Jie Li, Jiaxin Gao, Wenbo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16943v1.pdf)  
  Keywords: recognition, ar, human, gaussian splatting, dynamic, semantic  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, 3d gaussian, nerf, gaussian splatting, tracking, dynamic, lighting, fast  
- **[Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting](https://arxiv.org/abs/2603.14316v1)**  
  Authors: Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14316v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, head, gaussian splatting, dynamic  

### Few-shot

*Showing the latest 50 out of 80 papers*

- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, 3d reconstruction, 3d gaussian, geometry, gaussian splatting, sparse-view, semantic, segmentation  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: ar, 3d reconstruction, high-fidelity, efficient, sparse view, understanding, 3d gaussian, gaussian splatting  
- **[Active View Selection with Perturbed Gaussian Ensemble for Tomographic Reconstruction](https://arxiv.org/abs/2603.06852v1)**  
  Authors: Yulun Wu, Ruyi Zha, Wei Cao, Yingying Li, Yuanhao Cai, Yaoyao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06852v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, sparse-view, fast  
- **[CylinderSplat: 3D Gaussian Splatting with Cylindrical Triplanes for Panoramic Novel View Synthesis](https://arxiv.org/abs/2603.05882v1)**  
  Authors: Qiwei Wang, Xianghui Ze, Jingyi Yu, Yujiao Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05882v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, sparse-view  
- **[DSA-SRGS: Super-Resolution Gaussian Splatting for Dynamic Sparse-View DSA Reconstruction](https://arxiv.org/abs/2603.04770v1)**  
  Authors: Shiyu Zhang, Zhicong Wu, Huangxuan Zhao, Zhentao Liu, Lei Chen, Yong Luo, Lefei Zhang, Zhiming Cui, Ziwen Ke, Bo Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.04770v1.pdf)  
  Keywords: ar, 4d, gaussian splatting, sparse-view, dynamic  
- **[Multimodal-Prior-Guided Importance Sampling for Hierarchical Gaussian Splatting in Sparse-View Novel View Synthesis](https://arxiv.org/abs/2603.02866v1)**  
  Authors: Kaiqiang Xiong, Zhanke Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02866v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, sparse-view, semantic  
- **[Sparse View Distractor-Free Gaussian Splatting](https://arxiv.org/abs/2603.01603v1)**  
  Authors: Yi Gu, Zhaorui Wang, Jiahang Cao, Jiaxu Wang, Mingle Zhao, Dongjun Ye, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01603v1.pdf)  
  Keywords: semantic, ar, efficient, sparse view, 3d gaussian, geometry, gaussian splatting, sparse-view, fast  
- **[HeroGS: Hierarchical Guidance for Robust 3D Gaussian Splatting under Sparse Views](https://arxiv.org/abs/2603.01099v2)**  
  Authors: Jiashu Li, Xumeng Han, Zhaoyang Wei, Zipeng Wang, Kuiran Wang, Guorong Li, Zhenjun Han, Jianbin Jiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01099v2.pdf)  
  Keywords: ar, high-fidelity, sparse view, 3d gaussian, geometry, gaussian splatting, sparse-view  
- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: ar, 3d reconstruction, sparse view, 3d gaussian, gaussian splatting  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: ar, efficient, head, 3d gaussian, gaussian splatting, sparse-view, compression  

### Geometry Reconstruction

*Showing the latest 50 out of 373 papers*

- **[HUGE-Bench: A Benchmark for High-Level UAV Vision-Language-Action Tasks](https://arxiv.org/abs/2603.19822v1)**  
  Authors: Jingyu Guo, Ziye Chen, Ziwen Li, Zhengqing Gao, Jiaxin Huang, Hanlue Zhang, Fengming Huang, Yu Yao, Tongliang Liu, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19822v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, lighting, semantic  
- **[StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention](https://arxiv.org/abs/2603.19552v1)**  
  Authors: Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19552v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://streetforward.github.io.)  
  Keywords: motion, ar, high-fidelity, efficient, 3d gaussian, geometry, gaussian splatting, dynamic, autonomous driving  
- **[Reconstruction Matters: Learning Geometry-Aligned BEV Representation through 3D Gaussian Splatting](https://arxiv.org/abs/2603.19193v1)**  
  Authors: Yiren Lu, Xin Ye, Burhaneddin Yaman, Jingru Luo, Zhexiao Xiong, Liu Ren, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19193v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, understanding, 3d gaussian, geometry, gaussian splatting, autonomous driving, semantic, segmentation  
- **[GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137v1)**  
  Authors: Yiren Lu, Yi Du, Disheng Liu, Yunlai Zhou, Chen Wang, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19137v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, geometry, gaussian splatting, semantic  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[CrowdGaussian: Reconstructing High-Fidelity 3D Gaussians for Human Crowd from a Single Image](https://arxiv.org/abs/2603.17779v1)**  
  Authors: Yizheng Song, Yiyu Zhuang, Qipeng Xu, Haixiang Wang, Jiahe Zhu, Jing Tian, Siyu Zhu, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17779v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, human, geometry, gaussian splatting  
- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, 3d reconstruction, 3d gaussian, geometry, gaussian splatting, sparse-view, semantic, segmentation  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, localization, outdoor  
- **[Leveling3D: Leveling Up 3D Reconstruction with Feed-Forward 3D Gaussian Splatting and Geometry-Aware Generation](https://arxiv.org/abs/2603.16211v1)**  
  Authors: Yiming Huang, Baixiang Huang, Beilei Cui, Chi Kit Ng, Long Bai, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16211v1.pdf)  
  Keywords: ar, 3d reconstruction, lightweight, 3d gaussian, geometry, gaussian splatting  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: semantic, ar, avatar, head, geometry, tracking, fast  

### Large Scene

*Showing the latest 50 out of 61 papers*

- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, efficient, head, tracking, gaussian splatting, dynamic, outdoor, slam  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, localization, outdoor  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: ar, 3d reconstruction, 3d gaussian, urban scene, geometry, face, gaussian splatting  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: ar, 3d reconstruction, relightable, 3d gaussian, reflection, nerf, gaussian splatting, lighting, relighting, fast, outdoor, illumination  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: semantic, ar, lightweight, 3d gaussian, face, gaussian splatting, lighting, outdoor, fast  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: ar, 3d reconstruction, high-fidelity, efficient, 3d gaussian, nerf, gaussian splatting, outdoor, vr, neural rendering  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: semantic, ar, head, 3d gaussian, geometry, gaussian splatting, localization, mapping, lighting, outdoor  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: ar, real-time rendering, 3d gaussian, nerf, gaussian splatting, global illumination, lighting, autonomous driving, outdoor, illumination  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v2)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v2.pdf)  
  Keywords: ar, relightable, high-fidelity, lightweight, 3d gaussian, geometry, gaussian splatting, dynamic, lighting, outdoor, illumination  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: ar, efficient, head, large scene, 3d gaussian, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 424 papers*

- **[Fourier Splatting: Generalized Fourier encoded primitives for scalable radiance fields](https://arxiv.org/abs/2603.19834v1)**  
  Authors: Mihnea-Bogdan Jurca, Bert Van hauwermeiren, Adrian Munteanu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19834v1.pdf)  
  Keywords: ar, high-fidelity, efficient, real-time rendering, 3d gaussian, gaussian splatting  
- **[StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention](https://arxiv.org/abs/2603.19552v1)**  
  Authors: Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19552v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://streetforward.github.io.)  
  Keywords: motion, ar, high-fidelity, efficient, 3d gaussian, geometry, gaussian splatting, dynamic, autonomous driving  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[OnlinePG: Online Open-Vocabulary Panoptic Mapping with 3D Gaussian Splatting](https://arxiv.org/abs/2603.18510v1)**  
  Authors: Hongjia Zhai, Qi Zhang, Xiaokun Pan, Xiyu Zhang, Yitong Dong, Huaqi Zhang, Dan Xu, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18510v1.pdf)  
  Keywords: ar, understanding, efficient, 3d gaussian, gaussian splatting, mapping, semantic  
- **[Adaptive Anchor Policies for Efficient 4D Gaussian Streaming](https://arxiv.org/abs/2603.17227v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17227v1.pdf)  
  Keywords: ar, efficient, real-time rendering, 4d, gaussian splatting, dynamic, fast  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, efficient, head, tracking, gaussian splatting, dynamic, outdoor, slam  
- **[Leveling3D: Leveling Up 3D Reconstruction with Feed-Forward 3D Gaussian Splatting and Geometry-Aware Generation](https://arxiv.org/abs/2603.16211v1)**  
  Authors: Yiming Huang, Baixiang Huang, Beilei Cui, Chi Kit Ng, Long Bai, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16211v1.pdf)  
  Keywords: ar, 3d reconstruction, lightweight, 3d gaussian, geometry, gaussian splatting  
- **[NanoGS: Training-Free Gaussian Splat Simplification](https://arxiv.org/abs/2603.16103v1)**  
  Authors: Butian Xiong, Rong Liu, Tiantian Zhou, Meida Chen, Zhiwen Fan, Andrew Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://saliteta.github.io/NanoGS/.)  
  Keywords: ar, compact, high-fidelity, efficient, lightweight, 3d gaussian, compression  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, high-fidelity, efficient, ray marching, real-time rendering, 3d gaussian, gaussian splatting  
- **[LiDAR-EVS: Enhance Extrapolated View Synthesis for 3D Gaussian Splatting with Pseudo-LiDAR Supervision](https://arxiv.org/abs/2603.14763v1)**  
  Authors: Yiming Huang, Xin Kang, Sipeng Zhang, Hongliang Ren, Weihua Zhang, Junjie Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14763v1.pdf)  
  Keywords: ar, lightweight, 3d gaussian, gaussian splatting, autonomous driving, neural rendering  

### Quality Enhancement

*Showing the latest 50 out of 225 papers*

- **[Fourier Splatting: Generalized Fourier encoded primitives for scalable radiance fields](https://arxiv.org/abs/2603.19834v1)**  
  Authors: Mihnea-Bogdan Jurca, Bert Van hauwermeiren, Adrian Munteanu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19834v1.pdf)  
  Keywords: ar, high-fidelity, efficient, real-time rendering, 3d gaussian, gaussian splatting  
- **[StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention](https://arxiv.org/abs/2603.19552v1)**  
  Authors: Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19552v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://streetforward.github.io.)  
  Keywords: motion, ar, high-fidelity, efficient, 3d gaussian, geometry, gaussian splatting, dynamic, autonomous driving  
- **[GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137v1)**  
  Authors: Yiren Lu, Yi Du, Disheng Liu, Yunlai Zhou, Chen Wang, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19137v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, geometry, gaussian splatting, semantic  
- **[CrowdGaussian: Reconstructing High-Fidelity 3D Gaussians for Human Crowd from a Single Image](https://arxiv.org/abs/2603.17779v1)**  
  Authors: Yizheng Song, Yiyu Zhuang, Qipeng Xu, Haixiang Wang, Jiahe Zhu, Jing Tian, Siyu Zhu, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17779v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, human, geometry, gaussian splatting  
- **[SMAL-pets: SMAL Based Avatars of Pets from Single Image](https://arxiv.org/abs/2603.17131v1)**  
  Authors: Piotr Borycki, Joanna Waczyńska, Yizhe Zhu, Yongqiang Gao, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17131v1.pdf)  
  Keywords: ar, high-fidelity, avatar, 3d gaussian, human, face, gaussian splatting, animation  
- **[NanoGS: Training-Free Gaussian Splat Simplification](https://arxiv.org/abs/2603.16103v1)**  
  Authors: Butian Xiong, Rong Liu, Tiantian Zhou, Meida Chen, Zhiwen Fan, Andrew Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://saliteta.github.io/NanoGS/.)  
  Keywords: ar, compact, high-fidelity, efficient, lightweight, 3d gaussian, compression  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, high-fidelity, efficient, ray marching, real-time rendering, 3d gaussian, gaussian splatting  
- **[NavGSim: High-Fidelity Gaussian Splatting Simulator for Large-Scale Navigation](https://arxiv.org/abs/2603.15186v1)**  
  Authors: Jiahang Liu, Yuanxing Duan, Jiazhao Zhang, Minghan Li, Shaoan Wang, Zhizheng Zhang, He Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15186v1.pdf)  
  Keywords: ar, understanding, high-fidelity, 3d gaussian, gaussian splatting  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, reflection, face, gaussian splatting, lighting, relighting  
- **[AstroSplat: Physics-Based Gaussian Splatting for Rendering and Reconstruction of Small Celestial Bodies](https://arxiv.org/abs/2603.11969v1)**  
  Authors: Jennifer Nolan, Travis Driver, John Christian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.11969v1.pdf)  
  Keywords: ar, high-fidelity, face, gaussian splatting, body  

### Ray Tracing

- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: ray tracing, ar, 3d gaussian, survey, gaussian splatting, mapping  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, high-fidelity, efficient, ray marching, real-time rendering, 3d gaussian, gaussian splatting  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ar, efficient, 3d gaussian, geometry, gaussian splatting, robotics, fast, ray casting  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ray tracing, ar, efficient, lightweight, reflection, geometry, face, gaussian splatting, fast  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ray tracing, ar, efficient, reflection, gaussian splatting, global illumination, lighting, relighting, illumination  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: ar, real-time rendering, 3d gaussian, nerf, gaussian splatting, global illumination, lighting, autonomous driving, outdoor, illumination  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: ar, efficient, geometry, gaussian splatting, global illumination, lighting, relighting, shadow, illumination  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: ar, understanding, lightweight, head, path tracing, medical, gaussian splatting, vr  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: ray tracing, ar, efficient, head, 3d gaussian, acceleration, gaussian splatting  

### Relighting

*Showing the latest 50 out of 134 papers*

- **[HUGE-Bench: A Benchmark for High-Level UAV Vision-Language-Action Tasks](https://arxiv.org/abs/2603.19822v1)**  
  Authors: Jingyu Guo, Ziye Chen, Ziwen Li, Zhengqing Gao, Jiaxin Huang, Hanlue Zhang, Fengming Huang, Yu Yao, Tongliang Liu, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19822v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, lighting, semantic  
- **[Semantic Segmentation and Depth Estimation for Real-Time Lunar Surface Mapping Using 3D Gaussian Splatting](https://arxiv.org/abs/2603.18218v1)**  
  Authors: Guillem Casadesus Vila, Adam Dai, Grace Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18218v1.pdf)  
  Keywords: ar, understanding, 3d gaussian, face, gaussian splatting, mapping, lighting, semantic, segmentation, slam  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, 3d gaussian, nerf, gaussian splatting, tracking, dynamic, lighting, fast  
- **[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001v1)**  
  Authors: Jiale Wu, Xiaoyang Bai, Zongqi He, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14001v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, reflection, face, gaussian splatting, lighting, relighting  
- **[LR-SGS: Robust LiDAR-Reflectance-Guided Salient Gaussian Splatting for Self-Driving Scene Reconstruction](https://arxiv.org/abs/2603.12647v1)**  
  Authors: Ziyu Chen, Fan Zhu, Hui Zhu, Deyi Kong, Xinkai Kuang, Yujia Zhang, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.12647v1.pdf)  
  Keywords: motion, ar, efficient, 3d gaussian, gaussian splatting, lighting  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ray tracing, ar, efficient, lightweight, reflection, geometry, face, gaussian splatting, fast  
- **[3DGS-HPC: Distractor-free 3D Gaussian Splatting with Hybrid Patch-wise Classification](https://arxiv.org/abs/2603.07587v1)**  
  Authors: Jiahao Chen, Yipeng Qin, Ganlong Zhao, Xin Li, Wenping Wang, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07587v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, semantic, shadow  
- **[SSR-GS: Separating Specular Reflection in Gaussian Splatting for Glossy Surface Reconstruction](https://arxiv.org/abs/2603.05152v1)**  
  Authors: Ningjing Fan, Yiqun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.05152v1.pdf)  
  Keywords: ar, efficient, 3d gaussian, reflection, geometry, face, gaussian splatting, illumination  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: ar, 3d reconstruction, relightable, 3d gaussian, reflection, nerf, gaussian splatting, lighting, relighting, fast, outdoor, illumination  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ray tracing, ar, efficient, reflection, gaussian splatting, global illumination, lighting, relighting, illumination  

### SLAM

*Showing the latest 50 out of 149 papers*

- **[OnlinePG: Online Open-Vocabulary Panoptic Mapping with 3D Gaussian Splatting](https://arxiv.org/abs/2603.18510v1)**  
  Authors: Hongjia Zhai, Qi Zhang, Xiaokun Pan, Xiyu Zhang, Yitong Dong, Huaqi Zhang, Dan Xu, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18510v1.pdf)  
  Keywords: ar, understanding, efficient, 3d gaussian, gaussian splatting, mapping, semantic  
- **[Inst4DGS: Instance-Decomposed 4D Gaussian Splatting with Multi-Video Label Permutation Learning](https://arxiv.org/abs/2603.18402v1)**  
  Authors: Yonghan Lee, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18402v1.pdf)  
  Keywords: motion, ar, 4d, tracking, gaussian splatting, dynamic, segmentation  
- **[Semantic Segmentation and Depth Estimation for Real-Time Lunar Surface Mapping Using 3D Gaussian Splatting](https://arxiv.org/abs/2603.18218v1)**  
  Authors: Guillem Casadesus Vila, Adam Dai, Grace Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18218v1.pdf)  
  Keywords: ar, understanding, 3d gaussian, face, gaussian splatting, mapping, lighting, semantic, segmentation, slam  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v1)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v1.pdf)  
  Keywords: ray tracing, ar, 3d gaussian, survey, gaussian splatting, mapping  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, efficient, head, tracking, gaussian splatting, dynamic, outdoor, slam  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, localization, outdoor  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: semantic, ar, avatar, head, geometry, tracking, fast  
- **[E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction](https://arxiv.org/abs/2603.14684v1)**  
  Authors: Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.14684v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, 3d gaussian, nerf, gaussian splatting, tracking, dynamic, lighting, fast  
- **[VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM](https://arxiv.org/abs/2603.09673v1)**  
  Authors: Anh Thuan Tran, Jana Kosecka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09673v1.pdf)  
  Keywords: ar, high-fidelity, efficient, 3d gaussian, face, tracking, gaussian splatting, localization, mapping, fast, slam  
- **[X-GS: An Extensible Open Framework for Perceiving and Thinking via 3D Gaussian Splatting](https://arxiv.org/abs/2603.09632v2)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.09632v2.pdf)  
  Keywords: ar, 3d gaussian, face, gaussian splatting, semantic, slam  

### Scene Understanding

*Showing the latest 50 out of 236 papers*

- **[HUGE-Bench: A Benchmark for High-Level UAV Vision-Language-Action Tasks](https://arxiv.org/abs/2603.19822v1)**  
  Authors: Jingyu Guo, Ziye Chen, Ziwen Li, Zhengqing Gao, Jiaxin Huang, Hanlue Zhang, Fengming Huang, Yu Yao, Tongliang Liu, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19822v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, lighting, semantic  
- **[Reconstruction Matters: Learning Geometry-Aligned BEV Representation through 3D Gaussian Splatting](https://arxiv.org/abs/2603.19193v1)**  
  Authors: Yiren Lu, Xin Ye, Burhaneddin Yaman, Jingru Luo, Zhexiao Xiong, Liu Ren, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19193v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, understanding, 3d gaussian, geometry, gaussian splatting, autonomous driving, semantic, segmentation  
- **[GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137v1)**  
  Authors: Yiren Lu, Yi Du, Disheng Liu, Yunlai Zhou, Chen Wang, Yu Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.19137v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, geometry, gaussian splatting, semantic  
- **[GHOST: Fast Category-agnostic Hand-Object Interaction Reconstruction from RGB Videos using Gaussian Splatting](https://arxiv.org/abs/2603.18912v1)**  
  Authors: Ahmed Tawfik Aboukhadra, Marcel Rogge, Nadia Robertini, Abdalla Arafa, Jameel Malik, Ahmed Elhayek, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18912v1.pdf)  
  Keywords: ar, 3d reconstruction, efficient, understanding, gaussian splatting, dynamic, robotics, fast, vr  
- **[OnlinePG: Online Open-Vocabulary Panoptic Mapping with 3D Gaussian Splatting](https://arxiv.org/abs/2603.18510v1)**  
  Authors: Hongjia Zhai, Qi Zhang, Xiaokun Pan, Xiyu Zhang, Yitong Dong, Huaqi Zhang, Dan Xu, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18510v1.pdf)  
  Keywords: ar, understanding, efficient, 3d gaussian, gaussian splatting, mapping, semantic  
- **[Inst4DGS: Instance-Decomposed 4D Gaussian Splatting with Multi-Video Label Permutation Learning](https://arxiv.org/abs/2603.18402v1)**  
  Authors: Yonghan Lee, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18402v1.pdf)  
  Keywords: motion, ar, 4d, tracking, gaussian splatting, dynamic, segmentation  
- **[Semantic Segmentation and Depth Estimation for Real-Time Lunar Surface Mapping Using 3D Gaussian Splatting](https://arxiv.org/abs/2603.18218v1)**  
  Authors: Guillem Casadesus Vila, Adam Dai, Grace Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.18218v1.pdf)  
  Keywords: ar, understanding, 3d gaussian, face, gaussian splatting, mapping, lighting, semantic, segmentation, slam  
- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: ar, 3d reconstruction, 3d gaussian, geometry, gaussian splatting, sparse-view, semantic, segmentation  
- **[Feed-forward Gaussian Registration for Head Avatar Creation and Editing](https://arxiv.org/abs/2603.15811v1)**  
  Authors: Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15811v1.pdf)  
  Keywords: semantic, ar, avatar, head, geometry, tracking, fast  
- **[NavGSim: High-Fidelity Gaussian Splatting Simulator for Large-Scale Navigation](https://arxiv.org/abs/2603.15186v1)**  
  Authors: Jiahang Liu, Yuanxing Duan, Jiazhao Zhang, Minghan Li, Shaoan Wang, Zhizheng Zhang, He Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15186v1.pdf)  
  Keywords: ar, understanding, high-fidelity, 3d gaussian, gaussian splatting  



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