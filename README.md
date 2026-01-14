# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-01-14 01:03:22

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
- [Acceleration](#acceleration) (251 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (342 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (398 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (358 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (69 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (412 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (201 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (19 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (126 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (215 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: dynamic, compact, gaussian splatting, compression, ar, high-fidelity, efficient, 4d, 3d reconstruction, survey, 3d gaussian  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: semantic, nerf, understanding, robotics, gaussian splatting, ar, localization, mapping, slam, survey, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: semantic, robotics, gaussian splatting, ar, efficient, high-fidelity, localization, mapping, slam, survey, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: nerf, ar, gaussian splatting, 4d, fast, motion, survey, 3d gaussian, geometry  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: face, ar, gaussian splatting, efficient, avatar, animation, lighting, 3d reconstruction, real-time rendering, efficient rendering, survey, 3d gaussian  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: lightweight, nerf, understanding, ar, gaussian splatting, human, efficient, survey  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: nerf, neural rendering, understanding, gaussian splatting, ar, efficient, fast, slam, survey, 3d gaussian  
- **[A-TDOM: Active TDOM via On-the-Fly 3DGS](https://arxiv.org/abs/2509.12759v3)**  
  Authors: Yiwei Xu, Xiang Wang, Yifei Yu, Wentian Gan, Luca Morelli, Giulio Perda, Xin Wang, Zongqian Zhan, Fabio Remondino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12759v3.pdf)  
  Keywords: face, ar, gaussian splatting, survey, 3d gaussian  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v3)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v3.pdf)  
  Keywords: semantic, nerf, understanding, compact, gaussian splatting, ar, high-fidelity, efficient, lighting, survey, 3d gaussian, segmentation  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: semantic, nerf, understanding, robotics, gaussian splatting, ar, efficient, survey, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 251 papers*

- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[Akasha 2: Hamiltonian State Space Duality and Visual-Language Joint Embedding Predictive Architectur](https://arxiv.org/abs/2601.06212v1)**  
  Authors: Yani Meziani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06212v1.pdf)  
  Keywords: fast, gaussian splatting, 3d gaussian, ar  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v1)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v1.pdf)  
  Keywords: semantic, head, understanding, ar, gaussian splatting, efficient, fast, 3d gaussian, geometry  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: head, ar, gaussian splatting, relighting, 3d gaussian, lighting, real-time rendering, illumination  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: face, neural rendering, sparse view, gaussian splatting, robotics, ar, efficient, 3d reconstruction, efficient rendering, 3d gaussian  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: dynamic, illumination, gaussian splatting, ar, relighting, avatar, fast, mapping, lighting, 3d gaussian, shadow  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, gaussian splatting, ray marching, ar, sparse-view, efficient, 3d reconstruction, efficient rendering, 3d gaussian, shadow  
