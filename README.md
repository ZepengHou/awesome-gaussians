# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-09-10 00:51:16

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

- [3DGS Surveys](#3dgs-surveys) (20 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (262 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (325 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (389 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (70 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (306 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (74 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (411 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (166 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (18 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (112 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (150 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (195 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: semantic, survey, 3d gaussian, understanding, segmentation, nerf, compact, gaussian splatting, high-fidelity, lighting, ar  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: robotics, semantic, survey, 3d gaussian, understanding, nerf, gaussian splatting, efficient, ar  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: robotics, survey, 3d gaussian, human, nerf, gaussian splatting, ar  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: robotics, vr, survey, 3d reconstruction, 3d gaussian, nerf, sparse-view, gaussian splatting, geometry, motion, ar  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v2)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Hanspeter Pfister, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v2.pdf)  
  Keywords: robotics, dynamic, vr, fast, survey, 3d reconstruction, 3d gaussian, human, nerf, gaussian splatting, lighting, slam, ar  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: autonomous driving, dynamic, survey, 3d gaussian, nerf, face, gaussian splatting, high-fidelity, outdoor, efficient, ar  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: robotics, autonomous driving, vr, survey, 3d reconstruction, 3d gaussian, nerf, gaussian splatting, high-fidelity, neural rendering, ar  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: semantic, survey, 3d reconstruction, 3d gaussian, understanding, segmentation, gaussian splatting, high-fidelity, outdoor, efficient, neural rendering, ar  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: localization, semantic, survey, 3d gaussian, segmentation, nerf, gaussian splatting, efficient, mapping, slam, ar  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: dynamic, survey, 3d gaussian, understanding, gaussian splatting, 4d, body, motion, ar  

### Acceleration

*Showing the latest 50 out of 262 papers*

- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, fast, 3d gaussian, real-time rendering, compact, gaussian splatting, efficient, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: fast, semantic, segmentation, human, face, gaussian splatting, 4d, avatar, neural rendering, ar  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: fast, 3d reconstruction, 3d gaussian, compact, high-fidelity, gaussian splatting, geometry, ar  
- **[AGS: Accelerating 3D Gaussian Splatting SLAM via CODEC-Assisted Frame
  Covisibility Detection](https://arxiv.org/abs/2509.00433v1)**  
  Authors: Houshu He, Naifeng Jing, Li Jiang, Xiaoyao Liang, Zhuoran Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00433v1.pdf)  
  Keywords: localization, 3d gaussian, tracking, gaussian splatting, efficient, mapping, slam, acceleration, ar  
- **[Scale-GS: Efficient Scalable Gaussian Splatting via Redundancy-filtering
  Training on Streaming Content](https://arxiv.org/abs/2508.21444v1)**  
  Authors: Jiayu Yang, Weijian Su, Songqian Zhang, Yuqi Han, Jinli Suo, Qiang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21444v1.pdf)  
  Keywords: dynamic, 3d gaussian, real-time rendering, head, high-fidelity, gaussian splatting, efficient, deformation, motion, ar  
- **[MAPo : Motion-Aware Partitioning of Deformable 3D Gaussian Splatting for
  High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2508.19786v1)**  
  Authors: Han Jiao, Jiakai Sun, Yexing Xu, Lei Zhao, Wei Xing, Huaizhong Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19786v1.pdf)  
  Keywords: dynamic, fast, 3d gaussian, high-fidelity, gaussian splatting, deformation, motion, ar  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: fast, animation, 3d gaussian, head, tracking, face, high-fidelity, gaussian splatting, avatar, ar  
- **[LabelGS: Label-Aware 3D Gaussian Splatting for 3D Scene Segmentation](https://arxiv.org/abs/2508.19699v1)**  
  Authors: Yupeng Zhang, Dezhi Zheng, Ping Lu, Han Zhang, Lei Wang, Liping xiang, Cheng Luo, Kaijun Deng, Xiaowen Fu, Linlin Shen, Jinbao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19699v1.pdf)  
  Keywords: semantic, 3d gaussian, understanding, segmentation, high-fidelity, gaussian splatting, efficient, efficient rendering, ar  

### Applications

*Showing the latest 50 out of 995 papers*

- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v2)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v2.pdf)  
  Keywords: dynamic, large scene, gaussian splatting, motion, ar  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v1)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v1.pdf)  
  Keywords: understanding, gaussian splatting, efficient, mapping, slam, ar  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: large scene, 3d gaussian, gaussian splatting, ar  
- **[Toward Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.05216v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05216v1.pdf)  
  Keywords: 3d gaussian, face, high-fidelity, gaussian splatting, ar  
- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: dynamic, 3d gaussian, face, gaussian splatting, efficient, geometry, ar  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[SSGaussian: Semantic-Aware and Structure-Preserving 3D Style Transfer](https://arxiv.org/abs/2509.04379v1)**  
  Authors: Jimin Xu, Bosheng Qin, Tao Jin, Zhou Zhao, Zhenhui Ye, Jun Yu, Fei Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04379v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jm-xu.github.io/SSGaussian)  
  Keywords: semantic, 3d gaussian, gaussian splatting, ar  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, fast, 3d gaussian, real-time rendering, compact, gaussian splatting, efficient, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: semantic, head, gaussian splatting, efficient, ar  

### Avatar Generation

*Showing the latest 50 out of 325 papers*

- **[Toward Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.05216v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05216v1.pdf)  
  Keywords: 3d gaussian, face, high-fidelity, gaussian splatting, ar  
- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: dynamic, 3d gaussian, face, gaussian splatting, efficient, geometry, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: semantic, head, gaussian splatting, efficient, ar  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: fast, semantic, segmentation, human, face, gaussian splatting, 4d, avatar, neural rendering, ar  
- **[Im2Haircut: Single-view Strand-based Hair Reconstruction for Human
  Avatars](https://arxiv.org/abs/2509.01469v1)**  
  Authors: Vanessa Sklyarova, Egor Zakharov, Malte Prinzler, Giorgio Becherini, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01469v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://im2haircut.is.tue.mpg.de.)  
  Keywords: human, avatar, geometry, ar  
- **[Complete Gaussian Splats from a Single Image with Denoising Diffusion
  Models](https://arxiv.org/abs/2508.21542v1)**  
  Authors: Ziwei Liao, Mohamed Sayed, Steven L. Waslander, Sara Vicente, Daniyar Turmukhambetov, Michael Firman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21542v1.pdf)  
  Keywords: face, gaussian splatting, ar  
- **[Scale-GS: Efficient Scalable Gaussian Splatting via Redundancy-filtering
  Training on Streaming Content](https://arxiv.org/abs/2508.21444v1)**  
  Authors: Jiayu Yang, Weijian Su, Songqian Zhang, Yuqi Han, Jinli Suo, Qiang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21444v1.pdf)  
  Keywords: dynamic, 3d gaussian, real-time rendering, head, high-fidelity, gaussian splatting, efficient, deformation, motion, ar  
- **[ARGS: Advanced Regularization on Aligning Gaussians over the Surface](https://arxiv.org/abs/2508.21344v1)**  
  Authors: Jeong Uk Lee, Sung Hee Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21344v1.pdf)  
  Keywords: 3d gaussian, face, gaussian splatting, geometry, ar  
- **[AvatarBack: Back-Head Generation for Complete 3D Avatars from Front-View
  Images](https://arxiv.org/abs/2508.20623v1)**  
  Authors: Shiqi Xin, Xiaolin Zhang, Yanbin Liu, Peng Zhang, Caifeng Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20623v1.pdf)  
  Keywords: 3d gaussian, head, gaussian splatting, avatar, motion, ar  

### Dynamic Scene

*Showing the latest 50 out of 389 papers*

- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v2)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v2.pdf)  
  Keywords: dynamic, large scene, gaussian splatting, motion, ar  
- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: dynamic, 3d gaussian, face, gaussian splatting, efficient, geometry, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: fast, semantic, segmentation, human, face, gaussian splatting, 4d, avatar, neural rendering, ar  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: dynamic, localization, tracking, high-fidelity, gaussian splatting, efficient, mapping, slam, ar  
- **[Scale-GS: Efficient Scalable Gaussian Splatting via Redundancy-filtering
  Training on Streaming Content](https://arxiv.org/abs/2508.21444v1)**  
  Authors: Jiayu Yang, Weijian Su, Songqian Zhang, Yuqi Han, Jinli Suo, Qiang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21444v1.pdf)  
  Keywords: dynamic, 3d gaussian, real-time rendering, head, high-fidelity, gaussian splatting, efficient, deformation, motion, ar  
