# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.7

------



## :paperclip:  今日要点

1. [CVPR 2022｜未标注视频也能训练目标检测？微软提出时空目标蒸馏框架STUD](https://mp.weixin.qq.com/s/JNfHqH09byZ5JSfQ8BuUhA)         :star::star:
   - Abstract: 微软提出时空目标蒸馏框架STUD
   - Paper: [Unknown-Aware Object Detection: Learning What You Don't Know from Videos in the Wild](https://arxiv.org/abs/2203.03800)
   - Code: [https://github.com/deeplearning-wisc/stud](https://github.com/deeplearning-wisc/stud)
   - Tips:  本文来自威斯康星大学麦迪逊分校和微软研究院，提出了一种时空未知目标蒸馏框架（Spatial-Temporal Unknown Distillation，STUD），其可以在大量未标注视频中提取未知目标，并对原有目标检测模型的决策边界进行规范化。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV10vZ2WZibxcTF80j2qX8URQoFXtHsEHeOoGLd2KHNnQNhTDG736J7Z7iblIQ43hxcnzUyIzb27UJkA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




2. [只需要十分之一数据，就能通关四大视觉任务，居然还开源了！](https://mp.weixin.qq.com/s/7R8DgOvqxlcjCYhgAqrd2g)       :star::star:
   - Abstract: OpenGVLab开源超高性能预训练模型，节省90%数据量！分类、目标检测、语义分割、深度估计，四大任务一网打尽！
   - Paper: [INTERN: A New Learning Paradigm Towards General Vision](arxiv.org/abs/2111.08687)
   - Code: [https://github.com/opengvlab](https://github.com/opengvlab)
   - Tips: 上海人工智能实验室联合商汤科技、香港中文大学、上海交通大学发布通用视觉技术体系“书生”INTERN，一套持续学习框架，用于系统化解决当下人工智能视觉领域中存在的任务通用、场景泛化和数据效率等一系列瓶颈问题。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/cNFA8C0uVPsNMYMVjuI9CJjjx6SibFTbnjibEqgN3dA0DWfUXE9zhRL45mZIHydozklgmXMeiaXetic7g8UAzSb2DA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



3. [EdgeFormer: 向视觉 Transformer 学习，构建一个比 MobileViT 更好更快的卷积网络](https://mp.weixin.qq.com/s/R53VtsmH7sAkPQ6UXvw4LQ)       :star::star:
   - Abstract: EdgeFormer: 向视觉 Transformer 学习，构建一个比 MobileViT 更好更快的卷积网络
   - Paper: [EdgeFormer: Improving Light-weight ConvNets by Learning from Vision Transformers](https://arxiv.org/abs/2203.03952)
   - Code: [https://github.com/hkzhang91/EdgeFormer](https://github.com/hkzhang91/EdgeFormer)
   - Tips: 本文提出的核心算子，即 global circular convolution (GCC)，是一个卷积操作，但是会引入位置嵌入，同时还具有全局的感受野。另一个改进点是使用提出的 GCC 和 SE 操作构建了类似于 Vision Transformer 的基础操作单元。借助于 SE 引入了样本相关的注意力机制。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTWg50IKKplAickSELFnEHvzJmgyjsLn4sNc9WppZiaRhMzzOiawwU0frhLxA9GyjACfypVCmOaFC1hGg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [LSTM在CV领域杀出一条血路！Sequencer：完美超越Swin与ConvNeXt等前沿算法](https://mp.weixin.qq.com/s/gv9TTnk84AOGwECUBqRjsg)       :star::star:
   - Abstract: Sequencer：完美超越Swin与ConvNeXt等前沿算法
   - Paper: [Sequencer: Deep LSTM for Image Classification](https://arxiv.org/abs/2205.01972)
   - Tips: 本文提出Sequencer，一个全新且具有竞争性的架构，可以替代ViT，为分类问题提供了一个全新的视角。作者还提出了一个二维的Sequencer模块，其中一个LSTM被分解成垂直和水平的LSTM，以提高性能。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfraib0TMLNymB7s3Fcpd7KSHxZDX3ib5Wa3mUnhAXhYb7omhNMiczfhjMPKlCoqsLqQBcMYrQDzKktXA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



5. [视觉Transformer的复仇！Meta AI提出DeiT III：ViT训练的全新baseline](https://mp.weixin.qq.com/s/hhSY5qv6mCDlBmNgu-VWUw)       :star::star::star::star:
   - Abstract: Meta AI提出DeiT III：ViT训练的全新baseline
   - Paper: [DeiT III: Revenge of the ViT](https://arxiv.org/abs/2204.07118)
   - Tips: 本文提出了训练视觉 Transformer（ViT）的三种数据增强方法：灰度、过度曝光、高斯模糊，以及一种简单的随机剪枝方法 (SRC)。实验结果表明，这些新方法在效果上大大优于 ViT 此前的全监督训练方法。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9JnGBvutVGOzsvCtYyHib8Zicfr3RBYjWFDMKczdE5X0X5Jx2DW3xlYj2gDogHWNDXVgFnicVic2YrMA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [引入特征空间，显著降低计算量：双边局部注意力ViT性能媲美全局注意力](https://mp.weixin.qq.com/s/487MBvfsy6s4chLCTD3MYQ)       :star::star:
   - Abstract: 引入特征空间，显著降低计算量：双边局部注意力ViT性能媲美全局注意力
   - Paper: [BOAT: Bilateral Local Attention Vision Transformer](https://arxiv.org/pdf/2201.13027v1.pdf)
   - Code: [https://github.com/mahaoyuHKU/pytorch-boat](https://github.com/mahaoyuHKU/pytorch-boat)
   - Tips: 作者提出了双边局部注意力 ViT （简称 BOAT)，把特征空间局部注意力模块加入到现有的基于窗口的局部注意力视觉 Transformer 模型中，作为图像空间局部注意力的补充，大大提升了针对远距离特征依赖的建模能力，在几个基准数据集上的大量实验表明结合了特征空间局部注意力的模型明显优于现有的 ConvNet 和 ViT 模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicLY3WEsU1F8x72suaCqRMdsV0Hrp9gbQBsd66fEIo6Kib4MD4rt7SI0DtfQ5XJsmI3Fsqb7Bh2odw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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