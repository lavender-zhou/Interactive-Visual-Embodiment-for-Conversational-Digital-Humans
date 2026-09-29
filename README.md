# Awesome Interactive Conversational Digital Humans

A curated list of papers and resources for the survey  
**Interactive Visual Embodiment for Conversational Digital Humans**.

> This repository is under active construction. Paper links point to DOI records, publisher pages, OpenReview, or arXiv whenever available.

---

## Contents

- [Background](#background)
  - [Surveys and Background](#surveys-and-background)

- [Tasks](#tasks)
  - [Speaking Behavior Generation](#speaking-behavior-generation)
  - [Listening Behavior Generation](#listening-behavior-generation)
  - [Bidirectional Interaction](#bidirectional-interaction)
    - [Role Transition](#role-transition)
    - [Turn-Taking and Interruption](#turn-taking-and-interruption)
    - [Conversational Continuity and Context Modeling](#conversational-continuity-and-context-modeling)
    - [Full-Duplex Interaction](#full-duplex-interaction)

- [Techniques](#techniques)
  - [Multimodal Perception](#multimodal-perception)
    - [Speech and Language Signals](#speech-and-language-signals)
    - [Visual Signals](#visual-signals)
  - [Understanding and Planning](#understanding-and-planning)
    - [Dialogue and Context Understanding](#dialogue-and-context-understanding)
    - [Emotion and Intent Modeling](#emotion-and-intent-modeling)
  - [Generation and Rendering](#generation-and-rendering)
    - [Behavior Representations](#behavior-representations)
    - [Generative Models](#generative-models)
    - [Two-Dimensional Visual Synthesis](#two-dimensional-visual-synthesis)
    - [Three-Dimensional Avatar Rendering](#three-dimensional-avatar-rendering)
    - [Hybrid and Real-Time Systems](#hybrid-and-real-time-systems)

- [Datasets and Evaluation](#datasets-and-evaluation)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  - [Evaluation](#evaluation)
    - [Visual Quality](#visual-quality)
    - [Response Appropriateness](#response-appropriateness)
    - [User Experience](#user-experience)

---

# Background

## Surveys and Background

### Talking-Head and Human Synthesis

- **[Talking Human Face Generation: A Survey](https://doi.org/10.1016/j.eswa.2023.119678)** — *Expert Systems with Applications 2023*

- **[Human–Computer Interaction System: A Survey of Talking-Head Generation](https://doi.org/10.3390/electronics12010218)** — *Electronics 2023*

- **[Deep Person Generation: A Survey from the Perspective of Face, Pose, and Cloth Synthesis](https://doi.org/10.1145/3575656)** — *ACM Computing Surveys 2023*

- **[A Survey of Talking Head Synthesis Techniques: Portrait Generation, Driving Mechanisms, and Editing](https://doi.org/10.1145/3785656)** — *ACM Computing Surveys 2026*

### Digital Humans, Avatars, and Human Motion

- **[Virtual Human: A Comprehensive Survey on Academic and Applications](https://doi.org/10.1109/ACCESS.2023.3329573)** — *IEEE Access 2023*

- **[Human Motion Generation: A Survey](https://doi.org/10.1109/TPAMI.2023.3330935)** — *IEEE TPAMI 2024*

- **[The Interaction Design of 3D Virtual Humans: A Survey](https://doi.org/10.1016/j.cosrev.2024.100653)** — *Computer Science Review 2024*

### Nonverbal Behavior and Embodied Agents

- **[A Comprehensive Review of Data-Driven Co-Speech Gesture Generation](https://doi.org/10.1111/cgf.14776)** — *Computer Graphics Forum 2023*

- **[Embodied Conversational Agents in Extended Reality: A Systematic Review](https://doi.org/10.1109/ACCESS.2025.3566698)** — *IEEE Access 2025*

- **[A Survey on Generative Nonverbal Facial Behavior for Highly Realistic Embodied Agents](https://doi.org/10.1007/s11370-025-00674-2)** — *Intelligent Service Robotics 2026*

---

# Tasks

## Speaking Behavior Generation

- **[Synthesizing Obama: Learning Lip Sync from Audio](https://doi.org/10.1145/3072959.3073640)** — *ACM TOG 2017*

- **[Lip Movements Generation at a Glance](https://doi.org/10.1007/978-3-030-01234-2_32)** — *ECCV 2018*

- **[You Said That?: Synthesising Talking Faces from Audio](https://doi.org/10.1007/s11263-019-01150-y)** — *IJCV 2019*

- **[First Order Motion Model for Image Animation](https://arxiv.org/abs/2003.00196)** — *NeurIPS 2019*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[MakeItTalk: Speaker-Aware Talking-Head Animation](https://doi.org/10.1145/3414685.3417774)** — *ACM TOG 2020*

- **[MeshTalk: 3D Face Animation from Speech using Cross-Modality Disentanglement](https://doi.org/10.1109/ICCV48922.2021.00121)** — *ICCV 2021*

- **[Audio2Head: Audio-Driven One-Shot Talking-Head Generation with Natural Head Motion](https://doi.org/10.24963/ijcai.2021/152)** — *IJCAI 2021*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://doi.org/10.1109/CVPR46437.2021.00991)** — *CVPR 2021*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

- **[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://doi.org/10.1109/CVPR52688.2022.01821)** — *CVPR 2022*

- **[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://doi.org/10.1109/CVPR52729.2023.00836)** — *CVPR 2023*

- **[EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://doi.org/10.1109/ICCV51070.2023.01891)** — *ICCV 2023*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **[SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://doi.org/10.1145/3581783.3611734)** — *ACM MM 2023*

- **[Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/abs/2406.08801)** — *2024*

- **[ScanTalk: 3D Talking Heads from Unregistered Scans](https://doi.org/10.1007/978-3-031-73397-0_2)** — *ECCV 2024*

---

## Listening Behavior Generation

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation](https://doi.org/10.1109/ICCV51070.2023.01905)** — *ICCV 2023*

- **[Can Language Models Learn to Listen?](https://arxiv.org/abs/2308.10897)** — *ICCV 2023*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://doi.org/10.1145/3581783.3612123)** — *ACM MM 2023*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://doi.org/10.1109/CVPR52734.2025.00996)** — *CVPR 2025*

- **[Diffusion-based Realistic Listening Head Generation via Hybrid Motion Modeling](https://doi.org/10.1109/CVPR52734.2025.01481)** — *CVPR 2025*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010)** — *ICCV 2025*

---

## Bidirectional Interaction

### Role Transition

- **[Interactive Conversational Head Generation](https://doi.org/10.1109/TPAMI.2025.3562651)** — *IEEE TPAMI 2025*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://arxiv.org/abs/2505.18096)** — *CVPR 2025*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/abs/2412.04037)** — *CVPR 2025*

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://arxiv.org/abs/2507.00472)** — *ICCV 2025*

- **[Towards Flexible, Natural, Efficient Interaction for Conversational Talking Face Generation](https://arxiv.org/abs/2606.31088)** — *2026*

### Turn-Taking and Interruption

- **[TurnGPT: A Transformer-based Language Model for Predicting Turn-taking in Spoken Dialog](https://doi.org/10.18653/v1/2020.findings-emnlp.268)** — *Findings of EMNLP 2020*

- **[Voice Activity Projection: Self-supervised Learning of Turn-taking Events](https://doi.org/10.21437/Interspeech.2022-10955)** — *INTERSPEECH 2022*

- **[Language Model Can Listen While Speaking](https://doi.org/10.1609/aaai.v39i23.34665)** — *AAAI 2025*

- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals](https://doi.org/10.18653/v1/2025.acl-long.743)** — *ACL 2025*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://doi.org/10.18653/v1/2025.acl-long.709)** — *ACL 2025*

### Conversational Continuity and Context Modeling

- **[Echo: Enhancing Conversational Behavior Generation via Hierarchical Semantic Comprehension with Large Language Models](https://doi.org/10.1145/3757377.3763998)** — *SIGGRAPH Asia 2025*

- **[Social Agent: Mastering Dyadic Nonverbal Behavior Generation via Conversational LLM Agents](https://doi.org/10.1145/3757377.3763879)** — *SIGGRAPH Asia 2025*

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://arxiv.org/abs/2601.02103)** — *CVPR 2026*

- **[PolySLGen: Online Multimodal Speaking-Listening Reaction Generation in Polyadic Interaction](https://arxiv.org/abs/2604.08125)** — *CVPR 2026*

- **[Towards Seamless Interaction: Causal Turn-Level Modeling of Interactive 3D Conversational Head Dynamics](https://arxiv.org/abs/2512.15340)** — *2026*

- **[ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation](https://arxiv.org/abs/2603.17427)** — *2026*

### Full-Duplex Interaction

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://doi.org/10.18653/v1/2024.emnlp-main.1192)** — *EMNLP 2024*

- **[Moshi: A Speech-Text Foundation Model for Real-Time Dialogue](https://arxiv.org/abs/2410.00037)** — *2024*

- **[A Full-Duplex Speech Dialogue Scheme Based on Large Language Model](https://doi.org/10.52202/079017-0427)** — *NeurIPS 2024*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://doi.org/10.18653/v1/2025.acl-long.709)** — *ACL 2025*

---

# Techniques

## Multimodal Perception

### Speech and Language Signals

- **[wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477)** — *NeurIPS 2020*

- **[HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://doi.org/10.1109/TASLP.2021.3122291)** — *IEEE/ACM TASLP 2021*

- **[WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing](https://doi.org/10.1109/JSTSP.2022.3188113)** — *IEEE JSTSP 2022*

- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)** — *ICML 2023*

- **[SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://arxiv.org/abs/2310.13289)** — *ICLR 2024*

- **[AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://doi.org/10.18653/v1/2024.acl-long.521)** — *ACL 2024*

- **[Qwen2-Audio Technical Report](https://arxiv.org/abs/2407.10759)** — *2024*

- **[Let's Go Real Talk: Spoken Dialogue Model for Face-to-Face Conversation](https://doi.org/10.18653/v1/2024.acl-long.860)** — *ACL 2024*

- **[SPIRIT-LM: Interleaved Spoken and Written Language Model](https://doi.org/10.1162/tacl_a_00728)** — *TACL 2025*

### Visual Signals

- **[OpenFace: An Open Source Facial Behavior Analysis Toolkit](https://doi.org/10.1109/WACV.2016.7477553)** — *WACV 2016*

- **[Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/abs/1611.08050)** — *CVPR 2017*

- **[ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation](https://doi.org/10.52202/068431-2795)** — *NeurIPS 2022*

- **[Learning Long-Term Spatial-Temporal Graphs for Active Speaker Detection](https://doi.org/10.1007/978-3-031-19833-5_22)** — *ECCV 2022*

- **[RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation](https://arxiv.org/abs/2312.07526)** — *CVPR 2024*

- **[LoCoNet: Long-Short Context Network for Active Speaker Detection](https://doi.org/10.1109/CVPR52733.2024.01747)** — *CVPR 2024*

- **[Sapiens: Foundation for Human Vision Models](https://doi.org/10.1007/978-3-031-73235-5_12)** — *ECCV 2024*

- **[OpenFace 3.0: A Lightweight Multitask System for Comprehensive Facial Behavior Analysis](https://doi.org/10.1109/FG61629.2025.11099277)** — *FG 2025*

- **[Gaze-LLE: Gaze Target Estimation via Large-Scale Learned Encoders](https://arxiv.org/abs/2412.09586)** — *CVPR 2025*

---

## Understanding and Planning

### Dialogue and Context Understanding

#### Structured Dialogue State Modeling

- **[SUMBT: Slot-Utterance Matching for Universal and Scalable Belief Tracking](https://aclanthology.org/P19-1546/)** — *ACL 2019*

- **[TRADE: Transferable Multi-Domain State Generator for Task-Oriented Dialogue Systems](https://aclanthology.org/P19-1078/)** — *ACL 2019*

- **[A Simple Language Model for Task-Oriented Dialogue](https://arxiv.org/abs/2005.00796)** — *NeurIPS 2020*

- **[Description-Driven Dialogue State Tracking](https://aclanthology.org/2022.sigdial-1.22/)** — *SIGDIAL 2022*

#### Interaction Structure and Participant Grounding

- **[GSN: A Graph-Structured Network for Multi-Party Dialogues](https://doi.org/10.24963/ijcai.2019/696)** — *IJCAI 2019*

- **[MPC-BERT: A Pre-Trained Language Model for Multi-Party Conversation Understanding](https://aclanthology.org/2021.acl-long.285/)** — *ACL-IJCNLP 2021*

- **[GIFT: Graph-Induced Fine-Tuning for Multi-Party Conversation Understanding](https://aclanthology.org/2023.acl-long.651/)** — *ACL 2023*

- **[Friends-MMC: A Dataset for Multi-modal Multi-party Conversation Understanding](https://ojs.aaai.org/index.php/AAAI/article/view/35078)** — *AAAI 2025*

#### Visually Grounded Dialogue

- **Audio Visual Scene-Aware Dialog** — *CVPR 2019*

- **SIMMC 2.0: A Task-oriented Dialog Dataset for Immersive Multimodal Conversations** — *EMNLP 2021*

- **VSTAR: Visual Situated Understanding with Scene and Topic Transitions**

- **MMDU: Multi-Turn Multi-Image Dialog Understanding**

#### Long-Term Conversational Memory

- **[Beyond Goldfish Memory: Long-Term Open-Domain Conversation](https://aclanthology.org/2022.acl-long.356/)** — *ACL 2022*

- **[Generative Agents: Interactive Simulacra of Human Behavior](https://doi.org/10.1145/3586183.3606763)** — *UIST 2023*

- **[MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation](https://arxiv.org/abs/2308.08239)** — *2023*

- **[MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://doi.org/10.1609/aaai.v38i17.29946)** — *AAAI 2024*

- **[Evaluating Very Long-Term Conversational Memory of LLM Agents](https://arxiv.org/abs/2402.17753)** — *ACL 2024*

- **SeCom: Towards Long-Term Conversation Memory through Topic-Based Segmentation and Compression**

- **[LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://openreview.net/forum?id=Q4Y1cs8hrZ)** — *ICLR 2025*

### Emotion and Intent Modeling

#### Multimodal Emotion Understanding

- **[MMGCN: Multimodal Fusion via Deep Graph Convolution Network for Emotion Recognition in Conversation](https://doi.org/10.18653/v1/2021.acl-long.440)** — *ACL-IJCNLP 2021*

- **[COGMEN: COntextualized GNN Based Multimodal Emotion RecognitioN](https://doi.org/10.18653/v1/2022.naacl-main.306)** — *NAACL 2022*

- **Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning with Instruction Tuning**

- **[SemEval-2024 Task 3: Multimodal Emotion Cause Analysis in Conversations](https://doi.org/10.18653/v1/2024.semeval-1.277)** — *SemEval 2024*

#### Multimodal Intent Understanding

- **[MIntRec: A New Dataset for Multimodal Intent Recognition](https://doi.org/10.1145/3503161.3547906)** — *ACM MM 2022*

- **[MIntRec2.0: A Large-Scale Benchmark Dataset for Multimodal Intent Recognition and Out-of-Scope Detection in Conversations](https://openreview.net/forum?id=JbL9f9XeI2)** — *ICLR 2024*

---

## Generation and Rendering

### Behavior Representations

#### Two-Dimensional Representations

- **Animating Arbitrary Objects via Deep Motion Transfer (Monkey-Net)** — *CVPR 2019*

- **[First Order Motion Model for Image Animation](https://arxiv.org/abs/2003.00196)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

#### Three-Dimensional Representations

- **[A Morphable Model for the Synthesis of 3D Faces](https://doi.org/10.1145/311535.311556)** — *SIGGRAPH 1999*

- **[Face Transfer with Multilinear Models](https://doi.org/10.1145/1073204.1073209)** — *ACM TOG 2005*

- **[FaceWarehouse: A 3D Facial Expression Database for Visual Computing](https://doi.org/10.1109/TVCG.2013.249)** — *IEEE TVCG 2014*

- **[SMPL: A Skinned Multi-Person Linear Model](https://doi.org/10.1145/2816795.2818013)** — *ACM TOG 2015*

- **[Learning a Model of Facial Shape and Expression from 4D Scans (FLAME)](https://doi.org/10.1145/3130800.3130813)** — *ACM TOG 2017*

- **[Expressive Body Capture: 3D Hands, Face, and Body from a Single Image (SMPL-X)](https://doi.org/10.1109/CVPR.2019.01123)** — *CVPR 2019*

- **FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction** — *CVPR 2020*

#### Learned Discrete Motion Representations

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations** — *CVPR 2023*

### Generative Models

#### Generative Adversarial Models

- **Generative Adversarial Nets** — *NeurIPS 2014*

- **[Image-to-Image Translation with Conditional Adversarial Networks](https://doi.org/10.1109/CVPR.2017.632)** — *CVPR 2017*

- **Few-Shot Adversarial Learning of Realistic Neural Talking Head Models** — *ICCV 2019*

- **Speech-Driven Facial Animation Using Cascaded GANs for Learning of Motion and Texture** — *ECCV 2020*

- **FLNet: Landmark Driven Talking Face Generation** — *AAAI 2020*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **HeadGAN: One-Shot Neural Head Synthesis and Editing** — *ICCV 2021*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

#### Latent-Variable Models

- **Audio2Gestures: Generating Diverse Gestures from Speech Audio with Conditional Variational Autoencoders** — *ICCV 2021*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation](https://doi.org/10.1109/ICCV51070.2023.01905)** — *ICCV 2023*

- **TalkSHOW: Generating Holistic 3D Human Motion from Speech** — *CVPR 2023*

#### Autoregressive Models

- **[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://doi.org/10.1109/CVPR52688.2022.01821)** — *CVPR 2022*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **TalkSHOW: Generating Holistic 3D Human Motion from Speech** — *CVPR 2023*

#### Diffusion Models

- **[Denoising Diffusion Probabilistic Models](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)** — *NeurIPS 2020*

- **[DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://doi.org/10.1109/CVPR52729.2023.00197)** — *CVPR 2023*

- **DiffuseStyleGesture: Stylized Audio-Driven Co-Speech Gesture Generation with Diffusion Models** — *IJCAI 2023*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://doi.org/10.1145/3581783.3612123)** — *ACM MM 2023*

- **Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation** — *WACV 2024*

- **DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models** — *ACM TOG 2024*

- **DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-Driven Holistic 3D Expression and Gesture Generation** — *CVPR 2024*

- **MoDiTalker: Motion-Disentangled Diffusion Model for High-Fidelity Talking Head Generation** — *AAAI 2025*

### Two-Dimensional Visual Synthesis

#### Motion Field Warping and Inpainting

- **[First Order Motion Model for Image Animation](https://arxiv.org/abs/2003.00196)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

- **DaGAN: Depth-Aware Generative Adversarial Network for Talking Head Video Generation** — *CVPR 2022*

- **Audio-Visual Face Reenactment (AVFR-GAN)** — *WACV 2023*

- **[LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/abs/2407.03168)** — *2024*

#### Feed-Forward Image Synthesis

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

- **PD-FGC: Progressive Disentangled Representation Learning for Fine-Grained Controllable Talking Head Synthesis** — *CVPR 2023*

- **StyleLipSync: Style-based Personalized Lip-sync Video Generation** — *ICCV 2023*

- **StyleSync** — *CVPR 2024*

#### Diffusion-Based Video Synthesis

- **[DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://doi.org/10.1109/CVPR52729.2023.00197)** — *CVPR 2023*

- **HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation** — *CVPR 2025*

- **Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Video Diffusion Transformer** — *CVPR 2025*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010)** — *ICCV 2025*

### Three-Dimensional Avatar Rendering

#### Mesh-Based Rendering

- **Neural Voice Puppetry: Audio-Driven Facial Reenactment** — *ECCV 2020*

- **Neural Head Avatars from Monocular RGB Videos** — *CVPR 2022*

- **DynTet: Learning Dynamic Tetrahedra for High-Quality Talking Head Synthesis** — *CVPR 2024*

- **TexTalker: Towards High-Fidelity 3D Talking Avatar with Personalized Dynamic Texture** — *2025*

#### Neural Radiance Fields

- **AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis** — *ICCV 2021*

- **GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis** — *ICLR 2023*

- **HiDe-NeRF: One-Shot High-Fidelity Talking-Head Synthesis with Deformable Neural Radiance Field** — *CVPR 2023*

- **ER-NeRF: Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis** — *ICCV 2023*

- **SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis** — *CVPR 2024*

- **S3D-NeRF: Single-Shot Speech-Driven Neural Radiance Field for High-Fidelity Talking Head Synthesis** — *ECCV 2024*

#### 3D Gaussian Splatting

- **GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting** — *ACM MM 2024*

- **GaussianSpeech: Audio-Driven Personalized 3D Gaussian Avatars** — *2025*

- **DGTalker: Disentangled Generative Latent Space Learning for Audio-Driven Gaussian Talking Heads** — *2025*

- **InsTaG: Learning Personalized 3D Talking Head from Few-Second Video** — *2025*

- **GGTalker: Talking Head Synthesis with Generalizable Gaussian Priors and Identity-Specific Adaptation** — *2025*

- **MGGTalk: Monocular and Generalizable Gaussian Talking Head Animation** — *2025*

- **TaoAvatar: Real-Time Lifelike Full-Body Talking Avatars for Augmented Reality via 3D Gaussian Splatting** — *2025*

### Hybrid and Real-Time Systems

- **[Audio2Head: Audio-Driven One-Shot Talking-Head Generation with Natural Head Motion](https://doi.org/10.24963/ijcai.2021/152)** — *IJCAI 2021*

- **SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis** — *CVPR 2024*

- **GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting** — *ACM MM 2024*

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://arxiv.org/abs/2507.00472)** — *ICCV 2025*

- **TaoAvatar: Real-Time Lifelike Full-Body Talking Avatars for Augmented Reality via 3D Gaussian Splatting** — *2025*

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://arxiv.org/abs/2601.02103)** — *CVPR 2026*

---

# Datasets and Evaluation

## Datasets and Benchmarks

### Speaking and Talking-Head Datasets

- **BIWI 3D Audio-Visual Corpus** — *3D facial motion*

- **VOCASET** — *Speech-aligned 4D face scans*

- **HDTF: High-Definition Talking Face Dataset** — *Talking-head video*

- **VoxCeleb2** — *Large-scale audiovisual speaker data*

- **LRS2** — *Audiovisual speech*

- **LRS3** — *Audiovisual speech*

- **TalkVid** — *Large-scale talking-head video*

### Interactive and Listening Datasets

- **[ViCo: Responsive Listening Head Generation](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[REACT2023](https://doi.org/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[ViCo-X: Interactive Conversational Head Generation](https://doi.org/10.1109/TPAMI.2025.3562651)** — *IEEE TPAMI 2025*

- **[DualTalk](https://arxiv.org/abs/2505.18096)** — *CVPR 2025*

- **SpeakerVid-5M** — *Dyadic interactive video*

- **Multi-TPC** — *Three-party speech, body motion, and gaze*

### Interaction Benchmarks

- **[REACT2023: The First Multiple Appropriate Facial Reaction Generation Challenge](https://doi.org/10.1145/3581783.3612832)** — *ACM MM 2023*

- **REACT 2025: The Third Multiple Appropriate Facial Reaction Generation Challenge** — *ACM MM 2025*

- **[Full-Duplex-Bench](https://arxiv.org/abs/2503.04721)** — *2025*

- **[VideoFDB](https://arxiv.org/abs/2605.30256)** — *2026*

---

## Evaluation

### Visual Quality

- **[Structural Similarity Index (SSIM)](https://doi.org/10.1109/TIP.2003.819861)** — *IEEE TIP 2004*

- **Fréchet Inception Distance (FID)** — *NeurIPS 2017*

- **[Learned Perceptual Image Patch Similarity (LPIPS)](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.html)** — *CVPR 2018*

- **[Fréchet Video Distance (FVD)](https://arxiv.org/abs/1812.01717)** — *2018*

- **SyncNet** — *ACCV Workshop 2016*

- **[Wav2Lip / LSE-D / LSE-C](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

### Response Appropriateness

- **[Learning to Listen](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[REACT2023](https://doi.org/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[CustomListener](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://doi.org/10.1109/CVPR52734.2025.00996)** — *CVPR 2025*

- **[Full-Duplex-Bench](https://arxiv.org/abs/2503.04721)** — *2025*

### User Experience

- **[Responsive Listening Head Generation](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[CustomListener](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://doi.org/10.18653/v1/2024.emnlp-main.1192)** — *EMNLP 2024*

---

## Contributing

Contributions are welcome.

If you find a relevant paper on interactive visual embodiment, speaking/listening behavior generation, multimodal perception, conversational understanding, generation and rendering, datasets, or evaluation, please feel free to open an issue or submit a pull request.
