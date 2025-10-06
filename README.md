# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-10-06 00:53:13

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

- [3DGS Surveys](#3dgs-surveys) (21 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (259 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (329 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (386 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (73 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (316 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (74 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (411 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (163 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (16 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (116 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (153 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (195 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, slam, fast, efficient, ar, neural rendering, nerf, understanding, 3d gaussian  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: semantic, gaussian splatting, survey, ar, segmentation, nerf, understanding, lighting, compact, 3d gaussian, high-fidelity  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: semantic, gaussian splatting, survey, efficient, ar, nerf, understanding, robotics, 3d gaussian  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: gaussian splatting, survey, ar, nerf, robotics, human, 3d gaussian  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: gaussian splatting, geometry, survey, ar, sparse-view, nerf, 3d reconstruction, robotics, vr, motion, 3d gaussian  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v3)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Kaichen Zhou, Paul Pu Liang, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v3.pdf)  
  Keywords: robotics, gaussian splatting, survey, slam, fast, dynamic, ar, nerf, 3d reconstruction, lighting, vr, human, 3d gaussian  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: outdoor, gaussian splatting, survey, dynamic, efficient, ar, nerf, autonomous driving, face, 3d gaussian, high-fidelity  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: gaussian splatting, survey, ar, neural rendering, nerf, 3d reconstruction, robotics, vr, autonomous driving, 3d gaussian, high-fidelity  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: outdoor, gaussian splatting, semantic, survey, efficient, ar, segmentation, neural rendering, 3d reconstruction, understanding, 3d gaussian, high-fidelity  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: semantic, gaussian splatting, survey, slam, localization, mapping, efficient, ar, segmentation, nerf, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 259 papers*

- **[ROI-GS: Interest-based Local Quality 3D Gaussian Splatting](https://arxiv.org/abs/2510.01978v1)**  
  Authors: Quoc-Anh Bui, Gilles Rougeron, Géraldine Morin, Simone Gasparini  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01978v1.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, 3d gaussian, high-fidelity  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[LLM-Powered Code Analysis and Optimization for Gaussian Splatting
  Kernels](https://arxiv.org/abs/2509.25626v1)**  
  Authors: Yi Hu, Huiyang Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25626v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, ar, nerf, 3d gaussian  
- **[GaussianLens: Localized High-Resolution Reconstruction via On-Demand
  Gaussian Densification](https://arxiv.org/abs/2509.25603v1)**  
  Authors: Yijia Weng, Zhicheng Wang, Songyou Peng, Saining Xie, Howard Zhou, Leonidas J. Guibas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25603v1.pdf)  
  Keywords: gaussian splatting, fast, sparse view, ar, human, 3d gaussian  
- **[Triangle Splatting+: Differentiable Rendering with Opaque Triangles](https://arxiv.org/abs/2509.25122v1)**  
  Authors: Jan Held, Renaud Vandeghen, Sanghyun Son, Daniel Rebain, Matheus Gadelha, Yi Zhou, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25122v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://trianglesplatting2.github.io/trianglesplatting2/.)  
  Keywords: real-time rendering, gaussian splatting, fast, efficient, ar, head, nerf, vr, 3d gaussian  
- **[GEM: 3D Gaussian Splatting for Efficient and Accurate Cryo-EM
  Reconstruction](https://arxiv.org/abs/2509.25075v2)**  
  Authors: Huaizhi Qu, Xiao Wang, Gengwei Zhang, Jie Peng, Tianlong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25075v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, nerf, 3d reconstruction, compact, 3d gaussian  
- **[Proxy-GS: Efficient 3D Gaussian Splatting via Proxy Mesh](https://arxiv.org/abs/2509.24421v2)**  
  Authors: Yuanyuan Gao, Yuning Gong, Yifei Liu, Li Jingfeng, Zhihang Zhong, Dingwen Zhang, Yanci Zhang, Dan Xu, Xiao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24421v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, face, 3d gaussian  
- **[CrashSplat: 2D to 3D Vehicle Damage Segmentation in Gaussian Splatting](https://arxiv.org/abs/2509.23947v1)**  
  Authors: Dragoş-Andrei Chileban, Andrei-Ştefan Bulzan, Cosmin Cernǎzanu-Glǎvan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23947v1.pdf)  
  Keywords: gaussian splatting, fast, ar, segmentation, 3d reconstruction, motion, 3d gaussian  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, slam, fast, efficient, ar, neural rendering, nerf, understanding, 3d gaussian  
- **[Vision-Language Alignment from Compressed Image Representations using 2D
  Gaussian Splatting](https://arxiv.org/abs/2509.22615v1)**  
  Authors: Yasmine Omri, Connor Ding, Tsachy Weissman, Thierry Tambe  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22615v1.pdf)  
  Keywords: semantic, gaussian splatting, fast, lightweight, efficient, ar, compact  

### Applications

*Showing the latest 50 out of 995 papers*

- **[StealthAttack: Robust 3D Gaussian Splatting Poisoning via Density-Guided
  Illusions](https://arxiv.org/abs/2510.02314v1)**  
  Authors: Bo-Hsu Ke, You-Zhe Xie, Yu-Lun Liu, Wei-Chen Chiu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hentci.github.io/stealthattack/)  
  Keywords: gaussian splatting, nerf, ar, 3d gaussian  
- **[Performance-Guided Refinement for Visual Aerial Navigation using
  Editable Gaussian Splatting in FalconGym 2.0](https://arxiv.org/abs/2510.02248v1)**  
  Authors: Yan Miao, Ege Yuceel, Georgios Fainekos, Bardh Hoxha, Hideki Okamoto, Sayan Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02248v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, ar  
- **[Spec-Gloss Surfels and Normal-Diffuse Priors for Relightable Glossy
  Objects](https://arxiv.org/abs/2510.02069v1)**  
  Authors: Georgios Kouros, Minye Wu, Tinne Tuytelaars  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02069v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, dynamic, ar, relightable, neural rendering, lighting, face, illumination  
- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[4DGS-Craft: Consistent and Interactive 4D Gaussian Splatting Editing](https://arxiv.org/abs/2510.01991v1)**  
  Authors: Lei Liu, Can Wang, Zhenghao Chen, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01991v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, ar, understanding, face  
- **[ROI-GS: Interest-based Local Quality 3D Gaussian Splatting](https://arxiv.org/abs/2510.01978v1)**  
  Authors: Quoc-Anh Bui, Gilles Rougeron, Géraldine Morin, Simone Gasparini  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01978v1.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, 3d gaussian, high-fidelity  
- **[GreenhouseSplat: A Dataset of Photorealistic Greenhouse Simulations for
  Mobile Robotics](https://arxiv.org/abs/2510.01848v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01848v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, localization  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust
  Physics-Based Dynamics](https://arxiv.org/abs/2510.01619v1)**  
  Authors: Changmin Lee, Jihyun Lee, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://KAISTChangmin.github.io/MPMAvatar/)  
  Keywords: gaussian splatting, avatar, dynamic, body, ar, animation, shadow, human, deformation, 3d gaussian, high-fidelity  
- **[HART: Human Aligned Reconstruction Transformer](https://arxiv.org/abs/2509.26621v1)**  
  Authors: Xiyi Chen, Shaofei Wang, Marko Mihajlovic, Taewon Kang, Sergey Prokudin, Ming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26621v1.pdf)  
  Keywords: geometry, ar, body, sparse-view, human  

### Avatar Generation

*Showing the latest 50 out of 329 papers*

- **[Spec-Gloss Surfels and Normal-Diffuse Priors for Relightable Glossy
  Objects](https://arxiv.org/abs/2510.02069v1)**  
  Authors: Georgios Kouros, Minye Wu, Tinne Tuytelaars  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02069v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, dynamic, ar, relightable, neural rendering, lighting, face, illumination  
- **[4DGS-Craft: Consistent and Interactive 4D Gaussian Splatting Editing](https://arxiv.org/abs/2510.01991v1)**  
  Authors: Lei Liu, Can Wang, Zhenghao Chen, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01991v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, ar, understanding, face  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust
  Physics-Based Dynamics](https://arxiv.org/abs/2510.01619v1)**  
  Authors: Changmin Lee, Jihyun Lee, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://KAISTChangmin.github.io/MPMAvatar/)  
  Keywords: gaussian splatting, avatar, dynamic, body, ar, animation, shadow, human, deformation, 3d gaussian, high-fidelity  
- **[HART: Human Aligned Reconstruction Transformer](https://arxiv.org/abs/2509.26621v1)**  
  Authors: Xiyi Chen, Shaofei Wang, Marko Mihajlovic, Taewon Kang, Sergey Prokudin, Ming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26621v1.pdf)  
  Keywords: geometry, ar, body, sparse-view, human  
- **[GaussianLens: Localized High-Resolution Reconstruction via On-Demand
  Gaussian Densification](https://arxiv.org/abs/2509.25603v1)**  
  Authors: Yijia Weng, Zhicheng Wang, Songyou Peng, Saining Xie, Howard Zhou, Leonidas J. Guibas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25603v1.pdf)  
  Keywords: gaussian splatting, fast, sparse view, ar, human, 3d gaussian  
- **[Triangle Splatting+: Differentiable Rendering with Opaque Triangles](https://arxiv.org/abs/2509.25122v1)**  
  Authors: Jan Held, Renaud Vandeghen, Sanghyun Son, Daniel Rebain, Matheus Gadelha, Yi Zhou, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25122v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://trianglesplatting2.github.io/trianglesplatting2/.)  
  Keywords: real-time rendering, gaussian splatting, fast, efficient, ar, head, nerf, vr, 3d gaussian  
- **[GEM: 3D Gaussian Splatting for Efficient and Accurate Cryo-EM
  Reconstruction](https://arxiv.org/abs/2509.25075v2)**  
  Authors: Huaizhi Qu, Xiao Wang, Gengwei Zhang, Jie Peng, Tianlong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25075v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, nerf, 3d reconstruction, compact, 3d gaussian  
- **[Proxy-GS: Efficient 3D Gaussian Splatting via Proxy Mesh](https://arxiv.org/abs/2509.24421v2)**  
  Authors: Yuanyuan Gao, Yuning Gong, Yifei Liu, Li Jingfeng, Zhihang Zhong, Dingwen Zhang, Yanci Zhang, Dan Xu, Xiao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24421v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, face, 3d gaussian  
- **[OMeGa: Joint Optimization of Explicit Meshes and Gaussian Splats for
  Robust Scene-Level Surface Reconstruction](https://arxiv.org/abs/2509.24308v1)**  
  Authors: Yuhang Cao, Haojun Yan, Danya Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24308v1.pdf)  
  Keywords: gaussian splatting, geometry, ar, neural rendering, face  

### Dynamic Scene

*Showing the latest 50 out of 386 papers*

- **[Performance-Guided Refinement for Visual Aerial Navigation using
  Editable Gaussian Splatting in FalconGym 2.0](https://arxiv.org/abs/2510.02248v1)**  
  Authors: Yan Miao, Ege Yuceel, Georgios Fainekos, Bardh Hoxha, Hideki Okamoto, Sayan Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02248v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, ar  
- **[Spec-Gloss Surfels and Normal-Diffuse Priors for Relightable Glossy
  Objects](https://arxiv.org/abs/2510.02069v1)**  
  Authors: Georgios Kouros, Minye Wu, Tinne Tuytelaars  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02069v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, dynamic, ar, relightable, neural rendering, lighting, face, illumination  
- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[4DGS-Craft: Consistent and Interactive 4D Gaussian Splatting Editing](https://arxiv.org/abs/2510.01991v1)**  
  Authors: Lei Liu, Can Wang, Zhenghao Chen, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01991v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, ar, understanding, face  
- **[MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust
  Physics-Based Dynamics](https://arxiv.org/abs/2510.01619v1)**  
  Authors: Changmin Lee, Jihyun Lee, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://KAISTChangmin.github.io/MPMAvatar/)  
  Keywords: gaussian splatting, avatar, dynamic, body, ar, animation, shadow, human, deformation, 3d gaussian, high-fidelity  
- **[CrashSplat: 2D to 3D Vehicle Damage Segmentation in Gaussian Splatting](https://arxiv.org/abs/2509.23947v1)**  
  Authors: Dragoş-Andrei Chileban, Andrei-Ştefan Bulzan, Cosmin Cernǎzanu-Glǎvan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23947v1.pdf)  
  Keywords: gaussian splatting, fast, ar, segmentation, 3d reconstruction, motion, 3d gaussian  
- **[Orientation-anchored Hyper-Gaussian for 4D Reconstruction from Casual
  Videos](https://arxiv.org/abs/2509.23492v1)**  
  Authors: Junyi Wu, Jiachen Tao, Haoxuan Wang, Gaowen Liu, Ramana Rao Kompella, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23492v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, dynamic, ar, motion, deformation, 3d gaussian  
- **[Large Material Gaussian Model for Relightable 3D Generation](https://arxiv.org/abs/2509.22112v1)**  
  Authors: Jingrui Ye, Lingting Zhu, Runze Zhang, Zeyu Hu, Yingda Yin, Lanjiong Li, Lequan Yu, Qingmin Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22112v1.pdf)  
  Keywords: gaussian splatting, relighting, dynamic, efficient, ar, relightable, lighting, 3d gaussian  
- **[Drag4D: Align Your Motion with Text-Driven 3D Scene Generation](https://arxiv.org/abs/2509.21888v1)**  
  Authors: Minjun Kang, Inkyu Shin, Taeyeop Lee, In So Kweon, Kuk-Jin Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.21888v1.pdf)  
  Keywords: gaussian splatting, 4d, ar, 3d reconstruction, motion  
- **[Dynamic Novel View Synthesis in High Dynamic Range](https://arxiv.org/abs/2509.21853v2)**  
  Authors: Kaixuan Zhang, Zhipeng Xiong, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.21853v2.pdf)  
  Keywords: gaussian splatting, mapping, 4d, dynamic, ar, lighting  

### Few-shot

*Showing the latest 50 out of 73 papers*

- **[HART: Human Aligned Reconstruction Transformer](https://arxiv.org/abs/2509.26621v1)**  
  Authors: Xiyi Chen, Shaofei Wang, Marko Mihajlovic, Taewon Kang, Sergey Prokudin, Ming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26621v1.pdf)  
  Keywords: geometry, ar, body, sparse-view, human  
- **[GaussianLens: Localized High-Resolution Reconstruction via On-Demand
  Gaussian Densification](https://arxiv.org/abs/2509.25603v1)**  
  Authors: Yijia Weng, Zhicheng Wang, Songyou Peng, Saining Xie, Howard Zhou, Leonidas J. Guibas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25603v1.pdf)  
  Keywords: gaussian splatting, fast, sparse view, ar, human, 3d gaussian  
- **[DWGS: Enhancing Sparse-View Gaussian Splatting with Hybrid-Loss Depth
  Estimation and Bidirectional Warping](https://arxiv.org/abs/2509.24893v1)**  
  Authors: Yu Ma, Guoliang Wei, Yue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24893v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, sparse-view, 3d reconstruction, 3d gaussian, high-fidelity  
- **[OracleGS: Grounding Generative Priors for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2509.23258v1)**  
  Authors: Atakan Topaloglu, Kunyi Li, Michael Niemeyer, Nassir Navab, A. Murat Tekalp, Federico Tombari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23258v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, sparse-view, nerf, 3d gaussian  
- **[WaveletGaussian: Wavelet-domain Diffusion for Sparse-view 3D Gaussian
  Object Reconstruction](https://arxiv.org/abs/2509.19073v1)**  
  Authors: Hung Nguyen, Runfa Li, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19073v1.pdf)  
  Keywords: gaussian splatting, lightweight, efficient, ar, sparse-view, nerf, 3d gaussian  
- **[FixingGS: Enhancing 3D Gaussian Splatting via Training-Free Score
  Distillation](https://arxiv.org/abs/2509.18759v1)**  
  Authors: Zhaorui Wang, Yi Gu, Deming Zhou, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18759v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, sparse-view, 3d reconstruction, 3d gaussian  
- **[SPFSplatV2: Efficient Self-Supervised Pose-Free 3D Gaussian Splatting
  from Sparse Views](https://arxiv.org/abs/2509.17246v1)**  
  Authors: Ranran Huang, Krystian Mikolajczyk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17246v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ranrhuang.github.io/spfsplatv2/.)  
  Keywords: gaussian splatting, sparse view, efficient, ar, 3d gaussian  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v3)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v3.pdf)  
  Keywords: semantic, gaussian splatting, geometry, ar, sparse-view, nerf, motion, 3d gaussian  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, sparse-view  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, geometry, fast, ar, sparse-view, segmentation, motion, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 316 papers*

- **[Performance-Guided Refinement for Visual Aerial Navigation using
  Editable Gaussian Splatting in FalconGym 2.0](https://arxiv.org/abs/2510.02248v1)**  
  Authors: Yan Miao, Ege Yuceel, Georgios Fainekos, Bardh Hoxha, Hideki Okamoto, Sayan Mitra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02248v1.pdf)  
  Keywords: gaussian splatting, geometry, dynamic, ar  
- **[Spec-Gloss Surfels and Normal-Diffuse Priors for Relightable Glossy
  Objects](https://arxiv.org/abs/2510.02069v1)**  
  Authors: Georgios Kouros, Minye Wu, Tinne Tuytelaars  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02069v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, dynamic, ar, relightable, neural rendering, lighting, face, illumination  
- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[4DGS-Craft: Consistent and Interactive 4D Gaussian Splatting Editing](https://arxiv.org/abs/2510.01991v1)**  
  Authors: Lei Liu, Can Wang, Zhenghao Chen, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01991v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, ar, understanding, face  
- **[HART: Human Aligned Reconstruction Transformer](https://arxiv.org/abs/2509.26621v1)**  
  Authors: Xiyi Chen, Shaofei Wang, Marko Mihajlovic, Taewon Kang, Sergey Prokudin, Ming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26621v1.pdf)  
  Keywords: geometry, ar, body, sparse-view, human  
- **[GEM: 3D Gaussian Splatting for Efficient and Accurate Cryo-EM
  Reconstruction](https://arxiv.org/abs/2509.25075v2)**  
  Authors: Huaizhi Qu, Xiao Wang, Gengwei Zhang, Jie Peng, Tianlong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25075v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, nerf, 3d reconstruction, compact, 3d gaussian  
- **[DWGS: Enhancing Sparse-View Gaussian Splatting with Hybrid-Loss Depth
  Estimation and Bidirectional Warping](https://arxiv.org/abs/2509.24893v1)**  
  Authors: Yu Ma, Guoliang Wei, Yue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24893v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, sparse-view, 3d reconstruction, 3d gaussian, high-fidelity  
- **[OMeGa: Joint Optimization of Explicit Meshes and Gaussian Splats for
  Robust Scene-Level Surface Reconstruction](https://arxiv.org/abs/2509.24308v1)**  
  Authors: Yuhang Cao, Haojun Yan, Danya Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24308v1.pdf)  
  Keywords: gaussian splatting, geometry, ar, neural rendering, face  
- **[CrashSplat: 2D to 3D Vehicle Damage Segmentation in Gaussian Splatting](https://arxiv.org/abs/2509.23947v1)**  
  Authors: Dragoş-Andrei Chileban, Andrei-Ştefan Bulzan, Cosmin Cernǎzanu-Glǎvan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23947v1.pdf)  
  Keywords: gaussian splatting, fast, ar, segmentation, 3d reconstruction, motion, 3d gaussian  
- **[Orientation-anchored Hyper-Gaussian for 4D Reconstruction from Casual
  Videos](https://arxiv.org/abs/2509.23492v1)**  
  Authors: Junyi Wu, Jiachen Tao, Haoxuan Wang, Gaowen Liu, Ramana Rao Kompella, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23492v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, dynamic, ar, motion, deformation, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 74 papers*

- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[LVT: Large-Scale Scene Reconstruction via Local View Transformers](https://arxiv.org/abs/2509.25001v1)**  
  Authors: Tooba Imtiaz, Lucy Chai, Kathryn Heal, Xuan Luo, Jungyeon Park, Jennifer Dy, John Flynn  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25001v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://toobaimt.github.io/lvt/.)  
  Keywords: ar, large scene, 3d gaussian  
- **[Aerial-Ground Image Feature Matching via 3D Gaussian Splatting-based
  Intermediate View Rendering](https://arxiv.org/abs/2509.19898v1)**  
  Authors: Jiangxue Yu, Hui Wang, San Jiang, Xing Zhang, Dejin Zhang, Qingquan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19898v1.pdf)  
  Keywords: gaussian splatting, ar, large scene, motion, 3d gaussian  
- **[FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS
  Models to LiDAR](https://arxiv.org/abs/2509.17390v1)**  
  Authors: Junzhe Wu, Yufei Jia, Yiyi Yan, Zhixing Chen, Tiao Tan, Zifan Wang, Guangyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17390v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, ar, robotics, autonomous driving, 3d gaussian, high-fidelity  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: outdoor, gaussian splatting, geometry, illumination, relighting, efficient, ar, relightable, efficient rendering, head, nerf, lighting, compact, 3d gaussian  
- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v3)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v3.pdf)  
  Keywords: gaussian splatting, dynamic, ar, large scene, motion  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: gaussian splatting, ar, large scene, 3d gaussian  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: outdoor, gaussian splatting, localization, ar, 3d gaussian  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: outdoor, gaussian splatting, geometry, relighting, sparse view, ar, lighting, autonomous driving, face, 3d gaussian  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: outdoor, gaussian splatting, 3d gaussian, ar, 3d reconstruction, understanding, lighting, illumination  

### Model Compression

*Showing the latest 50 out of 411 papers*

- **[ROI-GS: Interest-based Local Quality 3D Gaussian Splatting](https://arxiv.org/abs/2510.01978v1)**  
  Authors: Quoc-Anh Bui, Gilles Rougeron, Géraldine Morin, Simone Gasparini  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01978v1.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, 3d gaussian, high-fidelity  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[GaussEdit: Adaptive 3D Scene Editing with Text and Image Prompts](https://arxiv.org/abs/2509.26055v1)**  
  Authors: Zhenyu Shu, Junlong Yu, Kai Chao, Shiqing Xin, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.26055v1.pdf)  
  Keywords: gaussian splatting, ar, efficient, 3d gaussian  
- **[Triangle Splatting+: Differentiable Rendering with Opaque Triangles](https://arxiv.org/abs/2509.25122v1)**  
  Authors: Jan Held, Renaud Vandeghen, Sanghyun Son, Daniel Rebain, Matheus Gadelha, Yi Zhou, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25122v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://trianglesplatting2.github.io/trianglesplatting2/.)  
  Keywords: real-time rendering, gaussian splatting, fast, efficient, ar, head, nerf, vr, 3d gaussian  
- **[GEM: 3D Gaussian Splatting for Efficient and Accurate Cryo-EM
  Reconstruction](https://arxiv.org/abs/2509.25075v2)**  
  Authors: Huaizhi Qu, Xiao Wang, Gengwei Zhang, Jie Peng, Tianlong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.25075v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, nerf, 3d reconstruction, compact, 3d gaussian  
- **[ExGS: Extreme 3D Gaussian Compression with Diffusion Priors](https://arxiv.org/abs/2509.24758v2)**  
  Authors: Jiaqi Chen, Xinhao Ji, Yuanyuan Gao, Hao Li, Yuning Gong, Yifei Liu, Dan Xu, Zhihang Zhong, Dingwen Zhang, Xiao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24758v2.pdf)  
  Keywords: gaussian splatting, lightweight, efficient, ar, neural rendering, compression, 3d gaussian  
- **[Proxy-GS: Efficient 3D Gaussian Splatting via Proxy Mesh](https://arxiv.org/abs/2509.24421v2)**  
  Authors: Yuanyuan Gao, Yuning Gong, Yifei Liu, Li Jingfeng, Zhihang Zhong, Dingwen Zhang, Yanci Zhang, Dan Xu, Xiao Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24421v2.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, head, face, 3d gaussian  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, slam, fast, efficient, ar, neural rendering, nerf, understanding, 3d gaussian  
- **[Learning Unified Representation of 3D Gaussian Splatting](https://arxiv.org/abs/2509.22917v1)**  
  Authors: Yuelin Xin, Yuheng Liu, Xiaohui Xie, Xinke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22917v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, ar, 3d reconstruction, 3d gaussian  
- **[Vision-Language Alignment from Compressed Image Representations using 2D
  Gaussian Splatting](https://arxiv.org/abs/2509.22615v1)**  
  Authors: Yasmine Omri, Connor Ding, Tsachy Weissman, Thierry Tambe  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22615v1.pdf)  
  Keywords: semantic, gaussian splatting, fast, lightweight, efficient, ar, compact  

### Quality Enhancement

*Showing the latest 50 out of 163 papers*

- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[ROI-GS: Interest-based Local Quality 3D Gaussian Splatting](https://arxiv.org/abs/2510.01978v1)**  
  Authors: Quoc-Anh Bui, Gilles Rougeron, Géraldine Morin, Simone Gasparini  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01978v1.pdf)  
  Keywords: gaussian splatting, fast, efficient, ar, 3d gaussian, high-fidelity  
- **[LOBE-GS: Load-Balanced and Efficient 3D Gaussian Splatting for
  Large-Scale Scene Reconstruction](https://arxiv.org/abs/2510.01767v1)**  
  Authors: Sheng-Hsiang Hung, Ting-Yu Yen, Wei-Fang Sun, Simon See, Shih-Hsuan Hung, Hung-Kuo Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01767v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, lightweight, efficient, ar, head, 3d gaussian, high-fidelity  
- **[MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust
  Physics-Based Dynamics](https://arxiv.org/abs/2510.01619v1)**  
  Authors: Changmin Lee, Jihyun Lee, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://KAISTChangmin.github.io/MPMAvatar/)  
  Keywords: gaussian splatting, avatar, dynamic, body, ar, animation, shadow, human, deformation, 3d gaussian, high-fidelity  
- **[DWGS: Enhancing Sparse-View Gaussian Splatting with Hybrid-Loss Depth
  Estimation and Bidirectional Warping](https://arxiv.org/abs/2509.24893v1)**  
  Authors: Yu Ma, Guoliang Wei, Yue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.24893v1.pdf)  
  Keywords: gaussian splatting, sparse view, ar, sparse-view, 3d reconstruction, 3d gaussian, high-fidelity  
- **[DeblurSplat: SfM-free 3D Gaussian Splatting with Event Camera for Robust
  Deblurring](https://arxiv.org/abs/2509.18898v1)**  
  Authors: Pengteng Li, Yunfan Lu, Pinhao Song, Weiyu Guo, Huizai Yao, F. Richard Yu, Hui Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18898v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, motion, 3d gaussian, high-fidelity  
- **[EmbodiedSplat: Personalized Real-to-Sim-to-Real Navigation with Gaussian
  Splats from a Mobile Device](https://arxiv.org/abs/2509.17430v2)**  
  Authors: Gunjan Chhablani, Xiaomeng Ye, Muhammad Zubair Irshad, Zsolt Kira  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17430v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gchhablani.github.io/embodied-splat.)  
  Keywords: gaussian splatting, efficient, ar, 3d gaussian, high-fidelity  
- **[FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS
  Models to LiDAR](https://arxiv.org/abs/2509.17390v1)**  
  Authors: Junzhe Wu, Yufei Jia, Yiyi Yan, Zhixing Chen, Tiao Tan, Zifan Wang, Guangyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17390v1.pdf)  
  Keywords: outdoor, gaussian splatting, fast, ar, robotics, autonomous driving, 3d gaussian, high-fidelity  
- **[PGSTalker: Real-Time Audio-Driven Talking Head Generation via 3D
  Gaussian Splatting with Pixel-Aware Density Control](https://arxiv.org/abs/2509.16922v1)**  
  Authors: Tianheng Zhu, Yinfeng Yu, Liejun Wang, Fuchun Sun, Wendong Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16922v1.pdf)  
  Keywords: gaussian splatting, avatar, lightweight, dynamic, ar, head, nerf, deformation, 3d gaussian, high-fidelity  
- **[ConfidentSplat: Confidence-Weighted Depth Fusion for Accurate 3D
  Gaussian Splatting SLAM](https://arxiv.org/abs/2509.16863v1)**  
  Authors: Amanuel T. Dufera, Yuan-Li Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16863v1.pdf)  
  Keywords: gaussian splatting, geometry, slam, dynamic, efficient, ar, 3d gaussian, high-fidelity  

### Ray Tracing

- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, light transport, efficient, ar, lighting, global illumination, illumination  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: gaussian splatting, 4d, ray tracing, fast, dynamic, ar  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: gaussian splatting, geometry, illumination, relighting, reflection, ray tracing, ar, nerf, lighting, face, 3d gaussian, high-fidelity  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: outdoor, gaussian splatting, illumination, relighting, shadow, dynamic, ar, relightable, lighting, global illumination, face, 3d gaussian  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: gaussian splatting, dynamic, ar, lighting, face, 3d gaussian, path tracing  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, efficient, ar, relightable, efficient rendering, ray marching, lighting, face, 3d gaussian  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, ray tracing, efficient, ar, high-fidelity  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v2)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v2.pdf)  
  Keywords: gaussian splatting, geometry, avatar, relighting, ray tracing, fast, ar, relightable, lighting, shadow, human  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: gaussian splatting, relighting, ray tracing, efficient, ar, efficient rendering, acceleration, lighting, 3d gaussian  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: gaussian splatting, dynamic, efficient, ar, acceleration, ray marching, animation, compact, 3d gaussian  

### Relighting

*Showing the latest 50 out of 116 papers*

- **[Spec-Gloss Surfels and Normal-Diffuse Priors for Relightable Glossy
  Objects](https://arxiv.org/abs/2510.02069v1)**  
  Authors: Georgios Kouros, Minye Wu, Tinne Tuytelaars  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02069v1.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, dynamic, ar, relightable, neural rendering, lighting, face, illumination  
- **[MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust
  Physics-Based Dynamics](https://arxiv.org/abs/2510.01619v1)**  
  Authors: Changmin Lee, Jihyun Lee, Tae-Kyun Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01619v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://KAISTChangmin.github.io/MPMAvatar/)  
  Keywords: gaussian splatting, avatar, dynamic, body, ar, animation, shadow, human, deformation, 3d gaussian, high-fidelity  
- **[Large Material Gaussian Model for Relightable 3D Generation](https://arxiv.org/abs/2509.22112v1)**  
  Authors: Jingrui Ye, Lingting Zhu, Runze Zhang, Zeyu Hu, Yingda Yin, Lanjiong Li, Lequan Yu, Qingmin Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22112v1.pdf)  
  Keywords: gaussian splatting, relighting, dynamic, efficient, ar, relightable, lighting, 3d gaussian  
- **[Dynamic Novel View Synthesis in High Dynamic Range](https://arxiv.org/abs/2509.21853v2)**  
  Authors: Kaixuan Zhang, Zhipeng Xiong, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.21853v2.pdf)  
  Keywords: gaussian splatting, mapping, 4d, dynamic, ar, lighting  
- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: gaussian splatting, geometry, reflection, mapping, ar, nerf, 3d reconstruction, face, 3d gaussian  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: gaussian splatting, geometry, relighting, reflection, light transport, efficient, ar, lighting, global illumination, illumination  
- **[From Restoration to Reconstruction: Rethinking 3D Gaussian Splatting for
  Underwater Scenes](https://arxiv.org/abs/2509.17789v1)**  
  Authors: Guoxi Huang, Haoran Wang, Zipeng Qi, Wenjun Lu, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17789v1.pdf)  
  Keywords: gaussian splatting, lightweight, ar, nerf, 3d reconstruction, 3d gaussian, illumination  
- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: gaussian splatting, 4d, fast, efficient, ar, lighting, autonomous driving, 3d gaussian  
- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: gaussian splatting, reflection, ar, face, 3d gaussian  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: outdoor, gaussian splatting, geometry, illumination, relighting, efficient, ar, relightable, efficient rendering, head, nerf, lighting, compact, 3d gaussian  

### SLAM

*Showing the latest 50 out of 153 papers*

- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[GreenhouseSplat: A Dataset of Photorealistic Greenhouse Simulations for
  Mobile Robotics](https://arxiv.org/abs/2510.01848v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01848v1.pdf)  
  Keywords: robotics, gaussian splatting, ar, localization  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, slam, fast, efficient, ar, neural rendering, nerf, understanding, 3d gaussian  
- **[Learning Unified Representation of 3D Gaussian Splatting](https://arxiv.org/abs/2509.22917v1)**  
  Authors: Yuelin Xin, Yuheng Liu, Xiaohui Xie, Xinke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22917v1.pdf)  
  Keywords: gaussian splatting, mapping, efficient, ar, 3d reconstruction, 3d gaussian  
- **[Dynamic Novel View Synthesis in High Dynamic Range](https://arxiv.org/abs/2509.21853v2)**  
  Authors: Kaixuan Zhang, Zhipeng Xiong, Minxian Li, Mingwu Ren, Jiankang Deng, Xiatian Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.21853v2.pdf)  
  Keywords: gaussian splatting, mapping, 4d, dynamic, ar, lighting  
- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: gaussian splatting, geometry, reflection, mapping, ar, nerf, 3d reconstruction, face, 3d gaussian  
- **[ConfidentSplat: Confidence-Weighted Depth Fusion for Accurate 3D
  Gaussian Splatting SLAM](https://arxiv.org/abs/2509.16863v1)**  
  Authors: Amanuel T. Dufera, Yuan-Li Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16863v1.pdf)  
  Keywords: gaussian splatting, geometry, slam, dynamic, efficient, ar, 3d gaussian, high-fidelity  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v2)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v2.pdf)  
  Keywords: gaussian splatting, slam, mapping, ar, robotics, autonomous driving, 3d gaussian, high-fidelity  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: gaussian splatting, slam, efficient, ar, face, 3d gaussian  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: gaussian splatting, avatar, mapping, fast, efficient, ar, human, deformation  

### Scene Understanding

*Showing the latest 50 out of 195 papers*

- **[GaussianMorphing: Mesh-Guided 3D Gaussians for Semantic-Aware Object
  Morphing](https://arxiv.org/abs/2510.02034v1)**  
  Authors: Mengtian Li, Yunshu Bai, Yimin Chu, Yijun Shen, Zhongmei Li, Weifeng Ge, Zhifeng Xie, Chaofeng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.02034v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://baiyunshu.github.io/GAUSSIANMORPHING.github.io/)  
  Keywords: semantic, gaussian splatting, geometry, mapping, ar, deformation, 3d gaussian, high-fidelity  
- **[4DGS-Craft: Consistent and Interactive 4D Gaussian Splatting Editing](https://arxiv.org/abs/2510.01991v1)**  
  Authors: Lei Liu, Can Wang, Zhenghao Chen, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.01991v1.pdf)  
  Keywords: gaussian splatting, geometry, 4d, ar, understanding, face  
- **[CrashSplat: 2D to 3D Vehicle Damage Segmentation in Gaussian Splatting](https://arxiv.org/abs/2509.23947v1)**  
  Authors: Dragoş-Andrei Chileban, Andrei-Ştefan Bulzan, Cosmin Cernǎzanu-Glǎvan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23947v1.pdf)  
  Keywords: gaussian splatting, fast, ar, segmentation, 3d reconstruction, motion, 3d gaussian  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene
  Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, survey, slam, fast, efficient, ar, neural rendering, nerf, understanding, 3d gaussian  
- **[Vision-Language Alignment from Compressed Image Representations using 2D
  Gaussian Splatting](https://arxiv.org/abs/2509.22615v1)**  
  Authors: Yasmine Omri, Connor Ding, Tsachy Weissman, Thierry Tambe  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22615v1.pdf)  
  Keywords: semantic, gaussian splatting, fast, lightweight, efficient, ar, compact  
- **[Polysemous Language Gaussian Splatting via Matching-based Mask Lifting](https://arxiv.org/abs/2509.22225v1)**  
  Authors: Jiayu Ding, Xinpeng Liu, Zhiyi Pan, Shiqiang Long, Ge Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.22225v1.pdf)  
  Keywords: semantic, gaussian splatting, ar, segmentation, understanding, 3d gaussian  
- **[4D Driving Scene Generation With Stereo Forcing](https://arxiv.org/abs/2509.20251v1)**  
  Authors: Hao Lu, Zhuang Ma, Guangfeng Jiang, Wenhang Ge, Bohan Li, Yuzhan Cai, Wenzhao Zheng, Yunpeng Zhang, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.20251v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiangxb98.github.io/PhiGensis}{PhiGensis}.)  
  Keywords: semantic, gaussian splatting, geometry, 4d, dynamic, ar, motion  
- **[SINGER: An Onboard Generalist Vision-Language Navigation Policy for
  Drones](https://arxiv.org/abs/2509.18610v1)**  
  Authors: Maximilian Adang, JunEn Low, Ola Shorinwa, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18610v1.pdf)  
  Keywords: semantic, gaussian splatting, lightweight, efficient, ar  
- **[Event-guided 3D Gaussian Splatting for Dynamic Human and Scene
  Reconstruction](https://arxiv.org/abs/2509.18566v1)**  
  Authors: Xiaoting Yin, Hao Shi, Kailun Yang, Jiajun Zhai, Shangwei Guo, Lin Wang, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18566v1.pdf)  
  Keywords: semantic, gaussian splatting, fast, dynamic, ar, human, animation, motion, deformation, 3d gaussian  
- **[ST-GS: Vision-Based 3D Semantic Occupancy Prediction with
  Spatial-Temporal Gaussian Splatting](https://arxiv.org/abs/2509.16552v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16552v1.pdf)  
  Keywords: semantic, gaussian splatting, geometry, ar, head, understanding, autonomous driving  



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