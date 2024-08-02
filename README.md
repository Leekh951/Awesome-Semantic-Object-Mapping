# Awesome Semantic-Object Mapping [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository considers papers that optimize robot and object states based on Monocular, RGB-D, and LiDAR, as well as papers that perform loop closure detection through semantic scene matching. Here, object states typically include object pose and shape parameters.  
This repository is still under construction and will continue to be updated!

## Papers

### Parametric Object Representation & Association

| Year | Venue | Paper Title | Repository |
|:----:|:-----:|-------------|------------|
| 2024 | arXiv | [SlideSLAM: Sparse, Lightweight, Decentralized Metric-Semantic SLAM for Multi-Robot Navigation](https://arxiv.org/pdf/2406.17249) | N/A |
| 2024 | arXiv | [Multi-Robot Object SLAM using Distributed Variational Inference](https://arxiv.org/pdf/2404.18331) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/intrepidChw/distributed_msckf) |
| 2024 | ICRA | [VOOM: Robust Visual Object Odometry and Mapping using Hierarchical Landmarks](https://arxiv.org/pdf/2402.13609.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/yutongwangBIT/VOOM) |
| 2024 | RA-L | [ObVi-SLAM: Long-Term Object-Visual SLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423794) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/ut-amrl/ObVi-SLAM) [![Video](https://img.shields.io/badge/YouTube-Video-red)](https://youtu.be/quJOgnEdaZ0) |
| 2023 | T-RO | [An Object SLAM Framework for Association, Mapping, and High-Level Tasks](https://arxiv.org/pdf/2305.07299.pdf) | N/A |
| 2023 | T-ITS | [Object SLAM With Robust Quadric Initialization and Mapping for Dynamic Outdoors](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10149129) | N/A |
| 2023 | RA-L | [QISO-SLAM: Object-Oriented SLAM Using Dual Quadrics as Landmarks Based on Instance Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10056983) | N/A |
| 2023 | Journal of Intelligent & Robotic Systems | [SQ-SLAM: Monocular Semantic SLAM Based on Superquadric Object Representation](https://arxiv.org/pdf/2209.10817.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/XiaoHan-Git/SQ-SLAM) |
| 2023 | arXiv | [BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects](https://arxiv.org/abs/2303.14158) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/NVlabs/BundleSDF) [![Video](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=5PymzKbKv8w) |
| 2023 | arXiv | [Object-based SLAM utilizing unambiguous pose parameters considering general symmetry types](https://arxiv.org/pdf/2303.07872.pdf) | [![Video](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=aVc4x3hsVo4) |
| 2023 | arXiv | [UniQuadric: A SLAM Backend for Unknown Rigid Object 3D Tracking and Light-Weight Modeling](https://arxiv.org/pdf/2309.17036.pdf) | N/A |
| 2022 | ICRA | [Unified Representation of Geometric Primitives for Graph-SLAM Optimization Using Decomposed Quadrics](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812162) | N/A |
| 2022 | arXiv | [LayoutSLAM: Object Layout based Simultaneous Localization and Mapping for Reducing Object Map Distortion](https://ieeexplore.ieee.org/abstract/document/9981492) | N/A |
| 2022 | arXiv | [OA-SLAM: Leveraging Objects for Camera Relocalization in Visual SLAM](https://arxiv.org/pdf/2209.08338.pdf) | [![Code](https://img.shields.io/badge/Gitlab-Repository-blue)](https://gitlab.inria.fr/tangram/oa-slam) [![Video1](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=L1HEL4kLJ3g) [![Video2](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=50zXF7Z7FLo) |
| 2022 | RA-L | [SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints](https://arxiv.org/pdf/2109.04884.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/XunshanMan/SoSLAM) |
| 2022 | CVPR | [Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Merrill_Symmetry_and_Uncertainty-Aware_Object_SLAM_for_6DoF_Object_Pose_Estimation_CVPR_2022_paper.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/rpng/suo_slam) |
| 2021 | IROS | [LiDAR-Based Object-Level SLAM for Autonomous Vehicles](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636299) | N/A |
| 2022 | RA-L | [Accurate and Robust Object SLAM With 3D Quadric Landmark Reconstruction in Outdoors](https://arxiv.org/pdf/2110.08977.pdf) | [![Video](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=t1KQ8FhO0wo&ab_channel=SLAMer) |
| 2021 | arXiv | [A Multi-Hypothesis Approach to Pose Ambiguity in Object-Based SLAM](https://arxiv.org/pdf/2108.01225.pdf) | [![Video](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=O3wzdGToh-8&ab_channel=MITMarineRoboticsGroup) |
| 2021 | arXiv | [DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM](https://arxiv.org/pdf/2010.07820.pdf) | N/A |

<p align="right">[<a href="#table-of-contents">back to table</a>]</p>

### Semantic Scene Matching for Loop closing

| Year | Venue | Paper Title | Repository |
|:----:|:-----:|-------------|------------|
| 2024 | arXiv | [SemanticTopoLoop: Semantic Loop Closure With 3D Topological Graph Based on Quadric-Level Object Map](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10460989) | N/A |








# Awesome Metric-Object SLAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
- This repository considers papers that optimize robot and object states based on Monocular, RGB-D, and LiDAR, as well as papers that perform loop closure detection through semantic scene matching. Here, object states typically include object pose and shape parameters.
- This repository is still under construction and will continue to be updated!



## Papers

### Parametric Object Representation & Association

#### 2024
  - SlideSLAM: Sparse, Lightweight, Decentralized Metric-Semantic SLAM for Multi-Robot Navigation. [arXiv] \
[\[PDF\]](https://arxiv.org/pdf/2406.17249)
  - Multi-Robot Object SLAM using Distributed Variational Inference. [arXiv]\
[\[PDF\]](https://arxiv.org/pdf/2404.18331) [\[Code\]](https://github.com/intrepidChw/distributed_msckf)
  - VOOM: Robust Visual Object Odometry and Mapping using Hierarchical Landmarks. [2024 ICRA]\
[\[PDF\]](https://arxiv.org/pdf/2402.13609.pdf) [\[Code\]](https://github.com/yutongwangBIT/VOOM)
  - ObVi-SLAM: Long-Term Object-Visual SLAM. [2024 RA-L]\
 [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423794) [\[Code\]](https://github.com/ut-amrl/ObVi-SLAM) [\[Video\]](https://youtu.be/quJOgnEdaZ0)
#### 2023

  - An Object SLAM Framework for Association, Mapping, and High-Level Tasks. [2023 T-RO]\
[\[PDF\]](https://arxiv.org/pdf/2305.07299.pdf)
  - Object SLAM With Robust Quadric Initialization and Mapping for Dynamic Outdoors. [2023 T-ITS] \
[\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10149129)
  - QISO-SLAM: Object-Oriented SLAM Using Dual Quadrics as Landmarks Based on Instance Segmentation [2023 RA-L] \
[\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10056983)
  - BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects. \
[\[PDF\]](https://arxiv.org/abs/2303.14158) [\[Code\]](https://github.com/NVlabs/BundleSDF) [\[Video\]](https://www.youtube.com/watch?v=5PymzKbKv8w)
  - Object-based SLAM utilizing unambiguous pose parameters considering general symmetry types. \
[\[PDF\]](https://arxiv.org/pdf/2303.07872.pdf) [\[Video\]](https://www.youtube.com/watch?v=aVc4x3hsVo4)

  - UniQuadric: A SLAM Backend for Unknown Rigid Object 3D Tracking and Light-Weight Modeling. [arXiv] \
[\[PDF\]](https://arxiv.org/pdf/2309.17036.pdf)

#### 2022
  - Unified Representation of Geometric Primitives for Graph-SLAM Optimization Using Decomposed Quadrics. [2022 ICRA] \
[\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812162)
  - LayoutSLAM: Object Layout based Simultaneous Localization and Mapping for Reducing Object Map Distortion. \
[\[PDF\]](https://ieeexplore.ieee.org/abstract/document/9981492)
  - OA-SLAM: Leveraging Objects for Camera Relocalization in Visual SLAM. \
[\[PDF\]](https://arxiv.org/pdf/2209.08338.pdf) [\[Code\]](https://gitlab.inria.fr/tangram/oa-slam) [\[Video1\]](https://www.youtube.com/watch?v=L1HEL4kLJ3g) [\[Video2\]](https://www.youtube.com/watch?v=50zXF7Z7FLo)
  - SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints. [2022 RA-L]\
 [\[PDF\]](https://arxiv.org/pdf/2109.04884.pdf) [\[Code\]](https://github.com/XunshanMan/SoSLAM)
  - SQ-SLAM: Monocular Semantic SLAM Based on Superquadric Object Representation. [2023 Journal of Intelligent & Robotic Systems]\
[\[PDF\]](https://arxiv.org/pdf/2209.10817.pdf) [\[Code\]](https://github.com/XiaoHan-Git/SQ-SLAM)
  - Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation.\
 [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Merrill_Symmetry_and_Uncertainty-Aware_Object_SLAM_for_6DoF_Object_Pose_Estimation_CVPR_2022_paper.pdf) [\[Code\]](https://github.com/rpng/suo_slam)


#### 2021
  - LiDAR-Based Object-Level SLAM for Autonomous Vehicles. [2021 IROS] \
[\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636299)
  - Accurate and Robust Object SLAM With 3D Quadric Landmark Reconstruction in Outdoors. [2022 RA-L]\
[\[PDF\]](https://arxiv.org/pdf/2110.08977.pdf) [\[Video\]](https://www.youtube.com/watch?v=t1KQ8FhO0wo&ab_channel=SLAMer)
  - A Multi-Hypothesis Approach to Pose Ambiguity in Object-Based SLAM. \
[\[PDF\]](https://arxiv.org/pdf/2108.01225.pdf) [\[Video\]](https://www.youtube.com/watch?v=O3wzdGToh-8&ab_channel=MITMarineRoboticsGroup)
  - DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM.\
[\[PDF\]](https://arxiv.org/pdf/2010.07820.pdf)
  - Object-Augmented RGB-D SLAM for Wide-Disparity Relocalisation.\
[\[PDF\]](https://arxiv.org/pdf/2108.02522) [\[Code\]](https://github.com/YuhangMing/Object-Guided-Relocalisation) [\[Video\]](https://www.youtube.com/watch?v=H3i9Q4JvX2o)

#### 2020

  - Dynamic SLAM: The Need for Speed.\
 [\[PDF\]](https://arxiv.org/pdf/2002.08584.pdf)
  - EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association. [2020 IROS]\
 [\[PDF\]](https://arxiv.org/pdf/2004.12730.pdf) [\[Code\]](https://github.com/yanmin-wu/EAO-SLAM) [\[Project Page\]](https://yanmin-wu.github.io/project/eaoslam/)
  - OrcVIO: Object Residual Constrained Visual-Inertial Odometry.  \
[\[PDF\]](https://arxiv.org/pdf/2007.15107.pdf) [\[Code\]](https://github.com/shanmo/OrcVIO-Stereo-Mapping) [\[Project Page\]](https://moshan.cf/orcvio_githubpage/)
  - VDO-SLAM: A Visual Dynamic Object-Aware SLAM System.\
 [\[PDF\]](https://arxiv.org/pdf/2005.11052.pdf) [\[Code\]](https://github.com/halajun/VDO_SLAM) [\[Video\]](https://drive.google.com/file/d/1PbL4KiJ3sUhxyJSQPZmRP6mgi9dIC0iu/view)

#### 2019

  - CubeSLAM: Monocular 3D Object SLAM. [2019 T-RO]\
 [\[PDF\]](https://arxiv.org/pdf/1806.00557.pdf) [\[Code\]](https://github.com/shichaoy/cube_slam) [\[Video\]](https://www.youtube.com/watch?v=QnVlexXi9_c&ab_channel=ShichaoYang)
  - Monocular Object and Plane SLAM in Structured Environments. [2019 RA-L] \
[\[PDF\]](https://arxiv.org/pdf/1809.03415.pdf) [\[Video\]](https://www.youtube.com/watch?v=jzBMsKCm0uk&ab_channel=ShichaoYang)
  - QuadricSLAM: Dual Quadrics from Object Detections as Landmarks in Object-Oriented SLAM. [2018 RA-L]\
[\[PDF\]](https://natanaso.github.io/rcw-icra18/assets/ref/ICRA-MRP18_paper_14.pdf) [\[Code\]](https://github.com/qcr/quadricslam) [\[Video\]](https://www.youtube.com/watch?v=n-j0DFDFSKU&ab_channel=LachlanNicholson)
  - Real-Time Monocular Object-Model Aware Sparse SLAM. \
[\[PDF\]](https://ieeexplore.ieee.org/document/8793728) [\[Video\]](https://www.youtube.com/watch?v=UMWXd4sHONw&ab_channel=MehdiHosseinzadeh)
  - Robust Object-based SLAM for High-Speed Autonomous Navigation. [2019 ICRA]\
 [\[PDF\]](https://groups.csail.mit.edu/rrg/papers/OkLiu19icra.pdf)

#### 2018

  - Structure Aware SLAM using Quadrics and Planes. \
[\[PDF\]](https://arxiv.org/pdf/1804.09111.pdf) [\[Video\]](https://www.youtube.com/watch?v=dR-rB9keF8M&ab_channel=MehdiHosseinzadeh)

### Semantic Scene Matching for Loop closing

#### 2024
#### 2023


----------------------

## Resources

### Datasets

- [ApolloScape](http://apolloscape.auto/)
- [Cityscapes](https://www.cityscapes-dataset.com/)
- [ICL-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html)
- [KITTI](https://www.cvlibs.net/datasets/kitti/index.php)
- [Microsoft-RGBD](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/)
- [NYU Depth v2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)
- [Redwood-OS](http://redwood-data.org/3dscan/)
- [RGBD Scenes v1](https://rgbd-dataset.cs.washington.edu/)
- [RGBD Scenes v2](https://rgbd-dataset.cs.washington.edu/dataset/rgbd-scenes-v2/)
- [ScanNet](http://www.scan-net.org/)
- [TUM](https://vision.in.tum.de/data/datasets/rgbd-dataset/download)
- [YCB-Video](https://rse-lab.cs.washington.edu/projects/posecnn/)
