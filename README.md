# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-08-11 01:00:51

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

- [3DGS Surveys](#3dgs-surveys) (19 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (274 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (323 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (393 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (69 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (316 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (66 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (403 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (164 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (18 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (108 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (156 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (193 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v1.pdf)  
  Keywords: understanding, robotics, ar, semantic, survey, gaussian splatting, efficient, 3d gaussian, nerf  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: ar, survey, 3d gaussian, gaussian splatting, robotics, human, nerf  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: ar, geometry, sparse-view, motion, 3d reconstruction, vr, survey, gaussian splatting, robotics, 3d gaussian, nerf  
- **[Advances in Feed-Forward 3D Reconstruction and View Synthesis: A Survey](https://arxiv.org/abs/2507.14501v2)**  
  Authors: Jiahui Zhang, Yuelei Li, Anpei Chen, Muyu Xu, Kunhao Liu, Jianyuan Wang, Xiao-Xiao Long, Hanxue Liang, Zexiang Xu, Hao Su, Christian Theobalt, Christian Rupprecht, Andrea Vedaldi, Hanspeter Pfister, Shijian Lu, Fangneng Zhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14501v2.pdf)  
  Keywords: ar, robotics, fast, 3d reconstruction, vr, survey, dynamic, gaussian splatting, slam, human, 3d gaussian, lighting, nerf  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: ar, high-fidelity, survey, autonomous driving, face, dynamic, gaussian splatting, outdoor, efficient, 3d gaussian, nerf  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: ar, high-fidelity, 3d reconstruction, vr, survey, neural rendering, autonomous driving, gaussian splatting, robotics, 3d gaussian, nerf  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: understanding, ar, high-fidelity, 3d reconstruction, semantic, segmentation, survey, neural rendering, gaussian splatting, outdoor, efficient, 3d gaussian  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: ar, mapping, localization, semantic, segmentation, survey, gaussian splatting, slam, efficient, 3d gaussian, nerf  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: understanding, ar, body, motion, survey, dynamic, gaussian splatting, 3d gaussian, 4d  
- **[A Survey of 3D Reconstruction with Event Cameras](https://arxiv.org/abs/2505.08438v2)**  
  Authors: Chuanzhi Xu, Haoxian Zhou, Langyi Chen, Haodong Chen, Ying Zhou, Vera Chung, Qiang Qu, Weidong Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.08438v2.pdf)  
  Keywords: ar, illumination, geometry, motion, 3d reconstruction, survey, neural rendering, autonomous driving, dynamic, gaussian splatting, robotics, 3d gaussian, nerf  

### Acceleration

*Showing the latest 50 out of 274 papers*

- **[GAP: Gaussianize Any Point Clouds with Text Guidance](https://arxiv.org/abs/2508.05631v1)**  
  Authors: Weiqi Zhang, Junsheng Zhou, Haotian Geng, Wenyuan Zhang, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05631v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/GAP.)  
  Keywords: ar, high-fidelity, fast, face, gaussian splatting, 3d gaussian  
- **[3DGabSplat: 3D Gabor Splatting for Frequency-adaptive Radiance Field
  Rendering](https://arxiv.org/abs/2508.05343v1)**  
  Authors: Junyu Zhou, Yuyang Huang, Wenrui Dai, Junni Zou, Ziyang Zheng, Nuowen Kan, Chenglin Li, Hongkai Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05343v1.pdf)  
  Keywords: ar, high-fidelity, head, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[CF3: Compact and Fast 3D Feature Fields](https://arxiv.org/abs/2508.05254v2)**  
  Authors: Hyunjoon Lee, Joonkyu Min, Jaesik Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05254v2.pdf)  
  Keywords: ar, fast, 3d gaussian, gaussian splatting, efficient, compact  
- **[Perceive-Sample-Compress: Towards Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2508.04965v1)**  
  Authors: Zijian Wang, Beizhen Zhao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04965v1.pdf)  
  Keywords: ar, compression, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[Duplex-GS: Proxy-Guided Weighted Blending for Real-Time
  Order-Independent Gaussian Splatting](https://arxiv.org/abs/2508.03180v1)**  
  Authors: Weihang Liu, Yuke Li, Yuxuan Li, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03180v1.pdf)  
  Keywords: ar, head, gaussian splatting, acceleration, 3d gaussian  
- **[H3R: Hybrid Multi-view Correspondence for Generalizable 3D
  Reconstruction](https://arxiv.org/abs/2508.03118v1)**  
  Authors: Heng Jia, Linchao Zhu, Na Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03118v1.pdf)  
  Keywords: ar, fast, 3d reconstruction, semantic, face, gaussian splatting, efficient, 3d gaussian  
- **[RobustGS: Unified Boosting of Feedforward 3D Gaussian Splatting under
  Low-Quality Conditions](https://arxiv.org/abs/2508.03077v1)**  
  Authors: Anran Wu, Long Peng, Xin Di, Xueyuan Dai, Chen Wu, Yang Wang, Xueyang Fu, Yang Cao, Zheng-Jun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03077v1.pdf)  
  Keywords: ar, geometry, fast, 3d reconstruction, semantic, gaussian splatting, efficient, 3d gaussian  
- **[GENIE: Gaussian Encoding for Neural Radiance Fields Interactive Editing](https://arxiv.org/abs/2508.02831v1)**  
  Authors: Mikołaj Zieliński, Krzysztof Byrski, Tomasz Szczepanik, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02831v1.pdf)  
  Keywords: ar, high-fidelity, geometry, fast, neural rendering, real-time rendering, dynamic, gaussian splatting, efficient, nerf  
- **[PMGS: Reconstruction of Projectile Motion across Large Spatiotemporal
  Spans via 3D Gaussian Splatting](https://arxiv.org/abs/2508.02660v1)**  
  Authors: Yijun Xu, Jingrui Zhang, Yuhan Chen, Dingwen Wang, Lei Yu, Chu He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02660v1.pdf)  
  Keywords: ar, deformation, motion, dynamic, gaussian splatting, acceleration, 3d gaussian  
- **[VDEGaussian: Video Diffusion Enhanced 4D Gaussian Splatting for Dynamic
  Urban Scenes Modeling](https://arxiv.org/abs/2508.02129v1)**  
  Authors: Yuru Xiao, Zihan Lin, Chao Lu, Deming Zhai, Kui Jiang, Wenbo Zhao, Wei Zhang, Junjun Jiang, Huanran Wang, Xianming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02129v1.pdf)  
  Keywords: ar, high-fidelity, fast, urban scene, face, dynamic, gaussian splatting, 4d  

