# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-07-06 02:10:37

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
- [Acceleration](#acceleration) (227 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (331 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (377 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (80 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (406 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (421 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (250 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (29 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (138 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (153 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (227 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: compact, 3d reconstruction, 3d gaussian, autonomous driving, 4d, ar, survey, vr, gaussian splatting, neural rendering, motion, recognition, medical  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: mapping, ar, survey, gaussian splatting, animation, geometry  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, tracking, ar, survey, gaussian splatting, motion, slam, geometry, efficient  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, ar, survey, vr, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: 3d gaussian, mapping, ar, survey, ray tracing, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, face, survey, ar, gaussian splatting, motion, slam, localization, efficient  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, survey, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: 3d gaussian, ar, survey, gaussian splatting, nerf, geometry, efficient  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: compact, 3d reconstruction, 3d gaussian, dynamic, 4d, ar, survey, gaussian splatting, compression, high-fidelity, efficient  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: robotics, 3d gaussian, mapping, ar, survey, gaussian splatting, slam, nerf, localization, understanding, semantic  

### Acceleration

*Showing the latest 50 out of 227 papers*

- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v1)**  
  Authors: Duy Cao, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, compression, geometry, efficient  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, fast, gaussian splatting, segmentation, semantic, geometry  
- **[Online Segment 3D Gaussians via Launching Virtual Drones](https://arxiv.org/abs/2607.01628v1)**  
  Authors: Liwei Liao, Rongjie Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01628v1.pdf)  
  Keywords: real-time rendering, 3d gaussian, ar, gaussian splatting, segmentation  
- **[FastBridge: Closing the Model-Based Realization Gap in Safety Filters on 3D Gaussian Splatting for Fast Quadrotor Flight](https://arxiv.org/abs/2607.01200v1)**  
  Authors: Tscholl Dario, Nakka Yashwanth Kumar, Gunter Brian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01200v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, acceleration, fast, gaussian splatting, geometry  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: real-time rendering, 3d gaussian, ar, deformation, avatar, gaussian splatting, motion, animation, head, high-fidelity  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: real-time rendering, efficient, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, neural rendering, nerf, sparse-view  
- **[AnchorSplat: Fast and Structure Consistent Detail Synthesis for Gaussian Splatting](https://arxiv.org/abs/2607.01290v1)**  
  Authors: Dexu Zhu, Jiangnan Shao, Xiaofeng Wang, Junxian Duan, Jie Cao, Zheng Zhu, Huaibo Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01290v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, fast, gaussian splatting, head, high-fidelity  
- **[GADA: Geometry-Aware Deformable Aggregation for Image-Based Gaussian Splatting](https://arxiv.org/abs/2607.00595v2)**  
  Authors: Siwoo Lim, Sunjae Yoon, Gwanhyeong Koo, Chang D. Yoo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00595v2.pdf)  
  Keywords: ar, fast, geometry, gaussian splatting  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, nerf, geometry, sparse-view  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  

### Applications

*Showing the latest 50 out of 995 papers*

- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, nerf, segmentation, geometry  
- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v1)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, localization, semantic, high-fidelity  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v1)**  
  Authors: Duy Cao, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, compression, geometry, efficient  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, fast, gaussian splatting, segmentation, semantic, geometry  
