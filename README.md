# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-09-16 02:22:09

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
- [Acceleration](#acceleration) (209 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (317 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (376 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (420 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (46 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (410 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (224 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (124 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (158 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (217 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: geometry, ar, 3d reconstruction, survey, illumination, motion, gaussian splatting  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: nerf, geometry, ar, 3d reconstruction, survey, 3d gaussian, dynamic, gaussian splatting  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: neural rendering, 3d reconstruction, survey, ar, medical, 4d, recognition, vr, 3d gaussian, motion, compact, autonomous driving, gaussian splatting  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, animation, ar, survey, mapping, gaussian splatting  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: geometry, ar, 3d reconstruction, survey, slam, tracking, 3d gaussian, motion, efficient, gaussian splatting  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: ar, survey, vr, 3d gaussian, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ray tracing, ar, survey, 3d gaussian, mapping, gaussian splatting  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: face, ar, survey, slam, tracking, localization, 3d gaussian, dynamic, mapping, motion, efficient, gaussian splatting  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: ar, survey, 3d gaussian, robotics, gaussian splatting  

### Acceleration

*Showing the latest 50 out of 209 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, compression, lightweight, fast, high-fidelity, deformation, efficient, gaussian splatting  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: geometry, head, ar, lightweight, fast, high-fidelity, 3d gaussian, gaussian splatting  
- **[GSComplete: Gaussian Splat Completion with 2D Diffusion Priors](https://arxiv.org/abs/2609.08449v1)**  
  Authors: Elias Brugger, Philipp Erler, Stefan Ohrhallinger, Paul Guerrero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08449v1.pdf)  
  Keywords: high-fidelity, ar, fast  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, slam, tracking, fast, high-fidelity, 3d gaussian, motion, efficient, gaussian splatting  
- **[UniFusion: Sparse-View 4D Reconstruction via Unified Spatio-temporal Depth Alignment](https://arxiv.org/abs/2609.05888v1)**  
  Authors: Yongzhe Lyu, Shaofei Wang, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05888v1.pdf)  
  Keywords: geometry, ar, segmentation, 4d, tracking, sparse-view, fast, human, dynamic, gaussian splatting  
- **[GradRig: Differentiable Weights for Skinned Gaussian Splat Deformation](https://arxiv.org/abs/2609.05127v1)**  
  Authors: Nina Vesseron, Élie Michel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05127v1.pdf)  
  Keywords: ar, real-time rendering, 3d gaussian, dynamic, deformation  
- **[TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization](https://arxiv.org/abs/2609.03613v1)**  
  Authors: Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, Juho Kannala  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03613v1.pdf)  
  Keywords: geometry, ar, fast, 3d gaussian, gaussian splatting  
- **[Laplacian Frequency Hierarchies for Efficient 3D Gaussian Splatting Training](https://arxiv.org/abs/2609.03334v1)**  
  Authors: Yixiong Yang, Sisheng Zhang, Qingsong Yan, Shaohuai Shi, Qiang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03334v1.pdf)  
  Keywords: head, ar, fast, 3d gaussian, acceleration, efficient, gaussian splatting  

### Applications

*Showing the latest 50 out of 995 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[BRAVE-6D: Benchmark for Robotic Active Vision in 6DOF Pose Estimation](https://arxiv.org/abs/2609.17106v1)**  
  Authors: Philipp Ausserlechner, Bernhard Neuberger, Alessandro Scherl, Michael Schebek, Stefan Thalhammer, Markus Vincze  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17106v1.pdf)  
  Keywords: robotics, ar  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: geometry, ar, sparse-view, 3d gaussian, motion, gaussian splatting  
- **[HLC-GS: Risk-Map-Guided Height-Layer Consistency Gaussian Splatting for DSM Reconstruction from Optical Satellite Imagery](https://arxiv.org/abs/2609.16772v1)**  
  Authors: Jie Yang, Yingdong Pi, Qiyan Luo, Xiaoyu Wang, Lekang Wen, Mi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16772v1.pdf)  
  Keywords: face, ar, 3d gaussian, efficient, gaussian splatting  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: ar, outdoor, 3d gaussian, motion, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[SceneBench: A Hierarchical Benchmark for Vision-Language Understanding of 3D Scenes](https://arxiv.org/abs/2609.16233v1)**  
  Authors: Anubhav Khanal, Prabigya Acharya, Roshni Poudel, Sujan Kapali, Bigyan Bhatta, Pramish Paudel, Francois Rameau, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16233v1.pdf)  
  Keywords: geometry, ar, recognition, understanding, human, semantic, gaussian splatting  
- **[What Makes a 3D Scene Editable? A Factorized Benchmark of Fidelity, Locality, Consistency, and Preservation](https://arxiv.org/abs/2609.14899v1)**  
  Authors: Sariah Patro, Arjun Mehra, Nikhil Bhatia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14899v1.pdf)  
  Keywords: nerf, geometry, ar, 3d gaussian, semantic, gaussian splatting  
- **[Gaussian-splatting ptychography via explicit and interpretable primitives](https://arxiv.org/abs/2609.14891v1)**  
  Authors: Qianhao Zhao, Zhixuan Hong, David Brady, Changhuei Yang, Andrew Maiden, Zhongtian Zheng, Ruihai Wang, Daniel Gage, Mary Lipton, Christopher Anderton, Arunima Bhattacharjee, Guoan Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14891v1.pdf)  
  Keywords: ar  
- **[SCOUT-SLAM: Structurally-Coupled Dual Uncertainty-Aware 3DGS SLAM in the Wild](https://arxiv.org/abs/2609.14634v1)**  
  Authors: Kumaran Karthik, Pramat Shastri Jois, Suresh Sundaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14634v1.pdf)  
  Keywords: ar, slam, tracking, localization, 3d gaussian, dynamic, motion, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 317 papers*

- **[HLC-GS: Risk-Map-Guided Height-Layer Consistency Gaussian Splatting for DSM Reconstruction from Optical Satellite Imagery](https://arxiv.org/abs/2609.16772v1)**  
  Authors: Jie Yang, Yingdong Pi, Qiyan Luo, Xiaoyu Wang, Lekang Wen, Mi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16772v1.pdf)  
  Keywords: face, ar, 3d gaussian, efficient, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[SceneBench: A Hierarchical Benchmark for Vision-Language Understanding of 3D Scenes](https://arxiv.org/abs/2609.16233v1)**  
  Authors: Anubhav Khanal, Prabigya Acharya, Roshni Poudel, Sujan Kapali, Bigyan Bhatta, Pramish Paudel, Francois Rameau, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16233v1.pdf)  
  Keywords: geometry, ar, recognition, understanding, human, semantic, gaussian splatting  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: nerf, head, ar, 3d gaussian, outdoor, compact, gaussian splatting  
- **[RouteBridge: Reliability-Routed Bidirectional Distillation Between Neural Radiance Fields and 3D Gaussian Splatting](https://arxiv.org/abs/2609.09606v1)**  
  Authors: YuanHang Wang, Xin Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.09606v1.pdf)  
  Keywords: nerf, face, ar, 3d gaussian, gaussian splatting  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: geometry, head, ar, lightweight, fast, high-fidelity, 3d gaussian, gaussian splatting  
- **[Heat Kernel Textures: the Geodesic Gaussians That Do Not Splat](https://arxiv.org/abs/2609.07557v1)**  
  Authors: Simone Foti, Caner Korkmaz, Stefanos Zafeiriou, Tolga Birdal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07557v1.pdf)  
  Keywords: face, geometry, ar, 3d gaussian, mapping, gaussian splatting  
- **[From Explicit References to Scene Manifolds: Distributional Fidelity and Realism for Radiance Field Quality Assessment](https://arxiv.org/abs/2609.07346v1)**  
  Authors: Saeed Mahmoudpour, Gi-Mun Um, Hyon-Gon Choo, Peter Schelkens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07346v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gitlab.com/saeedmp/scoda.)  
  Keywords: nerf, ar, compression, lightweight, 3d gaussian, human, semantic, gaussian splatting  
- **[UniFusion: Sparse-View 4D Reconstruction via Unified Spatio-temporal Depth Alignment](https://arxiv.org/abs/2609.05888v1)**  
  Authors: Yongzhe Lyu, Shaofei Wang, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05888v1.pdf)  
  Keywords: geometry, ar, segmentation, 4d, tracking, sparse-view, fast, human, dynamic, gaussian splatting  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: face, geometry, ar, 3d gaussian, mapping, gaussian splatting  

### Dynamic Scene

*Showing the latest 50 out of 376 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: geometry, ar, sparse-view, 3d gaussian, motion, gaussian splatting  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: ar, outdoor, 3d gaussian, motion, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[SCOUT-SLAM: Structurally-Coupled Dual Uncertainty-Aware 3DGS SLAM in the Wild](https://arxiv.org/abs/2609.14634v1)**  
  Authors: Kumaran Karthik, Pramat Shastri Jois, Suresh Sundaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14634v1.pdf)  
  Keywords: ar, slam, tracking, localization, 3d gaussian, dynamic, motion, gaussian splatting  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, compression, lightweight, fast, high-fidelity, deformation, efficient, gaussian splatting  
- **[SkyAnchor: Updating Metric-scale Aerial 3D Gaussian Scenes from Unposed Ground-View Sequences](https://arxiv.org/abs/2609.13903v1)**  
  Authors: Zhuoxiao Li, Xinyi Liu, Taoyu Wu, Yinrui Ren, Tongyan Hua, Ou Jing, Shuai Zhang, Dongli Wu, Rongjun Qin, Ge Lin Kan, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.13903v1.pdf)  
  Keywords: ar, lightweight, localization, 3d gaussian, motion, gaussian splatting  
- **[NOVA-GS: Noise-Aware View-Consistent Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2609.12682v1)**  
  Authors: Shaurya Pavan A, Vemunuri Divya Madhuri, Yash Pradeep Gawande, Kaushik Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shaurya2524.github.io/nova-gs/)  
  Keywords: geometry, ar, 3d gaussian, motion, gaussian splatting  
