# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.10

------



## :paperclip:  今日要点

1. [CVPR2021：单目实时全身动作捕捉（清华大学）](https://mp.weixin.qq.com/s/comg8g4kCKZvCZN1uEfiGA)         :star::star:
   - Abstract: 单目实时全身动作捕捉
   - Paper: [Monocular Real-time Full Body Capture with Inter-part Correlations](https://arxiv.org/abs/2012.06087)
   - Tips:  整个网络框架主要被划分为四个独立的模块：DetNet，是根据人体图像估算人体和手部关键点的位置，其中嵌有新的交互特征，注意力机制和二级人体关键点检测结构。BodyIKNet和HandIKNet，是根据人体和手部的关键点坐标估计形状参数和关节角度；FaceNet，是用于从人脸图像裁剪中回归获取人脸的参数

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Q0FNTB1XHicx8eXJhlThstZAuzPQuugAFUgrS4hhjXshlibAicgkN2sEV5hxFzkJTpNM1LyvhhVlOGj2QXXz3VryQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [近期激光雷达点云的3D目标检测方法](https://mp.weixin.qq.com/s/Gk39tazsqEcqJFbHPSHEcA)       :star::star:
   - Abstract: 近期激光雷达做目标检测的论文
   - Tips: 包括自动标注、SIENet、室内数据、HVPP、SE-SSD、BEVDetNet六篇论文

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/Q0FNTB1XHicx8eXJhlThstZAuzPQuugAFJgumWibJsyTicNCNibuUUrDicOww5lfDLhgXSRu5EgGewNfg9TCWHE8VNw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [GODIVA：只需一步，文字到视频秒级生成，微软亚洲研究院最新成果](https://mp.weixin.qq.com/s/LCKL09tspA4WoP0q4rvFqg)       :star::star:
   - Abstract: 开放领域视频生成预训练模型GODIVA
   - Paper: [GODIVA: Generating Open-DomaIn Videos from nAtural Descriptions](https://arxiv.org/abs/2104.14806)
   - Tips: 实现了文字到视频的秒级生成，在视频日渐成为主流传播介质的今天，未来每个人都有机会成为视频制作达人

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/HkPvwCuFwNNVH4dpbZgT5l6xqzJtxlZLFAu3iaIJhF10tThNRsicsF5hufibPgNqtsBGZJWB2S2zHWbJkqZALxKUA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [EACL 2021 | 基于依存句法增强的方面情感分析](https://mp.weixin.qq.com/s/rTPxm_V7U99j0pHG7jqvyA)       :star::star:
   - Abstract: 基于依存句法增强的方面情感分析
   - Paper: [Enhancing Aspect-level Sentiment Analysis with Word Dependencies](https://www.aclweb.org/anthology/2021.eacl-main.326/)
   - Code: [https://github.com/cuhksz-nlp/ASA-WD](https://github.com/cuhksz-nlp/ASA-WD)
   - Tips: 论文采用记忆网络（Memory network）的形式将句子的依存句法 （dependency syntax）信息加入到方面情感分析（aspect-level sentiment analysis）中，使得模型能够学习依存句法中有用的信息，达到更好的方面情感分析效果

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/reteKm2hCvia3KmKBBcdhK4FrNeMib4pW18yKB3jwKfNbACLHF9icwfZCF64ibCNic6Ric3yibCN3gXGGqAZRAA33YpDQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [MobileBERT —资源受限设备上的任务无关BERT](https://mp.weixin.qq.com/s/HSPW38MgUZlwBMpWnP9iAg)       :star::star:
   - Abstract: 提出 MobileBert 来压缩和加速 Bert 模型
   - Paper: [MobileBERT: a Compact Task-Agnostic BERT for Resource-Limited Devices](https://arxiv.org/abs/2004.02984)
   - Code: [https://github.com/google-research/google-research/tree/master/mobilebert](https://github.com/google-research/google-research/tree/master/mobilebert)
   - Tips: MobileBERT 在转换模块中引入了bottleneck，这使我们可以更轻松地将知识从大teacher模型传授给小student模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1niaDLWmibswfAQs6UIjOpBwRAdFAHArMqQAFbkVlan3TibSfBqfMUHAz4ibpY6LdZ5oiaamQdv0LLF3mQUiaSryT2gg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [CVPR 2021 | RfD-Net: 从点云中重建三维物体实例](https://mp.weixin.qq.com/s/U1H5j3EZMYqn2iB_5Rk2IQ)       :star::star:
   - Abstract: 从三维场景点云中重建高精度物体网格的学习框架RfD-Net
   - Paper: [RfD-Net: Point Scene Understanding by Semantic Instance Reconstruction](https://arxiv.org/abs/2011.14744)
   - Code: [https://github.com/yinyunie/RfDNet](https://github.com/yinyunie/RfDNet)
   - Tips:  主要思路是通过目标检测来进行三维重建，该网络由三个模块组成：三维检测器模块(3D detector)，空间变换器模块(spatial transformer)和形状生成器模块(shape generator)

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV27QpSqqPgKbFxY3iaqtywAGgjQFr4DRUvh2CDp9ltdoW1j5MUKRicoS6icibmiazG5eFFeozuVzdxMKyA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    9. <a href="notes/202105/0509.md" target="_blank">公众号内容拓展学习笔记（2021.5.9）</a>
    10. <a href="notes/202105/05010.md" target="_blank">公众号内容拓展学习笔记（2021.5.10）</a>
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