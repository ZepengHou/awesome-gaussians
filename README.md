# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-12-14 01:03:36

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
- [Acceleration](#acceleration) (247 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (344 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (402 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (84 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (347 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (74 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (399 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (192 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (15 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (123 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (148 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (208 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d reconstruction, survey, ar, dynamic, 3d gaussian, gaussian splatting, compression, compact, efficient, high-fidelity  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: survey, ar, localization, slam, 3d gaussian, gaussian splatting, semantic, mapping, nerf, robotics, understanding  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: survey, ar, localization, slam, 3d gaussian, gaussian splatting, semantic, mapping, efficient, robotics, high-fidelity  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: 4d, fast, survey, ar, 3d gaussian, gaussian splatting, geometry, motion, nerf  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: avatar, 3d reconstruction, survey, ar, animation, 3d gaussian, face, gaussian splatting, efficient, efficient rendering, real-time rendering, lighting  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: lightweight, survey, ar, gaussian splatting, efficient, nerf, human, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: survey, fast, ar, slam, 3d gaussian, gaussian splatting, efficient, nerf, neural rendering, understanding  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: survey, ar, 3d gaussian, gaussian splatting, segmentation, semantic, compact, nerf, lighting, high-fidelity, understanding  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: survey, ar, 3d gaussian, gaussian splatting, semantic, efficient, nerf, robotics, understanding  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: nerf, survey, ar, 3d gaussian, gaussian splatting, human, robotics  

### Acceleration

*Showing the latest 50 out of 247 papers*

- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: avatar, fast, ar, gaussian splatting, tracking, mapping, head  
- **[Long-LRM++: Preserving Fine Details in Feed-Forward Wide-Coverage Reconstruction](https://arxiv.org/abs/2512.10267v1)**  
  Authors: Chen Ziwen, Hao Tan, Peng Wang, Zexiang Xu, Li Fuxin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10267v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, compression, real-time rendering  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[MoRel: Long-Range Flicker-Free 4D Motion Modeling via Anchor Relay-based Bidirectional Blending with Hierarchical Densification](https://arxiv.org/abs/2512.09270v1)**  
  Authors: Sangwoon Kwak, Weeyoung Kwon, Jun Young Jeong, Geonho Kim, Won-Sik Cheong, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09270v1.pdf)  
  Keywords: 4d, ar, dynamic, 3d gaussian, gaussian splatting, deformation, efficient, motion, real-time rendering  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: acceleration, fast, ar, 3d gaussian, gaussian splatting, nerf, face, high-fidelity, reflection  
- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: fast, ar, 3d gaussian, gaussian splatting, compact  
- **[MeshSplatting: Differentiable Rendering with Opaque Meshes](https://arxiv.org/abs/2512.06818v1)**  
  Authors: Jan Held, Sanghyun Son, Renaud Vandeghen, Daniel Rebain, Matheus Gadelha, Yi Zhou, Anthony Cioppa, Ming C. Lin, Marc Van Droogenbroeck, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06818v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://meshsplatting.github.io/.)  
  Keywords: fast, ar, 3d gaussian, face, gaussian splatting, vr, geometry, efficient, nerf, real-time rendering, neural rendering  
- **[EGGS: Exchangeable 2D/3D Gaussian Splatting for Geometry-Appearance Balanced Novel View Synthesis](https://arxiv.org/abs/2512.02932v1)**  
  Authors: Yancheng Zhang, Guangyu Sun, Chen Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02932v1.pdf)  
  Keywords: ar, autonomous driving, dynamic, 3d gaussian, gaussian splatting, vr, geometry, efficient, real-time rendering  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: ar, efficient rendering, 3d gaussian, face, gaussian splatting, geometry, efficient, nerf, real-time rendering, high-fidelity, reflection  
- **[Content-Aware Texturing for Gaussian Splatting](https://arxiv.org/abs/2512.02621v1)**  
  Authors: Panagiotis Papantonakis, Georgios Kopanas, Fredo Durand, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02621v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gs-texturing/)  
  Keywords: 3d reconstruction, ar, gaussian splatting, geometry, mapping, real-time rendering  

### Applications

*Showing the latest 50 out of 995 papers*

- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: avatar, fast, ar, gaussian splatting, tracking, mapping, head  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: ar, deformation, gaussian splatting, mapping, face, high-fidelity  
- **[Neural Hamiltonian Deformation Fields for Dynamic Scene Rendering](https://arxiv.org/abs/2512.10424v1)**  
  Authors: Hai-Long Qin, Sixian Wang, Guo Lu, Jincheng Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10424v1.pdf)  
  Keywords: ar, dynamic, deformation, gaussian splatting, mapping, motion  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, motion, sparse view, high-fidelity  
- **[Physically Aware 360$^\circ$ View Generation from a Single Image using Disentangled Scene Embeddings](https://arxiv.org/abs/2512.10293v1)**  
  Authors: Karthikeya KV, Narendra Bandaru  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10293v1.pdf)  
  Keywords: medical, ar, gaussian splatting, nerf  
- **[Long-LRM++: Preserving Fine Details in Feed-Forward Wide-Coverage Reconstruction](https://arxiv.org/abs/2512.10267v1)**  
  Authors: Chen Ziwen, Hao Tan, Peng Wang, Zexiang Xu, Li Fuxin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10267v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, compression, real-time rendering  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, ar, gaussian splatting, segmentation, geometry, light transport, lighting, sparse-view  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: ar, localization, recognition, 3d gaussian, gaussian splatting, compact, mapping, human  

### Avatar Generation

*Showing the latest 50 out of 344 papers*

- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: avatar, fast, ar, gaussian splatting, tracking, mapping, head  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: ar, deformation, gaussian splatting, mapping, face, high-fidelity  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: ar, localization, recognition, 3d gaussian, gaussian splatting, compact, mapping, human  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: relighting, avatar, ar, relightable, dynamic, 3d gaussian, body, gaussian splatting, deformation, motion, nerf, human, lighting, high-fidelity  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: relighting, avatar, ar, relightable, gaussian splatting, geometry, mapping, efficient, head, lighting  
- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 4d, avatar, lightweight, ar, dynamic, 3d gaussian, gaussian splatting, efficient, neural rendering  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: acceleration, fast, ar, 3d gaussian, gaussian splatting, nerf, face, high-fidelity, reflection  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, deformation, gaussian splatting, face, sparse-view  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: lightweight, ar, 3d gaussian, gaussian splatting, efficient, head, sparse-view  

### Dynamic Scene

*Showing the latest 50 out of 402 papers*

- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: ar, deformation, gaussian splatting, mapping, face, high-fidelity  
- **[Neural Hamiltonian Deformation Fields for Dynamic Scene Rendering](https://arxiv.org/abs/2512.10424v1)**  
  Authors: Hai-Long Qin, Sixian Wang, Guo Lu, Jincheng Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10424v1.pdf)  
  Keywords: ar, dynamic, deformation, gaussian splatting, mapping, motion  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, motion, sparse view, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[ReMoSPLAT: Reactive Mobile Manipulation Control on a Gaussian Splat](https://arxiv.org/abs/2512.09656v1)**  
  Authors: Nicolas Marticorena, Tobias Fischer, Niko Suenderhauf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09656v1.pdf)  
  Keywords: efficient, motion, ar  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: relighting, avatar, ar, relightable, dynamic, 3d gaussian, body, gaussian splatting, deformation, motion, nerf, human, lighting, high-fidelity  
- **[MoRel: Long-Range Flicker-Free 4D Motion Modeling via Anchor Relay-based Bidirectional Blending with Hierarchical Densification](https://arxiv.org/abs/2512.09270v1)**  
  Authors: Sangwoon Kwak, Weeyoung Kwon, Jun Young Jeong, Geonho Kim, Won-Sik Cheong, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09270v1.pdf)  
  Keywords: 4d, ar, dynamic, 3d gaussian, gaussian splatting, deformation, efficient, motion, real-time rendering  
- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 4d, avatar, lightweight, ar, dynamic, 3d gaussian, gaussian splatting, efficient, neural rendering  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, deformation, gaussian splatting, face, sparse-view  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d reconstruction, survey, ar, dynamic, 3d gaussian, gaussian splatting, compression, compact, efficient, high-fidelity  

### Few-shot

*Showing the latest 50 out of 84 papers*

- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, motion, sparse view, high-fidelity  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, ar, gaussian splatting, segmentation, geometry, light transport, lighting, sparse-view  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, deformation, gaussian splatting, face, sparse-view  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: lightweight, ar, 3d gaussian, gaussian splatting, efficient, head, sparse-view  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, segmentation, compact, efficient, head, sparse view, understanding  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, efficient, sparse view, sparse-view  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relighting, ar, relightable, dynamic, 3d gaussian, body, geometry, tracking, efficient, motion, illumination, human, sparse view, lighting, sparse-view  
- **[Observer Actor: Active Vision Imitation Learning with Sparse View Gaussian Splatting](https://arxiv.org/abs/2511.18140v1)**  
  Authors: Yilong Wang, Cheng Qian, Ruomeng Fan, Edward Johns  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18140v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://obact.github.io.)  
  Keywords: ar, dynamic, 3d gaussian, gaussian splatting, sparse view  
- **[Frequency-Adaptive Sharpness Regularization for Improving 3D Gaussian Splatting Generalization](https://arxiv.org/abs/2511.17918v1)**  
  Authors: Youngsik Yun, Dongjun Gu, Youngjung Uh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17918v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://bbangsik13.github.io/FASR.)  
  Keywords: few-shot, 3d gaussian, ar, gaussian splatting  

### Geometry Reconstruction

*Showing the latest 50 out of 347 papers*

- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, motion, sparse view, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, ar, gaussian splatting, segmentation, geometry, light transport, lighting, sparse-view  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: relighting, avatar, ar, relightable, gaussian splatting, geometry, mapping, efficient, head, lighting  
- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: ar, localization, slam, 3d gaussian, segmentation, gaussian splatting, semantic, geometry, vr, tracking, mapping, robotics, understanding  
- **[On-the-fly Large-scale 3D Reconstruction from Multi-Camera Rigs](https://arxiv.org/abs/2512.08498v1)**  
  Authors: Yijia Guo, Tong Hu, Zhiwei Li, Liwen Hu, Keming Qian, Xitong Lin, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08498v1.pdf)  
  Keywords: 3d reconstruction, lightweight, ar, 3d gaussian, gaussian splatting, efficient  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, semantic, understanding  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d reconstruction, survey, ar, dynamic, 3d gaussian, gaussian splatting, compression, compact, efficient, high-fidelity  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v2)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v2.pdf)  
  Keywords: relighting, ar, relightable, 3d gaussian, gaussian splatting, geometry, face, lighting  

### Large Scene

*Showing the latest 50 out of 74 papers*

- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: 4d, ar, dynamic, 3d gaussian, outdoor, gaussian splatting, efficient, motion, nerf, robotics  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, outdoor, gaussian splatting, geometry, understanding  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: fast, ar, outdoor, gaussian splatting, semantic, geometry  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: relighting, ar, outdoor, gaussian splatting, segmentation, geometry, semantic, efficient, illumination, face, lighting, high-fidelity  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: ar, 3d gaussian, outdoor, gaussian splatting, geometry, high-fidelity  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: 4d, urban scene, ar, autonomous driving, dynamic, gaussian splatting, human  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: fast, large scene, ar, 3d gaussian, gaussian splatting, head  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: ar, slam, 3d gaussian, outdoor, gaussian splatting, geometry, mapping, motion, understanding  
- **[D$^2$GS: Dense Depth Regularization for LiDAR-free Urban Scene Reconstruction](https://arxiv.org/abs/2510.25173v2)**  
  Authors: Kejing Xia, Jidong Jia, Ke Jin, Yucai Bai, Li Sun, Dacheng Tao, Youjian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25173v2.pdf)  
  Keywords: urban scene, ar, autonomous driving, gaussian splatting, geometry  
- **[AtlasGS: Atlanta-world Guided Surface Reconstruction with Implicit Structured Gaussians](https://arxiv.org/abs/2510.25129v1)**  
  Authors: Xiyu Zhang, Chong Bao, Yipeng Chen, Hongjia Zhai, Yitong Dong, Hujun Bao, Zhaopeng Cui, Guofeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.25129v1.pdf)  
  Keywords: urban scene, 3d reconstruction, ar, gaussian splatting, semantic, face  

### Model Compression

*Showing the latest 50 out of 399 papers*

- **[Long-LRM++: Preserving Fine Details in Feed-Forward Wide-Coverage Reconstruction](https://arxiv.org/abs/2512.10267v1)**  
  Authors: Chen Ziwen, Hao Tan, Peng Wang, Zexiang Xu, Li Fuxin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10267v1.pdf)  
  Keywords: lightweight, ar, gaussian splatting, compression, real-time rendering  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, efficient, efficient rendering, face, sparse-view  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: ar, localization, recognition, 3d gaussian, gaussian splatting, compact, mapping, human  
- **[ReMoSPLAT: Reactive Mobile Manipulation Control on a Gaussian Splat](https://arxiv.org/abs/2512.09656v1)**  
  Authors: Nicolas Marticorena, Tobias Fischer, Niko Suenderhauf  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09656v1.pdf)  
  Keywords: efficient, motion, ar  
- **[MoRel: Long-Range Flicker-Free 4D Motion Modeling via Anchor Relay-based Bidirectional Blending with Hierarchical Densification](https://arxiv.org/abs/2512.09270v1)**  
  Authors: Sangwoon Kwak, Weeyoung Kwon, Jun Young Jeong, Geonho Kim, Won-Sik Cheong, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09270v1.pdf)  
  Keywords: 4d, ar, dynamic, 3d gaussian, gaussian splatting, deformation, efficient, motion, real-time rendering  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: relighting, avatar, ar, relightable, gaussian splatting, geometry, mapping, efficient, head, lighting  
- **[On-the-fly Large-scale 3D Reconstruction from Multi-Camera Rigs](https://arxiv.org/abs/2512.08498v1)**  
  Authors: Yijia Guo, Tong Hu, Zhiwei Li, Liwen Hu, Keming Qian, Xitong Lin, Shengbo Chen, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08498v1.pdf)  
  Keywords: 3d reconstruction, lightweight, ar, 3d gaussian, gaussian splatting, efficient  
- **[Visionary: The World Model Carrier Built on WebGPU-Powered Gaussian Splatting Platform](https://arxiv.org/abs/2512.08478v1)**  
  Authors: Yuning Gong, Yifei Liu, Yifan Zhan, Muyao Niu, Xueying Li, Yuanjun Liao, Jiaming Chen, Yuanyuan Gao, Jiaqi Chen, Minming Chen, Li Zhou, Yuning Zhang, Wei Wang, Xiaoqing Hou, Huaxi Huang, Shixiang Tang, Le Ma, Dingwen Zhang, Xue Yang, Junchi Yan, Yanchi Zhang, Yinqiang Zheng, Xiao Sun, Zhihang Zhong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08478v1.pdf)  
  Keywords: 4d, avatar, lightweight, ar, dynamic, 3d gaussian, gaussian splatting, efficient, neural rendering  
- **[Multi-view Pyramid Transformer: Look Coarser to See Broader](https://arxiv.org/abs/2512.07806v1)**  
  Authors: Gyeongjin Kang, Seungkwon Yang, Seungtae Nam, Younggeun Lee, Jungwoo Kim, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07806v1.pdf)  
  Keywords: fast, ar, 3d gaussian, gaussian splatting, compact  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d reconstruction, survey, ar, dynamic, 3d gaussian, gaussian splatting, compression, compact, efficient, high-fidelity  

### Quality Enhancement

*Showing the latest 50 out of 192 papers*

- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: ar, deformation, gaussian splatting, mapping, face, high-fidelity  
- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, motion, sparse view, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: relighting, avatar, ar, relightable, dynamic, 3d gaussian, body, gaussian splatting, deformation, motion, nerf, human, lighting, high-fidelity  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: acceleration, fast, ar, 3d gaussian, gaussian splatting, nerf, face, high-fidelity, reflection  
- **[SUCCESS-GS: Survey of Compactness and Compression for Efficient Static and Dynamic Gaussian Splatting](https://arxiv.org/abs/2512.07197v1)**  
  Authors: Seokhyun Youn, Soohyun Lee, Geonho Kim, Weeyoung Kwon, Sung-Ho Bae, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07197v1.pdf)  
  Keywords: 4d, 3d reconstruction, survey, ar, dynamic, 3d gaussian, gaussian splatting, compression, compact, efficient, high-fidelity  
- **[AGORA: Adversarial Generation Of Real-time Animatable 3D Gaussian Head Avatars](https://arxiv.org/abs/2512.06438v2)**  
  Authors: Ramazan Fazylov, Sergey Zagoruyko, Aleksandr Parkin, Stamatis Lefkimmiatis, Ivan Laptev  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06438v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ramazan793.github.io/AGORA/)  
  Keywords: avatar, lightweight, ar, dynamic, 3d gaussian, gaussian splatting, deformation, vr, nerf, human, head, high-fidelity  
- **[TriaGS: Differentiable Triangulation-Guided Geometric Consistency for 3D Gaussian Splatting](https://arxiv.org/abs/2512.06269v1)**  
  Authors: Quan Tran, Tuan Dang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06269v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, geometry, face, high-fidelity  
- **[SplatPainter: Interactive Authoring of 3D Gaussians from 2D Edits via Test-Time Training](https://arxiv.org/abs/2512.05354v1)**  
  Authors: Yang Zheng, Hao Tan, Kai Zhang, Peng Wang, Leonidas Guibas, Gordon Wetzstein, Wang Yifan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05354v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, compact, high-fidelity  
- **[Splannequin: Freezing Monocular Mannequin-Challenge Footage with Dual-Detection Splatting](https://arxiv.org/abs/2512.05113v2)**  
  Authors: Hao-Jen Chien, Yi-Chuan Huang, Chung-Ho Wu, Wei-Lun Chao, Yu-Lun Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05113v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chien90190.github.io/splannequin/)  
  Keywords: ar, dynamic, gaussian splatting, motion, head, high-fidelity  

### Ray Tracing

- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: ar, gaussian splatting, geometry, ray tracing, illumination, reflection  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: ar, 3d gaussian, gaussian splatting, geometry, efficient, ray marching  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: ar, relightable, face, gaussian splatting, ray tracing, efficient, shadow, light transport, real-time rendering, lighting  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: relighting, ar, gaussian splatting, geometry, efficient, illumination, global illumination, light transport, lighting, reflection  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: 4d, fast, ar, dynamic, gaussian splatting, ray tracing  
- **[GOGS: High-Fidelity Geometry and Relighting for Glossy Objects via Gaussian Surfels](https://arxiv.org/abs/2508.14563v1)**  
  Authors: Xingyuan Yang, Min Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.14563v1.pdf)  
  Keywords: relighting, ar, 3d gaussian, gaussian splatting, ray tracing, geometry, illumination, nerf, face, lighting, high-fidelity, reflection  
- **[GaRe: Relightable 3D Gaussian Splatting for Outdoor Scenes from Unconstrained Photo Collections](https://arxiv.org/abs/2507.20512v1)**  
  Authors: Haiyang Bai, Jiaqi Zhu, Songru Jiang, Wei Huang, Tao Lu, Yuanqi Li, Jie Guo, Runze Fu, Yanwen Guo, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.20512v1.pdf)  
  Keywords: relighting, ar, relightable, dynamic, 3d gaussian, outdoor, gaussian splatting, shadow, global illumination, illumination, face, lighting  
- **[GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D Gaussian Splatting](https://arxiv.org/abs/2507.19718v2)**  
  Authors: David Bauer, Qi Wu, Hamid Gadirov, Kwan-Liu Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.19718v2.pdf)  
  Keywords: path tracing, ar, dynamic, 3d gaussian, gaussian splatting, face, lighting  
- **[Gaussian Splatting with Discretized SDF for Relightable Assets](https://arxiv.org/abs/2507.15629v1)**  
  Authors: Zuo-Liang Zhu, Jian Yang, Beibei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.15629v1.pdf)  
  Keywords: relighting, ar, relightable, 3d gaussian, gaussian splatting, geometry, efficient, efficient rendering, ray marching, face, lighting  

### Relighting

*Showing the latest 50 out of 123 papers*

- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, gaussian splatting, ray tracing, geometry, high-fidelity, reflection  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, ar, gaussian splatting, segmentation, geometry, light transport, lighting, sparse-view  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: relighting, avatar, ar, relightable, dynamic, 3d gaussian, body, gaussian splatting, deformation, motion, nerf, human, lighting, high-fidelity  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: relighting, avatar, ar, relightable, gaussian splatting, geometry, mapping, efficient, head, lighting  
- **[HybridSplat: Fast Reflection-baked Gaussian Tracing using Hybrid Splatting](https://arxiv.org/abs/2512.08334v1)**  
  Authors: Chang Liu, Hongliang Yuan, Lianghao Zhang, Sichao Wang, Jianwei Guo, Shi-Sheng Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08334v1.pdf)  
  Keywords: acceleration, fast, ar, 3d gaussian, gaussian splatting, nerf, face, high-fidelity, reflection  
- **[COREA: Coarse-to-Fine 3D Representation Alignment Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision](https://arxiv.org/abs/2512.07107v2)**  
  Authors: Jaeyoon Lee, Hojoon Jung, Sungtae Hwang, Jihyong Oh, Jongwon Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07107v2.pdf)  
  Keywords: relighting, ar, relightable, 3d gaussian, gaussian splatting, geometry, face, lighting  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, gaussian splatting, semantic, illumination  
- **[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://arxiv.org/abs/2512.02664v1)**  
  Authors: Derui Shan, Qian Qiao, Hao Lu, Tao Du, Peng Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02664v1.pdf)  
  Keywords: ar, efficient rendering, 3d gaussian, face, gaussian splatting, geometry, efficient, nerf, real-time rendering, high-fidelity, reflection  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: relighting, ar, relightable, dynamic, 3d gaussian, body, geometry, tracking, efficient, motion, illumination, human, sparse view, lighting, sparse-view  
- **[Endo-G$^{2}$T: Geometry-Guided & Temporally Aware Time-Embedded 4DGS For Endoscopic Scenes](https://arxiv.org/abs/2511.21367v1)**  
  Authors: Yangle Liu, Fengze Li, Kan Liu, Jieming Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.21367v1.pdf)  
  Keywords: 4d, lightweight, ar, dynamic, gaussian splatting, geometry, motion, nerf, reflection  

### SLAM

*Showing the latest 50 out of 148 papers*

- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: avatar, fast, ar, gaussian splatting, tracking, mapping, head  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: ar, deformation, gaussian splatting, mapping, face, high-fidelity  
- **[Neural Hamiltonian Deformation Fields for Dynamic Scene Rendering](https://arxiv.org/abs/2512.10424v1)**  
  Authors: Hai-Long Qin, Sixian Wang, Guo Lu, Jincheng Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10424v1.pdf)  
  Keywords: ar, dynamic, deformation, gaussian splatting, mapping, motion  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: ar, localization, recognition, 3d gaussian, gaussian splatting, compact, mapping, human  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: relighting, avatar, ar, relightable, gaussian splatting, geometry, mapping, efficient, head, lighting  
- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: ar, localization, slam, 3d gaussian, segmentation, gaussian splatting, semantic, geometry, vr, tracking, mapping, robotics, understanding  
- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: 4d, ar, animation, dynamic, gaussian splatting, tracking, motion  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: 4d, ar, dynamic, gaussian splatting, segmentation, geometry, semantic, tracking, motion, understanding  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: survey, ar, localization, slam, 3d gaussian, gaussian splatting, semantic, mapping, nerf, robotics, understanding  
- **[PoreTrack3D: A Benchmark for Dynamic 3D Gaussian Splatting in Pore-Scale Facial Trajectory Tracking](https://arxiv.org/abs/2512.02648v1)**  
  Authors: Dong Li, Jiahao Xiong, Yingda Huang, Le Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.02648v1.pdf)  
  Keywords: 3d reconstruction, ar, dynamic, 3d gaussian, gaussian splatting, tracking, motion, face, high-fidelity  

### Scene Understanding

*Showing the latest 50 out of 208 papers*

- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: relighting, ar, gaussian splatting, segmentation, geometry, light transport, lighting, sparse-view  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: ar, localization, recognition, 3d gaussian, gaussian splatting, compact, mapping, human  
- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: ar, localization, slam, 3d gaussian, segmentation, gaussian splatting, semantic, geometry, vr, tracking, mapping, robotics, understanding  
- **[Zero-Splat TeleAssist: A Zero-Shot Pose Estimation Framework for Semantic Teleoperation](https://arxiv.org/abs/2512.08271v1)**  
  Authors: Srijan Dokania, Dharini Raghavan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08271v1.pdf)  
  Keywords: ar, 3d gaussian, segmentation, gaussian splatting, semantic  
- **[STRinGS: Selective Text Refinement in Gaussian Splatting](https://arxiv.org/abs/2512.07230v1)**  
  Authors: Abhinav Raundhal, Gaurav Behera, P J Narayanan, Ravi Kiran Sarvadevabhatla, Makarand Tapaswi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07230v1.pdf)  
  Keywords: 3d reconstruction, ar, 3d gaussian, gaussian splatting, semantic, understanding  
- **[4DLangVGGT: 4D Language-Visual Geometry Grounded Transformer](https://arxiv.org/abs/2512.05060v1)**  
  Authors: Xianfeng Wu, Yajing Bai, Minghan Li, Xianzu Wu, Xueqi Zhao, Zhongyuan Lai, Wenyu Liu, Xinggang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.05060v1.pdf)  
  Keywords: 4d, ar, dynamic, gaussian splatting, geometry, semantic, nerf, understanding  
- **[RobustSplat++: Decoupling Densification, Dynamics, and Illumination for In-the-Wild 3DGS](https://arxiv.org/abs/2512.04815v1)**  
  Authors: Chuanyu Fu, Guanying Chen, Yuqi Zhang, Kunbin Yao, Yuan Xiong, Chuan Huang, Shuguang Cui, Yasuyuki Matsushita, Xiaochun Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04815v1.pdf)  
  Keywords: ar, dynamic, 3d gaussian, gaussian splatting, semantic, illumination  
- **[Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting](https://arxiv.org/abs/2512.04731v1)**  
  Authors: Jian Tang, Pu Pang, Haowen Sun, Chengzhong Ma, Xingyu Chen, Hua Huang, Xuguang Lan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04731v1.pdf)  
  Keywords: ar, gaussian splatting, semantic  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, segmentation, compact, efficient, head, sparse view, understanding  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: 4d, ar, dynamic, gaussian splatting, segmentation, geometry, semantic, tracking, motion, understanding  



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