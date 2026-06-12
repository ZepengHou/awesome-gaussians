# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-06-12 02:36:40

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

- [3DGS Surveys](#3dgs-surveys) (14 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (216 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (337 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (385 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (78 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (394 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (45 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (427 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (244 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (28 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (132 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (149 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (226 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: 4d, 3d gaussian, 3d reconstruction, neural rendering, compact, autonomous driving, survey, vr, ar, gaussian splatting, recognition, medical, motion  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, survey, animation, ar, gaussian splatting, mapping  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, efficient, slam, survey, ar, gaussian splatting, tracking, motion  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: 3d gaussian, survey, vr, ar, gaussian splatting  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: 3d gaussian, ray tracing, survey, ar, gaussian splatting, mapping  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: 3d gaussian, efficient, slam, survey, face, ar, gaussian splatting, tracking, mapping, localization, dynamic, motion  
- **[Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey](https://arxiv.org/abs/2602.03878v1)**  
  Authors: Longjie Zhao, Ziming Hong, Jiaxin Huang, Runnan Chen, Mingming Gong, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.03878v1.pdf)  
  Keywords: robotics, 3d gaussian, survey, ar, gaussian splatting  
- **[TreeDGS: Aerial Gaussian Splatting for Distant DBH Measurement](https://arxiv.org/abs/2601.12823v3)**  
  Authors: Belal Shaheen, Minh-Hieu Nguyen, Bach-Thuan Bui, Shubham, Tim Wu, Michael Fairley, Matthew David Zane, Michael Wu, James Tompkin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2601.12823v3.pdf)  
  Keywords: geometry, 3d gaussian, efficient, survey, nerf, gaussian splatting, ar  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d gaussian, 3d reconstruction, efficient, compact, survey, ar, gaussian splatting, high-fidelity, compression, dynamic  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v2)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v2.pdf)  
  Keywords: understanding, 3d gaussian, robotics, slam, survey, nerf, gaussian splatting, ar, mapping, localization, semantic  

### Acceleration

*Showing the latest 50 out of 216 papers*

- **[Seeing What Matters: Perceptual Wrapper with Common Randomness for 3D Gaussian Splatting](https://arxiv.org/abs/2606.11782v1)**  
  Authors: He-Bi Yang, Jing-Zhong Chen, Yen-Kuan Ho, Sang NguyenQuang, Fan-Yi Hsu, Yun-Yu Lee, Jui-Chiu Chiang, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11782v1.pdf)  
  Keywords: lightweight, 3d gaussian, real-time rendering, ar, gaussian splatting  
- **[Leveraging NeRF-Rendered Images for 3D Gaussian Splatting](https://arxiv.org/abs/2606.09034v1)**  
  Authors: Mizuki Morikawa, Yuta Shimizu, Chunyu Li, Yusuke Monno, Masatoshi Okutomi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09034v1.pdf)  
  Keywords: 3d gaussian, fast, nerf, gaussian splatting, ar  
- **[LEGS: Laplacian-Enhanced Gaussian Splatting with a Nonlinear Weighted Loss](https://arxiv.org/abs/2606.07932v1)**  
  Authors: Yongfei Guo, Qizhou Huo, Xuan Sun, Yuanhao Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07932v1.pdf)  
  Keywords: 3d gaussian, fast, efficient, vr, nerf, gaussian splatting, ar  
- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: 3d gaussian, fast, efficient, ar, gaussian splatting, acceleration, compression, dynamic  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: understanding, 3d gaussian, fast, efficient, compact, ar, gaussian splatting, segmentation, semantic  
- **[VEDAL: Variational Error-Driven Asynchronous Learning for 3D Gaussian Splatting Pruning](https://arxiv.org/abs/2606.02346v1)**  
  Authors: Aoduo Li, Jiancheng Li, Huan Ye, Hongjian Xu, Shiting Wu, Xiujun Zhang, Zimeng Li, Xuhang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02346v1.pdf)  
  Keywords: 3d gaussian, real-time rendering, head, nerf, gaussian splatting, ar, compression  
- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: lightweight, 3d gaussian, fast, efficient, compact, sparse-view, nerf, gaussian splatting, ar  
- **[TIDES: Time-Derivative Event Simulation via Deformable Reconstruction](https://arxiv.org/abs/2606.02058v1)**  
  Authors: Christopher Thirgood, Dipon Kumar Ghosh, Simon Hadfield  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02058v1.pdf)  
  Keywords: geometry, fast, ar, gaussian splatting, dynamic, motion  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, shadow, fast, global illumination, face, ar, gaussian splatting, illumination  
- **[HiGS: A Hierarchical Rendering Architecture for Real-Time 3D Gaussian Splatting](https://arxiv.org/abs/2606.00352v1)**  
  Authors: Dawid Pająk, Martin Bisson, Rodolfo Lima  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00352v1.pdf)  
  Keywords: 3d gaussian, fast, ar, gaussian splatting, acceleration  

### Applications

*Showing the latest 50 out of 995 papers*

- **[Flex4DHuman: Flexible Multi-view Video Diffusion for 4D Human Reconstruction](https://arxiv.org/abs/2606.13655v1)**  
  Authors: Jen-Hao Cheng, Yipeng Wang, Hao Zhang, Gengshan Yang, Jenq-Neng Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.13655v1.pdf)  
  Keywords: 4d, geometry, human, vr, ar, gaussian splatting, dynamic  
- **[Wild3R: Feed-Forward 3D Gaussian Splatting from Unconstrained Sparse Photo Collection](https://arxiv.org/abs/2606.11894v2)**  
  Authors: Yuto Furutani, Takashi Otonari, Kaede Shiohara, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11894v2.pdf)  
  Keywords: 3d gaussian, lighting, ar, gaussian splatting, illumination  
