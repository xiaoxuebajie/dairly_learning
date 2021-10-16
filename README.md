# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.10.16

------

## :paperclip:  今日要点

1. [ICCV 2021 | 字节跳动利用单幅图片做三维重建！将NeRF、MPI结合，提出MINE新工作](https://mp.weixin.qq.com/s/kuAjTMYi8c88InAhjcRJ7g)         :star::star:
   - Abstract: 一种新的三维空间表达方式 MINE利用单幅图片做三维重建
   - Paper: [MINE: Towards Continuous Depth MPI with NeRF for Novel View Synthesis](https://arxiv.org/pdf/2103.14910.pdf)
   - Code: [https://github.com/vincentfung13/MINE](https://github.com/vincentfung13/MINE)
   - Tips:  相比于 MPI 和 NeRF，MINE具有很大的优势。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8GpMRJicD0IA8JZh07MZ3zNhaKFibDjcrXiat2G0bBLTlMkO8S9lGDnfoOp5G6CicNr6j6iby6ribXuibiag/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [浙大三维视觉团队提出Animatable NeRF，从RGB视频中重建可驱动人体模型 (ICCV'21)](https://mp.weixin.qq.com/s/BlDaqHdSuHmmGVKHOc-nRA)       :star::star:
   - Abstract: 浙大三维视觉团队提出Animatable NeRF，从RGB视频中重建可驱动人体模型
   - Paper: [Animatable Neural Radiance Fields for Modeling Dynamic Human Bodies](https://arxiv.org/abs/2105.02872)
   - Code: [https://github.com/zju3dv/animatable_nerf](https://github.com/zju3dv/animatable_nerf)
   - Tips: 当人体模型训练完成后，可以用新的人体骨架进行驱动

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/BJbRvwibeSTtK8Ze1qbeZbfwFDFw9H4w5beia4125t1QEGoBUGoeIBfHibNFcWtM4c1xJF9ibwP3fRP421UKEtckGw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [CVPR2021 用更好的目标检测器提取视觉特征！微软提出VinVL，基于更好的视觉特征，达到更强的多模态性能](https://mp.weixin.qq.com/s/Arf-ajkmGdze4RWY4Od8pw)       :star::star:
   - Abstract: 微软提出VinVL，基于更好的视觉特征，达到更强的多模态性能
   - Paper: [VinVL: Revisiting Visual Representations in Vision-Language Models](https://arxiv.org/abs/2101.00529)
   - Code: [https://github.com/pzzhang/VinVL](https://github.com/pzzhang/VinVL)
   - Tips: 作者将新的目标检测模型生成的视觉特征输入到基于Transformer的VL融合模型OSCAR中

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTs45gWnNPeic521nq5MFFcZxeNVu2WmvZic2Sn21lZicNRymd9TM6fAQy8iaf9sVaobAP5asyFTBtCkibA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [全新instruction调优，零样本性能超越小样本，谷歌1370亿参数新模型比GPT-3更强](https://mp.weixin.qq.com/s/Tf7RXgSEbj_9aHFlaBI1yw)       :star::star:
   - Abstract: 全新instruction调优，零样本性能超越小样本，谷歌1370亿参数新模型比GPT-3更强
   - Paper: [FINETUNED LANGUAGE MODELS ARE ZERO-SHOT LEARNERS](https://arxiv.org/pdf/2109.01652.pdf)
   - Code: [https://github.com/google-research/flan](https://github.com/google-research/flan)
   - Tips: FLAN采用指令调整技术后的模型在自然语言推理、阅读理解和开放域问答等未见过的任务上的零样本性能超越了 GPT-3 的小样本性能。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicjIXvroicVtmBzWtRjhulibkFF9X0Qmm11wVLQGEn6y3DLJwTbibrYzSPic9Er7ib69uFMg7gOpfxdbFA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [“推荐算法”最新工作，一次让你看个够！](https://mp.weixin.qq.com/s/9ZGR04FfMna4heFlpgOGbQ)       :star::star:
   - Abstract: 推荐系统最新工作
   - Tips:  8篇有关推荐系统最新工作的总结。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV3eWTEvmBTu2tmCWTIh3PGVo2w0ibwGtFIPKs3LCibGvq1zSoU3LicTMLPaMguywgkXAbcLiaYBuZiaLuA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [视频理解综述：动作识别、时序动作定位、视频Embedding](https://mp.weixin.qq.com/s/4X521CTcFiitQUHvf60dIQ)       :star::star:
   - Abstract: 视频理解综述：动作识别、时序动作定位、视频Embedding
   - Tips: 本文将介绍视频理解中的三大基础领域:动作识别(Action Recognition)、时序动作定位(Temporal Action Localization)和视频 Embedding

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicV4sIdrNiaNmxBYnYO4C6E5LfKWicWG6bebdAq30T0Zk8vbe2QZFzH6xMDYwOQP2cgZI6ibdfnVPx2g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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