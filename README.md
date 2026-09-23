# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2026-09-23 02:25:41

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

- [3DGS Surveys](#3dgs-surveys) (10 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (203 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (317 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (376 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (85 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (419 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (48 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (402 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (215 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (24 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (122 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (168 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (212 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, high-fidelity, survey  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: ar, compression, 3d gaussian, gaussian splatting, survey  
- **[Gaussian Splatting Underwater: A Controlled Cross-Regime Study](https://arxiv.org/abs/2608.25483v1)**  
  Authors: Olaya Álvarez-Tuñón, Stella Graßhof  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.25483v1.pdf)  
  Keywords: ar, illumination, motion, 3d reconstruction, gaussian splatting, geometry, survey  
- **[UAV3DCrop: Benchmarking 3D Reconstruction in Repeated Multi-Angle UAV Crop Surveys](https://arxiv.org/abs/2608.06404v1)**  
  Authors: Junxiong Zhou, Xuechen Li, Chonghao Qiu, Lang Qiao, Xiaowei Jia, Qi Yang, Chishan Zhang, Leikun Yin, Nanshan You, Vipin Kumar, David Mulla, Ce Yang, Zhenong Jin, Licheng Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.06404v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://link-dev.github.io/UAV3DCrop/)  
  Keywords: ar, nerf, 3d gaussian, 3d reconstruction, dynamic, gaussian splatting, geometry, survey  
- **[Recent Advances and Trends in Learning-based 3D Representations](https://arxiv.org/abs/2606.04871v1)**  
  Authors: Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.04871v1.pdf)  
  Keywords: ar, medical, neural rendering, recognition, 3d gaussian, motion, vr, 3d reconstruction, compact, gaussian splatting, autonomous driving, 4d, survey  
- **[Advances in Neural 3D Mesh Texturing: A Survey](https://arxiv.org/abs/2606.00137v1)**  
  Authors: Sai Raj Kishore Perla, Hao Zhang, Ali Mahdavi-Amiri  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00137v1.pdf)  
  Keywords: survey, ar, gaussian splatting, geometry, mapping, animation  
- **[ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting](https://arxiv.org/abs/2604.11992v1)**  
  Authors: Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2604.11992v1.pdf)  
  Keywords: ar, slam, 3d gaussian, tracking, motion, 3d reconstruction, gaussian splatting, efficient, geometry, survey  
- **[Nevis Digital Twin: Photogrammetry and Immersive Visualization of Historical Sites](https://arxiv.org/abs/2603.20560v1)**  
  Authors: Alex Apffel, Huy Tran, Vuthea Chheang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.20560v1.pdf)  
  Keywords: ar, 3d gaussian, vr, gaussian splatting, survey  
- **[A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awareness](https://arxiv.org/abs/2603.17499v7)**  
  Authors: Xiucheng Wang, Yuhao Pan, Nan Cheng, Çağkan Yapar, Ruijin Sun, Zhisheng Yin, Conghao Zhou, Wenchao Xu, Yuxiang Zhang, Jianhua Zhang, Shuguang Cui, Xuemin Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2603.17499v7.pdf)  
  Keywords: ar, ray tracing, 3d gaussian, gaussian splatting, mapping, survey  
- **[Towards Next-Generation SLAM: A Survey on 3DGS-SLAM Focusing on Performance, Robustness, and Future Directions](https://arxiv.org/abs/2602.04251v1)**  
  Authors: Li Wang, Ruixuan Gong, Yumo Han, Lei Yang, Lu Yang, Ying Li, Bin Xu, Huaping Liu, Rong Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2602.04251v1.pdf)  
  Keywords: localization, ar, face, slam, 3d gaussian, tracking, motion, dynamic, gaussian splatting, efficient, mapping, survey  

### Acceleration

*Showing the latest 50 out of 203 papers*

- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: ar, fast, face, slam, semantic, 3d gaussian, gaussian splatting  
- **[Ultra-fast Neural Inference for Stochastic Gaussian Splatting Denoising](https://arxiv.org/abs/2609.25604v1)**  
  Authors: Chenxiao Hu, Hao Zhang, Yanchen Zhang, Meng Gai, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25604v1.pdf)  
  Keywords: gaussian splatting, fast, ar, head  
- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v1)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v1.pdf)  
  Keywords: ar, nerf, real-time rendering, 3d gaussian, gaussian splatting, geometry, sparse-view  
- **[LiteTex-GS: Fast and Lightweight Texturing for Gaussian Splatting](https://arxiv.org/abs/2609.23380v1)**  
  Authors: Zhiwei Li, Yijia Guo, Yishi Lu, Liwen Hu, Hong Rao, Shengbo Chen, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23380v1.pdf)  
  Keywords: ar, fast, lightweight, head, compact, gaussian splatting, geometry  
- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: localization, ar, fast, lighting, slam, 3d gaussian, tracking, motion, dynamic, gaussian splatting, geometry, robotics, mapping  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: outdoor, ar, fast, illumination, human, dynamic, gaussian splatting, 4d  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, fast, compression, deformation, efficient, lightweight, gaussian splatting, high-fidelity  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: ar, fast, lightweight, 3d gaussian, head, gaussian splatting, high-fidelity, geometry  
- **[GSComplete: Gaussian Splat Completion with 2D Diffusion Priors](https://arxiv.org/abs/2609.08449v1)**  
  Authors: Elias Brugger, Philipp Erler, Stefan Ohrhallinger, Paul Guerrero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08449v1.pdf)  
  Keywords: ar, high-fidelity, fast  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, fast, efficient, slam, 3d gaussian, tracking, motion, gaussian splatting, high-fidelity  