- **[Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting](https://arxiv.org/abs/2606.11841v1)**  
  Authors: Mingzhe Lyu, Jinqiang Cui, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11841v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, gaussian splatting, mapping, dynamic  
- **[Seeing What Matters: Perceptual Wrapper with Common Randomness for 3D Gaussian Splatting](https://arxiv.org/abs/2606.11782v1)**  
  Authors: He-Bi Yang, Jing-Zhong Chen, Yen-Kuan Ho, Sang NguyenQuang, Fan-Yi Hsu, Yun-Yu Lee, Jui-Chiu Chiang, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11782v1.pdf)  
  Keywords: lightweight, 3d gaussian, real-time rendering, ar, gaussian splatting  
- **[A Scalable PyTorch Abstraction for Multi-GPU Gaussian Splatting](https://arxiv.org/abs/2606.11390v1)**  
  Authors: Matthew Cong, Francis Williams, Jonathan Swartz, Mark Harris, Sanja Fidler, Ken Museth  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11390v1.pdf)  
  Keywords: ar, gaussian splatting  
- **[WorldOlympiad: Can Your World Model Survive a Triathlon?](https://arxiv.org/abs/2606.11129v1)**  
  Authors: Yuke Zhao, Wangbo Zhao, Weijie Wang, Zeyu Zhang, Dakai An, Akide Liu, Yinghao Yu, Jiasheng Tang, Fan Wang, Wei Wang, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11129v1.pdf)  
  Keywords: geometry, robotics, ar, gaussian splatting, segmentation, dynamic, semantic, motion  
- **[ManiSplat: Manipulation Trajectory Synthesis from Monocular Video via Decoupled 3D Gaussian Splatting](https://arxiv.org/abs/2606.10645v1)**  
  Authors: Wenhao Hu, Haonan Zhou, Liu Liu, Yun Du, Xinjie Wang, Ziang Li, Zhizhong Su, Gaoang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.10645v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, gaussian splatting, high-fidelity, dynamic, motion  
- **[GaussTrace: Provenance Analysis of 3D Gaussian Splatting Models with Evidence-based LLM Reasoning](https://arxiv.org/abs/2606.10612v1)**  
  Authors: Haoliang Han, Ziyuan Luo, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.10612v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://haolianghan.github.io/GaussTrace.)  
  Keywords: ar, gaussian splatting, 3d gaussian, high-fidelity  
- **[ABot-Earth 0.5: Generative 3D Earth Model](https://arxiv.org/abs/2606.09967v1)**  
  Authors: Ming Qian, Tianjian Ouyang, Mingchao Sun, Zijian Wang, Jincheng Xiong, Jiarong Han, Yongchang Zhang, Jiawei Zhang, Xu Wang, Yu Liu, Luyang Tang, Fei Yu, Zengye Ge, Mengmeng Du, Yuan Liu, Nianfei Fan, Song Wang, Yingliang Peng, Chunxue Jia, Yang Liu, Shiying Zeng, Haozhe Shi, Junnan Lai, Hongyu Pan, Zheng Wu, Ning Guo, Mu Xu, Hang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09967v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, ar, gaussian splatting, high-fidelity  
- **[REFINE: Super-efficient 3D Gaussian Splatting Pruning via Rendering-Free Primitive Importance](https://arxiv.org/abs/2606.09074v1)**  
  Authors: Zhang Chen, Shuai Wan, Mengting Yu, Fuzheng Yang, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09074v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity  

### Avatar Generation

*Showing the latest 50 out of 337 papers*

- **[Flex4DHuman: Flexible Multi-view Video Diffusion for 4D Human Reconstruction](https://arxiv.org/abs/2606.13655v1)**  
  Authors: Jen-Hao Cheng, Yipeng Wang, Hao Zhang, Gengshan Yang, Jenq-Neng Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.13655v1.pdf)  
  Keywords: 4d, geometry, human, vr, ar, gaussian splatting, dynamic  
- **[REFINE: Super-efficient 3D Gaussian Splatting Pruning via Rendering-Free Primitive Importance](https://arxiv.org/abs/2606.09074v1)**  
  Authors: Zhang Chen, Shuai Wan, Mengting Yu, Fuzheng Yang, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09074v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity  
- **[RigPAPR: Rig-Based Animation of Static Neural Point Clouds from a Fixed-Viewpoint Video](https://arxiv.org/abs/2606.06685v1)**  
  Authors: Shichong Peng, Yanshu Zhang, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.06685v1.pdf)  
  Keywords: ar, animation, face  
- **[Geometry Gaussians: Decoupling Appearance and Geometry in Gaussian Splatting](https://arxiv.org/abs/2606.05124v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05124v1.pdf)  
  Keywords: geometry, 3d gaussian, face, ar, gaussian splatting  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: 3d gaussian, efficient, head, ar, gaussian splatting, mapping  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: 3d gaussian, avatar, human, compact, ar, gaussian splatting, high-fidelity, dynamic  
- **[Characterizing Detectability in 3DGS Poisoning: A Stage-wise Benchmark](https://arxiv.org/abs/2606.03499v1)**  
  Authors: Quoc-Anh Bui-Huynh, Thanh Duc Ngo, Xue Geng, Kaixin Xu, Wang Zhe, Xulei Yang, Ngai-Man Cheung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03499v1.pdf)  
  Keywords: geometry, 3d gaussian, face, ar, gaussian splatting, dynamic  
- **[PersistGS: Differentiable Physics for Object Permanence in 4D Gaussian Splatting](https://arxiv.org/abs/2606.03479v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03479v1.pdf)  
  Keywords: 4d, 3d gaussian, ar, gaussian splatting, body, dynamic  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity, dynamic  
- **[VEDAL: Variational Error-Driven Asynchronous Learning for 3D Gaussian Splatting Pruning](https://arxiv.org/abs/2606.02346v1)**  
  Authors: Aoduo Li, Jiancheng Li, Huan Ye, Hongjian Xu, Shiting Wu, Xiujun Zhang, Zimeng Li, Xuhang Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02346v1.pdf)  
  Keywords: 3d gaussian, real-time rendering, head, nerf, gaussian splatting, ar, compression  

### Dynamic Scene

*Showing the latest 50 out of 385 papers*

- **[Flex4DHuman: Flexible Multi-view Video Diffusion for 4D Human Reconstruction](https://arxiv.org/abs/2606.13655v1)**  
  Authors: Jen-Hao Cheng, Yipeng Wang, Hao Zhang, Gengshan Yang, Jenq-Neng Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.13655v1.pdf)  
  Keywords: 4d, geometry, human, vr, ar, gaussian splatting, dynamic  
- **[Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting](https://arxiv.org/abs/2606.11841v1)**  
  Authors: Mingzhe Lyu, Jinqiang Cui, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11841v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, gaussian splatting, mapping, dynamic  
- **[WorldOlympiad: Can Your World Model Survive a Triathlon?](https://arxiv.org/abs/2606.11129v1)**  
  Authors: Yuke Zhao, Wangbo Zhao, Weijie Wang, Zeyu Zhang, Dakai An, Akide Liu, Yinghao Yu, Jiasheng Tang, Fan Wang, Wei Wang, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11129v1.pdf)  
  Keywords: geometry, robotics, ar, gaussian splatting, segmentation, dynamic, semantic, motion  
- **[ManiSplat: Manipulation Trajectory Synthesis from Monocular Video via Decoupled 3D Gaussian Splatting](https://arxiv.org/abs/2606.10645v1)**  
  Authors: Wenhao Hu, Haonan Zhou, Liu Liu, Yun Du, Xinjie Wang, Ziang Li, Zhizhong Su, Gaoang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.10645v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, gaussian splatting, high-fidelity, dynamic, motion  
- **[QuadVerse: An Integrated Framework Aligning Visual-Physical Reality for Quadruped Simulation](https://arxiv.org/abs/2606.07118v2)**  
  Authors: Yuxiang Chen, Yuanhao Wang, Ziheng Zhang, Meng Zhang, Yu Liu, Yufei Jia, Tiancai Wang, Erjin Zhou, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07118v2.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, tracking, dynamic, semantic, motion  
- **[RigPAPR: Rig-Based Animation of Static Neural Point Clouds from a Fixed-Viewpoint Video](https://arxiv.org/abs/2606.06685v1)**  
  Authors: Shichong Peng, Yanshu Zhang, Ke Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.06685v1.pdf)  
  Keywords: ar, animation, face  
- **[Liquid Neural Networks as a Drop-in Continuous-Time Deformation Field for Dynamic 3D Gaussian Splatting](https://arxiv.org/abs/2606.07670v1)**  
  Authors: Mingzhao Li, Arghya Pal, Guan Yuan Tan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07670v1.pdf)  
  Keywords: 3d gaussian, deformation, nerf, gaussian splatting, ar, dynamic, motion  
- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: 3d gaussian, fast, efficient, ar, gaussian splatting, acceleration, compression, dynamic  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 4d, 3d gaussian, 3d reconstruction, neural rendering, compact, autonomous driving, survey, vr, ar, gaussian splatting, recognition, medical, motion  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: geometry, 3d gaussian, efficient, ar, gaussian splatting, high-fidelity, compression, dynamic  

### Few-shot

*Showing the latest 50 out of 78 papers*

- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: 3d gaussian, efficient, sparse-view, nerf, gaussian splatting, high-fidelity, outdoor, ar  
- **[BEAST3D: Animal behavioral analysis and neural encoding from multi-view video via Gaussian splatting](https://arxiv.org/abs/2606.02937v1)**  
  Authors: Yanchen Wang, Lenny Aharon, Wangshu Zhu, Kyle Daruwalla, Linghua Zhang, Jiaru Zou, Selmaan Chettih, Helen Hou, Liam Paninski, Matthew R Whiteway  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02937v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, sparse-view, ar, gaussian splatting  
- **[Fast and Lightweight Novel View Synthesis with Differentiable Multiplane Image](https://arxiv.org/abs/2606.02068v1)**  
  Authors: Kaidi Zhang, Guanxu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.02068v1.pdf)  
  Keywords: lightweight, 3d gaussian, fast, efficient, compact, sparse-view, nerf, gaussian splatting, ar  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: 3d gaussian, efficient, sparse-view, nerf, gaussian splatting, high-fidelity, ar, motion  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: geometry, 3d gaussian, relighting, fast, lighting, sparse-view, relightable, ar, gaussian splatting, high-fidelity, illumination  
- **[ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views](https://arxiv.org/abs/2605.24304v1)**  
  Authors: Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24304v1.pdf)  
  Keywords: geometry, 3d gaussian, fast, sparse-view, nerf, gaussian splatting, ar, motion  
- **[TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting](https://arxiv.org/abs/2605.22069v2)**  
  Authors: Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22069v2.pdf)  
  Keywords: 3d gaussian, fast, sparse-view, deformation, nerf, gaussian splatting, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: 3d gaussian, fast, autonomous driving, lighting, ar, gaussian splatting, high-fidelity, illumination, outdoor, mapping, dynamic, sparse view  
- **[PanoPlane: Plane-Aware Panoramic Completion for Sparse-View Indoor 3D Gaussian Splatting](https://arxiv.org/abs/2605.14135v1)**  
  Authors: Adil Qureshi, Dongki Jung, Jaehoon Choi, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.14135v1.pdf)  
  Keywords: geometry, 3d gaussian, sparse-view, face, ar, gaussian splatting, high-fidelity  
- **[GeoQuery: Geometry-Query Diffusion for Sparse-View Reconstruction](https://arxiv.org/abs/2605.12399v1)**  
  Authors: Xiao Cao, Yuze Li, Youmin Zhang, Jiayu Song, Cheng Yan, Wen Li, Lixin Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.12399v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, sparse-view, ar, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 394 papers*

- **[Flex4DHuman: Flexible Multi-view Video Diffusion for 4D Human Reconstruction](https://arxiv.org/abs/2606.13655v1)**  
  Authors: Jen-Hao Cheng, Yipeng Wang, Hao Zhang, Gengshan Yang, Jenq-Neng Hwang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.13655v1.pdf)  
  Keywords: 4d, geometry, human, vr, ar, gaussian splatting, dynamic  
- **[Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting](https://arxiv.org/abs/2606.11841v1)**  
  Authors: Mingzhe Lyu, Jinqiang Cui, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11841v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, gaussian splatting, mapping, dynamic  
- **[WorldOlympiad: Can Your World Model Survive a Triathlon?](https://arxiv.org/abs/2606.11129v1)**  
  Authors: Yuke Zhao, Wangbo Zhao, Weijie Wang, Zeyu Zhang, Dakai An, Akide Liu, Yinghao Yu, Jiasheng Tang, Fan Wang, Wei Wang, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11129v1.pdf)  
  Keywords: geometry, robotics, ar, gaussian splatting, segmentation, dynamic, semantic, motion  
- **[ABot-Earth 0.5: Generative 3D Earth Model](https://arxiv.org/abs/2606.09967v1)**  
  Authors: Ming Qian, Tianjian Ouyang, Mingchao Sun, Zijian Wang, Jincheng Xiong, Jiarong Han, Yongchang Zhang, Jiawei Zhang, Xu Wang, Yu Liu, Luyang Tang, Fei Yu, Zengye Ge, Mengmeng Du, Yuan Liu, Nianfei Fan, Song Wang, Yingliang Peng, Chunxue Jia, Yang Liu, Shiying Zeng, Haozhe Shi, Junnan Lai, Hongyu Pan, Zheng Wu, Ning Guo, Mu Xu, Hang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09967v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, ar, gaussian splatting, high-fidelity  
- **[REFINE: Super-efficient 3D Gaussian Splatting Pruning via Rendering-Free Primitive Importance](https://arxiv.org/abs/2606.09074v1)**  
  Authors: Zhang Chen, Shuai Wan, Mengting Yu, Fuzheng Yang, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09074v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity  
- **[QuadVerse: An Integrated Framework Aligning Visual-Physical Reality for Quadruped Simulation](https://arxiv.org/abs/2606.07118v2)**  
  Authors: Yuxiang Chen, Yuanhao Wang, Ziheng Zhang, Meng Zhang, Yu Liu, Yufei Jia, Tiancai Wang, Erjin Zhou, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07118v2.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, tracking, dynamic, semantic, motion  
- **[RPC-GS: Gaussian Splatting with native RPC Rendering for Satellite Imagery](https://arxiv.org/abs/2606.06690v1)**  
  Authors: Valentin Wagner, Sebastian Bullinger, Christoph Bodensteiner, Michael Arens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.06690v1.pdf)  
  Keywords: mapping, gaussian splatting, geometry, ar  
- **[Geometry Gaussians: Decoupling Appearance and Geometry in Gaussian Splatting](https://arxiv.org/abs/2606.05124v1)**  
  Authors: Hongyu Zhou, Zorah Lähner  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05124v1.pdf)  
  Keywords: geometry, 3d gaussian, face, ar, gaussian splatting  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 4d, 3d gaussian, 3d reconstruction, neural rendering, compact, autonomous driving, survey, vr, ar, gaussian splatting, recognition, medical, motion  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: geometry, 3d gaussian, efficient, ar, gaussian splatting, high-fidelity, compression, dynamic  

### Large Scene

- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: 3d gaussian, efficient, sparse-view, nerf, gaussian splatting, high-fidelity, outdoor, ar  
- **[City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images](https://arxiv.org/abs/2605.30310v1)**  
  Authors: Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30310v1.pdf)  
  Keywords: geometry, 3d reconstruction, large scene, face, nerf, gaussian splatting, high-fidelity, ar, urban scene  
- **[Feed-Forward Gaussian Splatting from Sparse Aerial Views](https://arxiv.org/abs/2605.19949v1)**  
  Authors: Dongli Wu, Zhuoxiao Li, Tongyan Hua, Yinrui Ren, Xiaobao Wei, Rongjun Qin, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19949v1.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, urban scene  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, outdoor, ar  
- **[P2GS: Physical Prior-guided Gaussian Splatting for Photometrically Consistent Urban Reconstruction](https://arxiv.org/abs/2605.16925v1)**  
  Authors: Kota Shimomura, Hidehisa Arai, Tsubasa Takahashi, Takayoshi Yamashita, Hironobu Fujiyoshi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.16925v1.pdf)  
  Keywords: 3d gaussian, fast, autonomous driving, lighting, ar, gaussian splatting, high-fidelity, illumination, outdoor, mapping, dynamic, sparse view  
- **[FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting](https://arxiv.org/abs/2605.00177v1)**  
  Authors: Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.00177v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pku-vcl-geometry.github.io/FieryGS/.)  
  Keywords: geometry, 3d gaussian, efficient, face, ar, gaussian splatting, high-fidelity, outdoor, dynamic  
- **[EnerGS: Energy-Based Gaussian Splatting with Partial Geometric Priors](https://arxiv.org/abs/2604.26238v1)**  
  Authors: Rui Song, Tianhui Cai, Markus Gross, Yun Zhang, Walter Zimmer, Zhiyu Huang, Olaf Wysocki, Jiaqi Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.26238v1.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, outdoor  
- **[DF3DV-1K: A Large-Scale Dataset and Benchmark for Distractor-Free Novel View Synthesis](https://arxiv.org/abs/2604.13416v1)**  
  Authors: Cheng-You Lu, Yi-Shan Hung, Wei-Ling Chi, Hao-Ping Wang, Charlie Li-Ting Tsai, Yu-Cheng Chang, Yu-Lun Liu, Thomas Do, Chin-Teng Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.13416v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, outdoor  
- **[RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM](https://arxiv.org/abs/2604.12942v2)**  
  Authors: Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E. H. Tay, Marcelo H. Ang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.12942v2.pdf)  
  Keywords: 3d gaussian, slam, ar, gaussian splatting, outdoor, mapping, localization  
- **[GS4City: Hierarchical Semantic Gaussian Splatting via City-Model Priors](https://arxiv.org/abs/2604.11401v1)**  
  Authors: Qilin Zhang, Jinyu Zhu, Olaf Wysocki, Benjamin Busam, Boris Jutzi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11401v1.pdf)  
  Keywords: geometry, 3d gaussian, understanding, compact, ar, gaussian splatting, segmentation, semantic, urban scene  

### Model Compression

*Showing the latest 50 out of 427 papers*

- **[Seeing What Matters: Perceptual Wrapper with Common Randomness for 3D Gaussian Splatting](https://arxiv.org/abs/2606.11782v1)**  
  Authors: He-Bi Yang, Jing-Zhong Chen, Yen-Kuan Ho, Sang NguyenQuang, Fan-Yi Hsu, Yun-Yu Lee, Jui-Chiu Chiang, Wen-Hsiao Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11782v1.pdf)  
  Keywords: lightweight, 3d gaussian, real-time rendering, ar, gaussian splatting  
- **[REFINE: Super-efficient 3D Gaussian Splatting Pruning via Rendering-Free Primitive Importance](https://arxiv.org/abs/2606.09074v1)**  
  Authors: Zhang Chen, Shuai Wan, Mengting Yu, Fuzheng Yang, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09074v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity  
- **[MaterialClusterGS: Palette-Based Material Decomposition and Physically-Based Relighting with 2D Gaussian Splatting](https://arxiv.org/abs/2606.09018v1)**  
  Authors: Hao Zhang, Ang Li, Boyan Du, Junke Zhu, Fei Zhu, Meng Gai, Zhangjin Huang, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09018v1.pdf)  
  Keywords: shadow, relighting, compact, lighting, ar, gaussian splatting, illumination  
- **[LEGS: Laplacian-Enhanced Gaussian Splatting with a Nonlinear Weighted Loss](https://arxiv.org/abs/2606.07932v1)**  
  Authors: Yongfei Guo, Qizhou Huo, Xuan Sun, Yuanhao Gong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07932v1.pdf)  
  Keywords: 3d gaussian, fast, efficient, vr, nerf, gaussian splatting, ar  
- **[GS-NFS: Bandwidth-adaptive Streaming of Dynamic Gaussian Splats and Point Clouds](https://arxiv.org/abs/2606.05650v1)**  
  Authors: Rajrup Ghosh, Haodong Wang, Haoran Hong, Eduardo Pavez, Amartya Chaudhuri, Weiwu Pang, Harsha V. Madhyastha, Antonio Ortega, Ramesh Govindan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05650v1.pdf)  
  Keywords: 3d gaussian, fast, efficient, ar, gaussian splatting, acceleration, compression, dynamic  
- **[ZipSplat: Fewer Gaussians, Better Splats](https://arxiv.org/abs/2606.05102v1)**  
  Authors: Alexander Veicht, Sunghwan Hong, Dániel Baráth, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.05102v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://veichta.com/zipsplat}{https://veichta.com/zipsplat}}$.)  
  Keywords: lightweight, 3d gaussian, compact, nerf, gaussian splatting, ar  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 4d, 3d gaussian, 3d reconstruction, neural rendering, compact, autonomous driving, survey, vr, ar, gaussian splatting, recognition, medical, motion  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: 3d gaussian, efficient, head, ar, gaussian splatting, mapping  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: geometry, 3d gaussian, efficient, ar, gaussian splatting, high-fidelity, compression, dynamic  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: understanding, 3d gaussian, fast, efficient, compact, ar, gaussian splatting, segmentation, semantic  

### Quality Enhancement

*Showing the latest 50 out of 244 papers*

- **[ManiSplat: Manipulation Trajectory Synthesis from Monocular Video via Decoupled 3D Gaussian Splatting](https://arxiv.org/abs/2606.10645v1)**  
  Authors: Wenhao Hu, Haonan Zhou, Liu Liu, Yun Du, Xinjie Wang, Ziang Li, Zhizhong Su, Gaoang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.10645v1.pdf)  
  Keywords: robotics, 3d gaussian, ar, gaussian splatting, high-fidelity, dynamic, motion  
- **[GaussTrace: Provenance Analysis of 3D Gaussian Splatting Models with Evidence-based LLM Reasoning](https://arxiv.org/abs/2606.10612v1)**  
  Authors: Haoliang Han, Ziyuan Luo, Renjie Wan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.10612v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://haolianghan.github.io/GaussTrace.)  
  Keywords: ar, gaussian splatting, 3d gaussian, high-fidelity  
- **[ABot-Earth 0.5: Generative 3D Earth Model](https://arxiv.org/abs/2606.09967v1)**  
  Authors: Ming Qian, Tianjian Ouyang, Mingchao Sun, Zijian Wang, Jincheng Xiong, Jiarong Han, Yongchang Zhang, Jiawei Zhang, Xu Wang, Yu Liu, Luyang Tang, Fei Yu, Zengye Ge, Mengmeng Du, Yuan Liu, Nianfei Fan, Song Wang, Yingliang Peng, Chunxue Jia, Yang Liu, Shiying Zeng, Haozhe Shi, Junnan Lai, Hongyu Pan, Zheng Wu, Ning Guo, Mu Xu, Hang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09967v1.pdf)  
  Keywords: geometry, 3d gaussian, 3d reconstruction, ar, gaussian splatting, high-fidelity  
- **[REFINE: Super-efficient 3D Gaussian Splatting Pruning via Rendering-Free Primitive Importance](https://arxiv.org/abs/2606.09074v1)**  
  Authors: Zhang Chen, Shuai Wan, Mengting Yu, Fuzheng Yang, Junhui Hou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09074v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity  
- **[SparseStreet: Sparse Gaussian Splatting for Real-Time Street Scene Simulation](https://arxiv.org/abs/2606.03909v1)**  
  Authors: Qingpo Wuwu, Xiaobao Wei, Peng Chen, Nan Huang, Zhongyu Zhao, Hao Wang, Ming Lu, Ningning Ma, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03909v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sparsestreet.github.io/.)  
  Keywords: geometry, 3d gaussian, efficient, ar, gaussian splatting, high-fidelity, compression, dynamic  
- **[GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation](https://arxiv.org/abs/2606.03682v1)**  
  Authors: Xinhai Li, Xiaotao Zhang, Yuehao Huang, Jiankun Dong, Tianhang Wang, Sunyao Zhou, Yunzi Wu, Chengnuo Sun, Yunfei Ge, Qizhen Weng, Chi Zhang, Chenjia Bai, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03682v1.pdf)  
  Keywords: 3d gaussian, avatar, human, compact, ar, gaussian splatting, high-fidelity, dynamic  
- **[FreeStreamGS: Online Feed-forward 3D Gaussian Splatting from Unposed Streaming Inputs](https://arxiv.org/abs/2606.03254v1)**  
  Authors: Ruiyang Chen, Feiran Li, Chu Zhou, Zonglin Li, Zhanyu Ma, Heng Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03254v1.pdf)  
  Keywords: geometry, 3d gaussian, efficient, head, ar, gaussian splatting, high-fidelity, dynamic  
- **[KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis](https://arxiv.org/abs/2606.03120v1)**  
  Authors: Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03120v1.pdf)  
  Keywords: 3d gaussian, efficient, sparse-view, nerf, gaussian splatting, high-fidelity, outdoor, ar  
- **[Splatshot: 3D Face Avatar Generation from a Single Unconstrained Photo](https://arxiv.org/abs/2606.01493v1)**  
  Authors: Hao Liang, Zhixuan Ge, Soumendu Majee, Joanna Li, Ashok Veeraraghavan, Guha Balakrishnan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01493v1.pdf)  
  Keywords: 3d gaussian, avatar, face, ar, gaussian splatting, high-fidelity  
- **[DeblurNVS: Geometric Latent Diffusion for Novel View Synthesis from Sparse Motion-Blurred Images](https://arxiv.org/abs/2606.01315v1)**  
  Authors: Changyue Shi, Wangbo Yu, Chaoran Feng, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01315v1.pdf)  
  Keywords: 3d gaussian, efficient, sparse-view, nerf, gaussian splatting, high-fidelity, ar, motion  

### Ray Tracing

- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: geometry, 3d gaussian, ray tracing, efficient, reflection, ar, gaussian splatting, segmentation, semantic  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, shadow, fast, global illumination, face, ar, gaussian splatting, illumination  
- **[Underwater360: Reconstructing Underwater Scenes from Panoramic Images with Omnidirectional Gaussian Splatting](https://arxiv.org/abs/2605.26447v1)**  
  Authors: Jiangbei Hu, Weichao Song, Shibo Yu, Mohan Wang, Zihan Yi, Rui Wu, Mingkang Xiang, Na Lei, Shengfa Wang, Zhongxuan Luo, Ying He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.26447v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, ray casting  
- **[Differentiable Ray Tracing with Gaussians for Unified Radio Propagation Simulation and View Synthesis](https://arxiv.org/abs/2605.07781v1)**  
  Authors: Niklas Vaara, Lam Huynh, Pekka Sangi, Miguel Bordallo López, Janne Heikkilä  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.07781v1.pdf)  
  Keywords: geometry, ray tracing, 3d gaussian, ar, gaussian splatting, high-fidelity  
- **[ViserDex: Visual Sim-to-Real for Robust Dexterous In-hand Reorientation](https://arxiv.org/abs/2604.11138v1)**  
  Authors: Arjun Bhardwaj, Maximum Wilder-Smith, Mayank Mittal, Vaishakh Patil, Marco Hutter  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11138v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://rffr.leggedrobotics.com/works/viserdex/)  
  Keywords: robotics, 3d gaussian, ray tracing, efficient, lighting, ar, gaussian splatting, tracking, dynamic, semantic  
- **[RT-GS: Gaussian Splatting with Reflection and Transmittance Primitives](https://arxiv.org/abs/2604.00509v1)**  
  Authors: Kunnong Zeng, Chensheng Peng, Yichen Xie, Masayoshi Tomizuka, Cem Yuksel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.00509v1.pdf)  
  Keywords: ray tracing, reflection, face, ar, gaussian splatting  
- **[GS3LAM: Gaussian Semantic Splatting SLAM](https://arxiv.org/abs/2603.27781v1)**  
  Authors: Linfei Li, Lin Zhang, Zhong Wang, Ying Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.27781v1.pdf)  
  Keywords: 3d gaussian, ray tracing, efficient, slam, face, ar, gaussian splatting, tracking, mapping, localization, semantic  
- **[Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting](https://arxiv.org/abs/2603.23637v2)**  
  Authors: Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.23637v2.pdf)  
  Keywords: 3d gaussian, shadow, ray tracing, reflection, relightable, ar, gaussian splatting, mapping  
- **[RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing](https://arxiv.org/abs/2603.21695v1)**  
  Authors: Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.21695v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yimgshao.github.io/refracgs/.)  
  Keywords: geometry, 3d gaussian, ray tracing, real-time rendering, fast, efficient, face, nerf, gaussian splatting, high-fidelity, ar  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: 3d gaussian, ray tracing, survey, ar, gaussian splatting, mapping  

### Relighting

*Showing the latest 50 out of 132 papers*

- **[Wild3R: Feed-Forward 3D Gaussian Splatting from Unconstrained Sparse Photo Collection](https://arxiv.org/abs/2606.11894v2)**  
  Authors: Yuto Furutani, Takashi Otonari, Kaede Shiohara, Toshihiko Yamasaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11894v2.pdf)  
  Keywords: 3d gaussian, lighting, ar, gaussian splatting, illumination  
- **[MaterialClusterGS: Palette-Based Material Decomposition and Physically-Based Relighting with 2D Gaussian Splatting](https://arxiv.org/abs/2606.09018v1)**  
  Authors: Hao Zhang, Ang Li, Boyan Du, Junke Zhu, Fei Zhu, Meng Gai, Zhangjin Huang, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.09018v1.pdf)  
  Keywords: shadow, relighting, compact, lighting, ar, gaussian splatting, illumination  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: geometry, 3d gaussian, ray tracing, efficient, reflection, ar, gaussian splatting, segmentation, semantic  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: 3d gaussian, shadow, fast, global illumination, face, ar, gaussian splatting, illumination  
- **[F-RNG: Feed-Forward Relightable Neural Gaussians](https://arxiv.org/abs/2605.25975v2)**  
  Authors: Guangming Fu, Jiahui Fan, Jian Yang, Miloš Hašan, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.25975v2.pdf)  
  Keywords: geometry, 3d gaussian, relighting, fast, lighting, sparse-view, relightable, ar, gaussian splatting, high-fidelity, illumination  
- **[COSY: Compositional 3DGS Synthesis for Disentangled Human Head Editing](https://arxiv.org/abs/2605.24114v1)**  
  Authors: Florian Barthel, Shalini De Mello, Koki Nagano, Wieland Morgenstern, Anna Hilsmann, Peter Eisert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.24114v1.pdf)  
  Keywords: 3d gaussian, human, head, lighting, ar, gaussian splatting, segmentation, semantic  
- **[SpaceDG: Benchmarking Spatial Intelligence under Visual Degradation](https://arxiv.org/abs/2605.22536v1)**  
  Authors: Xiaolong Zhou, Yifei Liu, Ziyang Gong, Jiarui Li, Qiyue Zhao, Muyao Niu, Yuanyuan Gao, Le Ma, Xue Yang, Hongjie Zhang, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.22536v1.pdf)  
  Keywords: understanding, 3d gaussian, human, lighting, ar, gaussian splatting, compression, motion  
- **[A Geometric Algebra-Informed 3DGS Framework for Wireless Channel Prediction](https://arxiv.org/abs/2605.19065v3)**  
  Authors: Jingzhou Shen, Tianya Zhao, Xuyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19065v3.pdf)  
  Keywords: reflection, gaussian splatting, 3d gaussian, ar  
- **[RT-Splatting: Joint Reflection-Transmission Modeling with Gaussian Splatting](https://arxiv.org/abs/2605.18263v1)**  
  Authors: Ji Shi, Xianghua Ying, Bowei Xing, Ruohao Guo, Wenzhen Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.18263v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sjj118.github.io/RT-Splatting.)  
  Keywords: 3d gaussian, real-time rendering, reflection, face, ar, gaussian splatting, high-fidelity  
- **[A Single Atlas is All You Need: Decoder-Side Gaussian Splatting for Immersive Video](https://arxiv.org/abs/2605.17002v1)**  
  Authors: Dawid Mieloch, Stuart Perry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.17002v1.pdf)  
  Keywords: 3d gaussian, reflection, ar, gaussian splatting, compression  

### SLAM

*Showing the latest 50 out of 149 papers*

- **[Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting](https://arxiv.org/abs/2606.11841v1)**  
  Authors: Mingzhe Lyu, Jinqiang Cui, Hong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11841v1.pdf)  
  Keywords: 3d gaussian, 3d reconstruction, ar, gaussian splatting, mapping, dynamic  
- **[QuadVerse: An Integrated Framework Aligning Visual-Physical Reality for Quadruped Simulation](https://arxiv.org/abs/2606.07118v2)**  
  Authors: Yuxiang Chen, Yuanhao Wang, Ziheng Zhang, Meng Zhang, Yu Liu, Yufei Jia, Tiancai Wang, Erjin Zhou, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07118v2.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, tracking, dynamic, semantic, motion  
- **[RPC-GS: Gaussian Splatting with native RPC Rendering for Satellite Imagery](https://arxiv.org/abs/2606.06690v1)**  
  Authors: Valentin Wagner, Sebastian Bullinger, Christoph Bodensteiner, Michael Arens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.06690v1.pdf)  
  Keywords: mapping, gaussian splatting, geometry, ar  
- **[Multi-Agent Next-Best-View Optimization for Risk-Averse Planning](https://arxiv.org/abs/2606.04158v1)**  
  Authors: Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04158v1.pdf)  
  Keywords: 3d gaussian, efficient, head, ar, gaussian splatting, mapping  
- **[Real-Time Physics Simulation with Dynamic Mesh-Gaussian Reconstructions](https://arxiv.org/abs/2606.00444v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00444v1.pdf)  
  Keywords: efficient, 3d reconstruction, ar, gaussian splatting, tracking, dynamic  
- **[Triangle Splatting SLAM](https://arxiv.org/abs/2605.31419v2)**  
  Authors: Nicholas Fry, Eric Dexheimer, Kirill Mazur, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.31419v2.pdf)  
  Keywords: geometry, 3d gaussian, slam, deformation, ar, gaussian splatting, tracking, mapping  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: geometry, survey, animation, ar, gaussian splatting, mapping  
- **[Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field](https://arxiv.org/abs/2605.30342v1)**  
  Authors: Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.30342v1.pdf)  
  Keywords: 3d gaussian, efficient, ar, gaussian splatting, mapping  
- **[Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments](https://arxiv.org/abs/2605.21935v1)**  
  Authors: Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.21935v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziya-jiang.github.io/MIF-homepage/)  
  Keywords: geometry, 3d gaussian, human, ar, gaussian splatting, mapping, dynamic, semantic, motion  
- **[Cross-View Splatter: Feed-Forward View Synthesis with Georeferenced Images](https://arxiv.org/abs/2605.19656v1)**  
  Authors: Matias Turkulainen, Akshay Krishnan, Filippo Aleotti, Mohamed Sayed, Guillermo Garcia-Hernando, Juho Kannala, Arno Solin, Gabriel Brostow, Daniyar Turmukhambetov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2605.19656v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nianticspatial.github.io/cross-view-splatter/.)  
  Keywords: mapping, outdoor, ar  

### Scene Understanding

*Showing the latest 50 out of 226 papers*

- **[WorldOlympiad: Can Your World Model Survive a Triathlon?](https://arxiv.org/abs/2606.11129v1)**  
  Authors: Yuke Zhao, Wangbo Zhao, Weijie Wang, Zeyu Zhang, Dakai An, Akide Liu, Yinghao Yu, Jiasheng Tang, Fan Wang, Wei Wang, Bohan Zhuang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.11129v1.pdf)  
  Keywords: geometry, robotics, ar, gaussian splatting, segmentation, dynamic, semantic, motion  
- **[QuadVerse: An Integrated Framework Aligning Visual-Physical Reality for Quadruped Simulation](https://arxiv.org/abs/2606.07118v2)**  
  Authors: Yuxiang Chen, Yuanhao Wang, Ziheng Zhang, Meng Zhang, Yu Liu, Yufei Jia, Tiancai Wang, Erjin Zhou, Jin Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.07118v2.pdf)  
  Keywords: geometry, 3d gaussian, ar, gaussian splatting, tracking, dynamic, semantic, motion  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: 4d, 3d gaussian, 3d reconstruction, neural rendering, compact, autonomous driving, survey, vr, ar, gaussian splatting, recognition, medical, motion  
- **[MLP Splatting: Object-Centric Neural Fields](https://arxiv.org/abs/2606.03877v1)**  
  Authors: Shinjeong Kim, Yuzhou Cheng, Xin Kong, Paul H. J. Kelly, Andrew J. Davison  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03877v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shinjeongkim.com/mlp-splatting)  
  Keywords: understanding, 3d gaussian, fast, efficient, compact, ar, gaussian splatting, segmentation, semantic  
- **[UnsOcc: 3D Semantic Occupancy Prediction in Unstructured Scene via Rendering Fusion](https://arxiv.org/abs/2606.03581v1)**  
  Authors: Ye Wu, Ruiqi Song, Baiyong Ding, Nanxin Zeng, Junjie Cheng, Yunfeng Ai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.03581v1.pdf)  
  Keywords: autonomous driving, ar, gaussian splatting, segmentation, semantic  
- **[$\text{VG}^2$GT: Voxel-Gaussian Splatting Visual Geometry Grounded Transformer](https://arxiv.org/abs/2606.01573v2)**  
  Authors: Yibin Zhao, Yihan Pan, Jun Nan, Wenli Yang, Liwei Chen, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01573v2.pdf)  
  Keywords: understanding, geometry, 3d reconstruction, ar, gaussian splatting  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: geometry, 3d gaussian, ray tracing, efficient, reflection, ar, gaussian splatting, segmentation, semantic  
- **[Beyond Static Gaussians: An Empirical Investigation of Architectural Paradigms for Dynamic 3D Scene Reconstruction](https://arxiv.org/abs/2606.00452v1)**  
  Authors: Adrian Ramlal, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00452v1.pdf)  
  Keywords: 4d, understanding, 3d gaussian, compact, head, deformation, nerf, gaussian splatting, ar, dynamic  
- **[Optimizing 3D Gaussian Splatting via Point Cloud Upsampling](https://arxiv.org/abs/2606.00450v1)**  
  Authors: Adrian Ramlal, Yan Song Hu, John S. Zelek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00450v1.pdf)  
  Keywords: geometry, 3d gaussian, understanding, face, nerf, gaussian splatting, ar, motion  
- **[GeoSAM-3D: Geodesic Prompt Propagation for Open-Vocabulary 3D Scene Segmentation from Monocular Video](https://arxiv.org/abs/2606.00447v1)**  
  Authors: Arun Sharma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00447v1.pdf)  
  Keywords: 3d gaussian, head, face, ar, gaussian splatting, segmentation  



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