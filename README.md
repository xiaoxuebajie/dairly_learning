# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.24

------

## :paperclip:  今日要点

1. [屠榜语义分割！ViT-Adapter：用于密集预测的视觉Transformer适配器](https://mp.weixin.qq.com/s/_nKUt6rExaac93GCBKVrlQ)         :star::star:
   - Abstract: ViT-Adapter：用于密集预测的视觉Transformer适配器
   - Paper: [Vision Transformer Adapter for Dense Predictions](https://arxiv.org/abs/2205.08534)
   - Code: [https://github.com/czczup/ViT-Adapter](https://github.com/czczup/ViT-Adapter)
   - Tips: `ViT-Adapter`中的`Backbone`是一个普通的`Transformer`，可以用多模态数据进行预训练。在对下游任务进行微调时，使用特定于模态的适配器将数据和任务的先验信息引入模型，使其适用于这些任务。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgldGOVfsLc65GwPSagzGEAWo6sZQ7c1A8skfIelSQzJwWyH2NHlImlG6YwSYrtwEASicRRWkvcgNkg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2022 | 关注文本阅读顺序，蚂蚁集团、上海交大提出多模态文档理解模型](https://mp.weixin.qq.com/s/hSfxgkabieLNpRgY-SbzYw)       :star::star:
   - Abstract: 关注文本阅读顺序，蚂蚁集团、上海交大提出多模态文档理解模型
   - Paper: [XYLayoutLM: Towards Layout-Aware Multimodal Networks For Visually-Rich Document Understanding](https://arxiv.org/abs/2203.06947)
   - Tips: 本文提出一个创新的 Augmented XY Cut 算法作为 augmentation 策略来对文本框进行排序生成合理的阅读顺序，从而改进模型性能；基于空洞卷积的思想，提出了可以处理变长输入序列的空洞条件位置编码 DCPE 生成模块。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gW9bTHG3kH8Qq0KibpxRAeC56Y4PBNLria1WNM1iaEicYJibk1MfXicX5Tdr1uAmJtBngXK5xo8jYwkIfaaQ/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


3. [ICLR 2022 TAdaConv：空间卷积也能进行时序推理，高效的视频理解模型TAdaConvNeXt出炉！](https://mp.weixin.qq.com/s/z6mbgFQvp_yX4ABycGj4Og)       :star::star:
   - Abstract: TAdaConv：空间卷积也能进行时序推理，高效的视频理解模型TAdaConvNeXt出炉！
   - Paper: [TADA! TEMPORALLY-ADAPTIVE CONVOLUTIONS FOR VIDEO UNDERSTANDING](https://arxiv.org/pdf/2110.06178.pdf)
   - Code: [https://github.com/alibaba-mmai-research/TAdaConv](https://github.com/alibaba-mmai-research/TAdaConv)
   - Tips: 本文作者提出时序自适应卷积（TAdaConv），自适应地对卷积核沿着时间维度进行调整，从而使空间卷积能够进行时序推理，在几乎没有额外计算量的情况下有效提升模型的时序推理能力。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTvNwqE03o5I178lF4gxoOm36xCe82xiaPIUBS3Bicg2MCh8wFgdKibasLHZzfyd9lqKhuow0SSaGle3Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [BEVerse：自动驾驶视觉为中心的BEV统一感知和预测框架](https://mp.weixin.qq.com/s/CJ9n0doq_nC74UR_hDUEzQ)       :star::star:
   - Abstract: BEVerse：自动驾驶视觉为中心的BEV统一感知和预测框架
   - Code: [BEVerse: Unified Perception and Prediction in Birds-Eye-View for Vision-Centric Autonomous Driving](https://arxiv.org/abs/2205.09743)
   - Code: [https://github.com/zhangyp15/BEVerse](https://github.com/zhangyp15/BEVerse)
   - Tips: 本文提出了基于多摄像机系统的3D感知和预测的统一框架**BEVerse**。与现有研究专注于改进单任务方法不同，BEVerse的特点是从多摄像头视频中生成BEV表征，并对多个任务进行联合推理，实现以视觉为中心的自动驾驶。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwhqxvs7AnVlhsJcuJhfuChuLBkWmI58Fen8eALLvTlmkkTlmzhxHtqWa2auxghcT0VwdxGhhXgRqA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [CVPR 2022 NTIRE 高动态范围成像（HDR）比赛冠军方案](https://mp.weixin.qq.com/s/5F2PzSdC88wtFwB8tpX8DQ)       :star::star:
   - Abstract: CVPR 2022 NTIRE 高动态范围成像（HDR）比赛冠军方案
   - Tips: 网易互娱 AI Lab 凭借以往对 low-level 视觉任务和轻量化网络设计的经验积累，在基线模型的基础上，提出了一个 Efficient HDR 网络，包括高效的多帧对齐和特征提取模块两个模块，同时优化了模型的训练方法。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWibNQxdlxh8C6cmSSUWI36dmH6L9lFBWy8WSvy5zX0kGZkAiaKVGPnhqXvhficaaWcNEEeN9Qrjcp84w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [“YoloV7”？目标检测算法终结篇：正式开源](https://mp.weixin.qq.com/s/GDPOUrnzjNSigMtzt1SLeQ)       :star::star:
   - Abstract: “YoloV7”？目标检测算法终结篇：正式开源
   - Code: [https://github.com/jinfagang/yolov7](https://github.com/jinfagang/yolov7)
   - Tips: 这里7只代表一种幸运代码，它的目的是让YOLO全面开花，不仅仅只是做目标检测。也不是简单的加一个semantic head做分割，而是做一个体系的目标检测积木模块，即插即用，使之能够更简单的做复杂的上层任务，比如多个分类head，实例分割，甚至是加上姿态检测等等。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwMiaU29NJ4icrtbY1oopN7upOwKm2tFLQm4gsh5GMbXNLyCYd3Yt5XzPNCuuOB4IWFcEocCu7HLwibeg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    13. <a href="notes/202205/0524.md" target="_blank">公众号内容拓展学习笔记（2022.5.24）</a>
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