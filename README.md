# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-07-17 01:47:23

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
- [Dynamic Scene](#dynamic-scene) (376 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (79 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (415 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (416 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (247 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (29 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (136 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (160 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (229 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: recognition, survey, 4d, neural rendering, motion, autonomous driving, ar, compact, 3d reconstruction, gaussian splatting, medical, 3d gaussian, vr  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: survey, ar, mapping, animation, gaussian splatting, geometry  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: slam, efficient, survey, motion, ar, tracking, 3d reconstruction, gaussian splatting, 3d gaussian, geometry  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, ar, gaussian splatting, 3d gaussian, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: survey, ar, ray tracing, mapping, gaussian splatting, 3d gaussian  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: dynamic, slam, efficient, survey, motion, ar, tracking, mapping, face, localization, gaussian splatting, 3d gaussian  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, survey, ar, gaussian splatting, 3d gaussian  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: efficient, survey, ar, gaussian splatting, 3d gaussian, geometry, nerf  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: dynamic, efficient, survey, 4d, ar, compact, 3d reconstruction, gaussian splatting, 3d gaussian, high-fidelity, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: semantic, slam, robotics, survey, ar, mapping, localization, gaussian splatting, understanding, 3d gaussian, nerf  

### Acceleration

*Showing the latest 50 out of 229 papers*

- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: motion, 3d gaussian, ar, face, gaussian splatting, fast, geometry, real-time rendering  
- **[Compression of 3D Gaussian Splatting Data Using GPU-friendly Graphics Texture Coding](https://arxiv.org/abs/2607.14513v1)**  
  Authors: Amir Said, Randall Rauwendaal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14513v1.pdf)  
  Keywords: efficient, acceleration, ar, gaussian splatting, 3d gaussian, compression  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: fast, efficient, ar, mapping, compact, gaussian splatting, 3d gaussian, geometry  
- **[Calibrated Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v1)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v1.pdf)  
  Keywords: fast, ar, gaussian splatting, sparse-view  
- **[SpeedyGS: Content-Aware 3D Gaussian Splatting Compression via Two-Stage Optimization](https://arxiv.org/abs/2607.12656v1)**  
  Authors: Junteng Zhang, Tong Chen, Yuxin Zhao, Yibo Shi, Jing Wang, Zhan Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12656v1.pdf)  
  Keywords: fast, efficient, head, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, compression  
- **[Implicit 4D Gaussian Splatting for Fast Motion with Large Inter-Frame Displacements](https://arxiv.org/abs/2607.12362v1)**  
  Authors: Seung-gyeom Kim, Areum Kim, Yongjae Yoo, Sukmin Yun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12362v1.pdf)  
  Keywords: 4d, head, lightweight, motion, ar, gaussian splatting, fast  
- **[HyperGS: Fast and Generalizable Gaussian Video Representation](https://arxiv.org/abs/2607.11500v1)**  
  Authors: Fatimah Zohra, Chen Zhao, Shuming Liu, Yahya Al Malallah, Bernard Ghanem  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11500v1.pdf)  
  Keywords: dynamic, fast, ar, gaussian splatting  
- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: dynamic, 4d, motion, ar, face, gaussian splatting, deformation, fast, nerf  

### Applications

*Showing the latest 50 out of 993 papers*

- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: dynamic, semantic, motion, ar, tracking, gaussian splatting, 3d gaussian  
- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: motion, 3d gaussian, ar, face, gaussian splatting, fast, geometry, real-time rendering  
- **[Compression of 3D Gaussian Splatting Data Using GPU-friendly Graphics Texture Coding](https://arxiv.org/abs/2607.14513v1)**  
  Authors: Amir Said, Randall Rauwendaal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14513v1.pdf)  
  Keywords: efficient, acceleration, ar, gaussian splatting, 3d gaussian, compression  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[Instant NuRec: Feed-Forward 3D Gaussian Reconstruction for Driving Scene Simulation](https://arxiv.org/abs/2607.14203v1)**  
  Authors: NVIDIA, :, Jiahui Huang, Jiawei Ren, Michal Tyszkiewicz, Bjoern Haefner, Michael Shelley, Xin Kang, Seung Wook Kim, Ning Xu, Qi Wu, Janick Martinez Esturo, Shengyu Huang, Nick Schneider, Laura Leal-Taixe, Zan Gojcic, Sanja Fidler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14203v1.pdf)  
  Keywords: dynamic, autonomous driving, ar, gaussian splatting, 3d gaussian  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: fast, efficient, ar, mapping, compact, gaussian splatting, 3d gaussian, geometry  
