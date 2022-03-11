# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.11

------

## :paperclip:  今日要点

1. [CVPR | Facebook提出FP-NAS：搜索速度更快、分类精度更高、性能更好](https://mp.weixin.qq.com/s/4v0grlvv7wARd_Dh5_uD_g)         :star::star:
   - Abstract: Facebook提出FP-NAS：搜索速度更快、分类精度更高、性能更好
   - Paper: [FP-NAS: Fast Probabilistic Neural Architecture Search](https://arxiv.org/abs/2011.10949)
   - Tips:  该算法采用自适应架构概率分布熵的架构采样，能够减少采样样本达 60%，加速搜索快 1.8 倍。此外，该算法还包括一种新的基于分解概率分布的由粗到细的搜索策略，进一步加速搜索快达 1.2 倍。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwPxfJIiaWYwh2arlsxvdZLDtQYeiapticwXfSjUolTu56HXccKaPA4FArwVffqvoTEIn7WwcQXXptRrQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR最有趣论文 | 再模糊的照片AI都可以可以恢复](https://mp.weixin.qq.com/s/KmizgnGOfirFh08UFX_G7Q)       :star::star:
   - Abstract: 再模糊的照片AI都可以可以恢复
   - Paper: [Towards Real-World Blind Face Restoration with Generative Facial Prior](https://arxiv.org/pdf/2101.04061.pdf)
   - Code: [https://github.com/TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN)
   - Tips:  GFP-GAN框架的概述：它包括一个degradation removal模块和一个预先训练好的face GAN作为 facial prior。它们由latent code映射和几个Channel-Split Spatial Feature Transform(CSSFT)层。所提出的CS-SFT调制实现了良好的保真度和保真度平衡。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwPxfJIiaWYwh2arlsxvdZLDtgGm8wGl9SwWy2ZWM4Flmyr0hUoo9uzp7sxagDT9j8slJwfkd4eAMyQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




3. [ZippyPoint: 一种基于学习的特征点提取+二进制描述子，速度提升5倍+，为移动平台提供一种ORB的替代方案](https://mp.weixin.qq.com/s/1Kw3j6yT7koZdJ0HDUm93g)       :star::star:
   - Abstract: MIT最新研究：ZippyPoint: 一种基于学习的特征点提取+二进制描述子，速度提升5倍+，为移动平台提供一种ORB的替代方案
   - Paper: [ZippyPoint: Fast Interest Point Detection, Description, and Matching through Mixed Precision Discretization](https://arxiv.org/abs/2203.03610)
   - Tips: 本文设计了ZippyPoint，它是一个用于特征点提取的网络。与ORB的描述子类似，ZippyPoint得到的也是二进制描述子。该特征点可以获得与基于学习的特征匹配以及视觉定位性能，同时速度提升5倍。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/RkDHyHvXvJ6yBlr3JfYhXF9GSagyDaWxIDrlA5QjG8fNkhhGZ2tmiasQ3iau6QutoEnUfhtIpiaOLd7ww76WAkmiaw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




4. [CVPR 2022 最新 65 篇论文分方向整理｜包含目标检测、动作识别、人群计数等方向（附打包下载）](https://mp.weixin.qq.com/s/TAMflTf8RBtHBknom9F6yw)       :star::star:
   - Abstract: CVPR 2022 最新 65 篇论文分方向整理｜包含目标检测、动作识别、人群计数等方向
   - Address: [https://bbs.cvmart.net/articles/6124](https://bbs.cvmart.net/articles/6124)
   - Tips: 65 篇 CVPR 2022 论文，包含目标检测、异常检测、超分辨率、姿态估计、三维重建、医学影像、动作识别、人群计数、视觉预测、图像特征匹配等方向。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfo3T7brEa3n6ropDWL85EHYQFBicwQpdUH7LExY7qUSv6qE40thCehaSfoHNrxicclk3vRdj6d42mHg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [YOLOv5-Lite 详解教程 | 嚼碎所有原理、训练自己数据集、TensorRT部署落地应有尽有](https://mp.weixin.qq.com/s/CuLuoaGaN8AaXj67Y1Y21A)       :star::star:
   - Abstract: YOLOv5-Lite 详解教程
   - Tips: YOLOv5 Lite在YOLOv5的基础上进行一系列消融实验，使其更轻（Flops更小，内存占用更低，参数更少），更快（加入shuffle channel，yolov5 head进行通道裁剪，在320的input_size至少能在树莓派4B上的推理速度可以达到10+FPS），更易部署（摘除Focus层和4次slice操作，让模型量化精度下降在可接受范围内）。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/5ooHoYt0tgnkY0YNkpaibu2ZxNOjEdtOMA75WP85XzHicdFzCSJcibMmfLIia6yaTBcF7Ux5VH4zThrlO2YGDFQjRw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




6. [模型量化技巧及在低功耗IOT设备的应用实践](https://mp.weixin.qq.com/s/KWyM3mgvZhtlcuXaodNJ3A)       :star::star:
   - Abstract: 模型量化技巧及在低功耗IOT设备的应用实践
   - Tips: 本文介绍了神经网络模型在轻量级设备的部署技巧，具体内容包括神经网络模型量化的基本原理和主要方法，以及部分低功耗IOT设备上模型部署的实例与技巧。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/xm3mwmQ97RcWfJt9Zonu6uzOY7RzOUkoAbS0M73icWY6sATPMbenPxib9IJTQebFYpiaXOA2ElqytjFDPmwVm9Zdw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




## :paperclip:  历史更新

<pre><details><summary>2021年</summary>
<details><summary>3月</summary>
    1. <a href="notes/202103/0321.md" target="_blank">公众号内容拓展学习笔记（2021.3.21）</a>
    2. <a href="notes/202103/0322.md" target="_blank">公众号内容拓展学习笔记（2021.3.22）</a>
    3. <a href="notes/202103/0323.md" target="_blank">公众号内容拓展学习笔记（2021.3.23）</a>
    4. <a href="notes/202103/0324.md" target="_blank">公众号内容拓展学习笔记（2021.3.24）</a>
    5. <a href="notes/202103/0325.md" target="_blank">公众号内容拓展学习笔记（2021.3.25）</a>
    6. <a href="notes/202103/0326.md" target="_blank">公众号内容拓展学习笔记（2021.3.26）</a>
    7. <a href="notes/202103/0327.md" target="_blank">公众号内容拓展学习笔记（2021.3.27）</a>
    8. <a href="notes/202103/0328.md" target="_blank">公众号内容拓展学习笔记（2021.3.28）</a>
    9. <a href="notes/202103/0329.md" target="_blank">公众号内容拓展学习笔记（2021.3.29）</a>
    10. <a href="notes/202103/0330.md" target="_blank">公众号内容拓展学习笔记（2021.3.30）</a>
    11. <a href="notes/202103/0331.md" target="_blank">公众号内容拓展学习笔记（2021.3.31）</a>
</details>
<details><summary>4月</summary>
    1. <a href="notes/202104/0401.md" target="_blank">公众号内容拓展学习笔记（2021.4.1）</a>
    2. <a href="notes/202104/0402.md" target="_blank">公众号内容拓展学习笔记（2021.4.2）</a>
    3. <a href="notes/202104/0403.md" target="_blank">公众号内容拓展学习笔记（2021.4.3）</a>
    4. <a href="notes/202104/0404.md" target="_blank">公众号内容拓展学习笔记（2021.4.4）</a>
    5. <a href="notes/202104/0405.md" target="_blank">公众号内容拓展学习笔记（2021.4.5）</a>
    6. <a href="notes/202104/0406.md" target="_blank">公众号内容拓展学习笔记（2021.4.6）</a>
    7. <a href="notes/202104/0407.md" target="_blank">公众号内容拓展学习笔记（2021.4.7）</a>
    8. <a href="notes/202104/0408.md" target="_blank">公众号内容拓展学习笔记（2021.4.8）</a>
    9. <a href="notes/202104/0409.md" target="_blank">公众号内容拓展学习笔记（2021.4.9）</a>
    10. <a href="notes/202104/0410.md" target="_blank">公众号内容拓展学习笔记（2021.4.10）</a>
    11. <a href="notes/202104/0411.md" target="_blank">公众号内容拓展学习笔记（2021.4.11）</a>
    12. <a href="notes/202104/0412.md" target="_blank">公众号内容拓展学习笔记（2021.4.12）</a>
    13. <a href="notes/202104/0413.md" target="_blank">公众号内容拓展学习笔记（2021.4.13）</a>
    14. <a href="notes/202104/0414.md" target="_blank">公众号内容拓展学习笔记（2021.4.14）</a>
    15. <a href="notes/202104/0415.md" target="_blank">公众号内容拓展学习笔记（2021.4.15）</a>
    16. <a href="notes/202104/0416.md" target="_blank">公众号内容拓展学习笔记（2021.4.16）</a>
    17. <a href="notes/202104/0417.md" target="_blank">公众号内容拓展学习笔记（2021.4.17）</a>
    18. <a href="notes/202104/0418.md" target="_blank">公众号内容拓展学习笔记（2021.4.18）</a>
    19. <a href="notes/202104/0419.md" target="_blank">公众号内容拓展学习笔记（2021.4.19）</a>
    20. <a href="notes/202104/0420.md" target="_blank">公众号内容拓展学习笔记（2021.4.20）</a>
    21. <a href="notes/202104/0421.md" target="_blank">公众号内容拓展学习笔记（2021.4.21）</a>
    22. <a href="notes/202104/0422.md" target="_blank">公众号内容拓展学习笔记（2021.4.22）</a>
    23. <a href="notes/202104/0423.md" target="_blank">公众号内容拓展学习笔记（2021.4.23）</a>
    24. <a href="notes/202104/0424.md" target="_blank">公众号内容拓展学习笔记（2021.4.24）</a>
    25. <a href="notes/202104/0425.md" target="_blank">公众号内容拓展学习笔记（2021.4.25）</a>
    26. <a href="notes/202104/0426.md" target="_blank">公众号内容拓展学习笔记（2021.4.26）</a>
    27. <a href="notes/202104/0427.md" target="_blank">公众号内容拓展学习笔记（2021.4.27）</a>
    28. <a href="notes/202104/0428.md" target="_blank">公众号内容拓展学习笔记（2021.4.28）</a>
    29. <a href="notes/202104/0429.md" target="_blank">公众号内容拓展学习笔记（2021.4.29）</a>
    30. <a href="notes/202104/0430.md" target="_blank">公众号内容拓展学习笔记（2021.4.30）</a>
</details>
<details><summary>5月</summary>
    1. <a href="notes/202105/0501.md" target="_blank">公众号内容拓展学习笔记（2021.5.1）</a>
    2. <a href="notes/202105/0502.md" target="_blank">公众号内容拓展学习笔记（2021.5.2）</a>
    3. <a href="notes/202105/0503.md" target="_blank">公众号内容拓展学习笔记（2021.5.3）</a>
    4. <a href="notes/202105/0504.md" target="_blank">公众号内容拓展学习笔记（2021.5.4）</a>
    5. <a href="notes/202105/0505.md" target="_blank">公众号内容拓展学习笔记（2021.5.5）</a>
    6. <a href="notes/202105/0506.md" target="_blank">公众号内容拓展学习笔记（2021.5.6）</a>
    7. <a href="notes/202105/0507.md" target="_blank">公众号内容拓展学习笔记（2021.5.7）</a>
    8. <a href="notes/202105/0508.md" target="_blank">公众号内容拓展学习笔记（2021.5.8）</a>
    9. <a href="notes/202105/0509.md" target="_blank">公众号内容拓展学习笔记（2021.5.9）</a>
    10. <a href="notes/202105/05010.md" target="_blank">公众号内容拓展学习笔记（2021.5.10）</a>
    11. <a href="notes/202105/05011.md" target="_blank">公众号内容拓展学习笔记（2021.5.11）</a>
    12. <a href="notes/202105/05012.md" target="_blank">公众号内容拓展学习笔记（2021.5.12）</a>
    13. <a href="notes/202105/05013.md" target="_blank">公众号内容拓展学习笔记（2021.5.13）</a>
    14. <a href="notes/202105/05014.md" target="_blank">公众号内容拓展学习笔记（2021.5.14）</a>
    15. <a href="notes/202105/05015.md" target="_blank">公众号内容拓展学习笔记（2021.5.15）</a>
    16. <a href="notes/202105/05016.md" target="_blank">公众号内容拓展学习笔记（2021.5.16）</a>
    17. <a href="notes/202105/05027.md" target="_blank">公众号内容拓展学习笔记（2021.5.27）</a>
</details>
<details><summary>9月</summary>
    1. <a href="notes/202109/0930.md" target="_blank">公众号内容拓展学习笔记（2021.9.30）</a>
</details>
<details><summary>10月</summary>
    1. <a href="notes/202110/1001.md" target="_blank">公众号内容拓展学习笔记（2021.10.1）</a>
    2. <a href="notes/202110/1002.md" target="_blank">公众号内容拓展学习笔记（2021.10.2）</a>
    3. <a href="notes/202110/1003.md" target="_blank">公众号内容拓展学习笔记（2021.10.3）</a>
    4. <a href="notes/202110/1004.md" target="_blank">公众号内容拓展学习笔记（2021.10.4）</a>
    5. <a href="notes/202110/1006.md" target="_blank">公众号内容拓展学习笔记（2021.10.6）</a>
    6. <a href="notes/202110/1008.md" target="_blank">公众号内容拓展学习笔记（2021.10.8）</a>
    7. <a href="notes/202110/1016.md" target="_blank">公众号内容拓展学习笔记（2021.10.16）</a>
    8. <a href="notes/202110/1018.md" target="_blank">公众号内容拓展学习笔记（2021.10.18）</a>
</details>
</pre>
<pre><details><summary>2022年</summary>
<details><summary>1月</summary>
    1. <a href="notes/202201/0120.md" target="_blank">公众号内容拓展学习笔记（2022.1.20）</a>
</details>
<details><summary>2月</summary>
    1. <a href="notes/202202/0225.md" target="_blank">公众号内容拓展学习笔记（2022.2.25）</a>
    2. <a href="notes/202202/0226.md" target="_blank">公众号内容拓展学习笔记（2022.2.26）</a>
    3. <a href="notes/202202/0227.md" target="_blank">公众号内容拓展学习笔记（2022.2.27）</a>
    4. <a href="notes/202202/0228.md" target="_blank">公众号内容拓展学习笔记（2022.2.28）</a>
</details>
<details><summary>3月</summary>
    1. <a href="notes/202203/0301.md" target="_blank">公众号内容拓展学习笔记（2022.3.1）</a>
    2. <a href="notes/202203/0302.md" target="_blank">公众号内容拓展学习笔记（2022.3.2）</a>
    3. <a href="notes/202203/0303.md" target="_blank">公众号内容拓展学习笔记（2022.3.3）</a>
    4. <a href="notes/202203/0304.md" target="_blank">公众号内容拓展学习笔记（2022.3.4）</a>
    5. <a href="notes/202203/0305.md" target="_blank">公众号内容拓展学习笔记（2022.3.5）</a>
    6. <a href="notes/202203/0306.md" target="_blank">公众号内容拓展学习笔记（2022.3.6）</a>
    7. <a href="notes/202203/0307.md" target="_blank">公众号内容拓展学习笔记（2022.3.7）</a>
    8. <a href="notes/202203/0308.md" target="_blank">公众号内容拓展学习笔记（2022.3.8）</a>
    9. <a href="notes/202203/0309.md" target="_blank">公众号内容拓展学习笔记（2022.3.9）</a>
    10. <a href="notes/202203/0310.md" target="_blank">公众号内容拓展学习笔记（2022.3.10）</a>
    11. <a href="notes/202203/0311.md" target="_blank">公众号内容拓展学习笔记（2022.3.11）</a>
</details>
</pre>


## :paperclip:  Others

- 由于图片权限问题，[GitHub](https://github.com/xiaoxuebajie/dairly_learning)是完整版，可以点点 star
- 星标的数量是与个人相关程度，不代表文章内容的好坏
- 关注我的[个人网站](http://www.cvbds.cn/)
- 关注我的[CSDN](https://blog.csdn.net/xiaoxuebajie)博客
- 关注我的[哔哩哔哩](https://space.bilibili.com/424394389)
- 关注我的公众号CV伴读社

<div align=center><img src="https://img-blog.csdnimg.cn/202005031406335.jpg" style='zoom:80%'>
</div>