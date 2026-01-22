# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-01-22 01:02:37

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
- [Acceleration](#acceleration) (244 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (343 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (396 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (360 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (69 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (205 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (17 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (127 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (152 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (216 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: 3d gaussian, gaussian splatting, survey, geometry, nerf, efficient, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, survey, dynamic, compression, 3d reconstruction, efficient, 4d, ar, compact  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, survey, slam, localization, nerf, ar, robotics, mapping  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, survey, slam, localization, efficient, ar, robotics, mapping  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 3d gaussian, gaussian splatting, survey, geometry, fast, nerf, 4d, ar, motion  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, efficient rendering, 3d gaussian, gaussian splatting, survey, real-time rendering, lighting, 3d reconstruction, efficient, face, ar, animation  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: understanding, lightweight, survey, gaussian splatting, nerf, efficient, human, ar  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, survey, slam, fast, neural rendering, nerf, efficient, ar  
- **[A-TDOM: Active TDOM via On-the-Fly 3DGS](https://arxiv.org/abs/2509.12759v3)**  
  Authors: Yiwei Xu, Xiang Wang, Yifei Yu, Wentian Gan, Luca Morelli, Giulio Perda, Xin Wang, Zongqian Zhan, Fabio Remondino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12759v3.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, face, ar  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v3)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v3.pdf)  
  Keywords: understanding, high-fidelity, semantic, 3d gaussian, gaussian splatting, survey, lighting, nerf, efficient, ar, segmentation, compact  

### Acceleration

*Showing the latest 50 out of 244 papers*

- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: understanding, semantic, lightweight, 3d gaussian, gaussian splatting, real-time rendering, compression, efficient, ar, segmentation  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, dynamic, real-time rendering, lighting, vr, ar, robotics  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, geometry, real-time rendering, fast, efficient, tracking, ar, deformation, segmentation, compact, motion  
- **[Akasha 2: Hamiltonian State Space Duality and Visual-Language Joint Embedding Predictive Architectur](https://arxiv.org/abs/2601.06212v1)**  
  Authors: Yani Meziani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06212v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, fast  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, head, geometry, fast, efficient, ar  
- **[A High-Fidelity Digital Twin for Robotic Manipulation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2601.03200v1)**  
  Authors: Ziyang Sun, Lingfan Bao, Tianhu Peng, Jingcheng Sun, Chengxu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03200v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, geometry, fast, efficient, ar, motion  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, head, real-time rendering, lighting, illumination, ar, relighting  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, 3d reconstruction, neural rendering, efficient, face, ar, sparse view, robotics  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, dynamic, ar, lighting, fast, illumination, shadow, relighting, mapping  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, ar, sparse-view, 3d reconstruction, illumination, efficient, ray marching, shadow  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, motion  
- **[One-Shot Refiner: Boosting Feed-forward Novel View Synthesis via One-Step Diffusion](https://arxiv.org/abs/2601.14161v1)**  
  Authors: Yitong Dong, Qi Zhang, Minchao Jiang, Zhiqiang Wu, Qingnan Fan, Ying Feng, Huaqi Zhang, Hujun Bao, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14161v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[GaussExplorer: 3D Gaussian Splatting for Embodied Exploration and Reasoning](https://arxiv.org/abs/2601.13132v1)**  
  Authors: Kim Yu-Ji, Dahye Lee, Kim Jun-Seong, GeonU Kim, Nam Hyeon-Woo, Yongjin Kwon, Yu-Chiang Frank Wang, Jaesung Choe, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13132v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, geometry, nerf, efficient, ar  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: understanding, semantic, lightweight, 3d gaussian, gaussian splatting, real-time rendering, compression, efficient, ar, segmentation  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: gaussian splatting, geometry, face, ar, compact  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[studentSplat: Your Student Model Learns Single-view 3D Gaussian Splatting](https://arxiv.org/abs/2601.11772v1)**  
  Authors: Yimu Pan, Hongda Mao, Qingshuang Chen, Yelin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.11772v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, lighting, ar  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, head, efficient, face, vr, ar, motion  

### Avatar Generation

*Showing the latest 50 out of 343 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: gaussian splatting, geometry, face, ar, compact  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, head, efficient, face, vr, ar, motion  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, face, ar, deformation, motion  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: high-fidelity, lightweight, 3d gaussian, gaussian splatting, head, face, ar  
- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: lightweight, avatar, 3d gaussian, gaussian splatting, dynamic, body, human, vr, ar, deformation, motion  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, face, ar, segmentation, recognition, animation  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, head, geometry, fast, efficient, ar  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, head, relightable, lighting, illumination, ar, mapping, relighting, high quality  
- **[CaricatureGS: Exaggerating 3D Gaussian Splatting Faces With Gaussian Curvature](https://arxiv.org/abs/2601.03319v1)**  
  Authors: Eldad Matmon, Amit Bracha, Noam Rotstein, Ron Kimmel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03319v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, geometry, efficient, face, ar, deformation  

### Dynamic Scene

*Showing the latest 50 out of 396 papers*

- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, motion  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, head, efficient, face, vr, ar, motion  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, face, ar, deformation, motion  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, dynamic, real-time rendering, lighting, vr, ar, robotics  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, quality enhancement, geometry, efficient, ar, deformation, motion  
- **[Mon3tr: Monocular 3D Telepresence with Pre-built Gaussian Avatars as Amortization](https://arxiv.org/abs/2601.07518v1)**  
  Authors: Fangyu Lin, Yingdong Hu, Zhening Liu, Yufan Zhuang, Zehong Lin, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07518v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mon3tr3d.github.io.)  
  Keywords: lightweight, avatar, 3d gaussian, gaussian splatting, dynamic, body, human, vr, ar, deformation, motion  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, geometry, vr, ar, motion  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: ar, gaussian splatting, recognition, motion  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, face, ar, segmentation, recognition, animation  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, sparse-view, ar  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, 3d reconstruction, neural rendering, efficient, face, ar, sparse view, robotics  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, ar, sparse-view, 3d reconstruction, illumination, efficient, ray marching, shadow  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v2)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, 3d reconstruction, ar, sparse view, motion  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: gaussian splatting, geometry, lighting, segmentation, sparse-view, ar, light transport, relighting  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, 3d reconstruction, efficient, face, sparse-view, ar  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, dynamic, face, sparse-view, ar, deformation  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, head, efficient, sparse-view, ar  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, head, compact, efficient, ar, segmentation, sparse view  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, sparse-view, ar, sparse view  

### Geometry Reconstruction

*Showing the latest 50 out of 360 papers*

- **[Rig-Aware 3D Reconstruction of Vehicle Undercarriages using Gaussian Splatting](https://arxiv.org/abs/2601.14208v1)**  
  Authors: Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Dan Buckmaster, Philip Schneider, Chunming Qiao, Alina Vereshchaka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14208v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, motion  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, geometry, nerf, efficient, ar  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: gaussian splatting, geometry, face, ar, compact  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[Thinking Like Van Gogh: Structure-Aware Style Transfer via Flow-Guided 3D Gaussian Splatting](https://arxiv.org/abs/2601.10075v1)**  
  Authors: Zhendong Wang, Lebin Zhou, Jingchuan Xiao, Rongduo Han, Nam Ling, Cihan Ruan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10075v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, face, ar, deformation, motion  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, quality enhancement, geometry, efficient, ar, deformation, motion  
- **[ViewMorpher3D: A 3D-aware Diffusion Framework for Multi-Camera Novel View Synthesis in Autonomous Driving](https://arxiv.org/abs/2601.07540v2)**  
  Authors: Farhad G. Zanjani, Hong Cai, Amirhossein Habibian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07540v2.pdf)  
  Keywords: ar, autonomous driving, gaussian splatting, 3d reconstruction  
- **[SARA: Scene-Aware Reconstruction Accelerator](https://arxiv.org/abs/2601.06831v1)**  
  Authors: Jee Won Lee, Hansol Lim, Minhyeok Im, Dohyeon Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06831v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, geometry, vr, ar, motion  
- **[NAS-GS: Noise-Aware Sonar Gaussian Splatting](https://arxiv.org/abs/2601.06285v1)**  
  Authors: Shida Xu, Jingqi Jiang, Jonatan Scharff Willners, Sen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06285v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, 3d reconstruction  

### Large Scene

*Showing the latest 50 out of 69 papers*

- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: semantic, 3d gaussian, gaussian splatting, compression, segmentation, vr, ar, outdoor  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, urban scene, 3d reconstruction, illumination, efficient, face, ar  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, geometry, fast, ar, outdoor, compact  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, dynamic, nerf, 4d, efficient, ar, outdoor, robotics, motion  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: understanding, 3d gaussian, gaussian splatting, geometry, 3d reconstruction, ar, outdoor  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: semantic, gaussian splatting, geometry, fast, ar, outdoor  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: high-fidelity, semantic, gaussian splatting, geometry, lighting, illumination, efficient, face, segmentation, ar, outdoor, relighting  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, geometry, ar, outdoor  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: autonomous driving, dynamic, gaussian splatting, urban scene, 4d, human, ar  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: large scene, 3d gaussian, head, gaussian splatting, fast, ar  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v1)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, geometry, nerf, efficient, ar  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: understanding, semantic, lightweight, 3d gaussian, gaussian splatting, real-time rendering, compression, efficient, ar, segmentation  
- **[KaoLRM: Repurposing Pre-trained Large Reconstruction Models for Parametric 3D Face Reconstruction](https://arxiv.org/abs/2601.12736v1)**  
  Authors: Qingtian Zhu, Xu Cao, Zhixiang Wang, Yinqiang Zheng, Takafumi Taketomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12736v1.pdf)  
  Keywords: gaussian splatting, geometry, face, ar, compact  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, head, efficient, face, vr, ar, motion  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, efficient, ar, compact, mapping  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: high-fidelity, lightweight, 3d gaussian, gaussian splatting, head, face, ar  
- **[A$^2$TG: Adaptive Anisotropic Textured Gaussians for Efficient 3D Scene Representation](https://arxiv.org/abs/2601.09243v1)**  
  Authors: Sheng-Chi Hsu, Ting-Yu Yen, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09243v1.pdf)  
  Keywords: ar, gaussian splatting, efficient  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, quality enhancement, geometry, efficient, ar, deformation, motion  

### Quality Enhancement

*Showing the latest 50 out of 205 papers*

- **[One-Shot Refiner: Boosting Feed-forward Novel View Synthesis via One-Step Diffusion](https://arxiv.org/abs/2601.14161v1)**  
  Authors: Yitong Dong, Qi Zhang, Minchao Jiang, Zhiqiang Wu, Qingnan Fan, Ying Feng, Huaqi Zhang, Hujun Bao, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.14161v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity  
- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation](https://arxiv.org/abs/2601.10606v1)**  
  Authors: Peng Chen, Xiaobao Wei, Yi Yang, Naiming Yao, Hui Chen, Feng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.10606v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, head, efficient, face, vr, ar, motion  
- **[TIDI-GS: Floater Suppression in 3D Gaussian Splatting for Enhanced Indoor Scene Fidelity](https://arxiv.org/abs/2601.09291v2)**  
  Authors: Sooyeun Yang, Cheyul Im, Jee Won Lee, Jongseong Brad Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09291v2.pdf)  
  Keywords: high-fidelity, lightweight, 3d gaussian, gaussian splatting, head, face, ar  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, dynamic, real-time rendering, lighting, vr, ar, robotics  
- **[3DGS-Drag: Dragging Gaussians for Intuitive Point-Based 3D Editing](https://arxiv.org/abs/2601.07963v1)**  
  Authors: Jiahua Dong, Yu-Xiong Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.07963v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, quality enhancement, geometry, efficient, ar, deformation, motion  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, face, ar, segmentation, recognition, animation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, geometry, real-time rendering, fast, efficient, tracking, ar, deformation, segmentation, compact, motion  
- **[OceanSplat: Object-aware Gaussian Splatting with Trinocular View Consistency for Underwater Scene Reconstruction](https://arxiv.org/abs/2601.04984v2)**  
  Authors: Minseong Kweon, Jinsun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04984v2.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity  

### Ray Tracing

- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, ar, sparse-view, 3d reconstruction, illumination, efficient, ray marching, shadow  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: understanding, ray tracing, 3d gaussian, gaussian splatting, geometry, 3d reconstruction, fast, ar, motion  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: ray tracing, gaussian splatting, geometry, relightable, lighting, 3d reconstruction, ar, relighting  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: ray tracing, 3d gaussian, gaussian splatting, fast, nerf, face, ar  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: high-fidelity, ray tracing, 3d gaussian, gaussian splatting, real-time rendering, fast, ar, compact  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: high-fidelity, ray tracing, dynamic, gaussian splatting, reflection, geometry, 3d reconstruction, ar  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ray tracing, gaussian splatting, reflection, geometry, illumination, ar  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: 3d gaussian, gaussian splatting, geometry, efficient, ray marching, ar  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: ray tracing, gaussian splatting, relightable, real-time rendering, ar, lighting, efficient, face, shadow, light transport  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: gaussian splatting, reflection, geometry, lighting, illumination, efficient, ar, light transport, relighting, global illumination  

### Relighting

*Showing the latest 50 out of 127 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[studentSplat: Your Student Model Learns Single-view 3D Gaussian Splatting](https://arxiv.org/abs/2601.11772v1)**  
  Authors: Yimu Pan, Hongda Mao, Qingshuang Chen, Yelin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.11772v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, lighting, ar  
- **[GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://arxiv.org/abs/2601.09265v1)**  
  Authors: Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09265v1.pdf)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, dynamic, real-time rendering, lighting, vr, ar, robotics  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, head, relightable, lighting, illumination, ar, mapping, relighting, high quality  
- **[HeadLighter: Disentangling Illumination in Generative 3D Gaussian Heads via Lightstage Captures](https://arxiv.org/abs/2601.02103v1)**  
  Authors: Yating Wang, Yuan Sun, Xuan Wang, Ran Yi, Boyao Zhou, Yipengjing Sun, Hongyu Liu, Yinuo Wang, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02103v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, head, real-time rendering, lighting, illumination, ar, relighting  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, dynamic, ar, lighting, fast, illumination, shadow, relighting, mapping  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: efficient rendering, 3d gaussian, gaussian splatting, ar, sparse-view, 3d reconstruction, illumination, efficient, ray marching, shadow  
- **[Improved 3D Gaussian Splatting of Unknown Spacecraft Structure Using Space Environment Illumination Knowledge](https://arxiv.org/abs/2512.23998v1)**  
  Authors: Tae Ha Park, Simone D'Amico  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.23998v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, dynamic, geometry, ar, lighting, illumination, shadow  
- **[SCPainter: A Unified Framework for Realistic 3D Asset Insertion and Novel View Synthesis](https://arxiv.org/abs/2512.22706v1)**  
  Authors: Paul Dobre, Jackson Cooper, Xin Wang, Hongzhou Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.22706v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, dynamic, ar, lighting, shadow, high quality  

### SLAM

*Showing the latest 50 out of 152 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[Variable Basis Mapping for Real-Time Volumetric Visualization](https://arxiv.org/abs/2601.09417v1)**  
  Authors: Qibiao Li, Yuxuan Wang, Youcheng Cai, Huangsheng Du, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.09417v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, efficient, ar, compact, mapping  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, 3d gaussian, gaussian splatting, slam, efficient, tracking, ar, segmentation, mapping  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, geometry, real-time rendering, fast, efficient, tracking, ar, deformation, segmentation, compact, motion  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, geometry, localization, ar, segmentation  
- **[RelightAnyone: A Generalized Relightable 3D Gaussian Head Model](https://arxiv.org/abs/2601.03357v1)**  
  Authors: Yingyan Xu, Pramod Rao, Sebastian Weiss, Gaspard Zoss, Markus Gross, Christian Theobalt, Marc Habermann, Derek Bradley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03357v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, head, relightable, lighting, illumination, ar, mapping, relighting, high quality  
- **[InpaintHuman: Reconstructing Occluded Humans with Multi-Scale UV Mapping and Identity-Preserving Diffusion Inpainting](https://arxiv.org/abs/2601.02098v1)**  
  Authors: Jinlong Fan, Shanshan Zhao, Liang Zheng, Jing Zhang, Yuxiang Yang, Mingming Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02098v1.pdf)  
  Keywords: high-fidelity, semantic, avatar, 3d gaussian, gaussian splatting, geometry, human, ar, motion, mapping  
- **[Animated 3DGS Avatars in Diverse Scenes with Consistent Lighting and Shadows](https://arxiv.org/abs/2601.01660v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01660v1.pdf)  
  Keywords: avatar, 3d gaussian, gaussian splatting, dynamic, ar, lighting, fast, illumination, shadow, relighting, mapping  
- **[ParkGaussian: Surround-view 3D Gaussian Splatting for Autonomous Parking](https://arxiv.org/abs/2601.01386v1)**  
  Authors: Xiaobao Wei, Zhangjie Ye, Yuxiang Gu, Zunjie Zhu, Yunfei Guo, Yingying Shen, Shan Zhao, Ming Lu, Haiyang Sun, Bing Wang, Guang Chen, Rongfeng Lu, Hangjun Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.01386v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, gaussian splatting, geometry, localization, 3d reconstruction, ar, mapping  

### Scene Understanding

*Showing the latest 50 out of 216 papers*

- **[ParkingTwin: Training-Free Streaming 3D Reconstruction for Parking-Lot Digital Twins](https://arxiv.org/abs/2601.13706v1)**  
  Authors: Xinhao Liu, Yu Wang, Xiansheng Guo, Gordon Owusu Boateng, Yu Cao, Haonan Si, Xingchen Guo, Nirwan Ansari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.13706v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mihoutao-liu.github.io/ParkingTwin/)  
  Keywords: high-fidelity, lightweight, semantic, 3d gaussian, gaussian splatting, dynamic, geometry, lighting, 3d reconstruction, neural rendering, illumination, face, ar, mapping  
- **[CSGaussian: Progressive Rate-Distortion Compression and Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2601.12814v1)**  
  Authors: Yu-Jen Tseng, Chia-Hao Kao, Jing-Zhong Chen, Alessandro Gnutti, Shao-Yuan Lo, Yen-Yu Lin, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12814v1.pdf)  
  Keywords: understanding, semantic, lightweight, 3d gaussian, gaussian splatting, real-time rendering, compression, efficient, ar, segmentation  
- **[Active Semantic Mapping of Horticultural Environments Using Gaussian Splatting](https://arxiv.org/abs/2601.12122v1)**  
  Authors: Jose Cuaran, Naveen K. Upalapati, Girish Chowdhary  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12122v1.pdf)  
  Keywords: high-fidelity, semantic, 3d gaussian, gaussian splatting, lighting, 3d reconstruction, efficient, ar, segmentation, robotics, mapping  
- **[studentSplat: Your Student Model Learns Single-view 3D Gaussian Splatting](https://arxiv.org/abs/2601.11772v1)**  
  Authors: Yimu Pan, Hongda Mao, Qingshuang Chen, Yelin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.11772v1.pdf)  
  Keywords: understanding, 3d gaussian, gaussian splatting, lighting, ar  
- **[SRFlow: A Dataset and Regularization Model for High-Resolution Facial Optical Flow via Splatting Rasterization](https://arxiv.org/abs/2601.06479v1)**  
  Authors: JiaLin Zhang, Dong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.06479v1.pdf)  
  Keywords: ar, gaussian splatting, recognition, motion  
- **[FeatureSLAM: Feature-enriched 3D gaussian splatting SLAM in real time](https://arxiv.org/abs/2601.05738v1)**  
  Authors: Christopher Thirgood, Oscar Mendez, Erin Ling, Jon Storey, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05738v1.pdf)  
  Keywords: semantic, 3d gaussian, gaussian splatting, slam, efficient, tracking, ar, segmentation, mapping  
- **[GaussianSwap: Animatable Video Face Swapping with 3D Gaussian Splatting](https://arxiv.org/abs/2601.05511v1)**  
  Authors: Xuan Cheng, Jiahao Rao, Chengyang Li, Wenhao Wang, Weilin Chen, Lvqing Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05511v1.pdf)  
  Keywords: high-fidelity, avatar, 3d gaussian, gaussian splatting, dynamic, face, ar, segmentation, recognition, animation  
- **[MOSAIC-GS: Monocular Scene Reconstruction via Advanced Initialization for Complex Dynamic Environments](https://arxiv.org/abs/2601.05368v1)**  
  Authors: Svitlana Morkva, Maximum Wilder-Smith, Michael Oechsle, Alessio Tonioni, Marco Hutter, Vaishakh Patil  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.05368v1.pdf)  
  Keywords: high-fidelity, dynamic, gaussian splatting, geometry, real-time rendering, fast, efficient, tracking, ar, deformation, segmentation, compact, motion  
- **[ProFuse: Efficient Cross-View Context Fusion for Open-Vocabulary 3D Gaussian Splatting](https://arxiv.org/abs/2601.04754v2)**  
  Authors: Yen-Jen Chiou, Wei-Tse Cheng, Yuan-Fu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.04754v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chiou1203.github.io/ProFuse/.)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, head, geometry, fast, efficient, ar  
- **[G2P: Gaussian-to-Point Attribute Alignment for Boundary-Aware 3D Semantic Segmentation](https://arxiv.org/abs/2601.03510v1)**  
  Authors: Hojun Song, Chae-yeong Song, Jeong-hun Hong, Chaewon Moon, Dong-hwi Kim, Gahyeon Kim, Soo Ye Kim, Yiyi Liao, Jaehyup Lee, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03510v1.pdf)  
  Keywords: understanding, semantic, 3d gaussian, gaussian splatting, geometry, localization, ar, segmentation  



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