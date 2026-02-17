# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-02-17 01:15:03

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

- [3DGS Surveys](#3dgs-surveys) (23 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (234 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (341 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (399 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (359 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (68 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (414 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (218 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (20 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (123 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (147 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (222 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: survey, tracking, motion, dynamic, mapping, efficient, 3d gaussian, slam, face, gaussian splatting, ar, localization  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, 3d gaussian, gaussian splatting, ar, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: survey, efficient, 3d gaussian, gaussian splatting, ar, nerf, geometry  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: survey, 4d, compression, high-fidelity, 3d reconstruction, dynamic, efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: survey, semantic, mapping, 3d gaussian, slam, localization, understanding, gaussian splatting, ar, robotics, nerf  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: survey, high-fidelity, semantic, mapping, efficient, 3d gaussian, slam, gaussian splatting, ar, robotics, localization  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: survey, 4d, motion, 3d gaussian, fast, gaussian splatting, ar, nerf, geometry  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: survey, real-time rendering, avatar, 3d reconstruction, efficient, 3d gaussian, lighting, animation, efficient rendering, face, gaussian splatting, ar  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: survey, lightweight, ar, efficient, understanding, gaussian splatting, human, nerf  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: neural rendering, survey, efficient, 3d gaussian, slam, fast, understanding, gaussian splatting, ar, nerf  

### Acceleration

*Showing the latest 50 out of 234 papers*

- **[Faster-GS: Analyzing and Improving Gaussian Splatting Optimization](https://arxiv.org/abs/2602.09999v1)**  
  Authors: Florian Hahlbohm, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09999v1.pdf)  
  Keywords: 4d, efficient, 3d gaussian, fast, gaussian splatting, ar  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, 3d gaussian, animation, fast, human, segmentation  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, avatar, head, 3d gaussian, gaussian splatting, ar  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: dynamic, mapping, efficient, fast, gaussian splatting, ar, segmentation  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, body, ar, gaussian splatting, human  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: neural rendering, real-time rendering, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, real-time rendering, sparse-view, 3d gaussian, gaussian splatting, ar, nerf  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, high-fidelity, efficient, 3d gaussian, gaussian splatting, ar  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: 4d, motion, dynamic, high-fidelity, efficient, 3d gaussian, fast, face, gaussian splatting, ar  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: semantic, 3d gaussian, fast, gaussian splatting, ar, segmentation  

### Applications

*Showing the latest 50 out of 995 papers*

- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: dynamic, high-fidelity, 3d gaussian, face, gaussian splatting, ar, geometry  
- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: semantic, mapping, efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[3DGSNav: Enhancing Vision-Language Model Reasoning for Object Navigation via Active 3D Gaussian Splatting](https://arxiv.org/abs/2602.12159v1)**  
  Authors: Wancai Zheng, Hao Chen, Xianlong Lu, Linlin Ou, Xinyi Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12159v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aczheng-cai.github.io/3dgsnav.github.io/)  
  Keywords: semantic, recognition, efficient, 3d gaussian, gaussian splatting, ar  
- **[GSO-SLAM: Bidirectionally Coupled Gaussian Splatting and Direct Visual Odometry](https://arxiv.org/abs/2602.11714v1)**  
  Authors: Jiung Yeon, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11714v1.pdf)  
  Keywords: tracking, mapping, head, slam, gaussian splatting, ar  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: motion, dynamic, sparse-view, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[Variation-aware Flexible 3D Gaussian Editing](https://arxiv.org/abs/2602.11638v2)**  
  Authors: Hao Qin, Yukai Sun, Meng Wang, Ming Kong, Mengxu Lu, Qiang Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11638v2.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: efficient, deformation, 3d gaussian, gaussian splatting, ar, segmentation  
- **[ReaDy-Go: Real-to-Sim Dynamic 3D Gaussian Splatting Simulation for Environment-Specific Visual Navigation with Moving Obstacles](https://arxiv.org/abs/2602.11575v1)**  
  Authors: Seungyeon Yoo, Youngseok Jang, Dabin Kim, Youngsoo Han, Seungwoo Jung, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11575v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/ready-go-site/.)  
  Keywords: motion, avatar, dynamic, ar, 3d gaussian, animation, gaussian splatting, human  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, dynamic, 3d gaussian, gaussian splatting, ar, geometry  
- **[XSPLAIN: XAI-enabling Splat-based Prototype Learning for Attribute-aware INterpretability](https://arxiv.org/abs/2602.10239v1)**  
  Authors: Dominik Galus, Julia Farganus, Tymoteusz Zapala, Mikołaj Czachorowski, Piotr Borycki, Przemysław Spurek, Piotr Syga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10239v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, vr, 3d gaussian, gaussian splatting, ar  

### Avatar Generation

*Showing the latest 50 out of 341 papers*

- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: dynamic, high-fidelity, 3d gaussian, face, gaussian splatting, ar, geometry  
- **[GSO-SLAM: Bidirectionally Coupled Gaussian Splatting and Direct Visual Odometry](https://arxiv.org/abs/2602.11714v1)**  
  Authors: Jiung Yeon, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11714v1.pdf)  
  Keywords: tracking, mapping, head, slam, gaussian splatting, ar  
- **[ReaDy-Go: Real-to-Sim Dynamic 3D Gaussian Splatting Simulation for Environment-Specific Visual Navigation with Moving Obstacles](https://arxiv.org/abs/2602.11575v1)**  
  Authors: Seungyeon Yoo, Youngseok Jang, Dabin Kim, Youngsoo Han, Seungwoo Jung, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11575v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/ready-go-site/.)  
  Keywords: motion, avatar, dynamic, ar, 3d gaussian, animation, gaussian splatting, human  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, 3d gaussian, animation, fast, human, segmentation  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, avatar, head, 3d gaussian, gaussian splatting, ar  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: 4d, motion, high-fidelity, dynamic, semantic, vr, head, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: motion, avatar, high-fidelity, 3d reconstruction, dynamic, head, 3d gaussian, animation, face, gaussian splatting, ar, geometry  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, body, ar, gaussian splatting, human  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, tracking, motion, dynamic, mapping, efficient, 3d gaussian, slam, face, gaussian splatting, ar, localization  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: dynamic, ar, body, 3d gaussian  

### Dynamic Scene

*Showing the latest 50 out of 399 papers*

- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: dynamic, high-fidelity, 3d gaussian, face, gaussian splatting, ar, geometry  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: motion, dynamic, sparse-view, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: efficient, deformation, 3d gaussian, gaussian splatting, ar, segmentation  
- **[ReaDy-Go: Real-to-Sim Dynamic 3D Gaussian Splatting Simulation for Environment-Specific Visual Navigation with Moving Obstacles](https://arxiv.org/abs/2602.11575v1)**  
  Authors: Seungyeon Yoo, Youngseok Jang, Dabin Kim, Youngsoo Han, Seungwoo Jung, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11575v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/ready-go-site/.)  
  Keywords: motion, avatar, dynamic, ar, 3d gaussian, animation, gaussian splatting, human  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, dynamic, 3d gaussian, gaussian splatting, ar, geometry  
- **[Faster-GS: Analyzing and Improving Gaussian Splatting Optimization](https://arxiv.org/abs/2602.09999v1)**  
  Authors: Florian Hahlbohm, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09999v1.pdf)  
  Keywords: 4d, efficient, 3d gaussian, fast, gaussian splatting, ar  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, 3d gaussian, animation, fast, human, segmentation  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, avatar, head, 3d gaussian, gaussian splatting, ar  
- **[Grow with the Flow: 4D Reconstruction of Growing Plants with Gaussian Flow Fields](https://arxiv.org/abs/2602.08958v2)**  
  Authors: Weihan Luo, Lily Goli, Sherwin Bahmani, Felix Taubner, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08958v2.pdf)  
  Keywords: 4d, motion, dynamic, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: dynamic, mapping, efficient, fast, gaussian splatting, ar, segmentation  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: motion, dynamic, sparse-view, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, real-time rendering, sparse-view, 3d gaussian, gaussian splatting, ar, nerf  
- **[LoD-Structured 3D Gaussian Splatting for Streaming Video Reconstruction](https://arxiv.org/abs/2601.18475v1)**  
  Authors: Xinhui Liu, Can Wang, Lei Liu, Zhenghao Chen, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18475v1.pdf)  
  Keywords: motion, dynamic, high-fidelity, sparse-view, efficient, 3d gaussian, gaussian splatting, ar  
- **[LGDWT-GS: Local and Global Discrete Wavelet-Regularized 3D Gaussian Splatting for Sparse-View Scene Reconstruction](https://arxiv.org/abs/2601.17185v1)**  
  Authors: Shima Salehi, Atharva Agashe, Andrew J. McFarland, Joshua Peeples  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17185v1.pdf)  
  Keywords: 3d reconstruction, few-shot, sparse-view, 3d gaussian, gaussian splatting, ar, geometry  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: sparse-view, efficient, 3d gaussian, gaussian splatting, ar  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: neural rendering, 3d reconstruction, efficient, 3d gaussian, sparse view, efficient rendering, face, gaussian splatting, ar, robotics  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, shadow, 3d reconstruction, sparse-view, efficient, 3d gaussian, ray marching, efficient rendering, gaussian splatting, ar  
- **[COSMOS: Coherent Supergaussian Modeling with Spatial Priors for Sparse-View 3D Splatting](https://arxiv.org/abs/2602.06044v1)**  
  Authors: Chaeyoung Jeong, Kwangsu Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06044v1.pdf)  
  Keywords: 3d reconstruction, sparse-view, 3d gaussian, gaussian splatting, ar, segmentation  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: motion, high-fidelity, 3d reconstruction, 3d gaussian, sparse view, gaussian splatting, ar  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, light transport, sparse-view, lighting, gaussian splatting, ar, segmentation, geometry  

### Geometry Reconstruction

*Showing the latest 50 out of 359 papers*

- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: dynamic, high-fidelity, 3d gaussian, face, gaussian splatting, ar, geometry  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: motion, dynamic, sparse-view, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, dynamic, 3d gaussian, gaussian splatting, ar, geometry  
- **[XSPLAIN: XAI-enabling Splat-based Prototype Learning for Attribute-aware INterpretability](https://arxiv.org/abs/2602.10239v1)**  
  Authors: Dominik Galus, Julia Farganus, Tymoteusz Zapala, Mikołaj Czachorowski, Piotr Borycki, Przemysław Spurek, Piotr Syga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10239v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, vr, 3d gaussian, gaussian splatting, ar  
- **[Stability and Concentration in Nonlinear Inverse Problems with Block-Structured Parameters: Lipschitz Geometry, Identifiability, and an Application to Gaussian Splatting](https://arxiv.org/abs/2602.09415v1)**  
  Authors: Joe-Mei Feng, Hsin-Hsiung Kao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09415v1.pdf)  
  Keywords: gaussian splatting, ar, geometry  
- **[Grow with the Flow: 4D Reconstruction of Growing Plants with Gaussian Flow Fields](https://arxiv.org/abs/2602.08958v2)**  
  Authors: Weihan Luo, Lily Goli, Sherwin Bahmani, Felix Taubner, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08958v2.pdf)  
  Keywords: 4d, motion, dynamic, 3d gaussian, deformation, gaussian splatting, ar, geometry  
- **[Analysis of Converged 3D Gaussian Splatting Solutions: Density Effects and Prediction Limit](https://arxiv.org/abs/2602.08909v1)**  
  Authors: Zhendong Wang, Cihan Ruan, Jingchuan Xiao, Chuqing Shi, Wei Jiang, Wei Wang, Wenjie Liu, Nam Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08909v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: relighting, illumination, shadow, efficient, lighting, global illumination, gaussian splatting, ar, geometry  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: 4d, motion, high-fidelity, dynamic, semantic, vr, head, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, high-fidelity, relightable, dynamic, lightweight, 3d gaussian, lighting, outdoor, gaussian splatting, ar, geometry  

### Large Scene

*Showing the latest 50 out of 68 papers*

- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, high-fidelity, relightable, dynamic, lightweight, 3d gaussian, lighting, outdoor, gaussian splatting, ar, geometry  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: head, large scene, efficient, 3d gaussian, gaussian splatting, ar  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: autonomous driving, 4d, motion, dynamic, semantic, efficient, 3d gaussian, urban scene, gaussian splatting, ar, geometry  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: compression, semantic, vr, 3d gaussian, outdoor, gaussian splatting, ar, segmentation  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: illumination, 3d reconstruction, efficient, 3d gaussian, urban scene, face, gaussian splatting, ar, geometry  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: 3d gaussian, outdoor, compact, fast, gaussian splatting, ar, geometry  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: 4d, motion, dynamic, efficient, 3d gaussian, outdoor, gaussian splatting, ar, robotics, nerf  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: 3d reconstruction, 3d gaussian, outdoor, understanding, gaussian splatting, ar, geometry  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: semantic, outdoor, fast, gaussian splatting, ar, geometry  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: relighting, illumination, high-fidelity, semantic, efficient, lighting, outdoor, face, gaussian splatting, ar, segmentation, geometry  

### Model Compression

*Showing the latest 50 out of 414 papers*

- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: semantic, mapping, efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[3DGSNav: Enhancing Vision-Language Model Reasoning for Object Navigation via Active 3D Gaussian Splatting](https://arxiv.org/abs/2602.12159v1)**  
  Authors: Wancai Zheng, Hao Chen, Xianlong Lu, Linlin Ou, Xinyi Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12159v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aczheng-cai.github.io/3dgsnav.github.io/)  
  Keywords: semantic, recognition, efficient, 3d gaussian, gaussian splatting, ar  
- **[Variation-aware Flexible 3D Gaussian Editing](https://arxiv.org/abs/2602.11638v2)**  
  Authors: Hao Qin, Yukai Sun, Meng Wang, Ming Kong, Mengxu Lu, Qiang Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11638v2.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: efficient, deformation, 3d gaussian, gaussian splatting, ar, segmentation  
- **[Faster-GS: Analyzing and Improving Gaussian Splatting Optimization](https://arxiv.org/abs/2602.09999v1)**  
  Authors: Florian Hahlbohm, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09999v1.pdf)  
  Keywords: 4d, efficient, 3d gaussian, fast, gaussian splatting, ar  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: dynamic, mapping, efficient, fast, gaussian splatting, ar, segmentation  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: relighting, illumination, shadow, efficient, lighting, global illumination, gaussian splatting, ar, geometry  
- **[GaussianPOP: Principled Simplification Framework for Compact 3D Gaussian Splatting via Error Quantification](https://arxiv.org/abs/2602.06830v1)**  
  Authors: Soonbin Lee, Yeong-Gyu Kim, Simon Sasse, Tomas M. Borges, Yago Sanchez, Eun-Seok Ryu, Thomas Schierl, Cornelius Hellge  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06830v1.pdf)  
  Keywords: efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, high-fidelity, relightable, dynamic, lightweight, 3d gaussian, lighting, outdoor, gaussian splatting, ar, geometry  
- **[Nix and Fix: Targeting 1000x Compression of 3D Gaussian Splatting with Diffusion Models](https://arxiv.org/abs/2602.04549v1)**  
  Authors: Cem Eteke, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04549v1.pdf)  
  Keywords: gaussian splatting, ar, compression, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 218 papers*

- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: dynamic, high-fidelity, 3d gaussian, face, gaussian splatting, ar, geometry  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, dynamic, 3d gaussian, gaussian splatting, ar, geometry  
- **[XSPLAIN: XAI-enabling Splat-based Prototype Learning for Attribute-aware INterpretability](https://arxiv.org/abs/2602.10239v1)**  
  Authors: Dominik Galus, Julia Farganus, Tymoteusz Zapala, Mikołaj Czachorowski, Piotr Borycki, Przemysław Spurek, Piotr Syga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10239v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, vr, 3d gaussian, gaussian splatting, ar  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, avatar, head, 3d gaussian, gaussian splatting, ar  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: 4d, motion, high-fidelity, dynamic, semantic, vr, head, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, high-fidelity, relightable, dynamic, lightweight, 3d gaussian, lighting, outdoor, gaussian splatting, ar, geometry  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: motion, avatar, high-fidelity, 3d reconstruction, dynamic, head, 3d gaussian, animation, face, gaussian splatting, ar, geometry  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: motion, real-time rendering, dynamic, high-fidelity, body, ar, gaussian splatting, human  
- **[VecSet-Edit: Unleashing Pre-trained LRM for Mesh Editing from Single Image](https://arxiv.org/abs/2602.04349v1)**  
  Authors: Teng-Fang Hsiao, Bo-Kai Ruan, Yu-Lun Liu, Hong-Han Shuai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04349v1.pdf)  
  Keywords: gaussian splatting, ar, high-fidelity, 3d gaussian  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: motion, 4d, dynamic, high-fidelity, compression, gaussian splatting, ar  

### Ray Tracing

- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: relighting, illumination, shadow, efficient, lighting, global illumination, gaussian splatting, ar, geometry  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: gaussian splatting, ar, ray tracing, 3d gaussian  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: path tracing, lightweight, vr, head, medical, understanding, gaussian splatting, ar  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: acceleration, efficient, 3d gaussian, head, ray tracing, gaussian splatting, ar  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, shadow, 3d reconstruction, sparse-view, efficient, 3d gaussian, ray marching, efficient rendering, gaussian splatting, ar  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: motion, 3d reconstruction, 3d gaussian, fast, understanding, ray tracing, gaussian splatting, ar, geometry  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: relighting, 3d reconstruction, relightable, lighting, ray tracing, gaussian splatting, ar, geometry  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: 3d gaussian, fast, face, ray tracing, gaussian splatting, ar, nerf  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: real-time rendering, high-fidelity, 3d gaussian, compact, fast, ray tracing, gaussian splatting, ar  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, dynamic, reflection, ray tracing, gaussian splatting, ar, geometry  

### Relighting

*Showing the latest 50 out of 123 papers*

- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: relighting, illumination, shadow, efficient, lighting, global illumination, gaussian splatting, ar, geometry  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: 4d, motion, high-fidelity, dynamic, semantic, vr, head, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, high-fidelity, relightable, dynamic, lightweight, 3d gaussian, lighting, outdoor, gaussian splatting, ar, geometry  
- **[NVS-HO: A Benchmark for Novel View Synthesis of Handheld Objects](https://arxiv.org/abs/2602.05822v1)**  
  Authors: Musawar Ali, Manuel Carranza-García, Nicola Fioraio, Samuele Salti, Luigi Di Stefano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05822v1.pdf)  
  Keywords: gaussian splatting, lighting, ar, nerf  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: neural rendering, real-time rendering, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, lighting, gaussian splatting, ar  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: shadow, illumination, 3d reconstruction, ar, nerf, geometry  
- **[Mirage2Matter: A Physically Grounded Gaussian World Model from Video](https://arxiv.org/abs/2602.00096v1)**  
  Authors: Zhengqing Gao, Ziwen Li, Xin Wang, Jiaxin Huang, Zhenyang Ren, Mingkai Shao, Hanlue Zhang, Tianyu Huang, Yongkang Cheng, Yandong Guo, Runqi Lin, Yuanyuan Wang, Tongliang Liu, Kun Zhang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00096v1.pdf)  
  Keywords: high-fidelity, efficient, 3d gaussian, lighting, gaussian splatting, ar, geometry  
- **[ThermoSplat: Cross-Modal 3D Gaussian Splatting with Feature Modulation and Geometry Decoupling](https://arxiv.org/abs/2601.15897v2)**  
  Authors: Zhaoqi Su, Shihai Chen, Xinyan Lin, Liqin Huang, Zhipeng Su, Xiaoqiang Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15897v2.pdf)  
  Keywords: dynamic, semantic, 3d gaussian, lighting, gaussian splatting, ar, geometry  
- **[LL-GaussianMap: Zero-shot Low-Light Image Enhancement via 2D Gaussian Splatting Guided Gain Maps](https://arxiv.org/abs/2601.15766v2)**  
  Authors: Yuhan Chen, Ying Fang, Guofa Li, Wenxuan Yu, Yicui Shi, Jingrui Zhang, Kefei Qian, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15766v2.pdf)  
  Keywords: high-fidelity, efficient, lighting, gaussian splatting, ar  

### SLAM

*Showing the latest 50 out of 147 papers*

- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: semantic, mapping, efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[GSO-SLAM: Bidirectionally Coupled Gaussian Splatting and Direct Visual Odometry](https://arxiv.org/abs/2602.11714v1)**  
  Authors: Jiung Yeon, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11714v1.pdf)  
  Keywords: tracking, mapping, head, slam, gaussian splatting, ar  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: dynamic, mapping, efficient, fast, gaussian splatting, ar, segmentation  
- **[Thermal odometry and dense mapping using learned odometry and Gaussian splatting](https://arxiv.org/abs/2602.07493v2)**  
  Authors: Tianhao Zhou, Yujia Chen, Zhihao Zhan, Yuhang Ming, Jianzhu Huai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07493v2.pdf)  
  Keywords: motion, mapping, slam, gaussian splatting, ar, robotics  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, tracking, motion, dynamic, mapping, efficient, 3d gaussian, slam, face, gaussian splatting, ar, localization  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: dynamic, mapping, deformation, gaussian splatting, ar, geometry  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: tracking, avatar, body, vr, head, 3d gaussian, gaussian splatting, ar  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v2)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v2.pdf)  
  Keywords: compression, real-time rendering, mapping, efficient, gaussian splatting, ar, nerf  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: neural rendering, illumination, high-fidelity, 3d reconstruction, dynamic, lightweight, semantic, mapping, 3d gaussian, lighting, face, gaussian splatting, ar, geometry  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, 3d reconstruction, semantic, mapping, efficient, 3d gaussian, lighting, gaussian splatting, ar, segmentation, robotics  

### Scene Understanding

*Showing the latest 50 out of 222 papers*

- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: semantic, mapping, efficient, 3d gaussian, compact, gaussian splatting, ar  
- **[3DGSNav: Enhancing Vision-Language Model Reasoning for Object Navigation via Active 3D Gaussian Splatting](https://arxiv.org/abs/2602.12159v1)**  
  Authors: Wancai Zheng, Hao Chen, Xianlong Lu, Linlin Ou, Xinyi Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12159v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aczheng-cai.github.io/3dgsnav.github.io/)  
  Keywords: semantic, recognition, efficient, 3d gaussian, gaussian splatting, ar  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: efficient, deformation, 3d gaussian, gaussian splatting, ar, segmentation  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, 3d gaussian, animation, fast, human, segmentation  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: dynamic, mapping, efficient, fast, gaussian splatting, ar, segmentation  
- **[Informative Object-centric Next Best View for Object-aware 3D Gaussian Splatting in Cluttered Scenes](https://arxiv.org/abs/2602.08266v1)**  
  Authors: Seunghoon Jeong, Eunho Lee, Jeongyun Kim, Ayoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08266v1.pdf)  
  Keywords: gaussian splatting, ar, semantic, 3d gaussian  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: 4d, motion, high-fidelity, dynamic, semantic, vr, head, 3d gaussian, reflection, gaussian splatting, ar, geometry  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: semantic, high-fidelity, efficient, gaussian splatting, ar, geometry  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: semantic, 3d gaussian, fast, gaussian splatting, ar, segmentation  
- **[PSGS: Text-driven Panorama Sliding Scene Generation via Gaussian Splatting](https://arxiv.org/abs/2602.00463v1)**  
  Authors: Xin Zhang, Shen Chen, Jiale Zhou, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00463v1.pdf)  
  Keywords: semantic, high-fidelity, vr, 3d gaussian, gaussian splatting, ar  



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