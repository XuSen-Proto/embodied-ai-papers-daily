# 物理AI / 具身智能 (Physical & Embodied AI)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-08-21

### [DreamHand: Repurposing Video Diffusion Models for Occlusion-Robust Egocentric 3D Hand Motion Recovery](https://arxiv.org/abs/2608.20308v1)

- **arXiv**: `2608.20308v1`  |  **提交日期**: 2026-08-20
- **作者**: Yufei Liu, Xixi Wang, Hao Li, Ganlong Zhao, Kaitong Cai, Chengkai Jin et al.

Egocentric video offers scalable manipulation data for embodied AI, yet recovering metric 3D hand trajectories remains challenging due to severe object occlusion and frequent out-of-sight gaps. Existing single-frame and windowed temporal regressors fail when hand shortly leaves the frame, while recent video diffusion models (VDMs) rely on heavy, stochastic multi-step sampling as pixel-space renderers. We instead repurpose VDM into a deterministic geometry encoder. A single forward pass over the clean latent exposes scene content beyond current observations, including occluded and out-of-sight…

---

### [Towards general embodied intelligence: integrating large language models, knowledge bases, and reasoning capabilities to build the next generation of AI agents](https://arxiv.org/abs/2608.19794v1)

- **arXiv**: `2608.19794v1`  |  **提交日期**: 2026-08-20
- **作者**: Fujiang Yuan, Xia Huang, Lusheng Wang, Jun Ding, Zhen Tian, Yuxin Wang et al.

The convergence of large language models (LLMs), structured knowledge bases (KBs), and reasoning ability (RA) presents a promising trajectory toward general embodied intelligence (GEI). This paper reviews the evolution of LLM-centered intelligent systems, emphasising their integration with knowledge representation, logical reasoning, and physical embodiment. We analyse LLM architectures, pre-training methods, and inference mechanisms, along with their interaction with external knowledge sources and structured reasoning frameworks. Furthermore, we examine embodied intelligence (EI) paradigms…

---

### [SafeBranch: Branch-Pair Safety Alignment for Embodied Agents](https://arxiv.org/abs/2608.19729v1)

- **arXiv**: `2608.19729v1`  |  **提交日期**: 2026-08-20
- **作者**: Hyunse Lee, Jiwoo Jeong, Haneul Lee, Kyochul Jang, Youngjae Yu, Woojin Lee

Vision-language-model-based embodied agents can complete instructed tasks but often violate safety constraints in the process, a problem recently framed as interactive safety. Training such agents to act safely is difficult, since safety and task success are distinct objectives, and safety arises only at a small number of safety-critical steps within a trajectory. Standard supervision is insufficient: imitating safe trajectories teaches behavior without explaining why it is safe, and contrasting arbitrary safe and unsafe trajectories mixes the safety signal with unrelated differences. We…

---

### [The Verification Gap in Networked Physical AI: A Post-Semantic Communication Framework](https://arxiv.org/abs/2608.19593v1)

- **arXiv**: `2608.19593v1`  |  **提交日期**: 2026-08-20
- **作者**: Shunsuke Saruwatari

A task-effective proposal is not yet a justified physical action. In networked Physical AI, a proposal may be understood while valid, timely, proposal-bound evidence or the authority required to finalize an action remains unavailable. We call this mismatch the verification gap and introduce a Post-Semantic Communication Framework for the systems interface between proposal formation and physical execution. The framework begins with application-declared evidence requirements, represents qualifying observations as evidence records, validates supporting and conflicting records through one path,…

---

### [Learning the Right Abstraction: Neural Reduced Dynamics for Complex Robot Control](https://arxiv.org/abs/2608.19375v1)

- **arXiv**: `2608.19375v1`  |  **提交日期**: 2026-08-19
- **作者**: Harry Zhang, Dan Negrut

High-fidelity embodied AI simulators provide realistic evaluation of complex robotic systems, but their computational cost limits their direct use for large-scale reinforcement learning campaigns. We advocate the use of less accurate but more expeditious simulations, which might draw on data-driven, e.g., neural dynamics, models. This contribution argues that the practical value of a neural dynamics model for complex robot control lies in learning the \emph{right abstraction}: a reduced state that preserves the control-relevant physics of the high-fidelity system while enabling…

---

## 📅 2026-08-20

### [Beyond Placement and Articulation: Usage-Driven Code Scenes for Embodied Interaction](https://arxiv.org/abs/2608.18840v1)

- **arXiv**: `2608.18840v1`  |  **提交日期**: 2026-08-19
- **作者**: Zijian Xiao, Zipeng Ye, Jinkun Hao, Xiong Yang, Yuchen Xie, Ran Yi

Indoor scene synthesis provides essential environments for embodied AI, robotic manipulation, and simulation-based policy learning. Recent code-based scene generation methods produce editable and extensible environments, yet they remain focused on visual construction and object-level articulation, leaving the functional usage of scenes largely unmodeled. To address this problem, we present RoomWright, an agentic usage-driven framework for generating 3D scenes represented entirely as code for embodied interaction. RoomWright performs usage-driven object reasoning, which treats each anchor as a…

---

### [CL4D: Contrastive Language-4D Pretraining for Vision-Language Reasoning in Dynamic Scenes](https://arxiv.org/abs/2608.18734v1)

- **arXiv**: `2608.18734v1`  |  **提交日期**: 2026-08-19
- **作者**: Kumal Hewagamage, Isuranga Senavirathne, Sasika Amarasinghe, Hasitha Gallella, Dulanga Weerakoon, Vigneshwaran Subbaraju et al.

4D understanding and reasoning is a fundamental capability for embodied AI agents operating in dynamic physical environments. However, existing vision encoders are largely limited to static 2D images or 3D point clouds without temporal modeling, or to 2D videos that lack accurate geometric depth reasoning. Consequently, current approaches fail to jointly capture spatial structure and motion evolution in dynamic scenes. We present CL4D, the first foundational 4D vision encoder that directly operates on dynamic point clouds, trained with a contrastive learning objective to align spatio-temporal…

---

### [Vision-Language Models for Egocentric Video: From Hand-Object Interaction to Embodied AI](https://arxiv.org/abs/2608.18671v1)

- **arXiv**: `2608.18671v1`  |  **提交日期**: 2026-08-19
- **作者**: Mohammad Zamani, Fatemeh Ziaeetabar

Egocentric video captures activities from the wearer's perspective, providing a direct view of human attention, hand--object interaction, and goal-directed behavior. This perspective is increasingly important for wearable intelligence, assistive systems, human--robot interaction, and embodied AI, yet it introduces challenges including ego-motion, occlusion, small active objects, viewpoint-dependent appearance, and long-range temporal dependencies. Vision--language models (VLMs) offer a promising foundation for addressing these challenges by linking visual observations with semantic knowledge…

---

### [Breaking Planner Integrity Boundary: Enviroment State-Text Injection Attack on LLM-Driven Embodied Agents](https://arxiv.org/abs/2608.16806v2)

- **arXiv**: `2608.16806v2`  |  **提交日期**: 2026-08-17
- **作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan et al.

Large language model (LLM)-driven embodied agents rely on environment states to interpret scenes, generate high-level plans, and drive physical execution, making planner-visible state representations a critical security boundary. Existing attacks primarily manipulate user instructions, prompt contexts, model behavior, or perceptual inputs, while paying limited attention to whether environment-state text itself can serve as deceptive task evidence and propagate beyond planning to affect execution outcomes. Because embodied tasks are constrained by entity grounding, action preconditions,…

---

### [Neurosymbolic Embodied Agents](https://arxiv.org/abs/2608.16794v2)

- **arXiv**: `2608.16794v2`  |  **提交日期**: 2026-08-17
- **作者**: Mohammad Albinhassan, Yuming Feng, Alessandra Russo, Pranava Madhyastha

Language and vision-language models generate plausible embodied plans but do not guarantee executability, as their outputs can violate environment dynamics or act on incorrectly grounded entities. We present a neurosymbolic agent that factors long-horizon household tasks into task-directed visual exploration and constrained symbolic planning. In the first phase, a vision-language model and exploration harness acquire goal-relevant predicates and instance bindings from egocentric observations and grounded interactions, producing a symbolic initial state. In the second, a PDDL transition model…

---

## 📅 2026-08-19

### [Edge-Native Embodied Intelligence for Action-Aware Wireless Edge Networks](https://arxiv.org/abs/2608.17774v1)

- **arXiv**: `2608.17774v1`  |  **提交日期**: 2026-08-18
- **作者**: Yiru Wang, Chuanao Jiang, Jiahui Cui, Zide Fan, Lei Wang, Zehui Xiong et al.

Embodied intelligence is shifting artificial intelligence from passive digital perception toward active physical interaction. However, foundation-model-enabled embodied agents face a fundamental tension between open-world cognition and resource-constrained deployment. On-device models are limited by computation, memory, and energy budgets, whereas cloud-centric solutions introduce latency and reliability risks over dynamic wireless links. Edge general intelligence provides a promising cognitive backbone, but existing frameworks still lack physical grounding, action awareness, and mechanisms…

---

### [GroupForward: Building Referable 3D Scenes via Instance-Grouped Feed-Forward Gaussian Splatting](https://arxiv.org/abs/2608.17535v1)

- **arXiv**: `2608.17535v1`  |  **提交日期**: 2026-08-18
- **作者**: Qijian Tian, Zimeng Wu, Xuhong Wang, Lizhuang Ma, Xin Tan

Simultaneously reconstructing and understanding 3D environments is essential for embodied agents. Toward this goal, feed-forward semantic 3D Gaussian Splatting (3DGS) efficiently constructs semantic scene representations from sparse multi-view observations. However, existing methods lack explicit instance discrimination and mainly support category- or phrase-based semantic queries. To this end, we propose GroupForward, an instance-grouped feed-forward Gaussian splatting model that reconstructs geometry, appearance, instance structure, and semantics from sparse, unposed, and uncalibrated…

---

### [If, Then, Otherwise: Diagnosing Conditional Branching in Vision-Language Navigation](https://arxiv.org/abs/2608.17318v1)

- **arXiv**: `2608.17318v1`  |  **提交日期**: 2026-08-18
- **作者**: Seoyoung Lee, Neel P. Bhatt, Pranay Samineni, Cong Liu, S P Sharan, Timothy Barclay et al.

Vision-language navigation agents are often evaluated on their ability to follow route-like instructions toward a fixed goal. Yet, real navigation instructions often depend on observed states of the environment: if a condition holds, then follow one path, otherwise take another. Such instructions require an agent to evaluate scene evidence, select the correct logical branch, and execute the corresponding navigation behavior. Existing evaluations provide limited control over conditional branch execution, making it difficult to determine whether agents fail because of perception, grounding,…

---

### [The 10th AI City Challenge](https://arxiv.org/abs/2608.17044v1)

- **arXiv**: `2608.17044v1`  |  **提交日期**: 2026-08-17
- **作者**: Zheng Tang, Shuo Wang, David C. Anastasiu, Ming-Ching Chang, Anuj Sharma, Quan Kong et al.

The 10th AI City Challenge, held with ECCV 2026, marks a decade of community benchmarking for intelligent transportation, smart cities, and physical AI. Since its 2017 start with vehicle detection, classification, and tracking, the challenge has grown into a broad benchmark suite for multi-camera perception, multimodal reasoning, synthetic-to-real learning, generative forecasting, and privacy-preserving evaluation. The 2026 edition continued this growth with 325 registered teams, up from 245 in 2025, and participation from 26 countries and regions, up from 15. Its six primary tracks cover…

---

## 📅 2026-08-18

### [Security of Foundation-Model-Powered Embodied Agents: Attack Surfaces, Attacks, Defenses, and Evaluation](https://arxiv.org/abs/2608.16843v1)

- **arXiv**: `2608.16843v1`  |  **提交日期**: 2026-08-17
- **作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan et al.

