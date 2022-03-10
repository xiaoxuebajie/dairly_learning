# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.10

------

## :paperclip:  今日要点

1. [U2PL: 使用不可靠伪标签的半监督语义分割 (CVPR'22)](https://mp.weixin.qq.com/s/ruOIXZ8lMImKnzgcE0d6vQ)         :star::star:
   - Abstract: U2PL: 使用不可靠伪标签的半监督语义分割 
   - Paper: [Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels](https://arxiv.org/pdf/2203.03884.pdf)
   - Code: [https://github.com/Haochen-Wang409/U2PL](https://github.com/Haochen-Wang409/U2PL)
   - Tips:  半监督任务的关键在于充分利用无标签数据，本文基于「 Every Pixel Matters」的理念，有效利用了包括不可靠样本在内的全部无标签数据，大幅提升算法精度。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfpqGQBBp2Dibm5CuMZC4Z1JKA9JNsBUaoj9SySVQ0kibic3jlXM4paYiaM0oDaqvdPmYPewp0FgdzLHzg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [ICLR 2022 Oral | PiCO：基于对比消歧的偏标签学习](https://mp.weixin.qq.com/s/H8igvPdhIPZv82CBAhNI2Q)       :star::star:
   - Abstract: PiCO：基于对比消歧的偏标签学习
   - Paper: [PiCO: Contrastive Label Disambiguation for Partial Label Learning](https://arxiv.org/abs/2201.08984)
   - Tips:  本文提出一个协同的框架解决 PLL 中的两个关键研究挑战——表征学习和标签消歧。具体来说PiCO 由一个对比学习模块和一个新颖的基于类原型的标签消歧算法组成。PiCO 为来自同一类的样本生成紧密对齐的表示，同时促进标签消歧。从理论上讲，我们表明这两个组件能够互相促进，并且可以从期望最大化 (EM) 算法的角度得到严格证明

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV1tNHdJpayNO1SaOf4Pia790v4Q9N5iaVVAryZQ6q1QULO59FibiakmAeILfgcVNY0YicaUDuOPl8HpaDw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



3. [骗人还是文字强！MIT最新研究：DeepFake换脸还不如编辑动动笔](https://mp.weixin.qq.com/s/0iL4fwL43xHgZzsvkeD73g)       :star::star:
   - Abstract: MIT最新研究：DeepFake换脸还不如编辑动动笔
   - Paper: [Human detection of political deepfakes across transcripts, audio, and video](https://arxiv.org/pdf/2202.12883.pdf)
   - Tips: 伪造的政治演讲视频比伪造的文字记录更容易识别，这一发现强调了重新让人们忆起常被遗忘的『眼见为实』格言的必要性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/UicQ7HgWiaUb0umeKaXU2mIcLD96efib8FEajQRXu1VEDJWEzoialgyu2mQfLQJLz7YIicJK5etzXVTBOzBDTibNGv0A/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>



4. [Detectors for the 2020s 目标检测算法最新进展](https://mp.weixin.qq.com/s/NJhE3Psvp-DHeZverfJxng)       :star::star:
   - Abstract: 目标检测算法最新进展
   - Tips: 近几年目标检测的落地越发成熟，新的sota网络同样层出不穷，不断刷新着coco的记录。本文盘点截止2019-2021年，在coco test-dev上霸榜，且知名度较广的目标检测网络。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SdQCib1UzF3uViau2OJXatzYic5e17ibhibnxujWib66ZddibLD6Fg51lV3wial9EIhfwHedoX7L5z0vFsUq7S6lvGO9Pw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [目标检测最少训练数据量及类别不平衡的实战研究](https://mp.weixin.qq.com/s/iZYmst7GuWPpEr4s-rTsqg)       :star::star:
   - Abstract: 目标检测最少训练数据量及类别不平衡的实战研究
   - Tips: 本文采用Yolov5进行测试，从实验中得出训练时所需图像数据的最少数据量，数据不平衡问题的解决方式，以及模型更新的最优方法。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/VvkhdVVVIDhicEs3IeDbRDWKicfuRRbwgjtFnMXvoiaGItMrsLyMsibw2Wm00ZpuL973ZS2Vvl3gzQulL9jMianAcdA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [你一定从未看过如此通俗易懂的YOLO系列（从V1到V5）模型解读！](https://mp.weixin.qq.com/s/EAONLOEIuexJBqbUvvb07g)       :star::star:
   - Abstract: 通俗易懂的YOLO系列（从V1到V5）模型解读！
   - Tips: 本文采用生动有趣的语言和案例，对YOLO系列模型的原理、设计及改进思路进行了详细解读，干货满满，不仅适合新手入门阅读，也能帮助大家进一步加深理解。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfp0Y6EQc74RUsLKenPy1Bg14z5yHQVKgnnOg3xfFQTicfBUtLhQtsCsiaqBGfpyAcSPxAIUhBIGZHcw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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