# Awesome Semantic-Object Mapping [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository considers papers that optimize robot and object states based on Monocular, RGB-D, and LiDAR, as well as papers that perform loop closure detection through semantic scene matching. Here, object states typically include object pose and shape parameters.  
This repository is still under construction and will continue to be updated!

<!-- ## Table of Contents

- [Papers](#papers)
  - [Object SLAM & Parameterization](#Object-SLAM-Parameterization)
  - [Semantic Scene Matching for Loop Closing](#semantic-scene-matching-for-loop-closing)
- [Resources](#resources)
  - [Datasets](#datasets) -->

## Papers

### Object SLAM & Parameterization

| Year | Venue | Paper Title | Repository |
|:----:|:-----:|-------------|------------|
| `2024` | `arXiv` | [SlideSLAM: Sparse, Lightweight, Decentralized Metric-Semantic SLAM for Multi-Robot Navigation](https://arxiv.org/pdf/2406.17249) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/XuRobotics/slide-slam) |
| `2024` | `arXiv` | [Multi-Robot Object SLAM using Distributed Variational Inference](https://arxiv.org/pdf/2404.18331) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/intrepidChw/distributed_msckf) |
| `2024` | `ICRA` | [VOOM: Robust Visual Object Odometry and Mapping using Hierarchical Landmarks](https://arxiv.org/pdf/2402.13609.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/yutongwangBIT/VOOM) |
| `2024` | `RA-L` | [ObVi-SLAM: Long-Term Object-Visual SLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423794) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/ut-amrl/ObVi-SLAM) |
| `2023` | `T-RO` | [An Object SLAM Framework for Association, Mapping, and High-Level Tasks](https://arxiv.org/pdf/2305.07299.pdf) | N/A |
| `2023` | `T-ITS` | [Object SLAM With Robust Quadric Initialization and Mapping for Dynamic Outdoors](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10149129) | N/A |
| `2023` | `RA-L` | [QISO-SLAM: Object-Oriented SLAM Using Dual Quadrics as Landmarks Based on Instance Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10056983) | N/A |
| `2023` | `JIRS` [1] | [SQ-SLAM: Monocular Semantic SLAM Based on Superquadric Object Representation](https://arxiv.org/pdf/2209.10817.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/XiaoHan-Git/SQ-SLAM) |
| `2023` | `ICRA` | [Object-based SLAM utilizing unambiguous pose parameters considering general symmetry types](https://arxiv.org/pdf/2303.07872.pdf) | N/A |
| `2023` | `arXiv` | [UniQuadric: A SLAM Backend for Unknown Rigid Object 3D Tracking and Light-Weight Modeling](https://arxiv.org/pdf/2309.17036.pdf) | N/A |
| `2022` | `ICRA` | [Unified Representation of Geometric Primitives for Graph-SLAM Optimization Using Decomposed Quadrics](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812162) | N/A |
| `2022` | `IROS` | [LayoutSLAM: Object Layout based Simultaneous Localization and Mapping for Reducing Object Map Distortion](https://ieeexplore.ieee.org/abstract/document/9981492) | N/A |
| `2022` | `ISMAR`  | [OA-SLAM: Leveraging Objects for Camera Relocalization in Visual SLAM](https://arxiv.org/pdf/2209.08338.pdf) | [![Code](https://img.shields.io/badge/Gitlab-Repository-blue)](https://gitlab.inria.fr/tangram/oa-slam) |
| `2022` | `RA-L` | [SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints](https://arxiv.org/pdf/2109.04884.pdf) | [![Code1](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/XunshanMan/SoSLAM) [![Code2](https://img.shields.io/badge/Github-Repository-red)](https://github.com/MRHan-426/SOSLAM)|
| `2022` | `CVPR` | [Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Merrill_Symmetry_and_Uncertainty-Aware_Object_SLAM_for_6DoF_Object_Pose_Estimation_CVPR_2022_paper.pdf) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/rpng/suo_slam) |
| `2022` | `RA-L` | [Accurate and Robust Object SLAM With 3D Quadric Landmark Reconstruction in Outdoors](https://arxiv.org/pdf/2110.08977.pdf)  | N/A |
| `2021` | `IROS` | [LiDAR-Based Object-Level SLAM for Autonomous Vehicles](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636299) | N/A |
| `2021` | `ICCV` | [ODAM: Object Detection, Association, and Mapping using Posed RGB Video](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9710968) | [![Code](https://img.shields.io/badge/Gitlab-Repository-blue)](https://github.com/likojack/odam)|
| `2021` | `RA-L` | [DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM](https://arxiv.org/pdf/2010.07820.pdf) | N/A |
| `2021` | `arXiv` | [Superquadric Object Representation for Optimization-based Semantic SLAM](https://arxiv.org/pdf/2109.09627) | N/A |
| `2020` | `IROS` | [EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9341757) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/yanmin-wu/EAO-SLAM) |
| `2019` | `ICRA` | [Robust Object-based SLAM for High-speed Autonomous Navigation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8794344) | N/A |
| `2019` | `RA-L` | [Monocular Object and Plane SLAM in Structured Environments](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8744612) | N/A |
| `2019` | `T-RO` | [CubeSLAM: Monocular 3D Object SLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8708251) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/shichaoy/cube_slam) |
| `2019` | `RA-L` | [QuadricSLAM: Dual Quadrics From Object Detections as Landmarks in Object-Oriented SLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8440105) | [![Code1](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/qcr/quadricslam)  [![Code2](https://img.shields.io/badge/Github-Repository-purple)](https://github.com/qcr/gtsam-quadrics)|
| `2018` | `ACCV` | [Structure Aware SLAM using Quadrics and Planes](https://arxiv.org/pdf/1804.09111) | N/A |

[1]: JIRS = Journal of Intelligent & Robotic Systems 
<p align="right">[<a href="#table-of-contents">back to table</a>]</p>

### Semantic Scene Matching for Loop closing

| Year | Venue | Paper Title | Repository |
|:----:|:----:|-------------|------------|
| `2024` | `RA-L` | [SemanticTopoLoop: Semantic Loop Closure With 3D Topological Graph Based on Quadric-Level Object Map](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10460989) | N/A |
| `2023` | `arXiv` | [Loop Closure Detection Based on Object-level Spatial Layout and Semantic Consistency](https://arxiv.org/pdf/2304.05146) | N/A |
| `2022` | `RA-L` | [Towards Accurate Loop Closure Detection in Semantic SLAM With 3D Semantic Covisibility Graphs](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9691853) | N/A |
| `2022` | `CASE` | [Object-based Loop Closure with Directional Histogram Descriptor](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926687) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/benchun123/object-based-loop-closure?tab=readme-ov-file) |
| `2021` | `JVCIR` [2] | [Semantic loop closure detection based on graph matching in multi-objects scenes](https://www.sciencedirect.com/science/article/pii/S1047320321000389) | N/A |
| `2021` | `RA-L` | [Topology Aware Object-Level Semantic Mapping Towards More Robust Loop Closure](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9484819) | N/A |
| `2021` | `RA-L` | [Semantic histogram based graph matching for real-time multi-robot global localization in large scale environment](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9353207) | [![Code](https://img.shields.io/badge/Github-Repository-blue)](https://github.com/gxytcrc/semantic-histogram-based-global-localization) |
| `2019` | `ICRA` | [Global localization with objectlevel semantics and topology](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8794475) | N/A |
| `2019` | `ICRA` | [Semantic Mapping for View-Invariant Relocalization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8793624) | N/A |
| `2017` | `RA-L` | [X-View: Graph-Based Semantic Multi-View Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8281068) | N/A |

[2]: JVCIR = Journal of Visual Communication and Image Representation
<p align="right">[<a href="#table-of-contents">back to table</a>]</p>

----------------------
## Resources

### Datasets

| Dataset Name       | Description                                                                                           | Link                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| KITTI              | A well-known dataset for autonomous driving research, offering stereo and LiDAR data for tasks like object detection, tracking, and SLAM. | [KITTI](https://www.cvlibs.net/datasets/kitti/index.php)   |
| SemanticKITTI      | A large-scale dataset providing semantic segmentation labels for LiDAR point clouds, based on the KITTI Odometry Benchmark, suitable for autonomous driving applications.            | [SemanticKITTI](https://www.semantic-kitti.org/) |
| Replica            | A highly detailed and realistic dataset of 18 indoor environments, providing photorealistic textures and semantic annotations for 3D research.                   | [Replica](https://github.com/facebookresearch/Replica-Dataset) |
| TUM                | A dataset for evaluating RGB-D SLAM systems, containing benchmark sequences recorded with a Microsoft Kinect camera.                   | [TUM](https://vision.in.tum.de/data/datasets/rgbd-dataset/download) |
| Matterport3D       | A large dataset of indoor RGB-D images with 3D meshes and semantic annotations, used for developing scene understanding algorithms.        | [Matterport3D](https://niessner.github.io/Matterport/) |
| SUN RGB-D          | A dataset containing RGB-D images from various sensors, annotated with 3D bounding boxes for object detection and scene understanding research.        | [SUN RGB-D](https://rgbd.cs.princeton.edu/) |
| Microsoft-RGBD     | A dataset featuring RGB-D sequences captured in various indoor environments, used for scene understanding and 3D reconstruction tasks.                 | [Microsoft-RGBD](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/) |
| NYU Depth v2       | An RGB-D dataset collected with a Kinect sensor, providing labeled depth maps and semantic annotations for indoor scenes.                            | [NYU Depth v2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) |
| Redwood-OS         | A collection of RGB-D sequences designed for evaluating 3D reconstruction algorithms, with a focus on object and scene scanning.              | [Redwood-OS](http://redwood-data.org/3dscan/)              |
| RGBD Scenes v1     | A dataset with RGB-D video sequences for studying 3D object recognition and scene understanding, featuring cluttered indoor environments.          | [RGBD Scenes v1](https://rgbd-dataset.cs.washington.edu/)  |
| RGBD Scenes v2     | An extended version of RGBD Scenes v1, providing additional objects and sequences for more complex scene analysis.                  | [RGBD Scenes v2](https://rgbd-dataset.cs.washington.edu/dataset/rgbd-scenes-v2/) |
| ICL-NUIM           | A synthetic RGB-D dataset for benchmarking SLAM and visual odometry algorithms, featuring photo-realistic scenes.        | [ICL-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) |
| ScanNet            | A richly annotated dataset with RGB-D video sequences of indoor environments, aimed at advancing 3D scene understanding and reconstruction.    | [ScanNet](http://www.scan-net.org/)                        |
| YCB-Video          | A dataset for benchmarking 6-DoF object pose estimation in video, including real and synthetic sequences of household objects.          | [YCB-Video](https://rse-lab.cs.washington.edu/projects/posecnn/) |
| ApolloScape        | A comprehensive dataset for autonomous driving, providing annotated 2D/3D images and point clouds from real-world traffic scenarios.                               | [ApolloScape](http://apolloscape.auto/)                    |
| Cityscapes         | A large-scale dataset for semantic urban scene understanding, featuring pixel-level annotations for various urban street scenes.                                   | [Cityscapes](https://www.cityscapes-dataset.com/)          |
<p align="right">[<a href="#table-of-contents">back to table</a>]</p>