- **[Calibrated Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v1)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v1.pdf)  
  Keywords: fast, ar, gaussian splatting, sparse-view  
- **[COLMAR: Cooperative View Policy Learning for Multi-Agent Active 3D Reconstruction](https://arxiv.org/abs/2607.13524v1)**  
  Authors: Phu Pham, Damon Conover, Aniket Bera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13524v1.pdf)  
  Keywords: ar, 3d reconstruction, gaussian splatting, 3d gaussian, high-fidelity  
- **[Learning Physics-Guided Residual Dynamics for Deformable Object Simulation](https://arxiv.org/abs/2607.13451v1)**  
  Authors: Shivansh Patel, Kaifeng Zhang, Sanjay Pokkali, Svetlana Lazebnik, Yunzhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13451v1.pdf)  
  Keywords: dynamic, 3d gaussian, ar, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 328 papers*

- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: motion, 3d gaussian, ar, face, gaussian splatting, fast, geometry, real-time rendering  
- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation](https://arxiv.org/abs/2607.13154v1)**  
  Authors: Lingxiao Guo, Huanyu Li, Guanya Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13154v1.pdf)  
  Keywords: human, motion, ar, body, gaussian splatting  
- **[SpeedyGS: Content-Aware 3D Gaussian Splatting Compression via Two-Stage Optimization](https://arxiv.org/abs/2607.12656v1)**  
  Authors: Junteng Zhang, Tong Chen, Yuxin Zhao, Yibo Shi, Jing Wang, Zhan Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12656v1.pdf)  
  Keywords: fast, efficient, head, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, compression  
- **[Implicit 4D Gaussian Splatting for Fast Motion with Large Inter-Frame Displacements](https://arxiv.org/abs/2607.12362v1)**  
  Authors: Seung-gyeom Kim, Areum Kim, Yongjae Yoo, Sukmin Yun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12362v1.pdf)  
  Keywords: 4d, head, lightweight, motion, ar, gaussian splatting, fast  
- **[SalientGS: Unified SfM-to-3DGS with Importance-Guided MCMC Gaussian Allocation](https://arxiv.org/abs/2607.11285v2)**  
  Authors: Tianyu Xiong, Rui Li, Suning Ge, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11285v2.pdf)  
  Keywords: dynamic, motion, ar, face, gaussian splatting, 3d gaussian  
- **[AsySplat: Efficient Asymmetric 3D Gaussian Splatting for Long-Sequence Scene Modeling](https://arxiv.org/abs/2607.10995v1)**  
  Authors: Yingji Zhong, Dave Zhenyu Chen, Fuzhao Ou, Youyu Chen, Zhihao Li, Lanqing Hong, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10995v1.pdf)  
  Keywords: efficient, head, ar, gaussian splatting, 3d gaussian, geometry  
- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: dynamic, efficient, head, face, gaussian splatting, 3d gaussian, high-fidelity  
- **[Grassmannian Splatting I: Moving rank-2 Spacetime Surfels for Dynamic Scene Rendering](https://arxiv.org/abs/2607.10489v1)**  
  Authors: Aaron Maurice Berman, Shantanu Dave  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10489v1.pdf)  
  Keywords: dynamic, 4d, motion, ar, face, gaussian splatting, deformation, fast, nerf  
- **[A 3DGS-Driven Dynamic Viewpoint and Vibrotactile Framework for Subsea Teleoperation Validated via fNIRS](https://arxiv.org/abs/2607.13067v1)**  
  Authors: Fang Xu, Tianyu Zhou, Ruitong Tian, Md Jahidul Islam, Jing Du  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13067v1.pdf)  
  Keywords: dynamic, human, ar, gaussian splatting, 3d gaussian  

### Dynamic Scene

*Showing the latest 50 out of 376 papers*

- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: dynamic, semantic, motion, ar, tracking, gaussian splatting, 3d gaussian  
- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: motion, 3d gaussian, ar, face, gaussian splatting, fast, geometry, real-time rendering  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[Instant NuRec: Feed-Forward 3D Gaussian Reconstruction for Driving Scene Simulation](https://arxiv.org/abs/2607.14203v1)**  
  Authors: NVIDIA, :, Jiahui Huang, Jiawei Ren, Michal Tyszkiewicz, Bjoern Haefner, Michael Shelley, Xin Kang, Seung Wook Kim, Ning Xu, Qi Wu, Janick Martinez Esturo, Shengyu Huang, Nick Schneider, Laura Leal-Taixe, Zan Gojcic, Sanja Fidler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14203v1.pdf)  
  Keywords: dynamic, autonomous driving, ar, gaussian splatting, 3d gaussian  
