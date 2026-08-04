# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-08-04 01:27:31

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
- [Acceleration](#acceleration) (229 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (993 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (328 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (379 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (412 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (424 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (245 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (31 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (138 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (161 papers) - Papers about SLAM using Gaussian Splatting
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
  Keywords: motion, medical, survey, 4d, 3d gaussian, gaussian splatting, vr, ar, recognition, autonomous driving, compact, neural rendering, 3d reconstruction  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, animation, survey, gaussian splatting, ar, mapping  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: motion, geometry, survey, 3d gaussian, gaussian splatting, tracking, slam, ar, efficient, 3d reconstruction  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, 3d gaussian, gaussian splatting, ar, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: survey, 3d gaussian, gaussian splatting, ray tracing, ar, mapping  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: motion, survey, 3d gaussian, gaussian splatting, face, tracking, localization, slam, ar, efficient, dynamic, mapping  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, survey, 3d gaussian, gaussian splatting, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: geometry, nerf, survey, 3d gaussian, gaussian splatting, ar, efficient  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: compression, survey, 4d, 3d gaussian, gaussian splatting, high-fidelity, ar, efficient, compact, dynamic, 3d reconstruction  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: nerf, robotics, survey, 3d gaussian, gaussian splatting, localization, slam, ar, semantic, mapping, understanding  

### Acceleration

*Showing the latest 50 out of 229 papers*

- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, tracking, localization, slam, efficient rendering, ar, efficient, mapping, 3d reconstruction  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, fast, tracking, ar, human  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: geometry, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, semantic, lightweight, compact, mapping, compression  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, ar, lightweight, dynamic, high quality  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: acceleration, head, motion, avatar, 3d gaussian, gaussian splatting, face, tracking, ar, human, dynamic, deformation  
- **[3D Gaussian Splatting for Scientific Particle Data Compression and Rendering](https://arxiv.org/abs/2607.22956v1)**  
  Authors: Bo Jiang, Youyuan Liu, Taolue Yang, Sheng Di, Sian Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22956v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, fast, ar, lightweight, compact, compression  
- **[Construction and Dynamic Update of Channel Gain Maps via 3D Gaussian Splatting](https://arxiv.org/abs/2607.21099v1)**  
  Authors: Yilong Chen, Yuan Guo, Juncong Zhou, Jie Xu, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21099v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, fast, ar, efficient, compact, dynamic  
- **[QIRF Quantum-Inspired Non-Orthogonal Function-Space Compression for 3D Gaussian Splatting](https://arxiv.org/abs/2607.18067v1)**  
  Authors: Shizeng Jiang, Hao Zhang, Xuerui Ma, Ying Hu, Tao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18067v1.pdf)  
  Keywords: nerf, real-time rendering, 3d gaussian, gaussian splatting, ar, compression  
- **[Locality-Aware Density Control for Efficient Gaussian-based Image Representation](https://arxiv.org/abs/2607.17896v1)**  
  Authors: Jiacong Chen, Qingyu Mao, Xiandong Meng, Shuai Liu, Chao Li, Fanyang Meng, Youneng Bao, Yongsheng Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17896v1.pdf)  
  Keywords: efficient, ar, gaussian splatting, fast  
- **[CaT-GS: Efficient 3DGS Rendering for Large Scale Scenes via Inter-frame Caching and Tile Scheduling](https://arxiv.org/abs/2607.17842v1)**  
  Authors: Tingjia Zhang, Bo Chen, Shengzhong Liu, Fan Wu, Guihai Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17842v1.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, high-fidelity, ar, efficient, neural rendering  

### Applications

*Showing the latest 50 out of 993 papers*

- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: head, motion, geometry, gaussian splatting, localization, ar, 3d reconstruction  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, tracking, localization, slam, efficient rendering, ar, efficient, mapping, 3d reconstruction  
- **[Scene2Sound: Auditory-Grounded Soundscape Generation for 3D Gaussian Worlds](https://arxiv.org/abs/2608.00463v1)**  
  Authors: Masaki Yoshida, Ren Togo, Takahiro Ogawa, Miki Haseyama  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00463v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://masaki-lmd.github.io/scene2sound/.)  
  Keywords: motion, ar, 3d gaussian, gaussian splatting  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: geometry, face, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[OASIS: Occlusion-aware Single-image Hand Avatar Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2607.29633v1)**  
  Authors: Zhisheng Han, Shiyao Wu, Jiayan Qiu, Yakun Ju, Lu Liu, Le Zhang, Pengfei Feng, Huiyu Zhou, Zheheng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29633v1.pdf)  
  Keywords: geometry, nerf, avatar, 3d gaussian, gaussian splatting, face, ar, deformation  
- **[FillGS: Filling Observation Gaps in 4D Gaussian Splatting via Viewpoint-Time Selection and Generative Refinement](https://arxiv.org/abs/2607.29284v1)**  
  Authors: Takashi Otonari, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29284v1.pdf)  
  Keywords: motion, 4d, gaussian splatting, ar, dynamic  
- **[FocusGS: Spatial Delta Layers for Local Repair and Deterministic Editing of Trained 3D Gaussian Assets](https://arxiv.org/abs/2607.28834v1)**  
  Authors: Yiqun Pan, Yukun Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28834v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, ar  
- **[S-Avatar: Diffusion-Guided Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2607.28164v1)**  
  Authors: Hail Song, Seokhwan Yang, Jiwon Yang, Woojin Cho, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28164v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, ar, efficient, vr, dynamic  
- **[TSOG: A Format For Temporally And Spatially Ordered Gaussians](https://arxiv.org/abs/2607.28049v1)**  
  Authors: Shady Gmira, Evangelos Alexiou, Emmanouil Potetsianakis, Emmanuel Thomas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28049v1.pdf)  
  Keywords: geometry, 4d, gaussian splatting, ar, efficient, dynamic  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, fast, tracking, ar, human  

### Avatar Generation

*Showing the latest 50 out of 328 papers*

- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: head, motion, geometry, gaussian splatting, localization, ar, 3d reconstruction  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: geometry, face, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[OASIS: Occlusion-aware Single-image Hand Avatar Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2607.29633v1)**  
  Authors: Zhisheng Han, Shiyao Wu, Jiayan Qiu, Yakun Ju, Lu Liu, Le Zhang, Pengfei Feng, Huiyu Zhou, Zheheng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29633v1.pdf)  
  Keywords: geometry, nerf, avatar, 3d gaussian, gaussian splatting, face, ar, deformation  
- **[S-Avatar: Diffusion-Guided Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2607.28164v1)**  
  Authors: Hail Song, Seokhwan Yang, Jiwon Yang, Woojin Cho, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28164v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, ar, efficient, vr, dynamic  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, fast, tracking, ar, human  
- **[4DHumanDiff: Direct Text-to-4DGS Generation for Consistent 360-Degree Dynamic Humans](https://arxiv.org/abs/2607.27634v1)**  
  Authors: Renlong Wu, Haoran Chen, Yuxiang Wei, Xiaowei Jin, Wangmeng Zuo, Hui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.27634v1.pdf)  
  Keywords: motion, geometry, 4d, gaussian splatting, ar, human, dynamic  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: head, 3d gaussian, gaussian splatting, ar, understanding  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, face, ar, efficient  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: reflection, illumination, face, high-fidelity, ar  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: motion, body, avatar, 3d gaussian, gaussian splatting, ar, semantic, human  

### Dynamic Scene

*Showing the latest 50 out of 379 papers*

- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: head, motion, geometry, gaussian splatting, localization, ar, 3d reconstruction  
- **[Scene2Sound: Auditory-Grounded Soundscape Generation for 3D Gaussian Worlds](https://arxiv.org/abs/2608.00463v1)**  
  Authors: Masaki Yoshida, Ren Togo, Takahiro Ogawa, Miki Haseyama  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00463v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://masaki-lmd.github.io/scene2sound/.)  
  Keywords: motion, ar, 3d gaussian, gaussian splatting  
- **[OASIS: Occlusion-aware Single-image Hand Avatar Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2607.29633v1)**  
  Authors: Zhisheng Han, Shiyao Wu, Jiayan Qiu, Yakun Ju, Lu Liu, Le Zhang, Pengfei Feng, Huiyu Zhou, Zheheng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29633v1.pdf)  
  Keywords: geometry, nerf, avatar, 3d gaussian, gaussian splatting, face, ar, deformation  
- **[FillGS: Filling Observation Gaps in 4D Gaussian Splatting via Viewpoint-Time Selection and Generative Refinement](https://arxiv.org/abs/2607.29284v1)**  
  Authors: Takashi Otonari, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29284v1.pdf)  
  Keywords: motion, 4d, gaussian splatting, ar, dynamic  
- **[S-Avatar: Diffusion-Guided Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2607.28164v1)**  
  Authors: Hail Song, Seokhwan Yang, Jiwon Yang, Woojin Cho, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28164v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, ar, efficient, vr, dynamic  
- **[TSOG: A Format For Temporally And Spatially Ordered Gaussians](https://arxiv.org/abs/2607.28049v1)**  
  Authors: Shady Gmira, Evangelos Alexiou, Emmanouil Potetsianakis, Emmanuel Thomas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28049v1.pdf)  
  Keywords: geometry, 4d, gaussian splatting, ar, efficient, dynamic  
- **[4DHumanDiff: Direct Text-to-4DGS Generation for Consistent 360-Degree Dynamic Humans](https://arxiv.org/abs/2607.27634v1)**  
  Authors: Renlong Wu, Haoran Chen, Yuxiang Wei, Xiaowei Jin, Wangmeng Zuo, Hui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.27634v1.pdf)  
  Keywords: motion, geometry, 4d, gaussian splatting, ar, human, dynamic  
- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: motion, geometry, 3d gaussian, gaussian splatting, ar, compact, understanding  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, ar, lightweight, dynamic, high quality  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: motion, body, avatar, 3d gaussian, gaussian splatting, ar, semantic, human  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: geometry, face, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: motion, geometry, sparse view, illumination, 3d gaussian, gaussian splatting, localization, ar  
- **[Posterior Variance Is a Constraint Map, Not an Error Map: Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v2)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v2.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, fast  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, high-fidelity, semantic, ar, sparse-view, neural rendering  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: geometry, sparse view, 3d gaussian, gaussian splatting, ar  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: geometry, sparse view, 3d gaussian, gaussian splatting, face, large scene, ar, efficient  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: geometry, sparse view, 3d gaussian, gaussian splatting, face, high-fidelity, ar, sparse-view, 3d reconstruction  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: motion, nerf, robotics, 3d gaussian, gaussian splatting, fast, ar, sparse-view, vr  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: nerf, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, lightweight, sparse-view, efficient, dynamic, neural rendering  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: nerf, geometry, real-time rendering, gaussian splatting, ar, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 412 papers*

- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: head, motion, geometry, gaussian splatting, localization, ar, 3d reconstruction  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, tracking, localization, slam, efficient rendering, ar, efficient, mapping, 3d reconstruction  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: geometry, face, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[OASIS: Occlusion-aware Single-image Hand Avatar Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2607.29633v1)**  
  Authors: Zhisheng Han, Shiyao Wu, Jiayan Qiu, Yakun Ju, Lu Liu, Le Zhang, Pengfei Feng, Huiyu Zhou, Zheheng Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.29633v1.pdf)  
  Keywords: geometry, nerf, avatar, 3d gaussian, gaussian splatting, face, ar, deformation  
- **[TSOG: A Format For Temporally And Spatially Ordered Gaussians](https://arxiv.org/abs/2607.28049v1)**  
  Authors: Shady Gmira, Evangelos Alexiou, Emmanouil Potetsianakis, Emmanuel Thomas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28049v1.pdf)  
  Keywords: geometry, 4d, gaussian splatting, ar, efficient, dynamic  
- **[4DHumanDiff: Direct Text-to-4DGS Generation for Consistent 360-Degree Dynamic Humans](https://arxiv.org/abs/2607.27634v1)**  
  Authors: Renlong Wu, Haoran Chen, Yuxiang Wei, Xiaowei Jin, Wangmeng Zuo, Hui Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.27634v1.pdf)  
  Keywords: motion, geometry, 4d, gaussian splatting, ar, human, dynamic  
- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: motion, geometry, 3d gaussian, gaussian splatting, ar, compact, understanding  
- **[3DGBGS: 3D Granular Ball Gaussian Splatting for Compact Novel View Synthesis](https://arxiv.org/abs/2607.26578v1)**  
  Authors: Meng Yang, Shuyin Xia, Dawei Dai, YiWang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26578v1.pdf)  
  Keywords: compact, geometry, gaussian splatting, ar  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: geometry, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, semantic, lightweight, compact, mapping, compression  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, face, ar, efficient  

### Large Scene

- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, tracking, localization, slam, ar, outdoor, lightweight, mapping  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: motion, animation, 3d gaussian, gaussian splatting, ar, outdoor, dynamic, deformation  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: motion, real-time rendering, 3d gaussian, gaussian splatting, fast, large scene, slam, ar, recognition, efficient  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: geometry, 3d gaussian, gaussian splatting, tracking, slam, ar, outdoor, mapping  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ar, outdoor  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: geometry, sparse view, 3d gaussian, gaussian splatting, face, large scene, ar, efficient  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: 3d gaussian, ar, outdoor, human, deformation  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ar, outdoor, mapping  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: head, motion, 3d gaussian, gaussian splatting, tracking, slam, high-fidelity, ar, outdoor, efficient, dynamic, mapping  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, face, localization, slam, ar, outdoor, autonomous driving, efficient, mapping  

### Model Compression

*Showing the latest 50 out of 424 papers*

- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, tracking, localization, slam, efficient rendering, ar, efficient, mapping, 3d reconstruction  
- **[FocusGS: Spatial Delta Layers for Local Repair and Deterministic Editing of Trained 3D Gaussian Assets](https://arxiv.org/abs/2607.28834v1)**  
  Authors: Yiqun Pan, Yukun Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28834v1.pdf)  
  Keywords: lightweight, 3d gaussian, gaussian splatting, ar  
- **[S-Avatar: Diffusion-Guided Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2607.28164v1)**  
  Authors: Hail Song, Seokhwan Yang, Jiwon Yang, Woojin Cho, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28164v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, ar, efficient, vr, dynamic  
- **[TSOG: A Format For Temporally And Spatially Ordered Gaussians](https://arxiv.org/abs/2607.28049v1)**  
  Authors: Shady Gmira, Evangelos Alexiou, Emmanouil Potetsianakis, Emmanuel Thomas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28049v1.pdf)  
  Keywords: geometry, 4d, gaussian splatting, ar, efficient, dynamic  
- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: motion, geometry, 3d gaussian, gaussian splatting, ar, compact, understanding  
- **[3DGBGS: 3D Granular Ball Gaussian Splatting for Compact Novel View Synthesis](https://arxiv.org/abs/2607.26578v1)**  
  Authors: Meng Yang, Shuyin Xia, Dawei Dai, YiWang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26578v1.pdf)  
  Keywords: compact, geometry, gaussian splatting, ar  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: geometry, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, semantic, lightweight, compact, mapping, compression  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, ar, lightweight, dynamic, high quality  
- **[CORF-GS: Real-Time Wireless Radiance Field Reconstruction via Coupled Optical-RF Gaussian Splatting](https://arxiv.org/abs/2607.25569v1)**  
  Authors: Jinya Zhang, Jiajia Guo, Chao-Kai Wen, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25569v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, face, ar, efficient  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, high-fidelity, ar, lightweight, compact, compression  

### Quality Enhancement

*Showing the latest 50 out of 245 papers*

- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, ar, lightweight, dynamic, high quality  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: reflection, illumination, face, high-fidelity, ar  
- **[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403v1)**  
  Authors: Qiang Hu, Zhenlong Wu, Lei Huang, Zihan Zheng, Xiaoyun Zhang, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.24403v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, high-fidelity, ar, lightweight, compact, compression  
- **[SubSplat: High-Resolution Pixel-aligned 3DGS via Sub-pixel Gaussian Reparameterization](https://arxiv.org/abs/2607.20813v1)**  
  Authors: Jiun Lee, Jaekwang Kim, Sangmin Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20813v1.pdf)  
  Keywords: face, gaussian splatting, high-fidelity, ar, efficient  
- **[3D-GIMP: When 3D Gaussian Inpainting Meets PatchMatch](https://arxiv.org/abs/2607.20789v1)**  
  Authors: Xuening Tian, Dieter Schmalstieg, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20789v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, high-fidelity, 3d reconstruction  
- **[Exploration Matters for Escaping the Blur Trap in 3D Gaussian Splatting](https://arxiv.org/abs/2607.17965v1)**  
  Authors: Chengbo Wang, Guozheng Ma, Jinhong Wu, Tie Ji, Yizhen Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17965v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chengbo-wang.github.io/ExploreGS/)  
  Keywords: high-fidelity, 3d gaussian, gaussian splatting, ar  
- **[Packet-Loss Robust 3D Gaussian Compression via Atomic Packaging and GNN-based Error Concealment](https://arxiv.org/abs/2607.17916v1)**  
  Authors: Yuxuan Tao, Xuerui Ma, Hao Zhang, Chunhua Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17916v1.pdf)  
  Keywords: nerf, 3d gaussian, gaussian splatting, high-fidelity, ar, lightweight, neural rendering, compression  
- **[CaT-GS: Efficient 3DGS Rendering for Large Scale Scenes via Inter-frame Caching and Tile Scheduling](https://arxiv.org/abs/2607.17842v1)**  
  Authors: Tingjia Zhang, Bo Chen, Shengzhong Liu, Fan Wu, Guihai Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17842v1.pdf)  
  Keywords: real-time rendering, 3d gaussian, gaussian splatting, high-fidelity, ar, efficient, neural rendering  
- **[FillGauss: Fine-Grained Filling-Aware Impact Sound Generation for 3D Gaussian Splatting](https://arxiv.org/abs/2607.17773v1)**  
  Authors: Chen Yang, Ganye Wen, Bin Huang, Jiayi Lyu, Zehai Niu, Linlin Shen, Jinbao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.17773v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, face, high-fidelity, ar  
- **[SPARE-GS: Structural Parsimony and Resource Efficiency for 3D Gaussian Splatting](https://arxiv.org/abs/2607.16624v1)**  
  Authors: Zhang Chen, Shuai Wan, Fuzheng Yang, Jiazhi Xia, Weiyao Lin, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16624v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, high-fidelity, ar, compact, dynamic, compression  

### Ray Tracing

- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: relighting, reflection, illumination, face, gaussian splatting, ray tracing, ar, efficient, lighting  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: motion, geometry, reflection, 3d gaussian, gaussian splatting, ray tracing, face, high-fidelity, ar, human, dynamic  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, gaussian splatting, ray tracing, fast, ar  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: geometry, real-time rendering, reflection, 3d gaussian, gaussian splatting, ray tracing, fast, path tracing, ar, efficient  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: geometry, illumination, 3d gaussian, gaussian splatting, ar, efficient, global illumination, 3d reconstruction  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: illumination, gaussian splatting, high-fidelity, ar, global illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: geometry, reflection, 3d gaussian, gaussian splatting, ray tracing, segmentation, ar, semantic, efficient  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: illumination, 3d gaussian, gaussian splatting, fast, face, shadow, ar, global illumination  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ray casting, ar, 3d gaussian, gaussian splatting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ray tracing, high-fidelity, ar  

### Relighting

*Showing the latest 50 out of 138 papers*

- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: reflection, illumination, face, high-fidelity, ar  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: illumination, 3d gaussian, gaussian splatting, ar, efficient  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: relighting, reflection, illumination, face, gaussian splatting, ray tracing, ar, efficient, lighting  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: motion, geometry, sparse view, illumination, 3d gaussian, gaussian splatting, localization, ar  
- **[ECoNGS: Efficient Compressive Neural Gaussian Splats for Volume Visualization](https://arxiv.org/abs/2607.18466v1)**  
  Authors: Kaiyuan Tang, Chaoli Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18466v1.pdf)  
  Keywords: vr, gaussian splatting, ar, lightweight, efficient, compact, dynamic, lighting  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: motion, geometry, robotics, illumination, 3d gaussian, gaussian splatting, fast, ar, mapping, lighting, 3d reconstruction  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: motion, geometry, reflection, 3d gaussian, gaussian splatting, ray tracing, face, high-fidelity, ar, human, dynamic  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: geometry, robotics, illumination, gaussian splatting, slam, ar, mapping, 3d reconstruction  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: gaussian splatting, ar, dynamic, mapping, lighting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: geometry, illumination, 3d gaussian, gaussian splatting, face, ar, efficient, 3d reconstruction  

### SLAM

*Showing the latest 50 out of 161 papers*

- **[Swimm3R: Splatting with Medium-aware SfM for Underwater 3D Reconstruction](https://arxiv.org/abs/2608.00950v1)**  
  Authors: Minseong Kweon, Junaed Sattar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00950v1.pdf)  
  Keywords: head, motion, geometry, gaussian splatting, localization, ar, 3d reconstruction  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, tracking, localization, slam, efficient rendering, ar, efficient, mapping, 3d reconstruction  
- **[Split and Drive: Dual-Axis Disentanglement for Real-Time Gaussian Head Avatars](https://arxiv.org/abs/2607.28032v1)**  
  Authors: MD Wahiduzzaman Khan, Mingshan Jia, Xiaolin Zhang, En Yu, Kaska Musial-Gabrys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.28032v1.pdf)  
  Keywords: head, avatar, 3d gaussian, gaussian splatting, fast, tracking, ar, human  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: geometry, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, semantic, lightweight, compact, mapping, compression  
- **[Head Avatars with Dynamic Explicit Hair](https://arxiv.org/abs/2607.23861v1)**  
  Authors: Vanessa Sklyarova, Haonan Chen, Berna Kabadayi, Tobias Kirschstein, Zicong Fan, Xi Wang, Gerard Pons-Moll, Matthias Nießner, Marc Pollefeys, Michael J. Black, Justus Thies  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23861v1.pdf)  
  Keywords: acceleration, head, motion, avatar, 3d gaussian, gaussian splatting, face, tracking, ar, human, dynamic, deformation  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: motion, geometry, sparse view, illumination, 3d gaussian, gaussian splatting, localization, ar  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, tracking, localization, slam, ar, outdoor, lightweight, mapping  
- **[FlexiAvatar: Unified 3D Gaussian Human Avatars Under Arbitrary Body Visibility](https://arxiv.org/abs/2607.19100v1)**  
  Authors: Yihalem Yimolal Tiruneh, Muhammad Salman Ali, Uyoung Jeong, Muneeb A. Khan, MD Khalequzzaman Chowdhury Sayem, Allanur Bayramgeldiyev, Binod Bhattarai, Seungryul Baek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.19100v1.pdf)  
  Keywords: head, body, avatar, 3d gaussian, gaussian splatting, tracking, ar, human, vr, neural rendering  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: motion, geometry, robotics, illumination, 3d gaussian, gaussian splatting, fast, ar, mapping, lighting, 3d reconstruction  
- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, tracking, ar, semantic, dynamic  

### Scene Understanding

*Showing the latest 50 out of 228 papers*

- **[StructureGS: Structure-aware Gaussian Splatting for Articulated Object Reconstruction](https://arxiv.org/abs/2607.26889v1)**  
  Authors: Gahye Lee, Gyoonseo Kim, Wonjong Jang, Jooeun Son, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26889v1.pdf)  
  Keywords: motion, geometry, 3d gaussian, gaussian splatting, ar, compact, understanding  
- **[SpatialQ: Understanding 3D Gaussian Splatting Scene Quality via Visual-based MLLM](https://arxiv.org/abs/2607.26595v1)**  
  Authors: Jingxuan Su, Shenglin Wang, Tiesong Zhao, Ge Li, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26595v1.pdf)  
  Keywords: head, 3d gaussian, gaussian splatting, ar, understanding  
- **[AtlasLC: Fast Codec-Ready Compression of Object-Centric 3D Gaussian Splatting](https://arxiv.org/abs/2607.26525v1)**  
  Authors: ByungHyun Kim, Jinwoo Jeon, Woontack Woo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.26525v1.pdf)  
  Keywords: geometry, real-time rendering, 3d gaussian, gaussian splatting, fast, ar, semantic, lightweight, compact, mapping, compression  
- **[SONG: A Photorealistic 3D Gaussian Simulation Platform for Benchmarking Social Navigation](https://arxiv.org/abs/2607.25219v1)**  
  Authors: Weiqi Huang, Dianyi Yang, Jiaxin Li, Shuangyi Dong, Hao Xu, Zan Wang, Wei Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25219v1.pdf)  
  Keywords: motion, body, avatar, 3d gaussian, gaussian splatting, ar, semantic, human  
- **[Fashion-3DLR: A Controllable 3D Garment Generation Using Pairwise Fashion Elements for Intelligent Design](https://arxiv.org/abs/2607.23189v1)**  
  Authors: Shenghao Yang, Hongtao Zhang, Yuhan Yi, Zhihao Tang, Zihao Cui, Lian Wen, Han Yan, Yuan Gao, Mingbo Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.23189v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, ar, semantic  
- **[Real2Sim2Real for Vision-Language-Action Manipulation: An AMD ROCm-Based Pipeline](https://arxiv.org/abs/2607.22997v1)**  
  Authors: Qing Yang, Xun Wang, Ziguan Wang, Zhenjiang Li, Hongqiang Wang, Dongdong Weng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22997v1.pdf)  
  Keywords: motion, body, 3d gaussian, gaussian splatting, ar, semantic, human  
- **[RealVDeblur: One-Step Diffusion for Generalizable Real-World Video Deblurring](https://arxiv.org/abs/2607.20628v1)**  
  Authors: Renbiao Jin, Mingxin Yang, Yutian Chen, Junhao Zhuang, Xin Cai, Mulin Yu, Linning Xu, Wenxian Yu, Danping Zou, Shi Guo, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.20628v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rbjin.github.io/RealVDeblur)  
  Keywords: motion, 3d gaussian, gaussian splatting, 3d reconstruction, semantic, ar, efficient, compression  
- **[ZeroSplat: Generalized Referring Segmentation in 3D Gaussian Splatting](https://arxiv.org/abs/2607.18801v1)**  
  Authors: Jiayu Ding, Meilu Song, Xiaoyi Zhang, Hongbo Jin, Yichen Jin, Xiangtian Si  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18801v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inkmind-ai.github.io/ZeroSplat)  
  Keywords: head, 3d gaussian, gaussian splatting, segmentation, ar, semantic, dynamic, understanding  
- **[TopoGS: Planar Reconstruction via Topology-aware 3D Gaussian Splatting](https://arxiv.org/abs/2607.16838v1)**  
  Authors: Shanshan Pan, Jiale Chen, Yilin Liu, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16838v1.pdf)  
  Keywords: geometry, 3d gaussian, gaussian splatting, segmentation, ar, compact, 3d reconstruction  
- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: motion, 3d gaussian, gaussian splatting, tracking, ar, semantic, dynamic  



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