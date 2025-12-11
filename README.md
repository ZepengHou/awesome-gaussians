# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-12-11 00:59:57

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

- [3DGS Surveys](#3dgs-surveys) (23 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (249 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (344 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (403 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (345 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (76 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (401 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (190 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (14 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (119 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (144 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (208 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: 3d gaussian, survey, semantic, ar, robotics, slam, nerf, mapping, localization, gaussian splatting, understanding  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: 3d gaussian, survey, semantic, ar, robotics, slam, high-fidelity, mapping, localization, gaussian splatting, efficient  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 3d gaussian, survey, ar, 4d, geometry, nerf, fast, motion, gaussian splatting  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: lighting, 3d gaussian, survey, 3d reconstruction, ar, animation, real-time rendering, avatar, gaussian splatting, efficient, face, efficient rendering  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: survey, ar, human, lightweight, nerf, gaussian splatting, efficient, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: 3d gaussian, survey, ar, slam, nerf, neural rendering, fast, gaussian splatting, efficient, understanding  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: lighting, 3d gaussian, survey, semantic, ar, nerf, compact, high-fidelity, segmentation, gaussian splatting, understanding  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: 3d gaussian, survey, semantic, ar, robotics, nerf, gaussian splatting, efficient, understanding  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: 3d gaussian, survey, ar, human, robotics, nerf, gaussian splatting  

### Acceleration

*Showing the latest 50 out of 249 papers*

- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, nerf, high-fidelity, acceleration, fast, gaussian splatting, face  
- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: 3d gaussian, ar, compact, fast, gaussian splatting  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: 3d gaussian, ar, vr, geometry, nerf, neural rendering, real-time rendering, fast, gaussian splatting, efficient, face  
- **[EGGS: Exchangeable 2D/3D Gaussian Splatting for Geometry-Appearance Balanced Novel View Synthesis](https://arxiv.org/abs/2512.02932v1)**  
  Authors: Yancheng Zhang, Guangyu Sun, Chen Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02932v1.pdf)  
  Keywords: 3d gaussian, ar, autonomous driving, geometry, real-time rendering, dynamic, gaussian splatting, efficient, vr  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, geometry, nerf, high-fidelity, real-time rendering, gaussian splatting, efficient, face, efficient rendering  
- **[Content-Aware Texturing for Gaussian Splatting](https://arxiv.org/abs/2512.02621v1)**  
  Authors: Panagiotis Papantonakis, Georgios Kopanas, Fredo Durand, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02621v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gs-texturing/)  
  Keywords: 3d reconstruction, ar, geometry, mapping, real-time rendering, gaussian splatting  
- **[G-SHARP: Gaussian Surgical Hardware Accelerated Real-time Pipeline](https://arxiv.org/abs/2512.02482v1)**  
  Authors: Vishwesh Nath, Javier G. Tejero, Ruilong Li, Filippo Filicori, Mahdi Azizian, Sean D. Huver  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02482v1.pdf)  
  Keywords: deformation, ar, nerf, high-fidelity, fast, gaussian splatting  
- **[Asset-Driven Sematic Reconstruction of Dynamic Scene with Multi-Human-Object Interactions](https://arxiv.org/abs/2512.00547v1)**  
  Authors: Sandika Biswas, Qianyi Wu, Biplab Banerjee, Hamid Rezatofighi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00547v1.pdf)  
  Keywords: 3d gaussian, semantic, deformation, ar, human, vr, geometry, high-fidelity, mapping, fast, dynamic, motion, gaussian splatting, face  
- **[SplatFont3D: Structure-Aware Text-to-3D Artistic Font Generation with Part-Level Style Control](https://arxiv.org/abs/2512.00413v1)**  
  Authors: Ji Gan, Lingxu Chen, Jiaxu Leng, Xinbo Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00413v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, human, animation, nerf, fast, dynamic, gaussian splatting  
- **[DiskChunGS: Large-Scale 3D Gaussian SLAM Through Chunk-Based Memory Management](https://arxiv.org/abs/2511.23030v1)**  
  Authors: Casimir Feldmann, Maximum Wilder-Smith, Vaishakh Patil, Michael Oechsle, Michael Niemeyer, Keisuke Tateno, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.23030v1.pdf)  
  Keywords: 3d gaussian, ar, slam, real-time rendering, gaussian splatting, face  

### Applications

*Showing the latest 50 out of 995 papers*

- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, vr, tracking, robotics, geometry, slam, mapping, localization, segmentation, gaussian splatting, understanding  
- **[On-the-fly Large-scale 3D Reconstruction from Multi-Camera Rigs](https://arxiv.org/abs/2512.08498v1)**  
  Authors: Yijia Guo, Tong Hu, Zhiwei Li, Liwen Hu, Keming Qian, Xitong Lin, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08498v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, lightweight, gaussian splatting, efficient  
- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 3d gaussian, avatar, ar, 4d, lightweight, neural rendering, dynamic, gaussian splatting, efficient  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, nerf, high-fidelity, acceleration, fast, gaussian splatting, face  
- **[Zero-Splat TeleAssist: A Zero-Shot Pose Estimation Framework for Semantic Teleoperation](https://arxiv.org/abs/2512.08271v1)**  
  Authors: Srijan Dokania, Dharini Raghavan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08271v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, segmentation, gaussian splatting  
- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: 3d gaussian, ar, compact, fast, gaussian splatting  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, sparse-view, dynamic, gaussian splatting, face  
- **[AdLift: Lifting Adversarial Perturbations to Safeguard 3D Gaussian Splatting Assets Against Instruction-Driven Editing](https://arxiv.org/abs/2512.07247v1)**  
  Authors: Ziming Hong, Tianyu Huang, Runnan Chen, Shanshan Ye, Mingming Gong, Bo Han, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07247v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d gaussian, semantic, 3d reconstruction, ar, gaussian splatting, understanding  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  

### Avatar Generation

*Showing the latest 50 out of 344 papers*

- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 3d gaussian, avatar, ar, 4d, lightweight, neural rendering, dynamic, gaussian splatting, efficient  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, nerf, high-fidelity, acceleration, fast, gaussian splatting, face  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, sparse-view, dynamic, gaussian splatting, face  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: 3d gaussian, ar, lightweight, sparse-view, head, gaussian splatting, efficient  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v2)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v2.pdf)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, geometry, gaussian splatting, face  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: 3d gaussian, ar, vr, geometry, nerf, neural rendering, real-time rendering, fast, gaussian splatting, efficient, face  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: 3d gaussian, avatar, deformation, ar, human, lightweight, nerf, head, high-fidelity, dynamic, gaussian splatting, vr  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, high-fidelity, gaussian splatting, face  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: ar, head, high-fidelity, motion, dynamic, gaussian splatting  
- **[Gaussian Entropy Fields: Driving Adaptive Sparsity in 3D Gaussian Optimization](https://arxiv.org/abs/2512.04542v1)**  
  Authors: Hong Kuang, Jianchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04542v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, nerf, gaussian splatting, face  

### Dynamic Scene

*Showing the latest 50 out of 403 papers*

- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 3d gaussian, avatar, ar, 4d, lightweight, neural rendering, dynamic, gaussian splatting, efficient  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, sparse-view, dynamic, gaussian splatting, face  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  
- **[RAVE: Rate-Adaptive Visual Encoding for 3D Gaussian Splatting](https://arxiv.org/abs/2512.07052v1)**  
  Authors: Hoang-Nhat Tran, Francesco Di Sario, Gabriele Spadaro, Giuseppe Valenzise, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07052v1.pdf)  
  Keywords: 3d gaussian, ar, lightweight, dynamic, gaussian splatting, compression, efficient  
- **[EMGauss: Continuous Slice-to-3D Reconstruction via Dynamic Gaussian Modeling in Volume Electron Microscopy](https://arxiv.org/abs/2512.06684v1)**  
  Authors: Yumeng He, Zanwei Zhou, Yekun Zheng, Chen Liang, Yunbo Wang, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06684v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, dynamic  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: 3d gaussian, avatar, deformation, ar, human, lightweight, nerf, head, high-fidelity, dynamic, gaussian splatting, vr  
- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: ar, 4d, animation, tracking, motion, dynamic, gaussian splatting  
- **[TED-4DGS: Temporally Activated and Embedding-based Deformation for 4DGS Compression](https://arxiv.org/abs/2512.05446v1)**  
  Authors: Cheng-Yuan Ho, He-Bi Yang, Jui-Chiu Chiang, Yu-Lun Liu, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05446v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, 4d, lightweight, compact, dynamic, gaussian splatting, compression, efficient  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: ar, head, high-fidelity, motion, dynamic, gaussian splatting  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: semantic, ar, 4d, geometry, nerf, dynamic, gaussian splatting, understanding  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, sparse-view, dynamic, gaussian splatting, face  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: 3d gaussian, ar, lightweight, sparse-view, head, gaussian splatting, efficient  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: 3d gaussian, ar, compact, sparse view, head, segmentation, gaussian splatting, efficient, understanding  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: 3d gaussian, ar, sparse view, sparse-view, gaussian splatting, efficient  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, human, tracking, geometry, sparse view, sparse-view, motion, dynamic, illumination, efficient, body  
- **[Observer Actor: Active Vision Imitation Learning with Sparse View Gaussian Splatting](https://arxiv.org/abs/2511.18140v1)**  
  Authors: Yilong Wang, Cheng Qian, Ruomeng Fan, Edward Johns  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18140v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://obact.github.io.)  
  Keywords: 3d gaussian, ar, sparse view, dynamic, gaussian splatting  
- **[Frequency-Adaptive Sharpness Regularization for Improving 3D Gaussian Splatting Generalization](https://arxiv.org/abs/2511.17918v1)**  
  Authors: Youngsik Yun, Dongjun Gu, Youngjung Uh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17918v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://bbangsik13.github.io/FASR.)  
  Keywords: few-shot, gaussian splatting, 3d gaussian, ar  
- **[SPAGS: Sparse-View Articulated Object Reconstruction from Single State via Planar Gaussian Splatting](https://arxiv.org/abs/2511.17092v2)**  
  Authors: Di Wu, Liu Liu, Xueyu Yuan, Qiaojun Yu, Wenxiao Chen, Ruilong Yan, Yiming Tang, Liangtu Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17092v2.pdf)  
  Keywords: few-shot, 3d gaussian, 3d reconstruction, ar, sparse view, sparse-view, segmentation, gaussian splatting, face  
- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: 3d gaussian, 3d reconstruction, ar, sparse view, high-fidelity, sparse-view, gaussian splatting, efficient  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, nerf, sparse-view, gaussian splatting, efficient, face  

### Geometry Reconstruction

*Showing the latest 50 out of 345 papers*

- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, vr, tracking, robotics, geometry, slam, mapping, localization, segmentation, gaussian splatting, understanding  
- **[On-the-fly Large-scale 3D Reconstruction from Multi-Camera Rigs](https://arxiv.org/abs/2512.08498v1)**  
  Authors: Yijia Guo, Tong Hu, Zhiwei Li, Liwen Hu, Keming Qian, Xitong Lin, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08498v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, lightweight, gaussian splatting, efficient  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d gaussian, semantic, 3d reconstruction, ar, gaussian splatting, understanding  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v2)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v2.pdf)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, geometry, gaussian splatting, face  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: 3d gaussian, ar, vr, geometry, nerf, neural rendering, real-time rendering, fast, gaussian splatting, efficient, face  
- **[EMGauss: Continuous Slice-to-3D Reconstruction via Dynamic Gaussian Modeling in Volume Electron Microscopy](https://arxiv.org/abs/2512.06684v1)**  
  Authors: Yumeng He, Zanwei Zhou, Yekun Zheng, Chen Liang, Yunbo Wang, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06684v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, dynamic  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, high-fidelity, gaussian splatting, face  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: semantic, ar, 4d, geometry, nerf, dynamic, gaussian splatting, understanding  
- **[Gaussian Entropy Fields: Driving Adaptive Sparsity in 3D Gaussian Optimization](https://arxiv.org/abs/2512.04542v1)**  
  Authors: Hong Kuang, Jianchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04542v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, nerf, gaussian splatting, face  

### Large Scene

*Showing the latest 50 out of 76 papers*

- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: 3d gaussian, ar, 4d, robotics, outdoor, nerf, motion, dynamic, gaussian splatting, efficient  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: 3d gaussian, 3d reconstruction, ar, outdoor, geometry, gaussian splatting, understanding  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: semantic, ar, outdoor, geometry, fast, gaussian splatting  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: relighting, lighting, semantic, ar, outdoor, geometry, high-fidelity, segmentation, gaussian splatting, illumination, efficient, face  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: 3d gaussian, ar, outdoor, geometry, high-fidelity, gaussian splatting  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: urban scene, ar, human, 4d, autonomous driving, dynamic, gaussian splatting  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: 3d gaussian, ar, head, fast, gaussian splatting, large scene  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: 3d gaussian, ar, outdoor, geometry, slam, mapping, motion, gaussian splatting, understanding  
- **[D$^2$GS: Dense Depth Regularization for LiDAR-free Urban Scene Reconstruction](https://arxiv.org/abs/2510.25173v2)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v2.pdf)  
  Keywords: urban scene, ar, autonomous driving, geometry, gaussian splatting  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: urban scene, semantic, 3d reconstruction, ar, gaussian splatting, face  

### Model Compression

*Showing the latest 50 out of 401 papers*

- **[On-the-fly Large-scale 3D Reconstruction from Multi-Camera Rigs](https://arxiv.org/abs/2512.08498v1)**  
  Authors: Yijia Guo, Tong Hu, Zhiwei Li, Liwen Hu, Keming Qian, Xitong Lin, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08498v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, lightweight, gaussian splatting, efficient  
- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 3d gaussian, avatar, ar, 4d, lightweight, neural rendering, dynamic, gaussian splatting, efficient  
- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: 3d gaussian, ar, compact, fast, gaussian splatting  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: 3d gaussian, ar, lightweight, sparse-view, head, gaussian splatting, efficient  
- **[RAVE: Rate-Adaptive Visual Encoding for 3D Gaussian Splatting](https://arxiv.org/abs/2512.07052v1)**  
  Authors: Hoang-Nhat Tran, Francesco Di Sario, Gabriele Spadaro, Giuseppe Valenzise, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07052v1.pdf)  
  Keywords: 3d gaussian, ar, lightweight, dynamic, gaussian splatting, compression, efficient  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: 3d gaussian, ar, vr, geometry, nerf, neural rendering, real-time rendering, fast, gaussian splatting, efficient, face  
- **[RDSplat: Robust Watermarking Against Diffusion Editing for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06774v1)**  
  Authors: Longjie Zhao, Ziming Hong, Zhenyang Ren, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06774v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, efficient  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: 3d gaussian, avatar, deformation, ar, human, lightweight, nerf, head, high-fidelity, dynamic, gaussian splatting, vr  
- **[TED-4DGS: Temporally Activated and Embedding-based Deformation for 4DGS Compression](https://arxiv.org/abs/2512.05446v1)**  
  Authors: Cheng-Yuan Ho, He-Bi Yang, Jui-Chiu Chiang, Yu-Lun Liu, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05446v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, 4d, lightweight, compact, dynamic, gaussian splatting, compression, efficient  

### Quality Enhancement

*Showing the latest 50 out of 190 papers*

- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, nerf, high-fidelity, acceleration, fast, gaussian splatting, face  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, survey, 3d reconstruction, ar, 4d, compact, high-fidelity, dynamic, gaussian splatting, compression, efficient  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: 3d gaussian, avatar, deformation, ar, human, lightweight, nerf, head, high-fidelity, dynamic, gaussian splatting, vr  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, high-fidelity, gaussian splatting, face  
- **[SplatPainter: Interactive Authoring of 3D Gaussians from 2D Edits via Test-Time Training](https://arxiv.org/abs/2512.05354v1)**  
  Authors: Yang Zheng, Hao Tan, Kai Zhang, Peng Wang, Leonidas Guibas, Gordon Wetzstein, Wang Yifan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05354v1.pdf)  
  Keywords: 3d gaussian, ar, compact, high-fidelity, gaussian splatting  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: ar, head, high-fidelity, motion, dynamic, gaussian splatting  
- **[SyncTrack4D: Cross-Video Motion Alignment and Video Synchronization for Multi-Video 4D Gaussian Splatting](https://arxiv.org/abs/2512.04315v1)**  
  Authors: Yonghan Lee, Tsung-Wei Huang, Shiv Gehlot, Jaehoon Choi, Guan-Ming Su, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04315v1.pdf)  
  Keywords: ar, 4d, geometry, nerf, high-fidelity, motion, dynamic, gaussian splatting  
- **[Mind-to-Face: Neural-Driven Photorealistic Avatar Synthesis via EEG Decoding](https://arxiv.org/abs/2512.04313v1)**  
  Authors: Haolin Xiong, Tianwen Fu, Pratusha Bhuvana Prasad, Yunxuan Cai, Haiwei Chen, Wenbin Teng, Hanyuan Xiao, Yajie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04313v1.pdf)  
  Keywords: 3d gaussian, avatar, ar, geometry, high-fidelity, motion, dynamic, gaussian splatting, face  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, geometry, nerf, high-fidelity, real-time rendering, gaussian splatting, efficient, face, efficient rendering  
- **[PoreTrack3D: A Benchmark for Dynamic 3D Gaussian Splatting in Pore-Scale Facial Trajectory Tracking](https://arxiv.org/abs/2512.02648v1)**  
  Authors: Dong Li, Jiahao Xiong, Yingda Huang, Le Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02648v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, tracking, high-fidelity, motion, dynamic, gaussian splatting, face  

### Ray Tracing

- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ar, reflection, geometry, ray tracing, gaussian splatting, illumination  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: 3d gaussian, efficient, ar, geometry, gaussian splatting, ray marching  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: lighting, relightable, ar, light transport, real-time rendering, shadow, ray tracing, gaussian splatting, efficient, face  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: relighting, lighting, ar, reflection, geometry, light transport, gaussian splatting, illumination, efficient, global illumination  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: ar, 4d, fast, dynamic, ray tracing, gaussian splatting  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: relighting, 3d gaussian, lighting, ar, reflection, geometry, nerf, high-fidelity, ray tracing, gaussian splatting, illumination, face  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, dynamic, outdoor, shadow, gaussian splatting, illumination, face, global illumination  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: lighting, 3d gaussian, ar, face, dynamic, gaussian splatting, path tracing  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relighting, 3d gaussian, lighting, relightable, efficient, ar, geometry, gaussian splatting, ray marching, face, efficient rendering  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: ar, high-fidelity, real-time rendering, ray tracing, gaussian splatting, efficient  

### Relighting

*Showing the latest 50 out of 119 papers*

- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, nerf, high-fidelity, acceleration, fast, gaussian splatting, face  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v2)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v2.pdf)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, geometry, gaussian splatting, face  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, dynamic, gaussian splatting, illumination  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, geometry, nerf, high-fidelity, real-time rendering, gaussian splatting, efficient, face, efficient rendering  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relighting, 3d gaussian, lighting, relightable, ar, human, tracking, geometry, sparse view, sparse-view, motion, dynamic, illumination, efficient, body  
- **[Endo-G$^{2}$T: Geometry-Guided & Temporally Aware Time-Embedded 4DGS For Endoscopic Scenes](https://arxiv.org/abs/2511.21367v1)**  
  Authors: Yangle Liu, Fengze Li, Kan Liu, Jieming Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.21367v1.pdf)  
  Keywords: ar, 4d, reflection, lightweight, geometry, nerf, motion, dynamic, gaussian splatting  
- **[CUS-GS: A Compact Unified Structured Gaussian Splatting Framework for Multimodal Scene Representation](https://arxiv.org/abs/2511.17904v1)**  
  Authors: Yuhang Ming, Chenxin Fang, Xingyuan Yu, Fan Zhang, Weichen Dai, Wanzeng Kong, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17904v1.pdf)  
  Keywords: lighting, semantic, ar, geometry, compact, dynamic, gaussian splatting, understanding  
- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: lighting, 3d gaussian, deformation, ar, 4d, geometry, motion, dynamic, gaussian splatting  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, geometry, compact, sparse-view, high-fidelity, gaussian splatting, illumination, face  
- **[iGaussian: Real-Time Camera Pose Estimation via Feed-Forward 3D Gaussian Splatting Inversion](https://arxiv.org/abs/2511.14149v1)**  
  Authors: Hao Wang, Linqing Zhao, Xiuwei Xu, Jiwen Lu, Haibin Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14149v1.pdf)  
  Keywords: lighting, 3d gaussian, ar, tracking, robotics, slam, nerf, head, gaussian splatting  

### SLAM

*Showing the latest 50 out of 144 papers*

- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, vr, tracking, robotics, geometry, slam, mapping, localization, segmentation, gaussian splatting, understanding  
- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: ar, 4d, animation, tracking, motion, dynamic, gaussian splatting  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: semantic, ar, 4d, tracking, geometry, motion, dynamic, segmentation, gaussian splatting, understanding  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: 3d gaussian, survey, semantic, ar, robotics, slam, nerf, mapping, localization, gaussian splatting, understanding  
- **[PoreTrack3D: A Benchmark for Dynamic 3D Gaussian Splatting in Pore-Scale Facial Trajectory Tracking](https://arxiv.org/abs/2512.02648v1)**  
  Authors: Dong Li, Jiahao Xiong, Yingda Huang, Le Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02648v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, tracking, high-fidelity, motion, dynamic, gaussian splatting, face  
- **[Content-Aware Texturing for Gaussian Splatting](https://arxiv.org/abs/2512.02621v1)**  
  Authors: Panagiotis Papantonakis, Georgios Kopanas, Fredo Durand, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02621v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gs-texturing/)  
  Keywords: 3d reconstruction, ar, geometry, mapping, real-time rendering, gaussian splatting  
- **[VIGS-SLAM: Visual Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2512.02293v1)**  
  Authors: Zihan Zhu, Wei Zhang, Norbert Haala, Marc Pollefeys, Daniel Barath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02293v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vigs-slam.github.io)  
  Keywords: 3d gaussian, ar, tracking, slam, high-fidelity, mapping, motion, gaussian splatting  
- **[TagSplat: Topology-Aware Gaussian Splatting for Dynamic Mesh Modeling and Tracking](https://arxiv.org/abs/2512.01329v1)**  
  Authors: Hanzhi Guo, Dongdong Weng, Mo Su, Yixiao Chen, Xiaonuo Dongye, Chenyu Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.01329v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://haza628.github.io/tagSplat/)  
  Keywords: ar, 4d, animation, tracking, dynamic, gaussian splatting, face  
- **[EGG-Fusion: Efficient 3D Reconstruction with Geometry-aware Gaussian Surfel on the Fly](https://arxiv.org/abs/2512.01296v1)**  
  Authors: Xiaokun Pan, Zhenzhe Li, Zhichao Ye, Hongjia Zhai, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.01296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/eggfusion/)  
  Keywords: 3d gaussian, 3d reconstruction, ar, tracking, geometry, nerf, slam, mapping, gaussian splatting, efficient, face  
- **[Binary-Gaussian: Compact and Progressive Representation for 3D Gaussian Segmentation](https://arxiv.org/abs/2512.00944v1)**  
  Authors: An Yang, Chenyu Liu, Jun Du, Jianqing Gao, Jia Pan, Jinshui Hu, Baocai Yin, Bing Yin, Cong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00944v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, compact, head, mapping, segmentation, gaussian splatting, efficient  

### Scene Understanding

*Showing the latest 50 out of 208 papers*

- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, vr, tracking, robotics, geometry, slam, mapping, localization, segmentation, gaussian splatting, understanding  
- **[Zero-Splat TeleAssist: A Zero-Shot Pose Estimation Framework for Semantic Teleoperation](https://arxiv.org/abs/2512.08271v1)**  
  Authors: Srijan Dokania, Dharini Raghavan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08271v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, segmentation, gaussian splatting  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d gaussian, semantic, 3d reconstruction, ar, gaussian splatting, understanding  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: semantic, ar, 4d, geometry, nerf, dynamic, gaussian splatting, understanding  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: 3d gaussian, semantic, ar, dynamic, gaussian splatting, illumination  
- **[Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting](https://arxiv.org/abs/2512.04731v1)**  
  Authors: Jian Tang, Pu Pang, Haowen Sun, Chengzhong Ma, Xingyu Chen, Hua Huang, Xuguang Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04731v1.pdf)  
  Keywords: ar, gaussian splatting, semantic  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: 3d gaussian, ar, compact, sparse view, head, segmentation, gaussian splatting, efficient, understanding  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: semantic, ar, 4d, tracking, geometry, motion, dynamic, segmentation, gaussian splatting, understanding  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: 3d gaussian, survey, semantic, ar, robotics, slam, nerf, mapping, localization, gaussian splatting, understanding  
- **[ManualVLA: A Unified VLA Model for Chain-of-Thought Manual Generation and Robotic Manipulation](https://arxiv.org/abs/2512.02013v1)**  
  Authors: Chenyang Gu, Jiaming Liu, Hao Chen, Runzhong Huang, Qingpo Wuwu, Zhuoyang Liu, Xiaoqi Li, Ying Li, Renrui Zhang, Peng Jia, Pheng-Ann Heng, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02013v1.pdf)  
  Keywords: 3d gaussian, ar, understanding, high-fidelity, gaussian splatting, face  



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