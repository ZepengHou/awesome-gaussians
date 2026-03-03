# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-03-03 01:15:34

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
- [Acceleration](#acceleration) (235 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (337 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (401 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (76 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (363 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (65 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (417 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (217 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (21 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (131 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (151 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (227 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: face, mapping, dynamic, survey, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, 3d gaussian, gaussian splatting, robotics, ar  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v2)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v2.pdf)  
  Keywords: survey, 3d gaussian, efficient, gaussian splatting, ar, nerf, geometry  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, survey, dynamic, 3d gaussian, 3d reconstruction, compression, efficient, gaussian splatting, high-fidelity, compact, ar  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: mapping, survey, 3d gaussian, slam, gaussian splatting, robotics, localization, understanding, ar, nerf, semantic  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: mapping, survey, 3d gaussian, slam, efficient, gaussian splatting, robotics, high-fidelity, localization, ar, semantic  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: fast, 4d, survey, 3d gaussian, gaussian splatting, ar, nerf, motion, geometry  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: face, survey, animation, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, real-time rendering, avatar, ar, efficient rendering  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: lightweight, survey, efficient, gaussian splatting, understanding, ar, nerf, human  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: fast, survey, 3d gaussian, neural rendering, slam, efficient, gaussian splatting, understanding, ar, nerf  

### Acceleration

*Showing the latest 50 out of 235 papers*

- **[Prune Wisely, Reconstruct Sharply: Compact 3D Gaussian Splatting via Adaptive Pruning and Difference-of-Gaussian Primitives](https://arxiv.org/abs/2602.24136v1)**  
  Authors: Haoran Wang, Guoxi Huang, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24136v1.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, compact, real-time rendering, ar  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[Monocular Endoscopic Tissue 3D Reconstruction with Multi-Level Geometry Regularization](https://arxiv.org/abs/2602.20718v1)**  
  Authors: Yangsen Chen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20718v1.pdf)  
  Keywords: face, fast, 3d gaussian, deformation, 3d reconstruction, gaussian splatting, real-time rendering, ar, nerf, geometry  
- **[tttLRM: Test-Time Training for Long Context and Autoregressive 3D Reconstruction](https://arxiv.org/abs/2602.20160v1)**  
  Authors: Chen Wang, Hao Tan, Wang Yifan, Zhiqin Chen, Yuheng Liu, Kalyan Sunkavalli, Sai Bi, Lingjie Liu, Yiwei Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20160v1.pdf)  
  Keywords: fast, 3d gaussian, 3d reconstruction, efficient, ar  
- **[Augmented Radiance Field: A General Framework for Enhanced Gaussian Splatting](https://arxiv.org/abs/2602.19916v1)**  
  Authors: Yixin Yang, Bojian Wu, Yang Zhou, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19916v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaoxinyyx.github.io/augs.)  
  Keywords: 3d gaussian, gaussian splatting, real-time rendering, reflection, ar, nerf  
- **[RAP: Fast Feedforward Rendering-Free Attribute-Guided Primitive Importance Score Prediction for Efficient 3D Gaussian Splatting Processing](https://arxiv.org/abs/2602.19753v1)**  
  Authors: Kaifa Yang, Qi Yang, Yiling Xu, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19753v1.pdf)  
  Keywords: fast, 3d gaussian, compression, efficient, gaussian splatting, compact, ar  
- **[Unifying Color and Lightness Correction with View-Adaptive Curve Adjustment for Robust 3D Novel View Synthesis](https://arxiv.org/abs/2602.18322v1)**  
  Authors: Ziteng Cui, Shuhong Liu, Xiaoyu Dong, Xuangeng Chu, Lin Gu, Ming-Hsuan Yang, Tatsuya Harada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.18322v1.pdf)  
  Keywords: 3d gaussian, lighting, gaussian splatting, real-time rendering, ar, nerf, illumination  
- **[Diff2DGS: Reliable Reconstruction of Occluded Surgical Scenes via 2D Gaussian Splatting](https://arxiv.org/abs/2602.18314v1)**  
  Authors: Tianyi Song, Danail Stoyanov, Evangelos Mazomenos, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.18314v1.pdf)  
  Keywords: dynamic, acceleration, deformation, 3d reconstruction, gaussian splatting, high-fidelity, ar, nerf, geometry  
- **[B$^3$-Seg: Camera-Free, Training-Free 3DGS Segmentation via Analytic EIG and Beta-Bernoulli Bayesian Updates](https://arxiv.org/abs/2602.17134v1)**  
  Authors: Hiromichi Kamata, Samuel Arthur Munro, Fuminori Homma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17134v1.pdf)  
  Keywords: segmentation, fast, 3d gaussian, gaussian splatting, ar  

### Applications

*Showing the latest 50 out of 995 papers*

- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v1)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: 4d, dynamic, 3d gaussian, high-fidelity, ar, motion, geometry  
- **[Prune Wisely, Reconstruct Sharply: Compact 3D Gaussian Splatting via Adaptive Pruning and Difference-of-Gaussian Primitives](https://arxiv.org/abs/2602.24136v1)**  
  Authors: Haoran Wang, Guoxi Huang, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24136v1.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, compact, real-time rendering, ar  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v1)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v1.pdf)  
  Keywords: dynamic, 3d gaussian, lighting, gaussian splatting, ar, nerf  
