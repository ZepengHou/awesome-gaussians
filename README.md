# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-09-26 00:52:01

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

- [3DGS Surveys](#3dgs-surveys) (20 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (256 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (328 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (385 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (72 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (311 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (74 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (410 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (160 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (17 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (114 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (195 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing,
  and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: compact, survey, semantic, high-fidelity, lighting, gaussian splatting, 3d gaussian, segmentation, understanding, nerf, ar  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: robotics, survey, semantic, gaussian splatting, 3d gaussian, understanding, nerf, ar, efficient  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: robotics, human, survey, gaussian splatting, 3d gaussian, nerf, ar  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: motion, robotics, survey, 3d reconstruction, vr, gaussian splatting, 3d gaussian, geometry, sparse-view, nerf, ar  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v2)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Hanspeter Pfister, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v2.pdf)  
  Keywords: robotics, human, dynamic, survey, 3d reconstruction, lighting, gaussian splatting, vr, 3d gaussian, nerf, ar, fast, slam  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: face, dynamic, survey, high-fidelity, outdoor, gaussian splatting, 3d gaussian, autonomous driving, nerf, ar, efficient  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: robotics, survey, 3d reconstruction, high-fidelity, vr, gaussian splatting, neural rendering, 3d gaussian, autonomous driving, nerf, ar  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: survey, 3d reconstruction, semantic, high-fidelity, outdoor, gaussian splatting, neural rendering, 3d gaussian, segmentation, understanding, ar, efficient  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: survey, semantic, slam, gaussian splatting, mapping, 3d gaussian, segmentation, localization, nerf, ar, efficient  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: 4d, motion, dynamic, survey, body, gaussian splatting, 3d gaussian, understanding, ar  

### Acceleration

*Showing the latest 50 out of 256 papers*

- **[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface
  Reconstruction](https://arxiv.org/abs/2509.19726v1)**  
  Authors: Yufei Han, Bowen Tie, Heng Guo, Youwei Lyu, Si Li, Boxin Shi, Yunpeng Jia, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19726v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, shape reconstruction, ar, fast, efficient  
- **[Lyra: Generative 3D Scene Reconstruction via Video Diffusion Model
  Self-Distillation](https://arxiv.org/abs/2509.19296v1)**  
  Authors: Sherwin Bahmani, Tianchang Shen, Jiawei Ren, Jiahui Huang, Yifeng Jiang, Haithem Turki, Andrea Tagliasacchi, David B. Lindell, Zan Gojcic, Sanja Fidler, Huan Ling, Jun Gao, Xuanchi Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19296v1.pdf)  
  Keywords: robotics, dynamic, 3d reconstruction, gaussian splatting, 3d gaussian, autonomous driving, ar, real-time rendering  
- **[Event-guided 3D Gaussian Splatting for Dynamic Human and Scene
  Reconstruction](https://arxiv.org/abs/2509.18566v1)**  
  Authors: Xiaoting Yin, Hao Shi, Kailun Yang, Jiajun Zhai, Shangwei Guo, Lin Wang, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18566v1.pdf)  
  Keywords: motion, human, dynamic, semantic, gaussian splatting, deformation, 3d gaussian, ar, animation, fast  
- **[FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS
  Models to LiDAR](https://arxiv.org/abs/2509.17390v1)**  
  Authors: Junzhe Wu, Yufei Jia, Yiyi Yan, Zhixing Chen, Tiao Tan, Zifan Wang, Guangyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17390v1.pdf)  
  Keywords: robotics, high-fidelity, outdoor, gaussian splatting, 3d gaussian, autonomous driving, ar, fast  
- **[Efficient 3D Scene Reconstruction and Simulation from Sparse Endoscopic
  Views](https://arxiv.org/abs/2509.17027v1)**  
  Authors: Zhenya Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17027v1.pdf)  
  Keywords: gaussian splatting, deformation, geometry, medical, ar, fast, efficient  
- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: 4d, lighting, gaussian splatting, 3d gaussian, autonomous driving, ar, fast, efficient  
- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, high quality, fast, efficient  
- **[Plug-and-Play PDE Optimization for 3D Gaussian Splatting: Toward
  High-Quality Rendering and Reconstruction](https://arxiv.org/abs/2509.13938v1)**  
  Authors: Yifan Mo, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13938v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, ar, fast  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: motion, gaussian splatting, 3d gaussian, segmentation, geometry, sparse-view, ar, real-time rendering, fast  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: human, gaussian splatting, deformation, mapping, avatar, ar, fast, efficient  

### Applications

*Showing the latest 50 out of 995 papers*

- **[4D Driving Scene Generation With Stereo Forcing](https://arxiv.org/abs/2509.20251v1)**  
  Authors: Hao Lu, Zhuang Ma, Guangfeng Jiang, Wenhang Ge, Bohan Li, Yuzhan Cai, Wenzhao Zheng, Yunpeng Zhang, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.20251v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiangxb98.github.io/PhiGensis}{PhiGensis}.)  
  Keywords: 4d, motion, dynamic, semantic, gaussian splatting, geometry, ar  
- **[GS-RoadPatching: Inpainting Gaussians via 3D Searching and Placing for
  Driving Scenes](https://arxiv.org/abs/2509.19937v1)**  
  Authors: Guo Chen, Jiarun Liu, Sicong Du, Chenming Wu, Deqi Li, Shi-Sheng Huang, Guofeng Zhang, Sheng Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19937v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shanzhaguoo.github.io/GS-RoadPatching/)  
  Keywords: 3d gaussian, ar, gaussian splatting  
- **[Aerial-Ground Image Feature Matching via 3D Gaussian Splatting-based
  Intermediate View Rendering](https://arxiv.org/abs/2509.19898v1)**  
  Authors: Jiangxue Yu, Hui Wang, San Jiang, Xing Zhang, Dejin Zhang, Qingquan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19898v1.pdf)  
  Keywords: motion, gaussian splatting, large scene, 3d gaussian, ar  
- **[BiTAA: A Bi-Task Adversarial Attack for Object Detection and Depth
  Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2509.19793v1)**  
  Authors: Yixun Zhang, Feng Zhou, Jianqin Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19793v1.pdf)  
  Keywords: 3d gaussian, autonomous driving, ar, gaussian splatting  
