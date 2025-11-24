# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-11-24 00:59:46

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

- [3DGS Surveys](#3dgs-surveys) (23 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (259 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (337 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (395 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (319 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (76 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (404 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (183 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (15 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (122 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (140 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (199 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: robotics, ar, gaussian splatting, high-fidelity, localization, semantic, efficient, slam, 3d gaussian, survey, mapping  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: motion, nerf, fast, ar, 4d, geometry, gaussian splatting, 3d gaussian, survey  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, ar, 3d reconstruction, real-time rendering, gaussian splatting, lighting, animation, face, efficient rendering, efficient, 3d gaussian, survey  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: lightweight, nerf, gaussian splatting, efficient, human, ar, understanding, survey  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: nerf, fast, ar, gaussian splatting, neural rendering, efficient, slam, 3d gaussian, understanding, survey  
- **[A-TDOM: Active TDOM via On-the-Fly 3DGS](https://arxiv.org/abs/2509.12759v2)**  
  Authors: Yiwei Xu, Xiang Wang, Yifei Yu, Wentian Gan, Luca Morelli, Giulio Perda, Xiongwu Xiao, Zongqian Zhan, Xin Wang, Fabio Remondino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12759v2.pdf)  
  Keywords: ar, survey, face  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: nerf, compact, ar, segmentation, gaussian splatting, high-fidelity, lighting, semantic, 3d gaussian, understanding, survey  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: robotics, nerf, ar, gaussian splatting, semantic, efficient, 3d gaussian, understanding, survey  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: robotics, nerf, ar, gaussian splatting, human, 3d gaussian, survey  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: robotics, motion, nerf, ar, 3d reconstruction, geometry, gaussian splatting, sparse-view, 3d gaussian, survey, vr  

### Acceleration

*Showing the latest 50 out of 259 papers*

- **[Optimizing 3D Gaussian Splattering for Mobile GPUs](https://arxiv.org/abs/2511.16298v1)**  
  Authors: Md Musfiqur Rahman Sanim, Zhihao Shu, Bahram Afsharmanesh, AmirAli Mirian, Jiexiong Guan, Wei Niu, Bin Ren, Gagan Agrawal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16298v1.pdf)  
  Keywords: fast, ar, gaussian splatting, efficient, 3d gaussian, mapping  
- **[Gaussian Blending: Rethinking Alpha Blending in 3D Gaussian Splatting](https://arxiv.org/abs/2511.15102v1)**  
  Authors: Junseo Koo, Jinseo Jeong, Gunhee Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.15102v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, real-time rendering  
- **[IBGS: Image-Based Gaussian Splatting](https://arxiv.org/abs/2511.14357v1)**  
  Authors: Hoang Chuong Nguyen, Wei Mao, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14357v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, efficient, head, 3d gaussian  
- **[SF-Recon: Simplification-Free Lightweight Building Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2511.13278v1)**  
  Authors: Zihan Li, Tengfei Wang, Wentian Gan, Hao Zhan, Xin Wang, Zongqian Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13278v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lzh282140127-cell.github.io/SF-Recon-project/)  
  Keywords: lightweight, fast, ar, geometry, gaussian splatting, face, 3d gaussian  
- **[Neo: Real-Time On-Device 3D Gaussian Splatting with Reuse-and-Update Sorting Acceleration](https://arxiv.org/abs/2511.12930v1)**  
  Authors: Changhun Oh, Seongryong Oh, Jinwoo Hwang, Yoonsung Kim, Hardik Sharma, Jongse Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12930v1.pdf)  
  Keywords: tracking, ar, gaussian splatting, efficient, 3d gaussian, acceleration, vr  
- **[Changes in Real Time: Online Scene Change Detection with Multi-View Fusion](https://arxiv.org/abs/2511.12370v1)**  
  Authors: Chamuditha Jayanga Galappaththige, Jason Lai, Lloyd Windrim, Donald Dansereau, Niko Sünderhauf, Dimity Miller  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12370v1.pdf)  
  Keywords: 3d gaussian, fast, gaussian splatting, ar  
- **[RealisticDreamer: Guidance Score Distillation for Few-shot Gaussian Splatting](https://arxiv.org/abs/2511.11213v1)**  
  Authors: Ruocheng Wu, Haolan He, Yufei Wang, Zhihao Li, Bihan Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11213v1.pdf)  
  Keywords: motion, ar, geometry, real-time rendering, gaussian splatting, few-shot, semantic, 3d gaussian  
- **[YoNoSplat: You Only Need One Model for Feedforward 3D Gaussian Splatting](https://arxiv.org/abs/2511.07321v1)**  
  Authors: Botao Ye, Boqi Chen, Haofei Xu, Daniel Barath, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.07321v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://botaoye.github.io/yonosplat/.)  
  Keywords: 3d gaussian, fast, gaussian splatting, ar  
- **[GFix: Perceptually Enhanced Gaussian Splatting Video Compression](https://arxiv.org/abs/2511.06953v1)**  
  Authors: Siyue Teng, Ge Gao, Duolikun Danier, Yuxuan Jiang, Fan Zhang, Thomas Davis, Zoe Liu, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06953v1.pdf)  
  Keywords: fast, ar, compression, gaussian splatting, quality enhancement, efficient, 3d gaussian  
- **[ConeGS: Error-Guided Densification Using Pixel Cones for Improved Reconstruction with Fewer Primitives](https://arxiv.org/abs/2511.06810v1)**  
  Authors: Bartłomiej Baranowski, Stefano Esposito, Patricia Gschoßmann, Anpei Chen, Andreas Geiger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06810v1.pdf)  
  Keywords: fast, ar, geometry, gaussian splatting, efficient, 3d gaussian  

### Applications

*Showing the latest 50 out of 996 papers*

- **[EOGS++: Earth Observation Gaussian Splatting with Internal Camera Refinement and Direct Panchromatic Rendering](https://arxiv.org/abs/2511.16542v1)**  
  Authors: Pierrick Bournez, Luca Savant Aira, Thibaud Ehret, Gabriele Facciolo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16542v1.pdf)  
  Keywords: 3d gaussian, nerf, gaussian splatting, ar  
- **[Upsample Anything: A Simple and Hard to Beat Baseline for Feature Upsampling](https://arxiv.org/abs/2511.16301v1)**  
  Authors: Minseok Seo, Mark Hamilton, Changick Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16301v1.pdf)  
  Keywords: lightweight, segmentation, gaussian splatting, semantic, ar  
- **[Optimizing 3D Gaussian Splattering for Mobile GPUs](https://arxiv.org/abs/2511.16298v1)**  
  Authors: Md Musfiqur Rahman Sanim, Zhihao Shu, Bahram Afsharmanesh, AmirAli Mirian, Jiexiong Guan, Wei Niu, Bin Ren, Gagan Agrawal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16298v1.pdf)  
  Keywords: fast, ar, gaussian splatting, efficient, 3d gaussian, mapping  
- **[LEGO-SLAM: Language-Embedded Gaussian Optimization SLAM](https://arxiv.org/abs/2511.16144v1)**  
  Authors: Sibaek Lee, Seongbo Ha, Kyeongsu Kang, Joonyeol Choi, Seungjun Tak, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16144v1.pdf)  
  Keywords: tracking, compact, ar, gaussian splatting, localization, semantic, head, slam, 3d gaussian, understanding, mapping  
- **[Clustered Error Correction with Grouped 4D Gaussian Splatting](https://arxiv.org/abs/2511.16112v1)**  
  Authors: Taeho Kang, Jaeyeon Park, Kyungjin Lee, Youngki Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16112v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, ar, mapping  
- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: ar, 3d reconstruction, gaussian splatting, high-fidelity, sparse-view, sparse view, efficient, 3d gaussian  
- **[Gaussian Blending: Rethinking Alpha Blending in 3D Gaussian Splatting](https://arxiv.org/abs/2511.15102v1)**  
  Authors: Junseo Koo, Jinseo Jeong, Gunhee Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.15102v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, real-time rendering  
- **[Gaussian See, Gaussian Do: Semantic 3D Motion Transfer from Multiview Video](https://arxiv.org/abs/2511.14848v1)**  
  Authors: Yarin Bekor, Gal Michael Harari, Or Perel, Or Litany  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14848v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsgd-motiontransfer.github.io/)  
  Keywords: motion, dynamic, ar, 4d, gaussian splatting, semantic, 3d gaussian  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: nerf, ar, geometry, gaussian splatting, sparse-view, face, efficient, 3d gaussian  
- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: dynamic, motion, ar, 4d, geometry, gaussian splatting, lighting, deformation, 3d gaussian  

### Avatar Generation

*Showing the latest 50 out of 337 papers*

- **[LEGO-SLAM: Language-Embedded Gaussian Optimization SLAM](https://arxiv.org/abs/2511.16144v1)**  
  Authors: Sibaek Lee, Seongbo Ha, Kyeongsu Kang, Joonyeol Choi, Seungjun Tak, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16144v1.pdf)  
  Keywords: tracking, compact, ar, gaussian splatting, localization, semantic, head, slam, 3d gaussian, understanding, mapping  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: nerf, ar, geometry, gaussian splatting, sparse-view, face, efficient, 3d gaussian  
- **[IBGS: Image-Based Gaussian Splatting](https://arxiv.org/abs/2511.14357v1)**  
  Authors: Hoang Chuong Nguyen, Wei Mao, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14357v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, efficient, head, 3d gaussian  
- **[Silhouette-to-Contour Registration: Aligning Intraoral Scan Models with Cephalometric Radiographs](https://arxiv.org/abs/2511.14343v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Ji Jiang, Tong Chen, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14343v1.pdf)  
  Keywords: geometry, gaussian splatting, high-fidelity, face, ar  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[iGaussian: Real-Time Camera Pose Estimation via Feed-Forward 3D Gaussian Splatting Inversion](https://arxiv.org/abs/2511.14149v1)**  
  Authors: Hao Wang, Linqing Zhao, Xiuwei Xu, Jiwen Lu, Haibin Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14149v1.pdf)  
  Keywords: tracking, robotics, nerf, ar, gaussian splatting, lighting, head, slam, 3d gaussian  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[SF-Recon: Simplification-Free Lightweight Building Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2511.13278v1)**  
  Authors: Zihan Li, Tengfei Wang, Wentian Gan, Hao Zhan, Xin Wang, Zongqian Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13278v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lzh282140127-cell.github.io/SF-Recon-project/)  
  Keywords: lightweight, fast, ar, geometry, gaussian splatting, face, 3d gaussian  
- **[Beyond Darkness: Thermal-Supervised 3D Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2511.13011v1)**  
  Authors: Qingsen Ma, Chen Zou, Dianyun Wang, Jia Wang, Liuyu Xiang, Zhaofeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13011v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, geometry, gaussian splatting, illumination, face, 3d gaussian  
- **[LiDAR-GS++:Improving LiDAR Gaussian Reconstruction via Diffusion Priors](https://arxiv.org/abs/2511.12304v1)**  
  Authors: Qifeng Chen, Jiarun Liu, Rengan Xie, Tao Tang, Sicong Du, Yiru Zhao, Yuchi Huo, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12304v1.pdf)  
  Keywords: nerf, geometry, gaussian splatting, high-fidelity, face, ar  

### Dynamic Scene

*Showing the latest 50 out of 395 papers*

- **[Clustered Error Correction with Grouped 4D Gaussian Splatting](https://arxiv.org/abs/2511.16112v1)**  
  Authors: Taeho Kang, Jaeyeon Park, Kyungjin Lee, Youngki Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16112v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, ar, mapping  
- **[Gaussian See, Gaussian Do: Semantic 3D Motion Transfer from Multiview Video](https://arxiv.org/abs/2511.14848v1)**  
  Authors: Yarin Bekor, Gal Michael Harari, Or Perel, Or Litany  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14848v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsgd-motiontransfer.github.io/)  
  Keywords: motion, dynamic, ar, 4d, gaussian splatting, semantic, 3d gaussian  
- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: dynamic, motion, ar, 4d, geometry, gaussian splatting, lighting, deformation, 3d gaussian  
- **[Opt3DGS: Optimizing 3D Gaussian Splatting with Adaptive Exploration and Curvature-Aware Exploitation](https://arxiv.org/abs/2511.13571v1)**  
  Authors: Ziyang Huang, Jiagang Chen, Jin Liu, Shunping Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13571v1.pdf)  
  Keywords: 3d gaussian, dynamic, gaussian splatting, efficient, ar  
- **[Beyond Darkness: Thermal-Supervised 3D Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2511.13011v1)**  
  Authors: Qingsen Ma, Chen Zou, Dianyun Wang, Jia Wang, Liuyu Xiang, Zhaofeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13011v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, geometry, gaussian splatting, illumination, face, 3d gaussian  
- **[Reconstructing 3D Scenes in Native High Dynamic Range](https://arxiv.org/abs/2511.12895v1)**  
  Authors: Kaixuan Zhang, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12895v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, gaussian splatting, 3d gaussian, mapping  
- **[RealisticDreamer: Guidance Score Distillation for Few-shot Gaussian Splatting](https://arxiv.org/abs/2511.11213v1)**  
  Authors: Ruocheng Wu, Haolan He, Yufei Wang, Zhihao Li, Bihan Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11213v1.pdf)  
  Keywords: motion, ar, geometry, real-time rendering, gaussian splatting, few-shot, semantic, 3d gaussian  
- **[Dynamic Gaussian Scene Reconstruction from Unsynchronized Videos](https://arxiv.org/abs/2511.11175v1)**  
  Authors: Zhixin Xu, Hengyu Zhou, Yuan Liu, Wenhan Xue, Hao Pan, Wenping Wang, Bin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11175v1.pdf)  
  Keywords: dynamic, motion, 4d, gaussian splatting, ar  
- **[PINGS-X: Physics-Informed Normalized Gaussian Splatting with Axes Alignment for Efficient Super-Resolution of 4D Flow MRI](https://arxiv.org/abs/2511.11048v1)**  
  Authors: Sun Jo, Seok Young Hong, JinHyun Kim, Seungmin Kang, Ahjin Choi, Don-Gwan An, Simon Song, Je Hyeong Hong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11048v1.pdf)  
  Keywords: dynamic, ar, 4d, gaussian splatting, efficient, 3d gaussian  
- **[AHA! Animating Human Avatars in Diverse Scenes with Gaussian Splatting](https://arxiv.org/abs/2511.09827v1)**  
  Authors: Aymen Mir, Jian Wang, Riza Alp Guler, Chuan Guo, Gerard Pons-Moll, Bing Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.09827v1.pdf)  
  Keywords: avatar, 3d gaussian, motion, ar, geometry, gaussian splatting, human, animation  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: ar, 3d reconstruction, gaussian splatting, high-fidelity, sparse-view, sparse view, efficient, 3d gaussian  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: nerf, ar, geometry, gaussian splatting, sparse-view, face, efficient, 3d gaussian  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[RoboTidy : A 3D Gaussian Splatting Household Tidying Benchmark for Embodied Navigation and Action](https://arxiv.org/abs/2511.14161v2)**  
  Authors: Xiaoquan Sun, Ruijian Zhang, Kang Pang, Bingchen Miao, Yuxiang Tan, Zhen Yang, Ming Li, Jiayu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14161v2.pdf)  
  Keywords: few-shot, 3d gaussian, gaussian splatting, ar  
- **[SplatSearch: Instance Image Goal Navigation for Mobile Robots using 3D Gaussian Splatting and Diffusion Models](https://arxiv.org/abs/2511.12972v1)**  
  Authors: Siddarth Narasimhan, Matthew Lisondra, Haitong Wang, Goldie Nejat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12972v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, semantic, 3d gaussian  
- **[RealisticDreamer: Guidance Score Distillation for Few-shot Gaussian Splatting](https://arxiv.org/abs/2511.11213v1)**  
  Authors: Ruocheng Wu, Haolan He, Yufei Wang, Zhihao Li, Bihan Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11213v1.pdf)  
  Keywords: motion, ar, geometry, real-time rendering, gaussian splatting, few-shot, semantic, 3d gaussian  
- **[Sparse4DGS: 4D Gaussian Splatting for Sparse-Frame Dynamic Scene Reconstruction](https://arxiv.org/abs/2511.07122v1)**  
  Authors: Changyue Shi, Chuxiao Yang, Xinyuan Hu, Minghao Chen, Wenwen Pan, Yan Yang, Jiajun Ding, Zhou Yu, Jun Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.07122v1.pdf)  
  Keywords: dynamic, nerf, 4d, gaussian splatting, few-shot, deformation, ar  
- **[FastGS: Training 3D Gaussian Splatting in 100 Seconds](https://arxiv.org/abs/2511.04283v1)**  
  Authors: Shiwei Ren, Tianci Wen, Yongchun Fang, Biao Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fastgs.github.io/)  
  Keywords: dynamic, nerf, fast, ar, gaussian splatting, localization, sparse-view, face, efficient, head, 3d gaussian, acceleration, mapping  
- **[DentalSplat: Dental Occlusion Novel View Synthesis from Sparse Intra-Oral Photographs](https://arxiv.org/abs/2511.03099v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Sihao Li, Ji Jiang, Youpeng Yang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.03099v1.pdf)  
  Keywords: ar, 3d reconstruction, gaussian splatting, sparse view, 3d gaussian  
- **[Initialize to Generalize: A Stronger Initialization Pipeline for Sparse-View 3DGS](https://arxiv.org/abs/2510.17479v1)**  
  Authors: Feng Zhou, Wenkai Guo, Pu Cao, Zhicheng Zhang, Jianqin Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.17479v1.pdf)  
  Keywords: motion, nerf, ar, gaussian splatting, sparse-view, sparse view, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 319 papers*

- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: ar, 3d reconstruction, gaussian splatting, high-fidelity, sparse-view, sparse view, efficient, 3d gaussian  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: nerf, ar, geometry, gaussian splatting, sparse-view, face, efficient, 3d gaussian  
- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: dynamic, motion, ar, 4d, geometry, gaussian splatting, lighting, deformation, 3d gaussian  
- **[Silhouette-to-Contour Registration: Aligning Intraoral Scan Models with Cephalometric Radiographs](https://arxiv.org/abs/2511.14343v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Ji Jiang, Tong Chen, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14343v1.pdf)  
  Keywords: geometry, gaussian splatting, high-fidelity, face, ar  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[GEN3D: Generating Domain-Free 3D Scenes from a Single Image](https://arxiv.org/abs/2511.14291v1)**  
  Authors: Yuxin Zhang, Ziyu Lu, Hongbo Duan, Keyu Fan, Pengting Luo, Peiyu Zhuang, Mengyu Yang, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14291v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, high-fidelity  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[SF-Recon: Simplification-Free Lightweight Building Reconstruction via 3D Gaussian Splatting](https://arxiv.org/abs/2511.13278v1)**  
  Authors: Zihan Li, Tengfei Wang, Wentian Gan, Hao Zhan, Xin Wang, Zongqian Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13278v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lzh282140127-cell.github.io/SF-Recon-project/)  
  Keywords: lightweight, fast, ar, geometry, gaussian splatting, face, 3d gaussian  
- **[Beyond Darkness: Thermal-Supervised 3D Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2511.13011v1)**  
  Authors: Qingsen Ma, Chen Zou, Dianyun Wang, Jia Wang, Liuyu Xiang, Zhaofeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13011v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, geometry, gaussian splatting, illumination, face, 3d gaussian  
- **[Reconstructing 3D Scenes in Native High Dynamic Range](https://arxiv.org/abs/2511.12895v1)**  
  Authors: Kaixuan Zhang, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12895v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, gaussian splatting, 3d gaussian, mapping  

### Large Scene

*Showing the latest 50 out of 76 papers*

- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, high-fidelity, outdoor, 3d gaussian  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: dynamic, 4d, autonomous driving, gaussian splatting, urban scene, human, ar  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: fast, ar, gaussian splatting, head, large scene, 3d gaussian  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, ar, geometry, gaussian splatting, outdoor, slam, 3d gaussian, understanding, mapping  
- **[D$^2$GS: Dense Depth Regularization for LiDAR-free Urban Scene Reconstruction](https://arxiv.org/abs/2510.25173v2)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v2.pdf)  
  Keywords: autonomous driving, geometry, gaussian splatting, urban scene, ar  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: 3d reconstruction, gaussian splatting, semantic, urban scene, face, ar  
- **[LVD-GS: Gaussian Splatting SLAM for Dynamic Scenes via Hierarchical Explicit-Implicit Representation Collaboration Rendering](https://arxiv.org/abs/2510.22669v1)**  
  Authors: Wenkai Zhu, Xu Li, Qimin Xu, Benwu Wang, Kun Wei, Yiming Peng, Zihang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22669v1.pdf)  
  Keywords: dynamic, slam, ar, segmentation, gaussian splatting, high-fidelity, outdoor, human, 3d gaussian, mapping  
- **[Leveraging 2D Priors and SDF Guidance for Dynamic Urban Scene Rendering](https://arxiv.org/abs/2510.13381v1)**  
  Authors: Siddharth Tourani, Jayaram Reddy, Akash Kumbar, Satyajit Tourani, Nishant Goyal, Madhava Krishna, N. Dinesh Reddy, Muhammad Haris Khan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.13381v1.pdf)  
  Keywords: tracking, motion, dynamic, ar, segmentation, gaussian splatting, urban scene, deformation, 3d gaussian  
- **[PAGS: Priority-Adaptive Gaussian Splatting for Dynamic Driving Scenes](https://arxiv.org/abs/2510.12282v1)**  
  Authors: Ying A, Wenzhang Sun, Chang Zeng, Chunfeng Wang, Hao Li, Jianxun Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.12282v1.pdf)  
  Keywords: dynamic, 3d reconstruction, autonomous driving, gaussian splatting, semantic, urban scene, face, ar  

### Model Compression

*Showing the latest 50 out of 404 papers*

- **[Upsample Anything: A Simple and Hard to Beat Baseline for Feature Upsampling](https://arxiv.org/abs/2511.16301v1)**  
  Authors: Minseok Seo, Mark Hamilton, Changick Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16301v1.pdf)  
  Keywords: lightweight, segmentation, gaussian splatting, semantic, ar  
- **[Optimizing 3D Gaussian Splattering for Mobile GPUs](https://arxiv.org/abs/2511.16298v1)**  
  Authors: Md Musfiqur Rahman Sanim, Zhihao Shu, Bahram Afsharmanesh, AmirAli Mirian, Jiexiong Guan, Wei Niu, Bin Ren, Gagan Agrawal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16298v1.pdf)  
  Keywords: fast, ar, gaussian splatting, efficient, 3d gaussian, mapping  
- **[LEGO-SLAM: Language-Embedded Gaussian Optimization SLAM](https://arxiv.org/abs/2511.16144v1)**  
  Authors: Sibaek Lee, Seongbo Ha, Kyeongsu Kang, Joonyeol Choi, Seungjun Tak, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16144v1.pdf)  
  Keywords: tracking, compact, ar, gaussian splatting, localization, semantic, head, slam, 3d gaussian, understanding, mapping  
- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: ar, 3d reconstruction, gaussian splatting, high-fidelity, sparse-view, sparse view, efficient, 3d gaussian  
- **[SparseSurf: Sparse-View 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2511.14633v1)**  
  Authors: Meiying Gu, Jiawei Zhang, Jiahe Li, Xiaohan Yu, Haonan Luo, Jin Zheng, Xiao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14633v1.pdf)  
  Keywords: nerf, ar, geometry, gaussian splatting, sparse-view, face, efficient, 3d gaussian  
- **[IBGS: Image-Based Gaussian Splatting](https://arxiv.org/abs/2511.14357v1)**  
  Authors: Hoang Chuong Nguyen, Wei Mao, Jose M. Alvarez, Miaomiao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14357v1.pdf)  
  Keywords: fast, ar, gaussian splatting, face, efficient, head, 3d gaussian  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[Gaussian Splatting-based Low-Rank Tensor Representation for Multi-Dimensional Image Recovery](https://arxiv.org/abs/2511.14270v2)**  
  Authors: Yiming Zeng, Xi-Le Zhao, Wei-Hao Wu, Teng-Yu Ji, Chao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14270v2.pdf)  
  Keywords: ar, compact, gaussian splatting  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[Opt3DGS: Optimizing 3D Gaussian Splatting with Adaptive Exploration and Curvature-Aware Exploitation](https://arxiv.org/abs/2511.13571v1)**  
  Authors: Ziyang Huang, Jiagang Chen, Jin Liu, Shunping Ji  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13571v1.pdf)  
  Keywords: 3d gaussian, dynamic, gaussian splatting, efficient, ar  

### Quality Enhancement

*Showing the latest 50 out of 183 papers*

- **[CuriGS: Curriculum-Guided Gaussian Splatting for Sparse View Synthesis](https://arxiv.org/abs/2511.16030v1)**  
  Authors: Zijian Wu, Mingfeng Jiang, Zidian Lin, Ying Song, Hanjie Ma, Qun Wu, Dongping Zhang, Guiyang Pu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16030v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zijian1026.github.io/CuriGS/)  
  Keywords: ar, 3d reconstruction, gaussian splatting, high-fidelity, sparse-view, sparse view, efficient, 3d gaussian  
- **[Silhouette-to-Contour Registration: Aligning Intraoral Scan Models with Cephalometric Radiographs](https://arxiv.org/abs/2511.14343v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Ji Jiang, Tong Chen, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14343v1.pdf)  
  Keywords: geometry, gaussian splatting, high-fidelity, face, ar  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[GEN3D: Generating Domain-Free 3D Scenes from a Single Image](https://arxiv.org/abs/2511.14291v1)**  
  Authors: Yuxin Zhang, Ziyu Lu, Hongbo Duan, Keyu Fan, Pengting Luo, Peiyu Zhuang, Mengyu Yang, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14291v1.pdf)  
  Keywords: ar, gaussian splatting, 3d reconstruction, high-fidelity  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[LiDAR-GS++:Improving LiDAR Gaussian Reconstruction via Diffusion Priors](https://arxiv.org/abs/2511.12304v1)**  
  Authors: Qifeng Chen, Jiarun Liu, Rengan Xie, Tao Tang, Sicong Du, Yiru Zhao, Yuchi Huo, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12304v1.pdf)  
  Keywords: nerf, geometry, gaussian splatting, high-fidelity, face, ar  
- **[3D Gaussian and Diffusion-Based Gaze Redirection](https://arxiv.org/abs/2511.11231v1)**  
  Authors: Abiram Panchalingam, Indu Bodala, Stuart Middleton  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11231v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, head, 3d gaussian  
- **[OUGS: Active View Selection via Object-aware Uncertainty Estimation in 3DGS](https://arxiv.org/abs/2511.09397v1)**  
  Authors: Haiyi Li, Qi Chen, Denis Kalkofen, Hsiang-Ting Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.09397v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, high-fidelity, semantic, efficient, 3d gaussian  
- **[Perceptual Quality Assessment of 3D Gaussian Splatting: A Subjective Dataset and Prediction Metric](https://arxiv.org/abs/2511.08032v1)**  
  Authors: Zhaolin Wan, Yining Diao, Jingqi Xu, Hao Wang, Zhiyang Li, Xiaopeng Fan, Wangmeng Zuo, Debin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.08032v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, lighting, 3d gaussian  
- **[GFix: Perceptually Enhanced Gaussian Splatting Video Compression](https://arxiv.org/abs/2511.06953v1)**  
  Authors: Siyue Teng, Ge Gao, Duolikun Danier, Yuxuan Jiang, Fan Zhang, Thomas Davis, Zoe Liu, David Bull  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06953v1.pdf)  
  Keywords: fast, ar, compression, gaussian splatting, quality enhancement, efficient, 3d gaussian  

### Ray Tracing

- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ray tracing, geometry, reflection, gaussian splatting, illumination, ar  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: ar, geometry, gaussian splatting, ray marching, efficient, 3d gaussian  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: relightable, shadow, ray tracing, real-time rendering, gaussian splatting, lighting, face, efficient, light transport, ar  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: reflection, geometry, light transport, gaussian splatting, lighting, relighting, illumination, efficient, global illumination, ar  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: dynamic, fast, 4d, ray tracing, gaussian splatting, ar  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: nerf, ar, ray tracing, reflection, geometry, gaussian splatting, high-fidelity, lighting, relighting, illumination, face, 3d gaussian  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: relightable, dynamic, ar, shadow, gaussian splatting, lighting, outdoor, relighting, illumination, face, global illumination, 3d gaussian  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: dynamic, ar, path tracing, gaussian splatting, lighting, face, 3d gaussian  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relightable, ar, geometry, gaussian splatting, lighting, ray marching, relighting, face, efficient, 3d gaussian, efficient rendering  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: ray tracing, real-time rendering, gaussian splatting, high-fidelity, efficient, ar  

### Relighting

*Showing the latest 50 out of 122 papers*

- **[Interaction-Aware 4D Gaussian Splatting for Dynamic Hand-Object Interaction Reconstruction](https://arxiv.org/abs/2511.14540v1)**  
  Authors: Hao Tian, Chenyangguang Zhang, Rui Liu, Wen Shen, Xiaolin Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14540v1.pdf)  
  Keywords: dynamic, motion, ar, 4d, geometry, gaussian splatting, lighting, deformation, 3d gaussian  
- **[Dental3R: Geometry-Aware Pairing for Intraoral 3D Reconstruction from Sparse-View Photographs](https://arxiv.org/abs/2511.14315v1)**  
  Authors: Yiyi Miao, Taoyu Wu, Tong Chen, Ji Jiang, Zhe Tang, Zhengyong Jiang, Angelos Stefanidis, Limin Yu, Jionglong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14315v1.pdf)  
  Keywords: compact, ar, 3d reconstruction, geometry, gaussian splatting, high-fidelity, sparse-view, illumination, face, 3d gaussian  
- **[iGaussian: Real-Time Camera Pose Estimation via Feed-Forward 3D Gaussian Splatting Inversion](https://arxiv.org/abs/2511.14149v1)**  
  Authors: Hao Wang, Linqing Zhao, Xiuwei Xu, Jiwen Lu, Haibin Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14149v1.pdf)  
  Keywords: tracking, robotics, nerf, ar, gaussian splatting, lighting, head, slam, 3d gaussian  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[Beyond Darkness: Thermal-Supervised 3D Gaussian Splatting for Low-Light Novel View Synthesis](https://arxiv.org/abs/2511.13011v1)**  
  Authors: Qingsen Ma, Chen Zou, Dianyun Wang, Jia Wang, Liuyu Xiang, Zhaofeng He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13011v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, geometry, gaussian splatting, illumination, face, 3d gaussian  
- **[Perceptual Quality Assessment of 3D Gaussian Splatting: A Subjective Dataset and Prediction Metric](https://arxiv.org/abs/2511.08032v1)**  
  Authors: Zhaolin Wan, Yining Diao, Jingqi Xu, Hao Wang, Zhiyang Li, Xiaopeng Fan, Wangmeng Zuo, Debin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.08032v1.pdf)  
  Keywords: ar, gaussian splatting, high-fidelity, lighting, 3d gaussian  
- **[UltraGS: Gaussian Splatting for Ultrasound Novel View Synthesis](https://arxiv.org/abs/2511.07743v1)**  
  Authors: Yuezhe Yang, Wenjie Cai, Dexin Yang, Yufang Dong, Xingbo Dong, Zhe Jin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.07743v1.pdf)  
  Keywords: reflection, lightweight, gaussian splatting, ar  
- **[Channel Knowledge Map Construction: Recent Advances and Open Challenges](https://arxiv.org/abs/2511.04944v1)**  
  Authors: Zixiang Ren, Juncong Zhou, Jie Xu, Ling Qiu, Yong Zeng, Han Hu, Juyong Zhang, Rui Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04944v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, lighting, efficient, ar  
- **[RoGER-SLAM: A Robust Gaussian Splatting SLAM System for Noisy and Low-light Environment Resilience](https://arxiv.org/abs/2510.22600v1)**  
  Authors: Huilin Yin, Zhaolin Yang, Linchuan Zhang, Gerhard Rigoll, Johannes Betz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.22600v1.pdf)  
  Keywords: tracking, ar, gaussian splatting, high-fidelity, localization, semantic, illumination, slam, 3d gaussian, mapping  
- **[Dino-Diffusion Modular Designs Bridge the Cross-Domain Gap in Autonomous Parking](https://arxiv.org/abs/2510.20335v1)**  
  Authors: Zixuan Wu, Hengyuan Zhang, Ting-Hsuan Chen, Yuliang Guo, David Paz, Xinyu Huang, Liu Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.20335v1.pdf)  
  Keywords: motion, ar, gaussian splatting, lighting, 3d gaussian  

### SLAM

*Showing the latest 50 out of 140 papers*

- **[Optimizing 3D Gaussian Splattering for Mobile GPUs](https://arxiv.org/abs/2511.16298v1)**  
  Authors: Md Musfiqur Rahman Sanim, Zhihao Shu, Bahram Afsharmanesh, AmirAli Mirian, Jiexiong Guan, Wei Niu, Bin Ren, Gagan Agrawal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16298v1.pdf)  
  Keywords: fast, ar, gaussian splatting, efficient, 3d gaussian, mapping  
- **[LEGO-SLAM: Language-Embedded Gaussian Optimization SLAM](https://arxiv.org/abs/2511.16144v1)**  
  Authors: Sibaek Lee, Seongbo Ha, Kyeongsu Kang, Joonyeol Choi, Seungjun Tak, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16144v1.pdf)  
  Keywords: tracking, compact, ar, gaussian splatting, localization, semantic, head, slam, 3d gaussian, understanding, mapping  
- **[Clustered Error Correction with Grouped 4D Gaussian Splatting](https://arxiv.org/abs/2511.16112v1)**  
  Authors: Taeho Kang, Jaeyeon Park, Kyungjin Lee, Youngki Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16112v1.pdf)  
  Keywords: dynamic, 4d, gaussian splatting, ar, mapping  
- **[iGaussian: Real-Time Camera Pose Estimation via Feed-Forward 3D Gaussian Splatting Inversion](https://arxiv.org/abs/2511.14149v1)**  
  Authors: Hao Wang, Linqing Zhao, Xiuwei Xu, Jiwen Lu, Haibin Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14149v1.pdf)  
  Keywords: tracking, robotics, nerf, ar, gaussian splatting, lighting, head, slam, 3d gaussian  
- **[GUIDE: Gaussian Unified Instance Detection for Enhanced Obstacle Perception in Autonomous Driving](https://arxiv.org/abs/2511.12941v1)**  
  Authors: Chunyong Hu, Qi Luo, Jianyun Xu, Song Wang, Qiang Li, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12941v1.pdf)  
  Keywords: autonomous driving, tracking, 3d gaussian, ar  
- **[Neo: Real-Time On-Device 3D Gaussian Splatting with Reuse-and-Update Sorting Acceleration](https://arxiv.org/abs/2511.12930v1)**  
  Authors: Changhun Oh, Seongryong Oh, Jinwoo Hwang, Yoonsung Kim, Hardik Sharma, Jongse Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12930v1.pdf)  
  Keywords: tracking, ar, gaussian splatting, efficient, 3d gaussian, acceleration, vr  
- **[Reconstructing 3D Scenes in Native High Dynamic Range](https://arxiv.org/abs/2511.12895v1)**  
  Authors: Kaixuan Zhang, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12895v1.pdf)  
  Keywords: dynamic, ar, 3d reconstruction, gaussian splatting, 3d gaussian, mapping  
- **[FastGS: Training 3D Gaussian Splatting in 100 Seconds](https://arxiv.org/abs/2511.04283v1)**  
  Authors: Shiwei Ren, Tianci Wen, Yongchun Fang, Biao Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04283v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fastgs.github.io/)  
  Keywords: dynamic, nerf, fast, ar, gaussian splatting, localization, sparse-view, face, efficient, head, 3d gaussian, acceleration, mapping  
- **[WildfireX-SLAM: A Large-scale Low-altitude RGB-D Dataset for Wildfire SLAM and Beyond](https://arxiv.org/abs/2510.27133v1)**  
  Authors: Zhicong Sun, Jacqueline Lo, Jinxing Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.27133v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zhicongsun.github.io/wildfirexslam.)  
  Keywords: ar, gaussian splatting, localization, slam, 3d gaussian, mapping  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: motion, ar, geometry, gaussian splatting, outdoor, slam, 3d gaussian, understanding, mapping  

### Scene Understanding

*Showing the latest 50 out of 199 papers*

- **[Upsample Anything: A Simple and Hard to Beat Baseline for Feature Upsampling](https://arxiv.org/abs/2511.16301v1)**  
  Authors: Minseok Seo, Mark Hamilton, Changick Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16301v1.pdf)  
  Keywords: lightweight, segmentation, gaussian splatting, semantic, ar  
- **[LEGO-SLAM: Language-Embedded Gaussian Optimization SLAM](https://arxiv.org/abs/2511.16144v1)**  
  Authors: Sibaek Lee, Seongbo Ha, Kyeongsu Kang, Joonyeol Choi, Seungjun Tak, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.16144v1.pdf)  
  Keywords: tracking, compact, ar, gaussian splatting, localization, semantic, head, slam, 3d gaussian, understanding, mapping  
- **[Gaussian See, Gaussian Do: Semantic 3D Motion Transfer from Multiview Video](https://arxiv.org/abs/2511.14848v1)**  
  Authors: Yarin Bekor, Gal Michael Harari, Or Perel, Or Litany  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.14848v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsgd-motiontransfer.github.io/)  
  Keywords: motion, dynamic, ar, 4d, gaussian splatting, semantic, 3d gaussian  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: geometry, segmentation, gaussian splatting, high-fidelity, lighting, outdoor, relighting, semantic, illumination, face, efficient, ar  
- **[SplatSearch: Instance Image Goal Navigation for Mobile Robots using 3D Gaussian Splatting and Diffusion Models](https://arxiv.org/abs/2511.12972v1)**  
  Authors: Siddarth Narasimhan, Matthew Lisondra, Haitong Wang, Goldie Nejat  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.12972v1.pdf)  
  Keywords: ar, gaussian splatting, sparse-view, semantic, 3d gaussian  
- **[RealisticDreamer: Guidance Score Distillation for Few-shot Gaussian Splatting](https://arxiv.org/abs/2511.11213v1)**  
  Authors: Ruocheng Wu, Haolan He, Yufei Wang, Zhihao Li, Bihan Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.11213v1.pdf)  
  Keywords: motion, ar, geometry, real-time rendering, gaussian splatting, few-shot, semantic, 3d gaussian  
- **[OUGS: Active View Selection via Object-aware Uncertainty Estimation in 3DGS](https://arxiv.org/abs/2511.09397v1)**  
  Authors: Haiyi Li, Qi Chen, Denis Kalkofen, Hsiang-Ting Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.09397v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, high-fidelity, semantic, efficient, 3d gaussian  
- **[Inpaint360GS: Efficient Object-Aware 3D Inpainting via Gaussian Splatting for 360° Scenes](https://arxiv.org/abs/2511.06457v1)**  
  Authors: Shaoxiang Wang, Shihong Zhang, Christen Millerdurai, Rüdiger Westermann, Didier Stricker, Alain Pagani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06457v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dfki-av.github.io/inpaint360gs/)  
  Keywords: nerf, ar, segmentation, gaussian splatting, high-fidelity, efficient, 3d gaussian  
- **[4D3R: Motion-Aware Neural Reconstruction and Rendering of Dynamic Scenes from Monocular Videos](https://arxiv.org/abs/2511.05229v1)**  
  Authors: Mengqi Guo, Bo Xu, Yanyan Li, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.05229v1.pdf)  
  Keywords: dynamic, nerf, motion, ar, 4d, geometry, segmentation, gaussian splatting, efficient, deformation, 3d gaussian, neural rendering  
- **[3D Gaussian Point Encoders](https://arxiv.org/abs/2511.04797v1)**  
  Authors: Jim James, Ben Wilson, Simon Lucey, James Hays  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04797v1.pdf)  
  Keywords: lightweight, recognition, nerf, fast, 3d reconstruction, ar, geometry, gaussian splatting, efficient, 3d gaussian  



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