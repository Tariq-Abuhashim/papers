## List of key papers:
### DETR:
- [**DETR**](https://arxiv.org/abs/2005.12872):End-to-End Object Detection with Transformers. 
- Deformable Convolutional Networks. [paper](https://arxiv.org/abs/1703.06211)  
- [**Deformable DETR**](https://arxiv.org/abs/2010.04159): Deformable Transformers for End-to-End Object Detection.  
- [**DAB-DETR**](https://arxiv.org/abs/2201.12329): Dynamic Anchor Boxes are Better Queries for DETR.  
- [**DN-DETR**](https://arxiv.org/abs/2203.01305): Accelerate DETR Training by Introducing Query DeNoising.  
- [**DINO**](https://arxiv.org/abs/2203.03605): DETR with Improved DeNoising AnchorBoxes for End-to-End Object Detection.  
- [**DETRs Beat YOLOs**](https://arxiv.org/abs/2304.08069) on Real-time Object Detection.  
- [**RT-DETRv3**](https://arxiv.org/abs/2409.08475): Real-time End-to-End Object Detection with Hierarchical Dense Positive Supervision.

### Language
- Attention Is All You Need. [paper](https://arxiv.org/abs/1706.03762)  
- Transformer Self-Attention Mechanism Visualized. [video](https://www.youtube.com/watch?v=u8pSGp__0Xk)  
- Neural Networks: Zero to Hero. [website](https://karpathy.ai/zero-to-hero.html)  
- Language Models are Few-Shot Learners. [paper](https://arxiv.org/abs/2005.14165)  
- OpenAI Agents SDK. [code](https://github.com/openai/openai-agents-python?tab=readme-ov-file)  
- MetaGPT: The Multi-Agent Framework. [code](https://github.com/geekan/MetaGPT)
- **DeepSeek**:
    - [**DeepSeekMoE**](https://arxiv.org/abs/2401.06066): Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models.
    - [**Auxiliary-Loss-Free**](https://arxiv.org/abs/2408.15664) Load Balancing Strategy for Mixture-of-Experts.
    - [**DeepSeek-V3**](https://arxiv.org/abs/2412.19437) Technical Report.
    - [**DeepSeek-R1**](https://arxiv.org/abs/2501.12948): Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.
- [**SpatialLM**](https://manycore-research.github.io/SpatialLM): Large Language Model for Spatial Understanding.
    - [**SceneScript**](https://arxiv.org/abs/2403.13064): Reconstructing Scenes With An Autoregressive Structured Language Model.
    - [**MASt3R-SLAM**](https://arxiv.org/abs/2412.12392): Real-Time Dense SLAM with 3D Reconstruction Priors.

### Multimodal
- [**ViT**](https://arxiv.org/abs/2010.11929): An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.  
- [**PaLM-E**](https://arxiv.org/abs/2303.03378): An Embodied Multimodal Language Model.
- [**M2T2**](https://arxiv.org/abs/2311.00926): Multi-Task Masked Transformer for Object-centric Pick and Place.
[]()

### Visual SLAM
- **ORB-SLAM**: [v2](https://arxiv.org/abs/1610.06475), [v3](https://arxiv.org/abs/2007.11898), [semi-Dense](https://www.roboticsproceedings.org/rss11/p41.pdf)  
- [**DROID-SLAM**](https://arxiv.org/abs/2108.10869): Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras.
- **Deep Patch**: a new deep learning system for monocular Visual [Odometry](https://arxiv.org/abs/2208.04726) and [SLAM](https://arxiv.org/abs/2408.01654)  
[]()

### Collaborative SLAM
- [**COVINS**](https://arxiv.org/abs/2108.05756): Visual-Inertial SLAM for Centralized Collaboration.
- [**SlideSLAM**](https://arxiv.org/abs/2406.17249): Sparse, Lightweight, Decentralized Metric-Semantic SLAM for Multi-Robot Navigation. 
[]()  

### Point-Clouds
- Difference of Normals as a Multi-Scale Operator in Unorganized Point Clouds. [paper](https://arxiv.org/abs/1209.1759)  
- Fast Range Image-Based Segmentation of Sparse 3D Laser Scans for Online Operation. [paper](https://www.ipb.uni-bonn.de/pdfs/bogoslavskyi16iros.pdf)  
- [**PointNet**](https://arxiv.org/abs/1612.00593): Deep Learning on Point Sets for 3D Classification and Segmentation. 
- [**PointNet++**](https://arxiv.org/abs/1706.02413): Deep Hierarchical Feature Learning on Point Sets in a Metric Space.
- [**VoxelNet**](https://arxiv.org/abs/1711.06396): End-to-End Learning for Point Cloud Based 3D Object Detection.
- [**PointPillars**](https://arxiv.org/abs/1812.05784): Fast Encoders for Object Detection from Point Clouds.
- **SEGCloud**: Semantic Segmentation of 3D Point Clouds. [paper](https://arxiv.org/abs/1710.07563), [supplementary](https://cvgl.stanford.edu/projects/segcloud/supplementary.pdf)  
[]()

### Structure from Motion
- [**GLOMAP**](https://arxiv.org/abs/2407.20219): Global Structure-from-Motion Revisited.
- 3D Line Mapping Revisited. [paper](https://arxiv.org/abs/2303.17504), [supplementary](http://b1ueber2y.me/projects/LIMAP/limap-supp.pdf)  
 

### LiDAR SLAM 
- [**Faster-LIO**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9718203): Lightweight Tightly Coupled Lidar-Inertial Odometry Using Parallel Sparse Incremental Voxels.  
[]()

### Object Tracking
- SORT. [paper](https://arxiv.org/abs/1602.00763), [code](https://github.com/abewley/sort)
- with deep association metric. [paper](https://arxiv.org/abs/1703.07402), [code](https://github.com/nwojke/deep_sort)
- with deep cosine metric learning for re-identification. [paper](https://arxiv.org/abs/1812.00442)

**When to use what?** This table compares SORT with newer algorithms based on your needs:

| Algorithm    | Year | Key Improvement | Notes |
|--------------|------|-----------------| -------|
| [**SORT**](https://arxiv.org/abs/1602.00763) | 2016 | Real-time, Kalman filter + Hungarian algo | Fast but prone to ID switches |
| [**DeepSORT**](https://arxiv.org/abs/1703.07402) | 2017 | Adds appearance descriptors (ReID) | More robust, slower than SORT |
| [**FairMOT**](https://arxiv.org/abs/2004.01888) | 2020 | Joint detection + ReID (anchor-free) | Good for crowded scenes |
| [**ByteTrack**](https://arxiv.org/abs/2110.06864) | 2021 | Uses low-confidence detections | Better occlusion handling, near real-time |
| [**OC-SORT**](https://arxiv.org/abs/2203.14360) | 2022 | Occlusion-aware motion model | Fewer ID switches |
| [**BoT-SORT**](https://arxiv.org/abs/2206.14651) | 2022 | Motion + appearance + camera compensation | SOTA on MOT17/MOT20 |
| [**StrongSORT**](https://arxiv.org/abs/2202.13514) | 2022 | BoT-SORT + stronger ReID | High accuracy, slower |
| [**MOTR**](https://arxiv.org/abs/2105.03247) (Transformer) | 2022 | Built upon DETR query-based tracking | Heavy but cutting-edge |

- **Need speed?** → SORT or ByteTrack
- **Crowded scenes?** → BoT-SORT or OC-SORT  
- **Best accuracy?** → StrongSORT ([code](https://github.com/dyhBUPT/StrongSORT))
- **Cutting-edge?** → MOTR ([code](https://github.com/megvii-research/MOTR))

### Applications
- Automatic number plate recognition with Python, Yolov8 and EasyOCR. [video](https://www.youtube.com/watch?v=fyJB1t0o0ms), [code](https://github.com/computervisioneng/automatic-number-plate-recognition-python-yolov8)
- [**TreeScope**](https://arxiv.org/abs/2310.02162): An Agricultural Robotics Dataset for LiDAR-Based Mapping of Trees in Forests and Orchards.  
[]()  

### Website creation
- The source [code](https://github.com/nerfies/nerfies.github.io) for the [Nerfies website](https://nerfies.github.io/).
