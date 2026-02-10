# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-02-10 01:26:01

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

- [3DGS Surveys](#3dgs-surveys) (25 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (239 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (347 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (395 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (79 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (357 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (69 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (217 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (19 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (122 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (146 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (218 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: gaussian splatting, survey, ar, robotics, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: gaussian splatting, survey, geometry, nerf, ar, efficient, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: gaussian splatting, survey, 4d, compression, compact, dynamic, ar, efficient, 3d reconstruction, 3d gaussian, high-fidelity  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: gaussian splatting, survey, mapping, semantic, nerf, ar, localization, understanding, robotics, slam, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, robotics, semantic, ar, localization, efficient, slam, 3d gaussian, high-fidelity  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: gaussian splatting, survey, 4d, geometry, motion, nerf, ar, 3d gaussian, fast  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: gaussian splatting, survey, ar, efficient rendering, lighting, animation, real-time rendering, face, avatar, efficient, 3d reconstruction, 3d gaussian  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: gaussian splatting, survey, nerf, lightweight, ar, human, understanding, efficient  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, neural rendering, nerf, ar, understanding, efficient, slam, 3d gaussian, fast  

### Acceleration

*Showing the latest 50 out of 239 papers*

- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: gaussian splatting, body, dynamic, motion, ar, real-time rendering, human, high-fidelity  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, reflection, ar, real-time rendering, 3d gaussian  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: gaussian splatting, motion, nerf, sparse-view, ar, real-time rendering, 3d gaussian  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, real-time rendering, efficient, 3d gaussian, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, motion, ar, face, efficient, 3d gaussian, high-fidelity, fast  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: gaussian splatting, semantic, segmentation, ar, 3d gaussian, fast  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: gaussian splatting, geometry, ar, efficient, 3d reconstruction, fast  
- **[Learning Physics-Grounded 4D Dynamics with Neural Gaussian Force Fields](https://arxiv.org/abs/2602.00148v1)**  
  Authors: Shiqian Li, Ruihong Shen, Junfeng Ni, Chang Pan, Chi Zhang, Yixin Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00148v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, ar, 3d gaussian, fast  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: gaussian splatting, ray tracing, acceleration, ar, head, efficient, 3d gaussian  
- **[WaterClear-GS: Optical-Aware Gaussian Splatting for Underwater Reconstruction and Restoration](https://arxiv.org/abs/2601.19753v1)**  
  Authors: Xinrui Zhang, Yufeng Wang, Shuangkang Fang, Zesheng Wang, Dacheng Qi, Wenrui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19753v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://buaaxrzhang.github.io/WaterClear-GS/.)  
  Keywords: gaussian splatting, geometry, nerf, ar, real-time rendering, 3d reconstruction, 3d gaussian  

### Applications

*Showing the latest 50 out of 995 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[GaussianPOP: Principled Simplification Framework for Compact 3D Gaussian Splatting via Error Quantification](https://arxiv.org/abs/2602.06830v1)**  
  Authors: Soonbin Lee, Yeong-Gyu Kim, Simon Sasse, Tomas M. Borges, Yago Sanchez, Eun-Seok Ryu, Thomas Schierl, Cornelius Hellge  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06830v1.pdf)  
  Keywords: gaussian splatting, compact, ar, efficient, 3d gaussian  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, ar, face, animation, head, avatar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[NVS-HO: A Benchmark for Novel View Synthesis of Handheld Objects](https://arxiv.org/abs/2602.05822v1)**  
  Authors: Musawar Ali, Manuel Carranza-García, Nicola Fioraio, Samuele Salti, Luigi Di Stefano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05822v1.pdf)  
  Keywords: gaussian splatting, lighting, nerf, ar  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: gaussian splatting, body, dynamic, motion, ar, real-time rendering, human, high-fidelity  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, reflection, ar, real-time rendering, 3d gaussian  
- **[Nix and Fix: Targeting 1000x Compression of 3D Gaussian Splatting with Diffusion Models](https://arxiv.org/abs/2602.04549v1)**  
  Authors: Cem Eteke, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04549v1.pdf)  
  Keywords: gaussian splatting, compression, 3d gaussian, ar  
- **[VecSet-Edit: Unleashing Pre-trained LRM for Mesh Editing from Single Image](https://arxiv.org/abs/2602.04349v1)**  
  Authors: Teng-Fang Hsiao, Bo-Kai Ruan, Yu-Lun Liu, Hong-Han Shuai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04349v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, high-fidelity  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[AnyStyle: Single-Pass Multimodal Stylization for 3D Gaussian Splatting](https://arxiv.org/abs/2602.04043v1)**  
  Authors: Joanna Kaleta, Bartosz Świrta, Kacper Kania, Przemysław Spurek, Marek Kowalski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04043v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, 3d gaussian, ar  

### Avatar Generation

*Showing the latest 50 out of 347 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, ar, face, animation, head, avatar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: gaussian splatting, body, dynamic, motion, ar, real-time rendering, human, high-fidelity  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: body, dynamic, 3d gaussian, ar  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: gaussian splatting, geometry, ar, face, 3d reconstruction, 3d gaussian, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, motion, ar, face, efficient, 3d gaussian, high-fidelity, fast  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: gaussian splatting, body, tracking, vr, ar, head, avatar, 3d gaussian  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, large scene, ar, head, efficient, 3d gaussian  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: gaussian splatting, path tracing, vr, lightweight, ar, medical, head, understanding  

### Dynamic Scene

*Showing the latest 50 out of 395 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, ar, face, animation, head, avatar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: gaussian splatting, body, dynamic, motion, ar, real-time rendering, human, high-fidelity  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: gaussian splatting, 4d, compression, dynamic, motion, ar, high-fidelity  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: gaussian splatting, motion, nerf, sparse-view, ar, real-time rendering, 3d gaussian  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: body, dynamic, 3d gaussian, ar  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, real-time rendering, efficient, 3d gaussian, high-fidelity  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: gaussian splatting, mapping, geometry, dynamic, ar, deformation  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, motion, ar, face, efficient, 3d gaussian, high-fidelity, fast  

### Few-shot

*Showing the latest 50 out of 79 papers*

- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: gaussian splatting, motion, nerf, sparse-view, ar, real-time rendering, 3d gaussian  
- **[LoD-Structured 3D Gaussian Splatting for Streaming Video Reconstruction](https://arxiv.org/abs/2601.18475v1)**  
  Authors: Xinhui Liu, Can Wang, Lei Liu, Zhenghao Chen, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18475v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, sparse-view, ar, efficient, 3d gaussian, high-fidelity  
- **[LGDWT-GS: Local and Global Discrete Wavelet-Regularized 3D Gaussian Splatting for Sparse-View Scene Reconstruction](https://arxiv.org/abs/2601.17185v1)**  
  Authors: Shima Salehi, Atharva Agashe, Andrew J. McFarland, Joshua Peeples  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17185v1.pdf)  
  Keywords: gaussian splatting, geometry, sparse-view, few-shot, ar, 3d reconstruction, 3d gaussian  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: gaussian splatting, ar, sparse-view, efficient, 3d gaussian  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: gaussian splatting, neural rendering, robotics, sparse view, ar, efficient rendering, face, efficient, 3d reconstruction, 3d gaussian  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: gaussian splatting, ray marching, shadow, sparse-view, ar, efficient rendering, illumination, efficient, 3d reconstruction, 3d gaussian  
- **[COSMOS: Coherent Supergaussian Modeling with Spatial Priors for Sparse-View 3D Splatting](https://arxiv.org/abs/2602.06044v1)**  
  Authors: Chaeyoung Jeong, Kwangsu Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06044v1.pdf)  
  Keywords: gaussian splatting, sparse-view, segmentation, ar, 3d reconstruction, 3d gaussian  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: gaussian splatting, sparse view, motion, ar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: gaussian splatting, geometry, light transport, sparse-view, segmentation, lighting, relighting, ar  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: gaussian splatting, sparse-view, ar, efficient rendering, face, efficient, 3d reconstruction, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 357 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, ar, face, animation, head, avatar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, reflection, ar, real-time rendering, 3d gaussian  
- **[AnyStyle: Single-Pass Multimodal Stylization for 3D Gaussian Splatting](https://arxiv.org/abs/2602.04043v1)**  
  Authors: Joanna Kaleta, Bartosz Świrta, Kacper Kania, Przemysław Spurek, Marek Kowalski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04043v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: gaussian splatting, geometry, ar, face, 3d reconstruction, 3d gaussian, high-fidelity  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: gaussian splatting, mapping, geometry, dynamic, ar, deformation  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, ar, efficient, high-fidelity  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: geometry, shadow, nerf, ar, illumination, 3d reconstruction  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: gaussian splatting, geometry, ar, efficient, 3d reconstruction, fast  
- **[GVGS: Gaussian Visibility-Aware Multi-View Geometry for Accurate Surface Reconstruction](https://arxiv.org/abs/2601.20331v1)**  
  Authors: Mai Su, Qihan Yu, Zhongtao Wang, Yilong Li, Chengwei Pan, Yisong Chen, Guoping Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20331v1.pdf)  
  Keywords: gaussian splatting, geometry, ar, face, efficient, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 69 papers*

- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, large scene, ar, head, efficient, 3d gaussian  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, ar, urban scene, efficient, autonomous driving, 3d gaussian  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: gaussian splatting, compression, semantic, vr, segmentation, ar, 3d gaussian, outdoor  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: gaussian splatting, geometry, ar, face, illumination, urban scene, efficient, 3d reconstruction, 3d gaussian  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: gaussian splatting, geometry, compact, ar, 3d gaussian, outdoor, fast  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: gaussian splatting, 4d, robotics, dynamic, motion, nerf, ar, efficient, 3d gaussian, outdoor  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: gaussian splatting, geometry, ar, understanding, 3d reconstruction, 3d gaussian, outdoor  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: gaussian splatting, semantic, geometry, ar, outdoor, fast  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: gaussian splatting, outdoor, semantic, geometry, segmentation, ar, lighting, relighting, illumination, face, efficient, high-fidelity  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, geometry, ar, 3d gaussian, outdoor  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[GaussianPOP: Principled Simplification Framework for Compact 3D Gaussian Splatting via Error Quantification](https://arxiv.org/abs/2602.06830v1)**  
  Authors: Soonbin Lee, Yeong-Gyu Kim, Simon Sasse, Tomas M. Borges, Yago Sanchez, Eun-Seok Ryu, Thomas Schierl, Cornelius Hellge  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06830v1.pdf)  
  Keywords: gaussian splatting, compact, ar, efficient, 3d gaussian  
- **[Nix and Fix: Targeting 1000x Compression of 3D Gaussian Splatting with Diffusion Models](https://arxiv.org/abs/2602.04549v1)**  
  Authors: Cem Eteke, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04549v1.pdf)  
  Keywords: gaussian splatting, compression, 3d gaussian, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: gaussian splatting, 4d, compression, dynamic, motion, ar, high-fidelity  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, real-time rendering, efficient, 3d gaussian, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, motion, ar, face, efficient, 3d gaussian, high-fidelity, fast  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, ar, efficient, high-fidelity  
- **[HPC: Hierarchical Point-based Latent Representation for Streaming Dynamic Gaussian Splatting Compression](https://arxiv.org/abs/2602.00671v1)**  
  Authors: Yangzhi Ma, Bojun Liu, Wenting Liao, Dong Liu, Zhu Li, Li Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00671v1.pdf)  
  Keywords: gaussian splatting, compression, compact, dynamic, ar, efficient  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, large scene, ar, head, efficient, 3d gaussian  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: gaussian splatting, geometry, ar, efficient, 3d reconstruction, fast  

### Quality Enhancement

*Showing the latest 50 out of 217 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[From Blurry to Believable: Enhancing Low-quality Talking Heads with 3D Generative Priors](https://arxiv.org/abs/2602.06122v1)**  
  Authors: Ding-Jiun Huang, Yuanhao Wang, Shao-Ji Yuan, Albert Mosella-Montoro, Francisco Vicente Carrasco, Cheng Zhang, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06122v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, ar, face, animation, head, avatar, 3d reconstruction, 3d gaussian, high-fidelity  
- **[PoseGaussian: Pose-Driven Novel View Synthesis for Robust 3D Human Reconstruction](https://arxiv.org/abs/2602.05190v1)**  
  Authors: Ju Shen, Chen Chen, Tam V. Nguyen, Vijayan K. Asari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05190v1.pdf)  
  Keywords: gaussian splatting, body, dynamic, motion, ar, real-time rendering, human, high-fidelity  
- **[VecSet-Edit: Unleashing Pre-trained LRM for Mesh Editing from Single Image](https://arxiv.org/abs/2602.04349v1)**  
  Authors: Teng-Fang Hsiao, Bo-Kai Ruan, Yu-Lun Liu, Hong-Han Shuai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04349v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, high-fidelity  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: gaussian splatting, 4d, compression, dynamic, motion, ar, high-fidelity  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, real-time rendering, efficient, 3d gaussian, high-fidelity  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: gaussian splatting, geometry, ar, face, 3d reconstruction, 3d gaussian, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: gaussian splatting, 4d, dynamic, motion, ar, face, efficient, 3d gaussian, high-fidelity, fast  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, ar, efficient, high-fidelity  
- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: gaussian splatting, ar, lighting, 3d gaussian, high-fidelity  

### Ray Tracing

- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: gaussian splatting, ray tracing, 3d gaussian, ar  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: gaussian splatting, path tracing, vr, lightweight, ar, medical, head, understanding  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: gaussian splatting, ray tracing, acceleration, ar, head, efficient, 3d gaussian  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: gaussian splatting, ray marching, shadow, sparse-view, ar, efficient rendering, illumination, efficient, 3d reconstruction, 3d gaussian  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, ray tracing, geometry, motion, ar, understanding, 3d reconstruction, 3d gaussian, fast  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: gaussian splatting, ray tracing, geometry, relightable, ar, relighting, lighting, 3d reconstruction  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: gaussian splatting, ray tracing, nerf, ar, face, 3d gaussian, fast  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: gaussian splatting, ray tracing, compact, ar, real-time rendering, 3d gaussian, high-fidelity, fast  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: gaussian splatting, ray tracing, geometry, dynamic, reflection, ar, 3d reconstruction, high-fidelity  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: gaussian splatting, ray tracing, geometry, reflection, ar, illumination  

### Relighting

*Showing the latest 50 out of 122 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[NVS-HO: A Benchmark for Novel View Synthesis of Handheld Objects](https://arxiv.org/abs/2602.05822v1)**  
  Authors: Musawar Ali, Manuel Carranza-García, Nicola Fioraio, Samuele Salti, Luigi Di Stefano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05822v1.pdf)  
  Keywords: gaussian splatting, lighting, nerf, ar  
- **[QuantumGS: Quantum Encoding Framework for Gaussian Splatting](https://arxiv.org/abs/2602.05047v1)**  
  Authors: Grzegorz Wilczyński, Rafał Tobiasz, Paweł Gora, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.05047v1.pdf)  
  Keywords: gaussian splatting, neural rendering, geometry, reflection, ar, real-time rendering, 3d gaussian  
- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: gaussian splatting, ar, lighting, 3d gaussian, high-fidelity  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: geometry, shadow, nerf, ar, illumination, 3d reconstruction  
- **[Mirage2Matter: A Physically Grounded Gaussian World Model from Video](https://arxiv.org/abs/2602.00096v1)**  
  Authors: Zhengqing Gao, Ziwen Li, Xin Wang, Jiaxin Huang, Zhenyang Ren, Mingkai Shao, Hanlue Zhang, Tianyu Huang, Yongkang Cheng, Yandong Guo, Runqi Lin, Yuanyuan Wang, Tongliang Liu, Kun Zhang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00096v1.pdf)  
  Keywords: gaussian splatting, geometry, ar, lighting, efficient, 3d gaussian, high-fidelity  
- **[ThermoSplat: Cross-Modal 3D Gaussian Splatting with Feature Modulation and Geometry Decoupling](https://arxiv.org/abs/2601.15897v1)**  
  Authors: Zhaoqi Su, Shihai Chen, Xinyan Lin, Liqin Huang, Zhipeng Su, Xiaoqiang Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15897v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, dynamic, ar, lighting, 3d gaussian  
- **[LL-GaussianMap: Zero-shot Low-Light Image Enhancement via 2D Gaussian Splatting Guided Gain Maps](https://arxiv.org/abs/2601.15766v2)**  
  Authors: Yuhan Chen, Ying Fang, Guofa Li, Wenxuan Yu, Yicui Shi, Jingrui Zhang, Kefei Qian, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15766v2.pdf)  
  Keywords: gaussian splatting, ar, lighting, efficient, high-fidelity  
- **[SplatBus: A Gaussian Splatting Viewer Framework via GPU Interprocess Communication](https://arxiv.org/abs/2601.15431v1)**  
  Authors: Yinghan Xu, Théo Morales, John Dingliana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15431v1.pdf)  
  Keywords: gaussian splatting, ar, lighting, real-time rendering, robotics, autonomous driving, 3d gaussian, high-fidelity  
- **[LuxRemix: Lighting Decomposition and Remixing for Indoor Scenes](https://arxiv.org/abs/2601.15283v1)**  
  Authors: Ruofan Liang, Norman Müller, Ethan Weber, Duncan Zauss, Nandita Vijaykumar, Peter Kontschieder, Christian Richardt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luxremix.github.io.)  
  Keywords: gaussian splatting, relightable, ar, relighting, lighting, illumination, 3d gaussian  

### SLAM

*Showing the latest 50 out of 146 papers*

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, survey, mapping, motion, dynamic, tracking, ar, face, localization, efficient, slam, 3d gaussian  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: gaussian splatting, mapping, geometry, dynamic, ar, deformation  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: gaussian splatting, body, tracking, vr, ar, head, avatar, 3d gaussian  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v2)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v2.pdf)  
  Keywords: gaussian splatting, compression, mapping, nerf, ar, real-time rendering, efficient  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: gaussian splatting, neural rendering, mapping, semantic, geometry, dynamic, lightweight, ar, lighting, face, illumination, 3d reconstruction, 3d gaussian, high-fidelity  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: gaussian splatting, mapping, robotics, semantic, segmentation, ar, lighting, efficient, 3d reconstruction, 3d gaussian, high-fidelity  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: gaussian splatting, mapping, compact, lightweight, ar, efficient, 3d gaussian  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: gaussian splatting, mapping, semantic, tracking, segmentation, ar, efficient, slam, 3d gaussian  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, motion, compact, tracking, segmentation, ar, real-time rendering, efficient, deformation, high-fidelity, fast  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, segmentation, ar, localization, understanding, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 218 papers*

- **[DynFOA: Generating First-Order Ambisonics with Conditional Diffusion for Dynamic and Acoustically Complex 360-Degree Videos](https://arxiv.org/abs/2602.06846v1)**  
  Authors: Ziyu Luo, Lin Chen, Qiang Qu, Xiaoming Chen, Yiran Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06846v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, motion, vr, reflection, ar, head, 3d gaussian, high-fidelity  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, ar, efficient, high-fidelity  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: gaussian splatting, semantic, segmentation, ar, 3d gaussian, fast  
- **[PSGS: Text-driven Panorama Sliding Scene Generation via Gaussian Splatting](https://arxiv.org/abs/2602.00463v1)**  
  Authors: Xin Zhang, Shen Chen, Jiale Zhou, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00463v1.pdf)  
  Keywords: gaussian splatting, semantic, vr, ar, 3d gaussian, high-fidelity  
- **[Learning Geometrically-Grounded 3D Visual Representations for View-Generalizable Robotic Manipulation](https://arxiv.org/abs/2601.22988v1)**  
  Authors: Di Zhang, Weicheng Duan, Dasen Gu, Hongye Lu, Hai Zhang, Hang Yu, Junqiao Zhao, Guang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22988v1.pdf)  
  Keywords: gaussian splatting, ar, understanding  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: gaussian splatting, path tracing, vr, lightweight, ar, medical, head, understanding  
- **[TIGaussian: Disentangle Gaussians for Spatial-Awared Text-Image-3D Alignment](https://arxiv.org/abs/2601.19247v1)**  
  Authors: Jiarun Liu, Qifeng Chen, Yiru Zhao, Minghua Liu, Baorui Ma, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19247v1.pdf)  
  Keywords: gaussian splatting, compact, recognition, ar, 3d gaussian  
- **[Bridging Visual and Wireless Sensing: A Unified Radiation Field for 3D Radio Map Construction](https://arxiv.org/abs/2601.19216v1)**  
  Authors: Chaozheng Wen, Jingwen Tong, Zehong Lin, Chenghong Bian, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19216v1.pdf)  
  Keywords: gaussian splatting, geometry, nerf, ar, understanding, 3d gaussian, high-fidelity  
- **[ExoGS: A 4D Real-to-Sim-to-Real Framework for Scalable Manipulation Data Collection](https://arxiv.org/abs/2601.18629v1)**  
  Authors: Yiming Wang, Ruogu Zhang, Minyang Li, Hao Shi, Junbo Wang, Deyi Li, Jieji Ren, Wenhai Liu, Weiming Wang, Hao-Shu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18629v1.pdf)  
  Keywords: gaussian splatting, 4d, semantic, geometry, dynamic, lightweight, ar, human, efficient, 3d gaussian  
- **[A Step to Decouple Optimization in 3DGS](https://arxiv.org/abs/2601.16736v2)**  
  Authors: Renjie Ding, Yaonan Wang, Min Liu, Jialin Zhu, Jiazheng Wang, Jiahao Zhao, Wenting Shen, Feixiang He, Xiang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.16736v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, understanding  



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