# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.10

------



## :paperclip:  今日要点

1. [CVPR 2022 | 涨点显著！AMD提出：动态Sparse R-CNN](https://mp.weixin.qq.com/s/YBNbWdiW6tQGPCoJF8LMCw)         :star::star:
   - Abstract: 涨点显著！AMD提出：动态Sparse R-CNN
   - Paper: [Dynamic Sparse R-CNN](https://arxiv.org/abs/2205.02101)
   - Tips:  `Sparse R-CNN`是最近的一种强目标检测`Baseline`，通过对稀疏的、可学习的`proposal boxes`和`proposal features`进行集合预测。在这项工作中提出了2个动态设计来改进`Sparse R-CNN`。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgl3MMndmrCICD9kwr9oggwAKMIMMia8HsNJMNeibu5icSeppfuPbJnSkKK2qX46UYegZOcwY60j0fBZg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




2. [CVPR2022｜小样本行为识别最新进展STRM框架，时空关系建模仍是重中之重](https://mp.weixin.qq.com/s/-HpMEGG4kMWIBfM2SrMk8A)       :star::star:
   - Abstract: 小样本行为识别最新进展STRM框架，时空关系建模仍是重中之重
   - Paper: [Spatio-temporal Relation Modeling for Few-shot Action Recognition](https://arxiv.org/abs/2112.05132)
   - Code: [https://github.com/Anirudh257/strm](https://github.com/Anirudh257/strm)
   - Tips: 本文的出发点是解决小样本行为识别领域中的时空关系建模问题，提出了一种新颖的时空信息增强模块，分别从局部和全局的角度对视频中的对象特征和时空上下文进行捕捉。此外，作者还设计了一种查询类相似性分类器来增强网络对特定行为类的特征辨别能力。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV34gGB02tibuoaMJnkf8icp4CyL04nSA3odWicVNkN9cfpvEibzmVrB2pXsH25kkzBzS9vibdnfxTraZBQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



3. [CVPR 2022 | 从自注意力中学习语义Affinity用于端到端弱监督语义分割](https://mp.weixin.qq.com/s/0WoMvQbb0KRjBoLAFjcJzA)       :star::star:
   - Abstract: 从自注意力中学习语义Affinity用于端到端弱监督语义分割
   - Paper: [Structured Pruning Learns Compact and Accurate Models](https://arxiv.org/pdf/2204.00408.pdf)
   - Code: [https://github.com/princeton-nlp/CoFiPruning](https://github.com/princeton-nlp/CoFiPruning)
   - Tips: 本文提出了一个Affinity from Attention（AFA）模块，从Transformer的注意力矩阵中学习高质量的语义Affinity信息，用于对初始伪标签进行改善。为了进一步补充伪标签的局部细节信息，同时保证端到端训练的效率，本文基于像素自适应卷积设计了一个高效的处理模块。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Mcdq8uia1WiacLyFJwpup4N51FibnoHicqiaefKOKLPF27JzKu20hLhmPxuWVpANUGg3Fl2R4EcIqd2z45pElqHU5CA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [GitHub 20000+ Star，这个超轻量OCR系统效果再提升5% - 11%！](https://mp.weixin.qq.com/s/uoh_PMVEf_NYU8Z-9NdY7g)       :star::star:
   - Abstract: 这个超轻量OCR系统效果再提升5% - 11%
   - Code: [https://github.com/PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
   - Tips: 本次PaddleOCR最新发版，带来四大重磅升级，发布超轻量OCR系统PP-OCRv3；发布半自动标注工具PPOCRLabelv2；发布OCR产业落地工具集；发布业界首个交互式OCR开源电子书《动手学OCR》。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/ByEtV06HvDia9P9pCfviaUsic9AsDXrlw5ylu1tAhExcThppkqRvibhGibyXgrFQTvPFRxrdvAm8ibOjlTBLcmPaCyicw/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>



5. [使用PyTorch复现ConvNext：从Resnet到ConvNext的完整步骤详解](https://mp.weixin.qq.com/s/PTBAXkMAOGHIs_pQt3gfJg)       :star::star:
   - Abstract: 使用PyTorch复现ConvNext：从Resnet到ConvNext的完整步骤详解
   - Tips: ConvNext论文提出了一种新的基于卷积的架构，不仅超越了基于 Transformer 的模型（如 Swin），而且可以随着数据量的增加而扩展！本文通过Pytorch对其进行复现。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/6wQyVOrkRNJUe2VOzQQOcrgWKtPqdI5pOjZIhMGiaSkpYz48qQN3rpU2ZNeTsDZHommMuyiaXHEr3Ek7kGfw2a0w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [视频目标跟踪从0到1，概念与方法](https://mp.weixin.qq.com/s/1N3B1tt-bMivln7AMOWeiA)       :star::star:
   - Abstract: 视频目标跟踪从0到1，概念与方法
   - Tips: 从目标跟踪的应用场景，底层模型，组件，类型和具体算法几个方面对目标跟踪做了全方面的介绍，非常好的入门文章。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KYSDTmOVZvriag9o7IEOJvg6XlutFXY00espFtjXypeObSXlibFFMIW4azAtA35FZnuJN02h7KynpWiaX1EA7LTIg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    4. <a href="notes/202205/0510.md" target="_blank">公众号内容拓展学习笔记（2022.5.10）</a>
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