### Applications

*Showing the latest 50 out of 995 papers*

- **[φ-RIE: From Photorealistic Reconstruction to Interactive Environments](https://arxiv.org/abs/2609.26795v1)**  
  Authors: Runyi Yang, Deheng Zhang, Xiaoye Wang, Kanzhi Wu, Lei Sun, Ajad Chhatkuli, Kunyu Peng, Luc Van Gool, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26795v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: ar, fast, face, slam, semantic, 3d gaussian, gaussian splatting  
- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: outdoor, ar, 3d gaussian, motion, gaussian splatting  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, geometry  
- **[Robust, Estimator-Agnostic Dynamic 3DGS Compression](https://arxiv.org/abs/2609.25633v1)**  
  Authors: Chenjunjie Wang, Zixi Huang, Yao Wang, Jona Ballé  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25633v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wcjj1236.github.io/d3dgs-benchmark.)  
  Keywords: ar, compression, 3d gaussian, motion, dynamic  
- **[Ultra-fast Neural Inference for Stochastic Gaussian Splatting Denoising](https://arxiv.org/abs/2609.25604v1)**  
  Authors: Chenxiao Hu, Hao Zhang, Yanchen Zhang, Meng Gai, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25604v1.pdf)  
  Keywords: gaussian splatting, fast, ar, head  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: ar, face, neural rendering, semantic, 3d reconstruction, gaussian splatting  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, high-fidelity, survey  
- **[BayesianGS-SLAM: Uncertainty-Aware Neural Rendering SLAM via Probabilistic Formulation](https://arxiv.org/abs/2609.24140v1)**  
  Authors: Kyeongsu Kang, Seongbo Ha, Sibaek Lee, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24140v1.pdf)  
  Keywords: ar, neural rendering, slam, 3d gaussian, tracking, gaussian splatting, mapping  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  

### Avatar Generation

*Showing the latest 50 out of 317 papers*

- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: ar, fast, face, slam, semantic, 3d gaussian, gaussian splatting  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, geometry  
- **[Ultra-fast Neural Inference for Stochastic Gaussian Splatting Denoising](https://arxiv.org/abs/2609.25604v1)**  
  Authors: Chenxiao Hu, Hao Zhang, Yanchen Zhang, Meng Gai, Guoping Wang, Sheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25604v1.pdf)  
  Keywords: gaussian splatting, fast, ar, head  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: ar, face, neural rendering, semantic, 3d reconstruction, gaussian splatting  
- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, high-fidelity, survey  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[LiteTex-GS: Fast and Lightweight Texturing for Gaussian Splatting](https://arxiv.org/abs/2609.23380v1)**  
  Authors: Zhiwei Li, Yijia Guo, Yishi Lu, Liwen Hu, Hong Rao, Shengbo Chen, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23380v1.pdf)  
  Keywords: ar, fast, lightweight, head, compact, gaussian splatting, geometry  
- **[VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction](https://arxiv.org/abs/2609.23049v1)**  
  Authors: Haolin Yu, Jiadong Tang, YiXian Wang, Yu Gao, Shi He, Zhilin Lai, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23049v1.pdf)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, autonomous driving, mapping  
- **[Kinematic Interface for the Wild: Modular Bimanual Loco-Manipulation Capture from 360$^{\circ}$ Cameras Alone](https://arxiv.org/abs/2609.22809v1)**  
  Authors: Benjamin Yang, Weiying Wang, Shenggao Li, Keming Yan, Sasha Wilkinson, Zelin Wang, Yip Fun Yeung, Lingfeng Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22809v1.pdf)  
  Keywords: localization, ar, face, 3d gaussian, tracking, head  
- **[2D GauSS-MI: Efficient Active Scene Reconstruction with Balanced Visual and Geometric Quality](https://arxiv.org/abs/2609.21516v1)**  
  Authors: Yuhan Xie, Jia Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21516v1.pdf)  
  Keywords: ar, face, gaussian splatting, efficient, mapping  

### Dynamic Scene

*Showing the latest 50 out of 376 papers*

- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: outdoor, ar, 3d gaussian, motion, gaussian splatting  
- **[Robust, Estimator-Agnostic Dynamic 3DGS Compression](https://arxiv.org/abs/2609.25633v1)**  
  Authors: Chenjunjie Wang, Zixi Huang, Yao Wang, Jona Ballé  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25633v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wcjj1236.github.io/d3dgs-benchmark.)  
  Keywords: ar, compression, 3d gaussian, motion, dynamic  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[Elevator-VIGS: Separating Elevator Motion from Robot Motion in Visual-Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2609.23491v1)**  
  Authors: Rui Zhou, Zihan Zhu, Wei Zhang, Zizhou Luo, Norbert Haala, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ruizhou-cn.github.io/elevator-vigs/.)  
  Keywords: ar, slam, 3d gaussian, tracking, motion, gaussian splatting, mapping  
- **[LINGO: Latent Initialization and Gradient Optimization for Sparse-view X-ray Novel View Synthesis and CT Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2609.22849v1)**  
  Authors: Lifeng Xing, Dequan Jin, Kunpeng Bu, Peigeng He, Shihui Ying  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22849v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting, sparse-view  
- **[AirSplan: Risk-Aware Motion Planning for Quadrotors in Cluttered 3D Gaussian Splats](https://arxiv.org/abs/2609.21226v1)**  
  Authors: Seth Isaacson, William Hong, Katherine A. Skinner, Ram Vasudevan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21226v1.pdf)  
  Keywords: ar, 3d gaussian, motion, gaussian splatting, high-fidelity, geometry  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v2)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v2.pdf)  
  Keywords: ar, dynamic, gaussian splatting, large scene, 4d, sparse-view  
