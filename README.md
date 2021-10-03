# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2021.10.3

------





## :paperclip:  今日要点

1. [Google 提出两个逆天模型：体积下降7倍，速度提升10倍](https://mp.weixin.qq.com/s/GmH9wBkNUjBgZS9rF6ngdw)         :star::star:
   - Abstract: Google 提出两个逆天模型EfficientNetV2和CoAtNet
   - Paper1: [EfficientNetV2: Smaller Models and Faster Training](https://arxiv.org/abs/2104.00298)
   - Paper2: [CoAtNet: Marrying Convolution and Attention for All Data Sizes](https://arxiv.org/abs/2106.04803)
   - Code1: [https://github.com/d-li14/efficientnetv2.pytorch](https://github.com/d-li14/efficientnetv2.pytorch)
   - Tips:  EfficientNetV2在较小数据集上模型更小更快，CoAtNet结合了卷积和自注意的混合模型在大规模数据集上实现更高的精度。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb3hv0a8iaR7Gth8ibrt98PNmH5icIsS063WyYia9EC8kHpldHKmBY8ACno8AibStibTqpWBLIaodTGZXmgQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb3hv0a8iaR7Gth8ibrt98PNmHPeTJLj4vw4iabrJEEYV0TyzM6MB3CmV24TF9PjljZbibQHOeoKA07Xbg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [NeurIPS 2021 | 所有图像都值16x16个词吗？清华提出DVT：可变序列长度的动态Transformer](https://mp.weixin.qq.com/s/dsQaIN3sm7qPjnBXTUEmFw)       :star::star:
   - Abstract: 清华提出DVT可变序列长度的动态Transformer
   - Paper: [Not All Images are Worth 16x16 Words: Dynamic Vision Transformers with Adaptive Sequence Length](https://arxiv.org/abs/2105.15075)
   - Code: [https://github.com/blackfeather-wang/Dynamic-Vision-Transformer](https://github.com/blackfeather-wang/Dynamic-Vision-Transformer)
   - Tips: 对于大多数Transformer采用的对图片以固定方式划分patch的表征方式，不够灵活，应当根据输入数据动态调整表征方式。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oUS4c203L60Fe8iaeSZeuVCIYosgxZYQ4FicCvribiaxRnq0CyMu6K3ZB42zicpzuYf07cibbaHFhvUQDCg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>



3. [用ViT替代卷积网络做密集预测，英特尔实验室提出DPT架构，在线Demo可用](https://mp.weixin.qq.com/s/6HfYVVMa6ZR8u-Vy51LKhQ)       :star::star:
   - Abstract: 英特尔实验室提出DPT架构做密集预测
   - Paper: [Vision Transformers for Dense Prediction](https://arxiv.org/abs/2103.13413)
   - Code: [https://github.com/intel-isl/dpt](https://github.com/intel-isl/dpt)
   - Demo: [https://huggingface.co/spaces/akhaliq/DPT-Large](https://huggingface.co/spaces/akhaliq/DPT-Large)
   - Tips: DPT这种架构对于密集预测任务有很大的改进，特别是在有大量训练数据可用的情况下。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8KyE14ibib9Xx3ZQx28NRcpKoLodLZ0mibj86ibfVfvhPibOqdOWrPTWia7PO9hBcZAG3kmrfoxZkxNYFw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [一文读懂3D人脸识别十年发展及未来趋势](https://mp.weixin.qq.com/s/kEZYpPnqJiiLxqH-CIK-Zw)       :star::star:
   - Abstract:  3D人脸识别十年发展及未来趋势
   - Paper: [3D Face Recognition: A Survey](https://arxiv.org/pdf/2108.11082v1.pdf)
   - Tips: 这是第一篇全面涵盖传统方法和基于深度学习的 3D 人脸识别方法的调查论文,特别关注基于深度学习的 3D 人脸识别方法.

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWibzjrRjLy3UfhQ4JVjUZJo6cglIgucnZvAndHj3h3GDMRLdZKzzib25gIAN4MG8OY4XrgY5GtFNPGw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [单目视觉系统检测车辆的测距方法（Mobileye单目测距等7种方法）](https://mp.weixin.qq.com/s/0kL-RUb8nmmYIgnD-h2EcA)       :star::star:
   - Abstract: 单目视觉系统检测车辆的测距方法
   - Tips: 介绍了若干有关单目视觉系统的测距方法以及相关论文

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/q7yyTjjeGadmqdCwibNoI0a4oIKeaqMDVKEWDRuQVfP4zRYPauagJo2ck7RiaI5dfzabWvAhufGmYNia8ehYtSnbw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [2021年自然语言处理校招社招实习必备知识点盘点分享](https://mp.weixin.qq.com/s/0B_nxgv0w_4MoTErjdvoHg)       :star::star:
   - Abstract: 2021年自然语言处理校招社招实习必备知识点盘点分享
   - Address: [https://github.com/km1994/nlp_paper_study](https://github.com/km1994/nlp_paper_study)
   - Tips: 本资源整理了自然语言处理领域中常见的一些知识点，并给出了答案，分享给大家。对于准备自然语言处理校招、社招、实习岗位的朋友，可以好好研读一下

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/1niaDLWmibswdnHxTOMoKrwuXdQCPsicibT1IL9ia1VuD4H3v4O56nr8PfJ172CSVzVSCSAF3OPMwQJt1laic8VLDj6g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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