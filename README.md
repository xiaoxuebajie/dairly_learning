# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.2.26

------

## :paperclip:  今日要点

1. [成功检测远距离目标，将点云与RGB图像结合，谷歌&Waymo提出新算法：4D-Net](https://mp.weixin.qq.com/s/9F3Vhb8EqyhD8niojtUktw)         :star::star:
   - Abstract: 谷歌&Waymo提出新算法：4D-Net将点云与RGB图像结合成功检测远距离目标
   - Paper: [4D-Net for Learned Multi-Modal Alignment](https://openaccess.thecvf.com/content/ICCV2021/papers/Piergiovanni_4D-Net_for_Learned_Multi-Modal_Alignment_ICCV_2021_paper.pdf)
   - Tips:  4D-Net 的优点是，它既利用了 RGB 提供的高分辨率，可以准确地检测到图像上的目标，又利用了点云数据提供的精确深度。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/KmXPKA19gWibfVFFCvW8W7iahbnbGiaq4NeG2FUl0a9qhX26EwlTNDjKrj4pQyNeHc3D0B0Z7WFcNBaRoIAlK4kJQ/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>



2. [91.2%准确率！ViTAEv2：视觉Transformer新工作！更大模型、更多任务、更高效率](https://mp.weixin.qq.com/s/G7vcrqeSYoFrZkkqRmlTsQ)       :star::star:
   - Abstract: ViTAEv2：视觉Transformer新工作！更大模型、更多任务、更高效率
   - Paper: [ ViTAEv2: Vision Transformer Advanced by Exploring Inductive Bias for Image Recognition and Beyond](https://arxiv.org/abs/2202.10108)
   - Code: [https://github.com/Annbless/ViTAE](https://github.com/Annbless/ViTAE)
   - Tips: ViTAEv2说明了面对多种下游任务场景，归纳偏置对于提升Vision Transformer模型性能仍然效果显著。目前，主要探索了局部性和尺度不变性归纳偏置在Vision Transformer中的作用，未来还可以探索更多的归纳偏置的影响，如视角不变性等。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Mcdq8uia1WiadSibRZiakS9Qchh8eJTicFbmoKLB1B7ON42DoR3Ya3Gs2AVdnGLicwDrIuqRVWFnkcHk5BS1CG5nQkRw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [NeurIPS 2021 | 图像损坏场景下行人重识别新基准](https://mp.weixin.qq.com/s/K0jund_B61q8hsvAVWfhcQ)       :star::star:
   - Abstract: 图像损坏场景下行人重识别新基准CIL-ReID
   - Paper: [Benchmarks for Corruption Invariant Person Re-identification](https://arxiv.org/abs/2111.00880)
   - Code: [https://github.com/MinghuiChen43/CIL-ReID](https://github.com/MinghuiChen43/CIL-ReID)
   - Tips: 本文提出了一个全新的ReID任务场景，图片损坏场景下的行人重识别。针对21种ReID方法在5个数据集上进行了详尽的损坏鲁棒性评估，同时针对ReID中损坏鲁棒性提出了新的基线方法——CIL，并取得了SOTA的性能。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oWRBYjafstxcEhlrQbP5wiatb6HTxjZ9DzSdU8Nia9ExUXEh0aRXiaYklFUNhpwkYIwZzia3RguhyXv6w/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [半监督目标检测相关方法总结](https://mp.weixin.qq.com/s/lBWHHEpL8zI77X5TwViDnA)       :star::star:
   - Abstract: 半监督目标检测相关方法总结
   - Tips: 主要两个方向：一致性学习和伪标签。前者利用两个深度卷积神经网络学习同一张 unlabeled 图像不同扰动（比如水平翻转，不同的对比度，亮度等）之间的一致性，充分利用 unlabeled data的信息。后者利用在 labeled data 上学习的预训练模型对 unlabeled data 进行推理，经过 NMS 后减少大量冗余框后，利用一个阈值去挑选伪标签，最后利用伪标签训练模型。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfoeGuReemLtcNg9hSrtqhBk9tYZqxfmjjlvNLdw4BTnBmAMEGMXxaBqibNw6h0OMD5QsiaCS5ELv0Vg/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




5. [在Android上部署TF目标检测模型](https://mp.weixin.qq.com/s/eLraSFITgfywbT4I8E5y4w)       :star::star:
   - Abstract: 在Android上部署TF目标检测模型
   - Code: [https://github.com/victordibia/handtracking](https://github.com/victordibia/handtracking)
   - Tips: 通过手检测详细演示如何将TF部署到Android手机上。

<div align=center><img src="https://github.com/victordibia/handtracking/raw/master/images/doodle.gif" style='zoom:100%'>
</div>


6. [再不用怕Markdown中的绘图了，GitHub官方支持Mermaid图表绘制工具](https://mp.weixin.qq.com/s/eTKH_yDyX8Xou8y12Ekh6g)       :star::star:
   - Abstract: GitHub官方支持Mermaid图表绘制工具
   - Tips: 用户可以通过 GitHub 体验到一项原生功能 —— 支持基于 JavaScript 的 Mermaid 图表和流程图生成工具

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9uapy6kuaqGaTJpuV1aEMz0uLqYJRL9ueBUF1HfKwpDeLn2XwEIzj7xxBmgsFacpiaERN89AibSxlQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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