- **[Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning](https://arxiv.org/abs/2609.21112v1)**  
  Authors: Beichen Wang, Yuen-Hei Yeung, V. R. Sridhar Devarakonda, Xuesu Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21112v1.pdf)  
  Keywords: ar, 3d gaussian, human, dynamic, gaussian splatting, high-fidelity  
- **[SplashSplat: Reconstructing Splashing Liquids from Real-World Multi-View Videos](https://arxiv.org/abs/2609.20818v1)**  
  Authors: Peiyu Liu, Dingxi Zhang, Federico Tombari, Marc Pollefeys, Christina Tsalicoglou, Daniel Barath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20818v1.pdf)  
  Keywords: ar, face, motion, dynamic, gaussian splatting, geometry  
- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: ar, lighting, shadow, slam, illumination, tracking, motion, dynamic, gaussian splatting, mapping  

### Few-shot

*Showing the latest 50 out of 85 papers*

- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v1)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v1.pdf)  
  Keywords: ar, nerf, real-time rendering, 3d gaussian, gaussian splatting, geometry, sparse-view  
- **[D3GS: Depth, DINO, and RGB Diffusion Co-Guided 3D Gaussian Splatting for Sparse-View Reconstruction](https://arxiv.org/abs/2609.22941v1)**  
  Authors: Yunqi Gao, Zhanfeng Liao, Hanzhang Tu, Zhaoqi Su, Guoqing Zheng, Songtao Wang, Hongwen Zhang, Zhou Xue, Leyuan Liu, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22941v1.pdf)  
  Keywords: ar, nerf, 3d gaussian, gaussian splatting, geometry, sparse-view  
- **[LINGO: Latent Initialization and Gradient Optimization for Sparse-view X-ray Novel View Synthesis and CT Reconstruction with 3D Gaussian Splatting](https://arxiv.org/abs/2609.22849v1)**  
  Authors: Lifeng Xing, Dequan Jin, Kunpeng Bu, Peigeng He, Shihui Ying  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22849v1.pdf)  
  Keywords: ar, 3d gaussian, dynamic, gaussian splatting, sparse-view  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v2)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v2.pdf)  
  Keywords: ar, dynamic, gaussian splatting, large scene, 4d, sparse-view  
