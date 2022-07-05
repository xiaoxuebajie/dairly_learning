# dairly_learning
主要内容：有关计算机视觉，NLP等公众号内容学习笔记日更记录

更新开始时间：2021.3.21

更新今日时间：2022.7.5

------



## :paperclip:  今日要点

1. [港科大&MSRA：图像到图像转换，Finetuning is all you need](https://mp.weixin.qq.com/s/dIFubdO7TPx4pvRQ8aSEAQ)         :star::star:
   - Abstract: 港科大&MSRA：图像到图像转换，Finetuning is all you need
   - Paper: [Pretraining is All You Need for Image-to-Image Translation](https://arxiv.org/pdf/2205.12952.pdf)
   - Tips:  研究者将每个图像到图像的转换问题视为下游任务，并引入了一个简单通用框架，该框架采用预训练的扩散模型来适应各种图像到图像的转换。他们将提出的预训练图像到图像转换模型称为 PITI（pretraining-based image-to-image translation）。此外，研究者还提出用对抗训练来增强扩散模型训练中的纹理合成，并与归一化指导采样结合以提升生成质量。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gWicGSyLwmgvrPibLE4pesQnqgTqN7IX6xLfSZ6zVVbor6XufjOoqklXosvEfV1ElTtMCDWzCf1dUXWA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

2. [屠榜多目标跟踪！BoT-SORT：稳健的关联多行人跟踪](https://mp.weixin.qq.com/s/5d22OZbrxS-FTLqh1iCn4g)       :star::star:
   - Abstract: 屠榜多目标跟踪！BoT-SORT：稳健的关联多行人跟踪
   - Paper: [BoT-SORT: Robust Associations Multi-Pedestrian Tracking](https://arxiv.org/abs/2206.14651)
   - Code: [https://github.com/NirAharon/BOT-SORT](https://github.com/NirAharon/BOT-SORT)
   - Tips: 在本文中提出了一种新的鲁棒跟踪器，它可以结合运动和外观信息的优点，以及相机运动补偿和更准确的卡尔曼滤波器状态向量。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/5ooHoYt0tgktYQfMrLIJOqz7t9YDZAUCWPdwxkCiaTv2Ls3POc5fVTuO6Lt2GabtiaQib92DjsUUfGrIibKlLOXqgA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


3. [ScePT: 为规划的场景一致和基于策略轨迹预测](https://mp.weixin.qq.com/s/UxZFYHFk32MSTnK58FSFwQ)       :star::star:
   - Abstract: ScePT: 为规划的场景一致和基于策略轨迹预测
   - Paper: [ScePT: Scene-consistent, Policy-based Trajectory Predictions for Planning](https://arxiv.org/abs/2206.13387)
   - Code: [https://github.com/nvr-avg/ScePT](https://github.com/nvr-avg/ScePT)
   - Tips: 这项工作提出基于策略规划的轨迹预测模型ScePT，该模型可以生成适用于自主系统运动规划、精确、场景一致的轨迹预测。其明确地强制场景一致性，并学习可用于制约预测的智体交互策略。在多个真实行人和自主车辆数据集上的实验表明，ScePT匹配当前最先进的预测精度，并显著提高场景一致性。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/E5w2bqqaSwiaxw6ZUxiadRMERFqj1L9nBLp6oj5wMaPolUngBB3lLwDqqsngnLn8yKjtkp5b79dBy5AoqVo8SYAg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>


4. [CVPR 2022 | 复旦大学提出ZITS：基于Transformer结构增强的增量式图像修复](https://mp.weixin.qq.com/s/Bnqw2gFS_TTEeglRm3aIIw)       :star::star:
   - Abstract: 复旦大学提出ZITS：基于Transformer结构增强的增量式图像修复
   - Paper: [Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding](https://arxiv.org/abs/2203.00867)
   - Code: [https://github.com/DQiaole/ZITS_inpainting](https://github.com/DQiaole/ZITS_inpainting)
   - Tips: 作者利用了一个基于Transformer的模型推断整体结构（边缘+线框）。利用简单的CNN，我们可以把这种结构图非常轻松的上采样到任意分辨率。进一步地，我们提出了利用零初始化残差连接技术增量式地将结构注入到后续CNN纹理修复网络。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_jpg/yNnalkXE7oX1JznWHEUhCBa6FgnxEGmGRPJIibvsnhWnFaTw6zgSCuoN4mm4YQqu4VJQA3TayicD5QXypts1rZ0g/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

5. [【源头活水】CVPR 2022 | 大幅减少零样本学习所需的人工标注，马普所和北邮提出富含视觉信息的类别语义嵌入](https://mp.weixin.qq.com/s/VfXlObtw2nbZayuuxtUsvg)       :star::star:
   - Abstract: 大幅减少零样本学习所需的人工标注，马普所和北邮提出富含视觉信息的类别语义嵌入
   - Paper: [VGSE: Visually-Grounded Semantic Embeddings for Zero-Shot Learning](https://arxiv.org/abs/2203.10444)
   - Code: [https://github.com/wenjiaXu/VGSE](https://github.com/wenjiaXu/VGSE)
   - Tips: 为减少零样本学习所需的人工标注，提高类别嵌入的语义和视觉完备性，本文提出一个自动的类别嵌入发掘网络 VSGE 模型，能够利用图像切片的视觉相似性发掘类别嵌入。

<div align=center><img src="https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW9zTkJA8futG2rNvAkVibZnFJAIYTSHFQTJEohUynFZQZYlHNNUErSEyuqsmkn5LH9Sf23KClVc9qQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" style='zoom:100%'>
</div>

6. [SIGGRAPH 2022|通过步态就能识别身体疾病，好神奇](https://mp.weixin.qq.com/s/3rbNM6PkQHxIvwG3NmsoLA)       :star::star:
   - Abstract: 通过步态就能识别身体疾病，好神奇
   - Paper: [Generative GaitNet](https://mrl.snu.ac.kr/research/ProjectGaitNet/paper.pdf)
   - Tips: 本文提出了生成式GaitNet，这是一种基于深度强化学习控制一个包含304条hill型肌肉肌腱的全面的全身肌肉骨骼模型。生成式GaitNet是一个预先训练的，在618-dimensional连续学习的人工神经网络的集成系统解剖学状况(例如，质量分布、身体比例、骨骼畸形和肌肉缺陷)和步态状况(如步幅和节奏)。

<div align=center><video src="http://mpvideo.qpic.cn/0bc3eiaaiaaauiakgsf64brfaiwdaqraabaa.f10003.mp4?dis_k=71a653cadfe202f8cdc22ebe63ea0f5f&dis_t=1656987195&vid=wxv_2467418745456656388&format_id=10003&support_redirect=0&mmversion=false" style='zoom:100%'>
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
<details><summary>7月</summary>
    1. <a href="notes/202207/07015.md" target="_blank">公众号内容拓展学习笔记（2022.7.5）</a>
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