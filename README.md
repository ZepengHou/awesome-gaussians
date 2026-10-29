# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-10-29 03:29:51

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
- [Acceleration](#acceleration) (178 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (322 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (366 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (84 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (410 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (49 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (391 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (196 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (18 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (111 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (155 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (201 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Gaussian Splatting for Real-Time Scene Reconstruction: Methods, Systems, and Trade-offs](https://arxiv.org/abs/2610.17513v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.17513v1.pdf)  
  Keywords: gaussian splatting, survey, slam, dynamic, real-time rendering, compression, localization, mapping, ar, 3d gaussian, tracking, sparse-view  
- **[GS-Pool: Object-Level Change Detection in 3D Gaussian Splatting](https://arxiv.org/abs/2610.06688v1)**  
  Authors: Boaz Keren-Gil, James Gain, Patrick Marais  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.06688v1.pdf)  
  Keywords: gaussian splatting, survey, ar, 3d gaussian, geometry  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: gaussian splatting, face, survey, high-fidelity, ar, 3d gaussian  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: gaussian splatting, survey, compression, ar, 3d gaussian  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: gaussian splatting, survey, 3d reconstruction, illumination, ar, motion, geometry  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: gaussian splatting, survey, 3d reconstruction, dynamic, nerf, ar, 3d gaussian, geometry  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: gaussian splatting, survey, 3d reconstruction, medical, vr, 4d, ar, 3d gaussian, compact, autonomous driving, recognition, motion, neural rendering  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: gaussian splatting, animation, survey, mapping, ar, geometry  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: gaussian splatting, survey, slam, 3d reconstruction, efficient, ar, 3d gaussian, tracking, motion, geometry  

### Acceleration

*Showing the latest 50 out of 178 papers*

- **[Spatial MIMO Channel Rendering: A 3D Gaussian Splatting Approach](https://arxiv.org/abs/2610.36880v1)**  
  Authors: Juntaek Han, Geonha Kim, Chaozheng Wen, Ahmed Alkhateeb, Jun Zhang, Jeonghun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36880v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, head, 3d gaussian, fast  
- **[CVTSplat: Multi-view Reconstruction Using an Adaptive Centroidal Voronoi Tessellation](https://arxiv.org/abs/2610.35347v1)**  
  Authors: Briac Toussaint, Diego Thomas, Jean-Sébastien Franco, Edmond Boyer, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35347v1.pdf)  
  Keywords: face, ar, efficient, fast  
- **[RacerGS: Residual-Autoregressive Context for 3D Gaussian Splatting Compression](https://arxiv.org/abs/2610.34263v1)**  
  Authors: Wenqing Wang, Huimin Zeng, Yun Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34263v1.pdf)  
  Keywords: gaussian splatting, compression, ar, 3d gaussian, compact, fast  
- **[KoalaGS: Complexity-Aware Continuous Level of Detail for Gaussian Splatting](https://arxiv.org/abs/2610.28615v1)**  
  Authors: Radu Beche, Raoul de Charette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.28615v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, fast  
- **[Learning from Automatic 3D Gaussian Splatting Edits for Online Bayesian Scene Change Detection](https://arxiv.org/abs/2610.28490v2)**  
  Authors: Changrui Zhu, Simon Julier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.28490v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://changruizhu96.github.io/work/lego-scd/)  
  Keywords: gaussian splatting, ar, 3d gaussian, fast  
- **[RLSplat: Resource-Linear Budget Control for Feed-forward 3D Gaussian Splatting](https://arxiv.org/abs/2610.27712v2)**  
  Authors: Injae Kim, Minseok Joo, Jihwan Park, Sehyung Kim, Minseong Bae, Hyunwoo J. Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.27712v2.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, fast, efficient  
- **[Localization and Neural Splatting on the Edge: An FPGA Scene Memory for Robots](https://arxiv.org/abs/2610.25068v2)**  
  Authors: Haohua Que, Mingkai Liu, Tianle Zhu, Handong Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25068v2.pdf)  
  Keywords: gaussian splatting, localization, acceleration, ar, 3d gaussian, fast  
- **[SwitchSplat: Learning Discrete Object States from Casually Captured Scenes](https://arxiv.org/abs/2610.24812v2)**  
  Authors: Yizheng Xie, Yalda Foroutan, George Shramko, Daniel Rebain, Shrisudhan Govindarajan, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.24812v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://switchsplat.github.io)  
  Keywords: gaussian splatting, 3d reconstruction, dynamic, high-fidelity, 4d, ar, 3d gaussian, fast, geometry  
- **[RoMo-GS: Efficient Online 3D Gaussian Splatting for Robot Mapping via Exposure-Integrated Motion Blur](https://arxiv.org/abs/2610.24605v1)**  
  Authors: Sangwoo Jung, Di Deng, Jiahui Fu, Laura Herlant, Ayoung Kim, Yafei Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.24605v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, ar, 3d gaussian, fast, motion, geometry, robotics  
- **[EGGHead: Efficient Generalizable Gaussian Heads from a Single Image](https://arxiv.org/abs/2610.26898v1)**  
  Authors: Pilseo Park, Andrew Hou, Michel Sarkis, Ning Bi, Yiying Tong, Xiaoming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.26898v1.pdf)  
  Keywords: gaussian splatting, face, real-time rendering, semantic, nerf, ar, head, efficient, human  

### Applications

*Showing the latest 50 out of 996 papers*

- **[CTBakeGS: training-free baking of photorealistic CT volume renderings into 3D Gaussian splats](https://arxiv.org/abs/2610.37406v1)**  
  Authors: Haruki Fukuda, Constantin Lux, Wolf Schweitzer, Tadashi Hosoya, Lars Ebert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37406v1.pdf)  
  Keywords: gaussian splatting, medical, ar, 3d gaussian, lighting  
- **[DomeGS: Perceptually Consistent Background Completion for Unbounded 3D Gaussian Splatting in Virtual Reality](https://arxiv.org/abs/2610.37172v1)**  
  Authors: Anastasiya Pechko, Agata Szymańska, Piotr Borycki, Joanna Szelewska, Michał Mnich, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37172v1.pdf)  
  Keywords: gaussian splatting, vr, high-fidelity, ar, outdoor, 3d gaussian, geometry  
- **[GraftRay: Physically Based Mesh Insertion into Gaussian Splatting Scenes via Path Tracing](https://arxiv.org/abs/2610.37036v1)**  
  Authors: Jinxin Ai, Matthias Niessner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37036v1.pdf)  
  Keywords: gaussian splatting, face, reflection, illumination, shadow, ar, 3d gaussian, lighting, path tracing  
- **[Spatial MIMO Channel Rendering: A 3D Gaussian Splatting Approach](https://arxiv.org/abs/2610.36880v1)**  
  Authors: Juntaek Han, Geonha Kim, Chaozheng Wen, Ahmed Alkhateeb, Jun Zhang, Jeonghun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36880v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, head, 3d gaussian, fast  
- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[GeoGSplat: Geometry-Grounded Non-Pixel-Aligned Gaussian Splatting](https://arxiv.org/abs/2610.36760v1)**  
  Authors: Jiale Wang, Chen Zhao, Haoyang Zhang, Yanhao Wu, Fei He, Yanhu Shan, Rui Wu, Wei Ke, Tong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://comedy0913.github.io/projects/geogsplat)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[ClusterSplat: Semantic Cluster Selection for 3D Visual Grounding in Gaussian Splatting](https://arxiv.org/abs/2610.36462v1)**  
  Authors: Jaesung Lee, Hyeontaek Hwang, Gabriel Manalu, Daeyoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36462v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jaesung8.github.io/clustersplat/)  
  Keywords: gaussian splatting, segmentation, lightweight, semantic, ar, 3d gaussian  
- **[SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation](https://arxiv.org/abs/2610.36312v1)**  
  Authors: Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36312v1.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, outdoor, 3d gaussian, tracking, motion, geometry  
- **[PrinGS: Privacy Preservation in Gaussian Splatting](https://arxiv.org/abs/2610.36168v1)**  
  Authors: Gaurav Behera, Abhinav Raundhal, Archisha Panda, Saumya Balina, Gargi Shroff, Ponnurangam Kumaraguru  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36168v1.pdf)  
  Keywords: gaussian splatting, face, high-fidelity, ar, 3d gaussian, geometry, human  
- **[VidEdit3D: Flexible 3D Gaussian Editing with Video Diffusion](https://arxiv.org/abs/2610.35756v1)**  
  Authors: Yanming Yang, Chenxi Song, Tong Zhao, Juntao Xu, Wenhao Rao, Yiwen Chen, Yiwei Wang, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35756v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, semantic, ar, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 322 papers*

- **[GraftRay: Physically Based Mesh Insertion into Gaussian Splatting Scenes via Path Tracing](https://arxiv.org/abs/2610.37036v1)**  
  Authors: Jinxin Ai, Matthias Niessner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37036v1.pdf)  
  Keywords: gaussian splatting, face, reflection, illumination, shadow, ar, 3d gaussian, lighting, path tracing  
- **[Spatial MIMO Channel Rendering: A 3D Gaussian Splatting Approach](https://arxiv.org/abs/2610.36880v1)**  
  Authors: Juntaek Han, Geonha Kim, Chaozheng Wen, Ahmed Alkhateeb, Jun Zhang, Jeonghun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36880v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, head, 3d gaussian, fast  
- **[PrinGS: Privacy Preservation in Gaussian Splatting](https://arxiv.org/abs/2610.36168v1)**  
  Authors: Gaurav Behera, Abhinav Raundhal, Archisha Panda, Saumya Balina, Gargi Shroff, Ponnurangam Kumaraguru  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36168v1.pdf)  
  Keywords: gaussian splatting, face, high-fidelity, ar, 3d gaussian, geometry, human  
- **[VidEdit3D: Flexible 3D Gaussian Editing with Video Diffusion](https://arxiv.org/abs/2610.35756v1)**  
  Authors: Yanming Yang, Chenxi Song, Tong Zhao, Juntao Xu, Wenhao Rao, Yiwen Chen, Yiwei Wang, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35756v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, semantic, ar, 3d gaussian  
- **[Robot-Aligned 3D Gaussian Splatting for Precise Reaching with Wrist-Camera VLA Policies](https://arxiv.org/abs/2610.35626v1)**  
  Authors: Zuoxu Wang, Xiao Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35626v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://001-wang.github.io/PrecisionReach-GS/)  
  Keywords: gaussian splatting, ar, 3d gaussian, efficient, human  
- **[CVTSplat: Multi-view Reconstruction Using an Adaptive Centroidal Voronoi Tessellation](https://arxiv.org/abs/2610.35347v1)**  
  Authors: Briac Toussaint, Diego Thomas, Jean-Sébastien Franco, Edmond Boyer, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35347v1.pdf)  
  Keywords: face, ar, efficient, fast  
- **[Complexity-guided Regularization for Generalizable Human Gaussian Splatting](https://arxiv.org/abs/2610.35152v1)**  
  Authors: Gun Ryu, Gi-Mun Um, Won-Sik Cheong, Wonjun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35152v1.pdf)  
  Keywords: gaussian splatting, ar, human  
- **[RecallGS: Geometry-Grounded Recall for Online Semantic Gaussian Splatting](https://arxiv.org/abs/2610.31293v1)**  
  Authors: Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.31293v1.pdf)  
  Keywords: gaussian splatting, segmentation, lightweight, understanding, semantic, ar, head, 3d gaussian, geometry  
- **[H-2DGS: Height-Field Gaussian Splatting for Sharp and Deformable Neurosurgical Surface Reconstruction](https://arxiv.org/abs/2610.30910v1)**  
  Authors: Zhang Zichuan, Bart Brouwers, Rembrandt Bakker, Maud Landers, Geert-Jan Rutten, Maxime Chamberland  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30910v1.pdf)  
  Keywords: gaussian splatting, face, ar, 3d gaussian, compact, geometry  
- **[TerraTransfer++: Demonstration-Free End-to-End Planner](https://arxiv.org/abs/2610.30319v1)**  
  Authors: Zikang Xiong, Weixin Li, Zhouchonghao Wu, Akshay Rangesh, Saarth Bonde, Grantland Hall, Chen Tang, Yihan Hu, Wei Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30319v1.pdf)  
  Keywords: gaussian splatting, lightweight, ar, 3d gaussian, autonomous driving, human  

### Dynamic Scene

*Showing the latest 50 out of 366 papers*

- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation](https://arxiv.org/abs/2610.36312v1)**  
  Authors: Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36312v1.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, outdoor, 3d gaussian, tracking, motion, geometry  
- **[VidEdit3D: Flexible 3D Gaussian Editing with Video Diffusion](https://arxiv.org/abs/2610.35756v1)**  
  Authors: Yanming Yang, Chenxi Song, Tong Zhao, Juntao Xu, Wenhao Rao, Yiwen Chen, Yiwei Wang, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35756v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, semantic, ar, 3d gaussian  
- **[GaussianSpline: Adaptive Bézier Splines for Highly Dynamic 4D Gaussian Splatting](https://arxiv.org/abs/2610.35224v1)**  
  Authors: Tom Yachil, Andrei Sharf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35224v1.pdf)  
  Keywords: gaussian splatting, dynamic, reflection, deformation, high-fidelity, 4d, ar, compact, motion  
- **[DUET4D: Self-Corrective Coupled Guidance for Sparse-View 4D Reconstruction](https://arxiv.org/abs/2610.35002v1)**  
  Authors: Beizhen Zhao, Nanjie Yao, Boyi Fu, Qingsong Yan, Haofan Ren, Kaiyong Zhao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35002v1.pdf)  
  Keywords: gaussian splatting, ar, 4d, sparse-view  
- **[SceneAgent: An Agentic Pipeline from 3D and 4D Captures to Simulation Environments](https://arxiv.org/abs/2610.34745v1)**  
  Authors: Luke Hollis, Tianxing Fan, Heng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34745v1.pdf)  
  Keywords: gaussian splatting, dynamic, segmentation, 4d, ar, 3d gaussian  
- **[R4DGS: Referring Segmentation in 4D Gaussian Splatting](https://arxiv.org/abs/2610.30326v1)**  
  Authors: Bangpu Chen, Yaxuan Li, Shirui Peng, Xiangtian Si, Liuxin Chu, Xitong Cao, Hongbo Jin, Jiayu Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30326v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chenbangpu.github.io/R4DGS/.)  
  Keywords: gaussian splatting, dynamic, segmentation, 4d, semantic, ar  
- **[AutoPhyX: Automatic Text-Condition Physics Property Generation](https://arxiv.org/abs/2610.29517v1)**  
  Authors: Bei Huang, Yixin Chen, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.29517v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 4d, semantic, nerf, ar  
- **[AEON: Unifying Video and 3D World Models](https://arxiv.org/abs/2610.28631v1)**  
  Authors: Weiqi Zhang, Wenyuan Zhang, Yu-Shen Liu, Junsheng Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.28631v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/AEON)  
  Keywords: gaussian splatting, ar, dynamic, 4d  
- **[CrossFit-GS: Out-of-Fold Pose Estimation for COLMAP-Free 3D Gaussian Splatting](https://arxiv.org/abs/2610.28190v1)**  
  Authors: Zijian Wu, Jinliang Wang, Mingfeng Jiang, Zidian Lin, Ying Song, Ziqian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.28190v1.pdf)  
  Keywords: gaussian splatting, motion, ar, 3d gaussian  

### Few-shot

*Showing the latest 50 out of 84 papers*

- **[DUET4D: Self-Corrective Coupled Guidance for Sparse-View 4D Reconstruction](https://arxiv.org/abs/2610.35002v1)**  
  Authors: Beizhen Zhao, Nanjie Yao, Boyi Fu, Qingsong Yan, Haofan Ren, Kaiyong Zhao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35002v1.pdf)  
  Keywords: gaussian splatting, ar, 4d, sparse-view  
- **[Rethinking Sparse-View 3D Gaussian Splatting: A Few-Shot Learning Perspective on Overfitting Prevention](https://arxiv.org/abs/2610.25887v1)**  
  Authors: Lejia Ye, Bin Wu, Jingjing Gao, Yiyang Wu, Xiaohu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25887v1.pdf)  
  Keywords: gaussian splatting, dynamic, vr, ar, 3d gaussian, few-shot, sparse-view, motion, geometry  
- **[Holi-Spatial 360: Generative Reconstruction from Sparse Panoramas for Spatial Rendering and Intelligence](https://arxiv.org/abs/2610.19502v1)**  
  Authors: Yuanyuan Gao, Zhirui Liu, Yuning Gong, Yifei Liu, Yifan Zhan, Kuixuan Jiao, Xiaolong Zhou, Yifan Yang, Hongjie Zhang, Xue Yang, Dan Xu, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.19502v1.pdf)  
  Keywords: gaussian splatting, understanding, sparse view, semantic, ar, 3d gaussian  
- **[Gaussian Splatting for Real-Time Scene Reconstruction: Methods, Systems, and Trade-offs](https://arxiv.org/abs/2610.17513v1)**  
  Authors: Ashim Dahal, Rabab Abdelfattah, Nick Rahimi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.17513v1.pdf)  
  Keywords: gaussian splatting, survey, slam, dynamic, real-time rendering, compression, localization, mapping, ar, 3d gaussian, tracking, sparse-view  
- **[AD-GS: Anatomical Density-guided 3D Gaussian Splatting for Sparse-View Dental CBCT Reconstruction](https://arxiv.org/abs/2610.14963v1)**  
  Authors: Zonglin Li, Kexian Xie, Feiran Li, Chu Zhou, Yixing Huang, Ruiyang Chen, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.14963v1.pdf)  
  Keywords: gaussian splatting, medical, semantic, ar, 3d gaussian, sparse-view  
- **[CompactSplat: Spatially Adaptive Gaussian Distribution for Feedforward Scene Reconstruction](https://arxiv.org/abs/2610.13177v1)**  
  Authors: Bing He, Jingnan Gao, Yunuo Chen, Zhengxue Cheng, Rong Xie, Li Song, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.13177v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, sparse view, high-fidelity, ar, 3d gaussian, compact, geometry  
- **[OX-NeRF: 3D X-ray Tomography Reconstruction from Sparse Views Using Implicit Neural Representation](https://arxiv.org/abs/2610.11547v1)**  
  Authors: Thomas Welsch, Min-Hsin Tu, David J. Chapman, Daniel E. Eakins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.11547v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, sparse view, nerf, ar  
- **[DensiTok: Making Feed-Forward 3D Gaussian Splatting See More Views Than It Is Given](https://arxiv.org/abs/2610.07958v1)**  
  Authors: Minhyeok Lee, Jungho Lee, Minseok Kang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.07958v1.pdf)  
  Keywords: gaussian splatting, ar, head, 3d gaussian, compact, sparse-view, geometry  
- **[Sparse-View 4D Gaussian Splatting via Spatiotemporal Priors and Generative Assistance](https://arxiv.org/abs/2610.04606v2)**  
  Authors: Shengqi Wang, Zhengxian Yang, Kaiwen Tian, Yang Liu, Bowen Liu, Hua Du, Taicheng Huang, Jiamin Wu, Tao Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04606v2.pdf)  
  Keywords: gaussian splatting, dynamic, sparse view, 4d, ar, sparse-view, motion, geometry  
- **[Sparse-GS2Mesh: 3D Gaussian Splatting Guided by Novel Stereo Views and 2DGS for Sparse View Surface Reconstruction](https://arxiv.org/abs/2610.04203v3)**  
  Authors: Younghyun Noh, Minje Kim, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.04203v3.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yhnoh8623.github.io/projects/s-gs2mesh/.)  
  Keywords: gaussian splatting, face, sparse view, efficient, ar, 3d gaussian, sparse-view, geometry  

### Geometry Reconstruction

*Showing the latest 50 out of 410 papers*

- **[DomeGS: Perceptually Consistent Background Completion for Unbounded 3D Gaussian Splatting in Virtual Reality](https://arxiv.org/abs/2610.37172v1)**  
  Authors: Anastasiya Pechko, Agata Szymańska, Piotr Borycki, Joanna Szelewska, Michał Mnich, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37172v1.pdf)  
  Keywords: gaussian splatting, vr, high-fidelity, ar, outdoor, 3d gaussian, geometry  
- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[GeoGSplat: Geometry-Grounded Non-Pixel-Aligned Gaussian Splatting](https://arxiv.org/abs/2610.36760v1)**  
  Authors: Jiale Wang, Chen Zhao, Haoyang Zhang, Yanhao Wu, Fei He, Yanhu Shan, Rui Wu, Wei Ke, Tong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://comedy0913.github.io/projects/geogsplat)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation](https://arxiv.org/abs/2610.36312v1)**  
  Authors: Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36312v1.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, outdoor, 3d gaussian, tracking, motion, geometry  
- **[PrinGS: Privacy Preservation in Gaussian Splatting](https://arxiv.org/abs/2610.36168v1)**  
  Authors: Gaurav Behera, Abhinav Raundhal, Archisha Panda, Saumya Balina, Gargi Shroff, Ponnurangam Kumaraguru  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36168v1.pdf)  
  Keywords: gaussian splatting, face, high-fidelity, ar, 3d gaussian, geometry, human  
- **[SG-Splat: Stable Geometry Learning under Pose Uncertainty for Pose-Free 3D Gaussian Splatting](https://arxiv.org/abs/2610.35361v1)**  
  Authors: Xiaohan Lu, Jiaqi Zhang, Weijia Jiang, Siwei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35361v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[RIDE-Splat: Reflection Removal for In-the-Wild Driving Environments](https://arxiv.org/abs/2610.34632v1)**  
  Authors: Kevin David Hayes, Alex Hanson, Allen Tu, Pranav Asthana, Matthias Zwicker, Tom Goldstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34632v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, reflection, ar, 3d gaussian, geometry  
- **[LegoOcc++: Towards Consistent Open-Vocabulary 3D Occupancy Prediction](https://arxiv.org/abs/2610.34093v1)**  
  Authors: Changqing Zhou, Yueru Luo, Han Zhang, Zeyu Jiang, Changhao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34093v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, outdoor, geometry  
- **[RecallGS: Geometry-Grounded Recall for Online Semantic Gaussian Splatting](https://arxiv.org/abs/2610.31293v1)**  
  Authors: Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.31293v1.pdf)  
  Keywords: gaussian splatting, segmentation, lightweight, understanding, semantic, ar, head, 3d gaussian, geometry  
- **[H-2DGS: Height-Field Gaussian Splatting for Sharp and Deformable Neurosurgical Surface Reconstruction](https://arxiv.org/abs/2610.30910v1)**  
  Authors: Zhang Zichuan, Bart Brouwers, Rembrandt Bakker, Maud Landers, Geert-Jan Rutten, Maxime Chamberland  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30910v1.pdf)  
  Keywords: gaussian splatting, face, ar, 3d gaussian, compact, geometry  

### Large Scene

- **[DomeGS: Perceptually Consistent Background Completion for Unbounded 3D Gaussian Splatting in Virtual Reality](https://arxiv.org/abs/2610.37172v1)**  
  Authors: Anastasiya Pechko, Agata Szymańska, Piotr Borycki, Joanna Szelewska, Michał Mnich, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37172v1.pdf)  
  Keywords: gaussian splatting, vr, high-fidelity, ar, outdoor, 3d gaussian, geometry  
- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation](https://arxiv.org/abs/2610.36312v1)**  
  Authors: Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36312v1.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, outdoor, 3d gaussian, tracking, motion, geometry  
- **[BoundedGS: Memory-Efficient High-Resolution Training for 3D Gaussian Splatting](https://arxiv.org/abs/2610.34233v1)**  
  Authors: Xiaobin Deng, Changyu Diao, Min Li, Duanqing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34233v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobin2001.github.io/BoundedGS-Web/)  
  Keywords: gaussian splatting, ar, outdoor, 3d gaussian, compact, efficient  
- **[LegoOcc++: Towards Consistent Open-Vocabulary 3D Occupancy Prediction](https://arxiv.org/abs/2610.34093v1)**  
  Authors: Changqing Zhou, Yueru Luo, Han Zhang, Zeyu Jiang, Changhao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34093v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, outdoor, geometry  
- **[AirPlayground: Benchmarking Aerial Navigation across Diverse Reconstructed Environments](https://arxiv.org/abs/2610.29699v1)**  
  Authors: Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Mingsheng Li, Qingsong Yan, Chao Yan, Yuhang Zhang, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.29699v1.pdf)  
  Keywords: gaussian splatting, ar, outdoor, 3d gaussian, geometry  
- **[Counting Contributions, Not Views: Occlusion-Aware Densification for 3D Gaussian Splatting](https://arxiv.org/abs/2610.27108v1)**  
  Authors: Marcel Rogge, René Schuster, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.27108v1.pdf)  
  Keywords: gaussian splatting, ar, 3d gaussian, large scene, geometry  
- **[HyperLoop: Hyperspectral-Assisted Loop Closure Detection in 3D-SLAM for Planetary Exploration](https://arxiv.org/abs/2610.19742v1)**  
  Authors: Annie Bhalla, Dennis Rotondi, Riccardo Giubilato, Kai O. Arras, Wolfgang Stuerzl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.19742v1.pdf)  
  Keywords: gaussian splatting, slam, illumination, mapping, ar, outdoor, 3d gaussian  
- **[3D Gaussian Splatting for Fine-grained Urban Scene Reconstruction via Semantic-guided Density Control and Loss Design](https://arxiv.org/abs/2610.16292v1)**  
  Authors: Yueling Liao, San Jiang, Xing Zhang, Zhongwen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.16292v1.pdf)  
  Keywords: gaussian splatting, dynamic, 3d reconstruction, segmentation, high-fidelity, semantic, ar, 3d gaussian, urban scene  
- **[Federated 3D Gaussian Splatting for Large-Scale Scene Reconstruction at Wireless Edge](https://arxiv.org/abs/2609.32177v1)**  
  Authors: Guanlin Wu, Chao Hu, Pu Chen, Juyong Zhang, Han Hu, Shuguang Cui, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.32177v1.pdf)  
  Keywords: gaussian splatting, face, lightweight, ar, 3d gaussian, large scene, efficient  

### Model Compression

*Showing the latest 50 out of 391 papers*

- **[GeoGSplat: Geometry-Grounded Non-Pixel-Aligned Gaussian Splatting](https://arxiv.org/abs/2610.36760v1)**  
  Authors: Jiale Wang, Chen Zhao, Haoyang Zhang, Yanhao Wu, Fei He, Yanhu Shan, Rui Wu, Wei Ke, Tong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36760v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://comedy0913.github.io/projects/geogsplat)  
  Keywords: gaussian splatting, 3d reconstruction, geometry, ar, efficient  
- **[ClusterSplat: Semantic Cluster Selection for 3D Visual Grounding in Gaussian Splatting](https://arxiv.org/abs/2610.36462v1)**  
  Authors: Jaesung Lee, Hyeontaek Hwang, Gabriel Manalu, Daeyoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36462v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jaesung8.github.io/clustersplat/)  
  Keywords: gaussian splatting, segmentation, lightweight, semantic, ar, 3d gaussian  
- **[Robot-Aligned 3D Gaussian Splatting for Precise Reaching with Wrist-Camera VLA Policies](https://arxiv.org/abs/2610.35626v1)**  
  Authors: Zuoxu Wang, Xiao Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35626v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://001-wang.github.io/PrecisionReach-GS/)  
  Keywords: gaussian splatting, ar, 3d gaussian, efficient, human  
- **[CVTSplat: Multi-view Reconstruction Using an Adaptive Centroidal Voronoi Tessellation](https://arxiv.org/abs/2610.35347v1)**  
  Authors: Briac Toussaint, Diego Thomas, Jean-Sébastien Franco, Edmond Boyer, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35347v1.pdf)  
  Keywords: face, ar, efficient, fast  
- **[GaussianSpline: Adaptive Bézier Splines for Highly Dynamic 4D Gaussian Splatting](https://arxiv.org/abs/2610.35224v1)**  
  Authors: Tom Yachil, Andrei Sharf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35224v1.pdf)  
  Keywords: gaussian splatting, dynamic, reflection, deformation, high-fidelity, 4d, ar, compact, motion  
- **[RacerGS: Residual-Autoregressive Context for 3D Gaussian Splatting Compression](https://arxiv.org/abs/2610.34263v1)**  
  Authors: Wenqing Wang, Huimin Zeng, Yun Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34263v1.pdf)  
  Keywords: gaussian splatting, compression, ar, 3d gaussian, compact, fast  
- **[ParetoGS: High-Quality Continuous-Budget 3D Gaussian Splatting with Sparse Adapted Anchors](https://arxiv.org/abs/2610.34235v1)**  
  Authors: Xiaobin Deng, Changyu Diao, Min Li, Duanqing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34235v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobin2001.github.io/ParetoGS-Web/)  
  Keywords: gaussian splatting, ar, 3d gaussian, compact  
- **[BoundedGS: Memory-Efficient High-Resolution Training for 3D Gaussian Splatting](https://arxiv.org/abs/2610.34233v1)**  
  Authors: Xiaobin Deng, Changyu Diao, Min Li, Duanqing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34233v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaobin2001.github.io/BoundedGS-Web/)  
  Keywords: gaussian splatting, ar, outdoor, 3d gaussian, compact, efficient  
- **[RecallGS: Geometry-Grounded Recall for Online Semantic Gaussian Splatting](https://arxiv.org/abs/2610.31293v1)**  
  Authors: Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.31293v1.pdf)  
  Keywords: gaussian splatting, segmentation, lightweight, understanding, semantic, ar, head, 3d gaussian, geometry  
- **[H-2DGS: Height-Field Gaussian Splatting for Sharp and Deformable Neurosurgical Surface Reconstruction](https://arxiv.org/abs/2610.30910v1)**  
  Authors: Zhang Zichuan, Bart Brouwers, Rembrandt Bakker, Maud Landers, Geert-Jan Rutten, Maxime Chamberland  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30910v1.pdf)  
  Keywords: gaussian splatting, face, ar, 3d gaussian, compact, geometry  

### Quality Enhancement

*Showing the latest 50 out of 196 papers*

- **[DomeGS: Perceptually Consistent Background Completion for Unbounded 3D Gaussian Splatting in Virtual Reality](https://arxiv.org/abs/2610.37172v1)**  
  Authors: Anastasiya Pechko, Agata Szymańska, Piotr Borycki, Joanna Szelewska, Michał Mnich, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37172v1.pdf)  
  Keywords: gaussian splatting, vr, high-fidelity, ar, outdoor, 3d gaussian, geometry  
- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[PrinGS: Privacy Preservation in Gaussian Splatting](https://arxiv.org/abs/2610.36168v1)**  
  Authors: Gaurav Behera, Abhinav Raundhal, Archisha Panda, Saumya Balina, Gargi Shroff, Ponnurangam Kumaraguru  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36168v1.pdf)  
  Keywords: gaussian splatting, face, high-fidelity, ar, 3d gaussian, geometry, human  
- **[GaussianSpline: Adaptive Bézier Splines for Highly Dynamic 4D Gaussian Splatting](https://arxiv.org/abs/2610.35224v1)**  
  Authors: Tom Yachil, Andrei Sharf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35224v1.pdf)  
  Keywords: gaussian splatting, dynamic, reflection, deformation, high-fidelity, 4d, ar, compact, motion  
- **[AutoPhyX: Automatic Text-Condition Physics Property Generation](https://arxiv.org/abs/2610.29517v1)**  
  Authors: Bei Huang, Yixin Chen, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.29517v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 4d, semantic, nerf, ar  
- **[GOFusion: Real-Time Gaussian-Occupancy Submap Fusion for Fisher-Informed Autonomous Robot Navigation](https://arxiv.org/abs/2610.25261v1)**  
  Authors: Boxin Bu, Simon Boche, Haoming Zhang, Jaehyung Jung, Jiaxin Wei, Hannah Schieber, Daniel Roth, Angela P. Schoellig, Stefan Leutenegger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25261v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://youtu.be/pLQKbxQvb6I.)  
  Keywords: gaussian splatting, slam, mapping, high-fidelity, ar, 3d gaussian  
- **[SwitchSplat: Learning Discrete Object States from Casually Captured Scenes](https://arxiv.org/abs/2610.24812v2)**  
  Authors: Yizheng Xie, Yalda Foroutan, George Shramko, Daniel Rebain, Shrisudhan Govindarajan, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.24812v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://switchsplat.github.io)  
  Keywords: gaussian splatting, 3d reconstruction, dynamic, high-fidelity, 4d, ar, 3d gaussian, fast, geometry  
- **[3D Gaussian Splatting for Fine-grained Urban Scene Reconstruction via Semantic-guided Density Control and Loss Design](https://arxiv.org/abs/2610.16292v1)**  
  Authors: Yueling Liao, San Jiang, Xing Zhang, Zhongwen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.16292v1.pdf)  
  Keywords: gaussian splatting, dynamic, 3d reconstruction, segmentation, high-fidelity, semantic, ar, 3d gaussian, urban scene  
- **[Demiurge: Forging Navigable 4D Worlds via Autoregressive Video Rerendering](https://arxiv.org/abs/2610.14685v1)**  
  Authors: Hanxin Zhu, Jianqi Ma, Cong Wang, Zhihao Hu, Junyao Gao, Tianyu He, Junyan Lin, Jiayin Xiao, Jiateng Shou, Sen Liang, Weidong Zhang, Zhibo Chen, Jun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.14685v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanxinzhu-lab.github.io/demiurge_project_page/.)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 4d, ar, 3d gaussian, motion, geometry  
- **[TETRIS-4DGS: Efficient Post-Training Compression of 4D Gaussian Splatting](https://arxiv.org/abs/2610.14663v1)**  
  Authors: Chengzhen Wu, Kelei Liu, Sicheng Li, Lu Yu, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.14663v1.pdf)  
  Keywords: gaussian splatting, dynamic, compression, high quality, 4d, ar, head, motion, efficient  

### Ray Tracing

- **[GraftRay: Physically Based Mesh Insertion into Gaussian Splatting Scenes via Path Tracing](https://arxiv.org/abs/2610.37036v1)**  
  Authors: Jinxin Ai, Matthias Niessner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37036v1.pdf)  
  Keywords: gaussian splatting, face, reflection, illumination, shadow, ar, 3d gaussian, lighting, path tracing  
- **[Spatial MIMO Channel Rendering: A 3D Gaussian Splatting Approach](https://arxiv.org/abs/2610.36880v1)**  
  Authors: Juntaek Han, Geonha Kim, Chaozheng Wen, Ahmed Alkhateeb, Jun Zhang, Jeonghun Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36880v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, head, 3d gaussian, fast  
- **[A Hybrid and Hierarchical Ray Tracing Method for Efficient 3D Gaussian Rendering](https://arxiv.org/abs/2610.13498v1)**  
  Authors: Tiancheng Zhao, Sixu Li, Yuzhou Chen, Hengyu Ding, Zhiming Pan, Chaojian Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.13498v1.pdf)  
  Keywords: gaussian splatting, ray tracing, ar, head, 3d gaussian, lighting, efficient  
- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: gaussian splatting, face, ray tracing, real-time rendering, nerf, ar, 3d gaussian, fast, compact, motion  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: gaussian splatting, ray tracing, reflection, mapping, shadow, nerf, ar, 3d gaussian, fast, compact, efficient  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: gaussian splatting, face, ray tracing, reflection, illumination, relighting, ar, lighting, efficient  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: gaussian splatting, face, ray tracing, dynamic, reflection, high-fidelity, ar, 3d gaussian, motion, geometry, human  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: gaussian splatting, ray tracing, ar, 3d gaussian, fast  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: gaussian splatting, ray tracing, real-time rendering, reflection, efficient, ar, 3d gaussian, fast, geometry, path tracing  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, illumination, global illumination, efficient, ar, 3d gaussian, geometry  

### Relighting

*Showing the latest 50 out of 111 papers*

- **[CTBakeGS: training-free baking of photorealistic CT volume renderings into 3D Gaussian splats](https://arxiv.org/abs/2610.37406v1)**  
  Authors: Haruki Fukuda, Constantin Lux, Wolf Schweitzer, Tadashi Hosoya, Lars Ebert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37406v1.pdf)  
  Keywords: gaussian splatting, medical, ar, 3d gaussian, lighting  
- **[GraftRay: Physically Based Mesh Insertion into Gaussian Splatting Scenes via Path Tracing](https://arxiv.org/abs/2610.37036v1)**  
  Authors: Jinxin Ai, Matthias Niessner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.37036v1.pdf)  
  Keywords: gaussian splatting, face, reflection, illumination, shadow, ar, 3d gaussian, lighting, path tracing  
- **[GaussianSpline: Adaptive Bézier Splines for Highly Dynamic 4D Gaussian Splatting](https://arxiv.org/abs/2610.35224v1)**  
  Authors: Tom Yachil, Andrei Sharf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35224v1.pdf)  
  Keywords: gaussian splatting, dynamic, reflection, deformation, high-fidelity, 4d, ar, compact, motion  
- **[RIDE-Splat: Reflection Removal for In-the-Wild Driving Environments](https://arxiv.org/abs/2610.34632v1)**  
  Authors: Kevin David Hayes, Alex Hanson, Allen Tu, Pranav Asthana, Matthias Zwicker, Tom Goldstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34632v1.pdf)  
  Keywords: gaussian splatting, 3d reconstruction, reflection, ar, 3d gaussian, geometry  
- **[SplatXR: A Toolkit for Multi-Layered Extended Reality via On-Headset 3D Gaussian Splatting](https://arxiv.org/abs/2610.26338v1)**  
  Authors: Cyrus Vachha, Mohamed Kari, Parastoo Abtahi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.26338v1.pdf)  
  Keywords: gaussian splatting, face, shadow, ar, head, 3d gaussian, geometry  
- **[RxGS: Relightable Gaussian Stylization via BRDF Decomposition](https://arxiv.org/abs/2610.25681v1)**  
  Authors: Wanrong Hong, Liu Jiang, Mukesh Prasad, Jun Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25681v1.pdf)  
  Keywords: gaussian splatting, face, illumination, relightable, nerf, ar, 3d gaussian, lighting, geometry  
- **[MCSplat: Multi-View Photometric and Geometric Consistent Feed-Forward Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2610.25345v1)**  
  Authors: Yifei Wang, Wei Tian, Wenhua Bao, Jia Zhou, Hanshi Wang, Fudong Ge, Jianhua Wu, Shuai Yuan, Zhipeng Zhang, Xingliang Liu, Xianming Zeng, Jianyun Xu, Bingzhao Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25345v1.pdf)  
  Keywords: gaussian splatting, face, illumination, ar, geometry  
- **[Directionally Factorized Illumination with Spherical Harmonic Rotation](https://arxiv.org/abs/2610.24811v1)**  
  Authors: Yimeng Dou, Adam M. Saunders, Andre T. S. Hucke, Michael E. Kim, Adam W. Anderson, Eric R. Tkaczyk, Bennett A. Landman, Daniel Moyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.24811v1.pdf)  
  Keywords: gaussian splatting, face, illumination, medical, nerf, ar, lighting, neural rendering, geometry  
- **[Where Should the Gaussians Go? Reusable Label-Aware Allocation for Budget-Constrained Gaussian Splatting of Cinematic CT](https://arxiv.org/abs/2610.20397v1)**  
  Authors: Bowen Xiang, Dingjie Su, Jon S. Heiselman, Michael I. Miga  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.20397v1.pdf)  
  Keywords: gaussian splatting, lighting, ar, 3d gaussian  
- **[VisibilitySplat: Ray-Traced Occlusion for Relighting with 3D Gaussian Splatting](https://arxiv.org/abs/2610.19847v1)**  
  Authors: Sven Kluge, Oliver Staadt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.19847v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, illumination, relighting, nerf, ar, 3d gaussian, lighting  

### SLAM

*Showing the latest 50 out of 155 papers*

- **[LingGS: Decoupling Feed-Forward Geometry Prediction from Camera Tracking for High-Fidelity Gaussian SLAM](https://arxiv.org/abs/2610.36853v1)**  
  Authors: Da Li, Yihan Zang, Ivan Viola, Zeyu Wang, Dominik Engel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36853v1.pdf)  
  Keywords: gaussian splatting, slam, high-fidelity, ar, outdoor, tracking, motion, geometry  
- **[SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation](https://arxiv.org/abs/2610.36312v1)**  
  Authors: Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36312v1.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, outdoor, 3d gaussian, tracking, motion, geometry  
- **[ClunoGS: Compact Language 3D Gaussian Splatting via Unified Optimization](https://arxiv.org/abs/2610.30013v1)**  
  Authors: Jian Xu, Yi Li, Ying Huang, Siyi Wu, Bingzhe Li, Yuede Ji, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30013v1.pdf)  
  Keywords: gaussian splatting, localization, segmentation, compression, understanding, semantic, ar, 3d gaussian, compact  
- **[GOFusion: Real-Time Gaussian-Occupancy Submap Fusion for Fisher-Informed Autonomous Robot Navigation](https://arxiv.org/abs/2610.25261v1)**  
  Authors: Boxin Bu, Simon Boche, Haoming Zhang, Jaehyung Jung, Jiaxin Wei, Hannah Schieber, Daniel Roth, Angela P. Schoellig, Stefan Leutenegger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25261v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://youtu.be/pLQKbxQvb6I.)  
  Keywords: gaussian splatting, slam, mapping, high-fidelity, ar, 3d gaussian  
- **[Localization and Neural Splatting on the Edge: An FPGA Scene Memory for Robots](https://arxiv.org/abs/2610.25068v2)**  
  Authors: Haohua Que, Mingkai Liu, Tianle Zhu, Handong Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.25068v2.pdf)  
  Keywords: gaussian splatting, localization, acceleration, ar, 3d gaussian, fast  
- **[RoMo-GS: Efficient Online 3D Gaussian Splatting for Robot Mapping via Exposure-Integrated Motion Blur](https://arxiv.org/abs/2610.24605v1)**  
  Authors: Sangwoo Jung, Di Deng, Jiahui Fu, Laura Herlant, Ayoung Kim, Yafei Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.24605v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, ar, 3d gaussian, fast, motion, geometry, robotics  
- **[KFS$^4$LAM: Adaptive KeyFrame Selection with Structure-Aware Mapping for Endoscopic Gaussian Splatting SLAM](https://arxiv.org/abs/2610.22505v1)**  
  Authors: Xinwei Ju, Zhehua Mao, Tianyi Song, Danail Stoyanov, Sophia Bano, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.22505v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xinweiju.github.io/KFSLAM/.)  
  Keywords: gaussian splatting, slam, dynamic, localization, deformation, mapping, ar, motion  
- **[Compression of Uniformly Distributed Unit Quaternions](https://arxiv.org/abs/2610.22052v1)**  
  Authors: Carsten Faber, Bastian Kuth, Rinaldo Schuster, Daniel Pauls, Quirin Meyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.22052v1.pdf)  
  Keywords: gaussian splatting, animation, compression, mapping, ar, efficient  
- **[Training-Free Target-Aware Refinement of 3D Gaussian Language Map](https://arxiv.org/abs/2610.21619v1)**  
  Authors: Sibaek Lee, Kyeongsu Kang, Seongbo Ha, Yewon Jeon, Joonyeol Choi, Daegeol Ko, Jaehyuk Hur, Taemin Choi, Minsu Kim, Hyungjoo Ahn, Wonsok Yoo, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.21619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lab-of-ai-and-robotics.github.io/target-aware-langmap/)  
  Keywords: gaussian splatting, localization, segmentation, ar, 3d gaussian, efficient, robotics  
- **[HyperLoop: Hyperspectral-Assisted Loop Closure Detection in 3D-SLAM for Planetary Exploration](https://arxiv.org/abs/2610.19742v1)**  
  Authors: Annie Bhalla, Dennis Rotondi, Riccardo Giubilato, Kai O. Arras, Wolfgang Stuerzl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.19742v1.pdf)  
  Keywords: gaussian splatting, slam, illumination, mapping, ar, outdoor, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 201 papers*

- **[ClusterSplat: Semantic Cluster Selection for 3D Visual Grounding in Gaussian Splatting](https://arxiv.org/abs/2610.36462v1)**  
  Authors: Jaesung Lee, Hyeontaek Hwang, Gabriel Manalu, Daeyoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.36462v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jaesung8.github.io/clustersplat/)  
  Keywords: gaussian splatting, segmentation, lightweight, semantic, ar, 3d gaussian  
- **[VidEdit3D: Flexible 3D Gaussian Editing with Video Diffusion](https://arxiv.org/abs/2610.35756v1)**  
  Authors: Yanming Yang, Chenxi Song, Tong Zhao, Juntao Xu, Wenhao Rao, Yiwen Chen, Yiwei Wang, Chi Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.35756v1.pdf)  
  Keywords: gaussian splatting, face, dynamic, semantic, ar, 3d gaussian  
- **[SceneAgent: An Agentic Pipeline from 3D and 4D Captures to Simulation Environments](https://arxiv.org/abs/2610.34745v1)**  
  Authors: Luke Hollis, Tianxing Fan, Heng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34745v1.pdf)  
  Keywords: gaussian splatting, dynamic, segmentation, 4d, ar, 3d gaussian  
- **[LegoOcc++: Towards Consistent Open-Vocabulary 3D Occupancy Prediction](https://arxiv.org/abs/2610.34093v1)**  
  Authors: Changqing Zhou, Yueru Luo, Han Zhang, Zeyu Jiang, Changhao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.34093v1.pdf)  
  Keywords: gaussian splatting, semantic, ar, outdoor, geometry  
- **[RelateGS: Reliable Semantic and Relational Evidence for 3D Scene Understanding with Gaussian Splatting](https://arxiv.org/abs/2610.33868v1)**  
  Authors: Seongjun Choi, Sangyoun Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.33868v1.pdf)  
  Keywords: gaussian splatting, understanding, semantic, ar, 3d gaussian  
- **[RecallGS: Geometry-Grounded Recall for Online Semantic Gaussian Splatting](https://arxiv.org/abs/2610.31293v1)**  
  Authors: Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.31293v1.pdf)  
  Keywords: gaussian splatting, segmentation, lightweight, understanding, semantic, ar, head, 3d gaussian, geometry  
- **[R4DGS: Referring Segmentation in 4D Gaussian Splatting](https://arxiv.org/abs/2610.30326v1)**  
  Authors: Bangpu Chen, Yaxuan Li, Shirui Peng, Xiangtian Si, Liuxin Chu, Xitong Cao, Hongbo Jin, Jiayu Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30326v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chenbangpu.github.io/R4DGS/.)  
  Keywords: gaussian splatting, dynamic, segmentation, 4d, semantic, ar  
- **[ClunoGS: Compact Language 3D Gaussian Splatting via Unified Optimization](https://arxiv.org/abs/2610.30013v1)**  
  Authors: Jian Xu, Yi Li, Ying Huang, Siyi Wu, Bingzhe Li, Yuede Ji, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.30013v1.pdf)  
  Keywords: gaussian splatting, localization, segmentation, compression, understanding, semantic, ar, 3d gaussian, compact  
- **[AutoPhyX: Automatic Text-Condition Physics Property Generation](https://arxiv.org/abs/2610.29517v1)**  
  Authors: Bei Huang, Yixin Chen, Hongbin Zha, Yuru Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.29517v1.pdf)  
  Keywords: gaussian splatting, dynamic, high-fidelity, 4d, semantic, nerf, ar  
- **[Real2Sem2Real: 3D Semantic Augmentations for Robot Learning from a Single Human RGB Demonstration](https://arxiv.org/abs/2610.28880v1)**  
  Authors: Matthew Strong, Ankush K. Dhawan, Julien Poffet, Giuse Pham, Jinho So, Monroe Kennedy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2610.28880v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://real2sem2real.github.io/.)  
  Keywords: ar, human, semantic  



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