- **[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface
  Reconstruction](https://arxiv.org/abs/2509.19726v1)**  
  Authors: Yufei Han, Bowen Tie, Heng Guo, Youwei Lyu, Si Li, Boxin Shi, Yunpeng Jia, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19726v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, shape reconstruction, ar, fast, efficient  
- **[VolSplat: Rethinking Feed-Forward 3D Gaussian Splatting with
  Voxel-Aligned Prediction](https://arxiv.org/abs/2509.19297v1)**  
  Authors: Weijie Wang, Yeqing Chen, Zeyu Zhang, Hengyu Liu, Haoxiao Wang, Zhiyuan Feng, Wenkang Qin, Zheng Zhu, Donny Y. Chen, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19297v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lhmd.top/volsplat.)  
  Keywords: 3d gaussian, ar, gaussian splatting, 3d reconstruction  
- **[Lyra: Generative 3D Scene Reconstruction via Video Diffusion Model
  Self-Distillation](https://arxiv.org/abs/2509.19296v1)**  
  Authors: Sherwin Bahmani, Tianchang Shen, Jiawei Ren, Jiahui Huang, Yifeng Jiang, Haithem Turki, Andrea Tagliasacchi, David B. Lindell, Zan Gojcic, Sanja Fidler, Huan Ling, Jun Gao, Xuanchi Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19296v1.pdf)  
  Keywords: robotics, dynamic, 3d reconstruction, gaussian splatting, 3d gaussian, autonomous driving, ar, real-time rendering  
- **[WaveletGaussian: Wavelet-domain Diffusion for Sparse-view 3D Gaussian
  Object Reconstruction](https://arxiv.org/abs/2509.19073v1)**  
  Authors: Hung Nguyen, Runfa Li, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19073v1.pdf)  
  Keywords: lightweight, gaussian splatting, 3d gaussian, sparse-view, nerf, ar, efficient  
- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: face, reflection, 3d reconstruction, gaussian splatting, mapping, 3d gaussian, geometry, nerf, ar  
- **[DeblurSplat: SfM-free 3D Gaussian Splatting with Event Camera for Robust
  Deblurring](https://arxiv.org/abs/2509.18898v1)**  
  Authors: Pengteng Li, Yunfan Lu, Pinhao Song, Weiyu Guo, Huizai Yao, F. Richard Yu, Hui Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18898v1.pdf)  
  Keywords: motion, dynamic, high-fidelity, gaussian splatting, 3d gaussian, ar  

### Avatar Generation

*Showing the latest 50 out of 328 papers*

- **[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface
  Reconstruction](https://arxiv.org/abs/2509.19726v1)**  
  Authors: Yufei Han, Bowen Tie, Heng Guo, Youwei Lyu, Si Li, Boxin Shi, Yunpeng Jia, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19726v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, shape reconstruction, ar, fast, efficient  
- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: face, reflection, 3d reconstruction, gaussian splatting, mapping, 3d gaussian, geometry, nerf, ar  
- **[Event-guided 3D Gaussian Splatting for Dynamic Human and Scene
  Reconstruction](https://arxiv.org/abs/2509.18566v1)**  
  Authors: Xiaoting Yin, Hao Shi, Kailun Yang, Jiajun Zhai, Shangwei Guo, Lin Wang, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18566v1.pdf)  
  Keywords: motion, human, dynamic, semantic, gaussian splatting, deformation, 3d gaussian, ar, animation, fast  
- **[GeoSVR: Taming Sparse Voxels for Geometrically Accurate Surface
  Reconstruction](https://arxiv.org/abs/2509.18090v1)**  
  Authors: Jiahe Li, Jiawei Zhang, Youmin Zhang, Xiao Bai, Jin Zheng, Xiaohan Yu, Lin Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18090v1.pdf)  
  Keywords: face, ar, vr, gaussian splatting  
- **[HyRF: Hybrid Radiance Fields for Memory-efficient and High-quality Novel
  View Synthesis](https://arxiv.org/abs/2509.17083v2)**  
  Authors: Zipeng Wang, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17083v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wzpscott.github.io/hyrf/.)  
  Keywords: compact, gaussian splatting, 3d gaussian, head, geometry, nerf, ar, efficient  
- **[PGSTalker: Real-Time Audio-Driven Talking Head Generation via 3D
  Gaussian Splatting with Pixel-Aware Density Control](https://arxiv.org/abs/2509.16922v1)**  
  Authors: Tianheng Zhu, Yinfeng Yu, Liejun Wang, Fuchun Sun, Wendong Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16922v1.pdf)  
  Keywords: dynamic, lightweight, high-fidelity, gaussian splatting, deformation, 3d gaussian, avatar, head, nerf, ar  
- **[MedGS: Gaussian Splatting for Multi-Modal 3D Medical Imaging](https://arxiv.org/abs/2509.16806v1)**  
  Authors: Kacper Marzol, Ignacy Kolton, Weronika Smolak-Dyżewska, Joanna Kaleta, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16806v1.pdf)  
  Keywords: face, high-fidelity, gaussian splatting, medical, ar, efficient  
- **[ST-GS: Vision-Based 3D Semantic Occupancy Prediction with
  Spatial-Temporal Gaussian Splatting](https://arxiv.org/abs/2509.16552v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16552v1.pdf)  
  Keywords: semantic, gaussian splatting, autonomous driving, understanding, head, geometry, ar  
- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: face, reflection, gaussian splatting, 3d gaussian, ar  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: face, human, semantic, high-fidelity, gaussian splatting, 3d gaussian, avatar, ar  

### Dynamic Scene

*Showing the latest 50 out of 385 papers*

- **[4D Driving Scene Generation With Stereo Forcing](https://arxiv.org/abs/2509.20251v1)**  
  Authors: Hao Lu, Zhuang Ma, Guangfeng Jiang, Wenhang Ge, Bohan Li, Yuzhan Cai, Wenzhao Zheng, Yunpeng Zhang, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.20251v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiangxb98.github.io/PhiGensis}{PhiGensis}.)  
  Keywords: 4d, motion, dynamic, semantic, gaussian splatting, geometry, ar  
- **[Aerial-Ground Image Feature Matching via 3D Gaussian Splatting-based
  Intermediate View Rendering](https://arxiv.org/abs/2509.19898v1)**  
  Authors: Jiangxue Yu, Hui Wang, San Jiang, Xing Zhang, Dejin Zhang, Qingquan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19898v1.pdf)  
  Keywords: motion, gaussian splatting, large scene, 3d gaussian, ar  
- **[Lyra: Generative 3D Scene Reconstruction via Video Diffusion Model
  Self-Distillation](https://arxiv.org/abs/2509.19296v1)**  
  Authors: Sherwin Bahmani, Tianchang Shen, Jiawei Ren, Jiahui Huang, Yifeng Jiang, Haithem Turki, Andrea Tagliasacchi, David B. Lindell, Zan Gojcic, Sanja Fidler, Huan Ling, Jun Gao, Xuanchi Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19296v1.pdf)  
  Keywords: robotics, dynamic, 3d reconstruction, gaussian splatting, 3d gaussian, autonomous driving, ar, real-time rendering  
- **[DeblurSplat: SfM-free 3D Gaussian Splatting with Event Camera for Robust
  Deblurring](https://arxiv.org/abs/2509.18898v1)**  
  Authors: Pengteng Li, Yunfan Lu, Pinhao Song, Weiyu Guo, Huizai Yao, F. Richard Yu, Hui Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18898v1.pdf)  
  Keywords: motion, dynamic, high-fidelity, gaussian splatting, 3d gaussian, ar  
- **[Event-guided 3D Gaussian Splatting for Dynamic Human and Scene
  Reconstruction](https://arxiv.org/abs/2509.18566v1)**  
  Authors: Xiaoting Yin, Hao Shi, Kailun Yang, Jiajun Zhai, Shangwei Guo, Lin Wang, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18566v1.pdf)  
  Keywords: motion, human, dynamic, semantic, gaussian splatting, deformation, 3d gaussian, ar, animation, fast  
- **[GaussianPSL: A novel framework based on Gaussian Splatting for exploring
  the Pareto frontier in multi-criteria optimization](https://arxiv.org/abs/2509.17889v1)**  
  Authors: Phuong Mai Dinh, Van-Nam Huynh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17889v1.pdf)  
  Keywords: ar, gaussian splatting, dynamic  
- **[Efficient 3D Scene Reconstruction and Simulation from Sparse Endoscopic
  Views](https://arxiv.org/abs/2509.17027v1)**  
  Authors: Zhenya Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17027v1.pdf)  
  Keywords: gaussian splatting, deformation, geometry, medical, ar, fast, efficient  
- **[PGSTalker: Real-Time Audio-Driven Talking Head Generation via 3D
  Gaussian Splatting with Pixel-Aware Density Control](https://arxiv.org/abs/2509.16922v1)**  
  Authors: Tianheng Zhu, Yinfeng Yu, Liejun Wang, Fuchun Sun, Wendong Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16922v1.pdf)  
  Keywords: dynamic, lightweight, high-fidelity, gaussian splatting, deformation, 3d gaussian, avatar, head, nerf, ar  
- **[ConfidentSplat: Confidence-Weighted Depth Fusion for Accurate 3D
  Gaussian Splatting SLAM](https://arxiv.org/abs/2509.16863v1)**  
  Authors: Amanuel T. Dufera, Yuan-Li Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16863v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, 3d gaussian, geometry, slam, ar, efficient  
- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: 4d, lighting, gaussian splatting, 3d gaussian, autonomous driving, ar, fast, efficient  

### Few-shot

*Showing the latest 50 out of 72 papers*

- **[WaveletGaussian: Wavelet-domain Diffusion for Sparse-view 3D Gaussian
  Object Reconstruction](https://arxiv.org/abs/2509.19073v1)**  
  Authors: Hung Nguyen, Runfa Li, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19073v1.pdf)  
  Keywords: lightweight, gaussian splatting, 3d gaussian, sparse-view, nerf, ar, efficient  
- **[FixingGS: Enhancing 3D Gaussian Splatting via Training-Free Score
  Distillation](https://arxiv.org/abs/2509.18759v1)**  
  Authors: Zhaorui Wang, Yi Gu, Deming Zhou, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18759v1.pdf)  
  Keywords: sparse view, 3d reconstruction, gaussian splatting, 3d gaussian, sparse-view, ar  
- **[SPFSplatV2: Efficient Self-Supervised Pose-Free 3D Gaussian Splatting
  from Sparse Views](https://arxiv.org/abs/2509.17246v1)**  
  Authors: Ranran Huang, Krystian Mikolajczyk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17246v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ranrhuang.github.io/spfsplatv2/.)  
  Keywords: sparse view, gaussian splatting, 3d gaussian, ar, efficient  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v2)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v2.pdf)  
  Keywords: motion, semantic, gaussian splatting, 3d gaussian, geometry, sparse-view, nerf, ar  
- **[LamiGauss: Pitching Radiative Gaussian for Sparse-View X-ray
  Laminography Reconstruction](https://arxiv.org/abs/2509.13863v1)**  
  Authors: Chu Chen, Ander Biguri, Jean-Michel Morel, Raymond H. Chan, Carola-Bibiane Schönlieb, Jizhou Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13863v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, efficient  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: motion, gaussian splatting, 3d gaussian, segmentation, geometry, sparse-view, ar, real-time rendering, fast  
- **[AD-GS: Alternating Densification for Sparse-Input 3D Gaussian Splatting](https://arxiv.org/abs/2509.11003v2)**  
  Authors: Gurutva Patle, Nilay Girgaonkar, Nagabhushan Somraj, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11003v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gurutvapatle.github.io/publications/2025/ADGS.html)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, ar  
- **[${C}^{3}$-GS: Learning Context-aware, Cross-dimension, Cross-scale
  Feature for Generalizable Gaussian Splatting](https://arxiv.org/abs/2508.20754v1)**  
  Authors: Yuxi Hu, Jun Zhang, Kuangyi Chen, Zhe Zhang, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.20754v1.pdf)  
  Keywords: sparse view, lightweight, gaussian splatting, geometry, ar  
- **[MeshSplat: Generalizable Sparse-View Surface Reconstruction via Gaussian
  Splatting](https://arxiv.org/abs/2508.17811v1)**  
  Authors: Hanzhi Chang, Ruijie Zhu, Wenjie Chang, Mulin Yu, Yanzhe Liang, Jiahao Lu, Zhuoyuan Li, Tianzhu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17811v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hanzhichang.github.io/meshsplat_web)  
  Keywords: face, gaussian splatting, sparse-view, geometry, ar  
- **[Enhancing Novel View Synthesis from extremely sparse views with SfM-free
  3D Gaussian Splatting Framework](https://arxiv.org/abs/2508.15457v1)**  
  Authors: Zongqi He, Hanmin Li, Kin-Chung Chan, Yushen Zuo, Hao Xie, Zhe Xiao, Jun Xiao, Kin-Man Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15457v1.pdf)  
  Keywords: motion, sparse view, gaussian splatting, 3d gaussian, geometry, sparse-view, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 311 papers*

- **[4D Driving Scene Generation With Stereo Forcing](https://arxiv.org/abs/2509.20251v1)**  
  Authors: Hao Lu, Zhuang Ma, Guangfeng Jiang, Wenhang Ge, Bohan Li, Yuzhan Cai, Wenzhao Zheng, Yunpeng Zhang, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.20251v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiangxb98.github.io/PhiGensis}{PhiGensis}.)  
  Keywords: 4d, motion, dynamic, semantic, gaussian splatting, geometry, ar  
- **[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface
  Reconstruction](https://arxiv.org/abs/2509.19726v1)**  
  Authors: Yufei Han, Bowen Tie, Heng Guo, Youwei Lyu, Si Li, Boxin Shi, Yunpeng Jia, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19726v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, shape reconstruction, ar, fast, efficient  
- **[VolSplat: Rethinking Feed-Forward 3D Gaussian Splatting with
  Voxel-Aligned Prediction](https://arxiv.org/abs/2509.19297v1)**  
  Authors: Weijie Wang, Yeqing Chen, Zeyu Zhang, Hengyu Liu, Haoxiao Wang, Zhiyuan Feng, Wenkang Qin, Zheng Zhu, Donny Y. Chen, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19297v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lhmd.top/volsplat.)  
  Keywords: 3d gaussian, ar, gaussian splatting, 3d reconstruction  
- **[Lyra: Generative 3D Scene Reconstruction via Video Diffusion Model
  Self-Distillation](https://arxiv.org/abs/2509.19296v1)**  
  Authors: Sherwin Bahmani, Tianchang Shen, Jiawei Ren, Jiahui Huang, Yifeng Jiang, Haithem Turki, Andrea Tagliasacchi, David B. Lindell, Zan Gojcic, Sanja Fidler, Huan Ling, Jun Gao, Xuanchi Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19296v1.pdf)  
  Keywords: robotics, dynamic, 3d reconstruction, gaussian splatting, 3d gaussian, autonomous driving, ar, real-time rendering  
- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: face, reflection, 3d reconstruction, gaussian splatting, mapping, 3d gaussian, geometry, nerf, ar  
- **[FixingGS: Enhancing 3D Gaussian Splatting via Training-Free Score
  Distillation](https://arxiv.org/abs/2509.18759v1)**  
  Authors: Zhaorui Wang, Yi Gu, Deming Zhou, Renjing Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18759v1.pdf)  
  Keywords: sparse view, 3d reconstruction, gaussian splatting, 3d gaussian, sparse-view, ar  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v1)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v1.pdf)  
  Keywords: relighting, reflection, illumination, global illumination, lighting, gaussian splatting, geometry, light transport, ar, efficient  
