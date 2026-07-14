# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-07-14 01:27:27

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

- [3DGS Surveys](#3dgs-surveys) (10 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (224 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (328 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (372 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (414 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (42 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (415 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (248 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (29 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (139 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (158 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (229 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 4d, survey, ar, 3d gaussian, motion, autonomous driving, compact, recognition, 3d reconstruction, vr, medical, neural rendering, gaussian splatting  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: survey, ar, mapping, animation, geometry, gaussian splatting  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: survey, slam, ar, 3d gaussian, motion, tracking, efficient, 3d reconstruction, geometry, gaussian splatting  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, ar, 3d gaussian, vr, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: survey, ar, 3d gaussian, mapping, ray tracing, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, slam, ar, motion, 3d gaussian, dynamic, mapping, tracking, face, efficient, localization, gaussian splatting  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, survey, ar, 3d gaussian, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, ar, 3d gaussian, nerf, efficient, geometry, gaussian splatting  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, survey, high-fidelity, ar, 3d gaussian, dynamic, compact, 3d reconstruction, compression, efficient, gaussian splatting  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: robotics, survey, slam, ar, 3d gaussian, nerf, semantic, understanding, mapping, localization, gaussian splatting  

### Acceleration

*Showing the latest 50 out of 224 papers*

- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: 4d, ar, motion, nerf, dynamic, fast, deformation, face, gaussian splatting  
- **[NoDrift3R: Raymap-Guided Coupling for Drift-Robust Unposed Feed-Forward 3D Reconstruction](https://arxiv.org/abs/2607.07168v1)**  
  Authors: Xiangyu Sun, Liu Liu, Seungkwon Yang, Jingbing Han, Seungtae Nam, Zhizhong Su, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07168v1.pdf)  
  Keywords: ar, 3d gaussian, fast, 3d reconstruction, geometry, gaussian splatting  
- **[Real-Time LiDAR Gaussian Splatting SLAM](https://arxiv.org/abs/2607.04127v1)**  
  Authors: Seungjun Tak, Yewon Jeon, Jaeik Hwang, SukMin Hwang, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04127v1.pdf)  
  Keywords: slam, ar, mapping, tracking, fast, face, geometry, gaussian splatting  
- **[TemporalGS: Training-Free Plug-and-Play Acceleration for 3D Gaussian Splatting Rendering via Temporal Priors](https://arxiv.org/abs/2607.03390v1)**  
  Authors: Yuhongze Zhou, Zihao Yang, Xinxin Zuo, Juwei Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03390v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, dynamic, fast, acceleration, geometry, gaussian splatting  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: robotics, sparse-view, ar, motion, 3d gaussian, nerf, fast, vr, gaussian splatting  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v2)**  
  Authors: Cao Duy, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v2.pdf)  
  Keywords: ar, 3d gaussian, fast, efficient, face, geometry, compression  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, fast, 3d reconstruction, geometry, segmentation, gaussian splatting  
- **[Online Segment 3D Gaussians via Launching Virtual Drones](https://arxiv.org/abs/2607.01628v1)**  
  Authors: Liwei Liao, Rongjie Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01628v1.pdf)  
  Keywords: ar, 3d gaussian, real-time rendering, segmentation, gaussian splatting  
