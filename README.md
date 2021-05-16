# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.16

------



## :paperclip:  今日要点

1. [IJCAI 2021｜美团提出车道线检测新框架SGNet，精准且快速](https://mp.weixin.qq.com/s/1dwRw9u3mI9SGP-vqGHplQ)         :star::star:
   - Abstract: 美团提出车道线检测新框架SGNet
   - Paper: [Structure Guided Lane Detection](https://arxiv.org/pdf/2105.05403.pdf)
   - Tips:  实现了一种结构信息引导的车道线检测框架 SGNet，可以精准地描述车道线并对不确定条数的车道线进行分类与定位

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW96C0Ofhb81ibXQnKBuX4kziaqlPfDlDGzQaX4zwcotzOibZ6D2Reqgk0xQFbDpsdb7yicT9eSYsmt4Iw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [SlowFast Networks for Video Recognition](https://mp.weixin.qq.com/s/FnPTJ5o_qxu5BNZC2udP_A)       :star::star:
   - Abstract: 一种双流视频识别模型SlowFast网络
   - Paper: [SlowFast Networks for Video Recognition](https://arxiv.org/pdf/1812.03982.pdf)
   - Code: [https://github.com/facebookresearch/SlowFast](https://github.com/facebookresearch/SlowFast)
   - Tips: 将slow path和fast path在时间和空间维度对齐，之后可以在channel维度上concat，拼接之后的特征经过空间池化被输入到全连接层进行分类

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ldNS06W0w5uWgYNPwzR9T1Zz9EeiaS5qL8humJP3NMrnvvog5x9wkpMYdntW0UmkDVcUocAGmEbwCJ6SibkaWOTg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [更逼真的抠图技术！Realistic Lighting on Different Backgrounds](https://mp.weixin.qq.com/s/WAUvHV-oc4MstXouvU9NGA)       :star::star:
   - Abstract: 更逼真的抠图技术
   - Paper: [Total Relighting: Learning to Relight Portraits for Background Replacement](https://augmentedperception.github.io/total_relighting/total_relighting_paper.pdf)
   - Code: [https://github.com/augmentedperception/total_relighting](https://github.com/augmentedperception/total_relighting)
   - Tips: 目标是根据你添加的新背景的照明正确地重新照亮任何肖像

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/7jnsg27ZEVFYXCQ5Mic6rvc3zbrCnQ2EU30JQ47soFjq6u3aqwj7upIztAricUZIn36b8VGaRWWUQtkK2FUzHpVQ/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>

4. [CVPR2021 行人重识别/Person Re-identification 论文+开源代码汇总](https://mp.weixin.qq.com/s/cH1EfiJbj0Ikg34HB0VH_Q)       :star::star:
   - Abstract:  行人重识别/Person Re-identification 论文+开源代码汇总
   - Tips: 行人重识别（Person re-identification）也称行人再识别，是利用计算机视觉技术判断图像或者视频序列中是否存在特定行人的技术。广泛被认为是一个图像检索的子问题。给定一个监控行人图像，检索跨设备下的该行人图像

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/7jnsg27ZEVGgmz49vy0KbCxjZYS596lAdPzhc148GNuAfsclyOibLqQz9U5CTH9fHbQjIbYXNJBBe1ibBibJNfVZQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [基于运动相关分析的实时多源异构传感器时空标定方法研究](https://mp.weixin.qq.com/s/2Qb1TbaiBpM7HscmKNcAAA)       :star::star:
   - Abstract: 基于运动相关分析的实时多源异构传感器时空标定方法研究
   - Paper: [Real-Time Temporal and Rotational Calibration of Heterogeneous Sensors Using Motion Correlation Analysis](https://ieeexplore.ieee.org/document/9271875)
   - Tips: 一种异构多源传感器校准的中心IMU时间偏移和外部旋转参数的估计算法。该校准方法与优化方法具有相当的估计精度，具有更大的时间偏移估计范围和解析式的外部旋转参数。它可以实时的在没有标定板的自然场景中工作

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Q0FNTB1XHicxlwugTXy9Twic6dxoEJv6yLQKkJZdxE1vdI6e7ZibZxtCAvELibDs03xLrYPo8SjVhILnn65icg6Tu7Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [CVPR 2021 Inpainting专题](https://mp.weixin.qq.com/s/VSZqai9fptteGnrg_hb-yQ)       :star::star:
   - Abstract: CVPR 2021 Inpainting专题
   - Tips:  CVPR 2021的inpainting相关的文章进行了总结

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ldNS06W0w5uWgYNPwzR9T1Zz9EeiaS5qLzDjCByaVjrL4bbNrFTibj00klZEC3J36CsWbtAbjwVDiao0iam0gG19jA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


7. [增量学习(Incremental Learning)小综述](https://mp.weixin.qq.com/s/fWUrS05w35jr1dTqQZexJA)       :star::star:
   - Abstract: 增量学习(Incremental Learning)小综述
   - Tips: 尤其要注意增量学习和在线学习的区别，在线学习通常要求每个样本只能使用一次，且数据全都来自于同一个任务，而增量学习是多任务的，但它允许在进入下一个任务之前多次处理当前任务的数据

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/nJZZib3qIQW5Gnp7RLgCKs4Y2iaG6OqvTHpyNx8xp6XxA4OZ6ClYDOlRuV7BETJ0pUlTPabKGXYESzDO78wuKfyw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    14. <a href="notes/202105/05014.md" target="_blank">公众号内容拓展学习笔记（2021.5.14）</a>
    15. <a href="notes/202105/05015.md" target="_blank">公众号内容拓展学习笔记（2021.5.15）</a>
    16. <a href="notes/202105/05016.md" target="_blank">公众号内容拓展学习笔记（2021.5.16）</a>
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