Foundation models are increasingly used for perception, reasoning, planning, and action generation in embodied agents, creating security risks that can propagate from digital inputs to physical behavior. Existing surveys often organize threats by mechanisms such as jailbreaks, prompt injection, backdoors, poisoning, or adversarial examples, but these categories do not consistently identify where an adversary first enters the embodied control loop. We present a trust-boundary-centric survey of foundation-model-powered embodied-agent security. Using a first-compromised-trust-boundary principle,…

---

### [Neurosymbolic Embodied Agents](https://arxiv.org/abs/2608.16794v1)

- **arXiv**: `2608.16794v1`  |  **提交日期**: 2026-08-17
- **作者**: Mohammad Albinhassan, Yuming Feng, Alessandra Russo, Pranava Madhyastha

Language and vision-language models generate plausible embodied plans but do not guarantee executability, as their outputs can violate environment dynamics or act on incorrectly grounded entities. We present a neurosymbolic agent that factors long-horizon household tasks into task-directed visual exploration and constrained symbolic planning. In the first phase, a vision-language model and exploration harness acquire goal-relevant predicates and instance bindings from egocentric observations and grounded interactions, producing a symbolic initial state. In the second, a PDDL transition model…

---

### [UniTAC: Universal Task-Aware Compression via Weighted Distortion Measures](https://arxiv.org/abs/2608.16696v1)

- **arXiv**: `2608.16696v1`  |  **提交日期**: 2026-08-17
- **作者**: Homa Esfahanizadeh, Matin Mortaheb, Jinfeng Du, Harish Viswanathan

Physical AI systems such as autonomous vehicles and robots rely on timely exchange of high-dimensional sensory signals under tight bandwidth, latency, and energy budgets. Because the task driving downstream decisions evolves over time, a task-specific codec is brittle and retraining one per task is infeasible in the field. We propose UniTAC, a single learned image codec spanning universal (task-agnostic) to task-specialized operation, re-targeted at runtime without retraining. The task is abstracted as a per-component importance vector, derived, e.g., from gradient attribution of any…

---

### [Zetta $ζ$: An Efficient Closed-Loop Embodied Harness for Self-Evolving Physical Intelligence](https://arxiv.org/abs/2608.16590v1)

- **arXiv**: `2608.16590v1`  |  **提交日期**: 2026-08-17
- **作者**: Xin Ding, Liang Mi, Mingzhe Huang, Zixuan Wang, Chao Zhang, Zixu Hao et al.

Embodied agents are increasingly used to close the gap left by end-to-end policy models. Yet the agentic path has not realized closed-loop learning in physical execution: existing harnesses remain largely open-loop, following fixed skills during rollout and reflecting only after an episode completes. Such post-hoc reflection cannot govern execution as it unfolds, because physical interaction requires decisions to track rapidly changing robot-environment states at a frequency beyond today's large agentic models. We present Zetta, a closed-loop embodied harness that evolves code-based runtime…

---

### [Co-design of Neural and Muscle Network based on Embodied Perceptron Representation](https://arxiv.org/abs/2608.16555v1)

- **arXiv**: `2608.16555v1`  |  **提交日期**: 2026-08-17
- **作者**: Siyuan Tao, Yoichi Masuda, Hiroyuki Nabae, Masato Ishikawa

Recent advances in AI technologies have enabled the advanced design of complex control policies. In contrast, focusing on the body, many robots still employ simple bodies that can limit adaptability to environments. Studies in embodied robotics have shown that well-designed bodies can partially replace the role of control and computation with physical body-environment interactions, yet such designs still depend heavily on expert intuition. There is a need for a systematic theoretical framework for body design, as well as a method for joint optimization of the body and controller. To address…

---

### [HiPHI: A Large-Scale Benchmark for High-Precision Human Motion and Object-Interaction](https://arxiv.org/abs/2608.16222v1)

- **arXiv**: `2608.16222v1`  |  **提交日期**: 2026-08-17
- **作者**: Jiahao Ji, Ji Ma, Runhan Zhang, Runyi Yu, Wenjia Wang, Weiheng Chi et al.

Humanoid intelligence requires learning over an extremely diverse space of whole-body motions and physically grounded interactions. However, existing embodied datasets remain fundamentally limited: internet-scale video data lack precise physical states and interaction grounding, while laboratory motion datasets provide high fidelity but only narrow behavioral coverage. This mismatch creates a critical bottleneck for scalable humanoid policy learning. We present HiPHI, a 600+ hour scale high-fidelity whole-body human motion dataset designed to systematically maximize coverage of the human…

---

### [AlloEgo-VLM: Disambiguating Allocentric and Egocentric Reference Frames in Vision-Language Models](https://arxiv.org/abs/2608.15605v1)

- **arXiv**: `2608.15605v1`  |  **提交日期**: 2026-08-16
- **作者**: Kuan-Lin Chen, Tzu-Ti Wei, Chao-Chi Liao, Yu-Chee Tseng, Jen-Jee Chen

This study investigates the challenge of ambiguity faced by Vision-Language Models (VLMs) in understanding spatial semantics. Spatial cognition, shaped by cognitive psychology, spatial science, and cultural context, often assigns directionality to objects. However, natural language descriptions of spatial relations frequently omit explicit reference frames, leading to semantic ambiguity and potentially serious errors for embodied AI robots. Existing VLMs, due to insufficient training on reference frames and object orientations, often produce inconsistent responses. To address this issue, we…

---

### [FloodReasonBench: Benchmarking VLM Reasoning Segmentation for Embodied Flood Response at the Edge](https://arxiv.org/abs/2608.15410v1)

- **arXiv**: `2608.15410v1`  |  **提交日期**: 2026-08-15
- **作者**: Rajat Bhattacharjya, Yoomee Jung, Minwoo Kim, Sing-Yao Wu, Eli Bozorgzadeh, Nalini Venkatasubramanian et al.

Reasoning segmentation enables vision-language models (VLMs) to translate mission-relevant language requests into pixel-level visual grounding, offering a natural perception interface for embodied agents. However, existing benchmarks largely focus on generic visual scenes and overlook the domain and resource constraints encountered in flood-response platforms. We present FloodReasonBench, a benchmark for VLM reasoning segmentation for embodied flood response at the edge. At its core, FloodReasonBench introduces FloodResponseSeg, a flood-specific reasoning-segmentation dataset constructed from…

---

### [Constitutive Priors for Machine Intelligence: A Legitimacy Theory of the Artificial Physical World](https://arxiv.org/abs/2608.15147v1)

- **arXiv**: `2608.15147v1`  |  **提交日期**: 2026-08-15
- **作者**: Jiang Jiang, Yifu Sun, Qi Shen

Machine intelligence has conquered the symbolic world but stalled at the physical one. The stall is structural: physical AI faces a cold-start deadlock -- no intelligence without data, no data without deployed intelligence. Our thesis: the deadlock is real but unevenly distributed, and the exception has a name: the artificial physical world. Buildings, industrial facilities, and infrastructure are intentionally constituted and documented: designed artifacts ship with readable archives that precede and constitute their instances; here, norms are promulgated before instances, not averaged from…

---

## 📅 2026-08-17

### [Rollplex: Cross-Phase GPU Spatial Sharing for Vision Language Model Post-Training](https://arxiv.org/abs/2608.14498v1)

- **arXiv**: `2608.14498v1`  |  **提交日期**: 2026-08-14
- **作者**: Hanfeng Lu, Tianyu Feng, Suyi Li, Yuheng Zhao, Wei Gao, Shaopan Xiong et al.

Vision-language models (VLMs) enable embodied agents to reason and act from visual observations and language instructions. Reinforcement learning (RL) post-training enhances these capabilities using task feedback, but current on-policy RL runtimes execute rollout, reference scoring, and actor training in strict serial phases. While effective for text-only RL, this phase-granular execution is wasteful for VLMs, where processing dense video inputs and prompt prefixes occupies a large fraction of each phase. Because prefix processing is independent of the generated response, it can be run…

---

### [PRM-as-a-Judge 1.5: A Toolkit for Robot Process Assessment](https://arxiv.org/abs/2608.14284v1)

- **arXiv**: `2608.14284v1`  |  **提交日期**: 2026-08-14
- **作者**: Yuyang Liu, Yanqing Shen, Ruike Chen, Jifan Zhao, Yuxuan Tian, Yichi Zhang et al.

Fine-grained robotic evaluation matters for understanding embodied models, going beyond binary success rates and rule-based process scores. We present PRM-as-a-Judge 1.5, a toolkit for robot process assessment that turns rollout videos into dense progress curves and derives multiple fine metrics. PRM-as-a-Judge 1.5 introduces three metrics, building on version 1.0, that characterize failure-side progress, post-drawdown recovery, and success-side execution quality, helping users understand embodied model capability. Based on the rollout videos from benchmarks, we perform a comprehensive…

---

### [Implementing Computational Law in Wolfram Language for the Governance of Artificial Intelligence](https://arxiv.org/abs/2608.13958v1)

- **arXiv**: `2608.13958v1`  |  **提交日期**: 2026-08-14
- **作者**: James K. Wiles

How do we govern AI systems whose reasoning we cannot fully inspect? Governance does not require understanding a system's reasoning. It requires stating what the system is obliged, permitted, and forbidden to do, and checking whether it complied. I present an implementation of Reified Input/Output Logic, the formalism behind the DAPRECO knowledge base, in Wolfram Language: the core I/O axioms, obligations, permissions, constitutive norms, reified eventualities, and temporal operators. I then test whether GPT-4 can translate English legal statements into the formalism, and report the failures:…

---

## 📅 2026-08-14

### [Enhancing Virtual Agents through SLMs and Edge-Computing: An Exploratory Evaluation of Think and Memory Processes](https://arxiv.org/abs/2608.13420v1)

- **arXiv**: `2608.13420v1`  |  **提交日期**: 2026-08-13
- **作者**: Aimilios Hadjiliasi, Louis Nisiotis

Embodied intelligent virtual agents are expected to operate as persistent, adaptive, and context-aware entities within complex virtual and Metaverse worlds. However, implementing cognitively capable agents in such environments is conceptually and technologically challenging. Among a range of blueprints and development approaches, the Cognitive Embodied Agent Architecture (CEAA) has been developed as an implementation-oriented framework for architecting components of perception, memory, reasoning, planning, and embodied action. Considering the recent advances in edge computing and generative…

---

### [Semantic Radiance Fields as Simulators for Spatial Reasoning in Real-World Scenes](https://arxiv.org/abs/2608.13095v1)

- **arXiv**: `2608.13095v1`  |  **提交日期**: 2026-08-13
- **作者**: Nico Heider, Michał Jan Włodarczyk, Katarzyna Wasielewska-Michniewska, Przemysław Hołda, Martin Schieck, Marcin Paprzycki et al.

Training and evaluating spatial reasoning in embodied agents requires diverse environments that are both geometrically faithful and semantically queryable. Synthetic simulators offer ground truth semantics but sacrifice realism; simulators based on reconstructions of real-world environments have realistic appearance but lack ground truth semantics by default. We propose using Semantic Radiance Fields (SRF) as simulators for spatial reasoning agents. SRFs are a representation that unifies these requirements by lifting 2D semantic segmentations from pretrained vision models into a 3D radiance…

---

### [Spatial Memory Agent: Experience-Grounded Procedure Memory for Spatial Intelligence](https://arxiv.org/abs/2608.12743v1)

- **arXiv**: `2608.12743v1`  |  **提交日期**: 2026-08-13
- **作者**: Haokai Zhang, Yuhang Ding, Yunshu Zhou, Xinze Du, Shengtao Zhang, Zhiyue Zhao et al.

