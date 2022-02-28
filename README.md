# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.2.28

------

## :paperclip:  今日要点

1. [ICLR 2022 Oral | 港大和商汤开源CycleMLP：用于检测与分割任务的MLP架构](https://mp.weixin.qq.com/s/82krdn9-3qgbL4B7Z8pOKg)         :star::star:
   - Abstract: 港大和商汤开源CycleMLP：用于检测与分割任务的MLP架构
   - Paper: [CycleMLP: A MLP-like Architecture for Dense Prediction](https://arxiv.org/abs/2107.10224)
   - Code: [https://github.com/ShoufaChen/CycleMLP](https://github.com/ShoufaChen/CycleMLP)
   - Tips:  本文针对MLP-Mixer等已有方案存在的分辨率相关、不便于向下游任务迁移的问题，提出了一种新颖的CycleFC操作，并由此构建了CycleMLP架构。本文非常漂亮的一个操作：通过对ChannelFC的采样点引入更高感受野升级为CycleFC，提升感受野的同时保持计算量不变。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrPMhYaaNts86Ccg08Q7t1W8kw6CT17ZB5ljsMcehX22I23ybFn8jpOibn6ib4Uf8GaSIc4SHJJrHBA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [(CVPR 2021)动态区域感知卷积](https://mp.weixin.qq.com/s/_8rzSn6419tjn6xSfs9k4A)       :star::star:
   - Abstract: 旷视科技发表在CVPR2021的工作动态区域感知卷积DRConv
   - Paper: [Dynamic Region-Aware Convolution](https://arxiv.org/pdf/2003.12243.pdf)
   - Tips: DRConv是一种处理复杂多变空间信息分布的有效而优雅的方法。它具有即插即用的特性，可以替代任何现有网络中的标准卷积。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/xT3a9RE17lTNbWibbMoQJFNOEENJGicle2dGrbeqQiaOUPaUfiaL8xae4hS9ppo1l2cqR60UPUHmZyynVVtxtrQ2Fg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [TPAMI 2022 | 国防科大等高校提出光场解耦机制，在超分辨与视差估计任务上取得优异性能](https://mp.weixin.qq.com/s/AeunZC4EBb5rdkYZkYtV9Q)       :star::star:
   - Abstract: 国防科大等高校提出光场解耦机制，在超分辨与视差估计任务上取得优异性能
   - Paper: [Disentangling Light Fields for Super-Resolution and Disparity Estimation](https://arxiv.org/pdf/2202.10603.pdf)
   - Code: [https://yingqianwang.github.io/DistgLF/](https://yingqianwang.github.io/DistgLF/)
   - Tips: 该文提出了一种通用的光场解耦机制，通过设计一系列的解耦卷积将高维光场解耦至多个低维子空间，实现了光场数据的高效处理。基于所提解耦机制，该文针对空间超分辨、角度超分辨以及视差估计任务分别设计了DistgSSR、DistgASR以及DistgDisp三个网络。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTu5ssMNv622MZFGHiahS5wlgt02HfAudlOZN4pZiac0UC97mQmOkJF6LnLE95eNKVZSdtcCtRZ5iaKlw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [注意力机制YYDS，AI编辑人脸终于告别P一处而毁全图](https://mp.weixin.qq.com/s/ViVJ4W1jJLaPmJ0n_KR1bQ)       :star::star:
   - Abstract: FEAT通过在GAN中引入注意力机制，成功解决了编辑人脸时会产生的一些“手抖”问题
   - Paper: [FEAT: Face Editing with Attention](https://arxiv.org/abs/2202.02713)
   - Tips: FEAT是在StyleGAN生成器的基础上，引入注意力机制,具体来说就是利用StyleGAN2的潜空间进行人脸编辑。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/Z8w2ExrFgDzC9w2FDqA9tfOm7XiaZ15ibSxXSyphhRjgT9C2V2aJOT5uPlr0r55IuQUWOEKacdDBeQklCJZstEMw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [GitHub 7.5k star量，各种视觉Transformer的PyTorch实现合集整理好了](https://mp.weixin.qq.com/s/SruewApFEo6ekH039idsNA)       :star::star:
   - Abstract: GitHub 7.5k star量，各种视觉Transformer的PyTorch实现合集整理好了
   - Code: [https://github.com/lucidrains/vit-pytorch](https://github.com/lucidrains/vit-pytorch)
   - Tips: 该项目名为「vit-pytorch」，它是一个 Vision Transformer 实现，展示了一种在 PyTorch 中仅使用单个 transformer 编码器来实现视觉分类 SOTA 结果的简单方法。除了 Vision Transformer 之外，该项目还提供了 Deep ViT、CaiT、Token-to-Token ViT、PiT 等其他 ViT 变体模型的 PyTorch 实现。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWicr7bCQicQzg3uKibL9p92bbJBFEwWibxNpbApKI7RK3icocHGicLgSqygUqVnFNFsIhk5PRUZtHd3vOMA/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


6. [Science：为什么越老，睡个好觉就越难](https://mp.weixin.qq.com/s/bJwqkHEcTCsksSDYGM3euQ)       :star::star:
   - Abstract: 为什么越老，睡个好觉就越难
   - Tips: 该研究通过小鼠实验，确定了调节睡眠和清醒的大脑回路如何随着时间的推移而退化的，为人类更好的治疗睡眠质量铺平了道路。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/f1HH88jZicVuM3kosx55dnvwcYvhCiaicBNgv0IPcKkeTq77NDHJOuJc721KacrdTL63Arfex3OhhZHWkBTXfwb6g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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