- **[From Restoration to Reconstruction: Rethinking 3D Gaussian Splatting for
  Underwater Scenes](https://arxiv.org/abs/2509.17789v1)**  
  Authors: Guoxi Huang, Haoran Wang, Zipeng Qi, Wenjun Lu, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17789v1.pdf)  
  Keywords: illumination, 3d reconstruction, lightweight, gaussian splatting, 3d gaussian, nerf, ar  
- **[HyRF: Hybrid Radiance Fields for Memory-efficient and High-quality Novel
  View Synthesis](https://arxiv.org/abs/2509.17083v2)**  
  Authors: Zipeng Wang, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17083v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wzpscott.github.io/hyrf/.)  
  Keywords: compact, gaussian splatting, 3d gaussian, head, geometry, nerf, ar, efficient  
- **[Efficient 3D Scene Reconstruction and Simulation from Sparse Endoscopic
  Views](https://arxiv.org/abs/2509.17027v1)**  
  Authors: Zhenya Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17027v1.pdf)  
  Keywords: gaussian splatting, deformation, geometry, medical, ar, fast, efficient  

### Large Scene

*Showing the latest 50 out of 74 papers*

- **[Aerial-Ground Image Feature Matching via 3D Gaussian Splatting-based
  Intermediate View Rendering](https://arxiv.org/abs/2509.19898v1)**  
  Authors: Jiangxue Yu, Hui Wang, San Jiang, Xing Zhang, Dejin Zhang, Qingquan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19898v1.pdf)  
  Keywords: motion, gaussian splatting, large scene, 3d gaussian, ar  
