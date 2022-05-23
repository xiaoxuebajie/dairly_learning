# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.23

------

## :paperclip:  今日要点

1. [CLCNet：用分类置信网络重新思考集成建模（附源代码下载）](https://mp.weixin.qq.com/s/_h_FYThsiuHcNvSkl5bj0A)         :star::star:
   - Abstract: CLCNet：用分类置信网络重新思考集成建模
   - Paper: [CLCNet: Rethinking of Ensemble Modeling with Classification Confidence Network](https://arxiv.org/pdf/2205.09612.pdf)
   - Tips: 分类置信网络（CLCNet）可以获取任意维度的向量形式的分类结果，并返回一个置信度分数作为输出，它代表了一个实例被正确分类的概率。这是一种新型的集成建模。与通用集成建模一样，它可以实现比单一分类模型更高的性能，但新的系统比通用集成建模需要更少的计算量。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwOM9W1Vzibrg9lXtw5xTV5CFkpgEKGjbBNDbPZYAibyaSkMUfHGkibve3H8NGCicEFDQmxxVkBgcElMDQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [CVPR 2022 | Vision Transformer模型在out-of-distribution数据上的泛化性能研究](https://mp.weixin.qq.com/s/WFqZKMKpCVGwl0QRlmDOKg)       :star::star:
   - Abstract: Vision Transformer模型在out-of-distribution数据上的泛化性能研究
   - Paper: [Delving Deep into the Generalization of Vision Transformers under Distribution Shifts](https://arxiv.org/abs/2106.07617)
   - Code: [https://github.com/Phoenix1153/ViT_OOD_generalization](https://github.com/Phoenix1153/ViT_OOD_generalization)
   - Tips: 通过将这三种泛化增强的ViT与它们对应的CNN模型进行综合比较，得到以下结论：对于泛化增强的ViT，模型结构越庞大，其对于OOD数据的泛化能力得到的增益更多；与相应的CNN模型相比，泛化增强的ViT对超参数更敏感。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV3HfvzcW2ANFKOAraEBdpHbqzBP4ghmeVZTWIm7fsn7TbxCmrG1uH1ichLjQFdhADPAQj6rXszc6Ig/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [HAT | 探究SwinIR优于RCAN的背后机理，挖掘预训练策略潜能！](https://mp.weixin.qq.com/s/4zIMR6QmJlkdPXy6rdyCZA)       :star::star:
   - Abstract: 探究SwinIR优于RCAN的背后机理，挖掘预训练策略潜能！
   - Paper: [Activating More Pixels in Image Super-Resolution Transformer](https://arxiv.org/abs/2205.04437)
   - Tips: 本文提出了一种新颖Hybrid Attention Transformer(HAT)方案，它同时利用了通道注意力与自注意力机制。此外，更好的进行跨窗口信息聚合，本文提出一种Overlapping Cross-Attention模块以增强相邻窗口之间的信息交互。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/ibaXaPIy7jV3HfvzcW2ANFKOAraEBdpHb5uxUzUzE04uQ7Hr7XVtm87a8jBY2LMnN15jInM7cqPPCEQwiclNeMag/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [8个token能学到什么？谷歌提出《TokenLearner》，用8个token就可以达到优于数百个token的结果！](https://mp.weixin.qq.com/s/tNYDQ0cqCSwCzq1GkZ62KQ)       :star::star:
   - Abstract: 谷歌提出《TokenLearner》，用8个token就可以达到优于数百个token的结果！
   - Code: [TokenLearner: What Can 8 Learned Tokens Do for Images and Videos?](https://arxiv.org/abs/2106.11297)
   - Code: [https://github.com/google-research/scenic/tree/main/scenic/projects/token_learner](https://github.com/google-research/scenic/tree/main/scenic/projects/token_learner)
   - Tips: 本文提出了一种新的视觉表征学习方法TokenLearner，它可以自适应地tokenize输入。目标是学习从图像和视频帧中提取重要的token，用于识别任务。与目前工作相比，本文的方法更为有效，因为作者发现了一些重要的时空token，可以对图像和视频的视觉表征进行建模。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTu62OxibZUKOxHytYdEOeFpUJ5wsp8UCh8Y7DYoUFj9UGndgwvuTWQiarrDV0W3NVcsYa3aicM2EFO6g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [多模态学习工具包PaddleMM](https://mp.weixin.qq.com/s/SREn-X0Jta9Rv83XgyyhcA)       :star::star:
   - Abstract: 多模态学习工具包PaddleMM
   - Code: [https://github.com/njustkmg/PaddleMM](https://github.com/njustkmg/PaddleMM)
   - Tips: 多模态学习工具包兼容PaddlePaddle平台和PyTorch平台，提供模态联合学习和跨模态学习算法模型库，为处理图片文本等多模态数据提供高效的解决方案，助力多模态学习应用落地。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/RKzhFqs0jAagTNviajSs4iaz8ea5PTkyHiavhaLL08vqF9lHibXKWH5ShP83FvkvqLnWVW4CqcWb8JqedDLeIc4sjw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [人工智能如何助力市政垃圾清洁？垃圾检测全流程方案详解](https://mp.weixin.qq.com/s/tsG7mpRtMuwbDEA35mGDXg)       :star::star:
   - Abstract: 人工智能如何助力市政垃圾清洁？垃圾检测全流程方案详解
   - Tips: 基于飞桨目标检测开发套件PaddleDetection提供了一套完整的智慧城市垃圾检测方案，通过在市政车辆上安装摄像头对路面垃圾检测并分析，实现对路面遗撒的垃圾进行监控，记录并通知环卫人员清理，大大提升了环卫人效。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/sKia1FKFiafgiaNjkBJnXia79AjBZypvNa2QicvJXKVic06g0RXOzXXpqwUHFExIiaDnl5lKz0odCsvX8GYPtqEHLDI6w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
<details><summary>4月</summary>
    1. <a href="notes/202204/0402.md" target="_blank">公众号内容拓展学习笔记（2022.4.2）</a>
    2. <a href="notes/202204/0414.md" target="_blank">公众号内容拓展学习笔记（2022.4.14）</a>
</details>
<details><summary>5月</summary>
    1. <a href="notes/202205/0505.md" target="_blank">公众号内容拓展学习笔记（2022.5.5）</a>
    2. <a href="notes/202205/0507.md" target="_blank">公众号内容拓展学习笔记（2022.5.7）</a>
    3. <a href="notes/202205/0509.md" target="_blank">公众号内容拓展学习笔记（2022.5.9）</a>
    4. <a href="notes/202205/0510.md" target="_blank">公众号内容拓展学习笔记（2022.5.10）</a>
    5. <a href="notes/202205/0511.md" target="_blank">公众号内容拓展学习笔记（2022.5.11）</a>
    6. <a href="notes/202205/0517.md" target="_blank">公众号内容拓展学习笔记（2022.5.17）</a>
    7. <a href="notes/202205/0518.md" target="_blank">公众号内容拓展学习笔记（2022.5.18）</a>
    8. <a href="notes/202205/0519.md" target="_blank">公众号内容拓展学习笔记（2022.5.19）</a>
    9. <a href="notes/202205/0520.md" target="_blank">公众号内容拓展学习笔记（2022.5.20）</a>
    10. <a href="notes/202205/0521.md" target="_blank">公众号内容拓展学习笔记（2022.5.21）</a>
    11. <a href="notes/202205/0522.md" target="_blank">公众号内容拓展学习笔记（2022.5.22）</a>
    12. <a href="notes/202205/0523.md" target="_blank">公众号内容拓展学习笔记（2022.5.23）</a>
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