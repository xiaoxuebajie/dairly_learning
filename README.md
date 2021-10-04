# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.10.4

------





## :paperclip:  今日要点

1. [ICCV2021 Oral SimROD：简单高效的数据增强！华为提出了一种简单的鲁棒目标检测自适应方法](https://mp.weixin.qq.com/s/ioX3DVMUpuKsKt6eyFTwEg)         :star::star:
   - Abstract: 简单有效的鲁棒目标检测无监督自适应方法SimROD
   - Paper: [SimROD: A Simple Adaptation Method for Robust Object Detection](https://arxiv.org/abs/2107.13389)
   - Code: [https://github.com/reactivetype/simrod](https://github.com/reactivetype/simrod)
   - Tips:  利用域混合数据增强和教师指导下的逐步自适应策略来减轻域转移的影响。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTvzEhsggGrJNm6s2uhPicOIiaUDkXnBmUwtfRib3rhAO1aRe1ZpibMxJ8dVPvsqgQC8zatJjc35H81VXA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [NeurIPS 2021 | 超越Swin！微软提出Focal Transformer：又一超强主干网络！](https://mp.weixin.qq.com/s/NOKMUS6JJOkJTb2SwTSA0w)       :star::star:
   - Abstract: 微软提出超强主干网络Focal Transformer
   - Paper: [Focal Self-attention for Local-Global Interactions in Vision Transformers](https://arxiv.org/abs/2107.00641)
   - Code: [https://github.com/microsoft/Focal-Transformer](https://github.com/microsoft/Focal-Transformer)
   - Tips: 本文提出了Focal Self-Attention，对当前token周围的区域进行细粒度的关注，对离当前token较远的区域进行粗粒度的关注，用这样的方式来更加有效的捕获局部和全局的注意力。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfoVQDtNKjHffB2f00poQEHn1rg8OGxFXEKckZJib0WE0k8mzRggVFWy4wu4cH5fl78cIhgn9qYia2mw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>




3. [ICCV 2021 | 2D和3D通用！港大提出PCRL：新医疗影像自监督SOTA！](https://mp.weixin.qq.com/s/7CwY_ngBvez2kAmW621rkw)       :star::star:
   - Abstract: 新的自监督方法PCRL，可以简单拓展到多个2D和3D医疗影像数据集上
   - Paper: [Preservational Learning Improves Self-supervised Medical Image Models by Reconstructing Diverse Contexts](https://arxiv.org/abs/2109.04379)
   - Code: [https://github.com/Luchixiang/PCRL](https://github.com/Luchixiang/PCRL)
   - Tips: 通过结合基于contrastive的方法和predictive的方法取得更好的自监督性能。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oWXs0TDrwSSlFHLd1cXdiaX3BtqsbnHxkpmeJQwBQqJQichP0R6LiarOxjKFA2lfHGurrclNlib6YP3Tg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [目标检测中边界框的回归策略](https://mp.weixin.qq.com/s/lC5iRYgOrmExaCoAAFvx7A)       :star::star:
   - Abstract:  目标检测中边界框的回归策略
   - Tips: 主要讲述：1.无Anchor的目标检测算法：YOLOv1，CenterNet，CornerNet的边框回归策略；2.有Anchor的目标检测算法：SSD，YOLOv2，Faster R-CNN的边框回归策略

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/gYUsOT36vfqkEd3rlEKAXRfVTLic5FBibIzrhsXXByxtER4ctLfjmxl4oO6k2PV9d3cjMyHR0SibNcZIe0xTuyQBA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



5. [用 Python 画不可思议的专业插图](https://mp.weixin.qq.com/s/KLOUvOneQdpCQT25tD89Eg)       :star::star:
   - Abstract: 用 Python 画不可思议的专业插图
   - Tips:  Python 的绘图模块 matplotlib

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqX4zPvOw25FCYQa4xKRztWIaObucA0zheJ3njzxwsiaQ6STP0L8g4UK7fZwWOEQA69Tm9PJc1voRw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [AI 模型部署概述](https://mp.weixin.qq.com/s/OIb5j3OHcgQKYB1l5qVGug)       :star::star:
   - Abstract: AI 模型部署概述
   - Tips: 本文介绍了部署的场景、部署方式（中心服务化还是本地终端部署）、模型的优化指标，以及如何提高吞吐率和减少延迟等

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/V2E1ll6kaTXbmJqRrnTwJaxZnhnY1zVODfvicm46WRvd7lB8KWtAaQV2H46pICw1NMjE4eGSh0c3kmibPEpCdBOA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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