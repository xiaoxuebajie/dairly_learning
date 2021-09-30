# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.9.30

------



## :paperclip:  今日要点

1. [ICCV 2021 | ResRep：剪枝SOTA！用结构重参数化实现CNN无损压缩](https://mp.weixin.qq.com/s/88nRC3VttYBsuTZ5S49Iww)         :star::star:
   - Abstract: ResRep用结构重参数化实现CNN无损压缩
   - Paper: [ResRep: Lossless CNN Pruning via Decoupling Remembering and Forgetting](https://arxiv.org/abs/2007.03260)
   - Code: [https://github.com/DingXiaoH/ResRep](https://github.com/DingXiaoH/ResRep)
   - Tips:  将原CNN等价拆分成负责“记忆”（保持精度不降低）的部分和负责“遗忘”（去掉某些通道）的部分，前者进行“记忆训练”，后者进行“遗忘训练”。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV3lC5xFY2lIsWycerFiaXgEdt1HNr87KHnIUNMVzK6hVjTYCsIFUxkn6fFPsLKxarwxkziaP4trQ8Jw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [深入探究ConvNets vs. Transformers，哪种预训练模型的可迁移性更好？](https://mp.weixin.qq.com/s/lH4o_g319N4Xeq2hi5UQvg)       :star::star:
   - Abstract: 通过下游实验来验证ConvNets和Transformers哪个预训练模型的可迁移性更好
   - Paper: [ConvNets vs. Transformers: Whose Visual Representations are More Transferable?](https://arxiv.org/abs/2108.05305)
   - Tips: 综合表现Transformers更佳，传统的观点一般认为Transformer优于ConvNets的原因是在于其更加放松（relaxed）的inductive bias。通过系统的实验，我们认为使得Transformer的迁移性能优于ConvNets的另外一大原因是其在提供相近ImageNet预训练性能的情况下，具有更少的参数量，这有利于降低预训练模型在下游任务上过拟合的风险。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTue6LO8k8PoDcHCVkJibPFGnZN4bElk1KraUhax91cXH19Y6jtQoibmnOagL6WibKWrjecPSXCVhsInw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



3. [CVPR 2021 比CNN和Transformer更好的Backbone？伯克利&谷歌提出BoTNet，精度达84.7%](https://mp.weixin.qq.com/s/A40zE1CA_YwovI53eLGA1A)       :star::star:
   - Abstract: BoTNet比CNN和Transformer更好的Backbone
   - Paper: [Bottleneck Transformers for Visual Recognition](https://arxiv.org/abs/2101.11605)
   - Tips: 直接将ResNet C5中的3x3卷积替换成了Self-Attention，来提升模型的性能

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTt3F9VlTib8RB3o9sZhnxSECnbZEMZyOEmJfHZpclc0Iy3Rmu0ibmKst9vmQR6HcdGqzsXp5teevU2A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [语义分割综述](https://mp.weixin.qq.com/s/Tz7kT14S8ZkWZ-OgE2WO5g)       :star::star:
   - Abstract:  有关语义分割的文献综述
   - Tips: 比较经典的几篇文章，适合研究语义分割的同学好好看看。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTXGLrzSIq30EEb7tENQWaHn5l1pXWP1TYR8h1dZia1XWvPTKTKFaJexeT45L1cEG4KQR4LliapHdWyQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [高通人工智能应用创新大赛冠军方案解读](https://mp.weixin.qq.com/s/2efke2PymcqMstkw4httUA)       :star::star:
   - Abstract:高通人工智能应用创新大赛冠军方案解读
   - Tips: 解决方案更贴近工业应用，包括落地

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqkuEUVb8WJCRXZCY6HA6tu9eLm69ztjTstynjKFKWUqyPClaBxGic4aKoHFMZlw2AcPpLpsSrAm0A/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [AI全自动钓鱼，原神游戏沦陷！（硬核开源）](https://mp.weixin.qq.com/s/zA1jnCS6o1UNPum_FoUQlg)       :star::star:
   - Abstract:AI全自动钓鱼项目详解
   - Code: [https://github.com/7eu7d7/genshin_auto_fish](https://github.com/7eu7d7/genshin_auto_fish)
   - bilibili: [https://www.bilibili.com/read/cv13270965](https://www.bilibili.com/read/cv13270965)
   - Tips: YOLOX 用于鱼的定位和类型的识别以及鱼竿落点的定位,DQN 用于自适应控制钓鱼过程的点击，让力度落在最佳区域内

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/v1JN0W4OpXgShLltx9u3vsPxNRmvp29suzF38JQB1FbJccV4RQCT4C8dOgu6zWynAHITI18mTT55hVclZgVccg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1" style='zoom:100%'>
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