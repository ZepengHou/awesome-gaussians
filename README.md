# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-08-17 00:39:57

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
- [Acceleration](#acceleration) (228 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (320 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (373 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (416 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (44 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (428 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (238 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (31 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (136 papers) - Papers about relighting and illumination effects in Gaussian Splatting
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

- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: ar, nerf, survey, geometry, dynamic, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: ar, recognition, survey, medical, motion, compact, neural rendering, autonomous driving, gaussian splatting, vr, 4d, 3d gaussian, 3d reconstruction  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: ar, animation, geometry, survey, mapping, gaussian splatting  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: ar, slam, geometry, survey, tracking, motion, efficient, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: ar, survey, gaussian splatting, vr, 3d gaussian  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ar, survey, ray tracing, mapping, gaussian splatting, 3d gaussian  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: ar, slam, survey, face, tracking, motion, localization, dynamic, mapping, gaussian splatting, 3d gaussian, efficient  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, survey, robotics, gaussian splatting, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: ar, nerf, geometry, survey, gaussian splatting, 3d gaussian, efficient  

### Acceleration

*Showing the latest 50 out of 228 papers*

- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v1)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v1.pdf)  
  Keywords: ar, geometry, fast, localization, gaussian splatting, 3d gaussian, outdoor  
- **[Compact Feed-Forward 3D Gaussians via Saliency-Guided Primitive Merging](https://arxiv.org/abs/2608.10712v1)**  
  Authors: Tim-Felix Fassch, Jochen Kall, Cyrill Stachniss  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10712v1.pdf)  
  Keywords: ar, segmentation, fast, compact, gaussian splatting, 3d gaussian, efficient  
- **[ERF-GS: Reconstructing Fast Motion from Disjoint Event-RGB Viewpoints](https://arxiv.org/abs/2608.08531v1)**  
  Authors: Xiaoyang Bai, Zhenyang Li, Weiwei Xu, Edmund Y. Lam, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08531v1.pdf)  
  Keywords: ar, nerf, motion, fast, dynamic, gaussian splatting, 4d, 3d gaussian  
- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: ar, geometry, motion, gaussian splatting, real-time rendering, 3d gaussian  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: ar, compression, high-fidelity, fast, compact, mapping, gaussian splatting, real-time rendering, vr, 3d gaussian, efficient  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: ar, geometry, motion, fast, dynamic, head, gaussian splatting, avatar, 3d gaussian  
- **[FAST-GS: Frequency Aware Space-time Gaussian Splatting for Photorealistic Dynamic Novel View Synthesis](https://arxiv.org/abs/2608.01958v2)**  
  Authors: Zhengyang Zhang, Ziyu Lu, PengCheng Li, Hongbo Duan, Yi Liu, Pengting Luo, Peiyu Zhuang, Xinghui Li, Shaohua Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01958v2.pdf)  
  Keywords: ar, motion, fast, efficient, dynamic, gaussian splatting, real-time rendering, 4d, 3d reconstruction  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: ar, animation, geometry, face, high-fidelity, motion, efficient rendering, gaussian splatting, 3d gaussian, efficient  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, sparse-view, dynamic, gaussian splatting, real-time rendering, 4d, efficient  
- **[Stipple: Real-Time Incremental Gaussian Splatting with Visual-Inertial Tracking](https://arxiv.org/abs/2608.00931v1)**  
  Authors: Kilian Northoff, Mateo de Mayo, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00931v1.pdf)  
  Keywords: ar, slam, tracking, robotics, 3d reconstruction, efficient rendering, localization, mapping, gaussian splatting, 3d gaussian, efficient  

### Applications

*Showing the latest 50 out of 994 papers*

- **[GS$^{2}$CI: Robust Gaussian Splatting For Snapshot Compressive Imaging via Large Vision Model Priors](https://arxiv.org/abs/2608.13502v1)**  
  Authors: Yanming Yang, Chenxi Song, Ping Wang, Xin Yuan, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13502v1.pdf)  
  Keywords: ar, motion, gaussian splatting, 3d gaussian, efficient  
