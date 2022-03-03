# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.3

------

## :paperclip:  今日要点

1. [商汤提出cosFormer：在注意力中重新思考Softmax](https://mp.weixin.qq.com/s/fpDKnaJvTWZhRmGRvk4Yvg)         :star::star:
   - Abstract: 商汤提出cosFormer：在注意力中重新思考Softmax
   - Paper: [COSFORMER : RETHINKING SOFTMAX IN ATTENTION](https://arxiv.org/pdf/2202.08791.pdf)
   - Tips:  COSFORMER 的关键思路在于将不可分解非线性 softmax 操作替换为具有可分解非线性重加权机制的线性操作。该模型适用于随机注意力和交叉注意力，并且输入序列长度具有线性时间和空间复杂度，从而在建模长程依赖中显示出强大的能力。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicoaChsDYzlI4M82sCucRSaMR7lOA8MM1kdxyJOVXA6BUkmxYiaicWzWFylvvNoheiaqiabk6wiaHoVicbw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [一张照片就能生成3D模型，GAN和自动编码器碰撞出奇迹，苏黎世联邦理工学院出品](https://mp.weixin.qq.com/s/i7vBrs1ODVDhU5NkmL3Rmg)       :star::star:
   - Abstract: 一张照片就能生成3D模型，GAN和自动编码器碰撞出奇迹，苏黎世联邦理工学院出品
   - Paper: [Pix2NeRF: Unsupervised Conditional π-GAN for Single Image to Neural Radiance Fields Translation](https://arxiv.org/abs/2202.13162)
   - Code: [https://github.com/sxyu/pixel-nerf](https://github.com/sxyu/pixel-nerf)
   - Tips: 首先，自动编码器可以通过无监督学习，来获取输入图像的隐藏特征，包括物体姿态和物体形状，并利用学习到的特征重建出原始的数据；然后，再利用GAN来通过姿态和形状数据，重构出与原来的物体形状不同的新视图。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/YicUhk5aAGtBPib0LjLrvUw6IRXqUHfCjznA7icuwCIuIV0Gl6SLVDPEfH8vx1SzDkvSo04GEyvupgia5XAh2epTVQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR 2022 | 南开程明明团队和天大提出LD：目标检测的定位蒸馏](https://mp.weixin.qq.com/s/dxss8RjJH283h6IbPCT9vg)       :star::star:
   - Abstract: 南开程明明团队和天大提出LD：目标检测的定位蒸馏
   - Paper: [Localization Distillation for Dense Object Detection](https://arxiv.org/abs/2102.12252)
   - Code: [https://github.com/HikariTJU/LD](https://github.com/HikariTJU/LD)
   - Tips: : 把用于分类head的KD（知识蒸馏），用于目标检测的定位head，即有了LD （Localization Distillation）。LD使得logit mimicking首次战胜了Feature imitation。分类知识与定位知识的蒸馏应分而治之、因地制宜。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oWI8SkLuGDQoictYSoAziaZldNKiagssGQxHTYmXP2TEVs6ibibx2YPRbn1RJ6UjqFuKHHIVfLnmK4bRZA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [新目标检测框架 | 基于改进的one-shot的目标检测](https://mp.weixin.qq.com/s/mEItJ5cZzFC3dr_64vokCQ)       :star::star:
   - Abstract: 基于改进的one-shot的目标检测OSCD
   - Paper: [OSCD: A one-shot conditional object detection framework](https://www.sciencedirect.com/science/article/pii/S0925231220306779?via%3Dihub)
   - Tips: 研究者就提出了将检测问题更好地命名为one-shot条件目标检测。并设计了一个基于可学习度量和two-stages检测模型的通用one-shot条件目标检测框架(OSCD)。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNlphibB3Rhz9ia1jAjjo8voJbfjiatNCnpM1usUHQWU46CM2Glqg37B6YuVurSK2hOicpkYNxKbHANlA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [CVPR 2022放榜！2067篇论文被接收，Masked Autoencoders 能否夺得最佳论文？](https://mp.weixin.qq.com/s/_FOLwn_0IHsme8iQoHBipA)       :star::star:
   - Abstract: Auto-Sklearn：CVPR 2022放榜！2067篇论文被接收，Masked Autoencoders 能否夺得最佳论文？
   - Paper: [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377)
   - Tips: 这篇论文展示了一种被称为掩蔽自编码器（masked autoencoders，MAE）的新方法，可以用作计算机视觉的可扩展自监督学习器。MAE 基于两个核心理念：研究人员开发了一个非对称编码器 - 解码器架构，其中一个编码器只对可见的 patch 子集进行操作（没有掩蔽 token），另一个简单解码器可以从潜在表征和掩蔽 token 重建原始图像。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8Mwx3prCpIEibE9wGzibGXuegLxdwiazpN9OUiazsTTTiaib8qib5qTVmU77UhvSm42BEoWO13ettGnTQyA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [最新 955 不加班的公司名单（2022版）](https://mp.weixin.qq.com/s/kNIDs-4baFh1QakSgxCHFg)       :star::star:
   - Abstract: 最新 955 不加班的公司名单（2022版）
   - Tips: 以下公司名单，基本不属于 996 的公司，相对接近 955/965 的水平，但是依旧要看部门和地区，不能保证完全准确性。

<div align=center><img src="./notes/202203/images/20220303.jpeg" style='zoom:100%'>
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