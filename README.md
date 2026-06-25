# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-06-25 02:15:13

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

- [3DGS Surveys](#3dgs-surveys) (13 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (216 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (996 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (325 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (379 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (77 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (400 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (45 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (420 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (245 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (27 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (135 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (151 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (229 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, 4d, autonomous driving, motion, medical, 3d reconstruction, compact, ar, recognition, vr, neural rendering  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: survey, gaussian splatting, geometry, mapping, ar, animation  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, motion, tracking, slam, geometry, efficient, 3d reconstruction, ar  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, ar, vr  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ray tracing, survey, gaussian splatting, 3d gaussian, mapping, ar  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, face, motion, dynamic, tracking, slam, efficient, mapping, localization, ar  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, ar, robotics  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, geometry, efficient, ar, nerf  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, 4d, high-fidelity, dynamic, efficient, 3d reconstruction, compression, compact, ar  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: survey, gaussian splatting, 3d gaussian, understanding, slam, mapping, semantic, localization, ar, nerf, robotics  

### Acceleration

*Showing the latest 50 out of 216 papers*

- **[ArtiTwinSplat: Interactable Digital Twin Reconstruction via Gaussian Splatting from RGB-D videos](https://arxiv.org/abs/2606.24628v1)**  
  Authors: Pranjal Mishra, René Zurbrügg, Max Wilder-Smith, Marco Hutter, Marc Pollefeys, Zuria Bauer, Hermann Blum  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24628v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, motion, tracking, human, ar  
- **[Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints](https://arxiv.org/abs/2606.24353v1)**  
  Authors: Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24353v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hchoi256.github.io/projects/ovbevseg/.)  
  Keywords: gaussian splatting, segmentation, autonomous driving, geometry, efficient, semantic, ar, fast  
- **[3DCarGen: Scalable 3D Car Generation via 3D-consistent Multi-view Synthesis](https://arxiv.org/abs/2606.24257v1)**  
  Authors: Hongli Xiao, Youjian Zhang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24257v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, autonomous driving, ar, fast  
- **[Deep Learning Approaches for 3D Medical Scene Completion: From Geometric Modeling to Generative Paradigms](https://arxiv.org/abs/2606.24180v1)**  
  Authors: Afifa Khaled, Said Jadid Abdulkadir, Majdy Mohamed Eltayeb Eltahir  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24180v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, medical, semantic, ar, robotics  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[ACE-GS: Acing the Trade-off with Accurate, Compact and Efficient 3D Gaussian Splatting](https://arxiv.org/abs/2606.21244v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21244v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, high-fidelity, acceleration, efficient, compact, ar, fast  
- **[Hand-4DGS: Feed-Forward 3D Gaussian Splatting for 4D Hand Reconstruction from Egocentric Videos](https://arxiv.org/abs/2606.19156v1)**  
  Authors: Jeongmin Bae, Seoha Kim, Marc Pollefeys, Mahdi Rad, Youngjung Uh, Taein Kwon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19156v1.pdf)  
  Keywords: head, gaussian splatting, 3d gaussian, body, 4d, vr, motion, dynamic, human, ar, fast  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, efficient, outdoor, ar, fast  
- **[Intrinsic 4D Gaussian Segmentation from Scene Cues](https://arxiv.org/abs/2606.18623v1)**  
  Authors: Hasan Yazar, Mohamed Rayan Barhdadi, Erchin Serpedin, Mehmet Tuncel, Hasan Kurban  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18623v1.pdf)  
  Keywords: gaussian splatting, segmentation, 4d, motion, dynamic, geometry, ar, deformation, nerf, fast  

### Applications

*Showing the latest 50 out of 996 papers*

- **[Gastroendoscopy View Synthesis: A New Real Dataset and Evaluation](https://arxiv.org/abs/2606.25427v1)**  
  Authors: Masaki Minai, Yusuke Monno, Masatoshi Okutomi, Sho Suzuki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.25427v1.pdf)  
  Keywords: ar, gaussian splatting, nerf, 3d gaussian  
- **[FLUX3D: High-Fidelity 3D Gaussian Generation with Diffusion-Aligned Sparse Representation](https://arxiv.org/abs/2606.24874v1)**  
  Authors: Haorui Ji, Weizhe Liu, Hongdong Li, Hengkai Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, geometry, semantic, ar  
- **[OrbitForge: Text-to-3D Scene Generation via Reconstruction-Anchored Video Synthesis](https://arxiv.org/abs/2606.24799v1)**  
  Authors: Chenrui Fan, Paolo Favaro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24799v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, 3d reconstruction, high quality, ar  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[ArtiTwinSplat: Interactable Digital Twin Reconstruction via Gaussian Splatting from RGB-D videos](https://arxiv.org/abs/2606.24628v1)**  
  Authors: Pranjal Mishra, René Zurbrügg, Max Wilder-Smith, Marco Hutter, Marc Pollefeys, Zuria Bauer, Hermann Blum  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24628v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, motion, tracking, human, ar  
- **[SignNet-1M: Large-Scale Multilingual Sign Language Video Dataset with Downstream Benchmarks](https://arxiv.org/abs/2606.24361v1)**  
  Authors: Zhewen He, Junyi Hu, Haomian Huang, Zhenhua Li, Yu-Shen Liu, Yi Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24361v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://signnet.chatsign.ai/.)  
  Keywords: gaussian splatting, 3d gaussian, motion, compression, ar, recognition  
- **[Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints](https://arxiv.org/abs/2606.24353v1)**  
  Authors: Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24353v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hchoi256.github.io/projects/ovbevseg/.)  
  Keywords: gaussian splatting, segmentation, autonomous driving, geometry, efficient, semantic, ar, fast  
- **[MM-TRELLIS: Point-Cloud Guided Multi-Modal 3D Vehicle Generation in Autonomous Driving](https://arxiv.org/abs/2606.24301v1)**  
  Authors: Hongli Xiao, Youjian Zhang, Yucai Bai, Chaoyue Wang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24301v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, autonomous driving, high-fidelity, geometry, ar, neural rendering  
- **[3DCarGen: Scalable 3D Car Generation via 3D-consistent Multi-view Synthesis](https://arxiv.org/abs/2606.24257v1)**  
  Authors: Hongli Xiao, Youjian Zhang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24257v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, autonomous driving, ar, fast  
- **[Deep Learning Approaches for 3D Medical Scene Completion: From Geometric Modeling to Generative Paradigms](https://arxiv.org/abs/2606.24180v1)**  
  Authors: Afifa Khaled, Said Jadid Abdulkadir, Majdy Mohamed Eltayeb Eltahir  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24180v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, medical, semantic, ar, robotics  

### Avatar Generation

*Showing the latest 50 out of 325 papers*

- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[ArtiTwinSplat: Interactable Digital Twin Reconstruction via Gaussian Splatting from RGB-D videos](https://arxiv.org/abs/2606.24628v1)**  
  Authors: Pranjal Mishra, René Zurbrügg, Max Wilder-Smith, Marco Hutter, Marc Pollefeys, Zuria Bauer, Hermann Blum  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24628v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, motion, tracking, human, ar  
- **[Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild](https://arxiv.org/abs/2606.23688v1)**  
  Authors: Yehonathan Litman, Xiaoxuan Ma, Manan Shah, Nicolas Ugrinovic, Kris Kitani, Fernando De la Torre, Shubham Tulsiani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23688v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, 4d, motion, dynamic, geometry, 3d reconstruction, ar, deformation  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[LOGOS: LiDAR-Only Gaussian Elevation Splatting for Unified Tiny Obstacle Segmentation](https://arxiv.org/abs/2606.21527v1)**  
  Authors: Nan Ming, Yeqiang Qian, Chunxiang Wang, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21527v1.pdf)  
  Keywords: face, ar, gaussian splatting, segmentation  
- **[LIT-GS: LiDAR-Inertial-Thermal Gaussian Splatting for Illumination-Robust Mapping](https://arxiv.org/abs/2606.20424v1)**  
  Authors: Shikuan Shi, Chunran Zheng, Jiaming Xu, Tianyong Ye, Tao Yu, Yukang Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20424v1.pdf)  
  Keywords: gaussian splatting, face, illumination, geometry, lighting, mapping, ar, neural rendering  
- **[Hand-4DGS: Feed-Forward 3D Gaussian Splatting for 4D Hand Reconstruction from Egocentric Videos](https://arxiv.org/abs/2606.19156v1)**  
  Authors: Jeongmin Bae, Seoha Kim, Marc Pollefeys, Mahdi Rad, Youngjung Uh, Taein Kwon  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19156v1.pdf)  
  Keywords: head, gaussian splatting, 3d gaussian, body, 4d, vr, motion, dynamic, human, ar, fast  
- **[FlowObject: Flow Steering for Bridging Generative Priors and Reconstruction Fidelity](https://arxiv.org/abs/2606.19019v1)**  
  Authors: Yuchen Rao, Xuqian Ren, Yinyu Nie, Sayan Deb Sarkar, Biao Zhang, Vincent Lepetit, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19019v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, sparse-view, geometry, 3d reconstruction, ar  
- **[AIGS-Net: Compact Illumination Field Modeling via 2D Gaussian Splatting for Fast Low-Light Image Enhancement](https://arxiv.org/abs/2606.17998v1)**  
  Authors: Yuhan Chen, Kunyang Huang, Fuchen Li, Zhuohan Qin, Guofa Li, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17998v1.pdf)  
  Keywords: lightweight, gaussian splatting, face, illumination, dynamic, efficient, mapping, compact, ar, fast  

### Dynamic Scene

*Showing the latest 50 out of 379 papers*

- **[OrbitForge: Text-to-3D Scene Generation via Reconstruction-Anchored Video Synthesis](https://arxiv.org/abs/2606.24799v1)**  
  Authors: Chenrui Fan, Paolo Favaro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24799v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, 3d reconstruction, high quality, ar  
- **[ArtiTwinSplat: Interactable Digital Twin Reconstruction via Gaussian Splatting from RGB-D videos](https://arxiv.org/abs/2606.24628v1)**  
  Authors: Pranjal Mishra, René Zurbrügg, Max Wilder-Smith, Marco Hutter, Marc Pollefeys, Zuria Bauer, Hermann Blum  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24628v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, motion, tracking, human, ar  
- **[SignNet-1M: Large-Scale Multilingual Sign Language Video Dataset with Downstream Benchmarks](https://arxiv.org/abs/2606.24361v1)**  
  Authors: Zhewen He, Junyi Hu, Haomian Huang, Zhenhua Li, Yu-Shen Liu, Yi Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24361v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://signnet.chatsign.ai/.)  
  Keywords: gaussian splatting, 3d gaussian, motion, compression, ar, recognition  
- **[Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild](https://arxiv.org/abs/2606.23688v1)**  
  Authors: Yehonathan Litman, Xiaoxuan Ma, Manan Shah, Nicolas Ugrinovic, Kris Kitani, Fernando De la Torre, Shubham Tulsiani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23688v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, 4d, motion, dynamic, geometry, 3d reconstruction, ar, deformation  
- **[MeGAS: Thermomechanical Dynamic Gaussian Splatting for Thermophysical Scene Editing](https://arxiv.org/abs/2606.23455v1)**  
  Authors: Zesong Yang, Yuanhang Lei, Liyuan Cui, Yihang Chen, Jiaer Huang, Boming Zhao, Peter Yichen Chen, Hujun Bao, Zhaopeng Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23455v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, dynamic, animation, ar, deformation, neural rendering  
- **[Temporally Aware Densification for Dynamic 3D Gaussian Splatting](https://arxiv.org/abs/2606.23212v1)**  
  Authors: Vikram Sandu, Mayurdeep Pathak, Rajiv Soundararajan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23212v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, dynamic, ar, deformation  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, efficient, ar, deformation  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  
- **[Scene-Level Heterogeneous Physics Simulation with 3D Gaussian Splats](https://arxiv.org/abs/2606.21753v1)**  
  Authors: Xiaoyang Liu, Shangzhe Wu, Kai Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21753v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, ar, deformation  

### Few-shot

*Showing the latest 50 out of 77 papers*

- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, efficient, ar, deformation  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[From Uncertainty to Stability and Fidelity: Guiding Sparse-View 3D Gaussian Splatting with Fisher Information](https://arxiv.org/abs/2606.20842v1)**  
  Authors: Junbao Zhou, Qingshan Xu, Yuan Zhou, Xiaolong Shen, Beier Zhu, Kesen Zhao, Yiming Zeng, Chen Bai, Cheng Lu, Hanwang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20842v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, sparse-view  
- **[VisDom: Sparse Novel View Synthesis with Visible Domain Constraint](https://arxiv.org/abs/2606.20531v1)**  
  Authors: Mariia Gladkova*, Tarun Yenamandra*, Edmond Boyer, Robert Maier, Tony Tung, Daniel Cremers  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20531v1.pdf)  
  Keywords: gaussian splatting, sparse-view, geometry, ar, nerf  
- **[FlowObject: Flow Steering for Bridging Generative Priors and Reconstruction Fidelity](https://arxiv.org/abs/2606.19019v1)**  
  Authors: Yuchen Rao, Xuqian Ren, Yinyu Nie, Sayan Deb Sarkar, Biao Zhang, Vincent Lepetit, Friedrich Fraundorfer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19019v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, sparse-view, geometry, 3d reconstruction, ar  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, high-fidelity, efficient, outdoor, ar, nerf  
- **[BEAST3D: Animal behavioral analysis and neural encoding from multi-view video via Gaussian splatting](https://arxiv.org/abs/2606.02937v1)**  
  Authors: Yanchen Wang, Lenny Aharon, Wangshu Zhu, Kyle Daruwalla, Linghua Zhang, Jiaru Zou, Selmaan Chettih, Helen Hou, Liam Paninski, Matthew R Whiteway  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02937v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, 3d reconstruction, ar  
- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: lightweight, gaussian splatting, 3d gaussian, sparse-view, efficient, compact, ar, nerf, fast  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, motion, high-fidelity, efficient, ar, nerf  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, relighting, sparse-view, high-fidelity, illumination, geometry, lighting, relightable, ar, fast  

### Geometry Reconstruction

*Showing the latest 50 out of 400 papers*

- **[FLUX3D: High-Fidelity 3D Gaussian Generation with Diffusion-Aligned Sparse Representation](https://arxiv.org/abs/2606.24874v1)**  
  Authors: Haorui Ji, Weizhe Liu, Hongdong Li, Hengkai Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, geometry, semantic, ar  
- **[OrbitForge: Text-to-3D Scene Generation via Reconstruction-Anchored Video Synthesis](https://arxiv.org/abs/2606.24799v1)**  
  Authors: Chenrui Fan, Paolo Favaro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24799v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, 3d reconstruction, high quality, ar  
- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints](https://arxiv.org/abs/2606.24353v1)**  
  Authors: Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24353v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hchoi256.github.io/projects/ovbevseg/.)  
  Keywords: gaussian splatting, segmentation, autonomous driving, geometry, efficient, semantic, ar, fast  
- **[MM-TRELLIS: Point-Cloud Guided Multi-Modal 3D Vehicle Generation in Autonomous Driving](https://arxiv.org/abs/2606.24301v1)**  
  Authors: Hongli Xiao, Youjian Zhang, Yucai Bai, Chaoyue Wang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24301v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, autonomous driving, high-fidelity, geometry, ar, neural rendering  
- **[Geometry-Aware Style Transfer in 3D Gaussian Splatting](https://arxiv.org/abs/2606.24144v1)**  
  Authors: Min Hyeok Bang, Jun Hyeong Kim, Seung-Wook Kim, Se-Ho Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24144v1.pdf)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian  
- **[Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild](https://arxiv.org/abs/2606.23688v1)**  
  Authors: Yehonathan Litman, Xiaoxuan Ma, Manan Shah, Nicolas Ugrinovic, Kris Kitani, Fernando De la Torre, Shubham Tulsiani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23688v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, 4d, motion, dynamic, geometry, 3d reconstruction, ar, deformation  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, efficient, ar, deformation  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  

### Large Scene

- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, efficient, outdoor, ar, fast  
- **[MoonSplat: Monocular Online Gaussian Splatting with Sim(3) Global Optimization](https://arxiv.org/abs/2606.17935v1)**  
  Authors: Guo Pu, Yixuan Han, Haofeng Li, Yao Zhang, Hui Zhou, Zhouhui Lian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17935v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, tracking, efficient, 3d reconstruction, outdoor, ar, vr, robotics  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, high-fidelity, efficient, outdoor, ar, nerf  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: urban scene, gaussian splatting, large scene, face, high-fidelity, geometry, 3d reconstruction, ar, nerf  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, geometry, ar  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: outdoor, mapping, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: sparse view, gaussian splatting, 3d gaussian, autonomous driving, high-fidelity, illumination, dynamic, lighting, mapping, outdoor, ar, fast  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: gaussian splatting, 3d gaussian, face, high-fidelity, dynamic, geometry, efficient, outdoor, ar  

### Model Compression

*Showing the latest 50 out of 420 papers*

- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[SignNet-1M: Large-Scale Multilingual Sign Language Video Dataset with Downstream Benchmarks](https://arxiv.org/abs/2606.24361v1)**  
  Authors: Zhewen He, Junyi Hu, Haomian Huang, Zhenhua Li, Yu-Shen Liu, Yi Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24361v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://signnet.chatsign.ai/.)  
  Keywords: gaussian splatting, 3d gaussian, motion, compression, ar, recognition  
- **[Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints](https://arxiv.org/abs/2606.24353v1)**  
  Authors: Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24353v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hchoi256.github.io/projects/ovbevseg/.)  
  Keywords: gaussian splatting, segmentation, autonomous driving, geometry, efficient, semantic, ar, fast  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[Projection-Volume Fidelity Divergence: Diagnosing and Controlling Optimization Drift in Sparse-View 3D Gaussian Tomography](https://arxiv.org/abs/2606.22525v1)**  
  Authors: Yikuang Yuluo, Ao Wang, Shen Kuan, Yujie Liu, Wang Liao, Ying Chen, Shuangyang Zhong, Yixing Huang, Fuquan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22525v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, sparse-view, geometry, efficient, ar, deformation  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: gaussian splatting, global illumination, 3d gaussian, illumination, geometry, efficient, 3d reconstruction, ar  
- **[ACE-GS: Acing the Trade-off with Accurate, Compact and Efficient 3D Gaussian Splatting](https://arxiv.org/abs/2606.21244v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21244v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, high-fidelity, acceleration, efficient, compact, ar, fast  
- **[Point-Cloud-Assistant Localized Statistical Channel Prediction by Tangent Gaussian Splatting](https://arxiv.org/abs/2606.18734v1)**  
  Authors: Ye Xue, Yiheng Wang, Xinhua Shao, Qi Yan, Shutao Zhang, Tsung-Hui Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18734v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, geometry, efficient, outdoor, ar, fast  

### Quality Enhancement

*Showing the latest 50 out of 245 papers*

- **[FLUX3D: High-Fidelity 3D Gaussian Generation with Diffusion-Aligned Sparse Representation](https://arxiv.org/abs/2606.24874v1)**  
  Authors: Haorui Ji, Weizhe Liu, Hongdong Li, Hengkai Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, geometry, semantic, ar  
- **[OrbitForge: Text-to-3D Scene Generation via Reconstruction-Anchored Video Synthesis](https://arxiv.org/abs/2606.24799v1)**  
  Authors: Chenrui Fan, Paolo Favaro  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24799v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, 3d reconstruction, high quality, ar  
- **[MM-TRELLIS: Point-Cloud Guided Multi-Modal 3D Vehicle Generation in Autonomous Driving](https://arxiv.org/abs/2606.24301v1)**  
  Authors: Hongli Xiao, Youjian Zhang, Yucai Bai, Chaoyue Wang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24301v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, autonomous driving, high-fidelity, geometry, ar, neural rendering  
- **[MeGAS: Thermomechanical Dynamic Gaussian Splatting for Thermophysical Scene Editing](https://arxiv.org/abs/2606.23455v1)**  
  Authors: Zesong Yang, Yuanhang Lei, Liyuan Cui, Yihang Chen, Jiaer Huang, Boming Zhao, Peter Yichen Chen, Hujun Bao, Zhaopeng Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23455v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, dynamic, animation, ar, deformation, neural rendering  
- **[DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction](https://arxiv.org/abs/2606.23031v1)**  
  Authors: Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23031v1.pdf)  
  Keywords: urban scene, gaussian splatting, 3d gaussian, large scene, high-fidelity, dynamic, geometry, efficient, ar, fast  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[ACE-GS: Acing the Trade-off with Accurate, Compact and Efficient 3D Gaussian Splatting](https://arxiv.org/abs/2606.21244v1)**  
  Authors: Jijian Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21244v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, high-fidelity, acceleration, efficient, compact, ar, fast  
- **[MMD-SLAM: Structure-Enhanced Multi-Meta Gaussian Distribution-Guided Visual SLAM](https://arxiv.org/abs/2606.19874v1)**  
  Authors: Fan Zhu, Ziyu Chen, Peichen Liu, Yifan Zhao, Zhisong Xu, Hui Zhu, Hongxing Zhou, Sixun Liu, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, tracking, slam, geometry, mapping, localization, ar  
- **[Splaxel: Efficient Distributed Training of 3D Gaussian Splatting for Large-scale Scene Reconstruction via Pixel-level Communication](https://arxiv.org/abs/2606.18588v1)**  
  Authors: Wenqi Jia, Zhewen Hu, Ying Huang, Yu Gong, Stavros Kalafatis, Yuke Wang, Wei Niu, Chengming Zhang, Ang Li, Sheng Di, Yuede Ji, Bo Fang, Miao Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18588v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, efficient, ar  

### Ray Tracing

- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: gaussian splatting, global illumination, 3d gaussian, illumination, geometry, efficient, 3d reconstruction, ar  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: gaussian splatting, global illumination, high-fidelity, illumination, ar  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: ray tracing, gaussian splatting, 3d gaussian, segmentation, geometry, efficient, semantic, ar, reflection  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: gaussian splatting, global illumination, 3d gaussian, face, shadow, illumination, ar, fast  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, gaussian splatting, ray casting, 3d gaussian  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: ray tracing, gaussian splatting, 3d gaussian, high-fidelity, geometry, ar  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: ray tracing, gaussian splatting, 3d gaussian, dynamic, tracking, efficient, lighting, semantic, ar, robotics  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ray tracing, face, gaussian splatting, ar, reflection  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: ray tracing, gaussian splatting, face, 3d gaussian, tracking, slam, efficient, mapping, semantic, localization, ar  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: ray tracing, gaussian splatting, 3d gaussian, shadow, mapping, relightable, ar, reflection  

### Relighting

*Showing the latest 50 out of 135 papers*

- **[Lighting-Consistent Object Transfer Across Radiance Fields](https://arxiv.org/abs/2606.22481v1)**  
  Authors: Nicolás Violante, George Kopanas, Linus Franke, Julien Philip, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22481v1.pdf)  
  Keywords: lighting, gaussian splatting, 3d gaussian, ar  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: gaussian splatting, global illumination, 3d gaussian, illumination, geometry, efficient, 3d reconstruction, ar  
- **[LIT-GS: LiDAR-Inertial-Thermal Gaussian Splatting for Illumination-Robust Mapping](https://arxiv.org/abs/2606.20424v1)**  
  Authors: Shikuan Shi, Chunran Zheng, Jiaming Xu, Tianyong Ye, Tao Yu, Yukang Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20424v1.pdf)  
  Keywords: gaussian splatting, face, illumination, geometry, lighting, mapping, ar, neural rendering  
- **[AIGS-Net: Compact Illumination Field Modeling via 2D Gaussian Splatting for Fast Low-Light Image Enhancement](https://arxiv.org/abs/2606.17998v1)**  
  Authors: Yuhan Chen, Kunyang Huang, Fuchen Li, Zhuohan Qin, Guofa Li, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17998v1.pdf)  
  Keywords: lightweight, gaussian splatting, face, illumination, dynamic, efficient, mapping, compact, ar, fast  
- **[Gaussian Light Field Splatting: A Physical Prior-Driven Vision Transformer for Unsupervised Low-Light Image Enhancement](https://arxiv.org/abs/2606.17985v1)**  
  Authors: Yuhan Chen, Wenxuan Yu, Guofa Li, Fuchen Li, Kunyang Huang, Yicui Shi, Ying Fang, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17985v1.pdf)  
  Keywords: illumination, gaussian splatting, ar  
- **[RealityBridge: Bridging Editable 3D Gaussian Splatting Driving Simulations and Real-World Videos](https://arxiv.org/abs/2606.16278v1)**  
  Authors: Zhenhua Wu, Yun Pang, Mingkun Chang, Yuwei Ning, Liangzhi Wang, Yi Xiao, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16278v1.pdf)  
  Keywords: lightweight, gaussian splatting, 3d gaussian, autonomous driving, illumination, semantic, ar  
- **[Dehaze-GaussianImage: Zero-Shot Dehazing via Efficient 2D Gaussian Splatting Representation](https://arxiv.org/abs/2606.16163v1)**  
  Authors: Yuhan Chen, Wenxuan Yu, Guofa Li, Kunyang Huang, Ying Fang, Yicui Shi, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16163v1.pdf)  
  Keywords: gaussian splatting, dynamic, efficient, lighting, ar  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: gaussian splatting, global illumination, high-fidelity, illumination, ar  
- **[Wild3R: Feed-Forward 3D Gaussian Splatting from Unconstrained Sparse Photo Collection](https://arxiv.org/abs/2606.11894v2)**  
  Authors: Yuto Furutani, Takashi Otonari, Kaede Shiohara, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11894v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, illumination, lighting, ar  
- **[MaterialClusterGS: Palette-Based Material Decomposition and Physically-Based Relighting with 2D Gaussian Splatting](https://arxiv.org/abs/2606.09018v1)**  
  Authors: Hao Zhang, Ang Li, Boyan Du, Junke Zhu, Fei Zhu, Meng Gai, Zhangjin Huang, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09018v1.pdf)  
  Keywords: gaussian splatting, relighting, shadow, illumination, lighting, compact, ar  

### SLAM

*Showing the latest 50 out of 151 papers*

- **[Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM](https://arxiv.org/abs/2606.24796v1)**  
  Authors: Leshu Li, Jie Peng, Yang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, face, autonomous driving, slam, geometry, efficient, mapping, localization, outdoor, ar  
- **[ArtiTwinSplat: Interactable Digital Twin Reconstruction via Gaussian Splatting from RGB-D videos](https://arxiv.org/abs/2606.24628v1)**  
  Authors: Pranjal Mishra, René Zurbrügg, Max Wilder-Smith, Marco Hutter, Marc Pollefeys, Zuria Bauer, Hermann Blum  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24628v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, motion, tracking, human, ar  
- **[ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only](https://arxiv.org/abs/2606.22091v1)**  
  Authors: Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22091v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, sparse-view, high-fidelity, slam, geometry, mapping, ar, fast, robotics  
- **[LIT-GS: LiDAR-Inertial-Thermal Gaussian Splatting for Illumination-Robust Mapping](https://arxiv.org/abs/2606.20424v1)**  
  Authors: Shikuan Shi, Chunran Zheng, Jiaming Xu, Tianyong Ye, Tao Yu, Yukang Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.20424v1.pdf)  
  Keywords: gaussian splatting, face, illumination, geometry, lighting, mapping, ar, neural rendering  
- **[MMD-SLAM: Structure-Enhanced Multi-Meta Gaussian Distribution-Guided Visual SLAM](https://arxiv.org/abs/2606.19874v1)**  
  Authors: Fan Zhu, Ziyu Chen, Peichen Liu, Yifan Zhao, Zhisong Xu, Hui Zhu, Hongxing Zhou, Sixun Liu, Chunmao Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, tracking, slam, geometry, mapping, localization, ar  
- **[AIGS-Net: Compact Illumination Field Modeling via 2D Gaussian Splatting for Fast Low-Light Image Enhancement](https://arxiv.org/abs/2606.17998v1)**  
  Authors: Yuhan Chen, Kunyang Huang, Fuchen Li, Zhuohan Qin, Guofa Li, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17998v1.pdf)  
  Keywords: lightweight, gaussian splatting, face, illumination, dynamic, efficient, mapping, compact, ar, fast  
- **[MoonSplat: Monocular Online Gaussian Splatting with Sim(3) Global Optimization](https://arxiv.org/abs/2606.17935v1)**  
  Authors: Guo Pu, Yixuan Han, Haofeng Li, Yao Zhang, Hui Zhou, Zhouhui Lian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17935v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, tracking, efficient, 3d reconstruction, outdoor, ar, vr, robotics  
- **[SplatlessDF: Continuous Distance Field Mapping with Non-Splatting Gaussians](https://arxiv.org/abs/2606.13990v1)**  
  Authors: Monisha Mushtary Uttsha, Lan Wu, Teresa Vidal-Calleja  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.13990v1.pdf)  
  Keywords: face, gaussian splatting, geometry, efficient, mapping, ar  
- **[Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting](https://arxiv.org/abs/2606.11841v1)**  
  Authors: Mingzhe Lyu, Jinqiang Cui, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11841v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, dynamic, 3d reconstruction, mapping, ar  
- **[QuadVerse: An Integrated Framework Aligning Visual-Physical Reality for Quadruped Simulation](https://arxiv.org/abs/2606.07118v2)**  
  Authors: Yuxiang Chen, Yuanhao Wang, Ziheng Zhang, Meng Zhang, Yu Liu, Yufei Jia, Tiancai Wang, Erjin Zhou, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07118v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, motion, dynamic, tracking, geometry, semantic, ar  

### Scene Understanding

*Showing the latest 50 out of 229 papers*

- **[FLUX3D: High-Fidelity 3D Gaussian Generation with Diffusion-Aligned Sparse Representation](https://arxiv.org/abs/2606.24874v1)**  
  Authors: Haorui Ji, Weizhe Liu, Hongdong Li, Hengkai Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24874v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, high-fidelity, geometry, semantic, ar  
- **[SignNet-1M: Large-Scale Multilingual Sign Language Video Dataset with Downstream Benchmarks](https://arxiv.org/abs/2606.24361v1)**  
  Authors: Zhewen He, Junyi Hu, Haomian Huang, Zhenhua Li, Yu-Shen Liu, Yi Fang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24361v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://signnet.chatsign.ai/.)  
  Keywords: gaussian splatting, 3d gaussian, motion, compression, ar, recognition  
- **[Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints](https://arxiv.org/abs/2606.24353v1)**  
  Authors: Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24353v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hchoi256.github.io/projects/ovbevseg/.)  
  Keywords: gaussian splatting, segmentation, autonomous driving, geometry, efficient, semantic, ar, fast  
- **[Deep Learning Approaches for 3D Medical Scene Completion: From Geometric Modeling to Generative Paradigms](https://arxiv.org/abs/2606.24180v1)**  
  Authors: Afifa Khaled, Said Jadid Abdulkadir, Majdy Mohamed Eltayeb Eltahir  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.24180v1.pdf)  
  Keywords: real-time rendering, gaussian splatting, 3d gaussian, medical, semantic, ar, robotics  
- **[Learning Stable Canonical Worlds for Novel View Synthesis and Beyond](https://arxiv.org/abs/2606.23027v1)**  
  Authors: Xiaoyu Xu, Jian Zou, Sheyang Tang, Zhihua Wang, Jing Liao, Kede Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.23027v1.pdf)  
  Keywords: ar, gaussian splatting, semantic, segmentation  
- **[Multi4D: High-Fidelity Dynamic Gaussian Splatting via Multi-Level Competitive Allocation](https://arxiv.org/abs/2606.22197v1)**  
  Authors: Rui Wang, Quentin Lohmeyer, Siyu Tang, Mirko Meboldt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.22197v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://batfacewayne.github.io/Multi4D.io/)  
  Keywords: head, gaussian splatting, 3d gaussian, face, 4d, segmentation, motion, high-fidelity, dynamic, geometry, semantic, compact, ar, deformation  
- **[LOGOS: LiDAR-Only Gaussian Elevation Splatting for Unified Tiny Obstacle Segmentation](https://arxiv.org/abs/2606.21527v1)**  
  Authors: Nan Ming, Yeqiang Qian, Chunxiang Wang, Ming Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21527v1.pdf)  
  Keywords: face, ar, gaussian splatting, segmentation  
- **[Building Drift: Documenting On-Site Construction Adaptations Across Material Lifecycles](https://arxiv.org/abs/2606.19609v1)**  
  Authors: Ritik Batra, Martin Tamke, Tom Svilans, Jan Hüls, Amritansh Kwatra, Steven J. Jackson, Thijs Roumen, Mette Ramsgaard Thomsen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.19609v1.pdf)  
  Keywords: ar, gaussian splatting, semantic, 3d gaussian  
- **[Intrinsic 4D Gaussian Segmentation from Scene Cues](https://arxiv.org/abs/2606.18623v1)**  
  Authors: Hasan Yazar, Mohamed Rayan Barhdadi, Erchin Serpedin, Mehmet Tuncel, Hasan Kurban  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.18623v1.pdf)  
  Keywords: gaussian splatting, segmentation, 4d, motion, dynamic, geometry, ar, deformation, nerf, fast  
- **[Edit3DGS: Unified Framework for Dynamic Head Editing via 2D Instruction-Guided Diffusion and 3D Gaussian Splatting](https://arxiv.org/abs/2606.17432v1)**  
  Authors: Duy-Dat Tran, Trung-Nghia Le  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.17432v1.pdf)  
  Keywords: lightweight, head, gaussian splatting, 3d gaussian, motion, high-fidelity, dynamic, 3d reconstruction, avatar, semantic, ar  



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