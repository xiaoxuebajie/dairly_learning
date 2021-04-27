# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.4.27

------



## :paperclip:  今日要点

1. [CVPR 2021 | 港大、牛津提出PAConv: 一种位置自适应卷积，点云分类、分割任务表现SOTA](https://mp.weixin.qq.com/s/t6zVLOM2OvqkVyFS6ZNyCg)         :star::star:
   - Abstract: 点云上具有动态内核组装的位置自适应卷积PAConv
   - Paper: [PAConv: Position Adaptive Convolution with Dynamic Kernel Assembling on Point Clouds](https://arxiv.org/abs/2103.14635)
   - Code: [https://github.com/CVMI-Lab/PAConv](https://github.com/CVMI-Lab/PAConv)
   - Tips: PAConv通过结合Weight Bank中的基本权重矩阵以及通过ScoreNet从点位置学习的相关系数来构造卷积核。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV21vCEBZjiaGwCPjQCqjbAxM7DOGlmIibl9y5x3TMibWH9NJvmoMUVTqFdDyQXFibGfHqqnmKePJ9J2Zw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2021 | 让机器想象未见的世界！反事实的零次和开集识别](https://mp.weixin.qq.com/s/-9K57blqFPBl5qY-7oEkXA)       :star::star:
   - Abstract: 反事实的零次和开集识别
   - Paper: [Counterfactual Zero-Shot and Open-Set Visual Recognition](https://arxiv.org/abs/2103.00887)
   - Code: [https://github.com/yue-zhongqi/gcm-cf](https://github.com/yue-zhongqi/gcm-cf)
   - Tips: 提出一个见过/未见过类别的二元分类器GCM-CF，二元分类后可以适用任何监督学习（在见过类别上）和零次学习算法（在未见过类别上）

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oXWpJQBgEu6qXJKwPAoyolSBlbCISGYkmpKA9SvGDjHsnLDp5aY7ejLtqkorFia0gJEGyhqFoKajjA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [从稀疏对应关系中学习光流运动 | CVPR 2021](https://mp.weixin.qq.com/s/M-tPbsBcRZtjJt98PK3q5g)       :star::star:
   - Abstract: 提出了一种新的计算光流的方法，从稀疏对应关系中学习光流运动。
   - Paper: [Learning Optical Flow from a Few Matches](https://arxiv.org/abs/2104.02166)
   - Code: [https://github.com/zacjiang/SCV](https://github.com/zacjiang/SCV)
   - Tips: 随着未来的图像或者视频的分辨率继续增加，为了让显存消耗保持在合适的范围内，sparse cost volume可能会被其他的工作所采用。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/cNFA8C0uVPsSo2vqnfot28IqKoAaPmicMh5LXzOe2OGJTjm7aJ5ibwfcWlEHV6W3RoxP7CsNClkf04kky6w2lmuA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [Meta-DETR | 图像级“元”学习提升目标检测精度](https://mp.weixin.qq.com/s/AeB7FazD3MPhLFzGxmMVhg)       :star::star:
   - Abstract: 新的元检测器框架，即Meta-DETR，实现区域预测，并以统一互补的方式在图像水平上学习目标位置和分类。
   - Paper: [Meta-DETR: Few-Shot Object Detection via Unified Image-Level Meta-Learning](https://arxiv.org/pdf/2103.11731.pdf)
   - Tips：首先将support和query图像编码为特定类别的特征，然后将它们输入到一个与类别无关的解码器中，以直接生成具体类的预测。为了促进深度网络的元学习，研究者设计了一个简单而有效的语义对齐机制(Semantic Alignment Mechanism，SAM)，它协调高级和低级特征语义，以改进元学习表示的泛化。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNOtHpkdw11EuBuWt1r122sybX82nneicHOYEHoHsEoViaicWXzQnicYqrbAcA8b1qAu4IkZvmibJ11icXw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [缺陷检测算法汇总（传统+深度学习方式）|综述、源码](https://mp.weixin.qq.com/s/-70_2uGgub4gckSV1Br5hQ)       :star::star:
   - Abstract: 机器视觉表面缺陷检测综述
   - Code: [https://github.com/Eatzhy/surface-defect-detection](https://github.com/Eatzhy/surface-defect-detection)
   - Tips: 缺陷检测算法综述和源码，非常全面，不同的应用领域，不同的解决方案以及部分数据集

6. [AIWIN-保险文本认知问答 直播分享](https://mp.weixin.qq.com/s/Bi8Sg15BOoPGl59cUVlJYw)       :star::star:
   - Abstract: AIWIN-保险文本认知问答 NLP比赛分享直播
   - Competition: [http://ailab.aiwin.org.cn](http://ailab.aiwin.org.cn)
   - Code: [https://github.com/datawhalechina/competition-baseline](https://github.com/datawhalechina/competition-baseline)
   - Tips: 利用了PaddleOCR，做NLP比赛的可以看看

7. [Docker镜像优化：从1.16GB到22.4MB](https://mp.weixin.qq.com/s/W_nmaxd7_QRoMQbX4MRnug)       :star::star:
   - Abstract: Docker镜像优化
   - Tips: 
     - 使用轻量化基础镜像
     - 多阶段构建

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/QFzRdz9libEYc88M2dfgq6XfpfxTpGL4lunqK1nMOYHvCEdq8GsCwud5AIBvlicj9CseIyQqUYvKwtZ21yUR0LbQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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