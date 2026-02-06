# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-02-06 01:10:30

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
- [Acceleration](#acceleration) (240 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (345 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (394 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (79 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (357 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (69 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (418 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (214 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (19 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (120 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (217 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, gaussian splatting, ar, 3d gaussian, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: geometry, survey, gaussian splatting, ar, 3d gaussian, efficient, nerf  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d reconstruction, compact, survey, gaussian splatting, dynamic, ar, 3d gaussian, efficient, 4d, compression, high-fidelity  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: localization, understanding, survey, gaussian splatting, slam, 3d gaussian, ar, semantic, robotics, nerf, mapping  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: localization, survey, gaussian splatting, slam, efficient, 3d gaussian, ar, semantic, robotics, mapping, high-fidelity  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: geometry, fast, motion, survey, gaussian splatting, ar, 3d gaussian, 4d, nerf  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: 3d reconstruction, real-time rendering, survey, gaussian splatting, ar, 3d gaussian, animation, efficient rendering, efficient, face, lighting, avatar  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: understanding, survey, gaussian splatting, ar, efficient, lightweight, nerf, human  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: neural rendering, fast, understanding, survey, gaussian splatting, slam, 3d gaussian, efficient, ar, nerf  

### Acceleration

*Showing the latest 50 out of 240 papers*

- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, sparse-view, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: fast, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, face, high-fidelity  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: fast, gaussian splatting, ar, 3d gaussian, semantic, segmentation  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: geometry, fast, 3d reconstruction, gaussian splatting, ar, efficient  
- **[Learning Physics-Grounded 4D Dynamics with Neural Gaussian Force Fields](https://arxiv.org/abs/2602.00148v1)**  
  Authors: Shiqian Li, Ruihong Shen, Junfeng Ni, Chang Pan, Chi Zhang, Yixin Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00148v1.pdf)  
  Keywords: fast, dynamic, gaussian splatting, ar, 3d gaussian, 4d  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: acceleration, ray tracing, gaussian splatting, ar, efficient, 3d gaussian, head  
- **[WaterClear-GS: Optical-Aware Gaussian Splatting for Underwater Reconstruction and Restoration](https://arxiv.org/abs/2601.19753v1)**  
  Authors: Xinrui Zhang, Yufeng Wang, Shuangkang Fang, Zesheng Wang, Dacheng Qi, Wenrui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19753v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://buaaxrzhang.github.io/WaterClear-GS/.)  
  Keywords: geometry, 3d reconstruction, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[Advancing Structured Priors for Sparse-Voxel Surface Reconstruction](https://arxiv.org/abs/2601.17720v1)**  
  Authors: Ting-Hsun Chi, Chu-Rong Chen, Chi-Tun Hsu, Hsuan-Ting Lin, Sheng-Yu Huang, Cheng Sun, Yu-Chiang Frank Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17720v1.pdf)  
  Keywords: geometry, fast, gaussian splatting, ar, 3d gaussian, face  
- **[SplatBus: A Gaussian Splatting Viewer Framework via GPU Interprocess Communication](https://arxiv.org/abs/2601.15431v1)**  
  Authors: Yinghan Xu, Théo Morales, John Dingliana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15431v1.pdf)  
  Keywords: autonomous driving, real-time rendering, gaussian splatting, ar, 3d gaussian, robotics, lighting, high-fidelity  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Nix and Fix: Targeting 1000x Compression of 3D Gaussian Splatting with Diffusion Models](https://arxiv.org/abs/2602.04549v1)**  
  Authors: Cem Eteke, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04549v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar  
- **[VecSet-Edit: Unleashing Pre-trained LRM for Mesh Editing from Single Image](https://arxiv.org/abs/2602.04349v1)**  
  Authors: Teng-Fang Hsiao, Bo-Kai Ruan, Yu-Lun Liu, Hong-Han Shuai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04349v1.pdf)  
  Keywords: ar, 3d gaussian, high-fidelity, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[AnyStyle: Single-Pass Multimodal Stylization for 3D Gaussian Splatting](https://arxiv.org/abs/2602.04043v1)**  
  Authors: Joanna Kaleta, Bartosz Świrta, Kacper Kania, Przemysław Spurek, Marek Kowalski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04043v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, gaussian splatting  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: motion, dynamic, gaussian splatting, ar, 4d, compression, high-fidelity  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, sparse-view, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: body, 3d gaussian, dynamic, ar  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, gaussian splatting, ar, 3d gaussian, robotics  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, 3d gaussian, face, high-fidelity  

### Avatar Generation

*Showing the latest 50 out of 345 papers*

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: body, 3d gaussian, dynamic, ar  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, 3d gaussian, face, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: fast, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, face, high-fidelity  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: gaussian splatting, vr, ar, 3d gaussian, head, tracking, body, avatar  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian, head, large scene  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: path tracing, understanding, gaussian splatting, ar, medical, head, lightweight, vr  
- **[FreeFix: Boosting 3D Gaussian Splatting via Fine-Tuning-Free Diffusion Models](https://arxiv.org/abs/2601.20857v1)**  
  Authors: Hongyu Zhou, Zisen Shao, Sheng Miao, Pan Wang, Dongfeng Bai, Bingbing Liu, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20857v1.pdf)  
  Keywords: ar, 3d gaussian, face, gaussian splatting  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: acceleration, ray tracing, gaussian splatting, ar, efficient, 3d gaussian, head  
- **[GVGS: Gaussian Visibility-Aware Multi-View Geometry for Accurate Surface Reconstruction](https://arxiv.org/abs/2601.20331v1)**  
  Authors: Mai Su, Qihan Yu, Zhongtao Wang, Yilong Li, Chengwei Pan, Yisong Chen, Guoping Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20331v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, 3d gaussian, face  

### Dynamic Scene

*Showing the latest 50 out of 394 papers*

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: motion, dynamic, gaussian splatting, ar, 4d, compression, high-fidelity  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, sparse-view, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402v1)**  
  Authors: Mu Huang, Hui Wang, Kerui Ren, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02402v1.pdf)  
  Keywords: body, 3d gaussian, dynamic, ar  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar, mapping, deformation  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: fast, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, face, high-fidelity  
- **[HPC: Hierarchical Point-based Latent Representation for Streaming Dynamic Gaussian Splatting Compression](https://arxiv.org/abs/2602.00671v1)**  
  Authors: Yangzhi Ma, Bojun Liu, Wenting Liao, Dong Liu, Zhu Li, Li Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00671v1.pdf)  
  Keywords: compact, dynamic, gaussian splatting, ar, efficient, compression  
- **[Learning Physics-Grounded 4D Dynamics with Neural Gaussian Force Fields](https://arxiv.org/abs/2602.00148v1)**  
  Authors: Shiqian Li, Ruihong Shen, Junfeng Ni, Chang Pan, Chi Zhang, Yixin Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00148v1.pdf)  
  Keywords: fast, dynamic, gaussian splatting, ar, 3d gaussian, 4d  
- **[Graphical X Splatting (GraphiXS): A Graphical Model for 4D Gaussian Splatting under Uncertainty](https://arxiv.org/abs/2601.19843v1)**  
  Authors: Doga Yilmaz, Jialin Zhu, Deshan Gong, He Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19843v1.pdf)  
  Keywords: neural rendering, 4d, gaussian splatting, ar  

### Few-shot

*Showing the latest 50 out of 79 papers*

- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: motion, sparse-view, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[LoD-Structured 3D Gaussian Splatting for Streaming Video Reconstruction](https://arxiv.org/abs/2601.18475v1)**  
  Authors: Xinhui Liu, Can Wang, Lei Liu, Zhenghao Chen, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18475v1.pdf)  
  Keywords: motion, sparse-view, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[LGDWT-GS: Local and Global Discrete Wavelet-Regularized 3D Gaussian Splatting for Sparse-View Scene Reconstruction](https://arxiv.org/abs/2601.17185v1)**  
  Authors: Shima Salehi, Atharva Agashe, Andrew J. McFarland, Joshua Peeples  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17185v1.pdf)  
  Keywords: geometry, 3d reconstruction, sparse-view, gaussian splatting, ar, 3d gaussian, few-shot  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: sparse-view, gaussian splatting, ar, efficient, 3d gaussian  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: neural rendering, 3d reconstruction, gaussian splatting, ar, 3d gaussian, efficient, efficient rendering, face, sparse view, robotics  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, 3d reconstruction, sparse-view, ray marching, gaussian splatting, shadow, ar, 3d gaussian, efficient, efficient rendering  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, motion, gaussian splatting, ar, 3d gaussian, sparse view, high-fidelity  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: geometry, sparse-view, gaussian splatting, ar, segmentation, light transport, relighting, lighting  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, sparse-view, gaussian splatting, ar, 3d gaussian, efficient, efficient rendering, face  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: sparse-view, dynamic, gaussian splatting, ar, 3d gaussian, face, deformation  

### Geometry Reconstruction

*Showing the latest 50 out of 357 papers*

- **[AnyStyle: Single-Pass Multimodal Stylization for 3D Gaussian Splatting](https://arxiv.org/abs/2602.04043v1)**  
  Authors: Joanna Kaleta, Bartosz Świrta, Kacper Kania, Przemysław Spurek, Marek Kowalski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04043v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, gaussian splatting  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, 3d gaussian, face, high-fidelity  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar, mapping, deformation  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, semantic, high-fidelity  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: geometry, illumination, 3d reconstruction, shadow, ar, nerf  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: geometry, fast, 3d reconstruction, gaussian splatting, ar, efficient  
- **[GVGS: Gaussian Visibility-Aware Multi-View Geometry for Accurate Surface Reconstruction](https://arxiv.org/abs/2601.20331v1)**  
  Authors: Mai Su, Qihan Yu, Zhongtao Wang, Yilong Li, Chengwei Pan, Yisong Chen, Guoping Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20331v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, 3d gaussian, face  
- **[WaterClear-GS: Optical-Aware Gaussian Splatting for Underwater Reconstruction and Restoration](https://arxiv.org/abs/2601.19753v1)**  
  Authors: Xinrui Zhang, Yufeng Wang, Shuangkang Fang, Zesheng Wang, Dacheng Qi, Wenrui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19753v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://buaaxrzhang.github.io/WaterClear-GS/.)  
  Keywords: geometry, 3d reconstruction, real-time rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[Bridging Visual and Wireless Sensing: A Unified Radiation Field for 3D Radio Map Construction](https://arxiv.org/abs/2601.19216v1)**  
  Authors: Chaozheng Wen, Jingwen Tong, Zehong Lin, Chenghong Bian, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19216v1.pdf)  
  Keywords: geometry, understanding, gaussian splatting, ar, 3d gaussian, nerf, high-fidelity  
- **[Splat-Portrait: Generalizing Talking Heads with Gaussian Splatting](https://arxiv.org/abs/2601.18633v1)**  
  Authors: Tong Shi, Melonie de Almeida, Daniela Ivanova, Nicolas Pugeault, Paul Henderson  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18633v1.pdf)  
  Keywords: 3d reconstruction, motion, gaussian splatting, ar, animation, head, avatar  

### Large Scene

*Showing the latest 50 out of 69 papers*

- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian, head, large scene  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: geometry, autonomous driving, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, semantic, urban scene  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: gaussian splatting, vr, ar, 3d gaussian, semantic, segmentation, compression, outdoor  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: geometry, illumination, 3d reconstruction, gaussian splatting, ar, 3d gaussian, efficient, face, urban scene  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: geometry, fast, compact, gaussian splatting, ar, 3d gaussian, outdoor  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, robotics, nerf, outdoor  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: geometry, 3d reconstruction, understanding, gaussian splatting, ar, 3d gaussian, outdoor  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: geometry, fast, gaussian splatting, ar, semantic, outdoor  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, illumination, outdoor, gaussian splatting, ar, efficient, face, semantic, segmentation, lighting, high-fidelity, relighting  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, 3d gaussian, high-fidelity, outdoor  

### Model Compression

*Showing the latest 50 out of 418 papers*

- **[Nix and Fix: Targeting 1000x Compression of 3D Gaussian Splatting with Diffusion Models](https://arxiv.org/abs/2602.04549v1)**  
  Authors: Cem Eteke, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04549v1.pdf)  
  Keywords: compression, 3d gaussian, gaussian splatting, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: motion, dynamic, gaussian splatting, ar, 4d, compression, high-fidelity  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: fast, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, face, high-fidelity  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, semantic, high-fidelity  
- **[HPC: Hierarchical Point-based Latent Representation for Streaming Dynamic Gaussian Splatting Compression](https://arxiv.org/abs/2602.00671v1)**  
  Authors: Yangzhi Ma, Bojun Liu, Wenting Liao, Dong Liu, Zhu Li, Li Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00671v1.pdf)  
  Keywords: compact, dynamic, gaussian splatting, ar, efficient, compression  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian, head, large scene  
- **[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046v2)**  
  Authors: Changjian Jiang, Kerui Ren, Xudong Li, Kaiwen Song, Linning Xu, Tao Lu, Junting Dong, Yu Zhang, Bo Dai, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22046v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://city-super.github.io/PLANING/)  
  Keywords: geometry, fast, 3d reconstruction, gaussian splatting, ar, efficient  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: path tracing, understanding, gaussian splatting, ar, medical, head, lightweight, vr  

### Quality Enhancement

*Showing the latest 50 out of 214 papers*

- **[VecSet-Edit: Unleashing Pre-trained LRM for Mesh Editing from Single Image](https://arxiv.org/abs/2602.04349v1)**  
  Authors: Teng-Fang Hsiao, Bo-Kai Ruan, Yu-Lun Liu, Hong-Han Shuai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04349v1.pdf)  
  Keywords: ar, 3d gaussian, high-fidelity, gaussian splatting  
- **[Constrained Dynamic Gaussian Splatting](https://arxiv.org/abs/2602.03538v1)**  
  Authors: Zihan Zheng, Zhenglong Wu, Xuanxuan Wang, Houqiang Zhong, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03538v1.pdf)  
  Keywords: motion, dynamic, gaussian splatting, ar, 4d, compression, high-fidelity  
- **[UrbanGS: A Scalable and Efficient Architecture for Geometrically Accurate Large-Scene Reconstruction](https://arxiv.org/abs/2602.02089v1)**  
  Authors: Changbai Li, Haodong Zhu, Hanlin Chen, Xiuping Liang, Tongfei Chen, Shuwei Shao, Linlin Yang, Huobin Tan, Baochang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02089v1.pdf)  
  Keywords: real-time rendering, dynamic, gaussian splatting, ar, 3d gaussian, efficient, high-fidelity  
- **[SurfSplat: Conquering Feedforward 2D Gaussian Splatting with Surface Continuity Priors](https://arxiv.org/abs/2602.02000v2)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Ning Cao, Gang Chen, Zhengxue Cheng, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02000v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hebing-sjtu.github.io/SurfSplat-website/)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, 3d gaussian, face, high-fidelity  
- **[FastPhysGS: Accelerating Physics-based Dynamic 3DGS Simulation via Interior Completion and Adaptive Optimization](https://arxiv.org/abs/2602.01723v1)**  
  Authors: Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01723v1.pdf)  
  Keywords: fast, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, face, high-fidelity  
- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, semantic, high-fidelity  
- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, lighting, high-fidelity  
- **[PSGS: Text-driven Panorama Sliding Scene Generation via Gaussian Splatting](https://arxiv.org/abs/2602.00463v1)**  
  Authors: Xin Zhang, Shen Chen, Jiale Zhou, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00463v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, semantic, vr, high-fidelity  
- **[ClipGS-VR: Immersive and Interactive Cinematic Visualization of Volumetric Medical Data in Mobile Virtual Reality](https://arxiv.org/abs/2601.19310v1)**  
  Authors: Yuqi Tong, Ruiyang Li, Chengkun Li, Qixuan Liu, Shi Qiu, Pheng-Ann Heng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19310v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, medical, head, vr, high-fidelity  
- **[Bridging Visual and Wireless Sensing: A Unified Radiation Field for 3D Radio Map Construction](https://arxiv.org/abs/2601.19216v1)**  
  Authors: Chaozheng Wen, Jingwen Tong, Zehong Lin, Chenghong Bian, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19216v1.pdf)  
  Keywords: geometry, understanding, gaussian splatting, ar, 3d gaussian, nerf, high-fidelity  

### Ray Tracing

- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: ar, 3d gaussian, ray tracing, gaussian splatting  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: path tracing, understanding, gaussian splatting, ar, medical, head, lightweight, vr  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: acceleration, ray tracing, gaussian splatting, ar, efficient, 3d gaussian, head  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, 3d reconstruction, sparse-view, ray marching, gaussian splatting, shadow, ar, 3d gaussian, efficient, efficient rendering  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: geometry, fast, 3d reconstruction, motion, ray tracing, understanding, gaussian splatting, ar, 3d gaussian  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: geometry, 3d reconstruction, ray tracing, gaussian splatting, ar, lighting, relightable, relighting  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: fast, ray tracing, gaussian splatting, ar, 3d gaussian, face, nerf  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: fast, ray tracing, real-time rendering, compact, gaussian splatting, ar, 3d gaussian, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: geometry, 3d reconstruction, ray tracing, gaussian splatting, dynamic, ar, high-fidelity, reflection  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: geometry, illumination, ray tracing, gaussian splatting, ar, reflection  

### Relighting

*Showing the latest 50 out of 120 papers*

- **[Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit](https://arxiv.org/abs/2602.02602v1)**  
  Authors: Yangfan Deng, Anirudh Nakra, Min Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.02602v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, lighting, high-fidelity  
- **[Diachronic Stereo Matching for Multi-Date Satellite Imagery](https://arxiv.org/abs/2601.22808v1)**  
  Authors: Elías Masquil, Luca Savant Aira, Roger Marí, Thibaud Ehret, Pablo Musé, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22808v1.pdf)  
  Keywords: geometry, illumination, 3d reconstruction, shadow, ar, nerf  
- **[Mirage2Matter: A Physically Grounded Gaussian World Model from Video](https://arxiv.org/abs/2602.00096v1)**  
  Authors: Zhengqing Gao, Ziwen Li, Xin Wang, Jiaxin Huang, Zhenyang Ren, Mingkai Shao, Hanlue Zhang, Tianyu Huang, Yongkang Cheng, Yandong Guo, Runqi Lin, Yuanyuan Wang, Tongliang Liu, Kun Zhang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00096v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, 3d gaussian, efficient, lighting, high-fidelity  
- **[ThermoSplat: Cross-Modal 3D Gaussian Splatting with Feature Modulation and Geometry Decoupling](https://arxiv.org/abs/2601.15897v1)**  
  Authors: Zhaoqi Su, Shihai Chen, Xinyan Lin, Liqin Huang, Zhipeng Su, Xiaoqiang Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15897v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar, 3d gaussian, semantic, lighting  
- **[LL-GaussianMap: Zero-shot Low-Light Image Enhancement via 2D Gaussian Splatting Guided Gain Maps](https://arxiv.org/abs/2601.15766v2)**  
  Authors: Yuhan Chen, Ying Fang, Guofa Li, Wenxuan Yu, Yicui Shi, Jingrui Zhang, Kefei Qian, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15766v2.pdf)  
  Keywords: gaussian splatting, ar, efficient, lighting, high-fidelity  
- **[SplatBus: A Gaussian Splatting Viewer Framework via GPU Interprocess Communication](https://arxiv.org/abs/2601.15431v1)**  
  Authors: Yinghan Xu, Théo Morales, John Dingliana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15431v1.pdf)  
  Keywords: autonomous driving, real-time rendering, gaussian splatting, ar, 3d gaussian, robotics, lighting, high-fidelity  
- **[LuxRemix: Lighting Decomposition and Remixing for Indoor Scenes](https://arxiv.org/abs/2601.15283v1)**  
  Authors: Ruofan Liang, Norman Müller, Ethan Weber, Duncan Zauss, Nandita Vijaykumar, Peter Kontschieder, Christian Richardt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luxremix.github.io.)  
  Keywords: illumination, gaussian splatting, ar, 3d gaussian, lighting, relightable, relighting  
- **[POTR: Post-Training 3DGS Compression](https://arxiv.org/abs/2601.14821v1)**  
  Authors: Bert Ramlot, Martijn Courteaux, Peter Lambert, Glenn Van Wallendael  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14821v1.pdf)  
  Keywords: fast, compression, gaussian splatting, ar, 3d gaussian, efficient, nerf, lighting  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: neural rendering, illumination, 3d reconstruction, geometry, gaussian splatting, dynamic, ar, 3d gaussian, face, semantic, lightweight, lighting, high-fidelity, mapping  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, ar, 3d gaussian, efficient, semantic, segmentation, robotics, lighting, high-fidelity, mapping  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, localization, survey, dynamic, gaussian splatting, slam, 3d gaussian, efficient, face, ar, tracking, mapping  
- **[CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions](https://arxiv.org/abs/2602.01844v1)**  
  Authors: Yuliang Zhan, Jian Li, Wenbing Huang, Wenbing Huang, Yang Liu, Hao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01844v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar, mapping, deformation  
- **[VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR](https://arxiv.org/abs/2602.01674v1)**  
  Authors: Hail Song, Boram Yoon, Seokhwan Yang, Seoyoung Kang, Hyunjeong Kim, Henning Metzmacher, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01674v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vrgaussianavatar.github.io.)  
  Keywords: gaussian splatting, vr, ar, 3d gaussian, head, tracking, body, avatar  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v2)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v2.pdf)  
  Keywords: compression, real-time rendering, gaussian splatting, ar, efficient, nerf, mapping  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: neural rendering, illumination, 3d reconstruction, geometry, gaussian splatting, dynamic, ar, 3d gaussian, face, semantic, lightweight, lighting, high-fidelity, mapping  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, ar, 3d gaussian, efficient, semantic, segmentation, robotics, lighting, high-fidelity, mapping  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: compact, gaussian splatting, ar, efficient, 3d gaussian, lightweight, mapping  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: gaussian splatting, slam, efficient, 3d gaussian, ar, semantic, segmentation, tracking, mapping  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: deformation, geometry, fast, motion, real-time rendering, compact, gaussian splatting, dynamic, ar, efficient, segmentation, tracking, high-fidelity  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: geometry, localization, understanding, gaussian splatting, ar, 3d gaussian, semantic, segmentation  

### Scene Understanding

*Showing the latest 50 out of 217 papers*

- **[MarkCleaner: High-Fidelity Watermark Removal via Imperceptible Micro-Geometric Perturbation](https://arxiv.org/abs/2602.01513v1)**  
  Authors: Xiaoxi Kong, Jieyu Yuan, Pengdi Chen, Yuanlin Zhang, Chongyi Li, Bin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01513v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, efficient, semantic, high-fidelity  
- **[Split&Splat: Zero-Shot Panoptic Segmentation via Explicit Instance Modeling and 3D Gaussian Splatting](https://arxiv.org/abs/2602.03809v1)**  
  Authors: Leonardo Monchieri, Elena Camuffo, Francesco Barbato, Pietro Zanuttigh, Simone Milani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03809v1.pdf)  
  Keywords: fast, gaussian splatting, ar, 3d gaussian, semantic, segmentation  
- **[PSGS: Text-driven Panorama Sliding Scene Generation via Gaussian Splatting](https://arxiv.org/abs/2602.00463v1)**  
  Authors: Xin Zhang, Shen Chen, Jiale Zhou, Lei Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00463v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, semantic, vr, high-fidelity  
- **[Learning Geometrically-Grounded 3D Visual Representations for View-Generalizable Robotic Manipulation](https://arxiv.org/abs/2601.22988v1)**  
  Authors: Di Zhang, Weicheng Duan, Dasen Gu, Hongye Lu, Hai Zhang, Hang Yu, Junqiao Zhao, Guang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22988v1.pdf)  
  Keywords: understanding, ar, gaussian splatting  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: path tracing, understanding, gaussian splatting, ar, medical, head, lightweight, vr  
- **[TIGaussian: Disentangle Gaussians for Spatial-Awared Text-Image-3D Alignment](https://arxiv.org/abs/2601.19247v1)**  
  Authors: Jiarun Liu, Qifeng Chen, Yiru Zhao, Minghua Liu, Baorui Ma, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19247v1.pdf)  
  Keywords: compact, gaussian splatting, ar, 3d gaussian, recognition  
- **[Bridging Visual and Wireless Sensing: A Unified Radiation Field for 3D Radio Map Construction](https://arxiv.org/abs/2601.19216v1)**  
  Authors: Chaozheng Wen, Jingwen Tong, Zehong Lin, Chenghong Bian, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.19216v1.pdf)  
  Keywords: geometry, understanding, gaussian splatting, ar, 3d gaussian, nerf, high-fidelity  
- **[ExoGS: A 4D Real-to-Sim-to-Real Framework for Scalable Manipulation Data Collection](https://arxiv.org/abs/2601.18629v1)**  
  Authors: Yiming Wang, Ruogu Zhang, Minyang Li, Hao Shi, Junbo Wang, Deyi Li, Jieji Ren, Wenhai Liu, Weiming Wang, Hao-Shu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18629v1.pdf)  
  Keywords: geometry, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, semantic, lightweight, human  
- **[A Step to Decouple Optimization in 3DGS](https://arxiv.org/abs/2601.16736v2)**  
  Authors: Renjie Ding, Yaonan Wang, Min Liu, Jialin Zhu, Jiazheng Wang, Jiahao Zhao, Wenting Shen, Feixiang He, Xiang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.16736v2.pdf)  
  Keywords: understanding, ar, 3d gaussian, gaussian splatting  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: geometry, autonomous driving, motion, dynamic, gaussian splatting, ar, 3d gaussian, efficient, 4d, semantic, urban scene  



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