# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-12-10 00:59:15

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
- [Avatar Generation](#avatar-generation) (342 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (405 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (82 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (344 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (76 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (401 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (190 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (14 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (118 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (143 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (206 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, survey, semantic, slam, mapping, robotics, ar, nerf, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: efficient, gaussian splatting, localization, survey, semantic, slam, mapping, robotics, ar, high-fidelity, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, gaussian splatting, survey, motion, fast, ar, geometry, nerf, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: efficient, 3d reconstruction, efficient rendering, gaussian splatting, lighting, survey, face, avatar, animation, ar, 3d gaussian, real-time rendering  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: efficient, gaussian splatting, understanding, survey, lightweight, ar, human, nerf  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: efficient, gaussian splatting, neural rendering, understanding, survey, slam, fast, ar, nerf, 3d gaussian  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: gaussian splatting, understanding, lighting, survey, semantic, segmentation, ar, high-fidelity, compact, nerf, 3d gaussian  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: efficient, gaussian splatting, understanding, survey, semantic, robotics, ar, nerf, 3d gaussian  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: gaussian splatting, survey, robotics, ar, human, nerf, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 249 papers*

- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: gaussian splatting, ar, fast, compact, 3d gaussian  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: efficient, gaussian splatting, neural rendering, face, fast, ar, geometry, nerf, 3d gaussian, vr, real-time rendering  
- **[EGGS: Exchangeable 2D/3D Gaussian Splatting for Geometry-Appearance Balanced Novel View Synthesis](https://arxiv.org/abs/2512.02932v1)**  
  Authors: Yancheng Zhang, Guangyu Sun, Chen Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02932v1.pdf)  
  Keywords: efficient, gaussian splatting, dynamic, autonomous driving, ar, geometry, 3d gaussian, vr, real-time rendering  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: efficient, efficient rendering, reflection, gaussian splatting, face, ar, high-fidelity, geometry, nerf, 3d gaussian, real-time rendering  
- **[Content-Aware Texturing for Gaussian Splatting](https://arxiv.org/abs/2512.02621v1)**  
  Authors: Panagiotis Papantonakis, Georgios Kopanas, Fredo Durand, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02621v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gs-texturing/)  
  Keywords: 3d reconstruction, gaussian splatting, mapping, ar, geometry, real-time rendering  
- **[G-SHARP: Gaussian Surgical Hardware Accelerated Real-time Pipeline](https://arxiv.org/abs/2512.02482v1)**  
  Authors: Vishwesh Nath, Javier G. Tejero, Ruilong Li, Filippo Filicori, Mahdi Azizian, Sean D. Huver  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02482v1.pdf)  
  Keywords: deformation, gaussian splatting, fast, ar, high-fidelity, nerf  
- **[Asset-Driven Sematic Reconstruction of Dynamic Scene with Multi-Human-Object Interactions](https://arxiv.org/abs/2512.00547v1)**  
  Authors: Sandika Biswas, Qianyi Wu, Biplab Banerjee, Hamid Rezatofighi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00547v1.pdf)  
  Keywords: deformation, gaussian splatting, mapping, semantic, dynamic, motion, face, fast, ar, human, high-fidelity, geometry, 3d gaussian, vr  
- **[SplatFont3D: Structure-Aware Text-to-3D Artistic Font Generation with Part-Level Style Control](https://arxiv.org/abs/2512.00413v1)**  
  Authors: Ji Gan, Lingxu Chen, Jiaxu Leng, Xinbo Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00413v1.pdf)  
  Keywords: gaussian splatting, semantic, dynamic, fast, animation, human, ar, nerf, 3d gaussian  
- **[DiskChunGS: Large-Scale 3D Gaussian SLAM Through Chunk-Based Memory Management](https://arxiv.org/abs/2511.23030v1)**  
  Authors: Casimir Feldmann, Maximum Wilder-Smith, Vaishakh Patil, Michael Oechsle, Michael Niemeyer, Keisuke Tateno, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.23030v1.pdf)  
  Keywords: gaussian splatting, slam, face, ar, 3d gaussian, real-time rendering  
- **[DenoiseGS: Gaussian Reconstruction Model for Burst Denoising](https://arxiv.org/abs/2511.22939v2)**  
  Authors: Yongsen Cheng, Yuanhao Cai, Yulun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.22939v2.pdf)  
  Keywords: gaussian splatting, motion, fast, ar, geometry, nerf, 3d gaussian  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: gaussian splatting, ar, fast, compact, 3d gaussian  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: deformation, sparse-view, gaussian splatting, dynamic, face, ar, 3d gaussian  
- **[AdLift: Lifting Adversarial Perturbations to Safeguard 3D Gaussian Splatting Assets Against Instruction-Driven Editing](https://arxiv.org/abs/2512.07247v1)**  
  Authors: Ziming Hong, Tianyu Huang, Runnan Chen, Shanshan Ye, Mingming Gong, Bo Han, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07247v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, understanding, semantic, ar, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, head, lightweight, ar, 3d gaussian  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v1)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v1.pdf)  
  Keywords: relightable, relighting, gaussian splatting, lighting, face, ar, geometry, 3d gaussian  
