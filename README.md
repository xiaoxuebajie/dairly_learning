# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.6

------

## :paperclip:  今日要点

1. [CVPR 2022 | 超越Transformer！FAIR重新设计纯卷积架构：ConvNeXt](https://mp.weixin.qq.com/s/Xg5wPYExnvTqRo6s5-2cAw)         :star::star:
   - Abstract: 超越Transformer！FAIR重新设计纯卷积架构：ConvNeXt
   - Paper: [A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545)
   - Code: [https://github.com/facebookresearch/ConvNeXt](https://github.com/facebookresearch/ConvNeXt)
   - Tips:  完全标准ConvNet模块构建的ConvNeXt取得了优于Transformer的精度87.8%，在COCO检测与ADE20K分割任务上超越了SwinTransformer，同时保持了ConvNet的简单性与高效性。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfpSoBBiaAtdGUOVDmwXWFH5YI5Kq26ibtJNgbIdfjMLibEdNfd7kvY1m1iaaUSkia4XialLeRH8VgDERGLw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [YOLOS：通过目标检测重新思考Transformer（附源代码）](https://mp.weixin.qq.com/s/t-la4ZKHm8_3Krl2pD1xSw)       :star::star:
   - Abstract: YOLOS：通过目标检测重新思考Transformer
   - Paper: [You Only Look at One Sequence: Rethinking Transformer in Vision through Object Detection](https://arxiv.org/pdf/2106.00666.pdf)
   - Code: [https://github.com/hustvl/YOLOS](https://github.com/hustvl/YOLOS)
   - Tips: 我们发现仅在中等大小的ImageNet-1k数据集上预训练的YOLOS已经可以在COCO上实现具有竞争力的目标检测性能，例如直接从BERT-Base中采用的YOLOS-Base可以实现42.0 box AP。研究者还通过目标检测讨论了当前预训练方案和模型缩放策略对Transformer在视觉中的影响和局限性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwOmIoXkZicZBNXclhhSba0iaBswxzUDeuvGiccINYWDvuHSOJmoTYPLoCTfddP5jSUIfDxHYCBrAukKQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [You're AllSet! 以多重集函数角度重新检视超图GNN](https://mp.weixin.qq.com/s/KQcCGDa_80vxaf9-_BEl-A)       :star::star:
   - Abstract: 以多重集函数角度重新检视超图GNN
   - Paper: [You are AllSet: A Multiset Learning Framework for Hypergraph Neural Networks.](https://openreview.net/forum?id=hpBTIv2uy_E)
   - Code: [https://github.com/jianhao2016/AllSet](https://github.com/jianhao2016/AllSet)
   - Tips: 我们针对超图神经网络提出了一个泛用的框架AllSet，我们证明了大部分现有超图神经网络层的表达能力皆严格弱于AllSet，且证明了AllSet为MPNN的超图推广。我们利用近年深层多重集函数学习的结果，结合AllSet概念设计出可学习的AllSet层AllSSetTransformer。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ExPPKXgNVtdFDmO8CEI78BqZaXdvhfvCgSGw0vWC94xbTLPXGVeKu4EK4a21qIl9BlH2FIop55NVRplUEeUdQw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [ETH联合Meta和鲁汶大学 提出视频恢复算法VRT，在视频超分辨率、去模糊和去噪性能达到SOTA](https://mp.weixin.qq.com/s/qDmaVKn4TGu_e4f7kplMzQ)       :star::star:
   - Abstract: ETH联合Meta和鲁汶大学 提出视频恢复算法VRT，在视频超分辨率、去模糊和去噪性能达到SOTA
   - Paper: [VRT: A Video Restoration Transformer](https://arxiv.org/pdf/2201.12288.pdf)
   - Code: [https://github.com/JingyunLiang/VRT](https://github.com/JingyunLiang/VRT)
   - Tips: 该论文为将Swin Transformer应用于单图超分中的SwinIR的视频扩展版本，在视频复原的各领域中都有很大的提升，本文将从视频超分方向来解读VRT。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTuJsNTNxOUeaUcFnoKXmicJFRsqpw27124h8ZQrtLUWBJFhZ6wSSYzmLauG7DyhIWUib8Wq7jZNNmug/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [论文解释：SeFa ，在潜在空间中为 GAN 寻找语义向量](https://mp.weixin.qq.com/s/Pmjcl4U5gsF2zD2_3isAGA)       :star::star:
   - Abstract: SeFa ，在潜在空间中为 GAN 寻找语义向量
   - Paper: [Closed-Form Factorization of Latent Semantics in GANs](https://arxiv.org/abs/2007.06600)
   - Tips: 论文提出了一种名为 SeFa 的封闭形式和无监督方法，可以无需数据采样和模型训练并找出这些方向向量来改变输出图像中的不同属性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/6wQyVOrkRNLdmx0vlSj2CY9g1PjOZCc1sAxULUspcom3t6gS2eDhciasicDbtZFHP7R41Sxw6PiamEic9HgAV5l8ibg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [开源真实场景图像检测数据集汇总](https://mp.weixin.qq.com/s/pmFxKWR66cufNTYDMQV2rA)       :star::star:
   - Abstract: 开源真实场景图像检测数据集汇总
   - Tips: 本文汇总了九个图像检测相关的真实场景数据集，附有下载链接

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_png/gYUsOT36vfoWp5hpMic2ic3dCrzZuW8H0IMVYia1bl0xk9QK0waN2L9dG1YWeECpgoVgAv5JhQbNZF4caAZZspcsQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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