# 世界模型 (World Models)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-08-10

### [Beyond Myopic World Models: Long-Horizon End-to-End Training for Direct Future Prediction](https://arxiv.org/abs/2608.07420v1)

- **arXiv**: `2608.07420v1`  |  **提交日期**: 2026-08-07
- **作者**: Xinyi Li, Zaishuo Xia, Chenjie Hao, Yubei Chen

World models are expected to support imagination over extended temporal horizons, yet most are still trained through local few-step prediction objectives and deployed by recursively rolling out their own predictions. This creates a fundamental mismatch: few-step losses optimize local transition fidelity, while long-horizon prediction depends on how errors and gradients propagate through the entire trajectory. As a result, transitions with different downstream influence on the endpoint are treated uniformly during training, and small local errors are amplified through recursive inference. We…

---

### [UniJEPA: A Unified Joint-Embedding Predictive Architecture for Task-Agnostic Visual World Modeling](https://arxiv.org/abs/2608.07409v1)

- **arXiv**: `2608.07409v1`  |  **提交日期**: 2026-08-07
- **作者**: An Lanji, Dawei Liu, Jin Li, Haoran Xu, Mei Chen, Yu Tian

Joint-Embedding Predictive Architectures (JEPAs) have emerged as a principled framework for self-supervised learning of world models in compact latent spaces, yet existing methods are fragmented: some predict masked parts of a single image in latent space (I-JEPA), others learn to predict global photometric transformations (Image World Models), while video-scale JEPAs predict future temporal states and are post-trained for action-conditioned planning (V-JEPA~2, DINO-World, DINO-WM). These objectives are treated as distinct recipes with separate encoders, predictors, and anti-collapse…

---

### [Addressable Memory for Video World Models](https://arxiv.org/abs/2608.07408v1)

- **arXiv**: `2608.07408v1`  |  **提交日期**: 2026-08-07
- **作者**: Xindi Wu, Sven Elflein, James Lucas, Olga Russakovsky, Laura Leal-Taixé, Despoina Paschalidou et al.

We study visual persistence in interactive video world models. These models rely on a Key-Value (KV) cache as a growing visual memory to carry forward previously generated frames. However, we find that models can no longer reliably address stored content once rollouts extend beyond the training horizon, because temporal Rotary Positional Embeddings (RoPE) offsets then fall outside the range seen during training and the model struggles to retrieve the relevant visual information through attention. Moreover, naively compressing the cache in the RoPE-rotated space corrupts memory by averaging…

---

### [From Optimal Actions to World Models: Identifiability of Transition Kernels in Discounted MDPs](https://arxiv.org/abs/2608.07301v1)

- **arXiv**: `2608.07301v1`  |  **提交日期**: 2026-08-07
- **作者**: Neal Batra

We study what can be recovered about the transition probabilities of a Markov decision process from optimal actions alone. This is closely related to the inverse problem considered by Letcher et al., who ask when the dynamics can be recovered from numerical \(Q\)-values. Here the numerical values themselves are not observed; only the optimal actions are known, for every reward in a given class. For state-action rewards \(r(s,a)\), knowing the optimal actions for every reward also tells us how much better one action is than another when each is followed by the same fixed policy. This is still…

---

### [MemWM: Memory-Augmented Text-Based World Model](https://arxiv.org/abs/2608.07107v1)

- **arXiv**: `2608.07107v1`  |  **提交日期**: 2026-08-07
- **作者**: Yujun Wang, Tao Zhang, Jinhe Bi,  Aniri, Wenxuan Ye, Boliang Liu et al.

World models are increasingly used to support planning in agents by predicting how environment states evolve in response to agent actions. Yet fluent next-state predictions can still omit task-critical facts, corrupt product attributes, or apply incorrect transition rules. To address such systematic prediction errors, we introduce MemWM, a memory-augmented text-based world model. MemWM uses world memory, a curated memory bank of transition rules, state caches, and hard-to-predict facts, to condition next-state imagination. We evaluate factual state preservation with Structured State Fidelity…

---

### [Transformers Struggle to Use Their Emergent World Models: Revisiting the Tower of Hanoi, and the Illusion of Thinking](https://arxiv.org/abs/2608.07077v1)

- **arXiv**: `2608.07077v1`  |  **提交日期**: 2026-08-07
- **作者**: Devin Pereira, Willem Zuidema

The Tower of Hanoi is a simple planning puzzle that in prior work has proven challenging for large reasoning models (LRMs). Current models solve the standard formulation of the puzzle, but still struggle with the flat-to-flat variant (where initial and goal states are not restricted to have all rings on a single peg). This paper presents an in-depth study of how both small, in-house Transformers and large, third-party LRMs solve this task. To understand the failures mechanistically, we first train small Transformers from scratch on precomputed solution traces. Using a variety of…

---

### [Is Forward Prediction Enough? Physical State Grounding for JEPA World Models](https://arxiv.org/abs/2608.06799v1)

- **arXiv**: `2608.06799v1`  |  **提交日期**: 2026-08-07
- **作者**: Haodong Yan, Jiaguan Zhu, Mingyuan Jia, Ruiqing Yin, Junjie He, Zhide Zhong et al.

Learning structured and control-relevant latent representations remains a key challenge for world models. Recent JEPA-based world models learn action-conditioned predictive latent dynamics from observation sequences. However, their forward-prediction objectives do not explicitly enforce reliable identifiability of robot-centric physical state from individual latents or state changes from latent pairs, which can limit downstream planning and policy performance. We propose PSG-JEPA, a physically grounded JEPA world model that shapes its latent space with two complementary grounding objectives…

---

### [Surg-UniWorld: A Unified Surgical World Model with Multimodal Control Experts](https://arxiv.org/abs/2608.06770v1)

- **arXiv**: `2608.06770v1`  |  **提交日期**: 2026-08-07
- **作者**: Rulin Zhou, Wanhao Liu, Guoheng Ma, Liangjin Shao, Qiujie Song, Yidu Wang et al.

Controllable surgical world models can provide a generative foundation for surgical artificial intelligence and simulation by synthesizing realistic instrument--tissue interactions. However, existing methods lack a unified multimodal control paradigm, while direct fusion of heterogeneous visual conditions often causes anatomical distortion, instrument appearance drift, and temporally inconsistent interactions. In this work, we propose {Surg-UniWorld}, a unified surgical world model with multimodal control experts. Surg-UniWorld first constructs a {Hierarchical Surgical Anchor} from…

---

### [Dueling World Models: Advantage-Style Action Channels for Common-Mode Distractor Rejection](https://arxiv.org/abs/2608.06706v1)

- **arXiv**: `2608.06706v1`  |  **提交日期**: 2026-08-07
- **作者**: Jiazhuo Li, Yiming Fei, Zhiruo Zhou, Heikichi Hayashi

Latent world models plan by predicting future states from an action, but when a scene contains motion the agent does not control, they quietly go action-blind: predictions for different actions become indistinguishable even as the training loss keeps improving. Existing remedies suppress this distraction with reconstruction, task reward, or auxiliary objectives, each adding machinery or assumptions. We show that a minimal alternative suffices, borrowed from the dueling decomposition of value into a state baseline and an action advantage: in latent dynamics, subtracting a prediction's mean…

---

## 📅 2026-08-07

### [GeniWorld: A Generalizable Interactive World Model for Robotic Manipulation via Visual Actions](https://arxiv.org/abs/2608.06332v1)

- **arXiv**: `2608.06332v1`  |  **提交日期**: 2026-08-06
- **作者**: Chenghao Gu, Hanyang Yu, Jingbo Zhang, Haitao Lin, Wenyao Zhang, Jinghe Wang et al.

Generalist robot policies exhibit strong capabilities, but their robustness in complex and unseen environments remains limited. Scaling robot learning and evaluation in diverse real-world environments remains costly and challenging. Action-conditioned world models offer a promising alternative, but they often suffer from limited action controllability and poor generalization to out-of-distribution (OOD) scenarios. To this end, we present GeniWorld, an interactive world model for robots that generalizes robustly across unseen scenarios. Building on pretrained video generative models, we use…

---

### [MASS: Multiplayer World Models with Authoritative Shared State](https://arxiv.org/abs/2608.06257v1)

- **arXiv**: `2608.06257v1`  |  **提交日期**: 2026-08-06
- **作者**: Ziqi Cai, Siqi Yang, Yimu Wang, Zixian Gao, Yunheng Liu, Shuchen Weng et al.

Current video world models struggle in multiplayer environments because they entangle world state with view-dependent visual latents, leading to redundant compute, view inconsistencies, and poor scalability. We propose MAS (Multiplayer world models with Authoritative Shared State) to resolve this limitation. Inspired by multiplayer game architectures, MAS disentangles world dynamics and view rendering. A learned Logic Engine advances a global, authoritative typed state from joint actions without any hand-written transition function, acting as the sole recurrent memory and synchronization…

---

### [From Passive Mirrors to Active Agents: Holonic Digital Twins for Physical AI over Networks](https://arxiv.org/abs/2608.06227v1)

- **arXiv**: `2608.06227v1`  |  **提交日期**: 2026-08-06
- **作者**: Christo Kurisummoottil Thomas, Omar Hashash, Walid Saad

Despite advances in artificial intelligence (AI) across multiple sectors, today's AI tools, including deep learning and generative AI, still fail when embedded into physical systems, such as robots and vehicles operating under real-world physical laws. This stems from their inability to maintain reliable world models for long-horizon planning under uncertainty and generalize to unseen scenarios. In this context, wireless networks, through pervasive sensing and communication, can orchestrate physical intelligence. However, current architectures optimize throughput, latency, and reliability and…

---

### [EnvACE: Internalizing Environment Dynamics via World Rehearsal for Agentic Reinforcement Learning](https://arxiv.org/abs/2608.06197v1)

- **arXiv**: `2608.06197v1`  |  **提交日期**: 2026-08-06
- **作者**: Zishan Xu, Zhiyuan Yao, Yuxin Chen, Yifu Guo, Zhengxi Lu, Yuquan Lu et al.

Training large language model agents for long-horizon tool use typically relies on interactions with real or synthesized executable environments, whose construction and verification are costly, or on external simulators that are difficult to ground. We introduce EnvACE, an agentic reinforcement learning method that replaces external environment interaction during training with world rehearsal. The policy alternates between acting and rehearsal: it first generates a tool call, then plays the role of the environment to produce the response induced by that action, and conditions subsequent…

---

### [Adaptive-WAM: Quality-Guided Early-Exit Planning from Intermediate Video-Diffusion Features](https://arxiv.org/abs/2608.06008v1)

- **arXiv**: `2608.06008v1`  |  **提交日期**: 2026-08-06
- **作者**: Sining Ang, Yuguang Yang, Yan Wang

Large video diffusion models provide rich spatiotemporal priors for autonomous driving, but existing world-action models often inherit the cost of iterative future-video generation even though deployment only requires an ego trajectory. We ask a more basic question: how much of a video diffusion model must be executed to make a reliable driving decision? Through a controlled study of video denoising timesteps and Diffusion Transformer (DiT) depth, we find that planning performance is largely insensitive to the tested video-noise levels, whereas strong trajectories can already be decoded from…

---

### [GAUGE: A Measurement-Grounded Benchmark for Physical Fidelity in Simulation Engines and Video World Models](https://arxiv.org/abs/2608.05948v1)

- **arXiv**: `2608.05948v1`  |  **提交日期**: 2026-08-06
- **作者**: Shuai Wang, Yaxin Feng, Xuekun Jiang, Shihan Tian, Ningyu Yan, Xing Shen et al.

Physics engines facilitate large-scale training and evaluation for embodied intelligence, while generative video world models are emerging as implicit simulators of future states and interactions. However, existing evaluations of physical fidelity are often conducted in isolation and rely heavily on perceptual similarity or human judgments, providing limited insight into which physical principles or parameters are violated. We introduce GAUGE, a real-world-grounded diagnostic benchmark for jointly evaluating how numerical simulators and generative video world models reproduce or deviate from…

---

### [AppDeltaWorld: Transition-Grounded Delta Code World Model for Mobile GUI Agents](https://arxiv.org/abs/2608.05891v1)

- **arXiv**: `2608.05891v1`  |  **提交日期**: 2026-08-06
- **作者**: Weikai Xu, Yunren Feng, Haoxiang Lei, Kun Huang, Yuxuan Liu, Kang Zhao et al.

Mobile GUI agents can operate apps through pixel perception and touch actions, making them a promising interface for collecting and improving long-horizon mobile interaction policies. However, real trajectories are difficult to obtain for sensitive apps and privacy-critical operations. At the same time, existing simulated environments are costly to scale up, and GUI world models still suffer from unstable generation, limited modality coverage, and inconsistent action-transition logic. To address these limitations, we propose AppDeltaWorld, a transition-grounded delta code world model that…

---

### [XEWorld: Can Action-Conditioned World Models Generalize to Unseen Robot Embodiments?](https://arxiv.org/abs/2608.05799v1)

- **arXiv**: `2608.05799v1`  |  **提交日期**: 2026-08-06
- **作者**: Yixiang Chen, Jiabing Yang, Yuan Xu, Qisen Ma, Keji He, Peiyan Li et al.

Action-conditioned world models are promising learned simulators for robotic manipulation, yet evaluating them exclusively on training robots fails to reveal whether they capture physical dynamics or merely memorize visual patterns. To answer whether a model can faithfully render a robot it has never seen, we introduce XEWorld, a controlled cross-embodiment testbed for world models that isolates embodiments by evaluating held-out robots within physically identical scenes. Our systematic analysis uncovers a shared architectural bottleneck: current models act primarily as 2D visual pattern…

---

### [When Agentic AI Meets Integrated Sensing and Communication](https://arxiv.org/abs/2608.05792v1)

- **arXiv**: `2608.05792v1`  |  **提交日期**: 2026-08-06
- **作者**: Kai Li, Conggai Li, Sarah Ali Siddiqui, Syed Sohail Ahmed, Xin Yuan, Shenghong Li et al.

Agentic artificial intelligence (AI) is transforming Integrated Sensing and Communication (ISAC) from a function-oriented physical-layer technology into a goal-driven, closed-loop intelligent system, a paradigm we term AISAC. Existing work on learning-based sensing, resource allocation, reconfigurable intelligent surfaces (RIS), edge intelligence, multi-agent coordination, and resilient networking has developed largely in isolation. This survey unifies the literature within a six-stage closed-loop framework comprising observation, contextualization, reasoning and prediction, planning and…

---

### [PhyLatent: Learning Dynamics-Relevant Representations for JEPA World Models](https://arxiv.org/abs/2608.05720v1)

- **arXiv**: `2608.05720v1`  |  **提交日期**: 2026-08-06
- **作者**: Xi Zeng, Haojie Ren, Ziying Song

We propose PhyLatent, a dynamics-relevant training objective for JointEmbedding Predictive Architecture (JEPA) world models. Our key observation is that preventing global latent collapse does not ensure that a representation preserves physical states and action consequences. We identify three failure modes in JEPA world models: physical invariance collapse, physical identifiability collapse, and counterfactual dynamics collapse. PhyLatent addresses them through three training pathways: physical invariance, physical identifiability, and counterfactual dynamics, implemented with physical state…

---

### [LAWM-3D: Learning 3D-Aware Latent Actions from Human Videos for Generalizable Robot World Models](https://arxiv.org/abs/2608.05706v1)

- **arXiv**: `2608.05706v1`  |  **提交日期**: 2026-08-06
- **作者**: Jiarui Yang, Jiale Zhange, Jiawei Li, Hang Guo, Wen Huang, Jinpeng Wang et al.

World models enable agents to perform forward rollout and planning without real-world interaction. However, their application in open-world embodied intelligence remains limited by the high cost of action annotations and the heterogeneity of action spaces across platforms. Recently, latent action models (LAMs) have alleviated this bottleneck by learning action representations directly from unlabeled human videos in a self-supervised manner. Nevertheless, most existing LAMs rely on single-view inputs and operate primarily in 2D pixel space, raising a fundamental question: can simply…

---

### [DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695v1)

- **arXiv**: `2608.05695v1`  |  **提交日期**: 2026-08-06
- **作者**: Wenhao Lin, Chenyu Yu, Xingwei Lin, Sicong Cao, Xiang Chen, Lei Xue et al.

As large language model (LLM) agents increasingly invoke external tools and interact with real-world systems, unsafe actions may cause irreversible consequences on external states, user data, and downstream services. Recent runtime guardrails mitigate such risks by checking proposed actions before execution, but many remain reactive: they primarily assess the apparent safety of the current action, lacking an explicit model of how risk evolves across the trajectory. This limitation creates a critical blind spot for long-horizon risks, where individually benign-looking actions can gradually…

---

### [JoyAI-RA 0.5: Scaling Robot Manipulation Learning via Dual Action Alignment](https://arxiv.org/abs/2608.05674v1)

- **arXiv**: `2608.05674v1`  |  **提交日期**: 2026-08-06
- **作者**: JoyAI-RA Team

Robot data is scarce, so generalist policies need to learn from heterogeneous sources, including human egocentric video, simulation, and real robots, which differ in supervision and embodiment, with action labels missing or mutually incompatible. Human egocentric data scale best but sit farthest from robot data, and naive pooling causes negative transfer rather than knowledge sharing. We propose JoyAI-RA 0.5, a generalist Vision-Language-World-Action (VLWA) framework that couples physical world-dynamics priors with visual semantics and scales manipulation learning across such data via dual…

