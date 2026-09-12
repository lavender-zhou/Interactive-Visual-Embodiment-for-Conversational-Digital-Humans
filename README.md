# Awesome Interactive Conversational Digital Humans

A curated list of papers and resources for the survey **Interactive Visual Embodiment for Conversational Digital Humans**.

> This repository is under active construction. Paper links point to DOI records or arXiv whenever available.

## Contents

- [Surveys and Background](#surveys-and-background)
- [Speaking Behavior Generation](#speaking-behavior-generation)
- [Listening Behavior Generation](#listening-behavior-generation)
- [Bidirectional Interaction](#bidirectional-interaction)
  - [Role Transition](#role-transition)
  - [Turn-Taking and Interruption](#turn-taking-and-interruption)
  - [Conversational Continuity](#conversational-continuity)
- [Full-Duplex Interaction](#full-duplex-interaction)
- [Multimodal Perception](#multimodal-perception)
  - [Speech and Text Signals](#speech-and-text-signals)
  - [Visual Signals](#visual-signals)
- [Understanding and Behavior Planning](#understanding-and-behavior-planning)
- [Datasets and Benchmarks](#datasets-and-benchmarks)

## Surveys and Background

### Talking-Head and Human Synthesis

- **[Talking Human Face Generation: A Survey](https://doi.org/10.1016/j.eswa.2023.119678)** — *Expert Systems with Applications 2023*

- **[Human–Computer Interaction System: A Survey of Talking-Head Generation](https://doi.org/10.3390/electronics12010218)** — *Electronics 2023*

- **[Deep Person Generation: A Survey from the Perspective of Face, Pose, and Cloth Synthesis](https://doi.org/10.1145/3575656)** — *ACM Computing Surveys 2023*

- **[A Survey of Talking Head Synthesis Techniques: Portrait Generation, Driving Mechanisms, and Editing](https://doi.org/10.1145/3785656)** — *ACM Computing Surveys 2026*

- **[Deepfake Generation and Detection: A Benchmark and Survey](https://doi.org/10.1145/3801962)** — *ACM Computing Surveys 2026*

### Digital Humans, Avatars, and Human Motion

- **[Virtual Human: A Comprehensive Survey on Academic and Applications](https://doi.org/10.1109/ACCESS.2023.3329573)** — *IEEE Access 2023*

- **[Human Motion Generation: A Survey](https://doi.org/10.1109/TPAMI.2023.3330935)** — *IEEE TPAMI 2024*

- **[The Interaction Design of 3D Virtual Humans: A Survey](https://doi.org/10.1016/j.cosrev.2024.100653)** — *Computer Science Review 2024*

### Nonverbal Behavior and Embodied Agents

- **[A Comprehensive Review of Data-Driven Co-Speech Gesture Generation](https://doi.org/10.1111/cgf.14776)** — *Computer Graphics Forum 2023*

- **[Embodied Conversational Agents in Extended Reality: A Systematic Review](https://doi.org/10.1109/ACCESS.2025.3566698)** — *IEEE Access 2025*

- **[A Survey on Generative Nonverbal Facial Behavior for Highly Realistic Embodied Agents](https://doi.org/10.1007/s11370-025-00674-2)** — *Intelligent Service Robotics 2026*

## Speaking Behavior Generation

- **[Synthesizing Obama: learning lip sync from audio](https://doi.org/10.1145/3072959.3073640)** — *ACM TOG 2017*

- **[You Said That?: Synthesising Talking Faces from Audio](https://doi.org/10.1007/s11263-019-01150-y)** — *IJCV 2019*

- **[Lip Movements Generation at a Glance](https://doi.org/10.1007/978-3-030-01234-2_32)** — *ECCV 2018*

- **[MakeItTalk: Speaker-Aware Talking-Head Animation](https://doi.org/10.1145/3414685.3417774)** — *ACM TOG 2020*

- **[First Order Motion Model for Image Animation](https://arxiv.org/abs/2003.00196)** — *NeurIPS 2019*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://doi.org/10.1109/CVPR46437.2021.00991)** — *CVPR 2021*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

- **[Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://doi.org/10.24963/ijcai.2021/152)** — *IJCAI 2021*

- **[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://doi.org/10.1109/CVPR52729.2023.00836)** — *CVPR 2023*

- **[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://doi.org/10.1109/CVPR52688.2022.01821)** — *CVPR 2022*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[MeshTalk: 3D Face Animation from Speech using Cross-Modality Disentanglement](https://doi.org/10.1109/ICCV48922.2021.00121)** — *ICCV 2021*

- **[EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://doi.org/10.1109/ICCV51070.2023.01891)** — *ICCV 2023*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **[SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://doi.org/10.1145/3581783.3611734)** — *ACM MM 2023*

- **[ScanTalk: 3D Talking Heads from Unregistered Scans](https://doi.org/10.1007/978-3-031-73397-0_2)** — *ECCV 2024*

- **[Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/abs/2406.08801)** — *arXiv 2024*

## Listening Behavior Generation

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[Can Language Models Learn to Listen?](https://arxiv.org/abs/2308.10897)** — *ICCV 2023*

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://doi.org/10.1109/CVPR52734.2025.00996)** — *CVPR 2025*

- **[Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation](https://doi.org/10.1109/ICCV51070.2023.01905)** — *ICCV 2023*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://doi.org/10.1145/3581783.3612123)** — *ACM MM 2023*

- **[Diffusion-based Realistic Listening Head Generation via Hybrid Motion Modeling](https://doi.org/10.1109/CVPR52734.2025.01481)** — *CVPR 2025*

## Bidirectional Interaction

### Role Transition

- **[Interactive Conversational Head Generation](https://doi.org/10.1109/TPAMI.2025.3562651)** — *IEEE TPAMI 2025*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://arxiv.org/abs/2505.18096)** — *CVPR 2025*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/abs/2412.04037)** — *CVPR 2025*

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://arxiv.org/abs/2507.00472)** — *ICCV 2025*

- **[Towards Flexible, Natural, Efficient Interaction for Conversational Talking Face Generation](https://arxiv.org/abs/2606.31088)** — *arXiv 2026*

### Turn-Taking and Interruption

- **[TurnGPT: a Transformer-based Language Model for Predicting Turn-taking in Spoken Dialog](https://doi.org/10.18653/v1/2020.findings-emnlp.268)** — *Findings of EMNLP 2020*

- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals](https://doi.org/10.18653/v1/2025.acl-long.743)** — *ACL 2025*

- **[Language Model Can Listen While Speaking](https://doi.org/10.1609/aaai.v39i23.34665)** — *AAAI 2025*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://doi.org/10.18653/v1/2025.acl-long.709)** — *ACL 2025*

- **[Voice Activity Projection: Self-supervised Learning of Turn-taking Events](https://doi.org/10.21437/Interspeech.2022-10955)** — *INTERSPEECH 2022*

### Conversational Continuity

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://arxiv.org/abs/2601.02103)** — *CVPR 2026*

- **[PolySLGen: Online Multimodal Speaking-Listening Reaction Generation in Polyadic Interaction](https://arxiv.org/abs/2604.08125)** — *CVPR 2026*

- **[Echo: Enhancing Conversational Behavior Generation via Hierarchical Semantic Comprehension with Large Language Models](https://doi.org/10.1145/3757377.3763998)** — *SIGGRAPH Asia 2025*

- **[Social Agent: Mastering Dyadic Nonverbal Behavior Generation via Conversational LLM Agents](https://doi.org/10.1145/3757377.3763879)** — *SIGGRAPH Asia 2025*

- **[Towards Seamless Interaction: Causal Turn-Level Modeling of Interactive 3D Conversational Head Dynamics](https://arxiv.org/abs/2512.15340)** — *arXiv 2026*

- **[ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation](https://arxiv.org/abs/2603.17427)** — *arXiv 2026*

## Full-Duplex Interaction

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://doi.org/10.18653/v1/2024.emnlp-main.1192)** — *EMNLP 2024*

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Model](https://doi.org/10.52202/079017-0427)** — *NeurIPS 2024*

## Multimodal Perception

### Speech and Text Signals

- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)** — *ICML 2023*

- **[wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477)** — *NeurIPS 2020*

- **[HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://doi.org/10.1109/TASLP.2021.3122291)** — *IEEE/ACM TASLP 2021*

- **[WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing](https://doi.org/10.1109/JSTSP.2022.3188113)** — *IEEE JSTSP 2022*

- **[SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://arxiv.org/abs/2310.13289)** — *ICLR 2024*

- **[Advancing Large Language Models to Capture Varied Speaking Styles and Respond Properly in Spoken Conversations](https://doi.org/10.18653/v1/2024.acl-long.358)** — *ACL 2024*

- **[Qwen2-Audio Technical Report](https://arxiv.org/abs/2407.10759)** — *arXiv 2024*

- **[Speech Recognition Meets Large Language Model: Benchmarking, Models, and Exploration](https://doi.org/10.1609/aaai.v39i23.34666)** — *AAAI 2025*

- **[AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://doi.org/10.18653/v1/2024.acl-long.521)** — *ACL 2024*

- **[SPIRIT-LM: Interleaved Spoken and Written Language Model](https://doi.org/10.1162/tacl_a_00728)** — *TACL 2025*

- **[Let’s Go Real Talk: Spoken Dialogue Model for Face-to-Face Conversation](https://doi.org/10.18653/v1/2024.acl-long.860)** — *ACL 2024*

### Visual Signals

- **[OpenFace: An Open Source Facial Behavior Analysis Toolkit](https://doi.org/10.1109/WACV.2016.7477553)** — *WACV 2016*

- **[Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/abs/1611.08050)** — *CVPR 2017*

- **[ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation](https://doi.org/10.52202/068431-2795)** — *NeurIPS 2022*

- **[RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation](https://arxiv.org/abs/2312.07526)** — *CVPR 2024*

- **[Sapiens: Foundation for Human Vision Models](https://doi.org/10.1007/978-3-031-73235-5_12)** — *ECCV 2024*

- **[OpenFace 3.0: A Lightweight Multitask System for Comprehensive Facial Behavior Analysis](https://doi.org/10.1109/FG61629.2025.11099277)** — *FG 2025*

- **[Gaze-LLE: Gaze Target Estimation via Large-Scale Learned Encoders](https://arxiv.org/abs/2412.09586)** — *CVPR 2025*

- **[AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection](https://doi.org/10.1109/ICASSP40776.2020.9053900)** — *ICASSP 2020*

- **[Is Someone Speaking? Exploring Long-Term Temporal Features for Audio-Visual Active Speaker Detection](https://doi.org/10.1145/3474085.3475587)** — *ACM MM 2021*

- **[Learning Long-Term Spatial-Temporal Graphs for Active Speaker Detection](https://doi.org/10.1007/978-3-031-19833-5_22)** — *ECCV 2022*

- **[A Light Weight Model for Active Speaker Detection](https://arxiv.org/abs/2303.04439)** — *CVPR 2023*

- **[LoCoNet: Long-Short Context Network for Active Speaker Detection](https://doi.org/10.1109/CVPR52733.2024.01747)** — *CVPR 2024*

## Understanding and Behavior Planning

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
#### Long-Term Conversational Memory
- **[Beyond Goldfish Memory: Long-Term Open-Domain Conversation](https://aclanthology.org/2022.acl-long.356/)** — *ACL 2022*
- **[Generative Agents: Interactive Simulacra of Human Behavior](https://doi.org/10.1145/3586183.3606763)** — *UIST 2023*
- **[MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation](https://arxiv.org/abs/2308.08239)** — *arXiv 2023*
- **[MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://doi.org/10.1609/aaai.v38i17.29946)** — *AAAI 2024*
- **[Evaluating Very Long-Term Conversational Memory of LLM Agents](https://arxiv.org/abs/2402.17753)** — *ACL 2024*
- **[LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://openreview.net/forum?id=Q4Y1cs8hrZ)** — *ICLR 2025*
- **[On Memory Construction and Retrieval for Personalized Conversational Agents](https://openreview.net/forum?id=xKDZAW0He3)** — *ICLR 2025*

## Datasets and Benchmarks

<!-- Papers to be added. -->

## Contributing

Suggestions and corrections are welcome. Please open an issue or submit a pull request.

## Note

For records without a DOI or an explicit URL in the bibliography, the title links to a Google Scholar search and should be replaced with an official paper page when available.

