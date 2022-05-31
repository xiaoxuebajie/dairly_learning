# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.31

------

## :paperclip:  今日要点

1. [2022年人体姿态估计SOTA方案ViTPose论文解读](https://mp.weixin.qq.com/s/lKBK1jbz0rMJ4y5x3e8iaQ)         :star::star:
   - Abstract: 2022年人体姿态估计SOTA方案ViTPose论文解读
   - Paper: [ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation](https://arxiv.org/pdf/2204.12484v2.pdf)
   - Code: [https://github.com/ViTAE-Transformer/ViTPose](https://github.com/ViTAE-Transformer/ViTPose)
   - Tips: 本文实验了纯ViT用于人体姿态估计，在COCO数据集上取得了SOTA表现，同时验证了纯ViT所具有的诸多良好特性：结构简单、模型规模容易扩展、训练灵活、知识可迁移。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/bVTJ0talG6ooLicsZbhazLwQlibVSFyrpcoickqytsWzNbIOPosYcOtQfFDAXJMSk4TD1YXyvcKw2jkMicYwaYsadg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2022 | BoxeR：用于2D和3D Transformer的Box新注意力机制](https://mp.weixin.qq.com/s/yPg5ctZ5bd1ZE7UtoBuVEg)       :star::star:
   - Abstract: BoxeR：用于2D和3D Transformer的Box新注意力机制
   - Paper: [BoxeR: Box-Attention for 2D and 3D Transformers](https://arxiv.org/abs/2111.13087)
   - Code: [https://github.com/kienduynguyen/BoxeR](https://github.com/kienduynguyen/BoxeR)
   - Tips: 这篇文章主要基于 Deformable DETR 做了进一步拓展，Deformable DETR 是通过对原特征学出需要的注意的几个点以及其相应注意力权重，而本文提出，只注意一个 box 区域内的所有点。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oX2Fyj7kRLIkTMhE0PicWGuXbOib4APKbDxXiaFtjrmqia8otgkbM2JnGc1sBEZlAWd6zVGBbg77h7Siag/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [NAACL2022：（代码实践）好的视觉引导促进更好的特征提取，多模态命名实体识别（附源代码下载）](https://mp.weixin.qq.com/s/b1hLbQTVI7Ox6fyeYqWKOg)       :star::star:
   - Abstract: 好的视觉引导促进更好的特征提取，多模态命名实体识别
   - Paper: [Good Visual Guidance Makes A Better Extractor: Hierarchical Visual Prefix for Multimodal Entity and Relation Extraction](https://arxiv.org/pdf/2205.03521.pdf)
   - Code: [https://github.com/zjunlp/HVPNeT](https://github.com/zjunlp/HVPNeT)
   - Tips: 研究者提出了一种新颖的分层视觉前缀融合网络（HVPNeT），用于视觉增强实体和关系提取，旨在实现更有效和更强大的性能。具体来说，将视觉表示视为可插入的视觉前缀，以指导错误不敏感预测决策的文本表示。进一步提出了一种动态门控聚合策略，以实现分层多尺度视觉特征作为融合的视觉前缀。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNoNR85g66FeP2lIDQLIY4YqaOVMWIq4To151La9hNzHOflxMBak5EF59nsScKKhETGgGY70u9qJg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [BEVFusion: 基于统一BEV表征的多任务多传感器融合](https://mp.weixin.qq.com/s/_wwA9JyG4dBn25wRAIdKyw)       :star::star:
   - Abstract: BEVFusion: 基于统一BEV表征的多任务多传感器融合
   - Paper: [BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird’s-Eye View Representation](https://arxiv.org/abs/2205.13542)
   - Code: [https://github.com/mit-han-lab/bevfusion](https://github.com/mit-han-lab/bevfusion)
   - Tips: 本文提出的BEVFusion是一种多任务多传感器融合框架，其统一BEV表征空间中的多模态特征，很好地保留了几何和语义信息。为实现这一点，优化BEV池化，诊断并解除视图转换中的关键效率瓶颈，将延迟减少了40倍。BEVFusion从根本上来说是任务无关的，无缝支持不同的3D感知任务，几乎没有架构的更改。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/Q0FNTB1XHicwynyiamX3aEcbdMRxqwHZzKEkHnXG1fu9axB4X0MQY35Yfiah36dF19sMhqxAl0bIMMnF7OZnvBy3w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [RAL 2022｜基于3D语义共视图的语义SLAM精确回环检测](https://mp.weixin.qq.com/s/NfW2lec1m-ox9WU_cKCO-w)       :star::star:
   - Abstract: 基于3D语义共视图的语义SLAM精确回环检测
   - Paper: [Towards Accurate Loop Closure Detection in Semantic SLAM With 3D Semantic Covisibility Graphs](https://fujie.ece.ufl.edu/wp-content/uploads/sites/79/2022/02/SemanticSLAM-Covisibility-RAL2022.pdf)
   - Tips: 本文提出了一种新的基于单目视觉的语义SLAM系统中的循环检测和漂移校正方法，以充分利用high-level的语义信息和low-level的几何信息。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/O60Uib8kfuuicvDB5ukad7Rn6w0F1dPnlQY1T3Nt6C5dlFmdeBUGSib6zamSEaEjzTauN4ko8ibHXKafh6TOwILQjA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [如何轻松上手3D检测应用实战？飞桨产业实践范例全流程详解](https://mp.weixin.qq.com/s/cYFuHoxkTUm_0K3Tpa_FDg)       :star::star:
   - Abstract: 如何轻松上手3D检测应用实战？飞桨产业实践范例全流程详解
   - Code: [https://aistudio.baidu.com/aistudio/projectdetail/4038086](https://aistudio.baidu.com/aistudio/projectdetail/4038086)
   - Tips: 为了让大家能够更快速的应用前沿的技术，百度视觉技术部基于飞桨提供了一套完整的3D视觉检测产业实践范例，提供了从数据准备、模型训练及优化的全流程可复用方案，降低产业落地门槛。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/sKia1FKFiafgj7tbRHlkfIWE41ibnkMgWkFRlowvg7ytw910GsFPX3831FvwQms5bns2s9NgalKtkj5FNicprqm5Kw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    14. <a href="notes/202205/0525.md" target="_blank">公众号内容拓展学习笔记（2022.5.25）</a>
    15. <a href="notes/202205/0527.md" target="_blank">公众号内容拓展学习笔记（2022.5.27）</a>
    16. <a href="notes/202205/0528.md" target="_blank">公众号内容拓展学习笔记（2022.5.28）</a>
    17. <a href="notes/202205/0529.md" target="_blank">公众号内容拓展学习笔记（2022.5.29）</a>
    18. <a href="notes/202205/0530.md" target="_blank">公众号内容拓展学习笔记（2022.5.30）</a>
    19. <a href="notes/202205/0531.md" target="_blank">公众号内容拓展学习笔记（2022.5.31）</a>
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