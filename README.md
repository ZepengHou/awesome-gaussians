# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-07-13 01:02:48

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

- [3DGS Surveys](#3dgs-surveys) (18 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (278 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (329 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (402 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (69 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (315 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (65 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (397 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (163 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (15 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (108 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (157 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (188 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: 3d gaussian, nerf, dynamic, autonomous driving, outdoor, high-fidelity, survey, ar, gaussian splatting, face, efficient  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: 3d gaussian, neural rendering, nerf, autonomous driving, 3d reconstruction, high-fidelity, survey, ar, robotics, gaussian splatting, vr  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: 3d gaussian, neural rendering, understanding, 3d reconstruction, outdoor, high-fidelity, survey, ar, gaussian splatting, segmentation, efficient, semantic  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: 3d gaussian, nerf, localization, survey, ar, mapping, slam, gaussian splatting, segmentation, efficient, semantic  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: dynamic, 3d gaussian, body, understanding, survey, ar, motion, gaussian splatting, 4d  
- **[A Survey of 3D Reconstruction with Event Cameras](https://arxiv.org/abs/2505.08438v2)**  
  Authors: Chuanzhi Xu, Haoxian Zhou, Langyi Chen, Haodong Chen, Ying Zhou, Vera Chung, Qiang Qu, Weidong Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.08438v2.pdf)  
  Keywords: 3d gaussian, neural rendering, nerf, dynamic, autonomous driving, 3d reconstruction, survey, ar, robotics, motion, geometry, gaussian splatting, illumination  
- **[UltraGauss: Ultrafast Gaussian Reconstruction of 3D Ultrasound Volumes](https://arxiv.org/abs/2505.05643v1)**  
  Authors: Mark C. Eid, Ana I. L. Namburete, João F. Henriques  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.05643v1.pdf)  
  Keywords: 3d reconstruction, fast, survey, ar, gaussian splatting, efficient  
- **[Visual enhancement and 3D representation for underwater scenes: a review](https://arxiv.org/abs/2505.01869v1)**  
  Authors: Guoxi Huang, Haoran Wang, Brett Seymour, Evan Kovacs, John Ellerbrock, Dave Blackham, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.01869v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, lighting, survey  
- **[A Survey on 3D Reconstruction Techniques in Plant Phenotyping: From
  Classical Methods to Neural Radiance Fields (NeRF), 3D Gaussian Splatting
  (3DGS), and Beyond](https://arxiv.org/abs/2505.00737v1)**  
  Authors: Jiajia Li, Xinda Qi, Seyed Hamidreza Nabaei, Meiqi Liu, Dong Chen, Xin Zhang, Xunyuan Yin, Zhaojian Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.00737v1.pdf)  
  Keywords: sparse view, 3d gaussian, nerf, understanding, 3d reconstruction, outdoor, survey, ar, geometry, gaussian splatting, face  
- **[Digital Twin Generation from Visual Data: A Survey](https://arxiv.org/abs/2504.13159v1)**  
  Authors: Andrew Melnik, Benjamin Alt, Giang Nguyen, Artur Wilkowski, Maciej Stefańczyk, Qirui Wu, Sinan Harms, Helge Rhodin, Manolis Savva, Michael Beetz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.13159v1.pdf)  
  Keywords: 3d gaussian, survey, ar, lighting, robotics, gaussian splatting, segmentation, semantic  

### Acceleration

*Showing the latest 50 out of 278 papers*

- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, deformation, gaussian splatting, face  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: 3d gaussian, fast, ar, compression, gaussian splatting  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: fast, ar, gaussian splatting, efficient, semantic, high quality  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, 3d gaussian, neural rendering, human, head, ar, tracking, vr, gaussian splatting, face, efficient rendering, efficient  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: 3d gaussian, fast, lightweight, ar, slam, gaussian splatting  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: 3d gaussian, dynamic, urban scene, autonomous driving, high-fidelity, ar, real-time rendering, gaussian splatting  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: 3d gaussian, fast, high-fidelity, ar, avatar, lighting, deformation, reflection, gaussian splatting, face  
- **[A LoD of Gaussians: Unified Training and Rendering for Ultra-Large Scale
  Reconstruction with External Memory](https://arxiv.org/abs/2507.01110v2)**  
  Authors: Felix Windisch, Lukas Radl, Thomas Köhler, Michael Steiner, Dieter Schmalstieg, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.01110v2.pdf)  
  Keywords: dynamic, lightweight, ar, real-time rendering, gaussian splatting, vr, efficient  
- **[GaussianVLM: Scene-centric 3D Vision-Language Models using
  Language-aligned Gaussian Splats for Embodied Reasoning and Beyond](https://arxiv.org/abs/2507.00886v1)**  
  Authors: Anna-Maria Halacheva, Jan-Nico Zaech, Xi Wang, Danda Pani Paudel, Luc Van Gool  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00886v1.pdf)  
  Keywords: compact, 3d gaussian, understanding, fast, ar, gaussian splatting  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: 3d gaussian, dynamic, fast, high-fidelity, ar, real-time rendering, geometry, gaussian splatting, face  

### Applications

*Showing the latest 50 out of 995 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: 3d gaussian, relighting, ar, lighting, reflection, gaussian splatting, efficient  
- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, 3d gaussian, nerf, understanding, outdoor, ar, motion, gaussian splatting, segmentation, 4d  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: compact, dynamic, 3d gaussian, ar, deformation, motion, gaussian splatting, efficient, 4d  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: 3d gaussian, ar, lighting, gaussian splatting, segmentation  
- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, deformation, gaussian splatting, face  
- **[Photometric Stereo using Gaussian Splatting and inverse rendering](https://arxiv.org/abs/2507.06684v1)**  
  Authors: Matéo Ducastel, David Tschumperlé, Yvain Quéau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06684v1.pdf)  
  Keywords: gaussian splatting, ar  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: 3d gaussian, fast, ar, compression, gaussian splatting  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, medical, understanding, ar, deformation, gaussian splatting  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: fast, ar, gaussian splatting, efficient, semantic, high quality  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, motion, geometry, gaussian splatting  

### Avatar Generation

*Showing the latest 50 out of 329 papers*

- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, deformation, gaussian splatting, face  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: 3d gaussian, nerf, ar, geometry, reflection, gaussian splatting, face, efficient  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: 3d gaussian, human, animation, high-fidelity, ar, avatar, gaussian splatting, recognition  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: nerf, high-fidelity, ar, vr, motion, geometry, gaussian splatting, face, segmentation  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: 3d gaussian, nerf, ar, geometry, gaussian splatting, face, efficient  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, 3d gaussian, neural rendering, human, head, ar, tracking, vr, gaussian splatting, face, efficient rendering, efficient  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: 3d gaussian, fast, high-fidelity, ar, avatar, lighting, deformation, reflection, gaussian splatting, face  
- **[Masks make discriminative models great again!](https://arxiv.org/abs/2507.00916v1)**  
  Authors: Tianshi Cao, Marie-Julie Rakotosaona, Ben Poole, Federico Tombari, Michael Niemeyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00916v1.pdf)  
  Keywords: 3d gaussian, ar, face  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: 3d gaussian, dynamic, fast, high-fidelity, ar, real-time rendering, geometry, gaussian splatting, face  
- **[MILo: Mesh-In-the-Loop Gaussian Splatting for Detailed and Efficient
  Surface Reconstruction](https://arxiv.org/abs/2506.24096v1)**  
  Authors: Antoine Guédon, Diego Gomez, Nissim Maruani, Bingchen Gong, George Drettakis, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.24096v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, geometry, gaussian splatting, face, efficient  

### Dynamic Scene

*Showing the latest 50 out of 402 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, 3d gaussian, nerf, understanding, outdoor, ar, motion, gaussian splatting, segmentation, 4d  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: compact, dynamic, 3d gaussian, ar, deformation, motion, gaussian splatting, efficient, 4d  
- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, deformation, gaussian splatting, face  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, medical, understanding, ar, deformation, gaussian splatting  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, motion, geometry, gaussian splatting  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: 3d gaussian, human, animation, high-fidelity, ar, avatar, gaussian splatting, recognition  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, ar, compression, motion, gaussian splatting, efficient  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: nerf, high-fidelity, ar, vr, motion, geometry, gaussian splatting, face, segmentation  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, deformation, geometry, gaussian splatting, semantic  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, 3d gaussian, neural rendering, human, head, ar, tracking, vr, gaussian splatting, face, efficient rendering, efficient  

### Few-shot

*Showing the latest 50 out of 69 papers*

- **[Particle-Grid Neural Dynamics for Learning Deformable Object Models from
  RGB-D Videos](https://arxiv.org/abs/2506.15680v1)**  
  Authors: Kaifeng Zhang, Baoyu Li, Kris Hauser, Yunzhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.15680v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kywind.github.io/pgnd)  
  Keywords: dynamic, sparse-view, ar, motion, gaussian splatting  
- **[PointGS: Point Attention-Aware Sparse View Synthesis with Gaussian
  Splatting](https://arxiv.org/abs/2506.10335v1)**  
  Authors: Lintao Xiang, Hongpei Zheng, Yating Huang, Qijun Yang, Hujun Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.10335v1.pdf)  
  Keywords: sparse view, 3d gaussian, nerf, few-shot, lightweight, ar, gaussian splatting  
- **[UniForward: Unified 3D Scene and Semantic Field Reconstruction via
  Feed-Forward Gaussian Splatting from Only Sparse-View Images](https://arxiv.org/abs/2506.09378v1)**  
  Authors: Qijian Tian, Xin Tan, Jingyu Gong, Yuan Xie, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.09378v1.pdf)  
  Keywords: 3d gaussian, understanding, sparse-view, ar, gaussian splatting, segmentation, semantic  
- **[ProSplat: Improved Feed-Forward 3D Gaussian Splatting for Wide-Baseline
  Sparse Views](https://arxiv.org/abs/2506.07670v1)**  
  Authors: Xiaohan Lu, Jiaye Fu, Jiaqi Zhang, Zetian Song, Chuanmin Jia, Siwei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.07670v1.pdf)  
  Keywords: sparse view, 3d gaussian, high-fidelity, ar, gaussian splatting  
- **[Learning Fine-Grained Geometry for Sparse-View Splatting via Cascade
  Depth Loss](https://arxiv.org/abs/2505.22279v1)**  
  Authors: Wenjun Lu, Haodong Chen, Anqi Yi, Yuk Ying Chung, Zhiyong Wang, Kun Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22279v1.pdf)  
  Keywords: 3d gaussian, nerf, sparse-view, ar, geometry, gaussian splatting, efficient  
- **[Intern-GS: Vision Model Guided Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2505.20729v1)**  
  Authors: Xiangyu Sun, Runnan Chen, Mingming Gong, Dong Xu, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.20729v1.pdf)  
  Keywords: 3d gaussian, sparse-view, ar, motion, gaussian splatting, face  
- **[Sparse2DGS: Sparse-View Surface Reconstruction using 2D Gaussian
  Splatting with Dense Point Cloud](https://arxiv.org/abs/2505.19854v2)**  
  Authors: Natsuki Takama, Shintaro Ito, Koichi Ito, Hwann-Tzong Chen, Takafumi Aoki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19854v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsisaoki.github.io/SPARSE2DGS/)  
  Keywords: 3d reconstruction, sparse-view, fast, ar, motion, gaussian splatting, face  
- **[Improving Novel view synthesis of 360$^\circ$ Scenes in Extremely Sparse
  Views by Jointly Training Hemisphere Sampled Synthetic Images](https://arxiv.org/abs/2505.19264v1)**  
  Authors: Guangan Chen, Anh Minh Truong, Hanhe Lin, Michiel Vlaminck, Wilfried Philips, Hiep Luong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19264v1.pdf)  
  Keywords: sparse view, 3d gaussian, sparse-view, ar, motion, gaussian splatting  
- **[SHaDe: Compact and Consistent Dynamic 3D Reconstruction via Tri-Plane
  Deformation and Latent Diffusion](https://arxiv.org/abs/2505.16535v1)**  
  Authors: Asrar Alruwayqi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.16535v1.pdf)  
  Keywords: compact, dynamic, 3d reconstruction, sparse-view, head, ar, deformation, motion, gaussian splatting, efficient, 4d  
- **[RUSplatting: Robust 3D Gaussian Splatting for Sparse-View Underwater
  Scene Reconstruction](https://arxiv.org/abs/2505.15737v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15737v1.pdf)  
  Keywords: 3d gaussian, sparse-view, high-fidelity, ar, robotics, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 315 papers*

- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, motion, geometry, gaussian splatting  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: 3d gaussian, nerf, ar, geometry, reflection, gaussian splatting, face, efficient  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: nerf, high-fidelity, ar, vr, motion, geometry, gaussian splatting, face, segmentation  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: 3d gaussian, nerf, ar, geometry, gaussian splatting, face, efficient  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, deformation, geometry, gaussian splatting, semantic  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: 3d gaussian, ar, mapping, lighting, geometry, reflection, gaussian splatting  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: 3d gaussian, dynamic, fast, high-fidelity, ar, real-time rendering, geometry, gaussian splatting, face  
- **[MILo: Mesh-In-the-Loop Gaussian Splatting for Detailed and Efficient
  Surface Reconstruction](https://arxiv.org/abs/2506.24096v1)**  
  Authors: Antoine Guédon, Diego Gomez, Nissim Maruani, Bingchen Gong, George Drettakis, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.24096v1.pdf)  
  Keywords: 3d gaussian, animation, fast, ar, geometry, gaussian splatting, face, efficient  
- **[GaVS: 3D-Grounded Video Stabilization via Temporally-Consistent Local
  Reconstruction and Rendering](https://arxiv.org/abs/2506.23957v1)**  
  Authors: Zinuo You, Stamatios Georgoulis, Anpei Chen, Siyu Tang, Dengxin Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23957v1.pdf)  
  Keywords: dynamic, ar, motion, geometry, gaussian splatting  
- **[AttentionGS: Towards Initialization-Free 3D Gaussian Splatting via
  Structural Attention](https://arxiv.org/abs/2506.23611v1)**  
  Authors: Ziao Liu, Zhenjia Li, Yifeng Shi, Xiangang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23611v1.pdf)  
  Keywords: 3d gaussian, nerf, 3d reconstruction, ar, motion, gaussian splatting, face, efficient rendering, efficient  

### Large Scene

*Showing the latest 50 out of 65 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, 3d gaussian, nerf, understanding, outdoor, ar, motion, gaussian splatting, segmentation, 4d  
- **[3DGS_LSR:Large_Scale Relocation for Autonomous Driving Based on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.05661v1)**  
  Authors: Haitao Lu, Haijier Chen, Haoze Liu, Shoujian Zhang, Bo Xu, Ziao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05661v1.pdf)  
  Keywords: 3d gaussian, autonomous driving, outdoor, ar, mapping, localization, gaussian splatting  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: 3d gaussian, dynamic, urban scene, autonomous driving, high-fidelity, ar, real-time rendering, gaussian splatting  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, 3d gaussian, outdoor, high-fidelity, ar, mapping, slam, gaussian splatting, tracking  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: 3d gaussian, dynamic, outdoor, high-fidelity, ar, mapping, lighting, geometry, slam, gaussian splatting, tracking, illumination  
- **[BézierGS: Dynamic Urban Scene Reconstruction with Bézier Curve
  Gaussian Splatting](https://arxiv.org/abs/2506.22099v3)**  
  Authors: Zipei Ma, Junzhe Jiang, Yurui Chen, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.22099v3.pdf)  
  Keywords: dynamic, urban scene, autonomous driving, ar, motion, gaussian splatting  
- **[ICP-3DGS: SfM-free 3D Gaussian Splatting for Large-scale Unbounded
  Scenes](https://arxiv.org/abs/2506.21629v1)**  
  Authors: Chenhao Zhang, Yezhi Shen, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21629v1.pdf)  
  Keywords: 3d gaussian, neural rendering, nerf, outdoor, ar, motion, gaussian splatting  
- **[GRAND-SLAM: Local Optimization for Globally Consistent Large-Scale
  Multi-Agent Gaussian SLAM](https://arxiv.org/abs/2506.18885v1)**  
  Authors: Annika Thomas, Aneesa Sonawalla, Alex Rose, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.18885v1.pdf)  
  Keywords: 3d gaussian, outdoor, ar, slam, gaussian splatting, tracking  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: 3d gaussian, nerf, dynamic, autonomous driving, outdoor, high-fidelity, survey, ar, gaussian splatting, face, efficient  
- **[Multiview Geometric Regularization of Gaussian Splatting for Accurate
  Radiance Fields](https://arxiv.org/abs/2506.13508v1)**  
  Authors: Jungeon Kim, Geonsoo Park, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.13508v1.pdf)  
  Keywords: 3d gaussian, outdoor, ar, geometry, gaussian splatting  

### Model Compression

*Showing the latest 50 out of 397 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: 3d gaussian, relighting, ar, lighting, reflection, gaussian splatting, efficient  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: compact, dynamic, 3d gaussian, ar, deformation, motion, gaussian splatting, efficient, 4d  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: 3d gaussian, fast, ar, compression, gaussian splatting  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: fast, ar, gaussian splatting, efficient, semantic, high quality  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: 3d gaussian, nerf, ar, geometry, reflection, gaussian splatting, face, efficient  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, ar, compression, motion, gaussian splatting, efficient  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: 3d gaussian, nerf, ar, geometry, gaussian splatting, face, efficient  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: 3d gaussian, ar, localization, gaussian splatting, efficient, semantic  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, 3d gaussian, neural rendering, human, head, ar, tracking, vr, gaussian splatting, face, efficient rendering, efficient  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: 3d gaussian, fast, lightweight, ar, slam, gaussian splatting  

### Quality Enhancement

*Showing the latest 50 out of 163 papers*

- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: fast, ar, gaussian splatting, efficient, semantic, high quality  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, motion, geometry, gaussian splatting  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: 3d gaussian, human, animation, high-fidelity, ar, avatar, gaussian splatting, recognition  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, 3d gaussian, high-fidelity, ar, compression, motion, gaussian splatting, efficient  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: nerf, high-fidelity, ar, vr, motion, geometry, gaussian splatting, face, segmentation  
- **[SegmentDreamer: Towards High-fidelity Text-to-3D Synthesis with
  Segmented Consistency Trajectory Distillation](https://arxiv.org/abs/2507.05256v1)**  
  Authors: Jiahao Zhu, Zixuan Chen, Guangcong Wang, Xiaohua Xie, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05256v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, ar  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, deformation, geometry, gaussian splatting, semantic  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: 3d gaussian, dynamic, urban scene, autonomous driving, high-fidelity, ar, real-time rendering, gaussian splatting  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, 3d gaussian, outdoor, high-fidelity, ar, mapping, slam, gaussian splatting, tracking  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: 3d gaussian, fast, high-fidelity, ar, avatar, lighting, deformation, reflection, gaussian splatting, face  

### Ray Tracing

- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: high-fidelity, ar, real-time rendering, ray tracing, gaussian splatting, efficient  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v1)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v1.pdf)  
  Keywords: shadow, human, relightable, relighting, fast, ar, avatar, ray tracing, lighting, geometry, gaussian splatting  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: 3d gaussian, relighting, ar, ray tracing, lighting, gaussian splatting, acceleration, efficient rendering, efficient  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: compact, 3d gaussian, dynamic, animation, ar, ray marching, gaussian splatting, acceleration, efficient  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: 3d gaussian, ar, real-time rendering, ray tracing, lighting, gaussian splatting, face, efficient, illumination, global illumination  
- **[REdiSplats: Ray Tracing for Editable Gaussian Splatting](https://arxiv.org/abs/2503.12284v1)**  
  Authors: Krzysztof Byrski, Grzegorz Wilczyński, Weronika Smolak-Dyżewska, Piotr Borycki, Dawid Baran, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12284v1.pdf)  
  Keywords: 3d gaussian, neural rendering, shadow, fast, ar, ray tracing, reflection, gaussian splatting  
- **[MeshSplats: Mesh-Based Rendering with Gaussian Splatting Initialization](https://arxiv.org/abs/2502.07754v1)**  
  Authors: Rafał Tobiasz, Grzegorz Wilczyński, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07754v1.pdf)  
  Keywords: shadow, ray tracing, lighting, reflection, gaussian splatting, face  
- **[Scalable 3D Gaussian Splatting-Based RF Signal Spatial Propagation
  Modeling](https://arxiv.org/abs/2502.01826v1)**  
  Authors: Kang Yang, Gaofeng Dong, Sijie Ji, Wan Du, Mani Srivastava  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01826v1.pdf)  
  Keywords: 3d gaussian, survey, ar, ray tracing, gaussian splatting  
- **[Radiant Foam: Real-Time Differentiable Ray Tracing](https://arxiv.org/abs/2502.01157v1)**  
  Authors: Shrisudhan Govindarajan, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01157v1.pdf)  
  Keywords: ar, ray tracing, light transport, reflection, gaussian splatting, acceleration, efficient  
- **[RaySplats: Ray Tracing based Gaussian Splatting](https://arxiv.org/abs/2501.19196v1)**  
  Authors: Krzysztof Byrski, Marcin Mazur, Jacek Tabor, Tadeusz Dziarmaga, Marcin Kądziołka, Dawid Baran, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.19196v1.pdf)  
  Keywords: 3d gaussian, shadow, ar, ray tracing, reflection, gaussian splatting  

### Relighting

*Showing the latest 50 out of 108 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: 3d gaussian, relighting, ar, lighting, reflection, gaussian splatting, efficient  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: 3d gaussian, ar, lighting, gaussian splatting, segmentation  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: 3d gaussian, nerf, ar, geometry, reflection, gaussian splatting, face, efficient  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: 3d gaussian, fast, high-fidelity, ar, avatar, lighting, deformation, reflection, gaussian splatting, face  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: 3d gaussian, ar, mapping, lighting, geometry, reflection, gaussian splatting  
- **[SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable
  Gaussian Splatting](https://arxiv.org/abs/2506.23309v2)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Kun Yuan, Guankun Wang, Mobarak I. Hoque, Nicolas Padoy, Nassir Navab, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23309v2.pdf)  
  Keywords: understanding, 3d reconstruction, ar, lighting, deformation, gaussian splatting, segmentation, tracking, semantic  
- **[Endo-4DGX: Robust Endoscopic Scene Reconstruction and Illumination
  Correction with Gaussian Splatting](https://arxiv.org/abs/2506.23308v1)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Yanheng Li, Tong Chen, Jie Wang, Jinlin Wu, Zhen Lei, Hongbin Liu, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23308v1.pdf)  
  Keywords: dynamic, 3d gaussian, ar, lighting, gaussian splatting, illumination, 4d  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: 3d gaussian, dynamic, outdoor, high-fidelity, ar, mapping, lighting, geometry, slam, gaussian splatting, tracking, illumination  
- **[MADrive: Memory-Augmented Driving Scene Modeling](https://arxiv.org/abs/2506.21520v1)**  
  Authors: Polina Karpikova, Daniil Selikhanovych, Kirill Struminsky, Ruslan Musaev, Maria Golitsyna, Dmitry Baranchuk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yandex-research.github.io/madrive/)  
  Keywords: 3d gaussian, autonomous driving, relighting, ar, lighting, gaussian splatting  
- **[Micro-macro Gaussian Splatting with Enhanced Scalability for
  Unconstrained Scene Reconstruction](https://arxiv.org/abs/2506.13516v1)**  
  Authors: Yihui Li, Chengxin Lv, Hongyu Yang, Di Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.13516v1.pdf)  
  Keywords: 3d reconstruction, ar, motion, gaussian splatting, illumination  

### SLAM

*Showing the latest 50 out of 157 papers*

- **[3DGS_LSR:Large_Scale Relocation for Autonomous Driving Based on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.05661v1)**  
  Authors: Haitao Lu, Haijier Chen, Haoze Liu, Shoujian Zhang, Bo Xu, Ziao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05661v1.pdf)  
  Keywords: 3d gaussian, autonomous driving, outdoor, ar, mapping, localization, gaussian splatting  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: 3d gaussian, ar, localization, gaussian splatting, efficient, semantic  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, 3d gaussian, neural rendering, human, head, ar, tracking, vr, gaussian splatting, face, efficient rendering, efficient  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: 3d gaussian, fast, lightweight, ar, slam, gaussian splatting  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, 3d gaussian, outdoor, high-fidelity, ar, mapping, slam, gaussian splatting, tracking  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: 3d gaussian, ar, mapping, lighting, geometry, reflection, gaussian splatting  
- **[SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable
  Gaussian Splatting](https://arxiv.org/abs/2506.23309v2)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Kun Yuan, Guankun Wang, Mobarak I. Hoque, Nicolas Padoy, Nassir Navab, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23309v2.pdf)  
  Keywords: understanding, 3d reconstruction, ar, lighting, deformation, gaussian splatting, segmentation, tracking, semantic  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: 3d gaussian, dynamic, outdoor, high-fidelity, ar, mapping, lighting, geometry, slam, gaussian splatting, tracking, illumination  
- **[VoteSplat: Hough Voting Gaussian Splatting for 3D Scene Understanding](https://arxiv.org/abs/2506.22799v1)**  
  Authors: Minchao Jiang, Shunyu Jia, Jiaming Gu, Xiaoyuan Lu, Guangming Zhu, Anqi Dong, Liang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.22799v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sy-ja.github.io/votesplat/)  
  Keywords: 3d gaussian, understanding, ar, real-time rendering, localization, gaussian splatting, segmentation, semantic  
- **[EndoFlow-SLAM: Real-Time Endoscopic SLAM with Flow-Constrained Gaussian
  Splatting](https://arxiv.org/abs/2506.21420v2)**  
  Authors: Taoyu Wu, Yiyi Miao, Zhuoxiao Li, Haocheng Zhao, Kang Dang, Jionglong Su, Limin Yu, Haoang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21420v2.pdf)  
  Keywords: 3d gaussian, dynamic, 3d reconstruction, localization, ar, mapping, motion, slam, gaussian splatting, face, efficient  

### Scene Understanding

*Showing the latest 50 out of 188 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, 3d gaussian, nerf, understanding, outdoor, ar, motion, gaussian splatting, segmentation, 4d  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: 3d gaussian, ar, lighting, gaussian splatting, segmentation  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, medical, understanding, ar, deformation, gaussian splatting  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: fast, ar, gaussian splatting, efficient, semantic, high quality  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: 3d gaussian, human, animation, high-fidelity, ar, avatar, gaussian splatting, recognition  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: nerf, high-fidelity, ar, vr, motion, geometry, gaussian splatting, face, segmentation  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: 3d gaussian, ar, localization, gaussian splatting, efficient, semantic  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, deformation, geometry, gaussian splatting, semantic  
- **[ArtGS:3D Gaussian Splatting for Interactive Visual-Physical Modeling and
  Manipulation of Articulated Objects](https://arxiv.org/abs/2507.02600v1)**  
  Authors: Qiaojun Yu, Xibin Yuan, Yu jiang, Junting Chen, Dongzhe Zheng, Ce Hao, Yang You, Yixing Chen, Yao Mu, Liu Liu, Cewu Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02600v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/artgs/home)  
  Keywords: dynamic, 3d gaussian, understanding, ar, robotics, motion, gaussian splatting, efficient, semantic  
- **[VISTA: Open-Vocabulary, Task-Relevant Robot Exploration with Online
  Semantic Gaussian Splatting](https://arxiv.org/abs/2507.01125v1)**  
  Authors: Keiko Nagami, Timothy Chen, Javier Yu, Ola Shorinwa, Maximilian Adang, Carlyn Dougherty, Eric Cristofalo, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.01125v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, efficient, semantic  



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