Spatial intelligence is becoming a foundation for embodied agents, robotic planning, and multimodal assistants. To improve the spatial reasoning ability of VLM agents, existing work has mainly followed two lines. One line uses post-training methods, such as supervised fine-tuning and reinforcement learning. Another line adopts an agentic paradigm in which the model calls external spatial tools, such as depth estimation and 3D reconstruction tools, to gather intermediate spatial evidence. We study a complementary and underexplored route: Can a frozen VLM agent improve its spatial reasoning…

---

### [FUSE: Active Functional Affordance Grounding through Adaptive Semantic-Geometric Evidence Acquisition](https://arxiv.org/abs/2608.12683v1)

- **arXiv**: `2608.12683v1`  |  **提交日期**: 2026-08-13
- **作者**: Zhou Chen, Sathyanarayanan N. Aakur

Embodied agents must often identify and interact with objects based on their function rather than their identity, requiring them to actively acquire observations that reveal discriminative functional evidence. Existing affordance grounding methods operate from fixed viewpoints and lack mechanisms for deciding where to look when functional cues are occluded or incomplete. We introduce Active Functional Affordance Grounding, a new task in which an agent sequentially explores a scene to identify and spatially ground an object satisfying a functional query. To address this problem, we propose…

---

## 📅 2026-08-13

### [Map-Det3D: Metric Feed-Forward 3D Reconstruction Prior for Multi-view 3D Object Detection from Streaming Inputs](https://arxiv.org/abs/2608.12179v1)

- **arXiv**: `2608.12179v1`  |  **提交日期**: 2026-08-12
- **作者**: Yung-Hsu Yang, Luigi Piccinelli, Samuel Rota Bulò, Sunghwan Hong, Denis Rozumny, Johannes Schönberger et al.

Metric 3D object detection is a core capability for embodied agents, yet most reliable systems lean on depth sensors, trading away cost, power, and integration simplicity. This motivates monocular 3D detection, which avoids additional constraints, yet it faces a major obstacle: from a single image, depth, and especially absolute scale, are underconstrained. As a result, the prevailing pattern of detecting in 2D and then predicting 3D attributes is often brittle, since modest range errors can dominate 3D localization, and the learned scale prior can fail when cameras, motion, or environments…

---

### [HandEdit: A Unified Benchmark for Egocentric Human-to-Robot Dexterous Hand Image Editing](https://arxiv.org/abs/2608.12122v1)

- **arXiv**: `2608.12122v1`  |  **提交日期**: 2026-08-12
- **作者**: Zhenjie Yang, Xingyu Jiao, Guopeng Zhong, Shuzhe Yang, Shi Che, Chao Wu et al.

Robotic manipulation with dexterous hands is a cornerstone of Embodied AI, yet its progress is stifled by the high cost of collecting embodiment-aware teleoperation data. While abundant egocentric videos of human hands offer a scalable alternative, the profound discrepancies in appearance, articulation, and camera viewpoints between human and robotic data raise significant challenges for co-training. Though existing general image-editing models demonstrate strong capabilities, they lack necessary embodiment-specific priors to fully bridge this gap. In this work, we present HandEdit, a unified…

---

### [D3D-GEN: Robot-Aware Domain-Grounded Interactive 3D World Generation for Social Robotics](https://arxiv.org/abs/2608.11876v1)

- **arXiv**: `2608.11876v1`  |  **提交日期**: 2026-08-12
- **作者**: Anh Duc Do, Volodymyr Scherbyna, Tai Duc Nguyen, Spaarsh Thakkar, Zhengcheng Shen, Teham Buiyan et al.

Training and validation of Embodied AI for social navigation critically depends on realistic simulation environments, yet many current approaches fail to find a balance between realism and simulability. We propose D3D-GEN, a novel world generation system that combines a domain agent with a retrieval-augmented generation (RAG) pipeline grounded in that domain. Our system enables users to rapidly generate domain-grounded, fully interactive 3D worlds by automating both the collection of domain knowledge and the synthesis of realistic floorplans and object placements, without dependence on any…

---

### [HUGIN: Enhancing Vision-Language Planning for Autonomous Logistics Sorting](https://arxiv.org/abs/2608.11692v1)

- **arXiv**: `2608.11692v1`  |  **提交日期**: 2026-08-12
- **作者**: Xikai Sun, Cangtian Zhou, Kebin Liu, Ke Ma, Xu Wang, Zaishu Chen et al.

Autonomous logistics sorting systems (ALSS) are an important industrial application of embodied AI, which requires joint planning over spatially disjoint camera views. We formulate this setting as Joint Multi-Scene Understanding (JMSU). With open-world visual understanding and task-planning capabilities, vision-language models (VLMs) are promising candidates for JMSU. However, directly applying existing VLMs to JMSU is non-trivial due to scarce cross-scene supervision and attention dispersion caused by long visual context in JMSU. To address these challenges, we propose HUGIN, a training…

---

### [A Frequency-Space Terahertz Transceiver Chip for Multi-Agent Communications and Spatial Awareness](https://arxiv.org/abs/2608.11651v1)

- **arXiv**: `2608.11651v1`  |  **提交日期**: 2026-08-12
- **作者**: Xiaoyue Xia, Zhicheng Lin, Hao Guo, Siran Wang, Jingyuan Zhang, Xinyu Fang et al.

Future indoor embodied-intelligence systems require scalable hardware platforms that support both high-capacity multi-agent connectivity and mutual spatial awareness. The terahertz (THz) spectrum offers abundant bandwidth and inherent spatial selectivity for integrated sensing and communication (ISAC); however, conventional phased arrays and programmable metasurfaces rely on dense beamforming networks, element-level control, or external THz illumination, making scalable multibeam operation challenging. Here, we report a fully integrated 208-258GHz 65-nm CMOS THz transceiver chip that…

---

### [Self-Evolving Embodied Agents via Skill-Harness Evolution](https://arxiv.org/abs/2608.11350v1)

- **arXiv**: `2608.11350v1`  |  **提交日期**: 2026-08-11
- **作者**: Peidong Wang, Zhiming Ma, Ying Chang, Xufang Luo, Xiaocui Yang, Shi Feng et al.

Embodied agents are increasingly built as systems around foundation models, where performance depends not only on model weights but also on the skills, context, action interfaces, and execution harness surrounding the model. While supervised fine-tuning and reinforcement learning can adapt agents to new environments, they require additional data, rewards, and training runs; meanwhile, many train-free code-centric approaches rely on programmable robot APIs that may be unavailable in fixed-interface settings. We propose SHAPER, a self-evolving framework for train-free embodied adaptation that…

---

## 📅 2026-08-12

### [HUI360: A 360° Egocentric Dataset and Baselines for Human-Robot Interaction Anticipation](https://arxiv.org/abs/2608.11051v1)

- **arXiv**: `2608.11051v1`  |  **提交日期**: 2026-08-11
- **作者**: Raphael Lorenzo-Louis, Fabio Amadio, Bertrand Luvison, Serena Ivaldi

As robots increasingly operate in human-populated environments, anticipating human intentions is essential for enabling proactive and socially aware behavior. Automatic anticipation of human-robot interactions is thus emerging as a crucial perception challenge for embodied agents. To this end, we introduce HUI360, the largest dataset for human-robot interaction anticipation in the wild and its set of baselines. The dataset was collected from a mobile robot, in the wild, over multiple days within a 3-month period, and in several environments, capturing natural, spontaneous behaviors from both…

---

### [Multi-View Relational Distillation for Spatial Reasoning with Vision-Language Models](https://arxiv.org/abs/2608.10864v1)

- **arXiv**: `2608.10864v1`  |  **提交日期**: 2026-08-11
- **作者**: Kiet T. Nguyen, Hanbo Shim, Jinwoo Kim, Seunghoon Hong

Vision-language models (VLMs) have achieved strong image and video understanding, yet their visual-spatial representations remain geometrically fragile, leading to failures in spatial reasoning needed for embodied AI, robotics, and autonomous driving. Prior approaches to geometry grounding either fine-tune VLMs on spatial question answering, which can perpetuate spurious visual representations, or fuse features from large geometry-grounded vision models, which substantially increases model size at inference. Knowledge distillation from geometry-grounded vision models offers an alternative,…

---

### [Chain of Spatial Thoughts: Modality-Agnostic Spatial Grounding for Vision Language Models](https://arxiv.org/abs/2608.10278v1)

- **arXiv**: `2608.10278v1`  |  **提交日期**: 2026-08-10
- **作者**: Hunter Schofield, Mohammed Elmahgiubi, Mohammad Mahdavian, Richard Shi, Jinjun Shan, Amir Rasouli et al.

Spatial understanding is fundamental to embodied intelligence, underpinning applications such as robotic manipulation, embodied navigation, and autonomous driving. Although recent vision-language models (VLMs) have achieved impressive performance on spatial reasoning benchmarks, state-of-the-art approaches typically rely on additional spatial encoders or architectural modifications during inference, increasing computational cost. We introduce Space Tokens, a lightweight, architecture-agnostic framework that equips VLMs with explicit continuous spatial representations without requiring…

---

### [CEAA: A Cognitive Embodied Agents Architecture for Interactive Computing Systems](https://arxiv.org/abs/2608.09848v1)

- **arXiv**: `2608.09848v1`  |  **提交日期**: 2026-08-10
- **作者**: Aimilios Hadjiliasi, Louis Nisiotis

The development of embodied Intelligent Virtual Agents (IVAs) that have cognitive capabilities in real-time interactive virtual environments remains a challenge, even with today's advancements in technology. Existing architectures are often focused on either the implementation of low-level reactive control systems that are constrained by commercial game engines, or high-level representations of reasoning models that can be difficult to implement in virtual worlds. This paper builds on that notion and proposes a modular cognitive architecture for deploying embodied IVAs. This architecture…

---

## 📅 2026-08-11

### [SAIN: Structure-Aware Interactive Navigation with Active Dialogue Grounding for Mobile Robot](https://arxiv.org/abs/2608.09196v1)

- **arXiv**: `2608.09196v1`  |  **提交日期**: 2026-08-10
- **作者**: Yuhao Cao, Xiao Liu, Yang Xie, Lu Liu, Haoyao Chen

Most existing vision-language navigation tasks assume that instructions are complete and unambiguous. However, real-world robots often encounter natural human instructions that are ambiguous, underspecified, or incomplete, requiring them to resolve such uncertainties through active questioning. Interactive Instance Goal Navigation (IIGN) requires an embodied agent to find the specific instance under an ambiguous category-level instruction through active dialogue. However, existing dialogue-enabled methods often consume oracle answers as transient textual context for immediate decisions,…

---

### [360CityArena: A Realistic Virtual Urban Navigation Benchmark for Embodied Agents](https://arxiv.org/abs/2608.08814v1)

- **arXiv**: `2608.08814v1`  |  **提交日期**: 2026-08-09
- **作者**: Kenta Watanabe, Atsuyuki Miyai, Mizuki Takenawa, Kiyoharu Aizawa, Toshihiko Yamasaki

We present 360CityArena, a benchmark for evaluating the urban exploration capabilities of embodied agents within a photorealistic environment constructed from 360-degree videos. Existing outdoor benchmarks either lack sufficient photorealism or complexity, resulting in a considerable gap from real-world urban environments. 360CityArena is built on a realistic reconstruction of the Akihabara district in Tokyo, Japan, using 602 360-degree video segments covering 85 streets, and consists of 175 meticulously human-crafted tasks. It encompasses three task categories: Environment Understanding,…

---

### [Discovering Diverse Planning Policies for Multimodal Embodied Agents with Quality-Diversity Optimization](https://arxiv.org/abs/2608.08523v1)

- **arXiv**: `2608.08523v1`  |  **提交日期**: 2026-08-09
- **作者**: Pengfei Xu, Yong Liu, Xiaoya Nan, Qiang Yang, Peilan Xu