---

### [Uncertainty-Aware World Model for Aerial Image-Goal Navigation](https://arxiv.org/abs/2608.05597v1)

- **arXiv**: `2608.05597v1`  |  **提交日期**: 2026-08-06
- **作者**: Deyi Zhu, Haoyu Fan, Yinan Zhu, Weichen Zhang, Shilin Ma, Xinlei Chen et al.

Aerial image-goal navigation requires an unmanned aerial vehicle (UAV) to reach a target location specified by a goal image. Existing world-model-based methods rank candidate trajectories using predicted futures, but typically rely on only one or a few point predictions, which is inadequate for large-scale outdoor environments with substantial future-state uncertainty. To address this limitation, we propose the Uncertainty-Aware Navigation World Model (UA-NWM), an efficient latent world model for aerial image-goal navigation, which formulates trajectory scoring as conditional…

---

### [HERA: Historical Evidence Routing Adapter for Physical Prediction in Latent World Models](https://arxiv.org/abs/2608.05523v1)

- **arXiv**: `2608.05523v1`  |  **提交日期**: 2026-08-06
- **作者**:  Yuanruyi, Yue Cao, Haojia Gao, Guanqiu Guo,  Ziyuezhang,  Shangqin et al.

Predictive video models have emerged as promising world models by learning latent visual dynamics from large-scale video. Yet these models remain challenged by physical events under occlusion, where later predictions may depend on object evidence that is no longer available in the current view. Addressing this challenge requires historical evidence not only to be preserved but also to remain accessible when it becomes relevant to a subsequent prediction. Existing approaches mainly enlarge the temporal context, cache generic video features, or impose explicit object-centric states, thereby…

---

### [Quantum-Structured World Models (QSWMs) for Predictive Latent Dynamics](https://arxiv.org/abs/2608.05371v1)

- **arXiv**: `2608.05371v1`  |  **提交日期**: 2026-08-05
- **作者**: Hailong Jiang, Emran Hossain, Feng Yu, Jianfeng Zhu, Guilin Zhang, Wulan Guo

World models learn latent states that summarize interaction histories, evolve over time, and support prediction, simulation, or planning. Most existing world models represent these states using classical vectors, probability distributions, recurrent hidden states, or transformer activations. In this paper, we introduce Quantum-Structured World Models (QSWMs), a quantum-inspired framework for predictive world modeling with structured latent states, latent transition operators, and measurement-inspired decoding maps. We study whether mathematical structures inspired by quantum theory, such as…

---

## 📅 2026-08-06

### [HelloWorld: Enabling Socially Interactive Characters in Video World Models](https://arxiv.org/abs/2608.05070v1)

- **arXiv**: `2608.05070v1`  |  **提交日期**: 2026-08-05
- **作者**: Liangyang Ouyang, Ruicong Liu, Xuangeng Chu, Kaipeng Zhang, Yoichi Sato

Despite the remarkable recent progress of video world models, social interaction between users and the characters within these worlds remains unsupported. To fill this gap, we present HelloWorld, a video world model that enables social interaction with in-world characters. With a single button press, users can prompt the on-screen character to respond toward the camera, e.g., turning to the viewer, waving, nodding, or speaking a short greeting. To make these interactions natural, we propose a self-distillation pipeline that finetunes the video generation model on data synthesized by itself.…

---

### [DreamWAM: Beyond RGB Future Prediction for World Action Models](https://arxiv.org/abs/2608.04996v1)

- **arXiv**: `2608.04996v1`  |  **提交日期**: 2026-08-05
- **作者**: Shanglin Yuan, Weiheng Zhao, Xin Shi, Haoyi Jiang, Xianda Guo, Liu Liu et al.

World Action Models (WAMs) learn action-relevant representations by predicting how the observed world will evolve. Most existing WAMs define this future in RGB space, where task-relevant state transitions are entangled with nuisance variations in texture, illumination, background, and viewpoint. We argue that WAMs should explicitly predict action-relevant future state rather than relying on RGB prediction alone. We introduce DreamWAM, which reformulates future prediction as structured world modeling beyond RGB, representing future states through complementary views of appearance, motion,…

---

### [WorldCycle: Self-Verifiable Reinforcement Learning for Long-Horizon Video World Models](https://arxiv.org/abs/2608.04964v1)

- **arXiv**: `2608.04964v1`  |  **提交日期**: 2026-08-05
- **作者**: Bohai Gu, Yueyang Yuan, Taiyi Wu, Dazhao Du, Jian Liu, Xiaoyi Pang et al.

Interactive video world models are essential for long-horizon planning and exploration, yet they suffer from compounding errors. Post-training methods such as reinforcement learning (RL) can improve these models, but they hit a verification bottleneck: for arbitrary action sequences, no ground-truth future state exists to measure long-term drift. Our key insight is that reversible action cycles make this verification possible: a sequence composed with its inverse must analytically return to the initial state, yielding annotation-free supervision on long-horizon correctness. Building on this,…

---

### [Overcoming Statistical Bias in Action-Controllable World Models](https://arxiv.org/abs/2608.04653v1)

- **arXiv**: `2608.04653v1`  |  **提交日期**: 2026-08-05
- **作者**: Yuhong Shi, Zhenhao Chu, Jie Wei, Jun Hao, Jianyi Liu, Jingwen Fu

Action-conditioned world models aim to predict how visual environments evolve under an agent's actions. Yet future frames are often highly predictable from visual inertia and recurring motion patterns alone. This creates a shortcut: models can fit the data by exploiting statistical biases without making their visible dynamics meaningfully depend on the action. As a result, different actions may produce similar futures, while motion may persist even under zero action. The key question is how to reduce reliance on statistical shortcuts from dominating action-conditioned prediction. We argue…

---

### [muSync-GS: Physics-Synchronized Driving Video Synthesis for Weather and Geometric Road Hazards](https://arxiv.org/abs/2608.04412v1)

- **arXiv**: `2608.04412v1`  |  **提交日期**: 2026-08-05
- **作者**: Yang Chen, Yicheng Zhu, Tao Li, Zilin Bian

High-quality driving data are essential for autonomous-driving systems and generative world models. However, rare and safety-critical scenarios involving adverse weather, braking under low tire--road friction, and uneven road geometry are costly and risky to collect at scale. Existing video-generation and 3D Gaussian editing methods can modify weather appearance or road geometry, but typically do not couple these edits with tire--road interaction and vehicle dynamics. As a result, an edited video may retain its original trajectory even when the modified road condition should alter braking,…

---

### [Helping Music Co-Creation Agents 'Listen' Well: Hierarchical Self-Supervised World Models for Understanding and Generation](https://arxiv.org/abs/2608.04378v1)

- **arXiv**: `2608.04378v1`  |  **提交日期**: 2026-08-05
- **作者**: Scott H. Hawley

Collaborative music agents need internal representations rich enough to support both understanding and generation, yet flexible enough for a workflow where the human retains agency. We present a hierarchical self-supervised ``world model'' for symbolic music: a 2.55M-parameter Swin V2 encoder trained on MIDI piano-roll images with JEPA-style objectives (pitch- and time-shift equivariance, masked embedding prediction, and a distributional regularizer), using no labels and no music-theory vocabulary. Probing the frozen embeddings shows that the level at which a musical property becomes…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v3)

- **arXiv**: `2608.02150v3`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

## 📅 2026-08-05

### [Stochastic Multiple Shooting Trajectory Optimization via Sequential Local Policy Evaluation](https://arxiv.org/abs/2608.03978v1)

- **arXiv**: `2608.03978v1`  |  **提交日期**: 2026-08-04
- **作者**: Ashwin Gupta, Joseph Moore

Stochastic single shooting trajectory optimization methods such as Model Predictive Path Integral control (MPPI) have been widely adopted in robotics due to their ability to reason about probabilistic dynamics and provide solutions where model gradients are noisy, costly to evaluate, or unavailable. However, satisfaction of terminal constraints when shooting over long action sequences is often sample inefficient, requiring a large number of iterations for convergence. In this paper, we present a stochastic multiple shooting method that optimizes short control action sequences connected via…

---

### [Enactive Artificial Intelligence: A Decision-Centric Architecture for Complex Systems](https://arxiv.org/abs/2608.03413v1)

- **arXiv**: `2608.03413v1`  |  **提交日期**: 2026-08-04
- **作者**: Zuojun Max Shen, Yuan Qu, Pujun Zhang, Anbang Liu, Yunhao Liang

As artificial intelligence (AI) continues to evolve and mature, recent AI practices have moved beyond large language models (LLMs) and text or image generation tasks, increasingly integrating tools, agents, and harnesses to solve real business and industrial problems. However, the power of AI is not verified under these real-world complex systems for various reasons, considering reliability, feasibility, resilience, and responsibility requirements in real commercial and industrial operations. This study synthesizes adjacent research and introduces Enactive AI as a conceptual framework for…

---

### [UniNav: A Unified World-Action Diffusion Model for Visual Navigation](https://arxiv.org/abs/2608.03244v1)

- **arXiv**: `2608.03244v1`  |  **提交日期**: 2026-08-04
- **作者**: Changqing Zhou, Yueru Luo, Zeyu Jiang, Changhao Chen

Image-goal visual navigation is a fundamental capability for embodied agents. Existing navigation policies efficiently predict waypoint trajectories but lack visual foresight, while navigation world models can anticipate future observations but often require costly planning rollouts. We present UniNav, a unified world-action model that generates future visual observations and continuous waypoint trajectories through a single diffusion process. Given history frames and a goal image, UniNav jointly denoises visual and waypoint tokens within a single transformer, unifying future prediction and…

---

### [CrossScope: A Role-Asymmetric World Model for Joint Dual-Scope Surgical Video Prediction](https://arxiv.org/abs/2608.03211v1)

- **arXiv**: `2608.03211v1`  |  **提交日期**: 2026-08-04
- **作者**: Wanhao Liu, Jinsong Lin, Rulin Zhou, Chi Kit Ng, Wenbin Pan, Zhiqing Tang et al.

Visual world models typically learn future dynamics from a single observation stream, limiting their ability to model cooperative systems with multiple independently moving observers. We investigate this challenge in Mother--Child endoscopic retrograde cholangiopancreatography (ERCP), where two flexible scopes provide complementary yet role-dependent views without a calibrated stereo relationship. Unlike conventional multi-view fusion that assumes symmetric information exchange, we formulate \textbf{role-asymmetric dual-scope future prediction}, where cross-view evidence is selectively…

---

### [EmbodiedVAE: Disentangled Video VAE for Efficient and Controllable Embodied Manipulation](https://arxiv.org/abs/2608.02990v1)

- **arXiv**: `2608.02990v1`  |  **提交日期**: 2026-08-04
- **作者**: Jiayi Luo, Hanxin Zhu, Chen Gao, Jiankun Wang, Cong Wang, Tianyu He et al.

Latent diffusion models (LDMs) have recently significantly advanced embodied learning in constructing powerful embodied manipulation world models. However, despite the remarkable performance, existing LDMs predominantly rely on Variational Autoencoders (VAEs) optimized for natural scenes while failing to account for the unique characteristics of embodied manipulation scenarios, yielding latent representations that are neither compact nor controllable, thereby hindering efficient training of LDMs and precise robotic control. To solve this problem, we present EmbodiedVAE, a novel video VAE that…

---

### [RealWeather: Realistic and Scene-Faithful Weather Translation with Driving World Models](https://arxiv.org/abs/2608.02953v1)

- **arXiv**: `2608.02953v1`  |  **提交日期**: 2026-08-03
- **作者**: Yuwei Ning, Liangzhi Wang, Yi Xiao, Zhenhua Wu, Yun Pang, Mingkun Chan et al.

Realistic weather translation is valuable for developing and evaluating autonomous driving systems, yet collecting paired videos of the same scenes under different weather conditions at scale is impractical. Existing methods therefore rely on synthetic data, 3D weather editing, or geometry-conditioned generation, often compromising weather realism or scene fidelity. We propose RealWeather, a driving world model for both realistic and scene-faithful weather translation. Our key idea is to learn authentic weather dynamics directly from real-world videos. Specifically, RealWeather employs…

---

### [Quo Vadis, World Modeling?](https://arxiv.org/abs/2608.02713v1)

- **arXiv**: `2608.02713v1`  |  **提交日期**: 2026-08-03
- **作者**: Yu Yang, Xuemeng Yang, Licheng Wen, Lingdong Kong, Xiaobin Hu, Dongyue Lu et al.

Continually improving agents require dynamic interaction feedback beyond static supervision, yet direct real-environment interaction is costly, slow, unsafe, and hard to parallelize. World modeling offers a natural intermediate proxy that allows agents to query lower-cost, more controllable feedback before committing to real actions. Classical world models instantiate this proxy primarily through future physical-state prediction, a formulation useful yet narrow for agents that require actionable feedback beyond raw state transitions. In this work, we conceptualize Agent-Centric Interactive…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v2)

- **arXiv**: `2608.02150v2`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

### [MiniWorld: Democratizing the Training of Video World Models from Scratch](https://arxiv.org/abs/2608.01127v2)

- **arXiv**: `2608.01127v2`  |  **提交日期**: 2026-08-02
- **作者**: Yian Zhao, Ruochong Zheng, Hongcan Guo, Yu Yan, Jian Zhang, Jie Chen

Video world models predict future observations conditioned on historical observations and control signals, enabling long-horizon generation through autoregressive state transitions. Unlike conventional video generation models that primarily capture visual appearance and motion, video world models learn the underlying dynamics governing environment evolution under agent actions, providing a foundation for embodied AI and interactive simulation. Recent progress has largely relied on adapting pretrained video generation models through post-training or distillation. Although effective, these…

---

## 📅 2026-08-04

### [WorldExam: Benchmarking World Models from Apparent Appearance to Inherent Reactivity](https://arxiv.org/abs/2608.02603v1)

- **arXiv**: `2608.02603v1`  |  **提交日期**: 2026-08-03
- **作者**: Yuxue Yang, Shuyao Shang, Jiahe Wang, Zitong Zhou, Liang Tan, Junhan Zeng et al.

Controllable video generation models are increasingly being developed as world models. Accordingly, evaluating them in this role extends beyond the apparent appearance of generated videos to the inherent reactivity of the worlds they depict: the ability to infer from the scene state how the world should react and to generate plausible consequences not explicitly described in the input. Yet existing benchmarks mainly assess visual quality or explicit instruction fulfillment by checking whether requested actions and interaction outcomes are realized, leaving inherent reactivity underexamined.…

---

### [Analytic Planning under Uncertainty with Moment Closure](https://arxiv.org/abs/2608.02519v1)

- **arXiv**: `2608.02519v1`  |  **提交日期**: 2026-08-03
- **作者**: Shishir Sharma, Doina Precup

Effective model-based reinforcement learning in stochastic environments requires planning that accounts for predictive uncertainty. Propagating full state distributions analytically offers a principled way to do this, but has traditionally required restrictive policy or reward structures to remain tractable. Consequently, modern deep reinforcement learning has largely retreated to either stochastic sampling, which introduces significant target variance, or deterministic point estimates that ignore predictive covariance entirely. We investigate whether distribution-aware planning is possible…

---

### [DF$^3$: World Modeling via Decoder-Free Feature Forecasting in Autonomous Navigation](https://arxiv.org/abs/2608.02428v1)

- **arXiv**: `2608.02428v1`  |  **提交日期**: 2026-08-03
- **作者**: Jiaming Chen, Guoan Xu, Aoshen Huang, Haozhuo Zhang, Yang Li, Wei Pan

Forecasting future states from video sequences is a critical challenge for autonomous robotic systems and a fundamental objective of world modeling. Prior generative methods operating at the pixel level inevitably overemphasize task-irrelevant details, leading to prohibitive computational overhead. While latent-based approaches attempt to mitigate this by predicting features directly, the persistent reliance on heavy decoders for state-to-task mapping remains a computational bottleneck. In this work, we propose Decoder-Free Feature Forecasting (DF$^3$), a novel framework that models world…

---

### [Faster-WAM: Do World Action Models Need Deep Action Modules?](https://arxiv.org/abs/2608.02365v1)

- **arXiv**: `2608.02365v1`  |  **提交日期**: 2026-08-03
- **作者**: Liheng Ma, Rui Heng Yang, Zhanguang Zhang, Mateo Clemente, Ziwen Hu, Tongtong Cao et al.

World Action Models (WAMs) couple robot action prediction with video world models. Existing WAMs with shared-backbone and Mixture-of-Transformers designs generally tie the depth of the action module to that of the video backbone, resulting in substantial computational overhead and high inference latency. To address this limitation, we introduce Dock of Transformer (DoT), a video-centric design principle that treats a pretrained video Transformer as a representation hub and connects lightweight output-heads through docking interfaces. This enables flexible output-head design while providing…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v1)

- **arXiv**: `2608.02150v1`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

### [ProWorld: Progress-Aware Hyperbolic World Models for Long-Horizon Visual Goal Reaching](https://arxiv.org/abs/2608.01926v1)

- **arXiv**: `2608.01926v1`  |  **提交日期**: 2026-08-03
- **作者**: Zihan Liu, Yuzhe Zhuang, Yuanzu Li, Wanshuang Gou, Jiahong Liu, Min Zhou et al.

