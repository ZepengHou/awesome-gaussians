# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-06-02 02:40:37

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
- [Acceleration](#acceleration) (220 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (340 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (381 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (80 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (393 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (46 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (427 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (239 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (28 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (134 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (226 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, mapping, survey, animation, geometry, ar  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: gaussian splatting, motion, tracking, survey, 3d gaussian, geometry, efficient, slam, 3d reconstruction, ar  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: gaussian splatting, survey, 3d gaussian, vr, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: gaussian splatting, mapping, ray tracing, survey, 3d gaussian, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: gaussian splatting, motion, mapping, face, localization, survey, 3d gaussian, efficient, slam, dynamic, tracking, ar  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: gaussian splatting, robotics, survey, 3d gaussian, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: nerf, gaussian splatting, survey, 3d gaussian, geometry, efficient, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, survey, 3d gaussian, 4d, compact, efficient, compression, dynamic, high-fidelity, ar  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: nerf, gaussian splatting, mapping, localization, robotics, semantic, survey, 3d gaussian, slam, understanding, ar  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: gaussian splatting, mapping, localization, robotics, efficient, survey, 3d gaussian, semantic, slam, high-fidelity, ar  

### Acceleration

*Showing the latest 50 out of 220 papers*

- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, lightweight, efficient, 3d gaussian, ar, compact, fast  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: gaussian splatting, motion, geometry, dynamic, ar, fast  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, face, shadow, 3d gaussian, illumination, ar, fast  
- **[HiGS: A Hierarchical Rendering Architecture for Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2606.00352v1)**  
  Authors: Dawid Pająk, Martin Bisson, Rodolfo Lima  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00352v1.pdf)  
  Keywords: gaussian splatting, fast, 3d gaussian, acceleration, ar  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, 3d gaussian, autonomous driving, ar, 3d reconstruction, fast  
- **[Smaller and Faster 3DGS via Post-Training Dictionary Learning](https://arxiv.org/abs/2605.30396v1)**  
  Authors: Jiarong Gong, Jonas Unger, Ehsan Miandji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30396v1.pdf)  
  Keywords: gaussian splatting, real-time rendering, 3d gaussian, compression, ar, fast  
- **[Eulerian Gaussian Splatting using Hashed Probability Pyramids](https://arxiv.org/abs/2605.29136v1)**  
  Authors: Mia Gaia Polansky, George Kopanas, Stephan Garbin, Todd Zickler, Dor Verbin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29136v1.pdf)  
  Keywords: nerf, gaussian splatting, efficient, 3d gaussian, ar, fast  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: gaussian splatting, face, real-time rendering, 3d reconstruction, 3d gaussian, geometry, ar, high-fidelity, fast  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: sparse-view, gaussian splatting, relightable, relighting, 3d gaussian, illumination, geometry, lighting, ar, high-fidelity, fast  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, 3d gaussian, geometry, ar, fast  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, lightweight, efficient, 3d gaussian, ar, compact, fast  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: gaussian splatting, motion, geometry, dynamic, ar, fast  
- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v1)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v1.pdf)  
  Keywords: gaussian splatting, geometry, understanding, 3d reconstruction, ar  
- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, avatar, high-fidelity, ar  
- **[LEGS: Fine-Tuning Teleop-Free VLAs for Humanoid Loco-manipulation in an Embodied Gaussian Splatting World](https://arxiv.org/abs/2606.01458v1)**  
  Authors: Hojune Kim, Timothy Chen, Jiankai Sun, Lars W. Osterberg, Qianzhong Chen, Ke Wang, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01458v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://legsvla.github.io/.)  
  Keywords: gaussian splatting, motion, human, body, 3d gaussian, ar  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, efficient, 3d gaussian, high-fidelity, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, face, shadow, 3d gaussian, illumination, ar, fast  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: nerf, gaussian splatting, head, deformation, 4d, 3d gaussian, understanding, dynamic, compact, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: nerf, gaussian splatting, motion, face, 3d gaussian, geometry, understanding, ar  

### Avatar Generation

*Showing the latest 50 out of 340 papers*

- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, avatar, high-fidelity, ar  
- **[LEGS: Fine-Tuning Teleop-Free VLAs for Humanoid Loco-manipulation in an Embodied Gaussian Splatting World](https://arxiv.org/abs/2606.01458v1)**  
  Authors: Hojune Kim, Timothy Chen, Jiankai Sun, Lars W. Osterberg, Qianzhong Chen, Ke Wang, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01458v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://legsvla.github.io/.)  
  Keywords: gaussian splatting, motion, human, body, 3d gaussian, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, face, shadow, 3d gaussian, illumination, ar, fast  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: nerf, gaussian splatting, head, deformation, 4d, 3d gaussian, understanding, dynamic, compact, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: nerf, gaussian splatting, motion, face, 3d gaussian, geometry, understanding, ar  
- **[GeoSAM-3D: Geodesic Prompt Propagation for Open-Vocabulary 3D Scene Segmentation from Monocular Video](https://arxiv.org/abs/2606.00447v1)**  
  Authors: Arun Sharma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00447v1.pdf)  
  Keywords: gaussian splatting, face, head, 3d gaussian, segmentation, ar  
- **[Benchmarking Single-Step Inpainting Methods for Multi-Object 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2605.30987v1)**  
  Authors: Finn Dröge, Cecilia Curreli, Abhishek Saroha, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30987v1.pdf)  
  Keywords: face, gaussian splatting, ar, 3d gaussian  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, gaussian splatting, face, urban scene, 3d reconstruction, geometry, ar, high-fidelity, large scene  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: motion, semantic, human, 4d, 3d gaussian, dynamic, ar  
- **[Comparative evaluation of photogrammetric reconstruction methods and 3D Gaussian Splatting for road surface roughness analysis](https://arxiv.org/abs/2605.29452v1)**  
  Authors: Marouane Elmegdar, Teng Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29452v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, geometry, segmentation, 3d reconstruction, ar  

### Dynamic Scene

*Showing the latest 50 out of 381 papers*

- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: gaussian splatting, motion, geometry, dynamic, ar, fast  
- **[LEGS: Fine-Tuning Teleop-Free VLAs for Humanoid Loco-manipulation in an Embodied Gaussian Splatting World](https://arxiv.org/abs/2606.01458v1)**  
  Authors: Hojune Kim, Timothy Chen, Jiankai Sun, Lars W. Osterberg, Qianzhong Chen, Ke Wang, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01458v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://legsvla.github.io/.)  
  Keywords: gaussian splatting, motion, human, body, 3d gaussian, ar  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, efficient, 3d gaussian, high-fidelity, ar  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: nerf, gaussian splatting, head, deformation, 4d, 3d gaussian, understanding, dynamic, compact, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: nerf, gaussian splatting, motion, face, 3d gaussian, geometry, understanding, ar  
- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: gaussian splatting, tracking, efficient, dynamic, 3d reconstruction, ar  
- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: gaussian splatting, mapping, deformation, 3d gaussian, geometry, slam, tracking, ar  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, dynamic, high-fidelity, ar  
- **[Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation](https://arxiv.org/abs/2605.30855v2)**  
  Authors: Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30855v2.pdf)  
  Keywords: geometry, gaussian splatting, dynamic, ar  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, mapping, survey, animation, geometry, ar  

### Few-shot

*Showing the latest 50 out of 80 papers*

- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, lightweight, efficient, 3d gaussian, ar, compact, fast  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, efficient, 3d gaussian, high-fidelity, ar  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: sparse-view, gaussian splatting, relightable, relighting, 3d gaussian, illumination, geometry, lighting, ar, high-fidelity, fast  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, 3d gaussian, geometry, ar, fast  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v2)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v2.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, deformation, 3d gaussian, ar, fast  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: gaussian splatting, mapping, sparse view, 3d gaussian, illumination, lighting, outdoor, dynamic, ar, high-fidelity, autonomous driving, fast  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: sparse-view, gaussian splatting, face, 3d gaussian, geometry, high-fidelity, ar  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d gaussian, geometry, 3d reconstruction, ar  
- **[PairDropGS: Paired Dropout-Induced Consistency Regularization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.12072v2)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Xingtao Wang, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12072v2.pdf)  
  Keywords: sparse-view, gaussian splatting, 3d gaussian, geometry, ar  
- **[VidSplat: Gaussian Splatting Reconstruction with Geometry-Guided Video Diffusion Priors](https://arxiv.org/abs/2605.11424v1)**  
  Authors: Jimin Tang, Wenyuan Zhang, Junsheng Zhou, Zian Huang, Kanle Shi, Shenkun Xu, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.11424v1.pdf)  
  Keywords: sparse-view, gaussian splatting, face, geometry, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 393 papers*

- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: gaussian splatting, motion, geometry, dynamic, ar, fast  
- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v1)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v1.pdf)  
  Keywords: gaussian splatting, geometry, understanding, 3d reconstruction, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: nerf, gaussian splatting, motion, face, 3d gaussian, geometry, understanding, ar  
- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: gaussian splatting, tracking, efficient, dynamic, 3d reconstruction, ar  
- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: gaussian splatting, mapping, deformation, 3d gaussian, geometry, slam, tracking, ar  
- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, understanding, ar  
- **[Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation](https://arxiv.org/abs/2605.30855v2)**  
  Authors: Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30855v2.pdf)  
  Keywords: geometry, gaussian splatting, dynamic, ar  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, mapping, survey, animation, geometry, ar  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, 3d gaussian, autonomous driving, ar, 3d reconstruction, fast  

### Large Scene

- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, gaussian splatting, face, urban scene, 3d reconstruction, geometry, ar, high-fidelity, large scene  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: gaussian splatting, urban scene, 3d gaussian, geometry, ar  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: ar, mapping, outdoor  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: gaussian splatting, mapping, sparse view, 3d gaussian, illumination, lighting, outdoor, dynamic, ar, high-fidelity, autonomous driving, fast  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: gaussian splatting, face, efficient, 3d gaussian, geometry, outdoor, dynamic, high-fidelity, ar  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, outdoor, ar  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: ar, gaussian splatting, outdoor, 3d gaussian  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: gaussian splatting, mapping, outdoor, localization, 3d gaussian, slam, ar  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: gaussian splatting, urban scene, semantic, 3d gaussian, geometry, understanding, segmentation, compact, ar  
- **[Neural Harmonic Textures for High-Quality Primitive Based Neural Reconstruction](https://arxiv.org/abs/2604.01204v2)**  
  Authors: Jorge Condor, Nicolas Moenne-Loccoz, Merlin Nimier-David, Piotr Didyk, Zan Gojcic, Qi Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.01204v2.pdf)  
  Keywords: gaussian splatting, semantic, 3d gaussian, ar, large scene  

### Model Compression

*Showing the latest 50 out of 427 papers*

- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, lightweight, efficient, 3d gaussian, ar, compact, fast  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, efficient, 3d gaussian, high-fidelity, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: nerf, gaussian splatting, head, deformation, 4d, 3d gaussian, understanding, dynamic, compact, ar  
- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: gaussian splatting, tracking, efficient, dynamic, 3d reconstruction, ar  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, dynamic, high-fidelity, ar  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, 3d gaussian, ar  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, 3d gaussian, autonomous driving, ar, 3d reconstruction, fast  
- **[FRUC: Feedforward Dynamic Scene Reconstruction from Uncalibrated Collaborative Driving Views](https://arxiv.org/abs/2605.29997v1)**  
  Authors: Yihang Tao, Yu Guo, Zhengru Fang, Haonan An, Yuguang Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29997v1.pdf)  
  Keywords: gaussian splatting, efficient, 3d gaussian, geometry, dynamic, ar  
