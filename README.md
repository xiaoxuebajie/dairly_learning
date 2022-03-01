# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.1

------

## :paperclip:  今日要点

1. [TTFNet：改进CenterNet，使得训练时间缩短7倍](https://mp.weixin.qq.com/s/E9XCpho0kPF6430rTjqN_Q)         :star::star:
   - Abstract: TTFNet：改进CenterNet，使得训练时间缩短7倍
   - Paper: [Training-Time-Friendly Network for Real-Time Object Detection](https://arxiv.org/abs/1909.00700)
   - Code: [https://github.com/ZJULearning/ttfnet](https://github.com/ZJULearning/ttfnet)
   - Tips:  本文是对CenterNet的一种改进，主要是增加了训练时参与回归的样本，提升了收敛速度，加快了训练时间，同时使用了椭圆高斯核来代替CenterNet中的圆形高斯核，感觉更加合理。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KYSDTmOVZvollhHAJ83ID8UiaptPRHFzqaRAIql1PHUvF3QWVr71XUAyZglZBHZQ9IVRaibZd7VDcEUsszO78HAQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



2. [SWideRNet：全景分割新标杆！](https://mp.weixin.qq.com/s/eBi8yAJY0YKHh2cp0-ivCA)       :star::star:
   - Abstract: SWideRNet：全景分割新标杆！
   - Paper: [Scaling Wide Residual Networks for Panoptic Segmentation](paper: https://arxiv.org/abs/2011.11675)
   - Tips: 本文是DeepLab系列作者“Liang-Chieh Chen”大神在全景分割领域的又一力作。它在Wide-ResNet的基础上引入SE与"Switchable Atrous Convolution,SAC"两种改进，嵌入到Panoptic-DeepLab框架中并在全景分割领域取得了SOTA性能(在更快、更大模型配置方面均取得了SOTA指标)。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqx7sZxYefZ3p2gRFxsGjabuq9OuxxIzGkNTicqeHItdyW7UdEjrartn8xCu9NZktcEJsnraia1qSdA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [谷歌Quoc V. Le团队新作FLASH：高效Transformer新设计！训练成本暴减！](https://mp.weixin.qq.com/s/evNb8bFJJwd4ratif8LgPg)       :star::star:
   - Abstract: 谷歌Quoc V. Le团队新作FLASH，高效Transformer新设计
   - Paper: [Transformer Quality in Linear Time](https://arxiv.org/abs/2202.10447)
   - Code: [https://github.com/DerrickXuNu/OpenCOOD](https://github.com/DerrickXuNu/OpenCOOD)
   - Tips: : 谷歌的新研究FLASH，让 transformer 模型的效率有了巨大提升，该方法的核心在于减少注意力机制。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8oQr96R8fL6nPWOWw8rvSgBLFd5I2PvLB0UPxRUgYfvEkuUSA6s3C8ia1AtphqVDhjriap5hL9riabw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




4. [R-C3D 视频活动检测](https://mp.weixin.qq.com/s/bLpPw1cPTCuarOewYKGFrA)       :star::star:
   - Abstract: 视频活动检测经典模型 R-C3D
   - Paper: [R-C3D: Region Convolutional 3D Network for Temporal Activity Detect](https://arxiv.org/pdf/1703.07814.pdf)
   - Code: [http://ai.bu.edu/r-c3d/](http://ai.bu.edu/r-c3d/)
   - Tips: 论文提出了活动检测模型，即R-C3D,这是一种端到端活动检测模型，结合活动建议和分类阶段，可以检测任意长度的活动。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTvY0X0no58EdzS4L2TDopKOcrRAGLNDLoial6l1PW41p4bXswhibrL3ib0hibdE6WbXzZjia4uTINg9m8g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




5. [AAAI 2022 | RTPB: 针对无偏场景图生成的抵抗训练方法](https://mp.weixin.qq.com/s/cNhszsKdGyDBvsty-RJrPg)       :star::star:
   - Abstract: RTPB: 针对无偏场景图生成的抵抗训练方法
   - Paper: [Resistance Training using Prior Bias: toward Unbiased Scene Graph Generation](https://arxiv.org/abs/2201.06794)
   - Tips: 为抑制数据集长尾分布问题对场景图生成任务的影响，我们提出了一种基于数据集先验偏差的抵抗训练方法，基于训练集的统计信息，调整训练进程，抑制数据长尾分布对模型的影响，实现更加平衡的场景图生成。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Mcdq8uia1Wiacs5VfsUDEjhyhSFbGsS6becLaiaRu1JJaMc5xKaFMrdcF9IpqQpoWrUvJANa9qKYmyLia2B992QiciaA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [谷歌和伯克利分校的新工作：规模化大场景的神经绘制方法Block-NeRF](https://mp.weixin.qq.com/s/jq3vo99goqQsltvPDqcT1A)       :star::star:
   - Abstract: 谷歌和伯克利分校的新工作：规模化大场景的神经绘制方法Block-NeRF
   - Paper: [Block-NeRF: Scalable Large Scene Neural View Synthesis](https://mp.weixin.qq.com/s/jq3vo99goqQsltvPDqcT1A)
   - Tips: Block-NeRF，一种可以代表大规模环境的Neural Radiance Fields（NeRF）变型。具体来说，规模化的NeRF渲染跨越多个块（blocks）的城市规模场景时，将场景分解为单独训练的NeRF。这种分解将渲染时间与场景大小分解，使渲染能够扩展到任意大的环境，并允许对环境进行逐块更新。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwhXwL96K8yWmRjOoTicvCKicrdEmibeUpiamTa72Ch3qib3RuicMw1RKt2g9ACs8Siaqk0db51icNsBXlTYHw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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