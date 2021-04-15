# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.4.15

------



## :paperclip:  今日要点

1. [压缩版styleGAN，合成高保真图像，参数更少、计算复杂度更低](https://mp.weixin.qq.com/s/W3T72paS1mlQdt2ZIqdejw)         :star::star::star:
   - 主要内容：提出了一种名为 MobileStyleGAN 的新架构
   - paper: [MobileStyleGAN: A Lightweight Convolutional Neural Network for High-Fidelity Image Synthesis](https://arxiv.org/pdf/2104.04767.pdf)
   - code: [https://github.com/bes-dev/MobileStyleGAN.pytorch](https://github.com/bes-dev/MobileStyleGAN.pytorch)
   - Tips: 相比于 StyleGAN2，参数量减少了约 71 %，计算复杂度降低约 90 %，并且生成质量几乎没有下降。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWibOjTBJ6gIBRJVP58iau9icwiagicjvHXztPuicFO0DyaOJWScEDeeweEh1qhxbIK87DWfKcX8WBicErWlA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


2. [突破置换模块计算瓶颈，MSRA开源轻量版HRNet，超越主流轻量化网络！｜CVPR2021](https://mp.weixin.qq.com/s/q188jdQq5UJSgX7EHQtZwQ)       :star::star:
   - 主要内容：Lite-HRNet是针对HRNet的轻量化设计
   - paper: [Lite-HRNet: A Lightweight High-Resolution Network](https://arxiv.org/abs/2104.06403)
   - code: [https://github.com/HRNet/Lite-HRNet](https://github.com/HRNet/Lite-HRNet)
   - Tips: 通过简单的将ShuffleNet中的置换模块嵌入到HRNet即可得到性能优于其他轻量化方案的基础版Lite-HRNet;通过引入一种高效条件通道加权单元替换置换模块的卷积得到本文所提改进版高效网络Lite-HRNet

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrD0Y0ROfQrccvKPY9Z3k7kiamQIiaHuEtX99j9dS3z9qMFHxFsxIsZrStSF95ZmTedqnUTy9whBLMQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR 2021 | MSRA提出像素级别自监督预训练方法PixPro，大幅提升下游检测分割任务性能](https://mp.weixin.qq.com/s/Gbb1l7qNQSzVaGkf-8faeQ)       :star::star:
   - 主要内容：针对下游密集任务的自监督算法PixPro
   - paper: [Propagate Yourself: Exploring Pixel-Level Consistency for Unsupervised Visual Representation Learning](https://arxiv.org/abs/2011.10043)
   - code: [https://github.com/zdaxie/PixPro](https://github.com/zdaxie/PixPro)

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oUu3hnwv7QWic8OHLtycxQt20sP6hYBBuMHIoklFict9MunLdR5OrkkfzRJwhibLMiajA119IKxAmJ8jQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [Kaggle竞赛中使用YoloV5将物体检测的性能翻倍的心路历程](https://mp.weixin.qq.com/s/ynTrY88wKj6YQ85igdSH4w)       :star::star:
   - 主要内容：Kaggle比赛经验分享
   - code: [https://github.com/mostafaibrahim17/VinBigData-Chest-Xrays-Object-detection-](https://github.com/mostafaibrahim17/VinBigData-Chest-Xrays-Object-detection-)
   - Tips: 这里采用“2 filter”的方式和我之前参与的违法广告里面想用的思路一致

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KYSDTmOVZvqYWyIxpqbDHXySdngD3fxjX4Gcf5ek2nam5SVBhsaS7PUqnwt0xRxS25fq4ESXq6ccT8vmic6ZuWg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [近期计算机视觉算法竞赛汇总：2021.4--2021.9](https://mp.weixin.qq.com/s/Tcsqk4It92KaVeNycPw5jg)       :star::star:
   - 主要内容：近期的一些计算机视觉比赛




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
</details>
</pre>



## :paperclip:  Others

- 由于图片权限问题，[GitHub](https://github.com/xiaoxuebajie/dairly_learning)是完整版，可以点点 star
- 星标的数量是与个人相关程度，不代表文章内容的好坏
- 关注我的[CSDN](https://mp.csdn.net/console/article)博客
- 关注我的[哔哩哔哩](https://space.bilibili.com/424394389?spm_id_from=333.788.b_765f7570696e666f.1)
- 关注我的公众号CV伴读社

<div align=center><img src="https://img-blog.csdnimg.cn/202005031406335.jpg" style='zoom:80%'>
</div>