- **[Smaller and Faster 3DGS via Post-Training Dictionary Learning](https://arxiv.org/abs/2605.30396v1)**  
  Authors: Jiarong Gong, Jonas Unger, Ehsan Miandji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30396v1.pdf)  
  Keywords: gaussian splatting, real-time rendering, 3d gaussian, compression, ar, fast  

### Quality Enhancement

*Showing the latest 50 out of 239 papers*

- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, avatar, high-fidelity, ar  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: nerf, sparse-view, gaussian splatting, motion, efficient, 3d gaussian, high-fidelity, ar  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: gaussian splatting, robotics, efficient, dynamic, high-fidelity, ar  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: nerf, gaussian splatting, face, urban scene, 3d reconstruction, geometry, ar, high-fidelity, large scene  
- **[POINav: Benchmarking and Enhancing Final-Meters Arrival in Real-World Vision-Language Navigation](https://arxiv.org/abs/2605.28237v1)**  
  Authors: Ruiyan Gong, Meisheng Zhang, Yuxiang Zhao, Mingchao Sun, Yanfen Shen, Zedong Chu, Zhining Gu, Wei Guo, Xiaolong Cheng, Qiming Li, Kangning Niu, Yanqing Zhu, Xiaolong Wu, Tianlun Li, Mu Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.28237v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, 3d gaussian  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: gaussian splatting, face, real-time rendering, 3d reconstruction, 3d gaussian, geometry, ar, high-fidelity, fast  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: sparse-view, gaussian splatting, relightable, relighting, 3d gaussian, illumination, geometry, lighting, ar, high-fidelity, fast  
- **[Depth Peeling for High-Fidelity Gaussian-Enhanced Surfel Rendering](https://arxiv.org/abs/2605.25345v1)**  
  Authors: Keyang Ye, Hongzhi Wu, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25345v1.pdf)  
  Keywords: nerf, gaussian splatting, 3d gaussian, high-fidelity, ar  
- **[ParkingWorld: End-to-End Autonomous Parking Reinforcement Learning from Corrective Experience in 3DGS Simulation](https://arxiv.org/abs/2605.25029v2)**  
  Authors: Zhengcheng Yu, Changze Li, Haoran Liu, Tong Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25029v2.pdf)  
  Keywords: gaussian splatting, face, head, efficient, human, 3d gaussian, high-fidelity, ar  
- **[Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving](https://arxiv.org/abs/2605.22809v2)**  
  Authors: Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22809v2.pdf)  
  Keywords: gaussian splatting, 4d, autonomous driving, high-fidelity, ar  

### Ray Tracing

- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, face, shadow, 3d gaussian, illumination, ar, fast  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ray casting, gaussian splatting, ar, 3d gaussian  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: gaussian splatting, ray tracing, 3d gaussian, geometry, high-fidelity, ar  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: gaussian splatting, ray tracing, robotics, efficient, 3d gaussian, semantic, lighting, dynamic, tracking, ar  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: gaussian splatting, ray tracing, face, reflection, ar  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: gaussian splatting, mapping, ray tracing, face, localization, efficient, 3d gaussian, semantic, slam, tracking, ar  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: gaussian splatting, mapping, ray tracing, relightable, shadow, 3d gaussian, reflection, ar  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: nerf, gaussian splatting, ray tracing, face, real-time rendering, efficient, 3d gaussian, geometry, ar, high-fidelity, fast  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: gaussian splatting, mapping, ray tracing, survey, 3d gaussian, ar  

### Relighting

*Showing the latest 50 out of 134 papers*

- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, face, shadow, 3d gaussian, illumination, ar, fast  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: sparse-view, gaussian splatting, relightable, relighting, 3d gaussian, illumination, geometry, lighting, ar, high-fidelity, fast  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: gaussian splatting, head, semantic, human, 3d gaussian, lighting, segmentation, ar  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: gaussian splatting, motion, 3d gaussian, human, compression, lighting, understanding, ar  
- **[A Geometric Algebra-Informed 3DGS Framework for Wireless Channel Prediction](https://arxiv.org/abs/2605.19065v3)**  
  Authors: Jingzhou Shen, Tianya Zhao, Xuyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19065v3.pdf)  
  Keywords: ar, gaussian splatting, reflection, 3d gaussian  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: gaussian splatting, face, real-time rendering, 3d gaussian, reflection, high-fidelity, ar  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, compression, reflection, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: gaussian splatting, mapping, sparse view, 3d gaussian, illumination, lighting, outdoor, dynamic, ar, high-fidelity, autonomous driving, fast  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: gaussian splatting, semantic, 3d gaussian, lighting, high-fidelity, ar  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: gaussian splatting, tracking, efficient, dynamic, 3d reconstruction, ar  
- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: gaussian splatting, mapping, deformation, 3d gaussian, geometry, slam, tracking, ar  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, mapping, survey, animation, geometry, ar  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, 3d gaussian, ar  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: gaussian splatting, motion, mapping, semantic, 3d gaussian, geometry, human, dynamic, ar  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: ar, mapping, outdoor  
- **[Efficient Sparse-to-Dense Visual Localization via Compact Gaussian Scene Representation and Accelerated Dense Pose Estimation](https://arxiv.org/abs/2605.17777v1)**  
  Authors: Zizhuo Li, Songchu Deng, Linfeng Tang, Jiayi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17777v1.pdf)  
  Keywords: gaussian splatting, localization, head, efficient, 3d gaussian, compact, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: gaussian splatting, mapping, sparse view, 3d gaussian, illumination, lighting, outdoor, dynamic, ar, high-fidelity, autonomous driving, fast  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: gaussian splatting, tracking, 4d, autonomous driving, dynamic, high-fidelity, ar  
- **[PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization](https://arxiv.org/abs/2605.12144v1)**  
  Authors: Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12144v1.pdf)  
  Keywords: gaussian splatting, lightweight, localization, 3d gaussian, ar  

### Scene Understanding

*Showing the latest 50 out of 226 papers*

- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v1)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v1.pdf)  
  Keywords: gaussian splatting, geometry, understanding, 3d reconstruction, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: gaussian splatting, ray tracing, efficient, 3d gaussian, geometry, semantic, reflection, segmentation, ar  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: nerf, gaussian splatting, head, deformation, 4d, 3d gaussian, understanding, dynamic, compact, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: nerf, gaussian splatting, motion, face, 3d gaussian, geometry, understanding, ar  
