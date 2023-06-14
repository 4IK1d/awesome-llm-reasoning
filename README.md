# awesome-llm-reasoning
Collections of resources for LLM reasoning, including papers, codes and data. 
There are numbers of awesome repos focus on reasoning of LLM, we try to summarize these methods in a different angle, their specific domain,
such common reasoning, math, table related, KG relate or multimodal(welcome to name them more).

*We try to give a comprehensive view of resources, thus papers here may not be well evaluated by now for the sake of time, any suggestion are well appreciated!*

[![Awesome](https://awesome.re/badge.svg)](https://github.com/4IK1d/awesome-llm-reasoning/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/4IK1d/awesome-llm-reasoning?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)

# Tool-augmented/oriented Reasoning

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [Augmented Language Models: a Survey](https://arxiv.org/pdf/2302.07842.pdf)  | / | / |
|  [Tool Learning with Foundation Models](https://arxiv.org/abs/2304.08354)  | [project](https://github.com/OpenBMB/BMTools) | [ToolBench](https://github.com/OpenBMB/ToolBench) |
|  [Behavior Cloned Transformers are Neurosymbolic Reasoners](https://arxiv.org/pdf/2210.07382.pdf)  | [neurosymbolic](https://github.com/cognitiveailab/neurosymbolic/) | [TWC](https://github.com/IBM/commonsense-rl)/[MapReader](https://living-with-machines.github.io/MapReader/) |
|  [RECITATION-AUGMENTED LANGUAGE MODELS](https://arxiv.org/pdf/2210.01296.pdf)  | [RECITE](https://github.com/Edward-Sun/RECITE) | [NaturalQuestions](https://ai.google.com/research/NaturalQuestions)/[TriviaQA](http://nlp.cs.washington.edu/triviaqa/)/[hotpotqa](https://paperswithcode.com/dataset/hotpotqa)|
|  [MIND’S EYE: GROUNDED LANGUAGE MODEL REASONING THROUGH SIMULATION](https://arxiv.org/pdf/2210.05359.pdf)  | / | [MuJoCo](https://mujoco.org/) |
|  [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/pdf/2211.12588.pdf)  | [Program-of-Thoughts](https://github.com/wenhuchen/Program-of-Thoughts) | [data](https://github.com/wenhuchen/Program-of-Thoughts) |
|  [SHOW YOUR WORK: SCRATCHPADS FOR INTERMEDIATE COMPUTATION WITH LANGUAGE MODELS](https://arxiv.org/pdf/2112.00114.pdf)  | [PAL](https://github.com/reasoning-machines/pal) | [data](https://github.com/reasoning-machines/pal/tree/main/datasets) |




# Table-based Reasoning

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [StructGPT: A General Framework for Large Language Model to Reason over Structured Data](https://arxiv.org/pdf/2305.09645.pdf)  | [code](https://github.com/RUCAIBox/StructGPT) | [data](https://drive.google.com/drive/folders/11_2pqU_MhEtmxpp3zfK_8EJ1bbQzsnfJ?usp=sharing) / [raw](https://github.com/HKUNLP/UnifiedSKG) |
|  [Large Language Models are Effective Table-to-Text Generators, Evaluators, and Feedback Providers](https://arxiv.org/abs/2305.14987)  | [code](https://github.com/yilunzhao/LLM-T2T) | [data](https://github.com/yilunzhao/LLM-T2T) |
|  [Large Language Models are few(1)-shot Table Reasoners](https://arxiv.org/pdf/2210.06710.pdf)  | [code](https://github.com/wenhuchen/TableCoT) | [WikiTableQuestions](https://ppasupat.github.io/WikiTableQuestions/) / [FetaQA](https://arxiv.org/pdf/2104.00369v1.pdf) / [TabFact](https://tabfact.github.io/) / [FEVEROUS](https://fever.ai/dataset/feverous.html)|
|  [OmniTab: Pretraining with Natural and Synthetic Data for Few-shot Table-based Question Answering](https://arxiv.org/pdf/2207.03637.pdf)  | [code](https://github.com/jzbjyb/OmniTab) | [data](https://drive.google.com/drive/u/1/folders/14IAqJb9ObVDE5oOJouhkqgd_mn11PkYY) |
|  [REASTAP: Injecting Table Reasoning Skills During Pre-training via Synthetic Reasoning Examples](https://arxiv.org/pdf/2210.12374.pdf)  | [code](https://github.com/Yale-LILY/ReasTAP) | [data](https://drive.google.com/drive/folders/1YRmRibz_fVZbrb2W1ynFWS6h-uwJw0oN?usp=sharing) |
|  [Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning](https://arxiv.org/pdf/2301.13808)  | [code](https://github.com/AlibabaResearch/DAMO-ConvAI) | [WikiTableQuestions](https://drive.google.com/drive/u/1/folders/14IAqJb9ObVDE5oOJouhkqgd_mn11PkYY) / [FetaQA](https://arxiv.org/pdf/2104.00369v1.pdf) |
|  [Evaluating and Enhancing Structural Understanding Capabilities of Large Language Models on Tables via Input Designs](https://arxiv.org/pdf/2305.13062.pdf)  | [code](https://github.com/RUCAIBox/POPE) | [HybridQA](https://github.com/wenhuchen/HybridQA) / [ToTTo](https://github.com/google-research-datasets/totto) / [TabFact](https://tabfact.github.io/) / [FEVEROUS](https://fever.ai/dataset/feverous.html) |
|  [Enhancing Few-shot Text-to-SQL Capabilities of Large Language Models: A Study on Prompt Design Strategies](https://arxiv.org/pdf/2305.13062.pdf)  | [code](https://github.com/linyongnan/STRIKE) | [data](https://github.com/linyongnan/STRIKE) |

# Related Fields

## Hallucination Evaluation

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/pdf/2305.10355.pdf)  | [code](https://anonymous.4open.science/r/StructuredLLM-76F3) | [MSCOCO](https://cocodataset.org/) / [SQA](https://www.microsoft.com/en-us/download/details.aspx?id=54253) / [A-OKVQA](https://allenai.org/project/a-okvqa/home) / [GQA](https://cs.stanford.edu/people/dorarad/gqa/) |
|  [HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models](https://arxiv.org/pdf/2305.11747.pdf)  | [code](https://github.com/RUCAIBox/HaluEval) | [data](https://github.com/RUCAIBox/HaluEval) |

<!-- |  [Large Language Models are few(1)-shot Table Reasoners](https://arxiv.org/pdf/2210.06710.pdf)  | [code](https://github.com/wenhuchen/TableCoT) | |
|  [OmniTab: Pretraining with Natural and Synthetic Data for Few-shot Table-based Question Answering](https://arxiv.org/pdf/2207.03637.pdf)  | [code](https://github.com/jzbjyb/OmniTab) | [data](https://drive.google.com/drive/u/1/folders/14IAqJb9ObVDE5oOJouhkqgd_mn11PkYY) |
|  [REASTAP: Injecting Table Reasoning Skills During Pre-training via Synthetic Reasoning Examples](https://arxiv.org/pdf/2210.12374.pdf)  | [code](https://github.com/Yale-LILY/ReasTAP) | [data](https://drive.google.com/drive/folders/1YRmRibz_fVZbrb2W1ynFWS6h-uwJw0oN?usp=sharing) |
|  [Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning](https://arxiv.org/pdf/2301.13808)  | [code](https://github.com/AlibabaResearch/DAMO-ConvAI) | [WikiTableQuestions](https://drive.google.com/drive/u/1/folders/14IAqJb9ObVDE5oOJouhkqgd_mn11PkYY) / [FetaQA](https://arxiv.org/pdf/2104.00369v1.pdf) | -->

## Refer to Awesome Lists

We are standing on the shoulders of giants, inspired and borrow a lot from them.

- **[Awesome-Multimodal-Reasoning](https://github.com/atfortes/Awesome-Multimodal-Reasoning)**  Collection of papers and resources on Multimodal Reasoning, including Vision-Language Models, Multimodal Chain-of-Thought, Visual Inference, and others.
- **[Chain-of-ThoughtsPapers](https://github.com/Timothyxxx/Chain-of-ThoughtsPapers)**  A trend starts from "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models".
- **[LM-reasoning](https://github.com/jeffhj/LM-reasoning)**  Collection of papers and resources on Reasoning in Large Language Models.
- **[Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers)**  Repository for the paper "Reasoning with Language Model Prompting: A Survey".
- **[ReasoningNLP](https://github.com/FreedomIntelligence/ReasoningNLP)**  Paper list on reasoning in NLP
- **[Instruction-Tuning-Papers](https://github.com/SinclairCoder/Instruction-Tuning-Papers)**  Reading list of Instruction-tuning.
- **[Deep-Reasoning-Papers](https://github.com/floodsung/Deep-Reasoning-Papers)**  Recent Papers including Neural Symbolic Reasoning, Logical Reasoning, Visual Reasoning, planning and any other topics connecting deep learning and reasoning.
- **[Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)**  Curated list of Large Language Model.
