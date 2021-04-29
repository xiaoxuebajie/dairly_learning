# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.4.28

------



## :paperclip:  今日要点

1. [丹琦女神的对比学习新SOTA，在中文表现如何？我们补充实验后，惊了！](https://mp.weixin.qq.com/s/P6oi6AgQzXiEF593y63zoA)         :star::star:
   - Abstract: SimCSE中文表现评测
   - Paper: [SimCSE: Simple Contrastive Learning of Sentence Embeddings](https://arxiv.org/abs/2104.08821)
   - Code: [https://github.com/bojone/SimCSE](https://github.com/bojone/SimCSE)
   - Tips: 本文分享了在SimCSE上的中文实验，结果表明不少任务上 SimCSE 确实相当优秀，能明显优于 BERT-whiteining 

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5fknb41ib9qF8ibOBKRwHnzqaCgLfAnpQa5LibErX1ibxrvEeW6HmVz3x3ibuUvrTypwaxhMbB2gS2aqKL1X8LmzGHQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [多模态预训练模型简述](https://mp.weixin.qq.com/s/1bnfuMJMj64WQjNovs_zSw)       :star::star:
   - Abstract: 多模态预训练模型简述
   - Tips: 目前多模态预训练领域相关方法，并总结了各个方法所设计的预训练任务及验证实验所使用的下游任务

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/58FUuNaBUjob2EkMWh0dfl0bY8icwqjVUBz8Twz01lbzUrwkd5qqUy0libRfosiazFmNqruXx0CAcUWYJQuVeLcpQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [面向智能视频监控的多目标检测与跟踪算法研究](https://mp.weixin.qq.com/s/0_kLkINBNUSmTMkD1S1DAQ)       :star::star:
   - Abstract: 面向智能视频监控的多目标检测与跟踪算法研究
   - Tips: 多目标跟踪最近比较主流的就是融合传统的目标跟踪和基于深度学习网络模型的跟踪算法

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KToRmsQB0NHo1iafBR8hPsI3NgFFEsg5rzt9fpl3sExRyco6G16eM6xToia5UyTjr0pTMN5ebIEMWoEyVjQSTzxg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [超越YOLOv5的PP-YOLOv2和1.3M超轻量PP-YOLO Tiny都来了！（附源码）](https://mp.weixin.qq.com/s/_1RHvwDv31GejbvLOgs7MQ)       :star::star:
   - Abstract: 高效的PP-YOLOv2和超轻量的PP-YOLO Tiny
   - Paper: [PP-YOLOv2: A Practical Object Detector](https://arxiv.org/abs/2104.10419)
   - Code: [https://github.com/paddlepaddle/paddledetection](https://github.com/paddlepaddle/paddledetection)
   - Tips: mAP 50.3%，106.5FPS 的 PP-YOLOv2，1.3M超轻量PPYOLO Tiny, 让目标检测界再起风波。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9aKt3mveTcP9clPkvYYiaQfmWBYsCR3ia8DQ3k5JT2uKhEicic9FHrhEO6T7tLXENLIyQguO1zKrukkA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [Google 内部的 Python 代码风格指南](https://mp.weixin.qq.com/s/lfeWdZCFeu2ua0uS7FWHRQ)       :star::star:
   - Abstract: Google 内部的 Python 代码风格指南
   - Code: [https://github.com/shendeguize/GooglePythonStyleGuideCN](https://github.com/shendeguize/GooglePythonStyleGuideCN)
   - Tips: Google Python代码风格指南，很全面。可以作为公司的code review 标准，也可以作为自己编写代码的风格指南

6. [C++ OpenCV实现图像去阴影](https://mp.weixin.qq.com/s/ejBBC_GFM27R-0-kQuHK0Q)       :star::star:
   - Abstract: 基于OpenCV的图像阴影去除
   - Code: [https://github.com/kavyamusty/Shading-removal-of-images](https://github.com/kavyamusty/Shading-removal-of-images)
   - Tips: 
     - 图将转为灰度图
     - 将灰度图进行膨胀操作
     - 膨胀后的图再进行腐蚀操作
     - 先膨胀后腐蚀后的图减去原灰度图再取反
     - 将取反后的图使用归一化将白色背景修改贴近原图

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1PGshybxVDS3kwrbibJvVicqmKfYS95vP2osTFPdsicRIdxdR37IS3d7rMD9m8zCvFZYhd6lm1fP6XUmcibtn9KrmA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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