- **[AvatarBack: Back-Head Generation for Complete 3D Avatars from Front-View
  Images](https://arxiv.org/abs/2508.20623v1)**  
  Authors: Shiqi Xin, Xiaolin Zhang, Yanbin Liu, Peng Zhang, Caifeng Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20623v1.pdf)  
  Keywords: 3d gaussian, head, gaussian splatting, avatar, motion, ar  
- **[MAPo : Motion-Aware Partitioning of Deformable 3D Gaussian Splatting for
  High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2508.19786v1)**  
  Authors: Han Jiao, Jiakai Sun, Yexing Xu, Lei Zhao, Wei Xing, Huaizhong Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19786v1.pdf)  
  Keywords: dynamic, fast, 3d gaussian, high-fidelity, gaussian splatting, deformation, motion, ar  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: fast, animation, 3d gaussian, head, tracking, face, high-fidelity, gaussian splatting, avatar, ar  
- **[Style4D-Bench: A Benchmark Suite for 4D Stylization](https://arxiv.org/abs/2508.19243v1)**  
  Authors: Beiqi Chen, Shuai Shao, Haitang Feng, Jianhuang Lai, Jianlou Si, Guangcong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19243v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://becky-catherine.github.io/Style4D)  
  Keywords: dynamic, gaussian splatting, 4d, lightweight, geometry, motion, ar  

### Few-shot

*Showing the latest 50 out of 70 papers*

- **[${C}^{3}$-GS: Learning Context-aware, Cross-dimension, Cross-scale
  Feature for Generalizable Gaussian Splatting](https://arxiv.org/abs/2508.20754v1)**  
  Authors: Yuxi Hu, Jun Zhang, Kuangyi Chen, Zhe Zhang, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20754v1.pdf)  
  Keywords: gaussian splatting, lightweight, sparse view, geometry, ar  
- **[MeshSplat: Generalizable Sparse-View Surface Reconstruction via Gaussian
  Splatting](https://arxiv.org/abs/2508.17811v1)**  
  Authors: Hanzhi Chang, Ruijie Zhu, Wenjie Chang, Mulin Yu, Yanzhe Liang, Jiahao Lu, Zhuoyuan Li, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17811v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanzhichang.github.io/meshsplat_web)  
  Keywords: sparse-view, face, gaussian splatting, geometry, ar  
- **[Enhancing Novel View Synthesis from extremely sparse views with SfM-free
  3D Gaussian Splatting Framework](https://arxiv.org/abs/2508.15457v1)**  
  Authors: Zongqi He, Hanmin Li, Kin-Chung Chan, Yushen Zuo, Hao Xie, Zhe Xiao, Jun Xiao, Kin-Man Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15457v1.pdf)  
  Keywords: 3d gaussian, sparse-view, gaussian splatting, sparse view, geometry, motion, ar  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, 3d gaussian, face, gaussian splatting, lighting, outdoor, relighting, sparse view, geometry, ar  
- **[Quantifying and Alleviating Co-Adaptation in Sparse-View 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.12720v2)**  
  Authors: Kangjie Chen, Yingji Zhong, Zhihao Li, Jiaqi Lin, Youyu Chen, Minghan Qin, Haoqian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12720v2.pdf)  
  Keywords: 3d gaussian, understanding, sparse-view, gaussian splatting, lightweight, ar  
- **[Toward Human-Robot Teaming: Learning Handover Behaviors from 3D Scenes](https://arxiv.org/abs/2508.09855v1)**  
  Authors: Yuekun Wu, Yik Lung Pang, Andrea Cavallaro, Changjae Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09855v1.pdf)  
  Keywords: sparse-view, gaussian splatting, human, ar  
- **[GSFixer: Improving 3D Gaussian Splatting with Reference-Guided Video
  Diffusion Priors](https://arxiv.org/abs/2508.09667v1)**  
  Authors: Xingyilang Yin, Qi Zhang, Jiahao Chang, Ying Feng, Qingnan Fan, Xi Yang, Chi-Man Pun, Huaqi Zhang, Xiaodong Cun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09667v1.pdf)  
  Keywords: semantic, 3d reconstruction, 3d gaussian, sparse-view, gaussian splatting, sparse view, geometry, ar  
