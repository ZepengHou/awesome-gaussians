# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-04-07 01:24:28

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
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (337 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (385 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (85 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (383 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (57 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (429 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (232 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (29 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (143 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (149 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (231 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, vr, survey, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, ray tracing, survey, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, localization, face, slam, survey, ar, motion, tracking, dynamic, efficient  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, robotics, survey, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, nerf, survey, ar, efficient  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, 3d reconstruction, compression, compact, survey, ar, 4d, dynamic, efficient  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, localization, semantic, understanding, nerf, slam, robotics, survey, ar  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, mapping, localization, semantic, slam, robotics, survey, ar, efficient  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: geometry, gaussian splatting, 3d gaussian, fast, nerf, motion, survey, ar, 4d  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, animation, 3d reconstruction, efficient, avatar, face, lighting, efficient rendering, survey, ar, real-time rendering  

### Acceleration

*Showing the latest 50 out of 233 papers*

- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, robotics, ar, motion, tracking, dynamic, efficient  
- **[GEMM-GS: Accelerating 3D Gaussian Splatting on Tensor Cores with GEMM-Compatible Blending](https://arxiv.org/abs/2604.02120v1)**  
  Authors: Haomin Li, Bowen Zhu, Fangxin Liu, Zongwu Wang, Xinran Liang, Li Jiang, Haibing Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02120v1.pdf)  
  Keywords: nerf, gaussian splatting, 3d gaussian, acceleration  
- **[GS^2: Graph-based Spatial Distribution Optimization for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2604.01884v1)**  
  Authors: Xianben Yang, Tao Wang, Yuxuan Li, Yi Jin, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01884v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, compact, ar, dynamic, real-time rendering  
- **[FaCT-GS: Fast and Scalable CT Reconstruction with Gaussian Splatting](https://arxiv.org/abs/2604.01844v1)**  
  Authors: Pawel Tomasz Pieta, Rasmus Juul Pedersen, Sina Borgi, Jakob Sauer Jørgensen, Jens Wenzel Andreasen, Vedrana Andersen Dahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01844v1.pdf)  
  Keywords: ar, gaussian splatting, fast  
- **[Diff3R: Feed-forward 3D Gaussian Splatting with Uncertainty-aware Differentiable Optimization](https://arxiv.org/abs/2604.01030v1)**  
  Authors: Yueh-Cheng Liu, Jozef Hladký, Matthias Nießner, Angela Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01030v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, ar, sparse-view  
- **[AA-Splat: Anti-Aliased Feed-forward Gaussian Splatting](https://arxiv.org/abs/2603.29394v1)**  
  Authors: Taewoo Suh, Sungpyo Kim, Jongmin Park, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29394v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, ar, sparse-view  
- **[LG-HCC: Local Geometry-Aware Hierarchical Context Compression for 3D Gaussian Splatting](https://arxiv.org/abs/2603.28431v3)**  
  Authors: Xuan Deng, Xiandong Meng, Hengyu Man, Qiang Zhu, Tiange Zhang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28431v3.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, head, compression, nerf, compact, ar, lightweight, real-time rendering  
- **[ObjectMorpher: 3D-Aware Image Editing via Deformable 3DGS Models](https://arxiv.org/abs/2603.28152v1)**  
  Authors: Yuhuan Xie, Aoxuan Pan, Yi-Hua Huang, Chirui Chang, Peng Dai, Xin Yu, Xiaojuan Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28152v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, fast, lighting, deformation, ar  
- **[DiffSoup: Direct Differentiable Rasterization of Triangle Soup for Extreme Radiance Field Simplification](https://arxiv.org/abs/2603.27151v1)**  
  Authors: Kenji Tojo, Bernd Bickel, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27151v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, real-time rendering, ar, efficient  
- **[ViewSplat: View-Adaptive Dynamic Gaussian Splatting for Feed-Forward Synthesis](https://arxiv.org/abs/2603.25265v1)**  
  Authors: Moonyeon Jeong, Seunggi Min, Suhyeon Lee, Hongje Seong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.25265v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, fast, ar, dynamic, real-time rendering  

### Applications

*Showing the latest 50 out of 994 papers*

- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: geometry, gaussian splatting, high-fidelity, ar, 4d, dynamic, sparse-view  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, motion, deformation, ar, human, 4d, dynamic  
- **[M2StyleGS: Multi-Modality 3D Style Transfer with Gaussian Splatting](https://arxiv.org/abs/2604.03773v1)**  
  Authors: Xingyu Miao, Xueqi Qiu, Haoran Duan, Yawen Huang, Xian Wu, Jingjing Deng, Yang Long  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03773v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian  
- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, compact, ar  
- **[SpectralSplat: Appearance-Disentangled Feed-Forward Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2604.03462v1)**  
  Authors: Quentin Herau, Tianshuo Xu, Depu Meng, Jiezhi Yang, Chensheng Peng, Spencer Sherk, Yihan Hu, Wei Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03462v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, lighting, relighting, ar, autonomous driving  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, mapping, slam, lighting, compact, ar, tracking, efficient  
- **[SparseSplat: Towards Applicable Feed-Forward 3D Gaussian Splatting with Pixel-Unaligned Prediction](https://arxiv.org/abs/2604.03069v1)**  
  Authors: Zicheng Zhang, Xiangting Meng, Ke Wu, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03069v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/SparseSplat-page/.)  
  Keywords: gaussian splatting, 3d gaussian, compact, ar, efficient  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v1)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, robotics, ar, human, dynamic, sparse-view  
- **[GP-4DGS: Probabilistic 4D Gaussian Splatting from Monocular Video via Variational Gaussian Processes](https://arxiv.org/abs/2604.02915v1)**  
  Authors: Mijeong Kim, Jungtaek Kim, Bohyung Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02915v1.pdf)  
  Keywords: gaussian splatting, deformation, ar, motion, dynamic, 4d  
- **[Streaming Real-Time Rendered Scenes as 3D Gaussians](https://arxiv.org/abs/2604.02851v1)**  
  Authors: Matti Siekkinen, Teemu Kämäräinen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02851v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, lighting, relighting, ar, dynamic  

### Avatar Generation

*Showing the latest 50 out of 337 papers*

- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, motion, deformation, ar, human, 4d, dynamic  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v1)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, robotics, ar, human, dynamic, sparse-view  
- **[UNICA: A Unified Neural Framework for Controllable 3D Avatars](https://arxiv.org/abs/2604.02799v1)**  
  Authors: Jiahe Zhu, Xinyao Wang, Yiyu Zhuang, Yanwen Wang, Jing Tian, Yao Yao, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02799v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, vr, avatar, ar, human, motion, dynamic  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, head, motion, deformation, segmentation, ar, 4d, lightweight, dynamic  
- **[F3DGS: Federated 3D Gaussian Splatting for Decentralized Multi-Agent World Modeling](https://arxiv.org/abs/2604.01605v1)**  
  Authors: Morui Zhu, Mohammad Dehghani Tezerjani, Mátyás Szántó, Márton Vaitkus, Song Fu, Qing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01605v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, head, ar, efficient  
- **[Better Rigs, Not Bigger Networks: A Body Model Ablation for Gaussian Avatars](https://arxiv.org/abs/2604.01447v2)**  
  Authors: Derek Austin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01447v2.pdf)  
  Keywords: body, gaussian splatting, 3d gaussian, avatar, deformation, ar, human  
- **[LESV: Language Embedded Sparse Voxel Fusion for Open-Vocabulary 3D Scene Understanding](https://arxiv.org/abs/2604.01388v1)**  
  Authors: Fusang Wang, Nathan Piasco, Moussab Bennehar, Luis Roldão, Dzmitry Tsishkou, Fabien Moutarde  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01388v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, head, vr, semantic, understanding, ar  
- **[Autoregressive Appearance Prediction for 3D Gaussian Avatars](https://arxiv.org/abs/2604.00928v1)**  
  Authors: Michael Steiner, Zhang Chen, Alexander Richard, Vasu Agrawal, Markus Steinberger, Michael Zollhöfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00928v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, avatar, compact, ar, human, motion, dynamic  
- **[TRiGS: Temporal Rigid-Body Motion for Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2604.00538v1)**  
  Authors: Suwoong Yeom, Joonsik Nam, Seunggyu Choi, Lucas Yunkyu Lee, Sangmin Kim, Jaesik Park, Joonsoo Kim, Kugjin Yun, Kyeongbo Kong, Sukju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00538v1.pdf)  
  Keywords: gaussian splatting, ar, body, motion, dynamic, 4d  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, ray tracing, face, ar, reflection  

### Dynamic Scene

*Showing the latest 50 out of 385 papers*

- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: geometry, gaussian splatting, high-fidelity, ar, 4d, dynamic, sparse-view  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, motion, deformation, ar, human, 4d, dynamic  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v1)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, robotics, ar, human, dynamic, sparse-view  
- **[GP-4DGS: Probabilistic 4D Gaussian Splatting from Monocular Video via Variational Gaussian Processes](https://arxiv.org/abs/2604.02915v1)**  
  Authors: Mijeong Kim, Jungtaek Kim, Bohyung Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02915v1.pdf)  
  Keywords: gaussian splatting, deformation, ar, motion, dynamic, 4d  
- **[Streaming Real-Time Rendered Scenes as 3D Gaussians](https://arxiv.org/abs/2604.02851v1)**  
  Authors: Matti Siekkinen, Teemu Kämäräinen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02851v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, lighting, relighting, ar, dynamic  
- **[UNICA: A Unified Neural Framework for Controllable 3D Avatars](https://arxiv.org/abs/2604.02799v1)**  
  Authors: Jiahe Zhu, Xinyao Wang, Yiyu Zhuang, Yanwen Wang, Jing Tian, Yao Yao, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02799v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, vr, avatar, ar, human, motion, dynamic  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, dynamic, reflection  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, robotics, ar, motion, tracking, dynamic, efficient  
- **[ProDiG: Progressive Diffusion-Guided Gaussian Splatting for Aerial to Ground Reconstruction](https://arxiv.org/abs/2604.02003v1)**  
  Authors: Sirshapan Mitra, Yogesh S. Rawat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02003v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, head, motion, deformation, segmentation, ar, 4d, lightweight, dynamic  

### Few-shot

*Showing the latest 50 out of 85 papers*

- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: geometry, gaussian splatting, high-fidelity, ar, 4d, dynamic, sparse-view  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v1)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, robotics, ar, human, dynamic, sparse-view  
- **[Diff3R: Feed-forward 3D Gaussian Splatting with Uncertainty-aware Differentiable Optimization](https://arxiv.org/abs/2604.01030v1)**  
  Authors: Yueh-Cheng Liu, Jozef Hladký, Matthias Nießner, Angela Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01030v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, ar, sparse-view  
- **[AA-Splat: Anti-Aliased Feed-forward Gaussian Splatting](https://arxiv.org/abs/2603.29394v1)**  
  Authors: Taewoo Suh, Sungpyo Kim, Jongmin Park, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29394v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, ar, sparse-view  
- **[\textit{4DSurf}: High-Fidelity Dynamic Scene Surface Reconstruction](https://arxiv.org/abs/2603.28064v1)**  
  Authors: Renjie Wu, Hongdong Li, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28064v1.pdf)  
  Keywords: geometry, gaussian splatting, high-fidelity, face, motion, deformation, ar, 4d, dynamic, sparse-view  
- **[SGS-Intrinsic: Semantic-Invariant Gaussian Splatting for Sparse-View Indoor Inverse Rendering](https://arxiv.org/abs/2603.27516v2)**  
  Authors: Jiahao Niu, Rongjia Zheng, Wenju Xu, Wei-Shi Zheng, Qing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27516v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, illumination, ar, sparse view, shadow, sparse-view  
- **[Detailed Geometry and Appearance from Opportunistic Motion](https://arxiv.org/abs/2603.26665v1)**  
  Authors: Ryosuke Hirai, Kohei Yamashita, Antoine Guédon, Ryo Kawahara, Vincent Lepetit, Ko Nishino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.26665v1.pdf)  
  Keywords: geometry, gaussian splatting, illumination, ar, sparse view, motion  
- **[EmoTaG: Emotion-Aware Talking Head Synthesis on Gaussian Splatting with Few-Shot Personalization](https://arxiv.org/abs/2603.21332v2)**  
  Authors: Haolan Xu, Keli Cheng, Lei Wang, Ning Bi, Xiaoming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21332v2.pdf)  
  Keywords: few-shot, gaussian splatting, 3d gaussian, head, face, nerf, lighting, ar, motion  
- **[UniSem: Generalizable Semantic 3D Reconstruction from Sparse Unposed Images](https://arxiv.org/abs/2603.17519v1)**  
  Authors: Guibiao Liao, Qian Ren, Kaimin Liao, Hua Wang, Zhi Chen, Luchao Wang, Yaohua Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17519v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, 3d reconstruction, semantic, segmentation, ar, sparse-view  
- **[S2D: Sparse to Dense Lifting for 3D Reconstruction with Minimal Inputs](https://arxiv.org/abs/2603.10893v1)**  
  Authors: Yuzhou Ji, Qijian Tian, He Zhu, Xiaoqi Jiang, Guangzhi Cao, Lizhuang Ma, Yuan Xie, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.10893v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, 3d reconstruction, understanding, ar, sparse view, efficient  

### Geometry Reconstruction

*Showing the latest 50 out of 383 papers*

- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: geometry, gaussian splatting, high-fidelity, ar, 4d, dynamic, sparse-view  
- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, compact, ar  
- **[SpectralSplat: Appearance-Disentangled Feed-Forward Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2604.03462v1)**  
  Authors: Quentin Herau, Tianshuo Xu, Depu Meng, Jiezhi Yang, Chensheng Peng, Spencer Sherk, Yihan Hu, Wei Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03462v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, lighting, relighting, ar, autonomous driving  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, mapping, slam, lighting, compact, ar, tracking, efficient  
- **[NavCrafter: Exploring 3D Scenes from a Single Image](https://arxiv.org/abs/2604.02828v1)**  
  Authors: Hongbo Duan, Peiyu Zhuang, Yi Liu, Zhengyang Zhang, Yuxin Zhang, Pengting Luo, Fangming Liu, Xueqian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02828v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, 3d reconstruction, ar  
- **[UNICA: A Unified Neural Framework for Controllable 3D Avatars](https://arxiv.org/abs/2604.02799v1)**  
  Authors: Jiahe Zhu, Xinyao Wang, Yiyu Zhuang, Yanwen Wang, Jing Tian, Yao Yao, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02799v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, vr, avatar, ar, human, motion, dynamic  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, dynamic, reflection  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, robotics, ar, motion, tracking, dynamic, efficient  
- **[ProDiG: Progressive Diffusion-Guided Gaussian Splatting for Aerial to Ground Reconstruction](https://arxiv.org/abs/2604.02003v1)**  
  Authors: Sirshapan Mitra, Yogesh S. Rawat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02003v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar  
- **[F3DGS: Federated 3D Gaussian Splatting for Decentralized Multi-Agent World Modeling](https://arxiv.org/abs/2604.01605v1)**  
  Authors: Morui Zhu, Mohammad Dehghani Tezerjani, Mátyás Szántó, Márton Vaitkus, Song Fu, Qing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01605v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, head, ar, efficient  

### Large Scene

*Showing the latest 50 out of 57 papers*

- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v1)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, semantic, large scene, ar  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: geometry, gaussian splatting, high-fidelity, neural rendering, understanding, large scene, motion, ar, 4d, shadow, dynamic, efficient  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: gaussian splatting, outdoor, localization, ar, efficient  
- **[FilterGS: Traversal-Free Parallel Filtering and Adaptive Shrinking for Large-Scale LoD 3D Gaussian Splatting](https://arxiv.org/abs/2603.23891v1)**  
  Authors: Yixian Wang, Haolin Yu, Jiadong Tang, Yu Gao, Xihan Wang, Yufeng Yue, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23891v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, head, neural rendering, face, large scene, ar, efficient  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: gaussian splatting, outdoor, head, slam, ar, tracking, dynamic, efficient  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, outdoor, localization, ar  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, 3d reconstruction, face, urban scene, ar  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, outdoor, relightable, fast, illumination, nerf, lighting, relighting, ar, reflection  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, outdoor, semantic, face, fast, lighting, ar, lightweight  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, high-fidelity, outdoor, neural rendering, vr, nerf, ar, efficient  

### Model Compression

*Showing the latest 50 out of 429 papers*

- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, compact, ar  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, mapping, slam, lighting, compact, ar, tracking, efficient  
- **[SparseSplat: Towards Applicable Feed-Forward 3D Gaussian Splatting with Pixel-Unaligned Prediction](https://arxiv.org/abs/2604.03069v1)**  
  Authors: Zicheng Zhang, Xiangting Meng, Ke Wu, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03069v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/SparseSplat-page/.)  
  Keywords: gaussian splatting, 3d gaussian, compact, ar, efficient  
- **[Differentiable Stroke Planning with Dual Parameterization for Efficient and High-Fidelity Painting Creation](https://arxiv.org/abs/2604.02752v1)**  
  Authors: Jinfan Liu, Wuze Zhang, Zhangli Hu, Zhehan Zhao, Ye Chen, Bingbing Ni  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02752v1.pdf)  
  Keywords: ar, mapping, efficient, high-fidelity  
- **[VBGS-SLAM: Variational Bayesian Gaussian Splatting Simultaneous Localization and Mapping](https://arxiv.org/abs/2604.02696v1)**  
  Authors: Yuhan Zhu, Yanyu Zhang, Jie Xu, Wei Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02696v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, localization, slam, ar, tracking, efficient  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, robotics, ar, motion, tracking, dynamic, efficient  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, head, motion, deformation, segmentation, ar, 4d, lightweight, dynamic  
- **[GS^2: Graph-based Spatial Distribution Optimization for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2604.01884v1)**  
  Authors: Xianben Yang, Tao Wang, Yuxuan Li, Yi Jin, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01884v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, compact, ar, dynamic, real-time rendering  
- **[F3DGS: Federated 3D Gaussian Splatting for Decentralized Multi-Agent World Modeling](https://arxiv.org/abs/2604.01605v1)**  
  Authors: Morui Zhu, Mohammad Dehghani Tezerjani, Mátyás Szántó, Márton Vaitkus, Song Fu, Qing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01605v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, head, ar, efficient  
- **[Satellite-Free Training for Drone-View Geo-Localization](https://arxiv.org/abs/2604.01581v2)**  
  Authors: Tao Liu, Yingzhi Zhang, Kan Ren, Xiaoqi Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01581v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, localization, ar, lightweight  

### Quality Enhancement

*Showing the latest 50 out of 232 papers*

- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: geometry, gaussian splatting, high-fidelity, ar, 4d, dynamic, sparse-view  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, motion, deformation, ar, human, 4d, dynamic  
- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, compact, ar  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v1)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, robotics, ar, human, dynamic, sparse-view  
- **[UNICA: A Unified Neural Framework for Controllable 3D Avatars](https://arxiv.org/abs/2604.02799v1)**  
  Authors: Jiahe Zhu, Xinyao Wang, Yiyu Zhuang, Yanwen Wang, Jing Tian, Yao Yao, Hao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02799v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, vr, avatar, ar, human, motion, dynamic  
- **[Differentiable Stroke Planning with Dual Parameterization for Efficient and High-Fidelity Painting Creation](https://arxiv.org/abs/2604.02752v1)**  
  Authors: Jinfan Liu, Wuze Zhang, Zhangli Hu, Zhehan Zhao, Ye Chen, Bingbing Ni  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02752v1.pdf)  
  Keywords: ar, mapping, efficient, high-fidelity  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, head, motion, deformation, segmentation, ar, 4d, lightweight, dynamic  
- **[Autoregressive Appearance Prediction for 3D Gaussian Avatars](https://arxiv.org/abs/2604.00928v1)**  
  Authors: Michael Steiner, Zhang Chen, Alexander Richard, Vasu Agrawal, Markus Steinberger, Michael Zollhöfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00928v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, avatar, compact, ar, human, motion, dynamic  
- **[DirectFisheye-GS: Enabling Native Fisheye Input in Gaussian Splatting with Cross-View Joint Optimization](https://arxiv.org/abs/2604.00648v1)**  
  Authors: Zhengxian Yang, Fei Xie, Xutao Xue, Rui Zhang, Taicheng Huang, Yang Liu, Mengqi Ji, Tao Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00648v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, vr, ar, efficient  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: geometry, gaussian splatting, high-fidelity, neural rendering, understanding, large scene, motion, ar, 4d, shadow, dynamic, efficient  

### Ray Tracing

- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, ray tracing, face, ar, reflection  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ray tracing, mapping, localization, semantic, face, slam, ar, tracking, efficient  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ray tracing, mapping, relightable, ar, shadow, reflection  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, efficient, high-fidelity, ray tracing, face, fast, nerf, ar, real-time rendering  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, ray tracing, survey, ar  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ray marching, gaussian splatting, 3d gaussian, efficient, high-fidelity, ar, real-time rendering  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, fast, robotics, ar, efficient, ray casting  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: geometry, gaussian splatting, ray tracing, face, fast, ar, lightweight, efficient, reflection  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: gaussian splatting, ray tracing, illumination, lighting, relighting, ar, global illumination, efficient, reflection  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, outdoor, illumination, nerf, lighting, ar, autonomous driving, global illumination, real-time rendering  

### Relighting

*Showing the latest 50 out of 143 papers*

- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, motion, deformation, ar, human, 4d, dynamic  
- **[SpectralSplat: Appearance-Disentangled Feed-Forward Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2604.03462v1)**  
  Authors: Quentin Herau, Tianshuo Xu, Depu Meng, Jiezhi Yang, Chensheng Peng, Spencer Sherk, Yihan Hu, Wei Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03462v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, lighting, relighting, ar, autonomous driving  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, mapping, slam, lighting, compact, ar, tracking, efficient  
- **[Streaming Real-Time Rendered Scenes as 3D Gaussians](https://arxiv.org/abs/2604.02851v1)**  
  Authors: Matti Siekkinen, Teemu Kämäräinen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02851v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, lighting, relighting, ar, dynamic  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, dynamic, reflection  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, ray tracing, face, ar, reflection  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: geometry, gaussian splatting, high-fidelity, neural rendering, understanding, large scene, motion, ar, 4d, shadow, dynamic, efficient  
- **[LightHarmony3D: Harmonizing Illumination and Shadows for Object Insertion in 3D Gaussian Splatting](https://arxiv.org/abs/2603.29209v1)**  
  Authors: Tianyu Huang, Zhenyang Ren, Zhenchen Wan, Jiyang Zheng, Wenjie Wang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29209v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, vr, illumination, lighting, ar, shadow, efficient  
- **[ObjectMorpher: 3D-Aware Image Editing via Deformable 3DGS Models](https://arxiv.org/abs/2603.28152v1)**  
  Authors: Yuhuan Xie, Aoxuan Pan, Yi-Hua Huang, Chirui Chang, Peng Dai, Xin Yu, Xiaojuan Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28152v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, fast, lighting, deformation, ar  
- **[SGS-Intrinsic: Semantic-Invariant Gaussian Splatting for Sparse-View Indoor Inverse Rendering](https://arxiv.org/abs/2603.27516v2)**  
  Authors: Jiahao Niu, Rongjia Zheng, Wenju Xu, Wei-Shi Zheng, Qing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27516v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, illumination, ar, sparse view, shadow, sparse-view  

### SLAM

*Showing the latest 50 out of 149 papers*

- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: geometry, gaussian splatting, 3d gaussian, mapping, slam, lighting, compact, ar, tracking, efficient  
- **[Differentiable Stroke Planning with Dual Parameterization for Efficient and High-Fidelity Painting Creation](https://arxiv.org/abs/2604.02752v1)**  
  Authors: Jinfan Liu, Wuze Zhang, Zhangli Hu, Zhehan Zhao, Ye Chen, Bingbing Ni  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02752v1.pdf)  
  Keywords: ar, mapping, efficient, high-fidelity  
- **[VBGS-SLAM: Variational Bayesian Gaussian Splatting Simultaneous Localization and Mapping](https://arxiv.org/abs/2604.02696v1)**  
  Authors: Yuhan Zhu, Yanyu Zhang, Jie Xu, Wei Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02696v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, localization, slam, ar, tracking, efficient  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, fast, robotics, ar, motion, tracking, dynamic, efficient  
- **[Satellite-Free Training for Drone-View Geo-Localization](https://arxiv.org/abs/2604.01581v2)**  
  Authors: Tao Liu, Yingzhi Zhang, Kan Ren, Xiaoqi Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01581v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, localization, ar, lightweight  
- **[Compact Keyframe-Optimized Multi-Agent Gaussian Splatting SLAM](https://arxiv.org/abs/2604.00804v1)**  
  Authors: Monica M. Q. Li, Pierre-Yves Lajoie, Jialiang Liu, Giovanni Beltrame  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00804v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, localization, slam, compact, ar, lightweight, efficient  
- **[GRVS: a Generalizable and Recurrent Approach to Monocular Dynamic View Synthesis](https://arxiv.org/abs/2603.29734v1)**  
  Authors: Thomas Tanay, Mohammed Brahimi, Michal Nazarczuk, Qingwen Zhang, Sibi Catley-Chandar, Arthur Moreau, Zhensong Zhang, Eduardo Pérez-Pellitero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29734v1.pdf)  
  Keywords: gaussian splatting, efficient, mapping, ar, motion, dynamic, 4d  
- **[Efficient Camera Pose Augmentation for View Generalization in Robotic Policy Learning](https://arxiv.org/abs/2603.29192v1)**  
  Authors: Sen Wang, Huaiyi Dong, Jingyi Tian, Jiayi Li, Zhuo Yang, Tongtong Cao, Anlin Chen, Shuang Wu, Le Wang, Sanping Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29192v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, mapping, high-fidelity, ar, efficient  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: gaussian splatting, outdoor, localization, ar, efficient  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ray tracing, mapping, localization, semantic, face, slam, ar, tracking, efficient  

### Scene Understanding

*Showing the latest 50 out of 231 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, dynamic, reflection  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, head, motion, deformation, segmentation, ar, 4d, lightweight, dynamic  
- **[LESV: Language Embedded Sparse Voxel Fusion for Open-Vocabulary 3D Scene Understanding](https://arxiv.org/abs/2604.01388v1)**  
  Authors: Fusang Wang, Nathan Piasco, Moussab Bennehar, Luis Roldão, Dzmitry Tsishkou, Fabien Moutarde  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01388v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, head, vr, semantic, understanding, ar  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v1)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, semantic, large scene, ar  
- **[TreeGaussian: Tree-Guided Cascaded Contrastive Learning for Hierarchical Consistent 3D Gaussian Scene Segmentation and Understanding](https://arxiv.org/abs/2604.03309v1)**  
  Authors: Jingbin You, Zehao Li, Hao Jiang, Xinzhu Ma, Shuqin Gao, Honglong Zhao, Congcong Zheng, Tianlu Mao, Feng Dai, Yucheng Zhang, Zhaoqi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03309v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, semantic, understanding, segmentation, ar  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: geometry, gaussian splatting, high-fidelity, neural rendering, understanding, large scene, motion, ar, 4d, shadow, dynamic, efficient  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ray tracing, mapping, localization, semantic, face, slam, ar, tracking, efficient  
- **[SGS-Intrinsic: Semantic-Invariant Gaussian Splatting for Sparse-View Indoor Inverse Rendering](https://arxiv.org/abs/2603.27516v2)**  
  Authors: Jiahao Niu, Rongjia Zheng, Wenju Xu, Wei-Shi Zheng, Qing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27516v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, semantic, illumination, ar, sparse view, shadow, sparse-view  
- **[Drive-Through 3D Vehicle Exterior Reconstruction via Dynamic-Scene SfM and Distortion-Aware Gaussian Splatting](https://arxiv.org/abs/2603.26638v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.26638v1.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, high-fidelity, 3d reconstruction, semantic, face, segmentation, ar, motion, dynamic  
- **[Scene Grounding In the Wild](https://arxiv.org/abs/2603.26584v2)**  
  Authors: Tamir Cohen, Leo Segre, Shay Shomer-Chai, Shai Avidan, Hadar Averbuch-Elor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.26584v2.pdf)  
  Keywords: geometry, gaussian splatting, 3d gaussian, 3d reconstruction, semantic, ar  



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