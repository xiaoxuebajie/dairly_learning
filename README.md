# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.30

------

## :paperclip:  今日要点

1. [CVPR 2022｜基于GAN逆映射的高保真图像编辑算法 by 港科大&腾讯AI Lab开源](https://mp.weixin.qq.com/s/AYQWrbdIynwglxFUz_Ri5Q)         :star::star:
   - Abstract: 基于GAN逆映射的高保真图像编辑算法
   - Paper: [High-Fidelity GAN Inversion for Image Attribute Editing](https://arxiv.org/abs/2109.06590)
   - Code: [https://github.com/Tengfei-Wang/HFGI](https://github.com/Tengfei-Wang/HFGI)
   - Tips:  本文提出了一种名为信息参照（information consultation）的方法，同时利用low-rate和high-rate隐编码。该模型包括两个编码器，基础编码器压缩低率隐编码，用于保证图像的可编辑性；参照编码器对低率重建图像的失真信息进行补充编码，得到一个高率的隐编码，补充丢失的细节信息。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_png/gYUsOT36vfo2EXh31yIPtb0f44V0uEcUq88NU7TwRHa7rCrMK99bVC0SkDasTicWoHJgvCKJvZCLo7X8IuOdOcA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2022 | 华南理工提出VISTA：双跨视角空间注意力机制实现3D目标检测SOTA，即插即用](https://mp.weixin.qq.com/s/QJmqRk0tqZd-4Io1TBM-9g)       :star::star:
   - Abstract: 华南理工提出VISTA：双跨视角空间注意力机制实现3D目标检测SOTA，即插即用
   - Paper: [VISTA: Boosting 3D Object Detection via Dual Cross-VIew SpaTial Attention](https://arxiv.org/abs/2203.09704)
   - Code: [https://github.com/Gorilla-Lab-SCUT/VISTA](https://github.com/Gorilla-Lab-SCUT/VISTA)
   - Tips:  本文提出了 VISTA，一种新颖的即插即用多视角融合策略，用于准确的 3D 对象检测。为了使 VISTA 能够关注特定目标而不是一般点，研究者提出限制学习的注意力权重的方差。将分类和回归任务解耦以处理不平衡训练问题。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8ibFhOLCfAmFN6s8icGW9WYkibMvSwHicF5Wcwp7k2OOmE7Z1JnoNkHChPfmu4gsH7ribe6rF6y4hatcw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR 2022｜Adobe提出InsetGAN！ 全身都生成，这可太GAN了](https://mp.weixin.qq.com/s/4sR6IDlhYKAu8T4g05hzcg)       :star::star:
   - Abstract: Adobe提出InsetGAN！ 全身都生成，这可太GAN了
   - Paper: [InsetGAN for Full-Body Image Generation](https://arxiv.org/abs/2203.07293)
   - Tips: 他们首先引入了一个边界框检测器，检测部分GAN生成的特定区域在底层画布，也就是全身GAN生成的区域中的位置，经过裁剪后再将特定区域嵌入。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfo1C6AbudEABOxOdvicXC5icGM3FoT7uUfMHZxqqOvia2UxFDibAAeiaJl9y0aOaSnSKQdodWY9ZUglncw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [Swim-Transform V2：用于目标检测，视觉大模型不再是难题（附源代码）](https://mp.weixin.qq.com/s/8ItDlfkQfTrdpJc9A2luuQ)       :star::star:
   - Abstract: Swim-Transform V2：用于目标检测，视觉大模型不再是难题（附源代码）
   - Paper: [Swin Transformer V2: Scaling Up Capacity and Resolution](https://arxiv.org/pdf/2111.09883.pdf)
   - Code: [https://github.com/microsoft/Swin-Transformer](https://github.com/microsoft/Swin-Transformer)
   - Tips: MSRA时隔大半年放出了Swin Transformer 2.0版本，在1.0版本的基础上做了改动，使得模型规模更大并且能适配不同分辨率的图片和不同尺寸的窗口！这也证实了，Transformer将是视觉领域的研究趋势！

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwPafgZwmXyn9YJVUPgaIroNicficOibzZmqTToVC7Zm7vKmY8DbicVENCl2Au3pHX7oDBKWG2usc8s22A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [CVPR 2022 | 天大本科生论文入选！深度学习长尾分类新SOTA](https://mp.weixin.qq.com/s/n7jloECjzmhftMeZBwfWdA)       :star::star:
   - Abstract: 深度学习长尾分类新SOTA
   - Paper: [Trustworthy Long-Tailed Classification](https://arxiv.org/abs/2111.09030)
   - Tips: 通过引入不确定性集成，来实现对尾部类别样本的自动感知。在此基础上，提出为尾部类别样本动态分配比头部样本更多的模型资源（experts），以兼顾性能与效率。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qFQcBXEhW2NFnD8ZibVJAavpxoviaqUyicibEth2icXXicAGar7fLGbPyPzokOEIh1Ob0z9dKLWKHOHoNaw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [刷新4个SOTA！港大&字节开源ReferFormer: 语言作为查询的视频目标分割框架](https://mp.weixin.qq.com/s/MsEBgLRJ8TxTS6opeewNyw)       :star::star:
   - Abstract: 港大&字节开源ReferFormer: 语言作为查询的视频目标分割框架
   - Paper: [Language as Queries for Referring Video Object Segmentation](https://arxiv.org/abs/2201.00487)
   - Code: [https://github.com/wjn922/ReferFormer](https://github.com/wjn922/ReferFormer)
   - Tips: 研究者们提出了一种基于Transformer的参考视频目标分割新框架ReferFormer。其将语言描述视为查询条件，直接在视频中查找目标对象，除此之外，通过实例序列的整体输出自然地完成目标物体的跟踪，无需进行任何后处理。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oUEGwNWCu09LOic1W2uZbblYpsndsxhTMucEG9E6VcYmPJoYAq9I5MibOnQxbTKOnpGPgkUvUhSSXyg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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