- **[FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS
  Models to LiDAR](https://arxiv.org/abs/2509.17390v1)**  
  Authors: Junzhe Wu, Yufei Jia, Yiyi Yan, Zhixing Chen, Tiao Tan, Zifan Wang, Guangyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17390v1.pdf)  
  Keywords: robotics, high-fidelity, outdoor, gaussian splatting, 3d gaussian, autonomous driving, ar, fast  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, compact, illumination, efficient rendering, relightable, outdoor, lighting, gaussian splatting, 3d gaussian, head, geometry, nerf, ar, efficient  
- **[VIM-GS: Visual-Inertial Monocular Gaussian Splatting via Object-level
  Guidance in Large Scenes](https://arxiv.org/abs/2509.06685v3)**  
  Authors: Shengkai Zhang, Yuhe Liu, Guanjun Wu, Jianhua He, Xinggang Wang, Mozi Chen, Kezhong Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06685v3.pdf)  
  Keywords: motion, dynamic, gaussian splatting, large scene, ar  
- **[3DOF+Quantization: 3DGS quantization for large scenes with limited
  Degrees of Freedom](https://arxiv.org/abs/2509.06400v1)**  
  Authors: Matthieu Gendrin, Stéphane Pateux, Théo Ladune  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06400v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting, large scene  
- **[GSVisLoc: Generalizable Visual Localization for Gaussian Splatting Scene
  Representations](https://arxiv.org/abs/2508.18242v1)**  
  Authors: Fadi Khatib, Dror Moran, Guy Trostianetsky, Yoni Kasten, Meirav Galun, Ronen Basri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18242v1.pdf)  
  Keywords: outdoor, gaussian splatting, 3d gaussian, localization, ar  
- **[MeSS: City Mesh-Guided Outdoor Scene Generation with Cross-View
  Consistent Diffusion](https://arxiv.org/abs/2508.15169v2)**  
  Authors: Xuyang Chen, Zhijun Zhai, Kaixuan Zhou, Zengmao Wang, Jianan He, Dong Wang, Yanfeng Zhang, mingwei Sun, Rüdiger Westermann, Konrad Schindler, Liqiu Meng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.15169v2.pdf)  
  Keywords: face, relighting, sparse view, outdoor, lighting, gaussian splatting, 3d gaussian, autonomous driving, geometry, ar  
- **[Reconstruction Using the Invisible: Intuition from NIR and Metadata for
  Enhanced 3D Gaussian Splatting](https://arxiv.org/abs/2508.14443v1)**  
  Authors: Gyusam Chang, Tuan-Anh Vu, Vivek Alumootil, Harris Song, Deanna Pham, Sangpil Kim, M. Khalid Jawed  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14443v1.pdf)  
  Keywords: illumination, 3d reconstruction, outdoor, lighting, gaussian splatting, 3d gaussian, understanding, ar  
- **[Online 3D Gaussian Splatting Modeling with Novel View Selection](https://arxiv.org/abs/2508.14014v2)**  
  Authors: Byeonggwon Lee, Junkyu Park, Khang Truong Giang, Soohwan Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14014v2.pdf)  
  Keywords: outdoor, gaussian splatting, 3d gaussian, ar, slam  
- **[InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes](https://arxiv.org/abs/2508.12015v1)**  
  Authors: Hongyuan Liu, Haochen Yu, Jianfei Jiang, Qiankun Liu, Jiansheng Chen, Huimin Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.12015v1.pdf)  
  Keywords: dynamic, lightweight, outdoor, gaussian splatting, 3d gaussian, segmentation, understanding, autonomous driving, ar  

### Model Compression

*Showing the latest 50 out of 410 papers*

- **[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface
  Reconstruction](https://arxiv.org/abs/2509.19726v1)**  
  Authors: Yufei Han, Bowen Tie, Heng Guo, Youwei Lyu, Si Li, Boxin Shi, Yunpeng Jia, Zhanyu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19726v1.pdf)  
  Keywords: face, gaussian splatting, 3d gaussian, shape reconstruction, ar, fast, efficient  
- **[WaveletGaussian: Wavelet-domain Diffusion for Sparse-view 3D Gaussian
  Object Reconstruction](https://arxiv.org/abs/2509.19073v1)**  
  Authors: Hung Nguyen, Runfa Li, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.19073v1.pdf)  
  Keywords: lightweight, gaussian splatting, 3d gaussian, sparse-view, nerf, ar, efficient  
- **[SINGER: An Onboard Generalist Vision-Language Navigation Policy for
  Drones](https://arxiv.org/abs/2509.18610v1)**  
  Authors: Maximilian Adang, JunEn Low, Ola Shorinwa, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18610v1.pdf)  
  Keywords: semantic, lightweight, gaussian splatting, ar, efficient  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v1)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v1.pdf)  
  Keywords: relighting, reflection, illumination, global illumination, lighting, gaussian splatting, geometry, light transport, ar, efficient  
