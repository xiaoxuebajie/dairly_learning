# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.17

------



## :paperclip:  今日要点

1. [李飞飞团队提出零样本泛化的技术，性能超越SOTA！](https://mp.weixin.qq.com/s/CdwpToIQJoMwNYyPT5QzwQ)         :star::star:
   - Abstract: 李飞飞团队提出零样本泛化的技术，性能超越SOTA！
   - Paper: [SECANT: Self-Expert Cloning for Zero-Shot Generalization of Visual Policies](https://arxiv.org/abs/2106.09678)
   - Tips: 提出了SECANT模型，可以依次解决策略学习和鲁棒性表征学习问题，从而实现了对未见过的视觉环境的强大零样本泛化性能；在自动驾驶、机器人操作和室内物体导航四个领域中，设计并制定了一套多样化的基准测试

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/UicQ7HgWiaUb2FurX4cbJs64CTiaRvZQORvEOMEmsWJDPPwq2oicOzn5gSmlEGy2Fr2PRGA7LMUQ9YhdXibx3Fp1jQg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [浙大蔡登团队：基于序列对比学习的长视频逐帧动作表征](https://mp.weixin.qq.com/s/n7bpcKZL_QJbl8RND3144Q)       :star::star:
   - Abstract: 浙大蔡登团队：基于序列对比学习的长视频逐帧动作表征
   - Paper: [Frame-wise Action Representations for Long Videos via Sequence Contrastive Learning](https://arxiv.org/pdf/2203.14957.pdf)
   - Tips: 浙大蔡登团队携手微软亚洲研究院，提出了一个新的对比动作表征学习（CARL）框架，以自监督的方式学习逐帧动作表征，尤其是针对长视频；它考虑了时空上下文来提取逐帧表征，是一种基于Transformer的简单而高效的视频编码器。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/cNFA8C0uVPsoX5eOX4VUha5cflWbDibYu5C1c2cU7FRjmYDsVUmNdafzhMzvmhoDGyFMkuHdiaQNUzCAfNJicnnZw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [实时图像增强，基于“间距自适应查找表”的方法（CVPR 2022）](https://mp.weixin.qq.com/s/GPVRPyj5wsePLUh2_6tdxQ)       :star::star:
   - Abstract: 实时图像增强，基于“间距自适应查找表”的方法
   - Paper: [AdaInt: Learning Adaptive Intervals for 3D Lookup Tables on Real-time Image Enhancement](https://arxiv.org/abs/2204.13983)
   - Code: [https://github.com/ImCharlesY/AdaInt](https://github.com/ImCharlesY/AdaInt)
   - Tips: 首次提出了通过深度学习对输入图像自适应地学习具有非均匀布局的三维颜色查找表，从而对输入图像进行高效色彩增强的创新性技术，并在学术界公开仿真数据集上取得了最优客观指标（PSNR）的同时做到了当前运行速度最快。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/33P2FdAnju8vCRfEib17iashXliaTjvWMXvEw2WLoRrxGBFkKzzu5kibrNYE7tS9Q3cFwTGLe8iaOkiaibT0MYrcYkpEA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [CVPR 2022 | 看谷歌的单张图片人体重建效果如何？](https://mp.weixin.qq.com/s/p3-GBwElqpjuIq9xNFf10A)       :star::star:
   - Abstract: 看谷歌的单张图片人体重建效果如何？
   - Paper: [Photorealistic Monocular 3D Reconstruction of Humans Wearing Clothing](https://arxiv.org/abs/2204.08906)
   - Tips: 提出了一个端到端的高质量人体重建方法，能够取得比当前 SOTA 更加准确、更多细节的重建结果；首次计算出人体的albedo和shading信息；提出了渲染损失，极大改善了预测的外观的真实性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/vwMhFCxvECgmFk0TIFSShM9rjulFC0HClYB5q9HibrdUvajZEnKRP3QARfW1D8WhwDYThcGohNnCicj3y74TUJBQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [硕博都在用的高校论文工具：科研工具推荐大合集！](https://mp.weixin.qq.com/s/y7ZB0_rwFSqvfMXWk4uJBQ)       :star::star:
   - Abstract: 硕博都在用的高校论文工具：科研工具推荐大合集！
   - Tips: 作者作为一个平时就很辛苦的科研er，本着能用工具解决的问题绝对不花苦力的原则，收集了很多科研利器，现在分享给大家，相信大家看完以后科研效率都能够得到质的提升！ 

<div align=center><img src="https://mmbiz.qpic.cn/sz_mmbiz_jpg/gYUsOT36vfqZSUYOO95jXVcBOkn4iaaOe0wENESNZHnV4wLQNvIbTzQcnzuy575H1urkTd9IZUtj88fyhTKXDnQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [多目标追踪小抄：快速了解MOT的基本概念](https://mp.weixin.qq.com/s/uXAe9rNAmsQsvUNBPQ803g)       :star::star:
   - Abstract: 多目标追踪小抄：快速了解MOT的基本概念
   - Tips: 有关多目标跟踪的相关基本概念，基础教学

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/6wQyVOrkRNLicEmR6G42CAUicyNwNFrU9hWoVWZ8QWzibPaYDTFcVqNlyUG0ibjSf6XPVvvraqaOOVkYf1SMlLjuKg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    15. <a href="notes/202203/0316.md" target="_blank">公众号内容拓展学习笔记（2022.3.16）</a>
    16. <a href="notes/202203/0317.md" target="_blank">公众号内容拓展学习笔记（2022.3.17）</a>
    17. <a href="notes/202203/0330.md" target="_blank">公众号内容拓展学习笔记（2022.3.30）</a>
</details>
<details><summary>4月</summary>
    1. <a href="notes/202204/0402.md" target="_blank">公众号内容拓展学习笔记（2022.4.2）</a>
    2. <a href="notes/202204/0414.md" target="_blank">公众号内容拓展学习笔记（2022.4.14）</a>
</details>
<details><summary>5月</summary>
    1. <a href="notes/202205/0505.md" target="_blank">公众号内容拓展学习笔记（2022.5.5）</a>
    2. <a href="notes/202205/0507.md" target="_blank">公众号内容拓展学习笔记（2022.5.7）</a>
    3. <a href="notes/202205/0509.md" target="_blank">公众号内容拓展学习笔记（2022.5.9）</a>
    4. <a href="notes/202205/0510.md" target="_blank">公众号内容拓展学习笔记（2022.5.10）</a>
    5. <a href="notes/202205/0511.md" target="_blank">公众号内容拓展学习笔记（2022.5.11）</a>
    6. <a href="notes/202205/0517.md" target="_blank">公众号内容拓展学习笔记（2022.5.17）</a>
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