- **[Learning Physics-Guided Residual Dynamics for Deformable Object Simulation](https://arxiv.org/abs/2607.13451v1)**  
  Authors: Shivansh Patel, Kaifeng Zhang, Sanjay Pokkali, Svetlana Lazebnik, Yunzhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13451v1.pdf)  
  Keywords: dynamic, 3d gaussian, ar, gaussian splatting  
- **[Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation](https://arxiv.org/abs/2607.13154v1)**  
  Authors: Lingxiao Guo, Huanyu Li, Guanya Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13154v1.pdf)  
  Keywords: human, motion, ar, body, gaussian splatting  
- **[Implicit 4D Gaussian Splatting for Fast Motion with Large Inter-Frame Displacements](https://arxiv.org/abs/2607.12362v1)**  
  Authors: Seung-gyeom Kim, Areum Kim, Yongjae Yoo, Sukmin Yun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12362v1.pdf)  
  Keywords: 4d, head, lightweight, motion, ar, gaussian splatting, fast  
- **[HyperGS: Fast and Generalizable Gaussian Video Representation](https://arxiv.org/abs/2607.11500v1)**  
  Authors: Fatimah Zohra, Chen Zhao, Shuming Liu, Yahya Al Malallah, Bernard Ghanem  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11500v1.pdf)  
  Keywords: dynamic, fast, ar, gaussian splatting  
- **[SalientGS: Unified SfM-to-3DGS with Importance-Guided MCMC Gaussian Allocation](https://arxiv.org/abs/2607.11285v2)**  
  Authors: Tianyu Xiong, Rui Li, Suning Ge, Jiaqi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11285v2.pdf)  
  Keywords: dynamic, motion, ar, face, gaussian splatting, 3d gaussian  
- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: dynamic, efficient, head, face, gaussian splatting, 3d gaussian, high-fidelity  

### Few-shot

*Showing the latest 50 out of 79 papers*

- **[Calibrated Closed-Form Uncertainty for Radiative Gaussian Splatting in Sparse-View CT](https://arxiv.org/abs/2607.13682v1)**  
  Authors: Chulin Zhao, Yiran Xu, Shu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13682v1.pdf)  
  Keywords: fast, ar, gaussian splatting, sparse-view  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, neural rendering, ar, gaussian splatting, sparse-view, 3d gaussian, geometry, high-fidelity  
- **[Rendering-Aware Bayesian 3D Gaussian Splatting with Native Uncertainty and Adaptive Complexity Control](https://arxiv.org/abs/2607.05522v1)**  
  Authors: Gaoxiang Jia, Vikram Appia, Junzhou Huang, Xinlei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05522v1.pdf)  
  Keywords: ar, gaussian splatting, sparse view, 3d gaussian, geometry  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: efficient, sparse view, ar, face, gaussian splatting, large scene, 3d gaussian, geometry  
- **[Sparse-View Surface Reconstruction using Gaussian Splatting through High-Confidence Depth Propagation with Normal Priors](https://arxiv.org/abs/2607.03765v1)**  
  Authors: Liang Han, Bangcai Wei, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03765v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/DP-GS.)  
  Keywords: ar, face, 3d reconstruction, gaussian splatting, sparse view, sparse-view, 3d gaussian, geometry, high-fidelity  
- **[Fast 3D Foundation Model Initialized Gaussian Splatting](https://arxiv.org/abs/2607.03209v1)**  
  Authors: Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03209v1.pdf)  
  Keywords: fast, robotics, motion, ar, gaussian splatting, sparse-view, 3d gaussian, vr, nerf  
- **[Improving Sparse-View 3DGS Generalization via Flat Minima Optimization](https://arxiv.org/abs/2607.00885v1)**  
  Authors: Kangmin Seo, Sangeek Hyun, MinKyu Lee, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00885v1.pdf)  
  Keywords: dynamic, fast, efficient, lightweight, neural rendering, ar, gaussian splatting, sparse-view, 3d gaussian, real-time rendering, nerf  
