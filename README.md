# CVPR 2026 Robot Manipulation Paper Collection

个人整理的 CVPR 2026 机器人操作相关论文及代码仓库。

## 1. 视频/图像指导机器人抓取

*   **[Robo-Dopamine: General Process Reward Modeling for High-Precision Robotic Manipulation](https://arxiv.org/abs/2512.23703)**
    *   [GitHub链接](https://github.com/FlagOpen/Robo-Dopamine)
    *   简介：提出了用于RL训练的多巴胺奖励（Dopamine-Reward），这是一种新颖的奖励建模方法，用于从多视角输入中学习通用的、步数感知的过程奖励模型。
      
*   **[MM-ACT: Learn from Multimodal Parallel Generation to Act](https://arxiv.org/abs/2512.00975)**
    *   [GitHub链接](https://github.com/HHYHRHY/MM-ACT?tab=readme-ov-file)
    *   简介：MM-ACT是一个统一的视觉-语言-行动（VLA）模型，在共享token空间中集成文本、图像和动作，并从三种模态中生成兼具语义理解、环境预测和环境互动等能力的策略。
      
*   **[ORV: 4D Occupancy-centric Robot Video Generation](https://arxiv.org/abs/2506.03079)**
    *   [GitHub链接](https://github.com/OrangeSodahub/ORV)
    *   简介：ORV是一种以占用为中心的机器人视频生成框架，将动作先验与占用衍生的视觉先验结合起来，进一步探索使用生成视频训练机器人的可能性。

*   **[Real2Edit2Real: Generating Robotic Demonstrations via a 3D Control Interface](https://arxiv.org/abs/2512.19402)**
    *   [GitHub链接](https://github.com/Real2Edit2Real/Real2Edit2Real)
    *   简介：本文提出了Real2Edit2Real框架，通过3D控制界面连接3D编辑性与2D视觉数据，生成用于机器人训练的合成演示。

*   **[DemoFunGrasp: Universal Dexterous Functional Grasping via Demonstration-Editing Reinforcement Learning](https://arxiv.org/abs/2512.13380)** 
    *   [GitHub链接](https://github.com/BeingBeyond/DemoFunGrasp)
    *   简介：本研究提出了用于通用灵巧功能抓握的DemoFunGrasp，旨在解决功能抓取面临诸多挑战。我们将功能性抓握条件分解为抓取风格和可供性两个互补组成部分，并将其集成到一个能够学习掌握任何具有函数抓握条件的对象的强化学习框架中。通过引入视觉语言模型（VLM）进行规划，我们的策略实现了自主指令跟随抓取执行。

*   **[ViHOI: Human-Object Interaction Synthesis with Visual Priors](https://arxiv.org/abs/2603.24383)**
    *   [GitHub链接](https://github.com/Songjin-Cai/ViHOI)
    *   简介：有视觉先验的人机交互框架。以视觉语言模型（VLM）为基础从二维图像中提取丰富的视觉先验信息，利用先验信息提升扩散模型所生成的交互姿势质量。

*   **[Global Prior Meets Local Consistency: Dual-Memory Augmented Vision-Language-Action Model for Efficient Robotic Manipulation](https://arxiv.org/abs/2602.20200)**
    *   [GitHub链接](https://github.com/CybertronAgent/OptimusVLA.github.io)
    *   简介：OptimusVLA是一种双记忆层级视觉-语言-行动（VLA）框架，通过引入全局先验内存（GPM），从语义相似轨迹中检索的任务级先验取代高斯噪声，从而缩短生成路径并减少函数评估（NFE）。通过局部一致性内存（LCM），动态建模执行的动作序列以推断任务进展，并添加学习的一致性约束，保证时间一致性和轨迹的平滑性。

*   **[RealVLG-R1: A Large-Scale Real-World Visual-Language Grounding Benchmark for Robotic Perception and Manipulation](https://arxiv.org/abs/2603.14880)**
    *   [GitHub链接](https://github.com/lif314/RealVLG-R1?tab=readme-ov-file#realvlg-r1-a-large-scale-real-world-visual-language-grounding-benchmark-for-robotic-perception-and-manipulation)
    *   简介：RealVLG是一个旨在弥合自然语言与机器人抓取之间鸿沟的统一框架，该框架整合了RealVLG-11B数据集和RealVLG-R1模型。RealVLG-11B 数据集提供多粒度注释，包括边界框、分割遮罩、抓握姿态、接触点以及人工验证的细粒度语言描述。基于该数据集，RealVLG-R1 在预训练的大规模视觉语言模型上采用强化微调，在自然语言指令下统一预测边界框、分割掩码、抓取姿势和接触点。

*   **[Beyond Success: Refining Elegant Robot Manipulation from Mixed-Quality Data via Just-in-Time Intervention](https://arxiv.org/abs/2511.22555)**
    *   [GitHub链接](https://github.com/Mwuqiu/BeyondSuccess)
    *   简介：VLA模型生成的策略质量较为参差，我们将这种变异归因于人类演示的质量参差不齐，即在这些演示中决定行动应如何执行的隐含条件仅被部分满足。为应对这一挑战，我们引入了带有明确执行质量评估标准的LIBERO-Elegant基准测试，即时评估并干涉机器人运动，实现在不修改或重新训练基础VLA策略的情况下提升策略质量。


*   **[Clay-to-Stone: Phase-wise 3D Gaussian Splatting for Monocular Articulated Hand-Object Manipulation Modeling（尚未公开论文）]
    *   [GitHub链接](https://github.com/ru1ven/ArGS)
    *   简介：用于单眼关节手-物体操作建模的相位三维高斯喷溅。
    
## 2. 双手抓取

*   **[UniDex: A Robot Foundation Suite for Universal Dexterous Hand Control from Egocentric Human Videos](https://arxiv.org/abs/2603.22264)**
    *   [GitHub链接](https://github.com/ru1ven/ArGS)
    *   简介：UniDex是由UniDex-Dataset、UniDex-VLA 和 UniDex-Cap 共同构成的一套机器人操作基础套件，将大规模机器人中心数据集与统一的视觉-语言-行动（VLA）策略及实用的人类数据采集方案相结合，实现通用灵活的手部控制。

*   **[论文标题](论文链接)**
    *   [GitHub链接](https://github.com/zzz/zzz)
    *   简介：
      
## 3. 人手到机器手迁移

*   **[MimiCAT: Mimic with Correspondence-Aware Cascade-Transformer for Category-Free 3D Pose Transfer](https://arxiv.org/abs/2511.18370)**
    *   [GitHub链接](https://github.com/czh-98/MimiCAT)
    *   简介：3D姿态转移旨在将源网格的姿态样式转移到目标角色，同时保持目标的几何体和源的姿态特征。本研究构建了一个涵盖数百个不同字符的百万尺度姿势数据集，并提出了MimiCAT，一种设计用于无类别三维姿态转移的级联Transformer模型。MimiCAT不再依赖严格的一对应映射，而是利用语义关键点标签学习一种新颖的软对应，实现字符间灵活的多对多匹配。
      
## 4. Others

*   **[Efficient Hybrid SE(3)-Equivariant Visuomotor Flow Policy via Spherical Harmonics for Robot Manipulation](https://arxiv.org/html/2603.23227v1)**
    *   [GitHub链接](https://github.com/zql-kk/E3Flow)
    *   简介：基于Diffusion Policy的机器人抓取框架，主要聚焦于等变抓取情景下的计算效率问题。
      
*   **[FrankenMotion: Part-level Human Motion Generation and Composition](https://arxiv.org/abs/2601.10909)**
    *   [GitHub链接](https://github.com/Coral79/FrankenMotion-Code?tab=readme-ov-filez)
    *   简介：