- **[Splat-based Metal Artifact Reduction in Cone-Beam CT via Polychromatic Modeling](https://arxiv.org/abs/2608.13159v1)**  
  Authors: Kiseok Choi, Inchul Kim, Jaemin Cho, Hyeongjun Cho, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, efficient  
- **[ProbSplat: Efficient Probabilistic Hardware for Gaussian Splatting in 3D Scene Reconstruction](https://arxiv.org/abs/2608.13143v1)**  
  Authors: Siddarth Gottumukkula, M P Samartha, Vedant Pahariya, Priyanshi Jain, Amit Ranjan Trivedi, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13143v1.pdf)  
  Keywords: ar, robotics, gaussian splatting, vr, efficient  
- **[HumanoidVLN: A Physics-Grounded Simulator and Benchmark for Vision-Language Navigation Across Diverse Humanoid Embodiments](https://arxiv.org/abs/2608.12860v1)**  
  Authors: Quan-Dung Pham, Anh Dao, The-Anh Nguyen, Minh Nguyen-Dinh, Phuong Nam Dang, Tri Pham, Hung Tran, Bach Dao, Tuyen P. Le, Truong Nguyen, Quan Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.12860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humanoid-vln.github.io/.)  
  Keywords: ar, motion, human, dynamic, gaussian splatting, body, 3d gaussian  
- **[Seed2GS: Camera-Free, Training-Free Object Extraction from 3D Gaussian Scenes via a Single Reference-View Grounding](https://arxiv.org/abs/2608.11928v1)**  
  Authors: Zongjian Ding, Yudong Gao, Jiale Liu, Xinglin Yu, Junxing Ren, Dong Wei, Yajing Chen, Shan Huang, Mingjun Cheng, Min Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11928v1.pdf)  
  Keywords: ar, tracking, gaussian splatting, 3d gaussian  
- **[CausalSplat: Towards Comprehensive Hierarchical Reasoning in 3D Gaussian Splatting](https://arxiv.org/abs/2608.11150v2)**  
  Authors: Jiayu Ding, Meilu Song, Yun Chen, Wei Gao, Ge Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11150v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiayuding031020.github.io/CausalSplat)  
  Keywords: ar, understanding, segmentation, gaussian splatting, 3d gaussian  
- **[WildFireGS: Physics-Based Wildfire Simulation in Large-Scale Semantics-Enriched Gaussian Splatting Forest Scenes](https://arxiv.org/abs/2608.11100v1)**  
  Authors: Nienke Driessen, Joris Rijsdijk, Sören Pirk, Wojtek Palubicki, Dominik L. Michels, Michael Weinmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11100v1.pdf)  
  Keywords: ar, dynamic, gaussian splatting, semantic, 3d gaussian  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v1)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v1.pdf)  
  Keywords: ar, geometry, fast, localization, gaussian splatting, 3d gaussian, outdoor  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: ar, face, few-shot, localization, gaussian splatting, semantic, 3d gaussian  
- **[Compact Feed-Forward 3D Gaussians via Saliency-Guided Primitive Merging](https://arxiv.org/abs/2608.10712v1)**  
  Authors: Tim-Felix Fassch, Jochen Kall, Cyrill Stachniss  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10712v1.pdf)  
  Keywords: ar, segmentation, fast, compact, gaussian splatting, 3d gaussian, efficient  

### Avatar Generation

*Showing the latest 50 out of 320 papers*

- **[HumanoidVLN: A Physics-Grounded Simulator and Benchmark for Vision-Language Navigation Across Diverse Humanoid Embodiments](https://arxiv.org/abs/2608.12860v1)**  
  Authors: Quan-Dung Pham, Anh Dao, The-Anh Nguyen, Minh Nguyen-Dinh, Phuong Nam Dang, Tri Pham, Hung Tran, Bach Dao, Tuyen P. Le, Truong Nguyen, Quan Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.12860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humanoid-vln.github.io/.)  
  Keywords: ar, motion, human, dynamic, gaussian splatting, body, 3d gaussian  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: ar, face, few-shot, localization, gaussian splatting, semantic, 3d gaussian  
- **[Visual Geometry Foundation-Aware Gaussians for Single-Frame Surround-View Driving Reconstruction](https://arxiv.org/abs/2608.10682v1)**  
  Authors: Junhong Lin, Jinlong Wang, Xianda Guo, Yanlun Peng, Wei Zheng, Guoqing Liu, Hanli Wang, Tiesong Zhao, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10682v1.pdf)  
  Keywords: ar, geometry, face, gaussian splatting, 3d gaussian  
- **[Gaussian Sculpting: End-to-End Controllable Surface Reconstruction via Field Optimization](https://arxiv.org/abs/2608.10602v1)**  
  Authors: Ke Jiaxin, Juncheng Liu, Yi Wang, Zhouhui Lian, Bin Liu, Shengfa Wang, Xiangjia He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10602v1.pdf)  
  Keywords: ar, geometry, face, gaussian splatting, 3d gaussian  
