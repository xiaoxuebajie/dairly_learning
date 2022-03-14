# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.3.14

------

## :paperclip:  今日要点

1. [PlaneTR：一种用于提取场景中3D平面特征的Transformer(ICCV 2021)](https://mp.weixin.qq.com/s/S9RXpE2HwYBkCz1TRr4nsw)         :star::star:
   - Abstract: PlaneTR：一种用于提取场景中3D平面特征的Transformer
   - Paper: [PlaneTR: Structure-Guided Transformers for 3D Plane Recovery](https://arxiv.org/abs/2107.13108)
   - Code: [https://github.com/IceTTTb/PlaneTR3D](https://github.com/IceTTTb/PlaneTR3D)
   - Tips:  利用线段作为标记化序列而不是密集图来指导学习具有几何结构的3D平面恢复。结合传统方法和基于学习的方法的思想，提出了一种联合利用上下文信息和几何结构进行3D平面恢复的框架。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/Q0FNTB1XHicz6HclzFscoxWCDPS2iaFD4iaRZPImBzxFlf9F1b4O7nsBQBfHHp8qgKmLiag6mLX8P180qhzHhFAEJw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [基于Yolov5 C++的超准确人脸检测&关键点识别](https://mp.weixin.qq.com/s/PGHELNv7Xn7HcA6bCRIP4A)       :star::star:
   - Abstract: 基于Yolov5 C++的超准确人脸检测&关键点识别
   - Paper: [YOLO5Face: Why Reinventing a Face Detector](https://arxiv.org/abs/2105.12931)
   - Code: [https://github.com/deepcam-cn/yolov5-face](https://github.com/deepcam-cn/yolov5-face)
   - Tips:  本文主要记录一下YOLO5Face C++工程相关的问题，并且简单介绍下如何使用 Lite.AI.ToolKit C++工具箱来跑直接YOLO5Face人脸检测(带关键点) , 这些案例包含了ONNXRuntime C++、MNN、TNN和NCNN版本。 

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrCf4tMJDXfGGtp9J4tI3ZZ6C2bcuV4HicSalMBWa45TiawSwMc4C5ZLW9NChcKG8rqGYHHiafCjxPuA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [PPCNN：细粒度特征提取和定位用于目标检测（附论文下载）](https://mp.weixin.qq.com/s/6kzoSHKJVSr9RAXpf-hs-w)       :star::star:
   - Abstract: PPCNN：细粒度特征提取和定位用于目标检测
   - Paper: [PPCNN: Object Detection using Fine-grained Feature Extraction and Localization](http://ki-it.com/xml/28058/28058.pdf)
   - Tips: 研究者提出了独特的网络架构，PPCNN（金字塔池化卷积神经网络），以减少定位误差，并提取高级特征图。该网络由改进的VGGNet和U-shape特征金字塔网络组成。介绍了一种提取和收集目标的小特征信息并从源图像中检测小物体的网络。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwP6icOmxiaZcbMZn7tfhibthrj8Jjibu4zoCcqC8fRBgLSx38fxK27spV0bd0FYpEvwOBLNOx0iavxiaVRA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



4. [AnchorFree算法-SAPD论文解析（附论文与源码）](https://mp.weixin.qq.com/s/toeel-JZ30dOAYN6UuN4KQ)       :star::star:
   - Abstract: AnchorFree算法-SAPD论文解析
   - Paper: [Soft Anchor-Point Object Detection](https://arxiv.org/pdf/1911.12448.pdf)
   - Code: [https://github.com/cherish24/SAPD](https://github.com/cherish24/SAPD)
   - Tips: 作者在FSAF的基础上进一步地分析了现有的两个问题：注意力偏差和特征选择问题。前一个问题通过对不同样本加权实现，后一个问题通过对不同分辨率加权实。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/mZ89VeqFiaqvxxGoicMFTvz3mnSUMiaef8EsfYawI80Pj68ltLcRojjRN4Z8cyh07BvyNgrwfN18JG7m5MK61xC9A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [CVPR 2022 | Restormer: 刷新多个low-level任务指标](https://mp.weixin.qq.com/s/tFIZF7sLzJ29jph0_EYyvg)       :star::star:
   - Abstract: Restormer: 刷新多个low-level任务指标
   - Paper: [Restormer: Efficient Transformer for High-Resolution Image Restoration](https://arXiv.org/abs/2111.09881)
   - Code: [https://github.com/swz30/Restormer](https://github.com/swz30/Restormer)
   - Tips: 本文是MPRNet与MIRNet的作者在图像复原领域的又一力作，也是Transformer技术在low-level领域的又一个SOTA。针对Transformer在高分辨率图像复原中存在的难点，提出了两种MDTA与GDFN两种改进，极大程度上缓解了计算量与GPU缓存占用问题。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfriciaRYsYPkeACLYeRVyN1NeVweNw2JAtnOw64MzM6mmtdDEvIZnib79picD07ew3sBb0vBHNXrszfag/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



6. [十个最常用深度学习图像/视频数据标注工具](https://mp.weixin.qq.com/s/LUwd3eJgbkNDK0SJs8EO_Q)       :star::star:
   - Abstract: 十个最常用深度学习图像/视频数据标注工具
   - Tips: 人工数据标注的好处是标注结果比较可靠，自动数据标注一般都需要二次复核，避免程序错误，外包数据标注很多时候会面临数据泄密与流失风险。人工数据标注特别是图像数据标注常用的标注工具从标注工具的软件属性上分类可以分为客户端与WEB端标注工具，推荐大家使用客户端标注工具或者离线的WEB端标注工具，在线的WEB端标注工具面临数据流失风险！请慎用！

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/urgCdYOG5QfqlaaVpnblKf48dlGx66Z2RCquaRQR5gK8PKfENzkicrJUUlRAOTZPeAL7AV9tkY6lxfQFicCiaLO3Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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