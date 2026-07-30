# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-07-30 01:25:52

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

- [3DGS Surveys](#3dgs-surveys) (10 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (230 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (993 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (326 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (377 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (76 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (412 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (422 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (247 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (31 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (139 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (159 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (227 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 3d gaussian, neural rendering, recognition, gaussian splatting, motion, compact, medical, vr, survey, ar, autonomous driving, 4d, 3d reconstruction  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, mapping, animation, survey, ar, geometry  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, efficient, slam, survey, ar, tracking, 3d reconstruction, geometry  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, vr, survey, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: 3d gaussian, gaussian splatting, mapping, survey, ar, ray tracing  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, efficient, face, mapping, slam, localization, survey, ar, tracking, dynamic  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, ar, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, survey, ar, nerf, geometry  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, efficient, survey, ar, dynamic, 4d, 3d reconstruction  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, mapping, slam, localization, survey, ar, understanding, nerf, robotics  

### Acceleration

*Showing the latest 50 out of 230 papers*

- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, lightweight, real-time rendering, dynamic, high quality  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, face, deformation, head, human, avatar, ar, tracking, acceleration, dynamic  
- **[3D Gaussian Splatting for Scientific Particle Data Compression and Rendering](https://arxiv.org/abs/2607.22956v1)**  
  Authors: Bo Jiang, Youyuan Liu, Taolue Yang, Sheng Di, Sian Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22956v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compression, compact, ar, fast, lightweight  
- **[Construction and Dynamic Update of Channel Gain Maps via 3D Gaussian Splatting](https://arxiv.org/abs/2607.21099v1)**  
  Authors: Yilong Chen, Yuan Guo, Juncong Zhou, Jie Xu, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21099v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compact, efficient, ar, fast, dynamic, geometry  
- **[QIRF Quantum-Inspired Non-Orthogonal Function-Space Compression for 3D Gaussian Splatting](https://arxiv.org/abs/2607.18067v1)**  
  Authors: Shizeng Jiang, Hao Zhang, Xuerui Ma, Ying Hu, Tao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18067v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compression, ar, real-time rendering, nerf  
- **[Locality-Aware Density Control for Efficient Gaussian-based Image Representation](https://arxiv.org/abs/2607.17896v1)**  
  Authors: Jiacong Chen, Qingyu Mao, Xiandong Meng, Shuai Liu, Chao Li, Fanyang Meng, Youneng Bao, Yongsheng Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17896v1.pdf)  
  Keywords: ar, fast, gaussian splatting, efficient  
- **[CaT-GS: Efficient 3DGS Rendering for Large Scale Scenes via Inter-frame Caching and Tile Scheduling](https://arxiv.org/abs/2607.17842v1)**  
  Authors: Tingjia Zhang, Bo Chen, Shengzhong Liu, Fan Wu, Guihai Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17842v1.pdf)  
  Keywords: 3d gaussian, neural rendering, high-fidelity, gaussian splatting, efficient, ar, real-time rendering  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, motion, mapping, ar, fast, lighting, robotics, illumination, geometry  
- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, face, ar, fast, real-time rendering, geometry  

### Applications

*Showing the latest 50 out of 993 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, ar, understanding, geometry  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, head, ar, understanding  
- **[3DGBGS: 3D Granular Ball Gaussian Splatting for Compact Novel View Synthesis](https://arxiv.org/abs/2607.26578v1)**  
  Authors: Meng Yang, Shuyin Xia, Dawei Dai, YiWang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26578v1.pdf)  
  Keywords: ar, compact, gaussian splatting, geometry  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, lightweight, real-time rendering, dynamic, high quality  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, face, ar, geometry  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, face, reflection, ar, illumination  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, avatar, ar  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, ar, lightweight, geometry  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, face, deformation, head, human, avatar, ar, tracking, acceleration, dynamic  

### Avatar Generation

*Showing the latest 50 out of 326 papers*

- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, head, ar, understanding  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, face, ar, geometry  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, face, reflection, ar, illumination  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, avatar, ar  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, face, deformation, head, human, avatar, ar, tracking, acceleration, dynamic  
- **[Real2Sim2Real for Vision-Language-Action Manipulation: An AMD ROCm-Based Pipeline](https://arxiv.org/abs/2607.22997v1)**  
  Authors: Qing Yang, Xun Wang, Ziguan Wang, Zhenjiang Li, Hongqiang Wang, Dongdong Weng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22997v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, ar  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: gaussian splatting, efficient, face, reflection, ar, relighting, lighting, ray tracing, illumination  
- **[SubSplat: High-Resolution Pixel-aligned 3DGS via Sub-pixel Gaussian Reparameterization](https://arxiv.org/abs/2607.20813v1)**  
  Authors: Jiun Lee, Jaekwang Kim, Sangmin Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20813v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, efficient, face, ar  
- **[FlexiAvatar: Unified 3D Gaussian Human Avatars Under Arbitrary Body Visibility](https://arxiv.org/abs/2607.19100v1)**  
  Authors: Yihalem Yimolal Tiruneh, Muhammad Salman Ali, Uyoung Jeong, Muneeb A. Khan, MD Khalequzzaman Chowdhury Sayem, Allanur Bayramgeldiyev, Binod Bhattarai, Seungryul Baek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.19100v1.pdf)  
  Keywords: 3d gaussian, neural rendering, gaussian splatting, body, head, vr, human, avatar, ar, tracking  
- **[ZeroSplat: Generalized Referring Segmentation in 3D Gaussian Splatting](https://arxiv.org/abs/2607.18801v1)**  
  Authors: Jiayu Ding, Meilu Song, Xiaoyi Zhang, Hongbo Jin, Yichen Jin, Xiangtian Si  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18801v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inkmind-ai.github.io/ZeroSplat)  
  Keywords: 3d gaussian, semantic, gaussian splatting, head, ar, segmentation, dynamic, understanding  

### Dynamic Scene

*Showing the latest 50 out of 377 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, ar, understanding, geometry  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, lightweight, real-time rendering, dynamic, high quality  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, avatar, ar  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, face, deformation, head, human, avatar, ar, tracking, acceleration, dynamic  
- **[Real2Sim2Real for Vision-Language-Action Manipulation: An AMD ROCm-Based Pipeline](https://arxiv.org/abs/2607.22997v1)**  
  Authors: Qing Yang, Xun Wang, Ziguan Wang, Zhenjiang Li, Hongqiang Wang, Dongdong Weng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22997v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, ar  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: 3d gaussian, sparse view, motion, gaussian splatting, localization, ar, illumination, geometry  
- **[GrainGS: Gradient-Decoupled Gaussian Splatting for Efficient Dynamic Novel View Synthesis](https://arxiv.org/abs/2607.21448v2)**  
  Authors: Jiahao He, Yihua Shao, Zhengkai Zhao, Pan Gao, Fei Ma, Jingcai Guo, Hao Tang, Nicu Sebe, Qi Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21448v2.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, efficient, deformation, ar, dynamic  
- **[Construction and Dynamic Update of Channel Gain Maps via 3D Gaussian Splatting](https://arxiv.org/abs/2607.21099v1)**  
  Authors: Yilong Chen, Yuan Guo, Juncong Zhou, Jie Xu, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21099v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compact, efficient, ar, fast, dynamic, geometry  
- **[RealVDeblur: One-Step Diffusion for Generalizable Real-World Video Deblurring](https://arxiv.org/abs/2607.20628v1)**  
  Authors: Renbiao Jin, Mingxin Yang, Yutian Chen, Junhao Zhuang, Xin Cai, Mulin Yu, Linning Xu, Wenxian Yu, Danping Zou, Shi Guo, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20628v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rbjin.github.io/RealVDeblur)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, compression, efficient, ar, 3d reconstruction  
- **[TOM-GS: Editable Video Representation via Temporal Opacity Modulation of Static 3D Gaussians](https://arxiv.org/abs/2607.22717v1)**  
  Authors: Marek Lisowski, Łukasz Smoliński, Kornel Howil, Piotr Biliński, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22717v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, deformation, ar, dynamic, geometry  

### Few-shot

*Showing the latest 50 out of 76 papers*

- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: 3d gaussian, sparse view, motion, gaussian splatting, localization, ar, illumination, geometry  
- **[Calibrated Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v1)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v1.pdf)  
  Keywords: sparse-view, fast, gaussian splatting, ar  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: 3d gaussian, neural rendering, semantic, high-fidelity, gaussian splatting, sparse-view, ar, geometry  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: 3d gaussian, sparse view, gaussian splatting, ar, geometry  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: 3d gaussian, sparse view, gaussian splatting, efficient, face, ar, large scene, geometry  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: 3d gaussian, sparse view, high-fidelity, gaussian splatting, sparse-view, face, ar, 3d reconstruction, geometry  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, motion, sparse-view, vr, ar, fast, nerf, robotics  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: 3d gaussian, neural rendering, gaussian splatting, sparse-view, efficient, ar, fast, lightweight, real-time rendering, dynamic, nerf  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: sparse-view, gaussian splatting, ar, real-time rendering, nerf, geometry  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v2)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, face, head, ar, dynamic, nerf, geometry  

### Geometry Reconstruction

*Showing the latest 50 out of 412 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, ar, understanding, geometry  
- **[3DGBGS: 3D Granular Ball Gaussian Splatting for Compact Novel View Synthesis](https://arxiv.org/abs/2607.26578v1)**  
  Authors: Meng Yang, Shuyin Xia, Dawei Dai, YiWang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26578v1.pdf)  
  Keywords: ar, compact, gaussian splatting, geometry  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, face, ar, geometry  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, ar, lightweight, geometry  
- **[Fashion-3DLR: A Controllable 3D Garment Generation Using Pairwise Fashion Elements for Intelligent Design](https://arxiv.org/abs/2607.23189v1)**  
  Authors: Shenghao Yang, Hongtao Zhang, Yuhan Yi, Zhihao Tang, Zihao Cui, Lian Wen, Han Yan, Yuan Gao, Mingbo Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23189v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, ar, geometry  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: 3d gaussian, sparse view, motion, gaussian splatting, localization, ar, illumination, geometry  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, slam, localization, ar, lightweight, tracking, geometry  
- **[Construction and Dynamic Update of Channel Gain Maps via 3D Gaussian Splatting](https://arxiv.org/abs/2607.21099v1)**  
  Authors: Yilong Chen, Yuan Guo, Juncong Zhou, Jie Xu, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21099v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compact, efficient, ar, fast, dynamic, geometry  
- **[3D-GIMP: When 3D Gaussian Inpainting Meets PatchMatch](https://arxiv.org/abs/2607.20789v1)**  
  Authors: Xuening Tian, Dieter Schmalstieg, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20789v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, ar, 3d reconstruction  

### Large Scene

- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, slam, localization, ar, lightweight, tracking, geometry  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, animation, deformation, outdoor, ar, dynamic  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: 3d gaussian, recognition, motion, gaussian splatting, efficient, slam, ar, fast, large scene, real-time rendering  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, slam, ar, tracking, geometry  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, outdoor, ar, geometry  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: 3d gaussian, sparse view, gaussian splatting, efficient, face, ar, large scene, geometry  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: 3d gaussian, deformation, outdoor, human, ar  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, ar, geometry  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, motion, gaussian splatting, efficient, mapping, head, outdoor, slam, ar, tracking, dynamic  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, face, mapping, outdoor, slam, localization, ar, autonomous driving, geometry  

### Model Compression

*Showing the latest 50 out of 422 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, ar, understanding, geometry  
- **[3DGBGS: 3D Granular Ball Gaussian Splatting for Compact Novel View Synthesis](https://arxiv.org/abs/2607.26578v1)**  
  Authors: Meng Yang, Shuyin Xia, Dawei Dai, YiWang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26578v1.pdf)  
  Keywords: ar, compact, gaussian splatting, geometry  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, lightweight, real-time rendering, dynamic, high quality  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, face, ar, geometry  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, ar, lightweight, geometry  
- **[3D Gaussian Splatting for Scientific Particle Data Compression and Rendering](https://arxiv.org/abs/2607.22956v1)**  
  Authors: Bo Jiang, Youyuan Liu, Taolue Yang, Sheng Di, Sian Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22956v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compression, compact, ar, fast, lightweight  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, ar, illumination  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: gaussian splatting, efficient, face, reflection, ar, relighting, lighting, ray tracing, illumination  
- **[GrainGS: Gradient-Decoupled Gaussian Splatting for Efficient Dynamic Novel View Synthesis](https://arxiv.org/abs/2607.21448v2)**  
  Authors: Jiahao He, Yihua Shao, Zhengkai Zhao, Pan Gao, Fei Ma, Jingcai Guo, Hao Tang, Nicu Sebe, Qi Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21448v2.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, efficient, deformation, ar, dynamic  

### Quality Enhancement

*Showing the latest 50 out of 247 papers*

- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, lightweight, real-time rendering, dynamic, high quality  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, face, reflection, ar, illumination  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, ar, lightweight, geometry  
- **[SubSplat: High-Resolution Pixel-aligned 3DGS via Sub-pixel Gaussian Reparameterization](https://arxiv.org/abs/2607.20813v1)**  
  Authors: Jiun Lee, Jaekwang Kim, Sangmin Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20813v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, efficient, face, ar  
- **[3D-GIMP: When 3D Gaussian Inpainting Meets PatchMatch](https://arxiv.org/abs/2607.20789v1)**  
  Authors: Xuening Tian, Dieter Schmalstieg, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20789v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, ar, 3d reconstruction  
- **[Exploration Matters for Escaping the Blur Trap in 3D Gaussian Splatting](https://arxiv.org/abs/2607.17965v1)**  
  Authors: Chengbo Wang, Guozheng Ma, Jinhong Wu, Tie Ji, Yizhen Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17965v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chengbo-wang.github.io/ExploreGS/)  
  Keywords: 3d gaussian, ar, high-fidelity, gaussian splatting  
- **[Packet-Loss Robust 3D Gaussian Compression via Atomic Packaging and GNN-based Error Concealment](https://arxiv.org/abs/2607.17916v1)**  
  Authors: Yuxuan Tao, Xuerui Ma, Hao Zhang, Chunhua Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17916v1.pdf)  
  Keywords: 3d gaussian, neural rendering, high-fidelity, gaussian splatting, compression, ar, lightweight, nerf  
- **[CaT-GS: Efficient 3DGS Rendering for Large Scale Scenes via Inter-frame Caching and Tile Scheduling](https://arxiv.org/abs/2607.17842v1)**  
  Authors: Tingjia Zhang, Bo Chen, Shengzhong Liu, Fan Wu, Guihai Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17842v1.pdf)  
  Keywords: 3d gaussian, neural rendering, high-fidelity, gaussian splatting, efficient, ar, real-time rendering  
- **[FillGauss: Fine-Grained Filling-Aware Impact Sound Generation for 3D Gaussian Splatting](https://arxiv.org/abs/2607.17773v1)**  
  Authors: Chen Yang, Ganye Wen, Bin Huang, Jiayi Lyu, Zehai Niu, Linlin Shen, Jinbao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17773v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, face, ar, geometry  
- **[SPARE-GS: Structural Parsimony and Resource Efficiency for 3D Gaussian Splatting](https://arxiv.org/abs/2607.16624v1)**  
  Authors: Zhang Chen, Shuai Wan, Fuzheng Yang, Jiazhi Xia, Weiyao Lin, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16624v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, compression, compact, ar, dynamic  

### Ray Tracing

- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: gaussian splatting, efficient, face, reflection, ar, relighting, lighting, ray tracing, illumination  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, motion, face, reflection, human, ar, dynamic, ray tracing, geometry  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, ray tracing  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: 3d gaussian, path tracing, gaussian splatting, efficient, reflection, ar, fast, real-time rendering, ray tracing, geometry  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, efficient, ar, global illumination, illumination, geometry  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, global illumination, illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, efficient, reflection, ar, segmentation, ray tracing, geometry  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, face, ar, fast, global illumination, shadow, illumination  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: 3d gaussian, ar, ray casting, gaussian splatting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, ar, ray tracing, geometry  

### Relighting

*Showing the latest 50 out of 139 papers*

- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, face, reflection, ar, illumination  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, efficient, ar, illumination  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: gaussian splatting, efficient, face, reflection, ar, relighting, lighting, ray tracing, illumination  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: 3d gaussian, sparse view, motion, gaussian splatting, localization, ar, illumination, geometry  
- **[ECoNGS: Efficient Compressive Neural Gaussian Splats for Volume Visualization](https://arxiv.org/abs/2607.18466v1)**  
  Authors: Kaiyuan Tang, Chaoli Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18466v1.pdf)  
  Keywords: gaussian splatting, efficient, compact, vr, ar, lightweight, dynamic, lighting  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, motion, mapping, ar, fast, lighting, robotics, illumination, geometry  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, motion, face, reflection, human, ar, dynamic, ray tracing, geometry  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, mapping, slam, ar, robotics, illumination, geometry  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: gaussian splatting, mapping, ar, dynamic, lighting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, efficient, face, ar, illumination, geometry  

### SLAM

*Showing the latest 50 out of 159 papers*

- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, face, deformation, head, human, avatar, ar, tracking, acceleration, dynamic  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: 3d gaussian, sparse view, motion, gaussian splatting, localization, ar, illumination, geometry  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, slam, localization, ar, lightweight, tracking, geometry  
- **[FlexiAvatar: Unified 3D Gaussian Human Avatars Under Arbitrary Body Visibility](https://arxiv.org/abs/2607.19100v1)**  
  Authors: Yihalem Yimolal Tiruneh, Muhammad Salman Ali, Uyoung Jeong, Muneeb A. Khan, MD Khalequzzaman Chowdhury Sayem, Allanur Bayramgeldiyev, Binod Bhattarai, Seungryul Baek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.19100v1.pdf)  
  Keywords: 3d gaussian, neural rendering, gaussian splatting, body, head, vr, human, avatar, ar, tracking  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, 3d reconstruction, motion, mapping, ar, fast, lighting, robotics, illumination, geometry  
- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, ar, tracking, dynamic  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: 3d gaussian, recognition, motion, gaussian splatting, efficient, slam, ar, fast, large scene, real-time rendering  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compact, efficient, mapping, ar, fast, geometry  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: 3d gaussian, gaussian splatting, mapping, outdoor, slam, ar, tracking, geometry  

### Scene Understanding

*Showing the latest 50 out of 227 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: 3d gaussian, motion, gaussian splatting, compact, ar, understanding, geometry  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, head, ar, understanding  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, compression, compact, mapping, ar, fast, lightweight, real-time rendering, geometry  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, avatar, ar  
- **[Fashion-3DLR: A Controllable 3D Garment Generation Using Pairwise Fashion Elements for Intelligent Design](https://arxiv.org/abs/2607.23189v1)**  
  Authors: Shenghao Yang, Hongtao Zhang, Yuhan Yi, Zhihao Tang, Zihao Cui, Lian Wen, Han Yan, Yuan Gao, Mingbo Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23189v1.pdf)  
  Keywords: 3d gaussian, semantic, gaussian splatting, ar, geometry  
- **[Real2Sim2Real for Vision-Language-Action Manipulation: An AMD ROCm-Based Pipeline](https://arxiv.org/abs/2607.22997v1)**  
  Authors: Qing Yang, Xun Wang, Ziguan Wang, Zhenjiang Li, Hongqiang Wang, Dongdong Weng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22997v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, body, human, ar  
- **[RealVDeblur: One-Step Diffusion for Generalizable Real-World Video Deblurring](https://arxiv.org/abs/2607.20628v1)**  
  Authors: Renbiao Jin, Mingxin Yang, Yutian Chen, Junhao Zhuang, Xin Cai, Mulin Yu, Linning Xu, Wenxian Yu, Danping Zou, Shi Guo, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20628v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rbjin.github.io/RealVDeblur)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, compression, efficient, ar, 3d reconstruction  
- **[ZeroSplat: Generalized Referring Segmentation in 3D Gaussian Splatting](https://arxiv.org/abs/2607.18801v1)**  
  Authors: Jiayu Ding, Meilu Song, Xiaoyi Zhang, Hongbo Jin, Yichen Jin, Xiangtian Si  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18801v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inkmind-ai.github.io/ZeroSplat)  
  Keywords: 3d gaussian, semantic, gaussian splatting, head, ar, segmentation, dynamic, understanding  
- **[TopoGS: Planar Reconstruction via Topology-aware 3D Gaussian Splatting](https://arxiv.org/abs/2607.16838v1)**  
  Authors: Shanshan Pan, Jiale Chen, Yilin Liu, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16838v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compact, ar, segmentation, 3d reconstruction, geometry  
- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: 3d gaussian, semantic, motion, gaussian splatting, ar, tracking, dynamic  



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