### Applications

*Showing the latest 50 out of 995 papers*

- **[GAP: Gaussianize Any Point Clouds with Text Guidance](https://arxiv.org/abs/2508.05631v1)**  
  Authors: Weiqi Zhang, Junsheng Zhou, Haotian Geng, Wenyuan Zhang, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05631v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/GAP.)  
  Keywords: ar, high-fidelity, fast, face, gaussian splatting, 3d gaussian  
- **[3DGabSplat: 3D Gabor Splatting for Frequency-adaptive Radiance Field
  Rendering](https://arxiv.org/abs/2508.05343v1)**  
  Authors: Junyu Zhou, Yuyang Huang, Wenrui Dai, Junni Zou, Ziyang Zheng, Nuowen Kan, Chenglin Li, Hongkai Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05343v1.pdf)  
  Keywords: ar, high-fidelity, head, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[CF3: Compact and Fast 3D Feature Fields](https://arxiv.org/abs/2508.05254v2)**  
  Authors: Hyunjoon Lee, Joonkyu Min, Jaesik Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05254v2.pdf)  
  Keywords: ar, fast, 3d gaussian, gaussian splatting, efficient, compact  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v1.pdf)  
  Keywords: understanding, robotics, ar, semantic, survey, gaussian splatting, efficient, 3d gaussian, nerf  
- **[UGOD: Uncertainty-Guided Differentiable Opacity and Soft Dropout for
  Enhanced Sparse-View 3DGS](https://arxiv.org/abs/2508.04968v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04968v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, 3d gaussian, nerf  
- **[Laplacian Analysis Meets Dynamics Modelling: Gaussian Splatting for 4D
  Reconstruction](https://arxiv.org/abs/2508.04966v1)**  
  Authors: Yifan Zhou, Beizhen Zhao, Pengcheng Wu, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04966v1.pdf)  
  Keywords: ar, deformation, motion, dynamic, gaussian splatting, efficient, 3d gaussian, 4d  
- **[Perceive-Sample-Compress: Towards Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2508.04965v1)**  
  Authors: Zijian Wang, Beizhen Zhao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04965v1.pdf)  
  Keywords: ar, compression, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[CryoGS: Gaussian Splatting for Cryo-EM Homogeneous Reconstruction](https://arxiv.org/abs/2508.04929v1)**  
  Authors: Suyi Chen, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04929v1.pdf)  
  Keywords: ar, efficient, compact, gaussian splatting  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: ar, survey, 3d gaussian, gaussian splatting, robotics, human, nerf  
- **[MuGS: Multi-Baseline Generalizable Gaussian Splatting Reconstruction](https://arxiv.org/abs/2508.04297v1)**  
  Authors: Yaopeng Lou, Liao Shen, Tianqi Liu, Jiaqi Li, Zihao Huang, Huiqiang Sun, Zhiguo Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04297v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, outdoor, 3d gaussian, nerf  

### Avatar Generation

*Showing the latest 50 out of 323 papers*

- **[GAP: Gaussianize Any Point Clouds with Text Guidance](https://arxiv.org/abs/2508.05631v1)**  
  Authors: Weiqi Zhang, Junsheng Zhou, Haotian Geng, Wenyuan Zhang, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05631v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/GAP.)  
  Keywords: ar, high-fidelity, fast, face, gaussian splatting, 3d gaussian  
- **[3DGabSplat: 3D Gabor Splatting for Frequency-adaptive Radiance Field
  Rendering](https://arxiv.org/abs/2508.05343v1)**  
  Authors: Junyu Zhou, Yuyang Huang, Wenrui Dai, Junni Zou, Ziyang Zheng, Nuowen Kan, Chenglin Li, Hongkai Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05343v1.pdf)  
  Keywords: ar, high-fidelity, head, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned
  and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: ar, survey, 3d gaussian, gaussian splatting, robotics, human, nerf  
- **[Duplex-GS: Proxy-Guided Weighted Blending for Real-Time
  Order-Independent Gaussian Splatting](https://arxiv.org/abs/2508.03180v1)**  
  Authors: Weihang Liu, Yuke Li, Yuxuan Li, Jingyi Yu, Xin Lou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03180v1.pdf)  
  Keywords: ar, head, gaussian splatting, acceleration, 3d gaussian  
- **[H3R: Hybrid Multi-view Correspondence for Generalizable 3D
  Reconstruction](https://arxiv.org/abs/2508.03118v1)**  
  Authors: Heng Jia, Linchao Zhu, Na Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03118v1.pdf)  
  Keywords: ar, fast, 3d reconstruction, semantic, face, gaussian splatting, efficient, 3d gaussian  
- **[VDEGaussian: Video Diffusion Enhanced 4D Gaussian Splatting for Dynamic
  Urban Scenes Modeling](https://arxiv.org/abs/2508.02129v1)**  
  Authors: Yuru Xiao, Zihan Lin, Chao Lu, Deming Zhai, Kui Jiang, Wenbo Zhao, Wei Zhang, Junjun Jiang, Huanran Wang, Xianming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02129v1.pdf)  
  Keywords: ar, high-fidelity, fast, urban scene, face, dynamic, gaussian splatting, 4d  
- **[From Photons to Physics: Autonomous Indoor Drones and the Future of
  Objective Property Assessment](https://arxiv.org/abs/2508.01965v1)**  
  Authors: Petteri Teikari, Mike Jarrell, Irene Bandera Moreno, Harri Pesola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01965v1.pdf)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, human  
- **[OCSplats: Observation Completeness Quantification and Label Noise
  Separation in 3DGS](https://arxiv.org/abs/2508.01239v1)**  
  Authors: Han Ling, Xian Xu, Yinghui Sun, Quansen Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01239v1.pdf)  
  Keywords: ar, shadow, 3d reconstruction, face, dynamic, gaussian splatting, 3d gaussian  
- **[Omni-Scan: Creating Visually-Accurate Digital Twin Object Models Using a
  Bimanual Robot with Handover and Gaussian Splat Merging](https://arxiv.org/abs/2508.00354v1)**  
  Authors: Tianshuang Qiu, Zehan Ma, Karim El-Refai, Hiya Shah, Chung Min Kim, Justin Kerr, Ken Goldberg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.00354v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://berkeleyautomation.github.io/omni-scan/)  
  Keywords: ar, 3d gaussian, face  
- **[SeqAffordSplat: Scene-level Sequential Affordance Reasoning on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.23772v1)**  
  Authors: Di Li, Jie Feng, Jiahao Chen, Weisheng Dong, Guanbin Li, Yuhui Zheng, Mingtao Feng, Guangming Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23772v1.pdf)  
  Keywords: understanding, ar, geometry, semantic, segmentation, 3d gaussian, gaussian splatting, human  

### Dynamic Scene

*Showing the latest 50 out of 393 papers*

- **[Refining Gaussian Splatting: A Volumetric Densification Approach](https://arxiv.org/abs/2508.05187v1)**  
  Authors: Mohamed Abdul Gafoor, Marius Preda, Titus Zaharia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05187v1.pdf)  
  Keywords: 3d gaussian, motion, nerf, gaussian splatting  
- **[Laplacian Analysis Meets Dynamics Modelling: Gaussian Splatting for 4D
  Reconstruction](https://arxiv.org/abs/2508.04966v1)**  
  Authors: Yifan Zhou, Beizhen Zhao, Pengcheng Wu, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04966v1.pdf)  
  Keywords: ar, deformation, motion, dynamic, gaussian splatting, efficient, 3d gaussian, 4d  
- **[SplitGaussian: Reconstructing Dynamic Scenes via Visual Geometry
  Decomposition](https://arxiv.org/abs/2508.04224v1)**  
  Authors: Jiahui Li, Shengeng Tang, Jingxuan He, Gang Huang, Zhangye Wang, Yantao Pan, Lechao Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04224v1.pdf)  
  Keywords: ar, geometry, motion, dynamic, gaussian splatting  
- **[RLGS: Reinforcement Learning-Based Adaptive Hyperparameter Tuning for
  Gaussian Splatting](https://arxiv.org/abs/2508.04078v1)**  
  Authors: Zhan Li, Huangying Zhan, Changyang Li, Qingan Yan, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04078v1.pdf)  
  Keywords: ar, dynamic, gaussian splatting, 3d gaussian, lightweight  
- **[GENIE: Gaussian Encoding for Neural Radiance Fields Interactive Editing](https://arxiv.org/abs/2508.02831v1)**  
  Authors: Mikołaj Zieliński, Krzysztof Byrski, Tomasz Szczepanik, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02831v1.pdf)  
  Keywords: ar, high-fidelity, geometry, fast, neural rendering, real-time rendering, dynamic, gaussian splatting, efficient, nerf  
- **[PMGS: Reconstruction of Projectile Motion across Large Spatiotemporal
  Spans via 3D Gaussian Splatting](https://arxiv.org/abs/2508.02660v1)**  
  Authors: Yijun Xu, Jingrui Zhang, Yuhan Chen, Dingwen Wang, Lei Yu, Chu He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02660v1.pdf)  
  Keywords: ar, deformation, motion, dynamic, gaussian splatting, acceleration, 3d gaussian  
- **[Low-Frequency First: Eliminating Floating Artifacts in 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.02493v2)**  
  Authors: Jianchao Wang, Peng Zhou, Cen Li, Rong Quan, Jie Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02493v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jcwang-gh.github.io/EFA-GS.)  
  Keywords: ar, geometry, 3d reconstruction, dynamic, gaussian splatting, efficient, 3d gaussian  
