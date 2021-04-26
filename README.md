# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.4.26

------



## :paperclip:  今日要点

1. [CVPR'21 | RMNet：又快又好！基于局部特征记忆网络的视频物体分割](https://mp.weixin.qq.com/s/w17mzD5KE-TnFJNIJ-3xXA)         :star::star:
   - Abstract: 基于局部特征记忆的视频分割网络RMNet
   - Paper: [Efficient Regional Memory Network for Video Object Segmentation](hhttps://arxiv.org/pdf/2103.12934.pdf)
   - Code: [https://github.com/hzxie/RMNet](https://github.com/hzxie/RMNet)
   - Tips: 本文主要是针对STM的全局匹配出现的误匹配问题，提出局部记忆网络来改善性能，可以和昨天阿里的LCM网络结合来看。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV17m7Dic4fkibia8HzoIEXtdLjHjfJNQwiblu1pbeOrPNpfuZADQxiaSbhHFP5OUdIaXvL6x696rKct1zg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [各类Transformer都得稍逊一筹，LV-ViT：探索多个用于提升ViT性能的高效Trick](https://mp.weixin.qq.com/s/iWT7Udg5ohu_n9TKQGlJ2g)       :star::star:
   - Abstract: 探索多个用于提升ViT性能的高效Trick
   - Paper: [Token Labeling: Training a 85.4% Top-1 Accuracy Vision Transformer with 56M Parameters on ImageNet](https://arxiv.org/abs/2104.10858)
   - Code: [https://github.com/zihangJiang/TokenLabeling](https://github.com/zihangJiang/TokenLabeling)
   - Tips: 与更改网络结构不同，这篇文章主要是通过更多的Trick来提升模型的性能，对于做视觉比赛来说，这篇文章受益良多。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfp9M4apDF6uJPKMkWfWIwbe7dTBSZomBlCUmnfqSSf0rsmdcwSh8CX7rOicaxETBl0GOWD3lu7LV9g/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [数据集 | 全新人脸微表情识别数据集——MMEW发布！](https://mp.weixin.qq.com/s/LPb7S0p1Z8KBdezOxVX4Qw)       :star::star:
   - Abstract: 一个新的数据集——微-宏表情仓库(MMEW)
   - Paper: [Video-based Facial Micro-Expression Analysis: A Survey of Datasets, Features and Algorithms](https://ieeexplore.ieee.org/document/9382112)
   - Dataset: [http://www.dpailab.com/database.html](http://www.dpailab.com/database.html)
   - Tips: 论文中也给出了现有最先进的微表情分析方法的性能，并指出未来研究的突出问题。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/uqJ8pmTvGgxZM5ugsxjmvTvfbr6foUZyxV4nI7oiaTNWLAa06BfbSOMa3AwHZaojHzKPb10zFggvpSlZlIicbIUg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [Transformer 的稳健性更好吗？](https://mp.weixin.qq.com/s/Iu3hKvXaUkchDI_ECxcf3Q)       :star::star:
   - Abstract: 讨论Tranformer和CNN相比的稳健性(对抗训练)
   - Paper1: [Understanding Robustness of Transformers for Image Classification](https://arxiv.org/abs/2103.14586)
   - Paper2: [On the Adversarial Robustness of Visual Transformers](https://arxiv.org/abs/2103.15670)
   - Tips：Transformer与CNN学习到的特征不同，而不一样的特征能取得相似的效果，可见Transformer确实是有别于CNN，且具有竞争力。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/nJZZib3qIQW43L6eGuic21TMn5RiaXgk5aUEf2BUh2oib4ZsrjQDTj1JGUlvaDRDnPv0yejFzrwr4FJmSjWzmo2sUg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [在目标检测中如何解决小目标的问题？](https://mp.weixin.qq.com/s/ZllNiZsGoNdpP0ez7238hQ)       :star::star:
   - Abstract: 一些小目标物体检测的方法和思路
   - Tips: 图像金字塔和多尺度滑动窗口检测  简单，粗暴和可靠的数据增强  特征融合FPN  合适的训练方法SNIP，SNIPER，SAN  更密集的Anchor采样和匹配策略S3FD， FaceBoxes

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KYSDTmOVZvrriadxibZDN0aNGhSaG6KB7GwbOM9T38XLVjk74iclJPOBA1nod2UUu9ktVkI4G41e7PcAke7WwXC7Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [盘点热门的目标检测开源方案(附论文+代码下载）](https://mp.weixin.qq.com/s/2t_y94u-lGgXjMYff0La1Q)       :star::star:
   - Abstract: 热门的目标检测开源方案
   - Tips: YOLOv4, DETR, EfficientDet, CenterNet2, DetectoRS

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SjQAYGc0mKFIgicbff4ia58fET6ncjWichicgBMDibFWgTspv7QPjKJqWsRwWPgAsNQibZZCLVMRotzackV0wDssnLOA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


7. [手把手教你用OpenCV做人脸口罩佩戴检测(附详细步骤+代码)](https://mp.weixin.qq.com/s/2t_UwsM4-qEF4rWSq1mAlw)       :star::star:
   - Abstract: 一个基于OpenCV的口罩佩戴检测系统项目
   - Tips: 实现步骤：
     - 使用OpenCV DNN网络检测人脸
     - 通过HSV阈值提取肤色
     - 通过肤色轮廓面积与人脸ROI面积比值判断是否佩戴口罩

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/rDAib0gF5OjbvlpjIM9WibpD5L4WpNRAnlH9DefHvxrxt3ZqSDDRCBOIu9ZZibichUJxhicea8sj3m1qItibxlg5afiag/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


8. [腾讯/字节/华为/旷视 2022届实习面经—计算机视觉方向](https://mp.weixin.qq.com/s/NAzCSIl7XKGgl4jxB8NpAA)       :star::star:
   - Abstract: 计算机视觉方向面经
   - Tips: 没事就看看，看看就看看



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