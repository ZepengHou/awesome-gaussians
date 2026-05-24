# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-05-24 02:13:45

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

- [3DGS Surveys](#3dgs-surveys) (14 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (221 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (346 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (379 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (83 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (391 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (48 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (430 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (240 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (139 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (220 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: ar, gaussian splatting, efficient, geometry, 3d reconstruction, 3d gaussian, survey, motion, slam, tracking  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: vr, ar, gaussian splatting, 3d gaussian, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: ar, gaussian splatting, mapping, 3d gaussian, survey, ray tracing  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, mapping, 3d gaussian, localization, face, dynamic, survey, motion, slam, tracking  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, survey, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: ar, gaussian splatting, efficient, geometry, 3d gaussian, nerf, survey  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, 3d reconstruction, 3d gaussian, 4d, dynamic, survey, compact, high-fidelity, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: ar, gaussian splatting, mapping, 3d gaussian, nerf, understanding, localization, survey, slam, semantic, robotics  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, mapping, 3d gaussian, localization, survey, high-fidelity, slam, semantic, robotics  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, nerf, 4d, survey, fast, motion  

### Acceleration

*Showing the latest 50 out of 221 papers*

- **[No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos](https://arxiv.org/abs/2605.22190v1)**  
  Authors: Matteo Balice, Yanik Kunzi, Chenyangguang Zhang, Matteo Matteucci, Marc Pollefeys, Sungwhan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22190v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, 4d, dynamic, fast, motion  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v1)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 3d gaussian, nerf, fast, sparse-view  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[Transcoding a 3D Gaussian Splatting Model from a Plenoptic Point Cloud or Mesh without the Original Multi-view Images](https://arxiv.org/abs/2605.21051v1)**  
  Authors: Maja Krivokuća, Riad Bendouro, Neus Sabater  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21051v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, face, fast  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: ar, gaussian splatting, real-time rendering, 3d gaussian, reflection, face, high-fidelity  
- **[Accelerating 3D Gaussian Splatting using Tensor Cores](https://arxiv.org/abs/2605.17855v2)**  
  Authors: Sheng Li, Yang Sui, Yue Wu, Zhuoran Song, Bo Yuan, Xulong Tang, Yue Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17855v2.pdf)  
  Keywords: neural rendering, ar, gaussian splatting, head, 3d gaussian, acceleration  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[Eff-WRFGS: Efficient Wireless Radiance Field Using 3D Gaussian Splatting](https://arxiv.org/abs/2605.15324v1)**  
  Authors: Chenghong Bian, Meng Hua, Deniz Gunduz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15324v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, head, 3d gaussian, nerf, efficient rendering  
- **[Sparse Code Uplifting for Efficient 3D Language Gaussian Splatting](https://arxiv.org/abs/2605.13600v1)**  
  Authors: Lovre Antonio Budimir, Yushi Guan, Steve Ryhner, Sven Lončarić, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13600v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, 3d gaussian, understanding, fast, compact, semantic  
- **[Z-Order Transformer for Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2605.13465v1)**  
  Authors: Can Wang, Lei Liu, Wei Jiang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13465v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, 3d gaussian, fast, semantic  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving](https://arxiv.org/abs/2605.22809v1)**  
  Authors: Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22809v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, 4d, high-fidelity  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[4D-GSW: Kinematic-Aware Spatio-Temporal Consistent Watermarking for 4D Gaussian Splatting](https://arxiv.org/abs/2605.22342v1)**  
  Authors: Sifan Zhou, Hang Zhang, Yuhang Wang, Ming Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22342v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 4d, dynamic, motion, high-fidelity  
- **[No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos](https://arxiv.org/abs/2605.22190v1)**  
  Authors: Matteo Balice, Yanik Kunzi, Chenyangguang Zhang, Matteo Matteucci, Marc Pollefeys, Sungwhan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22190v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, 4d, dynamic, fast, motion  
- **[Flow-based Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution](https://arxiv.org/abs/2605.22147v1)**  
  Authors: Jiangwei Mo, Xi Lu, Hanlin Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22147v1.pdf)  
  Keywords: ar, gaussian splatting  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v1)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 3d gaussian, nerf, fast, sparse-view  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[RCGDet3D: Rethinking 4D Radar-Camera Fusion-based 3D Object Detection with Enhanced Radar Feature Encoding](https://arxiv.org/abs/2605.21112v1)**  
  Authors: Weiyi Xiong, Bing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21112v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, efficient, 4d, semantic  
- **[Transcoding a 3D Gaussian Splatting Model from a Plenoptic Point Cloud or Mesh without the Original Multi-view Images](https://arxiv.org/abs/2605.21051v1)**  
  Authors: Maja Krivokuća, Riad Bendouro, Neus Sabater  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21051v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, face, fast  

### Avatar Generation

*Showing the latest 50 out of 346 papers*

- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[Transcoding a 3D Gaussian Splatting Model from a Plenoptic Point Cloud or Mesh without the Original Multi-view Images](https://arxiv.org/abs/2605.21051v1)**  
  Authors: Maja Krivokuća, Riad Bendouro, Neus Sabater  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21051v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, face, fast  
- **[OP2GS: Object-Aware 3D Gaussian Splatting with Dual-Opacity Primitives](https://arxiv.org/abs/2605.20044v1)**  
  Authors: Guiyu Liu, Niklas Vaara, Janne Mustaniemi, Juho Kannala, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20044v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, 3d gaussian, understanding, semantic  
- **[FlyMirage: A Fully Automated Generation Pipeline for Diverse and Scalable UAV Flight Data via Generative World Model](https://arxiv.org/abs/2605.19600v1)**  
  Authors: Jinhan Li, Xijie Huang, Zhaoqi Wang, Yijin Wang, Weiqi Ge, Qiyi He, Mo Zhu, Fei Gao, Yuze Wu, Xin Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19600v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, dynamic, high-fidelity, semantic  
- **[MMGS: 10$\times$ Compressed 3DGS through Optimal Transport Aggregation based on Multi-view Ranking](https://arxiv.org/abs/2605.19304v1)**  
  Authors: Beizhen Zhao, Sicheng Yu, Ziran Yin, Dongxu Shen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19304v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, geometry, 3d gaussian, high-fidelity, compression  
- **[3D Skew Gaussian Splatting with Any Camera Trajectory Visualization Engine](https://arxiv.org/abs/2605.18334v1)**  
  Authors: Beizhen Zhao, Yifan Zhou, Gaochao Song, Ziran Yin, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18334v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3d-skew-gs.github.io/}}.)  
  Keywords: ar, gaussian splatting, efficient, human, 3d gaussian, compact  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: ar, gaussian splatting, real-time rendering, 3d gaussian, reflection, face, high-fidelity  
- **[Accelerating 3D Gaussian Splatting using Tensor Cores](https://arxiv.org/abs/2605.17855v2)**  
  Authors: Sheng Li, Yang Sui, Yue Wu, Zhuoran Song, Bo Yuan, Xulong Tang, Yue Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17855v2.pdf)  
  Keywords: neural rendering, ar, gaussian splatting, head, 3d gaussian, acceleration  

### Dynamic Scene

*Showing the latest 50 out of 379 papers*

- **[Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving](https://arxiv.org/abs/2605.22809v1)**  
  Authors: Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22809v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, 4d, high-fidelity  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[4D-GSW: Kinematic-Aware Spatio-Temporal Consistent Watermarking for 4D Gaussian Splatting](https://arxiv.org/abs/2605.22342v1)**  
  Authors: Sifan Zhou, Hang Zhang, Yuhang Wang, Ming Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22342v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 4d, dynamic, motion, high-fidelity  
- **[No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos](https://arxiv.org/abs/2605.22190v1)**  
  Authors: Matteo Balice, Yanik Kunzi, Chenyangguang Zhang, Matteo Matteucci, Marc Pollefeys, Sungwhan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22190v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, 4d, dynamic, fast, motion  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v1)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 3d gaussian, nerf, fast, sparse-view  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[RCGDet3D: Rethinking 4D Radar-Camera Fusion-based 3D Object Detection with Enhanced Radar Feature Encoding](https://arxiv.org/abs/2605.21112v1)**  
  Authors: Weiyi Xiong, Bing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21112v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, efficient, 4d, semantic  
- **[FlyMirage: A Fully Automated Generation Pipeline for Diverse and Scalable UAV Flight Data via Generative World Model](https://arxiv.org/abs/2605.19600v1)**  
  Authors: Jinhan Li, Xijie Huang, Zhaoqi Wang, Yijin Wang, Weiqi Ge, Qiyi He, Mo Zhu, Fei Gao, Yuze Wu, Xin Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19600v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, dynamic, high-fidelity, semantic  
- **[PanoWorld: A Generative Spatial World Model for Consistent Whole-House Panorama Synthesis](https://arxiv.org/abs/2605.17916v2)**  
  Authors: Jinrang Jia, Zhenjia Li, Yijiang Hu, Yifeng Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17916v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jjrcn.github.io/PanoWorld-project-home/)  
  Keywords: vr, ar, gaussian splatting, geometry, 3d gaussian, dynamic  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  

### Few-shot

*Showing the latest 50 out of 83 papers*

- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v1)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 3d gaussian, nerf, fast, sparse-view  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, face, high-fidelity, sparse-view  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d reconstruction, 3d gaussian, sparse-view  
- **[PairDropGS: Paired Dropout-Induced Consistency Regularization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.12072v2)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Xingtao Wang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12072v2.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, sparse-view  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, face, sparse-view  
- **[ConFixGS: Learning to Fix Feedforward 3D Gaussian Splatting with Confidence-Aware Diffusion Priors in Driving Scenes](https://arxiv.org/abs/2605.09688v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Xingcheng Zhou, Zewei Zhou, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09688v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, sparse-view  
- **[FrameTwin: Curve-Anchored Gaussian Alignment from Sparse Views for Adaptive Wireframe 3D Printing](https://arxiv.org/abs/2605.09362v1)**  
  Authors: Wenting Wang, Zhuo Huang, Kun Qian, Neelotpal Dutta, Yuhu Guo, Yingjun Tian, Yeung Yam, Charlie C. L. Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09362v1.pdf)  
  Keywords: ar, geometry, deformation, sparse view, compact, sparse-view  
- **[SatSurfGS: Generalizable 2D Gaussian Splatting for Sparse-View Satellite Surface Reconstruction](https://arxiv.org/abs/2605.07181v1)**  
  Authors: Min Chen, Wei Guo, Bin Wang, Wen Li, Tong Fang, Jinbo Zhang, Junqi Zhao, Hong Kuang, Han Hu, Xuming Ge, Qing Zhu, Bo Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07181v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, face, sparse-view  
- **[Residual Gaussian Splatting for Ultra Sparse-View CBCT Reconstruction](https://arxiv.org/abs/2604.27552v1)**  
  Authors: Jian Lin, Jiancheng Fang, Shaoyu Wang, Changan Lai, Yikun Zhang, Yang Chen, Qiegen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27552v1.pdf)  
  Keywords: neural rendering, ar, gaussian splatting, efficient, 3d gaussian, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 391 papers*

- **[No Pose, No Problem in 4D: Feed-Forward Dynamic Gaussians from Unposed Multi-View Videos](https://arxiv.org/abs/2605.22190v1)**  
  Authors: Matteo Balice, Yanik Kunzi, Chenyangguang Zhang, Matteo Matteucci, Marc Pollefeys, Sungwhan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22190v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, 4d, dynamic, fast, motion  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[TideGS: Scalable Training of Over One Billion 3D Gaussian Splatting Primitives via Out-of-Core Optimization](https://arxiv.org/abs/2605.20150v1)**  
  Authors: Chonghao Zhong, Linfeng Shi, Hua Chen, Tiecheng Sun, Hao Zhao, Binhang Yuan, Chaojian Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20150v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, geometry  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, urban scene  
- **[MMGS: 10$\times$ Compressed 3DGS through Optimal Transport Aggregation based on Multi-view Ranking](https://arxiv.org/abs/2605.19304v1)**  
  Authors: Beizhen Zhao, Sicheng Yu, Ziran Yin, Dongxu Shen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19304v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, geometry, 3d gaussian, high-fidelity, compression  
- **[PanoWorld: A Generative Spatial World Model for Consistent Whole-House Panorama Synthesis](https://arxiv.org/abs/2605.17916v2)**  
  Authors: Jinrang Jia, Zhenjia Li, Yijiang Hu, Yifeng Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17916v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jjrcn.github.io/PanoWorld-project-home/)  
  Keywords: vr, ar, gaussian splatting, geometry, 3d gaussian, dynamic  
- **[ArtMesh: Part-Aware Articulated Mesh Fields with Motion-Consistent Dynamics](https://arxiv.org/abs/2605.16582v1)**  
  Authors: Sylvia Yuan, Dan Wang, Ravi Ramamoorthi, Xinrui Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16582v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, face, dynamic, motion, semantic  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, face, high-fidelity, sparse-view  
- **[Revisiting Photometric Ambiguity for Accurate Gaussian-Splatting Surface Reconstruction](https://arxiv.org/abs/2605.12494v1)**  
  Authors: Jiahe Li, Jiawei Zhang, Xiao Bai, Jin Zheng, Xiaohan Yu, Lin Gu, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12494v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fictionarry.github.io/AmbiSuR-Proj/)  
  Keywords: ar, gaussian splatting, geometry, 3d reconstruction, face  

### Large Scene

- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, urban scene  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, outdoor, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: ar, gaussian splatting, efficient, geometry, 3d gaussian, face, dynamic, high-fidelity, outdoor  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, outdoor  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: 3d gaussian, outdoor, ar, gaussian splatting  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: ar, gaussian splatting, mapping, 3d gaussian, localization, slam, outdoor  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, understanding, compact, urban scene, semantic, segmentation  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, semantic, large scene  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: neural rendering, shadow, ar, gaussian splatting, efficient, geometry, 4d, understanding, dynamic, high-fidelity, motion, large scene  

### Model Compression

*Showing the latest 50 out of 430 papers*

- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[RCGDet3D: Rethinking 4D Radar-Camera Fusion-based 3D Object Detection with Enhanced Radar Feature Encoding](https://arxiv.org/abs/2605.21112v1)**  
  Authors: Weiyi Xiong, Bing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21112v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, efficient, 4d, semantic  
- **[CAdam: Context-Adaptive Moment Estimation for 3D Gaussian Densification in Generative Distillation](https://arxiv.org/abs/2605.20872v1)**  
  Authors: SeungJeh Chung, Geonho Park, Misong Kim, HyeongYeop Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20872v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, efficient  
- **[AIR: Amortized Image Reconstruction Framework for Self-Supervised Feed-Forward 2D Gaussian Splatting](https://arxiv.org/abs/2605.20820v1)**  
  Authors: Zhaojie Zeng, Yuesong Wang, Yawei Luo, Tao Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20820v1.pdf)  
  Keywords: compact, ar, gaussian splatting, efficient  
- **[OP2GS: Object-Aware 3D Gaussian Splatting with Dual-Opacity Primitives](https://arxiv.org/abs/2605.20044v1)**  
  Authors: Guiyu Liu, Niklas Vaara, Janne Mustaniemi, Juho Kannala, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20044v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, 3d gaussian, understanding, semantic  
- **[MMGS: 10$\times$ Compressed 3DGS through Optimal Transport Aggregation based on Multi-view Ranking](https://arxiv.org/abs/2605.19304v1)**  
  Authors: Beizhen Zhao, Sicheng Yu, Ziran Yin, Dongxu Shen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19304v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, geometry, 3d gaussian, high-fidelity, compression  
- **[3D Skew Gaussian Splatting with Any Camera Trajectory Visualization Engine](https://arxiv.org/abs/2605.18334v1)**  
  Authors: Beizhen Zhao, Yifan Zhou, Gaochao Song, Ziran Yin, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18334v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3d-skew-gs.github.io/}}.)  
  Keywords: ar, gaussian splatting, efficient, human, 3d gaussian, compact  
- **[Efficient Sparse-to-Dense Visual Localization via Compact Gaussian Scene Representation and Accelerated Dense Pose Estimation](https://arxiv.org/abs/2605.17777v1)**  
  Authors: Zizhuo Li, Songchu Deng, Linfeng Tang, Jiayi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17777v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, localization, 3d gaussian, compact  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, reflection, compression  

### Quality Enhancement

*Showing the latest 50 out of 240 papers*

- **[Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving](https://arxiv.org/abs/2605.22809v1)**  
  Authors: Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22809v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, 4d, high-fidelity  
- **[4D-GSW: Kinematic-Aware Spatio-Temporal Consistent Watermarking for 4D Gaussian Splatting](https://arxiv.org/abs/2605.22342v1)**  
  Authors: Sifan Zhou, Hang Zhang, Yuhang Wang, Ming Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22342v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 4d, dynamic, motion, high-fidelity  
- **[ForeSplat: Optimization-Aware Foresight for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2605.22020v1)**  
  Authors: Yuke Li, Weihang Liu, Cheng Zhang, Yuefeng Zhang, Jiadi Cui, Zixuan Wang, Junran Ding, Haoyu Wu, Yujiao Shi, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22020v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, 3d gaussian, fast, compact, high-fidelity, lightweight  
- **[FlyMirage: A Fully Automated Generation Pipeline for Diverse and Scalable UAV Flight Data via Generative World Model](https://arxiv.org/abs/2605.19600v1)**  
  Authors: Jinhan Li, Xijie Huang, Zhaoqi Wang, Yijin Wang, Weiqi Ge, Qiyi He, Mo Zhu, Fei Gao, Yuze Wu, Xin Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19600v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, dynamic, high-fidelity, semantic  
- **[MMGS: 10$\times$ Compressed 3DGS through Optimal Transport Aggregation based on Multi-view Ranking](https://arxiv.org/abs/2605.19304v1)**  
  Authors: Beizhen Zhao, Sicheng Yu, Ziran Yin, Dongxu Shen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19304v1.pdf)  
  Keywords: ar, gaussian splatting, head, 3d reconstruction, geometry, 3d gaussian, high-fidelity, compression  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: ar, gaussian splatting, real-time rendering, 3d gaussian, reflection, face, high-fidelity  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting](https://arxiv.org/abs/2605.16065v1)**  
  Authors: Raushan Joshi, Jean-Yves Guillemaut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16065v1.pdf)  
  Keywords: high quality, ar, vr, gaussian splatting, 3d gaussian, segmentation, robotics  
- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: ar, gaussian splatting, 4d, dynamic, high-fidelity, segmentation  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, high-fidelity, lighting, semantic  

### Ray Tracing

- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, high-fidelity, ray tracing  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: ar, gaussian splatting, efficient, 3d gaussian, dynamic, ray tracing, lighting, semantic, tracking, robotics  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ar, gaussian splatting, reflection, face, ray tracing  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, mapping, 3d gaussian, localization, face, ray tracing, slam, semantic, tracking  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: shadow, ar, gaussian splatting, mapping, 3d gaussian, reflection, relightable, ray tracing  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: ar, gaussian splatting, real-time rendering, geometry, efficient, 3d gaussian, nerf, face, fast, high-fidelity, ray tracing  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: ar, gaussian splatting, mapping, 3d gaussian, survey, ray tracing  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: ar, gaussian splatting, real-time rendering, efficient, ray marching, 3d gaussian, high-fidelity  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, geometry, 3d gaussian, fast, ray casting, robotics  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ar, gaussian splatting, efficient, geometry, reflection, face, fast, lightweight, ray tracing  

### Relighting

*Showing the latest 50 out of 139 papers*

- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[A Geometric Algebra-Informed 3D Gaussian Splatting Framework for Wireless Scene Representation](https://arxiv.org/abs/2605.19065v1)**  
  Authors: Jingzhou Shen, Tianya Zhao, Xuyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19065v1.pdf)  
  Keywords: 3d gaussian, ar, reflection, gaussian splatting  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: ar, gaussian splatting, real-time rendering, 3d gaussian, reflection, face, high-fidelity  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, reflection, compression  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, high-fidelity, lighting, semantic  
- **[HarmoGS: Robust 3D Gaussian Splatting in the Wild via Conflict-Aware Gradient Harmonization](https://arxiv.org/abs/2605.13073v2)**  
  Authors: Yulei Kang, Tianze Zhu, Jian-Fang Hu, Jianhuang Lai, Wei-Shi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13073v2.pdf)  
  Keywords: ar, gaussian splatting, illumination, 3d gaussian, semantic  
- **[TransmissiveGS: Residual-Guided Disentangled Gaussian Splatting for Transmissive Scene Reconstruction and Rendering](https://arxiv.org/abs/2605.10705v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Tianchao Li, Jack C. P. Cheng, Chi-Keung Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10705v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, reflection, face, high-fidelity  
- **[Relightable Gaussian Splatting for Virtual Production Using Image-Based Illumination](https://arxiv.org/abs/2605.09024v1)**  
  Authors: Adrian Azzarelli, Nantheera Anantrasirichai, James Pollock, David R. Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09024v1.pdf)  
  Keywords: vr, ar, gaussian splatting, light transport, 3d reconstruction, relighting, illumination, geometry, efficient, reflection, relightable, lighting  
- **[3DSS: 3D Surface Splatting for Inverse Rendering](https://arxiv.org/abs/2605.05876v3)**  
  Authors: Mae Younes, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.05876v3.pdf)  
  Keywords: ar, geometry, relighting, illumination, face, lighting  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, outdoor, ar  
- **[Efficient Sparse-to-Dense Visual Localization via Compact Gaussian Scene Representation and Accelerated Dense Pose Estimation](https://arxiv.org/abs/2605.17777v1)**  
  Authors: Zizhuo Li, Songchu Deng, Linfeng Tang, Jiayi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17777v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, localization, 3d gaussian, compact  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, illumination, 3d gaussian, mapping, dynamic, sparse view, fast, high-fidelity, lighting, outdoor  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, 4d, dynamic, high-fidelity, tracking  
- **[PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization](https://arxiv.org/abs/2605.12144v1)**  
  Authors: Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12144v1.pdf)  
  Keywords: ar, gaussian splatting, localization, 3d gaussian, lightweight  
- **[MAGS-SLAM: Monocular Multi-Agent Gaussian Splatting SLAM for Geometrically and Photometrically Consistent Reconstruction](https://arxiv.org/abs/2605.10760v1)**  
  Authors: Zhihao Cao, Qi Shao, Shuhao Zhai, Jing Zhang, Anh Nguyen, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10760v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, geometry, mapping, 3d gaussian, compact, high-fidelity, lightweight, slam, tracking  
- **[PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.10307v1)**  
  Authors: Yinan Deng, Jianyu Dou, Jiahui Wang, Jingyu Zhao, Yi Yang, Yufeng Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10307v1.pdf)  
  Keywords: ar, gaussian splatting, deformation, 4d, dynamic, fast, high-fidelity, motion, tracking, segmentation, robotics  
- **[Disambiguating 2D-3D Correspondences in Gaussian Splatting-based Feature Fields for Visual Localization](https://arxiv.org/abs/2605.07351v1)**  
  Authors: Miso Lee, Sangeek Hyun, Yerim Jeon, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07351v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, mapping, localization, compact  
- **[ULF-Loc: Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting](https://arxiv.org/abs/2605.04730v1)**  
  Authors: Yingdong Gu, Shaocheng Yan, Zhenjun Zhao, Yuan Kou, Jianxin Luo, Pengcheng Shi, Jiayuan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.04730v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, geometry, localization, 3d gaussian, efficient rendering  

### Scene Understanding

*Showing the latest 50 out of 220 papers*

- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, understanding, motion, lighting, compression  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: ar, gaussian splatting, geometry, human, 3d gaussian, mapping, dynamic, motion, semantic  
- **[RCGDet3D: Rethinking 4D Radar-Camera Fusion-based 3D Object Detection with Enhanced Radar Feature Encoding](https://arxiv.org/abs/2605.21112v1)**  
  Authors: Weiyi Xiong, Bing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21112v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, efficient, 4d, semantic  
- **[OP2GS: Object-Aware 3D Gaussian Splatting with Dual-Opacity Primitives](https://arxiv.org/abs/2605.20044v1)**  
  Authors: Guiyu Liu, Niklas Vaara, Janne Mustaniemi, Juho Kannala, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.20044v1.pdf)  
  Keywords: ar, gaussian splatting, head, efficient, 3d gaussian, understanding, semantic  
- **[FlyMirage: A Fully Automated Generation Pipeline for Diverse and Scalable UAV Flight Data via Generative World Model](https://arxiv.org/abs/2605.19600v1)**  
  Authors: Jinhan Li, Xijie Huang, Zhaoqi Wang, Yijin Wang, Weiqi Ge, Qiyi He, Mo Zhu, Fei Gao, Yuze Wu, Xin Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19600v1.pdf)  
  Keywords: ar, gaussian splatting, human, 3d gaussian, dynamic, high-fidelity, semantic  
- **[ArtMesh: Part-Aware Articulated Mesh Fields with Motion-Consistent Dynamics](https://arxiv.org/abs/2605.16582v1)**  
  Authors: Sylvia Yuan, Dan Wang, Ravi Ramamoorthi, Xinrui Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16582v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian, face, dynamic, motion, semantic  
- **[Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting](https://arxiv.org/abs/2605.16065v1)**  
  Authors: Raushan Joshi, Jean-Yves Guillemaut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16065v1.pdf)  
  Keywords: high quality, ar, vr, gaussian splatting, 3d gaussian, segmentation, robotics  
- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: ar, gaussian splatting, 4d, dynamic, high-fidelity, segmentation  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, high-fidelity, lighting, semantic  
- **[Sparse Code Uplifting for Efficient 3D Language Gaussian Splatting](https://arxiv.org/abs/2605.13600v1)**  
  Authors: Lovre Antonio Budimir, Yushi Guan, Steve Ryhner, Sven Lončarić, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13600v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, 3d gaussian, understanding, fast, compact, semantic  



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