# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-09-30 03:00:20

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

- [3DGS Surveys](#3dgs-surveys) (9 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (200 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (312 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (365 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (84 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (417 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (48 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (405 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (204 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (22 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (117 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (163 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (210 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: survey, gaussian splatting, 3d gaussian, high-fidelity, ar, face  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: survey, gaussian splatting, ar, 3d gaussian, compression  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, survey, illumination, gaussian splatting, motion, geometry, ar  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: 3d reconstruction, survey, gaussian splatting, dynamic, geometry, ar, nerf, 3d gaussian  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: autonomous driving, 4d, 3d reconstruction, survey, gaussian splatting, motion, compact, recognition, medical, ar, neural rendering, 3d gaussian, vr  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: mapping, survey, animation, gaussian splatting, geometry, ar  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d reconstruction, survey, gaussian splatting, slam, motion, ar, tracking, geometry, efficient, 3d gaussian  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, gaussian splatting, ar, 3d gaussian, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v8)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v8.pdf)  
  Keywords: mapping, survey, gaussian splatting, ar, ray tracing, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 200 papers*

- **[RLX: A Unified Multi-Backend Tensor Compiler and Distributed Runtime in Rust](https://arxiv.org/abs/2609.37916v1)**  
  Authors: Eugene Hauptmann, Nataliya Kosmyna  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37916v1.pdf)  
  Keywords: gaussian splatting, fast, ar, 3d gaussian  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: illumination, gaussian splatting, dynamic, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, fast, 3d gaussian  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: 3d reconstruction, gaussian splatting, dynamic, motion, ar, real-time rendering  
- **[Rate-Distortion Adaptive Primitive Selection for Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2609.34367v1)**  
  Authors: Yulong Cheng, Youneng Bao, Junfeng Zhou, Mu Li, Jie Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34367v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, fast, vr  
- **[AGILE-GS: Anchor-Guided Fast Next-Best-View Selection for Active 3D Gaussian Splatting](https://arxiv.org/abs/2609.34176v1)**  
  Authors: Amirhossein Mollaei Khass, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34176v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, fast, 3d gaussian  
- **[Towards Practical Compression of 3D Gaussian Splatting](https://arxiv.org/abs/2609.30245v1)**  
  Authors: Pengpeng Yu, Yueru Chen, Fei Song, Tai Qin, Qi Zhang, Jing Wang, Yulan Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.30245v1.pdf)  
  Keywords: gaussian splatting, ar, compact, geometry, fast, 3d gaussian, compression  
- **[OceanXL: Large-scale Underwater 3D Gaussian Splatting via Block Partitioning and Adaptive Pruning](https://arxiv.org/abs/2609.29985v1)**  
  Authors: Haoran Wang, Shaoyu Cai, Adrian Azzarelli, Zhuodong Jiang, Guoxi Huang, Eng Tat Khoo, Brett Seymour, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29985v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, ar, compact, efficient, fast, real-time rendering, nerf, large scene, 3d gaussian  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: gaussian splatting, slam, semantic, ar, 3d gaussian, fast, face  
- **[Ultra-fast Neural Inference for Stochastic Gaussian Splatting Denoising](https://arxiv.org/abs/2609.25604v1)**  
  Authors: Chenxiao Hu, Hao Zhang, Yanchen Zhang, Meng Gai, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25604v1.pdf)  
  Keywords: gaussian splatting, fast, head, ar  

### Applications

*Showing the latest 50 out of 996 papers*

- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, gaussian splatting, understanding, compact, geometry, body, ar, 3d gaussian  
- **[RLX: A Unified Multi-Backend Tensor Compiler and Distributed Runtime in Rust](https://arxiv.org/abs/2609.37916v1)**  
  Authors: Eugene Hauptmann, Nataliya Kosmyna  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37916v1.pdf)  
  Keywords: gaussian splatting, fast, ar, 3d gaussian  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: illumination, gaussian splatting, dynamic, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, fast, 3d gaussian  
- **[NRF-GS: Neural Residual Fields for Expressive and Compact Gaussian Splatting](https://arxiv.org/abs/2609.37115v1)**  
  Authors: Pratik Singh Bisht, Andreas Kolb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37115v1.pdf)  
  Keywords: gaussian splatting, lightweight, compact, ar, 3d gaussian  
- **[Prior-Driven Enhancements in 3D Gaussian Splatting: Normals and Depths Regularization](https://arxiv.org/abs/2609.36969v1)**  
  Authors: Gyeonggwan Lee, Seunghwan Hong, Junghun Suh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36969v1.pdf)  
  Keywords: gaussian splatting, motion, 3d gaussian, ar, face  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, localization, geometry, deformation, ar, 3d gaussian  
- **[AESplat: Advancing Pose-Free Feed-Forward 3D Gaussian Splatting via Decoupled Appearance Modeling](https://arxiv.org/abs/2609.36693v1)**  
  Authors: Shiwei Ren, Zhiang Liu, Yongchun Fang, Hongwei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36693v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aesplat.github.io/.)  
  Keywords: gaussian splatting, efficient, ar, 3d gaussian  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: 3d reconstruction, gaussian splatting, dynamic, motion, ar, real-time rendering  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: gaussian splatting, lighting, motion, ar, 3d gaussian, vr  

### Avatar Generation

*Showing the latest 50 out of 312 papers*

- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, gaussian splatting, understanding, compact, geometry, body, ar, 3d gaussian  
- **[Prior-Driven Enhancements in 3D Gaussian Splatting: Normals and Depths Regularization](https://arxiv.org/abs/2609.36969v1)**  
  Authors: Gyeonggwan Lee, Seunghwan Hong, Junghun Suh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36969v1.pdf)  
  Keywords: gaussian splatting, motion, 3d gaussian, ar, face  
- **[Remote Sensing Sparse-View 3D Gaussian Splatting via Depth Image-Based Rendering](https://arxiv.org/abs/2609.35612v1)**  
  Authors: Jiaming Kang, Zhengxia Zou, Zhenwei Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35612v1.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d gaussian, ar, nerf, face  
- **[Endo-TSR: Temporal Spectral Modeling of Appearance and Motion for Endoscopic Reconstruction](https://arxiv.org/abs/2609.32399v1)**  
  Authors: Taoyu Wu, Yiyi Miao, Qi Shao, Zhuoxiao Li, Zhe Tang, Limin Yu, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32399v1.pdf)  
  Keywords: gaussian splatting, motion, ar, efficient, nerf, face  
- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, face, large scene, 3d gaussian  
- **[Gauss What You Need: Compact Gaussian Splatting Across Scene Scales](https://arxiv.org/abs/2609.31248v1)**  
  Authors: Afif Boudaoud, Jiayi Liu, Alexandru Calotoiu, Torsten Hoefler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31248v1.pdf)  
  Keywords: gaussian splatting, compact, 3d gaussian, ar, face  
- **[3dgs-sc: a controlled static screen-content benchmark for 3d gaussian splatting](https://arxiv.org/abs/2609.31756v1)**  
  Authors: Shicheng Cai, Hao Zhang, Dong Dai, Xuerui Ma, Ying Hu, Tao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31756v1.pdf)  
  Keywords: gaussian splatting, ar, face, 3d gaussian  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: gaussian splatting, slam, semantic, ar, 3d gaussian, fast, face  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: gaussian splatting, slam, tracking, 3d gaussian, geometry, outdoor, ar, face  
- **[Ultra-fast Neural Inference for Stochastic Gaussian Splatting Denoising](https://arxiv.org/abs/2609.25604v1)**  
  Authors: Chenxiao Hu, Hao Zhang, Yanchen Zhang, Meng Gai, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25604v1.pdf)  
  Keywords: gaussian splatting, fast, head, ar  

### Dynamic Scene

*Showing the latest 50 out of 365 papers*

- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: illumination, gaussian splatting, dynamic, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[Prior-Driven Enhancements in 3D Gaussian Splatting: Normals and Depths Regularization](https://arxiv.org/abs/2609.36969v1)**  
  Authors: Gyeonggwan Lee, Seunghwan Hong, Junghun Suh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36969v1.pdf)  
  Keywords: gaussian splatting, motion, 3d gaussian, ar, face  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, localization, geometry, deformation, ar, 3d gaussian  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: 3d reconstruction, gaussian splatting, dynamic, motion, ar, real-time rendering  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: gaussian splatting, lighting, motion, ar, 3d gaussian, vr  
- **[Gaussian Splatting-based Volumetric Video Compression with Sparse 4D Anchors](https://arxiv.org/abs/2609.33969v1)**  
  Authors: Ge Gao, Siyue Teng, Chanqgi Wang, Fan Zhang, Nantheera Anantrasirichai, Jui Chiu Chiang, Wen-Hsiao Peng, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33969v1.pdf)  
  Keywords: 4d, gaussian splatting, dynamic, motion, ar, compact, geometry, efficient, 3d gaussian, compression  
- **[ProDyGS: Dynamic Gaussian Splatting from a Single Static Monocular Camera](https://arxiv.org/abs/2609.32711v1)**  
  Authors: Ugo Leone Cavalcanti, Fabio Tosi, Matteo Poggi, Andrea Conti, Vladimir Zlokolica, Valerio Cambareri, Stefano Mattoccia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32711v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, deformation, ar, nerf, 3d gaussian  
- **[Endo-TSR: Temporal Spectral Modeling of Appearance and Motion for Endoscopic Reconstruction](https://arxiv.org/abs/2609.32399v1)**  
  Authors: Taoyu Wu, Yiyi Miao, Qi Shao, Zhuoxiao Li, Zhe Tang, Limin Yu, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32399v1.pdf)  
  Keywords: gaussian splatting, motion, ar, efficient, nerf, face  
- **[OneFixer: High-Quality and Consistent One-Step Autoregressive 3DGS Refinement for Driving Scenes](https://arxiv.org/abs/2609.32175v1)**  
  Authors: Boseong Jeon, Junhyeop Lee, Juhan Cha, Hayoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32175v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://onefixer-web.vercel.app/)  
  Keywords: gaussian splatting, dynamic, geometry, ar, 3d gaussian  
- **[OC-GS: Gaussian Splatting for Irregular Turntable Capture](https://arxiv.org/abs/2609.31572v1)**  
  Authors: Jae Joong Lee, Bedrich Benes  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31572v1.pdf)  
  Keywords: gaussian splatting, ar, motion, geometry  

### Few-shot

*Showing the latest 50 out of 84 papers*

- **[Remote Sensing Sparse-View 3D Gaussian Splatting via Depth Image-Based Rendering](https://arxiv.org/abs/2609.35612v1)**  
  Authors: Jiaming Kang, Zhengxia Zou, Zhenwei Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35612v1.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d gaussian, ar, nerf, face  
- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v2)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v2.pdf)  
  Keywords: sparse-view, gaussian splatting, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[D3GS: Depth, DINO, and RGB Diffusion Co-Guided 3D Gaussian Splatting for Sparse-View Reconstruction](https://arxiv.org/abs/2609.22941v1)**  
  Authors: Yunqi Gao, Zhanfeng Liao, Hanzhang Tu, Zhaoqi Su, Guoqing Zheng, Songtao Wang, Hongwen Zhang, Zhou Xue, Leyuan Liu, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22941v1.pdf)  
  Keywords: sparse-view, gaussian splatting, geometry, ar, nerf, 3d gaussian  
- **[LINGO: Latent Initialization and Gradient Optimization for Sparse-view X-ray Novel View Synthesis and CT Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2609.22849v1)**  
  Authors: Lifeng Xing, Dequan Jin, Kunpeng Bu, Peigeng He, Shihui Ying  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22849v1.pdf)  
  Keywords: sparse-view, gaussian splatting, dynamic, ar, 3d gaussian  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: sparse-view, 4d, gaussian splatting, dynamic, ar, large scene  
- **[Geometry beneath the Waves: Dense Priors for Sparse-View Underwater 3D Gaussian Splatting](https://arxiv.org/abs/2609.18737v1)**  
  Authors: Harvey Caldeira, Haoran Wang, Guoxi Huang, Shaoyu Cai, Rachel Fu, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18737v1.pdf)  
  Keywords: sparse-view, 3d reconstruction, gaussian splatting, geometry, ar, 3d gaussian  
- **[CADSplat: Sparse-View 3D Gaussian Splatting Aided by CAD Models for Robust, Photorealistic Digital-Twin Reconstruction](https://arxiv.org/abs/2609.18473v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18473v1.pdf)  
  Keywords: sparse-view, gaussian splatting, deformation, few-shot, ar, face, 3d gaussian  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: sparse-view, gaussian splatting, motion, geometry, ar, 3d gaussian  
- **[VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views](https://arxiv.org/abs/2609.12343v1)**  
  Authors: Yunsu Jeong, Hyuk Heo, Youngsang Kwak, Jaehwa Kwak, Il Yong Chun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12343v1.pdf)  
  Keywords: gaussian splatting, ar, sparse-view  
- **[Shape-guided Gaussian Splatting for Sparse-View X-ray 3D Reconstruction](https://arxiv.org/abs/2609.10376v1)**  
  Authors: Pranav Poudel, Florence Dell'Aniello Picard, Nairouz Shehata, Frédéric Lavoie, Herve Lombaert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10376v1.pdf)  
  Keywords: sparse-view, 3d reconstruction, gaussian splatting, geometry, ar, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 417 papers*

- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, gaussian splatting, understanding, compact, geometry, body, ar, 3d gaussian  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: illumination, gaussian splatting, dynamic, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, fast, 3d gaussian  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, localization, geometry, deformation, ar, 3d gaussian  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: 3d reconstruction, gaussian splatting, dynamic, motion, ar, real-time rendering  
- **[GenNVS: Geometry-enhanced Novel View Synthesis via Disentangled 3D Prior](https://arxiv.org/abs/2609.34579v2)**  
  Authors: Yajiao Xiong, Youyu Luan, Xiaoyu Zhou, Yongtao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34579v2.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[AGILE-GS: Anchor-Guided Fast Next-Best-View Selection for Active 3D Gaussian Splatting](https://arxiv.org/abs/2609.34176v1)**  
  Authors: Amirhossein Mollaei Khass, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34176v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, fast, 3d gaussian  
- **[Gaussian Splatting-based Volumetric Video Compression with Sparse 4D Anchors](https://arxiv.org/abs/2609.33969v1)**  
  Authors: Ge Gao, Siyue Teng, Chanqgi Wang, Fan Zhang, Nantheera Anantrasirichai, Jui Chiu Chiang, Wen-Hsiao Peng, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33969v1.pdf)  
  Keywords: 4d, gaussian splatting, dynamic, motion, ar, compact, geometry, efficient, 3d gaussian, compression  
- **[Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation](https://arxiv.org/abs/2609.33872v1)**  
  Authors: Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang, Daqiang Guo, Peng Zhou, Lihui Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33872v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://robot-gst.github.io)  
  Keywords: gaussian splatting, geometry, high-fidelity, ar, 3d gaussian  
- **[OneFixer: High-Quality and Consistent One-Step Autoregressive 3DGS Refinement for Driving Scenes](https://arxiv.org/abs/2609.32175v1)**  
  Authors: Boseong Jeon, Junhyeop Lee, Juhan Cha, Hayoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32175v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://onefixer-web.vercel.app/)  
  Keywords: gaussian splatting, dynamic, geometry, ar, 3d gaussian  

### Large Scene

- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, face, large scene, 3d gaussian  
- **[ChronoFuseGS: Multi-Temporal Gaussian Fusion with Per-Splat Persistence and Change Visualization](https://arxiv.org/abs/2609.31339v1)**  
  Authors: Tobias Batik, Diana Marin, Peter Kán, Hannes Kaufmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31339v1.pdf)  
  Keywords: gaussian splatting, ar, outdoor  
- **[OceanXL: Large-scale Underwater 3D Gaussian Splatting via Block Partitioning and Adaptive Pruning](https://arxiv.org/abs/2609.29985v1)**  
  Authors: Haoran Wang, Shaoyu Cai, Adrian Azzarelli, Zhuodong Jiang, Guoxi Huang, Eng Tat Khoo, Brett Seymour, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29985v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, ar, compact, efficient, fast, real-time rendering, nerf, large scene, 3d gaussian  
- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: gaussian splatting, motion, outdoor, ar, 3d gaussian  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: gaussian splatting, slam, tracking, 3d gaussian, geometry, outdoor, ar, face  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: mapping, gaussian splatting, slam, high-fidelity, tracking, 3d gaussian, outdoor, ar, face  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: sparse-view, 4d, gaussian splatting, dynamic, ar, large scene  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: gaussian splatting, motion, outdoor, ar, 3d gaussian  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: 4d, human, illumination, gaussian splatting, dynamic, ar, outdoor, fast  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: gaussian splatting, compact, outdoor, ar, head, nerf, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 405 papers*

- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, gaussian splatting, understanding, compact, geometry, body, ar, 3d gaussian  
- **[NRF-GS: Neural Residual Fields for Expressive and Compact Gaussian Splatting](https://arxiv.org/abs/2609.37115v1)**  
  Authors: Pratik Singh Bisht, Andreas Kolb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37115v1.pdf)  
  Keywords: gaussian splatting, lightweight, compact, ar, 3d gaussian  
- **[AESplat: Advancing Pose-Free Feed-Forward 3D Gaussian Splatting via Decoupled Appearance Modeling](https://arxiv.org/abs/2609.36693v1)**  
  Authors: Shiwei Ren, Zhiang Liu, Yongchun Fang, Hongwei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36693v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aesplat.github.io/.)  
  Keywords: gaussian splatting, efficient, ar, 3d gaussian  
- **[Less Is More: Genetic Frame Selection for Efficient Novel View Synthesis](https://arxiv.org/abs/2609.35573v1)**  
  Authors: Diego E. Farchione, Ramzi Idoughi, Alberto Jaspe-Villanueva, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35573v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, nerf, 3d gaussian  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, compact, segmentation, ar, 3d gaussian  
- **[Rate-Distortion Adaptive Primitive Selection for Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2609.34367v1)**  
  Authors: Yulong Cheng, Youneng Bao, Junfeng Zhou, Mu Li, Jie Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34367v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, fast, vr  
- **[Gaussian Splatting-based Volumetric Video Compression with Sparse 4D Anchors](https://arxiv.org/abs/2609.33969v1)**  
  Authors: Ge Gao, Siyue Teng, Chanqgi Wang, Fan Zhang, Nantheera Anantrasirichai, Jui Chiu Chiang, Wen-Hsiao Peng, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33969v1.pdf)  
  Keywords: 4d, gaussian splatting, dynamic, motion, ar, compact, geometry, efficient, 3d gaussian, compression  
- **[FeCoSplat: Feedback-Guided Compression for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2609.33330v1)**  
  Authors: Yuxuan Li, Yihang Chen, Yufeng Zhang, Jianfei Cai, Weiyao Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33330v1.pdf)  
  Keywords: gaussian splatting, ar, compact, lightweight, efficient, 3d gaussian, compression  
- **[Endo-TSR: Temporal Spectral Modeling of Appearance and Motion for Endoscopic Reconstruction](https://arxiv.org/abs/2609.32399v1)**  
  Authors: Taoyu Wu, Yiyi Miao, Qi Shao, Zhuoxiao Li, Zhe Tang, Limin Yu, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32399v1.pdf)  
  Keywords: gaussian splatting, motion, ar, efficient, nerf, face  
- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, efficient, face, large scene, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 204 papers*

- **[Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation](https://arxiv.org/abs/2609.33872v1)**  
  Authors: Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang, Daqiang Guo, Peng Zhou, Lihui Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33872v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://robot-gst.github.io)  
  Keywords: gaussian splatting, geometry, high-fidelity, ar, 3d gaussian  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: survey, gaussian splatting, 3d gaussian, high-fidelity, ar, face  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: gaussian splatting, dynamic, compact, geometry, high-fidelity, ar, face  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: mapping, gaussian splatting, slam, high-fidelity, tracking, 3d gaussian, outdoor, ar, face  
- **[AirSplan: Risk-Aware Motion Planning for Quadrotors in Cluttered 3D Gaussian Splats](https://arxiv.org/abs/2609.21226v1)**  
  Authors: Seth Isaacson, William Hong, Katherine A. Skinner, Ram Vasudevan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21226v1.pdf)  
  Keywords: gaussian splatting, motion, geometry, high-fidelity, ar, 3d gaussian  
- **[Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning](https://arxiv.org/abs/2609.21112v1)**  
  Authors: Beichen Wang, Yuen-Hei Yeung, V. R. Sridhar Devarakonda, Xuesu Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21112v1.pdf)  
  Keywords: human, gaussian splatting, dynamic, high-fidelity, ar, 3d gaussian  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, ar, lightweight, deformation, efficient, fast, compression  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: gaussian splatting, ar, lightweight, geometry, high-fidelity, fast, head, 3d gaussian  
- **[GSComplete: Gaussian Splat Completion with 2D Diffusion Priors](https://arxiv.org/abs/2609.08449v1)**  
  Authors: Elias Brugger, Philipp Erler, Stefan Ohrhallinger, Paul Guerrero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08449v1.pdf)  
  Keywords: fast, ar, high-fidelity  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: gaussian splatting, slam, motion, ar, tracking, high-fidelity, efficient, fast, 3d gaussian  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: gaussian splatting, motion, ar, compact, face, fast, real-time rendering, nerf, ray tracing, 3d gaussian  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: mapping, gaussian splatting, shadow, ar, compact, reflection, efficient, fast, nerf, ray tracing, 3d gaussian  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: illumination, gaussian splatting, lighting, ar, reflection, efficient, ray tracing, relighting, face  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: human, gaussian splatting, dynamic, motion, face, reflection, geometry, high-fidelity, ar, ray tracing, 3d gaussian  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: gaussian splatting, ar, fast, ray tracing, 3d gaussian  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: gaussian splatting, ar, reflection, geometry, efficient, fast, real-time rendering, ray tracing, path tracing, 3d gaussian  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d reconstruction, illumination, gaussian splatting, ar, global illumination, geometry, efficient, 3d gaussian  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: illumination, gaussian splatting, global illumination, high-fidelity, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, segmentation, reflection, geometry, efficient, ray tracing, 3d gaussian  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: illumination, gaussian splatting, shadow, ar, global illumination, fast, face, 3d gaussian  

### Relighting

*Showing the latest 50 out of 117 papers*

- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: illumination, gaussian splatting, dynamic, geometry, ar, real-time rendering, nerf, 3d gaussian  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: gaussian splatting, lighting, motion, ar, 3d gaussian, vr  
- **[PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2609.28645v1)**  
  Authors: Sungjae Choi, Seunghee Koh, Junmo Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28645v1.pdf)  
  Keywords: gaussian splatting, lighting, semantic, segmentation, geometry, ar, nerf, 3d gaussian  
- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: mapping, illumination, gaussian splatting, shadow, lighting, dynamic, motion, slam, tracking, ar  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: illumination, gaussian splatting, relightable, lighting, semantic, ar, geometry, efficient  
- **[RGS: Reflection-aware Gaussian Splatting via Learning Geometry Continuity for Reflective Objects](https://arxiv.org/abs/2609.19421v1)**  
  Authors: Xiaobiao Du, Yida Wang, Cheng Bi, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19421v1.pdf)  
  Keywords: gaussian splatting, reflection, 3d gaussian, geometry, ar, face  
- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: mapping, gaussian splatting, slam, lighting, dynamic, motion, localization, tracking, robotics, ar, geometry, fast, 3d gaussian  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: 4d, human, illumination, gaussian splatting, dynamic, ar, outdoor, fast  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: gaussian splatting, lighting, robotics, recognition, geometry, ar, 3d gaussian  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: gaussian splatting, lighting, ar, compact, efficient, 3d gaussian  

### SLAM

*Showing the latest 50 out of 163 papers*

- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, localization, geometry, deformation, ar, 3d gaussian  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, compact, segmentation, ar, 3d gaussian  
- **[Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free 3D Gaussian Splatting](https://arxiv.org/abs/2609.30865v1)**  
  Authors: Zijian Wu, Jinliang Wang, Zidian Lin, Ying Song, Ziqian Lu, Hanjie Ma, Zhen Ye, Mingfeng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.30865v1.pdf)  
  Keywords: gaussian splatting, dynamic, motion, tracking, ar, 3d gaussian  
- **[From Scattered Gaussians to Structured Maps: Efficient Gaussian Splatting Coding via Dual-phase Morton Sorting](https://arxiv.org/abs/2609.29041v1)**  
  Authors: Bolin Chen, Shanzhi Yin, Ru-Ling Liao, Yibo Fan, Yan Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29041v1.pdf)  
  Keywords: mapping, gaussian splatting, ar, efficient, 3d gaussian, compression  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: gaussian splatting, slam, semantic, ar, 3d gaussian, fast, face  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: gaussian splatting, slam, tracking, 3d gaussian, geometry, outdoor, ar, face  
- **[BayesianGS-SLAM: Uncertainty-Aware Neural Rendering SLAM via Probabilistic Formulation](https://arxiv.org/abs/2609.24140v1)**  
  Authors: Kyeongsu Kang, Seongbo Ha, Sibaek Lee, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24140v1.pdf)  
  Keywords: mapping, gaussian splatting, slam, tracking, ar, neural rendering, 3d gaussian  
- **[Elevator-VIGS: Separating Elevator Motion from Robot Motion in Visual-Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2609.23491v1)**  
  Authors: Rui Zhou, Zihan Zhu, Wei Zhang, Zizhou Luo, Norbert Haala, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ruizhou-cn.github.io/elevator-vigs/.)  
  Keywords: mapping, gaussian splatting, slam, motion, tracking, ar, 3d gaussian  
- **[VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction](https://arxiv.org/abs/2609.23049v1)**  
  Authors: Haolin Yu, Jiadong Tang, YiXian Wang, Yu Gao, Shi He, Zhilin Lai, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23049v1.pdf)  
  Keywords: mapping, autonomous driving, gaussian splatting, 3d gaussian, ar, face  
- **[Kinematic Interface for the Wild: Modular Bimanual Loco-Manipulation Capture from 360$^{\circ}$ Cameras Alone](https://arxiv.org/abs/2609.22809v1)**  
  Authors: Benjamin Yang, Weiying Wang, Shenggao Li, Keming Yan, Sasha Wilkinson, Zelin Wang, Yip Fun Yeung, Lingfeng Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22809v1.pdf)  
  Keywords: localization, tracking, 3d gaussian, ar, head, face  

### Scene Understanding

*Showing the latest 50 out of 210 papers*

- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, gaussian splatting, understanding, compact, geometry, body, ar, 3d gaussian  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: gaussian splatting, understanding, localization, compact, segmentation, ar, 3d gaussian  
- **[GraphWrit3R: End-to-End 3D Scene Graph Writing](https://arxiv.org/abs/2609.31595v1)**  
  Authors: Luka Milivojevic, Nikola Popovic, Sayan Deb Sarkar, Sebastian Koch, Iro Armeni, Luc Van Gool, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31595v1.pdf)  
  Keywords: ar, semantic  
- **[PlenoCI: Plenoptic CharacterIstics for View Dependence Aware Change Classification](https://arxiv.org/abs/2609.28930v1)**  
  Authors: Jason Lai, Chamuditha Jayanga Galappaththige, Niko Suenderhauf, Dimity Miller, Donald G. Dansereau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://js0n-lai.github.io/plenoci.)  
  Keywords: gaussian splatting, understanding, ar, efficient, 3d gaussian  
- **[PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2609.28645v1)**  
  Authors: Sungjae Choi, Seunghee Koh, Junmo Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28645v1.pdf)  
  Keywords: gaussian splatting, lighting, semantic, segmentation, geometry, ar, nerf, 3d gaussian  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: gaussian splatting, slam, semantic, ar, 3d gaussian, fast, face  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, semantic, ar, neural rendering, face  
- **[CoRef-GS: Cooperative Referring Gaussian Splatting for Multi-Agent Scene Understanding](https://arxiv.org/abs/2609.20586v1)**  
  Authors: Zhikun Zhou, Kunyu Peng, Runyi Yang, Junhao Cai, Di Wen, Ruiping Liu, Danda Pani Paudel, Yi Zhou, Luc Van Gool, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20586v1.pdf)  
  Keywords: gaussian splatting, understanding, semantic, ar  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: illumination, gaussian splatting, relightable, lighting, semantic, ar, geometry, efficient  
- **[GAPrompt++: Multi-Granular Geometry-Aware Point Cloud Prompt for 3D Vision Model](https://arxiv.org/abs/2609.19716v1)**  
  Authors: Zixiang Ai, Zhenyu Cui, Yufei Guo, Wenwen Qiang, Lei Chen, Jiwen Lu, Jiahuan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19716v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, geometry, efficient, 3d gaussian  



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