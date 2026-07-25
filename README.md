# Awesome-Loco-Manipulation

A curated index of research on robotic manipulation, dexterous hand manipulation,
mobile manipulation, legged loco-manipulation, and whole-body control.

## Index

1. [Manipulation](manipulation.md)
   - [1.1 Data](manipulation.md#11-data)
   - [1.2 Teleoperation](manipulation.md#12-teleoperation)
   - [1.3 Model-Based Manipulation](manipulation.md#13-model-based-manipulation)
   - [1.4 Learning-Based Manipulation — RL / IL](manipulation.md#14-learning-based-manipulation--rl--il)
   - [1.5 Real2Sim](manipulation.md#15-real2sim)
   - [1.6 Policy-Based — Diffusion / Flow](manipulation.md#16-policy-based--diffusion--flow)
   - [1.7 Foundation Models — VLA](manipulation.md#17-foundation-models--vla)
   - [1.8 World Action Models (WAM)](manipulation.md#18-world-action-models-wam)
   - [1.9 Ego-Centric Manipulation](manipulation.md#19-ego-centric-manipulation)
   - [1.10 Benchmarks](manipulation.md#110-benchmarks)
2. [Dexterous Hand Manipulation](dexterous_manipulation.md)
   - [2.1 Dexterous Data & Demonstrations](dexterous_manipulation.md#21-dexterous-data--demonstrations)
   - [2.2 Dexterous Retargeting & Teleoperation](dexterous_manipulation.md#22-dexterous-retargeting--teleoperation)
   - [2.3 Dexterous Grasping](dexterous_manipulation.md#23-dexterous-grasping)
   - [2.4 Dexterous In-Hand Manipulation](dexterous_manipulation.md#24-dexterous-in-hand-manipulation)
   - [2.5 Dexterous Tactile Manipulation](dexterous_manipulation.md#25-dexterous-tactile-manipulation)
   - [2.6 Dexterous Learning-Based Manipulation](dexterous_manipulation.md#26-dexterous-learning-based-manipulation)
   - [2.7 Dexterous Generative Policies](dexterous_manipulation.md#27-dexterous-generative-policies)
   - [2.8 Dexterous Foundation Models](dexterous_manipulation.md#28-dexterous-foundation-models)
   - [2.9 Dexterous Ego-Centric Manipulation](dexterous_manipulation.md#29-dexterous-ego-centric-manipulation)
3. [Mobile Manipulation](#3-mobile-manipulation)
4. [Legged Loco-Manipulation](#4-legged-loco-manipulation)
5. [Whole-Body Control & Loco-Manipulation](#5-whole-body-control--loco-manipulation)
6. [Animation / Motion Synthesis](#6-animation--motion-synthesis)

Resources: [Awesome Lists](#awesome-lists) · [Surveys & Reviews](#surveys--reviews)



## 3. Mobile Manipulation

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2025– | **BEHAVIOR Robot Suite** | [arXiv 2025](https://www.alphaxiv.org/search?q=BEHAVIOR+Robot+Suite) | [GitHub](https://github.com/behavior-robot-suite/brs-algo) |
| 2026 | **WHOLE-MoMa** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.12509) | — |
| 2025 | **BiGym** | [arXiv 2025](https://www.alphaxiv.org/search?q=BiGym) | [GitHub](https://github.com/chernyadev/bigym) |
| 2025 | **Open-World Mobile Manipulation** | [arXiv 2025](https://www.alphaxiv.org/search?q=Open-World+Mobile+Manipulation) | — |
| 2025 | **EMMA** | [arXiv 2025](https://www.alphaxiv.org/search?q=EMMA) | — |
| 2024 | **Mobile ALOHA** | [arXiv 2024](https://www.alphaxiv.org/search?q=Mobile+ALOHA) | [GitHub](https://github.com/MarkFzp/mobile-aloha) |
| 2024 | **OK-Robot: What Really Matters in Integrating Open-Knowledge Models for Robotics** | [arXiv 2024](https://www.alphaxiv.org/search?q=OK-Robot%3A+What+Really+Matters+in+Integrating+Open-Knowledge+Models+for+Robotics) | [GitHub](https://github.com/ok-robot/ok-robot) |
| 2024 | **MoMa-LLM: Language-Grounded Dynamic Scene Graphs for Interactive Object Search** | [arXiv 2024](https://www.alphaxiv.org/search?q=MoMa-LLM%3A+Language-Grounded+Dynamic+Scene+Graphs+for+Interactive+Object+Search) | [GitHub](https://github.com/robot-learning-freiburg/MoMa-LLM) |
| 2024 | **TidyBot++** | [arXiv 2024](https://www.alphaxiv.org/search?q=TidyBot%2B%2B) | [GitHub](https://github.com/jimmyyhwu/tidybot) |
| 2024 | **SPIN: Simultaneous Perception, Interaction and Navigation** | [arXiv 2024](https://www.alphaxiv.org/search?q=SPIN%3A+Simultaneous+Perception%2C+Interaction+and+Navigation) | — |
| 2023 | **HomeRobot: Open-Vocabulary Mobile Manipulation** | [arXiv 2023](https://www.alphaxiv.org/search?q=HomeRobot%3A+Open-Vocabulary+Mobile+Manipulation) | [GitHub](https://github.com/facebookresearch/home-robot) |

## 4. Legged Loco-Manipulation

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **ODYSSEY: Open-World Quadruped Loco-Manipulation** | [arXiv 2026](https://www.alphaxiv.org/search?q=ODYSSEY%3A+Open-World+Quadruped+Loco-Manipulation) | — |
| 2026 | **Learning Dynamic Pick-and-Place for Legged Manipulators** | [arXiv 2026](https://www.alphaxiv.org/search?q=Learning+Dynamic+Pick-and-Place+for+Legged+Manipulators) | — |
| 2026 | **Calf-Integrated Arms for Whole-Body Loco-Manipulation** | [arXiv 2026](https://www.alphaxiv.org/search?q=Calf-Integrated+Arms+for+Whole-Body+Loco-Manipulation) | — |
| 2025 | **Unified Position and Force Control for Legged Loco-Manipulation** | [arXiv 2025](https://www.alphaxiv.org/search?q=Unified+Position+and+Force+Control+for+Legged+Loco-Manipulation) | — |
| 2025 | **An Open Framework for Quadrupedal Loco-Manipulation with Unitree B1 + Z1** | [arXiv 2025](https://www.alphaxiv.org/search?q=An+Open+Framework+for+Quadrupedal+Loco-Manipulation+with+Unitree+B1+%2B+Z1) | — |
| 2024 | **Whole-Body Dynamic Throwing with Legged Manipulators** | [arXiv 2024](https://www.alphaxiv.org/search?q=Whole-Body+Dynamic+Throwing+with+Legged+Manipulators) | — |
| 2023 | **Pedipulate: Enabling Manipulation Skills using a Quadruped Robot's Leg** | [arXiv 2023](https://www.alphaxiv.org/search?q=Pedipulate%3A+Enabling+Manipulation+Skills+using+a+Quadruped+Robot's+Leg) | — |
| 2023 | **Learning Force Control for Legged Manipulation** | [arXiv 2023](https://www.alphaxiv.org/search?q=Learning+Force+Control+for+Legged+Manipulation) | [GitHub](https://github.com/Improbable-AI/learning_compliance) |
| 2023 | **Visual Whole-Body Control for Legged Loco-Manipulation** | [arXiv 2023](https://www.alphaxiv.org/search?q=Visual+Whole-Body+Control+for+Legged+Loco-Manipulation) | — |
| 2022 | **Deep Whole-Body Control: Learning a Unified Policy for Manipulation and Locomotion** | [arXiv 2022](https://www.alphaxiv.org/search?q=Deep+Whole-Body+Control%3A+Learning+a+Unified+Policy+for+Manipulation+and+Locomotion) | — |

## 5. Whole-Body Control & Loco-Manipulation

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2025– | **HumanoidVerse** | [arXiv 2025](https://www.alphaxiv.org/search?q=HumanoidVerse) | [GitHub](https://github.com/LeCAR-Lab/HumanoidVerse) |
| 2026 | **MotionWAM** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.09215) | — |
| 2026 | **REFINE-DP** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.13707) | — |
| 2025–2026 | **GR00T Whole-Body Control / GEAR-SONIC / MotionBricks** | [arXiv 2025](https://www.alphaxiv.org/search?q=GR00T+Whole-Body+Control+%2F+GEAR-SONIC+%2F+MotionBricks) | [GitHub](https://github.com/NVlabs/GR00T-WholeBodyControl) |
| 2026 | **WholeBodyVLA** | [arXiv 2026](https://www.alphaxiv.org/search?q=WholeBodyVLA) | [GitHub](https://github.com/OpenDriveLab/WholebodyVLA) |
| 2026 | **EgoHumanoid** | [arXiv 2026](https://www.alphaxiv.org/search?q=EgoHumanoid) | [GitHub](https://github.com/OpenDriveLab/EgoHumanoid) |
| 2025 | **HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots** | [arXiv 2025](https://www.alphaxiv.org/search?q=HOVER%3A+Versatile+Neural+Whole-Body+Controller+for+Humanoid+Robots) | [GitHub](https://github.com/NVlabs/HOVER) |
| 2025 | **ASAP: Aligning Simulation and Real-World Physics for Agile Humanoid Skills** | [arXiv 2025](https://www.alphaxiv.org/search?q=ASAP%3A+Aligning+Simulation+and+Real-World+Physics+for+Agile+Humanoid+Skills) | [GitHub](https://github.com/LeCAR-Lab/ASAP) |
| 2025 | **TWIST: Teleoperated Whole-Body Imitation System** | [arXiv 2025](https://www.alphaxiv.org/search?q=TWIST%3A+Teleoperated+Whole-Body+Imitation+System) | [GitHub](https://github.com/LeCAR-Lab/TWIST) |
| 2025 | **Generalizable Humanoid Manipulation with 3D Diffusion Policies** | [arXiv 2025](https://www.alphaxiv.org/search?q=Generalizable+Humanoid+Manipulation+with+3D+Diffusion+Policies) | [GitHub](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy) |
| 2025 | **HOMIE** | [arXiv 2025](https://www.alphaxiv.org/search?q=HOMIE) | [GitHub](https://github.com/OpenRobotLab/OpenHomie) |
| 2024 | **HumanPlus** | [arXiv 2024](https://www.alphaxiv.org/search?q=HumanPlus) | [GitHub](https://github.com/MarkFzp/humanplus) |
| 2024 | **OmniH2O** | [arXiv 2024](https://www.alphaxiv.org/search?q=OmniH2O) | [GitHub](https://github.com/LeCAR-Lab/human2humanoid) |
| 2024 | **WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts** | [arXiv 2024](https://www.alphaxiv.org/search?q=WoCoCo%3A+Learning+Whole-Body+Humanoid+Control+with+Sequential+Contacts) | [GitHub](https://github.com/LeCAR-Lab/WoCoCo) |
| 2023 | **ExBody: Expressive Whole-Body Control for Humanoid Robots** | [arXiv 2023](https://www.alphaxiv.org/search?q=ExBody%3A+Expressive+Whole-Body+Control+for+Humanoid+Robots) | [GitHub](https://github.com/chengxuxin/expressive-humanoid) |
| 2023 | **PHC: Perpetual Humanoid Control for Real-Time Simulated Avatars** | [arXiv 2023](https://www.alphaxiv.org/search?q=PHC%3A+Perpetual+Humanoid+Control+for+Real-Time+Simulated+Avatars) | [GitHub](https://github.com/ZhengyiLuo/PHC) |

## 6. Animation / Motion Synthesis

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2025–2026 | **MotionBricks** | [arXiv 2025](https://www.alphaxiv.org/search?q=MotionBricks) | [GitHub](https://github.com/NVlabs/GR00T-WholeBodyControl) |
| 2026 | **KungfuBot / KungfuBot2** | [arXiv 2026](https://www.alphaxiv.org/search?q=KungfuBot+%2F+KungfuBot2) | [GitHub](https://github.com/TeleHuman/PBHC) |
| 2025 | **MaskedMimic** | [arXiv 2025](https://www.alphaxiv.org/search?q=MaskedMimic) | [GitHub](https://github.com/NVlabs/ProtoMotions) |
| 2025 | **ProtoMotions** | [arXiv 2025](https://www.alphaxiv.org/search?q=ProtoMotions) | [GitHub](https://github.com/NVlabs/ProtoMotions) |
| 2025 | **VideoMimic** | [arXiv 2025](https://www.alphaxiv.org/search?q=VideoMimic) | [GitHub](https://github.com/hongsukchoi/VideoMimic) |
| 2025 | **ASAP** | [arXiv 2025](https://www.alphaxiv.org/search?q=ASAP) | [GitHub](https://github.com/LeCAR-Lab/ASAP) |
| 2024 | **HumanPlus** | [arXiv 2024](https://www.alphaxiv.org/search?q=HumanPlus) | [GitHub](https://github.com/MarkFzp/humanplus) |
| 2024 | **OmniH2O** | [arXiv 2024](https://www.alphaxiv.org/search?q=OmniH2O) | [GitHub](https://github.com/LeCAR-Lab/human2humanoid) |
| 2023 | **PHC: Perpetual Humanoid Control** | [arXiv 2023](https://www.alphaxiv.org/search?q=PHC%3A+Perpetual+Humanoid+Control) | [GitHub](https://github.com/ZhengyiLuo/PHC) |
| 2023 | **PULSE: Universal Humanoid Motion Representations for Physics-Based Control** | [arXiv 2023](https://www.alphaxiv.org/search?q=PULSE%3A+Universal+Humanoid+Motion+Representations+for+Physics-Based+Control) | [GitHub](https://github.com/ZhengyiLuo/PULSE) |
| 2022 | **ASE: Large-Scale Reusable Adversarial Skill Embeddings** | [arXiv 2022](https://www.alphaxiv.org/search?q=ASE%3A+Large-Scale+Reusable+Adversarial+Skill+Embeddings) | [GitHub](https://github.com/nv-tlabs/ASE) |
| 2022 | **CALM: Conditional Adversarial Latent Models for Directable Virtual Characters** | [arXiv 2022](https://www.alphaxiv.org/search?q=CALM%3A+Conditional+Adversarial+Latent+Models+for+Directable+Virtual+Characters) | [GitHub](https://github.com/NVlabs/CALM) |
| 2021 | **AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control** | [arXiv 2021](https://www.alphaxiv.org/search?q=AMP%3A+Adversarial+Motion+Priors+for+Stylized+Physics-Based+Character+Control) | [GitHub](https://github.com/isaac-sim/IsaacGymEnvs) |
| 2018 | **DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills** | [arXiv 2018](https://www.alphaxiv.org/search?q=DeepMimic%3A+Example-Guided+Deep+Reinforcement+Learning+of+Physics-Based+Character+Skills) | [GitHub](https://github.com/xbpeng/DeepMimic) |

# Resources

## Awesome Lists

### Locomotion

- [Awesome Loco-Manipulation](https://github.com/aCodeDog/awesome-loco-manipulation)

### Humanoid

- [Awesome Humanoid Robot Learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning)
- [Awesome Humanoid Manipulation](https://github.com/Tsunami-kun/awesome-humanoid-manipulation)
- [WholeBodyVLA Index](https://github.com/OpenDriveLab/WholebodyVLA)

## Surveys & Reviews

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **Vision-Language-Action Models for Robotics: A Survey** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.23001) | — |
| 2026 | **A Survey on Learning-Based Whole-Body Control for Humanoid Robots** | [arXiv 2026](https://www.alphaxiv.org/search?q=A+Survey+on+Learning-Based+Whole-Body+Control+for+Humanoid+Robots) | [github](https://github.com/Earl000333/humanoid-wbc-review) |
| 2025 | **Towards a Unified Understanding of Robot Manipulation: A Comprehensive Survey** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.10903) | — |
| 2025 | **Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.13073) | [github](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation) |

| 2025 | **Dexterous Manipulation through Imitation Learning: A Survey** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.03515) | — |
| 2024 | **A Survey of Embodied Learning for Object-Centric Robotic Manipulation** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.11537) | — |
| 2024 | **A Systematic Review on Custom Data Gloves** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.15417) | — |
