# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-08-08 00:54:02

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

- [3DGS Surveys](#3dgs-surveys) (9 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (228 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (321 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (377 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (415 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (427 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (244 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (31 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (137 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (156 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (228 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: 4d, vr, autonomous driving, 3d reconstruction, ar, survey, gaussian splatting, 3d gaussian, compact, recognition, motion, neural rendering, medical  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: animation, mapping, survey, gaussian splatting, geometry, ar  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d reconstruction, slam, tracking, survey, gaussian splatting, efficient, geometry, 3d gaussian, motion, ar  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: vr, survey, gaussian splatting, 3d gaussian, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: mapping, ray tracing, survey, gaussian splatting, 3d gaussian, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: mapping, slam, tracking, ar, dynamic, survey, gaussian splatting, efficient, 3d gaussian, face, motion, localization  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, gaussian splatting, robotics, 3d gaussian, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, gaussian splatting, efficient, geometry, 3d gaussian, nerf, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, compression, high-fidelity, 3d reconstruction, survey, gaussian splatting, dynamic, efficient, 3d gaussian, compact, ar  

### Acceleration

*Showing the latest 50 out of 228 papers*

- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, motion, real-time rendering, ar  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compression, vr, high-fidelity, mapping, efficient, gaussian splatting, 3d gaussian, compact, real-time rendering, fast, ar  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: avatar, dynamic, gaussian splatting, geometry, 3d gaussian, head, motion, fast, ar  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: 4d, 3d reconstruction, dynamic, gaussian splatting, efficient, motion, real-time rendering, fast, ar  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: efficient rendering, animation, high-fidelity, efficient, gaussian splatting, geometry, 3d gaussian, face, motion, ar  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: 4d, sparse-view, dynamic, gaussian splatting, efficient, geometry, real-time rendering, ar  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: efficient rendering, mapping, 3d reconstruction, slam, tracking, efficient, gaussian splatting, ar, robotics, 3d gaussian, localization  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: tracking, avatar, human, gaussian splatting, 3d gaussian, head, fast, ar  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: compression, semantic, mapping, gaussian splatting, geometry, 3d gaussian, compact, lightweight, real-time rendering, fast, ar  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: high quality, dynamic, gaussian splatting, 3d gaussian, lightweight, real-time rendering, ar  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, motion, real-time rendering, ar  
- **[GSBF: Gaussian Splatting for Environment-Aware Beamforming](https://arxiv.org/abs/2608.05896v1)**  
  Authors: Yijie Bian, Wei Guo, Zixin Wang, Shenghui Song, Jun Zhang, Khaled B. Letaief  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05896v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, head, ar  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: compression, gaussian splatting, geometry, 3d gaussian, compact, face, ar  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compression, vr, high-fidelity, mapping, efficient, gaussian splatting, 3d gaussian, compact, real-time rendering, fast, ar  
- **[CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer](https://arxiv.org/abs/2608.05482v1)**  
  Authors: Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05482v1.pdf)  
  Keywords: semantic, segmentation, gaussian splatting, face, ar  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: few-shot, 3d reconstruction, ar, gaussian splatting, geometry, 3d gaussian, compact, localization  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[UniWorld-View: Large-Baseline View Synthesis via Video Diffusion Models](https://arxiv.org/abs/2608.04701v1)**  
  Authors: Haiyang Zhou, Wangbo Yu, Chaoran Feng, Xunyu Zhou, Yonghong Tian, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04701v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, 3d gaussian, motion, nerf, ar  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: avatar, dynamic, gaussian splatting, geometry, 3d gaussian, head, motion, fast, ar  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: 4d, compression, high-fidelity, dynamic, gaussian splatting, compact, lightweight, motion, ar  

### Avatar Generation

*Showing the latest 50 out of 321 papers*

- **[GSBF: Gaussian Splatting for Environment-Aware Beamforming](https://arxiv.org/abs/2608.05896v1)**  
  Authors: Yijie Bian, Wei Guo, Zixin Wang, Shenghui Song, Jun Zhang, Khaled B. Letaief  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05896v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, head, ar  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: compression, gaussian splatting, geometry, 3d gaussian, compact, face, ar  
- **[CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer](https://arxiv.org/abs/2608.05482v1)**  
  Authors: Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05482v1.pdf)  
  Keywords: semantic, segmentation, gaussian splatting, face, ar  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: avatar, dynamic, gaussian splatting, geometry, 3d gaussian, head, motion, fast, ar  
- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, gaussian splatting, geometry, 3d gaussian, face, ar  
- **[InfiniSplat: Implicit Gaussian Decoding for Large-Baseline Monocular View Synthesis](https://arxiv.org/abs/2608.02437v2)**  
  Authors: Jiawei Wang, Hao Yu, Yongzhen Hu, Xinyi Yang, Tao Ni, Xin Zhan, Junbo Chen, Xiaowei Zhou, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02437v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/InfiniSplat.)  
  Keywords: gaussian splatting, geometry, 3d gaussian, face, ar  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: efficient rendering, animation, high-fidelity, efficient, gaussian splatting, geometry, 3d gaussian, face, motion, ar  
- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: 3d reconstruction, ar, gaussian splatting, geometry, head, localization, motion  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: sparse-view, gaussian splatting, geometry, 3d gaussian, face, ar  

### Dynamic Scene

*Showing the latest 50 out of 377 papers*

- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, motion, real-time rendering, ar  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[UniWorld-View: Large-Baseline View Synthesis via Video Diffusion Models](https://arxiv.org/abs/2608.04701v1)**  
  Authors: Haiyang Zhou, Wangbo Yu, Chaoran Feng, Xunyu Zhou, Yonghong Tian, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04701v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, 3d gaussian, motion, nerf, ar  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: avatar, dynamic, gaussian splatting, geometry, 3d gaussian, head, motion, fast, ar  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: 4d, compression, high-fidelity, dynamic, gaussian splatting, compact, lightweight, motion, ar  
- **[Super-Gaussian: Interactive Scene Editing for 3D Gaussian Splatting and NLI-Based Volume Visualization in Virtual Reality](https://arxiv.org/abs/2608.04475v1)**  
  Authors: Suemin Jeon, Kaiyuan Tang, Chaoli Wang, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04475v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smin0136.github.io/super-gaussian-project/)  
  Keywords: vr, semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, motion, medical  
- **[UniqueSplat: View-conditioned 3D Gaussian Splatting for Generalizable 3D Reconstruction](https://arxiv.org/abs/2608.02145v1)**  
  Authors: Haixu Song, Xiaoke Yang, Shengjun Zhang, Jiwen Lu, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02145v1.pdf)  
  Keywords: 3d reconstruction, dynamic, gaussian splatting, 3d gaussian, ar  
- **[ASTRA: Asynchronous Spatio-Temporal Reconstruction via Trajectory Alignment](https://arxiv.org/abs/2608.02006v2)**  
  Authors: Junyu Zhu, Hao Zhu, Xinzhuo Zhang, Hongdong Li, Zhan Ma, Xun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02006v2.pdf)  
  Keywords: dynamic, gaussian splatting, geometry, motion, deformation, ar  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, high-fidelity, gaussian splatting, 3d gaussian, motion, understanding, ar  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: 4d, 3d reconstruction, dynamic, gaussian splatting, efficient, motion, real-time rendering, fast, ar  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: few-shot, 3d reconstruction, ar, gaussian splatting, geometry, 3d gaussian, compact, localization  
- **[CLEAR: Conflict-aware Learning via Evidence-guided Adaptive Routing for Unified Sparse-View 3D Gaussian Super-Resolution](https://arxiv.org/abs/2608.02206v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02206v1.pdf)  
  Keywords: 3d gaussian, sparse-view, ar, gaussian splatting  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: 4d, sparse-view, dynamic, gaussian splatting, efficient, geometry, real-time rendering, ar  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: sparse-view, gaussian splatting, geometry, 3d gaussian, face, ar  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: ar, gaussian splatting, sparse view, geometry, 3d gaussian, motion, localization, illumination  
- **[Posterior Variance Is a Constraint Map, Not an Error Map: Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v2)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v2.pdf)  
  Keywords: ar, fast, sparse-view, gaussian splatting  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, high-fidelity, sparse-view, gaussian splatting, geometry, 3d gaussian, neural rendering, ar  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: gaussian splatting, sparse view, geometry, 3d gaussian, ar  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: large scene, efficient, gaussian splatting, sparse view, geometry, 3d gaussian, face, ar  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: high-fidelity, 3d reconstruction, sparse-view, gaussian splatting, sparse view, geometry, 3d gaussian, face, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 415 papers*

- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, motion, real-time rendering, ar  
- **[GSBF: Gaussian Splatting for Environment-Aware Beamforming](https://arxiv.org/abs/2608.05896v1)**  
  Authors: Yijie Bian, Wei Guo, Zixin Wang, Shenghui Song, Jun Zhang, Khaled B. Letaief  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05896v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, head, ar  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: compression, gaussian splatting, geometry, 3d gaussian, compact, face, ar  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: few-shot, 3d reconstruction, ar, gaussian splatting, geometry, 3d gaussian, compact, localization  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: avatar, dynamic, gaussian splatting, geometry, 3d gaussian, head, motion, fast, ar  
- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, gaussian splatting, geometry, 3d gaussian, face, ar  
- **[InfiniSplat: Implicit Gaussian Decoding for Large-Baseline Monocular View Synthesis](https://arxiv.org/abs/2608.02437v2)**  
  Authors: Jiawei Wang, Hao Yu, Yongzhen Hu, Xinyi Yang, Tao Ni, Xin Zhan, Junbo Chen, Xiaowei Zhou, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02437v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/InfiniSplat.)  
  Keywords: gaussian splatting, geometry, 3d gaussian, face, ar  
- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, geometry, 3d gaussian, nerf, ar, illumination  
- **[GSRAIN: Physically Calibrated High-/Low-Frequency Rainfall Synthesis for 3D Gaussian Driving Scenes](https://arxiv.org/abs/2608.02177v1)**  
  Authors: Fanyu Wang, Longgao Zhang, Junyi Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02177v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, geometry, 3d gaussian, ar  

### Large Scene

- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, understanding, outdoor, localization  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: mapping, slam, tracking, ar, gaussian splatting, geometry, 3d gaussian, lightweight, outdoor, localization  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: animation, dynamic, gaussian splatting, 3d gaussian, motion, outdoor, deformation, ar  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: large scene, slam, efficient, gaussian splatting, 3d gaussian, recognition, motion, real-time rendering, fast, ar  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: mapping, slam, tracking, gaussian splatting, geometry, 3d gaussian, outdoor, ar  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, outdoor, ar  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: large scene, efficient, gaussian splatting, sparse view, geometry, 3d gaussian, face, ar  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, 3d gaussian, outdoor, deformation, ar  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: mapping, gaussian splatting, geometry, 3d gaussian, outdoor, ar  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: high-fidelity, mapping, slam, tracking, dynamic, gaussian splatting, efficient, 3d gaussian, head, motion, outdoor, ar  

### Model Compression

*Showing the latest 50 out of 427 papers*

- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: compression, gaussian splatting, geometry, 3d gaussian, compact, face, ar  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compression, vr, high-fidelity, mapping, efficient, gaussian splatting, 3d gaussian, compact, real-time rendering, fast, ar  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: few-shot, 3d reconstruction, ar, gaussian splatting, geometry, 3d gaussian, compact, localization  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: 4d, compression, high-fidelity, dynamic, gaussian splatting, compact, lightweight, motion, ar  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, understanding, outdoor, localization  
- **[Super-Gaussian: Interactive Scene Editing for 3D Gaussian Splatting and NLI-Based Volume Visualization in Virtual Reality](https://arxiv.org/abs/2608.04475v1)**  
  Authors: Suemin Jeon, Kaiyuan Tang, Chaoli Wang, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04475v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smin0136.github.io/super-gaussian-project/)  
  Keywords: vr, semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, motion, medical  
- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, gaussian splatting, geometry, 3d gaussian, face, ar  
- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v3)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v3.pdf)  
  Keywords: efficient, ar, mapping  
- **[DeGS: A Scalable 3DGS Architecture via Decoupled Workload Parsing and Reorganization](https://arxiv.org/abs/2608.02099v1)**  
  Authors: Minnan Pei, Gang Li, Zeyu Zhu, Siting Wang, Junwen Si, Zhuoran Song, Yu Feng, Fangxin Liu, Xiaoyao Liang, Jian Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02099v1.pdf)  
  Keywords: efficient, gaussian splatting, 3d gaussian, compact, ar  

### Quality Enhancement

*Showing the latest 50 out of 244 papers*

- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compression, vr, high-fidelity, mapping, efficient, gaussian splatting, 3d gaussian, compact, real-time rendering, fast, ar  
- **[UniWorld-View: Large-Baseline View Synthesis via Video Diffusion Models](https://arxiv.org/abs/2608.04701v1)**  
  Authors: Haiyang Zhou, Wangbo Yu, Chaoran Feng, Xunyu Zhou, Yonghong Tian, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04701v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, 3d gaussian, motion, nerf, ar  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: 4d, compression, high-fidelity, dynamic, gaussian splatting, compact, lightweight, motion, ar  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, high-fidelity, gaussian splatting, 3d gaussian, motion, understanding, ar  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, lighting, high-fidelity, autonomous driving, dynamic, gaussian splatting, 3d gaussian, relighting, neural rendering, ar, illumination  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: efficient rendering, animation, high-fidelity, efficient, gaussian splatting, geometry, 3d gaussian, face, motion, ar  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: high-fidelity, 3d reconstruction, efficient, gaussian splatting, geometry, 3d gaussian, understanding, ar  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: high quality, dynamic, gaussian splatting, 3d gaussian, lightweight, real-time rendering, ar  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, reflection, face, ar, illumination  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: compression, high-fidelity, gaussian splatting, geometry, 3d gaussian, compact, lightweight, ar  

### Ray Tracing

- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: lighting, ray tracing, reflection, efficient, gaussian splatting, relighting, face, ar, illumination  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: high-fidelity, ray tracing, reflection, dynamic, gaussian splatting, human, geometry, 3d gaussian, face, motion, ar  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: ray tracing, gaussian splatting, 3d gaussian, fast, ar  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: ray tracing, ar, reflection, efficient, gaussian splatting, geometry, 3d gaussian, real-time rendering, fast, path tracing  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d reconstruction, efficient, global illumination, gaussian splatting, geometry, 3d gaussian, ar, illumination  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, global illumination, gaussian splatting, ar, illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: semantic, segmentation, ray tracing, reflection, efficient, gaussian splatting, geometry, 3d gaussian, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: global illumination, gaussian splatting, 3d gaussian, face, fast, shadow, ar, illumination  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: 3d gaussian, ray casting, gaussian splatting, ar  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: high-fidelity, ray tracing, gaussian splatting, geometry, 3d gaussian, ar  

### Relighting

*Showing the latest 50 out of 137 papers*

- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, geometry, 3d gaussian, nerf, ar, illumination  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, lighting, high-fidelity, autonomous driving, dynamic, gaussian splatting, 3d gaussian, relighting, neural rendering, ar, illumination  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, reflection, face, ar, illumination  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: efficient, gaussian splatting, 3d gaussian, ar, illumination  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: lighting, ray tracing, reflection, efficient, gaussian splatting, relighting, face, ar, illumination  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: ar, gaussian splatting, sparse view, geometry, 3d gaussian, motion, localization, illumination  
- **[ECoNGS: Efficient Compressive Neural Gaussian Splats for Volume Visualization](https://arxiv.org/abs/2607.18466v1)**  
  Authors: Kaiyuan Tang, Chaoli Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18466v1.pdf)  
  Keywords: vr, lighting, efficient, dynamic, gaussian splatting, compact, lightweight, ar  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: lighting, mapping, 3d reconstruction, gaussian splatting, geometry, 3d gaussian, robotics, motion, fast, ar, illumination  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: high-fidelity, ray tracing, reflection, dynamic, gaussian splatting, human, geometry, 3d gaussian, face, motion, ar  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: mapping, 3d reconstruction, slam, gaussian splatting, geometry, robotics, ar, illumination  

### SLAM

*Showing the latest 50 out of 156 papers*

- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compression, vr, high-fidelity, mapping, efficient, gaussian splatting, 3d gaussian, compact, real-time rendering, fast, ar  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: few-shot, 3d reconstruction, ar, gaussian splatting, geometry, 3d gaussian, compact, localization  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, understanding, outdoor, localization  
- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v3)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v3.pdf)  
  Keywords: efficient, ar, mapping  
- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: 3d reconstruction, ar, gaussian splatting, geometry, head, localization, motion  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: efficient rendering, mapping, 3d reconstruction, slam, tracking, efficient, gaussian splatting, ar, robotics, 3d gaussian, localization  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: tracking, avatar, human, gaussian splatting, 3d gaussian, head, fast, ar  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: compression, semantic, mapping, gaussian splatting, geometry, 3d gaussian, compact, lightweight, real-time rendering, fast, ar  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: acceleration, tracking, avatar, dynamic, gaussian splatting, human, 3d gaussian, face, head, motion, deformation, ar  

### Scene Understanding

*Showing the latest 50 out of 228 papers*

- **[CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer](https://arxiv.org/abs/2608.05482v1)**  
  Authors: Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05482v1.pdf)  
  Keywords: semantic, segmentation, gaussian splatting, face, ar  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: segmentation, tracking, dynamic, gaussian splatting, efficient, human, geometry, 3d gaussian, motion, nerf, ar  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, understanding, outdoor, localization  
- **[Super-Gaussian: Interactive Scene Editing for 3D Gaussian Splatting and NLI-Based Volume Visualization in Virtual Reality](https://arxiv.org/abs/2608.04475v1)**  
  Authors: Suemin Jeon, Kaiyuan Tang, Chaoli Wang, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04475v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smin0136.github.io/super-gaussian-project/)  
  Keywords: vr, semantic, segmentation, ar, efficient, gaussian splatting, 3d gaussian, motion, medical  
- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, gaussian splatting, geometry, 3d gaussian, face, ar  
- **[Standalone DINOv3 for Training-Free Open-Vocabulary Semantic Segmentation in Remote Sensing](https://arxiv.org/abs/2608.03023v1)**  
  Authors: Changhao Zhao, Haoxiang Li, Yuke Li, Hai Liu, LingLin Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03023v1.pdf)  
  Keywords: segmentation, ar, semantic, gaussian splatting  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, high-fidelity, gaussian splatting, 3d gaussian, motion, understanding, ar  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, lighting, high-fidelity, autonomous driving, dynamic, gaussian splatting, 3d gaussian, relighting, neural rendering, ar, illumination  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: high-fidelity, 3d reconstruction, efficient, gaussian splatting, geometry, 3d gaussian, understanding, ar  
- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: gaussian splatting, geometry, 3d gaussian, compact, motion, understanding, ar  



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