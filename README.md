# Awesome Interactive Conversational Digital Humans

A curated list of papers and resources for the survey **Interactive Visual Embodiment for Conversational Digital Humans**.

> This repository is under active construction. Papers are organized according to the section in which they are cited in the current survey draft. Each paper title includes a link to the DOI, official page, arXiv/OpenReview page, or a Google Scholar search when no stable direct link is available.

## Contents

- [Introduction](#introduction)
- [Background](#background)
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
- [Datasets and Evaluation](#datasets-and-evaluation)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  - [Evaluation](#evaluation)
    - [Visual Quality](#visual-quality)
    - [Response Appropriateness](#response-appropriateness)
    - [User Experience](#user-experience)

---

# Introduction

- **[Synthesizing Obama: learning lip sync from audio](https://scholar.google.com/scholar?q=Synthesizing+Obama%3A+learning+lip+sync+from+audio)** — *ACM TOG 2017*

- **[A Survey of Talking Head Synthesis Techniques: Portrait Generation, Driving Mechanisms, and Editing](https://scholar.google.com/scholar?q=A+Survey+of+Talking+Head+Synthesis+Techniques%3A+Portrait+Generation%2C+Driving+Mechanisms%2C+and+Editing)** — *2026*

- **[Deep Person Generation: A Survey from the Perspective of Face, Pose, and Cloth Synthesis](https://scholar.google.com/scholar?q=Deep+Person+Generation%3A+A+Survey+from+the+Perspective+of+Face%2C+Pose%2C+and+Cloth+Synthesis)** — *2023*

- **[Talking Human Face Generation: A Survey](https://scholar.google.com/scholar?q=Talking+Human+Face+Generation%3A+A+Survey)** — *Expert Systems with Applications 2023*

- **[Human–Computer Interaction System: A Survey of Talking-Head Generation](https://scholar.google.com/scholar?q=Human%E2%80%93Computer+Interaction+System%3A+A+Survey+of+Talking-Head+Generation)** — *Electronics 2023*

- **[A survey on generative nonverbal facial behavior for highly realistic embodied agents](https://scholar.google.com/scholar?q=A+survey+on+generative+nonverbal+facial+behavior+for+highly+realistic+embodied+agents)** — *Intelligent Service Robotics 2026*

- **[A Comprehensive Review of Data-Driven Co-Speech Gesture Generation](https://scholar.google.com/scholar?q=A+Comprehensive+Review+of+Data-Driven+Co-Speech+Gesture+Generation)** — *Computer Graphics Forum 2023*

- **[Human Motion Generation: A Survey](https://scholar.google.com/scholar?q=Human+Motion+Generation%3A+A+Survey)** — *IEEE TPAMI 2024*

- **[Virtual Human: A Comprehensive Survey on Academic and Applications](https://scholar.google.com/scholar?q=Virtual+Human%3A+A+Comprehensive+Survey+on+Academic+and+Applications)** — *IEEE Access 2023*

- **[The interaction design of 3D virtual humans: A survey](https://scholar.google.com/scholar?q=The+interaction+design+of+3D+virtual+humans%3A+A+survey)** — *Computer Science Review 2024*

- **[Embodied Conversational Agents in Extended Reality: A Systematic Review](https://scholar.google.com/scholar?q=Embodied+Conversational+Agents+in+Extended+Reality%3A+A+Systematic+Review)** — *IEEE Access 2025*

---

# Background

No external papers are cited in the current draft's **Key Concepts** or **Problem Formulation** subsections.

---

# Tasks

## Speaking Behavior Generation

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Synthesizing Obama: learning lip sync from audio](https://scholar.google.com/scholar?q=Synthesizing+Obama%3A+learning+lip+sync+from+audio)** — *ACM TOG 2017*

- **[You Said That?: Synthesising Talking Faces from Audio](https://doi.org/10.1007/s11263-019-01150-y)** — *IJCV 2019*

- **[Lip Movements Generation at a Glance](https://doi.org/10.1007/978-3-030-01234-2_32)** — *ECCV 2018*

- **[MakeItTalk: Speaker-Aware Talking-Head Animation](https://doi.org/10.1145/3414685.3417774)** — *ACM TOG 2020*

- **[Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://doi.org/10.24963/ijcai.2021/152)** — *IJCAI 2021*

- **[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://doi.org/10.1109/CVPR52729.2023.00836)** — *CVPR 2023*

- **[Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/abs/2406.08801)** — *arXiv 2024*

- **[MeshTalk: 3D Face Animation from Speech using Cross-Modality Disentanglement](https://doi.org/10.1109/ICCV48922.2021.00121)** — *ICCV 2021*

- **[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://doi.org/10.1109/CVPR52688.2022.01821)** — *CVPR 2022*

- **[EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://doi.org/10.1109/ICCV51070.2023.01891)** — *ICCV 2023*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **[SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://doi.org/10.1145/3581783.3611734)** — *ACM MM 2023*

- **[ScanTalk: 3D Talking Heads from Unregistered Scans](https://doi.org/10.1007/978-3-031-73397-0_2)** — *ECCV 2025*

- **[First Order Motion Model for Image Animation](https://scholar.google.com/scholar?q=First+Order+Motion+Model+for+Image+Animation)** — *NeurIPS 2019*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://doi.org/10.1109/CVPR46437.2021.00991)** — *CVPR 2021*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

## Listening Behavior Generation

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://doi.org/10.1145/3581783.3612123)** — *ACM MM 2023*

- **[Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation](https://doi.org/10.1109/ICCV51070.2023.01905)** — *ICCV 2023*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[VividListener: Expressive and Controllable Listener Dynamics Modeling for Multi-Modal Responsive Interaction](https://scholar.google.com/scholar?q=VividListener%3A+Expressive+and+Controllable+Listener+Dynamics+Modeling+for+Multi-Modal+Responsive+Interaction)** — *AAAI 2026*

- **[Can Language Models Learn to Listen?](https://scholar.google.com/scholar?q=Can+Language+Models+Learn+to+Listen%3F)** — *ICCV 2023*

- **[DIM: Dyadic Interaction Modeling for Social Behavior Generation](https://scholar.google.com/scholar?q=DIM%3A+Dyadic+Interaction+Modeling+for+Social+Behavior+Generation)** — *ECCV 2024*

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://doi.org/10.1109/CVPR52734.2025.00996)** — *CVPR 2025*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010)** — *ICCV 2025*

- **[Diffusion-based Realistic Listening Head Generation via Hybrid Motion Modeling](https://doi.org/10.1109/CVPR52734.2025.01481)** — *CVPR 2025*

- **[REA-Listener: Real-Time Listening Head Generation with Dynamic Emotion Modeling and Flexible Modality Adaptation](https://doi.org/10.1145/3746027.3755093)** — *ACM MM 2025*

## Bidirectional Interaction

### Role Transition

- **[Interactive Conversational Head Generation](https://doi.org/10.1109/TPAMI.2025.3562651)** — *IEEE TPAMI 2025*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://arxiv.org/abs/2505.18096)** — *CVPR 2025*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/abs/2412.04037)** — *CVPR 2025*

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://arxiv.org/abs/2507.00472)** — *ICCV 2025*

- **[Towards Flexible, Natural, Efficient Interaction for Conversational Talking Face Generation](https://arxiv.org/abs/2606.31088)** — *arXiv 2026*

### Turn-Taking and Interruption

- **[TurnGPT: a Transformer-based Language Model for Predicting Turn-taking in Spoken Dialog](https://doi.org/10.18653/v1/2020.findings-emnlp.268)** — *Findings of ACL 2020*

- **[Voice Activity Projection: Self-supervised Learning of Turn-taking Events](https://doi.org/10.21437/Interspeech.2022-10955)** — *INTERSPEECH 2022*

- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals](https://doi.org/10.18653/v1/2025.acl-long.743)** — *ACL 2025*

- **[Language Model Can Listen While Speaking](https://doi.org/10.1609/aaai.v39i23.34665)** — *AAAI 2025*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://doi.org/10.18653/v1/2025.acl-long.709)** — *ACL 2025*

### Conversational Continuity and Context Modeling

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://arxiv.org/abs/2601.02103)** — *CVPR 2026*

- **[Towards Seamless Interaction: Causal Turn-Level Modeling of Interactive 3D Conversational Head Dynamics](https://arxiv.org/abs/2512.15340)** — *arXiv 2026*

- **[Echo: Enhancing Conversational Behavior Generation via Hierarchical Semantic Comprehension with Large Language Models](https://doi.org/10.1145/3757377.3763998)** — *SIGGRAPH Asia 2025*

- **[Social Agent: Mastering Dyadic Nonverbal Behavior Generation via Conversational LLM Agents](https://doi.org/10.1145/3757377.3763879)** — *SIGGRAPH Asia 2025*

- **[ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation](https://arxiv.org/abs/2603.17427)** — *arXiv 2026*

### Full-Duplex Interaction

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://doi.org/10.18653/v1/2024.emnlp-main.1192)** — *EMNLP 2024*

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Model](https://doi.org/10.52202/079017-0427)** — *NeurIPS 2024*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://doi.org/10.18653/v1/2025.acl-long.709)** — *ACL 2025*

---

# Techniques

## Multimodal Perception

### Speech and Language Signals

- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)** — *2023*

- **[wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477)** — *NeurIPS 2020*

- **[HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://doi.org/10.1109/TASLP.2021.3122291)** — *IEEE/ACM TASLP 2021*

- **[WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing](https://doi.org/10.1109/JSTSP.2022.3188113)** — *IEEE JSTSP 2022*

- **[Qwen2-Audio Technical Report](https://arxiv.org/abs/2407.10759)** — *arXiv 2024*

- **[Advancing Large Language Models to Capture Varied Speaking Styles and Respond Properly in Spoken Conversations](https://scholar.google.com/scholar?q=Advancing+Large+Language+Models+to+Capture+Varied+Speaking+Styles+and+Respond+Properly+in+Spoken+Conversations)** — *ACL 2024*

- **[Speech Recognition Meets Large Language Model: Benchmarking, Models, and Exploration](https://scholar.google.com/scholar?q=Speech+Recognition+Meets+Large+Language+Model%3A+Benchmarking%2C+Models%2C+and+Exploration)** — *AAAI 2025*

- **[SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://arxiv.org/abs/2310.13289)** — *ICLR 2024*

- **[Let’s Go Real Talk: Spoken Dialogue Model for Face-to-Face Conversation](https://scholar.google.com/scholar?q=Let%E2%80%99s+Go+Real+Talk%3A+Spoken+Dialogue+Model+for+Face-to-Face+Conversation)** — *ACL 2024*

- **[AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://doi.org/10.18653/v1/2024.acl-long.521)** — *ACL 2024*

- **[SPIRIT-LM: Interleaved Spoken and Written Language Model](https://doi.org/10.1162/tacl_a_00728)** — *TACL 2025*

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

### Visual Signals

- **[OpenFace: An Open Source Facial Behavior Analysis Toolkit](https://doi.org/10.1109/WACV.2016.7477553)** — *2016*

- **[OpenFace 3.0: A Lightweight Multitask System for Comprehensive Facial Behavior Analysis](https://scholar.google.com/scholar?q=OpenFace+3.0%3A+A+Lightweight+Multitask+System+for+Comprehensive+Facial+Behavior+Analysis)** — *2025*

- **[Gaze-LLE: Gaze Target Estimation via Large-Scale Learned Encoders](https://arxiv.org/abs/2412.09586)** — *2025*

- **[Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields](https://scholar.google.com/scholar?q=Realtime+Multi-Person+2D+Pose+Estimation+Using+Part+Affinity+Fields)** — *2017*

- **[ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation](https://doi.org/10.52202/068431-2795)** — *NeurIPS 2022*

- **[RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation](https://arxiv.org/abs/2312.07526)** — *CVPR 2024*

- **[Sapiens: Foundation for Human Vision Models](https://scholar.google.com/scholar?q=Sapiens%3A+Foundation+for+Human+Vision+Models)** — *ECCV 2024*

- **[AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection](https://scholar.google.com/scholar?q=AVA+Active+Speaker%3A+An+Audio-Visual+Dataset+for+Active+Speaker+Detection)** — *ICASSP 2020*

- **[Is Someone Speaking? Exploring Long-Term Temporal Features for Audio-Visual Active Speaker Detection](https://scholar.google.com/scholar?q=Is+Someone+Speaking%3F+Exploring+Long-Term+Temporal+Features+for+Audio-Visual+Active+Speaker+Detection)** — *ACM MM 2021*

- **[Learning Long-Term SpatialTemporal Graphs for Active Speaker Detection](https://scholar.google.com/scholar?q=Learning+Long-Term+SpatialTemporal+Graphs+for+Active+Speaker+Detection)** — *ECCV 2022*

- **[A Light Weight Model for Active Speaker Detection](https://scholar.google.com/scholar?q=A+Light+Weight+Model+for+Active+Speaker+Detection)** — *CVPR 2023*

- **[LoCoNet: Long-Short Context Network for Active Speaker Detection](https://doi.org/10.1109/CVPR52733.2024.01747)** — *CVPR 2024*

## Understanding and Planning

### Dialogue and Context Understanding

- **[A Simple Language Model for Task-Oriented Dialogue](https://scholar.google.com/scholar?q=A+Simple+Language+Model+for+Task-Oriented+Dialogue)** — *NeurIPS 2020*

- **[SUMBT: Slot-Utterance Matching for Universal and Scalable Belief Tracking](https://scholar.google.com/scholar?q=SUMBT%3A+Slot-Utterance+Matching+for+Universal+and+Scalable+Belief+Tracking)** — *ACL 2019*

- **[TRADE: Transferable Multi-Domain State Generator for Task-Oriented Dialogue Systems](https://doi.org/10.18653/v1/P19-1078)** — *ACL 2019*

- **[Description-Driven Dialogue State Tracking](https://doi.org/10.18653/v1/2022.sigdial-1.22)** — *SIGDIAL 2022*

- **[GSN: A Graph-Structured Network for Multi-Party Dialogues](https://scholar.google.com/scholar?q=GSN%3A+A+Graph-Structured+Network+for+Multi-Party+Dialogues)** — *IJCAI 2019*

- **[GIFT: Graph-Induced Fine-Tuning for MultiParty Conversation Understanding](https://scholar.google.com/scholar?q=GIFT%3A+Graph-Induced+Fine-Tuning+for+MultiParty+Conversation+Understanding)** — *ACL 2023*

- **[MPC-BERT: A PreTrained Language Model for Multi-Party Conversation Understanding](https://scholar.google.com/scholar?q=MPC-BERT%3A+A+PreTrained+Language+Model+for+Multi-Party+Conversation+Understanding)** — *ACL 2021*

- **[Friends-MMC: A Dataset for Multi-Modal Multi-Party Conversation Understanding](https://scholar.google.com/scholar?q=Friends-MMC%3A+A+Dataset+for+Multi-Modal+Multi-Party+Conversation+Understanding)** — *AAAI 2025*

- **[Audio Visual Scene-Aware Dialog](https://scholar.google.com/scholar?q=Audio+Visual+Scene-Aware+Dialog)** — *CVPR 2019*

- **[SIMMC 2.0: A Task-Oriented Dialog Dataset for Immersive Multimodal Conversations](https://scholar.google.com/scholar?q=SIMMC+2.0%3A+A+Task-Oriented+Dialog+Dataset+for+Immersive+Multimodal+Conversations)** — *EMNLP 2021*

- **[MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs](https://scholar.google.com/scholar?q=MMDU%3A+A+Multi-Turn+Multi-Image+Dialog+Understanding+Benchmark+and+Instruction-Tuning+Dataset+for+LVLMs)** — *NeurIPS 2024*

- **[VSTAR: A Video-Grounded Dialogue Dataset for Situated Semantic Understanding with Scene and Topic Transitions](https://scholar.google.com/scholar?q=VSTAR%3A+A+Video-Grounded+Dialogue+Dataset+for+Situated+Semantic+Understanding+with+Scene+and+Topic+Transitions)** — *ACL 2023*

- **[Generative Agents: Interactive Simulacra of Human Behavior](https://scholar.google.com/scholar?q=Generative+Agents%3A+Interactive+Simulacra+of+Human+Behavior)** — *UIST 2023*

- **[Beyond Goldfish Memory: Long-Term Open-Domain Conversation](https://doi.org/10.18653/v1/2022.acl-long.356)** — *ACL 2022*

- **[MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation](https://scholar.google.com/scholar?q=MemoChat%3A+Tuning+LLMs+to+Use+Memos+for+Consistent+Long-Range+Open-Domain+Conversation)** — *arXiv 2023*

- **[MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://doi.org/10.1609/aaai.v38i17.29946)** — *AAAI 2024*

- **[On Memory Construction and Retrieval for Personalized Conversational Agents](https://scholar.google.com/scholar?q=On+Memory+Construction+and+Retrieval+for+Personalized+Conversational+Agents)** — *ICLR 2025*

- **[Evaluating Very Long-Term Conversational Memory of LLM Agents](https://scholar.google.com/scholar?q=Evaluating+Very+Long-Term+Conversational+Memory+of+LLM+Agents)** — *ACL 2024*

- **[LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://openreview.net/forum?id=Q4Y1cs8hrZ)** — *ICLR 2025*

### Emotion and Intent Modeling

- **[MMGCN: Multimodal Fusion via Deep Graph Convolution Network for Emotion Recognition in Conversation](https://scholar.google.com/scholar?q=MMGCN%3A+Multimodal+Fusion+via+Deep+Graph+Convolution+Network+for+Emotion+Recognition+in+Conversation)** — *ACL 2021*

- **[COGMEN: COntextualized GNN Based Multimodal Emotion RecognitioN](https://scholar.google.com/scholar?q=COGMEN%3A+COntextualized+GNN+Based+Multimodal+Emotion+RecognitioN)** — *NAACL 2022*

- **[Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning with Instruction Tuning](https://scholar.google.com/scholar?q=Emotion-LLaMA%3A+Multimodal+Emotion+Recognition+and+Reasoning+with+Instruction+Tuning)** — *NeurIPS 2024*

- **[SemEval-2024 Task 3: Multimodal Emotion Cause Analysis in Conversations](https://doi.org/10.18653/v1/2024.semeval-1.277)** — *SemEval 2024*

- **[MIntRec: A New Dataset for Multimodal Intent Recognition](https://doi.org/10.1145/3503161.3547906)** — *ACM MM 2022*

- **[MIntRec2.0: A Large-Scale Benchmark Dataset for Multimodal Intent Recognition and Out-of-Scope Detection in Conversations](https://openreview.net/forum?id=JbL9f9XeI2)** — *ICLR 2024*

## Generation and Rendering

### Behavior Representations

#### Two-Dimensional Representations

- **[Animating Arbitrary Objects via Deep Motion Transfer](https://openaccess.thecvf.com/content_CVPR_2019/html/Siarohin_Animating_Arbitrary_)** — *CVPR 2019*

- **[First Order Motion Model for Image Animation](https://scholar.google.com/scholar?q=First+Order+Motion+Model+for+Image+Animation)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

#### Three-Dimensional Representations

- **[A Morphable Model for the Synthesis of 3D Faces](https://doi.org/10.1145/311535.311556)** — *SIGGRAPH 1999*

- **[FaceWarehouse: A 3D Facial Expression Database for Visual Computing](https://doi.org/10.1109/TVCG.2013.249)** — *2014*

- **[Face Transfer with Multilinear Models](https://scholar.google.com/scholar?q=Face+Transfer+with+Multilinear+Models)** — *ACM TOG 2005*

- **[Learning a Model of Facial Shape and Expression from 4D Scans](https://doi.org/10.1145/3130800.3130813)** — *ACM TOG 2017*

- **[FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction](https://scholar.google.com/scholar?q=FaceScape%3A+A+Large-Scale+High+Quality+3D+Face+Dataset+and+Detailed+Riggable+3D+Face+Prediction)** — *CVPR 2020*

- **[Learning an Animatable Detailed 3D Face Model from In-the-Wild Images](https://scholar.google.com/scholar?q=Learning+an+Animatable+Detailed+3D+Face+Model+from+In-the-Wild+Images)** — *ACM TOG 2021*

- **[SMPL: A Skinned Multi-Person Linear Model](https://doi.org/10.1145/2816795.2818013)** — *ACM TOG 2015*

- **[Expressive Body Capture: 3D Hands, Face, and Body from a Single Image](https://doi.org/10.1109/CVPR.2019.01123)** — *CVPR 2019*

#### Learned Discrete Motion Representations

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **[T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations](https://scholar.google.com/scholar?q=T2M-GPT%3A+Generating+Human+Motion+from+Textual+Descriptions+with+Discrete+Representations)** — *CVPR 2023*

### Generative Models

#### Generative Adversarial Models

- **[Generative Adversarial Nets](https://scholar.google.com/scholar?q=Generative+Adversarial+Nets)** — *NeurIPS 2014*

- **[Image-to-Image Translation with Conditional Adversarial Networks](https://doi.org/10.1109/CVPR.2017.632)** — *2017*

- **[HeadGAN: One-Shot Neural Head Synthesis and Editing](https://openaccess.thecvf.com/content/ICCV2021/html/Doukas_HeadGAN_One-Shot_Neural_Head_)** — *ICCV 2021*

- **[Few-Shot Adversarial Learning of Realistic Neural Talking Head Models](https://doi.org/10.1109/ICCV.2019.00955)** — *ICCV 2019*

- **[Speech-Driven Facial Animation Using Cascaded GANs for Learning of Motion and Texture](https://scholar.google.com/scholar?q=Speech-Driven+Facial+Animation+Using+Cascaded+GANs+for+Learning+of+Motion+and+Texture)** — *ECCV 2020*

- **[FLNet: Landmark Driven Fetching and Learning Network for Faithful Talking Facial Animation Synthesis](https://scholar.google.com/scholar?q=FLNet%3A+Landmark+Driven+Fetching+and+Learning+Network+for+Faithful+Talking+Facial+Animation+Synthesis)** — *AAAI 2020*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

#### Latent-Variable Models

- **[Audio2Gestures: Generating Diverse Gestures from Speech Audio with Conditional Variational Autoencoders](https://scholar.google.com/scholar?q=Audio2Gestures%3A+Generating+Diverse+Gestures+from+Speech+Audio+with+Conditional+Variational+Autoencoders)** — *ICCV 2021*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation](https://doi.org/10.1109/ICCV51070.2023.01905)** — *ICCV 2023*

- **[Generating Holistic 3D Human Motion from Speech](https://scholar.google.com/scholar?q=Generating+Holistic+3D+Human+Motion+from+Speech)** — *CVPR 2023*

#### Autoregressive Models

- **[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://doi.org/10.1109/CVPR52688.2022.01821)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://doi.org/10.1109/CVPR52729.2023.01229)** — *CVPR 2023*

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[Generating Holistic 3D Human Motion from Speech](https://scholar.google.com/scholar?q=Generating+Holistic+3D+Human+Motion+from+Speech)** — *CVPR 2023*

#### Diffusion Models

- **[Denoising Diffusion Probabilistic Models](https://scholar.google.com/scholar?q=Denoising+Diffusion+Probabilistic+Models)** — *NeurIPS 2020*

- **[DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://doi.org/10.1109/CVPR52729.2023.00197)** — *CVPR 2023*

- **[Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://scholar.google.com/scholar?q=Diffused+Heads%3A+Diffusion+Models+Beat+GANs+on+Talking-Face+Generation)** — *WACV 2024*

- **[MoDiTalker: Motion-Disentangled Diffusion Model for High-Fidelity Talking Head Generation](https://scholar.google.com/scholar?q=MoDiTalker%3A+Motion-Disentangled+Diffusion+Model+for+High-Fidelity+Talking+Head+Generation)** — *AAAI 2025*

- **[DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models](https://scholar.google.com/scholar?q=DiffPoseTalk%3A+Speech-Driven+Stylistic+3D+Facial+Animation+and+Head+Pose+Generation+via+Diffusion+Models)** — *ACM TOG 2024*

- **[DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-Driven Holistic 3D Expression and Gesture Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_DiffSHEG_A_Diffusion-Based_Approach_)** — *CVPR 2024*

- **[DiffuseStyleGesture: Stylized Audio-Driven Co-Speech Gesture Generation with Diffusion Models](https://doi.org/10.24963/ijcai.2023/650)** — *IJCAI 2023*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://doi.org/10.1145/3581783.3612123)** — *ACM MM 2023*

### Two-Dimensional Visual Synthesis

#### Motion Field Warping and Inpainting

- **[First Order Motion Model for Image Animation](https://scholar.google.com/scholar?q=First+Order+Motion+Model+for+Image+Animation)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://openaccess.thecvf.com/content/CVPR2022/html/Hong_Depth-Aware_Generative_Adversarial_)** — *CVPR 2022*

- **[Audio-Visual Face Reenactment](https://openaccess.thecvf.com/content/WACV2023/html/Agarwal_Audio-Visual_Face_Reenactment_WACV_2023_paper.html)** — *WACV 2023*

- **[LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/abs/2407.03168)** — *arXiv 2024*

#### Feed-Forward Image Synthesis

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Progressive Disentangled Representation Learning for Fine-Grained Controllable Talking Head Synthesis](https://scholar.google.com/scholar?q=Progressive+Disentangled+Representation+Learning+for+Fine-Grained+Controllable+Talking+Head+Synthesis)** — *CVPR 2023*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://doi.org/10.1109/CVPR46437.2021.00416)** — *CVPR 2021*

- **[StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-Based Generator](https://scholar.google.com/scholar?q=StyleSync%3A+High-Fidelity+Generalized+and+Personalized+Lip+Sync+in+Style-Based+Generator)** — *CVPR 2023*

- **[StyleLipSync: Style-based Personalized Lip-sync Video Generation](https://scholar.google.com/scholar?q=StyleLipSync%3A+Style-based+Personalized+Lip-sync+Video+Generation)** — *ICCV 2023*

#### Diffusion-Based Video Synthesis

- **[DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://doi.org/10.1109/CVPR52729.2023.00197)** — *CVPR 2023*

- **[HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation](https://scholar.google.com/scholar?q=HunyuanPortrait%3A+Implicit+Condition+Control+for+Enhanced+Portrait+Animation)** — *CVPR 2025*

- **[Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Video Diffusion Transformer](https://scholar.google.com/scholar?q=Hallo3%3A+Highly+Dynamic+and+Realistic+Portrait+Image+Animation+with+Video+Diffusion+Transformer)** — *CVPR 2025*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://scholar.google.com/scholar?q=DiTaiListener%3A+Controllable+High+Fidelity+Listener+Video+Generation+with+Diffusion)** — *ICCV 2025*

### Three-Dimensional Avatar Rendering

#### Mesh-Based Rendering

- **[Neural Voice Puppetry: Audio-driven Facial Reenactment](https://scholar.google.com/scholar?q=Neural+Voice+Puppetry%3A+Audio-driven+Facial+Reenactment)** — *ECCV 2020*

- **[Neural Head Avatars from Monocular RGB Videos](https://scholar.google.com/scholar?q=Neural+Head+Avatars+from+Monocular+RGB+Videos)** — *CVPR 2022*

- **[Learning Dynamic Tetrahedra for High-Quality Talking Head Synthesis](https://scholar.google.com/scholar?q=Learning+Dynamic+Tetrahedra+for+High-Quality+Talking+Head+Synthesis)** — *CVPR 2024*

- **[Towards High-fidelity 3D Talking Avatar with Personalized Dynamic Texture](https://scholar.google.com/scholar?q=Towards+High-fidelity+3D+Talking+Avatar+with+Personalized+Dynamic+Texture)** — *CVPR 2025*

#### Neural Radiance Fields

- **[AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://scholar.google.com/scholar?q=AD-NeRF%3A+Audio+Driven+Neural+Radiance+Fields+for+Talking+Head+Synthesis)** — *ICCV 2021*

- **[GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://scholar.google.com/scholar?q=GeneFace%3A+Generalized+and+High-Fidelity+Audio-Driven+3D+Talking+Face+Synthesis)** — *ICLR 2023*

- **[One-Shot High-Fidelity Talking-Head Synthesis with Deformable Neural Radiance Field](https://scholar.google.com/scholar?q=One-Shot+High-Fidelity+Talking-Head+Synthesis+with+Deformable+Neural+Radiance+Field)** — *CVPR 2023*

- **[Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis](https://scholar.google.com/scholar?q=Efficient+Region-Aware+Neural+Radiance+Fields+for+High-Fidelity+Talking+Portrait+Synthesis)** — *ICCV 2023*

- **[SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis](https://scholar.google.com/scholar?q=SyncTalk%3A+The+Devil+is+in+the+Synchronization+for+Talking+Head+Synthesis)** — *CVPR 2024*

- **[S3D-NeRF: Single-Shot Speech-Driven Neural Radiance Field for High Fidelity Talking Head Synthesis](https://scholar.google.com/scholar?q=S3D-NeRF%3A+Single-Shot+Speech-Driven+Neural+Radiance+Field+for+High+Fidelity+Talking+Head+Synthesis)** — *ECCV 2024*

#### 3D Gaussian Splatting

- **[GaussianTalker: Real-Time Talking Head Synthesis with 3D Gaussian Splatting](https://doi.org/10.1145/3664647.3681627)** — *ACM MM 2024*

- **[GaussianSpeech: Audio-Driven Personalized 3D Gaussian Avatars](https://scholar.google.com/scholar?q=GaussianSpeech%3A+Audio-Driven+Personalized+3D+Gaussian+Avatars)** — *ICCV 2025*

- **[DGTalker: Disentangled Generative Latent Space Learning for Audio-Driven Gaussian Talking Heads](https://scholar.google.com/scholar?q=DGTalker%3A+Disentangled+Generative+Latent+Space+Learning+for+Audio-Driven+Gaussian+Talking+Heads)** — *ICCV 2025*

- **[InsTaG: Learning Personalized 3D Talking Head from Few-Second Video](https://scholar.google.com/scholar?q=InsTaG%3A+Learning+Personalized+3D+Talking+Head+from+Few-Second+Video)** — *CVPR 2025*

- **[GGTalker: Talking Head Systhesis with Generalizable Gaussian Priors and Identity-Specific Adaptation](https://scholar.google.com/scholar?q=GGTalker%3A+Talking+Head+Systhesis+with+Generalizable+Gaussian+Priors+and+Identity-Specific+Adaptation)** — *ICCV 2025*

- **[Monocular and Generalizable Gaussian Talking Head Animation](https://scholar.google.com/scholar?q=Monocular+and+Generalizable+Gaussian+Talking+Head+Animation)** — *CVPR 2025*

- **[TaoAvatar: Real-Time Lifelike Full-Body Talking Avatars for Augmented Reality via 3D Gaussian Splatting](https://scholar.google.com/scholar?q=TaoAvatar%3A+Real-Time+Lifelike+Full-Body+Talking+Avatars+for+Augmented+Reality+via+3D+Gaussian+Splatting)** — *CVPR 2025*

---

# Datasets and Evaluation

## Datasets and Benchmarks

- **[Capture, Learning, and Synthesis of 3D Speaking Styles](https://doi.org/10.1109/CVPR.2019.01034)** — *CVPR 2019*

- **[A 3-D Audio-Visual Corpus of Affective Communication](https://doi.org/10.1109/TMM.2010.2052239)** — *IEEE TMM 2010*

- **[VoxCeleb2: Deep Speaker Recognition](https://doi.org/10.21437/Interspeech.2018-1929)** — *INTERSPEECH 2018*

- **[Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://doi.org/10.1109/CVPR46437.2021.00366)** — *CVPR 2021*

- **[TalkVid: A Large-Scale Diversified Dataset for Audio-Driven Talking Head Synthesis](https://arxiv.org/abs/2508.13618)** — *CVPR 2026*

- **[Deep Audio-Visual Speech Recognition](https://doi.org/10.1109/TPAMI.2018.2889052)** — *IEEE TPAMI 2022*

- **[LRS3-TED: A Large-Scale Dataset for Visual Speech Recognition](https://arxiv.org/abs/1809.00496)** — *arXiv 2018*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[REACT2023: The First Multiple Appropriate Facial Reaction Generation Challenge](https://doi.org/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[Interactive Conversational Head Generation](https://doi.org/10.1109/TPAMI.2025.3562651)** — *IEEE TPAMI 2025*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://arxiv.org/abs/2505.18096)** — *CVPR 2025*

- **[SpeakerVid-5M: A Large-Scale High-Quality Dataset for Audio-Visual Dyadic Interactive Human Generation](https://proceedings.iclr.cc/paper_files/paper/2026/hash/bf7dbac50ed7f6e12ad529c5b9396bc4-Abstract-Conference.html)** — *ICLR 2026*

- **[Multi-TPC: A Multimodal Dataset for Three-Party Conversations with Speech, Motion, and Gaze](https://doi.org/10.1038/s41597-026-06819-x)** — *Scientific Data 2026*

- **[REACT 2025: The Third Multiple Appropriate Facial Reaction Generation Challenge](https://doi.org/10.1145/3746027.3762244)** — *ACM MM 2025*

- **[Full-Duplex-Bench: A Benchmark to Evaluate Full-Duplex Spoken Dialogue Models on Turn-taking Capabilities](https://scholar.google.com/scholar?q=Full-Duplex-Bench%3A+A+Benchmark+to+Evaluate+Full-Duplex+Spoken+Dialogue+Models+on+Turn-taking+Capabilities)** — *ASRU 2025*

- **[VideoFDB: Evaluating Full-Duplex Vision-Speech Capabilities in Conversational Agents](https://arxiv.org/abs/2605.30256)** — *arXiv 2026*

## Evaluation

### Visual Quality

- **[Image Quality Assessment: From Error Visibility to Structural Similarity](https://doi.org/10.1109/TIP.2003.819861)** — *IEEE TIP 2004*

- **[The Unreasonable Effectiveness of Deep Features as a Perceptual Metric](https://scholar.google.com/scholar?q=The+Unreasonable+Effectiveness+of+Deep+Features+as+a+Perceptual+Metric)** — *CVPR 2018*

- **[GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium](https://scholar.google.com/scholar?q=GANs+Trained+by+a+Two+Time-Scale+Update+Rule+Converge+to+a+Local+Nash+Equilibrium)** — *NeurIPS 2017*

- **[Towards Accurate Generative Models of Video: A New Metric & Challenges](https://arxiv.org/abs/1812.01717)** — *arXiv 2018*

- **[Out of Time: Automated Lip Sync in the Wild](https://scholar.google.com/scholar?q=Out+of+Time%3A+Automated+Lip+Sync+in+the+Wild)** — *ACCV Workshop 2016*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://doi.org/10.1145/3394171.3413532)** — *ACM MM 2020*

### Response Appropriateness

- **[Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://arxiv.org/abs/2204.08451)** — *CVPR 2022*

- **[REACT2023: The First Multiple Appropriate Facial Reaction Generation Challenge](https://doi.org/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://scholar.google.com/scholar?q=LLM-driven+Multimodal+and+Multi-Identity+Listening+Head+Generation)** — *CVPR 2025*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://scholar.google.com/scholar?q=Beyond+Turn-Based+Interfaces%3A+Synchronous+LLMs+as+Full-Duplex+Dialogue+Agents)** — *EMNLP 2024*

- **[Full-Duplex-Bench: A Benchmark to Evaluate Full-Duplex Spoken Dialogue Models on Turn-taking Capabilities](https://scholar.google.com/scholar?q=Full-Duplex-Bench%3A+A+Benchmark+to+Evaluate+Full-Duplex+Spoken+Dialogue+Models+on+Turn-taking+Capabilities)** — *arXiv 2025*

### User Experience

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://arxiv.org/abs/2403.00274)** — *CVPR 2024*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://scholar.google.com/scholar?q=Beyond+Turn-Based+Interfaces%3A+Synchronous+LLMs+as+Full-Duplex+Dialogue+Agents)** — *EMNLP 2024*

---

## Contributing

Contributions are welcome. If you find a relevant paper or notice a broken link, please open an issue or submit a pull request.