- **[Structure-Aware Gaussian Splatting for Large-Scale Scene Reconstruction](https://arxiv.org/abs/2607.01698v1)**  
  Authors: Weiyi Xue, Fan Lu, Chi Zhang, Tianhang Wang, Sanqing Qu, Zehan Zheng, Boyuan Zheng, Junqiao Zhao, Guang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01698v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting  
- **[Online Segment 3D Gaussians via Launching Virtual Drones](https://arxiv.org/abs/2607.01628v1)**  
  Authors: Liwei Liao, Rongjie Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01628v1.pdf)  
  Keywords: real-time rendering, 3d gaussian, ar, gaussian splatting, segmentation  
- **[MVFusion-GS: Motion-Variance Guided Temporal Attention for High-Quality Dynamic Gaussian Splatting](https://arxiv.org/abs/2607.01578v1)**  
  Authors: Jianwei Hu, Tingxuan Huang, Hengyu Zhou, Ningna Wang, Xiaohu Guo Jinshan Lai, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01578v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, deformation, gaussian splatting, motion  
- **[Mind the Gap: Standard 3DGS Evaluation Primarily Measures Near-Trajectory Interpolation](https://arxiv.org/abs/2607.01556v1)**  
  Authors: Gaoxiang Jia, Vikram Appia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01556v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, nerf, geometry  
- **[FastBridge: Closing the Model-Based Realization Gap in Safety Filters on 3D Gaussian Splatting for Fast Quadrotor Flight](https://arxiv.org/abs/2607.01200v1)**  
  Authors: Tscholl Dario, Nakka Yashwanth Kumar, Gunter Brian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01200v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, acceleration, fast, gaussian splatting, geometry  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: real-time rendering, 3d gaussian, ar, deformation, avatar, gaussian splatting, motion, animation, head, high-fidelity  

### Avatar Generation

*Showing the latest 50 out of 331 papers*

- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v1)**  
  Authors: Duy Cao, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, compression, geometry, efficient  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: real-time rendering, 3d gaussian, ar, deformation, avatar, gaussian splatting, motion, animation, head, high-fidelity  
- **[AnchorSplat: Fast and Structure Consistent Detail Synthesis for Gaussian Splatting](https://arxiv.org/abs/2607.01290v1)**  
  Authors: Dexu Zhu, Jiangnan Shao, Xiaofeng Wang, Junxian Duan, Jie Cao, Zheng Zhu, Huaibo Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01290v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, fast, gaussian splatting, head, high-fidelity  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, 3d gaussian, ar, deformation, outdoor  
- **[Practical High-Fidelity Novel-View Synthesis of Mounted Lepidoptera](https://arxiv.org/abs/2606.31679v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31679v1.pdf)  
  Keywords: 3d gaussian, body, face, ar, gaussian splatting, segmentation, high-fidelity  
- **[Intrinsic decomposition and editing of 3D Gaussian splats](https://arxiv.org/abs/2606.31637v1)**  
  Authors: Alexandre Lanvin, Jeffrey Hu, Simon Lucas, Adrien Bousseau, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31637v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, lighting  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  
- **[VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes](https://arxiv.org/abs/2606.30645v1)**  
  Authors: Yen-Jen Wang, Jiaman Li, Sirui Chen, Takara E. Truong, Pei Xu, Pieter Abbeel, Rocky Duan, Koushil Sreenath, Angjoo Kanazawa, Carmelo Sferrazza, Guanya Shi, Karen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30645v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vision-language-kinematics.github.io/)  
  Keywords: human, 3d gaussian, body, mapping, ar, gaussian splatting, motion  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v1)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: 3d gaussian, dynamic, face, ar, gaussian splatting, head, nerf, geometry, sparse-view  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, head, outdoor, high-fidelity, efficient  

### Dynamic Scene

*Showing the latest 50 out of 377 papers*

- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v1)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, localization, semantic, high-fidelity  
- **[MVFusion-GS: Motion-Variance Guided Temporal Attention for High-Quality Dynamic Gaussian Splatting](https://arxiv.org/abs/2607.01578v1)**  
  Authors: Jianwei Hu, Tingxuan Huang, Hengyu Zhou, Ningna Wang, Xiaohu Guo Jinshan Lai, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01578v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, deformation, gaussian splatting, motion  
- **[FastBridge: Closing the Model-Based Realization Gap in Safety Filters on 3D Gaussian Splatting for Fast Quadrotor Flight](https://arxiv.org/abs/2607.01200v1)**  
  Authors: Tscholl Dario, Nakka Yashwanth Kumar, Gunter Brian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01200v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, acceleration, fast, gaussian splatting, geometry  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: real-time rendering, 3d gaussian, ar, deformation, avatar, gaussian splatting, motion, animation, head, high-fidelity  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: real-time rendering, efficient, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, neural rendering, nerf, sparse-view  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, 3d gaussian, ar, deformation, outdoor  
- **[Progressive Pose-Guided 4D Animal Reconstruction from Monocular Video](https://arxiv.org/abs/2607.00157v1)**  
  Authors: Siyuan Li, Weiying Chen, Yilin Wang, Xinxin Zuo, Xingyu Li, Li Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00157v1.pdf)  
  Keywords: 3d gaussian, 4d, ar, deformation, gaussian splatting, high-fidelity  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  
- **[VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes](https://arxiv.org/abs/2606.30645v1)**  
  Authors: Yen-Jen Wang, Jiaman Li, Sirui Chen, Takara E. Truong, Pei Xu, Pieter Abbeel, Rocky Duan, Koushil Sreenath, Angjoo Kanazawa, Carmelo Sferrazza, Guanya Shi, Karen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30645v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vision-language-kinematics.github.io/)  
  Keywords: human, 3d gaussian, body, mapping, ar, gaussian splatting, motion  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v1)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: 3d gaussian, dynamic, face, ar, gaussian splatting, head, nerf, geometry, sparse-view  

### Few-shot

*Showing the latest 50 out of 80 papers*

- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: real-time rendering, efficient, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, neural rendering, nerf, sparse-view  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, nerf, geometry, sparse-view  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v1)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: 3d gaussian, dynamic, face, ar, gaussian splatting, head, nerf, geometry, sparse-view  
- **[Occlusion-Robust Multi-Object Decoupling for Physics-Based Robotic Interaction](https://arxiv.org/abs/2606.29303v2)**  
  Authors: Xin Dong, Lihan Zhang, Tianru Dai, Wenfeng Deng, Yansong Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29303v2.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, dynamic, ar, gaussian splatting, segmentation, geometry, sparse-view  
- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, deformation, gaussian splatting, geometry, sparse-view  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: robotics, 3d gaussian, lightweight, mapping, ar, fast, high-fidelity, gaussian splatting, slam, head, geometry, sparse-view  
- **[From Uncertainty to Stability and Fidelity: Guiding Sparse-View 3D Gaussian Splatting with Fisher Information](https://arxiv.org/abs/2606.20842v1)**  
  Authors: Junbao Zhou, Qingshan Xu, Yuan Zhou, Xiaolong Shen, Beier Zhu, Kesen Zhao, Yiming Zeng, Chen Bai, Cheng Lu, Hanwang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20842v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting  
- **[VisDom: Sparse Novel View Synthesis with Visible Domain Constraint](https://arxiv.org/abs/2606.20531v1)**  
  Authors: Mariia Gladkova*, Tarun Yenamandra*, Edmond Boyer, Robert Maier, Tony Tung, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20531v1.pdf)  
  Keywords: ar, gaussian splatting, nerf, geometry, sparse-view  
- **[FlowObject: Flow Steering for Bridging Generative Priors and Reconstruction Fidelity](https://arxiv.org/abs/2606.19019v1)**  
  Authors: Yuchen Rao, Xuqian Ren, Yinyu Nie, Sayan Deb Sarkar, Biao Zhang, Vincent Lepetit, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19019v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, face, ar, gaussian splatting, geometry, sparse-view  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting, nerf, outdoor, high-fidelity, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 406 papers*

- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, nerf, segmentation, geometry  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v1)**  
  Authors: Duy Cao, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, compression, geometry, efficient  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, fast, gaussian splatting, segmentation, semantic, geometry  
- **[Structure-Aware Gaussian Splatting for Large-Scale Scene Reconstruction](https://arxiv.org/abs/2607.01698v1)**  
  Authors: Weiyi Xue, Fan Lu, Chi Zhang, Tianhang Wang, Sanqing Qu, Zehan Zheng, Boyuan Zheng, Junqiao Zhao, Guang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01698v1.pdf)  
  Keywords: ar, 3d gaussian, geometry, gaussian splatting  
- **[Mind the Gap: Standard 3DGS Evaluation Primarily Measures Near-Trajectory Interpolation](https://arxiv.org/abs/2607.01556v1)**  
  Authors: Gaoxiang Jia, Vikram Appia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01556v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, nerf, geometry  
- **[FastBridge: Closing the Model-Based Realization Gap in Safety Filters on 3D Gaussian Splatting for Fast Quadrotor Flight](https://arxiv.org/abs/2607.01200v1)**  
  Authors: Tscholl Dario, Nakka Yashwanth Kumar, Gunter Brian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01200v1.pdf)  
  Keywords: 3d gaussian, dynamic, ar, acceleration, fast, gaussian splatting, geometry  
- **[GADA: Geometry-Aware Deformable Aggregation for Image-Based Gaussian Splatting](https://arxiv.org/abs/2607.00595v2)**  
  Authors: Siwoo Lim, Sunjae Yoon, Gwanhyeong Koo, Chang D. Yoo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00595v2.pdf)  
  Keywords: ar, fast, geometry, gaussian splatting  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: real-time rendering, ar, gaussian splatting, nerf, geometry, sparse-view  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: real-time rendering, 3d gaussian, ar, fast, ray tracing, path tracing, gaussian splatting, reflection, geometry, efficient  

### Large Scene

- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, 3d gaussian, ar, deformation, outdoor  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, gaussian splatting, outdoor, geometry  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, head, outdoor, high-fidelity, efficient  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: 3d gaussian, autonomous driving, mapping, face, ar, gaussian splatting, slam, outdoor, localization, geometry, efficient  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: efficient, 3d gaussian, dynamic, ar, fast, high-fidelity, gaussian splatting, large scene, geometry, urban scene  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: 3d gaussian, ar, fast, gaussian splatting, outdoor, geometry, efficient  
- **[MoonSplat: Monocular Online Gaussian Splatting with Sim(3) Global Optimization](https://arxiv.org/abs/2606.17935v1)**  
  Authors: Guo Pu, Yixuan Han, Haofeng Li, Yao Zhang, Hui Zhou, Zhouhui Lian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17935v1.pdf)  
  Keywords: real-time rendering, robotics, 3d reconstruction, 3d gaussian, tracking, ar, vr, gaussian splatting, outdoor, efficient  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting, nerf, outdoor, high-fidelity, sparse-view  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: 3d reconstruction, face, ar, high-fidelity, gaussian splatting, nerf, large scene, geometry, urban scene  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, geometry, urban scene  

### Model Compression

*Showing the latest 50 out of 421 papers*

- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, nerf, segmentation, geometry  
- **[PixGS: Pixel-Space Diffusion for Direct 3D Gaussian Splat Generation](https://arxiv.org/abs/2607.01803v1)**  
  Authors: Duy Cao, Phong Nguyen-Ha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01803v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, compression, geometry, efficient  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: real-time rendering, efficient, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, neural rendering, nerf, sparse-view  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: real-time rendering, 3d gaussian, ar, fast, ray tracing, path tracing, gaussian splatting, reflection, geometry, efficient  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, head, outdoor, high-fidelity, efficient  
- **[FastPano3D: Feed-Forward Indoor Panoramic 3D Reconstruction from a Single Image](https://arxiv.org/abs/2606.30352v1)**  
  Authors: Jianqiang Li, Liumei Zhang, Wenjia Guo, Tianlong Feng, Yongzhi Liao, Di Lu, Hanchi Ren, Jingjing Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30352v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, lightweight, ar, fast, gaussian splatting, nerf, high-fidelity, efficient  
- **[Monte Carlo Energy Aggregation for Mobile 3D Gaussian Splatting](https://arxiv.org/abs/2606.30017v1)**  
  Authors: Xiaobiao Du, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30017v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/flux-gs-project/}{https://xiaobiaodu.github.io/flux-gs-project/}}.)  
  Keywords: compact, 3d gaussian, ar, gaussian splatting, head, compression, lighting, high-fidelity  
- **[Shell-Supervised Gaussian Splatting for Urban Real-to-Sim Reconstruction](https://arxiv.org/abs/2606.30014v1)**  
  Authors: Yuan Yang, Peijun Lu, Fangzhou Lu, Sai Fan, Siqi Yan, Chenyuan Zhang, Haobo Liang, Yichen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30014v1.pdf)  
  Keywords: 3d reconstruction, lightweight, face, ar, gaussian splatting, reflection, geometry  
- **[Learning Efficient 4D Gaussian Representations from Monocular Videos with Flow Splatting](https://arxiv.org/abs/2606.29976v1)**  
  Authors: Shengjun Zhang, Jinzhao Li, Xin Fei, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29976v1.pdf)  
  Keywords: 3d gaussian, dynamic, 4d, ar, deformation, gaussian splatting, motion, efficient  

### Quality Enhancement

*Showing the latest 50 out of 250 papers*

- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v1)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, localization, semantic, high-fidelity  
- **[Consistent Scene Understanding in 3D Gaussian Splatting via Multi-Cue Mask Refinement](https://arxiv.org/abs/2607.01708v1)**  
  Authors: Hyunjoon Park, Donghyeon Cho  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01708v1.pdf)  
  Keywords: 3d gaussian, understanding, gaussian splatting, segmentation, semantic, high-fidelity  
- **[GaussianEmoTalker: Real-Time Emotional Talking Head Synthesis with Audio-Driven and Blendshape-Based 3D Gaussian Splatting](https://arxiv.org/abs/2607.00959v1)**  
  Authors: Haijie Yang, Zhenyu Zhang, Yixuan Dong, Jianjun Qian, Jian Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00959v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://njust-yang.github.io/GaussianEmoTalker.github.io/)  
  Keywords: real-time rendering, 3d gaussian, ar, deformation, avatar, gaussian splatting, motion, animation, head, high-fidelity  
- **[AnchorSplat: Fast and Structure Consistent Detail Synthesis for Gaussian Splatting](https://arxiv.org/abs/2607.01290v1)**  
  Authors: Dexu Zhu, Jiangnan Shao, Xiaofeng Wang, Junxian Duan, Jie Cao, Zheng Zhu, Huaibo Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01290v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, fast, gaussian splatting, head, high-fidelity  
- **[Progressive Pose-Guided 4D Animal Reconstruction from Monocular Video](https://arxiv.org/abs/2607.00157v1)**  
  Authors: Siyuan Li, Weiying Chen, Yilin Wang, Xinxin Zuo, Xingyu Li, Li Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00157v1.pdf)  
  Keywords: 3d gaussian, 4d, ar, deformation, gaussian splatting, high-fidelity  
- **[Practical High-Fidelity Novel-View Synthesis of Mounted Lepidoptera](https://arxiv.org/abs/2606.31679v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31679v1.pdf)  
  Keywords: 3d gaussian, body, face, ar, gaussian splatting, segmentation, high-fidelity  
- **[Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)**  
  Authors: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin, SouYoung Jin, Liang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31050v1.pdf)  
  Keywords: human, 3d reconstruction, 3d gaussian, lightweight, dynamic, ar, fast, gaussian splatting, head, high-fidelity  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, head, outdoor, high-fidelity, efficient  
- **[FastPano3D: Feed-Forward Indoor Panoramic 3D Reconstruction from a Single Image](https://arxiv.org/abs/2606.30352v1)**  
  Authors: Jianqiang Li, Liumei Zhang, Wenjia Guo, Tianlong Feng, Yongzhi Liao, Di Lu, Hanchi Ren, Jingjing Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30352v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, lightweight, ar, fast, gaussian splatting, nerf, high-fidelity, efficient  
- **[Monte Carlo Energy Aggregation for Mobile 3D Gaussian Splatting](https://arxiv.org/abs/2606.30017v1)**  
  Authors: Xiaobiao Du, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30017v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/flux-gs-project/}{https://xiaobiaodu.github.io/flux-gs-project/}}.)  
  Keywords: compact, 3d gaussian, ar, gaussian splatting, head, compression, lighting, high-fidelity  

### Ray Tracing

- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, ar, fast, ray tracing, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: real-time rendering, 3d gaussian, ar, fast, ray tracing, path tracing, gaussian splatting, reflection, geometry, efficient  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, global illumination, gaussian splatting, illumination, geometry, efficient  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: ar, global illumination, gaussian splatting, illumination, high-fidelity  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: 3d gaussian, ar, ray tracing, gaussian splatting, reflection, segmentation, semantic, geometry, efficient  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, face, ar, fast, global illumination, gaussian splatting, illumination, shadow  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, ray casting, 3d gaussian, gaussian splatting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: 3d gaussian, ar, high-fidelity, ray tracing, gaussian splatting, geometry  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: robotics, 3d gaussian, dynamic, tracking, ar, ray tracing, gaussian splatting, lighting, semantic, efficient  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ar, face, ray tracing, gaussian splatting, reflection  

### Relighting

*Showing the latest 50 out of 138 papers*

- **[Intrinsic decomposition and editing of 3D Gaussian splats](https://arxiv.org/abs/2606.31637v1)**  
  Authors: Alexandre Lanvin, Jeffrey Hu, Simon Lucas, Adrien Bousseau, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31637v1.pdf)  
  Keywords: 3d gaussian, ar, face, gaussian splatting, lighting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: real-time rendering, 3d gaussian, ar, fast, ray tracing, path tracing, gaussian splatting, reflection, geometry, efficient  
- **[Monte Carlo Energy Aggregation for Mobile 3D Gaussian Splatting](https://arxiv.org/abs/2606.30017v1)**  
  Authors: Xiaobiao Du, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30017v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/flux-gs-project/}{https://xiaobiaodu.github.io/flux-gs-project/}}.)  
  Keywords: compact, 3d gaussian, ar, gaussian splatting, head, compression, lighting, high-fidelity  
- **[Shell-Supervised Gaussian Splatting for Urban Real-to-Sim Reconstruction](https://arxiv.org/abs/2606.30014v1)**  
  Authors: Yuan Yang, Peijun Lu, Fangzhou Lu, Sai Fan, Siqi Yan, Chenyuan Zhang, Haobo Liang, Yichen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30014v1.pdf)  
  Keywords: 3d reconstruction, lightweight, face, ar, gaussian splatting, reflection, geometry  
- **[DR-GS: Physically-Based Deformable and Relightable 2D Gaussians](https://arxiv.org/abs/2606.29379v1)**  
  Authors: Jiaxin Li, Tong Wu, Yi Wei, Tailin Wu, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29379v1.pdf)  
  Keywords: lighting, relighting, dynamic, face, ar, deformation, vr, gaussian splatting, reflection, illumination, efficient rendering, relightable, geometry, efficient  
- **[RAGA: Real Time Ray Traced Gaussian Shadow Casting for 3DGS Avatar-Scene Interaction](https://arxiv.org/abs/2606.29329v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Peter Wonka, Bing Zhou, Gerard Pons-Moll  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29329v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://miraymen.github.io/raga/.)  
  Keywords: 3d gaussian, ar, deformation, gaussian splatting, shadow, avatar  
- **[RefGlass-GS: A UAV-Enabled Fusion Framework for Photorealistic, Semantic and Interactive Digitization of Reflective Glass Facades via Gaussian Splatting](https://arxiv.org/abs/2606.28826v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Boyu Wang, Zhaolun Liang, Ang Li, Jeff Chak Fu Chan, Mingzhu Wang, Jack C. P. Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28826v1.pdf)  
  Keywords: ar, gaussian splatting, reflection, segmentation, semantic  
- **[AEGIR: Modeling Area Emitters for Indoor Inverse Rendering using Gaussian Splatting](https://arxiv.org/abs/2606.28635v2)**  
  Authors: Mohamed Shawky Sabae, Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28635v2.pdf)  
  Keywords: light transport, relighting, lighting, face, ar, gaussian splatting, illumination, shadow, relightable, geometry, efficient  
- **[SatSplat: Geometrically-Accurate Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2606.28581v1)**  
  Authors: Shuang Song, Jiyong Kim, Rongjun Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28581v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gdaosu.github.io/satsplat/.)  
  Keywords: 3d reconstruction, 3d gaussian, mapping, face, ar, gaussian splatting, illumination, shadow  
- **[SatSplatDiff: Geometry-preserving generative refinement for high-fidelity satellite Gaussian Splatting](https://arxiv.org/abs/2606.27223v2)**  
  Authors: Jiyong Kim, Shuang Song, Ronjgun Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.27223v2.pdf)  
  Keywords: 3d reconstruction, face, ar, high-fidelity, gaussian splatting, shadow, geometry  

### SLAM

*Showing the latest 50 out of 153 papers*

- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v1)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, localization, semantic, high-fidelity  
- **[AnchorSplat: Fast and Structure Consistent Detail Synthesis for Gaussian Splatting](https://arxiv.org/abs/2607.01290v1)**  
  Authors: Dexu Zhu, Jiangnan Shao, Xiaofeng Wang, Junxian Duan, Jie Cao, Zheng Zhu, Huaibo Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01290v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, fast, gaussian splatting, head, high-fidelity  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, gaussian splatting, outdoor, geometry  
- **[VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes](https://arxiv.org/abs/2606.30645v1)**  
  Authors: Yen-Jen Wang, Jiaman Li, Sirui Chen, Takara E. Truong, Pei Xu, Pieter Abbeel, Rocky Duan, Koushil Sreenath, Angjoo Kanazawa, Carmelo Sferrazza, Guanya Shi, Karen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30645v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vision-language-kinematics.github.io/)  
  Keywords: human, 3d gaussian, body, mapping, ar, gaussian splatting, motion  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, head, outdoor, high-fidelity, efficient  
- **[FalconTrack: Photorealistic Auto-Labeled Perception and Physics-Aware Vision-Based Aerial Tracking](https://arxiv.org/abs/2606.29783v1)**  
  Authors: Yan Miao, Karteek Gandiboyina, Noah Giles, Hideki Okamoto, Bardh Hoxha, Georgios Fainekos, Sayan Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29783v1.pdf)  
  Keywords: dynamic, tracking, ar, fast, gaussian splatting, head  
- **[Graph-GSReg: Leveraging 3D Scene Graphs for Gaussian Splatting Registration](https://arxiv.org/abs/2606.29782v1)**  
  Authors: Jaewon Lee, Mangyu Kong, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29782v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, gaussian splatting, understanding, semantic  
- **[MyGO-Splat: Multi-Objective Closed-Loop Geometric Feedback for RGB-Only Gaussian SLAM](https://arxiv.org/abs/2606.29738v1)**  
  Authors: Fan Zhu, Ziyu Chen, Zhenjun Zhao, Zhisong Xu, Hui Zhu, Mingrui Li, Chunmao Jiang, Javier Civera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29738v1.pdf)  
  Keywords: 3d gaussian, mapping, tracking, face, ar, high-fidelity, gaussian splatting, slam, localization, geometry  
- **[MoPe: Motion Permanence for Robust Monocular Gaussian Mapping in Dynamic Environments](https://arxiv.org/abs/2606.29237v1)**  
  Authors: Qixin Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29237v1.pdf)  
  Keywords: human, dynamic, tracking, mapping, ar, high-fidelity, gaussian splatting, motion, slam, localization, geometry  
- **[CubifyGS: Object-Centric 3D Gaussian Splatting for Lifelong Dynamic Scene Maintenance](https://arxiv.org/abs/2606.28720v1)**  
  Authors: Bohan Ren, Dianyi Yang, Shiyang Liu, Yu Gao, Jiadong Tang, Zhilin Lai, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28720v1.pdf)  
  Keywords: robotics, 3d gaussian, mapping, dynamic, ar, gaussian splatting, high-fidelity  

### Scene Understanding

*Showing the latest 50 out of 227 papers*

- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, nerf, segmentation, geometry  
- **[DL-SLAM: Enabling High-Fidelity Gaussian Splatting SLAM in Dynamic Environments based on Dual-Level Probability](https://arxiv.org/abs/2607.01860v1)**  
  Authors: Ziheng Xu, Qingfeng Li, Xuefeng Liu, Chen Chen, Jianwei Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01860v1.pdf)  
  Keywords: 3d gaussian, dynamic, tracking, mapping, ar, gaussian splatting, motion, slam, localization, semantic, high-fidelity  
- **[The Turning Point of 3D Plant Phenotyping: 3D Foundation Models Enable Minute-to-Second Cross-Crop Reconstruction and Beyond](https://arxiv.org/abs/2607.01753v1)**  
  Authors: Hanyue Jia, Wei Zhou, Wenbo Zhou, Yanan Li, Hao Lu, Tingting Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01753v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, fast, gaussian splatting, segmentation, semantic, geometry  
- **[Consistent Scene Understanding in 3D Gaussian Splatting via Multi-Cue Mask Refinement](https://arxiv.org/abs/2607.01708v1)**  
  Authors: Hyunjoon Park, Donghyeon Cho  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01708v1.pdf)  
  Keywords: 3d gaussian, understanding, gaussian splatting, segmentation, semantic, high-fidelity  
- **[Online Segment 3D Gaussians via Launching Virtual Drones](https://arxiv.org/abs/2607.01628v1)**  
  Authors: Liwei Liao, Rongjie Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.01628v1.pdf)  
  Keywords: real-time rendering, 3d gaussian, ar, gaussian splatting, segmentation  
- **[Practical High-Fidelity Novel-View Synthesis of Mounted Lepidoptera](https://arxiv.org/abs/2606.31679v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31679v1.pdf)  
  Keywords: 3d gaussian, body, face, ar, gaussian splatting, segmentation, high-fidelity  
- **[Open-Vocabulary and Referring Segmentation for 3D Gaussians Using 2D Detectors](https://arxiv.org/abs/2606.30638v1)**  
  Authors: Jameel Hassan, Yasiru Ranasinghe, Vishal Patel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30638v1.pdf)  
  Keywords: 3d gaussian, understanding, ar, gaussian splatting, segmentation, semantic  
- **[Graph-GSReg: Leveraging 3D Scene Graphs for Gaussian Splatting Registration](https://arxiv.org/abs/2606.29782v1)**  
  Authors: Jaewon Lee, Mangyu Kong, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29782v1.pdf)  
  Keywords: 3d gaussian, mapping, ar, gaussian splatting, understanding, semantic  
- **[Occlusion-Robust Multi-Object Decoupling for Physics-Based Robotic Interaction](https://arxiv.org/abs/2606.29303v2)**  
  Authors: Xin Dong, Lihan Zhang, Tianru Dai, Wenfeng Deng, Yansong Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29303v2.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, dynamic, ar, gaussian splatting, segmentation, geometry, sparse-view  
- **[DLGStream: Dynamic Language-embedded Guassian Splatting for Open-vocabulary Enabled Free-viewpoint Video Streaming](https://arxiv.org/abs/2606.28840v1)**  
  Authors: Zhihui Ke, Yuyang Liu, Xiaobo Zhou, Tie Qiu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28840v1.pdf)  
  Keywords: 3d gaussian, dynamic, 4d, ar, deformation, gaussian splatting, segmentation  



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