Multimodal embodied agents are increasingly required to solve long-horizon tasks by integrating visual observations, textual goals, and interaction history into closed-loop decision making. However, state-of-the-art large-model-based planners often rely on a single dominant planning style during execution. Once this execution mode becomes ineffective, the agent may remain stalled for many steps, repeatedly interacting with the environment without making meaningful progress. We address this limitation by proposing a Quality-Diversity (QD) framework for discovering diverse planning policies for…

---

### [TrustRoboReward: Preference-Ordered Isotonic Score Editing for Multi-Paradigm Robot Reward Models](https://arxiv.org/abs/2608.08491v1)

- **arXiv**: `2608.08491v1`  |  **提交日期**: 2026-08-09
- **作者**: Yidong Wang, Yan Zhan, Ziteng Feng, Zhenyu Cui, Ziyi Zhou, Renzhao Liang et al.

Reward models are a bottleneck for reinforcement learning in embodied AI. Long-horizon robotic manipulation requires scalable vision feedback beyond handcrafted rewards or task-specific annotations. Existing open-source VLM reward judges like RoboReward adopt simple 1--5 trajectory progress scoring, lacking pairwise preferences for RLHF, DPO and Bradley-Terry frameworks, while failing to optimize video scene understanding. Augmenting RoboReward with pairwise comparison and video-QA supervision causes inconsistency between pairwise preferences and pointwise scores, introducing training noise…

---

### [Action- and Language-Conditioned Video Assessment for Embodied Control](https://arxiv.org/abs/2608.08273v1)

- **arXiv**: `2608.08273v1`  |  **提交日期**: 2026-08-08
- **作者**: Hwanhee Kim, Jaehyun Jang, Seungmin Cha, Hyeonseo Yun, Donghoon Lee, Chang D. Yoo

Vision-based embodied agents executing multi-step natural language instructions require feedback mechanisms that assess task progress over complete trajectories. Conventional approaches based on final-frame matching or continuous embedding similarity may overlook intermediate transitions that are necessary for determining whether an instruction has been completed. We propose ALVA (Action- and Language-Conditioned Video Assessment), a trajectory evaluator that conditions its assessment on visual observations, the executed action sequence, and the natural language instruction. The method uses a…

---

### [Multi-modal Interactive Control of Robotic Arm based on Offline Large Language Models](https://arxiv.org/abs/2608.08183v1)

- **arXiv**: `2608.08183v1`  |  **提交日期**: 2026-08-08
- **作者**: Hanxiao Chen

Large Language Models (LLMs) have significantly revolutionized the modern society with numerous advanced interactions between humans and AI agents, whereas the usage of most large language models including ChatGPT are not friendly open-sourced and must require the users paying a lot for such AI services continuously. Therefore, deploying open-sourced large language models on local servers can be considered as an efficient approach to design and implement creative embodied AI algorithms with lower cost and more stable free usage. Inspired by this ordinary motivation, we originally propose and…

---

### [PhysX-CoT: Structured Physical Reasoning from a Single Image to Simulation-Ready 3D Assets](https://arxiv.org/abs/2608.08053v1)

- **arXiv**: `2608.08053v1`  |  **提交日期**: 2026-08-08
- **作者**: Jie Huang, Xiaohe Li, Jiahao Li, Fangli Mou, Chen Qian, Yuqiang Fang et al.

Simulation-ready 3D assets are central to robotics and embodied AI. Generating them from a single image is usually framed as a vision-language model that emits a serialized asset for a decoder to turn into geometry and physical fields, leaving the image-to-3D reasoning implicit. We argue the limiting factor is this output-centric view: part placement and local shape are entangled in one global-coordinate token stream, and the intermediate physical states are never exposed for supervision, conditioning, or verification. PhysX-CoT instead casts single-image asset generation as an explicit…

---

### [Lingjing: A Simulation Testbed for Multi-Agent Embodied Tasks in Open-Ended Cities](https://arxiv.org/abs/2608.08045v1)

- **arXiv**: `2608.08045v1`  |  **提交日期**: 2026-08-08
- **作者**: Xiaohe Li, Yiru Wang, Junhao Fan, Mingyuan Liu, Jie Huang, Kaixin Zhang et al.

Urban embodied intelligence requires coordination among heterogeneous agents (e.g., UAVs, ground robots, and autonomous vehicles) in dynamic cities. Simulators therefore provide a scalable foundation for developing and evaluating such coordination. Existing platforms nevertheless isolate different embodiments and decouple them from task design and evaluation. We present \textbf{Lingjing}, a simulation platform for heterogeneous multi-agent embodied intelligence in open-ended urban environments. Lingjing reconstructs and renders evolving cities from geographic data, synchronizes multiple…

---

### [Compiling and Benchmarking Task-State Horizons for Embodied Agents](https://arxiv.org/abs/2608.08036v1)

- **arXiv**: `2608.08036v1`  |  **提交日期**: 2026-08-08
- **作者**: Meiqi Wang, Shichao Li

Frontier agentic models are increasingly deployed as high-level planners for long-horizon embodied tasks. Existing robotic benchmarks have advanced long-horizon evaluation, but primarily characterize difficulty through action-sequence length and subtask complexity, overlooking a distinct challenge: agents must track evolving task-relevant world states induced by both their exploration and environmental dynamics. We define the span of task-relevant state transitions that an agent must track as task-state horizon (TSH). To evaluate how agent performance varies with TSH, we introduce RoboGraph,…

---

### [GraphThink: Graph-Enhanced LLM Thinking for Long-Horizon Embodied Task Planning](https://arxiv.org/abs/2608.07905v1)

- **arXiv**: `2608.07905v1`  |  **提交日期**: 2026-08-08
- **作者**: Chen Li, Sijie Cheng, Yuelin Zhang, Junxi Li, Maozhi Huang, Yang Liu et al.

Embodied agents using LLM-based planners often struggle with physical hallucinations, poor generalization to long-horizon tasks, and lack of environmental awareness. We propose GraphThink, a novel framework that integrates a task graph to provide structured knowledge for robust planning and a scene graph to maintain environmental memory for event-driven replanning. Specifically, the task graph guides LLM thinking through contextual prompting and iterative refinement, effectively mitigating planning hallucinations. Furthermore, within the GRPO framework, the task graph offers delicate reward…

---

## 📅 2026-08-10

### [Representation Handoffs for OpenArm-Based Laboratory Mobile Manipulation](https://arxiv.org/abs/2608.07154v1)

- **arXiv**: `2608.07154v1`  |  **提交日期**: 2026-08-07
- **作者**: Yang Shen, Chonghao Cheng, Ziyi Zhao, Jialuo Zhu, Zhenyi Yi, Qi Zhao et al.

Open-source robotics and foundation models have lowered the barrier to embodied AI, yet language-guided laboratory automation still requires reliable alignment from instructions and observations to safe actions. This field report presents an OpenArm-based mobile manipulation prototype for laboratory-style tasks, built by integrating dual OpenArm manipulators with a mobile base, vertical slide, RGB-D sensing, lidar-based mapping, ROS2/MoveIt execution, and profile-defined skill interfaces. The system is organized around representation handoffs: natural language requests are constrained into…

---

### [Unordered Landmark Visual Navigation](https://arxiv.org/abs/2608.06833v1)

- **arXiv**: `2608.06833v1`  |  **提交日期**: 2026-08-07
- **作者**: Hao Ren, Junzhe Zhu, Yihan Li, Zetong Bi, Le Zheng, Zhi Li et al.

Image-goal navigation is a fundamental capability for embodied AI, yet its practical deployment is strained by strong prior assumptions. Existing methods predominantly rely on temporally ordered video streams or auxiliary sensors (e.g., depth, LiDAR) to maintain spatial consistency. These sequential and multimodal dependencies severely restrict scalability, especially when deploying robots using crowd-sourced or pre-recorded unordered image collections. When temporal priors are removed, current methods struggle with severe perceptual aliasing, noisy associations, and catastrophic mapping…

---

### [Capek 0.5: An Execution-Centric Vision-Language Model for Embodied Intelligence](https://arxiv.org/abs/2608.06756v1)

- **arXiv**: `2608.06756v1`  |  **提交日期**: 2026-08-07
- **作者**: Ying Chen, Weizhen Li, Zhe Hu, Zhenjiang Li, Rui Jiang, Zhifeng Gu et al.

Vision-language models are increasingly serving as the reasoning core of embodied agents. Robot execution is inherently iterative: each action reshapes the scene and physical state, continually renewing what must be perceived, reasoned about, and verified. Meeting these demands requires complementary capabilities that differ in supervision signals, prediction formats, and verification criteria. Existing approaches typically develop these capabilities against isolated, task-specific objectives, leaving open how they should be organized and integrated around execution as a whole. We present…

---

## 📅 2026-08-07

### [iARCS: Iterative Agentic RL for Controllable 3D Scene Generation](https://arxiv.org/abs/2608.06161v1)

- **arXiv**: `2608.06161v1`  |  **提交日期**: 2026-08-06
- **作者**: Saugat Adhikari, Ashok Prasad Neupane, Pramish Paudel, Ajad Chhatkuli, Danda Pani Paudel

Synthetic 3D scene generation is increasingly used as a data source for computer vision and embodied AI, but existing generators often optimize perceptual realism without reliably satisfying task-critical functional constraints. This mismatch limits the usefulness of synthetic data for downstream training, where accessibility, traversability, and spatial rule compliance are often essential. We present iARCS, an iterative agentic reinforcement learning framework that adapts a pretrained scene generator to natural-language task requirements. iARCS uses a two-stage strategy: universal-reward…

---

### [IcFuzz: Fuzzing Isaac Sim with Semantic Stage Guidance and Multi-level Mutation](https://arxiv.org/abs/2608.06088v1)

- **arXiv**: `2608.06088v1`  |  **提交日期**: 2026-08-06
- **作者**: Zhixiang Chen, Zhuangbin Chen, Ruoxi Jia, Zeqin Liao, Wei Li, Jinyang Liu et al.

Robotics simulators serve as a foundational infrastructure for embodied AI, facilitating safe and scalable robotic system development. NVIDIA Isaac Sim has emerged as one of the most popular simulators, distinguished by its GPU-accelerated physics engine and photorealistic rendering, which enable high-fidelity modeling of complex environments. However, its inherent complexity inevitably introduces software bugs that can compromise simulation reliability. Existing fuzzing approaches struggle to test Isaac Sim effectively due to challenges of context-aware object semantics, hierarchical…

---

### [GST-Bench: Can VLMs Develop Global Spatial Awareness from Video?](https://arxiv.org/abs/2608.05747v1)

- **arXiv**: `2608.05747v1`  |  **提交日期**: 2026-08-06
- **作者**: Qifeng Zhang, Kaixiang Huang, Heng Dong, Huang Fang, Junting Chen, Junjie Zhu et al.

Spatial intelligence is fundamental to embodied agents, yet existing benchmarks focus on local spatial perception from single or few viewpoints, overlooking global spatial awareness over continuous, long-horizon visual streams. To address this limitation, we introduce the Global-Spatial-Temporal Benchmark (GST-Bench), a VQA benchmark for global spatial intelligence in video understanding, comprising human-verified questions derived from 6,790 minutes of synthetically generated video. It requires models to perform accurate spatial inference from novel viewpoints unseen in the input video and…

---

### [SkillZip: Contract-Preserving Graph Compression for Scalable Agent Skill Libraries](https://arxiv.org/abs/2608.05604v1)

- **arXiv**: `2608.05604v1`  |  **提交日期**: 2026-08-06
- **作者**: Xingyu Tan, Xiaoyang Wang, Qing Liu, Xiwei Xu, Xin Yuan, Liming Zhu et al.

Large Language Models (LLMs) increasingly act as agents whose procedural knowledge is stored in reusable skill packages and loaded at inference time. As skill libraries grow, a central challenge is to expose the smallest sufficient executable context under a limited context budget. Existing systems struggle to reuse routines below the whole-skill level, preserve procedural contracts during compression, keep compressed routines executable and expandable, and update the compressed library as skills evolve. These challenges reveal a unit mismatch: skills are retrieved as packages, compressed as…