- **[RAVE: Rate-Adaptive Visual Encoding for 3D Gaussian Splatting](https://arxiv.org/abs/2512.07052v1)**  
  Authors: Hoang-Nhat Tran, Francesco Di Sario, Gabriele Spadaro, Giuseppe Valenzise, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07052v1.pdf)  
  Keywords: efficient, gaussian splatting, dynamic, lightweight, compression, ar, 3d gaussian  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: efficient, gaussian splatting, neural rendering, face, fast, ar, geometry, nerf, 3d gaussian, vr, real-time rendering  
- **[RDSplat: Robust Watermarking Against Diffusion Editing for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06774v1)**  
  Authors: Longjie Zhao, Ziming Hong, Zhenyang Ren, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06774v1.pdf)  
  Keywords: gaussian splatting, efficient, 3d gaussian, ar  

### Avatar Generation

*Showing the latest 50 out of 342 papers*

- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: deformation, sparse-view, gaussian splatting, dynamic, face, ar, 3d gaussian  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, head, lightweight, ar, 3d gaussian  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v1)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v1.pdf)  
  Keywords: relightable, relighting, gaussian splatting, lighting, face, ar, geometry, 3d gaussian  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: efficient, gaussian splatting, neural rendering, face, fast, ar, geometry, nerf, 3d gaussian, vr, real-time rendering  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: deformation, gaussian splatting, head, dynamic, lightweight, ar, human, high-fidelity, nerf, 3d gaussian, vr, avatar  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: gaussian splatting, face, ar, high-fidelity, geometry, 3d gaussian  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: gaussian splatting, head, motion, dynamic, ar, high-fidelity  
- **[Gaussian Entropy Fields: Driving Adaptive Sparsity in 3D Gaussian Optimization](https://arxiv.org/abs/2512.04542v1)**  
  Authors: Hong Kuang, Jianchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04542v1.pdf)  
  Keywords: gaussian splatting, face, ar, geometry, nerf, 3d gaussian  