JEPA-style visual world models offer an effective paradigm for visual goal planning by predicting future latent representations. Existing methods typically learn local transition consistency through next-step representation prediction. However, in long-horizon tasks, accurate local prediction alone need not ensure sustained progress toward the goal. First, multi-step rollouts can remain locally plausible while drifting away from goal-relevant trajectories. Second, locally similar future states can correspond to substantially different long-term progress, making them difficult to distinguish…

---

### [WorldDynCache: Risk-Controlled Latent Dynamics Approximation for Diffusion World Model](https://arxiv.org/abs/2608.01845v1)

- **arXiv**: `2608.01845v1`  |  **提交日期**: 2026-08-03
- **作者**: Leyang Chen, Junyi Wu, Shaoqiu Zhang, Yulun Zhang

Diffusion world models generate high-quality futures, but re- peated transformer evaluations make inference prohibitively slow. Existing caches reuse intermediate features, selectively update tokens, or reuse and extrapolate denoising outputs ac- cording to local drift or short native-space histories. These criteria can miss both approximation-induced latent transition defects that accumulate across skipped steps and phase- or condition-dependent changes in the direction of latent evo- lution. We propose WorldDynCache, a risk-controlled latent dynamics approximation framework with two core…

---

### [SG-WAM: Self-Guided World Modeling in Geometry-Aware Policy Space](https://arxiv.org/abs/2608.01397v1)

- **arXiv**: `2608.01397v1`  |  **提交日期**: 2026-08-02
- **作者**: Ruiteng Zhao, Zhengshen Zhang, Yue Su, Wenshuo Wang, Jiahui Li, Zhiyuan Yang et al.

World Action Models (WAMs) couple action generation with prediction of future states. Their effectiveness depends on whether future dynamics are modeled in a space that is both aligned with action generation and sufficiently geometry-aware to capture where and how actions change the scene. Existing WAMs typically satisfy only part of this requirement, relying on either perceptually heavy observation-space targets or auxiliary latent spaces that are not jointly structured for action relevance and geometry. We propose SG-WAM, a self-guided framework that learns geometry-aware action-conditioned…

---

### [EndoWAM: A Grounded World-Action Model for Generalizable Endoscopic Navigation](https://arxiv.org/abs/2608.01221v1)

- **arXiv**: `2608.01221v1`  |  **提交日期**: 2026-08-02
- **作者**: Jinsong Lin, Zikang Pan, Wanhao Liu, Chi Kit Ng, Liangjing Shao, Zihang Yu et al.

Autonomous endoscopic navigation can reduce clinicians' operational burden, yet robust control remains challenging due to tissue deformation, transient occlusions, and rapidly changing viewpoints. Existing learning-based policies typically predict actions from current observations without explicitly modeling future dynamics, limiting their robustness and reliability in safety-critical settings. World Action Models (WAMs) offer a promising alternative by coupling predictive visual dynamics with action generation, but extending them to robotic endoscopy remains challenging due to limited…

---

### [Climate-Dyna Deep Hedging for XVAs: Model-Based Reinforcement Learning, Residual Climate HVA, and Hedge-Instrument Discovery](https://arxiv.org/abs/2608.01208v1)

- **arXiv**: `2608.01208v1`  |  **提交日期**: 2026-08-02
- **作者**: Xiaozhen Wang, Francois Buet-Golfouse

For a trading desk, residual climate hedging valuation adjustment (HVA) is the climate cost left after its inherited hedge and any admissible overlay have been taken into account; it therefore cannot be inferred from a stand-alone stress loss. We obtain this residual by comparing paired climate-on and baseline worlds and reoptimizing the overlay for each hedge universe, which also turns hedge-instrument discovery into a valuation problem: an instrument is useful to the extent that it lowers the optimized residual cost. The linear-Gaussian case has an exact finite-horizon Riccati solution;…

---

### [MiniWorld: Democratizing the Training of Video World Models from Scratch](https://arxiv.org/abs/2608.01127v1)

- **arXiv**: `2608.01127v1`  |  **提交日期**: 2026-08-02
- **作者**: Yian Zhao, Ruochong Zheng, Hongcan Guo, Yu Yan, Jian Zhang, Jie Chen

Video world models predict future observations conditioned on historical observations and control signals, enabling long-horizon generation through autoregressive state transitions. Unlike conventional video generation models that primarily capture visual appearance and motion, video world models learn the underlying dynamics governing environment evolution under agent actions, providing a foundation for embodied AI and interactive simulation. Recent progress has largely relied on adapting pretrained video generation models through post-training or distillation. Although effective, these…

---

### [FactorJEPA: Factorizing Monolithic Futures into Layout-Agent-Interaction Channels for Crowded and Chaotic Global South Urban Worlds](https://arxiv.org/abs/2608.01049v1)

- **arXiv**: `2608.01049v1`  |  **提交日期**: 2026-08-02
- **作者**: Kapil Wanaskar, Gaytri Jena, Aman Chadha, Vinija Jain, Vasu Sharma, Amitava Das

World models have attracted significant attention for their ability to capture and predict the structure and dynamics of the physical world. In this emerging landscape, Joint Embedding Predictive Architectures (JEPA) offer a particularly compelling direction. We study a largely unexplored regime: populous, crowded, and chaotic Global South urban environments, which we call DENSEWORLD. Unlike the lower-density, lane-structured settings that dominate existing evaluations, these scenes exhibit soft spatial boundaries, extreme agent heterogeneity, persistent occlusion, and rapid social…

---

### [Why Does the Future Branch? Identifiable Closure Tests for Stochastic Physical World Models](https://arxiv.org/abs/2608.00591v1)

- **arXiv**: `2608.00591v1`  |  **提交日期**: 2026-08-01
- **作者**: Yibin Dong

Stochastic world models are usually evaluated by the accuracy and calibration of their predicted futures. These criteria leave a decision-relevant ambiguity: the same conditional future distribution can arise because an observation aliases different physical states, or because the dynamics remain random after the declared full state is fixed. We prove that this attribution is not identifiable from ordinary transition data, even with an optimal probabilistic predictor. We introduce ClosurePairs, an interventional evaluation protocol that crosses compatible microstates with repeated exogenous…

---

## 📅 2026-07-14

### [Cycle-World: Mitigating Error Accumulation in Long-term Video World Models via Reverse-Prediction Cycle Consistency](https://arxiv.org/abs/2607.11836v1)

- **arXiv**: `2607.11836v1`  |  **提交日期**: 2026-07-13
- **作者**: Zihan Su, Teng Hu, Jiangning Zhang, Ruiyan Wang, Ran Yi, Lizhuang Ma et al.

Autoregressive diffusion models have enabled high-quality video generation, yet their sequential nature inherently suffers from error accumulation. In long-horizon video synthesis, minor prediction deviations compound over time, inevitably leading to unconstrained generative drift, structural collapse, and severe visual degradation. To address this, we propose Cycle-World, a novel framework designed for stable and temporally consistent long-video generation. Our approach tackles error drift by enforcing strict temporal reversibility across both the training and inference phases.…

---

### [ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v1)

- **arXiv**: `2607.11673v1`  |  **提交日期**: 2026-07-13
- **作者**: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang et al.

We present ABot-3DWorld 0, a universal multimodal 3D world model that turns text, image, and video inputs into high-fidelity, explorable 3D worlds. At the heart of our framework is a unified Spatial Generative Primitive (SGP), a compact tuple of a high-quality panorama and a spatial point cloud that delivers an efficient description of any 3D space. Multimodal inputs are first lifted into this primitive; a 3D-consistent panoramic video generator then explores the primitive along a planned trajectory; finally, our panoramic video reconstruction engine converts the generated video into a clean,…

---

### [Xiaomi-Robotics-U0: Unified Embodied Synthesis with World Foundation Model](https://arxiv.org/abs/2607.11643v1)

- **arXiv**: `2607.11643v1`  |  **提交日期**: 2026-07-13
- **作者**: Xinghang Li, Jun Guo, Qiwei Li, Long Qian, Hang Lai, Yueze Wang et al.

Recent foundation image and video generation models offer strong generalization and controllability, but their direct application to embodied scenarios is limited by requirements for multi-view consistency, geometric coherence, and robot embodiment constraints. Existing methods typically adapt foundation models with limited robot data, often sacrificing visual knowledge acquired during large-scale pre-training. We present Xiaomi-Robotics-U0, a 38-billion-parameter multimodal autoregressive model for unified embodied synthesis. It treats embodied generation as an extension of foundation image…

---

### [WALA Learning Executable Latent Actions from Action-Labeled Demonstrations and Action-Free Videos](https://arxiv.org/abs/2607.11397v1)

- **arXiv**: `2607.11397v1`  |  **提交日期**: 2026-07-13
- **作者**: Jiahao Liu, Zhongpu Xia, Shuai Tian, Huangrui Li, Yuhang Zheng, Ning Ma et al.

Generalizable robot policies typically rely on action-labeled robot demonstrations, which are expensive to collect and difficult to scale. In contrast, large-scale human and robot videos contain rich physical interactions but often lack executable robot action labels. We present WALA, a framework for learning executable latent actions from both action-labeled demonstrations and action-free videos. WALA first pretrains a semantic-geometric latent action model from videos by modeling the evolution between current observations and sparsely sampled future observations. Instead of reconstructing…

---

### [Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models](https://arxiv.org/abs/2607.10781v1)

- **arXiv**: `2607.10781v1`  |  **提交日期**: 2026-07-12
- **作者**: Xiyan Su, Frank Diermeyer, Markus Lienkamp

Driving world models built on large video-diffusion backbones generate realistic scenes but are hard to control: enforcing a traffic norm typically means retraining the backbone or conditioning it on hand-built layouts. We ask whether controllability requires training at all. Our experiment shows that a rectified-flow driving world model, which jointly generates future video and a planned ego trajectory, can have its planned trajectory steered entirely at sampling time by differentiable energy functions that encode driving norms, without knowledge-specific retraining of the diffusion…

---

### [World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning](https://arxiv.org/abs/2607.10630v1)

- **arXiv**: `2607.10630v1`  |  **提交日期**: 2026-07-12
- **作者**: Tong Nie, Yuewen Mei, Junlin He, Yihong Tang, Jian Sun, Wei Ma

Robust motion planning in dense traffic requires autonomous vehicles to interact in rare and safety-critical scenarios that are underrepresented in naturalistic driving data. Although adversarial training offers a feasible solution, existing methods often rely on external scenario generators, heuristic perturbations, or simulator-heavy rollouts, which makes them difficult to integrate with modern autoregressive planners. Here, we cast adversarially robust planner learning as a constrained min-max game and propose Adversarial World Modeling (AWM), a theoretically grounded multi-agent self-play…

---

### [Stateful Worlds, Stateless Elasticity: Exact-State Serving for Interactive World Models](https://arxiv.org/abs/2607.10389v1)

- **arXiv**: `2607.10389v1`  |  **提交日期**: 2026-07-11
- **作者**: Jin Li, Jiawei Chen

A persistent interactive world model keeps its running state resident on the GPU that serves it: a multi-gigabyte attention cache, almost all of it rewritten at every generation step. That state cannot be recomputed in interactive time or approximated without changing the world, so a live session pins its device. The pin is a scheduling problem. WorldMove moves a live session under one guarantee: the destination is bit-identical to the source, or nothing is installed. It relocates the cache in 18.8 ms same-node, 101x faster than save/load. It holds a checksum-verified 92.1-94.8 Gb/s on a 100…

---

### [A Control Theory of Predictability in Latent World Models](https://arxiv.org/abs/2607.10362v1)

- **arXiv**: `2607.10362v1`  |  **提交日期**: 2026-07-11
- **作者**: Hanzhe You, Yonggang Zhang, Maohao Ran, Zhiqin Yang, Zhenyuan Zhang, Wei Xue et al.

Latent world models are trained to predict future states in a learned representation and are then deployed inside a planner that selects actions by simulating them forward. Current practice adopts the prediction error, the single- or multi-step rollout loss on held-out data, as the training and model-selection objective, on the assumption that a lower prediction error yields better control. We show that this assumption is unreliable for a structural reason: a planner does not query the model on the training distribution but on the states that its candidate actions reach, which generally leave…

---

### [When Does Depth Survive Composition? Compute--Quality Regimes in Latent World Models](https://arxiv.org/abs/2607.10203v1)

- **arXiv**: `2607.10203v1`  |  **提交日期**: 2026-07-11
- **作者**: Achyuthan Sivasankar

Adaptive-compute world models -- early-exit or mixture-of-depths predictors that spend variable depth per step -- assume depth buys better predictions and can be routed adaptively. In autoregressive rollouts, the first assumption requires depth's per-step precision to survive composition. We test this with a pre-registered instrument, the shallow penalty $ρ=\mathrm{err}(\text{shallowest-exit rollout})/\mathrm{err}(\text{full-depth rollout})$, across nine DeepMind Control tasks under matched single-step ($K=1$) and multi-step ($K=4$) training, three seeds each. We find three regimes: on 6/9…

---

## 📅 2026-07-13

### [PanoWorld: Real-World Panoramic Generation](https://arxiv.org/abs/2607.09661v1)

- **arXiv**: `2607.09661v1`  |  **提交日期**: 2026-07-10
- **作者**: Haoyuan Li, Dizhe Zhang, Yuemei Zhou, Xiangkai Zhang, Haoran Feng, Xiaofan Lin et al.

In this work, we aim to address the challenge of long-range memory in panoramic world models by exploiting the rotation-equivariant property of omnidirectional representations, where rotation can be treated as an implicit geometric transformation.Building on this insight, we propose PanoWorld, which simplifies camera trajectories into translations via fixed headings for both current-action modeling and long-range memory through Dense Panoramic Ray-Conditioning (DPRC) and Geometry-aware Memory Augmentation (GMA).Then, a three-stage training pipeline is introduced to progressively optimize each…

---

### [Shortcut Trajectory Planning for Efficient Offline Reinforcement Learning](https://arxiv.org/abs/2607.09336v1)

- **arXiv**: `2607.09336v1`  |  **提交日期**: 2026-07-10
- **作者**: Guanquan Wang, Yoshimasa Tsuruoka

Diffusion-based trajectory planners have shown strong performance in offline reinforcement learning, but their iterative denoising process often incurs high inference cost. Consistency-based planners reduce the number of sampling steps, yet they typically rely on a two-stage teacher--student distillation pipeline that increases training cost and may introduce instability. We propose Shortcut Trajectory Planning (STP), an offline model-based reinforcement learning framework that incorporates shortcut models as efficient trajectory generators. STP trains a conditional shortcut trajectory model…

---

### [Causally Debiased Latent Action Model for Embodied Action Conditioned World Models](https://arxiv.org/abs/2607.09185v1)

- **arXiv**: `2607.09185v1`  |  **提交日期**: 2026-07-10
- **作者**: Yufan Wei, Kun Zhou, Lingjun Mao, Zijun Zhang, Ziming Xu, Ziqiao Xi et al.

Action-conditioned world models (ACWMs) aim to simulate future observations conditioned on embodied actions, offering a promising foundation for robot planning, policy evaluation, and data augmentation. However, learning controllable ACWMs requires large-scale action-labeled data, which remains costly to collect in the real world. Latent action models (LAMs) mitigate this bottleneck by inferring latent actions from unlabeled videos, but existing LAMs are typically trained with reconstruction-only objectives and therefore entangle action-relevant dynamics with action-irrelevant visual factors…

---

### [Toward Active Object Detection for UAVs in the Wild: A Large-Scale Dataset, Benchmark and Method](https://arxiv.org/abs/2607.09078v1)

- **arXiv**: `2607.09078v1`  |  **提交日期**: 2026-07-10
- **作者**: Tianpeng Liu, Xinhua Jiang, Li Liu, Qinmu Shen, Siwei Tang, Zhen Liu et al.

Object detection is a fundamental component in numerous Unmanned Aerial Vehicle (UAV) applications, yet it has long been plagued by hindrances like occlusion or target pixel scarcity. Active Object Detection (AOD) provides a novel paradigm to address these challenges via active vision, while UAV-based AOD research remains scarce due to the lack of high-quality datasets and benchmarks for algorithm development and evaluation. To fill this gap, this paper presents ATRNet-LUDO, the first large-scale real-world dataset for UAV-Ground Active Object Detection (UGAOD). It contains 121,000 multi-view…

---

## 📅 2026-07-10

### [Write-Protected Discrete Bottlenecks for Language-Grounded World Models: A Structural Limitation and Sufficient Fix](https://arxiv.org/abs/2607.08312v1)

- **arXiv**: `2607.08312v1`  |  **提交日期**: 2026-07-09
- **作者**: Jiayi Fang

How should language interface with a world model's discrete symbol system? The dominant paradigm -- end-to-end injection of LLM/VLM features into robot world models (RT-2, Octo, PaLM-E) -- implicitly assumes that language gradients can directly shape physical symbol representations. We ask whether this assumption is safe, find that it is not, and characterize the minimal architectural constraint that prevents the failure. Any language gradient entering a Gumbel-softmax-based discrete symbol bottleneck forces a structural trade-off: the vanilla estimator collapses to 2.2/64 symbols (4/5…

---

## 📅 2026-07-09

### [Infinite Worlds with Versatile Interactions](https://arxiv.org/abs/2607.07534v1)

- **arXiv**: `2607.07534v1`  |  **提交日期**: 2026-07-08
- **作者**: Zelin Gao, Qiuyu Wang, Jiapeng Zhu, Jingye Chen, Zichen Liu, Qingyan Bai et al.