- **[SkySplat: Generalizable 3D Gaussian Splatting from Multi-Temporal Sparse
  Satellite Images](https://arxiv.org/abs/2508.09479v1)**  
  Authors: Xuejun Huang, Xinyi Liu, Yi Wan, Zhi Zheng, Bin Zhang, Mingtao Xiong, Yingying Pei, Yongjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09479v1.pdf)  
  Keywords: 3d gaussian, sparse-view, gaussian splatting, efficient, ar  
- **[DIP-GS: Deep Image Prior For Gaussian Splatting Sparse View Recovery](https://arxiv.org/abs/2508.07372v1)**  
  Authors: Rajaei Khatib, Raja Giryes  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.07372v1.pdf)  
  Keywords: 3d gaussian, real-time rendering, sparse-view, gaussian splatting, sparse view, ar  
- **[UGOD: Uncertainty-Guided Differentiable Opacity and Soft Dropout for
  Enhanced Sparse-View 3DGS](https://arxiv.org/abs/2508.04968v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04968v1.pdf)  
  Keywords: 3d gaussian, nerf, sparse-view, gaussian splatting, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 306 papers*

- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: dynamic, 3d gaussian, face, gaussian splatting, efficient, geometry, ar  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[Im2Haircut: Single-view Strand-based Hair Reconstruction for Human
  Avatars](https://arxiv.org/abs/2509.01469v1)**  
  Authors: Vanessa Sklyarova, Egor Zakharov, Malte Prinzler, Giorgio Becherini, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01469v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://im2haircut.is.tue.mpg.de.)  
  Keywords: human, avatar, geometry, ar  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: fast, 3d reconstruction, 3d gaussian, compact, high-fidelity, gaussian splatting, geometry, ar  
- **[SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00800v1.pdf)  
  Keywords: semantic, 3d reconstruction, 3d gaussian, understanding, nerf, gaussian splatting, high-fidelity, ar  
- **[ARGS: Advanced Regularization on Aligning Gaussians over the Surface](https://arxiv.org/abs/2508.21344v1)**  
  Authors: Jeong Uk Lee, Sung Hee Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21344v1.pdf)  
  Keywords: 3d gaussian, face, gaussian splatting, geometry, ar  
- **[${C}^{3}$-GS: Learning Context-aware, Cross-dimension, Cross-scale
  Feature for Generalizable Gaussian Splatting](https://arxiv.org/abs/2508.20754v1)**  
  Authors: Yuxi Hu, Jun Zhang, Kuangyi Chen, Zhe Zhang, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20754v1.pdf)  
  Keywords: gaussian splatting, lightweight, sparse view, geometry, ar  
- **[Style4D-Bench: A Benchmark Suite for 4D Stylization](https://arxiv.org/abs/2508.19243v1)**  
  Authors: Beiqi Chen, Shuai Shao, Haitang Feng, Jianhuang Lai, Jianlou Si, Guangcong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19243v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://becky-catherine.github.io/Style4D)  
  Keywords: dynamic, gaussian splatting, 4d, lightweight, geometry, motion, ar  
- **[Camera Pose Refinement via 3D Gaussian Splatting](https://arxiv.org/abs/2508.17876v1)**  
  Authors: Lulu Hao, Lipu Zhou, Zhenzhong Wei, Xu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17876v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, lightweight, geometry, ar  

### Large Scene

*Showing the latest 50 out of 74 papers*

- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v2)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v2.pdf)  
  Keywords: dynamic, large scene, gaussian splatting, motion, ar  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: large scene, 3d gaussian, gaussian splatting, ar  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: localization, 3d gaussian, gaussian splatting, outdoor, ar  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, 3d gaussian, face, gaussian splatting, lighting, outdoor, relighting, sparse view, geometry, ar  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, understanding, gaussian splatting, lighting, outdoor, illumination, ar  
- **[Online 3D Gaussian Splatting Modeling with Novel View Selection](https://arxiv.org/abs/2508.14014v2)**  
  Authors: Byeonggwon Lee, Junkyu Park, Khang Truong Giang, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14014v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, outdoor, slam, ar  
- **[InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2508.12015v1)**  
  Authors: Hongyuan Liu, Haochen Yu, Jianfei Jiang, Qiankun Liu, Jiansheng Chen, Huimin Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12015v1.pdf)  
  Keywords: autonomous driving, dynamic, 3d gaussian, understanding, segmentation, gaussian splatting, outdoor, lightweight, ar  
- **[Remove360: Benchmarking Residuals After Object Removal in 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.11431v1)**  
  Authors: Simona Kocour, Assia Benbihi, Torsten Sattler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.11431v1.pdf)  
  Keywords: semantic, 3d reconstruction, 3d gaussian, understanding, face, outdoor, gaussian splatting, geometry, ar  
- **[Multi-view Normal and Distance Guidance Gaussian Splatting for Surface
  Reconstruction](https://arxiv.org/abs/2508.07701v2)**  
  Authors: Bo Jia, Yanan Guo, Ying Chang, Benkui Zhang, Ying Xie, Kangning Du, Lin Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.07701v2.pdf)  
  Keywords: 3d gaussian, face, outdoor, gaussian splatting, geometry, ar  

### Model Compression

*Showing the latest 50 out of 411 papers*

- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v1)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v1.pdf)  
  Keywords: understanding, gaussian splatting, efficient, mapping, slam, ar  
