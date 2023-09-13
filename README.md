<div align="center">

 <img width="100%" src="com.png">

</div>

<div align="center">

[简体中文](README.md) | [English](README.EN.md) | [Paper](https://arxiv.org/abs/2308.06743)
# TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution
这里是论文[TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution]((https://arxiv.org/abs/2308.06743))的官方复现仓库。TextDiff是一个场景文字超分辨率优化模型（详见[论文](https://arxiv.org/abs/2308.06743)).
</div>

# 使用指南



## 环境配置
### 深度学习环境
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

### 数据集
- <a href="https://github.com/WenjiaWang0312/TextZoom" title="点击可跳转到TextZoom">下载TextZoom数据集</a>

### 相关权重文件
- <a href="https://github.com/ayumiymk/aster.pytorch" title="点击可跳转到TextZoom">下载Aster model权重文件</a>
- <a href="https://github.com/Canjie-Luo/MORAN_v2" title="点击可跳转到TextZoom">下载Moran model权重文件</a>
- <a href="https://github.com/meijieru/crnn.pytorch" title="点击可跳转到TextZoom">下载CRNN model权重文件</a>


# To-do lists

- [ ] 添加训练代码
- [ ] 添加推理代码
- [ ] 使用DPM_solver减少推理步长
- [ ] 上传Inference notebook，方便复现


# 感谢

- 如果你觉得TextDiff对你有帮助，请给个star，谢谢！
- 如果你有任何问题，欢迎提issue，我会尽快回复。
- 如果你想交流，欢迎给我发邮件**baolin@bupt.edu.cn**，备注：**TextDiff**。
- 如果你愿意将TextDiff作为你的项目的baseline，欢迎引用我们的论文。


# References
<div id="refer-anchor-1"></div>

- [1] 