- **[Geometry beneath the Waves: Dense Priors for Sparse-View Underwater 3D Gaussian Splatting](https://arxiv.org/abs/2609.18737v1)**  
  Authors: Harvey Caldeira, Haoran Wang, Guoxi Huang, Shaoyu Cai, Rachel Fu, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18737v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, gaussian splatting, geometry, sparse-view  
- **[CADSplat: Sparse-View 3D Gaussian Splatting Aided by CAD Models for Robust, Photorealistic Digital-Twin Reconstruction](https://arxiv.org/abs/2609.18473v1)**  
  Authors: Kristof Overdulve, Lode Jorissen, Nick Michiels  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18473v1.pdf)  
  Keywords: ar, deformation, few-shot, face, 3d gaussian, gaussian splatting, sparse-view  
- **[Bi-FlowGS: Bridging Generative View Completion and Gaussian Geometry through Bidirectional Flow Co-Refinement](https://arxiv.org/abs/2609.17039v1)**  
  Authors: Yuetong Wang, Jinsheng Quan, Yi Yang, Yawei Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17039v1.pdf)  
  Keywords: ar, 3d gaussian, motion, gaussian splatting, geometry, sparse-view  
- **[VS-Splat: Voxel-Selective feed-forward Gaussian Splatting for end-to-end 3D object reconstruction from sparse-views](https://arxiv.org/abs/2609.12343v1)**  
  Authors: Yunsu Jeong, Hyuk Heo, Youngsang Kwak, Jaehwa Kwak, Il Yong Chun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.12343v1.pdf)  
  Keywords: gaussian splatting, ar, sparse-view  
- **[Shape-guided Gaussian Splatting for Sparse-View X-ray 3D Reconstruction](https://arxiv.org/abs/2609.10376v1)**  
  Authors: Pranav Poudel, Florence Dell'Aniello Picard, Nairouz Shehata, Frédéric Lavoie, Herve Lombaert  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10376v1.pdf)  
  Keywords: ar, 3d gaussian, 3d reconstruction, gaussian splatting, geometry, sparse-view  
- **[TV-SGS: Gaussian Splatting with Geometric Information Propagation via Tensor Voting under sparse views](https://arxiv.org/abs/2609.07734v1)**  
  Authors: Harish N Sathishchandra, Philippos Mordohai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07734v1.pdf)  
  Keywords: gaussian splatting, sparse view, geometry, ar  

### Geometry Reconstruction

*Showing the latest 50 out of 419 papers*

- **[φ-RIE: From Photorealistic Reconstruction to Interactive Environments](https://arxiv.org/abs/2609.26795v1)**  
  Authors: Runyi Yang, Deheng Zhang, Xiaoye Wang, Kanzhi Wu, Lei Sun, Ajad Chhatkuli, Kunyu Peng, Luc Van Gool, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26795v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, geometry  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: ar, face, neural rendering, semantic, 3d reconstruction, gaussian splatting  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[GAPS: Generative Active Pseudo-view Selection for Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2609.23436v1)**  
  Authors: Hongfei Zhu, Haochen Deng, Sitao Zhang, Ling Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23436v1.pdf)  
  Keywords: ar, nerf, real-time rendering, 3d gaussian, gaussian splatting, geometry, sparse-view  
- **[LiteTex-GS: Fast and Lightweight Texturing for Gaussian Splatting](https://arxiv.org/abs/2609.23380v1)**  
  Authors: Zhiwei Li, Yijia Guo, Yishi Lu, Liwen Hu, Hong Rao, Shengbo Chen, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23380v1.pdf)  
  Keywords: ar, fast, lightweight, head, compact, gaussian splatting, geometry  
- **[GrapeSplat: Geometry-Grounded Reconstruction via Amalgamated Pose-Free Encoding for Feed-Forward 3D Gaussian Splatting](https://arxiv.org/abs/2609.23182v1)**  
  Authors: Si-Yu Lu, Yung-Yao Chen, Yi Jan Chen, Shang-Lin Li, Ching-Chan Liao, Wen-Huang Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23182v1.pdf)  
  Keywords: gaussian splatting, ar, geometry, 3d gaussian  
- **[D3GS: Depth, DINO, and RGB Diffusion Co-Guided 3D Gaussian Splatting for Sparse-View Reconstruction](https://arxiv.org/abs/2609.22941v1)**  
  Authors: Yunqi Gao, Zhanfeng Liao, Hanzhang Tu, Zhaoqi Su, Guoqing Zheng, Songtao Wang, Hongwen Zhang, Zhou Xue, Leyuan Liu, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22941v1.pdf)  
  Keywords: ar, nerf, 3d gaussian, gaussian splatting, geometry, sparse-view  
- **[AirSplan: Risk-Aware Motion Planning for Quadrotors in Cluttered 3D Gaussian Splats](https://arxiv.org/abs/2609.21226v1)**  
  Authors: Seth Isaacson, William Hong, Katherine A. Skinner, Ram Vasudevan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21226v1.pdf)  
  Keywords: ar, 3d gaussian, motion, gaussian splatting, high-fidelity, geometry  
- **[SplashSplat: Reconstructing Splashing Liquids from Real-World Multi-View Videos](https://arxiv.org/abs/2609.20818v1)**  
  Authors: Peiyu Liu, Dingxi Zhang, Federico Tombari, Marc Pollefeys, Christina Tsalicoglou, Daniel Barath  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20818v1.pdf)  
  Keywords: ar, face, motion, dynamic, gaussian splatting, geometry  

### Large Scene

- **[Skytopia: Monocular Drone Navigation with Action-Conditioned Latent World Models](https://arxiv.org/abs/2609.26007v1)**  
  Authors: Yuhang Zhang, Rangya Zhang, Yujing Shang, Zhuoyuan Yu, Weiying Wang, Steven Yang, Qingsong Yan, Chao Yan, Mir Feroskhan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26007v1.pdf)  
  Keywords: outdoor, ar, 3d gaussian, motion, gaussian splatting  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, geometry  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, high-fidelity, mapping  
- **[4DGS-Fixer: Generative Sparse-View 4D Gaussian Splatting with Iterative Refinement Guided by Video Diffusion Priors](https://arxiv.org/abs/2609.21176v2)**  
  Authors: Haitao Huang, Shenghao Zhao, Boyuan Tian, Shin-Fang Chng, Songlin Yang, Sheila Lim, Huangying Zhan, Yi Xu, Anyi Rao, Frank Guan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21176v2.pdf)  
  Keywords: ar, dynamic, gaussian splatting, large scene, 4d, sparse-view  
- **[The Neverwhere Visual Parkour Benchmark Suite](https://arxiv.org/abs/2609.16443v1)**  
  Authors: Ziyu Chen, Henghui Bao, Haoran Chang, Alan Yu, Ran Choi, Kai McClennen, Gio Huh, Kevin Yang, Ri-Zhao Qiu, Yajvan Ravan, John J. Leonard, Xiaolong Wang, Phillip Isola, Ge Yang, Yue Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16443v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ziyc.github.io/neverwhere-bench/.)  
  Keywords: outdoor, ar, 3d gaussian, motion, gaussian splatting  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: outdoor, ar, fast, illumination, human, dynamic, gaussian splatting, 4d  
- **[LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting](https://arxiv.org/abs/2609.10095v1)**  
  Authors: Donghun Ryu, Minhyeok Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.10095v1.pdf)  
  Keywords: outdoor, ar, nerf, 3d gaussian, head, compact, gaussian splatting  
- **[M$^3$ISR: A Multi-Modal Multi-View Benchmark for 3D/4D Gaussian Splatting and Feedforward Compression](https://arxiv.org/abs/2608.22465v1)**  
  Authors: Xinhui Liu, Lei Liu, Zhenghao Chen, Lebin Zhou, Wei Wang, Wei Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.22465v1.pdf)  
  Keywords: outdoor, segmentation, ar, compression, semantic, motion, dynamic, gaussian splatting, high-fidelity, geometry, 4d  
- **[CoMVS-GS: Collaborative Multi-View Stereo and 3D Gaussian Splatting for Surface Reconstruction](https://arxiv.org/abs/2608.18413v1)**  
  Authors: Shihan Chen, Junjing Zhang, Qingsong Yan, Haibing Liu, Haofan Ren, Fei Deng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.18413v1.pdf)  
  Keywords: outdoor, ar, face, 3d gaussian, motion, compact, gaussian splatting, efficient, geometry  
- **[GS-CPE: Unified 6-Degree-of-Freedom Camera Pose Estimation via 3D Gaussian Splatting](https://arxiv.org/abs/2608.10938v2)**  
  Authors: Huaiyuan Weng, Chul Min Yeum, Su-Min Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.10938v2.pdf)  
  Keywords: outdoor, localization, fast, ar, 3d gaussian, gaussian splatting, geometry  

### Model Compression

*Showing the latest 50 out of 402 papers*

- **[Robust, Estimator-Agnostic Dynamic 3DGS Compression](https://arxiv.org/abs/2609.25633v1)**  
  Authors: Chenjunjie Wang, Zixi Huang, Yao Wang, Jona Ballé  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25633v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wcjj1236.github.io/d3dgs-benchmark.)  
  Keywords: ar, compression, 3d gaussian, motion, dynamic  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[LiteTex-GS: Fast and Lightweight Texturing for Gaussian Splatting](https://arxiv.org/abs/2609.23380v1)**  
  Authors: Zhiwei Li, Yijia Guo, Yishi Lu, Liwen Hu, Hong Rao, Shengbo Chen, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23380v1.pdf)  
  Keywords: ar, fast, lightweight, head, compact, gaussian splatting, geometry  
- **[Quality Assessment of 3D Gaussian Splatting: Distortions, Benchmarks, and Open Challenges](https://arxiv.org/abs/2609.23027v1)**  
  Authors: Shuai Liu, Binqiang Liu, Qingyu Mao, Jiacong Chen, Yongsheng Liang, Youneng Bao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23027v1.pdf)  
  Keywords: ar, compression, 3d gaussian, gaussian splatting, survey  
- **[Compressing 3D Gaussian Splatting via Cross-Representation Priors](https://arxiv.org/abs/2609.23005v1)**  
  Authors: Yezheng Zhang, Huanxiong Liang, Chuqin Zhou, Guo Lu, Wenjun Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23005v1.pdf)  
  Keywords: gaussian splatting, ar, compression, 3d gaussian  
- **[2D GauSS-MI: Efficient Active Scene Reconstruction with Balanced Visual and Geometric Quality](https://arxiv.org/abs/2609.21516v1)**  
  Authors: Yuhan Xie, Jia Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21516v1.pdf)  
  Keywords: ar, face, gaussian splatting, efficient, mapping  
- **[VoxelTTO: Voxel-Aligned Feed-Forward 3D Gaussian Splatting with Test-Time Optimization](https://arxiv.org/abs/2609.21498v1)**  
  Authors: Yibin Zhao, Yihan Pan, Yangwen Li, Jun Nan, Jianjun Yi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21498v1.pdf)  
  Keywords: gaussian splatting, lightweight, 3d gaussian, ar  
- **[PhGS: Post-Hoc Pruning and Refinement of Single-View Feed-Forward 3D Gaussian Reconstructions](https://arxiv.org/abs/2609.20623v1)**  
  Authors: Rinto Yagawa, Han Cheng, Dieter Schmalstieg, Hideo Saito, Shohei Mori  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20623v1.pdf)  
  Keywords: ar, lightweight, 3d gaussian, compact, gaussian splatting  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: ar, relightable, lighting, semantic, illumination, gaussian splatting, efficient, geometry  
- **[GAPrompt++: Multi-Granular Geometry-Aware Point Cloud Prompt for 3D Vision Model](https://arxiv.org/abs/2609.19716v1)**  
  Authors: Zixiang Ai, Zhenyu Cui, Yufei Guo, Wenwen Qiang, Lei Chen, Jiwen Lu, Jiahuan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19716v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, gaussian splatting, efficient, geometry  

### Quality Enhancement

*Showing the latest 50 out of 215 papers*

- **[OpenFlyScan: A Quality-Guided Aerial Reconstruction System for Consumer Drones](https://arxiv.org/abs/2609.24253v1)**  
  Authors: Zhongrui You, Zhen Li, Junli Liu, Zhigang Wang, Bin Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24253v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://openflyscan.github.io/.)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, high-fidelity, survey  
- **[GARO: Geometry-Aware Redundancy Optimization for Real-Time and High-Fidelity Dynamic Gaussian Splatting](https://arxiv.org/abs/2609.23509v1)**  
  Authors: Huiwen Xue, Kaixing Zhao, Zuheng Ming, Tingcheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23509v1.pdf)  
  Keywords: ar, face, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, high-fidelity, mapping  
- **[AirSplan: Risk-Aware Motion Planning for Quadrotors in Cluttered 3D Gaussian Splats](https://arxiv.org/abs/2609.21226v1)**  
  Authors: Seth Isaacson, William Hong, Katherine A. Skinner, Ram Vasudevan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21226v1.pdf)  
  Keywords: ar, 3d gaussian, motion, gaussian splatting, high-fidelity, geometry  
- **[Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning](https://arxiv.org/abs/2609.21112v1)**  
  Authors: Beichen Wang, Yuen-Hei Yeung, V. R. Sridhar Devarakonda, Xuesu Xiao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21112v1.pdf)  
  Keywords: ar, 3d gaussian, human, dynamic, gaussian splatting, high-fidelity  
- **[Deformable 2D Gaussian Splatting for Efficient 4K Video Compression](https://arxiv.org/abs/2609.14129v1)**  
  Authors: Chenhao Zhang, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14129v1.pdf)  
  Keywords: ar, fast, compression, deformation, efficient, lightweight, gaussian splatting, high-fidelity  
- **[CVT-GS: Learning to Simplify 3D Gaussian Splatting with Centroidal Voronoi Tessellation](https://arxiv.org/abs/2609.08730v1)**  
  Authors: Bingxian Li, Yilong Li, Jingliang Peng, Peng-Shuai Wang, Fei Zhu, Guozheng Li, Chi Harold Liu, Guoping Wang, Bo Pang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08730v1.pdf)  
  Keywords: ar, fast, lightweight, 3d gaussian, head, gaussian splatting, high-fidelity, geometry  
- **[GSComplete: Gaussian Splat Completion with 2D Diffusion Priors](https://arxiv.org/abs/2609.08449v1)**  
  Authors: Elias Brugger, Philipp Erler, Stefan Ohrhallinger, Paul Guerrero  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.08449v1.pdf)  
  Keywords: ar, high-fidelity, fast  
- **[LightSplat: Real-Time High-Fidelity 3D Gaussian SLAM with Loop Closure](https://arxiv.org/abs/2609.07274v1)**  
  Authors: Junze Bao, Ye Gao, Yiming Huang, Xiaolong Yu, Chen Dong, Qing Gao, Wei Wang, Jinhu Lü  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07274v1.pdf)  
  Keywords: ar, fast, efficient, slam, 3d gaussian, tracking, motion, gaussian splatting, high-fidelity  
- **[Generalizable 6D Pose Estimation of Textureless Objects with Planar-based Gaussian Splatting](https://arxiv.org/abs/2609.07231v1)**  
  Authors: Jie Lu, Hengtan Zhang, Li Gong, Pengpeng Wang, Xianjia Yu, Jinxiang Deng, Tomi Westerlund, Zhongxue Gan, Lirong Zheng, Zhuo Zou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07231v1.pdf)  
  Keywords: ar, 3d gaussian, gaussian splatting, high-fidelity, geometry  

### Ray Tracing

- **[Differentiable Voronoi Ray Tracing Beyond Rasterization Speeds](https://arxiv.org/abs/2608.17682v1)**  
  Authors: Bernardo Taveira, Carl Lindström, Joakim Johnander, Fredrik Kahl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17682v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://research.zenseact.com/publications/vorotracing)  
  Keywords: ar, fast, nerf, real-time rendering, ray tracing, face, 3d gaussian, motion, compact, gaussian splatting  
- **[3D Gaussian Accelerated Ray Tracing: Fast training through particle-based backward propagation](https://arxiv.org/abs/2608.17298v1)**  
  Authors: Laurent Vit, Oliver Batchelor, Richard Green  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.17298v1.pdf)  
  Keywords: reflection, ar, fast, nerf, ray tracing, 3d gaussian, compact, shadow, gaussian splatting, efficient, mapping  
- **[Inter-Reflective Gaussian Splatting for Robust and Efficient Inverse Rendering](https://arxiv.org/abs/2607.22780v1)**  
  Authors: Chun Gu, Xiaofei Wei, Zixuan Zeng, Yuxuan Yao, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.22780v1.pdf)  
  Keywords: reflection, ar, lighting, ray tracing, face, illumination, relighting, gaussian splatting, efficient  
- **[HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing](https://arxiv.org/abs/2607.15806v1)**  
  Authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2607.15806v1.pdf)  
  Keywords: reflection, ar, ray tracing, face, 3d gaussian, human, motion, dynamic, gaussian splatting, high-fidelity, geometry  
- **[GRay: Ray Tracing 3D Gaussians Near the Speed of Splats](https://arxiv.org/abs/2606.30869v1)**  
  Authors: Yohan Poirier-Ginter, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30869v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/gray.)  
  Keywords: ar, fast, ray tracing, 3d gaussian, gaussian splatting  
- **[Editable Physically-based Reflections in Raytraced Gaussian Radiance Fields](https://arxiv.org/abs/2606.30861v1)**  
  Authors: Yohan Poirier-Ginter, Jeffrey Hu, Jean-François Lalonde, George Drettakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.30861v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://repo-sam.inria.fr/nerphys/editable-gaussian-reflections/)  
  Keywords: reflection, ar, fast, real-time rendering, ray tracing, path tracing, 3d gaussian, gaussian splatting, efficient, geometry  
- **[Mesh2GS: White-Box 3DGS Construction via Plenoptic Sampling](https://arxiv.org/abs/2606.21898v1)**  
  Authors: Haoran Zhu, Youcheng Cai, Huangsheng Du, Jingyang Meng, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.21898v1.pdf)  
  Keywords: ar, global illumination, 3d gaussian, illumination, 3d reconstruction, gaussian splatting, efficient, geometry  
- **[Continuous Splatting meets Retinex: Continuous Gaussian Splatting and Implicit Reflectance Modeling for Low-Light Image Enhancement](https://arxiv.org/abs/2606.16159v1)**  
  Authors: Yuhan Chen, Yicui Shi, Guofa Li, Wenxuan Yu, Ying Fang, Guangrui Bai, Wenbo Chu, Keqiang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.16159v1.pdf)  
  Keywords: ar, global illumination, illumination, gaussian splatting, high-fidelity  
- **[RFDT-Channel: RGB-LiDAR-Based RF Digital Twin Scene Construction for 28 GHz Indoor Ray-Tracing Channel Simulation](https://arxiv.org/abs/2606.01261v1)**  
  Authors: Chengyang Yao, Cunhua Pan, Jiaming Zeng, Yuquan Sun, Haoyang Weng, Haojian Wang, Hong Ren, Jiangzhou Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.01261v1.pdf)  
  Keywords: reflection, ar, ray tracing, 3d gaussian, semantic, segmentation, gaussian splatting, efficient, geometry  
- **[Directed Distance Fields for Constant-Time Ray Queries on Gaussian Splatting](https://arxiv.org/abs/2606.00817v1)**  
  Authors: Subhankar MIshra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2606.00817v1.pdf)  
  Keywords: ar, fast, face, global illumination, 3d gaussian, illumination, shadow, gaussian splatting  

### Relighting

*Showing the latest 50 out of 122 papers*

- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: ar, lighting, shadow, slam, illumination, tracking, motion, dynamic, gaussian splatting, mapping  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: ar, relightable, lighting, semantic, illumination, gaussian splatting, efficient, geometry  
- **[RGS: Reflection-aware Gaussian Splatting via Learning Geometry Continuity for Reflective Objects](https://arxiv.org/abs/2609.19421v1)**  
  Authors: Xiaobiao Du, Yida Wang, Cheng Bi, Kun Zhan, Xin Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19421v1.pdf)  
  Keywords: reflection, ar, face, 3d gaussian, gaussian splatting, geometry  
- **[PanoGS-SLAM: Panoramic 3D Gaussian Splatting SLAM](https://arxiv.org/abs/2609.17387v1)**  
  Authors: Yongqi Mao, Hao Shi, Yufan Zhang, Zhonghua Yi, Xiangfei Guo, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.17387v1.pdf)  
  Keywords: localization, ar, fast, lighting, slam, 3d gaussian, tracking, motion, dynamic, gaussian splatting, geometry, robotics, mapping  
- **[Racing in Volume with Flow Ensembles](https://arxiv.org/abs/2609.16310v1)**  
  Authors: Saswat Subhajyoti Mallick, Riu Cherdchusakulchai, Marc Ruiz Olle, Albert Mosella-Montoro, Jose Ribeiro-Gomes, Francisco Vicente Carrasco, Fernando De la Torre  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://humansensinglab.github.io/monaco4d/.)  
  Keywords: outdoor, ar, fast, illumination, human, dynamic, gaussian splatting, 4d  
- **[Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models](https://arxiv.org/abs/2609.04381v1)**  
  Authors: Chenxi Tao, Seung-Kyum Choi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.04381v1.pdf)  
  Keywords: ar, lighting, recognition, 3d gaussian, gaussian splatting, geometry, robotics  
- **[Sparse auto-regressive modeling for scene generation from multi-view images](https://arxiv.org/abs/2609.03931v1)**  
  Authors: Thomas Lucas, Maxime Pietrantoni, Philippe Weinzaepfel, Wonjune Cho, Bardienus Pieter Duisterhof, Vincent Leroy, Jerome Revaud  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.03931v1.pdf)  
  Keywords: ar, lighting, 3d gaussian, compact, gaussian splatting, efficient  
- **[LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting](https://arxiv.org/abs/2609.02543v1)**  
  Authors: Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.02543v1.pdf)  
  Keywords: ar, lighting, 3d gaussian, illumination, relighting, gaussian splatting, efficient  
- **[ChainSplat: A Physics-Inspired Screw-Theoretic Model for Learning Deformable Linear Object Dynamics from Multi-View RGB Videos](https://arxiv.org/abs/2608.28570v1)**  
  Authors: Seungyeon Kim, Noémie Jaquier  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28570v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://chainsplat.github.io.)  
  Keywords: ar, lighting, compact, dynamic, gaussian splatting, high-fidelity, geometry  
- **[WilLaGS: Latent-Conditional 3D Appearance Fields for Robust Gaussian Splatting In-the-Wild](https://arxiv.org/abs/2608.28240v2)**  
  Authors: Yuhao Bai, Qianqiu Tan, Lilong Chen, Huanhuan Lv, Lijun Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2608.28240v2.pdf)  
  Keywords: ar, real-time rendering, 3d gaussian, illumination, dynamic, gaussian splatting, high-fidelity  

### SLAM

*Showing the latest 50 out of 168 papers*

- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: ar, fast, face, slam, semantic, 3d gaussian, gaussian splatting  
- **[Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking](https://arxiv.org/abs/2609.25746v1)**  
  Authors: Edward Beng Wai Tan, Siew-Kei Lam  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25746v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, geometry  
- **[BayesianGS-SLAM: Uncertainty-Aware Neural Rendering SLAM via Probabilistic Formulation](https://arxiv.org/abs/2609.24140v1)**  
  Authors: Kyeongsu Kang, Seongbo Ha, Sibaek Lee, Hyeonwoo Yu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.24140v1.pdf)  
  Keywords: ar, neural rendering, slam, 3d gaussian, tracking, gaussian splatting, mapping  
- **[Elevator-VIGS: Separating Elevator Motion from Robot Motion in Visual-Inertial Gaussian Splatting SLAM](https://arxiv.org/abs/2609.23491v1)**  
  Authors: Rui Zhou, Zihan Zhu, Wei Zhang, Zizhou Luo, Norbert Haala, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23491v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ruizhou-cn.github.io/elevator-vigs/.)  
  Keywords: ar, slam, 3d gaussian, tracking, motion, gaussian splatting, mapping  
- **[VDGS: Visibility-Driven Large-Scale 3D Gaussian Splatting for Aerial Scene Reconstruction](https://arxiv.org/abs/2609.23049v1)**  
  Authors: Haolin Yu, Jiadong Tang, YiXian Wang, Yu Gao, Shi He, Zhilin Lai, Yi Yang, Mengyin Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.23049v1.pdf)  
  Keywords: ar, face, 3d gaussian, gaussian splatting, autonomous driving, mapping  
- **[Kinematic Interface for the Wild: Modular Bimanual Loco-Manipulation Capture from 360$^{\circ}$ Cameras Alone](https://arxiv.org/abs/2609.22809v1)**  
  Authors: Benjamin Yang, Weiying Wang, Shenggao Li, Keming Yan, Sasha Wilkinson, Zelin Wang, Yip Fun Yeung, Lingfeng Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.22809v1.pdf)  
  Keywords: localization, ar, face, 3d gaussian, tracking, head  
- **[2D GauSS-MI: Efficient Active Scene Reconstruction with Balanced Visual and Geometric Quality](https://arxiv.org/abs/2609.21516v1)**  
  Authors: Yuhan Xie, Jia Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21516v1.pdf)  
  Keywords: ar, face, gaussian splatting, efficient, mapping  
- **[Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization](https://arxiv.org/abs/2609.21347v1)**  
  Authors: Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.21347v1.pdf)  
  Keywords: outdoor, ar, face, slam, 3d gaussian, tracking, gaussian splatting, high-fidelity, mapping  
- **[RawSLAM: Online HDR Gaussian SLAM from Linear Radiance](https://arxiv.org/abs/2609.20589v1)**  
  Authors: Marina Orozco González, Luis Merino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20589v1.pdf)  
  Keywords: ar, lighting, shadow, slam, illumination, tracking, motion, dynamic, gaussian splatting, mapping  
- **[EliGSiR: Continual RGB-D Mapping with Gaussian Splatting under Bounded Compute](https://arxiv.org/abs/2609.20348v1)**  
  Authors: Björn Ellensohn, Elmar Rueckert, Christian Rauch  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20348v1.pdf)  
  Keywords: ar, slam, 3d gaussian, gaussian splatting, geometry, mapping  

### Scene Understanding

*Showing the latest 50 out of 212 papers*

- **[ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards](https://arxiv.org/abs/2609.26315v1)**  
  Authors: Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.26315v1.pdf)  
  Keywords: ar, fast, face, slam, semantic, 3d gaussian, gaussian splatting  
- **[Agentic Building-Aware Satellite Gaussian Splatting for Auditable Urban DSM Reconstruction](https://arxiv.org/abs/2609.25578v1)**  
  Authors: Wentao Sun, Zhengsen Xu, Yiping Chen, John S. Zelek, Jonathan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.25578v1.pdf)  
  Keywords: ar, face, neural rendering, semantic, 3d reconstruction, gaussian splatting  
- **[CoRef-GS: Cooperative Referring Gaussian Splatting for Multi-Agent Scene Understanding](https://arxiv.org/abs/2609.20586v1)**  
  Authors: Zhikun Zhou, Kunyu Peng, Runyi Yang, Junhao Cai, Di Wen, Ruiping Liu, Danda Pani Paudel, Yi Zhou, Luc Van Gool, Kailun Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.20586v1.pdf)  
  Keywords: gaussian splatting, ar, understanding, semantic  
- **[GS-PI: An Optimization-Decoupled Appearance Decomposition Approach for Generating PBR Gaussian Assets](https://arxiv.org/abs/2609.19907v1)**  
  Authors: Jieting Xu, Rengan Xie, Zijian Huang, Zehui Jin, Rui Wang, Yuchi Huo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19907v1.pdf)  
  Keywords: ar, relightable, lighting, semantic, illumination, gaussian splatting, efficient, geometry  
- **[GAPrompt++: Multi-Granular Geometry-Aware Point Cloud Prompt for 3D Vision Model](https://arxiv.org/abs/2609.19716v1)**  
  Authors: Zixiang Ai, Zhenyu Cui, Yufei Guo, Wenwen Qiang, Lei Chen, Jiwen Lu, Jiahuan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19716v1.pdf)  
  Keywords: ar, 3d gaussian, semantic, gaussian splatting, efficient, geometry  
- **[ParticleSplat: Self-supervised Object-centric Latent Particle Splatting](https://arxiv.org/abs/2609.19463v1)**  
  Authors: Lyuxing He, Daniel Guo, Elizabeth Terveen, Deepak Pathak, David Held, Tal Daniel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.19463v1.pdf)  
  Keywords: gaussian splatting, ar, semantic, 3d gaussian  
- **[MoQSplat: Adaptive Progressive Streaming of 3D Gaussian Splatting via MoQ](https://arxiv.org/abs/2609.18624v1)**  
  Authors: Emanuele Artioli, Mohammadreza Ghafari, Md Tariqul Islam, Farzad Tashtarian, Christian Rothenberg, Christian Timmerer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.18624v1.pdf)  
  Keywords: ar, semantic, 3d gaussian, head, dynamic, gaussian splatting  
- **[SceneBench: A Hierarchical Benchmark for Vision-Language Understanding of 3D Scenes](https://arxiv.org/abs/2609.16233v1)**  
  Authors: Anubhav Khanal, Prabigya Acharya, Roshni Poudel, Sujan Kapali, Bigyan Bhatta, Pramish Paudel, Francois Rameau, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.16233v1.pdf)  
  Keywords: ar, recognition, understanding, semantic, human, gaussian splatting, geometry  
- **[What Makes a 3D Scene Editable? A Factorized Benchmark of Fidelity, Locality, Consistency, and Preservation](https://arxiv.org/abs/2609.14899v1)**  
  Authors: Sariah Patro, Arjun Mehra, Nikhil Bhatia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.14899v1.pdf)  
  Keywords: ar, nerf, 3d gaussian, semantic, gaussian splatting, geometry  
- **[From Explicit References to Scene Manifolds: Distributional Fidelity and Realism for Radiance Field Quality Assessment](https://arxiv.org/abs/2609.07346v1)**  
  Authors: Saeed Mahmoudpour, Gi-Mun Um, Hyon-Gon Choo, Peter Schelkens  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2609.07346v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gitlab.com/saeedmp/scoda.)  
  Keywords: ar, nerf, compression, lightweight, 3d gaussian, semantic, human, gaussian splatting  



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