- **[GeoSplat: A Deep Dive into Geometry-Constrained Gaussian Splatting](https://arxiv.org/abs/2509.05075v1)**  
  Authors: Yangming Li, Chaoyu Liu, Lihao Liu, Simon Masnou, Carola-Bibian Schönlieb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05075v1.pdf)  
  Keywords: dynamic, 3d gaussian, face, gaussian splatting, efficient, geometry, ar  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, fast, 3d gaussian, real-time rendering, compact, gaussian splatting, efficient, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: semantic, head, gaussian splatting, efficient, ar  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: fast, 3d reconstruction, 3d gaussian, compact, high-fidelity, gaussian splatting, geometry, ar  
- **[GS-TG: 3D Gaussian Splatting Accelerator with Tile Grouping for Reducing
  Redundant Sorting while Preserving Rasterization Efficiency](https://arxiv.org/abs/2509.00911v2)**  
  Authors: Joongho Jo, Jongsun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00911v2.pdf)  
  Keywords: 3d gaussian, nerf, gaussian splatting, efficient, ar  
- **[MarkSplatter: Generalizable Watermarking for 3D Gaussian Splatting Model
  via Splatter Image Structure](https://arxiv.org/abs/2509.00757v1)**  
  Authors: Xiufeng Huang, Ziyuan Luo, Qi Song, Ruofei Wang, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00757v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kevinhuangxf.github.io/marksplatter.)  
  Keywords: 3d gaussian, segmentation, gaussian splatting, efficient, ar  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: dynamic, localization, tracking, high-fidelity, gaussian splatting, efficient, mapping, slam, ar  

### Quality Enhancement

*Showing the latest 50 out of 166 papers*

- **[Toward Distributed 3D Gaussian Splatting for High-Resolution Isosurface
  Visualization](https://arxiv.org/abs/2509.05216v1)**  
  Authors: Mengjiao Han, Andres Sewell, Joseph Insley, Janet Knowles, Victor A. Mateevitsi, Michael E. Papka, Steve Petruzza, Silvio Rizzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.05216v1.pdf)  
  Keywords: 3d gaussian, face, high-fidelity, gaussian splatting, ar  
- **[ContraGS: Codebook-Condensed and Trainable Gaussian Splatting for Fast,
  Memory-Efficient Reconstruction](https://arxiv.org/abs/2509.03775v1)**  
  Authors: Sankeerth Durvasula, Sharanshangar Muhunthan, Zain Moustafa, Richard Chen, Ruofan Liang, Yushi Guan, Nilesh Ahuja, Nilesh Jain, Selvakumar Panneer, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.03775v1.pdf)  
  Keywords: high quality, fast, 3d gaussian, real-time rendering, compact, gaussian splatting, efficient, ar  
- **[GRMM: Real-Time High-Fidelity Gaussian Morphable Head Model with Learned
  Residuals](https://arxiv.org/abs/2509.02141v1)**  
  Authors: Mohit Mendiratta, Mayur Deshmukh, Kartik Teotia, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.02141v1.pdf)  
  Keywords: vr, fast, animation, real-time rendering, head, face, high-fidelity, gaussian splatting, lightweight, deformation, geometry, ar  
