# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-09-07 01:53:23

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
- [Acceleration](#acceleration) (212 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (316 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (375 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (419 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (420 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (230 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (128 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (157 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (223 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, geometry, motion, ar, survey, illumination, gaussian splatting  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: 3d reconstruction, nerf, geometry, dynamic, 3d gaussian, ar, survey, gaussian splatting  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 3d reconstruction, neural rendering, recognition, compact, 3d gaussian, motion, ar, vr, survey, autonomous driving, 4d, medical, gaussian splatting  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, mapping, animation, ar, survey, gaussian splatting  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d reconstruction, efficient, geometry, tracking, slam, 3d gaussian, motion, ar, survey, gaussian splatting  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, ar, vr, survey, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ray tracing, mapping, 3d gaussian, ar, survey, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: efficient, mapping, tracking, slam, dynamic, localization, motion, 3d gaussian, ar, survey, face, gaussian splatting  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, survey, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: nerf, efficient, geometry, 3d gaussian, ar, survey, gaussian splatting  

### Acceleration

*Showing the latest 50 out of 212 papers*

- **[GradRig: Differentiable Weights for Skinned Gaussian Splat Deformation](https://arxiv.org/abs/2609.05127v1)**  
  Authors: Nina Vesseron, Élie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05127v1.pdf)  
  Keywords: real-time rendering, dynamic, 3d gaussian, ar, deformation  
- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: fast, geometry, 3d gaussian, ar, gaussian splatting  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: fast, efficient, 3d gaussian, head, ar, acceleration, gaussian splatting  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: real-time rendering, efficient, dynamic, compression, compact, ar, 4d, deformation, gaussian splatting  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: real-time rendering, dynamic, high-fidelity, 3d gaussian, ar, illumination, gaussian splatting  
- **[Fast and Compact 3D Gaussian Splatting with Polarized Opacity Prior](https://arxiv.org/abs/2608.22344v1)**  
  Authors: Zi-Ming Wang, Kai-Wen Duan, Kowei Huang, Akihiro Sugimoto, Shang-Hong Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22344v1.pdf)  
  Keywords: fast, efficient, compact, 3d gaussian, ar, gaussian splatting  
- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: fast, nerf, real-time rendering, ray tracing, compact, 3d gaussian, motion, ar, face, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: fast, nerf, ray tracing, efficient, mapping, reflection, compact, 3d gaussian, ar, shadow, gaussian splatting  
- **[RoofGS: Roofline-Guided End-to-End Acceleration of 3D Gaussian Splatting](https://arxiv.org/abs/2608.15785v1)**  
  Authors: Yang Luo, Yan Gong, Yongsheng Gao, Jie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.15785v1.pdf)  
  Keywords: fast, compact, 3d gaussian, ar, acceleration, gaussian splatting  
- **[GaussMemory: Task-Driven 3D Gaussian Scene Memory for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2608.14986v1)**  
  Authors: Zhiqiang Hu, Shouren Huang, Masatoshi Ishikawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14986v1.pdf)  
  Keywords: fast, 3d gaussian, ar, gaussian splatting  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Compact Neural Appearance Models for Efficient Gaussian Splatting](https://arxiv.org/abs/2609.05255v1)**  
  Authors: Florian Hahlbohm, Jorge Condor, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05255v1.pdf)  
  Keywords: efficient, geometry, compact, 3d gaussian, ar, gaussian splatting  
- **[GradRig: Differentiable Weights for Skinned Gaussian Splat Deformation](https://arxiv.org/abs/2609.05127v1)**  
  Authors: Nina Vesseron, Élie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05127v1.pdf)  
  Keywords: real-time rendering, dynamic, 3d gaussian, ar, deformation  
