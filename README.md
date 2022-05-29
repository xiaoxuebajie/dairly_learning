# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.5.29

------

## :paperclip:  今日要点

1. [基于跨模态元迁移，美图&大连理工的参考视频目标分割方法只需单阶段](https://mp.weixin.qq.com/s/7GPy-WmIki0X8WLtCfgliA)         :star::star:
   - Abstract: 基于跨模态元迁移，美图&大连理工的参考视频目标分割方法只需单阶段
   - Paper: [You Only Infer Once: Cross-Modal Meta-Transfer for Referring Video Object Segmentation](https://www.aaai.org/AAAI22Papers/AAAI-1100.LiD.pdf)
   - Tips: 该研究提出了一种跨模态元迁移的端到端 RVOS 框架 ——YOFO，只需单阶段推理，即可实现利用参考文本信息直接得到视频目标的分割结果；提出了一个元迁移（Meta-Transfer）模块来增强时序信息，从而实现了更聚焦于目标的特征学习；提出了一个多尺度跨模态特征挖掘（Multi-Scale Cross-Modal Feature Mining）模块，能够充分融合语言、图片中的有用特征。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/KmXPKA19gWibFORd1PPiaLxnibStokSaqwgGLgTicStvSuAGymYtoQHfMHlqmXOLick784YhL4yGcGwJO59txYXIRkA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [3D车道线单目检测方法ONCE-3DLanes](https://mp.weixin.qq.com/s/dWu8hCuSe5i9sDQvRLGo7g)       :star::star:
   - Abstract: 3D车道线单目检测方法ONCE-3DLanes
   - Paper: [ONCE-3DLanes: Building Monocular 3D Lane Detection](https://arxiv.org/abs/2205.00301)
   - Code: [https://github.com/once-3dlanes/once_3dlanes_benchmark](https://github.com/once-3dlanes/once_3dlanes_benchmark)
   - Tips: 该文提出一个真实世界的自动驾驶数据集，ONCE-3DLanes，具有3-D空间的车道线布局标注。通过点云和图像像素之间的显式关系，文章设计了该数据集标注流水线，从211K个道路场景的2D车道线标注，自动生成高质量的3D车道线位置。此外，作者还提出一种无外参、无锚点的方法，称为SALAD，在图像视图中回归车道线的3D坐标，而无需将特征地图转换为BEV。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwgPFZfItoJRIU8WyUMP2DxicZEk8gl2d7tkeadNZvkNEdUYthoIYqpdHWo2y5FWEFdRof5U2tf59CQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [浙大提出神经3D重建新工作！收录图形学顶会SIGGRAPH 2022](https://mp.weixin.qq.com/s/NQ-_AgFB0UXqxLDOGDgrWA)       :star::star:
   - Abstract: 浙大提出神经3D重建新工作！收录图形学顶会SIGGRAPH 2022
   - Paper: [Neural 3D Reconstruction in the Wild](https://arxiv.org/abs/2205.12955)
   - Code: [https://zju3dv.github.io/neuralrecon-w](https://zju3dv.github.io/neuralrecon-w)
   - Tips: 这项研究的基本框架借鉴了NeurIPS 2021上的NeuS，一种把隐式神经标准和体积渲染结合起来的方法。考虑NeuS的一些不足，研究人员提出体素引导（Voxel-guided）和表面引导（Surface-guided）混合的新采样方法。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_gif/YicUhk5aAGtDWs05CiaLVxqH1BfJr4fUvSGh8kvicswd4eK9Al4fON2yHJibrqaBwl1evXzowUv8NUbIeKeLV6U3Dw/640?wx_fmt=gif&wxfrom=5&wx_lazy=1" style='zoom:100%'>
</div>


4. [CVPR 2022 | 图森未来提出小目标检测工作QueryDet：使用级联稀疏query加速高分辨率下的小目标检测](https://mp.weixin.qq.com/s/jyE_73f0oSWiV70LRHi0Fg)       :star::star:
   - Abstract: 图森未来提出小目标检测工作QueryDet：使用级联稀疏query加速高分辨率下的小目标检测
   - Paper: [QueryDet: Cascaded Sparse Query for Accelerating High-Resolution Small Object Detection](https://arxiv.org/abs/2103.09136)
   - Code: [https://github.com/ChenhongyiYang/QueryDet-PyTorch](https://github.com/ChenhongyiYang/QueryDet-PyTorch)
   - Tips: QueryDet利用high-resolution feature来提升小目标检测性能的同时，通过CSQ机制，利用高层低分辨率特征初筛含有小目标的区域，在高分辨特征层上利用初筛获得的位置，使用sparse convolution，极大地节约了计算消耗。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oWwLqLCO7nbYE9PWOnDv7wvNicsicxhYcWNZvrAosZh9no6yWlo7GQNjxWpPY9weKYTXwic7V3517ZlA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


5. [Science：睡眠医学的突破，大脑会在梦境中巩固积极情绪](https://mp.weixin.qq.com/s/xFdR-3hd0xpD96RvCqu38Q)       :star::star:
   - Abstract: 睡眠医学的突破，大脑会在梦境中巩固积极情绪
   - Paper: [Paradoxical somatodendritic decoupling supports cortical plasticity during REM sleep](https://www.science.org/doi/10.1126/science.abk2734)
   - Tips: 在这项研究中，科学家们发现大脑会在梦境睡眠中对情绪进行分类，并巩固积极情绪的储存，同时抑制消极情绪。研究人员表示，这项工作强调了睡眠在心理健康中的重要性，并开辟了新的治疗策略。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5qv5QsBmI9Cf6zzjVoM3N2rictzAJu89U82JJCtwLcUTKDkgspaObVg0Z0ibVuXV3Y7M9vKTtJMYZoSYzib797Q2A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


6. [ACL 2022 | 蚂蚁、北大提出基于层次化对比学习的文本生成框架，提升支付宝搜索体验](https://mp.weixin.qq.com/s/UA3JQzMiHKNT3WaIdqbdLw)       :star::star:
   - Abstract: 蚂蚁、北大提出基于层次化对比学习的文本生成框架，提升支付宝搜索体验
   - Paper: [Keywords and Instances: A Hierarchical Contrastive Learning Framework Unifying Hybrid Granularities for Text Generation](https://aclanthology.org/2022.acl-long.304.pdf)
   - Tips: 研究者提出了一种多粒度对比生成方法，设计了层次化对比结构，在不同层级上进行信息增强，在句子粒度上增强学习整体的语义，在词粒度上增强局部重要信息。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWibquRMwEibkpA6kMms9zjIvBPY4pHyxhicj18jsf8xLtMkkXFOJFUsMicXHCYJYWolqnMOtDIFgNgHZw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    7. <a href="notes/202205/0518.md" target="_blank">公众号内容拓展学习笔记（2022.5.18）</a>
    8. <a href="notes/202205/0519.md" target="_blank">公众号内容拓展学习笔记（2022.5.19）</a>
    9. <a href="notes/202205/0520.md" target="_blank">公众号内容拓展学习笔记（2022.5.20）</a>
    10. <a href="notes/202205/0521.md" target="_blank">公众号内容拓展学习笔记（2022.5.21）</a>
    11. <a href="notes/202205/0522.md" target="_blank">公众号内容拓展学习笔记（2022.5.22）</a>
    12. <a href="notes/202205/0523.md" target="_blank">公众号内容拓展学习笔记（2022.5.23）</a>
    13. <a href="notes/202205/0524.md" target="_blank">公众号内容拓展学习笔记（2022.5.24）</a>
    14. <a href="notes/202205/0525.md" target="_blank">公众号内容拓展学习笔记（2022.5.25）</a>
    15. <a href="notes/202205/0527.md" target="_blank">公众号内容拓展学习笔记（2022.5.27）</a>
    16. <a href="notes/202205/0528.md" target="_blank">公众号内容拓展学习笔记（2022.5.28）</a>
    17. <a href="notes/202205/0529.md" target="_blank">公众号内容拓展学习笔记（2022.5.29）</a>
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