- **[Contour Information Aware 2D Gaussian Splatting for Image Representation](https://arxiv.org/abs/2512.23255v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai, Zheming Fan, Ryo Ishimoto, Kakeru Sugimoto, Ruri Imichi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.23255v1.pdf)  
  Keywords: lightweight, compact, gaussian splatting, compression, ar, efficient, fast, segmentation  
- **[AirGS: Real-Time 4D Gaussian Streaming for Free-Viewpoint Video Experiences](https://arxiv.org/abs/2512.20943v1)**  
  Authors: Zhe Wang, Jinghang Li, Yifei Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.20943v1.pdf)  
  Keywords: dynamic, lightweight, head, ar, gaussian splatting, efficient, fast, 4d, 3d gaussian  

### Applications

*Showing the latest 50 out of 995 papers*

- **[ViewMorpher3D: A 3D-aware Diffusion Framework for Multi-Camera Novel View Synthesis in Autonomous Driving](https://arxiv.org/abs/2601.07540v1)**  
  Authors: Farhad G. Zanjani, Hong Cai, Amirhossein Habibian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07540v1.pdf)  
  Keywords: ar, gaussian splatting, autonomous driving, 3d reconstruction  
- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: dynamic, lightweight, body, vr, ar, gaussian splatting, human, avatar, motion, 3d gaussian, deformation  
- **[R3-RECON: Radiance-Field-Free Active Reconstruction via Renderability](https://arxiv.org/abs/2601.07484v1)**  
  Authors: Xiaofeng Jin, Matteo Frosi, Yiran Guo, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07484v1.pdf)  
  Keywords: lightweight, neural rendering, ar, gaussian splatting, efficient, 3d gaussian  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, vr, ar, gaussian splatting, motion, 3d gaussian, geometry  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: recognition, gaussian splatting, ar, motion  
- **[NAS-GS: Noise-Aware Sonar Gaussian Splatting](https://arxiv.org/abs/2601.06285v1)**  
  Authors: Shida Xu, Jingqi Jiang, Jonatan Scharff Willners, Sen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06285v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, tracking, ar, gaussian splatting, efficient, mapping, slam, 3d gaussian, segmentation  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: face, dynamic, recognition, gaussian splatting, ar, high-fidelity, avatar, animation, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[Akasha 2: Hamiltonian State Space Duality and Visual-Language Joint Embedding Predictive Architectur](https://arxiv.org/abs/2601.06212v1)**  
  Authors: Yani Meziani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06212v1.pdf)  
  Keywords: fast, gaussian splatting, 3d gaussian, ar  

### Avatar Generation

*Showing the latest 50 out of 342 papers*

- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: dynamic, lightweight, body, vr, ar, gaussian splatting, human, avatar, motion, 3d gaussian, deformation  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: face, dynamic, recognition, gaussian splatting, ar, high-fidelity, avatar, animation, 3d gaussian, segmentation  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v1)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v1.pdf)  
  Keywords: semantic, head, understanding, ar, gaussian splatting, efficient, fast, 3d gaussian, geometry  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: head, illumination, gaussian splatting, relightable, ar, relighting, avatar, high quality, mapping, lighting, 3d gaussian  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: face, ar, gaussian splatting, efficient, avatar, 3d gaussian, deformation, geometry  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: head, ar, gaussian splatting, relighting, 3d gaussian, lighting, real-time rendering, illumination  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: face, neural rendering, sparse view, gaussian splatting, robotics, ar, efficient, 3d reconstruction, efficient rendering, 3d gaussian  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, human, high-fidelity, avatar, mapping, motion, 3d gaussian, geometry  
- **[ESGaussianFace: Emotional and Stylized Audio-Driven Facial Animation via 3D Gaussian Splatting](https://arxiv.org/abs/2601.01847v1)**  
  Authors: Chuhang Ma, Shuai Tan, Ye Pan, Jiaolong Yang, Xin Tong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01847v1.pdf)  
  Keywords: face, head, ar, gaussian splatting, efficient, animation, high quality, motion, 3d gaussian, deformation  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: dynamic, illumination, gaussian splatting, ar, relighting, avatar, fast, mapping, lighting, 3d gaussian, shadow  

### Dynamic Scene

*Showing the latest 50 out of 398 papers*

- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: dynamic, lightweight, body, vr, ar, gaussian splatting, human, avatar, motion, 3d gaussian, deformation  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, vr, ar, gaussian splatting, motion, 3d gaussian, geometry  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: recognition, gaussian splatting, ar, motion  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: face, dynamic, recognition, gaussian splatting, ar, high-fidelity, avatar, animation, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: face, ar, gaussian splatting, efficient, avatar, 3d gaussian, deformation, geometry  
- **[CAMO: Category-Agnostic 3D Motion Transfer from Monocular 2D Videos](https://arxiv.org/abs/2601.02716v1)**  
  Authors: Taeyeon Kim, Youngju Na, Jumin Lee, Minhyuk Sung, Sung-Eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02716v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, motion, 3d gaussian  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, human, high-fidelity, avatar, mapping, motion, 3d gaussian, geometry  
- **[SketchRodGS: Sketch-based Extraction of Slender Geometries for Animating Gaussian Splatting Scenes](https://arxiv.org/abs/2601.02072v1)**  
  Authors: Haato Watanabe, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02072v1.pdf)  
  Keywords: ar, gaussian splatting, dynamic, efficient  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v1)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, efficient, 3d gaussian  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: face, neural rendering, sparse view, gaussian splatting, robotics, ar, efficient, 3d reconstruction, efficient rendering, 3d gaussian  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, gaussian splatting, ray marching, ar, sparse-view, efficient, 3d reconstruction, efficient rendering, 3d gaussian, shadow  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: sparse view, gaussian splatting, ar, high-fidelity, motion, 3d reconstruction, 3d gaussian  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: ar, gaussian splatting, segmentation, relighting, sparse-view, lighting, light transport, geometry  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: face, ar, gaussian splatting, sparse-view, efficient, 3d reconstruction, efficient rendering, 3d gaussian  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: face, dynamic, ar, gaussian splatting, sparse-view, 3d gaussian, deformation  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: lightweight, head, ar, gaussian splatting, sparse-view, efficient, 3d gaussian  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: head, understanding, sparse view, gaussian splatting, compact, ar, efficient, 3d gaussian, segmentation  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: sparse view, gaussian splatting, ar, sparse-view, efficient, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 358 papers*