---

## 📅 2026-08-06

### [SmartMage: Dynamic Modality Orchestration for 3D Scene Understanding](https://arxiv.org/abs/2608.05137v1)

- **arXiv**: `2608.05137v1`  |  **提交日期**: 2026-08-05
- **作者**: Yue Zhang, Yingzhao Jian, Yunqiu Xu, Xiaoxiao Sun, Hehe Fan

Understanding 3D scenes is fundamental to embodied intelligence, requiring joint reasoning over heterogeneous information from multiple modalities, including visual and geometric cues. However, the relevance of these modalities often varies across queries. Existing Multimodal Large Language Models (MLLMs) typically rely on fixed modality combinations, overlooking query-dependent modality needs. Such a rigid design can introduce semantic noise from irrelevant modalities while underutilizing more informative ones, leading to wasted computation and diluted reasoning. To address these challenges,…

---

### [Mimir: A Neuro-Symbolic Memory System with Dynamic Grounding for Embodied Agents in Interactive Environments](https://arxiv.org/abs/2608.04933v1)

- **arXiv**: `2608.04933v1`  |  **提交日期**: 2026-08-05
- **作者**: Haoming Xu, Zhenlin He, Hengyi Wang, Jiafeng Xu, Hao Dong

Long-horizon embodied task requires agents to act under partial observability while preserving both scene belief and execution progress. Flat histories or implicit policy states may contain past observations, but they do not provide an explicit interface for deciding which world facts support the currently active goal. We introduce Mimir, a neuro-symbolic memory that separates world memory from task memory and dynamically grounds them before each action. World memory maintains object locations, object states, and perceptual evidence, while task memory maintains an ordered goal agenda,…

---

### [Talk2Sensors: 3D Visual Grounding in Autonomous Driving via Sensor-Adaptive Physical Cue Matching](https://arxiv.org/abs/2608.04568v1)

- **arXiv**: `2608.04568v1`  |  **提交日期**: 2026-08-05
- **作者**: Runwei Guan, Di Tian, Ningwei Ouyang, Ruixiao Zhang, Shaofeng Liang, Haocheng Zhao et al.

As a key capability for embodied intelligence, 3D visual grounding (3DVG) has been predominantly studied in indoor scenes with RGB-D or point-cloud inputs, while existing outdoor extensions largely rely on monocular images alone. Both settings fall short of real-world outdoor perception, where heterogeneous sensors capture complementary yet distinct physical properties, such as visual texture, 3D geometry, and object kinematics, that are indispensable for flexible and robust query-adaptive grounding but remain under-exploited. To bridge this gap, we introduce Talk2Sensors, the first…

---

## 📅 2026-08-05

### [LiteMVS: Efficient Multi-View Stereo with Foundation Distillation and Expert Aggregation](https://arxiv.org/abs/2608.03851v1)

- **arXiv**: `2608.03851v1`  |  **提交日期**: 2026-08-04
- **作者**: Tianbao Zhang, Zeyu Liu, Shuyu Wu, Fanxing Li, Zhaoxin Fan, Wenjun Wu et al.

Real-time 3D perception is crucial for robotics, augmented reality, and embodied intelligence applications. Existing multi-view stereo (MVS) methods primarily rely on geometric correspondences, which often fail in textureless or repetitive regions, while monocular depth models leverage strong image-level priors but lack robust multi-view geometric constraints. More importantly, in robotics and embodied manipulation scenarios, high-quality 3D geometry is not only essential for static reconstruction, but also serves as a critical foundation for learning temporally consistent 4D representations.…

---

### [Human Centric Embodied Intelligence for Soft Wearable Robotics](https://arxiv.org/abs/2608.03556v1)

- **arXiv**: `2608.03556v1`  |  **提交日期**: 2026-08-04
- **作者**: Rainier Natividad, Raye Chen-Hua Yeow

Soft wearable robots have evolved rapidly from proof-of-concept devices into promising platforms for rehabilitation, occupational assistance, and human augmentation. As the field matures, its central challenge extends beyond the development of softer materials and more capable actuators to the integration of sensing, intelligence, and human adaptation into systems that users can wear comfortably, trust, and benefit from over extended periods. This transition motivates the concept of Human-Centric Embodied Intelligence (HCEI), in which intelligence emerges from the coupled human-robot system…

---

### [Principles of Robot Autonomy](https://arxiv.org/abs/2608.03496v1)

- **arXiv**: `2608.03496v1`  |  **提交日期**: 2026-08-04
- **作者**: Daniele Gammelli, Joseph Lorenzetti, Katie Luo, Gioele Zardini, Marco Pavone

Autonomous robots are moving rapidly from research labs into everyday life - on roads, in the air, in warehouses, and in space. Robot autonomy is no longer solely an academic pursuit, but a collection of mature, field-tested methods and tools that practitioners rely on in real-world deployments. This book offers a clear, unified introduction to the methods that make this possible. Built on decades of teaching at Stanford, the text develops the core elements of modern autonomy stacks within a single conceptual framework, bridging classical robotics and modern physical AI. Every major topic is…

---

## 📅 2026-08-04

### [DerainSplat: Feed-Forward Clean 3D Gaussian Splatting from Sparse Rainy Views](https://arxiv.org/abs/2608.02191v1)

- **arXiv**: `2608.02191v1`  |  **提交日期**: 2026-08-03
- **作者**: Fuzhen Jiang, Changyue Shi, Chuxiao Yang, Xinyuan Hu, Wenjie Ye, Minghao Chen

Although image deraining has advanced substantially, existing methods mainly focus on 2D image restoration. As spatial intelligence applications such as embodied AI and autonomous driving continue to emerge, reconstructing clean 3D scenes from sparse rainy views in a feed-forward manner becomes increasingly important. Existing feed-forward 3D Gaussian Splatting (3DGS) methods often assume clean inputs and collapse under rainy conditions. To this end, we present \textbf{\textit{DerainSplat}}, a feed-forward framework that reconstructs clean 3D scenes from only a few rainy views. To support…

---

### [When Replanning Becomes the Bottleneck: Budgeted Replanning for Embodied Agents](https://arxiv.org/abs/2608.01428v1)

- **arXiv**: `2608.01428v1`  |  **提交日期**: 2026-08-02
- **作者**: Shuaijun Liu, Feiyang You, Xingwei Chen, Ningxin Su

Embodied agents replan frequently to recover from execution drift, partial observability, and coordination hazards, but each LLM-based replanning call can consume an accumulated textual context that grows over time and across agents. Once this context becomes large, replanning latency develops heavy tails and can miss real-time deadlines even when task success remains high, a failure mode that is hard to detect from average latency or success alone. We present BRACE, a controller that formulates replanning as a budgeted control loop by deciding whether to replan, selecting a replanning mode,…

---

### [InteracVid: Building a Real Interactive Audio-Visual Response Dataset from Live-Chat Videos](https://arxiv.org/abs/2608.01157v1)

- **arXiv**: `2608.01157v1`  |  **提交日期**: 2026-08-02
- **作者**: Chi Zhang, Haoyang Shi, Yueyi Liu, Zhaokun Yan, Yishu Yin, Yuhang Wu et al.

Large language models have made text the default medium for human--AI interaction, buttext alone cannot express the full range of responses required by multimodal assistants,avatars, and embodied agents. While recent audio-video generative models can synthesizehigh-fidelity synchronized content, existing supervision is largely \emph{descriptive}:models are trained to render captions rather than to produce audio-visual responsescaused by external user interactions. We introduce \textbf{InteracVid}, \emph{the firstopen-source large-scale dataset that addresses this missing supervision}, so that…

---

## 📅 2026-07-14

### [AdvNav: Behavior-Guided Black-Box Adversarial Attacks on Vision-Language Navigation](https://arxiv.org/abs/2607.11063v1)

- **arXiv**: `2607.11063v1`  |  **提交日期**: 2026-07-13
- **作者**: Chenyang Li, Kaige Li, Zeyu Jiang, Changhao Chen

Despite progress in Embodied AI, Vision-and-Language Navigation systems remain vulnerable to adversarial visual disturbances. Most existing methods rely on white-box access to target model gradients, which is often unrealistic for real-world deployed systems and computationally exhaustive due to recursive backpropagation for optimization, limiting their applicability. While previous black-box methods predominantly target single-step, instantaneous decision tasks, they struggle to handle the task complexities and temporal dependencies. This highlights the need for a gradient-free attack method…

---

### [Edge Physical AI Deployment of Vision Transformers on Heterogeneous Edge GPU Targeting Autonomous Vehicles](https://arxiv.org/abs/2607.10942v1)

- **arXiv**: `2607.10942v1`  |  **提交日期**: 2026-07-12
- **作者**: Ashiyana Abdul Majeed, Mahmoud Meribout, Neethu Joseph, Abel Kidane Haile, Mohammad Abdullah Al Faruque

Physical AI systems, such as autonomous vehicles and intelligent machines, require transformer-based perception models that satisfy stringent edge latency and energy constraints. However, heterogeneous edge-GPU deployment remains limited by underutilized hardware engines and accelerator-incompatible operators, causing fragmented execution and lower throughput per watt. This paper presents Heterogeneous Frame Dispatch Scheduling (H-FraDS), a hardware-aware frame scheduling methodology for transformer inference on a recent NVIDIA edge GPU. H-FraDS routes frames across the GPU and dual deep…

---

### [Distributed Agent System: Fault-Tolerant Collaboration Among Embodied Agents](https://arxiv.org/abs/2607.10811v1)

- **arXiv**: `2607.10811v1`  |  **提交日期**: 2026-07-12
- **作者**: Kai Yu, Lu Chen, Hanqi Li

AI engineering is shifting from passive text generation by large language models (LLMs) to agent-driven task execution, creating new reliability challenges for long-horizon tasks under resource constraints and environmental uncertainty. Conventional error-elimination optimization strategies fail to address cumulative error propagation. This paper proposes Distributed Agent System (DAS), a device-edge-cloud framework for fault-tolerant collaboration among heterogeneous agents. We redefine agent reliability as system-level fault tolerance rather than single-turn zero-error accuracy, and present…

---

### [Traj-VLN: Learning Pixel-Space Interaction via Autoregressive Trajectory Generation](https://arxiv.org/abs/2607.10744v1)

- **arXiv**: `2607.10744v1`  |  **提交日期**: 2026-07-12
- **作者**: Changfei Fu, Guangcheng Chen, Wenjun Xu, Hong Zhang

Benefiting from the powerful priors embedded in large-scale pre-training data and the emerging commonsense reasoning ability, large language models (LLMs) have shown unprecedented generalization capabilities in many research fields. Recently, projecting visual embeddings into the language space via vision-language models (VLMs) to achieve sim-toreal and cross-scene generalization has become a prevailing paradigm in the field of Vision-and-Language Navigation in Continuous Environments (VLN-CE). VLN requires an embodied agent to navigate through unseen environments following natural linguistic…

---

### [ABot-AgentOS: A General Robotic Agent OS with Lifelong Multi-modal Memory](https://arxiv.org/abs/2607.10350v1)

- **arXiv**: `2607.10350v1`  |  **提交日期**: 2026-07-11
- **作者**: Jiayi Tian, Shiao Liu, Yuting Xu, Jia Lu, Zihao Guan, Honglin Han et al.

Recent VLM and VLA systems have improved robotic perception and action prediction, yet long-horizon embodied agents still require a general runtime layer for reasoning, memory, tool use, verification, and cross-embodiment execution. We present ABot-AgentOS, a general robotic Agent Operating System that sits above low-level controllers and provides a deliberative agent layer for scene-conditioned planning, context-isolated skill execution, multi-stage verification, multi-modal memory, and edge-cloud collaboration. To evaluate such systems, we introduce EmbodiedWorldBench, an executable…