- **[From Restoration to Reconstruction: Rethinking 3D Gaussian Splatting for
  Underwater Scenes](https://arxiv.org/abs/2509.17789v1)**  
  Authors: Guoxi Huang, Haoran Wang, Zipeng Qi, Wenjun Lu, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17789v1.pdf)  
  Keywords: illumination, 3d reconstruction, lightweight, gaussian splatting, 3d gaussian, nerf, ar  
- **[EmbodiedSplat: Personalized Real-to-Sim-to-Real Navigation with Gaussian
  Splats from a Mobile Device](https://arxiv.org/abs/2509.17430v2)**  
  Authors: Gunjan Chhablani, Xiaomeng Ye, Muhammad Zubair Irshad, Zsolt Kira  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17430v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gchhablani.github.io/embodied-splat.)  
  Keywords: high-fidelity, gaussian splatting, 3d gaussian, ar, efficient  
- **[SPFSplatV2: Efficient Self-Supervised Pose-Free 3D Gaussian Splatting
  from Sparse Views](https://arxiv.org/abs/2509.17246v1)**  
  Authors: Ranran Huang, Krystian Mikolajczyk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17246v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ranrhuang.github.io/spfsplatv2/.)  
  Keywords: sparse view, gaussian splatting, 3d gaussian, ar, efficient  
