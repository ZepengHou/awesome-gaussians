# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-10-09 03:40:11

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
- [Acceleration](#acceleration) (192 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (327 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (360 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (82 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (412 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (45 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (403 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (202 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (21 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (109 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (161 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (207 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[GS-Pool: Object-Level Change Detection in 3D Gaussian Splatting](https://arxiv.org/abs/2610.06688v1)**  
  Authors: Boaz Keren-Gil, James Gain, Patrick Marais  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06688v1.pdf)  
  Keywords: 3d gaussian, geometry, ar, gaussian splatting, survey  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: 3d gaussian, high-fidelity, face, ar, gaussian splatting, survey  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: 3d gaussian, compression, ar, gaussian splatting, survey  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: geometry, illumination, motion, survey, ar, gaussian splatting, 3d reconstruction  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: 3d gaussian, nerf, geometry, survey, ar, gaussian splatting, 3d reconstruction, dynamic  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, 4d, medical, neural rendering, motion, vr, survey, recognition, ar, gaussian splatting, 3d reconstruction, compact  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: mapping, geometry, animation, ar, gaussian splatting, survey  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d gaussian, geometry, efficient, slam, tracking, motion, survey, ar, gaussian splatting, 3d reconstruction  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, vr, ar, gaussian splatting, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v8)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v8.pdf)  
  Keywords: 3d gaussian, mapping, ray tracing, ar, gaussian splatting, survey  

### Acceleration

*Showing the latest 50 out of 192 papers*

- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[LoCoSplat: Real-Time Feed-Forward 3D Gaussian Splatting with Minimal 3D Reasoning](https://arxiv.org/abs/2610.04351v1)**  
  Authors: Sinan Wang, Jinjin He, Yuchen Sun, Duowen Chen, Shenyifan Lu, Bo Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04351v1.pdf)  
  Keywords: 3d gaussian, fast, ar, gaussian splatting, dynamic  
- **[Budgeted-GS: Real-Time Large-Scale Gaussian Splatting via Factoring LOD](https://arxiv.org/abs/2610.03162v1)**  
  Authors: Haipeng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.03162v1.pdf)  
  Keywords: 3d gaussian, high quality, ar, gaussian splatting, real-time rendering  
- **[FactorSplat: Appearance-Controllable Gaussian Proxies for Medical Volume Rendering](https://arxiv.org/abs/2610.02382v1)**  
  Authors: Zhongpai Gao, Benjamin Planche, Meng Zheng, Anwesa Choudhuri, Terrence Chen, Ziyan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.02382v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gaozhongpai.github.io/FactorSplat/.)  
  Keywords: medical, geometry, fast, ar, gaussian splatting  
- **[Affine-Aligned Atlas for Canonical Gaussian Construction in Video Representation](https://arxiv.org/abs/2610.01114v1)**  
  Authors: Masaya Takabe, Hiroshi Watanabe, Sujun Hong, Tomohiro Ikai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01114v1.pdf)  
  Keywords: deformation, efficient, motion, fast, ar, gaussian splatting  