---

## 📅 2026-07-13

### [Seeing is Free, Speaking is Not: Uncovering the True Energy Bottleneck in Edge VLM Inference](https://arxiv.org/abs/2607.09520v1)

- **arXiv**: `2607.09520v1`  |  **提交日期**: 2026-07-10
- **作者**: Junfei Zhan, Haoxun Shen, Mingang Guo, Zixuan Huang, Tengjiao He

Vision-Language Models (VLMs) are the perceptual backbone of embodied AI, but their energy footprint on edge hardware remains poorly understood. Existing efficiency efforts focus predominantly on reducing visual tokens, implicitly treating visual processing as the dominant energy cost. We overturn this implicit assumption through the first systematic energy profiling of on-device VLM inference, spanning five models across three architecture families, four input resolutions, and two hardware platforms (NVIDIA RTX 3070 and Jetson Orin NX). Our analysis yields three findings. First, average…

---

### [Communication-Efficient Digital-Twin Coordination for Heterogeneous LLM Embodied Agents over Computing Power Networks](https://arxiv.org/abs/2607.09330v1)

- **arXiv**: `2607.09330v1`  |  **提交日期**: 2026-07-10
- **作者**: Nuocheng Yang, Sihua Wang, Zihan Chen, Tony Q. S. Quek, Changchuan Yin

Embodied agent teams powered by heterogeneous large language models (LLMs) are being widely deployed in physical artificial intelligence such as smart factories, warehouses, and service robotics. To enable collaboration among such an agent team, efficient coordination mechanisms that operate reliably under limited network resources are required. However, existing heterogeneous LLM-agent coordination frameworks that rely on multi-round natural-language-based conversations introduce three coupled challenges. First, inter-agent dialogue incurs communication overhead that grows rapidly with team…

---

## 📅 2026-07-10

### [Early to Share, Late to Save: Synchronisation-Driven Communication Gating in Bandwidth-Constrained Cooperative VLN](https://arxiv.org/abs/2607.08504v1)

- **arXiv**: `2607.08504v1`  |  **提交日期**: 2026-07-09
- **作者**: Arav Gupta, Nivedan Yakolli, Avinash Gautam

Most cooperative Vision-Language Navigation (VLN) methods assume unlimited communication, not considering real-world applications where bandwidth is restricted and information efficiency is critical. We introduce \textbf{bandwidth-constrained cooperative VLN} and propose \textbf{hindsight gating}: a lightweight supervised gate that labels communication-critical steps post-hoc from navigation failures, avoiding the high variance of REINFORCE. Contrary to the intuition that agents should communicate when uncertain, we observe a consistent counter-intuitive pattern: trained gates fire…

---

### [GIRAF: Towards Generalizable Human Interactions with Articulated Objects](https://arxiv.org/abs/2607.07880v1)

- **arXiv**: `2607.07880v1`  |  **提交日期**: 2026-07-08
- **作者**: Xiaohan Zhang, Sebastian Starke, Alexander Winkler, Federica Bogo, Samir Aroudj, Yuting Ye

Synthesizing realistic full-body human interactions with articulated objects is a fundamental challenge for embodied AI and graphics, with applications in robotics training and virtual agents. Existing models remain limited: some focus on simple activities with static objects, while others restrict attention to hand-only manipulation. This leaves open the problem of generating coordinated full-body motion that approaches, manipulates, and moves articulated objects in a realistic and generalizable way. The key difficulty lies in reasoning jointly about locomotion, fine-grained contact, and…

---

## 📅 2026-07-09

### [Scaling Mixture-of-Experts Video Pretraining for Embodied Intelligence](https://arxiv.org/abs/2607.07675v1)

- **arXiv**: `2607.07675v1`  |  **提交日期**: 2026-07-08
- **作者**: Shuailei Ma, Jiaqi Liao, Xinyang Wang, Jingjing Wang, Chaoran Feng, Zijing Hu et al.

Despite the recent promise in robot control, video generative models suffer from a domain mismatch due to their primary focus on content creation. For example, their design inherently prioritizes visual fidelity and creativity over computational efficiency and physical realism. In this work, we present LingBot-Video, a DiT-based video pretraining paradigm specifically tailored for embodied intelligence. From the architecture perspective, we adopt the Mixture-of-Experts (MoE), instead of dense, framework to achieve a better trade-off between modeling capacity and inference efficiency, and…

---

### [EmbodiedGen V2: An Agentic, Simulation-Ready 3D World Engine for Embodied AI](https://arxiv.org/abs/2607.07459v1)

- **arXiv**: `2607.07459v1`  |  **提交日期**: 2026-07-08
- **作者**: Xinjie Wang, Liu Liu, Taojun Ding, Andrew Choi, Chaodong Huang, Mengao Zhao et al.

We present EmbodiedGen V2, a generative 3D world engine for building executable sim-ready environments for embodied intelligence. Sim-ready 3D asset generation has advanced rapidly, yet assembling such assets into policy-ready task environments remains largely manual, limiting scalable closed-loop learning. EmbodiedGen V2 addresses this gap through a unified sim-ready representation that connects cross-simulator assets, interaction affordances, task-driven worlds, large-scale multi-room scenes, and stateful Vibe Coding into a generative, editable, and reusable simulation pipeline. The…

---

### [Ego-Human Motion Prediction with 3D-Aware LLM](https://arxiv.org/abs/2607.07001v1)

- **arXiv**: `2607.07001v1`  |  **提交日期**: 2026-07-08
- **作者**: Yujin Bae, Jaewoo Jeong, Hyeonseong Kim, Kuk-Jin Yoon

Anticipating human motion from an egocentric perspective is fundamental for proactive assistance in AR/VR, human-robot collaboration, and embodied AI. While recent works incorporate language as a semantic prior to reduce the ill-posed nature of egocentric forecasting, they largely neglect the 3D spatial and semantic context that governs how motion unfolds, and treat pose and language prediction as separate inference streams. We introduce Ego3DLM, built on two core principles: accurate motion forecasting requires explicit spatial and semantic understanding of the 3D environment, and pose and…

---

### [WildCity: A Real-World City-Scale Testbed for Rendering, Simulation, and Spatial Intelligence](https://arxiv.org/abs/2607.06838v1)

- **arXiv**: `2607.06838v1`  |  **提交日期**: 2026-07-07
- **作者**: Xiangyu Han, Mengyu Yang, Jiaqi Li, Bowen Chang, Ziyu Chen, Hexu Zhao et al.

Humans can navigate an unfamiliar city and gradually form a coherent spatial mental map spanning tens of square kilometers. Can AI build spatial representations at a comparable scale? Although recent foundation models have advanced scene reconstruction and embodied intelligence, scaling to entire cities remains an open challenge, primarily due to the lack of city-scale data. To bridge the gap, we introduce WildCity, a real-world multimodal dataset collected by autonomous fleets traversing complex urban environments. Our dataset includes 18 trajectories, each averaging 83.7 kilometers in…

---

### [SPEAR: A Simulator for Photorealistic Embodied AI Research](https://arxiv.org/abs/2607.06701v1)

- **arXiv**: `2607.06701v1`  |  **提交日期**: 2026-07-07
- **作者**: Mike Roberts, Renhan Wang, Rushikesh Zawar, Rachith Dey-Prakash, Quentin Leboutet, Stephan R. Richter et al.

Interactive simulators have become powerful tools for training embodied agents and generating synthetic visual data, but existing photorealistic simulators suffer from limited generality, programmability, and rendering speed. We address these limitations by introducing SPEAR: A Simulator for Photorealistic Embodied AI Research. At its core, SPEAR is a Python library that can connect to, and programmatically control, any Unreal Engine (UE) application via a modular plugin architecture. SPEAR exposes over 14K unique UE functions to Python, representing an order-of-magnitude increase in…

---

## 📅 2026-07-07

### [ACE-Brain-0.5: A Unified Embodied Foundational Model for Physical Agentic AI](https://arxiv.org/abs/2607.04426v1)

- **arXiv**: `2607.04426v1`  |  **提交日期**: 2026-07-05
- **作者**: ACE-Brain Team,  :, Ziyang Gong, Haoming Gu, Zehang Luo, Tianyi Zhang et al.

Embodied AI is moving from isolated perception or action modules toward physical agents that understand, plan under goals, act through robot bodies, monitor progress, and improve from experience. Existing systems address this loop only in parts: end-to-end policies generate actions but often lack spatial reasoning, planning, and execution assessment, while robot-agent systems orchestrate tools or specialists but do not learn a shared representation. This fragmentation limits general Physical Agentic AI. We present ACE-Brain-0.5, a unified embodied foundation model that organizes robot…

---

### [WSA$_1$: a 3D-Centric World-Spatial-Action Model for Generalizable Robot Control](https://arxiv.org/abs/2607.03941v1)

- **arXiv**: `2607.03941v1`  |  **提交日期**: 2026-07-04
- **作者**: Jiahao Jiang, Jianing Zhang, Zhenhan Yin, Ruidong Chen, Sen Wang, Zhaoshu Yu et al.

Recent advances in embodied AI have established robot foundation models (RFMs) as the dominant approach for generalist robotic systems to date. By leveraging imitation learning on extensive robot demonstrations, RFMs have achieved impressive capabilities in mapping visual observations and language instructions to continuous robotic actions. However, current RFMs lack an inherent ability to reason about physical dynamics and the causal effects of robot behaviors on the 3D physical world. This creates a fundamental mismatch between 2D-centric visual perception and 3D-centric embodied…

---

### [ObjRetarget: An Object-Aware Motion Retargeting Framework with Anthropomorphic Arm Constraints and Polyhedral Hand Modeling](https://arxiv.org/abs/2607.03828v1)

- **arXiv**: `2607.03828v1`  |  **提交日期**: 2026-07-04
- **作者**: Yuanchuan Lai, Qing Gao, Ziyan Liang, Junjie Hu, Zhaojie Ju

Learning robot dexterous manipulation from human manipulation videos requires reliably retargeting human intent to executable robot actions while maintaining stable hand-object contact, which remains a key challenge in embodied intelligence. Existing retargeting methods often ignore explicit contact modeling or rely on reinforcement learning, resulting in limited accuracy and generalization. To address this, we propose ObjRetarget, a human-to-robot motion retargeting framework for learning robot dexterous manipulation from human videos, which integrates anthropomorphic arm trajectory…

---

## 📅 2026-07-03

### [Seek to Segment: Active Perception for Panoramic Referring Segmentation](https://arxiv.org/abs/2607.02497v1)

- **arXiv**: `2607.02497v1`  |  **提交日期**: 2026-07-02
- **作者**: Song Tang, Shuming Hu, Xincheng Shuai, Henghui Ding, Yu-Gang Jiang

Existing referring segmentation models passively process static images captured from fixed perspectives, limiting their applicability in Embodied AI, where agents must perform active perception in the continuous 360$^\circ$ environments. To bridge this gap, we introduce a novel task: Active Panoramic Referring Segmentation (APRS). In this setting, an agent is required to adjust its viewing direction ($Δθ, Δφ$) to explore the 360$^\circ$ environment, seeking the object specified by a user instruction for segmentation. To tackle this challenging task, we propose PanoSeeker, a memory-augmented…

---

### [Learning to Evolve Scenes: Reasoning about Human Activities with Scene Graphs](https://arxiv.org/abs/2607.02425v1)

- **arXiv**: `2607.02425v1`  |  **提交日期**: 2026-07-02
- **作者**: Francesca Pistilli, Simone Alberto Peirone, Giuseppe Averta

Understanding human behavior while interacting with the surrounding world is crucial for many applications of embodied AI. First-person videos are particularly informative for this problem, as they well capture how activities reshape the scene over time. However, existing approaches often rely on implicit visual or language-aligned representations, disregarding structured reasoning over the scene dynamic. We argue that explicit, compositional and editable representations of human-environment interactions can play a crucial role for rich grounded activity understanding. To this end, we…

