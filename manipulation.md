# 1. Manipulation

> Last updated: 2026-07-27.


## Table of Contents

- [1.1 Model-Based Manipulation](#11-model-based-manipulation)
- [1.2 Data & Benchmarks](#12-data--benchmarks)
- [1.3 Learning-Based Manipulation — RL / IL](#13-learning-based-manipulation--rl--il)
- [1.4 Real2Sim](#14-real2sim)
- [1.5 Policy-Based — Diffusion / Flow](#15-policy-based--diffusion--flow)
- [1.6 Foundation Models — VLA](#16-foundation-models--vla)
- [1.7 World Action Models (WAM)](#17-world-action-models-wam)
- [1.8 Ego-Centric Manipulation](#18-ego-centric-manipulation)

## 1.1 Model-Based Manipulation

### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **cuRoboV2: Faster and More Generalizable GPU Motion Generation** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.05493) | [github](https://github.com/NVlabs/curobo) |
| 2024– | **Tesseract Robotics** | [arXiv 2024](https://www.alphaxiv.org/search?q=Tesseract+Robotics) | [github](https://github.com/tesseract-robotics/tesseract) |
| 2023 | **cuRobo: Parallelized Collision-Free Robot Motion Generation** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.17274) | [github](https://github.com/NVlabs/curobo) |
| 2021 | **MoveIt 2: Manipulation Planning Framework for ROS 2** | [arXiv 2021](https://www.alphaxiv.org/search?q=MoveIt+2%3A+Manipulation+Planning+Framework+for+ROS+2) | [github](https://github.com/moveit/moveit2) |
| 2021 | **Pinocchio: Fast Forward and Inverse Dynamics for Poly-Articulated Systems** | [arXiv 2021](https://www.alphaxiv.org/search?q=Pinocchio%3A+Fast+Forward+and+Inverse+Dynamics+for+Poly-Articulated+Systems) | [github](https://github.com/stack-of-tasks/pinocchio) |
| 2020 | **Crocoddyl: An Efficient and Versatile Framework for Multi-Contact Optimal Control** | [arXiv 2020](https://www.alphaxiv.org/search?q=Crocoddyl%3A+An+Efficient+and+Versatile+Framework+for+Multi-Contact+Optimal+Control) | [github](https://github.com/loco-3d/crocoddyl) |
| 2020 | **PDDLStream: Integrating Symbolic Planners and Blackbox Samplers via Optimistic Adaptive Planning** | [arXiv 2018.02](https://www.alphaxiv.org/abs/1802.08705) | [github](https://github.com/caelan/pddlstream) |
| 2018 | **RMPflow: A Computational Graph for Automatic Motion Policy Generation** | [arXiv 2020.07](https://www.alphaxiv.org/abs/2007.14256) | — |
| 2017 | **TSID: Efficient Inverse Dynamics Under Flexible Constraints** | [arXiv 2017](https://www.alphaxiv.org/search?q=TSID%3A+Efficient+Inverse+Dynamics+Under+Flexible+Constraints) | [github](https://github.com/stack-of-tasks/tsid) |
| 2016 | **Drake: Model-Based Design and Verification for Robotics** | [arXiv 2016](https://www.alphaxiv.org/search?q=Drake%3A+Model-Based+Design+and+Verification+for+Robotics) | [github](https://github.com/RobotLocomotion/drake) |
| 2013 | **TrajOpt: Sequential Convex Optimization for Efficient Robot Motion Planning** | [arXiv 2013](https://www.alphaxiv.org/search?q=TrajOpt%3A+Sequential+Convex+Optimization+for+Efficient+Robot+Motion+Planning) | [github](https://github.com/tesseract-robotics/trajopt) |
| 2011 | **STOMP: Stochastic Trajectory Optimization for Motion Planning** | [arXiv 2011](https://www.alphaxiv.org/search?q=STOMP%3A+Stochastic+Trajectory+Optimization+for+Motion+Planning) | [github](https://github.com/moveit/stomp_moveit) |
| 2009 | **CHOMP: Covariant Hamiltonian Optimization for Motion Planning** | [arXiv 2009](https://www.alphaxiv.org/search?q=CHOMP%3A+Covariant+Hamiltonian+Optimization+for+Motion+Planning) | [github](https://github.com/moveit/moveit2) |
| 1987 | **A Unified Approach for Motion and Force Control of Robot Manipulators: The Operational Space Formulation** | [arXiv 1987](https://www.alphaxiv.org/search?q=A+Unified+Approach+for+Motion+and+Force+Control+of+Robot+Manipulators%3A+The+Operational+Space+Formulation) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.2 Data & Benchmarks

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **Awesome Embodied AI Datasets** | — | [github](https://github.com/freekatz/awesome-embodied-ai-datasets) |
| **Awesome Robotic Benchmarks** | — | [github](https://github.com/HaoranZhangumich/Awesome-Robotic-Benchmarks) |
| **Awesome VLA / WAM Datasets & Benchmarks** | — | [github](https://github.com/ziyaow1010/vla-datasets-benchmarks) |
| **Awesome Robot Learning** | — | [github](https://github.com/RayYoh/Awesome-Robot-Learning) |

### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| Ongoing | **InternDataEngine: Pioneering High-Fidelity Synthetic Data Generator for Robotic Manipulation** | — | [github](https://github.com/InternRobotics/InternDataEngine) |
| 2026 | **Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.13154) | — |
| 2026 | **PRISM: Personalized Robotic Dataset Generation via Image-based Scene and Motion Synthesis** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.04880) | — |
| 2026 | **RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.04434) | [github](https://github.com/RoboDojo-Benchmark/RoboDojo) |
| 2026 | **EVA-Client: A Unified Framework for Deployment, Evaluation, and Data Collection on Real Robots** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.02646) | [github](https://github.com/Noietch/EVA-CLIENT) |
| 2026 | 🌟️ **SimFoundry: Modular and Automated Scene Generation for Policy Learning and Evaluation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.28276) | — |
| 2026 | **PGDG: Physically Grounded Data Generation for Robust Bimanual Policy Learning from a Single Demonstration** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.21710) | — |
| 2026 | **RoboLab: A High-Fidelity Simulation Benchmark for Analysis of Task Generalist Policies** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.09860) | [github](https://github.com/NVlabs/RoboLab) |
| 2026 | 🌟️ **SoftMimicGen: A Data Generation System for Scalable Robot Learning in Deformable Object Manipulation** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.25725) | [github](https://github.com/NVlabs/SoftMimicGen) |
| 2026 | **MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.11337) | [github](https://github.com/allenai/molmospaces) |
| 2026 | **WorldArena: A Unified Benchmark for Evaluating Perception and Functional Utility of Embodied World Models** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.08971) | [github](https://github.com/worldarena/WorldArena) |
| 2026 | **RoboMIND 2.0** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.24653) | [github](https://github.com/x-humanoid-robomind/RoboMIND-dataset-utils) |
| 2025 | **REALM: A Real-to-Sim Validated Benchmark for Generalization in Robotic Manipulation** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.19562) | [github](https://github.com/martin-sedlacek/REALM) |
| 2025 | **RoboChallenge: Large-scale Real-robot Evaluation of Embodied Policies** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.17950) | [github](https://github.com/RoboChallenge/RoboChallengeInference) |
| 2025 | 🌟️ **GraspGen: A Diffusion-based Framework for 6-DOF Grasping with On-Generator Training** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.13097) | [GraspGen](https://github.com/NVlabs/GraspGen)<br>[GraspGenX](https://github.com/NVlabs/GraspGenX) |
| 2025 | **What Matters in Learning from Large-Scale Datasets for Robot Manipulation** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2506.13536) | [github](https://github.com/GaTech-RL2/mimiclabs) |
| 2025 | 🌟️ **RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.18088) | [github](https://github.com/RoboTwin-Platform/RoboTwin) |
| 2025 | **Steerable Scene Generation with Post Training and Inference-Time Search** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.04831) | — |
| 2025 | 🌟️ **RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.18904) | [github](https://github.com/RoboVerseOrg/RoboVerse) |
| 2025 | **Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.13175) | [github](https://github.com/InternRobotics/RoboSplat) |
| 2025 | 🌟️ **AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.06669) | [github](https://github.com/OpenDriveLab/AgiBot-World) |
| 2025 | **Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.20382) | — |
| 2025 | **RoboInter** | [arXiv 2025](https://www.alphaxiv.org/search?q=RoboInter) | [github](https://github.com/InternRobotics/RoboInter) |
| 2025 | **VideoMimic: Visual Imitation Enables Contextual Humanoid Control** | [arXiv 2025](https://www.alphaxiv.org/search?q=VideoMimic%3A+Visual+Imitation+Enables+Contextual+Humanoid+Control) | [github](https://github.com/hongsukchoi/VideoMimic) |
| 2024 | **VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.18194) | [github](https://github.com/OpenMOSS/VLABench) |
| 2024 | **RoboMIND: A Dataset for Large-Scale Multi-Embodiment Robot Manipulation** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.13877) | [github](https://github.com/x-humanoid-robomind/RoboMIND-dataset-utils) |
| 2024 | 🌟️ **DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.24185) | [github](https://github.com/NVlabs/dexmimicgen) |
| 2024 | **SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.18907) | — |
| 2024 | **Automated Creation of Digital Cousins for Robust Policy Learning** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.07408) | — |
| 2024 | 🌟️ **RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.02523) | [github](https://github.com/robocasa/robocasa) |
| 2024 | 🌟️ **Evaluating Real-World Robot Manipulation Policies in Simulation (SimplerEnv)** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.05941) | [github](https://github.com/simpler-env/SimplerEnv) |
| 2024 | **DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.12945) | [github](https://github.com/droid-dataset/droid)<br>[Policy Learning](https://github.com/droid-dataset/droid_policy_learning) |
| 2024 | 🌟️ **BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.09227) | [github](https://github.com/StanfordVL/BEHAVIOR-1K) |
| 2024 | 🌟️ **MimicGen: A Data Generation System for Scalable Robot Learning using Human Demonstrations** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.17596) | [github](https://github.com/NVlabs/mimicgen) |
| 2023 | **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.01455) | — |
| 2023 | 🌟️ **Open X-Embodiment: Robotic Learning Datasets and RT-X Models** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.08864) | [github](https://github.com/google-deepmind/open_x_embodiment) |
| 2023 | **GenSim: Generating Robotic Simulation Tasks via Large Language Models** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.01361) | [github](https://github.com/liruiw/GenSim) |
| 2023 | 🌟️ **LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.03310) | [github](https://github.com/Lifelong-Robot-Learning/LIBERO) |
| 2023 | **RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot** | [arXiv 2023](https://www.alphaxiv.org/search?q=RH20T%3A+A+Comprehensive+Robotic+Dataset+for+Learning+Diverse+Skills+in+One-Shot) | [github](https://github.com/rh20t/rh20t_api) |
| 2023 | **RoboSet: A Diverse Dataset for Robot Learning** | [arXiv 2023](https://www.alphaxiv.org/search?q=RoboSet%3A+A+Diverse+Dataset+for+Robot+Learning) | — |
| 2023 | **RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning** | [arXiv 2023](https://www.alphaxiv.org/search?q=RoboGen%3A+Towards+Unleashing+Infinite+Data+for+Automated+Robot+Learning) | [github](https://github.com/Genesis-Embodied-AI/RoboGen) |
| 2021 | 🌟️ **ManiSkill: Generalizable Manipulation Skill Benchmark with Large-Scale Demonstrations** | [arXiv 2021.07](https://www.alphaxiv.org/abs/2107.14483) | [github](https://github.com/mani-skill/ManiSkill) |
| 2021 | **BridgeData / BridgeData V2** | [arXiv 2021](https://www.alphaxiv.org/search?q=BridgeData+%2F+BridgeData+V2) | [github](https://github.com/rail-berkeley/bridge_data_v2) |
| 2020 | 🌟️ **iGibson 1.0: A Simulation Environment for Interactive Tasks in Large Realistic Scenes** | [arXiv 2020.12](https://www.alphaxiv.org/abs/2012.02924) | [github](https://github.com/StanfordVL/iGibson) |
| 2020 | 🌟️ **robosuite: A Modular Simulation Framework and Benchmark for Robot Learning** | [arXiv 2020.09](https://www.alphaxiv.org/abs/2009.12293) | [github](https://github.com/ARISE-Initiative/robosuite) |
| 2020 | 🌟️ **SAPIEN: A SimulAted Part-based Interactive ENvironment** | [arXiv 2020.03](https://www.alphaxiv.org/abs/2003.08515) | [github](https://github.com/haosulab/SAPIEN) |
| 2019 | 🌟️ **Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning** | [arXiv 2019.10](https://www.alphaxiv.org/abs/1910.10897) | [github](https://github.com/Farama-Foundation/Metaworld) |
| 2019 | 🌟️ **RLBench: The Robot Learning Benchmark & Learning Environment** | [arXiv 2019.09](https://www.alphaxiv.org/abs/1909.12271) | [github](https://github.com/stepjam/RLBench) |
| 2019 | 🌟️ **Habitat: A Platform for Embodied AI Research** | [arXiv 2019.04](https://www.alphaxiv.org/abs/1904.01201) | [github lab](https://github.com/facebookresearch/habitat-lab)<br>[github sim](https://github.com/facebookresearch/habitat-sim) |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.3 Learning-Based Manipulation — RL / IL

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **Awesome Manipulation** | — | [github](https://github.com/curieuxjy/Awesome_Manipulation) |
| **Awesome Robotics Manipulation** | — | [github](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) |
| **Awesome Bimanual Manipulation** | — | [github](https://github.com/Skylark0924/awesome-bimanual-manipulation) |
| **Deep Reinforcement Learning for Robotics: A Survey of Real-World Successes** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.03539) | — |

### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **Robots Acquire Manipulation Skills in Seconds from a Single Human Video** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.20033) | — |
| 2026 | **NeuralActuator: Neural Actuation Modeling for Robot Dynamics and External Force Perception** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.11734) | — |
| 2026 | 🌟️ **Scalable Behavior Cloning with Open Data, Training, and Evaluation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.27375) | [github](https://github.com/amazon-far/abc) |
| 2026 | **Learning Dynamic Rope Manipulation Using Task-Level Iterative Learning Control** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.21302) | — |
| 2026 | **DexImit: Learning Bimanual Dexterous Manipulation from Monocular Human Videos** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.10105) | — |
| 2025 | 🌟️ **RL-100: Performant Robotic Manipulation with Real-World Reinforcement Learning** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.14830) | — |
| 2025 | **Robot Learning from Any Images** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.22970) | — |
| 2025 | **mindmap: Spatial Memory in Deep Feature Maps for 3D Action Policies** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.20297) | — |
| 2025 | **HERMES: Human-to-Robot Embodied Learning from Multi-Source Motion Data for Mobile Dexterous Manipulation** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.20085) | — |
| 2025 | 🌟️ **Mobi-$π$: Mobilizing Your Robot Learning Policy** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.23692) | [github](https://github.com/yjy0625/mobipi) |
| 2025 | 🌟️ **Crossing the Human-Robot Embodiment Gap with Sim-to-Real RL using One Human Demonstration** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.12609) | [github](https://github.com/tylerlum/human2sim2robot) |
| 2025 | 🌟️ **BEHAVIOR Robot Suite: Streamlining Real-World Whole-Body Manipulation for Everyday Household Activities** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.05652) | [Algor](https://github.com/behavior-robot-suite/brs-algo)<br>[Robot](https://github.com/behavior-robot-suite/brs-ctrl) |
| 2025 | **SRSA: Skill Retrieval and Adaptation for Robotic Assembly Tasks** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.04538) | [github](https://github.com/NVlabs/SRSA) |
| 2025 | **Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.24361) | — |
| 2025 | 🌟️🌟️ **HIL-SERL: Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning** | [arXiv 2025](https://www.alphaxiv.org/abs/2410.21845) | [github](https://github.com/rail-berkeley/hil-serl) |
| 2025 | **FACTR: Force-Attending Curriculum Training for Contact-Rich Policy Learning** | [arXiv 2025](https://www.alphaxiv.org/search?q=FACTR%3A+Force-Attending+Curriculum+Training+for+Contact-Rich+Policy+Learning) | — |
| 2024 | **AnyBimanual: Transferring Unimanual Policy for General Bimanual Manipulation** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.06779) | [github](https://github.com/Tengbo-Yu/AnyBimanual) |
| 2024 | **Inference-Time Policy Steering through Human Interactions** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.16627) | — |
| 2024 | **LEGATO: Cross-Embodiment Imitation Using a Grasping Tool** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.03682) | — |
| 2024 | **Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.21845) | — |
| 2024 | **ARCap: Collecting High-quality Human Demonstrations for Robot Learning with Augmented Reality Feedback** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.08464) | — |
| 2024 | 🌟️ **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.20537) | [github](https://github.com/liruiw/HPT) |
| 2024 | 🌟️ **Neural MP: A Generalist Neural Motion Planner** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.05864) | [github](https://github.com/mihdalal/neuralmotionplanner) |
| 2024 | 🌟️ **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.11812) | [github](https://github.com/rail-berkeley/crossformer) |
| 2024 | **A Comparison of Imitation Learning Algorithms for Bimanual Manipulation** | [arXiv 2024.08](https://www.alphaxiv.org/abs/2408.06536) | [github](https://github.com/ir-lab/bimanual-imitation) |
| 2024 | **AutoMate: Specialist and Generalist Assembly Policies over Diverse Geometries** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.08028) | — |
| 2024 | **PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.00278) | [github](https://github.com/markusgrotz/peract_bimanual) |
| 2024 | 🌟️🌟️ **ALOHA 2: An Enhanced Low-Cost Hardware for Bimanual Teleoperation** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.02292) | [github](https://github.com/google-deepmind/aloha_sim) |
| 2024 | **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.01534) | [github](https://github.com/mihdalal/planseqlearn) |
| 2024 | **Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.12943) | — |
| 2024 | 🌟️🌟️ **SERL: A Software Suite for Sample-Efficient Robotic Reinforcement Learning** | [arXiv 2024.01](https://www.alphaxiv.org/abs/2401.16013) | [github](https://github.com/rail-berkeley/serl) |
| 2024 | 🌟️🌟️ **Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation** | [arXiv 2024.01](https://www.alphaxiv.org/abs/2401.02117) | [github](https://github.com/MarkFzp/mobile-aloha)<br>[github](https://github.com/MarkFzp/act-plus-plus) |
| 2024 | **RVT: Robotic View Transformer for 3D Object Manipulation** | [arXiv 2024](https://www.alphaxiv.org/search?q=RVT%3A+Robotic+View+Transformer+for+3D+Object+Manipulation) | [github](https://github.com/NVlabs/RVT) |
| 2024 | **RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking** | [arXiv 2024](https://www.alphaxiv.org/search?q=RoboAgent%3A+Generalization+and+Efficiency+in+Robot+Manipulation+via+Semantic+Augmentations+and+Action+Chunking) | [github](https://github.com/robopen/roboagent) |
| 2024 | **BAKU: An Efficient Transformer for Multi-Task Policy Learning** | [arXiv 2024](https://www.alphaxiv.org/search?q=BAKU%3A+An+Efficient+Transformer+for+Multi-Task+Policy+Learning) | [github](https://github.com/siddhanthaldar/BAKU) |
| 2023 | 🌟️ **On Bringing Robots Home** | [arXiv 2023.11](https://www.alphaxiv.org/abs/2311.16098) | [github](https://github.com/notmahi/dobb-e) |
| 2023 | **GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.16891) | — |
| 2023 | **On the Efficacy of 3D Point Cloud Reinforcement Learning** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.06799) | — |
| 2023 | 🌟️ **IndustReal** | [arXiv 2023.05](https://www.alphaxiv.org/abs/2305.17110) | [github](https://github.com/NVLabs/industreallib) |
| 2023 | 🌟️🌟️ **Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware** | [arXiv 2023.04](https://www.alphaxiv.org/abs/2304.13705) | [github](https://github.com/tonyzhaozh/act) |
| 2023 | 🌟️ **MimicPlay: Long-Horizon Imitation Learning by Watching Human Play** | [arXiv 2023.02](https://www.alphaxiv.org/abs/2302.12422) | [github](https://github.com/j96w/MimicPlay) |
| 2023 | **Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware (ACT)** | [arXiv 2023](https://www.alphaxiv.org/search?q=Learning+Fine-Grained+Bimanual+Manipulation+with+Low-Cost+Hardware+(ACT)) | [github](https://github.com/tonyzhaozh/act) |
| 2023 | 🌟️🌟️ **ALOHA: A Low-Cost Hardware System for Bimanual Teleoperation** | [arXiv 2023](https://www.alphaxiv.org/abs/2304.13705) | [github](https://github.com/tonyzhaozh/aloha) |
| 2022 | **End-to-End Affordance Learning for Robotic Manipulation** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.12941) | — |
| 2022 | 🌟️ **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.05451) | [github](https://github.com/peract/peract) |
| 2022 | **Closed-Loop Next-Best-View Planning for Target-Driven Grasping** | [arXiv 2022.07](https://www.alphaxiv.org/abs/2207.10543) | — |
| 2022 | 🌟️ **Behavior Transformers: Cloning $k$ modes with one stone** | [arXiv 2022.06](https://www.alphaxiv.org/abs/2206.11251) | [github](https://github.com/notmahi/bet) |
| 2022 | **Factory: Fast Contact for Robotic Assembly** | [arXiv 2022.05](https://www.alphaxiv.org/abs/2205.03532) | — |
| 2022 | **R3M: A Universal Visual Representation for Robot Manipulation** | [arXiv 2022](https://www.alphaxiv.org/abs/2203.12601) | [github](https://github.com/facebookresearch/r3m) |
| 2022 | **VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training** | [arXiv 2022](https://www.alphaxiv.org/search?q=VIP%3A+Towards+Universal+Visual+Reward+and+Representation+via+Value-Implicit+Pre-Training) | [github](https://github.com/facebookresearch/vip) |
| 2021 | **OSCAR: Data-Driven Operational Space Control for Adaptive and Robust Robot Manipulation** | [arXiv 2021.10](https://www.alphaxiv.org/abs/2110.00704) | — |
| 2021 | **Implicit Behavioral Cloning** | [arXiv 2021.09](https://www.alphaxiv.org/abs/2109.00137) | [github](https://github.com/google-research/ibc)<br>[torch version](https://github.com/kevinzakka/ibc) |
| 2021 | 🌟️🌟️ **What Matters in Learning from Offline Human Demonstrations for Robot Manipulation** | [arXiv 2021.08](https://www.alphaxiv.org/abs/2108.03298) | [github](https://github.com/ARISE-Initiative/robomimic) |
| 2021 | **How to Train Your Robot with Deep Reinforcement Learning; Lessons We've Learned** | [arXiv 2021.02](https://www.alphaxiv.org/abs/2102.02915) | — |
| 2021 | **BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning** | [arXiv 2021](https://www.alphaxiv.org/search?q=BC-Z%3A+Zero-Shot+Task+Generalization+with+Robotic+Imitation+Learning) | — |
| 2020 | **Transporter Networks: Rearranging the Visual World for Robotic Manipulation** | [arXiv 2020.10](https://www.alphaxiv.org/abs/2010.14406) | [github](https://github.com/google-research/ravens) |
| 2020 | **Accelerating Reinforcement Learning with Learned Skill Priors** | [arXiv 2020.10](https://www.alphaxiv.org/abs/2010.11944) | [github](https://github.com/clvrai/spirl) |
| 2019 | **Grasping in the Wild:Learning 6DoF Closed-Loop Grasping from Low-Cost Demonstrations** | [arXiv 2019.12](https://www.alphaxiv.org/abs/1912.04344) | — |
| 2019 | **IKEA Furniture Assembly Environment for Long-Horizon Complex Manipulation Tasks** | [arXiv 2019.11](https://www.alphaxiv.org/abs/1912.04344) | — |
| 2019 | **TossingBot: Learning to Throw Arbitrary Objects with Residual Physics** | [arXiv 2019.03](https://www.alphaxiv.org/abs/1911.07246) | [github](https://github.com/clvrai/furniture) |
| 2018 | **Visual Foresight: Model-Based Deep Reinforcement Learning for Vision-Based Robotic Control** | [arXiv 2018.12](https://www.alphaxiv.org/abs/1812.00568) | — |
| 2018 | **Learning Synergies between Pushing and Grasping with Self-supervised Deep Reinforcement Learning** | [arXiv 2018.03](https://www.alphaxiv.org/abs/1803.09956) | [github](https://github.com/andyzeng/visual-pushing-grasping) |
| 2018 | **QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation** | [arXiv 2018](https://www.alphaxiv.org/search?q=QT-Opt%3A+Scalable+Deep+Reinforcement+Learning+for+Vision-Based+Robotic+Manipulation) | — |
| 2018 | **SAC-X: Scheduled Auxiliary Control for Many-Task Deep Reinforcement Learning** | [arXiv 2018](https://www.alphaxiv.org/search?q=SAC-X%3A+Scheduled+Auxiliary+Control+for+Many-Task+Deep+Reinforcement+Learning) | — |
| 2016 | **Deep Reinforcement Learning for Robotic Manipulation with Asynchronous Off-Policy Updates** | [arXiv 2016.10](https://www.alphaxiv.org/abs/1610.00633) | — |
| 2015 | **End-to-End Training of Deep Visuomotor Policies (Guided Policy Search)** | [arXiv 2015.04](https://www.alphaxiv.org/abs/1504.00702) | [github](https://github.com/cbfinn/gps) |
| 2011 | **DAgger: A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning** | [arXiv 2011](https://www.alphaxiv.org/search?q=DAgger%3A+A+Reduction+of+Imitation+Learning+and+Structured+Prediction+to+No-Regret+Online+Learning) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.4 Real2Sim

### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.19190) | — |
| 2026 | **RoboSnap: One-Shot Real-to-Sim Scene Generation for Generalizable Robot Learning and Evaluation** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.06699) | — |
| 2026 | **Zero-Shot Sim-to-Real Robot Learning: A Dexterous Manipulation Study on Reactive Catching** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.09789) | — |
| 2026 | **GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.25459) | [github](https://github.com/discoverse-dev/gs_playground) |
| 2026 | **GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.05108) | — |
| 2026 | **D-REX: Differentiable Real-to-Sim-to-Real Engine for Learning Dexterous Grasping** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.01151) | — |
| 2026 | **Squint: Fast Visual Reinforcement Learning for Sim-to-Real Robotics** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.21203) | — |
| 2026 | **SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.02402) | — |
| 2025 | 🌟️ **PolaRiS: Scalable Real-to-Sim Evaluations for Generalist Robot Policies** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.16881) | [train](https://github.com/arhanjain/polaris)<br>[eval](https://github.com/arhanjain/sim-evals) |
| 2025 | 🌟️ **Real-to-Sim Robot Policy Evaluation with Gaussian Splatting Simulation of Soft-Body Interactions** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.04665) | [github](https://github.com/kywind/real2sim-eval) |
| 2025 | 🌟️ **GSWorld: Closed-Loop Photo-Realistic Simulation Suite for Robotic Manipulation** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.20813) | [github](https://github.com/luccachiang/GSWorld) |
| 2025 | 🌟️ **Manipulation as in Simulation: Enabling Accurate Geometry Perception in Robots** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.02530) | [github](https://github.com/ByteDance-Seed/manip-as-in-sim-suite) |
| 2025 | 🌟️ **Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.09601) | [github](https://github.com/uynitsuj/real2render2real) |
| 2025 | **Crossing the Human-Robot Embodiment Gap with Sim-to-Real RL using One Human Demonstration** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.12609) | — |
| 2025 | **Real-is-Sim: Bridging the Sim-to-Real Gap with a Dynamic Digital Twin** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.03597) | — |
| 2025 | **DRAWER: Digital Reconstruction and Articulation With Environment Realism** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.15278) | [github](https://github.com/xiahongchi/DRAWER) |
| 2025 | 🌟️ **PhysTwin: Physics-Informed Reconstruction and Simulation of Deformable Objects from Videos** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.17973) | [github](https://github.com/Jianghanxiao/PhysTwin) |
| 2025 | **ReBot: Scaling Robot Learning with Real-to-Sim-to-Real Robotic Video Synthesis** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.14526) | — |
| 2025 | **Persistent Object Gaussian Splat (POGS) for Tracking Human and Robot Manipulation of Irregularly Shaped Objects** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.05189) | — |
| 2025 | 🌟️ **Scalable Real2Sim: Physics-Aware Asset Generation Via Robotic Pick-and-Place Setups** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.00370) | [github](https://github.com/nepfaff/scalable-real2sim) |
| 2025 | **Re$^3$Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.08645) | [github](https://github.com/InternRobotics/Re3Sim) |
| 2024 | **One-Shot Real-to-Sim via End-to-End Differentiable Simulation and Rendering** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.00259) | — |
| 2024 | **RoboGSim: A Real2Sim2Real Robotic Gaussian Splatting Simulator** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.11839) | — |
| 2024 | 🌟️ **Differentiable Robot Rendering** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.13851) | [github](https://github.com/cvlab-columbia/drrobot) |
| 2024 | **SplatSim: Zero-Shot Sim2Real Transfer of RGB Manipulation Policies Using Gaussian Splatting** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.10161) | [github](https://github.com/qureshinomaan/SplatSim) |
| 2024 | **GraspSplats: Efficient Manipulation with 3D Feature Splatting** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.02084) | — |
| 2024 | **IRASim: A Fine-Grained World Model for Robot Manipulation** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.14540) | — |
| 2024 | 🌟️ **Physically Embodied Gaussian Splatting: A Visually Learnt and Physically Grounded 3D Representation for Robotics** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.10788v1) | [github](https://github.com/rai-opensource/embodied_gaussians) |
| 2024 | **Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.04378) | — |
| 2024 | 🌟️ **ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.08321) | [github](https://github.com/GuanxingLu/ManiGaussian) |
| 2024 | 🌟️ **RialTo: Reconciling Reality Through Simulation** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.03949) | [github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |
| 2023 | **D$^3$Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement** | [arXiv 2023.09](https://www.alphaxiv.org/abs/2309.16118) | [github](https://github.com/WangYixuan12/d3fields) |
| 2023 | **IndustReal: Transferring Contact-Rich Assembly Tasks from Simulation to Reality** | [arXiv 2023.05](https://www.alphaxiv.org/abs/2305.17110) | — |
| 2023 | **Sim2Real$^2$: Actively Building Explicit Physics Model for Precise Articulated Object Manipulation** | [arXiv 2023.02](https://www.alphaxiv.org/abs/2302.10693) | — |
| 2022 | **A Real2Sim2Real Method for Robust Object Grasping with Neural Surface Reconstruction** | [arXiv 2022.10](https://www.alphaxiv.org/abs/2210.02685) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.5 Policy-Based — Diffusion / Flow

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **Awesome UMI** | — | [github](https://github.com/chang-xinhai/Awesome-UMI) |
| **Awesome Robotics Diffusion** | — | [github](https://github.com/showlab/Awesome-Robotics-Diffusion) |
| **VLA-Diffusion-Policy-Robotics / Diffusion Models for Robotic Manipulation: A Survey** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.08438) | [github](https://github.com/EmbodiedMind/VLA-Diffusion-Policy-Robotics) |
| **VLA-Diffusion-Policy-Robotics** | — | [github](https://github.com/iLearn-Lab/VLA-Diffusion-Policy-Robotics) |


### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **B-spline Policy: Accelerating Manipulation Policies via B-spline Action Representations** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.09648) | [github](https://github.com/B-spline-policy/bspline-policy) |
| 2026 | **Behavior Prompting Policy Demonstrations as Prompts for Manipulation** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2606.30457) | [github](https://github.com/real-stanford/behavior_prompting) |
| 2026 | **Abstracting Robot Manipulation Skills via Mixture-of-Experts Diffusion Policies** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.21251) | — |
| 2025 | **Much Ado About Noising: Dispelling the Myths of Generative Robotic Control** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.01809) | [github](https://github.com/simchowitzlabpublic/much-ado-about-noising) |
| 2025 | **ACG: Action Coherence Guidance for Flow-Based VLA Models** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.22201) | [github](https://github.com/DAVIAN-Robotics/ACG) |
| 2025 | **NovaFlow: Zero-Shot Manipulation via Actionable Flow from Generated Videos** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.08568) | [github](https://github.com/rai-opensource/NovaFlow) |
| 2025 | **ManiFlow: A General Robot Manipulation Policy via Consistency Flow Training** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.01819) | [github](https://github.com/geyan21/ManiFlow_Policy) |
| 2025 | **VFP: Variational Flow-Matching Policy for Multi-Modal Robot Manipulation** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.01622) | — |
| 2025 | **Flow Matching Policy Gradients** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.21053) | — |
| 2025 | 🌟️ **Reinforcement Learning with Action Chunking** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.07969) | [github](https://github.com/ColinQiyangLi/qc) |
| 2025 | 🌟️ **A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.05331) | [github train](https://github.com/lucidrains/TRI-LBM)<br>[github eval](https://github.com/ToyotaResearchInstitute/lbm_eval) |
| 2025 | **Steering Your Diffusion Policy with Latent Space Reinforcement Learning** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.15799) | [github](https://github.com/nakamotoo/dsrl_pi0) |
| 2025 | **Vision in Action: Learning Active Perception from Human Demonstrations** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.15666) | [github](https://github.com/haoyu-x/vision-in-action) |
| 2025 | **ReinFlow: Fine-tuning Flow Matching Policy with Online Reinforcement Learning** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.22094) | [github](https://github.com/ReinFlow/ReinFlow) |
| 2025 | **Streaming Flow Policy: Simplifying diffusion/flow-matching policies by treating action trajectories as flow trajectories** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.21851) | [github](https://github.com/siddancha/streaming-flow-policy) |
| 2025 | **Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.02881) | — |
| 2025 | **DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.16932) | [github](https://github.com/TEA-Lab/DemoGen) |
| 2025 | **Flow Q-Learning** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.02538) | [github](https://github.com/seohongpark/fql) |
| 2025 | **FlowPolicy: Fast and Robust 3D Flow-Based Policy via Consistency Flow Matching** | [arXiv 2025](https://www.alphaxiv.org/search?q=FlowPolicy%3A+Fast+and+Robust+3D+Flow-Based+Policy+via+Consistency+Flow+Matching) | [github](https://github.com/zql-kk/FlowPolicy) |
| 2025 | **Spherical Diffusion Policy** | [arXiv 2025](https://www.alphaxiv.org/search?q=Spherical+Diffusion+Policy) | [github](https://github.com/amazon-science/Spherical_Diffusion_Policy) |
| 2025 | **Improved 3D Diffusion Policy (iDP3)** | [arXiv 2025](https://www.alphaxiv.org/search?q=Improved+3D+Diffusion+Policy+(iDP3)) | [github](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy) |
| 2024–2025 | **π0 / π0-FAST / π0.5** | [arXiv 2024](https://www.alphaxiv.org/search?q=%CF%800+%2F+%CF%800-FAST+%2F+%CF%800.5) | [github](https://github.com/Physical-Intelligence/openpi) |
| 2024 | **Efficient Diffusion Transformer Policies with Mixture of Expert Denoisers for Multitask Learning** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.12953) | [github](https://github.com/Fanqi-Lin/Data-Scaling-Laws) |
| 2024 | 🌟️ **RDT-1B: A Diffusion Foundation Model for Bimanual Manipulation** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.07864) | [github](https://github.com/thu-ml/RoboticsDiffusionTransformer) |
| 2024 | 🌟️ **Data Scaling Laws in Imitation Learning for Robotic Manipulation** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.18647) | [github](https://github.com/thu-ml/RoboticsDiffusionTransformer) |
| 2024 | **Affordance-based Robot Manipulation with Flow Matching** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.01083) | [github](https://github.com/HRI-EU/flow-matching-policy) |
| 2024 | 🌟️ **Diffusion Policy Policy Optimization** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.00588) | [github](https://github.com/irom-princeton/dppo) |
| 2024 | **Equivariant Diffusion Policy** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.01812) | [github](https://github.com/pointW/equidiff) |
| 2024 | 🌟️ **Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.01392) | [github](https://github.com/buoyancy99/diffusion-forcing) |
| 2024 | **CleanDiffuser: An Easy-to-use Modularized Library for Diffusion Models in Decision Making** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.09509) | [github](https://github.com/CleanDiffuserTeam/CleanDiffuser) |
| 2024 | 🌟️ **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.03954) | [github](https://github.com/YanjieZe/3D-Diffusion-Policy) |
| 2024 | 🌟️ **VQ-BeT: Behavior Generation with Latent Actions** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.03181) | [github](https://github.com/jayLEE0301/vq_bet_official) |
| 2024 | **Behavior Generation with Latent Actions** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.03181) | — |
| 2024 | 🌟️ **Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots** | [arXiv 2024.02](https://www.alphaxiv.org/abs/2402.10329) | [github](https://github.com/real-stanford/universal_manipulation_interface) |
| 2024 | **EquiBot: SIM(3)-Equivariant Diffusion Policy** | [arXiv 2024](https://www.alphaxiv.org/abs/2407.01479) | [github](https://github.com/yjy0625/equibot) |
| 2024 | **Hierarchical Diffusion Policy for Multi-Task Robotic Manipulation** | [arXiv 2024](https://www.alphaxiv.org/search?q=Hierarchical+Diffusion+Policy+for+Multi-Task+Robotic+Manipulation) | [github](https://github.com/dyson-ai/hdp) |
| 2024 | **Consistency Policy: Accelerated Visuomotor Policies via Consistency Distillation** | [arXiv 2024](https://www.alphaxiv.org/search?q=Consistency+Policy%3A+Accelerated+Visuomotor+Policies+via+Consistency+Distillation) | [github](https://github.com/Aaditya-Prasad/Consistency-Policy) |
| 2024 | 🌟️ **Octo: An Open-Source Generalist Robot Policy** | [arXiv 2024](https://www.alphaxiv.org/search?q=Octo%3A+An+Open-Source+Generalist+Robot+Policy) | [github](https://github.com/octo-models/octo) |
| 2023 | **Diffusion Reward: Learning Rewards via Conditional Video Diffusion** | [arXiv 2023.12](https://www.alphaxiv.org/abs/2312.14134) | [github](https://github.com/TEA-Lab/diffusion_reward) |
| 2023 | **Motion Planning Diffusion: Learning and Planning of Robot Motions with Diffusion Models** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.01557) | — |
| 2023 | **Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition** | [arXiv 2023.07](https://www.alphaxiv.org/abs/2307.14535) | [github](https://github.com/real-stanford/scalingup) |
| 2023 | 🌟️ **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies** | [arXiv 2023.04](https://www.alphaxiv.org/abs/2304.02532) | [github](https://github.com/intuitive-robots/beso) |
| 2023 | 🌟️ **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.04137) | [github](https://github.com/real-stanford/diffusion_policy) |
| 2023 | **Imitating Human Behaviour with Diffusion Models** | [arXiv 2023.01](https://www.alphaxiv.org/abs/2301.10677) | [github](https://github.com/microsoft/Imitating-Human-Behaviour-w-Diffusion) |
| 2022 | **Flow Matching for Generative Modeling** | [arXiv 2022.10](https://www.alphaxiv.org/abs/2210.02747) | — |
| 2022 | **SE(3)-DiffusionFields: Learning smooth cost functions for joint grasp and motion optimization through diffusion** | [arXiv 2022.09](https://www.alphaxiv.org/abs/2209.03855) | [github](https://github.com/robotgradient/grasp_diffusion) |
| 2022 | **Planning with Diffusion for Flexible Behavior Synthesis** | [arXiv 2022.05](https://www.alphaxiv.org/abs/2205.09991) | — |
| 2022 | **Diffuser: Diffusion Models for Offline Reinforcement Learning** | [arXiv 2022](https://www.alphaxiv.org/search?q=Diffuser%3A+Diffusion+Models+for+Offline+Reinforcement+Learning) | [github](https://github.com/jannerm/diffuser) |
| 2022 | **Diffusion-QL: Diffusion Policies as an Expressive Policy Class for Offline Reinforcement Learning** | [arXiv 2022](https://www.alphaxiv.org/search?q=Diffusion-QL%3A+Diffusion+Policies+as+an+Expressive+Policy+Class+for+Offline+Reinforcement+Learning) | [github](https://github.com/Zhendong-Wang/Diffusion-Policies-for-Offline-RL) |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.6 Foundation Models — VLA

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **Large-VLM-based VLA for Robotic Manipulation / Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.13073) | [github](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation) |
| **A Survey on Vision-Language-Action Models: An Action Tokenization Perspective** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.01925) | — |
| **A Survey on Vision-Language-Action Models for Embodied AI** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.14093) | — |
| **Awesome Embodied VLA** | — | [github](https://github.com/jonyzhang2023/awesome-embodied-vla-va-vln) |
| **Awesome RL-VLA for Robotic Manipulation** | — | [github](https://github.com/Denghaoyuan123/Awesome-RL-VLA) |
| **Awesome VLA Robotics** | — | [github](https://github.com/Jiaaqiliu/Awesome-VLA-Robotics) |
| **Awesome VLA** | — | [github](https://github.com/yueen-ma/awesome-vla) |
| **Awesome Robotics Foundation Models** | — | [github](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models) |
| **Awesome-Memory-for-Robotics** | — | [github](https://github.com/Everloom-129/Awesome-Memory-for-Robotics) |


### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **RynnBrain 1.1: Towards More Capable and Generalizable Embodied Foundation Model** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.17977) | — |
| 2026 | 🌟️ **Xiaomi-Robotics-1: Scaling Vision-Language-Action Models with over 100K Hours of Real-World Trajectories** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.15330) | — |
| 2026 | 🌟️ **RoboTTT: Context Scaling for Robot Policies** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.15275) | — |
| 2026 | **Never Too Late for Force: Accelerating VLA Post-Training with Reactive Force Injection** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.14236) | — |
| 2026 | **From Foundation to Application: Improving VLA Models in Practice** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.06403) | — |
| 2026 | **InternVLA-A1.5: Unifying Understanding, Latent Foresight, and Action for Compositional Generalization** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.04988) | — |
| 2026 | **RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.04434) | [github](https://github.com/RoboDojo-Benchmark/RoboDojo) |
| 2026 | **ASPIRE: Agentic /Skills Discovery for Robotics** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.00272) | — |
| 2026 | 🌟️ **ENPIRE: Agentic Robot Policy Self-Improvement in the Real World** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.19980) | — |
| 2026 | **MolmoMotion: Forecasting Point Trajectories in 3D with Language Instruction** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.18558) | [github](https://github.com/allenai/molmo-motion) |
| 2026 | **Qwen-RobotManip Technical Report: Alignment Unlocks Scale for Robotic Manipulation Foundation Models** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.17846) | — |
| 2026 | **Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.30280) | — |
| 2026 | **RLDX-1 Technical Report** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.03269) | — |
| 2026 | 🌟️ **MolmoAct2: Action Reasoning Models for Real-world Deployment** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.02881) | [github](https://github.com/allenai/molmoact2) |
| 2026 | **Learning While Deploying: Fleet-Scale Reinforcement Learning for Generalist Robot Policies** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.00416) | — |
| 2026 | 🌟️ **$π_{0.7}$: a Steerable Generalist Robotic Foundation Model with Emergent Capabilities** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.15483) | — |
| 2026 | **Grounding Sim-to-Real Generalization in Robotic Manipulation: An Empirical Study with Vision-Language-Action Models** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.22876) | — |
| 2026 | **CaP-X: A Framework for Benchmarking and Improving Coding Agents for Robot Manipulation** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.22435) | — |
| 2026 | **Scaling Verification Can Be More Effective than Scaling Policy Learning for Vision-Language-Action Alignment** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.12281) | — |
| 2026 | **LAP: Language-Action Pre-Training Enables Zero-shot Cross-Embodiment Transfer** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.10556) | — |
| 2026 | **BagelVLA: Enhancing Long-Horizon Manipulation via Interleaved Vision-Language-Action Generation** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.09849) | — |
| 2026 | **VLS: Steering Pretrained Robot Policies via Vision-Language Models** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.03973) | — |
| 2026 | **A Pragmatic VLA Foundation Model** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.18692) | — |
| 2026 | **ACoT-VLA: Action Chain-of-Thought for Vision-Language-Action Models** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.11404) | — |
| 2026 | **Fast-ThinkAct: Efficient Vision-Language-Action Reasoning via Verbalizable Latent Planning** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.09708) | — |
| 2025–2026 | **GR00T N1 / N1.5 / N1.6 / N1.7** | [arXiv 2025](https://www.alphaxiv.org/search?q=GR00T+N1+%2F+N1.5+%2F+N1.6+%2F+N1.7) | [github](https://github.com/NVIDIA/Isaac-GR00T) |
| 2026 | **LLaVA-VLA** | [arXiv 2026](https://www.alphaxiv.org/search?q=LLaVA-VLA) | [github](https://github.com/OpenHelix-Team/LLaVA-VLA) |
| 2026 | **WholeBodyVLA** | [arXiv 2026](https://www.alphaxiv.org/search?q=WholeBodyVLA) | [github](https://github.com/OpenDriveLab/WholebodyVLA) |
| 2025–2026 | **Being-H0 / H0.5 / H0.7** | [arXiv 2025](https://www.alphaxiv.org/search?q=Being-H0+%2F+H0.5+%2F+H0.7) | [github](https://github.com/BeingBeyond/Being-H) |
| 2025 | **Mind to Hand: Purposeful Robotic Control via Embodied Reasoning** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.08580) | — |
| 2025 | 🌟️ **GR-RL: Going Dexterous and Precise for Long-Horizon Robotic Manipulation** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.01801) | — |
| 2025 | **MiMo-Embodied: X-Embodied Foundation Model Technical Report** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.16518) | — |
| 2025 | 🌟️ **$π^{*}_{0.6}$: a VLA That Learns From Experience** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.14759) | — |
| 2025 | **Self-Improving Vision-Language-Action Models with Data Generation via Residual RL** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.00091) | — |
| 2025 | **X-VLA: Soft-Prompted Transformer as Scalable Cross-Embodiment Vision-Language-Action Model** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.10274) | — |
| 2025 | **SimpleVLA-RL: Scaling VLA Training via Reinforcement Learning** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.09674) | [github](https://github.com/PRIME-RL/SimpleVLA-RL) |
| 2025 | **VLA-Adapter: An Effective Paradigm for Tiny-Scale Vision-Language-Action Model** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.09372) | — |
| 2025 | **Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.19958) | — |
| 2025 | **MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.19236) | — |
| 2025 | **ReconVLA: Reconstructive Vision-Language-Action Model as Effective Robot Perceiver** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.10333) | — |
| 2025 | **ThinkAct: Vision-Language-Action Reasoning via Reinforced Visual Latent Planning** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.16815) | — |
| 2025 | **Being-H0: Vision-Language-Action Pretraining from Large-Scale Human Videos** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.15597) | [github](https://github.com/BeingBeyond/Being-H0) |
| 2025 | 🌟️ **GR-3 Technical Report** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.15493) | — |
| 2025 | **Is Diversity All You Need for Scalable Robotic Manipulation?** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.06219) | — |
| 2025 | **Training-Time Action Conditioning for Efficient Real-Time Chunking** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.05964) | [github](https://github.com/Physical-Intelligence/real-time-chunking-kinetix) |
| 2025 | **Real-Time Execution of Action Chunking Flow Policies** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.07339) | [github](https://github.com/Physical-Intelligence/real-time-chunking-kinetix) |
| 2025 | **SmolVLA: A Vision-Language-Action Model for Affordable and Efficient Robotics** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.01844) | [github](https://github.com/huggingface/lerobot) |
| 2025 | 🌟️ **VLA-RL: Towards Masterful and General Robotic Manipulation with Scalable Reinforcement Learning** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.18719) | [github](https://github.com/GuanxingLu/vlarl) |
| 2025 | **UniVLA: Learning to Act Anywhere with Task-centric Latent Actions** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.06111) | [github](https://github.com/OpenDriveLab/UniVLA) |
| 2025 | 🌟️ **$π_{0.5}$: a Vision-Language-Action Model with Open-World Generalization** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.16054) | — |
| 2025 | 🌟️ **CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.22020) | — |
| 2025 | **Gemini Robotics: Bringing AI into the Physical World** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.20020) | — |
| 2025 | **HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.10631) | [github](https://github.com/PKU-HMI-Lab/Hybrid-VLA) |
| 2025 | **Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success** | [arXiv 2025.02](https://www.alphaxiv.org/abs/2502.19645) | [github](https://github.com/moojink/openvla-oft) |
| 2025 | **FAST: Efficient Action Tokenization for Vision-Language-Action Models** | [arXiv 2025.01](https://www.alphaxiv.org/abs/2501.09747) | — |
| 2025 | 🌟️ **π0 / π0-FAST / π0.5** | [arXiv 2024](https://www.alphaxiv.org/search?q=%CF%800+%2F+%CF%800-FAST+%2F+%CF%800.5) | [github](https://github.com/Physical-Intelligence/openpi) |
| 2025 | 🌟️ **SmolVLA** | [arXiv 2025](https://www.alphaxiv.org/search?q=SmolVLA) | [github](https://github.com/huggingface/lerobot) |
| 2025 | **Gemini Robotics** | [arXiv 2025](https://www.alphaxiv.org/search?q=Gemini+Robotics) | — |
| 2025 | **EvoVLA** | [arXiv 2025](https://www.alphaxiv.org/search?q=EvoVLA) | [github](https://github.com/AIGeeksGroup/EvoVLA) |
| 2024 | 🌟️ **$π_0$: A Vision-Language-Action Flow Model for General Robot Control** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.24164) | — |
| 2024 | **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.17772) | — |
| 2024 | 🌟️ **ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation** | [arXiv 2024.09](https://www.alphaxiv.org/abs/2409.01652) | [github](https://github.com/huangwl18/ReKep) |
| 2024 | **Robotic Control via Embodied Chain-of-Thought Reasoning** | [arXiv 2024.07](https://www.alphaxiv.org/abs/2407.08693) | [github](https://github.com/MichalZawalski/embodied-CoT) |
| 2024 | 🌟️ **OpenVLA** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.09246) | [github](https://github.com/openvla/openvla) |
| 2024 | 🌟️ **Octo: An Open-Source Generalist Robot Policy** | [arXiv 2024.05](https://www.alphaxiv.org/abs/2405.12213) | [github](https://github.com/octo-models/octo) |
| 2024 | **GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping** | [arXiv 2024.03](https://www.alphaxiv.org/abs/2403.09637) | — |
| 2024 | 🌟️ **RDT-1B** | [arXiv 2024](https://www.alphaxiv.org/search?q=RDT-1B) | [github](https://github.com/thu-ml/RoboticsDiffusionTransformer) |
| 2024 | **CogACT** | [arXiv 2024](https://www.alphaxiv.org/search?q=CogACT) | [github](https://github.com/microsoft/CogACT) |
| 2024 | **SpatialVLA** | [arXiv 2024](https://www.alphaxiv.org/search?q=SpatialVLA) | [github](https://github.com/SpatialVLA/SpatialVLA) |
| 2023 | 🌟️ **Open X-Embodiment: Robotic Learning Datasets and RT-X Models** | [arXiv 2023.10](https://www.alphaxiv.org/abs/2310.08864) | [github](https://github.com/google-deepmind/open_x_embodiment) |
| 2023 | **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation** | [arXiv 2023.08](https://www.alphaxiv.org/abs/2308.07931) | — |
| 2023 | 🌟️ **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** | [arXiv 2023.07](https://www.alphaxiv.org/abs/2307.15818) | [github](https://github.com/google-research/robotics_transformer) |
| 2023 | **RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.11706) | — |
| 2023 | **A Universal Semantic-Geometric Representation for Robotic Manipulation** | [arXiv 2023.06](https://www.alphaxiv.org/abs/2306.10474) | — |
| 2023 | **PaLM-E: An Embodied Multimodal Language Model** | [arXiv 2023.03](https://www.alphaxiv.org/abs/2303.03378) | — |
| 2023 | **RoboCat: A Self-Improving Foundation Agent for Robotic Manipulation** | [arXiv 2023](https://www.alphaxiv.org/search?q=RoboCat%3A+A+Self-Improving+Foundation+Agent+for+Robotic+Manipulation) | — |
| 2023 | 🌟️ **Open X-Embodiment / RT-X** | [arXiv 2023](https://www.alphaxiv.org/search?q=Open+X-Embodiment+%2F+RT-X) | [github](https://github.com/google-deepmind/open_x_embodiment) |
| 2022 | 🌟️ **RT-1: Robotics Transformer for Real-World Control at Scale** | [arXiv 2022.12](https://www.alphaxiv.org/abs/2212.06817) | [github](https://github.com/google-research/robotics_transformer) |
| 2022 | **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances** | [arXiv 2022.04](https://www.alphaxiv.org/abs/2204.01691) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.7 World Action Models (WAM)

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **From World Models to World Action Models: A Concise Tutorial for Robotics** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.00836) | [github](https://github.com/clearlab-sustech/WorldModelSurvey) |
| **Awesome World Model for Robotics Policy / World Model for Robot Learning: A Comprehensive Survey** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.00080) | [github](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy) |
| **Awesome WAM** | — | [github](https://github.com/OpenMOSS/Awesome-WAM) |
| **Awesome VLA WAM** | — | [github](https://github.com/DravenALG/awesome-vla-wam) |
| **Awesome World Models for Manipulation** | — | [github](https://github.com/jacob-zietek/awesome-world-models-manipulation) |
| **Awesome World Action Models** | — | [github](https://github.com/HyperbolicCurve/Awesome-World-Action-Model) |
| **Awesome World Models for Robots** | — | [github](https://github.com/operator22th/awesome-world-models-for-robots) |
| **World Action Models: A Survey** | — | [github](https://github.com/world-action-models/awesome-world-action-models) |
| **Awesome Robot Learning from Human Videos** | — | [github](https://github.com/IRMVLab/awesome-robot-learning-from-human-videos) |
| **Awesome-Video-Robotic-Papers** | — | [github](https://github.com/H-Freax/Awesome-Video-Robotic-Papers) |
| **Awesome-Video-Action-Models** | — | [github](https://github.com/BofangJia/Awesome-Video-Action-Model) |



### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| 2026 | **Masked Visual Actions for Unified World Modeling** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.19343) | — |
| 2026 | **DriftWorld: Fast World Modeling through Drifting** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.15065) | — |
| 2026 | 🌟️ **GigaWorld-Policy-0.5: A Faster and Stronger WAM Empowered by AutoResearch** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.13960) | [github](https://github.com/open-gigaai/giga-world-policy) |
| 2026 | **FlowWAM: Optical Flow as a Unified Action Representation for World Action Models** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.13017) | — |
| 2026 | **From World Action Models to Embodied Brains: A Roadmap for Open-World Physical Intelligence** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.11689) | — |
| 2026 | 🌟️ **Xiaomi-Robotics-U0: Unified Embodied Synthesis with World Foundation Model** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.11643) | — |
| 2026 | **Towards Predictive, Aligned, and Scalable Robot Learning** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.11270) | — |
| 2026 | **WAM-TTT: Steering World-Action Models by Watching Human Play at Test Time** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.06988) | — |
| 2026 | **RynnWorld-4D: 4D Embodied World Models for Robotic Manipulation** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.06559) | — |
| 2026 | **DSWAM: Dual-Stream World Action Model** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.04927) | — |
| 2026 | 🌟️ **GigaWorld-1: A Roadmap to Build World Models for Robot Policy Evaluation** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.02642) | [github](https://github.com/open-gigaai/giga-world-1) |
| 2026 | **ABot-M0.5: Unified Mobility-and-Manipulation World Action Model** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.00678) | [github](https://github.com/amap-cvlab/ABot-Manipulation) |
| 2026 | **Tactile-WAM: Touch-Aware World Action Model with Tactile Asymmetric Attention** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.26663) | — |
| 2026 | **World Value Models for Robotic Manipulation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.24742) | — |
| 2026 | **IOI: Decoupling Kinematics and Physics for Interactive World Models** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.23296) | — |
| 2026 | **Vesta: A Generalist Embodied Reasoning Model** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.20905) | — |
| 2026 | **Ambient Diffusion Policy: Imitation Learning from Suboptimal Data in Robotics** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.12365) | — |
| 2026 | 🌟️ **AHA-WAM:Asynchronous Horizon-Adaptive World-Action Modeling with Observation-Guided Context Routing** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.09811) | [github](https://github.com/serene-sivy/AHA-WAM) |
| 2026 | **MotionWAM: Motion-Aware World Action Model for Humanoid Loco-Manipulation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.09215) | — |
| 2026 | **Cosmos 3: Omnimodal World Models for Physical AI** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.02800) | — |
| 2026 | **τ0-WM: A Unified Video-Action World Model for Robotic Manipulation** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.01027) | [github](https://github.com/sii-research/tau-0-wm) |
| 2026 | **World Action Models: The Next Frontier in Embodied AI** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.12090) | — |
| 2026 | **OA-WAM: Object-Aware World Action Model** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.06481) | — |
| 2026 | 🌟️ **Being-H0.7: A Latent World-Action Model from Egocentric Videos** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.00078) | [github](https://github.com/BeingBeyond/Being-H) |
| 2026 | 🌟️ **LeWorldModel: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.19312) | [github](https://github.com/lucas-maes/le-wm) |
| 2026 | **ManiDreams: An Open-Source Library for Robust Object Manipulation via Uncertainty-aware Task-specific Intuitive Physics** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.18336) | [github](https://github.com/Rice-RobotPI-Lab/ManiDreams) |
| 2026 | 🌟️ **Fast-WAM: Do World Action Models Need Test-time Future Imagination?** | [arXiv 2026.03](https://www.alphaxiv.org/abs/2603.16666) | [github](https://github.com/yuantianyuan01/FastWAM) |
| 2026 | **World Guidance: World Modeling in Condition Space for Action Generation** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.22010) | [github](https://github.com/Selen-Suyue/WoG) |
| 2026 | 🌟️ **World Action Models are Zero-shot Policies** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.15922) | [github](https://github.com/dreamzero0/dreamzero) |
| 2026 | **RynnBrain: Open Embodied Foundation Models** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.14979) | [github](https://github.com/alibaba-damo-academy/RynnBrain) |
| 2026 | **LDA-1B: Scaling Latent Dynamics Action Model via Universal Embodied Data Ingestion** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.12215) | [github](https://github.com/jiangranlv/LDA-1B) |
| 2026 | **RISE: Self-Improving Robot Policy with Compositional World Model** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.12215) | [github](https://github.com/OpenDriveLab/RISE) |
| 2026 | 🌟️ **VLA-JEPA: Enhancing Vision-Language-Action Model with Latent World Model** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.10098) | [github](https://github.com/ginwind/VLA-JEPA) |
| 2026 | 🌟️ **DreamDojo: A Generalist Robot World Model from Large-Scale Human Videos** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.06949) | [github](https://github.com/NVIDIA/DreamDojo) |
| 2026 | 🌟️ **Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.16163) | [github](https://github.com/nvlabs/cosmos-policy) |
| 2026 | 🌟️ **PointWorld: Scaling 3D World Models for In-The-Wild Robotic Manipulation** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.03782) | [github](https://github.com/NVlabs/PointWorld) |
| 2026 | 🌟️ **WALL-WM: Carving World Action Modeling at the Event Joints** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2606.01955) | [github](https://github.com/X-Square-Robot/wall-x) |
| 2026 | 🌟️ **LingBot-VA: Causal World Modeling for Robot Control** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.21998) | [github](https://github.com/Robbyant/lingbot-va) |
| 2026 | **Being-H0.7: A World Action Model for Humanoid Loco-Manipulation** | [arXiv 2026](https://www.alphaxiv.org/search?q=Being-H0.7%3A+A+World+Action+Model+for+Humanoid+Loco-Manipulation) | [github](https://github.com/BeingBeyond/Being-H) |
| 2025 | 🌟️ **What Drives Success in Physical Planning with Joint-Embedding Predictive World Models?** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.24497) | [github](https://github.com/facebookresearch/jepa-wms) |
| 2025 | **Large Video Planner Enables Generalizable Robot Control** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.15840) | [github](https://github.com/buoyancy99/large-video-planner) |
| 2025 | 🌟️ **mimic-video: Video-Action Models for Generalizable Robot Control Beyond VLAs** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.15692) | [github](https://github.com/mimic-video/mimic-video)<br>[github](https://github.com/lucidrains/mimic-video) |
| 2025 | 🌟️ **Motus: A Unified Latent Action World Model** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.13030) | [github](https://github.com/thu-ml/Motus) |
| 2025 | **Evaluating Gemini Robotics Policies in a Veo World Simulator** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.10675) | — |
| 2025 | 🌟️ **GigaWorld-0: World Models as Data Engine to Empower Embodied AI** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.19861) | [github](https://github.com/open-gigaai/giga-world-0) |
| 2025 | 🌟️ **GigaWorld-0: World Models as Data Engine to Empower Embodied AI** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.19861) | [github](https://github.com/open-gigaai/giga-world-0) |
| 2025 | **WMPO: World Model-based Policy Optimization for Vision-Language-Action Models** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.09515) | [github](https://github.com/WM-PO/WMPO) |
| 2025 | **RynnVLA-002: A Unified Vision-Language-Action and World Model** | [arXiv 2025.11](https://www.alphaxiv.org/abs/2511.17502) | [github](https://github.com/alibaba-damo-academy/RynnVLA-002) |
| 2025 | **GigaBrain-0: A World Model-Powered Vision-Language-Action Model** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.19430) | [github](https://github.com/open-gigaai/giga-brain-0) |
| 2025 | **Ctrl-World: A Controllable Generative World Model for Robot Manipulation** | [arXiv 2025.10](https://www.alphaxiv.org/abs/2510.10125) | [github](https://github.com/Robert-gyj/Ctrl-World) |
| 2025 | **Video models are zero-shot learners and reasoners** | [arXiv 2025.09](https://www.alphaxiv.org/abs/2509.20328) | — |
| 2025 | 🌟️ **MolmoAct: Action Reasoning Models that can Reason in Space** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.07917) | [github](https://github.com/allenai/molmoact) |
| 2025 | 🌟️ **Genie Envisioner: A Unified World Foundation Platform for Robotic Manipulation** | [arXiv 2025.08](https://www.alphaxiv.org/abs/2508.05635) | [github](https://github.com/AgibotTech/Genie-Envisioner) |
| 2025 | **ParticleFormer: A 3D Point Cloud World Model for Multi-Object, Multi-Material Robotic Manipulation** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.23126) | — |
| 2025 | **WorldVLA: Towards Autoregressive Action World Model** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.21539) | [github](https://github.com/alibaba-damo-academy/WorldVLA) |
| 2025 | 🌟️ **V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning** | [arXiv 2025.06](https://www.alphaxiv.org/abs/2506.09985) | [github](https://github.com/facebookresearch/vjepa2) |
| 2025 | **FLARE: Robot Learning with Implicit World Modeling** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.15659) | — |
| 2025 | 🌟️ **DreamGen: Unlocking Generalization in Robot Learning through Video World Models** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.12705) | [github](https://github.com/NVIDIA/GR00T-Dreams) |
| 2025 | **EWMBench: Evaluating Scene, Motion, and Semantic Quality in Embodied World Models** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.09694) | [github](https://github.com/AgibotTech/EWMBench) |
| 2025 | **TesserAct: Learning 4D Embodied World Models** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.20995) | [github](https://github.com/UMass-Embodied-AGI/TesserAct) |
| 2025 | **Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets** | [arXiv 2025.04](https://www.alphaxiv.org/abs/2504.02792) | [github](https://github.com/WEIRDLabUW/unified-world-model) |
| 2025 | **AdaWorld: Learning Adaptable World Models with Latent Actions** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.18938) | — |
| 2025 | **Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.15558) | — |
| 2025 | 🌟️ **GR00T N1: An Open Foundation Model for Generalist Humanoid Robots** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.14734) | — |
| 2025 | **Cosmos-Transfer1: Conditional World Generation with Adaptive Multimodal Control** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.14492) | [github](https://github.com/nvidia-cosmos/cosmos-transfer1) |
| 2025 | **Unified Video Action Model** | [arXiv 2025.03](https://www.alphaxiv.org/abs/2503.00200) | [github](https://github.com/ShuangLI59/unified_video_action) |
| 2025 | 🌟️ **Cosmos World Foundation Model Platform for Physical AI** | [arXiv 2025.01](https://www.alphaxiv.org/abs/2501.03575) | — |
| 2025 | **World Action Models: Coupling Video Prediction with Action Generation** | [arXiv 2025](https://www.alphaxiv.org/search?q=World+Action+Models%3A+Coupling+Video+Prediction+with+Action+Generation) | [github](https://github.com/BeingBeyond/Being-H) |
| 2024 | 🌟️ **PREDICTIVE INVERSE DYNAMICS MODELS ARE SCAL-ABLE LEARNERS FOR ROBOTIC MANIPULATION** | [arXiv 2024.12](https://www.alphaxiv.org/abs/2412.15109) | [github](https://github.com/InternRobotics/Seer) |
| 2024 | 🌟️ **DINO-WM: World Models on Pre-trained Visual Features enable Zero-shot Planning** | [arXiv 2024.11](https://www.alphaxiv.org/abs/2411.04983) | [github](https://github.com/gaoyuezhou/dino_wm) |
| 2024 | 🌟️ **Latent Action Pretraining from Videos** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.11758) | [github](https://github.com/LatentActionPretraining/LAPA) |
| 2024 | **Learning Manipulation by Predicting Interaction** | [arXiv 2024.06](https://www.alphaxiv.org/abs/2406.00439) | [github](https://github.com/OpenDriveLab/MPI) |
| 2021 | **Discovering and Achieving Goals via World Models** | [arXiv 2021.10](https://www.alphaxiv.org/abs/2110.09514) | — |
|  |  |  | [Back to top ↑](#table-of-contents) |

## 1.8 Ego-Centric Manipulation

### Surveys & Awesome Lists

| Title | Paper | github |
|-------|-------|--------|
| **Learning by Watching: A Review of Video-based Learning Approaches for Robot Manipulation** | [arXiv 2024.02](https://www.alphaxiv.org/abs/2402.07127) | — |
| **Awesome Ego Video Datasets** | — | [github](https://github.com/player0718/awesome-ego-video-datasets) |

### Papers

| Year | Title | Paper | github |
|:----:|-------|-------|--------|
| Ongoing | **Hand Tracking Streamer: Meta Quest Hand and Wrist Telemetry for Robotics** | — | [github](https://github.com/wengmister/hand-tracking-streamer) |
| 2026 | **Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.14183) | [github](https://github.com/ant-research/Open-AoE) |
| 2026 | **EgoWAM: World Action Models Beyond Pixels with In-the-Wild Egocentric Human Data** | [arXiv 2026.07](https://www.alphaxiv.org/abs/2607.08436) | — |
| 2026 | **EgoInfinity: A Web-Scale 4D Hand-Object Interaction Data Engine for Any-View Robot Retargeting and Video-to-Action Robot Learning** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.17385) | [github](https://github.com/Rice-RobotPI-Lab/EgoInfinity) |
| 2026 | **EgoEngine: From Egocentric Human Videos to High-Fidelity Dexterous Robot Demonstrations** | [arXiv 2026.06](https://www.alphaxiv.org/abs/2606.12604) | — |
| 2026 | 🌟️ **HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.24934) | [github](https://github.com/TX-Leo/HumanEgo) |
| 2026 | **HumanNet: Scaling Human-centric Video Learning to One Million Hours** | [arXiv 2026.05](https://www.alphaxiv.org/abs/2605.06747) | [github](https://github.com/DAGroup-PKU/HumanNet) |
| 2026 | 🌟️ **EgoVerse: An Egocentric Human Dataset for Robot Learning from Around the World** | [arXiv 2026.04](https://www.alphaxiv.org/abs/2604.07607) | [github](https://github.com/GaTech-RL2/EgoVerse) |
| 2026 | **AoE: Always-on Egocentric Human Video Collection for Embodied AI** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.23893) | — |
| 2026 | **WHOLE: World-Grounded Hand-Object Lifted from Egocentric Videos** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.22209) | — |
| 2026 | 🌟️ **EgoScale: Scaling Dexterous Manipulation with Diverse Egocentric Human Data** | [arXiv 2026.02](https://www.alphaxiv.org/abs/2602.16710) | — |
| 2026 | **Being-H0.5: Scaling Human-Centric Robot Learning for Cross-Embodiment Generalization** | [arXiv 2026.01](https://www.alphaxiv.org/abs/2601.12993) | [github](https://github.com/BeingBeyond/Being-H) |
| 2025–2026 | **Being-H0 / H0.5** | [arXiv 2025](https://www.alphaxiv.org/search?q=Being-H0+%2F+H0.5) | [github](https://github.com/BeingBeyond/Being-H) |
| 2026 | 🌟️ **EgoHumanoid** | [arXiv 2026](https://www.alphaxiv.org/search?q=EgoHumanoid) | [github](https://github.com/OpenDriveLab/EgoHumanoid) |
| 2025 | **World In Your Hands: A Large-Scale and Open-Source Ecosystem for Learning Human-Centric Manipulation in the Wild** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.24310) | [github](https://github.com/tars-robotics/World-In-Your-Hands) |
| 2025 | **EgoX: Egocentric Video Generation from a Single Exocentric Video** | [arXiv 2025.12](https://www.alphaxiv.org/abs/2512.08269) | [github](https://github.com/DAVIAN-Robotics/EgoX) |
| 2025 | 🌟️ **EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos** | [arXiv 2025.07](https://www.alphaxiv.org/abs/2507.12440) | [github](https://github.com/RchalYang/EgoVLA_Release)<br>[github benchmark](https://github.com/quincy-u/Ego_Humanoid_Manipulation_Benchmark) |
| 2025 | **EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video** | [arXiv 2025.05](https://www.alphaxiv.org/abs/2505.11709) | [github](https://github.com/apple/ml-egodex) |
| 2025 | **VideoMimic** | [arXiv 2025](https://www.alphaxiv.org/search?q=VideoMimic) | [github](https://github.com/hongsukchoi/VideoMimic) |
| 2025 | **EMMA: Egocentric Multi-Modal Mobile Manipulation** | [arXiv 2025](https://www.alphaxiv.org/search?q=EMMA%3A+Egocentric+Multi-Modal+Mobile+Manipulation) | — |
| 2025 | **Gen2Act** | [arXiv 2025](https://www.alphaxiv.org/search?q=Gen2Act) | — |
| 2025 | **Track2Act** | [arXiv 2025](https://www.alphaxiv.org/search?q=Track2Act) | — |
| 2024 | **EgoMimic: Scaling Imitation Learning via Egocentric Video** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.24221) | [github](https://github.com/SimarKareer/EgoMimic) |
| 2024 | **Estimating Body and Hand Motion in an Ego-sensed World (egoallo)** | [arXiv 2024.10](https://www.alphaxiv.org/abs/2410.03665) | [github](https://github.com/brentyi/egoallo) |
| 2024 | **DexCap** | [arXiv 2024](https://www.alphaxiv.org/search?q=DexCap) | [github](https://github.com/j96w/DexCap) |
| 2024 | **Ego-Exo4D** | [arXiv 2024](https://www.alphaxiv.org/search?q=Ego-Exo4D) | [github](https://github.com/facebookresearch/Ego-Exo4D) |
| 2024 | **HOT3D** | [arXiv 2024](https://www.alphaxiv.org/search?q=HOT3D) | [github](https://github.com/facebookresearch/hot3d) |
| 2021 | **Ego4D: Around the World in 3,000 Hours of Egocentric Video** | [arXiv 2021.10](https://www.alphaxiv.org/abs/2110.07058) | [github](https://github.com/facebookresearch/Ego4d) |
|  |  |  | [Back to top ↑](#table-of-contents) |