- **[Dirichlet Splatting: Differentiable Rendering for Wave-Based Inverse Problems](https://arxiv.org/abs/2610.00618v1)**  
  Authors: Xingyu Chen, Wuqiong Zhao, Xinyu Zhang, Tzu-Mao Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.00618v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, fast  
- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: 3d gaussian, acceleration, high-fidelity, efficient, ar, gaussian splatting, compact  
- **[RLX: A Unified Multi-Backend Tensor Compiler and Distributed Runtime in Rust](https://arxiv.org/abs/2609.37916v1)**  
  Authors: Eugene Hauptmann, Nataliya Kosmyna  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37916v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, fast  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, nerf, geometry, illumination, ar, gaussian splatting, real-time rendering, dynamic  
- **[WINGS: Reference-Free Gaussian Splatting Inpainting with 3D-Native Generative Priors](https://arxiv.org/abs/2609.37816v1)**  
  Authors: Noé Lallouet, Michael Fischer, Elie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37816v1.pdf)  
  Keywords: 3d gaussian, geometry, fast, ar, gaussian splatting  

### Applications

*Showing the latest 50 out of 996 papers*

- **[OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs](https://arxiv.org/abs/2610.12461v1)**  
  Authors: You-Zhe Xie, Ting-Wei Chou, Yu-Hsuan Li, Kaipeng Zhang, Zhixiang Wang, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12461v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ouroworld.userwei.com)  
  Keywords: 3d gaussian, 4d, deformation, illumination, motion, ar, gaussian splatting, dynamic  
- **[LVS: Local View Synthesis from Relative Camera Pose by Reusing Previous Views](https://arxiv.org/abs/2610.12127v1)**  
  Authors: Qizhou Huo, Xuan Sun, Yongfei Guo, Zhipeng Wang, Yuanhao Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12127v1.pdf)  
  Keywords: 3d gaussian, motion, lightweight, ar, gaussian splatting  
- **[2DGS-Planner: Rasterization-based Path Planning in 2D Gaussian Splatting Map](https://arxiv.org/abs/2610.11752v1)**  
  Authors: Jiwon Park, Dong-Uk Seo, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11752v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://2dgs-planner.github.io/)  
  Keywords: geometry, efficient, face, ar, gaussian splatting  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[OX-NeRF: 3D X-ray Tomography Reconstruction from Sparse Views Using Implicit Neural Representation](https://arxiv.org/abs/2610.11547v1)**  
  Authors: Thomas Welsch, Min-Hsin Tu, David J. Chapman, Daniel E. Eakins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11547v1.pdf)  
  Keywords: nerf, sparse view, ar, gaussian splatting, 3d reconstruction  
- **[FlyMark: Training-Free Invisible Watermarking of 3D Gaussian Splatting via a Fruit Fly Connectome](https://arxiv.org/abs/2610.11364v1)**  
  Authors: Ziyuan Luo, Haoliang Li, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11364v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, geometry  
- **[Rendering-Free Lookahead for Question-Guided Active Vision](https://arxiv.org/abs/2610.11039v1)**  
  Authors: Koya Sakamoto, Daichi Azuma, Shuhei Kurita, Naoya Chiba, Yusuke Iwasawa, Yutaka Matsuo, Taiki Miyanishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11039v1.pdf)  
  Keywords: 3d gaussian, head, motion, ar, gaussian splatting  
- **[PCAsplat: Gaussian Splatting with Local PCA Regularization](https://arxiv.org/abs/2610.11011v1)**  
  Authors: Vitor Matias, Filipe Nascimento, Kiyohiro Nakayama, João Paulo Lima, Márcus Lobo, Gordon Wetzstein, Leonidas Guibas, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11011v1.pdf)  
  Keywords: nerf, geometry, segmentation, face, ar, gaussian splatting, 3d reconstruction  
- **[Gaussian Density Splatting Network](https://arxiv.org/abs/2610.10396v2)**  
  Authors: Miao Shang, Yabin Wang, Xiaopeng Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.10396v2.pdf)  
  Keywords: ar, gaussian splatting  
- **[DeltaSplat: Iterative Gaussian Refinement for Pose-Free Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2610.09853v1)**  
  Authors: Chanung Park, Seunghyeon Song, Joo Chan Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.09853v1.pdf)  
  Keywords: 3d gaussian, efficient, head, lightweight, ar, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 327 papers*

- **[2DGS-Planner: Rasterization-based Path Planning in 2D Gaussian Splatting Map](https://arxiv.org/abs/2610.11752v1)**  
  Authors: Jiwon Park, Dong-Uk Seo, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11752v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://2dgs-planner.github.io/)  
  Keywords: geometry, efficient, face, ar, gaussian splatting  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[Rendering-Free Lookahead for Question-Guided Active Vision](https://arxiv.org/abs/2610.11039v1)**  
  Authors: Koya Sakamoto, Daichi Azuma, Shuhei Kurita, Naoya Chiba, Yusuke Iwasawa, Yutaka Matsuo, Taiki Miyanishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11039v1.pdf)  
  Keywords: 3d gaussian, head, motion, ar, gaussian splatting  
- **[PCAsplat: Gaussian Splatting with Local PCA Regularization](https://arxiv.org/abs/2610.11011v1)**  
  Authors: Vitor Matias, Filipe Nascimento, Kiyohiro Nakayama, João Paulo Lima, Márcus Lobo, Gordon Wetzstein, Leonidas Guibas, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11011v1.pdf)  
  Keywords: nerf, geometry, segmentation, face, ar, gaussian splatting, 3d reconstruction  
- **[DeltaSplat: Iterative Gaussian Refinement for Pose-Free Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2610.09853v1)**  
  Authors: Chanung Park, Seunghyeon Song, Joo Chan Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.09853v1.pdf)  
  Keywords: 3d gaussian, efficient, head, lightweight, ar, gaussian splatting  
- **[DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given](https://arxiv.org/abs/2610.07958v1)**  
  Authors: Minhyeok Lee, Jungho Lee, Minseok Kang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07958v1.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, head, ar, gaussian splatting, compact  
- **[MoonGS: High-quality Representation of the Lunar Surface via Gaussian Splatting Using Robust Depth Features from Image Pairs](https://arxiv.org/abs/2610.07110v1)**  
  Authors: Yun Jiang, Bo Zheng, Yingying Zhang, Xueming Xiao, Tao Hu, Hutao Cui, Zhiguo Meng, Ke Gao, Yang Gao, Meibao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07110v1.pdf)  
  Keywords: 3d gaussian, nerf, semantic, face, head, ar, gaussian splatting, 3d reconstruction  
- **[MaRO-GS: Mask-Robust Object-Centric Gaussian Splatting from Inconsistent Multi-view Masks](https://arxiv.org/abs/2610.06472v1)**  
  Authors: Eunji Kim, Gahyeon Kim, Gianella Cravioto, Dong-hun Lee, Chaewon Moon, Chae-yeong Song, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06472v1.pdf)  
  Keywords: head, gaussian splatting, ar, segmentation  
- **[Controllable and Photorealistic Pedestrian Risky Motion Generation for End-to-End Driving Safety Evaluation](https://arxiv.org/abs/2610.06171v1)**  
  Authors: Siyuan Liu, Miao Li, Haibao Yu, Haohong Lin, Qing Zhou, Bingbing Nie, Ding Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06171v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, human, motion, avatar, ar, gaussian splatting  
- **[Mobile-4DGS: Unified Static-Dynamic Real-time Mobile Gaussian Splatting](https://arxiv.org/abs/2610.05289v1)**  
  Authors: Xiaobiao Du, Beixi Hao, Zhen Fang, Tianqing Zhu, Richard Hartley, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05289v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/mobile-4dgs-project/}{Code)  
  Keywords: 3d gaussian, 4d, deformation, high-fidelity, compact, head, motion, lightweight, ar, gaussian splatting, dynamic  

### Dynamic Scene

*Showing the latest 50 out of 360 papers*

- **[OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs](https://arxiv.org/abs/2610.12461v1)**  
  Authors: You-Zhe Xie, Ting-Wei Chou, Yu-Hsuan Li, Kaipeng Zhang, Zhixiang Wang, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12461v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ouroworld.userwei.com)  
  Keywords: 3d gaussian, 4d, deformation, illumination, motion, ar, gaussian splatting, dynamic  
- **[LVS: Local View Synthesis from Relative Camera Pose by Reusing Previous Views](https://arxiv.org/abs/2610.12127v1)**  
  Authors: Qizhou Huo, Xuan Sun, Yongfei Guo, Zhipeng Wang, Yuanhao Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12127v1.pdf)  
  Keywords: 3d gaussian, motion, lightweight, ar, gaussian splatting  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[Rendering-Free Lookahead for Question-Guided Active Vision](https://arxiv.org/abs/2610.11039v1)**  
  Authors: Koya Sakamoto, Daichi Azuma, Shuhei Kurita, Naoya Chiba, Yusuke Iwasawa, Yutaka Matsuo, Taiki Miyanishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11039v1.pdf)  
  Keywords: 3d gaussian, head, motion, ar, gaussian splatting  
- **[Controllable and Photorealistic Pedestrian Risky Motion Generation for End-to-End Driving Safety Evaluation](https://arxiv.org/abs/2610.06171v1)**  
  Authors: Siyuan Liu, Miao Li, Haibao Yu, Haohong Lin, Qing Zhou, Bingbing Nie, Ding Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06171v1.pdf)  
  Keywords: autonomous driving, 3d gaussian, human, motion, avatar, ar, gaussian splatting  
- **[Mobile-4DGS: Unified Static-Dynamic Real-time Mobile Gaussian Splatting](https://arxiv.org/abs/2610.05289v1)**  
  Authors: Xiaobiao Du, Beixi Hao, Zhen Fang, Tianqing Zhu, Richard Hartley, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05289v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/mobile-4dgs-project/}{Code)  
  Keywords: 3d gaussian, 4d, deformation, high-fidelity, compact, head, motion, lightweight, ar, gaussian splatting, dynamic  
- **[Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative Assistance](https://arxiv.org/abs/2610.04606v2)**  
  Authors: Shengqi Wang, Zhengxian Yang, Kaiwen Tian, Yang Liu, Bowen Liu, Hua Du, Taicheng Huang, Jiamin Wu, Tao Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04606v2.pdf)  
  Keywords: 4d, geometry, sparse-view, motion, sparse view, ar, gaussian splatting, dynamic  
- **[LoCoSplat: Real-Time Feed-Forward 3D Gaussian Splatting with Minimal 3D Reasoning](https://arxiv.org/abs/2610.04351v1)**  
  Authors: Sinan Wang, Jinjin He, Yuchen Sun, Duowen Chen, Shenyifan Lu, Bo Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04351v1.pdf)  
  Keywords: 3d gaussian, fast, ar, gaussian splatting, dynamic  
- **[A differentiable Lagrangian-coupled 3D Gaussian Splatting-SPH model for forward simulation and inverse analysis in solid mechanics](https://arxiv.org/abs/2610.04336v1)**  
  Authors: Tian Xu, Soroush Atashi, Tianju Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04336v1.pdf)  
  Keywords: 3d gaussian, deformation, geometry, animation, face, ar, gaussian splatting, dynamic  
- **[ManifoldSplat: Language-Guided Semantic Shape Editing of 3D Gaussian Head Avatars](https://arxiv.org/abs/2610.03599v1)**  
  Authors: Antonio Canela, Jordi Sànchez-Riera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.03599v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://a-canela.github.io/manifoldsplat/)  
  Keywords: 3d gaussian, high-fidelity, geometry, semantic, animation, head, avatar, ar, gaussian splatting  

### Few-shot

*Showing the latest 50 out of 82 papers*

- **[OX-NeRF: 3D X-ray Tomography Reconstruction from Sparse Views Using Implicit Neural Representation](https://arxiv.org/abs/2610.11547v1)**  
  Authors: Thomas Welsch, Min-Hsin Tu, David J. Chapman, Daniel E. Eakins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11547v1.pdf)  
  Keywords: nerf, sparse view, ar, gaussian splatting, 3d reconstruction  
- **[DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given](https://arxiv.org/abs/2610.07958v1)**  
  Authors: Minhyeok Lee, Jungho Lee, Minseok Kang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07958v1.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, head, ar, gaussian splatting, compact  
- **[Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative Assistance](https://arxiv.org/abs/2610.04606v2)**  
  Authors: Shengqi Wang, Zhengxian Yang, Kaiwen Tian, Yang Liu, Bowen Liu, Hua Du, Taicheng Huang, Jiamin Wu, Tao Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04606v2.pdf)  
  Keywords: 4d, geometry, sparse-view, motion, sparse view, ar, gaussian splatting, dynamic  
- **[Sparse-GS2Mesh: 3D Gaussian Splatting Guided by Novel Stereo Views and 2DGS for Sparse View Surface Reconstruction](https://arxiv.org/abs/2610.04203v2)**  
  Authors: Younghyun Noh, Minje Kim, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04203v2.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, efficient, face, sparse view, ar, gaussian splatting  
- **[UGOD: Uncertainty-Guided Opacity and Dropout for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.39089v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Chenghao Qian, Ziyang Wang, Xinqi Fan, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39089v1.pdf)  
  Keywords: 3d gaussian, nerf, sparse-view, head, lightweight, ar, gaussian splatting, compact  
- **[Remote Sensing Sparse-View 3D Gaussian Splatting via Depth Image-Based Rendering](https://arxiv.org/abs/2609.35612v1)**  
  Authors: Jiaming Kang, Zhengxia Zou, Zhenwei Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35612v1.pdf)  
  Keywords: 3d gaussian, nerf, sparse-view, face, ar, gaussian splatting  
- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v2)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v2.pdf)  
  Keywords: 3d gaussian, nerf, geometry, sparse-view, ar, gaussian splatting, real-time rendering  
- **[D3GS: Depth, DINO, and RGB Diffusion Co-Guided 3D Gaussian Splatting for Sparse-View Reconstruction](https://arxiv.org/abs/2609.22941v1)**  
  Authors: Yunqi Gao, Zhanfeng Liao, Hanzhang Tu, Zhaoqi Su, Guoqing Zheng, Songtao Wang, Hongwen Zhang, Zhou Xue, Leyuan Liu, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22941v1.pdf)  
  Keywords: 3d gaussian, nerf, geometry, sparse-view, ar, gaussian splatting  
- **[LINGO: Latent Initialization and Gradient Optimization for Sparse-view X-ray Novel View Synthesis and CT Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2609.22849v1)**  
  Authors: Lifeng Xing, Dequan Jin, Kunpeng Bu, Peigeng He, Shihui Ying  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22849v1.pdf)  
  Keywords: 3d gaussian, sparse-view, ar, gaussian splatting, dynamic  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: 4d, sparse-view, large scene, ar, gaussian splatting, dynamic  

### Geometry Reconstruction

*Showing the latest 50 out of 412 papers*

- **[2DGS-Planner: Rasterization-based Path Planning in 2D Gaussian Splatting Map](https://arxiv.org/abs/2610.11752v1)**  
  Authors: Jiwon Park, Dong-Uk Seo, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11752v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://2dgs-planner.github.io/)  
  Keywords: geometry, efficient, face, ar, gaussian splatting  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[OX-NeRF: 3D X-ray Tomography Reconstruction from Sparse Views Using Implicit Neural Representation](https://arxiv.org/abs/2610.11547v1)**  
  Authors: Thomas Welsch, Min-Hsin Tu, David J. Chapman, Daniel E. Eakins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11547v1.pdf)  
  Keywords: nerf, sparse view, ar, gaussian splatting, 3d reconstruction  
- **[FlyMark: Training-Free Invisible Watermarking of 3D Gaussian Splatting via a Fruit Fly Connectome](https://arxiv.org/abs/2610.11364v1)**  
  Authors: Ziyuan Luo, Haoliang Li, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11364v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, geometry  
- **[PCAsplat: Gaussian Splatting with Local PCA Regularization](https://arxiv.org/abs/2610.11011v1)**  
  Authors: Vitor Matias, Filipe Nascimento, Kiyohiro Nakayama, João Paulo Lima, Márcus Lobo, Gordon Wetzstein, Leonidas Guibas, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11011v1.pdf)  
  Keywords: nerf, geometry, segmentation, face, ar, gaussian splatting, 3d reconstruction  
- **[DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given](https://arxiv.org/abs/2610.07958v1)**  
  Authors: Minhyeok Lee, Jungho Lee, Minseok Kang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07958v1.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, head, ar, gaussian splatting, compact  
- **[OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception](https://arxiv.org/abs/2610.07569v1)**  
  Authors: Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07569v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://csiro-robotics.github.io/OpenSplatGraph.)  
  Keywords: 3d gaussian, understanding, mapping, high-fidelity, geometry, efficient, semantic, robotics, lightweight, ar, gaussian splatting  
- **[SURGE: Sonar-fUsed Reconstruction and localization via image-gated Graph Estimation](https://arxiv.org/abs/2610.07472v1)**  
  Authors: Mohammed Ibrahim M, Vallabh Deogaonkar, Trung Dong, Jane Shin, Abhilash Somayajula, Xiaomin Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07472v1.pdf)  
  Keywords: understanding, geometry, localization, ar, gaussian splatting, compact  
- **[GS-Pool: Object-Level Change Detection in 3D Gaussian Splatting](https://arxiv.org/abs/2610.06688v1)**  
  Authors: Boaz Keren-Gil, James Gain, Patrick Marais  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06688v1.pdf)  
  Keywords: 3d gaussian, geometry, ar, gaussian splatting, survey  
- **[MoonGS: High-quality Representation of the Lunar Surface via Gaussian Splatting Using Robust Depth Features from Image Pairs](https://arxiv.org/abs/2610.07110v1)**  
  Authors: Yun Jiang, Bo Zheng, Yingying Zhang, Xueming Xiao, Tao Hu, Hutao Cui, Zhiguo Meng, Ke Gao, Yang Gao, Meibao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07110v1.pdf)  
  Keywords: 3d gaussian, nerf, semantic, face, head, ar, gaussian splatting, 3d reconstruction  

### Large Scene

- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: 3d gaussian, efficient, lightweight, face, large scene, ar, gaussian splatting  
- **[ChronoFuseGS: Multi-Temporal Gaussian Fusion with Per-Splat Persistence and Change Visualization](https://arxiv.org/abs/2609.31339v1)**  
  Authors: Tobias Batik, Diana Marin, Peter Kán, Hannes Kaufmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.31339v1.pdf)  
  Keywords: ar, gaussian splatting, outdoor  
- **[OceanXL: Large-scale Underwater 3D Gaussian Splatting via Block Partitioning and Adaptive Pruning](https://arxiv.org/abs/2609.29985v1)**  
  Authors: Haoran Wang, Shaoyu Cai, Adrian Azzarelli, Zhuodong Jiang, Guoxi Huang, Eng Tat Khoo, Brett Seymour, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29985v1.pdf)  
  Keywords: 3d gaussian, nerf, efficient, fast, large scene, ar, gaussian splatting, real-time rendering, 3d reconstruction, compact  
- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: 3d gaussian, motion, ar, gaussian splatting, outdoor  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: 3d gaussian, geometry, face, tracking, ar, gaussian splatting, outdoor, slam  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: 3d gaussian, mapping, high-fidelity, face, tracking, ar, gaussian splatting, outdoor, slam  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v3)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v3.pdf)  
  Keywords: 4d, sparse-view, large scene, ar, gaussian splatting, dynamic  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: 3d gaussian, motion, ar, gaussian splatting, outdoor  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: 4d, human, illumination, fast, ar, gaussian splatting, outdoor, dynamic  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: 3d gaussian, nerf, head, ar, gaussian splatting, outdoor, compact  

### Model Compression

*Showing the latest 50 out of 403 papers*

- **[LVS: Local View Synthesis from Relative Camera Pose by Reusing Previous Views](https://arxiv.org/abs/2610.12127v1)**  
  Authors: Qizhou Huo, Xuan Sun, Yongfei Guo, Zhipeng Wang, Yuanhao Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12127v1.pdf)  
  Keywords: 3d gaussian, motion, lightweight, ar, gaussian splatting  
- **[2DGS-Planner: Rasterization-based Path Planning in 2D Gaussian Splatting Map](https://arxiv.org/abs/2610.11752v1)**  
  Authors: Jiwon Park, Dong-Uk Seo, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11752v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://2dgs-planner.github.io/)  
  Keywords: geometry, efficient, face, ar, gaussian splatting  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[DeltaSplat: Iterative Gaussian Refinement for Pose-Free Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2610.09853v1)**  
  Authors: Chanung Park, Seunghyeon Song, Joo Chan Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.09853v1.pdf)  
  Keywords: 3d gaussian, efficient, head, lightweight, ar, gaussian splatting  
- **[DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given](https://arxiv.org/abs/2610.07958v1)**  
  Authors: Minhyeok Lee, Jungho Lee, Minseok Kang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07958v1.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, head, ar, gaussian splatting, compact  
- **[Efficient Gaussian Splatting Sequence Compression with Standard Video Codecs](https://arxiv.org/abs/2610.07795v1)**  
  Authors: Qi Yang, Shuting Xia, Le Yang, Geert Van Der Auwera, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07795v1.pdf)  
  Keywords: ar, gaussian splatting, efficient, compression  
- **[OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception](https://arxiv.org/abs/2610.07569v1)**  
  Authors: Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07569v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://csiro-robotics.github.io/OpenSplatGraph.)  
  Keywords: 3d gaussian, understanding, mapping, high-fidelity, geometry, efficient, semantic, robotics, lightweight, ar, gaussian splatting  
- **[SURGE: Sonar-fUsed Reconstruction and localization via image-gated Graph Estimation](https://arxiv.org/abs/2610.07472v1)**  
  Authors: Mohammed Ibrahim M, Vallabh Deogaonkar, Trung Dong, Jane Shin, Abhilash Somayajula, Xiaomin Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07472v1.pdf)  
  Keywords: understanding, geometry, localization, ar, gaussian splatting, compact  
- **[SteadySplats: Resampling of Low-Variance Gaussians for High-Fidelity Stochastic Rendering](https://arxiv.org/abs/2610.05576v2)**  
  Authors: Felix Windisch, Thomas Köhler, Lukas Radl, Chris Wyman, Georgios Kopanas, Bernhard Kerbl, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05576v2.pdf)  
  Keywords: 3d gaussian, high-fidelity, efficient, ar, gaussian splatting  
- **[Mobile-4DGS: Unified Static-Dynamic Real-time Mobile Gaussian Splatting](https://arxiv.org/abs/2610.05289v1)**  
  Authors: Xiaobiao Du, Beixi Hao, Zhen Fang, Tianqing Zhu, Richard Hartley, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05289v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/mobile-4dgs-project/}{Code)  
  Keywords: 3d gaussian, 4d, deformation, high-fidelity, compact, head, motion, lightweight, ar, gaussian splatting, dynamic  

### Quality Enhancement

*Showing the latest 50 out of 202 papers*

- **[OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception](https://arxiv.org/abs/2610.07569v1)**  
  Authors: Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07569v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://csiro-robotics.github.io/OpenSplatGraph.)  
  Keywords: 3d gaussian, understanding, mapping, high-fidelity, geometry, efficient, semantic, robotics, lightweight, ar, gaussian splatting  
- **[SteadySplats: Resampling of Low-Variance Gaussians for High-Fidelity Stochastic Rendering](https://arxiv.org/abs/2610.05576v2)**  
  Authors: Felix Windisch, Thomas Köhler, Lukas Radl, Chris Wyman, Georgios Kopanas, Bernhard Kerbl, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05576v2.pdf)  
  Keywords: 3d gaussian, high-fidelity, efficient, ar, gaussian splatting  
- **[Mobile-4DGS: Unified Static-Dynamic Real-time Mobile Gaussian Splatting](https://arxiv.org/abs/2610.05289v1)**  
  Authors: Xiaobiao Du, Beixi Hao, Zhen Fang, Tianqing Zhu, Richard Hartley, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.05289v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/mobile-4dgs-project/}{Code)  
  Keywords: 3d gaussian, 4d, deformation, high-fidelity, compact, head, motion, lightweight, ar, gaussian splatting, dynamic  
- **[Return-to-Home Feasible Micro-Aerial Vehicle Exploration for 3D Gaussian Splatting Reconstruction](https://arxiv.org/abs/2610.04013v1)**  
  Authors: Prajit Krisshnakumar, Fan Yang, Koichiro Niinuma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04013v1.pdf)  
  Keywords: 3d gaussian, geometry, high-fidelity, head, lightweight, ar, gaussian splatting, 3d reconstruction  
- **[ManifoldSplat: Language-Guided Semantic Shape Editing of 3D Gaussian Head Avatars](https://arxiv.org/abs/2610.03599v1)**  
  Authors: Antonio Canela, Jordi Sànchez-Riera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.03599v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://a-canela.github.io/manifoldsplat/)  
  Keywords: 3d gaussian, high-fidelity, geometry, semantic, animation, head, avatar, ar, gaussian splatting  
- **[Budgeted-GS: Real-Time Large-Scale Gaussian Splatting via Factoring LOD](https://arxiv.org/abs/2610.03162v1)**  
  Authors: Haipeng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.03162v1.pdf)  
  Keywords: 3d gaussian, high quality, ar, gaussian splatting, real-time rendering  
- **[SCION: Scene Composition with Instanced Neural Primitives](https://arxiv.org/abs/2610.02322v2)**  
  Authors: William Koch, Amogh Joshi, Cyrus Vachha, Cheng Zheng, Felix Heide  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.02322v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://light.princeton.edu/SCION)  
  Keywords: 3d gaussian, compression, animation, human, high quality, lightweight, ar, gaussian splatting, compact  
- **[EffGS: Efficient and High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2609.39553v1)**  
  Authors: Changbai Li, Shuo Yang, Yichen Yang, Shuwei Shao, Huobin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39553v1.pdf)  
  Keywords: 3d gaussian, acceleration, high-fidelity, efficient, ar, gaussian splatting, compact  
- **[Gaussian Stippling: Efficient Sorting-Free 3D Gaussian Rendering through Hybrid Sampling and Spatiotemporal Reconstruction](https://arxiv.org/abs/2609.38488v1)**  
  Authors: Zijian Huang, Suiliang Mai, Chuankun Zheng, Yuan Meng, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38488v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, efficient, lightweight, ar, gaussian splatting  
- **[Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation](https://arxiv.org/abs/2609.33872v1)**  
  Authors: Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang, Daqiang Guo, Peng Zhou, Lihui Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.33872v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://robot-gst.github.io)  
  Keywords: 3d gaussian, high-fidelity, geometry, ar, gaussian splatting  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: 3d gaussian, nerf, ray tracing, face, motion, fast, ar, gaussian splatting, real-time rendering, compact  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: 3d gaussian, nerf, shadow, mapping, ray tracing, efficient, fast, ar, gaussian splatting, reflection, compact  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: ray tracing, relighting, efficient, illumination, lighting, face, ar, gaussian splatting, reflection  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: 3d gaussian, ray tracing, high-fidelity, geometry, human, face, motion, ar, gaussian splatting, reflection, dynamic  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, ray tracing, fast, ar, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: 3d gaussian, path tracing, ray tracing, geometry, efficient, fast, reflection, ar, gaussian splatting, real-time rendering  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d gaussian, geometry, efficient, illumination, global illumination, ar, gaussian splatting, 3d reconstruction  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, illumination, global illumination, ar, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: 3d gaussian, ray tracing, geometry, segmentation, efficient, semantic, ar, gaussian splatting, reflection  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, shadow, illumination, face, global illumination, fast, ar, gaussian splatting  

### Relighting

*Showing the latest 50 out of 109 papers*

- **[OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs](https://arxiv.org/abs/2610.12461v1)**  
  Authors: You-Zhe Xie, Ting-Wei Chou, Yu-Hsuan Li, Kaipeng Zhang, Zhixiang Wang, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.12461v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ouroworld.userwei.com)  
  Keywords: 3d gaussian, 4d, deformation, illumination, motion, ar, gaussian splatting, dynamic  
- **[PAM-ToD: Plug-and-Play Appearance Modeling for Cross-Time-of-Day 3D Gaussian Splatting](https://arxiv.org/abs/2610.11572v1)**  
  Authors: Kota Shimomura, Sungho Moon, Tsubasa Hirakawa, Takayoshi Yamashita, Sunghoon Im, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11572v1.pdf)  
  Keywords: 3d gaussian, geometry, illumination, face, lightweight, ar, gaussian splatting, real-time rendering, dynamic  
- **[VolS-GS: Relightable Gaussian Splatting with Volumetric Subsurface Scattering](https://arxiv.org/abs/2610.04007v2)**  
  Authors: Junyeong Ahn, Jaegul Choo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04007v2.pdf)  
  Keywords: relightable, shadow, relighting, efficient, face, lighting, ar, gaussian splatting  
- **[EvenSplat: Coupled 2D-3D Decomposition for Gaussian Splatting under Exposure and Illumination Variation](https://arxiv.org/abs/2610.01876v1)**  
  Authors: Tongyu Wu, Jacob Edwards, Ziteng Cui, Caigui Jiang, Cheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.01876v1.pdf)  
  Keywords: 3d gaussian, shadow, geometry, illumination, lighting, face, ar, gaussian splatting  
- **[EndoPrior-GS: Dynamic Endoscopic Reconstruction with a Joint Texture Prior](https://arxiv.org/abs/2609.37874v1)**  
  Authors: Jiaqi Huang, Shidong Wang, Tong Xin, Kabita Adhikari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.37874v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiaqi-huang-77.github.io/EndoPrior-GS/.)  
  Keywords: 3d gaussian, nerf, geometry, illumination, ar, gaussian splatting, real-time rendering, dynamic  
- **[CollisionSplatting: Collision-Aware Motion Planning in 3DGS Scenes with Image-Conditioned Objectives and Adjustable Conservatism](https://arxiv.org/abs/2609.35619v1)**  
  Authors: R. Khorrambakht, Joaquim Ortiz-Haro, Stephan Weiss, Ludovic Righetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.35619v1.pdf)  
  Keywords: 3d gaussian, motion, lighting, vr, ar, gaussian splatting  
- **[PePESeg3D: Perception Prior Enhances Multi-Scale Segmentation for 3D Gaussian Splatting](https://arxiv.org/abs/2609.28645v1)**  
  Authors: Sungjae Choi, Seunghee Koh, Junmo Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.28645v1.pdf)  
  Keywords: 3d gaussian, nerf, geometry, segmentation, semantic, lighting, ar, gaussian splatting  
- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: shadow, mapping, illumination, lighting, motion, tracking, ar, gaussian splatting, slam, dynamic  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: relightable, geometry, efficient, semantic, illumination, lighting, ar, gaussian splatting  
- **[RGS: Reflection-aware Gaussian Splatting via Learning Geometry Continuity for Reflective Objects](https://arxiv.org/abs/2609.19421v1)**  
  Authors: Xiaobiao Du, Yida Wang, Cheng Bi, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19421v1.pdf)  
  Keywords: 3d gaussian, geometry, face, ar, gaussian splatting, reflection  

### SLAM

*Showing the latest 50 out of 161 papers*

- **[OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception](https://arxiv.org/abs/2610.07569v1)**  
  Authors: Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07569v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://csiro-robotics.github.io/OpenSplatGraph.)  
  Keywords: 3d gaussian, understanding, mapping, high-fidelity, geometry, efficient, semantic, robotics, lightweight, ar, gaussian splatting  
- **[SURGE: Sonar-fUsed Reconstruction and localization via image-gated Graph Estimation](https://arxiv.org/abs/2610.07472v1)**  
  Authors: Mohammed Ibrahim M, Vallabh Deogaonkar, Trung Dong, Jane Shin, Abhilash Somayajula, Xiaomin Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07472v1.pdf)  
  Keywords: understanding, geometry, localization, ar, gaussian splatting, compact  
- **[Lens Flare Removal and Reconstruction](https://arxiv.org/abs/2609.39527v1)**  
  Authors: Tarun Yenamandra, Jonathon Luiten, Daniel Cremers, Nathan Matsuda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39527v1.pdf)  
  Keywords: ar, gaussian splatting, localization  
- **[DispFlow-GS: Displacement Flow Supervision with Motion Disentangling for Monocular Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2609.36940v1)**  
  Authors: Thai Duy Nguyen, Haitian Zhang, Addison Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.36940v1.pdf)  
  Keywords: 3d gaussian, deformation, geometry, motion, localization, ar, gaussian splatting, dynamic  
- **[EviSplat: Preserving Multi-View Evidence in 3D Gaussian Splatting for Open-Vocabulary Segmentation](https://arxiv.org/abs/2609.34853v1)**  
  Authors: Sungho Moon, Kota Shimomura, Junwoo Park, Wonhyeok Choi, Seunghun Lee, Takayoshi Yamashita, Sunghoon Im  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.34853v1.pdf)  
  Keywords: 3d gaussian, understanding, segmentation, localization, ar, gaussian splatting, compact  
- **[Reliability-Regulated Trajectory Optimization for Progressive COLMAP-Free 3D Gaussian Splatting](https://arxiv.org/abs/2609.30865v1)**  
  Authors: Zijian Wu, Jinliang Wang, Zidian Lin, Ying Song, Ziqian Lu, Hanjie Ma, Zhen Ye, Mingfeng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.30865v1.pdf)  
  Keywords: 3d gaussian, tracking, motion, ar, gaussian splatting, dynamic  
- **[From Scattered Gaussians to Structured Maps: Efficient Gaussian Splatting Coding via Dual-phase Morton Sorting](https://arxiv.org/abs/2609.29041v1)**  
  Authors: Bolin Chen, Shanzhi Yin, Ru-Ling Liao, Yibo Fan, Yan Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.29041v1.pdf)  
  Keywords: 3d gaussian, mapping, efficient, compression, ar, gaussian splatting  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: 3d gaussian, semantic, face, fast, ar, gaussian splatting, slam  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: 3d gaussian, geometry, face, tracking, ar, gaussian splatting, outdoor, slam  
- **[BayesianGS-SLAM: Uncertainty-Aware Neural Rendering SLAM via Probabilistic Formulation](https://arxiv.org/abs/2609.24140v1)**  
  Authors: Kyeongsu Kang, Seongbo Ha, Sibaek Lee, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24140v1.pdf)  
  Keywords: 3d gaussian, neural rendering, mapping, tracking, ar, gaussian splatting, slam  

### Scene Understanding

*Showing the latest 50 out of 207 papers*

- **[PCAsplat: Gaussian Splatting with Local PCA Regularization](https://arxiv.org/abs/2610.11011v1)**  
  Authors: Vitor Matias, Filipe Nascimento, Kiyohiro Nakayama, João Paulo Lima, Márcus Lobo, Gordon Wetzstein, Leonidas Guibas, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11011v1.pdf)  
  Keywords: nerf, geometry, segmentation, face, ar, gaussian splatting, 3d reconstruction  
- **[Post-Training Semantic Lifting for 3D Gaussian Splatting: Separating Detector, Lifting and Representation Error](https://arxiv.org/abs/2610.08756v1)**  
  Authors: Iván Verdugo Guerra, Ezequiel López Rubio, Jorge García González  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.08756v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, semantic  
- **[OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception](https://arxiv.org/abs/2610.07569v1)**  
  Authors: Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07569v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://csiro-robotics.github.io/OpenSplatGraph.)  
  Keywords: 3d gaussian, understanding, mapping, high-fidelity, geometry, efficient, semantic, robotics, lightweight, ar, gaussian splatting  
- **[SURGE: Sonar-fUsed Reconstruction and localization via image-gated Graph Estimation](https://arxiv.org/abs/2610.07472v1)**  
  Authors: Mohammed Ibrahim M, Vallabh Deogaonkar, Trung Dong, Jane Shin, Abhilash Somayajula, Xiaomin Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07472v1.pdf)  
  Keywords: understanding, geometry, localization, ar, gaussian splatting, compact  
- **[MoonGS: High-quality Representation of the Lunar Surface via Gaussian Splatting Using Robust Depth Features from Image Pairs](https://arxiv.org/abs/2610.07110v1)**  
  Authors: Yun Jiang, Bo Zheng, Yingying Zhang, Xueming Xiao, Tao Hu, Hutao Cui, Zhiguo Meng, Ke Gao, Yang Gao, Meibao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07110v1.pdf)  
  Keywords: 3d gaussian, nerf, semantic, face, head, ar, gaussian splatting, 3d reconstruction  
- **[MaRO-GS: Mask-Robust Object-Centric Gaussian Splatting from Inconsistent Multi-view Masks](https://arxiv.org/abs/2610.06472v1)**  
  Authors: Eunji Kim, Gahyeon Kim, Gianella Cravioto, Dong-hun Lee, Chaewon Moon, Chae-yeong Song, Sang-hyo Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06472v1.pdf)  
  Keywords: head, gaussian splatting, ar, segmentation  
- **[GS-Codec: A Gaussian-Splatting Bottleneck for Neural Audio Coding](https://arxiv.org/abs/2610.04651v1)**  
  Authors: Ron Aluf, Alon Canfi, Eliya Nachmani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04651v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ronaluf.github.io/gs-codec/)  
  Keywords: semantic, lightweight, ar, gaussian splatting, compact  
- **[ManifoldSplat: Language-Guided Semantic Shape Editing of 3D Gaussian Head Avatars](https://arxiv.org/abs/2610.03599v1)**  
  Authors: Antonio Canela, Jordi Sànchez-Riera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.03599v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://a-canela.github.io/manifoldsplat/)  
  Keywords: 3d gaussian, high-fidelity, geometry, semantic, animation, head, avatar, ar, gaussian splatting  
- **[Reconstructing the Dynamic World: A Representation-Centric View of 4D Scene Reconstruction](https://arxiv.org/abs/2609.39960v2)**  
  Authors: Ziren Gong, Guo Chen, Yongjia Li, Yihua Shao, Fabio Tosi, Stefano Mattoccia, Matteo Poggi, Hao Tang, Fei Ma, Shuyan Li, Ziyang Yan, Nicu Sebe, Ling Shao, Jianfei Cai, Qi Tian, Ming-Hsuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.39960v2.pdf)  
  Keywords: 3d gaussian, understanding, 4d, nerf, geometry, motion, ar, gaussian splatting, dynamic  
- **[Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering](https://arxiv.org/abs/2609.38177v1)**  
  Authors: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon, Heeseong Shin, Wonjun Moon, Federico Tombari, Daniel Barath, Marc Pollefeys, Seungryong Kim, Sunghwan Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.38177v1.pdf)  
  Keywords: 3d gaussian, understanding, geometry, human, ar, gaussian splatting, body, compact  



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