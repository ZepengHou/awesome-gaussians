# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-05-02 01:52:06

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

- [3DGS Surveys](#3dgs-surveys) (16 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (228 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (341 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (378 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (84 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (387 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (54 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (435 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (233 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (140 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (222 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, geometry, slam, 3d reconstruction, motion, survey, tracking, gaussian splatting  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: ar, 3d gaussian, survey, vr, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: ar, mapping, 3d gaussian, ray tracing, survey, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, efficient, localization, dynamic, slam, motion, survey, tracking, face, gaussian splatting  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, 3d gaussian, robotics, survey, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: ar, 3d gaussian, efficient, geometry, nerf, survey, gaussian splatting  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, dynamic, 3d reconstruction, compression, survey, compact, high-fidelity, gaussian splatting  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: ar, mapping, 3d gaussian, semantic, localization, robotics, slam, nerf, understanding, survey, gaussian splatting  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, efficient, semantic, localization, robotics, slam, survey, high-fidelity, gaussian splatting  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: ar, 3d gaussian, 4d, geometry, nerf, fast, motion, survey, gaussian splatting  

### Acceleration

*Showing the latest 50 out of 228 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Faster 3D Gaussian Splatting Convergence via Structure-Aware Densification](https://arxiv.org/abs/2604.28016v1)**  
  Authors: Linjie Lyu, Ayush Tewari, Jianchun Chen, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28016v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, fast, gaussian splatting  
- **[MesonGS++: Post-training Compression of 3D Gaussian Splatting with Hyperparameter Searching](https://arxiv.org/abs/2604.26799v1)**  
  Authors: Shuzhao Xie, Junchen Ge, Weixiang Zhang, Jiahang Liu, Chen Tang, Yunpeng Bai, Shijia Ge, Jingyan Jiang, Yuzhi Huang, Fengnian Yang, Cong Zhang, Xiaoyi Fan, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26799v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, compression, real-time rendering  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images](https://arxiv.org/abs/2604.21182v1)**  
  Authors: Yuki Fujimura, Takahiro Kushida, Kazuya Kitano, Takuya Funatomi, Yasuhiro Mukaigawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21182v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, gaussian splatting, lighting, real-time rendering  
- **[GSCompleter: A Distillation-Free Plugin for Metric-Aware 3D Gaussian Splatting Completion in Seconds](https://arxiv.org/abs/2604.20155v1)**  
  Authors: Ao Gao, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20155v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting, real-time rendering  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: ar, deformation, 3d gaussian, efficient, geometry, dynamic, gaussian splatting, motion, efficient rendering, face, human, high-fidelity, real-time rendering  
- **[Neural Gabor Splatting: Enhanced Gaussian Splatting with Neural Gabor for High-frequency Surface Reconstruction](https://arxiv.org/abs/2604.15941v1)**  
  Authors: Haato Watanabe, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15941v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, nerf, gaussian splatting, fast, lightweight, face, real-time rendering  
- **[CLOTH-HUGS: Cloth Aware Human Gaussian Splatting](https://arxiv.org/abs/2604.15875v1)**  
  Authors: Sadia Mubashshira, Nazanin Amini, Kevin Desai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15875v1.pdf)  
  Keywords: ar, deformation, neural rendering, body, dynamic, gaussian splatting, human, real-time rendering  
- **[Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography](https://arxiv.org/abs/2604.15862v1)**  
  Authors: Yijia Guo, Wenkai Huang, Tong Hu, Gaolei Li, Yang Li, Yuxin Hong, Liwen Hu, Xitong Ling, Jianhua Li, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15862v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, 4d, efficient, dynamic, 3d reconstruction, fast, gaussian splatting  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[GSDrive: Reinforcing Driving Policies by Multi-mode Trajectory Probing with 3D Gaussian Splatting Environment](https://arxiv.org/abs/2604.28111v1)**  
  Authors: Ziang Guo, Min Chen, Xuefeng Zhang, Yixiao Zhou, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28111v1.pdf)  
  Keywords: ar, autonomous driving, 3d gaussian, gaussian splatting  
- **[Faster 3D Gaussian Splatting Convergence via Structure-Aware Densification](https://arxiv.org/abs/2604.28016v1)**  
  Authors: Linjie Lyu, Ayush Tewari, Jianchun Chen, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28016v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, fast, gaussian splatting  
- **[Fake3DGS: A Benchmark for 3D Manipulation Detection in Neural Rendering](https://arxiv.org/abs/2604.27590v1)**  
  Authors: Davide Di Nucci, Riccardo Catalini, Guido Borghi, Roberto Vezzani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27590v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, geometry, 3d reconstruction, gaussian splatting  
- **[Residual Gaussian Splatting for Ultra Sparse-View CBCT Reconstruction](https://arxiv.org/abs/2604.27552v1)**  
  Authors: Jian Lin, Jiancheng Fang, Shaoyu Wang, Changan Lai, Yikun Zhang, Yang Chen, Qiegen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27552v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, sparse-view, efficient, gaussian splatting  
- **[Softmax-GS: Generalized Gaussians Learning When to Blend or Bound](https://arxiv.org/abs/2604.27437v1)**  
  Authors: Chen Ziwen, Peng Wang, Hao Tan, Zexiang Xu, Li Fuxin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27437v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting  
- **[Color-Encoded Illumination for High-Speed Volumetric Scene Reconstruction](https://arxiv.org/abs/2604.26920v1)**  
  Authors: David Novikov, Eilon Vaknin, Narek Tumanyan, Mark Sheinin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26920v1.pdf)  
  Keywords: ar, illumination, dynamic, motion, gaussian splatting  
- **[MesonGS++: Post-training Compression of 3D Gaussian Splatting with Hyperparameter Searching](https://arxiv.org/abs/2604.26799v1)**  
  Authors: Shuzhao Xie, Junchen Ge, Weixiang Zhang, Jiahang Liu, Chen Tang, Yunpeng Bai, Shijia Ge, Jingyan Jiang, Yuzhi Huang, Fengnian Yang, Cong Zhang, Xiaoyi Fan, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26799v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, compression, real-time rendering  
- **[Semantic Foam: Unifying Spatial and Semantic Scene Decomposition](https://arxiv.org/abs/2604.26262v1)**  
  Authors: Amr Sharafeldin, Shrisudhan Govindarajan, Thomas Walker, Aryan Mikaeili, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26262v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](http://semanticfoam.github.io/)  
  Keywords: ar, 3d gaussian, segmentation, semantic, human, gaussian splatting  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: ar, outdoor, 3d gaussian, geometry, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 341 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Semantic Foam: Unifying Spatial and Semantic Scene Decomposition](https://arxiv.org/abs/2604.26262v1)**  
  Authors: Amr Sharafeldin, Shrisudhan Govindarajan, Thomas Walker, Aryan Mikaeili, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26262v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](http://semanticfoam.github.io/)  
  Keywords: ar, 3d gaussian, segmentation, semantic, human, gaussian splatting  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, semantic, body, localization, human, gaussian splatting  
- **[GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning](https://arxiv.org/abs/2604.25459v1)**  
  Authors: Yufei Jia, Heng Zhang, Ziheng Zhang, Junzhe Wu, Mingrui Yu, Zifan Wang, Dixuan Jiang, Zheng Li, Chenyu Cao, Zhuoyuan Yu, Xun Yang, Haizhou Ge, Yuchi Zhang, Jiayuan Zhang, Zhenbiao Huang, Tianle Liu, Shenyu Chen, Jiacheng Wang, Bin Xie, Xuran Yao, Xiwa Deng, Guangyu Wang, Jinzhi Zhang, Lei Hao, Zhixing Chen, Yuxiang Chen, Anqi Wang, Hongyun Tian, Yiyi Yan, Zhanxiang Cao, Yizhou Jiang, Hanyang Shao, Yue Li, Lu Shi, Bokui Chen, Wei Sui, Hanqing Cui, Yusen Qin, Ruqi Huang, Lei Han, Tiancai Wang, Guyue Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25459v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsplayground.github.io.)  
  Keywords: ar, 3d gaussian, efficient, head, motion, high-fidelity, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[Large-Scale Photogrammetric Documentation of St. John's Co-Cathedral: A Workflow for Cultural Heritage Preservation](https://arxiv.org/abs/2604.24316v1)**  
  Authors: Matthew Kenely, Mark Bugeja, Andre Grima, Peter Pullicino, Matthew Pullicino, Dylan Seychell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24316v1.pdf)  
  Keywords: 3d reconstruction, face, ar, gaussian splatting  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, sparse-view, few-shot, reflection, head, lightweight, gaussian splatting  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, robotics, dynamic, 3d reconstruction, lighting, motion, human, gaussian splatting  
- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, semantic, head, gaussian splatting  
- **[DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures](https://arxiv.org/abs/2604.21631v1)**  
  Authors: Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21631v1.pdf)  
  Keywords: ar, 3d gaussian, nerf, lightweight, face, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 378 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Color-Encoded Illumination for High-Speed Volumetric Scene Reconstruction](https://arxiv.org/abs/2604.26920v1)**  
  Authors: David Novikov, Eilon Vaknin, Narek Tumanyan, Mark Sheinin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26920v1.pdf)  
  Keywords: ar, illumination, dynamic, motion, gaussian splatting  
- **[GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning](https://arxiv.org/abs/2604.25459v1)**  
  Authors: Yufei Jia, Heng Zhang, Ziheng Zhang, Junzhe Wu, Mingrui Yu, Zifan Wang, Dixuan Jiang, Zheng Li, Chenyu Cao, Zhuoyuan Yu, Xun Yang, Haizhou Ge, Yuchi Zhang, Jiayuan Zhang, Zhenbiao Huang, Tianle Liu, Shenyu Chen, Jiacheng Wang, Bin Xie, Xuran Yao, Xiwa Deng, Guangyu Wang, Jinzhi Zhang, Lei Hao, Zhixing Chen, Yuxiang Chen, Anqi Wang, Hongyun Tian, Yiyi Yan, Zhanxiang Cao, Yizhou Jiang, Hanyang Shao, Yue Li, Lu Shi, Bokui Chen, Wei Sui, Hanqing Cui, Yusen Qin, Ruqi Huang, Lei Han, Tiancai Wang, Guyue Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25459v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsplayground.github.io.)  
  Keywords: ar, 3d gaussian, efficient, head, motion, high-fidelity, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, robotics, dynamic, 3d reconstruction, lighting, motion, human, gaussian splatting  
- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v2)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v2.pdf)  
  Keywords: ar, mapping, 3d gaussian, 4d, efficient, localization, dynamic, slam, motion, tracking, gaussian splatting  
- **[EvFlow-GS: Event Enhanced Motion Deblurring with Optical Flow for 3D Gaussian Splatting](https://arxiv.org/abs/2604.22183v1)**  
  Authors: Feiyu An, Yufei Deng, Zihui Zhang, Rong Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22183v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, motion, gaussian splatting  
- **[Gaussians on a Diet: High-Quality Memory-Bounded 3D Gaussian Splatting Training](https://arxiv.org/abs/2604.20046v2)**  
  Authors: Yangming Zhang, Jian Xu, Chaojian Li, Kunxiong Zhu, Wei Niu, Gagan Agrawal, Yang Katie Zhao, Jian Wang, Yingyan Celine Lin, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20046v2.pdf)  
  Keywords: ar, 3d gaussian, efficient, dynamic, gaussian splatting  
- **[An Object-Centered Data Acquisition Method for 3D Gaussian Splatting using Mobile Phones](https://arxiv.org/abs/2604.19216v1)**  
  Authors: Yuezhe Zhang, Luqian Bai, Mengting Yu, Lei Wei, Shuai Wan, Yifan Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19216v1.pdf)  
  Keywords: ar, 3d gaussian, motion, gaussian splatting  
- **[BALTIC: A Benchmark and Cross-Domain Strategy for 3D Reconstruction Across Air and Underwater Domains Under Varying Illumination](https://arxiv.org/abs/2604.19133v2)**  
  Authors: Michele Grimaldi, David Nakath, Oscar Pizarro, Jonatan Scharff Willners, Ignacio Carlucho, Yvan R. Petillot  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19133v2.pdf)  
  Keywords: ar, illumination, 3d gaussian, geometry, 3d reconstruction, lighting, motion, gaussian splatting  

### Few-shot

*Showing the latest 50 out of 84 papers*

- **[Residual Gaussian Splatting for Ultra Sparse-View CBCT Reconstruction](https://arxiv.org/abs/2604.27552v1)**  
  Authors: Jian Lin, Jiancheng Fang, Shaoyu Wang, Changan Lai, Yikun Zhang, Yang Chen, Qiegen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27552v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, sparse-view, efficient, gaussian splatting  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, semantic, body, localization, human, gaussian splatting  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, sparse-view, few-shot, reflection, head, lightweight, gaussian splatting  
- **[GSCompleter: A Distillation-Free Plugin for Metric-Aware 3D Gaussian Splatting Completion in Seconds](https://arxiv.org/abs/2604.20155v1)**  
  Authors: Ao Gao, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20155v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting, real-time rendering  
- **[FluSplat: Sparse-View 3D Editing without Test-Time Optimization](https://arxiv.org/abs/2604.20038v1)**  
  Authors: Haitao Huang, Shin-Fang Chng, Huangying Zhan, Qingan Yan, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20038v1.pdf)  
  Keywords: ar, sparse view, 3d gaussian, sparse-view, 3d reconstruction, gaussian splatting  
- **[ArtifactWorld: Scaling 3D Gaussian Splatting Artifact Restoration via Video Generation Models](https://arxiv.org/abs/2604.12251v1)**  
  Authors: Xinliang Wang, Yifeng Shi, Zhenyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12251v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, 3d reconstruction, gaussian splatting, high-fidelity, real-time rendering  
- **[Learning 3D Representations for Spatial Intelligence from Unposed Multi-View Images](https://arxiv.org/abs/2604.10573v1)**  
  Authors: Bo Zhou, Qiuxia Lai, Zeren Sun, Xiangbo Shu, Yazhou Yao, Wenguan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.10573v1.pdf)  
  Keywords: ar, sparse-view, semantic, geometry, head, understanding, gaussian splatting  
- **[SurfelSplat: Learning Efficient and Generalizable Gaussian Surfel Representations for Sparse-View Surface Reconstruction](https://arxiv.org/abs/2604.08370v1)**  
  Authors: Chensheng Dai, Shengjun Zhang, Min Chen, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.08370v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, geometry, face, gaussian splatting  
- **[DOC-GS: Dual-Domain Observation and Calibration for Reliable Sparse-View Gaussian Splatting](https://arxiv.org/abs/2604.06739v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06739v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting, understanding  
- **[PR-IQA: Partial-Reference Image Quality Assessment for Diffusion-Based Novel View Synthesis](https://arxiv.org/abs/2604.04576v2)**  
  Authors: Inseong Choi, Siwoo Lee, Seung-Hun Nam, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04576v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kakaomacao.github.io/pr-iqa-project-page/.)  
  Keywords: ar, 3d gaussian, sparse-view, 3d reconstruction, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 387 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Fake3DGS: A Benchmark for 3D Manipulation Detection in Neural Rendering](https://arxiv.org/abs/2604.27590v1)**  
  Authors: Davide Di Nucci, Riccardo Catalini, Guido Borghi, Roberto Vezzani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27590v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, geometry, 3d reconstruction, gaussian splatting  
- **[MesonGS++: Post-training Compression of 3D Gaussian Splatting with Hyperparameter Searching](https://arxiv.org/abs/2604.26799v1)**  
  Authors: Shuzhao Xie, Junchen Ge, Weixiang Zhang, Jiahang Liu, Chen Tang, Yunpeng Bai, Shijia Ge, Jingyan Jiang, Yuzhi Huang, Fengnian Yang, Cong Zhang, Xiaoyi Fan, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26799v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, compression, real-time rendering  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: ar, outdoor, 3d gaussian, geometry, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[Large-Scale Photogrammetric Documentation of St. John's Co-Cathedral: A Workflow for Cultural Heritage Preservation](https://arxiv.org/abs/2604.24316v1)**  
  Authors: Matthew Kenely, Mark Bugeja, Andre Grima, Peter Pullicino, Matthew Pullicino, Dylan Seychell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24316v1.pdf)  
  Keywords: 3d reconstruction, face, ar, gaussian splatting  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, robotics, dynamic, 3d reconstruction, lighting, motion, human, gaussian splatting  
- **[Spatiotemporal Degradation-Aware 3D Gaussian Splatting for Realistic Underwater Scene Reconstruction](https://arxiv.org/abs/2604.23551v1)**  
  Authors: Shaohua Liu, Ning Gao, Zuoya Gu, Hongkun Dou, Yue Deng, Hongjue Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23551v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, 3d reconstruction, gaussian splatting  
- **[EvFlow-GS: Event Enhanced Motion Deblurring with Optical Flow for 3D Gaussian Splatting](https://arxiv.org/abs/2604.22183v1)**  
  Authors: Feiyu An, Yufei Deng, Zihui Zhang, Rong Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22183v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, motion, gaussian splatting  
- **[PAGaS: Pixel-Aligned 1DoF Gaussian Splatting for Depth Refinement](https://arxiv.org/abs/2604.22129v1)**  
  Authors: David Recasens, Robert Maier, Aljaz Bozic, Stephane Grabli, Javier Civera, Tony Tung, Edmond Boyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22129v1.pdf)  
  Keywords: ar, efficient, geometry, 3d reconstruction, gaussian splatting  

### Large Scene

*Showing the latest 50 out of 54 papers*

- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: ar, outdoor, 3d gaussian, geometry, gaussian splatting  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: ar, outdoor, 3d gaussian, gaussian splatting  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: ar, outdoor, mapping, 3d gaussian, localization, slam, gaussian splatting  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: ar, 3d gaussian, segmentation, urban scene, semantic, geometry, understanding, compact, gaussian splatting  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: ar, 3d gaussian, semantic, large scene, gaussian splatting  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: ar, neural rendering, 4d, shadow, efficient, geometry, dynamic, understanding, motion, large scene, high-fidelity, gaussian splatting  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: ar, outdoor, efficient, localization, gaussian splatting  
- **[FilterGS: Traversal-Free Parallel Filtering and Adaptive Shrinking for Large-Scale LoD 3D Gaussian Splatting](https://arxiv.org/abs/2603.23891v1)**  
  Authors: Yixian Wang, Haolin Yu, Jiadong Tang, Yu Gao, Xihan Wang, Yufeng Yue, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23891v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, efficient, head, large scene, face, gaussian splatting  
- **[MAGICIAN: Efficient Long-Term Planning with Imagined Gaussians for Active Mapping](https://arxiv.org/abs/2603.22650v2)**  
  Authors: Shiyao Li, Antoine Guédon, Shizhe Chen, Vincent Lepetit  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.22650v2.pdf)  
  Keywords: ar, outdoor, mapping, 3d gaussian, efficient, fast, lighting, face, gaussian splatting  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: ar, outdoor, efficient, dynamic, slam, head, tracking, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 435 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Faster 3D Gaussian Splatting Convergence via Structure-Aware Densification](https://arxiv.org/abs/2604.28016v1)**  
  Authors: Linjie Lyu, Ayush Tewari, Jianchun Chen, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28016v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, fast, gaussian splatting  
- **[Residual Gaussian Splatting for Ultra Sparse-View CBCT Reconstruction](https://arxiv.org/abs/2604.27552v1)**  
  Authors: Jian Lin, Jiancheng Fang, Shaoyu Wang, Changan Lai, Yikun Zhang, Yang Chen, Qiegen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27552v1.pdf)  
  Keywords: ar, neural rendering, 3d gaussian, sparse-view, efficient, gaussian splatting  
- **[MesonGS++: Post-training Compression of 3D Gaussian Splatting with Hyperparameter Searching](https://arxiv.org/abs/2604.26799v1)**  
  Authors: Shuzhao Xie, Junchen Ge, Weixiang Zhang, Jiahang Liu, Chen Tang, Yunpeng Bai, Shijia Ge, Jingyan Jiang, Yuzhi Huang, Fengnian Yang, Cong Zhang, Xiaoyi Fan, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26799v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting, compression, real-time rendering  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, semantic, body, localization, human, gaussian splatting  
- **[GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning](https://arxiv.org/abs/2604.25459v1)**  
  Authors: Yufei Jia, Heng Zhang, Ziheng Zhang, Junzhe Wu, Mingrui Yu, Zifan Wang, Dixuan Jiang, Zheng Li, Chenyu Cao, Zhuoyuan Yu, Xun Yang, Haizhou Ge, Yuchi Zhang, Jiayuan Zhang, Zhenbiao Huang, Tianle Liu, Shenyu Chen, Jiacheng Wang, Bin Xie, Xuran Yao, Xiwa Deng, Guangyu Wang, Jinzhi Zhang, Lei Hao, Zhixing Chen, Yuxiang Chen, Anqi Wang, Hongyun Tian, Yiyi Yan, Zhanxiang Cao, Yizhou Jiang, Hanyang Shao, Yue Li, Lu Shi, Bokui Chen, Wei Sui, Hanqing Cui, Yusen Qin, Ruqi Huang, Lei Han, Tiancai Wang, Guyue Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25459v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsplayground.github.io.)  
  Keywords: ar, 3d gaussian, efficient, head, motion, high-fidelity, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, sparse-view, few-shot, reflection, head, lightweight, gaussian splatting  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, robotics, dynamic, 3d reconstruction, lighting, motion, human, gaussian splatting  
- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: ar, light transport, efficient, localization, gaussian splatting  

### Quality Enhancement

*Showing the latest 50 out of 233 papers*

- **[GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning](https://arxiv.org/abs/2604.25459v1)**  
  Authors: Yufei Jia, Heng Zhang, Ziheng Zhang, Junzhe Wu, Mingrui Yu, Zifan Wang, Dixuan Jiang, Zheng Li, Chenyu Cao, Zhuoyuan Yu, Xun Yang, Haizhou Ge, Yuchi Zhang, Jiayuan Zhang, Zhenbiao Huang, Tianle Liu, Shenyu Chen, Jiacheng Wang, Bin Xie, Xuran Yao, Xiwa Deng, Guangyu Wang, Jinzhi Zhang, Lei Hao, Zhixing Chen, Yuxiang Chen, Anqi Wang, Hongyun Tian, Yiyi Yan, Zhanxiang Cao, Yizhou Jiang, Hanyang Shao, Yue Li, Lu Shi, Bokui Chen, Wei Sui, Hanqing Cui, Yusen Qin, Ruqi Huang, Lei Han, Tiancai Wang, Guyue Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25459v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsplayground.github.io.)  
  Keywords: ar, 3d gaussian, efficient, head, motion, high-fidelity, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[You Only Gaussian Once: Controllable 3D Gaussian Splatting for Ultra-Densely Sampled Scenes](https://arxiv.org/abs/2604.21400v2)**  
  Authors: Jinrang Jia, Zhenjia Li, Yifeng Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21400v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jjrcn.github.io/yogo-project-home/)  
  Keywords: ar, neural rendering, 3d gaussian, high-fidelity, gaussian splatting  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: ar, deformation, 3d gaussian, efficient, geometry, dynamic, gaussian splatting, motion, efficient rendering, face, human, high-fidelity, real-time rendering  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: ar, 3d gaussian, motion, lighting, human, high-fidelity, gaussian splatting  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, understanding, lighting, high-fidelity, gaussian splatting  
- **[GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments](https://arxiv.org/abs/2604.12837v1)**  
  Authors: Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12837v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, semantic, localization, dynamic, slam, motion, high-fidelity, gaussian splatting  
- **[Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting](https://arxiv.org/abs/2604.12626v1)**  
  Authors: Ziyuan Xia, Jingyi Xu, Chong Cui, Yuanhong Yu, Jiazhao Zhang, Qingsong Yan, Tao Ni, Junbo Chen, Xiaowei Zhou, Hujun Bao, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12626v1.pdf)  
  Keywords: avatar, ar, 3d gaussian, dynamic, human, high-fidelity, gaussian splatting  
- **[PDF-GS: Progressive Distractor Filtering for Robust 3D Gaussian Splatting](https://arxiv.org/abs/2604.12580v2)**  
  Authors: Kangmin Seo, MinKyu Lee, Tae-Young Kim, ByeongCheol Lee, JoonSeoung An, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12580v2.pdf)  
  Keywords: ar, 3d gaussian, head, lightweight, high-fidelity, gaussian splatting  
- **[ArtifactWorld: Scaling 3D Gaussian Splatting Artifact Restoration via Video Generation Models](https://arxiv.org/abs/2604.12251v1)**  
  Authors: Xinliang Wang, Yifeng Shi, Zhenyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12251v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, 3d reconstruction, gaussian splatting, high-fidelity, real-time rendering  

### Ray Tracing

- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: ar, 3d gaussian, efficient, ray tracing, semantic, dynamic, robotics, lighting, tracking, gaussian splatting  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ar, ray tracing, reflection, face, gaussian splatting  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, efficient, ray tracing, semantic, localization, slam, tracking, face, gaussian splatting  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: ar, mapping, 3d gaussian, shadow, ray tracing, reflection, relightable, gaussian splatting  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: ar, 3d gaussian, efficient, ray tracing, geometry, nerf, gaussian splatting, fast, face, high-fidelity, real-time rendering  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: ar, mapping, 3d gaussian, ray tracing, survey, gaussian splatting  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, gaussian splatting, ray marching, high-fidelity, real-time rendering  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, robotics, geometry, fast, ray casting, gaussian splatting  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ar, efficient, ray tracing, reflection, geometry, fast, lightweight, face, gaussian splatting  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ar, illumination, efficient, ray tracing, reflection, relighting, global illumination, lighting, gaussian splatting  

### Relighting

*Showing the latest 50 out of 140 papers*

- **[Color-Encoded Illumination for High-Speed Volumetric Scene Reconstruction](https://arxiv.org/abs/2604.26920v1)**  
  Authors: David Novikov, Eilon Vaknin, Narek Tumanyan, Mark Sheinin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26920v1.pdf)  
  Keywords: ar, illumination, dynamic, motion, gaussian splatting  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, sparse-view, few-shot, reflection, head, lightweight, gaussian splatting  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: ar, 3d gaussian, 4d, efficient, robotics, dynamic, 3d reconstruction, lighting, motion, human, gaussian splatting  
- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: ar, light transport, efficient, localization, gaussian splatting  
- **[WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images](https://arxiv.org/abs/2604.21182v1)**  
  Authors: Yuki Fujimura, Takahiro Kushida, Kazuya Kitano, Takuya Funatomi, Yasuhiro Mukaigawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21182v1.pdf)  
  Keywords: ar, illumination, 3d gaussian, gaussian splatting, lighting, real-time rendering  
- **[BALTIC: A Benchmark and Cross-Domain Strategy for 3D Reconstruction Across Air and Underwater Domains Under Varying Illumination](https://arxiv.org/abs/2604.19133v2)**  
  Authors: Michele Grimaldi, David Nakath, Oscar Pizarro, Jonatan Scharff Willners, Ignacio Carlucho, Yvan R. Petillot  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19133v2.pdf)  
  Keywords: ar, illumination, 3d gaussian, geometry, 3d reconstruction, lighting, motion, gaussian splatting  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: ar, 3d gaussian, motion, lighting, human, high-fidelity, gaussian splatting  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, segmentation, efficient, semantic, lighting, relighting, gaussian splatting  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, understanding, lighting, high-fidelity, gaussian splatting  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: recognition, ar, mapping, localization, geometry, slam, lighting, gaussian splatting  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: ar, deformation, body, dynamic, geometry, localization, fast, motion, lightweight, gaussian splatting  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, semantic, body, localization, human, gaussian splatting  
- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: ar, light transport, efficient, localization, gaussian splatting  
- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v2)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v2.pdf)  
  Keywords: ar, mapping, 3d gaussian, 4d, efficient, localization, dynamic, slam, motion, tracking, gaussian splatting  
- **[OT-UVGS: Revisiting UV Mapping for Gaussian Splatting as a Capacity Allocation Problem](https://arxiv.org/abs/2604.19127v1)**  
  Authors: Byunghyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19127v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, nerf, compact, lightweight, gaussian splatting  
- **[GS-STVSR: Ultra-Efficient Continuous Spatio-Temporal Video Super-Resolution via 2D Gaussian Splatting](https://arxiv.org/abs/2604.18047v1)**  
  Authors: Mingyu Shi, Xin Di, Long Peng, Boxiang Cao, Anran Wu, Zhanfeng Feng, Jiaming Guo, Renjing Pei, Xueyang Fu, Yang Cao, Zhengjun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.18047v1.pdf)  
  Keywords: ar, mapping, efficient, motion, lightweight, gaussian splatting  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, segmentation, efficient, semantic, lighting, relighting, gaussian splatting  
- **[Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography](https://arxiv.org/abs/2604.15862v1)**  
  Authors: Yijia Guo, Wenkai Huang, Tong Hu, Gaolei Li, Yang Li, Yuxin Hong, Liwen Hu, Xitong Ling, Jianhua Li, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15862v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, 4d, efficient, dynamic, 3d reconstruction, fast, gaussian splatting  
- **[GaussianFlow SLAM: Monocular Gaussian Splatting SLAM Guided by GaussianFlow](https://arxiv.org/abs/2604.15612v1)**  
  Authors: Dong-Uk Seo, Jinwoo Jeon, Eungchang Mason Lee, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15612v1.pdf)  
  Keywords: ar, mapping, geometry, slam, tracking, motion, gaussian splatting  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: recognition, ar, mapping, localization, geometry, slam, lighting, gaussian splatting  

### Scene Understanding

*Showing the latest 50 out of 222 papers*

- **[Semantic Foam: Unifying Spatial and Semantic Scene Decomposition](https://arxiv.org/abs/2604.26262v1)**  
  Authors: Amr Sharafeldin, Shrisudhan Govindarajan, Thomas Walker, Aryan Mikaeili, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26262v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](http://semanticfoam.github.io/)  
  Keywords: ar, 3d gaussian, segmentation, semantic, human, gaussian splatting  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, efficient, semantic, body, localization, human, gaussian splatting  
- **[Generalizable 3D Gaussian Splatting enabled Semantic Coding for Real-Time Immersive Video Communications](https://arxiv.org/abs/2604.25330v1)**  
  Authors: Dingxi Yang, Wenqi Guo, Yue Liu, Jungong Han, Zhijin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25330v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, dynamic, 3d reconstruction, gaussian splatting, compression, lightweight, human, high-fidelity, real-time rendering  
- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, semantic, head, gaussian splatting  
- **[TransSplat: Unbalanced Semantic Transport for Language-Driven 3DGS Editing](https://arxiv.org/abs/2604.19571v2)**  
  Authors: Yanhui Chen, Jiahong Li, Jingchao Wang, Junyi Lin, Zixin Zeng, Yang Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19571v2.pdf)  
  Keywords: ar, 3d gaussian, semantic, vr, gaussian splatting  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: ar, mapping, 3d gaussian, segmentation, efficient, semantic, lighting, relighting, gaussian splatting  
- **[One-shot Compositional 3D Head Avatars with Deformable Hair](https://arxiv.org/abs/2604.14782v1)**  
  Authors: Yuan Sun, Xuan Wang, WeiLi Zhang, Wenxuan Zhang, Yu Guo, Fei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14782v1.pdf)  
  Keywords: avatar, ar, deformation, 3d gaussian, semantic, dynamic, geometry, head, motion, animation, face, gaussian splatting  
- **[NG-GS: NeRF-Guided 3D Gaussian Splatting Segmentation](https://arxiv.org/abs/2604.14706v1)**  
  Authors: Yi He, Tao Wang, Yi Jin, Congyan Lang, Yidong Li, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14706v1.pdf)  
  Keywords: ar, 3d gaussian, segmentation, efficient, nerf, lightweight, gaussian splatting  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: ar, 3d gaussian, efficient, understanding, lighting, high-fidelity, gaussian splatting  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: recognition, ar, mapping, localization, geometry, slam, lighting, gaussian splatting  



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