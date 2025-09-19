

<div align="center">
<h3>[🎉NeurIPS 2025!]Genesis: Multimodal Driving Scene Generation with Spatio-Temporal and Cross-Modal Consistency</h3>

Xiangyu Guo<sup>1\*</sup>, Zhanqian Wu<sup>2\*</sup>, Kaixin Xiong<sup>2\*</sup>, Ziyang Xu<sup>1</sup>, Lijun Zhou<sup>2</sup>, Gangwei Xu<sup>1</sup>, 
Shaoqing Xu<sup>2</sup>,  Haiyang Sun<sup>2†</sup>,  Bing Wang<sup>2</sup>, Guang Chen<sup>2</sup>, 
Hangjun Ye<sup>2</sup>, Wenyu Liu<sup>1</sup>, Xinggang Wang<sup>1,✉</sup>

<sup>1</sup>  Huazhong University of Science and Technology
<sup>2</sup>  Xiaomi EV 

(\*) Equal contribution. (†) Project leader. (✉)Corresponding Author.

<a href="https://arxiv.org/abs/2506.07497"><img src='https://img.shields.io/badge/arXiv-Genesis-red' alt='Paper PDF'></a>
<a href="https://xiaomi-research.github.io/genesis/"><img src='https://img.shields.io/badge/Project_Page-Genesis-green' alt='Project Page'></a>
</div>


<!-- ## Introduction -->
## Abstract
We present Genesis, a unified framework for joint generation of multi-view driving videos and LiDAR sequences with spatio-temporal and cross-modal consistency. Genesis employs a two-stage architecture that integrates a DiT-based video diffusion model with 3D-VAE encoding, and a BEV-aware LiDAR generator with NeRF-based rendering and adaptive sampling. Both modalities are directly coupled through a shared latent space, enabling coherent evolution across visual and geometric domains. To guide the generation with structured semantics, we introduce DataCrafter, a captioning module built on vision-language models that provides scene-level and instance-level supervision. Extensive experiments on the nuScenes benchmark demonstrate that Genesis achieves state-of-the-art performance across video and LiDAR metrics (FVD 16.95, FID 4.24, Chamfer 0.611), and benefits downstream tasks including segmentation and 3D detection, validating the semantic fidelity and practical utility of the generated data.

## Overview
<div align="center">
<img src="assets/images/framework.png" width="1000">
</div>

## News
`[2025/09/18]` Genesis is accepted by NeurIPS 2025🎉🎉🎉!

`[2025/06/18]` [ArXiv](https://arxiv.org/abs/2506.07497) paper release. Models/Code are coming soon. Please stay tuned! ☕️

## Updates
- [x] Release Paper   
- [ ] Release Full Models  
- [ ] Release Inference Framework 
- [ ] Release Training Framework 


## Citation
If you find Genesis is useful in your research or applications, please consider giving us a star 🌟 and citing it by the following BibTeX entry.

```bibtex
@article{guo2025genesis,
  title={Genesis: Multimodal Driving Scene Generation with Spatio-Temporal and Cross-Modal Consistency},
  author={Guo, Xiangyu and Wu, Zhanqian and Xiong, Kaixin and Xu, Ziyang and Zhou, Lijun and Xu, Gangwei and Xu, Shaoqing and Sun, Haiyang and Wang, Bing and Chen, Guang and others},
  journal={arXiv preprint arXiv:2506.07497},
  year={2025}
}
```