- **[VDEGaussian: Video Diffusion Enhanced 4D Gaussian Splatting for Dynamic
  Urban Scenes Modeling](https://arxiv.org/abs/2508.02129v1)**  
  Authors: Yuru Xiao, Zihan Lin, Chao Lu, Deming Zhai, Kui Jiang, Wenbo Zhao, Wei Zhang, Junjun Jiang, Huanran Wang, Xianming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02129v1.pdf)  
  Keywords: ar, high-fidelity, fast, urban scene, face, dynamic, gaussian splatting, 4d  
- **[OCSplats: Observation Completeness Quantification and Label Noise
  Separation in 3DGS](https://arxiv.org/abs/2508.01239v1)**  
  Authors: Han Ling, Xian Xu, Yinghui Sun, Quansen Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01239v1.pdf)  
  Keywords: ar, shadow, 3d reconstruction, face, dynamic, gaussian splatting, 3d gaussian  
- **[Gaussian Variation Field Diffusion for High-fidelity Video-to-4D
  Synthesis](https://arxiv.org/abs/2507.23785v1)**  
  Authors: Bowen Zhang, Sicheng Xu, Chuxin Wang, Jiaolong Yang, Feng Zhao, Dong Chen, Baining Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23785v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gvfdiffusion.github.io/.)  
  Keywords: ar, high-fidelity, motion, dynamic, animation, efficient, compact, 4d  

### Few-shot

*Showing the latest 50 out of 69 papers*

- **[UGOD: Uncertainty-Guided Differentiable Opacity and Soft Dropout for
  Enhanced Sparse-View 3DGS](https://arxiv.org/abs/2508.04968v1)**  
  Authors: Zhihao Guo, Peng Wang, Zidong Chen, Xiangyu Kong, Yan Lyu, Guanyu Gao, Liangxiu Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04968v1.pdf)  
  Keywords: ar, sparse-view, gaussian splatting, 3d gaussian, nerf  
- **[DET-GS: Depth- and Edge-Aware Regularization for High-Fidelity 3D
  Gaussian Splatting](https://arxiv.org/abs/2508.04099v1)**  
  Authors: Zexu Huang, Min Xu, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04099v1.pdf)  
  Keywords: ar, high-fidelity, sparse-view, semantic, gaussian splatting, efficient, 3d gaussian  