- **[EdMCGS: Event-Driven Markov Chain Gaussian Splatting for Extreme-Low-Frame-Rate Dynamic Scene Reconstruction](https://arxiv.org/abs/2609.08332v1)**  
  Authors: Yuzhong Wang, Wenmin Wang, Xinxing Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08332v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, motion, compact, gaussian splatting  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, slam, tracking, fast, high-fidelity, 3d gaussian, motion, efficient, gaussian splatting  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: geometry, ar, sparse-view, 3d gaussian, motion, gaussian splatting  
- **[VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views](https://arxiv.org/abs/2609.12343v1)**  
  Authors: Yunsu Jeong, Hyuk Heo, Youngsang Kwak, Jaehwa Kwak, Il Yong Chun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12343v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting  
- **[Shape-guided Gaussian Splatting for Sparse-View X-ray 3D Reconstruction](https://arxiv.org/abs/2609.10376v1)**  
  Authors: Pranav Poudel, Florence Dell'Aniello Picard, Nairouz Shehata, Frédéric Lavoie, Herve Lombaert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10376v1.pdf)  
  Keywords: geometry, ar, 3d reconstruction, sparse-view, 3d gaussian, gaussian splatting  
- **[TV-SGS: Gaussian Splatting with Geometric Information Propagation via Tensor Voting under sparse views](https://arxiv.org/abs/2609.07734v1)**  
  Authors: Harish N Sathishchandra, Philippos Mordohai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07734v1.pdf)  
  Keywords: sparse view, geometry, ar, gaussian splatting  
- **[UniFusion: Sparse-View 4D Reconstruction via Unified Spatio-temporal Depth Alignment](https://arxiv.org/abs/2609.05888v1)**  
  Authors: Yongzhe Lyu, Shaofei Wang, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05888v1.pdf)  
  Keywords: geometry, ar, segmentation, 4d, tracking, sparse-view, fast, human, dynamic, gaussian splatting  
- **[Rethinking 3D Noise: Learning 3D-Aware Video Priors via Optimization-Free Morphological Perturbations](https://arxiv.org/abs/2609.03657v1)**  
  Authors: Onat Şahin, Mohammad Altillawi, George Eskandar, Carlos Carbone, Ziyuan Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03657v1.pdf)  
  Keywords: nerf, ar, lightweight, sparse-view, 3d gaussian, robotics, gaussian splatting  
- **[GSPotential: Camera Potential Field for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2608.29346v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Yijun Feng, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29346v1.pdf)  
  Keywords: 3d gaussian, ar, sparse-view, gaussian splatting  
- **[PAGS: Autofocusing Photoacoustic Tomography via Speed-of-Sound-Adaptive Gaussian Splatting](https://arxiv.org/abs/2608.25472v1)**  
  Authors: Jiarui Ge, Jintao Ma, Bangxu Fan, Jinyan Zhang, Xiaokang Yang, Shuai Na, Xiaoyun Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25472v1.pdf)  
  Keywords: ar, sparse-view, compact, efficient, gaussian splatting  
- **[Seeing the Unseen: Semantic-in-Gaussian for Sparse-View 3D Generalization](https://arxiv.org/abs/2608.22740v1)**  
  Authors: Zeyang Bai, Yunpeng Wang, Yunbiao Wang, Jun Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22740v1.pdf)  
  Keywords: face, ar, sparse-view, 3d gaussian, compact, efficient, semantic, gaussian splatting  
- **[GaussVid: Sparse-View Gaussian Splatting with 3D-Aware Video Diffusion Priors](https://arxiv.org/abs/2608.21849v1)**  
  Authors: Xinhui Liu, Can Wang, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.21849v1.pdf)  
  Keywords: geometry, ar, sparse view, sparse-view, 3d gaussian, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 420 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: geometry, ar, sparse-view, 3d gaussian, motion, gaussian splatting  
- **[SceneBench: A Hierarchical Benchmark for Vision-Language Understanding of 3D Scenes](https://arxiv.org/abs/2609.16233v1)**  
  Authors: Anubhav Khanal, Prabigya Acharya, Roshni Poudel, Sujan Kapali, Bigyan Bhatta, Pramish Paudel, Francois Rameau, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16233v1.pdf)  
  Keywords: geometry, ar, recognition, understanding, human, semantic, gaussian splatting  
- **[What Makes a 3D Scene Editable? A Factorized Benchmark of Fidelity, Locality, Consistency, and Preservation](https://arxiv.org/abs/2609.14899v1)**  
  Authors: Sariah Patro, Arjun Mehra, Nikhil Bhatia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14899v1.pdf)  
  Keywords: nerf, geometry, ar, 3d gaussian, semantic, gaussian splatting  
- **[NOVA-GS: Noise-Aware View-Consistent Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2609.12682v1)**  
  Authors: Shaurya Pavan A, Vemunuri Divya Madhuri, Yash Pradeep Gawande, Kaushik Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shaurya2524.github.io/nova-gs/)  
  Keywords: geometry, ar, 3d gaussian, motion, gaussian splatting  
- **[RIDE: Relocalization-Informed Depth Estimation with 3D Gaussian Splatting](https://arxiv.org/abs/2609.11079v1)**  
  Authors: Jiarong Lian, Zhe Xiao, Zhaoyang Zhang, Wei Li, Ruizhi Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.11079v1.pdf)  
  Keywords: geometry, ar, localization, 3d gaussian, gaussian splatting  
- **[Shape-guided Gaussian Splatting for Sparse-View X-ray 3D Reconstruction](https://arxiv.org/abs/2609.10376v1)**  
  Authors: Pranav Poudel, Florence Dell'Aniello Picard, Nairouz Shehata, Frédéric Lavoie, Herve Lombaert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10376v1.pdf)  
  Keywords: geometry, ar, 3d reconstruction, sparse-view, 3d gaussian, gaussian splatting  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: geometry, head, ar, lightweight, fast, high-fidelity, 3d gaussian, gaussian splatting  
- **[TV-SGS: Gaussian Splatting with Geometric Information Propagation via Tensor Voting under sparse views](https://arxiv.org/abs/2609.07734v1)**  
  Authors: Harish N Sathishchandra, Philippos Mordohai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07734v1.pdf)  
  Keywords: sparse view, geometry, ar, gaussian splatting  
- **[Heat Kernel Textures: the Geodesic Gaussians That Do Not Splat](https://arxiv.org/abs/2609.07557v1)**  
  Authors: Simone Foti, Caner Korkmaz, Stefanos Zafeiriou, Tolga Birdal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07557v1.pdf)  
  Keywords: face, geometry, ar, 3d gaussian, mapping, gaussian splatting  

### Large Scene

- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: ar, outdoor, 3d gaussian, motion, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: nerf, head, ar, 3d gaussian, outdoor, compact, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: geometry, ar, compression, outdoor, segmentation, 4d, high-fidelity, dynamic, motion, semantic, gaussian splatting  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: face, geometry, ar, outdoor, 3d gaussian, motion, compact, efficient, gaussian splatting  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: geometry, ar, localization, fast, 3d gaussian, outdoor, gaussian splatting  
- **[OutLangSplat: 3D Language Gaussian Splatting for UAV Outdoor Scenes](https://arxiv.org/abs/2608.04560v1)**  
  Authors: Xia Yan, He Wu, Yanghui Xu, Zizhao Wu, Jiazhou Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.04560v1.pdf)  
  Keywords: ar, segmentation, localization, understanding, 3d gaussian, outdoor, efficient, semantic, gaussian splatting  
- **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](https://arxiv.org/abs/2607.21416v1)**  
  Authors: Panagiotis Mermigkas, Argyris Manetas, Petros Maragos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.21416v1.pdf)  
  Keywords: geometry, ar, slam, lightweight, tracking, localization, 3d gaussian, mapping, outdoor, gaussian splatting  
- **[AniGS: Bridging Rendering and Diffusion Prior for 3D Scene Animation](https://arxiv.org/abs/2607.18539v1)**  
  Authors: Yen-Chi Cheng, Chen Gao, Chuhan Chen, Tuotuo Li, Rajvi Shah, Ayush Saraf, Changil Kim, Liangyan Gui, Alexander Schwing, Johannes Kopf, Hung-Yu Tseng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.18539v1.pdf)  
  Keywords: animation, ar, outdoor, 3d gaussian, dynamic, deformation, motion, gaussian splatting  
- **[Immediate 3D Gaussian Splat Reconstruction of Unordered Input with Global Consistency](https://arxiv.org/abs/2607.14481v1)**  
  Authors: Andreas Meuleman, Linus Franke, Boris Zhestiankin, Camille Montemagni, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.14481v1.pdf)  
  Keywords: large scene, ar, slam, real-time rendering, recognition, fast, 3d gaussian, motion, efficient, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 410 papers*

- **[HLC-GS: Risk-Map-Guided Height-Layer Consistency Gaussian Splatting for DSM Reconstruction from Optical Satellite Imagery](https://arxiv.org/abs/2609.16772v1)**  
  Authors: Jie Yang, Yingdong Pi, Qiyan Luo, Xiaoyu Wang, Lekang Wen, Mi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16772v1.pdf)  
  Keywords: face, ar, 3d gaussian, efficient, gaussian splatting  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, compression, lightweight, fast, high-fidelity, deformation, efficient, gaussian splatting  
- **[SkyAnchor: Updating Metric-scale Aerial 3D Gaussian Scenes from Unposed Ground-View Sequences](https://arxiv.org/abs/2609.13903v1)**  
  Authors: Zhuoxiao Li, Xinyi Liu, Taoyu Wu, Yinrui Ren, Tongyan Hua, Ou Jing, Shuai Zhang, Dongli Wu, Rongjun Qin, Ge Lin Kan, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.13903v1.pdf)  
  Keywords: ar, lightweight, localization, 3d gaussian, motion, gaussian splatting  
- **[Is Gaussian Splatting Becoming Neural Again? A Taxonomy and Controlled Study of Learned Parameterization](https://arxiv.org/abs/2609.12395v1)**  
  Authors: YuanHang Wang, Xin Cao, Yi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12395v1.pdf)  
  Keywords: nerf, efficient, ar, gaussian splatting  
- **[Hologram Representation via Quadratic Phase Gaussian Splatting](https://arxiv.org/abs/2609.11434v1)**  
  Authors: Haolong Wang, Yicheng Zhan, Kaan Akşit, Simeng Qiu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.11434v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: nerf, head, ar, 3d gaussian, outdoor, compact, gaussian splatting  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: geometry, head, ar, lightweight, fast, high-fidelity, 3d gaussian, gaussian splatting  
- **[EdMCGS: Event-Driven Markov Chain Gaussian Splatting for Extreme-Low-Frame-Rate Dynamic Scene Reconstruction](https://arxiv.org/abs/2609.08332v1)**  
  Authors: Yuzhong Wang, Wenmin Wang, Xinxing Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08332v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, motion, compact, gaussian splatting  
- **[From Explicit References to Scene Manifolds: Distributional Fidelity and Realism for Radiance Field Quality Assessment](https://arxiv.org/abs/2609.07346v1)**  
  Authors: Saeed Mahmoudpour, Gi-Mun Um, Hyon-Gon Choo, Peter Schelkens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07346v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gitlab.com/saeedmp/scoda.)  
  Keywords: nerf, ar, compression, lightweight, 3d gaussian, human, semantic, gaussian splatting  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, slam, tracking, fast, high-fidelity, 3d gaussian, motion, efficient, gaussian splatting  

### Quality Enhancement

*Showing the latest 50 out of 224 papers*

- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, compression, lightweight, fast, high-fidelity, deformation, efficient, gaussian splatting  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: geometry, head, ar, lightweight, fast, high-fidelity, 3d gaussian, gaussian splatting  
- **[GSComplete: Gaussian Splat Completion with 2D Diffusion Priors](https://arxiv.org/abs/2609.08449v1)**  
  Authors: Elias Brugger, Philipp Erler, Stefan Ohrhallinger, Paul Guerrero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08449v1.pdf)  
  Keywords: high-fidelity, ar, fast  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, slam, tracking, fast, high-fidelity, 3d gaussian, motion, efficient, gaussian splatting  
- **[Generalizable 6D Pose Estimation of Textureless Objects with Planar-based Gaussian Splatting](https://arxiv.org/abs/2609.07231v1)**  
  Authors: Jie Lu, Hengtan Zhang, Li Gong, Pengpeng Wang, Xianjia Yu, Jinxiang Deng, Tomi Westerlund, Zhongxue Gan, Lirong Zheng, Zhuo Zou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07231v1.pdf)  
  Keywords: geometry, ar, high-fidelity, 3d gaussian, gaussian splatting  
- **[InceptionGS: Generative Bootstrapping for Large-Scale Gaussian Splatting under Unstructured View Sampling](https://arxiv.org/abs/2609.02747v1)**  
  Authors: Tianheng Lu, Guangyu Wang, Ruqi Huang, Lu Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02747v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting  
- **[As-Rigid-As-Possible Deformation of Gaussian Radiance Fields](https://arxiv.org/abs/2608.29538v1)**  
  Authors: Xinhao Tong, Tianjia Shao, Yanlin Weng, Yin Yang, Kun Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29538v1.pdf)  
  Keywords: ar, 3d gaussian, deformation, high quality, gaussian splatting  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: geometry, ar, high-fidelity, dynamic, compact, lighting, gaussian splatting  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: ar, real-time rendering, illumination, high-fidelity, 3d gaussian, dynamic, gaussian splatting  
- **[Comparative Evaluation of 3D Reconstruction Methods for Immersive Visualization of Laboratory Objects](https://arxiv.org/abs/2608.27301v1)**  
  Authors: Brian De La Cruz, Aaron Y. Zhao, Maitrey Gramopadhye, Sawyer J. Lazar, Xianming Tan, Daniel Szafir, David S. Lawrence  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.27301v1.pdf)  
  Keywords: nerf, ar, 3d reconstruction, high-fidelity, gaussian splatting  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: nerf, ray tracing, face, ar, real-time rendering, fast, 3d gaussian, motion, compact, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, ray tracing, ar, reflection, shadow, fast, 3d gaussian, mapping, compact, efficient, gaussian splatting  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: face, ray tracing, ar, relighting, reflection, illumination, efficient, lighting, gaussian splatting  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: face, ray tracing, geometry, ar, reflection, high-fidelity, 3d gaussian, human, dynamic, motion, gaussian splatting  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: ray tracing, ar, fast, 3d gaussian, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: ray tracing, geometry, ar, real-time rendering, reflection, fast, path tracing, 3d gaussian, efficient, gaussian splatting  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: global illumination, geometry, ar, 3d reconstruction, illumination, 3d gaussian, efficient, gaussian splatting  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: global illumination, ar, illumination, high-fidelity, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: geometry, ray tracing, ar, segmentation, reflection, 3d gaussian, efficient, semantic, gaussian splatting  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: global illumination, face, ar, shadow, fast, illumination, 3d gaussian, gaussian splatting  

### Relighting

*Showing the latest 50 out of 124 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: ar, 4d, fast, illumination, human, dynamic, outdoor, gaussian splatting  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: geometry, ar, recognition, 3d gaussian, robotics, lighting, gaussian splatting  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: ar, 3d gaussian, compact, efficient, lighting, gaussian splatting  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: ar, relighting, illumination, 3d gaussian, efficient, lighting, gaussian splatting  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: geometry, ar, high-fidelity, dynamic, compact, lighting, gaussian splatting  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v1)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v1.pdf)  
  Keywords: ar, real-time rendering, illumination, high-fidelity, 3d gaussian, dynamic, gaussian splatting  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: geometry, ar, 3d reconstruction, survey, illumination, motion, gaussian splatting  
- **[Point-Based 3D Reconstruction from Sparse Views under Known Illumination](https://arxiv.org/abs/2608.20000v1)**  
  Authors: Magnus Kaufmann Gjerde, Joakim Bruslund Haurum, Jeppe Revall Frisvad, Markus Worchel, J. Andreas Bærentzen, Thomas B. Moeslund  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.20000v1.pdf)  
  Keywords: face, geometry, ar, 3d reconstruction, sparse view, illumination, compact, light transport, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: nerf, ray tracing, ar, reflection, shadow, fast, 3d gaussian, mapping, compact, efficient, gaussian splatting  

### SLAM

*Showing the latest 50 out of 158 papers*

- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: geometry, ar, slam, tracking, localization, fast, 3d gaussian, dynamic, mapping, motion, robotics, lighting, gaussian splatting  
- **[SCOUT-SLAM: Structurally-Coupled Dual Uncertainty-Aware 3DGS SLAM in the Wild](https://arxiv.org/abs/2609.14634v1)**  
  Authors: Kumaran Karthik, Pramat Shastri Jois, Suresh Sundaram  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14634v1.pdf)  
  Keywords: ar, slam, tracking, localization, 3d gaussian, dynamic, motion, gaussian splatting  
- **[SkyAnchor: Updating Metric-scale Aerial 3D Gaussian Scenes from Unposed Ground-View Sequences](https://arxiv.org/abs/2609.13903v1)**  
  Authors: Zhuoxiao Li, Xinyi Liu, Taoyu Wu, Yinrui Ren, Tongyan Hua, Ou Jing, Shuai Zhang, Dongli Wu, Rongjun Qin, Ge Lin Kan, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.13903v1.pdf)  
  Keywords: ar, lightweight, localization, 3d gaussian, motion, gaussian splatting  
- **[RIDE: Relocalization-Informed Depth Estimation with 3D Gaussian Splatting](https://arxiv.org/abs/2609.11079v1)**  
  Authors: Jiarong Lian, Zhe Xiao, Zhaoyang Zhang, Wei Li, Ruizhi Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.11079v1.pdf)  
  Keywords: geometry, ar, localization, 3d gaussian, gaussian splatting  
- **[Heat Kernel Textures: the Geodesic Gaussians That Do Not Splat](https://arxiv.org/abs/2609.07557v1)**  
  Authors: Simone Foti, Caner Korkmaz, Stefanos Zafeiriou, Tolga Birdal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07557v1.pdf)  
  Keywords: face, geometry, ar, 3d gaussian, mapping, gaussian splatting  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, slam, tracking, fast, high-fidelity, 3d gaussian, motion, efficient, gaussian splatting  
- **[UniFusion: Sparse-View 4D Reconstruction via Unified Spatio-temporal Depth Alignment](https://arxiv.org/abs/2609.05888v1)**  
  Authors: Yongzhe Lyu, Shaofei Wang, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05888v1.pdf)  
  Keywords: geometry, ar, segmentation, 4d, tracking, sparse-view, fast, human, dynamic, gaussian splatting  
- **[STARS-GS: Structure-Aware Regularized Gaussian Splatting for Large-Scale Aerial Surface Reconstruction](https://arxiv.org/abs/2609.03447v1)**  
  Authors: Bocheng Li, Wenjuan Zhang, Jie Pan. Dongxu Han, Xuesong Ma, Yiling Yao, Yaning Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03447v1.pdf)  
  Keywords: face, geometry, ar, 3d gaussian, mapping, gaussian splatting  
- **[PointGT: Simultaneous Geometry and Texture Editing for Point-Based Representations](https://arxiv.org/abs/2609.03341v1)**  
  Authors: Yanshu Zhang, George Shramko, Pratul P. Srinivasan, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03341v1.pdf)  
  Keywords: geometry, ar, 3d gaussian, deformation, mapping, gaussian splatting  
- **[ATGS: Anchored Temporal Gaussian Splatting for Long Volumetric Video Representation](https://arxiv.org/abs/2608.30184v1)**  
  Authors: Jiahao Wu, Jie Liang, Die Hu, Jiayu Yang, Kaiqiang Xiong, Xiang Li, Xiaoyun Zheng, Chao Wang, Ronggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30184v1.pdf)  
  Keywords: ar, tracking, dynamic, motion, compact, gaussian splatting  

### Scene Understanding

*Showing the latest 50 out of 217 papers*

- **[SceneBench: A Hierarchical Benchmark for Vision-Language Understanding of 3D Scenes](https://arxiv.org/abs/2609.16233v1)**  
  Authors: Anubhav Khanal, Prabigya Acharya, Roshni Poudel, Sujan Kapali, Bigyan Bhatta, Pramish Paudel, Francois Rameau, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16233v1.pdf)  
  Keywords: geometry, ar, recognition, understanding, human, semantic, gaussian splatting  
- **[What Makes a 3D Scene Editable? A Factorized Benchmark of Fidelity, Locality, Consistency, and Preservation](https://arxiv.org/abs/2609.14899v1)**  
  Authors: Sariah Patro, Arjun Mehra, Nikhil Bhatia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14899v1.pdf)  
  Keywords: nerf, geometry, ar, 3d gaussian, semantic, gaussian splatting  
- **[From Explicit References to Scene Manifolds: Distributional Fidelity and Realism for Radiance Field Quality Assessment](https://arxiv.org/abs/2609.07346v1)**  
  Authors: Saeed Mahmoudpour, Gi-Mun Um, Hyon-Gon Choo, Peter Schelkens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07346v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gitlab.com/saeedmp/scoda.)  
  Keywords: nerf, ar, compression, lightweight, 3d gaussian, human, semantic, gaussian splatting  
- **[UniFusion: Sparse-View 4D Reconstruction via Unified Spatio-temporal Depth Alignment](https://arxiv.org/abs/2609.05888v1)**  
  Authors: Yongzhe Lyu, Shaofei Wang, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05888v1.pdf)  
  Keywords: geometry, ar, segmentation, 4d, tracking, sparse-view, fast, human, dynamic, gaussian splatting  
- **[An overview of 3D Vision-Language Models](https://arxiv.org/abs/2609.05583v1)**  
  Authors: Márcus Lobo, Vitor Matias, Afonso Paiva, Jeová Farias, Tiago Novello, Moacir Ponti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.05583v1.pdf)  
  Keywords: ar, segmentation, recognition, 3d gaussian, robotics, gaussian splatting  
- **[NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions](https://arxiv.org/abs/2609.04602v1)**  
  Authors: Junhui Wang, Wei Yang, Xinyao Li, Ningjing Fan, Yuehao Yin, Xuecheng Chen, Chao Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04602v1.pdf)  
  Keywords: 3d gaussian, ar, semantic, gaussian splatting  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: geometry, ar, recognition, 3d gaussian, robotics, lighting, gaussian splatting  
- **[SMG: Semantic Motion Graph for Monocular Dynamic Gaussian Splatting](https://arxiv.org/abs/2608.31023v1)**  
  Authors: Haozheng Yu, Xinyu Yang, Rundong Luo, Jennifer J. Sun, Bharath Hariharan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.31023v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://smg-gaussian.github.io/.)  
  Keywords: ar, dynamic, motion, semantic, gaussian splatting  
- **[VCAR: Training-Free 3DGS Segmentation via View Completeness and Axis-Aware Boundary Refinement](https://arxiv.org/abs/2608.30870v1)**  
  Authors: Kun Cao, Di Wang, Haibin Zhu, Haozhi Huang, Xu Wang, Zheng Shi, Guanghua Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.30870v1.pdf)  
  Keywords: head, ar, compression, segmentation, understanding, 3d gaussian, semantic, gaussian splatting  
- **[RoSe-SLAM: Robust Semantic-Aware Gaussian Splatting SLAM from Dynamic Monocular Videos](https://arxiv.org/abs/2608.29003v1)**  
  Authors: Wenting Wang, Jiaxin Guo, Wenzhen Dong, Yun-Hui Liu, Charlie C. L. Wang, Yeung Yam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.29003v1.pdf)  
  Keywords: geometry, ar, slam, tracking, understanding, dynamic, mapping, motion, semantic, gaussian splatting  



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