- **[SR3R: Rethinking Super-Resolution 3D Reconstruction With Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2602.24020v1)**  
  Authors: Xiang Feng, Xiangbo Wang, Tieshi Zhong, Chengkai Wang, Yiting Zhao, Tianxiang Xu, Zhenzhong Kuang, Feiwei Qin, Xuefei Yin, Yanming Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24020v1.pdf)  
  Keywords: mapping, 3d gaussian, 3d reconstruction, gaussian splatting, ar, geometry  
- **[No Calibration, No Depth, No Problem: Cross-Sensor View Synthesis with 3D Consistency](https://arxiv.org/abs/2602.23559v1)**  
  Authors: Cho-Ying Wu, Zixun Huang, Xinyu Huang, Liu Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23559v1.pdf)  
  Keywords: 3d gaussian, ar, gaussian splatting  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[PackUV: Packed Gaussian UV Maps for 4D Volumetric Video](https://arxiv.org/abs/2602.23040v1)**  
  Authors: Aashish Rai, Angela Xing, Anushka Agarwal, Xiaoyan Cong, Zekun Li, Tao Lu, Aayush Prakash, Srinath Sridhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23040v1.pdf)  
  Keywords: 4d, dynamic, efficient, gaussian splatting, compact, ar, motion  
- **[GSTurb: Gaussian Splatting for Atmospheric Turbulence Mitigation](https://arxiv.org/abs/2602.22800v1)**  
  Authors: Hanliang Du, Zhangji Lu, Zewei Cai, Qijian Tang, Qifeng Yu, Xiaoli Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22800v1.pdf)  
  Keywords: ar, gaussian splatting  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: dynamic, 3d gaussian, slam, 3d reconstruction, gaussian splatting, ar, nerf  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: segmentation, dynamic, 3d gaussian, gaussian splatting, high-fidelity, ar, motion, geometry  

### Avatar Generation

*Showing the latest 50 out of 337 papers*

- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[BrepGaussian: CAD reconstruction from Multi-View Images with Gaussian Splatting](https://arxiv.org/abs/2602.21105v1)**  
  Authors: Jiaxing Yu, Dongyang Ren, Hangyu Xu, Zhouyuxiao Yang, Yuanqi Li, Jie Guo, Zhengkang Zhou, Yanwen Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21105v1.pdf)  
  Keywords: geometry, face, ar, gaussian splatting  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: 3d gaussian, compression, efficient, head, gaussian splatting, sparse-view, ar  
- **[Monocular Endoscopic Tissue 3D Reconstruction with Multi-Level Geometry Regularization](https://arxiv.org/abs/2602.20718v1)**  
  Authors: Yangsen Chen, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20718v1.pdf)  
  Keywords: face, fast, 3d gaussian, deformation, 3d reconstruction, gaussian splatting, real-time rendering, ar, nerf, geometry  
- **[WildGHand: Learning Anti-Perturbation Gaussian Hand Avatars from Monocular In-the-Wild Videos](https://arxiv.org/abs/2602.20556v1)**  
  Authors: Hanhui Li, Xuan Huang, Wanquan Liu, Yuhao Cheng, Long Chen, Yiqiang Yan, Xiaodan Liang, Chenqiang Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20556v1.pdf)  
  Keywords: dynamic, 3d gaussian, gaussian splatting, high-fidelity, motion, avatar, ar, illumination  
- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: 3d gaussian, head, gaussian splatting, real-time rendering, ar, nerf, motion, semantic  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: mapping, 3d gaussian, outdoor, lighting, head, gaussian splatting, localization, ar, semantic, geometry  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, efficient, gaussian splatting, high-fidelity, ar  

### Dynamic Scene

*Showing the latest 50 out of 401 papers*

- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v1)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: 4d, dynamic, 3d gaussian, high-fidelity, ar, motion, geometry  
- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v1)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v1.pdf)  
  Keywords: dynamic, 3d gaussian, lighting, gaussian splatting, ar, nerf  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[PackUV: Packed Gaussian UV Maps for 4D Volumetric Video](https://arxiv.org/abs/2602.23040v1)**  
  Authors: Aashish Rai, Angela Xing, Anushka Agarwal, Xiaoyan Cong, Zekun Li, Tao Lu, Aayush Prakash, Srinath Sridhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23040v1.pdf)  
  Keywords: 4d, dynamic, efficient, gaussian splatting, compact, ar, motion  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: dynamic, 3d gaussian, slam, 3d reconstruction, gaussian splatting, ar, nerf  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: segmentation, dynamic, 3d gaussian, gaussian splatting, high-fidelity, ar, motion, geometry  
