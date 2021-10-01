# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.10.1

------



## :paperclip:  今日要点

1. [ICCV 2021 | 英伟达新研究：直接通过视频就能捕获3D人体动作！](https://mp.weixin.qq.com/s/b3qJSrC-aevPlBc89GwCAw)         :star::star:
   - Abstract: 英伟达新研究直接通过视频就能捕获3D人体动作
   - Paper: [Physics-based Human Motion Estimation and Synthesis from Videos](https://arxiv.org/abs/2109.09913)
   - Tips:  用输入视频生成动作序列，然后建模成3D人体，再进行优化，最后就可以像使用标准动作捕捉数据集一样使用它们来训练你的动作生成模型

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/YicUhk5aAGtATo98PmhyiavfJNjnFHKxcOiaGoaMfHxM7HGbmibExPxm04ndEXAT0dFuk7jHQeTYNddHjnuUmRia8eA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


2. [NeurIPS 2021 | Twins：更高效的Transformer主干网！完美适配下游检测、分割任务](https://mp.weixin.qq.com/s/jqbPt5yXKPdEnW3WzAno9g)       :star::star:
   - Abstract: Twins 更高效的 Transformer 主干网，完美适配下游检测、分割任务
   - Paper: [Twins: Revisiting the Design of Spatial Attention in Vision Transformers](https://arxiv.org/abs/2104.13840)
   - Code: [https://github.com/Meituan-AutoML/Twins](https://github.com/Meituan-AutoML/Twins)
   - Tips: 这篇文章 Twins 提出了两种新的 Transformer 架构，分别起名叫 Twins-PCPVT 和 Twins-SVT

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oUS4c203L60Fe8iaeSZeuVCII06bbQ161hPia4jAricic6wrGcjbJZzcOEpESXXjYiawgRal3pzTHfgf4w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oUS4c203L60Fe8iaeSZeuVCIZYuyHrdYB8bez6iaibymWaNJCOaA9XicBopicDeXZ5GIIY9z14sCsEc59A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [完美抠图王冰冰！字节实习生开发的 AI，实现 4K60 帧视频实时抠图，连头发丝都根根分明](https://mp.weixin.qq.com/s/kHMWQ8D-mQWJltwGp2dt2w)       :star::star:
   - Abstract: 实现 4K60 帧视频实时抠图，连头发丝都根根分明
   - Paper: [Robust High-Resolution Video Matting with Temporal Guidance](https://arxiv.org/abs/2108.11515)
   - Code: [https://github.com/PeterL1n/RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)
   - Demo: [https://peterl1n.github.io/RobustVideoMatting/#/demo](https://peterl1n.github.io/RobustVideoMatting/#/demo)
   - Tips: 除了一些遮挡或者阴暗效果较差以外，性能都非常理想。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/libMic1J2Kj4r3QiaXMFCHviaMoYfKRs5JonGiciamcicUwH3GcFUO5I6f5RsfHIL7DsPaKPAwvjdicrIwr8yDmIVgshvw/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


4. [图特征金字塔应用在目标检测，最终精度大幅度提升（附论文下载）](https://mp.weixin.qq.com/s/X25kEQDF9KM4xPgfliaD0g)       :star::star:
   - Abstract:  图特征金字塔应用在目标检测，精度大幅度提升
   - Paper: [GraphFPN: Graph Feature Pyramid Network for Object Detection](https://arxiv.org/pdf/2108.00580.pdf)
   - Tips: 图特征金字塔网络可以增强卷积特征金字塔网络的多尺度特征

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwPVaibPicy7Txh9tIVUnUiaicLogIhGNriaaEJmzMASibWUiaicwmlAp7hDLDibdYOGYxdEibJhFCkDXYZhPyfQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [图像去模糊算法代码实践！](https://mp.weixin.qq.com/s/pHUqQ-6dPpVAHD71h6Gxgg)       :star::star:
   - Abstract: 图像去模糊算法代码实践
   - Tips: 采用的方法DeblurGANv2

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/vI9nYe94fsEIfkFYyX4FjBiavmerdnlBIiaIhRwW7fGn23p1HKP6Rljic7Do9ggdN7yTlTvxylrmCKByPGcLXibASQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [Batch Size 对 神经网络训练的影响](https://mp.weixin.qq.com/s/cVMOGS64KR5gLuuoco2x1w)       :star::star:
   - Abstract: Batch Size 对 神经网络训练的影响
   - Tips: 主要介绍了batch size对于网络训练的影响以及如何调整。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_png/gYUsOT36vfqc1hq4Picemq0ElPXMbB6EOvxWibqW5VolPgzGNgavbEKYu2SlovPC8qv7SWciabk0zeETIHrzFZBKg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    1. <a href="notes/202110/1001.md" target="_blank">公众号内容拓展学习笔记（2021.9.30）</a>
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