# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.9

------



## :paperclip:  今日要点

1. [CVPR 2022 | 北大、腾讯提出文字logo生成模型，脑洞大开](https://mp.weixin.qq.com/s/UDkE-tHvahrAVGZGn7_6vQ)         :star::star:
   - Abstract: 北大、腾讯提出文字logo生成模型
   - Paper: [Aesthetic Text Logo Synthesis via Content-aware Layout Inferring](https://arxiv.org/abs/2204.02701)
   - Code: [https://github.com/yizhiwang96/TextLogoLayout](https://github.com/yizhiwang96/TextLogoLayout)
   - Tips:  本模型基于 Conditional GAN 来生成文字 logo，创新性地使用双判别器结构（序列判别器和图像判别器），对字形的轨迹序列和整体 logo 图像分别做判别；同时借助可微分拼接(Differentiable Composition)，构建位置坐标到 logo 图像的可微分渲染过程。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWibqentvzSlBUfic9MTjYhj8jfgaicBOqeFdYxVSibrbgJ9gZxJQfvpS57UibZ7bzGYViaLt7ojZah9SSNg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [CVPR2022 Oral：GAN监督的密集视觉对齐，代码开源](https://mp.weixin.qq.com/s/YI3CRFeSQwvnfYWFY2OQMg)       :star::star:
   - Abstract: GAN监督的密集视觉对齐，代码开源
   - Paper: [GAN-Supervised Dense Visual Alignment](https://arxiv.org/abs/2112.05143)
   - Code: [https://www.github.com/wpeebles/gangealing](https://www.github.com/wpeebles/gangealing)
   - Tips: 在该论文中作者提出了一种用于端到端联合学习的GAN生成数据的框架。受到经典方法的启发，论文中作者联合训练一个空间变换器，将随机样本从基于未对齐数据训练的GAN映射到共同的、联合学习的目标模式。

<video id="video" controls=""src="http://mpvideo.qpic.cn/0bc3iiaa4aaa4qao57dpnnrfaqwdbzbaadqa.f10003.mp4?dis_k=85b8fb229280fbf356d366dec7e53593&dis_t=1652058067&vid=wxv_2380802778538688513&format_id=10003&support_redirect=0&mmversion=false" preload="none">


3. [ACL'22 | 陈丹琦提出CoFi模型剪枝，加速10倍，精度几乎无损](https://mp.weixin.qq.com/s/0VO036qHI8JYfYu_r-3Tgw)       :star::star:
   - Abstract: 陈丹琦提出CoFi模型剪枝，加速10倍，精度几乎无损
   - Paper: [Structured Pruning Learns Compact and Accurate Models](https://arxiv.org/pdf/2204.00408.pdf)
   - Code: [https://github.com/princeton-nlp/CoFiPruning](https://github.com/princeton-nlp/CoFiPruning)
   - Tips: 作者提出的结构化剪枝方法 CoFi 在几乎没有太多精度损失的情况下，达到了 10 倍以上的加速比，同时，和常规的蒸馏做法相比，避免了因使用大量无标签数据预训练模型而带来的训练成本过高的问题，按作者的话来说，该方法可以是蒸馏的一个有效替代品。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qEqBFibgRXqh8zdwZ3TIbOqUWO2GJpFnStnqzicibsUkfoUhvhL2Evl3RvAsxBa97Hk5nBTZj6gvRTmA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




4. [MAGIC: 一个即插即用、无需训练的图像-文本生成框架](https://mp.weixin.qq.com/s/bCeALWVmPZnNvfMN7xOrLQ)       :star::star:
   - Abstract: MAGIC: 一个即插即用、无需训练的图像-文本生成框架
   - Paper: [LanguageModels Can See: Plugging Visual Controls in Text Generation](https://arxiv.org/abs/2205.02655)
   - Code: [https://github.com/yxuansu/MAGIC](https://github.com/yxuansu/MAGIC)
   - Tips: 本文提出了一个全新的MAGIC框架。该框架可以使用图片模态的信息指导预训练语言模型完成一系列跨模态生成任务与其他方法不同的是，MAGIC框架无需多模态的训练数据，只需利用现成的语言模型和图文匹配模型就能够以zero-shot的方式高质量地完成多模态生成任务。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/nJZZib3qIQW7M5v7ChRYa7Gol6z2VC4WficogWcOwms9VA7l0icqZkqbjn9gKsKAxbohU242ribtCDvjCxrW1pfic6g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




5. [多模态理解与生成，西南交大&MSRA提出统一的"视频和语言预训练"模型：UniVL！](https://mp.weixin.qq.com/s/P3WiKQmboTrgad2JzIAvgA)       :star::star::star::star:
   - Abstract: 西南交大&MSRA提出统一的"视频和语言预训练"模型：UniVL
   - Paper: [UniVL: A Uniﬁed Video and Language Pre-Training Model for Multimodal Understanding and Generation](https://arxiv.org/abs/2002.06353)
   - Code: [https://github.com/microsoft/UniVL](https://github.com/microsoft/UniVL)
   - Tips: 本文提出了一种基于自监督学习的大规模视频语言表示方法UniVL。UniVL设计有四个模块和五个目标，用于视频语言理解和生成任务。它是一个灵活的模型，适用于大多数多模态下游任务，同时考虑效率和有效性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTtUnlibcGGfdY7DlpgcicSf5iafNHcZJCCm1DuQDTLXCxtQvPpXm09CzxyroZCup5Uh4xZ2sM8RWDwsA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




6. [小样本学习只是一场学术界自嗨吗？](https://mp.weixin.qq.com/s/GyRxJ47HDpz2JZatWxPnOg)       :star::star:
   - Abstract: 小样本学习只是一场学术界自嗨吗？
   - Tips: 这两年看见很多人，都在批评few-shot learning，觉得是学术界在自high，思考良久，感觉有必要给这个领域正个名～（注意，本文仅关注few-shot image classification）

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqMsywC0jhRXchnH1jh4dIsdgbCRuYGuhPkQgcopJ4mS9Veerq4pD5MicXHBDntrAkvMtuv7ebGicOQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    12. <a href="notes/202203/0312.md" target="_blank">公众号内容拓展学习笔记（2022.3.12）</a>
    13. <a href="notes/202203/0313.md" target="_blank">公众号内容拓展学习笔记（2022.3.13）</a>
    14. <a href="notes/202203/0314.md" target="_blank">公众号内容拓展学习笔记（2022.3.14）</a>
    15. <a href="notes/202203/0316.md" target="_blank">公众号内容拓展学习笔记（2022.3.16）</a>
    16. <a href="notes/202203/0317.md" target="_blank">公众号内容拓展学习笔记（2022.3.17）</a>
    17. <a href="notes/202203/0330.md" target="_blank">公众号内容拓展学习笔记（2022.3.30）</a>
</details>
<details><summary>4月</summary>
    1. <a href="notes/202204/0402.md" target="_blank">公众号内容拓展学习笔记（2022.4.2）</a>
    2. <a href="notes/202204/0414.md" target="_blank">公众号内容拓展学习笔记（2022.4.14）</a>
</details>
<details><summary>5月</summary>
    1. <a href="notes/202205/0505.md" target="_blank">公众号内容拓展学习笔记（2022.5.5）</a>
    2. <a href="notes/202205/0507.md" target="_blank">公众号内容拓展学习笔记（2022.5.7）</a>
    3. <a href="notes/202205/0509.md" target="_blank">公众号内容拓展学习笔记（2022.5.9）</a>
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