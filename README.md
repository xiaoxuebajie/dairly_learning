# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.12

------

## :paperclip:  今日要点

1. [DINO：目标检测benchmark COCO屠榜的正确姿势](https://mp.weixin.qq.com/s/gX_YEEpBlbEPBL0mTNrFGg)         :star::star:
   - Abstract: DINO：目标检测benchmark COCO屠榜的正确姿势
   - Paper: [DINO: DETR with Improved DeNoising Anchor Boxes for End-to-End Object Detection](https://arxiv.org/abs/2203.03605)
   - Code: [https://github.com/IDEACVR/DINO](https://github.com/IDEACVR/DINO)
   - Tips:  DINO改善了one-to-one匹配问题，训练的时候正样本和负样本同时加了噪声，提出mixed query selection method，有助于改善queries的初始化，引入非临近层的特征，更像是增加感受一下，提高小目标的表达能力。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfot2j3EflmEpbeLhx2Lb3pYhjrXqGPJZZmlTNI87ZHvDn61msTIv2wp26F13QC5GoNERypFEic0nxg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [难度炸裂！DeepChange：一个新的超大规模的换衣行人再识别数据集](https://mp.weixin.qq.com/s/3ZgXvRsQrdMBSn23-z2mJQ)       :star::star:
   - Abstract: DeepChange：一个新的超大规模的换衣行人再识别数据集
   - Paper: [DeepChange: A Large Long-Term Person Re-Identification Benchmark with Clothes Change](https://arxiv.org/abs/2105.14685)
   - Code: [https://github.com/PengBoXiangShang/deepchange](https://github.com/PengBoXiangShang/deepchange)
   - Tips:  17个监控摄像头（多种分辨率），1121个person ID，17万余个bbox，时间覆盖12个月，这几项主要指标，均是目前该领域数据集中的最大值。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTviaRCkhrZDOSQiaI5fDuPcibfzn1v3Pc1UibgjVUXFopic3sxUBGYvvCdPzL5HMhh3lS0x5qKU5HBxTicw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [人脸随意编辑！Adobe祭出新一代GAN神器：最多支持35个人脸属性变化](https://mp.weixin.qq.com/s/jYWGF2k8uWKZVUkT-wDB6g)       :star::star:
   - Abstract: Adobe祭出新一代GAN神器：最多支持35个人脸属性变化
   - Paper: [Latent to Latent: A Learned Mapper for Identity Preserving Editing of Multiple Face Attributes in StyleGAN-generated Images](https://openaccess.thecvf.com/content/WACV2022/papers/Khodadadeh_Latent_to_Latent_A_Learned_Mapper_for_Identity_Preserving_Editing_WACV_2022_paper.pdf)
   - Tips: 用GAN模型进行图像合成有一个显著缺点，就是生成的图像不可控制，经常是摘个眼睛把性别都变了。最近Adobe提出新一代GAN模型，能够自由控制35个人脸属性的变化，而不会互相干扰。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb31cG3UkPQq4n9NUubY9ZISl0HVbbQKxibz6kpSZz1zfsIVzbU2LqZfSb4Mdsp4uiaK7pqR7PnzMD5Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [CVPR 2022 | 高分论文！港科大/IDEA/清华提出DN-DETR: 加速DETR收敛的去噪训练](https://mp.weixin.qq.com/s/xdMfZ_L628Ru1d1iaMny0w)       :star::star:
   - Abstract: 港科大/IDEA/清华提出DN-DETR: 加速DETR收敛的去噪训练
   - Paper: [DN-DETR: Accelerate DETR Training by Introducing Query DeNoising](https://arxiv.org/abs/2203.01305)
   - Address: [https://github.com/FengLi-ust/DN-DETR](https://github.com/FengLi-ust/DN-DETR)
   - Tips: 第一次提出了全新的去噪训练(DeNoising training)解决DETR decoder二分图匹配 （bipartite graph matching）不稳定的问题，可以让模型收敛速度翻倍，并对检测结果带来显著提升

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oXyfKwzFmDkr2qwZOftNFTM87nj0PNAzFUCDya1vWORPzzHNps0PYtXm9RLlqrzaQ7b1U08nuVhIw/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [ECCV 2020 Oral | 可逆图像缩放：完美恢复降采样后的高清图片](https://mp.weixin.qq.com/s/YWbJUco2PBy5kA3d6IZ_Bw)       :star::star:
   - Abstract: 可逆图像缩放：完美恢复降采样后的高清图片
   - Paper: [Invertible Image Rescaling](https://arxiv.org/pdf/2005.05650.pdf)
   - Code: [https://github.com/pkuxmq/Invertible-Image-Rescaling](https://github.com/pkuxmq/Invertible-Image-Rescaling)
   - Tips: 本文使用可逆神经网络对解决这一对逆任务进行了初步的尝试，沿着这条思路仍有很多值得发掘的点。同时，信息丢失(Information Loss)所导致的ill-posed问题在现实中也大量存在，本文提供的对Lost Information进行建模的视角，相信可以对类似任务有一定的参考价值。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/cNFA8C0uVPsBOQBLj8MChIxGicfWeo1Pib385zBXywjvKDYBSU6QuIVxwV9NPkjcia9UFf3zyXazmBByu7XCw5MOA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [超级干货 | 用万字文章总结25种正则化方法](https://mp.weixin.qq.com/s/adPMorv80Gx3LrpuyxU2jQ)       :star::star:
   - Abstract: 用万字文章总结25种正则化方法
   - Paper: [Avoiding Overfitting: A Survey on Regularization Methods for Convolutional Neural Networks](https://arxiv.org/abs/2201.03299v1)
   - Tips: 训练中的一个关键因素是网络的正则化，它可以防止模型在训练的过程中出现过拟合的现象。本文分析了过去几年发展起来的几种正则化方法，显示了不同CNN模型的显著改进。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfpqGQBBp2Dibm5CuMZC4Z1JKic0vsiaDg4oSl9fTzGzDx4e3xpvwB9SyznaqwVVnefo6NTnXISF2u1eg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    10. <a href="notes/202203/0310.md" target="_blank">公众号内容拓展学习笔记（2022.3.10）</a>
    11. <a href="notes/202203/0311.md" target="_blank">公众号内容拓展学习笔记（2022.3.11）</a>
    12. <a href="notes/202203/0312.md" target="_blank">公众号内容拓展学习笔记（2022.3.12）</a>
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