# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.11

------



## :paperclip:  今日要点

1. [AI圈真魔幻！谷歌最新研究表明卷积在NLP预训练上竟优于Transformer？LeCun暧昧表态](https://mp.weixin.qq.com/s/w70mFSP-l-Zk95ZpEAo8qQ)         :star::star:
   - Abstract: 谷歌最新研究表明卷积在NLP预训练上竟优于Transformer
   - Paper: [Are Pre-trained Convolutions Better than Pre-trained Transformers?](https://arxiv.org/abs/2105.03322)
   - Tips:  通过对大量NLP任务的实验表明，在某些场景下，预训练卷积在模型质量和训练速度方面甚至优于预训练Transformers的SOTA性能

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/cNFA8C0uVPtUWFrCicwbEWgraqHTpGzd08WKHN6uiaReDa11OkNgTsFLUTPZ4ywBIl5M6hc9V8tCFacOtzl36mWw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [高光压制、清晰边界、任意场景，谷歌人像抠图新作！有了它，以后五一足不出户游世界](https://mp.weixin.qq.com/s/1QCSMHquZvYKTLypqPMzmQ)       :star::star:
   - Abstract: 高光压制、清晰边界、任意场景，谷歌人像抠图新作
   - Paper: [Total Relighting: Learning to Relight Portraits for Background Replacement](https://augmentedperception.github.io/total_relighting/total_relighting_paper.pdf)
   - Tips:  该研究的亮点和核心是通过前景蒙版（alpha matting）、重照明（relighting）和合成（compositing）进行前景估计。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWicdP2xibVicdHzGJDnTavYyWyKial6HICTPclaQrsokicoKgybaibCCksfPKgqYskACicabpUmqappic8K8w/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>

3. [半监督学习与PyTorch和SESEMI](https://mp.weixin.qq.com/s/jyDaJbyRFNTsdSfzSDBq8g)       :star::star:
   - Abstract: 半监督训练技术SESEMI
   - Code: [https://github.com/FlyreelAI/sesemi](https://github.com/FlyreelAI/sesemi)
   - Tips: 速度上手，效果显著，非常适合比赛中使用，感觉可以不再用手工Pseudo-lable了

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/6wQyVOrkRNLZKmOpzic5bQ7WxAQfpchkuFINPP3pS3V8n2VnL96goM8gBQuvniaeB6FkTNDDia961Gk0XY86Kl23g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [传统方法 + 深度学习发威！ | 2021瓷砖缺陷检测总决赛冠军思路分享](https://mp.weixin.qq.com/s/S8G91KWFf7q0A8oGEho_Qw)       :star::star:
   - Abstract: 2021瓷砖缺陷检测总决赛冠军思路分享
   - Tips: 核心就是把通过差分得到的特征在深层和浅层按通道进行拼接，和天池布匹比赛思路有点像，后续就是一个acc和map的balance的双阈值

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/7jnsg27ZEVGJ0Kzict56rEFquz9NvryvwBtGTJGjjdWPPffPMJibtiayn3eibhHiajbMVWkL52qgDiaWaBv5JFS4IRUw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [Attention九层塔：注意力机制的九重理解](https://mp.weixin.qq.com/s/2qLUKeuEBeH8fVAqwBtRyg)       :star::star:
   - Abstract: 效仿EM九层塔，提出Attention九层塔
   - Tips: 对Attention进行了梳理，万象归春，所有的模型都只是促进我们对数据的深入认知而已。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/J24zDnPUB9EW9OhXXF61nu1bNs02COZyOwno4Jh1CW4icr1Y8qMdDKqTkl27CpvtbEyia5LhsqgZMSlLTEy2hicGw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [SAHI：用于对大图像/小目标执行切片推理的视觉库](https://mp.weixin.qq.com/s/vdD8KTc8aLRYWKIQBX7YbA)       :star::star:
   - Abstract: 基于mmdetection用于对大图像/小目标执行切片推理的视觉库SAHI
   - Code: [https://github.com/obss/sahi](https://github.com/obss/sahi)
   - Tips:  视觉比赛中对于大图像中的小目标检测问题常用的策略就是切分infer，这里直接提供了一个库SAHI

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/SjQAYGc0mKGuJD1Rr7unBDszFBviaPsF9l8BbNmJoVUPJibiclicQxibHOPM76oEO1ODV4C5AMfNtd3CS3KNJaDkibWg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>

7. [Github标星4.8K！微软开源的可视化工具，未免太酷炫了吧](https://mp.weixin.qq.com/s/kL3hg0a-YsORwGiMBK6t2g)       :star::star:
   - Abstract: 微软开源的可视化工具SandDance
   - Code: [https://github.com/microsoft/SandDance](https://github.com/microsoft/SandDance)
   - Demo: [https://sanddance.js.org/app/](https://sanddance.js.org/app/)
   - Tips: 最近推荐了好几个可视化教程，这个也很秀

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KdayOo3PqHDakAgwPrTaMDSfCDCBIkIXtBnzjkOiaYib9PTyAyDheX5enUONkqhiaicpjSHudKKMz96SWicyMah3icxg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
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