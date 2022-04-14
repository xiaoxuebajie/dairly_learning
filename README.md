# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.4.14

------

## :paperclip:  今日要点

1. [CVPR 2022｜Self-Attention和CNN的优雅集成！清华大学等提出ACmix，性能速度全面提升！](https://mp.weixin.qq.com/s/rJHR-C4Hos6G9_tL3OCS6w)         :star::star:
   - Abstract: 清华大学等提出ACmix，Self-Attention和CNN的优雅集成，性能速度全面提升
   - Paper: [On the Integration of Self-Attention and Convolution](https://arxiv.org/pdf/2111.14556.pdf)
   - Code: [https://github.com/Panxuran/ACmix](https://github.com/Panxuran/ACmix)
   - Tips:  清华大学等提出了一个混合模型ACmix：它既兼顾Self-Attention和Convolution的优点，同时与Convolution或Self-Attention对应的模型相比，具有更小的计算开销。实验表明，本文方法在图像识别和下游任务上取得了持续改进的结果

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfq41B6oVLgoJ5JFgLPjFyVTm3q803luhObhj9CQ09XR2PYmXGfymBQTkrf4Lj4c9MDaw2ibr3ibh0bQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [CVPR 2022 Oral | MetaFormer：证明Transformer的威力源自其整体架构！颜水成团队工作！](https://mp.weixin.qq.com/s/2WIhkOGKRv4TOlBnaKmEsw)       :star::star:
   - Abstract: MetaFormer：证明Transformer的威力源自其整体架构
   - Paper: [MetaFormer is Actually What You Need for Vision](https://arxiv.org/abs/2111.11418)
   - Code: [https://github.com/sail-sg/poolformer](https://github.com/sail-sg/poolformer)
   - Tips: 作者认为`MetaFormer`是为最近的Transformer和类似MLP的视觉任务模型获得优越结果的关键。这项工作需要更多的未来研究，致力于改进`MetaFormer`，而不是专注于`token mixer module`。此外，作者提出的PoolFormer可以作为未来`MetaFormer`设计的Baseline。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgnITQrfYicacJtGytOgAU3uG510bbx5jTH8ianZCHkmXZEPbFCpvFpgjiaibXGOpAvINRZrokxTv6GDZA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [视频生成无需GAN、VAE，谷歌用扩散模型联合训练视频、图像，实现新SOTA](https://mp.weixin.qq.com/s/VlQVhBJCzn9yei8ZtWPrWA)       :star::star:
   - Abstract: 谷歌用扩散模型联合训练视频、图像，实现新SOTA
   - Paper: [Video Diffusion Models](https://arxiv.org/pdf/2204.03458.pdf)
   - Code: [https://video-diffusion.github.io/](https://video-diffusion.github.io/)
   - Tips: : 首先谷歌展示了使用扩散模型生成视频的首个结果，包括无条件和有条件设置。其次该研究表明，可以通过高斯扩散模型的标准公式来生成高质量的视频，除了直接的架构更改以适应深度学习加速器的内存限制外，几乎不需要其他修改。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWibJGtFAALicxXwtgjHz4EhbjicVJw0fdbZCGcAI3LOlWEKlPtmbLFs5D120PzzJU4aGfIHqfdpZ9yrA/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


4. [CVPR | 浙大小姐姐提出了秃头生成器，完美保留五官，让程序员简历大加分？](https://mp.weixin.qq.com/s/zurx_rIP2ec5hYPGr4s1PA)       :star::star:
   - Abstract: 浙大小姐姐提出了秃头生成器，完美保留五官
   - Paper: [HairMapper: Removing Hair from Portraits Using GANs](http://www.cad.zju.edu.cn/home/jin/cvpr2022/HairMapper.pdf)
   - Code: [https://github.com/oneThousand1000/non-hair-FFHQ](https://github.com/oneThousand1000/non-hair-FFHQ)
   - Tips: HairMapper的原理一共分为三步，生成秃头→保留五官→合并头像。首先，作者们利用StyleGAN，做出一个与原头型相近的秃头效果；接下来，就是利用InterFaceGAN，抠出一个头发以外的脸型和五官形象，同时也保留四周的风景；最后，将前两步生成的效果合成，就做出了一个完美的“光头”。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/YicUhk5aAGtDD4P7eGZsOShpoPT09e8H8ribg2Sc9gYtkTm3S2zNLiba5sMUhSry2LtpQib7mn6Bib9Iv6XTVGMdudw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [CVPR 2022 | 南大提出：Structured Sparse R-CNN：单阶段端到端场景图生成器](https://mp.weixin.qq.com/s/fTT8N7UcrDhyy6CmZ-Fbhw)       :star::star:
   - Abstract: 南大提出：Structured Sparse R-CNN：单阶段端到端场景图生成器
   - Paper: [Structured Sparse R-CNN for Direct Scene Graph Generation](https://arxiv.org/abs/2106.10815)
   - Code: [https://github.com/MCG-NJU/Structured-Sparse-RCNN](https://github.com/MCG-NJU/Structured-Sparse-RCNN)
   - Tips: 本工作将端到端稀疏目标检测器引入场景图生成领域，并提出了相应的关系建模组件和训练策略。该模型在 Visual Genome, Open Image V4/V6 数据集上取得了 SOTA 效果。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oWyibL6R9xZ20yAfZFAZIMJxzib8tn1b5UPpOicsPo8kNQzlzib3k6VGy1SW45nUFpoc79cPyovyjd63Q/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [CVPR 2022｜打破传统的跟踪范式！南大开源MixFormer：端到端目标检测新模型](https://mp.weixin.qq.com/s/VI4SOEsD7VxEaa-PhLgd4g)       :star::star:
   - Abstract: 打破传统的跟踪范式！南大开源MixFormer：端到端目标检测新模型
   - Paper: [MixFormer: End-to-End Tracking with Iterative Mixed Attention](https://arxiv.org/abs/2203.11082)
   - Code: [https://github.com/MCG-NJU/MixFormer](https://github.com/MCG-NJU/MixFormer)
   - Tips: 本文介绍了一篇单目标跟踪(VOT)领域的新工作-基于 transformer 的简洁的端到端模型 MixFormer，该工作已经被CVPR 2022收录。该工作打破了传统的跟踪范式，通过模板与测试样本混合的backbone加上一个简单的回归头直接出跟踪结果，并且不使用框的后处理、多尺度特征融合策略等。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfo2EXh31yIPtb0f44V0uEcUsq3BQV6UXD3cNGh9iaibY0icJB0rvK9vDxeBT2BBAy2zaGnf5OnBQmtyg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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