We present LingBot-World 2.0 (also known as LingBot-World-Infinity), an advanced iteration of LingBot-World featuring four distinct upgrades. (1) Our model achieves an unbounded interaction horizon while maintaining consistent output quality, benefiting from a carefully crafted causal pretraining paradigm. (2) Through distilling a real-time variant from the base model, our system guarantees rapid response time, sufficient to drive 720p video streams at 60 fps. (3) Compared to the previous version, this update introduces highly diverse interactive elements, comprising a broader spectrum of…

---

### [Validate the Dream Before You Trust Its Verdict: Admissibility for World-Model Simulators](https://arxiv.org/abs/2607.07196v1)

- **arXiv**: `2607.07196v1`  |  **提交日期**: 2026-07-08
- **作者**: Christian Oefinger, Finn Rasmus Schäfer, Korbinian Moller, Mattia Piccinini, Johannes Betz

Across robotics, World Models (WMs) are increasingly used to evaluate action policies by simulating the consequences of actions in an imagined world, and returning a success or safety verdict. Yet a verdict is only as trustworthy as the WM that produced it, and the WM itself needs to be certified. In video-generation WMs, fidelity metrics such as Fréchet Video Distance (FVD) reward visual realism, but ignore whether the world responds correctly to the policy's actions, including those unseen in training. Classical simulation-based validation assumes a trusted simulator evaluating an untrusted…

---

### [Grounding Spatial Relations in a Compact World Model: Instruction Leakage and a Goal-Free Dynamics Fix](https://arxiv.org/abs/2607.06925v1)

- **arXiv**: `2607.06925v1`  |  **提交日期**: 2026-07-08
- **作者**: Yufeng Wang, Lu Wei, Haibin Ling

Compact world models that condition on a language goal promise to ground relations such as ``put the red block left of the blue block'' using a sparse set of explicit \emph{reference anchors}. We ask when such references actually ground a relation, and identify a trap: a goal-conditioned predictor reaches a striking $0.90$ relation-readout accuracy, yet this is \emph{instruction transcription}, not perception. Withholding the goal collapses it to chance ($0.90\!\to\!0.27$, three seeds) and a counterfactual instruction makes the predicted anchors follow the \emph{false} instruction $94.5\%$ of…

---

### [The Rank-One Corner: How Much Value Equivalence Does a Task Need from a World Model?](https://arxiv.org/abs/2607.06640v1)

- **arXiv**: `2607.06640v1`  |  **提交日期**: 2026-07-07
- **作者**: Donna Vakalis

A learned world model is usually judged by how faithfully it reconstructs its observations or predicts reward, as though quality were something the model simply has or lacks. But what a task actually needs from a model is narrower: the few predictive coordinates its queries depend on, which we call the closure. We show that how much of that closure a latent comes to represent is set not by the model's capacity or its observations but by the dimensionality of the objective it is trained against, and we measure this directly on a DreamerV3 stack in a controlled environment with known…

---

## 📅 2026-07-08

### [RynnWorld-4D: 4D Embodied World Models for Robotic Manipulation](https://arxiv.org/abs/2607.06559v1)

- **arXiv**: `2607.06559v1`  |  **提交日期**: 2026-07-07
- **作者**: Haoyu Zhao, Xingyue Zhao, Siteng Huang, Xin Li, Deli Zhao, Zhongyu Li

Robotic manipulation in the open world requires not only recognizing what a scene looks like, but also anticipating how its 3D structure moves under interaction. We argue that synchronized RGB, depth, and optical flow, namely RGB-DF, provide a physically grounded representation that captures the underlying 4D dynamics of a scene. Compared to 2D pixel videos, this multi-modal synergy aligns visual appearance with geometric structure and temporal motion, creating a representation space significantly closer to the low-level end-effector actions demanded by robotic systems, thereby narrowing the…

---

### [RynnWorld-Teleop: An Action-Conditioned World Model for Digital Teleoperation](https://arxiv.org/abs/2607.06558v1)

- **arXiv**: `2607.06558v1`  |  **提交日期**: 2026-07-07
- **作者**: Haoyu Zhao, Xingyue Zhao, Hangyu Li, Biao Gong, Kehan Li, Siteng Huang et al.

Scaling robot learning requires massive, diverse trajectory data, yet collection is currently bottlenecked by physical teleoperation, where every demonstration binds operator time to specific hardware and workspaces. We introduce digital teleoperation, a paradigm that decouples data collection from physical constraints by replacing the real robot with a generative world model. In this framework, an operator's hand-pose stream drives a robot-centric generative world model to synthesize high-fidelity egocentric videos from a single reference image. The recorded pose stream serves as an…

---

### [Hypothesis-driven Model Expansion under Uncertainty for Open-World Robot Planning](https://arxiv.org/abs/2607.06501v1)

- **arXiv**: `2607.06501v1`  |  **提交日期**: 2026-07-07
- **作者**: Anxing Xiao, Hanbo Zhang, Tianrun Hu, David Hsu

We consider an open-world planning setting in which service robots must operate in unknown environments with incomplete knowledge of objects and actions. Traditional closed-world approaches with pre-programmed knowledge bases fail when robots encounter unexpected situations and tasks, posing a fundamental challenge for autonomous knowledge expansion in human environments. In this work, we propose an open-world planning framework that enables robots to automatically generate, verify, and update hypotheses about their abstract world models. Our key insight is to explicitly maintain…

---

### [A Definition and Roadmap for World Models](https://arxiv.org/abs/2607.06401v1)

- **arXiv**: `2607.06401v1`  |  **提交日期**: 2026-07-07
- **作者**: Xinyuan Chen, Haoyu Guo, Shi Guo, Bingqi Jiang, Chunhua Shen, Xing Shen et al.

World models -- internal simulators that learn the structure and dynamics of an environment -- have become one of the most actively debated concepts in AI. From model-based reinforcement learning and video generation to embodied robotics and ultimately, physical AI, researchers across AI subfields are building systems that they call "world models", yet there is no consensus on what a world model fundamentally is, what it should predict, or how it should be built. This perspective article provides a scientific definition of world models, discussions of their key technical aspects, and a staged…

---

### [AlayaWorld: Long-Horizon and Playable Video World Generation](https://arxiv.org/abs/2607.06291v1)

- **arXiv**: `2607.06291v1`  |  **提交日期**: 2026-07-07
- **作者**:  AlayaWorld Team, Kaipeng Zhang, Chuanhao Li, Yifan Zhan, Yongtao Ge, Yuanyang Yin et al.

Game worlds have traditionally been built through labor-intensive production pipelines, making them costly to develop, difficult to customization, and expensive to modify after deployment. Recent advances in video world models offer a fundamentally different paradigm. Rather than explicitly authoring every component of a virtual environment, these models autoregressively synthesize future observations conditioned on the current world state and user interactions, enabling playable worlds to be generated online. Trained on both gameplay recordings and real-world videos, they can capture diverse…

---

### [MoWorld: A Flash World Model](https://arxiv.org/abs/2607.06216v1)

- **arXiv**: `2607.06216v1`  |  **提交日期**: 2026-07-07
- **作者**: Team Moxin, Deyi Ji, Tianrun Chen, Xin Zhang, Jiale Yang, Qi Zhu et al.

The future of World Models depends not only on scaling model capability, but also on scaling practicality and inference efficiency. High-frame-rate inference enables responsive perception, planning, and control in real-world autonomous systems. To this end, we present MoWorld, a cost-effective yet high-performance Flash World Model with an end-to-end framework spanning data generation, pre-training, distillation, and efficient inference, enabling up to 50 FPS real-time interaction with cinematic visual quality without the need of high-end GPUs. To enable large-scale real-world deployment,…

---

### [Imagined Rollouts are Kinematic, Not Dynamic: A Diagnosis of Long-Horizon World-Model Failure](https://arxiv.org/abs/2607.05966v1)

- **arXiv**: `2607.05966v1`  |  **提交日期**: 2026-07-07
- **作者**: Finn Rasmus Schäfer, Korbinian Moller, Yuan Gao, Christian Oefinger, Sebastian Schmidt, Johannes Betz

Long-horizon failure in world models is conventionally attributed to compounding error, a generic framing that does not distinguish what kind of error compounds. We propose a kinematic-vs-dynamic reframing: world models tend to imagine kinematically rather than dynamically. We operationalize this as the imagined Kinematic-Consistency Error, a per-step diagnostic that measures how far a rollout departs from a closed-form kinematic null, paired with a perturbation protocol that tests whether iKCE responds when physical conditions cross a regime boundary. We instantiate the diagnostic on a…

---

### [Narrative World Model: Narratology-Grounded Writer Memory for Long-Form Fiction](https://arxiv.org/abs/2607.05577v1)

- **arXiv**: `2607.05577v1`  |  **提交日期**: 2026-07-06
- **作者**: Mohammad Saifullah, Thomas Kornmaier, Taaha Kazi, Vasu Sharma, Aditya Sanjiv Kanade, Aanand Kumar Yadav

Long-form fiction writers need memory that answers multi-hop questions about evolving story state: who knows a secret and when they learned it, whether an event preceded the narration that revealed it, whether a setup paid off, and how a relationship shifted. General-purpose retrieval and agent-memory systems represent entities and facts but not the narratological structure these questions turn on, so they surface the wrong evidence or none at all. We introduce the Narrative World Model (NWM), a writer-memory system that pairs a narratology-grounded typed temporal-state graph with…

---

### [Multiplayer Interactive World Models with Representation Autoencoders](https://arxiv.org/abs/2607.05352v2)

- **arXiv**: `2607.05352v2`  |  **提交日期**: 2026-07-06
- **作者**: Anthony Hu, Václav Volhejn, Adrien Ramanana Rahary, Chris Mulder, Aditya Makkar, Alyx Liao et al.

We introduce the first multiplayer world model for highly dynamic environments governed by complex physical interactions. Whereas single-player world models treat the other agents as part of the environment, ours conditions on the action streams of multiple agents, learning to attribute changes in the scene to the correct player and to stay coherent under arbitrary combinations of their actions. We study this problem in the game of Rocket League, where players compete and cooperate under fast, tightly coupled dynamics. Trained on 10,000 hours of gameplay collected with publicly available…

---

## 📅 2026-07-07

### [Deform360: A Massive Multi-view Visuotactile Dataset for Deformable World Models](https://arxiv.org/abs/2607.05390v1)

- **arXiv**: `2607.05390v1`  |  **提交日期**: 2026-07-06
- **作者**: Hongyu Li, Wanjia Fu, Xiaoyan Cong, Zekun Li, Binghao Huang, Hanxiao Jiang et al.

Predicting object dynamics (i.e., world modeling) is a fundamental challenge for robotic manipulation, and modeling deformable objects presents a particularly difficult case due to their high-dimensional state spaces and complex material properties. While current world models approach this through two distinct paradigms: learning the dynamics over the 2D pixel space or more explicit 3D geometric space. A systematic understanding of their relative strengths and limitations remains elusive due to the lack of diverse, large-scale real-world data. To address this, we present Deform360, a…

---

### [Multiplayer Interactive World Models with Representation Autoencoders](https://arxiv.org/abs/2607.05352v1)

- **arXiv**: `2607.05352v1`  |  **提交日期**: 2026-07-06
- **作者**: Anthony Hu, Václav Volhejn, Adrien Ramanana Rahary, Chris Mulder, Aditya Makkar, Amélie Royer et al.

We introduce the first multiplayer world model for highly dynamic environments governed by complex physical interactions. Whereas single-player world models treat the other agents as part of the environment, ours conditions on the action streams of multiple agents, learning to attribute changes in the scene to the correct player and to stay coherent under arbitrary combinations of their actions. We study this problem in the game of Rocket League, where players compete and cooperate under fast, tightly coupled dynamics. Trained on 10,000 hours of gameplay collected with publicly available…

---

### [MoP-JEPA: Hard-Assigned Predictor Mixtures for Stochastic JEPA World Models](https://arxiv.org/abs/2607.05238v1)

- **arXiv**: `2607.05238v1`  |  **提交日期**: 2026-07-06
- **作者**: Zhi Song, Ximing Xing, Zhenchao Tang, hanbo Huang, Tianxu Lv, minghao Yang et al.

JEPA world models predict the next latent state with a single deterministic predictor trained by latent regression. We show that this fails structurally when the environment is stochastic: at a branching transition, the regression-optimal predictor outputs the conditional mean of the successor embeddings, a point between the true next states that corresponds to no state at all. We prove this collapse for deterministic and gated mixture-of-experts predictors, and prove that MoP-JEPA's hard-assigned predictors converge instead to a quantizer of the transition distribution: one head per…

---

### [InternVLA-A1.5: Unifying Understanding, Latent Foresight, and Action for Compositional Generalization](https://arxiv.org/abs/2607.04988v1)

- **arXiv**: `2607.04988v1`  |  **提交日期**: 2026-07-06
- **作者**: Haoxiang Ma, Junhao Cai, Xiaoxu Xu, Hao Li, Yuyin Yang, Yang Tian et al.

Unified models for robot manipulation aim to equip one policy with both the semantic priors of pretrained VLMs and the physical dynamics learned through future prediction. In practice, existing designs tend to erode the semantics of the pretrained backbone, suffer interference among heterogeneous objectives, and learn future prediction from scratch in pixel space, leaving the dynamics priors of pretrained video generators unexploited. We present InternVLA-A1.5, which builds the policy on a native VLM backbone that keeps training on VQA and subtask prediction, and attaches a lightweight…

---

### [Qantara: Bridge-Flow Training for Multi-Paradigm JEPA Control](https://arxiv.org/abs/2607.04978v1)

- **arXiv**: `2607.04978v1`  |  **提交日期**: 2026-07-06
- **作者**: Ruslan Rakhimov, George Bredis, Yuriy Maksyuta, Daniil Gavrilov

Joint-Embedding Predictive Architectures (JEPAs) underpin a growing family of latent world models for control from raw pixels, but every existing JEPA world model commits at training time to a single inference paradigm: either trajectory optimisation in a learned dynamics model, or direct behaviour cloning. A single checkpoint that serves both would defer this choice to inference, when deployment constraints (rollout cost, observation accessibility) determine which path wins. We present Qantara, an end-to-end JEPA whose joint training objective pairs a Brownian-bridge interpolant between…

---

### [KAM-WM: Kinematic Affordance Maps from Latent World Models for Robot Manipulation](https://arxiv.org/abs/2607.04652v1)

- **arXiv**: `2607.04652v1`  |  **提交日期**: 2026-07-06
- **作者**: Xinyu Shao, Keru Zhou, Guowei Huang, Yajun Gao, Tongtong Cao, Xiu Li

Learning manipulation from few demonstrations requires visual priors that capture not only where to interact, but also how the interaction should begin; static priors such as segmentation masks encode only the former. We present KAM-WM, a framework that extracts a coarse directional interaction cue from a frozen latent video world model without rollout or world-model fine-tuning. KAM-WM queries a Flow Matching image-to-video backbone once and interprets its single-step latent velocity as a Kinematic Affordance Map (KAM), which provides task-conditioned interaction regions and coarse motion…

---

### [CRISP: A Spatiotemporal Camera-Radar Backbone for Driving via Forecasting-Based World-Model Pretraining](https://arxiv.org/abs/2607.04541v1)

- **arXiv**: `2607.04541v1`  |  **提交日期**: 2026-07-05
- **作者**: Jingyu Song, Yi Liu, Katherine A. Skinner

Camera-radar (CR) fusion is a practical sensing configuration for autonomous driving, but existing models are typically trained with task-specific supervision, limiting reusable representation learning. We present CRISP, a spatiotemporal CR backbone pretrained through forecasting-based representation learning. Given historical multi-view images and radar sweeps, CRISP learns a unified bird's-eye-view (BEV) representation by predicting future LiDAR point clouds. LiDAR is used only as privileged supervision during pretraining; the deployed model requires only camera and radar. To make…

---

### [Geographic Diversity Beats Data Volume for Cross-Domain Generalization in Zero-Label JEPA Driving World Models](https://arxiv.org/abs/2607.04500v1)

- **arXiv**: `2607.04500v1`  |  **提交日期**: 2026-07-05
- **作者**: Santosh Jaiswal

Self-supervised latent world models can assign a surprise score to driving scenarios without any human labels. A natural follow-up question is whether such a model, trained on driving data from one geographic region, can generalize its notion of complexity to unseen cities and sensor configurations. We study this question through a controlled transfer experiment: we train JEPA-based world models on nuPlan data (Pittsburgh, Boston, Singapore) and evaluate zero-shot on held-out Argoverse 2 validation scenarios from Miami and Austin. We find that models trained on geographically diverse data…

---

### [Operator-on-F complements value-equivalence: a planning-time diagnostic for latent world models](https://arxiv.org/abs/2607.04464v1)

- **arXiv**: `2607.04464v1`  |  **提交日期**: 2026-07-05
- **作者**: Donna Vakalis

World-model evaluation for model-based reinforcement learning typically asks whether the learned model predicts reward and value well, which can leave planning-relevant errors in the model's latent rollouts unmeasured. We introduce a complementary diagnostic, operator-on-F, that compares a model's k-step latent pushforward to the environment's on an observable subset F, using the model's own predictor. On a TD-MPC2 size sweep over cheetah-run, reward-prediction error stays within [0.028, 0.091] for every model size - only about 3x variation - so an unnormalized reward-fit check has narrow…