- **[HyRF: Hybrid Radiance Fields for Memory-efficient and High-quality Novel
  View Synthesis](https://arxiv.org/abs/2509.17083v2)**  
  Authors: Zipeng Wang, Dan Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17083v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wzpscott.github.io/hyrf/.)  
  Keywords: compact, gaussian splatting, 3d gaussian, head, geometry, nerf, ar, efficient  
- **[Efficient 3D Scene Reconstruction and Simulation from Sparse Endoscopic
  Views](https://arxiv.org/abs/2509.17027v1)**  
  Authors: Zhenya Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17027v1.pdf)  
  Keywords: gaussian splatting, deformation, geometry, medical, ar, fast, efficient  
- **[PGSTalker: Real-Time Audio-Driven Talking Head Generation via 3D
  Gaussian Splatting with Pixel-Aware Density Control](https://arxiv.org/abs/2509.16922v1)**  
  Authors: Tianheng Zhu, Yinfeng Yu, Liejun Wang, Fuchun Sun, Wendong Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16922v1.pdf)  
  Keywords: dynamic, lightweight, high-fidelity, gaussian splatting, deformation, 3d gaussian, avatar, head, nerf, ar  

### Quality Enhancement

*Showing the latest 50 out of 160 papers*

- **[DeblurSplat: SfM-free 3D Gaussian Splatting with Event Camera for Robust
  Deblurring](https://arxiv.org/abs/2509.18898v1)**  
  Authors: Pengteng Li, Yunfan Lu, Pinhao Song, Weiyu Guo, Huizai Yao, F. Richard Yu, Hui Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18898v1.pdf)  
  Keywords: motion, dynamic, high-fidelity, gaussian splatting, 3d gaussian, ar  
- **[EmbodiedSplat: Personalized Real-to-Sim-to-Real Navigation with Gaussian
  Splats from a Mobile Device](https://arxiv.org/abs/2509.17430v2)**  
  Authors: Gunjan Chhablani, Xiaomeng Ye, Muhammad Zubair Irshad, Zsolt Kira  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17430v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gchhablani.github.io/embodied-splat.)  
  Keywords: high-fidelity, gaussian splatting, 3d gaussian, ar, efficient  
- **[FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS
  Models to LiDAR](https://arxiv.org/abs/2509.17390v1)**  
  Authors: Junzhe Wu, Yufei Jia, Yiyi Yan, Zhixing Chen, Tiao Tan, Zifan Wang, Guangyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17390v1.pdf)  
  Keywords: robotics, high-fidelity, outdoor, gaussian splatting, 3d gaussian, autonomous driving, ar, fast  
- **[PGSTalker: Real-Time Audio-Driven Talking Head Generation via 3D
  Gaussian Splatting with Pixel-Aware Density Control](https://arxiv.org/abs/2509.16922v1)**  
  Authors: Tianheng Zhu, Yinfeng Yu, Liejun Wang, Fuchun Sun, Wendong Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16922v1.pdf)  
  Keywords: dynamic, lightweight, high-fidelity, gaussian splatting, deformation, 3d gaussian, avatar, head, nerf, ar  
- **[ConfidentSplat: Confidence-Weighted Depth Fusion for Accurate 3D
  Gaussian Splatting SLAM](https://arxiv.org/abs/2509.16863v1)**  
  Authors: Amanuel T. Dufera, Yuan-Li Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16863v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, 3d gaussian, geometry, slam, ar, efficient  
- **[MedGS: Gaussian Splatting for Multi-Modal 3D Medical Imaging](https://arxiv.org/abs/2509.16806v1)**  
  Authors: Kacper Marzol, Ignacy Kolton, Weronika Smolak-Dyżewska, Joanna Kaleta, Marcin Mazur, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16806v1.pdf)  
  Keywords: face, high-fidelity, gaussian splatting, medical, ar, efficient  
- **[GS-Scale: Unlocking Large-Scale 3D Gaussian Splatting Training via Host
  Offloading](https://arxiv.org/abs/2509.15645v1)**  
  Authors: Donghyun Lee, Dawoon Jeong, Jae W. Lee, Hongil Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15645v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, high quality, fast, efficient  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: face, human, semantic, high-fidelity, gaussian splatting, 3d gaussian, avatar, ar  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: robotics, high-fidelity, mapping, gaussian splatting, 3d gaussian, autonomous driving, ar, slam  
- **[Dream3DAvatar: Text-Controlled 3D Avatar Reconstruction from a Single
  Image](https://arxiv.org/abs/2509.13013v1)**  
  Authors: Gaofeng Liu, Hengsen Li, Ruoyu Gao, Xuetong Li, Zhiyuan Ma, Tao Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13013v1.pdf)  
  Keywords: lightweight, body, high-fidelity, 3d gaussian, avatar, geometry, ar, animation, efficient  

### Ray Tracing

- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v1)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v1.pdf)  
  Keywords: relighting, reflection, illumination, global illumination, lighting, gaussian splatting, geometry, light transport, ar, efficient  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing
  for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v1)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, ray tracing, ar, fast  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via
  Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: face, relighting, reflection, illumination, high-fidelity, lighting, gaussian splatting, 3d gaussian, ray tracing, geometry, nerf, ar  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: face, relighting, illumination, dynamic, relightable, global illumination, lighting, gaussian splatting, outdoor, 3d gaussian, shadow, ar  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: face, dynamic, lighting, gaussian splatting, 3d gaussian, ar, path tracing  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: face, relighting, ray marching, efficient rendering, relightable, lighting, gaussian splatting, 3d gaussian, geometry, ar, efficient  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: high-fidelity, gaussian splatting, ray tracing, ar, real-time rendering, efficient  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v2)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v2.pdf)  
  Keywords: relighting, human, relightable, lighting, gaussian splatting, avatar, ray tracing, shadow, geometry, ar, fast  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: relighting, efficient rendering, lighting, gaussian splatting, 3d gaussian, ray tracing, acceleration, ar, efficient  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: ray marching, dynamic, compact, gaussian splatting, 3d gaussian, acceleration, ar, animation, efficient  

