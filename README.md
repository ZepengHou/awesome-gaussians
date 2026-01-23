# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-01-23 01:02:33

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

- [3DGS Surveys](#3dgs-surveys) (24 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (245 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (341 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (396 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (358 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (68 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (205 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (17 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (129 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (153 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (215 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, nerf, survey, geometry, efficient, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, dynamic, compact, survey, 3d reconstruction, compression, efficient, ar, 4d, high-fidelity  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, localization, nerf, mapping, survey, semantic, slam, ar, understanding  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, localization, mapping, survey, semantic, slam, efficient, ar, high-fidelity  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 3d gaussian, gaussian splatting, fast, nerf, motion, survey, geometry, 4d, ar  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: animation, lighting, face, 3d gaussian, gaussian splatting, avatar, survey, 3d reconstruction, efficient rendering, efficient, real-time rendering, ar  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: lightweight, human, gaussian splatting, nerf, survey, efficient, ar, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, fast, nerf, survey, neural rendering, slam, efficient, ar, understanding  
- **[A-TDOM: Active TDOM via On-the-Fly 3DGS](https://arxiv.org/abs/2509.12759v3)**  
  Authors: Yiwei Xu, Xiang Wang, Yifei Yu, Wentian Gan, Luca Morelli, Giulio Perda, Xin Wang, Zongqian Zhan, Fabio Remondino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12759v3.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, survey, ar  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v3)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v3.pdf)  
  Keywords: understanding, lighting, 3d gaussian, gaussian splatting, compact, nerf, survey, semantic, segmentation, efficient, ar, high-fidelity  

### Acceleration

*Showing the latest 50 out of 245 papers*

- **[POTR: Post-Training 3DGS Compression](https://arxiv.org/abs/2601.14821v1)**  
  Authors: Bert Ramlot, Martijn Courteaux, Peter Lambert, Glenn Van Wallendael  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14821v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, nerf, compression, efficient, ar  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v1)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v1.pdf)  
  Keywords: gaussian splatting, nerf, mapping, compression, efficient, real-time rendering, ar  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, semantic, compression, efficient, segmentation, real-time rendering, ar, understanding  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, dynamic, vr, real-time rendering, ar, high-fidelity  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, gaussian splatting, fast, dynamic, motion, compact, segmentation, geometry, efficient, real-time rendering, ar, deformation, high-fidelity  
- **[Akasha 2: Hamiltonian State Space Duality and Visual-Language Joint Embedding Predictive Architectur](https://arxiv.org/abs/2601.06212v1)**  
  Authors: Yani Meziani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06212v1.pdf)  
  Keywords: gaussian splatting, fast, 3d gaussian, ar  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: 3d gaussian, head, gaussian splatting, fast, semantic, geometry, efficient, ar, understanding  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, fast, motion, semantic, geometry, efficient, ar, high-fidelity  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: lighting, 3d gaussian, head, gaussian splatting, illumination, real-time rendering, ar, relighting  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: sparse view, face, robotics, 3d gaussian, gaussian splatting, neural rendering, 3d reconstruction, efficient rendering, efficient, ar  

### Applications

*Showing the latest 50 out of 995 papers*

- **[LuxRemix: Lighting Decomposition and Remixing for Indoor Scenes](https://arxiv.org/abs/2601.15283v1)**  
  Authors: Ruofan Liang, Norman Müller, Ethan Weber, Duncan Zauss, Nandita Vijaykumar, Peter Kontschieder, Christian Richardt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luxremix.github.io.)  
  Keywords: lighting, 3d gaussian, gaussian splatting, illumination, relightable, relighting, ar  
- **[POTR: Post-Training 3DGS Compression](https://arxiv.org/abs/2601.14821v1)**  
  Authors: Bert Ramlot, Martijn Courteaux, Peter Lambert, Glenn Van Wallendael  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14821v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, nerf, compression, efficient, ar  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v1)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v1.pdf)  
  Keywords: gaussian splatting, nerf, mapping, compression, efficient, real-time rendering, ar  
- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, motion, ar  
- **[One-Shot Refiner: Boosting Feed-forward Novel View Synthesis via One-Step Diffusion](https://arxiv.org/abs/2601.14161v1)**  
  Authors: Yitong Dong, Qi Zhang, Minchao Jiang, Zhiqiang Wu, Qingnan Fan, Ying Feng, Huaqi Zhang, Hujun Bao, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14161v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, high-fidelity  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[GaussExplorer: 3D Gaussian Splatting for Embodied Exploration and Reasoning](https://arxiv.org/abs/2601.13132v1)**  
  Authors: Kim Yu-Ji, Dahye Lee, Kim Jun-Seong, GeonU Kim, Nam Hyeon-Woo, Yongjin Kwon, Yu-Chiang Frank Wang, Jaesung Choe, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13132v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, nerf, survey, geometry, efficient, ar  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, semantic, compression, efficient, segmentation, real-time rendering, ar, understanding  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: face, gaussian splatting, compact, geometry, ar  

### Avatar Generation

*Showing the latest 50 out of 341 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: face, gaussian splatting, compact, geometry, ar  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: face, 3d gaussian, head, gaussian splatting, dynamic, avatar, motion, vr, efficient, ar, high-fidelity  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, motion, geometry, ar, deformation  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: lightweight, face, 3d gaussian, head, gaussian splatting, ar, high-fidelity  
- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: lightweight, human, body, 3d gaussian, gaussian splatting, dynamic, avatar, motion, vr, ar, deformation  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: recognition, animation, face, 3d gaussian, gaussian splatting, dynamic, avatar, segmentation, ar, high-fidelity  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: 3d gaussian, head, gaussian splatting, fast, semantic, geometry, efficient, ar, understanding  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: lighting, 3d gaussian, head, gaussian splatting, illumination, avatar, mapping, high quality, relightable, relighting, ar  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, avatar, geometry, efficient, ar, deformation  

### Dynamic Scene

*Showing the latest 50 out of 396 papers*

- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, motion, ar  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: face, 3d gaussian, head, gaussian splatting, dynamic, avatar, motion, vr, efficient, ar, high-fidelity  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, motion, geometry, ar, deformation  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, dynamic, vr, real-time rendering, ar, high-fidelity  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, geometry, efficient, ar, deformation, quality enhancement  
- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: lightweight, human, body, 3d gaussian, gaussian splatting, dynamic, avatar, motion, vr, ar, deformation  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, motion, geometry, vr, ar  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: recognition, gaussian splatting, motion, ar  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: recognition, animation, face, 3d gaussian, gaussian splatting, dynamic, avatar, segmentation, ar, high-fidelity  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, efficient, ar  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: sparse view, face, robotics, 3d gaussian, gaussian splatting, neural rendering, 3d reconstruction, efficient rendering, efficient, ar  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, illumination, sparse-view, shadow, 3d reconstruction, efficient rendering, efficient, ray marching, ar  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: sparse view, 3d gaussian, gaussian splatting, motion, 3d reconstruction, ar, high-fidelity  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: lighting, light transport, gaussian splatting, sparse-view, segmentation, geometry, ar, relighting  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, sparse-view, 3d reconstruction, efficient rendering, efficient, ar  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, dynamic, sparse-view, ar, deformation  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: lightweight, 3d gaussian, head, gaussian splatting, sparse-view, efficient, ar  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: sparse view, 3d gaussian, head, gaussian splatting, compact, segmentation, efficient, ar, understanding  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: sparse view, 3d gaussian, gaussian splatting, sparse-view, efficient, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 358 papers*

- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, motion, ar  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, nerf, survey, geometry, efficient, ar  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: face, gaussian splatting, compact, geometry, ar  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, motion, geometry, ar, deformation  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, geometry, efficient, ar, deformation, quality enhancement  
- **[ViewMorpher3D: A 3D-aware Diffusion Framework for Multi-Camera Novel View Synthesis in Autonomous Driving](https://arxiv.org/abs/2601.07540v2)**  
  Authors: Farhad G. Zanjani, Hong Cai, Amirhossein Habibian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07540v2.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, ar, autonomous driving  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, motion, geometry, vr, ar  
- **[NAS-GS: Noise-Aware Sonar Gaussian Splatting](https://arxiv.org/abs/2601.06285v1)**  
  Authors: Shida Xu, Jingqi Jiang, Jonatan Scharff Willners, Sen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06285v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, 3d gaussian, ar  

### Large Scene

*Showing the latest 50 out of 68 papers*

- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, semantic, compression, segmentation, vr, ar, outdoor  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, face, 3d gaussian, gaussian splatting, illumination, 3d reconstruction, geometry, efficient, ar  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, fast, compact, geometry, ar, outdoor  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, dynamic, nerf, motion, efficient, 4d, outdoor, ar  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, geometry, ar, outdoor, understanding  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: gaussian splatting, fast, semantic, geometry, ar, outdoor  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: face, lighting, gaussian splatting, illumination, semantic, geometry, efficient, segmentation, ar, outdoor, relighting, high-fidelity  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, ar, outdoor, high-fidelity  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: urban scene, human, autonomous driving, gaussian splatting, dynamic, 4d, ar  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: 3d gaussian, head, gaussian splatting, fast, large scene, ar  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[POTR: Post-Training 3DGS Compression](https://arxiv.org/abs/2601.14821v1)**  
  Authors: Bert Ramlot, Martijn Courteaux, Peter Lambert, Glenn Van Wallendael  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14821v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, nerf, compression, efficient, ar  
- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v1)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v1.pdf)  
  Keywords: gaussian splatting, nerf, mapping, compression, efficient, real-time rendering, ar  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, nerf, survey, geometry, efficient, ar  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, semantic, compression, efficient, segmentation, real-time rendering, ar, understanding  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: face, gaussian splatting, compact, geometry, ar  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: face, 3d gaussian, head, gaussian splatting, dynamic, avatar, motion, vr, efficient, ar, high-fidelity  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, compact, mapping, efficient, ar  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: lightweight, face, 3d gaussian, head, gaussian splatting, ar, high-fidelity  

### Quality Enhancement

*Showing the latest 50 out of 205 papers*

- **[One-Shot Refiner: Boosting Feed-forward Novel View Synthesis via One-Step Diffusion](https://arxiv.org/abs/2601.14161v1)**  
  Authors: Yitong Dong, Qi Zhang, Minchao Jiang, Zhiqiang Wu, Qingnan Fan, Ying Feng, Huaqi Zhang, Hujun Bao, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14161v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, high-fidelity  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: face, 3d gaussian, head, gaussian splatting, dynamic, avatar, motion, vr, efficient, ar, high-fidelity  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: lightweight, face, 3d gaussian, head, gaussian splatting, ar, high-fidelity  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, dynamic, vr, real-time rendering, ar, high-fidelity  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, geometry, efficient, ar, deformation, quality enhancement  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: recognition, animation, face, 3d gaussian, gaussian splatting, dynamic, avatar, segmentation, ar, high-fidelity  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, gaussian splatting, fast, dynamic, motion, compact, segmentation, geometry, efficient, real-time rendering, ar, deformation, high-fidelity  
- **[OceanSplat: Object-aware Gaussian Splatting with Trinocular View Consistency for Underwater Scene Reconstruction](https://arxiv.org/abs/2601.04984v2)**  
  Authors: Minseong Kweon, Jinsun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04984v2.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, high-fidelity  

### Ray Tracing

- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, illumination, sparse-view, shadow, 3d reconstruction, efficient rendering, efficient, ray marching, ar  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: 3d gaussian, ray tracing, gaussian splatting, fast, motion, 3d reconstruction, geometry, ar, understanding  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: lighting, ray tracing, gaussian splatting, 3d reconstruction, geometry, relightable, relighting, ar  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: face, 3d gaussian, ray tracing, gaussian splatting, fast, nerf, ar  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: 3d gaussian, ray tracing, gaussian splatting, fast, compact, real-time rendering, ar, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: ray tracing, gaussian splatting, dynamic, 3d reconstruction, geometry, reflection, ar, high-fidelity  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ray tracing, gaussian splatting, illumination, geometry, reflection, ar  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: 3d gaussian, gaussian splatting, geometry, efficient, ray marching, ar  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: face, lighting, ray tracing, gaussian splatting, light transport, shadow, efficient, real-time rendering, relightable, ar  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: lighting, light transport, gaussian splatting, illumination, geometry, reflection, efficient, ar, relighting, global illumination  

### Relighting

*Showing the latest 50 out of 129 papers*

- **[LuxRemix: Lighting Decomposition and Remixing for Indoor Scenes](https://arxiv.org/abs/2601.15283v1)**  
  Authors: Ruofan Liang, Norman Müller, Ethan Weber, Duncan Zauss, Nandita Vijaykumar, Peter Kontschieder, Christian Richardt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luxremix.github.io.)  
  Keywords: lighting, 3d gaussian, gaussian splatting, illumination, relightable, relighting, ar  
- **[POTR: Post-Training 3DGS Compression](https://arxiv.org/abs/2601.14821v1)**  
  Authors: Bert Ramlot, Martijn Courteaux, Peter Lambert, Glenn Van Wallendael  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14821v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, nerf, compression, efficient, ar  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[studentSplat: Your Student Model Learns Single-view 3D Gaussian Splatting](https://arxiv.org/abs/2601.11772v1)**  
  Authors: Yimu Pan, Hongda Mao, Qingshuang Chen, Yelin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.11772v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, ar, understanding  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, dynamic, vr, real-time rendering, ar, high-fidelity  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: lighting, 3d gaussian, head, gaussian splatting, illumination, avatar, mapping, high quality, relightable, relighting, ar  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: lighting, 3d gaussian, head, gaussian splatting, illumination, real-time rendering, ar, relighting  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, illumination, dynamic, avatar, mapping, shadow, ar, relighting  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, illumination, sparse-view, shadow, 3d reconstruction, efficient rendering, efficient, ray marching, ar  

### SLAM

*Showing the latest 50 out of 153 papers*

- **[Structured Image-based Coding for Efficient Gaussian Splatting Compression](https://arxiv.org/abs/2601.14510v1)**  
  Authors: Pedro Martin, Antonio Rodrigues, Joao Ascenso, Maria Paula Queluz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14510v1.pdf)  
  Keywords: gaussian splatting, nerf, mapping, compression, efficient, real-time rendering, ar  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, compact, mapping, efficient, ar  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, mapping, segmentation, semantic, efficient, slam, ar  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, gaussian splatting, fast, dynamic, motion, compact, segmentation, geometry, efficient, real-time rendering, ar, deformation, high-fidelity  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, localization, segmentation, semantic, geometry, ar, understanding  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: lighting, 3d gaussian, head, gaussian splatting, illumination, avatar, mapping, high quality, relightable, relighting, ar  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: human, 3d gaussian, gaussian splatting, avatar, mapping, motion, semantic, geometry, ar, high-fidelity  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, fast, illumination, dynamic, avatar, mapping, shadow, ar, relighting  

### Scene Understanding

*Showing the latest 50 out of 215 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: lightweight, face, lighting, 3d gaussian, gaussian splatting, illumination, dynamic, mapping, neural rendering, 3d reconstruction, geometry, semantic, ar, high-fidelity  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, semantic, compression, efficient, segmentation, real-time rendering, ar, understanding  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: lighting, robotics, 3d gaussian, gaussian splatting, mapping, 3d reconstruction, semantic, efficient, segmentation, ar, high-fidelity  
- **[studentSplat: Your Student Model Learns Single-view 3D Gaussian Splatting](https://arxiv.org/abs/2601.11772v1)**  
  Authors: Yimu Pan, Hongda Mao, Qingshuang Chen, Yelin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.11772v1.pdf)  
  Keywords: lighting, 3d gaussian, gaussian splatting, ar, understanding  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: recognition, gaussian splatting, motion, ar  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: tracking, 3d gaussian, gaussian splatting, mapping, segmentation, semantic, efficient, slam, ar  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: recognition, animation, face, 3d gaussian, gaussian splatting, dynamic, avatar, segmentation, ar, high-fidelity  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: tracking, gaussian splatting, fast, dynamic, motion, compact, segmentation, geometry, efficient, real-time rendering, ar, deformation, high-fidelity  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: 3d gaussian, head, gaussian splatting, fast, semantic, geometry, efficient, ar, understanding  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, localization, segmentation, semantic, geometry, ar, understanding  



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