---

### [Learning Task-Sufficient World Models by Synergizing Agentic Exploration and Structured Modeling](https://arxiv.org/abs/2607.04409v1)

- **arXiv**: `2607.04409v1`  |  **提交日期**: 2026-07-05
- **作者**: Fan Feng, Yujia Zheng, Minghao Fu, Yongqiang Chen, Guangyi Chen, Kevin Murphy et al.

Learning and planning in imagination using world models provides an effective paradigm for training agents for decision-making. However, existing approaches often rely on high-dimensional latent spaces or generic visual embeddings that retain many factors irrelevant to control, limiting efficiency and generalization across tasks. To this end, we study how agents can learn world models with representations that are task-specific, minimal, and sufficient for decision-making. We achieve this via a closed-loop synergy between the agent and the world model, in which structured world-model learning…

---

### [Last-Meter Precision Navigation for UAVs: A Diffusion-Refined Aerial Visual Servoing Approach](https://arxiv.org/abs/2607.04352v1)

- **arXiv**: `2607.04352v1`  |  **提交日期**: 2026-07-05
- **作者**: Yaxuan Li, Jiarui Zeng, Shaofei Huang, Zhedong Zheng

In this work, we study the last-meter precision navigation for UAVs, e.g., autonomously reaching a target within the final 10 meters using monocular vision. This task is challenging due to scale ambiguity, rotation discontinuities, and the need for fine-grained spatial reasoning. Existing methods often fail under large viewpoint changes or lack generalization to unseen environments. To this end, we propose DreamNav, a coarse-to-fine diffusion-refined aerial visual servoing framework. In the first coarse-estimation stage, a robust regression policy employs a trigonometric parameterization to…

---

### [DynaVieW: Schema-Guided World Modeling for Understanding Hierarchical Visual Dynamics](https://arxiv.org/abs/2607.04112v1)

- **arXiv**: `2607.04112v1`  |  **提交日期**: 2026-07-05
- **作者**: Silin Gao, Hao Zhao, Zeming Chen, Sepideh Mamooler, Antara Raaghavi Bhattacharya, Qiyu Wu et al.

Multimodal LLMs struggle to systematically model the temporal evolution of visual scenes in videos or multi-image sequences. Such inputs require models to predict or simulate multiple levels of dynamic constituents, such as actions taken in the visual sequence, and the associated changes to the visual environment that result. To address this challenge, we propose a dynamic schema-guided world model, DynaVieW, optimized for visual dynamic prediction and simulation. DynaVieW achieves an in-depth understanding of visual dynamics by learning interleaved state-transition sequences, where states…

---

### [Worldscape-MoE: A Unified Mixture-of-Experts World Model for Scalable Heterogeneous Action Control](https://arxiv.org/abs/2607.03964v1)

- **arXiv**: `2607.03964v1`  |  **提交日期**: 2026-07-04
- **作者**: Jianjie Fang, Yongyan Xu, Ziyou Wang, Chen Gao, Yuchao Huang, Zhaolu Wang et al.

World models are rapidly becoming a core infrastructure for embodied intelligence and interactive agents: they provide controllable simulators in which agents can perceive, act, forecast, and acquire scalable experience. Yet current video generation world models are still organized around isolated control interfaces, such as camera trajectories, robot actions, or hand-joint signals. This fragmentation is increasingly a scaling bottleneck. The central challenge is not the absence of controllable generators, but the lack of a unified and extensible learning framework that can absorb…

---

### [ThermoForce: A Physics-Structured Interventional World Model for Building HVAC Control](https://arxiv.org/abs/2607.03942v1)

- **arXiv**: `2607.03942v1`  |  **提交日期**: 2026-07-04
- **作者**: Yifan Wang

Model predictive control (MPC) of building HVAC systems needs thermal models that answer a causal question: what indoor temperature, energy use, and comfort will result if a control action is applied? Time-series foundation models (TSFMs) can forecast passive building trajectories with strong zero-shot skill, but high factual accuracy does not imply valid response to control interventions. We show that an observational grey-box model with the best passive accuracy predicts cooling effects with the wrong sign, and that adding control and weather covariates to a TSFM does not fix intervention…

---

## 📅 2026-07-03

### [WorldDirector: Building Controllable World Simulators with Persistent Dynamic Memory](https://arxiv.org/abs/2607.02517v1)

- **arXiv**: `2607.02517v1`  |  **提交日期**: 2026-07-02
- **作者**: Hanlin Wang, Hao Ouyang, Qiuyu Wang, Wen Wang, Qingyan Bai, Ka Leong Cheng et al.

We present WorldDirector, a highly controllable video world model framework designed for persistent dynamic object memory and unrestricted viewpoint exploration. Unlike existing world models that entangle physical dynamics with pixel rendering and rely on continuous visual observation to sustain motion, our framework explicitly decouples semantic motion orchestration from visual generation. By leveraging an LLM to coordinate 3D trajectories with camera movements and subsequently employing these orchestrated trajectories as control signals for video generation, our approach ensures strict…

---

### [WorldSample: Closed-loop Real-robot RL with World Modelling](https://arxiv.org/abs/2607.02431v1)

- **arXiv**: `2607.02431v1`  |  **提交日期**: 2026-07-02
- **作者**: Yuquan Xue, Le Xu, Zeyi Liu, Zhenyu Wu, Zhengyi Gu, Xinyang Song et al.

Reinforcement learning (RL) can overcome the demonstration-coverage limitation of imitation learning (IL) by allowing robots to improve through trial-and-error interaction beyond the states observed in demonstrations. However, deploying RL on real robots remains constrained by high interaction costs, since each physical rollout is costly and reflects only one realized action-outcome path. To address this challenge, we propose WorldSample, a physically grounded data augmentation framework for real-robot RL that closes a real-synthetic loop between physical rollouts, world-model generation, and…

---

### [ACID: Action Consistency via Inverse Dynamics for Planning with World Models](https://arxiv.org/abs/2607.02403v1)

- **arXiv**: `2607.02403v1`  |  **提交日期**: 2026-07-02
- **作者**: Gawon Seo, Dongwon Kim, Suha Kwak

Decision-time planning with action-conditioned world models has become a popular paradigm for embodied control. However, the standard planning cost judges a candidate solely by how close its predicted terminal state lies to the goal, leaving the realizability of the intermediate transitions unchecked -- a predicted trajectory can look convincing while the environment rollout drifts away from it. In this paper, we propose ACID, a decision-time planning framework that introduces cycle action consistency: the action inferred backward from a predicted transition by an inverse dynamics model…

---

### [DecompRL: Solving Harder Problems by Learning Modular Code Generation](https://arxiv.org/abs/2607.02390v1)

- **arXiv**: `2607.02390v1`  |  **提交日期**: 2026-07-02
- **作者**: Juliette Decugis, Fabian Gloeckle, Francis Bach, Taco Cohen, Gabriel Synnaeve

How can Large Language Models (LLMs) solve problems they currently cannot? Repeated sampling scales test-time compute but GPU cost grows linearly with attempts, while reinforcement learning (RL) with verifiable rewards improves single-attempt accuracy at the expense of sample diversity. Both strategies ultimately fail when the base policy has near-zero probability of producing a correct solution: no amount of sampling or gradient signal can overcome a search space that is simply too large. We take a different approach: rather than sampling harder, we make the task easier by decomposing…

---

### [Hardware-Enforced Semantic Coordination for Safety-Critical Real-Time Autonomous Systems](https://arxiv.org/abs/2607.02376v1)

- **arXiv**: `2607.02376v1`  |  **提交日期**: 2026-07-02
- **作者**: Uwe M. Borghoff, Paolo Bottoni, Remo Pareschi

Recent advances in agentic AI are producing increasingly complex autonomous systems that integrate large language models, world models, optimization engines, specialized neural architectures, autonomous platforms, and human operators. While much current research focuses on improving reasoning capabilities, safety-critical real-time deployment also requires bounded and verifiable coordination among heterogeneous components operating concurrently under uncertainty. Software-mediated coordination presents fundamental limitations in domains where bounded latency, deterministic coordination, and…

---

### [PWM-ArtGen: Part World Model for Articulated Object Generation](https://arxiv.org/abs/2607.02045v1)

- **arXiv**: `2607.02045v1`  |  **提交日期**: 2026-07-02
- **作者**: Wentao Zheng, Ancong Wu

The key challenge in articulated 3D object generation from a single image is accurately predicting the underlying kinematic structure. Existing methods either infer kinematic parameters directly from a static image that lacks dynamic part-level kinematic relationships, or estimate parameters from visual dynamics generated from a single image, which is prone to accumulated errors of two steps. Moreover, the limited scale and diversity of existing annotated datasets further hinder generalization to complex, real-world objects. To overcome these limitations, we propose to learn the joint…

---

### [Liquid Latent State Dynamics for Interpretable Turbofan Degradation Modeling](https://arxiv.org/abs/2607.01986v1)

- **arXiv**: `2607.01986v1`  |  **提交日期**: 2026-07-02
- **作者**: Weizhi Nie, Weijie Wang, Yuting Su

Multivariate time-series models for prognostics are often evaluated by point prediction accuracy, yet their internal states rarely expose a coherent degradation process. We study liquid neural networks as latent dynamics models for aircraft engine health monitoring on the C-MAPSS benchmark. The proposed model encodes a history window into a latent state, evolves that state with a liquid transition model, and decodes future sensor observations. To separate health evolution from operating-condition variation, the latent state is factorized into degradation and condition components. Remaining…

---

### [PhysMani: Physics-principled 3D World Model for Dynamic Object Manipulation](https://arxiv.org/abs/2607.01938v1)

- **arXiv**: `2607.01938v1`  |  **提交日期**: 2026-07-02
- **作者**: Peng Yun, Shouwang Huang, Hao Li, Jinxi Li, Jianan Wang, Bo Yang

Manipulating fast and dynamically moving targets in unstructured 3D environments remains challenging for embodied AI. Existing visual-language-action models and world models struggle with accurate 3D geometry and physically meaningful forecasting. We propose PhysMani, a framework that couples a physics-principled 3D Gaussian world model with a future-aware action policy model. The world model learns a divergence-free Gaussian velocity field via online optimization for fast and physically grounded future dynamics prediction. The policy model integrates the predicted 3D scene future dynamics…

---

### [Repair the Amplifier, Not the Symptom: Stable World-Model Correction for Agent Rollouts](https://arxiv.org/abs/2607.01767v1)

- **arXiv**: `2607.01767v1`  |  **提交日期**: 2026-07-02
- **作者**: Xinyuan Song, Zekun Cai

As agent planning moves from short tool chains toward persistent workflows with thousands or tens of thousands of steps, failures will occur inside large planning graphs rather than in isolated predictions. Replanning the entire graph after every mistake is neither computationally realistic nor desirable: full-graph replay consumes large context budgets, exposes the LLM to many irrelevant symptoms, and can degrade long-context retrieval. This paper studies the missing component in such systems: a world-model corrector that repairs the failed planning graph in place. We compare two families of…

---

### [Predicting Closed-Loop Performance of Latent World Models: Offline Checkpoint Selection for MPC and Model-Based RL Under Non-Markovian Rewards in LunarLander](https://arxiv.org/abs/2607.01736v1)

- **arXiv**: `2607.01736v1`  |  **提交日期**: 2026-07-02
- **作者**: Nikolai Smolyanskiy

We study how to predict the downstream closed-loop performance of a learned latent world model from validation-time diagnostics alone. Choosing the right checkpoint from a world-model training run is difficult: validation loss and multi-step prediction RMSE keep improving long after closed-loop performance has collapsed. We present a suite of structural validation-time diagnostics drawn from optimal-control theory and apply them to Gymnasium's LunarLander v3, which features shaped rewards. We train an RSSM [5, 4] world model on it and treat per checkpoint CEM-MPC return as the oracle for…

---

### [Safe and Adaptive Cloud Healing: Verifying LLM-Generated Recovery Plans with a Neural-Symbolic World Model](https://arxiv.org/abs/2607.01595v1)

- **arXiv**: `2607.01595v1`  |  **提交日期**: 2026-07-02
- **作者**: Junyan Tan, Haoran Lin, Siyuan Guo, Yichen Fang, Xinyue Luo, Tianyu Shen et al.

As the scale and complexity of cloud-based AI systems continue to escalate, ensuring service reliability through rapid fault detection and adaptive recovery has become a critical challenge. While existing approaches integrate Large Language Models (LLMs) for semantic understanding and Deep Reinforcement Learning (DRL) for policy optimization, they often rely on sequential, loosely coupled architectures that underutilize the generative and reasoning capabilities of LLMs. In this paper, we propose a paradigm shift with PASE, a Planning-Aware Semantic self-healing engine, a novel fault…

---

### [Certified World Models as Sensing Clocks: Drift-Aware Deadlines for Active Perception](https://arxiv.org/abs/2607.01537v1)

- **arXiv**: `2607.01537v1`  |  **提交日期**: 2026-07-01
- **作者**: Hongbo Wang

Certified world models estimate how long their predictions remain valid. We turn this validity horizon into an operational sensing clock: a rule for when an agent should stop coasting and re-sense. Starting from an audited equivariant world model, we derive a deadline for no-sensing intervals and show that deployable deadlines in learned world models must be drift-aware: on-manifold Lyapunov rates alone overestimate coasting validity, while calibrated native rollout-drift envelopes carry the deployed guarantee. On a frozen 3D VN-JEPA model, the resulting clock controls held-out…

---

### [OPINE-World: Programmatic World Modeling with Ontology-error-Prioritized Interactive Exploration](https://arxiv.org/abs/2607.01531v1)

- **arXiv**: `2607.01531v1`  |  **提交日期**: 2026-07-01
- **作者**: David Courtis, Wenhao Li, Scott Sanner

Learning how an environment behaves from interaction is central to building agents that adapt to unfamiliar tasks. World models learned with deep networks are flexible but data-hungry and transfer poorly beyond their training distribution. Program-synthesized world models, written as source code by LLMs and refined through counterexample-guided inductive synthesis (CEGIS), are instead data-efficient and reusable, yet they have been demonstrated mainly on structured-state worlds with a given object vocabulary, and a single program search does not scale to pixel-rendered environments whose…

---

### [From World Models to World Action Models: A Concise Tutorial for Robotics](https://arxiv.org/abs/2607.00836v2)

- **arXiv**: `2607.00836v2`  |  **提交日期**: 2026-07-01
- **作者**: Xiaoxiong Zhang, Xiong Zeng, Wei Zhang

World models are increasingly used in embodied intelligence and generative simulation, yet their scope remains ambiguous across communities. This tutorial presents a design-space view of world models as action-conditioned predictive models that estimate the future evolution of task-relevant observations or states. We categorize existing methods into observation-space and state-space world models, comparing their trade-offs in visual fidelity, spatial structure, physical interpretability, and control usability. We further introduce world action models, which connect predicted futures with…

---

### [DVG-WM: Disentangled Video Generation Enables Efficient Embodied World Model for Robotic Manipulation](https://arxiv.org/abs/2606.32028v2)

- **arXiv**: `2606.32028v2`  |  **提交日期**: 2026-06-30
- **作者**: Ziyu Shan, Zhenyu Wu, Xiaofeng Wang, Zheng Zhu, Ziwei Wang

Video-based embodied world models provide an appealing substrate for robotic manipulation by predicting future states, yet current approaches remain limited by a fundamental entanglement: accurately modeling dynamics typically requires low-level temporal reasoning, while producing high-resolution frames demands expansive visual synthesis according to high-level semantics. This entanglement results in slow inference speed for iterative planning or too coarse predictions to retain contact-rich details. To solve this dilemma, we present Disentangled Video Generation World Model (DVG-WM), an…

---

### [WorldOdysseyBench: An Open-World Benchmark for Long-Horizon Stability of Interactive World Models](https://arxiv.org/abs/2606.31672v2)

- **arXiv**: `2606.31672v2`  |  **提交日期**: 2026-06-30
- **作者**: Ting-Bing Xu, Jiacheng Sui, Zhe Gao, Kewei Shi, Wenjin Yang, Zhicheng Liu et al.

Despite rapid progress in interactive world models (IWMs), existing benchmarks evaluate action following only at trajectory level and ignore memory and interaction physics. We introduce WorldOdysseyBench, an open-world benchmark for long-horizon stability across four dimensions, each with tailored innovations: (i) Action: per-frame action metric bypassing cross-model semantic scale disparity and exposing failures hidden by trajectory; (ii) Vision: segment-based drift metric capturing non-monotonic mid-sequence collapse missed by start-vs-end comparisons; (iii) Physics: controllability-gated…

---

## 📅 2026-07-02

### [Structured 4D Latent Predictive Model for Robot Planning](https://arxiv.org/abs/2607.01166v1)

- **arXiv**: `2607.01166v1`  |  **提交日期**: 2026-07-01
- **作者**: Zhiyi Li, Peilin Wu, Xiaoshen Han, Ruojin Cai, Yilun Du

Video predictive models are emerging as a powerful paradigm in robotics, offering a promising path toward task generalization, long-horizon planning, and flexible decision-making. However, prevailing approaches often operate on 2D video sequences, inherently lacking the 3D geometric understanding necessary for precise spatial reasoning and physical consistency. We introduce a Structured 4D Latent Predictive Model, which predicts the evolution of a scene's 3D structure in a structured latent space conditioned on observations and textual instructions. Our representation encodes the scene…

