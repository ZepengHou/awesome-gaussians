# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-05-18 02:27:34

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
- [Acceleration](#acceleration) (226 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (344 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (377 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (82 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (392 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (46 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (439 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (242 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (135 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (149 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (223 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: survey, 3d reconstruction, efficient, geometry, gaussian splatting, ar, tracking, 3d gaussian, motion, slam  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, ar, gaussian splatting, 3d gaussian, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: survey, mapping, gaussian splatting, ar, 3d gaussian, ray tracing  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, localization, dynamic, efficient, mapping, face, gaussian splatting, ar, tracking, 3d gaussian, motion, slam  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, ar, gaussian splatting, robotics, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, efficient, geometry, gaussian splatting, ar, nerf, 3d gaussian  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: survey, 3d reconstruction, dynamic, 4d, efficient, high-fidelity, gaussian splatting, ar, compact, 3d gaussian, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: survey, understanding, localization, mapping, gaussian splatting, ar, robotics, nerf, 3d gaussian, semantic, slam  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: survey, localization, efficient, mapping, high-fidelity, gaussian splatting, ar, robotics, 3d gaussian, semantic, slam  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v2)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: survey, fast, 4d, geometry, gaussian splatting, ar, nerf, 3d gaussian, motion  

### Acceleration

*Showing the latest 50 out of 226 papers*

- **[Eff-WRFGS: Efficient Wireless Radiance Field Using 3D Gaussian Splatting](https://arxiv.org/abs/2605.15324v1)**  
  Authors: Chenghong Bian, Meng Hua, Deniz Gunduz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15324v1.pdf)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, head, efficient rendering  
- **[Sparse Code Uplifting for Efficient 3D Language Gaussian Splatting](https://arxiv.org/abs/2605.13600v1)**  
  Authors: Lovre Antonio Budimir, Yushi Guan, Steve Ryhner, Sven Lončarić, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13600v1.pdf)  
  Keywords: understanding, fast, efficient, gaussian splatting, ar, compact, 3d gaussian, semantic  
- **[Z-Order Transformer for Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2605.13465v1)**  
  Authors: Can Wang, Lei Liu, Wei Jiang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13465v1.pdf)  
  Keywords: fast, efficient, gaussian splatting, ar, 3d gaussian, semantic  
- **[PointForward: Feedforward Driving Reconstruction through Point-Aligned Representations](https://arxiv.org/abs/2605.11594v1)**  
  Authors: Cheng Chi, Xianqi Wang, Hongcheng Luo, Mingfei Tu, Gangwei Xu, Zehan Zhang, Bing Wang, Guang Chen, Hangjun Ye, Sida Peng, Xin Yang, Haiyang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11594v1.pdf)  
  Keywords: fast, dynamic, high-fidelity, gaussian splatting, ar, autonomous driving, 3d gaussian, motion  
- **[3DGS$^3$: Joint Super Sampling and Frame Interpolation for Real-Time Large-Scale 3DGS Rendering](https://arxiv.org/abs/2605.11489v1)**  
  Authors: Yibo Zhao, Fan Gao, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11489v1.pdf)  
  Keywords: efficient, high-fidelity, face, gaussian splatting, ar, compact, 3d gaussian, lightweight, acceleration  
- **[PG-3DGS: Optimizing 3D Gaussian Splatting to Satisfy Physics Objectives](https://arxiv.org/abs/2605.11266v1)**  
  Authors: Zachary Lee, Maxwell Jacobson, Yexiang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11266v1.pdf)  
  Keywords: understanding, fast, dynamic, high-fidelity, gaussian splatting, ar, 3d gaussian  
- **[PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.10307v1)**  
  Authors: Yinan Deng, Jianyu Dou, Jiahui Wang, Jingyu Zhao, Yi Yang, Yufeng Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10307v1.pdf)  
  Keywords: fast, dynamic, 4d, high-fidelity, gaussian splatting, ar, robotics, deformation, tracking, motion, segmentation  
- **[CAGS: Color-Adaptive Volumetric Video Streaming with Dynamic 3D Gaussian Splatting](https://arxiv.org/abs/2605.09279v1)**  
  Authors: Daheng Yin, Yili Jin, Jianxin Shi, Isaac Ding, Miao Zhang, Fangxin Wang, Zhaowu Huang, Cong Zhang, Jiangchuan Liu, Fang Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09279v1.pdf)  
  Keywords: fast, dynamic, face, gaussian splatting, ar, 3d gaussian, compression  
- **[AdpSplit: Error-Driven Adaptive Splitting for Faster Geometry Discovery in 3D Gaussian Splatting](https://arxiv.org/abs/2605.06876v1)**  
  Authors: Yongjae Lee, Jingxing Li, Abhay Kumar Yadav, Rama Chellappa, Deliang Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.06876v1.pdf)  
  Keywords: fast, efficient, geometry, gaussian splatting, ar, nerf, 3d gaussian, acceleration  
