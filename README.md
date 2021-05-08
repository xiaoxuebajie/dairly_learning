# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.8

------



## :paperclip:  今日要点

1. [MLP回归，无需卷积、自注意力，纯多层感知机视觉架构媲美CNN、ViT](https://mp.weixin.qq.com/s/gK6OHqH5zEWKVPGGfJBVxg)         :star::star:
   - Abstract: 一种舍弃卷积和自注意力且完全使用多层感知机（MLP）的视觉网络架构 MLP-Mixer 
   - Paper: [MLP-Mixer: An all-MLP Architecture for Vision](https://arxiv.org/pdf/2105.01601.pdf)
   - Code: [https://github.com/google-research/vision_transformer/tree/linen](https://github.com/google-research/vision_transformer/tree/linen)
   - Tips: Mixer 架构的设计思想是清楚地将按位置（channel-mixing）操作 (i) 和跨位置（token-mixing）操作 (ii) 分开，两种操作都通过 MLP 来实现

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/KmXPKA19gW9ePbz8uFT0UPiad6mAibvZolcywxibZMrWWzunHYPt5bjKw9PH9EpzsVZ1J2hoSjtlTU1f5zCpOIaQw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [RepPoint及RepPointv2初探](https://mp.weixin.qq.com/s/UCTvSgqGVba4ym-f7Nr02A)       :star::star:公众号内容拓展学习笔记（2021.5.8）
   - Abstract: 基于特征采样点目标检测网络RepPoint及RepPointv2
   - Paper: [RepPoints v2: Verification Meets Regression for Object Detection](https://arxiv.org/pdf/2007.08508.pdf)
   - Code: [https://github.com/Scalsol/RepPointsV2](https://github.com/Scalsol/RepPointsV2)
   - Tips: 给出的是RepPointsV2的论文代码以及网络结构图，相对于v1主要是通过添加辅助分支来强化了定位能力

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SdQCib1UzF3ugnSAYPGGt7knCUicHJk459s166y8R8LFPrzOKia64OBoBmaTaT6zw6iazMLblvxicvjaO0g7GexLHIg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [干货｜pytorch必须掌握的的4种学习率衰减策略](https://mp.weixin.qq.com/s/N_mzevDeBE4Er-Ncj7gsRQ)       :star::star:
   - Abstract: pytorch必须掌握的的4种学习率衰减策略
   - Tips: 指数衰减、固定步长的衰减、多步长衰、余弦退火衰减

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_png/gYUsOT36vfo7NFWmf8QBM9BzaxzibhWa2xpVbXiaiaZyaKYibCRStkpu5ibAhPSJPf8g6ckp34fYWyXezpRNfcXiblzA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [CV圈杀疯了！继谷歌之后，清华、牛津等学者又发表三篇MLP相关论文，LeCun也在发声](https://mp.weixin.qq.com/s/MU4j1ORGa8fJu5J8LZkWug)       :star::star:
   - Abstract: MLP（多层感知机）真的有那么“丝滑”吗，它究竟有多大的潜力？
   - Tips: MLP->CNN->Transformer->MLP，真是兜兜绕绕又回来了，最近MLP的三兄弟大合集
     - External Attention——清华大学Jittor团队
     - RepMLP——清华大学丁贵广团队
     - Feed forward代替Attention ——牛津学者

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/Z8w2ExrFgDyGqhgclsib6vOYYHiaqKZwbYPiatfHyDA5WTP0rXtB0PVSQQs0FzdVVB9WhjdwzdvNgZ3VK6WmEQj6g/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [清华&旷视提出RepMLP：将重参数卷积嵌入到全连接层](https://mp.weixin.qq.com/s/DfQoKLl7blbhr07nYdLm0Q)       :star::star:
   - Abstract: 将重参数卷积嵌入到全连接层的RepMLP
   - Paper: [RepMLP: Re-parameterizing Convolutions into Fully-connected Layers for Image Recognition](https://arxiv.org/abs/2105.01883 )
   - Code: [https://github.com/DingXiaoH/RepMLP](https://github.com/DingXiaoH/RepMLP)
   - Tips: 本文提出一种多层感知器风格的神经网络构建模块RepMLP用于图像识别，它有一系列的全连接层构成

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/VvkhdVVVIDia19rHySo0WSnWCfQf5iaDOg0JENFPSaSE2xuYCGAmMGFysgNWODDde0UYibjbUByJFEMuVaJS8DduA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [CVPR2021 | 任何网络都能山寨！新型黑盒对抗攻击模拟未知网络进行攻击](https://mp.weixin.qq.com/s/8EBqX8fhK2rW5FLx2qh1UQ)       :star::star:
   - Abstract: 新型黑盒对抗攻击模拟未知网络进行攻击
   - Paper: [Inverting Generative Adversarial Renderer for Face Reconstruction](https://arxiv.org/abs/2009.00960)
   - Code: [https://github.com/machanic/SimulatorAttack](https://github.com/machanic/SimulatorAttack)
   - Tips:  攻击者可以在获知目标模型的最少量的信息的情况下成功地伪造出相似的模型，即模拟器。在攻击时，这就可以将大量的查询转移到模拟器上，从而将查询复杂度显著降低而不过多地改变成功率

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9ePbz8uFT0UPiad6mAibvZolccLAUcK1NZAJkhrVT3OIr7ia7ZfxSE1WpGrXITuWqsCA8sSOYjTvXTw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


## 


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