- **[GR-Gaussian: Graph-Based Radiative Gaussian Splatting for Sparse-View CT
  Reconstruction](https://arxiv.org/abs/2508.02408v2)**  
  Authors: Yikuang Yuluo, Yue Ma, Kuan Shen, Tongtong Jin, Wang Liao, Yangpu Ma, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02408v2.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting  
- **[No Pose at All: Self-Supervised Pose-Free 3D Gaussian Splatting from
  Sparse Views](https://arxiv.org/abs/2508.01171v1)**  
  Authors: Ranran Huang, Krystian Mikolajczyk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01171v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ranrhuang.github.io/spfsplat/.)  
  Keywords: ar, geometry, gaussian splatting, efficient, 3d gaussian, sparse view  
- **[Sparse-View 3D Reconstruction: Recent Advances and Open Challenges](https://arxiv.org/abs/2507.16406v1)**  
  Authors: Tanveer Younis, Zhanglin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.16406v1.pdf)  
  Keywords: ar, geometry, sparse-view, motion, 3d reconstruction, vr, survey, gaussian splatting, robotics, 3d gaussian, nerf  
- **[DWTGS: Rethinking Frequency Regularization for Sparse-view 3D Gaussian
  Splatting](https://arxiv.org/abs/2507.15690v1)**  
  Authors: Hung Nguyen, Runfa Li, An Le, Truong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15690v1.pdf)  
  Keywords: ar, 3d gaussian, sparse-view, gaussian splatting  
- **[SurfaceSplat: Connecting Surface Reconstruction and Gaussian Splatting](https://arxiv.org/abs/2507.15602v2)**  
  Authors: Zihui Gao, Jia-Wang Bian, Guosheng Lin, Hao Chen, Chunhua Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15602v2.pdf)  
  Keywords: ar, geometry, sparse-view, face, gaussian splatting, 3d gaussian  
- **[DCHM: Depth-Consistent Human Modeling for Multiview Detection](https://arxiv.org/abs/2507.14505v1)**  
  Authors: Jiahao Ma, Tianyu Wang, Miaomiao Liu, David Ahmedt-Aristizabal, Chuong Nguyen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.14505v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jiahao-ma.github.io/DCHM/}{project)  
  Keywords: ar, localization, sparse-view, segmentation, gaussian splatting, human  
- **[BRUM: Robust 3D Vehicle Reconstruction from 360 Sparse Images](https://arxiv.org/abs/2507.12095v1)**  
  Authors: Davide Di Nucci, Matteo Tomei, Guido Borghi, Luca Ciuffreda, Roberto Vezzani, Rita Cucchiara  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.12095v1.pdf)  
  Keywords: ar, sparse-view, motion, 3d reconstruction, gaussian splatting  
- **[TRAN-D: 2D Gaussian Splatting-based Sparse-view Transparent Object Depth
  Reconstruction via Physics Simulation for Scene Update](https://arxiv.org/abs/2507.11069v2)**  
  Authors: Jeongyun Kim, Seunghoon Jeong, Giseop Kim, Myung-Hwan Jeon, Eunji Jun, Ayoung Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.11069v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jeongyun0609.github.io/TRAN-D/.)  
  Keywords: understanding, ar, geometry, sparse-view, face, reflection, gaussian splatting, dynamic, sparse view  

### Geometry Reconstruction

*Showing the latest 50 out of 316 papers*

- **[MuGS: Multi-Baseline Generalizable Gaussian Splatting Reconstruction](https://arxiv.org/abs/2508.04297v1)**  
  Authors: Yaopeng Lou, Liao Shen, Tianqi Liu, Jiaqi Li, Zihao Huang, Huiqiang Sun, Zhiguo Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04297v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, outdoor, 3d gaussian, nerf  
- **[SplitGaussian: Reconstructing Dynamic Scenes via Visual Geometry
  Decomposition](https://arxiv.org/abs/2508.04224v1)**  
  Authors: Jiahui Li, Shengeng Tang, Jingxuan He, Gang Huang, Zhangye Wang, Yantao Pan, Lechao Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04224v1.pdf)  
  Keywords: ar, geometry, motion, dynamic, gaussian splatting  
- **[Bridging Diffusion Models and 3D Representations: A 3D Consistent
  Super-Resolution Framework](https://arxiv.org/abs/2508.04090v1)**  
  Authors: Yi-Ting Chen, Ting-Hsuan Liao, Pengsheng Guo, Alexander Schwing, Jia-Bin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04090v1.pdf)  
  Keywords: ar, 3d gaussian, nerf, 3d reconstruction  
- **[H3R: Hybrid Multi-view Correspondence for Generalizable 3D
  Reconstruction](https://arxiv.org/abs/2508.03118v1)**  
  Authors: Heng Jia, Linchao Zhu, Na Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03118v1.pdf)  
  Keywords: ar, fast, 3d reconstruction, semantic, face, gaussian splatting, efficient, 3d gaussian  
- **[RobustGS: Unified Boosting of Feedforward 3D Gaussian Splatting under
  Low-Quality Conditions](https://arxiv.org/abs/2508.03077v1)**  
  Authors: Anran Wu, Long Peng, Xin Di, Xueyuan Dai, Chen Wu, Yang Wang, Xueyang Fu, Yang Cao, Zheng-Jun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03077v1.pdf)  
  Keywords: ar, geometry, fast, 3d reconstruction, semantic, gaussian splatting, efficient, 3d gaussian  
- **[GENIE: Gaussian Encoding for Neural Radiance Fields Interactive Editing](https://arxiv.org/abs/2508.02831v1)**  
  Authors: Mikołaj Zieliński, Krzysztof Byrski, Tomasz Szczepanik, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02831v1.pdf)  
  Keywords: ar, high-fidelity, geometry, fast, neural rendering, real-time rendering, dynamic, gaussian splatting, efficient, nerf  
- **[Low-Frequency First: Eliminating Floating Artifacts in 3D Gaussian
  Splatting](https://arxiv.org/abs/2508.02493v2)**  
  Authors: Jianchao Wang, Peng Zhou, Cen Li, Rong Quan, Jie Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02493v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://jcwang-gh.github.io/EFA-GS.)  
  Keywords: ar, geometry, 3d reconstruction, dynamic, gaussian splatting, efficient, 3d gaussian  
- **[GaussianCross: Cross-modal Self-supervised 3D Representation Learning
  via Gaussian Splatting](https://arxiv.org/abs/2508.02172v1)**  
  Authors: Lei Yao, Yi Wang, Yi Zhang, Moyun Liu, Lap-Pui Chau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rayyoh.github.io/GaussianCross/}{https://rayyoh.github.io/GaussianCross/}.)  
  Keywords: understanding, ar, geometry, semantic, segmentation, gaussian splatting, 3d gaussian  
- **[ScrewSplat: An End-to-End Method for Articulated Object Recognition](https://arxiv.org/abs/2508.02146v1)**  
  Authors: Seungyeon Kim, Junsu Ha, Young Hun Kim, Yonghyeon Lee, Frank C. Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02146v1.pdf)  
  Keywords: geometry, ar, recognition, gaussian splatting  
- **[OCSplats: Observation Completeness Quantification and Label Noise
  Separation in 3DGS](https://arxiv.org/abs/2508.01239v1)**  
  Authors: Han Ling, Xian Xu, Yinghui Sun, Quansen Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01239v1.pdf)  
  Keywords: ar, shadow, 3d reconstruction, face, dynamic, gaussian splatting, 3d gaussian  

### Large Scene

*Showing the latest 50 out of 66 papers*

- **[MuGS: Multi-Baseline Generalizable Gaussian Splatting Reconstruction](https://arxiv.org/abs/2508.04297v1)**  
  Authors: Yaopeng Lou, Liao Shen, Tianqi Liu, Jiaqi Li, Zihao Huang, Huiqiang Sun, Zhiguo Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04297v1.pdf)  
  Keywords: ar, geometry, gaussian splatting, outdoor, 3d gaussian, nerf  
- **[VDEGaussian: Video Diffusion Enhanced 4D Gaussian Splatting for Dynamic
  Urban Scenes Modeling](https://arxiv.org/abs/2508.02129v1)**  
  Authors: Yuru Xiao, Zihan Lin, Chao Lu, Deming Zhai, Kui Jiang, Wenbo Zhao, Wei Zhang, Junjun Jiang, Huanran Wang, Xianming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02129v1.pdf)  
  Keywords: ar, high-fidelity, fast, urban scene, face, dynamic, gaussian splatting, 4d  
- **[Stereo 3D Gaussian Splatting SLAM for Outdoor Urban Scenes](https://arxiv.org/abs/2507.23677v1)**  
  Authors: Xiaohan Li, Ziren Gong, Fabio Tosi, Matteo Poggi, Stefano Mattoccia, Dong Liu, Jun Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23677v1.pdf)  
  Keywords: tracking, mapping, high-fidelity, ar, fast, gaussian splatting, slam, outdoor, 3d gaussian, urban scene  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: ar, global illumination, illumination, shadow, relightable, face, dynamic, gaussian splatting, outdoor, relighting, 3d gaussian, lighting  
- **[SaLF: Sparse Local Fields for Multi-Sensor Rendering in Real-Time](https://arxiv.org/abs/2507.18713v1)**  
  Authors: Yun Chen, Matthew Haines, Jingkang Wang, Krzysztof Baron-Lis, Sivabalan Manivasagam, Ze Yang, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18713v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://waabi.ai/salf/)  
  Keywords: ar, high-fidelity, fast, large scene, gaussian splatting, 3d gaussian, nerf  
- **[Unposed 3DGS Reconstruction with Probabilistic Procrustes Mapping](https://arxiv.org/abs/2507.18541v1)**  
  Authors: Chong Cheng, Zijian Wang, Sicheng Yu, Yu Hu, Nanjie Yao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18541v1.pdf)  
  Keywords: ar, mapping, geometry, gaussian splatting, outdoor, 3d gaussian  
- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: understanding, ar, motion, segmentation, dynamic, gaussian splatting, outdoor, 3d gaussian, 4d, nerf  
- **[3DGS_LSR:Large_Scale Relocation for Autonomous Driving Based on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.05661v1)**  
  Authors: Haitao Lu, Haijier Chen, Haoze Liu, Shoujian Zhang, Bo Xu, Ziao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05661v1.pdf)  
  Keywords: ar, mapping, localization, autonomous driving, gaussian splatting, outdoor, 3d gaussian  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: ar, high-fidelity, autonomous driving, real-time rendering, dynamic, gaussian splatting, 3d gaussian, urban scene  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v2)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: tracking, mapping, high-fidelity, ar, dynamic, gaussian splatting, slam, outdoor, 3d gaussian  

### Model Compression

*Showing the latest 50 out of 403 papers*

- **[3DGabSplat: 3D Gabor Splatting for Frequency-adaptive Radiance Field
  Rendering](https://arxiv.org/abs/2508.05343v1)**  
  Authors: Junyu Zhou, Yuyang Huang, Wenrui Dai, Junni Zou, Ziyang Zheng, Nuowen Kan, Chenglin Li, Hongkai Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05343v1.pdf)  
  Keywords: ar, high-fidelity, head, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[CF3: Compact and Fast 3D Feature Fields](https://arxiv.org/abs/2508.05254v2)**  
  Authors: Hyunjoon Lee, Joonkyu Min, Jaesik Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05254v2.pdf)  
  Keywords: ar, fast, 3d gaussian, gaussian splatting, efficient, compact  
- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v1.pdf)  
  Keywords: understanding, robotics, ar, semantic, survey, gaussian splatting, efficient, 3d gaussian, nerf  
- **[Laplacian Analysis Meets Dynamics Modelling: Gaussian Splatting for 4D
  Reconstruction](https://arxiv.org/abs/2508.04966v1)**  
  Authors: Yifan Zhou, Beizhen Zhao, Pengcheng Wu, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04966v1.pdf)  
  Keywords: ar, deformation, motion, dynamic, gaussian splatting, efficient, 3d gaussian, 4d  
- **[Perceive-Sample-Compress: Towards Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2508.04965v1)**  
  Authors: Zijian Wang, Beizhen Zhao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04965v1.pdf)  
  Keywords: ar, compression, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[CryoGS: Gaussian Splatting for Cryo-EM Homogeneous Reconstruction](https://arxiv.org/abs/2508.04929v1)**  
  Authors: Suyi Chen, Haibin Ling  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04929v1.pdf)  
  Keywords: ar, efficient, compact, gaussian splatting  
- **[DET-GS: Depth- and Edge-Aware Regularization for High-Fidelity 3D
  Gaussian Splatting](https://arxiv.org/abs/2508.04099v1)**  
  Authors: Zexu Huang, Min Xu, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04099v1.pdf)  
  Keywords: ar, high-fidelity, sparse-view, semantic, gaussian splatting, efficient, 3d gaussian  
- **[RLGS: Reinforcement Learning-Based Adaptive Hyperparameter Tuning for
  Gaussian Splatting](https://arxiv.org/abs/2508.04078v1)**  
  Authors: Zhan Li, Huangying Zhan, Changyang Li, Qingan Yan, Yi Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04078v1.pdf)  
  Keywords: ar, dynamic, gaussian splatting, 3d gaussian, lightweight  
- **[H3R: Hybrid Multi-view Correspondence for Generalizable 3D
  Reconstruction](https://arxiv.org/abs/2508.03118v1)**  
  Authors: Heng Jia, Linchao Zhu, Na Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03118v1.pdf)  
  Keywords: ar, fast, 3d reconstruction, semantic, face, gaussian splatting, efficient, 3d gaussian  
- **[RobustGS: Unified Boosting of Feedforward 3D Gaussian Splatting under
  Low-Quality Conditions](https://arxiv.org/abs/2508.03077v1)**  
  Authors: Anran Wu, Long Peng, Xin Di, Xueyuan Dai, Chen Wu, Yang Wang, Xueyang Fu, Yang Cao, Zheng-Jun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03077v1.pdf)  
  Keywords: ar, geometry, fast, 3d reconstruction, semantic, gaussian splatting, efficient, 3d gaussian  

### Quality Enhancement

*Showing the latest 50 out of 164 papers*

- **[GAP: Gaussianize Any Point Clouds with Text Guidance](https://arxiv.org/abs/2508.05631v1)**  
  Authors: Weiqi Zhang, Junsheng Zhou, Haotian Geng, Wenyuan Zhang, Yu-Shen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05631v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://weiqi-zhang.github.io/GAP.)  
  Keywords: ar, high-fidelity, fast, face, gaussian splatting, 3d gaussian  
- **[3DGabSplat: 3D Gabor Splatting for Frequency-adaptive Radiance Field
  Rendering](https://arxiv.org/abs/2508.05343v1)**  
  Authors: Junyu Zhou, Yuyang Huang, Wenrui Dai, Junni Zou, Ziyang Zheng, Nuowen Kan, Chenglin Li, Hongkai Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05343v1.pdf)  
  Keywords: ar, high-fidelity, head, real-time rendering, gaussian splatting, efficient, 3d gaussian  
- **[DET-GS: Depth- and Edge-Aware Regularization for High-Fidelity 3D
  Gaussian Splatting](https://arxiv.org/abs/2508.04099v1)**  
  Authors: Zexu Huang, Min Xu, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04099v1.pdf)  
  Keywords: ar, high-fidelity, sparse-view, semantic, gaussian splatting, efficient, 3d gaussian  
- **[GENIE: Gaussian Encoding for Neural Radiance Fields Interactive Editing](https://arxiv.org/abs/2508.02831v1)**  
  Authors: Mikołaj Zieliński, Krzysztof Byrski, Tomasz Szczepanik, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02831v1.pdf)  
  Keywords: ar, high-fidelity, geometry, fast, neural rendering, real-time rendering, dynamic, gaussian splatting, efficient, nerf  
- **[VDEGaussian: Video Diffusion Enhanced 4D Gaussian Splatting for Dynamic
  Urban Scenes Modeling](https://arxiv.org/abs/2508.02129v1)**  
  Authors: Yuru Xiao, Zihan Lin, Chao Lu, Deming Zhai, Kui Jiang, Wenbo Zhao, Wei Zhang, Junjun Jiang, Huanran Wang, Xianming Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02129v1.pdf)  
  Keywords: ar, high-fidelity, fast, urban scene, face, dynamic, gaussian splatting, 4d  
- **[Gaussian Variation Field Diffusion for High-fidelity Video-to-4D
  Synthesis](https://arxiv.org/abs/2507.23785v1)**  
  Authors: Bowen Zhang, Sicheng Xu, Chuxin Wang, Jiaolong Yang, Feng Zhao, Dong Chen, Baining Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23785v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gvfdiffusion.github.io/.)  
  Keywords: ar, high-fidelity, motion, dynamic, animation, efficient, compact, 4d  
- **[Enhanced Velocity Field Modeling for Gaussian Video Reconstruction](https://arxiv.org/abs/2507.23704v1)**  
  Authors: Zhenyang Li, Xiaoyang Bai, Tongchen Zhang, Pengfei Shen, Weiwei Xu, Yifan Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23704v1.pdf)  
  Keywords: ar, high-fidelity, deformation, motion, vr, real-time rendering, dynamic, gaussian splatting, 3d gaussian  
- **[Stereo 3D Gaussian Splatting SLAM for Outdoor Urban Scenes](https://arxiv.org/abs/2507.23677v1)**  
  Authors: Xiaohan Li, Ziren Gong, Fabio Tosi, Matteo Poggi, Stefano Mattoccia, Dong Liu, Jun Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23677v1.pdf)  
  Keywords: tracking, mapping, high-fidelity, ar, fast, gaussian splatting, slam, outdoor, 3d gaussian, urban scene  
- **[iLRM: An Iterative Large 3D Reconstruction Model](https://arxiv.org/abs/2507.23277v1)**  
  Authors: Gyeongjin Kang, Seungtae Nam, Xiangyu Sun, Sameh Khamis, Abdelrahman Mohamed, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23277v1.pdf)  
  Keywords: ar, high-fidelity, fast, 3d reconstruction, compact, gaussian splatting, efficient, 3d gaussian  
- **[DISCOVERSE: Efficient Robot Simulation in Complex High-Fidelity
  Environments](https://arxiv.org/abs/2507.21981v1)**  
  Authors: Yufei Jia, Guangyu Wang, Yuhang Dong, Junzhe Wu, Yupei Zeng, Haonan Lin, Zifan Wang, Haizhou Ge, Weibin Gu, Kairui Ding, Zike Yan, Yunjie Cheng, Yue Li, Ziming Wang, Chuxuan Li, Wei Sui, Lu Shi, Guanzhong Tian, Ruqi Huang, Guyue Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.21981v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://air-discoverse.github.io/.)  
  Keywords: ar, high-fidelity, geometry, gaussian splatting, efficient  

### Ray Tracing

- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: ar, global illumination, illumination, shadow, relightable, face, dynamic, gaussian splatting, outdoor, relighting, 3d gaussian, lighting  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: ar, path tracing, face, dynamic, gaussian splatting, 3d gaussian, lighting  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: ar, geometry, efficient, relightable, ray marching, face, gaussian splatting, relighting, 3d gaussian, efficient rendering, lighting  
- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: ar, high-fidelity, real-time rendering, gaussian splatting, efficient, ray tracing  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v1)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v1.pdf)  
  Keywords: ar, shadow, geometry, fast, relightable, gaussian splatting, avatar, relighting, human, lighting, ray tracing  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: ar, efficient, gaussian splatting, acceleration, relighting, 3d gaussian, efficient rendering, ray tracing, lighting  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: ar, ray marching, dynamic, gaussian splatting, animation, acceleration, compact, efficient, 3d gaussian  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: ar, global illumination, illumination, real-time rendering, face, gaussian splatting, efficient, 3d gaussian, lighting, ray tracing  
- **[REdiSplats: Ray Tracing for Editable Gaussian Splatting](https://arxiv.org/abs/2503.12284v1)**  
  Authors: Krzysztof Byrski, Grzegorz Wilczyński, Weronika Smolak-Dyżewska, Piotr Borycki, Dawid Baran, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12284v1.pdf)  
  Keywords: ar, shadow, fast, neural rendering, reflection, gaussian splatting, 3d gaussian, ray tracing  
- **[MeshSplats: Mesh-Based Rendering with Gaussian Splatting Initialization](https://arxiv.org/abs/2502.07754v1)**  
  Authors: Rafał Tobiasz, Grzegorz Wilczyński, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07754v1.pdf)  
  Keywords: shadow, face, reflection, gaussian splatting, lighting, ray tracing  

### Relighting

*Showing the latest 50 out of 108 papers*

- **[OCSplats: Observation Completeness Quantification and Label Noise
  Separation in 3DGS](https://arxiv.org/abs/2508.01239v1)**  
  Authors: Han Ling, Xian Xu, Yinghui Sun, Quansen Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01239v1.pdf)  
  Keywords: ar, shadow, 3d reconstruction, face, dynamic, gaussian splatting, 3d gaussian  
- **[I2V-GS: Infrastructure-to-Vehicle View Transformation with Gaussian
  Splatting for Autonomous Driving Data Generation](https://arxiv.org/abs/2507.23683v1)**  
  Authors: Jialei Chen, Wuhao Xu, Sipeng He, Baoru Huang, Dongchun Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23683v1.pdf)  
  Keywords: ar, 3d reconstruction, autonomous driving, gaussian splatting, efficient, lighting  
- **[MagicRoad: Semantic-Aware 3D Road Surface Reconstruction via Obstacle
  Inpainting](https://arxiv.org/abs/2507.23340v1)**  
  Authors: Xingyue Peng, Yuandong Lyu, Lang Zhang, Jian Zhu, Songtao Wang, Jiaxin Deng, Songxin Lu, Weiliang Ma, Dangen She, Peng Jia, XianPeng Lang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23340v1.pdf)  
  Keywords: ar, mapping, semantic, segmentation, autonomous driving, face, dynamic, gaussian splatting, efficient, 3d gaussian, lighting  
- **[GSFusion:Globally Optimized LiDAR-Inertial-Visual Mapping for Gaussian
  Splatting](https://arxiv.org/abs/2507.23273v1)**  
  Authors: Jaeseok Park, Chanoh Park, Minsu Kim, Soohwan Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23273v1.pdf)  
  Keywords: ar, mapping, illumination, slam, gaussian splatting, efficient, 3d gaussian  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from
  Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: ar, global illumination, illumination, shadow, relightable, face, dynamic, gaussian splatting, outdoor, relighting, 3d gaussian, lighting  
- **[Automated 3D-GS Registration and Fusion via Skeleton Alignment and
  Gaussian-Adaptive Features](https://arxiv.org/abs/2507.20480v1)**  
  Authors: Shiyang Liu, Dianyi Yang, Yu Gao, Bohan Ren, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20480v1.pdf)  
  Keywords: ar, real-time rendering, gaussian splatting, 3d gaussian, lighting  
- **[From Gallery to Wrist: Realistic 3D Bracelet Insertion in Videos](https://arxiv.org/abs/2507.20331v2)**  
  Authors: Chenjian Gao, Lihe Ding, Rui Han, Zhanpeng Huang, Zibin Wang, Tianfan Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20331v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://cjeen.github.io/BraceletPaper/)  
  Keywords: ar, illumination, motion, dynamic, gaussian splatting, 3d gaussian, lighting  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: ar, path tracing, face, dynamic, gaussian splatting, 3d gaussian, lighting  
- **[PS-GS: Gaussian Splatting for Multi-View Photometric Stereo](https://arxiv.org/abs/2507.18231v1)**  
  Authors: Yixiao Chen, Bin Liang, Hanzhi Guo, Yongqing Cheng, Jiayi Zhao, Dongdong Weng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18231v1.pdf)  
  Keywords: ar, illumination, geometry, efficient, 3d reconstruction, gaussian splatting, relighting, lighting  
- **[StreamME: Simplify 3D Gaussian Avatar within Live Stream](https://arxiv.org/abs/2507.17029v1)**  
  Authors: Luchuan Song, Yang Zhou, Zhan Xu, Yi Zhou, Deepali Aneja, Chenliang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.17029v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://songluchuan.github.io/StreamME/.)  
  Keywords: ar, geometry, fast, head, vr, face, gaussian splatting, animation, avatar, relighting, 3d gaussian, lighting  

### SLAM

*Showing the latest 50 out of 156 papers*

- **[Stereo 3D Gaussian Splatting SLAM for Outdoor Urban Scenes](https://arxiv.org/abs/2507.23677v1)**  
  Authors: Xiaohan Li, Ziren Gong, Fabio Tosi, Matteo Poggi, Stefano Mattoccia, Dong Liu, Jun Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23677v1.pdf)  
  Keywords: tracking, mapping, high-fidelity, ar, fast, gaussian splatting, slam, outdoor, 3d gaussian, urban scene  
- **[Gaussian Splatting Feature Fields for Privacy-Preserving Visual
  Localization](https://arxiv.org/abs/2507.23569v1)**  
  Authors: Maxime Pietrantoni, Gabriela Csurka, Torsten Sattler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23569v1.pdf)  
  Keywords: ar, localization, geometry, segmentation, gaussian splatting, 3d gaussian  
- **[MagicRoad: Semantic-Aware 3D Road Surface Reconstruction via Obstacle
  Inpainting](https://arxiv.org/abs/2507.23340v1)**  
  Authors: Xingyue Peng, Yuandong Lyu, Lang Zhang, Jian Zhu, Songtao Wang, Jiaxin Deng, Songxin Lu, Weiliang Ma, Dangen She, Peng Jia, XianPeng Lang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23340v1.pdf)  
  Keywords: ar, mapping, semantic, segmentation, autonomous driving, face, dynamic, gaussian splatting, efficient, 3d gaussian, lighting  
- **[GSFusion:Globally Optimized LiDAR-Inertial-Visual Mapping for Gaussian
  Splatting](https://arxiv.org/abs/2507.23273v1)**  
  Authors: Jaeseok Park, Chanoh Park, Minsu Kim, Soohwan Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.23273v1.pdf)  
  Keywords: ar, mapping, illumination, slam, gaussian splatting, efficient, 3d gaussian  
- **[No Redundancy, No Stall: Lightweight Streaming 3D Gaussian Splatting for
  Real-time Rendering](https://arxiv.org/abs/2507.21572v2)**  
  Authors: Linye Wei, Jiajun Tang, Fan Fei, Boxin Shi, Runsheng Wang, Meng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.21572v2.pdf)  
  Keywords: ar, mapping, autonomous driving, real-time rendering, face, gaussian splatting, efficient, 3d gaussian, lightweight  
- **[RaGS: Unleashing 3D Gaussian Splatting from 4D Radar and Monocular Cues
  for 3D Object Detection](https://arxiv.org/abs/2507.19856v2)**  
  Authors: Xiaokai Bai, Chenxu Zhou, Lianqing Zheng, Si-Yuan Cao, Jianan Liu, Xiaohan Zhang, Zhengzhuang Zhang, Hui-liang Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19856v2.pdf)  
  Keywords: understanding, ar, localization, geometry, semantic, autonomous driving, dynamic, gaussian splatting, efficient, 3d gaussian, 4d  
- **[DINO-SLAM: DINO-informed RGB-D SLAM for Neural Implicit and Explicit
  Representations](https://arxiv.org/abs/2507.19474v1)**  
  Authors: Ziren Gong, Xiaohan Li, Fabio Tosi, Youmin Zhang, Stefano Mattoccia, Jun Wu, Matteo Poggi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19474v1.pdf)  
  Keywords: ar, gaussian splatting, slam, 3d gaussian, nerf  
- **[Unposed 3DGS Reconstruction with Probabilistic Procrustes Mapping](https://arxiv.org/abs/2507.18541v1)**  
  Authors: Chong Cheng, Zijian Wang, Sicheng Yu, Yu Hu, Nanjie Yao, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18541v1.pdf)  
  Keywords: ar, mapping, geometry, gaussian splatting, outdoor, 3d gaussian  
- **[CRUISE: Cooperative Reconstruction and Editing in V2X Scenarios using
  Gaussian Splatting](https://arxiv.org/abs/2507.18473v1)**  
  Authors: Haoran Xu, Saining Zhang, Peishuo Li, Baijun Ye, Xiaoxue Chen, Huan-ang Gao, Jv Zheng, Xiaowei Song, Ziqiao Peng, Run Miao, Jinrang Jia, Yifeng Shi, Guangqi Yi, Hang Zhao, Hao Tang, Hongyang Li, Kaicheng Yu, Hao Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18473v1.pdf)  
  Keywords: ar, tracking, autonomous driving, dynamic, gaussian splatting  
- **[G2S-ICP SLAM: Geometry-aware Gaussian Splatting ICP SLAM](https://arxiv.org/abs/2507.18344v1)**  
  Authors: Gyuhyeon Pak, Hae Min Cho, Euntai Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.18344v1.pdf)  
  Keywords: tracking, ar, high-fidelity, localization, geometry, 3d reconstruction, face, gaussian splatting, slam  

### Scene Understanding

*Showing the latest 50 out of 193 papers*

- **[A Study of the Framework and Real-World Applications of Language
  Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v1.pdf)  
  Keywords: understanding, robotics, ar, semantic, survey, gaussian splatting, efficient, 3d gaussian, nerf  
- **[DET-GS: Depth- and Edge-Aware Regularization for High-Fidelity 3D
  Gaussian Splatting](https://arxiv.org/abs/2508.04099v1)**  
  Authors: Zexu Huang, Min Xu, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04099v1.pdf)  
  Keywords: ar, high-fidelity, sparse-view, semantic, gaussian splatting, efficient, 3d gaussian  
- **[Trace3D: Consistent Segmentation Lifting via Gaussian Instance Tracing](https://arxiv.org/abs/2508.03227v1)**  
  Authors: Hongyu Shen, Junfeng Ni, Yixin Chen, Weishuo Li, Mingtao Pei, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03227v1.pdf)  
  Keywords: ar, segmentation, gaussian splatting, semantic  
- **[H3R: Hybrid Multi-view Correspondence for Generalizable 3D
  Reconstruction](https://arxiv.org/abs/2508.03118v1)**  
  Authors: Heng Jia, Linchao Zhu, Na Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03118v1.pdf)  
  Keywords: ar, fast, 3d reconstruction, semantic, face, gaussian splatting, efficient, 3d gaussian  
- **[RobustGS: Unified Boosting of Feedforward 3D Gaussian Splatting under
  Low-Quality Conditions](https://arxiv.org/abs/2508.03077v1)**  
  Authors: Anran Wu, Long Peng, Xin Di, Xueyuan Dai, Chen Wu, Yang Wang, Xueyang Fu, Yang Cao, Zheng-Jun Zha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.03077v1.pdf)  
  Keywords: ar, geometry, fast, 3d reconstruction, semantic, gaussian splatting, efficient, 3d gaussian  
- **[GaussianCross: Cross-modal Self-supervised 3D Representation Learning
  via Gaussian Splatting](https://arxiv.org/abs/2508.02172v1)**  
  Authors: Lei Yao, Yi Wang, Yi Zhang, Moyun Liu, Lap-Pui Chau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rayyoh.github.io/GaussianCross/}{https://rayyoh.github.io/GaussianCross/}.)  
  Keywords: understanding, ar, geometry, semantic, segmentation, gaussian splatting, 3d gaussian  
- **[ScrewSplat: An End-to-End Method for Articulated Object Recognition](https://arxiv.org/abs/2508.02146v1)**  
  Authors: Seungyeon Kim, Junsu Ha, Young Hun Kim, Yonghyeon Lee, Frank C. Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.02146v1.pdf)  
  Keywords: geometry, ar, recognition, gaussian splatting  
- **[AG$^2$aussian: Anchor-Graph Structured Gaussian Splatting for
  Instance-Level 3D Scene Understanding and Editing](https://arxiv.org/abs/2508.01740v1)**  
  Authors: Zhaonan Wang, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01740v1.pdf)  
  Keywords: understanding, ar, semantic, segmentation, compact, gaussian splatting, 3d gaussian  
- **[Can3Tok: Canonical 3D Tokenization and Latent Modeling of Scene-Level 3D
  Gaussians](https://arxiv.org/abs/2508.01464v1)**  
  Authors: Quankai Gao, Iliyan Georgiev, Tuanfeng Y. Wang, Krishna Kumar Singh, Ulrich Neumann, Jae Shin Yoon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.01464v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, semantic  
- **[PointGauss: Point Cloud-Guided Multi-Object Segmentation for Gaussian
  Splatting](https://arxiv.org/abs/2508.00259v1)**  
  Authors: Wentao Sun, Hanqing Xu, Quanyun Wu, Dedong Zhang, Yiping Chen, Lingfei Ma, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.00259v1.pdf)  
  Keywords: ar, segmentation, efficient, gaussian splatting  



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