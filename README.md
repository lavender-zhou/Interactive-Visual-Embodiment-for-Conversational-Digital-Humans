# Awesome Interactive Digital Humans

A curated list of papers and resources for the survey **Interactive Visual Embodiment for Conversational Digital Humans: A Survey**.


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
  - [Interaction Modeling and Control](#interaction-modeling-and-control)
    - [Predictive Interaction Control](#predictive-interaction-control)
    - [Dyadic Conditional Generation](#dyadic-conditional-generation)
    - [Causal and Multi-Stream Modeling](#causal-and-multi-stream-modeling)
- [Datasets and Evaluation](#datasets-and-evaluation)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  - [Evaluation](#evaluation)
    - [Visual Quality](#visual-quality)
    - [Response Appropriateness](#response-appropriateness)
    - [User Experience](#user-experience)
- [Challenges and Future Directions](#challenges-and-future-directions)
  - [Challenges](#challenges)
    - [Data Scarcity](#data-scarcity)
    - [Generalization](#generalization)
    - [Ethical Risks](#ethical-risks)
  - [Future Directions](#future-directions)
    - [Long-term Memory and Persona](#long-term-memory-and-persona)
    - [Holistic Multi-party Embodiment](#holistic-multi-party-embodiment)
    - [Robust Real-Time Interaction](#robust-real-time-interaction)

---

# Introduction


- **[Using Large Language Models in Psychology](https://www.nature.com/articles/s44159-023-00241-5)** — *Nature Reviews Psychology 2023*

- **[Proactive Conversational AI: A Comprehensive Survey of Advancements and Opportunities](https://dl.acm.org/doi/10.1145/3715097)** — *ACM TOIS 2025*

- **[Large Language Model Based Multi-Agents: A Survey of Progress and Challenges](https://www.ijcai.org/proceedings/2024/890)** — *IJCAI 2024*

- **[Exploring the Frontiers of LLMs in Psychological Applications: A Comprehensive Review](https://link.springer.com/article/10.1007/s10462-025-11297-5)** — *Artificial Intelligence Review 2025*

- **[A Survey of Talking Head Synthesis Techniques: Portrait Generation, Driving Mechanisms, and Editing](https://dl.acm.org/doi/10.1145/3785656)** — *ACM Computing Surveys(CSUR) 2026*

- **[A survey on generative nonverbal facial behavior for highly realistic embodied agents](https://link.springer.com/article/10.1007/s11370-025-00674-2)** — *Intelligent Service Robotics 2026*

- **[A Comprehensive Review of Data‐Driven Co‐Speech Gesture Generation](https://onlinelibrary.wiley.com/doi/10.1111/cgf.14776)** — *Computer Graphics Forum 2023*

- **[A Review of Eye Gaze in Virtual Agents, Social Robotics and HCI: Behaviour Generation, User Interaction and Perception](https://onlinelibrary.wiley.com/doi/10.1111/cgf.12603)** — *Computer Graphics Forum 2015*

- **[Deep Person Generation: A Survey from the Perspective of Face, Pose, and Cloth Synthesis](https://dl.acm.org/doi/10.1145/3575656)** — *2023*

- **[Talking Human Face Generation: A Survey](https://doi.org/10.1016/j.eswa.2023.119678)** — *Expert Systems with Applications 2023*

- **[A Survey on Large Language Model Based Autonomous Agents](https://link.springer.com/article/10.1007/s11704-024-40231-1?error=cookies_not_supported&code=e4d124e8-5e69-4873-8a84-b17caf0549a5)** — *Frontiers of Computer Science 2024*

- **[The interaction design of 3D virtual humans: A survey](https://doi.org/10.1016/j.cosrev.2024.100653)** — *Computer Science Review 2024*

- **[Embodied Conversational Agents in Extended Reality: A Systematic Review](https://ieeexplore.ieee.org/document/10985757/)** — *IEEE Access 2025*

- **[Human Motion Generation: A Survey](https://ieeexplore.ieee.org/document/10313063/)** — *IEEE TPAMI 2024*

- **[Deep Learning for Visual Speech Analysis: A Survey](https://doi.org/10.1109/TPAMI.2024.3376710)** — *IEEE TPAMI 2024*

- **[Deepfake Generation and Detection: A Benchmark and Survey](https://doi.org/10.1145/3801962)** — *ACM Computing Surveys 2026*

- **[Audiovisual Speech Synthesis: An Overview of the State-of-the-Art](https://doi.org/10.1016/j.specom.2014.11.001)** — *Speech Communication 2015*

- **[Face Generation and Editing With StyleGAN: A Survey](https://doi.org/10.1109/TPAMI.2024.3350004)** — *IEEE TPAMI 2024*

- **[Generative Adversarial Networks for Face Generation: A Survey](https://doi.org/10.1145/3527850)** — *ACM Computing Surveys 2023*

- **[3D Morphable Face Models—Past, Present, and Future](https://doi.org/10.1145/3395208)** — *ACM TOG 2020*

- **[Conversational Agents in Augmented Reality: A Systematic Review](https://doi.org/10.1145/3815590)** — *ACM Transactions on Interactive Intelligent Systems 2026*

- **[Examining the Use of Nonverbal Communication in Virtual Agents](https://doi.org/10.1080/10447318.2021.1898851)** — *International Journal of Human–Computer Interaction 2021*

- **[Empathy in Virtual Agents and Robots: A Survey](https://doi.org/10.1145/2912150)** — *ACM Transactions on Interactive Intelligent Systems 2017*

- **[The Effect of Design Features on Relationship Quality with Embodied Conversational Agents: A Systematic Review](https://doi.org/10.1007/s12369-020-00680-7)** — *International Journal of Social Robotics 2020*

- **[AI-powered avatar assistants: a systematic literature review of tools, application domains and challenges](https://doi.org/10.1007/s12652-026-05052-z)** — *Journal of Ambient Intelligence and Humanized Computing 2026*

- **[Computer-Controlled Virtual Humans in Patient-Facing Systems: Systematic Review and Meta-Analysis](https://www.jmir.org/2020/7/e18839/)** — *Journal of Medical Internet Research 2020*

- **[Embodied Conversational Agents for Chronic Diseases: Scoping Review](https://www.jmir.org/2024/1/e47134/)** — *Journal of Medical Internet Research 2024*

---

# Background

No external papers are cited in the current draft’s Key Concepts or Problem Formulation subsections.

# Tasks

## Speaking Behavior Generation

- **[Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/html/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.html)** — *ECCV 2018*

- **[FaceFormer: Speech-Driven 3D Facial Animation With Transformers](https://openaccess.thecvf.com/content/CVPR2022/html/Fan_FaceFormer_Speech-Driven_3D_Facial_Animation_With_Transformers_CVPR_2022_paper.html)** — *CVPR 2022*

- **[You Said That?: Synthesising Talking Faces from Audio](https://link.springer.com/article/10.1007/s11263-019-01150-y?error=cookies_not_supported&code=da7d8ef2-4ced-48e5-b038-df14bfdb977d)** — *IJCV 2019*

- **[ScanTalk: 3D Talking Heads from Unregistered Scans](https://link.springer.com/chapter/10.1007/978-3-031-73397-0_2)** — *ECCV 2024*

- **[SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://dl.acm.org/doi/10.1145/3581783.3611734)** — *ACM MM 2023*

- **[EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://openaccess.thecvf.com/content/ICCV2023/html/Peng_EmoTalk_Speech-Driven_Emotional_Disentanglement_for_3D_Face_Animation_ICCV_2023_paper.html)** — *ICCV 2023*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[MeshTalk: 3D Face Animation From Speech Using Cross-Modality Disentanglement](https://openaccess.thecvf.com/content/ICCV2021/html/Richard_MeshTalk_3D_Face_Animation_From_Speech_Using_Cross-Modality_Disentanglement_ICCV_2021_paper.html)** — *ICCV 2021*

- **[First Order Motion Model for Image Animation](https://proceedings.neurips.cc/paper_files/paper/2019/hash/31c0b36aef265d9221af80872ceb62f9-Abstract.html)** — *NeurIPS 2019*

- **[Synthesizing Obama: learning lip sync from audio](https://dl.acm.org/doi/10.1145/3072959.3073640)** — *ACM TOG 2017*

- **[Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://www.ijcai.org/proceedings/2021/152)** — *IJCAI 2021*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_One-Shot_Free-View_Neural_Talking-Head_Synthesis_for_Video_Conferencing_CVPR_2021_paper.html)** — *CVPR 2021*

- **[CodeTalker: Speech-Driven 3D Facial Animation With Discrete Motion Prior](https://openaccess.thecvf.com/content/CVPR2023/html/Xing_CodeTalker_Speech-Driven_3D_Facial_Animation_With_Discrete_Motion_Prior_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/abs/2406.08801)** — *arXiv 2024*

- **[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_SadTalker_Learning_Realistic_3D_Motion_Coefficients_for_Stylized_Audio-Driven_Single_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)** — *CVPR 2021*

- **[MakeItTalk: Speaker-Aware Talking-Head Animation](https://dl.acm.org/doi/10.1145/3414685.3417774)** — *ACM TOG 2020*

---

## Listening Behavior Generation

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://openaccess.thecvf.com/content/CVPR2025/html/Lai_LLM-driven_Multimodal_and_Multi-Identity_Listening_Head_Generation_CVPR_2025_paper.html)** — *CVPR 2025*

- **[VividListener: Expressive and Controllable Listener Dynamics Modeling for Multi-Modal Responsive Interaction](https://ojs.aaai.org/index.php/AAAI/article/view/37567)** — *AAAI 2026*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://dl.acm.org/doi/10.1145/3581783.3612123)** — *ACM MM 2023*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_CustomListener_Text-guided_Responsive_Interaction_for_User-friendly_Listening_Head_Generation_CVPR_2024_paper.html)** — *CVPR 2024*

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Can Language Models Learn to Listen?](https://openaccess.thecvf.com/content/ICCV2023/html/Ng_Can_Language_Models_Learn_to_Listen_ICCV_2023_paper.html)** — *ICCV 2023*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://openaccess.thecvf.com/content/ICCV2025/html/Siniukov_DiTaiListener_Controllable_High_Fidelity_Listener_Video_Generation_with_Diffusion_ICCV_2025_paper.html)** — *ICCV 2025*

- **[Emotional Listener Portrait: Neural Listener Head Generation with Emotion](https://openaccess.thecvf.com/content/ICCV2023/html/Song_Emotional_Listener_Portrait_Neural_Listener_Head_Generation_with_Emotion_ICCV_2023_paper.html)** — *ICCV 2023*

- **[DIM: Dyadic Interaction Modeling for Social Behavior Generation](https://link.springer.com/chapter/10.1007/978-3-031-72913-3_27)** — *ECCV 2024*

- **[Diffusion-based Realistic Listening Head Generation via Hybrid Motion Modeling](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Diffusion-based_Realistic_Listening_Head_Generation_via_Hybrid_Motion_Modeling_CVPR_2025_paper.html)** — *CVPR 2025*

- **[REA-Listener: Real-Time Listening Head Generation with Dynamic Emotion Modeling and Flexible Modality Adaptation](https://dl.acm.org/doi/10.1145/3746027.3755093)** — *ACM MM 2025*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

---

## Bidirectional Interaction

### Role Transition

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://openaccess.thecvf.com/content/ICCV2025/html/Guo_ARIG_Autoregressive_Interactive_Head_Generation_for_Real-time_Conversations_ICCV_2025_paper.html)** — *ICCV 2025*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_DualTalk_Dual-Speaker_Interaction_for_3D_Talking_Head_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

- **[Towards Flexible, Natural, Efficient Interaction for Conversational Talking Face Generation](https://arxiv.org/abs/2606.31088)** — *arXiv 2026*

- **[Interactive Conversational Head Generation](https://ieeexplore.ieee.org/document/10979678/)** — *IEEE TPAMI 2025*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Zhu_INFP_Audio-Driven_Interactive_Head_Generation_in_Dyadic_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

---

### Turn-Taking and Interruption

- **[TurnGPT: a Transformer-based Language Model for Predicting Turn-taking in Spoken Dialog](https://aclanthology.org/2020.findings-emnlp.268/)** — *Findings of ACL 2020*

- **[Voice Activity Projection: Self-supervised Learning of Turn-taking Events](https://www.isca-archive.org/interspeech_2022/ekstedt22_interspeech.html)** — *INTERSPEECH 2022*

- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals](https://aclanthology.org/2025.acl-long.743/)** — *ACL 2025*

- **[Language Model Can Listen While Speaking](https://ojs.aaai.org/index.php/AAAI/article/view/34665)** — *AAAI 2025*

---

### Conversational Continuity and Context Modeling

- **[Towards Seamless Interaction: Causal Turn-Level Modeling of Interactive 3D Conversational Head Dynamics](https://arxiv.org/abs/2512.15340)** — *arXiv 2026*

- **[ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation](https://arxiv.org/abs/2603.17427)** — *arXiv 2026*

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_MimicTalker_A_Multimodal_Interactive_and_Memory-Enhanced_Framework_for_Real-Time_Dyadic_CVPR_2026_paper.html)** — *CVPR 2026*

- **[Echo: Enhancing Conversational Behavior Generation via Hierarchical Semantic Comprehension with Large Language Models](https://dl.acm.org/doi/10.1145/3757377.3763998)** — *SIGGRAPH Asia 2025*

- **[Social Agent: Mastering Dyadic Nonverbal Behavior Generation via Conversational LLM Agents](https://dl.acm.org/doi/10.1145/3757377.3763879)** — *SIGGRAPH Asia 2025*

---

### Full-Duplex Interaction

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://aclanthology.org/2024.emnlp-main.1192/)** — *EMNLP 2024*

- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Model](https://proceedings.neurips.cc/paper_files/paper/2024/hash/180d4373aca26bd86bf45fc50d1a709f-Abstract-Conference.html)** — *NeurIPS 2024*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://aclanthology.org/2025.acl-long.709/)** — *ACL 2025*

---

# Techniques

## Multimodal Perception

### Speech and Language Signals

- **[SD-Eval: A Benchmark Dataset for Spoken Dialogue Understanding Beyond Words](https://proceedings.neurips.cc/paper_files/paper/2024/hash/681fe4ec554beabdc9c84a1780cd5a8a-Abstract-Datasets_and_Benchmarks_Track.html)** — *NeurIPS 2024*

- **[wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://proceedings.neurips.cc/paper_files/paper/2020/hash/92d1e1eb1cd6f9fba3227870bb6d7f07-Abstract.html)** — *NeurIPS 2020*

- **[HyPoradise: An Open Baseline for Generative Speech Recognition with Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2023/hash/6492267465a7ac507be1f9fd1174e78d-Abstract-Datasets_and_Benchmarks.html)** — *NeurIPS 2023*

- **[WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing](https://ieeexplore.ieee.org/document/9814838/)** — *IEEE JSTSP 2022*

- **[Qwen2-Audio Technical Report](https://arxiv.org/abs/2407.10759)** — *arXiv 2024*

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

- **[HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://ieeexplore.ieee.org/document/9585401/)** — *IEEE/ACM TASLP 2021*

- **[AudioGPT: Understanding and Generating Speech, Music, Sound, and Talking Head](https://ojs.aaai.org/index.php/AAAI/article/view/30570)** — *AAAI 2024 (Demo)*

- **[Advancing Large Language Models to Capture Varied Speaking Styles and Respond Properly in Spoken Conversations](https://aclanthology.org/2024.acl-long.358/)** — *ACL 2024*

- **[Speech Recognition Meets Large Language Model: Benchmarking, Models, and Exploration](https://ojs.aaai.org/index.php/AAAI/article/view/34666)** — *AAAI 2025*

- **[SPIRIT-LM: Interleaved Spoken and Written Language Model](https://arxiv.org/abs/2402.05755)** — *TACL 2025*

- **[Let’s Go Real Talk: Spoken Dialogue Model for Face-to-Face Conversation](https://aclanthology.org/2024.acl-long.860/)** — *ACL 2024*

- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://proceedings.mlr.press/v202/radford23a.html)** — *2023*

- **[SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://proceedings.iclr.cc/paper_files/paper/2024/hash/476ab8f369e489c04187ba84f68cfa68-Abstract-Conference.html)** — *ICLR 2024*

- **[AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://aclanthology.org/2024.acl-long.521/)** — *ACL 2024*

---

### Visual Signals

- **[OpenFace: An open source facial behavior analysis toolkit](http://ieeexplore.ieee.org/document/7477553/)** — *WACV 2016*

- **[Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields](https://openaccess.thecvf.com/content_cvpr_2017/html/Cao_Realtime_Multi-Person_2D_CVPR_2017_paper.html)** — *CVPR 2017*

- **[OpenFace 3.0: A Lightweight Multitask System for Comprehensive Facial Behavior Analysis](https://arxiv.org/abs/2506.02891)** — *FG 2025*

- **[Sapiens: Foundation for Human Vision Models](https://link.springer.com/chapter/10.1007/978-3-031-73235-5_12)** — *ECCV 2024*

- **[A Light Weight Model for Active Speaker Detection](https://openaccess.thecvf.com/content/CVPR2023/html/Liao_A_Light_Weight_Model_for_Active_Speaker_Detection_CVPR_2023_paper.html)** — *CVPR 2023*

- **[RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation](https://openaccess.thecvf.com/content/CVPR2024/html/Lu_RTMO_Towards_High-Performance_One-Stage_Real-Time_Multi-Person_Pose_Estimation_CVPR_2024_paper.html)** — *CVPR 2024*

- **[Learning Long-Term SpatialTemporal Graphs for Active Speaker Detection](https://link.springer.com/chapter/10.1007/978-3-031-19833-5_22)** — *ECCV 2022*

- **[Ava Active Speaker: An Audio-Visual Dataset for Active Speaker Detection](https://ieeexplore.ieee.org/document/9053900/)** — *ICASSP 2020*

- **[Gaze-LLE: Gaze Target Estimation via Large-Scale Learned Encoders](https://openaccess.thecvf.com/content/CVPR2025/html/Ryan_Gaze-LLE_Gaze_Target_Estimation_via_Large-Scale_Learned_Encoders_CVPR_2025_paper.html)** — *CVPR 2025*

- **[Is Someone Speaking? Exploring Long-Term Temporal Features for Audio-Visual Active Speaker Detection](https://arxiv.org/abs/2107.06592)** — *ACM MM 2021*

- **[LoCoNet: Long-Short Context Network for Active Speaker Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_LoCoNet_Long-Short_Context_Network_for_Active_Speaker_Detection_CVPR_2024_paper.html)** — *CVPR 2024*

- **[ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation](https://proceedings.neurips.cc/paper_files/paper/2022/hash/fbb10d319d44f8c3b4720873e4177c65-Abstract-Conference.html)** — *NeurIPS 2022*

---

## Understanding and Planning

### Dialogue and Context Understanding

- **[Audio Visual Scene-Aware Dialog](https://openaccess.thecvf.com/content_CVPR_2019/html/Alamri_Audio_Visual_Scene-Aware_Dialog_CVPR_2019_paper.html)** — *CVPR 2019*

- **[GIFT: Graph-Induced Fine-Tuning for MultiParty Conversation Understanding](https://aclanthology.org/2023.acl-long.651/)** — *ACL 2023*

- **[MPC-BERT: A PreTrained Language Model for Multi-Party Conversation Understanding](https://aclanthology.org/2021.acl-long.285/)** — *ACL 2021*

- **[A Simple Language Model for Task-Oriented Dialogue](https://proceedings.neurips.cc/paper_files/paper/2020/hash/e946209592563be0f01c844ab2170f0c-Abstract.html)** — *NeurIPS 2020*

- **[GSN: A Graph-Structured Network for Multi-Party Dialogues](https://www.ijcai.org/proceedings/2019/696)** — *IJCAI 2019*

- **[SIMMC 2.0: A Task-Oriented Dialog Dataset for Immersive Multimodal Conversations](https://aclanthology.org/2021.emnlp-main.401/)** — *EMNLP 2021*

- **[SUMBT: Slot-Utterance Matching for Universal and Scalable Belief Tracking](https://aclanthology.org/P19-1546/)** — *ACL 2019*

- **[MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs](https://proceedings.neurips.cc/paper_files/paper/2024/hash/1057053100de064a44286239724f7865-Abstract-Datasets_and_Benchmarks_Track.html)** — *NeurIPS 2024*

- **[MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation](https://arxiv.org/abs/2308.08239)** — *arXiv 2023*

- **[Evaluating Very Long-Term Conversational Memory of LLM Agents](https://aclanthology.org/2024.acl-long.747/)** — *ACL 2024*

- **[On Memory Construction and Retrieval for Personalized Conversational Agents](https://arxiv.org/abs/2502.05589)** — *ICLR 2025*

- **[Generative Agents: Interactive Simulacra of Human Behavior](https://dl.acm.org/doi/10.1145/3586183.3606763)** — *UIST 2023*

- **[Testing theory of mind in large language models and humans](https://www.nature.com/articles/s41562-024-01882-z)** — *Nature Human Behaviour 2024*

- **[Friends-MMC: A Dataset for Multi-modal Multi-party Conversation Understanding](https://ojs.aaai.org/index.php/AAAI/article/view/34731)** — *AAAI 2025*

- **[VSTAR: A Video-Grounded Dialogue Dataset for Situated Semantic Understanding with Scene and Topic Transitions](https://aclanthology.org/2023.acl-long.276/)** — *ACL 2023*

- **[Transferable Multi-Domain State Generator for Task-Oriented Dialogue Systems](https://aclanthology.org/P19-1078/)** — *ACL 2019*

- **[LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://proceedings.iclr.cc/paper_files/paper/2025/hash/d813d324dbf0598bbdc9c8e79740ed01-Abstract-Conference.html)** — *ICLR 2025*

- **[Beyond Goldfish Memory: Long-Term Open-Domain Conversation](https://aclanthology.org/2022.acl-long.356/)** — *ACL 2022*

- **[Description-Driven Task-Oriented Dialog Modeling](https://arxiv.org/abs/2201.08904)** — *arXiv 2022*

- **[MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://ojs.aaai.org/index.php/AAAI/article/view/29946)** — *AAAI 2024*

---

### Emotion and Intent Modeling

- **[Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning with Instruction Tuning](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c7f43ada17acc234f568dc66da527418-Abstract-Conference.html)** — *NeurIPS 2024*

- **[MMGCN: Multimodal Fusion via Deep Graph Convolution Network for Emotion Recognition in Conversation](https://aclanthology.org/2021.acl-long.440/)** — *ACL 2021*

- **[COGMEN: COntextualized GNN Based Multimodal Emotion RecognitioN](https://aclanthology.org/2022.naacl-main.306/)** — *NAACL 2022*

- **[Human–AI collaboration enables more empathic conversations in text-based peer-to-peer mental health support](https://www.nature.com/articles/s42256-022-00593-2?error=cookies_not_supported&code=eaba4a4d-0133-4a50-a483-ef6e5d82b620)** — *Nature Machine Intelligence 2023*

- **[SemEval-2024 Task 3: Multimodal Emotion Cause Analysis in Conversations](https://aclanthology.org/2024.semeval-1.277/)** — *SemEval 2024*

- **[MIntRec2.0: A Large-Scale Benchmark Dataset for Multimodal Intent Recognition and Out-of-Scope Detection in Conversations](https://proceedings.iclr.cc/paper_files/paper/2024/hash/ca97c1a8c52889c49e16497912244c3b-Abstract-Conference.html)** — *ICLR 2024*

- **[MIntRec: A New Dataset for Multimodal Intent Recognition](https://dl.acm.org/doi/10.1145/3503161.3547906)** — *ACM MM 2022*

---

## Generation and Rendering

### Behavior Representations

#### Three-Dimensional Representations

- **[A morphable model for the synthesis of 3D faces](https://dl.acm.org/doi/10.1145/311535.311556)** — *SIGGRAPH 1999*

- **[FaceWarehouse: A 3D Facial Expression Database for Visual Computing](http://ieeexplore.ieee.org/document/6654137/)** — *2014*

- **[Learning an animatable detailed 3D face model from in-the-wild images](https://dl.acm.org/doi/10.1145/3450626.3459936)** — *ACM TOG 2021*

- **[Learning a model of facial shape and expression from 4D scans](https://dl.acm.org/doi/10.1145/3130800.3130813)** — *ACM TOG 2017*

- **[SMPL: A Skinned Multi-Person Linear Model](https://dl.acm.org/doi/10.1145/2816795.2818013)** — *ACM TOG 2015*

- **[Expressive Body Capture: 3D Hands, Face, and Body From a Single Image](https://openaccess.thecvf.com/content_CVPR_2019/html/Pavlakos_Expressive_Body_Capture_3D_Hands_Face_and_Body_From_a_CVPR_2019_paper.html)** — *CVPR 2019*

- **[Face transfer with multilinear models](https://dl.acm.org/doi/10.1145/1073204.1073209)** — *ACM TOG 2005*

- **[FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction](https://openaccess.thecvf.com/content_CVPR_2020/html/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.html)** — *CVPR 2020*

#### Learned Discrete Motion Representations

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation With Discrete Motion Prior](https://openaccess.thecvf.com/content/CVPR2023/html/Xing_CodeTalker_Speech-Driven_3D_Facial_Animation_With_Discrete_Motion_Prior_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Generating Human Motion From Textual Descriptions With Discrete Representations](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Generating_Human_Motion_From_Textual_Descriptions_With_Discrete_Representations_CVPR_2023_paper.html)** — *CVPR 2023*

#### Two-Dimensional Representations

- **[Animating Arbitrary Objects via Deep Motion Transfer](https://openaccess.thecvf.com/content_CVPR_2019/html/Siarohin_Animating_Arbitrary_Objects_via_Deep_Motion_Transfer_CVPR_2019_paper.html)** — *CVPR 2019*

- **[First Order Motion Model for Image Animation](https://proceedings.neurips.cc/paper_files/paper/2019/hash/31c0b36aef265d9221af80872ceb62f9-Abstract.html)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

---

### Generative Models

#### Diffusion Models

- **[DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-driven Holistic 3D Expression and Gesture Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_DiffSHEG_A_Diffusion-Based_Approach_for_Real-Time_Speech-driven_Holistic_3D_Expression_CVPR_2024_paper.html)** — *CVPR 2024*

- **[Denoising Diffusion Probabilistic Models](https://proceedings.neurips.cc/paper_files/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)** — *NeurIPS 2020*

- **[MoDiTalker: Motion-Disentangled Diffusion Model for High-Fidelity Talking Head Generation](https://ojs.aaai.org/index.php/AAAI/article/view/32452)** — *AAAI 2025*

- **[MFR-Net: Multi-faceted Responsive Listening Head Generation via Denoising Diffusion Model](https://dl.acm.org/doi/10.1145/3581783.3612123)** — *ACM MM 2023*

- **[DiffTalk: Crafting Diffusion Models for Generalized Audio-Driven Portraits Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Shen_DiffTalk_Crafting_Diffusion_Models_for_Generalized_Audio-Driven_Portraits_Animation_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://openaccess.thecvf.com/content/WACV2024/html/Stypulkowski_Diffused_Heads_Diffusion_Models_Beat_GANs_on_Talking-Face_Generation_WACV_2024_paper.html)** — *WACV 2024*

- **[DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models](https://dl.acm.org/doi/10.1145/3658221)** — *ACM TOG 2024*

- **[DiffuseStyleGesture: Stylized Audio-Driven Co-Speech Gesture Generation with Diffusion Models](https://www.ijcai.org/proceedings/2023/650)** — *IJCAI 2023*

#### Generative Adversarial Models

- **[Speech-Driven Facial Animation Using Cascaded GANs for Learning of Motion and Texture](https://link.springer.com/chapter/10.1007/978-3-030-58577-8_25)** — *ECCV 2020*

- **[HeadGAN: One-Shot Neural Head Synthesis and Editing](https://openaccess.thecvf.com/content/ICCV2021/html/Doukas_HeadGAN_One-Shot_Neural_Head_Synthesis_and_Editing_ICCV_2021_paper.html)** — *ICCV 2021*

- **[Generative Adversarial Nets](https://papers.nips.cc/paper_files/paper/2014/hash/f033ed80deb0234979a61f95710dbe25-Abstract.html)** — *NeurIPS 2014*

- **[FLNet: Landmark Driven Fetching and Learning Network for Faithful Talking Facial Animation Synthesis](https://ojs.aaai.org/index.php/AAAI/article/view/6717)** — *AAAI 2020*

- **[Image-To-Image Translation With Conditional Adversarial Networks](https://openaccess.thecvf.com/content_cvpr_2017/html/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.html)** — *CVPR 2017*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Few-Shot Adversarial Learning of Realistic Neural Talking Head Models](https://openaccess.thecvf.com/content_ICCV_2019/html/Zakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.html)** — *ICCV 2019*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)** — *CVPR 2021*

#### Autoregressive Models

- **[FaceFormer: Speech-Driven 3D Facial Animation With Transformers](https://openaccess.thecvf.com/content/CVPR2022/html/Fan_FaceFormer_Speech-Driven_3D_Facial_Animation_With_Transformers_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[CodeTalker: Speech-Driven 3D Facial Animation With Discrete Motion Prior](https://openaccess.thecvf.com/content/CVPR2023/html/Xing_CodeTalker_Speech-Driven_3D_Facial_Animation_With_Discrete_Motion_Prior_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Generating Holistic 3D Human Motion From Speech](https://openaccess.thecvf.com/content/CVPR2023/html/Yi_Generating_Holistic_3D_Human_Motion_From_Speech_CVPR_2023_paper.html)** — *CVPR 2023*

#### Latent-Variable Models

- **[Audio2Gestures: Generating Diverse Gestures From Speech Audio With Conditional Variational Autoencoders](https://openaccess.thecvf.com/content/ICCV2021/html/Li_Audio2Gestures_Generating_Diverse_Gestures_From_Speech_Audio_With_Conditional_Variational_ICCV_2021_paper.html)** — *ICCV 2021*

- **[Emotional Listener Portrait: Neural Listener Head Generation with Emotion](https://openaccess.thecvf.com/content/ICCV2023/html/Song_Emotional_Listener_Portrait_Neural_Listener_Head_Generation_with_Emotion_ICCV_2023_paper.html)** — *ICCV 2023*

---

### Two-Dimensional Visual Synthesis

#### Motion Field Warping and Inpainting

- **[Audio-Visual Face Reenactment](https://openaccess.thecvf.com/content/WACV2023/html/Agarwal_Audio-Visual_Face_Reenactment_WACV_2023_paper.html)** — *WACV 2023*

- **[LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/abs/2407.03168)** — *arXiv 2024*

- **[Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://openaccess.thecvf.com/content/CVPR2022/html/Hong_Depth-Aware_Generative_Adversarial_Network_for_Talking_Head_Video_Generation_CVPR_2022_paper.html)** — *CVPR 2022*

- **[First Order Motion Model for Image Animation](https://proceedings.neurips.cc/paper_files/paper/2019/hash/31c0b36aef265d9221af80872ceb62f9-Abstract.html)** — *NeurIPS 2019*

- **[Thin-Plate Spline Motion Model for Image Animation](https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Thin-Plate_Spline_Motion_Model_for_Image_Animation_CVPR_2022_paper.html)** — *CVPR 2022*

#### Diffusion-Based Video Synthesis

- **[Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Video Diffusion Transformer](https://openaccess.thecvf.com/content/CVPR2025/html/Cui_Hallo3_Highly_Dynamic_and_Realistic_Portrait_Image_Animation_with_Video_CVPR_2025_paper.html)** — *CVPR 2025*

- **[DiffTalk: Crafting Diffusion Models for Generalized Audio-Driven Portraits Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Shen_DiffTalk_Crafting_Diffusion_Models_for_Generalized_Audio-Driven_Portraits_Animation_CVPR_2023_paper.html)** — *CVPR 2023*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://openaccess.thecvf.com/content/ICCV2025/html/Siniukov_DiTaiListener_Controllable_High_Fidelity_Listener_Video_Generation_with_Diffusion_ICCV_2025_paper.html)** — *ICCV 2025*

- **[HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation](https://openaccess.thecvf.com/content/CVPR2025/html/Xu_HunyuanPortrait_Implicit_Condition_Control_for_Enhanced_Portrait_Animation_CVPR_2025_paper.html)** — *CVPR 2025*

#### Feed-Forward Image Synthesis

- **[StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-Based Generator](https://openaccess.thecvf.com/content/CVPR2023/html/Guan_StyleSync_High-Fidelity_Generalized_and_Personalized_Lip_Sync_in_Style-Based_Generator_CVPR_2023_paper.html)** — *CVPR 2023*

- **[StyleLipSync: Style-based Personalized Lip-sync Video Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Ki_StyleLipSync_Style-based_Personalized_Lip-sync_Video_Generation_ICCV_2023_paper.html)** — *ICCV 2023*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Progressive Disentangled Representation Learning for Fine-Grained Controllable Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Progressive_Disentangled_Representation_Learning_for_Fine-Grained_Controllable_Talking_Head_Synthesis_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)** — *CVPR 2021*

---

### Three-Dimensional Avatar Rendering

#### 3D Gaussian Splatting

- **[GaussianSpeech: Audio-Driven Personalized 3D Gaussian Avatars](https://openaccess.thecvf.com/content/ICCV2025/html/Aneja_GaussianSpeech_Audio-Driven_Personalized_3D_Gaussian_Avatars_ICCV_2025_paper.html)** — *ICCV 2025*

- **[TaoAvatar: Real-Time Lifelike Full-Body Talking Avatars for Augmented Reality via 3D Gaussian Splatting](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_TaoAvatar_Real-Time_Lifelike_Full-Body_Talking_Avatars_for_Augmented_Reality_via_CVPR_2025_paper.html)** — *CVPR 2025*

- **[GaussianTalker: Real-Time Talking Head Synthesis with 3D Gaussian Splatting](https://dl.acm.org/doi/10.1145/3664647.3681627)** — *ACM MM 2024*

- **[Monocular and Generalizable Gaussian Talking Head Animation](https://openaccess.thecvf.com/content/CVPR2025/html/Gong_Monocular_and_Generalizable_Gaussian_Talking_Head_Animation_CVPR_2025_paper.html)** — *CVPR 2025*

- **[GGTalker: Talking Head Systhesis with Generalizable Gaussian Priors and Identity-Specific Adaptation](https://openaccess.thecvf.com/content/ICCV2025/html/Hu_GGTalker_Talking_Head_Systhesis_with_Generalizable_Gaussian_Priors_and_Identity-Specific_ICCV_2025_paper.html)** — *ICCV 2025*

- **[InsTaG: Learning Personalized 3D Talking Head from Few-Second Video](https://openaccess.thecvf.com/content/CVPR2025/html/Li_InsTaG_Learning_Personalized_3D_Talking_Head_from_Few-Second_Video_CVPR_2025_paper.html)** — *CVPR 2025*

- **[DGTalker: Disentangled Generative Latent Space Learning for Audio-Driven Gaussian Talking Heads](https://openaccess.thecvf.com/content/ICCV2025/html/Liang_DGTalker_Disentangled_Generative_Latent_Space_Learning_for_Audio-Driven_Gaussian_Talking_ICCV_2025_paper.html)** — *ICCV 2025*

#### Mesh-Based Rendering

- **[Neural Head Avatars From Monocular RGB Videos](https://openaccess.thecvf.com/content/CVPR2022/html/Grassal_Neural_Head_Avatars_From_Monocular_RGB_Videos_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Towards High-fidelity 3D Talking Avatar with Personalized Dynamic Texture](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Towards_High-fidelity_3D_Talking_Avatar_with_Personalized_Dynamic_Texture_CVPR_2025_paper.html)** — *CVPR 2025*

- **[Neural Voice Puppetry: Audio-driven Facial Reenactment](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_42)** — *ECCV 2020*

- **[Learning Dynamic Tetrahedra for High-Quality Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Learning_Dynamic_Tetrahedra_for_High-Quality_Talking_Head_Synthesis_CVPR_2024_paper.html)** — *CVPR 2024*

#### Neural Radiance Fields

- **[AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://openaccess.thecvf.com/content/ICCV2021/html/Guo_AD-NeRF_Audio_Driven_Neural_Radiance_Fields_for_Talking_Head_Synthesis_ICCV_2021_paper.html)** — *ICCV 2021*

- **[S3D-NeRF: Single-Shot Speech-Driven Neural Radiance Field for High Fidelity Talking Head Synthesis](https://link.springer.com/chapter/10.1007/978-3-031-72684-2_21)** — *ECCV 2024*

- **[Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Efficient_Region-Aware_Neural_Radiance_Fields_for_High-Fidelity_Talking_Portrait_Synthesis_ICCV_2023_paper.html)** — *ICCV 2023*

- **[One-Shot High-Fidelity Talking-Head Synthesis With Deformable Neural Radiance Field](https://openaccess.thecvf.com/content/CVPR2023/html/Li_One-Shot_High-Fidelity_Talking-Head_Synthesis_With_Deformable_Neural_Radiance_Field_CVPR_2023_paper.html)** — *CVPR 2023*

- **[SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2024/html/Peng_SyncTalk_The_Devil_is_in_the_Synchronization_for_Talking_Head_CVPR_2024_paper.html)** — *CVPR 2024*

- **[GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://arxiv.org/abs/2301.13430)** — *ICLR 2023*

---

## Interaction Modeling and Control

### Predictive Interaction Control

- **[TurnGPT: a Transformer-based Language Model for Predicting Turn-taking in Spoken Dialog](https://aclanthology.org/2020.findings-emnlp.268/)** — *Findings of ACL 2020*

- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals](https://aclanthology.org/2025.acl-long.743/)** — *ACL 2025*

- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Model](https://proceedings.neurips.cc/paper_files/paper/2024/hash/180d4373aca26bd86bf45fc50d1a709f-Abstract-Conference.html)** — *NeurIPS 2024*

---

### Dyadic Conditional Generation

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_DualTalk_Dual-Speaker_Interaction_for_3D_Talking_Head_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Zhu_INFP_Audio-Driven_Interactive_Head_Generation_in_Dyadic_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

---

### Causal and Multi-Stream Modeling

- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)** — *arXiv 2024*

- **[ARIG: Autoregressive Interactive Head Generation for Real-time Conversations](https://openaccess.thecvf.com/content/ICCV2025/html/Guo_ARIG_Autoregressive_Interactive_Head_Generation_for_Real-time_Conversations_ICCV_2025_paper.html)** — *ICCV 2025*

- **[OmniFlatten: An End-to-end GPT Model for Seamless Voice Conversation](https://aclanthology.org/2025.acl-long.709/)** — *ACL 2025*

---

# Datasets and Evaluation

## Datasets and Benchmarks

- **[Deep Audio-Visual Speech Recognition](https://ieeexplore.ieee.org/document/8585066/)** — *IEEE TPAMI 2022*

- **[LRS3-TED: A Large-Scale Dataset for Visual Speech Recognition](https://arxiv.org/abs/1809.00496)** — *arXiv 2018*

- **[TalkVid: A Large-Scale Diversified Dataset for Audio-Driven Talking Head Synthesis](https://arxiv.org/abs/2508.13618)** — *CVPR 2026*

- **[VoxCeleb2: Deep Speaker Recognition](https://www.isca-archive.org/interspeech_2018/chung18b_interspeech.html)** — *INTERSPEECH 2018*

- **[Capture, Learning, and Synthesis of 3D Speaking Styles](https://openaccess.thecvf.com/content_CVPR_2019/html/Cudeiro_Capture_Learning_and_Synthesis_of_3D_Speaking_Styles_CVPR_2019_paper.html)** — *CVPR 2019*

- **[A 3-D Audio-Visual Corpus of Affective Communication](http://ieeexplore.ieee.org/document/5571821/)** — *IEEE TMM 2010*

- **[Multi-TPC: A Multimodal Dataset for Three-Party Conversations with Speech, Motion, and Gaze](https://www.nature.com/articles/s41597-026-06819-x?error=cookies_not_supported&code=c6158320-5ce0-40c0-a724-368309037118)** — *Scientific Data 2026*

- **[Full-Duplex-Bench: A Benchmark to Evaluate Full-Duplex Spoken Dialogue Models on Turn-taking Capabilities](https://ieeexplore.ieee.org/document/11433838/)** — *ASRU 2025*

- **[VideoFDB: Evaluating Full-Duplex Vision-Speech Capabilities in Conversational Agents](https://arxiv.org/abs/2605.30256)** — *arXiv 2026*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_DualTalk_Dual-Speaker_Interaction_for_3D_Talking_Head_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

- **[REACT 2025: the Third Multiple Appropriate Facial Reaction Generation Challenge](https://dl.acm.org/doi/10.1145/3746027.3762244)** — *ACM MM 2025*

- **[REACT2023: The First Multiple Appropriate Facial Reaction Generation Challenge](https://dl.acm.org/doi/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[SpeakerVid-5M: A Large-Scale High-Quality Dataset for Audio-Visual Dyadic Interactive Human Generation](https://proceedings.iclr.cc/paper_files/paper/2026/hash/bf7dbac50ed7f6e12ad529c5b9396bc4-Abstract-Conference.html)** — *ICLR 2026*

- **[Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://openaccess.thecvf.com/content/CVPR2021/html/Zhang_Flow-Guided_One-Shot_Talking_Face_Generation_With_a_High-Resolution_Audio-Visual_Dataset_CVPR_2021_paper.html)** — *CVPR 2021*

- **[Interactive Conversational Head Generation](https://ieeexplore.ieee.org/document/10979678/)** — *IEEE TPAMI 2025*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

---

## Evaluation

### Visual Quality

- **[Out of Time: Automated Lip Sync in the Wild](https://link.springer.com/chapter/10.1007/978-3-319-54427-4_19)** — *ACCV Workshop 2016*

- **[GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium](https://proceedings.neurips.cc/paper_files/paper/2017/hash/8a1d694707eb0fefe65871369074926d-Abstract.html)** — *NeurIPS 2017*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Towards Accurate Generative Models of Video: A New Metric & Challenges](https://arxiv.org/abs/1812.01717)** — *arXiv 2018*

- **[Image quality assessment: from error visibility to structural similarity](https://ieeexplore.ieee.org/document/1284395/)** — *IEEE TIP 2004*

- **[The Unreasonable Effectiveness of Deep Features as a Perceptual Metric](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.html)** — *CVPR 2018*

---

### Response Appropriateness

- **[LLM-driven Multimodal and Multi-Identity Listening Head Generation](https://openaccess.thecvf.com/content/CVPR2025/html/Lai_LLM-driven_Multimodal_and_Multi-Identity_Listening_Head_Generation_CVPR_2025_paper.html)** — *CVPR 2025*

- **[Full-Duplex-Bench: A Benchmark to Evaluate Full-Duplex Spoken Dialogue Models on Turn-taking Capabilities](https://ieeexplore.ieee.org/document/11433838/)** — *ASRU 2025*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_CustomListener_Text-guided_Responsive_Interaction_for_User-friendly_Listening_Head_Generation_CVPR_2024_paper.html)** — *CVPR 2024*

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[REACT2023: The First Multiple Appropriate Facial Reaction Generation Challenge](https://dl.acm.org/doi/10.1145/3581783.3612832)** — *ACM MM 2023*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://aclanthology.org/2024.emnlp-main.1192/)** — *EMNLP 2024*

---

### User Experience

- **[Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/html/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.html)** — *ECCV 2018*

- **[Hierarchical Cross-Modal Talking Face Generation With Dynamic Pixel-Wise Loss](https://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Hierarchical_Cross-Modal_Talking_Face_Generation_With_Dynamic_Pixel-Wise_Loss_CVPR_2019_paper.html)** — *CVPR 2019*

- **[EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions](https://ojs.aaai.org/index.php/AAAI/article/view/32241)** — *AAAI 2025*

- **[GaussianTalker: Real-Time Talking Head Synthesis with 3D Gaussian Splatting](https://dl.acm.org/doi/10.1145/3664647.3681627)** — *ACM MM 2024*

- **[Efficient Emotional Adaptation for Audio-Driven Talking-Head Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Gan_Efficient_Emotional_Adaptation_for_Audio-Driven_Talking-Head_Generation_ICCV_2023_paper.html)** — *ICCV 2023*

- **[High-Fidelity and Freely Controllable Talking Head Video Generation](https://openaccess.thecvf.com/content/CVPR2023/html/Gao_High-Fidelity_and_Freely_Controllable_Talking_Head_Video_Generation_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Monocular and Generalizable Gaussian Talking Head Animation](https://openaccess.thecvf.com/content/CVPR2025/html/Gong_Monocular_and_Generalizable_Gaussian_Talking_Head_Animation_CVPR_2025_paper.html)** — *CVPR 2025*

- **[StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-Based Generator](https://openaccess.thecvf.com/content/CVPR2023/html/Guan_StyleSync_High-Fidelity_Generalized_and_Personalized_Lip_Sync_in_Style-Based_Generator_CVPR_2023_paper.html)** — *CVPR 2023*

- **[AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://openaccess.thecvf.com/content/ICCV2021/html/Guo_AD-NeRF_Audio_Driven_Neural_Radiance_Fields_for_Talking_Head_Synthesis_ICCV_2021_paper.html)** — *ICCV 2021*

- **[Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://openaccess.thecvf.com/content/CVPR2022/html/Hong_Depth-Aware_Generative_Adversarial_Network_for_Talking_Head_Video_Generation_CVPR_2022_paper.html)** — *CVPR 2022*

- **[GGTalker: Talking Head Systhesis with Generalizable Gaussian Priors and Identity-Specific Adaptation](https://openaccess.thecvf.com/content/ICCV2025/html/Hu_GGTalker_Talking_Head_Systhesis_with_Generalizable_Gaussian_Priors_and_Identity-Specific_ICCV_2025_paper.html)** — *ICCV 2025*

- **[Sonic: Shifting Focus to Global Audio Perception in Portrait Animation](https://openaccess.thecvf.com/content/CVPR2025/html/Ji_Sonic_Shifting_Focus_to_Global_Audio_Perception_in_Portrait_Animation_CVPR_2025_paper.html)** — *CVPR 2025*

- **[EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://dl.acm.org/doi/10.1145/3528233.3530745)** — *2022*

- **[Realistic One-Shot Mesh-Based Head Avatars](https://link.springer.com/chapter/10.1007/978-3-031-20086-1_20?error=cookies_not_supported&code=48dd12a6-0f2b-4c4c-82db-f5cc2833e459)** — *ECCV 2022*

- **[Learning to Generate Conditional Tri-Plane for 3D-Aware Expression Controllable Portrait Animation](https://link.springer.com/chapter/10.1007/978-3-031-73232-4_27?error=cookies_not_supported&code=979a8f79-4112-484f-80f7-984b4729cd46)** — *ECCV 2024*

- **[FLOAT: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait](https://openaccess.thecvf.com/content/ICCV2025/html/Ki_FLOAT_Generative_Motion_Latent_Flow_Matching_for_Audio-driven_Talking_Portrait_ICCV_2025_paper.html)** — *ICCV 2025*

- **[All You Need Is Your Voice: Emotional Face Representation with Audio Perspective for Emotional Talking Face Generation](https://link.springer.com/chapter/10.1007/978-3-031-73039-9_20)** — *2024*

- **[TalkingGaussian: Structure-Persistent 3D Talking Head Synthesis via Gaussian Splatting](https://link.springer.com/chapter/10.1007/978-3-031-72684-2_8?error=cookies_not_supported&code=e7ba1cf6-7294-4516-b924-21956cd3aa66)** — *ECCV 2024*

- **[Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Efficient_Region-Aware_Neural_Radiance_Fields_for_High-Fidelity_Talking_Portrait_Synthesis_ICCV_2023_paper.html)** — *ICCV 2023*

- **[Ditto: Motion-Space Diffusion for Controllable Realtime Talking Head Synthesis](https://dl.acm.org/doi/10.1145/3746027.3755075)** — *ACM MM 2025*

- **[One-Shot High-Fidelity Talking-Head Synthesis With Deformable Neural Radiance Field](https://openaccess.thecvf.com/content/CVPR2023/html/Li_One-Shot_High-Fidelity_Talking-Head_Synthesis_With_Deformable_Neural_Radiance_Field_CVPR_2023_paper.html)** — *CVPR 2023*

- **[AniTalker: Animate Vivid and Diverse Talking Faces through Identity-Decoupled Facial Motion Encoding](https://dl.acm.org/doi/10.1145/3664647.3681198)** — *ACM MM 2024*

- **[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_CustomListener_Text-guided_Responsive_Interaction_for_User-friendly_Listening_Head_Generation_CVPR_2024_paper.html)** — *CVPR 2024*

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[DPE: Disentanglement of Pose and Expression for General Video Portrait Editing](https://openaccess.thecvf.com/content/CVPR2023/html/Pang_DPE_Disentanglement_of_Pose_and_Expression_for_General_Video_Portrait_CVPR_2023_paper.html)** — *CVPR 2023*

- **[SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2024/html/Peng_SyncTalk_The_Devil_is_in_the_Synchronization_for_Talking_Head_CVPR_2024_paper.html)** — *CVPR 2024*

- **[A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/10.1145/3394171.3413532)** — *ACM MM 2020*

- **[Comparing the value of perceived human versus AI-generated empathy](https://www.nature.com/articles/s41562-025-02247-w?error=cookies_not_supported&code=7f6ffce9-c8a7-4785-8494-578a32071e38)** — *Nature Human Behaviour 2025*

- **[First Order Motion Model for Image Animation](https://proceedings.neurips.cc/paper_files/paper/2019/hash/31c0b36aef265d9221af80872ceb62f9-Abstract.html)** — *NeurIPS 2019*

- **[DisFlowEm : One-Shot Emotional Talking Head Generation using Disentangled Pose and Expression Flow-Guidance](https://openaccess.thecvf.com/content/WACV2025/html/Sinha_DisFlowEm__One-Shot_Emotional_Talking_Head_Generation_using_Disentangled_Pose_WACV_2025_paper.html)** — *WACV 2025*

- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://openaccess.thecvf.com/content/ICCV2025/html/Siniukov_DiTaiListener_Controllable_High_Fidelity_Listener_Video_Generation_with_Diffusion_ICCV_2025_paper.html)** — *ICCV 2025*

- **[Emotional Listener Portrait: Neural Listener Head Generation with Emotion](https://openaccess.thecvf.com/content/ICCV2023/html/Song_Emotional_Listener_Portrait_Neural_Listener_Head_Generation_with_Emotion_ICCV_2023_paper.html)** — *ICCV 2023*

- **[EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis](https://link.springer.com/chapter/10.1007/978-3-031-72658-3_23)** — *2024*

- **[DIM: Dyadic Interaction Modeling for Social Behavior Generation](https://link.springer.com/chapter/10.1007/978-3-031-72913-3_27)** — *ECCV 2024*

- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents](https://aclanthology.org/2024.emnlp-main.1192/)** — *EMNLP 2024*

- **[Progressive Disentangled Representation Learning for Fine-Grained Controllable Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Progressive_Disentangled_Representation_Learning_for_Fine-Grained_Controllable_Talking_Head_Synthesis_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Seeing_What_You_Said_Talking_Face_Generation_Guided_by_a_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://www.ijcai.org/proceedings/2021/152)** — *IJCAI 2021*

- **[One-Shot Talking Face Generation from Single-Speaker Audio-Visual Correlation Learning](https://ojs.aaai.org/index.php/AAAI/article/view/20154)** — *AAAI 2022*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_One-Shot_Free-View_Neural_Talking-Head_Synthesis_for_Video_Conferencing_CVPR_2021_paper.html)** — *CVPR 2021*

- **[High-Fidelity Generalized Emotional Talking Face Generation With Multi-Modal Emotion Space Learning](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_High-Fidelity_Generalized_Emotional_Talking_Face_Generation_With_Multi-Modal_Emotion_Space_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Audiodriven Talking Face Generation with Stabilized Synchronization Loss](https://link.springer.com/chapter/10.1007/978-3-031-72655-2_24)** — *2024*

- **[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_SadTalker_Learning_Realistic_3D_Motion_Coefficients_for_Stylized_Audio-Driven_Single_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Identity-Preserving Talking Face Generation With Landmark and Appearance Priors](https://openaccess.thecvf.com/content/CVPR2023/html/Zhong_Identity-Preserving_Talking_Face_Generation_With_Landmark_and_Appearance_Priors_CVPR_2023_paper.html)** — *CVPR 2023*

- **[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)** — *CVPR 2021*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

- **[MakeItTalk: Speaker-Aware Talking-Head Animation](https://dl.acm.org/doi/10.1145/3414685.3417774)** — *ACM TOG 2020*

---

# Challenges and Future Directions

## Challenges

### Data Scarcity

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Responsive Listening Head Generation: A Benchmark Dataset and Baseline](https://arxiv.org/abs/2112.13548)** — *ECCV 2022*

---

### Generalization

- **[FaceFormer: Speech-Driven 3D Facial Animation With Transformers](https://openaccess.thecvf.com/content/CVPR2022/html/Fan_FaceFormer_Speech-Driven_3D_Facial_Animation_With_Transformers_CVPR_2022_paper.html)** — *CVPR 2022*

- **[Avatar Forcing: Real-Time Interactive Head Avatar Generation for Natural Conversation](https://openaccess.thecvf.com/content/CVPR2026/html/Ki_Avatar_Forcing_Real-Time_Interactive_Head_Avatar_Generation_for_Natural_Conversation_CVPR_2026_paper.html)** — *CVPR 2026*

- **[Learning To Listen: Modeling Non-Deterministic Dyadic Facial Motion](https://openaccess.thecvf.com/content/CVPR2022/html/Ng_Learning_To_Listen_Modeling_Non-Deterministic_Dyadic_Facial_Motion_CVPR_2022_paper.html)** — *CVPR 2022*

- **[DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_DualTalk_Dual-Speaker_Interaction_for_3D_Talking_Head_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

- **[SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://dl.acm.org/doi/10.1145/3581783.3611734)** — *ACM MM 2023*

- **[EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://openaccess.thecvf.com/content/ICCV2023/html/Peng_EmoTalk_Speech-Driven_Emotional_Disentanglement_for_3D_Face_Animation_ICCV_2023_paper.html)** — *ICCV 2023*

- **[One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_One-Shot_Free-View_Neural_Talking-Head_Synthesis_for_Video_Conferencing_CVPR_2021_paper.html)** — *CVPR 2021*

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_MimicTalker_A_Multimodal_Interactive_and_Memory-Enhanced_Framework_for_Real-Time_Dyadic_CVPR_2026_paper.html)** — *CVPR 2026*

- **[CodeTalker: Speech-Driven 3D Facial Animation With Discrete Motion Prior](https://openaccess.thecvf.com/content/CVPR2023/html/Xing_CodeTalker_Speech-Driven_3D_Facial_Animation_With_Discrete_Motion_Prior_CVPR_2023_paper.html)** — *CVPR 2023*

- **[INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://openaccess.thecvf.com/content/CVPR2025/html/Zhu_INFP_Audio-Driven_Interactive_Head_Generation_in_Dyadic_Conversations_CVPR_2025_paper.html)** — *CVPR 2025*

---

### Ethical Risks

- **[How human–AI feedback loops alter human perceptual, emotional and social judgements](https://www.nature.com/articles/s41562-024-02077-2?error=cookies_not_supported&code=811769ef-af41-4907-82c3-3a0209a1cdac)** — *Nature Human Behaviour 2025*

- **[Influencing human–AI interaction by priming beliefs about AI can increase perceived trustworthiness, empathy and effectiveness](https://www.nature.com/articles/s42256-023-00720-7?error=cookies_not_supported&code=13544f54-bcb0-46f2-818e-11439269a7c1)** — *Nature Machine Intelligence 2023*

- **[FaceForensics++: Learning to Detect Manipulated Facial Images](https://openaccess.thecvf.com/content_ICCV_2019/html/Rossler_FaceForensics_Learning_to_Detect_Manipulated_Facial_Images_ICCV_2019_paper.html)** — *ICCV 2019*

---

## Future Directions

### Long-term Memory and Persona

- **[BRIDGE: Triangular Fixed-Point Refinement for Long-Horizon Persona Consistency](https://proceedings.mlr.press/v306/jiang26aw.html)** — *2026*

- **[MimicTalker: A Multimodal Interactive and Memory-Enhanced Framework for Real-Time Dyadic 3D Head Generation](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_MimicTalker_A_Multimodal_Interactive_and_Memory-Enhanced_Framework_for_Real-Time_Dyadic_CVPR_2026_paper.html)** — *CVPR 2026*

---

### Holistic Multi-party Embodiment

- **[PolySLGen: Online Multimodal SpeakingListening Reaction Generation in Polyadic Interaction](https://arxiv.org/abs/2604.08125)** — *CVPR 2026*

---

### Robust Real-Time Interaction

- **[Avatar Forcing: Real-Time Interactive Head Avatar Generation for Natural Conversation](https://openaccess.thecvf.com/content/CVPR2026/html/Ki_Avatar_Forcing_Real-Time_Interactive_Head_Avatar_Generation_for_Natural_Conversation_CVPR_2026_paper.html)** — *CVPR 2026*

---


## Contributing

Contributions are welcome. If you find a relevant paper or notice a broken link, please open an issue or submit a pull request.
