

<div align="center">
<h3>Genesis: Multimodal Driving Scene Generation with Spatio-Temporal and Cross-Modal Consistency</h3>

Xiangyu Guo<sup>1\*</sup>, Zhanqian Wu<sup>2\*</sup>, Kaixin Xiong<sup>2\*</sup>, Ziyang Xu<sup>1</sup>, Lijun Zhou<sup>2</sup>, Gangwei Xu<sup>1</sup>, Shaoqing Xu<sup>2</sup>, <br> Haiyang Sun<sup>2†</sup>,  Bing Wang<sup>2</sup>, Guang Chen<sup>2</sup>, Hangjun Ye<sup>2</sup>, Wenyu Liu<sup>1</sup>, Xinggang Wang<sup>1,✉</sup>

<sup>1</sup>  Huazhong University of Science & Technology, <sup>2</sup>  Xiaomi EV 

(\*) Equal contribution. (†) Project leader. (✉)Corresponding Author.

<a href=""><img src='https://img.shields.io/badge/arXiv-Genesis-red' alt='Paper PDF'></a>
<a href="https://xiaomi-research.github.io/genesis/"><img src='https://img.shields.io/badge/Project_Page-Genesis-green' alt='Project Page'></a>
</div>


<!-- ## Introduction -->
## Abstract
We present Genesis, a unified framework for joint generation of multi-view driving videos and LiDAR sequences with spatio-temporal and cross-modal consistency. Genesis employs a two-stage architecture that integrates a DiT-based video diffusion model with 3D-VAE encoding, and a BEV-aware LiDAR generator with NeRF-based rendering and adaptive sampling. Both modalities are directly coupled through a shared latent space, enabling coherent evolution across visual and geometric domains. To guide the generation with structured semantics, we introduce DataCrafter, a captioning module built on vision-language models that provides scene-level and instance-level supervision. Extensive experiments on the nuScenes benchmark demonstrate that Genesis achieves state-of-the-art performance across video and LiDAR metrics (FVD 16.95, FID 4.24, Chamfer 0.611), and benefits downstream tasks including segmentation and 3D detection, validating the semantic fidelity and practical utility of the generated data.

## Overview
<div align="center">
<img src="assets/images/framework.png" width="1000">
</div>

<!-- ## News