- **[EvTrajGS: Accurate and Efficient 3D Gaussian Splatting from Unposed Event Streams](https://arxiv.org/abs/2608.08585v1)**  
  Authors: Zixuan Chen, Jiakai Zhang, Junhao Dong, Guangcong Wang, Jianhuang Lai, Yew-Soon Ong, Xiaohua Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08585v1.pdf)  
  Keywords: ar, slam, tracking, motion, efficient, dynamic, mapping, head, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[XClipGS: Exact Half-Space Clipping for Medical Volume Gaussian Splatting](https://arxiv.org/abs/2608.07760v1)**  
  Authors: Zhongpai Gao, Benjamin Planche, Meng Zheng, Anwesa Choudhuri, Chaoyi Zhou, Terrence Chen, Ziyan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.07760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gaozhongpai.github.io/XClipGS/)  
  Keywords: ar, gaussian splatting, medical, face  
- **[AdvTiles: Physical Adversarial Camouflage Clothing against Person Detectors via Learnable Tiles](https://arxiv.org/abs/2608.06801v1)**  
  Authors: Jinlei Wang, Jiahuan Long, Mingkai Sun, Yafei Guo, Yuanhao Huang, Ming Wang, Junqi Wu, Jiacheng Hou, Hongbo Chen, Xingxing Wei, Tingsong Jiang, Wen Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06801v1.pdf)  
  Keywords: ar, illumination, gaussian splatting, body, 3d gaussian  
- **[GSBF: Gaussian Splatting for Environment-Aware Beamforming](https://arxiv.org/abs/2608.05896v1)**  
  Authors: Yijie Bian, Wei Guo, Zixin Wang, Shenghui Song, Jun Zhang, Khaled B. Letaief  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05896v1.pdf)  
  Keywords: ar, geometry, head, gaussian splatting, 3d gaussian  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: ar, geometry, compression, face, compact, gaussian splatting, 3d gaussian  
- **[CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer](https://arxiv.org/abs/2608.05482v1)**  
  Authors: Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05482v1.pdf)  
  Keywords: ar, face, segmentation, gaussian splatting, semantic  

### Dynamic Scene

*Showing the latest 50 out of 373 papers*

- **[GS$^{2}$CI: Robust Gaussian Splatting For Snapshot Compressive Imaging via Large Vision Model Priors](https://arxiv.org/abs/2608.13502v1)**  
  Authors: Yanming Yang, Chenxi Song, Ping Wang, Xin Yuan, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13502v1.pdf)  
  Keywords: ar, motion, gaussian splatting, 3d gaussian, efficient  
- **[HumanoidVLN: A Physics-Grounded Simulator and Benchmark for Vision-Language Navigation Across Diverse Humanoid Embodiments](https://arxiv.org/abs/2608.12860v1)**  
  Authors: Quan-Dung Pham, Anh Dao, The-Anh Nguyen, Minh Nguyen-Dinh, Phuong Nam Dang, Tri Pham, Hung Tran, Bach Dao, Tuyen P. Le, Truong Nguyen, Quan Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.12860v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humanoid-vln.github.io/.)  
  Keywords: ar, motion, human, dynamic, gaussian splatting, body, 3d gaussian  
- **[WildFireGS: Physics-Based Wildfire Simulation in Large-Scale Semantics-Enriched Gaussian Splatting Forest Scenes](https://arxiv.org/abs/2608.11100v1)**  
  Authors: Nienke Driessen, Joris Rijsdijk, Sören Pirk, Wojtek Palubicki, Dominik L. Michels, Michael Weinmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11100v1.pdf)  
  Keywords: ar, dynamic, gaussian splatting, semantic, 3d gaussian  
- **[EvTrajGS: Accurate and Efficient 3D Gaussian Splatting from Unposed Event Streams](https://arxiv.org/abs/2608.08585v1)**  
  Authors: Zixuan Chen, Jiakai Zhang, Junhao Dong, Guangcong Wang, Jianhuang Lai, Yew-Soon Ong, Xiaohua Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08585v1.pdf)  
  Keywords: ar, slam, tracking, motion, efficient, dynamic, mapping, head, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[ERF-GS: Reconstructing Fast Motion from Disjoint Event-RGB Viewpoints](https://arxiv.org/abs/2608.08531v1)**  
  Authors: Xiaoyang Bai, Zhenyang Li, Weiwei Xu, Edmund Y. Lam, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08531v1.pdf)  
  Keywords: ar, nerf, motion, fast, dynamic, gaussian splatting, 4d, 3d gaussian  
- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: ar, geometry, motion, gaussian splatting, real-time rendering, 3d gaussian  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: ar, nerf, geometry, tracking, motion, segmentation, human, dynamic, gaussian splatting, 3d gaussian, efficient  
- **[UniWorld-View: Large-Baseline View Synthesis via Video Diffusion Models](https://arxiv.org/abs/2608.04701v1)**  
  Authors: Haiyang Zhou, Wangbo Yu, Chaoran Feng, Xunyu Zhou, Yonghong Tian, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04701v1.pdf)  
  Keywords: ar, nerf, high-fidelity, motion, dynamic, gaussian splatting, 3d gaussian  
- **[PD-GS: Phoneme-Driven 3DGS for Audio-Driven Talking Heads](https://arxiv.org/abs/2608.05218v1)**  
  Authors: Ao Fu, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05218v1.pdf)  
  Keywords: ar, geometry, motion, fast, dynamic, head, gaussian splatting, avatar, 3d gaussian  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: ar, compression, high-fidelity, motion, compact, lightweight, dynamic, gaussian splatting, 4d  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: ar, face, few-shot, localization, gaussian splatting, semantic, 3d gaussian  
- **[TRACE-GS: On-Policy Trajectory Distillation with Privileged Geometric Conditioning for Sparse-View 3DGS Restoration](https://arxiv.org/abs/2608.10286v1)**  
  Authors: Linlian Jiang, Yuchen Xi, Sadman Rakib Pinon, Ruigang Yang, Yang Wang, Xinxin Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10286v1.pdf)  
  Keywords: ar, geometry, sparse-view, gaussian splatting, 3d gaussian  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: ar, geometry, few-shot, compact, localization, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[CLEAR: Conflict-aware Learning via Evidence-guided Adaptive Routing for Unified Sparse-View 3D Gaussian Super-Resolution](https://arxiv.org/abs/2608.02206v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02206v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, sparse-view  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: ar, geometry, sparse-view, dynamic, gaussian splatting, real-time rendering, 4d, efficient  
- **[Manifold-GS: Certified Hybrid Assets via Varifold-Conservative Gaussian Splatting](https://arxiv.org/abs/2608.00214v1)**  
  Authors: Boyang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.00214v1.pdf)  
  Keywords: ar, face, geometry, sparse-view, gaussian splatting, 3d gaussian  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: sparse view, ar, geometry, motion, illumination, localization, gaussian splatting, 3d gaussian  
- **[Posterior Variance Is a Constraint Map, Not an Error Map: Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v2)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v2.pdf)  
  Keywords: ar, fast, gaussian splatting, sparse-view  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: ar, geometry, high-fidelity, neural rendering, sparse-view, gaussian splatting, semantic, 3d gaussian  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: sparse view, ar, geometry, gaussian splatting, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 416 papers*

- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v1)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v1.pdf)  
  Keywords: ar, geometry, fast, localization, gaussian splatting, 3d gaussian, outdoor  
- **[Visual Geometry Foundation-Aware Gaussians for Single-Frame Surround-View Driving Reconstruction](https://arxiv.org/abs/2608.10682v1)**  
  Authors: Junhong Lin, Jinlong Wang, Xianda Guo, Yanlun Peng, Wei Zheng, Guoqing Liu, Hanli Wang, Tiesong Zhao, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10682v1.pdf)  
  Keywords: ar, geometry, face, gaussian splatting, 3d gaussian  
- **[Gaussian Sculpting: End-to-End Controllable Surface Reconstruction via Field Optimization](https://arxiv.org/abs/2608.10602v1)**  
  Authors: Ke Jiaxin, Juncheng Liu, Yi Wang, Zhouhui Lian, Bin Liu, Shengfa Wang, Xiangjia He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10602v1.pdf)  
  Keywords: ar, geometry, face, gaussian splatting, 3d gaussian  
- **[TRACE-GS: On-Policy Trajectory Distillation with Privileged Geometric Conditioning for Sparse-View 3DGS Restoration](https://arxiv.org/abs/2608.10286v1)**  
  Authors: Linlian Jiang, Yuchen Xi, Sadman Rakib Pinon, Ruigang Yang, Yang Wang, Xinxin Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10286v1.pdf)  
  Keywords: ar, geometry, sparse-view, gaussian splatting, 3d gaussian  
- **[EndoMD-SLAM: Endoscopic Gaussian Splatting SLAM under Optical Degradation with Memory and Static-Transient Decomposition](https://arxiv.org/abs/2608.08949v1)**  
  Authors: Nuo Chen, Kangqi Ni, Lulin Liu, Joga Ivatury, Ying Ding, Farshid Alambeigi, Tianlong Chen, Zhiwen Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08949v1.pdf)  
  Keywords: ar, slam, geometry, tracking, localization, mapping, gaussian splatting, 3d reconstruction  
