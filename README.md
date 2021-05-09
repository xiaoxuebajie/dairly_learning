# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.9

------



## :paperclip:  今日要点

1. [CoMoGAN （白天->黑夜->白天） 连续模仿引导的 img-to-img translation |CVPR2021](https://mp.weixin.qq.com/s/uQSdwJ-Rysq62h1YcyQdoQ)         :star::star:
   - Abstract: 连续模仿引导的 img-to-img translation的CoMoGAN
   - Paper: [CoMoGAN: continuous model-guided image-to-image translation](https://arxiv.org/abs/2103.06879)
   - Code: [https://github.com/cv-rits/CoMoGAN](https://github.com/cv-rits/CoMoGAN)
   - Tips:  CoMoGAN可以与任何GAN主干一起使用，并且允许新类型的图像转换，例如像timelapse生成这样的循环图像转换，或者分离的线性转换

<div align=center><img src="notes/202105/images/sample_result.gif" style='zoom:100%'>
</div>


2. [技压群雄！2021 NTIRE @CVPR 2021的三冠一亚视频超分方案：BasicVSR++](https://mp.weixin.qq.com/s/TyYb6jKW7GCBCVjP5TN_UQ)       :star::star:
   - Abstract: 视频超分方案BasicVSR++
   - Paper: [BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment](https://arxiv.org/pdf/2104.13371.pdf)
   - Code: [https://github.com/open-mmlab/mmediting](https://github.com/open-mmlab/mmediting)
   - Tips: 本文提出了流引导可变形对齐，该模块使用光流作为基础偏移量而没有直接学习DCN偏移量，通过学习残差偏移量来减轻偏移量学习的负担

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTut9cNvfutZOwW1C2ibQcjklcsX39OmO0UyTVjVQoksqBFhGPIrtlnBJ8OVt4wU4PkEEE9n8liceCmg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [Deblurring by Realistic Blurring 图像去模糊论文解读](https://mp.weixin.qq.com/s/Hee6PTXZ1ZgtgMpWLthV_w)       :star::star:
   - Abstract: 一种全新的图像去模糊GAN网络
   - Paper: [Deblurring by Realistic Blurring](https://ieeexplore.ieee.org/document/9156306)
   - Tips: 设计了一个可以生成逼真合成模糊图像的GAN网络，并提出了一种新的对抗损失函数，其实很多领域都可以借鉴这篇文章的方法来生成数据集

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SdQCib1UzF3sAV9icNA3Q5XFngqzHOhYAzYCXhiclO5aFAYPC9OEa0Jicod6Agm4icdHkSqlzaYJrBnLia3K4QFCDOxw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [计算机视觉物体检测中所面对的挑战](https://mp.weixin.qq.com/s/c_uZJXLcpkyrAhhzTk1YdA)       :star::star:
   - Abstract: 目前目标检测中的一些问题和挑战
   - Tips: 视角的多样性，变形，遮挡，光照，杂乱或有纹理的背景，速度等

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/KYSDTmOVZvrt7YLvabtHDBbCCq3ItoLxAxqGxOJm8JnicF6r5qWodJSQ13bM3WEvL9jAEmXlBUovkicBKOZTZupg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [大神推荐：国内较强的NLP高校实验室有哪些？](https://mp.weixin.qq.com/s/JUofGnVaYIU1j4LMKrNgaQ)       :star::star:
   - Abstract: 国内较强的NLP高校实验室
   - Tips: 研究方向是NLP的同学找导师的话可以优选之


6. [【NLP】可交互的 Attention 可视化工具！我的Transformer可解释性有救了？](https://mp.weixin.qq.com/s/s-94r54K6i-CqxHZaG_u5Q)       :star::star:
   - Abstract: DODRIO，一种可交互的Attention可视化工具
   - Paper: [DODRIO: Exploring Transformer Models with Interactive Visualization](http://arxiv-download.xixiaoyao.cn/pdf/2103.14625.pdf)
   - Code: [https://poloclub.github.io/dodrio/](https://poloclub.github.io/dodrio/)
   - Tips:  从句法和寓意层面总结了不同注意力头的信息

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qFLWnPvDEgVfwuLAWGFcUQicX9mF0KhNNfGUOR4XiarLmGBYEPRrUrNGHRtufKJjqbkggMD8XUExpbw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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