- **[Towards Integrating Multi-Spectral Imaging with Gaussian Splatting](https://arxiv.org/abs/2509.00989v1)**  
  Authors: Josef Grün, Lukas Meyer, Maximilian Weiherer, Bernhard Egger, Marc Stamminger, Linus Franke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00989v1.pdf)  
  Keywords: fast, 3d reconstruction, 3d gaussian, compact, high-fidelity, gaussian splatting, geometry, ar  
- **[SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00800v1.pdf)  
  Keywords: semantic, 3d reconstruction, 3d gaussian, understanding, nerf, gaussian splatting, high-fidelity, ar  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: dynamic, localization, tracking, high-fidelity, gaussian splatting, efficient, mapping, slam, ar  
- **[Scale-GS: Efficient Scalable Gaussian Splatting via Redundancy-filtering
  Training on Streaming Content](https://arxiv.org/abs/2508.21444v1)**  
  Authors: Jiayu Yang, Weijian Su, Songqian Zhang, Yuqi Han, Jinli Suo, Qiang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.21444v1.pdf)  
  Keywords: dynamic, 3d gaussian, real-time rendering, head, high-fidelity, gaussian splatting, efficient, deformation, motion, ar  
- **[MAPo : Motion-Aware Partitioning of Deformable 3D Gaussian Splatting for
  High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2508.19786v1)**  
  Authors: Han Jiao, Jiakai Sun, Yexing Xu, Lei Zhao, Wei Xing, Huaizhong Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19786v1.pdf)  
  Keywords: dynamic, fast, 3d gaussian, high-fidelity, gaussian splatting, deformation, motion, ar  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: fast, animation, 3d gaussian, head, tracking, face, high-fidelity, gaussian splatting, avatar, ar  
- **[LabelGS: Label-Aware 3D Gaussian Splatting for 3D Scene Segmentation](https://arxiv.org/abs/2508.19699v1)**  
  Authors: Yupeng Zhang, Dezhi Zheng, Ping Lu, Han Zhang, Lei Wang, Liping xiang, Cheng Luo, Kaijun Deng, Xiaowen Fu, Linlin Shen, Jinbao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19699v1.pdf)  
  Keywords: semantic, 3d gaussian, understanding, segmentation, high-fidelity, gaussian splatting, efficient, efficient rendering, ar  

### Ray Tracing

- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: reflection, 3d gaussian, ray tracing, nerf, face, gaussian splatting, high-fidelity, lighting, relighting, illumination, geometry, ar  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: dynamic, shadow, global illumination, 3d gaussian, face, gaussian splatting, lighting, outdoor, relighting, illumination, relightable, ar  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: dynamic, 3d gaussian, path tracing, gaussian splatting, lighting, face, ar  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relightable, 3d gaussian, face, gaussian splatting, lighting, ray marching, relighting, efficient, geometry, efficient rendering, ar  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: ray tracing, real-time rendering, high-fidelity, gaussian splatting, efficient, ar  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v2)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v2.pdf)  
  Keywords: fast, shadow, ray tracing, human, gaussian splatting, lighting, relighting, avatar, geometry, relightable, ar  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: ray tracing, 3d gaussian, gaussian splatting, lighting, efficient, relighting, acceleration, efficient rendering, ar  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: dynamic, animation, 3d gaussian, compact, gaussian splatting, ray marching, efficient, acceleration, ar  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: global illumination, 3d gaussian, ray tracing, real-time rendering, face, gaussian splatting, lighting, efficient, illumination, ar  
- **[REdiSplats: Ray Tracing for Editable Gaussian Splatting](https://arxiv.org/abs/2503.12284v1)**  
  Authors: Krzysztof Byrski, Grzegorz Wilczyński, Weronika Smolak-Dyżewska, Piotr Borycki, Dawid Baran, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12284v1.pdf)  
  Keywords: fast, shadow, reflection, 3d gaussian, ray tracing, gaussian splatting, neural rendering, ar  

### Relighting

*Showing the latest 50 out of 112 papers*