### Relighting

*Showing the latest 50 out of 114 papers*

- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: face, reflection, 3d reconstruction, gaussian splatting, mapping, 3d gaussian, geometry, nerf, ar  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted
  Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v1)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v1.pdf)  
  Keywords: relighting, reflection, illumination, global illumination, lighting, gaussian splatting, geometry, light transport, ar, efficient  
- **[From Restoration to Reconstruction: Rethinking 3D Gaussian Splatting for
  Underwater Scenes](https://arxiv.org/abs/2509.17789v1)**  
  Authors: Guoxi Huang, Haoran Wang, Zipeng Qi, Wenjun Lu, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.17789v1.pdf)  
  Keywords: illumination, 3d reconstruction, lightweight, gaussian splatting, 3d gaussian, nerf, ar  
- **[RadarGaussianDet3D: An Efficient and Effective Gaussian-based 3D
  Detector with 4D Automotive Radars](https://arxiv.org/abs/2509.16119v1)**  
  Authors: Weiyi Xiong, Bing Zhu, Tao Huang, Zewei Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16119v1.pdf)  
  Keywords: 4d, lighting, gaussian splatting, 3d gaussian, autonomous driving, ar, fast, efficient  
- **[Camera Splatting for Continuous View Optimization](https://arxiv.org/abs/2509.15677v1)**  
  Authors: Gahye Lee, Hyomin Kim, Gwangjin Ju, Jooeun Son, Hyejeong Yoon, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15677v1.pdf)  
  Keywords: face, reflection, gaussian splatting, 3d gaussian, ar  
- **[ROSGS: Relightable Outdoor Scenes With Gaussian Splatting](https://arxiv.org/abs/2509.11275v1)**  
  Authors: Lianjun Liao, Chunhui Zhang, Tong Wu, Henglei Lv, Bailin Deng, Lin Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11275v1.pdf)  
  Keywords: relighting, compact, illumination, efficient rendering, relightable, outdoor, lighting, gaussian splatting, 3d gaussian, head, geometry, nerf, ar, efficient  
- **[On the Geometric Accuracy of Implicit and Primitive-based
  Representations Derived from View Rendering Constraints](https://arxiv.org/abs/2509.10241v2)**  
  Authors: Elias De Smijter, Renaud Detry, Christophe De Vleeschouwer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10241v2.pdf)  
  Keywords: robotics, compact, lighting, gaussian splatting, geometry, ar  
- **[DreamLifting: A Plug-in Module Lifting MV Diffusion Models for 3D Asset
  Generation](https://arxiv.org/abs/2509.07435v1)**  
  Authors: Ze-Xin Yin, Jiaxiong Qiu, Liu Liu, Xinjie Wang, Wei Sui, Zhizhong Su, Jian Yang, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.07435v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zx-yin.github.io/dreamlifting/.)  
  Keywords: relightable, lightweight, gaussian splatting, geometry, ar, efficient  
- **[ColorGS: High-fidelity Surgical Scene Reconstruction with Colored
  Gaussian Splatting](https://arxiv.org/abs/2508.18696v1)**  
  Authors: Qun Ji, Peng Li, Mingqiang Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18696v1.pdf)  
  Keywords: motion, dynamic, high-fidelity, lighting, gaussian splatting, deformation, vr, 3d gaussian, nerf, ar, real-time rendering, efficient  
- **[Fiducial Marker Splatting for High-Fidelity Robotics Simulations](https://arxiv.org/abs/2508.17012v1)**  
  Authors: Diram Tabaa, Gianni Di Caro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.17012v1.pdf)  
  Keywords: robotics, high-fidelity, lighting, gaussian splatting, neural rendering, localization, ar, efficient  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[Seeing Through Reflections: Advancing 3D Scene Reconstruction in
  Mirror-Containing Environments with Gaussian Splatting](https://arxiv.org/abs/2509.18956v1)**  
  Authors: Zijing Guo, Yunyang Zhao, Lin Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18956v1.pdf)  
  Keywords: face, reflection, 3d reconstruction, gaussian splatting, mapping, 3d gaussian, geometry, nerf, ar  
- **[ConfidentSplat: Confidence-Weighted Depth Fusion for Accurate 3D
  Gaussian Splatting SLAM](https://arxiv.org/abs/2509.16863v1)**  
  Authors: Amanuel T. Dufera, Yuan-Li Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16863v1.pdf)  
  Keywords: dynamic, high-fidelity, gaussian splatting, 3d gaussian, geometry, slam, ar, efficient  
- **[MCGS-SLAM: A Multi-Camera SLAM Framework Using Gaussian Splatting for
  High-Fidelity Mapping](https://arxiv.org/abs/2509.14191v1)**  
  Authors: Zhihao Cao, Hanyu Wu, Li Wa Tang, Zizhou Luo, Zihan Zhu, Wei Zhang, Marc Pollefeys, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14191v1.pdf)  
  Keywords: robotics, high-fidelity, mapping, gaussian splatting, 3d gaussian, autonomous driving, ar, slam  
- **[MemGS: Memory-Efficient Gaussian Splatting for Real-Time SLAM](https://arxiv.org/abs/2509.13536v1)**  
  Authors: Yinlong Bai, Hongxin Zhang, Sheng Zhong, Junkai Niu, Hai Li, Yijia He, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.13536v1.pdf)  
  Keywords: face, efficient, gaussian splatting, 3d gaussian, ar, slam  
- **[On the Skinning of Gaussian Avatars](https://arxiv.org/abs/2509.11411v1)**  
  Authors: Nikolaos Zioulis, Nikolaos Kotarelas, Georgios Albanis, Spyridon Thermos, Anargyros Chatzitofis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11411v1.pdf)  
  Keywords: human, gaussian splatting, deformation, mapping, avatar, ar, fast, efficient  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: efficient, mapping, gaussian splatting, understanding, ar, slam  
