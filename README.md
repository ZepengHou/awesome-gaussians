# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-09-06 01:55:58

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
- [Avatar Generation](#avatar-generation) (317 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (375 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (78 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (419 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (43 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (421 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (232 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (128 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (159 papers) - Papers about SLAM using Gaussian Splatting
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
  Keywords: gaussian splatting, survey, 3d reconstruction, geometry, illumination, ar, motion  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: nerf, dynamic, geometry, gaussian splatting, survey, 3d reconstruction, 3d gaussian, ar  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: medical, recognition, neural rendering, 4d, compact, gaussian splatting, 3d reconstruction, survey, autonomous driving, vr, 3d gaussian, ar, motion  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: mapping, animation, gaussian splatting, survey, geometry, ar  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: geometry, efficient, gaussian splatting, survey, 3d reconstruction, tracking, slam, 3d gaussian, ar, motion  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: gaussian splatting, survey, vr, 3d gaussian, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: mapping, gaussian splatting, ray tracing, survey, 3d gaussian, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: dynamic, mapping, efficient, face, localization, gaussian splatting, survey, tracking, slam, 3d gaussian, ar, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, gaussian splatting, survey, 3d gaussian, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: nerf, geometry, efficient, gaussian splatting, survey, 3d gaussian, ar  

### Acceleration

*Showing the latest 50 out of 212 papers*

- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: geometry, fast, gaussian splatting, 3d gaussian, ar  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: efficient, fast, gaussian splatting, head, acceleration, 3d gaussian, ar  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: dynamic, 4d, efficient, compact, gaussian splatting, compression, real-time rendering, deformation, ar  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, real-time rendering, 3d gaussian, illumination, ar  
- **[Fast and Compact 3D Gaussian Splatting with Polarized Opacity Prior](https://arxiv.org/abs/2608.22344v1)**  
  Authors: Zi-Ming Wang, Kai-Wen Duan, Kowei Huang, Akihiro Sugimoto, Shang-Hong Lai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22344v1.pdf)  
  Keywords: efficient, compact, fast, gaussian splatting, 3d gaussian, ar  
- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: nerf, face, compact, fast, gaussian splatting, ray tracing, real-time rendering, 3d gaussian, ar, motion  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, mapping, efficient, compact, fast, gaussian splatting, ray tracing, reflection, 3d gaussian, shadow, ar  
- **[RoofGS: Roofline-Guided End-to-End Acceleration of 3D Gaussian Splatting](https://arxiv.org/abs/2608.15785v1)**  
  Authors: Yang Luo, Yan Gong, Yongsheng Gao, Jie Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.15785v1.pdf)  
  Keywords: compact, fast, gaussian splatting, acceleration, 3d gaussian, ar  
- **[GaussMemory: Task-Driven 3D Gaussian Scene Memory for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2608.14986v1)**  
  Authors: Zhiqiang Hu, Shouren Huang, Masatoshi Ishikawa  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14986v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, fast  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: geometry, outdoor, localization, fast, gaussian splatting, 3d gaussian, ar  

### Applications

*Showing the latest 50 out of 994 papers*

- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: lighting, efficient, compact, gaussian splatting, 3d gaussian, ar  
- **[Reparametrizing 3D Gaussian Splatting for Real-Time Palette-based Color and Luminance Editing](https://arxiv.org/abs/2609.03897v1)**  
  Authors: Cheng-Kang Ted Chao, Yotam Gingold  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03897v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar  
- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: lightweight, nerf, robotics, sparse-view, gaussian splatting, 3d gaussian, ar  
- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: geometry, fast, gaussian splatting, 3d gaussian, ar  
- **[TruncGradGS: Improved 3D Gaussian Splatting via Truncated Gradient Updates](https://arxiv.org/abs/2609.03534v1)**  
  Authors: Theo Morales, Nhat-Quynh Le-Pham, Robin Atkins, Binh-Son Hua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03534v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, dynamic, ar  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: mapping, geometry, face, gaussian splatting, 3d gaussian, ar  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: mapping, geometry, gaussian splatting, 3d gaussian, deformation, ar  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: efficient, fast, gaussian splatting, head, acceleration, 3d gaussian, ar  
- **[AnyGS2Mesh: Feed-Forward Mesh Reconstruction from 3D Gaussian Splatting with Arbitrary-Resolution Views](https://arxiv.org/abs/2609.03304v1)**  
  Authors: Yuxuan Song, Fan Gao, Yibo Zhao, Jiarui Wen, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03304v1.pdf)  
  Keywords: geometry, efficient, gaussian splatting, 3d gaussian, ar  
- **[InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling](https://arxiv.org/abs/2609.02747v1)**  
  Authors: Tianheng Lu, Guangyu Wang, Ruqi Huang, Lu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02747v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, ar  

### Avatar Generation

*Showing the latest 50 out of 317 papers*

- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: mapping, geometry, face, gaussian splatting, 3d gaussian, ar  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: efficient, fast, gaussian splatting, head, acceleration, 3d gaussian, ar  
- **[Atlas: Algorithm-Hardware Co-Design for On-Device City-Scale 3D Gaussian Splatting in VR](https://arxiv.org/abs/2609.02352v1)**  
  Authors: He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Zihan Liu, Ruyang Li, Hui Wei, Yaqian Zhao, Jingwen Leng, Minyi Guo, Yu Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02352v1.pdf)  
  Keywords: dynamic, gaussian splatting, head, vr, 3d gaussian, ar  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: geometry, efficient, face, gaussian splatting, 3d gaussian, ar  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: segmentation, semantic, understanding, gaussian splatting, head, compression, 3d gaussian, ar  
- **[When 3D Gaussian Splatting Recovers Real Surfaces](https://arxiv.org/abs/2608.30054v1)**  
  Authors: Songhe Wang, David Johnathan Miller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30054v1.pdf)  
  Keywords: geometry, face, gaussian splatting, 3d gaussian, ar  
- **[GhostSplat: Input-Triggered Backdoors for Multi-View-Consistent 3D Content Manipulation in Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.29184v1)**  
  Authors: Yudong Gao, Zongjian Ding, Linghan Chen, Yajing Chen, Yu Xinglin, Jiale Liu, Shan Huang, Mingjun Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29184v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, ar  
- **[Physics-Integrated Operator Learning via Gaussian Splatting Representations](https://arxiv.org/abs/2608.24049v1)**  
  Authors: Jihao Zhang, Junyi Guo, Jian-Xun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.24049v1.pdf)  
  Keywords: dynamic, efficient, face, gaussian splatting, ar  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: semantic, efficient, face, sparse-view, compact, gaussian splatting, 3d gaussian, ar  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: nerf, human, mapping, high-fidelity, gaussian splatting, 3d reconstruction, 3d gaussian, ar  

### Dynamic Scene

*Showing the latest 50 out of 375 papers*

- **[TruncGradGS: Improved 3D Gaussian Splatting via Truncated Gradient Updates](https://arxiv.org/abs/2609.03534v1)**  
  Authors: Theo Morales, Nhat-Quynh Le-Pham, Robin Atkins, Binh-Son Hua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03534v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, dynamic, ar  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: mapping, geometry, gaussian splatting, 3d gaussian, deformation, ar  
- **[Atlas: Algorithm-Hardware Co-Design for On-Device City-Scale 3D Gaussian Splatting in VR](https://arxiv.org/abs/2609.02352v1)**  
  Authors: He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Zihan Liu, Ruyang Li, Hui Wei, Yaqian Zhao, Jingwen Leng, Minyi Guo, Yu Feng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02352v1.pdf)  
  Keywords: dynamic, gaussian splatting, head, vr, 3d gaussian, ar  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: dynamic, 4d, efficient, compact, gaussian splatting, compression, real-time rendering, deformation, ar  
- **[VirSqueezer: Generating Realistic Deformations and Squeezing Dynamics in VR from Fine-Grained Squeezing Controls](https://arxiv.org/abs/2609.01698v1)**  
  Authors: Qian Zhang, Xiaoming Chen, Xiaorui Ma, Haisheng Li, Weidong Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.01698v1.pdf)  
  Keywords: dynamic, gaussian splatting, vr, 3d gaussian, deformation, ar  
- **[EvoGS: Modeling Deformation Evolution for Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.00994v1)**  
  Authors: Wei Dong, Shahram Shirani, Jun Chen, Han Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.00994v1.pdf)  
  Keywords: dynamic, gaussian splatting, 3d gaussian, deformation, ar, motion  
- **[SMG: Semantic Motion Graph for Monocular Dynamic Gaussian Splatting](https://arxiv.org/abs/2608.31023v1)**  
  Authors: Haozheng Yu, Xinyu Yang, Rundong Luo, Jennifer J. Sun, Bharath Hariharan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31023v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smg-gaussian.github.io/.)  
  Keywords: dynamic, semantic, gaussian splatting, ar, motion  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: dynamic, compact, gaussian splatting, tracking, ar, motion  
- **[As-Rigid-As-Possible Deformation of Gaussian Radiance Fields](https://arxiv.org/abs/2608.29538v1)**  
  Authors: Xinhao Tong, Tianjia Shao, Yanlin Weng, Yin Yang, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29538v1.pdf)  
  Keywords: high quality, gaussian splatting, 3d gaussian, deformation, ar  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: dynamic, mapping, semantic, understanding, gaussian splatting, tracking, slam, geometry, ar, motion  

### Few-shot

*Showing the latest 50 out of 78 papers*

- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: lightweight, nerf, robotics, sparse-view, gaussian splatting, 3d gaussian, ar  
- **[GSPotential: Camera Potential Field for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2608.29346v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Yijun Feng, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29346v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, ar  
- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: efficient, sparse-view, compact, gaussian splatting, ar  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: semantic, efficient, face, sparse-view, compact, gaussian splatting, 3d gaussian, ar  
- **[GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors](https://arxiv.org/abs/2608.21849v1)**  
  Authors: Xinhui Liu, Can Wang, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21849v1.pdf)  
  Keywords: geometry, sparse-view, gaussian splatting, sparse view, 3d gaussian, ar  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: geometry, face, compact, gaussian splatting, 3d reconstruction, sparse view, light transport, illumination, ar  
- **[TR-GS: High-Fidelity Sparse-View CT Volumetric Rendering via t-Distribution Gaussian Splatting and Ray-Confidence Modeling](https://arxiv.org/abs/2608.16042v1)**  
  Authors: Zedong Xiao, Yiren Wang, Zhou Liu, Xiaolin Liu, Zhangji Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16042v1.pdf)  
  Keywords: medical, efficient, high-fidelity, sparse-view, gaussian splatting, sparse view, 3d gaussian, ar  
- **[Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)**  
  Authors: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10756v1.pdf)  
  Keywords: semantic, few-shot, face, localization, gaussian splatting, 3d gaussian, ar  
- **[TRACE-GS: On-Policy Trajectory Distillation with Privileged Geometric Conditioning for Sparse-View 3DGS Restoration](https://arxiv.org/abs/2608.10286v1)**  
  Authors: Linlian Jiang, Yuchen Xi, Sadman Rakib Pinon, Ruigang Yang, Yang Wang, Xinxin Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10286v1.pdf)  
  Keywords: geometry, sparse-view, gaussian splatting, 3d gaussian, ar  
- **[Objects as Audio-Visual Modal Sound Fields](https://arxiv.org/abs/2608.05145v2)**  
  Authors: Zisen Shao, Zihao Wei, Derong Jin, Ruohan Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.05145v2.pdf)  
  Keywords: geometry, few-shot, compact, localization, gaussian splatting, 3d reconstruction, 3d gaussian, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 419 papers*

- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: geometry, fast, gaussian splatting, 3d gaussian, ar  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: mapping, geometry, face, gaussian splatting, 3d gaussian, ar  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: mapping, geometry, gaussian splatting, 3d gaussian, deformation, ar  
- **[AnyGS2Mesh: Feed-Forward Mesh Reconstruction from 3D Gaussian Splatting with Arbitrary-Resolution Views](https://arxiv.org/abs/2609.03304v1)**  
  Authors: Yuxuan Song, Fan Gao, Yibo Zhao, Jiarui Wen, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03304v1.pdf)  
  Keywords: geometry, efficient, gaussian splatting, 3d gaussian, ar  
- **[DualDiff3D: Dual Structure-Appearance Diffusion Priors for Reliability-Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2609.01516v1)**  
  Authors: Qian Wang, Yu Wang, Weiqi Li, Xinhua Cheng, Xiandong Meng, Ronggang Wang, Jian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.01516v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, 3d reconstruction  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: geometry, efficient, face, gaussian splatting, 3d gaussian, ar  
- **[When 3D Gaussian Splatting Recovers Real Surfaces](https://arxiv.org/abs/2608.30054v1)**  
  Authors: Songhe Wang, David Johnathan Miller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30054v1.pdf)  
  Keywords: geometry, face, gaussian splatting, 3d gaussian, ar  
- **[Elastic Triangle Splatting](https://arxiv.org/abs/2608.29106v1)**  
  Authors: Tian Shi, Shenhan Qian, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29106v1.pdf)  
  Keywords: neural rendering, gaussian splatting, 3d gaussian, ar, shape reconstruction  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: dynamic, mapping, semantic, understanding, gaussian splatting, tracking, slam, geometry, ar, motion  
- **[ReconSplat: Generalizable 3D Scene Reconstruction Beyond Observed Views](https://arxiv.org/abs/2608.28895v1)**  
  Authors: Giuseppe Stracquadanio, Kevin Raj, Julia Grabinski, Stefan Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28895v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, ar  

### Large Scene

- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: segmentation, dynamic, semantic, outdoor, 4d, high-fidelity, gaussian splatting, compression, geometry, ar, motion  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: geometry, outdoor, efficient, face, compact, gaussian splatting, 3d gaussian, ar, motion  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: geometry, outdoor, localization, fast, gaussian splatting, 3d gaussian, ar  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: segmentation, semantic, outdoor, understanding, efficient, localization, gaussian splatting, 3d gaussian, ar  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: lightweight, geometry, mapping, outdoor, localization, gaussian splatting, tracking, slam, 3d gaussian, ar  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: dynamic, outdoor, animation, gaussian splatting, 3d gaussian, deformation, ar, motion  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: recognition, efficient, fast, gaussian splatting, large scene, real-time rendering, slam, 3d gaussian, ar, motion  
- **[GeoGS-SLAM: Online Monocular Reconstruction Using Gaussian Splatting with Geometric Priors](https://arxiv.org/abs/2607.11184v1)**  
  Authors: Ruilan Gao, Letian Jin, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.11184v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rlgao.github.io/geogs_slam.)  
  Keywords: geometry, mapping, outdoor, gaussian splatting, tracking, slam, 3d gaussian, ar  
- **[Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction](https://arxiv.org/abs/2607.08769v1)**  
  Authors: Weijian Chen, Weibo Yao, Yuhang Zhang, Xiaolin Tang, Guo Wang, Weijun Zhang, Xitong Gao, Yihao Chen, Hongde Qin, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.08769v1.pdf)  
  Keywords: geometry, outdoor, gaussian splatting, 3d gaussian, ar  
- **[City-Level 3D Surface Reconstruction with Viewpoint Orientation Partitioning and Scene Completion](https://arxiv.org/abs/2607.03771v1)**  
  Authors: Liang Han, Wenyuan Zhang, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.03771v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanl2010.github.io/VOP-GS.)  
  Keywords: geometry, efficient, face, large scene, gaussian splatting, sparse view, 3d gaussian, ar  

### Model Compression

*Showing the latest 50 out of 421 papers*

- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: lighting, efficient, compact, gaussian splatting, 3d gaussian, ar  
- **[Reparametrizing 3D Gaussian Splatting for Real-Time Palette-based Color and Luminance Editing](https://arxiv.org/abs/2609.03897v1)**  
  Authors: Cheng-Kang Ted Chao, Yotam Gingold  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03897v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar  
- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: lightweight, nerf, robotics, sparse-view, gaussian splatting, 3d gaussian, ar  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: efficient, fast, gaussian splatting, head, acceleration, 3d gaussian, ar  
- **[AnyGS2Mesh: Feed-Forward Mesh Reconstruction from 3D Gaussian Splatting with Arbitrary-Resolution Views](https://arxiv.org/abs/2609.03304v1)**  
  Authors: Yuxuan Song, Fan Gao, Yibo Zhao, Jiarui Wen, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03304v1.pdf)  
  Keywords: geometry, efficient, gaussian splatting, 3d gaussian, ar  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: lighting, efficient, relighting, gaussian splatting, 3d gaussian, illumination, ar  
- **[CC-4DGS: Computational Deformation and Point-Cloud Compression for Storage-Efficient Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.02184v1)**  
  Authors: Kyungdae Park, Chae Eun Rhee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02184v1.pdf)  
  Keywords: dynamic, 4d, efficient, compact, gaussian splatting, compression, real-time rendering, deformation, ar  
- **[BRF-GS: Hyperspectral Bidirectional Reflectance Factor Modeling and Image Generation Based on 3D Gaussian Splatting](https://arxiv.org/abs/2608.31159v1)**  
  Authors: Yiling Yao, Wenjuan Zhang, Bowen Wang, Bocheng Li, Wentao Song, Bing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31159v1.pdf)  
  Keywords: geometry, efficient, face, gaussian splatting, 3d gaussian, ar  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: segmentation, semantic, understanding, gaussian splatting, head, compression, 3d gaussian, ar  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: dynamic, compact, gaussian splatting, tracking, ar, motion  

### Quality Enhancement

*Showing the latest 50 out of 232 papers*

- **[InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling](https://arxiv.org/abs/2609.02747v1)**  
  Authors: Tianheng Lu, Guangyu Wang, Ruqi Huang, Lu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02747v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, ar  
- **[As-Rigid-As-Possible Deformation of Gaussian Radiance Fields](https://arxiv.org/abs/2608.29538v1)**  
  Authors: Xinhao Tong, Tianjia Shao, Yanlin Weng, Yin Yang, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29538v1.pdf)  
  Keywords: high quality, gaussian splatting, 3d gaussian, deformation, ar  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: dynamic, lighting, high-fidelity, compact, gaussian splatting, geometry, ar  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, real-time rendering, 3d gaussian, illumination, ar  
- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: nerf, high-fidelity, gaussian splatting, 3d reconstruction, ar  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: geometry, mapping, efficient, high-fidelity, localization, gaussian splatting, tracking, slam, 3d gaussian, ar  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, semantic, 4d, high-fidelity, gaussian splatting, tracking, 3d gaussian, ar, motion  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: segmentation, dynamic, semantic, outdoor, 4d, high-fidelity, gaussian splatting, compression, geometry, ar, motion  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: nerf, human, mapping, high-fidelity, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[TopoSurfel: Closing the Loop between Gaussian Surfels and Meshes for Surface Reconstruction](https://arxiv.org/abs/2608.20687v2)**  
  Authors: Chuanjin Fan, Wenjie Chang, Bohao Liao, Yujia Chen, Wenfei Yang, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20687v2.pdf)  
  Keywords: dynamic, geometry, high-fidelity, face, gaussian splatting, 3d gaussian, ar  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: nerf, face, compact, fast, gaussian splatting, ray tracing, real-time rendering, 3d gaussian, ar, motion  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, mapping, efficient, compact, fast, gaussian splatting, ray tracing, reflection, 3d gaussian, shadow, ar  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: lighting, efficient, face, relighting, gaussian splatting, ray tracing, reflection, illumination, ar  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: human, dynamic, geometry, high-fidelity, face, gaussian splatting, ray tracing, reflection, 3d gaussian, ar, motion  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: fast, gaussian splatting, ray tracing, 3d gaussian, ar  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: geometry, efficient, fast, gaussian splatting, ray tracing, path tracing, real-time rendering, reflection, 3d gaussian, ar  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: geometry, efficient, global illumination, gaussian splatting, 3d reconstruction, 3d gaussian, illumination, ar  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: high-fidelity, global illumination, gaussian splatting, illumination, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: segmentation, geometry, semantic, efficient, gaussian splatting, ray tracing, reflection, 3d gaussian, ar  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: global illumination, face, fast, gaussian splatting, 3d gaussian, shadow, illumination, ar  

### Relighting

*Showing the latest 50 out of 128 papers*

- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: lighting, efficient, compact, gaussian splatting, 3d gaussian, ar  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: lighting, efficient, relighting, gaussian splatting, 3d gaussian, illumination, ar  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: dynamic, lighting, high-fidelity, compact, gaussian splatting, geometry, ar  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, real-time rendering, 3d gaussian, illumination, ar  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: gaussian splatting, survey, 3d reconstruction, geometry, illumination, ar, motion  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: geometry, face, compact, gaussian splatting, 3d reconstruction, sparse view, light transport, illumination, ar  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, mapping, efficient, compact, fast, gaussian splatting, ray tracing, reflection, 3d gaussian, shadow, ar  
- **[Geometry-Aware Online Mapping for 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2608.14902v1)**  
  Authors: Thai Luu, Quan Tran, Hieu Phan, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14902v1.pdf)  
  Keywords: geometry, mapping, lighting, efficient, localization, gaussian splatting, head, tracking, slam, 3d gaussian, ar  
- **[SpotlessGS: Relightable 3D Gaussian Splatting under Dynamic Illumination for Robotic Perception](https://arxiv.org/abs/2608.14713v1)**  
  Authors: Liang Hong, Jiaxin Wei, Simon Schaefer, Stefan Leutenegger, Jaehyung Jung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.14713v1.pdf)  
  Keywords: dynamic, lighting, gaussian splatting, relightable, 3d reconstruction, 3d gaussian, illumination, ar  
- **[AdvTiles: Physical Adversarial Camouflage Clothing against Person Detectors via Learnable Tiles](https://arxiv.org/abs/2608.06801v1)**  
  Authors: Jinlei Wang, Jiahuan Long, Mingkai Sun, Yafei Guo, Yuanhao Huang, Ming Wang, Junqi Wu, Jiacheng Hou, Hongbo Chen, Xingxing Wei, Tingsong Jiang, Wen Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06801v1.pdf)  
  Keywords: body, gaussian splatting, 3d gaussian, illumination, ar  

### SLAM

*Showing the latest 50 out of 159 papers*

- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: mapping, geometry, face, gaussian splatting, 3d gaussian, ar  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: mapping, geometry, gaussian splatting, 3d gaussian, deformation, ar  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: dynamic, compact, gaussian splatting, tracking, ar, motion  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: dynamic, mapping, semantic, understanding, gaussian splatting, tracking, slam, geometry, ar, motion  
- **[Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots](https://arxiv.org/abs/2608.26383v1)**  
  Authors: Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26383v1.pdf)  
  Keywords: nerf, lightweight, geometry, gaussian splatting, 3d reconstruction, tracking, 3d gaussian, ar  
- **[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906v1)**  
  Authors: Yingxiang Xu, Kerui Ren, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22906v1.pdf)  
  Keywords: geometry, mapping, efficient, high-fidelity, localization, gaussian splatting, tracking, slam, 3d gaussian, ar  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, semantic, 4d, high-fidelity, gaussian splatting, tracking, 3d gaussian, ar, motion  
- **[In-Situ Reconstruction of the International Space Station Using 3D Gaussian Splatting and Astrobee](https://arxiv.org/abs/2608.21685v1)**  
  Authors: Hudson Kim, Ryan Soussan, Brian Coltin, Jordan Kam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21685v1.pdf)  
  Keywords: nerf, human, mapping, high-fidelity, gaussian splatting, 3d reconstruction, 3d gaussian, ar  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, mapping, efficient, compact, fast, gaussian splatting, ray tracing, reflection, 3d gaussian, shadow, ar  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: nerf, semantic, high-fidelity, face, localization, gaussian splatting, tracking, 3d gaussian, ar  

### Scene Understanding

*Showing the latest 50 out of 223 papers*

- **[SMG: Semantic Motion Graph for Monocular Dynamic Gaussian Splatting](https://arxiv.org/abs/2608.31023v1)**  
  Authors: Haozheng Yu, Xinyu Yang, Rundong Luo, Jennifer J. Sun, Bharath Hariharan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31023v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smg-gaussian.github.io/.)  
  Keywords: dynamic, semantic, gaussian splatting, ar, motion  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: segmentation, semantic, understanding, gaussian splatting, head, compression, 3d gaussian, ar  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: dynamic, mapping, semantic, understanding, gaussian splatting, tracking, slam, geometry, ar, motion  
- **[CoGeo-GS: Concept-Driven and Geometry-Aware Multi-Object Removal in 3D Scenes](https://arxiv.org/abs/2608.26656v1)**  
  Authors: Yuanxiang Ni, Xianliang Huang, Chenhang Ma, Chen Xiao, Yuewen Ma, Ruxin Wang, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.26656v1.pdf)  
  Keywords: geometry, semantic, gaussian splatting, 3d gaussian, ar  
- **[NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction](https://arxiv.org/abs/2608.22888v2)**  
  Authors: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22888v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nemosplat.hkustvgd.com)  
  Keywords: dynamic, semantic, 4d, high-fidelity, gaussian splatting, tracking, 3d gaussian, ar, motion  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: semantic, efficient, face, sparse-view, compact, gaussian splatting, 3d gaussian, ar  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: segmentation, dynamic, semantic, outdoor, 4d, high-fidelity, gaussian splatting, compression, geometry, ar, motion  
- **[GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.17535v1)**  
  Authors: Qijian Tian, Zimeng Wu, Xuhong Wang, Lizhuang Ma, Xin Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17535v1.pdf)  
  Keywords: segmentation, geometry, semantic, understanding, efficient, compact, gaussian splatting, 3d gaussian, ar  
- **[DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438v1)**  
  Authors: Xiujin Liu, Tianyu Yang, Yilun Zhao, Xiangliang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21438v1.pdf)  
  Keywords: nerf, semantic, high-fidelity, face, localization, gaussian splatting, tracking, 3d gaussian, ar  
- **[Beyond Similarity Matching: Structured Reasoning for Open-Vocabulary Referring Segmentation in 3DGS](https://arxiv.org/abs/2608.16103v1)**  
  Authors: Yizhao Wang, Xinfa Wang, Jingbo Wang, Jingbo Wang, Guantao Zhang, Yafeng Han, Guohong Gao, Yuhe Xia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.16103v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, segmentation, ar  



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