- **[ColorGS: High-fidelity Surgical Scene Reconstruction with Colored
  Gaussian Splatting](https://arxiv.org/abs/2508.18696v1)**  
  Authors: Qun Ji, Peng Li, Mingqiang Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18696v1.pdf)  
  Keywords: dynamic, vr, 3d gaussian, real-time rendering, nerf, gaussian splatting, high-fidelity, lighting, efficient, deformation, motion, ar  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, localization, high-fidelity, gaussian splatting, efficient, lighting, neural rendering, ar  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: autonomous driving, 3d gaussian, face, gaussian splatting, lighting, outdoor, relighting, sparse view, geometry, ar  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: reflection, 3d gaussian, ray tracing, nerf, face, gaussian splatting, high-fidelity, lighting, relighting, illumination, geometry, ar  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, understanding, gaussian splatting, lighting, outdoor, illumination, ar  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: semantic, survey, 3d gaussian, understanding, segmentation, nerf, compact, gaussian splatting, high-fidelity, lighting, ar  
- **[HumanGenesis: Agent-Based Geometric and Generative Modeling for
  Synthetic Human Dynamics](https://arxiv.org/abs/2508.09858v1)**  
  Authors: Weiqi Li, Zehao Zhang, Liang Lin, Guangrun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09858v1.pdf)  
  Keywords: dynamic, reflection, 3d gaussian, human, face, gaussian splatting, 4d, deformation, motion, ar  
- **[Vision-Only Gaussian Splatting for Collaborative Semantic Occupancy
  Prediction](https://arxiv.org/abs/2508.10936v1)**  
  Authors: Cheng Chen, Hao Huang, Saurabh Bagchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.10936v1.pdf)  
  Keywords: semantic, gaussian splatting, lighting, geometry, ar  
- **[Touch-Augmented Gaussian Splatting for Enhanced 3D Scene Reconstruction](https://arxiv.org/abs/2508.07717v1)**  
  Authors: Yuchen Gao, Xiao Xu, Eckehard Steinbach, Daniel E. Lucani, Qi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.07717v1.pdf)  
  Keywords: 3d gaussian, face, gaussian splatting, lighting, geometry, ar  
- **[UW-3DGS: Underwater 3D Reconstruction with Physics-Aware Gaussian
  Splatting](https://arxiv.org/abs/2508.06169v1)**  
  Authors: Wenpeng Xing, Jie Chen, Zaifeng Yang, Changting Lin, Jianfeng Dong, Chaochao Chen, Xun Zhou, Meng Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.06169v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, light transport, nerf, face, gaussian splatting, geometry, ar  

### SLAM

*Showing the latest 50 out of 150 papers*

- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v1)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v1.pdf)  
  Keywords: understanding, gaussian splatting, efficient, mapping, slam, ar  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: dynamic, localization, tracking, high-fidelity, gaussian splatting, efficient, mapping, slam, ar  
- **[AGS: Accelerating 3D Gaussian Splatting SLAM via CODEC-Assisted Frame
  Covisibility Detection](https://arxiv.org/abs/2509.00433v1)**  
  Authors: Houshu He, Naifeng Jing, Li Jiang, Xiaoyao Liang, Zhuoran Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00433v1.pdf)  
  Keywords: localization, 3d gaussian, tracking, gaussian splatting, efficient, mapping, slam, acceleration, ar  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: fast, animation, 3d gaussian, head, tracking, face, high-fidelity, gaussian splatting, avatar, ar  
- **[PseudoMapTrainer: Learning Online Mapping without HD Maps](https://arxiv.org/abs/2508.18788v1)**  
  Authors: Christian Löwens, Thorben Funke, Jingchao Xie, Alexandru Paul Condurache  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18788v1.pdf)  
  Keywords: semantic, segmentation, face, gaussian splatting, mapping, ar  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: localization, 3d gaussian, gaussian splatting, outdoor, ar  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, localization, high-fidelity, gaussian splatting, efficient, lighting, neural rendering, ar  
