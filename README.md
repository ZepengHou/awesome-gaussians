# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-04-10 01:26:25

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
- [Acceleration](#acceleration) (232 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (338 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (382 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (85 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (383 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (55 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (425 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (235 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (29 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (141 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (149 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (228 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: gaussian splatting, vr, survey, ar, 3d gaussian  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: gaussian splatting, 3d gaussian, survey, ar, ray tracing, mapping  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, dynamic, mapping, slam, efficient, localization, tracking, survey, ar, motion, 3d gaussian, face  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: gaussian splatting, robotics, survey, ar, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: gaussian splatting, efficient, geometry, survey, ar, nerf, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, efficient, compression, 3d reconstruction, survey, 4d, ar, compact, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: gaussian splatting, mapping, slam, semantic, localization, robotics, survey, ar, understanding, nerf, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: gaussian splatting, mapping, high-fidelity, slam, efficient, semantic, localization, robotics, survey, ar, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: gaussian splatting, fast, geometry, survey, 4d, ar, nerf, motion, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: gaussian splatting, efficient, animation, efficient rendering, 3d reconstruction, survey, ar, lighting, avatar, real-time rendering, 3d gaussian, face  

### Acceleration

*Showing the latest 50 out of 232 papers*

- **[ReconPhys: Reconstruct Appearance and Physical Attributes from Single Video](https://arxiv.org/abs/2604.07882v1)**  
  Authors: Boyuan Wang, Xiaofeng Wang, Yongkang Li, Zheng Zhu, Yifan Chang, Angen Ye, Guosheng Zhao, Chaojun Ni, Guan Huang, Yijie Ren, Yueqi Duan, Xingang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07882v1.pdf)  
  Keywords: gaussian splatting, dynamic, fast, geometry, robotics, ar, 3d gaussian  
- **[From Blobs to Spokes: High-Fidelity Surface Reconstruction via Oriented Gaussians](https://arxiv.org/abs/2604.07337v1)**  
  Authors: Diego Gomez, Antoine Guédon, Nissim Maruani, Bingchen Gong, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07337v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, fast, ar, 3d gaussian, face  
- **[Genie Sim PanoRecon: Fast Immersive Scene Generation from Single-View Panorama](https://arxiv.org/abs/2604.07105v1)**  
  Authors: Zhijun Li, Yongxin Su, Di Yang, Jichao Wang, Zheyuan Xing, Qian Wang, Maoqing Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07105v1.pdf)  
  Keywords: high-fidelity, fast, ar, 3d gaussian, face  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, dynamic, efficient, fast, tracking, 3d reconstruction, robotics, ar, motion, 3d gaussian  
- **[GEMM-GS: Accelerating 3D Gaussian Splatting on Tensor Cores with GEMM-Compatible Blending](https://arxiv.org/abs/2604.02120v2)**  
  Authors: Haomin Li, Bowen Zhu, Fangxin Liu, Zongwu Wang, Xinran Liang, Li Jiang, Haibing Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02120v2.pdf)  
  Keywords: gaussian splatting, acceleration, nerf, 3d gaussian  
- **[GS^2: Graph-based Spatial Distribution Optimization for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2604.01884v1)**  
  Authors: Xianben Yang, Tao Wang, Yuxuan Li, Yi Jin, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01884v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, compact, real-time rendering, 3d gaussian  
- **[FaCT-GS: Fast and Scalable CT Reconstruction with Gaussian Splatting](https://arxiv.org/abs/2604.01844v1)**  
  Authors: Pawel Tomasz Pieta, Rasmus Juul Pedersen, Sina Borgi, Jakob Sauer Jørgensen, Jens Wenzel Andreasen, Vedrana Andersen Dahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01844v1.pdf)  
  Keywords: gaussian splatting, ar, fast  
- **[Diff3R: Feed-forward 3D Gaussian Splatting with Uncertainty-aware Differentiable Optimization](https://arxiv.org/abs/2604.01030v1)**  
  Authors: Yueh-Cheng Liu, Jozef Hladký, Matthias Nießner, Angela Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01030v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, ar, sparse-view  
- **[AA-Splat: Anti-Aliased Feed-forward Gaussian Splatting](https://arxiv.org/abs/2603.29394v1)**  
  Authors: Taewoo Suh, Sungpyo Kim, Jongmin Park, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29394v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, 3d reconstruction, ar, sparse-view  
- **[LG-HCC: Local Geometry-Aware Hierarchical Context Compression for 3D Gaussian Splatting](https://arxiv.org/abs/2603.28431v3)**  
  Authors: Xuan Deng, Xiandong Meng, Hengyu Man, Qiang Zhu, Tiange Zhang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28431v3.pdf)  
  Keywords: gaussian splatting, high-fidelity, compact, compression, geometry, ar, lightweight, nerf, head, real-time rendering, 3d gaussian  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Generative 3D Gaussian Splatting for Arbitrary-ResolutionAtmospheric Downscaling and Forecasting](https://arxiv.org/abs/2604.07928v1)**  
  Authors: Tao Hana, Zhibin Wen, Zhenghao Chen, Fenghua Lin, Junyu Gao, Song Guo, Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07928v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, 3d gaussian  
- **[ReconPhys: Reconstruct Appearance and Physical Attributes from Single Video](https://arxiv.org/abs/2604.07882v1)**  
  Authors: Boyuan Wang, Xiaofeng Wang, Yongkang Li, Zheng Zhu, Yifan Chang, Angen Ye, Guosheng Zhao, Chaojun Ni, Guan Huang, Yijie Ren, Yueqi Duan, Xingang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07882v1.pdf)  
  Keywords: gaussian splatting, dynamic, fast, geometry, robotics, ar, 3d gaussian  
- **[GEAR: GEometry-motion Alternating Refinement for Articulated Object Modeling with Gaussian Splatting](https://arxiv.org/abs/2604.07728v1)**  
  Authors: Jialin Li, Bin Fu, Ruiping Wang, Xilin Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07728v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, segmentation, geometry, ar, motion  
- **[From Blobs to Spokes: High-Fidelity Surface Reconstruction via Oriented Gaussians](https://arxiv.org/abs/2604.07337v1)**  
  Authors: Diego Gomez, Antoine Guédon, Nissim Maruani, Bingchen Gong, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07337v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, fast, ar, 3d gaussian, face  
- **[Splats under Pressure: Exploring Performance-Energy Trade-offs in Real-Time 3D Gaussian Splatting under Constrained GPU Budgets](https://arxiv.org/abs/2604.07177v1)**  
  Authors: Muhammad Fahim Tajwar, Arthur Wuhrlin, Bhojan Anand  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07177v1.pdf)  
  Keywords: gaussian splatting, head, ar, 3d gaussian  
- **[Genie Sim PanoRecon: Fast Immersive Scene Generation from Single-View Panorama](https://arxiv.org/abs/2604.07105v1)**  
  Authors: Zhijun Li, Yongxin Su, Di Yang, Jichao Wang, Zheyuan Xing, Qian Wang, Maoqing Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07105v1.pdf)  
  Keywords: high-fidelity, fast, ar, 3d gaussian, face  
- **[Radio-Frequency Inverse Rendering for Wireless Environment Modeling](https://arxiv.org/abs/2604.07086v1)**  
  Authors: Fuhai Wang, Zihan Jin, Lehang Wang, Xuehui Dong, Tiebin Mi, Robert Caiming Qiu, Zenan ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07086v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, ar, face  
- **[DOC-GS: Dual-Domain Observation and Calibration for Reliable Sparse-View Gaussian Splatting](https://arxiv.org/abs/2604.06739v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06739v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, understanding, sparse-view  
- **[4D Vessel Reconstruction for Benchtop Thrombectomy Analysis](https://arxiv.org/abs/2604.06671v1)**  
  Authors: Ethan Nguyen, Javier Carmona, Arisa Matsuzaki, Naoki Kaneko, Katsushi Arisaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06671v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ethanuser.github.io/vessel4D)  
  Keywords: gaussian splatting, mapping, motion, tracking, 4d, ar, deformation, face  
- **[GS-Surrogate: Deformable Gaussian Splatting for Parameter Space Exploration of Ensemble Simulations](https://arxiv.org/abs/2604.06358v1)**  
  Authors: Ziwei Li, Rumali Perera, Angus Forbes, Ken Moreland, Dave Pugmire, Scott Klasky, Wei-Lun Chao, Han-Wei Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06358v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, deformation, face  

### Avatar Generation

*Showing the latest 50 out of 338 papers*

- **[From Blobs to Spokes: High-Fidelity Surface Reconstruction via Oriented Gaussians](https://arxiv.org/abs/2604.07337v1)**  
  Authors: Diego Gomez, Antoine Guédon, Nissim Maruani, Bingchen Gong, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07337v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, fast, ar, 3d gaussian, face  
- **[Splats under Pressure: Exploring Performance-Energy Trade-offs in Real-Time 3D Gaussian Splatting under Constrained GPU Budgets](https://arxiv.org/abs/2604.07177v1)**  
  Authors: Muhammad Fahim Tajwar, Arthur Wuhrlin, Bhojan Anand  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07177v1.pdf)  
  Keywords: gaussian splatting, head, ar, 3d gaussian  
- **[Genie Sim PanoRecon: Fast Immersive Scene Generation from Single-View Panorama](https://arxiv.org/abs/2604.07105v1)**  
  Authors: Zhijun Li, Yongxin Su, Di Yang, Jichao Wang, Zheyuan Xing, Qian Wang, Maoqing Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07105v1.pdf)  
  Keywords: high-fidelity, fast, ar, 3d gaussian, face  
- **[Radio-Frequency Inverse Rendering for Wireless Environment Modeling](https://arxiv.org/abs/2604.07086v1)**  
  Authors: Fuhai Wang, Zihan Jin, Lehang Wang, Xuehui Dong, Tiebin Mi, Robert Caiming Qiu, Zenan ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07086v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, ar, face  
- **[4D Vessel Reconstruction for Benchtop Thrombectomy Analysis](https://arxiv.org/abs/2604.06671v1)**  
  Authors: Ethan Nguyen, Javier Carmona, Arisa Matsuzaki, Naoki Kaneko, Katsushi Arisaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06671v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ethanuser.github.io/vessel4D)  
  Keywords: gaussian splatting, mapping, motion, tracking, 4d, ar, deformation, face  
- **[GS-Surrogate: Deformable Gaussian Splatting for Parameter Space Exploration of Ensemble Simulations](https://arxiv.org/abs/2604.06358v1)**  
  Authors: Ziwei Li, Rumali Perera, Angus Forbes, Ken Moreland, Dave Pugmire, Scott Klasky, Wei-Lun Chao, Han-Wei Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06358v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, deformation, face  
- **[Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction](https://arxiv.org/abs/2604.05908v1)**  
  Authors: Yangyi Xiao, Siting Zhu, Baoquan Yang, Tianchen Deng, Yongbo Chen, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05908v1.pdf)  
  Keywords: gaussian splatting, reflection, high-fidelity, geometry, illumination, ar, lighting, autonomous driving, face  
- **[In Depth We Trust: Reliable Monocular Depth Supervision for Gaussian Splatting](https://arxiv.org/abs/2604.05715v1)**  
  Authors: Wenhui Xiao, Ethan Goan, Rodrigo Santa Cruz, David Ahmedt-Aristizabal, Olivier Salvado, Clinton Fookes, Leo Lebrat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05715v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, ar, face  
- **[AvatarPointillist: AutoRegressive 4D Gaussian Avatarization](https://arxiv.org/abs/2604.04787v1)**  
  Authors: Hongyu Liu, Xuan Wang, Yating Wang, Zijian Wu, Ziyu Wan, Yue Ma, Runtao Liu, Boyao Zhou, Yujun Shen, Qifeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04787v1.pdf)  
  Keywords: gaussian splatting, dynamic, animation, 4d, ar, avatar, 3d gaussian  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, deformation, 4d, human, lighting, ar, motion  

### Dynamic Scene

*Showing the latest 50 out of 382 papers*

- **[ReconPhys: Reconstruct Appearance and Physical Attributes from Single Video](https://arxiv.org/abs/2604.07882v1)**  
  Authors: Boyuan Wang, Xiaofeng Wang, Yongkang Li, Zheng Zhu, Yifan Chang, Angen Ye, Guosheng Zhao, Chaojun Ni, Guan Huang, Yijie Ren, Yueqi Duan, Xingang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07882v1.pdf)  
  Keywords: gaussian splatting, dynamic, fast, geometry, robotics, ar, 3d gaussian  
- **[GEAR: GEometry-motion Alternating Refinement for Articulated Object Modeling with Gaussian Splatting](https://arxiv.org/abs/2604.07728v1)**  
  Authors: Jialin Li, Bin Fu, Ruiping Wang, Xilin Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07728v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, segmentation, geometry, ar, motion  
- **[4D Vessel Reconstruction for Benchtop Thrombectomy Analysis](https://arxiv.org/abs/2604.06671v1)**  
  Authors: Ethan Nguyen, Javier Carmona, Arisa Matsuzaki, Naoki Kaneko, Katsushi Arisaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06671v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ethanuser.github.io/vessel4D)  
  Keywords: gaussian splatting, mapping, motion, tracking, 4d, ar, deformation, face  
- **[GS-Surrogate: Deformable Gaussian Splatting for Parameter Space Exploration of Ensemble Simulations](https://arxiv.org/abs/2604.06358v1)**  
  Authors: Ziwei Li, Rumali Perera, Angus Forbes, Ken Moreland, Dave Pugmire, Scott Klasky, Wei-Lun Chao, Han-Wei Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06358v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, deformation, face  
- **[PanopticQuery: Unified Query-Time Reasoning for 4D Scenes](https://arxiv.org/abs/2604.05638v1)**  
  Authors: Ruilin Tang, Yang Zhou, Zhong Ye, Wenxi Liu, Yan Huang, Shengfeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05638v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, semantic, 4d, ar, understanding  
- **[AvatarPointillist: AutoRegressive 4D Gaussian Avatarization](https://arxiv.org/abs/2604.04787v1)**  
  Authors: Hongyu Liu, Xuan Wang, Yating Wang, Zijian Wu, Ziyu Wan, Yue Ma, Runtao Liu, Boyao Zhou, Yujun Shen, Qifeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04787v1.pdf)  
  Keywords: gaussian splatting, dynamic, animation, 4d, ar, avatar, 3d gaussian  
- **[GA-GS: Generation-Assisted Gaussian Splatting for Static Scene Reconstruction](https://arxiv.org/abs/2604.04331v1)**  
  Authors: Yedong Shen, Shiqi Zhang, Sha Zhang, Yifan Duan, Xinran Zhang, Wenhao Yu, Lu Zhang, Jiajun Deng, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04331v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, autonomous driving, motion  
- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: gaussian splatting, dynamic, high-fidelity, geometry, 4d, ar, sparse-view  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, deformation, 4d, human, lighting, ar, motion  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v2)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v2.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 3d gaussian, vr, robotics, human, ar, sparse-view  

### Few-shot

*Showing the latest 50 out of 85 papers*

- **[DOC-GS: Dual-Domain Observation and Calibration for Reliable Sparse-View Gaussian Splatting](https://arxiv.org/abs/2604.06739v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06739v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, understanding, sparse-view  
- **[PR-IQA: Partial-Reference Image Quality Assessment for Diffusion-Based Novel View Synthesis](https://arxiv.org/abs/2604.04576v2)**  
  Authors: Inseong Choi, Siwoo Lee, Seung-Hun Nam, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04576v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kakaomacao.github.io/pr-iqa-project-page/.)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, ar, sparse-view  
- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: gaussian splatting, dynamic, high-fidelity, geometry, 4d, ar, sparse-view  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v2)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v2.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 3d gaussian, vr, robotics, human, ar, sparse-view  
- **[Diff3R: Feed-forward 3D Gaussian Splatting with Uncertainty-aware Differentiable Optimization](https://arxiv.org/abs/2604.01030v1)**  
  Authors: Yueh-Cheng Liu, Jozef Hladký, Matthias Nießner, Angela Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01030v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, ar, sparse-view  
- **[AA-Splat: Anti-Aliased Feed-forward Gaussian Splatting](https://arxiv.org/abs/2603.29394v1)**  
  Authors: Taewoo Suh, Sungpyo Kim, Jongmin Park, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29394v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, fast, 3d reconstruction, ar, sparse-view  
- **[\textit{4DSurf}: High-Fidelity Dynamic Scene Surface Reconstruction](https://arxiv.org/abs/2603.28064v1)**  
  Authors: Renjie Wu, Hongdong Li, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28064v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, geometry, deformation, 4d, ar, motion, sparse-view, face  
- **[SGS-Intrinsic: Semantic-Invariant Gaussian Splatting for Sparse-View Indoor Inverse Rendering](https://arxiv.org/abs/2603.27516v2)**  
  Authors: Jiahao Niu, Rongjia Zheng, Wenju Xu, Wei-Shi Zheng, Qing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27516v2.pdf)  
  Keywords: gaussian splatting, sparse view, semantic, shadow, geometry, illumination, sparse-view, ar, 3d gaussian  
- **[Detailed Geometry and Appearance from Opportunistic Motion](https://arxiv.org/abs/2603.26665v1)**  
  Authors: Ryosuke Hirai, Kohei Yamashita, Antoine Guédon, Ryo Kawahara, Vincent Lepetit, Ko Nishino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.26665v1.pdf)  
  Keywords: gaussian splatting, sparse view, geometry, illumination, ar, motion  
- **[EmoTaG: Emotion-Aware Talking Head Synthesis on Gaussian Splatting with Few-Shot Personalization](https://arxiv.org/abs/2603.21332v2)**  
  Authors: Haolan Xu, Keli Cheng, Lei Wang, Ning Bi, Xiaoming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21332v2.pdf)  
  Keywords: gaussian splatting, few-shot, ar, lighting, nerf, head, motion, 3d gaussian, face  

### Geometry Reconstruction

*Showing the latest 50 out of 383 papers*

- **[ReconPhys: Reconstruct Appearance and Physical Attributes from Single Video](https://arxiv.org/abs/2604.07882v1)**  
  Authors: Boyuan Wang, Xiaofeng Wang, Yongkang Li, Zheng Zhu, Yifan Chang, Angen Ye, Guosheng Zhao, Chaojun Ni, Guan Huang, Yijie Ren, Yueqi Duan, Xingang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07882v1.pdf)  
  Keywords: gaussian splatting, dynamic, fast, geometry, robotics, ar, 3d gaussian  
- **[GEAR: GEometry-motion Alternating Refinement for Articulated Object Modeling with Gaussian Splatting](https://arxiv.org/abs/2604.07728v1)**  
  Authors: Jialin Li, Bin Fu, Ruiping Wang, Xilin Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07728v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, segmentation, geometry, ar, motion  
- **[Radio-Frequency Inverse Rendering for Wireless Environment Modeling](https://arxiv.org/abs/2604.07086v1)**  
  Authors: Fuhai Wang, Zihan Jin, Lehang Wang, Xuehui Dong, Tiebin Mi, Robert Caiming Qiu, Zenan ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07086v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, ar, face  
- **[Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction](https://arxiv.org/abs/2604.05908v1)**  
  Authors: Yangyi Xiao, Siting Zhu, Baoquan Yang, Tianchen Deng, Yongbo Chen, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05908v1.pdf)  
  Keywords: gaussian splatting, reflection, high-fidelity, geometry, illumination, ar, lighting, autonomous driving, face  
- **[GaussianGrow: Geometry-aware Gaussian Growing from 3D Point Clouds with Text Guidance](https://arxiv.org/abs/2604.05721v1)**  
  Authors: Weiqi Zhang, Junsheng Zhou, Haotian Geng, Kanle Shi, Shenkun Xu, Yi Fang, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05721v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/GaussianGrow)  
  Keywords: gaussian splatting, ar, 3d gaussian, geometry  
- **[In Depth We Trust: Reliable Monocular Depth Supervision for Gaussian Splatting](https://arxiv.org/abs/2604.05715v1)**  
  Authors: Wenhui Xiao, Ethan Goan, Rodrigo Santa Cruz, David Ahmedt-Aristizabal, Olivier Salvado, Clinton Fookes, Leo Lebrat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05715v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, ar, face  
- **[3DTurboQuant: Training-Free Near-Optimal Quantization for 3D Reconstruction Models](https://arxiv.org/abs/2604.05366v1)**  
  Authors: Jae Joong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05366v1.pdf)  
  Keywords: gaussian splatting, compression, 3d reconstruction, ar, nerf, 3d gaussian  
- **[SmokeGS-R: Physics-Guided Pseudo-Clean 3DGS for Real-World Multi-View Smoke Restoration](https://arxiv.org/abs/2604.05301v1)**  
  Authors: Xueming Fu, Lixia Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05301v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d reconstruction, ar, 3d gaussian  
- **[PR-IQA: Partial-Reference Image Quality Assessment for Diffusion-Based Novel View Synthesis](https://arxiv.org/abs/2604.04576v2)**  
  Authors: Inseong Choi, Siwoo Lee, Seung-Hun Nam, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04576v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kakaomacao.github.io/pr-iqa-project-page/.)  
  Keywords: gaussian splatting, 3d gaussian, 3d reconstruction, ar, sparse-view  
- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: gaussian splatting, dynamic, high-fidelity, geometry, 4d, ar, sparse-view  

### Large Scene

*Showing the latest 50 out of 55 papers*

- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: gaussian splatting, large scene, semantic, ar, 3d gaussian  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: gaussian splatting, large scene, dynamic, high-fidelity, neural rendering, efficient, shadow, geometry, 4d, ar, understanding, motion  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: gaussian splatting, efficient, localization, ar, outdoor  
- **[FilterGS: Traversal-Free Parallel Filtering and Adaptive Shrinking for Large-Scale LoD 3D Gaussian Splatting](https://arxiv.org/abs/2603.23891v1)**  
  Authors: Yixian Wang, Haolin Yu, Jiadong Tang, Yu Gao, Xihan Wang, Yufeng Yue, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23891v1.pdf)  
  Keywords: gaussian splatting, large scene, neural rendering, efficient, ar, head, 3d gaussian, face  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: gaussian splatting, dynamic, slam, efficient, tracking, head, ar, outdoor  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: gaussian splatting, localization, geometry, ar, outdoor, 3d gaussian  
- **[EntON: Eigenentropy-Optimized Neighborhood Densification in 3D Gaussian Splatting](https://arxiv.org/abs/2603.06216v1)**  
  Authors: Miriam Jäger, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.06216v1.pdf)  
  Keywords: gaussian splatting, urban scene, geometry, 3d reconstruction, ar, 3d gaussian, face  
- **[R3GW: Relightable 3D Gaussians for Outdoor Scenes in the Wild](https://arxiv.org/abs/2603.02801v1)**  
  Authors: Margherita Lea Corona, Wieland Morgenstern, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.02801v1.pdf)  
  Keywords: gaussian splatting, reflection, relightable, fast, relighting, 3d reconstruction, illumination, ar, lighting, nerf, outdoor, 3d gaussian  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: gaussian splatting, semantic, fast, ar, lighting, lightweight, outdoor, 3d gaussian, face  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: gaussian splatting, neural rendering, high-fidelity, efficient, vr, 3d reconstruction, ar, nerf, outdoor, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 425 papers*

- **[Generative 3D Gaussian Splatting for Arbitrary-ResolutionAtmospheric Downscaling and Forecasting](https://arxiv.org/abs/2604.07928v1)**  
  Authors: Tao Hana, Zhibin Wen, Zhenghao Chen, Fenghua Lin, Junyu Gao, Song Guo, Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07928v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, 3d gaussian  
- **[GS-Surrogate: Deformable Gaussian Splatting for Parameter Space Exploration of Ensemble Simulations](https://arxiv.org/abs/2604.06358v1)**  
  Authors: Ziwei Li, Rumali Perera, Angus Forbes, Ken Moreland, Dave Pugmire, Scott Klasky, Wei-Lun Chao, Han-Wei Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06358v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, deformation, face  
- **[3D Smoke Scene Reconstruction Guided by Vision Priors from Multimodal Large Language Models](https://arxiv.org/abs/2604.05687v1)**  
  Authors: Xinye Zheng, Fei Wang, Yiqi Nie, Kun Li, Junjie Chen, Jiaqi Zhao, Yanyan Wei, Zhiliang Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05687v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, lightweight, 3d gaussian  
- **[3DTurboQuant: Training-Free Near-Optimal Quantization for 3D Reconstruction Models](https://arxiv.org/abs/2604.05366v1)**  
  Authors: Jae Joong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05366v1.pdf)  
  Keywords: gaussian splatting, compression, 3d reconstruction, ar, nerf, 3d gaussian  
- **[GaussFly: Contrastive Reinforcement Learning for Visuomotor Policies in 3D Gaussian Fields](https://arxiv.org/abs/2604.05062v1)**  
  Authors: Yuhang Zhang, Mingsheng Li, Yujing Shang, Zhuoyuan Yu, Chao Yan, Jiaping Xiao, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05062v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, ar, compact, 3d gaussian  
- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, geometry, ar, compact, 3d gaussian  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: gaussian splatting, mapping, slam, efficient, geometry, tracking, ar, lighting, compact, 3d gaussian  
- **[SparseSplat: Towards Applicable Feed-Forward 3D Gaussian Splatting with Pixel-Unaligned Prediction](https://arxiv.org/abs/2604.03069v1)**  
  Authors: Zicheng Zhang, Xiangting Meng, Ke Wu, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03069v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/SparseSplat-page/.)  
  Keywords: gaussian splatting, efficient, ar, compact, 3d gaussian  
- **[Differentiable Stroke Planning with Dual Parameterization for Efficient and High-Fidelity Painting Creation](https://arxiv.org/abs/2604.02752v1)**  
  Authors: Jinfan Liu, Wuze Zhang, Zhangli Hu, Zhehan Zhao, Ye Chen, Bingbing Ni  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02752v1.pdf)  
  Keywords: efficient, ar, mapping, high-fidelity  
- **[VBGS-SLAM: Variational Bayesian Gaussian Splatting Simultaneous Localization and Mapping](https://arxiv.org/abs/2604.02696v1)**  
  Authors: Yuhan Zhu, Yanyu Zhang, Jie Xu, Wei Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02696v1.pdf)  
  Keywords: gaussian splatting, mapping, slam, efficient, localization, tracking, ar, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 235 papers*

- **[GEAR: GEometry-motion Alternating Refinement for Articulated Object Modeling with Gaussian Splatting](https://arxiv.org/abs/2604.07728v1)**  
  Authors: Jialin Li, Bin Fu, Ruiping Wang, Xilin Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07728v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, segmentation, geometry, ar, motion  
- **[From Blobs to Spokes: High-Fidelity Surface Reconstruction via Oriented Gaussians](https://arxiv.org/abs/2604.07337v1)**  
  Authors: Diego Gomez, Antoine Guédon, Nissim Maruani, Bingchen Gong, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07337v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, fast, ar, 3d gaussian, face  
- **[Genie Sim PanoRecon: Fast Immersive Scene Generation from Single-View Panorama](https://arxiv.org/abs/2604.07105v1)**  
  Authors: Zhijun Li, Yongxin Su, Di Yang, Jichao Wang, Zheyuan Xing, Qian Wang, Maoqing Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07105v1.pdf)  
  Keywords: high-fidelity, fast, ar, 3d gaussian, face  
- **[Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction](https://arxiv.org/abs/2604.05908v1)**  
  Authors: Yangyi Xiao, Siting Zhu, Baoquan Yang, Tianchen Deng, Yongbo Chen, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05908v1.pdf)  
  Keywords: gaussian splatting, reflection, high-fidelity, geometry, illumination, ar, lighting, autonomous driving, face  
- **[PanopticQuery: Unified Query-Time Reasoning for 4D Scenes](https://arxiv.org/abs/2604.05638v1)**  
  Authors: Ruilin Tang, Yang Zhou, Zhong Ye, Wenxi Liu, Yan Huang, Shengfeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05638v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, semantic, 4d, ar, understanding  
- **[GaussFly: Contrastive Reinforcement Learning for Visuomotor Policies in 3D Gaussian Fields](https://arxiv.org/abs/2604.05062v1)**  
  Authors: Yuhang Zhang, Mingsheng Li, Yujing Shang, Zhuoyuan Yu, Chao Yan, Jiaping Xiao, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05062v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, ar, compact, 3d gaussian  
- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: gaussian splatting, dynamic, high-fidelity, geometry, 4d, ar, sparse-view  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, deformation, 4d, human, lighting, ar, motion  
- **[CGHair: Compact Gaussian Hair Reconstruction with Card Clustering](https://arxiv.org/abs/2604.03716v1)**  
  Authors: Haimin Luo, Srinjay Sarkar, Albert Mosella-Montoro, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03716v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, geometry, ar, compact, 3d gaussian  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v2)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v2.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 3d gaussian, vr, robotics, human, ar, sparse-view  

### Ray Tracing

- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, reflection, ar, ray tracing, face  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: gaussian splatting, mapping, slam, efficient, semantic, localization, tracking, ar, ray tracing, 3d gaussian, face  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: gaussian splatting, reflection, relightable, mapping, shadow, ar, ray tracing, 3d gaussian  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: gaussian splatting, high-fidelity, efficient, fast, geometry, ar, nerf, ray tracing, real-time rendering, 3d gaussian, face  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: gaussian splatting, 3d gaussian, survey, ar, ray tracing, mapping  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, efficient, ar, real-time rendering, ray marching, 3d gaussian  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: gaussian splatting, efficient, fast, geometry, robotics, ar, ray casting, 3d gaussian  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: gaussian splatting, reflection, efficient, fast, geometry, ar, lightweight, ray tracing, face  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: gaussian splatting, reflection, efficient, relighting, illumination, ar, lighting, global illumination, ray tracing  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: gaussian splatting, illumination, autonomous driving, ar, lighting, nerf, global illumination, outdoor, real-time rendering, 3d gaussian  

### Relighting

*Showing the latest 50 out of 141 papers*

- **[Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction](https://arxiv.org/abs/2604.05908v1)**  
  Authors: Yangyi Xiao, Siting Zhu, Baoquan Yang, Tianchen Deng, Yongbo Chen, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05908v1.pdf)  
  Keywords: gaussian splatting, reflection, high-fidelity, geometry, illumination, ar, lighting, autonomous driving, face  
- **[HOIGS: Human-Object Interaction Gaussian Splatting](https://arxiv.org/abs/2604.04016v1)**  
  Authors: Taewoo Kim, Suwoong Yeom, Jaehyun Pyun, Geonho Cha, Dongyoon Wee, Joonsik Nam, Yun-Seong Jeong, Kyeongbo Kong, Suk-Ju Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04016v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, deformation, 4d, human, lighting, ar, motion  
- **[SpectralSplat: Appearance-Disentangled Feed-Forward Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2604.03462v1)**  
  Authors: Quentin Herau, Tianshuo Xu, Depu Meng, Jiezhi Yang, Chensheng Peng, Spencer Sherk, Yihan Hu, Wei Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03462v1.pdf)  
  Keywords: gaussian splatting, relighting, geometry, ar, lighting, autonomous driving, 3d gaussian  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: gaussian splatting, mapping, slam, efficient, geometry, tracking, ar, lighting, compact, 3d gaussian  
- **[Streaming Real-Time Rendered Scenes as 3D Gaussians](https://arxiv.org/abs/2604.02851v1)**  
  Authors: Matti Siekkinen, Teemu Kämäräinen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02851v1.pdf)  
  Keywords: gaussian splatting, dynamic, relighting, ar, lighting, 3d gaussian  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: gaussian splatting, reflection, dynamic, semantic, geometry, 3d gaussian  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, reflection, ar, ray tracing, face  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: gaussian splatting, large scene, dynamic, high-fidelity, neural rendering, efficient, shadow, geometry, 4d, ar, understanding, motion  
- **[LightHarmony3D: Harmonizing Illumination and Shadows for Object Insertion in 3D Gaussian Splatting](https://arxiv.org/abs/2603.29209v1)**  
  Authors: Tianyu Huang, Zhenyang Ren, Zhenchen Wan, Jiyang Zheng, Wenjie Wang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29209v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, efficient, vr, shadow, geometry, illumination, ar, lighting, 3d gaussian  
- **[ObjectMorpher: 3D-Aware Image Editing via Deformable 3DGS Models](https://arxiv.org/abs/2603.28152v1)**  
  Authors: Yuhuan Xie, Aoxuan Pan, Yi-Hua Huang, Chirui Chang, Peng Dai, Xin Yu, Xiaojuan Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.28152v1.pdf)  
  Keywords: gaussian splatting, fast, geometry, ar, lighting, deformation, 3d gaussian  

### SLAM

*Showing the latest 50 out of 149 papers*

- **[4D Vessel Reconstruction for Benchtop Thrombectomy Analysis](https://arxiv.org/abs/2604.06671v1)**  
  Authors: Ethan Nguyen, Javier Carmona, Arisa Matsuzaki, Naoki Kaneko, Katsushi Arisaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06671v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ethanuser.github.io/vessel4D)  
  Keywords: gaussian splatting, mapping, motion, tracking, 4d, ar, deformation, face  
- **[LSGS-Loc: Towards Robust 3DGS-Based Visual Localization for Large-Scale UAV Scenarios](https://arxiv.org/abs/2604.05402v1)**  
  Authors: Xiang Zhang, Tengfei Wang, Fang Xu, Xin Wang, Zongqian Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05402v1.pdf)  
  Keywords: gaussian splatting, ar, localization, 3d gaussian  
- **[Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM](https://arxiv.org/abs/2604.03092v1)**  
  Authors: Zicheng Zhang, Ke Wu, Xiangting Meng, Keyu Liu, Jieru Zhao, Wenchao Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03092v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://victkk.github.io/flash-mono.)  
  Keywords: gaussian splatting, mapping, slam, efficient, geometry, tracking, ar, lighting, compact, 3d gaussian  
- **[Differentiable Stroke Planning with Dual Parameterization for Efficient and High-Fidelity Painting Creation](https://arxiv.org/abs/2604.02752v1)**  
  Authors: Jinfan Liu, Wuze Zhang, Zhangli Hu, Zhehan Zhao, Ye Chen, Bingbing Ni  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02752v1.pdf)  
  Keywords: efficient, ar, mapping, high-fidelity  
- **[VBGS-SLAM: Variational Bayesian Gaussian Splatting Simultaneous Localization and Mapping](https://arxiv.org/abs/2604.02696v1)**  
  Authors: Yuhan Zhu, Yanyu Zhang, Jie Xu, Wei Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02696v1.pdf)  
  Keywords: gaussian splatting, mapping, slam, efficient, localization, tracking, ar, 3d gaussian  
- **[TrackerSplat: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://arxiv.org/abs/2604.02586v1)**  
  Authors: Daheng Yin, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02586v1.pdf)  
  Keywords: gaussian splatting, dynamic, efficient, fast, tracking, 3d reconstruction, robotics, ar, motion, 3d gaussian  
- **[Satellite-Free Training for Drone-View Geo-Localization](https://arxiv.org/abs/2604.01581v2)**  
  Authors: Tao Liu, Yingzhi Zhang, Kan Ren, Xiaoqi Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01581v2.pdf)  
  Keywords: gaussian splatting, localization, geometry, ar, lightweight, 3d gaussian  
- **[Compact Keyframe-Optimized Multi-Agent Gaussian Splatting SLAM](https://arxiv.org/abs/2604.00804v1)**  
  Authors: Monica M. Q. Li, Pierre-Yves Lajoie, Jialiang Liu, Giovanni Beltrame  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00804v1.pdf)  
  Keywords: gaussian splatting, mapping, slam, efficient, localization, ar, lightweight, compact, 3d gaussian  
- **[GRVS: a Generalizable and Recurrent Approach to Monocular Dynamic View Synthesis](https://arxiv.org/abs/2603.29734v1)**  
  Authors: Thomas Tanay, Mohammed Brahimi, Michal Nazarczuk, Qingwen Zhang, Sibi Catley-Chandar, Arthur Moreau, Zhensong Zhang, Eduardo Pérez-Pellitero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29734v1.pdf)  
  Keywords: gaussian splatting, dynamic, efficient, 4d, ar, motion, mapping  
- **[Efficient Camera Pose Augmentation for View Generalization in Robotic Policy Learning](https://arxiv.org/abs/2603.29192v1)**  
  Authors: Sen Wang, Huaiyi Dong, Jingyi Tian, Jiayi Li, Zhuo Yang, Tongtong Cao, Anlin Chen, Shuang Wu, Le Wang, Sanping Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29192v1.pdf)  
  Keywords: gaussian splatting, mapping, high-fidelity, efficient, ar, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 228 papers*

- **[GEAR: GEometry-motion Alternating Refinement for Articulated Object Modeling with Gaussian Splatting](https://arxiv.org/abs/2604.07728v1)**  
  Authors: Jialin Li, Bin Fu, Ruiping Wang, Xilin Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.07728v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, segmentation, geometry, ar, motion  
- **[DOC-GS: Dual-Domain Observation and Calibration for Reliable Sparse-View Gaussian Splatting](https://arxiv.org/abs/2604.06739v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06739v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, understanding, sparse-view  
- **[PanopticQuery: Unified Query-Time Reasoning for 4D Scenes](https://arxiv.org/abs/2604.05638v1)**  
  Authors: Ruilin Tang, Yang Zhou, Zhong Ye, Wenxi Liu, Yan Huang, Shengfeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05638v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, semantic, 4d, ar, understanding  
- **[Indoor Asset Detection in Large Scale 360° Drone-Captured Imagery via 3D Gaussian Splatting](https://arxiv.org/abs/2604.05316v1)**  
  Authors: Monica Tang, Avideh Zakhor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.05316v1.pdf)  
  Keywords: gaussian splatting, segmentation, semantic, ar, 3d gaussian  
- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2604.02781v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02781v1.pdf)  
  Keywords: gaussian splatting, reflection, dynamic, semantic, geometry, 3d gaussian  
- **[Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation](https://arxiv.org/abs/2604.01994v1)**  
  Authors: Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01994v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, segmentation, deformation, 4d, ar, lightweight, head, motion, 3d gaussian  
- **[LESV: Language Embedded Sparse Voxel Fusion for Open-Vocabulary 3D Scene Understanding](https://arxiv.org/abs/2604.01388v1)**  
  Authors: Fusang Wang, Nathan Piasco, Moussab Bennehar, Luis Roldão, Dzmitry Tsishkou, Fabien Moutarde  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01388v1.pdf)  
  Keywords: gaussian splatting, semantic, vr, geometry, ar, understanding, head, 3d gaussian  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: gaussian splatting, large scene, semantic, ar, 3d gaussian  
- **[TreeGaussian: Tree-Guided Cascaded Contrastive Learning for Hierarchical Consistent 3D Gaussian Scene Segmentation and Understanding](https://arxiv.org/abs/2604.03309v1)**  
  Authors: Jingbin You, Zehao Li, Hao Jiang, Xinzhu Ma, Shuqin Gao, Honglong Zhao, Congcong Zheng, Tianlu Mao, Feng Dai, Yucheng Zhang, Zhaoqi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.03309v1.pdf)  
  Keywords: gaussian splatting, segmentation, semantic, ar, understanding, 3d gaussian  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: gaussian splatting, large scene, dynamic, high-fidelity, neural rendering, efficient, shadow, geometry, 4d, ar, understanding, motion  



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