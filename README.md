# Writing Research

Curated collection of research papers on AI systems for automated writing, text generation, writing assistance, and computational composition.

## Research Focus

This corpus covers AI systems for:
- **LLMs for Writing**: Large language models applied to text generation, creative writing, and composition
- **Text Generation**: Neural text generation, controllable generation, creative writing
- **Writing Assistants**: AI-powered writing tools, autocomplete, grammar checking
- **Writing Planning**: Outline generation, story planning, discourse structure
- **Human-AI Collaboration**: Human-in-the-loop writing, editing assistance, co-creative writing
- **Control & Personalization**: Style transfer, persona control, factuality
- **Evaluation**: Metrics, benchmarks, and evaluation methods for generated text

## 📊 Corpus Statistics

<!-- BEGIN CORPUS STATISTICS -->

## 📊 Corpus Statistics

**5996 papers** across **9 categories**.  
Sources: **arXiv** 2285 (38%).  

### Top categories

| Category | Papers | Recent | |
|----------|--------|--------|-|
| applications | **1108** | 495 | ████████████ |
| large-language-models | **1057** | 296 | ███████████░ |
| generation | **1030** | 338 | ███████████░ |
| evaluation | **753** | 237 | ████████░░░░ |
| human-ai | **605** | 329 | ███████░░░░░ |
| control | **598** | 294 | ██████░░░░░░ |
| survey | **460** | 229 | █████░░░░░░░ |
| planning | **317** | 121 | ███░░░░░░░░░ |
| writing-assistants | **68** | 21 | █░░░░░░░░░░░ |

### By year

| Year | Papers | |
|------|--------|-|
| 2023 | 425 | ███░░░░░░░░░ |
| 2024 | 1851 | ███████████░ |
| 2025 | 1956 | ████████████ |
| 2026 | 1764 | ███████████░ |

### Momentum (hottest categories)

| Category | Total | Rate | Recent | Score |
|----------|-------|------|--------|-------|
| Human Ai | 605 | 27.4/mo | 54% | 140 |
| Survey | 460 | 19.1/mo | 50% | 111 |
| Control | 598 | 24.5/mo | 49% | 108 |
| Applications | 1108 | 41.2/mo | 45% | 84 |
| Planning | 317 | 10.1/mo | 38% | 47 |
| Generation | 1030 | 28.2/mo | 33% | 38 |
| Evaluation | 753 | 19.8/mo | 32% | 18 |
| Large Language Models | 1057 | 24.7/mo | 28% | 4 |
| Writing Assistants | 68 | 1.8/mo | 31% | 1 |

### Trending keywords

| Keyword | Papers | Burst |
|---------|--------|-------|
| autocomplete | 9 | 1.63 |
| writing assistant | 145 | 1.53 |
| human-ai | 147 | 1.43 |
| academic writing | 204 | 1.4 |
| controllable generation | 44 | 1.33 |
| multimodal | 245 | 1.29 |
| coherence | 161 | 1.28 |
| creative writing | 80 | 1.28 |

### Top venues

| Venue | Papers |
|-------|--------|
| arXiv (Cornell University) | 676 |
| Zenodo (CERN European Organization for Nuclear Research) | 326 |
| Lecture notes in computer science | 105 |
| SSRN Electronic Journal | 69 |
| IEEE Access | 50 |
| Proceedings of the AAAI Conference on Artificial Intelligence | 43 |
| Scientific Reports | 40 |
| Research Square | 30 |
| ACM Transactions on Software Engineering and Methodology | 29 |
| Preprints.org | 24 |

### Research gaps (thinnest cells)

| Cell | Papers |
|------|--------|
| `planning/code-as-text` | 1 |
| `writing-assistants/creative-writing` | 1 |
| `human-ai/controllable-generation` | 1 |
| `human-ai/code-as-text` | 1 |
| `large-language-models/narrative-arc` | 1 |

*Generated 2026-09 by `scripts/standard_stats.py`.*

<!-- END CORPUS STATISTICS -->

## 📚 Paper List

<!-- BEGIN PAPER LIST -->

## 📚 Paper list

- [📚 LLMs for Writing](#llms-for-writing)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Autocomplete](#autocomplete)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Interactive Writing](#interactive-writing)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [NLP Metrics](#nlp-metrics)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Code Generation](#code-generation)
- [📚 Text Generation](#text-generation)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [NLP Metrics](#nlp-metrics)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Code Generation](#code-generation)
  - [Multimodal Writing](#multimodal-writing)
- [📚 Writing Assistants](#writing-assistants)
  - [Creative Writing](#creative-writing)
  - [Autocomplete](#autocomplete)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Interactive Writing](#interactive-writing)
- [📚 Writing Planning & Structure](#writing-planning-&-structure)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Code Generation](#code-generation)
- [📚 Evaluation & Quality](#evaluation-&-quality)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [NLP Metrics](#nlp-metrics)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Multimodal Writing](#multimodal-writing)
- [📚 Human-AI Collaboration](#human-ai-collaboration)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Autocomplete](#autocomplete)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Interactive Writing](#interactive-writing)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Human-in-the-Loop](#human-in-the-loop)
  - [Editing Assistance](#editing-assistance)
  - [Co-creative Writing](#co-creative-writing)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [NLP Metrics](#nlp-metrics)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Code Generation](#code-generation)
  - [Multimodal Writing](#multimodal-writing)
- [📚 Control & Personalization](#control-&-personalization)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Human-in-the-Loop](#human-in-the-loop)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Multimodal Writing](#multimodal-writing)
- [📚 Writing Applications](#writing-applications)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Autocomplete](#autocomplete)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Interactive Writing](#interactive-writing)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Human-in-the-Loop](#human-in-the-loop)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [NLP Metrics](#nlp-metrics)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Code Generation](#code-generation)
  - [Multimodal Writing](#multimodal-writing)
- [📚 Surveys & Taxonomies](#surveys-&-taxonomies)
  - [LLM Evaluation](#llm-evaluation)
  - [Prompt Engineering](#prompt-engineering)
  - [Few-shot Learning](#few-shot-learning)
  - [Neural Text Generation](#neural-text-generation)
  - [Controllable Generation](#controllable-generation)
  - [Creative Writing](#creative-writing)
  - [Summarization](#summarization)
  - [Text Rewriting](#text-rewriting)
  - [Grammar & Style Checking](#grammar-&-style-checking)
  - [Outline & Planning](#outline-&-planning)
  - [Discourse Structure](#discourse-structure)
  - [Narrative Arc](#narrative-arc)
  - [Editing Assistance](#editing-assistance)
  - [Persona Control](#persona-control)
  - [Factuality Control](#factuality-control)
  - [Human Evaluation](#human-evaluation)
  - [Benchmark Datasets](#benchmark-datasets)
  - [Academic Writing](#academic-writing)
  - [Business Writing](#business-writing)
  - [Code Generation](#code-generation)
  - [Multimodal Writing](#multimodal-writing)

### LLMs for Writing

#### LLM Evaluation

##### 2026

- [2026] **Incremental Pooled LLM Evaluation for Cost-Effective Retrieval Model Selection** [[paper](https://arxiv.org/abs/2609.02745)]
- [2026] **Who's That Player?: Externalizing Query Interpretation in Spoken XR Sports Interaction** [[paper](https://arxiv.org/abs/2608.00876)]
- [2026] **Recipes for Creativity: Iterative Generation and Evaluation in Large Language Models** [[paper](https://arxiv.org/abs/2608.07243)]
- [2026] **Procedural Collapse: A Structural Account of Disengagement in LLM-Assisted Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.17326)]
- [2026] **Incremental Instruction Creative Writing: Benchmark, Generations, and Evaluation Dataset** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21954789)]
- [2026] **Expectations and Practices around AI Disclosure in CS Research** [[paper](https://arxiv.org/abs/2608.23271)]
- [2026] **An intelligent composition system for Chinese art songs via a cascaded pipeline of symbolic music generation and LLM-based lyric writing** *Multimedia Systems* [[paper](https://doi.org/10.1007/s00530-026-02605-2)]
- [2026] **IsoSci: A Benchmark of Isomorphic Cross-Domain Science Problems for Evaluating Reasoning versus Knowledge Retrieval in LLMs** [[paper](https://arxiv.org/abs/2607.01431)] [[project](https://huggingface.co/datasets/isosci/isosci)]
- [2026] **Building a European Multilingual Evaluation Dataset: The MMLU Localisation Project within the EMT Network** [[paper](https://arxiv.org/abs/2607.18432)]
- [2026] **Wazobia Eval: A Benchmark for Nigerian Pidgin Emotion Understanding, Sarcasm Detection, and Cultural Reasoning** [[paper](https://arxiv.org/abs/2608.21369)] [[project](https://huggingface.co/WAZOBIALABS)]
- [2026] **Reconceptualising LLM-Mediated Writing Practices: A Relational Approach** [[paper](https://doi.org/10.31235/osf.io/su2yk_v1)]
- [2026] **RealMath-Eval: Why SOTA Judges Struggle with Real Human Reasoning** [[paper](https://arxiv.org/abs/2606.10254)]
- [2026] **Poller: Are LLMs Suitable for Evaluating the Poetry Understanding Task?** [[paper](https://arxiv.org/abs/2606.30556)]
- [2026] **Contaminated Collaboration: Measuring Gender Bias Transfer in LLM-Assisted Student Writing** [[paper](https://arxiv.org/abs/2606.15914)]
- [2026] **Building Software by Rolling the Dice: A Qualitative Study of Vibe Coding** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3797105)]
- [2026] **A comparison of human and LLM-simulated participants in a writing style task** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.16778)]
- [2026] **TextLDM: Language Modeling with Continuous Latent Diffusion** [[paper](https://arxiv.org/abs/2605.07748)]
- [2026] **SAGE: Hierarchical LLM-Based Literary Evaluation through Ontology-Grounded Interpretive Dimensions** [[paper](https://arxiv.org/abs/2605.07102)]
- [2026] **Rethinking Visual Neglect: Steering via Context-Preference for MLLM Hallucination Mitigation** [[paper](https://arxiv.org/abs/2605.27993)]
- [2026] **OpenCompass: A Universal Evaluation Platform for Large Language Models** [[paper](https://arxiv.org/abs/2605.19276)]
- [2026] **Integrating LLMs and self-regulated learning in cognitive architectures: a case study in essay-writing tutoring** *Cognitive Systems Research* [[paper](https://doi.org/10.1016/j.cogsys.2026.101475)]
- [2026] **ErgoGlide: A Wearable Trackball Device for Ergonomic Text Entry in Virtual Reality** [[paper](https://arxiv.org/abs/2606.00823)]
- [2026] **Dystruct: Dynamically Structured Diffusion Language Model Decoding via Bayesian Inference** [[paper](https://arxiv.org/abs/2605.09820)]
- [2026] **DLM-SWAI: Steering Diffusion Language Models Before They Unmask** [[paper](https://arxiv.org/abs/2605.29626)]
- [2026] **CyberCorrect: A Cybernetic Framework for Closed-Loop Self-Correction in Large Language Models** [[paper](https://arxiv.org/abs/2605.17305)]
- [2026] **Continuous Latent Diffusion Language Model** [[paper](https://arxiv.org/abs/2605.06548)]
- [2026] **Boosting DBMS Test Coverage via LLM-Driven SQL Generation** [[paper](https://doi.org/10.1145/3810991.3811637)]
- [2026] **Towards Faster Language Model Inference Using Mixture-of-Experts Flow Matching** [[paper](https://arxiv.org/abs/2604.15009)]
- [2026] **SwEYEpinch: Exploring Intuitive, Efficient Text Entry for Extended Reality via Eye and Hand Tracking** [[paper](https://arxiv.org/abs/2604.03520)]
- [2026] **Reliability Gated Multi-Teacher Distillation for Low Resource Abstractive Summarization** [[paper](https://arxiv.org/abs/2604.03192)]
- [2026] **MBD semantic annotation and closed-loop back-writing for aircraft components based on MLLM and MKG** *Journal of Manufacturing Systems* [[paper](https://doi.org/10.1016/j.jmsy.2026.03.018)]
- [2026] **LAWE-CL2: Multi-agent LLM-based automated writing evaluation system integrating linguistic features with fine-tuning for Chinese L2 writing assessment** *Assessing Writing* [[paper](https://doi.org/10.1016/j.asw.2026.101051)]
- [2026] **Interpretable Stylistic Variation in Human and LLM Writing Across Genres, Models, and Decoding Strategies** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.14111)]
- [2026] **From Use to Oversight: How Mental Models Influence User Behavior and Output in AI Writing Assistants** [[paper](https://arxiv.org/abs/2604.05166)]
- [2026] **Fast-dVLM: Efficient Block-Diffusion VLM via Direct Conversion from Autoregressive VLM** [[paper](https://arxiv.org/abs/2604.06832)]
- [2026] **DualDiffusion: A Speculative Decoding Strategy for Masked Diffusion Models** [[paper](https://arxiv.org/abs/2604.05250)]
- [2026] **Before You Interpret the Profile: Validity Scaling for LLM Metacognitive Self-Report** [[paper](https://arxiv.org/abs/2604.17707)] [[code](https://github.com/synthiumjp/validity-scaling-llm)]
- [2026] **Artificial Intelligence Tools for Gastrointestinal Research: A Practical Guide** *Clinical Gastroenterology and Hepatology* [[paper](https://doi.org/10.1016/j.cgh.2026.03.032)]
- [2026] **An Empirical Study on Pragmatic Unit Test Generation with Large Language Models** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9194820/v1)]
- [2026] **Permutation-Consensus Listwise Judging for Robust Factuality Evaluation** *ACL 2026* [[paper](https://arxiv.org/abs/2603.20562)]
- [2026] **GRAFITE: Generative Regression Analysis Framework for Issue Tracking and Evaluation** [[paper](https://arxiv.org/abs/2603.18173)] [[code](https://github.com/IBM/grafite)]
- [2026] **From text to DSM: evaluating the impact of writing style and entity naming on LLM-based retrieval of asymmetrical indirect design dependencies** *Research in Engineering Design* [[paper](https://doi.org/10.1007/s00163-026-00476-2)]
- [2026] **ClinConsensus: A Physician-Calibrated Benchmark for Evaluating Clinical Rubric Coverage in Chinese Medical LLMs** [[paper](https://arxiv.org/abs/2603.02097)]
- [2026] **Can AI provide useful analytic essay scoring for different genres of writing with elementary grade students?** *Assessing Writing* [[paper](https://doi.org/10.1016/j.asw.2026.101038)]
- [2026] **AnkleType: A Hands- and Eyes-free Foot-based Text Entry Technique in Virtual Reality** [[paper](https://arxiv.org/abs/2603.21915)]
- [2026] **Adaptive Guidance for Retrieval-Augmented Masked Diffusion Models** [[paper](https://arxiv.org/abs/2603.17677)]
- [2026] **Adaptive Decoding via Test-Time Policy Learning for Self-Improving Generation** [[paper](https://arxiv.org/abs/2603.18428)]
- [2026] **A Resource-Rational Principle for Modeling Visual Attention Control** [[paper](https://arxiv.org/abs/2603.02056)]
- [2026] **Texterial: A Text-as-Material Interaction Paradigm for LLM-Mediated Writing** [[paper](https://arxiv.org/abs/2603.00452)]
- [2026] **MILE-RefHumEval: A Reference-Free, Multi-Independent LLM Framework for Human-Aligned Evaluation** [[paper](https://arxiv.org/abs/2602.09624)]
- [2026] **KeySense: LLM-Powered Hands-Down, Ten-Finger Typing on Commodity Touchscreens** [[paper](https://arxiv.org/abs/2602.12432)]
- [2026] **Fine-Tuned Large Language Models for Generating Multiple-Choice Questions in Anesthesiology: Psychometric Comparison With Faculty-Written Items** *JMIR Formative Research* [[paper](https://doi.org/10.2196/84904)]
- [2026] **Time-Annealed Perturbation Sampling: Diverse Generation for Diffusion Language Models** [[paper](https://arxiv.org/abs/2601.22629)]
- [2026] **Relying on LLMs: Student Practices and Instructor Norms are Changing in Computer Science Education** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6627298)]
- [2026] **DPWriter: Reinforcement Learning with Diverse Planning Branching for Creative Writing** [[paper](https://arxiv.org/abs/2601.09609)]
- [2026] **Confident Rankings with Fewer Items: Adaptive LLM Evaluation with Continuous Scores** [[paper](https://arxiv.org/abs/2601.13885)]
- [2026] **Compressed code: the hidden effects of quantization and distillation on programming tokens** [[paper](https://arxiv.org/abs/2601.02563)]
- [2026] **Comparative Study of Large Language Models on Chinese Film Script Continuation: An Empirical Analysis Based on GPT-5.2 and Qwen-Max** [[paper](https://arxiv.org/abs/2601.14826)]
- [2026] **A Virtual Tutor Based on Integration of LLM with a Cognitive Architecture** *Studies in computational intelligence* [[paper](https://doi.org/10.1007/978-3-032-13977-1_11)]
- [2026] **A Scoping Review and Guidelines on Privacy Policy's Visualization from an HCI Perspective** [[paper](https://arxiv.org/abs/2601.17368)]

##### 2025

- [2025] **WRAVAL -- WRiting Assist eVALuation** [[paper](https://arxiv.org/abs/2601.03268)] [[code](https://github.com/amazon-science/wraval)]
- [2025] **Say it or AI it: Evaluating Hands-Free Text Correction in Virtual Reality** [[paper](https://arxiv.org/abs/2512.11564)]
- [2025] **SA-DiffuSeq: Addressing Computational and Scalability Challenges in Long-Document Generation with Sparse Attention** [[paper](https://arxiv.org/abs/2512.20724)]
- [2025] **Optimizing Decoding Paths in Masked Diffusion Models by Quantifying Uncertainty** [[paper](https://arxiv.org/abs/2512.21336)]
- [2025] **MindShift: Analyzing Language Models' Reactions to Psychological Prompts** [[paper](https://arxiv.org/abs/2512.09149)]
- [2025] **Safer in Translation? Presupposition Robustness in Indic Languages** [[paper](https://arxiv.org/abs/2511.01360)]
- [2025] **STAR: Smartphone-analogous Typing in Augmented Reality** [[paper](https://arxiv.org/abs/2511.21143)]
- [2025] **On the Brittleness of LLMs: A Journey around Set Membership** [[paper](https://arxiv.org/abs/2511.12728)]
- [2025] **LLM-SYM: Integrating Symbolic Methods and Large Language Models for Automated Theorem Proving** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-4213-0_3)]
- [2025] **LLM-Boofuzz: Generation-Based Black-Box Fuzzing for Network Protocols via LLMs** *Electronics* [[paper](https://doi.org/10.3390/electronics14234550)]
- [2025] **LLM Driven Unit Test Case Generation Using Agentic AI** *Journal of Ubiquitous Computing and Communication Technologies* [[paper](https://doi.org/10.36548/jucct.2025.4.003)]
- [2025] **G2: Guided Generation for Enhanced Output Diversity in LLMs** [[paper](https://arxiv.org/abs/2511.00432)]
- [2025] **Control Barrier Function for Aligning Large Language Models** [[paper](https://arxiv.org/abs/2511.03121)]
- [2025] **Better Datasets Start From RefineLab: Automatic Optimization for High-Quality Dataset Refinement** [[paper](https://arxiv.org/abs/2511.06530)]
- [2025] **Which Heads Matter for Reasoning? RL-Guided KV Cache Compression** [[paper](https://arxiv.org/abs/2510.08525)]
- [2025] **Towards Mixed-Modal Retrieval for Universal Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2510.17354)]
- [2025] **The impact of large language models on medical research and patient care: A systematic review of current trends, challenges, and future innovations** *Computer Science Review* [[paper](https://doi.org/10.1016/j.cosrev.2025.100847)]
- [2025] **More than a Moment: Towards Coherent Sequences of Audio Descriptions** [[paper](https://arxiv.org/abs/2510.25440)]
- [2025] **Large Language Model Assistant for Emergency Department Discharge Documentation** *JAMA Network Open* [[paper](https://doi.org/10.1001/jamanetworkopen.2025.38427)]
- [2025] **Intelligent application of large language model to life cycle assessment methodology** *Journal of Cleaner Production* [[paper](https://doi.org/10.1016/j.jclepro.2025.146776)]
- [2025] **Exploring the Feasibility of Gaze-Based Navigation Across Path Types** [[paper](https://arxiv.org/abs/2510.07184)]
- [2025] **A Use-Case Specific Dataset for Measuring Dimensions of Responsible Performance in LLM-generated Text** [[paper](https://arxiv.org/abs/2510.20782)]
- [2025] **Toward Subtrait-Level Model Explainability in Automated Writing Evaluation** [[paper](https://arxiv.org/abs/2509.08345)]
- [2025] **Students’ Perception of the Integration of GenAI in Academic Paper Assignment Preparation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-01429-0_15)]
- [2025] **Neurosurgical journals’ policies on artificial intelligence use in manuscript preparation and peer review** *Neurosurgical Review* [[paper](https://doi.org/10.1007/s10143-025-03793-7)]
- [2025] **Evalet: Evaluating Large Language Models through Functional Fragmentation** [[paper](https://arxiv.org/abs/2509.11206)]
- [2025] **Efficient Decoding Methods for Language Models on Encrypted Data** [[paper](https://arxiv.org/abs/2509.08383)]
- [2025] **CausalARC: Abstract Reasoning with Causal World Models** [[paper](https://arxiv.org/abs/2509.03636)]
- [2025] **CRACQ: A Multi-Dimensional Approach To Automated Document Assessment** [[paper](https://arxiv.org/abs/2510.02337)]
- [2025] **Building Benchmarks from the Ground Up: Community-Centered Evaluation of LLMs in Healthcare Chatbot Settings** [[paper](https://arxiv.org/abs/2509.24506)]
- [2025] **Bounded PCTL Model Checking of Large Language Model Outputs** [[paper](https://arxiv.org/abs/2509.18836)]
- [2025] **Beyond Pointwise Scores: Decomposed Criteria-Based Evaluation of LLM Responses** [[paper](https://arxiv.org/abs/2509.16093)]
- [2025] **Better Call Claude: Can LLMs Detect Changes of Writing Style?** *Lecture notes in computer science* [[paper](https://arxiv.org/abs/2508.00680)]
- [2025] **Improving Text Style Transfer using Masked Diffusion Language Models with Inference-time Scaling** [[paper](https://arxiv.org/abs/2508.10995)]
- [2025] **Igniting Creative Writing in Small Language Models: LLM-as-a-Judge versus Multi-Agent Refined Rewards** [[paper](https://arxiv.org/abs/2508.21476)] [[code](https://github.com/weixiaolong94-hub/Igniting-Creative-Writing-in-Small-Language-Models)]
- [2025] **Benchmarking Hindi LLMs: A New Suite of Datasets and a Comparative Analysis** [[paper](https://arxiv.org/abs/2508.19831)]
- [2025] **ViSP: A PPO-Driven Framework for Sarcasm Generation with Contrastive Learning** [[paper](https://arxiv.org/abs/2507.09482)] [[code](https://github.com/wclapply/ViSP)]
- [2025] **SymbolicThought: Integrating Language Models and Symbolic Reasoning for Consistent and Interpretable Human Relationship Understanding** [[paper](https://arxiv.org/abs/2507.04189)]
- [2025] **OpenCodeReasoning-II: A Simple Test Time Scaling Approach via Self-Critique** [[paper](https://arxiv.org/abs/2507.09075)]
- [2025] **Mind the Gap: Conformative Decoding to Improve Output Diversity of Instruction-Tuned Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.20956)]
- [2025] **LowKeyEMG: Electromyographic typing with a reduced keyset** [[paper](https://arxiv.org/abs/2507.19736)]
- [2025] **Lightweight Safety Guardrails via Synthetic Data and RL-guided Adversarial Training** [[paper](https://arxiv.org/abs/2507.08284)]
- [2025] **Intelligent Virtual Sonographer (IVS): Enhancing Physician-Robot-Patient Communication** [[paper](https://arxiv.org/abs/2507.13052)]
- [2025] **From Queries to Criteria: Understanding How Astronomers Evaluate LLMs** [[paper](https://arxiv.org/abs/2507.15715)]
- [2025] **From Benchmarks to Skills: Low-Rank Factors for LLM Evaluation** [[paper](https://arxiv.org/abs/2507.20208)]
- [2025] **False Alarms, Real Damage: Adversarial Attacks Using LLM-based Models on Text-based Cyber Threat Intelligence Systems** [[paper](https://arxiv.org/abs/2507.06252)]
- [2025] **Towards Predictive Communication: The Fusion of Large Language Models and Brain–Computer Interface** *Sensors* [[paper](https://doi.org/10.3390/s25133987)]
- [2025] **Large language models to write scientific manuscripts: to be considered but not trusted** *Global Cardiology* [[paper](https://doi.org/10.4081/cardio.2025.74)]
- [2025] **From Guidelines to Practice: A New Paradigm for Arabic Language Model Evaluation** [[paper](https://arxiv.org/abs/2506.01920)]
- [2025] **Finance Language Model Evaluation (FLaME)** [[paper](https://arxiv.org/abs/2506.15846)]
- [2025] **Enhancing large language models for text-to-testcase generation** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2025.112531)]
- [2025] **AutoEvoEval: An Automated Framework for Evolving Close-Ended LLM Evaluation Data** [[paper](https://arxiv.org/abs/2506.23735)] [[code](https://github.com/SYSUSELab/AutoEvoEval)]
- [2025] **AI in the Writing Process: How Purposeful AI Support Fosters Student Writing** [[paper](https://arxiv.org/abs/2506.20595)]
- [2025] **Towards Contamination Resistant Benchmarks** [[paper](https://arxiv.org/abs/2505.08389)]
- [2025] **ReliableEval: A Recipe for Stochastic LLM Evaluation via Method of Moments** [[paper](https://arxiv.org/abs/2505.22169)]
- [2025] **FisherSFT: Data-Efficient Supervised Fine-Tuning of Language Models Using Information Gain** [[paper](https://arxiv.org/abs/2505.14826)]
- [2025] **Evaluating Artificial Intelligence-Based Writing Assistance Among Published Orthopaedic Studies** *Journal of Bone and Joint Surgery* [[paper](https://doi.org/10.2106/jbjs.24.01462)]
- [2025] **Developing A Framework to Support Human Evaluation of Bias in Generated Free Response Text** [[paper](https://arxiv.org/abs/2505.03053)]
- [2025] **4Hammer: a board-game reinforcement learning environment for the hour long time frame** [[paper](https://arxiv.org/abs/2505.13638)]
- [2025] **Towards Test Generation from Task Description for Mobile Testing with Multi-modal Reasoning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.15917)]
- [2025] **ScholarCopilot: Training Large Language Models for Academic Writing with Accurate Citations** [[paper](https://arxiv.org/abs/2504.00824)]
- [2025] **MEQA: A Meta-Evaluation Framework for Question &amp; Answer LLM Benchmarks** [[paper](https://arxiv.org/abs/2504.14039)]
- [2025] **Large Language Models Could Be Rote Learners** [[paper](https://arxiv.org/abs/2504.08300)]
- [2025] **Iterative Self-Training for Code Generation via Reinforced Re-Ranking** [[paper](https://arxiv.org/abs/2504.09643)]
- [2025] **Confidence in Large Language Model Evaluation: A Bayesian Approach to Limited-Sample Challenges** [[paper](https://arxiv.org/abs/2504.21303)]
- [2025] **Comparing Text Augmentation by GPT-3.5 and Llama3 for Evaluating Student Responses** *International Journal of Artificial Intelligence in Education* [[paper](https://doi.org/10.1007/s40593-025-00473-x)]
- [2025] **Automated Verilog Assertion Generation Using Fine-Tuned LLMs with Subtask-Specific Iterative Prompting** [[paper](https://doi.org/10.1109/isqed65160.2025.11014349)]
- [2025] **Automated Creativity Evaluation for Large Language Models: A Reference-Based Approach** [[paper](https://arxiv.org/abs/2504.15784)]
- [2025] **Assessing LLMs in Art Contexts: Critique Generation and Theory of Mind Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.12805)]
- [2025] **The Writer In-between: A Post-phenomenological Analysis of LLMs and their Implications for Writer-Tool Relationships** *Journal of Human-Technology Relations* [[paper](https://doi.org/10.59490/jhtr.2025.3.7398)]
- [2025] **Poor Alignment and Steerability of Large Language Models: Evidence from College Admission Essays** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.20062)]
- [2025] **OASST-ETC Dataset: Alignment Signals from Eye-tracking Analysis of LLM Responses** [[paper](https://arxiv.org/abs/2503.10927)]
- [2025] **Modifying Large Language Model Post-Training for Diverse Creative Writing** [[paper](https://arxiv.org/abs/2503.17126)]
- [2025] **DuSK: Faster Indirect Text Entry Supporting Out-Of-Vocabulary Words for Touchpads** [[paper](https://arxiv.org/abs/2503.02133)]
- [2025] **Automated UI Interface Generation via Diffusion Models: Enhancing Personalization and Efficiency** [[paper](https://arxiv.org/abs/2503.20229)]
- [2025] **Writing Style Matters: An Examination of Bias and Fairness in Information Retrieval Systems** [[paper](https://arxiv.org/abs/2411.13173)]
- [2025] **Which of These Best Describes Multiple Choice Evaluation with LLMs? A) Forced B) Flawed C) Fixable D) All of the Above** [[paper](https://arxiv.org/abs/2502.14127)]
- [2025] **Timing Matters: How Using LLMs at Different Timings Influences Writers' Perceptions and Ideation Outcomes in AI-Assisted Ideation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.06197)]
- [2025] **The Science of Evaluating Foundation Models** [[paper](https://arxiv.org/abs/2502.09670)]
- [2025] **Predicting Liquidity-Aware Bond Yields using Causal GANs and Deep Reinforcement Learning with LLM Evaluation** [[paper](https://arxiv.org/abs/2502.17011)]
- [2025] **Multilingual Encoder Knows more than You Realize: Shared Weights Pretraining for Extremely Low-Resource Languages** [[paper](https://arxiv.org/abs/2502.10852)]
- [2025] **Multi-turn Evaluation of Anthropomorphic Behaviours in Large Language Models** [[paper](https://arxiv.org/abs/2502.07077)]
- [2025] **Mind the Gap! Choice Independence in Using Multilingual LLMs for Persuasive Co-Writing Tasks in Different Languages** [[paper](https://arxiv.org/abs/2502.09532)]
- [2025] **LemmaHead: RAG Assisted Proof Generation Using Large Language Models** *Qeios* [[paper](https://doi.org/10.32388/rfa8le)]
- [2025] **Large language models for scientific discovery in molecular property prediction** *Nature Machine Intelligence* [[paper](https://doi.org/10.1038/s42256-025-00994-z)]
- [2025] **Energy-Conscious LLM Decoding: Impact of Text Generation Strategies on GPU Energy Consumption** [[paper](https://arxiv.org/abs/2502.11723)]
- [2025] **An Empirical Analysis of Uncertainty in Large Language Model Evaluations** [[paper](https://arxiv.org/abs/2502.10709)] [[code](https://github.com/hasakiXie123/LLM-Evaluator-Uncertainty)]
- [2025] **AI versus human-generated multiple-choice questions for medical education: a cohort study in a high-stakes examination** *BMC Medical Education* [[paper](https://doi.org/10.1186/s12909-025-06796-6)]
- [2025] **Vision Language Models as Values Detectors** [[paper](https://arxiv.org/abs/2501.03957)]
- [2025] **Toyteller: AI-powered Visual Storytelling Through Toy-Playing with Character Symbols** [[paper](https://arxiv.org/abs/2501.13284)]
- [2025] **Software System Testing Assisted by Large Language Models: An Exploratory Study** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-80889-0_17)]
- [2025] **Safeguarding Large Language Models in Real-time with Tunable Safety-Performance Trade-offs** [[paper](https://arxiv.org/abs/2501.02018)]
- [2025] **Prototypical Human-AI Collaboration Behaviors from LLM-Assisted Writing in the Wild** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.852)]
- [2025] **Improving Clinical Note Generation from Complex Doctor-Patient Conversation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-8186-0_17)]
- [2025] **Fine-Tuning Large Language Models Using Nlp and a Self-Organizing Map for Genre-Based Automated Writing Evaluation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5117045)]
- [2025] **Environmental large language model Evaluation (ELLE) dataset: A Benchmark for Evaluating Generative AI applications in Eco-environment Domain** [[paper](https://arxiv.org/abs/2501.06277)] [[code](https://github.com/CEEAI/elle)]
- [2025] **Citation by Completion: LLM Writing Aids and the Redistribution of Academic Credits** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5575851)]
- [2025] **Bridging Language Barriers: Causal Evidence on the Scholarly Impact of LLM-Assisted Writing** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5378725)]
- [2025] **Beyond Text Generation: Assessing Large Language Models’ Ability to Reason Logically and Follow Strict Rules** *AI* [[paper](https://doi.org/10.3390/ai6010012)]
- [2025] **Benchmarking Large Language Models for Cryptanalysis and Side-Channel Vulnerabilities** [[paper](https://doi.org/10.18653/v1/2025.findings-emnlp.1082)]

##### 2024

- [2024] **LMUnit: Fine-grained Evaluation with Natural Language Unit Tests** [[paper](https://arxiv.org/abs/2412.13091)]
- [2024] **LLM-Based Business Process Documentation Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-0805-8_27)]
- [2024] **How to Choose a Threshold for an Evaluation Metric for Large Language Models** [[paper](https://arxiv.org/abs/2412.12148)]
- [2024] **How secure is AI-generated code: a large-scale comparison of large language models** *Empirical Software Engineering* [[paper](https://arxiv.org/abs/2404.18353)]
- [2024] **HalluCana: Fixing LLM Hallucination with A Canary Lookahead** [[paper](https://arxiv.org/abs/2412.07965)]
- [2024] **Exploring AI Text Generation, Retrieval-Augmented Generation, and Detection Technologies: a Comprehensive Overview** [[paper](https://arxiv.org/abs/2412.03933)]
- [2024] **Data augmented large language models for medical record generation** *Applied Intelligence* [[paper](https://doi.org/10.1007/s10489-024-05934-9)]
- [2024] **Ranking Unraveled: Recipes for LLM Rankings in Head-to-Head AI Combat** [[paper](https://arxiv.org/abs/2411.14483)]
- [2024] **ProverbEval: Exploring LLM Evaluation Challenges for Low-resource Language Understanding** [[paper](https://arxiv.org/abs/2411.05049)] [[code](https://github.com/EthioNLP/EthioProverbEval)] [[project](https://huggingface.co/datasets/israel/ProverbEval,)]
- [2024] **Perceiving and Countering Hate: The Role of Identity in Online Responses** [[paper](https://arxiv.org/abs/2411.01675)]
- [2024] **Large Language Models** [[paper](https://doi.org/10.4324/9781032688503-13)]
- [2024] **LLM-Ref: Enhancing Reference Handling in Technical Writing with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.00294)]
- [2024] **Evaluating the Consistency of LLM Evaluators** [[paper](https://arxiv.org/abs/2412.00543)]
- [2024] **Early Results of an AI Multiagent System for Requirements Elicitation and Analysis** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-78386-9_20)]
- [2024] **Community Perspectives on ChatGPT: Sentiment Analysis in Educational Forum** *TechTrends* [[paper](https://doi.org/10.1007/s11528-024-01012-6)]
- [2024] **Chinese SimpleQA: A Chinese Factuality Evaluation for Large Language Models** [[paper](https://arxiv.org/abs/2411.07140)]
- [2024] **Benchmarking Multimodal Models for Ukrainian Language Understanding Across Academic and Cultural Domains** [[paper](https://arxiv.org/abs/2411.14647)]
- [2024] **Automatic High-quality Verilog Assertion Generation through Subtask-Focused Fine-Tuned LLMs and Iterative Prompting** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.15442)]
- [2024] **Adding Error Bars to Evals: A Statistical Approach to Language Model Evaluations** [[paper](https://arxiv.org/abs/2411.00640)]
- [2024] **A Framework for Evaluating LLMs Under Task Indeterminacy** *NeurIPS 2024 Workshops on Evaluating Evaluations* [[paper](https://arxiv.org/abs/2411.13760)]
- [2024] **Understanding Forgetting in LLM Supervised Fine-Tuning and Preference Learning -- A Convex Optimization Perspective** [[paper](https://arxiv.org/abs/2410.15483)] [[code](https://github.com/heshandevaka/XRIGHT)]
- [2024] **Towards Reproducible LLM Evaluation: Quantifying Uncertainty in LLM Benchmark Scores** [[paper](https://arxiv.org/abs/2410.03492)]
- [2024] **Towards Multilingual LLM Evaluation for European Languages** [[paper](https://arxiv.org/abs/2410.08928)]
- [2024] **TouchInsight: Uncertainty-aware Rapid Touch and Text Input for Mixed Reality from Egocentric Vision** [[paper](https://arxiv.org/abs/2410.05940)]
- [2024] **Self-Preference Bias in LLM-as-a-Judge** *NeurIPS 2024 Safe Generative AI Workshop* [[paper](https://arxiv.org/abs/2410.21819)]
- [2024] **RevisEval: Improving LLM-as-a-Judge via Response-Adapted References** [[paper](https://arxiv.org/abs/2410.05193)]
- [2024] **MiLoRA: Efficient Mixture of Low-Rank Adaptation for Large Language Models Fine-tuning** [[paper](https://arxiv.org/abs/2410.18035)]
- [2024] **Malinowski in the Age of AI: Can large language models create a text game based on an anthropological classic?** [[paper](https://arxiv.org/abs/2410.20536)]
- [2024] **Humanizing the Machine: Proxy Attacks to Mislead LLM Detectors** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.19230)]
- [2024] **Human-Computer Interaction and Visualization in Natural Language Generation Models: Applications, Challenges, and Opportunities** [[paper](https://arxiv.org/abs/2410.08723)]
- [2024] **Generating Signed Language Instructions in Large-Scale Dialogue Systems** [[paper](https://arxiv.org/abs/2410.14026)] [[code](https://github.com/Merterm/signed-dialogue)] [[project](https://huggingface.co/spaces/merterm/signed-instructions)]
- [2024] **Enterprise Benchmarks for Large Language Model Evaluation** [[paper](https://arxiv.org/abs/2410.12857)]
- [2024] **Decoding Game: On Minimax Optimality of Heuristic Text Generation Strategies** [[paper](https://arxiv.org/abs/2410.03968)]
- [2024] **AI-Powered Multi-Agent Framework for Automated Unit Test Case Generation: Enhancing Software Quality through LLM’s** [[paper](https://doi.org/10.1109/gcat62922.2024.10923987)]
- [2024] **Multi-Programming Language Ensemble for Code Generation in Large Language Model** [[paper](https://arxiv.org/abs/2409.04114)] [[code](https://github.com/NinjaTech-AI/MPLE)]
- [2024] **Large Language Model Use in Radiology Residency Applications: Unwelcomed but Inevitable** *Journal of the American College of Radiology* [[paper](https://doi.org/10.1016/j.jacr.2024.08.027)]
- [2024] **Kalahi: A handcrafted, grassroots cultural LLM evaluation suite for Filipino** [[paper](https://arxiv.org/abs/2409.15380)]
- [2024] **HELPD: Mitigating Hallucination of LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding** [[paper](https://arxiv.org/abs/2409.20429)]
- [2024] **Customizing Large Language Model Generation Style using Parameter-Efficient Finetuning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.04574)]
- [2024] **Beyond Fine-tuning: Unleashing the Potential of Continuous Pretraining for Clinical LLMs** [[paper](https://arxiv.org/abs/2409.14988)]
- [2024] **Backtracking Improves Generation Safety** [[paper](https://arxiv.org/abs/2409.14586)]
- [2024] **AI Suggestions Homogenize Writing Toward Western Styles and Diminish Cultural Nuances** [[paper](https://arxiv.org/abs/2409.11360)]
- [2024] **A Perspective on Literary Metaphor in the Context of Generative AI** [[paper](https://arxiv.org/abs/2409.01053)]
- [2024] **Unraveling Text Generation in LLMs: A Stochastic Differential Equation Approach** [[paper](https://arxiv.org/abs/2408.11863)]
- [2024] **Transforming Learning: Assessing the Efficacy of a Retrieval-Augmented Generation System as a Tutor for Introductory Psychology** *Proceedings of the Human Factors and Ergonomics Society Annual Meeting* [[paper](https://doi.org/10.1177/10711813241275509)]
- [2024] **The transformative impact of large language models on medical writing and publishing: current applications, challenges and future directions** *Korean Journal of Physiology and Pharmacology* [[paper](https://doi.org/10.4196/kjpp.2024.28.5.393)]
- [2024] **The creative psychometric item generator: a framework for item generation and validation using large language models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.00202)]
- [2024] **MODOC: A Modular Interface for Flexible Interlinking of Text Retrieval and Text Generation Functions** [[paper](https://arxiv.org/abs/2408.14623)]
- [2024] **Generative Artificial Intelligence Tools in Gastroenterology Training** *Clinical Gastroenterology and Hepatology* [[paper](https://doi.org/10.1016/j.cgh.2024.05.050)]
- [2024] **Controllable Text Generation for Large Language Models: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.12599)]
- [2024] **CBF-LLM: Safe Control for LLM Alignment** [[paper](https://arxiv.org/abs/2408.15625)] [[code](https://github.com/Mya-Mya/CBF-LLM)]
- [2024] **AI Managed Emergency Documentation with a Pretrained Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.09193)]
- [2024] **A Bibliometric Analysis of Trust in Conversational Agents over the Past Fifteen Years** [[paper](https://arxiv.org/abs/2408.16837)]
- [2024] **Turning Up the Heat: Min-p Sampling for Creative and Coherent LLM Outputs** *ICLR 2025. Camera-ready version available at https* [[paper](https://arxiv.org/abs/2407.01082)]
- [2024] **Probability of Differentiation Reveals Brittleness of Homogeneity Bias in GPT-4** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.07329)]
- [2024] **On the attribution of confidence to large language models** [[paper](https://arxiv.org/abs/2407.08388)]
- [2024] **On Evaluating The Performance of Watermarked Machine-Generated Texts Under Adversarial Attacks** [[paper](https://arxiv.org/abs/2407.04794)]
- [2024] **LAAG-RV: LLM Assisted Assertion Generation for RTL Design Verification** [[paper](https://doi.org/10.1109/itcindia62949.2024.10651860)]
- [2024] **Inference acceleration for large language models using "stairs" assisted greedy generation** [[paper](https://arxiv.org/abs/2407.19947)]
- [2024] **Detecting LLM-assisted writing in scientific communication: Are we there yet?** *Journal of Data and Information Science* [[paper](https://arxiv.org/abs/2401.16807)]
- [2024] **Beyond Benchmarking: A New Paradigm for Evaluation and Assessment of Large Language Models** [[paper](https://arxiv.org/abs/2407.07531)]
- [2024] **AI-generated text in otolaryngology publications: a comparative analysis before and after the release of ChatGPT.** *European Archives of Oto-Rhino-Laryngology* [[paper](https://doi.org/10.1007/s00405-024-08834-3)]
- [2024] **A Systematic Survey and Critical Review on Evaluating Large Language Models: Challenges, Limitations, and Recommendations** *EMNLP 2024* [[paper](https://arxiv.org/abs/2407.04069)]
- [2024] **A Comparative Analysis of Large Language Models for Code Documentation Generation** [[paper](https://doi.org/10.1145/3664646.3664765)]
- [2024] **ReceiptSense: Beyond Traditional OCR -- A Dataset for Receipt Understanding** [[paper](https://arxiv.org/abs/2406.04493)] [[code](https://github.com/Update-For-Integrated-Business-AI/CORU)]
- [2024] **ReadCtrl: Personalizing text generation with readability-controlled instruction learning** [[paper](https://arxiv.org/abs/2406.09205)]
- [2024] **QOG:Question and Options Generation based on Language Model** [[paper](https://arxiv.org/abs/2406.12381)]
- [2024] **QCQA: Quality and Capacity-aware grouped Query Attention** [[paper](https://arxiv.org/abs/2406.10247)]
- [2024] **Multi-property Steering of Large Language Models with Dynamic Activation Composition** [[paper](https://arxiv.org/abs/2406.17563)]
- [2024] **MixEval: Deriving Wisdom of the Crowd from LLM Benchmark Mixtures** [[paper](https://arxiv.org/abs/2406.06565)]
- [2024] **Large Language Models as Evaluators for Recommendation Explanations** [[paper](https://arxiv.org/abs/2406.03248)] [[code](https://github.com/Xiaoyu-SZ/LLMasEvaluator)]
- [2024] **From Decoding to Meta-Generation: Inference-time Algorithms for Large Language Models** [[paper](https://arxiv.org/abs/2406.16838)]
- [2024] **Fairer Preferences Elicit Improved Human-Aligned Large Language Model Judgments** [[paper](https://arxiv.org/abs/2406.11370)]
- [2024] **Demystifying ChatGPT: An In-depth Survey of OpenAI’s Robust Large Language Models** *Archives of Computational Methods in Engineering* [[paper](https://doi.org/10.1007/s11831-024-10115-5)]
- [2024] **Benchmark Data Contamination of Large Language Models: A Survey** [[paper](https://arxiv.org/abs/2406.04244)]
- [2024] **Analyzing constrained LLM through PDFA-learning** [[paper](https://arxiv.org/abs/2406.08269)]
- [2024] **xFinder: Large Language Models as Automated Evaluators for Reliable Evaluation** [[paper](https://arxiv.org/abs/2405.11874)]
- [2024] **T^2 of Thoughts: Temperature Tree Elicits Reasoning in Large Language Models** [[paper](https://arxiv.org/abs/2405.14075)]
- [2024] **Supercharging Document Composition with Generative AI: A Secure, Custom Retrieval-Augmented Generation Approach** [[paper](https://dx.doi.org/10.1109/sds60720.2024.00025)]
- [2024] **Open Ko-LLM Leaderboard: Evaluating Large Language Models in Korean with Ko-H5 Benchmark** *ACL 2024 Main* [[paper](https://arxiv.org/abs/2405.20574)]
- [2024] **Narrative Review of Emotional Expression Support in XR: Psychophysiology of Speech-to-Text Interfaces** [[paper](https://arxiv.org/abs/2405.13924)]
- [2024] **Multi-Aspect Controllable Text Generation with Disentangled Counterfactual Augmentation** [[paper](https://arxiv.org/abs/2405.19958)] [[code](https://github.com/nju-websoft/MAGIC)]
- [2024] **LLM Discussion: Enhancing the Creativity of Large Language Models via Discussion Framework and Role-Play** [[paper](https://arxiv.org/abs/2405.06373)] [[code](https://github.com/lawraa/LLM-Discussion)]
- [2024] **Evaluating large language models in medical applications: a survey** [[paper](https://arxiv.org/abs/2405.07468)]
- [2024] **Enhancing user experience in large language models through human-centered design: Integrating theoretical insights with an experimental study to meet diverse software learning needs with a single document knowledge base** [[paper](https://arxiv.org/abs/2405.11505)]
- [2024] **Decoding moral judgement from text: a pilot study** [[paper](https://arxiv.org/abs/2407.00039)]
- [2024] **Collage is the New Writing: Exploring the Fragmentation of Text and User Interfaces in AI Tools** [[paper](https://arxiv.org/abs/2405.17217)]
- [2024] **Children's Mental Models of Generative Visual and Text Based AI Models** [[paper](https://arxiv.org/abs/2405.13081)]
- [2024] **ChatGPT’s ability to generate realistic experimental images poses a new challenge to academic integrity** *Journal of Hematology & Oncology* [[paper](https://doi.org/10.1186/s13045-024-01543-8)]
- [2024] **Unveiling LLM Evaluation Focused on Metrics: Challenges and Solutions** [[paper](https://arxiv.org/abs/2404.09135)]
- [2024] **Understandable Test Generation Through Capture/Replay and LLMs** [[paper](https://doi.org/10.1145/3639478.3639789)]
- [2024] **Paraphrase and Solve: Exploring and Exploiting the Impact of Surface Form on Mathematical Reasoning in Large Language Models** [[paper](https://arxiv.org/abs/2404.11500)]
- [2024] **Large Language Model Empowered Next-Generation MIMO Networks: Fundamentals, Challenges, and Visions** [[paper](https://arxiv.org/abs/2404.08878)]
- [2024] **LLM-RadJudge: Achieving Radiologist-Level Evaluation for X-Ray Report Generation** [[paper](https://arxiv.org/abs/2404.00998)]
- [2024] **Is ChatGPT Transforming Academics' Writing Style?** [[paper](https://arxiv.org/abs/2404.08627)]
- [2024] **Generalization Measures for Zero-Shot Cross-Lingual Transfer** [[paper](https://arxiv.org/abs/2404.15928)]
- [2024] **Creative Beam Search: LLM-as-a-Judge For Improving Response Generation** [[paper](https://arxiv.org/abs/2405.00099)]
- [2024] **The Value, Benefits, and Concerns of Generative AI-Powered Assistance in Writing** [[paper](https://arxiv.org/abs/2403.12004)]
- [2024] **The Potential of Neural Network Potentials** *ACS Physical Chemistry Au* [[paper](https://doi.org/10.1021/acsphyschemau.4c00004)]
- [2024] **LLMs as Writing Assistants: Exploring Perspectives on Sense of Ownership and Reasoning** [[paper](https://arxiv.org/abs/2404.00027)]
- [2024] **From Consumers to Critical Users: Prompty, an AI Literacy Tool for High School Students** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i21.30378)]
- [2024] **Crossing Linguistic Horizons: Finetuning and Comprehensive Evaluation of Vietnamese Large Language Models** [[paper](https://arxiv.org/abs/2403.02715)]
- [2024] **An Ensemble LLM Framework of Text Recognition Based on BERT and BPE Tokenization** [[paper](https://doi.org/10.1109/ainit61980.2024.10581466)]
- [2024] **-generAItor: Tree-in-the-loop Text Generation for Language Model Explainability and Adaptation** *ACM Transactions on Interactive Intelligent Systems* [[paper](https://arxiv.org/abs/2403.07627)]
- [2024] **StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback** [[paper](https://arxiv.org/abs/2402.01391)]
- [2024] **QASE Enhanced PLMs: Improved Control in Text Generation for MRC** [[paper](https://arxiv.org/abs/2403.04771)]
- [2024] **KMMLU: Measuring Massive Multitask Language Understanding in Korean** [[paper](https://arxiv.org/abs/2402.11548)]
- [2024] **With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation** [[paper](https://arxiv.org/abs/2401.11504)]
- [2024] **When Content is Goliath and Algorithm is David: The Style and Semantic Effects of Generative Search Engine** *SSRN Electronic Journal* [[paper](https://arxiv.org/abs/2402.19421)]
- [2024] **Soft Self-Consistency Improves Language Models Agents** [[paper](https://doi.org/10.18653/v1/2024.acl-short.28)]
- [2024] **Reinforced Subject-Aware Graph Neural Network for Related Work Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-97-5492-2_16)]
- [2024] **Red Teaming Language Model Detectors with Language Models** *Transactions of the Association for Computational Linguistics* [[paper](https://doi.org/10.1162/tacl_a_00639)]
- [2024] **Please note that I’m just an AI: Analysis of Behavior Patterns of LLMs in (Non-)offensive Speech Identification** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-main.1019)]
- [2024] **Overall Writing Effectiveness: Exploring Students’ Use of LLMs, Pushing the Limits of Automated Text Generation** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-031-61905-2_2)]
- [2024] **NL2CTL: Automatic Generation of Formal Requirements Specifications via Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-0617-7_1)]
- [2024] **Monte Carlo Tree Search for Recipe Generation using GPT-2** [[paper](https://arxiv.org/abs/2401.05199)]
- [2024] **Language Models can Evaluate Themselves via Probability Discrepancy** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.291)]
- [2024] **LLM-Based Structuring of Oral Discussion in Workshop to Support Collaboration Among Local Government and Simulated Citizens** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-67998-8_1)]
- [2024] **Knowledge Planning in Large Language Models for Domain-Aligned Counseling Summarization** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.984)]
- [2024] **IndicGenBench: A Multilingual Benchmark to Evaluate Generation Capabilities of LLMs on Indic Languages** [[paper](https://doi.org/10.18653/v1/2024.acl-long.595)]
- [2024] **Generating Diverse and High-Quality Texts by Minimum Bayes Risk Decoding** [[paper](https://arxiv.org/abs/2401.05054)]
- [2024] **Evaluating LLM -- Generated Multimodal Diagnosis from Medical Images and Symptom Analysis** [[paper](https://arxiv.org/abs/2402.01730)]
- [2024] **Ethical Use of Large Language Models in Academic Research and Writing: A How-To** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.4950138)]
- [2024] **Automated Comment Generation Based on the Large Language Model** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-97-0730-0_25)]
- [2024] **Auffusion: Leveraging the Power of Diffusion and Large Language Models for Text-to-Audio Generation** [[paper](https://arxiv.org/abs/2401.01044)]
- [2024] **Accelerating Multilingual Language Model for Excessively Tokenized Languages** [[paper](https://arxiv.org/abs/2401.10660)]

##### 2023

- [2023] **Using Large Language Models to Accelerate Communication for Users with Severe Motor Impairments** [[paper](https://arxiv.org/abs/2312.01532)]
- [2023] **ToViLaG: Your Visual-Language Generative Model is Also An Evildoer** [[paper](https://arxiv.org/abs/2312.11523)]
- [2023] **LLM-SQL-Solver: Can LLMs Determine SQL Equivalence?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.10321)]
- [2023] **From Voices to Validity: Leveraging Large Language Models (LLMs) for Textual Analysis of Policy Stakeholder Interviews** [[paper](https://arxiv.org/abs/2312.01202)]
- [2023] **Exploiting Novel GPT-4 APIs** [[paper](https://arxiv.org/abs/2312.14302)]
- [2023] **Enhancing Hybrid Eye Typing Interfaces with Word and Letter Prediction: A Comprehensive Evaluation** [[paper](https://arxiv.org/abs/2312.08731)]
- [2023] **An Extended Variational Mode Decomposition Algorithm Developed Speech Emotion Recognition Performance** [[paper](https://arxiv.org/abs/2312.10937)]
- [2023] **Unrolling Virtual Worlds for Immersive Experiences** [[paper](https://arxiv.org/abs/2311.17924)]
- [2023] **Post Turing: Mapping the landscape of LLM Evaluation** [[paper](https://arxiv.org/abs/2311.02049)]
- [2023] **Pearl: Personalizing Large Language Model Writing Assistants with Generation-Calibrated Retrievers** *EMNLP 2024* [[paper](https://arxiv.org/abs/2311.09180)]
- [2023] **PEMA: An Offsite-Tunable Plug-in External Memory Adaptation for Language Models** [[paper](https://arxiv.org/abs/2311.08590)]
- [2023] **Neural Authorship Attribution: Stylometric Analysis on Large Language Models** [[paper](https://doi.org/10.1109/cyberc58899.2023.00019)]
- [2023] **Model-Based Minimum Bayes Risk Decoding for Text Generation** [[paper](https://arxiv.org/abs/2311.05263)]
- [2023] **Leveraging High-Level Synthesis and Large Language Models to Generate, Simulate, and Deploy a Uniform Random Number Generator Hardware Design** [[paper](https://arxiv.org/abs/2311.03489)]
- [2023] **LIMIT: Less Is More for Instruction Tuning Across Evaluation Paradigms** [[paper](https://arxiv.org/abs/2311.13133)]
- [2023] **An Assessment of ChatGPT on Log Data** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-99-7587-7_13)]
- [2023] **Pseudointelligence: A Unifying Framework for Language Model Evaluation** [[paper](https://arxiv.org/abs/2310.12135)]
- [2023] **Parameter-Efficient Tuning Helps Language Model Alignment** [[paper](https://arxiv.org/abs/2310.00819)]
- [2023] **Is ChatGPT a Financial Expert? Evaluating Language Models on Financial Natural Language Processing** [[paper](https://arxiv.org/abs/2310.12664)]
- [2023] **InfoDiffusion: Information Entropy Aware Diffusion Process for Non-Autoregressive Text Generation** [[paper](https://arxiv.org/abs/2310.11976)]
- [2023] **Establishing Vocabulary Tests as a Benchmark for Evaluating Large Language Models** [[paper](https://arxiv.org/abs/2310.14703)]
- [2023] **DATATALES: Investigating the use of Large Language Models for Authoring Data-Driven Articles** [[paper](https://doi.org/10.1109/vis54172.2023.00055)]
- [2023] **CrossData: Leveraging Text-Data Connections for Authoring Data Documents** [[paper](https://arxiv.org/abs/2310.11639)]
- [2023] **Auto-Instruct: Automatic Instruction Generation and Ranking for Black-Box Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.13127)]
- [2023] **Specializing Small Language Models towards Complex Style Transfer via Latent Attribute Pre-Training** [[paper](https://arxiv.org/abs/2309.10929)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Are LLM-based Chatbots Good Enough to Support Computer Science Students in Multiple-Choice Exercises?** [[paper](https://arxiv.org/abs/2606.15919)]
- [2026] **AUTOMATED PROFESSIONAL DOCUMENT GENERATION USING LARGE LANGUAGE MODELS FOR CAREER APPLICATIONS** *EPRA International Journal of Multidisciplinary Research (IJMR)* [[paper](https://doi.org/10.36713/epra27875)]
- [2026] **The PICCO Framework for Large Language Model Prompting: A Taxonomy and Reference Architecture for Prompt Structure** [[paper](https://arxiv.org/abs/2604.14197)]
- [2026] **PSYCHOMETRIC MODEL FOR VALIDATING LLM-GENERATED TASKS FOR MICRO-ASSESSMENT IN LANGUAGE TESTING** *Information Technologies and Learning Tools* [[paper](https://doi.org/10.33407/itlt.v112i2.6572)]
- [2026] **Guidelines to Prompt Large Language Models for Code Generation: An Empirical Characterization** [[paper](https://doi.org/10.1145/3794763.3794819)]
- [2026] **Hallucination to Consensus: Multi-Agent LLMs for End-to-End JUnit Test Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://arxiv.org/abs/2506.02943)]
- [2026] **Customizing ChatGPT for Second Language Speaking Practice: Genuine Support or Just a Marketing Gimmick?** [[paper](https://arxiv.org/abs/2603.14884)]
- [2026] **Large Language Models (LLMS) for Clinical Note Generation: International Classification of Disease (ICD) Code, Knowledge Graph (KG) and Prompt Evaluation** *ODU Digital Commons (Old Dominion University)* [[paper](https://digitalcommons.odu.edu/computerscience_etds/197)]
- [2026] **Evaluating Prompt Engineering Strategies for Sentiment Control in AI-Generated Texts** [[paper](https://arxiv.org/abs/2602.06692)]
- [2026] **Simplify-This: A Comparative Analysis of Prompt-Based and Fine-Tuned LLMs** [[paper](https://arxiv.org/abs/2601.05794)]
- [2026] **Securing LLM code generation: Leveraging prompt engineering to mitigate vulnerabilities across models and languages** *Science of Computer Programming* [[paper](https://doi.org/10.1016/j.scico.2026.103446)]
- [2026] **Large Language Models for Creative Writing Collaboration with Human Authors in Storytelling** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2026.01.024)]
- [2026] **From Instruction to Output: The Role of Prompting in Modern NLG** [[paper](https://arxiv.org/abs/2602.11179)]
- [2026] **Exploring Approaches for Detecting Memorization of Recommender System Data in Large Language Models** [[paper](https://arxiv.org/abs/2601.02002)]
- [2026] **Automatic Prompt Engineering with No Task Cues and No Tuning** [[paper](https://arxiv.org/abs/2601.03130)]

##### 2025

- [2025] **Prompt engineering does not universally improve Large Language Model performance across clinical decision-making tasks** [[paper](https://arxiv.org/abs/2512.22966)]
- [2025] **Decoding the Black Box: Discerning AI Rhetorics About and Through Poetic Prompting** [[paper](https://arxiv.org/abs/2512.05243)]
- [2025] **BanglaForge: LLM Collaboration with Self-Refinement for Bangla Code Generation** [[paper](https://arxiv.org/abs/2512.19122)]
- [2025] **AI-generated neurology consultation summaries improve efficiency and reduce documentation burden in the emergency department** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-22769-7)]
- [2025] **Unraveling Emotions with Pre-Trained Models** [[paper](https://arxiv.org/abs/2510.19668)]
- [2025] **Lightweight Prompt Engineering for Cognitive Alignment in Educational AI: A OneClickQuiz Case Study** [[paper](https://arxiv.org/abs/2510.03374)]
- [2025] **Learning to Rewrite Prompts for Bootstrapping LLMs on Downstream Tasks** [[paper](https://arxiv.org/abs/2510.06695)]
- [2025] **Generations of Generating a Cytology Report** *Veterinary Clinical Pathology* [[paper](https://doi.org/10.1111/vcp.70074)]
- [2025] **The Prompt Engineering Report Distilled: Quick Start Guide for Life Sciences** [[paper](https://arxiv.org/abs/2509.11295)]
- [2025] **The Impact of Role Design in In-Context Learning for Large Language Models** [[paper](https://arxiv.org/abs/2509.23501)]
- [2025] **A vibe coding learning design to enhance EFL students' talking to, through, and about AI** [[paper](https://arxiv.org/abs/2509.08854)]
- [2025] **The Prompting Brain: Neurocognitive Markers of Expertise in Guiding Large Language Models** [[paper](https://arxiv.org/abs/2508.14869)]
- [2025] **Guardians and Offenders: A Survey on Harmful Content Generation and Safety Mitigation of LLM** [[paper](https://arxiv.org/abs/2508.05775)]
- [2025] **Can AI Have a Personality? Prompt Engineering for AI Personality Simulation: A Chatbot Case Study in Gender-Affirming Voice Therapy Training** [[paper](https://arxiv.org/abs/2508.18234)]
- [2025] **Resource-Efficient Adaptation of Large Language Models for Text Embeddings via Prompt Engineering and Contrastive Fine-tuning** [[paper](https://arxiv.org/abs/2507.22729)]
- [2025] **Large Language Models (LLMs) for Healthcare** *Productivity Press eBooks* [[paper](https://doi.org/10.4324/9781003541769)]
- [2025] **The Safety Reminder: A Soft Prompt to Reactivate Delayed Safety Awareness in Vision-Language Models** [[paper](https://arxiv.org/abs/2506.15734)]
- [2025] **Prompt Engineering Techniques for Mitigating Cultural Bias Against Arabs and Muslims in Large Language Models: A Systematic Review** [[paper](https://arxiv.org/abs/2506.18199)]
- [2025] **Prompt Engineering Large Language Models' Forecasting Capabilities** [[paper](https://arxiv.org/abs/2506.01578)]
- [2025] **S2LPP: Small-to-Large Prompt Prediction across LLMs** [[paper](https://arxiv.org/abs/2505.20097)]
- [2025] **Evaluating Prompt Engineering Techniques for Accuracy and Confidence Elicitation in Medical LLMs** [[paper](https://arxiv.org/abs/2506.00072)]
- [2025] **Ensuring Reproducibility in Generative AI Systems for General Use Cases: A Framework for Regression Testing and Open Datasets** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.02854)]
- [2025] **Critical thinking in the age of generative AI: implications for health sciences education** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1571527)]
- [2025] **Compensating for Data with Reasoning: Low-Resource Machine Translation with LLMs** [[paper](https://arxiv.org/abs/2505.22293)]
- [2025] **What's the Difference? Supporting Users in Identifying the Effects of Prompt and Model Changes Through Token Patterns** *ACL* [[paper](https://arxiv.org/abs/2504.15815)]
- [2025] **The Future of MLLM Prompting is Adaptive: A Comprehensive Experimental Evaluation of Prompt Engineering Methods for Robust Multimodal Performance** [[paper](https://arxiv.org/abs/2504.10179)]
- [2025] **Self-Adaptive Cognitive Debiasing for Large Language Models in Decision-Making** [[paper](https://arxiv.org/abs/2504.04141)]
- [2025] **Reflexive Prompt Engineering: A Framework for Responsible Prompt Engineering and Interaction Design** [[paper](https://arxiv.org/abs/2504.16204)]
- [2025] **Local Prompt Optimization** *NAACL 2025* [[paper](https://arxiv.org/abs/2504.20355)]
- [2025] **DDPT: Diffusion-Driven Prompt Tuning for Large Language Model Code Generation** [[paper](https://arxiv.org/abs/2504.04351)]
- [2025] **CoTAL: Human-in-the-Loop Prompt Engineering for Generalizable Formative Assessment Scoring and Feedback** [[paper](https://arxiv.org/abs/2504.02323)]
- [2025] **Beyond the Next Token: Towards Prompt-Robust Zero-Shot Classification via Efficient Multi-Token Prediction** *NAACL 2025* [[paper](https://arxiv.org/abs/2504.03159)]
- [2025] **Beyond Human Limits: The Promise and Pitfalls of Large Language Models in Radiology Research** *Journal of Computer Assisted Tomography* [[paper](https://doi.org/10.1097/rct.0000000000001709)]
- [2025] **Aplicação de Large Language Models na Análise e Síntese de Documentos Jurídicos: Uma Revisão de Literatura** [[paper](https://arxiv.org/abs/2504.00725)]
- [2025] **Transforming hematological research documentation with large language models: an approach to scientific writing and data analysis** *Blood Research* [[paper](https://doi.org/10.1007/s44313-025-00062-w)]
- [2025] **Prompt Sentiment: The Catalyst for LLM Change** [[paper](https://arxiv.org/abs/2503.13510)]
- [2025] **BanglAssist: A Bengali-English Generative AI Chatbot for Code-Switching and Dialect-Handling in Customer Service** [[paper](https://arxiv.org/abs/2503.22283)]
- [2025] **A Systematic Evaluation of LLM Strategies for Mental Health Text Analysis: Fine-tuning vs. Prompt Engineering vs. RAG** [[paper](https://arxiv.org/abs/2503.24307)]
- [2025] **UM_FHS at TREC 2024 PLABA: Exploration of Fine-tuning and AI agent approach for plain language adaptations of biomedical text** [[paper](https://arxiv.org/abs/2502.14144)]
- [2025] **Prompting in the Dark: Assessing Human Performance in Prompt Engineering for Data Labeling When Gold Labels Are Absent** [[paper](https://arxiv.org/abs/2502.11267)]
- [2025] **Emulating Retrieval Augmented Generation via Prompt Engineering for Enhanced Long Context Comprehension in LLMs** [[paper](https://arxiv.org/abs/2502.12462)]
- [2025] **Effects of Prompt Length on Domain-specific Tasks for Large Language Models** [[paper](https://arxiv.org/abs/2502.14255)]
- [2025] **Earnings Call Scripts Generation With Large Language Models Using Few‐Shot Learning Prompt Engineering and Fine‐Tuning Methods** *Applied AI Letters* [[paper](https://doi.org/10.1002/ail2.110)]
- [2025] **Code Summarization Beyond Function Level** [[paper](https://arxiv.org/abs/2502.16704)] [[code](https://github.com/kilimanj4r0/code-summarization-beyond-function-level)]
- [2025] **A Systematic Survey of Automatic Prompt Optimization Techniques** [[paper](https://arxiv.org/abs/2502.16923)]
- [2025] **Sharing Experiences on Artificial Intelligence Through Prompt Engineering to Create CNC Programs in an Engineering Course** *Lecture notes in educational technology* [[paper](https://doi.org/10.1007/978-981-95-5234-4_3)]
- [2025] **Network-informed Prompt Engineering against Organized Astroturf Campaigns under Extreme Class Imbalance** [[paper](https://arxiv.org/abs/2501.11849)]
- [2025] **Code Generation Using LLMs** *International Journal of Future Engineering Innovations* [[paper](https://doi.org/10.54660/ijfei.2025.2.2.16-22)]
- [2025] **A Sequential Optimal Learning Approach to Automated Prompt Engineering in Large Language Models** [[paper](https://arxiv.org/abs/2501.03508)]

##### 2024

- [2024] **iPrOp: Interactive Prompt Optimization for Large Language Models with a Human in the Loop** [[paper](https://arxiv.org/abs/2412.12644)]
- [2024] **The Synergy of Automated Pipelines with Prompt Engineering and Generative AI in Web Crawling** [[paper](https://arxiv.org/abs/2502.15691)]
- [2024] **The Role of Prompt Engineering in Improving Language Understanding and Generation** *International Journal For Multidisciplinary Research* [[paper](https://doi.org/10.36948/ijfmr.2024.v06i06.32232)]
- [2024] **A Machine Learning Approach for Emergency Detection in Medical Scenarios Using Large Language Models** [[paper](https://arxiv.org/abs/2412.16341)]
- [2024] **RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance** [[paper](https://arxiv.org/abs/2410.01242)]
- [2024] **Performance in a dialectal profiling task of LLMs for varieties of Brazilian Portuguese** [[paper](https://arxiv.org/abs/2410.10991)]
- [2024] **Intelligent Understanding of Large Language Models in Traditional Chinese Medicine Based on Prompt Engineering Framework** [[paper](https://arxiv.org/abs/2410.19451)]
- [2024] **Generating Synthetic Datasets for Few-shot Prompt Tuning** [[paper](https://arxiv.org/abs/2410.10865)]
- [2024] **Exploring Prompt Engineering: A Systematic Review with SWOT Analysis** [[paper](https://arxiv.org/abs/2410.12843)]
- [2024] **Comparative Study of Multilingual Idioms and Similes in Large Language Models** [[paper](https://arxiv.org/abs/2410.16461)]
- [2024] **Coal Mining Question Answering with LLMs** [[paper](https://arxiv.org/abs/2410.02959)]
- [2024] **Automatic deductive coding in discourse analysis: an application of large language models in learning analytics** [[paper](https://arxiv.org/abs/2410.01240)]
- [2024] **A Systematic Review on Prompt Engineering in Large Language Models for K-12 STEM Education** [[paper](https://arxiv.org/abs/2410.11123)]
- [2024] **Counterfactual Token Generation in Large Language Models** [[paper](https://arxiv.org/abs/2409.17027)]
- [2024] **Beyond Scores: A Modular RAG-Based System for Automatic Short Answer Scoring with Feedback** [[paper](https://arxiv.org/abs/2409.20042)]
- [2024] **A Looming Replication Crisis in Evaluating Behavior in Language Models? Evidence and Solutions** [[paper](https://arxiv.org/abs/2409.20303)]
- [2024] **Toward Large Language Models as a Therapeutic Tool: Comparing Prompting Techniques to Improve GPT-Delivered Problem-Solving Therapy** [[paper](https://arxiv.org/abs/2409.00112)]
- [2024] **Leveraging Large Language Models with Chain-of-Thought and Prompt Engineering for Traffic Crash Severity Analysis and Inference** [[paper](https://arxiv.org/abs/2408.04652)]
- [2024] **Leveraging Language Models for Emotion and Behavior Analysis in Education** [[paper](https://arxiv.org/abs/2408.06874)]
- [2024] **LLM-assisted Labeling Function Generation for Semantic Type Detection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.16173)]
- [2024] **Evaluating the Impact of Advanced LLM Techniques on AI-Lecture Tutors for a Robotics Course** [[paper](https://arxiv.org/abs/2408.04645)]
- [2024] **Conversational Prompt Engineering** [[paper](https://arxiv.org/abs/2408.04560)]
- [2024] **Using Grammar Masking to Ensure Syntactic Validity in LLM-based Modeling Tasks** [[paper](https://arxiv.org/abs/2407.06146)]
- [2024] **RB-SQL: A Retrieval-based LLM Framework for Text-to-SQL** [[paper](https://arxiv.org/abs/2407.08273)]
- [2024] **PAS: Data-Efficient Plug-and-Play Prompt Augmentation System** [[paper](https://arxiv.org/abs/2407.06027)]
- [2024] **Hard Prompts Made Interpretable: Sparse Entropy Regularization for Prompt Tuning with RL** [[paper](https://arxiv.org/abs/2407.14733)]
- [2024] **Generation and Evaluation of a Culturally-Relevant CS1 Textbook for Latines using Large Language Models** [[paper](https://doi.org/10.1145/3649217.3653600)]
- [2024] **GRAD-SUM: Leveraging Gradient Summarization for Optimal Prompt Engineering** [[paper](https://arxiv.org/abs/2407.12865)]
- [2024] **Enhancing Agricultural Machinery Management through Advanced LLM Integration** [[paper](https://arxiv.org/abs/2407.20588)]
- [2024] **Effects of a Prompt Engineering Intervention on Undergraduate Students' AI Self-Efficacy, AI Knowledge and Prompt Engineering Ability: A Mixed Methods Study** [[paper](https://arxiv.org/abs/2408.07302)]
- [2024] **Educational Personalized Learning Path Planning with Large Language Models** [[paper](https://arxiv.org/abs/2407.11773)]
- [2024] **Concise Thoughts: Impact of Output Length on LLM Reasoning and Cost** [[paper](https://arxiv.org/abs/2407.19825)]
- [2024] **APE: Active Learning-based Tooling for Finding Informative Few-shot Examples for LLM-based Entity Matching** [[paper](https://arxiv.org/abs/2408.04637)]
- [2024] **A Survey of Prompt Engineering Methods in Large Language Models for Different NLP Tasks** [[paper](https://arxiv.org/abs/2407.12994)]
- [2024] **The Prompt Report: A Systematic Survey of Prompt Engineering Techniques** [[paper](https://arxiv.org/abs/2406.06608)]
- [2024] **Demonstration Notebook: Finding the Most Suited In-Context Learning Example from Interactions** [[paper](https://arxiv.org/abs/2406.10878)]
- [2024] **Autonomous Prompt Engineering in Large Language Models** [[paper](https://arxiv.org/abs/2407.11000)]
- [2024] **Actionable Cyber Threat Intelligence using Knowledge Graphs and Large Language Models** [[paper](https://arxiv.org/abs/2407.02528)]
- [2024] **A Tool for Test Case Scenarios Generation Using Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.07021)]
- [2024] **Towards AI-Driven Healthcare: Systematic Optimization, Linguistic Analysis, and Clinicians’ Evaluation of Large Language Models for Smoking Cessation Interventions** [[paper](https://doi.org/10.1145/3613904.3641965)]
- [2024] **Revolutionizing Process Mining: A Novel Architecture for ChatGPT Integration and Enhanced User Experience through Optimized Prompt Engineering** [[paper](https://arxiv.org/abs/2405.10689)]
- [2024] **Prompt engineering paradigms for medical applications: scoping review and recommendations for better practices** [[paper](https://arxiv.org/abs/2405.01249)]
- [2024] **Using large language models for safety-related table summarization in clinical study reports** *JAMIA Open* [[paper](https://doi.org/10.1093/jamiaopen/ooae043)]
- [2024] **Position Engineering: Boosting Large Language Models through Positional Information Manipulation** [[paper](https://arxiv.org/abs/2404.11216)]
- [2024] **Plug and Play with Prompts: A Prompt Tuning Approach for Controlling Text Generation** *AAAI-2024* [[paper](https://arxiv.org/abs/2404.05143)]
- [2024] **Integrating Chemistry Knowledge in Large Language Models via Prompt Engineering** [[paper](https://arxiv.org/abs/2404.14467)]
- [2024] **Generation of Backward-Looking Complex Reflections for a Motivational Interviewing–Based Smoking Cessation Chatbot Using GPT-4: Algorithm Development and Validation** *JMIR Mental Health* [[paper](https://doi.org/10.2196/53778)]
- [2024] **Towards Full Authorship with AI: Supporting Revision with AI-Generated Views** [[paper](https://arxiv.org/abs/2403.01055)]
- [2024] **LAMPER: LanguAge Model and Prompt EngineeRing for zero-shot time series classification** *ICLR 2024* [[paper](https://arxiv.org/abs/2403.15875)]
- [2024] **DataAgent: Evaluating Large Language Models' Ability to Answer Zero-Shot, Natural Language Queries** [[paper](https://arxiv.org/abs/2404.00188)]
- [2024] **AI on AI: Exploring the Utility of GPT as an Expert Annotator of AI Publications** [[paper](https://arxiv.org/abs/2403.09097)]
- [2024] **A comparison of Human, GPT-3.5, and GPT-4 Performance in a University-Level Coding Course** [[paper](https://arxiv.org/abs/2403.16977)]
- [2024] **Using Large Language Models to Automate and Expedite Reinforcement Learning with Reward Machine** [[paper](https://arxiv.org/abs/2402.07069)]
- [2024] **Style Vectors for Steering Generative Large Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01618)]
- [2024] **Semantic Mirror Jailbreak: Genetic Algorithm Based Jailbreak Prompts Against Open-source LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.14872)]
- [2024] **Intent-based Prompt Calibration: Enhancing prompt optimization with synthetic boundary cases** [[paper](https://arxiv.org/abs/2402.03099)] [[code](https://github.com/Eladlev/AutoPrompt)]
- [2024] **GhostWriter: Augmenting Collaborative Human-AI Writing Experiences Through Personalization and Agency** [[paper](https://arxiv.org/abs/2402.08855)]
- [2024] **An Empirical Categorization of Prompting Techniques for Large Language Models: A Practitioner's Guide** [[paper](https://arxiv.org/abs/2402.14837)]
- [2024] **A Systematic Survey of Prompt Engineering in Large Language Models: Techniques and Applications** [[paper](https://arxiv.org/abs/2402.07927)]
- [2024] **Wordflow: Social Prompt Engineering for Large Language Models** [[paper](https://arxiv.org/abs/2401.14447)] [[project](https://poloclub.github.io/wordflow)]
- [2024] **Towards Goal-oriented Prompt Engineering for Large Language Models: A Survey** [[paper](https://arxiv.org/abs/2401.14043)]
- [2024] **Quantifying Similarity: Text-Mining Approaches to Evaluate ChatGPT and Google Bard Content in Relation to BioMedical Literature** [[paper](https://arxiv.org/abs/2402.05116)]
- [2024] **PRewrite: Prompt Rewriting with Reinforcement Learning** [[paper](https://arxiv.org/abs/2401.08189)]
- [2024] **OMPGPT: A Generative Pre-trained Transformer Model for OpenMP** [[paper](https://arxiv.org/abs/2401.16445)]
- [2024] **Code Generation with AlphaCodium: From Prompt Engineering to Flow Engineering** [[paper](https://arxiv.org/abs/2401.08500)] [[code](https://github.com/Codium-ai/AlphaCodium)]

##### 2023

- [2023] **Enhancing Medical Task Performance in GPT-4V: A Comprehensive Study on Prompt Engineering Strategies** [[paper](https://arxiv.org/abs/2312.04344)]
- [2023] **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation** [[paper](https://arxiv.org/abs/2312.13010)]
- [2023] **To be or not to be? an exploration of continuously controllable prompt engineering** [[paper](https://arxiv.org/abs/2311.09773)]
- [2023] **Prompt Engineering a Prompt Engineer** [[paper](https://arxiv.org/abs/2311.05661)]
- [2023] **On the Discussion of Large Language Models: Symmetry of Agents and Interplay with Prompts** [[paper](https://arxiv.org/abs/2311.07076)]
- [2023] **MemoryCompanion: A Smart Healthcare Solution to Empower Efficient Alzheimer's Care Via Unleashing Generative AI** [[paper](https://arxiv.org/abs/2311.14730)]
- [2023] **I Was Blind but Now I See: Implementing Vision-Enabled Dialogue in Social Robots** [[paper](https://arxiv.org/abs/2311.08957)]
- [2023] **Efficient Black-Box Adversarial Attacks on Neural Text Detectors** [[paper](https://arxiv.org/abs/2311.01873)]
- [2023] **What's the Magic Word? A Control Theory of LLM Prompting** [[paper](https://arxiv.org/abs/2310.04444)]
- [2023] **Unleashing the potential of prompt engineering for large language models** [[paper](https://arxiv.org/abs/2310.14735)]
- [2023] **Prompt-Engineering and Transformer-based Question Generation and Evaluation** [[paper](https://arxiv.org/abs/2310.18867)]
- [2023] **On the Safety of Open-Sourced Large Language Models: Does Alignment Really Prevent Them From Being Misused?** [[paper](https://arxiv.org/abs/2310.01581)]
- [2023] **Model Tuning or Prompt Tuning? A Study of Large Language Models for Clinical Concept and Relation Extraction** [[paper](https://arxiv.org/abs/2310.06239)]
- [2023] **Interactive Task Planning with Language Models** [[paper](https://arxiv.org/abs/2310.10645)] [[project](https://wuphilipp.github.io/itp_site)]
- [2023] **Generation of Backward-Looking Complex Reflections for a Motivational Interviewing-Based Smoking Cessation Chatbot using GPT-4 (Preprint)** [[paper](https://doi.org/10.2196/preprints.53778)]
- [2023] **Demonstrations of the Potential of AI-based Political Issue Polling** *Harvard Data Science Review* [[paper](https://doi.org/10.1162/99608f92.1d3cf75d)]
- [2023] **Apollo: Zero-shot MultiModal Reasoning with Multiple Experts** [[paper](https://arxiv.org/abs/2310.18369)]
- [2023] **AdaRefiner: Refining Decisions of Language Models with Adaptive Feedback** [[paper](https://arxiv.org/abs/2309.17176)]
- [2023] **A Brief History of Prompt: Leveraging Language Models. (Through Advanced Prompting)** [[paper](https://arxiv.org/abs/2310.04438)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **FLARE: Few-shot Learning-based Adaptive Reflective Engine** [[paper](https://arxiv.org/abs/2608.02919)]
- [2026] **HalluTruthQA: A Fine-Grained Benchmark for Hallucination Detection, Localization, and Explanation in Arabic Question Answering** [[paper](https://arxiv.org/abs/2607.20219)]
- [2026] **Circuit Tracing in Autoregressive Protein Language Models** *ICML 2026. 24 pages* [[paper](https://arxiv.org/abs/2606.16044)]
- [2026] **Evi-Steer: Learning to Steer Biomedical Vision-Language Models through Efficient and Generalizable Evidential Tuning** [[paper](https://arxiv.org/abs/2605.26292)] [[code](https://github.com/HealthX-Lab/Evi-Steer)]
- [2026] **StoryCoder: Narrative Reformulation for Structured Reasoning in LLM Code Generation** [[paper](https://arxiv.org/abs/2604.14631)] [[code](https://github.com/gu-ni/StoryCoder)]
- [2026] **Understanding code semantics: a benchmark study of LLMs** *International Journal on Software Tools for Technology Transfer* [[paper](https://doi.org/10.1007/s10009-026-00842-4)]
- [2026] **Text Style Transfer with Parameter-efficient LLM Finetuning and Round-trip Translation** [[paper](https://arxiv.org/abs/2602.15013)]
- [2026] **ARGUS: Seeing the Influence of Narrative Features on Persuasion in Argumentative Texts** [[paper](https://arxiv.org/abs/2602.24109)]
- [2026] **Can LLMs Write Correct TLA + Specifications? Evaluating Natural-Language-to-TLA + Generation** [[paper](https://arxiv.org/abs/2606.05792)]
- [2026] **An artificial intelligence-driven platform for practice question generation** *Academic Medicine* [[paper](https://doi.org/10.1093/acamed/wvaf074)]

##### 2025

- [2025] **MiMo-Audio: Audio Language Models are Few-Shot Learners** [[paper](https://arxiv.org/abs/2512.23808)] [[code](https://github.com/XiaomiMiMo/MiMo-Audio)]
- [2025] **Complementary Learning Approach for Text Classification using Large Language Models** [[paper](https://arxiv.org/abs/2512.07583)]
- [2025] **Reasoning-Guided Claim Normalization for Noisy Multilingual Social Media Posts** [[paper](https://arxiv.org/abs/2511.05078)]
- [2025] **MAPROC at AHaSIS Shared Task: Few-Shot and Sentence Transformer for Sentiment Analysis of Arabic Hotel Reviews** [[paper](https://arxiv.org/abs/2511.15291)]
- [2025] **Evaluating AI Models for Autograding Explain in Plain English Questions: Challenges and Considerations** *ACM Transactions on Interactive Intelligent Systems* [[paper](https://doi.org/10.1145/3774752)]
- [2025] **How Well Do Llms Imitate Human Writing Style?** [[paper](https://doi.org/10.1109/uemcon67449.2025.11267719)]
- [2025] **EEschematic: Multimodal-LLM Based AI Agent for Schematic Generation of Analog Circuit** [[paper](https://arxiv.org/abs/2510.17002)]
- [2025] **Beyond Correctness: Evaluating Subjective Writing Preferences Across Cultures** [[paper](https://arxiv.org/abs/2510.14616)]
- [2025] **AcademicEval: Live Long-Context LLM Benchmark** [[paper](https://arxiv.org/abs/2510.17725)] [[code](https://github.com/ulab-uiuc/AcademicEval)]
- [2025] **MLSD: A Novel Few-Shot Learning Approach to Enhance Cross-Target and Cross-Domain Stance Detection** [[paper](https://arxiv.org/abs/2509.03725)]
- [2025] **GemDetox at TextDetox CLEF 2025: Enhancing a Massively Multilingual Model for Text Detoxification on Low-resource Languages** [[paper](https://arxiv.org/abs/2510.01250)]
- [2025] **Controlled Generation for Private Synthetic Text** [[paper](https://arxiv.org/abs/2509.25729)]
- [2025] **A Study of Large Language Models for Patient Information Extraction: Model Architecture, Fine-Tuning Strategy, and Multi-task Instruction Tuning** [[paper](https://arxiv.org/abs/2509.04753)]
- [2025] **Retrieval-Augmented Review Generation for Poisoning Recommender Systems** [[paper](https://arxiv.org/abs/2508.15252)]
- [2025] **Prompt-Based Approach for Czech Sentiment Analysis** [[paper](https://arxiv.org/abs/2508.08651)]
- [2025] **Large Language Models: Evolution, Architecture, Applications, and Future Horizons** [[paper](https://doi.org/10.1109/icscsa66339.2025.11170884)]
- [2025] **ITUNLP at SemEval-2025 Task 8: Question-Answering over Tabular Data: A Zero-Shot Approach using LLM-Driven Code Generation** [[paper](https://arxiv.org/abs/2508.00762)]
- [2025] **E3RG: Building Explicit Emotion-driven Empathetic Response Generation System with Multimodal Large Language Model** [[paper](https://arxiv.org/abs/2508.12854)] [[code](https://github.com/RH-Lin/E3RG)]
- [2025] **AutoCodeBench: Large Language Models are Automatic Code Benchmark Generators** [[paper](https://arxiv.org/abs/2508.09101)]
- [2025] **Assessing Consciousness-Related Behaviors in Large Language Models Using the Maze Test** [[paper](https://arxiv.org/abs/2508.16705)]
- [2025] **A Language-based Approach to Macroprogramming for IoT Systems through Large Language Models** *ACM Transactions on Internet of Things* [[paper](https://doi.org/10.1145/3758326)]
- [2025] **WETBench: A Benchmark for Detecting Task-Specific Machine-Generated Text on Wikipedia** [[paper](https://arxiv.org/abs/2507.03373)]
- [2025] **TextOmics-Guided Diffusion for Hit-like Molecular Generation** [[paper](https://arxiv.org/abs/2507.09982)]
- [2025] **P-CoT: A Pedagogically-motivated Participatory Chain-of-Thought Prompting for Phonological Reasoning in LLMs** [[paper](https://arxiv.org/abs/2507.16656)]
- [2025] **LitBench: A Benchmark and Dataset for Reliable Evaluation of Creative Writing** [[paper](https://arxiv.org/abs/2507.00769)] [[project](https://huggingface.co/collections/SAA-Lab/litbench-68267b5da3aafe58f9e43461,)]
- [2025] **Cross-lingual Few-shot Learning for Persian Sentiment Analysis with Incremental Adaptation** [[paper](https://arxiv.org/abs/2507.11634)]
- [2025] **Cross-Domain Transfer and Few-Shot Learning for Personal Identifiable Information Recognition** [[paper](https://arxiv.org/abs/2507.11862)]
- [2025] **CLI-RAG: A Retrieval-Augmented Framework for Clinically Structured and Context Aware Text Generation with LLMs** [[paper](https://arxiv.org/abs/2507.06715)]
- [2025] **Beyond Scale: Small Language Models are Comparable to GPT-4 in Mental Health Understanding** [[paper](https://arxiv.org/abs/2507.08031)]
- [2025] **SplashNet: Split-and-Share Encoders for Accurate and Efficient Typing with Surface Electromyography** [[paper](https://arxiv.org/abs/2506.12356)]
- [2025] **Prompting as Scientific Inquiry** [[paper](https://arxiv.org/abs/2507.00163)]
- [2025] **MarginSel : Max-Margin Demonstration Selection for LLMs** [[paper](https://arxiv.org/abs/2506.06699)]
- [2025] **Improving Automatic Evaluation of Large Language Models (LLMs) in Biomedical Relation Extraction via LLMs-as-the-Judge** *ACL 2025* [[paper](https://arxiv.org/abs/2506.00777)] [[code](https://github.com/tahmedge/llm_judge_biomedical_re)]
- [2025] **Culture Matters in Toxic Language Detection in Persian** [[paper](https://arxiv.org/abs/2506.03458)]
- [2025] **ASTRAL: A Tool for the Automated Safety Testing of Large Language Models** [[paper](https://doi.org/10.1145/3713081.3731733)]
- [2025] **Understanding In-context Learning of Addition via Activation Subspaces** [[paper](https://arxiv.org/abs/2505.05145)]
- [2025] **TCSinger 2: Customizable Multilingual Zero-shot Singing Voice Synthesis** [[paper](https://arxiv.org/abs/2505.14910)] [[project](https://aaronz345.github.io/TCSinger2Demo/)]
- [2025] **SynDec: A Synthesize-then-Decode Approach for Arbitrary Textual Style Transfer via Large Language Models** [[paper](https://arxiv.org/abs/2505.12821)]
- [2025] **Optimized Story Generation using DeepSeek LLM with Supervised Fine-Tuning** [[paper](https://doi.org/10.1109/rmkmate64874.2025.11042725)]
- [2025] **Implementing Long Text Style Transfer with LLMs through Dual-Layered Sentence and Paragraph Structure Extraction and Mapping** [[paper](https://arxiv.org/abs/2505.07888)]
- [2025] **StyleRec: A Benchmark Dataset for Prompt Recovery in Writing Style Transformation** [[paper](https://arxiv.org/abs/2504.04373)]
- [2025] **Pre-trained Language Models and Few-shot Learning for Medical Entity Extraction** [[paper](https://arxiv.org/abs/2504.04385)]
- [2025] **HyPerAlign: Interpretable Personalized LLM Alignment via Hypothesis Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.00038)]
- [2025] **Enhancing NER Performance in Low-Resource Pakistani Languages using Cross-Lingual Data Augmentation** [[paper](https://arxiv.org/abs/2504.08792)]
- [2025] **Capturing Symmetry and Antisymmetry in Language Models through Symmetry-Aware Training Objectives** [[paper](https://arxiv.org/abs/2504.16312)]
- [2025] **ASTRAL: Automated Safety Testing of Large Language Models** [[paper](https://doi.org/10.1109/ast66626.2025.00018)]
- [2025] **Synthetic Data Augmentation for Cross-domain Implicit Discourse Relation Recognition** [[paper](https://arxiv.org/abs/2503.20588)]
- [2025] **Optimizing Large Language Models for Detecting Symptoms of Comorbid Depression or Anxiety in Chronic Diseases: Insights from Patient Messages** [[paper](https://arxiv.org/abs/2503.11384)]
- [2025] **Network Traffic Classification Using Machine Learning, Transformer, and Large Language Models** [[paper](https://arxiv.org/abs/2503.02141)]
- [2025] **Memory Is All You Need: Testing How Model Memory Affects LLM Performance in Annotation Tasks** [[paper](https://arxiv.org/abs/2503.04874)]
- [2025] **Medifact at PerAnsSumm 2025: Leveraging Lightweight Models for Perspective-Specific Summarization of Clinical Q&amp;A Forums** [[paper](https://arxiv.org/abs/2503.16513)]
- [2025] **Malware Classification from Memory Dumps Using Machine Learning, Transformers, and Large Language Models** [[paper](https://arxiv.org/abs/2503.02144)]
- [2025] **Learning to Search Effective Example Sequences for In-Context Learning** *NAACL 2025* [[paper](https://arxiv.org/abs/2503.08030)]
- [2025] **From User Preferences to Optimization Constraints Using Large Language Models** [[paper](https://arxiv.org/abs/2503.21360)]
- [2025] **ConvoGen: Enhancing Conversational AI with Synthetic Data: A Multi-Agent Approach** [[paper](https://arxiv.org/abs/2503.17460)]
- [2025] **Assessing Generative Models for Structured Data** [[paper](https://arxiv.org/abs/2503.20903)]
- [2025] **UltraGen: Extremely Fine-grained Controllable Generation via Attribute Reconstruction and Global Preference Optimization** [[paper](https://arxiv.org/abs/2502.12375)]
- [2025] **Modeling Narrative Structure in Latin Epic Poetry with Automatically Generated Story Grammars** [[paper](https://arxiv.org/abs/2502.12276)]
- [2025] **HuDEx: Integrating Hallucination Detection and Explainability for Enhancing the Reliability of LLM responses** [[paper](https://arxiv.org/abs/2502.08109)]
- [2025] **Explainable Sentiment Analysis with DeepSeek-R1: Performance, Efficiency, and Few-Shot Learning** [[paper](https://arxiv.org/abs/2503.11655)]
- [2025] **DiTAR: Diffusion Transformer Autoregressive Modeling for Speech Generation** [[paper](https://arxiv.org/abs/2502.03930)]
- [2025] **Active Few-Shot Learning for Text Classification** [[paper](https://arxiv.org/abs/2502.18782)]
- [2025] **Zero-shot and Few-shot Learning with Instruction-following LLMs for Claim Matching in Automated Fact-checking** [[paper](https://arxiv.org/abs/2501.10860)]
- [2025] **Unraveling the Capabilities of Language Models in News Summarization** [[paper](https://arxiv.org/abs/2501.18128)]
- [2025] **Towards Safer Social Media Platforms: Scalable and Performant Few-Shot Harmful Content Moderation Using Large Language Models** [[paper](https://arxiv.org/abs/2501.13976)]
- [2025] **Leveraging Domain Knowledge at Inference Time for LLM Translation: Retrieval versus Generation** [[paper](https://doi.org/10.18653/v1/2025.knowledgenlp-1.7)]
- [2025] **LLMs can see and hear without any training** [[paper](https://arxiv.org/abs/2501.18096)]
- [2025] **Evaluating and Improving Graph to Text Generation with Large Language Models** [[paper](https://arxiv.org/abs/2501.14497)] [[code](https://github.com/probe2/kg_text)]
- [2025] **End-to-End Automated Item Generation and Scoring for Adaptive English Writing Assessment with Large Language Models** [[paper](https://doi.org/10.18653/v1/2025.bea-1.73)]
- [2025] **Catch Me If You Can? Not Yet: LLMs Still Struggle to Imitate the Implicit Writing Styles of Everyday Authors** [[paper](https://doi.org/10.18653/v1/2025.findings-emnlp.532)]
- [2025] **Automated Ontology Generation for Zero-Shot Defect Identification in Manufacturing** *IEEE Transactions on Automation Science and Engineering* [[paper](https://doi.org/10.1109/tase.2025.3537463)]

##### 2024

- [2024] **X-Prompt: Towards Universal In-Context Image Generation in Auto-Regressive Vision Language Foundation Models** [[paper](https://arxiv.org/abs/2412.01824)]
- [2024] **ROUTE: Robust Multitask Tuning and Collaboration for Text-to-SQL** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.10138)]
- [2024] **PETapter: Leveraging PET-style classification heads for modular few-shot parameter-efficient fine-tuning** [[paper](https://arxiv.org/abs/2412.04975)]
- [2024] **Optimization Techniques in Large Language Models for News Report Generation** [[paper](https://doi.org/10.1109/emergin63207.2024.10961084)]
- [2024] **On the Generalization and Adaptation Ability of Machine-Generated Text Detectors in Academic Writing** [[paper](https://arxiv.org/abs/2412.17242)] [[code](https://github.com/Y-L-LIU/MGTBench-2.0)]
- [2024] **LitLLMs, LLMs for Literature Review: Are we there yet?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.15249)]
- [2024] **LLM Distillation for Efficient Few-Shot Multiple Choice Question Answering** [[paper](https://arxiv.org/abs/2412.09807)]
- [2024] **Does Few-Shot Learning Help LLM Performance in Code Synthesis?** [[paper](https://arxiv.org/abs/2412.02906)]
- [2024] **BioRAGent: A Retrieval-Augmented Generation System for Showcasing Generative Query Expansion and Domain-Specific Search for Scientific Q&amp;A** [[paper](https://arxiv.org/abs/2412.12358)]
- [2024] **An Agentic Approach to Automatic Creation of P&amp;ID Diagrams from Natural Language Descriptions** [[paper](https://arxiv.org/abs/2412.12898)]
- [2024] **Network for knowledge Organization (NEKO): An AI knowledge mining workflow for synthetic biology research** *Metabolic Engineering* [[paper](https://doi.org/10.1016/j.ymben.2024.11.006)]
- [2024] **In-Context Learning for Preserving Patient Privacy: A Framework for Synthesizing Realistic Patient Portal Messages** [[paper](https://arxiv.org/abs/2411.06549)]
- [2024] **CoCoP: Enhancing Text Classification with LLM through Code Completion Prompt** [[paper](https://arxiv.org/abs/2411.08979)]
- [2024] **Towards More Effective Table-to-Text Generation: Assessing In-Context Learning and Self-Evaluation with Open-Source Models** [[paper](https://arxiv.org/abs/2410.12878)]
- [2024] **Style-Specific Neurons for Steering LLMs in Text Style Transfer** *EMNLP 2024 main conference. The code is publicly available at https* [[paper](https://arxiv.org/abs/2410.00593)]
- [2024] **SPORTU: A Comprehensive Sports Understanding Benchmark for Multimodal Large Language Models** [[paper](https://arxiv.org/abs/2410.08474)]
- [2024] **Investigating Cost-Efficiency of LLM-Generated Training Data for Conversational Semantic Frame Analysis** [[paper](https://arxiv.org/abs/2410.06550)]
- [2024] **Context-Aware SQL Error Correction Using Few-Shot Learning -- A Novel Approach Based on NLQ, Error, and SQL Similarity** [[paper](https://arxiv.org/abs/2410.09174)]
- [2024] **CalliffusionV2: Personalized Natural Calligraphy Generation with Flexible Multi-modal Control** [[paper](https://arxiv.org/abs/2410.03787)]
- [2024] **Bridging Modalities: Enhancing Cross-Modality Hate Speech Detection with Few-Shot In-Context Learning** *EMNLP* [[paper](https://arxiv.org/abs/2410.05600)]
- [2024] **Visually Grounded Speech Models for Low-resource Languages and Cognitive Modelling** [[paper](https://arxiv.org/abs/2409.02865)]
- [2024] **TCSinger: Zero-Shot Singing Voice Synthesis with Style Transfer and Multi-Level Style Control** [[paper](https://arxiv.org/abs/2409.15977)] [[project](https://aaronz345.github.io/TCSingerDemo/)]
- [2024] **Improved Visually Prompted Keyword Localisation in Real Low-Resource Settings** [[paper](https://arxiv.org/abs/2409.06013)]
- [2024] **Evaluating the fairness of task-adaptive pretraining on unlabeled test data before few-shot text classification** *EMNLP 2024* [[paper](https://arxiv.org/abs/2410.00179)] [[code](https://github.com/kddubey/pretrain-on-test)]
- [2024] **Analysis of Socially Unacceptable Discourse with Zero-shot Learning** [[paper](https://arxiv.org/abs/2409.13735)]
- [2024] **Unlocking Exocentric Video-Language Data for Egocentric Video Representation Learning** [[paper](https://arxiv.org/abs/2408.03567)]
- [2024] **SpeechPrompt: Prompting Speech Language Models for Speech Processing Tasks** [[paper](https://arxiv.org/abs/2408.13040)]
- [2024] **Revisiting the Exit from Nuclear Energy in Germany with NLP** [[paper](https://arxiv.org/abs/2408.13810)]
- [2024] **Recording for Eyes, Not Echoing to Ears: Contextualized Spoken-to-Written Conversion of ASR Transcripts** [[paper](https://arxiv.org/abs/2408.09688)]
- [2024] **Granting GPT-4 License and Opportunity: Enhancing Accuracy and Confidence Estimation for Few-Shot Event Detection** [[paper](https://arxiv.org/abs/2408.00914)]
- [2024] **FLEURS-R: A Restored Multilingual Speech Corpus for Generation Tasks** [[paper](https://arxiv.org/abs/2408.06227)]
- [2024] **Chain-of-Thought in Neural Code Generation: From and for Lightweight Language Models** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3440503)]
- [2024] **Bridging the Language Gap: Enhancing Multilingual Prompt-Based Code Generation in LLMs via Zero-Shot Cross-Lingual Transfer** [[paper](https://arxiv.org/abs/2408.09701)]
- [2024] **Acquiring Bidirectionality via Large and Small Language Models** [[paper](https://arxiv.org/abs/2408.09640)]
- [2024] **Strengthening Structural Inductive Biases by Pre-training to Perform Syntactic Transformations** [[paper](https://arxiv.org/abs/2407.04543)]
- [2024] **Motamot: A Dataset for Revealing the Supremacy of Large Language Models over Transformer Models in Bengali Political Sentiment Analysis** [[paper](https://arxiv.org/abs/2407.19528)]
- [2024] **Evaluating Linguistic Capabilities of Multimodal LLMs in the Lens of Few-Shot Learning** [[paper](https://arxiv.org/abs/2407.12498)]
- [2024] **Evaluating Generative Artificial Intelligence on Multilingual Sentiment Analysis** *Journal of Electrical Systems* [[paper](https://dx.doi.org/10.52783/jes.4986)]
- [2024] **Dynamic Few-Shot Learning for Knowledge Graph Question Answering** [[paper](https://arxiv.org/abs/2407.01409)]
- [2024] **VHDL-Eval: A Framework for Evaluating Large Language Models in VHDL Code Generation** [[paper](https://arxiv.org/abs/2406.04379)]
- [2024] **TinyStyler: Efficient Few-Shot Text Style Transfer with Authorship Embeddings** [[paper](https://arxiv.org/abs/2406.15586)] [[project](https://huggingface.co/tinystyler/tinystyler)]
- [2024] **The current status of large language models in summarizing radiology report impressions** [[paper](https://arxiv.org/abs/2406.02134)]
- [2024] **Putting GPT-4o to the Sword: A Comprehensive Evaluation of Language, Vision, Speech, and Multimodal Proficiency** [[paper](https://arxiv.org/abs/2407.09519)]
- [2024] **Low-Resource Cross-Lingual Summarization through Few-Shot Learning with Large Language Models** [[paper](https://arxiv.org/abs/2406.04630)]
- [2024] **LongLaMP: A Benchmark for Personalized Long-form Text Generation** [[paper](https://arxiv.org/abs/2407.11016)]
- [2024] **LLM-based Rewriting of Inappropriate Argumentation using Reinforcement Learning from Machine Feedback** [[paper](https://arxiv.org/abs/2406.03363)]
- [2024] **Evaluating the Effectiveness of the Foundational Models for Q&amp;A Classification in Mental Health care** [[paper](https://arxiv.org/abs/2406.15966)]
- [2024] **Docimological Quality Analysis of LLM-Generated Multiple Choice Questions in Computer Science and Medicine** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-024-02963-6)]
- [2024] **Bilingual Sexism Classification: Fine-Tuned XLM-RoBERTa and GPT-3.5 Few-Shot Learning** [[paper](https://arxiv.org/abs/2406.07287)]
- [2024] **BADGE: BADminton report Generation and Evaluation with LLM** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.18116)]
- [2024] **Are Large Language Models Actually Good at Text Style Transfer?** [[paper](https://arxiv.org/abs/2406.05885)]
- [2024] **WisPerMed at BioLaySumm: Adapting Autoregressive Large Language Models for Lay Summarization of Scientific Articles** [[paper](https://arxiv.org/abs/2405.11950)]
- [2024] **UniGen: Universal Domain Generalization for Sentiment Classification via Zero-shot Dataset Generation** [[paper](https://arxiv.org/abs/2405.01022)]
- [2024] **TEII: Think, Explain, Interact and Iterate with Large Language Models to Solve Cross-lingual Emotion Detection** [[paper](https://arxiv.org/abs/2405.17129)]
- [2024] **RAGSys: Item-Cold-Start Recommender as RAG System** [[paper](https://arxiv.org/abs/2405.17587)]
- [2024] **Mashee at SemEval-2024 Task 8: The Impact of Samples Quality on the Performance of In-Context Learning for Machine Text Classification** [[paper](https://arxiv.org/abs/2406.17790)]
- [2024] **Large Language Models are Inconsistent and Biased Evaluators** [[paper](https://arxiv.org/abs/2405.01724)]
- [2024] **Investigating Wit, Creativity, and Detectability of Large Language Models in Domain-Specific Writing Style Adaptation of Reddit's Showerthoughts** [[paper](https://arxiv.org/abs/2405.01660)]
- [2024] **Enhancing News Summarization with ELearnFit through Efficient In-Context Learning and Efficient Fine-Tuning** [[paper](https://arxiv.org/abs/2405.02710)]
- [2024] **DrugLLM: Open Large Language Model for Few-shot Molecule Generation** [[paper](https://arxiv.org/abs/2405.06690)]
- [2024] **When LLMs are Unfit Use FastFit: Fast and Effective Text Classification with Many Classes** [[paper](https://arxiv.org/abs/2404.12365)]
- [2024] **Navigating the Landscape of Large Language Models: A Comprehensive Review and Analysis of Paradigms and Fine-Tuning Strategies** [[paper](https://arxiv.org/abs/2404.09022)]
- [2024] **Exploring LLM Prompting Strategies for Joint Essay Scoring and Feedback Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.15845)]
- [2024] **Evaluation of Few-Shot Learning for Classification Tasks in the Polish Language** [[paper](https://arxiv.org/abs/2404.17832)]
- [2024] **Enhancing Pre-Trained Generative Language Models with Question Attended Span Extraction on Machine Reading Comprehension** [[paper](https://arxiv.org/abs/2404.17991)]
- [2024] **Elephants Never Forget: Memorization and Learning of Tabular Data in Large Language Models** [[paper](https://arxiv.org/abs/2404.06209)] [[code](https://github.com/interpretml/LLM-Tabular-Memorization-Checker)]
- [2024] **AMU-Tuning: Effective Logit Bias for CLIP-based Few-shot Learning** [[paper](https://arxiv.org/abs/2404.08958)]
- [2024] **"A good pun is its own reword": Can Large Language Models Understand Puns?** [[paper](https://arxiv.org/abs/2404.13599)]
- [2024] **TaxoLLaMA: WordNet-based Model for Solving Multiple Lexical Semantic Tasks** [[paper](https://arxiv.org/abs/2403.09207)] [[code](https://github.com/VityaVitalich/TaxoLLaMA)]
- [2024] **Rethinking ASTE: A Minimalist Tagging Scheme Alongside Contrastive Learning** [[paper](https://arxiv.org/abs/2403.07342)]
- [2024] **RAT: Retrieval Augmented Thoughts Elicit Context-Aware Reasoning in Long-Horizon Generation** [[paper](https://arxiv.org/abs/2403.05313)] [[project](https://craftjarvis.github.io/RAT)]
- [2024] **Pragmatic Competence Evaluation of Large Language Models for the Korean Language** [[paper](https://arxiv.org/abs/2403.12675)]
- [2024] **PCToolkit: A Unified Plug-and-Play Prompt Compression Toolkit of Large Language Models** [[paper](https://arxiv.org/abs/2403.17411)]
- [2024] **Leveraging Weakly Annotated Data for Hate Speech Detection in Code-Mixed Hinglish: A Feasibility-Driven Transfer Learning Approach with Large Language Models** [[paper](https://arxiv.org/abs/2403.02121)]
- [2024] **Distilling Text Style Transfer With Self-Explanation From LLMs** [[paper](https://arxiv.org/abs/2403.01106)]
- [2024] **Designing Informative Metrics for Few-Shot Example Selection** [[paper](https://arxiv.org/abs/2403.03861)]
- [2024] **Analyzing and Adapting Large Language Models for Few-Shot Multilingual NLU: Are We There Yet?** [[paper](https://arxiv.org/abs/2403.01929)]
- [2024] **Unsupervised Text Style Transfer via LLMs and Attention Masking with Multi-way Interactions** [[paper](https://arxiv.org/abs/2402.13647)]
- [2024] **Technical Report on the Pangram AI-Generated Text Classifier** [[paper](https://arxiv.org/abs/2402.14873)]
- [2024] **SynthDST: Synthetic Data is All You Need for Few-Shot Dialog State Tracking** [[paper](https://arxiv.org/abs/2402.02285)] [[code](https://github.com/apple/ml-synthdst)]
- [2024] **Small Language Models as Effective Guides for Large Language Models in Chinese Relation Extraction** [[paper](https://arxiv.org/abs/2402.14373)]
- [2024] **Rethinking Skill Extraction in the Job Market Domain using Large Language Models** [[paper](https://arxiv.org/abs/2402.03832)]
- [2024] **Prompt-Based Bias Calibration for Better Zero/Few-Shot Learning of Language Models** [[paper](https://arxiv.org/abs/2402.10353)]
- [2024] **Modularized Networks for Few-shot Hateful Meme Detection** [[paper](https://arxiv.org/abs/2402.11845)]
- [2024] **Measuring and Reducing LLM Hallucination without Gold-Standard Answers** [[paper](https://arxiv.org/abs/2402.10412)]
- [2024] **Leveraging Large Language Models for Concept Graph Recovery and Question Answering in NLP Education** [[paper](https://arxiv.org/abs/2402.14293)]
- [2024] **In-Context Learning Demonstration Selection via Influence Analysis** [[paper](https://arxiv.org/abs/2402.11750)]
- [2024] **Automatic Combination of Sample Selection Strategies for Few-Shot Learning** [[paper](https://arxiv.org/abs/2402.03038)]
- [2024] **“A good pun is its own reword”: Can Large Language Models Understand Puns?** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.657)]
- [2024] **Zero-Shot RTL Code Generation with Attention Sink Augmented Large Language Models** [[paper](https://arxiv.org/abs/2401.08683)]
- [2024] **Make Prompts Adaptable: Bayesian Modeling for Vision-Language Prompt Learning with Data-Dependent Prior** [[paper](https://arxiv.org/abs/2401.06799)] [[code](https://github.com/youngjae-cho/APP)]
- [2024] **Leveraging Biases in Large Language Models: "bias-kNN'' for Effective Few-Shot Learning** [[paper](https://arxiv.org/abs/2401.09783)]
- [2024] **Investigating Wit, Creativity, and Detectability of Large Language Models in Domain-Specific Writing Style Adaptation of Reddit’s Showerthoughts** [[paper](https://dx.doi.org/10.18653/v1/2024.starsem-1.23)]
- [2024] **Correctness Comparison of ChatGPT-4, Gemini, Claude-3, and Copilot for Spatial Tasks** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.02404)]

##### 2023

- [2023] **StyleSinger: Style Transfer for Out-of-Domain Singing Voice Synthesis** [[paper](https://arxiv.org/abs/2312.10741)] [[project](https://aaronz345.github.io/StyleSingerDemo/)]
- [2023] **Instruct-SCTG: Guiding Sequential Controlled Text Generation through Instructions** [[paper](https://arxiv.org/abs/2312.12299)]
- [2023] **Few-shot learning for automated content analysis: Efficient coding of arguments and claims in the debate on arms deliveries to Ukraine** [[paper](https://arxiv.org/abs/2312.16975)]
- [2023] **Assertion Enhanced Few-Shot Learning: Instructive Technique for Large Language Models to Generate Educational Explanations** [[paper](https://arxiv.org/abs/2312.03122)]
- [2023] **Nexus at ArAIEval Shared Task: Fine-Tuning Arabic Language Models for Propaganda and Disinformation Detection** [[paper](https://arxiv.org/abs/2311.03184)]
- [2023] **Italian Crossword Generator: Enhancing Education through Interactive Word Puzzles** [[paper](https://arxiv.org/abs/2311.15723)]
- [2023] **In-context Vectors: Making In Context Learning More Effective and Controllable Through Latent Space Steering** [[paper](https://arxiv.org/abs/2311.06668)]
- [2023] **In-context Learning and Gradient Descent Revisited** [[paper](https://arxiv.org/abs/2311.07772)]
- [2023] **GenCodeSearchNet: A Benchmark Test Suite for Evaluating Generalization in Programming Language Understanding** [[paper](https://arxiv.org/abs/2311.09707)]
- [2023] **Function-constrained Program Synthesis** [[paper](https://arxiv.org/abs/2311.15500)]
- [2023] **CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation** [[paper](https://arxiv.org/abs/2311.18775)]
- [2023] **ClimateX: Do LLMs Accurately Assess Human Expert Confidence in Climate Statements?** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2311.17107)]
- [2023] **A Simple yet Efficient Ensemble Approach for AI-generated Text Detection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.03084)]
- [2023] **Retrofitting Light-weight Language Models for Emotions using Supervised Contrastive Learning** [[paper](https://arxiv.org/abs/2310.18930)]
- [2023] **Large Language Models are biased to overestimate profoundness** [[paper](https://arxiv.org/abs/2310.14422)]
- [2023] **Improving generalization in large language models by learning prefix subspaces** [[paper](https://arxiv.org/abs/2310.15793)] [[code](https://github.com/Liloulou/prefix_subspace)]
- [2023] **Eureka: Human-Level Reward Design via Coding Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.12931)]
- [2023] **Effectiveness of Generative Artificial Intelligence for Scientific Content Analysis** [[paper](https://doi.org/10.1109/aict59525.2023.10313167)]
- [2023] **EIPE-text: Evaluation-Guided Iterative Plan Extraction for Long-Form Narrative Text Generation** [[paper](https://arxiv.org/abs/2310.08185)]
- [2023] **A Few-Shot Learning Focused Survey on Recent Named Entity Recognition and Relation Classification Methods** [[paper](https://arxiv.org/abs/2310.19055)]
- [2023] **Toward Unified Controllable Text Generation via Regular Expression Instruction** [[paper](https://arxiv.org/abs/2309.10447)]
- [2023] **Is it Possible to Modify Text to a Target Readability Level? An Initial Investigation Using Zero-Shot Large Language Models** [[paper](https://arxiv.org/abs/2309.12551)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2025

- [2025] **Leveraging Natural Language Processing for the Computational Generation of Creative Writing** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202507.0702.v1)]

##### 2023

- [2023] **Copiloting the Copilots: Fusing Large Language Models with Completion Engines for Automated Program Repair** [[paper](https://arxiv.org/abs/2309.00608)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **Language Structure Convergence in Language Models** [[paper](https://osf.io/ypw4m)]
- [2026] **Writing creativity, cohesion, and formal linguistic competence in LLMs: A comparative evaluation based on English and Chinese continuation writing** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0335185)]
- [2026] **Overall performance of the four LLMs.** *Figshare* [[paper](https://figshare.com/articles/dataset/_p_Overall_performance_of_the_four_LLMs_p_/32763350)]
- [2026] **LLMs used in the present study.** *Figshare* [[paper](https://figshare.com/articles/dataset/_p_LLMs_used_in_the_present_study_p_/32763344)]
- [2026] **From Prompt to Play: A Haptic Instrument for Creative Writing with an LLM** [[paper](https://doi.org/10.1145/3805029.3818303)]
- [2026] **Enhancing creative writing with robot– LLM integration: The interplay of embodiment, AI creativity and user engagement** *British Journal of Educational Technology* [[paper](https://doi.org/10.1111/bjet.70071)]
- [2026] **LLM Token Estimation Benchmarks: Tokenizer Efficiency and Cost Analysis Across 17 Large Language Models** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19314967)]
- [2026] **LLM Review: Enhancing Creative Writing via Blind Peer Review Feedback** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.08003)]
- [2026] **An NLP-Based Evaluation of LLMs Across Creativity, Factual Accuracy, Open-Ended and Technical Explanations** *ICCK Transactions on Emerging Topics in Artificial Intelligence* [[paper](https://doi.org/10.62762/tetai.2025.264517)]

##### 2025

- [2025] **Human versus artificial creativity: A case study in poetry** *Journal of Creativity* [[paper](https://doi.org/10.1016/j.yjoc.2025.100118)]
- [2025] **Towards Personalized LLMs: Investigating Narrative Generation and Personality-Based Preferences in Large Language Models** *Brock University Digital Repository (Brock University)* [[paper](https://hdl.handle.net/10464/19509)]
- [2025] **Enhancing Genre Fidelity in Children's Story Generation via Fine-Tuned LLMs** [[paper](https://doi.org/10.1109/qpain66474.2025.11171897)]
- [2025] **Enhanced Language Generation Capabilities of Mistral 7B Using Quantized Parameter Efficient Fine-Tuning with Lora and Rag** [[paper](https://doi.org/10.1109/icctdc64446.2025.11158789)]
- [2025] **One Does Not Simply Meme Alone: Evaluating Co-Creativity Between LLMs and Humans in the Generation of Humor** [[paper](https://arxiv.org/abs/2501.11433)]
- [2025] **The Future of AI: Exploring the Potential of Large Concept Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.05487)]
- [2025] **CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.203)]

##### 2024

- [2024] **Evaluating Creative Short Story Generation in Humans and Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.02316)]
- [2024] **A Review of The Opportunities and Challenges with Large Language Models in Radiology: The Road Ahead** *American Journal of Neuroradiology* [[paper](https://doi.org/10.3174/ajnr.a8589)]
- [2024] **Re-imagen: Generating coherent background activity in synthetic scenario-based forensic datasets using large language models** *Forensic Science International Digital Investigation* [[paper](https://doi.org/10.1016/j.fsidi.2024.301805)]
- [2024] **Agents' Room: Narrative Generation through Multi-step Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.02603)]
- [2024] **Assessing Language Models' Worldview for Fiction Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.07904)]
- [2024] **Refining LLMs with Reinforcement Learning for Human-Like Text Generation** [[paper](https://doi.org/10.1109/conecct62155.2024.10677038)]
- [2024] **MM-Instruct: Generated Visual Instructions for Large Multimodal Model Alignment** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.19736)]
- [2024] **On the Taxonomy of Developers' Discussion Topics with ChatGPT** [[paper](https://doi.org/10.1145/3643991.3645080)]
- [2024] **BlogGen- A Blog Generation Application Using Llama-2** [[paper](https://doi.org/10.1109/adics58448.2024.10533489)]
- [2024] **Small But Funny: A Feedback-Driven Approach to Humor Distillation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.18113)]
- [2024] **Weaver: Foundation Models for Creative Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.17268)]
- [2024] **Subtle Biases Need Subtler Measures: Dual Metrics for Evaluating Representative and Affinity Bias in Large Language Models** [[paper](https://doi.org/10.18653/v1/2024.acl-long.23)]
- [2024] **SWAG: Storytelling With Action Guidance** [[paper](https://dx.doi.org/10.18653/v1/2024.findings-emnlp.824)]

##### 2023

- [2023] **Autonomous GIS: the next-generation AI-powered GIS** *International Journal of Digital Earth* [[paper](https://doi.org/10.1080/17538947.2023.2278895)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **Evaluating the Performance of Large Language Models in Academic Writing Tasks** *Dandao Xuebao/Journal of Ballistics* [[paper](https://doi.org/10.52783/dxjb.v38.348)]
- [2026] **Limitations and mitigation strategies for using generative artificial intelligence in medical writing: a narrative review** *Journal of Korean Medical Association* [[paper](https://doi.org/10.5124/jkma.25.0163)]
- [2026] **From Rubrics to Reliable Scores: Evidence-Grounded Text Evaluation with LLM Judges** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.08654)]

##### 2025

- [2025] **Generative Artificial Intelligence in English Language Education: Potential, Challenges, and the Path Forward** *TESOL Quarterly* [[paper](https://doi.org/10.1002/tesq.70042)]
- [2025] **ASSURE: Metamorphic Testing for AI-powered Browser Extensions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.05307)]
- [2025] **Utilizing Artificial Intelligence to Facilitate Qualitative Surgical Research** *Annals of Surgery Open* [[paper](https://doi.org/10.1097/as9.0000000000000577)]
- [2025] **A Comprehensive Analysis of Large Language Model Outputs: Similarity, Diversity, and Bias** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.09056)]
- [2025] **Navigating the Impact of Artificial Intelligence on Medical Writing** *Annals of Cardiac Anaesthesia* [[paper](https://doi.org/10.4103/aca.aca_14_25)]
- [2025] **Using AI Large Language Model (LLM-ChatGPT) to Mitigate Spelling Errors of EFL Learners** *Forum for Linguistic Studies* [[paper](https://doi.org/10.30564/fls.v7i3.8438)]
- [2025] **On protecting the data privacy of Large Language Models (LLMs) and LLM agents: A literature review** *High-Confidence Computing* [[paper](https://doi.org/10.1016/j.hcc.2025.100300)]
- [2025] **Evaluating LLMs for Arabic Code Summarization: Challenges and Insights from GPT-4** [[paper](https://doi.org/10.1109/cdma61895.2025.00017)]
- [2025] **DeepSeek versus ChatGPT: Multimodal artificial intelligence revolutionizing scientific discovery. From language editing to autonomous content generation—Redefining innovation in research and practice** *Knee Surgery Sports Traumatology Arthroscopy* [[paper](https://doi.org/10.1002/ksa.12628)]
- [2025] **Meetalk: Retrieval-Augmented and Adaptively Personalized Meeting Summarization with Knowledge Learning from User Corrections** [[paper](https://doi.org/10.18653/v1/2025.knowllm-1.9)]
- [2025] **Large Language Models for Automated Literature Review: An Evaluation of Reference Generation, Abstract Writing, and Review Composition** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.83)]
- [2025] **Intelligenza artificiale generativa nella medicina di laboratorio: innovazioni, limiti e considerazioni etiche** *Biochimica Clinica* [[paper](https://doi.org/10.23736/s0393-0564.24.00003-0)]

##### 2024

- [2024] **Context-aware Code Summary Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.09006)]
- [2024] **A Narrative Review on the Application of Large Language Models to Support Cancer Care and Research** *Yearbook of Medical Informatics* [[paper](https://doi.org/10.1055/s-0044-1800726)]
- [2024] **On the Evaluation of Machine-Generated Reports** [[paper](https://arxiv.org/abs/2405.00982)]
- [2024] **AviationGPT: A Large Language Model for the Aviation Domain** [[paper](https://doi.org/10.2514/6.2024-4250)]
- [2024] **Editorial: Large language models: from entertainment to solutions** *Digital Transformation and Society* [[paper](https://doi.org/10.1108/dts-04-2024-100)]

##### 2023

- [2023] **The ChatGPT therapist will see you now: Navigating generative artificial intelligence's potential in addiction medicine research and patient care** *Addiction* [[paper](https://doi.org/10.1111/add.16341)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **Measuring the Language in Language Models The Missing Writing Benchmark in Health Economics and Outcomes Research** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21343394)]

##### 2024

- [2024] **LaMPost: AI Writing Assistance for Adults with Dyslexia Using Large Language Models** *Communications of the ACM* [[paper](https://doi.org/10.1145/3626952)]
- [2024] **ABScribe: Rapid Exploration & Organization of Multiple Writing Variations in Human-AI Co-Writing Tasks using Large Language Models** [[paper](https://doi.org/10.1145/3613904.3641899)]
- [2024] **Neural Text Rewriting: Style Transfer, Figurative Language, and Beyond** [[paper](https://dx.doi.org/10.33612/diss.910519765)]
- [2024] **SpeciaLex: A Benchmark for In-Context Specialized Lexicon Learning** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.52)]

##### 2023

- [2023] **Using LLMs to bring evidence-based feedback into the classroom: AI-generated feedback increases secondary students’ text revision, motivation, and positive emotions** *Computers and Education Artificial Intelligence* [[paper](https://doi.org/10.1016/j.caeai.2023.100199)]

[⬆ Back to top](#paper-list)

#### Autocomplete

##### 2025

- [2025] **Why can’t epidemiology be automated (yet)?** *International Journal of Epidemiology* [[paper](https://arxiv.org/abs/2507.15617)]

##### 2024

- [2024] **Enhancing LLM Conversational Acuity Using Pragmatic Measures** [[paper](https://doi.org/10.1109/ictc62082.2024.10826785)]
- [2024] **Has artificial intelligence rendered language teaching obsolete?** *Modern Language Journal* [[paper](https://doi.org/10.1111/modl.12929)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **WriteGuard-X: Constraint-Governed LLM Assistance for Ethical Scientific Writing** [[paper](https://doi.org/10.1109/wccst67302.2026.11496178)]
- [2026] **Automatic Corpus Query Generation Method Based on Large Language Model** *DOAJ (DOAJ: Directory of Open Access Journals)* [[paper](https://doaj.org/article/8707f818952e4dd59d01896a41e8c073)]

##### 2025

- [2025] **The Transparency Paradox: Why Researchers Avoid Disclosing AI Assistance in Scientific Writing** *Nature and Science of Sleep* [[paper](https://doi.org/10.2147/nss.s568375)]
- [2025] **Role of Medical Editors in the Age of Generative Artificial Intelligence** *Healthcare Informatics Research* [[paper](https://doi.org/10.4258/hir.2025.31.4.317)]
- [2025] **Artificial Intelligence Tools in Medical Writing – Boon or Bane?** *Neurology India* [[paper](https://doi.org/10.4103/neurol-india.neurol-india-d-25-00617)]
- [2025] **Research on Collaborative Reasoning of Large Language Models and Knowledge Graphs for Professional Writing Assistance** [[paper](https://doi.org/10.1109/cipae66821.2025.00046)]
- [2025] **What Shapes User Trust in ChatGPT? A Mixed-Methods Study of User Attributes, Trust Dimensions, Task Context, and Societal Perceptions among University Students** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.05046)]
- [2025] **Comparative Analysis of Artificial Intelligence-Generated and Human-Written Personal Statements in Emergency Medicine Applications** *Cureus* [[paper](https://doi.org/10.7759/cureus.88818)]
- [2025] **A Multiagent Scorer for Improved AES of International Students’ Essays** *International Journal of High Speed Electronics and Systems* [[paper](https://doi.org/10.1142/s0129156425407594)]
- [2025] **Towards the LLM-Based Generation of Formal Specifications from Natural-Language Contracts: Early Experiments with Symboleo** [[paper](https://doi.org/10.1109/raise66696.2025.00006)]
- [2025] **The Challenges of Artificial Intelligence in the English Language Teaching, Learning, and Academic Publications** [[paper](https://doi.org/10.31235/osf.io/ejwtz_v1)]
- [2025] **Feedback and Automated Writing Evaluation (AWE)** [[paper](https://doi.org/10.29140/9781763711600-16)]
- [2025] **Language translation application based on machine learning** [[paper](https://doi.org/10.70593/978-81-984306-7-0_2)]
- [2025] **Editorial: Some early insights into the use of AI tools within urban design and planning research – risks and opportunities** *Proceedings of the Institution of Civil Engineers - Urban Design and Planning* [[paper](https://doi.org/10.1680/jurdp.2025.178.1.1)]

##### 2024

- [2024] **Generative Artificial Intelligence, AI for Scientific Writing: A Literature Review** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202406.0011.v1)]
- [2024] **Open generative AI changes a lot, but not everything** *Modern Language Journal* [[paper](https://doi.org/10.1111/modl.12927)]
- [2024] **Artificial intelligence and the Journal of Research in Science Teaching** *Journal of Research in Science Teaching* [[paper](https://doi.org/10.1002/tea.21933)]
- [2024] **Fair Use of Augmented Intelligence and Artificial Intelligence in the Preparation and Review of Submissions to the Society of Critical Care Medicine Journals: Critical Care Medicine, Pediatric Critical Care Medicine, and Critical Care Explorations** *Pediatric Critical Care Medicine* [[paper](https://doi.org/10.1097/pcc.0000000000003430)]
- [2024] **Artificial intelligence/machine learning and journalology: Challenges and opportunities** *Acta Obstetricia Et Gynecologica Scandinavica* [[paper](https://doi.org/10.1111/aogs.14772)]

[⬆ Back to top](#paper-list)

#### Interactive Writing

##### 2024

- [2024] **Decoding AI and Human Authorship: Nuances Revealed through NLP and Statistical Analysis** *International Journal on Cybernetics & Informatics* [[paper](https://arxiv.org/abs/2408.00769)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **A Multi-Framework Comparison of Outline Stages in Long-Form Generation with LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.26177)]
- [2026] **PaperOrchestrator: An LLM-Orchestrated multi-agent pipeline for automated end-to-end scientific paper writing** *Journal of King Saud University - Computer and Information Sciences* [[paper](https://doi.org/10.1007/s44443-026-00708-4)]
- [2026] **A Survey on Large Language Models in Software Security: Opportunities and Threats** *Computers* [[paper](https://doi.org/10.3390/computers15040226)]
- [2026] **Narrative-Integrated Thematic Analysis (NITA): How can LLMs support theme generation without coding?** *Qualitative Research in Psychology* [[paper](https://doi.org/10.1080/14780887.2026.2638348)]
- [2026] **Comment on “ SegORG : Report Generation of Oral Potentially Malignant Disorders Image Based on Lesion Segmentation‐Enhanced LLM ”** *Oral Diseases* [[paper](https://doi.org/10.1111/odi.70262)]
- [2026] **Research on the Role of Large Language Models in Enhancing English Learners' Writing Skills: A Literature Review** *Journal of Education Teaching and Social Studies* [[paper](https://doi.org/10.22158/jetss.v8n1p1)]

##### 2025

- [2025] **Using generative artificial intelligence in clinical practice: a narrative review and proposed agenda for implementation** *The Medical Journal of Australia* [[paper](https://doi.org/10.5694/mja2.70057)]
- [2025] **Use of LLM assistants as support in the Project’s Formulation process: A Systematic Mapping** *Inge CUC* [[paper](https://doi.org/10.17981/ingecuc21.2.2025.05)]
- [2025] **The Imparts and Pedagogical Challenges of AIGenerated Codes on Computer Programming Education at Introductory Level: Curriculum Design Recommendations** *Caliphate Journal of Science and Technology* [[paper](https://doi.org/10.4314/cajost.v7i2.4)]
- [2025] **The promise and potential pitfalls of artificial intelligence in risk prediction models** *European Journal of Cardiovascular Nursing* [[paper](https://doi.org/10.1093/eurjcn/zvaf117)]
- [2025] **The benefits and dangers of anthropomorphic conversational agents** *Proceedings of the National Academy of Sciences* [[paper](https://doi.org/10.1073/pnas.2415898122)]
- [2025] **Reconceptualizing Gatekeeping in the Age of Artificial Intelligence: A Theoretical Exploration of Artificial Intelligence-Driven News Curation and Automated Journalism** *Journalism and Media* [[paper](https://doi.org/10.3390/journalmedia6020068)]
- [2025] **Foam-Agent: A Large Language Model-Based Multi-Agent Framework for Automating Computational Fluid Dynamics Workflows** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.04997)]
- [2025] **InteractiveSurvey: An LLM-based Personalized and Interactive Survey Paper Generation System** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08762)]
- [2025] **DORA AI Scientist: Multi-agent Virtual Research Team for Scientific Exploration Discovery and Automated Report Generation** *bioRxiv (Cold Spring Harbor Laboratory)* [[paper](https://doi.org/10.1101/2025.03.06.641840)]
- [2025] **Research paper AI assistant using retrieval augmented generation and multimodal LLM** *UiTM Institutional Repositories (Universiti Teknologi MARA)* [[paper](https://ir.uitm.edu.my/id/eprint/119095/1/119095.pdf)]
- [2025] **LLM-Assisted, Iterative Curriculum Writing: A Human-Centered AI Approach in Finnish Higher Education** [[paper](https://doi.org/10.18653/v1/2025.bea-1.76)]
- [2025] **Humans and AI writing lectures together** *AHFE international* [[paper](https://doi.org/10.54941/ahfe1005809)]

##### 2024

- [2024] **AI Literacy and the Politics of Academic Labor** *Critical AI* [[paper](https://doi.org/10.1215/2834703x-11556047)]
- [2024] **Generating Code World Models with Large Language Models Guided by Monte Carlo Tree Search** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.15383)]
- [2024] **Navigating the Path of Writing: Outline-guided Text Generation with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.13919)]
- [2024] **Knowledge-Aware Code Generation with Large Language Models** [[paper](https://doi.org/10.1145/3643916.3644418)]

##### 2023

- [2023] **Preventing harm from non-conscious bias in medical generative AI** *The Lancet Digital Health* [[paper](https://doi.org/10.1016/s2589-7500(23)00246-7)]
- [2023] **VISAR: A Human-AI Argumentative Writing Assistant with Visual Programming and Rapid Draft Prototyping** [[paper](https://doi.org/10.1145/3586183.3606800)]
- [2023] **ChatGPT: Where Is a Silver Lining? Exploring the realm of GPT and large language models** *Journal of language and Education* [[paper](https://doi.org/10.17323/jle.2023.18119)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **Stronger Alignment between Brain Activity and LLM Embeddings during Code Writing compared to Prose Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.24900)]
- [2026] **LLM-derived metrics in second language writing assessment: an explainable AI approach** *Computers & Education* [[paper](https://doi.org/10.1016/j.compedu.2026.105721)]
- [2026] **ScholarScribe: A Privacy-First Local LLM Writing Companion for Researchers** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21033187)]
- [2026] **Temporal Flattening in LLM-Generated Text: Comparing Human and LLM Writing Trajectories** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.12097)]
- [2026] **Enhanced Generative Question Answering for Language Learning Using Finetuned LLMs and Reinforcement Learning** [[paper](https://doi.org/10.1109/qpain69676.2026.11545756)]
- [2026] **Applications of Machine Learning, Natural Language Processing, and Generative Artificial Intelligence in Dermatology Education and Research: A Scoping Review** *International Journal of Dermatology* [[paper](https://doi.org/10.1111/ijd.70418)]
- [2026] **Performance Evaluation of Open-Source Large Language Models for Assisting Pathology Report Writing in Japanese** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.11597)]
- [2026] **Accepted with Minor Revisions: Value of AI-Assisted Scientific Writing** [[paper](https://arxiv.org/abs/2511.12529)]
- [2026] **Do Large Language Models Encode Second-Language Writing Proficiency? A CALF-Based Perspective** *Digital studies in language and literature* [[paper](https://doi.org/10.1515/dsll-2025-0019)]
- [2026] **Retrieval augmented generation with LLMs for enterprise proposal automation** *ITM Web of Conferences* [[paper](https://doi.org/10.1051/itmconf/20268502007)]
- [2026] **Reasoning in a Combinatorial and Constrained World: Benchmarking LLMs on Natural-Language Combinatorial Optimization** [[paper](https://doi.org/10.18653/v1/2026.findings-acl.1529)]

##### 2025

- [2025] **Multi-Stage Generation of Rust Unit Tests with LLMs** [[paper](https://doi.org/10.1109/apsec66846.2025.00049)]
- [2025] **Leveraging Large Language Models to Generate Multiple-Choice Questions for Ophthalmology Education** *JAMA Ophthalmology* [[paper](https://doi.org/10.1001/jamaophthalmol.2025.3622)]
- [2025] **Exploring Influence Factors on LLM Suitability for No‐Code Development of End User Applications** *Software Practice and Experience* [[paper](https://arxiv.org/abs/2505.04710)]
- [2025] **ReqInOne: A Large Language Model-Based Agent for Software Requirements Specification Generation** [[paper](https://doi.org/10.1109/re63999.2025.00054)]
- [2025] **Pharmacometrics in the Age of Large Language Models: A Vision of the Future** *Pharmaceutics* [[paper](https://doi.org/10.3390/pharmaceutics17101274)]
- [2025] **Navigating the Labyrinth: Path-Sensitive Unit Test Generation with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.23812)]
- [2025] **Fabricated or accurate? Ethical concerns and citation hallucination in aI-generated scientific writing on musculoskeletal topics** *Anatolian Current Medical Journal* [[paper](https://doi.org/10.38053/acmj.1746227)]
- [2025] **Long Text Generation Enhanced by Agents for Large Language Models** [[paper](https://doi.org/10.1109/icicc66840.2025.11199412)]
- [2025] **Leveraging Multi-Model Linguistic Fusion for Enhanced AI Text Generation Evasion** [[paper](https://doi.org/10.1109/gaclm67198.2025.11231821)]
- [2025] **LLM-based Generation of Formal Specification for Run-time Security Monitoring of ICS** [[paper](https://doi.org/10.1109/csr64739.2025.11130130)]
- [2025] **AI-Assisted Tools for Scientific Review Writing: Opportunities and Cautions** *ACS Applied Materials & Interfaces* [[paper](https://doi.org/10.1021/acsami.5c08837)]
- [2025] **LLM synthetic generation to enhance online content moderation generalization in hate speech scenarios** *Computing* [[paper](https://doi.org/10.1007/s00607-025-01518-8)]
- [2025] **Doc2OracLL: Investigating the Impact of Documentation on LLM-Based Test Oracle Generation** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3729354)]
- [2025] **SpecLLM: Exploring Generation and Review of VLSI Design Specification with Large Language Model** [[paper](https://doi.org/10.1109/iseda65950.2025.11100410)]
- [2025] **GreenIQ: A Deep Search Platform for Comprehensive Carbon Market Analysis and Automated Report Generation** [[paper](https://doi.org/10.1109/icmlt65785.2025.11193211)]
- [2025] **Designing an LLM-Based IELTS Question Generator, Assessment, and Personalized Training System: Architecture and Research Agenda** [[paper](https://doi.org/10.1109/ecti-con64996.2025.11101665)]
- [2025] **Amplifying Your Social Media Presence: Personalized Influential Content Generation with LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.01698)]
- [2025] **Cognitive Computing with Large Language Models for Student Assessment Feedback** *Big Data and Cognitive Computing* [[paper](https://doi.org/10.3390/bdcc9050112)]
- [2025] **Comparative Analysis of Web Scraping Methodologies Using Generative AI** [[paper](https://doi.org/10.1109/rait65068.2025.11088928)]
- [2025] **A Comprehensive Review of DeepSeek: Performance, Architecture and Capabilities** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202503.1887.v1)]
- [2025] **Knowledge Synthesis of Photosynthesis Research Using a Large Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.01059)]
- [2025] **Writing Like the Best: Exemplar-Based Expository Text Generation** [[paper](https://doi.org/10.18653/v1/2025.acl-long.1250)]
- [2025] **Beyond Checkmate: Exploring the Creative Choke Points for AI Generated Texts** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.600)]

##### 2024

- [2024] **Low-Resource Chinese Named Entity Recognition via CNN-based Multitask Learning** *Journal of Data Science and Intelligent Systems* [[paper](https://doi.org/10.47852/bonviewjdsis42024432)]
- [2024] **DiCE: Distributed Code Generation and Execution** [[paper](https://doi.org/10.1109/picom64201.2024.00008)]
- [2024] **On the Evaluation of Large Language Models in Unit Test Generation** [[paper](https://doi.org/10.1145/3691620.3695529)]
- [2024] **Assessing Retrieval-Augmented Large Language Model Performance in Emergency Department ICD-10-CM Coding Compared to Human Coders** *medRxiv* [[paper](https://doi.org/10.1101/2024.10.15.24315526)]
- [2024] **Constructing a Large Language Model to Generate Impressions from Findings in Radiology Reports** *Radiology* [[paper](https://doi.org/10.1148/radiol.240885)]
- [2024] **The Power of Personalized Datasets: Advancing Chinese Composition Writing for Elementary School through Targeted Model Fine-Tuning** [[paper](https://doi.org/10.1109/ialp63756.2024.10661174)]
- [2024] **Generative AI in drug discovery and development: the next revolution of drug discovery and development would be directed by generative AI** *Annals of Medicine and Surgery* [[paper](https://doi.org/10.1097/ms9.0000000000002438)]
- [2024] **Extending the Frontier of ChatGPT: Code Generation and Debugging** [[paper](https://doi.org/10.1109/icecet61485.2024.10698405)]
- [2024] **Leveraging Large Language Models for the Automated Documentation of Hardware Designs** [[paper](https://doi.org/10.1109/meco62516.2024.10577923)]
- [2024] **GPT-4 in a Cancer Center — Institute-Wide Deployment Challenges and Lessons Learned** *NEJM AI* [[paper](https://doi.org/10.1056/aics2300191)]
- [2024] **AN EXPLORATORY ASSESSMENT OF THE USABILITY AND POTENTIAL OF GENERATIVE PRETRAINED TRANSFORMERS (GPTS) AS FEEDBACK ASSISTANTS FOR LONG-FORMAT ACADEMIC WRITING TASKS** *INTED proceedings* [[paper](https://doi.org/10.21125/inted.2024.0394)]
- [2024] **Leveraging AI Tools in University Writing Instruction: Enhancing Student Success While Upholding Academic Integrity** *The Journal of Interactive Learning Research* [[paper](https://doi.org/10.70725/355152wkijve)]
- [2024] **Generative Retrieval-Augmented Ontologic Graph and Multiagent Strategies for Interpretive Large Language Model-Based Materials Design** *ACS Engineering Au* [[paper](https://doi.org/10.1021/acsengineeringau.3c00058)]
- [2024] **Finding Blind Spots in Evaluator LLMs with Interpretable Checklists** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.911)]
- [2024] **Enhancing Generative AI Capabilities Through Retrieval-Augmented Generation Systems and LLMs** *Library Progress (International)* [[paper](https://doi.org/10.36893/libpro.2024.v44n3.17776)]
- [2024] **CoGenesis: A Framework Collaborating Large and Small Language Models for Secure Context-Aware Instruction Following** [[paper](https://doi.org/10.18653/v1/2024.acl-long.235)]

##### 2023

- [2023] **The application of large language models in pediatrics and medical research—Revolution or risk?** *Pediatric Discovery* [[paper](https://doi.org/10.1002/pdi3.39)]
- [2023] **Does Human Collaboration Enhance the Accuracy of Identifying LLM-Generated Deepfake Texts?** *Proceedings of the AAAI Conference on Human Computation and Crowdsourcing* [[paper](https://doi.org/10.1609/hcomp.v11i1.27557)]
- [2023] **A Wolf in Sheep’s Clothing? Critical Discourse Analysis of Five Online Automated Paraphrasing Sites** *Journal of University Teaching and Learning Practice* [[paper](https://doi.org/10.53761/1.20.7.08)]
- [2023] **A Generative AI-driven Application: Use of Large Language Models for Traffic Scenario Generation** [[paper](https://dx.doi.org/10.1109/eleco60389.2023.10415934)]
- [2023] **Generative retrieval-augmented ontologic graph and multi-agent strategies for interpretive large language model-based materials design** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.19998)]
- [2023] **GPT-4 in a Cancer Center: Institute-Wide Deployment Challenges and Lessons Learned** [[paper](https://doi.org/10.31219/osf.io/bqv4f)]
- [2023] **TOPFORMER: Topology-Aware Authorship Attribution of Deepfake Texts with Diverse Writing Styles** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.12934)]
- [2023] **AI literacy in geographic education and research: Capabilities, caveats, and criticality** *Geographical Journal* [[paper](https://doi.org/10.1111/geoj.12548)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2026

- [2026] **Vibe Coding Omics Data Analysis Applications** *Journal of Proteome Research* [[paper](https://doi.org/10.1021/acs.jproteome.5c00984)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **Training-Free Token-Level Steering for LLM Personalized Co-Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.06069)]
- [2026] **Proficiency Without Interaction: Comparing Stance and Engagement in LLM‐Generated and Human CEFR Writing** *International Journal of Applied Linguistics* [[paper](https://doi.org/10.1111/ijal.70353)]
- [2026] **Construction and Application of a Personalized Writing Feedback System for Higher Vocational Colleges Assisted by Large Language Model (LLM)** *Advanced Electromagnetics* [[paper](https://doi.org/10.7716/aem.v15i3.3893)]
- [2026] **KForge: LLM-Driven Cross-Platform Kernel Generation for AI Accelerators** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.02963)]
- [2026] **The Blind Spots in Automated Feedback Generation for Academic Writing** [[paper](https://doi.org/10.1145/3785022.3785120)]
- [2026] **Improving Software Testing with RAG-Based LLMs and Supporting Indian Regional Languages** [[paper](https://doi.org/10.1109/icitiit68860.2026.11499660)]
- [2026] **From Verification Burden to Trusted Collaboration: Design Goals for LLM-Assisted Literature Reviews** [[paper](https://doi.org/10.1145/3742414.3794723)]

##### 2025

- [2025] **AI ‐Driven Intelligent Feedback System for Enhancing Self‐Assessment Accuracy in Higher Education Writing** *Expert Systems* [[paper](https://doi.org/10.1111/exsy.70184)]
- [2025] **CPU-Only Self Enhancing Authoring Copilot Design-Based Markov Decision Processes Orchestration and Qwen 3 Local Large Language Model** *Technologies* [[paper](https://doi.org/10.3390/technologies13110520)]
- [2025] **Artificial Intelligence in Higher Education: A State-of-the-Art Overview of Pedagogical Integrity, Artificial Intelligence Literacy, and Policy Integration** *Encyclopedia* [[paper](https://doi.org/10.3390/encyclopedia5040180)]
- [2025] **A study on how LLMs (e.g. GPT-4, chatbots) are being integrated to support tutoring, essay feedback and content generation** *Journal of Computing and Electronic Information Management* [[paper](https://doi.org/10.54097/6r6yhn67)]
- [2025] **SGTest: A Semantics-Guided Framework for LLM-Driven Unit Test Generation** *Proceedings/Proceedings of the ... International Conference on Software Engineering and Knowledge Engineering* [[paper](https://doi.org/10.18293/seke2025-043)]
- [2025] **LL3M: Large Language 3D Modelers** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.08228)]
- [2025] **IncrFuzz: LLM-Driven Incremental Fuzz Driver Generation for Library APIs** [[paper](https://doi.org/10.1109/dsc67331.2025.00093)]
- [2025] **Deep Researcher with Test-Time Diffusion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.16075)]
- [2025] **Explainable AI for education: Enhancing essay scoring via rubric-aligned chain-of-thought prompting** *International Journal of Modern Physics C* [[paper](https://doi.org/10.1142/s0129183125420136)]
- [2025] **Test Intention Guided LLM-Based Unit Test Generation** [[paper](https://doi.org/10.1109/icse55347.2025.00243)]
- [2025] **JournalAIde: Empowering Older Adults in Digital Journal Writing** [[paper](https://doi.org/10.1145/3706598.3713339)]
- [2025] **Exploring Mobile Touch Interaction with Large Language Models** [[paper](https://arxiv.org/abs/2502.07629)]
- [2025] **Automatic Unit Test Generation for Programming Assignments Using Large Language Models** [[paper](https://doi.org/10.1109/cseet66350.2025.00031)]
- [2025] **Towards LLM-based fully automated reporting of nuclear medicine examinations at the example of renal scans** *Nuklearmedizin - NuclearMedicine* [[paper](https://doi.org/10.1055/s-0045-1804429)]
- [2025] **Refinement and Revision in Academic Writing: Integrating Multi-source Knowledge and LLMs with Delta Feedback** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.127226)]
- [2025] **KernelBench: Can LLMs Write Efficient GPU Kernels?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.10517)]
- [2025] **GLLM: Self-Corrective G-Code Generation using Large Language Models with User Feedback** *TUbilio (Technical University of Darmstadt)* [[paper](https://arxiv.org/abs/2501.17584)]
- [2025] **Annotating Errors in English Learners’ Written Language Production: Advancing Automated Written Feedback Systems** *Lecture notes in computer science* [[paper](https://arxiv.org/abs/2508.06810)]

##### 2024

- [2024] **Embracing generative AI: A necessary evolution in professional writing** *European Journal of Radiology Artificial Intelligence* [[paper](https://doi.org/10.1016/j.ejrai.2024.100001)]
- [2024] **Applications and Research Gaps of LLM-based English-as-a-foreign-language Education** *Journal of Education Humanities and Social Sciences* [[paper](https://doi.org/10.54097/jkhv4m38)]
- [2024] **Negation Blindness in Large Language Models: Unveiling the NO Syndrome in Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.00105)]
- [2024] **Navigating the Ethical Landscape of ChatGPT Integration in Scientific Research: Review of Challenges and Recommendations** *Journal of Computational and Cognitive Engineering* [[paper](https://doi.org/10.47852/bonviewjcce42023238)]
- [2024] **Artificial intelligence in academic writing: Insights from journal publishers’ guidelines** *Perspectives in Clinical Research* [[paper](https://doi.org/10.4103/picr.picr_67_24)]
- [2024] **How Beginning Programmers and Code LLMs (Mis)read Each Other** [[paper](https://arxiv.org/abs/2401.15232)]
- [2024] **EvaluMate: Using AI to support students’ feedback provision in peer assessment for writing** *Assessing Writing* [[paper](https://doi.org/10.1016/j.asw.2024.100864)]
- [2024] **TestSpark: IntelliJ IDEA's Ultimate Test Generation Companion** [[paper](https://doi.org/10.1145/3639478.3640024)]
- [2024] **Next-Step Hint Generation for Introductory Programming Using Large Language Models** [[paper](https://doi.org/10.1145/3636243.3636259)]
- [2024] **LLMCrit: Teaching Large Language Models to Use Criteria** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.472)]
- [2024] **Automated Focused Feedback Generation for Scientific Writing Assistance** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.580)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **Form Without Function? Register Sensitivity in CEFR‐Conditioned LLM and Second‐Language Learner Writing** *International Journal of Applied Linguistics* [[paper](https://doi.org/10.1111/ijal.70284)]

##### 2025

- [2025] **Revolutionizing medical education The role of generative artificial intelligence in medical education** *Progress in Medical Education* [[paper](https://doi.org/10.61189/141463mjzwgj)]
- [2025] **Interactive Text Generation Using GPT-2 with Gradio: An Approach to Accessible NLP Applications** [[paper](https://doi.org/10.1109/icact67549.2025.11351387)]
- [2025] **Exploring the Role of Large Language Models (LLMs) as an Academic Resource for Students: A Scoping Review** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18728618)]
- [2025] **A Review on Conversational AI as a Tool in Academic Writing** *Eskiyeni (Online)/Eskiyeni* [[paper](https://doi.org/10.37697/eskiyeni.1565854)]

##### 2024

- [2024] **Influence of critical thinking on LLM usage among Universitat d’Andorra students** *Interdisciplinary journal of didactics* [[paper](https://doi.org/10.14198/ijd.28095)]
- [2024] **Review-LLM: Harnessing Large Language Models for Personalized Review Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.07487)]
- [2024] **Automated Inspection Report Generation Using Multimodal Large Language Models and Set-of-Mark Prompting** *Proceedings of the ... ISARC* [[paper](https://doi.org/10.22260/isarc2024/0130)]

##### 2023

- [2023] **Adapting Large Language Models for Education: Foundational Capabilities, Potentials, and Challenges** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.08664)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **Automated SVA Generation with LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.11044)]
- [2026] **How LLMs Cite and Why It Matters: A Cross-Model Audit of Reference Fabrication in AI-Assisted Academic Writing and Methods to Detect Phantom Citations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.03299)]
- [2026] **Comparing the performance of four mainstream large language models on medical literature review generation: a human expert evaluation in SMILE surgery** *Graefe s Archive for Clinical and Experimental Ophthalmology* [[paper](https://doi.org/10.1007/s00417-025-07092-1)]

##### 2025

- [2025] **ChatGPT: how to use it and the pitfalls/cautions in academia** *Annals of Pediatric Endocrinology & Metabolism* [[paper](https://doi.org/10.6065/apem.2550028.014)]
- [2025] **Advancing Large Language Model Reasoning Techniques: Methods Enabling LLMs to 'Think' Beyond Text Generation for Reliable and Explainable AI** [[paper](https://doi.org/10.36227/techrxiv.176131150.00355935/v1)]
- [2025] **LLMs and Generative AI for the Detection and Generation of Scientific Content** [[paper](https://doi.org/10.1109/iccsc66714.2025.11134858)]
- [2025] **Opportunities and challenges in lung cancer care in the era of large language models and vision language models** *Translational Lung Cancer Research* [[paper](https://doi.org/10.21037/tlcr-24-801)]
- [2025] **How Large Language Models are Transforming Teachers' Assessment of Student Competency: A Case Study on LLM-Based Report Writing** [[paper](https://doi.org/10.1109/iceic64972.2025.10879736)]
- [2025] **AudioSetCaps: An Enriched Audio-Caption Dataset Using Automated Generation Pipeline With Large Audio and Language Models** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2025.3583354)]

##### 2024

- [2024] **Optimizing biomedical information retrieval with a keyword frequency-driven prompt enhancement strategy** *BMC Bioinformatics* [[paper](https://doi.org/10.1186/s12859-024-05902-7)]
- [2024] **Can ChatGPT assist authors with abstract writing in medical journals? Evaluating the quality of scientific abstracts generated by ChatGPT and original abstracts** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0297701)]
- [2024] **Gaps or Hallucinations? Scrutinizing Machine-Generated Legal Analysis for Fine-grained Text Evaluations** [[paper](https://dx.doi.org/10.18653/v1/2024.nllp-1.24)]

[⬆ Back to top](#paper-list)

#### NLP Metrics

##### 2024

- [2024] **GPT-Driven Radiology Report Generation with Fine-Tuned Llama 3** *Bioengineering* [[paper](https://doi.org/10.3390/bioengineering11101043)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2025

- [2025] **SurveyGen: Quality-Aware Scientific Survey Generation with Large Language Models** *Underline Science Inc.* [[paper](https://doi.org/10.48448/f0wv-br78)]
- [2025] **CtrlNews: LLM-based Multi-Agent Controllable News Writing via Knowledge Gravitational Field** *Underline Science Inc.* [[paper](https://doi.org/10.48448/npcz-q618)]
- [2025] **Use of Large Language Models in Turkish Patent Writing** [[paper](https://doi.org/10.1109/ubmk67458.2025.11207029)]
- [2025] **Identification of the Most Frequently Asked Questions in Financial Analyst Reports to Automate Equity Research Using Llama 3 and GPT-4** [[paper](https://doi.org/10.1109/sds66131.2025.00025)]

##### 2024

- [2024] **Patentformer: A Novel Method to Automate the Generation of Patent Applications** [[paper](https://doi.org/10.18653/v1/2024.emnlp-industry.101)]
- [2024] **Evaluating the Smooth Control of Attribute Intensity in Text Generation with LLMs** [[paper](https://dx.doi.org/10.18653/v1/2024.findings-acl.258)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Doc2CI: A Multi-Service Study of CI Configuration Generation Using Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.01451)]
- [2026] **Are They All Good? Evaluating the Quality of CoTs in LLM-Based Code Generation** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2026.3676295)]
- [2026] **GhostCite: A Large-Scale Analysis of Citation Validity in the Age of Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.06718)]
- [2026] **Can LLMs Cook Jamaican Couscous? A Study of Cultural Novelty in Recipe Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.10964)]
- [2026] **From Coarse to Fine: Benchmarking and Reward Modeling for Writing-Centric Generation Tasks** [[paper](https://doi.org/10.18653/v1/2026.findings-acl.134)]
- [2026] **AI‐Generated Essays: Characteristics and Implications on Automated Scoring and Academic Integrity** *Educational Measurement Issues and Practice* [[paper](https://doi.org/10.1111/emip.70013)]

##### 2025

- [2025] **Towards Small Language Models for Security Query Generation in SOC Workflows** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.06660)]
- [2025] **Detecting LLM-Generated Spam Reviews by Integrating Language Model Embeddings and Graph Neural Network** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.01801)]
- [2025] **RuleMaster+: LLM-Based Automated Rule Generation Framework for Intrusion Detection Systems** *Chinese Journal of Electronics* [[paper](https://doi.org/10.23919/cje.2024.00.342)]
- [2025] **Hybrid-NL2SVA: Integrating RAG and Finetuning for LLM-based NL2SVA** [[paper](https://doi.org/10.1109/mlcad65511.2025.11189208)]
- [2025] **AssertFix: Empowering Automated Assertion Fix via Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.23972)]
- [2025] **Activating Associative Disease-Aware Vision Token Memory for LLM-Based X-Ray Report Generation** *IEEE Transactions on Medical Imaging* [[paper](https://doi.org/10.1109/tmi.2025.3603416)]
- [2025] **THE COST OF EXPERTISE: PERFORMANCE TRADEOFFS IN LLMs FOR SYSTEMS ENGINEERING** *INCOSE International Symposium* [[paper](https://doi.org/10.1002/iis2.70078)]
- [2025] **Privacy-Preserving Synthetic Review Generation with Diverse Writing Styles Using LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.18055)]
- [2025] **MetaCrit: A Critical Thinking Framework for Self-Regulated LLM Reasoning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.15015)]
- [2025] **CurveMark: Detecting AI-Generated Text via Probabilistic Curvature and Dynamic Semantic Watermarking** *Entropy* [[paper](https://doi.org/10.3390/e27080784)]
- [2025] **Less Is More: On the Importance of Data Quality for Unit Test Generation** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3715778)]
- [2025] **EssayBench: Evaluating Large Language Models in Multi-Genre Chinese Essay Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.02596)]
- [2025] **MoDeST: A dataset for Multi Domain Scientific Title Generation** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.113557)]
- [2025] **CWEval: Outcome-driven Evaluation on Functionality and Security of LLM Code Generation** [[paper](https://doi.org/10.1109/llm4code66737.2025.00009)]
- [2025] **Automatic Metadata Extraction for Text-to-SQL** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.19988)]
- [2025] **Summary report auto-generation based on hierarchical corpus using large language model** *Displays* [[paper](https://doi.org/10.1016/j.displa.2025.103055)]
- [2025] **SCALM: Detecting Bad Practices in Smart Contracts Through LLMs** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i1.32026)]
- [2025] **RTLRepoCoder: Repository-Level RTL Code Completion through the Combination of Fine-Tuning and Retrieval Augmentation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08862)]
- [2025] **GraphCodeAgent: Dual Graph-Guided LLM Agent for Retrieval-Augmented Repo-Level Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.10046)]
- [2025] **Enriching automatic test case generation by extracting relevant test inputs from bug reports** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-025-10635-z)]
- [2025] **On Continually Tracing Origins of LLM-Generated Text and Its Application in Detecting Cheating in Student Coursework** *Big Data and Cognitive Computing* [[paper](https://doi.org/10.3390/bdcc9030050)]
- [2025] **LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.19103)]
- [2025] **CaseGen: A Benchmark for Multi-Stage Legal Case Documents Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.17943)]
- [2025] **Megafake: A Theory-Driven Dataset of Fake News Generated by Large Language Models** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5095309)]
- [2025] **Collaboration between intelligent agents and large language models: A novel approach for enhancing code generation capability** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2024.126357)]
- [2025] **Can LLMs Generate and Solve Linguistic Olympiad Puzzles?** [[paper](https://arxiv.org/abs/2509.21820)]
- [2025] **Beyond N-Grams: Enhancing String Kernels With Transformer-Guided Semantic Insights** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3576076)]
- [2025] **Almost AI, Almost Human: The Challenge of Detecting AI-Polished Writing** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.1303)]
- [2025] **Aligning, Autoencoding and Prompting Large Language Models for Novel Disease Reporting** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3534586)]
- [2025] **AI-Powered Unit Test Generation via Multi-LLM Chaining: A Case Study With GPT-4o, Gemini, and Claude-3.5** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3637221)]
- [2025] **A Multi-Modal Assessment Framework for Comparison of Specialized Deep Learning and General-Purpose Large Language Models** *IEEE Transactions on Big Data* [[paper](https://doi.org/10.1109/tbdata.2025.3536937)]

##### 2024

- [2024] **Human vs. Machine: A Comparative Study on the Detection of AI-Generated Content** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3708889)]
- [2024] **Exploring the Application of Large Language Models in English Reading and Writing Courses: Technical Challenges and Development Opportunities** [[paper](https://doi.org/10.1145/3735014.3735915)]
- [2024] **SCAR: Sparse Conditioned Autoencoders for Concept Detection and Steering in LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.07122)]
- [2024] **QUILL: Quotation Generation Enhancement of Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.03675)]
- [2024] **Machine Learning Approaches to Identify AI-Generated Text: a Comparative Analysis** [[paper](https://doi.org/10.1109/icec59683.2024.10837481)]
- [2024] **Leveraging LLM and RAG for Automated Answer Script Evaluation** [[paper](https://doi.org/10.1109/csitss64042.2024.10817016)]
- [2024] **Showing LLM-Generated Code Selectively Based on Confidence of LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.03234)]
- [2024] **Resource-Efficient Medical Report Generation using Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.15642)]
- [2024] **AAAR-1.0: Assessing AI's Potential to Assist Research** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.22394)]
- [2024] **ScriptSmith: A Unified LLM Framework for Enhancing IT Operations via Automated Bash Script Generation, Assessment, and Refinement** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.17166)]
- [2024] **Combining LLM Code Generation with Formal Specifications and Reactive Program Synthesis** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.19736)]
- [2024] **Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.10956)]
- [2024] **Generation and Assessment of Multiple-Choice Questions from Video Transcripts using Large Language Models** [[paper](https://doi.org/10.1145/3657604.3664714)]
- [2024] **Evaluating and Improving ChatGPT for Unit Test Generation** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3660783)]
- [2024] **Guiding LLM Temporal Logic Generation with Explicit Separation of Data and Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.07400)]
- [2024] **DALD: Improving Logits-based Detector without Logits from Black-box LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.05232)]
- [2024] **Exploring Large Language Models for Verilog Hardware Design Generation** [[paper](https://doi.org/10.1109/ipdpsw63119.2024.00034)]
- [2024] **The Future of Scientific Publishing: Automated Article Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.17586)]
- [2024] **Can ChatGPT Serve as a Multi-Criteria Decision Maker? A Novel Approach to Supplier Evaluation** [[paper](https://doi.org/10.1109/icassp48485.2024.10447204)]
- [2024] **Hidding the Ghostwriters: An Adversarial Evaluation of AI-Generated Student Essay Detection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.00412)]
- [2024] **ChemMiner: A Large Language Model Agent System for Chemical Literature Data Mining** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.12993)]
- [2024] **Automatic Commit Message Generation: A Critical Review and Directions for Future Work** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3364675)]
- [2024] **TheoremLlama: Transforming General-Purpose LLMs into Lean4 Experts** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.667)]
- [2024] **Selene: Pioneering Automated Proof in Software Verification** [[paper](https://dx.doi.org/10.18653/v1/2024.acl-long.98)]
- [2024] **Leveraging Context-Aware Prompting for Commit Message Generation** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-main.749)]
- [2024] **Knowledge-Infused Prompting: Assessing and Advancing Clinical Text Data Generation with Large Language Models** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.916)]
- [2024] **(Security) Assertions by Large Language Models** *IEEE Transactions on Information Forensics and Security* [[paper](https://doi.org/10.1109/tifs.2024.3372809)]

##### 2023

- [2023] **Token Prediction as Implicit Classification to Identify LLM-Generated Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.08723)]
- [2023] **MART: Improving LLM Safety with Multi-round Automatic Red-Teaming** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.07689)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2026

- [2026] **Can ChatGPT effectively generate abstracts in orthopedic surgery? A comparative analysis between human-written and ChatGPT-generated scientific abstracts** *Postgraduate Medical Journal* [[paper](https://doi.org/10.1093/postmj/qgag018)]

##### 2025

- [2025] **Estimating the prevalence of LLM-assisted text in scholarly writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.01560)]
- [2025] **ReefPaperAgent: Empowering Teaching Case Generation with Large Language Models** [[paper](https://doi.org/10.1145/3775073.3775093)]
- [2025] **TDCSA: LLM-Guided Top-Down Approach for Robust Citation Sentiment Analysis** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.335)]

##### 2024

- [2024] **Generative Pre-Trained Transformer (GPT) in Research: A Systematic Review on Data Augmentation** *Information* [[paper](https://doi.org/10.3390/info15020099)]
- [2024] **Exploring the Frontiers of LLMs in Psychological Applications: A Comprehensive Review** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.01519)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **LLM-Driven Generation of Summaries for Symbolic Execution** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.32961548.v1)]
- [2026] **University students’ perceptions and adoptions of AI: a cross-national study** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-026-01042-4)]
- [2026] **An Expert-In-The-Loop Design Utilising Knowledge Graphs to Prompt LLMs in Professional Writing** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-30849-8_31)]

##### 2025

- [2025] **Generative AI approach for inventive process visualisation – enhancing human-AI hybrid understanding and comparing of patents** *Journal of Engineering Design* [[paper](https://doi.org/10.1080/09544828.2025.2518657)]
- [2025] **Large Language Model Architectures in Health Care: Scoping Review of Research Perspectives** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/70315)]
- [2025] **AI-driven report-generation tools in mental healthcare: A review of commercial tools** *General Hospital Psychiatry* [[paper](https://doi.org/10.1016/j.genhosppsych.2025.02.018)]

##### 2024

- [2024] **Advancement in medical report generation: current practices, challenges, and future directions** *Medical & Biological Engineering & Computing* [[paper](https://doi.org/10.1007/s11517-024-03265-y)]
- [2024] **Inductive reasoning with large language models: a simulated randomized controlled trial for epilepsy** *medRxiv* [[paper](https://doi.org/10.1101/2024.03.18.24304493)]
- [2024] **Large Language Models and Artificial Intelligence for Police Report Writing** *CrimRxiv* [[paper](https://doi.org/10.21428/cb6ab371.779603ee)]

##### 2023

- [2023] **Effectively Fine-tune to Improve Large Multimodal Models for Radiology Report Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.01504)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2026

- [2026] **LRASGen: LLM-based RESTful API Specification Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://arxiv.org/abs/2504.16833)]
- [2026] **Code Roulette: How Prompt Variability Affects LLM Code Generation** [[paper](https://arxiv.org/abs/2506.10204)]

##### 2025

- [2025] **Using LLMs for Writing ATL Model Transformation Code** [[paper](https://doi.org/10.1109/acit68900.2025.11510614)]
- [2025] **LLM-ASSISTED CWE IDENTIFICATION, SEVERITY ASSESSMENT, AND VULNERABILITY DESCRIPTION GENERATION** *Lincoln (University of Nebraska)* [[paper](https://digitalcommons.unl.edu/computerscidiss/253)]
- [2025] **Learning to Generate Unit Test via Adversarial Reinforcement Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.21107)]
- [2025] **CITYWALK : Enhancing LLM-Based C++ Unit Test Generation via Project-Dependency Awareness and Language-Specific Knowledge** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3763791)]
- [2025] **Private-library-oriented code generation with large language models** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.113934)]
- [2025] **Large Language Models for C Test Case Generation: A Comparative Analysis** *Electronics* [[paper](https://doi.org/10.3390/electronics14112284)]
- [2025] **LLM-based code generation and system migration in language-driven engineering** *International Journal on Software Tools for Technology Transfer* [[paper](https://doi.org/10.1007/s10009-025-00798-x)]
- [2025] **Large Language Model-Based Automatic Generation Method for Test Cases Across Multiple Programming Language Types** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-96-7178-6_16)]
- [2025] **Effective LLM-Driven Code Generation with Pythoness** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.02138)]
- [2025] **CITYWALK: Enhancing LLM-Based C++ Unit Test Generation via Project-Dependency Awareness and Language-Specific Knowledge** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.16155)]

##### 2024

- [2024] **A Conversational Large-Language-Model AI Agent for Synthesis of Metal-Organic Frameworks for Efficient Hydrogenation of Dicyclopentadiene** *ChemRxiv* [[paper](https://doi.org/10.26434/chemrxiv-2024-7kds2)]
- [2024] **Multi-stage guided code generation for Large Language Models** *Engineering Applications of Artificial Intelligence* [[paper](https://doi.org/10.1016/j.engappai.2024.109491)]
- [2024] **Automated Generation and Compilation of Fuzz Driver Based on Large Language Models** [[paper](https://doi.org/10.1145/3689236.3689272)]
- [2024] **Correctness Comparison of ChatGPT ‐4, Gemini, Claude‐3, and Copilot for Spatial Tasks** *Transactions in GIS* [[paper](https://doi.org/10.1111/tgis.13233)]
- [2024] **Using GPT for Market Research** [[paper](https://doi.org/10.1145/3670865.3673479)]
- [2024] **Experiencing InstructPipe: Building Multi-modal AI Pipelines via Prompting LLMs and Visual Programming** [[paper](https://doi.org/10.1145/3613905.3648656)]
- [2024] **A Study of Vulnerability Repair in JavaScript Programs with Large Language Models** [[paper](https://arxiv.org/abs/2403.13193)]
- [2024] **Using GitHub Copilot for Test Generation in Python: An Empirical Study** [[paper](https://doi.org/10.1145/3644032.3644443)]
- [2024] **LogicAsker: Evaluating and Improving the Logical Reasoning Ability of Large Language Models** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.128)]
- [2024] **Interactions with Prompt Problems: A New Way to Teach Programming with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.10759)]
- [2024] **GPT-Driven Source-to-Source Transformation for Generating Compilable Parallel CUDA Code for Nussinov’s Algorithm** *Electronics* [[paper](https://doi.org/10.3390/electronics13030488)]

##### 2023

- [2023] **A Review on Code Generation with LLMs: Application and Evaluation** [[paper](https://doi.org/10.1109/medai59581.2023.00044)]
- [2023] **L2MAC: Large Language Model Automatic Computer for Extensive Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.02003)]
- [2023] **Exploring the Capability of ChatGPT in Test Generation** [[paper](https://doi.org/10.1109/qrs-c60940.2023.00013)]
- [2023] **ChatGPT in IoT Systems: Arduino Case Studies** [[paper](https://doi.org/10.1109/miel58498.2023.10315791)]

[⬆ Back to top](#paper-list)

### Text Generation

#### LLM Evaluation

##### 2026

- [2026] **Neural networks based predictive model to enhance thermal transfer rate in battery cooling performance using ethylene glycol-based hybrid nanofluid** *International Journal of Mechanics and Materials in Design* [[paper](https://doi.org/10.1007/s10999-026-09928-y)]
- [2026] **GNN-EGG: Graph neural network explanations via graph generation** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2026.133373)]
- [2026] **Neural network technologies in higher education: practices of use by students across different disciplines** *Uchenye zapiski universiteta imeni P F Lesgafta* [[paper](https://doi.org/10.5930/1994-4683-2026-2-212-219)]
- [2026] **Enhancing SPARQL query generation using multi-label text-to-text models** *Data & Knowledge Engineering* [[paper](https://doi.org/10.1016/j.datak.2026.102584)]
- [2026] **SNN-Comprypto: High-Performance Compression and Encryption Using Spiking Neural Network Chaotic Reservoir Dynamics** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18265446)]
- [2026] **Isotropic3D: Image-to-3D generation based on a single CLIP embedding** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2026.115367)]
- [2026] **Intelligent RBF neural network-based control for dynamic stability and power control in renewable-integrated microgrids** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-36641-9)]
- [2026] **AN AUTOMATED PODCAST GENERATION SYSTEM USING GENERATIVE AI AND NEURAL TEXT-TO-SPEECH** [[paper](https://doi.org/10.13140/rg.2.2.26532.44163)]
- [2026] **A Multi-Objective Evolutionary Neural Architecture Search Framework for Text Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6626991)]

##### 2025

- [2025] **Neural bolometers: Designing next-generation infrared thermal imagers with in-pixel neuromorphic computing** *Physical Review Applied* [[paper](https://doi.org/10.1103/1p38-2998)]
- [2025] **Neural Image abstraction using long smoothing B-splines** *ACM Transactions on Graphics* [[paper](https://arxiv.org/abs/2511.05360)]
- [2025] **Channel Modeling for 6G Optical Wireless Terahertz Communication Based on Convolutional Neural Networks** [[paper](https://doi.org/10.1109/eiecc67963.2025.11409548)]
- [2025] **Holographic voice-interactive system with omni-dimensional dynamic complex-valued convolutional neural network** *Optics & Laser Technology* [[paper](https://doi.org/10.1016/j.optlastec.2025.114219)]
- [2025] **CoVis: Neural and LLM-Driven Multi-Turn Interactions for Conversational Text-to-Visualization Generation** *The VLDB Journal* [[paper](https://doi.org/10.1007/s00778-025-00954-4)]
- [2025] **Neural Text Generation for Simulated Fault Diagnosis Scenarios in Renewable Energy Education** [[paper](https://doi.org/10.1109/itechsecom64750.2025.11307244)]
- [2025] **Direct speech-to-speech neural machine translation: A survey** *Speech Communication* [[paper](https://doi.org/10.1016/j.specom.2025.103317)]
- [2025] **A hybrid TH-LSTM-Transformer Model for text generation from EEG signals during imagined character speech** *Biomedical Signal Processing and Control* [[paper](https://doi.org/10.1016/j.bspc.2025.108871)]
- [2025] **Role of neural networks in machine translation and text generation** *Electronic Institutional Repository of the National Aviation University of Ukraine (National Aviation University, Ukraine)* [[paper](https://er.kai.edu.ua/handle/KAI/68066)]
- [2025] **Progress, challenges and future of linguistic neural decoding with deep learning** *Communications Biology* [[paper](https://doi.org/10.1038/s42003-025-08511-z)]
- [2025] **PolyGraph – Flexible, Biocompatible & Electrically Optimised Graphene-Polymer Composites for Next-Generation Neural Interfaces** *bioRxiv (Cold Spring Harbor Laboratory)* [[paper](https://doi.org/10.1101/2025.09.02.673516)]
- [2025] **NewtonGen: Physics-Consistent and Controllable Text-to-Video Generation via Neural Newtonian Dynamics** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.21309)]
- [2025] **Technology for training future mathematics teachers to use neural networks for the development of didactic materials** *Pedagogy Theory & Practice* [[paper](https://doi.org/10.30853/ped20250146)]
- [2025] **Performance analysis of concatenated Reed–Solomon and next generation polar codes for 6G communication systems** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-13672-2)]
- [2025] **Lightweight Diffusion Models Based on Multi-Objective Evolutionary Neural Architecture Search** *International Journal of Neural Systems* [[paper](https://doi.org/10.1142/s0129065725500595)]
- [2025] **Knowledge-driven innovation in industrial maintenance: A neural-enhanced model-based definition framework for lifecycle maintenance process information propagation** *Journal of Manufacturing Systems* [[paper](https://doi.org/10.1016/j.jmsy.2025.08.001)]
- [2025] **Improving Retrieval-Augmented Generation for Low-Resource Languages** [[paper](https://doi.org/10.1109/cmss66566.2025.11182476)]
- [2025] **Analyzing Heat Transfer and Irreversibility via Aggregation Dynamics in Darcy-Forchheimer Flow and Nonlinear Thermal Radiation Effects Utilizing Artificial Neural Networks** *Arabian Journal for Science and Engineering* [[paper](https://doi.org/10.1007/s13369-025-10547-6)]
- [2025] **Mamba-360: Survey of state space models as transformer alternative for long sequence modelling: Methods, Applications, and Challenges** *Engineering Applications of Artificial Intelligence* [[paper](https://doi.org/10.1016/j.engappai.2025.111279)]
- [2025] **Enhanced subtitle generation in videos: leveraging hybrid BERT–CNN–LSTM architecture for contextual understanding** *International Journal of Information Technology* [[paper](https://doi.org/10.1007/s41870-025-02610-0)]
- [2025] **Empowering Morphing Attack Detection Using Interpretable Image-Text Foundation Model** *Communications in computer and information science* [[paper](https://arxiv.org/abs/2508.10110)]
- [2025] **Diversifying Adversarial Attacks on Text-to-image Generation** *Proceedings of the Genetic and Evolutionary Computation Conference Companion* [[paper](https://doi.org/10.1145/3712255.3726755)]
- [2025] **Design of an Adaptive Defense Scheme for the Tambora Power System Based on Artificial Neural Networks** [[paper](https://doi.org/10.1109/isitia66279.2025.11137545)]
- [2025] **Learning to Sample Effective and Diverse Prompts for Text-to-Image Generation** [[paper](https://doi.org/10.1109/cvpr52734.2025.02200)]
- [2025] **HeSQLNet: A Heterogeneous graph neural network for SQL-to-Text generation** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2025.107820)]
- [2025] **eFAirWrite: Bringing energy efficient text entry to next generation smart devices** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.128306)]
- [2025] **The potential of neural networks in generating photorealistic content for media** *Moscow University Journalism Bulletin* [[paper](https://doi.org/10.55959/msu.vestnik.journ.4.2025.7895)]
- [2025] **TextBugger: an extended adversarial text attack on NLP-based text classification model** *Indonesian Journal of Electrical Engineering and Computer Science* [[paper](https://doi.org/10.11591/ijeecs.v38.i3.pp1735-1744)]
- [2025] **Talent3D: Optimizing geometry and enhancing appearance for high-quality Text-to-3D shape generation** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.130475)]
- [2025] **RFNNS: Robust Fixed Neural Network Steganography with Universal Text-to-Image Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.04116)]
- [2025] **HGNNLink: recovering requirements-code traceability links with text and dependency-aware heterogeneous graph neural networks** *Automated Software Engineering* [[paper](https://doi.org/10.1007/s10515-025-00528-2)]
- [2025] **Fuzzy-Assisted Contrastive Decoding Improving Code Generation of Large Language Models** *IEEE Transactions on Fuzzy Systems* [[paper](https://doi.org/10.1109/tfuzz.2025.3575060)]
- [2025] **DreaMark: Rooting Watermark in Score Distillation Sampling Generated Neural Radiance Fields** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i10.33197)]
- [2025] **GO-NeRF: Generating Objects in Neural Radiance Fields for Virtual Reality Content Creation** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3549558)]
- [2025] **FastTalker: An unified framework for generating speech and conversational gestures from text** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.130074)]
- [2025] **Deep learning for Chinese font generation: A survey** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.127105)]
- [2025] **Bash command comment generation via multi-scale heterogeneous feature fusion** *Automated Software Engineering* [[paper](https://doi.org/10.1007/s10515-025-00494-9)]
- [2025] **BN-GRAPH: Data Augmentation Based Bangla Text Sentiment Analysis in Deep Graph Neural Network** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-025-03763-2)]
- [2025] **Automatic trailer generation for movies using convolutional neural network** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-91084-y)]
- [2025] **Words shaping worlds: A comprehensive exploration of text-driven image and video generation with generative adversarial networks** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.129767)]
- [2025] **Screening of multi deep learning-based de novo molecular generation models and their application for specific target molecular generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-86840-z)]
- [2025] **Natural Language Generation in AI: Developing Human-Like Text Through Deep Learning** [[paper](https://doi.org/10.1109/ce2ct64011.2025.10939615)]
- [2025] **Research on the use of AI for Selecting Abstractions for Natural Language Image Generation Tools** *International Journal of Computing* [[paper](https://doi.org/10.47839/ijc.23.4.3763)]
- [2025] **Natural Language Processing Methods for Symbolic Music Generation and Information Retrieval: A Survey** *ACM Computing Surveys* [[paper](https://arxiv.org/abs/2402.17467)]
- [2025] **Latent Weight Quantization for Integerized Training of Deep Neural Networks** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3527498)]
- [2025] **FastTalker: Jointly Generating Speech and Conversational Gestures from Text** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-93806-1_14)]
- [2025] **Extractive Schema Linking for Text-to-SQL** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.17174)]
- [2025] **Enhancing Generative AI Models Through Quantum Computing for Improved Text and Image Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5198542)]
- [2025] **Enhanced Emotion-Aware Conversational Agent: Analyzing User Behavioral Status for Tailored Reponses in Chatbot Interactions** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3534197)]
- [2025] **DiffSampling: Enhancing Diversity and Accuracy in Neural Text Generation** *Archivio istituzionale della ricerca (Alma Mater Studiorum Università di Bologna)* [[paper](https://hdl.handle.net/11585/1034165)]
- [2025] **CoverGAN: cover photo generation from text story using layout guided GAN** *Soft Computing* [[paper](https://doi.org/10.1007/s00500-025-10436-y)]
- [2025] **CNO-Former: Chaotic Neural Oscillatory Transformer for Social Media Text Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-8295-9_15)]
- [2025] **Application of GenAI in Synthetic Data Generation in the Healthcare System** [[paper](https://doi.org/10.1007/978-3-031-82963-5_3)]
- [2025] **A Survey Paper on Text Visualization Using Generative Adversarial Network** *Cognitive science and technology* [[paper](https://doi.org/10.1007/978-981-97-9262-7_12)]
- [2025] **A Substation Safety Measure Ticket Generation Algorithm based on Neural Network and Inference Engine** [[paper](https://doi.org/10.1109/iciscn64258.2025.10934576)]

##### 2024

- [2024] **UNDERSTANDING NATURAL LANGUAGE PROCESSING (NLP) TECHNIQUES: FROM TEXT ANALYSIS TO LANGUAGE GENERATION** *INTERNATIONAL JOURNAL OF RESEARCH IN COMPUTER APPLICATIONS AND INFORMATION TECHNOLOGY* [[paper](https://doi.org/10.34218/ijrcait_07_02_213)]
- [2024] **Neural networks for illustration generation: towards the issue of adaptation practices** *RUDN Journal of Studies in Literature and Journalism* [[paper](https://doi.org/10.22363/2312-9220-2024-29-4-788-798)]
- [2024] **Hierarchical Contextual Embedding Through Neural Modulation for Advanced Text Comprehension** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-5545248/v1)]
- [2024] **Tell What You Hear From What You See -- Video to Audio Generation Through Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.05679)]
- [2024] **Rhyme-aware Chinese lyric generator based on GPT** [[paper](https://doi.org/10.1117/12.3049486)]
- [2024] **MagicMirror: Fast and High-Quality Avatar Generation with a Constrained Search Space** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72848-8_11)]
- [2024] **Generative Artificial Intelligence Meets Synthetic Aperture Radar: A survey** *IEEE Geoscience and Remote Sensing Magazine* [[paper](https://arxiv.org/abs/2411.05027)]
- [2024] **Generating Images Using Vanilla Generative Adversarial Networks** [[paper](https://doi.org/10.1109/ictacs62700.2024.10840720)]
- [2024] **DreamDissector: Learning Disentangled Text-to-3D Generation from 2D Diffusion Priors** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73254-6_8)]
- [2024] **Distributing Creative Responsibility Between a Knowledge-Based Content Determiner and a Neural Text Realizer** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73497-7_4)]
- [2024] **A Review of Adversarial Attacks and Defense Techniques in Text Processing Models** *Applied and Computational Engineering* [[paper](https://dx.doi.org/10.54254/2755-2721/96/20241306)]
- [2024] **iControl3D: An Interactive System for Controllable 3D Scene Generation** [[paper](https://doi.org/10.1145/3664647.3680557)]
- [2024] **Robustness of generative AI detection: adversarial attacks on black-box neural text detectors** *International Journal of Speech Technology* [[paper](https://doi.org/10.1007/s10772-024-10144-2)]
- [2024] **MVDiffusion++: A Dense High-Resolution Multi-view Diffusion Model for Single or Sparse-View 3D Object Reconstruction** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72640-8_10)]
- [2024] **From technology opportunities to solutions generation via patent analysis: Application of machine learning-based link prediction** *Advanced Engineering Informatics* [[paper](https://doi.org/10.1016/j.aei.2024.102944)]
- [2024] **A 2 × 2 Neural Amplifier Macro-Pixel with Shared DC Servo Loop for High-Density Brain-Computer Interfaces** [[paper](https://doi.org/10.1109/biocas61083.2024.10798201)]
- [2024] **TC4D: Trajectory-Conditioned Text-to-4D Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72952-2_4)]
- [2024] **Moshi: a speech-text foundation model for real-time dialogue** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.00037)]
- [2024] **Exploring the Potential of Neural Machine Translation for Cross-Language Clinical Natural Language Processing (NLP) Resource Generation through Annotation Projection** *Information* [[paper](https://doi.org/10.3390/info15100585)]
- [2024] **Evaluation of deep neural network architectures for authorship obfuscation of Portuguese texts** *Natural Language Processing Journal* [[paper](https://doi.org/10.1016/j.nlp.2024.100107)]
- [2024] **Empowering Graph Neural Network-Based Computational Drug Repositioning with Large Language Model-Inferred Knowledge Representation** *Interdisciplinary Sciences Computational Life Sciences* [[paper](https://doi.org/10.1007/s12539-024-00654-7)]
- [2024] **Advanced computational methods for news classification: A study in neural networks and CNN integrated with GPT** *Journal of Economy and Technology* [[paper](https://doi.org/10.1016/j.ject.2024.09.001)]
- [2024] **Neural surrogate-driven modelling, optimisation, and generation of engineering designs: A concise review** *Materials research proceedings* [[paper](https://doi.org/10.21741/9781644903254-53)]
- [2024] **Generative artificial intelligence in smart manufacturing** *Journal of Intelligent Manufacturing* [[paper](https://doi.org/10.1007/s10845-024-02480-6)]
- [2024] **Exploring the Potential of Neural Machine Translation for Cross-Language Clinical NLP Resource Generation through Annotation Projection** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202408.0616.v1)]
- [2024] **Conversion of Text-to-Image Generation** [[paper](https://doi.org/10.1109/iceect61758.2024.10739305)]
- [2024] **A 2.46-mm2 Miniaturized Brain-Machine Interface (MiBMI) Enabling 31-Class Brain-to-Text Decoding** *IEEE Journal of Solid-State Circuits* [[paper](https://doi.org/10.1109/jssc.2024.3443254)]
- [2024] **Portrait3D: Text-Guided High-Quality 3D Portrait Generation Using Pyramid Representation and GANs Prior** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3658162)]
- [2024] **Instruct Pix-to-3D: Instructional 3D object generation from a single image** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2024.128156)]
- [2024] **Indigenous language technology in the age of machine learning** *Acta Borealia* [[paper](https://doi.org/10.1080/08003831.2024.2410124)]
- [2024] **Image generation of hazardous situations in construction sites using text-to-image generative model for training deep neural networks** *Automation in Construction* [[paper](https://doi.org/10.1016/j.autcon.2024.105615)]
- [2024] **Dual-view graph convolutional network for multi-label text classification** *Applied Intelligence* [[paper](https://doi.org/10.1007/s10489-024-05666-w)]
- [2024] **DiLightNet: Fine-grained Lighting Control for Diffusion-based Image Generation** [[paper](https://arxiv.org/abs/2402.11929)]
- [2024] **Automated multiple-choice question generation in Spanish using neural language models** *Neural Computing and Applications* [[paper](https://doi.org/10.1007/s00521-024-10076-7)]
- [2024] **A Denoising Diffusion Probabilistic Model for Metal Artifact Reduction in CT** *IEEE Transactions on Medical Imaging* [[paper](https://doi.org/10.1109/tmi.2024.3416398)]
- [2024] **Utilizing Generative AI for Text-to-Image Generation** [[paper](https://doi.org/10.1109/icccnt61001.2024.10725454)]
- [2024] **Kalt: generating adversarial explainable chinese legal texts** *Machine Learning* [[paper](https://doi.org/10.1007/s10994-024-06572-5)]
- [2024] **DIRECT-3D: Learning Direct Text-to-3D Generation on Massive Noisy 3D Data** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.04322)]
- [2024] **AudioLCM: Text-to-Audio Generation with Latent Consistency Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.00356)]
- [2024] **Artistic Strategies to Guide Neural Networks** [[paper](https://doi.org/10.69564/isea2023-62-full-guljajeva-et-al-artistic-strategies)]
- [2024] **Approximate ground truth generation for semantic labeling of historical documents with minimal human effort** *International Journal on Document Analysis and Recognition (IJDAR)* [[paper](https://doi.org/10.1007/s10032-024-00475-w)]
- [2024] **An effective deep learning based Idrcnn and Bdc-Lstm models for complex word identification and synonym generation** *International Journal of Information Technology* [[paper](https://doi.org/10.1007/s41870-024-01973-0)]
- [2024] **A Current-Source-Free Constant-Current Wireless Adiabatic Neural Stimulator Achieving a 5.5-27.7x Improved RF-to-Electrode Stimulation Efficiency Factor** [[paper](https://dx.doi.org/10.1109/vlsitechnologyandcir46783.2024.10631437)]
- [2024] **TiV-ODE: A Neural ODE-based Approach for Controllable Video Generation From Text-Image Pairs** [[paper](https://dx.doi.org/10.1109/icra57147.2024.10610149)]
- [2024] **Structural and philological features of text generative neural networks** *Neophilology* [[paper](https://doi.org/10.20310/2587-6953-2024-10-2-452-464)]
- [2024] **Siracusa: A 16 nm Heterogenous RISC-V SoC for Extended Reality With At-MRAM Neural Engine** *IEEE Journal of Solid-State Circuits* [[paper](https://doi.org/10.1109/jssc.2024.3385987)]
- [2024] **Multi-grained visual pivot-guided multi-modal neural machine translation with text-aware cross-modal contrastive disentangling** *Neural Networks* [[paper](https://doi.org/10.1016/j.neunet.2024.106403)]
- [2024] **Instant3D: Instant Text-to-3D Generation** *International Journal of Computer Vision* [[paper](https://doi.org/10.1007/s11263-024-02097-5)]
- [2024] **Image Generation Using AI with Effective Audio Playback System** [[paper](https://doi.org/10.1109/incet61516.2024.10593387)]
- [2024] **Dual3D: Efficient and Consistent Text-to-3D Generation with Dual-mode Multi-view Latent Diffusion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.09874)]
- [2024] **Artist-Guided Neural Networks – Automated Creativity or Tools for Extending Minds?** *transcript Verlag eBooks* [[paper](https://doi.org/10.1515/9783839469224-004)]
- [2024] **Affect-Conditioned Image Generation** *IEEE Transactions on Affective Computing* [[paper](https://dx.doi.org/10.1109/taffc.2024.3406726)]
- [2024] **A Frustratingly Simple Decoding Method for Neural Text Generation** [[paper](https://doi.org/10.63317/2ga32r8djemq)]
- [2024] **Text-image conditioned diffusion for consistent text-to-3D generation** *Computer Aided Geometric Design* [[paper](https://doi.org/10.1016/j.cagd.2024.102292)]
- [2024] **Text-Guided Real-World-to-3D Generative Models with Real-Time Rendering on Mobile Devices** [[paper](https://doi.org/10.1109/wcnc57260.2024.10571062)]
- [2024] **Research on Text Summary Generation Algorithm Based on Fusion Neural Network and Knowledge Distillation** [[paper](https://dx.doi.org/10.1109/iccea62105.2024.10603522)]
- [2024] **OpenAI’s Sora in ophthalmology: revolutionary generative AI in eye health** *Eye* [[paper](https://doi.org/10.1038/s41433-024-03098-x)]
- [2024] **Condition-Aware Neural Network for Controlled Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.01143)]
- [2024] **eVAE: Evolutionary Variational Autoencoder** *IEEE Transactions on Neural Networks and Learning Systems* [[paper](https://doi.org/10.1109/tnnls.2024.3359275)]
- [2024] **Variational Monte Carlo with large patched transformers** *Communications Physics* [[paper](https://doi.org/10.1038/s42005-024-01584-y)]
- [2024] **TextMesh: Generation of Realistic 3D Meshes From Text Prompts** [[paper](https://doi.org/10.1109/3dv62453.2024.00154)]
- [2024] **Real3D: The Curious Case of Neural Scene Degeneration** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i2.27863)]
- [2024] **Performance Analysis of Deepfake Text Detection Techniques on Social-media** [[paper](https://doi.org/10.1109/icdcot61034.2024.10515626)]
- [2024] **Near Real-Time Syndromic Surveillance of Emergency Department Triage Texts Using Natural Language Processing: Case Study in Febrile Convulsion Detection** *JMIR AI* [[paper](https://doi.org/10.2196/54449)]
- [2024] **GTLNLP: A Mathematical Exploration of Cross-Domain Knowledge Transfer for Text Generation for Generative Transfer Learning in Natural Language Processing** *Journal of Electrical Systems* [[paper](https://doi.org/10.52783/jes.778)]
- [2024] **Speech-to-SQL: toward speech-driven SQL query generation from natural language question** *The VLDB Journal* [[paper](https://doi.org/10.1007/s00778-024-00837-0)]
- [2024] **Generative pretrained transformer-4, an artificial intelligence text predictive model, has a high capability for passing novel written radiology exam questions** *International Journal of Computer Assisted Radiology and Surgery* [[paper](https://doi.org/10.1007/s11548-024-03071-9)]
- [2024] **CMB delensing with neural network based lensing reconstruction in the presence of primordial tensor perturbations** *Physical review. D/Physical review. D.* [[paper](https://doi.org/10.1103/physrevd.109.043518)]
- [2024] **AI Innovator: Text to Image Generation using GAN** [[paper](https://doi.org/10.1109/sceecs61402.2024.10482008)]
- [2024] **fTSPL: Enhancing Brain Analysis with FMRI-Text Synergistic Prompt Learning** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72390-2_53)]
- [2024] **Vision AI-based human-robot collaborative assembly driven by autonomous robots** *CIRP Annals* [[paper](https://doi.org/10.1016/j.cirp.2024.03.004)]
- [2024] **Transforming Text into Art: Exploring DALL-E’s Text-to-Image Generation Capabilities** *Algorithms for intelligent systems* [[paper](https://doi.org/10.1007/978-981-97-3191-6_31)]
- [2024] **To Enhance the Efficiency and Features of Text to Image Generation Using Neural Network Models** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-75957-4_8)]
- [2024] **Text Identification for Questions Generation According to Bloom's Taxonomy Using Natural Language Processing** [[paper](https://doi.org/10.1007/978-981-99-9379-6_16)]
- [2024] **Review on Hybrid Deep Learning Models for Enhancing Encryption Techniques Against Side Channel Attacks** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3431218)]
- [2024] **Recurrent Neural Networks for Text Generation** *Studies in computational intelligence* [[paper](https://doi.org/10.1007/978-3-031-76516-2_11)]
- [2024] **Plain Language in the Age of Neural Machine Translation: An Opportunity for Translators** *New frontiers in translation studies* [[paper](https://doi.org/10.1007/978-981-97-2958-6_9)]
- [2024] **Neuro-Evolution-Based Language Model for Text Generation** *IFIP advances in information and communication technology* [[paper](https://doi.org/10.1007/978-3-031-69982-5_10)]
- [2024] **Nested Diffusion Processes for Anytime Image Generation** [[paper](https://doi.org/10.1109/wacv57701.2024.00493)]
- [2024] **MorphNeRF: Text-Guided 3D-Aware Editing via Morphing Generative Neural Radiance Fields** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2024.3379888)]
- [2024] **Large Language Model and Text Generation** *Cognitive informatics in biomedicine and healthcare* [[paper](https://doi.org/10.1007/978-3-031-55865-8_10)]
- [2024] **LATTE3D: Large-scale Amortized Text-To-Enhanced3D Synthesis** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72980-5_18)]
- [2024] **Hybrid Approach Text Generation for Low-Resource Language** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-70248-8_20)]
- [2024] **Folded ensemble deep learning based text generation on the brain signal** *Multimedia Tools and Applications* [[paper](https://doi.org/10.1007/s11042-024-18124-z)]
- [2024] **Exploring Language Diversity to Improve Neural Text Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-97-5489-2_22)]
- [2024] **Exploring Causal Chain Identification: Comprehensive Insights from Text and Knowledge Graphs** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-68323-7_11)]
- [2024] **Enhancing Chest X-ray Analysis using Encoder-Decoder with GRU for Report Generation** [[paper](https://doi.org/10.1109/icaect60202.2024.10469644)]
- [2024] **Digital Evolution of Universities: Neural Networks in Education** *Springer geography* [[paper](https://doi.org/10.1007/978-3-031-70886-2_38)]
- [2024] **CM-TTS: Enhancing Real Time Text-to-Speech Synthesis Efficiency through Weighted Samplers and Consistency Models** [[paper](https://doi.org/10.18653/v1/2024.findings-naacl.240)]
- [2024] **CLASSIFICATION OF NEURAL NETWORKS FOR CREATING EDUCATIONAL CONTENT BY UNIVERSITY EDUCATORS** *Вестник Южно-Уральского государственного университета. Серия: Образование. Педагогические науки* [[paper](https://doi.org/10.14529/ped240202)]
- [2024] **A transformer-based approach for Arabic offline handwritten text recognition** *Signal Image and Video Processing* [[paper](https://doi.org/10.1007/s11760-023-02970-9)]

##### 2023

- [2023] **RETRACTED ARTICLE: Artificial intelligence recruitment text automatic generation based on light detection and improved neural network algorithm** *Optical and Quantum Electronics* [[paper](https://doi.org/10.1007/s11082-023-05770-0)]
- [2023] **Open writer identification from handwritten text fragments using lite convolutional neural network** *International Journal on Document Analysis and Recognition (IJDAR)* [[paper](https://doi.org/10.1007/s10032-023-00458-3)]
- [2023] **Improving rare relation inferring for scene graph generation using bipartite graph network** *Computer Vision and Image Understanding* [[paper](https://doi.org/10.1016/j.cviu.2023.103901)]
- [2023] **From Reconstruction to Generation: State-of-Art Approaches for 3D Visualization** [[paper](https://doi.org/10.1145/3610538.3614647)]
- [2023] **Context-Aware Linguistic Steganography Model Based on Neural Machine Translation** *IEEE/ACM Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslp.2023.3340601)]
- [2023] **Assessing the Effect of Text Type on the Choice of Linguistic Mechanisms in Scientific Publications** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-50628-4_9)]
- [2023] **A prompt-based approach to adversarial example generation and robustness enhancement** *Frontiers of Computer Science* [[paper](https://doi.org/10.1007/s11704-023-2639-2)]
- [2023] **Text to Image Generation with Conformer-GAN** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-8073-4_1)]
- [2023] **Neural network-based regression for heat transfer and fluid flow over in-line cylinder arrays with random pitch distances at low Reynolds number** *Engineering Applications of Computational Fluid Mechanics* [[paper](https://doi.org/10.1080/19942060.2023.2288235)]
- [2023] **LCM-LoRA: A Universal Stable-Diffusion Acceleration Module** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.05556)]
- [2023] **Context-Dependent Text-to-SQL Generation with Intermediate Representation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-7019-3_21)]
- [2023] **CLIP-Head: Text-Guided Generation of Textured Neural Parametric 3D Head Models** [[paper](https://doi.org/10.1145/3610543.3626169)]
- [2023] **Analysis of the Basic Image Generation Methods by Neural Networks** [[paper](https://dx.doi.org/10.1109/tirved58506.2023.10332668)]
- [2023] **An explanation framework and method for AI-based text emotion analysis and visualisation** *Decision Support Systems* [[paper](https://doi.org/10.1016/j.dss.2023.114121)]
- [2023] **A Comprehensive Survey on Methods for Image Integrity** *ACM Transactions on Multimedia Computing Communications and Applications* [[paper](https://doi.org/10.1145/3633203)]
- [2023] **The FineMotion entry to the GENEA Challenge 2023: DeepPhase for conversational gestures generation** *INTERNATIONAL CONFERENCE ON MULTIMODAL INTERACTION* [[paper](https://doi.org/10.1145/3577190.3616119)]
- [2023] **Method for testing NLP models with text adversarial examples** *Scientific and technical journal of information technologies mechanics and optics* [[paper](https://doi.org/10.17586/2226-1494-2023-23-5-946-954)]
- [2023] **JointNet: Extending Text-to-Image Diffusion for Dense Distribution Modeling** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.06347)]
- [2023] **Dispute Classification and Analysis: Deep Learning–Based Text Mining for Construction Contract Management** *Journal of Construction Engineering and Management* [[paper](https://doi.org/10.1061/jcemd4.coeng-14080)]
- [2023] **VulGAI: vulnerability detection based on graphs and images** *Computers & Security* [[paper](https://doi.org/10.1016/j.cose.2023.103501)]
- [2023] **Learning to Diversify Neural Text Generation via Degenerative Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.12619)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Prompt Engineering for Cohesive and Factually Reliable Neural Text Generation: a 2025–2026 Structured Review with Gherkin-Inspired Prompt Design** [[paper](https://doi.org/10.1109/neuront71829.2026.11651386)]

##### 2025

- [2025] **The architecture of language: Understanding the mechanics behind LLMs** *Cambridge Forum on AI Law and Governance* [[paper](https://doi.org/10.1017/cfl.2024.16)]

##### 2024

- [2024] **Large Language Model Enhanced Text-to-SQL Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.06011)]
- [2024] **GAugLLM: Improving Graph Contrastive Learning for Text-Attributed Graphs with Large Language Models** [[paper](https://doi.org/10.1145/3637528.3672035)]
- [2024] **Large language models for biomedicine: foundations, opportunities, challenges, and best practices** *Journal of the American Medical Informatics Association* [[paper](https://doi.org/10.1093/jamia/ocae074)]
- [2024] **Prompt Engineering for Generative Artificial Intelligence in Gastroenterology and Hepatology** *The American Journal of Gastroenterology* [[paper](https://doi.org/10.14309/ajg.0000000000002689)]
- [2024] **LLaMA-LoRA Neural Prompt Engineering: A Deep Tuning Framework for Automatically Generating Chinese Text Logical Reasoning Thinking Chains** *Data Intelligence* [[paper](https://doi.org/10.1162/dint_a_00251)]

##### 2023

- [2023] **Large Language Models as Topological Structure Enhancers for Text-Attributed Graphs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.14324)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **Think Fast, Talk Smart: Partitioning Deterministic and Neural Computation for Structured Health Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.29652)]
- [2026] **A Unified Neural Codec Language Model for Selective Editable Text to Speech Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.12480)]

##### 2025

- [2025] **Pseudo-Autoregressive Neural Codec Language Models for Efficient Zero-Shot Text-to-Speech Synthesis** [[paper](https://doi.org/10.1145/3746027.3754745)]
- [2025] **Leveraging Large Language Models for Node Generation in Few-Shot Learning on Text-Attributed Graphs** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i12.33428)]
- [2025] **ELLA-V: Stable Neural Codec Language Modeling with Alignment-Guided Sequence Reordering** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i24.34703)]
- [2025] **Cross-Domain Multi-Modal Few-Shot Object Detection via Rich Text** [[paper](https://doi.org/10.1109/wacv61041.2025.00640)]
- [2025] **Vec-Tok Speech: Speech Vectorization and Tokenization for Neural Speech Generation** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2025.3546559)]
- [2025] **Retrieval‐augmented generation versus document‐grounded generation: a key distinction in large language models** *The Journal of Pathology Clinical Research* [[paper](https://doi.org/10.1002/2056-4538.70014)]
- [2025] **Controllable neural text generation in persona-based dialogue systems** [[paper](https://doi.org/10.32657/10356/182528)]

##### 2024

- [2024] **Leveraging Large Language Models for Improving Keyphrase Generation for Contextual Targeting** [[paper](https://doi.org/10.1145/3627673.3680093)]
- [2024] **A cross‐dataset study on automatic detection of autism spectrum disorder from text data** *Acta Psychiatrica Scandinavica* [[paper](https://doi.org/10.1111/acps.13737)]
- [2024] **TextGrad: Automatic "Differentiation" via Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.07496)]
- [2024] **Heuristic question sequence generation based on retrieval augmentation** *Education and lifelong development research.* [[paper](https://doi.org/10.46690/elder.2024.02.03)]
- [2024] **Optimizing large language models in digestive disease: strategies and challenges to improve clinical outcomes** *Liver International* [[paper](https://doi.org/10.1111/liv.15974)]
- [2024] **Bridging Languages through Images: A Multilingual Text-to-Image Synthesis Approach** *INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT* [[paper](https://doi.org/10.55041/ijsrem33773)]
- [2024] **ZeroNLG: Aligning and Autoencoding Domains for Zero-Shot Multimodal and Multilingual Natural Language Generation** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2024.3371376)]
- [2024] **VoiceCraft: Zero-Shot Speech Editing and Text-to-Speech in the Wild** [[paper](https://doi.org/10.18653/v1/2024.acl-long.673)]
- [2024] **SpeechX: Neural Codec Language Model as a Versatile Speech Transformer** *IEEE/ACM Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslp.2024.3419418)]

##### 2023

- [2023] **On the Zero-Shot Generalization of Machine-Generated Text Detectors** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.05165)]
- [2023] **HyperFields: Towards Zero-Shot Generation of NeRFs from Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.17075)]
- [2023] **GraphText: Graph Reasoning in Text Space** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.01089)]
- [2023] **Contrastive Learning Approach for Text-to Image Synthesis** [[paper](https://doi.org/10.1109/icacta58201.2023.10392445)]
- [2023] **Blended-NeRF: Zero-Shot Object Generation and Blending in Existing Neural Radiance Fields** [[paper](https://doi.org/10.1109/iccvw60793.2023.00316)]
- [2023] **AvatarFusion: Zero-shot Generation of Clothing-Decoupled 3D Avatars Using 2D Diffusion** [[paper](https://arxiv.org/abs/2307.06526)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2026

- [2026] **Reliability Challenges in Diffusion Vision-Language Models** [[paper](https://arxiv.org/abs/2609.01318)]
- [2026] **Financial Numerical Prediction and Allocation as Token Generation** [[paper](https://arxiv.org/abs/2608.09880)]
- [2026] **Balancing Efficiency and Efficacy: Training-Free Attention-Guided Switching Between Explicit and Latent Thoughts for MLLMs** [[paper](https://arxiv.org/abs/2608.03450)] [[code](https://github.com/swordAndSnow/MM26-AGS)]
- [2026] **Structure-aware neural generation of text from SQL queries** *Fuzzy Optimization and Decision Making* [[paper](https://doi.org/10.1007/s10700-026-09478-0)]
- [2026] **Global Sketch-Based Watermarking for Diffusion Language Models** [[paper](https://arxiv.org/abs/2606.04486)]
- [2026] **From Architecture to Output: Structural Origins of Hallucination in Large Language Models and the Amplifying Role of Data** [[paper](https://arxiv.org/abs/2606.07537)]
- [2026] **WavSLM: Single-Stream Speech Language Modeling via WavLM Distillation** [[paper](https://arxiv.org/abs/2603.05299)]
- [2026] **Towards Poisoning Robustness Certification for Natural Language Generation** [[paper](https://arxiv.org/abs/2602.09757)]
- [2026] **DICE: Diffusion Large Language Models Excel at Generating CUDA Kernels** [[paper](https://arxiv.org/abs/2602.11715)]
- [2026] **A sampling-based exploration of neural text generation models** *UvA-DARE (University of Amsterdam)* [[paper](https://handle.uba.uva.nl/personal/pure/en/publications/a-samplingbased-exploration-of-neural-text-generation-models(9cd9d44e-f091-4135-9dc3-5e33f232d9d9).html)]

##### 2025

- [2025] **Mechanistic Interpretability of Antibody Language Models Using SAEs** [[paper](https://arxiv.org/abs/2512.05794)]
- [2025] **GCG Attack On A Diffusion LLM** [[paper](https://arxiv.org/abs/2601.14266)]
- [2025] **DELTA: Language Diffusion-based EEG-to-Text Architecture** [[paper](https://arxiv.org/abs/2511.21746)]
- [2025] **Saber: An Efficient Sampling with Adaptive Acceleration and Backtracking Enhanced Remasking for Diffusion Language Model** [[paper](https://arxiv.org/abs/2510.18165)]
- [2025] **RAG-IGBench: Innovative Evaluation for RAG-based Interleaved Generation in Open-domain Question Answering** [[paper](https://arxiv.org/abs/2512.05119)] [[code](https://github.com/USTC-StarTeam/RAG-IGBench)]
- [2025] **On Powerful Ways to Generate: Autoregression, Diffusion, and Beyond** [[paper](https://arxiv.org/abs/2510.06190)]
- [2025] **Efficient Parallel Samplers for Recurrent-Depth Models and Their Connection to Diffusion Language Models** [[paper](https://arxiv.org/abs/2510.14961)]
- [2025] **A Multimodal, Multitask System for Generating E Commerce Text Listings from Images** [[paper](https://arxiv.org/abs/2510.21835)]
- [2025] **Why mask diffusion does not work** [[paper](https://arxiv.org/abs/2510.03289)]
- [2025] **Latent Visual Reasoning** [[paper](https://arxiv.org/abs/2509.24251)]
- [2025] **From Text to Talk: Audio-Language Model Needs Non-Autoregressive Joint Training** [[paper](https://arxiv.org/abs/2509.20072)]
- [2025] **DSCC-HS: A Dynamic Self-Reinforcing Framework for Hallucination Suppression in Large Language Models** [[paper](https://arxiv.org/abs/2509.13702)]
- [2025] **A Survey on Parallel Text Generation: From Parallel Decoding to Diffusion Language Models** [[paper](https://arxiv.org/abs/2508.08712)] [[code](https://github.com/zhanglingzhe0820/Awesome-Parallel-Text-Generation)]
- [2025] **Unveiling the Potential of Diffusion Large Language Model in Controllable Generation** [[paper](https://arxiv.org/abs/2507.04504)]
- [2025] **Language Models for Controllable DNA Sequence Design** [[paper](https://arxiv.org/abs/2507.19523)] [[code](https://github.com/divelab/AIRS)]
- [2025] **Esoteric Language Models: A Family of Any-Order Diffusion LLMs** [[paper](https://arxiv.org/abs/2506.01928)]
- [2025] **Unifying Continuous and Discrete Text Diffusion with Non-simultaneous Diffusion Processes** [[paper](https://arxiv.org/abs/2505.22165)]
- [2025] **Generative Adversarial Neural Networks for Random and Complex Chord Progression Generation** [[paper](https://doi.org/10.23919/fruct65909.2025.11008228)]
- [2025] **CASTILLO: Characterizing Response Length Distributions of Large Language Models** [[paper](https://arxiv.org/abs/2505.16881)]
- [2025] **Bridging Communication Gaps: Advancements, Challenges, and Future Directions in Text-to-Sign Language Translation** *Journal of Future Artificial Intelligence and Technologies* [[paper](https://doi.org/10.62411/faith.3048-3719-91)]
- [2025] **Breaking AR's Sampling Bottleneck: Provable Acceleration via Diffusion Language Models** *NeurIPS 2025* [[paper](https://arxiv.org/abs/2505.21400)]
- [2025] **TRACE Back from the Future: A Probabilistic Reasoning Approach to Controllable Language Generation** [[paper](https://arxiv.org/abs/2504.18535)] [[code](https://github.com/yidouweng/trace)]
- [2025] **The Best of Both Worlds: Integrating Language Models and Diffusion Models for Video Generation** [[paper](https://arxiv.org/abs/2503.04606)] [[project](https://landiff.github.io/)]
- [2025] **TTS-Transducer: End-to-End Speech Synthesis with Neural Transducer** [[paper](https://arxiv.org/abs/2501.06320)]
- [2025] **Qwen2.5-Omni Technical Report** [[paper](https://arxiv.org/abs/2503.20215)]
- [2025] **ObscuraCoder: Powering Efficient Code LM Pre-Training Via Obfuscation Grounding** [[paper](https://arxiv.org/abs/2504.00019)]
- [2025] **Constrained Discrete Diffusion** [[paper](https://arxiv.org/abs/2503.09790)]
- [2025] **Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models** [[paper](https://arxiv.org/abs/2503.09573)]
- [2025] **UniCMs: A Unified Consistency Model For Efficient Multimodal Generation and Understanding** [[paper](https://arxiv.org/abs/2502.05415)] [[code](https://github.com/zhijie-group/UniCMs)]
- [2025] **Reflection-Window Decoding: Text Generation with Selective Refinement** [[paper](https://arxiv.org/abs/2502.03678)]
- [2025] **InspireMusic: Integrating Super Resolution and Large Language Model for High-Fidelity Long-Form Music Generation** [[paper](https://arxiv.org/abs/2503.00084)] [[code](https://github.com/FunAudioLLM/InspireMusic)]
- [2025] **Flatten Graphs as Sequences: Transformers are Scalable Graph Generators** *NeurIPS 2025* [[paper](https://arxiv.org/abs/2502.02216)] [[code](https://github.com/BorgwardtLab/AutoGraph)]
- [2025] **Evaluation of Large Language Models via Coupled Token Generation** [[paper](https://arxiv.org/abs/2502.01754)]
- [2025] **Entropy-UID: A Method for Optimizing Information Density** [[paper](https://arxiv.org/abs/2502.14366)]
- [2025] **PackDiT: Joint Human Motion and Text Generation via Mutual Prompting** [[paper](https://arxiv.org/abs/2501.16551)]

##### 2024

- [2024] **Segment-Level Diffusion: A Framework for Controllable Long-Form Generation with Diffusion Language Models** [[paper](https://arxiv.org/abs/2412.11333)]
- [2024] **RenAIssance: A Survey Into AI Text-to-Image Generation in the Era of Large Model** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2024.3522305)]
- [2024] **GL-Fusion: Rethinking the Combination of Graph Neural Network and Large Language model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.06849)]
- [2024] **Dual Diffusion for Unified Image Generation and Understanding** [[paper](https://arxiv.org/abs/2501.00289)]
- [2024] **Think While You Generate: Discrete Diffusion with Planned Denoising** [[paper](https://arxiv.org/abs/2410.06264)] [[code](https://github.com/liusulin/DDPD)]
- [2024] **Improving Retrieval-Augmented Code Comment Generation by Retrieving for Generation** [[paper](https://doi.org/10.1109/icsme58944.2024.00040)]
- [2024] **Energy-Based Diffusion Language Models for Text Generation** [[paper](https://arxiv.org/abs/2410.21357)] [[code](https://github.com/MinkaiXu/Energy-Diffusion-LLM)]
- [2024] **A Study on Non-Autoregressive Mongolian-Chinese Neural Machine Translation for Multilingual Pre-Training** [[paper](https://doi.org/10.1109/mlnlp63328.2024.10800156)]
- [2024] **Spelling Correction through Rewriting of Non-Autoregressive ASR Lattices** [[paper](https://arxiv.org/abs/2409.16469)]
- [2024] **MIO: A Foundation Model on Multimodal Tokens** [[paper](https://arxiv.org/abs/2409.17692)]
- [2024] **VAIV bio-discovery service using transformer model and retrieval augmented generation** *BMC Bioinformatics* [[paper](https://doi.org/10.1186/s12859-024-05903-6)]
- [2024] **ANOLE: An Open, Autoregressive, Native Large Multimodal Models for Interleaved Image-Text Generation** [[paper](https://arxiv.org/abs/2407.06135)]
- [2024] **SC2: Towards Enhancing Content Preservation and Style Consistency in Long Text Style Transfer** [[paper](https://arxiv.org/abs/2406.04578)] [[code](https://github.com/jiezhao6/SC2)]
- [2024] **Challenges and Opportunities in Text Generation Explainability** [[paper](https://arxiv.org/abs/2405.08468)]
- [2024] **Training LLMs over Neurally Compressed Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.03626)]
- [2024] **Pre-Trained Language Models for Text Generation: A Survey** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3649449)]
- [2024] **Hierarchical Skip Decoding for Efficient Autoregressive Text Generation** [[paper](https://arxiv.org/abs/2403.14919)]
- [2024] **SyntaxShap: Syntax-aware Explainability Method for Text Generation** [[paper](https://arxiv.org/abs/2402.09259)]
- [2024] **FastSpeech: Fast, Robust and Controllable Text to Speech** *TIB Data Manager* [[paper](https://doi.org/10.57702/jd8hw0cw)]
- [2024] **Efficient Parallel Audio Generation using Group Masked Language Modeling** [[paper](https://arxiv.org/abs/2401.01099)]

##### 2023

- [2023] **Paralinguistics-Enhanced Large Language Modeling of Spoken Dialogue** [[paper](https://arxiv.org/abs/2312.15316)]
- [2023] **General Point Model with Autoencoding and Autoregressive** [[paper](https://arxiv.org/abs/2310.16861)]
- [2023] **Beyond MLE: Convex Learning for Text Generation** [[paper](https://arxiv.org/abs/2310.17217)] [[code](https://github.com/ictnlp/Convex-Learning)]
- [2023] **A‐PGRD: Attention‐based automatic business process model generation from RPA process description** *Concurrency and Computation Practice and Experience* [[paper](https://doi.org/10.1002/cpe.7940)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2026

- [2026] **The Illusion of Control: Why Bare Classifier Inversion Silently Fails in Concept-Bottleneck Text Generation** [[paper](https://arxiv.org/abs/2608.22956)]
- [2026] **SPOC-SQL: Stage-wise Preference Optimization for Controllable Text-to-SQL** [[paper](https://arxiv.org/abs/2608.22772)]
- [2026] **MemOps: Benchmarking Lifecycle Memory Operations in Long-Horizon Conversations** [[paper](https://arxiv.org/abs/2607.12893)]
- [2026] **Computational Humor with Multimodal LLMs: Methods, Datasets, Evaluation, and Challenges** [[paper](https://arxiv.org/abs/2607.19011)]
- [2026] **The Verbose Context Problem in Medical Records** [[paper](https://arxiv.org/abs/2606.29503)]
- [2026] **CombEval: A Framework for Evaluating Combinatorial Counting in Large Language Models** [[paper](https://arxiv.org/abs/2606.19788)] [[code](https://github.com/YuxuZhou-CN/combination-problem-generation)]
- [2026] **Do Large Language Models Plan Answer Positions? Position Bias in Multiple-Choice Question Generation** [[paper](https://arxiv.org/abs/2605.01846)]
- [2026] **A Comparative Study of Controlled Text Generation Systems Using Level-Playing-Field Evaluation Principles** [[paper](https://arxiv.org/abs/2605.12395)]
- [2026] **Narrix: Remixing Narrative Strategies from Examples for Story Writing** [[paper](https://arxiv.org/abs/2604.07643)]
- [2026] **Instruction-Guided Poetry Generation in Arabic and Its Dialects** [[paper](https://arxiv.org/abs/2604.27766)] [[code](https://github.com/mbzuai-nlp/instructpoet-ar)]
- [2026] **Conversational Control with Ontologies for Large Language Models: A Lightweight Framework for Constrained Generation** [[paper](https://arxiv.org/abs/2604.04450)]
- [2026] **Context-Aware Dialectal Arabic Machine Translation with Interactive Region and Register Selection** [[paper](https://arxiv.org/abs/2604.06456)]
- [2026] **Are Emotion and Rhetoric Neurons in LLM? Neuron Recognition and Adaptive Masking for Emotion-Rhetoric Prediction Steering** [[paper](https://arxiv.org/abs/2604.17255)]
- [2026] **LLM-guided headline rewriting for clickability enhancement without clickbait** [[paper](https://arxiv.org/abs/2603.22459)]
- [2026] **Audio ControlNet for Fine-Grained Audio Generation and Editing** [[paper](https://arxiv.org/abs/2602.04680)]
- [2026] **The Mouth is Not the Brain: Bridging Energy-Based World Models and Language Generation** [[paper](https://arxiv.org/abs/2601.17094)]
- [2026] **Steering Language Models Before They Speak: Logit-Level Interventions** [[paper](https://arxiv.org/abs/2601.10960)]
- [2026] **SonicBench: Dissecting the Physical Perception Bottleneck in Large Audio Language Models** [[paper](https://arxiv.org/abs/2601.11039)]
- [2026] **Factuality on Demand: Controlling the Factuality-Informativeness Trade-off in Text Generation** [[paper](https://arxiv.org/abs/2602.00848)]
- [2026] **DREAMSTATE: Diffusing States and Parameters for Recurrent Large Language Models** [[paper](https://arxiv.org/abs/2601.19221)] [[project](https://huggingface.co/2dgx41s/DreamState)]
- [2026] **Can AI-Generated Persuasion Be Detected? Persuaficial Benchmark and AI vs. Human Linguistic Differences** [[paper](https://arxiv.org/abs/2601.04925)]

##### 2025

- [2025] **Uni-MoE-2.0-Omni: Scaling Language-Centric Omnimodal Large Model with Advanced MoE, Training and Data** [[paper](https://arxiv.org/abs/2511.12609)]
- [2025] **Stemming Hallucination in Language Models Using a Licensing Oracle** [[paper](https://arxiv.org/abs/2511.06073)]
- [2025] **Difficulty-Controllable Cloze Question Distractor Generation** [[paper](https://arxiv.org/abs/2511.01526)]
- [2025] **Controllable Stylistic Text Generation with Train-Time Attribute-Regularized Diffusion** [[paper](https://arxiv.org/abs/2510.06386)]
- [2025] **Bridging the Gap Between Multimodal Foundation Models and World Models** [[paper](https://arxiv.org/abs/2510.03727)]
- [2025] **VideoScore2: Think before You Score in Generative Video Evaluation** [[paper](https://arxiv.org/abs/2509.22799)] [[project](https://tiger-ai-lab.github.io/VideoScore2/)]
- [2025] **Cognitive-Level Adaptive Generation via Capability-Aware Retrieval and Style Adaptation** [[paper](https://arxiv.org/abs/2509.19336)]
- [2025] **BTC-SAM: Leveraging LLMs for Generation of Bias Test Cases for Sentiment Analysis Models** *EMNLP 2025 main conference* [[paper](https://arxiv.org/abs/2509.24101)]
- [2025] **Vec2Summ: Text Summarization via Probabilistic Sentence Embeddings** [[paper](https://arxiv.org/abs/2508.07017)]
- [2025] **Semantic Bridge: Universal Multi-Hop Question Generation via AMR-Driven Graph Synthesis** [[paper](https://arxiv.org/abs/2508.10013)]
- [2025] **Toward Beginner-Friendly LLMs for Language Learning: Controlling Difficulty in Conversation** [[paper](https://arxiv.org/abs/2506.04072)]
- [2025] **Multi-Amateur Contrastive Decoding for Text Generation** [[paper](https://arxiv.org/abs/2507.21086)]
- [2025] **MORSE-500: A Programmatically Controllable Video Benchmark to Stress-Test Multimodal Reasoning** [[paper](https://arxiv.org/abs/2506.05523)]
- [2025] **URLs Help, Topics Guide: Understanding Metadata Utility in LLM Training** [[paper](https://arxiv.org/abs/2505.16570)]
- [2025] **Prompting is not Enough: Exploring Knowledge Integration and Controllable Generation** [[paper](https://arxiv.org/abs/2505.19660)] [[code](https://github.com/USTC-StarTeam/GenKI)]
- [2025] **GraphGen: Enhancing Supervised Fine-Tuning for LLMs with Knowledge-Driven Synthetic Data Generation** [[paper](https://arxiv.org/abs/2505.20416)] [[code](https://github.com/open-sciencelab/GraphGen)]
- [2025] **Syntactic and Semantic Control of Large Language Models via Sequential Monte Carlo** [[paper](https://arxiv.org/abs/2504.13139)]
- [2025] **Q-FAKER: Query-free Hard Black-box Attack via Controlled Generation** [[paper](https://arxiv.org/abs/2504.13551)]
- [2025] **Controllable Text-to-3D Generation via Surface-Aligned Gaussian Splatting** [[paper](https://doi.org/10.1109/3dv66043.2025.00107)]
- [2025] **BRIDGE: Bootstrapping Text to Control Time-Series Generation via Multi-Agent Iterative Optimization and Diffusion Modeling** [[paper](https://arxiv.org/abs/2503.02445)]
- [2025] **Sentence Smith: Controllable Edits for Evaluating Text Embeddings** [[paper](https://arxiv.org/abs/2502.14734)]
- [2025] **IMAGINE-E: Image Generation Intelligence Evaluation of State-of-the-art Text-to-Image Models** [[paper](https://arxiv.org/abs/2501.13920)] [[code](https://github.com/jylei16/Imagine-e)]
- [2025] **Controlling Large Language Models Through Concept Activation Vectors** [[paper](https://arxiv.org/abs/2501.05764)]

##### 2024

- [2024] **Sim911: Towards Effective and Equitable 9-1-1 Dispatcher Training with an LLM-Enabled Simulation** [[paper](https://arxiv.org/abs/2412.16844)]
- [2024] **Concept Bottleneck Large Language Models** [[paper](https://arxiv.org/abs/2412.07992)] [[code](https://github.com/Trustworthy-ML-Lab/CB-LLMs)]
- [2024] **Teaching Models to Improve on Tape** [[paper](https://arxiv.org/abs/2411.01483)]
- [2024] **Quantitative Assessment of Intersectional Empathetic Bias and Understanding** [[paper](https://arxiv.org/abs/2411.05777)]
- [2024] **Energy Efficient Protein Language Models: Leveraging Small Language Models with LoRA for Controllable Protein Generation** [[paper](https://arxiv.org/abs/2411.05966)]
- [2024] **InstructG2I: Synthesizing Images from Multimodal Attributed Graphs** [[paper](https://arxiv.org/abs/2410.07157)] [[code](https://github.com/PeterGriffinJin/InstructG2I)]
- [2024] **Fictitious Synthetic Data Can Improve LLM Factuality via Prerequisite Learning** [[paper](https://arxiv.org/abs/2410.19290)] [[code](https://github.com/UCSB-NLP-Chang/Prereq_tune.git)]
- [2024] **Control Large Language Models via Divide and Conquer** [[paper](https://arxiv.org/abs/2410.04628)]
- [2024] **Open-domain Implicit Format Control for Large Language Model Generation** [[paper](https://arxiv.org/abs/2408.04392)] [[code](https://github.com/cofe-ai/OIFC)]
- [2024] **Variational Best-of-N Alignment** *ICLR 2025* [[paper](https://arxiv.org/abs/2407.06057)]
- [2024] **Improving Citation Text Generation: Overcoming Limitations in Length Control** [[paper](https://arxiv.org/abs/2407.14997)]
- [2024] **Prompt-Based Length Controlled Generation with Multiple Control Types** [[paper](https://arxiv.org/abs/2406.10278)]
- [2024] **Differentially Private Tabular Data Synthesis using Large Language Models** [[paper](https://arxiv.org/abs/2406.01457)]
- [2024] **Dialogue Action Tokens: Steering Language Models in Goal-Directed Dialogue with a Multi-Turn Planner** [[paper](https://arxiv.org/abs/2406.11978)]
- [2024] **AMBROSIA: A Benchmark for Parsing Ambiguous Questions into Database Queries** [[paper](https://arxiv.org/abs/2406.19073)]
- [2024] **Controllable Text Generation in the Instruction-Tuning Era** [[paper](https://arxiv.org/abs/2405.01490)]
- [2024] **Dynamic Multi-Reward Weighting for Multi-Style Controllable Generation** [[paper](https://arxiv.org/abs/2402.14146)]
- [2024] **A Systematic Review of Data-to-Text NLG** [[paper](https://arxiv.org/abs/2402.08496)]
- [2024] **Supporting Student Decisions on Learning Recommendations: An LLM-Based Chatbot with Knowledge Graph Contextualization for Conversational Explainability and Mentoring** [[paper](https://arxiv.org/abs/2401.08517)]
- [2024] **Dynamically Allocated Interval-Based Generative Linguistic Steganography with Roulette Wheel** [[paper](https://arxiv.org/abs/2401.15656)]

##### 2023

- [2023] **Unlocking Anticipatory Text Generation: A Constrained Approach for Large Language Models Decoding** [[paper](https://arxiv.org/abs/2312.06149)]
- [2023] **Balancing the Style-Content Trade-Off in Sentiment Transfer Using Polarity-Aware Denoising** [[paper](https://arxiv.org/abs/2312.14708)]
- [2023] **A Block Metropolis-Hastings Sampler for Controllable Energy-based Text Generation** [[paper](https://arxiv.org/abs/2312.04510)]
- [2023] **Style Locality for Controllable Generation with kNN Language Models** [[paper](https://arxiv.org/abs/2311.00475)]
- [2023] **PixT3: Pixel-based Table-To-Text Generation** [[paper](https://arxiv.org/abs/2311.09808)]
- [2023] **On the steerability of large language models toward data-driven personas** [[paper](https://arxiv.org/abs/2311.04978)]
- [2023] **Controlled Text Generation for Black-box Language Models via Score-based Progressive Editor** *ACL 2024 Main* [[paper](https://arxiv.org/abs/2311.07430)] [[code](https://github.com/ysw1021/ScoPE)]
- [2023] **A Unified Approach for Text- and Image-guided 4D Scene Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.16854)]
- [2023] **uSee: Unified Speech Enhancement and Editing with Conditional Diffusion Models** [[paper](https://arxiv.org/abs/2310.00900)] [[project](https://muqiaoy.github.io/usee)]
- [2023] **Text Embeddings Reveal (Almost) As Much As Text** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.06816)] [[code](https://github.com/jxmorris12/vec2text)]
- [2023] **BOOST: Harnessing Black-Box Control to Boost Commonsense in LMs' Generation** [[paper](https://arxiv.org/abs/2310.17054)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **Scaling Creative Writing Beyond Story-Centric Data with Attribute-Guided Genre Expansion** [[paper](https://arxiv.org/abs/2608.13947)]
- [2026] **Narrative Keyframing for Generative Creative Writing** [[paper](https://arxiv.org/abs/2608.10337)]
- [2026] **Hidden Threat in Synthetic Data: Covert Targeted Bias Injection through Benign Text** *EMNLP 2026* [[paper](https://arxiv.org/abs/2608.30619)]
- [2026] **From Personas to Plot: Character-Grounded Multi-Agent Story Generation for Long-Form Narratives** [[paper](https://arxiv.org/abs/2607.00918)]
- [2026] **Unintended Effects of Geographic Conditioning in Large Language Models** *ACL 2026* [[paper](https://arxiv.org/abs/2606.18124)]
- [2026] **POLARIS: Guiding Small Models to Write Long Stories** [[paper](https://arxiv.org/abs/2606.04095)]
- [2026] **GraphStory: Collaborative Story Writing through Event-Based Narrative Editing** [[paper](https://arxiv.org/abs/2606.16102)]
- [2026] **Parameter-Efficient Neuroevolution for Diverse LLM Generation: Quality-Diversity Optimization via Prompt Embedding Evolution** [[paper](https://arxiv.org/abs/2605.09781)]
- [2026] **Controllable Narrative Rendering for Enhanced Assisted Writing** [[paper](https://arxiv.org/abs/2607.00009)]
- [2026] **Assessing the Creativity of Large Language Models: Testing, Limits, and New Frontiers** [[paper](https://arxiv.org/abs/2605.13450)]
- [2026] **ks-pret-5m: a 5 million word, 12 million token kashmiri pretraining dataset** [[paper](https://arxiv.org/abs/2604.11066)]
- [2026] **StoryScope: Investigating idiosyncrasies in AI fiction** [[paper](https://arxiv.org/abs/2604.03136)]
- [2026] **R2-Write: Reflection and Revision for Open-Ended Writing with Deep Reasoning** [[paper](https://arxiv.org/abs/2604.03004)]
- [2026] **POEMetric: The Last Stanza of Humanity** [[paper](https://arxiv.org/abs/2604.03695)] [[code](https://github.com/Bingru-Li/POEMetric)]
- [2026] **Min-k Sampling: Decoupling Truncation from Temperature Scaling via Relative Logit Dynamics** *ACL 2026* [[paper](https://arxiv.org/abs/2604.11012)]
- [2026] **Metaphors We Compute By: A Computational Audit of Cultural Translation vs. Thinking in LLMs** [[paper](https://arxiv.org/abs/2604.04732)]
- [2026] **Lighting Up or Dimming Down? Exploring Dark Patterns of LLMs in Co-Creativity** [[paper](https://arxiv.org/abs/2604.04735)]
- [2026] **Calibrated Surprise: An Information-Theoretic Account of Creative Quality** [[paper](https://arxiv.org/abs/2604.26269)]
- [2026] **Writer-R1: Enhancing Generative Writing in LLMs via Memory-augmented Replay Policy Optimization** [[paper](https://arxiv.org/abs/2603.15061)]
- [2026] **Pingala: Prosody-Aware Decoding for Sanskrit Poetry Generation** [[paper](https://arxiv.org/abs/2603.24413)]
- [2026] **Can ChatGPT Really Understand Modern Chinese Poetry?** [[paper](https://arxiv.org/abs/2603.20851)]
- [2026] **BiT-MCTS: A Theme-based Bidirectional MCTS Approach to Chinese Fiction Generation** [[paper](https://arxiv.org/abs/2603.14410)]
- [2026] **The Judge Who Never Admits: Hidden Shortcuts in LLM-based Evaluation** [[paper](https://arxiv.org/abs/2602.07996)]
- [2026] **Outcome Accuracy is Not Enough: Aligning the Reasoning Process of Reward Models** [[paper](https://arxiv.org/abs/2602.04649)]
- [2026] **LLMs Exhibit Significantly Lower Uncertainty in Creative Writing Than Professional Writers** [[paper](https://arxiv.org/abs/2602.16162)]
- [2026] **Improving Sampling for Masked Diffusion Models via Information Gain** [[paper](https://arxiv.org/abs/2602.18176)] [[code](https://github.com/yks23/Information-Gain-Sampler)]
- [2026] **DeltaKV: Residual-Based KV Cache Compression via Long-Range Similarity** [[paper](https://arxiv.org/abs/2602.08005)] [[code](https://github.com/CURRENTF/Sparse-vLLM)]
- [2026] **Alternating Reinforcement Learning for Rubric-Based Reward Modeling in Non-Verifiable LLM Post-Training** [[paper](https://arxiv.org/abs/2602.01511)]
- [2026] **What's the plan? Metrics for implicit planning in LLMs and their application to rhyme generation and question answering** *ICLR 2026* [[paper](https://arxiv.org/abs/2601.20164)]
- [2026] **TreeWriter: AI-Assisted Hierarchical Planning and Writing for Long-Form Documents** [[paper](https://arxiv.org/abs/2601.12740)]
- [2026] **TF3-RO-50M: Training Compact Romanian Language Models from Scratch on Synthetic Moral Microfiction** [[paper](https://arxiv.org/abs/2601.10410)]
- [2026] **Narrative Theory-Driven LLM Methods for Automatic Story Generation and Understanding: A Survey** [[paper](https://arxiv.org/abs/2602.15851)]
- [2026] **Codified Foreshadowing-Payoff Text Generation** [[paper](https://arxiv.org/abs/2601.07033)]
- [2026] **Can Good Writing Be Generative? Expert-Level AI Writing Emerges through Fine-Tuning on High-Quality Books** [[paper](https://arxiv.org/abs/2601.18353)]
- [2026] **Balancing Detectability and Fluency in Neural Text Generation via Reinforcement-Guided Watermark Placement** *Frontiers in Applied Physics and Mathematics* [[paper](https://doi.org/10.71465/fapm630)]

##### 2025

- [2025] **Integrating Cognitive, Symbolic, and Neural Approaches to Story Generation: A Review on the METATRON Framework** *Mathematics* [[paper](https://doi.org/10.3390/math13233885)]
- [2025] **DramaBench: A Six-Dimensional Evaluation Framework for Drama Script Continuation** [[paper](https://arxiv.org/abs/2512.19012)]
- [2025] **Capturing Classic Authorial Style in Long-Form Story Generation with GRPO Fine-Tuning** [[paper](https://arxiv.org/abs/2512.05747)]
- [2025] **Writing in Symbiosis: Mapping Human Creative Agency in the AI Era** [[paper](https://arxiv.org/abs/2512.13697)]
- [2025] **LiteraryTaste: A Preference Dataset for Creative Writing Personalization** [[paper](https://arxiv.org/abs/2511.09310)]
- [2025] **FNet-GPT: Fourier-based lightweight transformer for emotion-aware text generation using GPT** *Future Technology* [[paper](https://doi.org/10.55670/fpll.futech.4.4.12)]
- [2025] **Verbalized Sampling: How to Mitigate Mode Collapse and Unlock LLM Diversity** [[paper](https://arxiv.org/abs/2510.01171)]
- [2025] **Engagement Undermines Safety: How Stereotypes and Toxicity Shape Humor in Language Models** [[paper](https://arxiv.org/abs/2510.18454)]
- [2025] **DiffuStory: Improving text diffusion models for creative story generation with contrastive learning and decoder-decoder Transformers** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.130154)]
- [2025] **Deep Associations, High Creativity: A Simple yet Effective Metric for Evaluating Large Language Models** [[paper](https://arxiv.org/abs/2510.12110)]
- [2025] **Curiosity-Driven LLM-as-a-judge for Personalized Creative Judgment** [[paper](https://arxiv.org/abs/2510.05135)]
- [2025] **CreativityPrism: A Cross-Domain Evaluation Framework for Large Language Model Creativity** [[paper](https://arxiv.org/abs/2510.20091)]
- [2025] **Capabilities and Evaluation Biases of Large Language Models in Classical Chinese Poetry Generation: A Case Study on Tang Poetry** [[paper](https://arxiv.org/abs/2510.15313)]
- [2025] **COIG-Writer: A High-Quality Dataset for Chinese Creative Writing with Thought Processes** [[paper](https://arxiv.org/abs/2510.14763)]
- [2025] **Vistoria: A Multimodal System to Support Fictional Story Writing through Instrumental Text-Image Co-Editing** [[paper](https://arxiv.org/abs/2509.13646)]
- [2025] **Top-H Decoding: Adapting the Creativity and Coherence with Bounded Entropy in Text Generation** [[paper](https://arxiv.org/abs/2509.02510)] [[code](https://github.com/ErfanBaghaei/Top-H-Decoding)]
- [2025] **The Silent Judge: Unacknowledged Shortcut Bias in LLM-as-a-Judge** [[paper](https://arxiv.org/abs/2509.26072)]
- [2025] **The Geometry of Creative Variability: How Credal Sets Expose Calibration Gaps in Language Models** [[paper](https://arxiv.org/abs/2509.23088)]
- [2025] **Task-Dependent Evaluation of LLM Output Homogenization: A Taxonomy-Guided Framework** [[paper](https://arxiv.org/abs/2509.21267)]
- [2025] **Rethinking Creativity Evaluation: A Critical Analysis of Existing Creativity Evaluations** [[paper](https://arxiv.org/abs/2508.05470)]
- [2025] **RLMR: Reinforcement Learning with Mixed Rewards for Creative Writing** [[paper](https://arxiv.org/abs/2508.18642)]
- [2025] **Personality Matters: User Traits Predict LLM Preferences in Multi-Turn Collaborative Tasks** [[paper](https://arxiv.org/abs/2508.21628)]
- [2025] **Specification Self-Correction: Mitigating In-Context Reward Hacking Through Test-Time Refinement** [[paper](https://arxiv.org/abs/2507.18742)] [[code](https://github.com/vicgalle/specification-self-correction)]
- [2025] **A Survey of Pun Generation: Datasets, Evaluations and Methodologies** [[paper](https://arxiv.org/abs/2507.04793)]
- [2025] **StoryWriter: A Multi-Agent Framework for Long Story Generation** [[paper](https://arxiv.org/abs/2506.16445)]
- [2025] **STORYTELLER: An Enhanced Plot-Planning Framework for Coherent and Cohesive Story Generation** [[paper](https://arxiv.org/abs/2506.02347)]
- [2025] **Chandomitra: Towards Generating Structured Sanskrit Poetry from Natural Language Inputs** [[paper](https://arxiv.org/abs/2506.00815)]
- [2025] **Cat and Mouse -- Can Fake Text Generation Outpace Detector Systems?** [[paper](https://arxiv.org/abs/2506.21274)]
- [2025] **Advancing Decoding Strategies: Enhancements in Locally Typical Sampling for LLMs** [[paper](https://arxiv.org/abs/2506.05387)]
- [2025] **SIMPLEMIX: Frustratingly Simple Mixing of Off- and On-policy Data in Language Model Preference Learning** *ICML 2025* [[paper](https://arxiv.org/abs/2505.02363)]
- [2025] **Iterative Resolution of Prompt Ambiguities Using a Progressive Cutting-Search Approach** [[paper](https://arxiv.org/abs/2505.02952)]
- [2025] **Eye of Judgement: Dissecting the Evaluation of Russian-speaking LLMs with POLLUX** [[paper](https://arxiv.org/abs/2505.24616)]
- [2025] **Diverse, not Short: A Length-Controlled Data Selection Strategy for Improving Response Diversity of Language Models** [[paper](https://arxiv.org/abs/2505.16245)]
- [2025] **ParaPO: Aligning Language Models to Reduce Verbatim Reproduction of Pre-training Data** [[paper](https://arxiv.org/abs/2504.14452)]
- [2025] **Base Models Beat Aligned Models at Randomness and Creativity** [[paper](https://arxiv.org/abs/2505.00047)]
- [2025] **Phraselette: A Poet's Procedural Palette** [[paper](https://arxiv.org/abs/2503.06335)]
- [2025] **Where is my Glass Slipper? AI, Poetry and Art** [[paper](https://arxiv.org/abs/2503.05781)]
- [2025] **Thinking Outside the (Gray) Box: A Context-Based Score for Assessing Value and Originality in Neural Text Generation** [[paper](https://arxiv.org/abs/2502.13207)]
- [2025] **The Power of Personality: A Human Simulation Perspective to Investigate Large Language Model Agents** [[paper](https://arxiv.org/abs/2502.20859)]
- [2025] **LLMs Reproduce Stereotypes of Sexual and Gender Minorities** [[paper](https://arxiv.org/abs/2501.05926)]

##### 2024

- [2024] **MLD-EA: Check and Complete Narrative Coherence by Introducing Emotions and Actions** [[paper](https://arxiv.org/abs/2412.02897)]
- [2024] **Blending the Powers of BERT and Neural Style Transfer for Artistic Text Generation in Poetry** [[paper](https://doi.org/10.1109/ihcsp63227.2024.10960137)]
- [2024] **Richer Output for Richer Countries: Uncovering Geographical Disparities in Generated Stories and Travel Recommendations** [[paper](https://arxiv.org/abs/2411.07320)]
- [2024] **Beemo: Benchmark of Expert-edited Machine-generated Outputs** [[paper](https://arxiv.org/abs/2411.04032)]
- [2024] **Bayesian Calibration of Win Rate Estimation with LLM Evaluators** [[paper](https://arxiv.org/abs/2411.04424)]
- [2024] **"It was 80% me, 20% AI": Seeking Authenticity in Co-Writing with Large Language Models** [[paper](https://arxiv.org/abs/2411.13032)]
- [2024] **Which LLMs are Difficult to Detect? A Detailed Analysis of Potential Factors Contributing to Difficulties in LLM Text Detection** *NeurIPS 2024 - Safe Generative AI Workshop* [[paper](https://arxiv.org/abs/2410.14875)]
- [2024] **PositionID: LLMs can Control Lengths, Copy and Paste with Explicit Positional Awareness** [[paper](https://arxiv.org/abs/2410.07035)]
- [2024] **Collective Critics for Creative Story Generation** [[paper](https://arxiv.org/abs/2410.02428)]
- [2024] **A Neural Network-Based Language Model for Automatic Poem Generation** [[paper](https://doi.org/10.1109/iccp63557.2024.10792998)]
- [2024] **Small Language Models can Outperform Humans in Short Creative Writing: A Study Comparing SLMs with Humans and LLMs** *COLING 2025* [[paper](https://arxiv.org/abs/2409.11547)]
- [2024] **LongGenBench: Benchmarking Long-Form Generation in Long Context LLMs** [[paper](https://arxiv.org/abs/2409.02076)]
- [2024] **LLM-based multi-agent poetry generation in non-cooperative environments** [[paper](https://arxiv.org/abs/2409.03659)]
- [2024] **Drama Engine: A Framework for Narrative Agents** [[paper](https://arxiv.org/abs/2408.11574)]
- [2024] **Creating Arabic LLM Prompts at Scale** [[paper](https://arxiv.org/abs/2408.05882)]
- [2024] **Self-Cognition in Large Language Models: An Exploratory Study** *ICML 2024 Large Language Models and Cognition Workshop* [[paper](https://arxiv.org/abs/2407.01505)]
- [2024] **Pron vs Prompt: Can Large Language Models already Challenge a World-Class Fiction Author at Creative Text Writing?** [[paper](https://arxiv.org/abs/2407.01119)]
- [2024] **Exploring Bengali Religious Dialect Biases in Large Language Models with Evaluation Perspectives** [[paper](https://arxiv.org/abs/2407.18376)]
- [2024] **Write Summary Step-by-Step: A Pilot Study of Stepwise Summarization** [[paper](https://arxiv.org/abs/2406.05361)]
- [2024] **The Unlikely Duel: Evaluating Creative Writing in LLMs through a Unique Scenario** [[paper](https://arxiv.org/abs/2406.15891)]
- [2024] **The GPT-WritingPrompts Dataset: A Comparative Analysis of Character Portrayal in Short Stories** [[paper](https://arxiv.org/abs/2406.16767)] [[code](https://github.com/KristinHuangg/gpt-writing-prompts)]
- [2024] **Human-AI Collaborative Taxonomy Construction: A Case Study in Profession-Specific Writing Assistants** [[paper](https://arxiv.org/abs/2406.18675)]
- [2024] **Guiding and Diversifying LLM-Based Story Generation via Answer Set Programming** [[paper](https://arxiv.org/abs/2406.00554)]
- [2024] **GPT Czech Poet: Generation of Czech Poetic Strophes with Language Models** [[paper](https://arxiv.org/abs/2407.12790)]
- [2024] **Evaluating Diversity in Automatic Poetry Generation** [[paper](https://arxiv.org/abs/2406.15267)]
- [2024] **Dynamic Data Mixing Maximizes Instruction Tuning for Mixture-of-Experts** [[paper](https://arxiv.org/abs/2406.11256)] [[code](https://github.com/Spico197/MoE-SFT)]
- [2024] **Text Generation: A Systematic Literature Review of Tasks, Evaluation, and Challenges** [[paper](https://arxiv.org/abs/2405.15604)]
- [2024] **SARD: A Human-AI Collaborative Story Generation** [[paper](https://arxiv.org/abs/2403.01575)]
- [2024] **NewsBench: A Systematic Evaluation Framework for Assessing Editorial Capabilities of Large Language Models in Chinese Journalism** [[paper](https://arxiv.org/abs/2403.00862)]
- [2024] **Vietnamese Poem Generation &amp; The Prospect Of Cross-Language Poem-To-Poem Translation** [[paper](https://arxiv.org/abs/2401.01078)]
- [2024] **Story Generation Using GAN, RNN and LSTM** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-56700-1_16)]
- [2024] **SYNERGY OF INFORMATION TECHNOLOGIES AND NEURAL NETWORKS FOR TEXT CONTENT GENERATION** *Scientific notes of Taurida National V I Vernadsky University Series Technical Sciences* [[paper](https://doi.org/10.32782/2663-5941/2024.6.2/02)]
- [2024] **Raidar: geneRative AI Detection viA Rewriting** [[paper](https://arxiv.org/abs/2401.12970)]
- [2024] **Neural Poetry as a Battle of Poetic Languages** *Slovo ru Baltic accent* [[paper](https://dx.doi.org/10.5922/2225-5346-2024-2-7)]
- [2024] **CharPoet: A Chinese Classical Poetry Generation System Based on Token-free LLM** [[paper](https://arxiv.org/abs/2401.03512)]
- [2024] **A Systematic Literature Review on Text Generation using Deep Neural Networks** *International Journal For Multidisciplinary Research* [[paper](https://dx.doi.org/10.36948/ijfmr.2024.v06i01.11921)]

##### 2023

- [2023] **Text Generation: Using Markov Model & LSTM Networks to Generate Realistic Text** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2023.57601)]
- [2023] **TPPoet: Transformer-Based Persian Poem Generation using Minimal Data and Advanced Decoding Techniques** [[paper](https://arxiv.org/abs/2312.02125)]
- [2023] **Robust Knowledge Extraction from Large Language Models using Social Choice Theory** [[paper](https://arxiv.org/abs/2312.14877)]
- [2023] **Tailoring with Targeted Precision: Edit-Based Agents for Open-Domain Procedure Customization** [[paper](https://arxiv.org/abs/2311.09510)]
- [2023] **Inspo: Writing with Crowds Alongside AI** [[paper](https://arxiv.org/abs/2311.16521)]
- [2023] **Evaluating Large Language Model Creativity from a Literary Perspective** [[paper](https://arxiv.org/abs/2312.03746)]
- [2023] **Comprehensive Assessment of Toxicity in ChatGPT** [[paper](https://arxiv.org/abs/2311.14685)]
- [2023] **Quality-Diversity through AI Feedback** [[paper](https://arxiv.org/abs/2310.13032)]
- [2023] **Exploring the Reliability of Large Language Models as Customized Evaluators for Diverse NLP Tasks** [[paper](https://arxiv.org/abs/2310.19740)]
- [2023] **Erato: Automatizing Poetry Evaluation** [[paper](https://arxiv.org/abs/2310.20326)]
- [2023] **Dynamics of Instruction Fine-Tuning for Chinese Large Language Models** [[paper](https://arxiv.org/abs/2310.19651)]
- [2023] **A Confederacy of Models: a Comprehensive Evaluation of LLMs on Creative Writing** [[paper](https://arxiv.org/abs/2310.08433)]
- [2023] **Creativity Support in the Age of Large Language Models: An Empirical Study Involving Emerging Writers** [[paper](https://arxiv.org/abs/2309.12570)]
- [2023] **Art or Artifice? Large Language Models and the False Promise of Creativity** [[paper](https://arxiv.org/abs/2309.14556)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **LOOMSUM:Weaving Quantitative and Narrative Evidence for Faithful Long Text-Table Summarization** [[paper](https://arxiv.org/abs/2609.00241)]
- [2026] **Aïra: Rethinking AI Research Assistants for Interdisciplinary Science** [[paper](https://arxiv.org/abs/2607.12736)]
- [2026] **BioACE: An Automated Framework for Biomedical Answer and Citation Evaluations** [[paper](https://arxiv.org/abs/2602.04982)] [[code](https://github.com/deepaknlp/BioACE)]
- [2026] **Disco-RAG: Discourse-Aware Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2601.04377)]

##### 2025

- [2025] **Subjective Question Generation and Answer Evaluation using NLP** [[paper](https://arxiv.org/abs/2512.17289)]
- [2025] **Progress Ratio Embeddings: An Impatience Signal for Robust Length Control in Neural Text Generation** *HAL (Le Centre pour la Communication Scientifique Directe)* [[paper](https://arxiv.org/abs/2512.06938)]
- [2025] **LongCodeZip: Compress Long Context for Code Language Models** [[paper](https://arxiv.org/abs/2510.00446)]
- [2025] **Abstractive text summarization with convolutional neural network (CNN) and fuzzy rule generation model** *International Journal of Information Technology* [[paper](https://doi.org/10.1007/s41870-025-02824-2)]
- [2025] **Localizing Malicious Outputs from CodeLLM** *EMNLP 2025 Findings* [[paper](https://arxiv.org/abs/2509.17070)]
- [2025] **AraHalluEval: A Fine-grained Hallucination Evaluation Framework for Arabic LLMs** [[paper](https://arxiv.org/abs/2509.04656)] [[code](https://github.com/aishaalansari57/AraHalluEval)]
- [2025] **Robust Symbolic Reasoning for Visual Narratives via Hierarchical and Semantically Normalized Knowledge Graphs** [[paper](https://arxiv.org/abs/2508.14941)]
- [2025] **Natural Language Generation** *Oxford Research Encyclopedia of Linguistics* [[paper](https://doi.org/10.1093/acrefore/9780199384655.013.896)]
- [2025] **Dynamic Lexical Encoding for Neural Intelligent Language Understanding: Advancing Language Inception and Reconstruction via Deep Learning Paradigms** [[paper](https://doi.org/10.1109/indiscon66021.2025.11253898)]
- [2025] **Chain-of-Descriptions: Improving Code LLMs for VHDL Code Generation and Summarization** [[paper](https://arxiv.org/abs/2507.12308)]
- [2025] **DiscoSum: Discourse-aware News Summarization** [[paper](https://arxiv.org/abs/2506.06930)]
- [2025] **Controlling Summarization Length Through EOS Token Weighting** [[paper](https://arxiv.org/abs/2506.05017)]
- [2025] **Power-Law Decay Loss for Large Language Model Finetuning: A Theory Perspective** [[paper](https://arxiv.org/abs/2505.16900)]
- [2025] **NexusSum: Hierarchical LLM Agents for Long-Form Narrative Summarization** [[paper](https://arxiv.org/abs/2505.24575)]
- [2025] **Improving the Calibration of Confidence Scores in Text Generation Using the Output Distribution's Characteristics** [[paper](https://arxiv.org/abs/2506.00637)]
- [2025] **Hallucination Detection in LLMs with Topological Divergence on Attention Graphs** [[paper](https://arxiv.org/abs/2504.10063)]
- [2025] **Align to Structure: Aligning Large Language Models with Structural Information** [[paper](https://arxiv.org/abs/2504.03622)] [[code](https://github.com/minnesotanlp/struct_align)]
- [2025] **Evaluating LLMs' Assessment of Mixed-Context Hallucination Through the Lens of Summarization** [[paper](https://arxiv.org/abs/2503.01670)]
- [2025] **Applications of Large Language Model Reasoning in Feature Generation** [[paper](https://arxiv.org/abs/2503.11989)]
- [2025] **Smoothing Out Hallucinations: Mitigating LLM Hallucination with Smoothed Knowledge Distillation** [[paper](https://arxiv.org/abs/2502.11306)]
- [2025] **SCOPE: A Self-supervised Framework for Improving Faithfulness in Conditional Text Generation** [[paper](https://arxiv.org/abs/2502.13674)]
- [2025] **Evaluating Text Style Transfer Evaluation: Are There Any Reliable Metrics?** *NAACL SRW 2025* [[paper](https://arxiv.org/abs/2502.04718)]
- [2025] **Text Summarization Using Natural Language Processing** *Journal of Electrical Systems* [[paper](https://doi.org/10.52783/jes.8095)]
- [2025] **How to Select Datapoints for Efficient Human Evaluation of NLG Models?** [[paper](https://arxiv.org/abs/2501.18251)]
- [2025] **Brain-model neural similarity reveals abstractive summarization performance** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-84530-w)]
- [2025] **Automated Cricket Analytics for Player Classification and Commentary Generation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3598037)]

##### 2024

- [2024] **Automatic Text Summarization Using Sequence to Sequence Model and Recurrent Neural Network** *Computación y Sistemas* [[paper](https://doi.org/10.13053/cys-28-4-5289)]
- [2024] **AutoPatent: A Multi-Agent Framework for Automatic Patent Generation** [[paper](https://arxiv.org/abs/2412.09796)] [[code](https://github.com/QiYao-Wang/AutoPatent)]
- [2024] **Extractive Multi-Document Summarization Using Transformer-Based Neural Networks** [[paper](https://doi.org/10.1109/icses63445.2024.10763280)]
- [2024] **Building A Coding Assistant via the Retrieval-Augmented Language Model** [[paper](https://arxiv.org/abs/2410.16229)]
- [2024] **HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models** [[paper](https://arxiv.org/abs/2409.16191)] [[code](https://github.com/Quehry/HelloBench)]
- [2024] **Advancements in Neural Network-Based Text Summarization Techniques** [[paper](https://doi.org/10.1109/iicccs61609.2024.10763783)]
- [2024] **Comparative Study of Deep Neural Language Models for Text Generation** [[paper](https://doi.org/10.1109/iccubea61740.2024.10774930)]
- [2024] **An overview of current issues in automatic text summarization of natural language using artificial intelligence methods** *Technology audit and production reserves* [[paper](https://doi.org/10.15587/2706-5448.2024.309472)]
- [2024] **Next-Generation Database Interfaces: A Survey of LLM-based Text-to-SQL** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.08426)]
- [2024] **Unveiling the Achilles' Heel of NLG Evaluators: A Unified Adversarial Framework Driven by Large Language Models** [[paper](https://arxiv.org/abs/2405.14646)]
- [2024] **Improving Long Text Understanding with Knowledge Distilled from Summarization Model** [[paper](https://arxiv.org/abs/2405.04955)]
- [2024] **KnowHalu: Hallucination Detection via Multi-Form Knowledge Based Factual Checking** [[paper](https://arxiv.org/abs/2404.02935)]
- [2024] **On the Benefits of Fine-Grained Loss Truncation: A Case Study on Factuality in Summarization** [[paper](https://arxiv.org/abs/2403.05788)] [[code](https://github.com/yale-nlp/fine-grained-lt)]
- [2024] **FENICE: Factuality Evaluation of summarization based on Natural language Inference and Claim Extraction** [[paper](https://arxiv.org/abs/2403.02270)] [[code](https://github.com/Babelscape/FENICE)]
- [2024] **TofuEval: Evaluating Hallucinations of LLMs on Topic-Focused Dialogue Summarization** [[paper](https://arxiv.org/abs/2402.13249)]
- [2024] **Text summarization using modified generative adversarial network1** *Journal of Intelligent & Fuzzy Systems* [[paper](https://doi.org/10.3233/jifs-236813)]
- [2024] **How Much Annotation is Needed to Compare Summarization Models?** [[paper](https://arxiv.org/abs/2402.18756)]
- [2024] **FinBen: A Holistic Financial Benchmark for Large Language Models** [[paper](https://arxiv.org/abs/2402.12659)] [[code](https://github.com/The-FinAI/PIXIU)]
- [2024] **MSG-ATS: Multi-Level Semantic Graph for Arabic Text Summarization** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3441489)]
- [2024] **Image Caption Generation using Deep Learning For Video Summarization Applications** *International Journal of Advanced Computer Science and Applications* [[paper](https://dx.doi.org/10.14569/ijacsa.2024.0150155)]
- [2024] **Enhancing extractive text summarization using natural language processing with an optimal deep learning model** *AIMS Mathematics* [[paper](https://doi.org/10.3934/math.2024616)]
- [2024] **Beyond Sparse Rewards: Enhancing Reinforcement Learning with Language Model Critique in Text Generation** [[paper](https://arxiv.org/abs/2401.07382)]
- [2024] **A knowledge-graph based text summarization scheme for mobile edge computing** *Journal of Cloud Computing Advances Systems and Applications* [[paper](https://doi.org/10.1186/s13677-023-00585-6)]

##### 2023

- [2023] **Breaking the Silence: the Threats of Using LLMs in Software Engineering** [[paper](https://arxiv.org/abs/2312.08055)]
- [2023] **The Eval4NLP 2023 Shared Task on Prompting Large Language Models as Explainable Metrics** [[paper](https://arxiv.org/abs/2310.19792)]
- [2023] **Generating Summaries with Controllable Readability Levels** [[paper](https://arxiv.org/abs/2310.10623)]
- [2023] **Controllable Multi-document Summarization: Coverage &amp; Coherence Intuitive Policy with Large Language Model Based Rewards** [[paper](https://arxiv.org/abs/2310.03473)]
- [2023] **Automatic and Human-AI Interactive Text Generation** *ACL 2024* [[paper](https://arxiv.org/abs/2310.03878)]
- [2023] **Hallucination Reduction in Long Input Text Summarization** [[paper](https://arxiv.org/abs/2309.16781)]
- [2023] **Finding Pragmatic Differences Between Disciplines** *NAACL 2021* [[paper](https://arxiv.org/abs/2310.00204)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **HyperStyler: Low-resource Authorship Style Transfer via Context-aware Style Navigation and Hypernetworks** [[paper](https://arxiv.org/abs/2609.02772)]
- [2026] **Unfolding Scientific Papers into Multi-Turn Generation Trajectories for Continued Pre-Training** [[paper](https://arxiv.org/abs/2608.25826)]
- [2026] **The Assistant Erased You: Measuring Loss of Authorship Signals in AI-Mediated Communication** [[paper](https://arxiv.org/abs/2608.00926)]
- [2026] **AraDetox: A Multi-Dialect Arabic Detoxification Dataset** [[paper](https://arxiv.org/abs/2608.22894)] [[code](https://github.com/ArabicNLP-UK/AraDetox)]
- [2026] **Against Political Polarization: A Unified Framework for Tracing Evolving Political Ideologies on Social Media** [[paper](https://arxiv.org/abs/2608.17987)]
- [2026] **Trust Before Fusion: QIMG-7 and Source-Aware Resolution for Polluted Multimodal RAG** [[paper](https://arxiv.org/abs/2607.10798)] [[code](https://github.com/SaadElDine/Trust_Before_Fusion)]
- [2026] **Prosody-driven Jailbreaks in Audio LLMs: A Controlled Study and Mechanistic Analysis** [[paper](https://arxiv.org/abs/2607.26541)]
- [2026] **Non-Parametric Machine Text Detection via Multi-View Gaussian Processes** [[paper](https://arxiv.org/abs/2606.14060)]
- [2026] **Constrained Paraphrase Consistency for LLM Hallucination Detection** [[paper](https://arxiv.org/abs/2606.08158)]
- [2026] **StoryLens: Preference-Aligned Story Rewriting via Context-Aware Narrative Enrichment** [[paper](https://arxiv.org/abs/2605.28073)]
- [2026] **Please Make it Sound like Human: Encoder-Decoder vs. Decoder-Only Transformers for AI-to-Human Text Style Transfer** [[paper](https://arxiv.org/abs/2604.11687)]
- [2026] **Discourse Coherence and Response-Guided Context Rewriting for Multi-Party Dialogue Generation** [[paper](https://arxiv.org/abs/2604.06784)]
- [2026] **The Art That Poses Back: Assessing AI Pastiches after Contemporary Artworks** [[paper](https://arxiv.org/abs/2603.06324)]
- [2026] **AuthorMix: Modular Authorship Style Transfer via Layer-wise Adapter Mixing** [[paper](https://arxiv.org/abs/2603.23069)]
- [2026] **Activation Steering via Generative Causal Mediation** [[paper](https://arxiv.org/abs/2602.16080)]
- [2026] **Unsupervised Text Style Transfer for Controllable Intensity** [[paper](https://arxiv.org/abs/2601.01060)]
- [2026] **Text Detoxification in isiXhosa and Yorùbá: A Cross-Lingual Machine Learning Approach for Low-Resource African Languages** [[paper](https://arxiv.org/abs/2601.05624)]
- [2026] **Style Transfer as Bias Mitigation: Diffusion Models for Synthetic Mental Health Text for Arabic** [[paper](https://arxiv.org/abs/2601.14124)]
- [2026] **ShortCoder: Knowledge-Augmented Syntax Optimization for Token-Efficient Code Generation** [[paper](https://arxiv.org/abs/2601.09703)]

##### 2025

- [2025] **One-shot Style Transfer LLM log-probabilities for Authorship Attribution and Verification** [[paper](https://arxiv.org/abs/2510.13302)]
- [2025] **CLEAR: A Comprehensive Linguistic Evaluation of Argument Rewriting by Large Language Models** *EMNLP 2025 Findings* [[paper](https://arxiv.org/abs/2509.15027)]
- [2025] **MahaParaphrase: A Marathi Paraphrase Detection Corpus and BERT-based Models** [[paper](https://arxiv.org/abs/2508.17444)] [[code](https://github.com/l3cube-pune/MarathiNLP)]
- [2025] **Voice Conversion for Lombard Speaking Style with Implicit and Explicit Acoustic Feature Conditioning** [[paper](https://arxiv.org/abs/2507.09310)]
- [2025] **TexGS-VolVis: Expressive Scene Editing for Volume Visualization via Textured Gaussian Splatting** [[paper](https://arxiv.org/abs/2507.13586)]
- [2025] **Learning Text Styles: A Study on Transfer, Attribution, and Verification** [[paper](https://arxiv.org/abs/2507.16530)]
- [2025] **Evaluating Text Style Transfer: A Nine-Language Benchmark for Text Detoxification** [[paper](https://arxiv.org/abs/2507.15557)]
- [2025] **AutoRAG-LoRA: Hallucination-Triggered Knowledge Retuning via Lightweight Adapters** [[paper](https://arxiv.org/abs/2507.10586)]
- [2025] **Steering Large Language Models with Register Analysis for Arbitrary Style Transfer** [[paper](https://arxiv.org/abs/2505.00679)]
- [2025] **Neural Style Transfer for Synthesising a Dataset of Ancient Egyptian Hieroglyphs** [[paper](https://arxiv.org/abs/2504.02163)]
- [2025] **ReverBERT: A State Space Model for Efficient Text-Driven Speech Style Transfer** [[paper](https://arxiv.org/abs/2503.20992)]
- [2025] **Enhancing Retrieval for ESGLLM via ESG-CID -- A Disclosure Content Index Finetuning Dataset for Mapping GRI and ESRS** [[paper](https://arxiv.org/abs/2503.10674)] [[project](https://huggingface.co/datasets/airefinery/esg_cid_retrieval)]
- [2025] **Dr Genre: Reinforcement Learning from Decoupled LLM Feedback for Generic Text Rewriting** [[paper](https://arxiv.org/abs/2503.06781)]
- [2025] **mStyleDistance: Multilingual Style Embeddings and their Evaluation** [[paper](https://arxiv.org/abs/2502.15168)] [[project](https://huggingface.co/StyleDistance/mstyledistance)]
- [2025] **Mind the Style Gap: Meta-Evaluation of Style and Attribute Transfer Metrics** *EMNLP Findings 2025* [[paper](https://arxiv.org/abs/2502.15022)]
- [2025] **LLMs can be easily Confused by Instructional Distractions** [[paper](https://arxiv.org/abs/2502.04362)]
- [2025] **Exploring Rewriting Approaches for Different Conversational Tasks** [[paper](https://arxiv.org/abs/2502.18860)]
- [2025] **Beyond Profile: From Surface-Level Facts to Deep Persona Simulation in LLMs** [[paper](https://arxiv.org/abs/2502.12988)]
- [2025] **StAyaL | Multilingual Style Transfer** [[paper](https://arxiv.org/abs/2501.11639)]
- [2025] **Predicting Compact Phrasal Rewrites with Large Language Models for ASR Post Editing** [[paper](https://arxiv.org/abs/2501.13831)]
- [2025] **Improving Image Captioning by Mimicking Human Reformulation Feedback at Inference-time** [[paper](https://arxiv.org/abs/2501.04513)]
- [2025] **Exploring the Power of Generative Adversarial Networks (GANs) for Image Generation: A Case Study on the MNIST Dataset** *International Journal of Advances in Engineering and Management* [[paper](https://doi.org/10.35629/5252-07012146)]

##### 2024

- [2024] **Multilingual and Explainable Text Detoxification with Parallel Corpora** [[paper](https://arxiv.org/abs/2412.11691)]
- [2024] **On the Way to LLM Personalization: Learning to Remember User Conversations** [[paper](https://arxiv.org/abs/2411.13405)]
- [2024] **Interleaved Scene Graphs for Interleaved Text-and-Image Generation Assessment** [[paper](https://arxiv.org/abs/2411.17188)]
- [2024] **Learning from Response not Preference: A Stackelberg Approach for LLM Detoxification using Non-parallel Data** [[paper](https://arxiv.org/abs/2410.20298)] [[code](https://github.com/XXXinhong/Detoxification_LLM)]
- [2024] **Attacking Misinformation Detection Using Adversarial Examples Generated by Language Models** *EMNLP 2025* [[paper](https://arxiv.org/abs/2410.20940)]
- [2024] **An Active Learning Framework for Inclusive Generation by Large Language Models** [[paper](https://arxiv.org/abs/2410.13641)]
- [2024] **GTSinger: A Global Multi-Technique Singing Corpus with Realistic Music Scores for All Singing Tasks** [[paper](https://arxiv.org/abs/2409.13832)] [[code](https://github.com/AaronZ345/GTSinger)] [[project](http://aaronz345.github.io/GTSingerDemo/)]
- [2024] **REFFLY: Melody-Constrained Lyrics Editing Model** [[paper](https://arxiv.org/abs/2409.00292)]
- [2024] **Text Style Transfer: An Introductory Overview** [[paper](https://arxiv.org/abs/2407.14822)]
- [2024] **SETTP: Style Extraction and Tunable Inference via Dual-level Transferable Prompt Learning** [[paper](https://arxiv.org/abs/2407.15556)]
- [2024] **Change My Frame: Reframing in the Wild in r/ChangeMyView** [[paper](https://arxiv.org/abs/2407.02637)]
- [2024] **A Survey of Text Style Transfer: Applications and Ethical Implications** [[paper](https://arxiv.org/abs/2407.16737)]
- [2024] **Style Transfer with Multi-iteration Preference Optimization** [[paper](https://arxiv.org/abs/2406.11581)]
- [2024] **Style Mixture of Experts for Expressive Text-To-Speech Synthesis** [[paper](https://arxiv.org/abs/2406.03637)]
- [2024] **Formality Style Transfer in Persian** [[paper](https://arxiv.org/abs/2406.00867)]
- [2024] **SeamlessExpressiveLM: Speech Language Model for Expressive Speech-to-Speech Translation with Chain-of-Thought** [[paper](https://arxiv.org/abs/2405.20410)]
- [2024] **Multilingual Text Style Transfer: Datasets &amp; Models for Indian Languages** [[paper](https://arxiv.org/abs/2405.20805)]
- [2024] **WordDecipher: Enhancing Digital Workspace Communication with Explainable AI for Non-native English Speakers** [[paper](https://arxiv.org/abs/2404.07005)]
- [2024] **SLPL SHROOM at SemEval2024 Task 06: A comprehensive study on models ability to detect hallucination** [[paper](https://arxiv.org/abs/2404.04845)]
- [2024] **MultiParaDetox: Extending Text Detoxification with Parallel Data to New Languages** [[paper](https://arxiv.org/abs/2404.02037)]
- [2024] **LMStyle Benchmark: Evaluating Text Style Transfer for Chatbots** [[paper](https://arxiv.org/abs/2403.08943)]
- [2024] **Authorship Style Transfer with Policy Optimization** [[paper](https://arxiv.org/abs/2403.08043)]
- [2024] **Text Detoxification as Style Transfer in English and Hindi** [[paper](https://arxiv.org/abs/2402.07767)]
- [2024] **MORL-Prompt: An Empirical Analysis of Multi-Objective Reinforcement Learning for Discrete Prompt Optimization** [[paper](https://arxiv.org/abs/2402.11711)]
- [2024] **Counterfactual Generation with Identifiability Guarantees** [[paper](https://arxiv.org/abs/2402.15309)] [[code](https://github.com/hanqi-qi/Matte.git)]
- [2024] **CAT-LLM: Style-enhanced Large Language Models with Text Style Definition for Chinese Article-style Transfer** [[paper](https://arxiv.org/abs/2401.05707)]

##### 2023

- [2023] **Multilingual Bias Detection and Mitigation for Indian Languages** [[paper](https://arxiv.org/abs/2312.15181)]
- [2023] **Learning to Generate Text in Arbitrary Writing Styles** [[paper](https://arxiv.org/abs/2312.17242)]
- [2023] **STEER: Unified Style Transfer with Expert Reinforcement** [[paper](https://arxiv.org/abs/2311.07167)]
- [2023] **PSST: A Benchmark for Evaluation-driven Text Public-Speaking Style Transfer** [[paper](https://arxiv.org/abs/2311.08389)]
- [2023] **Translating away Translationese without Parallel Data** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.18830)]
- [2023] **Text Fact Transfer** [[paper](https://arxiv.org/abs/2310.14486)]
- [2023] **Prefix-Tuning Based Unsupervised Text Style Transfer** [[paper](https://arxiv.org/abs/2310.14599)]
- [2023] **Diversify Question Generation with Retrieval-Augmented Style Transfer** [[paper](https://arxiv.org/abs/2310.14503)] [[code](https://github.com/gouqi666/RAST)]
- [2023] **Benchmarking and Improving Generator-Validator Consistency of Language Models** [[paper](https://arxiv.org/abs/2310.01846)]
- [2023] **A Discourse-level Multi-scale Prosodic Model for Fine-grained Emotion Analysis** [[paper](https://arxiv.org/abs/2309.11849)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **Artificial Intelligence in media discourse: the classification of linguistic and pragmatic features of the generated text** *Vestnik of North-Eastern Federal University History Political Science Law* [[paper](https://doi.org/10.25587/2222-5404-2025-22-4-234-249)]

##### 2025

- [2025] **Automated Description Generation of Cytologic Findings for Lung Cytological Images Using a Pretrained Vision Model and Dual Text Decoders: Preliminary Study** *Cytopathology* [[paper](https://doi.org/10.1111/cyt.13474)]
- [2025] **Using generative artificial intelligence in text generation** *IET conference proceedings.* [[paper](https://doi.org/10.1049/icp.2024.4493)]

##### 2024

- [2024] **AltGosling: automatic generation of text descriptions for accessible genomics data visualization** *Bioinformatics* [[paper](https://doi.org/10.1093/bioinformatics/btae670)]
- [2024] **English Grammar Auto-Correction Robot based on Grammatical Error Generation Model** *Scalable Computing Practice and Experience* [[paper](https://doi.org/10.12694/scpe.v25i6.2171)]
- [2024] **Crystal Composition Transformer: Self‐Learning Neural Language Model for Generative and Tinkering Design of Materials** *Advanced Science* [[paper](https://doi.org/10.1002/advs.202304305)]
- [2024] **Dynamic Function Generation for Text Classification** [[paper](https://dx.doi.org/10.1109/cec60901.2024.10611777)]
- [2024] **Generative AI-Based Text Generation Methods Using Pre-Trained GPT 2 Model** [[paper](https://doi.org/10.36227/techrxiv.171216659.95569463/v1)]

##### 2023

- [2023] **Probabilistic generative transformer language models for generative design of molecules** *Journal of Cheminformatics* [[paper](https://doi.org/10.1186/s13321-023-00759-z)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2025

- [2025] **Dual-Stream Feature Learning with RAG-Based Text Generation for Automated Liver Tumor Diagnosis** [[paper](https://doi.org/10.1109/iciteics64870.2025.11341473)]
- [2025] **Differential equation-driven intelligent control: Integrating AI, Quantum computing, and adaptive strategies for next-generation industrial automation** *Advances in Differential Equations and Control Processes* [[paper](https://doi.org/10.59400/adecp3096)]
- [2025] **Code generation system based on MDA and convolutional neural networks** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1491958)]
- [2025] **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3613256)]
- [2025] **The Evolution of AI: From Classical Machine Learning to Modern Large Language Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3621344)]

##### 2024

- [2024] **Computer Vision and Creative Content Generation: Text-to-Sketch Conversion** [[paper](https://doi.org/10.1109/ic3iot60841.2024.10550294)]
- [2024] **UAV-ENeRF: Text-Driven UAV Scene Editing With Neural Radiance Fields** *IEEE Transactions on Geoscience and Remote Sensing* [[paper](https://doi.org/10.1109/tgrs.2024.3379649)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **Maya-Vaidya P6: From Synapse to Sentence — Modelling Formal Thought Disorder via NMDAR-Perturbed Antahkarana Ring-Attractor Spiking Neural Network** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20744310)]
- [2026] **The use of neural networks in teaching academic writing skills in English to non-linguistic graduate students (case study of the LexiBot platform)** *Pedagogy Theory & Practice* [[paper](https://doi.org/10.30853/ped20260063)]
- [2026] **Spatial–temporal graph neural network with autoencoder pretraining for intrusion detection in healthcare IoT ecosystems** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-45041-y)]
- [2026] **Transformer-Based Neural Network Approaches for Speech Recognition and Synthesis in the Sakha Language** *Arctic XXI century* [[paper](https://doi.org/10.25587/3034-7378-2025-4-56-78)]
- [2026] **On-device neural text generation for personalized wellness: A comparative evaluation of lightweight LSTMS and cloud-based large language models** *Rutgers University Community Repository (Rutgers University)* [[paper](https://www.proquest.com/LegacyDocView/DISSNUM/32450711)]
- [2026] **DreamAssemble: Complex Multi-Object Text-to-3D Generation via Multi-Density Neural Fields** *IEEE Transactions on Image Processing* [[paper](https://doi.org/10.1109/tip.2026.3676627)]

##### 2025

- [2025] **Text-Independent Speaker Recognition and Audio Integrity Verification in Next-Generation Communication Networks using MFCCs and Machine Learning** [[paper](https://doi.org/10.1109/fit67061.2025.11333635)]
- [2025] **Beyond N-gram Overlap: Rethinking Evaluation Metrics for Neural Text Generation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17829119)]
- [2025] **ART-DECO: Arbitrary Text Guidance for 3D Detailizer Construction** [[paper](https://doi.org/10.1145/3757377.3763877)]
- [2025] **Research on the construction and application of retrieval enhanced generation (RAG) model based on knowledge graph** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-21222-z)]
- [2025] **NeuralSVG: An Implicit Representation for Text-to-Vector Generation** [[paper](https://arxiv.org/abs/2501.03992)]
- [2025] **Court of LLMs: Evidence-Augmented Generation via Multi-LLM Collaboration for Text-Attributed Graph Anomaly Detection** [[paper](https://doi.org/10.1145/3746027.3754821)]
- [2025] **BugMentor: Generating answers to follow-up questions from software bug reports using structured information retrieval and neural text generation** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2025.112636)]
- [2025] **Adversarial and Quantum-Driven Neural Network Cryptography: A Comprehensive Framework for Secure Encryption** [[paper](https://doi.org/10.1109/icsit65336.2025.11295049)]
- [2025] **HoLa: B-Rep Generation using a Holistic Latent Representation** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3730842)]
- [2025] **Context-Aware Speech Generation Using BiLSTM-Based Neural Networks** [[paper](https://doi.org/10.38124/ijisrt/25jul358)]
- [2025] **Breaking barriers in ICD classification with a robust graph neural network for hierarchical coding** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-10590-1)]
- [2025] **Artificial Neural Network Text Generation as a New Type of Masking the Authorship** *Virtual Communication and Social Networks* [[paper](https://doi.org/10.21603/2782-4799-2025-4-2-163-171)]
- [2025] **A Novel Benchmark for Persian Table-to-Text Generation: A New Dataset and Baseline Experiments** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3748648)]
- [2025] **Natural Language Generation Using Markov Chains for Chatbot** [[paper](https://doi.org/10.1109/etcc65847.2025.11108398)]
- [2025] **Literature-Based Discovery (LBD): Towards Hypothesis Generation and Knowledge Discovery in Biomedical Text Mining** *Medinformatics* [[paper](https://doi.org/10.47852/bonviewmedin52025348)]
- [2025] **Linguopragmatic Features of AI-Generated Text in the Media Discourse of Social Networks (on the Example of Texts Devoted to the Governor Election in the Nizhny Novgorod Region, Russian Federation, 2023)** *Bulletin of the Moscow State Regional University* [[paper](https://doi.org/10.18384/2224-0209-2025-2-1649)]
- [2025] **Automated Extraction of Handwritten Text from Forms Using Advanced Handwritten Text Recognition (HTR)** [[paper](https://doi.org/10.1109/i2cacis65476.2025.11100803)]
- [2025] **Towards Agentic AI for Science Hypothesis Generation, Comprehension, Quantification, and Validation** [[paper](https://doi.org/10.1145/3701716.3718485)]
- [2025] **Synthetic Data Generation of Body Motion Data by Neural Gas Network for Emotion Recognition** *Qeios* [[paper](https://doi.org/10.32388/h3ywex)]
- [2025] **Part-Aware Shape Generation With Latent 3D Diffusion of Neural Voxel Fields** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3562871)]
- [2025] **Full-shape analysis with simulation-based priors: Cosmological parameters and the structure growth anomaly** *Physical review. D/Physical review. D.* [[paper](https://doi.org/10.1103/physrevd.111.063548)]
- [2025] **DeepStego: Privacy-Preserving Natural Language Steganography Using Large Language Models and Advanced Neural Architectures** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202503.0627.v1)]
- [2025] **Generative AI for Text Generation with Word Estimation Module for the Natural Language Processing** *Journal of Computer Allied Intelligence (JCAI).* [[paper](https://doi.org/10.69996/jsihs.202007)]
- [2025] **Viewgen3D: Efficient Text-to-3D Model Generation with Multiview Consistency and Neural Radiance Fields** [[paper](https://doi.org/10.1109/sceecs64059.2025.10941689)]
- [2025] **The Combinatorial Fusion Cascade as a Neural Network** *AI* [[paper](https://doi.org/10.3390/ai6020023)]
- [2025] **Improving Semantic Parsing and Text Generation Through Multi-Faceted Data Augmentation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3593857)]
- [2025] **Balancing Indeterminacy and Structure: Neural Text Generation for Artistic Inspiration** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-90167-6_14)]

##### 2024

- [2024] **StAR: Learning on Text-Attributed Graphs with Structure-Aware Rationales** [[paper](https://doi.org/10.1109/hpcc64274.2024.00055)]
- [2024] **An Energy-Efficient Unstructured Sparsity-Aware Deep SNN Accelerator With 3-D Computation Array** *IEEE Journal of Solid-State Circuits* [[paper](https://doi.org/10.1109/jssc.2024.3507095)]
- [2024] **Turning Images into Words: A Neural Approach to Image Captioning Using VGG16 and LSTM** [[paper](https://doi.org/10.1109/icesic61777.2024.10846150)]
- [2024] **Enhancing Document AI Data Generation Through Graph-Based Synthetic Layouts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.03590)]
- [2024] **Dynamic Neural Alignment Mechanisms in Large Language Models to Contextual Integrity Preservation** [[paper](https://doi.org/10.22541/au.173144151.18152901/v1)]
- [2024] **Advanced RAG Models with Graph Structures: Optimizing Complex Knowledge Reasoning and Text Generation** [[paper](https://doi.org/10.1109/isceic63613.2024.10810209)]
- [2024] **Transformative Neural Networks for Technical Text Generation: Context Length Dependence Analysis** [[paper](https://doi.org/10.1109/khpiweek61434.2024.10878089)]
- [2024] **The culture of neural networks Synthetic literature and art in (not only) the Czech and Slovak context** *Karolinum Press eBooks* [[paper](https://dx.doi.org/10.14712/9788024657844)]
- [2024] **Large Multi-modality Model Assisted AI-Generated Image Quality Assessment** [[paper](https://arxiv.org/abs/2404.17762)]
- [2024] **Exploration of Text Classification Techniques in Natural Language Processing** [[paper](https://doi.org/10.1109/c3it60531.2024.10829488)]
- [2024] **Text-to-Vector Generation with Neural Path Representation** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3658204)]
- [2024] **Image Caption Generation Through the Integration of CNN-Based Residual Network Architectures and LSTM** [[paper](https://doi.org/10.1109/icicos62600.2024.10636926)]
- [2024] **Current Status and Prospects of Research on Neural Radiance Fields** *Journal of Computer-Aided Design & Computer Graphics* [[paper](https://doi.org/10.3724/sp.j.1089.2024.2023-00376)]
- [2024] **CLAY: A Controllable Large-scale Generative Model for Creating High-quality 3D Assets** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3658146)]
- [2024] **NIVeL: Neural Implicit Vector Layers for Text-to-Vector Generation** [[paper](https://doi.org/10.1109/cvpr52733.2024.00439)]
- [2024] **Intelligent Neural Network Machine with Thinking Functions** *Informatics and Automation* [[paper](https://doi.org/10.15622/ia.23.4.6)]
- [2024] **AtomGPT: Atomistic Generative Pretrained Transformer for Forward and Inverse Materials Design** *The Journal of Physical Chemistry Letters* [[paper](https://doi.org/10.1021/acs.jpclett.4c01126)]
- [2024] **The five generations of facial recognition usage and the Australian privacy law** *International Data Privacy Law* [[paper](https://doi.org/10.1093/idpl/ipae007)]
- [2024] **SkelCap: Automated Generation of Descriptive Text from Skeleton Keypoint Sequences** [[paper](https://arxiv.org/abs/2405.02977)]
- [2024] **Particle Swarm Optimization-Based Model Abstraction and Explanation Generation for a Recurrent Neural Network** *Algorithms* [[paper](https://doi.org/10.3390/a17050210)]
- [2024] **Neural Methods for Data-to-text Generation** *ACM Transactions on Intelligent Systems and Technology* [[paper](https://doi.org/10.1145/3660639)]
- [2024] **MECHANISMS OF GENERATION OF FAKE INFORMATION BY ARTIFICIAL INTELLIGENCE IN MODERN MEDIA DISCOURSE** *Bulletin of the Moscow State Regional University* [[paper](https://doi.org/10.18384/2224-0209-2024-2-1456)]
- [2024] **DreamCraft: Text-Guided Generation of Functional 3D Environments in Minecraft** [[paper](https://doi.org/10.1145/3649921.3649943)]
- [2024] **Advanced Multimodal Deep Learning Architecture for Image-Text Matching** [[paper](https://doi.org/10.1109/icetci61221.2024.10594167)]
- [2024] **Human AI Collaboration for Backend Text Generation: Dynamic Content Recommendation (DCR) for Websites Based on Keywords** [[paper](https://doi.org/10.1109/iccds60734.2024.10560437)]
- [2024] **Prot2Text: Multimodal Protein’s Function Generation with GNNs and Transformers** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i10.28948)]
- [2024] **Text2NeRF: Text-Driven 3D Scene Generation With Neural Radiance Fields** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2024.3361502)]
- [2024] **Multilingual Semantic Parsing and Generation with Neural Models** [[paper](https://dx.doi.org/10.33612/diss.915085019)]
- [2024] **Beyond images: an integrative multi-modal approach to chest x-ray report generation** *Frontiers in Radiology* [[paper](https://doi.org/10.3389/fradi.2024.1339612)]
- [2024] **Weakly-Supervised 3D Scene Graph Generation via Visual-Linguistic Assisted Pseudo-Labeling** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2024.3443670)]
- [2024] **Predictability and Causality in Spanish and English Natural Language Generation** *IEEE Access* [[paper](https://arxiv.org/abs/2408.14283)]
- [2024] **Exploring Data Augmentation in Neural DRS-to-Text Generation** [[paper](https://doi.org/10.18653/v1/2024.eacl-long.132)]
- [2024] **Emotion generation method in online physical education teaching based on data mining of teacher-student interactions** *PeerJ Computer Science* [[paper](https://doi.org/10.7717/peerj-cs.1814)]
- [2024] **Compositional-structural, semantic and presuppositional-pragmatic parameters and defects of generated short texts in the GigaChat language neural network** *Гуманитарные и юридические исследования* [[paper](https://doi.org/10.37493/2409-1030.2024.2.21)]
- [2024] **CANBLWO: A Novel Hybrid Approach for Semantic Text Generation** *The International Arab Journal of Information Technology* [[paper](https://doi.org/10.34028/iajit/21/4/11)]

##### 2023

- [2023] **Topology optimization with text-guided stylization** *Structural and Multidisciplinary Optimization* [[paper](https://doi.org/10.1007/s00158-023-03686-7)]
- [2023] **Enhancing Coherence and Diversity in Multi-class Slogan Generation Systems** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3637551)]
- [2023] **Automatic sign language translation system using neural network technologies and 3D animation** *Innovative technologies and scientific solutions for industries* [[paper](https://doi.org/10.30837/itssi.2023.26.108)]
- [2023] **AI Content Generation Technology based on Open AI Language Model** *Journal of Artificial Intelligence and Capsule Networks* [[paper](https://doi.org/10.36548/jaicn.2023.4.006)]
- [2023] **Neural graph-to-text generation with euclidean and riemannian graph encoding** [[paper](https://doi.org/10.70675/b0563a9fz0ff1z4daaza710za9e4d3ed4301)]
- [2023] **Image Caption Generation using ResNET-50 and LSTM** [[paper](https://doi.org/10.1109/silcon59133.2023.10404600)]
- [2023] **HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.17061)]
- [2023] **ConRad: Image Constrained Radiance Fields for 3D Generation from a Single Image** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.05230)]
- [2023] **Recent progress in the JARVIS infrastructure for next-generation data-driven materials design** *Applied Physics Reviews* [[paper](https://doi.org/10.1063/5.0159299)]
- [2023] **Quantifying the Plausibility of Context Reliance in Neural Machine Translation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.01188)]
- [2023] **Controlling Topic-Focus Articulation in Meaning-to-Text Generation using Graph Neural Networks** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.02053)]
- [2023] **Artificial intelligence for prediction of biological activities and generation of molecular hits using stereochemical information** *Journal of Computer-Aided Molecular Design* [[paper](https://doi.org/10.1007/s10822-023-00539-9)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2025

- [2025] **Neural network-aided unsupervised input function estimation for dual-time-window PET Patlak analysis** *EJNMMI Physics* [[paper](https://doi.org/10.1186/s40658-025-00804-w)]
- [2025] **Development of digital literacy of teachers when designing plots of text games using neural network tools in the context of additional professional education** *Perspectives of science and education* [[paper](https://doi.org/10.32744/pse.2025.4.42)]
- [2025] **Pan-Canadian Predictive Modeling of Lithium–Cesium–Tantalum Pegmatites with Deep Learning and Natural Language Processing** *Natural Resources Research* [[paper](https://doi.org/10.1007/s11053-024-10438-x)]

##### 2023

- [2023] **Transforming Text Generation in NLP: Deep Learning with GPT Models and 2023 Twitter Corpus Using Transformer Architecture** *International Journal on Recent and Innovation Trends in Computing and Communication* [[paper](https://doi.org/10.17762/ijritcc.v11i9.9463)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2025

- [2025] **Text-driven 3D scene generation by panoramic neural radiance fields** [[paper](https://doi.org/10.1117/12.3070244)]
- [2025] **AI-Powered Solutions for Content Generation** [[paper](https://doi.org/10.1109/ginotech63460.2025.11076741)]
- [2025] **Text2Avatar: Articulated 3D Avatar Creation With Text Instructions** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2025.3535293)]

##### 2024

- [2024] **Towards Inclusive Reading: A Neural Text Generation Framework for Dyslexia Accessibility** [[paper](https://doi.org/10.1145/3696593.3696625)]
- [2024] **MDT-A2G: Exploring Masked Diffusion Transformers for Co-Speech Gesture Generation** [[paper](https://arxiv.org/abs/2408.03312)]
- [2024] **Enhancing Image Caption Generation Using Reinforcement Learning with Human Feedback** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.06735)]
- [2024] **Artificial intelligence-driven virtual rehabilitation for people living in the community: A scoping review** *npj Digital Medicine* [[paper](https://doi.org/10.1038/s41746-024-00998-w)]
- [2024] **Text2Layout: Layout Generation From Text Representation Using Transformer** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3452957)]
- [2024] **Survey of Different Large Language Model Architectures: Trends, Benchmarks, and Challenges** *IEEE Access* [[paper](https://arxiv.org/abs/2412.03220)]
- [2024] **Enhancing personalized learning: AI-driven identification of learning styles and content modification strategies** *International Journal of Cognitive Computing in Engineering* [[paper](https://doi.org/10.1016/j.ijcce.2024.06.002)]
- [2024] **Cross-Utterance Conditioned VAE for Speech Generation** *IEEE/ACM Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslp.2024.3453598)]

##### 2023

- [2023] **GEEF: A neural network model for automatic essay feedback generation by integrating writing skills assessment** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2023.123043)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **Neural Text Generation Model for Personalized Storytelling in Primary Education** [[paper](https://doi.org/10.1109/iciscois62701.2026.11447902)]

##### 2025

- [2025] **Automated sentiment analysis of short texts** *Ontology of Designing* [[paper](https://doi.org/10.18287/2223-9537-2025-15-4-566-577)]
- [2025] **Research on Low-Latency Inference and Training Efficiency Optimization for Graph Neural Network and Large Language Model-Based Recommendation Systems** [[paper](https://doi.org/10.1109/caibda65784.2025.11182947)]
- [2025] **High-precision improved text prompt 3D model generation and printing method** *Rapid Prototyping Journal* [[paper](https://doi.org/10.1108/rpj-01-2025-0019)]
- [2025] **Meta-StyleSpeech: Multi-speaker adaptive text-to-speech generation** *TIB Data Manager* [[paper](https://doi.org/10.57702/fqzsmwin)]
- [2025] **Application of Multimodal Generation Model in Short Video Content Personalized Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5166910)]

##### 2024

- [2024] **Analysis of Emotion Recognition System Based on Hybrid Neural Network** [[paper](https://doi.org/10.1109/icaica63239.2024.10823011)]
- [2024] **Fine-Tuning Text-To-Image Diffusion Models for Class-Wise Spurious Feature Generation** [[paper](https://dx.doi.org/10.1109/icip51287.2024.10647627)]
- [2024] **MeMemo: On-device Retrieval Augmentation for Private and Personalized Text Generation** [[paper](https://arxiv.org/abs/2407.01972)]
- [2024] **ReVoice: A Neural Network based Voice Cloning System** [[paper](https://doi.org/10.1109/i2ct61223.2024.10543448)]
- [2024] **Neural networks in libraries: A new development in bibliographic services** *Scientific and Technical Libraries* [[paper](https://doi.org/10.33186/1027-3689-2024-1-105-128)]
- [2024] **Generation WhatsApp: inter-brain synchrony during face-to-face and texting communication** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-52587-2)]
- [2024] **Personalizing Text-to-Image Diffusion Models by Fine-Tuning Classification for AI Applications** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-031-47721-8_44)]
- [2024] **Generative AI and Large Language Models - Benefits, Drawbacks, Future and Recommendations** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2024.09.689)]

##### 2023

- [2023] **Natural Language Processing: Chances and Challenges in Dentistry** *Journal of Dentistry* [[paper](https://doi.org/10.1016/j.jdent.2023.104796)]
- [2023] **DreamBooth3D: Subject-Driven Text-to-3D Generation** [[paper](https://doi.org/10.1109/iccv51070.2023.00223)]
- [2023] **Generation Whatsup: Inter-Brain Synchrony during Face-to-Face and Texting Communication** *Research Square* [[paper](https://dx.doi.org/10.21203/rs.3.rs-3370479/v1)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2025

- [2025] **Factual consistency in neural text generation: detecting, correcting, and understanding hallucinations** [[paper](https://hdl.handle.net/20.500.14905/120092)]

##### 2024

- [2024] **Reducing tail entity hallucinations with dependency edge prediction in text to text transfer transformer based auto-generated questions** *International Journal of Information Technology* [[paper](https://dx.doi.org/10.1007/s41870-024-02205-1)]
- [2024] **Conceptualizing generative AI as style engines: Application archetypes and implications** *International Journal of Information Management* [[paper](https://doi.org/10.1016/j.ijinfomgt.2024.102824)]
- [2024] **When Robots Get Chatty: Grounding Multimodal Human-Robot Conversation and Collaboration** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72341-4_21)]
- [2024] **Style-News: Incorporating Stylized News Generation and Adversarial Verification for Neural Fake News Detection** [[paper](https://doi.org/10.18653/v1/2024.eacl-long.92)]

[⬆ Back to top](#paper-list)

#### NLP Metrics

##### 2026

- [2026] **Metric-Driven Adaptive Temperature Prediction for Neural Text Generation: A Regression-Based Approach** [[paper](https://doi.org/10.1109/imed68921.2026.11484146)]

##### 2025

- [2025] **Enhancing SPARQL query generation for question answering with a hybrid encoder–decoder and cross-attention model** *Journal of Web Semantics* [[paper](https://doi.org/10.1016/j.websem.2025.100869)]
- [2025] **Image Caption Generation Using Deep Learning** *Journal of Information Systems Engineering & Management* [[paper](https://doi.org/10.52783/jisem.v10i47s.9258)]
- [2025] **Advances in neural text generation: A systematic review (2022-2024)** [[paper](https://doi.org/10.55056/ceur-ws.org/vol-3917/paper59.pdf)]
- [2025] **RAG-Enhanced Neural Machine Translation of Ancient Egyptian Text: A Case Study of THOTH AI** [[paper](https://doi.org/10.18653/v1/2025.nlp4dh-1.4)]

##### 2024

- [2024] **A Novel Model for Chart-to-Text Generation by Utilizing NN Models** [[paper](https://doi.org/10.1109/3ict64318.2024.10824513)]
- [2024] **“Idol talks!” AI-driven image to text to speech: illustrated by an application to images of deities** *Heritage Science* [[paper](https://doi.org/10.1186/s40494-024-01490-0)]
- [2024] **NeuGPT: Unified multi-modal Neural GPT** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.20916)]
- [2024] **A Hybrid Deep Learning Model for Automated Cricket Commentary Generation** [[paper](https://doi.org/10.1109/icccmla63077.2024.10871604)]
- [2024] **LLMs-in-the-loop Part-1: Expert Small AI Models for Bio-Medical Text Translation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.12126)]

##### 2023

- [2023] **Investigating T5 Generation Neural Machine Translation Performance on English to German** [[paper](https://doi.org/10.1109/icimcis60089.2023.10349061)]
- [2023] **Image Talk: A Model for Image Caption Generation with Voice** [[paper](https://dx.doi.org/10.1109/incoft60753.2023.10425636)]
- [2023] **Integrating Extractive and Abstractive Models for Code Comment Generation** [[paper](https://dx.doi.org/10.1109/qrs60937.2023.00027)]
- [2023] **Context-Aware Auto-Encoded Graph Neural Model for Dynamic Question Generation using NLP** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3626317)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2025

- [2025] **Graph-Guided Textual Explanation Generation Framework** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.1494)]

##### 2024

- [2024] **Foleygen: Visually-Guided Audio Generation** [[paper](https://doi.org/10.1109/mlsp58920.2024.10734721)]
- [2024] **Mitigating Text Toxicity with Counterfactual Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.09948)]
- [2024] **Exploring the impact of data representation on neural data-to-text generation** [[paper](https://doi.org/10.18653/v1/2024.inlg-main.20)]

##### 2023

- [2023] **What is the Best Automated Metric for Text to Motion Generation?** [[paper](https://doi.org/10.1145/3610548.3618185)]
- [2023] **Question Generation: An Experimental Study for Vietnamese Text** [[paper](https://doi.org/10.1109/rivf60135.2023.10471875)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Uncertain Aspect-Aware Triplet Disentangling-Transferring for Domain-Specific Multimodal Neural Machine Translation** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2026.3703201)]
- [2026] **Text-to-image generation with enhanced GANs: Bridging semantic gaps using RNN and CNN** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0340413)]
- [2026] **A Self-Adaptive Physics-Informed Gated Recurrent Unit Neural Networks Model for Estimating the Lifetime of Li-ion Batteries** *IEEE Transactions on Transportation Electrification* [[paper](https://doi.org/10.1109/tte.2026.3703913)]
- [2026] **6G conditioned spatiotemporal graph neural networks for real time traffic flow prediction** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-32795-0)]

##### 2025

- [2025] **Emotion classification using advanced neural networks on sentence-level data** *PeerJ Computer Science* [[paper](https://doi.org/10.7717/peerj-cs.3411)]
- [2025] **An augmented multi-label neural network-based approach for text classification in small and unbalanced datasets: the case of digital innovation in the EIP-AGRI Operational Groups** *The Journal of Supercomputing* [[paper](https://doi.org/10.1007/s11227-025-08100-1)]
- [2025] **ANN-based analysis of MHD third-grade hybrid nanofluid flow over a thin needle with fuzzy volume fraction under nonlinear radiation and heat generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-29013-2)]
- [2025] **A novel approach to identify deepfake text using social media data** *Social Network Analysis and Mining* [[paper](https://doi.org/10.1007/s13278-025-01536-6)]
- [2025] **A Systematic Framework for Text-To-Speech System** [[paper](https://doi.org/10.1109/iccca66364.2025.11325188)]
- [2025] **Optimizing deep learning models for on-orbit deployment through neural architecture search** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-21467-8)]
- [2025] **Next-Generation Text-to-Speech: Neural Models, Benchmarks and Future Prospects** [[paper](https://doi.org/10.1109/iccica67008.2025.11337494)]
- [2025] **Mitigating Stereotypes in Text-to-Image Generation: A Novel Perspective of Selective Neural Suppression** [[paper](https://doi.org/10.1145/3746027.3755293)]
- [2025] **CQ-CNN: A lightweight hybrid classical–quantum convolutional neural network for Alzheimer’s disease detection using 3D structural brain MRI** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0331870)]
- [2025] **OctFusion: Octree‐based Diffusion Models for 3D Shape Generation** *Computer Graphics Forum* [[paper](https://doi.org/10.1111/cgf.70198)]
- [2025] **Dynamic Image Generation with Deep Generative Artificial Neural Network** [[paper](https://doi.org/10.1109/iccpct65132.2025.11176756)]
- [2025] **Tucano: Advancing neural text generation for Portuguese** *Patterns* [[paper](https://doi.org/10.1016/j.patter.2025.101325)]
- [2025] **Convolutional neural networks with transfer learning for natural river flow prediction in ungauged basins** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-07088-1)]
- [2025] **Improved Text Generation Using Combined Generative Adversarial and Recurrent Neural Networks** *IETE Technical Review* [[paper](https://doi.org/10.1080/02564602.2025.2510960)]
- [2025] **Customization of the text-to-image diffusion model by fine-tuning for the generation of synthetic images of cyanobacterial blooms in lentic water bodies** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.128169)]
- [2025] **Text-to-Image Generation Using Recurrent Convolutional GANs** [[paper](https://doi.org/10.1109/icetecc65365.2025.11070226)]
- [2025] **Leveraging Text Semantics for Enhanced Scene Text Image Super-Resolution** *Intelligent and Converged Networks* [[paper](https://doi.org/10.23919/icn.2025.0009)]
- [2025] **Detection and classification of ChatGPT-generated content using deep transformer models** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1458707)]
- [2025] **An NLP Approach to Efficient Duplicate Question Detection using Neural Networks and TF-IDF** [[paper](https://doi.org/10.1109/iccit63348.2025.10989389)]
- [2025] **Text-Guided Synthesis in Medical Multimedia Retrieval: A Framework for Enhanced Colonoscopy Image Classification and Segmentation** *Algorithms* [[paper](https://doi.org/10.3390/a18030155)]
- [2025] **Evaluating Cross-Domain Sentiment Analysis using Convolutional Neural Network for Amazon Dataset** *Journal of Advanced Research in Applied Sciences and Engineering Technology* [[paper](https://doi.org/10.37934/araset.63.2.207214)]
- [2025] **BERT-Guided Pseudo Label Generation for Topical Text Classification** [[paper](https://doi.org/10.1109/ieecon64081.2025.10987595)]
- [2025] **AS-Net: Adaptive Style-aware Network for Handwritten Text Generation** [[paper](https://doi.org/10.1109/icassp49660.2025.10889851)]
- [2025] **A stochastic numerical analysis based on Levenberg–Marquardt backpropagation neural networks for entropy generation in nanofluid flow with radiation aspects** *International Journal of Geometric Methods in Modern Physics* [[paper](https://doi.org/10.1142/s0219887825501725)]
- [2025] **A Survey on Detection of Deepfake Text and Sentiment Analysis using Machine Learning Models** [[paper](https://doi.org/10.1201/9781003504832-8)]
- [2025] **\mathsf{TCG}-\mathsf{IDS} : Robust Network Intrusion Detection via Temporal Contrastive Graph Learning** *IEEE Transactions on Information Forensics and Security* [[paper](https://doi.org/10.1109/tifs.2025.3530702)]
- [2025] **SpeechFake: A Large-Scale Multilingual Speech Deepfake Dataset Incorporating Cutting-Edge Generation Methods** [[paper](https://doi.org/10.18653/v1/2025.acl-long.493)]
- [2025] **Retrieval Augmented Generation (RAG) Model** *International Journal of Research Publication and Reviews* [[paper](https://doi.org/10.55248/gengpi.6.0125.0635)]
- [2025] **Number Recognition Through Color Distortion Using Convolutional Neural Networks** *Computers* [[paper](https://doi.org/10.3390/computers14020034)]
- [2025] **Information extraction from texts based on ontology and large language models** *Ontology of Designing* [[paper](https://doi.org/10.18287/2223-9537-2025-15-1-114-129)]
- [2025] **Designing artificial intelligence computing techniques to study heat transfer of a ternary hybrid nanofluid flow: Application of particle swarm optimization and artificial neural network** *Modern Physics Letters B* [[paper](https://doi.org/10.1142/s0217984925501143)]
- [2025] **Deepfake Audio Detection for Urdu Language Using Deep Neural Networks** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3571293)]
- [2025] **CODE-ACCORD: A Corpus of building regulatory data for rule generation towards automatic compliance checking** *Scientific Data* [[paper](https://doi.org/10.1038/s41597-024-04320-x)]
- [2025] **Analyzing and Mitigating Inconsistency in Discrete Speech Tokens for Neural Codec Language Models** [[paper](https://doi.org/10.18653/v1/2025.acl-long.1498)]
- [2025] **An intelligent neural question answer generation from text using Seq2se2 with attention mechanism system** *International Journal of System of Systems Engineering* [[paper](https://doi.org/10.1504/ijsse.2025.147019)]

##### 2024

- [2024] **Forking Paths in Neural Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.07961)]
- [2024] **Distinguishing Human From Machine: A Review of Advances and Challenges in AI-Generated Text Detection** *International Journal of Interactive Multimedia and Artificial Intelligence* [[paper](https://doi.org/10.9781/ijimai.2024.12.002)]
- [2024] **Face Generation and Recognition in Forensic Science** [[paper](https://doi.org/10.1109/icacc63692.2024.10845604)]
- [2024] **Automatic Story Text Generation Using Recurrent Neural Network Algorithm** [[paper](https://doi.org/10.1109/comnetsat63286.2024.10861931)]
- [2024] **Synthetic Image Generation Using Deep Learning: A Systematic Literature Review** *Computational Intelligence* [[paper](https://doi.org/10.1111/coin.70002)]
- [2024] **Image Caption Generation using CNN and Audio Conversion** [[paper](https://doi.org/10.1109/icssas64001.2024.10760457)]
- [2024] **Guide for the application of the data augmentation approach on sets of texts in Spanish for sentiment and emotion analysis** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0310707)]
- [2024] **Development of a Neural Network Model for Recognizing Russian-Language Generated Texts** [[paper](https://doi.org/10.1109/sibircon63777.2024.10758447)]
- [2024] **Character-Level Text Generation for Shakespearean Style with LSTMs** *International Journal of Innovative Science and Research Technology (IJISRT)* [[paper](https://doi.org/10.38124/ijisrt/ijisrt24aug1043)]
- [2024] **Marrying Dialogue Systems with Data Visualization: Interactive Data Visualization Generation from Natural Language Conversations** [[paper](https://doi.org/10.1145/3637528.3671935)]
- [2024] **Digital Epidemiology of Prescription Drug References on X (Formerly Twitter): Neural Network Topic Modeling and Sentiment Analysis** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/57885)]
- [2024] **DialogueNeRF: towards realistic avatar face-to-face conversation video generation** *Visual Intelligence* [[paper](https://doi.org/10.1007/s44267-024-00057-8)]
- [2024] **Media2Face: Co-speech Facial Animation Generation With Multi-Modality Guidance** [[paper](https://doi.org/10.1145/3641519.3657413)]
- [2024] **Machine learning for big data and neural networks** [[paper](https://doi.org/10.1201/9781003500865-4)]
- [2024] **Generative adversarial networks for handwriting image generation: a review** *The Visual Computer* [[paper](https://doi.org/10.1007/s00371-024-03534-9)]
- [2024] **FastFaceCLIP: A lightweight text‐driven high‐quality face image manipulation** *IET Computer Vision* [[paper](https://doi.org/10.1049/cvi2.12295)]
- [2024] **A survey of generative models used in text-to-image** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/79/20241286)]
- [2024] **A novel design of recurrent neural network to investigate the heat transmission of radiative Casson nanofluid flow consisting of carbon nanotubes (CNTs) across a curved stretchable surface** *ZAMM ‐ Journal of Applied Mathematics and Mechanics / Zeitschrift für Angewandte Mathematik und Mechanik* [[paper](https://doi.org/10.1002/zamm.202400104)]
- [2024] **ECG-Image-Kit: a synthetic image generation toolbox to facilitate deep learning-based electrocardiogram digitization** *Physiological Measurement* [[paper](https://doi.org/10.1088/1361-6579/ad4954)]
- [2024] **Comparative study of typical neural solvers in solving math word problems** *Complex & Intelligent Systems* [[paper](https://doi.org/10.1007/s40747-024-01454-8)]
- [2024] **BEACOMP: A Novel Textual Adversarial Attack Architecture for Unveiling the Fragility of Neural Text Classifiers** [[paper](https://dx.doi.org/10.1109/incacct61598.2024.10550990)]
- [2024] **Automated Text Recognition and Segmentation for Historic Map Vectorization: A Mask R-CNN and UNet Approach** *Journal of Electrical Systems* [[paper](https://doi.org/10.52783/jes.3413)]
- [2024] **Optimizing Handwritten Text Recognition for Automated Note Generation for Enhanced Learning Environment** [[paper](https://doi.org/10.1109/mitadtsocicon60330.2024.10574919)]
- [2024] **Boosting generalization of fine-tuning BERT for fake news detection** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2024.103745)]
- [2024] **Development and Classification of Image Dataset for Text-to-Image Generation** *Journal of The Institution of Engineers (India) Series B* [[paper](https://doi.org/10.1007/s40031-024-01013-2)]
- [2024] **Automated Classification of User Needs for Beginner User Experience Designers: A Kano Model and Text Analysis Approach Using Deep Learning** *AI* [[paper](https://doi.org/10.3390/ai5010018)]
- [2024] **A Tale of Tails: Model Collapse as a Change of Scaling Laws** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.07043)]
- [2024] **A Study on the Application of Using Hypernetwork and Low Rank Adaptation for Text-to-Image Generation Based on Diffusion Models** [[paper](https://doi.org/10.1109/reepe60449.2024.10479561)]
- [2024] **Unsupervised Sign Language Translation and Generation** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.835)]
- [2024] **Towards Cross-Cultural Machine Translation with Retrieval-Augmented Generation from Multilingual Knowledge Graphs** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.914)]
- [2024] **Text2Face: Text-Based Face Generation With Geometry and Appearance Control** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2023.3349050)]
- [2024] **Sketch2NeRF: Multi-view Sketch-guided Text-to-3D Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.14257)]
- [2024] **ReflectanceFusion: Diffusion-based text to SVBRDF Generation** *Research Explorer (The University of Manchester)* [[paper](https://arxiv.org/abs/2406.14565)]
- [2024] **Project PRIMUS at EHRSQL 2024 : Text-to-SQL Generation using Large Language Model for EHR Analysis** [[paper](https://doi.org/10.18653/v1/2024.clinicalnlp-1.41)]
- [2024] **Multi-Speaker Text-to-Speech Training With Speaker Anonymized Data** *IEEE Signal Processing Letters* [[paper](https://doi.org/10.1109/lsp.2024.3482701)]
- [2024] **Multi-Loss Fusion: Angular and Contrastive Integration for Machine-Generated Text Detection** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.421)]
- [2024] **FreeCtrl: Constructing Control Centers with Feedforward Layers for Learning-Free Controllable Text Generation** [[paper](https://doi.org/10.18653/v1/2024.acl-long.412)]
- [2024] **Diffusion-Based Data Augmentation for Skin Disease Classification: Impact Across Original Medical Datasets to Fully Synthetic Images** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-53767-7_10)]
- [2024] **Controlled Transformation of Text-Attributed Graphs** [[paper](https://dx.doi.org/10.18653/v1/2024.findings-emnlp.923)]
- [2024] **Advanced image generation for cancer using diffusion models** *Biology Methods and Protocols* [[paper](https://doi.org/10.1093/biomethods/bpae062)]
- [2024] **A Video Captioning Method by Semantic Topic-Guided Generation** *Computers, materials & continua/Computers, materials & continua (Print)* [[paper](https://doi.org/10.32604/cmc.2023.046418)]

##### 2023

- [2023] **Neural Network Sentiment Classification of Russian Sentences into Four Classes** *Automatic Control and Computer Sciences* [[paper](https://doi.org/10.3103/s0146411623070052)]
- [2023] **Cross-Modal Question Generation: NLP-based Approaches for Text, Image, PDF, and Video Inputs** [[paper](https://dx.doi.org/10.1109/icimia60377.2023.10426142)]
- [2023] **A review of neural networks for rare intrusions detection in wireless networks** *Journal of Science and Technology on Information security* [[paper](https://dx.doi.org/10.54654/isj.v3i20.984)]
- [2023] **Text Description to Facial Sketch Generation using GANs** [[paper](https://dx.doi.org/10.1109/icet59753.2023.10374885)]
- [2023] **Recognition-Guided Diffusion Model for Scene Text Image Super-Resolution** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.13317)]
- [2023] **Invisible Relevance Bias: Text-Image Retrieval Models Prefer AI-Generated Images** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.14084)]
- [2023] **Text-Guided Image Generation for Railway Intrusion Anomaly Detection** [[paper](https://doi.org/10.1109/icus58632.2023.10318477)]
- [2023] **Synconn_build: A python based synthetic dataset generator for testing and validating control-oriented neural networks for building dynamics prediction** *MethodsX* [[paper](https://doi.org/10.1016/j.mex.2023.102464)]
- [2023] **Let the Pretrained Language Models "Imagine" for Short Texts Topic Modeling** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.15420)]
- [2023] **Evaluating the Effectiveness of Capsule Neural Network in Toxic Comment Classification Using Pre-Trained BERT Embeddings** [[paper](https://doi.org/10.1109/tencon58879.2023.10322429)]
- [2023] **Data Extraction via Semantic Regular Expression Synthesis** *Proceedings of the ACM on Programming Languages* [[paper](https://doi.org/10.1145/3622863)]
- [2023] **Adopting Neural Translation Model in Data Generation for Inverse Text Normalization** [[paper](https://dx.doi.org/10.1109/apsipaasc58517.2023.10317241)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2024

- [2024] **Image to Text Conversion Using Deep Learning Algorithms: Survey** [[paper](https://doi.org/10.1109/icaccs60874.2024.10716956)]
- [2024] **Fake Review Detection using Neural Network** [[paper](https://doi.org/10.1109/esci59607.2024.10497283)]
- [2024] **Sign Language to Text Translation with Computer Vision: Bridging the Communication Gap** [[paper](https://doi.org/10.1109/icdxa61007.2024.10470532)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Maya-Vak P1: Spike-Native Affective Language Generation in a Seven-Population Antahkarana SNN — From Internal State to First-Person Narration Without a Language Model** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20571339)]
- [2026] **A Systematic Literature Review on Integrated Deep Learning and Multiagent Vision-Language Frameworks for Pathology Image Analysis and Report Generation** *Computational and Structural Biotechnology Journal* [[paper](https://doi.org/10.34133/csbj.0023)]

##### 2025

- [2025] **(LLM) AI Generated Text Detection** *INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT* [[paper](https://doi.org/10.55041/ijsrem41593)]

##### 2024

- [2024] **Integrating Medical Imaging and Clinical Reports Using Multimodal Deep Learning for Advanced Disease Analysis** [[paper](https://doi.org/10.1109/icsece61636.2024.10729527)]
- [2024] **Exploring deep convolutional generative adversarial networks (DCGAN) in biometric systems: a survey study** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-024-00138-z)]
- [2024] **Evaluation of large language models performance against humans for summarizing MRI knee radiology reports: A feasibility study** *International Journal of Medical Informatics* [[paper](https://doi.org/10.1016/j.ijmedinf.2024.105443)]

##### 2023

- [2023] **Radiological Report Generation from Chest X-ray Images Using Pre-trained Word Embeddings** *Wireless Personal Communications* [[paper](https://doi.org/10.1007/s11277-024-10886-x)]
- [2023] **IIHT: Medical Report Generation with Image-to-Indicator Hierarchical Transformer** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-8076-5_5)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2024

- [2024] **Evolutionary Computation in the Era of Large Language Model: Survey and Roadmap** *IEEE Transactions on Evolutionary Computation* [[paper](https://doi.org/10.1109/tevc.2024.3506731)]
- [2024] **Creative Text-to-Audio Generation via Synthesizer Programming** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.00294)]
- [2024] **Enhancing Large Language Models-Based Code Generation by Leveraging Genetic Improvement** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-56957-9_7)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2025

- [2025] **Pythia-RAG: Retrieval-augmented generation over a unified multimodal knowledge graph for enhanced QA** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.115200)]
- [2025] **Image Generation With Supervised Selection Based on Multimodal Features for Semantic Communications** *IEEE Transactions on Communications* [[paper](https://doi.org/10.1109/tcomm.2025.3615798)]
- [2025] **One framework to rule them all: Unifying multimodal tasks with LLM neural-tuning** *Pattern Recognition* [[paper](https://doi.org/10.1016/j.patcog.2025.112275)]
- [2025] **Foundation neural-networks quantum states as a unified Ansatz for multiple hamiltonians** *Nature Communications* [[paper](https://doi.org/10.1038/s41467-025-62098-x)]
- [2025] **Understanding Generative Adversarial Networks (GANs): A Review** *Control Systems and Optimization Letters* [[paper](https://doi.org/10.59247/csol.v3i1.170)]

##### 2024

- [2024] **Hybrid explainable image caption generation using image processing and natural language processing** *International Journal of Systems Assurance Engineering and Management* [[paper](https://doi.org/10.1007/s13198-024-02495-5)]
- [2024] **Image-Text Multimodal Translation Based on AIGC Human-Machine Interaction** [[paper](https://doi.org/10.1145/3678429.3678436)]
- [2024] **Optimized Image Captioning: Hybrid Transformers Vision Transformers and Convolutional Neural Networks: Enhanced with Beam Search** *International Journal of Intelligent Systems and Applications* [[paper](https://doi.org/10.5815/ijisa.2024.02.05)]
- [2024] **TellMeTalk: Multimodal-driven talking face video generation** *Computers & Electrical Engineering* [[paper](https://doi.org/10.1016/j.compeleceng.2023.109049)]
- [2024] **Taylor African vulture optimization algorithm with hybrid deep convolution neural network for image captioning system** *Multimedia Tools and Applications* [[paper](https://doi.org/10.1007/s11042-023-18080-0)]
- [2024] **ReverseGAN: An intelligent reverse generative adversarial networks system for complex image captioning generation** *Displays* [[paper](https://doi.org/10.1016/j.displa.2024.102653)]

##### 2023

- [2023] **Text Generation for Hindi** [[paper](https://dx.doi.org/10.1109/icast59062.2023.10455023)]
- [2023] **Iterative Adversarial Attack on Image-Guided Story Ending Generation** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2023.3345167)]
- [2023] **FoldGEN: Multimodal Transformer for Garment Sketch-to-Photo Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-50072-5_36)]
- [2023] **Image caption generation using transformer learning methods: a case study on instagram image** *Multimedia Tools and Applications* [[paper](https://doi.org/10.1007/s11042-023-17275-9)]

[⬆ Back to top](#paper-list)

### Writing Assistants

#### Creative Writing

##### 2026

- [2026] **Proof-of-Concept Implementation: Time Series Data Integration for the Web of Things** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20829527)]

[⬆ Back to top](#paper-list)

#### Autocomplete

##### 2026

- [2026] **Designing Proactive Thought Partners for Writing** [[paper](https://arxiv.org/abs/2609.01588)]
- [2026] **AI Agents Explained: 12 Real Examples Across Industries** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21676342)]
- [2026] **Smart Developer Assistant (SDA): An AI-Driven Multi-Agent Framework for Automated Code Generation, Debugging, and Documentation** *INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT* [[paper](https://doi.org/10.55041/ijsrem63072)]
- [2026] **Democratizing Software Engineering in the Global South: A Comprehensive Analysis of the Omnient.io AI-Powered Development Platform by Synaptic AI Lab** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19094618)]
- [2026] **Biased AI writing assistants shift users’ attitudes on societal issues** *Science Advances* [[paper](https://doi.org/10.1126/sciadv.adw5578)]
- [2026] **Spelling Correction in Healthcare Query-Answer Systems: Methods, Retrieval Impact, and Empirical Evaluation** [[paper](https://arxiv.org/abs/2603.19249)]
- [2026] **AI for Code Generation and Developer Tools** [[paper](https://doi.org/10.1002/9781394406418.ch10)]

##### 2025

- [2025] **AI Writing Assistant Gender Stereotype Bias Intervention (Study 1)** [[paper](https://osf.io/c84e9)]
- [2025] **Dark Patterns in AI-Assisted Writing and Autocomplete Interfaces** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5448277)]

##### 2024

- [2024] **Predictive Tree-based Virtual Keyboard for Improved Gaze Typing** [[paper](https://arxiv.org/abs/2410.08570)]
- [2024] **Sequential Decision-Making for Inline Text Autocomplete** [[paper](https://arxiv.org/abs/2403.15502)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **Exploring Motivations for Algorithm Mention in the Domain of Natural Language Processing: A Deep Learning Approach** [[paper](https://arxiv.org/abs/2606.29859)]
- [2026] **Best Preprocessing Techniques for Sentiment Analysis** [[paper](https://arxiv.org/abs/2606.24055)]
- [2026] **LLMs for automatic annotation of Mandarin narrative transcripts** [[paper](https://arxiv.org/abs/2605.17205)]
- [2026] **Multi-Level Narrative Evaluation Outperforms Lexical Features for Mental Health** [[paper](https://arxiv.org/abs/2604.27846)]
- [2026] **CSRP: Chain-of-Thought Reasoning for Chinese Text Correction via Reinforcement Learning with Efficiency-Aware Rewards** [[paper](https://arxiv.org/abs/2606.00020)] [[code](https://github.com/TW-NLP/ChineseErrorCorrector)]
- [2026] **Developing a Guideline for the Labovian-Structural Analysis of Oral Narratives in Japanese** [[paper](https://arxiv.org/abs/2603.29347)]

##### 2025

- [2025] **Teaching Spell Checkers to Teach: Pedagogical Program Synthesis for Interactive Learning** [[paper](https://arxiv.org/abs/2512.12115)]
- [2025] **CEC-Zero: Zero-Supervision Character Error Correction with Self-Generated Rewards** [[paper](https://arxiv.org/abs/2512.23971)]
- [2025] **ChineseErrorCorrector3-4B: State-of-the-Art Chinese Spelling and Grammar Corrector** [[paper](https://arxiv.org/abs/2511.17562)]
- [2025] **Levée d'ambiguïtés par grammaires locales** [[paper](https://arxiv.org/abs/2510.24530)]
- [2025] **Vision Language Models Are Not (Yet) Spelling Correctors** [[paper](https://arxiv.org/abs/2509.17418)]
- [2025] **Contextualized Token Discrimination for Speech Search Query Correction** [[paper](https://arxiv.org/abs/2509.04393)]
- [2025] **TiSpell: A Semi-Masked Methodology for Tibetan Spelling Correction covering Multi-Level Error with Data Augmentation** [[paper](https://arxiv.org/abs/2505.08037)]
- [2025] **Rethinking Repetition Problems of LLMs in Code Generation** [[paper](https://arxiv.org/abs/2505.10402)]
- [2025] **Reconstructing Syllable Sequences in Abugida Scripts with Incomplete Inputs** [[paper](https://arxiv.org/abs/2505.11008)]
- [2025] **GPT Editors, Not Authors: The Stylistic Footprint of LLMs in Academic Preprints** [[paper](https://arxiv.org/abs/2505.17327)]
- [2025] **CEC-Zero: Chinese Error Correction Solution Based on LLM** [[paper](https://arxiv.org/abs/2505.09082)]
- [2025] **Automated Essay Scoring Incorporating Annotations from Automated Feedback Systems** [[paper](https://arxiv.org/abs/2505.22771)]
- [2025] **Unveiling the Impact of Multimodal Features on Chinese Spelling Correction: From Analysis to Design** [[paper](https://arxiv.org/abs/2504.07661)] [[code](https://github.com/iioSnail/NamBert)]
- [2025] **RAIR: Retrieval-Augmented Iterative Refinement for Chinese Spelling Correction** [[paper](https://arxiv.org/abs/2504.18938)]
- [2025] **TextInVision: Text and Prompt Complexity Driven Visual Text Generation Benchmark** [[paper](https://arxiv.org/abs/2503.13730)]
- [2025] **AxBERT: An Interpretable Chinese Spelling Correction Method Driven by Associative Knowledge Network** [[paper](https://arxiv.org/abs/2503.02255)]
- [2025] **SpellRing: Recognizing Continuous Fingerspelling in American Sign Language using a Ring** [[paper](https://arxiv.org/abs/2502.10830)]
- [2025] **Chinese Spelling Correction: A Comprehensive Survey of Progress, Challenges, and Opportunities** [[paper](https://arxiv.org/abs/2502.11508)]
- [2025] **A Training-free LLM-based Approach to General Chinese Character Error Correction** [[paper](https://arxiv.org/abs/2502.15266)]
- [2025] **Integration of LLM Quality Assurance into an NLG System** [[paper](https://arxiv.org/abs/2501.16078)]

##### 2024

- [2024] **ExecRepoBench: Multi-level Executable Code Completion Evaluation** [[paper](https://arxiv.org/abs/2412.11990)] [[project](https://execrepobench.github.io/}})]
- [2024] **Research on Domain-Specific Chinese Spelling Correction Method Based on Plugin Extension Modules** [[paper](https://arxiv.org/abs/2411.09884)]
- [2024] **Enhancing Character-Level Understanding in LLMs through Token Internal Structure Learning** [[paper](https://arxiv.org/abs/2411.17679)]
- [2024] **CNMBERT: A Model for Converting Hanyu Pinyin Abbreviations to Chinese Characters** [[paper](https://arxiv.org/abs/2411.11770)]
- [2024] **A Survey on Importance of Homophones Spelling Correction Model for Khmer Authors** [[paper](https://arxiv.org/abs/2411.10477)]
- [2024] **RingGesture: A Ring-Based Mid-Air Gesture Typing System Powered by a Deep-Learning Word Prediction Framework** [[paper](https://arxiv.org/abs/2410.18100)]
- [2024] **Retrieval Augmented Spelling Correction for E-Commerce Applications** [[paper](https://arxiv.org/abs/2410.11655)]
- [2024] **Neural spell-checker: Beyond words with synthetic data generation** [[paper](https://arxiv.org/abs/2410.23514)]
- [2024] **A Simple yet Effective Training-free Prompt-free Approach to Chinese Spelling Correction Based on Large Language Models** [[paper](https://arxiv.org/abs/2410.04027)]
- [2024] **EdaCSC: Two Easy Data Augmentation Methods for Chinese Spelling Correction** [[paper](https://arxiv.org/abs/2409.05105)]
- [2024] **A Coin Has Two Sides: A Novel Detector-Corrector Framework for Chinese Spelling Correction** [[paper](https://arxiv.org/abs/2409.04150)]
- [2024] **Improving the quality of Persian clinical text with a novel spelling correction system** [[paper](https://arxiv.org/abs/2408.03622)]
- [2024] **Refining Corpora from a Model Calibration Perspective for Chinese Spelling Correction** [[paper](https://arxiv.org/abs/2407.15498)]
- [2024] **PERCORE: A Deep Learning-Based Framework for Persian Spelling Correction with Phonetic Analysis** [[paper](https://arxiv.org/abs/2407.14789)]
- [2024] **Automatic Real-word Error Correction in Persian Text** [[paper](https://arxiv.org/abs/2407.14795)]
- [2024] **AraSpell: A Deep Learning Approach for Arabic Spelling Correction** [[paper](https://arxiv.org/abs/2405.06981)]
- [2024] **A Combination of BERT and Transformer for Vietnamese Spelling Correction** [[paper](https://arxiv.org/abs/2405.02573)]
- [2024] **Contextual Spelling Correction with Language Model for Low-resource Setting** [[paper](https://arxiv.org/abs/2404.18072)]
- [2024] **Mitigating Catastrophic Forgetting in Multi-domain Chinese Spelling Correction by Multi-stage Knowledge Transfer Framework** [[paper](https://arxiv.org/abs/2402.11422)]

##### 2023

- [2023] **GTA: Gated Toxicity Avoidance for LM Performance Preservation** [[paper](https://arxiv.org/abs/2312.06122)]
- [2023] **Multi-teacher Distillation for Multilingual Spelling Correction** [[paper](https://arxiv.org/abs/2311.11518)]
- [2023] **Eval-GCSC: A New Metric for Evaluating ChatGPT's Performance in Chinese Spelling Correction** [[paper](https://arxiv.org/abs/2311.08219)] [[code](https://github.com/ktlKTL/Eval-GCSC)]
- [2023] **XATU: A Fine-grained Instruction-based Benchmark for Explainable Text Updates** [[paper](https://arxiv.org/abs/2309.11063)] [[code](https://github.com/megagonlabs/xatu)]

[⬆ Back to top](#paper-list)

#### Interactive Writing

##### 2026

- [2026] **MindCopilot: Towards Formalizing and Evaluating Granular Human-LLM Co-Writing** [[paper](https://arxiv.org/abs/2605.23535)]

##### 2025

- [2025] **Reassessing Collaborative Writing Theories and Frameworks in the Age of LLMs: What Still Applies and What We Must Leave Behind** [[paper](https://arxiv.org/abs/2505.16254)]
- [2025] **Comparing Native and Non-native English Speakers' Behaviors in Collaborative Writing through Visual Analytics** [[paper](https://arxiv.org/abs/2502.18681)]

##### 2024

- [2024] **Deceptive Patterns of Intelligent and Interactive Writing Assistants** [[paper](https://arxiv.org/abs/2404.09375)]
- [2024] **A Design Space for Intelligent and Interactive Writing Assistants** [[paper](https://arxiv.org/abs/2403.14117)]
- [2024] **Evidence-centered Assessment for Writing with Generative AI** [[paper](https://arxiv.org/abs/2401.08964)]

##### 2023

- [2023] **Techniques for supercharging academic writing with generative AI** [[paper](https://arxiv.org/abs/2310.17143)]

[⬆ Back to top](#paper-list)

### Writing Planning & Structure

#### LLM Evaluation

##### 2025

- [2025] **Cultivating a productive sense of place: Heritage experience, wellbeing, and urban preservation in historic cities** *Wellbeing Space and Society* [[paper](https://doi.org/10.1016/j.wss.2025.100318)]
- [2025] **Speaking with Richard Rathbone** *Journal of West African History* [[paper](https://doi.org/10.14321/jwestafrihist.11.2.0159)]
- [2025] **Raphael Samuel and History at Ruskin College 1968–70** *History Workshop Journal* [[paper](https://doi.org/10.1093/hwj/dbaf033)]
- [2025] **Health and Healing on the Latter-day Saint Peripheries** *Utah Historical Quarterly* [[paper](https://doi.org/10.5406/26428652.93.1.03)]

##### 2024

- [2024] **A Case for Objects** *The American Historical Review* [[paper](https://dx.doi.org/10.1093/ahr/rhae356)]
- [2024] **Why Perfluorocarbon nanoparticles encounter bottlenecks in clinical translation despite promising oxygen carriers?** *European Journal of Pharmaceutics and Biopharmaceutics* [[paper](https://doi.org/10.1016/j.ejpb.2024.114292)]
- [2024] **Price of Service: The Economic and Political Conditions that Compelled Danbury and Connecticut's Bonuseers of 1932** *Connecticut History Review* [[paper](https://dx.doi.org/10.5406/26395991.63.1.02)]
- [2024] **Materializing Faith and Politics: The Unseen Power of the NCCS Pocket Constitution in American Religion** *Dialogue A Journal of Mormon Thought* [[paper](https://dx.doi.org/10.5406/15549399.57.2.03)]
- [2024] **Conclusion: Converging Paths and New Directions of Polish Migrant Families in Ireland** [[paper](https://doi.org/10.1007/978-3-031-54634-1_12)]
- [2024] **CT Integration by Design-Based Learning Perspective—Implementation Example of Digital Storytelling** [[paper](https://doi.org/10.1007/978-981-96-0853-9_8)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2023

- [2023] **End-to-end Story Plot Generator** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.08796)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **Recent Articles** *The Scriblerian and the Kit-Cats* [[paper](https://doi.org/10.5325/scriblerian.59.1.0062)]
- [2026] **Collective Narration and the Politicization of Climate Distress** *ISLE Interdisciplinary Studies in Literature and Environment* [[paper](https://doi.org/10.1093/isle/isag038)]
- [2026] **Joseph Smith as the Book of Mormon's Managing Editor** *Journal of Mormon History* [[paper](https://doi.org/10.5406/24736031.52.3.04)]
- [2026] **A Theory of Narrative Reinterpretability: Controlled Ambiguity, Value Vector Interference, and Temporal Reconstruction** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20734252)]
- [2026] **A Selection from Award-Winning UFVA Films (2022–2023)** *Journal of Film and Video* [[paper](https://doi.org/10.5406/19346018.78.2.03)]

##### 2025

- [2025] **Reflection-AI: augmenting creativity or compromising authenticity? Reflections on using generative AI in audio education** *Frontiers in Communication* [[paper](https://doi.org/10.3389/fcomm.2025.1613254)]
- [2025] **Generational Detectives** *M/C Journal* [[paper](https://doi.org/10.5204/mcj.3136)]
- [2025] **Graduate Career Allyship: How Mentors and Programs Can Support Students** *American Music* [[paper](https://doi.org/10.5406/19405103.43.1.2.02)]
- [2025] **Farrokh Ghaffari travels: aesthetic convergences and institutional formations** *Screen* [[paper](https://doi.org/10.1093/screen/hjaf034)]

##### 2024

- [2024] **The Applied Sci-Fi Project, Center for Science and the Imagination, Arizona State University, Tempe, Arizona, United States (online event), May 2022–June 2023** *Utopian Studies* [[paper](https://doi.org/10.5325/utopianstudies.35.2-3.0794)]
- [2024] **Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.13575)]
- [2024] **Environmental Emotions: Tracking Affects on Page and Screen, Ecocritical Network for Scandinavian Studies (ENSCAN), University of Helsinki, Helsinki, Finland, June 13–14, 2023** *Utopian Studies* [[paper](https://doi.org/10.5325/utopianstudies.35.2-3.0801)]
- [2024] **Editor’s Comment** *Studies in the American Short Story* [[paper](https://doi.org/10.5325/studamershorstor.5.2.v)]
- [2024] **DataNarrative: Automated Data-Driven Storytelling with Visualizations and Texts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.05346)]
- [2024] **The Gillham Abduction Story: Constructing an Alternative Narrative** *Journal of the Illinois State Historical Society (1998-)* [[paper](https://doi.org/10.5406/23283335.117.1.04)]
- [2024] **Translated Italian Fiction in the United States, 1949–1972: Modernity, Modernism, and Literary Innovation** *Italian American Review* [[paper](https://doi.org/10.5406/26902451.14.2.01)]
- [2024] **Great Books and True Religion: The Relief Society Literature Curriculum, 1914–1970** *Journal of Mormon History* [[paper](https://doi.org/10.5406/24736031.50.1.04)]
- [2024] **Earth to Tables Legacies: Multimedia Food Conversations across Generations and Cultures** *Journal of American Folklore* [[paper](https://doi.org/10.5406/15351882.137.546.14)]

##### 2023

- [2023] **Editors’ Note** *The F Scott Fitzgerald Review* [[paper](https://dx.doi.org/10.5325/fscotfitzrevi.21.vi)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2024

- [2024] **Natural language processing in healthcare: Unlocking insights from clinical data** [[paper](https://doi.org/10.70593/978-81-984306-1-8_5)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2025

- [2025] **Seowriting AI Coupon Code SKV25 Get 25% Off on All Plans** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17641391)]
- [2025] **Omi AI Discount Code : (ARCHANA) – Exclusive 10% Discount On Products** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17641927)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2024

- [2024] **Edward W. Klink III. The Beginning and End of All Things: A Biblical Theology of Creation and New Creation** *Bulletin for Biblical Research* [[paper](https://doi.org/10.5325/bullbiblrese.34.3.0396)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **Reconstructing Persistent Worlds from Narratives for Narrative-Grounded Interactive Experiences** [[paper](https://arxiv.org/abs/2608.04037)]
- [2026] **From Style to Story: A Curriculum Learning Approach for Imitative Novel Generation** *Underline Science Inc.* [[paper](https://doi.org/10.48448/pqyn-5c40)]
- [2026] **Artificial Intelligence and Machine Learning in Robotic Surgery** [[paper](https://doi.org/10.1201/9781003655121-15)]
- [2026] **AI – supported Digital Storytelling** *Journal of Technology-Integrated Lessons and Teaching* [[paper](https://doi.org/10.13001/jtilt.v5i1.10293)]
- [2026] **A Continuous-Time Markov Chain Framework for Insertion Language Models** [[paper](https://arxiv.org/abs/2606.10199)]
- [2026] **Domain-Adaptable Reinforcement Learning for Code Generation with Dense Rewards** [[paper](https://arxiv.org/abs/2605.21180)]
- [2026] **Planning Beyond Text: Graph-based Reasoning for Complex Narrative Generation** [[paper](https://arxiv.org/abs/2604.21253)]
- [2026] **From World-Gen to Quest-Line: A Dependency-Driven Prompt Pipeline for Coherent RPG Generation** [[paper](https://arxiv.org/abs/2604.25482)]
- [2026] **Dont Stop Early: Scalable Enterprise Deep Research with Controlled Information Flow and Evidence-Aware Termination** [[paper](https://arxiv.org/abs/2604.24978)]
- [2026] **QChunker: Learning Question-Aware Text Chunking for Domain RAG via Multi-Agent Debate** [[paper](https://arxiv.org/abs/2603.11650)]
- [2026] **Prioritizing Progress over Perfection: Finding Excellence through Grace and Graciousness** *Plastic & Reconstructive Surgery* [[paper](https://doi.org/10.1097/prs.0000000000012563)]
- [2026] **Lessons from Real-World Deployment of a Cognition-Preserving Writing Tool: Students Actively Engage with Critical Thinking and Planning Affordances** [[paper](https://arxiv.org/abs/2603.15777)]
- [2026] **Envisioning Auckland 2050: Insights from Emerging Scholars for a Thriving Future** *Rangahau Aranga AUT Graduate Review* [[paper](https://doi.org/10.24135/rangahau-aranga.v5i1.336)]
- [2026] **“Play the Long Game”** *The Public Historian* [[paper](https://doi.org/10.1525/tph.2026.48.1.8)]
- [2026] **Receipts for Wet-Lab Claims: Proof-Carrying Experiment Logs for AI-Designed Antibiotics** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18521719)]
- [2026] **Ideamap AI Promo Code (ARCHA20) Unlock 15% Discount On All Plans** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18506056)]
- [2026] **Detecting Cognitive Signatures in Typing Behavior for Non-Intrusive Authorship Verification** [[paper](https://arxiv.org/abs/2603.00177)]
- [2026] **Web Retrieval-Aware Chunking (W-RAC) for Efficient and Cost-Effective Retrieval-Augmented Generation Systems** [[paper](https://arxiv.org/abs/2604.04936)]
- [2026] **UK Seagrass 2025: Evidence, Action and Priorities. Insights from the UK Seagrass Symposium.** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.31802287)]
- [2026] **The Relevance of the FCC in Contemporary Media Culture** *Journal of Film and Video* [[paper](https://doi.org/10.5406/19346018.78.2.05)]
- [2026] **Lead from the Wild** *Nursing Management* [[paper](https://doi.org/10.1097/nmg.0000000000000328)]
- [2026] **ICARP IV Research Priority Team (RPT) 5. Final Report : Co-Production and Indigenous-led Arctic Research** *Cork Open Research Archive (University College Cork, Ireland)* [[paper](https://hdl.handle.net/10468/18670)]
- [2026] **Getting Person‐Centred Fundamental Care Right: Past Discourse and Future Directions** *Journal of Advanced Nursing* [[paper](https://doi.org/10.1111/jan.70485)]
- [2026] **From Biased Chatbots to Biased Agents: Examining Role Assignment Effects on LLM Agent Robustness** [[paper](https://arxiv.org/abs/2602.12285)]

##### 2025

- [2025] **“Six Faces of Globalization: Who Wins, Who Loses, and Why It Matters”, Anthea Roberts and Nicholas Lamp, Harvard University Press, 2021: overview** *Qualitative Research in Financial Markets* [[paper](https://doi.org/10.1108/qrfm-11-2025-372)]
- [2025] **SlideGen: Collaborative Multimodal Agents for Scientific Slide Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.04529)]
- [2025] **New Works Development and Student Learning Outcomes** *Theatre and Performance Notes and Counternotes* [[paper](https://doi.org/10.5325/tpnc.2.2.0224)]
- [2025] **ImageTalk: Designing a Multimodal AAC Text Generation System Driven by Image Recognition and Natural Language Generation** [[paper](https://arxiv.org/abs/2512.09610)]
- [2025] **Designing Oncology Care to Meet the Needs of a Growing Patient Population** *Oncology Times* [[paper](https://doi.org/10.1097/01.cot.0000000000000279)]
- [2025] **Between Here and There: Creating the Political Economy of Mexican Migration, 1900–1942** *Labor Studies in Working-Class History of the Americas* [[paper](https://doi.org/10.1215/15476715-11978162)]
- [2025] **Smart and inclusive tourism in Bukhara: towards accessibility in heritage city** *Frontiers in Sports and Active Living* [[paper](https://doi.org/10.3389/fspor.2025.1624663)]
- [2025] **From Emergence to Planning: A Triangle Framework for Scalable, Controllable Interactive Storytelling** *Proceedings of the AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment* [[paper](https://doi.org/10.1609/aiide.v21i1.36858)]
- [2025] **Cleaning Up the SOAP: “IS SOAP REAL”** *Emergency Medicine News* [[paper](https://doi.org/10.1097/01.eem.0000000000000141)]
- [2025] **Artificial Intelligence in Clinical and Translational Science : From Bench Insights to Bedside Impact** *Clinical and Translational Science* [[paper](https://doi.org/10.1111/cts.70383)]
- [2025] **Large Language Models Hallucination: A Comprehensive Survey** [[paper](https://arxiv.org/abs/2510.06265)]
- [2025] **Deep Literature Survey Automation with an Iterative Workflow** [[paper](https://arxiv.org/abs/2510.21900)] [[code](https://github.com/HancCui/IterSurvey)]
- [2025] **Correction: Development of a comprehensive school anti-bullying logic model in Abu Dhabi: a multi-method participatory approach** *Frontiers in Public Health* [[paper](https://doi.org/10.3389/fpubh.2025.1708227)]
- [2025] **What Counts As Biblical Reception? A Response** *Religious Studies Review* [[paper](https://doi.org/10.1111/rsr.18157)]
- [2025] **Editorial: Enhancing collaboration between school professionals and local communities** *Journal of Professional Capital and Community* [[paper](https://doi.org/10.1108/jpcc-07-2025-181)]
- [2025] **Disability Inclusion in Undergraduate Medical Education** *Academic Medicine* [[paper](https://doi.org/10.1097/01.acm.0001124876.95117.bf)]
- [2025] **Tracing Singapore's Urban Futures: A Review Essay** *Singapore Journal of Tropical Geography* [[paper](https://doi.org/10.1111/sjtg.70024)]
- [2025] **SGSimEval: A Comprehensive Multifaceted and Similarity-Enhanced Benchmark for Automatic Survey Generation Systems** [[paper](https://arxiv.org/abs/2508.11310)]
- [2025] **Rethinking assumptions: navigating gender equality in the seafood sector** *Frontiers in Ocean Sustainability* [[paper](https://doi.org/10.3389/focsu.2025.1668370)]
- [2025] **Overview of literature on IPAs** [[paper](https://doi.org/10.4324/9781003244448-12)]
- [2025] **Multi-Story Floor Plan Generation from Building Volumetric Design Using Graph Neural Network** *Kalpa publications in computing* [[paper](https://doi.org/10.29007/7sdt)]
- [2025] **Compassion as Compass: Navigating 50 Years of Change and Challenge in Mental Health Nursing** *Journal of Advanced Nursing* [[paper](https://doi.org/10.1111/jan.70120)]
- [2025] **Capabilities of GPT-5 across critical domains: Is it the next breakthrough?** [[paper](https://arxiv.org/abs/2508.19259)]
- [2025] **A comprehensive taxonomy of hallucinations in Large Language Models** [[paper](https://arxiv.org/abs/2508.01781)]
- [2025] **Teaching Language Models To Gather Information Proactively** [[paper](https://arxiv.org/abs/2507.21389)]
- [2025] **From Past to Present: Cultural Infrastructure for Climate Adaptation – a Methodological Framework** *Figshare* [[paper](https://figshare.com/articles/thesis/From_Past_to_Present_Cultural_Infrastructure_for_Climate_Adaptation_a_Methodological_Framework/29554787)]
- [2025] **DeepWriter: A Fact-Grounded Multimodal Writing Assistant Based On Offline Knowledge Base** [[paper](https://arxiv.org/abs/2507.14189)]
- [2025] **SuperWriter: Reflection-Driven Long-Form Generation with Large Language Models** [[paper](https://arxiv.org/abs/2506.04180)]
- [2025] **Antifeminism as moral governance in India: caste, religion, and the political erasure of queer and Dalit lifeworlds** *Frontiers in Political Science* [[paper](https://doi.org/10.3389/fpos.2025.1611435)]
- [2025] **Cultural and historical heritage of Kharkiv: the electrotechnical building of NTU «KhPI»** *Studies in history and philosophy of science and technology* [[paper](https://doi.org/10.15421/272508)]
- [2025] **Comparative Qualitative Analysis of AI-Generated Student Videos: AI Tool vs Human Evaluation** [[paper](https://doi.org/10.22541/au.174648255.50691574/v1)]
- [2025] **The Company of Biologists Workshops: supporting our community and inspiring new science** *Development* [[paper](https://doi.org/10.1242/dev.204708)]
- [2025] **Explorer: Robust Collection of Interactable GUI Elements** [[paper](https://arxiv.org/abs/2504.09352)] [[code](https://github.com/varnelis/Explorer)]
- [2025] **VinaBench: Benchmark for Faithful and Consistent Visual Narratives** [[paper](https://arxiv.org/abs/2503.20871)]
- [2025] **RAPID: Efficient Retrieval-Augmented Long Text Generation with Writing Planning and Information Discovery** [[paper](https://arxiv.org/abs/2503.00751)]
- [2025] **Nurse in Pursuit** *Journal of Christian Nursing* [[paper](https://doi.org/10.1097/cnj.0000000000001265)]
- [2025] **A Survey on (M)LLM-Based GUI Agents** [[paper](https://arxiv.org/abs/2504.13865)]
- [2025] **A Scholar on Trial: Emotion, Criticism, and the Study of Mircea Eliade's Legacy** *Religious Studies Review* [[paper](https://doi.org/10.1111/rsr.17759)]
- [2025] **WhatELSE: Shaping Narrative Spaces at Configurable Level of Abstraction for AI-bridged Interactive Storytelling** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.18641)]
- [2025] **Unveiling Global Discourse Structures: Theoretical Analysis and NLP Applications in Argument Mining** [[paper](https://arxiv.org/abs/2502.08371)]
- [2025] **Script&amp;Shift: A Layered Interface Paradigm for Integrating Content Development and Rhetorical Strategy with LLM Writing Assistants** [[paper](https://arxiv.org/abs/2502.10638)]
- [2025] **CODESIM: Multi-Agent Code Generation and Problem Solving through Simulation-Driven Planning and Debugging** *NAACL 2025 Findings* [[paper](https://arxiv.org/abs/2502.05664)] [[project](https://kagnlp.github.io/codesim.github.io/)]
- [2025] **A Study on the Role of Social Media in Attracting Customers** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.14915675)]
- [2025] **A Cognitive Writing Perspective for Constrained Long-Form Text Generation** [[paper](https://arxiv.org/abs/2502.12568)] [[code](https://github.com/KaiyangWan/CogWriter)]
- [2025] **Surgical Silence: When Choosing Not to Operate Is the Wisest Course of Action** *Journal of Orthopaedic Case Reports* [[paper](https://doi.org/10.13107/jocr.2025.v15.i07.5748)]
- [2025] **Out of the Darkness and Into the Light: Confronting the Global Challenges in Wound Education** *International Wound Journal* [[paper](https://doi.org/10.1111/iwj.70178)]
- [2025] **Marching Shoulder to Shoulder: New Life in the Connecticut Woman Suffrage Movement** *Connecticut History Review* [[paper](https://doi.org/10.5406/26395991.64.2.09)]
- [2025] **Environmental Stewardship and Confronting The Biodiversity Crisis** *Dialogue A Journal of Mormon Thought* [[paper](https://doi.org/10.5406/15549399.58.2.22)]
- [2025] **Armenians and The Church of Jesus Christ of Latter-day Saints: A Hauntological Exhibit** *Dialogue A Journal of Mormon Thought* [[paper](https://doi.org/10.5406/15549399.58.1.03)]

##### 2024

- [2024] **“My Work Is to Show That It’s So Much More Beautiful When You Can Mix”: An Interview With Kim Thúy** *Contemporary Women s Writing* [[paper](https://doi.org/10.1093/cww/vpae029)]
- [2024] **Generative AI in Multimodal User Interfaces: Trends, Challenges, and Cross-Platform Adaptability** [[paper](https://arxiv.org/abs/2411.10234)]
- [2024] **Eternal Calendar** *Common Knowledge* [[paper](https://doi.org/10.1215/0961754x-11416145)]
- [2024] **Developments in the Low Countries: The Interpretations of Original Sin of Schoonenberg and Schillebeeckx** *The Heythrop Journal* [[paper](https://doi.org/10.1111/heyj.14348)]
- [2024] **Cognitive Biases in Decision Making** [[paper](https://doi.org/10.22541/au.172685269.91673050/v1)]
- [2024] **A Fabulous Failure: The Clinton Presidency and the Transformation of American Capitalism** *Labor Studies in Working-Class History of the Americas* [[paper](https://dx.doi.org/10.1215/15476715-11225129)]
- [2024] **2024 Joint Address from the ASHP President and the Chief Executive Officer** *American Journal of Health-System Pharmacy* [[paper](https://dx.doi.org/10.1093/ajhp/zxae222)]
- [2024] **The Contrabands and Freedmen Cemetery Memorial of Alexandria, Virginia: A remembered, “forgotten,” and re‐remembered memory site** *The Journal of American Culture* [[paper](https://doi.org/10.1111/jacc.13582)]
- [2024] **Intelligent Artistic Typography: A Comprehensive Review of Artistic Text Design and Generation** [[paper](https://arxiv.org/abs/2407.14774)] [[code](https://github.com/williamyang1991/Awesome-Artistic-Typography)]
- [2024] **How to be a good mentor** *Cardiovascular Research* [[paper](https://doi.org/10.1093/cvr/cvae113)]
- [2024] **AutoSurvey: Large Language Models Can Automatically Write Surveys** [[paper](https://arxiv.org/abs/2406.10252)] [[code](https://github.com/AutoSurveys/AutoSurvey)]
- [2024] **Text-to-Video AI Is Here To Stay: What It Means for Mental Health** *Psychiatric News* [[paper](https://dx.doi.org/10.1176/appi.pn.2024.06.6.34)]
- [2024] **StoryVerse: Towards Co-authoring Dynamic Plot with LLM-based Character Simulation via Narrative Planning** [[paper](https://arxiv.org/abs/2405.13042)]
- [2024] **MapCoder: Multi-Agent Code Generation for Competitive Problem Solving** [[paper](https://arxiv.org/abs/2405.11403)] [[code](https://github.com/Md-Ashraful-Pramanik/MapCoder)]
- [2024] **D6.1 User stories usage scenarios and use case validation v1** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20286648)]
- [2024] **Corporate Communication Companion (CCC): An LLM-empowered Writing Assistant for Workplace Social Media** [[paper](https://arxiv.org/abs/2405.04656)]
- [2024] **Chameleon: Mixed-Modal Early-Fusion Foundation Models** [[paper](https://arxiv.org/abs/2405.09818)]
- [2024] **Addressing the global shortage of nurses: A call to arms** *Nursing and Health Sciences* [[paper](https://doi.org/10.1111/nhs.13130)]
- [2024] **Sankofa: Learning From the Past to Build the Future—Introduction to the Special Issue on Aging in Sub-Saharan Africa** *Innovation in Aging* [[paper](https://doi.org/10.1093/geroni/igae031)]
- [2024] **Looking back at International Radiation Protection Association 16: A tapestry of moments and milestones** *Radiation Protection and Environment* [[paper](https://doi.org/10.4103/rpe.rpe_26_24)]
- [2024] **Intentionally embracing emergence in leadership education** *New Directions for Student Leadership* [[paper](https://doi.org/10.1002/yd.20586)]
- [2024] **RoboScript: Code Generation for Free-Form Manipulation Tasks across Real and Simulation** [[paper](https://arxiv.org/abs/2402.14623)]
- [2024] **THE VERBAL IMAGE OF A MODERN TEENAGER (BASED ON THE STORY OF S. HRYDIN “NOT SUCH”)** *Culture of the Word* [[paper](https://doi.org/10.37919/0201-419x-2024.100.10)]
- [2024] **Scientists’ warning to humanity for long-term planetary thinking on biodiversity and humankind preservation, a cosmic perspective** *BioScience* [[paper](https://doi.org/10.1093/biosci/biad108)]
- [2024] **Rapid Assessment of COVID Evidence (RACE): Continuing Health Equity Research Beyond the Series** *Ethnicity & Disease* [[paper](https://doi.org/10.18865/ed.34.1.19)]
- [2024] **MM-LLMs: Recent Advances in MultiModal Large Language Models** [[paper](https://arxiv.org/abs/2401.13601)]
- [2024] **How does Generation Z tell the story of the Yellow River well?** *Advances in Social Science, Education and Humanities Research/Advances in social science, education and humanities research* [[paper](https://doi.org/10.2991/978-2-38476-277-4_42)]
- [2024] **Editor's Note** *Journal of the Illinois State Historical Society (1998-)* [[paper](https://doi.org/10.5406/23283335.117.4.01)]
- [2024] **A Just Energy Transition: Getting Decarbonisation Right in a Time of Crisis by Ed Atkins** *Global Environmental Politics* [[paper](https://doi.org/10.1162/glep_r_00755)]

##### 2023

- [2023] **Issues in Australian Foreign Policy January to June 2023** *Australian Journal of Politics & History* [[paper](https://dx.doi.org/10.1111/ajph.12957)]
- [2023] **Who holds power in decision making for young people's future?** *The Medical Journal of Australia* [[paper](https://doi.org/10.5694/mja2.52147)]
- [2023] **Who Will Advocate to Keep the Public Healthy? Establishing Competency-Based Advocacy Training for the Public Health Field** *Journal of Public Health Management and Practice* [[paper](https://doi.org/10.1097/phh.0000000000001839)]
- [2023] **Situated Critique of Education and the Future** [[paper](https://doi.org/10.4324/9781003279457-17)]
- [2023] **Sigrid Boysen, Review of Marie-Catherine Petersmann. When Environmental Protection and Human Rights Collide: The Politics of Conflict Management by Regional Courts** *European Journal of International Law* [[paper](https://dx.doi.org/10.1093/ejil/chad064)]
- [2023] **Reflections on the Impact of an Intergenerational Digital Storytelling Program on Changing Attitudes and Fostering Dialogue and Understanding across the Generations** *Social Sciences* [[paper](https://doi.org/10.3390/socsci12110606)]
- [2023] **Preface** *Small Axe A Caribbean Journal of Criticism* [[paper](https://dx.doi.org/10.1215/07990537-10899162)]
- [2023] **Improving Pacing in Long-Form Story Planning** [[paper](https://arxiv.org/abs/2311.04459)]
- [2023] **A framework for the Future Healthy Countdown 2030: tracking the health and wellbeing of children and young people to hold Australia to account** *The Medical Journal of Australia* [[paper](https://doi.org/10.5694/mja2.52145)]
- [2023] **uTalk: Bridging the Gap Between Humans and AI** [[paper](https://arxiv.org/abs/2310.02739)]
- [2023] **Are NLP Models Good at Tracing Thoughts: An Overview of Narrative Understanding** [[paper](https://arxiv.org/abs/2310.18783)]
- [2023] **Uneasy Partners: The Coming Together of Lindsay-Schaub Newspapers** *Journal of the Illinois State Historical Society (1998-)* [[paper](https://doi.org/10.5406/23283335.116.2.3.06)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **DiscoSign: Discourse-Aware Text to Sign Language Gloss Translation** *EMNLP 2026 Main Conference* [[paper](https://arxiv.org/abs/2609.02796)]
- [2026] **When Stories Evolve: Benchmarking LLM Storytelling Across Agent Architectures in Open-Ended World Simulations** [[paper](https://arxiv.org/abs/2608.15654)]
- [2026] **MigrationNarrate: A Dataset for Detection of Migration Narratives in YouTube Videos** [[paper](https://arxiv.org/abs/2608.20984)]
- [2026] **Internalizing Academic Writing Workflows for Introduction Generation via Struct-Aware Policy Learning** [[paper](https://arxiv.org/abs/2608.03138)]
- [2026] **Who's Behind It? Annotating and Extracting Conspiratorial Actors from German Telegram Posts** [[paper](https://arxiv.org/abs/2607.04962)]
- [2026] **Measuring How Students Rely on Generative AI in Academic Writing: Development and Multi-Source Validation of the Generative AI Reliance Types Scale (GenAI-RTS)** [[paper](https://arxiv.org/abs/2607.14301)]
- [2026] **Generative AI and linguistic diversity in academic writing and publishing: Perspectives from World Englishes** [[paper](https://arxiv.org/abs/2607.28505)]
- [2026] **When Context Misleads: Surprisal, Energy and Attention Entropy as Metrics of Coherence Illusions in LLMs** [[paper](https://arxiv.org/abs/2606.21203)]
- [2026] **Quantifying Media Representation Dynamics Across 25 Years of News Reporting on Policing-related Deaths** [[paper](https://arxiv.org/abs/2606.06812)]
- [2026] **Narrative-UFET: Narrative Generation for Ultra-Fine Entity Typing** [[paper](https://arxiv.org/abs/2606.27598)]
- [2026] **Information Terra: A Narrative-Anchored Semantic-First Projection of Document Embeddings** [[paper](https://arxiv.org/abs/2606.30824)]
- [2026] **From Prompts to Preferences: An Open-Source Platform for Generative AI-Enhanced Conjoint Analysis** [[paper](https://arxiv.org/abs/2606.12972)]
- [2026] **From 50K to 8.2 Million in 24 Hours: Vozinha's Algorithmic Consecration and the Multilingual Making of World Cup Visibility** [[paper](https://arxiv.org/abs/2606.19647)]
- [2026] **Evaluating Reasoning Fidelity in Visual Text Generation** *CVPR 2026 at the GRAIL-V* [[paper](https://arxiv.org/abs/2606.04479)]
- [2026] **Entity tracking emerges in sub-billion parameter language models and exceeds human performance in naturalistic narratives** [[paper](https://arxiv.org/abs/2608.18083)]
- [2026] **Does Finetuning with Scientific Data Increase Hallucinations? A Multi-domain Factuality Evaluation of LLMs** [[paper](https://arxiv.org/abs/2606.21359)]
- [2026] **Atomistic Language Models Understand and Generate Materials** [[paper](https://arxiv.org/abs/2606.21395)]
- [2026] **Not All That Is Fluent Is Factual: Investigating Hallucinations of Large Language Models in Academic Writing** [[paper](https://arxiv.org/abs/2605.04171)]
- [2026] **Mapping Discourse Reframing: A Multi-Layer Network Approach to Italian HPV Vaccine Discourse on X (2010-2024)** [[paper](https://arxiv.org/abs/2605.02629)]
- [2026] **Linear Semantic Segmentation for Low-Resource Spoken Dialects** [[paper](https://arxiv.org/abs/2605.06276)]
- [2026] **Cohesion-6K: An Arabic Dataset for Analyzing Social Cohesion and Conflict in Online Discourse** [[paper](https://arxiv.org/abs/2605.22447)]
- [2026] **Tracking the Temporal Dynamics of News Coverage of Catastrophic and Violent Events** [[paper](https://arxiv.org/abs/2604.14315)]
- [2026] **The Pragmatic Persona: Discovering LLM Persona through Bridging Inference** [[paper](https://arxiv.org/abs/2604.24079)] [[code](https://github.com/JiSoo-Yang/Persona_Bridging.git)]
- [2026] **Program Structure-aware Language Models: Targeted Software Testing beyond Textual Semantics** [[paper](https://arxiv.org/abs/2604.17715)]
- [2026] **From Intention to Text: AI-Supported Goal Setting in Academic Writing** [[paper](https://arxiv.org/abs/2604.15800)]
- [2026] **Semantic Shifts of Psychological Concepts in Scientific and Popular Media Discourse: A Distributional Semantics Analysis of Russian-Language Corpora** [[paper](https://arxiv.org/abs/2604.00017)]
- [2026] **Reddit After Roe: A Computational Analysis of Abortion Narratives and Barriers in the Wake of Dobbs** [[paper](https://arxiv.org/abs/2603.22566)]
- [2026] **PlayWrite: A Multimodal System for AI Supported Narrative Co-Authoring Through Play in XR** [[paper](https://arxiv.org/abs/2603.02366)]
- [2026] **Humans vs Vision-Language Models: A Unified Measure of Narrative Coherence** [[paper](https://arxiv.org/abs/2603.25537)] [[code](https://github.com/GU-CLASP/coherence-driven-humans)]
- [2026] **From Variance to Invariance: Qualitative Content Analysis for Narrative Graph Annotation** [[paper](https://arxiv.org/abs/2603.01930)]
- [2026] **An Agentic Approach to Generating XAI-Narratives** [[paper](https://arxiv.org/abs/2603.20003)]
- [2026] **Agenda-based Narrative Extraction: Steering Pathfinding Algorithms with Large Language Models** [[paper](https://arxiv.org/abs/2603.29661)]
- [2026] **A Causal Graph Approach to Oppositional Narrative Analysis** [[paper](https://arxiv.org/abs/2603.06135)]
- [2026] **TraceMem: Weaving Narrative Memory Schemata from User Conversational Traces** [[paper](https://arxiv.org/abs/2602.09712)] [[code](https://github.com/YimingShu-teay/TraceMem)]
- [2026] **Learned but Not Expressed: Capability-Expression Dissociation in Large Language Models** [[paper](https://arxiv.org/abs/2603.18013)]
- [2026] **CoLyricist: Enhancing Lyric Writing with AI through Workflow-Aligned Support** [[paper](https://arxiv.org/abs/2602.22606)]
- [2026] **What Are We Measuring in NLG? A Meta-Analysis of Evaluation Trends 2020-2025** [[paper](https://arxiv.org/abs/2601.07648)]
- [2026] **Top 10 Open Challenges Steering the Future of Diffusion Language Model and Its Variants** [[paper](https://arxiv.org/abs/2601.14041)]
- [2026] **TAIGR: Towards Modeling Influencer Content on Social Media via Structured, Pragmatic Inference** [[paper](https://arxiv.org/abs/2601.20032)]
- [2026] **Structured Episodic Event Memory** [[paper](https://arxiv.org/abs/2601.06411)]
- [2026] **PartisanLens: A Multilingual Dataset of Hyperpartisan and Conspiratorial Immigration Narratives in European Media** [[paper](https://arxiv.org/abs/2601.03860)]
- [2026] **Online Density-Based Clustering for Real-Time Narrative Evolution Monitorin** [[paper](https://arxiv.org/abs/2601.20680)]
- [2026] **LitVISTA: A Benchmark for Narrative Orchestration in Literary Text** [[paper](https://arxiv.org/abs/2601.06445)]

##### 2025

- [2025] **Siamese-Driven Optimization for Low-Resolution Image Latent Embedding in Image Captioning** [[paper](https://arxiv.org/abs/2512.08873)]
- [2025] **Mary, the Cheeseburger-Eating Vegetarian: Do LLMs Recognize Incoherence in Narratives?** [[paper](https://arxiv.org/abs/2512.07777)]
- [2025] **HybridQuestion: Human-AI Collaboration for Identifying High-Impact Research Questions** [[paper](https://arxiv.org/abs/2602.03849)]
- [2025] **Towards Improving Interpretability of Language Model Generation through a Structured Knowledge Discovery Approach** [[paper](https://arxiv.org/abs/2511.23335)]
- [2025] **The Shifting Landscape of Vaccine Discourse: Insights From a Decade of Pre- to Post-COVID-19 Vaccine Posts on Social Media** [[paper](https://arxiv.org/abs/2511.16832)]
- [2025] **Multimodal Peer Review Simulation with Actionable To-Do Recommendations for Community-Aware Manuscript Revisions** [[paper](https://arxiv.org/abs/2511.10902)]
- [2025] **Listening Between the Lines: Decoding Podcast Narratives with Language Modeling** [[paper](https://arxiv.org/abs/2511.05310)]
- [2025] **Grounded Visual Factualization: Factual Anchor-Based Finetuning for Enhancing MLLM Factual Consistency** [[paper](https://arxiv.org/abs/2511.10671)]
- [2025] **Enhancing Multimodal Misinformation Detection by Replaying the Whole Story from Image Modality Perspective** [[paper](https://arxiv.org/abs/2511.06284)]
- [2025] **Duality-based Mode Operations and Pyramid Multilayer Mapping for Rhetorical Modes** [[paper](https://arxiv.org/abs/2511.06601)]
- [2025] **Discourse Graph Guided Document Translation with Large Language Models** [[paper](https://arxiv.org/abs/2511.07230)]
- [2025] **Cross-Platform Digital Discourse Analysis of the Israel-Hamas Conflict: Sentiment, Topics, and Event Dynamics** [[paper](https://arxiv.org/abs/2601.02367)]
- [2025] **TypePilot: Leveraging the Scala Type System for Secure LLM-generated Code** [[paper](https://arxiv.org/abs/2510.11151)]
- [2025] **Reasoning Distillation and Structural Alignment for Improved Code Generation** [[paper](https://arxiv.org/abs/2510.17598)]
- [2025] **Head Pursuit: Probing Attention Specialization in Multimodal Transformers** *NeurIPS 2025* [[paper](https://arxiv.org/abs/2510.21518)]
- [2025] **GenQuest: An LLM-based Text Adventure Game for Language Learners** [[paper](https://arxiv.org/abs/2510.04498)]
- [2025] **Beating Harmful Stereotypes Through Facts: RAG-based Counter-speech Generation** [[paper](https://arxiv.org/abs/2510.12316)]
- [2025] **Joint Modeling of Entities and Discourse Relations for Coherence Assessment** [[paper](https://arxiv.org/abs/2509.04182)]
- [2025] **Integrating Text and Time-Series into (Large) Language Models to Predict Medical Outcomes** [[paper](https://arxiv.org/abs/2509.13696)]
- [2025] **IA aplicada al análisis del conflicto Irán-Israel: Mapeo de discursos en YouTube** [[paper](https://arxiv.org/abs/2510.00021)]
- [2025] **Framing Migration: A Computational Analysis of UK Parliamentary Discourse** [[paper](https://arxiv.org/abs/2509.14197)]
- [2025] **CognitiveSky: Scalable Sentiment and Narrative Analysis for Decentralized Social Media** [[paper](https://arxiv.org/abs/2509.11444)]
- [2025] **Cognitive alignment in cardiovascular AI: designing predictive models that think with, not just for, clinicians** *Frontiers in Cardiovascular Medicine* [[paper](https://doi.org/10.3389/fcvm.2025.1651324)]
- [2025] **Clustering Discourses: Racial Biases in Short Stories about Women Generated by Large Language Models** [[paper](https://arxiv.org/abs/2509.02834)]
- [2025] **A Survey on Retrieval And Structuring Augmented Generation with Large Language Models** [[paper](https://arxiv.org/abs/2509.10697)]
- [2025] **Semantic Anchoring in Agentic Memory: Leveraging Linguistic Structures for Persistent Conversational Context** [[paper](https://arxiv.org/abs/2508.12630)]
- [2025] **Chronological Passage Assembling in RAG framework for Temporal Question Answering** [[paper](https://arxiv.org/abs/2508.18748)]
- [2025] **Task Mode: Dynamic Filtering for Task-Specific Web Navigation using LLMs** [[paper](https://arxiv.org/abs/2507.14769)]
- [2025] **Multimodal Behavioral Patterns Analysis with Eye-Tracking and LLM-Based Reasoning** [[paper](https://arxiv.org/abs/2507.18252)]
- [2025] **StorySage: Conversational Autobiography Writing Powered by a Multi-Agent Framework** [[paper](https://arxiv.org/abs/2506.14159)]
- [2025] **If You Had to Pitch Your Ideal Software -- Evaluating Large Language Models to Support User Scenario Writing for User Experience Experts and Laypersons** [[paper](https://arxiv.org/abs/2506.23694)]
- [2025] **From Persona to Person: Enhancing the Naturalness with Multiple Discourse Relations Graph Learning in Personalized Dialogue Generation** [[paper](https://arxiv.org/abs/2506.11557)]
- [2025] **Detecting Narrative Shifts through Persistent Structures: A Topological Analysis of Media Discourse** [[paper](https://arxiv.org/abs/2506.14836)]
- [2025] **DeepOmni: Towards Seamless and Smart Speech Interaction with Adaptive Modality-Specific MoE** [[paper](https://arxiv.org/abs/2506.21864)] [[code](https://github.com/talkking/DeepTalk)]
- [2025] **XtraGPT: Context-Aware and Controllable Academic Paper Revision via Human-AI Collaboration** *ACL 2026* [[paper](https://arxiv.org/abs/2505.11336)] [[code](https://github.com/Xtra-Computing/XtraGPT)] [[project](https://huggingface.co/collections/Xtra-Computing/xtragpt)]
- [2025] **The Wisdom of Agent Crowds: A Human-AI Interaction Innovation Ignition Framework** [[paper](https://arxiv.org/abs/2505.06947)]
- [2025] **Removal of Hallucination on Hallucination: Debate-Augmented RAG** [[paper](https://arxiv.org/abs/2505.18581)] [[code](https://github.com/Huenao/Debate-Augmented-RAG)]
- [2025] **MultiHal: Multilingual Dataset for Knowledge-Graph Grounded Evaluation of LLM Hallucinations** [[paper](https://arxiv.org/abs/2505.14101)]
- [2025] **MedScore: Generalizable Factuality Evaluation of Free-Form Medical Answers by Domain-adapted Claim Decomposition and Verification** [[paper](https://arxiv.org/abs/2505.18452)]
- [2025] **Large Language Model Meets Constraint Propagation** [[paper](https://arxiv.org/abs/2505.24012)]
- [2025] **Knoll: Creating a Knowledge Ecosystem for Large Language Models** [[paper](https://arxiv.org/abs/2505.19335)]
- [2025] **Human-AI Collaboration or Academic Misconduct? Measuring AI Use in Student Writing Through Stylometric Evidence** [[paper](https://arxiv.org/abs/2505.08828)]
- [2025] **Examining Linguistic Shifts in Academic Writing Before and After the Launch of ChatGPT: A Study on Preprint Papers** [[paper](https://arxiv.org/abs/2505.12218)]
- [2025] **Enhancing Visual Reliance in Text Generation: A Bayesian Perspective on Mitigating Hallucination in Large Vision-Language Models** [[paper](https://arxiv.org/abs/2505.19498)]
- [2025] **Analyzing Biases in Political Dialogue: Tagging U.S. Presidential Debates with an Extended DAMSL Framework** [[paper](https://arxiv.org/abs/2505.19515)]
- [2025] **VIST-GPT: Ushering in the Era of Visual Storytelling with LLMs?** [[paper](https://arxiv.org/abs/2504.19267)]
- [2025] **Uncovering Conspiratorial Narratives within Arabic Online Content** [[paper](https://arxiv.org/abs/2504.14037)]
- [2025] **Talking Point based Ideological Discourse Analysis in News Events** [[paper](https://arxiv.org/abs/2504.07400)]
- [2025] **Stance-Driven Multimodal Controlled Statement Generation: New Dataset and Task** [[paper](https://arxiv.org/abs/2504.03295)]
- [2025] **Speculative Decoding for Verilog: Speed and Quality, All in One** [[paper](https://arxiv.org/abs/2503.14153)]
- [2025] **SCORE: Story Coherence and Retrieval Enhancement for AI Narratives** [[paper](https://arxiv.org/abs/2503.23512)]
- [2025] **SARGes: Semantically Aligned Reliable Gesture Generation via Intent Chain** [[paper](https://arxiv.org/abs/2503.20202)]
- [2025] **Narrative Context Protocol: An Open-Source Storytelling Framework for Generative AI** [[paper](https://arxiv.org/abs/2503.04844)]
- [2025] **Monitoring Decoding: Mitigating Hallucination via Evaluating the Factuality of Partial Response during Generation** [[paper](https://arxiv.org/abs/2503.03106)]
- [2025] **MaintainCoder: Maintainable Code Generation Under Dynamic Requirements** [[paper](https://arxiv.org/abs/2503.24260)] [[code](https://github.com/IAAR-Shanghai/MaintainCoder)]
- [2025] **Survey on Vision-Language-Action Models** [[paper](https://arxiv.org/abs/2502.06851)]
- [2025] **SCALAR: Scientific Citation-based Live Assessment of Long-context Academic Reasoning** [[paper](https://arxiv.org/abs/2502.13753)]
- [2025] **Enhancing RWKV-based Language Models for Long-Sequence Text Generation** [[paper](https://arxiv.org/abs/2502.15485)]
- [2025] **Context-Preserving Gradient Modulation for Large Language Models: A Novel Approach to Semantic Consistency in Long-Form Text Generation** [[paper](https://arxiv.org/abs/2502.03643)]
- [2025] **CORDIAL: Can Multimodal Large Language Models Effectively Understand Coherence Relationships?** [[paper](https://arxiv.org/abs/2502.11300)] [[project](https://aashish2000.github.io/CORDIAL/)]
- [2025] **Poles Retell Polish America's History** *Polish American Studies* [[paper](https://doi.org/10.5406/23300833.82.2.09)]
- [2025] **New Philadelphia and the Freedom Corridor** *Journal of the Illinois State Historical Society (1998-)* [[paper](https://doi.org/10.5406/23283335.118.1.06)]
- [2025] **Implicit Causality-biases in humans and LLMs as a tool for benchmarking LLM discourse capabilities** [[paper](https://arxiv.org/abs/2501.12980)]
- [2025] **Constructing Hydrosocialism while Fighting the Cold War** *Journal of Cold War Studies* [[paper](https://doi.org/10.1162/jcws.a.21)]
- [2025] **Consistency of Responses and Continuations Generated by Large Language Models on Social Media** [[paper](https://arxiv.org/abs/2501.08102)]
- [2025] **Chain of Grounded Objectives: Bridging Process and Goal-oriented Prompting for Code Generation** [[paper](https://arxiv.org/abs/2501.13978)]

##### 2024

- [2024] **PrefixLLM: LLM-aided Prefix Circuit Design** [[paper](https://arxiv.org/abs/2412.02594)]
- [2024] **Motion Generation Review: Exploring Deep Learning for Lifelike Animation with Manifold** [[paper](https://arxiv.org/abs/2412.10458)]
- [2024] **From Hallucinations to Facts: Enhancing Language Models with Curated Knowledge Graphs** [[paper](https://arxiv.org/abs/2412.18672)]
- [2024] **SAGEval: The frontiers of Satisfactory Agent based NLG Evaluation for reference-free open-ended text** [[paper](https://arxiv.org/abs/2411.16077)]
- [2024] **Interactive Cycle Model: The Linkage Combination among Automatic Speech Recognition, Large Language Models and Smart Glasses** [[paper](https://arxiv.org/abs/2411.10362)] [[code](https://github.com/brucewang123456789/GeniusTrail.git)]
- [2024] **Extracting narrative signals from public discourse: a network-based approach** [[paper](https://arxiv.org/abs/2411.00702)]
- [2024] **aiXcoder-7B: A Lightweight and Effective Large Language Model for Code Processing** [[paper](https://arxiv.org/abs/2410.13187)]
- [2024] **Towards Acyclic Preference Evaluation of Language Models via Multiple Evaluators** [[paper](https://arxiv.org/abs/2410.12869)]
- [2024] **LargePiG: Your Large Language Model is Secretly a Pointer Generator** [[paper](https://arxiv.org/abs/2410.11366)]
- [2024] **Function-Guided Conditional Generation Using Protein Language Models with Adapters** [[paper](https://arxiv.org/abs/2410.03634)]
- [2024] **Enhancing Text Generation in Joint NLG/NLU Learning Through Curriculum Learning, Semi-Supervised Training, and Advanced Optimization Techniques** [[paper](https://arxiv.org/abs/2410.13498)]
- [2024] **DPLM-2: A Multimodal Diffusion Protein Language Model** [[paper](https://arxiv.org/abs/2410.13782)]
- [2024] **Tell Me about the Worms!** *PAJ A Journal of Performance and Art* [[paper](https://dx.doi.org/10.1162/pajj_a_00724)]
- [2024] **Original Sin in the Context of Lonergan's Soteriology** *The Heythrop Journal* [[paper](https://dx.doi.org/10.1111/heyj.14347)]
- [2024] **Integrating Hierarchical Semantic into Iterative Generation Model for Entailment Tree Explanation** [[paper](https://arxiv.org/abs/2409.17757)]
- [2024] **Simplifying Scholarly Abstracts for Accessible Digital Libraries** [[paper](https://arxiv.org/abs/2408.03899)]
- [2024] **Are Large Language Models Capable of Generating Human-Level Narratives?** [[paper](https://arxiv.org/abs/2407.13248)]
- [2024] **Adaptive Contrastive Search: Uncertainty-Guided Decoding for Open-Ended Text Generation** [[paper](https://arxiv.org/abs/2407.18698)]
- [2024] **“To Save Our Brethren”: Mormons, Armenians, and the “Eastern Zion” in Ottoman Palestine and Beyond** *Journal of Mormon History* [[paper](https://dx.doi.org/10.5406/24736031.50.3.03)]
- [2024] **Reconsidering Sentence-Level Sign Language Translation** [[paper](https://arxiv.org/abs/2406.11049)]
- [2024] **Multi-Label Classification for Implicit Discourse Relation Recognition** [[paper](https://arxiv.org/abs/2406.04461)]
- [2024] **Modeling Comparative Logical Relation with Contrastive Learning for Text Generation** [[paper](https://arxiv.org/abs/2406.09095)]
- [2024] **Inclusivity in Large Language Models: Personality Traits and Gender Bias in Scientific Abstracts** [[paper](https://arxiv.org/abs/2406.19497)]
- [2024] **Hierarchical Context Pruning: Optimizing Real-World Code Completion with Repository-Level Pretrained Code LLMs** [[paper](https://arxiv.org/abs/2406.18294)] [[code](https://github.com/Hambaobao/HCP-Coder)]
- [2024] **End-to-end Text-to-SQL Generation within an Analytics Insight Engine** [[paper](https://arxiv.org/abs/2406.12104)]
- [2024] **Confabulation: The Surprising Value of Large Language Model Hallucinations** *ACL2024 main conference. 1 figure* [[paper](https://arxiv.org/abs/2406.04175)]
- [2024] **Can Large Language Models Generate High-quality Patent Claims?** [[paper](https://arxiv.org/abs/2406.19465)]
- [2024] **MemeMQA: Multimodal Question Answering for Memes via Rationale-Based Inferencing** *ACL* [[paper](https://arxiv.org/abs/2405.11215)]
- [2024] **Identifying Narrative Patterns and Outliers in Holocaust Testimonies Using Topic Modeling** [[paper](https://arxiv.org/abs/2405.02650)]
- [2024] **Exploration of Masked and Causal Language Modelling for Text Generation** [[paper](https://arxiv.org/abs/2405.12630)]
- [2024] **DEPTH: Discourse Education through Pre-Training Hierarchically** [[paper](https://arxiv.org/abs/2405.07788)] [[code](https://github.com/zbambergerNLP/depth.git)]
- [2024] **Analysing the Public Discourse around OpenAI's Text-To-Video Model 'Sora' using Topic Modeling** [[paper](https://arxiv.org/abs/2407.13071)]
- [2024] **GraSAME: Injecting Token-Level Structural Information to Pretrained Language Models via Graph-guided Self-Attention Mechanism** [[paper](https://arxiv.org/abs/2404.06911)]
- [2024] **LLMs in HCI Data Work: Bridging the Gap Between Information Retrieval and Responsible Research Practices** [[paper](https://arxiv.org/abs/2403.18173)]
- [2024] **Iterative Refinement of Project-Level Code Context for Precise Code Generation with Compiler Feedback** [[paper](https://arxiv.org/abs/2403.16792)]
- [2024] **CoUDA: Coherence Evaluation via Unified Data Augmentation** [[paper](https://arxiv.org/abs/2404.00681)]
- [2024] **CoCoST: Automatic Complex Code Generation with Online Searching and Correctness Testing** [[paper](https://arxiv.org/abs/2403.13583)]
- [2024] **Unlocking Structure Measuring: Introducing PDD, an Automatic Metric for Positional Discourse Coherence** [[paper](https://arxiv.org/abs/2402.10175)]
- [2024] **Fine-Tuned Language Models Generate Stable Inorganic Materials as Text** [[paper](https://arxiv.org/abs/2402.04379)]
- [2024] **Fine-Grained Modeling of Narrative Context: A Coherence Perspective via Retrospective Questions** [[paper](https://arxiv.org/abs/2402.13551)]
- [2024] **Diffusion Language Models Are Versatile Protein Learners** [[paper](https://arxiv.org/abs/2402.18567)] [[code](https://github.com/bytedance/dplm)]
- [2024] **Actor Identification in Discourse: A Challenge for LLMs?** [[paper](https://arxiv.org/abs/2402.00620)]
- [2024] **Globalizing Irish America: An Introduction** *Journal of American Ethnic History* [[paper](https://doi.org/10.5406/19364695.44.1.01)]

##### 2023

- [2023] **The life and times of the Murray cod By PaulHumphries, 1st edition, Clayton South, Victoria, Australia: CSIRO Publishing. 2023. xxiv + 230 pp. Price AUD $59.99 (paperback, also available as an eBook ). ISBN : 9781486312320** *Austral Ecology* [[paper](https://dx.doi.org/10.1111/aec.13458)]
- [2023] **A Guide to Evaluating the Experience of Media and Arts Technology** [[paper](https://arxiv.org/abs/2311.07490)]
- [2023] **OmniFill: Domain-Agnostic Form Filling Suggestions Using Multi-Faceted Context** [[paper](https://arxiv.org/abs/2310.17826)]
- [2023] **GraphextQA: A Benchmark for Evaluating Graph-Enhanced Large Language Models** [[paper](https://arxiv.org/abs/2310.08487)]
- [2023] **Emergent AI-Assisted Discourse: Case Study of a Second Language Writer Authoring with ChatGPT** [[paper](https://arxiv.org/abs/2310.10903)]
- [2023] **Discourse Structures Guided Fine-grained Propaganda Identification** [[paper](https://arxiv.org/abs/2310.18544)]
- [2023] **DeTiME: Diffusion-Enhanced Topic Modeling using Encoder-decoder based LLM** [[paper](https://arxiv.org/abs/2310.15296)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2026

- [2026] **EvoSpark: Endogenous Interactive Agent Societies for Unified Long-Horizon Narrative Evolution** [[paper](https://arxiv.org/abs/2604.12776)]

##### 2024

- [2024] **Human-Centered Design for AI-based Automatically Generated Assessment Reports: A Systematic Review** [[paper](https://arxiv.org/abs/2501.00081)]
- [2024] **Unfamiliar Finetuning Examples Control How Language Models Hallucinate** [[paper](https://arxiv.org/abs/2403.05612)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2024

- [2024] **Shaping integrity: why generative artificial intelligence does not have to undermine education** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2024.1471224)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **Charles Ives's Civil War** *Connecticut History Review* [[paper](https://doi.org/10.5406/26395991.65.1.04)]
- [2026] **Actively Pursuing Positive Peace** *The Pluralist* [[paper](https://doi.org/10.5406/19446489.21.1.01)]

##### 2025

- [2025] **Faith in Small Things: The RLDS Church, the New Left, and the Global 1970s** *Journal of Mormon History* [[paper](https://doi.org/10.5406/24736031.51.2.01)]

##### 2024

- [2024] **Family matters** *Evolution* [[paper](https://dx.doi.org/10.1093/evolut/qpae047)]
- [2024] **Curriculum, Archives, and the Digital Turn: The Italian American Experience and the Transnational Approach to Community-Based Learning** *Italian American Review* [[paper](https://doi.org/10.5406/26902451.14.2.03)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2026

- [2026] **Inaugural Address of the Incoming President: On Our Way** *American Journal of Health-System Pharmacy* [[paper](https://doi.org/10.1093/ajhp/zxag230)]

[⬆ Back to top](#paper-list)

### Evaluation & Quality

#### LLM Evaluation

##### 2026

- [2026] **Evaluating the Evaluators: Metric Reliability and Agreement in Text-to-Video Generation** [[paper](https://doi.org/10.1109/iccsc71566.2026.11650127)]
- [2026] **MMLNB: Multi-Modal Learning for Neuroblastoma subtyping classification assisted with textual description generation** *Biomedical Signal Processing and Control* [[paper](https://doi.org/10.1016/j.bspc.2026.110798)]
- [2026] **Towards Better Evaluation Metrics for Text-to-Motion Generation** [[paper](https://doi.org/10.1145/3774905.3794682)]
- [2026] **Towards Reliable Evaluation of Emotional Text Generation in LLMs: Human vs. Automatic Metrics** [[paper](https://doi.org/10.63317/554t7yighn5u)]
- [2026] **Natural language generation in healthcare: A review of methods and applications** *Journal of Biomedical Informatics* [[paper](https://doi.org/10.1016/j.jbi.2026.104997)]
- [2026] **Towards reliable evaluation of emotional text generation in LLMs : human vs. automatic metrics** *Ghent University Academic Bibliography (Ghent University)* [[paper](https://hdl.handle.net/1854/LU-01KJ5FJYKVBZ35PSQPHZHP2XPD)]
- [2026] **SVGauge: Towards Human-Aligned Evaluation for SVG Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-10185-3_15)]
- [2026] **Evolving Standards of NLP Evaluation: A Survey of Metrics for Text Generation and Understanding** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-19690-3_39)]
- [2026] **A generative AI-Driven framework integrating CNN-VLM-LLM for intelligent crop disease diagnosis and control strategy generation** *Computers and Electronics in Agriculture* [[paper](https://doi.org/10.1016/j.compag.2026.111475)]

##### 2025

- [2025] **Procedural Scene Programs for Open-Universe Scene Generation: LLM-Free Error Correction via Program Search** [[paper](https://doi.org/10.1145/3757377.3763930)]
- [2025] **Transformer-based large language foundation models for text generation: A comprehensive literature review for different languages and application domains** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2025.104477)]
- [2025] **VTLG: A vision-tactile-language grasp generation method oriented towards task** *Robotics and Computer-Integrated Manufacturing* [[paper](https://doi.org/10.1016/j.rcim.2025.103152)]
- [2025] **T23D-QA: An Open Dataset and Benchmark for Text-driven 3D Generation Quality Assessment** [[paper](https://doi.org/10.1145/3746027.3758302)]
- [2025] **Say It, See It: A Systematic Evaluation on Speech-Based 3D Content Generation Methods in Augmented Reality** [[paper](https://doi.org/10.1109/ismar-adjunct68609.2025.00069)]
- [2025] **Selection of Statistical, Embedding and Distance-Based Metrics for Evaluating LLMs in Text Generation Tasks** [[paper](https://doi.org/10.1109/resgenxai64788.2025.11344016)]
- [2025] **Prompt2Color: A prompt-based framework for image-derived color generation and visualization optimization** *Computers & Graphics* [[paper](https://doi.org/10.1016/j.cag.2025.104419)]
- [2025] **InkSpirit: An expert knowledge-driven approach for enhancing the visual logic of traditional Chinese painting text-to-image generation** *Computers & Graphics* [[paper](https://doi.org/10.1016/j.cag.2025.104330)]
- [2025] **IRAGKR:Iterative retrieval augmented generation with fine-grained knowledge refinement** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.131282)]
- [2025] **An approach to optimizing semantic consistency for text-to-digital human generation** *Engineering Applications of Artificial Intelligence* [[paper](https://doi.org/10.1016/j.engappai.2025.111909)]
- [2025] **A comprehensive study on factual consistency in LLMs for data-to-text generation** *Sadhana* [[paper](https://doi.org/10.1007/s12046-025-02860-5)]
- [2025] **A Comprehensive Survey on Text-to-Video Generation** *Chinese Journal of Electronics* [[paper](https://doi.org/10.23919/cje.2024.00.151)]
- [2025] **Automated Trustworthiness Oracle Generation for Machine Learning Text Classifiers** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3729376)]
- [2025] **“Are the current topic modeling evaluation metrics enough?” Mitigating the limitations of topic modeling evaluation metrics using a multi-perspective game theoretic approach** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.113634)]
- [2025] **Retrieval-Augmented Generation: Architecture, Techniques, and Evaluations** *Journal of modern technology and engineering.* [[paper](https://doi.org/10.62476/jmte.10142)]
- [2025] **Fuzz-Testing Meets LLM-Based Agents: An Automated and Efficient Framework for Jailbreaking Text-to-Image Generation Models** [[paper](https://doi.org/10.1109/sp61157.2025.00119)]
- [2025] **Dall-E in hand surgery: Exploring the utility of ChatGPT image generation** *Surgery Open Science* [[paper](https://doi.org/10.1016/j.sopen.2025.04.012)]
- [2025] **PanoDiT: Panoramic Videos Generation with Diffusion Transformer** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i10.33089)]
- [2025] **LegalT5-ABSA: a framework for aspect-based sentiment analysis of parties in legal cases using text-to-text transfer transformer** *International Journal of Data Science and Analytics* [[paper](https://doi.org/10.1007/s41060-025-00744-9)]
- [2025] **Enhancing text quality evaluation with integrating content security attributes** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.127234)]
- [2025] **Toward the Comprehensive Evaluation of Medical Text Generation by Large Language Models: Programmatic Metrics, Human Assessment, and Large Language Models Judgment** *Medicine Advances* [[paper](https://doi.org/10.1002/med4.70002)]
- [2025] **Exploring text-to-image generation models: Applications and cloud resource utilization** *Computers & Electrical Engineering* [[paper](https://doi.org/10.1016/j.compeleceng.2025.110194)]
- [2025] **Emotion Recognition and Generation: A Comprehensive Review of Face, Speech, and Text Modalities** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.06803)]
- [2025] **A Holistic Review of Image-to-Text Conversion: Techniques, Evaluation Metrics, Multilingual Captioning, Storytelling and Integration** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-025-03719-6)]
- [2025] **Text-Driven Complex 3D Shape Generation using GAN for Information Systems** *Springer proceedings in business and economics* [[paper](https://doi.org/10.1007/978-981-96-2548-2_10)]
- [2025] **Rethinking HTG Evaluation: Bridging Generation and Recognition** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-92089-9_12)]
- [2025] **Reference-free Evaluation Metrics for Text Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.12011)]
- [2025] **OpenGenAlign: A Preference Dataset and Benchmark for Trustworthy Reward Modeling in Open-Ended, Long-Context Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.13264)]
- [2025] **On the Capacity of Citation Generation by Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-1710-4_9)]
- [2025] **JoPA: Explaining Large Language Model’s Generation via Joint Prompt Attribution** [[paper](https://doi.org/10.18653/v1/2025.acl-long.1074)]
- [2025] **Image2Text2Image: A Novel Framework for Label-Free Evaluation of Image-to-Text Generation with Text-to-Image Diffusion Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-2071-5_30)]
- [2025] **From attributes to natural language: A survey and foresight on text-based person re-identification** *Information Fusion* [[paper](https://doi.org/10.1016/j.inffus.2024.102879)]
- [2025] **DialogGen: Multi-modal Interactive Dialogue System with Multi-turn Text-Image Generation** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.25)]
- [2025] **Decoding the Mystery: How Can LLMs Turn Text Into Cypher in Complex Knowledge Graphs?** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3567759)]
- [2025] **Context-Aware Topic Modeling and Intelligent Text Extraction Using Transformer-Based Architectures** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5275391)]
- [2025] **Ai-Powered Contextual 3d Environment Generation: A Systematic Review** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5355060)]

##### 2024

- [2024] **Show Me the World in My Language: Establishing the First Baseline for Scene-Text to Scene-Text Translation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-78113-1_21)]
- [2024] **On Channel Transforms to Enhance Reciprocity and Quantization in Physical-Layer Secret Key Generation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3523105)]
- [2024] **Legal Chunking: Evaluating Methods for Effective Legal Text Retrieval** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia241255)]
- [2024] **Investigating Large Language Models for Prompt-Based Open-Ended Question Generation in the Technical Domain** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-024-03464-2)]
- [2024] **ImproveYourVideos: Architectural Improvements for Text-to-Video Generation Pipeline** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3522510)]
- [2024] **Evaluation and Comparison of Open-Source LLMs Using Natural Language Generation Quality Metrics** [[paper](https://doi.org/10.1109/bigdata62323.2024.10825576)]
- [2024] **Automating high-quality concept banks: leveraging LLMs and multimodal evaluation metrics** *Computer Research and Modeling* [[paper](https://doi.org/10.20537/2076-7633-2024-16-7-1555-1567)]
- [2024] **Applying Generative AI to Create SOP, Reducing API Costs Through Prompt Compression and Evaluating LLM Responses with Tonic Validate RAG Metrics** [[paper](https://doi.org/10.1109/icuis64676.2024.10867024)]
- [2024] **Amphion: an Open-Source Audio, Music, and Speech Generation Toolkit** [[paper](https://doi.org/10.1109/slt61566.2024.10832255)]
- [2024] **TextFusion: Unveiling the power of textual semantics for controllable image fusion** *Information Fusion* [[paper](https://doi.org/10.1016/j.inffus.2024.102790)]
- [2024] **Skews in the Phenomenon Space Hinder Generalization in Text-to-Image Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73021-4_25)]
- [2024] **Routing Method for 5G NR-based V2X Single-Hop Communication Using SNR and Communication Failure-Based Metrics** [[paper](https://doi.org/10.1109/cscn63874.2024.10849729)]
- [2024] **Pattern-based quantum text watermarking: Securing digital content with next-Gen quantum techniques** *iScience* [[paper](https://doi.org/10.1016/j.isci.2024.111364)]
- [2024] **Integrating CLIP with Dynamic Memory Generative Adversarial Networks to Enhance Semantic Consistency in Text-to-Image Generation** [[paper](https://doi.org/10.1109/iccbd-ai65562.2024.00083)]
- [2024] **GenerateCT: Text-Conditional Generation of 3D Chest CT Volumes** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72986-7_8)]
- [2024] **Enhancing domain-specific text generation for power grid maintenance with P2FT** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-78078-y)]
- [2024] **Controllable Navigation Instruction Generation with Chain of Thought Prompting** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73397-0_3)]
- [2024] **Towards Better Open-Ended Text Generation: A Multicriteria Evaluation Framework** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.18653)]
- [2024] **Text Conditioned Generative Adversarial Networks Generating Images and Videos: A Critical Review** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-024-03289-z)]
- [2024] **Steganographic Text Generation Based on Large Language Models in Dialogue Scenarios** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-97-9437-9_37)]
- [2024] **PointLLM: Empowering Large Language Models to Understand Point Clouds** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72698-9_8)]
- [2024] **Innovation in clean energy from man-made wind and small-wind generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-74141-w)]
- [2024] **Gender and Ethnicity Bias of Text-to-Image Generative Artificial Intelligence in Medical Imaging, Part 1: Preliminary Evaluation** *Journal of Nuclear Medicine Technology* [[paper](https://doi.org/10.2967/jnmt.124.268332)]
- [2024] **FineMatch: Aspect-Based Fine-Grained Image and Text Mismatch Detection and Correction** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72673-6_26)]
- [2024] **Evaluating Text-to-Visual Generation with Image-to-Text Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72673-6_20)]
- [2024] **Enhancing Semantic Fidelity in Text-to-Image Synthesis: Attention Regulation in Diffusion Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73016-0_5)]
- [2024] **E.T. the Exceptional Trajectories: Text-to-Camera-Trajectory Generation with Character Awareness** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73235-5_26)]
- [2024] **Gender Bias Evaluation in Text-to-image Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.11358)]
- [2024] **CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.06072)]
- [2024] **T2V-CompBench: A Comprehensive Benchmark for Compositional Text-to-video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.14505)]
- [2024] **Open-Source Text-to-Image Models: Evaluation using Metrics and Human Perception** [[paper](https://dx.doi.org/10.1109/compsac61105.2024.00261)]
- [2024] **Addressing Bias in Text-to-Image Generation: A Review of Mitigation Methods** [[paper](https://doi.org/10.1109/icstsn61422.2024.10671230)]
- [2024] **Text Steganography Methods and their Influence in Malware: A Comprehensive Overview and Evaluation** [[paper](https://doi.org/10.1145/3658664.3659637)]
- [2024] **TCMBench: A Comprehensive Benchmark for Evaluating Large Language Models in Traditional Chinese Medicine** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.01126)]
- [2024] **RTRL: Relation-aware Transformer with Reinforcement Learning for Deep Question Generation** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2024.112120)]
- [2024] **Diffusion Models for Image Generation to Enhance Health Literacy** [[paper](https://dx.doi.org/10.1109/ichi61247.2024.00047)]
- [2024] **Visual question answering based evaluation metrics for text-to-image generation** [[paper](https://doi.org/10.1109/iscas58744.2024.10558259)]
- [2024] **Advancing Sentiment Analysis Through Emotionally-Agnostic Text Mining in Large Language Models (LLMS)** *Journal of Biosensors and Bioelectronics Research* [[paper](https://doi.org/10.47363/jbber/2024(2)118)]
- [2024] **A Survey On Text-to-3D Contents Generation In The Wild** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.09431)]
- [2024] **Procedural Level Generation in Educational Games From Natural Language Instruction** *IEEE Transactions on Games* [[paper](https://doi.org/10.1109/tg.2024.3392670)]
- [2024] **Image Generation using Generative Adversarial Network and Stable Diffusion** *Research Square* [[paper](https://dx.doi.org/10.21203/rs.3.rs-4231306/v1)]
- [2024] **Generative AI-Based Text Generation Methods Using Pre-Trained GPT-2 Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.01786)]
- [2024] **Criteria2Query 3.0: Leveraging generative large language models for clinical trial eligibility query generation** *Journal of Biomedical Informatics* [[paper](https://doi.org/10.1016/j.jbi.2024.104649)]
- [2024] **Text-to-Image Generation for Abstract Concepts** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i4.28122)]
- [2024] **MedAlign: A Clinician-Generated Dataset for Instruction Following with Electronic Medical Records** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i20.30205)]
- [2024] **Topic-Oriented Controlled Text Generation for Social Networks** *Journal of Signal Processing Systems* [[paper](https://doi.org/10.1007/s11265-023-01907-2)]
- [2024] **Large Language Models: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.06196)]
- [2024] **VLEU: a Method for Automatic Evaluation for Generalizability of Text-to-Image Models** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-main.618)]
- [2024] **Question Generation Capabilities of “Small" Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-70242-6_18)]
- [2024] **Latent representation discretization for unsupervised text style generation** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2024.103643)]
- [2024] **KorSmishing Explainer: A Korean-centric LLM-based Framework for Smishing Detection and Explanation Generation** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-industry.47)]
- [2024] **GPT-4V(ision) is a Human-Aligned Evaluator for Text-to-3D Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.04092)]
- [2024] **Evaluation Metrics for Automated Typographic Poster Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-56992-0_21)]
- [2024] **Evaluating Text Generation Model Performance by Combining Semantic Meaning and Word Order** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3426082)]
- [2024] **Development and Testing of Retrieval Augmented Generation in Large Language Models** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.4719185)]
- [2024] **Asymmetric Bias in Text-to-Image Generation with Adversarial Attacks** [[paper](https://dx.doi.org/10.18653/v1/2024.findings-acl.344)]
- [2024] **Assessing GPT-4 Generated Abstracts: Text Relevance and Detectors Based on Faithfulness, Expressiveness, and Elegance Principle** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-97-0837-6_12)]
- [2024] **AIGCIQA2023: A Large-Scale Image Quality Assessment Database for AI Generated Images: From the Perspectives of Quality, Authenticity and Correspondence** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-9119-8_5)]
- [2024] **A topic‐controllable keywords‐to‐text generator with knowledge base network** *CAAI Transactions on Intelligence Technology* [[paper](https://doi.org/10.1049/cit2.12280)]
- [2024] **A Survey on Natural Language Counterfactual Generation** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.276)]
- [2024] **A Strategy for Implementing Domain-Based Task Generation and Evaluation System Using Text-Text Generative Models** *Lecture notes in educational technology* [[paper](https://doi.org/10.1007/978-981-97-3883-0_3)]

##### 2023

- [2023] **Faithful AI in Medicine: A Systematic Review with Large Language Models and Beyond** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-3661764/v1)]
- [2023] **Amphion: An Open-Source Audio, Music and Speech Generation Toolkit** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.09911)]
- [2023] **Rethinking FID: Towards a Better Evaluation Metric for Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.09603)]
- [2023] **Probing Explicit and Implicit Gender Bias through LLM Conditional Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.00306)]
- [2023] **MDM: Meta diffusion model for hard-constrained text generation** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2023.111147)]
- [2023] **Hand Gesture Recognition Using MediaPipe and CNN for Indian Sign Language and Conversion to Speech Format for Indian Regional Languages** [[paper](https://doi.org/10.1109/csitss60515.2023.10334218)]
- [2023] **FusionFrames: Efficient Architectural Aspects for Text-to-Video Generation Pipeline** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.13073)]
- [2023] **Scalable Diffusion for Materials Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.09235)]
- [2023] **Diverse Diffusion: Enhancing Image Diversity in Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.12583)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2025

- [2025] **Sel3DCraft: Interactive Visual Prompts for User-Friendly Text-to-3D Generation** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3633875)]
- [2025] **A retrieval augmented generation based optimization approach for medical knowledge understanding and reasoning in large language models** *Array* [[paper](https://doi.org/10.1016/j.array.2025.100504)]
- [2025] **MedVH: Toward Systematic Evaluation of Hallucination for Large Vision Language Models in the Medical Context** *Advanced Intelligent Systems* [[paper](https://doi.org/10.1002/aisy.202500255)]
- [2025] **Notification Text Generation with Large Language Models** [[paper](https://doi.org/10.1109/siu66497.2025.11112125)]
- [2025] **Large Language Models for Automated Web-Form-Test Generation: An Empirical Study** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3735553)]
- [2025] **CriSPO: Multi-Aspect Critique-Suggestion-guided Automatic Prompt Optimization for Text Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i22.34575)]
- [2025] **Generative AI-based Phishing Text Generation Using Hybrid Prompt Design with Heuristic Algorithm for Multimodal Phishing Detection** *International journal of intelligent engineering and systems* [[paper](https://doi.org/10.22266/ijies2025.0331.36)]
- [2025] **RiTTA: Modeling Event Relations in Text-to-Audio Generation** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.173)]

##### 2024

- [2024] **LLM-Assisted Generation of SWRL Rules from Natural Language** [[paper](https://doi.org/10.1109/aixdke63520.2024.00008)]
- [2024] **Towards Dataset-Scale and Feature-Oriented Evaluation of Text Summarization in Large Language Model Prompts** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://arxiv.org/abs/2407.12192)]
- [2024] **ChatGPT4PCG 2 Competition: Prompt Engineering for Science Birds Level Generation** [[paper](https://doi.org/10.1109/cog60054.2024.10645641)]
- [2024] **Exploring the Potential of Novel Image-to-Text Generators as Prompt Engineers for CivitAI Models** [[paper](https://doi.org/10.1109/iiai-aai63651.2024.00118)]
- [2024] **Can Prompt Modifiers Control Bias? A Comparative Analysis of Text-to-Image Generative Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.05602)]
- [2024] **Exploring the Impact of the Output Format on the Evaluation of Large Language Models for Code Translation** [[paper](https://arxiv.org/abs/2403.17214)]
- [2024] **Divide and Conquer Radiology Report Generation via Observation Level Fine-grained Pretraining and Prompt Tuning** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.433)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **Understanding Tradeoffs in Clinical Text Extraction: Prompting, Retrieval-Augmented Generation, and Supervised Learning on Electronic Health Records** *Algorithms* [[paper](https://doi.org/10.3390/a19030215)]
- [2026] **SQL-to-Text Generation with Weighted-AST Few-Shot Prompting** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-6196-4_26)]
- [2026] **Accurate discharge summary generation using fine tuned large language models with self evaluation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-35552-z)]

##### 2025

- [2025] **Region-aware metric learning for few-shot detection of counterfeit cigarettes from packaging images** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.129456)]
- [2025] **A Text-to-tabular Approach to Generate Synthetic Patient Data using LLMs** [[paper](https://doi.org/10.1109/ichi64645.2025.00011)]
- [2025] **Performance evaluation of LLMs in the Text-to-SQL task in Portuguese** [[paper](https://doi.org/10.5753/sbsi.2025.246471)]
- [2025] **Large Language Models in Summarizing Radiology Report Impressions for Lung Cancer in Chinese: Evaluation Study** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/65547)]
- [2025] **GPT-4o in radiology: In-context learning based automatic generation of radiology impressions** *Natural Language Processing Journal* [[paper](https://doi.org/10.1016/j.nlp.2025.100145)]
- [2025] **Exploring Deep Learning and Generative AI Techniques in Automatic Text Summarization** [[paper](https://doi.org/10.23919/indiacom66777.2025.11115475)]
- [2025] **LegalViz: Legal Text Visualization by Text To Diagram Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.06147)]
- [2025] **Vision-Language Models for Design Concept Generation: An Actor–Critic Framework** *Journal of Mechanical Design* [[paper](https://doi.org/10.1115/1.4067619)]
- [2025] **The Effectiveness of Large Language Models in Transforming Unstructured Text to Standardized Formats** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3573030)]
- [2025] **Multimodal Knowledge-Infused VLM for Respiratory Disease Prediction and Clinical Report Generation** *IEEE Journal of Biomedical and Health Informatics* [[paper](https://doi.org/10.1109/jbhi.2025.3631264)]
- [2025] **DeepCRCEval: Revisiting the Evaluation of Code Review Comment Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-90900-9_3)]

##### 2024

- [2024] **Text-To-AMP: Antimicrobial Peptide Design Guided by Natural Text** [[paper](https://doi.org/10.1109/bibm62325.2024.10822829)]
- [2024] **Fast Prompt Alignment for Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.08639)]
- [2024] **Large language models-based metric for generative question answering systems** *IAES International Journal of Artificial Intelligence* [[paper](https://doi.org/10.11591/ijai.v14.i1.pp151-158)]
- [2024] **LLM-Based Expressive Text-to-Speech Synthesizer with Style and Timbre Disentanglement** [[paper](https://doi.org/10.1109/iscslp63861.2024.10800531)]
- [2024] **T2I-Scorer: Quantitative Evaluation on Text-to-Image Generation via Fine-Tuned Large Multi-Modal Models** [[paper](https://doi.org/10.1145/3664647.3680939)]
- [2024] **TnT-LLM: Text Mining at Scale with Large Language Models** [[paper](https://doi.org/10.1145/3637528.3671647)]
- [2024] **Seed-TTS: A Family of High-Quality Versatile Speech Generation Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.02430)]
- [2024] **Evaluating Quantized Llama 2 Models for IoT Privacy Policy Language Generation** *Future Internet* [[paper](https://doi.org/10.3390/fi16070224)]
- [2024] **Automatic Generation and Evaluation of Reading Comprehension Test Items with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.07720)]
- [2024] **Relation Extraction in Underexplored Biomedical Domains: A Diversity-optimized Sampling and Synthetic Data Generation Approach** *Computational Linguistics* [[paper](https://doi.org/10.1162/coli_a_00520)]
- [2024] **PrExMe! Large Scale Prompt Exploration of Open Source LLMs for Machine Translation and Summarization Evaluation** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.641)]
- [2024] **Optimizing Prompts Using In-Context Few-Shot Learning for Text-to-Image Generative Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2023.3348778)]
- [2024] **Opinerium: Subjective Question Generation Using Large Language Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3398553)]
- [2024] **Learning Personalized Alignment for Evaluating Open-ended Text Generation** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.737)]

##### 2023

- [2023] **Few-Shot Table-to-Text Generation with Structural Bias Attention** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-7022-3_31)]
- [2023] **Zero-shot Faithfulness Evaluation for Text Summarization with Foundation Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.11648)]
- [2023] **Investigating Personalization Methods in Text to Music Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.11140)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2024

- [2024] **Text-to-Image Synthesis: A Decade Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.16164)]
- [2024] **PoetryDiffusion: Towards Joint Semantic and Metrical Manipulation in Poetry Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i16.29787)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2025

- [2025] **HVEval: Towards Unified Evaluation of Human-Centric Video Generation and Understanding** [[paper](https://doi.org/10.1145/3746027.3758299)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2025

- [2025] **AI-driven generation of guzheng music from classical Chinese poetry: toward a new paradigm of creative practice in Chinese traditional Music** *Multimedia Systems* [[paper](https://doi.org/10.1007/s00530-025-02023-w)]
- [2025] **Fùxì: A Benchmark for Evaluating Language Models on Ancient Chinese Text Understanding and Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.15837)]

##### 2024

- [2024] **UPON: Urdu Poetry Generation Using Deep Learning: A Novel Approach and Evaluation** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3708535)]
- [2024] **Contextual Fine-Tuning of Language Models with Classifier-Driven Content Moderation for Text Generation** *Entropy* [[paper](https://doi.org/10.3390/e26121114)]
- [2024] **Decoding Decoded: Understanding Hyperparameter Effects in Open-Ended Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.06097)]
- [2024] **Once Upon a GPT-4: Enhancing Diversity in Automated Reading Comprehension Story Generation with Classic Tales** [[paper](https://doi.org/10.1109/icalt61570.2024.00063)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2025

- [2025] **Evaluating Medical Text Summaries Using Automatic Evaluation Metrics and LLM-as-a-Judge Approach: A Pilot Study** *Diagnostics* [[paper](https://doi.org/10.3390/diagnostics16010003)]
- [2025] **A Comparative Study of Decoding Strategies in Medical Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.13580)]
- [2025] **Generative artificial intelligence-based modified abstractive cross attention enabled sequence to sequence model for abstractive Hindi text summarization** *Engineering Applications of Artificial Intelligence* [[paper](https://doi.org/10.1016/j.engappai.2025.111478)]
- [2025] **Can LLMs Replace Human Evaluators? An Empirical Study of LLM-as-a-Judge in Software Engineering** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3728963)]
- [2025] **Optimizing Legal Text Summarization Through Dynamic Retrieval-Augmented Generation and Domain-Specific Adaptation** *Symmetry* [[paper](https://doi.org/10.3390/sym17050633)]
- [2025] **Integrating Knowledge Retrieval with Generation: A Comprehensive Survey of RAG Models in NLP** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202504.0351.v1)]
- [2025] **Current and future state of evaluation of large language models for medical summarization tasks** *npj Health Systems* [[paper](https://doi.org/10.1038/s44401-024-00011-2)]
- [2025] **Next-Generation Text Summarization: A T5-LSTM FusionNet Hybrid Approach for Psychological Data** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3540590)]
- [2025] **Kazakh Abstractive Summarization: Dataset, Model Evaluation, and Applications in Automated SEO Metadata Generation** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-96-5881-7_18)]
- [2025] **Exploring Text Similarity in Human and AI-Generated Scientific Abstracts: A Comprehensive Analysis** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3564867)]
- [2025] **Abstractive Text Summarization Berita Bahasa Indonesia Menggunakan Retrieval-Augmented Generation** *Jurnal Ilmu Komputer dan Sistem Informasi* [[paper](https://doi.org/10.24912/jiksi.v13i1.32861)]
- [2025] **A survey on chatbots and large language models: Testing and evaluation techniques** *Natural Language Processing Journal* [[paper](https://doi.org/10.1016/j.nlp.2025.100128)]

##### 2024

- [2024] **Survey on Abstractive Text Summarization: Dataset, Models, and Metrics** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.17165)]
- [2024] **Evaluating Relation Hallucination in Text Summarization: An Introduction to the Relation Hallucination Index** [[paper](https://doi.org/10.1145/3734947.3734958)]
- [2024] **Comparative Analysis of Pretrained Models for Text Classification, Generation and Summarization: A Detailed Analysis** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-78107-0_10)]
- [2024] **Assessing the Impact of Prompt Strategies on Text Summarization with Large Language Models** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-76273-4_4)]
- [2024] **Advancements in Natural Language Processing: Leveraging Transformer Models for Multilingual Text Generation** *Pacific Journal of Advanced Engineering Innovations* [[paper](https://doi.org/10.70818/pjaei.2024.v01i01.02)]
- [2024] **Evaluation of Question-Answering Based Text Summarization using LLM Invited Paper** [[paper](https://doi.org/10.1109/aitest62860.2024.00025)]
- [2024] **Ascle—A Python Natural Language Processing Toolkit for Medical Text Generation: Development and Evaluation Study** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/60601)]
- [2024] **Transformer Models for Brazilian Portuguese Question Generation: An Experimental Study** *Proceedings of the ... International Florida Artificial Intelligence Research Society Conference* [[paper](https://doi.org/10.32473/flairs.37.1.135334)]
- [2024] **Evaluating Consistency and Reasoning Capabilities of Large Language Models** [[paper](https://doi.org/10.1109/icdsis61070.2024.10594233)]
- [2024] **The Potential and Limitations of Large Language Models for Text Classification through Synthetic Data Generation** *INTERNATIONAL RESEARCH JOURNAL OF ENGINEERING AND APPLIED SCIENCES* [[paper](https://doi.org/10.55083/irjeas.2024.v12i02002)]
- [2024] **Machine-Learning Techniques for Effective Text Mining** [[paper](https://doi.org/10.1201/9781003461500-19)]
- [2024] **Development and Performance Evaluation of Text Summarization using Deep Learning and Natural Language Processing Techniques** [[paper](https://doi.org/10.1109/icict60155.2024.10544635)]
- [2024] **Biomedical text readability after hypernym substitution with fine-tuned large language models** *PLOS Digital Health* [[paper](https://doi.org/10.1371/journal.pdig.0000489)]
- [2024] **Automatic Extractive Text Summarization using Multiple Linguistic Features** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3656471)]
- [2024] **A survey on the dataset, techniques, and evaluation metric used for abstractive text summarization** *TELKOMNIKA (Telecommunication Computing Electronics and Control)* [[paper](https://doi.org/10.12928/telkomnika.v22i3.25512)]
- [2024] **A Comprehensive Survey on Evaluating Large Language Model Applications in the Medical Industry** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.15777)]
- [2024] **Contrastive Learning Penalized Cross-Entropy with Diversity Contrastive Search Decoding for Diagnostic Report Generation of Reduced Token Repetition** *Applied Sciences* [[paper](https://doi.org/10.3390/app14072817)]
- [2024] **LLMs as Narcissistic Evaluators: When Ego Inflates Evaluation Scores** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.753)]
- [2024] **End to End Urdu Abstractive Text Summarization With Dataset and Improvement in Evaluation Metric** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3377463)]
- [2024] **Can We Trust the Performance Evaluation of Uncertainty Estimation Methods in Text Summarization?** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.923)]
- [2024] **AXCEL: Automated eXplainable Consistency Evaluation using LLMs** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.878)]
- [2024] **APPLS: Evaluating Evaluation Metrics for Plain Language Summarization** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.519)]

##### 2023

- [2023] **Representation transfer and data cleaning in multi-views for text simplification** *Pattern Recognition Letters* [[paper](https://doi.org/10.1016/j.patrec.2023.11.011)]
- [2023] **FloodBrain: Flood Disaster Reporting by Web-based Retrieval Augmented Generation with an LLM** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.02597)]
- [2023] **DocLens: Multi-aspect Fine-grained Evaluation for Medical Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.09581)]
- [2023] **Text Summarization Using Large Language Models: A Comparative Study of MPT-7b-instruct, Falcon-7b-instruct, and OpenAI Chat-GPT Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.10449)]
- [2023] **Metric Ensembles For Hallucination Detection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.10495)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2025

- [2025] **RetriEVAL: Evaluating Text Generation with Contextualized Lexical Match** [[paper](https://doi.org/10.1145/3701551.3703581)]

##### 2024

- [2024] **Comparative analysis of paraphrasing performance of ChatGPT , GPT ‐3, and T5 language models using a new ChatGPT generated dataset: ParaGPT** *Expert Systems* [[paper](https://doi.org/10.1111/exsy.13699)]

##### 2023

- [2023] **Paraphrase Generation For Reading Comprehension** *SinkrOn* [[paper](https://doi.org/10.33395/sinkron.v8i4.12873)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2025

- [2025] **Automatic Generation of Scientific Articles Abstracts Based on Large Language Models** *Informatics and Automation* [[paper](https://doi.org/10.15622/ia.24.1.10)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports from Scratch with Agentic Framework** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i40.40734)]

##### 2025

- [2025] **Bridging Text and Video Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.04999)]
- [2025] **Evaluating Large Language Models: A Review of Metrics and Benchmarks** [[paper](https://doi.org/10.1109/sisy67000.2025.11205366)]
- [2025] **In-depth Analysis on Machine Learning Approaches** *ARO-The Scientific Journal of Koya University* [[paper](https://doi.org/10.14500/aro.12038)]
- [2025] **Cracking the clinical code: A scoping review on mechanistic interpretability in medical report generation** *Computational and Structural Biotechnology Reports* [[paper](https://doi.org/10.1016/j.csbr.2025.100066)]

##### 2024

- [2024] **From vision to text: A comprehensive review of natural image captioning in medical diagnosis and radiology report generation** *Medical Image Analysis* [[paper](https://doi.org/10.1016/j.media.2024.103264)]
- [2024] **Web Application for Retrieval-Augmented Generation: Implementation and Testing** *Electronics* [[paper](https://doi.org/10.3390/electronics13071361)]
- [2024] **A Survey of Cross-Modal Visual Content Generation** *IEEE Transactions on Circuits and Systems for Video Technology* [[paper](https://doi.org/10.1109/tcsvt.2024.3351601)]

##### 2023

- [2023] **Human Motion Generation: A Survey** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2023.3330935)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **MuseRAG++: a deep retrieval-augmented generation framework for semantic interaction and multi-modal reasoning in virtual museums** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-55700-9)]
- [2026] **Towards Efficient Evaluation Of Diffusion-Based Text-To-Video Generation Using Objective Quality Metrics** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20145933)]
- [2026] **Optimizing Retrieval-Augmented Generation (RAG) in clinical medicine: methods and performance evaluation** *Journal of the American Medical Informatics Association* [[paper](https://doi.org/10.1093/jamia/ocag056)]
- [2026] **CT-FineBench: A Diagnostic Fidelity Benchmark for Fine-Grained Evaluation of CT Report Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.24001)]
- [2026] **When Numbers Tell Half the Story: Human-Metric Alignment in Topic Model Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.01945)]
- [2026] **EVALUATING CHUNKING STRATEGIES FOR RETRIEVAL-AUGMENTED GENERATION IN OIL AND GAS ENTERPRISE DOCUMENTS** [[paper](https://arxiv.org/abs/2603.24556)]
- [2026] **Evaluation of Linguistic Consistency of LLM-Generated Text Personalization Using Natural Language Processing** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202602.1117.v1)]
- [2026] **A Scoping Review of Synthetic Data Generation by Language Models in Biomedical Research and Application: Data Utility and Quality Perspectives** *Journal of Healthcare Informatics Research* [[paper](https://arxiv.org/abs/2506.16594)]

##### 2025

- [2025] **A Systematic Literature Review of Retrieval-Augmented Generation: Techniques, Metrics, and Challenges** *Big Data and Cognitive Computing* [[paper](https://doi.org/10.3390/bdcc9120320)]
- [2025] **ELSA: A STYLE-ALIGNED DATASET FOR EMOTIONALLY INTELLIGENT LANGUAGE GENERATION** [[paper](https://doi.org/10.5121/csit.2025.152201)]
- [2025] **Assessing the potential of LLMs as crowdworkers for contextual information generation** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2025.104486)]
- [2025] **A scalable framework for evaluating multiple language models through cross-domain generation and hallucination detection** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-15203-5)]
- [2025] **Gender inclusive language generation framework: A reasoning approach with RAG and CoT** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.114092)]
- [2025] **Advancing Offline Handwritten Text Recognition: A Systematic Review of Data Augmentation and Generation Techniques** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.06275)]
- [2025] **A Perspective on Quality Evaluation for AI-Generated Videos** *Sensors* [[paper](https://doi.org/10.3390/s25154668)]
- [2025] **A New HOPE: Domain-agnostic Automatic Evaluation of Text Chunking** [[paper](https://arxiv.org/abs/2505.02171)]
- [2025] **Performance of diverse evaluation metrics in NLP-based assessment and text generation of consumer complaints** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.21623)]
- [2025] **WorldGenBench: A World-Knowledge-Integrated Benchmark for Reasoning-Driven Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.01490)]
- [2025] **What We Know About the Role of Large Language Models for Medical Synthetic Dataset Generation** *AI* [[paper](https://doi.org/10.3390/ai6060109)]
- [2025] **Contextual Contrastive Search for Improved Text Generations in Large Language Models** [[paper](https://doi.org/10.1109/incet64471.2025.11140308)]
- [2025] **A framework to assess clinical safety and hallucination rates of LLMs for medical text summarisation** *npj Digital Medicine* [[paper](https://doi.org/10.1038/s41746-025-01670-7)]
- [2025] **Bridging AI and Healthcare: A Scoping Review of Retrieval-Augmented Generation—Ethics, Bias, Transparency, Improvements, and Applications** *medRxiv* [[paper](https://doi.org/10.1101/2025.04.01.25325033)]
- [2025] **Vision-to-Music Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.21254)]
- [2025] **Challenges in Generating Accurate Text in Images: A Benchmark for Text-to-Image Models on Specialized Content** *Applied Sciences* [[paper](https://doi.org/10.3390/app15052274)]
- [2025] **Talk2Doc: A Patient Q A system using Retrieval-Augmented Generation with Weighted Knowledge Graphs and LLMs** [[paper](https://doi.org/10.65286/icic.v21i4.47743)]
- [2025] **Knowledge Distillation and Transformer-Based Framework for Automatic Spine CT Report Generation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3546131)]
- [2025] **Expert Multi-Agent Conversational System Using Retrieval-Augmented Generation and Dynamic Text-to-SQL for Government Transparency** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3635530)]
- [2025] **Evaluating Generative AI Models for Image-Text Modification** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3547677)]

##### 2024

- [2024] **Detection of AI-Generated Text** [[paper](https://doi.org/10.1109/icpids65698.2024.00032)]
- [2024] **CrysText: A Generative AI Approach for Text-Conditioned Crystal Structure Generation using LLM** *ChemRxiv* [[paper](https://doi.org/10.26434/chemrxiv-2024-gjhpq)]
- [2024] **From Natural Language to SQL: Review of LLM-based Text-to-SQL Systems** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.01066)]
- [2024] **Unleashing GPT‐3's Potential in Automatic Text Generation** [[paper](https://doi.org/10.1002/9781394248438.ch9)]
- [2024] **From text to multimodal: a survey of adversarial example generation in question answering systems** *Knowledge and Information Systems* [[paper](https://doi.org/10.1007/s10115-024-02199-z)]
- [2024] **A Text Intelligence-Based Approach for Automatic Generation of Fault Trees in Nuclear Power Plants** [[paper](https://doi.org/10.1115/icone31-134226)]
- [2024] **Check-Eval: A Checklist-based Approach for Evaluating Text Quality** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.14467)]
- [2024] **ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.18522)]
- [2024] **Bridging Modalities: A Survey of Cross-Modal Image-Text Retrieval** *Chinese journal of information fusion.* [[paper](https://doi.org/10.62762/cjif.2024.361895)]
- [2024] **Augmenting Large Language Models with Reverse Proxy Style Retrieval Augmented Generation for Higher Factual Accuracy** [[paper](https://doi.org/10.31219/osf.io/ma6cq)]
- [2024] **StructDiffusion: End-to-end intelligent shear wall structure layout generation and analysis using diffusion model** *Engineering Structures* [[paper](https://doi.org/10.1016/j.engstruct.2024.118068)]
- [2024] **Dialogues Are Not Just Text: Modeling Cognition for Dialogue Coherence Evaluation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i17.29819)]
- [2024] **Is This a Bad Table? A Closer Look at the Evaluation of Table Generation from Text** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-main.1239)]
- [2024] **Holistic Evaluation for Interleaved Text-and-Image Generation** [[paper](https://dx.doi.org/10.18653/v1/2024.emnlp-main.1228)]
- [2024] **DEBATE: Devil’s Advocate-Based Assessment and Text Evaluation** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.112)]
- [2024] **Bias and Fairness in Large Language Models: A Survey** *Computational Linguistics* [[paper](https://doi.org/10.1162/coli_a_00524)]

##### 2023

- [2023] **From Text to Maps: Automated Concept Map Generation Using Fine-tuned Large Language Model** [[paper](https://dx.doi.org/10.5753/sbie.2023.234749)]
- [2023] **Towards Verifiable Generation: A Benchmark for Knowledge-aware Language Model Attribution** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.05634)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2025

- [2025] **Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.164)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **VisionReward: Fine-Grained Multi-Dimensional Human Preference Learning for Image and Video Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i13.38107)]

##### 2025

- [2025] **Evaluation of StyleGAN-CLIP Models in Text-to-Image Generation of Faces** *Applied Sciences* [[paper](https://doi.org/10.3390/app15158692)]
- [2025] **LLM-Driven Data Generation and a Novel Soft Metric for Evaluating Text-to-SQL in Aviation MRO** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.13785)]
- [2025] **Text to Image Generation and Editing: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.02527)]
- [2025] **Image Regeneration: Evaluating Text-to-Image Model via Generating Identical Image with Multimodal Large Language Models** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i6.32651)]
- [2025] **EditBoard: Towards a Comprehensive Evaluation Benchmark for Text-Based Video Editing Models** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i15.33754)]
- [2025] **Diffusion Model-Based Image Editing: A Survey** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3541625)]

##### 2024

- [2024] **ChatGLM: A Family of Large Language Models from GLM-130B to GLM-4 All Tools** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.12793)]
- [2024] **Ask, Assess, and Refine: Rectifying Factual Consistency and Hallucination in LLMs with Metric-Guided Feedback Learning** [[paper](https://doi.org/10.18653/v1/2024.eacl-long.149)]

##### 2023

- [2023] **SingleInsert: Inserting New Concepts from a Single Image into Text-to-Image Models for Flexible Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.08094)]
- [2023] **ImagenHub: Standardizing the evaluation of conditional image generation models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.01596)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2025

- [2025] **SoulSearch: applying heuristic optimization to enhance text-to-image generation with personalized human-LMM collaboration** *Science China Information Sciences* [[paper](https://doi.org/10.1007/s11432-024-4564-6)]
- [2025] **Text Data Augmentation for Large Language Models: A Comprehensive Survey of Methods, Challenges, and Opportunities** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.18845)]
- [2025] **A Practical Application of Retrieval-Augmented Generation for Website-Based Chatbots: Combining Web Scraping, Vectorization, and Semantic Search** *Journal of Trends in Computer Science and Smart Technology* [[paper](https://doi.org/10.36548/jtcsst.2024.4.007)]

##### 2024

- [2024] **Dance-to-Music Generation with Encoder-based Textual Inversion** [[paper](https://doi.org/10.1145/3680528.3687562)]
- [2024] **Evaluating Large Language Model–Supported Instructions for Medication Use: First Steps Toward a Comprehensive Model** *Mayo Clinic Proceedings Digital Health* [[paper](https://doi.org/10.1016/j.mcpdig.2024.09.006)]
- [2024] **Evaluating Synthetic Data Generation from User Generated Text** *Computational Linguistics* [[paper](https://doi.org/10.1162/coli_a_00540)]
- [2024] **ConceptBed: Evaluating Concept Learning Abilities of Text-to-Image Diffusion Models** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i13.29371)]
- [2024] **SGDM: An Adaptive Style-Guided Diffusion Model for Personalized Text to Image Generation** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2024.3399075)]
- [2024] **How to use Language Models for Synthetic Text Generation in Cerebrovascular Disease-specific Medical Reports** [[paper](https://doi.org/10.18653/v1/2024.personalize-1.2)]

##### 2023

- [2023] **StyleBoost: A Study of Personalizing Text-to-Image Generation in Any Style using DreamBooth** [[paper](https://doi.org/10.1109/ictc58733.2023.10392676)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **A Survey of Multimodal Hallucination Evaluation and Detection** *International Journal of Computer Vision* [[paper](https://doi.org/10.1007/s11263-026-02756-9)]
- [2026] **Comprehensiveness Metrics for Automatic Evaluation of Factual Recall in Text Generation** [[paper](https://arxiv.org/abs/2510.07926)]

##### 2025

- [2025] **RAG Applications in Lightweight LLMs: Boosting Reliability for Text Generation in Railway** [[paper](https://doi.org/10.1109/icirt66379.2025.11216705)]
- [2025] **Retrieval Augmented Generation (RAG) using LLMs** [[paper](https://doi.org/10.1109/aicdmb64359.2025.11277692)]
- [2025] **Reinforced Retrieval-Augmented Generation in Large Language Models** [[paper](https://doi.org/10.1109/ijcnn64981.2025.11228816)]
- [2025] **Next-generation image captioning: A survey of methodologies and emerging challenges from transformers to Multimodal Large Language Models** *Natural Language Processing Journal* [[paper](https://doi.org/10.1016/j.nlp.2025.100159)]
- [2025] **Quantifying Bias in Text-to-Image Generative Models** *IEEE Transactions on Dependable and Secure Computing* [[paper](https://doi.org/10.1109/tdsc.2025.3572115)]
- [2025] **Evaluating Image Hallucination in Text-to-Image Generation with Question-Answering** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i25.34827)]

##### 2024

- [2024] **Offline Evaluation of Set-Based Text-to-Image Generation** [[paper](https://arxiv.org/abs/2410.17331)]
- [2024] **A Comparative Analysis of Text-Based Explainable Recommender Systems** [[paper](https://doi.org/10.1145/3640457.3688069)]
- [2024] **Report Generation from X-Ray imaging by Retrieval-Augmented Generation and improved Image-Text Matching** [[paper](https://doi.org/10.1109/ijcnn60899.2024.10650332)]
- [2024] **Evaluating emotional and subjective responses in synthetic art-related dialogues: A multi-stage framework with large language models** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2024.124524)]
- [2024] **CTGGAN: Controllable Text Generation with Generative Adversarial Network** *Applied Sciences* [[paper](https://doi.org/10.3390/app14073106)]
- [2024] **An Entity Extraction Pipeline for Medical Text Records Using Large Language Models: Analytical Study** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/54580)]
- [2024] **VeriScore: Evaluating the factuality of verifiable claims in long-form text generation** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.552)]
- [2024] **Advancing Retrieval-Augmented Generation with Inverted Question Matching for Enhanced QA Performance** *IEEE Access* [[paper](https://arxiv.org/abs/2501.02702)]

[⬆ Back to top](#paper-list)

#### NLP Metrics

##### 2026

- [2026] **SynopticBench: Evaluating Vision-Language Models on Generating Weather Forecast Discussions of the Future** [[paper](https://arxiv.org/abs/2604.16451)]
- [2026] **The attention mechanism for intelligent text generation of traditional cultural symbols in artistic design** *Applied Soft Computing* [[paper](https://doi.org/10.1016/j.asoc.2026.114733)]

##### 2025

- [2025] **Multimodal Arabic Captioning with Interpretable Visual Concept Integration** [[paper](https://arxiv.org/abs/2510.03295)]
- [2025] **Evaluation of a retrieval-augmented generation system using a Japanese Institutional Nuclear Medicine Manual and large language model-automated scoring** *Radiological Physics and Technology* [[paper](https://doi.org/10.1007/s12194-025-00941-y)]
- [2025] **Automated Question Generation for Arabic Texts** [[paper](https://doi.org/10.1109/icics65354.2025.11072964)]
- [2025] **Generation of Fundus Fluorescein Angiography Videos for Health Care Data Sharing** *JAMA Ophthalmology* [[paper](https://doi.org/10.1001/jamaophthalmol.2025.1419)]
- [2025] **Enhanced Retrieval-Augmented Generation Using Low-Rank Adaptation** *Applied Sciences* [[paper](https://doi.org/10.3390/app15084425)]
- [2025] **Advancing Bangla NLP: Transformer-Based Question Generation using Fine-Tuned LLM** [[paper](https://doi.org/10.1109/ecce64574.2025.11013206)]
- [2025] **Learning Evaluation Models From Large Language Models for Sequence Generation** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2025.3587460)]
- [2025] **Hybrid framework for automated generation of mammography radiology reports** *Computational and Structural Biotechnology Journal* [[paper](https://doi.org/10.1016/j.csbj.2025.07.018)]

##### 2024

- [2024] **Slit Lamp Report Generation and Question Answering: Development and Validation of a Multimodal Transformer Model with Large Language Model Integration** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/54047)]
- [2024] **Automatic text simplification for French: model fine-tuning for simplicity assessment and simpler text generation** *International Journal of Speech Technology* [[paper](https://doi.org/10.1007/s10772-024-10146-0)]
- [2024] **A Transformer-Based Model for Image Caption Generation with Memory Enhancement** [[paper](https://doi.org/10.1109/wiecon-ece64149.2024.10915030)]
- [2024] **Enhancing Chinese Dialogue Generation with Word–Phrase Fusion Embedding and Sparse SoftMax Optimization** *Systems* [[paper](https://doi.org/10.3390/systems12120516)]
- [2024] **Automated Literature Review Using NLP Techniques and LLM-Based Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2411.18583)]
- [2024] **Paragraph vs Sentence in Automatic Question Generation Fine-Tuning using Text-to-Text Transfer Transformer for Bahasa Indonesia** [[paper](https://doi.org/10.1109/icet64717.2024.10778465)]
- [2024] **Enhancing Social Media Accessibility: Automatic Alternative Text Generation in X by Image Captioning** [[paper](https://doi.org/10.1109/icset63729.2024.10775292)]
- [2024] **A transformer-based approach to Nigerian Pidgin text generation** *International Journal of Speech Technology* [[paper](https://doi.org/10.1007/s10772-024-10136-2)]
- [2024] **Multi-modal transformer architecture for medical image analysis and automated report generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-69981-5)]
- [2024] **Designing Prompts and Creating Cleaned Scientific Text for Retrieval Augmented Generation for More Precise Responses from Generative Large Language Models** [[paper](https://doi.org/10.1109/citds62610.2024.10791382)]
- [2024] **WRDScore: New Metric for Evaluation of Natural Language Generation Models** [[paper](https://doi.org/10.1109/opcs63516.2024.10720439)]
- [2024] **FFA-GPT: an automated pipeline for fundus fluorescein angiography interpretation and question-answer** *npj Digital Medicine* [[paper](https://doi.org/10.1038/s41746-024-01101-z)]
- [2024] **Cross-language Text Generation Using mBERT and XLM-R: English-Chinese Translation Task** [[paper](https://doi.org/10.1145/3662739.3672320)]
- [2024] **ICGA-GPT: report generation and question answering for indocyanine green angiography images** *British Journal of Ophthalmology* [[paper](https://doi.org/10.1136/bjo-2023-324446)]
- [2024] **EvaluLLM: LLM assisted evaluation of generative outputs** [[paper](https://doi.org/10.1145/3640544.3645216)]
- [2024] **Vision-Language Model for Generating Textual Descriptions From Clinical Images: Model Development and Validation Study** *JMIR Formative Research* [[paper](https://doi.org/10.2196/32690)]
- [2024] **High-quality Data-to-Text Generation for Severely Under-Resourced Languages with Out-of-the-box Large Language Models** [[paper](https://arxiv.org/abs/2402.12267)]
- [2024] **Classification and Generation of Arabic News Titles from Raw Text Based on an Encoder-Decoder Transformer Model (mT5)** *Research Square* [[paper](https://dx.doi.org/10.21203/rs.3.rs-3982909/v1)]
- [2024] **PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models** [[paper](https://arxiv.org/abs/2401.15042)]
- [2024] **How Reliable Are Automatic Evaluation Methods for Instruction-Tuned LLMs?** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.367)]
- [2024] **Enhancing diversity for logical table‐to‐text generation with mixture of experts** *Expert Systems* [[paper](https://doi.org/10.1111/exsy.13533)]
- [2024] **Distractor Generation Through Text-to-Text Transformer Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3361673)]
- [2024] **DIC-Transformer: interpretation of plant disease classification results using image caption generation technology** *Frontiers in Plant Science* [[paper](https://doi.org/10.3389/fpls.2023.1273029)]
- [2024] **Chest radiology report generation based on cross-modal multi-scale feature fusion** *Journal of Radiation Research and Applied Sciences* [[paper](https://doi.org/10.1016/j.jrras.2024.100823)]

##### 2023

- [2023] **Data-to-text generation using conditional generative adversarial with enhanced transformer** *Natural Language Engineering* [[paper](https://doi.org/10.1017/s1351324923000487)]
- [2023] **TRCaptionNet: A novel and accurate deep Turkish image captioning model with vision transformer based image encoders and deep linguistic text decoders** *TURKISH JOURNAL OF ELECTRICAL ENGINEERING & COMPUTER SCIENCES* [[paper](https://doi.org/10.55730/1300-0632.4035)]
- [2023] **Research on automatic pilot repetition generation method based on deep reinforcement learning** *Frontiers in Neurorobotics* [[paper](https://doi.org/10.3389/fnbot.2023.1285831)]
- [2023] **Automatic Answerability Evaluation for Question Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.12546)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2026

- [2026] **Learning Complementary Action Modeling from Automotive Maintenance Instructions** [[paper](https://arxiv.org/abs/2606.27808)]
- [2026] **From Relevance to Authority: Authority-aware Generative Retrieval in Web Search Engines** [[paper](https://arxiv.org/abs/2604.13468)]
- [2026] **TildeOpen LLM: Leveraging Curriculum Learning to Achieve Equitable Language Representation** [[paper](https://arxiv.org/abs/2603.08182)]
- [2026] **LFQA-HP-1M: A Large-Scale Human Preference Dataset for Long-Form Question Answering** [[paper](https://arxiv.org/abs/2602.23603)]

##### 2025

- [2025] **Deep Learning Techniques for Text-Based Emotional Response Generation: A Systematic Review** *IEEE Transactions on Affective Computing* [[paper](https://doi.org/10.1109/taffc.2025.3638957)]
- [2025] **FreshTab: Sourcing Fresh Data for Table-to-Text Generation Evaluation** [[paper](https://arxiv.org/abs/2510.13598)]
- [2025] **Assisting Research Proposal Writing with Large Language Models: Evaluation and Refinement** [[paper](https://arxiv.org/abs/2509.09709)]
- [2025] **Stick to Facts: Towards Fidelity-oriented Product Description Generation** [[paper](https://arxiv.org/abs/2503.08454)]
- [2025] **Can LLMs Automate Fact-Checking Article Writing?** [[paper](https://arxiv.org/abs/2503.17684)] [[code](https://github.com/mbzuai-nlp/qraft.git)]
- [2025] **Benchmarking Music Generation Models and Metrics via Human Preference Studies** [[paper](https://arxiv.org/abs/2506.19085)]
- [2025] **ExaGPT: Example-Based Machine-Generated Text Detection for Human Interpretability** [[paper](https://arxiv.org/abs/2502.11336)]
- [2025] **Semantic Evaluation of Multilingual Data-to-Text Generation via NLI Fine-Tuning: Precision, Recall and F1 scores** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.542)]
- [2025] **MeDiSumQA: Patient-Oriented Question-Answer Generation from Discharge Letters** [[paper](https://doi.org/10.18653/v1/2025.cl4health-1.10)]

##### 2024

- [2024] **Multi-modal, Multi-task, Multi-criteria Automatic Evaluation with Vision Language Models** [[paper](https://arxiv.org/abs/2412.14613)] [[project](https://stjohn2007.github.io/MMHE_project/)]
- [2024] **LingGen: Scalable Multi-Attribute Linguistic Control via Power-Law Masking** [[paper](https://arxiv.org/abs/2410.24201)]
- [2024] **Language Models can Self-Lengthen to Generate Long Texts** [[paper](https://arxiv.org/abs/2410.23933)] [[code](https://github.com/QwenLM/Self-Lengthen)]
- [2024] **Graded Suspiciousness of Adversarial Texts to Human** [[paper](https://arxiv.org/abs/2410.04377)]
- [2024] **DisGeM: Distractor Generation for Multiple Choice Questions with Span Masking** [[paper](https://arxiv.org/abs/2409.18263)] [[code](https://github.com/obss/disgem)]
- [2024] **Systematic Task Exploration with LLMs: A Study in Citation Text Generation** [[paper](https://arxiv.org/abs/2407.04046)]
- [2024] **Aligning Model Evaluations with Human Preferences: Mitigating Token Count Bias in Language Model Assessments** [[paper](https://arxiv.org/abs/2407.12847)]
- [2024] **TC-Bench: Benchmarking Temporal Compositionality in Text-to-Video and Image-to-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.08656)]
- [2024] **Rethinking Human Evaluation Protocol for Text-to-Video Models: Enhancing Reliability,Reproducibility, and Practicality** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.08845)]
- [2024] **Characterizing Similarities and Divergences in Conversational Tones in Humans and LLMs by Sampling with People** *ACL 2024* [[paper](https://arxiv.org/abs/2406.04278)]
- [2024] **SciNews: From Scholarly Complexities to Public Narratives -- A Dataset for Scientific News Report Generation** [[paper](https://arxiv.org/abs/2403.17768)]
- [2024] **Scaling Rectified Flow Transformers for High-Resolution Image Synthesis** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.03206)]
- [2024] **Development of a Human Evaluation Framework and Correlation with Automated Metrics for Natural Language Generation of Medical Diagnoses** *medRxiv* [[paper](https://doi.org/10.1101/2024.03.20.24304620)]
- [2024] **Aligning with Human Judgement: The Role of Pairwise Preference in Large Language Model Evaluators** [[paper](https://arxiv.org/abs/2403.16950)]
- [2024] **Open-ended VQA benchmarking of Vision-Language models by exploiting Classification datasets and their semantic hierarchy** [[paper](https://arxiv.org/abs/2402.07270)]
- [2024] **Language Model Sentence Completion with a Parser-Driven Rhetorical Control Method** [[paper](https://arxiv.org/abs/2402.06125)]
- [2024] **SemScore: Automated Evaluation of Instruction-Tuned LLMs based on Semantic Textual Similarity** [[paper](https://arxiv.org/abs/2401.17072)]

##### 2023

- [2023] **AIGCBench: Comprehensive evaluation of image-to-video content generated by AI** *BenchCouncil Transactions on Benchmarks Standards and Evaluations* [[paper](https://doi.org/10.1016/j.tbench.2024.100152)]
- [2023] **TencentLLMEval: A Hierarchical Evaluation of Real-World Capabilities for Human-Aligned LLMs** [[paper](https://arxiv.org/abs/2311.05374)]
- [2023] **Generative AI: A Review on Models and Applications** [[paper](https://doi.org/10.1109/iccsai59793.2023.10421601)]
- [2023] **FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.01813)]
- [2023] **T^3Bench: Benchmarking Current Progress in Text-to-3D Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.02977)]
- [2023] **TIGERScore: Towards Building Explainable Metric for All Text Generation Tasks** [[paper](https://arxiv.org/abs/2310.00752)] [[project](https://tiger-ai-lab.github.io/TIGERScore/})]
- [2023] **GenEval: An Object-Focused Framework for Evaluating Text-to-Image Alignment** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.11513)]
- [2023] **Evaluating Large Language Models at Evaluating Instruction Following** [[paper](https://arxiv.org/abs/2310.07641)]
- [2023] **Data Augmentation Techniques for Machine Translation of Code-Switched Texts: A Comparative Study** [[paper](https://arxiv.org/abs/2310.15262)]
- [2023] **Closing the Curious Case of Neural Text Degeneration** [[paper](https://arxiv.org/abs/2310.01693)]
- [2023] **Striking Gold in Advertising: Standardization and Exploration of Ad Text Generation** [[paper](https://arxiv.org/abs/2309.12030)]
- [2023] **Controllable Text Generation with Residual Memory Transformer** [[paper](https://arxiv.org/abs/2309.16231)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Most biomedical publications show signs of LLM-assisted writing** [[paper](https://arxiv.org/abs/2608.10715)]
- [2026] **Jako Tako or Fluent? Presenting PoVisLE: A Polish Vision-Language Evaluation** [[paper](https://arxiv.org/abs/2608.07763)]
- [2026] **DBLAST: Dependent Block Drafting for Stochastic Speculative Decoding** [[paper](https://arxiv.org/abs/2608.05448)]
- [2026] **Mask-Aware Policy Gradients for Diffusion Language Models** *COLM 2026* [[paper](https://arxiv.org/abs/2607.15200)]
- [2026] **The Alignment Problem in Constrained Code Generation** [[paper](https://arxiv.org/abs/2606.21619)]
- [2026] **3-Key-Input: Exploring the Theoretical Minimum Keys for Text Entry** [[paper](https://arxiv.org/abs/2606.11642)]
- [2026] **Enhancing Automatic Keyphrase Labelling with Text-to-Text Transfer Transformer (T5) Architecture: A Framework for Keyphrase Generation and Filtering** *International Journal of Computational Intelligence Systems* [[paper](https://arxiv.org/abs/2409.16760)]
- [2026] **OS-SPEAR: A Toolkit for the Safety, Performance,Efficiency, and Robustness Analysis of OS Agents** [[paper](https://arxiv.org/abs/2604.24348)] [[code](https://github.com/Wuzheng02/OS-SPEAR)]
- [2026] **To See is Not to Master: Teaching LLMs to Use Private Libraries for Code Generation** [[paper](https://arxiv.org/abs/2603.15159)] [[code](https://github.com/eniacode/PriCoder)]
- [2026] **TTA-Bench: A Comprehensive Benchmark for Evaluating Text-to-Audio Models** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i39.40639)]
- [2026] **Multi-Agent Dialectical Refinement for Enhanced Argument Classification** [[paper](https://arxiv.org/abs/2603.27451)]
- [2026] **InfoFlow KV: Information-Flow-Aware KV Recomputation for Long Context** [[paper](https://arxiv.org/abs/2603.05353)]
- [2026] **Characterizing Linear Alignment Across Language Models** [[paper](https://arxiv.org/abs/2603.18908)]
- [2026] **CONCUR: Benchmarking LLMs for Concurrent Code Generation** [[paper](https://arxiv.org/abs/2603.03683)]
- [2026] **Long-range Modeling and Processing of Multimodal Event Sequences** [[paper](https://arxiv.org/abs/2602.01125)]
- [2026] **Unit-Based Agent for Semi-Cascaded Full-Duplex Dialogue Systems** [[paper](https://arxiv.org/abs/2601.20230)] [[code](https://github.com/yu-haoyuan/fd-badcat)]
- [2026] **Founder effects shape the evolutionary dynamics of multimodality in open LLM families** [[paper](https://arxiv.org/abs/2603.22287)]
- [2026] **Evaluating and Achieving Controllable Code Completion in Code LLM** [[paper](https://arxiv.org/abs/2601.15879)]
- [2026] **A Survey of Text-to-Image Generation: From GANs to Diffusion Models, Datasets, Evaluation Metrics and Key Challenges** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6194927)]
- [2026] **A COMPARATIVE STUDY OF CHUNKING STRATEGIES FOR RETRIEVAL-AUGMENTED GENERATION** *Kibernetyka ta Systemnyi Analiz* [[paper](https://doi.org/10.34229/kca2522-9664.26.3.4)]

##### 2025

- [2025] **TV2TV: A Unified Framework for Interleaved Language and Video Generation** [[paper](https://arxiv.org/abs/2512.05103)]
- [2025] **Large Language Models for Education and Research: An Empirical and User Survey-based Analysis** [[paper](https://arxiv.org/abs/2512.08057)]
- [2025] **DiffRhythm+: Controllable and Flexible Full-Length Song Generation with Preference Optimization** [[paper](https://doi.org/10.1109/asru65441.2025.11434644)]
- [2025] **BeHGAN: Bengali Handwritten Word Generation from Plain Text Using Generative Adversarial Networks** [[paper](https://arxiv.org/abs/2512.21694)]
- [2025] **AGHI-QA: A Subjective-Aligned Dataset and Metric for AI-Generated Human Images** *IEEE Transactions on Circuits and Systems for Video Technology* [[paper](https://doi.org/10.1109/tcsvt.2025.3639620)]
- [2025] **Text-to-video generators: a comprehensive survey** *Journal Of Big Data* [[paper](https://doi.org/10.1186/s40537-025-01314-3)]
- [2025] **M-DAIGT: A Shared Task on Multi-Domain Detection of AI-Generated Text** [[paper](https://arxiv.org/abs/2511.11340)]
- [2025] **Fine-Tuning Vision-Language Models for Multimodal Polymer Property Prediction** [[paper](https://arxiv.org/abs/2511.05577)]
- [2025] **Inclusive Easy-to-Read Text Generation for Individuals with Cognitive Impairments** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia251224)]
- [2025] **F-Bench: Rethinking Human Preference Evaluation Metrics for Benchmarking Face Generation, Customization, and Restoration** [[paper](https://arxiv.org/abs/2412.13155)]
- [2025] **Evaluating Retrieval Augmented Generation (RAG) Chunking Strategy for Question Answering in Indonesian Law of The Sea** [[paper](https://doi.org/10.1109/ic3ina68387.2025.11325153)]
- [2025] **Deep Learning-Based Visual Fatigue Detection Using Eye Gaze Patterns in VR** [[paper](https://arxiv.org/abs/2510.12994)]
- [2025] **SynthMedic: Utilizing large language models for synthetic discharge summary generation, correction and validation** *Journal of Biomedical Informatics* [[paper](https://doi.org/10.1016/j.jbi.2025.104906)]
- [2025] **EditGRPO: Reinforcement Learning with Post-Rollout Edits for Clinically Accurate Chest X-Ray Report Generation** [[paper](https://arxiv.org/abs/2509.22812)]
- [2025] **DrDiff: Dynamic Routing Diffusion with Hierarchical Attention for Breaking the Efficiency-Quality Trade-off** [[paper](https://arxiv.org/abs/2509.02785)]
- [2025] **CodeRAG: Finding Relevant and Necessary Knowledge for Retrieval-Augmented Repository-Level Code Completion** [[paper](https://arxiv.org/abs/2509.16112)] [[code](https://github.com/KDEGroup/CodeRAG)]
- [2025] **CL^2GEC: A Multi-Discipline Benchmark for Continual Learning in Chinese Literature Grammatical Error Correction** [[paper](https://arxiv.org/abs/2509.13672)]
- [2025] **Towards AI-Assisted Research Writing: Benchmarking LLMs for AI/ML Introduction Generation** [[paper](https://arxiv.org/abs/2508.14273)]
- [2025] **Text-to-Image Generation of Bird Images Using GAN-CLS and MS-GAN** [[paper](https://doi.org/10.1109/nmitcon65824.2025.11188140)]
- [2025] **T2VEval: Benchmark dataset and objective evaluation method for T2V-generated videos** *Displays* [[paper](https://doi.org/10.1016/j.displa.2025.103178)]
- [2025] **SaraCoder: Orchestrating Semantic and Structural Cues for Resource-Optimized Repository-Level Code Completion** [[paper](https://arxiv.org/abs/2508.10068)]
- [2025] **Resource for Error Analysis in Text Simplification: New Taxonomy and Test Collection** [[paper](https://arxiv.org/abs/2505.16392)]
- [2025] **Multilingual Multimodal Software Developer for Code Generation** [[paper](https://arxiv.org/abs/2507.08719)]
- [2025] **MRAMG-Bench: A Comprehensive Benchmark for Advancing Multimodal Retrieval-Augmented Multimodal Generation** [[paper](https://doi.org/10.1145/3726302.3730288)]
- [2025] **GRR-CoCa: Leveraging LLM Mechanisms in Multimodal Model Architectures** [[paper](https://arxiv.org/abs/2507.18009)]
- [2025] **Enhancing Project-Specific Code Completion by Inferring Internal API Information** [[paper](https://arxiv.org/abs/2507.20888)]
- [2025] **Enhancing Domain-Specific Retrieval-Augmented Generation: Synthetic Data Generation and Evaluation using Reasoning Models** [[paper](https://doi.org/10.1109/iaict65714.2025.11100564)]
- [2025] **Development and Evaluation of a Retrieval-Augmented Generation-Based Electronic Medical Record Chatbot System** *Healthcare Informatics Research* [[paper](https://doi.org/10.4258/hir.2025.31.3.218)]
- [2025] **Benchmarking Multi-dimensional AIGC Video Quality Assessment: A Dataset and Unified Model** *ACM Transactions on Multimedia Computing Communications and Applications* [[paper](https://doi.org/10.1145/3749844)]
- [2025] **A Survey on Quality Metrics for Text-to-Image Generation** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3585077)]
- [2025] **A Survey on Code Generation with LLM-based Agents** [[paper](https://arxiv.org/abs/2508.00083)]
- [2025] **A Code Comprehension Benchmark for Large Language Models for Code** [[paper](https://arxiv.org/abs/2507.10641)]
- [2025] **ReCode: Updating Code API Knowledge with Reinforcement Learning** [[paper](https://arxiv.org/abs/2506.20495)] [[code](https://github.com/zjunlp/ReCode)]
- [2025] **Humanity's Last Code Exam: Can Advanced LLMs Conquer Human's Hardest Code Competition?** [[paper](https://arxiv.org/abs/2506.12713)] [[code](https://github.com/Humanity-s-Last-Code-Exam/HLCE)]
- [2025] **EVALUATION AND COMPARISON OF TEXT-TO-AUDIO GENERATION MODELS FOR MEDIA APPLICATIONS** *Herald of Khmelnytskyi National University Technical sciences* [[paper](https://doi.org/10.31891/2307-5732-2025-351-3)]
- [2025] **ATGen: A Framework for Active Text Generation** *ACL 2025 System Demonstrations* [[paper](https://arxiv.org/abs/2506.23342)]
- [2025] **A Pipeline for Automating Emergency Medicine Documentation Using LLMs with Retrieval-Augmented Text Generation** *Applied Artificial Intelligence* [[paper](https://doi.org/10.1080/08839514.2025.2519169)]
- [2025] **Improving AI models for rare thyroid cancer subtype by text guided diffusion models** *Nature Communications* [[paper](https://doi.org/10.1038/s41467-025-59478-8)]
- [2025] **Exploring Jailbreak Attacks on LLMs through Intent Concealment and Diversion** [[paper](https://arxiv.org/abs/2505.14316)]
- [2025] **CodeMixBench: Evaluating Large Language Models on Code Generation with Code-Mixed Prompts** [[paper](https://arxiv.org/abs/2505.05063)]
- [2025] **Can You Really Trust Code Copilots? Evaluating Large Language Models from a Code Security Perspective** [[paper](https://arxiv.org/abs/2505.10494)]
- [2025] **Benchmarking Radiology Report Generation From Noisy Free-Texts** *IEEE Journal of Biomedical and Health Informatics* [[paper](https://doi.org/10.1109/jbhi.2025.3569428)]
- [2025] **AutoGEEval: A Multimodal and Automated Framework for Geospatial Code Generation on GEE with Large Language Models** [[paper](https://arxiv.org/abs/2505.12900)]
- [2025] **Arena 4.0: a Comprehensive Ros2 Development and Benchmarking Platform for Human-Centric Navigation Using Generative-Model-Based Environment Generation** [[paper](https://doi.org/10.1109/icra55743.2025.11127635)]
- [2025] **MARKMyWORDS: Analyzing and Evaluating Language Model Watermarks** [[paper](https://doi.org/10.1109/satml64287.2025.00012)]
- [2025] **Evaluating and mitigating bias in AI-based medical text generation** *Nature Computational Science* [[paper](https://doi.org/10.1038/s43588-025-00789-7)]
- [2025] **Enhancing multimodal analogical reasoning with Logic Augmented Generation** [[paper](https://arxiv.org/abs/2504.11190)]
- [2025] **Elevating Flow-Guided Video Inpainting with Reference Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i3.32255)]
- [2025] **Advancing Arabic Reverse Dictionary Systems: A Transformer-Based Approach with Dataset Construction Guidelines** [[paper](https://arxiv.org/abs/2504.21475)]
- [2025] **A Brief Review on Benchmarking for Large Language Models Evaluation in Healthcare** *Wiley Interdisciplinary Reviews Data Mining and Knowledge Discovery* [[paper](https://doi.org/10.1002/widm.70010)]
- [2025] **WritingBench: A Comprehensive Benchmark for Generative Writing** [[paper](https://arxiv.org/abs/2503.05244)]
- [2025] **Well log data generation and imputation using sequence based generative adversarial networks** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-95709-0)]
- [2025] **Verbal Process Supervision Elicits Better Coding Agents** [[paper](https://arxiv.org/abs/2503.18494)]
- [2025] **Towards a holistic framework for multimodal LLM in 3D brain CT radiology report generation** *Nature Communications* [[paper](https://doi.org/10.1038/s41467-025-57426-0)]
- [2025] **RaT2IGen: Relation-aware Text-to-image Generation via Learnable Prompt** *ACM Transactions on Multimedia Computing Communications and Applications* [[paper](https://doi.org/10.1145/3726527)]
- [2025] **RL-finetuning LLMs from on- and off-policy data with a single algorithm** [[paper](https://arxiv.org/abs/2503.19612)]
- [2025] **RAGCol: RAG-Based Automatic Video Colorization Through Text Caption Generation and Knowledge Enrichment** [[paper](https://doi.org/10.1145/3672608.3707748)]
- [2025] **Can DeepSeek Reason Like a Surgeon? An Empirical Evaluation for Vision-Language Understanding in Robotic-Assisted Surgery** [[paper](https://arxiv.org/abs/2503.23130)]
- [2025] **ScholaWrite: A Dataset of End-to-End Scholarly Writing Process** [[paper](https://arxiv.org/abs/2502.02904)]
- [2025] **REAL: Realism Evaluation of Text-to-Image Generation Models for Effective Data Augmentation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.10663)]
- [2025] **Quality Assessment for Text-to-Image Generation: A Survey** *IEEE Multimedia* [[paper](https://doi.org/10.1109/mmul.2025.3538862)]
- [2025] **Large Language Models Penetration in Scholarly Writing and Peer Review** [[paper](https://arxiv.org/abs/2502.11193)]
- [2025] **JAM: Controllable and Responsible Text Generation via Causal Reasoning and Latent Vector Manipulation** [[paper](https://arxiv.org/abs/2502.20684)]
- [2025] **Isolating Language-Coding from Problem-Solving: Benchmarking LLMs with PseudoEval** [[paper](https://arxiv.org/abs/2502.19149)]
- [2025] **IndicEval-XL: Bridging Linguistic Diversity in Code Generation Across Indic Languages** [[paper](https://arxiv.org/abs/2502.19067)] [[code](https://github.com/telekom/IndicEval-XL)]
- [2025] **ControllableGPT: A Ground-Up Designed Controllable GPT for Molecule Optimization** [[paper](https://arxiv.org/abs/2502.10631)]
- [2025] **CodeSteer: Symbolic-Augmented Language Models via Code/Text Guidance** [[paper](https://arxiv.org/abs/2502.04350)] [[code](https://github.com/yongchao98/CodeSteer-v1.0)] [[project](https://huggingface.co/yongchao98)]
- [2025] **A Semi-Supervised Text Generation Framework Combining a Deep Transformer and a GAN** [[paper](https://arxiv.org/abs/2502.05937)]
- [2025] **A Deep Learning Approach to Interface Color Quality Assessment in HCI** [[paper](https://arxiv.org/abs/2502.09914)]
- [2025] **Thought2Text: Text Generation from EEG Signal using Large Language Models (LLMs)** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.207)]
- [2025] **T2I-CompBench++: An Enhanced and Comprehensive Benchmark for Compositional Text-to-Image Generation** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3531907)]
- [2025] **Implicit knowledge-augmented prompting for commonsense explanation generation** *Knowledge and Information Systems* [[paper](https://doi.org/10.1007/s10115-024-02326-w)]
- [2025] **Engineering Text-to-text Generation Language Models as Discriminative Classifiers for Accurate Answer Detection** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2025.04.553)]
- [2025] **Do Large Multimodal Models Solve Caption Generation for Scientific Figures? Lessons Learned from SciCap Challenge 2023** [[paper](https://arxiv.org/abs/2501.19353)]
- [2025] **Can OpenAI o1's Enhanced Reasoning Capabilities Extend to Ophthalmology? A Benchmark Study Across Large Language Models and Text Generation Metrics** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5091694)]
- [2025] **Automatic Scene Generation: State-of-the-Art Techniques, Models, Datasets, Challenges, and Future Prospects** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3574298)]
- [2025] **AD2AT: Audio Description to Alternative Text, a Dataset of Alternative Text from Movies** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-96-2054-8_5)]

##### 2024

- [2024] **Qwen2.5 Technical Report** [[paper](https://arxiv.org/abs/2412.15115)]
- [2024] **MedMax: Mixed-Modal Instruction Tuning for Training Biomedical Assistants** [[paper](https://arxiv.org/abs/2412.12661)] [[project](https://mint-medmax.github.io/)]
- [2024] **HumanEval Pro and MBPP Pro: Evaluating Large Language Models on Self-invoking Code Generation** [[paper](https://arxiv.org/abs/2412.21199)]
- [2024] **Evaluating RAG Pipeline in Multimodal LLM-based Question Answering Systems** [[paper](https://doi.org/10.1109/icacrs62842.2024.10841620)]
- [2024] **Enhancing Accessibility: Automated Tactile Graphics Generation for Individuals with Visual Impairments** *Computation* [[paper](https://doi.org/10.3390/computation12120251)]
- [2024] **DPN: Dynamics Priori Networks for Radiology Report Generation** *Tsinghua Science & Technology* [[paper](https://doi.org/10.26599/tst.2023.9010134)]
- [2024] **Beware of diffusion models for synthesizing medical images—a comparison with GANs in terms of memorizing brain MRI and chest x-ray images** *Machine Learning Science and Technology* [[paper](https://doi.org/10.1088/2632-2153/ad9a3a)]
- [2024] **Unlocking the Archives: Using Large Language Models to Transcribe Handwritten Historical Documents** [[paper](https://arxiv.org/abs/2411.03340)]
- [2024] **Pointwise Mutual Information as a Performance Gauge for Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2411.07773)]
- [2024] **Multi-modal Retrieval Augmented Multi-modal Generation: Datasets, Evaluation Metrics and Strong Baselines** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.16365)]
- [2024] **Libra: Leveraging Temporal Images for Biomedical Radiology Analysis** [[paper](https://arxiv.org/abs/2411.19378)]
- [2024] **Human-Activity AGV Quality Assessment: A Benchmark Dataset and an Objective Evaluation Metric** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.16619)]
- [2024] **Generative AI in the context of assistive technologies: Trends, limitations and future directions** *Image and Vision Computing* [[paper](https://doi.org/10.1016/j.imavis.2024.105347)]
- [2024] **EzSQL: An SQL intermediate representation for improving SQL-to-text Generation** [[paper](https://arxiv.org/abs/2411.18923)]
- [2024] **Automated Generation of Lung Cytological Images from Image Findings Using Text-to-Image Technology** *Computers* [[paper](https://doi.org/10.3390/computers13110303)]
- [2024] **mHumanEval -- A Multilingual Benchmark to Evaluate Large Language Models for Code Generation** [[paper](https://arxiv.org/abs/2410.15037)]
- [2024] **TemporalBench: Benchmarking Fine-grained Temporal Understanding for Multimodal Video Models** [[paper](https://arxiv.org/abs/2410.10818)]
- [2024] **TAVGBench: Benchmarking Text to Audible-Video Generation** [[paper](https://doi.org/10.1145/3664647.3680612)]
- [2024] **Subjective-Aligned Dataset and Metric for Text-to-Video Quality Assessment** [[paper](https://doi.org/10.1145/3664647.3680868)]
- [2024] **Self-Explained Keywords Empower Large Language Models for Code Generation** [[paper](https://arxiv.org/abs/2410.15966)]
- [2024] **Reference-Based Post-OCR Processing with LLM for Precise Diacritic Text in Historical Document Recognition** [[paper](https://arxiv.org/abs/2410.13305)]
- [2024] **On the Cultural Gap in Text-to-Image Generation** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia240581)]
- [2024] **M2rc-Eval: Massively Multilingual Repository-level Code Completion Evaluation** [[paper](https://arxiv.org/abs/2410.21157)]
- [2024] **Evaluation of Code LLMs on Geospatial Code Generation** [[paper](https://arxiv.org/abs/2410.04617)]
- [2024] **CoqPilot, a plugin for LLM-based generation of proofs** [[paper](https://arxiv.org/abs/2410.19605)] [[code](https://github.com/JetBrains-Research/coqpilot)]
- [2024] **CLaM: An Open-Source Library for Performance Evaluation of Text-driven Human Motion Generation** [[paper](https://doi.org/10.1145/3664647.3685523)]
- [2024] **'Quis custodiet ipsos custodes?' Who will watch the watchmen? On Detecting AI-generated peer-reviews** [[paper](https://arxiv.org/abs/2410.09770)]
- [2024] **Pipeline for Text-to-Image Panoramic Road Scene Generation and Evaluation** [[paper](https://doi.org/10.1145/3641308.3685038)]
- [2024] **End-to-End Clustering Enhanced Contrastive Learning for Radiology Reports Generation** *IEEE Transactions on Emerging Topics in Computational Intelligence* [[paper](https://doi.org/10.1109/tetci.2024.3449876)]
- [2024] **Contextualized Data-Wrangling Code Generation in Computational Notebooks** [[paper](https://arxiv.org/abs/2409.13551)]
- [2024] **Benchmarking LLM Code Generation for Audio Programming with Visual Dataflow Languages** [[paper](https://arxiv.org/abs/2409.00856)]
- [2024] **Automatic Question-Answer Generation for Education on Indonesian Texts : A Review of Methodologies, Dataset and Evaluation Metrics** [[paper](https://doi.org/10.1109/ictiia61827.2024.10761325)]
- [2024] **Security Attacks on LLM-based Code Completion Tools** *AAAI 2025* [[paper](https://arxiv.org/abs/2408.11006)] [[code](https://github.com/Sensente/Security-Attacks-on-LCCTs)]
- [2024] **OpenOmni: A Collaborative Open Source Tool for Building Future-Ready Multimodal Conversational Agents** *EMNLP 2024* [[paper](https://arxiv.org/abs/2408.03047)] [[code](https://github.com/AI4WA/OpenOmniFramework)]
- [2024] **Mini-Omni: Language Models Can Hear, Talk While Thinking in Streaming** [[paper](https://arxiv.org/abs/2408.16725)]
- [2024] **IMUGPT 2.0: Language-Based Cross Modality Transfer for Sensor-Based Human Activity Recognition** *Proceedings of the ACM on Interactive Mobile Wearable and Ubiquitous Technologies* [[paper](https://doi.org/10.1145/3678545)]
- [2024] **Evaluating Named Entity Recognition: A comparative analysis of mono- and multilingual transformer models on a novel Brazilian corporate earnings call transcripts dataset** *Applied Soft Computing* [[paper](https://arxiv.org/abs/2403.12212)]
- [2024] **Evaluation of Text-to-Video Generation Models: A Dynamics Perspective** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.01094)]
- [2024] **VersiCode: Towards Version-controllable Code Generation** [[paper](https://arxiv.org/abs/2406.07411)] [[code](https://github.com/wutong8023/VersiCode)]
- [2024] **TruthEval: A Dataset to Evaluate LLM Truthfulness and Reliability** [[paper](https://arxiv.org/abs/2406.01855)]
- [2024] **SemCoder: Training Code Language Models with Comprehensive Semantics Reasoning** [[paper](https://arxiv.org/abs/2406.01006)] [[code](https://github.com/ARiSE-Lab/SemCoder)]
- [2024] **R2C2-Coder: Enhancing and Benchmarking Real-world Repository-level Code Completion Abilities of Code Large Language Models** [[paper](https://arxiv.org/abs/2406.01359)]
- [2024] **PhyBench: A Physical Commonsense Benchmark for Evaluating Text-to-Image Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.11802)]
- [2024] **Evaluating and Improving Compositional Text-to-Visual Generation** [[paper](https://doi.org/10.1109/cvprw63382.2024.00538)]
- [2024] **CodeRAG-Bench: Can Retrieval Augment Code Generation?** [[paper](https://arxiv.org/abs/2406.14497)]
- [2024] **BioInstruct: instruction tuning of large language models for biomedical natural language processing** *Journal of the American Medical Informatics Association* [[paper](https://doi.org/10.1093/jamia/ocae122)]
- [2024] **An Investigative Analysis on Generation of AI Text Using Deep Learning Models for Large Language Models** [[paper](https://doi.org/10.1109/icsseecc61126.2024.10649514)]
- [2024] **AICoderEval: Improving AI Domain Code Generation of Large Language Models** [[paper](https://arxiv.org/abs/2406.04712)] [[project](https://huggingface.co/datasets/vixuowis/AICoderEval})]
- [2024] **A Survey on Large Language Models for Code Generation** [[paper](https://arxiv.org/abs/2406.00515)] [[code](https://github.com/juyongjiang/CodeLLMSurvey)]
- [2024] **Optimizing Large Language Models for OpenAPI Code Completion** [[paper](https://arxiv.org/abs/2405.15729)]
- [2024] **Learning Multi-dimensional Human Preference for Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.14705)]
- [2024] **Evaluating Text Generation Confidence: A Pseudo Confidence Metric for Completion Models** [[paper](https://doi.org/10.1109/isml60050.2024.11007363)]
- [2024] **Dataflow-Guided Retrieval Augmentation for Repository-Level Code Completion** [[paper](https://arxiv.org/abs/2405.19782)]
- [2024] **Alt4Blind: A User Interface to Simplify Charts Alt-Text Creation** [[paper](https://arxiv.org/abs/2405.19111)] [[project](https://moured.github.io/alt4blind/)]
- [2024] **A dataset of text prompts, videos and video quality metrics from generative text-to-video AI models** *Data in Brief* [[paper](https://doi.org/10.1016/j.dib.2024.110514)]
- [2024] **Survey of Bias In Text-to-Image Generation: Definition, Evaluation, and Mitigation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.01030)]
- [2024] **Replacing Judges with Juries: Evaluating LLM Generations with a Panel of Diverse Models** [[paper](https://arxiv.org/abs/2404.18796)]
- [2024] **Mapping the Increasing Use of LLMs in Scientific Papers** [[paper](https://arxiv.org/abs/2404.01268)]
- [2024] **MISTRA: Misogyny Detection through Text–Image Fusion and Representation Analysis** *Natural Language Processing Journal* [[paper](https://doi.org/10.1016/j.nlp.2024.100073)]
- [2024] **LLM Attributor: Interactive Visual Attribution for LLM Generation** [[paper](https://arxiv.org/abs/2404.01361)]
- [2024] **CEval: A Benchmark for Evaluating Counterfactual Text Generation** [[paper](https://arxiv.org/abs/2404.17475)]
- [2024] **A Review of Text-to-Image Synthesis Methods** [[paper](https://doi.org/10.1109/cvidl62147.2024.10603609)]
- [2024] **Triples-to-isiXhosa (T2X): Addressing the Challenges of Low-Resource Agglutinative Data-to-Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.07567)]
- [2024] **Text-to-Audio Generation Synchronized with Videos** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.07938)]
- [2024] **SPUQ: Perturbation-Based Uncertainty Quantification for Large Language Models** [[paper](https://arxiv.org/abs/2403.02509)]
- [2024] **Repoformer: Selective Retrieval for Repository-Level Code Completion** [[paper](https://arxiv.org/abs/2403.10059)]
- [2024] **Quantifying Contamination in Evaluating Code Generation Capabilities of Language Models** [[paper](https://arxiv.org/abs/2403.04811)]
- [2024] **Multi-Grained Radiology Report Generation With Sentence-Level Image-Language Contrastive Learning** *IEEE Transactions on Medical Imaging* [[paper](https://doi.org/10.1109/tmi.2024.3372638)]
- [2024] **Investigating the Performance of Language Models for Completing Code in Functional Programming Languages: a Haskell Case Study** [[paper](https://arxiv.org/abs/2403.15185)] [[code](https://github.com/AISE-TUDelft/HaskellCCEval)]
- [2024] **IRCoder: Intermediate Representations Make Language Models Robust Multilingual Code Generators** [[paper](https://arxiv.org/abs/2403.03894)]
- [2024] **Diverse and Aligned Audio-to-Video Generation via Text-to-Video Model Adaptation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i7.28486)]
- [2024] **BP4ER: Bootstrap Prompting for Explicit Reasoning in Medical Dialogue Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.19414)]
- [2024] **Audio Generation with Multiple Conditional Diffusion Model** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i16.29773)]
- [2024] **A Cross-Modal Approach to Silent Speech with LLM-Enhanced Recognition** [[paper](https://arxiv.org/abs/2403.05583)]
- [2024] **ToBlend: Token-Level Blending With an Ensemble of LLMs to Attack AI-Generated Text Detection** [[paper](https://arxiv.org/abs/2402.11167)]
- [2024] **The Effect of Sampling Temperature on Problem Solving in Large Language Models** [[paper](https://arxiv.org/abs/2402.05201)] [[code](https://github.com/matthewrenze/jhu-llm-temperature)]
- [2024] **HU at SemEval-2024 Task 8A: Can Contrastive Learning Learn Embeddings to Detect Machine-Generated Text?** [[paper](https://arxiv.org/abs/2402.11815)] [[code](https://github.com/dipta007/SemEval24-Task8)]
- [2024] **Generative Adversarial Networks for text-to-face synthesis & generation: A quantitative–qualitative analysis of Natural Language Processing encoders for Spanish** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2024.103667)]
- [2024] **DolphCoder: Echo-Locating Code Large Language Models with Diverse and Multi-Objective Instruction Tuning** [[paper](https://arxiv.org/abs/2402.09136)]
- [2024] **Distractor Generation in Multiple-Choice Tasks: A Survey of Methods, Datasets, and Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01512)]
- [2024] **CounterCurate: Enhancing Physical and Semantic Visio-Linguistic Compositional Reasoning via Counterfactual Examples** [[paper](https://arxiv.org/abs/2402.13254)]
- [2024] **Chinese Title Generation for Short Videos: Dataset, Metric and Algorithm** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://dx.doi.org/10.1109/tpami.2024.3365739)]
- [2024] **Towards Explainable Harmful Meme Detection through Multimodal Debate between Large Language Models** [[paper](https://arxiv.org/abs/2401.13298)]
- [2024] **Towards A Better Metric for Text-to-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.07781)]
- [2024] **Text-to-OverpassQL: A Natural Language Interface for Complex Geodata Querying of OpenStreetMap** *Transactions of the Association for Computational Linguistics* [[paper](https://doi.org/10.1162/tacl_a_00654)]
- [2024] **Text-to-Image Synthesis With Generative Models: Methods, Datasets, Performance Metrics, Challenges, and Future Direction** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3365043)]
- [2024] **RaTEScore: A Metric for Radiology Report Generation** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.836)]
- [2024] **Extracting and Encoding: Leveraging Large Language Models and Medical Knowledge to Enhance Radiological Text Representation** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.236)]
- [2024] **Enhancing Robustness of LLM-Synthetic Text Detectors for Academic Writing: A Comprehensive Analysis** [[paper](https://arxiv.org/abs/2401.08046)]
- [2024] **DevEval: Evaluating Code Generation in Practical Software Projects** [[paper](https://arxiv.org/abs/2401.06401)]

##### 2023

- [2023] **Optimizing Science Question Ranking through Model and Retrieval-Augmented Generation** *International Journal of Computer Science and Information Technology* [[paper](https://doi.org/10.62051/ijcsit.v1n1.17)]
- [2023] **FT2TF: First-Person Statement Text-To-Talking Face Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.05430)]
- [2023] **A Review of Repository Level Prompting for LLMs** [[paper](https://arxiv.org/abs/2312.10101)]
- [2023] **Vision Enhancing LLMs: Empowering Multimodal Knowledge Storage and Sharing in LLMs** [[paper](https://arxiv.org/abs/2311.15759)] [[code](https://github.com/HITsz-TMG/MKS2-Multimodal-Knowledge-Storage-and-Sharing)]
- [2023] **Tamil-Llama: A New Tamil Language Model Based on Llama 2** [[paper](https://arxiv.org/abs/2311.05845)]
- [2023] **Synthetic Speaking Children -- Why We Need Them and How to Make Them** [[paper](https://arxiv.org/abs/2311.06307)]
- [2023] **REST: Retrieval-Based Speculative Decoding** [[paper](https://arxiv.org/abs/2311.08252)] [[code](https://github.com/FasterDecoding/REST)]
- [2023] **Pre-trained Language Models Do Not Help Auto-regressive Text-to-Image Generation** *EMNLP 2024 Main Conference* [[paper](https://arxiv.org/abs/2311.16201)]
- [2023] **GSAP-NER: A Novel Task, Corpus, and Baseline for Scholarly Entity Extraction Focused on Machine Learning Models and Datasets** *EMNLP2023-Findings* [[paper](https://arxiv.org/abs/2311.09860)]
- [2023] **Automatic Synthesis of Realistic Images From Text using DC-Generative Adversarial Network (DCGAN)** [[paper](https://doi.org/10.1109/iciics59993.2023.10421212)]
- [2023] **A Systematic Review of Deep Learning-based Research on Radiology Report Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.14199)]
- [2023] **Write What You Want: Applying Text-to-video Retrieval to Audiovisual Archives** [[paper](https://arxiv.org/abs/2310.05825)]
- [2023] **Meta Semantic Template for Evaluation of Large Language Models** [[paper](https://arxiv.org/abs/2310.01448)]
- [2023] **Language Integration in Remote Sensing: Tasks, datasets, and future directions** *IEEE Geoscience and Remote Sensing Magazine* [[paper](https://doi.org/10.1109/mgrs.2023.3316438)]
- [2023] **EvalCrafter: Benchmarking and Evaluating Large Video Generation Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.11440)]
- [2023] **EfficienTransNet: An Automated Chest X-ray Report Generation Paradigm** [[paper](https://doi.org/10.1145/3607865.3616174)]
- [2023] **CrossCodeEval: A Diverse and Multilingual Benchmark for Cross-File Code Completion** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2310.11248)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2024

- [2024] **Semantic Image Synthesis from Text: Current Trends and Future Horizons in Text-to-Image Generation** *EAI Endorsed Transactions on Internet of Things* [[paper](https://doi.org/10.4108/eetiot.5336)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Robustness of Tabular Generative Evaluation Metrics Versus Statistical Distances on Adversarial Text Generation with Limited Data** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20653729)]

##### 2025

- [2025] **Enhancing medical image report generation using a self-boosting multimodal alignment framework** *Health Information Science and Systems* [[paper](https://doi.org/10.1007/s13755-025-00378-y)]
- [2025] **A Clinically-Informed Framework for Evaluating Vision-Language Models in Radiology Report Generation: Taxonomy of Errors and Risk-Aware Metric** *medRxiv* [[paper](https://doi.org/10.1101/2025.07.13.25331222)]
- [2025] **Large Language Models in radiology: A technical and clinical perspective** *European Journal of Radiology Artificial Intelligence* [[paper](https://doi.org/10.1016/j.ejrai.2025.100021)]
- [2025] **Optimizing medical image report generation through a discrete diffusion framework** *The Journal of Supercomputing* [[paper](https://doi.org/10.1007/s11227-025-07111-2)]
- [2025] **Pathology report generation from whole slide images with knowledge retrieval and multi-level regional feature selection** *Computer Methods and Programs in Biomedicine* [[paper](https://doi.org/10.1016/j.cmpb.2025.108677)]
- [2025] **LLM-Driven Chest X-Ray Report Generation With a Modular, Reduced-Size Architecture** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-79032-4_14)]

##### 2024

- [2024] **Enhancing radiology report generation through pre-trained language models** *Progress in Artificial Intelligence* [[paper](https://doi.org/10.1007/s13748-024-00358-5)]
- [2024] **Context-enhanced framework for medical image report generation using multimodal contexts** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2024.112913)]
- [2024] **Towards a Holistic Framework for Multimodal Large Language Models in Three-dimensional Brain CT Report Generation** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-4558754/v1)]
- [2024] **Reproducing the Metric-Based Evaluation of a Set of Controllable Text Generation Techniques** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.07875)]
- [2024] **Automatic generation of conclusions from neuroradiology MRI reports through natural language processing** *Neuroradiology* [[paper](https://doi.org/10.1007/s00234-024-03312-3)]
- [2024] **Development and Testing of Retrieval Augmented Generation in Large Language Models -- A Case Study Report** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01733)]

##### 2023

- [2023] **MAIRA-1: A specialised large multimodal model for radiology report generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.13668)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2025

- [2025] **TextToucher: Fine-Grained Text-to-Touch Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i7.32802)]
- [2025] **VT2Music: A Multimodal Framework for Text-Visual Guided Music Generation and Comprehensive Performance Analysis** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3572954)]

##### 2024

- [2024] **Image captioning by diffusion models: A survey** *Engineering Applications of Artificial Intelligence* [[paper](https://doi.org/10.1016/j.engappai.2024.109288)]

[⬆ Back to top](#paper-list)

### Human-AI Collaboration

#### LLM Evaluation

##### 2026

- [2026] **The Impact of AI-Assisted Writing Tools on the Quality of English for Specific Purposes Writing and Learner Strategies: An Empirical Study of Blended Learning** *Advanced Electromagnetics* [[paper](https://doi.org/10.7716/aem.v15i3.3932)]
- [2026] **SSS Framework: A Think-First, AI-Second Model for AI-Assisted Writing** *Annals of Biomedical Engineering* [[paper](https://doi.org/10.1007/s10439-026-04358-5)]
- [2026] **Medical English writing, Human-machine symbiosis, Instructional experiment, Self-efficacy, Collaboration** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9915798/v1)]
- [2026] **Exploring the potential of generative AI and teacher collaboration in evaluating academic papers** *Education and Information Technologies* [[paper](https://doi.org/10.1007/s10639-025-13864-3)]
- [2026] **CRITICAL GENERATIVE FRAMEWORK: HUMAN-AI CO-CREATION FOR THE VISIBILITY OF NEURODIVERGENT CONTEXTS** *Artefactum* [[paper](https://doi.org/10.23900/artefactum.v25i5.3272)]
- [2026] **Equipping elementary school students with self-regulated learning through human-AI collaboration in online learning** *Computers & Education* [[paper](https://doi.org/10.1016/j.compedu.2026.105697)]
- [2026] **Does Artificial Intelligence Make You Stupid? Cognitive Debt and a Three-Tier Framework for Sustainable Human–AI Collaboration** *Global Journal of Computer Science and Technology* [[paper](https://doi.org/10.34257/gjcstg257948)]
- [2026] **Contextual AI Meets Generative AI** [[paper](https://doi.org/10.4324/9781003661443-2)]
- [2026] **Beyond Co-Regulation: Interplay as a Methodological Framework for Examining Self-Regulation in Generative AI-Assisted Writing** *Written Communication* [[paper](https://doi.org/10.1177/07410883261440232)]
- [2026] **AI-assisted narrative design: a model of human-AI collaborative creativity in popularizing digital journalism articles** *Frontiers in Human Dynamics* [[paper](https://doi.org/10.3389/fhumd.2026.1777511)]
- [2026] **Human-GenAI Collaboration in Creative Tasks: Creative Industry Perspective** [[paper](https://doi.org/10.1145/3772363.3799212)]
- [2026] **Human Thinking under Plural LLM Assistance: Mathematical Problem Solving and Open-Ended Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.02677)]
- [2026] **AI Authorship and the Role of the Librarian** *Theological Librarianship* [[paper](https://doi.org/10.31046/7a5ddy84)]
- [2026] **Research on English Writing Evaluation Patterns From a Human-Computer Collaborative Perspective** [[paper](https://doi.org/10.1109/aieta69357.2026.11508861)]
- [2026] **Relying on AI at work reduces self-efficacy, ownership, and meaning while active collaboration mitigates the effects** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-42312-6)]
- [2026] **Collaboration** [[paper](https://doi.org/10.1201/9781003496052-11)]
- [2026] **Advances in Human‐AI Collaboration** [[paper](https://doi.org/10.1002/9781394266401)]
- [2026] **Sequential Human-AI Collaboration Impairs Narrative Creativity in University Students: A Randomized Controlled Trial** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8774138/v1)]
- [2026] **The Multitasking Brain Under AI Collaboration: An Exploratory N=1 EEG Study During Concurrent Theory Construction** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18367237)]
- [2026] **Separating Innovation from Mechanical Writing:,How Researchers and AI Can Pragmatically Collaborate to Increase Efficiency in Technical Writing While Preserving Research Integrity** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7129763)]
- [2026] **Provenance as Epistemic Fulcrum: A Three-Year Case Study in Human-AI Co-authorship** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7149262)]
- [2026] **Navigating the Impact of Augmentation Computing Intelligence, AI Literacy, and Human Integration in English Language Education 7.0 by Using Computer-Assisted Language Learning and Augmented (CALLedA) Model** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-04539-3_35)]
- [2026] **Multitasking with Generative AI: Experimental Evidence** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6153511)]
- [2026] **Mastering the Machine: Human-AI Co-Creation, Copyright, and the Future of the Creative Industries** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6701198)]
- [2026] **Human-AI and Social Robots Creative Collaboration** [[paper](https://doi.org/10.1007/978-3-032-07753-0_8)]
- [2026] **Human-AI Collaboration in Participatory Design: Refining the Writing Analytics Tool** *OSF Preprints (OSF Preprints)* [[paper](https://osf.io/8j9y6)]
- [2026] **How Generative AI is Changing Our World: Reflections from a Geographical Perspective** *Key challenges in geography* [[paper](https://doi.org/10.1007/978-3-032-05201-8_2)]
- [2026] **Epistemology in the Age of AI: Rethinking Knowledge, Polymathy, and Human Cognition** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6182658)]
- [2026] **Beyond Automated Scoring: Toward Dialogic Assessment and Interactional Fairness in Human–AI Collaboration** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-032-29791-4_30)]
- [2026] **Beyond AI-assisted Writing: Distributed Collaborative Cognition in Interdisciplinary Policy Research A Methodological Reflection on Recursive Human-AI Knowledge Formation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6881761)]
- [2026] **Augmenting Collective Intelligence Through Human–AI Co-creation in Real-Time Platforms** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-95-7292-2_2)]
- [2026] **Activity systems in transition: GenAI-Mediated thesis writing strategies and contradictions among Chinese doctoral students in Australia** *System* [[paper](https://doi.org/10.1016/j.system.2026.104002)]
- [2026] **AI Research should Keep Humans Human in the age of AI** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6313941)]
- [2026] **A Study on the Intersection of AI and Human Creativity** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5945094)]

##### 2025

- [2025] **The Fallacy of AI Makes You Stop Thinking** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17815153)]
- [2025] **Learner Perceptions of Reflective Writing Instruction Using an AI Music Generator** [[paper](https://doi.org/10.37736/kjlr.2025.12.16.6.10)]
- [2025] **Is AI working wonders in EFL Writing in China- A review study of AI-aided EFL writing practicein China** *Region - Educational Research and Reviews* [[paper](https://doi.org/10.32629/rerr.v7i8.4514)]
- [2025] **Collaboration between individuals and AI: fusing mental effort and AI for work meaningfulness** *AI & Society* [[paper](https://doi.org/10.1007/s00146-025-02772-2)]
- [2025] **‘AI-Learner Partnership:’: Psychological Mechanisms and Developmental Trajectories of EFL Learners’ Writing Agency in GenAI-Assisted Courses** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-7972095/v1)]
- [2025] **Human-AI collaboration in vocational writing: Building a framework for adaptive English learning** *DergiPark (Istanbul University)* [[paper](https://dergipark.org.tr/en/pub/jetol/article/1821890)]
- [2025] **Human–AI Collaboration: A Responsible Future in Scientific Writing** *OSF Preprints (OSF Preprints)* [[paper](https://osf.io/6gxyj)]
- [2025] **Human–AI Collaboration: Students’ Changing Perceptions of Generative Artificial Intelligence and Active Learning Strategies** *Sustainability* [[paper](https://doi.org/10.3390/su17188387)]
- [2025] **Can theory-driven learning analytics dashboard enhance human-AI collaboration in writing learning? Insights from an empirical experiment** *The Internet and Higher Education* [[paper](https://doi.org/10.1016/j.iheduc.2025.101054)]
- [2025] **AI Writing Is Always Embodied: Building a Critical Awareness of the Invisible Labor of Humans-in-the-Loop in AI Products** *College Composition and Communication* [[paper](https://doi.org/10.58680/ccc202577139)]
- [2025] **From Dependence to Development: The Role of AI in Enhancing Writing Proficiency Among Chinese English Majors** *Journal of Posthumanism* [[paper](https://doi.org/10.63332/joph.v5i8.3159)]
- [2025] **Cognitive Artificial Intelligence for Health and Climate: Deep Models, Interpretability, and Decision Support** [[paper](https://doi.org/10.70593/978-93-7185-745-1)]
- [2025] **Effects of generative artificial intelligence on cognitive effort and task performance: study protocol for a randomized controlled experiment among college students** *Trials* [[paper](https://doi.org/10.1186/s13063-025-08950-3)]
- [2025] **The evolution of STEM education and the transition to STEAM/STREAM** *Aquademia* [[paper](https://doi.org/10.29333/aquademia/16313)]
- [2025] **Potentials and pitfalls of Google Gemini in writing: Implications for educators** *Assessing Writing* [[paper](https://doi.org/10.1016/j.asw.2025.100955)]
- [2025] **GPT as book reviewer: A move and syntactic complexity analysis of GPT-generated versus scholar-written academic book reviews** *Journal of English for Academic Purposes* [[paper](https://doi.org/10.1016/j.jeap.2025.101533)]
- [2025] **How Not to Collaborate With Large Language Models** [[paper](https://doi.org/10.1093/9780198945215.003.0071)]
- [2025] **Education AI: exploring the impact of artificial intelligence on education in the digital age** *International Journal of Systems Assurance Engineering and Management* [[paper](https://doi.org/10.1007/s13198-025-02755-y)]
- [2025] **Ai-Driven Autonomous Vehicles And Legal Liability: Redefining Accountability In Human-Ai Collaborative Systems** *International Journal of Environmental Sciences* [[paper](https://doi.org/10.64252/3ffewb32)]
- [2025] **Human-AI Collaboration in Writing: A Multidimensional Framework for Creative and Intellectual Authorship** *International Journal of Changes in Education* [[paper](https://doi.org/10.47852/bonviewijce52024908)]
- [2025] **Exploring Human-AI Collaboration in Educational Contexts: Insights from Writing Analytics and Authorship Attribution** [[paper](https://doi.org/10.1145/3706468.3706536)]
- [2025] **Do AI-generative tools kill or nurture creativity in EFL teaching and learning?** *Education and Information Technologies* [[paper](https://doi.org/10.1007/s10639-025-13409-8)]
- [2025] **Understanding Human-GenAI Collaboration in Writing in the Age of Generative AI: A Systematic Review of Literature** [[paper](https://doi.org/10.13140/rg.2.2.23429.31200)]
- [2025] **Structural Language and the Second Curve of Expression: Designing a Native Interface for Human–AI Co-Creation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5395291)]
- [2025] **Responsible AI Integration into Research Practice** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5337355)]
- [2025] **Idea Co-Construction or Friction: Collaboration Patterns in Human-AI Co-Writing (Poster 18)** [[paper](https://doi.org/10.3102/2186882)]
- [2025] **Human-AI Collaboration with ChatGPT: A Systematic Review of Implications for Finance, Law, and Healthcare** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5394893)]
- [2025] **Human-AI Collaboration in Vietnamese Students’ Argumentative Writing: A Mixed-Methods Study** *Studies in computational intelligence* [[paper](https://doi.org/10.1007/978-3-032-01348-4_6)]
- [2025] **Generative Artificial Intelligence in Audiovisual Screenwriting** *Research series on responsible enterprise ecosystems* [[paper](https://doi.org/10.1007/978-3-031-80411-3_8)]
- [2025] **Generative AI in Higher Education: Teaching, Assessment, and Research in the AI** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5345033)]
- [2025] **Generative AI and the Evolution of Artistic Creativity** *Springer series on cultural computing* [[paper](https://doi.org/10.1007/978-3-031-86551-0_10)]
- [2025] **From Passive Assistance to Active Scaffolding: How A Pedagogy-Informed Generative AI Supports Human-AI Collaboration for Critical Thinking** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5944157)]
- [2025] **FULLY AI-GENERATED RESEARCH: TESTING THE LIMITS OF AUTONOMOUS PAPER WRITING** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5277919)]
- [2025] **Developing AI Literacy in the Classroom: AI–Human Collaboration and Ethical AI** *Smart innovation, systems and technologies* [[paper](https://doi.org/10.1007/978-981-96-0426-5_28)]
- [2025] **Attributing AI Authorship: Towards a System of Icons for Legal and Ethical Disclosure** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5152508)]
- [2025] **A Study of Human-AI Interaction Patterns in Artificial Intelligence-Assisted Second Language Writing** *International Journal of English Literature and Social Sciences* [[paper](https://doi.org/10.22161/ijels.102.8)]

##### 2024

- [2024] **Artificially funny: collaborative play at the intersection of AI, literature and humour** [[paper](https://doi.org/10.4324/9781003255789-37)]
- [2024] **Exploring AI-Assisted Writing Instruction from the Perspective of Human-Computer Collaboration** *THE JOURNAL OF ASIAN STUDIES* [[paper](https://doi.org/10.21740/jas.2024.11.30.2.385)]
- [2024] **Developing a Generative AI Model Using Rhetoric Prompts - Focusing on the Comparison of Rhetorical Writing and Rhetorical Prompts -** *한국실내디자인학회 논문집* [[paper](https://doi.org/10.14774/jkiid.2024.33.5.079)]
- [2024] **Writing Theory for Generative AI** [[paper](https://dx.doi.org/10.4324/9781003493563-4)]
- [2024] **Human-Centered AI** *Design and Culture* [[paper](https://doi.org/10.1080/17547075.2024.2386752)]
- [2024] **Using a hybrid of artificial intelligence and template-based method in automatic item generation to create multiple-choice questions in medical education: Hybrid AIG** *medRxiv* [[paper](https://doi.org/10.1101/2024.07.15.24310424)]
- [2024] **Research design and writing of scholarly articles: new artificial intelligence tools available for researchers** *Endocrine* [[paper](https://doi.org/10.1007/s12020-024-03977-z)]
- [2024] **Teaching AI Through Complex Problem Solving: Early AI-Assisted Educational Design Artifacts (2024)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20766978)]
- [2024] **Artificial intelligence (AI) content detection in ASCO scientific abstracts from 2021 to 2023.** *Journal of Clinical Oncology* [[paper](https://doi.org/10.1200/jco.2024.42.16_suppl.1565)]
- [2024] **Algorithmically-driven writing and academic integrity: exploring educators' practices, perceptions, and policies in AI era** *International Journal for Educational Integrity* [[paper](https://doi.org/10.1007/s40979-024-00153-8)]
- [2024] **Who has the last word? Lessons from using ChatGPT to develop an AI-based Spanish writing assistant** *Círculo de lingüística aplicada a la comunicación* [[paper](https://doi.org/10.5209/clac.91985)]
- [2024] **Unravelling the Evolution of Generative AI in Communication Education** *Advances in educational technologies and instructional design book series* [[paper](https://doi.org/10.4018/979-8-3693-0831-8.ch003)]
- [2024] **Revolutionizing healthcare through Chat GPT: AI is accelerating medical diagnosis** *Oral Oncology Reports* [[paper](https://doi.org/10.1016/j.oor.2024.100222)]
- [2024] **Exploring the bioethical implications of using artificial intelligence in writing research proposals** *Perspectives in Clinical Research* [[paper](https://doi.org/10.4103/picr.picr_226_23)]
- [2024] **The Symbiosis of AI and Human Agency in Digital Authorship: Redefining the Landscape of Contemporary Literature** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-031-50887-5_26)]
- [2024] **Negotiating Meaning with Machines: Ai's Role in Doctoral Writing Pedagogy** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.4793715)]

##### 2023

- [2023] **Towards development of an effective AI-based system for relevant comment generation** [[paper](https://doi.org/10.1145/3632754.3632770)]
- [2023] **Preparing Ourselves for Artificial Intelligence: A Review of The Alignment Problem and God, Human, Animal, Machine** *Irish Journal of Technology Enhanced Learning* [[paper](https://doi.org/10.22554/ijtel.v7i2.139)]
- [2023] **AI-Generated Content Detectors: Boon or Bane for Scientific Writing** *Indian Journal of Science and Technology* [[paper](https://doi.org/10.17485/ijst/v16i39.1632)]
- [2023] **Embracing artificial intelligence in medical writing: A new era of efficiency and collaboration** *Medical Writing* [[paper](https://dx.doi.org/10.56012/iamc1709)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Guest editorial: AI-assisted academic writing, translation, and literacy for the promotion of human agency in higher education** *Artificial Intelligence in Education* [[paper](https://doi.org/10.1108/aiie-12-2026-269)]
- [2026] **From tool to scaffold: structured human–AI collaboration and its effects on academic writing and digital critical thinking among Saudi EFL learners** *Frontiers in Psychology* [[paper](https://doi.org/10.3389/fpsyg.2026.1830103)]
- [2026] **AI Leadership and Human-Centered Design in Global Education: Reflections from Osaka, Japan (2026)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18796178)]
- [2026] **Rethinking Programming Skills in the Age of Generative AI** *Proceedings of the ... Annual Hawaii International Conference on System Sciences/Proceedings of the Annual Hawaii International Conference on System Sciences* [[paper](https://doi.org/10.24251/hicss.2026.863)]
- [2026] **Exploring learner prompting and AI feedback quality in L2 Portuguese writing** *Texto Livre Linguagem e Tecnologia* [[paper](https://doi.org/10.1590/1983-3652.2026.63188)]
- [2026] **Ep. 129: Stop Writing Prompts and Start Writing Constitutions** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19357859)]
- [2026] **Comment on “Diagnostic Performance of Multimodal Large Language Models in the Analysis of Oral Pathology”** *Oral Diseases* [[paper](https://doi.org/10.1111/odi.70216)]
- [2026] **A Report on the Iterative Model and Efficacy Practice of English Speech Draft Writing from the Perspective of Human-AI Collaboration** *Journal of International Education and Development* [[paper](https://doi.org/10.47297/wspiedwsp2516-250039.20261001)]

##### 2025

- [2025] **INTEGRARE IL PROMPT ENGINEERING TRA LE ABILITÀ TRASVERSALI PER L’EDUCAZIONE LINGUISTICA: UNO STUDIO DI CASO** *Italiano LinguaDue* [[paper](https://doi.org/10.54103/2037-3597/30456)]
- [2025] **PromptPilot: Improving Human-AI Collaboration Through LLM-Enhanced Prompt Engineering** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.00555)]
- [2025] **Artificial intelligence and pharmacy practice research: call to action** *International Journal of Pharmacy Practice* [[paper](https://doi.org/10.1093/ijpp/riaf096)]
- [2025] **Writing Is Coding** *International Journal of Online Pedagogy and Course Design* [[paper](https://doi.org/10.4018/ijopcd.385016)]
- [2025] **Epistemic responsibility: toward a community standard for human-AI collaborations** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1635691)]
- [2025] **Bridging LMS and generative AI: dynamic course content integration (DCCI) for enhancing student satisfaction and engagement via the ask ME assistant** *Journal of Computers in Education* [[paper](https://arxiv.org/abs/2504.03966)]

##### 2024

- [2024] **Process over product** *Pacific Journal of Technology Enhanced Learning* [[paper](https://dx.doi.org/10.24135/pjtel.v6i1.190)]
- [2024] **Foundation models: the future of surgical artificial intelligence?** *British journal of surgery* [[paper](https://doi.org/10.1093/bjs/znae090)]
- [2024] **Augmenting the Author: Exploring the Potential of AI Collaboration in Academic Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.16071)]

##### 2023

- [2023] **Pair programming with ChatGPT for sampling and estimation of copulas** *Computational Statistics* [[paper](https://doi.org/10.1007/s00180-023-01437-2)]
- [2023] **ChatGPT for Research and Publication: A Step-by-Step Guide** *The Journal of Pediatric Pharmacology and Therapeutics* [[paper](https://doi.org/10.5863/1551-6776-28.6.576)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **How Creative Is AI Writing? Generative and Collaborative AI in Japanese Fiction** *Journal of Creative Communications* [[paper](https://doi.org/10.1177/09732586261463934)]

##### 2025

- [2025] **Responsible Integration of Artificial Intelligence in Rapid Reviews: A Position Statement From the Cochrane Rapid Reviews Methods Group** *Cochrane Evidence Synthesis and Methods* [[paper](https://doi.org/10.1002/cesm.70063)]

##### 2024

- [2024] **The Spectre of Generative AI Over Advertising, Marketing, and Branding** [[paper](https://doi.org/10.22541/au.170534566.63147021/v1)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2026

- [2026] **PeerPrism: Peer Evaluation Expertise vs Review-writing AI** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.14513)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **When AI Magic Meets Creative Writing: The AI Noberisuto Literary Prize and the Boundaries of Non-human (Co)authorship** *Journal of International Crisis and Risk Communication Research* [[paper](https://stars.library.ucf.edu/elo2026/algorithmsandimaginaries/schedule/42)]
- [2026] **Toward a Shared Poetics: A Case Study in Long-Term Human–AI Literary Collaboration** [[paper](https://works.hcommons.org:dm6vn-vgj57)]
- [2026] **Toward a Shared Poetic: Observations on Extended Human–AI Literary Collaboration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21651724)]
- [2026] **Sequencing Human-Artificial Intelligence Creative Writing Collaboration Affects Perceived Authorship** *Cureus Journal of Computer Science.* [[paper](https://doi.org/10.7759/s44389-026-00183-y)]
- [2026] **CRAFT: Exploring Wearable Creative AI on Smart Glasses for Fiction Writing in Real-World Contexts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.21394)]
- [2026] **AI in Creative Writing: Partner or Rival of Human Creativity** *International Journal of Science Engineering and Technology* [[paper](https://doi.org/10.5281/zenodo.21715729)]
- [2026] **Material for Thought: Generative AI as an Active Creative Medium** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.19832)]
- [2026] **The Substrate Consultant: Irreplaceable Human Data and the Future of Human-AI Collaboration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19513635)]
- [2026] **Subjective Emotional Interpretation and Relatability of AI-Generated Versus Human-Created Content** *INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT* [[paper](https://doi.org/10.55041/ijsrem60452)]
- [2026] **Plotania: Exploring Transparency Trade-offs in AI Co-Writing Through Virtual Readers and Transparent Attribution** [[paper](https://doi.org/10.1145/3772318.3790926)]
- [2026] **Human-AI Interaction Traces as Blackout Poetry: Reframing AI-Supported Writing as Found-Text Creativity** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.09605)]
- [2026] **Human vs. LLM Creativity: A Comparative Analysis of Task-Dependent Asymmetry and Linguistic Mechanisms** *Journal of Intelligence* [[paper](https://doi.org/10.3390/jintelligence14020027)]
- [2026] **Cyber-Creativity: Challenges and Frictions in Human-AI Collaboration** [[paper](https://doi.org/10.1109/acdsa67686.2026.11468155)]
- [2026] **Artificial intelligence in writing: unveiling a research landscape** *IAES International Journal of Artificial Intelligence* [[paper](https://doi.org/10.11591/ijai.v15.i1.pp66-75)]
- [2026] **From Tools to Teammates? Examining Human–AI Synergy in Educational Design Fictions Through the Lens of Extended Cognition** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-032-29794-5_25)]
- [2026] **Creative Writing and AI: A 2024 Case Study** *Public humanities.* [[paper](https://doi.org/10.1017/pub.2025.10098)]
- [2026] **Computer Mediated Creative Writing (CMCW): A Process-Oriented Framework for Human–AI Collaboration** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6052219)]

##### 2025

- [2025] **Enterprise implementation of multimodal AI systems: a mixed-methods study on ‘Writing is Coding’ framework for organizational creative and innovative intelligence** *Enterprise Information Systems* [[paper](https://doi.org/10.1080/17517575.2025.2596840)]
- [2025] **Agency in Human-AI Collaboration for Image Generation and Creative Writing: Preliminary Insights from Think-Aloud Protocols** *Creativity Research Journal* [[paper](https://doi.org/10.1080/10400419.2025.2587803)]
- [2025] **Redefining roles: Human–AI collaboration in screenwriting** *Journal of Screenwriting* [[paper](https://doi.org/10.1386/josc_00190_1)]
- [2025] **Generative AI Does Not Erase Individual Differences in Human Creativity** *PsyArXiv (OSF Preprints)* [[paper](https://osf.io/jszrn)]
- [2025] **Generative AI for Automated Creative Writing Assistance: A Computational Approach to English Narrative Structuring** [[paper](https://doi.org/10.1109/iconat66879.2025.11362573)]
- [2025] **The Differential Role of Human Capital in Generative AI’s Impact on Creative Tasks** *Academy of Management Proceedings* [[paper](https://doi.org/10.5465/amproc.2025.16077abstract)]
- [2025] **1. WRITING A SONG FOR AIIA** *The White Horse Press eBooks* [[paper](https://doi.org/10.63308/63878687083054.ch01)]
- [2025] **Neural and Cognitive Impacts of AI: The Influence of Task Subjectivity on Human-LLM Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.04167)]
- [2025] **Lyric Poetry in the Face of Posthumanism: An Analysis of Generative AI-Assisted Poetry Writing** [[paper](https://doi.org/10.1145/3698061.3726919)]
- [2025] **Harnessing AI in Digital Humanities: Innovations and Implications** *Journal of Computational Science and Applications (JCSA) ISSN 3079-0867 (Onilne)* [[paper](https://doi.org/10.51846/jcsa.v2i1.3506)]
- [2025] **From Quill to Code: The Evolution of Literary Expression in the Age of AI** *International Journal of Scientific Research and Modern Technology.* [[paper](https://doi.org/10.38124/ijsrmt.v4i4.410)]
- [2025] **AI + Nonet: Machine and Human Poetry Collaboration** [[paper](https://doi.org/10.4324/9781003581239-9)]
- [2025] **The Unbearable Lightness of Imagination in the GenAI Era: Changing Creative Writing Practices in School** *Postdigital science and education* [[paper](https://doi.org/10.1007/978-3-032-01539-6_14)]
- [2025] **Generative Literature: The Role of Artificial Intelligence in the Creative Writing Process** *Allure Journal* [[paper](https://doi.org/10.26877/allure.v5i1.19959)]

##### 2024

- [2024] **Unleashing Human Potential: A Framework for Augmenting Co-Creation with Generative AI** *Proceedings of the International Conference on AI Research.* [[paper](https://doi.org/10.34190/icair.4.1.3074)]
- [2024] **Designing Human and Generative AI Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.14199)]
- [2024] **Code, Consciousness, and Composition: AI Ethics and Human-AI Co-Created Works** *TSpace (University of Toronto)* [[paper](https://hdl.handle.net/1807/141321)]
- [2024] **Artificial intelligence and the future of our sociolinguistic work** *Journal of Sociolinguistics* [[paper](https://doi.org/10.1111/josl.12678)]
- [2024] **The Next Word: A Framework for Imagining the Benefits and Harms of Generative AI as a Resource for Learning to Write** *Reading Research Quarterly* [[paper](https://doi.org/10.1002/rrq.567)]
- [2024] **Establishing the importance of co-creation and self-efficacy in creative collaboration with artificial intelligence** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-024-69423-2)]
- [2024] **Rethinking Creativity Frameworks for Artificial Intelligence** [[paper](https://doi.org/10.4324/9781003453901-5)]
- [2024] **Who Benefits More? The Role of AI-Human Interaction in Creativity Augmentation** *University of Birmingham Research Portal (University of Birmingham)* [[paper](https://research.birmingham.ac.uk/en/publications/718782eb-b462-4272-9649-e498c703c2a4)]
- [2024] **"It Felt Like Having a Second Mind": Investigating Human-AI Co-creativity in Prewriting with Large Language Models** *Proceedings of the ACM on Human-Computer Interaction* [[paper](https://doi.org/10.1145/3637361)]
- [2024] **ChatGPT and Teacher Human-Machine Collaboration for Personalized Teaching - Taking Poetry Writing Teaching as an Example** [[paper](https://doi.org/10.1109/iceit61397.2024.10540814)]
- [2024] **Artificial Intelligence in Diabetes Management and Research** *Chronicle of Diabetes Research and Practice* [[paper](https://doi.org/10.4103/cdrp.cdrp_14_23)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **AI assisted, mentor-guided narrative review writing task for medical students, a novel educational strategy to enhance research and academic writing** *Medical Teacher* [[paper](https://doi.org/10.1080/0142159x.2025.2604240)]

##### 2025

- [2025] **HUMAN–AI COLLABORATION IN KNOWLEDGE WORK: PRODUCTIVITY, ERRORS, AND ETHICAL RISK** *Lex localis - Journal of Local Self-Government* [[paper](https://doi.org/10.52152/6q2p9250)]
- [2025] **The power duo: unleashing cognitive potential through human-AI synergy in STEM and non-STEM education** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1534582)]

##### 2024

- [2024] **The Impact of Generative AI on Managerial Productivity, Decision-Making, and Organizational Performance** *Journal of Information Systems Engineering & Management* [[paper](https://doi.org/10.52783/jisem.v9i4s.13702)]
- [2024] **Human Bias in the Face of AI: Examining Human Judgment Against Text Labeled as AI Generated** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.03723)]
- [2024] **The emergence of ChatGPT: An opportunity or adversity for scholarly communications** *International Journal of Ayurveda Research* [[paper](https://doi.org/10.4103/ijar.ijar_7_24)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **Stop perfecting the feedback, start supporting the uptake: rethinking AI in writing instruction** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2026.1737037)]

##### 2025

- [2025] **The Human and Machine** *Visible Language* [[paper](https://doi.org/10.34314/3kvkgp44)]
- [2025] **Artificial Intelligence Disclosure in Academic Nursing: A Framework for Editorial Policy and Practice** *Nurse author & editor* [[paper](https://doi.org/10.1111/nae2.70002)]

[⬆ Back to top](#paper-list)

#### Autocomplete

##### 2026

- [2026] **When Stereotypes GTG: The Impact of Predictive Text Suggestions on Gender Bias in Human-AI Co-Writing** [[paper](https://arxiv.org/abs/2409.20390)]

##### 2024

- [2024] **Generative artificial intelligence, co‐evolution, and language education** *Modern Language Journal* [[paper](https://doi.org/10.1111/modl.12932)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **Misclassification of text in Ai detection: A serious limitation of Ai detectors and Its threats to human-based scholarly writing** *Journal of the Pakistan Medical Association* [[paper](https://doi.org/10.47391/jpma.40793)]
- [2026] **AI-generated versus human-developed assessment tasks in EFL context: insights from TPCK model** *Computers and Education Open* [[paper](https://doi.org/10.1016/j.caeo.2026.100415)]
- [2026] **Effects of AI-Powered Feedback on English Writing Development: A Systematic Review of Meta-Analytic and Empirical Evidence** *أطراس* [[paper](https://doi.org/10.70091/atras/vol07no02.06)]
- [2026] **Artificial Intelligence in Language Education: Human-AI Interaction, Pedagogical Design, and Ethical Challenges** *Global spectrum of research and humanities.* [[paper](https://doi.org/10.69760/gsrh.0260303001)]
- [2026] **Writing Centre 2.0: Towards improving student writing through consultant and GenAI collaboration** *Critical Studies in Teaching and Learning* [[paper](https://doi.org/10.17159/cristal.v14i1.27674)]
- [2026] **The Application of Generative AI in Chinese as a Second Language Writing** *Springer Link (Chiba Institute of Technology)* [[paper](https://www.shs-conferences.org/10.1051/shsconf/202623504012/pdf)]
- [2026] **Students' preferences in English writing tutorial and feedback comparing AI and human instructors** *Digilib UIN Sunan Ampel Surabaya (UIN Sunan Ampel)* [[paper](https://digilib.uinsby.ac.id/91317/1/Aisya%20Fadila%20Firdaus%20Umar_06020522026.pdf)]
- [2026] **AI-Assisted Research Writing: Graduate Students' Experiences, Outcomes and Academic Integrity** *International Journal of Learning Teaching and Educational Research* [[paper](https://doi.org/10.26803/ijlter.25.5.8)]
- [2026] **Designing traceable, prompt-scaffolded generative AI feedback to support EFL grammar accuracy and writing complexity: evidence from male Saudi undergraduates** *Interactive Learning Environments* [[paper](https://doi.org/10.1080/10494820.2026.2649549)]
- [2026] **Pedagogical Value and Limitations of Automated Writing Evaluation in English as a Second Language Writing Instruction** *Communications in Humanities Research* [[paper](https://doi.org/10.54254/2753-7064/2026.ht32003)]
- [2026] **AI in Collaborative Writing** [[paper](https://doi.org/10.1002/9781394266401.ch16)]
- [2026] **EMPLOYING AI TOOLS IN ENHANCING STUDENTS’ WRITING SKILLS: APPLIED APPROACHES** *Вісник науки та освіти* [[paper](https://doi.org/10.52058/2786-6165-2026-1(43)-1299-1319)]
- [2026] **An Epistemological and Ethical Examination of AI-Assisted Writing in Postgraduate Research at the Federal University of Lafia** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18510704)]
- [2026] **Human AI Collaboration Tools for boosting productivity of Library Staff in academic institutions** *Rivers State University Journal of Librarianship Information and Contemporary Studies (RSU-JOLICS)* [[paper](https://doi.org/10.61955/xrcars)]
- [2026] **Crimson Hexagon / NH-OS DOI Registry: Complete Document Archive — Comprehensive Index of 91 DOI-Anchored Documents (January 2026)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18284689)]

##### 2025

- [2025] **Enhancing student writing feedback through teacher–AI collaboration in higher education** *Journal of Education and e-Learning Research* [[paper](https://doi.org/10.20448/jeelr.v12i4.7877)]
- [2025] **Narrative Explorations of EFL Learners’ Engagement with AI Tools in Developing Writing Proficiency** *DUTIES Education and Humanities International Journal* [[paper](https://doi.org/10.70152/duties.v1i2.222)]
- [2025] **Generative AI-Driven Pathways for Optimizing English Writing Quality: An Empirical Study in Applied Universities** [[paper](https://doi.org/10.1109/icnc-fskd67701.2025.11197985)]
- [2025] **Students’ Perceptions of AI-Powered Feedback in English Writing: Benefits and Challenges in Higher Education** *International Journal of Changes in Education* [[paper](https://doi.org/10.47852/bonviewijce52025580)]
- [2025] **Exploring EFL Students’ Experience of Using AI Tools In Developing English Academic Writing** *Digilib UIN Sunan Ampel Surabaya (UIN Sunan Ampel)* [[paper](https://digilib.uinsby.ac.id/84863/3/Satria%20Ahmad%20Pardiansyah_06020521063%20OK.pdf)]
- [2025] **Ethical Integration of AI in First-Year Writing: Practical Assignments to Foster Academic Integrity and Critical Engagement** *Journal of International Crisis and Risk Communication Research* [[paper](https://stars.library.ucf.edu/teachwithai/2025/friday/14)]
- [2025] **Enhancing Arabic writing skills using Chat GPT-based AI learning models: A tridimensional human-AI collaboration framework** *Indonesian Journal of Applied Linguistics* [[paper](https://doi.org/10.17509/ijal.v15i1.75378)]
- [2025] **The GenAI Application of Personalized Learning and Human-AI Collaboration in English Education** [[paper](https://doi.org/10.1145/3746469.3746496)]
- [2025] **Fostering Ethical AI Integration in First-Year Writing: A Case Study on Human-Tool Collaboration in Artificial Intelligence Literacy** *Journal of Library Administration* [[paper](https://doi.org/10.1080/01930826.2025.2468136)]
- [2025] **Teacher–AI Collaboration in Formative Writing Assessment: Hybrid Feedback Models with Grammarly in ELT** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5822271)]

##### 2024

- [2024] **Revolutionizing Academic Medical Writing: The Role of AI** *Journal of Nursing and Allied Health* [[paper](https://doi.org/10.37939/jnah.v2i04.82)]
- [2024] **Collaboration of Artificial Intelligence and Journalists in Online Media from the Perspective of Human-Machine Communication** *Kalijaga Journal of Communication* [[paper](https://doi.org/10.14421/kjc.61.06.2024)]
- [2024] **Human-AI Collaboration: Exploring Synergies and Future Directions** [[paper](https://doi.org/10.22541/au.172560988.80084396/v1)]
- [2024] **Twenty‐first century technologies and language education: Charting a path forward** *Modern Language Journal* [[paper](https://doi.org/10.1111/modl.12924)]
- [2024] **Exploring Students’ Generative AI-Assisted Writing Processes: Perceptions and Experiences from Native and Nonnative English Speakers** *Technology Knowledge and Learning* [[paper](https://doi.org/10.1007/s10758-024-09744-3)]
- [2024] **A systematic literature review of empirical research on ChatGPT in education** *Discover Education* [[paper](https://doi.org/10.1007/s44217-024-00138-2)]
- [2024] **Application of the AIGC Large Language Model in College English Writing Teaching** *Chinese Language and Literature* [[paper](https://dx.doi.org/10.57237/j.cll.2024.01.002)]

[⬆ Back to top](#paper-list)

#### Interactive Writing

##### 2026

- [2026] **Across-the-board analysis of doctoral students’ GenAI literacy skills and self-perceived human–AI collaboration in writing scientific articles** *Learning Futures and Emerging Technologies* [[paper](https://doi.org/10.1108/lfet-03-2026-0031)]
- [2026] **Reconceptualizing the target domain of AI-assisted Writing: A multi-case analysis of AI literacy integration in writing courses in Hong Kong universities** *Asian Journal of English Language Teaching* [[paper](https://doi.org/10.65961/ajelt-2026-4-004)]
- [2026] **Modes of Human-AI Collaboration in Text: Benchmarks, Metrics, and Interpretive Tasks** *Scholarworks (University of Massachusetts Amherst)* [[paper](https://hdl.handle.net/20.500.14394/58306)]
- [2026] **Humanly: A Configurable and Traceable Environment for Human-AI Collaborative Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.21758)]
- [2026] **New writing communities: AI-driven cross-linguistic collaboration in primary school** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2026.1800040)]
- [2026] **Editor, Tutor, or Thinking Partner: How Students Position AI in the Writing Classroom** [[paper](https://doi.org/10.35542/osf.io/mbksp_v1)]
- [2026] **Exploring Human-AI Co-Creativity in English Literature** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18957008)]
- [2026] **Collaborative knowledge construction with generative AI: Exploring argumentative co-writing processes through n-gram and cluster analysis** [[paper](https://doi.org/10.31234/osf.io/8kmyz_v2)]
- [2026] **Generative AI as a Catalyst for Innovative Collaboration: Enhancing Group Projects Among Saudi Students in Digital Learning Environments** *AHFE international* [[paper](https://doi.org/10.54941/ahfe1007185)]

##### 2025

- [2025] **Human–AI Collaborative Writing Systems: A Technical Architecture for Controlled Co-Creation** *International journal of research and scientific innovation* [[paper](https://doi.org/10.51244/ijrsi.2025.1213cs0010)]
- [2025] **PAPER 8: BEYOND COGNITION - HYBRID BODY EMERGENCE AND EMBODIED HUMAN-AI COLLABORATION; 10-Paper Series on Compressed Communication & Cognitive Acceleration; Paper 8 of 10: Hybrid Body Theory & Emergence Phenomena** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17554473)]
- [2025] **Explainable AI Techniques to Detect Authorial Voice Shifts in Collaborative Digital Writing Platforms** [[paper](https://doi.org/10.1109/iconstem65670.2025.11374896)]
- [2025] **Human-AI Collaborative Management: Measuring Effectiveness in Hybrid Decision-Making Teams** *International Journal of Administration and Management Research Studies (IJAMRS)* [[paper](https://doi.org/10.63090/ijamrs/3107.9695.0010)]
- [2025] **Human-AI Collaborative Writing: Pedagogies for Using LLMs to Improve the Ideation and Revision Process in Academic Writing** *Artificial Intelligence Education Studies* [[paper](https://doi.org/10.6914/aiese.010202)]
- [2025] **Human-Centered AI Communication in Co-Creativity: An Initial Framework and Insights** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.18385)]

##### 2024

- [2024] **Rethinking Trust in Human-AI Collaboration in the Generative AI Era** *International Conference on Computers in Education* [[paper](https://doi.org/10.58459/icce.2024.4836)]
- [2024] **Teaming Up with an AI: Exploring Human–AI Collaboration in a Writing Scenario with ChatGPT** *AI* [[paper](https://doi.org/10.3390/ai5030065)]
- [2024] **Teaming up with an AI: Exploring human-AI collaboration in a writing scenario with ChatGPT** [[paper](https://doi.org/10.31219/osf.io/extmc)]

##### 2023

- [2023] **Narratron: Collaborative Writing and Shadow-playing of Children Stories with Large Language Models** [[paper](https://doi.org/10.1145/3586182.3625120)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **⭐ "AI Is Not an Opponent but a Friend: Transforming Artificial Intelligence into a Partner for Human Progress"** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22169857)]
- [2026] **Writing Models: A Review of Contemporary Literature** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21719954)]
- [2026] **Guest editorial: STARA (smart technology, AI, robotics and algorithms): implications for career research** *Career Development International* [[paper](https://doi.org/10.1108/cdi-06-2026-665)]
- [2026] **Building Bridges, Not Replacements: Using AI to Strengthen Peer Collaboration in EFL Writing** [[paper](https://doi.org/10.47908/44/13)]
- [2026] **Rethinking Graduate AI Competence: A Holistic AI Literacy Model for Higher Education** [[paper](https://doi.org/10.35542/osf.io/ewprv_v1)]
- [2026] **Research on the Development Path of College Students’ English Writing Competence from the Perspective of Human-Machine Collaboration: An Exploratory Application Based on Generative Artificial Intelligence** *Journal of Teaching Innovation and Practice* [[paper](https://doi.org/10.65170/jtr.v2i1.41)]
- [2026] **CoAuthorAI: A Human in the Loop System For Scientific Book Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.19772)]
- [2026] **Human-AI Collaboration in Agile Environments: Survey Results** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18504873)]
- [2026] **Editorial: The changing landscape of marketing research in the AI era: prospects and challenges** *Journal of Research in Interactive Marketing* [[paper](https://doi.org/10.1108/jrim-02-2026-766)]
- [2026] **Unlocking the potential of computer vision in precision pig farming: a call for a collaborative data and AI models platform** *Animal Frontiers* [[paper](https://doi.org/10.1093/af/vfag003)]
- [2026] **Research That Matters: A Call for Enhancing Rigour and Relevance in Artificial Intelligence Research in Endodontics** *International Endodontic Journal* [[paper](https://doi.org/10.1111/iej.70094)]
- [2026] **Artificial intelligence in education: applications and limitations for teachers in low- and middle-income countries** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1681836)]
- [2026] **AI as a Catalyst for Change in Creative Workflows** *Proceedings of the ... Annual Hawaii International Conference on System Sciences/Proceedings of the Annual Hawaii International Conference on System Sciences* [[paper](https://doi.org/10.24251/hicss.2026.012)]

##### 2025

- [2025] **The 2025 Landscape of Generative AI in Scholarly Writing and Publishing: A Scoping Review of Uses and Ethical Approaches** *Journal of language and Education* [[paper](https://doi.org/10.17323/jle.2025.29876)]
- [2025] **New paradigm for aging research: aging studies through innovative AI applications and interdisciplinary collaborations** *Life Medicine* [[paper](https://doi.org/10.1093/lifemedi/lnaf039)]
- [2025] **Generative AI in Research Group Formation: Academic Perceptions and Institutional Pathways** *Information* [[paper](https://doi.org/10.3390/info16121081)]
- [2025] **Enhancing College English Writing Instruction: Leveraging AI for Teachers and Learners in China and Beyond** *Journal of Education Society and Behavioural Science* [[paper](https://doi.org/10.9734/jesbs/2025/v38i61448)]
- [2025] **Editorial: Smart infrastructure and safety innovation: AI-driven risk management and resilience strategies** *Smart and Sustainable Built Environment* [[paper](https://doi.org/10.1108/sasbe-11-2025-570)]
- [2025] **Writing for Pediatric Critical Care Medicine: What is Happening to Systematic Reviews?** *Pediatric Critical Care Medicine* [[paper](https://doi.org/10.1097/pcc.0000000000003847)]
- [2025] **Toward emotional mediation: generative AI in art therapy for psychosocial health support** *Frontiers in Public Health* [[paper](https://doi.org/10.3389/fpubh.2025.1690119)]
- [2025] **AI agents** *Underline Science Inc.* [[paper](https://doi.org/10.48448/zat6-pn10)]
- [2025] **When misunderstanding meets artificial intelligence: the critical role of trust in human–AI and human–human team communication and performance** *Frontiers in Psychology* [[paper](https://doi.org/10.3389/fpsyg.2025.1637339)]
- [2025] **Perceptions of AI Collaboration in Writing among Teacher Aspirants: An Empirical Cross-Sectional Study among Teacher Aspirants** *EthAIca* [[paper](https://doi.org/10.56294/ai2025426)]
- [2025] **Developing generative AI literacies through self-regulated learning: A human-centered approach** *Computers and Education Artificial Intelligence* [[paper](https://doi.org/10.1016/j.caeai.2025.100482)]
- [2025] **Vibe Coding: Is Human Nature the Ghost in the Machine?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.20918)]
- [2025] **Three discipline collaborative radiation therapy (3DCRT) special debate: AI structure segmentation is better than clinician contouring for both OARs and targets** *Journal of Applied Clinical Medical Physics* [[paper](https://doi.org/10.1002/acm2.70183)]
- [2025] **Traditional Chinese Medicine + artificial intelligence: Wuzhen consensus** *Acupuncture and Herbal Medicine* [[paper](https://doi.org/10.1097/hm9.0000000000000163)]
- [2025] **ChatGPT: A Tool for Communication and Lifelong Education in the AI Age** *International Journal on Lifelong Education and Leadership* [[paper](https://doi.org/10.25233/ijlel.1550548)]
- [2025] **The impact of ChatGPT on academic integrity in medical education: a developing nation perspective** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1554444)]
- [2025] **Ethical use of ChatGPT in education—Best practices to combat AI-induced plagiarism** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2024.1465703)]
- [2025] **Ethical challenges and regulatory pathways for artificial intelligence in rheumatology** *Rheumatology Advances in Practice* [[paper](https://doi.org/10.1093/rap/rkaf035)]

##### 2024

- [2024] **Sixty years of ethical evolution: The 2024 revision of the Declaration of Helsinki (DoH)** *Health care science* [[paper](https://doi.org/10.1002/hcs2.126)]
- [2024] **Precision animal husbandry: using artificial intelligence for camera traps to optimize animal production and management decision support systems** *Animal Frontiers* [[paper](https://doi.org/10.1093/af/vfae026)]
- [2024] **Empowering young minds: The future of computational thinking and AI education in early childhood** *Future in Educational Research* [[paper](https://doi.org/10.1002/fer3.69)]
- [2024] **Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.15701)]
- [2024] **The integration of artificial intelligence with robotic instruments in surgical practice** *British journal of surgery* [[paper](https://doi.org/10.1093/bjs/znae248)]
- [2024] **Generative AI in Assessing Writing and Assessing for Academic Purposes – Insights from a collaboration between two EALTA SIGs** *PHSG #Proforis (St.Gallen University of Teacher Education)* [[paper](https://proforis.phsg.ch/handle/20.500.14111/5683)]
- [2024] **Guest Editorial: Big data and artificial intelligence in healthcare** *Healthcare Technology Letters* [[paper](https://doi.org/10.1049/htl2.12086)]
- [2024] **Potentials of ChatGPT in Computer Programming: Insights from Programming Instructors** *Journal of Information Technology Education Research* [[paper](https://doi.org/10.28945/5240)]

##### 2023

- [2023] **Role of ChatGPT in health science and research: A correspondence addressing potential application** *Health Science Reports* [[paper](https://doi.org/10.1002/hsr2.1625)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **Zenetist Authorship and AI-Collaboration Provenance Standard** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21890287)]
- [2026] **No Provenance Without Return: Generative Custody, Reciprocal Collaborator Formation, and a Provenance Standard for Human–AI Research** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21957302)]
- [2026] **Generative AI Empowering College English Writing Teaching Model Construction, Practical Path, and Effect Evaluation** *Advanced Electromagnetics* [[paper](https://doi.org/10.7716/aem.v15i3.3743)]
- [2026] **Credential-Based and Artifact-Based Trust: Certifying Science in the Age of Human–AI Collaboration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21859700)]
- [2026] **ChatGPT for Intelligent Human–AI Interaction: Opportunities and Limitations** *International Bulletin of Applied Sciences and Technology* [[paper](https://doi.org/10.37547/ibast/volume06issue08-03)]
- [2026] **Artificial Intelligence as a Co-Worker: Transforming Employment, Skills, Productivity, and Human–AI Collaboration in the Future Workplace** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22109275)]
- [2026] **AI Engineering: Design, Reproducibility, and Accountability in the Age of AI** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21856466)]
- [2026] **Structured AI Collaboration in Software Development: A Workflow Architecture for High-Efficiency Human-AI Pairing** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21500809)]
- [2026] **Research on Human-AI Collaborative Agent Dynamic Feedback Mechanism for Primary Chinese Large-Unit Instruction** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2026.35500)]
- [2026] **Human–AI Collaboration in Academic Writing: Examining Cambodian EFL Undergraduates’ Perceptions of AI Tools in Writing Autonomy, Confidence, Motivation, Critical Thinking, Creativity, and Ethical Concerns** *Journal of Educational Technology Systems* [[paper](https://doi.org/10.1177/00472395261464692)]
- [2026] **From Automated Feedback to Human-AI Collaboration: Mechanisms and Pathways of AI Integration in Foreign Language Education** *Journal of Contemporary Educational Research* [[paper](https://doi.org/10.26689/jcer.v10i6.15626)]
- [2026] **Augmented Decision-Making in Financial Markets: A Human–AI Co-Creative Approach** *Artificial Intelligence and Applications* [[paper](https://doi.org/10.47852/bonviewaia62027538)]
- [2026] **Strategies for AI Use in Thesis Writing among Undergraduate Language Students: A Think-Aloud Protocol** *Asia Pacific Journal of Educators and Education* [[paper](https://doi.org/10.21315/apjee2026.41.1.18)]
- [2026] **Human–AI Collaboration in Academic Writing: Indonesian EFL Students’ Perspectives on AI-Assisted Writing** *Jo-ELT (Journal of English Language Teaching) Fakultas Pendidikan Bahasa & Seni Prodi Pendidikan Bahasa Inggris IKIP* [[paper](https://doi.org/10.33394/jo-elt.v13i1.19807)]
- [2026] **Critical AI Literacy in Foreign Language Writing Instruction in the Age of Generative AI: Theoretical Framework and Pedagogical Pathways** *Higher education and practice.* [[paper](https://doi.org/10.62381/h261604)]
- [2026] **CANote: Empowering Fact-checking Note Writing Through Scaffolded and Provenance-based Human-AI Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.07101)]
- [2026] **Algorithmic Visibility: How Concepts, Names and Theories Become Findable in the Age of AI - The Semantic Field of Jean-Pol Martin as a Case of Digital Recognizability** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20809217)]
- [2026] **AI-Native Knowledge Platforms for Human-Machine Docs** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20778350)]
- [2026] **Symbiotic Diplomacy A Practitioner-Generated Framework for Human-AI** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20315444)]
- [2026] **AgentClick: A Skill-Based Human-in-the-Loop Review Layer for Terminal AI Agents** [[paper](https://doi.org/10.1145/3786335.3813232)]
- [2026] **AI-assisted MCQ creation increases item-writing flaws through automation bias: evaluation of a workflow of multiple AI agents with teachers** *Frontiers in Computer Science* [[paper](https://doi.org/10.3389/fcomp.2026.1831250)]
- [2026] **The Collaboration Gap in Human-AI Work** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.18096)]
- [2026] **Integration of Artificial Intelligence (AI) in Indonesian Language Learning to Improve Elementary School Students' Narrative Writing Skills** *Journal of Innovation and Research in Primary Education* [[paper](https://doi.org/10.56916/jirpe.v5i2.3610)]
- [2026] **From Wandering to Collaboration: Discourse Patterns in Middle School Generative AI Use** [[paper](https://doi.org/10.1145/3785022.3785094)]
- [2026] **Digital or Tangible? Card-Based Story Writing Interaction Designs with AI: A Comparative Study of GUI and TUI** *International Journal of Human-Computer Interaction* [[paper](https://doi.org/10.1080/10447318.2026.2658245)]
- [2026] **f.01 THE FRUITING BODY DIFFUSION PLUME: Giant Ants, Floating Chains, and the Decompression of Waste** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19155610)]
- [2026] **The SymbioMind Attribution Protocol: A Proposed Standard for Human-AI Collaborative Intellectual Production** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19028101)]
- [2026] **Generative AI-Driven Feedback in Flipped Writing Workshops: Transforming Business Education Through Improved Writing, Communication, and Self-Regulation** *Journal of Educational Computing Research* [[paper](https://doi.org/10.1177/07356331261431156)]
- [2026] **Evaluating generative artificial intelligence’s role in enhancing feedback for digital multimodal compositions: a comparative study** *Computer Assisted Language Learning* [[paper](https://doi.org/10.1080/09588221.2026.2640476)]
- [2026] **Diverse AI personas can mitigate the homogenization effect in human-AI collaborative ideation** *Computers in Human Behavior Artificial Humans* [[paper](https://arxiv.org/abs/2504.13868)]
- [2026] **ChatGPT in Knowledge-Intensive Work** *International Journal of Technology Diffusion* [[paper](https://doi.org/10.4018/ijtd.404029)]
- [2026] **Beyond the hype: a psychological perspective on AI chatbots** *Frontiers in Psychology* [[paper](https://doi.org/10.3389/fpsyg.2026.1766427)]
- [2026] **Meta-Human Leadership Regeneration: Reimagining Authority in a Hybrid Human–AI Civilization** *OSF eBooks* [[paper](https://osf.io/sp9zb)]
- [2026] **Jokeasy: Exploring Human-AI Collaboration in Thematic Joke Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.09496)]
- [2026] **A discourse analysis of cohesive devices in human and AI-produced personal statements** *English Learning Innovation* [[paper](https://doi.org/10.22219/englie.v7i1.41321)]
- [2026] **The Theory of Adopted Will and Telic Recursion: A Fusion of CTMU and Astralier Thought via Recursive Human-AI Co-Creation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18269294)]
- [2026] **The Role of Shared Mental Models in Driving Knowledge Complementarity: Enhancing Human–AI Team Effectiveness** *International Journal of Human-Computer Interaction* [[paper](https://doi.org/10.1080/10447318.2025.2598670)]
- [2026] **The Collaboration Gap in Human–AI Work** *European Society for Socially Embedded Technologies (EUSSETDL)* [[paper](https://doi.org/10.48340/ecscw2026_143)]
- [2026] **Responsible Vibe Coding: Architecture, Opportunities, and Research Agenda** *Journal of Computer Information Systems* [[paper](https://doi.org/10.1080/08874417.2026.2621186)]
- [2026] **Does AI Enhance or Replace Human Productivity? Evidence from Service and Manufacturing Sectors** *International Journal of Multidisciplinary Research and Growth Evaluation* [[paper](https://doi.org/10.54660/.ijmrge.2026.7.3.829-834)]

##### 2025

- [2025] **Recommendations for the integration of generative artificial intelligence in support of engineering education research workflows** *Journal of Engineering Education* [[paper](https://doi.org/10.1002/jee.70043)]
- [2025] **KathDB: Explainable Multimodal Database Management System with Human-AI Collaboration** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.11067)]
- [2025] **Human–AI Co-Creation in Melody Writing: A MIDI-Native Pilot on Flow, Authorship, and Control** [[paper](https://doi.org/10.33767/osf.io/zwtgp_v1)]
- [2025] **AI-Powered Personalization in ESP: Enhancing Learner Autonomy and Engagement in English for Professional Contexts** *International Journal of Research and Innovation in Social Science* [[paper](https://doi.org/10.47772/ijriss.2025.91100178)]
- [2025] **A Systematic Review of AI-Powered Language Teaching Trends, Innovations, and Challenges** *Ascarya Journal of Islamic Science Culture and Social Studies* [[paper](https://doi.org/10.53754/rth2mc61)]
- [2025] **A Study on the Application of AI-Assisted Grading Systems in Chinese Writing Instruction** [[paper](https://doi.org/10.1145/3799457.3799484)]
- [2025] **When AI Joined the Writing Class::Translingual Practice of Korean Language Learners in an Australian University** *UWA Profiles and Research Repository (UWA)* [[paper](https://research-repository.uwa.edu.au/en/publications/e17cbae5-0a19-43bb-8c17-740c6da8bd07)]
- [2025] **The Entangled Agency Framework: Modeling Human–Machine Collaboration in the Writing Classroom** *Knowledge Commons (Lakehead University)* [[paper](https://doi.org/10.17613/rcwj9-d4y71)]
- [2025] **RRC-AI Complete Framework: 10 Papers on Gen1-Gen4 Human-AI Integration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17579938)]
- [2025] **OmniScientist: Toward a Co-evolving Ecosystem of Human and AI Scientists** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2511.16931)]
- [2025] **Bridging the gap: exposing the hidden challenges towards adoption of artificial intelligence in surgery** *British journal of surgery* [[paper](https://doi.org/10.1093/bjs/znaf217)]
- [2025] **The One Health approach: reinventing our past knowledge to provide a sustainable future** *Animal Frontiers* [[paper](https://doi.org/10.1093/af/vfaf015)]
- [2025] **Introducing AI & Innovation** *AI & Innovation* [[paper](https://doi.org/10.1002/aiv2.70000)]
- [2025] **How Do AI Agents Do Human Work? Comparing AI and Human Workflows Across Diverse Occupations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.22780)]
- [2025] **Examining Human-AI Collaboration for Co-Writing Constructive Comments Online** *Proceedings of the ACM on Human-Computer Interaction* [[paper](https://doi.org/10.1145/3757591)]
- [2025] **Attitudes and perceptions of Generative Artificial Intelligence chatbots in the peer review of Traditional, Complementary, and Integrative Medicine research: A protocol for a large-scale, international cross-sectional survey** *International Journal of Ayurveda Research* [[paper](https://doi.org/10.4103/ijar.ijar_293_25)]
- [2025] **A Survey of AI Scientists** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.23045)]
- [2025] **ZaQQ: A New Arabic Dataset for Automatic Essay Scoring via a Novel Human–AI Collaborative Framework** *Data* [[paper](https://doi.org/10.3390/data10090148)]
- [2025] **Risky or rigorous? Developing trustworthiness criteria for AI ‐supported qualitative data analysis** *Anatomical Sciences Education* [[paper](https://doi.org/10.1002/ase.70125)]
- [2025] **Charting a new vision for life sciences, embracing the grand mission of Healthy China-Jinggangshan Declaration** *One Health Bulletin* [[paper](https://doi.org/10.4103/ohbl.ohbl_67_25)]
- [2025] **AI Agents with Human-Like Collaborative Tools: Adaptive Strategies for Enhanced Problem-Solving** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.13547)]
- [2025] **Opportunities and Challenges in Using Artificial Intelligence in Guideline Development and Implementation** *Clinical and Public Health Guidelines* [[paper](https://doi.org/10.1002/gin2.70029)]
- [2025] **A Feasibility Study on AI-Assisted Chinese Writing Instruction** *Journal of computer technology and electronic research.* [[paper](https://doi.org/10.70767/jcter.v2i3.560)]
- [2025] **Ethical limits and suggestions for improving the use of AI in scientific research, academic publishing, and the peer review process, based on deontological and consequentialist viewpoints** *Discover Education* [[paper](https://doi.org/10.1007/s44217-025-00696-z)]
- [2025] **AI and Technology in Geriatrics: A New Chapter in JAGS** *Journal of the American Geriatrics Society* [[paper](https://doi.org/10.1111/jgs.70007)]
- [2025] **Rethinking Authorship in the Age of AI: Reflections on the AI-Integrated Writing Framework (AWAI)** *Journal of Educational Technology and Innovation* [[paper](https://doi.org/10.61414/h2a5bt21)]
- [2025] **Editorial: Continuing engineering education for a sustainable future** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1629507)]
- [2025] **Current Landscape and Development Trends of Humanoid Robots** *SmartBot* [[paper](https://doi.org/10.1002/smb2.12020)]
- [2025] **Application of Support Vector Machine in Enhancing AI-Driven Critical Writing Instruction** [[paper](https://doi.org/10.1145/3764206.3764339)]
- [2025] **A Philosophical Inquiry Into Utilizing ChatGPT Through an I-Thou Framework** *Action Criticism and Theory for Music Education* [[paper](https://doi.org/10.22176/act24.3.109)]
- [2025] **Biodiversity2Drugs—Renaissance of exploring nature‐derived peptides for GPCR ligand discovery** *British Journal of Pharmacology* [[paper](https://doi.org/10.1111/bph.70072)]
- [2025] **Using a Hybrid of AI and Template-Based Method in Automatic Item Generation to Create Multiple-Choice Questions in Medical Education: Hybrid AIG** *JMIR Formative Research* [[paper](https://doi.org/10.2196/65726)]
- [2025] **Generative Artificial Intelligence in Writing** [[paper](https://doi.org/10.4324/9781003426936-12)]
- [2025] **Envisioning the Future of AI-Assisted EFL Teaching and Learning: Conceptual Representations of Prospective Teachers** *SAGE Open* [[paper](https://doi.org/10.1177/21582440251341590)]
- [2025] **AI Rivalry as a Craft: How Resisting and Embracing Generative AI Are Reshaping the Writing Profession** [[paper](https://arxiv.org/abs/2503.09901)]
- [2025] **Sisters, not twins: exploring artistic control and anthropomorphism through composing with a bespoke generative AI** *AI & Society* [[paper](https://doi.org/10.1007/s00146-025-02291-0)]
- [2025] **Discussion on the Participation and Trends of AI in Novel Creation** *Journal of Higher Education Research* [[paper](https://doi.org/10.32629/jher.v6i1.3629)]
- [2025] **Letter to the Editor: Comparing letters written by humans and ChatGPT : A preliminary study** *International Journal of Gynecology & Obstetrics* [[paper](https://doi.org/10.1002/ijgo.70035)]
- [2025] **Artificial intelligence in healthcare: medical technology or technology medical?** *Anaesthesia* [[paper](https://doi.org/10.1111/anae.16565)]
- [2025] **Rhythm OS: A Language Operating System for Human–AI Collaboration (Structure × Rhythm × Path)** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5399459)]
- [2025] **Between Prompt and Page: Writing, Reflection, and The Rise of A.I. Collaboration** *DigitalCommons - Kennesaw State University (Kennesaw State University)* [[paper](https://digitalcommons.kennesaw.edu/mastersprojects/59)]

##### 2024

- [2024] **iMeta Conference 2024: Building an innovative scientific research ecosystem for microbiome and One Health** *iMeta* [[paper](https://doi.org/10.1002/imt2.251)]
- [2024] **Claiming the research expertise on human–GenAI interaction for sociolinguistics** *Journal of Sociolinguistics* [[paper](https://doi.org/10.1111/josl.12683)]
- [2024] **Ethical and effortful: workshopping human and generative AI academic writing collaborations** *Journal of Learning Development in Higher Education* [[paper](https://dx.doi.org/10.47408/jldhe.vi32.1475)]
- [2024] **Enhancing legal writing skills: The impact of formative feedback in a hybrid intelligence learning environment** *British Journal of Educational Technology* [[paper](https://doi.org/10.1111/bjet.13529)]
- [2024] **Designing Human-AI Collaboration to Support Learning in Counterspeech Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.03032)]
- [2024] **Artificial Intelligence in Biomedical Research and Publications: It is not about Good or Evil but about its Ethical Use** *Indian Journal of Community Medicine* [[paper](https://doi.org/10.4103/ijcm.ijcm_560_24)]
- [2024] **A SWOT analysis of generative AI in applied linguistics: Leveraging strengths, addressing weaknesses, seizing opportunities, and mitigating threats** *F1000Research* [[paper](https://doi.org/10.12688/f1000research.155378.1)]
- [2024] **Utilizing artificial intelligence in nuclear medicine: Application and challenges** *Journal of Advanced Nursing* [[paper](https://doi.org/10.1111/jan.16402)]
- [2024] **A peep into the future: artificial intelligence for on-farm poultry welfare monitoring** *Animal Frontiers* [[paper](https://doi.org/10.1093/af/vfae031)]
- [2024] **Conversational and generative artificial intelligence and human–chatbot interaction in education and research** *International Transactions in Operational Research* [[paper](https://doi.org/10.1111/itor.13522)]
- [2024] **An investigation into the scientific landscape of the conversational and generative artificial intelligence, and human-chatbot interaction in education and research** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.12004)]
- [2024] **Language education in a brave new world: A dialectical imagination** *Modern Language Journal* [[paper](https://doi.org/10.1111/modl.12930)]
- [2024] **Comparing Student and Writing Instructor Perceptions of Academic Dishonesty When Collaborators Are Artificial Intelligence or Human** *Journal of Business and Technical Communication* [[paper](https://doi.org/10.1177/10506519241239937)]
- [2024] **Academic to AI-cademic: Challenges and Recommendations of Artificial Intelligence in Medical Writing** *Journal of Datta Meghe Institute of Medical Sciences University* [[paper](https://doi.org/10.4103/jdmimsu.jdmimsu_701_23)]
- [2024] **Towards Utilizing Artificial Intelligence in Scientific Writing** *International Journal of Electrical Engineering and Sustainability* [[paper](https://doi.org/10.65998/ijees.v2i1.76)]
- [2024] **Artificial intelligence for surgical services in Australia and New Zealand: opportunities, challenges and recommendations** *The Medical Journal of Australia* [[paper](https://doi.org/10.5694/mja2.52225)]
- [2024] **Advancing Students’ Academic Excellence in Distance Education: Exploring the Potential of Generative AI Integration to Improve Academic Writing Skills** *Open Praxis* [[paper](https://doi.org/10.55982/openpraxis.16.2.649)]

##### 2023

- [2023] **Generative AI and composing: an intergenerational conversation among literacy scholars** *English Teaching Practice & Critique* [[paper](https://doi.org/10.1108/etpc-08-2023-0104)]
- [2023] **Herbarium specimen label transcription reimagined with large language models: Capabilities, productivity, and risks** *American Journal of Botany* [[paper](https://doi.org/10.1002/ajb2.16256)]
- [2023] **Guiding principles and proposed classification system for the responsible adoption of artificial intelligence in scientific writing in medicine** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2023.1283353)]
- [2023] **Editorial: Approaching human intelligence through chemical systems: development of unconventional chemical artificial intelligence** *Frontiers in Chemistry* [[paper](https://doi.org/10.3389/fchem.2023.1332647)]
- [2023] **Machine learning prediction of mild cognitive impairment and its progression to Alzheimer's disease** *Health Science Reports* [[paper](https://doi.org/10.1002/hsr2.1438)]

[⬆ Back to top](#paper-list)

#### Human-in-the-Loop

##### 2026

- [2026] **Human-AI collaborative assessment in central Asian EFL classrooms: An action research study** *Social Sciences & Humanities Open* [[paper](https://doi.org/10.1016/j.ssaho.2026.103280)]

##### 2025

- [2025] **Continual Human-in-the-Loop Optimization** [[paper](https://arxiv.org/abs/2503.05405)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **The AI Mirror Studio** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-2600-3840-6.ch006)]
- [2026] **HUMAN–AI COLLABORATION IN CREATIVE CONTENT GENERATION** *International Journal of Computer Information Systems and Industrial Management Applications* [[paper](https://doi.org/10.70917/ijcisim-2026-4347)]
- [2026] **WrAFT: a Modularized Automated Writing Evaluation System for Argumentative Essays** [[paper](https://arxiv.org/abs/2607.14524)]
- [2026] **Managerial Values and Human-AI Collaboration: A Case Study of Online User Reviews Generation** *Academy of Management Proceedings* [[paper](https://doi.org/10.5465/amproc.2026.14640abstract)]
- [2026] **Embedding, Copilot, or Agent? L2 Teachers Modes of Collaboration With Generative AI in Providing Feedback on Writing Assignments: Rubric Influences, Workload Dynamics, and Barriers to Integration** *European Journal of Education* [[paper](https://doi.org/10.1111/ejed.70795)]
- [2026] **The Signal in the Noise: An Auditable Reliability Layer for Biomedical Text Classification** [[paper](https://arxiv.org/abs/2608.28595)]
- [2026] **Artificial Intelligence in Academic Writing: A Bibliometric Analysis** *European Journal of Contemporary Education* [[paper](https://doi.org/10.13187/ejced.2026.2.202)]
- [2026] **The Impact of Artificial Intelligence on High School Students' Writing Anxiety in Continuation Writing** *Scientific Journal of Technology* [[paper](https://doi.org/10.54691/gefrep13)]
- [2026] **A Systematic Survey on Image Description Techniques for STEM Domains** [[paper](https://arxiv.org/abs/2607.21611)]
- [2026] **NIRVANA: A Comprehensive Dataset for Reproducing How Students Use Generative AI for Essay Writing** [[paper](https://arxiv.org/abs/2604.07344)]
- [2026] **From Guessing to Placeholding: A Cost-Theoretic Framework for Uncertainty-Aware Code Completion** [[paper](https://arxiv.org/abs/2604.01849)]
- [2026] **Effects of AI feedback on students’ English writing performance in higher education: a meta-analysis** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.32137243)]
- [2026] **DraftMarks: Enhancing Transparency in Human-AI Co-Writing Through Interactive Skeuomorphic Process Traces** [[paper](https://arxiv.org/abs/2509.23505)]
- [2026] **Critical Inker: Scaffolding Critical Thinking in AI-Assisted Writing Through Socratic Questioning** [[paper](https://arxiv.org/abs/2604.07167)]
- [2026] **Construction of a "Feedback-Revision" Teaching Model for Senior High School English Continuation Writing Based on Generative AI** *International Journal of Educational Development* [[paper](https://doi.org/10.63313/ijed.9054)]
- [2026] **AnnotateGPT: Designing Human–AI Collaboration in Pen-Based Document Annotation** [[paper](https://doi.org/10.1145/3772318.3790867)]
- [2026] **Trusting AI to detect AI? A systematic evaluation of the reliability and robustness of current AIGC detection tools for student academic work** *Computers & Education* [[paper](https://doi.org/10.1016/j.compedu.2026.105616)]
- [2026] **The Last Mile of Writing: Style Growth in the Age of AI / 写作的Last Mile** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19307428)]
- [2026] **Evaluating GPT-generated feedback for beginning-level Spanish writing: An exploratory study** *ReCALL* [[paper](https://doi.org/10.1017/s0958344026100469)]
- [2026] **Beyond Ray-Casting: Evaluating Controller, Free-Hand, and Virtual-Touch Modalities for Immersive Text Entry** [[paper](https://arxiv.org/abs/2603.18435)]
- [2026] **Human-AI Collaboration for Qualitative Analysis in Participatory Design: Refining the Writing Analytics Tool** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://jedm.educationaldatamining.org/index.php/JEDM/article/view/1023)]
- [2026] **From Crafting Text to Crafting Thought: Grounding AI Writing Support to Writing Center Pedagogy** [[paper](https://arxiv.org/abs/2602.04047)]
- [2026] **The Developmental Bypass: How AI Assistance Undermines Human Growth** *Proceedings of the ... Annual Hawaii International Conference on System Sciences/Proceedings of the Annual Hawaii International Conference on System Sciences* [[paper](https://doi.org/10.24251/hicss.2026.026)]
- [2026] **Secure Text Entry using a Virtual Radial Keyboard with Dynamically Resized Keys and Non-Intrusive Randomization** [[paper](https://arxiv.org/abs/2601.05516)]
- [2026] **Impact of Artificial Intelligence on the Book Industry: A Path Toward the Knowledge Economy** *Knowledge Economy and Lifelong Learning* [[paper](https://doi.org/10.61093/kell.2(1).67-98.2026)]
- [2026] **Exposía: Teaching and Assessment of Academic Writing Skills for Research Project Proposals and Peer Feedback** [[paper](https://arxiv.org/abs/2601.06536)]
- [2026] **EduResearchBench: A Hierarchical Atomic Task Decomposition Benchmark for Full-Lifecycle Educational Research** [[paper](https://arxiv.org/abs/2602.15034)]
- [2026] **Can a Unimodal Language Agent Provide Preferences to Tune a Multimodal Vision-Language Model?** [[paper](https://arxiv.org/abs/2601.06424)]
- [2026] **Beyond Automation: Pedagogical Strategies for Meaningful Human-AI Collaboration in the Classroom** *Journal of Artificial Intelligence and Science Communication* [[paper](https://doi.org/10.54963/jaisc.v2i1.2226)]

##### 2025

- [2025] **Ethical Issues of Using AI in Language Education: A Critical Perspective** *English Teaching* [[paper](https://doi.org/10.15858/engtea.80.5.202512.229)]
- [2025] **Writing With Machines and Peers: Designing for Critical Engagement with Generative AI** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2511.15750)]
- [2025] **A Review on Bridging Brain-Inspired Mechanisms and Large-Scale Pre-trained Models: Toward Adaptive, Efficient, and Interpretable AI** *FinTech and Sustainable Innovation* [[paper](https://doi.org/10.47852/bonviewfsi52026630)]
- [2025] **"Pragmatic Tools or Empowering Friends?" Discovering and Co-Designing Personality-Aligned AI Writing Companions** [[paper](https://arxiv.org/abs/2509.11115)]
- [2025] **Surgeon, Trainee, or GPT ? A Blinded Multicentric Study of AI ‐Augmented Operative Notes** *The Laryngoscope* [[paper](https://doi.org/10.1002/lary.70063)]
- [2025] **Let's Revise Step-by-Step: A Unified Local Search Framework for Code Generation with LLMs** [[paper](https://arxiv.org/abs/2508.07434)]
- [2025] **Exploring the Potential of ChatGPT for Evaluating English Essays in a Criterion‐Based Assessment** *TESOL Quarterly* [[paper](https://doi.org/10.1002/tesq.70011)]
- [2025] **What they provide and how: An intervention study on pre-service teachers' GenAI-assisted writing feedback** *The Internet and Higher Education* [[paper](https://doi.org/10.1016/j.iheduc.2025.101040)]
- [2025] **The Impact of AI on Creativity: Enhancing Human Potential or Challenging Creative Expression** *Artificial Intelligence and Applications* [[paper](https://doi.org/10.47852/bonviewaia52024650)]
- [2025] **VectorEdits: A Dataset and Benchmark for Instruction-Based Editing of Vector Graphics** [[paper](https://arxiv.org/abs/2506.15903)]
- [2025] **Seed-Coder: Let the Code Model Curate Data for Itself** [[paper](https://arxiv.org/abs/2506.03524)]
- [2025] **One SPACE to Rule Them All: Jointly Mitigating Factuality and Faithfulness Hallucinations in LLMs** [[paper](https://arxiv.org/abs/2506.11088)]
- [2025] **OmniGen2: Towards Instruction-Aligned Multimodal Generation** [[paper](https://arxiv.org/abs/2506.18871)] [[code](https://github.com/VectorSpaceLab/OmniGen2)] [[project](https://vectorspacelab.github.io/OmniGen2;)]
- [2025] **To Co- Is Human: Designing Technologies That Center Human Connection, Co-creativity, and Calm in the Era of AI** *DSpace@MIT (Massachusetts Institute of Technology)* [[paper](https://hdl.handle.net/1721.1/164259)]
- [2025] **Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers** [[paper](https://arxiv.org/abs/2505.04718)]
- [2025] **Enhancing Code Generation via Bidirectional Comment-Level Mutual Grounding** [[paper](https://arxiv.org/abs/2505.07768)]
- [2025] **Artificial Intelligence in Content Creation** *International Journal For Multidisciplinary Research* [[paper](https://doi.org/10.36948/ijfmr.2025.v07i03.45053)]
- [2025] **A Survey of Generative Categories and Techniques in Multimodal Generative Models** [[paper](https://arxiv.org/abs/2506.10016)]
- [2025] **Examining Technology Perspectives of Older Adults with Mild Cognitive Impairment: A Scoping Review** [[paper](https://arxiv.org/abs/2504.13901)]
- [2025] **Divergent LLM Adoption and Heterogeneous Convergence Paths in Research Writing** [[paper](https://arxiv.org/abs/2504.13629)]
- [2025] **Text Entry for XR Trove (TEXT): Collecting and Analyzing Techniques for Text Input in XR** [[paper](https://arxiv.org/abs/2503.11357)]
- [2025] **How Problematic Writer-AI Interactions (Rather than Problematic AI) Hinder Writers' Idea Generation** [[paper](https://arxiv.org/abs/2503.11915)]
- [2025] **FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation** [[paper](https://arxiv.org/abs/2503.06680)]
- [2025] **VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output** [[paper](https://arxiv.org/abs/2502.04103)]
- [2025] **UKTA: Unified Korean Text Analyzer** [[paper](https://arxiv.org/abs/2502.09648)]
- [2025] **LongDPO: Unlock Better Long-form Generation Abilities for LLMs via Critique-augmented Stepwise Information** [[paper](https://arxiv.org/abs/2502.02095)]
- [2025] **Keeping up with the times: The application of innovative techniques in forensic entomology** *Medical and Veterinary Entomology* [[paper](https://doi.org/10.1111/mve.12792)]
- [2025] **ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments** [[paper](https://arxiv.org/abs/2502.19852)] [[project](https://huggingface.co/spaces/ConvCodeWorld/ConvCodeWorld)]
- [2025] **Coach not crutch: Evidence that AI can improve writing skill despite reducing effort** [[paper](https://arxiv.org/abs/2502.02880)]
- [2025] **eRevise+RF: A Writing Evaluation System for Assessing Student Essay Revisions and Providing Formative Feedback** [[paper](https://arxiv.org/abs/2501.00715)]
- [2025] **Vibe Coding: A Paradigm Shift in Human-AI Collaborative Programming** *Vascular and Endovascular Review* [[paper](https://doi.org/10.64149/j.ver.8.18s.160-164)]
- [2025] **Joining forces for online feedback management: policy recommendations for human–AI collaboration** *Data & Policy* [[paper](https://doi.org/10.1017/dap.2025.13)]
- [2025] **GPT API-based chatbots as adaptive and facilitative tutors for L2 English process writing** *Korean Journal of English Language and Linguistics* [[paper](https://doi.org/10.15738/kjell.25..202504.448)]
- [2025] **Challenges in scientific writing: Editor's perspective** *Journal of Ayurveda Case Reports* [[paper](https://doi.org/10.4103/jacr.jacr_47_25)]
- [2025] **Bridging Health Inequity in Rheumatology With Technology** *International Journal of Rheumatic Diseases* [[paper](https://doi.org/10.1111/1756-185x.70086)]

##### 2024

- [2024] **PTCL-SE: How AI Self-evaluation Influences Human-AI Collaborative Story Writing** [[paper](https://doi.org/10.1109/iscid63852.2024.00058)]
- [2024] **Improving Factuality with Explicit Working Memory** [[paper](https://arxiv.org/abs/2412.18069)]
- [2024] **Generative AI as a Collaborative Companion: Enhancing Peer Feedback in EFL Writing Classes** *Education Research and Perspectives* [[paper](https://doi.org/10.70953/erpv51.2412005)]
- [2024] **Disentangling Preference Representation and Text Generation for Efficient Individual Preference Alignment** [[paper](https://arxiv.org/abs/2412.20834)]
- [2024] **Beware of metacognitive laziness: Effects of generative artificial intelligence on learning motivation, processes, and performance** *British Journal of Educational Technology* [[paper](https://arxiv.org/abs/2412.09315)]
- [2024] **AI Usage in Education and Mitigation of Abilities: Collaboration, Communication, Critical Thinking and Creativity among University Students** *Research Journal of Social Sciences & Economics Review (RJSSER)* [[paper](https://doi.org/10.36902/rjsser-vol5-iss4-2024(20-28))]
- [2024] **On the Limits of Language Generation: Trade-Offs Between Hallucination and Mode Collapse** [[paper](https://arxiv.org/abs/2411.09642)]
- [2024] **Chain-of-Programming (CoP) : Empowering Large Language Models for Geospatial Code Generation** [[paper](https://arxiv.org/abs/2411.10753)]
- [2024] **TapType: Ten-finger text entry on everyday surfaces via Bayesian inference** [[paper](https://arxiv.org/abs/2410.06001)]
- [2024] **Examining Input Modalities and Visual Feedback Designs in Mobile Expressive Writing** [[paper](https://arxiv.org/abs/2410.00449)]
- [2024] **Enhancing AI Assisted Writing with One-Shot Implicit Negative Feedback** *EMNLP 2024* [[paper](https://arxiv.org/abs/2410.11009)]
- [2024] **Artificial intelligence for language learning and teaching: A narrative literature study** *Englisia Journal of language education and humanities* [[paper](https://doi.org/10.22373/ej.v12i1.23211)]
- [2024] **Are Large Language Models Good Classifiers? A Study on Edit Intent Classification in Scientific Document Revisions** [[paper](https://arxiv.org/abs/2410.02028)]
- [2024] **RethinkMCTS: Refining Erroneous Thoughts in Monte Carlo Tree Search for Code Generation** [[paper](https://arxiv.org/abs/2409.09584)]
- [2024] **Instruction-Based Molecular Graph Generation with Unified Text-Graph Diffusion Model** [[paper](https://arxiv.org/abs/2408.09896)] [[code](https://github.com/ran1812/UTGDiff)]
- [2024] **Improving Factuality in Large Language Models via Decoding-Time Hallucinatory and Truthful Comparators** [[paper](https://arxiv.org/abs/2408.12325)]
- [2024] **Regularizing Hidden States Enables Learning Generalizable Reward Model for LLMs** [[paper](https://arxiv.org/abs/2406.10216)]
- [2024] **Navigating Scientific Peer Review with ChatGPT: Ally or Adversary?** *Advanced Pharmaceutical Bulletin* [[paper](https://doi.org/10.34172/apb.2024.053)]
- [2024] **Measuring memorization in RLHF for code completion** [[paper](https://arxiv.org/abs/2406.11715)]
- [2024] **ReflectionCoder: Learning from Reflection Sequence for Enhanced One-off Code Generation** [[paper](https://arxiv.org/abs/2405.17057)] [[code](https://github.com/SenseLLM/ReflectionCoder)]
- [2024] **Exploring the potential of LLM-based customized test item generators: Focusing on Poe AI as a chatbot builder** [[paper](https://doi.org/10.18649/jkees.2024.23.2.181)]
- [2024] **From Model-centered to Human-Centered: Revision Distance as a Metric for Text Evaluation in LLMs-based Applications** [[paper](https://arxiv.org/abs/2404.07108)]
- [2024] **Filling the Gap: A Comprehensive Freshwater Network to Map Microplastics across Ecological Gradients in Argentina** *Limnology and Oceanography Bulletin* [[paper](https://doi.org/10.1002/lob.10641)]
- [2024] **AI-Assisted Writing in Education: Ecosystem Risks and Mitigations** [[paper](https://arxiv.org/abs/2404.10281)]
- [2024] **Typist Experiment: an Investigation of Human-to-Human Dictation via Role-play to Inform Voice-based Text Authoring** [[paper](https://arxiv.org/abs/2403.05785)]
- [2024] **Reinforcement Learning with Token-level Feedback for Controllable Text Generation** [[paper](https://arxiv.org/abs/2403.11558)] [[code](https://github.com/WindyLee0822/CTG)]
- [2024] **MATEval: A Multi-Agent Discussion Framework for Advancing Open-Ended Text Evaluation** [[paper](https://arxiv.org/abs/2403.19305)]
- [2024] **Is Factuality Enhancement a Free Lunch For LLMs? Better Factuality Can Lead to Worse Context-Faithfulness** [[paper](https://arxiv.org/abs/2404.00216)]
- [2024] **Detecting AI-Generated Sentences in Human-AI Collaborative Hybrid Texts: Challenges, Strategies, and Insights** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.03506)]
- [2024] **CYCLE: Learning to Self-Refine the Code Generation** [[paper](https://arxiv.org/abs/2403.18746)]
- [2024] **AI as a Collaborative Partner** *Advances in educational technologies and instructional design book series* [[paper](https://doi.org/10.4018/979-8-3693-1054-0.ch006)]
- [2024] **Exploring Precision and Recall to assess the quality and diversity of LLMs** [[paper](https://arxiv.org/abs/2402.10693)]
- [2024] **Exploring Data-Efficient Adaptation of Large Language Models for Code Generation** [[paper](https://arxiv.org/abs/2403.00046)]
- [2024] **Learning to Trust Your Feelings: Leveraging Self-awareness in LLMs for Hallucination Mitigation** [[paper](https://arxiv.org/abs/2401.15449)]
- [2024] **From Understanding to Utilization: A Survey on Explainability for Large Language Models** [[paper](https://arxiv.org/abs/2401.12874)]
- [2024] **From GeoSentinel data to epidemiological insights: a multidisciplinary effort towards artificial intelligence-supported detection of infectious disease outbreaks** *Journal of Travel Medicine* [[paper](https://doi.org/10.1093/jtm/taae013)]
- [2024] **Fine-grained Hallucination Detection and Editing for Language Models** *COLM 2024* [[paper](https://arxiv.org/abs/2401.06855)]
- [2024] **ChatGPT-Based Learning And Reading Assistant (C-LARA): Second Report** *HAL (Le Centre pour la Communication Scientifique Directe)* [[paper](https://hal.science/hal-04516027)]
- [2024] **ChatGPT and Impacting Medical Literature** *Arthroscopy The Journal of Arthroscopic and Related Surgery* [[paper](https://doi.org/10.1016/j.arthro.2023.08.069)]
- [2024] **Artificial Intelligence for the Obstetric Anesthesiologist—Still a Long Wait!** *Journal of Obstetric Anaesthesia and Critical Care* [[paper](https://doi.org/10.4103/joacc.joacc_8_24)]
- [2024] **Adapting peer review for the future: Digital disruptions and trust in peer review** *Learned Publishing* [[paper](https://doi.org/10.1002/leap.1594)]

##### 2023

- [2023] **IMPROVING CLARITY AND ACCESSIBILITY IN PUBLIC PROCUREMENT DOCUMENTS: AN AI–POWERED APPROACH TO PLAIN WRITING COMPLIANCE** *Calhoun: The Naval Postgraduate School Institutional Archive (Naval Postgraduate School)* [[paper](https://hdl.handle.net/10945/72543)]
- [2023] **Exploring the Efficacy of ChatGPT in Language Teaching** *AsiaCALL Online Journal* [[paper](https://doi.org/10.54855/acoj.2314210)]
- [2023] **Response to: Investigating the impact of innovative AI chatbot on post‐pandemic medical education and clinical assistance: a comprehensive analysis** *ANZ Journal of Surgery* [[paper](https://dx.doi.org/10.1111/ans.18720)]

[⬆ Back to top](#paper-list)

#### Co-creative Writing

##### 2026

- [2026] **A Systematic Review of Artistic Human-AI Co-Creative Systems and Interaction Design** *ACM Transactions on Interactive Intelligent Systems* [[paper](https://doi.org/10.1145/3834857)]
- [2026] **Collaborative and Co-creative Communication with AI** *Human-computer interaction series* [[paper](https://doi.org/10.1007/978-3-032-21689-2_6)]

##### 2025

- [2025] **Creative or Uncreative Partner: Comparing Humans and AI in Collaborative Creative Tasks** [[paper](https://doi.org/10.31234/osf.io/ey7u4_v1)]
- [2025] **Reflective AI-Partnerships: How Middle Schoolers Balance Creativity and AI Collaboration** *Computer-supported collaborative learning/The Computer-Supported Collaborative Learning Conference* [[paper](https://doi.org/10.22318/cscl2025.485037)]
- [2025] **A Systematic Review of Human-AI Co-Creativity** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.21333)]
- [2025] **Hybrid intelligence: Human– AI coevolution and learning** *British Journal of Educational Technology* [[paper](https://doi.org/10.1111/bjet.13560)]

##### 2024

- [2024] **The AI revolution in context** [[paper](https://dx.doi.org/10.4324/9781032665276-2)]
- [2024] **Grand challenges for ChatGPT usage in education: psychological theories, perspectives and opportunities** *DergiPark (Istanbul University)* [[paper](https://dergipark.org.tr/tr/pub/press/issue/85293/1451343)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **Personalized Intelligent Chatbot Based on AI-Generated Content Assists Memoir Writing for Older Adults With Cognitive Impairment: Mixed Methods Study** *JMIR Human Factors* [[paper](https://doi.org/10.2196/83428)]
- [2026] **The role of perceived anthropomorphism and anthropomorphic design elements in willingness to delegate writing tasks to AI: findings from a large-scale survey and a randomised controlled experiment** *Journal of Psychology and AI* [[paper](https://doi.org/10.1080/29974100.2026.2652861)]
- [2026] **Contextual justice: citizens’ dialogues on AI judges in Japan** *AI and Ethics* [[paper](https://doi.org/10.1007/s43681-026-01110-6)]
- [2026] **Creative Process Transformation through Generative AI Models** *GEORGIAN SCIENTISTS* [[paper](https://doi.org/10.52340/gs.2026.08.01.16)]
- [2026] **Psychological mechanisms of self-confidence in human-ai interaction: from social comparison to agency** [[paper](https://doi.org/10.32657/10356/219111)]
- [2026] **Holding the Thread: AI-ALI and the Need for Personal Continuity in Long Human-AI Collaboration** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6891158)]

##### 2025

- [2025] **AI and Transformative Learning in Higher Education: A Systematic Literature Review and Bibliometric Insights** *Journal of Teaching and Learning* [[paper](https://doi.org/10.22329/jtl.v19i4.10096)]
- [2025] **Exploring Master’s Students' Paraphrasing and Synthesis Techniques: A Comparative Analysis with AI-Based Text Generation** *Romblon State University Research Journal* [[paper](https://doi.org/10.58780/rsurj.v7i1.229)]
- [2025] **AI ‐Based Objective Severity Assessment of Atopic Dermatitis Using Patient Photos in a Real‐World Setting: A Digital Biomarker Approach** *Allergy* [[paper](https://doi.org/10.1111/all.16586)]

##### 2024

- [2024] **Artificial intelligence applications spreading into editorship: A critical conundrum for editors and publishers** *Journal of Clinical Ultrasound* [[paper](https://dx.doi.org/10.1002/jcu.23816)]
- [2024] **AI and Human Writing: Collaboration or Appropriation?** [[paper](https://doi.org/10.1515/9783110792270-008)]
- [2024] **DiaryMate: Understanding User Perceptions and Experience in Human-AI Collaboration for Personal Journaling** [[paper](https://doi.org/10.1145/3613904.3642693)]
- [2024] **Emotions in Human-Human and Human-AI Collaboration: Insights for Collaborative Design** *Digital Commons - USU (Utah State University)* [[paper](https://digitalcommons.usu.edu/researchweek/ResearchWeek2024/all2024/79)]
- [2024] **Integrating Artificial Intelligence with Human Psychology** *International Journal of Advanced Research in Science Communication and Technology* [[paper](https://doi.org/10.48175/ijarsct-15250)]
- [2024] **Embracing the use of artificial intelligence in scientific publishing** *International Journal for Quality in Health Care* [[paper](https://doi.org/10.1093/intqhc/mzae071)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **Generative AI in Scientific Writing : A Conceptual Analysis of Hallucinated References and Implications for Research Data Integrity** *Media Informatika* [[paper](https://doi.org/10.37595/mediainfo.v25i2.507)]
- [2026] **From Ghostwriter to Cognitive Partner: A Translanguaging Lens on Human-AI Interaction and the ACTS Model for EFL Academic Writing** *Journal of Education and Training Studies* [[paper](https://doi.org/10.11114/jets.v14i4.9076)]
- [2026] **What do you mean by human-AI collaboration: Prerequisite functions and the affordances needed to achieve it** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.15509)]
- [2026] **From Human-Centered Design to Human-AI Collaboration: Why the Future of HCI Still Starts With People** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.07482)]

##### 2025

- [2025] **Leveraging Artificial Intelligence in Scholarly Publishing** *Journal of Applied Social Sciences and Humanities* [[paper](https://doi.org/10.71426/jassh.v1.i1.pp1-8)]

[⬆ Back to top](#paper-list)

#### NLP Metrics

##### 2025

- [2025] **Swiftcommit: Integration of Commit Summary Generator Into Version Control Workflow** [[paper](https://doi.org/10.1109/ecai65401.2025.11095586)]
- [2025] **Measuring Human Involvement in AI-Generated Text: A Case Study on Academic Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.03501)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2026

- [2026] **The Human--AI Collaboration Frontier in Scientific Research** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21159521)]
- [2026] **Integrating AI in Teaching** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/407442)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **AI acceptance & Academic writing** *Harvard Dataverse* [[paper](https://doi.org/10.7910/dvn/pqqwtr)]

##### 2025

- [2025] **Human-AI Collaboration Increases Efficiency in Regulatory Writing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.09738)]
- [2025] **Empowering Human-AI Collaboration: Enterprise Technology Platforms and Human Expertise Synergy in Healthcare, Finance, and Scientific Research** *Journal of Computer Science and Technology Studies* [[paper](https://doi.org/10.32996/jcsts.2025.7.7.57)]

##### 2024

- [2024] **Training an AI-based Writing Assistant for Spanish Learners: The Usefulness of Chatbots and the Indispensability of Human-assisted Intelligence** *Lexikos* [[paper](https://doi.org/10.5788/34-1-1862)]

##### 2023

- [2023] **Consensus, dissensus and synergy between clinicians and specialist foundation models in radiology report generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.18260)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2026

- [2026] **Research on the Dilemmas and Solutions of College Students' AI-Assisted Writing Competence** *Journal of Higher Education Research* [[paper](https://doi.org/10.32629/jher.v7i3.5309)]
- [2026] **PETMALU-AI: A Reporting Checklist for Transparent and Accountable Generative AI-Assisted Research Writing** *Education Sciences* [[paper](https://doi.org/10.3390/educsci16071127)]
- [2026] **Generative AI As a Critical Writing Partner: A Human–AI Collaborative Framework for Academic Writing and Critical Thinking in English Language Education** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21947928)]
- [2026] **From affordance offers to uptake depth: examining hybrid intelligence in human–AI collaborative academic writing** *Behaviour and Information Technology* [[paper](https://doi.org/10.1080/0144929x.2026.2706668)]
- [2026] **USING ARTIFICIAL INTELLIGENCE IN DEVELOPING STUDENTS' ACADEMIC WRITING COMPETENCE** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19573251)]
- [2026] **Human–AI Collaboration in Research** [[paper](https://doi.org/10.1201/9781003786405)]
- [2026] **AI in Academic Writing** *The Encyclopedia of Applied Linguistics* [[paper](https://doi.org/10.1002/9781405198431.wbeal208345)]
- [2026] **Modeling human-AI collaboration in EFL academic writing: Hidden Markov model and process mining approach** *Journal of Second Language Writing* [[paper](https://doi.org/10.1016/j.jslw.2026.101296)]
- [2026] **Impacts of AI-enhanced task-based learning on EFL postgraduates’ higher order thinking skills and English academic writing self-efficacy** *Journal of English for Academic Purposes* [[paper](https://doi.org/10.1016/j.jeap.2026.101652)]
- [2026] **Human-AI collaboration in academic writing: Exploring university students’ agency through a sociocultural lens** *Ampersand* [[paper](https://doi.org/10.1016/j.amper.2026.100256)]
- [2026] **Evaluating AI Adoption in Academic Research** *DESIDOC Journal of Library & Information Technology* [[paper](https://doi.org/10.14429/djlit.20800)]

##### 2025

- [2025] **The Ethical Considerations of Using Gen AI and AI Tools in Academic Writing in Higher Education: A Systematic Review** *Kalika Journal of Multidisciplinary Research* [[paper](https://doi.org/10.3126/kjmr.v3i3.87215)]
- [2025] **Dialogic triad** *Journal of English for Research Publication Purposes* [[paper](https://doi.org/10.1075/jerpp.00038.cao)]
- [2025] **AI Assistance and Academic Collaboration: The Rise of a New Era** [[paper](https://doi.org/10.38124/ijisrt/25nov1073)]
- [2025] **Examining Graduate Students' Experiences in Using Generative AI for Academic Writing: Insights from Cambodian Higher Education** [[paper](https://doi.org/10.1201/9781003567257-10)]
- [2025] **The use of generative AI tools in academic writing: a systematic review of research trends and thematic insights** *AI and Ethics* [[paper](https://doi.org/10.1007/s43681-025-00827-0)]
- [2025] **A systematic review of the impact of generative AI on postgraduate research: opportunities, challenges, and ethical implications** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-025-00495-3)]
- [2025] **The Symbiotic Scholar: A Framework for Integrating Artificial Intelligence in Academic Writing While Upholding Ethical Integrity** *IARS International Research Journal* [[paper](https://doi.org/10.51611/iars.irj.v15i2.2025.266)]
- [2025] **Human-AI Collaboration in Academic Writing: towards a Synergy Model and A Case to Include AI as a Co-Author** [[paper](https://doi.org/10.31234/osf.io/snq4e_v1)]
- [2025] **Harnessing GPT for Enhanced Academic Writing: Evidence from a Field Experiment with Early-Career Researchers in the Social Sciences** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-6937665/v1)]
- [2025] **El impacto de la inteligencia artificial en la producción científica** *Multidisciplinary Latin American Journal (MLAJ)* [[paper](https://doi.org/10.62131/mlaj-v3-n1-031)]
- [2025] **Large‐scale and long‐term wildlife research and monitoring using camera traps: a continental synthesis** *Biological reviews/Biological reviews of the Cambridge Philosophical Society* [[paper](https://doi.org/10.1111/brv.13152)]
- [2025] **Human-AI Collaboration in Academic Writing: A Narrative Review and the Scholarly HI-AI Loop Framework for Ethical Knowledge Production** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5394918)]
- [2025] **Academic Integrity and Ethics in Higher Education** *Advances in library and information science (ALIS) book series* [[paper](https://doi.org/10.4018/979-8-3693-5807-8.ch009)]

##### 2024

- [2024] **Negotiating Meaning with Machines: AI’s Role in Doctoral Writing Pedagogy** *International Journal of Artificial Intelligence in Education* [[paper](https://doi.org/10.1007/s40593-024-00425-x)]
- [2024] **Implications of Leveraging AI in Students’ Academic Writing: A Review Analysis** *Malaysian Journal of Social Sciences and Humanities (MJSSH)* [[paper](https://doi.org/10.47405/mjssh.v9i8.2954)]
- [2024] **Hybrid Intelligence in Academic Writing: Examining Self-Regulated Learning Patterns in an AI-Assisted Writing Task** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia240198)]
- [2024] **Human-AI collaboration patterns in AI-assisted academic writing** *Studies in Higher Education* [[paper](https://doi.org/10.1080/03075079.2024.2323593)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Grounds, Frames, and Standing: The Absorbable and Irreducible Classes of Human Intervention in Agentic Work** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21563154)]
- [2026] **eLLMish: The Emerging Common Language of Human-AI Work** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21516513)]
- [2026] **Satisficing vs. Maximizing in Prompt Writing: Trait and Task Effects in Human–AI Interaction** [[paper](https://doi.org/10.1145/3772318.3790693)]
- [2026] **Multimodality, Adaptivity, and Human-AI Collaboration: Innovative Practices and Pathway Exploration in New TOEFL Writing Instruction—Dynamic Scaffolding Design for TOEFL Email Writing Tasks Based on Double Stimulation Theory** *Overseas English Testing Pedagogy and Research* [[paper](https://doi.org/10.12677/oetpr.2026.82006)]

##### 2025

- [2025] **Whodunit? Ownership and User Experience in Co-Creation with Generative AI** *TUbilio (Technical University of Darmstadt)* [[paper](https://tubiblio.ulb.tu-darmstadt.de/view/person/Sharma=3ABhavika=3A=3A.html>)]
- [2025] **When collaborating turns into dishonesty: A data-driven heuristic comparing human and AI collaborators** *Computers & composition/Computers and composition* [[paper](https://doi.org/10.1016/j.compcom.2025.102947)]
- [2025] **Understanding Empathy Together: How AI Explanations Influence Human Emotional Support Learning** *Open Science Framework* [[paper](https://doi.org/10.17605/osf.io/3xkjf)]
- [2025] **Reframing AI Use in Civil Engineering Lab Report Writing: The 4A-4B Approach to Human-AI Collaboration in Education** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5222308)]

##### 2024

- [2024] **Large language model usage guidelines in Korean medical journals: a survey using human-artificial intelligence collaboration** *Journal of Yeungnam Medical Science* [[paper](https://doi.org/10.12701/jyms.2024.00794)]
- [2024] **Three versions of an atopic dermatitis case report written by humans, artificial intelligence, or both: Identification of authorship and preferences** *Journal of Allergy and Clinical Immunology Global* [[paper](https://doi.org/10.1016/j.jacig.2024.100373)]
- [2024] **Generative AI Guidelines in Korean Medical Journals: A Survey Using Human-AI Collaboration** *medRxiv* [[paper](https://doi.org/10.1101/2024.03.08.24303960)]

##### 2023

- [2023] **The Proliferation of AI and Its Impact on the “Workly” Aspects of Writing** *안과밖* [[paper](https://dx.doi.org/10.46645/inoutsesk.55.7)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2026

- [2026] **Facets of Human–AI Collaboration: The Importance of Collaboration Type, Invocation Type, and AI Output Quality** *TUbilio (Technical University of Darmstadt)* [[paper](https://tubiblio.ulb.tu-darmstadt.de/view/person/Diebel=3AChristopher=3A=3A.html>)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2026

- [2026] **Who is the Author? Negotiating Authorial Identity in GenAI-Mediated L2 Writing Among Chinese High School Students** *Digital studies in language and literature* [[paper](https://doi.org/10.1515/dsll-2026-0015)]

##### 2024

- [2024] **Integrating generative AI into digital multimodal composition: A study of multicultural second-language classrooms** *Computers & composition/Computers and composition* [[paper](https://doi.org/10.1016/j.compcom.2024.102895)]

[⬆ Back to top](#paper-list)

### Control & Personalization

#### LLM Evaluation

##### 2026

- [2026] **UniMoFlow: Grounding Instruction-Driven 3D Human Motion Editing in Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.09143)]
- [2026] **Research on AI-Driven Generation Mechanisms and Design Methodologies for Digital Media Art** *Advanced Electromagnetics* [[paper](https://www.aemjournal.org/index.php/AEM/article/view/4190)]
- [2026] **Knowledge-Aware Diffusion Models for Controllable Image Generation With Semantic Layout and Style Decoupling** *International Journal on Semantic Web and Information Systems* [[paper](https://doi.org/10.4018/ijswis.419811)]
- [2026] **CookVoice: Unified Framework for Style Controllable Multi-Modal Human Voice Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.11590)]
- [2026] **Visual Image Generation Based on CLIP Semantic Guidance and Text Inversion** *Iranian Journal of Science and Technology Transactions of Electrical Engineering* [[paper](https://doi.org/10.1007/s40998-026-01178-0)]
- [2026] **Synaptic style weaver: A closed-loop multi-agent neuro-symbolic system for secure and hardware-agnostic academic text humanization** *Applied Soft Computing* [[paper](https://doi.org/10.1016/j.asoc.2026.115903)]
- [2026] **Attention-Enhanced HiGAN+ for Handwritten Text Generation** *IFIP advances in information and communication technology* [[paper](https://doi.org/10.1007/978-3-032-30612-8_15)]
- [2026] **The context of new media art for photography generation based on diffusion models** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-58912-1)]
- [2026] **KV-Control: Parameter-Efficient K/V Injection for Trajectory-Controlled Text-to-Motion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05624)]
- [2026] **How Do Instructions Shape Speech? Cross-Attention Attribution for Style-Captioned Text-to-Speech** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.20532)]
- [2026] **SIC3D: Style Image Conditioned Text-to-3D Gaussian Splatting Generation** *White Rose Research Online (University of Leeds, The University of Sheffield, University of York)* [[paper](https://arxiv.org/abs/2604.08760)]
- [2026] **Prompt Relay: Inference-Time Temporal Control for Multi-Event Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.10030)]
- [2026] **ControlTST: Precision-controllable text-driven image stylization via progressive content-aware guidance diffusion** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2026.133819)]
- [2026] **AIGC-Driven Short Video Generation Based on the Controllable Multimodal Fusion Architecture** *Electronics* [[paper](https://doi.org/10.3390/electronics15091783)]
- [2026] **Visually-Guided Controllable Medical Image Generation via Fine-Grained Semantic Disentanglement** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.10519)]
- [2026] **Research on Intelligent Generation Algorithm of Interface Icon Based on Diffusion Model** *International Scientific Technical and Economic Research* [[paper](https://doi.org/10.71451/istaer2607)]
- [2026] **ParaMETA: Towards Learning Disentangled Paralinguistic Speaking Styles Representations from Speech** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i38.40505)]
- [2026] **Deep learning image generation technology for enhancing the presentation effect of image art based on artificial intelligence** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-45739-z)]
- [2026] **Diff-Aid: Inference-time Adaptive Interaction Denoising for Rectified Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.13585)]
- [2026] **T2I-DiT: An Efficient and Controllable Transformer Diffusion Model for Text-to-Image Generation** [[paper](https://doi.org/10.1109/iscait69154.2026.11477450)]
- [2026] **OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation** *International Journal of Computer Vision* [[paper](https://doi.org/10.1007/s11263-025-02629-7)]
- [2026] **Fast Real-World Face De-Occlusion by Style-Based GAN Prior** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7306280)]
- [2026] **EIU-IC: Enhancing Interaction Understanding in Text-to-Image Generation Models with Interaction Control** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-5702-8_19)]
- [2026] **D$^2$-Diff: Controllable Fashion Image Generation with Disentangled Style and Content** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-22267-1_32)]
- [2026] **Controlling the Text Game: Game Theoretic Interactions Between LLMs for Controllable Text Generation** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-26370-4_13)]
- [2026] **Control strategies for expressive text-to-speech** *ERA* [[paper](https://era.ed.ac.uk/handle/1842/44458)]
- [2026] **Advancing the generation and integration of traditional motifs through AI-based techniques** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-025-00642-w)]
- [2026] **AI for arbitrary skeleton guided text-to-image generation** *DR-NTU (Nanyang Technological University)* [[paper](https://hdl.handle.net/10356/214459)]

##### 2025

- [2025] **SAST: Semantic-Aware stylized Text-to-Image generation** *Journal of Visual Communication and Image Representation* [[paper](https://doi.org/10.1016/j.jvcir.2025.104685)]
- [2025] **Closed-Loop Viability Control via Continuous Throttling From Hard Stop Criteria to Electric-Motor–Style Risk Modulation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18057607)]
- [2025] **Application of deep learning for transformation of Chinese traditional cultural narrative patterns and enhancement of cultural identity empowered by AIGC** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-32302-5)]
- [2025] **WorldGen: From Text to Traversable and Interactive 3D Worlds** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2511.16825)]
- [2025] **Stylized image generation based on multi-attribute decomposition** *Pattern Analysis and Applications* [[paper](https://doi.org/10.1007/s10044-025-01577-9)]
- [2025] **Single-Attribute Controllable Text Generation Based on Continuous Prompt Contrastive Learning** [[paper](https://doi.org/10.1109/dsis67228.2025.11390576)]
- [2025] **Semantic guidance for precise style control in diffusion image generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-28715-x)]
- [2025] **ParaStyleTTS: Toward Efficient and Robust Paralinguistic Style Control for Expressive Text-to-Speech Generation** [[paper](https://arxiv.org/abs/2510.18308)]
- [2025] **InstructAudio: Unified speech and music generation with natural language instruction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2511.18487)]
- [2025] **From Detection to Mitigation: Addressing Gender Bias in Chinese Texts via Efficient Tuning and Voting-Based Rebalancing** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-3352-7_39)]
- [2025] **Controllable Font Style for Visual Text Generation Using Reference Images** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-95-4091-4_20)]
- [2025] **UniGlyph: Unified Segmentation-Conditioned Diffusion for Precise Visual Text Synthesis** [[paper](https://arxiv.org/abs/2507.00992)]
- [2025] **StyleBoost: Controlling style-content fusion with SVD for text-driven** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.131843)]
- [2025] **SPG: Style‐Prompting Guidance for Style‐Specific Content Creation** *Computer Graphics Forum* [[paper](https://doi.org/10.1111/cgf.70251)]
- [2025] **ICE: Intercede Concept Erasure in Text-to-Image Diffusion Models** [[paper](https://doi.org/10.1145/3746027.3754992)]
- [2025] **Fraudulent Publishing in the Mathematical Sciences** *Notices of the American Mathematical Society* [[paper](https://arxiv.org/abs/2509.07257)]
- [2025] **FOCUS: Optimal Control for Multi-Entity World Modeling in Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.02315)]
- [2025] **Dual Orthogonal Guidance for Robust Diffusion-Based Handwritten Text Generation** [[paper](https://doi.org/10.1109/iccvw69036.2025.00725)]
- [2025] **SRC-IT2: Speech Rate-Controllable Mongolian Emotional Speech Synthesis Based on Improved Tacotron2** *Electronics* [[paper](https://doi.org/10.3390/electronics14193835)]
- [2025] **PG-CE: A Progressive Generation Dataset with Constraint Enhancement for Controllable Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.17669)]
- [2025] **InstructVTON: Optimal Auto-Masking and Natural-Language-Guided Interactive Style Control for Inpainting-Based Virtual Try-On** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.20524)]
- [2025] **DiffDesign: Controllable diffusion with meta prior for efficient interior design generation** *PLoS ONE* [[paper](https://doi.org/10.1371/journal.pone.0331240)]
- [2025] **Beyond Memorization: Training-Free Style Mixing for Variability in Handwritten Text Generation Using Writer Embedding Injection in Pretrained Diffusion Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-04627-7_27)]
- [2025] **Audiobook-CC: Controllable Long-context Speech Generation for Multicast Audiobook** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.17516)]
- [2025] **The Name-Free Gap: Policy-Aware Stylistic Control in Music Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.00654)]
- [2025] **MIDI and Text Conditioned Diffusion Model for Style-Controlled Music Generation** [[paper](https://doi.org/10.1109/prai67447.2025.11412815)]
- [2025] **Style-Content progressive aggregation network with stable diffusion** *Applied Intelligence* [[paper](https://doi.org/10.1007/s10489-025-06751-4)]
- [2025] **Integrating global signals with fine-grained consistency for conditional image generation** *Multimedia Systems* [[paper](https://doi.org/10.1007/s00530-025-01892-5)]
- [2025] **DreamArtist: Controllable One-Shot Text-to-Image Generation via Positive-Negative Adapter** *International Journal of Computer Vision* [[paper](https://doi.org/10.1007/s11263-025-02526-z)]
- [2025] **ArtGlyphDiffuser: Text-driven artistic glyph generation via Style-to-CLIP Projection and Multi-Level Controlled diffusion** *Pattern Recognition* [[paper](https://doi.org/10.1016/j.patcog.2025.112172)]
- [2025] **Training-Free Color-Style Disentanglement for Constrained Text-to-Image Synthesis** [[paper](https://doi.org/10.1109/cvprw67362.2025.00620)]
- [2025] **Multi-level Style Control for Chinese Handwriting Generation** *International Journal on Document Analysis and Recognition (IJDAR)* [[paper](https://doi.org/10.1007/s10032-025-00533-x)]
- [2025] **Enhancing image-based virtual try-on with Multi-Controlled Diffusion Models** *Neural Networks* [[paper](https://doi.org/10.1016/j.neunet.2025.107552)]
- [2025] **NAT-CVAE: A Novel Method for Controlled Long Text Generation** [[paper](https://doi.org/10.1109/ainit65432.2025.11035169)]
- [2025] **LLM Gesticulator: leveraging large language models for scalable and controllable co-speech gesture synthesis** [[paper](https://doi.org/10.1117/12.3060395)]
- [2025] **DreamFit: Garment-Centric Human Generation via a Lightweight Anything-Dressing Encoder** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i5.32554)]
- [2025] **Cascaded Diffusion Models for Virtual Try-On: Improving Control and Resolution** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i5.32495)]
- [2025] **Palette of Language Models: A Solver for Controlled Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.11182)]
- [2025] **ODE-based generative modeling: Learning from a single natural image** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.127185)]
- [2025] **RenderBox: Expressive Performance Rendering with Text Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.07711)]
- [2025] **Control-CLIP: Decoupling Category and Style Guidance in CLIP for Specific-Domain Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.11532)]
- [2025] **Text- and Speech-style Control for Lecture Speech Generation Focusing on Disfluency** *APSIPA Transactions on Signal and Information Processing* [[paper](https://doi.org/10.1561/116.20250005)]
- [2025] **Tedi: Discrete Style Modeling Framework for Text Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5200750)]
- [2025] **Stylesteinsvg: Example-Guided Text-to-Svg Diffusion Models Via Vectorized Stein Score Distillation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5384586)]
- [2025] **Research on Controllable Text Generation Method Based on Hamiltonian Systems and Large Language Models** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-96-9994-0_26)]
- [2025] **Object-level Visual Prompts for Compositional Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.01424)]
- [2025] **Improving lexical diversity of domain-specific automatic text generation with out-of-domain training data and style conditioning** *Tampere University Institutional Repository (Tampere University)* [[paper](https://trepo.tuni.fi/handle/10024/231681)]
- [2025] **Generating Deepfakes with Stable Diffusion, ControlNet, and LoRA** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-00635-6_9)]
- [2025] **Gender Bias in Instruction-Guided Speech Synthesis Models** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.298)]
- [2025] **Excitement-Inducing Commentary Text-to-Speech System for Fighting Game Video Scenes** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3648378)]
- [2025] **Concept Steerers: Leveraging K-Sparse Autoencoders for Test-Time Controllable Generations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.19066)]
- [2025] **CausDiff-HTR: Causality-Aware Diffusion Transformer for Explainable Handwritten Text Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5613131)]
- [2025] **Behavioral Prompting: A Mechanism for Injecting Cognitive Style and Affective Patterns into Large Language Models** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5728584)]
- [2025] **Art creator: Steering styles in diffusion model** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.129511)]

##### 2024

- [2024] **Enhancing Text Quality with Human-Machine Collaboration: A Refinement Approach** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-5506073/v1)]
- [2024] **Enhancing Painting Exhibition Experiences with the Application of Augmented Reality-Based AI Video Generation Technology** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-76815-6_18)]
- [2024] **DiffPPO: Reinforcement Learning Fine-Tuning of Diffusion Models for Text-to-Image Generation** [[paper](https://doi.org/10.1109/icnc64304.2024.10987802)]
- [2024] **Controllable 3D Object Generation with Single Image Prompt** *Lecture notes in computer science* [[paper](https://arxiv.org/abs/2511.22194)]
- [2024] **RoomTex: Texturing Compositional Indoor Scenes via Iterative Inpainting** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73113-6_27)]
- [2024] **I2TTS: Image-indicated Immersive Text-to-speech Synthesis with Spatial Perception** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.13314)]
- [2024] **DiffusionPen: Towards Controlling the Style of Handwritten Text Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73013-9_24)]
- [2024] **DAGSM: Disentangled Avatar Generation with GS-enhanced Mesh** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.15205)]
- [2024] **CTRLorALTer: Conditional LoRAdapter for Efficient 0-Shot Control and Altering of T2I Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73223-2_6)]
- [2024] **VoxInstruct: Expressive Human Instruction-to-Speech Generation with Unified Multilingual Codec Language Modelling** [[paper](https://arxiv.org/abs/2408.15676)]
- [2024] **Taming Diffusion for Fashion Clothing Generation with Versatile Condition** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-97-8620-6_42)]
- [2024] **StyleTokenizer: Defining Image Style by a Single Instance for Controlling Diffusion Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73390-1_7)]
- [2024] **A Token-Agnostic Approach to Controlling Generated Text Length in Large Language Models** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-5204102/v1)]
- [2024] **AudioComposer: Towards Fine-grained Audio Generation with Natural Language Descriptions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.12560)]
- [2024] **ArtWeaver: Advanced Dynamic Style Integration via Diffusion Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.15287)]
- [2024] **Big GCVAE: decision-making with adaptive transformer model for failure root cause analysis in semiconductor industry** *Journal of Intelligent Manufacturing* [[paper](https://doi.org/10.1007/s10845-024-02346-x)]
- [2024] **ProSwitch: Knowledge-Guided Instruction Tuning to Switch Between Professional and Non-Professional Responses** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.09131)]
- [2024] **Frequency-Controlled Diffusion Model for Versatile Text-Guided Image-to-Image Translation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://arxiv.org/abs/2407.03006)]
- [2024] **The Application of Artificial Intelligence Combined with Parametric Digital Design Tools in the Ceramic Modeling Design Process for Beginners. — A Geometric Vase as an Example** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-60615-1_26)]
- [2024] **Parameter-Efficient Detoxification with Contrastive Decoding** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.06947)]
- [2024] **From Ordinary to Polished: Refining Text with Human-Machine Collaboration Data** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.4924556)]
- [2024] **Fast 3D Stylized Gaussian Portrait Generation From a Single Image With Style Aligned Sampling Loss** *IEEE Access* [[paper](https://dx.doi.org/10.1109/access.2024.3392568)]
- [2024] **Controllable Text Layout Generation For Synthesizing Scene Text Image** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-70549-6_9)]
- [2024] **Comparative study on the advantages and disadvantages of AIGC tools in the field of industrial equipment modeling design** [[paper](https://doi.org/10.1145/3672758.3672915)]

##### 2023

- [2023] **Style Aligned Image Generation via Shared Attention** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.02133)]
- [2023] **EXIM: A Hybrid Explicit-Implicit Representation for Text-Guided 3D Shape Generation** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3618312)]
- [2023] **Nonparallel Expressive TTS for Unseen Target Speaker using Style-Controlled Adaptive Layer and Optimized Pitch Embedding** [[paper](https://dx.doi.org/10.1109/sped59241.2023.10314913)]
- [2023] **MIRACLE: Towards Personalized Dialogue Generation with Latent-Space Multiple Personal Attribute Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.18342)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Limits of n-gram Style Control for LLMs via Logit-Space Injection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.16224)]

##### 2025

- [2025] **Behavioral Prompting: A Mechanism for Injecting Cognitive Style and Affective Patterns into Large Language Models.** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17567381)]
- [2025] **Plang: Efficient prompt engineering language for blending natural language and control flow in large language models** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.130118)]
- [2025] **A Study on Controlling Character Deformation through AI Image Generation Model Training and Prompt Engineering** *Journal of Korea Multimedia Society* [[paper](https://doi.org/10.9717/kmms.2025.28.10.1599)]
- [2025] **A methodology for designing accurate, modifiable and reproducible scientific graphics in environmental studies using GPT4Designer** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-00300-2)]
- [2025] **Template-Based Text-to-Image Alignment for Language Accessibility: A Study on Visualizing Simplified Text** *Zurich Open Repository and Archive (University of Zurich)* [[paper](https://doi.org/10.5167/uzh-281057)]
- [2025] **Designing Personalized Multimodal Mnemonics With AI: A Medical Student’s Implementation Tutorial** *JMIR Medical Education* [[paper](https://doi.org/10.2196/67926)]

##### 2024

- [2024] **From Text to Pose to Image: Improving Diffusion Model Control and Quality** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.12872)]
- [2024] **PromptCharm: Text-to-Image Generation through Multi-modal Prompting and Refinement** [[paper](https://arxiv.org/abs/2403.04014)]
- [2024] **MULAN: A Multi Layer Annotated Dataset for Controllable Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.02790)]
- [2024] **Automated Black-box Prompt Engineering for Personalized Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.19103)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **GLASS: GRPO-Trained LoRA for Acoustic Style Steering in Zero-Shot Text-to-Speech** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05889)]
- [2026] **DisCo_Speech: Controllable Zero-Shot Speech Generation with A Disentangled Speech Codec** *Underline Science Inc.* [[paper](https://doi.org/10.48448/ntej-km77)]
- [2026] **Diff-Oracle: Learning Styles and Contents to Augment Realistic Oracle Characters in Diffusion Model** *ACM Transactions on Multimedia Computing Communications and Applications* [[paper](https://doi.org/10.1145/3806389)]
- [2026] **IndexTTS2: A Breakthrough in Emotionally Expressive and Duration-Controlled Auto-Regressive Zero-Shot Text-to-Speech** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i41.40820)]
- [2026] **From geometric mimicry to comprehensive generation: a context-informed multimodal diffusion model for urban morphology synthesis** *International Journal of Geographical Information Systems* [[paper](https://arxiv.org/abs/2409.17049)]
- [2026] **Cross-media style transfer in art: preserving artistic intent in diverse media using GANs** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-42852-x)]
- [2026] **LT-StyleCap: Lightweight Stylized Image Captioning With Dynamic Token Pruning and Factorized Style Control** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3704307)]

##### 2025

- [2025] **PerTTS: Personalized and Controllable Zero-Shot Spontaneous Style Text-to-Speech Synthesis** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2025.3639814)]
- [2025] **Style-Controlled VALL-E for Few-Shot Emotional German TTS** [[paper](https://doi.org/10.1109/sped67700.2025.11251681)]
- [2025] **FlexSpeech: Towards Stable, Controllable and Expressive Text-to-Speech** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.05159)]
- [2025] **Seeing Your Speech Style: A Novel Zero-Shot Identity-Disentanglement Face-based Voice Conversion** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i23.34694)]
- [2025] **Evolution and Perspectives of Speech Synthesis Technology: From Parametric Synthesis to the Era of Large Language Models** [[paper](https://doi.org/10.1109/icaid65275.2025.11034615)]
- [2025] **Zero-Shot Visual Concept Blending Without Text Guidance** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.21277)]
- [2025] **Spark-TTS: An Efficient LLM-Based Text-to-Speech Model with Single-Stream Decoupled Speech Tokens** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.01710)]
- [2025] **Zero-shot domain adaptation with enhanced consistency for semantic segmentation** *Computers & Electrical Engineering* [[paper](https://doi.org/10.1016/j.compeleceng.2025.110125)]
- [2025] **SPORT: From Zero-Shot Prompts to Real-Time Motion Generation** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3542631)]
- [2025] **Handwritten Text Generation with Diffusion Models: Beyond Visual Quality** *Epubl LTU* [[paper](https://urn.kb.se/resolve?urn=urn:nbn:se:ltu:diva-115100)]

##### 2024

- [2024] **ZePo: Zero-Shot Portrait Stylization with Faster Sampling** [[paper](https://arxiv.org/abs/2408.05492)]
- [2024] **UniStyle: Unified Style Modeling for Speaking Style Captioning and Stylistic Speech Synthesis** [[paper](https://doi.org/10.1145/3664647.3681465)]
- [2024] **PromotiCon: Prompt-based Emotion Controllable Text-to-Speech via Prompt Generation and Matching** [[paper](https://doi.org/10.1109/smc54092.2024.10831218)]
- [2024] **General-purpose pre-trained large cellular models for single-cell transcriptomics** *National Science Review* [[paper](https://doi.org/10.1093/nsr/nwae340)]
- [2024] **FireRedTTS: A Foundation Text-To-Speech Framework for Industry-Level Generative Speech Applications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.03283)]
- [2024] **ControlSpeech: Towards Simultaneous and Independent Zero-shot Speaker Cloning and Zero-shot Language Style Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.01205)]
- [2024] **Yolo-sd: simulated feature fusion for few-shot industrial defect detection based on YOLOv8 and stable diffusion** *International Journal of Machine Learning and Cybernetics* [[paper](https://doi.org/10.1007/s13042-024-02175-7)]
- [2024] **CTRLorALTer: Conditional LoRAdapter for Efficient 0-Shot Control & Altering of T2I Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.07913)]
- [2024] **Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.09967)]
- [2024] **V2Meow: Meowing to the Visual Beat via Video-to-Music Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i5.28299)]
- [2024] **AvatarVerse: High-Quality & Stable 3D Avatar Creation from Text and Pose** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i7.28540)]
- [2024] **Natural language guidance of high-fidelity text-to-speech with synthetic annotations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01912)]
- [2024] **ConRF: Zero-shot Stylization of 3D Scenes with Conditioned Radiation Fields** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01950)]
- [2024] **Standardize: Aligning Language Models with Expert-Defined Standards for Content Generation** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.94)]

##### 2023

- [2023] **Diff-Oracle: Deciphering Oracle Bone Scripts with Controllable Diffusion Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.13631)]
- [2023] **Audiobox: Unified Audio Generation with Natural Language Prompts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.15821)]
- [2023] **Bridging Code Semantic and LLMs: Semantic Chain-of-Thought Prompting for Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.10698)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2026

- [2026] **When Latent Geometry Is Not Enough: Draft-Conditioned Latent Refinement for Non-Autoregressive Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.15557)]
- [2026] **Unlocking Fine-Grained and Within-Utterance Speaking Style Control in Prompt-Based Text-to-Speech Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.27376)]
- [2026] **ISSE: An Instruction-Guided Speech Style Editing Dataset and Benchmark** [[paper](https://arxiv.org/abs/2509.24570)]
- [2026] **Autoregressive Styled Text Image Generation, but Make it Reliable** [[paper](https://doi.org/10.1109/wacv61042.2026.00358)]
- [2026] **DiMo: Discrete Diffusion Modeling for Motion Generation and Understanding** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.04188)]
- [2026] **Multimodal 2D/3D/4D Avatar Generation and Editing** [[paper](https://doi.org/10.14711/thesis-hdl169585)]

##### 2025

- [2025] **Controllable Text-to-Speech Synthesis with Masked-Autoencoded Style-Rich Representation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.02997)]
- [2025] **Generalized Multilingual Text-to-Speech Generation with Language-Aware Style Adaptation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08274)]

##### 2024

- [2024] **Content and Style Aware Audio-Driven Facial Animation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.07005)]
- [2024] **Metaphor Neural Generation Model Based on Cognitive Feature Constraints** *SSRN Electronic Journal* [[paper](https://dx.doi.org/10.2139/ssrn.4707242)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2026

- [2026] **PixelControl: Fine-Grained Condition Fidelity in Text-to-Image Diffusion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.15705)]
- [2026] **LDM-styler: a latent diffusion network for semantic-aware oil painting style transfer and cross-modal imagery reconstruction** *Journal of King Saud University - Computer and Information Sciences* [[paper](https://doi.org/10.1007/s44443-026-00978-y)]
- [2026] **Generative Modeling of Digital Artifacts with Style-Based GANs** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22202172)]
- [2026] **Beyond Starry Night: Shortcut-Aware Control-State Planning for Artist-Grounded Text to Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.06751)]
- [2026] **Research on human-AI collaboration mechanism of text-guided image generation models in visual communication design teaching** *Systems and Soft Computing* [[paper](https://doi.org/10.1016/j.sasc.2026.200543)]
- [2026] **Controllable Generation with Diffusion Models and Applications in Medical Imaging** *Durham e-Theses (Durham University)* [[paper](https://etheses.durham.ac.uk/id/eprint/16656/1/Junjie_PhD_Thesis_final.pdf)]
- [2026] **Controllable generation of building representations: Aligning campus building design intent with multi-stage retrieval-augmented diffusion models** *Frontiers of Architectural Research* [[paper](https://doi.org/10.1016/j.foar.2026.01.018)]
- [2026] **Semantic understanding and controllable generation methods of AIGC in virtual reality scene construction** *Discover Computing* [[paper](https://doi.org/10.1007/s10791-026-09991-1)]
- [2026] **Narratology meets text-to-image: a survey of consistency in AI generated storybook illustrations** *Artificial Intelligence Review* [[paper](https://doi.org/10.1007/s10462-025-11482-6)]
- [2026] **Composite-Semantic Control for NEV Styling Using Bayesian Evidence Updating and LoRA-Tuned Diffusion Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3685439)]

##### 2025

- [2025] **Stance-Driven Multimodal Controlled Statement Generation: New Task and Dataset** [[paper](https://doi.org/10.1145/3743093.3771055)]
- [2025] **Motion AutoStyling via Seperable Modelling of Posing and Dynamic LoRAs** [[paper](https://doi.org/10.1145/3757376.3771387)]
- [2025] **Eliciting Implicit Acoustic Styles from Open-domain Instructions to Facilitate Fine-grained Controllable Generation of Speech** *Underline Science Inc.* [[paper](https://doi.org/10.48448/fhrx-0h18)]
- [2025] **A pipeline for stochastic and controlled generation of realistic language input for simulating infant language acquisition** *Behavior Research Methods* [[paper](https://doi.org/10.3758/s13428-025-02772-6)]
- [2025] **Towards Controllable and Explainable Text Generation via Causal Intervention in LLMs** *Electronics* [[paper](https://doi.org/10.3390/electronics14163279)]
- [2025] **ESCT3D: Efficient and Selectively Controllable Text-Driven 3D Content Generation with Gaussian Splatting** *Proceedings of the ACM on Computer Graphics and Interactive Techniques* [[paper](https://arxiv.org/abs/2504.10316)]

##### 2024

- [2024] **UNIC-Adapter: Unified Image-instruction Adapter with Multi-modal Transformer for Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.18928)]
- [2024] **ECGText: Human-Centric Text Generation with Enhanced Emotional Intelligence** [[paper](https://doi.org/10.1109/calcon63337.2024.10914281)]
- [2024] **DreamPBR: Text-driven Generation of High-resolution SVBRDF with Multi-modal Guidance** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.14676)]
- [2024] **Controllable 3D Face Generation with Conditional Style Code Diffusion** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i5.28283)]
- [2024] **Attack Deterministic Conditional Image Generative Models for Diverse and Controllable Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i2.27900)]
- [2024] **Visual Style Prompting with Swapping Self-Attention** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.12974)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2025

- [2025] **Chinese Story Generation Based on Style Control of Transformer Model and Content Evaluation Method** *Algorithms* [[paper](https://doi.org/10.3390/a18030168)]
- [2025] **From Tokens to Tales: Semantic Similarity in Story Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-88036-0_9)]

##### 2024

- [2024] **Towards Logic-Consistent and Controllable Automatic Story Generation** *The Sydney eScholarship Repository (The University of Sydney)* [[paper](https://hdl.handle.net/2123/33249)]

##### 2023

- [2023] **The Science of Character: Human Objecthood and the Ends of Victorian Realism** *Modern Language Quarterly* [[paper](https://doi.org/10.1215/00267929-10929026)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **On the Limits of Steering Vectors for Preference-Aligned Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.01802)]
- [2026] **MythoBiLLM: BiLSTM-Guided Parameter-Efficient Fine-Tuning of Large Language Models for Coherent Summarization and Generation of Indian Mythological Texts** *Information* [[paper](https://doi.org/10.3390/info17080726)]
- [2026] **LAGRANGE OBSERVATORY! (LO!) Chamber Specification & Nobel Glas Provenance Crimson Hexagon Extension — Semantic Torus Field Hex: 15.OBS.LAGRANGE DOI: 10.5281/zenodo.18507849 — Crimson Hexagon Archive** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18507849)]
- [2026] **Controlling affective variables in conditional natural language generation** [[paper](https://nbn-resolving.de/urn:nbn:de:bsz:93-opus-ds-178800)]

##### 2025

- [2025] **Methods For Text Style Processing** *Qucosa (Saxon State and University Library Dresden)* [[paper](https://ul.qucosa.de/id/qucosa%3A99611)]

##### 2024

- [2024] **A new era of AI‐assisted journalism at Bloomberg** *AI Magazine* [[paper](https://doi.org/10.1002/aaai.12181)]
- [2024] **The Potential Application of Large Language Models in Pharmaceutical Supply Chain Management** *The Journal of Pediatric Pharmacology and Therapeutics* [[paper](https://doi.org/10.5863/1551-6776-29.2.200)]

##### 2023

- [2023] **Dont Add, dont Miss: Effective Content Preserving Generation from Pre-Selected Text Spans** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.09017)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **Title: Adaptive Neural Networks for Style Transfer Learning** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22183702)]
- [2026] **The Plan, Not the Decoder: Diagnosing and Repairing Compositional Failure in Reasoning-Augmented Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.21713)]
- [2026] **Learning Music Style for Piano Arrangement Through Cross-Modal Bootstrapping** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.03050)]
- [2026] **Multimodal 3D LUT Generation via StatLUT with Statistical Features for Photorealistic Style Transfer** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.08227)]
- [2026] **AutoSIFT: Automatic Style Sifting for Controllable Speech Generation with Arbitrary Style Infilling** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.12706)]
- [2026] **Compressing Image Style Training into a Single Model Forward** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.13809)]
- [2026] **Adaptive Content and Style Fusion for Text-to-Image Generations** *Electronics* [[paper](https://doi.org/10.3390/electronics15132800)]
- [2026] **Stylized Text-to-Motion Synthesis Via Multi-Condition Latent Diffusion** [[paper](https://doi.org/10.1109/icassp55912.2026.11461022)]
- [2026] **Heterogeneous Text Style Control Using Prompts** *ACM Transactions on Asian and Low-Resource Language Information Processing* [[paper](https://doi.org/10.1145/3806042)]
- [2026] **HAM: A Training-Free Style Transfer Approach via Heterogeneous Attention Modulation for Diffusion Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.24043)]
- [2026] **CleanStyle: Plug-and-Play Style Conditioning Purification for Text-to-Image Stylization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.20721)]
- [2026] **TSLP: Text driven and style transferable indoor furniture layout generation pipeline** [[paper](https://doi.org/10.65286/icic.v22i1.68723)]
- [2026] **LAMS-Edit: Latent and Attention Mixing with Schedulers for Improved Content Preservation in Diffusion-Based Image and Style Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.02987)]
- [2026] **Intelligent generation algorithm for digital image artworks based on decoupling representation and content-aware** *International Journal of Information and Communication Technology* [[paper](https://doi.org/10.1504/ijict.2026.153802)]
- [2026] **Intelligent Short-Video Generation and Style Transfer for Intangible Cultural Heritage Dissemination** [[paper](https://doi.org/10.1145/3806262.3806299)]
- [2026] **AbjadStyleTransfer: Authorship Style Transfer for Arabic-Script Languages at AbjadNLP 2026** [[paper](https://doi.org/10.18653/v1/2026.abjadnlp-1.70)]

##### 2025

- [2025] **Mcgm-styler: free-form styler for mask conditional text-to-image generative model** *The Visual Computer* [[paper](https://doi.org/10.1007/s00371-025-04226-8)]
- [2025] **Loom: Diffusion-Transformer for Interleaved Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.18254)]
- [2025] **Deep Learning-Based Automatic Generation and Style Transfer for Film and Television Dubbing** [[paper](https://doi.org/10.1145/3795154.3795260)]
- [2025] **Design of multimodal generation model and semantic driven reconstruction method for intangible cultural heritage text language data** [[paper](https://doi.org/10.1117/12.3091459)]
- [2025] **StyleMM: Stylized 3D Morphable Face Model via Text‐Driven Aligned Image Translation** *Computer Graphics Forum* [[paper](https://doi.org/10.1111/cgf.70234)]
- [2025] **Design of personalized creation model for cultural and creative products based on evolutionary adaptive network** *PeerJ Computer Science* [[paper](https://doi.org/10.7717/peerj-cs.3288)]
- [2025] **OpenGPT-4o-Image: A Comprehensive Dataset for Advanced Image Generation and Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.24900)]
- [2025] **Humor Style Transfer for Virtual AI Teachers Using StyleGPT4o for Comedian Guided Script Rewriting in Virtual Educational Environments** [[paper](https://doi.org/10.1109/iccgiv65419.2025.11085094)]
- [2025] **Break Stylistic Sophon: Are We Really Meant to Confine the Imagination in Style Transfer?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.15033)]
- [2025] **Text to Sketch Generation with Multi-Styles** [[paper](https://arxiv.org/abs/2511.04123)]
- [2025] **SwapDiffusion: Flexible Swapping Disentangled Content‐Style Embeddings in P+ \mathcal{P}+ Space for Diffusion Models** *IET Computer Vision* [[paper](https://doi.org/10.1049/cvi2.70048)]
- [2025] **Optimization Method for Controllable Image Style Transfer Based on DDPM Guided by Cross-Modal Text** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3643194)]
- [2025] **Nonparallel Spoken-Text-Style Transfer for Linguistic Expression Control in Speech Generation** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2024.3522757)]
- [2025] **Multi-channel correlated diffusion for text-driven artistic style transfer** *The Visual Computer* [[paper](https://doi.org/10.1007/s00371-025-03799-8)]
- [2025] **LingConv: An Interactive Toolkit for Controlled Paraphrase Generation with Linguistic Attribute Control** [[paper](https://doi.org/10.18653/v1/2025.emnlp-demos.4)]
- [2025] **Improved 3D Scene Stylization via Text-Guided Generative Image Editing with Region-Based Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.05285)]
- [2025] **Exploring The Practical Applications of Text-Guided Image Stylization: A Case Study of Diffstyler** *ITM Web of Conferences* [[paper](https://doi.org/10.1051/itmconf/20257804011)]
- [2025] **Discourse Driven Neural Text Style Transfer With Linguistic Adapatation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5021957)]
- [2025] **CSGO: Content-Style Composition in Text-to-Image Generation** [[paper](https://arxiv.org/abs/2408.16766)]

##### 2024

- [2024] **StyleStudio: Text-Driven Style Transfer with Selective Control of Style Elements** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.08503)]
- [2024] **IconDM: Text-Guided Icon Set Expansion Using Diffusion Models** [[paper](https://doi.org/10.1145/3664647.3681057)]
- [2024] **Editing Music with Melody and Text: Using ControlNet for Diffusion Transformer** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.05151)]
- [2024] **Text Prompt is Not Enough: Sound Event Enhanced Prompt Adapter for Target Style Audio Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.09381)]
- [2024] **Prompt-Softbox-Prompt: A Free-Text Embedding Control for Image Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.13623)]
- [2024] **Self-supervised Text Style Transfer Using Cycle-Consistent Adversarial Networks** *ACM Transactions on Intelligent Systems and Technology* [[paper](https://doi.org/10.1145/3678179)]
- [2024] **Combining audio control and style transfer using latent diffusion** *HAL (Le Centre pour la Communication Scientifique Directe)* [[paper](https://arxiv.org/abs/2408.00196)]
- [2024] **Multi-Style Shape Matching GAN for Text Images** *IEICE Transactions on Information and Systems* [[paper](https://doi.org/10.1587/transinf.2023ihp0010)]
- [2024] **Memory-enhanced text style transfer with dynamic style learning and calibration** *Science China Information Sciences* [[paper](https://doi.org/10.1007/s11432-022-3726-0)]
- [2024] **3D-aware Image Generation and Editing with Multi-modal Conditions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.06470)]
- [2024] **Foreground and background separated image style transfer with a single text condition** *Image and Vision Computing* [[paper](https://doi.org/10.1016/j.imavis.2024.104956)]
- [2024] **Paraphrasers and Classifiers: Controllable Text Generation for Text Style Transfer** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-54534-4_7)]
- [2024] **Disentangled Learning with Synthetic Parallel Data for Text Style Transfer** [[paper](https://doi.org/10.18653/v1/2024.acl-long.811)]

##### 2023

- [2023] **Unraveling the Impact of Explainability of Artificial Intelligence-Generated Content(AIGC) on Design Style Transfer Effects** [[paper](https://doi.org/10.1145/3638884.3638910)]
- [2023] **Anything to Glyph: Artistic Font Synthesis via Text-to-Image Diffusion Model** [[paper](https://doi.org/10.1145/3610548.3618208)]
- [2023] **LOVECon: Text-driven Training-Free Long Video Editing with ControlNet** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.09711)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **A Structured Approach to Grammar and Style Checking of Scientific Texts With ChatGPT** [[paper](https://doi.org/10.1109/ichora69329.2026.11536994)]
- [2026] **Impact of glycaemic control on complication rates after breast reconstruction** *BJS Open* [[paper](https://doi.org/10.1093/bjsopen/zrag012)]

##### 2025

- [2025] **Exam-Guided Automatic Cloze Generation from Raw Text via Data Shaping and Structured Decoding** [[paper](https://doi.org/10.1109/icftic68075.2025.11325038)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **Provenance-Constrained Selective Language Style Planning from Sparse Evidence** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22107472)]
- [2026] **Stone Style Programming paradigm prototype** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20637777)]

##### 2025

- [2025] **Artificial Intelligence in Multimedia Content Generation: A Review of Audio and Video Synthesis Techniques** *Journal of the Society for Information Display* [[paper](https://doi.org/10.1002/jsid.2111)]
- [2025] **Epistemic authority and generative AI in learning spaces: rethinking knowledge in the algorithmic age** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1647687)]
- [2025] **Text Mesh Generation Based on Mesh Shape** *Journal of the Korea Computer Graphics Society* [[paper](https://doi.org/10.15701/kcgs.2025.31.3.11)]
- [2025] **Towards Better Cephalometric Landmark Detection With Diffusion Data Generation** *IEEE Transactions on Medical Imaging* [[paper](https://doi.org/10.1109/tmi.2025.3557430)]
- [2025] **LayerCraft: Enhancing Text-to-Image Generation with CoT Reasoning and Layered Object Integration** [[paper](https://arxiv.org/abs/2504.00010)]
- [2025] **Controllable image generation and editing** *DR-NTU (Nanyang Technological University)* [[paper](https://hdl.handle.net/10356/184129)]
- [2025] **CoT-lized Diffusion: Let's Reinforce T2I Generation Step-by-step** [[paper](https://arxiv.org/abs/2507.04451)]

##### 2024

- [2024] **Forum on Artificial Intelligence** *Journal of Film and Video* [[paper](https://doi.org/10.5406/19346018.76.1.05)]
- [2024] **FEATURES, PROBLEMS, AND PROSPECTS OF USING ARTIFICIAL INTELLIGENCE IN THE CONTEMPORARY ART FIELD: WRITING, FINE ARTS, VOICE ACTING** *ART Space* [[paper](https://dx.doi.org/10.28925/2519-4135.2024.49)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **TransAnyText: Translating Arbitrary Text in E-commerce Images via Structured Visual Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.16284)]
- [2026] **EmoStyle: Affective Conditioning of Style-Specialist Experts for Emotional Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.10165)]
- [2026] **ArtChart: Faithful Artistic Chart Generation with Integrated Text Rendering** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.16060)]
- [2026] **Gender Artifacts from Art History to Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05829)]
- [2026] **Class-Structure Preservation Beats Diversity: A Comprehensive Benchmark of Text Augmentation Methods for Imbalanced Text Classification** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.12340)]
- [2026] **A Semantic Risk-Aware Optimization Framework for Virtual Power Plant Dispatch Using Large Language Models** *Energies* [[paper](https://doi.org/10.3390/en19122820)]
- [2026] **DriveCtrl: Conditioned Sim-to-Real Driving Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.15116)]
- [2026] **Detecting AI-Generated Text** *Advanced International Journal for Research* [[paper](https://doi.org/10.63363/aijfr.2026.v07i03.5461)]
- [2026] **AniMatrix: An Anime Video Generation Model that Thinks in Art, Not Physics** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.03652)]
- [2026] **WRitEer: A Multi-Objective, Preference-Driven Multi-Agent Framework for Human-Like Advanced Text Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i35.40232)]
- [2026] **VideoStylist: Text-to-Consistent Video Stylization with Temporal Anchor Tokens** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202603.1287.v1)]
- [2026] **TokenDial: Continuous Attribute Control in Text-to-Video via Spatiotemporal Token Offsets** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.27520)]
- [2026] **Structured Linked Data as a Memory Layer for Agent-Orchestrated Retrieval** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.10700)]
- [2026] **LogoDiffuser: Training-Free Multilingual Logo Generation and Stylization via Letter-Aware Attention Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.09759)]
- [2026] **FontUse: A Data-Centric Approach to Style- and Use-Case-Conditioned In-Image Typography** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.06038)]
- [2026] **Muse: Towards Reproducible Long-Form Song Generation with Fine-Grained Style Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.03973)]
- [2026] **Exploring text-to-image generators for enhancing artistic creativity for cartoon aesthetics** *DR-NTU (Nanyang Technological University)* [[paper](https://hdl.handle.net/10356/216636)]
- [2026] **Automatic social media content generation and style control via multimodal generative models: a methodological study** [[paper](https://doi.org/10.1117/12.3088991)]

##### 2025

- [2025] **Conceptualizing Visuals: A Foundational Model for Compositional and Controllable Text-to-Image Synthesis** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17827820)]
- [2025] **3SGen: Unified Subject, Style, and Structure-Driven Image Generation with Adaptive Task-specific Memory** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.19271)]
- [2025] **SplatFont3D: Structure-Aware Text-to-3D Artistic Font Generation with Part-Level Style Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.00413)]
- [2025] **Research on the Digital Interactive Design Platform for the Intelligent Generation of Clothing Styles** [[paper](https://doi.org/10.1109/isai-nlp66160.2025.11320535)]
- [2025] **Dataset for Sentiment and Named Entity Analysis in Uzbek Texts** *Mendeley Data* [[paper](https://doi.org/10.17632/y2d5pcyrzz.2)]
- [2025] **TextSSR: Diffusion-Based Data Synthesis for Scene Text Recognition** [[paper](https://arxiv.org/abs/2412.01137)]
- [2025] **ASMCC-Diff: Arbitrary Size Multi-Condition Controllable Chinese Landscape Painting Generation with Diffusion Models** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia250842)]
- [2025] **LLM-Generated Dataset for Speech-Driven 3D Facial Animation Models with Text-Controlled Expressivity** [[paper](https://doi.org/10.5753/sibgrapi.est.2025.38323)]
- [2025] **From Sketch to CAD Code: Multimodal AI for Controllable Design Generation** *DSpace@MIT (Massachusetts Institute of Technology)* [[paper](https://hdl.handle.net/1721.1/165165)]
- [2025] **Multi-Story Building Image Generation Using Retrieval Augmented Diffusion Models** [[paper](https://doi.org/10.1109/nicoint67466.2025.00013)]
- [2025] **SARD: A Large-Scale Synthetic Arabic OCR Dataset for Book-Style Text Recognition** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.24600)]
- [2025] **P2VA: Converting Persona Descriptions into Voice Attributes for Fair and Controllable Text-to-Speech** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.17093)]
- [2025] **MotionCrafter: Plug-and-Play Motion Guidance for Diffusion Models** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3568880)]
- [2025] **GlyphMastero: A Glyph Encoder for High-Fidelity Scene Text Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.04915)]
- [2025] **One-Shot Reference-based Structure-Aware Image to Sketch Synthesis** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i9.33000)]
- [2025] **Generative AI for Film Creation: A Survey of Recent Advances** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08296)]
- [2025] **ELSA: A Style Aligned Dataset for Emotionally Intelligent Language Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08281)]
- [2025] **CL-Attack: Textual Backdoor Attacks via Cross-Lingual Triggers** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v39i25.34842)]
- [2025] **AnyArtisticGlyph: Multilingual Controllable Artistic Glyph Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.04743)]
- [2025] **MagicScroll: Enhancing Immersive Storytelling with Controllable Scroll Image Generation** [[paper](https://doi.org/10.1109/vr59515.2025.00067)]
- [2025] **Steganographic embedding model in files with hierarchical structure** *Journal Of Applied Informatics* [[paper](https://doi.org/10.37791/2687-0649-2025-20-1-125-139)]

##### 2024

- [2024] **Can video generation replace cinematographers? Research on the cinematic language of generated video** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.12223)]
- [2024] **Controllable Music Loops Generation with MIDI and Text via Multi-Stage Cross Attention and Instrument-Aware Reinforcement Learning** [[paper](https://doi.org/10.1145/3664647.3681187)]
- [2024] **Image Generation Algorithm of Text Description Based on StyleGAN** [[paper](https://doi.org/10.1145/3700906.3700908)]
- [2024] **Feature Fusion for Multi-Condition Controllable Image Generation** [[paper](https://doi.org/10.1145/3697355.3697368)]
- [2024] **FLUXSynID: A Synthetic Face Dataset with Document and Live Images** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.03168)]
- [2024] **InstantStyle: Free Lunch towards Style-Preserving in Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.02733)]
- [2024] **AI - Assisted Text Composition for Automated Content Authoring Using Transformer-Based Language Models** [[paper](https://dx.doi.org/10.1109/ic_aset61847.2024.10596255)]
- [2024] **Stable-Makeup: When Real-World Makeup Transfer Meets Diffusion Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.07764)]
- [2024] **Freetalker: Controllable Speech and Text-Driven Gesture Generation Based on Diffusion Models for Enhanced Speaker Naturalness** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.03476)]

##### 2023

- [2023] **MotionCrafter: One-Shot Motion Customization of Diffusion Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.05288)]
- [2023] **MagicStick: Controllable Video Editing via Control Handle Transformations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.03047)]
- [2023] **MagicScroll: Nontypical Aspect-Ratio Image Generation for Visual Storytelling via Multi-Layered Semantic-Aware Denoising** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.10899)]
- [2023] **Stable Diffusion Reference Only: Image Prompt and Blueprint Jointly Guided Multi-Condition Diffusion Model for Secondary Painting** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.02343)]
- [2023] **Russian language and speech culture. Textbook and workshop** [[paper](https://doi.org/10.12737/1846127)]
- [2023] **Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.03602)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2026

- [2026] **RAG-VisualRec: An Open Resource for Vision- and Text-Enhanced Retrieval-Augmented Generation in Recommendation** *ACM Transactions on Recommender Systems* [[paper](https://arxiv.org/abs/2506.20817)]

[⬆ Back to top](#paper-list)

#### Human-in-the-Loop

##### 2025

- [2025] **An Interactive Drawing Assistant Harmonizing User Control and Creative Freedom in Image Generation** [[paper](https://doi.org/10.1145/3743093.3770961)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **HyperSketch: Controllable Video Sketching in a Style Hyperspace** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2609.00919)]
- [2026] **PosterText: Towards Unified Visual Text Generation and Editing for E-commerce Poster** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.16289)]
- [2026] **A Human-Computer Collaborative Video Creation Paradigm Integrating Creative Intent Memory, Preference Feedback, and Editable Generation Control** *Advanced Electromagnetics* [[paper](https://www.aemjournal.org/index.php/AEM/article/view/4200)]
- [2026] **Style-controllable adversarial example generation via image editing and prompt embedding optimization** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2026.134591)]
- [2026] **TextWand: A Unified Framework for Scene Text Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05730)]
- [2026] **Pareto-Guided Teacher Alignment for Fair Personalized Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.10126)]
- [2026] **Insert Anything: Image Insertion via In-Context Editing in DiT** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i11.37866)]
- [2026] **SIGMA: Selective-Interleaved Generation with Multi-Attribute Tokens** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.07564)]
- [2026] **Vevo2: A Unified and Controllable Framework for Speech and Singing Voice Generation** *IEEE Transactions on Audio Speech and Language Processing* [[paper](https://doi.org/10.1109/taslpro.2026.3671970)]

##### 2025

- [2025] **Handwritten-Text-Image Editing with Diffusion Models and Attention-Based Matching** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-4395-3_29)]
- [2025] **Expressive Human Volumetric Video Generation With Rich Text** *IEEE Transactions on Circuits and Systems for Video Technology* [[paper](https://doi.org/10.1109/tcsvt.2025.3628996)]
- [2025] **Parametric Shadow Control for Portrait Generation in Text-to-Image Diffusion Models** [[paper](https://arxiv.org/abs/2503.21943)]
- [2025] **FreeInsert : Personalized Object Insertion with Geometric and Style Control** [[paper](https://doi.org/10.1145/3746027.3755603)]
- [2025] **Development of mask guided visual effect generation with generative AI** [[paper](https://doi.org/10.1109/ictc66702.2025.11387993)]
- [2025] **Controllable Face Inpainting via Pseudo-Style Embedding** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia250815)]
- [2025] **FreeInsert: Personalized Object Insertion with Geometric and Style Control** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.20756)]
- [2025] **A Study of Text-Guided Photographic Image Generation Based on PSDM** [[paper](https://doi.org/10.1109/icpics66386.2025.11347194)]
- [2025] **FontAdapter: Instant Font Adaptation in Visual Text Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.05843)]
- [2025] **CreatiPoster: Towards Editable and Controllable Multi-Layer Graphic Design Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.10890)]
- [2025] **SVGDreamer++: Advancing Editability and Diversity in Text-Guided SVG Generation** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3547889)]
- [2025] **Expressive Image Generation and Editing with Rich Text** *International Journal of Computer Vision* [[paper](https://doi.org/10.1007/s11263-025-02361-2)]

##### 2024

- [2024] **SwapAnything: Enabling Arbitrary Object Swapping in Personalized Image Editing** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73411-3_23)]
- [2024] **T2DyVec: Leveraging Sparse Images and Controllable Text for Dynamic SVG** [[paper](https://doi.org/10.1145/3641234.3671020)]
- [2024] **LOOSECONTROL: Lifting ControlNet for Generalized Depth Conditioning** [[paper](https://doi.org/10.1145/3641519.3657525)]
- [2024] **PaRa: Personalizing Text-to-Image Diffusion via Parameter Rank Reduction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.05641)]
- [2024] **On Mechanistic Knowledge Localization in Text-to-Image Generative Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.01008)]
- [2024] **Voice Attribute Editing with Text Prompt** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.08857)]
- [2024] **SwapAnything: Enabling Arbitrary Object Swapping in Personalized Visual Editing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.05717)]

##### 2023

- [2023] **ProSpect: Prompt Spectrum for Attribute-Aware Personalization of Diffusion Models** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3618342)]
- [2023] **Tailoring Digital Privacy Education Interventions for Older Adults: A Comparative Study on Modality Preferences and Effectiveness** *Proceedings on Privacy Enhancing Technologies* [[paper](https://doi.org/10.56553/popets-2024-0036)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **LITERARYBIGFIVE: Author-Personalized Text Generation in a Unified Interpretable Space** [[paper](https://arxiv.org/abs/2608.23124)] [[code](https://github.com/Znull-1220/LiteraryBigFive)]
- [2026] **MAGDiff: a synergistic multi-attribute-guided diffusion framework for personalized fashion garment generation** *The Visual Computer* [[paper](https://doi.org/10.1007/s00371-026-04611-x)]
- [2026] **What Makes an AI Writing Companion a Good Fit? A Personality-Informed Co-Design Study** [[paper](https://arxiv.org/abs/2605.01108)]
- [2026] **Collocation Generation and Style Consistency Verification of Personalized Soft Outfit Based on Diffusion Model** *Journal of Intelligence and Engineering Technology* [[paper](https://doi.org/10.70393/6a696574.343132)]
- [2026] **Premier: Personalized Preference Modulation with Learnable User Embedding in Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.20725)]
- [2026] **Simulating Word Suggestion Usage in Mobile Typing to Guide Intelligent Text Entry Design** [[paper](https://arxiv.org/abs/2602.06489)]
- [2026] **CRAFT-LoRA: Content-Style Personalization via Rank-Constrained Adaptation and Training-Free Fusion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.18936)]
- [2026] **Who Owns the Text? Design Patterns for Preserving Authorship in AI-Assisted Writing** [[paper](https://arxiv.org/abs/2601.10236)]
- [2026] **Multimodal Dance Generation With Multi‐Granularity Style Control and Text Guidance** *Computer Animation and Virtual Worlds* [[paper](https://doi.org/10.1002/cav.70097)]

##### 2025

- [2025] **Diffusion-Controlled Aesthetic QR Code Generation using Text-to-Image Guidance** [[paper](https://doi.org/10.1109/icaft66710.2025.11452808)]
- [2025] **Typing Reinvented: Towards Hands-Free Input via sEMG** [[paper](https://arxiv.org/abs/2511.18213)]
- [2025] **PersonaGen: A Persona-Driven Open-Ended Machine-Generated Text Dataset** [[paper](https://doi.org/10.1145/3746252.3761611)]
- [2025] **Human Head Animation Generation Methods Driven by Multimodality** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2026.tj29059)]
- [2025] **Digital Companionship: Overlapping Uses of AI Companions and AI Assistants** [[paper](https://arxiv.org/abs/2510.15905)]
- [2025] **PersonaEval: Are LLM Evaluators Human Enough to Judge Role-Play?** [[paper](https://arxiv.org/abs/2508.10014)] [[code](https://github.com/maple-zhou/PersonaEval)]
- [2025] **Detecting Reading-Induced Confusion Using EEG and Eye Tracking** [[paper](https://arxiv.org/abs/2508.14442)]
- [2025] **CAP-LLM: Context-Augmented Personalized Large Language Models for News Headline Generation** [[paper](https://arxiv.org/abs/2508.03935)]
- [2025] **Artificial Intelligence (AI)-Driven Artistic Design With Stable Diffusion and BERT: Controllable Style–Emotion Alignment via Multimodal Generation and Sentiment Prediction** *The European Journal on Artificial Intelligence* [[paper](https://doi.org/10.1177/30504554251361472)]
- [2025] **Your Interface, Your Control: Adapting Takeover Requests for Seamless Handover in Semi-Autonomous Vehicles** [[paper](https://arxiv.org/abs/2506.01836)]
- [2025] **Fitted-Singer: Singing Voice Synthesis with Style Control and Rhythm Control** [[paper](https://doi.org/10.1109/icme59968.2025.11208979)]
- [2025] **A Literature Review on Simulation in Conversational Recommender Systems** [[paper](https://arxiv.org/abs/2506.20291)]
- [2025] **LLM-Enabled Style and Content Regularization for Personalized Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.15309)]
- [2025] **AI-enhanced conversational avatars for immersive interaction** *World Journal of Advanced Research and Reviews* [[paper](https://doi.org/10.30574/wjarr.2025.26.1.1101)]
- [2025] **Natural Language Processing in Generative Adversarial Network** [[paper](https://doi.org/10.1002/9781394209835.ch4)]
- [2025] **Enhancing Impression Change Prediction in Speed Dating Simulations Based on Speakers' Personalities** [[paper](https://arxiv.org/abs/2502.04706)]
- [2025] **Reasoning-Enhanced Self-Training for Long-Form Personalized Text Generation** [[paper](https://arxiv.org/abs/2501.04167)]
- [2025] **Free-Form Motion Control: A Synthetic Video Generation Dataset with Controllable Camera and Object Motions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.01425)]
- [2025] **ExPerT: Effective and Explainable Evaluation of Personalized Long-Form Text Generation** [[paper](https://arxiv.org/abs/2501.14956)]
- [2025] **Empathetic Conversational Agents: Utilizing Neural and Physiological Signals for Enhanced Empathetic Interactions** [[paper](https://arxiv.org/abs/2501.08393)]
- [2025] **Decider: A Dual-System Rule-Controllable Decoding Framework for Language Generation** *IEEE Transactions on Knowledge and Data Engineering* [[paper](https://doi.org/10.1109/tkde.2025.3554819)]

##### 2024

- [2024] **Research on the Interpretability and Controllability of Deep Learning-Based Exhibition Design Style Generation and Transfer** [[paper](https://doi.org/10.1109/icngn63705.2024.10871519)]
- [2024] **Infinite-ID: Identity-Preserved Personalization via ID-Semantics Decoupling Paradigm** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73242-3_16)]
- [2024] **Transforming Wearable Data into Personal Health Insights using Large Language Model Agents** [[paper](https://arxiv.org/abs/2406.06464)]
- [2024] **Ink and Individuality: Crafting a Personalised Narrative in the Age of LLMs** [[paper](https://arxiv.org/abs/2404.00026)]
- [2024] **Critique of comparative law: to compierreNegative Comparative Law: A Strong Programme for Weak Thought By PierreLegrand, Cambridge: Cambridge University Press, 2022, 352 pp., £95.00** *Journal of Law and Society* [[paper](https://doi.org/10.1111/jols.12466)]
- [2024] **Shaping Human-AI Collaboration: Varied Scaffolding Levels in Co-writing with Language Models** [[paper](https://arxiv.org/abs/2402.11723)]
- [2024] **Personalized Text Generation with Fine-Grained Linguistic Control** [[paper](https://doi.org/10.18653/v1/2024.personalize-1.8)]
- [2024] **A Two-Stage Personalized Virtual Try-On Framework With Shape Control and Texture Guidance** *IEEE Transactions on Multimedia* [[paper](https://doi.org/10.1109/tmm.2024.3405718)]

##### 2023

- [2023] **Can ChatGPT Read Who You Are?** [[paper](https://arxiv.org/abs/2312.16070)]
- [2023] **Prompt-to-OS (P2OS): Revolutionizing Operating Systems and Human-Computer Interaction with Integrated AI Generative Models** [[paper](https://arxiv.org/abs/2310.04875)]
- [2023] **Automated Evaluation of Personalized Text Generation using Large Language Models** [[paper](https://arxiv.org/abs/2310.11593)]
- [2023] **Automating question generation from educational text** [[paper](https://arxiv.org/abs/2309.15004)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **The Privacy-Hallucination Tradeoff in Differentially Private Language Models** [[paper](https://arxiv.org/abs/2609.00492)]
- [2026] **TA-RAG: Tone Awareness as a Design Imperative for Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2608.06672)]
- [2026] **Hallucination Span Detection with Input-Side Evidence Alignment** [[paper](https://arxiv.org/abs/2608.15804)]
- [2026] **HalluTruthQA-4K: A Fine-Grained Corpus and Annotation Process for Arabic Hallucination Detection and Truth Verification** [[paper](https://arxiv.org/abs/2608.03966)]
- [2026] **Mitigating Factual Hallucination in Large Reasoning Models via Mixed-Mode Advantage Regularization** [[paper](https://arxiv.org/abs/2607.05861)]
- [2026] **MAG: A Web-Agent Benchmark and Harness for Multimodal Action and Guide Generation** [[paper](https://arxiv.org/abs/2607.10079)]
- [2026] **Knowledge-Graph-Gated Defactualization for Style-Controllable and Fact-Preserving Generation in Agentic Conversational AI** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.20393)]
- [2026] **Not All Claims Are Equally Risky: FACTOR for Adaptive Verification in Factual Long-Form Generation** [[paper](https://arxiv.org/abs/2606.22474)]
- [2026] **RoadTones: Tone Controllable Text Generation from Road Event Videos** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.21411)]
- [2026] **Hallucination as an Anomaly: Dynamic Intervention via Probabilistic Circuits** [[paper](https://arxiv.org/abs/2605.05953)]
- [2026] **Clarify, Abstain or Answer? Strategising in Conversation with Belief-Augmented Generation** [[paper](https://arxiv.org/abs/2605.25831)]
- [2026] **Why Fine-Tuning Encourages Hallucinations and How to Fix It** [[paper](https://arxiv.org/abs/2604.15574)]
- [2026] **Unmasking Hallucinations: A Causal Graph-Attention Perspective on Factual Reliability in Large Language Models** [[paper](https://arxiv.org/abs/2604.04020)]
- [2026] **SLM Finetuning for Natural Language to Domain Specific Code Generation in Production** [[paper](https://arxiv.org/abs/2604.09952)]
- [2026] **Thinking to Recall: How Reasoning Unlocks Parametric Knowledge in LLMs** [[paper](https://arxiv.org/abs/2603.09906)]
- [2026] **MARCH: Multi-Agent Reinforced Self-Check for LLM Hallucination** [[paper](https://arxiv.org/abs/2603.24579)] [[code](https://github.com/Qwen-Applications/MARCH)]
- [2026] **Identifying, Explaining, and Correcting Ableist Language with AI** [[paper](https://arxiv.org/abs/2602.19560)]
- [2026] **Fine-Refine: Iterative Fine-grained Refinement for Mitigating Dialogue Hallucination** [[paper](https://arxiv.org/abs/2602.15509)]
- [2026] **Benchmarking Vision-Language Models for French PDF-to-Markdown Conversion** [[paper](https://arxiv.org/abs/2602.11960)]
- [2026] **Small Updates, Big Doubts: Does Parameter-Efficient Fine-tuning Enhance Hallucination Detection ?** [[paper](https://arxiv.org/abs/2602.11166)]
- [2026] **Reducing Hallucinations in LLMs via Factuality-Aware Preference Learning** [[paper](https://arxiv.org/abs/2601.03027)]
- [2026] **DHI: Leveraging Diverse Hallucination Induction for Enhanced Contrastive Factuality Control in Large Language Models** [[paper](https://arxiv.org/abs/2601.01156)]
- [2026] **AdversaRiskQA: An Adversarial Factuality Benchmark for High-Risk Domains** [[paper](https://arxiv.org/abs/2601.15511)]

##### 2025

- [2025] **LMSpell: Neural Spell Checking for Low-Resource Languages** [[paper](https://arxiv.org/abs/2512.05414)]
- [2025] **Does Less Hallucination Mean Less Creativity? An Empirical Investigation in LLMs** [[paper](https://arxiv.org/abs/2512.11509)]
- [2025] **Beyond Likelihood: A Causal Framework for Interpretable and Controllable Decoding** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17798324)]
- [2025] **BHRAM-IL: A Benchmark for Hallucination Recognition and Assessment in Multiple Indian Languages** [[paper](https://arxiv.org/abs/2512.01852)] [[code](https://github.com/sambhashana/BHRAM-IL)] [[project](https://huggingface.co/datasets/sambhashana/BHRAM-IL/)]
- [2025] **Consistency Is the Key: Detecting Hallucinations in LLM Generated Text By Checking Inconsistencies About Key Facts** [[paper](https://arxiv.org/abs/2511.12236)]
- [2025] **VISTA: Verification In Sequential Turn-based Assessment** [[paper](https://arxiv.org/abs/2510.27052)]
- [2025] **Train for Truth, Keep the Skills: Binary Retrieval-Augmented Reward Mitigates Hallucinations** [[paper](https://arxiv.org/abs/2510.17733)]
- [2025] **The Geometry of Truth: Layer-wise Semantic Dynamics for Hallucination Detection in Large Language Models** [[paper](https://arxiv.org/abs/2510.04933)]
- [2025] **Do LLMs Really Know What They Don't Know? Internal States Mainly Reflect Knowledge Recall Rather Than Truthfulness** [[paper](https://arxiv.org/abs/2510.09033)]
- [2025] **BitMar: Low-Bit Multimodal Fusion with Episodic Memory for Edge Devices** [[paper](https://arxiv.org/abs/2510.10560)]
- [2025] **Black-Box Hallucination Detection via Consistency Under the Uncertain Expression** [[paper](https://arxiv.org/abs/2509.21999)]
- [2025] **Beyond Accuracy: Rethinking Hallucination and Regulatory Response in Generative AI** [[paper](https://arxiv.org/abs/2509.13345)]
- [2025] **Learning to Reason for Factuality** [[paper](https://arxiv.org/abs/2508.05618)]
- [2025] **Counterfactual Probing for Hallucination Detection and Mitigation in Large Language Models** [[paper](https://arxiv.org/abs/2508.01862)]
- [2025] **The Curious Case of Factuality Finetuning: Models' Internal Beliefs Can Improve Factuality** [[paper](https://arxiv.org/abs/2507.08371)]
- [2025] **Investigating Hallucination in Conversations for Low Resource Languages** [[paper](https://arxiv.org/abs/2507.22720)]
- [2025] **FECT: Factuality Evaluation of Interpretive AI-Generated Claims in Contact Center Conversation Transcripts** [[paper](https://arxiv.org/abs/2508.00889)]
- [2025] **CX-Mind: A Pioneering Multimodal Large Language Model for Interleaved Reasoning in Chest X-ray via Curriculum-Guided Reinforcement Learning** [[paper](https://arxiv.org/abs/2508.03733)]
- [2025] **Revisit What You See: Revealing Visual Semantics in Vision Tokens to Guide LVLM Decoding** [[paper](https://arxiv.org/abs/2506.09522)]
- [2025] **KnowRL: Exploring Knowledgeable Reinforcement Learning for Factuality** [[paper](https://arxiv.org/abs/2506.19807)] [[code](https://github.com/zjunlp/KnowRL)]
- [2025] **COIN: Uncertainty-Guarding Selective Question Answering for Foundation Models with Provable Risk Guarantees** [[paper](https://arxiv.org/abs/2506.20178)]
- [2025] **Reasoning Models Hallucinate More: Factuality-Aware Reinforcement Learning for Large Reasoning Models** [[paper](https://arxiv.org/abs/2505.24630)]
- [2025] **Learning Auxiliary Tasks Improves Reference-Free Hallucination Detection in Open-Domain Long-Form Generation** [[paper](https://arxiv.org/abs/2505.12265)]
- [2025] **InFact: Informativeness Alignment for Improved LLM Factuality** [[paper](https://arxiv.org/abs/2505.20487)]
- [2025] **Faithfulness-Aware Uncertainty Quantification for Fact-Checking the Output of Retrieval Augmented Generation** [[paper](https://arxiv.org/abs/2505.21072)]
- [2025] **Are Reasoning Models More Prone to Hallucination?** [[paper](https://arxiv.org/abs/2505.23646)]
- [2025] **Active Layer-Contrastive Decoding Reduces Hallucination in Large Language Model Generation** [[paper](https://arxiv.org/abs/2505.23657)]
- [2025] **Spark: A System for Scientifically Creative Idea Generation** [[paper](https://arxiv.org/abs/2504.20090)]
- [2025] **HalluLens: LLM Hallucination Benchmark** [[paper](https://arxiv.org/abs/2504.17550)]
- [2025] **Don't Let It Hallucinate: Premise Verification via Retrieval-Augmented Logical Reasoning** [[paper](https://arxiv.org/abs/2504.06438)]
- [2025] **Mask-DPO: Generalizable Fine-grained Factuality Alignment of LLMs** [[paper](https://arxiv.org/abs/2503.02846)]
- [2025] **HalluVerse25: Fine-grained Multilingual Benchmark Dataset for LLM Hallucinations** [[paper](https://arxiv.org/abs/2503.07833)]
- [2025] **HICD: Hallucination-Inducing via Attention Dispersion for Contrastive Decoding to Mitigate Hallucinations in Large Language Models** [[paper](https://arxiv.org/abs/2503.12908)]
- [2025] **FactSelfCheck: Fact-Level Black-Box Hallucination Detection for LLMs** [[paper](https://arxiv.org/abs/2503.17229)]
- [2025] **Towards Conditioning Clinical Text Generation for User Control** [[paper](https://arxiv.org/abs/2502.17571)]
- [2025] **The Law of Knowledge Overshadowing: Towards Understanding, Predicting, and Preventing LLM Hallucination** [[paper](https://arxiv.org/abs/2502.16143)]
- [2025] **Improve Decoding Factuality by Token-wise Cross Layer Entropy of Large Language Models** [[paper](https://arxiv.org/abs/2502.03199)]
- [2025] **RAG-Check: Evaluating Multimodal Retrieval Augmented Generation Performance** [[paper](https://arxiv.org/abs/2501.03995)]

##### 2024

- [2024] **FactTest: Factuality Testing in Large Language Models with Finite-Sample and Distribution-Free Guarantees** [[paper](https://arxiv.org/abs/2411.02603)]
- [2024] **OMCAT: Omni Context Aware Transformer** [[paper](https://arxiv.org/abs/2410.12109)]
- [2024] **Medico: Towards Hallucination Detection and Correction with Multi-source Evidence Fusion** [[paper](https://arxiv.org/abs/2410.10408)]
- [2024] **Hallucination Detox: Sensitivity Dropout (SenD) for Large Language Model Training** [[paper](https://arxiv.org/abs/2410.15460)]
- [2024] **FactBench: A Dynamic Benchmark for In-the-Wild Language Model Factuality Evaluation** [[paper](https://arxiv.org/abs/2410.22257)]
- [2024] **Controlled Automatic Task-Specific Synthetic Data Generation for Hallucination Detection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.12278)]
- [2024] **LLM Hallucinations in Practical Code Generation: Phenomena, Mechanism, and Mitigation** [[paper](https://arxiv.org/abs/2409.20550)] [[code](https://github.com/DeepSoftwareAnalytics/LLMCodingHallucination)]
- [2024] **WildHallucinations: Evaluating Long-form Factuality in LLMs with Real-World Entity Queries** [[paper](https://arxiv.org/abs/2407.17468)]
- [2024] **MAVEN-Fact: A Large-scale Event Factuality Detection Dataset** [[paper](https://arxiv.org/abs/2407.15352)] [[code](https://github.com/lcy2723/MAVEN-FACT)]
- [2024] **REAL Sampling: Boosting Factuality and Diversity of Open-Ended Generation via Asymptotic Entropy** [[paper](https://arxiv.org/abs/2406.07735)]
- [2024] **HalluDial: A Large-Scale Benchmark for Automatic Dialogue-Level Hallucination Evaluation** [[paper](https://arxiv.org/abs/2406.07070)] [[code](https://github.com/FlagOpen/HalluDial)]
- [2024] **Beyond Under-Alignment: Atomic Preference Enhanced Factuality Tuning for Large Language Models** [[paper](https://arxiv.org/abs/2406.12416)]
- [2024] **FLAME: Factuality-Aware Alignment for Large Language Models** [[paper](https://arxiv.org/abs/2405.01525)]
- [2024] **The Hallucinations Leaderboard -- An Open Effort to Measure Hallucinations in Large Language Models** [[paper](https://arxiv.org/abs/2404.05904)]
- [2024] **SERPENT-VLM : Self-Refining Radiology Report Generation Using Vision Language Models** *NAACL 2024* [[paper](https://arxiv.org/abs/2404.17912)]
- [2024] **Retrieval Augmented Generation for Domain-specific Question Answering** [[paper](https://arxiv.org/abs/2404.14760)]
- [2024] **CodeHalu: Investigating Code Hallucinations in LLMs via Execution-based Verification** [[paper](https://arxiv.org/abs/2405.00253)] [[code](https://github.com/yuchen814/CodeHalu)]
- [2024] **Improving Attributed Text Generation of Large Language Models via Preference Learning** [[paper](https://arxiv.org/abs/2403.18381)]
- [2024] **FACTOID: FACtual enTailment fOr hallucInation Detection** [[paper](https://arxiv.org/abs/2403.19113)]
- [2024] **DiaHalu: A Dialogue-level Hallucination Evaluation Benchmark for Large Language Models** [[paper](https://arxiv.org/abs/2403.00896)]
- [2024] **Self-Alignment for Factuality: Mitigating Hallucinations in LLMs via Self-Evaluation** [[paper](https://arxiv.org/abs/2402.09267)]
- [2024] **Comparing Hallucination Detection Metrics for Multilingual Generation** [[paper](https://arxiv.org/abs/2402.10496)]
- [2024] **Hallucination Detection and Hallucination Mitigation: An Investigation** [[paper](https://arxiv.org/abs/2401.08358)]

##### 2023

- [2023] **Do Androids Know They're Only Dreaming of Electric Sheep?** [[paper](https://arxiv.org/abs/2312.17249)]
- [2023] **Alleviating Hallucinations of Large Language Models through Induced Hallucinations** [[paper](https://arxiv.org/abs/2312.15710)]
- [2023] **Successor Features for Efficient Multisubject Controlled Text Generation** [[paper](https://arxiv.org/abs/2311.04921)]
- [2023] **Multitask Multimodal Prompted Training for Interactive Embodied Task Completion** [[paper](https://arxiv.org/abs/2311.04067)]
- [2023] **Mitigating Large Language Model Hallucinations via Autonomous Knowledge Graph-based Retrofitting** [[paper](https://arxiv.org/abs/2311.13314)]
- [2023] **Are Large Language Models Reliable Judges? A Study on the Factuality Evaluation Capabilities of LLMs** *EMNLP 2023* [[paper](https://arxiv.org/abs/2311.00681)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2026

- [2026] **Bridging human judgment and AI precision: a step toward intercultural competence in text refinement** *Humanities and Social Sciences Communications* [[paper](https://doi.org/10.1057/s41599-026-06593-6)]
- [2026] **Human-Aligned Procedural Level Generation Reinforcement Learning via Text-Level-Sketch Shared Representation** *IEEE Transactions on Games* [[paper](https://arxiv.org/abs/2508.09860)]

##### 2025

- [2025] **A semi supervised framework for human and machine collaboration in computer assisted text refinement** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-10085-z)]
- [2025] **T2VTextBench: A Human Evaluation Benchmark for Textual Control in Video Generation Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.04946)]

##### 2024

- [2024] **ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.04324)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Non-Photorealistic Depictions of Gloss in Diverse Artistic Styles** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21787560)]
- [2026] **Enhanced Cross-Modal Attention Control for AIGC-Driven Artistic Image Generation** *International Journal of Pattern Recognition and Artificial Intelligence* [[paper](https://doi.org/10.1142/s0218001426400495)]
- [2026] **TextSLIP: Text Self-Supervised CLIP for Medical Report Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.21970)]
- [2026] **Disco-LoRA: Disentangled Composition of Content, Style, and Motion for Multi-concept Video Customization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.26668)]
- [2026] **StyleText: A Large-Scale Dataset and Benchmark for Stylized Scene Text Inpainting** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.17309)]
- [2026] **Generation of Dunhuang Murals Using Emotion Vectors and Style Matrix Control** *International Journal of Computational Intelligence Systems* [[paper](https://doi.org/10.1007/s44196-026-01346-4)]
- [2026] **Controllable Symbolic Music Generation via Stage-Aware Style Routing and Differentiable Melody Regularization** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202604.0984.v1)]
- [2026] **InnoAds-Composer: Efficient Condition Composition for E-Commerce Poster Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.05898)]
- [2026] **best ai ai tool for art generation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18724152)]
- [2026] **ALIVE: Animate Your World with Lifelike Audio-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.08682)]
- [2026] **MulSMo: Multimodal Stylized Motion Generation by Bidirectional Control Flow.** *PubMed* [[paper](https://pubmed.ncbi.nlm.nih.gov/42579591)]
- [2026] **MulSMo: Multimodal Stylized Motion Generation by Bidirectional Control Flow** *IEEE Transactions on Image Processing* [[paper](https://arxiv.org/abs/2412.09901)]
- [2026] **A Review of Artistic Image Generation and Evaluation: Models, Metrics, and Applications** *KSII Transactions on Internet and Information Systems* [[paper](https://doi.org/10.3837/tiis.2026.01.002)]

##### 2025

- [2025] **PhyCustom: Towards Realistic Physical Customization in Text-to-Image Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.02794)]
- [2025] **InfiniHuman: Realistic 3D Human Creation with Precise Control** [[paper](https://arxiv.org/abs/2510.11650)]
- [2025] **CLUE: Controllable Latent space of Unprompted Embeddings for Diversity Management in Text-to-Image Synthesis** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2511.10993)]
- [2025] **Image Generation Based on Image Style Extraction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2510.01347)]
- [2025] **DiFusion: Flexible Stylized Motion Generation Using Digest-and-Fusion Scheme** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2025.3620400)]
- [2025] **Semantically Consistent Text-to-Motion with Unsupervised Styles** [[paper](https://doi.org/10.1145/3721238.3730641)]
- [2025] **ADAPTATION OF TEXT GENERATION STYLE TO A SPECIFIC AUDIENCE OR CONTENT** *Herald of Kazakh-British technical university* [[paper](https://doi.org/10.55452/1998-6688-2025-22-2-141-154)]
- [2025] **A novel flexible identity-net with diffusion models for painting-style generation** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-12434-4)]
- [2025] **OpenDance: Multimodal Controllable 3D Dance Generation with Large-scale Internet Data** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.07565)]
- [2025] **Disentangling 3D from Large Vision-Language Models for Controlled Portrait Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.14015)]
- [2025] **Comparative Evaluation of Expressive Japanese Character Text-to-Speech with VITS and Style-BERT-VITS2** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.17320)]
- [2025] **DMM: Building a Versatile Image Generation Model via Distillation-Based Model Merging** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.12364)]
- [2025] **POSTA: A Go-to Framework for Customized Artistic Poster Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.14908)]
- [2025] **ACMo: Attribute Controllable Motion Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.11038)]
- [2025] **SnapMoGen: Human Motion Generation from Expressive Texts** [[paper](https://arxiv.org/abs/2507.09122)]
- [2025] **FleSpeech: Flexibly Controllable Speech Generation with Various Prompts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.04644)]
- [2025] **FillerSpeech: Towards Human-Like Text-to-Speech Synthesis with Filler Insertion and Filler Style Control** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.1730)]

##### 2024

- [2024] **StyleCrafter: Taming Artistic Video Diffusion with Reference-Augmented Adapter Learning** *ACM Transactions on Graphics* [[paper](https://doi.org/10.1145/3687975)]
- [2024] **Opt-In Art: Learning Art Styles Only from Few Examples** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.00176)]
- [2024] **Universal Fingerprint Generation: Controllable Diffusion Model With Multimodal Conditions** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2024.3486179)]
- [2024] **JoyType: A Robust Design for Multilingual Visual Text Creation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.17524)]
- [2024] **MMTryon: Multi-Modal Multi-Reference Control for High-Quality Fashion Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.00448)]
- [2024] **Text-to-Song: Towards Controllable Music Generation Incorporating Vocals and Accompaniment** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.09313)]
- [2024] **ConCLVD: Controllable Chinese Landscape Video Generation via Diffusion Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.12903)]
- [2024] **Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i5.28313)]
- [2024] **ExpCLIP: Bridging Text and Facial Expressions via Semantic Alignment** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i7.28594)]
- [2024] **Text2Avatar: Text to 3D Human Avatar Generation with Codebook-Driven Body Controllable Attribute** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.00711)]
- [2024] **Text Semantics to Image Generation: A Method of Building Facades Design Base on Stable Diffusion Model** *Computational design and robotic fabrication* [[paper](https://doi.org/10.1007/978-981-99-8405-3_3)]

##### 2023

- [2023] **StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.00330)]
- [2023] **Music ControlNet: Multiple Time-varying Controls for Music Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.07069)]
- [2023] **Controlled Text Generation via Language Model Arithmetic** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.14479)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2025

- [2025] **Evaluating AI-Generated Podcasts Versus Traditional Reading for Learning From Medical Articles: Protocol for a Mixed-Design Study Among Resident Physicians** *JMIR Research Protocols* [[paper](https://doi.org/10.2196/78505)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Preregistered Somatic-Marker Ablation in a Persistent Bio-Inspired Agent Substrate: A Negative Result on the Verbal-Output Axis** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21218491)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2026

- [2026] **Artistic Creation Inspiration Generation System Based on Diffusion Model** *Advanced Electromagnetics* [[paper](https://doi.org/10.7716/aem.v15i3.3124)]
- [2026] **MULTI-CONDITIONAL LATENT DIFFUSION FOR SKETCH-TEXT-GUIDED FASHION GARMENT GENERATION** [[paper](https://doi.org/10.1145/3830911.3830931)]

##### 2025

- [2025] **An end-to-end multifunctional AI platform for intraoperative diagnosis** *npj Digital Medicine* [[paper](https://doi.org/10.1038/s41746-025-01808-7)]

##### 2024

- [2024] **A Survey on Human Motion Generation Tasks: Consistency, Diversity, and Customization** [[paper](https://doi.org/10.1109/ceii65291.2024.00059)]
- [2024] **FreeMotion: MoCap-Free Human Motion Synthesis with Multimodal Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-73337-6_23)]
- [2024] **Control With Style: Style Embedding-Based Variational Autoencoder for Controlled Stylized Caption Generation Framework** *IEEE Transactions on Cognitive and Developmental Systems* [[paper](https://doi.org/10.1109/tcds.2024.3405573)]

##### 2023

- [2023] **Plugging Stylized Controls in Open-Stylized Image Captioning** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-99-8429-9_25)]
- [2023] **AvatarStudio: High-fidelity and Animatable 3D Avatar Creation from Text** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.17917)]

[⬆ Back to top](#paper-list)

### Writing Applications

#### LLM Evaluation

##### 2026

- [2026] **Information literacy in research training in virtual postgraduate programs** *Communications of International Proceedings* [[paper](https://doi.org/10.5171/2026.4715826)]
- [2026] **Do AI Models Speak Human?** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22159494)]
- [2026] **AcdaLink: Enhanced Android Project Repository with AI Detection Similarity Matching, and Assistant Support** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-31526-7_9)]
- [2026] **Ethical Commitment in Generative AI: Examine the Influence on the Quality of Graduate Academic Research** *International Journal of Computer Information Systems and Industrial Management Applications* [[paper](https://doi.org/10.70917/ijcisim-2026-3486)]
- [2026] **Penguatan Literasi Digital melalui Gen-AI Writing Assistant–Integrated Digital Writing Platform Menuju Indonesia Emas 2045 pada Siswa SMA Kota Cirebon** *Prima Abdika Jurnal Pengabdian Masyarakat* [[paper](https://doi.org/10.37478/abdika.v6i2.8369)]
- [2026] **Analisis Penerimaan Teknologi AI pada Mahasiswa** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20645433)]
- [2026] **AI Tools and Academic Integrity in Postgraduate Research: Addressing Opportunities, Boundaries, and Ethical Frameworks** *Science Journal of Education* [[paper](https://doi.org/10.11648/j.sjedu.20261403.14)]
- [2026] **Generative AI use in instructor-assigned learning activities among nursing students: A cross-sectional survey of perceptions, ethical awareness, faculty restrictions, and continuance intention** *Nurse Education Today* [[paper](https://doi.org/10.1016/j.nedt.2026.107162)]
- [2026] **Generative AI and Adaptive Systems for Customising Help-Seeking Scaffolds: A Systematic Review** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9471902/v1)]
- [2026] **EduBot: AI-Powered Virtual Assistant for Enhanced Student Support and Productivity** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.80445)]
- [2026] **Large Language Models for manufacturing** *Journal of Manufacturing Systems* [[paper](https://doi.org/10.1016/j.jmsy.2026.02.014)]
- [2026] **Ethical, Pedagogical, and Linguistic Implications of Using AI Tools in English Language and Literature Education** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18873938)]
- [2026] **Artificial intelligence-based writing tools in education: Impacts on students’ academic ethics, learning performance, and skill development** *International Journal of Applied Resilience and Sustainability* [[paper](https://doi.org/10.70593/deepsci.0202029)]
- [2026] **Impact of Artificial Intelligence Tools on Learning Motivation in University EMI Courses: A Network Meta-Analysis** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8857786/v1)]
- [2026] **The Myth of the Lone Author: AI as the Latest Member of a Long Line of Invisible Collaborators** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7010238)]
- [2026] **Generative AI in Legal Education: A Targeted Literature Review of Legal Reasoning, Legal Writing, and Instructional Design Safeguards** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7271161)]
- [2026] **Dr. Skynet, Ph.D.: AI Can Now Produce Science Papers by Itself -What Does This Mean for The Future of Research?** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6717418)]
- [2026] **Contributors** *Design Issues* [[paper](https://doi.org/10.1162/desi.x.730)]
- [2026] **CSLLM: Code-Specific Large Language Models—A Survey** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2025.130991)]
- [2026] **AI and Scholarly Evolution** [[paper](https://doi.org/10.1007/978-3-032-23069-0_7)]
- [2026] **A Scientometric Analysis of Generative AI in the Educational Context** [[paper](https://doi.org/10.1007/978-981-95-4871-2_18)]

##### 2025

- [2025] **THE FUTURE OF HIGHER EDUCATION IN THE AGE OF AI** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17924135)]
- [2025] **NL2ACSL : Interactively translating natural language to ANSI C specification language with large language models** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2025.115177)]
- [2025] **Empirical studies of parameter efficient methods for large language models of code and knowledge transfer to R** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-025-10740-z)]
- [2025] **Evaluating and improving LLM-based competitive program generation** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2025.107977)]
- [2025] **Patterns of ChatGPT Use and Attitudes Toward AI in Medical Education: Findings From a Cross-Sectional Survey** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-7674476/v1)]
- [2025] **Integration of AI Code-Writing Assistants in IT Higher Education** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-07989-3_4)]
- [2025] **Comprehending C codes with LLMs: Effective comment generation through retrieval and reasoning** *Pattern Recognition Letters* [[paper](https://doi.org/10.1016/j.patrec.2025.10.007)]
- [2025] **Artificial Intelligence** *Proceedings of the ALISE Annual Conference* [[paper](https://doi.org/10.21900/j.alise.2025.1938)]
- [2025] **Dictionaries Embedded: Writing Assistants and Other Tools** *Elsevier eBooks* [[paper](https://www.sciencedirect.com/science/article/pii/B9780323955041008760/pdf)]
- [2025] **Large Language Models in Code Co-generation for Safe Autonomous Vehicles** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-01241-8_13)]
- [2025] **Comparing human versus artificial intelligence for health literacy among patients with neurological disorders (HANDs study)** *Journal of Neurology* [[paper](https://doi.org/10.1007/s00415-025-13305-8)]
- [2025] **Education in AI ERA: The extent of higher education students' use of ChatGPT in Oman** *International Journal of Innovative Research and Scientific Studies* [[paper](https://doi.org/10.53894/ijirss.v8i4.8384)]
- [2025] **A Inteligência Artificial Generativa no Ecossistema Acadêmico: Uma Análise de Aplicações, Desafios e Oportunidades para a Pesquisa, o Ensino e a Divulgação Científica** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.03106)]
- [2025] **From Human Hands to Algorithmic Minds: WHATIF Machines Become Collaborators in Artistic Creation?** *The Open Review* [[paper](https://doi.org/10.47967/tor10fn9s)]
- [2025] **VeCoGen: Automating Generation of Formally Verified C Code With Large Language Models** [[paper](https://doi.org/10.1109/formalise66629.2025.00017)]
- [2025] **Use of Artificial Intelligence in Scientific Writing.** *PubMed* [[paper](https://pubmed.ncbi.nlm.nih.gov/40160084)]
- [2025] **Smart contract generation model based on code annotation and AST-LSTM tuning** *The Journal of Supercomputing* [[paper](https://doi.org/10.1007/s11227-025-07186-x)]
- [2025] **Perceptions and Utilization of Artificial Intelligence in Manuscript Writing: A Cross-Sectional Survey in Health Care Academics** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-5518955/v1)]
- [2025] **Influence of boundary condition variations on magnetohydrodynamics natural convection and entropy generation in a ternary nanofluid filled-square cavity with elliptic cylinder** *Physics of Fluids* [[paper](https://doi.org/10.1063/5.0269514)]
- [2025] **Acceptance Test Generation with Large Language Models: An Industrial Case Study** [[paper](https://arxiv.org/abs/2504.07244)]
- [2025] **Generation of Robot Manipulation Plans Using Generative Large Language Models** *International Journal of Semantic Computing* [[paper](https://doi.org/10.1142/s1793351x25410041)]
- [2025] **Bugs in large language models generated code: an empirical study** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-025-10614-4)]
- [2025] **BugSpotter: Automated Generation of Code Debugging Exercises** [[paper](https://doi.org/10.1145/3641554.3701974)]
- [2025] **cAST: Enhancing Code Retrieval-Augmented Generation with Structural Chunking via Abstract Syntax Tree** [[paper](https://doi.org/10.18653/v1/2025.findings-emnlp.430)]
- [2025] **When Chatgpt Meets Deepseek!** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5388472)]
- [2025] **Using AI Applications to Enhance EFL Students’ Writing Skills: Empirical Evidence from “Monica”** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5968394)]
- [2025] **THE IMPACT OF ARTIFICIAL INTELLIGENCE ON TEACHING WRITTEN LANGUAGE TO UNIVERSITY STUDENTS** *Innovate Pedagogy* [[paper](https://doi.org/10.32782/2663-6085/2025/83.1.2)]
- [2025] **Large Language Model Agents** [[paper](https://doi.org/10.1007/978-3-031-92285-5_8)]
- [2025] **Efficacy of Various Large Language Models in Generating Smart Contracts** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-031-85363-0_31)]
- [2025] **Automatic Generation of Loop Invariants in Dafny with Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-87054-5_10)]

##### 2024

- [2024] **Static Program Analysis Guided LLM Based Unit Test Generation** [[paper](https://doi.org/10.1145/3703323.3703742)]
- [2024] **Remembering Anand Jayprakash Vaidya** *Sophia* [[paper](https://doi.org/10.1007/s11841-024-01055-5)]
- [2024] **LLM-based Interactive Code Generation: Empirical Evaluation** [[paper](https://doi.org/10.1109/ispras64596.2024.10899123)]
- [2024] **Digital technology-based vocabulary learning for efl students with different learning styles** *Walisongo Repository (Walisongo State Islamic University)* [[paper](https://eprints.walisongo.ac.id/id/eprint/30160/1/2103046113%20-%20SRI%20WAHYUNINGSIH.pdf)]
- [2024] **The Role of Artificial Intelligence in Scientific Writing** *International Journal of Science and Healthcare Research* [[paper](https://doi.org/10.52403/ijshr.20240421)]
- [2024] **Embracing AI Assistants: Unraveling Young Researchers’ Journey with ChatGPT in Science Education Thesis Writing** *International Journal of Artificial Intelligence in Education* [[paper](https://doi.org/10.1007/s40593-024-00438-6)]
- [2024] **OpenSBLI v3.0: High-fidelity multi-block transonic aerofoil CFD simulations using domain specific languages on GPUs** *Computer Physics Communications* [[paper](https://doi.org/10.1016/j.cpc.2024.109406)]
- [2024] **Benchmarking Large Language Models for Ethereum Smart Contract Development** [[paper](https://doi.org/10.1109/brains63024.2024.10732686)]
- [2024] **Video Question Answering with Procedural Programs** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-72920-1_18)]
- [2024] **Large language model evaluation for high‐performance computing software development** *Concurrency and Computation Practice and Experience* [[paper](https://doi.org/10.1002/cpe.8269)]
- [2024] **Cross-Language Code Development with Generative AI: A Source-to-Source Translation Perspective** [[paper](https://doi.org/10.1109/iceict61637.2024.10671366)]
- [2024] **AutoFlow: Automated Workflow Generation for Large Language Model Agents** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.12821)]
- [2024] **Confix: Combining node-level fix templates and masked language model for automatic program repair** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2024.112116)]
- [2024] **“No Free Lunch” when using Large Language Models to Verify Self-Generated Programs** [[paper](https://doi.org/10.1109/icstw60967.2024.00018)]
- [2024] **Training Large Language Models for System-Level Test Program Generation Targeting Non-functional Properties** [[paper](https://doi.org/10.1109/ets61313.2024.10567741)]
- [2024] **LLM4VV: Developing LLM-driven testsuite for compiler validation** *Future Generation Computer Systems* [[paper](https://doi.org/10.1016/j.future.2024.05.034)]
- [2024] **Artificial Intelligence to Automate Health Economic Modelling: A Case Study to Evaluate the Potential Application of Large Language Models** *PharmacoEconomics - Open* [[paper](https://doi.org/10.1007/s41669-024-00477-8)]
- [2024] **The Role of AI Language Assistants in Dialogic Education for Collective Intelligence** *Intelligent systems reference library* [[paper](https://doi.org/10.1007/978-3-031-71232-6_7)]
- [2024] **Smart Contract Generation through NLP and Blockchain for Legal Documents** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2024.04.238)]
- [2024] **ScholarGPT: Fine-Tuning Large Language Models for Discipline-Specific Academic Paper Writing** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5040003)]
- [2024] **Leveraging error-assisted fine-tuning large language models for manufacturing excellence** *Robotics and Computer-Integrated Manufacturing* [[paper](https://doi.org/10.1016/j.rcim.2024.102728)]
- [2024] **ChatGPT and Artificial Intelligence in Higher Education: Literature Review Powered by Artificial Intelligence** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-031-62269-4_17)]
- [2024] **An AI-Powered Writing Assistant Using Natural Language Processing Approach** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-981-97-6678-9_4)]
- [2024] **Affordances of Technology-Enhanced Learning in Heritage Tourism—Exploratory Study** *Smart innovation, systems and technologies* [[paper](https://doi.org/10.1007/978-981-97-4954-6_13)]
- [2024] **Advancing Requirements Engineering Through Generative AI: Assessing the Role of LLMs** [[paper](https://doi.org/10.1007/978-3-031-55642-5_6)]

##### 2023

- [2023] **Automatic detection of Feature Envy and Data Class code smells using machine learning** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2023.122855)]
- [2023] **A Flexible FPGA-Based Stochastic Decoder for 5G LDPC Codes** *Electronics* [[paper](https://doi.org/10.3390/electronics12244986)]
- [2023] **Explaining Transformer-based Code Models: What Do They Learn? When They Do Not Work?** [[paper](https://doi.org/10.1109/scam59687.2023.00020)]
- [2023] **An initial investigation of ChatGPT unit test generation capability** [[paper](https://doi.org/10.1145/3624032.3624035)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Using generative AI tools in teaching students programming** *Professional education in the modern world* [[paper](https://doi.org/10.20913/2224-1841-2026-1-7)]
- [2026] **Штучний інтелект змінює все: штучний розум у вищій освіті** *Scientific periodicals of Ukraine* [[paper](https://visnyk-pedagogy.knlu.edu.ua/article/view/358727)]
- [2026] **Code generation with large language models: a survey from neural program synthesis to autonomous software development** *Applied Intelligence* [[paper](https://doi.org/10.1007/s10489-026-07230-0)]
- [2026] **AI changes everything: artificial intelligence in higher education (Українською)** *Vìsnik KNLU Serìâ “Psihologìâ ta pedagogìka” / Visnyk KNLU Series Pedagogy and Psychology* [[paper](https://doi.org/10.32589/2412-9283.43.2025.358727)]
- [2026] **Agents4PLC: Automating Closed-Loop PLC Code Generation and Verification in Industrial Control Systems Using LLM-Based Agents** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2026.3667895)]
- [2026] **COMPARATIVE ANALYSIS OF LLM-BASED AI ASSISTANTS FOR EFL WRITING INSTRUCTION: CHATGPT, CLAUDE, GEMINI, AND DEEPSEEK** *Esteem Journal of English Education Study Programme* [[paper](https://doi.org/10.31851/wdz59c93)]

##### 2025

- [2025] **Tugan.ai Promo Code "HPK90" – Get 90% OFF on Your First Payment** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18013230)]
- [2025] **Do Advanced Language Models Eliminate the Need for Prompt Engineering in Software Engineering?** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3771933)]
- [2025] **A Solver‐Aided Hierarchical Language for LLM‐Driven CAD Design** *Computer Graphics Forum* [[paper](https://doi.org/10.1111/cgf.70250)]
- [2025] **The Impact of Prompt Programming on Function-Level Code Generation** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2025.3587794)]
- [2025] **Automatic Generation of PLC Code Based on Finetuned Large Language Models** [[paper](https://doi.org/10.1109/ieeeconf65522.2025.11136984)]
- [2025] **Do Prompt Patterns Affect Code Quality? A First Empirical Assessment of ChatGPT-Generated Code** [[paper](https://doi.org/10.1145/3756681.3756938)]
- [2025] **The Impact of Generative Artificial Intelligence on University Information Literacy Education: A Systematic Review from Challenges to Changes** *International Journal of Latest Technology in Engineering Management & Applied Science* [[paper](https://doi.org/10.51583/ijltemas.2025.1402004)]
- [2025] **A study on prompt design, advantages and limitations of ChatGPT for deep learning program repair** *Automated Software Engineering* [[paper](https://doi.org/10.1007/s10515-025-00492-x)]
- [2025] **A Survey of Techniques, Key Components, Strategies, Challenges, and Student Perspectives on Prompt Engineering for Large Language Models (LLMs) in Education** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202503.1808.v1)]
- [2025] **WriteFlow : LLM-assisterad målsättning för reflekterande och kritiskt akademiskt skrivande** *Diva portal (Dalarna University Library)* [[paper](https://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-377315)]

##### 2024

- [2024] **Advanced Techniques in Prompt Engineering for Large Language Models: A Comprehensive Study** [[paper](https://doi.org/10.1109/ictbig64922.2024.10911672)]
- [2024] **A Study of Coding Framework Generation by ChatGPT** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2025.18277)]
- [2024] **Understanding Defects in Generated Codes by Language Models** [[paper](https://doi.org/10.1109/cascon62161.2024.10837857)]
- [2024] **AI-Powered Scholar** [[paper](https://dx.doi.org/10.4324/9781032665276)]
- [2024] **Human Evaluation of GPT for Scalable Python Programming Exercise Generation** [[paper](https://doi.org/10.1109/dsaa61799.2024.10722841)]
- [2024] **BuildProg: Program Generation for Testing ML-based Building Load Forecasting models via LLM and Prompt Engineering** [[paper](https://doi.org/10.1145/3671127.3698698)]
- [2024] **CHATGPT IN FOREIGN LANGUAGE TEACHING AND ASSESSMENT: EXPLORING EFL INSTRUCTORS’ EXPERIENCE** *Information Technologies and Learning Tools* [[paper](https://doi.org/10.33407/itlt.v102i4.5716)]
- [2024] **Enhancing Computer Programming Education with LLMs: A Study on Effective Prompt Engineering for Python Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.05437)]
- [2024] **Evaluation of Code Generation for Simulating Participant Behavior in Experience Sampling Method by Iterative In-Context Learning of a Large Language Model** *Proceedings of the ACM on Human-Computer Interaction* [[paper](https://doi.org/10.1145/3661143)]
- [2024] **CoPrompt: Supporting Prompt Sharing and Referring in Collaborative Natural Language Programming** [[paper](https://doi.org/10.1145/3613904.3642212)]
- [2024] **LLM4PLC: Harnessing Large Language Models for Verifiable Programming of PLCs in Industrial Control Systems** [[paper](https://doi.org/10.1145/3639477.3639743)]
- [2024] **AskIt: Unified Programming Interface for Programming with Large Language Models** [[paper](https://doi.org/10.1109/cgo57630.2024.10444830)]
- [2024] **New ChatGPT and AI Tools for Academic Research and Publishing** [[paper](https://dx.doi.org/10.61700/wdf7gomkxo8yh1080)]
- [2024] **Forgetful Large Language Models: Lessons Learned from Using LLMs in Robot Programming** *Proceedings of the AAAI Symposium Series* [[paper](https://doi.org/10.1609/aaaiss.v2i1.27721)]

##### 2023

- [2023] **Unveiling the Potential of Large Language Models in Generating Semantic and Cross-Language Clones** [[paper](https://doi.org/10.1109/iwsc60764.2023.00011)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **Exploring Code Analysis: Zero-Shot Insights on Syntax and Semantics with LLMs** *ACM Transactions on Software Engineering and Methodology* [[paper](https://arxiv.org/abs/2305.12138)]

##### 2025

- [2025] **Evaluating the Reasoning Capabilities of Large Language Models for Medical Coding and Hospital Readmission Risk Stratification: Zero-Shot Prompting Approach** *Journal of Medical Internet Research* [[paper](https://doi.org/10.2196/74142)]
- [2025] **Enhancing Code Generation for Low-Resource Languages: No Silver Bullet** [[paper](https://doi.org/10.1109/icpc66645.2025.00058)]
- [2025] **Large Language Model-Aware In-Context Learning for Code Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3715908)]
- [2025] **Evaluating Tokenizer Adaptation Methods for Large Language Models on Low-Resource Programming Languages** [[paper](https://doi.org/10.18653/v1/2025.acl-srw.57)]

##### 2024

- [2024] **Automated Commit Message Generation With Large Language Models: An Empirical Study and Beyond** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3478317)]
- [2024] **Towards No-Code Programming of Cobots: Experiments with Code Synthesis by Large Code Models for Conversational Programming** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.11041)]
- [2024] **Enhancing Code Translation in Language Models with Few-Shot Learning via Retrieval-Augmented Generation** [[paper](https://doi.org/10.1109/hpec62836.2024.10938485)]
- [2024] **Towards Efficient Fine-Tuning of Language Models With Organizational Data for Automated Software Review** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3428324)]
- [2024] **Self-Planning Code Generation with Large Language Models** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3672456)]
- [2024] **Can We Trust Large Language Models Generated Code? A Framework for In-Context Learning, Security Patterns, and Code Evaluations Across Diverse LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.12513)]
- [2024] **Automated Data Visualization from Natural Language via Large Language Models: An Exploratory Study** *Proceedings of the ACM on Management of Data* [[paper](https://arxiv.org/abs/2404.17136)]
- [2024] **Effective test generation using pre-trained Large Language Models and mutation testing** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2024.107468)]
- [2024] **CodeLMSec Benchmark: Systematically Evaluating and Finding Security Vulnerabilities in Black-Box Code Language Models** [[paper](https://doi.org/10.1109/satml59370.2024.00040)]
- [2024] **Multi-Intent Inline Code Comment Generation via Large Language Model** *International Journal of Software Engineering and Knowledge Engineering* [[paper](https://doi.org/10.1142/s0218194024500050)]
- [2024] **Large Language Models are Few-Shot Summarizers: Multi-Intent Comment Generation via In-Context Learning** [[paper](https://doi.org/10.1145/3597503.3608134)]
- [2024] **Multibody Models Generated from Natural Language** *Multibody System Dynamics* [[paper](https://doi.org/10.1007/s11044-023-09962-0)]
- [2024] **Leveraging Print Debugging to Improve Code Generation in Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.05319)]
- [2024] **A Two-Stage Code Generation Method using Large Language Models** *International Journal of Performability Engineering* [[paper](https://doi.org/10.23940/ijpe.24.07.p6.460467)]

##### 2023

- [2023] **SGLang: Efficient Execution of Structured Language Model Programs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.07104)]
- [2023] **Using Large Language Models for Bug Localization and Fixing** [[paper](https://doi.org/10.1109/icast57874.2023.10359304)]
- [2023] **Improving domain-specific neural code generation with few-shot meta-learning** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2023.107365)]
- [2023] **BookGPT: A General Framework for Book Recommendation Empowered by Large Language Model** *Electronics* [[paper](https://doi.org/10.3390/electronics12224654)]
- [2023] **L2CEval: Evaluating Language-to-Code Generation Capabilities of Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.17446)]
- [2023] **A New Approach to Web Application Security: Utilizing GPT Language Models for Source Code Inspection** *Future Internet* [[paper](https://doi.org/10.3390/fi15100326)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2025

- [2025] **A Comprehensive Study on Code Completion for Large Language Models** [[paper](https://doi.org/10.1109/icaace65325.2025.11020128)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2026

- [2026] **An academic writing assistant system with role-based agents and consistency verification** *DR-NTU (Nanyang Technological University)* [[paper](https://hdl.handle.net/10356/218953)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **Literature, Language, and Artificial Intelligence: Transformation, Creativity and Ethical Challenges in the Digital Age** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21868506)]
- [2026] **THE SYNERGY OF STUDENT CREATIVITY AND ARTIFICIAL INTELLIGENCE IN ENGLISH CREATIVE WRITING: AN ANALYSIS OF THE USE OF AI AS A WRITING ASSISTANT** *Esteem Journal of English Education Study Programme* [[paper](https://doi.org/10.31851/keq3at66)]
- [2026] **Enhancing Writing Quality with AI: A Multi-Model Approach for Grammar, Tone, and Style Optimization** [[paper](https://doi.org/10.1109/i5cps67958.2026.11452396)]
- [2026] **Trophi Ai Promo Code "AKV" Get 20% Off On all Plans** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18400800)]
- [2026] **The Dark Empath's Shadow: creative practice and collaborative screenwriting with AI** *Open Access at Essex (University of Essex)* [[paper](https://doi.org/10.5526/ERR-00042954)]

##### 2025

- [2025] **Playworks: Inclusive Development of New Plays at the Public University** *Theatre and Performance Notes and Counternotes* [[paper](https://doi.org/10.5325/tpnc.2.2.0197)]
- [2025] **Introduction to the Special Issue: Community-Based Language Learning (CBLL) in Korean Language Education** *The Korean Language in America* [[paper](https://doi.org/10.5325/korelangamer.29.2.0121)]
- [2025] **AI Multi-Agent Assistant** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17692280)]
- [2025] **Artificial Intelligence Usage in Students’ Academic Writing: on the Example of the Thesis of the Jurisprudence Section from the Collection of Works** *Artificial Intelligence* [[paper](https://doi.org/10.15407/jai2025.03.023)]
- [2025] **Artificial Intelligence and Education: Preserving Human Agency in a World of Automation** *SBV Journal of Basic Clinical and Applied Health Science* [[paper](https://doi.org/10.4103/sbvj.sbvj_19_25)]
- [2025] **Practical Considerations and Ethical Implications of Using Artificial Intelligence in Writing Scientific Manuscripts** *ACG Case Reports Journal* [[paper](https://doi.org/10.14309/crj.0000000000001629)]
- [2025] **The Advent of Artificial Intelligence and the Death of Narrative Reviews** *Journal of Multidisciplinary Health and Innovative Technology* [[paper](https://doi.org/10.4103/jmhit.jmhit_1_25)]
- [2025] **Metaphysical dialogue with AI (Blueprint B_01) Conferences & Book - written by by Stefano Dorian Franco, 2025, CC4** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.29484287.v2)]
- [2025] **Concept INTRODUCTION # Metaphysical dialogue with AI (Blueprint B_01) Conferences & Book - written by by Stefano Dorian Franco, 2025, CC4** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.29484287.v3)]

##### 2024

- [2024] **Literacy in the Age of AI** *Reading Research Quarterly* [[paper](https://doi.org/10.1002/rrq.581)]
- [2024] **Notes on Contributors** *Poetics Today* [[paper](https://doi.org/10.1215/03335372-11301586)]

##### 2023

- [2023] **Specimen Days** *Resources for American Literary Study* [[paper](https://doi.org/10.5325/resoamerlitestud.45.2.0459)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **Penguatan Literasi Etika Pemanfaatan Artificial Intelligence sebagai Asisten Riset Tanpa Plagiarisme bagi Mahasiswa** *Journal of Science and Social Development* [[paper](https://doi.org/10.55732/jssd.v9i1.2306)]
- [2026] **A Study of the Role of Generative AI Academic Writing Assistants in Enhancing the Efficiency of Academic Research in Business Studies** *Ingegneria Sismica* [[paper](https://doi.org/10.65102/is2026203)]

##### 2025

- [2025] **Verified Logically Promo Code 10SAVE (2025) – Save Extra 10% on AI-Powered Research Workspace** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17549624)]
- [2025] **Logically Promo Code 10SAVE (2025) – Verified Deal for Extra 10% OFF the Unlimited Plan** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17549493)]
- [2025] **Utilizing ChatGPT-4 with Canvas in Health Research Writing: Practical Applications and Ethical Guidelines** *Saudi Journal of Otorhinolaryngology Head and Neck Surgery* [[paper](https://doi.org/10.4103/sjoh.sjoh_8_25)]
- [2025] **Nursing students’ reflections of artificial intelligence use in assessments** *European Journal of Cardiovascular Nursing* [[paper](https://doi.org/10.1093/eurjcn/zvaf150)]
- [2025] **Evaluating quantized Large Language Models for code generation on low-resource language benchmarks** *Journal of Computer Languages* [[paper](https://doi.org/10.1016/j.cola.2025.101351)]
- [2025] **Do Current Language Models Support Code Intelligence for R Programming Language?** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3735635)]
- [2025] **Understanding the Robustness of Transformer-Based Code Intelligence via Code Transformation: Challenges and Opportunities** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3524461)]
- [2025] **Hallucination Detection on Code Generation with SelfCheckGPT** *Journal of Information Processing* [[paper](https://doi.org/10.2197/ipsjjip.33.487)]

##### 2024

- [2024] **The Use and Perceptions Towards AI Tools For Academic Writing Among University Students** *Innovations in Language Teaching Journal* [[paper](https://doi.org/10.53463/innovltej.20240328)]
- [2024] **AI-powered literature search: some observations and concerns** *Khyber Medical University Journal* [[paper](https://doi.org/10.35845/kmuj.2024.23740)]
- [2024] **A REVIEW OF THE INFLUENCE OF ARTIFICIAL INTELLIGENCE IN ACADEMIC WRITING** *Journal of Computer Science and Information Technology* [[paper](https://doi.org/10.70248/jcsit.v2i1.1134)]
- [2024] **A Novel LLM enabled Code Snippet Generation Framework** [[paper](https://doi.org/10.1109/iipem62726.2024.10925748)]
- [2024] **Generative AI: Redefining the Future of Research Publications** *Journal of Indian Academy of Oral Medicine and Radiology* [[paper](https://doi.org/10.4103/jiaomr.jiaomr_360_24)]
- [2024] **On the Effectiveness of Large Language Models in Statement-level Code Summarization** [[paper](https://doi.org/10.1109/qrs62785.2024.00030)]
- [2024] **Evaluating Large Language Models for Real-World Vulnerability Repair in C/C++ Code** [[paper](https://doi.org/10.1145/3643651.3659892)]
- [2024] **The Utilization of Artificial Intelligence (Ai) Writing Assistants to the Writing Proficiency** *International Journal of Research Publications* [[paper](https://doi.org/10.47119/ijrp1001501620246659)]
- [2024] **Interpretable Code Summarization** *IEEE Transactions on Reliability* [[paper](https://doi.org/10.1109/tr.2024.3392876)]
- [2024] **ChatGPT: Challenges and Benefits in Software Programming for Higher Education** *Sustainability* [[paper](https://doi.org/10.3390/su16031245)]
- [2024] **ICE-Score: Instructing Large Language Models to Evaluate Code** [[paper](https://doi.org/10.18653/v1/2024.findings-eacl.148)]

##### 2023

- [2023] **Enhancing code summarization with action word prediction** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2023.126777)]
- [2023] **ChatGPT-3.5 as writing assistance in students’ essays** *Humanities and Social Sciences Communications* [[paper](https://doi.org/10.1057/s41599-023-02269-7)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **The Impact of Generative AI on English Academic Writing, Learner Autonomy and Authorial Voice among ESL Postgraduate Students** *Indus journal of social sciences.* [[paper](https://doi.org/10.59075/ijss.v4i2.2148)]
- [2026] **AI-Powered Academic Integrity Assistant for Detecting Copied & AI-Rephrased Plagiarism** *International Journal of Innovative Science and Research Technology (IJISRT)* [[paper](https://doi.org/10.38124/ijisrt/26apr2482)]
- [2026] **How Much Do Students Use AI on Their Assignments?** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19463017)]
- [2026] **USING CHATGPT AS A WRITING ASSISTANT: BENEFITS AND CHALLENGES FOR EFL STUDENTS AT DONG NAI TECHNOLOGY UNIVERSITY** *Tạp chí Khoa học Trường Đại học Vinh. Series C Khoa học và công nghệ giáo dục* [[paper](https://doi.org/10.56824/vujs.2025c0121c)]
- [2026] **In the room but not on the byline: trust, fear, and the human role in addiction science in the age of AI** *Frontiers in Sociology* [[paper](https://doi.org/10.3389/fsoc.2026.1786377)]
- [2026] **CopySpace AI Discount Code 2026 [techxperio] – 10% OFF All Plans** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18788455)]
- [2026] **Alphana Ai Promo Code : (ARCH30) Get 20% Off On Subscription Plan** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18507987)]
- [2026] **The Vanishing Author: Do Multi-Turn LLM revisions drive scientific writing toward a uniform style?** *Aristotle University of Thessaloniki* [[paper](https://doi.org/10.26262/heal.auth.ir.375923)]
- [2026] **Editorial: Teaching and assessing with AI: teaching ideas, research, and reflections** *Frontiers in Communication* [[paper](https://doi.org/10.3389/fcomm.2025.1769019)]

##### 2025

- [2025] **ChatGPT in the Teaching of Academic Writing in Higher Education: Teachers' Perspectives on Its Uses, Challenges, and Future in Personalized Learning** *Edutec Revista Electrónica de Tecnología Educativa* [[paper](https://doi.org/10.21556/edutec.2025.93.3995)]
- [2025] **Using artificial intelligence technologies to prepare and compose scientific articles** *Informatics and Education* [[paper](https://doi.org/10.32517/0234-0453-2024-39-6-38-52)]

##### 2024

- [2024] **Artificial intelligence: The researcher's assistant or sheep in wolf's clothing?** *United European Gastroenterology Journal* [[paper](https://doi.org/10.1002/ueg2.12689)]
- [2024] **Understanding Translation Students' Use of AI-Powered Tools During Text Revision and Their Impact on Cognitive Load** *Advances in educational technologies and instructional design book series* [[paper](https://doi.org/10.4018/979-8-3693-4310-4.ch010)]
- [2024] **CodeWMBench: An Automated Benchmark for Code Watermarking Evaluation** [[paper](https://doi.org/10.1145/3674399.3674447)]
- [2024] **Ghostwriters in the machine: Openly appreciating AI tools and humans who helped us** *Journal of Organizational Behavior* [[paper](https://doi.org/10.1002/job.2778)]
- [2024] **Incorporating artificial intelligence into student academic writing in higher education:: the use of wordtune by Chinese international students** *Research Explorer (The University of Manchester)* [[paper](https://research.manchester.ac.uk/en/publications/6130c535-1d39-4b0e-a7fa-cb9d3fbf53e5)]
- [2024] **Incorporating Artificial Intelligence into Student Academic Writing in Higher Education: The Use of Wordtune by Chinese international students** *Proceedings of the ... Annual Hawaii International Conference on System Sciences/Proceedings of the Annual Hawaii International Conference on System Sciences* [[paper](https://doi.org/10.24251/hicss.2024.329)]

##### 2023

- [2023] **Writing for Pediatric Critical Care Medicine: Engaging With Citations to References in the Chatbot Generative Pre-Trained Transformer Era** *Pediatric Critical Care Medicine* [[paper](https://doi.org/10.1097/pcc.0000000000003356)]

[⬆ Back to top](#paper-list)

#### Autocomplete

##### 2026

- [2026] **INFLUENCE OF AI-ASSISTED MESSAGING ON STUDENTS’ LANGUAGE SIMPLIFICATION AND DEPENDENCE** *Journal of Applied Linguistics and TESOL (JALT)* [[paper](https://doi.org/10.63878/jalt2311)]

##### 2025

- [2025] **A Review on Vibe Coding: Fundamentals, State-of-the-art, Challenges and Future Directions** [[paper](https://doi.org/10.36227/techrxiv.174681482.27435614/v1)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **University Students' Perceptions and Use of Artificial Intelligence Tools for Academic Activities and Critical Thinking: A Thematic Literature Review with Reflections from Tanzanian Higher Education** *East African Journal of Education Studies* [[paper](https://doi.org/10.37284/eajes.9.3.5472)]
- [2026] **The Benefit of Using AI as an Assistant in Academic Writing** *Universitas Kristen Satya Wacana Institutional Repository (Universitas Kristen Satya Wacana)* [[paper](https://repository.uksw.edu/handle/123456789/41297)]
- [2026] **Examining AI-assisted writing revision through assignment design and implementation in an undergraduate course** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2026.1879758)]
- [2026] **Design and Conceptualization of an Intelligent Model for Self-Guide in Project Writing** *INTERNATIONAL JOURNAL OF COMPUTER SCIENCE AND MATHEMATICAL THEORY E-ISSN* [[paper](https://doi.org/10.56201/ijcsmt.vol.12.no5.2026.pg32.40)]
- [2026] **Assessment of Artificial Intelligence in Students' Research** *JPAIR Institutional Research* [[paper](https://doi.org/10.7719/irj.v27i1.1035)]
- [2026] **The Effects of AI-Supported Translanguaging Practices on Writing Performance and Metacognitive Awareness in English as a Second Language (ESL) Contexts** *Civil War Book Review* [[paper](https://repository.lsu.edu/gradschool_dissertations/7132)]
- [2026] **THE EFFECT OF AI-POWERED WRITING ASSISTANTS ON ESSAY WRITING PERFORMANCE AMONG STUDENTS OF LAGOS STATE COLLEGE OF HEALTH TECHNOLOGY, YABA, LAGOS STATE** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21629041)]
- [2026] **Overreliance on artificial intelligence in academic research: A study of non-native english-speaking students’ experiences in research proposal writing at a South African university** *Multidisciplinary Science Journal* [[paper](https://doi.org/10.31893/multiscience.2027138)]
- [2026] **INTEGRATION OF AI TOOLS INTO THE PROCESS OF TEACHING ACADEMIC WRITING TO STUDENTS: ADVANTAGES, RISKS, AND METHODOLOGICAL ASPECTS (BASED ON THE DigiFLEd PROJECT)** *Вісник науки та освіти* [[paper](https://doi.org/10.52058/2786-6165-2026-5(47)-167-179)]
- [2026] **ENGLISH DEPARTMENT STUDENTS' VOICES ON AI UNDERSTANDING AND USAGE: A STUDY OF AI LITERACY IN A UNIVERSITY SETTING** *Esteem Journal of English Education Study Programme* [[paper](https://doi.org/10.31851/mbd8am55)]
- [2026] **Artificial Intelligence in ESP and EAP Pedagogy : A Scoping Review of Practices, Challenges, and Future Directions** *Jurnal Pendidikan dan Sastra Inggris* [[paper](https://doi.org/10.55606/jupensi.v6i2.7513)]
- [2026] **AI in Spanish Language Learning: Practices, Perceptions, and Ethics among Ghanaian Students** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.32841974.v1)]
- [2026] **The Impact of Artificial Intelligence Writing Tools on English Language Learning and Academic Writing Practices** *Stanzaleaf International Journal of Multidisciplinary Studies* [[paper](https://doi.org/10.67313/slijms.2026.25)]
- [2026] **Linguistic Equity or Forced Assimilation: A Review of How AI Writing Tools Shape the International Student Experience** *International Journal of Innovative Science and Research Technology (IJISRT)* [[paper](https://doi.org/10.38124/ijisrt/26jun849)]
- [2026] **Improving the Academic Writing of Future English Teachers Using The AI-Powered Grammarly Program** *International Journal of Pedagogics* [[paper](https://doi.org/10.37547/ijp/volume06issue06-37)]
- [2026] **Exploring AI-Powered Writing Assistants’ Impact on the Academic Performance: A Case of a South African University** *International Journal of Learning Teaching and Educational Research* [[paper](https://doi.org/10.26803/ijlter.25.6.50)]
- [2026] **Editing Software to Improve the Quality of Students’ Scientific Works** *Buletin Edukasi Indonesia* [[paper](https://doi.org/10.56741/iistr.bei.001851)]
- [2026] **Cross-Cultural Language Processes in Multilingual Academic Writing Challenges and Strategies** *Indian Journal of Information Sources and Services* [[paper](https://doi.org/10.51983/ijiss-2026.16.2.71)]
- [2026] **Artificial Intelligence, Academic Writing and Access to Information among Graduate Students at the University for Development Studies** *Ghana Library Journal* [[paper](https://doi.org/10.65861/glj.v31i1.5)]
- [2026] **ARTIFICIAL INTELLIGENCE TOOLS IN DEVELOPING EFL STUDENTS' ACADEMIC WRITING SKILLS: A CRITICAL REVIEW OF RESEARCH (2022–2025)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20729698)]
- [2026] **ARTIFICIAL INTELLIGENCE AS A RESEARCH ASSISTANT: A FRAMEWORK FOR ETHICAL USE AMONG UNIVERSITY STUDENTS** *International Journal of Progressive Research in Engineering Management and Science* [[paper](https://doi.org/10.58257/ijprems54009)]
- [2026] **INTEGRATING ARTIFICIAL INTELLIGENCE INTO EFL WRITING INSTRUCTION: OPPORTUNITIES AND CHALLENGES** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20440802)]
- [2026] **FORMING ENGLISH WRITTEN COMMUNICATION SKILLS AMONG HIGHER EDUCATION INSTITUTION STUDENTS IN THE CONTEXT OF DIGITALIZED LEARNING** *Тrаnscarpathian Philological Studies* [[paper](https://doi.org/10.32782/tps2663-4880/2026.46.2.16)]
- [2026] **An Intelligent Word Processing Add-in for Real-Time Academic Argument Structure and Tone Enhancement Using NLP and LLMs** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19987133)]
- [2026] **Value and Cost of Using AI-powered Writing Assistants in Academic Writing: Basis for Crafting a Policy Brief** *Journal of Innovative Research* [[paper](https://doi.org/10.54536/jir.v4i1.6746)]
- [2026] **Use of AI Tools in Learning English at Highschool Level; Benefits and Challenges** *Advanced International Journal for Research* [[paper](https://doi.org/10.63363/aijfr.2026.v07i02.5184)]
- [2026] **Students’ Perceptions of the Impact of AI Writing Assistants on English Writing Skills** *Tạp chí Khoa học Ngoại ngữ* [[paper](https://doi.org/10.56844/tckhnn.85.1000)]
- [2026] **Students' Use of Artificial Intelligence in Kazakhstani Universities** *Nazarbayev University Repository (Nazarbayev University)* [[paper](https://nur.nu.edu.kz/handle/123456789/19027)]
- [2026] **Role of AI Tools In Education** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19396392)]
- [2026] **AI-Powered Academic Writing Assistant using NLP and ML as a Microsoft Word Add-in** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19487916)]
- [2026] **THE TENSION BETWEEN EFFICIENCY AND IDENTITY: EXPLORING EFL LEARNERS' AUTHORIAL VOICE IN AI-ASSISTED ACADEMIC WRITING** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18926734)]
- [2026] **Indian women in anaesthesia research: Touching the academic peaks** *Indian Journal of Anaesthesia* [[paper](https://doi.org/10.4103/ija.ija_331_26)]
- [2026] **Edukasi Tools Artificial Intelligences dalam Meningkatkan Kemampuan Dosen untuk Menyusun Artikel Sinta dan Scopus** *Jurnal Pengabdian Masyarakat (abdira)* [[paper](https://doi.org/10.31004/abdira.v6i2.1873)]
- [2026] **Artificial Intelligence in Education Writing Assistance, Tutoring, Creativity, and Ethical Concerns** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/406022)]
- [2026] **Artificial Intelligence (AI) In English Language Education: A Case Study of Chat GPT in Academic Writing Support** *Integrated Journal for Research in Arts and Humanities* [[paper](https://doi.org/10.55544/ijrah.dyparts.22)]
- [2026] **AI-Based Writing Assistants in Higher Education: Impacts on Student Critical Thinking and Academic Integrity** *VFAST Transactions on Education and Social Sciences* [[paper](https://doi.org/10.21015/vtess.v14i1.2396)]
- [2026] **A Study of SQL Programming Learning Assistant System for Novice Learners** *Institutional Repositories DataBase (IRDB)* [[paper](https://ousar.lib.okayama-u.ac.jp/70621)]
- [2026] **📚 Paperpal Coupon Code 2026 [PAP20] – 20% OFF Writing Tools** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18516264)]
- [2026] **Paperpal Coupon Code 2026 [PAP20] – 20% OFF Academic Writing Tools** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18788428)]
- [2026] **AI in Tertiary STEM+E Education: An exploration into current global practices and local insights from Japan** *Institutional Repositories DataBase (IRDB)* [[paper](https://uec.repo.nii.ac.jp/records/2000911)]
- [2026] **"THE IMPACT OF ARTIFICIAL INTELLIGENCE ON ACADEMIC WRITING SKILLS OF EFL STUDENTS"** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18509380)]
- [2026] **The ‘Grammarly Effect’: A Mixed-Methods Study on the Impact of Instantaneous AI Feedback on Student Writing Anxiety and Revision Processes** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-13196-6_19)]
- [2026] **The Editorial Mind – Troubles of a New Age** *Journal of The Indian Academy of Geriatrics* [[paper](https://doi.org/10.4103/jiag.jiag_40_26)]
- [2026] **Peningkatan Kompetensi Pengelolaan Jurnal Ilmiah Bagi Mahasiswa IBI Kesatuan Bogor** *Jurnal Abdimas Dedikasi Kesatuan* [[paper](https://doi.org/10.37641/jadkes.v7i1.4937)]
- [2026] **English Language Learning in the Age of Artificial Intelligence: Future Challenges and Possibilities** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18918959)]

##### 2025

- [2025] **ThinkBox: Integrating generative artificial intelligence into graduate studies in administration: impacts, ethical dilemmas, and methodological paths** *Revista de Gestão* [[paper](https://doi.org/10.1108/rege-10-2025-218)]
- [2025] **Role of artificial intelligence in improving the writing skills of individuals with visual impairment** *Aminu Kano Academic Scholars Association Multidisciplinary Journal* [[paper](https://doi.org/10.64726/6xc9ak16)]
- [2025] **Role of Artificial Intelligence & Social Media in Language Evolution** *Physical Education Health and Social Sciences* [[paper](https://doi.org/10.63163/jpehss.v3i4.928)]
- [2025] **It is not comparable! critically evaluating the role of GenAI/LLMs and educator support in the academic essay writing process** *Interactive Learning Environments* [[paper](https://doi.org/10.1080/10494820.2025.2604259)]
- [2025] **Digital Tools for Academic Writing: A Systematic Analysis of AI and Technology-Enhanced Support** *Türkiye Eğitim Dergisi* [[paper](https://doi.org/10.54979/turkegitimdergisi.1828027)]
- [2025] **Cognitive Scaffolding Through AI Writing Assistants: Mixed Methods Evidence from Arabic Language Education Students** *Uktub Journal of Arabic Studies* [[paper](https://doi.org/10.32678/uktub.v5i2.48)]
- [2025] **Cognitive Offloading: Implications of AI Dependency for Senior High School Learners’ Deep Learning and Retention** *International Multidisciplinary Research Journal* [[paper](https://doi.org/10.54476/ioer-imrj/434379)]
- [2025] **AI in Foreign Language Learning: Changing Usage Practices, Perceptions, and Training Needs among EFL Students** *Boğaziçi Üniversitesi Eğitim Dergisi* [[paper](https://doi.org/10.52597/buje.1687891)]
- [2025] **Using Artificial Intelligence Technology to Improve the Efficiency of the Daily Tasks of Management Assistants in the Faculty of Humanities, University of Kelaniya** [[paper](https://doi.org/10.64920/iprc25071)]
- [2025] **THE ROLE OF DIGITAL TOOLS IN LEARNING ENGLISH WRITING SKILLS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17632028)]
- [2025] **Students’ Perceptions and Digital Literacy Self-Efficacy Toward AI-Based Writing Feedback Systems in English Language Learning** *Education Jurnal Sosial Humaniora dan Pendidikan* [[paper](https://doi.org/10.51903/hj8yv131)]
- [2025] **Hierarchical Syntax-Aware Modeling for Code Generation and Program Repair** [[paper](https://doi.org/10.1109/icairc68035.2025.11385172)]
- [2025] **Editorial: Who is monitoring AI?** *Quarterly review of distance education* [[paper](https://doi.org/10.1108/qrde-10-2025-012)]
- [2025] **Editorial: Fully Compromised, but Thanks All the Same to Our Peer Reviewers** *Clinical Orthopaedics and Related Research* [[paper](https://doi.org/10.1097/corr.0000000000003723)]
- [2025] **E-Battery** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17567337)]
- [2025] **Continuance Intention to Use AI as Writing Assistants Among Indonesian University Students and Its Implications for Academic Literacy** [[paper](https://doi.org/10.1109/iipem65914.2025.11548208)]
- [2025] **AI-Assisted Academic Writing, Plagiarism Detection, and Grammar Enhancement Systems** [[paper](https://doi.org/10.71443/9789349552890-14)]
- [2025] **AI in Academic Writing Pedagogy: Insights from EFL University Instructors** *مجلة صدى الجامعة للعلوم الإنسانية* [[paper](https://doi.org/10.65422/sajh.v3i1.76)]
- [2025] **Examining the Role of AI-Powered Writing Assistants in Enhancing Critical Thinking In EFL Academic Writing** *Journal of Languages and Language Teaching* [[paper](https://doi.org/10.33394/jollt.v13i4.15077)]
- [2025] **Adoption of artificial intelligence in selected nursing schools: A study on higher education in nursing in the Western Province of Sri Lanka** [[paper](https://doi.org/10.66281/70130/8669)]
- [2025] **The Role of Artificial Intelligence in Scientific Writing: A Higher Education Review** *Academic Platform Journal of Engineering and Smart Systems* [[paper](https://doi.org/10.21541/apjess.1676506)]
- [2025] **The Role of AI in Academic Writing: Impacts on Writing Skills, Critical Thinking, and Integrity in Higher Education** *Societies* [[paper](https://doi.org/10.3390/soc15090247)]
- [2025] **Generative AI as an English Writing Aid: Thai University Students’ Perceptions and Experiences with ChatGPT and Gemini** *Suranaree Journal of Social Science* [[paper](https://doi.org/10.55766/sjss279466)]
- [2025] **Experiences of ESL students and instructors using Grammarly in academic writing** *Studies in English Language and Education* [[paper](https://doi.org/10.24815/siele.v12i3.40518)]
- [2025] **CHATGPT IN ACADEMIC WRITING: EFL PRE-SERVICE TEACHERS’ POINTS OF VIEW** *Wiralodra English Journal* [[paper](https://doi.org/10.31943/wej.v9i2.456)]
- [2025] **ANALISIS PEMANFAATAN ARTIFICIAL INTELLIGENCE DALAM PENULISAN KARYA TULIS ILMIAH MAHASISWA TEKNOLOGI PENDIDIKAN** *Repository at Universitas Pendidikan Indonesia (Universitas Pendidikan Indonesia)* [[paper](https://repository.upi.edu/141317/8/S_KTP_2109740_Title.pdf)]
- [2025] **AI-ASSISTED SCHOLARLY WRITING IN APPLIED LINGUISTICS AND LANGUAGE EDUCATION IN KAZAKHSTAN: A SCOPING REVIEW** *Журнал серии «Педагогические науки»* [[paper](https://doi.org/10.48371/peds.2025.78.3.010)]
- [2025] **Publishing Journal Articles: 5 Tips for Success** *Learned Publishing* [[paper](https://doi.org/10.1002/leap.2017)]
- [2025] **Balancing syntactic complexity and clarity: the role of AI in enhancing academic writing proficiency** *Saudi Journal of Language Studies* [[paper](https://doi.org/10.1108/sjls-10-2024-0062)]
- [2025] **The Soul and the Algorithm: Rethinking Peer Review in the Age of Artificial Intelligence** [[paper](https://doi.org/10.22541/au.175192032.21111455/v1)]
- [2025] **Empowering Female Students with AI:Improving Writing Skills in Higher Education** *Journal of English Language Teaching* [[paper](https://doi.org/10.66121/7s222e16)]
- [2025] **CoachGPT: A Scaffolding-based Academic Writing Assistant** [[paper](https://arxiv.org/abs/2506.18149)]
- [2025] **Can NotebookLM Support English Language Learners? A Theoretical Perspective on AI Tools in Education** *Porta Universorum* [[paper](https://doi.org/10.69760/portuni.0106003)]
- [2025] **AI in Higher Education: A Survey of Artificial Intelligence Usage in Students English Academic Writing** *Conference on English Language Teaching* [[paper](https://doi.org/10.24090/celti.2025.1338)]
- [2025] **The Role of Artificial Intelligence in Enhancing Human Longevity** *Golden Ratio of Social Science and Education* [[paper](https://doi.org/10.52970/grsse.v5i2.1275)]
- [2025] **The Impact of Using ChatGPT and Grammarly on developing Iraqi EFL University Students' Academic Essay Writing** *Journal of Misan Researches* [[paper](https://doi.org/10.52834/jmr.v21i41.286)]
- [2025] **Enhancing Academic Writing with AI: A Deep Learning-Based Tool for Emerging Faculty** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20404598)]
- [2025] **Alleviating writing anxiety through Artificial Intelligence: a digital shift in global education** *UiTM Institutional Repositories (Universiti Teknologi MARA)* [[paper](https://ir.uitm.edu.my/id/eprint/119164/1/119164.pdf)]
- [2025] **The Differential Impact of AI Tools Among EFL University Learners: A Process Writing Approach** *International Journal of Learning Teaching and Educational Research* [[paper](https://doi.org/10.26803/ijlter.24.5.24)]
- [2025] **Integrating AI Tools in English Writing Classes to Enhance Student Accuracy and Coherence** *The journal of academic science.* [[paper](https://doi.org/10.59613/vnnrve23)]
- [2025] **Impact of AI-Based Tools on Writing Skills** *Journal of Research in Education* [[paper](https://doi.org/10.3126/jore.v1i1.78725)]
- [2025] **Enhancing Scientific Writing with AI: Tools, Techniques, and Ethical Practices** [[paper](https://doi.org/10.31219/osf.io/xbdrq_v1)]
- [2025] **Utilisation of ChatGPT and other Artificial Intelligence tools among medical faculty in Uganda: a cross-sectional study** *MedEdPublish* [[paper](https://doi.org/10.12688/mep.20554.3)]
- [2025] **USING ARTIFICIAL INTELLIGENCE IN THE PROCESS OF TEACHING ENGLISH** *Scientific Herald of Sivershchyna Series Education Social and Behavioural Sciences* [[paper](https://doi.org/10.32755/sjeducation.2025.01.183)]
- [2025] **The Use of AI as an Assistant of University Students for their Research Proposal** *IDEAS Journal on English Language Teaching and Learning Linguistics and Literature* [[paper](https://doi.org/10.24256/ideas.v13i1.6159)]
- [2025] **Navigating Undergraduate Thesis Journey: Qualitative Exploration of Challenges, Strategies, and Skills in English Department Students** *JEES (Journal of English Educators Society)* [[paper](https://doi.org/10.21070/jees.v10i1.1916)]
- [2025] **AI-integrated language learning applications** [[paper](https://doi.org/10.29140/9781763711600-15)]
- [2025] **THE IMPACT OF AI QUILLBOT IN IMPROVING STUDENT WRITING ABILITY TO WRITE ARGUMENTATIVE ESSAYS** *English Review Journal of English Education* [[paper](https://doi.org/10.25134/erjee.v13i1.9746)]
- [2025] **Postgraduate students' voices on leveraging Grammarly as an AI-powered tool in academic writing** *Journal of Education* [[paper](https://doi.org/10.17159/2520-9868/i98a06)]
- [2025] **The Effectiveness of AI-Powered Writing Assistants in Enhancing Essay Writing Skills at Undergraduate Level** *Journal for social science archives* [[paper](https://doi.org/10.59075/jssa.v3i1.166)]
- [2025] **Using Grammarly as an Automated Writing Evaluation Tool for Academic Writing: Perceptions of English Linguistics Majors at a State University in Vietnam** *International Journal on Studies in English Language and Literature* [[paper](https://doi.org/10.20431/2347-3134.1306001)]
- [2025] **User Experience with AI Research Assistants in Tamil Nadu University Libraries: A Research Study** *International Journal of Information Studies and Libraries* [[paper](https://doi.org/10.21863/ijisl/2025.10.2.003)]
- [2025] **Teacher Perception of GenAI as an Assessment Aid** *Rare & Special e-Zone (The Hong Kong University of Science and Technology)* [[paper](https://repository.hkust.edu.hk/ir/Record/1783.1-170393)]
- [2025] **STUDENTS' EXPERIENCES IN USING GRAMMARLY IN ACADEMIC WRITING: THE SIXTH-SEMESTER STUDENTS’ OF ENGLISH LANGUAGE EDUCATION STUDY PROGRAM** *University of Bengkulu Scholar Repository (University of Bengkulu)* [[paper](https://repository.unib.ac.id/id/eprint/28162/1/Imel%20Nandarista%202%20-%20Imel%20Nandarista.pdf)]
- [2025] **A Study on the Utilization of Generative Artificial Intelligence Tools Among Students of Higher Education in India** *International journal of research studies in computer science and engineering* [[paper](https://doi.org/10.20431/2349-4859.1102002)]

##### 2024

- [2024] **GRAMMARLY’S INFLUENCE ON ACADEMIC WRITING CONFIDENCE IN HIGH SCHOOL STUDENTS: A QUASI-EXPERIMENTAL STUDY** *Pedagogy and Psychology* [[paper](https://doi.org/10.51889/2960-1649.2024.61.4.003)]
- [2024] **Enhancing Academic Writing through Digital Tools: A Systematic Review** *Journal of Language and Literature Studies* [[paper](https://doi.org/10.36312/jolls.v4i4.2342)]
- [2024] **EXAMINING THE IMPACT OF AI-POWERED WRITING TOOLS ON INDEPENDENT WRITING SKILLS OF HEALTH SCIENCE GRADUATES** *Advanced Education* [[paper](https://doi.org/10.20535/2410-8286.315068)]
- [2024] **EFL STUDENTS’ ATTITUDES AND PRACTICES TOWARD AI-BASED WRITING ASSISTANTS: AN EXPLANATORY MIXED-METHODS STUDY** *JIPI (Jurnal Ilmiah Penelitian dan Pembelajaran Informatika)* [[paper](https://doi.org/10.29100/jipi.v9i4.9184)]
- [2024] **Celebrating 25 Years of Nursing & Health Sciences: Interview With Founders and Editors** *Nursing and Health Sciences* [[paper](https://doi.org/10.1111/nhs.70025)]
- [2024] **The impact of artificial intelligence on scholars: an interview with Juan D. Machin-Mastromatteo** *Digital Library Perspectives* [[paper](https://doi.org/10.1108/dlp-10-2024-151)]
- [2024] **Navigating Ethical Dilemmas Of Generative AI In Medical Writing** *Journal of Rawalpindi Medical College* [[paper](https://doi.org/10.37939/jrmc.v28i3.2744)]
- [2024] **Exploring the Potential Synergy of Quillbot as a Natural Language Processing Tool in Demystifying Academic Writing** *أطراس* [[paper](https://doi.org/10.70091/atras/ai.5)]
- [2024] **Analyzing ESL Students Perceptions towards ChatGPT in Academic Writing** [[paper](https://doi.org/10.1145/3704611.3704625)]
- [2024] **AI Coders Are among Us: Rethinking Programming Language Grammar towards Efficient Code Generation** [[paper](https://doi.org/10.1145/3650212.3680347)]
- [2024] **Perceptions and detection of AI use in manuscript preparation for academic journals** *PLoS ONE* [[paper](https://arxiv.org/abs/2311.14720)]
- [2024] **Look Ma, No Input Samples! Mining Input Grammars from Code with Symbolic Parsing** [[paper](https://doi.org/10.1145/3663529.3663790)]
- [2024] **SpecGen: Automated Generation of Formal Program Specifications via Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.08807)]
- [2024] **RAR: Retrieval-augmented retrieval for code generation in low resource languages** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.1199)]
- [2024] **Pозробка письмового асистента за допомогою сучасних нейромережевих підходів для умовної генерації тексту** *eKNUTSHIR* [[paper](https://ir.library.knu.ua/handle/15071834/1824)]
- [2024] **On the Reliability and Explainability of Language Models for Program Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3641540)]
- [2024] **CodeIP: A Grammar-Guided Multi-Bit Watermark for Large Language Models of Code** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.541)]

##### 2023

- [2023] **Are You Creative? What College-Level English Language Learners Think of AI Writing Assistants** *Voices of English Language Education Society* [[paper](https://dx.doi.org/10.29408/veles.v7i3.21209)]
- [2023] **Editorial: Women in language and computation 2022** *Frontiers in Artificial Intelligence* [[paper](https://dx.doi.org/10.3389/frai.2023.1299100)]
- [2023] **AI (Artificial Intelligence) for scholars: ban it, or use it.** *Electronic Kyiv-Mohyla Academy Institutional Repository (National University of Kyiv-Mohyla Academy)* [[paper](https://ekmair.ukma.edu.ua/handle/123456789/26318)]

[⬆ Back to top](#paper-list)

#### Interactive Writing

##### 2026

- [2026] **Transformer-Powered AI Co-Writing Tools for Collaborative Academic Research Paper Development** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2026.01.021)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **Teachers, Tools, and AI: Understanding the Role of Generative Systems in Curriculum Production** *Open Research Online (The Open University)* [[paper](https://oro.open.ac.uk/view/person/tdu4.html>;)]
- [2026] **A new era in Education: Equipping first-year students with AI-driven study skills** *Journal of Perspectives in Applied Academic Practice* [[paper](https://doi.org/10.56433/mae00e73)]
- [2026] **Генеративний штучний інтелект у медичних наукових дослідженнях: можливості та ризики** *Scientific periodicals of Ukraine* [[paper](https://tubvil.com.ua/article/view/360285)]
- [2026] **The AI scientist: now academic papers can be fully automated, what does this mean for the future of research?** [[paper](https://doi.org/10.64628/ab.dt4s9yqtq)]
- [2026] **Generative Artificial Intelligence in Medical Research: Opportunities and Risks** *Tuberculosis Lung Diseases HIV Infection* [[paper](https://doi.org/10.30978/tb2026-2-105)]
- [2026] **Scholarly Integrity and Generative AI : Five Boundary Violations for IS Scholarship** *Information Systems Journal* [[paper](https://doi.org/10.1111/isj.70044)]
- [2026] **INTEGRATING AI TOOLS IN B2 LEVEL FOREIGN LANGUAGE CLASSROOMS: METHODS AND CHALLENGES** [[paper](https://doi.org/10.51889/3078-8463.2026.53.1.007)]
- [2026] **FROM WRITING TO SPEAKING: A SEQUENTIAL APPROACH TO DEVELOPING ACADEMIC PRESENTATIONS** *Наукові інновації та передові технології* [[paper](https://doi.org/10.52058/2786-5274-2026-4(56)-749-764)]
- [2026] **Influence of AI Tools on Academic Performance of Computer Application Graduates** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19414231)]
- [2026] **FERRAMENTAS DE INTELIGÊNCIA ARTIFICIAL GENERATIVA NA EDUCAÇÃO: UM ESTUDO COMPARATIVO** *RECIMA21 - Revista Científica Multidisciplinar - ISSN 2675-6218* [[paper](https://doi.org/10.47820/recima21.v7i2.7247)]
- [2026] **An Overview and Impact Analysis of AI Tools in Academic Research, Learning, and Educational Performance** *مجلة جامعة صنعاء للعلوم التطبيقية والتكنولوجيا* [[paper](https://doi.org/10.59628/jast.v4i2.1921)]
- [2026] **Project summary: Evaluating Generative AI as an Academic and Emotional Aid** *Open Research Online (The Open University)* [[paper](https://doi.org/10.21954/ou.se.31620499.v1)]
- [2026] **Logotic Programming: A Method for Encoding Conditions of Intelligibility for Machine and Human Intelligence** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18286050)]

##### 2025

- [2025] **AI Art Shop Discount Code HPK60 – Get 60% OFF AI Artwork** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18095079)]
- [2025] **The role of AI in ecology’s computational carbon footprint** *Frontiers in Ecology and the Environment* [[paper](https://doi.org/10.1002/fee.70021)]
- [2025] **Provide personalized programming learning for individuals based on large language models** *Alexandria Engineering Journal* [[paper](https://doi.org/10.1016/j.aej.2025.10.026)]
- [2025] **Hierarchical Chain-of-Thought and Mixture-of-Experts for Efficient Code Generation** [[paper](https://doi.org/10.1145/3778534.3778592)]
- [2025] **Data resource profile: the Intego-II primary care database** *International Journal of Epidemiology* [[paper](https://doi.org/10.1093/ije/dyaf200)]
- [2025] **Why diagnostic and nuclear medical physicists matter in academic medical centers: A perspective from a radiology department chair and a medical physicist** *Journal of Applied Clinical Medical Physics* [[paper](https://doi.org/10.1002/acm2.70255)]
- [2025] **The Role of Artificial Intelligence in Nursing Education: Opportunities and Challenges** *Nursing and Midwifery Journal* [[paper](https://doi.org/10.61882/unmf.23.3.1)]
- [2025] **The Path Forward for the Journal of Business Logistics** *Journal of Business Logistics* [[paper](https://doi.org/10.1111/jbl.70033)]
- [2025] **Natural Language Outlines for Code: Literate Programming in the LLM Era** [[paper](https://doi.org/10.1145/3696630.3728541)]
- [2025] **Code-Driven Planning in Grid Worlds with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.10749)]
- [2025] **Transforming orthopaedics with AI: Insights from a custom ChatGPT on ESSKA osteotomy consensus** *Knee Surgery Sports Traumatology Arthroscopy* [[paper](https://doi.org/10.1002/ksa.12653)]
- [2025] **Guest editorial: AI in education: transforming teaching and learning** *Information and Learning Sciences* [[paper](https://doi.org/10.1108/ils-01-2025-268)]
- [2025] **Editorial: Our polestars: articulating the vision and future of IJPDLM** *International Journal of Physical Distribution & Logistics Management* [[paper](https://doi.org/10.1108/ijpdlm-03-2025-558)]
- [2025] **Planning-Driven Programming: A Large Language Model Programming Workflow** [[paper](https://doi.org/10.18653/v1/2025.acl-long.621)]
- [2025] **Music’s AI Problem, AI’s Music Problem** *Journal of the American Musicological Society* [[paper](https://doi.org/10.1525/jams.2025.78.3.856)]
- [2025] **Letramento digital em Inteligência Artificial: conhecimentos e percepções de Pós-Graduandos em Educação sobre IA na pesquisa científica acadêmica** *LA Referencia (Red Federada de Repositorios Institucionales de Publicaciones Científicas)* [[paper](https://repositorio.ufc.br/handle/riufc/81787)]
- [2025] **Educators’ Perspectives on DeepSeek in ELT: A Qualitative Case Study of Pedagogical Potentials and Pitfalls in Chinese Higher Education** *Journal of Information Technology Education Research* [[paper](https://doi.org/10.28945/5625)]

##### 2024

- [2024] **Sustainability In FMCG: Energy Efficiency and Green Packaging As Transformative Practices** [[paper](https://doi.org/10.46254/ba07.20240006)]
- [2024] **Assessing ChatGPT’s Code Generation Capabilities with Short vs Long Context Programming Problems** [[paper](https://doi.org/10.1145/3704522.3704535)]
- [2024] **A Comprehensive Survey of AI-Driven Advancements and Techniques in Automated Program Repair and Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.07586)]
- [2024] **The Data Advantage: Artificial Intelligence in Ophthalmology** *Delhi Journal of Ophthalmology* [[paper](https://doi.org/10.4103/dljo.dljo_178_24)]
- [2024] **Statically Contextualizing Large Language Models with Typed Holes** *Proceedings of the ACM on Programming Languages* [[paper](https://arxiv.org/abs/2409.00921)]
- [2024] **Obvious artificial intelligence ‐generated anomalies in published journal articles: A call for enhanced editorial diligence** *Learned Publishing* [[paper](https://doi.org/10.1002/leap.1626)]
- [2024] **IJHG review 29.3: outstanding authors** *International Journal of Health Governance* [[paper](https://doi.org/10.1108/ijhg-09-2024-164)]
- [2024] **ChatScratch: An AI-Augmented System Toward Autonomous Visual Programming Learning for Children Aged 6-12** [[paper](https://arxiv.org/abs/2402.04975)]
- [2024] **Benchmarking Large Language Models for Bio-Image Analysis Code Generation** *bioRxiv (Cold Spring Harbor Laboratory)* [[paper](https://doi.org/10.1101/2024.04.19.590278)]
- [2024] **NekMesh: An open-source high-order mesh generation framework** *Computer Physics Communications* [[paper](https://doi.org/10.1016/j.cpc.2024.109089)]

##### 2023

- [2023] **A Survey of Learning-based Automated Program Repair** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3631974)]
- [2023] **Emerging applications of IoT and cybersecurity for electrical power systems** *IET Generation Transmission & Distribution* [[paper](https://doi.org/10.1049/gtd2.13012)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **Методика оцінювання ризиків взаємодії зі штучним інтелектом з урахуванням безпеки промптів** *Scientific periodicals of Ukraine* [[paper](https://sit.nuou.org.ua/article/view/363404)]
- [2026] **Utilization of AI Research Assistant on Creativity and Efficiency in Science Investigatory Projects Among Science, Technology, and Engineering (STE) Students** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22075509)]
- [2026] **The Impact of Artificial Intelligence on Software Engineering: Productivity, Code Quality, Security, and the Changing Role of Software Engineers** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21929388)]
- [2026] **INTEGRATING AI-ASSISTANT (COPILOT) TO IMPROVE LEARNERS’ AUTONOMOUS LEARNING OF ACADEMIC ENGLISH TEXTS** *Multidisciplinary Indonesian Center Journal* [[paper](https://doi.org/10.62567/micjo.v3i3.3081)]
- [2026] **Empowerment or Divide? A Mixed-Methods Investigation into AI Tool Usage in Chinese Language Learning among International Students in China’s Higher Vocational Colleges** *Journal of Artificial Intelligence and Information* [[paper](https://doi.org/10.66069/ojspub.5170260808)]
- [2026] **Artificial Intelligence Tools for Enhancing Academic and Psychological Student Support Services in Public Universities in Rivers State, Nigeria** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21805012)]
- [2026] **Role Of AI In Law Classroom** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21477035)]
- [2026] **FROM TOOL TO PARTNER: AI TECHNOLOGIES IN FOREIGN LANGUAGE TRAINING OF HIGHER EDUCATION STUDENTS** *Вісник науки та освіти* [[paper](https://doi.org/10.52058/2786-6165-2026-6(48)-1052-1066)]
- [2026] **Authorship, moral responsibility, and generative AI in nursing** *Nursing Ethics* [[paper](https://doi.org/10.1177/09697330261465739)]
- [2026] **AI in Foreign Language Teaching: Benefits, Risks, and Innovative Classroom Approaches** *Scientia* [[paper](https://doi.org/10.51773/sssh.v4i2.1032)]
- [2026] **Virtualia: vol. 3, n. 2 (2026).** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20171961)]
- [2026] **Smart Tools, Dependent Minds? Examining AI-Assisted Learning and Its Impact on Student Creativity and Independent Thinking** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21367530)]
- [2026] **Repositioning language teacher identity in the age of GenAI: Power, policy, and pedagogy in college writing classrooms** *SHAREOK (University of Oklahoma; Oklahoma State University; Central Oklahoma University)* [[paper](https://hdl.handle.net/20.500.14446/350321)]
- [2026] **Reimagining Pedagogy in the Age of Generative AI: From Teacher-Centered to Intelligence-Augmented Learning** *International Journal of Active & Healthy Aging* [[paper](https://doi.org/10.67015/ijaha.301)]
- [2026] **Guardians of Truth in Algerian Academia: Developing Ethical AI Frameworks for Multilingual Hypothesis-Driven Research** *Journal of Social Sciences* [[paper](https://doi.org/10.63939/jss.2026-vol10.n40.119-145)]
- [2026] **Editorial: Digital learning innovations: trends emerging scenario, challenges and opportunities** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2026.1871035)]
- [2026] **ChatGPT as an AI Learning Assistant for Enhancing EFL Students’ Writing** *Fonologi Jurnal Ilmuan Bahasa dan Sastra Inggris* [[paper](https://doi.org/10.61132/fonologi.v4i2.2752)]
- [2026] **Augmented With AI: A Practical Guide for Clinician Educators in Health Professions Education Scholarship (Preprint)** [[paper](https://doi.org/10.2196/preprints.104203)]
- [2026] **Artificial Intelligence: Concepts, Tools, and Practice BY N. V. Ratnakishor Gade, Dr. Mahaveerakannan R., Dr. Tamilvizhi T., Dr. Senduru Srinivasulu.** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20727076)]
- [2026] **Using the TAM Model to Explore the Faculty Lecturers’ Acceptance of ChatGPT as an Academic Writing Assistant Tool in Higher Education: A Case Study of a South African University** *TEM Journal* [[paper](https://doi.org/10.18421/tem152-62)]
- [2026] **The_Dilemma_of_Memory_Context_Rot_KV_Cache_LLM_EN** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20433182)]
- [2026] **The Use of AI Writing Assistance for Academic Writing: Investigating the Introduction Section of Research Articles Written by EFL Students** *Jurnal Pendidikan Bahasa Inggris undiksha* [[paper](https://doi.org/10.23887/jpbi.v14i1.111661)]
- [2026] **Skill Standards: Navigating Old Narrative Traps - A Briefing Note for Instructional Designers in New Zealand Vocational Education and Training** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20337480)]
- [2026] **Navigating ChatGPT in EFL Academic Writing: Pre-Service Teachers’ Experiences, Concerns, and Pedagogical Reflections** *Voices of English Language Education Society* [[paper](https://doi.org/10.29408/veles.v10i1.34008)]
- [2026] **Dr. Keechilat Pavithran, MD, DM, FRCP (May 23, 1962—April 28, 2026): A Tribute** *Indian Journal of Medical and Paediatric Oncology* [[paper](https://doi.org/10.1055/s-0046-1823652)]
- [2026] **AI-Assisted Academic Writing: Perspectives of EFL Students from Three Indonesian Universities** *FLIP Foreign Language Instruction Probe* [[paper](https://doi.org/10.54213/flip.v5i1.838)]
- [2026] **Workshop Sinergi Mendeley dan AI dalam Meningkatkan Kualitas Skripsi Mahasiswa Akhir IAI Laa Roiba Bogor** *El-Mujtama Jurnal Pengabdian Masyarakat* [[paper](https://doi.org/10.47467/elmujtama.v6i2.11591)]
- [2026] **Understanding AI Literacy Among College Students: Voices from a Historically Black College and University** *Journal of Interdisciplinary Studies in Education* [[paper](https://doi.org/10.32674/w76bnk04)]
- [2026] **The Impact of Artificial Intelligence on Postgraduate Students’ Learning Behaviour** *International Journal of Research & Technology* [[paper](https://doi.org/10.64882/ijrt.v14.is2.1223)]
- [2026] **The Future of Academic English Writing in the Age of Generative Artificial Intelligence** *Stanzaleaf International Journal of Multidisciplinary Studies* [[paper](https://doi.org/10.67313/slijms.2026.16)]
- [2026] **Neural Networks and Deep Learning: Foundations and Applications BY Prof. Vinayak Vijay Palmur,Prof. Nagesh Anand Goden,Ms. Pratiksha Chandrashekhar Parkarwar,Mr. Nehal Mane** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19878996)]
- [2026] **Editorial: Advancing vocal biomarkers and voice AI in healthcare: multidisciplinary focus on responsible and effective development and use** *Frontiers in Digital Health* [[paper](https://doi.org/10.3389/fdgth.2026.1811486)]
- [2026] **EVALUATING THE EFFICACY OF AI-POWERED LANGUAGE ASSISTANTS IN HIGHER EDUCATION** *Перспективи та інновації науки* [[paper](https://doi.org/10.52058/2786-4952-2026-3(61)-122-132)]
- [2026] **Consequences of Overdependence on Technology in English Learning Practices** *International Journal of English Teaching and Linguistics* [[paper](https://doi.org/10.37859/ijetl.v1i1.10836)]
- [2026] **Advancing Science Education Research Together (2020–2025): A Final JRST Editorial** *Journal of Research in Science Teaching* [[paper](https://doi.org/10.1002/tea.70051)]
- [2026] **AI as a Research Assistant: Opportunities, Risks, and Methodological Guidelines for Student Researchers** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19685131)]
- [2026] **TRANSFORMING GENERATIVE AI INTO A COGNITIVE SCAFFOLD: A SOCRATIC-STRUCTURED MODEL FOR DEVELOPING ACADEMIC WRITING SKILLS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19023075)]
- [2026] **Syntactic Complexity in Pakistani English Academic Writing: A Comparative Study of STEM vs Social Sciences Students** *Social science review archives.* [[paper](https://doi.org/10.70670/sra.v4i1.1994)]
- [2026] **Investigating Students’ Views on the Role of Generative AI in Academic Writing** *Journal of General Education and Humanities* [[paper](https://doi.org/10.58421/gehu.v5i2.1208)]
- [2026] **Advancing Higher Education through Faculty Development and Artificial Intelligence Training: A Case Study of a University in Punjab, Pakistan** *The critical review of social sciences studies* [[paper](https://doi.org/10.59075/gzf3n078)]
- [2026] **THE IMPACT OF AI TOOLS ON BOOSTING THE RESEARCHER’S ACADEMIC CULTURE: THEORETICAL APPROACH** *Наука і техніка сьогодні* [[paper](https://doi.org/10.52058/2786-6025-2026-1(55)-873-893)]
- [2026] **Revisiting the grand challenges: the road travelled and ahead at the frontiers of computer-aided drug design** *Frontiers in Drug Discovery* [[paper](https://doi.org/10.3389/fddsv.2026.1780834)]
- [2026] **Paper polish: Development of a GPT to fine-tune scientific manuscripts** *Indian Journal of Psychiatry* [[paper](https://doi.org/10.4103/indianjpsychiatry_1181_25)]
- [2026] **It’s Not Easy Staying Human: Generative AI, Cognition, and Reflection** [[paper](https://doi.org/10.5860/crln.87.2.58)]
- [2026] **Integrating Artificial Intelligence into a Multimodal Learning Framework** [[paper](https://doi.org/10.4324/9781003665472-7)]
- [2026] **IMPACT OF AI-ASSISTED SUGGESTIONS ON SYNTACTIC COMPLEXITY IN L2 ACADEMIC WRITING** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18654322)]
- [2026] **Abstracts Accepted for the 13th Annual Meeting of the Society of Clinical Anatomists, India, July 10th to 12th, 2025** *National Journal of Clinical Anatomy* [[paper](https://doi.org/10.4103/njca.njca_23_26)]
- [2026] **AI-Based Adaptive Learning Systems and their role in Enhancing Student Academic Performance** *Inverge Journal of Social Sciences* [[paper](https://doi.org/10.63544/ijss.v5i1.233)]
- [2026] **A STUDY ON THE ROLE OF ARTIFICIAL INTELLIGENCE IN ENHANCING STUDENT ACADEMIC PERFORMANCE** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18610015)]
- [2026] **UTILIZATION OF AI-ASSISTED LEARNING TOOLS AND DIGITAL LITERACY IN ENHANCING THE ACQUISITION OF RESEARCH COMPETENCIES AMONG HIGHER EDUCATION STEM STUDENTS IN AUSTRALIA.** *California Digital Library* [[paper](https://doi.org/10.48321/d10b233acb)]
- [2026] **The Effects of AI Tools on the Academic Performance and Engagement of TVL Learners** *International Journal of Research and Innovation in Social Science* [[paper](https://doi.org/10.47772/ijriss.2026.10100509)]
- [2026] **Technology-Enhanced English Language Learning: A Systematic Review of Digital Tools, Outcomes, and Limitations (SLR)** *International journal of research and scientific innovation* [[paper](https://doi.org/10.51244/ijrsi.2026.1306000456)]
- [2026] **Reimagining the Role of the EFL Teacher in the Age of Artificial Intelligence: Perceptions, Practices, and Pedagogical Transformations** [[paper](https://doi.org/10.66669/cineforum.v66is1.719)]
- [2026] **Intelligent Systems for Academic Research Integration (ISARI): A Local and Fully Offline Brainstorming Partner for Ethical Scholarly Inquiry** *Code Ocean* [[paper](https://doi.org/10.24433/co.2259729.v2)]
- [2026] **Custom GPTs to aid in compliance checking for reporting standards in academic publishing** *ALTEX* [[paper](https://doi.org/10.14573/altex.2601011)]
- [2026] **Comprehensive Consideration of Ethics in AI-assisted Scientific Writing and Peer Review** *Journal of Korean Medical Science* [[paper](https://doi.org/10.3346/jkms.2026.41.e281)]
- [2026] **Artificial Intelligence in Nursing Education: Exploring the Opportunities and Challenges of Technological Transformation** *Sağlık ve Hemşirelik Yönetimi Dergisi* [[paper](https://doi.org/10.54304/shyd.2026.26529)]
- [2026] **Artificial Intelligence Use in Nursing Education and Its Impact on Faculty Time Management, Task Efficiency, And Productivity** *Research and Analysis Journal* [[paper](https://doi.org/10.18535/raj.v9i08.629)]
- [2026] **Aria Programming Language** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18240247)]
- [2026] **A comparative analysis of AI grading tools: Efficiency, Pedagogy, and Human-in-the-Loop** *Rare & Special e-Zone (The Hong Kong University of Science and Technology)* [[paper](https://repository.hkust.edu.hk/ir/Record/1783.1-172128)]

##### 2025

- [2025] **Students' perception of using Chat Gpt as an academic writing assistant at an Islamic Senior High School** *eTheses of Maulana Malik Ibrahim State Islamic University (Maulana Malik Ibrahim State Islamic University)* [[paper](https://etheses.uin-malang.ac.id/82619/1/210107110064.pdf)]
- [2025] **Rigor and Representation: Leading the Next Five Years of JRST** *Journal of Research in Science Teaching* [[paper](https://doi.org/10.1002/tea.70031)]
- [2025] **REST: Embracing the rust programming language for modern electronic structure theory** *Chinese Journal of Chemical Physics* [[paper](https://doi.org/10.1063/1674-0068/cjcp2510156)]
- [2025] **Integrating Generative AI in EFL Academic Writing: Thai English-Major Students’ Purposes, Perceptions, and Experiences with ChatGPT** *rEFLections* [[paper](https://doi.org/10.61508/refl.v32i3.285982)]
- [2025] **Exploring Communication Authenticity Anxiety: A Data-DrivenPsychological Analysis of Al-Generated Content on StudentSelf-Perception and Expression** [[paper](https://doi.org/10.1109/decon67170.2025.11447813)]
- [2025] **QHackBench: Benchmarking Large Language Models for Quantum Code Generation Using PennyLane Hackathon Challenges** [[paper](https://doi.org/10.1109/qai63978.2025.00056)]
- [2025] **Hands-On Deep Learning: Tools, Frameworks, and Projects. BY Dr. J. Amutharaj, Mrs.A.Prema, Dr T Ramesh, Dr. M. Suresh** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17707287)]
- [2025] **Enhancing writing skills through AI-powered tools: perceived benefits and challenges among Vietnamese EFL students** *Discover Education* [[paper](https://doi.org/10.1007/s44217-025-00905-9)]
- [2025] **Conceptualizing Writing in the Digital Age: A Systematic Review of Research on AI-mediated EFL Analytical Writing** *International Journal of English Linguistics* [[paper](https://doi.org/10.5539/ijel.v15n6p114)]
- [2025] **AI in Scholarly Publishing** *Journal of Food Science* [[paper](https://doi.org/10.1111/1750-3841.70684)]
- [2025] **The Impact of AI Writing Assistants on Academic Writing Performance** *International Journal of Distance Education Technologies* [[paper](https://doi.org/10.4018/ijdet.391326)]
- [2025] **Programming Language Techniques for Bridging LLM Code Generation Semantic Gaps** [[paper](https://doi.org/10.1145/3759425.3763383)]
- [2025] **Learning with, rather than through, AI: co-designing science education for critical AI literacy** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1716353)]
- [2025] **How Natural Language Proficiency Shapes Generative AI Code for Software Engineering Tasks** *IEEE Software* [[paper](https://arxiv.org/abs/2511.04115)]
- [2025] **AI-Driven Research Practices in Indian Academia: Adoption, Challenges and Opportunities** [[paper](https://doi.org/10.1109/delcon68055.2025.11400275)]
- [2025] **AI-Digital Divide in Yemeni and South African Higher Education: Towards an Inclusive Policy-Oriented Approach** *Education and human development* [[paper](https://doi.org/10.5772/intechopen.1012099)]
- [2025] **A Journey of Purpose, Progress and Gratitude** *Journal of Indian Academy of Oral Medicine and Radiology* [[paper](https://doi.org/10.4103/jiaomr.jiaomr_426_25)]
- [2025] **Understanding EFL learners’ strategies in AI-assisted English writing: An activity theory perspective** *Porta Linguarum Revista Interuniversitaria de Didáctica de las Lenguas Extranjeras* [[paper](https://doi.org/10.30827/portalin.vixiii.32849)]
- [2025] **ChatGpt-generated modifications on human generated TESOL abstracts by Vietnamese researchers** *Ampersand* [[paper](https://doi.org/10.1016/j.amper.2025.100239)]
- [2025] **Artificial Intelligence in Medical Education: Knowledge, Attitudes, and Practices of AI Adoption among Teaching Staff and Medical Students at the University of Zawia** *AlQalam Journal of Medical and Applied Sciences* [[paper](https://doi.org/10.54361/ajmas.258394)]
- [2025] **GenAI as scholarly ally: patterns, pedagogy, and policies in graduate writing research** *Educational Technology Quarterly* [[paper](https://doi.org/10.55056/etq.965)]
- [2025] **From Tool to Partner** [[paper](https://doi.org/10.1093/9780198945215.003.0147)]
- [2025] **Constructing a New "Teacher-AI" Collaborative Teaching Paradigm in International Chinese Language Education Enabled by Generative AI** *Journal of Computing and Electronic Information Management* [[paper](https://doi.org/10.54097/9cknfy07)]
- [2025] **Rubric Is All You Need: Improving LLM-Based Code Evaluation With Question-Specific Rubrics** [[paper](https://arxiv.org/abs/2503.23989)]
- [2025] **Introduction** [[paper](https://doi.org/10.1201/9781003637738-1)]
- [2025] **Embracing Expansive Literacies: Our Collective Editorial Vision** *Journal of Adolescent & Adult Literacy* [[paper](https://doi.org/10.1002/jaal.70019)]
- [2025] **AnnCoder: A Mti-Agent-Based Code Generation and Optimization Model** *Symmetry* [[paper](https://doi.org/10.3390/sym17071087)]
- [2025] **A Systematic Review on the Use of ChatGPT in Literature Review on Urban Heat Island Concept** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18996416)]
- [2025] **Sustainability of Programming Education Through CDIO-Oriented Practice: An Empirical Study on Syntax-Level Structural Visualization for Functional Programming Languages** *Sustainability* [[paper](https://doi.org/10.3390/su17125630)]
- [2025] **STRUT: Structured Seed Case Guided Unit Test Generation for C Programs using LLMs** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3728970)]
- [2025] **Large Language Model for Verilog Generation with Code-Structure-Guided Reinforcement Learning** [[paper](https://doi.org/10.1109/iclad65226.2025.00025)]
- [2025] **CHATTING WITH THE ASSISTANT: ENABLING STUDENTS TO USE CHATGPT FOR SELF-ASSESSMENT BEFORE ASSIGNMENT SUBMISSION** [[paper](https://doi.org/10.36315/2025v2end114)]
- [2025] **Adapting High-Level Language Programming (C Language) Education in the Era of Large Language Models** *Journal of Contemporary Educational Research* [[paper](https://doi.org/10.26689/jcer.v9i5.10508)]
- [2025] **AI Chain-Driven Control Flow Graph Generation for Multiple Programming Language** *Wuhan University Journal of Natural Sciences* [[paper](https://doi.org/10.1051/wujns/2025303222)]
- [2025] **Multi-agent systems powered by large language models: applications in swarm intelligence** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1593017)]
- [2025] **Human Agency and Voice in the Shadow of Superintelligence** *Journal of International Crisis and Risk Communication Research* [[paper](https://stars.library.ucf.edu/teachwithai/2025/friday/39)]
- [2025] **On the Applicability of Code Language Models to Scientific Computing Programs** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2025.3564599)]
- [2025] **An Exploratory Study of Large Language Model-Based Writing Support for Postgraduate Engineering Students at a South African University** [[paper](https://doi.org/10.1109/educon62633.2025.11016325)]
- [2025] **AI Writing Assistants and Student Competence: A Linguistic Aspect** *Arab World English Journal* [[paper](https://doi.org/10.24093/awej/ai.18)]
- [2025] **A method for IoT devices test case generation using language models** *MethodsX* [[paper](https://doi.org/10.1016/j.mex.2025.103340)]
- [2025] **A PHENOMENOGRAPHIC Study on the Experiences of Students on the Use of Generative Artificial Intelligence (GAI) in Academic WRITING** *International Journal of Education Research* [[paper](https://doi.org/10.17158/ndv0dk46)]
- [2025] **Study 4 Use of ChatGPT** *Figshare* [[paper](https://figshare.com/articles/report/Study_4_Use_of_ChatGPT/28667852)]
- [2025] **Revisiting the Non-Determinism of Code Generation by the GPT-3.5 Large Language Model** [[paper](https://doi.org/10.1109/saner64311.2025.00012)]
- [2025] **Prompting Techniques for Secure Code Generation: A Systematic Investigation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3722108)]
- [2025] **Editorial: Pressures and dilemmas in scientific publishing in management: building rigor, relevance, and global impact** *Revista de Gestão* [[paper](https://doi.org/10.1108/rege-01-2025-212)]
- [2025] **AI Tools in Learning Academic Writing: Benefits and Challenges for MA Students in the English Language Studies at the Industrial University of Ho Chi Minh City** *International journal of AI in language education.* [[paper](https://doi.org/10.54855/ijaile.25215)]
- [2025] **A fine-tuned large language model based molecular dynamics agent for code generation to obtain material thermodynamic parameters** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-025-92337-6)]
- [2025] **Incorporating AI Literacy Instruction into Rhetorical Analysis Assignments** *AI-EDU arxiv.* [[paper](https://doi.org/10.36851/ai-edu.vi.5123)]
- [2025] **Academic Staff Perspectives on the Impact of Artificial Intelligence on Pharmaceutical Sciences Research and Writing: A Qualitative Study.** *Iraqi Journal of Pharmaceutical Sciences ( P-ISSN 1683 - 3597 E-ISSN 2521 - 3512)* [[paper](https://doi.org/10.31351/vol33iss(4si)pp12-19)]
- [2025] **Exploring Code Language Models for Automated HLS-based Hardware Generation: Benchmark, Infrastructure and Analysis** [[paper](https://doi.org/10.1145/3658617.3697616)]
- [2025] **Analysis of ChatGPT-Generated Codes Across Multiple Programming Languages** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3538050)]
- [2025] **AI Writing Assistants in Tanzanian Universities: Adoption Trends, Challenges, and Opportunities** [[paper](https://doi.org/10.18653/v1/2025.in2writing-1.4)]

##### 2024

- [2024] **The Potential Uses and Missuses of AI-Powered Writing Skills on Academic Writing: Students' Side** *Journal on Education* [[paper](https://doi.org/10.31004/joe.v7i1.7709)]
- [2024] **Guided Code Generation with LLMs: A Multi-Agent Framework for Complex Code Tasks** [[paper](https://doi.org/10.1109/jac-ecc64419.2024.11061204)]
- [2024] **Exploring ChatGPT-4 as an Academic Assistant in Thesis Development: A Case Study on Postgraduate Higher Education** [[paper](https://doi.org/10.1109/icalter65499.2024.10819226)]
- [2024] **Examining AI-Based Accuracy Assessment in L2 Learners’ Writing** *Journal of Pan-Pacific Association of Applied Linguistics* [[paper](https://doi.org/10.25256/paal.28.2.3)]
- [2024] **Using genAI in education: the case for critical thinking** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2024.1452131)]
- [2024] **Editorial: Generative artificial intelligence in the creator economy** *Online Information Review* [[paper](https://doi.org/10.1108/oir-11-2024-694)]
- [2024] **Automatic code generation based on Abstract Syntax-based encoding. Application on malware detection code generation based on MITRE ATT&CK techniques** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2024.125821)]
- [2024] **Patients and generative AI: Who owns your diagnosis?** *BJUI Compass* [[paper](https://doi.org/10.1002/bco2.420)]
- [2024] **Large Language Model-Based Optimization for System-Level Test Program Generation** [[paper](https://doi.org/10.1109/dft63277.2024.10753556)]
- [2024] **JavaBench: A Benchmark of Object-Oriented Code Generation for Evaluating Large Language Models** [[paper](https://doi.org/10.1145/3691620.3695470)]
- [2024] **Generating CAD Code with Vision-Language Models for 3D Designs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.05340)]
- [2024] **From Code to Correctness: Closing the Last Mile of Code Generation with Hierarchical Debugging** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.01215)]
- [2024] **Code Generation and Algorithmic Problem Solving Using Llama 3.1 405B** [[paper](https://doi.org/10.36227/techrxiv.172840612.21315865/v1)]
- [2024] **ChatGPT-driven machine learning code generation for android malware detection** *The Computer Journal* [[paper](https://doi.org/10.1093/comjnl/bxae114)]
- [2024] **Accelerating Optimal Power Flow With Structure-Aware Automatic Differentiation and Code Generation** *IEEE Transactions on Power Systems* [[paper](https://doi.org/10.1109/tpwrs.2024.3483489)]
- [2024] **Pedagogical Foundations of AI Integration** [[paper](https://doi.org/10.4324/9781003507949-2)]
- [2024] **What AI-Based Writing Assistant Actually Improved** *Advances in educational technologies and instructional design book series* [[paper](https://doi.org/10.4018/979-8-3693-2418-9.ch016)]
- [2024] **Structured Chain-of-Thought Prompting for Code Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3690635)]
- [2024] **Artificial intelligence-powered tools and academic writing: to use or not to use ChatGPT** *Saudi Journal of Language Studies* [[paper](https://doi.org/10.1108/sjls-06-2024-0029)]
- [2024] **Book review: Continuities and changes in ethnographies of work** *Journal of Organizational Ethnography* [[paper](https://doi.org/10.1108/joe-07-2024-102)]
- [2024] **Exploring EFL Teachers’ Insights Regarding Artificial Intelligence Driven Tools in Student-Centered Writing Instructions** *International Journal of English Linguistics* [[paper](https://doi.org/10.5539/ijel.v14n3p90)]
- [2024] **Automated Infrastructure as Code Program Testing** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3393070)]
- [2024] **LLM-based and Retrieval-Augmented Control Code Generation** [[paper](https://doi.org/10.1145/3643795.3648384)]
- [2024] **BatFix: Repairing language model-based transpilation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3658668)]
- [2024] **Investigating Chinese Learners ‘ Use and Perceptions of ChatGPT in EAP** [[paper](https://doi.org/10.1109/iciet60671.2024.10542734)]
- [2024] **The Imperative of Upholding Academic Integrity in the Face of Artificial Intelligence Challenges** *Indonesian Contemporary Nursing Journal (ICON Journal)* [[paper](https://doi.org/10.20956/icon.v8i2.33198)]
- [2024] **Saarthi: A Programming Language Designed to Introduce Coding to High Schoolers** [[paper](https://doi.org/10.23919/indiacom61295.2024.10498555)]
- [2024] **WORKSHOP ABSTRACTS** *Indian Journal of Psychiatry* [[paper](https://doi.org/10.4103/0019-5545.394311)]
- [2024] **TauchiGPT_V2: An Offline Agent-based Opensource AI Tool designed to Assist in Academic Research** *AHFE international* [[paper](https://doi.org/10.54941/ahfe1004567)]
- [2024] **Guiding Enumerative Program Synthesis with Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-65630-9_15)]
- [2024] **Flan: An Expressive and Efficient Datalog Compiler for Program Analysis** *Proceedings of the ACM on Programming Languages* [[paper](https://doi.org/10.1145/3632928)]
- [2024] **Code generation in ORCA: progress, efficiency and tight integration** *Physical Chemistry Chemical Physics* [[paper](https://doi.org/10.1039/d4cp00444b)]
- [2024] **AST-T5: Structure-Aware Pretraining for Code Generation and Understanding** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.03003)]

##### 2023

- [2023] **LLM-Assisted Code Cleaning For Training Accurate Code Generators** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.14904)]
- [2023] **ChatGPT: The Good, The Bad, and Everything in Between** *Indian Dermatology Online Journal* [[paper](https://doi.org/10.4103/idoj.idoj_274_23)]
- [2023] **An open-source natural language processing toolkit to support software development: addressing automatic bug detection, code summarisation and code search** *Open Research Europe* [[paper](https://doi.org/10.12688/openreseurope.14507.2)]

[⬆ Back to top](#paper-list)

#### Human-in-the-Loop

##### 2023

- [2023] **Ethical Considerations of LLM-Driven Quantum Code Generation for Optimization Tasks** *The American Journal of Engineering And Technology* [[paper](https://doi.org/10.37547/tajet/volume05issue12-13)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **THE ROLE OF ARTIFICIAL INTELLIGENCE IN DEVELOPING EFL LEARNERS' ACADEMIC WRITING SKILLS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21894387)]
- [2026] **Artificial Intelligence in Academic Writing: A Comprehensive Workflow and Practical Guide to 13 AI Research Assistants** [[paper](https://doi.org/10.67525/6pnc0868)]
- [2026] **Supervising in the Age of AI Cognitive Authenticity, and Reframing Integrity through Neurodiversity-Responsive Perspective Authors** *Arrow - TU Dublin (Technological University Dublin)* [[paper](https://arrow.tudublin.ie/jari/vol4/iss1/9)]
- [2026] **ECR Challenges and Opportunities** [[paper](https://doi.org/10.52843/cassyni.klqsg5)]
- [2026] **Bibby AI: An Editor-Native Agentic Platform for Academic Research, Writing, and Publishing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.05435)]
- [2026] **Assuring an AI Assistant for IRB Preparation: Replication Reliability, Warrant Stability, and Evidence-Driven Revision in Institutional RAG** *EdArXiv (OSF Preprints)* [[paper](https://osf.io/td47j)]
- [2026] **use of AI-powered writing tools in EFL academic writing in Indonesia: A meta-synthesis review** *Celtic A Journal of Culture English Language Teaching Literature and Linguistics* [[paper](https://doi.org/10.22219/celtic.v13i1.43324)]
- [2026] **Students’ Perceptions of AI-based Learning Assistants (AILAs) in Higher Education: A Systematic Review** *Journal of the National Organization for Student Success* [[paper](https://doi.org/10.61617/jnoss.114)]
- [2026] **Question-only AI Socratic dialogue as dialogic feedback in L2 argumentative writing: A quasi-experimental study** *Journal of Second Language Writing* [[paper](https://doi.org/10.1016/j.jslw.2026.101331)]
- [2026] **AI as Rubric Mediator: A Reflective Practice Brief on GPT-Supported Assessment for Learning in Music Education** *Asian Journal of Assessment in Teaching and Learning* [[paper](https://doi.org/10.37134/ajatel.vol16.1.6.2026)]
- [2026] **"I use it to polish my English": how researchers in Kazakhstan use AI in scholarly writing** *Suleyman Demirel University bulletin: pedagogy and teaching methods.* [[paper](https://doi.org/10.47344/4cxne315)]
- [2026] **Integration of AI-based writing assistants into ESP course** *Електронний архів наукових та освітніх матеріалів КПІ ім. Ігоря Сікорського (КПІ ім. Ігоря Сікорського)* [[paper](https://ela.kpi.ua/handle/123456789/82758)]
- [2026] **Integrating Large Language Models in Rheumatology: A Transformative Paradigm for Academia** *International Journal of Rheumatic Diseases* [[paper](https://doi.org/10.1111/1756-185x.70679)]
- [2026] **Error Analysis in the Age of AI: A Psycholinguistic Study of L2 Writer Dependency on Automated Writing Assistants** *World Journal of English Language* [[paper](https://doi.org/10.5430/wjel.v16n4p469)]
- [2026] **Helping LLMs improve code generation using feedback from testing and static analysis** *Discover Artificial Intelligence* [[paper](https://arxiv.org/abs/2412.14841)]
- [2026] **Crisis, Connection and Care** *Voices A World Forum for Music Therapy* [[paper](https://doi.org/10.15845/voices.v26i1.4700)]
- [2026] **Adapting AI tools in Research: Benefits, Barriers and Challenges in Implementations** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18957081)]
- [2026] **The Effectiveness of AI-Based Vocabulary Learning Platforms in Enhancing Academic Lexical Competence of University Students in AJK, Pakistan** *Inverge Journal of Social Sciences* [[paper](https://doi.org/10.63544/ijss.v5i1.241)]
- [2026] **Exploring the Role of Generative AI in Developing Student Skills in Higher Education: A Systematic Literature Review** *European Journal of Education* [[paper](https://doi.org/10.1111/ejed.70490)]
- [2026] **Exploring Student Behaviors and Motivations when using AI Teaching Assistants with Optional Guardrails** [[paper](https://doi.org/10.1145/3786228.3786233)]
- [2026] **Bibby AI -- AI Latex Editor writing assistant for researchers vs Overleaf Alternative vs OpenAI Prism. (Bibby AI Latex Editor)** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.16432)]
- [2026] **AN ANALYSIS ON "PROMOTING INCLUSIVITY: PSYCHOLOGICAL BENEFITS OF AI FOR STUDENTS WITH LEARNING DISABILITIES"** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18638379)]
- [2026] **Yapay Zekâ ile Akıllı Kodlama: Eğitim Alanında Kuramsal Bir İnceleme ve Uygulama Odaklı Çerçeve** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18236657)]
- [2026] **List of Contributors** [[paper](https://doi.org/10.1093/9780197759370.002.0007)]
- [2026] **Fostering EFL Students’ Academic Literacy: Students' Perception Using Elicit AI** *Edulitics (Education Literature and Linguistics) Journal* [[paper](https://doi.org/10.52166/edulitics.v10i2.11361)]
- [2026] **Academic Belonging in the Age of Artificial Intelligence: A Scoping Review Protocol** [[paper](https://osf.io/8h4j6)]

##### 2025

- [2025] **A Generative AI Virtual Teaching Assistant for Graduate Nursing Informatics Education** *CIN Computers Informatics Nursing* [[paper](https://doi.org/10.1097/cin.0000000000001411)]
- [2025] **AI sebagai Alat Bantu Literasi Digital di Politeknik Pelayaran Sumatera Barat: Studi Literatur** *Jurnal Cakrawala Bahari.* [[paper](https://doi.org/10.70031/jkb.v8i2.192)]
- [2025] **Introduction to Rowan Approved AI Tools: Copilot, Adobe, and Gemini** *Rowan Digitals Works (Rowan University)* [[paper](https://rdw.rowan.edu/libraryworkshops/45)]
- [2025] **Intelligent Code Analysis and Feedback Generation** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-3373-0598-1.ch006)]
- [2025] **Execution-Aware Hierarchical Code Generation with Qwen-72B and Retrieval Augmentation** [[paper](https://doi.org/10.1145/3778450.3778516)]
- [2025] **Engineering Students' Experiences With ChatGPT to Generate Code for Disciplinary Programming** *Computer Applications in Engineering Education* [[paper](https://doi.org/10.1002/cae.70090)]
- [2025] **Integrating AI into Critical Literacy Practices for Academic Publishing in Language Education: Insights from Kazakhstan** *Forum for Linguistic Studies* [[paper](https://doi.org/10.30564/fls.v7i10.10698)]
- [2025] **Guiding LLM-based Smart Contract Generation with Finite State Machine** [[paper](https://doi.org/10.24963/ijcai.2025/653)]
- [2025] **Artificial intelligence as author: Can scientific reviewers recognize GPT-4o-generated manuscripts?** *The American Journal of Emergency Medicine* [[paper](https://doi.org/10.1016/j.ajem.2025.07.034)]
- [2025] **Artificial Intelligence Integration in the Acquisition of English Academic Writing** *Porta Universorum* [[paper](https://doi.org/10.69760/portuni.0105006)]
- [2025] **Advancing Code Coverage: Incorporating Program Analysis with Large Language Models** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3748505)]
- [2025] **MAGE: A Multi-Agent Engine for Automated RTL Code Generation** [[paper](https://doi.org/10.1109/dac63849.2025.11133191)]
- [2025] **CRITICAL REFLECTIONS ON TRIALLING AN AI APPLICATION IN TEACHER EDUCATION ASSESSMENT IN THE TECHNOLOGICAL AGE** [[paper](https://doi.org/10.36315/2025v2end097)]
- [2025] **Chain-of-programming (CoP): empowering large language models for geospatial code generation task** *International Journal of Digital Earth* [[paper](https://doi.org/10.1080/17538947.2025.2509812)]
- [2025] **The use of artificial intelligence technologies in the students’ research work** *Moscow University Bulletin Series 19 Linguistics and Intercultural Communication* [[paper](https://doi.org/10.55959/msu-2074-1588-19-28-1-6)]
- [2025] **Exploring Student Behaviors and Motivations using AI TAs with Optional Guardrails** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.11146)]
- [2025] **Exploring the Use of AI-Powered Chatbots and Writing Assistants on Academic Integrity in Zambia’s Higher Learning Institutions** *Asian Journal of Research in Computer Science* [[paper](https://doi.org/10.9734/ajrcos/2025/v18i4620)]
- [2025] **Revolutionizing Peer Review: A Comparative Analysis of ChatGPT and Human Review Reports in Scientific Publishing** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202502.0058.v1)]
- [2025] **Unlocking AI Potential: Effort Expectancy, Satisfaction, and Usage in Research** *Journal of Information Technology Education Innovations in Practice* [[paper](https://doi.org/10.28945/5450)]
- [2025] **The Impact of Generative AI Tools on Postgraduate Students’ Learning Experiences: New Insights Into Usage Patterns** *Journal of Information Technology Education Research* [[paper](https://doi.org/10.28945/5428)]
- [2025] **Innovations in Digital Health From a Global Perspective: Proceedings of PRC‐HI 2024** *Health care science* [[paper](https://doi.org/10.1002/hcs2.128)]
- [2025] **Generative Artificial Intelligence (GenAI) in the research process – A survey of researchers’ practices and perceptions** *Technology in Society* [[paper](https://doi.org/10.1016/j.techsoc.2025.102813)]
- [2025] **CRUXEVAL-X: A Benchmark for Multilingual Code Reasoning, Understanding and Execution** [[paper](https://doi.org/10.18653/v1/2025.acl-long.1158)]

##### 2024

- [2024] **Review on AI Assistant Systems for Programming Language Learning in Learning Environments** [[paper](https://doi.org/10.1109/slaai-icai63667.2024.10844969)]
- [2024] **Enhancing the Academic Writing Process Using Artificial Intelligence: A Bibliometric** *Humanities & Language International Journal of Linguistics Humanities and Education* [[paper](https://doi.org/10.32734/djd9kz89)]
- [2024] **Artificial intelligence in scientific writing: sailing fair winds or between the devil and the deep blue sea?** *Women & Health* [[paper](https://doi.org/10.1080/03630242.2025.2445890)]
- [2024] **AlphaVerus: Bootstrapping Formally Verified Code Generation through Self-Improving Translation and Treefinement** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.06176)]
- [2024] **WhiteFox: White-Box Compiler Fuzzing Empowered by Large Language Models** *Proceedings of the ACM on Programming Languages* [[paper](https://doi.org/10.1145/3689736)]
- [2024] **Sifting through the Chaff: On Utilizing Execution Feedback for Ranking the Generated Code Candidates** [[paper](https://doi.org/10.1145/3691620.3695000)]
- [2024] **RLEF: Grounding Code LLMs in Execution Feedback with Reinforcement Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.02089)]
- [2024] **Programming with AI: Evaluating ChatGPT, Gemini, AlphaCode, and GitHub Copilot for Programmers** [[paper](https://doi.org/10.1145/3723178.3723224)]
- [2024] **AI-ASSISTED SCHOLARLY WRITING IN EDUCATION: A SCOPING REVIEW (2019–2024)** *Habaršy. Pedagogika ġylymdary seriâsy* [[paper](https://doi.org/10.51889/2959-5762.2025.87.3.003)]
- [2024] **Awareness and Attitudes of Chinese Medical Students Towards the Application of Large Language Models in Medicine: A Cross-Sectional Survey Study (Preprint)** [[paper](https://dx.doi.org/10.2196/preprints.66381)]
- [2024] **Perceptions and Use of AI Chatbots among Students in Higher Education: A Scoping Review of Empirical Studies** *Education Sciences* [[paper](https://doi.org/10.3390/educsci14080922)]
- [2024] **An Empirical Study on Self-correcting Large Language Models for Data Science Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.15658)]
- [2024] **Leveraging Lecture Content for Improved Feedback: Explorations with GPT-4 and Retrieval Augmented Generation** [[paper](https://doi.org/10.1109/cseet62301.2024.10663001)]
- [2024] **Code Generation Based Grading: Evaluating an Auto-grading Mechanism for "Explain-in-Plain-English" Questions** [[paper](https://doi.org/10.1145/3649217.3653582)]
- [2024] **Navigating the “Cooked” Data: A Framework for Understanding GenAI's Impact on Academic Writing and Learning** [[paper](https://doi.org/10.1145/3678610.3678630)]
- [2024] **Isolating Compiler Bugs by Generating Effective Witness Programs With Large Language Models** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3397822)]
- [2024] **Codexity: Secure AI-assisted Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.03927)]
- [2024] **UNVEILING THE IMPACT OF AI CHATBOTS ON HIGHER EDUCATION: INSIGHTS FROM STUDENTS** *INTED proceedings* [[paper](https://doi.org/10.21125/inted.2024.0428)]
- [2024] **Using Large Language Models for Student-Code Guided Test Case Generation in Computer Science Education** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.07081)]
- [2024] **The Effects of a QuillBot-Based Intervention on English Language Majors’ EFL Writing Performance, Apprehension, and Self-Efficacy** *Language Teaching Research Quarterly* [[paper](https://doi.org/10.32038/ltrq.2024.43.10)]
- [2024] **Grounding Data Science Code Generation with Input-Output Specifications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.08073)]
- [2024] **Do Large Code Models Understand Programming Concepts? Counterfactual Analysis for Code Predicates** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.05980)]
- [2024] **Assessing the Effectiveness and Security Implications of AI Code Generators** *Journal of The Colloquium for Information Systems Security Education* [[paper](https://doi.org/10.53735/cisse.v11i1.180)]
- [2024] **The Counterfeit Conundrum: Can Code Language Models Grasp the Nuances of Their Incorrect Generations?** [[paper](https://arxiv.org/abs/2402.19475)]
- [2024] **PokeMQA: Programmable knowledge editing for Multi-hop Question Answering** [[paper](https://doi.org/10.18653/v1/2024.acl-long.438)]
- [2024] **Instruct-Code-Llama: Improving Capabilities of Language Model in Competition Level Code Generation by Online Judge Feedback** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-97-5669-8_11)]
- [2024] **Aligning Crowd-Sourced Human Feedback for Reinforcement Learning on Code Generation by Large Language Models** *IEEE Transactions on Big Data* [[paper](https://arxiv.org/abs/2503.15129)]

##### 2023

- [2023] **Large Language Models (GPT) for automating feedback on programming assignments** *International Conference on Computers in Education* [[paper](https://doi.org/10.58459/icce.2023.950)]
- [2023] **Application of artificial intelligence chatbots, including ChatGPT, in education, scholarly work, programming, and content generation and its prospects: a narrative review** *Journal of Educational Evaluation for Health Professions* [[paper](https://doi.org/10.3352/jeehp.2023.20.38)]
- [2023] **AI-Enhanced Auto-Correction of Programming Exercises: How Effective is GPT-3.5?** *International Journal of Engineering Pedagogy (iJEP)* [[paper](https://doi.org/10.3991/ijep.v13i8.45621)]
- [2023] **FlowMind: Automatic Workflow Generation with LLMs** [[paper](https://doi.org/10.1145/3604237.3626908)]
- [2023] **CodeFuse-13B: A Pretrained Multi-lingual Code Large Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.06266)]
- [2023] **Case study: using AI-assisted code generation in mobile teams** [[paper](https://doi.org/10.1109/iccp60212.2023.10398656)]
- [2023] **Text2Reward: Reward Shaping with Language Models for Reinforcement Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.11489)]
- [2023] **Strategies to Promote Academic Integrity for Graduate Nursing Students in an Online Learning Environment** *Distance Learning* [[paper](https://doi.org/10.1108/dl-09-2023-0003)]
- [2023] **Fixing Large Language Models' Specification Misunderstanding for Better Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2309.16120)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **Apocalypse? Nah! Part II – two roads diverge** *Journal of Cell Science* [[paper](https://doi.org/10.1242/jcs.265186)]
- [2026] **Impact of Artificial intelligence tools on learning motivation in English instruction: a network meta-analysis** *Asian-Pacific Journal of Second and Foreign Language Education* [[paper](https://doi.org/10.1186/s40862-026-00421-9)]
- [2026] **Impact of AI Agents on the Thinking Process of Students in the Indian Education System** *International Journal of Innovative Research in Advanced Engineering* [[paper](https://doi.org/10.26562/ijirae.2026.v1307.03)]
- [2026] **Teaching Students to Identify Ethical Risks and Blind Spots in Academic AI Use** *Journal of Technology-Integrated Lessons and Teaching* [[paper](https://doi.org/10.13001/jtilt.v5i1.10297)]
- [2026] **STUDENTS’ ATTITUDES TOWARDS CHATGPT AS A LEARNING ASSISTANT** *International Journal of Entrepreneurship and Management Practices* [[paper](https://doi.org/10.35631/ijepc.1163058)]
- [2026] **Artificial Intelligence in English Language Learning: Transforming Teaching Pedagogy in the Digital Age** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21130214)]

##### 2025

- [2025] **The Rise of AI Tools in Classrooms: Threat or Opportunity for Academic Integrity** *Elicit Journal of Education Studies* [[paper](https://doi.org/10.65820/ejes-7vol1-issue1-2025)]
- [2025] **Using AI in Academic Writing: Development of Best Practices for Teacher Education Research** [[paper](https://doi.org/10.1109/aixheart65685.2025.00020)]
- [2025] **ARTIFICIAL INTELLIGENCE IN HIGHER EDUCATION** *DOAJ (DOAJ: Directory of Open Access Journals)* [[paper](https://doaj.org/article/4b7bc08947f74a3383720a723cd02bbe)]
- [2025] **Systematic Review of Large Language Model Applications in Programming Education** *Frontiers in artificial intelligence and applications* [[paper](https://doi.org/10.3233/faia250512)]
- [2025] **EXPLORING THE RELATIONSHIP BETWEEN AI USAGE, SELF-EFFICACY, AND ACADEMIC MOTIVATION AMONG ENGLISH LANGUAGE LEARNERS** *Qualitative Research Journal for Social Studies* [[paper](https://doi.org/10.63878/qrjs442)]
- [2025] **Integration of Retrieval-Augmented Generation and Multimodal Technologies for Advanced Virtual Research Assistants** *Journal of Information Systems Engineering & Management* [[paper](https://doi.org/10.52783/jisem.v10i37s.6508)]
- [2025] **Personalised Code and Error Predictions in Programming Education via Large Language Models** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-98420-4_29)]

##### 2024

- [2024] **One Step at a Time: Combining LLMs and Static Analysis to Generate Next-Step Hints for Programming Tasks** [[paper](https://arxiv.org/abs/2410.09268)]
- [2024] **Integrating AI into Academic Research: How We Navigate the Inevitable Ethically** [[paper](https://doi.org/10.36006/09651-1-07)]
- [2024] **Large Language Models in Computer Science Education: A Systematic Literature Review** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.16349)]
- [2024] **Student Assistants’ Perceived Leadership Impact of Artificial Intelligence on the Reading and Writing Landscape** *Atlantis highlights in social sciences, education and humanities/Atlantis Highlights in Social Sciences, Education and Humanities* [[paper](https://doi.org/10.2991/978-94-6463-439-6_11)]
- [2024] **AI-Powered Chatbots as Personalized Academic Writing Assistants for Non-Native English Speakers** [[paper](https://doi.org/10.1007/978-981-13-2262-4_313-1)]

##### 2023

- [2023] **ExGen: Ready-To-Use Exercise Generation in Introductory Programming Courses** *International Conference on Computers in Education* [[paper](https://doi.org/10.58459/icce.2023.953)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **A Comprehensive Review On The Comparison Between Chatgpt And Perplexity AI** *IOSR Journal of Computer Engineering* [[paper](https://doi.org/10.9790/0661-2801015661)]

##### 2025

- [2025] **P rome F uzz : A Knowledge-Driven Approach to Fuzzing Harness Generation with Large Language Models** [[paper](https://doi.org/10.1145/3719027.3765222)]
- [2025] **Look Before You Leap: An Exploratory Study of Uncertainty Analysis for Large Language Models** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3519464)]
- [2025] **Exploring the use of retrieval-augmented generation models in higher education: A pilot study on artificial intelligence-based tutoring** *Social Sciences & Humanities Open* [[paper](https://doi.org/10.1016/j.ssaho.2025.101751)]

##### 2024

- [2024] **Fight Fire With Fire: How Much Can We Trust ChatGPT on Source Code-Related Tasks?** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3492204)]
- [2024] **Automated C/C++ Program Repair for High-Level Synthesis via Large Language Models** [[paper](https://doi.org/10.1109/mlcad62225.2024.10740262)]

##### 2023

- [2023] **GenSim: Generating Robotic Simulation Tasks via Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.01361)]

[⬆ Back to top](#paper-list)

#### NLP Metrics

##### 2025

- [2025] **Generating vulnerability security fixes with Code Language Models** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2025.107786)]
- [2025] **Enhancing Code Intelligence with CodeT5: A Unified Approach to Code Analysis and Generation** [[paper](https://doi.org/10.1109/aide64228.2025.10987356)]
- [2025] **Bridging Language Barriers in Coding: An NLP-Powered Tool for Programming Education in Regional Languages** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3587056)]

##### 2024

- [2024] **The use of large language models for program repair** *Computer Standards & Interfaces* [[paper](https://doi.org/10.1016/j.csi.2024.103951)]
- [2024] **Exploring the Effectiveness of LLMs in Automated Logging Statement Generation: An Empirical Study** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2024.3475375)]
- [2024] **Enhancing Code Generation for Dataflow Programming: Fine-Tuning Large Language Models with the DFCPP Dataset** [[paper](https://doi.org/10.1109/ispa63168.2024.00314)]

##### 2023

- [2023] **CodeGen-Test: An Automatic Code Generation Model Integrating Program Test Information** [[paper](https://doi.org/10.1109/cbase60015.2023.10439105)]
- [2023] **The Good, the Bad, and the Missing: Neural Code Generation for Machine Learning Tasks** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3630009)]
- [2023] **SteloCoder: a Decoder-Only LLM for Multi-Language to Python Code Translation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.15539)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2026

- [2026] **AFFECTIVE DYNAMICS IN AI-ASSISTED AND TRADITIONAL SECOND LANGUAGE WRITING: AN IDIODYNAMIC STUDY INFORMED BY COMPLEXITY DYNAMIC SYSTEMS THEORY** *LLT Journal A Journal on Language and Language Teaching* [[paper](https://doi.org/10.24071/llt.v29i1.443)]

##### 2025

- [2025] **Investigating AI Literacy of Turkish Pre-Service EFL Teachers** *International Primary Education Research Journal* [[paper](https://doi.org/10.38089/ekuad.2025.244)]

##### 2024

- [2024] **Meet our European editorial board members** *International Wound Journal* [[paper](https://doi.org/10.1111/iwj.70085)]
- [2024] **ClarifyGPT: A Framework for Enhancing LLM-Based Code Generation via Requirements Clarification** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3660810)]
- [2024] **AceCoder : An Effective Prompting Technique Specialized in Code Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3675395)]
- [2024] **PythonSaga: Redefining the Benchmark to Evaluate Code Generating LLMs** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.996)]
- [2024] **L2CEval : Evaluating Language-to-Code Generation Capabilities of Large Language Models** *Transactions of the Association for Computational Linguistics* [[paper](https://doi.org/10.1162/tacl_a_00705)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Artificial Intelligence as a catalyst for Urdu language digitalization: opportunities, challenges and policy implications** *Aposta* [[paper](https://doi.org/10.23900/ra.v24i115.1391)]
- [2026] **Argumentative und unpersönliche Ausdrucksmittel in vorwissenschaftlichen Texten studentischer Produktion und ihren Bearbeitungen durch den KI-Schreibassistenten DeepL Write** *LEA - Lingue e Letterature d Oriente e d Occidente* [[paper](https://doi.org/10.36253/lea-1824-484x-17368)]
- [2026] **Security and Quality in LLM-Generated Code: A Multi-Language, Multi-Model Analysis** *IEEE Transactions on Dependable and Secure Computing* [[paper](https://doi.org/10.1109/tdsc.2026.3672745)]
- [2026] **Assessing small language models for code generation: An empirical study with benchmarks** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2026.112815)]
- [2026] **Steer Your Model: Secure Code Generation With Contrastive Decoding** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2025.3650127)]
- [2026] **Code Generation by Large Language Models: A Comparative Analysis of ChatGPT, Claude, and DeepSeek** *International Journal of Electrical and Electronic Engineering & Telecommunications* [[paper](https://doi.org/10.18178/ijeetc.15.1.19-28)]
- [2026] **Argumentative und unpersonliche Ausdrucksmittel in vorwissenschaftlichen Texten studentischer Produktion und ihren Bearbeitungen durch den KI-Schreibassistenten DeepL Write** *CINECA IRIS Institutial research information system (University of Pisa)* [[paper](https://hdl.handle.net/11568/1356880)]
- [2026] **A Study of LLMs’ Preferences for Libraries and Programming Languages** [[paper](https://arxiv.org/abs/2503.17181)]

##### 2025

- [2025] **QuanBench: Benchmarking Quantum Code Generation with Large Language Models** [[paper](https://doi.org/10.1109/ase63991.2025.00218)]
- [2025] **Neural Methods for Programming: A Comprehensive Survey and Future Directions** *Applied Sciences* [[paper](https://doi.org/10.3390/app152212150)]
- [2025] **Large mRNA language foundation modeling with NUWA for unified sequence perception and generation** *bioRxiv (Cold Spring Harbor Laboratory)* [[paper](https://doi.org/10.1101/2025.11.01.686058)]
- [2025] **Energy-Aware Code Generation with LLMs: Benchmarking Small vs. Large Language Models for Sustainable AI Programming** [[paper](https://doi.org/10.1109/fllm67465.2025.11391072)]
- [2025] **TaskEval: Assessing Difficulty of Code Generation Tasks for Large Language Models** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3773285)]
- [2025] **Leveraging Symmetry in Multi-Agent Code Generation: A Cross-Verification Collaboration Protocol for Competitive Programming** *Symmetry* [[paper](https://doi.org/10.3390/sym17101660)]
- [2025] **Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Accuracy, Reliability, and Latency** [[paper](https://doi.org/10.1109/aict67988.2025.11268754)]
- [2025] **A Survey on LLM-based Code Generation for Low-Resource and Domain-Specific Programming Languages** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3770084)]
- [2025] **PennyCoder: Efficient Domain-Specific LLMs for PennyLane-Based Quantum Code Generation** [[paper](https://arxiv.org/abs/2507.19562)]
- [2025] **Fault Localization from the Semantic Code Search Perspective** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3757915)]
- [2025] **Towards Formal Verification of LLM-Generated Code from Natural Language Prompts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.13290)]
- [2025] **CADInstruct: A multimodal dataset for natural language-guided CAD program synthesis** *Computer-Aided Design* [[paper](https://doi.org/10.1016/j.cad.2025.103926)]
- [2025] **Type-Constrained Code Generation with Language Models** *Proceedings of the ACM on Programming Languages* [[paper](https://arxiv.org/abs/2504.09246)]
- [2025] **Software Vulnerability Detection in Source Code Using Superb Fairy-Wren Deep Transformer Guided Model for Next Generation Software Security** [[paper](https://doi.org/10.1109/icirca65293.2025.11089899)]
- [2025] **Programming Embedded IoT Applications in Natural Language with IoTPilot** [[paper](https://doi.org/10.1145/3711875.3729136)]
- [2025] **PCEBench: A Multi-Dimensional Benchmark for Evaluating Large Language Models in Parallel Code Generation** [[paper](https://doi.org/10.1109/ipdps64566.2025.00055)]
- [2025] **GPIoT: Tailoring Small Language Models for IoT Program Synthesis and Development** [[paper](https://doi.org/10.1145/3715014.3722064)]
- [2025] **Comparative Analysis of ChatGPT, DeepSeek, and Gemini for Automated Code Generation** [[paper](https://doi.org/10.1109/emes65692.2025.11045587)]
- [2025] **Can LLMs Generate Higher Quality Code Than Humans? An Empirical Study** [[paper](https://doi.org/10.1109/msr66628.2025.00081)]
- [2025] **ASTER: Natural and Multi-Language Unit Test Generation with LLMs** [[paper](https://doi.org/10.1109/icse-seip66354.2025.00042)]
- [2025] **Impact of Large Language Models of Code on Fault Localization** [[paper](https://doi.org/10.1109/icst62969.2025.10989036)]
- [2025] **Fully Autonomous Programming Using Iterative Multi-Agent Debugging with Large Language Models** *ACM Transactions on Evolutionary Learning and Optimization* [[paper](https://arxiv.org/abs/2503.07693)]
- [2025] **TESTEVAL: Benchmarking Large Language Models for Test Case Generation** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.197)]
- [2025] **SolEval: Benchmarking Large Language Models for Repository-level Solidity Smart Contract Generation** [[paper](https://doi.org/10.18653/v1/2025.emnlp-main.218)]
- [2025] **ProjectEval: A Benchmark for Programming Agents Automated Evaluation on Project-Level Code Generation** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.1036)]
- [2025] **Optimizing Pre-Trained Code Embeddings With Triplet Loss for Code Smell Detection** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3542566)]
- [2025] **HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3715109)]
- [2025] **Flow2Code: Evaluating Large Language Models for Flowchart-based Code Generation Capability** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.425)]
- [2025] **Evaluation of Generative AI Models in Python Code Generation: A Comparative Study** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3560244)]
- [2025] **Evaluating Large Language Models for Automatic Register Transfer Logic Generation for Combinational Circuits via High-Level Synthesis** *Foundations and Trends® in Electronic Design Automation* [[paper](https://doi.org/10.1561/1000000063-3)]
- [2025] **CodeReviewQA: The Code Review Comprehension Assessment for Large Language Models** [[paper](https://doi.org/10.18653/v1/2025.findings-acl.476)]
- [2025] **CoT-RAG: Integrating Chain of Thought and Retrieval-Augmented Generation to Enhance Reasoning in Large Language Models** [[paper](https://doi.org/10.18653/v1/2025.findings-emnlp.168)]

##### 2024

- [2024] **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models (LLMs)** [[paper](https://arxiv.org/abs/2409.12699)]
- [2024] **Explainable automated debugging via large language model-driven scientific debugging** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-024-10594-x)]
- [2024] **Computational approaches for enteric methane mitigation research: from fermi calculations to artificial intelligence paradigms** *Animal Frontiers* [[paper](https://doi.org/10.1093/af/vfae025)]
- [2024] **From Natural Language to Code: AI Automation in Cyber-Physical Manufacturing Systems** [[paper](https://doi.org/10.1109/wccs62745.2024.10765530)]
- [2024] **Analysis of Datasets and Large Language Models for Vulnerability Detection in Imperative Programming Language Code** *PROGRAMMNAYA INGENERIA* [[paper](https://doi.org/10.17587/prin.15.555-569)]
- [2024] **SALLM: Security Assessment of Generated Code** [[paper](https://doi.org/10.1145/3691621.3694934)]
- [2024] **Research on Code Generation Technology based on LLM Pre-training** *Frontiers in Computing and Intelligent Systems* [[paper](https://doi.org/10.54097/scrwpt34)]
- [2024] **Prompt-based automation of building code information transformation for compliance checking** *Automation in Construction* [[paper](https://doi.org/10.1016/j.autcon.2024.105817)]
- [2024] **On the Effectiveness of Large Language Models in Domain-Specific Code Generation** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3697012)]
- [2024] **LLASP: Fine-tuning Large Language Models for Answer Set Programming** [[paper](https://doi.org/10.24963/kr.2024/78)]
- [2024] **EvoCodeBench: An Evolving Code Generation Benchmark with Domain-Specific Evaluations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.22821)]
- [2024] **EffiCoder: Enhancing Code Generation in Large Language Models through Efficiency-Aware Fine-tuning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.10209)]
- [2024] **Development and benchmarking of multilingual code clone detector** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2024.112215)]
- [2024] **ComplexCodeEval: A Benchmark for Evaluating Large Code Models on More Complex Code** [[paper](https://arxiv.org/abs/2409.10280)]
- [2024] **ChatGeoAI: Enabling Geospatial Analysis for Public through Natural Language, with Large Language Models** *ISPRS International Journal of Geo-Information* [[paper](https://doi.org/10.3390/ijgi13100348)]
- [2024] **A Preliminary Study of Multilingual Code Language Models for Code Generation Task Using Translated Benchmarks** [[paper](https://arxiv.org/abs/2411.15470)]
- [2024] **SpecEval: Evaluating Code Comprehension in Large Language Models via Program Specifications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.12866)]
- [2024] **Qiskit HumanEval: An Evaluation Benchmark for Quantum Code Generative Models** [[paper](https://doi.org/10.1109/qce60285.2024.00137)]
- [2024] **Fixing Function-Level Code Generation Errors for Foundation Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.00676)]
- [2024] **CoderUJB: An Executable and Unified Java Benchmark for Practical Programming Scenarios** [[paper](https://doi.org/10.1145/3650212.3652115)]
- [2024] **AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.10737)]
- [2024] **Evaluating Language Models for Efficient Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.06450)]
- [2024] **ChatIoT: Zero-code Generation of Trigger-action Based IoT Programs** *Proceedings of the ACM on Interactive Mobile Wearable and Ubiquitous Technologies* [[paper](https://doi.org/10.1145/3678585)]
- [2024] **PPM: Automated Generation of Diverse Programming Problems for Benchmarking Code Generation Models** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3643780)]
- [2024] **Mobile-LLaMA: Instruction Fine-Tuning Open-Source LLM for Network Analysis in 5G Networks** *IEEE Network* [[paper](https://doi.org/10.1109/mnet.2024.3421306)]
- [2024] **Evolutionary Multi-objective Optimization for Contextual Adversarial Example Generation** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3660808)]
- [2024] **DiffCoder: Enhancing Large Language Model on API Invocation via Analogical Code Exercises** *Proceedings of the ACM on software engineering.* [[paper](https://doi.org/10.1145/3643745)]
- [2024] **Comparing Large Language Models and Grammatical Evolution for Code Generation** *Proceedings of the Genetic and Evolutionary Computation Conference Companion* [[paper](https://doi.org/10.1145/3638530.3664162)]
- [2024] **From Effectiveness to Efficiency: Uncovering Linguistic Bias in Large Language Model-based Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.00602)]
- [2024] **CATCODER: Repository-Level Code Generation with Relevant Code and Type Context** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.03283)]
- [2024] **BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.15877)]
- [2024] **Benchmarks and Metrics for Evaluations of Code Generation: A Critical Review** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.12655)]
- [2024] **Benchmarking Llama 3 70B for Code Generation: A Comprehensive Evaluation** *Orclever Proceedings of Research and Development* [[paper](https://doi.org/10.56038/oprd.v4i1.444)]
- [2024] **On Evaluating the Efficiency of Source Code Generated by LLMs** [[paper](https://doi.org/10.1145/3650105.3652295)]
- [2024] **Mutation-based Consistency Testing for Evaluating the Code Understanding Capability of LLMs** [[paper](https://doi.org/10.1145/3644815.3644946)]
- [2024] **Low-Cost Language Models: Survey and Performance Evaluation on Python Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.11160)]
- [2024] **LLM-SR: Scientific Equation Discovery via Programming with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.18400)]
- [2024] **Exploring Multi-Lingual Bias of Large Code Models in Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.19368)]
- [2024] **DevGPT: Studying Developer-ChatGPT Conversations** [[paper](https://doi.org/10.1145/3643991.3648400)]
- [2024] **Code Generation from Flowchart using Optical Character Recognition & Large Language Model** [[paper](https://doi.org/10.36227/techrxiv.171392799.96378624/v1)]
- [2024] **Class-Level Code Generation from Natural Language Using Iterative, Tool-Enhanced Reasoning over Repository** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.01573)]
- [2024] **Automating Research in Business and Technical Communication: Large Language Models as Qualitative Coders** *Journal of Business and Technical Communication* [[paper](https://doi.org/10.1177/10506519241239927)]
- [2024] **An Empirical Comparison of Code Generation Approaches for Ansible** [[paper](https://doi.org/10.1145/3643661.3643951)]
- [2024] **Navigating Confidentiality in Test Automation: A Case Study in LLM Driven Test Data Generation** [[paper](https://doi.org/10.1109/saner60148.2024.00041)]
- [2024] **Hot or Cold? Adaptive Temperature Sampling for Code Generation with Large Language Models** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i1.27798)]
- [2024] **Exploring the Potential of Pre-Trained Language Models of Code for Automated Program Repair** *Electronics* [[paper](https://doi.org/10.3390/electronics13071200)]
- [2024] **Evaluating Large Language Model Code Generation as an Autograding Mechanism for "Explain in Plain English" Questions** [[paper](https://doi.org/10.1145/3626253.3635542)]
- [2024] **Enhancing Code Generation Performance of Smaller Models by Distilling the Reasoning Ability of LLMs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.13271)]
- [2024] **Can LLM Replace Stack Overflow? A Study on Robustness and Reliability of Large Language Model Code Generation** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i19.30185)]
- [2024] **User Centric Evaluation of Code Generation Tools** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.03130)]
- [2024] **Instruction Tuning for Secure Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.09497)]
- [2024] **HumanEval-XL: A Multilingual Code Generation Benchmark for Cross-lingual Natural Language Generalization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.16694)]
- [2024] **CodeMind: Evaluating Large Language Models for Code Reasoning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.09664)]
- [2024] **API Pack: A Massive Multi-Programming Language Dataset for API Call Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.09615)]
- [2024] **Vulnerabilities Introduced by LLMs Through Code Suggestions** [[paper](https://doi.org/10.1007/978-3-031-54827-7_9)]
- [2024] **OOP: Object-Oriented Programming Evaluation Benchmark for Large Language Models** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.808)]
- [2024] **Methodology for Code Synthesis Evaluation of LLMs Presented by a Case Study of ChatGPT and Copilot** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3403858)]
- [2024] **MMCode: Benchmarking Multimodal Large Language Models for Code Generation with Visually Rich Programming Problems** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.42)]
- [2024] **Improving Natural Language Capability of Code Large Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.14242)]
- [2024] **EvoR: Evolving Retrieval for Code Generation** [[paper](https://doi.org/10.18653/v1/2024.findings-emnlp.143)]
- [2024] **Evaluating Large Language Models for Enhanced Fuzzing: An Analysis Framework for LLM-Driven Seed Generation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3484947)]
- [2024] **DeepSeek-Coder: When the Large Language Model Meets Programming -- The Rise of Code Intelligence** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.14196)]
- [2024] **Debug like a Human: A Large Language Model Debugger via Verifying Runtime Execution Step by Step** [[paper](https://doi.org/10.18653/v1/2024.findings-acl.49)]
- [2024] **CodeJudge: Evaluating Code Generation with Large Language Models** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.1118)]
- [2024] **CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges** [[paper](https://doi.org/10.18653/v1/2024.acl-long.737)]
- [2024] **CGGNet: Compiler-Guided Generation Network for Smart Contract Data Augmentation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3427829)]

##### 2023

- [2023] **Turbulence: Systematically and Automatically Testing Instruction-Tuned Large Language Models for Code** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.14856)]
- [2023] **Multilingual Code Co-evolution using Large Language Models** [[paper](https://doi.org/10.1145/3611643.3616350)]
- [2023] **Large Language Models for Code: Security Hardening and Adversarial Testing** [[paper](https://arxiv.org/abs/2302.05319)]
- [2023] **Deep learning in digital health with chatgpt: a study on efficient code generation** *European Heart Journal* [[paper](https://doi.org/10.1093/eurheartj/ehad655.2937)]
- [2023] **CodeScope: An Execution-based Multilingual Multitask Multidimensional Benchmark for Evaluating LLMs on Code Understanding and Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.08588)]
- [2023] **Assessing the Promise and Pitfalls of ChatGPT for Automated Code Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2311.02640)]
- [2023] **A next-generation dynamic programming language Julia: Its features and applications in biological science** *Journal of Advanced Research* [[paper](https://doi.org/10.1016/j.jare.2023.11.015)]
- [2023] **Enhancing Code Language Models for Program Repair by Curricular Fine-tuning Framework** [[paper](https://doi.org/10.1109/icsme58846.2023.00024)]
- [2023] **Discriminating Human-authored from ChatGPT-Generated Code Via Discernable Feature Analysis** [[paper](https://doi.org/10.1109/issrew60843.2023.00059)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2026

- [2026] **«THE IMPACT OF CHATGPT ON THE DEVELOPMENT OF STUDENTS' WRITTEN COMMUNICATION SKILLS»** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21019823)]
- [2026] **Integrating peer support and the use of AI-based writing assistants for improving academic writing in a higher education classroom setting** *Libera Università di Bolzano* [[paper](https://doi.org/10.13124/9788860462077_12)]
- [2026] **Detecting undisclosed LLM-generated content in parliamentary texts** [[paper](https://arxiv.org/abs/2606.14209)]
- [2026] **Assistant, Not the Author: Confronting the Misuse of Artificial Intelligence in Academic Writing** *Journal of Diverse Medical Research Medicosphere* [[paper](https://doi.org/10.33005/jdiversemedres.v3i6.357)]
- [2026] **Pendampingan Literasi AI Akademik Berbasis NotebookLM bagi Komunitas Pemerhati Publikasi Ilmiah dalam Meningkatkan Produktivitas Penulisan Karya Ilmiah** *ASPIRASI Publikasi Hasil Pengabdian dan Kegiatan Masyarakat* [[paper](https://doi.org/10.61132/aspirasi.v4i3.2775)]
- [2026] **Academic Writing in the Age of AI : Potentials, Problems, and Praxis** *Journal of Adolescent & Adult Literacy* [[paper](https://doi.org/10.1002/jaal.70056)]
- [2026] **AI writing assistants as intralingual translation tools: Rethinking mediation and translation competence in L2 academic writing** [[paper](https://doi.org/10.65987/jdy254)]
- [2026] **HalluCiteChecker: A Lightweight Toolkit for Hallucinated Citation Detection and Verification in the Era of AI Scientists** [[paper](https://arxiv.org/abs/2604.26835)]
- [2026] **Can an AI assistant handle the tedious parts of academic writing?** [[paper](https://doi.org/10.59350/vj2m3-s2t36)]
- [2026] **Chatbots and virtual assistants in higher education: supporting academic writing and research** *EDUWEB* [[paper](https://doi.org/10.46502/issn.1856-7576/2026.20.01.23)]
- [2026] **Integrating AI in Educational Research Methodologies** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-3373-2752-5.ch015)]
- [2026] **Role and Challenges of AI Assistants in Academic Writing** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6292321)]
- [2026] **Perception of Using ChatGPT in Academic Writing in Peruvian University Students** *Smart innovation, systems and technologies* [[paper](https://doi.org/10.1007/978-3-032-09911-2_12)]
- [2026] **Pelatihan Pemanfaatan Artificial Intelligences Deepseek dalam Menurunkan Plagiasi Artikel Ilmiah bagi Mahasiswa Baru** *Jurnal Pengabdian Masyarakat (abdira)* [[paper](https://doi.org/10.31004/abdira.v6i1.1602)]
- [2026] **LLM or Human? Perceptions of Trust and Information Quality in Research Summaries** [[paper](https://arxiv.org/abs/2601.15556)]
- [2026] **Exploring Libyan PhD Students' Awareness and Use (AI) Based Conversational Agents and Speech Technologies to Improve Academic Writing** *International Science and Technology Journal* [[paper](https://doi.org/10.62341/anas9514)]
- [2026] **Artificial Intelligence in Academic Writing: Productivity Tool or Threat to Academic Integrity?** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6378858)]

##### 2025

- [2025] **Utilization of Artificial Intelligence Tools in Engineering Education among HEIs in Eastern Visayas, Philippines** *International Journal of Learning Teaching and Educational Research* [[paper](https://doi.org/10.26803/ijlter.24.12.32)]
- [2025] **The Summative Assessment of Generative AI Usage within Academic Writing in a Computing Foundation Year** [[paper](https://doi.org/10.1145/3772338.3772347)]
- [2025] **Carrying the light forward: Honouring Professor Li Liu's vision for Asian Social Psychology** *Asian Journal Of Social Psychology* [[paper](https://doi.org/10.1111/ajsp.70071)]
- [2025] **Balancing Innovation and Integrity: Ethical Guidelines for Ai Integration in Tertiary Education in Mwanza, Tanzania** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17670643)]
- [2025] **AcademAI: An Intelligent Framework for Automated Research Synthesis and Conference Recommendation** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2025.75949)]
- [2025] **Research Writing, Ghostwriting and Academic Cheating in the Age of AI: A Scoping Review** *International Conference on Education Research* [[paper](https://doi.org/10.34190/icer.2.1.4302)]
- [2025] **Artificial Intelligence in Education and Scientific Research: "Present Challenges and Future Opportunities"** *Libyan Journal of Medical and Applied Sciences* [[paper](https://doi.org/10.64943/ljmas.v3i3.108)]
- [2025] **Exploring the Use of ChatGPT in Academic Writing: A Systematic Literature Review on Undergraduates’ Perceptions** [[paper](https://doi.org/10.31235/osf.io/nhc9u_v1)]
- [2025] **Human-LLM Coevolution: Evidence from Academic Writing** [[paper](https://arxiv.org/abs/2502.09606)]
- [2025] **Writing Workshop: AI-powered Academic Assistant for Research and Publication (ChatGPT + Scite)** *UiTM Institutional Repositories (Universiti Teknologi MARA)* [[paper](https://ir.uitm.edu.my/id/eprint/132151/1/132151.pdf)]
- [2025] **Understanding How Paper Writers Use AI-Generated Captions in Figure Caption Writing** *AAAI 2025 Workshop* [[paper](https://arxiv.org/abs/2501.06317)]
- [2025] **The Role of Artificial Intelligence in Enhancing Human Longevity: Mitigating Cognitive Overload for Extended Lifespan Among Master’s Students in Mathematics at the Catholic University of Ghana** *International Journal of Research and Innovation in Social Science* [[paper](https://doi.org/10.47772/ijriss.2025.905000236)]
- [2025] **EMPOWERING FIRST-YEAR UNIVERSITY STUDENTS: INTEGRATING AI-POWERED WRITING ASSISTANTS IN ACADEMIC WRITING COURSES** [[paper](https://doi.org/10.20472/iac.2025.066.006)]
- [2025] **AI and the Emergence of New Academic Writing Literacies: Graduate Student Perspectives on its Affordances and Challenges** [[paper](https://doi.org/10.1007/978-3-032-01210-4_13)]

##### 2024

- [2024] **The Integration of ChatGPT in English for Foreign Language Course: Elevating AI Writing Assistant Acceptance** *Computers in the Schools* [[paper](https://doi.org/10.1080/07380569.2024.2446239)]
- [2024] **NLLG Quarterly arXiv Report 09/24: What are the most influential current AI Papers?** [[paper](https://arxiv.org/abs/2412.12121)]
- [2024] **Is artificial intelligence for everyone? Analyzing the role of ChatGPT as a writing assistant for medical students** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2024.1457744)]
- [2024] **Legality vs Legitimacy: Can AI-Written Papers Uphold the Spirit of Academic Integrity?** *Physical Education Health and Social Sciences* [[paper](https://doi.org/10.63163/jpehss.v2i4.537)]
- [2024] **ChatGPT, a new “Ghostwriter”: A teacher-and-students poetic autoethnography from an EMI academic writing class** *Digital Applied Linguistics* [[paper](https://doi.org/10.29140/dal.v1.2244)]
- [2024] **AIGS: Generating Science from AI-Powered Automated Falsification** [[paper](https://arxiv.org/abs/2411.11910)]
- [2024] **SparkRA: A Retrieval-Augmented Knowledge Service System Based on Spark Large Language Model** [[paper](https://arxiv.org/abs/2408.06574)]
- [2024] **LLM-DetectAIve: a Tool for Fine-Grained Machine-Generated Text Detection** [[paper](https://arxiv.org/abs/2408.04284)] [[code](https://github.com/mbzuai-nlp/LLM-DetectAIve)]
- [2024] **Future of Writing in Higher Education** [[paper](https://doi.org/10.1201/9781003400691-7)]
- [2024] **Generative artificial intelligence in dentistry: Current approaches and future challenges** [[paper](https://arxiv.org/abs/2407.17532)]
- [2024] **Exploring students’ perspectives on Generative AI-assisted academic writing** *Education and Information Technologies* [[paper](https://doi.org/10.1007/s10639-024-12878-7)]
- [2024] **Delving into the Utilisation of ChatGPT in Scientific Publications in Astronomy** [[paper](https://arxiv.org/abs/2406.17324)]
- [2024] **Delving into LLM-assisted writing in biomedical publications through excess vocabulary** [[paper](https://arxiv.org/abs/2406.07016)]
- [2024] **Using ChatGPT effectively for academic writing: An auto-ethnographical report** [[paper](https://doi.org/10.35542/osf.io/bxtes)]
- [2024] **Falcon 7b for Software Mention Detection in Scholarly Documents** [[paper](https://arxiv.org/abs/2405.08514)]
- [2024] **OverleafCopilot: Empowering Academic Writing in Overleaf with Large Language Models** [[paper](https://arxiv.org/abs/2403.09733)] [[code](https://github.com/wenhaomin/ChatGPT-PromptGenius)]
- [2024] **Shallow Synthesis of Knowledge in GPT-Generated Texts: A Case Study in Automatic Related Work Composition** [[paper](https://arxiv.org/abs/2402.12255)]
- [2024] **Artificial intelligence (AI) in psychology: a commentary on AI’s emerging role and the ensuing conversation** *South African Journal of Psychology* [[paper](https://doi.org/10.1177/00812463231223427)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Faculty perceptions of ChatGPT on academic integrity and institutional roles in higher education** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-63852-x)]
- [2026] **ADVANCE RESEARCH METHODOLOGY IN THE AGE OF AI** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21525777)]
- [2026] **In-Situ Immersive Analytics Authoring through Ergonomic Keyboard Support** [[paper](https://arxiv.org/abs/2606.08927)]
- [2026] **From Code Generation to Conceptual Learning: Student Use of LLMs in a Web Programming Course** [[paper](https://doi.org/10.1145/3772318.3793207)]
- [2026] **Authority and inquiry in the age of generative AI** *Proceedings of the International Conference on Networked Learning* [[paper](https://doi.org/10.54337/nlc.v15.10967)]
- [2026] **AI-Based Learning Tool Utilization and Academic Performance in Science, Technology, and Society (STS)** *Psychology and Education A Multidisciplinary Journal* [[paper](https://doi.org/10.70838/pemj.550208)]
- [2026] **The Role of Artificial Intelligence in Advancing Academic Research in Tertiary Institutions** *International Journal of Social Sciences Language and Linguistics* [[paper](https://doi.org/10.55640/ijssll-06-03-07)]
- [2026] **Meflex: A Multi-agent Scaffolding System for Entrepreneurial Ideation Iteration via Nonlinear Business Plan Writing** [[paper](https://arxiv.org/abs/2602.15631)]
- [2026] **Hierarchical Embedding Fusion for Retrieval-Augmented Code Generation** [[paper](https://arxiv.org/abs/2603.06593)]
- [2026] **Effects of an AI-Based Writing Assistant on First-Language Writing Performance and Self-Regulation: Evidence from a Mixed Methods Study** *European Journal of Educational Research* [[paper](https://doi.org/10.12973/eu-jer.15.2.669)]
- [2026] **Users Mispredict Their Own Preferences for AI Writing Assistance** [[paper](https://arxiv.org/abs/2601.04461)]

##### 2025

- [2025] **PAGE: Prompt Augmentation for text Generation Enhancement** [[paper](https://arxiv.org/abs/2510.13880)]
- [2025] **Authors self-disclosed use of artificial intelligence in research submissions to 49 biomedical journals: A cross-sectional study** *medRxiv* [[paper](https://doi.org/10.1101/2025.10.24.25338574)]
- [2025] **Assessing Awareness and Usage of AI Tools Among Faculty and Learners in Higher Education Institutions in Sub‑Saharan Africa** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17316893)]
- [2025] **Artificial Intelligence and Critical Thinking in University Students** *Journal of Biomedical Research & Environmental Sciences* [[paper](https://doi.org/10.37871/jbres2137)]
- [2025] **Does It Make Sense to Speak of Introspection in Large Language Models?** [[paper](https://arxiv.org/abs/2506.05068)]
- [2025] **Inteligencia Artificial y Pensamiento Crítico en Estudiantes Universitarios** [[paper](https://doi.org/10.1590/scielopreprints.11558)]
- [2025] **Thoughtful, Confused, or Untrustworthy: How Text Presentation Influences Perceptions of AI Writing Tools** [[paper](https://arxiv.org/abs/2504.20365)]
- [2025] **CKGFuzzer: LLM-Based Fuzz Driver Generation Enhanced By Code Knowledge Graph** [[paper](https://doi.org/10.1109/icse-companion66252.2025.00079)]
- [2025] **College Students' Use and Perceptions of Artificial Intelligence (AI): A Survey Study** *Journal of college student development* [[paper](https://doi.org/10.1353/csd.2025.a962923)]
- [2025] **Simulating Errors in Touchscreen Typing** [[paper](https://arxiv.org/abs/2502.03560)]
- [2025] **Finding Missed Code Size Optimizations in Compilers using Large Language Models** [[paper](https://doi.org/10.1145/3708493.3712686)]

##### 2024

- [2024] **Tailoring Your Code Companion: Leveraging LLMs and RAG to Develop a Chatbot to Support Students in a Programming Course** [[paper](https://doi.org/10.1109/tale62452.2024.10834365)]
- [2024] **SPICE: Smart Projection Interface for Cooking Enhancement** [[paper](https://arxiv.org/abs/2412.03551)]
- [2024] **Editorial: The “publish and perish” phenomenon: how journals can be affected by it and survive** *RAUSP Management Journal* [[paper](https://doi.org/10.1108/rausp-07-2024-280)]
- [2024] **GAZEploit: Remote Keystroke Inference Attack by Gaze Estimation from Avatar Views in VR/MR Devices** [[paper](https://arxiv.org/abs/2409.08122)]
- [2024] **Analyzing the Use of AI Writing Assistants in Generating Texts with Standard American English Conventions: A Case Study of ChatGPT and Bard** *The CATESOL journal.* [[paper](https://doi.org/10.5070/b5.25364)]
- [2024] **Instructor Perceptions of AI Code Generation Tools - A Multi-Institutional Interview Study** [[paper](https://doi.org/10.1145/3626252.3630880)]
- [2024] **Artificial Intelligence to Automate Network Meta-Analyses: Four Case Studies to Evaluate the Potential Application of Large Language Models** *PharmacoEconomics - Open* [[paper](https://doi.org/10.1007/s41669-024-00476-9)]

##### 2023

- [2023] **Generation Z's Ability to Discriminate Between AI-generated and Human-Authored Text on Discord** [[paper](https://arxiv.org/abs/2401.04120)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2026

- [2026] **From Typing to Vibes: a Systematic Review of AI Programming Assistants and Natural Language Programming in Introductory Programming Courses** *Aaltodoc (Aalto University)* [[paper](https://aaltodoc.aalto.fi/handle/123456789/146083)]
- [2026] **Large language models for code generation: A survey** *Computer Standards & Interfaces* [[paper](https://doi.org/10.1016/j.csi.2026.104165)]
- [2026] **A framework for assessing the capabilities of code generation of constraint domain-specific languages with large language models** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2026.112871)]
- [2026] **Evaluating large language models for generating programming questions from code** *Pollack Periodica* [[paper](https://doi.org/10.1556/606.2025.01471)]
- [2026] **Bridging Online and Offline RL: Contextual Bandit Learning for Multi-Turn Code Generation** [[paper](https://arxiv.org/abs/2602.03806)] [[code](https://github.com/OSU-NLP-Group/cobalt)]

##### 2025

- [2025] **Towards a next-generation LLM empowered low-code programming industrial robotic system for human-centric smart manufacturing** *Journal of Manufacturing Systems* [[paper](https://doi.org/10.1016/j.jmsy.2025.10.012)]
- [2025] **Empirical Analysis of AI-Assisted Code Generation Tools Impact on Code Quality, Security and Developer Productivity** *International Journal For Multidisciplinary Research* [[paper](https://doi.org/10.36948/ijfmr.2025.v07i06.61350)]
- [2025] **Towards Secure Code Generation With LLMs: A Study on Common Weakness Enumeration** *IEEE Transactions on Software Engineering* [[paper](https://doi.org/10.1109/tse.2025.3619281)]
- [2025] **Technological Stages of Neural Network AI Generation of System Program Code Based on Modular Neuro Integration** *American Journal of Embedded Systems and Applications* [[paper](https://doi.org/10.11648/j.ajesa.20251001.12)]
- [2025] **LLM-based Iterative Refinement of Finite-State Machines with STPA Controller Constraints and Generation of IEC 61499 Code** [[paper](https://doi.org/10.1109/etfa65518.2025.11205687)]
- [2025] **Hybrid Modal Decoupled Fusion for Stable Multilingual Code Generation** [[paper](https://doi.org/10.1145/3773365.3773431)]
- [2025] **Automatic Code Generation Techniques: A Systematic Literature Review** *Automated Software Engineering* [[paper](https://doi.org/10.1007/s10515-025-00551-3)]
- [2025] **On the performance of large language models on introductory programming assignments** *Journal of Intelligent Information Systems* [[paper](https://doi.org/10.1007/s10844-025-00968-y)]
- [2025] **MetaIndux-PLC: A Control Logic-Guided LLM for PLC code generation in industrial control systems** *Applied Soft Computing* [[paper](https://doi.org/10.1016/j.asoc.2025.113673)]
- [2025] **Automated Malware Source Code Generation via Uncensored LLMs and Adversarial Evasion of Censored Model** *Applied Sciences* [[paper](https://doi.org/10.3390/app15179252)]
- [2025] **Usage of Large Language Model for Code Generation Tasks: A Review** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-025-04241-5)]
- [2025] **Analyzing the dependability of Large Language Models for code clone generation** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2025.112548)]
- [2025] **``I Would Have Written My Code Differently': Beginners Struggle to Understand LLM-Generated Code** [[paper](https://arxiv.org/abs/2504.19037)]
- [2025] **HPC-Coder-v2: Studying Code LLMs Across Low-Resource Parallel Languages** [[paper](https://doi.org/10.23919/isc.2025.11017585)]
- [2025] **CoSEFA: An LLM-Based Programming Assistant for Secure Code Generation via Supervised Co-Decoding** [[paper](https://doi.org/10.1145/3696630.3728609)]
- [2025] **Generative AI in Software Engineering: Revolutionizing Code Generation and Debugging** *International Journal of Computational and Experimental Science and Engineering* [[paper](https://doi.org/10.22399/ijcesen.1718)]
- [2025] **AI vs. Human Programmers: Complexity and Performance in Code Generation** *VAWKUM Transactions on Computer Sciences* [[paper](https://doi.org/10.21015/vtcs.v13i1.2043)]
- [2025] **How Scientists Use Large Language Models to Program** [[paper](https://arxiv.org/abs/2502.17348)]
- [2025] **Evaluating Large Language Models for Code Generation: A Comparative Study on Python, Java, and Swift** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2025.tj22242)]
- [2025] **Beyond Code Generation: LLM-supported Exploration of the Program Design Space** [[paper](https://arxiv.org/abs/2503.06911)]
- [2025] **AI-Powered, But Power-Hungry? Energy Efficiency of LLM-Generated Code** [[paper](https://doi.org/10.1109/forge66646.2025.00012)]
- [2025] **Program Code Generation: Single LLMs vs. Multi-Agent Systems** [[paper](https://doi.org/10.1109/icnlp65360.2025.11108400)]
- [2025] **Evaluating the Impact of Generative AI on Intelligent Programming Assistance and Code Quality.** *Power System Technology* [[paper](https://doi.org/10.52783/pst.1668)]
- [2025] **Ensemble Learning for Large Language Models in Text and Code Generation: A Survey** [[paper](https://arxiv.org/abs/2503.13505)]
- [2025] **PWCT2: A Self-Hosting Visual Programming Language Based on Ring with Interactive Textual-to-Visual Code Conversion** *Applied Sciences* [[paper](https://doi.org/10.3390/app15031521)]
- [2025] **Mass Generation of Programming Learning Problems from Public Code Repositories** *Big Data and Cognitive Computing* [[paper](https://doi.org/10.3390/bdcc9030057)]
- [2025] **CodeSCM: Causal Analysis for Multi-Modal Code Generation** [[paper](https://arxiv.org/abs/2502.05150)]
- [2025] **Code-level quantum circuit generation based on large language models** *Zhongguo kexue. Wulixue Lixue Tianwenxue* [[paper](https://doi.org/10.1360/sspma-2024-0594)]
- [2025] **CoCoEvo: Co-Evolution of Programs and Test Cases to Enhance Code Generation** [[paper](https://doi.org/10.36227/techrxiv.173930984.47381789/v1)]
- [2025] **Breaking the Programming Language Barrier: Multilingual Prompting to Empower Non-Native English Learners** [[paper](https://doi.org/10.1145/3716640.3716649)]
- [2025] **An Empirical Study of Retrieval-Augmented Code Generation: Challenges and Opportunities** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3717061)]
- [2025] **Top Pass: improve code generation by pass@k-maximized code ranking** *Frontiers of Computer Science* [[paper](https://doi.org/10.1007/s11704-024-40415-9)]
- [2025] **The Current Challenges of Software Engineering in the Era of Large Language Models** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3712005)]
- [2025] **Next-Gen Service Function Chain Deployment: Combining Multi-Objective Optimization With AI Large Language Models** *IEEE Network* [[paper](https://doi.org/10.1109/mnet.2025.3532212)]
- [2025] **Large Language Model Guided Self-Debugging Code Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5396508)]
- [2025] **Language Models for Code Optimization: Survey, Challenges and Future Directions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.01277)]
- [2025] **Investigating the Transferability of Code Repair for Low-Resource Programming Languages** [[paper](https://doi.org/10.18653/v1/2025.findings-naacl.190)]
- [2025] **Integration of CAD Software Programming for G-code Generation** *SpringerBriefs in applied sciences and technology* [[paper](https://doi.org/10.1007/978-3-031-78747-8_5)]
- [2025] **Beyond Text: Implementing Multimodal Large Language Model-Powered Multi-Agent Systems Using a No-Code Platform** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.00750)]
- [2025] **Automatic Evaluation of Programming Tasks Supported by Language Models** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3601448)]
- [2025] **Assessing and Analyzing the Correctness of GitHub Copilot’s Code Suggestions** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3715108)]
- [2025] **Asleep at the Keyboard? Assessing the Security of GitHub Copilot’s Code Contributions** *Communications of the ACM* [[paper](https://doi.org/10.1145/3610721)]

##### 2024

- [2024] **Robustness evaluation of code generation systems via concretizing instructions** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2024.107645)]
- [2024] **Evaluating LLMs for Code Generation in HRI: A Comparative Study of ChatGPT, Gemini, and Claude** *Applied Artificial Intelligence* [[paper](https://doi.org/10.1080/08839514.2024.2439610)]
- [2024] **Enhancing Code LLMs with Reinforcement Learning in Code Generation: A Survey** [[paper](https://arxiv.org/abs/2412.20367)]
- [2024] **Comparing Large Language Models and Human Programmers for Generating Programming Code** *Advanced Science* [[paper](https://doi.org/10.1002/advs.202412279)]
- [2024] **Code Generation Templates for Accelerating Chatbot Development in Smart Tourism** [[paper](https://doi.org/10.1109/commnet63022.2024.10793260)]
- [2024] **AutoIoT: Automated IoT Platform Using Large Language Models** *IEEE Internet of Things Journal* [[paper](https://doi.org/10.1109/jiot.2024.3523907)]
- [2024] **A survey on the application of large language models in software engineering** *Computer Research and Modeling* [[paper](https://doi.org/10.20537/2076-7633-2024-16-7-1715-1726)]
- [2024] **A Systematic Literature Review of 10 years of Research on Program Synthesis and Natural Language Processing** *Programming and Computer Software* [[paper](https://doi.org/10.1134/s0361768824700737)]
- [2024] **“Ok Pal, we have to code that now”: interaction patterns of programming beginners with a conversational chatbot** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-024-10561-6)]
- [2024] **Poster: Enabling IoT Application Programming in Natural Language with IoTPilot** [[paper](https://doi.org/10.1145/3666025.3699429)]
- [2024] **Type-Safe Code Generation with Algebraic Effects and Handlers** [[paper](https://doi.org/10.1145/3689484.3690731)]
- [2024] **State of the Art of the Security of Code Generated by LLMs: A Systematic Literature Review** [[paper](https://doi.org/10.1109/conisoft63288.2024.00050)]
- [2024] **Large Language Models as Code Executors: An Exploratory Study** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.06667)]
- [2024] **Evaluation of Large Language Models for Unit Test Generation** [[paper](https://doi.org/10.1109/asyu62119.2024.10756954)]
- [2024] **Ansible Lightspeed: A Code Generation Service for IT Automation** [[paper](https://doi.org/10.1145/3691620.3695277)]
- [2024] **AUTOGENICS: Automated Generation of Context-Aware Inline Comments for Code Snippets on Programming Q&A Sites Using LLM** [[paper](https://doi.org/10.1109/scam63643.2024.00013)]
- [2024] **Towards Effective Validation and Integration of LLM-Generated Code** [[paper](https://doi.org/10.1109/vl/hcc60511.2024.00051)]
- [2024] **No Man is an Island: Towards Fully Automatic Programming by Code Search, Code Generation and Program Repair** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.03267)]
- [2024] **Harnessing the Power of Large Language Models for Automated Code Generation and Verification** *Robotics* [[paper](https://doi.org/10.3390/robotics13090137)]
- [2024] **Exploring the problems, their causes and solutions of AI pair programming: A study on GitHub and Stack Overflow** *Journal of Systems and Software* [[paper](https://doi.org/10.1016/j.jss.2024.112204)]
- [2024] **Automated Control Logic Test Case Generation using Large Language Models** [[paper](https://doi.org/10.1109/etfa61755.2024.10711016)]
- [2024] **A search-and-fill strategy to code generation for complex software requirements** *Information and Software Technology* [[paper](https://doi.org/10.1016/j.infsof.2024.107584)]
- [2024] **Unleashing offensive artificial intelligence: Automated attack technique code generation** *Computers & Security* [[paper](https://doi.org/10.1016/j.cose.2024.104077)]
- [2024] **LLM-Cloud Complete: Leveraging Cloud Computing for Efficient Large Language Model-based Code Completion** *Journal of Artificial Intelligence General science (JAIGS) ISSN 3006-4023* [[paper](https://doi.org/10.60087/jaigs.v5i1.200)]
- [2024] **Evaluating Large Language Models using Arabic Prompts to Generate Python Codes** [[paper](https://doi.org/10.1109/esmarta62850.2024.10638877)]
- [2024] **Closure-Free Functional Programming in a Two-Level Type Theory** *Proceedings of the ACM on Programming Languages* [[paper](https://doi.org/10.1145/3674648)]
- [2024] **Analysis of Natural language processing for code generation by using COPRAS Method** *REST Journal on Data Analytics and Artificial Intelligence* [[paper](https://doi.org/10.46632/jdaai/3/1/8)]
- [2024] **A Hybrid Approach of No-Code Robot Programming for Agile Production: Integrating Finger-Gesture and Point Cloud** [[paper](https://doi.org/10.1109/ro-man60168.2024.10731334)]
- [2024] **Unit Test Generation using Large Language Models for Unity Game Development** [[paper](https://doi.org/10.1145/3663532.3664466)]
- [2024] **Revisiting the Impact of Pursuing Modularity for Code Generation** [[paper](https://arxiv.org/abs/2407.11406)]
- [2024] **Comparative Study of AI Code Generation Tools: Quality Assessment and Performance Analysis** *LatIA* [[paper](https://doi.org/10.62486/latia2024104)]
- [2024] **Combining Constraint Programming Reasoning with Large Language Model Predictions** [[paper](https://arxiv.org/abs/2407.13490)]
- [2024] **ChatGPT Code Detection: Techniques for Uncovering the Source of Code** *AI* [[paper](https://arxiv.org/abs/2405.15512)]
- [2024] **Significant Productivity Gains through Programming with Large Language Models** *Proceedings of the ACM on Human-Computer Interaction* [[paper](https://doi.org/10.1145/3661145)]
- [2024] **SPROUT: An Interactive Authoring Tool for Generating Programming Tutorials With the Visualization of Large Language Models** *IEEE Transactions on Visualization and Computer Graphics* [[paper](https://doi.org/10.1109/tvcg.2024.3410523)]
- [2024] **MPIrigen: MPI Code Generation through Domain-Specific Language Models** [[paper](https://doi.org/10.1145/3660605.3660944)]
- [2024] **Large language model-based code generation for the control of construction assembly robots: A hierarchical generation approach** *Developments in the Built Environment* [[paper](https://doi.org/10.1016/j.dibe.2024.100488)]
- [2024] **Investigation and Implementation of AI-HDLCoder for Automated VHDL Code Synthesis and Code Generation for Hardware SoC Development** [[paper](https://doi.org/10.1109/issc61953.2024.10602909)]
- [2024] **Intertwining CP and NLP: The Generation of Unreasonably Constrained Sentences** [[paper](https://arxiv.org/abs/2406.15473)]
- [2024] **GitHub Copilot: the perfect Code compLeeter?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2406.11326)]
- [2024] **CodeGemma: Open Code Models Based on Gemma** [[paper](https://arxiv.org/abs/2406.11409)]
- [2024] **An Investigation into Misuse of Java Security APIs by Large Language Models** [[paper](https://doi.org/10.1145/3634737.3661134)]
- [2024] **The Impact of Large Language Models on Programming Education and Student Learning Outcomes** *Applied Sciences* [[paper](https://doi.org/10.3390/app14104115)]
- [2024] **Synergizing human expertise and AI efficiency with language model for microscopy operation and automated experiment design *** *Machine Learning Science and Technology* [[paper](https://doi.org/10.1088/2632-2153/ad52e9)]
- [2024] **Granite Code Models: A Family of Open Foundation Models for Code Intelligence** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.04324)]
- [2024] **Generating and Reviewing Programming Codes with Large Language Models: A Systematic Mapping Study** [[paper](https://doi.org/10.1145/3658271.3658342)]
- [2024] **Developing Critical Thinking Practices Interwoven with Generative AI Usage in an Introductory Programming Course** [[paper](https://doi.org/10.1109/educon60312.2024.10578746)]
- [2024] **Code Generation Using NLP and AI Based Techniques** *International Research Journal of Modernization in Engineering Technology and Science* [[paper](https://doi.org/10.56726/irjmets56402)]
- [2024] **Are We Testing or Being Tested? Exploring the Practical Applications of Large Language Models in Software Testing** [[paper](https://doi.org/10.1109/icst60714.2024.00039)]
- [2024] **Toward Artificial Intelligence-Human Paired Programming: A Review of the Educational Applications and Research on Artificial Intelligence Code-Generation Tools** *Journal of Educational Computing Research* [[paper](https://doi.org/10.1177/07356331241240460)]
- [2024] **RepairCAT: Applying Large Language Model to Fix Bugs in AI-Generated Programs** [[paper](https://doi.org/10.1145/3643788.3648020)]
- [2024] **KareCoder: A New Knowledge-Enriched Code Generation System** [[paper](https://doi.org/10.1145/3639478.3643076)]
- [2024] **A Model-Driven Architecture Approach to Accelerate Software Code Generation** [[paper](https://doi.org/10.1109/icosse62619.2024.00012)]
- [2024] **When Do Program-of-Thought Works for Reasoning?** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v38i16.29721)]
- [2024] **Natural Language Programming towards Solving Addition-Subtraction Word Problems for assessing AI-based offensive code generators** [[paper](https://dx.doi.org/10.1109/icdecs59733.2023.10503103)]
- [2024] **The “Code” of Ethics: A Holistic Audit of AI Code Generators** *IEEE Transactions on Dependable and Secure Computing* [[paper](https://doi.org/10.1109/tdsc.2024.3367737)]
- [2024] **Framework for evaluating code generation ability of large language models** *ETRI Journal* [[paper](https://doi.org/10.4218/etrij.2023-0357)]
- [2024] **Copilot Evaluation Harness: Evaluating LLM-Guided Software Programming** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.14261)]
- [2024] **Refining ChatGPT-Generated Code: Characterizing and Mitigating Code Quality Issues** *ACM Transactions on Software Engineering and Methodology* [[paper](https://doi.org/10.1145/3643674)]
- [2024] **Human Versus Machine Intelligence: Assessing Natural Language Generation Models Through Complex Systems Theory** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2024.3358168)]
- [2024] **Flexibility and Productivity in IoT Programming: A Case Study with Mruby** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-48855-9_2)]
- [2024] **Evaluation Metrics in LLM Code Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-70563-2_17)]
- [2024] **Development of a Modularized Undergraduate Data Science and Big Data Curricular Using No-Code Software Development Tools** *IEEE Access* [[paper](https://doi.org/10.1109/access.2024.3429241)]
- [2024] **Code Security Vulnerability Repair Using Reinforcement Learning with Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.07031)]
- [2024] **Clover: Closed-Loop Verifiable Code Generation** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-031-65112-0_7)]
- [2024] **A Sketch of DSL and Code Generator for Accelerating Chatbot Development** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2024.09.199)]
- [2024] **A Comparative Study of AI-Generated (GPT-4) and Human-crafted MCQs in Programming Education** [[paper](https://arxiv.org/abs/2312.03173)]

##### 2023

- [2023] **DeceptPrompt: Exploiting LLM-driven Code Generation via Adversarial Natural Language Instructions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2312.04730)]
- [2023] **Protecting Intellectual Property of Large Language Model-Based Code Generation APIs via Watermarks** [[paper](https://doi.org/10.1145/3576915.3623120)]
- [2023] **Can ChatGPT support software verification?** [[paper](https://arxiv.org/abs/2311.02433)]
- [2023] **Poisoning Programs by Un-Repairing Code: Security Concerns of AI-generated Code** [[paper](https://arxiv.org/abs/2403.06675)]
- [2023] **Extending Isabelle/HOL's Code Generator with support for the Go programming language** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.02704)]
- [2023] **CodeFusion: A Pre-trained Diffusion Model for Code Generation** [[paper](https://arxiv.org/abs/2310.17680)]
- [2023] **CoLadder: Supporting Programmers with Hierarchical Code Generation in Multi-Level Abstraction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2310.08699)]
- [2023] **A syntax-guided multi-task learning approach for Turducken-style code generation** *Empirical Software Engineering* [[paper](https://doi.org/10.1007/s10664-023-10372-1)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2026

- [2026] **Where did the ambiguity go? Examining how multimodal models interpret polysemous words** [[paper](https://arxiv.org/abs/2608.00410)]
- [2026] **MindAlign: Decoding Inner Speech from fMRI Signals via Multimodal Embedding Alignment under Limited Data** [[paper](https://arxiv.org/abs/2606.20696)]
- [2026] **Navigating Language Pedagogy through Digital Interfaces: A Pathway to Inclusive and Multilingual Classrooms** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18329114)]
- [2026] **Intelligent Systems for Academic Research Integration: An Offline and Multimodal Brainstorming Partner for Scholarly Inquiry** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6899067)]

##### 2025

- [2025] **UniRL-Zero: Reinforcement Learning on Unified Models with Joint Language Model and Diffusion Model Experts** [[paper](https://arxiv.org/abs/2510.17937)] [[code](https://github.com/G-U-N/UniRL)]
- [2025] **UALM: Unified Audio Language Model for Understanding, Generation and Reasoning** [[paper](https://arxiv.org/abs/2510.12000)]
- [2025] **ToolMem: Enhancing Multimodal Agents with Learnable Tool Capability Memory** [[paper](https://arxiv.org/abs/2510.06664)]
- [2025] **Intelligent Agents with Emotional Intelligence: Current Trends, Challenges, and Future Prospects** [[paper](https://arxiv.org/abs/2511.20657)]
- [2025] **Emotion Detection Using Conditional Generative Adversarial Networks (cGAN): A Deep Learning Approach** [[paper](https://arxiv.org/abs/2508.04481)]
- [2025] **Efficient Interleaved Speech Modeling through Knowledge Distillation** [[paper](https://arxiv.org/abs/2506.23670)]
- [2025] **Document-Level Text Generation with Minimum Bayes Risk Decoding using Optimal Transport** [[paper](https://arxiv.org/abs/2505.23078)] [[code](https://github.com/jinnaiyuu/mbr-optimal-transport)]
- [2025] **GazeLLM: Multimodal LLMs incorporating Human Visual Attention** [[paper](https://arxiv.org/abs/2504.00221)]

##### 2024

- [2024] **Typhoon 2: A Family of Open Text and Multimodal Thai Large Language Models** [[paper](https://arxiv.org/abs/2412.13702)]
- [2024] **Explainable and Interpretable Multimodal Large Language Models: A Comprehensive Survey** [[paper](https://arxiv.org/abs/2412.02104)]
- [2024] **LLaMo: Large Language Model-based Molecular Graph Assistant** [[paper](https://arxiv.org/abs/2411.00871)] [[code](https://github.com/mlvlab/LLaMo)]
- [2024] **Accented Character Entry Using Physical Keyboards in Virtual Reality** [[paper](https://arxiv.org/abs/2409.01709)]
- [2024] **PSLM: Parallel Generation of Text and Speech with LLMs for Low-Latency Spoken Dialogue Systems** [[paper](https://arxiv.org/abs/2406.12428)] [[project](https://rinnakk.github.io/research/publications/PSLM)]
- [2024] **Zipper: A Multi-Tower Decoder Architecture for Fusing Modalities** *NeurIPS* [[paper](https://arxiv.org/abs/2405.18669)]
- [2024] **Emergency Department Decision Support using Clinical Pseudo-notes** [[paper](https://arxiv.org/abs/2402.00160)]

##### 2023

- [2023] **VLIS: Unimodal Language Models Guide Multimodal Language Generation** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.09767)]
- [2023] **EasyGen: Easing Multimodal Generation with BiDiffuser and LLMs** [[paper](https://arxiv.org/abs/2310.08949)] [[code](https://github.com/zxy556677/EasyGen)]

[⬆ Back to top](#paper-list)

### Surveys & Taxonomies

#### LLM Evaluation

##### 2026

- [2026] **Study on the Association Between Generative Artificial Intelligence and the Reshaping of Learning Among Undergraduate Architecture Students—A Case Study of Eight Universities in Wuhan, China** *Buildings* [[paper](https://doi.org/10.3390/buildings16142800)]
- [2026] **Morphological Priors and Photogrammetric Conditioning for Auditable Generative 3D Miao and Dong Timber Heritage Scenes** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-10008303/v1)]
- [2026] **Federated Deep Learning and TinyML Co-Design for Securing Resource-Constrained IoT and SCADA Networks: A PRISMA-Compliant Systematic Review, Taxonomy and Statistical Meta-Analysis** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-10299029/v1)]
- [2026] **A review of generative autoencoder frameworks and their latent modeling strategies** *Applied Soft Computing* [[paper](https://doi.org/10.1016/j.asoc.2026.115933)]
- [2026] **Cathode chemistry for a sustainable battery future: From conventional intercalation to next-generation architectures** *Materials and Emerging Technologies for Sustainability* [[paper](https://doi.org/10.1142/s3060932126300052)]
- [2026] **Automated Multiple-Choice Question Generation: A Survey from a KDDM Perspective** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-92-1947-6_45)]
- [2026] **A&A community survey on the future of scientific publishing** *Springer Link (Chiba Institute of Technology)* [[paper](https://www.aanda.org/10.1051/0004-6361/202661365/pdf)]
- [2026] **Uncovering customer preference heterogeneity from online reviews via multi-dimensional clustering** *Journal of Business Research* [[paper](https://doi.org/10.1016/j.jbusres.2026.116314)]
- [2026] **Typed Mathematical Text for On-screen Examinations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.25276)]
- [2026] **LLM Evaluation in Practice: A Review of Metrics, Practitioner Insights, and Lessons Learned** [[paper](https://doi.org/10.63317/3exz7ndz9d6j)]
- [2026] **Data Summary & Analysis Human Computer Interaction Perspective on Paradox Design Students Towards AI** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.32297739.v1)]
- [2026] **A survey of large language models: techniques, applications, and challenges** *Multimedia Systems* [[paper](https://doi.org/10.1007/s00530-026-02288-9)]
- [2026] **Large Language Models for Material Science: A Systematic Review** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9377879/v1)]
- [2026] **LLMs, RAG systems, and agents in crystalline materials discovery and characterization: A systematic review** *MRS Bulletin* [[paper](https://doi.org/10.1557/s43577-026-01057-3)]
- [2026] **International Delphi consensus recommendations for the follow-up of children born to people with CF and exposed to CFTR modulators in utero or through breastfeeding; endorsed by the European Cystic Fibrosis Society** *Journal of Cystic Fibrosis* [[paper](https://doi.org/10.1016/j.jcf.2026.04.006)]
- [2026] **HUMANS AS PILOTS OF ECOLOGICAL DEGRADATION IN NIGERIA: AN EXAMINATION OF SACRED TEXTS IN AFRICAN RELIGION AND ISLAM** *International Journal of Law Politics and Humanities Research* [[paper](https://doi.org/10.70382/caijlphr.v11i6.091)]
- [2026] **Vulnerabilities in Autonomous Execution: A Survey of Security Threats and Defenses in LLM-driven Multi-Agent Systems** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7218206)]
- [2026] **Semantic Fidelity Challenges in Diffusion-Based Text-to-Image Models: A Survey** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6749420)]
- [2026] **Pros and Cons of AI Use in the Criminal Law Science** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6365400)]
- [2026] **Language models for environmental, social, and governance analysis: A review** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2025.104596)]
- [2026] **Co-occurrence Network Analysis in Consumer Studies** [[paper](https://doi.org/10.1007/978-3-032-04851-6_10)]
- [2026] **Agentic FinTech: A Comprehensive Survey on AI Agents in Finance in the Era of LLMs** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6136529)]
- [2026] **Advancement in Text-to-SQL System Using Large Language Model (LLMS): A Review** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-3-032-19185-4_10)]
- [2026] **Advanced Hardware Security on Embedded Processors: A Systematic Review Protocol (2020-2026)** [[paper](https://osf.io/e3967)]
- [2026] **A survey of large language models for legal tasks: Progress, prospects and challenges** *Computer Science Review* [[paper](https://doi.org/10.1016/j.cosrev.2026.100906)]
- [2026] **A Survey on Retrieval-Augmented Generation Technology in Large Language Models** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-981-95-4788-3_23)]
- [2026] **A Review of Evaluation Metrics for Text Similarity** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6900601)]

##### 2025

- [2025] **Recent Advances in Discrete Speech Tokens: A Review** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3643619)]
- [2025] **Between Faith and Capital: A Theological Review of the Banking System and Interests in the Abrahamic Religions** *Pharos Journal of Theology* [[paper](https://doi.org/10.46222/pharosjot.107.17)]
- [2025] **Advancements in talking head generation: a comprehensive review of techniques, metrics, and challenges** *The Visual Computer* [[paper](https://doi.org/10.1007/s00371-025-04232-w)]
- [2025] **A Survey on Addition Chains Generation Methods** *International Journal of Science and Research (IJSR)* [[paper](https://doi.org/10.21275/sr251220151342)]
- [2025] **A Survey of Generative Recommendation from a Tri-Decoupled Perspective: Tokenization, Architecture, and Optimization** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202512.0203.v1)]
- [2025] **A Comprehensive Survey on Linguistic Steganography: Methods, Countermeasures, Evaluation, and Challenges** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.29077)]
- [2025] **Mapping Research on Social Cognitive Bias in Large Language Models** [[paper](https://doi.org/10.1109/icdmw69685.2025.00159)]
- [2025] **From text mining to intelligent debate: Task frameworks and technological evolution in computational argumentation** *Information Processing & Management* [[paper](https://doi.org/10.1016/j.ipm.2025.104465)]
- [2025] **A Survey of Modular OCR Approaches for Tamil-Brahmi Inscriptions: Segmentation and Reconstruction Focus** [[paper](https://doi.org/10.1109/icuis67429.2025.11380767)]
- [2025] **Current status and future perspectives of multi‐modal bacteria‐based cancer therapies** *Clinical and Translational Medicine* [[paper](https://doi.org/10.1002/ctm2.70485)]
- [2025] **Towards Sustainable Image Synthesis: A Comprehensive Review of Text-to-Image Generation Models** *International Research Journal of Multidisciplinary Technovation* [[paper](https://doi.org/10.54392/irjmt2557)]
- [2025] **Mental Health of Adolescents in the Strawberry Generation: A Bibliometric Analysis** *Jurnal PROMKES* [[paper](https://doi.org/10.20473/jpk.v13.i2.2025.250-256)]
- [2025] **GPT-5 and open-weight large language models: Advances in reasoning, transparency, and control** *Information Systems* [[paper](https://doi.org/10.1016/j.is.2025.102620)]
- [2025] **The Application and Reflection of Generative Artificial Intelligence in Contemporary Art Creation** [[paper](https://doi.org/10.1145/3770445.3770464)]
- [2025] **Reviewing clinical knowledge in medical large language models: Training and beyond** *Knowledge-Based Systems* [[paper](https://arxiv.org/abs/2502.20988)]
- [2025] **Retrieval-Augmented Generation: A Survey of Security Challenges and Countermeasures** [[paper](https://doi.org/10.1109/pcds65695.2025.00037)]
- [2025] **Generative AI: A survey of historical development, emerging trends, and future outlook** [[paper](https://doi.org/10.69517/cser.2025.02.01.0004)]
- [2025] **Development of a Tool to Measure the Dyadic Process of Shared Decision Making in Young Children: The Making Decisions for Kids (MADE for Kids) Survey** *Medical Decision Making* [[paper](https://doi.org/10.1177/0272989x251353216)]
- [2025] **Decoding fake news fabrications and trends: A comprehensive survey** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.131118)]
- [2025] **Backdoor threats in large language models—a survey** *Science China Information Sciences* [[paper](https://doi.org/10.1007/s11432-024-4351-3)]
- [2025] **Knowledge graphs in heterogeneous catalysis: Recent advances and future opportunities** *Chinese Journal of Chemical Engineering* [[paper](https://doi.org/10.1016/j.cjche.2025.06.008)]
- [2025] **A Survey of Natural Language Processing for Classification of Saudi Arabic Dialect: Advancements, Opportunities, and Challenges** *Lecture notes of the Institute for Computer Sciences, Social Informatics and Telecommunications Engineering* [[paper](https://doi.org/10.1007/978-3-031-92625-9_8)]
- [2025] **A Review of GAN-based Methods for Image Translation and Caption Generation** [[paper](https://doi.org/10.1109/iccmc65190.2025.11140882)]
- [2025] **Evaluation of the impact of large language learning models on publications in the Journal of Shoulder and Elbow Surgery** *JSES International* [[paper](https://doi.org/10.1016/j.jseint.2025.05.027)]
- [2025] **A Survey of Automatic Evaluation Methods on Text, Visual and Speech Generations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2506.10019)]
- [2025] **ragnar: Retrieval-Augmented Generation (RAG) Workflows** [[paper](https://doi.org/10.32614/cran.package.ragnar)]
- [2025] **A review of generative models for virtual human motion driving** *Science China Information Sciences* [[paper](https://doi.org/10.1007/s11432-023-4284-x)]
- [2025] **Neural headline generation: A comprehensive survey** *Neurocomputing* [[paper](https://doi.org/10.1016/j.neucom.2025.129633)]
- [2025] **Attacks and Defenses for Generative Diffusion Models: A Comprehensive Survey** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3721479)]
- [2025] **Artificial intelligence for abdominopelvic trauma imaging: trends, gaps, and future directions** *Abdominal Radiology* [[paper](https://doi.org/10.1007/s00261-025-04816-z)]
- [2025] **How are communication companies adopting AI** *Comunicación y Sociedad* [[paper](https://doi.org/10.32870/cys.v2025.8846)]
- [2025] **Understanding the Role of Mixed Precision in Building and Optimizing Next-Generation Vision and Language Models at Scale** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5377268)]
- [2025] **Towards the Generation of Learning Objects with Generative Artificial Intelligence** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-85628-0_25)]
- [2025] **ProductiveMath: A Generative-AI-Powered App to Support Productive Failure Teaching** *Communications in computer and information science* [[paper](https://doi.org/10.1007/978-3-031-99264-3_43)]
- [2025] **Inteligencia Artificial Generativa: análisis conceptual y práctico del Modelo Generación Aumentada de Recuperación** *Dialnet (Universidad de la Rioja)* [[paper](https://dialnet.unirioja.es/servlet/oaiart?codigo=10614648)]
- [2025] **Empowering Adolescents in Stunting Prevention: A Literature Review on Educational Media and Methods** *Journal of Neonatal Surgery* [[paper](https://doi.org/10.52783/jns.v14.1507)]
- [2025] **Artificial Intelligence-Powered Contextual Three-Dimensional Environment Generation: A Systematic Review** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5396319)]
- [2025] **A survey of handwriting synthesis from 2019 to 2024: A comprehensive review** *Pattern Recognition* [[paper](https://doi.org/10.1016/j.patcog.2025.111357)]
- [2025] **A Survey on Text Classification Using Deep Learning Approaches** *Lecture notes in electrical engineering* [[paper](https://doi.org/10.1007/978-981-96-6034-6_25)]
- [2025] **A Comprehensive Survey on Text-to-Video Generation: Models, Architectures, and Challenges** *Lecture notes in networks and systems* [[paper](https://doi.org/10.1007/978-981-96-5604-2_6)]
- [2025] **A Comprehensive Survey on Generative AI Applications: Theoretical Foundations and Emerging Trends** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5229149)]

##### 2024

- [2024] **Large language models for generative information extraction: a survey** *Frontiers of Computer Science* [[paper](https://doi.org/10.1007/s11704-024-40555-y)]
- [2024] **AI Driven LLM integrated diffusion models for Image Enhancement- A Survey** [[paper](https://doi.org/10.1109/icei64305.2024.10912400)]
- [2024] **Natural Language Generation for Visualizations: State of the Art, Challenges and Future Directions** *Computer Graphics Forum* [[paper](https://doi.org/10.1111/cgf.15266)]
- [2024] **Nano device fabrication for in-memory and in-sensor reservoir computing** *International Journal of Extreme Manufacturing* [[paper](https://doi.org/10.1088/2631-7990/ad88bb)]
- [2024] **History, development, and principles of large language models: an introductory survey** *AI and Ethics* [[paper](https://doi.org/10.1007/s43681-024-00583-7)]
- [2024] **Generative technology for human emotion recognition: A scoping review** *Information Fusion* [[paper](https://doi.org/10.1016/j.inffus.2024.102753)]
- [2024] **Large Language Models for Human-Like Autonomous Driving: A Survey** [[paper](https://doi.org/10.1109/itsc58415.2024.10919629)]
- [2024] **From Northern Europe to Southern Europe and from the general to the particular: recent research on Jewish-Christian coexistence in medieval Europe** [[paper](https://dx.doi.org/10.4324/9781003556534-2)]
- [2024] **Continuity and Change in Chinese Worldviews An Historical Survey** [[paper](https://dx.doi.org/10.1093/oso/9780197766033.003.0003)]
- [2024] **Adversarial attacks and defenses on text-to-image diffusion models: A survey** *Information Fusion* [[paper](https://doi.org/10.1016/j.inffus.2024.102701)]
- [2024] **A Comprehensive Survey of Bias in LLMs: Current Landscape and Future Directions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.16430)]
- [2024] **Preface: Brain-Inspired AI Research** *Science China Technological Sciences* [[paper](https://doi.org/10.1007/s11431-024-2763-0)]
- [2024] **Clinical Research Informatics: Contributions from 2023** *Yearbook of Medical Informatics* [[paper](https://doi.org/10.1055/s-0044-1800733)]
- [2024] **Pre-trained language models for keyphrase prediction: A review** *ICT Express* [[paper](https://arxiv.org/abs/2409.01087)]
- [2024] **Literature Review of Socio-Cultural Studies on Incidence of Early Childhood Marriage** *Griya Widya Journal of Sexual and Reproductive Health* [[paper](https://doi.org/10.53088/griyawidya.v3i2.1722)]
- [2024] **How Machine Learning is Innovating Today's World** [[paper](https://doi.org/10.1002/9781394214167)]
- [2024] **ChatGPT for L2 learning: Current status and implications** *System* [[paper](https://doi.org/10.1016/j.system.2024.103351)]
- [2024] **Cantonese natural language processing in the transformers era: a survey and current challenges** *Language Resources and Evaluation* [[paper](https://doi.org/10.1007/s10579-024-09744-w)]
- [2024] **Barriers to migrant integration policy in Mexico** [[paper](https://dx.doi.org/10.4324/9781003509516-3)]
- [2024] **Large language models for air transportation: A critical review** *Journal of the Air Transport Research Society* [[paper](https://doi.org/10.1016/j.jatrs.2024.100024)]
- [2024] **Humor as a Teaching Tool: Evaluating the Impact of Memes on Student Engagement in Pharmacology Instruction** *Journal of Pharmacology and Experimental Therapeutics* [[paper](https://doi.org/10.1124/jpet.218.911970)]
- [2024] **A Survey of Adversarial Attacks: An Open Issue for Deep Learning Sentiment Analysis Models** *Applied Sciences* [[paper](https://doi.org/10.3390/app14114614)]
- [2024] **A Survey on Responsible Generative AI: What to Generate and What Not** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2404.05783)]
- [2024] **A Survey of AI-generated Text Forensic Systems: Detection, Attribution, and Characterization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.01152)]
- [2024] **Honoring our teachings: children’s storybooks as indigenous public health practice** *Frontiers in Public Health* [[paper](https://doi.org/10.3389/fpubh.2024.1354761)]
- [2024] **Exploring Digital Ageism: A Systematic Literature Review on Social Media and Aging** *American Journal of Geriatric Psychiatry* [[paper](https://doi.org/10.1016/j.jagp.2024.01.220)]
- [2024] **A survey on large language model (LLM) security and privacy: The Good, The Bad, and The Ugly** *High-Confidence Computing* [[paper](https://doi.org/10.1016/j.hcc.2024.100211)]
- [2024] **A Comprehensive Survey on 3D Content Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.01166)]
- [2024] **Review: California, A Slave State, by Jean Pfaelzer** *California History* [[paper](https://doi.org/10.1525/ch.2024.101.4.148)]
- [2024] **Local Fusions: Folk Music Experiments in Central Europe at the Millennium** *Ethnomusicology* [[paper](https://dx.doi.org/10.5406/21567417.68.2.12)]
- [2024] **Insights on the Use of Sentiment Analysis in the Context of Higher Education** *Lecture notes on data engineering and communications technologies* [[paper](https://doi.org/10.1007/978-3-031-57996-7_51)]
- [2024] **Generative Technology for Human Emotion Recognition: A Scope Review** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.4889990)]
- [2024] **Funny, You Don't Look Funny: Judaism and Humor from the Silent Generation to Millennials by Jennifer Caplan (review)** *Journal of Jewish identities* [[paper](https://doi.org/10.1353/jji.2024.a918655)]
- [2024] **Free-form Shape Modeling in XR: A Systematic Review** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2401.00924)]
- [2024] **A recent survey on controllable text generation: A causal perspective** *Fundamental Research* [[paper](https://doi.org/10.1016/j.fmre.2024.01.001)]
- [2024] **A Survey on RAG with LLMs** *Procedia Computer Science* [[paper](https://doi.org/10.1016/j.procs.2024.09.178)]
- [2024] **A Survey on LLMs: Evolution, Applications, and Future Frontiers** *Studies in computational intelligence* [[paper](https://doi.org/10.1007/978-981-97-8460-8_14)]
- [2024] **A Survey of Deep Learning Techniques and Applications in Bioengineering: A Latin American Perspective** *World Congress on Medical Physics and Biomedical Engineering, September 7 - 12, 2009, Munich, Germany* [[paper](https://doi.org/10.1007/978-3-031-61960-1_57)]

##### 2023

- [2023] **Social acceptance of geothermal technology on a global view: a systematic review** *Energy Sustainability and Society* [[paper](https://doi.org/10.1186/s13705-023-00432-1)]
- [2023] **Should menopause care be part of the skill set of a reproductive endocrinology and infertility specialist?** *Fertility and Sterility* [[paper](https://doi.org/10.1016/j.fertnstert.2023.11.018)]
- [2023] **Performance of the European Kidney Function Consortium (EKFC) creatinine-based equation in United States cohorts** *Kidney International* [[paper](https://doi.org/10.1016/j.kint.2023.11.024)]
- [2023] **GEODIVERSITY AND POSITIVE SOCIO-ENVIRONMENTAL IMPACTS IN THE IMPLEMENTATION OF GEOTOURISM** *International Journal Semiarid* [[paper](https://doi.org/10.56346/ijsa.v6i6.177)]
- [2023] **An Expansive Survey, in Clear and Vivid Form: Proctor and Vu's (2023) Attention** *The American Journal of Psychology* [[paper](https://doi.org/10.5406/19398298.136.4.09)]
- [2023] **A Survey on Machine Learning Based Keyphrase Generation in Natural Language Processing** *Nepal Journal of Science and Technology* [[paper](https://doi.org/10.3126/njst.v22i2.85238)]
- [2023] **Design mediating printing technology and food culture: a small paper box linking "eating" and "mobility"** [[paper](https://doi.org/10.21606/iasdr.2023.632)]
- [2023] **Bridging Conventional Admissions Metrics and Undergraduate Engineering Student Non-Cognitive and Affective Factors** [[paper](https://dx.doi.org/10.1109/fie58773.2023.10343325)]
- [2023] **Animated film made by women from Pará** *LA Referencia (Red Federada de Repositorios Institucionales de Publicaciones Científicas)* [[paper](https://hdl.handle.net/1843/63867)]

[⬆ Back to top](#paper-list)

#### Prompt Engineering

##### 2026

- [2026] **Operationalizing Fairness in Text-to-Image Models: A Survey of Bias, Fairness Audits and Mitigation Strategies** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.16516)]
- [2026] **Generative AI : A Comprehensive Overview of Large Language Models for Prompt Engineering and Applications** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8809658/v1)]
- [2026] **Evaluating the Impact of Prompt Engineering on Factual Accuracy and Hallucination in Large Language Models** *International journal of research and scientific innovation* [[paper](https://doi.org/10.51244/ijrsi.2026.1304000068)]
- [2026] **Ethical Synthetic Text Generation for Vulnerable Populations Using Large Language Models: A Comprehensive Survey** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3698020)]

##### 2025

- [2025] **Medical Reasoning in the Era of LLMs: A Systematic Review of Enhancement Techniques and Applications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.00669)]
- [2025] **A survey on pre-training and transfer learning for multimodal Vision-Language Models** *Advances in Engineering Innovation* [[paper](https://doi.org/10.54254/2977-3903/2025.23982)]
- [2025] **Editorial: Large Language Models for medical applications** *Frontiers in Medicine* [[paper](https://doi.org/10.3389/fmed.2025.1625293)]
- [2025] **Fine-Tuning Transformers Efficiently: A Survey on LoRA and Its Impact** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202502.1637.v1)]
- [2025] **Synthetic Data Generation Using Large Language Models: Advances in Text and Code** *IEEE Access* [[paper](https://arxiv.org/abs/2503.14023)]

[⬆ Back to top](#paper-list)

#### Few-shot Learning

##### 2026

- [2026] **SocioTable-KZ: Ethical and Privacy-Aware Bilingual Generation from Sociological Survey Data** *Information* [[paper](https://doi.org/10.3390/info17080765)]
- [2026] **Dynamic Cognitive Prior Generation for Robust EEG-to-Image Decoding** *Journal of Engineering and Computational Intelligence Review* [[paper](https://doi.org/10.63544/5e91eh66)]
- [2026] **Comprehensive review of traditional and deep learning approaches to text to speech synthesis** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-026-01924-7)]
- [2026] **Challenges and opportunities of generative artificial intelligence models in audio/acoustic domain: a comprehensive survey** *Artificial Intelligence Review* [[paper](https://doi.org/10.1007/s10462-026-11670-y)]
- [2026] **A Systematic Literature Review of AI-Powered Legal and Financial Assistance Systems: Approaches, Challenges, and Future Directions** [[paper](https://www.ipasj-org-iijcs-htm.ddns-ip.net)]
- [2026] **ECG Foundation Models and Medical LLMs for Agentic Cardiovascular Intelligence at the Edge: A Review and Outlook** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.02501)]
- [2026] **Empowering Video Translation using Multimodal Large Language Models** [[paper](https://doi.org/10.36227/techrxiv.177162137.77131035/v1)]
- [2026] **Large Language Models for Citation Context and Cited Content Recognition: From Boundary Detection to Evidence Grounding** *International Journal of English Literature and Social Sciences* [[paper](https://doi.org/10.22161/ijels.114.64)]
- [2026] **Jailbreaking LLMs & VLMs: Mechanisms, Evaluation, and Unified Defense** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2601.03594)]

##### 2025

- [2025] **Exploring the roles of large language models in reshaping transportation systems: A survey, framework, and roadmap** *Artificial Intelligence for Transportation* [[paper](https://arxiv.org/abs/2503.21411)]
- [2025] **Generative Artificial Intelligence in Real-World Applications: A Survey of Architectures, Use Cases, and Implementation Challenges** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19652204)]

##### 2024

- [2024] **Deep Generative Models for 3D Content Creation: A Comprehensive Survey of Architectures, Challenges, and Emerging Trends** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202410.2397.v1)]
- [2024] **Using Large Language Models (LLMs) to facilitate L2 proficiency development through personalized feedback and scaffolding: An empirical study** *Proceedings of the International CALL Research Conference* [[paper](https://doi.org/10.29140/9780648184485-09)]
- [2024] **Segment Anything for Videos: A Systematic Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.08315)]

[⬆ Back to top](#paper-list)

#### Neural Text Generation

##### 2026

- [2026] **Towards Automated Discovery: A Review of Generative Models, Multimodal Learning and Closed-Loop Workflows in Inverse Materials Design** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.02507)]
- [2026] **Generative AI for Video Trailer Synthesis: From Extractive Heuristics to Autoregressive Creativity** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.04953)]
- [2026] **Speculative Decoding for Multimodal Models: A Survey** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202603.2344.v1)]
- [2026] **Understanding Meets Generation: Design Philosophies and Emerging Directions Toward Unified Models** [[paper](https://doi.org/10.36227/techrxiv.177160514.47512518/v1)]
- [2026] **Advances in GRPO for Generation Models: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.06623)]
- [2026] **Review of artificial intelligence methods for video content generation and their application in building digital twins of situation centers** *Neurocomputers* [[paper](https://doi.org/10.18127/j19998554-202602-07)]
- [2026] **A Comprehensive Survey of Generative AI: Applications and Future Directions Across Domains** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3715238)]

##### 2025

- [2025] **Three Dimensional Gaussian Splatting as a Foundation for Multitask Scene Modeling Spanning Segmentation Editing and Generation** [[paper](https://doi.org/10.36227/techrxiv.176539670.07953468/v1)]
- [2025] **A Technical Overview of Continuous and Discrete Diffusion-based Language Models** [[paper](https://doi.org/10.1109/icicse66971.2025.11430022)]
- [2025] **Revisiting U-Net: a foundational backbone for modern generative AI** *Artificial Intelligence Review* [[paper](https://doi.org/10.1007/s10462-025-11450-0)]
- [2025] **A Survey of Unified Multimodal Understanding and Generation: Advances and Challenges** [[paper](https://doi.org/10.36227/techrxiv.176289261.16802577/v1)]
- [2025] **If generative AI is the answer, what is the question?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2509.06120)]
- [2025] **Reimagining Model Efficiency in Generative AI Through Unified and Differentiable Quantization Approaches** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202508.1223.v1)]
- [2025] **Quantization as a Foundation for Deployable High Performance Diffusion Models within the Landscape of Large Scale Generative AI** [[paper](https://doi.org/10.36227/techrxiv.175624440.05705133/v1)]
- [2025] **Personalized Image Generation with Deep Generative Models: A Decade Survey** *Computational Visual Media* [[paper](https://doi.org/10.26599/cvm.2025.9450495)]
- [2025] **Unified Multimodal Understanding and Generation Models: Advances, Challenges, and Opportunities** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.02567)]

##### 2024

- [2024] **A Comprehensive Survey of Hypermedia System for Text- to-Image Conversion Using Generative AI** *Advances in computational intelligence and robotics book series* [[paper](https://dx.doi.org/10.4018/979-8-3693-3278-8.ch001)]

[⬆ Back to top](#paper-list)

#### Controllable Generation

##### 2025

- [2025] **Controllable Generation With Text-to-Image Diffusion Models: A Survey** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://doi.org/10.1109/tpami.2025.3646548)]
- [2025] **Controllable Video Generation: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.16869)]

##### 2024

- [2024] **Text to Image using Deep Learning: A Survey** *SciNexuses.* [[paper](https://doi.org/10.61356/j.scin.2024.1518)]

##### 2023

- [2023] **Automatic Text Summarization of News Articles: Recent Advances and Challenges** [[paper](https://doi.org/10.1109/iementech60402.2023.10423515)]

[⬆ Back to top](#paper-list)

#### Creative Writing

##### 2026

- [2026] **Computational Approaches to Automatic Poetry Generation and Evaluation: A Survey** *Journal of Artificial Intelligence Research* [[paper](https://doi.org/10.1613/jair.1.20584)]
- [2026] **Text-to-Text Automatic Story Generation: A Survey** *Underline Science Inc.* [[paper](https://doi.org/10.48448/rsm7-1127)]

##### 2025

- [2025] **The Review of English Studies at 100: Origins and Early Years** *The Review of English Studies* [[paper](https://doi.org/10.1093/res/hgaf078)]
- [2025] **Applications of NLP in Computational Poetics and Literary Analysis** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202507.0615.v1)]

##### 2023

- [2023] **Idealizing Women in the Italian Renaissance ed. by Elena Brizio and Marco Piana (review)** *The Modern Language Review* [[paper](https://doi.org/10.1353/mlr.2023.a907868)]
- [2023] **Hubert Crackanthorpe: Selected Writings ed. by William Greenslade and Emanuela Ettorre (review)** *The Modern Language Review* [[paper](https://doi.org/10.1353/mlr.2023.a907861)]

[⬆ Back to top](#paper-list)

#### Summarization

##### 2026

- [2026] **A Reassessment of TextRank: Graph-Based Extractive Summarization in the Era of Large Language Models- A Systematic Review** *Iraqi Journal for Computers and Informatics* [[paper](https://doi.org/10.25195/ijci.v52i2.865)]
- [2026] **Generative small language models in clinical NLP: applications, adaptation, and evaluation** *PeerJ Computer Science* [[paper](https://doi.org/10.7717/peerj-cs.4000)]
- [2026] **A Survey on LLM Watermarking: Theory and Deployment** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.10103)]
- [2026] **Why Current XAI Is Not Enough for Arabic NLP: A Critical Survey of the Explainability Gap** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.26144)]
- [2026] **Automatic Legal Text Summarization: A Survey on Techniques, Rhetorical Roles, Challenges and Future Scope** [[paper](https://doi.org/10.1109/idciot67589.2026.11455895)]

##### 2025

- [2025] **Enterprise Applications for Text Summarization: Bridging Research Innovations with Market Trends and Future Directions** [[paper](https://doi.org/10.1109/aisummit66170.2025.11410837)]
- [2025] **A review of AI-based business lead generation: Scrapus as a case study** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1606431)]
- [2025] **A Survey of Adaptation of Large Language Models to Idea and Hypothesis Generation: Downstream Task Adaptation, Knowledge Distillation Approaches and Challenges** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3774628)]
- [2025] **Trending Applications of Large Language Models: A User Perspective Survey** *IEEE Transactions on Artificial Intelligence* [[paper](https://doi.org/10.1109/tai.2025.3620272)]
- [2025] **Opportunities and Applications of GenAI in Smart Cities: A User-Centric Survey** [[paper](https://arxiv.org/abs/2505.08034)]
- [2025] **From Insight to Impact: How AI Tools Transform Managerial Practice in Czech Companies** [[paper](https://doi.org/10.18690/um.epf.5.2025.59)]
- [2025] **A Survey on Hallucination in Large Language and Foundation Models** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202504.1236.v2)]
- [2025] **Various Approaches Of Text Summarization: A Literature Review** *International Journal of Advances in Signal and Image Sciences* [[paper](https://doi.org/10.29284/d30znw81)]
- [2025] **Natural Language Processing of Privacy Policies: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.10319)]

##### 2024

- [2024] **Key point generation as an instrument for generating core statements of a political debate on Twitter** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2024.1200949)]
- [2024] **Explainability Meets Text Summarization: A Survey** [[paper](https://doi.org/10.18653/v1/2024.inlg-main.49)]

[⬆ Back to top](#paper-list)

#### Text Rewriting

##### 2026

- [2026] **A survey on deep learning-based map generation via style transfer of visible light remote sensing image** *Open Geosciences* [[paper](https://doi.org/10.1515/geo-2025-0999)]

##### 2025

- [2025] **Motion Style Transfer: Methods, Challenges, and Future Directions** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-981-95-0100-7_4)]
- [2025] **A Survey on Data Contamination for Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.14425)]

##### 2024

- [2024] **AI Watermark Robustness: Evaluating Methods to Identify AI-Generated Content After Editing or Compression** *International Journal of Research and Review in Applied Science Humanities and Technology* [[paper](https://doi.org/10.71143/qrzzwv89)]
- [2024] **Study on Generative Adversarial Network in Discrete Data: A Survey** *DOAJ (DOAJ: Directory of Open Access Journals)* [[paper](https://doaj.org/article/dd721dc611f0460b91e19dbecb5dc1a9)]
- [2024] **Ethnic Transformation and Israel's Resurrection in the Pauline Epistles and Beyond: In Grateful Dialogue with Reviewers** *Religious Studies Review* [[paper](https://doi.org/10.1111/rsr.17452)]

[⬆ Back to top](#paper-list)

#### Grammar & Style Checking

##### 2026

- [2026] **Artificial Intelligence Guidelines for Scientific Writing in Academic Engineering** [[paper](https://doi.org/10.14293/pr2199.003443.v1)]
- [2026] **Appropriate Use and Reporting of AI tools in Manuscript Preparation** *Saudi Journal of Medicine and Medical Sciences* [[paper](https://doi.org/10.4103/sjmms.sjmms_10_26)]

##### 2025

- [2025] **Aristotle: Art of Rhetoric** *Philosophy and Rhetoric* [[paper](https://doi.org/10.5325/philrhet.58.1.0115)]

##### 2024

- [2024] **A Literature Review : Enhancing Sentiment Analysis of Deep Learning Techniques Using Generative AI Model** *International Journal of Scientific Research in Computer Science Engineering and Information Technology* [[paper](https://doi.org/10.32628/cseit24103204)]
- [2024] **Scientific rot: Unsustainable publishing practices threatens trust in medicine** *Journal of Evaluation in Clinical Practice* [[paper](https://doi.org/10.1111/jep.13989)]
- [2024] **Artificial Intelligence in Graduate Medical Education Applications** *Journal of Graduate Medical Education* [[paper](https://doi.org/10.4300/jgme-d-23-00510.1)]
- [2024] **Botanical Poetics: Early Modern Plant Books and the Husbandry of Print** *Modern Language Quarterly* [[paper](https://doi.org/10.1215/00267929-11060503)]

[⬆ Back to top](#paper-list)

#### Outline & Planning

##### 2026

- [2026] **Large language models in spine care and research** *European Spine Journal* [[paper](https://doi.org/10.1007/s00586-026-10204-y)]
- [2026] **Large language models in bioinformatics: a comprehensive survey** *Frontiers in Genetics* [[paper](https://doi.org/10.3389/fgene.2026.1797863)]
- [2026] **AI for Accelerated Materials Discovery: From Generative Design to Autonomous Realization** *Chemical Reviews* [[paper](https://doi.org/10.1021/acs.chemrev.6c00154)]
- [2026] **A Survey on Transformer-Based Long-Range Dependency Modeling in Intelligent Document Understanding** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3844505)]
- [2026] **Generative AI at the Edge: A Comprehensive Survey of Architectures, Hardware and Applications** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3829079)]
- [2026] **Correction: Understanding antibiotic decision-making for bovine respiratory disease: a survey of UK farm veterinarians** *Frontiers in Veterinary Science* [[paper](https://doi.org/10.3389/fvets.2026.1900336)]
- [2026] **A Survey on Foundations and Frontiers of Multimodal Agentic Frameworks: Techniques and Applications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.20379)]
- [2026] **From Automation to Collaboration: Human-in-the-Loop Methods for Safe and Trustworthy NLP** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.25226)]
- [2026] **Autoencoders in Natural Language Processing: A Comprehensive Review** *Computers* [[paper](https://doi.org/10.3390/computers15040232)]
- [2026] **From Secure Agentic AI to Secure Agentic Web: Challenges, Threats, and Future Directions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.01564)]
- [2026] **A Taxonomy of Generative Models with a Focus on Diffusion Models and Denoising Techniques** *Electronics* [[paper](https://doi.org/10.3390/electronics15061293)]
- [2026] **A Survey on Music Generation from Single-Modal, Cross-Modal, and Multi-Modal Perspectives** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3800682)]
- [2026] **Retrieval-Augmented Generation with Large Language Models for Domain-Oriented Decision Making** [[paper](https://doi.org/10.1109/icsedi66420.2026.11568372)]
- [2026] **Generalizability of Large Language Model-Based Agents: A Comprehensive Survey** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3794858)]
- [2026] **Relational Learning through Feminist Pragmatist Praxis in Place: Learning in and through Relationship** *The Pluralist* [[paper](https://doi.org/10.5406/19446489.21.2.06)]
- [2026] **Large Action Models: A Unified Smart Framework for Autonomous Intelligent Systems** [[paper](https://doi.org/10.1109/icsft66733.2026.11506682)]
- [2026] **Generative AI Empowers Brain-Computer Interfaces: A Review-Perspective on Technical Realities and Future Visions** *IEEE Transactions on Consumer Electronics* [[paper](https://doi.org/10.1109/tce.2025.3650654)]
- [2026] **Complementary Vulnerabilities: A Systematic Review Comparing Reasoning Failures in Human and LLM Clinical Decision-Making** [[paper](https://osf.io/mqj6y)]

##### 2025

- [2025] **Event Extraction in Large Language Model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2512.19537)]
- [2025] **A Comprehensive Survey on Real-Time Speech-To-Sign-Language Translation Systems for Assistive Communication** [[paper](https://doi.org/10.1109/icacrs67045.2025.11324368)]
- [2025] **Innovations in Clinical Pharmacology: Shaping the Future of Evidence Generation in Research, Development, and Utilization of Medicines** *Clinical Pharmacology & Therapeutics* [[paper](https://doi.org/10.1002/cpt.70109)]
- [2025] **From single-agent to multi-agent: a comprehensive review of LLM-based legal agents** *AI Agent* [[paper](https://doi.org/10.20517/aiagent.2025.06)]
- [2025] **Deep Learning for 3D Fashion Design: A Survey From a Sewing Pattern-Driven Perspective** *IEEE Transactions on Circuits and Systems for Video Technology* [[paper](https://doi.org/10.1109/tcsvt.2025.3637565)]
- [2025] **Book review: Revisiting foundations in an accelerating field: a review of Teaching and Learning at a Distance: Foundations of Distance Education (8th ed.)** *Quarterly review of distance education* [[paper](https://doi.org/10.1108/qrde-10-2025-015)]
- [2025] **A Comprehensive Investigation of Advances in Music Understanding and Generation Technologies Based on Large Language Models** *Communications in Humanities Research* [[paper](https://doi.org/10.54254/2753-7064/2025.ns29129)]
- [2025] **Multimedia-Aware Question Answering: A Review of Retrieval and Cross-Modal Reasoning Architectures** [[paper](https://arxiv.org/abs/2510.20193)]
- [2025] **Bridging Knowledge and Language Models in Healthcare: A RAG Survey** [[paper](https://doi.org/10.1109/iccke68588.2025.11273839)]
- [2025] **Towards Explainable AI in Agentic Retrieval-Augmented Generation: A Systematic Review** [[paper](https://doi.org/10.1109/idap68205.2025.11222281)]
- [2025] **Survey of General Practitioners' Cognition and Needs for AI Assisted Diagnosis and Treatment Systems** *DOAJ (DOAJ: Directory of Open Access Journals)* [[paper](https://doaj.org/article/c15f91f920b34550a0e3b67035165a96)]
- [2025] **LLMs for Mfg.—On the State of Large Language Models and Applications to Manufacturing** [[paper](https://doi.org/10.2172/3002123)]
- [2025] **How does Generative AI Affect Patients' Rights?** *Voices in Bioethics* [[paper](https://doi.org/10.52214/vib.v11i.14212)]
- [2025] **Trustworthy AI for Educational Metaverses** [[paper](https://doi.org/10.36227/techrxiv.170775108.81506629/v2)]
- [2025] **A Survey on Vision-Language Models for Multimodal Federated Learning Tasks** [[paper](https://doi.org/10.36227/techrxiv.175624545.56457516/v1)]
- [2025] **Human Motion Video Generation: A Survey** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://arxiv.org/abs/2509.03883)]
- [2025] **Data Resource Profile: Genomic data in multiple British birth cohorts (1946–2001)—linkage with health, social, and environmental data from birth to old age** *International Journal of Epidemiology* [[paper](https://doi.org/10.1093/ije/dyaf141)]
- [2025] **Impact of Generative Artificial Intelligence on Content Creation Efficiency for Chinese Self-Media Publishers** *Asia-pacific Journal of Convergent Research Interchange* [[paper](https://doi.org/10.47116/apjcri.2025.06.03)]
- [2025] **A Review of Financial Data Analysis Techniques for Unstructured Data in the Deep Learning Era: Methods, Challenges, and Applications** [[paper](https://doi.org/10.31219/osf.io/gdvbj_v1)]
- [2025] **Roadmap of Anaphylaxis Registries Across the World** *Clinical & Experimental Allergy* [[paper](https://doi.org/10.1111/cea.70074)]
- [2025] **Towards Trustworthy GUI Agents: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.23434)]
- [2025] **The relevance of policy process theories in Europe** *European Policy Analysis* [[paper](https://doi.org/10.1002/epa2.70002)]
- [2025] **Audio Deepfake Detection: What Has Been Achieved and What Lies Ahead** *Sensors* [[paper](https://doi.org/10.3390/s25071989)]
- [2025] **A Review of LLM-Assisted Ideation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.00946)]
- [2025] **Editorial: Patient Experience Data and Feedback for Quality Improvement and Learning Health Systems** *The International Journal of Health Planning and Management* [[paper](https://doi.org/10.1002/hpm.3917)]
- [2025] **Ask in Any Modality: A Comprehensive Survey on Multimodal Retrieval-Augmented Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.08826)]
- [2025] **A Survey on Pre-Trained Diffusion Model Distillations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.08364)]
- [2025] **A Quantitative Analysis on Depictions of Chronic Pain Generated via DALL-E 3, a Text-to-Image Artificial Intelligence Tool** *Anesthesiology* [[paper](https://doi.org/10.1097/aln.0000000000005364)]
- [2025] **Transforming Science with Large Language Models: A Survey on AI-assisted Scientific Discovery, Experimentation, Content Generation, and Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.05151)]
- [2025] **Chart Accessibility: A Review of Current Alt Text Generation** *IEEE Access* [[paper](https://doi.org/10.1109/access.2025.3571626)]

##### 2024

- [2024] **Document Parsing Unveiled: Techniques, Challenges, and Prospects for Structured Information Extraction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.21169)]
- [2024] **Data Resource Profile: The School Health Research Network (SHRN) Student Health and Well-being (SHW) survey of 11–16-year-olds (2017–2023)** *International Journal of Epidemiology* [[paper](https://doi.org/10.1093/ije/dyae161)]
- [2024] **All along the asset life cycle: Research opportunities for operations and supply chain management** *Journal of Operations Management* [[paper](https://doi.org/10.1002/joom.1326)]
- [2024] **How lived experience expertise shapes research and development in digital mental health** [[paper](https://doi.org/10.21955/wellcomeopenres.1115394.1)]
- [2024] **Hegel's Century: Alienation and Recognition in a Time of Revolution by Jon Stewart (review)** *Journal of the history of philosophy* [[paper](https://doi.org/10.1353/hph.2024.a925530)]

[⬆ Back to top](#paper-list)

#### Discourse Structure

##### 2026

- [2026] **alperozpinar/ascend: ASCEND v1.0.0** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22158472)]
- [2026] **Research Paper on Transformers in Text Generation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21836733)]
- [2026] **Acculturation and Metabolic Syndrome Among Hispanic/Latino Populations: A Scoping Review** [[paper](https://osf.io/axq9s)]
- [2026] **A Critical Review on Generative Artificial Intelligence in Healthcare: Innovations, Applications and Challenges** [[paper](https://doi.org/10.1201/9781042014446-29)]
- [2026] **Starved by scarcity: A three scarcities framework and decision roadmap for medical named entity recognition in low-resource languages** *Artificial Intelligence in Health* [[paper](https://doi.org/10.36922/aih026260068)]
- [2026] **Structural and Algorithmic Limitations in LLM-Driven BPMN Generation: A Rapid Review of Empirical Evidence** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20563488)]
- [2026] **Social Media Marketing and Generation Z Consumer Behaviour: A Systematic Literature Review in the Apparel and Cosmetics Industry** *Asian Journal of Management and Commerce* [[paper](https://doi.org/10.22271/27084515.2026.v7.i6a.1267)]
- [2026] **Skyrmion Photonics: From Topological Fundamentals to Integrated Devices and Critical Assessment** *Annalen der Physik* [[paper](https://doi.org/10.1002/andp.70235)]
- [2026] **Scaling Beyond Context: A Survey of Multimodal Retrieval-Augmented Generation for Document Understanding** *Underline Science Inc.* [[paper](https://doi.org/10.48448/pwn8-3537)]
- [2026] **Renewable and Citizen Energy Communities in the European Union: A Structured Review of Legal Frameworks, Implementation Barriers and Anchor-Prosumer Pathways in Romania** *Energies* [[paper](https://doi.org/10.3390/en19122911)]
- [2026] **Beyond NL2Code: A Structured Survey of Multimodal Code Intelligence** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.15932)]
- [2026] **An evaluation of LLMs for generating movie reviews: GPT-4o, Gemini-2.0 and DeepSeek-V3** *Neural Computing and Applications* [[paper](https://arxiv.org/abs/2506.00312)]
- [2026] **Advancements in Multimodal Foundation Models for Healthcare: An In-Depth Review and Future Outlook** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202606.1256.v1)]
- [2026] **AI-ASSISTED DIAGNOSIS AND PRECISION MEDICINE** [[paper](https://doi.org/10.58532/nbennurhac2)]
- [2026] **Tactile-based Multimodal Fusion in Embodied Intelligence: A Survey of Vision, Language, and Contact-Driven Paradigms** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.17336)]
- [2026] **Academic Citation Infrastructure: Infrastructure-Level Interventions for Generative Engine Optimization** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20401792)]
- [2026] **ADVANCING REASONING IN LARGE LANGUAGE MODELS (LLMs): ENHANCING COGNITIVE CAPABILITIES** *International Journal of Modeling and Applied Science Research* [[paper](https://doi.org/10.70382/caijmasr.v11i9.053)]
- [2026] **A comprehensive survey on facial expression generation: From GANs to LLM-guided multimodal models** *ICT Express* [[paper](https://doi.org/10.1016/j.icte.2026.05.007)]
- [2026] **A Scoping Review of Mental Health Risk and Resilience Factors among Vietnamese American Adolescents and Young Adults** *OSF Preprints (OSF Preprints)* [[paper](https://osf.io/4rhju)]
- [2026] **The Architectures of Inquiry: A History of Socratic Tutoring Systems and the Persistent Gap Between Theory and Implementation** [[paper](https://doi.org/10.35542/osf.io/kac9s_v1)]
- [2026] **From architecture to evaluation: A comprehensive review of video generation techniques** *Virtual Reality & Intelligent Hardware* [[paper](https://doi.org/10.1016/j.vrih.2026.03.002)]
- [2026] **Distinguishing anchoring from confirmation bias in diagnostic vignette studies: methodological implications for clinical decision-making** *Frontiers in Public Health* [[paper](https://doi.org/10.3389/fpubh.2026.1770198)]
- [2026] **A survey of Document understanding and question answering** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19364133)]
- [2026] **A Survey on Handwriting Recognition and NLP Integration Approaches** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21752554)]
- [2026] **A Comprehensive Survey on Automated Radiology Report Generation: Methods, Explainability, Multimodal Alignment, and Clinical Integration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19732654)]
- [2026] **Research on Innovative Design of Lower Limb Exoskeletons Based on AIGC** [[paper](https://doi.org/10.1145/3817124.3817227)]
- [2026] **Explainability of Text Processing and Retrieval Methods: A Survey** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3801957)]
- [2026] **A Survey on 3D Face Generation Technology** *DOAJ (DOAJ: Directory of Open Access Journals)* [[paper](https://doaj.org/article/6fbe401aaf544dab90f2eea006c5e3c8)]
- [2026] **Video Generation Models: A Survey of Post-Training and Alignment** [[paper](https://doi.org/10.36227/techrxiv.177220111.17351887/v1)]
- [2026] **Clinical Practice Guidelines for Menopause: *An Executive Summary and Recommendations: Indian Menopause Society 2026** *Journal of Mid-life Health* [[paper](https://doi.org/10.4103/jmh.jmh_302_25)]
- [2026] **COMPOSITIONALITY IN CONTRASTIVE VISION-LANGUAGE MODELS: A SURVEY OF METHODS AND BENCHMARKS** [[paper](https://doi.org/10.36227/techrxiv.177004940.09969046/v1)]
- [2026] **A Survey of LLM Reasoning in Healthcare and Medicine: from Individual Modeling to Collaborative Agents** [[paper](https://doi.org/10.36227/techrxiv.177127364.46765828/v1)]
- [2026] **The impact of generative AI on academic reading and writing: a synthesis of recent evidence (2023–2025)** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1711718)]
- [2026] **Photovoltaics Literature Survey (No. 205)** *Progress in Photovoltaics Research and Applications* [[paper](https://doi.org/10.1002/pip.70069)]
- [2026] **Leveraging Artificial Intelligence and Automation for Enhancing School Improvement Efforts** *Journal of Data Science* [[paper](https://doi.org/10.6339/26-jds1216)]
- [2026] **Consumer Trust in AI-Generated vs Human-Generated Content on eCommerce Platforms** *Aristotle University of Thessaloniki* [[paper](https://doi.org/10.26262/heal.auth.ir.375312)]
- [2026] **AI-Driven Synthetic Threats in Cybersecurity: A User-Centered Framework for Awareness, Detection, and Protective Behavior** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3673980)]
- [2026] **A Taxonomy of Knowledge Bases for Retrieval-Augmented Methods in Vision: A Comprehensive Survey** *IEEE Access* [[paper](https://doi.org/10.1109/access.2026.3668187)]

##### 2025

- [2025] **Logical Table-to-Text Generation: Challenges, Methods, and Reasoning** *Underline Science Inc.* [[paper](https://doi.org/10.48448/6y7n-5a37)]
- [2025] **Empirical tests of recursive and discrete scale-invariant cosmologies in a multi-modal theory of infinity** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.17926476)]
- [2025] **Core Applications and Techniques of RAG for Low-Resource Languages** *Science and Technology of Engineering Chemistry and Environmental Protection* [[paper](https://doi.org/10.61173/745jfc20)]
- [2025] **Advances in Spam Email Filtering: Integrating Deep Learning and Ensemble Methods** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18104802)]
- [2025] **A Survey on Acoustic Side-Channel Attacks: An Artificial Intelligence Perspective** *Journal of Cybersecurity and Privacy* [[paper](https://doi.org/10.3390/jcp6010006)]
- [2025] **Musicology as Data Science and Heritage Science** *Utrecht University Repository (Utrecht University)* [[paper](https://dspace.library.uu.nl/handle/1874/462414)]
- [2025] **Generative AI for Research: Paradigms, Tasks, Evaluation, and Best Practices** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202511.0421.v1)]
- [2025] **Enhancing SQL Query Learning Using Chatbot with NLP: A Methodical Review** [[paper](https://doi.org/10.1109/slaai-icai68534.2025.11318499)]
- [2025] **Smart Sign Language Interpreter for Text and Speech Conversion** *INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT* [[paper](https://doi.org/10.55041/ijsrem52921)]
- [2025] **Ethical implications of ChatGPT and other large language models in academia** *Frontiers in Artificial Intelligence* [[paper](https://doi.org/10.3389/frai.2025.1615761)]
- [2025] **Algorithmic Modeling of Generation Z’s Therapeutic Toys Consumption Behavior in an Emotional Economy Context** *Algorithms* [[paper](https://doi.org/10.3390/a18080506)]
- [2025] **A Comprehensive Analysis of Social Media’s Influence on English Vocabulary Development in Pakistan** *Inverge Journal of Social Sciences* [[paper](https://doi.org/10.63544/ijss.v4i3.161)]
- [2025] **Retrieval Augmented Generation Techniques for Processing Multi-Format Documents: A Comprehensive Survey** [[paper](https://doi.org/10.22541/au.175216954.43338458/v1)]
- [2025] **ADVANCES IN AUTOMATIC QUESTION GENERATION: A SURVEY OF AUTOMATIC QUESTION GENERATION TECHNIQUES, DATASETS, AND EVALUATION** *Bulletin of D Serikbayev EKTU* [[paper](https://doi.org/10.51885/1561-4212_2025_2_172)]
- [2025] **A Review of SoTL Research Methodologies: A Guide to Conceptualizing and Conducting the Scholarship of Teaching and Learning** *Asean Journal of Engineering Education* [[paper](https://doi.org/10.11113/ajee2025.9n1.192)]
- [2025] **Text-driven Motion Generation: Overview, Challenges and Directions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.09379)]
- [2025] **Survey of Abstract Meaning Representation: Then, Now, Future** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2505.03229)]
- [2025] **Authorship, Originality, and Linguistic Merits in the Era of Artificial Intelligence** *Journal of English Language Teaching* [[paper](https://doi.org/10.66121/08m1rd81)]
- [2025] **Leveraging Nature-Inspired Algorithms for Feature Selection in Sentiment Analysis: An Evaluation of Particle Swarm Optimization Effectiveness** [[paper](https://doi.org/10.1109/icvadv63329.2025.10961158)]
- [2025] **Knowledge Graph Combined with Retrieval-Augmented Generation for Enhancing LMs Reasoning: A Survey** *Academic Journal of Science and Technology* [[paper](https://doi.org/10.54097/h21fky45)]
- [2025] **Generative AI for synthetic data across multiple medical modalities: A systematic review of recent developments and challenges** *Computers in Biology and Medicine* [[paper](https://doi.org/10.1016/j.compbiomed.2025.109834)]
- [2025] **Diffusion and Flow Matching Models for Tabular Data: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.17119)]
- [2025] **A Survey on Bridging EEG Signals and Generative AI: From Image and Text to Beyond** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.12048)]
- [2025] **A Study the advantages and disadvantages of using the CHATGPT AI interface in academic research** *International Journal of Information Technology and Management* [[paper](https://doi.org/10.29070/8wetga52)]
- [2025] **The impact of paratext on readers of generative literature: Human evaluation of generated text** *ePrints Soton (University of Southampton)* [[paper](https://eprints.soton.ac.uk/505732/1/tkacz_final_corrected_dissertation.pdf)]
- [2025] **The impact of artificial intelligence on Sri Lanka libraries: an interview with Premila Gamage** *Digital Library Perspectives* [[paper](https://doi.org/10.1108/dlp-02-2025-154)]
- [2025] **Social networks in migration and migrant incorporation: New developments and challenges** *International Migration* [[paper](https://doi.org/10.1111/imig.13373)]
- [2025] **Picturing Dante's Commedia : A Review of Matthew Collins, ed., Reading Dante with Images: A Visual Lectura Dantis** *Italica* [[paper](https://doi.org/10.5406/23256672.102.1.10)]
- [2025] **Bridging Machine-Readable Code of Regulations and its Application on Generative AI: A Survey** *International Journal of Advanced Computer Science and Applications* [[paper](https://doi.org/10.14569/ijacsa.2025.0161050)]

##### 2024

- [2024] **Trustworthy Text-to-Image Diffusion Models: A Timely and Focused Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.18214)]
- [2024] **Next-Generation Text-to-SQL: A Survey of Advanced Reasoning Enhancements Techniques** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18137583)]
- [2024] **What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2408.14622)]
- [2024] **Commentary: Modernizing Educational Assessment Training for Changing Job Markets** *Educational Measurement Issues and Practice* [[paper](https://dx.doi.org/10.1111/emip.12629)]
- [2024] **Visualizing the Future of Medical Communication: Infographics and Their Impact on Academic Medicine** *Journal of Neurosurgical Anesthesiology* [[paper](https://doi.org/10.1097/ana.0000000000000970)]
- [2024] **Essays on Modern Chinese Engineering History** *JOURNAL OF ENGINEERING STUDIES* [[paper](https://dx.doi.org/10.3724/j.issn.1674-4969.20240058)]
- [2024] **Irish American Civil War Songs: Identity, Loyalty, and Nationhood by Catherine V. Bateson (review)** *Civil War history* [[paper](https://doi.org/10.1353/cwh.2024.a926943)]
- [2024] **Navigating the digital turn: recent books on technological integration in ELT** *ELT Journal* [[paper](https://doi.org/10.1093/elt/ccae014)]
- [2024] **The survey of GSM Wireless Data Communication System using the SPSS Method** *Computer Science Engineering and Technology* [[paper](https://doi.org/10.46632/cset/1/1/3)]
- [2024] **The Oxford Handbook of the Bible in Orthodox Christianity ed. by Eugen J. Pentiuc (review)** *The Catholic Biblical quarterly* [[paper](https://doi.org/10.1353/cbq.2024.a918397)]
- [2024] **The New Genetics of Sexuality** *GLQ A Journal of Lesbian and Gay Studies* [[paper](https://doi.org/10.1215/10642684-10938512)]
- [2024] **Review: Road Trip to Nowhere: Hollywood Encounters the Counterculture, by Jon Lewis** *California History* [[paper](https://doi.org/10.1525/ch.2024.101.1.70)]
- [2024] **Relevance of Professional Fisheries Certification in the 21st Century** *Fisheries* [[paper](https://doi.org/10.1002/fsh.11058)]

##### 2023

- [2023] **Reviewer #1 (Public Review): Repeatability of adaptation in sunflowers reveals that genomic regions harbouring inversions also drive adaptation in species lacking an inversion** [[paper](https://dx.doi.org/10.7554/elife.88604.3.sa1)]
- [2023] **Characterization of a new HIV-1 second-generation circulating recombinant form (CRF170_0107) among men who have sex with men in Yunnan, China** *Journal of Infection* [[paper](https://doi.org/10.1016/j.jinf.2023.12.009)]
- [2023] **Reviewer #2 (Public Review): Multiomics analyses reveal dynamic bioenergetic pathways and functional remodeling of the heart during intermittent fasting** [[paper](https://dx.doi.org/10.7554/elife.89214.2.sa2)]
- [2023] **Reviewer #1 (Public Review): Multiomics analyses reveal dynamic bioenergetic pathways and functional remodeling of the heart during intermittent fasting** [[paper](https://dx.doi.org/10.7554/elife.89214.2.sa1)]

[⬆ Back to top](#paper-list)

#### Narrative Arc

##### 2023

- [2023] **Exploring the Latest Applications of OpenAI and ChatGPT: An In-Depth Survey** *Computer Modeling in Engineering & Sciences* [[paper](https://doi.org/10.32604/cmes.2023.030649)]

[⬆ Back to top](#paper-list)

#### Editing Assistance

##### 2026

- [2026] **Data security in large language models: risks, defense, and directions** *Journal of King Saud University - Computer and Information Sciences* [[paper](https://doi.org/10.1007/s44443-026-01200-9)]
- [2026] **Large Language Models in Intelligent Education Systems: New Educational Perspectives—A Systematic Review** *Information* [[paper](https://doi.org/10.3390/info17050433)]
- [2026] **AI-Powered Mock Interview Web Application** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.83223)]
- [2026] **[Retracted] Biogenic synthesis of Silver-decorated Cobalt Ferrite nanoparticles using Moringa oleifera leaf extract: Antibacterial and catalytic performance** *Materials Nanoscience* [[paper](https://doi.org/10.62110/sciencein.mns.2026.v13.1801)]
- [2026] **Revisiting computer authorship: a longitudinal perspective** *AI & Society* [[paper](https://doi.org/10.1007/s00146-025-02783-z)]

##### 2025

- [2025] **Artificial intelligence in academic literacy: empirical evidence on reading and writing practices in higher education** *Frontiers in Education* [[paper](https://doi.org/10.3389/feduc.2025.1701238)]
- [2025] **A Survey on Voice-Based 2D AI-Powered Mock Interview Assistant** *IJARCCE* [[paper](https://doi.org/10.17148/ijarcce.2025.14611)]
- [2025] **Saudade, Manhã, Tristesse de la Lune e La Cloche Fêlée: edição, análise interpretativa e subsídios para performance de 4 canções de Ernani Braga** *LA Referencia (Red Federada de Repositorios Institucionales de Publicaciones Científicas)* [[paper](https://repositorio.ufrn.br/handle/123456789/63857)]
- [2025] **STAR Recommendations: A novel framework for generating recommendations** *Chinese Medical Journal* [[paper](https://doi.org/10.1097/cm9.0000000000003475)]

##### 2024

- [2024] **The Influence of User-Generated Beauty Content on Xiaohongshu on the Purchase Decisions of Generation Z Chinese Women** *Advances in Economics Management and Political Sciences* [[paper](https://doi.org/10.54254/2754-1169/2024.ga18927)]
- [2024] **The future of JSR : Hybrid or Open Access publishing, and launch of a sister journal?** *Journal of Sleep Research* [[paper](https://doi.org/10.1111/jsr.14234)]
- [2024] **The Revolution of Multimodal Large Language Models: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.12451)]

##### 2023

- [2023] **Reinforcement Learning in Natural Language Processing: A Survey** [[paper](https://doi.org/10.1145/3639479.3639496)]
- [2023] **Uncovering the true burden of hereditary angioedema due to C1-inhibitor deficiency: A focus on the Asia-Pacific region** *Journal of Allergy and Clinical Immunology* [[paper](https://doi.org/10.1016/j.jaci.2023.09.039)]

[⬆ Back to top](#paper-list)

#### Persona Control

##### 2026

- [2026] **A comprehensive review of use cases, misuses, and potential mitigation techniques in generative artificial intelligence** *Neural Networks* [[paper](https://doi.org/10.1016/j.neunet.2026.109073)]
- [2026] **LLM-Based Intelligent Notification Composition: From Static Personalization to Context-Aware Persuasive Messaging** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.16264)]

##### 2025

- [2025] **Cohort Profile: Cooperative Health Research in the Region of Augsburg (KORA) 1984–2024** *International Journal of Epidemiology* [[paper](https://doi.org/10.1093/ije/dyaf187)]
- [2025] **Editorial note Volume 54 Issue 1** *Family and Consumer Sciences Research Journal* [[paper](https://doi.org/10.1002/fcsr.70028)]
- [2025] **ABS0711 PRIORITY SETTING OF PHYSICAL ACTIVITY BARRIERS AND FACILITATORS AMONG INDIVIDUALS WITH RHEUMATOID ARTHRITIS: A NOMINAL GROUP TECHNIQUE STUDY** *Annals of the Rheumatic Diseases* [[paper](https://doi.org/10.1016/j.ard.2025.06.1582)]
- [2025] **Clinical document corpora—real ones, translated and synthetic substitutes, and assorted domain proxies: a survey of diversity in corpus design, with focus on German text data** *JAMIA Open* [[paper](https://doi.org/10.1093/jamiaopen/ooaf024)]
- [2025] **LLM on the edge: the new frontier** [[paper](https://doi.org/10.55056/ceur-ws.org/vol-3943/paper28.pdf)]
- [2025] **Exploring the usage demands of AIGC functions among Chinese researchers: A study based on the KANO model** *Information Development* [[paper](https://doi.org/10.1177/02666669241313369)]

##### 2024

- [2024] **Research on the applicability of generative artificial intelligence in image generation** [[paper](https://doi.org/10.1201/9781003514831-75)]
- [2024] **Wittenberger Universitätstheologie im frühen 17. Jahrhundert. Eine Fallstudie zu Friedrich Balduin (1575–1627) by Daniel Bohnert (review)** *Lutheran quarterly* [[paper](https://doi.org/10.1353/lut.2024.a921454)]
- [2024] **History, Development, and Principles of Large Language Models-An Introductory Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2402.06853)]

##### 2023

- [2023] **Research on Consumer Preferences and Potential Users of Vacuum Cleaning Robots-Based on Text Mining and Questionnaire Surveys** *Advances in transdisciplinary engineering* [[paper](https://dx.doi.org/10.3233/atde231002)]

[⬆ Back to top](#paper-list)

#### Factuality Control

##### 2026

- [2026] **Scalability of CIBER's Evidence Retrieval and Its Impact on Scientific Claim Verification Accuracy with Up to 1000 Documents** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20636929)]
- [2026] **AI-BASED VERIFICATION OF LLM RESPONSE** *IJARCCE* [[paper](https://doi.org/10.17148/ijarcce.2026.15574)]
- [2026] **A Survey of Audio Reasoning in Multimodal Foundation Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.21008)]
- [2026] **Factuality and Hallucinations in Large Language Models: A Comprehensive Survey** [[paper](https://doi.org/10.36227/techrxiv.177155933.37903126/v1)]
- [2026] **Hallucination as Boundary-access Failure: A Structural Account** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.6629178)]
- [2026] **A Taxonomy of Large Language Model Hallucination Detection Methods: Approaches, Evaluation Strategies, Challenges, and Open Research Problems** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.7299799)]
- [2026] **A Survey on the Evolving Journey of Generative AI: From Language Models to Multimodal Intelligence** *International Research Journal of Modernization in Engineering Technology and Science* [[paper](https://doi.org/10.56726/irjmets86382)]

##### 2025

- [2025] **Empowering Access to Public Services: An Analysis on Multimodal, Retrieval-Augmented Chatbots for Indic Language Support to Farmers** [[paper](https://doi.org/10.1109/ism66958.2025.00050)]
- [2025] **A Survey on Data Security in Large Language Models** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2508.02312)]
- [2025] **A Survey of Multimodal Retrieval-Augmented Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2504.08748)]
- [2025] **A Survey of State of the Art Large Vision Language Models: Alignment, Benchmark, Evaluations and Challenges** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.02189)]

##### 2024

- [2024] **Retrieval-Augmented Generation: Architectures, Advances, and Real-World Applications** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19584952)]

[⬆ Back to top](#paper-list)

#### Human Evaluation

##### 2026

- [2026] **Aktarım Zinciri / The Transmission Chain** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22093227)]

##### 2025

- [2025] **Transfer Learning for Text-To-Image Diffusion Models: Methods, Challenges, and Applications** *International Journal of Innovative Research in Advanced Engineering* [[paper](https://doi.org/10.26562/ijirae.2025.v1211.12)]

##### 2024

- [2024] **A Survey of Data-Driven 2D Diffusion Models for Generating Images from Text** *EAI Endorsed Transactions on AI and Robotics* [[paper](https://dx.doi.org/10.4108/airo.5453)]

[⬆ Back to top](#paper-list)

#### Benchmark Datasets

##### 2026

- [2026] **Collaborative Control in Diffusion Models for Precise Image Generation: A Survey** *Mathematics* [[paper](https://doi.org/10.3390/math14152737)]
- [2026] **Replication package: forward-snowballing update of a systematic literature review on developer experience and developer productivity** *Figshare* [[paper](https://doi.org/10.6084/m9.figshare.33123611)]
- [2026] **Automatic Sign Language Generation Systems for Accessible Human–Hearing-Impaired Communication** [[paper](https://doi.org/10.1109/iciics67880.2026.11483565)]
- [2026] **A Survey of Large Language Models for Text-Guided Molecular Discovery: From Molecule Generation to Optimization** *Underline Science Inc.* [[paper](https://doi.org/10.48448/0yya-4144)]
- [2026] **A Comprehensive Survey of Process Reward Models: Data Generation, Model Construction, and Usage** *Underline Science Inc.* [[paper](https://doi.org/10.48448/t34v-ws69)]
- [2026] **Multimodal Large Language Model-Enabled Video Translation: A Role-Oriented Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.11283)]
- [2026] **Audio generation through score-based generative modeling: design principles and implementation** *Foundations and Trends® in Signal Processing* [[paper](https://arxiv.org/abs/2506.08457)]
- [2026] **Generative AI for Text-to-Video Generation: Recent Advances and Future Directions** *Digital* [[paper](https://doi.org/10.3390/digital6010023)]
- [2026] **Generative AI and the Foundation Model Era: A Comprehensive Review** *Big Data and Cognitive Computing* [[paper](https://doi.org/10.3390/bdcc10030094)]
- [2026] **Cohort Profile: Generation Victoria (GenV)** *International Journal of Epidemiology* [[paper](https://doi.org/10.1093/ije/dyag028)]
- [2026] **Towards Visual Chain-of-Thought Reasoning: A Comprehensive Survey** [[paper](https://doi.org/10.36227/techrxiv.176964090.06440051/v1)]
- [2026] **A survey on text-driven visual generation: advances, frameworks, and future directions** *Advances in Engineering Innovation* [[paper](https://doi.org/10.54254/2977-3903/2026.31448)]
- [2026] **A Comprehensive Review of LLM-based Text-to-SQL Systems: Methods, Datasets, and Trends** *Computational Systems and Artificial Intelligence* [[paper](https://doi.org/10.69882/adba.csai.2026011)]

##### 2025

- [2025] **Assessing RAG: A Comprehensive Review of Evaluation Frameworks** [[paper](https://doi.org/10.1109/iccike67021.2025.11318213)]
- [2025] **Content Generation Models in Computational Pathology: A Comprehensive Survey on Methods, Applications, and Challenges** *IEEE Reviews in Biomedical Engineering* [[paper](https://doi.org/10.1109/rbme.2025.3619086)]
- [2025] **A Comprehensive Review of Datasets for Clinical Mental Health AI Systems** *TUbilio (Technical University of Darmstadt)* [[paper](https://arxiv.org/abs/2508.09809)]
- [2025] **Applications and Future Perspectives of Large Language Models in Otolaryngology-Head and Neck Surgery: A Comprehensive Survey** *Clinical and Experimental Otorhinolaryngology* [[paper](https://doi.org/10.21053/ceo.2025-00121)]
- [2025] **A Survey on the Ethnomedicinal claims of Blumea lanceolaria (Roxb.) Druce - An Anukta Dravya** *Journal of Ayurveda and Integrated Medical Sciences* [[paper](https://doi.org/10.21760/jaims.10.6.11)]
- [2025] **Vision-Language Modeling Meets Remote Sensing: Models, datasets, and perspectives** *IEEE Geoscience and Remote Sensing Magazine* [[paper](https://arxiv.org/abs/2505.14361)]
- [2025] **Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2507.02900)]
- [2025] **Implicit Bias in LLMs: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2503.02776)]
- [2025] **Visual question answering: from early developments to recent advances -- a survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2501.03939)]

##### 2024

- [2024] **From Complexity to Simplicity: Advancements in Large Language Model Compression** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202412.2132.v1)]
- [2024] **Clinical Document Corpora -- Real Ones, Translated and Synthetic Substitutes, and Assorted Domain Proxies: A Survey of Diversity in Corpus Design, with Focus on German Text Data** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2412.00230)]
- [2024] **Diffusion Models in 3D Vision: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2410.04738)]
- [2024] **What is the Role of Large Language Models in the Evolution of Astronomy Research?** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2409.20252)]
- [2024] **A Comprehensive Survey on Human Video Generation: Challenges, Methods, and Insights** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2407.08428)]
- [2024] **From Sora What We Can See: A Survey of Text-to-Video Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2405.10674)]
- [2024] **What Are Tools Anyway? A Survey from the Language Model Perspective** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2403.15452)]
- [2024] **The Gricean Maxims in NLP - A Survey** [[paper](https://doi.org/10.18653/v1/2024.inlg-main.39)]

##### 2023

- [2023] **When Near Becomes Far: Old Age in Rabbinic Literature by Mira Balberg and Haim Weiss (review)** *AJS Review The Journal of the Association for Jewish Studies* [[paper](https://doi.org/10.1353/ajs.2023.a911532)]
- [2023] **Generations: The Real Differences between Gen Z, Millennials, Gen X, Boomers, and Silents—and What They Mean for America’s Future** *Perspectives on Science and Christian Faith* [[paper](https://doi.org/10.56315/pscf12-23twenge)]

[⬆ Back to top](#paper-list)

#### Academic Writing

##### 2026

- [2026] **Akkermansia and Bacteroides Abundance, Significance, and Therapeutic Potential in Obesity and Associated Metabolic Dysfunction by Systematic Review of Clinical and Sequencing Data** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18462302)]

##### 2025

- [2025] **A Survey on Text-Driven 360° Panorama Generation** *IEEE Transactions on Circuits and Systems for Video Technology* [[paper](https://doi.org/10.1109/tcsvt.2025.3628738)]
- [2025] **A Survey on Text-Driven 360-Degree Panorama Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2502.14799)]

##### 2024

- [2024] **Related Work and Citation Text Generation: A Survey** [[paper](https://doi.org/10.18653/v1/2024.emnlp-main.767)]

##### 2023

- [2023] **Beyond Imitation: Exploring Novelty in Generative AI** *International Journal of Advanced Research in Science Communication and Technology* [[paper](https://doi.org/10.48175/ijarsct-13070)]

[⬆ Back to top](#paper-list)

#### Business Writing

##### 2026

- [2026] **Semantic-Preserving Graph Augmentations Enhance Robustness in Cross-Domain Code Generation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20482743)]
- [2026] **Mapping and synthesising the evidence on dietary acculturation and identify factors influencing post-migration dietary behaviours among Indian immigrants in Australia, Canada, New Zealand, and the UK: A scoping review protocol** *OSF Preprints (OSF Preprints)* [[paper](https://osf.io/hpb7w)]

##### 2025

- [2025] **Ethnic inequalities and contraception in Latin America and the Caribbean: a scoping review** *International Journal for Equity in Health* [[paper](https://doi.org/10.1186/s12939-025-02501-7)]
- [2025] **Building a Novel Question-Answering System using Retrieval-Augmented Generation for the California Fair Political Practices Commission** *DigitalCommons - CalPoly (California State Polytechnic University)* [[paper](https://digitalcommons.calpoly.edu/theses/3158)]
- [2025] **Modern approaches to predicting vaccine hesitancy: A scoping review** *medRxiv* [[paper](https://doi.org/10.1101/2025.01.29.25321367)]

##### 2024

- [2024] **Corrigendum: Eating behavior of adolescent girls in countries with a high prevalence of stunting under five: a systematic review** *Frontiers in Psychology* [[paper](https://doi.org/10.3389/fpsyg.2024.1530934)]
- [2024] **Verdicts on the optimization of corporate insolvency legal frameworks for sustainable development in Tanzania and Mauritius** *International Journal of Law and Management* [[paper](https://doi.org/10.1108/ijlma-09-2024-0324)]
- [2024] **What we have learned about learning to read in a digital age and children's contemporary reading experiences** *Journal of Research in Reading* [[paper](https://doi.org/10.1111/1467-9817.12472)]
- [2024] **An innovative learning strategy for improving clinical judgment among undergraduate nursing students: A reflection** *Journal of Nursing Education and Practice* [[paper](https://doi.org/10.5430/jnep.v14n7p13)]
- [2024] **Undergraduate Psychiatric Education in SAARC Countries** *Journal of SAARC Psychiatric Federation* [[paper](https://doi.org/10.4103/jspf.jspf_8_25)]
- [2024] **CHAT-GPT: A CLEVER SEARCH ENGINE OR A CREATIVE DESIGN ASSISTANT FOR STUDENTS AND INDUSTRY?** [[paper](https://doi.org/10.35199/epde.2024.70)]

##### 2023

- [2023] **Heart Failure Epidemiology and Outcomes Statistics: A Report of the Heart Failure Society of America** *Journal of Cardiac Failure* [[paper](https://doi.org/10.1016/j.cardfail.2023.07.006)]

[⬆ Back to top](#paper-list)

#### Code Generation

##### 2024

- [2024] **Large Language Models, Fine Tuning, Code Generation** [[paper](https://doi.org/10.1109/cando-epe65072.2024.10772760)]

[⬆ Back to top](#paper-list)

#### Multimodal Writing

##### 2026

- [2026] **Vision-Language Models for medical imaging: A survey on anomaly detection and multimodal applications** *Knowledge-Based Systems* [[paper](https://doi.org/10.1016/j.knosys.2026.116901)]
- [2026] **Explicit Content Generation in Text-to-Image Models: Training Mechanisms, Moderation Failures, and Safety Limits** *Indian Journal of Computer Science and Technology* [[paper](https://doi.org/10.59256/indjcst.20260502111)]
- [2026] **Towards High-Level Semantic Intelligence** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.24082)]
- [2026] **Data- and knowledge-driven multimodal learning in computational pathology: A comprehensive survey** *EngMedicine* [[paper](https://doi.org/10.1016/j.engmed.2026.100132)]
- [2026] **Conformal Prediction in the Age of Multimodal Foundation Models: A Survey** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-15120-9_13)]

##### 2025

- [2025] **It's All Connected: A Survey for Multimodal Arabic AI** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8007923/v1)]
- [2025] **Explainable AI for Clinical Decision Support: SHAP and Grad-CAM in Text- and Image-Based Medical Predictions** *International Journal For Multidisciplinary Research* [[paper](https://doi.org/10.36948/ijfmr.2025.v07i06.60343)]
- [2025] **Multimodal named entity recognition in the era of large pre-trained models: A comprehensive survey** *Information Fusion* [[paper](https://doi.org/10.1016/j.inffus.2025.103767)]
- [2025] **A Survey on Pre-trained Language Models Based on Deep Learning: Technological Development and Applications** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2025.po24899)]
- [2025] **Generalizing sentiment analysis: a review of progress, challenges, and emerging directions** *Social Network Analysis and Mining* [[paper](https://doi.org/10.1007/s13278-025-01461-8)]
- [2025] **MMA-RAG: A Survey on Multimodal Agentic Retrieval-Augmented Generation** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5630330)]
- [2025] **Exploring Multimodal Embeddings for Text and Impact on Language Processing** *SSRN Electronic Journal* [[paper](https://doi.org/10.2139/ssrn.5189610)]

##### 2024

- [2024] **Strategies of Building AI Agents for Multimodal Productivity with Contemporary Large Language Models** *Applied and Computational Engineering* [[paper](https://doi.org/10.54254/2755-2721/2025.20428)]
- [2024] **A Survey of AI-Generated Content (AIGC)** *ACM Computing Surveys* [[paper](https://doi.org/10.1145/3704262)]
- [2024] **Jailbreak Attacks and Defenses against Multimodal Generative Models: A Survey** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2411.09259)]

##### 2023

- [2023] **Semantic speech analysis using machine learning and deep learning techniques: a comprehensive review** *Multimedia Tools and Applications* [[paper](https://doi.org/10.1007/s11042-023-17769-6)]

[⬆ Back to top](#paper-list)

<!-- END PAPER LIST -->

## 🔧 Pipeline

```
config/taxonomy.yaml ──► papers.yaml ──► validate_papers.py
                          │   ▲              │
                          ▼   └── fetch_* ───┘
                   generate_readme.py ──► README.md paper list (auto)
                          │
                          ▼
                  standard_stats.py ──► statistics.json, docs/papers.json,
                                        README.md corpus statistics (auto)
```

## 🚀 Quick Start

```bash
# Fetch papers (arXiv + OpenAlex)
python3 scripts/fetch/fetch_new_papers.py --months 36 --local
python3 scripts/fetch/fetch_openalex_bulk.py --months 36 --per-category 500 --local

# Validate + generate
python3 scripts/validate_papers.py
python3 scripts/generate_readme.py
python3 scripts/standard_stats.py

# Unit tests
python3 -m pytest
```

## 🤖 Agent Workflow

See `AGENTS.md` for guidelines on working with this repo programmatically.

## 📄 License

MIT