- **[DyPho-SLAM : Real-time Photorealistic SLAM in Dynamic Environments](https://arxiv.org/abs/2509.00741v1)**  
  Authors: Yi Liu, Keyu Fan, Bin Lan, Houde Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00741v1.pdf)  
  Keywords: dynamic, efficient, high-fidelity, gaussian splatting, mapping, localization, tracking, ar, slam  
- **[AGS: Accelerating 3D Gaussian Splatting SLAM via CODEC-Assisted Frame
  Covisibility Detection](https://arxiv.org/abs/2509.00433v1)**  
  Authors: Houshu He, Naifeng Jing, Li Jiang, Xiaoyao Liang, Zhuoran Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.00433v1.pdf)  
  Keywords: efficient, gaussian splatting, mapping, 3d gaussian, localization, acceleration, tracking, ar, slam  
- **[FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction
  with Large Gaussian Reconstruction Transformers](https://arxiv.org/abs/2508.19754v1)**  
  Authors: Yue Wu, Yufan Wu, Wen Li, Yuxi Lu, Kairui Feng, Xuanhong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.19754v1.pdf)  
  Keywords: face, high-fidelity, gaussian splatting, 3d gaussian, avatar, head, tracking, ar, animation, fast  
- **[PseudoMapTrainer: Learning Online Mapping without HD Maps](https://arxiv.org/abs/2508.18788v1)**  
  Authors: Christian Löwens, Thorben Funke, Jingchao Xie, Alexandru Paul Condurache  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.18788v1.pdf)  
  Keywords: face, semantic, gaussian splatting, mapping, segmentation, ar  

### Scene Understanding

*Showing the latest 50 out of 195 papers*

- **[4D Driving Scene Generation With Stereo Forcing](https://arxiv.org/abs/2509.20251v1)**  
  Authors: Hao Lu, Zhuang Ma, Guangfeng Jiang, Wenhang Ge, Bohan Li, Yuzhan Cai, Wenzhao Zheng, Yunpeng Zhang, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.20251v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiangxb98.github.io/PhiGensis}{PhiGensis}.)  
  Keywords: 4d, motion, dynamic, semantic, gaussian splatting, geometry, ar  
- **[SINGER: An Onboard Generalist Vision-Language Navigation Policy for
  Drones](https://arxiv.org/abs/2509.18610v1)**  
  Authors: Maximilian Adang, JunEn Low, Ola Shorinwa, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18610v1.pdf)  
  Keywords: semantic, lightweight, gaussian splatting, ar, efficient  
- **[Event-guided 3D Gaussian Splatting for Dynamic Human and Scene
  Reconstruction](https://arxiv.org/abs/2509.18566v1)**  
  Authors: Xiaoting Yin, Hao Shi, Kailun Yang, Jiajun Zhai, Shangwei Guo, Lin Wang, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18566v1.pdf)  
  Keywords: motion, human, dynamic, semantic, gaussian splatting, deformation, 3d gaussian, ar, animation, fast  
- **[ST-GS: Vision-Based 3D Semantic Occupancy Prediction with
  Spatial-Temporal Gaussian Splatting](https://arxiv.org/abs/2509.16552v1)**  
  Authors: Xiaoyang Yan, Muleilan Pei, Shaojie Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.16552v1.pdf)  
  Keywords: semantic, gaussian splatting, autonomous driving, understanding, head, geometry, ar  
- **[FingerSplat: Contactless Fingerprint 3D Reconstruction and Generation
  based on 3D Gaussian Splatting](https://arxiv.org/abs/2509.15648v1)**  
  Authors: Yuwei Jia, Yutang Lu, Zhe Cui, Fei Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15648v1.pdf)  
  Keywords: recognition, 3d reconstruction, gaussian splatting, 3d gaussian, ar  
- **[MS-GS: Multi-Appearance Sparse-View 3D Gaussian Splatting in the Wild](https://arxiv.org/abs/2509.15548v2)**  
  Authors: Deming Li, Kaiwen Jiang, Yutao Tang, Ravi Ramamoorthi, Rama Chellappa, Cheng Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.15548v2.pdf)  
  Keywords: motion, semantic, gaussian splatting, 3d gaussian, geometry, sparse-view, nerf, ar  
- **[FMGS-Avatar: Mesh-Guided 2D Gaussian Splatting with Foundation Model
  Priors for 3D Monocular Avatar Reconstruction](https://arxiv.org/abs/2509.14739v1)**  
  Authors: Jinlong Fan, Bingyu Hu, Xingguang Li, Yuxiang Yang, Jing Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.14739v1.pdf)  
  Keywords: face, human, semantic, high-fidelity, gaussian splatting, 3d gaussian, avatar, ar  
- **[Beyond Averages: Open-Vocabulary 3D Scene Understanding with Gaussian
  Splatting and Bag of Embeddings](https://arxiv.org/abs/2509.12938v1)**  
  Authors: Abdalla Arafa, Didier Stricker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.12938v1.pdf)  
  Keywords: robotics, semantic, vr, gaussian splatting, 3d gaussian, segmentation, understanding, ar  
- **[Segmentation-Driven Initialization for Sparse-view 3D Gaussian Splatting](https://arxiv.org/abs/2509.11853v1)**  
  Authors: Yi-Hsin Li, Thomas Sikora, Sebastian Knorr, Måarten Sjöström  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.11853v1.pdf)  
  Keywords: motion, gaussian splatting, 3d gaussian, segmentation, geometry, sparse-view, ar, real-time rendering, fast  
- **[Real-time Photorealistic Mapping for Situational Awareness in Robot
  Teleoperation](https://arxiv.org/abs/2509.06433v2)**  
  Authors: Ian Page, Pierre Susbielle, Olivier Aycard, Pierre-Brice Wieber  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.06433v2.pdf)  
  Keywords: efficient, mapping, gaussian splatting, understanding, ar, slam  



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