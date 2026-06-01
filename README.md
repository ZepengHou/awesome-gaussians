# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-06-01 02:42:18

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

- [3DGS Surveys](#3dgs-surveys) (13 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (219 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (337 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (376 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (392 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (47 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (428 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (240 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (135 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (146 papers) - Papers about SLAM using Gaussian Splatting
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
  Keywords: efficient, tracking, 3d gaussian, gaussian splatting, ar, slam, geometry, 3d reconstruction, survey, motion  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: vr, 3d gaussian, ar, gaussian splatting, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, mapping, survey, ray tracing  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: efficient, face, tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, dynamic, survey, localization, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: 3d gaussian, ar, robotics, gaussian splatting, survey  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: efficient, nerf, 3d gaussian, gaussian splatting, ar, geometry, survey  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, compression, high-fidelity, 3d gaussian, gaussian splatting, ar, 4d, dynamic, 3d reconstruction, survey, compact  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: nerf, understanding, 3d gaussian, gaussian splatting, robotics, ar, slam, mapping, semantic, survey, localization  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: efficient, high-fidelity, 3d gaussian, gaussian splatting, robotics, ar, slam, mapping, semantic, survey, localization  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, 4d, geometry, survey, motion  

### Acceleration

*Showing the latest 50 out of 219 papers*

- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, robotics, ar, fast, autonomous driving, 3d reconstruction  
- **[Smaller and Faster 3DGS via Post-Training Dictionary Learning](https://arxiv.org/abs/2605.30396v1)**  
  Authors: Jiarong Gong, Jonas Unger, Ehsan Miandji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30396v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar, fast, real-time rendering  
- **[Eulerian Gaussian Splatting using Hashed Probability Pyramids](https://arxiv.org/abs/2605.29136v1)**  
  Authors: Mia Gaia Polansky, George Kopanas, Stephan Garbin, Todd Zickler, Dor Verbin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29136v1.pdf)  
  Keywords: efficient, nerf, 3d gaussian, gaussian splatting, ar, fast  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: face, high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, 3d reconstruction, real-time rendering  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, illumination, relighting, relightable, sparse-view, lighting  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, geometry, sparse-view, motion  
- **[No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos](https://arxiv.org/abs/2605.22190v1)**  
  Authors: Matteo Balice, Yanik Kunzi, Chenyangguang Zhang, Matteo Matteucci, Marc Pollefeys, Sungwhan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22190v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, 4d, geometry, dynamic, motion  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v2)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v2.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, deformation, sparse-view  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v2)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, lightweight, 3d reconstruction, compact, head  
- **[Transcoding a 3D Gaussian Splatting Model from a Plenoptic Point Cloud or Mesh without the Original Multi-view Images](https://arxiv.org/abs/2605.21051v1)**  
  Authors: Maja Krivokuća, Riad Bendouro, Neus Sabater  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21051v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, ar, fast  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, geometry, deformation  
- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: understanding, gaussian splatting, ar, geometry, semantic  
- **[Benchmarking Single-Step Inpainting Methods for Multi-Object 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2605.30987v1)**  
  Authors: Finn Dröge, Cecilia Curreli, Abhishek Saroha, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30987v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, ar  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: efficient, high-fidelity, gaussian splatting, robotics, ar, dynamic  
- **[Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation](https://arxiv.org/abs/2605.30855v1)**  
  Authors: Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30855v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting, mapping  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, robotics, ar, fast, autonomous driving, 3d reconstruction  
- **[MonoPhysics: Estimating Geometry, Appearance, and Physical Parameters from Monocular Videos](https://arxiv.org/abs/2605.30320v1)**  
  Authors: Daniel Rho, Jun Myeong Choi, Matthew Thornton, Biswadip Dey, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30320v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://daniel03c1.github.io/MonoPhysics/)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ar  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, face, high-fidelity, gaussian splatting, ar, geometry, 3d reconstruction, large scene, urban scene  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: 3d gaussian, ar, 4d, semantic, dynamic, motion, human  

### Avatar Generation

*Showing the latest 50 out of 337 papers*

- **[Benchmarking Single-Step Inpainting Methods for Multi-Object 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2605.30987v1)**  
  Authors: Finn Dröge, Cecilia Curreli, Abhishek Saroha, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30987v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, ar  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, face, high-fidelity, gaussian splatting, ar, geometry, 3d reconstruction, large scene, urban scene  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: 3d gaussian, ar, 4d, semantic, dynamic, motion, human  
- **[Comparative evaluation of photogrammetric reconstruction methods and 3D Gaussian Splatting for road surface roughness analysis](https://arxiv.org/abs/2605.29452v1)**  
  Authors: Marouane Elmegdar, Teng Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29452v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, segmentation, ar, geometry, 3d reconstruction  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: face, high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, 3d reconstruction, real-time rendering  
- **[R5DGS: Semantic-Aware 4D Gaussian Splatting with Rigid Body Constraints for Efficient Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.25909v1)**  
  Authors: Denis Gridusov, Maxim Popov, Sergey Kolyubin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25909v1.pdf)  
  Keywords: efficient, vr, body, gaussian splatting, ar, robotics, 4d, motion, semantic, dynamic, compact, head  
- **[SplitAvatar: One-shot Head Avatar with Autoregressive Gaussian Splitting](https://arxiv.org/abs/2605.25751v1)**  
  Authors: Hongzhe Liao, Chuhua Xian, Hongmin Cai, Haiyang Liu, Fa-Ting Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25751v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, dynamic, head, avatar, human  
- **[ParkingWorld: End-to-End Autonomous Parking Reinforcement Learning from Corrective Experience in 3DGS Simulation](https://arxiv.org/abs/2605.25029v2)**  
  Authors: Zhengcheng Yu, Changze Li, Haoran Liu, Tong Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25029v2.pdf)  
  Keywords: efficient, face, high-fidelity, 3d gaussian, gaussian splatting, ar, head, human  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, segmentation, ar, semantic, head, human  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: compression, understanding, 3d gaussian, gaussian splatting, ar, human, motion, lighting  

### Dynamic Scene

*Showing the latest 50 out of 376 papers*

- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, geometry, deformation  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: efficient, high-fidelity, gaussian splatting, robotics, ar, dynamic  
- **[Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation](https://arxiv.org/abs/2605.30855v1)**  
  Authors: Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30855v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: 3d gaussian, ar, 4d, semantic, dynamic, motion, human  
- **[FRUC: Feedforward Dynamic Scene Reconstruction from Uncalibrated Collaborative Driving Views](https://arxiv.org/abs/2605.29997v1)**  
  Authors: Yihang Tao, Yu Guo, Zhengru Fang, Haonan An, Yuguang Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29997v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, geometry, dynamic  
- **[FreeForm: Reduced-Order Deformable Simulation from Particle-Based Skinning Eigenmodes](https://arxiv.org/abs/2605.29318v1)**  
  Authors: Donglai Xiang, Vismay Modi, Rishit Dagli, Ty Trusty, Gilles Daviet, Anka He Chen, Nicholas Sharp, David I. W. Levin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29318v1.pdf)  
  Keywords: geometry, dynamic, ar  
- **[R5DGS: Semantic-Aware 4D Gaussian Splatting with Rigid Body Constraints for Efficient Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.25909v1)**  
  Authors: Denis Gridusov, Maxim Popov, Sergey Kolyubin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25909v1.pdf)  
  Keywords: efficient, vr, body, gaussian splatting, ar, robotics, 4d, motion, semantic, dynamic, compact, head  
- **[SplitAvatar: One-shot Head Avatar with Autoregressive Gaussian Splitting](https://arxiv.org/abs/2605.25751v1)**  
  Authors: Hongzhe Liao, Chuhua Xian, Hongmin Cai, Haiyang Liu, Fa-Ting Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25751v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, dynamic, head, avatar, human  
- **[Physics-Aware 3D Gaussian Editing for Driving Scene Generation](https://arxiv.org/abs/2605.25373v1)**  
  Authors: Feng Zhou, Jian Zhang, Yuhang Sun, He Wang, Qiong Wen, Debao Kong, Tieru Wu, Rui Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25373v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, geometry, autonomous driving, dynamic  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, geometry, sparse-view, motion  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, illumination, relighting, relightable, sparse-view, lighting  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, geometry, sparse-view, motion  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v2)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v2.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, ar, fast, deformation, sparse-view  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: outdoor, high-fidelity, 3d gaussian, gaussian splatting, sparse view, ar, fast, mapping, autonomous driving, illumination, dynamic, lighting  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: face, high-fidelity, 3d gaussian, gaussian splatting, ar, geometry, sparse-view  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, geometry, 3d reconstruction, sparse-view  
- **[PairDropGS: Paired Dropout-Induced Consistency Regularization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.12072v2)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Xingtao Wang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12072v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, geometry, sparse-view  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: face, gaussian splatting, ar, geometry, sparse-view  
- **[ConFixGS: Learning to Fix Feedforward 3D Gaussian Splatting with Confidence-Aware Diffusion Priors in Driving Scenes](https://arxiv.org/abs/2605.09688v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Xingcheng Zhou, Zewei Zhou, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09688v1.pdf)  
  Keywords: 3d gaussian, sparse-view, gaussian splatting, ar  
- **[FrameTwin: Curve-Anchored Gaussian Alignment from Sparse Views for Adaptive Wireframe 3D Printing](https://arxiv.org/abs/2605.09362v1)**  
  Authors: Wenting Wang, Zhuo Huang, Kun Qian, Neelotpal Dutta, Yuhu Guo, Yingjun Tian, Yeung Yam, Charlie C. L. Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09362v1.pdf)  
  Keywords: sparse view, ar, geometry, compact, deformation, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 392 papers*

- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, geometry, deformation  
- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: understanding, gaussian splatting, ar, geometry, semantic  
- **[Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation](https://arxiv.org/abs/2605.30855v1)**  
  Authors: Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30855v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, robotics, ar, fast, autonomous driving, 3d reconstruction  
- **[MonoPhysics: Estimating Geometry, Appearance, and Physical Parameters from Monocular Videos](https://arxiv.org/abs/2605.30320v1)**  
  Authors: Daniel Rho, Jun Myeong Choi, Matthew Thornton, Biswadip Dey, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30320v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://daniel03c1.github.io/MonoPhysics/)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ar  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, face, high-fidelity, gaussian splatting, ar, geometry, 3d reconstruction, large scene, urban scene  
- **[FRUC: Feedforward Dynamic Scene Reconstruction from Uncalibrated Collaborative Driving Views](https://arxiv.org/abs/2605.29997v1)**  
  Authors: Yihang Tao, Yu Guo, Zhengru Fang, Haonan An, Yuguang Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29997v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, geometry, dynamic  
- **[Learning Representations from 3D Gaussian Splats](https://arxiv.org/abs/2605.29549v1)**  
  Authors: Julia Farganus, Krzysztof Żurawicki, Arkadiusz Gaweł, Weronika Jakubowska, Halina Kwaśnicka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29549v1.pdf)  
  Keywords: understanding, 3d gaussian, ar, gaussian splatting, geometry  
- **[Comparative evaluation of photogrammetric reconstruction methods and 3D Gaussian Splatting for road surface roughness analysis](https://arxiv.org/abs/2605.29452v1)**  
  Authors: Marouane Elmegdar, Teng Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29452v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, segmentation, ar, geometry, 3d reconstruction  
- **[FreeForm: Reduced-Order Deformable Simulation from Particle-Based Skinning Eigenmodes](https://arxiv.org/abs/2605.29318v1)**  
  Authors: Donglai Xiang, Vismay Modi, Rishit Dagli, Ty Trusty, Gilles Daviet, Anka He Chen, Nicholas Sharp, David I. W. Levin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29318v1.pdf)  
  Keywords: geometry, dynamic, ar  

### Large Scene

- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, face, high-fidelity, gaussian splatting, ar, geometry, 3d reconstruction, large scene, urban scene  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, geometry, urban scene  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: outdoor, ar, mapping  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: outdoor, high-fidelity, 3d gaussian, gaussian splatting, sparse view, ar, fast, mapping, autonomous driving, illumination, dynamic, lighting  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: outdoor, efficient, face, high-fidelity, 3d gaussian, gaussian splatting, ar, geometry, dynamic  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: outdoor, 3d gaussian, gaussian splatting, ar, geometry  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: outdoor, 3d gaussian, gaussian splatting, ar  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: outdoor, 3d gaussian, gaussian splatting, ar, slam, mapping, localization  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, segmentation, ar, geometry, semantic, urban scene, compact  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, semantic, large scene  

### Model Compression

*Showing the latest 50 out of 428 papers*

- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: efficient, high-fidelity, gaussian splatting, robotics, ar, dynamic  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting, mapping  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, robotics, ar, fast, autonomous driving, 3d reconstruction  
- **[FRUC: Feedforward Dynamic Scene Reconstruction from Uncalibrated Collaborative Driving Views](https://arxiv.org/abs/2605.29997v1)**  
  Authors: Yihang Tao, Yu Guo, Zhengru Fang, Haonan An, Yuguang Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29997v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, geometry, dynamic  
- **[Smaller and Faster 3DGS via Post-Training Dictionary Learning](https://arxiv.org/abs/2605.30396v1)**  
  Authors: Jiarong Gong, Jonas Unger, Ehsan Miandji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30396v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar, fast, real-time rendering  
- **[BitC-3DGS: High-Capacity 3D Gaussian Splatting Watermarking via Bit Compression](https://arxiv.org/abs/2605.29583v1)**  
  Authors: Yuquan Bi, Baosheng Yu, Yingke Lei, Jianwei Yang, Hongsong Wang, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29583v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar, semantic  
- **[Eulerian Gaussian Splatting using Hashed Probability Pyramids](https://arxiv.org/abs/2605.29136v1)**  
  Authors: Mia Gaia Polansky, George Kopanas, Stephan Garbin, Todd Zickler, Dor Verbin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29136v1.pdf)  
  Keywords: efficient, nerf, 3d gaussian, gaussian splatting, ar, fast  
- **[GScomp-QA: A Subjective Dataset for Quality Assessment of Compressed Gaussian Splatting](https://arxiv.org/abs/2605.26880v1)**  
  Authors: Pedro Martin, António Rodrigues, João Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26880v1.pdf)  
  Keywords: efficient, compression, gaussian splatting, ar, 3d reconstruction  
- **[DelowlightSplat: Feed-Forward Gaussian Splatting for Lowlight 3D Scene Reconstruction](https://arxiv.org/abs/2605.26629v1)**  
  Authors: Fuzhen Jiang, Zengtian Xie, Zhuoran Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26629v1.pdf)  
  Keywords: vr, 3d gaussian, gaussian splatting, robotics, ar, lightweight, 3d reconstruction  
- **[R5DGS: Semantic-Aware 4D Gaussian Splatting with Rigid Body Constraints for Efficient Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.25909v1)**  
  Authors: Denis Gridusov, Maxim Popov, Sergey Kolyubin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25909v1.pdf)  
  Keywords: efficient, vr, body, gaussian splatting, ar, robotics, 4d, motion, semantic, dynamic, compact, head  

### Quality Enhancement

*Showing the latest 50 out of 240 papers*

- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: efficient, high-fidelity, gaussian splatting, robotics, ar, dynamic  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, face, high-fidelity, gaussian splatting, ar, geometry, 3d reconstruction, large scene, urban scene  
- **[POINav: Benchmarking and Enhancing Final-Meters Arrival in Real-World Vision-Language Navigation](https://arxiv.org/abs/2605.28237v1)**  
  Authors: Ruiyan Gong, Meisheng Zhang, Yuxiang Zhao, Mingchao Sun, Yanfen Shen, Zedong Chu, Zhining Gu, Wei Guo, Xiaolong Cheng, Qiming Li, Kangning Niu, Yanqing Zhu, Xiaolong Wu, Tianlun Li, Mu Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.28237v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: face, high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, 3d reconstruction, real-time rendering  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, illumination, relighting, relightable, sparse-view, lighting  
- **[Depth Peeling for High-Fidelity Gaussian-Enhanced Surfel Rendering](https://arxiv.org/abs/2605.25345v1)**  
  Authors: Keyang Ye, Hongzhi Wu, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25345v1.pdf)  
  Keywords: nerf, high-fidelity, 3d gaussian, gaussian splatting, ar  
- **[ParkingWorld: End-to-End Autonomous Parking Reinforcement Learning from Corrective Experience in 3DGS Simulation](https://arxiv.org/abs/2605.25029v2)**  
  Authors: Zhengcheng Yu, Changze Li, Haoran Liu, Tong Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25029v2.pdf)  
  Keywords: efficient, face, high-fidelity, 3d gaussian, gaussian splatting, ar, head, human  
- **[Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving](https://arxiv.org/abs/2605.22809v2)**  
  Authors: Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22809v2.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 4d, autonomous driving  
- **[4D-GSW: Kinematic-Aware Spatio-Temporal Consistent Watermarking for 4D Gaussian Splatting](https://arxiv.org/abs/2605.22342v1)**  
  Authors: Sifan Zhou, Hang Zhang, Yuhang Wang, Ming Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22342v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 4d, dynamic, deformation, motion  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v2)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, lightweight, 3d reconstruction, compact, head  

### Ray Tracing

- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ray casting, 3d gaussian, gaussian splatting, ar  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, geometry, ray tracing  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: efficient, tracking, 3d gaussian, gaussian splatting, robotics, ar, semantic, dynamic, ray tracing, lighting  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: face, gaussian splatting, ar, reflection, ray tracing  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: efficient, face, tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, localization, semantic, ray tracing  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: shadow, 3d gaussian, gaussian splatting, reflection, ar, mapping, ray tracing, relightable  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: efficient, nerf, face, high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, ray tracing, real-time rendering  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, mapping, survey, ray tracing  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: efficient, high-fidelity, 3d gaussian, gaussian splatting, ray marching, ar, real-time rendering  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, robotics, ar, fast, geometry, ray casting  

### Relighting

*Showing the latest 50 out of 135 papers*

- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, fast, geometry, illumination, relighting, relightable, sparse-view, lighting  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, segmentation, ar, semantic, head, human  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: compression, understanding, 3d gaussian, gaussian splatting, ar, human, motion, lighting  
- **[A Geometric Algebra-Informed 3DGS Framework for Wireless Channel Prediction](https://arxiv.org/abs/2605.19065v2)**  
  Authors: Jingzhou Shen, Tianya Zhao, Xuyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19065v2.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, reflection  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: face, high-fidelity, 3d gaussian, gaussian splatting, reflection, ar, real-time rendering  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: compression, 3d gaussian, ar, gaussian splatting, reflection  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: outdoor, high-fidelity, 3d gaussian, gaussian splatting, sparse view, ar, fast, mapping, autonomous driving, illumination, dynamic, lighting  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar, semantic, lighting  
- **[HarmoGS: Robust 3D Gaussian Splatting in the Wild via Conflict-Aware Gradient Harmonization](https://arxiv.org/abs/2605.13073v2)**  
  Authors: Yulei Kang, Tianze Zhu, Jian-Fang Hu, Jianhuang Lai, Wei-Shi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13073v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, illumination, semantic  
- **[TransmissiveGS: Residual-Guided Disentangled Gaussian Splatting for Transmissive Scene Reconstruction and Rendering](https://arxiv.org/abs/2605.10705v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Tianchao Li, Jack C. P. Cheng, Chi-Keung Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10705v1.pdf)  
  Keywords: face, high-fidelity, gaussian splatting, reflection, ar, geometry  

### SLAM

*Showing the latest 50 out of 146 papers*

- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, ar, slam, mapping, geometry, deformation  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting, mapping  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: 3d gaussian, gaussian splatting, ar, mapping, geometry, semantic, dynamic, motion, human  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: outdoor, ar, mapping  
- **[Efficient Sparse-to-Dense Visual Localization via Compact Gaussian Scene Representation and Accelerated Dense Pose Estimation](https://arxiv.org/abs/2605.17777v1)**  
  Authors: Zizhuo Li, Songchu Deng, Linfeng Tang, Jiayi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17777v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, localization, compact, head  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: outdoor, high-fidelity, 3d gaussian, gaussian splatting, sparse view, ar, fast, mapping, autonomous driving, illumination, dynamic, lighting  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: tracking, high-fidelity, gaussian splatting, ar, 4d, autonomous driving, dynamic  
- **[PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization](https://arxiv.org/abs/2605.12144v1)**  
  Authors: Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12144v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, lightweight, localization  
- **[MAGS-SLAM: Monocular Multi-Agent Gaussian Splatting SLAM for Geometrically and Photometrically Consistent Reconstruction](https://arxiv.org/abs/2605.10760v1)**  
  Authors: Zhihao Cao, Qi Shao, Shuhao Zhai, Jing Zhang, Anh Nguyen, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10760v1.pdf)  
  Keywords: tracking, high-fidelity, 3d gaussian, gaussian splatting, ar, slam, lightweight, mapping, geometry, 3d reconstruction, compact  
- **[PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.10307v1)**  
  Authors: Yinan Deng, Jianyu Dou, Jiahui Wang, Jingyu Zhao, Yi Yang, Yufeng Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10307v1.pdf)  
  Keywords: tracking, high-fidelity, gaussian splatting, segmentation, robotics, ar, fast, 4d, dynamic, deformation, motion  

### Scene Understanding

*Showing the latest 50 out of 222 papers*

- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: understanding, gaussian splatting, ar, geometry, semantic  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: 3d gaussian, ar, 4d, semantic, dynamic, motion, human  
- **[BitC-3DGS: High-Capacity 3D Gaussian Splatting Watermarking via Bit Compression](https://arxiv.org/abs/2605.29583v1)**  
  Authors: Yuquan Bi, Baosheng Yu, Yingke Lei, Jianwei Yang, Hongsong Wang, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29583v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar, semantic  
- **[Learning Representations from 3D Gaussian Splats](https://arxiv.org/abs/2605.29549v1)**  
  Authors: Julia Farganus, Krzysztof Żurawicki, Arkadiusz Gaweł, Weronika Jakubowska, Halina Kwaśnicka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29549v1.pdf)  
  Keywords: understanding, 3d gaussian, ar, gaussian splatting, geometry  
- **[Comparative evaluation of photogrammetric reconstruction methods and 3D Gaussian Splatting for road surface roughness analysis](https://arxiv.org/abs/2605.29452v1)**  
  Authors: Marouane Elmegdar, Teng Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29452v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, segmentation, ar, geometry, 3d reconstruction  
- **[TrackRef3D: Multi-View Consistent Track-then-Label for Open-World Referring Segmentation in 3D Gaussian Splatting](https://arxiv.org/abs/2605.26576v1)**  
  Authors: Yuyang Tan, Renhe Zhang, Hang Zhang, Ao Li, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26576v1.pdf)  
  Keywords: 3d gaussian, segmentation, gaussian splatting, ar, semantic  
- **[R5DGS: Semantic-Aware 4D Gaussian Splatting with Rigid Body Constraints for Efficient Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.25909v1)**  
  Authors: Denis Gridusov, Maxim Popov, Sergey Kolyubin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25909v1.pdf)  
  Keywords: efficient, vr, body, gaussian splatting, ar, robotics, 4d, motion, semantic, dynamic, compact, head  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, segmentation, ar, semantic, head, human  
- **[LangFlash: Feed-forward 3D Language Gaussian Splatting from Sparse Unposed Images](https://arxiv.org/abs/2605.23287v1)**  
  Authors: Yilong Liu, Wanhua Li, Chen Zhu-Tian, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.23287v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://liylo.github.io/langflash.github.io/.)  
  Keywords: understanding, gaussian splatting, ar, geometry, semantic, 3d reconstruction  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: compression, understanding, 3d gaussian, gaussian splatting, ar, human, motion, lighting  



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