- **[ULF-Loc: Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting](https://arxiv.org/abs/2605.04730v1)**  
  Authors: Yingdong Gu, Shaocheng Yan, Zhenjun Zhao, Yuan Kou, Jianxin Luo, Pengcheng Shi, Jiayuan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.04730v1.pdf)  
  Keywords: localization, efficient, geometry, gaussian splatting, ar, 3d gaussian, efficient rendering  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Smart target point control for Gaussian Splatting methods](https://arxiv.org/abs/2605.16158v1)**  
  Authors: Pratik Singh Bisht, Andreas Kolb  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16158v1.pdf)  
  Keywords: ar, gaussian splatting  
- **[Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting](https://arxiv.org/abs/2605.16065v1)**  
  Authors: Raushan Joshi, Jean-Yves Guillemaut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16065v1.pdf)  
  Keywords: high quality, gaussian splatting, ar, robotics, 3d gaussian, vr, segmentation  
- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, segmentation  
- **[Learn2Splat: Extending the Horizon of Learned 3DGS Optimization](https://arxiv.org/abs/2605.15760v1)**  
  Authors: Naama Pearl, Stefano Esposito, Haofei Xu, Amit Peleg, Patricia Gschossmann, Lorenzo Porzi, Peter Kontschieder, Gerard Pons-Moll, Andreas Geiger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://naamapearl.github.io/learn2splat)  
  Keywords: 3d gaussian, ar, gaussian splatting, efficient  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 3d gaussian, semantic, lighting  
- **[Eff-WRFGS: Efficient Wireless Radiance Field Using 3D Gaussian Splatting](https://arxiv.org/abs/2605.15324v1)**  
  Authors: Chenghong Bian, Meng Hua, Deniz Gunduz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15324v1.pdf)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, head, efficient rendering  
- **[3D Skew-Normal Splatting](https://arxiv.org/abs/2605.15010v2)**  
  Authors: Xiangru Wu, Ke Fan, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15010v2.pdf)  
  Keywords: efficient, face, gaussian splatting, ar, compact, 3d gaussian  
- **[Denoising-GS: Gaussian Splatting with Spatial-aware Denoising](https://arxiv.org/abs/2605.14880v1)**  
  Authors: Qingyuan Zhou, Xinyi Liu, Weidong Yang, Ning Wang, Shuquan Ye, Ben Fei, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14880v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, compact, 3d gaussian, motion  
- **[Efficient Dense Matching for Enhanced Gaussian Splatting Using AV1 Motion Vectors](https://arxiv.org/abs/2605.14629v1)**  
  Authors: Julien Zouein, Vibhoothi Vibhoothi, François Pitié, Anil Kokaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14629v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sigmedia.tv/AV1-3DGS.github.io/)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, motion, head  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  

### Avatar Generation

*Showing the latest 50 out of 344 papers*

- **[Eff-WRFGS: Efficient Wireless Radiance Field Using 3D Gaussian Splatting](https://arxiv.org/abs/2605.15324v1)**  
  Authors: Chenghong Bian, Meng Hua, Deniz Gunduz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15324v1.pdf)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, head, efficient rendering  
- **[3D Skew-Normal Splatting](https://arxiv.org/abs/2605.15010v2)**  
  Authors: Xiangru Wu, Ke Fan, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15010v2.pdf)  
  Keywords: efficient, face, gaussian splatting, ar, compact, 3d gaussian  
- **[Efficient Dense Matching for Enhanced Gaussian Splatting Using AV1 Motion Vectors](https://arxiv.org/abs/2605.14629v1)**  
  Authors: Julien Zouein, Vibhoothi Vibhoothi, François Pitié, Anil Kokaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14629v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sigmedia.tv/AV1-3DGS.github.io/)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, motion, head  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[Revisiting Photometric Ambiguity for Accurate Gaussian-Splatting Surface Reconstruction](https://arxiv.org/abs/2605.12494v1)**  
  Authors: Jiahe Li, Jiawei Zhang, Xiao Bai, Jin Zheng, Xiaohan Yu, Lin Gu, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12494v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fictionarry.github.io/AmbiSuR-Proj/)  
  Keywords: 3d reconstruction, face, geometry, gaussian splatting, ar  
- **[3D Gaussian Splatting for Efficient Retrospective Dynamic Scene Novel View Synthesis with a Standardized Benchmark](https://arxiv.org/abs/2605.12437v1)**  
  Authors: Yunxiao Zhang, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12437v1.pdf)  
  Keywords: dynamic, body, efficient, gaussian splatting, ar, nerf, deformation, 3d gaussian, motion  
- **[PointGS: Semantic-Consistent Unsupervised 3D Point Cloud Segmentation with 3D Gaussian Splatting](https://arxiv.org/abs/2605.11520v1)**  
  Authors: Yixiao Song, Qingyong Li, Wen Wang, Zhicheng Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11520v1.pdf)  
  Keywords: face, gaussian splatting, ar, autonomous driving, 3d gaussian, semantic, segmentation  
- **[3DGS$^3$: Joint Super Sampling and Frame Interpolation for Real-Time Large-Scale 3DGS Rendering](https://arxiv.org/abs/2605.11489v1)**  
  Authors: Yibo Zhao, Fan Gao, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11489v1.pdf)  
  Keywords: efficient, high-fidelity, face, gaussian splatting, ar, compact, 3d gaussian, lightweight, acceleration  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: face, geometry, gaussian splatting, ar, sparse-view  
- **[Forecast-aware Gaussian Splatting for Predictive 3D Representation in Language-Guided Pick-and-Place Manipulation](https://arxiv.org/abs/2605.11144v1)**  
  Authors: Kaixin Jia, Jiacheng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11144v1.pdf)  
  Keywords: understanding, human, ar, gaussian splatting, semantic  

### Dynamic Scene

*Showing the latest 50 out of 377 papers*

- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, segmentation  
- **[Denoising-GS: Gaussian Splatting with Spatial-aware Denoising](https://arxiv.org/abs/2605.14880v1)**  
  Authors: Qingyuan Zhou, Xinyi Liu, Weidong Yang, Ning Wang, Shuquan Ye, Ben Fei, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14880v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, compact, 3d gaussian, motion  
- **[Efficient Dense Matching for Enhanced Gaussian Splatting Using AV1 Motion Vectors](https://arxiv.org/abs/2605.14629v1)**  
  Authors: Julien Zouein, Vibhoothi Vibhoothi, François Pitié, Anil Kokaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14629v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sigmedia.tv/AV1-3DGS.github.io/)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, motion, head  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, autonomous driving, tracking  
- **[3D Gaussian Splatting for Efficient Retrospective Dynamic Scene Novel View Synthesis with a Standardized Benchmark](https://arxiv.org/abs/2605.12437v1)**  
  Authors: Yunxiao Zhang, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12437v1.pdf)  
  Keywords: dynamic, body, efficient, gaussian splatting, ar, nerf, deformation, 3d gaussian, motion  
- **[PointForward: Feedforward Driving Reconstruction through Point-Aligned Representations](https://arxiv.org/abs/2605.11594v1)**  
  Authors: Cheng Chi, Xianqi Wang, Hongcheng Luo, Mingfei Tu, Gangwei Xu, Zehan Zhang, Bing Wang, Guang Chen, Hangjun Ye, Sida Peng, Xin Yang, Haiyang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11594v1.pdf)  
  Keywords: fast, dynamic, high-fidelity, gaussian splatting, ar, autonomous driving, 3d gaussian, motion  
- **[PD-4DGS:Progressive Decomposition of 4D Gaussian Splatting for Bandwidth-Adaptive Dynamic Scene Streaming](https://arxiv.org/abs/2605.11427v1)**  
  Authors: Jiachen Li, Guangzhi Han, Jin Wan, Delong Han, Yuan Gao, Min Li, Mingle Zhou, Gang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11427v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, ar, deformation, motion, compression  
- **[PG-3DGS: Optimizing 3D Gaussian Splatting to Satisfy Physics Objectives](https://arxiv.org/abs/2605.11266v1)**  
  Authors: Zachary Lee, Maxwell Jacobson, Yexiang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11266v1.pdf)  
  Keywords: understanding, fast, dynamic, high-fidelity, gaussian splatting, ar, 3d gaussian  
- **[DySurface: Consistent 4D Surface Reconstruction via Bridging Explicit Gaussians and Implicit Functions](https://arxiv.org/abs/2605.10360v2)**  
  Authors: Minje Kim, Younghyun Noh, Jaesoon Kim, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10360v2.pdf)  
  Keywords: dynamic, 4d, face, gaussian splatting, ar, nerf, deformation, 3d gaussian  
- **[PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.10307v1)**  
  Authors: Yinan Deng, Jianyu Dou, Jiahui Wang, Jingyu Zhao, Yi Yang, Yufeng Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10307v1.pdf)  
  Keywords: fast, dynamic, 4d, high-fidelity, gaussian splatting, ar, robotics, deformation, tracking, motion, segmentation  

### Few-shot

*Showing the latest 50 out of 82 papers*

- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: 3d reconstruction, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[PairDropGS: Paired Dropout-Induced Consistency Regularization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.12072v2)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Xingtao Wang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12072v2.pdf)  
  Keywords: geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: face, geometry, gaussian splatting, ar, sparse-view  
- **[ConFixGS: Learning to Fix Feedforward 3D Gaussian Splatting with Confidence-Aware Diffusion Priors in Driving Scenes](https://arxiv.org/abs/2605.09688v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Xingcheng Zhou, Zewei Zhou, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09688v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, sparse-view  
- **[FrameTwin: Curve-Anchored Gaussian Alignment from Sparse Views for Adaptive Wireframe 3D Printing](https://arxiv.org/abs/2605.09362v1)**  
  Authors: Wenting Wang, Zhuo Huang, Kun Qian, Neelotpal Dutta, Yuhu Guo, Yingjun Tian, Yeung Yam, Charlie C. L. Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09362v1.pdf)  
  Keywords: geometry, ar, sparse view, compact, deformation, sparse-view  
- **[SatSurfGS: Generalizable 2D Gaussian Splatting for Sparse-View Satellite Surface Reconstruction](https://arxiv.org/abs/2605.07181v1)**  
  Authors: Min Chen, Wei Guo, Bin Wang, Wen Li, Tong Fang, Jinbo Zhang, Junqi Zhao, Hong Kuang, Han Hu, Xuming Ge, Qing Zhu, Bo Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07181v1.pdf)  
  Keywords: face, ar, gaussian splatting, 3d gaussian, sparse-view  
- **[Residual Gaussian Splatting for Ultra Sparse-View CBCT Reconstruction](https://arxiv.org/abs/2604.27552v1)**  
  Authors: Jian Lin, Jiancheng Fang, Shaoyu Wang, Changan Lai, Yikun Zhang, Yang Chen, Qiegen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.27552v1.pdf)  
  Keywords: efficient, gaussian splatting, neural rendering, ar, 3d gaussian, sparse-view  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: localization, body, human, efficient, gaussian splatting, ar, 3d gaussian, sparse-view, semantic  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: gaussian splatting, ar, few-shot, 3d gaussian, sparse-view, reflection, head, lightweight, illumination  

### Geometry Reconstruction

*Showing the latest 50 out of 392 papers*

- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[Revisiting Photometric Ambiguity for Accurate Gaussian-Splatting Surface Reconstruction](https://arxiv.org/abs/2605.12494v1)**  
  Authors: Jiahe Li, Jiawei Zhang, Xiao Bai, Jin Zheng, Xiaohan Yu, Lin Gu, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12494v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fictionarry.github.io/AmbiSuR-Proj/)  
  Keywords: 3d reconstruction, face, geometry, gaussian splatting, ar  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: 3d reconstruction, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[PairDropGS: Paired Dropout-Induced Consistency Regularization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.12072v2)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Xingtao Wang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12072v2.pdf)  
  Keywords: geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[XFreq-GS: Cross-Frequency Wireless Radiation Field Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2605.11432v1)**  
  Authors: Sheng Wang, Hengtao He, Chaozheng Wen, Jingwen Tong, Xinyu Li, Xiao Li, Jun Zhang, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11432v1.pdf)  
  Keywords: high-fidelity, geometry, gaussian splatting, ar, 3d gaussian  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: face, geometry, gaussian splatting, ar, sparse-view  
- **[MAGS-SLAM: Monocular Multi-Agent Gaussian Splatting SLAM for Geometrically and Photometrically Consistent Reconstruction](https://arxiv.org/abs/2605.10760v1)**  
  Authors: Zhihao Cao, Qi Shao, Shuhao Zhai, Jing Zhang, Anh Nguyen, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10760v1.pdf)  
  Keywords: 3d reconstruction, mapping, high-fidelity, geometry, gaussian splatting, ar, compact, tracking, 3d gaussian, lightweight, slam  
- **[TransmissiveGS: Residual-Guided Disentangled Gaussian Splatting for Transmissive Scene Reconstruction and Rendering](https://arxiv.org/abs/2605.10705v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Tianchao Li, Jack C. P. Cheng, Chi-Keung Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10705v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, reflection  
- **[BEA-GS: BEyond RAdiance Supervision in 3DGS for Precise Object Extraction](https://arxiv.org/abs/2605.09662v1)**  
  Authors: Alessio Mazzucchelli, Maria Naranjo-Almeida, Jorge Bustos-Sanchez, Mariella Dimiccoli, Francesc Moreno-Noguer, Jordi Sanchez-Riera, Adrian Penate-Sanchez  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09662v1.pdf)  
  Keywords: geometry, gaussian splatting, ar, semantic, segmentation  
- **[FrameTwin: Curve-Anchored Gaussian Alignment from Sparse Views for Adaptive Wireframe 3D Printing](https://arxiv.org/abs/2605.09362v1)**  
  Authors: Wenting Wang, Zhuo Huang, Kun Qian, Neelotpal Dutta, Yuhu Guo, Yingjun Tian, Yeung Yam, Charlie C. L. Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09362v1.pdf)  
  Keywords: geometry, ar, sparse view, compact, deformation, sparse-view  

### Large Scene

- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: dynamic, efficient, high-fidelity, face, geometry, gaussian splatting, outdoor, ar, 3d gaussian  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: geometry, gaussian splatting, outdoor, ar, 3d gaussian  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, outdoor  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: localization, mapping, gaussian splatting, outdoor, ar, 3d gaussian, slam  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: understanding, geometry, gaussian splatting, ar, compact, urban scene, 3d gaussian, semantic, segmentation  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, semantic, large scene  
- **[MotionScale: Reconstructing Appearance, Geometry, and Motion of Dynamic Scenes with Scalable 4D Gaussian Splatting](https://arxiv.org/abs/2603.29296v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29296v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion-scale-web/.)  
  Keywords: understanding, dynamic, 4d, efficient, high-fidelity, geometry, gaussian splatting, neural rendering, ar, motion, large scene, shadow  
- **[Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting](https://arxiv.org/abs/2603.29185v1)**  
  Authors: Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.29185v1.pdf)  
  Keywords: localization, efficient, ar, gaussian splatting, outdoor  
- **[FilterGS: Traversal-Free Parallel Filtering and Adaptive Shrinking for Large-Scale LoD 3D Gaussian Splatting](https://arxiv.org/abs/2603.23891v1)**  
  Authors: Yixian Wang, Haolin Yu, Jiadong Tang, Yu Gao, Xihan Wang, Yufeng Yue, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23891v1.pdf)  
  Keywords: efficient, face, gaussian splatting, neural rendering, ar, 3d gaussian, head, large scene  
- **[MAGICIAN: Efficient Long-Term Planning with Imagined Gaussians for Active Mapping](https://arxiv.org/abs/2603.22650v2)**  
  Authors: Shiyao Li, Antoine Guédon, Shizhe Chen, Vincent Lepetit  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.22650v2.pdf)  
  Keywords: fast, efficient, mapping, face, gaussian splatting, outdoor, ar, 3d gaussian, lighting  

### Model Compression

*Showing the latest 50 out of 439 papers*

- **[Learn2Splat: Extending the Horizon of Learned 3DGS Optimization](https://arxiv.org/abs/2605.15760v1)**  
  Authors: Naama Pearl, Stefano Esposito, Haofei Xu, Amit Peleg, Patricia Gschossmann, Lorenzo Porzi, Peter Kontschieder, Gerard Pons-Moll, Andreas Geiger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://naamapearl.github.io/learn2splat)  
  Keywords: 3d gaussian, ar, gaussian splatting, efficient  
- **[Eff-WRFGS: Efficient Wireless Radiance Field Using 3D Gaussian Splatting](https://arxiv.org/abs/2605.15324v1)**  
  Authors: Chenghong Bian, Meng Hua, Deniz Gunduz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15324v1.pdf)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, head, efficient rendering  
- **[3D Skew-Normal Splatting](https://arxiv.org/abs/2605.15010v2)**  
  Authors: Xiangru Wu, Ke Fan, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15010v2.pdf)  
  Keywords: efficient, face, gaussian splatting, ar, compact, 3d gaussian  
- **[Denoising-GS: Gaussian Splatting with Spatial-aware Denoising](https://arxiv.org/abs/2605.14880v1)**  
  Authors: Qingyuan Zhou, Xinyi Liu, Weidong Yang, Ning Wang, Shuquan Ye, Ben Fei, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14880v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, compact, 3d gaussian, motion  
- **[Efficient Dense Matching for Enhanced Gaussian Splatting Using AV1 Motion Vectors](https://arxiv.org/abs/2605.14629v1)**  
  Authors: Julien Zouein, Vibhoothi Vibhoothi, François Pitié, Anil Kokaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14629v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sigmedia.tv/AV1-3DGS.github.io/)  
  Keywords: efficient, gaussian splatting, ar, nerf, 3d gaussian, motion, head  
- **[Sparse Code Uplifting for Efficient 3D Language Gaussian Splatting](https://arxiv.org/abs/2605.13600v1)**  
  Authors: Lovre Antonio Budimir, Yushi Guan, Steve Ryhner, Sven Lončarić, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13600v1.pdf)  
  Keywords: understanding, fast, efficient, gaussian splatting, ar, compact, 3d gaussian, semantic  
- **[Z-Order Transformer for Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2605.13465v1)**  
  Authors: Can Wang, Lei Liu, Wei Jiang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13465v1.pdf)  
  Keywords: fast, efficient, gaussian splatting, ar, 3d gaussian, semantic  
- **[RoSplat: Robust Feed-Forward Pixel-wise Gaussian Splatting for Varying Input Views and High-Resolution Rendering](https://arxiv.org/abs/2605.13093v1)**  
  Authors: Hoang Chuong Nguyen, Renjie Wu, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13093v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, efficient  
- **[3D Gaussian Splatting for Efficient Retrospective Dynamic Scene Novel View Synthesis with a Standardized Benchmark](https://arxiv.org/abs/2605.12437v1)**  
  Authors: Yunxiao Zhang, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12437v1.pdf)  
  Keywords: dynamic, body, efficient, gaussian splatting, ar, nerf, deformation, 3d gaussian, motion  
- **[PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization](https://arxiv.org/abs/2605.12144v1)**  
  Authors: Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12144v1.pdf)  
  Keywords: localization, ar, gaussian splatting, 3d gaussian, lightweight  

### Quality Enhancement

*Showing the latest 50 out of 242 papers*

- **[Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting](https://arxiv.org/abs/2605.16065v1)**  
  Authors: Raushan Joshi, Jean-Yves Guillemaut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16065v1.pdf)  
  Keywords: high quality, gaussian splatting, ar, robotics, 3d gaussian, vr, segmentation  
- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, segmentation  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 3d gaussian, semantic, lighting  
- **[Denoising-GS: Gaussian Splatting with Spatial-aware Denoising](https://arxiv.org/abs/2605.14880v1)**  
  Authors: Qingyuan Zhou, Xinyi Liu, Weidong Yang, Ning Wang, Shuquan Ye, Ben Fei, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14880v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, compact, 3d gaussian, motion  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, 3d gaussian, sparse-view  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, autonomous driving, tracking  
- **[PointForward: Feedforward Driving Reconstruction through Point-Aligned Representations](https://arxiv.org/abs/2605.11594v1)**  
  Authors: Cheng Chi, Xianqi Wang, Hongcheng Luo, Mingfei Tu, Gangwei Xu, Zehan Zhang, Bing Wang, Guang Chen, Hangjun Ye, Sida Peng, Xin Yang, Haiyang Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11594v1.pdf)  
  Keywords: fast, dynamic, high-fidelity, gaussian splatting, ar, autonomous driving, 3d gaussian, motion  
- **[3DGS$^3$: Joint Super Sampling and Frame Interpolation for Real-Time Large-Scale 3DGS Rendering](https://arxiv.org/abs/2605.11489v1)**  
  Authors: Yibo Zhao, Fan Gao, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11489v1.pdf)  
  Keywords: efficient, high-fidelity, face, gaussian splatting, ar, compact, 3d gaussian, lightweight, acceleration  
- **[XFreq-GS: Cross-Frequency Wireless Radiation Field Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2605.11432v1)**  
  Authors: Sheng Wang, Hengtao He, Chaozheng Wen, Jingwen Tong, Xinyu Li, Xiao Li, Jun Zhang, Shi Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11432v1.pdf)  
  Keywords: high-fidelity, geometry, gaussian splatting, ar, 3d gaussian  
- **[PG-3DGS: Optimizing 3D Gaussian Splatting to Satisfy Physics Objectives](https://arxiv.org/abs/2605.11266v1)**  
  Authors: Zachary Lee, Maxwell Jacobson, Yexiang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11266v1.pdf)  
  Keywords: understanding, fast, dynamic, high-fidelity, gaussian splatting, ar, 3d gaussian  

### Ray Tracing

- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: high-fidelity, geometry, gaussian splatting, ar, 3d gaussian, ray tracing  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: ray tracing, dynamic, efficient, gaussian splatting, ar, robotics, tracking, 3d gaussian, semantic, lighting  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: face, ar, gaussian splatting, reflection, ray tracing  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: localization, efficient, slam, mapping, face, gaussian splatting, ar, tracking, 3d gaussian, semantic, ray tracing  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: reflection, mapping, gaussian splatting, ar, 3d gaussian, relightable, shadow, ray tracing  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: fast, ray tracing, efficient, high-fidelity, face, geometry, gaussian splatting, ar, nerf, 3d gaussian, real-time rendering  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v6)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v6.pdf)  
  Keywords: survey, mapping, gaussian splatting, ar, 3d gaussian, ray tracing  
- **[IRIS: Intersection-aware Ray-based Implicit Editable Scenes](https://arxiv.org/abs/2603.15368v1)**  
  Authors: Grzegorz Wilczyński, Mikołaj Zieliński, Krzysztof Byrski, Joanna Waczyńska, Dominik Belter, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.15368v1.pdf)  
  Keywords: efficient, high-fidelity, gaussian splatting, ar, ray marching, 3d gaussian, real-time rendering  
- **[Spherical-GOF: Geometry-Aware Panoramic Gaussian Opacity Fields for 3D Scene Reconstruction](https://arxiv.org/abs/2603.08503v1)**  
  Authors: Zhe Yang, Guoqiang Zhao, Sheng Wu, Kai Luo, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.08503v1.pdf)  
  Keywords: fast, efficient, geometry, gaussian splatting, ar, robotics, 3d gaussian, ray casting  
- **[Ref-DGS: Reflective Dual Gaussian Splatting](https://arxiv.org/abs/2603.07664v2)**  
  Authors: Ningjing Fan, Yiqun Wang, Dongming Yan, Peter Wonka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.07664v2.pdf)  
  Keywords: fast, efficient, face, geometry, gaussian splatting, ar, reflection, lightweight, ray tracing  

### Relighting

*Showing the latest 50 out of 135 papers*

- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 3d gaussian, semantic, lighting  
- **[HarmoGS: Robust 3D Gaussian Splatting in the Wild via Conflict-Aware Gradient Harmonization](https://arxiv.org/abs/2605.13073v2)**  
  Authors: Yulei Kang, Tianze Zhu, Jian-Fang Hu, Jianhuang Lai, Wei-Shi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13073v2.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, semantic, illumination  
- **[TransmissiveGS: Residual-Guided Disentangled Gaussian Splatting for Transmissive Scene Reconstruction and Rendering](https://arxiv.org/abs/2605.10705v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Tianchao Li, Jack C. P. Cheng, Chi-Keung Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10705v1.pdf)  
  Keywords: high-fidelity, face, geometry, gaussian splatting, ar, reflection  
- **[Relightable Gaussian Splatting for Virtual Production Using Image-Based Illumination](https://arxiv.org/abs/2605.09024v1)**  
  Authors: Adrian Azzarelli, Nantheera Anantrasirichai, James Pollock, David R. Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.09024v1.pdf)  
  Keywords: reflection, 3d reconstruction, efficient, geometry, gaussian splatting, light transport, ar, relighting, vr, relightable, illumination, lighting  
- **[3DSS: 3D Surface Splatting for Inverse Rendering](https://arxiv.org/abs/2605.05876v3)**  
  Authors: Mae Younes, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.05876v3.pdf)  
  Keywords: face, geometry, ar, relighting, illumination, lighting  
- **[GOR-IS: 3D Gaussian Object Removal in the Intrinsic Space](https://arxiv.org/abs/2605.00498v1)**  
  Authors: Yonghao Zhao, Yupeng Gao, Jian Yang, Jin Xie, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00498v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://applezyh.github.io/GOR-IS-project-page/)  
  Keywords: face, geometry, light transport, gaussian splatting, ar, nerf, 3d gaussian, lighting  
- **[Color-Encoded Illumination for High-Speed Volumetric Scene Reconstruction](https://arxiv.org/abs/2604.26920v1)**  
  Authors: David Novikov, Eilon Vaknin, Narek Tumanyan, Mark Sheinin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26920v1.pdf)  
  Keywords: dynamic, gaussian splatting, ar, motion, illumination  
- **[Light 'em Up: Enabling Few-Shot Low-Light 3D Gaussian Splatting with Multi-Scale Explicit Retinex Illumination Decoupling](https://arxiv.org/abs/2604.24053v1)**  
  Authors: YuHao Yin, Zongji Wang, Yuanben Zhang, Biqing Li, Jiesong Bai, Junyi Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.24053v1.pdf)  
  Keywords: gaussian splatting, ar, few-shot, 3d gaussian, sparse-view, reflection, head, lightweight, illumination  
- **[Bringing a Personal Point of View: Evaluating Dynamic 3D Gaussian Splatting for Egocentric Scene Reconstruction](https://arxiv.org/abs/2604.23803v1)**  
  Authors: Jan Warchocki, Xi Wang, Jonas Kulhanek, Jan van Gemert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23803v1.pdf)  
  Keywords: 3d reconstruction, dynamic, 4d, efficient, human, gaussian splatting, ar, robotics, 3d gaussian, motion, lighting  
- **[GS-DOT: Gaussian splatting-based image reconstruction for diffuse optical tomography](https://arxiv.org/abs/2604.23675v1)**  
  Authors: Jingjing Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.23675v1.pdf)  
  Keywords: localization, efficient, light transport, ar, gaussian splatting  

### SLAM

*Showing the latest 50 out of 149 papers*

- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, autonomous driving, tracking  
- **[PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization](https://arxiv.org/abs/2605.12144v1)**  
  Authors: Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12144v1.pdf)  
  Keywords: localization, ar, gaussian splatting, 3d gaussian, lightweight  
- **[MAGS-SLAM: Monocular Multi-Agent Gaussian Splatting SLAM for Geometrically and Photometrically Consistent Reconstruction](https://arxiv.org/abs/2605.10760v1)**  
  Authors: Zhihao Cao, Qi Shao, Shuhao Zhai, Jing Zhang, Anh Nguyen, Baoru Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10760v1.pdf)  
  Keywords: 3d reconstruction, mapping, high-fidelity, geometry, gaussian splatting, ar, compact, tracking, 3d gaussian, lightweight, slam  
- **[PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.10307v1)**  
  Authors: Yinan Deng, Jianyu Dou, Jiahui Wang, Jingyu Zhao, Yi Yang, Yufeng Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10307v1.pdf)  
  Keywords: fast, dynamic, 4d, high-fidelity, gaussian splatting, ar, robotics, deformation, tracking, motion, segmentation  
- **[Disambiguating 2D-3D Correspondences in Gaussian Splatting-based Feature Fields for Visual Localization](https://arxiv.org/abs/2605.07351v1)**  
  Authors: Miso Lee, Sangeek Hyun, Yerim Jeon, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07351v1.pdf)  
  Keywords: localization, mapping, efficient, gaussian splatting, ar, compact  
- **[ULF-Loc: Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting](https://arxiv.org/abs/2605.04730v1)**  
  Authors: Yingdong Gu, Shaocheng Yan, Zhenjun Zhao, Yuan Kou, Jianxin Luo, Pengcheng Shi, Jiayuan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.04730v1.pdf)  
  Keywords: localization, efficient, geometry, gaussian splatting, ar, 3d gaussian, efficient rendering  
- **[CoherentRaster: Efficient 3D Gaussian Splatting for Light Field Displays](https://arxiv.org/abs/2605.04509v1)**  
  Authors: Gyujin Sim, Seungjoo Shin, Hosung Jeon, Gwangsoon Lee, Hyon-Gon Choo, Sunghyun Cho  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.04509v1.pdf)  
  Keywords: efficient, mapping, gaussian splatting, ar, 3d gaussian, head, acceleration, real-time rendering  
- **[Multi-Scale Gaussian-Language Map for Zero-shot Embodied Navigation and Reasoning](https://arxiv.org/abs/2605.01736v1)**  
  Authors: Sixian Zhang, Yiyao Wang, Xinhang Song, Keming Zhang, Zijian Xu, Shuqiang Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.01736v1.pdf)  
  Keywords: understanding, fast, efficient, mapping, face, geometry, gaussian splatting, ar, compact, 3d gaussian, semantic  
- **[Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy](https://arxiv.org/abs/2604.28179v1)**  
  Authors: Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.28179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://asdunnbe.github.io/RESPIRE/)  
  Keywords: fast, localization, dynamic, body, geometry, gaussian splatting, ar, deformation, motion, lightweight  
- **[Generalizable Human Gaussian Splatting via Multi-view Semantic Consistency](https://arxiv.org/abs/2604.25466v1)**  
  Authors: Jingi Kim, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.25466v1.pdf)  
  Keywords: localization, body, human, efficient, gaussian splatting, ar, 3d gaussian, sparse-view, semantic  

### Scene Understanding

*Showing the latest 50 out of 223 papers*

- **[Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting](https://arxiv.org/abs/2605.16065v1)**  
  Authors: Raushan Joshi, Jean-Yves Guillemaut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16065v1.pdf)  
  Keywords: high quality, gaussian splatting, ar, robotics, 3d gaussian, vr, segmentation  
- **[EndoGSim: Physics-Aware 4D Dynamic Endoscopic Scene Simulations via MLLM-Guided Gaussian Splatting](https://arxiv.org/abs/2605.16022v1)**  
  Authors: Changjing Liu, Yiming Huang, Long Bai, Beilei Cui, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16022v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, gaussian splatting, ar, segmentation  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ar, 3d gaussian, semantic, lighting  
- **[Sparse Code Uplifting for Efficient 3D Language Gaussian Splatting](https://arxiv.org/abs/2605.13600v1)**  
  Authors: Lovre Antonio Budimir, Yushi Guan, Steve Ryhner, Sven Lončarić, Nandita Vijaykumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13600v1.pdf)  
  Keywords: understanding, fast, efficient, gaussian splatting, ar, compact, 3d gaussian, semantic  
- **[Z-Order Transformer for Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2605.13465v1)**  
  Authors: Can Wang, Lei Liu, Wei Jiang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13465v1.pdf)  
  Keywords: fast, efficient, gaussian splatting, ar, 3d gaussian, semantic  
- **[HarmoGS: Robust 3D Gaussian Splatting in the Wild via Conflict-Aware Gradient Harmonization](https://arxiv.org/abs/2605.13073v2)**  
  Authors: Yulei Kang, Tianze Zhu, Jian-Fang Hu, Jianhuang Lai, Wei-Shi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13073v2.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, semantic, illumination  
- **[PointGS: Semantic-Consistent Unsupervised 3D Point Cloud Segmentation with 3D Gaussian Splatting](https://arxiv.org/abs/2605.11520v1)**  
  Authors: Yixiao Song, Qingyong Li, Wen Wang, Zhicheng Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11520v1.pdf)  
  Keywords: face, gaussian splatting, ar, autonomous driving, 3d gaussian, semantic, segmentation  
- **[PG-3DGS: Optimizing 3D Gaussian Splatting to Satisfy Physics Objectives](https://arxiv.org/abs/2605.11266v1)**  
  Authors: Zachary Lee, Maxwell Jacobson, Yexiang Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11266v1.pdf)  
  Keywords: understanding, fast, dynamic, high-fidelity, gaussian splatting, ar, 3d gaussian  
- **[Forecast-aware Gaussian Splatting for Predictive 3D Representation in Language-Guided Pick-and-Place Manipulation](https://arxiv.org/abs/2605.11144v1)**  
  Authors: Kaixin Jia, Jiacheng Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11144v1.pdf)  
  Keywords: understanding, human, ar, gaussian splatting, semantic  
- **[VEGA: Visual Encoder Grounding Alignment for Spatially-Aware Vision-Language-Action Models](https://arxiv.org/abs/2605.10485v1)**  
  Authors: Hao Wang, Xiaobao Wei, Jingyang He, Chengyu Bai, Chun-Kai Fan, Jiajun Cao, Jintao Chen, Ying Li, Shanyu Rong, Ming Lu, Xiaozhu Ju, Jian Tang, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.10485v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, 3d gaussian, head, lightweight  



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