- **[Mind-to-Face: Neural-Driven Photorealistic Avatar Synthesis via EEG Decoding](https://arxiv.org/abs/2512.04313v1)**  
  Authors: Haolin Xiong, Tianwen Fu, Pratusha Bhuvana Prasad, Yunxuan Cai, Haiwei Chen, Wenbin Teng, Hanyuan Xiao, Yajie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04313v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, face, ar, high-fidelity, geometry, 3d gaussian, avatar  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: efficient, gaussian splatting, understanding, head, segmentation, ar, compact, 3d gaussian, sparse view  

### Dynamic Scene

*Showing the latest 50 out of 405 papers*

- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: deformation, sparse-view, gaussian splatting, dynamic, face, ar, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[RAVE: Rate-Adaptive Visual Encoding for 3D Gaussian Splatting](https://arxiv.org/abs/2512.07052v1)**  
  Authors: Hoang-Nhat Tran, Francesco Di Sario, Gabriele Spadaro, Giuseppe Valenzise, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07052v1.pdf)  
  Keywords: efficient, gaussian splatting, dynamic, lightweight, compression, ar, 3d gaussian  
- **[EMGauss: Continuous Slice-to-3D Reconstruction via Dynamic Gaussian Modeling in Volume Electron Microscopy](https://arxiv.org/abs/2512.06684v1)**  
  Authors: Yumeng He, Zanwei Zhou, Yekun Zheng, Chen Liang, Yunbo Wang, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06684v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, ar, dynamic  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: deformation, gaussian splatting, head, dynamic, lightweight, ar, human, high-fidelity, nerf, 3d gaussian, vr, avatar  
- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: gaussian splatting, tracking, motion, dynamic, animation, ar, 4d  
- **[TED-4DGS: Temporally Activated and Embedding-based Deformation for 4DGS Compression](https://arxiv.org/abs/2512.05446v1)**  
  Authors: Cheng-Yuan Ho, He-Bi Yang, Jui-Chiu Chiang, Yu-Lun Liu, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05446v1.pdf)  
  Keywords: efficient, deformation, gaussian splatting, dynamic, lightweight, compression, ar, compact, 4d, 3d gaussian  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: gaussian splatting, head, motion, dynamic, ar, high-fidelity  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: 4d, gaussian splatting, understanding, semantic, dynamic, ar, geometry, nerf  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: gaussian splatting, semantic, dynamic, ar, 3d gaussian, illumination  

### Few-shot

*Showing the latest 50 out of 82 papers*

- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: deformation, sparse-view, gaussian splatting, dynamic, face, ar, 3d gaussian  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, head, lightweight, ar, 3d gaussian  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: efficient, gaussian splatting, understanding, head, segmentation, ar, compact, 3d gaussian, sparse view  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, ar, 3d gaussian, sparse view  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relightable, efficient, relighting, sparse-view, body, lighting, tracking, dynamic, motion, ar, human, geometry, 3d gaussian, sparse view, illumination  
- **[Observer Actor: Active Vision Imitation Learning with Sparse View Gaussian Splatting](https://arxiv.org/abs/2511.18140v1)**  
  Authors: Yilong Wang, Cheng Qian, Ruomeng Fan, Edward Johns  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18140v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://obact.github.io.)  
  Keywords: gaussian splatting, dynamic, ar, 3d gaussian, sparse view  
- **[Frequency-Adaptive Sharpness Regularization for Improving 3D Gaussian Splatting Generalization](https://arxiv.org/abs/2511.17918v1)**  
  Authors: Youngsik Yun, Dongjun Gu, Youngjung Uh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17918v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://bbangsik13.github.io/FASR.)  
  Keywords: gaussian splatting, 3d gaussian, ar, few-shot  
- **[SPAGS: Sparse-View Articulated Object Reconstruction from Single State via Planar Gaussian Splatting](https://arxiv.org/abs/2511.17092v2)**  
  Authors: Di Wu, Liu Liu, Xueyu Yuan, Qiaojun Yu, Wenxiao Chen, Ruilong Yan, Yiming Tang, Liangtu Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17092v2.pdf)  
  Keywords: 3d reconstruction, sparse-view, gaussian splatting, few-shot, segmentation, face, ar, 3d gaussian, sparse view  
- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: efficient, 3d reconstruction, sparse-view, gaussian splatting, ar, high-fidelity, 3d gaussian, sparse view  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, face, ar, geometry, nerf, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 344 papers*

- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, understanding, semantic, ar, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v1)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v1.pdf)  
  Keywords: relightable, relighting, gaussian splatting, lighting, face, ar, geometry, 3d gaussian  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: efficient, gaussian splatting, neural rendering, face, fast, ar, geometry, nerf, 3d gaussian, vr, real-time rendering  
- **[EMGauss: Continuous Slice-to-3D Reconstruction via Dynamic Gaussian Modeling in Volume Electron Microscopy](https://arxiv.org/abs/2512.06684v1)**  
  Authors: Yumeng He, Zanwei Zhou, Yekun Zheng, Chen Liang, Yunbo Wang, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06684v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, ar, dynamic  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: gaussian splatting, face, ar, high-fidelity, geometry, 3d gaussian  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: 4d, gaussian splatting, understanding, semantic, dynamic, ar, geometry, nerf  
- **[Gaussian Entropy Fields: Driving Adaptive Sparsity in 3D Gaussian Optimization](https://arxiv.org/abs/2512.04542v1)**  
  Authors: Hong Kuang, Jianchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04542v1.pdf)  
  Keywords: gaussian splatting, face, ar, geometry, nerf, 3d gaussian  
- **[SyncTrack4D: Cross-Video Motion Alignment and Video Synchronization for Multi-Video 4D Gaussian Splatting](https://arxiv.org/abs/2512.04315v1)**  
  Authors: Yonghan Lee, Tsung-Wei Huang, Shiv Gehlot, Jaehoon Choi, Guan-Ming Su, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04315v1.pdf)  
  Keywords: 4d, gaussian splatting, dynamic, motion, ar, high-fidelity, geometry, nerf  
- **[Mind-to-Face: Neural-Driven Photorealistic Avatar Synthesis via EEG Decoding](https://arxiv.org/abs/2512.04313v1)**  
  Authors: Haolin Xiong, Tianwen Fu, Pratusha Bhuvana Prasad, Yunxuan Cai, Haiwei Chen, Wenbin Teng, Hanyuan Xiao, Yajie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04313v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, face, ar, high-fidelity, geometry, 3d gaussian, avatar  

### Large Scene

*Showing the latest 50 out of 76 papers*

- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: efficient, gaussian splatting, dynamic, motion, robotics, ar, outdoor, 4d, nerf, 3d gaussian  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: 3d reconstruction, gaussian splatting, understanding, ar, outdoor, geometry, 3d gaussian  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: gaussian splatting, semantic, fast, ar, outdoor, geometry  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: efficient, relighting, gaussian splatting, lighting, semantic, segmentation, face, ar, outdoor, high-fidelity, geometry, illumination  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: gaussian splatting, ar, outdoor, high-fidelity, geometry, 3d gaussian  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: gaussian splatting, urban scene, dynamic, autonomous driving, ar, human, 4d  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: gaussian splatting, head, fast, ar, large scene, 3d gaussian  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: gaussian splatting, understanding, slam, mapping, motion, ar, outdoor, geometry, 3d gaussian  
- **[D$^2$GS: Dense Depth Regularization for LiDAR-free Urban Scene Reconstruction](https://arxiv.org/abs/2510.25173v2)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v2.pdf)  
  Keywords: gaussian splatting, urban scene, autonomous driving, ar, geometry  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, semantic, urban scene, face, ar  

### Model Compression

*Showing the latest 50 out of 401 papers*

- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: gaussian splatting, ar, fast, compact, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: efficient, sparse-view, gaussian splatting, head, lightweight, ar, 3d gaussian  
- **[RAVE: Rate-Adaptive Visual Encoding for 3D Gaussian Splatting](https://arxiv.org/abs/2512.07052v1)**  
  Authors: Hoang-Nhat Tran, Francesco Di Sario, Gabriele Spadaro, Giuseppe Valenzise, Enzo Tartaglione  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07052v1.pdf)  
  Keywords: efficient, gaussian splatting, dynamic, lightweight, compression, ar, 3d gaussian  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: efficient, gaussian splatting, neural rendering, face, fast, ar, geometry, nerf, 3d gaussian, vr, real-time rendering  
- **[RDSplat: Robust Watermarking Against Diffusion Editing for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06774v1)**  
  Authors: Longjie Zhao, Ziming Hong, Zhenyang Ren, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06774v1.pdf)  
  Keywords: gaussian splatting, efficient, 3d gaussian, ar  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: deformation, gaussian splatting, head, dynamic, lightweight, ar, human, high-fidelity, nerf, 3d gaussian, vr, avatar  
- **[TED-4DGS: Temporally Activated and Embedding-based Deformation for 4DGS Compression](https://arxiv.org/abs/2512.05446v1)**  
  Authors: Cheng-Yuan Ho, He-Bi Yang, Jui-Chiu Chiang, Yu-Lun Liu, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05446v1.pdf)  
  Keywords: efficient, deformation, gaussian splatting, dynamic, lightweight, compression, ar, compact, 4d, 3d gaussian  
- **[SplatPainter: Interactive Authoring of 3D Gaussians from 2D Edits via Test-Time Training](https://arxiv.org/abs/2512.05354v1)**  
  Authors: Yang Zheng, Hao Tan, Kai Zhang, Peng Wang, Leonidas Guibas, Gordon Wetzstein, Wang Yifan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05354v1.pdf)  
  Keywords: gaussian splatting, ar, high-fidelity, compact, 3d gaussian  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: efficient, gaussian splatting, understanding, head, segmentation, ar, compact, 3d gaussian, sparse view  

### Quality Enhancement

*Showing the latest 50 out of 190 papers*

- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, survey, dynamic, compression, ar, high-fidelity, 4d, compact, 3d gaussian  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v1)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: deformation, gaussian splatting, head, dynamic, lightweight, ar, human, high-fidelity, nerf, 3d gaussian, vr, avatar  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: gaussian splatting, face, ar, high-fidelity, geometry, 3d gaussian  
- **[SplatPainter: Interactive Authoring of 3D Gaussians from 2D Edits via Test-Time Training](https://arxiv.org/abs/2512.05354v1)**  
  Authors: Yang Zheng, Hao Tan, Kai Zhang, Peng Wang, Leonidas Guibas, Gordon Wetzstein, Wang Yifan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05354v1.pdf)  
  Keywords: gaussian splatting, ar, high-fidelity, compact, 3d gaussian  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: gaussian splatting, head, motion, dynamic, ar, high-fidelity  
- **[SyncTrack4D: Cross-Video Motion Alignment and Video Synchronization for Multi-Video 4D Gaussian Splatting](https://arxiv.org/abs/2512.04315v1)**  
  Authors: Yonghan Lee, Tsung-Wei Huang, Shiv Gehlot, Jaehoon Choi, Guan-Ming Su, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04315v1.pdf)  
  Keywords: 4d, gaussian splatting, dynamic, motion, ar, high-fidelity, geometry, nerf  
- **[Mind-to-Face: Neural-Driven Photorealistic Avatar Synthesis via EEG Decoding](https://arxiv.org/abs/2512.04313v1)**  
  Authors: Haolin Xiong, Tianwen Fu, Pratusha Bhuvana Prasad, Yunxuan Cai, Haiwei Chen, Wenbin Teng, Hanyuan Xiao, Yajie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04313v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, face, ar, high-fidelity, geometry, 3d gaussian, avatar  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: efficient, efficient rendering, reflection, gaussian splatting, face, ar, high-fidelity, geometry, nerf, 3d gaussian, real-time rendering  
- **[PoreTrack3D: A Benchmark for Dynamic 3D Gaussian Splatting in Pore-Scale Facial Trajectory Tracking](https://arxiv.org/abs/2512.02648v1)**  
  Authors: Dong Li, Jiahao Xiong, Yingda Huang, Le Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02648v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, tracking, dynamic, motion, face, ar, high-fidelity, 3d gaussian  
- **[G-SHARP: Gaussian Surgical Hardware Accelerated Real-time Pipeline](https://arxiv.org/abs/2512.02482v1)**  
  Authors: Vishwesh Nath, Javier G. Tejero, Ruilong Li, Filippo Filicori, Mahdi Azizian, Sean D. Huver  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02482v1.pdf)  
  Keywords: deformation, gaussian splatting, fast, ar, high-fidelity, nerf  

### Ray Tracing

- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: reflection, gaussian splatting, ar, geometry, ray tracing, illumination  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: efficient, gaussian splatting, ar, geometry, 3d gaussian, ray marching  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: relightable, efficient, light transport, shadow, gaussian splatting, lighting, face, ar, ray tracing, real-time rendering  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: efficient, relighting, light transport, reflection, gaussian splatting, lighting, ar, geometry, global illumination, illumination  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: gaussian splatting, dynamic, fast, ar, 4d, ray tracing  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: relighting, reflection, gaussian splatting, lighting, face, ar, high-fidelity, geometry, nerf, 3d gaussian, ray tracing, illumination  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: relightable, relighting, shadow, gaussian splatting, lighting, dynamic, face, ar, outdoor, global illumination, 3d gaussian, illumination  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: path tracing, gaussian splatting, lighting, dynamic, face, ar, 3d gaussian  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relightable, efficient, relighting, efficient rendering, gaussian splatting, lighting, face, ar, geometry, 3d gaussian, ray marching  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: efficient, gaussian splatting, ar, high-fidelity, ray tracing, real-time rendering  

### Relighting

*Showing the latest 50 out of 118 papers*

- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v1)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v1.pdf)  
  Keywords: relightable, relighting, gaussian splatting, lighting, face, ar, geometry, 3d gaussian  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: gaussian splatting, semantic, dynamic, ar, 3d gaussian, illumination  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: efficient, efficient rendering, reflection, gaussian splatting, face, ar, high-fidelity, geometry, nerf, 3d gaussian, real-time rendering  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relightable, efficient, relighting, sparse-view, body, lighting, tracking, dynamic, motion, ar, human, geometry, 3d gaussian, sparse view, illumination  
- **[Endo-G$^{2}$T: Geometry-Guided & Temporally Aware Time-Embedded 4DGS For Endoscopic Scenes](https://arxiv.org/abs/2511.21367v1)**  
  Authors: Yangle Liu, Fengze Li, Kan Liu, Jieming Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.21367v1.pdf)  
  Keywords: 4d, reflection, gaussian splatting, dynamic, motion, lightweight, ar, geometry, nerf  
- **[CUS-GS: A Compact Unified Structured Gaussian Splatting Framework for Multimodal Scene Representation](https://arxiv.org/abs/2511.17904v1)**  
  Authors: Yuhang Ming, Chenxin Fang, Xingyuan Yu, Fan Zhang, Weichen Dai, Wanzeng Kong, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17904v1.pdf)  
  Keywords: gaussian splatting, understanding, lighting, semantic, dynamic, ar, compact, geometry  
- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: 4d, deformation, gaussian splatting, lighting, dynamic, motion, ar, geometry, 3d gaussian  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: 3d reconstruction, sparse-view, gaussian splatting, face, ar, high-fidelity, geometry, compact, 3d gaussian, illumination  
- **[iGaussian: Real-Time Camera Pose Estimation via Feed-Forward 3D Gaussian Splatting Inversion](https://arxiv.org/abs/2511.14149v1)**  
  Authors: Hao Wang, Linqing Zhao, Xiuwei Xu, Jiwen Lu, Haibin Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14149v1.pdf)  
  Keywords: gaussian splatting, head, lighting, slam, tracking, robotics, ar, nerf, 3d gaussian  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: efficient, relighting, gaussian splatting, lighting, semantic, segmentation, face, ar, outdoor, high-fidelity, geometry, illumination  

### SLAM

*Showing the latest 50 out of 143 papers*

- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: gaussian splatting, tracking, motion, dynamic, animation, ar, 4d  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: 4d, gaussian splatting, understanding, tracking, semantic, segmentation, motion, dynamic, ar, geometry  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, survey, semantic, slam, mapping, robotics, ar, nerf, 3d gaussian  
- **[PoreTrack3D: A Benchmark for Dynamic 3D Gaussian Splatting in Pore-Scale Facial Trajectory Tracking](https://arxiv.org/abs/2512.02648v1)**  
  Authors: Dong Li, Jiahao Xiong, Yingda Huang, Le Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02648v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, tracking, dynamic, motion, face, ar, high-fidelity, 3d gaussian  
- **[Content-Aware Texturing for Gaussian Splatting](https://arxiv.org/abs/2512.02621v1)**  
  Authors: Panagiotis Papantonakis, Georgios Kopanas, Fredo Durand, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02621v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gs-texturing/)  
  Keywords: 3d reconstruction, gaussian splatting, mapping, ar, geometry, real-time rendering  
- **[VIGS-SLAM: Visual Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2512.02293v1)**  
  Authors: Zihan Zhu, Wei Zhang, Norbert Haala, Marc Pollefeys, Daniel Barath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02293v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vigs-slam.github.io)  
  Keywords: gaussian splatting, tracking, slam, mapping, motion, ar, high-fidelity, 3d gaussian  
- **[TagSplat: Topology-Aware Gaussian Splatting for Dynamic Mesh Modeling and Tracking](https://arxiv.org/abs/2512.01329v1)**  
  Authors: Hanzhi Guo, Dongdong Weng, Mo Su, Yixiao Chen, Xiaonuo Dongye, Chenyu Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.01329v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://haza628.github.io/tagSplat/)  
  Keywords: gaussian splatting, tracking, face, dynamic, animation, ar, 4d  
- **[EGG-Fusion: Efficient 3D Reconstruction with Geometry-aware Gaussian Surfel on the Fly](https://arxiv.org/abs/2512.01296v1)**  
  Authors: Xiaokun Pan, Zhenzhe Li, Zhichao Ye, Hongjia Zhai, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.01296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/eggfusion/)  
  Keywords: efficient, 3d reconstruction, gaussian splatting, tracking, slam, mapping, face, ar, geometry, nerf, 3d gaussian  
- **[Binary-Gaussian: Compact and Progressive Representation for 3D Gaussian Segmentation](https://arxiv.org/abs/2512.00944v1)**  
  Authors: An Yang, Chenyu Liu, Jun Du, Jianqing Gao, Jia Pan, Jinshui Hu, Baocai Yin, Bing Yin, Cong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00944v1.pdf)  
  Keywords: efficient, gaussian splatting, head, mapping, semantic, segmentation, ar, compact, 3d gaussian  
- **[Asset-Driven Sematic Reconstruction of Dynamic Scene with Multi-Human-Object Interactions](https://arxiv.org/abs/2512.00547v1)**  
  Authors: Sandika Biswas, Qianyi Wu, Biplab Banerjee, Hamid Rezatofighi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00547v1.pdf)  
  Keywords: deformation, gaussian splatting, mapping, semantic, dynamic, motion, face, fast, ar, human, high-fidelity, geometry, 3d gaussian, vr  

### Scene Understanding

*Showing the latest 50 out of 206 papers*

- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, understanding, semantic, ar, 3d gaussian  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: 4d, gaussian splatting, understanding, semantic, dynamic, ar, geometry, nerf  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: gaussian splatting, semantic, dynamic, ar, 3d gaussian, illumination  
- **[Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting](https://arxiv.org/abs/2512.04731v1)**  
  Authors: Jian Tang, Pu Pang, Haowen Sun, Chengzhong Ma, Xingyu Chen, Hua Huang, Xuguang Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04731v1.pdf)  
  Keywords: gaussian splatting, ar, semantic  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: efficient, gaussian splatting, understanding, head, segmentation, ar, compact, 3d gaussian, sparse view  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: 4d, gaussian splatting, understanding, tracking, semantic, segmentation, motion, dynamic, ar, geometry  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, survey, semantic, slam, mapping, robotics, ar, nerf, 3d gaussian  
- **[ManualVLA: A Unified VLA Model for Chain-of-Thought Manual Generation and Robotic Manipulation](https://arxiv.org/abs/2512.02013v1)**  
  Authors: Chenyang Gu, Jiaming Liu, Hao Chen, Runzhong Huang, Qingpo Wuwu, Zhuoyang Liu, Xiaoqi Li, Ying Li, Renrui Zhang, Peng Jia, Pheng-Ann Heng, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02013v1.pdf)  
  Keywords: gaussian splatting, understanding, face, ar, high-fidelity, 3d gaussian  
- **[LISA-3D: Lifting Language-Image Segmentation to 3D via Multi-View Consistency](https://arxiv.org/abs/2512.01008v1)**  
  Authors: Zhongbin Guo, Jiahe Liu, Wenyu Gao, Yushan Li, Chengzhi Li, Ping Jian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.01008v1.pdf)  
  Keywords: efficient, 3d reconstruction, segmentation, ar, geometry  
- **[Binary-Gaussian: Compact and Progressive Representation for 3D Gaussian Segmentation](https://arxiv.org/abs/2512.00944v1)**  
  Authors: An Yang, Chenyu Liu, Jun Du, Jianqing Gao, Jia Pan, Jinshui Hu, Baocai Yin, Bing Yin, Cong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00944v1.pdf)  
  Keywords: efficient, gaussian splatting, head, mapping, semantic, segmentation, ar, compact, 3d gaussian  



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