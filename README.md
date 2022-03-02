# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.2

------

## :paperclip:  今日要点

1. [SFU、阿里提出通用QuadTree Attention，复杂度变线性，性能还更强！ICLR 2022已接收](https://mp.weixin.qq.com/s/GNNcOcTC0WddrhJi7afPSA)         :star::star:
   - Abstract: SFU、阿里提出通用QuadTree Attention，复杂度变线性，性能还更强！
   - Paper: [Quadtree Attention for Vision Transformers](https://openreview.net/forum?id=fR-EnKWL_Zb)
   - Code: [https://github.com/Tangshitao/QuadtreeAttention](https://github.com/Tangshitao/QuadtreeAttention)
   - Tips:  本文设计了一个高效的视觉Transformer，它可以捕捉精细的图像细节和长期依赖关系。在观察到大多数图像区域是不相关的启发下，构建了Token pyramids，并以从粗到细的方式计算注意力。这样，当对应的粗粒度区域没有前景时，可以快速跳过细粒度的不相关区域。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tglKibodsHREJCyDnTSkZkH5Bkj0tdls0CnIPLibB1fqolew6cbN6bPfzKanqfjbiay7ZiaBygvevIUheA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [1000层的Transformer，诞生了！](https://mp.weixin.qq.com/s/Ke8_go0wReLMejhJolnd9Q)       :star::star:
   - Abstract: 1000层的Transformer，诞生了！
   - Paper: [DeepNet: Scaling Transformers to 1,000 Layers](https://arxiv.org/pdf/2203.00555.pdf)
   - Code: [https://github.com/microsoft/unilm](https://github.com/microsoft/unilm)
   - Tips: 这篇论文最关键的贡献就是提出了一种新的Normalization方式——DeepNorm，有效解决了Transformer训练困难的问题。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qFXgia11bTu5S3ziaOOQ45efTjvqGsnJTE4eS8S20NRLvpMK0zaeF2e4mZriagQ7aP51OLyBgR9qTI5g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [解决图像分割落地场景真实问题，港中文等提出：开放世界实体分割](https://mp.weixin.qq.com/s/yiaAUCfEEjLXozWV6S9NKg)       :star::star:
   - Abstract: 解决图像分割落地场景真实问题，港中文等提出：开放世界实体分割
   - Paper: [Open-World Entity Segmentation](https://arxiv.org/abs/2107.14228)
   - Code: [https://github.com/dvlab-research/Entity](https://github.com/dvlab-research/Entity)
   - Tips: : 本文出发点是想解决语义/实例/全景分割在某些落地场景中实际存在的一些问题，因此提出了实体(Entity)分割任务，在图像编辑过程中对图像进行分"块"而无需对这些"块"进行分类识别，经过分割结果衡量和算法设计，取得了较好的图像分割效果。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfptGPkicu977zX1Qs7iaPQODyuRPE4p0k7JicP0yNKQngDoiaep3x29qFANiblLMuGA8bLph03JsicJJw0Q/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [实践教程｜分割mask生成动漫人脸！爆肝数周，从零搭建](https://mp.weixin.qq.com/s/IGacYvj0yGW8C3nAua54uQ)       :star::star:
   - Abstract: 分割mask生成动漫人脸！爆肝数周，从零搭建
   - Tips: 论本文分享了国外大佬的从0开始构建分割mask生成动漫人脸的项目，整个思路的搭建阐述的都非常的详细，有兴趣的朋友们可以按照这个流程去尝试自己搭建.

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/7jnsg27ZEVEVhQY9pclicI6dibzJCsNggbwvIh2LKzeoKQCxManolLOzOZWZK7Nk8hBnzkdcSckWq9UuAtphXX7g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [最近 Github 上爆火的 Chrome 生产力神器 Omni 是什么鬼？](https://mp.weixin.qq.com/s/gbaje_ZkicVWXXbcoXc6Lg)       :star::star:
   - Abstract: 最近 Github 上爆火的 Chrome 生产力神器 Omni 
   - Code: [https://github.com/alyssaxuu/omnin](https://github.com/alyssaxuu/omni)
   - Tips: Omni 是一个浏览器插件，它让你能够想使用 Mac 电脑一样使用你的浏览器，最近 Omni 接连登上 Github 趋势榜与 ProductHunt 榜首，成为大受各种程序员、产品设计师的追捧的生产力工具！

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/YmT5bQSrMy3UOmNgcNPlbq9oOfX8A7N2c5sRG9dtUyWb7dbLgj41ZwYcSs8sVPwTibH1MZorf7U5kddpdcw0IvA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [脑力25岁开始走下坡路？百万人数据证实：60岁以后才下降｜Nature子刊新研究](https://mp.weixin.qq.com/s/OuJ3CaM56qQsJPNujta_4A)       :star::star:
   - Abstract: 百万人数据证实：脑力60岁以后才下降
   - Paper: [Mental speed is high until age 60 as revealed by analysis of over a million participants](https://www.nature.com/articles/s41562-021-01282-7)
   - Code: [https://github.com/stefanradev93/DataSizeMatters](https://github.com/stefanradev93/DataSizeMatters)
   - Tips: 大脑处理信息的速度能从20岁一直保持到60岁。随着年龄增长，人会越来越谨慎。他们试图避免犯错，时间花在了反复考虑追求确定性上。思维速度在30岁左右达到巅峰，在30岁到60岁之间仅有轻微回落，直到60岁以后大脑处理信息的速度才真正开始下降。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/YicUhk5aAGtAKHQPnbLqbjH3OJtBNhYdXiasJfzzicG4kKg0FfhwNeicXrHleLVsdXickG9uLcbeJQsQnTOn0dtOXCw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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