- **[EvTrajGS: Accurate and Efficient 3D Gaussian Splatting from Unposed Event Streams](https://arxiv.org/abs/2608.08585v1)**  
  Authors: Zixuan Chen, Jiakai Zhang, Junhao Dong, Guangcong Wang, Jianhuang Lai, Yew-Soon Ong, Xiaohua Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08585v1.pdf)  
  Keywords: ar, slam, tracking, motion, efficient, dynamic, mapping, head, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[InstanceSplat: Instance-Aware Feed-Forward 3D Gaussian Splatting for Scene Understanding](https://arxiv.org/abs/2608.07144v1)**  
  Authors: Minchao Jiang, Xiaoxuan Ma, Shunyu Jia, Haoru Wang, Zhang Liang, Wentao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.07144v1.pdf)  
  Keywords: ar, understanding, geometry, segmentation, 3d reconstruction, gaussian splatting, semantic, 3d gaussian, efficient  
- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: ar, geometry, motion, gaussian splatting, real-time rendering, 3d gaussian  
- **[GSBF: Gaussian Splatting for Environment-Aware Beamforming](https://arxiv.org/abs/2608.05896v1)**  
  Authors: Yijie Bian, Wei Guo, Zixin Wang, Shenghui Song, Jun Zhang, Khaled B. Letaief  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05896v1.pdf)  
  Keywords: ar, geometry, head, gaussian splatting, 3d gaussian  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: ar, geometry, compression, face, compact, gaussian splatting, 3d gaussian  

### Large Scene

- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v1)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v1.pdf)  
  Keywords: ar, geometry, fast, localization, gaussian splatting, 3d gaussian, outdoor  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: ar, understanding, segmentation, localization, gaussian splatting, semantic, 3d gaussian, outdoor, efficient  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: ar, slam, geometry, tracking, lightweight, localization, mapping, gaussian splatting, 3d gaussian, outdoor  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: ar, animation, motion, deformation, dynamic, gaussian splatting, 3d gaussian, outdoor  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: ar, recognition, slam, motion, fast, large scene, gaussian splatting, real-time rendering, 3d gaussian, efficient  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: ar, slam, geometry, tracking, mapping, gaussian splatting, 3d gaussian, outdoor  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, 3d gaussian, outdoor  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: sparse view, ar, geometry, face, large scene, gaussian splatting, 3d gaussian, efficient  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: ar, deformation, human, 3d gaussian, outdoor  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: ar, geometry, mapping, gaussian splatting, 3d gaussian, outdoor  

### Model Compression

*Showing the latest 50 out of 428 papers*

- **[GS$^{2}$CI: Robust Gaussian Splatting For Snapshot Compressive Imaging via Large Vision Model Priors](https://arxiv.org/abs/2608.13502v1)**  
  Authors: Yanming Yang, Chenxi Song, Ping Wang, Xin Yuan, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13502v1.pdf)  
  Keywords: ar, motion, gaussian splatting, 3d gaussian, efficient  
