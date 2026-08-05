# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-08-05 01:42:03

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
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (321 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (378 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (416 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (425 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (246 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (31 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (139 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (156 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (228 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: compact, medical, vr, neural rendering, 3d gaussian, motion, ar, 3d reconstruction, recognition, 4d, gaussian splatting, survey, autonomous driving  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: mapping, ar, geometry, animation, gaussian splatting, survey  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: slam, 3d gaussian, motion, ar, geometry, 3d reconstruction, efficient, tracking, gaussian splatting, survey  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: vr, 3d gaussian, ar, gaussian splatting, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: mapping, 3d gaussian, ar, gaussian splatting, ray tracing, survey  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, face, slam, mapping, 3d gaussian, ar, efficient, dynamic, localization, tracking, gaussian splatting, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: 3d gaussian, robotics, ar, gaussian splatting, survey  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: 3d gaussian, nerf, ar, geometry, efficient, gaussian splatting, survey  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: compression, compact, 3d gaussian, high-fidelity, ar, 3d reconstruction, efficient, dynamic, 4d, gaussian splatting, survey  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: semantic, mapping, slam, 3d gaussian, robotics, nerf, ar, understanding, localization, gaussian splatting, survey  

### Acceleration

*Showing the latest 50 out of 230 papers*

- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, efficient, dynamic, 4d, real-time rendering, gaussian splatting, fast  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, efficient, dynamic, 4d, real-time rendering, gaussian splatting, sparse-view  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: mapping, efficient rendering, slam, 3d gaussian, robotics, ar, 3d reconstruction, efficient, localization, tracking, gaussian splatting  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: tracking, human, 3d gaussian, ar, avatar, head, gaussian splatting, fast  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: compression, compact, semantic, mapping, 3d gaussian, ar, lightweight, geometry, real-time rendering, gaussian splatting, fast  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, ar, lightweight, high quality, dynamic, real-time rendering, gaussian splatting  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: face, tracking, acceleration, 3d gaussian, human, deformation, ar, avatar, dynamic, head, gaussian splatting, motion  
- **[3D Gaussian Splatting for Scientific Particle Data Compression and Rendering](https://arxiv.org/abs/2607.22956v1)**  
  Authors: Bo Jiang, Youyuan Liu, Taolue Yang, Sheng Di, Sian Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22956v1.pdf)  
  Keywords: compression, compact, 3d gaussian, ar, lightweight, gaussian splatting, fast  
- **[Construction and Dynamic Update of Channel Gain Maps via 3D Gaussian Splatting](https://arxiv.org/abs/2607.21099v1)**  
  Authors: Yilong Chen, Yuan Guo, Juncong Zhou, Jie Xu, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21099v1.pdf)  
  Keywords: compact, 3d gaussian, ar, geometry, efficient, dynamic, gaussian splatting, fast  

### Applications

*Showing the latest 50 out of 994 papers*

- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, face, 3d gaussian, ar, geometry, gaussian splatting  
- **[Standalone DINOv3 for Training-Free Open-Vocabulary Semantic Segmentation in Remote Sensing](https://arxiv.org/abs/2608.03023v1)**  
  Authors: Changhao Zhao, Haoxiang Li, Yuke Li, Hai Liu, LingLin Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03023v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, segmentation  
- **[InfiniSplat: Implicit Gaussian Decoding for Large-Baseline Monocular View Synthesis](https://arxiv.org/abs/2608.02437v2)**  
  Authors: Jiawei Wang, Hao Yu, Yongzhen Hu, Xinyi Yang, Tao Ni, Xin Zhan, Junbo Chen, Xiaowei Zhou, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02437v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/InfiniSplat.)  
  Keywords: face, 3d gaussian, ar, geometry, gaussian splatting  
- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v1)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v1.pdf)  
  Keywords: efficient, ar, mapping  
- **[CLEAR: Conflict-aware Learning via Evidence-guided Adaptive Routing for Unified Sparse-View 3D Gaussian Super-Resolution](https://arxiv.org/abs/2608.02206v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02206v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, sparse-view  
- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: 3d gaussian, illumination, nerf, ar, geometry, gaussian splatting, autonomous driving  
- **[GSRAIN: Physically Calibrated High-/Low-Frequency Rainfall Synthesis for 3D Gaussian Driving Scenes](https://arxiv.org/abs/2608.02177v1)**  
  Authors: Fanyu Wang, Longgao Zhang, Junyi Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02177v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, gaussian splatting, autonomous driving  
- **[UniqueSplat: View-conditioned 3D Gaussian Splatting for Generalizable 3D Reconstruction](https://arxiv.org/abs/2608.02145v1)**  
  Authors: Haixu Song, Xiaoke Yang, Shengjun Zhang, Jiwen Lu, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02145v1.pdf)  
  Keywords: 3d gaussian, ar, 3d reconstruction, dynamic, gaussian splatting  
- **[DeGS: A Scalable 3DGS Architecture via Decoupled Workload Parsing and Reorganization](https://arxiv.org/abs/2608.02099v1)**  
  Authors: Minnan Pei, Gang Li, Zeyu Zhu, Siting Wang, Junwen Si, Zhuoran Song, Yu Feng, Fangxin Liu, Xiaoyao Liang, Jian Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02099v1.pdf)  
  Keywords: compact, 3d gaussian, ar, efficient, gaussian splatting  
- **[ASTRA: Asynchronous Spatio-Temporal Reconstruction via Trajectory Alignment](https://arxiv.org/abs/2608.02006v1)**  
  Authors: Junyu Zhu, Hao Zhu, Xinzhuo Zhang, Hongdong Li, Zhan Ma, Xun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02006v1.pdf)  
  Keywords: deformation, ar, geometry, dynamic, gaussian splatting, motion  

### Avatar Generation

*Showing the latest 50 out of 321 papers*

- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, face, 3d gaussian, ar, geometry, gaussian splatting  
- **[InfiniSplat: Implicit Gaussian Decoding for Large-Baseline Monocular View Synthesis](https://arxiv.org/abs/2608.02437v2)**  
  Authors: Jiawei Wang, Hao Yu, Yongzhen Hu, Xinyi Yang, Tao Ni, Xin Zhan, Junbo Chen, Xiaowei Zhou, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02437v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/InfiniSplat.)  
  Keywords: face, 3d gaussian, ar, geometry, gaussian splatting  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: ar, geometry, 3d reconstruction, localization, head, gaussian splatting, motion  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: face, 3d gaussian, ar, geometry, gaussian splatting, sparse-view  
- **[OASIS: Occlusion-aware Single-image Hand Avatar Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2607.29633v1)**  
  Authors: Zhisheng Han, Shiyao Wu, Jiayan Qiu, Yakun Ju, Lu Liu, Le Zhang, Pengfei Feng, Huiyu Zhou, Zheheng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29633v1.pdf)  
  Keywords: face, 3d gaussian, deformation, nerf, geometry, ar, avatar, gaussian splatting  
- **[S-Avatar: Diffusion-Guided Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2607.28164v1)**  
  Authors: Hail Song, Seokhwan Yang, Jiwon Yang, Woojin Cho, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28164v1.pdf)  
  Keywords: 3d gaussian, ar, efficient, avatar, dynamic, head, gaussian splatting, vr  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: tracking, human, 3d gaussian, ar, avatar, head, gaussian splatting, fast  
- **[4DHumanDiff: Direct Text-to-4DGS Generation for Consistent 360-Degree Dynamic Humans](https://arxiv.org/abs/2607.27634v1)**  
  Authors: Renlong Wu, Haoran Chen, Yuxiang Wei, Xiaowei Jin, Wangmeng Zuo, Hui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.27634v1.pdf)  
  Keywords: human, ar, geometry, dynamic, 4d, gaussian splatting, motion  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: 3d gaussian, ar, understanding, head, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 378 papers*

- **[UniqueSplat: View-conditioned 3D Gaussian Splatting for Generalizable 3D Reconstruction](https://arxiv.org/abs/2608.02145v1)**  
  Authors: Haixu Song, Xiaoke Yang, Shengjun Zhang, Jiwen Lu, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02145v1.pdf)  
  Keywords: 3d gaussian, ar, 3d reconstruction, dynamic, gaussian splatting  
- **[ASTRA: Asynchronous Spatio-Temporal Reconstruction via Trajectory Alignment](https://arxiv.org/abs/2608.02006v1)**  
  Authors: Junyu Zhu, Hao Zhu, Xinzhuo Zhang, Hongdong Li, Zhan Ma, Xun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02006v1.pdf)  
  Keywords: deformation, ar, geometry, dynamic, gaussian splatting, motion  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, 3d gaussian, high-fidelity, ar, understanding, gaussian splatting, motion  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, efficient, dynamic, 4d, real-time rendering, gaussian splatting, fast  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, relighting, neural rendering, 3d gaussian, illumination, high-fidelity, ar, lighting, dynamic, gaussian splatting, autonomous driving  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, efficient, dynamic, 4d, real-time rendering, gaussian splatting, sparse-view  
- **[DynActiveGS: Active Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2608.01178v1)**  
  Authors: Hongbo Duan, Pengting Luo, Chengzhi Zhao, Yuanhao Chiang, Fangming Liu, Xueqian Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01178v1.pdf)  
  Keywords: 3d gaussian, ar, dynamic, gaussian splatting, motion  
- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: ar, geometry, 3d reconstruction, localization, head, gaussian splatting, motion  
- **[Scene2Sound: Auditory-Grounded Soundscape Generation for 3D Gaussian Worlds](https://arxiv.org/abs/2608.00463v1)**  
  Authors: Masaki Yoshida, Ren Togo, Takahiro Ogawa, Miki Haseyama  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00463v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://masaki-lmd.github.io/scene2sound/.)  
  Keywords: 3d gaussian, gaussian splatting, ar, motion  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[CLEAR: Conflict-aware Learning via Evidence-guided Adaptive Routing for Unified Sparse-View 3D Gaussian Super-Resolution](https://arxiv.org/abs/2608.02206v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02206v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, sparse-view  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, efficient, dynamic, 4d, real-time rendering, gaussian splatting, sparse-view  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: face, 3d gaussian, ar, geometry, gaussian splatting, sparse-view  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: sparse view, 3d gaussian, illumination, ar, geometry, localization, gaussian splatting, motion  
- **[Posterior Variance Is a Constraint Map, Not an Error Map: Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v2)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v2.pdf)  
  Keywords: gaussian splatting, ar, fast, sparse-view  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, neural rendering, 3d gaussian, high-fidelity, ar, geometry, gaussian splatting, sparse-view  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: sparse view, 3d gaussian, ar, geometry, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: sparse view, face, 3d gaussian, large scene, ar, geometry, efficient, gaussian splatting  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: sparse view, face, 3d gaussian, high-fidelity, ar, geometry, 3d reconstruction, gaussian splatting, sparse-view  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: vr, 3d gaussian, robotics, fast, nerf, ar, gaussian splatting, motion, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 416 papers*

- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, face, 3d gaussian, ar, geometry, gaussian splatting  
- **[InfiniSplat: Implicit Gaussian Decoding for Large-Baseline Monocular View Synthesis](https://arxiv.org/abs/2608.02437v2)**  
  Authors: Jiawei Wang, Hao Yu, Yongzhen Hu, Xinyi Yang, Tao Ni, Xin Zhan, Junbo Chen, Xiaowei Zhou, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02437v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zju3dv.github.io/InfiniSplat.)  
  Keywords: face, 3d gaussian, ar, geometry, gaussian splatting  
- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: 3d gaussian, illumination, nerf, ar, geometry, gaussian splatting, autonomous driving  
- **[GSRAIN: Physically Calibrated High-/Low-Frequency Rainfall Synthesis for 3D Gaussian Driving Scenes](https://arxiv.org/abs/2608.02177v1)**  
  Authors: Fanyu Wang, Longgao Zhang, Junyi Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02177v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, gaussian splatting, autonomous driving  
- **[UniqueSplat: View-conditioned 3D Gaussian Splatting for Generalizable 3D Reconstruction](https://arxiv.org/abs/2608.02145v1)**  
  Authors: Haixu Song, Xiaoke Yang, Shengjun Zhang, Jiwen Lu, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02145v1.pdf)  
  Keywords: 3d gaussian, ar, 3d reconstruction, dynamic, gaussian splatting  
- **[ASTRA: Asynchronous Spatio-Temporal Reconstruction via Trajectory Alignment](https://arxiv.org/abs/2608.02006v1)**  
  Authors: Junyu Zhu, Hao Zhu, Xinzhuo Zhang, Hongdong Li, Zhan Ma, Xun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02006v1.pdf)  
  Keywords: deformation, ar, geometry, dynamic, gaussian splatting, motion  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, efficient, dynamic, 4d, real-time rendering, gaussian splatting, fast  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[StreamSplat: Streaming Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2608.01659v1)**  
  Authors: Changhao Song, Yuxuan Wang, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01659v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, efficient, gaussian splatting  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, efficient, dynamic, 4d, real-time rendering, gaussian splatting, sparse-view  

### Large Scene

- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: mapping, slam, 3d gaussian, ar, lightweight, geometry, localization, tracking, gaussian splatting, outdoor  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: 3d gaussian, deformation, ar, dynamic, animation, gaussian splatting, motion, outdoor  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, 3d gaussian, large scene, fast, ar, efficient, recognition, real-time rendering, gaussian splatting, motion  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: mapping, slam, 3d gaussian, ar, geometry, tracking, gaussian splatting, outdoor  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, gaussian splatting, outdoor  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: sparse view, face, 3d gaussian, large scene, ar, geometry, efficient, gaussian splatting  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, 3d gaussian, ar, deformation, outdoor  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: mapping, 3d gaussian, ar, geometry, gaussian splatting, outdoor  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: mapping, tracking, slam, 3d gaussian, high-fidelity, ar, efficient, dynamic, head, gaussian splatting, motion, outdoor  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: face, mapping, slam, 3d gaussian, ar, geometry, efficient, autonomous driving, localization, gaussian splatting, outdoor  

### Model Compression

*Showing the latest 50 out of 425 papers*

- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, face, 3d gaussian, ar, geometry, gaussian splatting  
- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v1)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v1.pdf)  
  Keywords: efficient, ar, mapping  
- **[DeGS: A Scalable 3DGS Architecture via Decoupled Workload Parsing and Reorganization](https://arxiv.org/abs/2608.02099v1)**  
  Authors: Minnan Pei, Gang Li, Zeyu Zhu, Siting Wang, Junwen Si, Zhuoran Song, Yu Feng, Fangxin Liu, Xiaoyao Liang, Jian Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02099v1.pdf)  
  Keywords: compact, 3d gaussian, ar, efficient, gaussian splatting  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v1)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v1.pdf)  
  Keywords: motion, ar, 3d reconstruction, efficient, dynamic, 4d, real-time rendering, gaussian splatting, fast  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, relighting, neural rendering, 3d gaussian, illumination, high-fidelity, ar, lighting, dynamic, gaussian splatting, autonomous driving  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[StreamSplat: Streaming Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2608.01659v1)**  
  Authors: Changhao Song, Yuxuan Wang, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01659v1.pdf)  
  Keywords: 3d gaussian, ar, geometry, efficient, gaussian splatting  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, efficient, dynamic, 4d, real-time rendering, gaussian splatting, sparse-view  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: 3d gaussian, high-fidelity, ar, geometry, 3d reconstruction, efficient, understanding, gaussian splatting  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: mapping, efficient rendering, slam, 3d gaussian, robotics, ar, 3d reconstruction, efficient, localization, tracking, gaussian splatting  

### Quality Enhancement

*Showing the latest 50 out of 246 papers*

- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, 3d gaussian, high-fidelity, ar, understanding, gaussian splatting, motion  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, relighting, neural rendering, 3d gaussian, illumination, high-fidelity, ar, lighting, dynamic, gaussian splatting, autonomous driving  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: face, efficient rendering, 3d gaussian, high-fidelity, ar, geometry, efficient, animation, gaussian splatting, motion  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: 3d gaussian, high-fidelity, ar, geometry, 3d reconstruction, efficient, understanding, gaussian splatting  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: 3d gaussian, ar, lightweight, high quality, dynamic, real-time rendering, gaussian splatting  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: reflection, face, illumination, ar, high-fidelity  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: compression, compact, 3d gaussian, high-fidelity, lightweight, geometry, ar, gaussian splatting  
- **[SubSplat: High-Resolution Pixel-aligned 3DGS via Sub-pixel Gaussian Reparameterization](https://arxiv.org/abs/2607.20813v1)**  
  Authors: Jiun Lee, Jaekwang Kim, Sangmin Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20813v1.pdf)  
  Keywords: face, high-fidelity, ar, efficient, gaussian splatting  
- **[3D-GIMP: When 3D Gaussian Inpainting Meets PatchMatch](https://arxiv.org/abs/2607.20789v1)**  
  Authors: Xuening Tian, Dieter Schmalstieg, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20789v1.pdf)  
  Keywords: 3d gaussian, ar, high-fidelity, 3d reconstruction, gaussian splatting  
- **[Exploration Matters for Escaping the Blur Trap in 3D Gaussian Splatting](https://arxiv.org/abs/2607.17965v1)**  
  Authors: Chengbo Wang, Guozheng Ma, Jinhong Wu, Tie Ji, Yizhen Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17965v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chengbo-wang.github.io/ExploreGS/)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity  

### Ray Tracing

- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: reflection, face, relighting, illumination, ar, efficient, lighting, gaussian splatting, ray tracing  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: reflection, face, 3d gaussian, human, high-fidelity, ar, geometry, dynamic, gaussian splatting, ray tracing, motion  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, ar, gaussian splatting, ray tracing, fast  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: reflection, 3d gaussian, ar, geometry, efficient, path tracing, real-time rendering, gaussian splatting, ray tracing, fast  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d gaussian, illumination, ar, geometry, 3d reconstruction, global illumination, efficient, gaussian splatting  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: illumination, high-fidelity, ar, global illumination, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: semantic, reflection, 3d gaussian, ar, geometry, efficient, segmentation, gaussian splatting, ray tracing  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: face, 3d gaussian, illumination, ar, shadow, global illumination, gaussian splatting, fast  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, ray casting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, geometry, gaussian splatting, ray tracing  

### Relighting

*Showing the latest 50 out of 139 papers*

- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: 3d gaussian, illumination, nerf, ar, geometry, gaussian splatting, autonomous driving  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, relighting, neural rendering, 3d gaussian, illumination, high-fidelity, ar, lighting, dynamic, gaussian splatting, autonomous driving  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: reflection, face, illumination, ar, high-fidelity  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: 3d gaussian, illumination, ar, efficient, gaussian splatting  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: reflection, face, relighting, illumination, ar, efficient, lighting, gaussian splatting, ray tracing  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: sparse view, 3d gaussian, illumination, ar, geometry, localization, gaussian splatting, motion  
- **[ECoNGS: Efficient Compressive Neural Gaussian Splats for Volume Visualization](https://arxiv.org/abs/2607.18466v1)**  
  Authors: Kaiyuan Tang, Chaoli Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18466v1.pdf)  
  Keywords: compact, ar, lightweight, efficient, lighting, dynamic, gaussian splatting, vr  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: mapping, 3d gaussian, illumination, robotics, motion, ar, geometry, 3d reconstruction, lighting, gaussian splatting, fast  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: reflection, face, 3d gaussian, human, high-fidelity, ar, geometry, dynamic, gaussian splatting, ray tracing, motion  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: mapping, slam, illumination, robotics, ar, geometry, 3d reconstruction, gaussian splatting  

### SLAM

*Showing the latest 50 out of 156 papers*

- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v1)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v1.pdf)  
  Keywords: efficient, ar, mapping  
- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: ar, geometry, 3d reconstruction, localization, head, gaussian splatting, motion  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: mapping, efficient rendering, slam, 3d gaussian, robotics, ar, 3d reconstruction, efficient, localization, tracking, gaussian splatting  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: tracking, human, 3d gaussian, ar, avatar, head, gaussian splatting, fast  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: compression, compact, semantic, mapping, 3d gaussian, ar, lightweight, geometry, real-time rendering, gaussian splatting, fast  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: face, tracking, acceleration, 3d gaussian, human, deformation, ar, avatar, dynamic, head, gaussian splatting, motion  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: sparse view, 3d gaussian, illumination, ar, geometry, localization, gaussian splatting, motion  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: mapping, slam, 3d gaussian, ar, lightweight, geometry, localization, tracking, gaussian splatting, outdoor  
- **[FlexiAvatar: Unified 3D Gaussian Human Avatars Under Arbitrary Body Visibility](https://arxiv.org/abs/2607.19100v1)**  
  Authors: Yihalem Yimolal Tiruneh, Muhammad Salman Ali, Uyoung Jeong, Muneeb A. Khan, MD Khalequzzaman Chowdhury Sayem, Allanur Bayramgeldiyev, Binod Bhattarai, Seungryul Baek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.19100v1.pdf)  
  Keywords: tracking, neural rendering, human, 3d gaussian, ar, body, avatar, head, gaussian splatting, vr  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: mapping, 3d gaussian, illumination, robotics, motion, ar, geometry, 3d reconstruction, lighting, gaussian splatting, fast  

### Scene Understanding

*Showing the latest 50 out of 228 papers*

- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: compression, semantic, face, 3d gaussian, ar, geometry, gaussian splatting  
- **[Standalone DINOv3 for Training-Free Open-Vocabulary Semantic Segmentation in Remote Sensing](https://arxiv.org/abs/2608.03023v1)**  
  Authors: Changhao Zhao, Haoxiang Li, Yuke Li, Hai Liu, LingLin Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03023v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, segmentation  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: vr, 3d gaussian, high-fidelity, ar, understanding, gaussian splatting, motion  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: compression, semantic, relighting, neural rendering, 3d gaussian, illumination, high-fidelity, ar, lighting, dynamic, gaussian splatting, autonomous driving  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: 3d gaussian, high-fidelity, ar, geometry, 3d reconstruction, efficient, understanding, gaussian splatting  
- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: compact, 3d gaussian, ar, geometry, understanding, gaussian splatting, motion  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: 3d gaussian, ar, understanding, head, gaussian splatting  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: compression, compact, semantic, mapping, 3d gaussian, ar, lightweight, geometry, real-time rendering, gaussian splatting, fast  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: semantic, human, 3d gaussian, ar, body, avatar, gaussian splatting, motion  
- **[Fashion-3DLR: A Controllable 3D Garment Generation Using Pairwise Fashion Elements for Intelligent Design](https://arxiv.org/abs/2607.23189v1)**  
  Authors: Shenghao Yang, Hongtao Zhang, Yuhan Yi, Zhihao Tang, Zihao Cui, Lian Wen, Han Yan, Yuan Gao, Mingbo Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23189v1.pdf)  
  Keywords: semantic, 3d gaussian, ar, geometry, gaussian splatting  



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