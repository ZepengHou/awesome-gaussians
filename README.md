# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-06-07 02:36:18

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

- [3DGS Surveys](#3dgs-surveys) (15 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (221 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (343 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (382 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (82 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (393 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (46 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (430 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (242 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (28 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (132 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (147 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (226 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, mapping, gaussian splatting, survey, animation, ar  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: efficient, tracking, geometry, 3d reconstruction, ar, 3d gaussian, gaussian splatting, survey, motion, slam  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, vr, survey, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ray tracing, mapping, 3d gaussian, gaussian splatting, survey, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: efficient, face, dynamic, localization, tracking, ar, mapping, 3d gaussian, gaussian splatting, survey, motion, slam  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, 3d gaussian, gaussian splatting, survey, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: efficient, geometry, nerf, 3d gaussian, gaussian splatting, survey, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: efficient, dynamic, 3d reconstruction, 4d, compact, 3d gaussian, gaussian splatting, survey, ar, high-fidelity, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: localization, robotics, semantic, slam, nerf, mapping, 3d gaussian, gaussian splatting, survey, ar, understanding  

### Acceleration

*Showing the latest 50 out of 221 papers*

- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: efficient, dynamic, 3d gaussian, gaussian splatting, ar, acceleration, fast, compression  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: efficient, semantic, segmentation, compact, 3d gaussian, gaussian splatting, ar, fast, understanding  
- **[VEDAL: Variational Error-Driven Asynchronous Learning for 3D Gaussian Splatting Pruning](https://arxiv.org/abs/2606.02346v1)**  
  Authors: Aoduo Li, Jiancheng Li, Huan Ye, Hongjian Xu, Shiting Wu, Xiujun Zhang, Zimeng Li, Xuhang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02346v1.pdf)  
  Keywords: head, nerf, 3d gaussian, gaussian splatting, real-time rendering, ar, compression  
- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: efficient, nerf, compact, 3d gaussian, gaussian splatting, ar, sparse-view, lightweight, fast  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: dynamic, geometry, ar, gaussian splatting, motion, fast  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: face, shadow, global illumination, illumination, 3d gaussian, gaussian splatting, ar, fast  
- **[HiGS: A Hierarchical Rendering Architecture for Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2606.00352v1)**  
  Authors: Dawid Pająk, Martin Bisson, Rodolfo Lima  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00352v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, acceleration, fast  
- **[Supercharging Thermal Gaussian Splatting with Depth Estimation](https://arxiv.org/abs/2605.30328v1)**  
  Authors: Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30328v1.pdf)  
  Keywords: efficient, robotics, 3d reconstruction, 3d gaussian, gaussian splatting, ar, fast, autonomous driving  
- **[Smaller and Faster 3DGS via Post-Training Dictionary Learning](https://arxiv.org/abs/2605.30396v1)**  
  Authors: Jiarong Gong, Jonas Unger, Ehsan Miandji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30396v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, real-time rendering, ar, fast, compression  
- **[Eulerian Gaussian Splatting using Hashed Probability Pyramids](https://arxiv.org/abs/2605.29136v1)**  
  Authors: Mia Gaia Polansky, George Kopanas, Stephan Garbin, Todd Zickler, Dor Verbin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.29136v1.pdf)  
  Keywords: efficient, nerf, 3d gaussian, gaussian splatting, ar, fast  

### Applications

*Showing the latest 50 out of 995 papers*

- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: efficient, dynamic, 3d gaussian, gaussian splatting, ar, acceleration, fast, compression  
- **[Unpaired RGB-Thermal Gaussian-Splatting Using Visual Geometric Transformers](https://arxiv.org/abs/2606.05491v1)**  
  Authors: Jean Cordonnier, Chenghao Xu, Olga Fink, Malcolm Mielle  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05491v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting  
- **[Geometry Gaussians: Decoupling Appearance and Geometry in Gaussian Splatting](https://arxiv.org/abs/2606.05124v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05124v1.pdf)  
  Keywords: face, geometry, 3d gaussian, gaussian splatting, ar  
- **[ZipSplat: Fewer Gaussians, Better Splats](https://arxiv.org/abs/2606.05102v1)**  
  Authors: Alexander Veicht, Sunghwan Hong, Dániel Baráth, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05102v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://veichta.com/zipsplat}{https://veichta.com/zipsplat}}$.)  
  Keywords: nerf, compact, 3d gaussian, gaussian splatting, ar, lightweight  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: efficient, head, mapping, 3d gaussian, gaussian splatting, ar  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: efficient, dynamic, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity, compression  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: efficient, semantic, segmentation, compact, 3d gaussian, gaussian splatting, ar, fast, understanding  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: dynamic, human, compact, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[UnsOcc: 3D Semantic Occupancy Prediction in Unstructured Scene via Rendering Fusion](https://arxiv.org/abs/2606.03581v1)**  
  Authors: Ye Wu, Ruiqi Song, Baiyong Ding, Nanxin Zeng, Junjie Cheng, Yunfeng Ai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03581v1.pdf)  
  Keywords: semantic, segmentation, gaussian splatting, ar, autonomous driving  

### Avatar Generation

*Showing the latest 50 out of 343 papers*

- **[Geometry Gaussians: Decoupling Appearance and Geometry in Gaussian Splatting](https://arxiv.org/abs/2606.05124v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05124v1.pdf)  
  Keywords: face, geometry, 3d gaussian, gaussian splatting, ar  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: efficient, head, mapping, 3d gaussian, gaussian splatting, ar  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: dynamic, human, compact, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[Characterizing Detectability in 3DGS Poisoning: A Stage-wise Benchmark](https://arxiv.org/abs/2606.03499v1)**  
  Authors: Quoc-Anh Bui-Huynh, Thanh Duc Ngo, Xue Geng, Kaixin Xu, Wang Zhe, Xulei Yang, Ngai-Man Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03499v1.pdf)  
  Keywords: face, dynamic, geometry, 3d gaussian, gaussian splatting, ar  
- **[PersistGS: Differentiable Physics for Object Permanence in 4D Gaussian Splatting](https://arxiv.org/abs/2606.03479v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03479v1.pdf)  
  Keywords: body, dynamic, 4d, 3d gaussian, gaussian splatting, ar  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: efficient, dynamic, head, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[VEDAL: Variational Error-Driven Asynchronous Learning for 3D Gaussian Splatting Pruning](https://arxiv.org/abs/2606.02346v1)**  
  Authors: Aoduo Li, Jiancheng Li, Huan Ye, Hongjian Xu, Shiting Wu, Xiujun Zhang, Zimeng Li, Xuhang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02346v1.pdf)  
  Keywords: head, nerf, 3d gaussian, gaussian splatting, real-time rendering, ar, compression  
- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[LEGS: Fine-Tuning Teleop-Free VLAs for Humanoid Loco-manipulation in an Embodied Gaussian Splatting World](https://arxiv.org/abs/2606.01458v1)**  
  Authors: Hojune Kim, Timothy Chen, Jiankai Sun, Lars W. Osterberg, Qianzhong Chen, Ke Wang, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01458v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://legsvla.github.io/.)  
  Keywords: body, human, ar, 3d gaussian, gaussian splatting, motion  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: face, shadow, global illumination, illumination, 3d gaussian, gaussian splatting, ar, fast  

### Dynamic Scene

*Showing the latest 50 out of 382 papers*

- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: efficient, dynamic, 3d gaussian, gaussian splatting, ar, acceleration, fast, compression  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: efficient, dynamic, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity, compression  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: dynamic, human, compact, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[Characterizing Detectability in 3DGS Poisoning: A Stage-wise Benchmark](https://arxiv.org/abs/2606.03499v1)**  
  Authors: Quoc-Anh Bui-Huynh, Thanh Duc Ngo, Xue Geng, Kaixin Xu, Wang Zhe, Xulei Yang, Ngai-Man Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03499v1.pdf)  
  Keywords: face, dynamic, geometry, 3d gaussian, gaussian splatting, ar  
- **[PersistGS: Differentiable Physics for Object Permanence in 4D Gaussian Splatting](https://arxiv.org/abs/2606.03479v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03479v1.pdf)  
  Keywords: body, dynamic, 4d, 3d gaussian, gaussian splatting, ar  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: efficient, dynamic, head, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: dynamic, geometry, ar, gaussian splatting, motion, fast  
- **[LEGS: Fine-Tuning Teleop-Free VLAs for Humanoid Loco-manipulation in an Embodied Gaussian Splatting World](https://arxiv.org/abs/2606.01458v1)**  
  Authors: Hojune Kim, Timothy Chen, Jiankai Sun, Lars W. Osterberg, Qianzhong Chen, Ke Wang, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01458v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://legsvla.github.io/.)  
  Keywords: body, human, ar, 3d gaussian, gaussian splatting, motion  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: efficient, nerf, ar, 3d gaussian, gaussian splatting, motion, sparse-view, high-fidelity  

### Few-shot

*Showing the latest 50 out of 82 papers*

- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, outdoor, nerf, 3d gaussian, gaussian splatting, ar, sparse-view, high-fidelity  
- **[BEAST3D: Animal behavioral analysis and neural encoding from multi-view video via Gaussian splatting](https://arxiv.org/abs/2606.02937v1)**  
  Authors: Yanchen Wang, Lenny Aharon, Wangshu Zhu, Kyle Daruwalla, Linghua Zhang, Jiaru Zou, Selmaan Chettih, Helen Hou, Liam Paninski, Matthew R Whiteway  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02937v1.pdf)  
  Keywords: geometry, 3d reconstruction, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: efficient, nerf, compact, 3d gaussian, gaussian splatting, ar, sparse-view, lightweight, fast  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: efficient, nerf, ar, 3d gaussian, gaussian splatting, motion, sparse-view, high-fidelity  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: relighting, illumination, geometry, relightable, 3d gaussian, gaussian splatting, lighting, ar, sparse-view, fast, high-fidelity  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: geometry, nerf, ar, 3d gaussian, gaussian splatting, motion, sparse-view, fast  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v2)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v2.pdf)  
  Keywords: deformation, nerf, 3d gaussian, gaussian splatting, ar, sparse-view, fast  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: dynamic, autonomous driving, illumination, outdoor, mapping, 3d gaussian, gaussian splatting, lighting, ar, sparse view, fast, high-fidelity  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: face, geometry, 3d gaussian, gaussian splatting, ar, sparse-view, high-fidelity  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: geometry, 3d reconstruction, 3d gaussian, gaussian splatting, ar, sparse-view  

### Geometry Reconstruction

*Showing the latest 50 out of 393 papers*

- **[Geometry Gaussians: Decoupling Appearance and Geometry in Gaussian Splatting](https://arxiv.org/abs/2606.05124v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05124v1.pdf)  
  Keywords: face, geometry, 3d gaussian, gaussian splatting, ar  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: efficient, dynamic, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity, compression  
- **[Characterizing Detectability in 3DGS Poisoning: A Stage-wise Benchmark](https://arxiv.org/abs/2606.03499v1)**  
  Authors: Quoc-Anh Bui-Huynh, Thanh Duc Ngo, Xue Geng, Kaixin Xu, Wang Zhe, Xulei Yang, Ngai-Man Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03499v1.pdf)  
  Keywords: face, dynamic, geometry, 3d gaussian, gaussian splatting, ar  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: efficient, dynamic, head, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[BEAST3D: Animal behavioral analysis and neural encoding from multi-view video via Gaussian splatting](https://arxiv.org/abs/2606.02937v1)**  
  Authors: Yanchen Wang, Lenny Aharon, Wangshu Zhu, Kyle Daruwalla, Linghua Zhang, Jiaru Zou, Selmaan Chettih, Helen Hou, Liam Paninski, Matthew R Whiteway  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02937v1.pdf)  
  Keywords: geometry, 3d reconstruction, 3d gaussian, gaussian splatting, ar, sparse-view  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: dynamic, geometry, ar, gaussian splatting, motion, fast  
- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v2)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v2.pdf)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, understanding  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: reflection, efficient, ray tracing, semantic, segmentation, geometry, 3d gaussian, gaussian splatting, ar  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: face, geometry, nerf, ar, 3d gaussian, gaussian splatting, motion, understanding  

### Large Scene

- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, outdoor, nerf, 3d gaussian, gaussian splatting, ar, sparse-view, high-fidelity  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: face, geometry, 3d reconstruction, nerf, urban scene, ar, gaussian splatting, large scene, high-fidelity  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: geometry, urban scene, 3d gaussian, gaussian splatting, ar  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, ar, outdoor  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: dynamic, autonomous driving, illumination, outdoor, mapping, 3d gaussian, gaussian splatting, lighting, ar, sparse view, fast, high-fidelity  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: efficient, face, dynamic, geometry, outdoor, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: geometry, outdoor, 3d gaussian, gaussian splatting, ar  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, outdoor  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: localization, outdoor, mapping, 3d gaussian, gaussian splatting, ar, slam  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: semantic, segmentation, geometry, urban scene, compact, 3d gaussian, gaussian splatting, ar, understanding  

### Model Compression

*Showing the latest 50 out of 430 papers*

- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: efficient, dynamic, 3d gaussian, gaussian splatting, ar, acceleration, fast, compression  
- **[ZipSplat: Fewer Gaussians, Better Splats](https://arxiv.org/abs/2606.05102v1)**  
  Authors: Alexander Veicht, Sunghwan Hong, Dániel Baráth, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05102v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://veichta.com/zipsplat}{https://veichta.com/zipsplat}}$.)  
  Keywords: nerf, compact, 3d gaussian, gaussian splatting, ar, lightweight  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: efficient, head, mapping, 3d gaussian, gaussian splatting, ar  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: efficient, dynamic, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity, compression  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: efficient, semantic, segmentation, compact, 3d gaussian, gaussian splatting, ar, fast, understanding  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: dynamic, human, compact, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: efficient, dynamic, head, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, outdoor, nerf, 3d gaussian, gaussian splatting, ar, sparse-view, high-fidelity  
- **[VEDAL: Variational Error-Driven Asynchronous Learning for 3D Gaussian Splatting Pruning](https://arxiv.org/abs/2606.02346v1)**  
  Authors: Aoduo Li, Jiancheng Li, Huan Ye, Hongjian Xu, Shiting Wu, Xiujun Zhang, Zimeng Li, Xuhang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02346v1.pdf)  
  Keywords: head, nerf, 3d gaussian, gaussian splatting, real-time rendering, ar, compression  

### Quality Enhancement

*Showing the latest 50 out of 242 papers*

- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: efficient, dynamic, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity, compression  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: dynamic, human, compact, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: efficient, dynamic, head, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: efficient, outdoor, nerf, 3d gaussian, gaussian splatting, ar, sparse-view, high-fidelity  
- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: face, 3d gaussian, gaussian splatting, ar, avatar, high-fidelity  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: efficient, nerf, ar, 3d gaussian, gaussian splatting, motion, sparse-view, high-fidelity  
- **[DSD-GS: Dynamic-Static Decomposition of Gaussian Splatting for Efficient and High-Fidelity Dynamic Scene Reconstruction](https://arxiv.org/abs/2605.30863v1)**  
  Authors: Youngtae Han, Sung-hwan Han, Youngmin Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30863v1.pdf)  
  Keywords: efficient, dynamic, robotics, gaussian splatting, ar, high-fidelity  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: face, geometry, 3d reconstruction, nerf, urban scene, ar, gaussian splatting, large scene, high-fidelity  
- **[POINav: Benchmarking and Enhancing Final-Meters Arrival in Real-World Vision-Language Navigation](https://arxiv.org/abs/2605.28237v1)**  
  Authors: Ruiyan Gong, Meisheng Zhang, Yuxiang Zhao, Mingchao Sun, Yanfen Shen, Zedong Chu, Zhining Gu, Wei Guo, Xiaolong Cheng, Qiming Li, Kangning Niu, Yanqing Zhu, Xiaolong Wu, Tianlun Li, Mu Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.28237v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity  
- **[Gaussian-Voxel Duet: A Dual-Scaffolding Hybrid Representation for Fast and Accurate Monocular Surface Reconstruction](https://arxiv.org/abs/2605.26616v1)**  
  Authors: Zhenhua Du, Zhen Tan, Haoyu Zhang, Dewen Hu, Shuaifeng Zhi, Peidong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26616v1.pdf)  
  Keywords: face, geometry, 3d reconstruction, 3d gaussian, gaussian splatting, real-time rendering, ar, fast, high-fidelity  

### Ray Tracing

- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: reflection, efficient, ray tracing, semantic, segmentation, geometry, 3d gaussian, gaussian splatting, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: face, shadow, global illumination, illumination, 3d gaussian, gaussian splatting, ar, fast  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, ray casting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: ray tracing, geometry, 3d gaussian, gaussian splatting, ar, high-fidelity  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: efficient, dynamic, tracking, robotics, ray tracing, semantic, 3d gaussian, gaussian splatting, lighting, ar  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: reflection, face, ray tracing, gaussian splatting, ar  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: efficient, face, localization, ray tracing, semantic, mapping, 3d gaussian, gaussian splatting, tracking, ar, slam  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: reflection, shadow, ray tracing, relightable, mapping, 3d gaussian, gaussian splatting, ar  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: efficient, face, ray tracing, geometry, nerf, 3d gaussian, gaussian splatting, real-time rendering, ar, fast, high-fidelity  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ray tracing, mapping, 3d gaussian, gaussian splatting, survey, ar  

### Relighting

*Showing the latest 50 out of 132 papers*

- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: reflection, efficient, ray tracing, semantic, segmentation, geometry, 3d gaussian, gaussian splatting, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: face, shadow, global illumination, illumination, 3d gaussian, gaussian splatting, ar, fast  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: relighting, illumination, geometry, relightable, 3d gaussian, gaussian splatting, lighting, ar, sparse-view, fast, high-fidelity  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: semantic, head, human, segmentation, 3d gaussian, gaussian splatting, lighting, ar  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: human, understanding, ar, 3d gaussian, gaussian splatting, lighting, motion, compression  
- **[A Geometric Algebra-Informed 3DGS Framework for Wireless Channel Prediction](https://arxiv.org/abs/2605.19065v3)**  
  Authors: Jingzhou Shen, Tianya Zhao, Xuyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19065v3.pdf)  
  Keywords: reflection, ar, 3d gaussian, gaussian splatting  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: reflection, face, 3d gaussian, gaussian splatting, real-time rendering, ar, high-fidelity  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: reflection, 3d gaussian, gaussian splatting, ar, compression  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: dynamic, autonomous driving, illumination, outdoor, mapping, 3d gaussian, gaussian splatting, lighting, ar, sparse view, fast, high-fidelity  
- **[3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation](https://arxiv.org/abs/2605.15398v1)**  
  Authors: Nicole Meng, Zheyuan Liu, Meng Jiang, Yingjie Lao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.15398v1.pdf)  
  Keywords: semantic, 3d gaussian, gaussian splatting, lighting, ar, high-fidelity  

### SLAM

*Showing the latest 50 out of 147 papers*

- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: efficient, head, mapping, 3d gaussian, gaussian splatting, ar  
- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: efficient, dynamic, 3d reconstruction, gaussian splatting, tracking, ar  
- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v1)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v1.pdf)  
  Keywords: deformation, geometry, mapping, 3d gaussian, gaussian splatting, tracking, ar, slam  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, mapping, gaussian splatting, survey, animation, ar  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: efficient, mapping, 3d gaussian, gaussian splatting, ar  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: dynamic, semantic, human, geometry, ar, mapping, 3d gaussian, gaussian splatting, motion  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, ar, outdoor  
- **[Efficient Sparse-to-Dense Visual Localization via Compact Gaussian Scene Representation and Accelerated Dense Pose Estimation](https://arxiv.org/abs/2605.17777v1)**  
  Authors: Zizhuo Li, Songchu Deng, Linfeng Tang, Jiayi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17777v1.pdf)  
  Keywords: efficient, localization, head, compact, 3d gaussian, gaussian splatting, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: dynamic, autonomous driving, illumination, outdoor, mapping, 3d gaussian, gaussian splatting, lighting, ar, sparse view, fast, high-fidelity  
- **[Real2Sim: A Physics-driven and Editable Gaussian Splatting Framework for Autonomous Driving Scenes](https://arxiv.org/abs/2605.13591v1)**  
  Authors: Kaicong Huang, Talha Azfar, Weisong Shi, Ruimin Ke  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.13591v1.pdf)  
  Keywords: dynamic, autonomous driving, 4d, gaussian splatting, tracking, ar, high-fidelity  

### Scene Understanding

*Showing the latest 50 out of 226 papers*

- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, 3d reconstruction, 4d, ar, compact, 3d gaussian, neural rendering, gaussian splatting, recognition, survey, vr, motion, autonomous driving  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: efficient, semantic, segmentation, compact, 3d gaussian, gaussian splatting, ar, fast, understanding  
- **[UnsOcc: 3D Semantic Occupancy Prediction in Unstructured Scene via Rendering Fusion](https://arxiv.org/abs/2606.03581v1)**  
  Authors: Ye Wu, Ruiqi Song, Baiyong Ding, Nanxin Zeng, Junjie Cheng, Yunfeng Ai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03581v1.pdf)  
  Keywords: semantic, segmentation, gaussian splatting, ar, autonomous driving  
- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v2)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v2.pdf)  
  Keywords: geometry, 3d reconstruction, gaussian splatting, ar, understanding  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: reflection, efficient, ray tracing, semantic, segmentation, geometry, 3d gaussian, gaussian splatting, ar  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: dynamic, deformation, head, 4d, nerf, compact, 3d gaussian, gaussian splatting, ar, understanding  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: face, geometry, nerf, ar, 3d gaussian, gaussian splatting, motion, understanding  
- **[GeoSAM-3D: Geodesic Prompt Propagation for Open-Vocabulary 3D Scene Segmentation from Monocular Video](https://arxiv.org/abs/2606.00447v1)**  
  Authors: Arun Sharma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00447v1.pdf)  
  Keywords: face, head, segmentation, 3d gaussian, gaussian splatting, ar  
- **[LiftNav: Path Planning via Semantic Lifting in TSDF-Guided Gaussian Splatting](https://arxiv.org/abs/2605.31376v1)**  
  Authors: Hannah Schieber, Dominik Frischmann, Victor Schaack, Angela P. Schoellig, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31376v1.pdf)  
  Keywords: semantic, geometry, gaussian splatting, ar, understanding  
- **[PhyGenHOI: Physically-Aware 4D Generation of Dynamic Human-Object Interactions](https://arxiv.org/abs/2605.30268v1)**  
  Authors: Omer Benishu, Gal Fiebelman, Sagie Benaim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30268v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omerbenishu.github.io/PhyGenHOI/)  
  Keywords: dynamic, semantic, human, 4d, ar, 3d gaussian, motion  



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