---

### [RoboWorld: Fast and Reliable Neural Simulators for Generalist Robot Policy Evaluation](https://arxiv.org/abs/2607.01060v1)

- **arXiv**: `2607.01060v1`  |  **提交日期**: 2026-07-01
- **作者**: Byeongguk Jeon, Seonghyeon Ye, JaeHyeok Doo, Sungdong Kim, Minjoon Seo, Hyungmok Son et al.

Video world models are emerging as a scalable alternative for evaluating generalist robot policies, bypassing the physical constraints and engineering burdens of real-world deployment. However, evaluating policies with video world models remains challenging, as world-model errors can make generated rollouts unreliable and slow inference limits large-scale throughput. We introduce RoboWorld, an automated evaluation pipeline that pairs a fast autoregressive video world model with a task-progress-aware vision-language model scoring. To enable reliable long-horizon autoregressive world-model…

---

### [Valdi: Value Diffusion World Models](https://arxiv.org/abs/2607.00917v1)

- **arXiv**: `2607.00917v1`  |  **提交日期**: 2026-07-01
- **作者**: Christopher Lindenberg, Kashyap Chitta

World models can enable Model Predictive Control (MPC), but this requires dynamics prediction that is both fast enough for online use and expressive enough to represent uncertain futures. Diffusion models offer a natural mechanism for modeling uncertain dynamics, yet their iterative inference procedure makes them difficult to use for low-latency latent planning. We bridge this gap with Value Diffusion World Models (Valdi), combining end-to-end online training for MPC with a latent diffusion dynamics model. In preliminary experiments on the CarRacing environment, we show that Valdi, using a…

---

### [DeWorldSG: Depth-Aware 3D Semantic Scene Graph Generation via World-Model Priors](https://arxiv.org/abs/2607.00889v1)

- **arXiv**: `2607.00889v1`  |  **提交日期**: 2026-07-01
- **作者**: Seok-Young Kim, Abdelrahman Elskhawy, Taewook Ha, Dooyoung Kim, Eunjae Shin, Benjamin Busam et al.

We present DeWorldSG, a novel framework that generates spatio-temporally robust 3D Semantic Scene Graphs from RGB-D sequences. Existing methods often struggle to construct reliable 3D scene graphs due to unstable 3D object representations and missing relations caused by frame-wise inference. DeWorldSG addresses these issues by estimating instance-level geometric 3D Gaussian distributions through depth-guided filtering and representing each object as a probabilistic 3D node rather than a single projected point. To mitigate relational sparsity from frame-wise inference, our framework further…

---

### [From World Models to World Action Models: A Concise Tutorial for Robotics](https://arxiv.org/abs/2607.00836v1)

- **arXiv**: `2607.00836v1`  |  **提交日期**: 2026-07-01
- **作者**: Xiaoxiong Zhang, Xiong Zeng, Wei Zhang

World models are increasingly used in embodied intelligence and generative simulation, yet their scope remains ambiguous across communities. This tutorial presents a design-space view of world models as action-conditioned predictive models that estimate the future evolution of task-relevant observations or states. We categorize existing methods into observation-space and state-space world models, comparing their trade-offs in visual fidelity, spatial structure, physical interpretability, and control usability. We further introduce world action models, which connect predicted futures with…

---

### [ABot-M0.5: Unified Mobility-and-Manipulation World Action Model](https://arxiv.org/abs/2607.00678v1)

- **arXiv**: `2607.00678v1`  |  **提交日期**: 2026-07-01
- **作者**: Ronghan Chen, Yandan Yang, Zuojin Tang, Dongjie Huo, Tong Lin, Haoning Wu et al.

Mobile manipulation is a key capability for general-purpose robots, yet remains challenging for current embodied learning methods. VLA policies are typically reactive and lack explicit world modeling, while existing World Action Models (WAMs) are still poorly aligned with the structure of mobile manipulation: they operate on coarse video chunks, model entangled navigation-manipulation actions, and train inverse dynamics under supervision that does not match autoregressive inference. As a result, they often miss fine-grained contact dynamics, suffer from action-distribution conflicts, and…

---

### [Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)

- **arXiv**: `2607.00673v1`  |  **提交日期**: 2026-07-01
- **作者**: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar

Robots deployed in unstructured outdoor environments often plan from scene reconstructions collected before deployment because operators cannot remap large or remote sites before every mission. As a result, robots must make long-horizon planning decisions using stale maps that assume the terrain remains unchanged, even though physical changes to the environment may render previously feasible routes unsafe or unreachable at execution time. We present a physically viable world model for evaluating what-if queries for robot navigation under future terrain change. The system augments…

---

### [AGI Maze as a Benchmark Framework for World-Modeling Agents](https://arxiv.org/abs/2607.00627v1)

- **arXiv**: `2607.00627v1`  |  **提交日期**: 2026-07-01
- **作者**: Alexey Potapov

Large language models (LLMs) are powerful pattern-completion systems, but their default operating mode - predicting the next token from a static context - does not reliably produce persistent, manipulable representations of an external world. Many tasks that look like "reasoning" in text become substantially harder once the environment is partially observable, stateful, and requires memory and structured hypotheses about hidden state. AGI Maze is a lightweight framework for building such environments without requiring high-dimensional sensory inputs. It provides a family of grid-based maze…

---

### [Multi-scale Mixture of World Models for Embodied Agents in Evolving Environments](https://arxiv.org/abs/2607.00457v1)

- **arXiv**: `2607.00457v1`  |  **提交日期**: 2026-07-01
- **作者**: Jinwoo Jang, Daniel J. Rho, Sihyung Yoon, Hyunsuk Cho, Honguk Woo

Embodied agents operating in the real world require multi-scale reasoning and knowledge adaptation as conditions change. We identify two challenges in applying Mixture of Experts (MoE) to this setting: routing lacks an explicit notion of scale, preventing targeted updates at specific scales, and a uniform update policy cannot accommodate the different rates at which knowledge at each scale becomes outdated. We present MuSix, a framework that addresses both challenges through scale-aware world model mixture and evolution. A two-stage routing mechanism grounds scale selection in experiential…

---

### [RetailSMV: Exocentric vs. Egocentric Adaptation of Foundation Video World Models in Retail](https://arxiv.org/abs/2607.00310v1)

- **arXiv**: `2607.00310v1`  |  **提交日期**: 2026-07-01
- **作者**: Amirreza Rouhi, Rajat Aggarwal, Parikshit Sakurikar, Anoop M. Namboodiri, Sashi P. Reddi

Foundation video diffusion models are increasingly viewed as world simulators for embodied agents, yet their pretraining on internet-scale generic video leaves them poorly aligned with real-world deployment domains. We study parameter-efficient adaptation of a pretrained foundation video world model to retail scenes: when synchronized egocentric and exocentric video of the same activity are available, which viewpoint of training data produces the strongest adapted model? We introduce RetailSMV (Retail Synchronized Multi-View), a corpus of 32,105 captioned retail clips from five supermarkets…

---

### [Testing Frontier Large Language Models' Physics Literacy in Parallel Physical Worlds](https://arxiv.org/abs/2607.00276v1)

- **arXiv**: `2607.00276v1`  |  **提交日期**: 2026-06-30
- **作者**: Dong Zhang

Current large-language-model (LLM) physics benchmarks are usually scored by answer accuracy, which cannot distinguish genuine reasoning from recall of familiar problem patterns and reveals little about where a model's reasoning breaks down. We introduce an auditable four-stage diagnostic that evaluates whether an LLM can reason inside an unfamiliar physics framework through induction, formulation, prediction, and review. The diagnostic combines locked pre-registrations, fresh sessions between stages, dual-LLM judging, and a human-audit pathway, and we apply it to three parallel physics…

---

### [VOCA: Visual Odometry with Codec Awareness](https://arxiv.org/abs/2607.00189v1)

- **arXiv**: `2607.00189v1`  |  **提交日期**: 2026-06-30
- **作者**: Nouri Alexander Hilscher, Mateo de Mayo, Dominik Muhle, Christoph Otten genannt Hermes, Daniel Cremers

Camera pose estimation from image streams is a critical component of spatial world models that integrate perception into planning and decision-making. Nearly all Visual Odometry (VO) and Simultaneous Localization and Mapping (V-SLAM) systems have focused on datasets containing raw, uncompressed videos. Many working systems instead use ubiquitous hardware units to efficiently compress and decode video streams, saving orders of magnitude in storage and bandwidth. However, this lossy compression introduces visual artifacts that hinder the performance of traditional tracking systems. We present…

---

## 📅 2026-07-01

### [DVG-WM: Disentangled Video Generation Enables Efficient Embodied World Model for Robotic Manipulation](https://arxiv.org/abs/2606.32028v1)

- **arXiv**: `2606.32028v1`  |  **提交日期**: 2026-06-30
- **作者**: Ziyu Shan, Zhenyu Wu, Xiaofeng Wang, Zheng Zhu, Ziwei Wang

Video-based embodied world models provide an appealing substrate for robotic manipulation by predicting future states, yet current approaches remain limited by a fundamental entanglement: accurately modeling dynamics typically requires low-level temporal reasoning, while producing high-resolution frames demands expansive visual synthesis according to high-level semantics. This entanglement results in slow inference speed for iterative planning or too coarse predictions to retain contact-rich details. To solve this dilemma, we present Disentangled Video Generation World Model (DVG-WM), an…

---

### [AdaJEPA: An Adaptive Latent World Model](https://arxiv.org/abs/2606.32026v1)

- **arXiv**: `2606.32026v1`  |  **提交日期**: 2026-06-30
- **作者**: Ying Wang, Oumayma Bounou, Yann LeCun, Mengye Ren

Latent world models enable planning from high-dimensional observations by predicting future states in a compact latent space. However, these models are typically kept frozen at test time: when their predictions become inaccurate, planning can fail, especially under test-time distribution shift. To address this, we propose AdaJEPA, an adaptive latent world model that performs test-time adaptation within the closed loop of model predictive control (MPC). After training, AdaJEPA plans and executes the first action chunk, uses the observed next-state transition as a self-supervised adaptation…

---

### [LeCropFollow: Latent Space Planning for Navigation in Unstructured Crop Fields](https://arxiv.org/abs/2606.31941v1)

- **arXiv**: `2606.31941v1`  |  **提交日期**: 2026-06-30
- **作者**: Felipe Tommaselli, Francisco Affonso, Arthur Pompeu, Gianluca Capezzuto, Arun Narenthiran Sivakumar, Girish Chowdhary et al.

Unstructured navigational features, such as irregular planting or discontinuities, remain the primary failure mode for under-canopy agricultural robots. Existing geometric approaches often fail in these scenarios because they compress high-dimensional visual data into deterministic spatial references, effectively discarding the uncertainty and semantic context required to navigate ambiguous terrain. To address this, we present LeCropFollow, a visual navigation framework that bypasses explicit geometric modeling in favor of a learned latent representation. By integrating a self-supervised…

---

### [MemLearner: Learning to Query Context memory for Video World Models](https://arxiv.org/abs/2606.31734v1)

- **arXiv**: `2606.31734v1`  |  **提交日期**: 2026-06-30
- **作者**: Jiwen Yu, Jianxiong Gao, Jianhong Bai, Yiran Qin, Kaiyi Huang, Quande Liu et al.

Video World Models are interactive video generation models that predict future world states based on user actions and history video frames. A critical challenge in video world models is the lack of memory, causing inconsistent generated scenes over extended durations. Previous methods explored rule-based context frame retrieval as memory, but they fail to generalize in scenarios with scene occlusions and dynamic objects. We propose MemLearner, a learning-based adaptive context query method using query tokens to bridge context and predicted tokens. By leveraging the video generation model…

---

### [WorldRoamBench: An Open-World Benchmark for Long-Horizon Stability of Interactive World Models](https://arxiv.org/abs/2606.31672v1)

- **arXiv**: `2606.31672v1`  |  **提交日期**: 2026-06-30
- **作者**: Ting-Bing Xu, Jiacheng Sui, Zhe Gao, Kewei Shi, Wenjin Yang, Zhicheng Liu et al.

Despite rapid progress in interactive world models (IWMs), existing benchmarks evaluate action following only at trajectory level and ignore memory and interaction physics. We introduce WorldRoamBench, an open-world benchmark for long-horizon stability across four dimensions, each with tailored innovations: (i) Action: per-frame action metric bypassing cross-model semantic scale disparity and exposing failures hidden by trajectory; (ii) Vision: segment-based drift metric capturing non-monotonic mid-sequence collapse missed by start-vs-end comparisons; (iii) Physics: controllability-gated…

---

### [Ask the World Before Acting: Budgeted Environment Probing for World-Model Calibration](https://arxiv.org/abs/2606.31422v1)

- **arXiv**: `2606.31422v1`  |  **提交日期**: 2026-06-30
- **作者**: Xinyuan Song, Zekun Cai

Long-horizon language agents do not only choose actions; they carry a private model of the world from one decision to the next. When that model drifts, a later failure can be decided before the failing action is ever taken. We study a direct repair mechanism: before committing to the next task action, an agent may ask the environment about one belief field and write the answer back into its world model. This makes environment interaction a scarce calibration resource, not merely a way to advance the task. We introduce \method, a budgeted probing operator for structured belief tables. The…

---

### [World-Model Collapse as a Phase Transition](https://arxiv.org/abs/2606.31399v1)

- **arXiv**: `2606.31399v1`  |  **提交日期**: 2026-06-30
- **作者**: Xinyuan Song, Zekun Cai

Water looks unchanged as it warms, then at a critical point it boils. We ask whether long-horizon language agents show an analogous transition in their implicit world models. In some parameter settings, changing state load by a small amount, or adding a single step of horizon, leaves behavior nearly unchanged; near a critical boundary, the same small change causes a sudden world collapse. We study this effect in a deterministic task family with exact per-step gold state. A large grid search over state cardinality, dependency density, horizon, branching, observation mode, and mutation rate…

---

### [One Video, One World: Turning Monocular Video into Physical 4D Scenes](https://arxiv.org/abs/2606.31388v1)

- **arXiv**: `2606.31388v1`  |  **提交日期**: 2026-06-30
- **作者**: Junhao Chen, Boran Zhang, Mingjin Chen, Henghaofan Zhang, Saining Zhang, Congcong Zhu et al.

We introduce \textbf{OVOW}, the first training-free system that reconstructs \emph{instance-level, simulation-ready} 4D mesh scenes from a single monocular video. Recent 4D reconstruction achieves impressive rendering quality, but its outputs (\eg, implicit fields, Gaussian primitives, or point clouds) lack the watertight topology, instance separation, and standardized physical interfaces required by physics simulators and embodied AI. OVOW closes this gap with a four-stage pipeline: a vision-language model discovers, labels, and motion-classifies all instances; category-aware reconstruction…

---

### [Delta-JEPA: Learning Action-Sensitive World Models via Latent Difference Decoding](https://arxiv.org/abs/2606.31232v1)

- **arXiv**: `2606.31232v1`  |  **提交日期**: 2026-06-30
- **作者**: Zhenghao Zhang, Yuanxiang Wang, Zhenyu Guan, Yujia Yang, Bingkang Shi, Tianyu Zong et al.

Learning visual world models for planning requires compact latent dynamics that remain sensitive to actions, yet reconstruction-free joint-embedding objectives can collapse to action-insensitive representations. We propose Delta-JEPA, an end-to-end reconstruction-free world model that augments latent forward prediction with a Latent Difference Action Decoder (LDAD). Unlike inverse decoders that infer actions from concatenated endpoint embeddings, LDAD reconstructs the executed action from the latent displacement between consecutive observations. This displacement-level supervision directly…

---

### [ForgeDrive: Bidirectional Cross-Conditioning for Unified Visual-Action Generation in Autonomous Driving](https://arxiv.org/abs/2606.31226v1)

- **arXiv**: `2606.31226v1`  |  **提交日期**: 2026-06-30
- **作者**: Xuchang Zhong, He Zheng, Chenxu Zhao, Tianxiong Lv, Hangqi Fan, Bohua Wang et al.

World-model-based autonomous driving endows the model with the ability to understand scene evolution. Yet this promise is undermined by the prevailing imagine-then-act paradigm, which allows errors from the more challenging visual generation stage to cascade into action planning. We introduce ForgeDrive, a unified autoregressive diffusion framework with visual-action cross-conditioning that closes this gap through act-then-imagine paradigm. ForgeDrive factorizes the future as a sequence of per-timestep frame-action pairs, intertwining each action with its corresponding visual observation.…

---

### [Long-term Traffic Simulation via Structured Autoregressive Modeling](https://arxiv.org/abs/2606.31209v1)

- **arXiv**: `2606.31209v1`  |  **提交日期**: 2026-06-30
- **作者**: Lingyu Xiao, Zexin Feng, Xintao Yan

Interactive traffic simulation is a vital world model for autonomous driving. A central challenge in long-horizon simulation is modeling sustained multi-agent interactions, which is further exacerbated by dynamic token cardinality as agents continuously enter and exit the scene. In this work, we propose that the solution lies in the synergy between the architectural inductive biases and statistical priors of large-scale sequence models, e.g., Large Language Models (LLMs). Our probing experiments reveal that the transferability of attention mechanisms and the distributional consistency between…

---

### [Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)

- **arXiv**: `2606.31050v1`  |  **提交日期**: 2026-06-30
- **作者**: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin et al.