- **[AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings](https://arxiv.org/abs/2606.31556v1)**  
  Authors: Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31556v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, geometry, real-time rendering, nerf  
- **[StereoGS: Sparse-View 3D Gaussian Splatting via Stereo Priors](https://arxiv.org/abs/2606.30545v2)**  
  Authors: Wenhao Yuan, Yiyuan Ge, Deli Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30545v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://stringerywh00.github.io/StereoGS_project_page/)  
  Keywords: dynamic, head, ar, face, gaussian splatting, sparse-view, 3d gaussian, geometry, nerf  
- **[Occlusion-Robust Multi-Object Decoupling for Physics-Based Robotic Interaction](https://arxiv.org/abs/2606.29303v2)**  
  Authors: Xin Dong, Lihan Zhang, Tianru Dai, Wenfeng Deng, Yansong Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29303v2.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, gaussian splatting, sparse-view, segmentation, 3d gaussian, geometry  

### Geometry Reconstruction

*Showing the latest 50 out of 415 papers*

- **[JADE-GS: Joint Alternating Deblurring Guided by Events in 3D Gaussian Splatting](https://arxiv.org/abs/2607.14990v1)**  
  Authors: Haoyu Fu, Jiafeng Huang, Yuchen Wang, Shengjie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14990v1.pdf)  
  Keywords: motion, 3d gaussian, ar, face, gaussian splatting, fast, geometry, real-time rendering  
- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: fast, efficient, ar, mapping, compact, gaussian splatting, 3d gaussian, geometry  
- **[COLMAR: Cooperative View Policy Learning for Multi-Agent Active 3D Reconstruction](https://arxiv.org/abs/2607.13524v1)**  
  Authors: Phu Pham, Damon Conover, Aniket Bera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13524v1.pdf)  
  Keywords: ar, 3d reconstruction, gaussian splatting, 3d gaussian, high-fidelity  
- **[SpeedyGS: Content-Aware 3D Gaussian Splatting Compression via Two-Stage Optimization](https://arxiv.org/abs/2607.12656v1)**  
  Authors: Junteng Zhang, Tong Chen, Yuxin Zhao, Yibo Shi, Jing Wang, Zhan Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12656v1.pdf)  
  Keywords: fast, efficient, head, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, compression  
- **[GeoFovea-GS: Geometry-Aware Cross-Layer Gaussian Splatting for Wireless Aerial VR](https://arxiv.org/abs/2607.12641v1)**  
  Authors: Zeyi Ren, Wencheng Yan, Jiawen Zhang, Jintao Yan, Sheng Zhou, Zhisheng Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12641v1.pdf)  
  Keywords: efficient, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, vr  
- **[ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v2)**  
  Authors: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang, Fei Yu, Zengye Ge, Yumin Liu, Jiacheng Zhang, Yongchang Zhang, Jiawei Zhang, Zhicheng Liu, Zhongxu Sun, Tianjian Ouyang, Wenzheng Chen, Shixing Yang, Nianfei Fan, Guodong Sun, Huan Li, Zheng Zhou, Yongze Li, Yingliang Peng, Mengmeng Du, Yuan Liu, Haozhe Shi, Chunnuo Gong, Chengzhen Yu, Chunxue Jia, Yang Liu, Shiying Zeng, Junnan Lai, Hang Zhang, Ning Guo, Baoquan Chen, Mu Xu, Hongyu Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11673v2.pdf)  
  Keywords: efficient, ar, compact, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: slam, ar, tracking, mapping, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[AsySplat: Efficient Asymmetric 3D Gaussian Splatting for Long-Sequence Scene Modeling](https://arxiv.org/abs/2607.10995v1)**  
  Authors: Yingji Zhong, Dave Zhenyu Chen, Fuzhao Ou, Youyu Chen, Zhihao Li, Lanqing Hong, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10995v1.pdf)  
  Keywords: efficient, head, ar, gaussian splatting, 3d gaussian, geometry  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, neural rendering, ar, gaussian splatting, sparse-view, 3d gaussian, geometry, high-fidelity  

### Large Scene

- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: slam, ar, tracking, mapping, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: ar, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: efficient, sparse view, ar, face, gaussian splatting, large scene, 3d gaussian, geometry  
- **[Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)**  
  Authors: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.00673v1.pdf)  
  Keywords: human, ar, outdoor, deformation, 3d gaussian  
- **[GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping](https://arxiv.org/abs/2606.30809v1)**  
  Authors: Annika Thomas, Mason Peterson, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30809v1.pdf)  
  Keywords: ar, mapping, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[Robust and Efficient Monocular 3D Gaussian SLAM for Kilometer-Scale Outdoor Scenes](https://arxiv.org/abs/2606.30436v1)**  
  Authors: Sicheng Yu, Dongxu Shen, Beizhen Zhao, Guanzhi Ding, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30436v1.pdf)  
  Keywords: dynamic, slam, efficient, head, motion, ar, tracking, mapping, gaussian splatting, outdoor, 3d gaussian, high-fidelity  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: slam, efficient, autonomous driving, ar, mapping, face, localization, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: dynamic, fast, efficient, ar, urban scene, gaussian splatting, large scene, 3d gaussian, geometry, high-fidelity  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: fast, efficient, ar, gaussian splatting, outdoor, 3d gaussian, geometry  

### Model Compression

*Showing the latest 50 out of 416 papers*

- **[Compression of 3D Gaussian Splatting Data Using GPU-friendly Graphics Texture Coding](https://arxiv.org/abs/2607.14513v1)**  
  Authors: Amir Said, Randall Rauwendaal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14513v1.pdf)  
  Keywords: efficient, acceleration, ar, gaussian splatting, 3d gaussian, compression  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: fast, efficient, ar, mapping, compact, gaussian splatting, 3d gaussian, geometry  
- **[SpeedyGS: Content-Aware 3D Gaussian Splatting Compression via Two-Stage Optimization](https://arxiv.org/abs/2607.12656v1)**  
  Authors: Junteng Zhang, Tong Chen, Yuxin Zhao, Yibo Shi, Jing Wang, Zhan Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12656v1.pdf)  
  Keywords: fast, efficient, head, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, compression  
- **[GeoFovea-GS: Geometry-Aware Cross-Layer Gaussian Splatting for Wireless Aerial VR](https://arxiv.org/abs/2607.12641v1)**  
  Authors: Zeyi Ren, Wencheng Yan, Jiawen Zhang, Jintao Yan, Sheng Zhou, Zhisheng Niu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12641v1.pdf)  
  Keywords: efficient, lightweight, ar, compact, gaussian splatting, 3d gaussian, geometry, vr  
- **[Implicit 4D Gaussian Splatting for Fast Motion with Large Inter-Frame Displacements](https://arxiv.org/abs/2607.12362v1)**  
  Authors: Seung-gyeom Kim, Areum Kim, Yongjae Yoo, Sukmin Yun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.12362v1.pdf)  
  Keywords: 4d, head, lightweight, motion, ar, gaussian splatting, fast  
- **[ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v2)**  
  Authors: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang, Fei Yu, Zengye Ge, Yumin Liu, Jiacheng Zhang, Yongchang Zhang, Jiawei Zhang, Zhicheng Liu, Zhongxu Sun, Tianjian Ouyang, Wenzheng Chen, Shixing Yang, Nianfei Fan, Guodong Sun, Huan Li, Zheng Zhou, Yongze Li, Yingliang Peng, Mengmeng Du, Yuan Liu, Haozhe Shi, Chunnuo Gong, Chengzhen Yu, Chunxue Jia, Yang Liu, Shiying Zeng, Junnan Lai, Hang Zhang, Ning Guo, Baoquan Chen, Mu Xu, Hongyu Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11673v2.pdf)  
  Keywords: efficient, ar, compact, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[AsySplat: Efficient Asymmetric 3D Gaussian Splatting for Long-Sequence Scene Modeling](https://arxiv.org/abs/2607.10995v1)**  
  Authors: Yingji Zhong, Dave Zhenyu Chen, Fuzhao Ou, Youyu Chen, Zhihao Li, Lanqing Hong, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10995v1.pdf)  
  Keywords: efficient, head, ar, gaussian splatting, 3d gaussian, geometry  
- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: dynamic, efficient, head, face, gaussian splatting, 3d gaussian, high-fidelity  

### Quality Enhancement

*Showing the latest 50 out of 247 papers*

- **[G$^2$SR: Geometric Methods for Fast and Memory-Efficient Gaussian-based Surface Reconstruction](https://arxiv.org/abs/2607.14470v1)**  
  Authors: Dasong Gao, Vivienne Sze, Sertac Karaman  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14470v1.pdf)  
  Keywords: fast, efficient, lightweight, ar, face, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[COLMAR: Cooperative View Policy Learning for Multi-Agent Active 3D Reconstruction](https://arxiv.org/abs/2607.13524v1)**  
  Authors: Phu Pham, Damon Conover, Aniket Bera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13524v1.pdf)  
  Keywords: ar, 3d reconstruction, gaussian splatting, 3d gaussian, high-fidelity  
- **[ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v2)**  
  Authors: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang, Fei Yu, Zengye Ge, Yumin Liu, Jiacheng Zhang, Yongchang Zhang, Jiawei Zhang, Zhicheng Liu, Zhongxu Sun, Tianjian Ouyang, Wenzheng Chen, Shixing Yang, Nianfei Fan, Guodong Sun, Huan Li, Zheng Zhou, Yongze Li, Yingliang Peng, Mengmeng Du, Yuan Liu, Haozhe Shi, Chunnuo Gong, Chengzhen Yu, Chunxue Jia, Yang Liu, Shiying Zeng, Junnan Lai, Hang Zhang, Ning Guo, Baoquan Chen, Mu Xu, Hongyu Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11673v2.pdf)  
  Keywords: efficient, ar, compact, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, neural rendering, ar, gaussian splatting, sparse-view, 3d gaussian, geometry, high-fidelity  
