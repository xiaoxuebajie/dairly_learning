# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.6.7

------

## :paperclip:  今日要点

1. [CVPR2022 | 重新审视池化：你的感受野不是最理想的](https://mp.weixin.qq.com/s/Ol4d3r5CudFrwmTp6HG-jw)         :star::star:
   - Abstract: 重新审视池化：你的感受野不是最理想的
   - Paper: [Pooling Revisited: Your Receptive Field is Suboptimal](https://arxiv.org/abs/2205.15254)
   - Tips:  本文提出了一种简单而有效的动态优化池操作（ Dynamically Optimized Pooling operation），称为DynOPool，它通过学习每一层感受野的最佳大小和形状来优化特征映射的端到端比例因子。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTW2KrmLQ8Wm2JCncZgibOc1UBFPos2l9SANu3eno4l8pepAW4xafiaK4FAe8yT1yqfr8jqgVw0deo9g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [即插即用 | 5行代码实现NAM注意力机制让ResNet、MobileNet轻松涨点(超越CBAM)](https://mp.weixin.qq.com/s/gK3LZd6iKdPDFE4EDqY3dA)       :star::star:
   - Abstract:  5行代码实现NAM注意力机制让ResNet、MobileNet轻松涨点(超越CBAM)
   - Paper: [NAM: Normalization-based Attention Module](https://arxiv.org/abs/2111.12419)
   - Code: [https://github.com/Christian-lyc/NAM](https://github.com/Christian-lyc/NAM)
   - Tips: 在这项工作中提出了一种新的基于规范化的注意力模块(NAM)，它抑制了较少显著性的权值。它对注意力模块应用一个权重稀疏惩罚，因此，在保持类似性能的同时，使它们更有效地计算。通过与ResNet和MobileNet上其他三种注意力机制的比较，表明本文的方法具有更高的准确性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tglXNC44WpNQrjPoE5gCAlOWwacYCt0vYdDv9uhVg5634ibcF2q3CRqvW05e2MbMMI3le0NL9Eoib8rQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tglXNC44WpNQrjPoE5gCAlOWu8ysRpIMQke5j5hTIsjlx3ml3XfHBBFQ2lRK3icEKEFd5cn82ibgSKbg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [ICPR 2022｜3DUNet：卷积+胶囊强强联手，医学图像分割的新良方](https://mp.weixin.qq.com/s/uV2RqIpQeqCzVsg4GP9pIw)       :star::star:
   - Abstract: 3DUNet：卷积+胶囊强强联手，医学图像分割的新良方
   - Paper: [3DConvCaps: 3DUnet with Convolutional Capsule Encoder for Medical Image Segmentation](https://arxiv.org/abs/2205.09299)
   - Tips: : 卷积神经网络（CNN）目前在医学图像分割领域应用广泛。本文基于胶囊网络，设计了一种包含卷积与胶囊编码器的3DUNet架构并应用于医学图像分割，在减少推理时间的同时性能远优于以往UNet类架构。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_png/gYUsOT36vfp8qOBAdTMgj1oplfVVSQ7vG7ZT9mo6f14QnibROdy4nvoibsEJmE2WA2Oib1VpjfChOQzTI5ooNeQkQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [SCI：快速、灵活与稳健的低光照图像增强方法（CVPR 2022 Oral）](https://mp.weixin.qq.com/s/1edHkevclvnDNoVNRPitTg)       :star::star:
   - Abstract: SCI：快速、灵活与稳健的低光照图像增强方法（CVPR 2022 Oral）
   - Paper: [Toward Fast, Flexible, and Robust Low-Light Image Enhancement](https://arxiv.org/pdf/2204.10137.pdf)
   - Code: [https://github.com/vis-opt-group/SCI](https://github.com/vis-opt-group/SCI)
   - Tips: 本文提出了一种全新的低光照图像增强方案：自校准光照学习（SCI）。通过构建引入自校准模块的权重共享光照学习过程，摒弃了网络结构的繁杂设计过程，实现了仅使用简单操作进行增强的目的。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTsX2ZVlvxRBmx3eQa4IteiaUaQW0iaPRve6AMjaMGEnaDbgmJibdTq9CwicOGnhkOnBknyQTvgichjJ4xA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [一个语义引导的轨迹预测半监督对抗训练方法](https://mp.weixin.qq.com/s/eFqFjLmABlOpKzMSTXyHtg)       :star::star:
   - Abstract: 一个语义引导的轨迹预测半监督对抗训练方法
   - Paper: [Semi-supervised Semantics-guided Adversarial Training for Trajectory Prediction](https://arxiv.org/abs/2205.14230)
   - Tips: 本文提出轨迹预测的对抗训练方法。具体来说是一种基于半监督对抗自动编码器（autoencoder）的方法，利用领域知识对分离的语义特征进行建模，并为对抗训练提供附加的潜标签。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwjz0mVvvViaoib1CzZ7caeQ9o7B8BqrE3iciaCqDt56BY5E8ef6VrIuRrO7LCiaMibUb4oRee3xnaoa5eyg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [StopNet：为城市自动驾驶的可扩展轨迹预测和占有预测方法](https://mp.weixin.qq.com/s/VGtFcRDLVcNDlCUbESSfFA)       :star::star:
   - Abstract: StopNet：为城市自动驾驶的可扩展轨迹预测和占有预测方法
   - Paper: [StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving](https://arxiv.org/abs/2206.00991)
   - Tips: 这项工作StopNet，是一种关注延迟和扩展性的运动预测方法。开发一种新的全场景（Whole-scene）稀疏输入表征，可以同时对包括所有智体的场景输入进行编码。借鉴3D目标检测，开发一个PointPillars启发的场景编码器，其同时处理从所有智体中采样的稀疏点，从而形成一个非常快速的轨迹预测模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwiaLj3aJXiassY4Vyr59PvvVtWOdv88aHAEwqA1ib5ulLyRQ320tS0oq814SrWfzby2B9icgj8Ysk5crA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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