- **[ViewMorpher3D: A 3D-aware Diffusion Framework for Multi-Camera Novel View Synthesis in Autonomous Driving](https://arxiv.org/abs/2601.07540v1)**  
  Authors: Farhad G. Zanjani, Hong Cai, Amirhossein Habibian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07540v1.pdf)  
  Keywords: ar, gaussian splatting, autonomous driving, 3d reconstruction  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, vr, ar, gaussian splatting, motion, 3d gaussian, geometry  
- **[NAS-GS: Noise-Aware Sonar Gaussian Splatting](https://arxiv.org/abs/2601.06285v1)**  
  Authors: Shida Xu, Jingqi Jiang, Jonatan Scharff Willners, Sen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06285v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[OceanSplat: Object-aware Gaussian Splatting with Trinocular View Consistency for Underwater Scene Reconstruction](https://arxiv.org/abs/2601.04984v1)**  
  Authors: Minseong Kweon, Jinsun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04984v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, geometry  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v1)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v1.pdf)  
  Keywords: semantic, head, understanding, ar, gaussian splatting, efficient, fast, 3d gaussian, geometry  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: semantic, understanding, ar, gaussian splatting, geometry, localization, 3d gaussian, segmentation  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: face, ar, gaussian splatting, efficient, avatar, 3d gaussian, deformation, geometry  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: face, neural rendering, sparse view, gaussian splatting, robotics, ar, efficient, 3d reconstruction, efficient rendering, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 69 papers*

- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: semantic, vr, ar, gaussian splatting, compression, outdoor, 3d gaussian, segmentation  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, face, ar, gaussian splatting, efficient, 3d gaussian, 3d reconstruction, illumination, geometry  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: compact, gaussian splatting, ar, fast, outdoor, 3d gaussian, geometry  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: dynamic, nerf, robotics, gaussian splatting, ar, efficient, outdoor, motion, 4d, 3d gaussian  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: understanding, ar, gaussian splatting, outdoor, 3d reconstruction, 3d gaussian, geometry  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: semantic, ar, gaussian splatting, outdoor, fast, geometry  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: face, semantic, ar, gaussian splatting, segmentation, relighting, high-fidelity, efficient, outdoor, lighting, illumination, geometry  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, outdoor, 3d gaussian, geometry  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: urban scene, dynamic, ar, gaussian splatting, human, autonomous driving, 4d  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: head, ar, gaussian splatting, large scene, fast, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 412 papers*

- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: dynamic, lightweight, body, vr, ar, gaussian splatting, human, avatar, motion, 3d gaussian, deformation  
- **[R3-RECON: Radiance-Field-Free Active Reconstruction via Renderability](https://arxiv.org/abs/2601.07484v1)**  
  Authors: Xiaofeng Jin, Matteo Frosi, Yiran Guo, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07484v1.pdf)  
  Keywords: lightweight, neural rendering, ar, gaussian splatting, efficient, 3d gaussian  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, vr, ar, gaussian splatting, motion, 3d gaussian, geometry  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, tracking, ar, gaussian splatting, efficient, mapping, slam, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v1)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v1.pdf)  
  Keywords: semantic, head, understanding, ar, gaussian splatting, efficient, fast, 3d gaussian, geometry  
- **[SCAR-GS: Spatial Context Attention for Residuals in Progressive Gaussian Splatting](https://arxiv.org/abs/2601.04348v1)**  
  Authors: Diego Revilla, Pooja Suresh, Anand Bhojan, Ooi Wei Tsang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04348v1.pdf)  
  Keywords: ar, gaussian splatting, compression, high-fidelity, 3d gaussian  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v1)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, efficient, 3d gaussian  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: face, ar, gaussian splatting, efficient, avatar, 3d gaussian, deformation, geometry  

### Quality Enhancement

*Showing the latest 50 out of 201 papers*

- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: face, dynamic, recognition, gaussian splatting, ar, high-fidelity, avatar, animation, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[SCAR-GS: Spatial Context Attention for Residuals in Progressive Gaussian Splatting](https://arxiv.org/abs/2601.04348v1)**  
  Authors: Diego Revilla, Pooja Suresh, Anand Bhojan, Ooi Wei Tsang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04348v1.pdf)  
  Keywords: ar, gaussian splatting, compression, high-fidelity, 3d gaussian  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: head, illumination, gaussian splatting, relightable, ar, relighting, avatar, high quality, mapping, lighting, 3d gaussian  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, human, high-fidelity, avatar, mapping, motion, 3d gaussian, geometry  
- **[ESGaussianFace: Emotional and Stylized Audio-Driven Facial Animation via 3D Gaussian Splatting](https://arxiv.org/abs/2601.01847v1)**  
  Authors: Chuhang Ma, Shuai Tan, Ye Pan, Jiaolong Yang, Xin Tong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01847v1.pdf)  
  Keywords: face, head, ar, gaussian splatting, efficient, animation, high quality, motion, 3d gaussian, deformation  
- **[SCPainter: A Unified Framework for Realistic 3D Asset Insertion and Novel View Synthesis](https://arxiv.org/abs/2512.22706v1)**  
  Authors: Paul Dobre, Jackson Cooper, Xin Wang, Hongzhou Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.22706v1.pdf)  
  Keywords: dynamic, ar, high quality, lighting, autonomous driving, 3d gaussian, shadow  
- **[Nebula: Enable City-Scale 3D Gaussian Splatting in Virtual Reality via Collaborative Rendering and Accelerated Stereo Rasterization](https://arxiv.org/abs/2512.20495v1)**  
  Authors: He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Jieru Zhao, Fangxin Liu, Yiming Gan, Jingwen Leng, Yu Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.20495v1.pdf)  
  Keywords: vr, ar, gaussian splatting, high-fidelity, acceleration, motion, 3d gaussian  
- **[Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://arxiv.org/abs/2512.17817v2)**  
  Authors: Yue Li, Qi Ma, Runyi Yang, Mengjiao Ma, Bin Ren, Nikola Popovic, Nicu Sebe, Theo Gevers, Luc Van Gool, Danda Pani Paudel, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17817v2.pdf)  
  Keywords: semantic, ar, gaussian splatting, efficient, high-fidelity, 3d gaussian, segmentation  

### Ray Tracing

- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, gaussian splatting, ray marching, ar, sparse-view, efficient, 3d reconstruction, efficient rendering, 3d gaussian, shadow  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: understanding, ar, gaussian splatting, motion, fast, 3d reconstruction, 3d gaussian, ray tracing, geometry  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: ar, relightable, gaussian splatting, relighting, lighting, 3d reconstruction, ray tracing, geometry  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: face, nerf, ar, gaussian splatting, fast, 3d gaussian, ray tracing  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: compact, gaussian splatting, ar, high-fidelity, fast, real-time rendering, 3d gaussian, ray tracing  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: dynamic, ar, gaussian splatting, reflection, high-fidelity, 3d reconstruction, ray tracing, geometry  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ar, gaussian splatting, reflection, illumination, ray tracing, geometry  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: ar, gaussian splatting, ray marching, efficient, 3d gaussian, geometry  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: face, ar, relightable, gaussian splatting, efficient, lighting, light transport, real-time rendering, ray tracing, shadow  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: ar, gaussian splatting, reflection, relighting, efficient, global illumination, light transport, lighting, illumination, geometry  

### Relighting

*Showing the latest 50 out of 126 papers*

- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: head, illumination, gaussian splatting, relightable, ar, relighting, avatar, high quality, mapping, lighting, 3d gaussian  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: head, ar, gaussian splatting, relighting, 3d gaussian, lighting, real-time rendering, illumination  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: dynamic, illumination, gaussian splatting, ar, relighting, avatar, fast, mapping, lighting, 3d gaussian, shadow  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: illumination, gaussian splatting, ray marching, ar, sparse-view, efficient, 3d reconstruction, efficient rendering, 3d gaussian, shadow  
- **[Improved 3D Gaussian Splatting of Unknown Spacecraft Structure Using Space Environment Illumination Knowledge](https://arxiv.org/abs/2512.23998v1)**  
  Authors: Tae Ha Park, Simone D'Amico  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.23998v1.pdf)  
  Keywords: dynamic, ar, gaussian splatting, 3d gaussian, lighting, illumination, geometry, shadow  
- **[SCPainter: A Unified Framework for Realistic 3D Asset Insertion and Novel View Synthesis](https://arxiv.org/abs/2512.22706v1)**  
  Authors: Paul Dobre, Jackson Cooper, Xin Wang, Hongzhou Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.22706v1.pdf)  
  Keywords: dynamic, ar, high quality, lighting, autonomous driving, 3d gaussian, shadow  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: ar, relightable, gaussian splatting, relighting, lighting, 3d reconstruction, ray tracing, geometry  
- **[Flying in Clutter on Monocular RGB by Learning in 3D Radiance Fields with Domain Adaptation](https://arxiv.org/abs/2512.17349v1)**  
  Authors: Xijie Huang, Jinhan Li, Tianyue Wu, Xin Zhou, Zhichao Han, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17349v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, 3d gaussian, illumination  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: face, semantic, nerf, ar, relightable, gaussian splatting, human, segmentation, high-fidelity, lighting, geometry  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, face, ar, gaussian splatting, efficient, 3d gaussian, 3d reconstruction, illumination, geometry  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, tracking, ar, gaussian splatting, efficient, mapping, slam, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: semantic, understanding, ar, gaussian splatting, geometry, localization, 3d gaussian, segmentation  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: head, illumination, gaussian splatting, relightable, ar, relighting, avatar, high quality, mapping, lighting, 3d gaussian  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, human, high-fidelity, avatar, mapping, motion, 3d gaussian, geometry  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: dynamic, illumination, gaussian splatting, ar, relighting, avatar, fast, mapping, lighting, 3d gaussian, shadow  
- **[ParkGaussian: Surround-view 3D Gaussian Splatting for Autonomous Parking](https://arxiv.org/abs/2601.01386v1)**  
  Authors: Xiaobao Wei, Zhangjie Ye, Yuxiang Gu, Zunjie Zhu, Yunfei Guo, Yingying Shen, Shan Zhao, Ming Lu, Haiyang Sun, Bing Wang, Guang Chen, Rongfeng Lu, Hangjun Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01386v1.pdf)  
  Keywords: ar, gaussian splatting, localization, mapping, 3d reconstruction, 3d gaussian, autonomous driving, geometry  
- **[GVSynergy-Det: Synergistic Gaussian-Voxel Representations for Multi-View 3D Object Detection](https://arxiv.org/abs/2512.23176v1)**  
  Authors: Yi Zhang, Yi Wang, Lei Yao, Lap-Pui Chau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.23176v1.pdf)  
  Keywords: face, ar, gaussian splatting, localization, geometry  
- **[RGS-SLAM: Robust Gaussian Splatting SLAM with One-Shot Dense Initialization](https://arxiv.org/abs/2601.00705v1)**  
  Authors: Wei-Tse Cheng, Yen-Jen Chiou, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00705v1.pdf)  
  Keywords: ar, gaussian splatting, localization, mapping, slam, geometry  
- **[Tracking by Predicting 3-D Gaussians Over Time](https://arxiv.org/abs/2512.22489v2)**  
  Authors: Tanish Baranwal, Himanshu Gaurav Singh, Jathushan Rajasegaran, Jitendra Malik  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.22489v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://videogmae.org/)  
  Keywords: mapping, tracking, dynamic, ar  

### Scene Understanding

*Showing the latest 50 out of 215 papers*

- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: recognition, gaussian splatting, ar, motion  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, tracking, ar, gaussian splatting, efficient, mapping, slam, 3d gaussian, segmentation  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: face, dynamic, recognition, gaussian splatting, ar, high-fidelity, avatar, animation, 3d gaussian, segmentation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, dynamic, compact, gaussian splatting, ar, segmentation, high-fidelity, motion, efficient, fast, real-time rendering, deformation, geometry  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v1)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v1.pdf)  
  Keywords: semantic, head, understanding, ar, gaussian splatting, efficient, fast, 3d gaussian, geometry  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: semantic, understanding, ar, gaussian splatting, geometry, localization, 3d gaussian, segmentation  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, high-fidelity, efficient, fast, motion, 3d gaussian, geometry  
- **[CAMO: Category-Agnostic 3D Motion Transfer from Monocular 2D Videos](https://arxiv.org/abs/2601.02716v1)**  
  Authors: Taeyeon Kim, Youngju Na, Jumin Lee, Minhyuk Sung, Sung-Eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02716v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, motion, 3d gaussian  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, human, high-fidelity, avatar, mapping, motion, 3d gaussian, geometry  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: semantic, vr, ar, gaussian splatting, compression, outdoor, 3d gaussian, segmentation  



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