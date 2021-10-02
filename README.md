# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.10.1

------



## :paperclip:  今日要点

1. [NLP与CV大一统的尽头是语言模型？Hinton团队提出Pix2Seq做目标检测，性能抗打！](https://mp.weixin.qq.com/s/UKdiPF0ro9IgUcYxPmXo0Q)         :star::star:
   - Abstract: Hinton团队提出Pix2Seq做目标检测
   - Paper: [PIX2SEQ: A LANGUAGE MODELING FRAMEWORK FOR OBJECT DETECTION](https://arxiv.org/pdf/2109.10852.pdf)
   - Tips:  将目标检测问题转化为NLP，这种转变会带来很多值得探索的方向。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqTes2wbJibCk8XfbdpGibBMrw6jrgU5Kjeo3RrPxPiayvct7mqS1jHV3Q3GEyKrcXZ1fOtAWn0A1wzA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [重磅干货来袭 | 关系网络用于目标检测（文末附源码）](https://mp.weixin.qq.com/s/ZJ5Jnk7azL3oku1jM3n5gQ)       :star::star:
   - Abstract: 关系网络用于目标检测
   - Paper: [Relation Networks for Object Detection](https://arxiv.org/pdf/1711.11575.pdf)
   - Code: [https://github.com/msracver/Relation-Networks-for-Object-Detection](https://github.com/msracver/Relation-Networks-for-Object-Detection)
   - Tips: 作者提出一个模块object relation module来描述目标之间的关系，同时引入到NMS中来提升性能。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwN6VStBnd3CGEcy4H4GS8EgJ8oux3fPhvDzK5CcLvVVZF9pCPhfudEavXgMhDnPiaLJ6aFuBichEHMQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [谷歌提出COMISR算法：针对视频压缩的压缩感知超分辨率](https://mp.weixin.qq.com/s/DhE49Ek0v0PelDewNNjP3w)       :star::star:
   - Abstract: 针对视频压缩的压缩感知超分辨率COMISR算法
   - Paper: [COMISR: Compression-Informed Video Super-Resolution](https://arxiv.org/pdf/2105.01237.pdf)
   - Tips: 针对H.264等视频压缩标准压缩后的视频进行超分，定量和定性效果相比过去的是视频超分辨率（VSR）算法有较大提升，有一定的业界价值。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTs2ECmrCYiabng4SpaLPC99Fic56hzeCGibdyw4mdZpSwItuASvRHWx9wKhHtsQ8RE7HwG7BhJfZ6T3A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [国庆堵车 | AI“高速”车辆检测轻而易举监测大家安全](https://mp.weixin.qq.com/s/LV8BTi1gAfpmxRIM_NUiHA)       :star::star:
   - Abstract:  通过目标检测实现车辆检测
   - Tips: 主要采用的SSD+LSN+双向网络（核心）

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwOuNIIv749gaVBDicnN2PaNy6TVae17XUvR4UGd3KyseT9SNFj1X1abD3p96Msm3pibE7nyIs9o9NVw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [深度框架训练：不是所有数据增强都可以提升最终精度](https://mp.weixin.qq.com/s/YryR16mQ-VJeWAlRVZd6PQ)       :star::star:
   - Abstract: 不是所有数据增强都可以提升最终精度
   - Tips: 数据增强可能会引入噪声增强的例子，从而在推理过程中损害非增强数据的性能

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNEBqGkDOyUqpUrZo2saDnwh9LH6Q7PHaPyLN1zBue4ia0Nuw3ug64LlBLZ6s0eWF5E5vKwCdtnT7Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [详尽实用的 PyCharm 教程，这篇文章值得一看](https://mp.weixin.qq.com/s/lv55Z_w5F1brk99P3r4zLA)       :star::star:
   - Abstract: 详尽实用的 PyCharm 教程
   - Tips: 非常详尽，包括安装运行以及debug等等

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/qX7rSBgoEp3ibc5jqqODEibTo7FCTXS90cmFicOFejXntAgOGcRbN2jayuic9AHyv1YfHSftOmRkEo3EGKyDQDXkGQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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