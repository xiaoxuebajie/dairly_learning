# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.27

------

## :paperclip:  今日要点

1. [实时风格迁移，移动端运行，人脸特效又有了新玩法](https://mp.weixin.qq.com/s/fZEKZDd9D4lPbYHoRNDtfQ)         :star::star:
   - Abstract: 实时风格迁移，移动端运行，人脸特效又有了新玩法
   - Paper: [FaceBlit: Instant Real-time Example-based Style Transfer to Facial Videos](https://ondrejtexler.github.io/res/faceblit-paper.pdf)
   - Tips: 研究者提出了一种基于实例的实时视频人脸风格迁移框架 FaceBlit，该框架通过语义上有意义的方式保留了风格的纹理细节，也就是说，用于描绘特定风格特征的笔画出现在目标图像的适当位置。该框架不仅保留了目标对象（target subject）的身份，而且不需要大型数据集和冗长训练周期即可实现实时运行。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWicicHw8jEjFTy6JjeXKmI9GViaWGlW1WvMibAdxzDYPOCjtqawKw4XvcnbR8C7f4FiboJaewFpAVsrF6A/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>

2. [CVPR 2022 | 结合短期动态、长期一致性，视频伪装物体检测框架，大幅超越SOTA](https://mp.weixin.qq.com/s/ZbjKIJUnLC9LzJ4jfctksA)       :star::star:
   - Abstract: 结合短期动态、长期一致性，视频伪装物体检测框架
   - Paper: [Implicit Motion Handling for Video Camouflaged Object Detection](https://xueliancheng.github.io/SLT-Net-project)
   - Tips: 本文提出了 SLT-Net，一个用于解决 VCOD 任务的新模型。该模型利用短期动态与长期一致性信息，在视频中检测伪装物体。SLT-Net 是由 Transformer 与 CNN 组件组合而成的混合模型。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV0bjpzAegDKwS8icod5cK289ibOJURIcqloVPFbwvib02Esve722iasXhGZDjQwquBrHR8EXafZEiamDnw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [CVPR22 Oral｜图像质量和推理速度都要！字节提出轻量级高效图像超分辨率架构RLFN](https://mp.weixin.qq.com/s/MbQy_pTnLyHstyf_rJyFRg)       :star::star:
   - Abstract: 图像质量和推理速度都要！字节提出轻量级高效图像超分辨率架构RLFN
   - Paper: [Residual Local Feature Network for Efficient Super-Resolution](https://arxiv.org/abs/2205.07514)
   - Code: [https://github.com/fyan111/RLFN](https://github.com/fyan111/RLFN)
   - Tips: 本文针对单幅图像超分辨率（SISR）领域难部署于资源受限设备上的问题，提出一种轻量级的残差局部特征网络（RLFN），简单有效且在重建图像质量与推理速度之间取得良好权衡，同时本文采用多阶段热启动训练策略来提升模型性能。 

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrNvYeyIzOk34aibddDR58ZkQ46PFPKGyPSbWPzkHDkGAWxH2ib9aT0H0zansdTZNaaBG0Y4gMhGX0w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [超越Mixup的数据增强方法！RandomMix 集百家之长](https://mp.weixin.qq.com/s/bXBiGJXcPCln16KWgn4ROw)       :star::star:
   - Abstract: 超越Mixup的数据增强方法！RandomMix 集百家之长
   - Paper: [RandomMix: A mixed sample data augmentation method with multiple mixed modes](https://arxiv.org/abs/2205.08728)
   - Tips: `RandomMix`的主要目标是通过整合以前的工作来提高模型的鲁棒性并增加训练数据的多样性。此外，`RandomMix`可以实现更好的性能，并且可以很容易地插入到现有的训练管道中。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgkyKr7nnF1diaa4x47dKlemCr3RUJjZtMpquUYlPibGh0uibgbiaegIHbYiaGL7KM68XuTBk0nuYSF3v2A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [用Transformer思想的分类器进行小样本分割](https://mp.weixin.qq.com/s/YVg8aupmAxiu5lGTYrhpCg)       :star::star:
   - Abstract: 用Transformer思想的分类器进行小样本分割
   - Paper: [Simpler is Better: Few-shot Semantic Segmentation with Classifier Weight Transformer](https://arxiv.org/pdf/2108.03032.pdf)
   - Code: [https://github.com/lixiang007666/CWT-for-FSS](https://github.com/lixiang007666/CWT-for-FSS)
   - Tips: 作者介绍了一种新的元学习训练范式来解决小样本语义分割问题。相比于现有的方法，这种方法更加简洁有效，只对分类器进行元学习。重要的是，为了解决类内差异问题，提出 Classifier Weight Transformer 利用 Query 特征信息来迭代训练分类器，从而获得更加鲁棒和精准的分割效果。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SdQCib1UzF3txLSRgEed7o8OA9VLhohEk7icP09DNrtnwLwwE9Y6pFLnEmvcNgDCDkeFicGLMSvwR1icIo9UsUOibmQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [labelGo：基于 YOLOv5 的辅助标注工具](https://mp.weixin.qq.com/s/RalSgyNu6EcuomhsEaCzRQ)       :star::star:
   - Abstract: labelGo：基于 YOLOv5 的辅助标注工具
   - Code: [https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg](https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg)
   - Tips: 这是一个基于 labelImg与 YOLOv5 的半自动标注工具，通过现有的YOLOv5 PyTorch模型对数据集进行半自动标注。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/b6P5kstO2jbmxl69jqibDNV11p7cHlU879KJu7RlLBYpIrwr6ar8KRjU8DvjKqW6TlPdy1TW1dTPV96Hua6dJzA/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
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