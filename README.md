# 3D-Detection-CVPR2022
CVPR2022 paper list on 3D Object Detection, include: method name, paper link, code link and dataset name.

## 1. Point Cloud


|   name   | paper link | code link | dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|
|     SST    |    https://arxiv.org/pdf/2112.06375.pdf        |  https://github.com/TuSimple/SST  |      Waymo     |
|    HyperDet3D   |     https://arxiv.org/pdf/2204.05599.pdf        |          -          |      ScanNetV2/ SUNRGBD     |
|    Point2Seq   |     https://arxiv.org/pdf/2203.13394.pdf        |   https://github.com/ocNflag/point2seq    |      Waymo/ONCE     |
|    IA-SSD   |     https://arxiv.org/pdf/2203.11139.pdf        |   https://github.com/yifanzhang713/IA-SSD     |      KITTI     |
|    VISTA   |     https://arxiv.org/pdf/2203.09704.pdf        |   https://github.com/Gorilla-Lab-SCUT/VISTA    |      NuScenes/Waymo     |
|    BacktoReality   |    https://arxiv.org/pdf/2203.05238.pdf    |   https://github.com/wyf-ACCEPT/BackToReality   |    ModelNet40/ScanNet |
|    OccAM’s Laser   |    https://arxiv.org/pdf/2204.06577.pdf  |          -          |     KITTI    |
|    PDV   |    https://arxiv.org/pdf/2203.05662.pdf  |  https://github.com/TRAILab/PDV  |     KITTI/Waymo    |
|    VMVF   |   https://arxiv.org/pdf/2203.02133.pdf  |          -          |   NuScenes   |
|   EON  |  https://openaccess.thecvf.com/content/CVPR2022/papers/Yu_Rotationally_Equivariant_3D_Object_Detection_CVPR_2022_paper.pdf |   https://kovenyu.com/eon/  |      ScanNetV2/ SUNRGBD     |
|  DisARM  |  https://openaccess.thecvf.com/content/CVPR2022/papers/Duan_DisARM_Displacement_Aware_Relation_Module_for_3D_Detection_CVPR_2022_paper.pdf |    https://github.com/YaraDuan/DisARM |    ScanNetV2/ SUNRGBD   |
| Canonical Voting | https://openaccess.thecvf.com/content/CVPR2022/papers/You_Canonical_Voting_Towards_Robust_Oriented_Bounding_Box_Detection_in_3D_CVPR_2022_paper.pdf |       https://github.com/qq456cvb/CanonicalVoting |   ScanNetV2/ SUNRGBD     |
| 3D-VField | https://openaccess.thecvf.com/content/CVPR2022/papers/Lehner_3D-VField_Adversarial_Augmentation_of_Point_Clouds_for_Domain_Generalization_in_CVPR_2022_paper.pdf |  https://crashd-cars.github.io/ |  KITTI/Waymo    |
|  SS3D  |  https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_SS3D_Sparsely-Supervised_3D_Object_Detection_From_Point_Cloud_CVPR_2022_paper.pdf |          -          |   KITTI |
|  RBGNet  |  https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_RBGNet_Ray-Based_Grouping_for_3D_Object_Detection_CVPR_2022_paper.pdf |  https://github.com/Haiyang-W/RBGNet  |  ScanNetV2/ SUNRGBD   |


## 2. Camera


|   name   | paper link | code link | dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|
|   MonoJSG    |  https://arxiv.org/pdf/2203.08563.pdf | https://github.com/lianqing11/MonoJSG |      KITTI/Waymo     |
|  Pseudo-Stereo-3D |  https://arxiv.org/pdf/2203.02112.pdf  |  https://github.com/revisitq/Pseudo-Stereo-3D |  KITTI  |
|  Geo-Aug |  https://openaccess.thecvf.com/content/CVPR2022/papers/Lian_Exploring_Geometric_Consistency_for_Monocular_3D_Object_Detection_CVPR_2022_paper.pdf  |  |     KITTI |
| Homography Loss |  https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Homography_Loss_for_Monocular_3D_Object_Detection_CVPR_2022_paper.pdf  |  https://github.com/TuSimple/SST  |   KITTI  |
| Dimension Embeddings | https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Dimension_Embeddings_for_Monocular_3D_Object_Detection_CVPR_2022_paper.pdf | https://github.com/lianqing11/MonoJSG |  KITTI |
| Time3D | https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Time3D_End-to-End_Joint_Monocular_3D_Object_Detection_and_Tracking_for_CVPR_2022_paper.pdf | https://github.com/lianqing11/MonoJSG | nuScenes  |
|  MonoDDE  | https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Diversity_Matters_Fully_Exploiting_Depth_Clues_for_Reliable_Monocular_3D_CVPR_2022_paper.pdf |  | KITTI |


## 3. Camera+Lidar Fusion


|   name   | paper link | code link | dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|
|  DeepFusion  | https://arxiv.org/pdf/2203.08195.pdf | https://github.com/tensorflow/lingvo/tree/master/lingvo |  Waymo  |
|  VFF | https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Voxel_Field_Fusion_for_3D_Object_Detection_CVPR_2022_paper.pdf | https://github.com/dvlab-research/VFF|  KITTI/nuScenes  |
| ST-MVDNet | https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Modality-Agnostic_Learning_for_Radar-Lidar_Fusion_in_Vehicle_Detection_CVPR_2022_paper.pdf| | Oxford Radar Robotcar|
| S2M2-SSD | https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Boosting_3D_Object_Detection_by_Simulating_Multimodality_on_Point_Clouds_CVPR_2022_paper.pdf | | nuScenes |

## 4. Multi-View/Pseudo Iamge


|   name   | paper link | code link | dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|
|  VMVF | https://openaccess.thecvf.com/content/CVPR2022/papers/Fazlali_A_Versatile_Multi-View_Framework_for_LiDAR-Based_3D_Object_Detection_With_CVPR_2022_paper.pdf| |nuScenes|
|  SFD | 	https://arxiv.org/pdf/2203.09780.pdf| |KITTI|

## 5. Transformer-based Method


|   name   | paper link | code link | dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|
|  CAT-Det| https://arxiv.org/pdf/2204.00325.pdf| |KITTI|
|  MonoDTR |https://arxiv.org/pdf/2203.10981.pdf| https://github.com/kuanchihhuang/MonoDTR |KITTI|
|  VoxSeT | https://arxiv.org/pdf/2203.10314.pdf | https://github.com/skyhehe123/VoxSeT |KITTI/Waymo |
|  TransFusion | https://arxiv.org/pdf/2203.11496.pdf | https://github.com/XuyangBai/TransFusion/ | NuScenes/Waymo |
|  LIFT | https://openaccess.thecvf.com/content/CVPR2022/papers/Zeng_LIFT_Learning_4D_LiDAR_Image_Fusion_Transformer_for_3D_Object_CVPR_2022_paper.pdf |   | NuScenes |
| BrT | https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Bridged_Transformer_for_Vision_and_Point_Cloud_3D_Object_Detection_CVPR_2022_paper.pdf |  | ScanNetV2/ SUNRGBD |
