# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-08-29 04:48:00

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
- [Acceleration](#acceleration) (218 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (994 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (321 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (378 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (78 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (421 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (44 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (425 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (232 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (30 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (130 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (161 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (227 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: 3d reconstruction, illumination, geometry, motion, ar, gaussian splatting, survey  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: 3d reconstruction, dynamic, 3d gaussian, nerf, geometry, ar, gaussian splatting, survey  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 3d reconstruction, 4d, compact, 3d gaussian, recognition, autonomous driving, motion, ar, gaussian splatting, medical, vr, neural rendering, survey  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: animation, geometry, ar, gaussian splatting, mapping, survey  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, slam, geometry, efficient, motion, ar, tracking, gaussian splatting, survey  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, ar, vr, gaussian splatting, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: 3d gaussian, ray tracing, ar, gaussian splatting, mapping, survey  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: dynamic, localization, 3d gaussian, face, slam, efficient, motion, ar, tracking, gaussian splatting, mapping, survey  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: 3d gaussian, robotics, ar, gaussian splatting, survey  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: 3d gaussian, nerf, geometry, efficient, ar, gaussian splatting, survey  

### Acceleration

*Showing the latest 50 out of 218 papers*

- **[Fast and Compact 3D Gaussian Splatting with Polarized Opacity Prior](https://arxiv.org/abs/2608.22344v1)**  
  Authors: Zi-Ming Wang, Kai-Wen Duan, Kowei Huang, Akihiro Sugimoto, Shang-Hong Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22344v1.pdf)  
  Keywords: compact, 3d gaussian, fast, efficient, ar, gaussian splatting  
- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: compact, 3d gaussian, ray tracing, face, nerf, real-time rendering, fast, motion, ar, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: compact, 3d gaussian, ray tracing, nerf, reflection, fast, efficient, ar, gaussian splatting, mapping, shadow  
- **[RoofGS: Roofline-Guided End-to-End Acceleration of 3D Gaussian Splatting](https://arxiv.org/abs/2608.15785v1)**  
  Authors: Yang Luo, Yan Gong, Yongsheng Gao, Jie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.15785v1.pdf)  
  Keywords: compact, 3d gaussian, fast, ar, gaussian splatting, acceleration  
- **[GaussMemory: Task-Driven 3D Gaussian Scene Memory for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2608.14986v1)**  
  Authors: Zhiqiang Hu, Shouren Huang, Masatoshi Ishikawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14986v1.pdf)  
  Keywords: gaussian splatting, ar, fast, 3d gaussian  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: localization, 3d gaussian, fast, geometry, ar, gaussian splatting, outdoor  
- **[Compact Feed-Forward 3D Gaussians via Saliency-Guided Primitive Merging](https://arxiv.org/abs/2608.10712v2)**  
  Authors: Tim-Felix Fassch, Jochen Kall, Cyrill Stachniss  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10712v2.pdf)  
  Keywords: compact, 3d gaussian, segmentation, fast, efficient, ar, gaussian splatting  
- **[ERF-GS: Reconstructing Fast Motion from Disjoint Event-RGB Viewpoints](https://arxiv.org/abs/2608.08531v1)**  
  Authors: Xiaoyang Bai, Zhenyang Li, Weiwei Xu, Edmund Y. Lam, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.08531v1.pdf)  
  Keywords: dynamic, 4d, 3d gaussian, nerf, fast, motion, ar, gaussian splatting  
