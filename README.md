# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.7

------



## :paperclip:  今日要点

1. [目标检测 | 丰富特征导向Refinement Network用于目标检测（附github源码）](https://mp.weixin.qq.com/s/Ij6uwXkgvLoVVx8Voklyyg)         :star::star:
   - Abstract: Refinement Neural Network解决了多尺度目标检测和类不平衡的问题
   - Paper: [Enriched Feature Guided Refinement Network for Object Detection](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nie_Enriched_Feature_Guided_Refinement_Network_for_Object_Detection_ICCV_2019_paper.pdf)
   - Code: [https://github.com/Ranchentx/EFGRNet](https://github.com/Ranchentx/EFGRNet)
   - Tips: 
     - 引入了一种简单而有效的特征丰富化方案来生成多尺度的上下文特征。
     - 进一步引入了一种级联的优化（精炼）方案

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwOicKqaU8hsiaibejndcaJUgyMWqIyNvpVZ3icgicicGLNmHvT90NeyNXib8ZwK6GRSadR6EurewwSGHaMEQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR2021｜引入记忆模块，突破长距离依赖视频预测的性能瓶颈](https://mp.weixin.qq.com/s/GXcoHk9ks_ekVv-o14fVGg)       :star::star:
   - Abstract: 一种突破长距离依赖视频预测的性能瓶颈视频预测方法
   - Paper: [Video Prediction Recalling Long-term Motion Context via Memory Alignment Learning](https://arxiv.org/abs/2104.00924)
   - Code: [https://github.com/sangmin-git/LMC-Memory](https://github.com/sangmin-git/LMC-Memory)
   - Tips: 本文方法主要由动作上下文驱动的视频预测模块和长距离动作上下文记忆模块构成

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTuWhMkTktMX7SyDicI6UdqGS6FE3Pkj9vuhCoI8WydhboKhz2tiaibLwTzjL1llegmngYqsad0b8rBpg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [SIGGRAPH 2021 | 学习带神经融合形状的人物动画](https://mp.weixin.qq.com/s/IuvyNRJ6amJn5ya7fr8L6A)       :star::star:
   - Abstract: 针对骨骼驱动的模型动画的高质量自动化生成进行改进，提出了神经融合形状技术
   - Paper: [Learning Skeletal Articulations with Neural Blend Shapes ](https://peizhuoli.github.io/neural-blend-shapes/papers/neural-blend-shapes-camera-ready.pdf)
   - Code: [https://github.com/PeizhuoLi/neural-blend-shapes](https://github.com/PeizhuoLi/neural-blend-shapes)
   - Tips: 该方法显著减少了已有方法中需要的人工干预，大大提升了生成动画的质量

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/3ca6UMoKPP2pJ32mXbM4ufmxVWyphsqPBKPliasicC85tFTia85bJGoxguds9z7pQ4qRPycyxVgt4I6Z31tBrkWnA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [复旦团队“人体经络图”火了！耗时9年，证明茶可疏通经络，网友：啊这都可以发论文](https://mp.weixin.qq.com/s/n9LShjiEQIm5QTi9C0neOw)       :star::star:
   - Abstract: 一张“人体经络图”，最近在全网火了。
   - Paper: [Infrared imageries of human body activated by teas indicate the existence of meridian system ](https://journal.hep.com.cn/qb/EN/article/downloadArticleFile.do?attachType=PDF&id=29259)
   - Tips: 偶尔吃吃瓜，看样子得喝喝茶，活络活络经络了。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/YicUhk5aAGtA1y0syEZic7Oe5N2LUD0icLsZ2sDHXxxhAaJdXYD2HhOmiaK0zxlribCcSRuTtKZZyfMI1ia6WHiaG3fGg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [30万字，“保姆级”可视化视觉设计优质学习攻略推荐](https://mp.weixin.qq.com/s/K1x1F7I3KCSSWmsGQH6eKA)       :star::star:
   - Abstract: 数据可视化方法
   - Tips: 之前推送的比较适合绘制普通适用的，这个就直接炫起来了，很不错

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/LVW0j64NZC152iaNAafRBIWUI7LWPxrLO4xzU0FGFr8LD6iaVlg3VAErUibrA3guzs0DjGIib8eoLliaslrLCMmZgfg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [CVPR2021(Oral) 商汤、港中文实现单目人脸重建新突破： 基于生成网络的渲染器！几何形状更精准！渲染效果更真实！](https://mp.weixin.qq.com/s/H2zdQGVBFY4N0x4MmLf55g)       :star::star:
   - Abstract: 基于风格化对抗生成器的人脸渲染器
   - Paper: [Inverting Generative Adversarial Renderer for Face Reconstruction](https://arxiv.org/pdf/2105.02431.pdf)
   - Code: [https://github.com/WestlyPark/StyleRenderer](https://github.com/WestlyPark/StyleRenderer)
   - Tips:  构建了一种从输入3D模型到生成图像的平滑梯度，同时可以以低精度建模获得渲染更高质量的图像

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/BJbRvwibeSTuLGuha3GVxopibDV8UbvqWhIWFDlYtsCVfic7qsttBaaBJMb0caWumI6f1EBboB1Gsxz4iaQcqMRHZQ/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
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