- **[NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions](https://arxiv.org/abs/2609.04602v1)**  
  Authors: Junhui Wang, Wei Yang, Xinyao Li, Ningjing Fan, Yuehao Yin, Xuecheng Chen, Chao Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04602v1.pdf)  
  Keywords: semantic, 3d gaussian, ar, gaussian splatting  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: robotics, geometry, recognition, 3d gaussian, ar, lighting, gaussian splatting  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: efficient, compact, 3d gaussian, ar, lighting, gaussian splatting  
- **[Reparametrizing 3D Gaussian Splatting for Real-Time Palette-based Color and Luminance Editing](https://arxiv.org/abs/2609.03897v1)**  
  Authors: Cheng-Kang Ted Chao, Yotam Gingold  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03897v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting  
- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: nerf, robotics, lightweight, sparse-view, 3d gaussian, ar, gaussian splatting  
- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: fast, geometry, 3d gaussian, ar, gaussian splatting  
- **[TruncGradGS: Improved 3D Gaussian Splatting via Truncated Gradient Updates](https://arxiv.org/abs/2609.03534v1)**  
  Authors: Theo Morales, Nhat-Quynh Le-Pham, Robin Atkins, Binh-Son Hua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03534v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, face, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 316 papers*

- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, face, gaussian splatting  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: fast, efficient, 3d gaussian, head, ar, acceleration, gaussian splatting  
- **[Atlas: Algorithm-Hardware Co-Design for On-Device City-Scale 3D Gaussian Splatting in VR](https://arxiv.org/abs/2609.02352v1)**  
  Authors: He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Zihan Liu, Ruyang Li, Hui Wei, Yaqian Zhao, Jingwen Leng, Minyi Guo, Yu Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02352v1.pdf)  
  Keywords: dynamic, head, 3d gaussian, ar, vr, gaussian splatting  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: efficient, geometry, 3d gaussian, ar, face, gaussian splatting  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: compression, semantic, head, 3d gaussian, ar, segmentation, understanding, gaussian splatting  
- **[When 3D Gaussian Splatting Recovers Real Surfaces](https://arxiv.org/abs/2608.30054v1)**  
  Authors: Songhe Wang, David Johnathan Miller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30054v1.pdf)  
  Keywords: geometry, 3d gaussian, ar, face, gaussian splatting  
- **[GhostSplat: Input-Triggered Backdoors for Multi-View-Consistent 3D Content Manipulation in Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.29184v1)**  
  Authors: Yudong Gao, Zongjian Ding, Linghan Chen, Yajing Chen, Yu Xinglin, Jiale Liu, Shan Huang, Mingjun Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29184v1.pdf)  
  Keywords: face, 3d gaussian, ar, gaussian splatting  
- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: efficient, dynamic, ar, face, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: efficient, semantic, sparse-view, compact, 3d gaussian, ar, face, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, nerf, mapping, high-fidelity, human, 3d gaussian, ar, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 375 papers*

- **[GradRig: Differentiable Weights for Skinned Gaussian Splat Deformation](https://arxiv.org/abs/2609.05127v1)**  
  Authors: Nina Vesseron, Élie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05127v1.pdf)  
  Keywords: real-time rendering, dynamic, 3d gaussian, ar, deformation  
- **[TruncGradGS: Improved 3D Gaussian Splatting via Truncated Gradient Updates](https://arxiv.org/abs/2609.03534v1)**  
  Authors: Theo Morales, Nhat-Quynh Le-Pham, Robin Atkins, Binh-Son Hua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03534v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, deformation, gaussian splatting  
- **[Atlas: Algorithm-Hardware Co-Design for On-Device City-Scale 3D Gaussian Splatting in VR](https://arxiv.org/abs/2609.02352v1)**  
  Authors: He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Zihan Liu, Ruyang Li, Hui Wei, Yaqian Zhao, Jingwen Leng, Minyi Guo, Yu Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02352v1.pdf)  
  Keywords: dynamic, head, 3d gaussian, ar, vr, gaussian splatting  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: real-time rendering, efficient, dynamic, compression, compact, ar, 4d, deformation, gaussian splatting  
- **[VirSqueezer: Generating Realistic Deformations and Squeezing Dynamics in VR from Fine-Grained Squeezing Controls](https://arxiv.org/abs/2609.01698v1)**  
  Authors: Qian Zhang, Xiaoming Chen, Xiaorui Ma, Haisheng Li, Weidong Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.01698v1.pdf)  
  Keywords: dynamic, 3d gaussian, ar, vr, deformation, gaussian splatting  
- **[EvoGS: Modeling Deformation Evolution for Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.00994v1)**  
  Authors: Wei Dong, Shahram Shirani, Jun Chen, Han Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.00994v1.pdf)  
  Keywords: dynamic, motion, 3d gaussian, ar, deformation, gaussian splatting  
- **[SMG: Semantic Motion Graph for Monocular Dynamic Gaussian Splatting](https://arxiv.org/abs/2608.31023v1)**  
  Authors: Haozheng Yu, Xinyu Yang, Rundong Luo, Jennifer J. Sun, Bharath Hariharan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31023v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smg-gaussian.github.io/.)  
  Keywords: dynamic, semantic, motion, ar, gaussian splatting  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: dynamic, compact, motion, ar, tracking, gaussian splatting  
- **[As-Rigid-As-Possible Deformation of Gaussian Radiance Fields](https://arxiv.org/abs/2608.29538v1)**  
  Authors: Xinhao Tong, Tianjia Shao, Yanlin Weng, Yin Yang, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29538v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, deformation, gaussian splatting  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: nerf, robotics, lightweight, sparse-view, 3d gaussian, ar, gaussian splatting  
- **[GSPotential: Camera Potential Field for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2608.29346v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Yijun Feng, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29346v1.pdf)  
  Keywords: sparse-view, 3d gaussian, ar, gaussian splatting  
- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: efficient, sparse-view, compact, ar, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: efficient, semantic, sparse-view, compact, 3d gaussian, ar, face, gaussian splatting  
- **[GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors](https://arxiv.org/abs/2608.21849v1)**  
  Authors: Xinhui Liu, Can Wang, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21849v1.pdf)  
  Keywords: geometry, sparse-view, 3d gaussian, ar, sparse view, gaussian splatting  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: 3d reconstruction, geometry, light transport, compact, ar, sparse view, face, illumination, gaussian splatting  
- **[TR-GS: High-Fidelity Sparse-View CT Volumetric Rendering via t-Distribution Gaussian Splatting and Ray-Confidence Modeling](https://arxiv.org/abs/2608.16042v1)**  
  Authors: Zedong Xiao, Yiren Wang, Zhou Liu, Xiaolin Liu, Zhangji Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16042v1.pdf)  
  Keywords: efficient, high-fidelity, sparse-view, 3d gaussian, ar, sparse view, medical, gaussian splatting  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: semantic, localization, 3d gaussian, ar, face, few-shot, gaussian splatting  
- **[TRACE-GS: On-Policy Trajectory Distillation with Privileged Geometric Conditioning for Sparse-View 3DGS Restoration](https://arxiv.org/abs/2608.10286v1)**  
  Authors: Linlian Jiang, Yuchen Xi, Sadman Rakib Pinon, Ruigang Yang, Yang Wang, Xinxin Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10286v1.pdf)  
  Keywords: geometry, sparse-view, 3d gaussian, ar, gaussian splatting  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: 3d reconstruction, geometry, compact, 3d gaussian, localization, ar, few-shot, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 419 papers*

- **[Compact Neural Appearance Models for Efficient Gaussian Splatting](https://arxiv.org/abs/2609.05255v1)**  
  Authors: Florian Hahlbohm, Jorge Condor, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05255v1.pdf)  
  Keywords: efficient, geometry, compact, 3d gaussian, ar, gaussian splatting  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: robotics, geometry, recognition, 3d gaussian, ar, lighting, gaussian splatting  
- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: fast, geometry, 3d gaussian, ar, gaussian splatting  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, face, gaussian splatting  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, deformation, gaussian splatting  
- **[AnyGS2Mesh: Feed-Forward Mesh Reconstruction from 3D Gaussian Splatting with Arbitrary-Resolution Views](https://arxiv.org/abs/2609.03304v1)**  
  Authors: Yuxuan Song, Fan Gao, Yibo Zhao, Jiarui Wen, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03304v1.pdf)  
  Keywords: efficient, geometry, 3d gaussian, ar, gaussian splatting  
- **[DualDiff3D: Dual Structure-Appearance Diffusion Priors for Reliability-Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2609.01516v1)**  
  Authors: Qian Wang, Yu Wang, Weiqi Li, Xinhua Cheng, Xiandong Meng, Ronggang Wang, Jian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.01516v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, ar, gaussian splatting  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: efficient, geometry, 3d gaussian, ar, face, gaussian splatting  
- **[When 3D Gaussian Splatting Recovers Real Surfaces](https://arxiv.org/abs/2608.30054v1)**  
  Authors: Songhe Wang, David Johnathan Miller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30054v1.pdf)  
  Keywords: geometry, 3d gaussian, ar, face, gaussian splatting  
- **[Elastic Triangle Splatting](https://arxiv.org/abs/2608.29106v1)**  
  Authors: Tian Shi, Shenhan Qian, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29106v1.pdf)  
  Keywords: neural rendering, shape reconstruction, 3d gaussian, ar, gaussian splatting  

### Large Scene

- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: geometry, dynamic, high-fidelity, outdoor, compression, semantic, motion, ar, 4d, segmentation, gaussian splatting  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: efficient, geometry, outdoor, compact, 3d gaussian, motion, ar, face, gaussian splatting  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: fast, geometry, outdoor, localization, 3d gaussian, ar, gaussian splatting  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: efficient, outdoor, semantic, localization, 3d gaussian, ar, segmentation, understanding, gaussian splatting  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: geometry, mapping, slam, outdoor, lightweight, localization, 3d gaussian, ar, tracking, gaussian splatting  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: dynamic, outdoor, animation, motion, 3d gaussian, ar, deformation, gaussian splatting  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: fast, real-time rendering, large scene, efficient, recognition, slam, 3d gaussian, motion, ar, gaussian splatting  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: geometry, mapping, slam, outdoor, 3d gaussian, ar, tracking, gaussian splatting  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: geometry, outdoor, 3d gaussian, ar, gaussian splatting  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: efficient, large scene, geometry, 3d gaussian, ar, sparse view, face, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 420 papers*

- **[Compact Neural Appearance Models for Efficient Gaussian Splatting](https://arxiv.org/abs/2609.05255v1)**  
  Authors: Florian Hahlbohm, Jorge Condor, Linus Franke, Martin Eisemann, Marcus Magnor  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05255v1.pdf)  
  Keywords: efficient, geometry, compact, 3d gaussian, ar, gaussian splatting  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: efficient, compact, 3d gaussian, ar, lighting, gaussian splatting  
- **[Reparametrizing 3D Gaussian Splatting for Real-Time Palette-based Color and Luminance Editing](https://arxiv.org/abs/2609.03897v1)**  
  Authors: Cheng-Kang Ted Chao, Yotam Gingold  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03897v1.pdf)  
  Keywords: efficient, 3d gaussian, ar, gaussian splatting  
- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: nerf, robotics, lightweight, sparse-view, 3d gaussian, ar, gaussian splatting  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: fast, efficient, 3d gaussian, head, ar, acceleration, gaussian splatting  
- **[AnyGS2Mesh: Feed-Forward Mesh Reconstruction from 3D Gaussian Splatting with Arbitrary-Resolution Views](https://arxiv.org/abs/2609.03304v1)**  
  Authors: Yuxuan Song, Fan Gao, Yibo Zhao, Jiarui Wen, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03304v1.pdf)  
  Keywords: efficient, geometry, 3d gaussian, ar, gaussian splatting  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: efficient, 3d gaussian, relighting, ar, lighting, illumination, gaussian splatting  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: real-time rendering, efficient, dynamic, compression, compact, ar, 4d, deformation, gaussian splatting  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: efficient, geometry, 3d gaussian, ar, face, gaussian splatting  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: compression, semantic, head, 3d gaussian, ar, segmentation, understanding, gaussian splatting  

### Quality Enhancement

*Showing the latest 50 out of 230 papers*

- **[InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling](https://arxiv.org/abs/2609.02747v1)**  
  Authors: Tianheng Lu, Guangyu Wang, Ruqi Huang, Lu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02747v1.pdf)  
  Keywords: ar, high-fidelity, gaussian splatting  
- **[As-Rigid-As-Possible Deformation of Gaussian Radiance Fields](https://arxiv.org/abs/2608.29538v1)**  
  Authors: Xinhao Tong, Tianjia Shao, Yanlin Weng, Yin Yang, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29538v1.pdf)  
  Keywords: high quality, 3d gaussian, ar, deformation, gaussian splatting  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: geometry, dynamic, high-fidelity, compact, ar, lighting, gaussian splatting  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: real-time rendering, dynamic, high-fidelity, 3d gaussian, ar, illumination, gaussian splatting  
- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: 3d reconstruction, nerf, high-fidelity, ar, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: efficient, geometry, mapping, slam, high-fidelity, localization, 3d gaussian, ar, tracking, gaussian splatting  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, high-fidelity, semantic, 3d gaussian, motion, ar, tracking, 4d, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: geometry, dynamic, high-fidelity, outdoor, compression, semantic, motion, ar, 4d, segmentation, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, nerf, mapping, high-fidelity, human, 3d gaussian, ar, gaussian splatting  
- **[TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction](https://arxiv.org/abs/2608.20687v2)**  
  Authors: Chuanjin Fan, Wenjie Chang, Bohao Liao, Yujia Chen, Wenfei Yang, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20687v2.pdf)  
  Keywords: geometry, dynamic, high-fidelity, 3d gaussian, ar, face, gaussian splatting  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: fast, nerf, real-time rendering, ray tracing, compact, 3d gaussian, motion, ar, face, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: fast, nerf, ray tracing, efficient, mapping, reflection, compact, 3d gaussian, ar, shadow, gaussian splatting  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: ray tracing, efficient, reflection, relighting, ar, lighting, face, illumination, gaussian splatting  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: ray tracing, geometry, reflection, dynamic, high-fidelity, human, 3d gaussian, motion, ar, face, gaussian splatting  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: fast, ray tracing, 3d gaussian, ar, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: fast, ray tracing, real-time rendering, efficient, geometry, reflection, path tracing, 3d gaussian, ar, gaussian splatting  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d reconstruction, efficient, global illumination, geometry, 3d gaussian, ar, illumination, gaussian splatting  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: global illumination, high-fidelity, ar, illumination, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: ray tracing, efficient, geometry, reflection, semantic, 3d gaussian, ar, segmentation, gaussian splatting  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: fast, global illumination, face, 3d gaussian, ar, shadow, illumination, gaussian splatting  

### Relighting

*Showing the latest 50 out of 128 papers*

- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: robotics, geometry, recognition, 3d gaussian, ar, lighting, gaussian splatting  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: efficient, compact, 3d gaussian, ar, lighting, gaussian splatting  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: efficient, 3d gaussian, relighting, ar, lighting, illumination, gaussian splatting  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: geometry, dynamic, high-fidelity, compact, ar, lighting, gaussian splatting  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: real-time rendering, dynamic, high-fidelity, 3d gaussian, ar, illumination, gaussian splatting  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, geometry, motion, ar, survey, illumination, gaussian splatting  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: 3d reconstruction, geometry, light transport, compact, ar, sparse view, face, illumination, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: fast, nerf, ray tracing, efficient, mapping, reflection, compact, 3d gaussian, ar, shadow, gaussian splatting  
- **[Geometry-Aware Online Mapping for 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2608.14902v1)**  
  Authors: Thai Luu, Quan Tran, Hieu Phan, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14902v1.pdf)  
  Keywords: efficient, geometry, mapping, slam, localization, 3d gaussian, head, ar, tracking, lighting, gaussian splatting  
- **[SpotlessGS: Relightable 3D Gaussian Splatting under Dynamic Illumination for Robotic Perception](https://arxiv.org/abs/2608.14713v1)**  
  Authors: Liang Hong, Jiaxin Wei, Simon Schaefer, Stefan Leutenegger, Jaehyung Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14713v1.pdf)  
  Keywords: 3d reconstruction, dynamic, 3d gaussian, ar, relightable, lighting, illumination, gaussian splatting  

### SLAM

*Showing the latest 50 out of 157 papers*

- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, face, gaussian splatting  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: geometry, mapping, 3d gaussian, ar, deformation, gaussian splatting  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: dynamic, compact, motion, ar, tracking, gaussian splatting  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: geometry, mapping, slam, dynamic, semantic, motion, ar, tracking, understanding, gaussian splatting  
- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: 3d reconstruction, nerf, geometry, lightweight, 3d gaussian, ar, tracking, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: efficient, geometry, mapping, slam, high-fidelity, localization, 3d gaussian, ar, tracking, gaussian splatting  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, high-fidelity, semantic, 3d gaussian, motion, ar, tracking, 4d, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, nerf, mapping, high-fidelity, human, 3d gaussian, ar, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: fast, nerf, ray tracing, efficient, mapping, reflection, compact, 3d gaussian, ar, shadow, gaussian splatting  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: nerf, high-fidelity, semantic, localization, 3d gaussian, ar, tracking, face, gaussian splatting  

### Scene Understanding

*Showing the latest 50 out of 223 papers*

- **[NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions](https://arxiv.org/abs/2609.04602v1)**  
  Authors: Junhui Wang, Wei Yang, Xinyao Li, Ningjing Fan, Yuehao Yin, Xuecheng Chen, Chao Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04602v1.pdf)  
  Keywords: semantic, 3d gaussian, ar, gaussian splatting  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: robotics, geometry, recognition, 3d gaussian, ar, lighting, gaussian splatting  
- **[SMG: Semantic Motion Graph for Monocular Dynamic Gaussian Splatting](https://arxiv.org/abs/2608.31023v1)**  
  Authors: Haozheng Yu, Xinyu Yang, Rundong Luo, Jennifer J. Sun, Bharath Hariharan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31023v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smg-gaussian.github.io/.)  
  Keywords: dynamic, semantic, motion, ar, gaussian splatting  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: compression, semantic, head, 3d gaussian, ar, segmentation, understanding, gaussian splatting  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: geometry, mapping, slam, dynamic, semantic, motion, ar, tracking, understanding, gaussian splatting  
- **[CoGeo-GS: Concept-Driven and Geometry-Aware Multi-Object Removal in 3D Scenes](https://arxiv.org/abs/2608.26656v1)**  
  Authors: Yuanxiang Ni, Xianliang Huang, Chenhang Ma, Chen Xiao, Yuewen Ma, Ruxin Wang, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26656v1.pdf)  
  Keywords: geometry, semantic, 3d gaussian, ar, gaussian splatting  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, high-fidelity, semantic, 3d gaussian, motion, ar, tracking, 4d, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: efficient, semantic, sparse-view, compact, 3d gaussian, ar, face, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: geometry, dynamic, high-fidelity, outdoor, compression, semantic, motion, ar, 4d, segmentation, gaussian splatting  
- **[GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.17535v1)**  
  Authors: Qijian Tian, Zimeng Wu, Xuhong Wang, Lizhuang Ma, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17535v1.pdf)  
  Keywords: efficient, geometry, semantic, compact, 3d gaussian, ar, segmentation, understanding, gaussian splatting  



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