- **[GeoSAM-3D: Geodesic Prompt Propagation for Open-Vocabulary 3D Scene Segmentation from Monocular Video](https://arxiv.org/abs/2606.00447v1)**  
  Authors: Arun Sharma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00447v1.pdf)  
  Keywords: gaussian splatting, face, head, 3d gaussian, segmentation, ar  
- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: gaussian splatting, semantic, geometry, understanding, ar  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: motion, semantic, human, 4d, 3d gaussian, dynamic, ar  
- **[BitC-3DGS: High-Capacity 3D Gaussian Splatting Watermarking via Bit Compression](https://arxiv.org/abs/2605.29583v1)**  
  Authors: Yuquan Bi, Baosheng Yu, Yingke Lei, Jianwei Yang, Hongsong Wang, Jie Gui, Yuan Yan Tang, James Tin-Yau Kwok  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29583v1.pdf)  
  Keywords: gaussian splatting, semantic, 3d gaussian, compression, ar  
- **[Learning Representations from 3D Gaussian Splats](https://arxiv.org/abs/2605.29549v1)**  
  Authors: Julia Farganus, Krzysztof Żurawicki, Arkadiusz Gaweł, Weronika Jakubowska, Halina Kwaśnicka  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29549v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, understanding, ar  
- **[Comparative evaluation of photogrammetric reconstruction methods and 3D Gaussian Splatting for road surface roughness analysis](https://arxiv.org/abs/2605.29452v1)**  
  Authors: Marouane Elmegdar, Teng Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29452v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, geometry, segmentation, 3d reconstruction, ar  



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