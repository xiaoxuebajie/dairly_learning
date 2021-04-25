# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.4.24

------



## :paperclip:  今日要点

1. [CVPR 2021 | 阿里达摩院提出半监督视频目标分割新算法，实现SOTA性能](https://mp.weixin.qq.com/s/1WvgpS4L7qcUB5J2we-QkA)         :star::star:
   - Abstract：视频目标分割方法 LCM，获得了 DAVIS 2020 半监督视频目标分割比赛的冠军
   - Paper: [Learning Position and Target Consistency for Memory-based Video Object Segmentation](https://arxiv.org/pdf/2104.04329.pdf)
   - Tips: 考虑STM分割中存在的问题，通过位置一致性和目标一致性两个方面着手，模型主要包括GRM、PGM、ORM三个模块，后两个尤为重要

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9Ht7yBKMF2v3uTltvnvdRZMuN7SJbRv3PnLhJFUcYeBlNibqTY5CuqFSA8p6aAfGjeE5eIlC59GvQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [CVPR 2021 | 港理工&达摩院提出LPTN：拉普拉斯金字塔变换网络](https://mp.weixin.qq.com/s/TgTwXUZjnHAdt-PMKBRU9w)       :star::star:
   - Abstract：LPTN网络将拉普拉斯金字塔与深度学习进行结合，完成I2IT任务
   - Paper: [High-Resolution Photorealistic Image Translation in Real-Time: A Laplacian Pyramid Translation Network](https://www4.comp.polyu.edu.hk/~cslzhang/paper/LPTN-cvpr21-paper.pdf)
   - Code：[https://github.com/csjliang/LPTN](https://github.com/csjliang/LPTN)
   - Tips：首个可以实时进行4K分辨率图像变换的方案

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/VvkhdVVVIDjrnvYic3JVngWxWKicmhzTmhUQq5ebqTdxdqpDwlmUYbfwEcGibXYRQxRVEKG9smXIEDOo9ehRuKR2Q/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [复旦提出M2TR：首个多模态多尺度Transformer](https://mp.weixin.qq.com/s/luSTifAqIum-dDxFX6CAIQ)       :star::star:
   - Abstract：首个多模态多尺度Transformer，应用于Deepfake Detection任务

- Paper: [M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection](https://arxiv.org/abs/2104.09770)
  - Tips: 融合了频域信息进行多模态融合，transformer中不同head取不同patch size实现多尺度，并且自制了一个Deepface数据集SR-DF，代码后续给出

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/yNnalkXE7oUfelRSOyhTiaague8o5ibePw1ibCL9RQumEd2ib2lPk1F5SZU5PMe42cSuUUmyZ424fmicvRUX5nrnjVQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [【CVPR 2021】通过GAN解决人脸识别的遗留难题](https://mp.weixin.qq.com/s/pee0M9VhTouZBtSXHwDFXA)       :star::star:
   - Abstract：两篇文章分别解决较大的姿态变化和年龄对人脸识别的影响
   - Paper1: [A 3D GAN for Improved Large-pose Facial Recognition](https://arxiv.org/abs/2012.10545v1)
   - Paper2: [When Age-Invariant Face Recognition Meets Face Age Synthesis: A Multi-Task Learning Framework](https://arxiv.org/abs/2103.01520)
   - code2: [https://github.com/Hzzone/MTLFace](https://github.com/Hzzone/MTLFace)
   - Tips：第一篇主要是采用3D可变形模型，将其合并到GAN的生成器中，并在不影响个人身份辨识度的情况下操纵姿势、照明和表情，第二篇通过注意力机制将混合的人脸特征分解为两个不相关的部分（身份和年龄相关的特征），然后使用多任务训练和连续域自适应将这两个部分的相关性进行解耦。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/LqxDjuCZT3icO5VAnYRCFRhTbdxjVzSib7IGia1MHiaSpPVrl5uHa7jUWYUr1kWansbNz9EnfYGYqiaeQbQicP4Y50AQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/LqxDjuCZT3icO5VAnYRCFRhTbdxjVzSib7fms77XiceFSDc4vemm0hl9pFm5FcQ0c19SKqyoY0el1cyubVU42mdrw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [人脸识别精度提升 | 基于Transformer的人脸识别（附源码）](https://mp.weixin.qq.com/s/09GTmVQ095SL83GWBV6PiA)       :star::star:
   - Abstract: 基于Transformer的人脸识别
   - paper: [Face Transformer for Recognition](https://arxiv.org/pdf/2103.14803.pdf)
   - code: [https://github.com/zhongyy/Face-Transformer](https://github.com/zhongyy/Face-Transformer)

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1MtnAxmWSwNx4PD9TQZ6SNx8q1LeQ2viacxicnR3CxSK87u0yELLY9uNzOE86KJHTujCZB4rhBnicYm9EdnXZEL5g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [Hugging Face发布PyTorch新库「Accelerate」：适用于多GPU、TPU、混合精度训练](https://mp.weixin.qq.com/s/-AjNv3E7NUkGGIruAm_SvQ)       :star::star:
   - Abstract: PyTorch新库「Accelerate」：适用于多GPU、TPU、混合精度训练
   - code: [https://github.com/huggingface/accelerate](https://github.com/huggingface/accelerate)

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9Ht7yBKMF2v3uTltvnvdRZO72t0HyFLjjfIbWCWEAD6HTu5sRFYVzpsLmUsAMAKQNQTsTHISMYjg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


7. [检测三维物体？一篇文章认识《双目立体视觉》](https://mp.weixin.qq.com/s/Fj1Ef7B7S9XkADXkX5xBDQ)       :star::star:
   - Abstract: 双目立体视觉检测三维物体
   - Tips: 完整pipeline，非常适合小白入门和对相关知识的梳理

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/rer5tGejndib3Ar9PuXeVnOBbuJVKndnnqf6TicCEauDfw7ibQVQQOgPkCw2lo3cd1t3IicxgeaLHG97VEzJxjlV8w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


8. [345 所开设人工智能本科专业高校名单大全](https://mp.weixin.qq.com/s/J73SNLj0HBJg-rkwWGVi2g)       :star::star:
   - Abstract: 345 所开设人工智能本科专业高校名单大全



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