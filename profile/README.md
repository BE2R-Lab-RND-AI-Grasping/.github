# AI-Driven Co-Design of Robotic Hands for Functional Grasping

It is an organisation for a project "Using AI for the co-synthesis of control systems and robotic hand designs to enable functional grasping of tools and manipulation objects." The project is being developed at ITMO University. 

### Objective:
This project aims to simplify the integration of robotic hands into robotic cells by developing AI-based methods for co-optimizing control and design of robotic hands. 

The project focuses on **functional grasps**, which refer to robotic gripping strategies that go beyond relatively simple pick-and-place tasks. To grasp an object at a special area and to get a specific orientation of an object such that it can be used as a tool. Unlike basic pick-and-place, functional grasps require tight integration of perception, mechanics, and control to ensure the object is not only stable but also functionally ready for its intended task.

Co-Design methodology is used to modify mechanics to get better performence of the control system. Optimized hands topology and finger shapes (e.g., soft pads, curved surfaces) paired with control policies to enhance dexterity, especially in underactuated or compliant hands.

### Key Innovations:
- Synergistic optimization of finger geometry and control policies for functional grasping.
- Emphasis on underactuated systems (~6 DoF) instead of costly fully actuated hands (~16 DoF), reducing weight, size, and cost.
- AI algorithms to jointly optimize hardware and software for diverse industrial tasks.

### Outcome

Open-source methods enabling cost-effective, task-aware robotic grasping in manufacturing.

## Core-dev team

The currently active core developers are:

-   [Yefim Osipov-Sigachev](https://github.com/Huowl) (ITMO University) works on [Isaac Grasp Env](https://github.com/BE2R-Lab-RND-AI-Grasping/IsaacGraspingEnv) a reinforcement learning environment for functional grasping
-   [Kirill Zharkov](https://github.com/ZharkovKirill) (ITMO University) works on [iCEM MPC Expert](https://github.com/BE2R-Lab-RND-AI-Grasping/cem_mpc_expert), a framework for robotic grasping using iterative Cross-Entropy Method (iCEM) with Model Predictive Control (MPC)
-   [Mikhail Chaikovskii](https://github.com/MikhailChaikovskii) (ITMO University) works on [AffordanceLabeling](https://github.com/BE2R-Lab-RND-AI-Grasping/Semantic_Object_Segmentation_for_Affordance_Labeling) needed to generate object datasets with affordances 
-   [Olga Borisova](https://github.com/BorisovaOlga) (ITMO University): responsible on grasps samples using [DexGraspNet](https://github.com/BE2R-Lab-RND-AI-Grasping/DexGraspNet)
-   [Egor Rakshin](https://github.com/RakshinEgor) (ITMO University): responsible on hands design and its models in [models_hub](https://github.com/BE2R-Lab-RND-AI-Grasping/hand_models_hub)
-   [Rahaf Alshaowa](https://github.com/RahafAlshaowa) (ITMO University) works of functional grasping in [Functional Classification of Point Clouds
](https://github.com/BE2R-Lab-RND-AI-Grasping/gt_functional_pc)
-   [Ivan Borisov](https://github.com/iiborisov) (ITMO University) is a scientific supervisor
<!--
[Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