How to accurately predict a high-fidelity future world? While the visual world is inherently continuous, existing deterministic video prediction models operate in discrete pixel space and are mainly optimized with pixel-wise mean squared error (MSE), which often leads to over-smoothed predictions and a lack of fine-grained visual details. To address these limitations, we propose Predictive Differentiable Rendering (PDR), a novel end-to-end video prediction paradigm that bridges the gap between discrete and continuous representations. Inspired by recent progress in 3D reconstruction with 3D…

---

### [LWDrive: Layer-Wise World-Model-Guided Vision-Language Model Planning for Autonomous Driving](https://arxiv.org/abs/2606.29879v2)

- **arXiv**: `2606.29879v2`  |  **提交日期**: 2026-06-29
- **作者**: Chen Yang, Yuhao Wei, Ze Xu, Ziheng Zou, Shuang Liang, Delin Ouyang et al.

Vision-Language Models (VLMs) provide powerful semantic understanding and commonsense reasoning for End-to-End Autonomous Driving (E2E-AD) planning. However, trajectories directly generated by VLMs often encode only coarse driving intentions and remain insufficient for geometrically accurate, future-aware, and multi-view-grounded planning. To address these limitations, we develop the Layer-Wise World-Model-Guided Driving framework (LWDrive). LWDrive is a VLM planning framework that refines coarse trajectories through layer-wise world-model guidance. Instead of treating the VLM output as the…

---

## 📅 2026-06-30

### [Self-Evolving World Models for LLM Agent Planning](https://arxiv.org/abs/2606.30639v1)

- **arXiv**: `2606.30639v1`  |  **提交日期**: 2026-06-29
- **作者**: Xuan Zhang, Wenxuan Zhang, See-Kiong Ng, Yang Deng

World models offer a principled way to equip long-horizon LLM agents with foresight: predictions of action consequences before execution. However, unreliable foresight can be ignored, misused, or even degrade downstream decision-making. In this paper, we introduce WorldEvolver, a self-evolving world model framework that revises its deployment-time context while keeping the downstream agent and all model parameters frozen. WorldEvolver integrates three modules: (i) Episodic Memory, which exploits real action transitions through retrieval-based simulation; (ii) Semantic Memory, which extracts…

---

### [OWMDrive: Causality-Aware End-to-End Autonomous Driving via 4D Occupancy World Model](https://arxiv.org/abs/2606.30421v1)

- **arXiv**: `2606.30421v1`  |  **提交日期**: 2026-06-29
- **作者**: Junjie Cheng, Ruiqi Song, Ye Wu, Nanxing Zeng, Ximiao Li, Yunfeng Ai

Autonomous driving systems are steadily moving toward end-to-end paradigms to mitigate the limited adaptability of rule-based pipelines in complex traffic environments. However, most existing learning-based methods still make decisions from static representations of the current scene, without explicit future rollouts or modeling of the temporal causal dynamics in traffic interactions. This limitation often results in unstable or overly conservative planning under high-uncertainty conditions, such as occlusions and unexpected events. To overcome these challenges, we introduce OWMDrive, a…

---

### [DreamForge-World 0.1 Preview: A Low-Compute Real-Time Controllable World Model](https://arxiv.org/abs/2606.30292v1)

- **arXiv**: `2606.30292v1`  |  **提交日期**: 2026-06-29
- **作者**: Daniyel Ayupov, Artur Markov-Tsoy

We present DreamForge-World 0.1 Preview, a preview foundational world model for real-time interactive world simulation. The system adapts the LongLive 1 autoregressive video stack, itself derived from Wan2.1-T2V-1.3B, with a residual action pathway inspired by the Matrix-Game family. DreamForge-World 0.1 Preview focuses on a complementary axis to frontier-scale world simulators: low-compute adaptation, consumer-GPU runtime, and broad interactive capability coverage. It supports live keyboard and mouse control, multimodal initialization, mid-stream reprompting, dual-view operation, and…

---

### [Pondering the Way: Spatial-perceiving World Action Model for Embodied Navigation](https://arxiv.org/abs/2606.29908v1)

- **arXiv**: `2606.29908v1`  |  **提交日期**: 2026-06-29
- **作者**: Hong Chen, Daqi Liu, Zehan Zhang, Haiguang Wang, Tianhao Lu, Longfei Yan et al.

Existing world model-based planners for visual navigation typically follow a verification-centric paradigm, decoupling goal intent from trajectory synthesis. This approach suffers from candidate dependence, heavy computational overhead, and inconsistencies between sampled actions and predicted visuals. To address these issues, we propose SWAM (Spatial-perceiving World Action Model), a task-centric joint observation-action generation framework. Given start and goal RGB observations, SWAM performs single-pass inference to simultaneously generate intermediate RGB-D sequences and corresponding…

---

### [LWDrive: Layer-Wise World-Model-Guided Vision-Language Model Planning for Autonomous Driving](https://arxiv.org/abs/2606.29879v1)

- **arXiv**: `2606.29879v1`  |  **提交日期**: 2026-06-29
- **作者**: Chen Yang, Yuhao Wei, Ze Xu, Ziheng Zou, Shuang Liang, Delin Ouyang et al.

Vision-Language Models (VLMs) provide powerful semantic understanding and commonsense reasoning for End-to-End Autonomous Driving (E2E-AD) planning. However, trajectories directly generated by VLMs often encode only coarse driving intentions and remain insufficient for geometrically accurate, future-aware, and multi-view-grounded planning. To address these limitations, we develop the Layer-Wise World-Model-Guided Driving framework (LWDrive). LWDrive is a VLM planning framework that refines coarse trajectories through layer-wise world-model guidance. Instead of treating the VLM output as the…

---

### [The CRISTAL Method: Neurosymbolic analysis from AI-synthesized world models](https://arxiv.org/abs/2606.29799v1)

- **arXiv**: `2606.29799v1`  |  **提交日期**: 2026-06-29
- **作者**: Rafael Kaufmann, Felix Neubürger, Michael Walters, Thomas Kopinski, Dimitrije Marković

This project introduces the CRISTAL Method (Coherent Reliable Intentional Synthesis of Truthful Analysis Logic), a neurosymbolic framework for automating complex analysis workflows, with fundamental investment analysis as a primary use case. This domain poses major challenges: high structural uncertainty, noisy and subjective data, tight attention budgets, and the need for justified, reproducible decisions. Human analysts often struggle in this domain due to cognitive biases and limitations, suggesting significant value in automation. But while LLM-based agents have been proposed as…

---

### [HERO: Improving the Reliability and Sensitivity of Generative Model Evaluation Using Historical Data](https://arxiv.org/abs/2606.29784v1)

- **arXiv**: `2606.29784v1`  |  **提交日期**: 2026-06-29
- **作者**: Xinrui Ruan, Zhenyu Zhao, Waverly Wei, Yueshan Zhang, Zeyu Zheng, Sui Huang et al.

Reliable generative AI models critically rely on expert human annotations to evaluate output quality, yet these "gold" labels are expensive to collect and limited in quantity. Organizations thus often turn to collecting vast but noisy "silver" labels from crowdsourced workers or vendor annotators as proxies for gold labels. Because gold remains the evaluation target, naively aggregating noisy silver labels may introduce bias, and estimators built on sparsely observed gold labels may have high variance to resolve the model performance gaps that guide practical decisions. Model evaluation has…

---

### [Learning Transferable Dynamics Priors from Action to World Modeling](https://arxiv.org/abs/2606.29501v1)

- **arXiv**: `2606.29501v1`  |  **提交日期**: 2026-06-28
- **作者**: Ze Huang, Jiahui Zhang, Hairuo Liu, Chenxi Zhang, Ran Cheng, Li Zhang

We study action-conditioned world modeling as a scalable way to learn transferable dynamics priors for robot learning. By pretraining a model to predict how actions drive visual scene evolution, the resulting world model captures reusable interaction dynamics beyond appearance-level video generation. Concretely, we pretrain a multi-view interactive base diffusion world model, A2World, on large-scale robot manipulation data with real action annotations. We validate the learned dynamics priors from two complementary perspectives. First, we adapt A2World into a task- or scene-specialized…

---

### [Cognitive World Models for Process-Level Social Influence Evaluation](https://arxiv.org/abs/2606.29495v1)

- **arXiv**: `2606.29495v1`  |  **提交日期**: 2026-06-28
- **作者**: Minghui Ma, Bin Guo, Han Wang, Mengqi Chen, Jingqi Liu, Yan Liu et al.

Social influence dialogue changes user behavior by altering internal cognitive states. The central evaluation question is whether the user's beliefs, desires, intentions, and emotions measurably change over the course of conversation, a process-oriented criterion that neither surface-level text metrics (BLEU/ROUGE) nor single-score LLM judgments can capture. We propose the \textbf{Cog}nitive \textbf{W}orld \textbf{M}odel \textbf{(CogWM)}, an LLM-based user model that reframes multi-turn dialogue evaluation from ``what did the user say'' to ``how did the user's internal cognitive state…

---

### [Prototype Latent World Model Replay for Class-Incremental Learning](https://arxiv.org/abs/2606.29465v1)

- **arXiv**: `2606.29465v1`  |  **提交日期**: 2026-06-28
- **作者**: Weizhi Nie, Hui Wang, Weijie Wang, Yuting Su

Class-incremental learning requires a model to learn new classes while preserving decision regions for old ones. This is difficult when raw old samples are no longer available. We propose Prototype Latent World Model Replay, a memory-free framework that stores old classes as distributions over stable hidden states rather than as images. A frozen ImageNet-pretrained encoder maps each image into a latent state space. In this space, each class is summarized by several prototype-centered distributions with class-specific variances. When new classes arrive, the model samples old latent states from…

---

### [L2D2-GS: Learning to Densify for Feedforward Dynamic Gaussian Scene Reconstruction](https://arxiv.org/abs/2606.29374v1)

- **arXiv**: `2606.29374v1`  |  **提交日期**: 2026-06-28
- **作者**: Zetian Song, Chenming Wu, Junnan Liu, Chitian Sun, Liangliang He, Hangjun Ye et al.

High-fidelity reconstruction of dynamic urban environments is a cornerstone of autonomous driving simulation and large-scale world modeling. While 3D Gaussian Splatting (3DGS) has established a new standard for real-time rendering, its reliance on expensive per-scene optimization limits scalability. Conversely, recent feedforward methods that infer Gaussian parameters offer faster speed but face fundamental bottlenecks: they are memory-prohibitive at high resolutions and struggle to fuse dense multi-view observations consistently. This paper presents L2D2-GS, a unified framework that…

---

### [ASTAD: Asymmetric Style Transfer for Synthetic-to-Real Adaptation in Autonomous Driving](https://arxiv.org/abs/2606.29286v1)

- **arXiv**: `2606.29286v1`  |  **提交日期**: 2026-06-28
- **作者**: Dingyi Yao, Xinqi Zhang, Lihui Peng, Jianming Hu, Danya Yao, Yi Zhang

Synthetic data mitigates the data scarcity problem in autonomous driving perception. However, the synthetic-to-real gap leads to performance degradation, hindering real-world model generalization. Although current methods leverage diffusion models for photorealistic style transfer to bridge this gap, they critically ignore a practical asymmetry: while synthetic data possesses perfect pixel-level annotations, real-world style reference images generally lack corresponding labels. Consequently, existing methods relying on symmetric semantic guidance suffer from either prohibitive annotation…

---

### [Flow Matching in Feature Space for Stochastic World Modeling](https://arxiv.org/abs/2606.29059v1)

- **arXiv**: `2606.29059v1`  |  **提交日期**: 2026-06-27
- **作者**: Francois Porcher, Nicolas Carion, Karteek Alahari, Shizhe Chen

World modeling requires forecasting uncertain futures while preserving information useful for downstream perception. Existing visual world models often struggle to satisfy both goals: VAE-based stochastic models operate in low-dimensional reconstruction latents, which can limit perception performance, while deterministic predictors using strong pretrained features collapse multimodal futures into a single blurry mean. In this work, we propose FlowWM, a stochastic world model that performs flow matching directly within pretrained feature space (e.g., DINOv3). This is challenging because…

---

### [A Physics-Grounded Benchmark for Multi-Agent Dynamics in World Models](https://arxiv.org/abs/2606.28757v1)

- **arXiv**: `2606.28757v1`  |  **提交日期**: 2026-06-27
- **作者**: Nuo Chen, Lulin Liu, Zihao Li, Ziyao Zeng, Zihao Zhu, Wenyan Cong et al.

Generative world models hold immense promise as scalable simulators for autonomous systems, particularly for synthesizing rare but safety-critical multi-agent interactions, such as vehicle collisions. However, current evaluation paradigms index heavily on visual fidelity and semantic alignment, leaving a critical blind spot: they cannot reliably quantify whether generated dynamics actually obey the fundamental physical laws required for reliable simulation. Assessing this physical plausibility is inherently difficult due to a lack of physical metrics and the challenge of extracting…

---

### [A Path-Space Formulation of Prediction in World Models: From a Single Action to Prediction, Planning, and Irreversibility](https://arxiv.org/abs/2606.28751v1)

- **arXiv**: `2606.28751v1`  |  **提交日期**: 2026-06-27
- **作者**: Gunn Kim

We propose a path-space formulation of prediction in AI world models. Rather than sequences of one-step conditional distributions, we argue that a world model implicitly defines a probability measure over future trajectories. In the local regime where latent dynamics admit an effective Markovian description, this path measure takes the Onsager-Machlup form. Within this framework, prediction (most probable trajectory), planning (constrained optimization), and uncertainty (fluctuations) emerge as operations on a single action functional. We decompose the latent dynamics into reversible and…

---

### [J-LAW: Joint Localization and Actionable World Modeling via Coupled Latent Factor Graphs](https://arxiv.org/abs/2606.28712v1)

- **arXiv**: `2606.28712v1`  |  **提交日期**: 2026-06-27
- **作者**: Guanqun Cao, Liang Chen

Classical SLAM estimates metric poses and a geometric map but produces no actionable predictive model for planning. Action-conditioned world models learn compact latent dynamics for planning but ignore global metric consistency and accumulate drift under open-loop rollout. We argue these are two views of the same estimation problem and propose J-LAW (Joint Localization and Actionable World Modeling) in this letter: a coupled factor graph that jointly optimizes metric object poses, latent world states, and latent landmark embeddings. The bridge is a pose-conditioned latent encoder and a…

---

## 📅 2026-06-29

### [PhysisForcing: Physics Reinforced World Simulator for Robotic Manipulation](https://arxiv.org/abs/2606.28128v1)

- **arXiv**: `2606.28128v1`  |  **提交日期**: 2026-06-26
- **作者**: Peiwen Zhang, Yufan Deng, Shangkun Sun, Juncheng Ma, Duomin Wang, Jonas Du et al.

Video generation models have emerged as a promising paradigm for embodied world simulation. However, both general-domain video generators and robot-specific data fine-tuned models can still produce physically implausible manipulations, including discontinuous motion trajectories and inconsistent robot-object interactions, which limits their reliability as world simulators. Through extensive experiments, we find that such physical instability mainly arises from two factors: deformation of moving objects and implausible spatio-temporal correlations among interacting entities, particularly…

---

### [From Tokens to States: LLMs as a Special Case of World Models and the Continuous Path Beyond](https://arxiv.org/abs/2606.28127v1)

- **arXiv**: `2606.28127v1`  |  **提交日期**: 2026-06-26
- **作者**: Paul Dubois

The AI community has framed the relationship between large language models (LLMs) and world models as a dichotomy: LLMs predict tokens; world models simulate reality. Yann LeCun argues in 2022 that reaching general intelligence requires abandoning autoregressive token prediction in favour of latent-space architectures. This framing is unnecessarily binary. Two claims will be defended. First, LLMs are a degenerate special case of world models: the state space is the set of all token sequences, the only action is appending one token, and world models are therefore a strict generalisation of…

---

### [Directing the World: Fast Autoregressive Video Generation with Compositional Human-Camera Control](https://arxiv.org/abs/2606.27964v1)

- **arXiv**: `2606.27964v1`  |  **提交日期**: 2026-06-26
- **作者**: Haoyuan Wang, Yabo Chen, Haibin Huang, Chi Zhang, Xuelong Li

Building interactive world models requires generating realistic videos while maintaining controllable dynamics over long horizons. Autoregressive video generation offers a scalable foundation, but suffers from error accumulation and temporal degradation during extended rollouts. This issue is further amplified under heterogeneous controls such as human motion and camera trajectories, which may interfere and destabilize a pretrained video prior, while existing methods often trade off controllability and visual quality. We propose "Directing the World", a fast autoregressive framework for…

---

### [Grounded Iterative Language Planning: How Parameterized World Models Reduce Hallucination Propagation in LLM Agents](https://arxiv.org/abs/2606.27806v1)

- **arXiv**: `2606.27806v1`  |  **提交日期**: 2026-06-26
- **作者**: Xinyuan Song, Zekun Cai

World models for language agents come in two useful forms. An agent-based world model calls an LLM API and reasons flexibly in language, but its errors appear as hallucinated state changes that are hard to score with ordinary regression losses. A parameterized world model is a trained transition predictor; its errors are easier to measure with quantities such as NodeMSE, delta accuracy, and validity accuracy, but it is usually weaker as a standalone planner. We compare these two families on four graph-structured planning benchmarks and introduce operational hallucination metrics for the…

