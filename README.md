# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.5.1

------



## :paperclip:  今日要点

1. [最强无监督行人重识别方法 Cluster Contrast ReID，精度超越有监督算法](https://mp.weixin.qq.com/s/c7NIGkVyYxiaUWioela8JA)         :star::star:
   - Abstract: 无监督行人重识别Cluster Contrast ReID，达到SOTA
   - Paper: [Cluster Contrast for Unsupervised Person Re-Identification](https://arxiv.org/abs/2103.11568)
   - Code: [https://github.com/alibaba/cluster-contrast-reid](https://github.com/alibaba/cluster-contrast-reid)
   - Tips: Cluster Contrast核心就是在人的维度上去进行特征的提取和更新，从而将特征的更新速度与图片数量进行解耦，让算法工程师能够在ID的层面对模型进行调优。

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfrpkibNH7ibrC8AthIaqbMQq7KDJ3kjGrBnXN3IU2Pzer29p6RBQIc6WqKuuQTGT2ldic6kLCEVahqiaA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [2位华人博士联手设计全景分割流水线，分辨率高达51.3%](https://mp.weixin.qq.com/s/CnXFE4WNCpIdJPN5-Jdm1A)       :star::star:
   - Abstract: 一种端到端的全景分割网络MaX-DeepLab
   - Paper: [MaX-DeepLab: End-to-End Panoptic Segmentation with Mask Transformers](https://arxiv.org/abs/2012.00759)
   - Tips: 端到端，结合了CNN与Transformer，缩小了box与box-free方法之间的差距，SOTA

<div align=center><img src="https://img-blog.csdnimg.cn/20210112143234543.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU3MjU5NQ==,size_16,color_FFFFFF,t_70#pic_center" style='zoom:100%'>
</div>

3. [陈丹琦组最新力作：仅需dropout两次的对比学习框架](https://mp.weixin.qq.com/s/0vK4pZXFEn28Dkxua5yN5Q)       :star::star:
   - Abstract: 前几天推的是SimCSE在中文的实验，今天讲的是对比学习SimCSE本尊
   - Paper: [SimCSE: Simple Contrastive Learning of Sentence Embeddings](https://arxiv.org/abs/2104.08821)
   - Code: [https://github.com/princeton-nlp/SimCSE](https://github.com/princeton-nlp/SimCSE)
   - Tips: 核心思想是缩短两个正样本之间的距离，拉大负样本之间的距离，从而得到输入更好的表示。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/VBcD02jFhgnr3T2SxCAZ3svkMDdJZQDumbZ54gZpfymUbhEgaUIQbMgnC8wcepYibrbOgxrFXibhNkrbEFA206pw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [Libra R-CNN：实现平衡学习的目标检测](https://mp.weixin.qq.com/s/SV8-0fprEbvtn59bkJpVtQ)       :star::star:
   - Abstract: 实现平衡学习的目标检测框架Libra R-CNN
   - Paper: [Libra R-CNN: Towards Balanced Learning for Object Detection](https://openaccess.thecvf.com/content_CVPR_2019/html/Pang_Libra_R-CNN_Towards_Balanced_Learning_for_Object_Detection_CVPR_2019_paper.html)
   - Tips: Libra R-CNN借助简单但有效的组件，即IoU平衡采样、平衡特征金字塔和平衡L1损失，实现了更准确的目标检测

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UZltaZktr9x32EvD2ka9uz0PgkXNjnD2Btu3X17cCyLXibocf7DkUZQg0dib9YAlEa2eOROzdyr8GpsaAcKCibRSw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [PFLD：高精度实时人脸关键点检测算法](https://mp.weixin.qq.com/s/dupmYSwX8tElT3Fmfi_ylg)       :star::star:
   - Abstract: 高精度实时人脸关键点检测算法PFLD
   - Paper: [PFLD: A Practical Facial Landmark Detector](https://github.com/DWCTOD/CVPR2021-Papers-with-Code-Demo)
   - Tips: backbone采用轻量级网络，自定义一个辅助网络获取旋转信息，设计了一个新的损失算法来解决几何正则化和数据不平衡问题

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/7jnsg27ZEVEUGGP2UNNMHQh0HeFPzS6Kf4dKRD3DpEwFziaQ7ZeAnD2QztMDT8ibEVFJp4L6KucKj4QLmk62LdTQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [用Python+OpenCV实现自动驾驶汽车的车道线检测](https://mp.weixin.qq.com/s/-DhcimloP9wU6st8Wd82lw)       :star::star:
   - Abstract: 使用Python+OpenCV实现自动驾驶汽车的车道线检测
   - Code: [https://github.com/pdhruv93/computer-vision/tree/main/lane-detection-self-driving](https://github.com/pdhruv93/computer-vision/tree/main/lane-detection-self-driving)
   - Tips: 基于OpenCV的车道线检测，思路清晰简洁，在深度学习的浪潮里，这种的小酌一下很嗨

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ABvEnMciauWtaXdibO9yLuS4qKx4iaDC0ubr8SJGSRqDQUGomds3EJw6PWXydUhqa2zfYlwr7AwETqwXosgMuia4fg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


7. [自动驾驶中的深度学习](https://mp.weixin.qq.com/s/PuDYR42JJyALxMU-Zs4wjQ)       :star::star:
   - Abstract: 在当前火热的自动驾驶中，用到了哪些深度学习技术
   - Tips: 
     - 在 感知（Perception） 中, 你发现周围的环境和障碍。
     - 在 定位（Localization） 中, 你在世界中确定了自己的位置，精度在 1-3 cm。
     - 在 规划（Planning） 中, 你利用感知和定位，确定了从 A 到 B 的轨迹。
     - 在 控制（Control） 中, 你产生方向盘转向角度和加速度值来沿着轨迹行进。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/8YTzYMibIWERSojpe6edicASvughUDMskSuZFSvUecNMianbcal1iajmibUTfvkiby3cCORL2Fg7wd2ltHw7Fu8vW81g/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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