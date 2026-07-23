# Dexterous Manipulation：遥操作、ACT、Diffusion Policy、VLA、World Model 全量扩展表

> 更新时间：2026-07-23。
>
> 仅保留统一字段：**工作、年份、分类、方法、Paper、GitHub**。
> 未确认官方代码时，GitHub 列标记为 `—`；不以第三方复现替代官方仓库。
> 同一工作如果横跨多个方向，可能在不同算法分类中重复出现，以方便按类别检索。

## 目录
- [1. 综述与持续更新索引](#1-综述与持续更新索引)
- [2. 遥操作、数据采集与动作重定向](#2-遥操作数据采集与动作重定向)
- [3. 模仿学习、ACT、人体视频与动作策略](#3-模仿学习act人体视频与动作策略)
- [4. Diffusion Policy、Flow Matching 与生成式动作模型](#4-diffusion-policyflow-matching-与生成式动作模型)
- [5. VLA、VLM 与灵巧操作基础模型](#5-vlavlm-与灵巧操作基础模型)
- [6. World Model、World Action Model 与视频预测](#6-world-modelworld-action-model-与视频预测)
- [7. Real-to-Sim、Sim-to-Real、数据生成与跨本体迁移](#7-real-to-simsim-to-real数据生成与跨本体迁移)
- [8. 人类在环、后训练、触觉与接触策略](#8-人类在环后训练触觉与接触策略)
- [9. 数据集、基准与大规模数据资源](#9-数据集基准与大规模数据资源)
- [10. Ego Manipulation 数据集与基准](#10-ego-manipulation-数据集与基准)
- [11. Ego 表征、手物感知与三维重建](#11-ego-表征手物感知与三维重建)
- [12. Ego-to-Robot、模仿学习与 VLA](#12-ego-to-robot模仿学习与-vla)
- [13. Ego World Model 与交互视频生成](#13-ego-world-model-与交互视频生成)

## 1. 综述与持续更新索引

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| Dexterous Manipulation through Imitation Learning: A Survey | 2025 | Survey / Imitation Learning | 系统梳理基于示范的灵巧操作方法、数据与挑战 | [Paper](https://arxiv.org/abs/2504.03515) | — |
| Diffusion Models for Robotic Manipulation: A Survey | 2025 | Survey / Diffusion | 梳理扩散模型在抓取、策略、规划和数据增强中的应用 | [Paper](https://arxiv.org/abs/2504.08438) | — |
| Towards Robotic Dexterous Hand Intelligence: A Survey | 2026 | Survey / Dexterous Hand | 从硬件、感知、控制、数据集和评测统一梳理灵巧手研究 | [Paper](https://arxiv.org/abs/2605.13925) | — |
| Robot Learning from Human Videos: A Survey | 2026 | Survey / Human Video | 梳理从人体视频到机器人动作、策略和世界模型的路线 | [Paper](https://arxiv.org/abs/2604.27621) | — |
| From Human Videos to Robot Manipulation: A Survey | 2026 | Survey / Human Video | 梳理人体视频重建、重定向、仿真优化和策略学习 | [Paper](https://arxiv.org/abs/2606.00054) | — |
| Awesome Humanoid & Dexterous Manipulation | 持续更新 | Awesome List | 人形、双臂、多指手、遥操与 sim-to-real 文献索引 | — | [GitHub](https://github.com/tsunami-kun/awesome-humanoid-manipulation) |
| Dexterous-Manipulation | 持续更新 | Awesome List | 灵巧手硬件、算法、数据集、VLA 与触觉资源索引 | — | [GitHub](https://github.com/kingchou007/Dexterous-Manipulation) |
| Awesome Robotics Diffusion | 持续更新 | Awesome List | 机器人 Diffusion / Flow Matching 策略文献索引 | — | [GitHub](https://github.com/showlab/Awesome-Robotics-Diffusion) |
| Awesome Touch | 持续更新 | Awesome List / Tactile | 触觉传感、视觉触觉策略与灵巧操作索引 | — | [GitHub](https://github.com/linchangyi1/Awesome-Touch) |
| Awesome Force/Tactile VLA | 持续更新 | Awesome List / VLA / Tactile | 力觉、触觉和 VLA 融合工作索引 | — | [GitHub](https://github.com/OpenHelix-Team/Awesome-Force-Tactile-VLA) |
| WholebodyVLA | 持续更新 | Awesome List / Whole-body VLA | 全身、移动、人形、双臂和灵巧 VLA 索引 | — | [GitHub](https://github.com/OpenDriveLab/WholebodyVLA) |
| Awesome World Models for Robots | 持续更新 | Awesome List / World Model | 机器人控制、规划和操作世界模型索引 | — | [GitHub](https://github.com/operator22th/awesome-world-models-for-robots) |

## 2. 遥操作、数据采集与动作重定向

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| DexPilot | 2020 | Teleoperation / Retargeting | 无标记视觉手部跟踪，联合控制机械臂与多指手 | [Paper](https://arxiv.org/abs/1910.03135) | — |
| DexMV | 2021/2022 | Human Video / Retargeting / IL | 从人体视频估计手物姿态，翻译为机器人灵巧手示范 | [Paper](https://arxiv.org/abs/2108.05877) | [GitHub](https://github.com/yzqin/dexmv-sim) |
| From One Hand to Multiple Hands | 2022 | Teleoperation / Retargeting / IL | 单相机采集人体手动作，并重定向到多种机器人手 | [Paper](https://arxiv.org/abs/2204.12490) | [GitHub](https://github.com/yzqin/dex-hand-teleop) |
| AnyTeleop | 2023 | Teleoperation / Retargeting | 统一不同机械臂、灵巧手和仿真/真实平台的视觉遥操 | [Paper](https://arxiv.org/abs/2307.04577) | [GitHub](https://github.com/dexsuite/dex-retargeting) |
| HIRO Hand | 2023 | Teleoperation / Haptic Interface | 同构穿戴式主手提供直接映射和操作者触觉 | [Paper](https://arxiv.org/abs/2309.14860) | — |
| DexCap | 2024 | Mocap / Teleoperation / IL | 手部动捕、SLAM 和三维场景联合采集灵巧示范 | [Paper](https://arxiv.org/abs/2403.07788) | [GitHub](https://github.com/j96w/DexCap) |
| Tilde / TeleHand | 2024 | Isomorphic Teleoperation / DP | 同构主手控制 DeltaHand，并以示范训练扩散策略 | [Paper](https://arxiv.org/abs/2405.18804) | — |
| Open-TeleVision | 2024 | XR Teleoperation / Bimanual | Vision Pro 沉浸式主动立体视觉双臂遥操 | [Paper](https://arxiv.org/abs/2407.01512) | [GitHub](https://github.com/OpenTeleVision/TeleVision) |
| Bunny-VisionPro | 2024 | XR Teleoperation / Bimanual Dexterity | 双臂双灵巧手重定向、触觉反馈和安全约束 | [Paper](https://arxiv.org/abs/2407.03162) | [GitHub](https://github.com/Dingry/BunnyVisionPro) |
| ACE | 2024 | Visual-Exoskeleton Teleoperation | 视觉手部跟踪与外骨骼腕部控制相结合的跨平台遥操 | [Paper](https://arxiv.org/abs/2408.11805) | — |
| BiDex: Bimanual Dexterity for Complex Tasks | 2024 | Leader-Follower / Glove Teleoperation | MANUS 手套与 teacher arms 采集高自由度双臂双手示范 | [Paper](https://arxiv.org/abs/2411.13677) | [GitHub](https://github.com/leap-hand/Bidex_Manus_Teleop) |
| TelePhantom | 2024 | Virtual-Assisted Teleoperation | 利用虚拟机器人预览和确认动作，提高遥操安全性 | [Paper](https://arxiv.org/abs/2412.13548) | — |
| DOGlove | 2025 | Haptic Glove / Teleoperation | 低成本 21-DoF 动捕、力反馈和指尖振动触觉手套 | [Paper](https://arxiv.org/abs/2502.07730) | [GitHub](https://github.com/TEA-Lab/DOGlove) |
| Exo-ViHa | 2025 | Exoskeleton / Visual-Haptic Teleoperation | 模块化外骨骼结合 SLAM、腕部视觉和动作捕捉手套 | [Paper](https://arxiv.org/abs/2503.01543) | — |
| DexUMI | 2025 | Wearable Interface / Embodiment Adaptation | 外骨骼、人手图像替换和 UMI 表示降低人手—机器人手差异 | [Paper](https://arxiv.org/abs/2505.21864) | [GitHub](https://github.com/real-stanford/DexUMI) |
| TeleOpBench | 2025 | Teleoperation Benchmark | 统一比较 MoCap、VR、外骨骼和单目视觉双臂遥操 | [Paper](https://arxiv.org/abs/2505.12748) | [GitHub](https://github.com/cyjdlhy/TeleOpBench) |
| GEX | 2025 | Exoskeleton / Isomorphic Teleoperation | 全驱动三指手与外骨骼手套构成低成本闭环遥操系统 | [Paper](https://arxiv.org/abs/2506.04982) | [GitHub](https://github.com/Democratizing-Dexterous/libgex) |
| Analyzing Key Objectives in Human-to-Robot Retargeting | 2025/2026 | Retargeting Analysis | 系统比较指尖、方向、位置等重定向目标的作用 | [Paper](https://arxiv.org/abs/2506.09384) | [GitHub](https://github.com/Mingrui-Yu/retargeting) |
| TypeTele | 2025 | Type-Guided Teleoperation | 引入灵巧操作类型库与 MLLM 检索，突破直接姿态模仿限制 | [Paper](https://arxiv.org/abs/2507.01857) | — |
| ByteDexter Teleoperation | 2025 | Glove Teleoperation / Retargeting | 手套驱动 20-DoF 灵巧手并实现臂手协调重定向 | [Paper](https://arxiv.org/abs/2507.03227) | — |
| Dexplore | 2025 | Reference-Guided Teleoperation / RL | 将人类参考动作、重定向和策略探索统一到神经控制框架 | [Paper](https://arxiv.org/abs/2509.09671) | — |
| GR-Dexter | 2025 | Bimanual Dexterous Teleoperation / VLA Data | 21-DoF 手、双臂遥操及多源数据训练体系 | [Paper](https://arxiv.org/abs/2512.24210) | — |
| UniBiDex | 2026 | Unified Bimanual Teleoperation | 统一 VR 与 leader–follower 输入，使用零空间优化保障双臂安全 | [Paper](https://arxiv.org/abs/2601.04629) | — |
| HumDex | 2026 | Whole-body Teleoperation / Retargeting | IMU 全身跟踪与学习式手部重定向，用人体运动预训练 | [Paper](https://arxiv.org/abs/2603.12260) | [GitHub](https://github.com/physical-superintelligence-lab/HumDex) |
| TeleDex: Accessible Dexterous Teleoperation | 2026 | Phone Teleoperation | 仅用手机输出腕部 6D 位姿和 21-DoF 手状态完成遥操 | [Paper](https://arxiv.org/abs/2603.17065) | — |
| DexTwist | 2026 | Retargeting / Twist Motion | 面向旋拧与手内转动的任务相关手部重定向 | [Paper](https://arxiv.org/abs/2605.12182) | — |
| RealDexUMI | 2026 | Wearable UMI / Zero-gap Data | 采集和部署共用同一灵巧末端、视觉与触觉模块 | [Paper](https://arxiv.org/abs/2606.06033) | — |
| Bilateral Teleoperation Framework | 2026 | Bilateral Teleoperation / Haptics | 臂手统一控制、多尺度触觉反馈与共享控制 | [Paper](https://arxiv.org/abs/2606.15434) | — |
| Force-Aware Bimanual Dexterous Teleoperation | 2026 | Bimanual Teleoperation / Force | 第一视角视觉、IK 重定向与力觉感知的双手遥操 | [Paper](https://arxiv.org/abs/2606.23431) | — |
| AnyDexRT | 2026 | Learning-based Retargeting | 自监督指尖对应、少量人类引导和接触分类的免标定重定向 | [Paper](https://arxiv.org/abs/2607.08341) | — |
| TeleDexter | 2026 | Object-centric Dexterous Teleoperation / RL | 人手—物体协同跟踪与学习式接触执行，实现手内换抓和工具使用 | [Paper](https://arxiv.org/abs/2607.11481) | — |
| AnyDexRetarget | 持续更新 | Retargeting Toolkit | 支持 Vision Pro、Quest、普通相机和多种灵巧手 | — | [GitHub](https://github.com/qqsq12321/AnyDexRetarget) |
| Unitree XR Teleoperate | 持续更新 | XR Teleoperation Toolkit | XR 控制 Unitree 机械臂与灵巧手并记录示范 | — | [GitHub](https://github.com/unitreerobotics/xr_teleoperate) |
| Fourier Teleoperation | 持续更新 | Humanoid Teleoperation Toolkit | 支持 Fourier 人形、灵巧手、XR 和相机数据采集 | — | [GitHub](https://github.com/FFTAI/teleoperation) |

## 3. 模仿学习、ACT、人体视频与动作策略

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| Learning Complex Dexterous Manipulation with Demonstrations (DAPG) | 2018 | RL from Demonstrations | 行为克隆初始化结合 Demo-Augmented Policy Gradient | [Paper](https://arxiv.org/abs/1709.10087) | [GitHub](https://github.com/aravindr93/hand_dapg) |
| DexVIP | 2022 | Human Video Prior / RL | 从网络人体视频提取手姿先验，指导灵巧抓取强化学习 | [Paper](https://arxiv.org/abs/2202.00164) | — |
| ACT | 2023 | Behavior Cloning / Transformer | Action Chunking Transformer 预测未来动作块并进行时间集成 | [Paper](https://arxiv.org/abs/2304.13705) | [GitHub](https://github.com/tonyzhaozh/act) |
| ALOHA | 2023 | Bimanual Imitation Learning | 低成本 leader–follower 双臂平台与 ACT 精细操作策略 | [Paper](https://arxiv.org/abs/2304.13705) | [GitHub](https://github.com/tonyzhaozh/aloha) |
| Mobile ALOHA | 2024 | Mobile Bimanual IL / ACT | 联合底盘、双臂和全身遥操数据的动作块行为克隆 | [Paper](https://arxiv.org/abs/2401.02117) | [GitHub](https://github.com/MarkFzp/mobile-aloha) |
| ACT++ | 2024 | ACT / DP Training Suite | 统一 ACT、Diffusion Policy、VINN 等双臂策略实现 | [Paper](https://mobile-aloha.github.io/) | [GitHub](https://github.com/MarkFzp/act-plus-plus) |
| ViViDex | 2024 | Human Video / RL-to-IL | 人体视频轨迹作为奖励训练状态策略，再蒸馏为视觉策略 | [Paper](https://arxiv.org/abs/2404.15709) | [GitHub](https://github.com/zerchen/vividex_sapien) |
| Learning Diverse Bimanual Dexterous Skills (BiDexHD) | 2024 | Bimanual IL / Teacher-Student | 从人体示范学习多种双臂双手技能并进行教师学生迁移 | [Paper](https://arxiv.org/abs/2410.02477) | — |
| DexMimicGen | 2024 | Bimanual IL / Demo Generation | 分解少量示范并在仿真中自动重组大规模双臂灵巧轨迹 | [Paper](https://arxiv.org/abs/2410.24185) | — |
| DexWild | 2025 | Human-Robot Co-training | 在多环境采集人手交互，与少量机器人示范联合训练 | [Paper](https://arxiv.org/abs/2505.07813) | — |
| EgoDex | 2025 | Egocentric Human Video / Pretraining | 大规模第一视角视频与三维手指跟踪用于灵巧策略预训练 | [Paper](https://arxiv.org/abs/2505.11709) | — |
| CordViP | 2025 | Correspondence-based Visuomotor Policy | 利用视觉对应关系提高真实灵巧操作的数据效率与泛化 | [Paper](https://arxiv.org/abs/2502.08449) | — |
| Interactive Imitation Learning for Dexterous Manipulation | 2025 | Interactive IL | 通过交互式示范补充失败与分布外状态 | [Paper](https://arxiv.org/abs/2506.00098) | — |
| RwoR | 2025 | Human-hand Data / Robot-free Policy Learning | 从人手采集生成机器人视觉与 SE(3) 动作示范 | [Paper](https://arxiv.org/abs/2507.03930) | — |
| DexMan | 2025 | Human/Generated Video / Bimanual RL | 从第三视角人体或生成视频恢复交互并训练双臂灵巧策略 | [Paper](https://arxiv.org/abs/2510.08475) | — |
| Dexplore | 2025 | Human Demonstration / Reference-guided RL | 以参考范围引导策略探索而非逐帧刚性模仿 | [Paper](https://arxiv.org/abs/2509.09671) | — |
| Object-Focus Actor | 2025 | Hierarchical IL / Dexterity | 先到达预操作位，再以对象中心策略执行灵巧技能 | [Paper](https://arxiv.org/abs/2505.15098) | — |
| DemoBot | 2026 | Human RGB-D Video / Bimanual RL | 从单条第三视角视频提取双手物体轨迹并用残差 RL 精炼 | [Paper](https://arxiv.org/abs/2601.01651) | — |
| DexImit | 2026 | Monocular Human Video / Bimanual Data Generation | 重建手物交互、分解子任务、合成机器人轨迹并增强 | [Paper](https://arxiv.org/abs/2602.10105) | — |
| VideoManip | 2026 | RGB Human Video / 4D Reconstruction | 重建四维手物轨迹、接触优化并生成真实机器人策略数据 | [Paper](https://arxiv.org/abs/2602.09013) | — |
| EgoScale | 2026 | Large-scale Human Video Pretraining | 研究大规模第一视角人体数据对灵巧策略的可预测扩展规律 | [Paper](https://arxiv.org/abs/2602.16710) | — |
| Structural Action Transformer | 2026 | 3D IL / Flow Matching | 将动作块表示为可变长度关节轨迹集合，支持跨手型学习 | [Paper](https://arxiv.org/abs/2603.03960) | — |
| UniDex: Robot Foundation Suite | 2026 | Foundation Suite / Human Data | 利用人手与机器人手结构相似性扩展通用灵巧预训练 | [Paper](https://arxiv.org/abs/2603.22264) | — |
| EgoAERO | 2026 | Single Egocentric RGB-D Demo / Residual RL | 无需 CAD 资产重建接触一致轨迹并从单示范学习 | [Paper](https://arxiv.org/abs/2606.08057) | — |
| Dexterous Point Policy | 2026 | Human Video / 3D Keypoint Policy | 以统一腕部和指尖三维关键点跨越人机本体差异 | [Paper](https://arxiv.org/abs/2606.10614) | — |
| V2P-Manip | 2026 | Monocular Human Video / Policy Learning | 从单目人体示范恢复物理可行轨迹并训练灵巧策略 | [Paper](https://arxiv.org/abs/2606.16436) | — |
| Do as I Do | 2026 | Everyday Human Video / Retargeting | 从第一或第三视角普通视频重建并生成机器人完整动作数据 | [Paper](https://arxiv.org/abs/2606.19333) | — |
| DexPIE | 2026 | Real-world Policy Improvement | 从真实执行经验稳定改进灵巧策略，缓解 BC 累积误差 | [Paper](https://arxiv.org/abs/2606.09615) | — |

## 4. Diffusion Policy、Flow Matching 与生成式动作模型

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| Diffusion Policy | 2023 | Diffusion Action Policy | 条件扩散建模多模态连续动作序列并滚动执行 | [Paper](https://arxiv.org/abs/2303.04137) | [GitHub](https://github.com/real-stanford/diffusion_policy) |
| 3D Diffusion Policy (DP3) | 2024 | Point Cloud Diffusion Policy | 紧凑三维点云表征条件下生成机器人动作序列 | [Paper](https://arxiv.org/abs/2403.03954) | [GitHub](https://github.com/YanjieZe/3D-Diffusion-Policy) |
| Tilde | 2024 | Dexterous Diffusion Policy | 使用真实同构遥操数据学习七类手内操作闭环策略 | [Paper](https://arxiv.org/abs/2405.18804) | — |
| VLA + Diffusion Policy Switching | 2024 | Hierarchical VLA / DP | VLA 处理远距离语义动作，DP 处理近物体精细接触 | [Paper](https://arxiv.org/abs/2410.14022) | — |
| RDT-1B | 2024 | Diffusion Transformer / Bimanual | 语言、视觉和状态条件下的大规模双臂动作生成 | [Paper](https://arxiv.org/abs/2410.07864) | [GitHub](https://github.com/thu-ml/RoboticsDiffusionTransformer) |
| UniDexFPM | 2024 | Diffusion Policy / Functional Pre-grasp | 多专家蒸馏结合扩散策略生成和执行功能性预抓取 | [Paper](https://arxiv.org/abs/2403.12421) | — |
| VTAO-BiManip | 2025 | Visual-Tactile-Action Pretraining | 遮掩式视觉触觉动作预训练与双臂灵巧课程学习 | [Paper](https://arxiv.org/abs/2501.03606) | — |
| DexGraspVLA | 2025 | Hierarchical VLA / Diffusion Controller | VLM 高层规划结合低层扩散策略完成通用灵巧抓取 | [Paper](https://arxiv.org/abs/2502.20900) | [GitHub](https://github.com/Psi-Robot/DexGraspVLA) |
| Visuomotor Diffusion for In-Hand Manipulation | 2025 | Dexterous Visuomotor Diffusion | 从视觉和本体状态生成手内操作动作块 | [Paper](https://arxiv.org/abs/2503.02587) | — |
| DexGrasp Anything | 2025 | Diffusion / Dexterous Grasp Generation | 物理感知的通用灵巧抓取生成 | [Paper](https://arxiv.org/abs/2503.08257) | — |
| ManiDP | 2025 | Manipulability-aware Diffusion | 将双臂操作度和姿态依赖约束融入扩散策略 | [Paper](https://arxiv.org/abs/2510.23016) | — |
| End-to-End Arm-Hand VLA via Shared Control | 2025 | VLA / Diffusion Action Expert | 共享控制辅助遥操采集并训练端到端臂手 VLA | [Paper](https://arxiv.org/abs/2511.00139) | — |
| Dexora | 2026 | Bimanual Diffusion Transformer / VLA | 质量加权真实与仿真数据训练高 DoF 双臂双手策略 | [Paper](https://arxiv.org/abs/2605.18722) | [GitHub](https://github.com/ZZongzheng0918/Dexora) |
| Structural Action Transformer | 2026 | Flow Matching / Cross-Embodiment | 以连续时间 flow matching 生成异构关节轨迹 | [Paper](https://arxiv.org/abs/2603.03960) | — |
| Decoupled Multimodal Diffusion Transformer | 2026 | Visual-Tactile Bimanual Diffusion | 解耦视觉、本体和触觉通道的双臂动作生成 | [Paper](https://arxiv.org/abs/2602.05513) | — |
| MoDex | 2026 | Diffusion / Sequential Multi-object Grasping | 面向连续多物体灵巧抓取的扩散动作策略 | [Paper](https://arxiv.org/abs/2606.05407) | — |
| DexFuture | 2026 | Future-state Visuomotor Policy | 分层预测未来视觉目标并生成灵巧动作 | [Paper](https://arxiv.org/abs/2606.05699) | — |

## 5. VLA、VLM 与灵巧操作基础模型

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| OpenVLA | 2024 | General VLA | 开源 7B VLA，以视觉语言模型输出离散机器人动作 | [Paper](https://arxiv.org/abs/2406.09246) | [GitHub](https://github.com/openvla/openvla) |
| Octo | 2024 | Generalist Robot Policy | 跨机器人数据预训练的通用视觉动作 Transformer | [Paper](https://arxiv.org/abs/2405.12213) | [GitHub](https://github.com/octo-models/octo) |
| π₀ / OpenPI | 2024 | VLA / Flow Matching | 视觉语言骨干结合 flow-matching action expert | [Paper](https://www.physicalintelligence.company/blog/pi0) | [GitHub](https://github.com/Physical-Intelligence/openpi) |
| RDT-1B | 2024 | Bimanual Foundation Policy | 统一多模态条件和双臂动作表示的扩散 Transformer | [Paper](https://arxiv.org/abs/2410.07864) | [GitHub](https://github.com/thu-ml/RoboticsDiffusionTransformer) |
| VLA + Diffusion Policy Switching | 2024 | Dexterous VLA / Hierarchical Control | 语言高层策略与多指手低层扩散策略事件切换 | [Paper](https://arxiv.org/abs/2410.14022) | — |
| DexGraspVLA | 2025 | Dexterous VLA | VLM 规划、域不变视觉表征和扩散动作控制 | [Paper](https://arxiv.org/abs/2502.20900) | [GitHub](https://github.com/Psi-Robot/DexGraspVLA) |
| RoboDexVLM | 2025 | VLM Planning / Dexterous Skills | VLM 任务规划、技能库、记忆与长时任务重规划 | [Paper](https://arxiv.org/abs/2503.01616) | [GitHub](https://github.com/henryhcliu/robodex_vlm) |
| Being-H0 | 2025 | Human-video Dexterous VLA | 从大规模人体视频显式建模手部动作并迁移到机器人 | [Paper](https://arxiv.org/abs/2507.15597) | [GitHub](https://github.com/BeingBeyond/Being-H) |
| VITRA | 2025 | Human-video VLA Pretraining | 将无标注第一视角人体视频转换为 VLA 对齐训练数据 | [Paper](https://arxiv.org/abs/2510.21571) | [GitHub](https://github.com/microsoft/VITRA) |
| GR-Dexter | 2025 | Bimanual Dexterous VLA | 多源数据训练双臂双 21-DoF 手语言条件策略 | [Paper](https://arxiv.org/abs/2512.24210) | — |
| Being-H0.5 | 2026 | Cross-Embodiment VLA / Mixture of Flow | 共享动作语言与 embodiment-specific flow experts | [Paper](https://research.beingbeyond.com/being-h05) | [GitHub](https://github.com/BeingBeyond/Being-H) |
| InternVLA-A1 | 2026 | VLA / Imagination | 融合 MLLM 理解、世界模型式想象和动作生成 | [Paper](https://arxiv.org/abs/2601.02456) | — |
| UniHM | 2026 | Language-guided Dexterous Manipulation | 统一不同灵巧手的离散动作 token，并用语言生成人手操作序列 | [Paper](https://arxiv.org/abs/2603.00732) | — |
| XL-VLA | 2026 | Cross-Hand Latent VLA | 建立不同灵巧手共享的 latent action space | [Paper](https://arxiv.org/abs/2603.10158) | — |
| DexHiL | 2026 | Dexterous VLA Post-training | 臂手联合在线纠错与干预感知的数据加权后训练 | [Paper](https://arxiv.org/abs/2603.09121) | — |
| HandITL | 2026 | Bimanual Dexterous VLA Intervention | 分离臂残差与手相对重定向，实现平滑人工接管 | [Paper](https://arxiv.org/abs/2605.15157) | — |
| Dexora | 2026 | Open-source Bimanual Dexterous VLA | 真实与 MuJoCo 数据联合训练双臂双手端到端 VLA | [Paper](https://arxiv.org/abs/2605.18722) | [GitHub](https://github.com/ZZongzheng0918/Dexora) |
| InDex | 2026 | Intent-conditioned Dexterous VLA | 通过意图条件和层级动作适配通用 VLA 到高维灵巧手 | [Paper](https://arxiv.org/abs/2606.12109) | — |
| Dexterous Point Policy | 2026 | Human-video Foundation Policy | 以三维关键点动作表示直接从人类视频迁移到多指手 | [Paper](https://arxiv.org/abs/2606.10614) | — |
| EgoSteer | 2026 | Steerable Dexterous VLA | 从第一视角人体视频规模化预训练并支持语言可控后训练 | [Paper](https://arxiv.org/abs/2607.09701) | — |
| TouchWorld | 2026 | Tactile Dexterous Foundation Model | VLA 高层规划、触觉目标预测与高频触觉残差控制 | [Paper](https://arxiv.org/abs/2607.07287) | — |
| NVIDIA GR00T N1 | 2025 | Humanoid VLA Foundation Model | VLM System-2 与 diffusion System-1 的人形动作模型 | [Paper](https://arxiv.org/abs/2503.14734) | [GitHub](https://github.com/NVIDIA/Isaac-GR00T) |

## 6. World Model、World Action Model 与视频预测

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| Unified World Models | 2025 | World Model / Action Model | 在同一 Transformer 中联合建模视频扩散与动作扩散 | [Paper](https://arxiv.org/abs/2504.02792) | — |
| MAPLE | 2025 | Human Video Predictive Model | 从第一视角交互学习未来手部运动和接触预测 | [Paper](https://arxiv.org/abs/2504.06084) | — |
| DexWM | 2025 | Latent Dexterous World Model | 从 900+ 小时人体与机器人视频学习动作条件 latent dynamics | [Paper](https://arxiv.org/abs/2512.13644) | [GitHub](https://github.com/facebookresearch/dexwm) |
| Dexterous World Models (DWM) | 2025 | Scene-action Video World Model | 静态三维场景与手部动作条件的视频扩散交互模型 | [Paper](https://arxiv.org/abs/2512.17907) | — |
| DreamDojo | 2026 | Foundation Robot World Model | 从大规模人体视频学习跨任务、跨本体操作视频模型 | [Paper](https://arxiv.org/abs/2602.06949) | — |
| InternVLA-A1 | 2026 | World-model-augmented VLA | 用想象模块预测未来视觉结果以辅助动作生成 | [Paper](https://arxiv.org/abs/2601.02456) | — |
| DexFuture | 2026 | Future-state Model / Policy | 预测层级未来视觉状态作为灵巧策略目标 | [Paper](https://arxiv.org/abs/2606.05699) | — |
| Dream-Tac | 2026 | Tactile World Action Model | 联合生成动作、未来视觉观测和触觉动态 | [Paper](https://arxiv.org/abs/2606.08737) | — |
| TouchWorld | 2026 | Tactile World Model / Foundation Policy | 预测接触目标并用高频触觉残差进行反应式修正 | [Paper](https://arxiv.org/abs/2607.07287) | — |
| Tactile-WAM | 2026 | Touch-aware World Action Model | 预测未来触觉接触状态并选择性路由触觉到动作去噪 | [Paper](https://arxiv.org/abs/2606.26663) | — |
| Not All Actions Are Equal | 2026 | Dexterous World Model Conditioning | 研究不同动作条件表示对灵巧视频世界模型的影响 | [Paper](https://arxiv.org/abs/2606.27325) | — |
| FBI | 2025 | Visual-Tactile Dynamics / Fast Diffusion | 学习动态感知 latent 并以单步 diffusion 实时生成动作 | [Paper](https://arxiv.org/abs/2508.14441) | — |

## 7. Real-to-Sim、Sim-to-Real、数据生成与跨本体迁移

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| RialTo | 2024 | Real-to-Sim-to-Real | 真实扫描建数字孪生，导入示范后用仿真 RL 增强鲁棒性 | [Paper](https://arxiv.org/abs/2403.03949) | — |
| DexMimicGen | 2024 | Real-to-Sim-to-Real / Demo Augmentation | 从少量真实示范生成大量双臂灵巧仿真数据 | [Paper](https://arxiv.org/abs/2410.24185) | — |
| ManipTrans | 2025 | Bimanual Motion Transfer / Residual RL | 人体双手动作重定向与残差策略优化物理可行性 | [Paper](https://arxiv.org/abs/2503.21860) | [GitHub](https://github.com/ManipTrans/ManipTrans) |
| Sim-and-Real Co-Training | 2025 | Sim-Real Joint Training | 真实数据、任务数字孪生数据和通用仿真数据联合训练 | [Paper](https://arxiv.org/abs/2503.24361) | — |
| HumanoidGen | 2025 | LLM Data Generation / Bimanual Dexterity | LLM 推理驱动场景生成、示范采集与数据泛化 | [Paper](https://arxiv.org/abs/2507.00833) | — |
| HERMES | 2025 | Human-to-Robot / Mobile Dexterity | 融合多源人体动作，通过 RL 转换为移动灵巧机器人行为 | [Paper](https://arxiv.org/abs/2508.20085) | — |
| DexMan | 2025 | Human/Generated Video to Simulation | 从真实或生成视频提取双臂双手技能并在仿真学习 | [Paper](https://arxiv.org/abs/2510.08475) | — |
| Gen2Real | 2025 | Generated Video to Real | 从生成式人体视频提取轨迹，经物理优化和残差 PPO 部署 | [Paper](https://arxiv.org/abs/2509.14178) | — |
| DexSim2Real² | 2025 | RGB-D Real-to-Sim / MPC | 显式重建物体，在仿真中优化动作后迁移到真实灵巧手 | [Paper](https://github.com/jiangtaoran/DexSim2Real2) | [GitHub](https://github.com/jiangtaoran/DexSim2Real2) |
| DemoBot | 2026 | Video-to-Sim / Residual RL | 人体视频运动先验结合接触密集残差强化学习 | [Paper](https://arxiv.org/abs/2601.01651) | — |
| DexImit | 2026 | Video-to-Robot Data Generation | 从单目视频自动生成物理可行双臂双手轨迹 | [Paper](https://arxiv.org/abs/2602.10105) | — |
| VideoManip | 2026 | Human Video to Real Robot | 四维重建、接触优化、示范合成并部署实体多指手 | [Paper](https://arxiv.org/abs/2602.09013) | — |
| EgoAERO | 2026 | Asset-free Real-to-Sim | 单条 RGB-D 人体示范中无 CAD 重建对象和接触轨迹 | [Paper](https://arxiv.org/abs/2606.08057) | — |
| V2P-Manip | 2026 | Video-to-Physics Policy | 从单目视频构建视觉一致且物理可行的灵巧操作训练数据 | [Paper](https://arxiv.org/abs/2606.16436) | — |
| Do as I Do | 2026 | In-the-wild Video Retargeting | 从日常人体视频生成多指机器人可执行的完整数据 | [Paper](https://arxiv.org/abs/2606.19333) | — |
| Dexora | 2026 | Digital Twin / Sim-Real VLA | 同一遥操接口驱动物理机器人与 MuJoCo 数字孪生 | [Paper](https://arxiv.org/abs/2605.18722) | [GitHub](https://github.com/ZZongzheng0918/Dexora) |

## 8. 人类在环、后训练、触觉与接触策略

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| HIL-SERL | 2024 | Human-in-the-Loop RL | 示范初始化、真实机器人自主学习和人工关键时刻干预 | [Paper](https://arxiv.org/abs/2410.21845) | — |
| DexCap / DexIL | 2024 | Interactive IL | 人体动捕示范与机器人在线纠错数据联合学习 | [Paper](https://arxiv.org/abs/2403.07788) | [GitHub](https://github.com/j96w/DexCap) |
| VTAO-BiManip | 2025 | Visual-Tactile-Action Pretraining | 用人体视觉触觉数据预训练双臂灵巧策略 | [Paper](https://arxiv.org/abs/2501.03606) | — |
| KineDex | 2025 | Tactile-informed Visuomotor Policy | 从触觉信息学习接触感知的视觉动作策略 | [Paper](https://proceedings.mlr.press/v305/zhang25l.html) | — |
| DexHiL | 2026 | Human-in-the-Loop VLA | 针对臂手联合 VLA 的实时接管和纠错片段加权后训练 | [Paper](https://arxiv.org/abs/2603.09121) | — |
| HandITL | 2026 | Seamless VLA Intervention | 维持现有接触的高维双手人工无跳变纠错 | [Paper](https://arxiv.org/abs/2605.15157) | — |
| DexPIE | 2026 | Real-world RL Post-training | 从真实经验和策略执行数据稳定提升灵巧操作 | [Paper](https://arxiv.org/abs/2606.09615) | — |
| DexTac | 2026 | Contact-aware Visuotactile Policy | 从人体示范采集接触力和区域，学习主动接触选择 | [Paper](https://arxiv.org/abs/2601.21474) | — |
| TransDex | 2026 | 3D Visuo-Tactile Policy | 点云重建预训练融合视觉、触觉和本体状态 | [Paper](https://arxiv.org/abs/2603.13869) | — |
| T-Rex | 2026 | Tactile-Reactive Dexterous Policy | 语言视觉策略结合高频触觉反应控制 | [Paper](https://arxiv.org/abs/2606.17055) | — |
| Dream-Tac | 2026 | Tactile World Action Model | 触觉动态预测与动作生成统一建模 | [Paper](https://arxiv.org/abs/2606.08737) | — |
| Tactile-WAM | 2026 | Touch-aware WAM | 预测触觉接触并辅助动作去噪 | [Paper](https://arxiv.org/abs/2606.26663) | — |
| TouchWorld | 2026 | Tactile Foundation Model | 预测触觉目标、视觉触觉动作生成和在线残差修正 | [Paper](https://arxiv.org/abs/2607.07287) | — |
| Pseudo-Tactile Contact Estimation | 2026 | Vision-Proprioception Contact Estimation | 从第一视角 RGB-D 与本体状态估计每个指尖接触 | [Paper](https://arxiv.org/abs/2606.24450) | — |
| Human-Centric Transferable Tactile Pre-training | 2026 | Tactile Pretraining / VLA | 利用人体触觉数据预训练可迁移的接触感知策略 | [Paper](https://arxiv.org/abs/2607.01067) | — |

## 9. 数据集、基准与大规模数据资源

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| DexGraspNet | 2022 | Synthetic Dexterous Grasp Dataset | 大规模对象、多指手抓取姿态与点云数据 | [Paper](https://arxiv.org/abs/2210.02697) | [GitHub](https://github.com/PKU-EPIC/DexGraspNet) |
| Bi-DexHands | 2022 | Bimanual Dexterous RL Benchmark | Isaac Gym 双灵巧手多任务强化学习基准 | [Paper](https://arxiv.org/abs/2206.08686) | [GitHub](https://github.com/PKU-MARL/DexterousHands) |
| DexCap Data | 2024 | Human Mocap Dataset | 人体手腕、手指、三维场景和操作示范数据 | [Paper](https://arxiv.org/abs/2403.07788) | [GitHub](https://github.com/j96w/DexCap) |
| TeleOpBench | 2025 | Teleoperation Benchmark | 30 个双臂灵巧环境和四类遥操输入对比 | [Paper](https://arxiv.org/abs/2505.12748) | [GitHub](https://github.com/cyjdlhy/TeleOpBench) |
| DexWild Dataset | 2025 | In-the-wild Human Interaction Data | 跨对象、任务和场景的人手交互示范 | [Paper](https://arxiv.org/abs/2505.07813) | — |
| EgoDex | 2025 | Egocentric Dexterous Video Dataset | 829 小时第一视角视频与三维手指跟踪 | [Paper](https://arxiv.org/abs/2505.11709) | — |
| OpenEgo | 2025 | Multimodal Egocentric Dataset | 面向灵巧操作的大规模多模态第一视角数据 | [Paper](https://arxiv.org/abs/2509.05513) | — |
| VITRA Human Hand VLA Data | 2025 | Human-video VLA Dataset | 超过百万 episode 的无标注人手 VLA 对齐数据 | [Paper](https://arxiv.org/abs/2510.21571) | [GitHub](https://github.com/microsoft/VITRA) |
| GigaHands | 2024/2025 | Bimanual Human Activity Dataset | 大规模双手活动视频和手物交互标注 | [Paper](https://arxiv.org/abs/2412.04244) | — |
| HumanoidGen | 2025 | Synthetic Bimanual Dataset Generator | 自动生成场景、任务和双臂灵巧示范 | [Paper](https://arxiv.org/abs/2507.00833) | — |
| DexMimicGen Environments | 2024 | Synthetic Demonstration Benchmark | 双臂灵巧任务环境和自动生成轨迹 | [Paper](https://arxiv.org/abs/2410.24185) | — |
| EgoDex-R | 2026 | Egocentric RGB-D Dataset | 430 万 RGB-D 帧及灵巧策略学习数据 | [Paper](https://arxiv.org/abs/2606.08057) | — |
| BiDexGrasp | 2026 | Bimanual Dexterous Grasp Dataset | 6351 对象、970 万双手协调抓取标注 | [Paper](https://arxiv.org/abs/2604.06589) | — |
| TactiDex | 2026 | Tactile Dexterous Benchmark | 真实触觉引导的灵巧操作数据与评测基准 | [Paper](https://arxiv.org/abs/2607.09190) | — |

## 10. Ego Manipulation 数据集与基准

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| EPIC-KITCHENS-100 | 2020 | Egocentric Action Dataset | 大规模厨房第一视角视频，提供动作、对象与叙述标注 | [Paper](https://arxiv.org/abs/2006.13256) | [GitHub](https://github.com/epic-kitchens/epic-kitchens-100-annotations) |
| Ego4D | 2021/2022 | Large-scale Egocentric Dataset | 覆盖日常活动、手物交互、预测和记忆任务的大规模第一视角数据 | [Paper](https://arxiv.org/abs/2110.07058) | [GitHub](https://github.com/facebookresearch/Ego4d) |
| H2O | 2021 | Egocentric 3D Hand-Object Dataset | 同步 RGB-D、双手三维姿态、物体 6D 姿态与交互标签 | [Paper](https://arxiv.org/abs/2104.11181) | [GitHub](https://github.com/taeinkwon/h2odataset) |
| HOI4D | 2022 | 4D Egocentric HOI Dataset | RGB-D 第一视角序列、手姿态、对象姿态和类别级交互标注 | [Paper](https://arxiv.org/abs/2203.01577) | [GitHub](https://github.com/leolyliu/HOI4D-Instructions) |
| Assembly101 | 2022 | Ego-Exo Procedural Dataset | 同步多视角与第一视角装配视频，包含错误、纠正和手部姿态 | [Paper](https://arxiv.org/abs/2203.14712) | [GitHub](https://github.com/assembly-101/assembly101-download-scripts) |
| OakInk | 2022 | Hand-Object Affordance Dataset | 对象 affordance、意图和多模态手物交互知识库 | [Paper](https://arxiv.org/abs/2203.15709) | [GitHub](https://github.com/oakink/OakInk) |
| ARCTIC | 2023 | Egocentric Bimanual HOI Dataset | 双手操作关节物体，提供手物网格和动态接触标注 | [Paper](https://arxiv.org/abs/2204.13662) | [GitHub](https://github.com/zc-alexfan/arctic) |
| HoloAssist | 2023 | Egocentric Interactive Assistance Dataset | 混合现实头显采集多模态操作者—指导者交互、错误和干预标注 | [Paper](https://arxiv.org/abs/2309.17024) | [GitHub](https://github.com/Ember-HoloAssist/holoassist-release) |
| Ego-Exo4D | 2023/2024 | Paired Ego-Exo Dataset | 同步第一和第三视角的技能活动、语言、姿态与多模态数据 | [Paper](https://arxiv.org/abs/2311.18259) | [GitHub](https://github.com/facebookresearch/Ego4d) |
| TACO | 2024 | Ego-Exo Bimanual Tool Dataset | 工具—动作—对象组合的双手交互和三维手物网格 | [Paper](https://arxiv.org/abs/2401.08399) | [GitHub](https://github.com/leolyliu/TACO-Instructions) |
| OAKINK2 | 2024 | Bimanual Complex-task Dataset | 以 affordance、原子任务和复杂任务组织双手对象操作 | [Paper](https://arxiv.org/abs/2403.19417) | — |
| HANDS23 | 2024 | Egocentric Hand-Object Benchmark | 基于 AssemblyHands 与 ARCTIC 的手和手物三维重建挑战 | [Paper](https://arxiv.org/abs/2403.16428) | — |
| HO-Cap | 2024/2025 | Egocentric Hand-Object Capture Dataset | 多 RGB-D 与 HoloLens 采集手物重建、位姿跟踪及操作示范 | [Paper](https://arxiv.org/abs/2406.06843) | — |
| HOT3D | 2024/2025 | Egocentric 3D Hand-Object Tracking Dataset | Aria 与 Quest 采集多视角第一人称手物跟踪、眼动和点云 | [Paper](https://arxiv.org/abs/2406.09598) | [GitHub](https://github.com/facebookresearch/hot3d) |
| GigaHands | 2024/2025 | Large-scale Bimanual Human Dataset | 大规模双手活动视频、手物交互与语言标注 | [Paper](https://arxiv.org/abs/2412.04244) | — |
| EgoDex | 2025 | Egocentric Dexterous Dataset | Vision Pro 采集 829 小时第一视角视频、全身/双手三维姿态与语言 | [Paper](https://arxiv.org/abs/2505.11709) | [GitHub](https://github.com/apple/ml-egodex) |
| OpenEgo | 2025 | Unified Egocentric Manipulation Dataset | 统一六个第一视角数据集的 MANO 手姿态和意图对齐动作原语 | [Paper](https://arxiv.org/abs/2509.05513) | [GitHub](https://github.com/ahadjawaid/openego) |
| EgoDex-R | 2026 | Egocentric RGB-D Robot-learning Dataset | 面向单示范灵巧策略学习的大规模第一视角 RGB-D 数据 | [Paper](https://arxiv.org/abs/2606.08057) | — |


## 11. Ego 表征、手物感知与三维重建

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| H+O | 2019 | Egocentric Hand-Object Recognition | 联合估计双手、物体三维姿态和第一视角交互类别 | [Paper](https://arxiv.org/abs/1904.05349) | — |
| R3M | 2022 | Ego-video Representation Pretraining | 在 Ego4D 人体视频上进行时间、语言和稀疏表示预训练 | [Paper](https://arxiv.org/abs/2203.12601) | [GitHub](https://github.com/facebookresearch/r3m) |
| MVP | 2022 | Masked Visual Pretraining | 使用大规模人体视频进行 masked visual pretraining 以支持机器人控制 | [Paper](https://arxiv.org/abs/2203.06173) | [GitHub](https://github.com/ir413/mvp) |
| VIP | 2022/2023 | Value-Implicit Video Pretraining | 从人体视频学习具有时间和任务进度结构的视觉价值表征 | [Paper](https://arxiv.org/abs/2210.00030) | [GitHub](https://github.com/facebookresearch/vip) |
| LIV | 2023 | Language-Image Representation / Reward | 联合语言和人体视频学习机器人控制表征与奖励 | [Paper](https://arxiv.org/abs/2306.00958) | [GitHub](https://github.com/peterchenwang/LIV) |
| CaRe-Ego | 2024 | Egocentric Hand-Object Segmentation | 以接触关系建模交互手和被操作对象的分割 | [Paper](https://arxiv.org/abs/2407.05576) | — |
| HaWoR | 2025 | World-space Hand Reconstruction | 将相机空间手部恢复、ego-SLAM 和轨迹补全结合到世界坐标 | [Paper](https://arxiv.org/abs/2501.02973) | [GitHub](https://github.com/ThunderVVV/HaWoR) |
| EgoHandICL | 2026 | Egocentric 3D Hand Reconstruction | 使用视觉语言引导的 in-context learning 提高遮挡和未知场景鲁棒性 | [Paper](https://arxiv.org/abs/2601.19850) | — |
| EgoGrasp | 2026 | World-space Hand-Object Reconstruction | 结合身体先验和扩散补全恢复动态相机下的世界坐标手物交互 | [Paper](https://arxiv.org/abs/2601.01050) | — |
| WHOLE | 2026 | Holistic Hand-Object Reconstruction | 用生成式手物运动先验联合恢复世界空间手和对象轨迹 | [Paper](https://arxiv.org/abs/2602.22209) | — |
| StableHand | 2026 | Dual-hand Motion Estimation | 以质量感知 flow matching 恢复世界坐标双手运动 | [Paper](https://huajian-zeng.github.io/projects/stablehand/) | — |
| HOI-DETR | 2026 | Hand-Object Interaction Detection | 从单幅 RGB 检测手、直接对象、工具作用对象及交互关系 | [Paper](https://arxiv.org/abs/2606.17384) | [GitHub](https://github.com/AhmadDarKhalil/HOI-DETR) |


## 12. Ego-to-Robot、模仿学习与 VLA

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| Universal Manipulation Interface (UMI) | 2024 | Egocentric Demonstration Interface | 手持式夹爪相机采集第一视角动作，并以相对轨迹训练策略 | [Paper](https://arxiv.org/abs/2402.10329) | [GitHub](https://github.com/real-stanford/universal_manipulation_interface) |
| R+X | 2024/2025 | Retrieval / In-context Imitation | 从长时无标注第一视角视频检索技能并即时执行 | [Paper](https://arxiv.org/abs/2407.12957) | [GitHub](https://github.com/gpapagiannis/r-plus-x-hand2actions) |
| EgoMimic | 2024 | Human-Robot Co-training | 将 Aria 人体第一视角示范与机器人遥操数据对齐并联合训练 | [Paper](https://arxiv.org/abs/2410.24221) | — |
| DexUMI | 2025 | Egocentric Dexterous Demonstration | 穿戴式第一视角、外骨骼手和视觉替换实现人手到机器人手迁移 | [Paper](https://arxiv.org/abs/2505.21864) | [GitHub](https://github.com/real-stanford/DexUMI) |
| EgoVLA | 2025 | Egocentric VLA | 在人类第一视角数据上预测腕部与 MANO 动作，再以少量机器人数据微调 | [Paper](https://arxiv.org/abs/2507.12440) | [GitHub](https://github.com/RchalYang/EgoVLA_Release) |
| VITRA | 2025 | Egocentric Human-video VLA | 自动分割、描述并恢复第一视角人手动作，构建百万级 VLA 数据 | [Paper](https://arxiv.org/abs/2510.21571) | [GitHub](https://github.com/microsoft/VITRA) |
| RwoR | 2025 | Robot-free Policy Learning | 从人体第一视角视频生成机器人观测与相对 SE(3) 动作数据 | [Paper](https://arxiv.org/abs/2503.00779) | — |
| UniSkill | 2025 | Cross-Embodiment Human-video Imitation | 从人体视频学习跨本体技能表示并适配机器人执行 | [Paper](https://arxiv.org/abs/2505.08787) | — |
| Being-H0 | 2025 | Egocentric Dexterous VLA | 显式建模人手动作，以人体第一视角数据预训练高自由度策略 | [Paper](https://arxiv.org/abs/2507.15597) | [GitHub](https://github.com/BeingBeyond/Being-H) |
| EgoScale | 2026 | Scaling Egocentric Dexterous VLA | 20k+ 小时人体第一视角预训练、对齐中训和少量机器人后训练 | [Paper](https://arxiv.org/abs/2602.16710) | — |
| EgoAVFlow | 2026 | Ego Policy / Active Vision | 通过共享三维 flow 联合学习操作动作和主动相机视角 | [Paper](https://arxiv.org/abs/2602.22461) | — |
| UniDex Robot Foundation Suite | 2026 | Egocentric Cross-hand Foundation Policy | 从 H2O、HOI4D、HOT3D 等第一视角视频学习跨灵巧手控制 | [Paper](https://arxiv.org/abs/2603.22264) | [GitHub](https://github.com/unidex-ai/UniDex) |
| EgoHumanoid | 2026 | Egocentric Human-Robot Co-training VLA | 联合大量人体第一视角示范和少量人形机器人数据训练 VLA | [Paper](https://github.com/OpenDriveLab/EgoHumanoid) | [GitHub](https://github.com/OpenDriveLab/EgoHumanoid) |
| HumanEgo | 2026 | Robot-data-free Ego Policy / Flow Matching | 以交互中心 token 和密集辅助目标从分钟级人体视频零样本迁移 | [Paper](https://arxiv.org/abs/2605.24934) | — |
| EgoAERO | 2026 | Single Ego RGB-D / Residual RL | 无需对象 CAD，从单条第一视角 RGB-D 示范恢复接触轨迹和策略 | [Paper](https://arxiv.org/abs/2606.08057) | — |
| EgoEngine | 2026 | Ego Video-to-Robot Data Engine | 将人体第一视角视频转换为机器人外观视频和可执行动作轨迹 | [Paper](https://arxiv.org/abs/2606.12604) | — |
| Co-training with Egocentric Walking Video | 2026 | Ego-to-Mobile Robot Imitation | 将第一视角行走视频的相机轨迹转换为移动机器人动作并联合训练 | [Paper](https://arxiv.org/abs/2606.01951) | — |


## 13. Ego World Model 与交互视频生成

| 工作 | 年份 | 分类 | 方法 | Paper | GitHub |
|---|---:|---|---|---|---|
| DexWM | 2025 | Dexterous Latent World Model | 从人体与机器人视频学习动作条件的手物交互 latent dynamics | [Paper](https://arxiv.org/abs/2512.13644) | [GitHub](https://github.com/facebookresearch/dexwm) |
| EgoWM | 2026 | Action-conditioned Egocentric World Model | 为预训练视频扩散模型加入轻量动作条件，预测第一视角未来视频 | [Paper](https://egowm.github.io/) | — |
| EgoHOI | 2026 | Egocentric HOI World Model | 以三维几何和运动学先验约束动作驱动的接触一致视频生成 | [Paper](https://arxiv.org/abs/2603.13615) | — |
| Hand2World | 2026 | Interactive Egocentric World Model | 以三维手网格和相机几何控制自回归第一视角交互生成 | [Paper](https://arxiv.org/abs/2602.09600) | — |
| WHOLE | 2026 | Generative Hand-Object Motion Prior | 用生成式先验补全遮挡和出视野的世界空间手物运动 | [Paper](https://arxiv.org/abs/2602.22209) | — |
| DreamDojo | 2026 | Robot World Model from Human Video | 从大规模人体视频预训练跨任务与跨本体操作世界模型 | [Paper](https://arxiv.org/abs/2602.06949) | — |
| HandsOnWorld | 2026 | Hand-controlled Egocentric Video Generation | 以 Plücker Hand Map 解耦手部和相机运动并生成长时交互视频 | [Paper](https://arxiv.org/abs/2607.02075) | — |
| EgoHOI Data/Code | 2026 | Ego World Model Toolkit | HOT3D 上的物理先验第一视角手物世界模型实现 | [Paper](https://egohoi.github.io/) | [GitHub](https://github.com/Dayou-Li/EgoHOI) |


---

**条目总数：225。**

### 维护规则

- 仅加入能够核验到论文页、项目页或官方仓库的工作。
- GitHub 列仅放官方或作者明确关联的仓库。
- 新增论文优先按主要算法归类；跨类别工作允许重复。
- Ego Manipulation 专题同时覆盖第一视角数据、感知重建、策略学习、VLA 与 World Model。
- 对尚未正式发表的 2025–2026 预印本，年份按首次公开时间记录。
