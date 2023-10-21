<div align="center">

 <img width="100%" src="com.png">

</div>

<div align="center">

[简体中文](README.md) | [English](README_EN.md) | [Paper](https://arxiv.org/abs/2308.06743)
# TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution
Here is the official reproduction repository of the paper [TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution]((https://arxiv.org/abs/2308.06743)). TextDiff is a scene text super-resolution optimization model (see [paper](https://arxiv.org/abs/2308.06743) for details).
</div>

# Network Structure
<div align="center">

 <img width="100%" src="model.png">
 </div>
 
# User Guide


## Environment configuration
### Deep Learning Environment
- python >= 3.7
- pytorch >= 1.7.0
- torchvision >= 0.8.0
- lmdb >= 0.98
- pillow >= 7.1.2
- numpy
- six
- tqdm
- python-opencv
- easydict
- yaml

### Dataset
- <a href="https://github.com/WenjiaWang0312/TextZoom" title="Click to jump toTextZoom">Download TextZoom dataset</a>

### Related weight files
- <a href="https://github.com/ayumiymk/aster.pytorch" title="Click to jump toTextZoom">Download Aster model weight file</a>
- <a href="https://github.com/Canjie-Luo/MORAN_v2" title="Click to jump toTextZoom">Download Moran model weight file</a>
- <a href="https://github.com/meijieru/crnn.pytorch" title="Click to jump toTextZoom">Download CRNN model weight file</a>

# To-do lists

- [ ] Add training code
- [ ] Add inference code
- [ ] Use DPM_solver to reduce inference step size
 
# Renderings
<div align="center"> <img width="400" src="sota.png"></div>

# Gratitude

- If you think TextDiff is helpful to you, please give it a star, thank you!
- If you have any questions, please raise an issue and I will reply as soon as possible.
- If you are willing to use TextDiff as a baseline for your project, you are welcome to cite our paper.


# References
<div id="refer-anchor-1"></div>

- [1] Scene text telescope:
Text-focused scene image super-resolution
- [2] Activating more pixels in image super-resolution
transformer.
- [3] Srdiff: Single image super-resolution
with diffusion probabilistic models.
- [4] DocDiff: Document Enhancement via Residual Diffusion Models
- [5]  Improving
Scene Text Image Super-Resolution via Dual Prior Modulation Network


# :book: Citation
If you use (part of) my code or find my work helpful, please consider citing
```
@article{liu2023textdiff,
  title={TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution},
  author={Liu, Baolin and Yang, Zongyuan and Wang, Pengfei and Zhou, Junjie and Liu, Ziqi and Song, Ziyi and Liu, Yan and Xiong, Yongping},
  journal={arXiv preprint arXiv:2308.06743},
  year={2023}
}
```

# Acknowledgement
This code is developed relying on <a href="https://github.com/Royalvice/DocDiff" title="DocDiff">DocDiff</a> and <a href="https://github.com/mjq11302010044/TATT" title="TATT">TATT</a>. Thanks for these great projects. Among them, DocDiff is the main research content of my classmate, and I participated in part of the research.

