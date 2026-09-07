# 3. Locomotion

## Table of Contents

- [3.1 Blind Locomotion](#31-blind-locomotion)
- [3.2 Vision Locomotion](#32-vision-locomotion)
  - [3.2.1 Elevation Map Locomotion](#321-elevation-map-locomotion)
  - [3.2.2 Depth Locomotion](#322-depth-locomotion)
- [3.3 Navigation Locomotion](#33-navigation-locomotion)
- [3.4 Generalist Models / World Models Locomotion](#34-generalist-models--world-models-locomotion)
- [3.5 Cross-Embodied Locomotion](#35-cross-embodied-locomotion)
- [3.6 Multi-Agent Locomotion](#36-multi-agent-locomotion)

## 3.1 Blind Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **Bridging the Gap: Enabling Soft Actor Critic for High Performance Legged Locomotion** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.24975) | [GitHub](https://github.com/leggedrobotics/rsl_rl_sac) |
| 2025 | **Towards bridging the gap: Systematic sim-to-real transfer for diverse legged robots** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.06342) | — |
| 2026 | **WARL: Wrench-Augmented Reinforcement Learning for Task-Agnostic Learning in Legged Robots** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.24036) | — |
| 2026 | **Mixture-of-Experts RL for Fault-Tolerant Legged Locomotion** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.25965) | — |
| 2026 | 🌟️🌟️ **FlashSAC: Fast and Stable Off-Policy Reinforcement Learning for High-Dimensional Robot Control** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.04539) | [GitHub](https://github.com/Holiday-Robot/FlashSAC) |
| 2026 | **MUJICA: Multi-skill Unified Joint Integration of Control Architecture for Wheeled-Legged Robots** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.13058) | — |
| 2026 | **Toward Reliable Sim-to-Real Predictability for MoE-based Robust Quadrupedal Locomotion** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.00678) | [GitHub](https://github.com/robogauge/code) |
| 2026 | **KiRAS: Keyframe Guided Self-Imitation for Robust and Adaptive Skill Learning in Quadruped Robots** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.15179) | — |
| 2026 | 🌟️ **Flow Policy Gradients for Robot Control** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.02481) | [GitHub](https://github.com/amazon-far/fpo-control) |
| 2024 | **Deep Reinforcement Learning for Bipedal Locomotion: A Brief Survey** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.17070) | — |
| 2025 | **Learning Sim-to-Real Humanoid Locomotion in 15 Minutes** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.01996) | — |
| 2025 | **Constrained Style Learning from Imperfect Demonstrations under Task Optimality** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.09371) | — |
| 2025 | 🌟️ **RSL-RL: A Learning Library for Robotics Research** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.10771) | [GitHub](https://github.com/leggedrobotics/rsl_rl) |
| 2025 | **Motion Priors Reimagined: Adapting Flat-Terrain Skills for Complex Quadruped Mobility** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.16084) | — |
| 2025 | **Divide, Discover, Deploy: Factorized Skill Learning with Symmetry and Style Priors** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.19953) | [GitHub](https://github.com/leggedrobotics/d3-skill-discovery) |
| 2025 | **Unsupervised Skill Discovery as Exploration for Learning Agile Locomotion** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.08982) | — |
| 2024 | **Spatio-Temporal Motion Retargeting for Quadruped Robots** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.11557) | — |
| 2025 | 🌟️ **FastTD3: Simple, Fast, and Capable Reinforcement Learning for Humanoid Control** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.22642) | [GitHub](https://github.com/younggyoseo/FastTD3) |
| 2025 | **MoE-Loco: Mixture of Experts for Multitask Locomotion** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.08564) | [GitHub](https://github.com/hrh6666/MoE-Loco) |
| 2025 | **Sampling-Based System Identification with Active Exploration for Legged Robot Sim2Real Learning** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.14266) | [GitHub](https://github.com/LeCAR-Lab/SPI-Active) |
| 2025 | **FACET: Force-Adaptive Control via Impedance Reference Tracking for Legged Robots** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.06883) | — |
| 2025 | **SATA: Safe and Adaptive Torque-Based Locomotion Policies Inspired by Animal Learning** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.12674) | [GitHub](https://github.com/marmotlab/SATA) |
| 2023 | **Generalized Animal Imitator: Agile Locomotion with Versatile Motion Prior** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.01408) | — |
| 2025 | **Robust Humanoid Walking on Compliant and Uneven Terrain with Deep Reinforcement Learning** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.13619) | [GitHub](https://github.com/rohanpsingh/LearningHumanoidWalking) |
| 2024 | **Morphological Symmetries in Robotics** | [arXiv 2024.02](https://www.alphaxiv.org/abs/2402.15552) | [GitHub](https://github.com/Danfoa/MorphoSymm) |
| 2024 | **Leveraging Symmetry in RL-based Legged Locomotion Control** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.17320) | — |
| 2025 | **Continuous Control of Diverse Skills in Quadruped Robots Without Complete Expert Datasets** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.03476) | — |
| 2025 | **Humanoid Whole-Body Locomotion on Narrow Terrain via Dynamic Balance and Reinforcement Learning** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.17219) | — |
| 2024 | **Learning-based legged locomotion; state of the art and future perspectives** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.01152) | — |
| 2024 | **RobotKeyframing: Learning Locomotion with High-Level Objectives via Mixture of Dense and Sparse Rewards** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.11562) | — |
| 2024 | 🌟️ **Learning Smooth Humanoid Locomotion through Lipschitz-Constrained Policies** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.11825) | [GitHub](https://github.com/zixuan417/smooth-humanoid-locomotion) |
| 2024 | **SLR: Learning Quadruped Locomotion without Privileged Information** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.04835) | — |
| 2024 | **Learning Quadruped Locomotion Using Differentiable Simulation** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.14864) | — |
| 2024 | **Learning Humanoid Locomotion over Challenging Terrain** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.03654) | — |
| 2024 | 🌟️ **Stage-Wise Reward Shaping for Acrobatic Robots: A Constrained Multi-Objective Reinforcement Learning Approach** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.15755) | [GitHub](https://github.com/rllab-snu/Stage-Wise-CMORL) |
| 2024 | **OGMP: Oracle Guided Multi-mode Policies for Agile and Versatile Robot Control** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.04205) | [MuJoCo](https://github.com/DRCL-USC/ogmp)<br>[Isaac](https://github.com/DRCL-USC/ogmp_isaac) |
| 2024 | **CTS: Concurrent Teacher-Student Reinforcement Learning for Legged Locomotion** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.10830) | — |
| 2024 | **Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control** | [arXiv 2024.01](https://www.alphaxiv.org/abs/2401.16889) | [GitHub](https://github.com/z-taylcr7/Adaptivity) |
| 2024 | 🌟️ **Berkeley Humanoid: A Research Platform for Learning-based Control** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.21781) | [Hardware](https://github.com/HybridRobotics/Berkeley-Humanoid-Lite)<br>[Train](https://github.com/HybridRobotics/isaac_berkeley_humanoid) |
| 2023 | **Not Only Rewards But Also Constraints: Applications on Legged Robot Locomotion** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.12517) | — |
| 2023 | 🌟️ **Lifelike Agility and Play in Quadrupedal Robots using Reinforcement Learning and Generative Pre-trained Models** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.15143) | [GitHub](https://github.com/Tencent-RoboticsX/lifelike-agility-and-play) |
| 2024 | **Learning Bipedal Walking on a Quadruped Robot via Adversarial Motion Priors** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.02282) | — |
| 2024 | **Learning H-Infinity Locomotion Control** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.14405) | — |
| 2024 | **DrEureka: Language Model Guided Sim-To-Real Transfer** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.01967) | [GitHub](https://github.com/eureka-research/DrEureka) |
| 2024 | 🌟️ **Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.05695) | [GitHub](https://github.com/roboterax/humanoid-gym) |
| 2023 | **Learning Risk-Aware Quadrupedal Locomotion using Distributional Reinforcement Learning** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.14246) | — |
| 2024 | **Symmetry Considerations for Learning Task Symmetric Robot Policies** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.04359) | — |
| 2024 | **Dexterous Legged Locomotion in Confined 3D Spaces with Reinforcement Learning** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.03848) | — |
| 2023 | **Learning Agile Bipedal Motions on a Quadrupedal Robot** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.05818) | — |
| 2024 | **FLD: Fourier Latent Dynamics for Structured Motion Representation and Learning** | [arXiv 2024.02](https://www.alphaxiv.org/abs/2402.13820) | [GitHub](https://github.com/mit-biomimetics/fld) |
| 2024 | **Reinforcement Learning for Blind Stair Climbing with Legged and Wheeled-Legged Robots** | [arXiv 2024.02](https://www.alphaxiv.org/abs/2402.06143) | — |
| 2023 | 🌟️ **Hybrid Internal Model: Learning Agile Legged Locomotion with Simulated Robot Response** | [arXiv 2023.12](https://www.alphaxiv.org/abs/2312.11460) | [GitHub](https://github.com/InternRobotics/HIMLoco)<br>[go2w](https://github.com/TrackinBIT/HIMLoco-for-Go2W) |
| 2023 | **Real-World Humanoid Locomotion with Reinforcement Learning** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.03381) | — |
| 2023 | **LocoMuJoCo: A Comprehensive Imitation Learning Benchmark for Locomotion** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.02496) | — |
| 2023 | **Grow Your Limits: Continuous Improvement with Real-World RL for Robotic Locomotion** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.17634) | — |
| 2023 | **Guardians as You Fall: Active Mode Transition for Safe Falling** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.04828) | — |
| 2023 | **Learning Robust, Agile, Natural Legged Locomotion Skills in the Wild** | [arXiv 2023.04](https://www.alphaxiv.org/abs/2304.10888) | — |
| 2023 | **Learning Bipedal Walking for Humanoids with Current Feedback** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.03724) | — |
| 2023 | **Learning Multiple Gaits within Latent Space for Quadruped Robots** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.03014) | — |
| 2022 | **VAE-Loco: Versatile Quadruped Locomotion by Learning a Disentangled Gait Representation** | [arXiv 2022.05](https://www.alphaxiv.org/abs/2205.01179) | — |
| 2023 | **On discrete symmetries of robotics systems: A group-theoretic and data-driven analysis** | [arXiv 2023.02](https://www.alphaxiv.org/abs/2302.10433) | — |
| 2023 | **DeepTransition: Viability Leads to the Emergence of Gait Transitions in Learning Anticipatory Quadrupedal Locomotion Skills** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.07419) | — |
| 2023 | **Learning and Adapting Agile Locomotion Skills by Transferring Experience** | [arXiv 2023.04](https://www.alphaxiv.org/abs/2304.09834) | — |
| 2022 | **Sim-to-Real Transfer for Quadrupedal Locomotion via Terrain Transformer** | [arXiv 2022.12](https://www.alphaxiv.org/abs/2212.07740) | — |
| 2023 | 🌟️ **DreamWaQ: Learning Robust Quadrupedal Locomotion With Implicit Terrain Imagination via Deep Reinforcement Learning** | [arXiv 2023.01](https://www.alphaxiv.org/abs/2301.10602) | [go1](https://github.com/Manaro-Alpha/DreamWaQ)<br>[go2w](https://github.com/yusongmin1/Dreamwaq)<br>[g1](https://github.com/liuyufei-nubot/HumanoidDreamWaq)<br>[g1](https://github.com/liuyufei-nubot/G1DWAQ_Lab)<br>[go2w](https://github.com/ShengqianChen/DreamWaQ_Go2W) |
| 2022 | **Versatile Skill Control via Self-supervised Adversarial Imitation of Unlabeled Mixed Motions** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.07899) | [GitHub](https://github.com/martius-lab/cassi) |
| 2022 | **Walk These Ways: Tuning Robot Control for Generalization with Multiplicity of Behavior** | [arXiv 2022.12](https://www.alphaxiv.org/abs/2212.03238) | [GitHub](https://github.com/Improbable-AI/walk-these-ways) |
| 2022 | **Learning Agile Skills via Adversarial Imitation of Rough Partial Demonstrations** | [arXiv 2022.06](https://www.alphaxiv.org/abs/2206.11693) | [GitHub](https://github.com/martius-lab/wasabi) |
| 2021 | 🌟️ **Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning** | [arXiv 2021.09](https://www.alphaxiv.org/abs/2109.11978) | [GitHub](https://github.com/leggedrobotics/legged_gym) |
| 2022 | 🌟️ **A Walk in the Park: Learning to Walk in 20 Minutes With Model-Free Reinforcement Learning** | [arXiv 2022.08](https://www.alphaxiv.org/abs/2208.07860) | [GitHub](https://github.com/ikostrikov/walk_in_the_park) |
| 2022 | **Rapid Locomotion via Reinforcement Learning** | [arXiv 2022.05](https://www.alphaxiv.org/abs/2205.02824) | [GitHub](https://github.com/Improbable-AI/rapid-locomotion-rl) |
| 2022 | 🌟️🌟️ **Adversarial Motion Priors Make Good Substitutes for Complex Reward Functions** | [arXiv 2022.03](https://www.alphaxiv.org/abs/2203.15103) | [GitHub](https://github.com/Alescontrela/AMP_for_hardware)<br>[go2](https://github.com/ak1raljl/amp_go2) |
| 2022 | **Advanced Skills through Multiple Adversarial Motion Priors in Reinforcement Learning** | [arXiv 2022.03](https://www.alphaxiv.org/abs/2203.14912) | — |
| 2021 | **Legged Robots that Keep on Learning: Fine-Tuning Locomotion Policies in the Real World** | [arXiv 2021.10](https://www.alphaxiv.org/abs/2110.05457) | [GitHub](https://github.com/lauramsmith/fine-tuning-locomotion) |
| 2021 | 🌟️ **RMA: Rapid Motor Adaptation for Legged Robots** | [arXiv 2021.07](https://www.alphaxiv.org/abs/2107.04034) | [GitHub](https://github.com/antonilo/rl_locomotion)<br>[GitHub](https://github.com/Manaro-Alpha/legged_gym_RMA) |
| 2020 | **Learning a Contact-Adaptive Controller for Robust, Efficient Legged Locomotion** | [arXiv 2020.09](https://www.alphaxiv.org/abs/2009.10019) | — |
| 2020 | 🌟️ **Learning Quadrupedal Locomotion over Challenging Terrain** | [arXiv 2020.10](https://www.alphaxiv.org/abs/2010.11251) | [GitHub](https://github.com/leggedrobotics/learning_quadrupedal_locomotion_over_challenging_terrain_supplementary) |
| 2020 | 🌟️ **Learning Agile Robotic Locomotion Skills by Imitating Animals** | [arXiv 2020.04](https://www.alphaxiv.org/abs/2004.00784) | [GitHub](https://github.com/erwincoumans/motion_imitation) |
| 2019 | **Data Efficient Reinforcement Learning for Legged Robots** | [arXiv 2019.07](https://www.alphaxiv.org/abs/1907.03613) | — |
| 2019 | **Sim-to-Real Transfer for Biped Locomotion** | [arXiv 2019.03](https://www.alphaxiv.org/abs/1903.01390) | — |
| 2018 | 🌟️ **Learning to Walk via Deep Reinforcement Learning** | [arXiv 2018.12](https://www.alphaxiv.org/abs/1812.11103) | — |
| 2019 | 🌟️ **Learning agile and dynamic motor skills for legged robots** | [arXiv 2019.01](https://www.alphaxiv.org/abs/1901.08652) | — |
| 2018 | **Sim-to-Real: Learning Agile Locomotion For Quadruped Robots** | [arXiv 2018.04](https://www.alphaxiv.org/abs/1804.10332) | — |
| 2018 | **Learning Symmetric and Low-energy Locomotion** | [arXiv 2018.01](https://www.alphaxiv.org/abs/1801.08093) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 3.2 Vision Locomotion

### 3.2.1 Elevation Map Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **Agile perceptive multi-skill locomotion for quadrupedal robots in the wild** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.13579) | — |
| 2026 | **Physics-Guided Biomechanical Gait Adaptation for Humanoid Locomotion on Extreme Sloped Terrains** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.07830) | — |
| 2026 | **Learning Locomotion on Discrete Terrain via Minimal Proximity Sensing** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.31912) | — |
| 2026 | **Global-Local Attention Decomposition for Terrain Encoding in Humanoid Perceptive Locomotion** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.00637) | — |
| 2026 | **TAGA: Terrain-aware Active Gaze Learning for Generalizable Agile Humanoid Locomotion** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.05880) | — |
| 2025 | **DreamPolicy: A Unified World-model Policy for Scalable Humanoid Locomotion** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.18780) | — |
| 2026 | **Explicit Stair Geometry Conditioning for Robust Humanoid Locomotion** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.09944) | — |
| 2026 | **Now You See That: Learning End-to-End Humanoid Locomotion from Raw Pixels** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.06382) | [GitHub](https://github.com/Hellod035/Now_You_See_That) |
| 2026 | **Watch Your Step: Learning Semantically-Guided Locomotion in Cluttered Environment** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.02657) | — |
| 2026 | **Learning Locomotion on Complex Terrain for Quadrupedal Robots with Foot Position Maps and Stability Rewards** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.02744) | — |
| 2026 | **AME-2: Agile and Generalized Legged Locomotion via Attention-Based Neural Map Encoding** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.08485) | [GitHub](https://github.com/Kitjesen/ame2) |
| 2026 | **Omnidirectional Humanoid Locomotion on Stairs via Unsafe Stepping Penalty and Sparse LiDAR Elevation Mapping** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.07928) | — |
| 2026 | **APEX: Learning Adaptive High-Platform Traversal for Humanoid Robots** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.11143) | — |
| 2026 | **CMoE: Contrastive Mixture of Experts for Motion Control and Terrain Adaptation of Humanoid Robots** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.03067) | [GitHub](https://github.com/Anonymous-ICRA2026/Anonymous-ICRA2026.github.io) |
| 2024 | **DreamWaQ++: Obstacle-Aware Quadrupedal Locomotion With Resilient Multi-Modal Reinforcement Learning** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.19709) | — |
| 2025 | **Robust Reinforcement Learning-Based Locomotion for Resource-Constrained Quadrupeds with Exteroceptive Sensing** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.12537) | [GitHub](https://github.com/ETH-PBL/elmap-rl-controller) |
| 2026 | **CMR: Contractive Mapping Embeddings for Robust Humanoid Locomotion on Unstructured Terrains** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.03511) | — |
| 2026 | **PILOT: A Perceptive Integrated Low-level Controller for Loco-manipulation over Unstructured Scenes** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.17440) | — |
| 2026 | **FocusNav: Spatial Selective Attention with Waypoint Guidance for Humanoid Local Navigation** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.12790) | — |
| 2026 | **FastStair: Learning to Run Up Stairs with Humanoid Robots** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.10365) | — |
| 2026 | **Walk the PLANC: Physics-Guided RL for Agile Humanoid Locomotion on Constrained Footholds** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.06286) | — |
| 2025 | **Gait-Adaptive Perceptive Humanoid Locomotion with Real-Time Under-Base Terrain Reconstruction** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.07464) | — |
| 2025 | **PPL: Point Cloud Supervised Proprioceptive Locomotion Reinforcement Learning for Legged Robots in Crawl Spaces** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.09950) | — |
| 2025 | **MARG: MAstering Risky Gap Terrains for Legged Robots with Elevation Mapping** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.20036) | — |
| 2025 | **Contrastive Representation Learning for Robust Sim-to-Real Transfer of Adaptive Humanoid Locomotion** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.12858) | — |
| 2025 | **Omni-Perception: Omnidirectional Collision Avoidance for Legged Locomotion in Dynamic Environments** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.19214) | [GitHub](https://github.com/aCodeDog/OmniPerception) |
| 2025 | **Attention-Based Map Encoding for Learning Generalized Legged Locomotion** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.09588) | — |
| 2025 | **VB-Com: Learning Vision-Blind Composite Humanoid Locomotion Against Deficient Perception** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.14814) | — |
| 2025 | **BeamDojo: Learning Agile Humanoid Locomotion on Sparse Footholds** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.10363) | — |
| 2025 | **Learning Perceptive Humanoid Locomotion over Challenging Terrain** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.00692) | — |
| 2024 | **Walking with Terrain Reconstruction: Learning to Traverse Risky Sparse Footholds** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.15692) | — |
| 2024 | **TRIP: Terrain Traversability Mapping With Risk-Aware Prediction for Enhanced Online Quadrupedal Robot Navigation** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.17134) | — |
| 2024 | **Learning Humanoid Locomotion with Perceptive Internal Model** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.14386) | — |
| 2023 | **Learning Agile Locomotion on Risky Terrains** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.10484) | — |
| 2024 | **Pixel to Elevation: Learning to Predict Elevation Maps at Long Range using Images for Autonomous Offroad Navigation** | [arXiv 2024.01](https://www.alphaxiv.org/abs/2401.17484) | — |
| 2024 | **CaT: Constraints as Terminations for Legged Locomotion Reinforcement Learning** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.18765) | — |
| 2024 | **Learning to walk in confined spaces using 3D representation** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.00187) | — |
| 2023 | **Perceptive Locomotion through Whole-Body MPC and Optimal Region Selection** | [arXiv 2023.05](https://www.alphaxiv.org/abs/2305.08926) | — |
| 2023 | **DTC: Deep Tracking Control** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.15462) | [GitHub](https://github.com/priest-yang/Deep-Tracking-Control) |
| 2023 | 🌟️ **MEM: Multi-Modal Elevation Mapping for Robotics and Learning** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.16818) | — |
| 2022 | **Perceptive Locomotion through Nonlinear Model Predictive Control** | [arXiv 2022.08](https://www.alphaxiv.org/abs/2208.08373) | — |
| 2022 | **Neural Scene Representation for Locomotion on Structured Terrain** | [arXiv 2022.06](https://www.alphaxiv.org/abs/2206.08077) | — |
| 2021 | **Learning Perceptual Locomotion on Uneven Terrains using Sparse Visual Observations** | [arXiv 2021.09](https://www.alphaxiv.org/abs/2109.14026) | — |
| 2020 | **RLOC: Terrain-Aware Legged Locomotion using Reinforcement Learning and Optimal Control** | [arXiv 2020.12](https://www.alphaxiv.org/abs/2012.03094) | — |
| 2022 | 🌟️ **Elevation Mapping for Locomotion and Navigation using GPU** | [arXiv 2022.04](https://www.alphaxiv.org/abs/2204.12876) | — |
| 2022 | 🌟️ **Learning robust perceptive locomotion for quadrupedal robots in the wild** | [arXiv 2022.01](https://www.alphaxiv.org/abs/2201.08117) | [GitHub](https://github.com/awesomericky/quadruped-robot-belief-encoder) |
| 2020 | 🌟️ **Learning Quadrupedal Locomotion over Challenging Terrain** | [arXiv 2020.10](https://www.alphaxiv.org/abs/2010.11251) | [GitHub](https://github.com/leggedrobotics/learning_quadrupedal_locomotion_over_challenging_terrain_supplementary) |
| 2020 | **Motion Planning for Quadrupedal Locomotion: Coupled Planning, Terrain Mapping and Whole-Body Control** | [arXiv 2020.03](https://www.alphaxiv.org/abs/2003.05481) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

### 3.2.2 Depth Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **StairMaster: Learning to Conquer Risky Hollow Stairs for Agile Quadrupedal Robots** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.25765) | — |
| 2026 | **CReF: Cross-modal and Recurrent Fusion for Depth-conditioned Humanoid Locomotion** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.29452) | [GitHub](https://github.com/cometlogic/cref.github.io) |
| 2026 | **PUMA: Perception-driven Unified Foothold Prior for Mobility Augmented Quadruped Parkour** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.15995) | — |
| 2025 | **KiVi: Kinesthetic-Visuospatial Integration for Dynamic and Safe Egocentric Legged Locomotion** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.23650) | — |
| 2026 | **CTS-MoE: Implicit Terrain Adaptation via Mixture-of-Experts for Perceptive Locomotion** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.19633) | — |
| 2026 | **ParkourFormer: Integrating Predictive Supervision and Sequence Modeling into Parkour Locomotion** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.25782) | — |
| 2026 | **CoRe-MoE: Contrastive Reweighted Mixture of Experts for Multi-Terrain Humanoid Locomotion with Gait Adaptation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.04718) | — |
| 2026 | **X-Loco: Towards Generalist Humanoid Locomotion Control via Synergetic Policy Distillation** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.03733) | — |
| 2026 | **MARCH: Model-Assisted Reinforcement Learning for the Perceptive Control of Humanoids over Sparse Footholds** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.10288) | — |
| 2026 | **SSR: Scaling Surefooted and Symmetric Humanoid Traversal to the Open World** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.30770) | — |
| 2026 | **PRIOR: Perceptive Learning for Humanoid Locomotion with Reference Gait Priors** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.18979) | — |
| 2026 | **GeoLoco: Leveraging 3D Geometric Priors from Visual Foundation Model for Robust RGB-Only Humanoid Locomotion** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.07624) | [GitHub](https://github.com/liuyufei-nubot/GeoLoco) |
| 2026 | **RPL: Learning Robust Humanoid Perceptive Locomotion on Challenging Terrains** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.03002) | — |
| 2026 | 🌟️ **TTT-Parkour: Rapid Test-Time Training for Perceptive Robot Parkour** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.02331) | — |
| 2026 | 🌟️ **Hiking in the Wild: A Scalable Perceptive Parkour Framework for Humanoids** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.07718) | — |
| 2026 | **Locomotion Beyond Feet** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.03607) | [GitHub](https://github.com/locomotion-beyond-feet/locomotion-beyond-feet.github.io) |
| 2025 | **START: Traversing Sparse Footholds with Terrain Reconstruction** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.13153) | — |
| 2025 | **DPL: Depth-only Perceptive Humanoid Locomotion via Realistic Depth Synthesis and Cross-Attention Terrain Reconstruction** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.07152) | — |
| 2025 | **RENet: Fault-Tolerant Motion Control for Quadruped Robots via Redundant Estimator Networks under Visual Collapse** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.09283) | — |
| 2025 | **LocoTouch: Learning Dynamic Quadrupedal Transport with Tactile Sensing** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.23175) | [GitHub](https://github.com/linchangyi1/LocoTouch) |
| 2025 | **MoRE: Mixture of Residual Experts for Humanoid Lifelike Gaits Learning on Complex Terrains** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.08840) | [GitHub](https://github.com/TeleHuman/MoRE) |
| 2025 | **Parkour in the Wild: Learning a General and Extensible Agile Locomotion Policy Using Multi-expert Distillation and RL Fine-tuning** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.11164) | — |
| 2025 | **Learning Diverse Natural Behaviors for Enhancing the Agility of Quadrupedal Robots** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.09979) | [GitHub](https://github.com/NJU-RLC/quadrupedal-agility) |
| 2025 | **Let Humanoids Hike! Integrative Skill Development on Complex Trails** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.06218) | — |
| 2024 | **SARO: Space-Aware Robot System for Terrain Crossing via Vision-Language Model** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.16412) | — |
| 2024 | **MOVE: Multi-skill Omnidirectional Legged Locomotion with Limited View in 3D Environments** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.03353) | — |
| 2024 | **Real-Time Polygonal Semantic Mapping for Humanoid Robot Stair Climbing** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.01919) | — |
| 2024 | **Eurekaverse: Environment Curriculum Generation via Large Language Models** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.01775) | [GitHub](https://github.com/eureka-research/eurekaverse) |
| 2024 | **Humanoid Parkour Learning** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.10759) | — |
| 2024 | **Agile Continuous Jumping in Discontinuous Terrains** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.10923) | — |
| 2024 | **PIE: Parkour with Implicit-Explicit Learning Framework for Legged Robots** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.13740) | — |
| 2023 | **Learning Vision-Based Bipedal Locomotion for Challenging Terrain** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.14594) | — |
| 2024 | **Agile But Safe: Learning Collision-Free High-Speed Legged Locomotion** | [arXiv 2024.01](https://www.alphaxiv.org/abs/2401.17583) | [GitHub](https://github.com/LeCAR-Lab/ABS) |
| 2023 | 🌟️ **Extreme Parkour with Legged Robots** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.14341) | [GitHub](https://github.com/chengxuxin/extreme-parkour) |
| 2023 | 🌟️ **Robot Parkour Learning** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.05665) | [GitHub](https://github.com/ZiwenZhuang/parkour) |
| 2023 | **Event-based Agile Object Catching with a Quadrupedal Robot** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.17479) | — |
| 2022 | **Learning to Walk by Steering: Perceptive Quadrupedal Locomotion in Dynamic Environments** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.09233) | [GitHub](https://github.com/UT-Austin-RPL/PRELUDE) |
| 2022 | 🌟️ **Legged Locomotion in Challenging Terrains using Egocentric Vision** | [arXiv 2022.11](https://www.alphaxiv.org/abs/2211.07638) | — |
| 2022 | 🌟️ **Learning Visual Locomotion with Cross-Modal Supervision** | [arXiv 2022.11](https://www.alphaxiv.org/abs/2211.03785) | [GitHub](https://github.com/antonilo/vision_locomotion) |
| 2022 | **Creating a Dynamic Quadrupedal Robotic Goalkeeper with Reinforcement Learning** | [arXiv 2022.10](https://www.alphaxiv.org/abs/2210.04435) | — |
| 2021 | **Vision-Guided Quadrupedal Locomotion in the Wild with Multi-Modal Delay Randomization** | [arXiv 2021.09](https://www.alphaxiv.org/abs/2109.14549) | — |
| 2021 | 🌟️ **Learning Vision-Guided Quadrupedal Locomotion End-to-End with Cross-Modal Transformers** | [arXiv 2021.07](https://www.alphaxiv.org/abs/2107.03996) | [GitHub](https://github.com/Mehooz/vision4leg) |
| 2021 | **Charge Radius of Neutron-deficient $^{54}$Ni and Symmetry Energy Constraints Using the Difference in Mirror Pair Charge Radii** | [arXiv 2021.06](https://www.alphaxiv.org/abs/2106.10378) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 3.3 Navigation Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **GuideWalk: Learning Unified Autonomous Navigation and Locomotion for Humanoid Robots across Versatile Terrains** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.10449) | — |
| 2026 | **Terrain Consistent Reference-Guided RL for Humanoid Navigation Autonomy** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.15517) | — |
| 2026 | **DreamFlow: Local Navigation Beyond Observation via Conditional Flow Matching in the Latent Space** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.02976) | — |
| 2026 | **SEA-Nav: Efficient Policy Learning for Safe and Agile Quadruped Navigation in Cluttered Environments** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.09460) | [GitHub](https://github.com/11chens/SEA-Nav-Code) |
| 2025 | **JanusVLN: Decoupling Semantics and Spatiality with Dual Implicit Memory for Vision-Language Navigation** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.22548) | [GitHub](https://github.com/MIV-XJTU/JanusVLN) |
| 2026 | **UEREBot: Learning Safe Quadrupedal Locomotion under Unstructured Environments and High-Speed Dynamic Obstacles** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.07363) | — |
| 2026 | **Large-Scale Autonomous Gas Monitoring for Volcanic Environments: A Legged Robot on Mount Etna** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.07362) | — |
| 2026 | **Collision-Free Humanoid Traversal in Cluttered Indoor Scenes** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.16035) | — |
| 2025 | **AutoOdom: Learning Auto-regressive Proprioceptive Odometry for Legged Locomotion** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.18857) | — |
| 2025 | **InEKFormer: A Hybrid State Estimator for Humanoid Robots** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.16306) | — |
| 2025 | **COMPASS: Cross-embodiment Mobility Policy via Residual RL and Skill Synthesis** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.16372) | — |
| 2025 | **APREBot: Active Perception System for Reflexive Evasion Robot** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.24733) | — |
| 2025 | **Spatially-Enhanced Recurrent Memory for Long-Range Mapless Navigation via End-to-End Reinforcement Learning** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.05997) | — |
| 2025 | **Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.03068) | [GitHub](https://github.com/Stanford-TML/HEAD_release) |
| 2025 | **FOCI: Trajectory Optimization on Gaussian Splats** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.08510) | — |
| 2025 | **Humanoid Occupancy: Enabling A Generalized Multimodal Occupancy Perception System on Humanoid Robots** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.20217) | [GitHub](https://github.com/Open-X-Humanoid/Humanoid-Occupancy) |
| 2024 | **X-MOBILITY: End-To-End Generalizable Navigation via World Modeling** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.17491) | [GitHub](https://github.com/NVlabs/X-MOBILITY) |
| 2024 | **SF-TIM: A Simple Framework for Enhancing Quadrupedal Robot Jumping Agility by Combining Terrain Imagination and Measurement** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.00486) | — |
| 2025 | **High-speed control and navigation for quadrupedal robots on complex and discrete terrain** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.02835) | — |
| 2024 | **Zero-shot Object-Centric Instruction Following: Integrating Foundation Models with Traditional Navigation** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.07848) | — |
| 2025 | 🌟️ **Learned Perceptive Forward Dynamics Model for Safe and Platform-aware Robotic Navigation** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.19322) | [GitHub](https://github.com/leggedrobotics/fdm) |
| 2024 | **NaVILA: Legged Robot Vision-Language-Action Model for Navigation** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.04453) | [GitHub](https://github.com/AnjieCheng/NaVILA) |
| 2024 | **Traversability-Aware Legged Navigation by Learning from Real-World Visual Data** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.10621) | — |
| 2024 | **State Estimation Transformers for Agile Legged Locomotion** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.13496) | — |
| 2024 | **Learning Semantic Traversability with Egocentric Video and Automated Annotation Strategy** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.02989) | — |
| 2023 | 🌟️ **ViPlanner: Visual Semantic Imperative Learning for Local Navigation** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.00982) | [GitHub](https://github.com/leggedrobotics/viplanner) |
| 2024 | **Learning Robust Autonomous Navigation and Locomotion for Wheeled-Legged Robots** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.01792) | — |
| 2024 | **Wild Visual Navigation: Fast Traversability Learning via Pre-Trained Models and Online Self-Supervision** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.07110) | [GitHub](https://github.com/leggedrobotics/wild_visual_navigation) |
| 2024 | **Agile and Safe Trajectory Planning for Quadruped Navigation with Motion Anisotropy Awareness** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.10101) | — |
| 2023 | **ProNav: Proprioceptive Traversability Estimation for Legged Robot Navigation in Outdoor Environments** | [arXiv 2023.07](https://www.alphaxiv.org/abs/2307.09754) | — |
| 2023 | **Learning to See Physical Properties with Active Sensing Motor Policies** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.01405) | — |
| 2022 | 🌟️ **ViNL: Visual Navigation and Locomotion Over Obstacles** | [arXiv 2022.10](https://www.alphaxiv.org/abs/2210.14791) | [GitHub](https://github.com/SimarKareer/ViNL) |
| 2023 | **Resilient Legged Local Navigation: Learning to Traverse with Compromised Perception End-to-End** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.03581) | — |
| 2023 | **SayTap: Language to Quadrupedal Locomotion** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.07580) | — |
| 2023 | 🌟️ **ANYmal Parkour: Learning Agile Navigation for Quadrupedal Robots** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.14874) | — |
| 2023 | 🌟️ **iPlanner: Imperative Path Planning** | [arXiv 2023.02](https://www.alphaxiv.org/abs/2302.11434) | — |
| 2023 | **Barkour: Benchmarking Animal-level Agility with Quadruped Robots** | [arXiv 2023.05](https://www.alphaxiv.org/abs/2305.14654) | — |
| 2023 | **ArtPlanner: Robust Legged Robot Navigation in the Field** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.01420) | — |
| 2022 | **Advanced Skills by Learning Locomotion and Local Navigation End-to-End** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.12827) | — |
| 2021 | **Coupling Vision and Proprioception for Navigation of Legged Robots** | [arXiv 2021.12](https://www.alphaxiv.org/abs/2112.02094) | [GitHub](https://github.com/MarkFzp/navigation-locomotion) |
| 2022 | **Learning Forward Dynamics Model and Informed Trajectory Sampler for Safe Quadruped Navigation** | [arXiv 2022.04](https://www.alphaxiv.org/abs/2204.08647) | [GitHub](https://github.com/awesomericky/complex-env-navigation) |
| 2022 | **Concurrent Training of a Control Policy and a State Estimator for Dynamic and Robust Legged Locomotion** | [arXiv 2022.02](https://www.alphaxiv.org/abs/2202.05481) | — |
| 2019 | **Contact-Aided Invariant Extended Kalman Filtering for Robot State Estimation** | [arXiv 2019.04](https://www.alphaxiv.org/abs/1904.09251) | — |
| 2017 | **Legged Robot State-Estimation Through Combined Forward Kinematic and Preintegrated Contact Factors** | [arXiv 2017.12](https://www.alphaxiv.org/abs/1712.05873) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 3.4 Generalist Models / World Models Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2026 | **Towards Bridging the Gap between Large-Scale Pretraining and Efficient Finetuning for Humanoid Control** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.21363) | [GitHub](https://github.com/bigai-ai/LIFT-humanoid) |
| 2025 | **Uncertainty-Aware Robotic World Model Makes Offline Model-Based Reinforcement Learning Work on Real Robots** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.16680) | — |
| 2025 | 🌟️ **Robotic World Model: A Neural Network Simulator for Robust Policy Optimization in Robotics** | [arXiv 2025.01](https://www.alphaxiv.org/abs/2501.10100) | [GitHub](https://github.com/leggedrobotics/robotic_world_model)<br>[Train](https://github.com/leggedrobotics/robotic_world_model_lite) |
| 2025 | **Flexible Locomotion Learning with Diffusion Model Predictive Control** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.04234) | [GitHub](https://github.com/hrh6666/Flexible-Locomotion-Learning-with-Diffusion-Model-Predictive-Control) |
| 2025 | **Integrating Diffusion-based Multi-task Learning with Online Reinforcement Learning for Robust Quadruped Robot Control** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.05674) | — |
| 2024 | **Diffusion Model Predictive Control** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.05364) | [GitHub](https://github.com/hrh6666/Flexible-Locomotion-Learning-with-Diffusion-Model-Predictive-Control) |
| 2024 | **PIP-Loco: A Proprioceptive Infinite Horizon Planning Framework for Quadrupedal Robot Locomotion** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.09441) | [GitHub](https://github.com/aceofspades07/pip-loco) |
| 2024 | **Preference Aligned Diffusion Planner for Quadrupedal Locomotion Control** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.13586) | — |
| 2025 | **Learning Humanoid Locomotion with World Model Reconstruction** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.16230) | — |
| 2024 | **World Model-based Perception for Visual Legged Locomotion** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.16784) | [GitHub](https://github.com/bytedance/WMP) |
| 2024 | **Full-Order Sampling-Based MPC for Torque-Level Locomotion Control via Diffusion-Style Annealing** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.15610) | [GitHub](https://github.com/LeCAR-Lab/dial-mpc) |
| 2024 | **Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.14472) | — |
| 2024 | 🌟️ **DiffuseLoco: Real-Time Legged Locomotion Control with Diffusion from Offline Datasets** | [arXiv 2024.04](https://www.alphaxiv.org/abs/2404.19264) | [GitHub](https://github.com/HybridRobotics/DiffuseLoco) |
| 2023 | **Robust Recovery Motion Control for Quadrupedal Robots via Learned Terrain Imagination** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.12712) | — |
| 2022 | 🌟️ **DayDreamer: World Models for Physical Robot Learning** | [arXiv 2022.06](https://www.alphaxiv.org/abs/2206.14176) | [GitHub](https://github.com/danijar/daydreamer) |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 3.5 Cross-Embodied Locomotion

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2025 | **Multi-Embodiment Robotic Retargeting via Guided Diffusion Model** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.20857) | — |
| 2026 | **X-Morph: Human Motion Priors for Scalable Robot Learning Across Morphologies** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.30290) | — |
| 2026 | **Any2Any: Efficient Cross-Embodiment Transfer for Humanoid Whole-Body Tracking** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.23733) | — |
| 2026 | **Scalable and General Whole-Body Control for Cross-Humanoid Locomotion** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.05791) | — |
| 2026 | **Articulated-Body Dynamics Network: Dynamics-Grounded Prior for Robot Learning** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.19078) | — |
| 2026 | **Embodiment-Aware Generalist Specialist Distillation for Unified Humanoid Whole-Body Control** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.02960) | — |
| 2025 | **H-Zero: Cross-Humanoid Locomotion Pretraining Enables Few-shot Novel Embodiment Transfer** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.00971) | — |
| 2024 | 🌟️ **One Policy to Run Them All: an End-to-end Learning Approach to Multi-Embodiment Locomotion** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.06366) | [GitHub](https://github.com/nico-bohlinger/one_policy_to_run_them_all) |
| 2024 | **MorAL: Learning Morphologically Adaptive Locomotion Controller for Quadrupedal Robots on Challenging Terrains** | [RA-L 2024.05](https://doi.org/10.1109/LRA.2024.3375086) | [Project Page](https://arclab-hku.github.io/MorAL_Quadruped_Robots/) |
| 2025 | 🌟️ **LocoFormer: Generalist Locomotion via Long-context Adaptation** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.23745) | [GitHub](https://github.com/lucidrains/locoformer)<br>[GitHub](https://github.com/linden713/BabyLocoFormer) |
| 2025 | **Towards Embodiment Scaling Laws in Robot Locomotion** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.05753) | [GitHub](https://github.com/BoAi01/embodiment-scaling-laws) |
| 2025 | **UniLegs: Universal Multi-Legged Robot Control through Morphology-Agnostic Policy Distillation** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.22653) | — |
| 2025 | **Multi-Loco: Unifying Multi-Embodiment Legged Locomotion via Reinforcement Learning Augmented Diffusion** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.11470) | — |
| 2024 | **PEAC: Unsupervised Pre-training for Cross-Embodiment Reinforcement Learning** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.14073) | [GitHub](https://github.com/thu-ml/CEURL) |
| 2024 | **MetaLoco: Universal Quadrupedal Locomotion with Meta-Reinforcement Learning and Motion Imitation** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.17502) | — |
| 2024 | **Body Transformer: Leveraging Robot Embodiment for Policy Learning** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.06316) | [GitHub](https://github.com/carlosferrazza/BodyTransformer) |
| 2023 | **ManyQuadrupeds: Learning a Single Locomotion Policy for Diverse Quadruped Robots** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.10486) | — |
| 2023 | **CrossLoco: Human Motion Driven Control of Legged Robots via Guided Unsupervised Reinforcement Learning** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.17046) | — |
| 2022 | **Multi-embodiment Legged Robot Control as a Sequence Modeling Problem** | [arXiv 2022.12](https://www.alphaxiv.org/abs/2212.09078) | — |
| 2022 | 🌟️ **GenLoco: Generalized Locomotion Controllers for Quadrupedal Robots** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.05309) | [GitHub](https://github.com/HybridRobotics/GenLoco) |
| 2022 | **Evolution Gym: A Large-Scale Benchmark for Evolving Soft Robots** | [arXiv 2022.01](https://www.alphaxiv.org/abs/2201.09863) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 3.6 Multi-Agent Locomotion

- [alphaXiv shared collection](https://www.alphaxiv.org/shared/folder/019f3561-8958-7973-92ef-fd5a89f342ea)

| Year | Title | Paper | GitHub |
|:----:|-------|-------|--------|
| 2025 | **Diffusion Forcing for Multi-Agent Interaction Sequence Modeling** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.17900) | [GitHub](https://github.com/Von31/MAGNet-code) |
| 2026 | **RoboStriker: Hierarchical Decision-Making for Autonomous Humanoid Boxing** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.22517) | — |
| 2025 | **It Takes Two: Learning Interactive Whole-Body Control Between Humanoid Robots** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.10206) | [GitHub](https://github.com/ZuhongLIU/Harmanoid) |
| 2025 | **Toward Real-World Cooperative and Competitive Soccer with Quadrupedal Robot Teams** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.13834) | — |
| 2024 | **Learning Decentralized Multi-Biped Control for Payload Transport** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.17279) | [GitHub](https://github.com/osudrl/decentralized_multibiped_controller) |
| 2024 | **MQE: Unleashing the Power of Interaction with Multi-agent Quadruped Environment** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.16015) | [GitHub](https://github.com/ziyanx02/multiagent-quadruped-environment) |
| 2025 | **A Framework for Scalable Heterogeneous Multi-Agent Adversarial Reinforcement Learning in IsaacLab** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.01264) | [GitHub](https://github.com/DIRECTLab/IsaacLab-HARL) |
|  |  |  | [Back to top ↑](#table-of-contents) |