---

### [ComplexMimic: Human-Scene Interaction Imitation in Complex 3D Environments](https://arxiv.org/abs/2607.02034v1)

- **arXiv**: `2607.02034v1`  |  **提交日期**: 2026-07-02
- **作者**: Lu Pan, Hongwei Zhao

Physics-based Human-Scene Interaction (HSI) imitation learning is crucial for embodied intelligence as it bridges the gap between kinematic 3D motions and real-world dynamics. However, most existing methods focus on simplified scene settings, leaving complex environments largely unexplored, which limits their applicability in real-world scenarios. In this paper, we focus on HSI mimicry in complex environments. Under this complex setting, we observe an inherent trade-off between successfully performing interaction and maintaining natural, physically plausible motions. To address this…

---

### [SimWorlds: A Multi-Agent System for Dynamic 3D Scene Creation](https://arxiv.org/abs/2607.01766v1)

- **arXiv**: `2607.01766v1`  |  **提交日期**: 2026-07-02
- **作者**: Chunjiang Liu, Xiaoyuan Wang, Haoyu Chen, Yizhou Zhao, Ming-Hsuan Yang, László A. Jeni

LLM agents are increasingly used to translate natural language into 3D scenes in a procedural way, but existing systems focus on static output. Dynamic 4D scenes from text alone, in which liquids flow, particles emit, rigid bodies cascade, and articulated mechanisms move, remain largely unexplored despite their value as editable content and as physics-grounded training data for video generation and embodied AI. Two challenges set the dynamic case apart from static text-to-scene work: an agent must jointly coordinate spatial layout, multiple physics solvers, temporal sequencing, camera, and…

---

### [Path-level Hindsight Instructions for Semantic Exploration in Vision-Language Navigation](https://arxiv.org/abs/2607.01754v1)

- **arXiv**: `2607.01754v1`  |  **提交日期**: 2026-07-02
- **作者**: Sung June Kim, Sangpil Kim, Honglak Lee

On-policy exploration is a crucial component for training robust Vision-Language Navigation agents, as it exposes the policy to a broader state distribution. However, such exploration inevitably leads to trajectories that deviate from expert demonstrations, resulting in a semantic mismatch between the executed visual stream and the original language instruction. In this work, we address this challenge by introducing Phi-Nav, a unified on-policy framework that leverages hindsight reasoning to align instructions with the agent's actual exploratory journey. Specifically, Phi-Nav operates through…

---

## 📅 2026-07-02

### [EgoSafetyBench: A Diagnostic Egocentric Video Benchmark for Evaluating Embodied VLMs as Runtime Safety Guards](https://arxiv.org/abs/2607.00218v1)

- **arXiv**: `2607.00218v1`  |  **提交日期**: 2026-06-30
- **作者**: Siddhant Panpatil, Arth Singh, Mijin Koo, Chaeyun Kim, Haon Park, Dasol Choi

Vision-language models (VLMs) are now proposed as runtime safety guards for embodied agents in homes and factories. A deployable guard must catch genuinely unsafe situations while avoiding unnecessary intervention on routine but superficially alarming activity, a distinction that binary safety benchmarks obscure. We introduce EgoSafetyBench, an egocentric video benchmark of 1,200 robot-view scenarios annotated at half-second granularity, to evaluate VLMs as streaming guards across two tracks. The situational track (800 scenarios) spans four families, from routine and safe-but-suspicious…

---

## 📅 2026-07-01

### [MECoBench: A Systematic Study of Multimodal Agent Collaboration in Embodied Environments](https://arxiv.org/abs/2606.31966v1)

- **arXiv**: `2606.31966v1`  |  **提交日期**: 2026-06-30
- **作者**: Qingyun Liu, Jiwen Zhang, Jingyi Hu, Siyuan Wang, Zhongyu Wei

Recent multimodal large language models (MLLMs) have strong potential as embodied agents, but their ability to collaborate in visually grounded environments remains underexplored. To address this gap, we introduce MECoBench, a multimodal embodied cooperation benchmark with an evaluation platform spanning diverse real-world tasks, two cooperation structures, and three collaboration modes. Through extensive experiments across various MLLMs, we summarize three key findings: (i) Collaboration generally improves embodied task completion, but its benefits depend on balancing collaborative gains…

---

### [MVP-Nav: Multi-layer Value Map Planner Navigator](https://arxiv.org/abs/2606.31919v1)

- **arXiv**: `2606.31919v1`  |  **提交日期**: 2026-06-30
- **作者**: Wenyuan Xie, Shaokai Wu, Yijin Zhou, Yanbiao Ji, Guodong Zhang, Bayram Bayramli et al.

Zero-shot Object Goal Navigation (ZSON) with RGB-only perception poses a fundamental challenge for embodied agents, as the absence of explicit depth information introduces severe physical uncertainty and semantic-physical misalignment. Existing approaches either rely on high-level semantic reasoning without geometric grounding or learn end-to-end policies that lack explicit physical constraints, often resulting in semantically plausible but physically unsafe behaviors. In this paper, we propose MVP-Nav, a physical-aware RGB-only navigation framework that aligns perception, planning, and…

---

### [Autonomous UAV Navigation for Individual Wildlife Re-Identification](https://arxiv.org/abs/2606.31772v1)

- **arXiv**: `2606.31772v1`  |  **提交日期**: 2026-06-30
- **作者**: Claire Sun, Tanya Berger-Wolf, Jenna Kline

Reliable individual re-identification (re-ID) of wildlife is essential for population monitoring, behavioral tracking, and conservation policy evaluation, yet large-scale data collection remains labor-intensive, relying on manual efforts by ecologists or citizen scientists. We propose an autonomous drone navigation system that actively optimizes image capture for downstream re-ID, moving beyond passive aerial sensing. The system combines YOLOv11 object detection with a DINOv2-based pose classifier to guide real-time flight decisions: detecting animals, orienting to expose the lateral flank…

---

### [AeroVerse-SatAgent: UAV-Satellite Collaborative Spatial Reasoning Inspired by the Dual Visual Pathway Theory of Cognitive Neuroscience](https://arxiv.org/abs/2606.31467v1)

- **arXiv**: `2606.31467v1`  |  **提交日期**: 2026-06-30
- **作者**: Wenyi Zhang, Fanglong Yao, Youzhi Liu, Peng Hu, Zhengqiu Zhu, Chen Gao et al.

With the rapid advancement of aerospace embodied intelligence, enabling Unmanned Aerial Vehicles (UAVs) to autonomously understand and reason about complex environments has become increasingly important. However, existing UAV-based spatial reasoning approaches face critical limitations: single-view perception renders them vulnerable to occlusions and perspective distortions, while most VLMs lack explicit geometric modeling, relying on semantic cues and yielding inconsistent reasoning under viewpoint and scale variations. To address these challenges, we propose SatAgent, a UAV-Satellite…

---

### [Rethinking Foundation Model Collaboration: Enhancing Specialized Models through Proxy Task Reasoning](https://arxiv.org/abs/2606.31157v1)

- **arXiv**: `2606.31157v1`  |  **提交日期**: 2026-06-30
- **作者**: Hongyi Lin, Yang Liu, Jinhua Zhao, Xiaobo Qu

Foundation models are increasingly integrated into embodied intelligence systems, but directly assigning them structured prediction tasks requires precise geometric and numerical estimation, where specialized models often remain stronger. This capability mismatch raises a key question: should foundation models replace task-specific predictors, or should they collaborate through tasks better aligned with their strengths? We propose FAT, a foundation-model-augmented task-specific reasoning framework that treats collaboration as task decomposition rather than model replacement. FAT decomposes…

---

### [CasaMaestro: Multi-View Panoramas for House-Scale 3D Reconstruction](https://arxiv.org/abs/2606.31086v1)

- **arXiv**: `2606.31086v1`  |  **提交日期**: 2026-06-30
- **作者**: Yuzhou Ji, Xiaotian Yang, Zhipeng Zhang

The rise of home-deployed embodied AI systems is driving a growing need for fast, metric 3D reconstruction of residential spaces to support navigation, interaction, and long-horizon task execution. However, the commonly used pinhole-camera 3D reconstruction pipelines struggle to model large indoor residences efficiently due to their limited field of view, to which achieving full coverage across multiple rooms often requires thousands of images and incurs drift from long chains of incremental alignment. In this work, we present CasaMaestro (Spanish words meaning ``house'' and ``master''), a…

---

### [Hierarchical 3D Scene Graph Construction and Belief-based Planning for Semantic Navigation](https://arxiv.org/abs/2606.31071v1)

- **arXiv**: `2606.31071v1`  |  **提交日期**: 2026-06-30
- **作者**: Bing Wu, Zuyao Chen, Changwen Chen

Semantic navigation is a fundamental task for embodied agents operating in unseen environments, requiring both semantic understanding and long-term decision-making. Recent foundation models have empowered agents with rich semantic priors for this task. However, without structured global representations, decision-making often falls back on local observations and greedy strategies, resulting in inefficient exploration and myopic behaviors, especially in long-distance navigation. To address these challenges, we propose a zero-shot semantic navigation framework. Our method incrementally maintains…

---

### [LabGuard: Grounding Natural-Language Laboratory Rules into Runtime Guards for Embodied Laboratory Agents](https://arxiv.org/abs/2606.31045v1)

- **arXiv**: `2606.31045v1`  |  **提交日期**: 2026-06-30
- **作者**: Jingpu Yang, Fengxian Ji, Zhengzhao Lai, Zhexuan Cui, Guangxian Ouyang, Qian Jiang et al.

Scientific embodied agents are increasingly capable of carrying out laboratory procedures, but executing these procedures safely in dynamic laboratory environments remains challenging. Current safety approaches often overlook the intermediate step of transforming laboratory natural language, including safety rules, manuals, protocols, and standard operating procedures, into machine-checkable runtime constraints. We introduce LabGuard (Laboratory Guard), a language-to-execution safety suite that grounds natural-language laboratory rules into executable specifications and deploys them as…

---

### [UnfoldArt: Zero-Shot Recovery of Full Articulated 3D Objects from Text or Image](https://arxiv.org/abs/2606.30608v2)

- **arXiv**: `2606.30608v2`  |  **提交日期**: 2026-06-29
- **作者**: Mohamed el Amine Boudjoghra, Ivan Laptev, Angela Dai

Articulated 3D objects are essential for interactive environments in embodied AI, robotics, and virtual reality, but reconstructing their structure and motion from sparse observations remains challenging. Existing approaches remain largely constrained by lack of supervised data or lack the priors needed to reliably recover articulation, hidden geometry, and internal object structure. We present the first debate-driven agentic approach to articulated 3D object reconstruction from text or image inputs that both grounds articulation reasoning in concrete motion and exposes the occluded geometry…

---

## 📅 2026-06-30

### [Open-Vocabulary and Referring Segmentation for 3D Gaussians Using 2D Detectors](https://arxiv.org/abs/2606.30638v1)

- **arXiv**: `2606.30638v1`  |  **提交日期**: 2026-06-29
- **作者**: Jameel Hassan, Yasiru Ranasinghe, Vishal Patel

3D Gaussian Splatting (3DGS) has emerged at the forefront of 3D scene reconstruction. Extending 3DGS with language-driven, open-vocabulary understanding has gained significant attention for real-world applications such as embodied AI. Recent methods achieve this by learning an instance feature attribute and assigning semantics by distilling high-dimensional Contrastive Language-Image Pretraining (CLIP) features directly into the scene representation. However, the instance grouping mechanisms of these methods either require a predefined number of instances or suffer from noise in their…

---

### [UnfoldArt: Zero-Shot Recovery of Full Articulated 3D Objects from Text or Image](https://arxiv.org/abs/2606.30608v1)

