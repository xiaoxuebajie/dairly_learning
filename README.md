# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.25

------

## :paperclip:  今日要点

1. [CVPR 2022 | FAIR提出MaskFeat：自监督视觉预训练新方法！灵感之一来自16年前CVPR论文](https://mp.weixin.qq.com/s/dU14B0Hmary-q_2Qg278oA)         :star::star:
   - Abstract: FAIR提出MaskFeat：自监督视觉预训练新方法！
   - Paper: [Masked Feature Prediction for Self-Supervised Visual Pre-Training](https://arxiv.org/abs/2112.09133)
   - Tips: MaskFeat最核心的改变就是将MAE对图像像素（pixel）的直接预测，替换成对图像的方向梯度直方图（HOG）的预测。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb3hicLBCn12AYLhQIAZboH07MmVn00upqukxPe7zGrFGaBYJe4SmIH7uX8CMjsJGGWyRAAWhobTqsA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [GAN掉人脸识别系统？GAN模型「女扮男装」](https://mp.weixin.qq.com/s/SC7iEVfyI2G69OJc4IryEQ)       :star::star:
   - Abstract: GAN掉人脸识别系统？GAN模型「女扮男装」
   - Paper: [Face Verification Bypass](https://arxiv.org/pdf/2203.15068.pdf)
   - Tips: 用对抗生成网络GAN生成一个面部图像来模仿目标人脸，看看人脸识别系统能否正确验证。因为人脸的关键特征信息都保留了下来，所以论文的结果显示，生成的人脸图像仍然可以通过人脸验证。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb17O0YMJxNwVpWdMFA5d6YhyL86sGPFKoLwC4sJASB96xcjXlsH2EOmUiab1s0oiciciaQQGWqOXbSSQA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [CVPR 2022 | TCTrack: 用于空中跟踪的时序信息框架](https://mp.weixin.qq.com/s/4UgyAwg1MJJH9Aajl35q9w)       :star::star:
   - Abstract: TCTrack: 用于空中跟踪的时序信息框架
   - Paper: [TCTrack: Temporal Contexts for Aerial Tracking](https://arxiv.org/abs/2203.01885)
   - Code: [https://github.com/vision4robotics/TCTrack](https://github.com/vision4robotics/TCTrack)
   - Tips: TCTrack通过特征维度及相似度图维度连续整合时序信息。在特征提取过程中，作者通过使用改进的Online TAdaConv在特征维度高效引入时序信息；而在特征图维度，本文使用了更加高效的时序信息策略，通过不断积累的时序信息修正特征图。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTubGWibia4L1a3j2oAK5IXDrIfmLMhUvtPibXlSaTbicOIhC8zWpexPvPRhvYos8kTlmSpmktcxKaGLfA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [CVPR 2022 | 清华开源DAT：具有可变形注意力的视觉Transformer](https://mp.weixin.qq.com/s/GydO8rBctduBbVcUKcdIRg)       :star::star:
   - Abstract: 清华开源DAT：具有可变形注意力的视觉Transformer
   - Code: [Vision Transformer with Deformable Attention](https://arxiv.org/abs/2201.00520)
   - Code: [https://github.com/LeapLabTHU/DAT](https://github.com/LeapLabTHU/DAT)
   - Tips: 本文提出了一种新的可变形的自注意力模块，该模块以数据依赖的方式选择了自注意力中的key和value对的位置。这种灵活的方案使自注意力模块能够聚焦于相关区域并捕获更多信息。在此基础上，提出了一种可变形注意力Transformer(Deformable Attention Transformer)模型，该模型具有可变形注意力，适用于图像分类和密集预测任务。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgkqhY0ZfBzXZuRNCg3boLickg7ZRvQOoq0bWhobg10evDISHQOdwmWyCBytiaHW77pql15koT68ibJ3A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [新加坡国立大学&哈工大提出《Incremental-DETR》，基于自监督学习的增量 Few-Shot 目标检测，性能SOTA！](https://mp.weixin.qq.com/s/8EAxkoDxJXzggS12PJx9rg)       :star::star:
   - Abstract: 新加坡国立大学&哈工大提出《Incremental-DETR》，基于自监督学习的增量 Few-Shot 目标检测
   - Paper: [Incremental-DETR: Incremental Few-Shot Object Detection via Self-Supervised Learning](https://arxiv.org/abs/2205.04042)
   - Tips: 在本文中，作者提出了一种新的增量few-shot目标检测框架：针对更具挑战性和现实性的场景，在训练数据集中没有来自基类的样本，只有来自新类的少量样本。作者提出使用两阶段微调策略和自监督学习来保留基类的知识，并学习更好的泛化表示。然后，作者利用知识提取策略，使用新类中的少量样本，将知识从基础转移到新模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTvNwqE03o5I178lF4gxoOm3pp7em23Xtk8DJG0KUk3XocicyNvUGY8acbwfYCuQ7GlF64sjKhB5K6g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [大规模模型训练tricks集锦](https://mp.weixin.qq.com/s/p99u10YOODDmZQPN0lc03w)       :star::star:
   - Abstract: 大规模模型训练tricks集锦
   - Tips: 大规模模型训练其实就是在和计算、存储和通信玩的过程，所以作者列一下跟这些相关的文章。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/5fknb41ib9qHGHDgutwHQTnMn7RfH4eANVKkSoMy2leXmRI2Y7NPJqtkIsHYqY9qQibS3WxR17ibIGu3S5icvXCRSA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    5. <a href="notes/202205/0511.md" target="_blank">公众号内容拓展学习笔记（2022.5.11）</a>
    6. <a href="notes/202205/0517.md" target="_blank">公众号内容拓展学习笔记（2022.5.17）</a>
    7. <a href="notes/202205/0518.md" target="_blank">公众号内容拓展学习笔记（2022.5.18）</a>
    8. <a href="notes/202205/0519.md" target="_blank">公众号内容拓展学习笔记（2022.5.19）</a>
    9. <a href="notes/202205/0520.md" target="_blank">公众号内容拓展学习笔记（2022.5.20）</a>
    10. <a href="notes/202205/0521.md" target="_blank">公众号内容拓展学习笔记（2022.5.21）</a>
    11. <a href="notes/202205/0522.md" target="_blank">公众号内容拓展学习笔记（2022.5.22）</a>
    12. <a href="notes/202205/0523.md" target="_blank">公众号内容拓展学习笔记（2022.5.23）</a>
    13. <a href="notes/202205/0524.md" target="_blank">公众号内容拓展学习笔记（2022.5.24）</a>
    14. <a href="notes/202205/0525.md" target="_blank">公众号内容拓展学习笔记（2022.5.25）</a>
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