- **[Incremental Online Scene Reconstruction by 3D Gaussian Triangulation](https://arxiv.org/abs/2607.10690v1)**  
  Authors: Yanjin Zhu, Shaofan Liu, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10690v1.pdf)  
  Keywords: dynamic, efficient, head, face, gaussian splatting, 3d gaussian, high-fidelity  
- **[EscFOA: Enhancing Spatial Learning for Visually Impaired Learners via Generative Spatial Audio in 360-Degree Educational Environments](https://arxiv.org/abs/2607.07015v1)**  
  Authors: Ziyu Luo, Xiaowei Dai, Siying Zhu, Xiaoming Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07015v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[RoboSnap: One-Shot Real-to-Sim Scene Generation for Generalizable Robot Learning and Evaluation](https://arxiv.org/abs/2607.06699v1)**  
  Authors: Shujie Zhang, Jingkun Yi, Weipeng Zhong, Zirui Zhou, Yangkun Zhu, Hanqing Wang, Xudong Xu, Weinan Zhang, Chunhua Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06699v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, high-fidelity  
- **[Semantic-Guided Progressive Object Removal with Gaussian Splatting](https://arxiv.org/abs/2607.04144v1)**  
  Authors: Xianliang Huang, Chen Xiao, Yuanxiang Ni, Guanming Liu, Mingkai Liu, Dikai Fan, Xiao Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04144v1.pdf)  
  Keywords: semantic, robotics, efficient, ar, gaussian splatting, vr, high-fidelity  
- **[MACRO: Training-free Multi-plane Attention for Closeup Render Optimization](https://arxiv.org/abs/2607.03875v1)**  
  Authors: Nitzan Hodos, Roy Amoyal, Lior Fritz, Ianir Ideses, Sagie Benaim, Netalee Efrat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03875v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nitzanhod.github.io/MACRO)  
  Keywords: 3d gaussian, ar, gaussian splatting, high-fidelity  
- **[SharpSplat: Edge-Regularized 3D Gaussian Splatting for High Fidelity Urban Building Reconstruction from UAV images](https://arxiv.org/abs/2607.03872v1)**  
  Authors: Porus Vaid, Shivam Chopra, Vaibhav Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03872v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, 3d gaussian, high-fidelity  

### Ray Tracing

- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: fast, ar, ray tracing, gaussian splatting, 3d gaussian  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: efficient, path tracing, 3d gaussian, ar, ray tracing, reflection, gaussian splatting, fast, geometry, real-time rendering  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: efficient, ar, 3d reconstruction, gaussian splatting, illumination, 3d gaussian, geometry, global illumination  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: ar, gaussian splatting, illumination, global illumination, high-fidelity  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: semantic, efficient, ar, ray tracing, reflection, gaussian splatting, segmentation, 3d gaussian, geometry  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: shadow, fast, ar, face, gaussian splatting, illumination, 3d gaussian, global illumination  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ray casting, 3d gaussian, ar, gaussian splatting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: ar, ray tracing, gaussian splatting, 3d gaussian, geometry, high-fidelity  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: dynamic, semantic, efficient, robotics, ar, ray tracing, tracking, gaussian splatting, lighting, 3d gaussian  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ar, ray tracing, face, reflection, gaussian splatting  

### Relighting

*Showing the latest 50 out of 136 papers*

- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: slam, robotics, ar, mapping, 3d reconstruction, gaussian splatting, illumination, geometry  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: dynamic, ar, mapping, gaussian splatting, lighting  
- **[WildSplat: Feedforward Gaussian Splatting from Unposed In-the-Wild Images](https://arxiv.org/abs/2607.05347v1)**  
  Authors: Xiyu Zhang, Jingyu Zhuang, Hongjia Zhai, Zizheng Yan, Jinwei Chen, Guofeng Zhang, Qingnan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05347v1.pdf)  
  Keywords: efficient, ar, face, 3d reconstruction, gaussian splatting, illumination, 3d gaussian, geometry  
- **[Intrinsic decomposition and editing of 3D Gaussian splats](https://arxiv.org/abs/2606.31637v1)**  
  Authors: Alexandre Lanvin, Jeffrey Hu, Simon Lucas, Adrien Bousseau, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.31637v1.pdf)  
  Keywords: ar, face, gaussian splatting, lighting, 3d gaussian  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: efficient, path tracing, 3d gaussian, ar, ray tracing, reflection, gaussian splatting, fast, geometry, real-time rendering  
- **[Monte Carlo Energy Aggregation for Mobile 3D Gaussian Splatting](https://arxiv.org/abs/2606.30017v1)**  
  Authors: Xiaobiao Du, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30017v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobiaodu.github.io/flux-gs-project/}{https://xiaobiaodu.github.io/flux-gs-project/}}.)  
  Keywords: head, ar, compact, lighting, gaussian splatting, 3d gaussian, high-fidelity, compression  
- **[Shell-Supervised Gaussian Splatting for Urban Real-to-Sim Reconstruction](https://arxiv.org/abs/2606.30014v1)**  
  Authors: Yuan Yang, Peijun Lu, Fangzhou Lu, Sai Fan, Siqi Yan, Chenyuan Zhang, Haobo Liang, Yichen Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30014v1.pdf)  
  Keywords: lightweight, ar, face, reflection, 3d reconstruction, gaussian splatting, geometry  
- **[DR-GS: Physically-Based Deformable and Relightable 2D Gaussians](https://arxiv.org/abs/2606.29379v1)**  
  Authors: Jiaxin Li, Tong Wu, Yi Wei, Tailin Wu, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29379v1.pdf)  
  Keywords: relighting, efficient rendering, dynamic, efficient, relightable, ar, face, reflection, gaussian splatting, lighting, deformation, illumination, geometry, vr  
- **[RAGA: Real Time Ray Traced Gaussian Shadow Casting for 3DGS Avatar-Scene Interaction](https://arxiv.org/abs/2606.29329v1)**  
  Authors: Aymen Mir, Riza Alp Guler, Jian Wang, Peter Wonka, Bing Zhou, Gerard Pons-Moll  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.29329v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://miraymen.github.io/raga/.)  
  Keywords: shadow, avatar, ar, gaussian splatting, deformation, 3d gaussian  
- **[RefGlass-GS: A UAV-Enabled Fusion Framework for Photorealistic, Semantic and Interactive Digitization of Reflective Glass Facades via Gaussian Splatting](https://arxiv.org/abs/2606.28826v1)**  
  Authors: Zhenyu Liang, Xiao Zhang, Boyu Wang, Zhaolun Liang, Ang Li, Jeff Chak Fu Chan, Mingzhu Wang, Jack C. P. Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.28826v1.pdf)  
  Keywords: semantic, ar, reflection, gaussian splatting, segmentation  

### SLAM

*Showing the latest 50 out of 160 papers*

- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: dynamic, semantic, motion, ar, tracking, gaussian splatting, 3d gaussian  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[Bake It Till You Make It: Ultrafast Spatial Texture-Atlas Splatting](https://arxiv.org/abs/2607.13808v1)**  
  Authors: Neel Kelkar, Simon Niedermayr, Kaloian Petkov, Klaus Engel, Rüdiger Westermann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.13808v1.pdf)  
  Keywords: fast, efficient, ar, mapping, compact, gaussian splatting, 3d gaussian, geometry  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: slam, ar, tracking, mapping, gaussian splatting, outdoor, 3d gaussian, geometry  
- **[AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration](https://arxiv.org/abs/2607.09260v1)**  
  Authors: Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.09260v1.pdf)  
  Keywords: semantic, slam, recognition, ar, gaussian splatting, 3d gaussian, vr  
- **[Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery](https://arxiv.org/abs/2607.08408v1)**  
  Authors: Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08408v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://track2map.github.io/.)  
  Keywords: slam, motion, ar, mapping, 3d reconstruction, gaussian splatting, deformation, 3d gaussian  
- **[GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM](https://arxiv.org/abs/2607.07452v1)**  
  Authors: Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.07452v1.pdf)  
  Keywords: slam, robotics, ar, mapping, 3d reconstruction, gaussian splatting, illumination, geometry  
- **[PhyMRI-SR: Toward Physics-Aware MRI Image Super-Resolution](https://arxiv.org/abs/2607.06238v1)**  
  Authors: Lihua Wei, Huatong Gao, Jia Gong, Zhiyu Tan, Hao Li, Jun Liu, Zhihua Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.06238v1.pdf)  
  Keywords: dynamic, ar, mapping, gaussian splatting, lighting  
- **[Real-Time LiDAR Gaussian Splatting SLAM](https://arxiv.org/abs/2607.04127v1)**  
  Authors: Seungjun Tak, Yewon Jeon, Jaeik Hwang, SukMin Hwang, Seongbo Ha, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04127v1.pdf)  
  Keywords: slam, ar, tracking, mapping, face, gaussian splatting, fast, geometry  
- **[PRISM3D: Probabilistic Refinement and Robust Initialization for Physically Consistent Scene Modeling under Extreme Motion Blur](https://arxiv.org/abs/2607.03855v1)**  
  Authors: Gopi Raju Matta, Reddypalli Trisha, Vemunuri Divya Madhuri, Kaushik Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03855v1.pdf)  
  Keywords: motion, ar, tracking, gaussian splatting, 3d gaussian, geometry  

### Scene Understanding

*Showing the latest 50 out of 229 papers*

- **[AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)**  
  Authors: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo, Zhongxin Chen, Yu Hu, Xinjiang Wang, Jian Sun, Gang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14997v1.pdf)  
  Keywords: dynamic, semantic, motion, ar, tracking, gaussian splatting, 3d gaussian  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: slam, efficient, recognition, motion, 3d gaussian, ar, gaussian splatting, large scene, fast, real-time rendering  
- **[MAC-Splat: Multi-Attribute Consistency for High-Fidelity Sparse-View Reconstruction](https://arxiv.org/abs/2607.10792v1)**  
  Authors: Jinqian Yang, Yichen Wu, Wanhua Li, Haokun Lin, Renzhen Wang, Xiangchu Feng, Xixi Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10792v1.pdf)  
  Keywords: semantic, neural rendering, ar, gaussian splatting, sparse-view, 3d gaussian, geometry, high-fidelity  
- **[CoSAG: Compact Semantic Anchor Gaussians via Training-Free Rate-Distortion Coding](https://arxiv.org/abs/2607.10237v1)**  
  Authors: Yuang Jia, Jinlong Wang, Junhong Lin, Ruiting Dai, Wei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.10237v1.pdf)  
  Keywords: semantic, ar, compact, gaussian splatting, understanding, 3d gaussian  
- **[AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration](https://arxiv.org/abs/2607.09260v1)**  
  Authors: Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.09260v1.pdf)  
  Keywords: semantic, slam, recognition, ar, gaussian splatting, 3d gaussian, vr  
- **[GaussFusion: Towards Multimodal 3D Gaussian Pretraining](https://arxiv.org/abs/2607.05906v1)**  
  Authors: Zhixuan You, Jihua Zhu, Yiding Sun, Zihao Guo, Haozhe Cheng, Dongxu Zhang, Lin Chen, Hainan Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.05906v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, 3d gaussian, geometry  
- **[DeGenseGS: Geometrically and Semantically Decoupled Surgical Scene Understanding in 4D Gaussian Splatting](https://arxiv.org/abs/2607.04761v1)**  
  Authors: Yimo Wang, Bin Kang, Shuojue Yang, Yueming Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04761v1.pdf)  
  Keywords: dynamic, semantic, 4d, ar, gaussian splatting, segmentation, understanding, deformation  
- **[Semantic-Guided Progressive Object Removal with Gaussian Splatting](https://arxiv.org/abs/2607.04144v1)**  
  Authors: Xianliang Huang, Chen Xiao, Yuanxiang Ni, Guanming Liu, Mingkai Liu, Dikai Fan, Xiao Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.04144v1.pdf)  
  Keywords: semantic, robotics, efficient, ar, gaussian splatting, vr, high-fidelity  
- **[SharpSplat: Edge-Regularized 3D Gaussian Splatting for High Fidelity Urban Building Reconstruction from UAV images](https://arxiv.org/abs/2607.03872v1)**  
  Authors: Porus Vaid, Shivam Chopra, Vaibhav Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03872v1.pdf)  
  Keywords: semantic, ar, gaussian splatting, 3d gaussian, high-fidelity  
- **[X-Splat: Gaussian Splatting for 3D CBCT Generation from Single Panoramic Radiograph](https://arxiv.org/abs/2607.02099v1)**  
  Authors: Tomasz Szczepański, Szymon Płotka, Michal K. Grzeszczyk, Tomasz Trzciński, Arkadiusz Sitek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.02099v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, segmentation, geometry, nerf  



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