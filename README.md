# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.6

------



## :paperclip:  今日要点

1. [CVPR2021 | 华为诺亚实验室提出Transformer in Transformer](https://mp.weixin.qq.com/s/h_MzNIXBW2pjcpNEXEerCw)         :star::star:
   - Abstract: 同时利用了块内部序列和块之间序列信息的transformer模型TNT
   - Paper: [Transformer in Transformer](https://arxiv.org/abs/2103.00112)
   - Code: [https://github.com/huawei-noah/noah-research/tree/master/TNT](https://github.com/huawei-noah/noah-research/tree/master/TNT)
   - Tips: 通过提出的TNT模型，可以把全局和局部的结构信息建模，并提高特征表示能力

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTWx3TXC7qp4SULxEK9eOavLrJiburQBHibyeH0nicN0ZGKDOdDCb66652FKT18ibYe7Vz4ztQBk50vT7Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2021 | pixelNeRF：一种基于NeRF的多视图三维重建网络](https://mp.weixin.qq.com/s/_BIJEe099JsYZpYX109Xbg)       :star::star:
   - Abstract: 只需要输入单张或多张图像，就能得到连续场景表示的学习框架pixelNeRF
   - Paper: [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/pdf/2012.02190.pdf)
   - Code: [https://alexyu.net/pixelnerf/](https://alexyu.net/pixelnerf/)
   - Tips: 
     - Pixel可以在多视图图像的数据集上面进行训练，而不需要任何额外的监督
     - PixelNeRF预测输入图像的摄像机坐标系中的NeRF表示，而不是标准坐标系
     - 它是完全卷积的，这允许它保持图像和输出3D表示之间的空间对齐
     - PixelNeRF可以在测试时合并任意数量的输入视图，且不需要任何优化

<div align=center><img src="https://alexyu.net/pixelnerf/img/teaser/dtu_outputs_sm.gif" style='zoom:100%'>
</div>


3. [CVPR 2021 | MotionRNN：针对复杂时空运动的通用视频预测模型](https://mp.weixin.qq.com/s/oBqtGcmsZtj_IWxBbdoGPg)       :star::star:
   - Abstract: 分解现实世界复杂运动的通用视频预测模型MotionRNN
   - Paper: [MotionRNN: A Flexible Model for Video Prediction with Spacetime-Varying Motions](https://arxiv.org/abs/2103.02243)
   - Tips: MotionRNN将运动趋势和瞬时变化进行统一建模，可以准确反映复杂的时空运动，得到更优的预测结果。同时，作为一个通用的视频预测模型，MotionRNN可以与现有的基于RNN模型结合，增强它们对于复杂时空运动的预测能力。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/2yicI4uAMVVF47MwkVrm4hYLhAnFAXT3osmiaefOiaDnibYpHOm7Stn4CnfxgXOYbMCOwEdQTlkU27JoZf39I2MQLw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [TransGAN：纯粹而又强大](https://mp.weixin.qq.com/s/OnPJrZkz_qr4lup9j6abDg)       :star::star:
   - Abstract: 将Transformers结构作为GAN网络的主结构的TransGAN
   - Paper: [TransGAN: Two Transformers Can Make One Strong GAN](https://arxiv.org/abs/2102.07074)
   - Code: [https://github.com/VITA-Group/TransGAN](https://github.com/VITA-Group/TransGAN)
   - Tips: 纯粹采用Transformers作为GAN模型的主体效果在一定程度上还是不错的

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/AIR6eRePgjOgBZQNgO5aaAnLdgkVddT3haC7rB7BA3ZOwYDe8HYZjg744cOJOLbB4wnc9icFIj9mcTYB8kuMENw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [Facebook刷新开放域问答SOTA：模型训模型！Reader当Teacher！](https://mp.weixin.qq.com/s/YfsqWQnz1FIrUC-MtTX0iQ)       :star::star:
   - Abstract: 利用生成式阅读器中的注意力权重作为相似度信息训练检索模型，刷新了开放域问答系统的SOTA
   - Paper: [DISTILLING KNOWLEDGE FROM READER TO RETRIEVER FOR QUESTION ANSWERING](https://openreview.net/pdf?id=NTEz-6wysdb)
   - Code: [https://github.com/lucidrains/distilled-retriever-pytorch](https://github.com/lucidrains/distilled-retriever-pytorch)
   - Tips: 简单有效地解决了开放域问答系统中训练检索模型缺乏标注数据的问题，为研究者们提供了新思路。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qEBqPZ0VkNNydjicj645urjoKfANCgDqXKmtyGHmjugpFwqiaGLjvU5hojsbKE912EllGnHnavJA26w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [【综述专栏】对抗网络：李宏毅GAN课程笔记](https://mp.weixin.qq.com/s/Uzpz57GH6kmPpc9awKEsVA)       :star::star:
   - Abstract: 李宏毅GAN课程笔记
   - Tips: 学习李宏毅老师GAN课程的笔记，全文约1.9w字，白嫖就完事了

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/AIR6eRePgjOtX6pTJqPiceP2goemWQTWOkXqk0z3FaFYichwdMoH5ZaFd2tOaT0Adh3CBQdu6JXicURyibib7KvGWcw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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