- **[AeroDGS: Physically Consistent Dynamic Gaussian Splatting for Single-Sequence Aerial 4D Reconstruction](https://arxiv.org/abs/2602.22376v1)**  
  Authors: Hanyang Liu, Rongjun Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22376v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, ar, motion, geometry  
- **[Space-Time Forecasting of Dynamic Scenes with Motion-aware Gaussian Grouping](https://arxiv.org/abs/2602.21668v1)**  
  Authors: Junmyeong Lee, Hoseung Choi, Minsu Cho  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21668v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://slime0519.github.io/mogaf)  
  Keywords: lightweight, 4d, dynamic, gaussian splatting, ar, motion  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: segmentation, lightweight, mapping, dynamic, illumination, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: 4d, dynamic, mapping, 3d gaussian, slam, 3d reconstruction, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  

### Few-shot

*Showing the latest 50 out of 76 papers*

- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: sparse view, 3d gaussian, 3d reconstruction, gaussian splatting, ar  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: 3d gaussian, compression, efficient, head, gaussian splatting, sparse-view, ar  
- **[TG-Field: Geometry-Aware Radiative Gaussian Fields for Tomographic Reconstruction](https://arxiv.org/abs/2602.11705v1)**  
  Authors: Yuxiang Zhong, Jun Wei, Chaoqi Chen, Senyou An, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.11705v1.pdf)  
  Keywords: dynamic, 3d gaussian, deformation, gaussian splatting, sparse-view, ar, motion, geometry  
- **[Pi-GS: Sparse-View Gaussian Splatting with Dense π^3 Initialization](https://arxiv.org/abs/2602.03327v1)**  
  Authors: Manuel Hofer, Markus Steinberger, Thomas Köhler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03327v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, sparse-view, real-time rendering, ar, nerf, motion  
- **[LoD-Structured 3D Gaussian Splatting for Streaming Video Reconstruction](https://arxiv.org/abs/2601.18475v1)**  
  Authors: Xinhui Liu, Can Wang, Lei Liu, Zhenghao Chen, Wei Jiang, Wei Wang, Dong Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.18475v1.pdf)  
  Keywords: dynamic, 3d gaussian, efficient, gaussian splatting, high-fidelity, sparse-view, ar, motion  
- **[LGDWT-GS: Local and Global Discrete Wavelet-Regularized 3D Gaussian Splatting for Sparse-View Scene Reconstruction](https://arxiv.org/abs/2601.17185v1)**  
  Authors: Shima Salehi, Atharva Agashe, Andrew J. McFarland, Joshua Peeples  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.17185v1.pdf)  
  Keywords: few-shot, 3d gaussian, 3d reconstruction, gaussian splatting, sparse-view, ar, geometry  
- **[SA-ResGS: Self-Augmented Residual 3D Gaussian Splatting for Next Best View Selection](https://arxiv.org/abs/2601.03024v2)**  
  Authors: Kim Jun-Seong, Tae-Hyun Oh, Eduardo Pérez-Pellitero, Youngkyoon Jang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.03024v2.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, sparse-view, ar  
- **[360-GeoGS: Geometrically Consistent Feed-Forward 3D Gaussian Splatting Reconstruction for 360 Images](https://arxiv.org/abs/2601.02102v1)**  
  Authors: Jiaqi Yao, Zhongmiao Yan, Jingyi Xu, Songpengcheng Xia, Yan Xiang, Ling Pei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.02102v1.pdf)  
  Keywords: face, sparse view, 3d gaussian, neural rendering, 3d reconstruction, efficient, gaussian splatting, robotics, ar, efficient rendering  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: ray marching, shadow, 3d gaussian, 3d reconstruction, efficient, gaussian splatting, sparse-view, ar, efficient rendering, illumination  
- **[COSMOS: Coherent Supergaussian Modeling with Spatial Priors for Sparse-View 3D Splatting](https://arxiv.org/abs/2602.06044v1)**  
  Authors: Chaeyoung Jeong, Kwangsu Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.06044v1.pdf)  
  Keywords: segmentation, 3d gaussian, 3d reconstruction, gaussian splatting, sparse-view, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 363 papers*

- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v1)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: 4d, dynamic, 3d gaussian, high-fidelity, ar, motion, geometry  
- **[SR3R: Rethinking Super-Resolution 3D Reconstruction With Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2602.24020v1)**  
  Authors: Xiang Feng, Xiangbo Wang, Tieshi Zhong, Chengkai Wang, Yiting Zhao, Tianxiang Xu, Zhenzhong Kuang, Feiwei Qin, Xuefei Yin, Yanming Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24020v1.pdf)  
  Keywords: mapping, 3d gaussian, 3d reconstruction, gaussian splatting, ar, geometry  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: dynamic, 3d gaussian, slam, 3d reconstruction, gaussian splatting, ar, nerf  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: segmentation, dynamic, 3d gaussian, gaussian splatting, high-fidelity, ar, motion, geometry  
- **[BetterScene: 3D Scene Synthesis with Representation-Aligned Generative Model](https://arxiv.org/abs/2602.22596v1)**  
  Authors: Yuci Han, Charles Toth, John E. Anderson, William J. Shuart, Alper Yilmaz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22596v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, semantic, geometry  
- **[GIFSplat: Generative Prior-Guided Iterative Feed-Forward 3D Gaussian Splatting from Sparse Views](https://arxiv.org/abs/2602.22571v1)**  
  Authors: Tianyu Chen, Wei Xiang, Kang Han, Yu Lu, Di Wu, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22571v1.pdf)  
  Keywords: sparse view, 3d gaussian, 3d reconstruction, gaussian splatting, ar  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[AeroDGS: Physically Consistent Dynamic Gaussian Splatting for Single-Sequence Aerial 4D Reconstruction](https://arxiv.org/abs/2602.22376v1)**  
  Authors: Hanyang Liu, Rongjun Qin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22376v1.pdf)  
  Keywords: 4d, dynamic, gaussian splatting, ar, motion, geometry  
- **[BrepGaussian: CAD reconstruction from Multi-View Images with Gaussian Splatting](https://arxiv.org/abs/2602.21105v1)**  
  Authors: Jiaxing Yu, Dongyang Ren, Hangyu Xu, Zhouyuxiao Yang, Yuanqi Li, Jie Guo, Zhengkang Zhou, Yanwen Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21105v1.pdf)  
  Keywords: geometry, face, ar, gaussian splatting  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: 4d, dynamic, mapping, 3d gaussian, slam, 3d reconstruction, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  

### Large Scene

*Showing the latest 50 out of 65 papers*

- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: 3d gaussian, neural rendering, outdoor, 3d reconstruction, efficient, gaussian splatting, high-fidelity, vr, ar, nerf  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: mapping, 3d gaussian, outdoor, lighting, head, gaussian splatting, localization, ar, semantic, geometry  
- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: 3d gaussian, outdoor, lighting, gaussian splatting, global illumination, real-time rendering, autonomous driving, ar, nerf, illumination  
- **[Zero-Shot UAV Navigation in Forests via Relightable 3D Gaussian Splatting](https://arxiv.org/abs/2602.07101v2)**  
  Authors: Zinan Lv, Yeqian Qian, Chen Sang, Hao Liu, Danping Zou, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.07101v2.pdf)  
  Keywords: lightweight, dynamic, 3d gaussian, outdoor, lighting, relightable, gaussian splatting, high-fidelity, ar, illumination, geometry  
- **[3DGS$^2$-TR: Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting](https://arxiv.org/abs/2602.00395v1)**  
  Authors: Roger Hsiao, Yuchen Fang, Xiangru Huang, Ruilong Li, Hesam Rabeti, Zan Gojcic, Javad Lavaei, James Demmel, Sophia Shao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.00395v1.pdf)  
  Keywords: 3d gaussian, head, efficient, gaussian splatting, ar, large scene  
- **[EVolSplat4D: Efficient Volume-based Gaussian Splatting for 4D Urban Scene Synthesis](https://arxiv.org/abs/2601.15951v1)**  
  Authors: Sheng Miao, Sijin Li, Pan Wang, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.15951v1.pdf)  
  Keywords: 4d, dynamic, 3d gaussian, efficient, gaussian splatting, autonomous driving, ar, urban scene, motion, semantic, geometry  
- **[Clean-GS: Semantic Mask-Guided Pruning for 3D Gaussian Splatting](https://arxiv.org/abs/2601.00913v1)**  
  Authors: Subhankar Mishra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00913v1.pdf)  
  Keywords: segmentation, 3d gaussian, outdoor, compression, gaussian splatting, vr, ar, semantic  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: face, 3d gaussian, 3d reconstruction, efficient, gaussian splatting, ar, urban scene, illumination, geometry  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: fast, 3d gaussian, outdoor, gaussian splatting, compact, ar, geometry  

### Model Compression

*Showing the latest 50 out of 417 papers*

- **[Prune Wisely, Reconstruct Sharply: Compact 3D Gaussian Splatting via Adaptive Pruning and Difference-of-Gaussian Primitives](https://arxiv.org/abs/2602.24136v1)**  
  Authors: Haoran Wang, Guoxi Huang, Fan Zhang, David Bull, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24136v1.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, compact, real-time rendering, ar  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[PackUV: Packed Gaussian UV Maps for 4D Volumetric Video](https://arxiv.org/abs/2602.23040v1)**  
  Authors: Aashish Rai, Angela Xing, Anushka Agarwal, Xiaoyan Cong, Zekun Li, Tao Lu, Aayush Prakash, Srinath Sridhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23040v1.pdf)  
  Keywords: 4d, dynamic, efficient, gaussian splatting, compact, ar, motion  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[Space-Time Forecasting of Dynamic Scenes with Motion-aware Gaussian Grouping](https://arxiv.org/abs/2602.21668v1)**  
  Authors: Junmyeong Lee, Hoseung Choi, Minsu Cho  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21668v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://slime0519.github.io/mogaf)  
  Keywords: lightweight, 4d, dynamic, gaussian splatting, ar, motion  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: segmentation, lightweight, mapping, dynamic, illumination, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[Dropping Anchor and Spherical Harmonics for Sparse-view Gaussian Splatting](https://arxiv.org/abs/2602.20933v1)**  
  Authors: Shuangkang Fang, I-Chao Shen, Xuanyang Zhang, Zesheng Wang, Yufeng Wang, Wenrui Ding, Gang Yu, Takeo Igarashi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20933v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sk-fun.fun/DropAnSH-GS)  
  Keywords: 3d gaussian, compression, efficient, head, gaussian splatting, sparse-view, ar  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: 4d, dynamic, mapping, 3d gaussian, slam, 3d reconstruction, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[Aesthetic Camera Viewpoint Suggestion with 3D Aesthetic Field](https://arxiv.org/abs/2602.20363v1)**  
  Authors: Sheyang Tang, Armin Shafiee Sarvestani, Jialu Xu, Xiaoyu Xu, Zhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20363v1.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, understanding, ar, geometry  

### Quality Enhancement

*Showing the latest 50 out of 217 papers*

- **[UFO-4D: Unposed Feedforward 4D Reconstruction from Two Images](https://arxiv.org/abs/2602.24290v1)**  
  Authors: Junhwa Hur, Charles Herrmann, Songyou Peng, Philipp Henzler, Zeyu Ma, Todd Zickler, Deqing Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24290v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ufo-4d.github.io/)  
  Keywords: 4d, dynamic, 3d gaussian, high-fidelity, ar, motion, geometry  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: segmentation, dynamic, 3d gaussian, gaussian splatting, high-fidelity, ar, motion, geometry  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[WildGHand: Learning Anti-Perturbation Gaussian Hand Avatars from Monocular In-the-Wild Videos](https://arxiv.org/abs/2602.20556v1)**  
  Authors: Hanhui Li, Xuan Huang, Wanquan Liu, Yuhao Cheng, Long Chen, Yiqiang Yan, Xiaodan Liang, Chenqiang Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20556v1.pdf)  
  Keywords: dynamic, 3d gaussian, gaussian splatting, high-fidelity, motion, avatar, ar, illumination  
- **[Large-scale Photorealistic Outdoor 3D Scene Reconstruction from UAV Imagery Using Gaussian Splatting Techniques](https://arxiv.org/abs/2602.20342v1)**  
  Authors: Christos Maikos, Georgios Angelidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20342v1.pdf)  
  Keywords: 3d gaussian, neural rendering, outdoor, 3d reconstruction, efficient, gaussian splatting, high-fidelity, vr, ar, nerf  
- **[DefenseSplat: Enhancing the Robustness of 3D Gaussian Splatting via Frequency-Aware Filtering](https://arxiv.org/abs/2602.19323v1)**  
  Authors: Yiran Qiao, Yiren Lu, Yunlai Zhou, Rui Yang, Linlin Hou, Yu Yin, Jing Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19323v1.pdf)  
  Keywords: 3d gaussian, lighting, 3d reconstruction, gaussian splatting, high-fidelity, ar  
- **[Diff2DGS: Reliable Reconstruction of Occluded Surgical Scenes via 2D Gaussian Splatting](https://arxiv.org/abs/2602.18314v1)**  
  Authors: Tianyi Song, Danail Stoyanov, Evangelos Mazomenos, Francisco Vasconcelos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.18314v1.pdf)  
  Keywords: dynamic, acceleration, deformation, 3d reconstruction, gaussian splatting, high-fidelity, ar, nerf, geometry  
- **[3D Scene Rendering with Multimodal Gaussian Splatting](https://arxiv.org/abs/2602.17124v1)**  
  Authors: Chi-Shiang Gau, Konstantinos D. Polyzos, Athanasios Bacharis, Saketh Madhuvarasu, Tara Javidi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17124v1.pdf)  
  Keywords: 3d gaussian, lighting, efficient, gaussian splatting, robotics, high-fidelity, ar, autonomous driving, illumination  
- **[DAV-GSWT: Diffusion-Active-View Sampling for Data-Efficient Gaussian Splatting Wang Tiles](https://arxiv.org/abs/2602.15355v1)**  
  Authors: Rong Fu, Jiekai Wu, Haiyun Wei, Yee Tan Jia, Wenxin Zhang, Yang Li, Xiaowen Ma, Wangyu Wu, Simon Fong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15355v1.pdf)  
  Keywords: 3d gaussian, neural rendering, efficient, gaussian splatting, high-fidelity, ar  
- **[Gaussian Mesh Renderer for Lightweight Differentiable Rendering](https://arxiv.org/abs/2602.14493v1)**  
  Authors: Xinpeng Liu, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14493v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, efficient, gaussian splatting, high-fidelity, ar  

### Ray Tracing

- **[Nighttime Autonomous Driving Scene Reconstruction with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2602.13549v1)**  
  Authors: Tae-Kyeong Kim, Xingxin Chen, Guile Wu, Chengjie Huang, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13549v1.pdf)  
  Keywords: 3d gaussian, outdoor, lighting, gaussian splatting, global illumination, real-time rendering, autonomous driving, ar, nerf, illumination  
- **[Rotated Lights for Consistent and Efficient 2D Gaussians Inverse Rendering](https://arxiv.org/abs/2602.08724v1)**  
  Authors: Geng Lin, Matthias Zwicker  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.08724v1.pdf)  
  Keywords: relighting, shadow, lighting, efficient, gaussian splatting, global illumination, ar, illumination, geometry  
- **[Radioactive 3D Gaussian Ray Tracing for Tomographic Reconstruction](https://arxiv.org/abs/2602.01057v1)**  
  Authors: Ling Chen, Bao Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.01057v1.pdf)  
  Keywords: 3d gaussian, ray tracing, ar, gaussian splatting  
- **[Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy](https://arxiv.org/abs/2601.22026v1)**  
  Authors: Constantin Kleinbeck, Luisa Theelke, Hannah Schieber, Ulrich Eck, Rüdiger von Eisenhart-Rothe, Daniel Roth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.22026v1.pdf)  
  Keywords: lightweight, head, medical, path tracing, gaussian splatting, vr, understanding, ar  
- **[GRTX: Efficient Ray Tracing for 3D Gaussian-Based Rendering](https://arxiv.org/abs/2601.20429v1)**  
  Authors: Junseo Lee, Sangyun Jeon, Jungi Lee, Junyong Park, Jaewoong Sim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.20429v1.pdf)  
  Keywords: acceleration, 3d gaussian, head, efficient, gaussian splatting, ray tracing, ar  
- **[ShadowGS: Shadow-Aware 3D Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2601.00939v1)**  
  Authors: Feng Luo, Hongbo Pan, Xiang Yang, Baoyu Jiang, Fengqing Liu, Tao Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.00939v1.pdf)  
  Keywords: ray marching, shadow, 3d gaussian, 3d reconstruction, efficient, gaussian splatting, sparse-view, ar, efficient rendering, illumination  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: fast, 3d gaussian, 3d reconstruction, gaussian splatting, ray tracing, understanding, ar, motion, geometry  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: relighting, 3d reconstruction, lighting, relightable, gaussian splatting, ray tracing, ar, geometry  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: face, fast, 3d gaussian, gaussian splatting, ray tracing, ar, nerf  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: fast, 3d gaussian, gaussian splatting, high-fidelity, real-time rendering, ray tracing, compact, ar  

### Relighting

*Showing the latest 50 out of 131 papers*

- **[DiffusionHarmonizer: Bridging Neural Reconstruction and Photorealistic Simulation with Online Diffusion Enhancer](https://arxiv.org/abs/2602.24096v1)**  
  Authors: Yuxuan Zhang, Katarína Tóthová, Zian Wang, Kangxue Yin, Haithem Turki, Riccardo de Lutio, Yen-Yu Chang, Or Litany, Sanja Fidler, Zan Gojcic  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24096v1.pdf)  
  Keywords: dynamic, 3d gaussian, lighting, gaussian splatting, ar, nerf  
- **[SwiftNDC: Fast Neural Depth Correction for High-Fidelity 3D Reconstruction](https://arxiv.org/abs/2602.22565v1)**  
  Authors: Kang Han, Wei Xiang, Lu Yu, Mathew Wyatt, Gaowen Liu, Ramana Rao Kompella  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22565v1.pdf)  
  Keywords: face, fast, 3d gaussian, 3d reconstruction, lighting, efficient, gaussian splatting, high-fidelity, ar, geometry  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: segmentation, lightweight, mapping, dynamic, illumination, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[WildGHand: Learning Anti-Perturbation Gaussian Hand Avatars from Monocular In-the-Wild Videos](https://arxiv.org/abs/2602.20556v1)**  
  Authors: Hanhui Li, Xuan Huang, Wanquan Liu, Yuhao Cheng, Long Chen, Yiqiang Yan, Xiaodan Liang, Chenqiang Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20556v1.pdf)  
  Keywords: dynamic, 3d gaussian, gaussian splatting, high-fidelity, motion, avatar, ar, illumination  
- **[Augmented Radiance Field: A General Framework for Enhanced Gaussian Splatting](https://arxiv.org/abs/2602.19916v1)**  
  Authors: Yixin Yang, Bojian Wu, Yang Zhou, Hui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19916v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiaoxinyyx.github.io/augs.)  
  Keywords: 3d gaussian, gaussian splatting, real-time rendering, reflection, ar, nerf  
- **[DefenseSplat: Enhancing the Robustness of 3D Gaussian Splatting via Frequency-Aware Filtering](https://arxiv.org/abs/2602.19323v1)**  
  Authors: Yiran Qiao, Yiren Lu, Yunlai Zhou, Rui Yang, Linlin Hou, Yu Yin, Jing Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.19323v1.pdf)  
  Keywords: 3d gaussian, lighting, 3d reconstruction, gaussian splatting, high-fidelity, ar  
- **[Unifying Color and Lightness Correction with View-Adaptive Curve Adjustment for Robust 3D Novel View Synthesis](https://arxiv.org/abs/2602.18322v1)**  
  Authors: Ziteng Cui, Shuhong Liu, Xiaoyu Dong, Xuangeng Chu, Lin Gu, Ming-Hsuan Yang, Tatsuya Harada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.18322v1.pdf)  
  Keywords: 3d gaussian, lighting, gaussian splatting, real-time rendering, ar, nerf, illumination  
- **[3D Scene Rendering with Multimodal Gaussian Splatting](https://arxiv.org/abs/2602.17124v1)**  
  Authors: Chi-Shiang Gau, Konstantinos D. Polyzos, Athanasios Bacharis, Saketh Madhuvarasu, Tara Javidi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17124v1.pdf)  
  Keywords: 3d gaussian, lighting, efficient, gaussian splatting, robotics, high-fidelity, ar, autonomous driving, illumination  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: mapping, 3d gaussian, outdoor, lighting, head, gaussian splatting, localization, ar, semantic, geometry  

### SLAM

*Showing the latest 50 out of 151 papers*

- **[SR3R: Rethinking Super-Resolution 3D Reconstruction With Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2602.24020v1)**  
  Authors: Xiang Feng, Xiangbo Wang, Tieshi Zhong, Chengkai Wang, Yiting Zhao, Tianxiang Xu, Zhenzhong Kuang, Feiwei Qin, Xuefei Yin, Yanming Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.24020v1.pdf)  
  Keywords: mapping, 3d gaussian, 3d reconstruction, gaussian splatting, ar, geometry  
- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[Sapling-NeRF: Geo-Localised Sapling Reconstruction in Forests for Ecological Monitoring](https://arxiv.org/abs/2602.22731v1)**  
  Authors: Miguel Ángel Muñoz-Bañón, Nived Chebrolu, Sruthi M. Krishna Moorthy, Yifu Tao, Fernando Torres, Roberto Salguero-Gómez, Maurice Fallon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22731v1.pdf)  
  Keywords: dynamic, 3d gaussian, slam, 3d reconstruction, gaussian splatting, ar, nerf  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: segmentation, lightweight, mapping, dynamic, illumination, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: 4d, dynamic, mapping, 3d gaussian, slam, 3d reconstruction, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[NRGS-SLAM: Monocular Non-Rigid SLAM for Endoscopy via Deformation-Aware 3D Gaussian Splatting](https://arxiv.org/abs/2602.17182v1)**  
  Authors: Jiwei Shan, Zeyu Cai, Yirui Li, Yongbo Chen, Lijun Han, Yun-hui Liu, Hesheng Wang, Shing Shin Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17182v1.pdf)  
  Keywords: mapping, 3d gaussian, slam, deformation, efficient, gaussian splatting, localization, ar, tracking, motion  
- **[Time-Archival Camera Virtualization for Sports and Visual Performances](https://arxiv.org/abs/2602.15181v1)**  
  Authors: Yunxiao Zhang, William Stone, Suryansh Kumar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15181v1.pdf)  
  Keywords: fast, 4d, dynamic, 3d gaussian, neural rendering, efficient, gaussian splatting, ar, tracking, motion  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: mapping, 3d gaussian, outdoor, lighting, head, gaussian splatting, localization, ar, semantic, geometry  
- **[High-fidelity 3D reconstruction for planetary exploration](https://arxiv.org/abs/2602.13909v1)**  
  Authors: Alfonso Martínez-Petersen, Levin Gerdes, David Rodríguez-Martínez, C. J. Pérez-del-Pulgar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.13909v1.pdf)  
  Keywords: face, mapping, slam, 3d reconstruction, efficient, gaussian splatting, robotics, high-fidelity, localization, ar, nerf, motion  
- **[LatentAM: Real-Time, Large-Scale Latent Gaussian Attention Mapping via Online Dictionary Learning](https://arxiv.org/abs/2602.12314v1)**  
  Authors: Junwoon Lee, Yulun Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.12314v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://junwoonlee.github.io/projects/LatentAM)  
  Keywords: mapping, 3d gaussian, efficient, gaussian splatting, compact, ar, semantic  

### Scene Understanding

*Showing the latest 50 out of 227 papers*

- **[Latent Gaussian Splatting for 4D Panoptic Occupancy Tracking](https://arxiv.org/abs/2602.23172v1)**  
  Authors: Maximilian Luz, Rohit Mohan, Thomas Nürnberg, Yakov Miron, Daniele Cattaneo, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.23172v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lags.cs.uni-freiburg.de/.)  
  Keywords: segmentation, 4d, dynamic, 3d gaussian, head, efficient, gaussian splatting, understanding, ar, tracking  
- **[ArtPro: Self-Supervised Articulated Object Reconstruction with Adaptive Integration of Mobility Proposals](https://arxiv.org/abs/2602.22666v1)**  
  Authors: Xuelu Li, Zhaonan Wang, Xiaogang Wang, Lei Wu, Manyi Li, Changhe Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22666v1.pdf)  
  Keywords: segmentation, dynamic, 3d gaussian, gaussian splatting, high-fidelity, ar, motion, geometry  
- **[BetterScene: 3D Scene Synthesis with Representation-Aligned Generative Model](https://arxiv.org/abs/2602.22596v1)**  
  Authors: Yuci Han, Charles Toth, John E. Anderson, William J. Shuart, Alper Yilmaz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.22596v1.pdf)  
  Keywords: 3d gaussian, gaussian splatting, ar, semantic, geometry  
- **[Interactive Augmented Reality-enabled Outdoor Scene Visualization For Enhanced Real-time Disaster Response](https://arxiv.org/abs/2602.21874v1)**  
  Authors: Dimitrios Apostolakis, Georgios Angelidis, Vasileios Argyriou, Panagiotis Sarigiannidis, Georgios Th. Papadopoulos  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21874v1.pdf)  
  Keywords: face, fast, lightweight, 3d gaussian, outdoor, lighting, gaussian splatting, ar, semantic  
- **[DAGS-SLAM: Dynamic-Aware 3DGS SLAM via Spatiotemporal Motion Probability and Uncertainty-Aware Scheduling](https://arxiv.org/abs/2602.21644v2)**  
  Authors: Li Zhang, Yu-An Liu, Xijia Jiang, Conghao Huang, Danyang Li, Yanyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.21644v2.pdf)  
  Keywords: segmentation, lightweight, mapping, dynamic, illumination, 3d gaussian, slam, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[RU4D-SLAM: Reweighting Uncertainty in Gaussian Splatting SLAM for 4D Scene Reconstruction](https://arxiv.org/abs/2602.20807v1)**  
  Authors: Yangfan Zhao, Hanwei Zhang, Ke Huang, Qiufeng Wang, Zhenzhou Shao, Dengyu Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ru4d-slam.github.io)  
  Keywords: 4d, dynamic, mapping, 3d gaussian, slam, 3d reconstruction, efficient, gaussian splatting, localization, ar, tracking, motion, semantic  
- **[Aesthetic Camera Viewpoint Suggestion with 3D Aesthetic Field](https://arxiv.org/abs/2602.20363v1)**  
  Authors: Sheyang Tang, Armin Shafiee Sarvestani, Jialu Xu, Xiaoyu Xu, Zhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.20363v1.pdf)  
  Keywords: 3d gaussian, efficient, gaussian splatting, understanding, ar, geometry  
- **[B$^3$-Seg: Camera-Free, Training-Free 3DGS Segmentation via Analytic EIG and Beta-Bernoulli Bayesian Updates](https://arxiv.org/abs/2602.17134v1)**  
  Authors: Hiromichi Kamata, Samuel Arthur Munro, Fuminori Homma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.17134v1.pdf)  
  Keywords: segmentation, fast, 3d gaussian, gaussian splatting, ar  
- **[Semantic-Guided 3D Gaussian Splatting for Transient Object Removal](https://arxiv.org/abs/2602.15516v1)**  
  Authors: Aditi Prabakaran, Priyesh Shukla  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.15516v1.pdf)  
  Keywords: 3d gaussian, head, gaussian splatting, real-time rendering, ar, nerf, motion, semantic  
- **[Wrivinder: Towards Spatial Intelligence for Geo-locating Ground Images onto Satellite Imagery](https://arxiv.org/abs/2602.14929v1)**  
  Authors: Chandrakanth Gudavalli, Tajuddin Manhar Mohammed, Abhay Yadav, Ananth Vishnu Bhaskar, Hardik Prajapati, Cheng Peng, Rama Chellappa, Shivkumar Chandrasekaran, B. S. Manjunath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.14929v1.pdf)  
  Keywords: mapping, 3d gaussian, outdoor, lighting, head, gaussian splatting, localization, ar, semantic, geometry  



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