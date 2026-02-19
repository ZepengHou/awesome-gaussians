# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-02-19 01:16:17

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

- [3DGS Surveys](#3dgs-surveys) (22 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (231 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (341 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (399 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (359 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (69 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (219 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (21 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (125 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (150 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (224 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: mapping, ar, dynamic, localization, tracking, survey, slam, gaussian splatting, face, efficient, 3d gaussian, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, survey, robotics, gaussian splatting, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: ar, nerf, survey, geometry, gaussian splatting, efficient, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, compression, 3d reconstruction, survey, 4d, gaussian splatting, compact, efficient, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: ar, nerf, localization, survey, semantic, slam, robotics, gaussian splatting, 3d gaussian, mapping, understanding  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: ar, high-fidelity, localization, survey, semantic, slam, robotics, gaussian splatting, efficient, 3d gaussian, mapping  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: ar, nerf, survey, 4d, geometry, fast, gaussian splatting, 3d gaussian, motion  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, ar, animation, 3d reconstruction, survey, efficient rendering, gaussian splatting, face, efficient, lighting, 3d gaussian, real-time rendering  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: ar, nerf, lightweight, survey, human, gaussian splatting, efficient, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: neural rendering, ar, nerf, survey, slam, gaussian splatting, fast, efficient, 3d gaussian, understanding  

### Acceleration

*Showing the latest 50 out of 231 papers*

- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: ar, nerf, semantic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, ar, dynamic, tracking, 4d, fast, gaussian splatting, efficient, 3d gaussian, motion  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, ar, high-fidelity, lightweight, fast, gaussian splatting, efficient, 3d gaussian  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, autonomous driving, ar, nerf, outdoor, gaussian splatting, lighting, 3d gaussian, real-time rendering, global illumination  
- **[Faster-GS: Analyzing and Improving Gaussian Splatting Optimization](https://arxiv.org/abs/2602.09999v1)**  
  Authors: Florian Hahlbohm, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09999v1.pdf)  
  Keywords: ar, 4d, fast, gaussian splatting, efficient, 3d gaussian  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, animation, segmentation, human, fast, 3d gaussian  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: avatar, ar, high-fidelity, dynamic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: ar, segmentation, fast, gaussian splatting, efficient, dynamic, mapping  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: ar, high-fidelity, body, human, gaussian splatting, dynamic, motion, real-time rendering  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: neural rendering, ar, geometry, reflection, gaussian splatting, 3d gaussian, real-time rendering  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: ar, nerf, semantic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[DAV-GSWT: Diffusion-Active-View Sampling for Data-Efficient Gaussian Splatting Wang Tiles](https://arxiv.org/abs/2602.15355v1)**  
  Authors: Rong Fu, Jiekai Wu, Haiyun Wei, Yee Tan Jia, Wenxin Zhang, Yang Li, Xiaowen Ma, Wangyu Wu, Simon Fong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15355v1.pdf)  
  Keywords: neural rendering, ar, high-fidelity, gaussian splatting, efficient, 3d gaussian  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, ar, dynamic, tracking, 4d, fast, gaussian splatting, efficient, 3d gaussian, motion  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, ar, high-fidelity, lightweight, fast, gaussian splatting, efficient, 3d gaussian  
- **[Learnable Multi-level Discrete Wavelet Transforms for 3D Gaussian Splatting Frequency Modulation](https://arxiv.org/abs/2602.14199v1)**  
  Authors: Hung Nguyen, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14199v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[Joint Orientation and Weight Optimization for Robust Watertight Surface Reconstruction via Dirichlet-Regularized Winding Fields](https://arxiv.org/abs/2602.13801v1)**  
  Authors: Jiaze Li, Daisheng Jin, Fei Hou, Junhui Hou, Zheng Liu, Shiqing Xin, Wenping Wang, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13801v1.pdf)  
  Keywords: ar, gaussian splatting, face, efficient, 3d gaussian  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, autonomous driving, ar, nerf, outdoor, gaussian splatting, lighting, 3d gaussian, real-time rendering, global illumination  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  

### Avatar Generation

*Showing the latest 50 out of 341 papers*

- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: ar, nerf, semantic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, ar, high-fidelity, lightweight, fast, gaussian splatting, efficient, 3d gaussian  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[Joint Orientation and Weight Optimization for Robust Watertight Surface Reconstruction via Dirichlet-Regularized Winding Fields](https://arxiv.org/abs/2602.13801v1)**  
  Authors: Jiaze Li, Daisheng Jin, Fei Hou, Junhui Hou, Zheng Liu, Shiqing Xin, Wenping Wang, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13801v1.pdf)  
  Keywords: ar, gaussian splatting, face, efficient, 3d gaussian  
- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, geometry, gaussian splatting, face, 3d gaussian  
- **[GSO-SLAM: Bidirectionally Coupled Gaussian Splatting and Direct Visual Odometry](https://arxiv.org/abs/2602.11714v1)**  
  Authors: Jiung Yeon, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11714v1.pdf)  
  Keywords: ar, tracking, slam, gaussian splatting, head, mapping  
- **[ReaDy-Go: Real-to-Sim Dynamic 3D Gaussian Splatting Simulation for Environment-Specific Visual Navigation with Moving Obstacles](https://arxiv.org/abs/2602.11575v2)**  
  Authors: Seungyeon Yoo, Youngseok Jang, Dabin Kim, Youngsoo Han, Seungwoo Jung, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11575v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/ready-go-site/.)  
  Keywords: avatar, ar, dynamic, 3d gaussian, human, gaussian splatting, animation, motion  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, animation, segmentation, human, fast, 3d gaussian  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: avatar, ar, high-fidelity, dynamic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  

### Dynamic Scene

*Showing the latest 50 out of 399 papers*

- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: ar, nerf, semantic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, ar, dynamic, tracking, 4d, fast, gaussian splatting, efficient, 3d gaussian, motion  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  
- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, geometry, gaussian splatting, face, 3d gaussian  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: ar, dynamic, geometry, gaussian splatting, sparse-view, deformation, 3d gaussian, motion  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, efficient, deformation, 3d gaussian  
- **[ReaDy-Go: Real-to-Sim Dynamic 3D Gaussian Splatting Simulation for Environment-Specific Visual Navigation with Moving Obstacles](https://arxiv.org/abs/2602.11575v2)**  
  Authors: Seungyeon Yoo, Youngseok Jang, Dabin Kim, Youngsoo Han, Seungwoo Jung, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11575v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/ready-go-site/.)  
  Keywords: avatar, ar, dynamic, 3d gaussian, human, gaussian splatting, animation, motion  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 3d reconstruction, geometry, gaussian splatting, 3d gaussian  
- **[Faster-GS: Analyzing and Improving Gaussian Splatting Optimization](https://arxiv.org/abs/2602.09999v1)**  
  Authors: Florian Hahlbohm, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09999v1.pdf)  
  Keywords: ar, 4d, fast, gaussian splatting, efficient, 3d gaussian  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: ar, dynamic, geometry, gaussian splatting, sparse-view, deformation, 3d gaussian, motion  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: ar, nerf, gaussian splatting, sparse-view, 3d gaussian, motion, real-time rendering  
- **[LoD-Structured 3D Gaussian Splatting for Streaming Video Reconstruction](https://arxiv.org/abs/2601.18475v1)**  
  Authors: Xinhui Liu, Can Wang, Lei Liu, Zhenghao Chen, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18475v1.pdf)  
  Keywords: efficient, ar, high-fidelity, dynamic, gaussian splatting, sparse-view, 3d gaussian, motion  
- **[LGDWT-GS: Local and Global Discrete Wavelet-Regularized 3D Gaussian Splatting for Sparse-View Scene Reconstruction](https://arxiv.org/abs/2601.17185v1)**  
  Authors: Shima Salehi, Atharva Agashe, Andrew J. McFarland, Joshua Peeples  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17185v1.pdf)  
  Keywords: few-shot, ar, 3d reconstruction, geometry, gaussian splatting, sparse-view, 3d gaussian  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: efficient, ar, gaussian splatting, sparse-view, 3d gaussian  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: neural rendering, ar, 3d reconstruction, sparse view, efficient rendering, robotics, gaussian splatting, face, efficient, 3d gaussian  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: ray marching, illumination, efficient, ar, 3d reconstruction, efficient rendering, gaussian splatting, shadow, sparse-view, 3d gaussian  
- **[COSMOS: Coherent Supergaussian Modeling with Spatial Priors for Sparse-View 3D Splatting](https://arxiv.org/abs/2602.06044v1)**  
  Authors: Chaeyoung Jeong, Kwangsu Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06044v1.pdf)  
  Keywords: ar, segmentation, 3d reconstruction, gaussian splatting, sparse-view, 3d gaussian  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: ar, high-fidelity, 3d reconstruction, sparse view, gaussian splatting, 3d gaussian, motion  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: ar, segmentation, relighting, geometry, gaussian splatting, light transport, sparse-view, lighting  

### Geometry Reconstruction

*Showing the latest 50 out of 359 papers*

- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[Learnable Multi-level Discrete Wavelet Transforms for 3D Gaussian Splatting Frequency Modulation](https://arxiv.org/abs/2602.14199v1)**  
  Authors: Hung Nguyen, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14199v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  
- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, geometry, gaussian splatting, face, 3d gaussian  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: ar, dynamic, geometry, gaussian splatting, sparse-view, deformation, 3d gaussian, motion  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 3d reconstruction, geometry, gaussian splatting, 3d gaussian  
- **[XSPLAIN: XAI-enabling Splat-based Prototype Learning for Attribute-aware INterpretability](https://arxiv.org/abs/2602.10239v1)**  
  Authors: Dominik Galus, Julia Farganus, Tymoteusz Zapala, Mikołaj Czachorowski, Piotr Borycki, Przemysław Spurek, Piotr Syga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10239v1.pdf)  
  Keywords: ar, high-fidelity, 3d reconstruction, gaussian splatting, 3d gaussian, vr  
- **[Stability and Concentration in Nonlinear Inverse Problems with Block-Structured Parameters: Lipschitz Geometry, Identifiability, and an Application to Gaussian Splatting](https://arxiv.org/abs/2602.09415v1)**  
  Authors: Joe-Mei Feng, Hsin-Hsiung Kao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09415v1.pdf)  
  Keywords: geometry, gaussian splatting, ar  
- **[Grow with the Flow: 4D Reconstruction of Growing Plants with Gaussian Flow Fields](https://arxiv.org/abs/2602.08958v2)**  
  Authors: Weihan Luo, Lily Goli, Sherwin Bahmani, Felix Taubner, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08958v2.pdf)  
  Keywords: ar, dynamic, 4d, geometry, gaussian splatting, deformation, 3d gaussian, motion  

### Large Scene

*Showing the latest 50 out of 69 papers*

- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, autonomous driving, ar, nerf, outdoor, gaussian splatting, lighting, 3d gaussian, real-time rendering, global illumination  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, ar, high-fidelity, relightable, dynamic, lightweight, geometry, outdoor, gaussian splatting, lighting, 3d gaussian  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, 3d gaussian, large scene  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: autonomous driving, urban scene, ar, dynamic, 4d, geometry, semantic, gaussian splatting, efficient, 3d gaussian, motion  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: ar, segmentation, compression, semantic, outdoor, gaussian splatting, 3d gaussian, vr  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: illumination, urban scene, ar, 3d reconstruction, geometry, gaussian splatting, face, efficient, 3d gaussian  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: ar, geometry, outdoor, fast, gaussian splatting, compact, 3d gaussian  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: ar, nerf, 3d gaussian, 4d, robotics, outdoor, gaussian splatting, efficient, dynamic, motion  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: ar, 3d reconstruction, geometry, outdoor, gaussian splatting, 3d gaussian, understanding  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[DAV-GSWT: Diffusion-Active-View Sampling for Data-Efficient Gaussian Splatting Wang Tiles](https://arxiv.org/abs/2602.15355v1)**  
  Authors: Rong Fu, Jiekai Wu, Haiyun Wei, Yee Tan Jia, Wenxin Zhang, Yang Li, Xiaowen Ma, Wangyu Wu, Simon Fong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15355v1.pdf)  
  Keywords: neural rendering, ar, high-fidelity, gaussian splatting, efficient, 3d gaussian  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, ar, dynamic, tracking, 4d, fast, gaussian splatting, efficient, 3d gaussian, motion  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, ar, high-fidelity, lightweight, fast, gaussian splatting, efficient, 3d gaussian  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[Joint Orientation and Weight Optimization for Robust Watertight Surface Reconstruction via Dirichlet-Regularized Winding Fields](https://arxiv.org/abs/2602.13801v1)**  
  Authors: Jiaze Li, Daisheng Jin, Fei Hou, Junhui Hou, Zheng Liu, Shiqing Xin, Wenping Wang, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13801v1.pdf)  
  Keywords: ar, gaussian splatting, face, efficient, 3d gaussian  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  
- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: ar, semantic, compact, gaussian splatting, efficient, 3d gaussian, mapping  
- **[3DGSNav: Enhancing Vision-Language Model Reasoning for Object Navigation via Active 3D Gaussian Splatting](https://arxiv.org/abs/2602.12159v1)**  
  Authors: Wancai Zheng, Hao Chen, Xianlong Lu, Linlin Ou, Xinyi Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12159v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aczheng-cai.github.io/3dgsnav.github.io/)  
  Keywords: ar, recognition, semantic, gaussian splatting, efficient, 3d gaussian  
- **[Variation-aware Flexible 3D Gaussian Editing](https://arxiv.org/abs/2602.11638v2)**  
  Authors: Hao Qin, Yukai Sun, Meng Wang, Ming Kong, Mengxu Lu, Qiang Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11638v2.pdf)  
  Keywords: efficient, ar, 3d gaussian, gaussian splatting  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, efficient, deformation, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 219 papers*

- **[DAV-GSWT: Diffusion-Active-View Sampling for Data-Efficient Gaussian Splatting Wang Tiles](https://arxiv.org/abs/2602.15355v1)**  
  Authors: Rong Fu, Jiekai Wu, Haiyun Wei, Yee Tan Jia, Wenxin Zhang, Yang Li, Xiaowen Ma, Wangyu Wu, Simon Fong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15355v1.pdf)  
  Keywords: neural rendering, ar, high-fidelity, gaussian splatting, efficient, 3d gaussian  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, ar, high-fidelity, lightweight, fast, gaussian splatting, efficient, 3d gaussian  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  
- **[GSM-GS: Geometry-Constrained Single and Multi-view Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2602.12796v1)**  
  Authors: Xiao Ren, Yu Liu, Ning An, Jian Cheng, Xin Qiao, He Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12796v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, geometry, gaussian splatting, face, 3d gaussian  
- **[ERGO: Excess-Risk-Guided Optimization for High-Fidelity Monocular 3D Gaussian Splatting](https://arxiv.org/abs/2602.10278v1)**  
  Authors: Zehua Ma, Hanhui Li, Zhenyu Xie, Xiaonan Luo, Michael Kampffmeyer, Feng Gao, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10278v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 3d reconstruction, geometry, gaussian splatting, 3d gaussian  
- **[XSPLAIN: XAI-enabling Splat-based Prototype Learning for Attribute-aware INterpretability](https://arxiv.org/abs/2602.10239v1)**  
  Authors: Dominik Galus, Julia Farganus, Tymoteusz Zapala, Mikołaj Czachorowski, Piotr Borycki, Przemysław Spurek, Piotr Syga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10239v1.pdf)  
  Keywords: ar, high-fidelity, 3d reconstruction, gaussian splatting, 3d gaussian, vr  
- **[Toward Fine-Grained Facial Control in 3D Talking Head Generation](https://arxiv.org/abs/2602.09736v1)**  
  Authors: Shaoyang Xie, Xiaofeng Cong, Baosheng Yu, Zhipeng Gui, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.09736v1.pdf)  
  Keywords: avatar, ar, high-fidelity, dynamic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 4d, geometry, reflection, semantic, gaussian splatting, head, 3d gaussian, motion, vr  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, ar, high-fidelity, relightable, dynamic, lightweight, geometry, outdoor, gaussian splatting, lighting, 3d gaussian  

### Ray Tracing

- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, autonomous driving, ar, nerf, outdoor, gaussian splatting, lighting, 3d gaussian, real-time rendering, global illumination  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: illumination, ar, relighting, geometry, gaussian splatting, shadow, efficient, lighting, global illumination  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, ray tracing  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: vr, ar, medical, lightweight, gaussian splatting, path tracing, head, understanding  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: ar, ray tracing, acceleration, gaussian splatting, head, efficient, 3d gaussian  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: ray marching, illumination, efficient, ar, 3d reconstruction, efficient rendering, gaussian splatting, shadow, sparse-view, 3d gaussian  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: ar, 3d reconstruction, ray tracing, geometry, fast, gaussian splatting, 3d gaussian, motion, understanding  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: ar, relightable, relighting, 3d reconstruction, ray tracing, geometry, gaussian splatting, lighting  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: face, ar, nerf, ray tracing, fast, gaussian splatting, 3d gaussian  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: ar, high-fidelity, ray tracing, fast, gaussian splatting, compact, 3d gaussian, real-time rendering  

### Relighting

*Showing the latest 50 out of 125 papers*

- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: illumination, autonomous driving, ar, nerf, outdoor, gaussian splatting, lighting, 3d gaussian, real-time rendering, global illumination  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: illumination, ar, relighting, geometry, gaussian splatting, shadow, efficient, lighting, global illumination  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 4d, geometry, reflection, semantic, gaussian splatting, head, 3d gaussian, motion, vr  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v1)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v1.pdf)  
  Keywords: illumination, ar, high-fidelity, relightable, dynamic, lightweight, geometry, outdoor, gaussian splatting, lighting, 3d gaussian  
- **[NVS-HO: A Benchmark for Novel View Synthesis of Handheld Objects](https://arxiv.org/abs/2602.05822v1)**  
  Authors: Musawar Ali, Manuel Carranza-García, Nicola Fioraio, Samuele Salti, Luigi Di Stefano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05822v1.pdf)  
  Keywords: ar, lighting, gaussian splatting, nerf  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: neural rendering, ar, geometry, reflection, gaussian splatting, 3d gaussian, real-time rendering  
- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, gaussian splatting, lighting  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: illumination, ar, nerf, 3d reconstruction, geometry, shadow  
- **[Mirage2Matter: A Physically Grounded Gaussian World Model from Video](https://arxiv.org/abs/2602.00096v1)**  
  Authors: Zhengqing Gao, Ziwen Li, Xin Wang, Jiaxin Huang, Zhenyang Ren, Mingkai Shao, Hanlue Zhang, Tianyu Huang, Yongkang Cheng, Yandong Guo, Runqi Lin, Yuanyuan Wang, Tongliang Liu, Kun Zhang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00096v1.pdf)  
  Keywords: ar, high-fidelity, 3d gaussian, geometry, gaussian splatting, efficient, lighting  

### SLAM

*Showing the latest 50 out of 150 papers*

- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: neural rendering, ar, dynamic, tracking, 4d, fast, gaussian splatting, efficient, 3d gaussian, motion  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: mapping, ar, high-fidelity, nerf, localization, 3d reconstruction, slam, robotics, gaussian splatting, face, efficient, motion  
- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: ar, semantic, compact, gaussian splatting, efficient, 3d gaussian, mapping  
- **[GSO-SLAM: Bidirectionally Coupled Gaussian Splatting and Direct Visual Odometry](https://arxiv.org/abs/2602.11714v1)**  
  Authors: Jiung Yeon, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11714v1.pdf)  
  Keywords: ar, tracking, slam, gaussian splatting, head, mapping  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: ar, segmentation, fast, gaussian splatting, efficient, dynamic, mapping  
- **[Thermal odometry and dense mapping using learned odometry and Gaussian splatting](https://arxiv.org/abs/2602.07493v2)**  
  Authors: Tianhao Zhou, Yujia Chen, Zhihao Zhan, Yuhang Ming, Jianzhu Huai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07493v2.pdf)  
  Keywords: ar, motion, slam, robotics, gaussian splatting, mapping  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: mapping, ar, dynamic, localization, tracking, survey, slam, gaussian splatting, face, efficient, 3d gaussian, motion  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, deformation, dynamic, mapping  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: avatar, ar, body, gaussian splatting, head, 3d gaussian, tracking, vr  

### Scene Understanding

*Showing the latest 50 out of 224 papers*

- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: ar, nerf, semantic, gaussian splatting, head, 3d gaussian, motion, real-time rendering  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: ar, localization, 3d gaussian, geometry, semantic, outdoor, gaussian splatting, head, lighting, mapping  
- **[FlowHOI: Flow-based Semantics-Grounded Generation of Hand-Object Interactions for Dexterous Robot Manipulation](https://arxiv.org/abs/2602.13444v1)**  
  Authors: Huajian Zeng, Lingyun Chen, Jiaqi Yang, Yuantai Zhang, Fan Shi, Peidong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13444v1.pdf)  
  Keywords: ar, high-fidelity, geometry, semantic, recognition, gaussian splatting, compact, 3d gaussian, motion  
- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: ar, semantic, compact, gaussian splatting, efficient, 3d gaussian, mapping  
- **[3DGSNav: Enhancing Vision-Language Model Reasoning for Object Navigation via Active 3D Gaussian Splatting](https://arxiv.org/abs/2602.12159v1)**  
  Authors: Wancai Zheng, Hao Chen, Xianlong Lu, Linlin Ou, Xinyi Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12159v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aczheng-cai.github.io/3dgsnav.github.io/)  
  Keywords: ar, recognition, semantic, gaussian splatting, efficient, 3d gaussian  
- **[LeafFit: Plant Assets Creation from 3D Gaussian Splatting](https://arxiv.org/abs/2602.11577v1)**  
  Authors: Chang Luo, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11577v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, efficient, deformation, 3d gaussian  
- **[ArtisanGS: Interactive Tools for Gaussian Splat Selection with AI and Human in the Loop](https://arxiv.org/abs/2602.10173v1)**  
  Authors: Clement Fuji Tsang, Anita Hu, Or Perel, Carsten Kolve, Maria Shugrina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.10173v1.pdf)  
  Keywords: ar, animation, segmentation, human, fast, 3d gaussian  
- **[GaussianCaR: Gaussian Splatting for Efficient Camera-Radar Fusion](https://arxiv.org/abs/2602.08784v1)**  
  Authors: Santiago Montiel-Marín, Miguel Antunes-García, Fabio Sánchez-García, Angel Llamazares, Holger Caesar, Luis M. Bergasa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08784v1.pdf)  
  Keywords: ar, segmentation, fast, gaussian splatting, efficient, dynamic, mapping  
- **[Informative Object-centric Next Best View for Object-aware 3D Gaussian Splatting in Cluttered Scenes](https://arxiv.org/abs/2602.08266v1)**  
  Authors: Seunghoon Jeong, Eunho Lee, Jeongyun Kim, Ayoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08266v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, semantic  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: ar, high-fidelity, dynamic, 4d, geometry, reflection, semantic, gaussian splatting, head, 3d gaussian, motion, vr  



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