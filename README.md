# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-11-02 00:58:43

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

- [3DGS Surveys](#3dgs-surveys) (24 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (258 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (339 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (396 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (71 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (325 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (77 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (404 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (176 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (16 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (118 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (147 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (208 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, motion, nerf, fast, gaussian splatting, survey, ar, geometry, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, real-time rendering, 3d reconstruction, gaussian splatting, efficient, survey, efficient rendering, lighting, animation, ar, face, 3d gaussian  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: nerf, human, understanding, gaussian splatting, efficient, survey, ar, lightweight  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: nerf, fast, understanding, gaussian splatting, efficient, survey, neural rendering, ar, 3d gaussian, slam  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: nerf, understanding, segmentation, gaussian splatting, survey, lighting, semantic, compact, ar, high-fidelity, 3d gaussian  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: nerf, understanding, gaussian splatting, efficient, survey, robotics, semantic, ar, 3d gaussian  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: nerf, human, gaussian splatting, robotics, survey, ar, 3d gaussian  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: sparse-view, motion, nerf, 3d reconstruction, gaussian splatting, robotics, survey, vr, ar, geometry, 3d gaussian  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v3)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Kaichen Zhou, Paul Pu Liang, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v3.pdf)  
  Keywords: nerf, dynamic, fast, human, 3d reconstruction, gaussian splatting, robotics, survey, lighting, vr, ar, 3d gaussian, slam  

### Acceleration

*Showing the latest 50 out of 258 papers*

- **[Explicit Memory through Online 3D Gaussian Splatting Improves
  Class-Agnostic Video Segmentation](https://arxiv.org/abs/2510.23521v1)**  
  Authors: Anthony Opipari, Aravindhan K Krishnan, Shreekant Gayaka, Min Sun, Cheng-Hao Kuo, Arnie Sen, Odest Chadwicke Jenkins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23521v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://topipari.com/projects/FastSAM-Splat/)  
  Keywords: fast, segmentation, gaussian splatting, ar, 3d gaussian  
- **[DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum](https://arxiv.org/abs/2510.22213v1)**  
  Authors: Yaokun Li, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22213v1.pdf)  
  Keywords: 4d, motion, dynamic, fast, semantic, gaussian splatting, animation, compact, face, ar, 3d gaussian  
- **[Towards Physically Executable 3D Gaussian for Embodied Navigation](https://arxiv.org/abs/2510.21307v1)**  
  Authors: Bingchen Miao, Rong Wei, Zhiqi Ge, Xiaoquan sun, Shiqi Gao, Jingzhe Zhu, Renhan Wang, Siliang Tang, Jun Xiao, Rui Tang, Juncheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.21307v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, semantic, ar, face, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, motion, nerf, fast, gaussian splatting, survey, ar, geometry, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, real-time rendering, 3d reconstruction, gaussian splatting, efficient, survey, efficient rendering, lighting, animation, ar, face, 3d gaussian  
- **[HGC-Avatar: Hierarchical Gaussian Compression for Streamable Dynamic 3D
  Avatars](https://arxiv.org/abs/2510.16463v1)**  
  Authors: Haocheng Tang, Ruoke Yan, Xinhui Yin, Qi Zhang, Xinfeng Zhang, Siwei Ma, Wen Gao, Chuanmin Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.16463v1.pdf)  
  Keywords: compression, avatar, motion, dynamic, fast, human, gaussian splatting, efficient, semantic, compact, ar, 3d gaussian  
- **[Proactive Scene Decomposition and Reconstruction](https://arxiv.org/abs/2510.16272v1)**  
  Authors: Baicheng Li, Zike Yan, Dong Wu, Hongbin Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.16272v1.pdf)  
  Keywords: dynamic, human, gaussian splatting, efficient, efficient rendering, ar  
- **[Phys2Real: Fusing VLM Priors with Interactive Online Adaptation for
  Uncertainty-Aware Sim-to-Real Manipulation](https://arxiv.org/abs/2510.11689v1)**  
  Authors: Maggie Wang, Stephen Tian, Aiden Swann, Ola Shorinwa, Jiajun Wu, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11689v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://phys2real.github.io/)  
  Keywords: dynamic, fast, gaussian splatting, ar, high-fidelity, 3d gaussian  
- **[P-4DGS: Predictive 4D Gaussian Splatting with 90$\times$ Compression](https://arxiv.org/abs/2510.10030v1)**  
  Authors: Henan Wang, Hanxin Zhu, Xinliang Gong, Tianyu He, Xin Li, Zhibo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.10030v1.pdf)  
  Keywords: compression, 4d, real-time rendering, dynamic, fast, gaussian splatting, compact, ar, 3d gaussian  
- **[LTGS: Long-Term Gaussian Scene Chronology From Sparse View Updates](https://arxiv.org/abs/2510.09881v1)**  
  Authors: Minkwan Kim, Seungmin Lee, Junho Kim, Young Min Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09881v1.pdf)  
  Keywords: sparse-view, fast, gaussian splatting, efficient, few-shot, ar, face, sparse view  

### Applications

*Showing the latest 50 out of 995 papers*

- **[HEIR: Learning Graph-Based Motion Hierarchies](https://arxiv.org/abs/2510.26786v1)**  
  Authors: Cheng Zheng, William Koch, Baiang Li, Felix Heide  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26786v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://light.princeton.edu/HEIR/)  
  Keywords: motion, dynamic, gaussian splatting, robotics, ar, deformation, 3d gaussian  
- **[The Impact and Outlook of 3D Gaussian Splatting](https://arxiv.org/abs/2510.26694v1)**  
  Authors: Bernhard Kerbl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26694v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, efficient, body, ar, 3d gaussian  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[6D Channel Knowledge Map Construction via Bidirectional Wireless
  Gaussian Splatting](https://arxiv.org/abs/2510.26166v1)**  
  Authors: Juncong Zhou, Chao Hu, Guanlin Wu, Zixiang Ren, Han Hu, Juyong Zhang, Rui Zhang, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26166v1.pdf)  
  Keywords: ar, gaussian splatting, dynamic  
- **[$D^2GS$: Dense Depth Regularization for LiDAR-free Urban Scene
  Reconstruction](https://arxiv.org/abs/2510.25173v1)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, urban scene, ar, geometry  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit
  Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[NVSim: Novel View Synthesis Simulator for Large Scale Indoor Navigation](https://arxiv.org/abs/2510.24335v1)**  
  Authors: Mingyu Jeong, Eunsung Kim, Sehun Park, Andrew Jaeyong Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.24335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://youtu.be/tTiIQt6nXC8)  
  Keywords: ar, gaussian splatting, 3d gaussian  
- **[LagMemo: Language 3D Gaussian Splatting Memory for Multi-modal
  Open-vocabulary Multi-goal Visual Navigation](https://arxiv.org/abs/2510.24118v1)**  
  Authors: Haotian Zhou, Xiaole Wang, He Li, Fusheng Sun, Shengyu Guo, Guolei Qi, Jianghuan Xu, Huijing Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.24118v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weekgoodday.github.io/lagmemo)  
  Keywords: dynamic, gaussian splatting, ar, 3d gaussian, localization  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 339 papers*

- **[The Impact and Outlook of 3D Gaussian Splatting](https://arxiv.org/abs/2510.26694v1)**  
  Authors: Bernhard Kerbl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26694v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, efficient, body, ar, 3d gaussian  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit
  Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  
- **[Gen-LangSplat: Generalized Language Gaussian Splatting with Pre-Trained
  Feature Compression](https://arxiv.org/abs/2510.22930v1)**  
  Authors: Pranav Saxena  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22930v1.pdf)  
  Keywords: compression, human, gaussian splatting, efficient, compact, ar, 3d gaussian  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum](https://arxiv.org/abs/2510.22213v1)**  
  Authors: Yaokun Li, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22213v1.pdf)  
  Keywords: 4d, motion, dynamic, fast, semantic, gaussian splatting, animation, compact, face, ar, 3d gaussian  
- **[Towards Physically Executable 3D Gaussian for Embodied Navigation](https://arxiv.org/abs/2510.21307v1)**  
  Authors: Bingchen Miao, Rong Wei, Zhiqi Ge, Xiaoquan sun, Shiqi Gao, Jingzhe Zhu, Renhan Wang, Siliang Tang, Jun Xiao, Rui Tang, Juncheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.21307v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, semantic, ar, face, 3d gaussian  
- **[GRASPLAT: Enabling dexterous grasping through novel view synthesis](https://arxiv.org/abs/2510.19200v1)**  
  Authors: Matteo Bortolon, Nuno Ferreira Duarte, Plinio Moreno, Fabio Poiesi, José Santos-Victor, Alessio Del Bue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19200v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mbortolon97.github.io/grasplat/)  
  Keywords: gaussian splatting, ar, face, high-fidelity, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, real-time rendering, 3d reconstruction, gaussian splatting, efficient, survey, efficient rendering, lighting, animation, ar, face, 3d gaussian  
- **[GSPlane: Concise and Accurate Planar Reconstruction via Structured
  Representation](https://arxiv.org/abs/2510.17095v1)**  
  Authors: Ruitong Gan, Junran Peng, Yang Liu, Chuanchen Luo, Qing Li, Zhaoxiang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.17095v1.pdf)  
  Keywords: dynamic, face, segmentation, gaussian splatting, ar, geometry  

### Dynamic Scene

*Showing the latest 50 out of 396 papers*

- **[HEIR: Learning Graph-Based Motion Hierarchies](https://arxiv.org/abs/2510.26786v1)**  
  Authors: Cheng Zheng, William Koch, Baiang Li, Felix Heide  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26786v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://light.princeton.edu/HEIR/)  
  Keywords: motion, dynamic, gaussian splatting, robotics, ar, deformation, 3d gaussian  
- **[The Impact and Outlook of 3D Gaussian Splatting](https://arxiv.org/abs/2510.26694v1)**  
  Authors: Bernhard Kerbl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26694v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, efficient, body, ar, 3d gaussian  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[6D Channel Knowledge Map Construction via Bidirectional Wireless
  Gaussian Splatting](https://arxiv.org/abs/2510.26166v1)**  
  Authors: Juncong Zhou, Chao Hu, Guanlin Wu, Zixiang Ren, Han Hu, Juyong Zhang, Rui Zhang, Jie Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26166v1.pdf)  
  Keywords: ar, gaussian splatting, dynamic  
- **[LagMemo: Language 3D Gaussian Splatting Memory for Multi-modal
  Open-vocabulary Multi-goal Visual Navigation](https://arxiv.org/abs/2510.24118v1)**  
  Authors: Haotian Zhou, Xiaole Wang, He Li, Fusheng Sun, Shengyu Guo, Guolei Qi, Jianghuan Xu, Huijing Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.24118v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weekgoodday.github.io/lagmemo)  
  Keywords: dynamic, gaussian splatting, ar, 3d gaussian, localization  
- **[EndoWave: Rational-Wavelet 4D Gaussian Splatting for Endoscopic
  Reconstruction](https://arxiv.org/abs/2510.23087v1)**  
  Authors: Taoyu Wu, Yiyi Miao, Jiaxin Guo, Ziyan Chen, Sihang Zhao, Zhuoxiao Li, Zhe Tang, Baoru Huang, Limin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23087v1.pdf)  
  Keywords: 4d, motion, nerf, dynamic, 3d reconstruction, gaussian splatting, ar  
- **[Scaling Up Occupancy-centric Driving Scene Generation: Dataset and
  Method](https://arxiv.org/abs/2510.22973v1)**  
  Authors: Bohan Li, Xin Jin, Hu Zhu, Hongsi Liu, Ruikai Li, Jiazhe Guo, Kaiwen Cai, Chao Ma, Yueming Jin, Hao Zhao, Xiaokang Yang, Wenjun Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22973v1.pdf)  
  Keywords: 4d, autonomous driving, dynamic, gaussian splatting, semantic, ar, high-fidelity  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[DynaPose4D: High-Quality 4D Dynamic Content Generation via Pose
  Alignment Loss](https://arxiv.org/abs/2510.22473v1)**  
  Authors: Jing Yang, Yufeng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22473v1.pdf)  
  Keywords: 4d, motion, dynamic, gaussian splatting, animation, ar, geometry, 3d gaussian  
- **[DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum](https://arxiv.org/abs/2510.22213v1)**  
  Authors: Yaokun Li, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22213v1.pdf)  
  Keywords: 4d, motion, dynamic, fast, semantic, gaussian splatting, animation, compact, face, ar, 3d gaussian  

### Few-shot

*Showing the latest 50 out of 71 papers*

- **[Initialize to Generalize: A Stronger Initialization Pipeline for
  Sparse-View 3DGS](https://arxiv.org/abs/2510.17479v1)**  
  Authors: Feng Zhou, Wenkai Guo, Pu Cao, Zhicheng Zhang, Jianqin Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.17479v1.pdf)  
  Keywords: sparse-view, motion, nerf, gaussian splatting, ar, 3d gaussian, sparse view  
- **[Opacity-Gradient Driven Density Control for Compact and Efficient
  Few-Shot 3D Gaussian Splatting](https://arxiv.org/abs/2510.10257v1)**  
  Authors: Abdelrhman Elrawy, Emad A. Mohammed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.10257v1.pdf)  
  Keywords: nerf, gaussian splatting, efficient, few-shot, compact, ar, 3d gaussian, lightweight  
- **[Gesplat: Robust Pose-Free 3D Reconstruction via Geometry-Guided Gaussian
  Splatting](https://arxiv.org/abs/2510.10097v2)**  
  Authors: Jiahui Lu, Haihong Xiao, Xueyan Zhao, Wenxiong Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.10097v2.pdf)  
  Keywords: sparse-view, nerf, 3d reconstruction, gaussian splatting, ar, geometry, 3d gaussian  
- **[LTGS: Long-Term Gaussian Scene Chronology From Sparse View Updates](https://arxiv.org/abs/2510.09881v1)**  
  Authors: Minkwan Kim, Seungmin Lee, Junho Kim, Young Min Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09881v1.pdf)  
  Keywords: sparse-view, fast, gaussian splatting, efficient, few-shot, ar, face, sparse view  
- **[D$^2$GS: Depth-and-Density Guided Gaussian Splatting for Stable and
  Accurate Sparse-View Reconstruction](https://arxiv.org/abs/2510.08566v1)**  
  Authors: Meixi Song, Xin Lin, Dizhe Zhang, Haodong Li, Xiangtai Li, Bo Du, Lu Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08566v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://insta360-research-team.github.io/DDGS-website/.)  
  Keywords: sparse-view, gaussian splatting, ar, high-fidelity, 3d gaussian, sparse view  
- **[FSFSplatter: Build Surface and Novel Views with Sparse-Views within 2min](https://arxiv.org/abs/2510.02691v2)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02691v2.pdf)  
  Keywords: sparse-view, fast, face, gaussian splatting, ar, geometry, head  
- **[HART: Human Aligned Reconstruction Transformer](https://arxiv.org/abs/2509.26621v1)**  
  Authors: Xiyi Chen, Shaofei Wang, Marko Mihajlovic, Taewon Kang, Sergey Prokudin, Ming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26621v1.pdf)  
  Keywords: sparse-view, human, body, ar, geometry  
- **[GaussianLens: Localized High-Resolution Reconstruction via On-Demand
  Gaussian Densification](https://arxiv.org/abs/2509.25603v1)**  
  Authors: Yijia Weng, Zhicheng Wang, Songyou Peng, Saining Xie, Howard Zhou, Leonidas J. Guibas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25603v1.pdf)  
  Keywords: fast, human, gaussian splatting, ar, 3d gaussian, sparse view  
- **[HBSplat: Robust Sparse-View Gaussian Reconstruction with Hybrid-Loss
  Guided Depth and Bidirectional Warping](https://arxiv.org/abs/2509.24893v3)**  
  Authors: Yu Ma, Guoliang Wei, Haihong Xiao, Yue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24893v3.pdf)  
  Keywords: sparse-view, 3d reconstruction, gaussian splatting, ar, high-fidelity, 3d gaussian, sparse view  
- **[OracleGS: Grounding Generative Priors for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2509.23258v2)**  
  Authors: Atakan Topaloglu, Kunyi Li, Michael Niemeyer, Nassir Navab, A. Murat Tekalp, Federico Tombari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23258v2.pdf)  
  Keywords: sparse-view, nerf, gaussian splatting, ar, 3d gaussian, sparse view  

### Geometry Reconstruction

*Showing the latest 50 out of 325 papers*

- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[$D^2GS$: Dense Depth Regularization for LiDAR-free Urban Scene
  Reconstruction](https://arxiv.org/abs/2510.25173v1)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, urban scene, ar, geometry  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit
  Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  
- **[EndoWave: Rational-Wavelet 4D Gaussian Splatting for Endoscopic
  Reconstruction](https://arxiv.org/abs/2510.23087v1)**  
  Authors: Taoyu Wu, Yiyi Miao, Jiaxin Guo, Ziyan Chen, Sihang Zhao, Zhuoxiao Li, Zhe Tang, Baoru Huang, Limin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23087v1.pdf)  
  Keywords: 4d, motion, nerf, dynamic, 3d reconstruction, gaussian splatting, ar  
- **[Region-Adaptive Learned Hierarchical Encoding for 3D Gaussian Splatting
  Data](https://arxiv.org/abs/2510.22812v1)**  
  Authors: Shashank N. Sridhara, Birendra Kathariya, Fangjun Pu, Peng Yin, Eduardo Pavez, Antonio Ortega  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22812v1.pdf)  
  Keywords: compression, gaussian splatting, efficient, ar, geometry, 3d gaussian, lightweight  
- **[DynaPose4D: High-Quality 4D Dynamic Content Generation via Pose
  Alignment Loss](https://arxiv.org/abs/2510.22473v1)**  
  Authors: Jing Yang, Yufeng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22473v1.pdf)  
  Keywords: 4d, motion, dynamic, gaussian splatting, animation, ar, geometry, 3d gaussian  
- **[Extreme Views: 3DGS Filter for Novel View Synthesis from
  Out-of-Distribution Camera Poses](https://arxiv.org/abs/2510.20027v1)**  
  Authors: Damian Bowness, Charalambos Poullis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.20027v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://damian-bowness.github.io/EV3DGS)  
  Keywords: nerf, 3d reconstruction, gaussian splatting, ar, geometry, 3d gaussian  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, motion, nerf, fast, gaussian splatting, survey, ar, geometry, 3d gaussian  
- **[Moving Light Adaptive Colonoscopy Reconstruction via
  Illumination-Attenuation-Aware 3D Gaussian Splatting](https://arxiv.org/abs/2510.18739v1)**  
  Authors: Hao Wang, Ying Zhou, Haoyu Zhao, Rui Wang, Qiang Hu, Xing Zhang, Qiang Li, Zhiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18739v1.pdf)  
  Keywords: tracking, dynamic, 3d reconstruction, illumination, gaussian splatting, ar, geometry, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 77 papers*

- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[$D^2GS$: Dense Depth Regularization for LiDAR-free Urban Scene
  Reconstruction](https://arxiv.org/abs/2510.25173v1)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v1.pdf)  
  Keywords: autonomous driving, gaussian splatting, urban scene, ar, geometry  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit
  Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[Leveraging 2D Priors and SDF Guidance for Dynamic Urban Scene Rendering](https://arxiv.org/abs/2510.13381v1)**  
  Authors: Siddharth Tourani, Jayaram Reddy, Akash Kumbar, Satyajit Tourani, Nishant Goyal, Madhava Krishna, N. Dinesh Reddy, Muhammad Haris Khan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.13381v1.pdf)  
  Keywords: tracking, motion, dynamic, segmentation, gaussian splatting, urban scene, ar, deformation, 3d gaussian  
- **[PAGS: Priority-Adaptive Gaussian Splatting for Dynamic Driving Scenes](https://arxiv.org/abs/2510.12282v1)**  
  Authors: Ying A, Wenzhang Sun, Chang Zeng, Chunfeng Wang, Hao Li, Jianxun Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.12282v1.pdf)  
  Keywords: autonomous driving, dynamic, 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[Two-Stage Gaussian Splatting Optimization for Outdoor Scene
  Reconstruction](https://arxiv.org/abs/2510.09489v1)**  
  Authors: Deborah Pintani, Ariel Caputo, Noah Lewis, Marc Stamminger, Fabio Pellacini, Andrea Giachetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09489v1.pdf)  
  Keywords: motion, outdoor, illumination, gaussian splatting, ar  
- **[Visibility-Aware Densification for 3D Gaussian Splatting in Dynamic
  Urban Scenes](https://arxiv.org/abs/2510.09364v1)**  
  Authors: Yikang Zhang, Rui Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09364v1.pdf)  
  Keywords: dynamic, face, gaussian splatting, urban scene, ar, geometry, high-fidelity, 3d gaussian  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: fast, outdoor, gaussian splatting, efficient, ar, head, high-fidelity, 3d gaussian, lightweight  
- **[LVT: Large-Scale Scene Reconstruction via Local View Transformers](https://arxiv.org/abs/2509.25001v1)**  
  Authors: Tooba Imtiaz, Lucy Chai, Kathryn Heal, Xuan Luo, Jungyeon Park, Jennifer Dy, John Flynn  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25001v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://toobaimt.github.io/lvt/.)  
  Keywords: ar, 3d gaussian, large scene  

### Model Compression

*Showing the latest 50 out of 404 papers*

- **[The Impact and Outlook of 3D Gaussian Splatting](https://arxiv.org/abs/2510.26694v1)**  
  Authors: Bernhard Kerbl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26694v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, efficient, body, ar, 3d gaussian  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  
- **[Gen-LangSplat: Generalized Language Gaussian Splatting with Pre-Trained
  Feature Compression](https://arxiv.org/abs/2510.22930v1)**  
  Authors: Pranav Saxena  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22930v1.pdf)  
  Keywords: compression, human, gaussian splatting, efficient, compact, ar, 3d gaussian  
- **[Region-Adaptive Learned Hierarchical Encoding for 3D Gaussian Splatting
  Data](https://arxiv.org/abs/2510.22812v1)**  
  Authors: Shashank N. Sridhara, Birendra Kathariya, Fangjun Pu, Peng Yin, Eduardo Pavez, Antonio Ortega  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22812v1.pdf)  
  Keywords: compression, gaussian splatting, efficient, ar, geometry, 3d gaussian, lightweight  
- **[Edge Collaborative Gaussian Splatting with Integrated Rendering and
  Communication](https://arxiv.org/abs/2510.22718v1)**  
  Authors: Yujie Wan, Chenxuan Liu, Shuai Wang, Tong Zhang, James Jianqiao Yu, Kejiang Ye, Dusit Niyato, Chengzhong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22718v1.pdf)  
  Keywords: ar, gaussian splatting, efficient  
- **[DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum](https://arxiv.org/abs/2510.22213v1)**  
  Authors: Yaokun Li, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22213v1.pdf)  
  Keywords: 4d, motion, dynamic, fast, semantic, gaussian splatting, animation, compact, face, ar, 3d gaussian  
- **[COS3D: Collaborative Open-Vocabulary 3D Segmentation](https://arxiv.org/abs/2510.20238v1)**  
  Authors: Runsong Zhu, Ka-Hei Hui, Zhengzhe Liu, Qianyi Wu, Weiliang Tang, Shi Qiu, Pheng-Ann Heng, Chi-Wing Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.20238v1.pdf)  
  Keywords: mapping, understanding, segmentation, robotics, efficient, ar  
- **[MoE-GS: Mixture of Experts for Dynamic Gaussian Splatting](https://arxiv.org/abs/2510.19210v1)**  
  Authors: In-Hwan Jin, Hyeongju Mun, Joonsoo Kim, Kugjin Yun, Kyeongbo Kong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19210v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://anonymous.4open.science/w/MoE-GS-68BA/.)  
  Keywords: dynamic, gaussian splatting, ar, 3d gaussian, lightweight  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, real-time rendering, 3d reconstruction, gaussian splatting, efficient, survey, efficient rendering, lighting, animation, ar, face, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 176 papers*

- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  
- **[Scaling Up Occupancy-centric Driving Scene Generation: Dataset and
  Method](https://arxiv.org/abs/2510.22973v1)**  
  Authors: Bohan Li, Xin Jin, Hu Zhu, Hongsi Liu, Ruikai Li, Jiazhe Guo, Kaiwen Cai, Chao Ma, Yueming Jin, Hao Zhao, Xiaokang Yang, Wenjun Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22973v1.pdf)  
  Keywords: 4d, autonomous driving, dynamic, gaussian splatting, semantic, ar, high-fidelity  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[RoGER-SLAM: A Robust Gaussian Splatting SLAM System for Noisy and
  Low-light Environment Resilience](https://arxiv.org/abs/2510.22600v1)**  
  Authors: Huilin Yin, Zhaolin Yang, Linchuan Zhang, Gerhard Rigoll, Johannes Betz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22600v1.pdf)  
  Keywords: tracking, mapping, illumination, gaussian splatting, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[GRASPLAT: Enabling dexterous grasping through novel view synthesis](https://arxiv.org/abs/2510.19200v1)**  
  Authors: Matteo Bortolon, Nuno Ferreira Duarte, Plinio Moreno, Fabio Poiesi, José Santos-Victor, Alessio Del Bue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19200v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mbortolon97.github.io/grasplat/)  
  Keywords: gaussian splatting, ar, face, high-fidelity, 3d gaussian  
- **[2DGS-R: Revisiting the Normal Consistency Regularization in 2D Gaussian
  Splatting](https://arxiv.org/abs/2510.16837v1)**  
  Authors: Haofan Ren, Qingsong Yan, Ming Lu, Rongfeng Lu, Zunjie Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.16837v1.pdf)  
  Keywords: gaussian splatting, lighting, ar, face, head, high-fidelity, 3d gaussian  
- **[GaussGym: An open-source real-to-sim framework for learning locomotion
  from pixels](https://arxiv.org/abs/2510.15352v1)**  
  Authors: Alejandro Escontrela, Justin Kerr, Arthur Allshire, Jonas Frey, Rocky Duan, Carmelo Sferrazza, Pieter Abbeel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.15352v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://escontrela.me/gauss_gym/.)  
  Keywords: motion, gaussian splatting, robotics, semantic, ar, high-fidelity, 3d gaussian  
- **[InsideOut: Integrated RGB-Radiative Gaussian Splatting for Comprehensive
  3D Object Representation](https://arxiv.org/abs/2510.17864v1)**  
  Authors: Jungmin Lee, Seonghyuk Hong, Juyong Lee, Jaeyoon Lee, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.17864v1.pdf)  
  Keywords: gaussian splatting, medical, ar, face, high-fidelity, 3d gaussian  
- **[Capture, Canonicalize, Splat: Zero-Shot 3D Gaussian Avatars from
  Unstructured Phone Images](https://arxiv.org/abs/2510.14081v3)**  
  Authors: Emanuel Garbin, Guy Adam, Oded Krams, Zohar Barzelay, Eran Guendelman, Michael Schwarz, Matteo Presutto, Moran Vatelmacher, Yigal Shenkman, Eli Peker, Itai Druker, Uri Patish, Yoav Blum, Max Bluvstein, Junxuan Li, Rawal Khirodkar, Shunsuke Saito  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.14081v3.pdf)  
  Keywords: avatar, gaussian splatting, body, ar, face, high-fidelity, 3d gaussian  

### Ray Tracing

- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent
  Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: reflection, ray tracing, illumination, gaussian splatting, ar, geometry  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: ray marching, gaussian splatting, efficient, ar, geometry, 3d gaussian  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral
  Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: shadow, real-time rendering, light transport, ray tracing, gaussian splatting, efficient, lighting, ar, face, relightable  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: reflection, light transport, global illumination, illumination, gaussian splatting, efficient, lighting, relighting, ar, geometry  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: 4d, dynamic, fast, ray tracing, gaussian splatting, ar  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: reflection, nerf, face, ray tracing, illumination, gaussian splatting, lighting, relighting, ar, geometry, high-fidelity, 3d gaussian  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: shadow, dynamic, global illumination, illumination, gaussian splatting, outdoor, lighting, relighting, ar, face, 3d gaussian, relightable  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: dynamic, gaussian splatting, path tracing, lighting, ar, face, 3d gaussian  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: geometry, face, gaussian splatting, efficient, efficient rendering, lighting, relighting, ar, ray marching, 3d gaussian, relightable  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: real-time rendering, ray tracing, gaussian splatting, efficient, ar, high-fidelity  

### Relighting

*Showing the latest 50 out of 118 papers*

- **[RoGER-SLAM: A Robust Gaussian Splatting SLAM System for Noisy and
  Low-light Environment Resilience](https://arxiv.org/abs/2510.22600v1)**  
  Authors: Huilin Yin, Zhaolin Yang, Linchuan Zhang, Gerhard Rigoll, Johannes Betz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22600v1.pdf)  
  Keywords: tracking, mapping, illumination, gaussian splatting, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[Dino-Diffusion Modular Designs Bridge the Cross-Domain Gap in Autonomous
  Parking](https://arxiv.org/abs/2510.20335v1)**  
  Authors: Zixuan Wu, Hengyuan Zhang, Ting-Hsuan Chen, Yuliang Guo, David Paz, Xinyu Huang, Liu Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.20335v1.pdf)  
  Keywords: motion, gaussian splatting, lighting, ar, 3d gaussian  
- **[Moving Light Adaptive Colonoscopy Reconstruction via
  Illumination-Attenuation-Aware 3D Gaussian Splatting](https://arxiv.org/abs/2510.18739v1)**  
  Authors: Hao Wang, Ying Zhou, Haoyu Zhao, Rui Wang, Qiang Hu, Xing Zhang, Qiang Li, Zhiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18739v1.pdf)  
  Keywords: tracking, dynamic, 3d reconstruction, illumination, gaussian splatting, ar, geometry, 3d gaussian  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, real-time rendering, 3d reconstruction, gaussian splatting, efficient, survey, efficient rendering, lighting, animation, ar, face, 3d gaussian  
- **[2DGS-R: Revisiting the Normal Consistency Regularization in 2D Gaussian
  Splatting](https://arxiv.org/abs/2510.16837v1)**  
  Authors: Haofan Ren, Qingsong Yan, Ming Lu, Rongfeng Lu, Zunjie Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.16837v1.pdf)  
  Keywords: gaussian splatting, lighting, ar, face, head, high-fidelity, 3d gaussian  
- **[GauSSmart: Enhanced 3D Reconstruction through 2D Foundation Models and
  Geometric Filtering](https://arxiv.org/abs/2510.14270v1)**  
  Authors: Alexander Valverde, Brian Xu, Yuyin Zhou, Meng Xu, Hongyun Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.14270v1.pdf)  
  Keywords: nerf, 3d reconstruction, segmentation, gaussian splatting, lighting, semantic, ar, 3d gaussian  
- **[Virtually Being: Customizing Camera-Controllable Video Diffusion Models
  with Multi-View Performance Captures](https://arxiv.org/abs/2510.14179v1)**  
  Authors: Yuancheng Xu, Wenqi Xian, Li Ma, Julien Philip, Ahmet Levent Taşel, Yiwei Zhao, Ryan Burgert, Mingming He, Oliver Hermann, Oliver Pilarski, Rahul Garg, Paul Debevec, Ning Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.14179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://eyeline-labs.github.io/Virtually-Being.)  
  Keywords: motion, 4d, gaussian splatting, efficient, lighting, relighting, ar  
- **[VA-GS: Enhancing the Geometric Representation of Gaussian Splatting via
  View Alignment](https://arxiv.org/abs/2510.11473v1)**  
  Authors: Qing Li, Huifang Feng, Xun Gong, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11473v1.pdf)  
  Keywords: face, illumination, gaussian splatting, efficient, lighting, ar, geometry, 3d gaussian  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent
  Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: reflection, ray tracing, illumination, gaussian splatting, ar, geometry  
- **[Two-Stage Gaussian Splatting Optimization for Outdoor Scene
  Reconstruction](https://arxiv.org/abs/2510.09489v1)**  
  Authors: Deborah Pintani, Ariel Caputo, Noah Lewis, Marc Stamminger, Fabio Pellacini, Andrea Giachetti  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09489v1.pdf)  
  Keywords: motion, outdoor, illumination, gaussian splatting, ar  

### SLAM

*Showing the latest 50 out of 147 papers*

- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[LagMemo: Language 3D Gaussian Splatting Memory for Multi-modal
  Open-vocabulary Multi-goal Visual Navigation](https://arxiv.org/abs/2510.24118v1)**  
  Authors: Haotian Zhou, Xiaole Wang, He Li, Fusheng Sun, Shengyu Guo, Guolei Qi, Jianghuan Xu, Huijing Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.24118v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weekgoodday.github.io/lagmemo)  
  Keywords: dynamic, gaussian splatting, ar, 3d gaussian, localization  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[RoGER-SLAM: A Robust Gaussian Splatting SLAM System for Noisy and
  Low-light Environment Resilience](https://arxiv.org/abs/2510.22600v1)**  
  Authors: Huilin Yin, Zhaolin Yang, Linchuan Zhang, Gerhard Rigoll, Johannes Betz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22600v1.pdf)  
  Keywords: tracking, mapping, illumination, gaussian splatting, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[COS3D: Collaborative Open-Vocabulary 3D Segmentation](https://arxiv.org/abs/2510.20238v1)**  
  Authors: Runsong Zhu, Ka-Hei Hui, Zhengzhe Liu, Qianyi Wu, Weiliang Tang, Shi Qiu, Pheng-Ann Heng, Chi-Wing Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.20238v1.pdf)  
  Keywords: mapping, understanding, segmentation, robotics, efficient, ar  
- **[Moving Light Adaptive Colonoscopy Reconstruction via
  Illumination-Attenuation-Aware 3D Gaussian Splatting](https://arxiv.org/abs/2510.18739v1)**  
  Authors: Hao Wang, Ying Zhou, Haoyu Zhao, Rui Wang, Qiang Hu, Xing Zhang, Qiang Li, Zhiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18739v1.pdf)  
  Keywords: tracking, dynamic, 3d reconstruction, illumination, gaussian splatting, ar, geometry, 3d gaussian  
- **[REALM: An MLLM-Agent Framework for Open World 3D Reasoning Segmentation
  and Editing on Gaussian Splatting](https://arxiv.org/abs/2510.16410v1)**  
  Authors: Changyue Shi, Minghao Chen, Yiping Mao, Chuxiao Yang, Xinyuan Hu, Jiajun Ding, Zhou Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.16410v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ChangyueShi.github.io/REALM.)  
  Keywords: human, understanding, segmentation, gaussian splatting, robotics, ar, 3d gaussian, localization  
- **[BalanceGS: Algorithm-System Co-design for Efficient 3D Gaussian
  Splatting Training on GPU](https://arxiv.org/abs/2510.14564v1)**  
  Authors: Junyi Wu, Jiaming Xu, Jinhao Li, Yongkang Zhou, Jiayi Pan, Xingyang Li, Guohao Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.14564v1.pdf)  
  Keywords: mapping, dynamic, 3d reconstruction, gaussian splatting, efficient, ar, 3d gaussian  
- **[Leveraging 2D Priors and SDF Guidance for Dynamic Urban Scene Rendering](https://arxiv.org/abs/2510.13381v1)**  
  Authors: Siddharth Tourani, Jayaram Reddy, Akash Kumbar, Satyajit Tourani, Nishant Goyal, Madhava Krishna, N. Dinesh Reddy, Muhammad Haris Khan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.13381v1.pdf)  
  Keywords: tracking, motion, dynamic, segmentation, gaussian splatting, urban scene, ar, deformation, 3d gaussian  

### Scene Understanding

*Showing the latest 50 out of 208 papers*

- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian
  Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, mapping, understanding, outdoor, gaussian splatting, ar, geometry, 3d gaussian, slam  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit
  Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, urban scene, semantic, ar, face  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, gaussian splatting, efficient, survey, robotics, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[PlanarGS: High-Fidelity Indoor 3D Gaussian Splatting Guided by
  Vision-Language Planar Priors](https://arxiv.org/abs/2510.23930v1)**  
  Authors: Xirui Jin, Renbiao Jin, Boying Li, Danping Zou, Wenxian Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23930v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://planargs.github.io)  
  Keywords: face, segmentation, gaussian splatting, efficient, ar, geometry, high-fidelity, 3d gaussian  
- **[Explicit Memory through Online 3D Gaussian Splatting Improves
  Class-Agnostic Video Segmentation](https://arxiv.org/abs/2510.23521v1)**  
  Authors: Anthony Opipari, Aravindhan K Krishnan, Shreekant Gayaka, Min Sun, Cheng-Hao Kuo, Arnie Sen, Odest Chadwicke Jenkins  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23521v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://topipari.com/projects/FastSAM-Splat/)  
  Keywords: fast, segmentation, gaussian splatting, ar, 3d gaussian  
- **[Scaling Up Occupancy-centric Driving Scene Generation: Dataset and
  Method](https://arxiv.org/abs/2510.22973v1)**  
  Authors: Bohan Li, Xin Jin, Hu Zhu, Hongsi Liu, Ruikai Li, Jiazhe Guo, Kaiwen Cai, Chao Ma, Yueming Jin, Hao Zhao, Xiaokang Yang, Wenjun Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22973v1.pdf)  
  Keywords: 4d, autonomous driving, dynamic, gaussian splatting, semantic, ar, high-fidelity  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical
  Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: mapping, dynamic, human, outdoor, segmentation, gaussian splatting, ar, high-fidelity, 3d gaussian, slam  
- **[RoGER-SLAM: A Robust Gaussian Splatting SLAM System for Noisy and
  Low-light Environment Resilience](https://arxiv.org/abs/2510.22600v1)**  
  Authors: Huilin Yin, Zhaolin Yang, Linchuan Zhang, Gerhard Rigoll, Johannes Betz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22600v1.pdf)  
  Keywords: tracking, mapping, illumination, gaussian splatting, semantic, ar, high-fidelity, 3d gaussian, localization, slam  
- **[DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum](https://arxiv.org/abs/2510.22213v1)**  
  Authors: Yaokun Li, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22213v1.pdf)  
  Keywords: 4d, motion, dynamic, fast, semantic, gaussian splatting, animation, compact, face, ar, 3d gaussian  
- **[Towards Physically Executable 3D Gaussian for Embodied Navigation](https://arxiv.org/abs/2510.21307v1)**  
  Authors: Bingchen Miao, Rong Wei, Zhiqi Ge, Xiaoquan sun, Shiqi Gao, Jingzhe Zhu, Renhan Wang, Siliang Tang, Jun Xiao, Rui Tang, Juncheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.21307v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, semantic, ar, face, 3d gaussian  



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