- **[Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction](https://arxiv.org/abs/2608.06117v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06117v1.pdf)  
  Keywords: 3d gaussian, real-time rendering, geometry, motion, ar, gaussian splatting  
- **[ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling](https://arxiv.org/abs/2608.05564v1)**  
  Authors: Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05564v1.pdf)  
  Keywords: compact, 3d gaussian, high-fidelity, real-time rendering, fast, compression, efficient, ar, gaussian splatting, mapping, vr  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: 3d reconstruction, high-fidelity, nerf, ar, gaussian splatting  
- **[Per-View Gaussian Predictions Enable Training-Free Distractor Filtering in Feed-Forward 3DGS](https://arxiv.org/abs/2608.26951v1)**  
  Authors: Kangmin Seo, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26951v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, ar, 3d gaussian  
- **[KISS-GS: 3D Gaussian Splatting Compression Kept Simple](https://arxiv.org/abs/2608.26948v1)**  
  Authors: Wieland Morgenstern, Friedrich Elias Branschke, Florian Fleischmann, Adrian Szatmari, Paul Schlack, Florian Barthel, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26948v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fraunhoferhhi.github.io/KISS-GS/)  
  Keywords: compact, 3d gaussian, compression, ar, gaussian splatting  
- **[CoGeo-GS: Concept-Driven and Geometry-Aware Multi-Object Removal in 3D Scenes](https://arxiv.org/abs/2608.26656v1)**  
  Authors: Yuanxiang Ni, Xianliang Huang, Chenhang Ma, Chen Xiao, Yuewen Ma, Ruxin Wang, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26656v1.pdf)  
  Keywords: 3d gaussian, semantic, geometry, ar, gaussian splatting  
- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, geometry, ar, lightweight, tracking, gaussian splatting  
- **[4DGS-WAM: Bridging Past and Future with an Object-Centric World Action Model based on 4D Gaussian Splatting](https://arxiv.org/abs/2608.25956v1)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25956v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, 4d  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, illumination, geometry, motion, ar, gaussian splatting, survey  
- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: compact, sparse-view, efficient, ar, gaussian splatting  
- **[PIVOT: A Multi-Trajectory Dataset and Testbed for Pose, Intrinsics, and Novel Viewpoint Evaluation in Real-World 3D Reconstruction](https://arxiv.org/abs/2608.25401v1)**  
  Authors: Mary Raymond  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25401v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, ar, gaussian splatting  
- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: dynamic, face, efficient, ar, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 321 papers*

- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: dynamic, face, efficient, ar, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: compact, 3d gaussian, sparse-view, semantic, face, efficient, ar, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, high-fidelity, nerf, human, ar, gaussian splatting, mapping  
- **[TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction](https://arxiv.org/abs/2608.20687v1)**  
  Authors: Chuanjin Fan, Wenjie Chang, Bohao Liao, Yujia Chen, Wenfei Yang, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20687v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, face, geometry, ar, gaussian splatting  
- **[4DAnyone: Create Anyone in 4D from a Casual Monocular Video](https://arxiv.org/abs/2608.20335v1)**  
  Authors: Yudong Jin, Tao Xie, Qihang Zhang, Zehong Shen, Zhen Xu, Yujun Shen, Hujun Bao, Xiaowei Zhou, Yinghao Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://4danyone.github.io.)  
  Keywords: gaussian splatting, 4d, human, ar  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: sparse view, 3d reconstruction, compact, face, illumination, geometry, ar, gaussian splatting, light transport  
- **[Stream4D: 4D-Consistency for Streaming Autoregressive Diffusion Video Models](https://arxiv.org/abs/2608.19556v1)**  
  Authors: Yuanhao Ban, Jiaqi Feng, Hengguang Zhou, Xiaohuan Pei, Justin Cui, Cho-Jui Hsieh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.19556v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://banyuanhao.github.io/Stream4D/)  
  Keywords: 3d reconstruction, dynamic, 4d, 3d gaussian, geometry, human, motion, lightweight, ar  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: compact, 3d gaussian, face, geometry, efficient, motion, ar, gaussian splatting, outdoor  
- **[Depth Anything V4: Dynamic 4D Scene Reconstruction via Riemannian Flow Matching on 4D Gaussian Splatting](https://arxiv.org/abs/2608.18388v2)**  
  Authors: Jiaming Fan, Jian Lu, Jinling Jia, Chenbin Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18388v2.pdf)  
  Keywords: dynamic, 4d, human, ar, gaussian splatting  
- **[QuARC-GS: Quantized Anchored Residual Coding for Compact Dynamic Scene Streaming with Gaussian Splatting](https://arxiv.org/abs/2608.18285v1)**  
  Authors: Vu Trung Nghia Nguyen, Yuchen Wang, Kyung Chul Lee, Kevin C. Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18285v1.pdf)  
  Keywords: dynamic, 4d, compact, head, deformation, nerf, compression, motion, ar, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 378 papers*

- **[4DGS-WAM: Bridging Past and Future with an Object-Centric World Action Model based on 4D Gaussian Splatting](https://arxiv.org/abs/2608.25956v1)**  
  Authors: Yueen Ma, Zenglin Xu, Irwin King  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25956v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, 4d  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, illumination, geometry, motion, ar, gaussian splatting, survey  
- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: dynamic, face, efficient, ar, gaussian splatting  
- **[FixAnything: 3D-Consistent Rendering Refinement via Video Generative Priors](https://arxiv.org/abs/2608.23549v1)**  
  Authors: Khiem Vuong, Deva Ramanan, Srinivasa Narasimhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.23549v1.pdf)  
  Keywords: lightweight, nerf, motion, ar, gaussian splatting  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, 4d, 3d gaussian, high-fidelity, semantic, motion, ar, tracking, gaussian splatting  
- **[LagrangeGS: Non-Conservative Lagrangian System on Dynamic 3D Gaussian Splatting](https://arxiv.org/abs/2608.22773v1)**  
  Authors: Shogo Sato, Takuhiro Kaneko, Shoichiro Takeda, Tomoyasu Shimada, Riku Inoue, Kazuhiko Murasaki, Ryuichi Tanida  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22773v1.pdf)  
  Keywords: dynamic, 3d gaussian, deformation, ar, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[Towards Alias-Free 4D Gaussian Representations with Motion-Aware Filtering](https://arxiv.org/abs/2608.21828v1)**  
  Authors: Ankit Dhiman, Kunal A Kathare, Pranav Vignesh, Lokesh R Boregowda, Venkatesh Babu Radhakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21828v1.pdf)  
  Keywords: dynamic, 4d, 3d gaussian, nerf, motion, ar, gaussian splatting, vr  
- **[TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction](https://arxiv.org/abs/2608.20687v1)**  
  Authors: Chuanjin Fan, Wenjie Chang, Bohao Liao, Yujia Chen, Wenfei Yang, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20687v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, face, geometry, ar, gaussian splatting  
- **[4DAnyone: Create Anyone in 4D from a Casual Monocular Video](https://arxiv.org/abs/2608.20335v1)**  
  Authors: Yudong Jin, Tao Xie, Qihang Zhang, Zehong Shen, Zhen Xu, Yujun Shen, Hujun Bao, Xiaowei Zhou, Yinghao Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://4danyone.github.io.)  
  Keywords: gaussian splatting, 4d, human, ar  

### Few-shot

*Showing the latest 50 out of 78 papers*

- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: compact, sparse-view, efficient, ar, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: compact, 3d gaussian, sparse-view, semantic, face, efficient, ar, gaussian splatting  
- **[GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors](https://arxiv.org/abs/2608.21849v1)**  
  Authors: Xinhui Liu, Can Wang, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21849v1.pdf)  
  Keywords: sparse view, 3d gaussian, sparse-view, geometry, ar, gaussian splatting  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: sparse view, 3d reconstruction, compact, face, illumination, geometry, ar, gaussian splatting, light transport  
- **[TR-GS: High-Fidelity Sparse-View CT Volumetric Rendering via t-Distribution Gaussian Splatting and Ray-Confidence Modeling](https://arxiv.org/abs/2608.16042v1)**  
  Authors: Zedong Xiao, Yiren Wang, Zhou Liu, Xiaolin Liu, Zhangji Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16042v1.pdf)  
  Keywords: sparse view, 3d gaussian, high-fidelity, sparse-view, efficient, ar, gaussian splatting, medical  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: localization, few-shot, 3d gaussian, semantic, face, ar, gaussian splatting  
- **[TRACE-GS: On-Policy Trajectory Distillation with Privileged Geometric Conditioning for Sparse-View 3DGS Restoration](https://arxiv.org/abs/2608.10286v1)**  
  Authors: Linlian Jiang, Yuchen Xi, Sadman Rakib Pinon, Ruigang Yang, Yang Wang, Xinxin Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10286v1.pdf)  
  Keywords: 3d gaussian, sparse-view, geometry, ar, gaussian splatting  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: 3d reconstruction, localization, few-shot, compact, 3d gaussian, geometry, ar, gaussian splatting  
- **[CLEAR: Conflict-aware Learning via Evidence-guided Adaptive Routing for Unified Sparse-View 3D Gaussian Super-Resolution](https://arxiv.org/abs/2608.02206v1)**  
  Authors: Hantang Li, Qiang Zhu, Xiandong Meng, Debin Zhao, Xiaopeng Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02206v1.pdf)  
  Keywords: gaussian splatting, sparse-view, ar, 3d gaussian  
- **[D^2-4DGS: Dual-Depth Guided Sparse-Camera 4D Gaussian Splatting](https://arxiv.org/abs/2608.01588v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01588v1.pdf)  
  Keywords: dynamic, 4d, sparse-view, real-time rendering, geometry, efficient, ar, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 421 papers*

- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: 3d reconstruction, high-fidelity, nerf, ar, gaussian splatting  
- **[Per-View Gaussian Predictions Enable Training-Free Distractor Filtering in Feed-Forward 3DGS](https://arxiv.org/abs/2608.26951v1)**  
  Authors: Kangmin Seo, Jae-Pil Heo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26951v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, ar, 3d gaussian  
- **[CoGeo-GS: Concept-Driven and Geometry-Aware Multi-Object Removal in 3D Scenes](https://arxiv.org/abs/2608.26656v1)**  
  Authors: Yuanxiang Ni, Xianliang Huang, Chenhang Ma, Chen Xiao, Yuewen Ma, Ruxin Wang, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26656v1.pdf)  
  Keywords: 3d gaussian, semantic, geometry, ar, gaussian splatting  
- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, geometry, ar, lightweight, tracking, gaussian splatting  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, illumination, geometry, motion, ar, gaussian splatting, survey  
- **[PIVOT: A Multi-Trajectory Dataset and Testbed for Pose, Intrinsics, and Novel Viewpoint Evaluation in Real-World 3D Reconstruction](https://arxiv.org/abs/2608.25401v1)**  
  Authors: Mary Raymond  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25401v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, ar, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors](https://arxiv.org/abs/2608.21849v1)**  
  Authors: Xinhui Liu, Can Wang, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21849v1.pdf)  
  Keywords: sparse view, 3d gaussian, sparse-view, geometry, ar, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, high-fidelity, nerf, human, ar, gaussian splatting, mapping  

### Large Scene

- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: compact, 3d gaussian, face, geometry, efficient, motion, ar, gaussian splatting, outdoor  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: localization, 3d gaussian, fast, geometry, ar, gaussian splatting, outdoor  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: localization, 3d gaussian, semantic, segmentation, efficient, ar, gaussian splatting, outdoor, understanding  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: localization, 3d gaussian, slam, geometry, ar, lightweight, tracking, gaussian splatting, mapping, outdoor  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: dynamic, animation, 3d gaussian, deformation, motion, ar, gaussian splatting, outdoor  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: 3d gaussian, recognition, slam, real-time rendering, fast, large scene, motion, efficient, ar, gaussian splatting  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: 3d gaussian, slam, geometry, ar, tracking, gaussian splatting, mapping, outdoor  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: 3d gaussian, geometry, ar, gaussian splatting, outdoor  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: sparse view, 3d gaussian, face, geometry, large scene, efficient, ar, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 425 papers*

- **[KISS-GS: 3D Gaussian Splatting Compression Kept Simple](https://arxiv.org/abs/2608.26948v1)**  
  Authors: Wieland Morgenstern, Friedrich Elias Branschke, Florian Fleischmann, Adrian Szatmari, Paul Schlack, Florian Barthel, Peter Eisert, Anna Hilsmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26948v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fraunhoferhhi.github.io/KISS-GS/)  
  Keywords: compact, 3d gaussian, compression, ar, gaussian splatting  
- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, geometry, ar, lightweight, tracking, gaussian splatting  
- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: compact, sparse-view, efficient, ar, gaussian splatting  
- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: dynamic, face, efficient, ar, gaussian splatting  
- **[FixAnything: 3D-Consistent Rendering Refinement via Video Generative Priors](https://arxiv.org/abs/2608.23549v1)**  
  Authors: Khiem Vuong, Deva Ramanan, Srinivasa Narasimhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.23549v1.pdf)  
  Keywords: lightweight, nerf, motion, ar, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: compact, 3d gaussian, sparse-view, semantic, face, efficient, ar, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[Fast and Compact 3D Gaussian Splatting with Polarized Opacity Prior](https://arxiv.org/abs/2608.22344v1)**  
  Authors: Zi-Ming Wang, Kai-Wen Duan, Kowei Huang, Akihiro Sugimoto, Shang-Hong Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22344v1.pdf)  
  Keywords: compact, 3d gaussian, fast, efficient, ar, gaussian splatting  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: sparse view, 3d reconstruction, compact, face, illumination, geometry, ar, gaussian splatting, light transport  

### Quality Enhancement

*Showing the latest 50 out of 232 papers*

- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: 3d reconstruction, high-fidelity, nerf, ar, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, 4d, 3d gaussian, high-fidelity, semantic, motion, ar, tracking, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, high-fidelity, nerf, human, ar, gaussian splatting, mapping  
- **[TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction](https://arxiv.org/abs/2608.20687v1)**  
  Authors: Chuanjin Fan, Wenjie Chang, Bohao Liao, Yujia Chen, Wenfei Yang, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20687v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, face, geometry, ar, gaussian splatting  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, semantic, face, nerf, ar, tracking, gaussian splatting  
- **[TR-GS: High-Fidelity Sparse-View CT Volumetric Rendering via t-Distribution Gaussian Splatting and Ray-Confidence Modeling](https://arxiv.org/abs/2608.16042v1)**  
  Authors: Zedong Xiao, Yiren Wang, Zhou Liu, Xiaolin Liu, Zhangji Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16042v1.pdf)  
  Keywords: sparse view, 3d gaussian, high-fidelity, sparse-view, efficient, ar, gaussian splatting, medical  
- **[HiCo-GS: Hierarchical Context Aggregation and Geometric Consistency for Octree Gaussian Splatting](https://arxiv.org/abs/2608.14136v1)**  
  Authors: Wei Zhang, Shengkai Yu, Shiqiang Gong, Qi Zhang, Qiang Li, Qi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14136v1.pdf)  
  Keywords: high-fidelity, head, geometry, ar, lightweight, gaussian splatting  
- **[Splat-based Metal Artifact Reduction in Cone-Beam CT via Polychromatic Modeling](https://arxiv.org/abs/2608.13159v1)**  
  Authors: Kiseok Choi, Inchul Kim, Jaemin Cho, Hyeongjun Cho, Min H. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.13159v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, efficient, ar  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: compact, 3d gaussian, ray tracing, face, nerf, real-time rendering, fast, motion, ar, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: compact, 3d gaussian, ray tracing, nerf, reflection, fast, efficient, ar, gaussian splatting, mapping, shadow  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: relighting, ray tracing, lighting, face, reflection, illumination, efficient, ar, gaussian splatting  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, ray tracing, face, reflection, geometry, human, motion, ar, gaussian splatting  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: 3d gaussian, ray tracing, fast, ar, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: path tracing, 3d gaussian, ray tracing, reflection, real-time rendering, fast, geometry, efficient, ar, gaussian splatting  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, global illumination, illumination, geometry, efficient, ar, gaussian splatting  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, global illumination, illumination, ar, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: 3d gaussian, ray tracing, semantic, segmentation, reflection, geometry, efficient, ar, gaussian splatting  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, global illumination, face, illumination, fast, ar, gaussian splatting, shadow  

### Relighting

*Showing the latest 50 out of 130 papers*

- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: 3d reconstruction, illumination, geometry, motion, ar, gaussian splatting, survey  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: sparse view, 3d reconstruction, compact, face, illumination, geometry, ar, gaussian splatting, light transport  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: compact, 3d gaussian, ray tracing, nerf, reflection, fast, efficient, ar, gaussian splatting, mapping, shadow  
- **[Geometry-Aware Online Mapping for 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2608.14902v1)**  
  Authors: Thai Luu, Quan Tran, Hieu Phan, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14902v1.pdf)  
  Keywords: localization, 3d gaussian, head, lighting, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[SpotlessGS: Relightable 3D Gaussian Splatting under Dynamic Illumination for Robotic Perception](https://arxiv.org/abs/2608.14713v1)**  
  Authors: Liang Hong, Jiaxin Wei, Simon Schaefer, Stefan Leutenegger, Jaehyung Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14713v1.pdf)  
  Keywords: 3d reconstruction, dynamic, 3d gaussian, lighting, illumination, relightable, ar, gaussian splatting  
- **[AdvTiles: Physical Adversarial Camouflage Clothing against Person Detectors via Learnable Tiles](https://arxiv.org/abs/2608.06801v1)**  
  Authors: Jinlei Wang, Jiahuan Long, Mingkai Sun, Yafei Guo, Yuanhao Huang, Ming Wang, Junqi Wu, Jiacheng Hou, Hongbo Chen, Xingxing Wei, Tingsong Jiang, Wen Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06801v1.pdf)  
  Keywords: 3d gaussian, body, illumination, ar, gaussian splatting  
- **[DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)**  
  Authors: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.02191v1.pdf)  
  Keywords: 3d gaussian, nerf, illumination, geometry, autonomous driving, ar, gaussian splatting  
- **[DecoupleGS: Interactive 3D Gaussian Splatting for End-to-End Autonomous Driving Testing](https://arxiv.org/abs/2608.01761v1)**  
  Authors: Siying Li, Ying Ni, Jie Sun, Jian Sun, Haotian Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.01761v1.pdf)  
  Keywords: dynamic, 3d gaussian, relighting, high-fidelity, semantic, lighting, illumination, compression, autonomous driving, ar, gaussian splatting, neural rendering  
- **[PanoLess: Environment Reconstruction from Partial Reflective Views](https://arxiv.org/abs/2607.25362v1)**  
  Authors: Ahitagni Das, Ashok Veeraraghavan, Vivek Boominathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.25362v1.pdf)  
  Keywords: high-fidelity, face, reflection, illumination, ar  
- **[Meshless Domain Randomization via Explicit Parameter Perturbation of 3D Gaussian Splatting](https://arxiv.org/abs/2607.22890v1)**  
  Authors: Felipe Nunes Carbone de Carvalho, Joyce de Morais Souza, Alan de Aguiar, Charles Morphy D. Santos, João Paulo Gois  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22890v1.pdf)  
  Keywords: 3d gaussian, illumination, efficient, ar, gaussian splatting  

### SLAM

*Showing the latest 50 out of 161 papers*

- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, nerf, geometry, ar, lightweight, tracking, gaussian splatting  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, 4d, 3d gaussian, high-fidelity, semantic, motion, ar, tracking, gaussian splatting  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: 3d reconstruction, 3d gaussian, high-fidelity, nerf, human, ar, gaussian splatting, mapping  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: compact, 3d gaussian, ray tracing, nerf, reflection, fast, efficient, ar, gaussian splatting, mapping, shadow  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, semantic, face, nerf, ar, tracking, gaussian splatting  
- **[Geometry-Aware Online Mapping for 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2608.14902v1)**  
  Authors: Thai Luu, Quan Tran, Hieu Phan, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14902v1.pdf)  
  Keywords: localization, 3d gaussian, head, lighting, slam, geometry, efficient, ar, tracking, gaussian splatting, mapping  
- **[Seed2GS: Camera-Free, Training-Free Object Extraction from 3D Gaussian Scenes via a Single Reference-View Grounding](https://arxiv.org/abs/2608.11928v1)**  
  Authors: Zongjian Ding, Yudong Gao, Jiale Liu, Xinglin Yu, Junxing Ren, Dong Wei, Yajing Chen, Shan Huang, Mingjun Cheng, Min Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11928v1.pdf)  
  Keywords: tracking, gaussian splatting, ar, 3d gaussian  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: localization, 3d gaussian, fast, geometry, ar, gaussian splatting, outdoor  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: localization, few-shot, 3d gaussian, semantic, face, ar, gaussian splatting  

### Scene Understanding

*Showing the latest 50 out of 227 papers*

- **[CoGeo-GS: Concept-Driven and Geometry-Aware Multi-Object Removal in 3D Scenes](https://arxiv.org/abs/2608.26656v1)**  
  Authors: Yuanxiang Ni, Xianliang Huang, Chenhang Ma, Chen Xiao, Yuewen Ma, Ruxin Wang, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26656v1.pdf)  
  Keywords: 3d gaussian, semantic, geometry, ar, gaussian splatting  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, 4d, 3d gaussian, high-fidelity, semantic, motion, ar, tracking, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: compact, 3d gaussian, sparse-view, semantic, face, efficient, ar, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: dynamic, 4d, high-fidelity, semantic, segmentation, geometry, compression, motion, ar, gaussian splatting, outdoor  
- **[GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.17535v1)**  
  Authors: Qijian Tian, Zimeng Wu, Xuhong Wang, Lizhuang Ma, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17535v1.pdf)  
  Keywords: compact, 3d gaussian, semantic, segmentation, geometry, efficient, ar, gaussian splatting, understanding  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: localization, 3d gaussian, high-fidelity, semantic, face, nerf, ar, tracking, gaussian splatting  
- **[Beyond Similarity Matching: Structured Reasoning for Open-Vocabulary Referring Segmentation in 3DGS](https://arxiv.org/abs/2608.16103v1)**  
  Authors: Yizhao Wang, Xinfa Wang, Jingbo Wang, Jingbo Wang, Guantao Zhang, Yafeng Han, Guohong Gao, Yuhe Xia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16103v1.pdf)  
  Keywords: gaussian splatting, segmentation, ar, 3d gaussian  
- **[Gaussian-JEPA: Joint-Embedding Predictive Learning for 3D Gaussian Splats](https://arxiv.org/abs/2608.15651v1)**  
  Authors: Bin Ren, Qi Ma, Yue Li, Zongyan Han, Yidi Li, Yuqian Fu, Rao Muhammad Anwer, Theo Gevers, Fahad Shahbaz Khan, Salman Khan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.15651v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://amazingren.github.io/Gaussian-JEPA/).)  
  Keywords: 3d gaussian, segmentation, geometry, ar, gaussian splatting  
- **[CausalSplat: Towards Comprehensive Hierarchical Reasoning in 3D Gaussian Splatting](https://arxiv.org/abs/2608.11150v2)**  
  Authors: Jiayu Ding, Meilu Song, Yun Chen, Wei Gao, Ge Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11150v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiayuding031020.github.io/CausalSplat)  
  Keywords: 3d gaussian, segmentation, ar, gaussian splatting, understanding  
- **[WildFireGS: Physics-Based Wildfire Simulation in Large-Scale Semantics-Enriched Gaussian Splatting Forest Scenes](https://arxiv.org/abs/2608.11100v1)**  
  Authors: Nienke Driessen, Joris Rijsdijk, Sören Pirk, Wojtek Palubicki, Dominik L. Michels, Michael Weinmann  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.11100v1.pdf)  
  Keywords: dynamic, 3d gaussian, semantic, ar, gaussian splatting  



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