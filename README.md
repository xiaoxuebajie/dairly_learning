# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.7

------

## :paperclip:  今日要点

1. [MUCNetV2：内存瓶颈和计算负载问题一举突破？分类&检测都有较高性能（附源代码下载）](https://mp.weixin.qq.com/s/0ORxzgOBK2EaICydw2WC2g)         :star::star:
   - Abstract: MUCNetV2：内存瓶颈和计算负载问题一举突破？分类&检测都有较高性能（附源代码下载）
   - Paper: [MCUNetV2: Memory-Efficient Patch-based Inference for Tiny Deep Learning](https://arxiv.org/pdf/2110.15352.pdf)
   - Code: [https://mcunet.mit.edu](https://mcunet.mit.edu)
   - Tips:  研究者提出一种patch-based inference机制打破初始层的内存瓶颈问题,极大程度上解决了TinyDL的内存瓶颈问题，为图像分类之外的其他视觉应用铺平了道路 。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwMrPYfnqvA52o0lj84mRMSmv6Ez4E4xFyybdvibggYra3tYWrhLDaJIPPTw2LXPqqASkoWIMSnpDhA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [一举打败16个同类模型，视频超分比赛冠军算法入选CVPR 2022，来自商汤&南洋理工大学](https://mp.weixin.qq.com/s/dowmz_mI7ZxNSCFjmKwibg)       :star::star:
   - Abstract: 来自商汤&南洋理工大学视频超分比赛冠军算法BasicVSR++
   - Paper: [BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment](https://arxiv.org/abs/2104.13371)
   - Code: [https://github.com/ckkelvinchan/RealBasicVSR](https://github.com/ckkelvinchan/RealBasicVSR)
   - Tips: 加强版的BasicVSR++在传播和对齐方面进行了重新改造，采用了二阶网格传播(second-order grid propagation) 和光流引导可变形对齐 (flow-guided deformable alignment)的设计来改善网络中的信息聚合能力，提升遮挡区域的鲁棒性和有效性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/YicUhk5aAGtCC7Xkc0OYK2GKZgNjRf6IiaIDhN1kvg40G3eSzxYJ0teVAlLxgft6NCibbzFYEBZMcKzVC301wpicdg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR 2022 | 即插即用！助力自监督涨点的ContrastiveCrop开源了！](https://mp.weixin.qq.com/s/VTP9D5f7KG9vg30U9kVI2A)       :star::star:
   - Abstract: 即插即用！助力自监督涨点的ContrastiveCrop开源了！
   - Paper: [Crafting Better Contrastive Views for Siamese Representation Learning](https://arxiv.org/abs/2202.03278)
   - Code: [https://github.com/xyupeng/ContrastiveCrop](https://github.com/xyupeng/ContrastiveCrop)
   - Tips: ContrastiveCrop旨在确保大部分正样本对语义一致的前提下，加大样本之间的差异性，从而通过最小化对比损失学习到更泛化的特征。ContrastiveCrop完全即插即用，且理论上适用于任何孪生网络架构。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oXhCL15yhpoXRnPzYOnIgVqM7HAtmBETewLAHvFt0ktwSxDhlR4Yy5q4LhbdjNOSM0Y1qLDT49fFw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [女娲算法，杀疯了！](https://mp.weixin.qq.com/s/v_hB5BGuzRTBqQfrHb4OlA)       :star::star:
   - Abstract: 多模态算法NÜWA（女娲）
   - Paper: [NÜWA: Visual Synthesis Pre-training for Neural visUal World creAtion](https://arxiv.org/abs/2111.12417)
   - Code: [https://github.com/microsoft/NUWA](https://github.com/microsoft/NUWA)
   - Tips: NÜWA模型的整体架构包含一个支持多种条件的 adaptive 编码器和一个预训练的解码器，能够同时使图像和视频的信息。对于图像补全、视频预测、图像处理和视频处理任务，将输入的部分图像或视频直接送入解码器即可。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/v1JN0W4OpXjKxdrh3FDZeCbe2ZnbF12X9hhAPVWLgJbxfDsQYibLiaeX0IQeWeAicR34iac4bib8JWlf5Q8Gqo9EichQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [ICRA 2022 | 基于多模态变分自编码器的任意时刻三维物体重建](https://mp.weixin.qq.com/s/5U4GN76q7uR-mHN79fKFkw)       :star::star:
   - Abstract: 基于多模态变分自编码器的任意时刻三维物体重建
   - Paper: [Anytime3D Object Reconstruction Using Multi-Modal Variational Autoencoder](https://arxiv.org/abs/2101.10391)
   - Tips: 为了实现类别级的插补和完整的三维形状重建，研究人员利用了潜在空间的多模态先验分布思想。与普通VAE不同，该方法中的每个模态都是在训练时自动确定的，并且包含特定类别的信息。利用这种先验分布，研究人员仅利用潜在空间中的传输元素来确定潜在变量的模式。通过从所选模型中输入采样变量，研究人员可以稳健地实现潜在向量检索和三维形状重建。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Q0FNTB1XHiczXF0P0oEzB6XCMib6yz4MOiaDTICm6icOxhj17uTIUp4dfpoCObIR6TaK0qmT3XL2KcZ2vNeswTaB1A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [基于大尺寸图像的小目标检测竞赛经验总结](https://mp.weixin.qq.com/s/qbbd5FdyKKk7UI3mmGBt4Q)       :star::star:
   - Abstract: 基于大尺寸图像的小目标检测竞赛经验总结
   - Tips: 本文为作者参加目标检测比赛总结的数据分析，比赛思路、模型、Tricks以及分享的一些相关资料。附有详细的模型总结以及anchor的设置总结图。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrqgczsQvHuFU02XwN3KL28ichBLll8Ku0bfC59fFlDBmFbPSBv488kaEWicBLDLeHbd4UJOu0ZshPw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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