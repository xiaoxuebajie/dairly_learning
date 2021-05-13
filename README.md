# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.13

------



## :paperclip:  今日要点

1. [CVPR 2021 | 无需密集人工标签，用于下游密集预测任务的自监督学习方法出炉](https://mp.weixin.qq.com/s/YTnKI2RLHzPwHkvRbWipjQ)         :star::star:
   - Abstract: 无需密集人工标签，用于下游密集预测任务的自监督学习方法
   - Paper: [Dense Contrastive Learning for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2011.09157.pdf)
   - Code: [https://github.com/WXinlong/DenseCL](https://github.com/WXinlong/DenseCL)
   - Tips:  该研究提出的新方法 DenseCL（Dense Contrastive Learning）通过考虑局部特征之间的对应关系，直接在输入图像的两个视图之间的像素（或区域）特征上优化成对的对比（不相似）损失来实现密集自监督学习

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9M1nGfNRTsDzlwx5fx2fmOMRqojLGX4NuxhT1CbfwW1u3ib8LDeyvOY2Mjj6OkxPJic3U3EwRL5O7w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [CVPR 2021| 端到端场景无关视觉定位算法(SuperGlue一作出品)](https://mp.weixin.qq.com/s/cjtHKEUqSGM8Ej_mOhLjWg)       :star::star:
   - Abstract: 端到端场景无关视觉定位算法PixLoc
   - Paper: [Back to the Feature: Learning Robust Camera Localization from Pixels to Pose](https://arxiv.org/abs/2103.09213)
   - Code: [http://github.com/cvg/pixloc](http://github.com/cvg/pixloc)
   - Tips:  PixLoc能够做到场景无关的端到端学习位姿，且能够较好地做到跨场景（室外到室内）的相机定位

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/RkDHyHvXvJ7aibibUCicRh3JvicDyibD0PXZvRdUwiaa5fkoJxcVn48C0XdaUnZComKIkx2YuhIUWIPuw5xlebBjeteg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [PatchmatchNet：一种高效multi-view stereo框架 (CVPR2021 Oral)](https://mp.weixin.qq.com/s/vR6Qz68we082kpZy5-XzEw)       :star::star:
   - Abstract: 一种高效multi-view stereo框架PatchmatchNet
   - Paper: [PatchmatchNet: Learned Multi-View Patchmatch Stereo](https://arxiv.org/abs/2012.01411)
   - Code: [https://github.com/FangjinhuaWang/PatchmatchNet](https://github.com/FangjinhuaWang/PatchmatchNet)
   - Tips: PatchmatchNet是一种以learning-based Patchmatch为主体的cascade结构，对传统的PatchMatch进行了拓展，提出了adaptive propagation和adaptive evaluation

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/Q0FNTB1XHicy1BFcBpwR4QtQ3ZxeHCicZ1BKyiaBvicx03LVtBsPMVUickkTx5NgrMN0UQeydJg9waPhvghyfniaZeVg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [CVPR2021| TimeSformer-视频理解的时空注意模型](https://mp.weixin.qq.com/s/VDkJ3Ro-4yMytjk7DNoeEg)       :star::star:
   - Abstract: TimeSformer-视频理解的时空注意模型
   - Paper: [Is Space-Time Attention All You Need for Video Understanding?](https://arxiv.org/abs/2102.05095)
   - Code: [https://github.com/lucidrains/TimeSformer-pytorch](https://github.com/lucidrains/TimeSformer-pytorch)
   - Tips: TimeSformer通过直接从一系列帧级别的patch中启用时空特征学习，将标准的Transformer体系结构适应于视频

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTVXcUwFiblB9Q4IicE5bWxwUjiaRiawm6T5Iu0lFZzIlDefnj9auEgI5ES3xNiadiaCGia2ZaapFjCpXuaAg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [来自Google Research：宽模型和深模型学到的是相同的东西吗？](https://mp.weixin.qq.com/s/3LtHqNrIp-grM0nQU_Qq0Q)       :star::star:
   - Abstract: 宽模型和深模型学到的是相同的东西吗？
   - Paper: [Do Wide and Deep Networks Learn the Same Things? Uncovering How Neural Network Representations Vary with Width and Depth](https://arxiv.org/abs/2010.15327)
   - Tips: 在研究深度和宽度对内部表征的影响时，我们发现了块结构现象，并证明了它与模型容量的联系。我们还表明，宽模型和深模型在类和样本级别上显示出系统输出差异

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KYSDTmOVZvoFs5sS44BmXLhwSwDo6H51CGptCn1jiaO5yldRFzeLgyyH2ZR4iafGILZwdZVI8Nicxy9ewhPZaUoBA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>

6. [用超分辨率扛把子算法 ESRGAN，训练图像增强模型](https://mp.weixin.qq.com/s/ROVY0GN8gh7cbElZmtMRhw)       :star::star:
   - Abstract: 用超分辨率扛把子算法 ESRGAN，训练图像增强模型
   - Code: [https://openbayes.com/console/openbayes/containers/EsAbdwfM6YN](https://openbayes.com/console/openbayes/containers/EsAbdwfM6YN)
   - Tips:  将图像或影片从低分辨率转化为高分辨率，恢复或补足丢失的细节（即高频信息），往往需要用到超分辨率技术，ESRGAN算法的demo

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/QkCvnz083Aj8xCgRCX0icsPp31JWoMbNwflSl3X4OVbjvgibKLdb1sOAZNqsz5Jstw181ZKdIqCxQBz2CCd8YXnQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    11. <a href="notes/202105/05011.md" target="_blank">公众号内容拓展学习笔记（2021.5.11）</a>
    12. <a href="notes/202105/05012.md" target="_blank">公众号内容拓展学习笔记（2021.5.12）</a>
    13. <a href="notes/202105/05013.md" target="_blank">公众号内容拓展学习笔记（2021.5.13）</a>
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