- **[From Slices to Structures: Unsupervised 3D Reconstruction of Female
  Pelvic Anatomy from Freehand Transvaginal Ultrasound](https://arxiv.org/abs/2508.14552v1)**  
  Authors: Max Krähenmann, Sergio Tascon-Morales, Fabian Laumer, Julia E. Vogt, Ece Ozkan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14552v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, tracking, compact, gaussian splatting, efficient, geometry, motion, ar  
- **[Online 3D Gaussian Splatting Modeling with Novel View Selection](https://arxiv.org/abs/2508.14014v2)**  
  Authors: Byeonggwon Lee, Junkyu Park, Khang Truong Giang, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14014v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, outdoor, slam, ar  
- **[SAGOnline: Segment Any Gaussians Online](https://arxiv.org/abs/2508.08219v1)**  
  Authors: Wentao Sun, Quanyun Wu, Hanqing Xu, Kyle Gao, Zhengsen Xu, Yiping Chen, Dedong Zhang, Lingfei Ma, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.08219v1.pdf)  
  Keywords: vr, 3d gaussian, understanding, segmentation, real-time rendering, tracking, nerf, gaussian splatting, efficient, lightweight, ar  

### Scene Understanding

*Showing the latest 50 out of 195 papers*

- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v1)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v1.pdf)  
  Keywords: understanding, gaussian splatting, efficient, mapping, slam, ar  
- **[CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus](https://arxiv.org/abs/2509.04859v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04859v1.pdf)  
  Keywords: robotics, fast, semantic, 3d reconstruction, 3d gaussian, segmentation, gaussian splatting, outdoor, efficient, ar  
- **[SSGaussian: Semantic-Aware and Structure-Preserving 3D Style Transfer](https://arxiv.org/abs/2509.04379v1)**  
  Authors: Jimin Xu, Bosheng Qin, Tao Jin, Zhou Zhao, Zhenhui Ye, Jun Yu, Fei Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.04379v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jm-xu.github.io/SSGaussian)  
  Keywords: semantic, 3d gaussian, gaussian splatting, ar  
- **[2D Gaussian Splatting with Semantic Alignment for Image Inpainting](https://arxiv.org/abs/2509.01964v1)**  
  Authors: Hongyu Li, Chaofeng Chen, Xiaoming Li, Guangming Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01964v1.pdf)  
  Keywords: semantic, head, gaussian splatting, efficient, ar  
- **[GaussianGAN: Real-Time Photorealistic controllable Human Avatars](https://arxiv.org/abs/2509.01681v1)**  
  Authors: Mohamed Ilyes Lakhal, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.01681v1.pdf)  
  Keywords: fast, semantic, segmentation, human, face, gaussian splatting, 4d, avatar, neural rendering, ar  
- **[SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00800v1.pdf)  
  Keywords: semantic, 3d reconstruction, 3d gaussian, understanding, nerf, gaussian splatting, high-fidelity, ar  
- **[MarkSplatter: Generalizable Watermarking for 3D Gaussian Splatting Model
  via Splatter Image Structure](https://arxiv.org/abs/2509.00757v1)**  
  Authors: Xiufeng Huang, Ziyuan Luo, Qi Song, Ruofei Wang, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00757v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kevinhuangxf.github.io/marksplatter.)  
  Keywords: 3d gaussian, segmentation, gaussian splatting, efficient, ar  
- **[LabelGS: Label-Aware 3D Gaussian Splatting for 3D Scene Segmentation](https://arxiv.org/abs/2508.19699v1)**  
  Authors: Yupeng Zhang, Dezhi Zheng, Ping Lu, Han Zhang, Lei Wang, Liping xiang, Cheng Luo, Kaijun Deng, Xiaowen Fu, Linlin Shen, Jinbao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19699v1.pdf)  
  Keywords: semantic, 3d gaussian, understanding, segmentation, high-fidelity, gaussian splatting, efficient, efficient rendering, ar  
- **[PseudoMapTrainer: Learning Online Mapping without HD Maps](https://arxiv.org/abs/2508.18788v1)**  
  Authors: Christian Löwens, Thorben Funke, Jingchao Xie, Alexandru Paul Condurache  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18788v1.pdf)  
  Keywords: semantic, segmentation, face, gaussian splatting, mapping, ar  
- **[GWM: Towards Scalable Gaussian World Models for Robotic Manipulation](https://arxiv.org/abs/2508.17600v1)**  
  Authors: Guanxing Lu, Baoxiong Jia, Puhao Li, Yixin Chen, Ziwei Wang, Yansong Tang, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17600v1.pdf)  
  Keywords: understanding, gaussian splatting, ar  



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