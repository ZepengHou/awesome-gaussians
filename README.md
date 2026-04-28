# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-04-28 01:59:55

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

- [3DGS Surveys](#3dgs-surveys) (17 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (228 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (336 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (377 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (83 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (387 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (54 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (433 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (232 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (137 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (146 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (225 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: motion, survey, gaussian splatting, slam, 3d reconstruction, tracking, geometry, 3d gaussian, ar, efficient  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, gaussian splatting, vr, 3d gaussian, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: survey, gaussian splatting, ray tracing, mapping, 3d gaussian, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: dynamic, motion, survey, gaussian splatting, slam, localization, face, mapping, tracking, 3d gaussian, ar, efficient  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, gaussian splatting, robotics, 3d gaussian, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, geometry, nerf, ar, efficient  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, survey, gaussian splatting, 3d reconstruction, compression, compact, 3d gaussian, ar, efficient  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: slam, survey, gaussian splatting, localization, robotics, 3d gaussian, understanding, semantic, mapping, nerf, ar  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: high-fidelity, survey, gaussian splatting, slam, localization, robotics, semantic, mapping, 3d gaussian, ar, efficient  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, motion, survey, gaussian splatting, fast, 3d gaussian, geometry, nerf, ar  

### Acceleration

*Showing the latest 50 out of 228 papers*

- **[WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images](https://arxiv.org/abs/2604.21182v1)**  
  Authors: Yuki Fujimura, Takahiro Kushida, Kazuya Kitano, Takuya Funatomi, Yasuhiro Mukaigawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21182v1.pdf)  
  Keywords: gaussian splatting, illumination, real-time rendering, lighting, 3d gaussian, ar  
- **[GSCompleter: A Distillation-Free Plugin for Metric-Aware 3D Gaussian Splatting Completion in Seconds](https://arxiv.org/abs/2604.20155v1)**  
  Authors: Ao Gao, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20155v1.pdf)  
  Keywords: sparse-view, gaussian splatting, real-time rendering, 3d gaussian, ar  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[Neural Gabor Splatting: Enhanced Gaussian Splatting with Neural Gabor for High-frequency Surface Reconstruction](https://arxiv.org/abs/2604.15941v1)**  
  Authors: Haato Watanabe, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15941v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, fast, face, lightweight, 3d gaussian, real-time rendering, nerf, ar  
- **[CLOTH-HUGS: Cloth Aware Human Gaussian Splatting](https://arxiv.org/abs/2604.15875v1)**  
  Authors: Sadia Mubashshira, Nazanin Amini, Kevin Desai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15875v1.pdf)  
  Keywords: dynamic, deformation, gaussian splatting, body, neural rendering, real-time rendering, human, ar  
- **[Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography](https://arxiv.org/abs/2604.15862v1)**  
  Authors: Yijia Guo, Wenkai Huang, Tong Hu, Gaolei Li, Yang Li, Yuxin Hong, Liwen Hu, Xitong Ling, Jianhua Li, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15862v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, 3d reconstruction, fast, mapping, 3d gaussian, ar, efficient  
- **[GlobalSplat: Efficient Feed-Forward 3D Gaussian Splatting via Global Scene Tokens](https://arxiv.org/abs/2604.15284v2)**  
  Authors: Roni Itkin, Noam Issachar, Yehonatan Keypur, Xingyu Chen, Anpei Chen, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15284v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://r-itk.github.io/globalsplat/)  
  Keywords: gaussian splatting, fast, geometry, compact, 3d gaussian, ar, efficient  
- **[ArtifactWorld: Scaling 3D Gaussian Splatting Artifact Restoration via Video Generation Models](https://arxiv.org/abs/2604.12251v1)**  
  Authors: Xinliang Wang, Yifeng Shi, Zhenyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12251v1.pdf)  
  Keywords: sparse-view, high-fidelity, gaussian splatting, 3d reconstruction, real-time rendering, 3d gaussian, ar  
- **[VVGT: Visual Volume-Grounded Transformer](https://arxiv.org/abs/2604.12217v1)**  
  Authors: Yuxuan Wang, Qibiao Li, Youcheng Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12217v1.pdf)  
  Keywords: gaussian splatting, fast, face, geometry, vr, 3d gaussian, ar  
- **[Ψ-Map: Panoptic Surface Integrated Mapping Enables Real2Sim Transfer](https://arxiv.org/abs/2604.10982v1)**  
  Authors: Xuan Yu, Yuxuan Xie, Changjian Jiang, Shichao Zhai, Rong Xiong, Yu Zhang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.10982v1.pdf)  
  Keywords: segmentation, gaussian splatting, efficient rendering, robotics, face, understanding, semantic, mapping, 3d gaussian, ar, efficient  

### Applications

*Showing the latest 50 out of 994 papers*

- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: gaussian splatting, light transport, localization, ar, efficient  
- **[Spatiotemporal Degradation-Aware 3D Gaussian Splatting for Realistic Underwater Scene Reconstruction](https://arxiv.org/abs/2604.23551v1)**  
  Authors: Shaohua Liu, Ning Gao, Zuoya Gu, Hongkun Dou, Yue Deng, Hongjue Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23551v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, 3d gaussian, ar  
- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: head, gaussian splatting, semantic, 3d gaussian, ar, efficient  
- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v1)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v1.pdf)  
  Keywords: dynamic, 4d, motion, slam, gaussian splatting, localization, mapping, tracking, 3d gaussian, ar, efficient  
- **[EvFlow-GS: Event Enhanced Motion Deblurring with Optical Flow for 3D Gaussian Splatting](https://arxiv.org/abs/2604.22183v1)**  
  Authors: Feiyu An, Yufei Deng, Zihui Zhang, Rong Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22183v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[PAGaS: Pixel-Aligned 1DoF Gaussian Splatting for Depth Refinement](https://arxiv.org/abs/2604.22129v1)**  
  Authors: David Recasens, Robert Maier, Aljaz Bozic, Stephane Grabli, Javier Civera, Tony Tung, Edmond Boyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22129v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures](https://arxiv.org/abs/2604.21631v1)**  
  Authors: Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21631v1.pdf)  
  Keywords: gaussian splatting, face, lightweight, 3d gaussian, nerf, ar  
- **[You Only Gaussian Once: Controllable 3D Gaussian Splatting for Ultra-Densely Sampled Scenes](https://arxiv.org/abs/2604.21400v2)**  
  Authors: Jinrang Jia, Zhenjia Li, Yifeng Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21400v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jjrcn.github.io/yogo-project-home/)  
  Keywords: high-fidelity, gaussian splatting, neural rendering, 3d gaussian, ar  
- **[WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images](https://arxiv.org/abs/2604.21182v1)**  
  Authors: Yuki Fujimura, Takahiro Kushida, Kazuya Kitano, Takuya Funatomi, Yasuhiro Mukaigawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21182v1.pdf)  
  Keywords: gaussian splatting, illumination, real-time rendering, lighting, 3d gaussian, ar  
- **[GSCompleter: A Distillation-Free Plugin for Metric-Aware 3D Gaussian Splatting Completion in Seconds](https://arxiv.org/abs/2604.20155v1)**  
  Authors: Ao Gao, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20155v1.pdf)  
  Keywords: sparse-view, gaussian splatting, real-time rendering, 3d gaussian, ar  

### Avatar Generation

*Showing the latest 50 out of 336 papers*

- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: head, gaussian splatting, semantic, 3d gaussian, ar, efficient  
- **[DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures](https://arxiv.org/abs/2604.21631v1)**  
  Authors: Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21631v1.pdf)  
  Keywords: gaussian splatting, face, lightweight, 3d gaussian, nerf, ar  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: high-fidelity, motion, gaussian splatting, human, lighting, 3d gaussian, ar  
- **[Neural Gabor Splatting: Enhanced Gaussian Splatting with Neural Gabor for High-frequency Surface Reconstruction](https://arxiv.org/abs/2604.15941v1)**  
  Authors: Haato Watanabe, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15941v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, fast, face, lightweight, 3d gaussian, real-time rendering, nerf, ar  
- **[CLOTH-HUGS: Cloth Aware Human Gaussian Splatting](https://arxiv.org/abs/2604.15875v1)**  
  Authors: Sadia Mubashshira, Nazanin Amini, Kevin Desai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15875v1.pdf)  
  Keywords: dynamic, deformation, gaussian splatting, body, neural rendering, real-time rendering, human, ar  
- **[One-shot Compositional 3D Head Avatars with Deformable Hair](https://arxiv.org/abs/2604.14782v1)**  
  Authors: Yuan Sun, Xuan Wang, WeiLi Zhang, Wenxuan Zhang, Yu Guo, Fei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14782v1.pdf)  
  Keywords: dynamic, head, motion, deformation, gaussian splatting, face, semantic, avatar, geometry, animation, 3d gaussian, ar  
- **[SSD-GS: Scattering and Shadow Decomposition for Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2604.13333v1)**  
  Authors: Iris Zheng, Guojun Tang, Alexander Doronin, Paul Teal, Fang-Lue Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13333v1.pdf)  
  Keywords: ar, gaussian splatting, illumination, face, relightable, shadow, lighting, relighting, 3d gaussian, reflection  
- **[PatchPoison: Poisoning Multi-View Datasets to Degrade 3D Reconstruction](https://arxiv.org/abs/2604.13153v1)**  
  Authors: Prajas Wadekar, Venkata Sai Pranav Bachina, Kunal Bhosikar, Ankit Gangwal, Charu Sharma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13153v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, lightweight, 3d gaussian, human, geometry, nerf, ar  
- **[Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting](https://arxiv.org/abs/2604.12626v1)**  
  Authors: Ziyuan Xia, Jingyi Xu, Chong Cui, Yuanhong Yu, Jiazhao Zhang, Qingsong Yan, Tao Ni, Junbo Chen, Xiaowei Zhou, Hujun Bao, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12626v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, human, avatar, 3d gaussian, ar  

### Dynamic Scene

*Showing the latest 50 out of 377 papers*

- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v1)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v1.pdf)  
  Keywords: dynamic, 4d, motion, slam, gaussian splatting, localization, mapping, tracking, 3d gaussian, ar, efficient  
- **[EvFlow-GS: Event Enhanced Motion Deblurring with Optical Flow for 3D Gaussian Splatting](https://arxiv.org/abs/2604.22183v1)**  
  Authors: Feiyu An, Yufei Deng, Zihui Zhang, Rong Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22183v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[Gaussians on a Diet: High-Quality Memory-Bounded 3D Gaussian Splatting Training](https://arxiv.org/abs/2604.20046v2)**  
  Authors: Yangming Zhang, Jian Xu, Chaojian Li, Kunxiong Zhu, Wei Niu, Gagan Agrawal, Yang Katie Zhao, Jian Wang, Yingyan Celine Lin, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20046v2.pdf)  
  Keywords: dynamic, gaussian splatting, 3d gaussian, ar, efficient  
- **[An Object-Centered Data Acquisition Method for 3D Gaussian Splatting using Mobile Phones](https://arxiv.org/abs/2604.19216v1)**  
  Authors: Yuezhe Zhang, Luqian Bai, Mengting Yu, Lei Wei, Shuai Wan, Yifan Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19216v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, motion  
- **[BALTIC: A Benchmark and Cross-Domain Strategy for 3D Reconstruction Across Air and Underwater Domains Under Varying Illumination](https://arxiv.org/abs/2604.19133v1)**  
  Authors: Michele Grimaldi, David Nakath, Oscar Pizarro, Jonatan Scharff Willners, Ignacio Carlucho, Yvan R. Petillot  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19133v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, illumination, lighting, geometry, 3d gaussian, ar  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[GS-STVSR: Ultra-Efficient Continuous Spatio-Temporal Video Super-Resolution via 2D Gaussian Splatting](https://arxiv.org/abs/2604.18047v1)**  
  Authors: Mingyu Shi, Xin Di, Long Peng, Boxiang Cao, Anran Wu, Zhanfeng Feng, Jiaming Guo, Renjing Pei, Xueyang Fu, Yang Cao, Zhengjun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.18047v1.pdf)  
  Keywords: motion, gaussian splatting, lightweight, mapping, ar, efficient  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: high-fidelity, motion, gaussian splatting, human, lighting, 3d gaussian, ar  
- **[Incoherent Deformation, Not Capacity: Diagnosing and Mitigating Overfitting in Dynamic Gaussian Splatting](https://arxiv.org/abs/2604.16747v1)**  
  Authors: Ahmad Droby  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.16747v1.pdf)  
  Keywords: dynamic, deformation, gaussian splatting, 3d gaussian, nerf, ar  
- **[CLOTH-HUGS: Cloth Aware Human Gaussian Splatting](https://arxiv.org/abs/2604.15875v1)**  
  Authors: Sadia Mubashshira, Nazanin Amini, Kevin Desai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15875v1.pdf)  
  Keywords: dynamic, deformation, gaussian splatting, body, neural rendering, real-time rendering, human, ar  

### Few-shot

*Showing the latest 50 out of 83 papers*

- **[GSCompleter: A Distillation-Free Plugin for Metric-Aware 3D Gaussian Splatting Completion in Seconds](https://arxiv.org/abs/2604.20155v1)**  
  Authors: Ao Gao, Jingyu Gong, Xin Tan, Zhizhong Zhang, Yuan Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20155v1.pdf)  
  Keywords: sparse-view, gaussian splatting, real-time rendering, 3d gaussian, ar  
- **[FluSplat: Sparse-View 3D Editing without Test-Time Optimization](https://arxiv.org/abs/2604.20038v1)**  
  Authors: Haitao Huang, Shin-Fang Chng, Huangying Zhan, Qingan Yan, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20038v1.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d reconstruction, sparse view, 3d gaussian, ar  
- **[ArtifactWorld: Scaling 3D Gaussian Splatting Artifact Restoration via Video Generation Models](https://arxiv.org/abs/2604.12251v1)**  
  Authors: Xinliang Wang, Yifeng Shi, Zhenyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12251v1.pdf)  
  Keywords: sparse-view, high-fidelity, gaussian splatting, 3d reconstruction, real-time rendering, 3d gaussian, ar  
- **[Learning 3D Representations for Spatial Intelligence from Unposed Multi-View Images](https://arxiv.org/abs/2604.10573v1)**  
  Authors: Bo Zhou, Qiuxia Lai, Zeren Sun, Xiangbo Shu, Yazhou Yao, Wenguan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.10573v1.pdf)  
  Keywords: sparse-view, head, gaussian splatting, understanding, semantic, geometry, ar  
- **[SurfelSplat: Learning Efficient and Generalizable Gaussian Surfel Representations for Sparse-View Surface Reconstruction](https://arxiv.org/abs/2604.08370v1)**  
  Authors: Chensheng Dai, Shengjun Zhang, Min Chen, Yueqi Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.08370v1.pdf)  
  Keywords: sparse-view, gaussian splatting, face, geometry, 3d gaussian, ar, efficient  
- **[DOC-GS: Dual-Domain Observation and Calibration for Reliable Sparse-View Gaussian Splatting](https://arxiv.org/abs/2604.06739v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.06739v1.pdf)  
  Keywords: sparse-view, gaussian splatting, understanding, 3d gaussian, ar  
- **[PR-IQA: Partial-Reference Image Quality Assessment for Diffusion-Based Novel View Synthesis](https://arxiv.org/abs/2604.04576v2)**  
  Authors: Inseong Choi, Siwoo Lee, Seung-Hun Nam, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04576v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kakaomacao.github.io/pr-iqa-project-page/.)  
  Keywords: sparse-view, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[4C4D: 4 Camera 4D Gaussian Splatting](https://arxiv.org/abs/2604.04063v1)**  
  Authors: Junsheng Zhou, Zhifan Yang, Liang Han, Wenyuan Zhang, Kanle Shi, Shenkun Xu, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.04063v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junshengzhou.github.io/4C4D.)  
  Keywords: dynamic, 4d, sparse-view, high-fidelity, gaussian splatting, geometry, ar  
- **[Rendering Multi-Human and Multi-Object with 3D Gaussian Splatting](https://arxiv.org/abs/2604.02996v2)**  
  Authors: Weiquan Wang, Jun Xiao, Feifei Shao, Yi Yang, Yueting Zhuang, Long Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.02996v2.pdf)  
  Keywords: dynamic, sparse-view, high-fidelity, gaussian splatting, robotics, human, vr, 3d gaussian, ar  
- **[Diff3R: Feed-forward 3D Gaussian Splatting with Uncertainty-aware Differentiable Optimization](https://arxiv.org/abs/2604.01030v1)**  
  Authors: Yueh-Cheng Liu, Jozef Hladký, Matthias Nießner, Angela Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01030v1.pdf)  
  Keywords: sparse-view, gaussian splatting, fast, 3d gaussian, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 387 papers*

- **[Spatiotemporal Degradation-Aware 3D Gaussian Splatting for Realistic Underwater Scene Reconstruction](https://arxiv.org/abs/2604.23551v1)**  
  Authors: Shaohua Liu, Ning Gao, Zuoya Gu, Hongkun Dou, Yue Deng, Hongjue Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23551v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, 3d gaussian, ar  
- **[EvFlow-GS: Event Enhanced Motion Deblurring with Optical Flow for 3D Gaussian Splatting](https://arxiv.org/abs/2604.22183v1)**  
  Authors: Feiyu An, Yufei Deng, Zihui Zhang, Rong Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22183v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[PAGaS: Pixel-Aligned 1DoF Gaussian Splatting for Depth Refinement](https://arxiv.org/abs/2604.22129v1)**  
  Authors: David Recasens, Robert Maier, Aljaz Bozic, Stephane Grabli, Javier Civera, Tony Tung, Edmond Boyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22129v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[FluSplat: Sparse-View 3D Editing without Test-Time Optimization](https://arxiv.org/abs/2604.20038v1)**  
  Authors: Haitao Huang, Shin-Fang Chng, Huangying Zhan, Qingan Yan, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20038v1.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d reconstruction, sparse view, 3d gaussian, ar  
- **[BALTIC: A Benchmark and Cross-Domain Strategy for 3D Reconstruction Across Air and Underwater Domains Under Varying Illumination](https://arxiv.org/abs/2604.19133v1)**  
  Authors: Michele Grimaldi, David Nakath, Oscar Pizarro, Jonatan Scharff Willners, Ignacio Carlucho, Yvan R. Petillot  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19133v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, illumination, lighting, geometry, 3d gaussian, ar  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[Neural Gabor Splatting: Enhanced Gaussian Splatting with Neural Gabor for High-frequency Surface Reconstruction](https://arxiv.org/abs/2604.15941v1)**  
  Authors: Haato Watanabe, Nobuyuki Umetani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15941v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, fast, face, lightweight, 3d gaussian, real-time rendering, nerf, ar  
- **[Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography](https://arxiv.org/abs/2604.15862v1)**  
  Authors: Yijia Guo, Wenkai Huang, Tong Hu, Gaolei Li, Yang Li, Yuxin Hong, Liwen Hu, Xitong Ling, Jianhua Li, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15862v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, 3d reconstruction, fast, mapping, 3d gaussian, ar, efficient  
- **[GaussianFlow SLAM: Monocular Gaussian Splatting SLAM Guided by GaussianFlow](https://arxiv.org/abs/2604.15612v1)**  
  Authors: Dong-Uk Seo, Jinwoo Jeon, Eungchang Mason Lee, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15612v1.pdf)  
  Keywords: slam, motion, gaussian splatting, mapping, tracking, geometry, ar  
- **[GlobalSplat: Efficient Feed-Forward 3D Gaussian Splatting via Global Scene Tokens](https://arxiv.org/abs/2604.15284v2)**  
  Authors: Roni Itkin, Noam Issachar, Yehonatan Keypur, Xingyu Chen, Anpei Chen, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15284v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://r-itk.github.io/globalsplat/)  
  Keywords: gaussian splatting, fast, geometry, compact, 3d gaussian, ar, efficient  

### Large Scene

*Showing the latest 50 out of 54 papers*

- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: gaussian splatting, outdoor, 3d gaussian, ar  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: slam, gaussian splatting, localization, outdoor, mapping, 3d gaussian, ar  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: segmentation, gaussian splatting, understanding, semantic, urban scene, geometry, compact, 3d gaussian, ar  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: large scene, gaussian splatting, semantic, 3d gaussian, ar  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: dynamic, 4d, high-fidelity, motion, gaussian splatting, large scene, shadow, understanding, neural rendering, geometry, ar, efficient  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: gaussian splatting, outdoor, localization, ar, efficient  
- **[FilterGS: Traversal-Free Parallel Filtering and Adaptive Shrinking for Large-Scale LoD 3D Gaussian Splatting](https://arxiv.org/abs/2603.23891v1)**  
  Authors: Yixian Wang, Haolin Yu, Jiadong Tang, Yu Gao, Xihan Wang, Yufeng Yue, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23891v1.pdf)  
  Keywords: head, large scene, gaussian splatting, face, neural rendering, 3d gaussian, ar, efficient  
- **[MAGICIAN: Efficient Long-Term Planning with Imagined Gaussians for Active Mapping](https://arxiv.org/abs/2603.22650v2)**  
  Authors: Shiyao Li, Antoine Guédon, Shizhe Chen, Vincent Lepetit  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.22650v2.pdf)  
  Keywords: gaussian splatting, fast, face, outdoor, mapping, lighting, 3d gaussian, ar, efficient  
- **[M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844v1)**  
  Authors: Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16844v1.pdf)  
  Keywords: dynamic, head, slam, gaussian splatting, outdoor, tracking, ar, efficient  
- **[Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty](https://arxiv.org/abs/2603.16538v1)**  
  Authors: Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.16538v1.pdf)  
  Keywords: gaussian splatting, outdoor, 3d gaussian, geometry, localization, ar  

### Model Compression

*Showing the latest 50 out of 433 papers*

- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: gaussian splatting, light transport, localization, ar, efficient  
- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: head, gaussian splatting, semantic, 3d gaussian, ar, efficient  
- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v1)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v1.pdf)  
  Keywords: dynamic, 4d, motion, slam, gaussian splatting, localization, mapping, tracking, 3d gaussian, ar, efficient  
- **[PAGaS: Pixel-Aligned 1DoF Gaussian Splatting for Depth Refinement](https://arxiv.org/abs/2604.22129v1)**  
  Authors: David Recasens, Robert Maier, Aljaz Bozic, Stephane Grabli, Javier Civera, Tony Tung, Edmond Boyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22129v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures](https://arxiv.org/abs/2604.21631v1)**  
  Authors: Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21631v1.pdf)  
  Keywords: gaussian splatting, face, lightweight, 3d gaussian, nerf, ar  
- **[Gaussians on a Diet: High-Quality Memory-Bounded 3D Gaussian Splatting Training](https://arxiv.org/abs/2604.20046v2)**  
  Authors: Yangming Zhang, Jian Xu, Chaojian Li, Kunxiong Zhu, Wei Niu, Gagan Agrawal, Yang Katie Zhao, Jian Wang, Yingyan Celine Lin, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.20046v2.pdf)  
  Keywords: dynamic, gaussian splatting, 3d gaussian, ar, efficient  
- **[OT-UVGS: Revisiting UV Mapping for Gaussian Splatting as a Capacity Allocation Problem](https://arxiv.org/abs/2604.19127v1)**  
  Authors: Byunghyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19127v1.pdf)  
  Keywords: gaussian splatting, lightweight, 3d gaussian, mapping, compact, nerf, ar  
- **[AdaGScale: Viewpoint-Adaptive Gaussian Scaling in 3D Gaussian Splatting to Reduce Gaussian-Tile Pairs](https://arxiv.org/abs/2604.18980v1)**  
  Authors: Joongho Jo, Hyerin Lim, Hanjun Choi, Jongsun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.18980v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, efficient  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[GS-STVSR: Ultra-Efficient Continuous Spatio-Temporal Video Super-Resolution via 2D Gaussian Splatting](https://arxiv.org/abs/2604.18047v1)**  
  Authors: Mingyu Shi, Xin Di, Long Peng, Boxiang Cao, Anran Wu, Zhanfeng Feng, Jiaming Guo, Renjing Pei, Xueyang Fu, Yang Cao, Zhengjun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.18047v1.pdf)  
  Keywords: motion, gaussian splatting, lightweight, mapping, ar, efficient  

### Quality Enhancement

*Showing the latest 50 out of 232 papers*

- **[You Only Gaussian Once: Controllable 3D Gaussian Splatting for Ultra-Densely Sampled Scenes](https://arxiv.org/abs/2604.21400v2)**  
  Authors: Jinrang Jia, Zhenjia Li, Yifeng Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21400v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jjrcn.github.io/yogo-project-home/)  
  Keywords: high-fidelity, gaussian splatting, neural rendering, 3d gaussian, ar  
- **[High-Fidelity 3D Gaussian Human Reconstruction via Region-Aware Initialization and Geometric Priors](https://arxiv.org/abs/2604.21714v1)**  
  Authors: Yang Liu, Zhiyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21714v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, deformation, efficient rendering, face, real-time rendering, human, geometry, 3d gaussian, ar, efficient  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: high-fidelity, motion, gaussian splatting, human, lighting, 3d gaussian, ar  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, understanding, lighting, 3d gaussian, ar, efficient  
- **[GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments](https://arxiv.org/abs/2604.12837v1)**  
  Authors: Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12837v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, slam, localization, semantic, mapping, 3d gaussian, ar  
- **[Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting](https://arxiv.org/abs/2604.12626v1)**  
  Authors: Ziyuan Xia, Jingyi Xu, Chong Cui, Yuanhong Yu, Jiazhao Zhang, Qingsong Yan, Tao Ni, Junbo Chen, Xiaowei Zhou, Hujun Bao, Ruizhen Hu, Sida Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12626v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, human, avatar, 3d gaussian, ar  
- **[PDF-GS: Progressive Distractor Filtering for Robust 3D Gaussian Splatting](https://arxiv.org/abs/2604.12580v2)**  
  Authors: Kangmin Seo, MinKyu Lee, Tae-Young Kim, ByeongCheol Lee, JoonSeoung An, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12580v2.pdf)  
  Keywords: head, high-fidelity, gaussian splatting, lightweight, 3d gaussian, ar  
- **[ArtifactWorld: Scaling 3D Gaussian Splatting Artifact Restoration via Video Generation Models](https://arxiv.org/abs/2604.12251v1)**  
  Authors: Xinliang Wang, Yifeng Shi, Zhenyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12251v1.pdf)  
  Keywords: sparse-view, high-fidelity, gaussian splatting, 3d reconstruction, real-time rendering, 3d gaussian, ar  
- **[Unfolding 3D Gaussian Splatting via Iterative Gaussian Synopsis](https://arxiv.org/abs/2604.11685v1)**  
  Authors: Yuqin Lu, Yang Zhou, Yihua Dai, Guiqing Li, Shengfeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11685v1.pdf)  
  Keywords: head, high-fidelity, gaussian splatting, compact, 3d gaussian, ar, efficient  
- **[Fast-SegSim: Real-Time Open-Vocabulary Segmentation for Robotics in Simulation](https://arxiv.org/abs/2604.10951v1)**  
  Authors: Xuan Yu, Yuxuan Xie, Shichao Zhai, Shuhao Ye, Rong Xiong, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.10951v1.pdf)  
  Keywords: segmentation, high-fidelity, gaussian splatting, 3d reconstruction, fast, robotics, nerf, ar  

### Ray Tracing

- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: dynamic, gaussian splatting, robotics, ray tracing, lighting, semantic, tracking, 3d gaussian, ar, efficient  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, reflection, face, ray tracing, ar  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: slam, gaussian splatting, localization, face, ray tracing, semantic, tracking, mapping, 3d gaussian, ar, efficient  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: ar, gaussian splatting, relightable, shadow, ray tracing, mapping, 3d gaussian, reflection  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: high-fidelity, gaussian splatting, fast, face, 3d gaussian, real-time rendering, ray tracing, geometry, nerf, ar, efficient  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes](https://arxiv.org/abs/2603.17499v5)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v5.pdf)  
  Keywords: survey, gaussian splatting, ray tracing, mapping, 3d gaussian, ar  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, real-time rendering, ray marching, 3d gaussian, ar, efficient  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: gaussian splatting, fast, robotics, geometry, 3d gaussian, ar, ray casting, efficient  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: ar, gaussian splatting, fast, face, lightweight, ray tracing, geometry, reflection, efficient  
- **[Radiometrically Consistent Gaussian Surfels for Inverse Rendering](https://arxiv.org/abs/2603.01491v1)**  
  Authors: Kyu Beom Han, Jaeyoon Kim, Woo Jae Kim, Jinhwan Seo, Sung-eui Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.01491v1.pdf)  
  Keywords: ar, gaussian splatting, illumination, ray tracing, global illumination, lighting, relighting, reflection, efficient  

### Relighting

*Showing the latest 50 out of 137 papers*

- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: gaussian splatting, light transport, localization, ar, efficient  
- **[WildSplatter: Feed-forward 3D Gaussian Splatting with Appearance Control from Unconstrained Images](https://arxiv.org/abs/2604.21182v1)**  
  Authors: Yuki Fujimura, Takahiro Kushida, Kazuya Kitano, Takuya Funatomi, Yasuhiro Mukaigawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.21182v1.pdf)  
  Keywords: gaussian splatting, illumination, real-time rendering, lighting, 3d gaussian, ar  
- **[BALTIC: A Benchmark and Cross-Domain Strategy for 3D Reconstruction Across Air and Underwater Domains Under Varying Illumination](https://arxiv.org/abs/2604.19133v1)**  
  Authors: Michele Grimaldi, David Nakath, Oscar Pizarro, Jonatan Scharff Willners, Ignacio Carlucho, Yvan R. Petillot  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19133v1.pdf)  
  Keywords: motion, gaussian splatting, 3d reconstruction, illumination, lighting, geometry, 3d gaussian, ar  
- **[E3VS-Bench: A Benchmark for Viewpoint-Dependent Active Perception in 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2604.17969v2)**  
  Authors: Koya Sakamoto, Taiki Miyanishi, Daichi Azuma, Shuhei Kurita, Shu Morikuni, Naoya Chiba, Motoaki Kawanabe, Yusuke Iwasawa, Yutaka Matsuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17969v2.pdf)  
  Keywords: high-fidelity, motion, gaussian splatting, human, lighting, 3d gaussian, ar  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: segmentation, gaussian splatting, semantic, lighting, mapping, relighting, 3d gaussian, ar, efficient  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, understanding, lighting, 3d gaussian, ar, efficient  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: slam, gaussian splatting, recognition, mapping, lighting, geometry, localization, ar  
- **[MSGS: Multispectral 3D Gaussian Splatting](https://arxiv.org/abs/2604.13340v1)**  
  Authors: Iris Zheng, Guojun Tang, Alexander Doronin, Paul Teal, Fang-Lue Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13340v1.pdf)  
  Keywords: ar, gaussian splatting, compact, 3d gaussian, reflection  
- **[SSD-GS: Scattering and Shadow Decomposition for Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2604.13333v1)**  
  Authors: Iris Zheng, Guojun Tang, Alexander Doronin, Paul Teal, Fang-Lue Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13333v1.pdf)  
  Keywords: ar, gaussian splatting, illumination, face, relightable, shadow, lighting, relighting, 3d gaussian, reflection  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: dynamic, gaussian splatting, robotics, ray tracing, lighting, semantic, tracking, 3d gaussian, ar, efficient  

### SLAM

*Showing the latest 50 out of 146 papers*

- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: gaussian splatting, light transport, localization, ar, efficient  
- **[Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM](https://arxiv.org/abs/2604.22339v1)**  
  Authors: Yunsong Wang, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22339v1.pdf)  
  Keywords: dynamic, 4d, motion, slam, gaussian splatting, localization, mapping, tracking, 3d gaussian, ar, efficient  
- **[OT-UVGS: Revisiting UV Mapping for Gaussian Splatting as a Capacity Allocation Problem](https://arxiv.org/abs/2604.19127v1)**  
  Authors: Byunghyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19127v1.pdf)  
  Keywords: gaussian splatting, lightweight, 3d gaussian, mapping, compact, nerf, ar  
- **[GS-STVSR: Ultra-Efficient Continuous Spatio-Temporal Video Super-Resolution via 2D Gaussian Splatting](https://arxiv.org/abs/2604.18047v1)**  
  Authors: Mingyu Shi, Xin Di, Long Peng, Boxiang Cao, Anran Wu, Zhanfeng Feng, Jiaming Guo, Renjing Pei, Xueyang Fu, Yang Cao, Zhengjun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.18047v1.pdf)  
  Keywords: motion, gaussian splatting, lightweight, mapping, ar, efficient  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: segmentation, gaussian splatting, semantic, lighting, mapping, relighting, 3d gaussian, ar, efficient  
- **[Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography](https://arxiv.org/abs/2604.15862v1)**  
  Authors: Yijia Guo, Wenkai Huang, Tong Hu, Gaolei Li, Yang Li, Yuxin Hong, Liwen Hu, Xitong Ling, Jianhua Li, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15862v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, 3d reconstruction, fast, mapping, 3d gaussian, ar, efficient  
- **[GaussianFlow SLAM: Monocular Gaussian Splatting SLAM Guided by GaussianFlow](https://arxiv.org/abs/2604.15612v1)**  
  Authors: Dong-Uk Seo, Jinwoo Jeon, Eungchang Mason Lee, Hyun Myung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.15612v1.pdf)  
  Keywords: slam, motion, gaussian splatting, mapping, tracking, geometry, ar  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: slam, gaussian splatting, recognition, mapping, lighting, geometry, localization, ar  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: slam, gaussian splatting, localization, outdoor, mapping, 3d gaussian, ar  
- **[GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments](https://arxiv.org/abs/2604.12837v1)**  
  Authors: Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12837v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, slam, localization, semantic, mapping, 3d gaussian, ar  

### Scene Understanding

*Showing the latest 50 out of 225 papers*

- **[NRGS: Neural Regularization for Robust 3D Semantic Gaussian Splatting](https://arxiv.org/abs/2604.22439v1)**  
  Authors: Zaiyan Yang, Xinpeng Liu, Heng Guo, Jinglei Shi, Zhanyu Ma, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.22439v1.pdf)  
  Keywords: head, gaussian splatting, semantic, 3d gaussian, ar, efficient  
- **[TransSplat: Unbalanced Semantic Transport for Language-Driven 3DGS Editing](https://arxiv.org/abs/2604.19571v1)**  
  Authors: Yanhui Chen, Jiahong Li, Jingchao Wang, Junyi Lin, Zixin Zeng, Yang Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.19571v1.pdf)  
  Keywords: gaussian splatting, semantic, vr, 3d gaussian, ar  
- **[Instant Colorization of Gaussian Splats](https://arxiv.org/abs/2604.17155v1)**  
  Authors: Daniel Lieber, Alexander Mock, Nils Wandel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.17155v1.pdf)  
  Keywords: segmentation, gaussian splatting, semantic, lighting, mapping, relighting, 3d gaussian, ar, efficient  
- **[One-shot Compositional 3D Head Avatars with Deformable Hair](https://arxiv.org/abs/2604.14782v1)**  
  Authors: Yuan Sun, Xuan Wang, WeiLi Zhang, Wenxuan Zhang, Yu Guo, Fei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14782v1.pdf)  
  Keywords: dynamic, head, motion, deformation, gaussian splatting, face, semantic, avatar, geometry, animation, 3d gaussian, ar  
- **[NG-GS: NeRF-Guided 3D Gaussian Splatting Segmentation](https://arxiv.org/abs/2604.14706v1)**  
  Authors: Yi He, Tao Wang, Yi Jin, Congyan Lang, Yidong Li, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14706v1.pdf)  
  Keywords: segmentation, gaussian splatting, lightweight, 3d gaussian, nerf, ar, efficient  
- **[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1)**  
  Authors: Team HY-World, Chenjie Cao, Xuhui Zuo, Zhenwei Wang, Yisu Zhang, Junta Wu, Zhenyang Liu, Yuning Gong, Yang Liu, Bo Yuan, Chao Zhang, Coopers Li, Dongyuan Guo, Fan Yang, Haiyu Zhang, Hang Cao, Jianchen Zhu, Jiaxin Lin, Jie Xiao, Jihong Zhang, Junlin Yu, Lei Wang, Lifu Wang, Lilin Wang, Linus, Minghui Chen, Peng He, Penghao Zhao, Qi Chen, Rui Chen, Rui Shao, Sicong Liu, Wangchen Qin, Xiaochuan Niu, Xiang Yuan, Yi Sun, Yifei Tang, Yifu Sun, Yihang Lian, Yonghao Tan, Yuhong Liu, Yuyang Yin, Zhiyuan Min, Tengfei Wang, Chunchao Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.14268v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, understanding, lighting, 3d gaussian, ar, efficient  
- **[RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment](https://arxiv.org/abs/2604.13492v1)**  
  Authors: Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13492v1.pdf)  
  Keywords: slam, gaussian splatting, recognition, mapping, lighting, geometry, localization, ar  
- **[GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments](https://arxiv.org/abs/2604.12837v1)**  
  Authors: Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12837v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, gaussian splatting, slam, localization, semantic, mapping, 3d gaussian, ar  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: segmentation, gaussian splatting, understanding, semantic, urban scene, geometry, compact, 3d gaussian, ar  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: dynamic, gaussian splatting, robotics, ray tracing, lighting, semantic, tracking, 3d gaussian, ar, efficient  



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