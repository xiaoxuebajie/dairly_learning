# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.6.20

------



## :paperclip:  今日要点

1. [CVPR 2022 Oral | TCFormer：基于动态token聚类的transformer](https://mp.weixin.qq.com/s/Yz-wrAqQAqm_TKlxjQa5xQ)         :star::star:
   - Abstract: TCFormer：基于动态token聚类的transformer
   - Paper: [Not All Tokens Are Equal: Human-centric Visual Analysis via Token Clustering Transformer](https://arxiv.org/abs/2204.08680)
   - Code: [https://github.com/zengwang430521/TCFormer](https://github.com/zengwang430521/TCFormer)
   - Tips:  TCFormer 采用了一种基于特征聚类的动态令牌生成方式，和一种基于 transformer 的特征聚合模块。TCFormer 在基于图像的人体全身关键点估计、人脸关键点估计和人体三维网格重建任务上都获得了最先进的效果，并在人体细节的重建精度上取得了明显的提升。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/ibaXaPIy7jV0yac2ueIs1mAWEibY02eeskas0j6YPujgfoQvHEHO4FUhFNPhop0q3nch6B1z0rzxorXQqxWrHFdw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


2. [预训练的数据不是越多越好？港科大&华为诺亚提出具有可扩展动态路由的自监督预训练范式SDRNet，在分类和检测任务上SOTA！](https://mp.weixin.qq.com/s/LwqDSQM0of2A0jVmLTjBXw)       :star::star:
   - Abstract:  港科大&华为诺亚提出具有可扩展动态路由的自监督预训练范式SDRNet
   - Paper: [Task-customized Self-supervised Pre-training with Scalable Dynamic Routing](https://www.aaai.org/AAAI22Papers/AAAI-12678.LiuZ.pdf)
   - Tips: 作者提出了一种新的SSL范式，称为可拓展动态路由（SDR），它可以为不同的下游任务实现动态预训练和高效部署。具体来说，作者用不同的子网构建SDRnet，并用包含不同语义簇的不同数据子集训练每个子网。作者进一步提出了一个数据感知的渐进式训练框架，以稳定子网的预训练过程并避免崩溃。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTteWLH8JCqqxWhJ2E0EmtMPbfzBXLAxT0MKrRv7QNBWiaSxhHr7G7x5IjHlGHd2O0WYxibQiavsE3aDg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

3. [CVPR 2022 | 只需要一组预训练参数，所有恶劣天气一次解决！](https://mp.weixin.qq.com/s/MnqgHMqGzA4c1kk6sI-IUg)       :star::star:
   - Abstract: 只需要一组预训练参数，所有恶劣天气一次解决！
   - Paper: [Learning Multiple Adverse Weather Removal via Two-stage Knowledge Learning and Multi-contrastive Regularization: Toward a Unified Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Learning_Multiple_Adverse_Weather_Removal_via_Two-Stage_Knowledge_Learning_and_CVPR_2022_paper.pdf)
   - Code: [https://github.com/fingerk28/Two-stage-Knowledge-For-Multiple-Adverse-Weather-Removal](https://github.com/fingerk28/Two-stage-Knowledge-For-Multiple-Adverse-Weather-Removal)
   - Tips: 使用collaborative knowledge Transfer去做不同的天气型态学习，并且设计多种模块帮助学习对于多天气学习是相当有帮助的；使用multi-contrastive regularization及two-stage knowledge learning能够帮助模型根据不同的难度去做知识的学习。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oUTcHDKKYHb9oGRuP0tVic5MsWZRnvZuv45MsYkWt4E4NyJ63gIoSWV5upMUndFdFScqdue7G99WVQ/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

4. [Curriculum Labeling：重新审视半监督学习的伪标签](https://mp.weixin.qq.com/s/xpJrqfJKdYuSoxn40dCSnQ)       :star::star:
   - Abstract: Curriculum Labeling：重新审视半监督学习的伪标签
   - Paper: [Curriculum Labeling: Revisiting Pseudo-Labeling for Semi-Supervised Learning](https://arxiv.org/abs/2001.06001)
   - Code: [https://github.com/uvavision/Curriculum-Labeling](https://github.com/uvavision/Curriculum-Labeling)
   - Tips: Curriculum Labeling (CL)，在每个自训练周期之前重新启动模型参数，优于伪标签 (PL)。Pseudo-Labeling (PL) 通过将伪标签应用于未标记集中的样本以在自训练周期中进行模型训练。Curriculum Labeling (CL)中，应用类似课程学习的原则，通过在每个自学习周期之前重新启动模型参数来避免概念漂移。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/6wQyVOrkRNIZjOQSiaMtOQSVNWcpvNI3vxWWaIIN2EBHLJnTK86EpicrDpDiaHzrp9kic184icgTlpfvJ9aJQj3lgKg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [CVPR2022 | 基于自我中心数据的OCR评估](https://mp.weixin.qq.com/s/SByoUbGiomVpx5VvcrYk6Q)       :star::star:
   - Abstract: 基于自我中心数据的OCR评估
   - Paper: [An Evaluation of OCR on Egocentric Data](http://arxiv.org/pdf/2206.05496)
   - Code: [https://github.com/tobyperrett/epic-text-annotations](https://github.com/tobyperrett/epic-text-annotations)
   - Tips: 本文研究了OCR方法在EPIC-KITCHENS数据集中识别图像中文本的能力。介绍了一种有效的旋转和合并pipeline。将其应用于经过预训练的最新OCR方法，展示了相对于所有非旋转感知基线的巨大改进。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/V2E1ll6kaTUgbicceq94yoZ60URa9RE0VWhMdqthjCsbBGcIjwicGnMELfHoodY42IFkO6I1lUpBQcPqJGCyzAww/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [卧槽，这才是最强Python刷题网站！](https://mp.weixin.qq.com/s/9tMM9ysdtKgOgL_d_2gzNA)       :star::star:
   - Abstract: 卧槽，这才是最强Python刷题网站！
   - Address: [https://www.nowcoder.com/link/pc_gzh_pyahzsq_python](https://www.nowcoder.com/link/pc_gzh_pyahzsq_python)
   - Tips: 作者给大家推荐一个粉丝反馈用起来不错的免费python学习&练习网站。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/SXE9StoF95O3o8X4eALeeTgpFL9Kjwk13dNL9QJrMyHXY7ntuIicJibjVRS41eJKpic8YgHT7UbuWibUUDLs5xb90Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
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
    18. <a href="notes/202205/0530.md" target="_blank">公众号内容拓展学习笔记（2022.5.30）</a>
    19. <a href="notes/202205/0531.md" target="_blank">公众号内容拓展学习笔记（2022.5.31）</a>
</details>
<details><summary>6月</summary>
    1. <a href="notes/202206/0601.md" target="_blank">公众号内容拓展学习笔记（2022.6.1）</a>
    2. <a href="notes/202206/0607.md" target="_blank">公众号内容拓展学习笔记（2022.6.7）</a>
    3. <a href="notes/202206/0619.md" target="_blank">公众号内容拓展学习笔记（2022.6.19）</a>
    4. <a href="notes/202206/0620.md" target="_blank">公众号内容拓展学习笔记（2022.6.20）</a>
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