---

### [Understanding Rollout Error in Graph World Models](https://arxiv.org/abs/2606.27780v1)

- **arXiv**: `2606.27780v1`  |  **提交日期**: 2026-06-26
- **作者**: Xinyuan Song, Zekun Cai

World models are often used for planning by rolling learned dynamics forward. Many planning environments, however, are not vectors or images; they are graphs of agents, tools, skills, routes, and dependencies. In these settings, a local prediction error may stay local or spread through the graph, and the failure mode changes again when edges are predicted rather than fixed. This paper studies long-horizon rollout error in Graph World Models (GWMs). We formulate a unified fixed-edge and dynamic-edge GWM framework with action nodes for node-, edge-, and graph-level decisions. We develop…

---

### [Textual Belief States for World Models: Identifiable Representation Learning Under Strict Mediation](https://arxiv.org/abs/2606.27681v1)

- **arXiv**: `2606.27681v1`  |  **提交日期**: 2026-06-26
- **作者**: Xiang Gao, Kaiwen Dong, Yuguang Yao, Padmaja Jonnalagedda, Kamalika Das

World models in partially observed environments rely on latent representations that summarize interaction history, but in many modern LLM-based architectures predictive performance fails to reflect representation quality due to history bypass, rendering the latent state unidentifiable. Strict latent state mediation, requiring predictions to depend only on the latent state and action, is a classical principle that resolves this, but enforcing it in text-based settings is an open challenge: textual latent states are discrete and non-differentiable, precluding variational training, and…

---

### [CascadeOcc: Rethinking 3D Occupancy World Models with Cascaded VQ Representations](https://arxiv.org/abs/2606.27644v1)

- **arXiv**: `2606.27644v1`  |  **提交日期**: 2026-06-26
- **作者**: Kyumin Hwang, Wonhyeok Choi, Jaeyeul Kim, Jihun Park, Daehee Park, Sunghoon Im

This letter proposes CascadeOcc, a novel occupancy world model that prioritizes intrinsic structural hierarchy over extrinsic auxiliary modalities for autonomous driving. Occupancy world models -- forecasting the future driving environment and planning the driving trajectory -- effectively bridge perception and planning, but current approaches often heavily rely on external modalities or large language models, failing to fully exploit the inherent structural potential of occupancy representations themselves. To enhance representational capacity for complex 3D scenes, we integrate a cascaded…

---

## 📅 2026-06-27

### [PhysiFormer: Learning to Simulate Mechanics in World Space](https://arxiv.org/abs/2606.27364v1)

- **arXiv**: `2606.27364v1`  |  **提交日期**: 2026-06-25
- **作者**: Yiming Chen, Yushi Lan, Andrea Vedaldi

We present PhysiFormer, a diffusion transformer for physically-plausible 3D object motion. Unlike video world models that operate in view-dependent pixel space, PhysiFormer represents objects as 3D meshes expressed in world coordinates. Given the initial vertex positions and velocities, as well as object material type, rigid or elastic, the model samples future vertex trajectories. While related neural physics approaches build on ad-hoc latent spaces or explicitly enforce rigidity and causality, PhysiFormer shows that excellent results can be obtained without any such inductive biases, by…

---

### [Hallucination in World Models is Predictable and Preventable](https://arxiv.org/abs/2606.27326v1)

- **arXiv**: `2606.27326v1`  |  **提交日期**: 2026-06-25
- **作者**: Nicklas Hansen, Xiaolong Wang

Modern generative world models render increasingly realistic action-controllable futures, yet they frequently hallucinate: rollouts remain visually fluent while drifting from the ground-truth dynamics. We hypothesize that hallucination concentrates in low-coverage regions of the state-action space, where lightweight data-centric signals can both detect it and guide mitigation. To test this, we introduce MMBench2, a 427-hour, 210-task dataset for visual world modeling with ground-truth actions, rewards, and live simulators, and train a 350M-parameter world model on it. We identify three…

---

### [Not All Actions Are Equal: Rethinking Conditioning for Dexterous World Model](https://arxiv.org/abs/2606.27325v1)

- **arXiv**: `2606.27325v1`  |  **提交日期**: 2026-06-25
- **作者**: Zizhao Yuan, Zhengtu Liang, Taowen Wang, Qiwei Liang, Yichi Wang, Yunheng Wang et al.

Recent advances in action-conditioned world models show promising progress in modeling complex interactions and forecasting future states under diverse action sequences. While these models are often driven by stronger visual representations and model capacity, action conditioning itself remains underexplored. Most existing approaches compress the entire action sequence into a single representation, which works well for low-DoF control but becomes less reliable in high-DoF scenarios. We observe that high-DoF dexterous actions are inherently heterogeneous, spanning multiple orders of magnitude,…

---

### [EO-WM: A Physically Informed World Model for Probabilistic Earth Observation Forecasting](https://arxiv.org/abs/2606.27277v1)

- **arXiv**: `2606.27277v1`  |  **提交日期**: 2026-06-25
- **作者**: Junwei Luo, Shuai Yuan, Zhenya Yang, Yansheng Li, Zhe Liu, Hengshuang Zhao

Earth Observation (EO) forecasting aims to predict future Earth surface dynamics from satellite observations under changing meteorological conditions. In this paper, we view this task as a partially observed, weather-driven world modeling problem, in which weather acts as a conditioning signal, while forecasting remains uncertain due to sparse observations and unobserved land-surface states. However, existing methods do not fully capture this setting: deterministic models collapse uncertainty into a single future prediction, while diffusion-based methods typically treat weather variables as…

---

### [A Generalization Theory for JEPA-Based World Models](https://arxiv.org/abs/2606.27014v1)

- **arXiv**: `2606.27014v1`  |  **提交日期**: 2026-06-25
- **作者**: Jingyi Cui, Qi Zhang, Hongwei Wen, Yisen Wang

Joint Embedding Predictive Architectures (JEPAs) have recently emerged as a promising paradigm for world modeling by learning predictive dynamics in a latent space rather than generating future observations at the input level. Despite their empirical success, the theoretical understanding of JEPA-based world models remains limited. In this paper, we develop the first generalization theory for JEPA-based world models. We formulate JEPA pretraining as a conditional spectral graph learning problem and show that the JEPA objective is equivalent to a low-rank factorization of an action-conditioned…

---

### [Einstein World Models](https://arxiv.org/abs/2606.26969v1)

- **arXiv**: `2606.26969v1`  |  **提交日期**: 2026-06-25
- **作者**: Munachiso Samuel Nwadike, Zangir Iklassov, Ali Mekky, Zayd M. Kawakibi Zuhri, Kentaro Inui

Does intelligence require the ability to reason about phenomena beyond direct experience? It is natural to suspect that some complex thought cannot be captured through language alone. However, of particular concern to this work, is whether visualising counterfactual events can complement language as a mechanism for complex thought. We ask whether LLMs can be trained to utilise such visualisation mechanisms, in a way that benefits their reasoning abilities. Motivated by this question, we propose Einstein World Models. EWMs are a blueprint for LLM-based reasoning systems that place…

---

### [Look-Before-Move: Narrative-Grounded World Visual Attention in Dynamic 3D Story Worlds](https://arxiv.org/abs/2606.26964v1)

- **arXiv**: `2606.26964v1`  |  **提交日期**: 2026-06-25
- **作者**: Jiaming Bian, Bingliang Li, Yuehao Wu, Pichao Wang, Zhi Wang, Hailan Ma et al.

As embodied AI and world models increasingly operate in dynamic 3D environments, visual perception must move beyond passively interpreting given observations toward actively deciding what to observe. We study this problem through camera planning in dynamic 3D story worlds, where the camera must not only generate smooth motion, but also decide what visual evidence should be acquired before it moves. We formulate this capability as Narrative-Grounded World Visual Attention, where the camera acts as an embodied observer that determines what to observe, how to compose the observation, and how to…

---

### [Risk-Aware Selective Multimodal Driver Monitoring with Driver-State World Modeling](https://arxiv.org/abs/2606.26922v1)

- **arXiv**: `2606.26922v1`  |  **提交日期**: 2026-06-25
- **作者**: Daosheng Qiu, Haozhuang Chi, Hao Su, Shu Long, Xinyue Miao, Yongle Dong et al.

Continuous driver monitoring in automated vehicles requires low-latency inference while avoiding unsafe decisions under uncertain driver states. Large vision-language models provide broad multimodal priors, but their latency and limited reliability in this setting make them unsuitable as always-on in-cabin monitors. We propose a cost-aware selective inference framework for deployable multimodal driver monitoring. The core system is a lightweight RGB-physiological student that combines in-cabin visual observations with window-level HR/EDA signals, and a learned gate that decides when to accept…

---

### [LithoDreamer: A Physics-Informed World Model for Multi-Stage Computational Lithography](https://arxiv.org/abs/2606.26713v1)

- **arXiv**: `2606.26713v1`  |  **提交日期**: 2026-06-25
- **作者**: Yuqi Jiang, Yumeng Liu, Zimu Li, Jinyuan Deng, Qian Jin, Yucheng Cui et al.

As semiconductor technology nodes scale, computational lithography is essential for ensuring yield and performance. However, lithography is a continuous physical process involving mask optimization, optical imaging, resist exposure, and development, which existing models fail to capture. To overcome this limitation, we present LithoDreamer, the first physics-informed World Model (WM) framework for computational lithography, which formulates the ``Layout-Mask-Resist Image-After Development Image (ADI)'' pipeline as a decision-driven multi-step evolution system. LithoDreamer captures feature…

---

### [PhysEditWorld: A Large-Scale Dataset Toward Physics-Editable World Models](https://arxiv.org/abs/2606.26694v1)

- **arXiv**: `2606.26694v1`  |  **提交日期**: 2026-06-25
- **作者**: Bin Hu, Yanwen Ma, Jiehui Huang, Ziliang Zhang, Haoning Wu, Ruicheng Zhang et al.

Recent game world models can synthesize visually plausible, action-conditioned rollouts. However, their interaction behaviors often remain limited to exploratory or wandering trajectories, and physical dynamics are typically learned as implicit correlations from data rather than as controllable variables. This limitation hinders their applicability to authored game environments, where physical rules are deliberately designed and require explicit manipulation. We introduce PhysEditWorld, a multimodal dataset with physical parameters, with a primary focus on gravity in this initial version. At…

---

### [Neural Voxel Dynamics: Learning Implicit 3D Physics via Volumetric Feature Advection](https://arxiv.org/abs/2606.26410v1)

- **arXiv**: `2606.26410v1`  |  **提交日期**: 2026-06-24
- **作者**: Zican Wang, Niloy Mitra

We present a self-supervised framework for learning implicit 3D physical dynamics directly from video-derived supervisory signals. While current generative video models achieve high visual fidelity, they lack a 3D geometric foundation, often resulting in physical inconsistencies and a failure to maintain object permanence. We address this by shifting the predictive bottleneck from 2D image space to a `lifted' 3D Volumetric Latent Space. Our method unprojects semantic features from a Video Joint-Embedding Predictive Architecture (V-JEPA) into a voxelized grid, grounded by monocular depth…

---

### [KRVF: A Source-Aware Semantic Voxel World Representation for Edge Mobile Manipulation](https://arxiv.org/abs/2606.26321v1)

- **arXiv**: `2606.26321v1`  |  **提交日期**: 2026-06-24
- **作者**: Runfeng Ling

Mobile manipulators need world models that are current, queryable, semantically meaningful, and usable under edge-compute constraints. This technical report presents KRVF, a source-aware semantic voxel world representation for edge mobile manipulation. Unlike reconstruction-centric mapping pipelines that primarily optimize global geometric fidelity, KRVF represents local world state as task-oriented voxels that encode occupancy, color, semantic evidence, temporal freshness, and evidence source. The representation separates measured occupancy from semantic-prior hypotheses, enabling…

---

### [Fast LeWorldModel](https://arxiv.org/abs/2606.26217v1)

- **arXiv**: `2606.26217v1`  |  **提交日期**: 2026-06-24
- **作者**: Yuntian Gao, Xiangyu Xu

Joint-Embedding Predictive Architectures (JEPAs), including recent LeWorldModel (LeWM), have become a promising foundation for reconstruction-free visual world models. For visual planning, however, LeWM evaluates candidate action sequences by repeatedly applying a local one-step latent transition model. This autoregressive rollout makes planning computationally expensive and exposes the predicted trajectory to accumulated latent errors as the horizon grows. We propose Fast LeWorldModel (Fast-LeWM), a fast latent world model that replaces repeated local rollout with action-prefix prediction.…

---

### [The Unfireable Safety Kernel: Execution-Time AI Alignment for AI Agents and Other Escapable AI Systems](https://arxiv.org/abs/2606.26057v1)

- **arXiv**: `2606.26057v1`  |  **提交日期**: 2026-06-24
- **作者**: Seth Dobrin, Łukasz Chmiel

AI agents are granted access to tools, APIs, and other infrastructure, making them active principals in those systems. The dominant approach places controls inside the agent's own runtime: system prompts, output filters, and guardrail libraries. Any control in the agent's address space is reachable by inputs that influence it; this generalizes to any AI system with sufficient reach into its own runtime, a class we term escapable AI systems. We identify four properties that an authorization mechanism must satisfy for architectural control rather than for cooperative requests: process…

---

### [In-Context World Modeling for Robotic Control](https://arxiv.org/abs/2606.26025v2)

- **arXiv**: `2606.26025v2`  |  **提交日期**: 2026-06-24
- **作者**: Siyin Wang, Junhao Shi, Senyu Fei, Zhaoyang Fu, Li Ji, Jingjing Gong et al.

Modern Vision-Language-Action (VLA) models often fail to generalize to novel setups, such as altered camera viewpoints or robot morphologies, because they are typically conditioned only on current observations and language instructions. By ignoring the underlying system configuration as a variable, these models implicitly assume a fixed execution context encountered during training, necessitating data-intensive fine-tuning for any new environment. In this work, we introduce In-Context World Modeling (ICWM), a framework that treats system identification as an in-context adaptation problem.…

---

### [USS: Unified Spatial-Semantic Prompts for Embodied Visual Tracking with Latent Dynamics Learning](https://arxiv.org/abs/2606.25880v1)

- **arXiv**: `2606.25880v1`  |  **提交日期**: 2026-06-24
- **作者**: Yuchen Xie, Xinyu Zhou, Kuangji Zuo, Yanshuo Lu, Fengrui Huang, Boyu Ma et al.

Embodied Visual Tracking (EVT) requires an agent to continuously follow a specified target while actively moving through dynamic environments. However, prevailing EVT paradigms predominantly rely on language-based target indication. While language is expressive and convenient, cluttered scenes often contain multiple objects that satisfy the same semantic description, leading to ambiguous target grounding. We therefore propose a paradigm shift, reframing target indication in EVT from text-only specification to unified spatial-semantic prompting. Based on this paradigm, we introduce Unified…

---

### [Beyond One-Size-Fits-All: Diagnosis-Driven Online Reinforcement Learning with Offline Priors](https://arxiv.org/abs/2606.25527v1)

- **arXiv**: `2606.25527v1`  |  **提交日期**: 2026-06-24
- **作者**: Guozheng Ma, Lu Li, Zilin Wang, Pierre-Luc Bacon, Dacheng Tao

Online reinforcement learning (RL) agents increasingly depend on knowledge acquired offline to achieve practical efficiency. Originally studied in offline-to-online RL, this paradigm now spans foundation model post-training and embodied intelligence, with prior types expanding from offline datasets and pre-trained policies to increasingly diverse knowledge sources such as multimodal foundation models and generative world models. Offline priors have become central to how deep RL is developed and deployed. However, this reliance introduces a challenge that the prevailing benchmark-driven…

---

### [Causal-rCM: A Unified Teacher-Forcing and Self-Forcing Open Recipe for Autoregressive Diffusion Distillation in Streaming Video Generation and Interactive World Models](https://arxiv.org/abs/2606.25473v1)

- **arXiv**: `2606.25473v1`  |  **提交日期**: 2026-06-24
- **作者**: Kaiwen Zheng, Guande He, Min Zhao, Jintao Zhang, Huayu Chen, Jianfei Chen et al.

Autoregressive video diffusion with causal diffusion transformers has emerged as a major paradigm for real-time streaming video generation and action-conditioned interactive world models. In this work, we extend rCM, an advanced diffusion distillation framework, to autoregressive video diffusion. The core philosophy of rCM lies in the complementarity between forward and reverse divergences, represented by consistency models (CMs) and distribution matching distillation (DMD), respectively, in diffusion distillation. This philosophy naturally carries over to the autoregressive setting, where…

---

### [Hypergraph Normal World Models for Logical Visual Anomaly Detection](https://arxiv.org/abs/2606.25368v1)

- **arXiv**: `2606.25368v1`  |  **提交日期**: 2026-06-24
- **作者**: Weizhi Nie, Zibo Xu, Weijie Wang, Yuting Su

Visual anomaly detection is often deployed with only normal training images. Most one-class detectors map test patches or features to a normal reference distribution. This works well for local structural defects. Logical anomalies are different. Each visible part may look normal, while the whole image violates a normal count, co-occurrence, or spatial relation. This paper studies whether a model can learn such a category-specific normal world from nominal images alone. We propose the Hypergraph Normal World Model, a normal-only detector that distills frozen DINOv2 patch tokens into patch,…

---

