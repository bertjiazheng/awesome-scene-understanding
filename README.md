
# Awesome Scene Understanding


## Table of Contents

- [Dataset](#dataset)
  - [Realistic Datasets](#realistic_dataset)
  - [Synthetic Datasets](#synthetic_dataset)
- [Holistic Scene Understanding](#holistic_scene_understanding)
- [Room Layout Estimation](#room_layout_estimation)
  - [Perspective Image](#perspective_image)
  - [Panoramic Image](#panoramic_image)
- [Floorplan](#floorplan)
- [Primitive Detection](#primitive_detection)
  - [Wireframe](#wireframe)
  - [Line Segment](#line_segment)
  - [Junction](#junction)
  - [Plane](#plane)

<a name="dataset" />

## Dataset

<a name="realistic_dataset" />

### Realistic Dataset

* Indoor Segmentation and Support Inference from RGBD Images (ECCV'12) [[Project]](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2) [[Paper]](http://cs.nyu.edu/~silberman/papers/indoor_seg_support.pdf) 

* SUN3D: A Database of Big Spaces Reconstructed using SfM and Object Labels (ICCV'13) [[Project]](http://sun3d.cs.princeton.edu/) [[Paper]](http://3dvision.princeton.edu/projects/2013/SUN3D/paper.pdf)

* SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite (CVPR'15) [[Project]](http://rgbd.cs.princeton.edu/) [[Paper]](http://rgbd.cs.princeton.edu/paper.pdf)

* SceneNN: a Scene Meshes Dataset with aNNotations (3DV'16) [[Project]](http://www.scenenn.net) [[Paper]](http://www.scenenn.net/pdf/dataset_3dv16.pdf)

* ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes (CVPR'17) [[Project]](http://www.scan-net.org/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)

* Joint 2D-3D-Semantic Data for Indoor Scene Understanding (arXiv'17) [[Project]](http://buildingparser.stanford.edu/dataset.html) [[Paper]](http://buildingparser.stanford.edu/images/2D-3D-S_2017.pdf)

* Matterport3D: Learning from RGB-D Data in Indoor Environments (3DV'17) [[Project]](https://niessner.github.io/Matterport/) [[Paper]](https://arxiv.org/pdf/1709.06158.pdf) [[Code]](https://github.com/niessner/Matterport) 

<a name="synthetic_dataset" />

### Synthetic Dataset

* The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes (CVPR'16) [[Project]](http://synthia-dataset.net/) [[Paper]](http://refbase.cvc.uab.es/files/RSM2016.pdf)

* SceneNet: Understanding Real World Indoor Scenes With Synthetic Data (CVPR'16) [[Project]](https://robotvault.bitbucket.io/) [[Paper]](http://arxiv.org/pdf/1511.07041.pdf)

* SUNCG (CVPR'17) [[Project]](http://suncg.cs.princeton.edu/) [[Paper]](https://arxiv.org/pdf/1611.08974v1.pdf)

* SceneNet RGB-D (ICCV'17) [[Project]](https://robotvault.bitbucket.io/scenenet-rgbd.html) [[Paper]](https://www.imperial.ac.uk/media/imperial-college/research-centres-and-groups/dyson-robotics-lab/jmccormac_etal_iccv2017.pdf)

* InteriorNet (BMVC'18) [[Project]](https://interiornet.org/) [[Paper]](https://arxiv.org/pdf/1809.00716.pdf)

<a name="holistic_scene_understanding" />

## Holistic Scene Understanding

* Thinking Inside the Box: Using Appearance Models and Context Based on Room Geometry (ECCV'10) [[Paper]](http://vision.cs.uiuc.edu/~vhedau2/Publications/eccv2010_think_inside.pdf)

* Estimating Spatial Layout of Rooms using Volumetric Reasoning about Objects and Surfaces (NeurIPS'10) [[Paper]](https://papers.nips.cc/paper/4120-estimating-spatial-layout-of-rooms-using-volumetric-reasoning-about-objects-and-surfaces.pdf)

* Efficient Exact Inference for 3D Indoor Scene Understanding (ECCV'12) [[Paper]](http://schwingag.de/papers/SchwingEtAl_ECCV2012.pdf)

* Recovering Free Space of Indoor Scenes from a Single Image (CVPR'12) [[Paper]](http://vision.cs.uiuc.edu/~vhedau2/Publications/cvpr2012_freespace.pdf)

* Understanding Indoor Scenes using 3D Geometric Phrases (CVPR'13) [[Paper]](http://cvgl.stanford.edu/papers/choi_cvpr13.pdf)

* Scene Parsing by Integrating Function, Geometry and Appearance Models (CVPR'13) [[Project]](http://www.stat.ucla.edu/~ybzhao/research/functionality/) [[Paper]](http://www.stat.ucla.edu/~ybzhao/research/functionality/functionality.pdf)

* Im2CAD (CVPR'18) [[Project]](https://homes.cs.washington.edu/~izadinia/im2cad.html) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Izadinia_IM2CAD_CVPR_2017_paper.pdf)

* Pano2CAD: Room Layout From A Single Panorama Image (WACV'17) [[Paper]](http://bjornstenger.github.io/papers/xu_wacv2017.pdf)

* DeepContext: Context-Encoding Neural Pathways for 3D Holistic Scene Understanding (ICCV'17) [[Project]](http://deepcontext.cs.princeton.edu) [[Paper]](http://deepcontext.cs.princeton.edu/paper.pdf)

* Factoring Shape, Pose, and Layout from the 2D Image of a 3D Scene (CVPR'18) [[Project]](https://shubhtuls.github.io/factored3d/) [[Paper]](https://arxiv.org/pdf/1712.01812.pdf) [[Code]](https://github.com/shubhtuls/factored3d)

* Holistic 3D Scene Parsing and Reconstruction from a Single RGB Image (ECCV'18) [[Project]](http://siyuanhuang.com/holistic_parsing/main.html) [[Paper]](http://siyuanhuang.com/files/eccv2018parsing.pdf) [[Code]](https://github.com/thusiyuan/holistic_scene_parsing)

* Cooperative Holistic Scene Understanding: Unifying 3D Object, Layout, and Camera Pose Estimation (NeurIPS'18) [[Project]](http://siyuanhuang.com/cooperative_parsing/main.html) [[Paper]](http://siyuanhuang.com/files/nips2018cooperative.pdf) [[Code]](https://github.com/thusiyuan/cooperative_scene_parsing)

* Complete 3D Scene Parsing from an RGBD Image (IJCV'18) [[Paper]](https://arxiv.org/pdf/1710.09490.pdf)

<a name="room_layout_estimation" />

## Room Layout Estimation

<a name="perspective_image" />

### Perspective Image

* Recovering the Spatial Layout of Cluttered Rooms (ICCV'09) [[Paper]](http://dhoiem.cs.illinois.edu/publications/iccv2009_hedau_indoor.pdf)

* Box In the Box: Joint 3D Layout and Object Reasoning from Single Images (CVPR'13) [[Paper]](http://openaccess.thecvf.com/content_iccv_2013/papers/Schwing_Box_in_the_2013_ICCV_paper.pdf)

* Learning Informative Edge Maps for Indoor Scene Layout Prediction (ICCV'15) [[Homepage]](http://arunmallya.github.io/) [[Paper]](http://slazebni.cs.illinois.edu/publications/iccv15_informative.pdf)

* DeLay: Robust Spatial Layout Estimation for Cluttered Indoor Scenes (CVPR'16) [[Paper]](http://cvgl.stanford.edu/papers/delay-robust-spatial.pdf)

* A Coarse-to-Fine Indoor Layout Estimation (CFILE) Method (ACCV'16) [[Paper]](https://arxiv.org/pdf/1607.00598.pdf)

* Physics Inspired Optimization on Semantic Transfer Features: An Alternative Method for Room Layout Estimation (CVPR'17) [[Project]](https://sites.google.com/view/st-pio/) [[Paper]](https://arxiv.org/pdf/1707.00383.pdf)

* RoomNet: End-to-End Room Layout Estimation (ICCV'17) [[Paper]](https://arxiv.org/pdf/1703.06241.pdf)

* Thinking Outside the Box: Generation of Unconstrained 3D Room Layouts (ACCV'18)

<a name="panoramic_image" />

### Panoramic Image

* PanoContext: A Whole-room 3D Context Model for Panoramic Scene Understanding (ECCV'14) [[Project]](http://panocontext.cs.princeton.edu/)

* Efficient 3D Room Shape Recovery From a Single Panorama (CVPR'16) [[Project]](http://cgcad.thss.tsinghua.edu.cn/yanghao/3droom/) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780954) [[Code]](https://github.com/YANG-H/Panoramix)

* LayoutNet: Reconstructing the 3D Room Layout from a Single RGB Image (CVPR'18) [[Code]](https://github.com/zouchuhang/LayoutNet)

* Layouts from Panoramic Images with Geometry and Deep Learning (IROS'18) [[Code]](https://github.com/cfernandezlab/Lines-and-Vanishing-Points-directly-on-Panoramas)

* HorizonNet: Learning Room Layout with 1D Representation and Pano Stretch Data Augmentation (CVPR'19) [[Paper]](https://arxiv.org/pdf/1901.03861) [[Code]](https://github.com/sunset1995/HorizonNet)

* DuLa-Net: A Dual-Projection Network for Estimating Room Layouts from a Single RGB Panorama (CVPR'19) [[Project]](https://cgv.cs.nthu.edu.tw/projects/dulanet) [[Paper]](https://arxiv.org/pdf/1811.11977.pdf)

<a name="floorplan" />

## Floorplan

* Raster-to-Vector: Revisiting Floorplan Transformation (ICCV'17) [[Project]](http://art-programmer.github.io/floorplan-transformation.html) [[Paper]](https://www.cse.wustl.edu/~chenliu/floorplan-transformation/paper.pdf) [[Code]](https://github.com/art-programmer/FloorplanTransformation)

* FloorNet: A unified framework for floorplan reconstruction from 3D scans (ECCV'18) [[Project]](http://art-programmer.github.io/floornet.html) [[Paper]](https://arxiv.org/pdf/1804.00090.pdf) [[Code]](https://github.com/art-programmer/FloorNet)

<a name="primitive_detection" />

## Primitive Detection

<a name="wireframe" />

### Wireframe

* Learning to Parse Wireframes in Images of Man-Made Environments (CVPR'18) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Learning_to_Parse_CVPR_2018_paper.pdf)

<a name="line_segment" />

### Line Segment

* LSD: A Fast Line Segment Detector with a False Detection Control (TPAMI'10) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4731268)

* Lifting 3D Manhattan Lines from a Single Image (ICCV'15) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6751171)

* MCMLSD: A Dynamic Programming Approach to Line Segment Detection (CVPR'17) [[Paper]](http://www.elderlab.yorku.ca/wp-content/uploads/2016/12/Almazan_MCMLSD_A_Dynamic_CVPR_2017_paper.pdf1)

* A Novel Linelet-Based Representation for Line Segment Detection (TPAMI'18) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7926451)

* Novel Single View Constraints for Manhattan 3D Line Reconstruction (3DV'18) [[Paper]](https://arxiv.org/pdf/1810.03737.pdf)

<a name="junction" />

### Junction

* Manhattan Junction Catalogue for Spatial Reasoning of Indoor Scenes (CVPR'13) [[Paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Ramalingam_Manhattan_Junction_Catalogue_2013_CVPR_paper.pdf)

<a name="plane" />

### Plane

* PlaneNet: Piece-wise Planar Reconstruction from a Single RGB Image (CVPR'18) [[Project]](https://www.cse.wustl.edu/~chenliu/planenet.html) [[Paper]](https://arxiv.org/abs/1804.06278) [[Code]](https://github.com/art-programmer/PlaneNet)

* Recovering 3D Planes from a Single Image via Convolutional Neural Networks (ECCV'18) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Fengting_Yang_Recovering_3D_Planes_ECCV_2018_paper.pdf) 

* Thinking Outside the Box: Generation of Unconstrained 3D Room Layouts (ACCV'18)

* PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image (CVPR'19) [[Paper]](https://arxiv.org/pdf/1812.04072.pdf)

* Single-Image Piece-wise Planar 3D Reconstruction via Associative Embedding (CVPR'19) [[Paper]](https://arxiv.org/pdf/1902.09777.pdf) 