- **arXiv**: `2606.30608v1`  |  **提交日期**: 2026-06-29
- **作者**: Mohamed el amine boudjoghra, Ivan Laptev, Angela Dai

Articulated 3D objects are essential for interactive environments in embodied AI, robotics, and virtual reality, but reconstructing their structure and motion from sparse observations remains challenging. Existing approaches remain largely constrained by lack of supervised data or lack the priors needed to reliably recover articulation, hidden geometry, and internal object structure. We present the first debate-driven agentic approach to articulated 3D object reconstruction from text or image inputs that both grounds articulation reasoning in concrete motion and exposes the occluded geometry…

---

### [The Surprising Effectiveness of Video Diffusion Models for Hand Motion Reconstruction](https://arxiv.org/abs/2606.30308v1)

- **arXiv**: `2606.30308v1`  |  **提交日期**: 2026-06-29
- **作者**: Yuxi Wang, Chengkai Jin, Yufei Liu, Wenqi Ouyang, Tianyi Wei, Zhiwei Zeng et al.

4D hand motion reconstruction from egocentric video is bottlenecked by clear limitations of existing methods: image-based pipelines depend on a detector that fails under heavy occlusion, while video-based methods rely on temporal modules learned only from scarce hand-pose annotations, a narrow signal insufficient to model motion dynamics, occlusion reasoning, and hand-object interaction. These capabilities, however, are exactly what video generative models must implicitly acquire when trained to synthesize coherent video at internet scale. Motivated by this, we present ViDiHand, which…

---

### [Shell-Supervised Gaussian Splatting for Urban Real-to-Sim Reconstruction](https://arxiv.org/abs/2606.30014v1)

- **arXiv**: `2606.30014v1`  |  **提交日期**: 2026-06-29
- **作者**: Yuan Yang, Peijun Lu, Fangzhou Lu, Sai Fan, Siqi Yan, Chenyuan Zhang et al.

Real-to-sim reconstruction for embodied AI requires geometry that is useful for collision reasoning, navigation, and agent-environment interaction, not only photorealistic novel-view synthesis. However, close-range urban facades are difficult for video-to-3D reconstruction: glass, reflections, repeated windows, and weak texture can produce visually plausible renderings with unstable surface geometry. We introduce shell-supervised Gaussian Splatting, a reconstruction-stage framework that uses an external facade structural shell as lightweight geometric supervision for video-driven Gaussian…

---

### [Efficient Visual Pointing for Embodied AI:Agent-Driven Data Synthesis, Cross-Block Attention, and Iterative Correction](https://arxiv.org/abs/2606.29850v1)

- **arXiv**: `2606.29850v1`  |  **提交日期**: 2026-06-29
- **作者**: Zijian Hong, Qi Lv, Yuxiang Xie, Jianming Xing, Xiang Deng, Weili Guan et al.

Visual pointing maps a language instruction to pixel co ordinates, a core skill for embodied AI. We describe our PointArena 2026 solution, which achieves 77.2% overall accuracy and ranks second on the benchmark. The ap proach targets three failure modes. First, agent-driven syn thesis builds large semantic and anchor-relative candidate pools; the server inventory contains 55,372 processed out puts, 53,772 de-duplicated sample IDs, and 37,574 train able completed or accepted rows. Second, a determinis tic steerable-data pipeline creates a verified 10,000-sample main set, plus reserve samples,…

---

## 📅 2026-06-29

### [HAT-4D: Lifting Monocular Video for 4D Multi-Object Interactions via Human-Agent Collaboration](https://arxiv.org/abs/2606.28215v1)

- **arXiv**: `2606.28215v1`  |  **提交日期**: 2026-06-26
- **作者**: Jiaxin Li, Yuxiang Wu, Zhenkai Zhang, Xinrui Shi, Haoyuan Wang, Yichen Zhao et al.

Extracting dynamic 4D object interactions from massive, in-the-wild monocular videos offers a highly efficient data collection pathway for scaling Embodied AI and training VLAs. However, existing monocular 4D reconstruction methods primarily focus on isolated objects, often failing under the severe occlusions and complex dynamics inherent in multi-object interactions. To bridge this gap, we propose HAT-4D, the first agentic framework designed to reconstruct the 3D geometry, temporal dynamics, and physical interactions of multiple objects from a single video. By integrating VLMs with a…

---

### [LLawCo: Learning Laws of Cooperation for Modeling Embodied Multi-Agent Behavior](https://arxiv.org/abs/2606.28182v1)

- **arXiv**: `2606.28182v1`  |  **提交日期**: 2026-06-26
- **作者**: Qinhong Zhou, Chuang Gan, Anoop Cherian

Embodied agents operating in decentralized and partially observable environments have attracted growing attention in recent years. However, existing large language model (LLM)-based agents often exhibit behaviors that are misaligned with their partners or inconsistent with the environment state, leading to inefficient cooperation and poor task success. To address this challenge, we propose a novel framework, Learning Laws of Cooperation (LLawCo), that enables embodied agents to autonomously align with both their partners and task objectives. Our framework allows agents to reflect on past…

---

### [AirGroundBench: Probing Spatial Intelligence in Multimodal Large Models under Heterogeneous Multi-View Embodied Collaboration](https://arxiv.org/abs/2606.28049v1)

- **arXiv**: `2606.28049v1`  |  **提交日期**: 2026-06-26
- **作者**: Haotian Li, Yida Wang, Leyuan Wang, Jinshan Lai, Keyang Wang, Zonghao Guo et al.

In recent years, multimodal large language models (MLLMs) have shown strong potential for embodied intelligence, yet their ability to maintain geometrically consistent spatial understanding across heterogeneous views remains under-evaluated. Existing benchmarks largely focus on single-agent, single-view perception, leaving a gap in the systematic assessment of collaborative air-ground settings, where multi-scale observations are complementary but introduce scale mismatch, asymmetric occlusion, and reference-frame inconsistencies. We present AirGroundBench, a diagnostic benchmark for…

---

### [Building a Scalable, Reproducible, Evaluatable, and Closed-Loop Simulation Environment Foundation for Embodied Intelligence Cloud-Native Simulation Infrastructure for Embodied Intelligence Training, Evaluation, and Data Collection](https://arxiv.org/abs/2606.27962v1)

- **arXiv**: `2606.27962v1`  |  **提交日期**: 2026-06-26
- **作者**: Junwu Xiong, Yongjian Guo, Mingxi Luo, Ning Qiao, Lei Kang, Song Wang et al.

This paper presents a cloud-native simulation infrastructure framework for embodied intelligence that supports large-scale training, standardized evaluation, and simulation-based data collection. The framework unifies simulation environment generation, task execution, trajectory collection, model evaluation, data management, and cloud services into a scalable and reproducible platform. To address the high cost, limited scalability, and poor reproducibility of real-world robotic data collection, the framework adopts cloud-native technologies including elastic resource scheduling, containerized…

---

### [When Multi-Robot Systems Meet Agentic AI:Towards Embodied Collective Intelligence](https://arxiv.org/abs/2606.27929v1)

- **arXiv**: `2606.27929v1`  |  **提交日期**: 2026-06-26
- **作者**: Yuxuan Yan, Yuanyuan Jia, Qianqian Yang

Embodied AI is increasingly becoming agentic, shifting robots from perception--control pipelines towards closed-loop systems that can retrieve context, deliberate during execution, monitor feedback, and refine future behavior. In parallel, robotics research has also moved from single-robot autonomy towards multi-robot systems, driven by the need for wider sensing, distributed action, heterogeneous capabilities, and fault tolerance. As AI agents move from single-agent use towards multi-agent collaboration, robotics faces a parallel challenge: robot teams must move beyond sharing maps, task…

---

### [NormAct: A Benchmark for Hidden Social Norm Compliance in Embodied Planning](https://arxiv.org/abs/2606.27826v1)

- **arXiv**: `2606.27826v1`  |  **提交日期**: 2026-06-26
- **作者**: Shiyun Zhao, Xinwei Song, Tianyu Guo, Xiaomeng Gao, Mingyuan Liu, Xu Han et al.

Multimodal large language models (MLLMs) are increasingly deployed as embodied planners in egocentric environments, where task success requires not only achieving instructed goals but also acting in socially appropriate ways. While explicit goals may render certain actions optimal, implicit social norms often impose hidden constraints. Existing evaluations typically focus on explicit goal achievement or direct norm knowledge, seldom assessing whether planners can infer and apply these hidden constraints within action sequences. We introduce NormAct, a benchmark for embodied social-norm…

---

## 📅 2026-06-27

### [Advancing Omnimodal Embodied Agents from Isolated Skills to Everyday Physical Autonomy](https://arxiv.org/abs/2606.27251v1)

- **arXiv**: `2606.27251v1`  |  **提交日期**: 2026-06-25
- **作者**: Junhao Shi, Zezheng Huai, Siyin Wang, Jia Chen, Yubang Wang, Zhaoye Fei et al.

Building persistent embodied agents in unstructured environments demands unified orchestration of heterogeneous tools spanning both cyber (APIs, IoT) and physical (manipulation, navigation) domains, coupled with autonomous recovery from physical failures that inevitably arise over extended operation. Existing systems treat these as separate problems: VLM-based planners lack a unified cyber-physical action space, agent frameworks accumulate unbounded context that degrades temporal coherence, and VLA policies execute open-loop without detecting their own failures. We argue that persistent…

---

### [ForesightSafety-VLA: A Unified Diagnostic Safety Benchmark for Vision-Language-Action Models](https://arxiv.org/abs/2606.27079v1)

- **arXiv**: `2606.27079v1`  |  **提交日期**: 2026-06-25
- **作者**: Mingyang Lyu, Yinqian Sun, Yiyang Jia, Sicheng Shen, Moquan Sha, Huangrui Li et al.

In embodied intelligence, safety is a prerequisite for reliable robot deployment in the physical world. Current vision-language-action (VLA) models continue to advance toward general-purpose task capability, yet their embodied safety limits remain poorly understood. To address this gap, we introduce ForesightSafety-VLA, a diagnostic benchmark that makes safety the primary evaluation target for VLA systems. We define a 13-category safety taxonomy covering physical interaction safety (Safe-Core), instruction-side safety (Safe-Lang), and perception-side safety (Safe-Vis), and evaluate policies…

---

### [SAGE-Nav: Leveraging LLM Planning and Alignment Fusion for Hierarchical Scene Graph-Guided Navigation](https://arxiv.org/abs/2606.25497v1)

- **arXiv**: `2606.25497v1`  |  **提交日期**: 2026-06-24
- **作者**: Hao Su, Yuehao Huang, Yukai Ma, Yong Liu, Jiajun Lv

Object-Goal Navigation (ObjNav) requires embodied agents to autonomously locate specified targets using only egocentric visual observations. Existing monolithic methods struggle with long-horizon reasoning and generalize poorly to novel environments. To address these limitations, we propose SAGE-Nav, a novel hierarchical framework that integrates the reasoning capabilities of Large Language Models (LLMs) with dynamic scene graphs. Crucially, it decouples asynchronous global semantic planning from the high-frequency reactive control loop. The LLM serves as a global planner, decomposing…

---

### [AI Coaching for Accelerating Human Skill Development with Reinforcement Learning](https://arxiv.org/abs/2606.25337v1)

- **arXiv**: `2606.25337v1`  |  **提交日期**: 2026-06-24
- **作者**: Wei Wang, Enlin Gu, Antonio Loquercio, Haimin Hu, Rahul Mangharam

AI copilots can substantially boost human performance through shared control, but excessive assistance can induce over-reliance and skill atrophy. This paper studies how an embodied AI agent can act as a coach that accelerates human motor-skill development. We argue that effective coaching requires strategic scaffolding and stepping back that are aligned with the learner's capability, allowing productive failures that drive learning. We formalize the interactive AI coaching process as a non-cooperative dynamic game in which the learner optimizes task performance while the coach targets the…

---

