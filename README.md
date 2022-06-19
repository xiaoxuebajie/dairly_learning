# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.6.19

------

## :paperclip:  今日要点

1. [改进Yolov5 | 用 GSConv+Slim Neck 一步步 Yolov5 再提升！！！](https://mp.weixin.qq.com/s/HkrCryQjtjWP1EfMPhxJwA)         :star::star:
   - Abstract: 用 GSConv+Slim Neck 一步步 Yolov5 再提升！！！
   - Paper: [Slim-neck by GSConv: A better design paradigm of detector architectures for autonomous vehicles](https://arxiv.org/abs/2206.02424)
   - Tips:  本文引入了一种新方法 `GSConv` 来减轻模型的复杂度并保持准确性。`GSConv` 可以更好地平衡模型的准确性和速度。并且，提供了一种设计范式，`Slim-Neck`，以实现检测器更高的计算成本效益。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgmHIibVGVL3oPI0sTD6iahwztJsKicmnLjfg7cOJVxfW6PmsAbAELUXHZibSbmd8Yic9tPpciaTHljeGMjQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [重振PointNet++雄风！PointNeXt：通过改进的模型训练和缩放策略重新审视PointNet++](https://mp.weixin.qq.com/s/p2ZFxUIHLfjSWrHy9nkzMQ)       :star::star:
   - Abstract:  PointNeXt：通过改进的模型训练和缩放策略重新审视PointNet++
   - Paper: [PointNeXt: Revisiting PointNet++ with Improved Training and Scaling Strategies](https://arxiv.org/abs/2206.0467)
   - Code: [https://github.com/guochengqian/pointnext](https://github.com/guochengqian/pointnext)
   - Tips: 在这项工作中首先提出了一组改进的训练策略，显著提高了 PointNet++ 的性能。其次将倒置残差瓶颈设计和可分离 MLP 引入 PointNet++，以实现高效且有效的模型缩放，并提出 PointNeXt，即下一版本的 PointNets。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oXt22exZ8eKVNCcgkLlt1vFRybDfvPicWCWrhLmVaySPPe9rGEMbzibPpBIUrv6MSFZibWyDloINjcYg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [腾讯Lab：用Transformer振兴CNN骨干网络（附论文源代码下载）](https://mp.weixin.qq.com/s/ZiNCywWKeLXyLClxVYkwkg)       :star::star:
   - Abstract: 腾讯Lab：用Transformer振兴CNN骨干网络（附论文源代码下载）
   - Paper: [Revitalizing CNN Attentions via Transformers in Self-Supervised Visual Representation Learning](https://arxiv.org/pdf/2110.05340.pdf)
   - Code: [https://github.com/ChongjianGE/CARE](https://github.com/ChongjianGE/CARE)
   - Tips: : 本文提出了一个利用 Transformer 结构来辅助 CNN 网络训练的视觉自监督表征学习框架。其核心贡献在于利用一种网络结构的特性（即 Transformer 的注意力提升特性），在训练中监督目标网络（即 CNN 骨干网络），从而使得网络特性能够得到迁移并提升目标网络性能的效果。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9NLDqanxM2JfzPQm4wLrF8CH4Jl63KyOhvAm6uc3eDbHhicoZTnuicHtEsjVkzn3iaicLU8PTB3X8XkQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [CVPR：IoU优化——在Anchor-Free中提升目标检测精度（附源码）](https://mp.weixin.qq.com/s/463ncxQVY-DCfKQRquh84w)       :star::star:
   - Abstract: IoU优化——在Anchor-Free中提升目标检测精度（附源码）
   - Paper: [Pseudo-IoU: Improving Label Assignment in Anchor-Free Object Detection](https://arxiv.org/abs/2104.14082)
   - Code: [https://github.com/SHI-Labs/Pseudo-IoU-for-Anchor-Free-Object-Detection](https://github.com/SHI-Labs/Pseudo-IoU-for-Anchor-Free-Object-Detection)
   - Tips: 研究者提出了伪IoU：一个简单的度量，带来更标准化和准确的分配规则到anchor-free目标检测框架没有任何额外的计算成本或额外的训练和测试参数，通过利用训练样本质量良好的有效分配规则使它可以进一步提高anchor-free目标检测，之前已经应用于基于anchor的方法。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwOofABsTcQEicBRMRaRlgKF5Ic4DwlmRP1a34Ahp8bafgml2so2qFCsiclcHZ0Eg0QEetDM0hsBGRDQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [详细解读TPH-YOLOv5 | 让目标检测任务中的小目标无处遁形](https://mp.weixin.qq.com/s/LQ_zVxgw8hymA6Yovcvl2g)       :star::star:
   - Abstract: 详细解读TPH-YOLOv5 | 让目标检测任务中的小目标无处遁形
   - Paper: [TPH-YOLOv5: Improved YOLOv5 Based on Transformer Prediction Head for Object Detection on Drone-captured Scenarios](https://arxiv.org/abs/2108.11539)
   - Tips: TPH-YOLOv5在YOLOv5的基础上增加了一个prediction heads 来检测不同尺度的目标。然后通过探索Self-Attention的预测潜力使用了Transformer Prediction Heads(TPH)代替原来的prediction heads。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tglHaia6B4F7D88cV76KsxdKvrg3BONjkzEsVibhFqmHlvMMh5oSWd53sQbwTYEkQ4dEd1jRbDbCyB9w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [新技术：高效的自监督视觉预训练，局部遮挡再也不用担心！](https://mp.weixin.qq.com/s/__48fY5hlH04weeYAnlJkw)       :star::star:
   - Abstract: 新技术：高效的自监督视觉预训练，局部遮挡再也不用担心！
   - Paper: [Efficient Self-supervised Vision Pretraining with Local Masked Reconstruction](https://arxiv.org/pdf/2206.00790.pdf)
   - Tips: 研究者提出了局部掩码重建(LoMaR)，这是一种简单而有效的方法，它在简单的Transformer编码器上的7×7补丁的小窗口内执行掩码重建，与全局相比，提高了效率和准确性之间的权衡对整个图像进行掩码重建。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNc8W1av8ykXno01F0He6jLfJpnh6CCI3XDcib2qewAZKNpian44WSedjAUXuicxAVSpwGiakhrZfKfgQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
<details><summary>6月</summary>
    1. <a href="notes/202206/0601.md" target="_blank">公众号内容拓展学习笔记（2022.6.1）</a>
    2. <a href="notes/202206/0607.md" target="_blank">公众号内容拓展学习笔记（2022.6.7）</a>
    3. <a href="notes/202206/0619.md" target="_blank">公众号内容拓展学习笔记（2022.6.19）</a>
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