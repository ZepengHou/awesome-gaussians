# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-10-02 03:08:45

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
- [Acceleration](#acceleration) (197 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (318 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (362 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (84 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (415 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (47 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (401 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (203 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (22 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (112 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (163 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (208 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, survey, ar, face  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compression, survey, ar  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: motion, gaussian splatting, survey, ar, 3d reconstruction, geometry, illumination  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: 3d gaussian, gaussian splatting, survey, ar, dynamic, nerf, 3d reconstruction, geometry  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: neural rendering, motion, 3d gaussian, medical, gaussian splatting, survey, ar, 4d, 3d reconstruction, autonomous driving, compact, vr, recognition  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: animation, gaussian splatting, survey, ar, mapping, geometry  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: efficient, motion, 3d gaussian, gaussian splatting, slam, survey, ar, 3d reconstruction, tracking, geometry  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, ar, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v8)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v8.pdf)  
  Keywords: 3d gaussian, gaussian splatting, survey, ar, mapping, ray tracing  

### Acceleration

*Showing the latest 50 out of 197 papers*

- **[Affine-Aligned Atlas for Canonical Gaussian Construction in Video Representation](https://arxiv.org/abs/2610.01114v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01114v1.pdf)  
  Keywords: efficient, motion, gaussian splatting, ar, fast, deformation  
- **[Dirichlet Splatting: Differentiable Rendering for Wave-Based Inverse Problems](https://arxiv.org/abs/2610.00618v1)**  
  Authors: Xingyu Chen, Wuqiong Zhao, Xinyu Zhang, Tzu-Mao Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00618v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, fast  
- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: efficient, 3d gaussian, high-fidelity, gaussian splatting, ar, compact, acceleration  
- **[RLX: A Unified Multi-Backend Tensor Compiler and Distributed Runtime in Rust](https://arxiv.org/abs/2609.37916v1)**  
  Authors: Eugene Hauptmann, Nataliya Kosmyna  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37916v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, fast  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, gaussian splatting, ar, dynamic, nerf, real-time rendering, geometry, illumination  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, geometry  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: motion, gaussian splatting, ar, dynamic, real-time rendering, 3d reconstruction  
- **[Rate-Distortion Adaptive Primitive Selection for Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2609.34367v2)**  
  Authors: Yulong Cheng, Youneng Bao, Junfeng Zhou, Mu Li, Jie Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34367v2.pdf)  
  Keywords: efficient, lightweight, gaussian splatting, ar, fast, vr  
- **[AGILE-GS: Anchor-Guided Fast Next-Best-View Selection for Active 3D Gaussian Splatting](https://arxiv.org/abs/2609.34176v1)**  
  Authors: Amirhossein Mollaei Khass, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34176v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, geometry  
- **[Towards Practical Compression of 3D Gaussian Splatting](https://arxiv.org/abs/2609.30245v1)**  
  Authors: Pengpeng Yu, Yueru Chen, Fei Song, Tai Qin, Qi Zhang, Jing Wang, Yulan Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.30245v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, compression, ar, fast, geometry, compact  

### Applications

*Showing the latest 50 out of 996 papers*

- **[EvenSplat: Coupled 2D-3D Decomposition for Gaussian Splatting under Exposure and Illumination Variation](https://arxiv.org/abs/2610.01876v1)**  
  Authors: Tongyu Wu, Jacob Edwards, Ziteng Cui, Caigui Jiang, Cheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01876v1.pdf)  
  Keywords: 3d gaussian, illumination, gaussian splatting, lighting, ar, face, geometry, shadow  
- **[MEGA: Object-Level Mesh Extraction from 3D Gaussian Splatting via Spatial Visual Distillation](https://arxiv.org/abs/2610.01707v1)**  
  Authors: Liwei Liao, Yingkui Zhang, Qianqian Tong, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01707v1.pdf)  
  Keywords: ar, face, 3d gaussian, gaussian splatting  
- **[Affine-Aligned Atlas for Canonical Gaussian Construction in Video Representation](https://arxiv.org/abs/2610.01114v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01114v1.pdf)  
  Keywords: efficient, motion, gaussian splatting, ar, fast, deformation  
- **[TRACE: Privacy-Preserving Next-Best-View Selection over Distributed 3D Gaussian-Splat Maps](https://arxiv.org/abs/2610.00822v1)**  
  Authors: Amirhossein Mollaei Khass, Athanasios Cosse, Qiyu Sun, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00822v1.pdf)  
  Keywords: ar, 3d gaussian, head, gaussian splatting  
- **[What Builds the Scene? Luminance Dominates Geometry Formation in 3D Gaussian Splatting](https://arxiv.org/abs/2610.00749v1)**  
  Authors: Rezvan Joshaghani, Steven Cutchin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00749v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, geometry  
- **[Measuring Asset and Scene Reconstruction Effects in Real-to-Sim Robot Evaluation](https://arxiv.org/abs/2610.00731v1)**  
  Authors: Sanya Verma, Luca Cilio, Velissarios Christodoulou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00731v1.pdf)  
  Keywords: ar, geometry  
- **[Dirichlet Splatting: Differentiable Rendering for Wave-Based Inverse Problems](https://arxiv.org/abs/2610.00618v1)**  
  Authors: Xingyu Chen, Wuqiong Zhao, Xinyu Zhang, Tzu-Mao Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00618v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, fast  
- **[Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction](https://arxiv.org/abs/2609.39960v1)**  
  Authors: Ziren Gong, Guo Chen, Yongjia Li, Yihua Shao, Fabio Tosi, Stefano Mattoccia, Matteo Poggi, Hao Tang, Fei Ma, Shuyan Li, Ziyang Yan, Nicu Sebe, Ling Shao, Jianfei Cai, Qi Tian, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39960v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, nerf, 4d, understanding, geometry  
- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: efficient, 3d gaussian, high-fidelity, gaussian splatting, ar, compact, acceleration  
- **[Lens Flare Removal and Reconstruction](https://arxiv.org/abs/2609.39527v1)**  
  Authors: Tarun Yenamandra, Jonathon Luiten, Daniel Cremers, Nathan Matsuda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39527v1.pdf)  
  Keywords: ar, localization, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 318 papers*

- **[EvenSplat: Coupled 2D-3D Decomposition for Gaussian Splatting under Exposure and Illumination Variation](https://arxiv.org/abs/2610.01876v1)**  
  Authors: Tongyu Wu, Jacob Edwards, Ziteng Cui, Caigui Jiang, Cheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01876v1.pdf)  
  Keywords: 3d gaussian, illumination, gaussian splatting, lighting, ar, face, geometry, shadow  
- **[MEGA: Object-Level Mesh Extraction from 3D Gaussian Splatting via Spatial Visual Distillation](https://arxiv.org/abs/2610.01707v1)**  
  Authors: Liwei Liao, Yingkui Zhang, Qianqian Tong, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01707v1.pdf)  
  Keywords: ar, face, 3d gaussian, gaussian splatting  
- **[TRACE: Privacy-Preserving Next-Best-View Selection over Distributed 3D Gaussian-Splat Maps](https://arxiv.org/abs/2610.00822v1)**  
  Authors: Amirhossein Mollaei Khass, Athanasios Cosse, Qiyu Sun, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00822v1.pdf)  
  Keywords: ar, 3d gaussian, head, gaussian splatting  
- **[What Builds the Scene? Luminance Dominates Geometry Formation in 3D Gaussian Splatting](https://arxiv.org/abs/2610.00749v1)**  
  Authors: Rezvan Joshaghani, Steven Cutchin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00749v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, geometry  
- **[UGOD: Uncertainty-Guided Opacity and Dropout for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.39089v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Chenghao Qian, Ziyang Wang, Xinqi Fan, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39089v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, sparse-view, ar, nerf, compact, head  
- **[StereoGaussians: Feed-Forward 3D Gaussian Splatting from Stereo Images](https://arxiv.org/abs/2609.38592v1)**  
  Authors: Boyuan Tian, Huangying Zhan, Zhan Li, Shin-Fang Chng, Hanwen Yang, Zirui Wang, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38592v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, geometry  
- **[Beyond Monoscopic Viewing: A Study on 3D Gaussian Splatting Quality in VR](https://arxiv.org/abs/2609.38525v1)**  
  Authors: Shreyas Shivakumara, Gabriel Eilertsen, Karljohan Lundin Palmerius  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38525v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, geometry, head, vr  
- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, 3d gaussian, gaussian splatting, ar, understanding, compact, geometry, body  
- **[Prior-Driven Enhancements in 3D Gaussian Splatting: Normals and Depths Regularization](https://arxiv.org/abs/2609.36969v1)**  
  Authors: Gyeonggwan Lee, Seunghwan Hong, Junghun Suh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36969v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, face  
- **[Remote Sensing Sparse-View 3D Gaussian Splatting via Depth Image-Based Rendering](https://arxiv.org/abs/2609.35612v1)**  
  Authors: Jiaming Kang, Zhengxia Zou, Zhenwei Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35612v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, face, nerf  

### Dynamic Scene

*Showing the latest 50 out of 362 papers*

- **[Affine-Aligned Atlas for Canonical Gaussian Construction in Video Representation](https://arxiv.org/abs/2610.01114v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01114v1.pdf)  
  Keywords: efficient, motion, gaussian splatting, ar, fast, deformation  
- **[Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction](https://arxiv.org/abs/2609.39960v1)**  
  Authors: Ziren Gong, Guo Chen, Yongjia Li, Yihua Shao, Fabio Tosi, Stefano Mattoccia, Matteo Poggi, Hao Tang, Fei Ma, Shuyan Li, Ziyang Yan, Nicu Sebe, Ling Shao, Jianfei Cai, Qi Tian, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39960v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, nerf, 4d, understanding, geometry  
- **[Eulerian Motion Reconstruction for Water Scenery](https://arxiv.org/abs/2609.38622v1)**  
  Authors: Chuhan Chen, Yen-Chi Cheng, Ayush Saraf, Rajvi Shah, Tuotuo Li, Johannes Kopf, Chen Gao, Hung-Yu Tseng, Deva Ramanan, Matthew O'Toole, Changil Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38622v1.pdf)  
  Keywords: motion, animation, ar, dynamic, 4d  
- **[PneuTac: Tactile Manipulation with Soft Pneumatic Robots via Unified MPM-Gaussian Splatting Simulation](https://arxiv.org/abs/2609.38418v1)**  
  Authors: Shaohong Zhong, Marco Pontin, Joe Watson, Perla Maiolino, Ingmar Posner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38418v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, dynamic  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, gaussian splatting, ar, dynamic, nerf, real-time rendering, geometry, illumination  
- **[Prior-Driven Enhancements in 3D Gaussian Splatting: Normals and Depths Regularization](https://arxiv.org/abs/2609.36969v1)**  
  Authors: Gyeonggwan Lee, Seunghwan Hong, Junghun Suh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36969v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, face  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, localization, geometry, deformation  
- **[Distilling Privileged Control Barrier Functions into RGB-Only Safety Filters for Dynamic Visual Navigation](https://arxiv.org/abs/2609.36520v1)**  
  Authors: Seungyeon Yoo, Gawon Lee, Seungwoo Jung, Inkyu Jang, H. Jin Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://syeon-yoo.github.io/distill-cbf-site/.)  
  Keywords: motion, gaussian splatting, ar, dynamic, real-time rendering, 3d reconstruction  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, lighting, ar, vr  
- **[Gaussian Splatting-based Volumetric Video Compression with Sparse 4D Anchors](https://arxiv.org/abs/2609.33969v1)**  
  Authors: Ge Gao, Siyue Teng, Chanqgi Wang, Fan Zhang, Nantheera Anantrasirichai, Jui Chiu Chiang, Wen-Hsiao Peng, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33969v1.pdf)  
  Keywords: efficient, motion, 3d gaussian, gaussian splatting, compression, ar, dynamic, 4d, geometry, compact  

### Few-shot

*Showing the latest 50 out of 84 papers*

- **[UGOD: Uncertainty-Guided Opacity and Dropout for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.39089v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Chenghao Qian, Ziyang Wang, Xinqi Fan, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39089v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, sparse-view, ar, nerf, compact, head  
- **[Remote Sensing Sparse-View 3D Gaussian Splatting via Depth Image-Based Rendering](https://arxiv.org/abs/2609.35612v1)**  
  Authors: Jiaming Kang, Zhengxia Zou, Zhenwei Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35612v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, face, nerf  
- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v2)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v2.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, nerf, real-time rendering, geometry  
- **[D3GS: Depth, DINO, and RGB Diffusion Co-Guided 3D Gaussian Splatting for Sparse-View Reconstruction](https://arxiv.org/abs/2609.22941v1)**  
  Authors: Yunqi Gao, Zhanfeng Liao, Hanzhang Tu, Zhaoqi Su, Guoqing Zheng, Songtao Wang, Hongwen Zhang, Zhou Xue, Leyuan Liu, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22941v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, nerf, geometry  
- **[LINGO: Latent Initialization and Gradient Optimization for Sparse-view X-ray Novel View Synthesis and CT Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2609.22849v1)**  
  Authors: Lifeng Xing, Dequan Jin, Kunpeng Bu, Peigeng He, Shihui Ying  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22849v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, dynamic  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: gaussian splatting, sparse-view, ar, dynamic, 4d, large scene  
- **[Geometry beneath the Waves: Dense Priors for Sparse-View Underwater 3D Gaussian Splatting](https://arxiv.org/abs/2609.18737v2)**  
  Authors: Harvey Caldeira, Haoran Wang, Guoxi Huang, Shaoyu Cai, Rachel Fu, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18737v2.pdf)  
  Keywords: sparse view, motion, 3d gaussian, gaussian splatting, sparse-view, ar, nerf, 3d reconstruction, geometry, head  
- **[CADSplat: Sparse-View 3D Gaussian Splatting Aided by CAD Models for Robust, Photorealistic Digital-Twin Reconstruction](https://arxiv.org/abs/2609.18473v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18473v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, ar, face, few-shot, deformation  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, sparse-view, ar, geometry  
- **[VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views](https://arxiv.org/abs/2609.12343v1)**  
  Authors: Yunsu Jeong, Hyuk Heo, Youngsang Kwak, Jaehwa Kwak, Il Yong Chun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12343v1.pdf)  
  Keywords: sparse-view, ar, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 415 papers*

- **[EvenSplat: Coupled 2D-3D Decomposition for Gaussian Splatting under Exposure and Illumination Variation](https://arxiv.org/abs/2610.01876v1)**  
  Authors: Tongyu Wu, Jacob Edwards, Ziteng Cui, Caigui Jiang, Cheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01876v1.pdf)  
  Keywords: 3d gaussian, illumination, gaussian splatting, lighting, ar, face, geometry, shadow  
- **[What Builds the Scene? Luminance Dominates Geometry Formation in 3D Gaussian Splatting](https://arxiv.org/abs/2610.00749v1)**  
  Authors: Rezvan Joshaghani, Steven Cutchin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00749v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, geometry  
- **[Measuring Asset and Scene Reconstruction Effects in Real-to-Sim Robot Evaluation](https://arxiv.org/abs/2610.00731v1)**  
  Authors: Sanya Verma, Luca Cilio, Velissarios Christodoulou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00731v1.pdf)  
  Keywords: ar, geometry  
- **[Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction](https://arxiv.org/abs/2609.39960v1)**  
  Authors: Ziren Gong, Guo Chen, Yongjia Li, Yihua Shao, Fabio Tosi, Stefano Mattoccia, Matteo Poggi, Hao Tang, Fei Ma, Shuyan Li, Ziyang Yan, Nicu Sebe, Ling Shao, Jianfei Cai, Qi Tian, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39960v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, nerf, 4d, understanding, geometry  
- **[TSGL: Teacher-Student Graph Learning for 3DGS Compression](https://arxiv.org/abs/2609.38635v1)**  
  Authors: Matin Bani Saedi, Matthew Kyan, Gene Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38635v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, compression, ar, compact, geometry  
- **[StereoGaussians: Feed-Forward 3D Gaussian Splatting from Stereo Images](https://arxiv.org/abs/2609.38592v1)**  
  Authors: Boyuan Tian, Huangying Zhan, Zhan Li, Shin-Fang Chng, Hanwen Yang, Zirui Wang, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38592v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, geometry  
- **[Beyond Monoscopic Viewing: A Study on 3D Gaussian Splatting Quality in VR](https://arxiv.org/abs/2609.38525v1)**  
  Authors: Shreyas Shivakumara, Gabriel Eilertsen, Karljohan Lundin Palmerius  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38525v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, geometry, head, vr  
- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, 3d gaussian, gaussian splatting, ar, understanding, compact, geometry, body  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, gaussian splatting, ar, dynamic, nerf, real-time rendering, geometry, illumination  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, geometry  

### Large Scene

- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: efficient, lightweight, 3d gaussian, gaussian splatting, ar, face, large scene  
- **[ChronoFuseGS: Multi-Temporal Gaussian Fusion with Per-Splat Persistence and Change Visualization](https://arxiv.org/abs/2609.31339v1)**  
  Authors: Tobias Batik, Diana Marin, Peter Kán, Hannes Kaufmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31339v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting  
- **[OceanXL: Large-scale Underwater 3D Gaussian Splatting via Block Partitioning and Adaptive Pruning](https://arxiv.org/abs/2609.29985v1)**  
  Authors: Haoran Wang, Shaoyu Cai, Adrian Azzarelli, Zhuodong Jiang, Guoxi Huang, Eng Tat Khoo, Brett Seymour, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29985v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, nerf, real-time rendering, fast, 3d reconstruction, large scene, compact  
- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, outdoor, ar  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, slam, outdoor, ar, face, tracking, geometry  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, slam, outdoor, ar, face, mapping, tracking  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: gaussian splatting, sparse-view, ar, dynamic, 4d, large scene  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: motion, 3d gaussian, gaussian splatting, outdoor, ar  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: human, gaussian splatting, outdoor, ar, dynamic, 4d, fast, illumination  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, outdoor, ar, nerf, compact, head  

### Model Compression

*Showing the latest 50 out of 401 papers*

- **[Affine-Aligned Atlas for Canonical Gaussian Construction in Video Representation](https://arxiv.org/abs/2610.01114v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01114v1.pdf)  
  Keywords: efficient, motion, gaussian splatting, ar, fast, deformation  
- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: efficient, 3d gaussian, high-fidelity, gaussian splatting, ar, compact, acceleration  
- **[UGOD: Uncertainty-Guided Opacity and Dropout for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.39089v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Chenghao Qian, Ziyang Wang, Xinqi Fan, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39089v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, sparse-view, ar, nerf, compact, head  
- **[TSGL: Teacher-Student Graph Learning for 3DGS Compression](https://arxiv.org/abs/2609.38635v1)**  
  Authors: Matin Bani Saedi, Matthew Kyan, Gene Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38635v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, compression, ar, compact, geometry  
- **[Gaussian Stippling: Efficient Sorting-Free 3D Gaussian Rendering through Hybrid Sampling and Spatiotemporal Reconstruction](https://arxiv.org/abs/2609.38488v1)**  
  Authors: Zijian Huang, Suiliang Mai, Chuankun Zheng, Yuan Meng, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38488v1.pdf)  
  Keywords: lightweight, efficient, 3d gaussian, high-fidelity, gaussian splatting, ar  
- **[PneuTac: Tactile Manipulation with Soft Pneumatic Robots via Unified MPM-Gaussian Splatting Simulation](https://arxiv.org/abs/2609.38418v1)**  
  Authors: Shaohong Zhong, Marco Pontin, Joe Watson, Perla Maiolino, Ingmar Posner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38418v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, dynamic  
- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, 3d gaussian, gaussian splatting, ar, understanding, compact, geometry, body  
- **[NRF-GS: Neural Residual Fields for Expressive and Compact Gaussian Splatting](https://arxiv.org/abs/2609.37115v1)**  
  Authors: Pratik Singh Bisht, Andreas Kolb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37115v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, ar, compact  
- **[AESplat: Advancing Pose-Free Feed-Forward 3D Gaussian Splatting via Decoupled Appearance Modeling](https://arxiv.org/abs/2609.36693v1)**  
  Authors: Shiwei Ren, Zhiang Liu, Yongchun Fang, Hongwei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36693v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://aesplat.github.io/.)  
  Keywords: efficient, ar, 3d gaussian, gaussian splatting  
- **[Less Is More: Genetic Frame Selection for Efficient Novel View Synthesis](https://arxiv.org/abs/2609.35573v1)**  
  Authors: Diego E. Farchione, Ramzi Idoughi, Alberto Jaspe-Villanueva, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35573v1.pdf)  
  Keywords: lightweight, efficient, 3d gaussian, gaussian splatting, ar, nerf  

### Quality Enhancement

*Showing the latest 50 out of 203 papers*

- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: efficient, 3d gaussian, high-fidelity, gaussian splatting, ar, compact, acceleration  
- **[Gaussian Stippling: Efficient Sorting-Free 3D Gaussian Rendering through Hybrid Sampling and Spatiotemporal Reconstruction](https://arxiv.org/abs/2609.38488v1)**  
  Authors: Zijian Huang, Suiliang Mai, Chuankun Zheng, Yuan Meng, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38488v1.pdf)  
  Keywords: lightweight, efficient, 3d gaussian, high-fidelity, gaussian splatting, ar  
- **[Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation](https://arxiv.org/abs/2609.33872v1)**  
  Authors: Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang, Daqiang Guo, Peng Zhou, Lihui Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33872v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://robot-gst.github.io)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, ar, geometry  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, survey, ar, face  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, face, dynamic, compact, geometry  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, gaussian splatting, slam, outdoor, ar, face, mapping, tracking  
- **[AirSplan: Risk-Aware Motion Planning for Quadrotors in Cluttered 3D Gaussian Splats](https://arxiv.org/abs/2609.21226v1)**  
  Authors: Seth Isaacson, William Hong, Katherine A. Skinner, Ram Vasudevan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21226v1.pdf)  
  Keywords: motion, 3d gaussian, high-fidelity, gaussian splatting, ar, geometry  
- **[Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning](https://arxiv.org/abs/2609.21112v1)**  
  Authors: Beichen Wang, Yuen-Hei Yeung, V. R. Sridhar Devarakonda, Xuesu Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21112v1.pdf)  
  Keywords: human, 3d gaussian, high-fidelity, gaussian splatting, ar, dynamic  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: efficient, lightweight, high-fidelity, gaussian splatting, compression, ar, fast, deformation  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: lightweight, 3d gaussian, high-fidelity, gaussian splatting, ar, fast, geometry, head  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, face, nerf, real-time rendering, fast, compact, ray tracing  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: efficient, 3d gaussian, reflection, gaussian splatting, ar, nerf, fast, mapping, compact, ray tracing, shadow  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: efficient, reflection, gaussian splatting, lighting, ar, face, relighting, ray tracing, illumination  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: human, motion, 3d gaussian, reflection, high-fidelity, gaussian splatting, ar, face, dynamic, geometry, ray tracing  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, gaussian splatting, ar, fast, ray tracing  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: efficient, 3d gaussian, reflection, gaussian splatting, ar, real-time rendering, fast, path tracing, geometry, ray tracing  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, 3d reconstruction, global illumination, geometry, illumination  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, global illumination, illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: efficient, 3d gaussian, reflection, gaussian splatting, ar, segmentation, geometry, ray tracing, semantic  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, shadow, face, ar, fast, global illumination, illumination  

### Relighting

*Showing the latest 50 out of 112 papers*

- **[EvenSplat: Coupled 2D-3D Decomposition for Gaussian Splatting under Exposure and Illumination Variation](https://arxiv.org/abs/2610.01876v1)**  
  Authors: Tongyu Wu, Jacob Edwards, Ziteng Cui, Caigui Jiang, Cheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01876v1.pdf)  
  Keywords: 3d gaussian, illumination, gaussian splatting, lighting, ar, face, geometry, shadow  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, gaussian splatting, ar, dynamic, nerf, real-time rendering, geometry, illumination  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, lighting, ar, vr  
- **[PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2609.28645v1)**  
  Authors: Sungjae Choi, Seunghee Koh, Junmo Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28645v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, lighting, ar, nerf, segmentation, geometry, semantic  
- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: motion, illumination, gaussian splatting, slam, lighting, ar, dynamic, mapping, tracking, shadow  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: efficient, relightable, gaussian splatting, lighting, ar, geometry, semantic, illumination  
- **[RGS: Reflection-aware Gaussian Splatting via Learning Geometry Continuity for Reflective Objects](https://arxiv.org/abs/2609.19421v1)**  
  Authors: Xiaobiao Du, Yida Wang, Cheng Bi, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19421v1.pdf)  
  Keywords: 3d gaussian, reflection, gaussian splatting, ar, face, geometry  
- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, slam, lighting, robotics, ar, dynamic, fast, mapping, localization, tracking, geometry  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: human, gaussian splatting, outdoor, ar, dynamic, 4d, fast, illumination  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, lighting, ar, compact  

### SLAM

*Showing the latest 50 out of 163 papers*

- **[Lens Flare Removal and Reconstruction](https://arxiv.org/abs/2609.39527v1)**  
  Authors: Tarun Yenamandra, Jonathon Luiten, Daniel Cremers, Nathan Matsuda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39527v1.pdf)  
  Keywords: ar, localization, gaussian splatting  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, localization, geometry, deformation  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, understanding, segmentation, localization, compact  
- **[Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free 3D Gaussian Splatting](https://arxiv.org/abs/2609.30865v1)**  
  Authors: Zijian Wu, Jinliang Wang, Zidian Lin, Ying Song, Ziqian Lu, Hanjie Ma, Zhen Ye, Mingfeng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.30865v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, tracking  
- **[From Scattered Gaussians to Structured Maps: Efficient Gaussian Splatting Coding via Dual-phase Morton Sorting](https://arxiv.org/abs/2609.29041v1)**  
  Authors: Bolin Chen, Shanzhi Yin, Ru-Ling Liao, Yibo Fan, Yan Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29041v1.pdf)  
  Keywords: efficient, 3d gaussian, gaussian splatting, compression, ar, mapping  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, slam, ar, face, fast, semantic  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, slam, outdoor, ar, face, tracking, geometry  
- **[BayesianGS-SLAM: Uncertainty-Aware Neural Rendering SLAM via Probabilistic Formulation](https://arxiv.org/abs/2609.24140v1)**  
  Authors: Kyeongsu Kang, Seongbo Ha, Sibaek Lee, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24140v1.pdf)  
  Keywords: neural rendering, 3d gaussian, gaussian splatting, slam, ar, mapping, tracking  
- **[Elevator-VIGS: Separating Elevator Motion from Robot Motion in Visual-Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2609.23491v1)**  
  Authors: Rui Zhou, Zihan Zhu, Wei Zhang, Zizhou Luo, Norbert Haala, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ruizhou-cn.github.io/elevator-vigs/.)  
  Keywords: motion, 3d gaussian, gaussian splatting, slam, ar, mapping, tracking  
- **[VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction](https://arxiv.org/abs/2609.23049v1)**  
  Authors: Haolin Yu, Jiadong Tang, YiXian Wang, Yu Gao, Shi He, Zhilin Lai, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23049v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, face, mapping, autonomous driving  

### Scene Understanding

*Showing the latest 50 out of 208 papers*

- **[Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction](https://arxiv.org/abs/2609.39960v1)**  
  Authors: Ziren Gong, Guo Chen, Yongjia Li, Yihua Shao, Fabio Tosi, Stefano Mattoccia, Matteo Poggi, Hao Tang, Fei Ma, Shuyan Li, Ziyang Yan, Nicu Sebe, Ling Shao, Jianfei Cai, Qi Tian, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39960v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, ar, dynamic, nerf, 4d, understanding, geometry  
- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: human, 3d gaussian, gaussian splatting, ar, understanding, compact, geometry, body  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, understanding, segmentation, localization, compact  
- **[GraphWrit3R: End-to-End 3D Scene Graph Writing](https://arxiv.org/abs/2609.31595v1)**  
  Authors: Luka Milivojevic, Nikola Popovic, Sayan Deb Sarkar, Sebastian Koch, Iro Armeni, Luc Van Gool, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31595v1.pdf)  
  Keywords: ar, semantic  
- **[PlenoCI: Plenoptic CharacterIstics for View Dependence Aware Change Classification](https://arxiv.org/abs/2609.28930v1)**  
  Authors: Jason Lai, Chamuditha Jayanga Galappaththige, Niko Suenderhauf, Dimity Miller, Donald G. Dansereau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://js0n-lai.github.io/plenoci.)  
  Keywords: efficient, 3d gaussian, gaussian splatting, ar, understanding  
- **[PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2609.28645v1)**  
  Authors: Sungjae Choi, Seunghee Koh, Junmo Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28645v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, lighting, ar, nerf, segmentation, geometry, semantic  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, slam, ar, face, fast, semantic  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: neural rendering, gaussian splatting, ar, face, 3d reconstruction, semantic  
- **[CoRef-GS: Cooperative Referring Gaussian Splatting for Multi-Agent Scene Understanding](https://arxiv.org/abs/2609.20586v1)**  
  Authors: Zhikun Zhou, Kunyu Peng, Runyi Yang, Junhao Cai, Di Wen, Ruiping Liu, Danda Pani Paudel, Yi Zhou, Luc Van Gool, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20586v1.pdf)  
  Keywords: ar, semantic, understanding, gaussian splatting  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: efficient, relightable, gaussian splatting, lighting, ar, geometry, semantic, illumination  



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