- **[FastBridge: Closing the Model-Based Realization Gap in Safety Filters on 3D Gaussian Splatting for Fast Quadrotor Flight](https://arxiv.org/abs/2607.01200v1)**  
  Authors: Tscholl Dario, Nakka Yashwanth Kumar, Gunter Brian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01200v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, fast, acceleration, geometry, gaussian splatting  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: high-fidelity, ar, motion, 3d gaussian, real-time rendering, avatar, deformation, animation, head, gaussian splatting  

### Applications

*Showing the latest 50 out of 994 papers*

- **[DP-Splat: Bayesian Nonparametric Complexity Control for Gaussian Splatting](https://arxiv.org/abs/2607.10912v1)**  
  Authors: Aqi Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10912v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, semantic, geometry, neural rendering, gaussian splatting  
- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: 4d, ar, motion, nerf, dynamic, fast, deformation, face, gaussian splatting  
- **[CoSAG: Compact Semantic Anchor Gaussians via Training-Free Rate-Distortion Coding](https://arxiv.org/abs/2607.10237v1)**  
  Authors: Yuang Jia, Jinlong Wang, Junhong Lin, Ruiting Dai, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10237v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, understanding, compact, gaussian splatting  
- **[SyncSpace: Layout-Conditioned 3D Gaussian Splatting for Space Reskinning in Mixed Reality](https://arxiv.org/abs/2607.10050v1)**  
  Authors: Qinchuan Zhang, Weibo Xu, Yunge Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10050v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting  
- **[AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration](https://arxiv.org/abs/2607.09260v1)**  
  Authors: Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.09260v1.pdf)  
  Keywords: slam, ar, 3d gaussian, semantic, recognition, vr, gaussian splatting  
- **[SplatCtrl: Perception-Action Coupling via Gaussian Scene Representations and Reactive Robot Control](https://arxiv.org/abs/2607.08948v1)**  
  Authors: Siddarth Jain, Ho Jin Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08948v1.pdf)  
  Keywords: ar, motion, 3d gaussian, dynamic, human, face, efficient, gaussian splatting  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: ar, 3d gaussian, outdoor, geometry, gaussian splatting  
- **[StereoSplat+: Feed-Forward Stereo Gaussian Splatting with Diffusion-Assisted Progressive Inference](https://arxiv.org/abs/2607.08808v1)**  
  Authors: Zihua Liu, Masatoshi Okutomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08808v1.pdf)  
  Keywords: robotics, ar, 3d gaussian, geometry, gaussian splatting  
- **[Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery](https://arxiv.org/abs/2607.08408v1)**  
  Authors: Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08408v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://track2map.github.io/.)  
  Keywords: slam, ar, motion, 3d gaussian, mapping, deformation, 3d reconstruction, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 328 papers*

- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, dynamic, face, efficient, head, gaussian splatting  
- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: 4d, ar, motion, nerf, dynamic, fast, deformation, face, gaussian splatting  
- **[SplatCtrl: Perception-Action Coupling via Gaussian Scene Representations and Reactive Robot Control](https://arxiv.org/abs/2607.08948v1)**  
  Authors: Siddarth Jain, Ho Jin Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08948v1.pdf)  
  Keywords: ar, motion, 3d gaussian, dynamic, human, face, efficient, gaussian splatting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: ar, 3d gaussian, illumination, efficient, 3d reconstruction, face, geometry, gaussian splatting  
- **[GUSH3R: Everyone Everywhere All at Once as Gaussians](https://arxiv.org/abs/2607.05243v1)**  
  Authors: Keito Abe, Kaede Shiohara, Takashi Otonari, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05243v1.pdf)  
  Keywords: ar, 3d gaussian, motion, dynamic, human, efficient, 3d reconstruction, geometry, gaussian splatting  
- **[Real-Time LiDAR Gaussian Splatting SLAM](https://arxiv.org/abs/2607.04127v1)**  
  Authors: Seungjun Tak, Yewon Jeon, Jaeik Hwang, SukMin Hwang, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04127v1.pdf)  
  Keywords: slam, ar, mapping, tracking, fast, face, geometry, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: ar, 3d gaussian, large scene, efficient, sparse view, face, geometry, gaussian splatting  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, 3d reconstruction, sparse view, face, geometry, gaussian splatting  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v2)**  
  Authors: Cao Duy, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v2.pdf)  
  Keywords: ar, 3d gaussian, fast, efficient, face, geometry, compression  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: high-fidelity, ar, motion, 3d gaussian, real-time rendering, avatar, deformation, animation, head, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 372 papers*

- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, dynamic, face, efficient, head, gaussian splatting  
- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: 4d, ar, motion, nerf, dynamic, fast, deformation, face, gaussian splatting  
- **[SplatCtrl: Perception-Action Coupling via Gaussian Scene Representations and Reactive Robot Control](https://arxiv.org/abs/2607.08948v1)**  
  Authors: Siddarth Jain, Ho Jin Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08948v1.pdf)  
  Keywords: ar, motion, 3d gaussian, dynamic, human, face, efficient, gaussian splatting  
- **[Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery](https://arxiv.org/abs/2607.08408v1)**  
  Authors: Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08408v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://track2map.github.io/.)  
  Keywords: slam, ar, motion, 3d gaussian, mapping, deformation, 3d reconstruction, gaussian splatting  
- **[On the Design of Mixture-of-Experts for Dynamic Gaussian Splatting](https://arxiv.org/abs/2607.08250v1)**  
  Authors: In-Hwan Jin, Hyeongju Mun, Joonsoo Kim, Kugjin Yun, Kyeongbo Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08250v1.pdf)  
  Keywords: ar, motion, 3d gaussian, dynamic, deformation, gaussian splatting  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: lighting, ar, mapping, dynamic, gaussian splatting  
- **[GUSH3R: Everyone Everywhere All at Once as Gaussians](https://arxiv.org/abs/2607.05243v1)**  
  Authors: Keito Abe, Kaede Shiohara, Takashi Otonari, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05243v1.pdf)  
  Keywords: ar, 3d gaussian, motion, dynamic, human, efficient, 3d reconstruction, geometry, gaussian splatting  
- **[DeGenseGS: Geometrically and Semantically Decoupled Surgical Scene Understanding in 4D Gaussian Splatting](https://arxiv.org/abs/2607.04761v1)**  
  Authors: Yimo Wang, Bin Kang, Shuojue Yang, Yueming Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04761v1.pdf)  
  Keywords: 4d, ar, semantic, dynamic, understanding, deformation, segmentation, gaussian splatting  
- **[PRISM3D: Probabilistic Refinement and Robust Initialization for Physically Consistent Scene Modeling under Extreme Motion Blur](https://arxiv.org/abs/2607.03855v1)**  
  Authors: Gopi Raju Matta, Reddypalli Trisha, Vemunuri Divya Madhuri, Kaushik Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03855v1.pdf)  
  Keywords: ar, motion, 3d gaussian, tracking, geometry, gaussian splatting  
- **[TemporalGS: Training-Free Plug-and-Play Acceleration for 3D Gaussian Splatting Rendering via Temporal Priors](https://arxiv.org/abs/2607.03390v1)**  
  Authors: Yuhongze Zhou, Zihao Yang, Xinxin Zuo, Juwei Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03390v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, dynamic, fast, acceleration, geometry, gaussian splatting  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, semantic, geometry, neural rendering, gaussian splatting  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: ar, 3d gaussian, sparse view, geometry, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: ar, 3d gaussian, large scene, efficient, sparse view, face, geometry, gaussian splatting  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, 3d reconstruction, sparse view, face, geometry, gaussian splatting  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: robotics, sparse-view, ar, motion, 3d gaussian, nerf, fast, vr, gaussian splatting  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: sparse-view, ar, 3d gaussian, nerf, dynamic, real-time rendering, lightweight, fast, efficient, neural rendering, gaussian splatting  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: sparse-view, ar, nerf, real-time rendering, geometry, gaussian splatting  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v2)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: sparse-view, ar, 3d gaussian, nerf, dynamic, face, geometry, head, gaussian splatting  
- **[Occlusion-Robust Multi-Object Decoupling for Physics-Based Robotic Interaction](https://arxiv.org/abs/2606.29303v2)**  
  Authors: Xin Dong, Lihan Zhang, Tianru Dai, Wenfeng Deng, Yansong Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29303v2.pdf)  
  Keywords: sparse-view, ar, 3d gaussian, dynamic, 3d reconstruction, geometry, segmentation, gaussian splatting  
- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: sparse-view, ar, 3d gaussian, deformation, efficient, geometry, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 414 papers*

- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, semantic, geometry, neural rendering, gaussian splatting  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: ar, 3d gaussian, outdoor, geometry, gaussian splatting  
- **[StereoSplat+: Feed-Forward Stereo Gaussian Splatting with Diffusion-Assisted Progressive Inference](https://arxiv.org/abs/2607.08808v1)**  
  Authors: Zihua Liu, Masatoshi Okutomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08808v1.pdf)  
  Keywords: robotics, ar, 3d gaussian, geometry, gaussian splatting  
- **[Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery](https://arxiv.org/abs/2607.08408v1)**  
  Authors: Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08408v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://track2map.github.io/.)  
  Keywords: slam, ar, motion, 3d gaussian, mapping, deformation, 3d reconstruction, gaussian splatting  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: robotics, slam, ar, mapping, illumination, 3d reconstruction, geometry, gaussian splatting  
- **[NoDrift3R: Raymap-Guided Coupling for Drift-Robust Unposed Feed-Forward 3D Reconstruction](https://arxiv.org/abs/2607.07168v1)**  
  Authors: Xiangyu Sun, Liu Liu, Seungkwon Yang, Jingbing Han, Seungtae Nam, Zhizhong Su, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07168v1.pdf)  
  Keywords: ar, 3d gaussian, fast, 3d reconstruction, geometry, gaussian splatting  
- **[EscFOA: Enhancing Spatial Learning for Visually Impaired Learners via Generative Spatial Audio in 360-Degree Educational Environments](https://arxiv.org/abs/2607.07015v1)**  
  Authors: Ziyu Luo, Xiaowei Dai, Siying Zhu, Xiaoming Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07015v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, geometry, gaussian splatting  
- **[GaussFusion: Towards Multimodal 3D Gaussian Pretraining](https://arxiv.org/abs/2607.05906v1)**  
  Authors: Zhixuan You, Jihua Zhu, Yiding Sun, Zihao Guo, Haozhe Cheng, Dongxu Zhang, Lin Chen, Hainan Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05906v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, geometry, gaussian splatting  
- **[SSA-3DGS: Unsupervised Removal of Screen-Space Artifacts for 3D Gaussian Splatting](https://arxiv.org/abs/2607.05598v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05598v1.pdf)  
  Keywords: ar, geometry, 3d gaussian, gaussian splatting  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: ar, 3d gaussian, sparse view, geometry, gaussian splatting  

### Large Scene

- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: ar, 3d gaussian, outdoor, geometry, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: ar, 3d gaussian, large scene, efficient, sparse view, face, geometry, gaussian splatting  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: ar, 3d gaussian, deformation, outdoor, human  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: ar, 3d gaussian, mapping, outdoor, geometry, gaussian splatting  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: high-fidelity, slam, ar, motion, 3d gaussian, dynamic, mapping, tracking, outdoor, efficient, head, gaussian splatting  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: slam, ar, 3d gaussian, mapping, autonomous driving, efficient, face, outdoor, geometry, localization, gaussian splatting  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, large scene, urban scene, dynamic, fast, efficient, geometry, gaussian splatting  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: ar, 3d gaussian, fast, efficient, outdoor, geometry, gaussian splatting  
- **[MoonSplat: Monocular Online Gaussian Splatting with Sim(3) Global Optimization](https://arxiv.org/abs/2606.17935v1)**  
  Authors: Guo Pu, Yixuan Han, Haofeng Li, Yao Zhang, Hui Zhou, Zhouhui Lian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17935v1.pdf)  
  Keywords: robotics, ar, 3d gaussian, real-time rendering, tracking, vr, 3d reconstruction, outdoor, efficient, gaussian splatting  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, nerf, outdoor, efficient, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 415 papers*

- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, dynamic, face, efficient, head, gaussian splatting  
- **[CoSAG: Compact Semantic Anchor Gaussians via Training-Free Rate-Distortion Coding](https://arxiv.org/abs/2607.10237v1)**  
  Authors: Yuang Jia, Jinlong Wang, Junhong Lin, Ruiting Dai, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10237v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, understanding, compact, gaussian splatting  
- **[SplatCtrl: Perception-Action Coupling via Gaussian Scene Representations and Reactive Robot Control](https://arxiv.org/abs/2607.08948v1)**  
  Authors: Siddarth Jain, Ho Jin Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08948v1.pdf)  
  Keywords: ar, motion, 3d gaussian, dynamic, human, face, efficient, gaussian splatting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: ar, 3d gaussian, illumination, efficient, 3d reconstruction, face, geometry, gaussian splatting  
- **[GUSH3R: Everyone Everywhere All at Once as Gaussians](https://arxiv.org/abs/2607.05243v1)**  
  Authors: Keito Abe, Kaede Shiohara, Takashi Otonari, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05243v1.pdf)  
  Keywords: ar, 3d gaussian, motion, dynamic, human, efficient, 3d reconstruction, geometry, gaussian splatting  
- **[Semantic-Guided Progressive Object Removal with Gaussian Splatting](https://arxiv.org/abs/2607.04144v1)**  
  Authors: Xianliang Huang, Chen Xiao, Yuanxiang Ni, Guanming Liu, Mingkai Liu, Dikai Fan, Xiao Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04144v1.pdf)  
  Keywords: robotics, high-fidelity, ar, semantic, vr, efficient, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: ar, 3d gaussian, large scene, efficient, sparse view, face, geometry, gaussian splatting  
- **[Provable Pruning for Efficient 3D Gaussian Splatting via Coresets](https://arxiv.org/abs/2607.02721v1)**  
  Authors: Waseem Mousa, Alaa Maalouf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02721v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, efficient, compression  
- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: ar, nerf, lightweight, geometry, segmentation, gaussian splatting  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v2)**  
  Authors: Cao Duy, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v2.pdf)  
  Keywords: ar, 3d gaussian, fast, efficient, face, geometry, compression  

### Quality Enhancement

*Showing the latest 50 out of 248 papers*

- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, semantic, geometry, neural rendering, gaussian splatting  
- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, dynamic, face, efficient, head, gaussian splatting  
- **[EscFOA: Enhancing Spatial Learning for Visually Impaired Learners via Generative Spatial Audio in 360-Degree Educational Environments](https://arxiv.org/abs/2607.07015v1)**  
  Authors: Ziyu Luo, Xiaowei Dai, Siying Zhu, Xiaoming Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07015v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, geometry, gaussian splatting  
- **[RoboSnap: One-Shot Real-to-Sim Scene Generation for Generalizable Robot Learning and Evaluation](https://arxiv.org/abs/2607.06699v1)**  
  Authors: Shujie Zhang, Jingkun Yi, Weipeng Zhong, Zirui Zhou, Yangkun Zhu, Hanqing Wang, Xudong Xu, Weinan Zhang, Chunhua Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06699v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, gaussian splatting  
- **[Semantic-Guided Progressive Object Removal with Gaussian Splatting](https://arxiv.org/abs/2607.04144v1)**  
  Authors: Xianliang Huang, Chen Xiao, Yuanxiang Ni, Guanming Liu, Mingkai Liu, Dikai Fan, Xiao Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04144v1.pdf)  
  Keywords: robotics, high-fidelity, ar, semantic, vr, efficient, gaussian splatting  
- **[MACRO: Training-free Multi-plane Attention for Closeup Render Optimization](https://arxiv.org/abs/2607.03875v1)**  
  Authors: Nitzan Hodos, Roy Amoyal, Lior Fritz, Ianir Ideses, Sagie Benaim, Netalee Efrat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03875v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nitzanhod.github.io/MACRO)  
  Keywords: high-fidelity, ar, 3d gaussian, gaussian splatting  
- **[SharpSplat: Edge-Regularized 3D Gaussian Splatting for High Fidelity Urban Building Reconstruction from UAV images](https://arxiv.org/abs/2607.03872v1)**  
  Authors: Porus Vaid, Shivam Chopra, Vaibhav Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03872v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, semantic, gaussian splatting  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, 3d reconstruction, sparse view, face, geometry, gaussian splatting  
- **[TemporalGS: Training-Free Plug-and-Play Acceleration for 3D Gaussian Splatting Rendering via Temporal Priors](https://arxiv.org/abs/2607.03390v1)**  
  Authors: Yuhongze Zhou, Zihao Yang, Xinxin Zuo, Juwei Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03390v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, dynamic, fast, acceleration, geometry, gaussian splatting  
- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v2)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v2.pdf)  
  Keywords: high-fidelity, slam, ar, motion, 3d gaussian, semantic, dynamic, mapping, tracking, localization, gaussian splatting  

### Ray Tracing

- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: ar, 3d gaussian, fast, ray tracing, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: ar, 3d gaussian, reflection, path tracing, real-time rendering, fast, efficient, ray tracing, geometry, gaussian splatting  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: global illumination, ar, 3d gaussian, illumination, efficient, 3d reconstruction, geometry, gaussian splatting  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: global illumination, high-fidelity, ar, illumination, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: ar, 3d gaussian, reflection, semantic, efficient, ray tracing, geometry, segmentation, gaussian splatting  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: global illumination, ar, 3d gaussian, illumination, fast, face, shadow, gaussian splatting  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, 3d gaussian, ray casting, gaussian splatting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, ray tracing, geometry, gaussian splatting  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: lighting, robotics, ar, 3d gaussian, semantic, dynamic, tracking, ray tracing, efficient, gaussian splatting  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ar, reflection, face, ray tracing, gaussian splatting  

### Relighting

*Showing the latest 50 out of 139 papers*

- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: robotics, slam, ar, mapping, illumination, 3d reconstruction, geometry, gaussian splatting  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: lighting, ar, mapping, dynamic, gaussian splatting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: ar, 3d gaussian, illumination, efficient, 3d reconstruction, face, geometry, gaussian splatting  
- **[Intrinsic decomposition and editing of 3D Gaussian splats](https://arxiv.org/abs/2606.31637v1)**  
  Authors: Alexandre Lanvin, Jeffrey Hu, Simon Lucas, Adrien Bousseau, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31637v1.pdf)  
  Keywords: lighting, ar, 3d gaussian, face, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: ar, 3d gaussian, reflection, path tracing, real-time rendering, fast, efficient, ray tracing, geometry, gaussian splatting  
- **[Monte Carlo Energy Aggregation for Mobile 3D Gaussian Splatting](https://arxiv.org/abs/2606.30017v1)**  
  Authors: Xiaobiao Du, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30017v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/flux-gs-project/}{https://xiaobiaodu.github.io/flux-gs-project/}}.)  
  Keywords: lighting, high-fidelity, ar, 3d gaussian, compact, gaussian splatting, head, compression  
- **[Shell-Supervised Gaussian Splatting for Urban Real-to-Sim Reconstruction](https://arxiv.org/abs/2606.30014v1)**  
  Authors: Yuan Yang, Peijun Lu, Fangzhou Lu, Sai Fan, Siqi Yan, Chenyuan Zhang, Haobo Liang, Yichen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30014v1.pdf)  
  Keywords: ar, reflection, lightweight, 3d reconstruction, face, geometry, gaussian splatting  
- **[DR-GS: Physically-Based Deformable and Relightable 2D Gaussians](https://arxiv.org/abs/2606.29379v1)**  
  Authors: Jiaxin Li, Tong Wu, Yi Wei, Tailin Wu, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29379v1.pdf)  
  Keywords: efficient rendering, lighting, ar, relighting, reflection, dynamic, illumination, relightable, deformation, efficient, face, vr, geometry, gaussian splatting  
- **[RAGA: Real Time Ray Traced Gaussian Shadow Casting for 3DGS Avatar-Scene Interaction](https://arxiv.org/abs/2606.29329v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Peter Wonka, Bing Zhou, Gerard Pons-Moll  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29329v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://miraymen.github.io/raga/.)  
  Keywords: ar, 3d gaussian, avatar, deformation, shadow, gaussian splatting  
- **[RefGlass-GS: A UAV-Enabled Fusion Framework for Photorealistic, Semantic and Interactive Digitization of Reflective Glass Facades via Gaussian Splatting](https://arxiv.org/abs/2606.28826v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Boyu Wang, Zhaolun Liang, Ang Li, Jeff Chak Fu Chan, Mingzhu Wang, Jack C. P. Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28826v1.pdf)  
  Keywords: ar, reflection, semantic, segmentation, gaussian splatting  

### SLAM

*Showing the latest 50 out of 158 papers*

- **[AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration](https://arxiv.org/abs/2607.09260v1)**  
  Authors: Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.09260v1.pdf)  
  Keywords: slam, ar, 3d gaussian, semantic, recognition, vr, gaussian splatting  
- **[Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery](https://arxiv.org/abs/2607.08408v1)**  
  Authors: Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08408v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://track2map.github.io/.)  
  Keywords: slam, ar, motion, 3d gaussian, mapping, deformation, 3d reconstruction, gaussian splatting  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: robotics, slam, ar, mapping, illumination, 3d reconstruction, geometry, gaussian splatting  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: lighting, ar, mapping, dynamic, gaussian splatting  
- **[Real-Time LiDAR Gaussian Splatting SLAM](https://arxiv.org/abs/2607.04127v1)**  
  Authors: Seungjun Tak, Yewon Jeon, Jaeik Hwang, SukMin Hwang, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04127v1.pdf)  
  Keywords: slam, ar, mapping, tracking, fast, face, geometry, gaussian splatting  
- **[PRISM3D: Probabilistic Refinement and Robust Initialization for Physically Consistent Scene Modeling under Extreme Motion Blur](https://arxiv.org/abs/2607.03855v1)**  
  Authors: Gopi Raju Matta, Reddypalli Trisha, Vemunuri Divya Madhuri, Kaushik Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03855v1.pdf)  
  Keywords: ar, motion, 3d gaussian, tracking, geometry, gaussian splatting  
- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v2)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v2.pdf)  
  Keywords: high-fidelity, slam, ar, motion, 3d gaussian, semantic, dynamic, mapping, tracking, localization, gaussian splatting  
- **[AnchorSplat: Fast and Structure Consistent Detail Synthesis for Gaussian Splatting](https://arxiv.org/abs/2607.01290v2)**  
  Authors: Dexu Zhu, Jiangnan Shao, Xiaofeng Wang, Junxian Duan, Jie Cao, Zheng Zhu, Huaibo Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01290v2.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, mapping, fast, head, gaussian splatting  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: ar, 3d gaussian, mapping, outdoor, geometry, gaussian splatting  
- **[VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes](https://arxiv.org/abs/2606.30645v1)**  
  Authors: Yen-Jen Wang, Jiaman Li, Sirui Chen, Takara E. Truong, Pei Xu, Pieter Abbeel, Rocky Duan, Koushil Sreenath, Angjoo Kanazawa, Carmelo Sferrazza, Guanya Shi, Karen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30645v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vision-language-kinematics.github.io/)  
  Keywords: ar, motion, 3d gaussian, mapping, body, human, gaussian splatting  

### Scene Understanding

*Showing the latest 50 out of 229 papers*

- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: sparse-view, high-fidelity, ar, 3d gaussian, semantic, geometry, neural rendering, gaussian splatting  
- **[CoSAG: Compact Semantic Anchor Gaussians via Training-Free Rate-Distortion Coding](https://arxiv.org/abs/2607.10237v1)**  
  Authors: Yuang Jia, Jinlong Wang, Junhong Lin, Ruiting Dai, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10237v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, understanding, compact, gaussian splatting  
- **[AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration](https://arxiv.org/abs/2607.09260v1)**  
  Authors: Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.09260v1.pdf)  
  Keywords: slam, ar, 3d gaussian, semantic, recognition, vr, gaussian splatting  
- **[GaussFusion: Towards Multimodal 3D Gaussian Pretraining](https://arxiv.org/abs/2607.05906v1)**  
  Authors: Zhixuan You, Jihua Zhu, Yiding Sun, Zihao Guo, Haozhe Cheng, Dongxu Zhang, Lin Chen, Hainan Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05906v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, geometry, gaussian splatting  
- **[DeGenseGS: Geometrically and Semantically Decoupled Surgical Scene Understanding in 4D Gaussian Splatting](https://arxiv.org/abs/2607.04761v1)**  
  Authors: Yimo Wang, Bin Kang, Shuojue Yang, Yueming Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04761v1.pdf)  
  Keywords: 4d, ar, semantic, dynamic, understanding, deformation, segmentation, gaussian splatting  
- **[Semantic-Guided Progressive Object Removal with Gaussian Splatting](https://arxiv.org/abs/2607.04144v1)**  
  Authors: Xianliang Huang, Chen Xiao, Yuanxiang Ni, Guanming Liu, Mingkai Liu, Dikai Fan, Xiao Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04144v1.pdf)  
  Keywords: robotics, high-fidelity, ar, semantic, vr, efficient, gaussian splatting  
- **[SharpSplat: Edge-Regularized 3D Gaussian Splatting for High Fidelity Urban Building Reconstruction from UAV images](https://arxiv.org/abs/2607.03872v1)**  
  Authors: Porus Vaid, Shivam Chopra, Vaibhav Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03872v1.pdf)  
  Keywords: high-fidelity, ar, 3d gaussian, semantic, gaussian splatting  
- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: ar, nerf, lightweight, geometry, segmentation, gaussian splatting  
- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v2)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v2.pdf)  
  Keywords: high-fidelity, slam, ar, motion, 3d gaussian, semantic, dynamic, mapping, tracking, localization, gaussian splatting  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, fast, 3d reconstruction, geometry, segmentation, gaussian splatting  



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