- **[Splat-based Metal Artifact Reduction in Cone-Beam CT via Polychromatic Modeling](https://arxiv.org/abs/2608.13159v1)**  
  Authors: Kiseok Choi, Inchul Kim, Jaemin Cho, Hyeongjun Cho, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, efficient  
- **[ProbSplat: Efficient Probabilistic Hardware for Gaussian Splatting in 3D Scene Reconstruction](https://arxiv.org/abs/2608.13143v1)**  
  Authors: Siddarth Gottumukkula, M P Samartha, Vedant Pahariya, Priyanshi Jain, Amit Ranjan Trivedi, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13143v1.pdf)  
  Keywords: ar, robotics, gaussian splatting, vr, efficient  
- **[Compact Feed-Forward 3D Gaussians via Saliency-Guided Primitive Merging](https://arxiv.org/abs/2608.10712v1)**  
  Authors: Tim-Felix Fassch, Jochen Kall, Cyrill Stachniss  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10712v1.pdf)  
  Keywords: ar, segmentation, fast, compact, gaussian splatting, 3d gaussian, efficient  
- **[JSGS: JPEG State-Guided Supervision for 3D Gaussian Splatting from Mixed-Quality Views](https://arxiv.org/abs/2608.08659v1)**  
  Authors: Jinhua Cui, Anhong Wang, Kai Hu, Donghan Bu, Peihao Li, Tammam Tillo, Hao Jing, Shiao Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08659v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, compression  
- **[EvTrajGS: Accurate and Efficient 3D Gaussian Splatting from Unposed Event Streams](https://arxiv.org/abs/2608.08585v1)**  
  Authors: Zixuan Chen, Jiakai Zhang, Junhao Dong, Guangcong Wang, Jianhuang Lai, Yew-Soon Ong, Xiaohua Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08585v1.pdf)  
  Keywords: ar, slam, tracking, motion, efficient, dynamic, mapping, head, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[InstanceSplat: Instance-Aware Feed-Forward 3D Gaussian Splatting for Scene Understanding](https://arxiv.org/abs/2608.07144v1)**  
  Authors: Minchao Jiang, Xiaoxuan Ma, Shunyu Jia, Haoru Wang, Zhang Liang, Wentao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.07144v1.pdf)  
  Keywords: ar, understanding, geometry, segmentation, 3d reconstruction, gaussian splatting, semantic, 3d gaussian, efficient  
- **[G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation](https://arxiv.org/abs/2608.05704v1)**  
  Authors: Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05704v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrick1159.github.io/gardGS-page/.)  
  Keywords: ar, geometry, compression, face, compact, gaussian splatting, 3d gaussian  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: ar, compression, high-fidelity, fast, compact, mapping, gaussian splatting, real-time rendering, vr, 3d gaussian, efficient  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: ar, geometry, few-shot, compact, localization, gaussian splatting, 3d gaussian, 3d reconstruction  

### Quality Enhancement

*Showing the latest 50 out of 238 papers*

- **[Splat-based Metal Artifact Reduction in Cone-Beam CT via Polychromatic Modeling](https://arxiv.org/abs/2608.13159v1)**  
  Authors: Kiseok Choi, Inchul Kim, Jaemin Cho, Hyeongjun Cho, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, efficient  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: ar, compression, high-fidelity, fast, compact, mapping, gaussian splatting, real-time rendering, vr, 3d gaussian, efficient  
- **[UniWorld-View: Large-Baseline View Synthesis via Video Diffusion Models](https://arxiv.org/abs/2608.04701v1)**  
  Authors: Haiyang Zhou, Wangbo Yu, Chaoran Feng, Xunyu Zhou, Yonghong Tian, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04701v1.pdf)  
  Keywords: ar, nerf, high-fidelity, motion, dynamic, gaussian splatting, 3d gaussian  
- **[ACA-GS: Adaptive-Capacity Anchored Gaussian Splatting for Compact Dynamic Radiance Fields](https://arxiv.org/abs/2608.04581v1)**  
  Authors: Seunghyeon Song, Joo Chan Lee, Chanung Park, Jun Young Jeong, Minseo Lee, Eunbyung Park, Jong Hwan Ko  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04581v1.pdf)  
  Keywords: ar, compression, high-fidelity, motion, compact, lightweight, dynamic, gaussian splatting, 4d  
- **[3D Gaussian Splatting and Mesh-Based Digital Twins: An Exploratory Study for Virtual Reality Tourism](https://arxiv.org/abs/2608.01969v1)**  
  Authors: Maximilian Warsinke, Francesco Vona, Abm Tariqul Islam, Tanja Kojić, Jan-Niklas Voigt-Antons, Sebastian Möller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01969v1.pdf)  
  Keywords: ar, understanding, high-fidelity, motion, gaussian splatting, vr, 3d gaussian  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: relighting, ar, compression, high-fidelity, neural rendering, illumination, autonomous driving, dynamic, lighting, gaussian splatting, semantic, 3d gaussian  
- **[G-Skin: Learning to Bind 3D Gaussians with Generative Visual Priors](https://arxiv.org/abs/2608.01726v1)**  
  Authors: Yuxin Yao, Kendong Liu, Shiqi Zhou, Jiazhi Xia, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01726v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yaoyx689.github.io/GSkin.html.)  
  Keywords: ar, animation, geometry, face, high-fidelity, motion, efficient rendering, gaussian splatting, 3d gaussian, efficient  
- **[QuerySplat: Decoupling Geometry and Appearance Representations in 3DGS Prediction](https://arxiv.org/abs/2608.01186v1)**  
  Authors: Yinglong Li, Donghui Shen, Xiaoyu Zhang, Zhichao Ye, Hongyu Wu, Aimin Hao, Guofeng Zhang, Haomin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01186v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://inspatio.github.io/querysplat.)  
  Keywords: ar, understanding, geometry, high-fidelity, efficient, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[SplatStream: Fine Granular Scalable Gaussian Splatting for Adaptive 3D Scene Streaming](https://arxiv.org/abs/2607.25971v2)**  
  Authors: Muhammad Talha, William Gordon, Sajid Umair, Zhu Li, Anique Akhtar, Joel Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25971v2.pdf)  
  Keywords: ar, lightweight, dynamic, high quality, gaussian splatting, real-time rendering, 3d gaussian  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: ar, face, high-fidelity, reflection, illumination  

### Ray Tracing

- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: relighting, ar, face, ray tracing, reflection, lighting, gaussian splatting, illumination, efficient  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: ar, geometry, face, ray tracing, high-fidelity, motion, human, reflection, dynamic, gaussian splatting, 3d gaussian  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: ar, ray tracing, fast, gaussian splatting, 3d gaussian  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: ar, geometry, ray tracing, fast, reflection, gaussian splatting, path tracing, real-time rendering, 3d gaussian, efficient  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: ar, geometry, efficient, illumination, gaussian splatting, global illumination, 3d gaussian, 3d reconstruction  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: ar, high-fidelity, gaussian splatting, global illumination, illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: ar, geometry, ray tracing, segmentation, reflection, gaussian splatting, semantic, 3d gaussian, efficient  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: ar, face, fast, shadow, illumination, gaussian splatting, global illumination, 3d gaussian  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ray casting, ar, gaussian splatting, 3d gaussian  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: ar, geometry, ray tracing, high-fidelity, gaussian splatting, 3d gaussian  

### Relighting

*Showing the latest 50 out of 136 papers*

- **[AdvTiles: Physical Adversarial Camouflage Clothing against Person Detectors via Learnable Tiles](https://arxiv.org/abs/2608.06801v1)**  
  Authors: Jinlei Wang, Jiahuan Long, Mingkai Sun, Yafei Guo, Yuanhao Huang, Ming Wang, Junqi Wu, Jiacheng Hou, Hongbo Chen, Xingxing Wei, Tingsong Jiang, Wen Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06801v1.pdf)  
  Keywords: ar, illumination, gaussian splatting, body, 3d gaussian  
- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: ar, nerf, geometry, illumination, autonomous driving, gaussian splatting, 3d gaussian  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: relighting, ar, compression, high-fidelity, neural rendering, illumination, autonomous driving, dynamic, lighting, gaussian splatting, semantic, 3d gaussian  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: ar, face, high-fidelity, reflection, illumination  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: ar, illumination, gaussian splatting, 3d gaussian, efficient  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: relighting, ar, face, ray tracing, reflection, lighting, gaussian splatting, illumination, efficient  
- **[Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis](https://arxiv.org/abs/2607.22147v1)**  
  Authors: Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22147v1.pdf)  
  Keywords: sparse view, ar, geometry, motion, illumination, localization, gaussian splatting, 3d gaussian  
- **[ECoNGS: Efficient Compressive Neural Gaussian Splats for Volume Visualization](https://arxiv.org/abs/2607.18466v1)**  
  Authors: Kaiyuan Tang, Chaoli Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18466v1.pdf)  
  Keywords: ar, lightweight, compact, dynamic, lighting, gaussian splatting, vr, efficient  
- **[Splat-based 3D Scene Reconstruction with Extreme Motion-blur](https://arxiv.org/abs/2607.16926v1)**  
  Authors: Hyeonjoong Jang, Dongyoung Choi, Donggun Kim, Woohyun Kang, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.16926v1.pdf)  
  Keywords: ar, geometry, robotics, motion, fast, illumination, mapping, lighting, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: ar, geometry, face, ray tracing, high-fidelity, motion, human, reflection, dynamic, gaussian splatting, 3d gaussian  

### SLAM

*Showing the latest 50 out of 161 papers*

- **[Seed2GS: Camera-Free, Training-Free Object Extraction from 3D Gaussian Scenes via a Single Reference-View Grounding](https://arxiv.org/abs/2608.11928v1)**  
  Authors: Zongjian Ding, Yudong Gao, Jiale Liu, Xinglin Yu, Junxing Ren, Dong Wei, Yajing Chen, Shan Huang, Mingjun Cheng, Min Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11928v1.pdf)  
  Keywords: ar, tracking, gaussian splatting, 3d gaussian  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v1)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v1.pdf)  
  Keywords: ar, geometry, fast, localization, gaussian splatting, 3d gaussian, outdoor  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: ar, face, few-shot, localization, gaussian splatting, semantic, 3d gaussian  
- **[EndoMD-SLAM: Endoscopic Gaussian Splatting SLAM under Optical Degradation with Memory and Static-Transient Decomposition](https://arxiv.org/abs/2608.08949v1)**  
  Authors: Nuo Chen, Kangqi Ni, Lulin Liu, Joga Ivatury, Ying Ding, Farshid Alambeigi, Tianlong Chen, Zhiwen Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08949v1.pdf)  
  Keywords: ar, slam, geometry, tracking, localization, mapping, gaussian splatting, 3d reconstruction  
- **[EvTrajGS: Accurate and Efficient 3D Gaussian Splatting from Unposed Event Streams](https://arxiv.org/abs/2608.08585v1)**  
  Authors: Zixuan Chen, Jiakai Zhang, Junhao Dong, Guangcong Wang, Jianhuang Lai, Yew-Soon Ong, Xiaohua Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08585v1.pdf)  
  Keywords: ar, slam, tracking, motion, efficient, dynamic, mapping, head, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: ar, compression, high-fidelity, fast, compact, mapping, gaussian splatting, real-time rendering, vr, 3d gaussian, efficient  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: ar, geometry, few-shot, compact, localization, gaussian splatting, 3d gaussian, 3d reconstruction  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: ar, nerf, geometry, tracking, motion, segmentation, human, dynamic, gaussian splatting, 3d gaussian, efficient  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: ar, understanding, segmentation, localization, gaussian splatting, semantic, 3d gaussian, outdoor, efficient  
- **[TRACE: Ergodic Trajectory Optimization for Active Scene Reconstruction](https://arxiv.org/abs/2608.02304v3)**  
  Authors: Ziyue Zheng, Linli Shi, Bingkun He, Wen Jiang, Ziyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02304v3.pdf)  
  Keywords: ar, mapping, efficient  

### Scene Understanding

*Showing the latest 50 out of 228 papers*

- **[CausalSplat: Towards Comprehensive Hierarchical Reasoning in 3D Gaussian Splatting](https://arxiv.org/abs/2608.11150v2)**  
  Authors: Jiayu Ding, Meilu Song, Yun Chen, Wei Gao, Ge Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11150v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiayuding031020.github.io/CausalSplat)  
  Keywords: ar, understanding, segmentation, gaussian splatting, 3d gaussian  
- **[WildFireGS: Physics-Based Wildfire Simulation in Large-Scale Semantics-Enriched Gaussian Splatting Forest Scenes](https://arxiv.org/abs/2608.11100v1)**  
  Authors: Nienke Driessen, Joris Rijsdijk, Sören Pirk, Wojtek Palubicki, Dominik L. Michels, Michael Weinmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11100v1.pdf)  
  Keywords: ar, dynamic, gaussian splatting, semantic, 3d gaussian  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: ar, face, few-shot, localization, gaussian splatting, semantic, 3d gaussian  
- **[Compact Feed-Forward 3D Gaussians via Saliency-Guided Primitive Merging](https://arxiv.org/abs/2608.10712v1)**  
  Authors: Tim-Felix Fassch, Jochen Kall, Cyrill Stachniss  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10712v1.pdf)  
  Keywords: ar, segmentation, fast, compact, gaussian splatting, 3d gaussian, efficient  
- **[InstanceSplat: Instance-Aware Feed-Forward 3D Gaussian Splatting for Scene Understanding](https://arxiv.org/abs/2608.07144v1)**  
  Authors: Minchao Jiang, Xiaoxuan Ma, Shunyu Jia, Haoru Wang, Zhang Liang, Wentao Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.07144v1.pdf)  
  Keywords: ar, understanding, geometry, segmentation, 3d reconstruction, gaussian splatting, semantic, 3d gaussian, efficient  
- **[CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer](https://arxiv.org/abs/2608.05482v1)**  
  Authors: Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05482v1.pdf)  
  Keywords: ar, face, segmentation, gaussian splatting, semantic  
- **[RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)**  
  Authors: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04842v1.pdf)  
  Keywords: ar, nerf, geometry, tracking, motion, segmentation, human, dynamic, gaussian splatting, 3d gaussian, efficient  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: ar, understanding, segmentation, localization, gaussian splatting, semantic, 3d gaussian, outdoor, efficient  
- **[Super-Gaussian: Interactive Scene Editing for 3D Gaussian Splatting and NLI-Based Volume Visualization in Virtual Reality](https://arxiv.org/abs/2608.04475v1)**  
  Authors: Suemin Jeon, Kaiyuan Tang, Chaoli Wang, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04475v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smin0136.github.io/super-gaussian-project/)  
  Keywords: ar, medical, motion, segmentation, gaussian splatting, vr, semantic, 3d gaussian, efficient  
- **[3DGSI-Assessor: A Large-Scale Dataset and An LMM-based Method for 3D Gaussian Splatting Image Quality Assessment](https://arxiv.org/abs/2608.03279v1)**  
  Authors: Yuke Xing, Jiarui Wang, William Gordon, Zhu Li, Guangtao Zhai, Yiling Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.03279v1.pdf)  
  Keywords: ar, geometry, compression, face, gaussian splatting, semantic, 3d gaussian  



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