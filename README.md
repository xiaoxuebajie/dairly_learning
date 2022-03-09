# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.9

------

## :paperclip:  今日要点

1. [【YOLOP 解读】基于YOLO改进的全景驾驶感知网络，可同时处理三大视觉任务！](https://mp.weixin.qq.com/s/OsNsw9Sg_dd9ivx3-lqI7g)         :star::star:
   - Abstract: YOLOP基于YOLO改进的全景驾驶感知网络，可同时处理三大视觉任务！
   - Paper: [YOLOP: You Only Look Once for Panoptic Driving Perception](https://arxiv.org/abs/2108.11250)
   - Code: [https://github.com/hustvl/YOLOP](https://github.com/hustvl/YOLOP)
   - Tips:  我们提出了一个高效的多任务网络，可以共同处理自动驾驶中的三个关键任务：物体检测、可行驶区域分割和车道检测，以节省计算成本，减少推理时间以提高每项任务的性能。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/RszMGpUQZjeZpibn2NLuP2iaus5QgPZicOrAicNkuQOzEwUpibcopq0tDcQnR3pYrOa1odjMGicubrpHfE3ukuyLS7hQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2022 | 清华&字节提出FGD：针对目标检测的重点与全局知识蒸馏](https://mp.weixin.qq.com/s/yDkreTudC8JL2V2ETsADwQ)       :star::star:
   - Abstract: 清华&字节提出FGD：针对目标检测的重点与全局知识蒸馏
   - Paper: [Focal and Global Knowledge Distillation for Detectors](https://arxiv.org/abs/2111.11837)
   - Code: [https://github.com/yzd-v/FGD](https://github.com/yzd-v/FGD)
   - Tips:  FGD仅需要获取学生与教师的特征图，便可完成重点蒸馏损失与全局蒸馏损失的计算，可以很方便的应用到各种类型的检测器上。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oUkO5p0VgUZn2dPeicTt1FqMgG0RM2OWc7iaACwzr2DSVYjPITZdhoqp1C8TvycYTWlLtjOh1dOSPKQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR 2022 | 南大&腾出提出ST++: 半监督语义分割中更优的自训练范式](https://mp.weixin.qq.com/s/knSnlebdtEnmrkChGM_0CA)       :star::star:
   - Abstract: 南大&腾出提出ST++: 半监督语义分割中更优的自训练范式
   - Paper: [ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation](https://arxiv.org/abs/2106.05095)
   - Code: [https://github.com/LiheYoung/ST-PlusPlus](https://github.com/LiheYoung/ST-PlusPlus)
   - Tips: 本文提出了两个关键的改进策略，分别是在无标签图像上注入强数据增广和基于图像级别选择的渐进式重训练策略。结合了上述改进策略后，传统的self-traininig范式可以同时享有entropy minimization和consistency regularization的优点，并且可以取得优于最新的采用端到端训练的方法的结果。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oVwUuUxNaotZFFpxIVb2RibiaZIOzbNcox2pYic7K1Tmr8DNEzhYNIwfggUiakJ0nYfpgic4Bib5WIe410g/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [AAAI2022 | SITVOS: 探索transformer在VOS中的隐式目标表征和信息传播](https://mp.weixin.qq.com/s/LCDsqmmCcPHKPwMNoIpqNA)       :star::star:
   - Abstract: SITVOS: 探索transformer在VOS中的隐式目标表征和信息传播
   - Paper: [Siamese Network with Interactive Transformer for Video Object Segmentation](https://arxiv.org/abs/2112.13983)
   - Tips: 在这篇论文中，我们为SVOS任务构建了一个基于孪生网络的高效架构，并设计了交互式transformer来实现目标表征的隐式增强和目标信息传递，从而完成对整个视频序列指定目标的分割。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Mcdq8uia1WiadqH3UzzqWYCuZbzEbjcj8RXxGD5OdUXR7TzznphcoSaxIBkRmwlTwch6mLaqxa0sT2Sdhib5icHW8g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [CVPR 2022 | CNN自监督预训练新SOTA：上交、Mila、字节联合提出具有层级结构的图像表征自学习新框架](https://mp.weixin.qq.com/s/CUa4ZAccoXFLvy00QFYCWQ)       :star::star:
   - Abstract: CNN自监督预训练新SOTA：上交、Mila、字节联合提出具有层级结构的图像表征自学习新框架
   - Paper: [HCSC: Hierarchical Contrastive Selective Coding](https://arxiv.org/abs/2202.00455)
   - Code: [https://github.com/gyfastas/HCSC](https://github.com/gyfastas/HCSC)
   - Tips: 这一框架通过将图像表征进行层级聚类，构造具有层级结构的原型向量 (hierarhcical prototypes)，并通过这些原型向量选择更加符合语义结构的负样本进行对比学习，由此将层级化的语义信息融入到图像表征中。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicib656vCpnTtDwiaUHVicYQ3ibKicTrpp5ibpu0vysPfNKKugtia4TwJXXOZRjER5MQ86jqkB21PJPEokkA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [新突破！华为诺亚开源首个亿级中文多模态数据集-悟空！](https://mp.weixin.qq.com/s/5o94Ncx5lAw9i_HC0hntMQ)       :star::star:
   - Abstract: 华为诺亚开源首个亿级中文多模态数据集-悟空！
   - Paper: [Wukong: 100 Million Large-scale Chinese Cross-modal Pre-training Dataset and A Foundation Framework](https://arxiv.org/pdf/2202.06767.pdf)
   - Dataset: [](https://wukong-dataset.github.io/wukong-dataset/benchmark.html)
   - Tips: 除了发布大型中文跨模态数据集悟空以外，还进一步发布了一组使用不同架构（ResNet/ViT/SwinT）和不同方法（CLIP、FILIP 和 LiT）大型预训练模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/KmXPKA19gWibFK8ZbARmc5zE6YSWmm0UAZZVJNlia45t5xiaVLrRibXrhsVdrC7qxcGSNaTMCJpGnJia7aK3gWOeRIQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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