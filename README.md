# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-12-24 00:59:02

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

- [3DGS Surveys](#3dgs-surveys) (22 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (254 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (344 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (398 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (81 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (348 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (71 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (407 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (197 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (19 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (128 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (146 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (204 papers) - Papers about scene understanding and semantic analysis



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
  Keywords: gaussian splatting, high-fidelity, 3d gaussian, dynamic, survey, compact, efficient, ar, 4d, 3d reconstruction, compression  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: robotics, gaussian splatting, nerf, 3d gaussian, slam, survey, ar, semantic, mapping, localization, understanding  
- **[A Survey on Collaborative SLAM with 3D Gaussian Splatting](https://arxiv.org/abs/2510.23988v1)**  
  Authors: Phuc Nguyen Xuan, Thanh Nguyen Canh, Huu-Hung Nguyen, Nak Young Chong, Xiem HoangVan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.23988v1.pdf)  
  Keywords: robotics, gaussian splatting, slam, 3d gaussian, efficient, survey, ar, semantic, mapping, high-fidelity, localization  
- **[Advances in 4D Representation: Geometry, Motion, and Interaction](https://arxiv.org/abs/2510.19255v1)**  
  Authors: Mingrui Zhao, Sauradip Nag, Kai Wang, Aditya Vora, Guangda Ji, Peter Chun, Ali Mahdavi-Amiri, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.19255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mingrui-zhao.github.io/4DRep-GMI/)  
  Keywords: gaussian splatting, nerf, 3d gaussian, survey, ar, 4d, geometry, motion, fast  
- **[From Volume Rendering to 3D Gaussian Splatting: Theory and Applications](https://arxiv.org/abs/2510.18101v1)**  
  Authors: Vitor Pereira Matias, Daniel Perazzo, Vinicius Silva, Alberto Raposo, Luiz Velho, Afonso Paiva, Tiago Novello  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.18101v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, survey, animation, efficient, ar, lighting, efficient rendering, real-time rendering, 3d reconstruction, avatar  
- **[Vision Language Models: A Survey of 26K Papers](https://arxiv.org/abs/2510.09586v1)**  
  Authors: Fengming Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.09586v1.pdf)  
  Keywords: gaussian splatting, nerf, human, efficient, survey, ar, lightweight, understanding  
- **[From Fields to Splats: A Cross-Domain Survey of Real-Time Neural Scene Representations](https://arxiv.org/abs/2509.23555v1)**  
  Authors: Javed Ahmad, Penggang Gao, Donatien Delehelle, Mennuti Canio, Nikhil Deshpande, Jesús Ortiz, Darwin G. Caldwell, Yonas Teodros Tefera  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.23555v1.pdf)  
  Keywords: gaussian splatting, nerf, 3d gaussian, slam, survey, efficient, ar, neural rendering, fast, understanding  
- **[A Survey on 3D Gaussian Splatting Applications: Segmentation, Editing, and Generation](https://arxiv.org/abs/2508.09977v2)**  
  Authors: Shuting He, Peilin Ji, Yitong Yang, Changshuo Wang, Jiayi Ji, Yinglin Wang, Henghui Ding  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.09977v2.pdf)  
  Keywords: gaussian splatting, nerf, 3d gaussian, survey, compact, ar, semantic, lighting, high-fidelity, understanding, segmentation  
- **[A Study of the Framework and Real-World Applications of Language Embedding for 3D Scene Understanding](https://arxiv.org/abs/2508.05064v2)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Yehor Karpichev, Brandon Haworth, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.05064v2.pdf)  
  Keywords: robotics, gaussian splatting, nerf, 3d gaussian, efficient, survey, ar, semantic, understanding  
- **[Radiance Fields in XR: A Survey on How Radiance Fields are Envisioned and Addressed for XR Research](https://arxiv.org/abs/2508.04326v2)**  
  Authors: Ke Li, Mana Masuda, Susanne Schmidt, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2508.04326v2.pdf)  
  Keywords: robotics, gaussian splatting, nerf, 3d gaussian, human, survey, ar  

### Acceleration

*Showing the latest 50 out of 254 papers*

- **[4D Gaussian Splatting as a Learned Dynamical System](https://arxiv.org/abs/2512.19648v1)**  
  Authors: Arnold Caleb Asiimwe, Carl Vondrick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19648v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, efficient, ar, 4d, motion, real-time rendering  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[Voxel-GS: Quantized Scaffold Gaussian Splatting Compression with Run-Length Coding](https://arxiv.org/abs/2512.17528v1)**  
  Authors: Chunyang Fu, Xiangrui Liu, Shiqi Wang, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17528v1.pdf)  
  Keywords: gaussian splatting, ar, compact, fast, high-fidelity, lightweight, compression  
- **[Instant Expressive Gaussian Head Avatar via 3D-Aware Expression Distillation](https://arxiv.org/abs/2512.16893v1)**  
  Authors: Kaiwen Jiang, Xueting Li, Seonwook Park, Ravi Ramamoorthi, Shalini De Mello, Koki Nagano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16893v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.nvidia.com/labs/amri/projects/instant4d)  
  Keywords: gaussian splatting, face, head, animation, efficient, ar, 4d, motion, fast, lightweight, avatar  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: gaussian splatting, face, nerf, 3d gaussian, ar, ray tracing, fast  
- **[Gaussian Pixel Codec Avatars: A Hybrid Representation for Efficient Rendering](https://arxiv.org/abs/2512.15711v1)**  
  Authors: Divam Gupta, Anuj Pahuja, Nemanja Bartolovic, Tomas Simon, Forrest Iandola, Giljoo Nam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15711v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, head, efficient, ar, efficient rendering, avatar  
- **[VLA-AN: An Efficient and Onboard Vision-Language-Action Framework for Aerial Navigation in Complex Environments](https://arxiv.org/abs/2512.15258v2)**  
  Authors: Yuze Wu, Mo Zhu, Xingxing Li, Yuheng Du, Yuxin Fan, Wenjun Li, Zhichao Han, Xin Zhou, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15258v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, fast, high-fidelity, lightweight  
- **[HGS: Hybrid Gaussian Splatting with Static-Dynamic Decomposition for Compact Dynamic View Synthesis](https://arxiv.org/abs/2512.14352v1)**  
  Authors: Kaizhe Zhang, Yijie Zhou, Weizhan Zhang, Caixia Yan, Haipeng Du, yugui xie, Yu-Hui Wen, Yong-Jin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14352v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, nerf, 3d gaussian, efficient, compact, ar, vr, real-time rendering  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, compact, geometry, fast, outdoor  
- **[Fast 2DGS: Efficient Image Representation with Deep Gaussian Prior](https://arxiv.org/abs/2512.12774v1)**  
  Authors: Hao Wang, Ashish Bastola, Chaoyi Zhou, Wenhui Zhu, Xiwen Chen, Xuanzhao Dong, Siyu Huang, Abolfazl Razi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.12774v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, real-time rendering, fast, high-fidelity, lightweight  

### Applications

*Showing the latest 50 out of 995 papers*

- **[WorldWarp: Propagating 3D Geometry with Asynchronous Video Diffusion](https://arxiv.org/abs/2512.19678v1)**  
  Authors: Hanyang Kong, Xingyi Yang, Xiaoxu Zheng, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19678v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyokong.github.io/worldwarp-page/}{https://hyokong.github.io/worldwarp-page/}.)  
  Keywords: ar, gaussian splatting, geometry, dynamic  
- **[4D Gaussian Splatting as a Learned Dynamical System](https://arxiv.org/abs/2512.19648v1)**  
  Authors: Arnold Caleb Asiimwe, Carl Vondrick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19648v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, efficient, ar, 4d, motion, real-time rendering  
- **[GaussianImage++: Boosted Image Representation and Compression with 2D Gaussian Splatting](https://arxiv.org/abs/2512.19108v1)**  
  Authors: Tiantian Li, Xinjie Zhang, Xingtong Ge, Tongda Xu, Dailan He, Jun Zhang, Yan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19108v1.pdf)  
  Keywords: compression, efficient, gaussian splatting, ar  
- **[EcoSplat: Efficiency-controllable Feed-forward 3D Gaussian Splatting from Multi-view Images](https://arxiv.org/abs/2512.18692v1)**  
  Authors: Jongmin Park, Minh-Quan Viet Bui, Juan Luis Gonzalez Bello, Jaeho Moon, Jihyong Oh, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18692v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, 3d gaussian  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[ChronoDreamer: Action-Conditioned World Model as an Online Simulator for Robotic Planning](https://arxiv.org/abs/2512.18619v1)**  
  Authors: Zhenhao Zhou, Dan Negrut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18619v1.pdf)  
  Keywords: ar, motion  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: gaussian splatting, relightable, ar, ray tracing, relighting, lighting, geometry, 3d reconstruction  
- **[Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://arxiv.org/abs/2512.17817v2)**  
  Authors: Yue Li, Qi Ma, Runyi Yang, Mengjiao Ma, Bin Ren, Nikola Popovic, Nicu Sebe, Theo Gevers, Luc Van Gool, Danda Pani Paudel, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17817v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, semantic, high-fidelity, segmentation  
- **[G3Splat: Geometrically Consistent Generalizable Gaussian Splatting](https://arxiv.org/abs/2512.17547v1)**  
  Authors: Mehdi Hosseinzadeh, Shin-Fang Chng, Yi Xu, Simon Lucey, Ian Reid, Ravi Garg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17547v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://m80hz.github.io/g3splat/).)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian  
- **[Voxel-GS: Quantized Scaffold Gaussian Splatting Compression with Run-Length Coding](https://arxiv.org/abs/2512.17528v1)**  
  Authors: Chunyang Fu, Xiangrui Liu, Shiqi Wang, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17528v1.pdf)  
  Keywords: gaussian splatting, ar, compact, fast, high-fidelity, lightweight, compression  

### Avatar Generation

*Showing the latest 50 out of 344 papers*

- **[Instant Expressive Gaussian Head Avatar via 3D-Aware Expression Distillation](https://arxiv.org/abs/2512.16893v1)**  
  Authors: Kaiwen Jiang, Xueting Li, Seonwook Park, Ravi Ramamoorthi, Shalini De Mello, Koki Nagano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16893v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.nvidia.com/labs/amri/projects/instant4d)  
  Keywords: gaussian splatting, face, head, animation, efficient, ar, 4d, motion, fast, lightweight, avatar  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: gaussian splatting, face, nerf, 3d gaussian, ar, ray tracing, fast  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: gaussian splatting, face, nerf, relightable, human, ar, semantic, lighting, geometry, high-fidelity, segmentation  
- **[Gaussian Pixel Codec Avatars: A Hybrid Representation for Efficient Rendering](https://arxiv.org/abs/2512.15711v1)**  
  Authors: Divam Gupta, Anuj Pahuja, Nemanja Bartolovic, Tomas Simon, Forrest Iandola, Giljoo Nam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15711v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, head, efficient, ar, efficient rendering, avatar  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, gaussian splatting, face, 3d gaussian, efficient, ar, geometry, 3d reconstruction, illumination  
- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: gaussian splatting, head, ar, mapping, tracking, fast, avatar  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: deformation, gaussian splatting, face, ar, mapping, high-fidelity  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, efficient, ar, efficient rendering, sparse-view, 3d reconstruction  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, human, ar, compact, mapping, recognition, localization  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: deformation, gaussian splatting, nerf, 3d gaussian, relightable, dynamic, human, ar, relighting, lighting, body, motion, high-fidelity, avatar  

### Dynamic Scene

*Showing the latest 50 out of 398 papers*

- **[WorldWarp: Propagating 3D Geometry with Asynchronous Video Diffusion](https://arxiv.org/abs/2512.19678v1)**  
  Authors: Hanyang Kong, Xingyi Yang, Xiaoxu Zheng, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19678v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyokong.github.io/worldwarp-page/}{https://hyokong.github.io/worldwarp-page/}.)  
  Keywords: ar, gaussian splatting, geometry, dynamic  
- **[4D Gaussian Splatting as a Learned Dynamical System](https://arxiv.org/abs/2512.19648v1)**  
  Authors: Arnold Caleb Asiimwe, Carl Vondrick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19648v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, efficient, ar, 4d, motion, real-time rendering  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[ChronoDreamer: Action-Conditioned World Model as an Online Simulator for Robotic Planning](https://arxiv.org/abs/2512.18619v1)**  
  Authors: Zhenhao Zhou, Dan Negrut  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18619v1.pdf)  
  Keywords: ar, motion  
- **[Instant Expressive Gaussian Head Avatar via 3D-Aware Expression Distillation](https://arxiv.org/abs/2512.16893v1)**  
  Authors: Kaiwen Jiang, Xueting Li, Seonwook Park, Ravi Ramamoorthi, Shalini De Mello, Koki Nagano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16893v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.nvidia.com/labs/amri/projects/instant4d)  
  Keywords: gaussian splatting, face, head, animation, efficient, ar, 4d, motion, fast, lightweight, avatar  
- **[Broadening View Synthesis of Dynamic Scenes from Constrained Monocular Videos](https://arxiv.org/abs/2512.14406v1)**  
  Authors: Le Jiang, Shaotong Zhu, Yedi Luo, Shayda Moezzi, Sarah Ostadabbas  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14406v1.pdf)  
  Keywords: dynamic, ar, gaussian splatting, nerf  
- **[HGS: Hybrid Gaussian Splatting with Static-Dynamic Decomposition for Compact Dynamic View Synthesis](https://arxiv.org/abs/2512.14352v1)**  
  Authors: Kaizhe Zhang, Yijie Zhou, Weizhan Zhang, Caixia Yan, Haipeng Du, yugui xie, Yu-Hui Wen, Yong-Jin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14352v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, nerf, 3d gaussian, efficient, compact, ar, vr, real-time rendering  
- **[Prior-Enhanced Gaussian Splatting for Dynamic Scene Reconstruction from Casual Video](https://arxiv.org/abs/2512.11356v1)**  
  Authors: Meng-Li Shih, Ying-Huan Chen, Yu-Lun Liu, Brian Curless  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11356v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, geometry, motion, segmentation  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: deformation, gaussian splatting, face, ar, mapping, high-fidelity  
- **[Neural Hamiltonian Deformation Fields for Dynamic Scene Rendering](https://arxiv.org/abs/2512.10424v1)**  
  Authors: Hai-Long Qin, Sixian Wang, Guo Lu, Jincheng Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10424v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, ar, mapping, motion  

### Few-shot

*Showing the latest 50 out of 81 papers*

- **[Breaking the Vicious Cycle: Coherent 3D Gaussian Splatting from Sparse and Motion-Blurred Views](https://arxiv.org/abs/2512.10369v1)**  
  Authors: Zhankuo Xu, Chaoran Feng, Yingtao Li, Jianbin Zhao, Jiashu Yang, Wangbo Yu, Li Yuan, Yonghong Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10369v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://potatobigroom.github.io/CoherentGS/.)  
  Keywords: gaussian splatting, high-fidelity, 3d gaussian, ar, motion, 3d reconstruction, sparse view  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: gaussian splatting, ar, relighting, lighting, geometry, sparse-view, light transport, segmentation  
- **[Splatent: Splatting Diffusion Latents for Novel View Synthesis](https://arxiv.org/abs/2512.09923v1)**  
  Authors: Or Hirschorn, Omer Sela, Inbar Huberman-Spiegelglas, Netalee Efrat, Eli Alshan, Ianir Ideses, Frederic Devernay, Yochai Zvik, Lior Fritz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09923v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, efficient, ar, efficient rendering, sparse-view, 3d reconstruction  
- **[Tessellation GS: Neural Mesh Gaussians for Robust Monocular Reconstruction of Dynamic Objects](https://arxiv.org/abs/2512.07381v1)**  
  Authors: Shuohan Tao, Boyao Zhou, Hanzhang Tu, Yuwang Wang, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07381v1.pdf)  
  Keywords: deformation, gaussian splatting, face, dynamic, 3d gaussian, ar, sparse-view  
- **[MuSASplat: Efficient Sparse-View 3D Gaussian Splats via Lightweight Multi-Scale Adaptation](https://arxiv.org/abs/2512.07165v1)**  
  Authors: Muyu Xu, Fangneng Zhan, Xiaoqin Zhang, Ling Shao, Shijian Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.07165v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, head, efficient, ar, sparse-view, lightweight  
- **[C3G: Learning Compact 3D Representations with 2K Gaussians](https://arxiv.org/abs/2512.04021v1)**  
  Authors: Honggyu An, Jaewoo Jung, Mungyeom Kim, Sunghwan Hong, Chaehyun Kim, Kazumi Fukuda, Minkyeong Jeon, Jisang Han, Takuya Narihira, Hyuna Ko, Junsu Kim, Yuki Mitsufuji, Seungryong Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.04021v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, head, efficient, compact, ar, sparse view, understanding, segmentation  
- **[Cross-Temporal 3D Gaussian Splatting for Sparse-View Guided Scene Update](https://arxiv.org/abs/2512.00534v1)**  
  Authors: Zeyuan An, Yanghang Xiao, Zhiying Leng, Frederick W. B. Li, Xiaohui Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00534v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, sparse-view, sparse view  
- **[Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://arxiv.org/abs/2512.00255v1)**  
  Authors: Kunwar Maheep Singh, Jianchun Chen, Vladislav Golyanik, Stephan J. Garbin, Thabo Beeler, Rishabh Dabral, Marc Habermann, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.00255v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/RHC/)  
  Keywords: dynamic, 3d gaussian, relightable, human, efficient, ar, relighting, lighting, body, geometry, tracking, motion, sparse-view, illumination, sparse view  
- **[Observer Actor: Active Vision Imitation Learning with Sparse View Gaussian Splatting](https://arxiv.org/abs/2511.18140v1)**  
  Authors: Yilong Wang, Cheng Qian, Ruomeng Fan, Edward Johns  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18140v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://obact.github.io.)  
  Keywords: gaussian splatting, dynamic, 3d gaussian, ar, sparse view  
- **[Frequency-Adaptive Sharpness Regularization for Improving 3D Gaussian Splatting Generalization](https://arxiv.org/abs/2511.17918v1)**  
  Authors: Youngsik Yun, Dongjun Gu, Youngjung Uh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.17918v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://bbangsik13.github.io/FASR.)  
  Keywords: ar, gaussian splatting, 3d gaussian, few-shot  

### Geometry Reconstruction

*Showing the latest 50 out of 348 papers*

- **[WorldWarp: Propagating 3D Geometry with Asynchronous Video Diffusion](https://arxiv.org/abs/2512.19678v1)**  
  Authors: Hanyang Kong, Xingyi Yang, Xiaoxu Zheng, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19678v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyokong.github.io/worldwarp-page/}{https://hyokong.github.io/worldwarp-page/}.)  
  Keywords: ar, gaussian splatting, geometry, dynamic  
- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: gaussian splatting, relightable, ar, ray tracing, relighting, lighting, geometry, 3d reconstruction  
- **[G3Splat: Geometrically Consistent Generalizable Gaussian Splatting](https://arxiv.org/abs/2512.17547v1)**  
  Authors: Mehdi Hosseinzadeh, Shin-Fang Chng, Yi Xu, Simon Lucey, Ian Reid, Ravi Garg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17547v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://m80hz.github.io/g3splat/).)  
  Keywords: ar, gaussian splatting, geometry, 3d gaussian  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: gaussian splatting, face, nerf, relightable, human, ar, semantic, lighting, geometry, high-fidelity, segmentation  
- **[Off The Grid: Detection of Primitives for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2512.15508v1)**  
  Authors: Arthur Moreau, Richard Shaw, Michal Nazarczuk, Jisu Shin, Thomas Tanay, Zhensong Zhang, Songcen Xu, Eduardo Pérez-Pellitero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15508v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, 3d reconstruction  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, gaussian splatting, face, 3d gaussian, efficient, ar, geometry, 3d reconstruction, illumination  
- **[GaussianPlant: Structure-aligned Gaussian Splatting for 3D Reconstruction of Plants](https://arxiv.org/abs/2512.14087v1)**  
  Authors: Yang Yang, Risa Shinoda, Hiroaki Santo, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14087v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, 3d gaussian, ar, geometry, 3d reconstruction  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, compact, geometry, fast, outdoor  
- **[Prior-Enhanced Gaussian Splatting for Dynamic Scene Reconstruction from Casual Video](https://arxiv.org/abs/2512.11356v1)**  
  Authors: Meng-Li Shih, Ying-Huan Chen, Yu-Lun Liu, Brian Curless  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11356v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, geometry, motion, segmentation  

### Large Scene

*Showing the latest 50 out of 71 papers*

- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, gaussian splatting, face, 3d gaussian, efficient, ar, geometry, 3d reconstruction, illumination  
- **[Nexels: Neurally-Textured Surfels for Real-Time Novel View Synthesis with Sparse Geometries](https://arxiv.org/abs/2512.13796v1)**  
  Authors: Victor Rong, Jan Held, Victor Chu, Daniel Rebain, Marc Van Droogenbroeck, Kiriakos N. Kutulakos, Andrea Tagliasacchi, David B. Lindell  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13796v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, compact, geometry, fast, outdoor  
- **[Flux4D: Flow-based Unsupervised 4D Reconstruction](https://arxiv.org/abs/2512.03210v1)**  
  Authors: Jingkang Wang, Henry Che, Yun Chen, Ze Yang, Lily Goli, Sivabalan Manivasagam, Raquel Urtasun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03210v1.pdf)  
  Keywords: robotics, gaussian splatting, dynamic, nerf, 3d gaussian, efficient, ar, 4d, motion, outdoor  
- **[PhysGS: Bayesian-Inferred Gaussian Splatting for Physical Property Estimation](https://arxiv.org/abs/2511.18570v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://samchopra2003.github.io/physgs.)  
  Keywords: gaussian splatting, 3d gaussian, ar, geometry, 3d reconstruction, outdoor, understanding  
- **[Splatblox: Traversability-Aware Gaussian Splatting for Outdoor Robot Navigation](https://arxiv.org/abs/2511.18525v1)**  
  Authors: Samarth Chopra, Jing Liang, Gershom Seneviratne, Yonghan Lee, Jaehoon Choi, Jianyu An, Stephen Cheng, Dinesh Manocha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.18525v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://splatblox.github.io)  
  Keywords: gaussian splatting, ar, semantic, geometry, fast, outdoor  
- **[Training-Free Multi-View Extension of IC-Light for Textual Position-Aware Scene Relighting](https://arxiv.org/abs/2511.13684v1)**  
  Authors: Jiangnan Ye, Jiedong Zhuang, Lianrui Mu, Wenjie Zheng, Jiaqi Hu, Xingze Zou, Jing Wang, Haoji Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.13684v1.pdf)  
  Keywords: gaussian splatting, face, efficient, ar, relighting, semantic, lighting, geometry, high-fidelity, illumination, outdoor, segmentation  
- **[Robust and High-Fidelity 3D Gaussian Splatting: Fusing Pose Priors and Geometry Constraints for Texture-Deficient Outdoor Scenes](https://arxiv.org/abs/2511.06765v1)**  
  Authors: Meijun Guo, Yongliang Shi, Caiyun Liu, Yixiao Feng, Ming Ma, Tinghai Yan, Weining Lu, Bin Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06765v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, geometry, high-fidelity, outdoor  
- **[DIAL-GS: Dynamic Instance Aware Reconstruction for Label-free Street Scenes with 4D Gaussian Splatting](https://arxiv.org/abs/2511.06632v1)**  
  Authors: Chenpeng Su, Wenhua Wu, Chensheng Peng, Tianchen Deng, Zhe Liu, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.06632v1.pdf)  
  Keywords: autonomous driving, urban scene, gaussian splatting, dynamic, human, ar, 4d  
- **[CLM: Removing the GPU Memory Barrier for 3D Gaussian Splatting](https://arxiv.org/abs/2511.04951v1)**  
  Authors: Hexu Zhao, Xiwen Min, Xiaoteng Liu, Moonjun Gong, Yiming Li, Ang Li, Saining Xie, Jinyang Li, Aurojit Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2511.04951v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, head, ar, fast, large scene  
- **[AgriGS-SLAM: Orchard Mapping Across Seasons via Multi-View Gaussian Splatting SLAM](https://arxiv.org/abs/2510.26358v1)**  
  Authors: Mirko Usuelli, David Rapado-Rincon, Gert Kootstra, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.26358v1.pdf)  
  Keywords: gaussian splatting, slam, 3d gaussian, ar, mapping, geometry, motion, outdoor, understanding  

### Model Compression

*Showing the latest 50 out of 407 papers*

- **[4D Gaussian Splatting as a Learned Dynamical System](https://arxiv.org/abs/2512.19648v1)**  
  Authors: Arnold Caleb Asiimwe, Carl Vondrick  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19648v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, efficient, ar, 4d, motion, real-time rendering  
- **[GaussianImage++: Boosted Image Representation and Compression with 2D Gaussian Splatting](https://arxiv.org/abs/2512.19108v1)**  
  Authors: Tiantian Li, Xinjie Zhang, Xingtong Ge, Tongda Xu, Dailan He, Jun Zhang, Yan Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.19108v1.pdf)  
  Keywords: compression, efficient, gaussian splatting, ar  
- **[EcoSplat: Efficiency-controllable Feed-forward 3D Gaussian Splatting from Multi-view Images](https://arxiv.org/abs/2512.18692v1)**  
  Authors: Jongmin Park, Minh-Quan Viet Bui, Juan Luis Gonzalez Bello, Jaeho Moon, Jihyong Oh, Munchurl Kim  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18692v1.pdf)  
  Keywords: ar, efficient, gaussian splatting, 3d gaussian  
- **[Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://arxiv.org/abs/2512.17817v2)**  
  Authors: Yue Li, Qi Ma, Runyi Yang, Mengjiao Ma, Bin Ren, Nikola Popovic, Nicu Sebe, Theo Gevers, Luc Van Gool, Danda Pani Paudel, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17817v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, semantic, high-fidelity, segmentation  
- **[Voxel-GS: Quantized Scaffold Gaussian Splatting Compression with Run-Length Coding](https://arxiv.org/abs/2512.17528v1)**  
  Authors: Chunyang Fu, Xiangrui Liu, Shiqi Wang, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17528v1.pdf)  
  Keywords: gaussian splatting, ar, compact, fast, high-fidelity, lightweight, compression  
- **[Instant Expressive Gaussian Head Avatar via 3D-Aware Expression Distillation](https://arxiv.org/abs/2512.16893v1)**  
  Authors: Kaiwen Jiang, Xueting Li, Seonwook Park, Ravi Ramamoorthi, Shalini De Mello, Koki Nagano  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16893v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.nvidia.com/labs/amri/projects/instant4d)  
  Keywords: gaussian splatting, face, head, animation, efficient, ar, 4d, motion, fast, lightweight, avatar  
- **[Gaussian Pixel Codec Avatars: A Hybrid Representation for Efficient Rendering](https://arxiv.org/abs/2512.15711v1)**  
  Authors: Divam Gupta, Anuj Pahuja, Nemanja Bartolovic, Tomas Simon, Forrest Iandola, Giljoo Nam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15711v1.pdf)  
  Keywords: gaussian splatting, face, 3d gaussian, head, efficient, ar, efficient rendering, avatar  
- **[Off The Grid: Detection of Primitives for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2512.15508v1)**  
  Authors: Arthur Moreau, Richard Shaw, Michal Nazarczuk, Jisu Shin, Thomas Tanay, Zhensong Zhang, Songcen Xu, Eduardo Pérez-Pellitero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15508v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, 3d reconstruction  
- **[VLA-AN: An Efficient and Onboard Vision-Language-Action Framework for Aerial Navigation in Complex Environments](https://arxiv.org/abs/2512.15258v2)**  
  Authors: Yuze Wu, Mo Zhu, Xingxing Li, Yuheng Du, Yuxin Fan, Wenjun Li, Zhichao Han, Xin Zhou, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15258v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, fast, high-fidelity, lightweight  
- **[HGS: Hybrid Gaussian Splatting with Static-Dynamic Decomposition for Compact Dynamic View Synthesis](https://arxiv.org/abs/2512.14352v1)**  
  Authors: Kaizhe Zhang, Yijie Zhou, Weizhan Zhang, Caixia Yan, Haipeng Du, yugui xie, Yu-Hui Wen, Yong-Jin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14352v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, nerf, 3d gaussian, efficient, compact, ar, vr, real-time rendering  

### Quality Enhancement

*Showing the latest 50 out of 197 papers*

- **[Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://arxiv.org/abs/2512.17817v2)**  
  Authors: Yue Li, Qi Ma, Runyi Yang, Mengjiao Ma, Bin Ren, Nikola Popovic, Nicu Sebe, Theo Gevers, Luc Van Gool, Danda Pani Paudel, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17817v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, semantic, high-fidelity, segmentation  
- **[Voxel-GS: Quantized Scaffold Gaussian Splatting Compression with Run-Length Coding](https://arxiv.org/abs/2512.17528v1)**  
  Authors: Chunyang Fu, Xiangrui Liu, Shiqi Wang, Zhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17528v1.pdf)  
  Keywords: gaussian splatting, ar, compact, fast, high-fidelity, lightweight, compression  
- **[Flying in Clutter on Monocular RGB by Learning in 3D Radiance Fields with Domain Adaptation](https://arxiv.org/abs/2512.17349v1)**  
  Authors: Xijie Huang, Jinhan Li, Tianyue Wu, Xin Zhou, Zhichao Han, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17349v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, high-fidelity, illumination  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: gaussian splatting, face, nerf, relightable, human, ar, semantic, lighting, geometry, high-fidelity, segmentation  
- **[VLA-AN: An Efficient and Onboard Vision-Language-Action Framework for Aerial Navigation in Complex Environments](https://arxiv.org/abs/2512.15258v2)**  
  Authors: Yuze Wu, Mo Zhu, Xingxing Li, Yuheng Du, Yuxin Fan, Wenjun Li, Zhichao Han, Xin Zhou, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.15258v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, fast, high-fidelity, lightweight  
- **[GaussianPlant: Structure-aligned Gaussian Splatting for 3D Reconstruction of Plants](https://arxiv.org/abs/2512.14087v1)**  
  Authors: Yang Yang, Risa Shinoda, Hiroaki Santo, Fumio Okura  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14087v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, 3d gaussian, ar, geometry, 3d reconstruction  
- **[ASAP-Textured Gaussians: Enhancing Textured Gaussians with Adaptive Sampling and Anisotropic Parameterization](https://arxiv.org/abs/2512.14039v1)**  
  Authors: Meng Wei, Cheng Zhang, Jianmin Zheng, Hamid Rezatofighi, Jianfei Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14039v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, high-fidelity  
- **[Fast 2DGS: Efficient Image Representation with Deep Gaussian Prior](https://arxiv.org/abs/2512.12774v1)**  
  Authors: Hao Wang, Ashish Bastola, Chaoyi Zhou, Wenhui Zhu, Xiwen Chen, Xuanzhao Dong, Siyu Huang, Abolfazl Razi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.12774v1.pdf)  
  Keywords: gaussian splatting, efficient, ar, real-time rendering, fast, high-fidelity, lightweight  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, compact, ray tracing, real-time rendering, fast, high-fidelity  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: deformation, gaussian splatting, face, ar, mapping, high-fidelity  

### Ray Tracing

- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: gaussian splatting, relightable, ar, ray tracing, relighting, lighting, geometry, 3d reconstruction  
- **[SDFoam: Signed-Distance Foam for explicit surface reconstruction](https://arxiv.org/abs/2512.16706v1)**  
  Authors: Antonella Rech, Nicola Conci, Nicola Garau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16706v1.pdf)  
  Keywords: gaussian splatting, face, nerf, 3d gaussian, ar, ray tracing, fast  
- **[Moment-Based 3D Gaussian Splatting: Resolving Volumetric Occlusion with Order-Independent Transmittance](https://arxiv.org/abs/2512.11800v1)**  
  Authors: Jan U. Müller, Robin Tim Landsgesell, Leif Van Holland, Patrick Stotko, Reinhard Klein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11800v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, compact, ray tracing, real-time rendering, fast, high-fidelity  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, dynamic, ar, ray tracing, geometry, 3d reconstruction, reflection  
- **[MaterialRefGS: Reflective Gaussian Splatting with Multi-view Consistent Material Inference](https://arxiv.org/abs/2510.11387v2)**  
  Authors: Wenyuan Zhang, Jimin Tang, Weiqi Zhang, Yi Fang, Yu-Shen Liu, Zhizhong Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.11387v2.pdf)  
  Keywords: gaussian splatting, ar, ray tracing, geometry, illumination, reflection  
- **[Splat the Net: Radiance Fields with Splattable Neural Primitives](https://arxiv.org/abs/2510.08491v1)**  
  Authors: Xilong Zhou, Bao-Huy Nguyen, Loïc Magne, Vladislav Golyanik, Thomas Leimkühler, Christian Theobalt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.08491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vcai.mpi-inf.mpg.de/projects/SplatNet/.)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, ray marching, geometry  
- **[ComGS: Efficient 3D Object-Scene Composition via Surface Octahedral Probes](https://arxiv.org/abs/2510.07729v1)**  
  Authors: Jian Gao, Mengqi Yuan, Yifei Zeng, Chang Zeng, Zhihao Li, Zhenyu Chen, Weichao Qiu, Xiao-Xiao Long, Hao Zhu, Xun Cao, Yao Yao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2510.07729v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://nju-3dv.github.io/projects/ComGS/.)  
  Keywords: gaussian splatting, face, relightable, efficient, ar, ray tracing, lighting, real-time rendering, shadow, light transport  
- **[Differentiable Light Transport with Gaussian Surfels via Adapted Radiosity for Efficient Relighting and Geometry Reconstruction](https://arxiv.org/abs/2509.18497v2)**  
  Authors: Kaiwen Jiang, Jia-Mu Sun, Zilu Li, Dan Wang, Tzu-Mao Li, Ravi Ramamoorthi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.18497v2.pdf)  
  Keywords: gaussian splatting, global illumination, efficient, ar, relighting, lighting, geometry, illumination, light transport, reflection  
- **[Every Camera Effect, Every Time, All at Once: 4D Gaussian Ray Tracing for Physics-based Camera Effect Data Generation](https://arxiv.org/abs/2509.10759v2)**  
  Authors: Yi-Ruei Liu, You-Zhe Xie, Yu-Hsiang Hsu, I-Sheng Fang, Yu-Lun Liu, Jun-Cheng Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2509.10759v2.pdf)  
  Keywords: gaussian splatting, dynamic, ar, ray tracing, 4d, fast  

### Relighting

*Showing the latest 50 out of 128 papers*

- **[MatSpray: Fusing 2D Material World Knowledge on 3D Geometry](https://arxiv.org/abs/2512.18314v1)**  
  Authors: Philipp Langsteiner, Jan-Niklas Dihlmann, Hendrik P. A. Lensch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18314v1.pdf)  
  Keywords: gaussian splatting, relightable, ar, ray tracing, relighting, lighting, geometry, 3d reconstruction  
- **[Flying in Clutter on Monocular RGB by Learning in 3D Radiance Fields with Domain Adaptation](https://arxiv.org/abs/2512.17349v1)**  
  Authors: Xijie Huang, Jinhan Li, Tianyue Wu, Xin Zhou, Zhichao Han, Fei Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17349v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, high-fidelity, illumination  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: gaussian splatting, face, nerf, relightable, human, ar, semantic, lighting, geometry, high-fidelity, segmentation  
- **[Beyond a Single Light: A Large-Scale Aerial Dataset for Urban Scene Reconstruction Under Varying Illumination](https://arxiv.org/abs/2512.14200v1)**  
  Authors: Zhuoxiao Li, Wenzong Ma, Taoyu Wu, Jinjing Zhu, Zhenchao Q, Shuai Zhang, Jing Ou, Yinrui Ren, Weiqing Qi, Guobin Shen, Hui Xiong, Wufan Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14200v1.pdf)  
  Keywords: urban scene, gaussian splatting, face, 3d gaussian, efficient, ar, geometry, 3d reconstruction, illumination  
- **[Spherical Voronoi: Directional Appearance as a Differentiable Partition of the Sphere](https://arxiv.org/abs/2512.14180v1)**  
  Authors: Francesco Di Sario, Daniel Rebain, Dor Verbin, Marco Grangetto, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.14180v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, efficient, reflection  
- **[Computer vision training dataset generation for robotic environments using Gaussian splatting](https://arxiv.org/abs/2512.13411v1)**  
  Authors: Patryk Niżeniec, Marcin Iwanowski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13411v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, shadow, segmentation  
- **[Light Field Based 6DoF Tracking of Previously Unobserved Objects](https://arxiv.org/abs/2512.13007v1)**  
  Authors: Nikolai Goncharov, James L. Gray, Donald G. Dansereau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13007v1.pdf)  
  Keywords: autonomous driving, robotics, ar, semantic, tracking, reflection  
- **[TraceFlow: Dynamic 3D Reconstruction of Specular Scenes Driven by Ray Tracing](https://arxiv.org/abs/2512.10095v1)**  
  Authors: Jiachen Tao, Junyi Wu, Haoxuan Wang, Zongxin Yang, Dawen Cai, Yan Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10095v1.pdf)  
  Keywords: gaussian splatting, high-fidelity, dynamic, ar, ray tracing, geometry, 3d reconstruction, reflection  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: gaussian splatting, ar, relighting, lighting, geometry, sparse-view, light transport, segmentation  
- **[Relightable and Dynamic Gaussian Avatar Reconstruction from Monocular Video](https://arxiv.org/abs/2512.09335v2)**  
  Authors: Seonghwa Choi, Moonkyeong Choi, Mingyu Jang, Jaekyung Kim, Jianfei Cai, Wen-Huang Cheng, Sanghoon Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09335v2.pdf)  
  Keywords: deformation, gaussian splatting, nerf, 3d gaussian, relightable, dynamic, human, ar, relighting, lighting, body, motion, high-fidelity, avatar  

### SLAM

*Showing the latest 50 out of 146 papers*

- **[Light Field Based 6DoF Tracking of Previously Unobserved Objects](https://arxiv.org/abs/2512.13007v1)**  
  Authors: Nikolai Goncharov, James L. Gray, Donald G. Dansereau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13007v1.pdf)  
  Keywords: autonomous driving, robotics, ar, semantic, tracking, reflection  
- **[GaussianHeadTalk: Wobble-Free 3D Talking Heads with Audio Driven Gaussian Splatting](https://arxiv.org/abs/2512.10939v1)**  
  Authors: Madhav Agarwal, Mingtian Zhang, Laura Sevilla-Lara, Steven McDonagh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10939v1.pdf)  
  Keywords: gaussian splatting, head, ar, mapping, tracking, fast, avatar  
- **[DeMapGS: Simultaneous Mesh Deformation and Surface Attribute Mapping via Gaussian Splatting](https://arxiv.org/abs/2512.10572v1)**  
  Authors: Shuyi Zhou, Shengze Zhong, Kenshi Takayama, Takafumi Taketomi, Takeshi Oishi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10572v1.pdf)  
  Keywords: deformation, gaussian splatting, face, ar, mapping, high-fidelity  
- **[Neural Hamiltonian Deformation Fields for Dynamic Scene Rendering](https://arxiv.org/abs/2512.10424v1)**  
  Authors: Hai-Long Qin, Sixian Wang, Guo Lu, Jincheng Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.10424v1.pdf)  
  Keywords: deformation, gaussian splatting, dynamic, ar, mapping, motion  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, human, ar, compact, mapping, recognition, localization  
- **[GTAvatar: Bridging Gaussian Splatting and Texture Mapping for Relightable and Editable Gaussian Avatars](https://arxiv.org/abs/2512.09162v1)**  
  Authors: Kelian Baert, Mae Younes, Francois Bourel, Marc Christie, Adnane Boukhayma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09162v1.pdf)  
  Keywords: gaussian splatting, relightable, head, efficient, ar, relighting, lighting, mapping, geometry, avatar  
- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: robotics, gaussian splatting, slam, 3d gaussian, ar, semantic, mapping, vr, geometry, tracking, localization, understanding, segmentation  
- **[Tracking-Guided 4D Generation: Foundation-Tracker Motion Priors for 3D Model Animation](https://arxiv.org/abs/2512.06158v1)**  
  Authors: Su Sun, Cheng Zhao, Himangi Mittal, Gaurav Mittal, Rohith Kukkala, Yingjie Victor Chen, Mei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.06158v1.pdf)  
  Keywords: gaussian splatting, dynamic, animation, ar, 4d, tracking, motion  
- **[Motion4D: Learning 3D-Consistent Motion and Semantics for 4D Scene Understanding](https://arxiv.org/abs/2512.03601v1)**  
  Authors: Haoran Zhou, Gim Hee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03601v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hrzhou2.github.io/motion4d-web/.)  
  Keywords: gaussian splatting, dynamic, ar, semantic, 4d, geometry, tracking, motion, understanding, segmentation  
- **[What Is The Best 3D Scene Representation for Robotics? From Geometric to Foundation Models](https://arxiv.org/abs/2512.03422v1)**  
  Authors: Tianchen Deng, Yue Pan, Shenghai Yuan, Dong Li, Chen Wang, Mingrui Li, Long Chen, Lihua Xie, Danwei Wang, Jingchuan Wang, Javier Civera, Hesheng Wang, Weidong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.03422v1.pdf)  
  Keywords: robotics, gaussian splatting, nerf, 3d gaussian, slam, survey, ar, semantic, mapping, localization, understanding  

### Scene Understanding

*Showing the latest 50 out of 204 papers*

- **[Geometric-Photometric Event-based 3D Gaussian Ray Tracing](https://arxiv.org/abs/2512.18640v1)**  
  Authors: Kai Kohyama, Yoshimitsu Aoki, Guillermo Gallego, Shintaro Shiba  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.18640v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, ray tracing, geometry, motion, fast, 3d reconstruction, understanding  
- **[Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://arxiv.org/abs/2512.17817v2)**  
  Authors: Yue Li, Qi Ma, Runyi Yang, Mengjiao Ma, Bin Ren, Nikola Popovic, Nicu Sebe, Theo Gevers, Luc Van Gool, Danda Pani Paudel, Martin R. Oswald  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.17817v2.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, semantic, high-fidelity, segmentation  
- **[Using Gaussian Splats to Create High-Fidelity Facial Geometry and Texture](https://arxiv.org/abs/2512.16397v1)**  
  Authors: Haodi He, Jihun Yu, Ronald Fedkiw  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.16397v1.pdf)  
  Keywords: gaussian splatting, face, nerf, relightable, human, ar, semantic, lighting, geometry, high-fidelity, segmentation  
- **[Computer vision training dataset generation for robotic environments using Gaussian splatting](https://arxiv.org/abs/2512.13411v1)**  
  Authors: Patryk Niżeniec, Marcin Iwanowski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13411v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, efficient, ar, shadow, segmentation  
- **[Light Field Based 6DoF Tracking of Previously Unobserved Objects](https://arxiv.org/abs/2512.13007v1)**  
  Authors: Nikolai Goncharov, James L. Gray, Donald G. Dansereau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.13007v1.pdf)  
  Keywords: autonomous driving, robotics, ar, semantic, tracking, reflection  
- **[Prior-Enhanced Gaussian Splatting for Dynamic Scene Reconstruction from Casual Video](https://arxiv.org/abs/2512.11356v1)**  
  Authors: Meng-Li Shih, Ying-Huan Chen, Yu-Lun Liu, Brian Curless  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.11356v1.pdf)  
  Keywords: gaussian splatting, dynamic, ar, geometry, motion, segmentation  
- **[GAINS: Gaussian-based Inverse Rendering from Sparse Multi-View Captures](https://arxiv.org/abs/2512.09925v1)**  
  Authors: Patrick Noras, Jun Myeong Choi, Didier Stricker, Pieter Peers, Roni Sengupta  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09925v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://patrickbail.github.io/gains/)  
  Keywords: gaussian splatting, ar, relighting, lighting, geometry, sparse-view, light transport, segmentation  
- **[YOPO-Nav: Visual Navigation using 3DGS Graphs from One-Pass Videos](https://arxiv.org/abs/2512.09903v1)**  
  Authors: Ryan Meegan, Adam D'Souza, Bryan Bo Cao, Shubham Jain, Kristin Dana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.09903v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, human, ar, compact, mapping, recognition, localization  
- **[OpenMonoGS-SLAM: Monocular Gaussian Splatting SLAM with Open-set Semantics](https://arxiv.org/abs/2512.08625v1)**  
  Authors: Jisang Yoo, Gyeongjin Kang, Hyun-kyu Ko, Hyeonwoo Yu, Eunbyung Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08625v1.pdf)  
  Keywords: robotics, gaussian splatting, slam, 3d gaussian, ar, semantic, mapping, vr, geometry, tracking, localization, understanding, segmentation  
- **[Zero-Splat TeleAssist: A Zero-Shot Pose Estimation Framework for Semantic Teleoperation](https://arxiv.org/abs/2512.08271v1)**  
  Authors: Srijan Dokania, Dharini Raghavan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2512.08271v1.pdf)  
  Keywords: gaussian splatting, 3d gaussian, ar, semantic, segmentation  



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