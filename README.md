# awesome-llm-reasoning
Collections of resources for LLM reasoning, including papers, codes and data. 
There are numbers of awesome repos focus on reasoning of LLM, we try to summarize these methods in a different angle, their specific domain,
such common reasoning, math, table related, KG relate or multimodal(welcome to name them more).

*We try to give a comprehensive view of resources, thus papers here may not be well evaluated by now for the sake of time, any suggestion are well appreciated!*

[![Awesome](https://awesome.re/badge.svg)](https://github.com/4IK1d/awesome-llm-reasoning/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/4IK1d/awesome-llm-reasoning?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)

<!-- # Math Reasoning -->

<!-- 
Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning|https://arxiv.org/abs/2209.14610|PromptPG|https://github.com/lupantech/PromptPG|TabMWP|https://promptpg.github.io/
 -->
 
<!--  # Robotic -->

<!-- multi-modal -->

<!-- 
Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language|https://arxiv.org/pdf/2204.00598.pdf|Socratic Models|https://socraticmodels.github.io/#code|data|https://socraticmodels.github.io/
Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models|https://arxiv.org/pdf/2303.04671.pdf|TaskMatrix|https://github.com/microsoft/TaskMatrix|data||
 -->
 

# Tool-augmented/oriented Reasoning

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [Augmented Language Models: a Survey](https://arxiv.org/pdf/2302.07842.pdf)  | / | / |
|  [Tool Learning with Foundation Models](https://arxiv.org/abs/2304.08354)  | [project](https://github.com/OpenBMB/BMTools) | [ToolBench](https://github.com/OpenBMB/ToolBench) |
|  [Behavior Cloned Transformers are Neurosymbolic Reasoners](https://arxiv.org/pdf/2210.07382.pdf)  | [neurosymbolic](https://github.com/cognitiveailab/neurosymbolic/) | [TWC](https://github.com/IBM/commonsense-rl)/[MapReader](https://living-with-machines.github.io/MapReader/) |
|  [RECITATION-AUGMENTED LANGUAGE MODELS](https://arxiv.org/pdf/2210.01296.pdf)  | [RECITE](https://github.com/Edward-Sun/RECITE) | [NaturalQuestions](https://ai.google.com/research/NaturalQuestions)/[TriviaQA](http://nlp.cs.washington.edu/triviaqa/)/[hotpotqa](https://paperswithcode.com/dataset/hotpotqa)|
|  [MIND’S EYE: GROUNDED LANGUAGE MODEL REASONING THROUGH SIMULATION](https://arxiv.org/pdf/2210.05359.pdf)  | / | [MuJoCo](https://mujoco.org/) |
|  [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/pdf/2211.12588.pdf)  | [Program-of-Thoughts](https://github.com/wenhuchen/Program-of-Thoughts) | [data](https://github.com/wenhuchen/Program-of-Thoughts) |
|  [PAL: Program-aided Language Models](https://arxiv.org/pdf/2211.10435.pdf)  | [PAL](https://github.com/reasoning-machines/pal) | [data](https://github.com/reasoning-machines/pal/tree/main/datasets) |
|  [SHOW YOUR WORK: SCRATCHPADS FOR INTERMEDIATE COMPUTATION WITH LANGUAGE MODELS](https://arxiv.org/pdf/2112.00114.pdf)  | / | / |
|  [GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information(Domain Tool)](https://arxiv.org/pdf/2304.09667.pdf)  | / | [GeneTuring](https://www.biorxiv.org/content/10.1101/2023.03.11.532238v1) |

<!-- 
Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models|https://arxiv.org/pdf/2304.09842.pdf|Chameleon|https://chameleon-llm.github.io/|ScienceQA|https://scienceqa.github.io/|TabMWP|https://promptpg.github.io/
Program of thoughts prompting: Disentangling computation from reasoning for numerical reasoning tasks|https://arxiv.org/abs/2211.12588|code|https://github.com/wenhuchen/Program-of-Thoughts|data|https://github.com/wenhuchen/Program-of-Thoughts
ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases|https://arxiv.org/pdf/2306.05301.pdf|code||data||
TALM: Tool Augmented Language Models|https://arxiv.org/pdf/2205.12255.pdf|code||NaturalQuestions|https://ai.google.com/research/NaturalQuestions|MathQA|https://math-qa.github.io/math-QA/
Adaptive Chameleon or Stubborn Sloth: Unraveling the Behavior of Large Language Models in Knowledge Clashes|https://arxiv.org/pdf/2305.13300.pdf|LLM-knowledge-conflict|https://github.com/OSU-NLP-Group/LLM-Knowledge-Conflict|conflictQA|https://github.com/OSU-NLP-Group/LLM-Knowledge-Conflict/tree/main/conflictQA
On the Tool Manipulation Capability of Open-source Large Language Models|https://arxiv.org/pdf/2305.16504.pdf|ToolBench|https://github.com/sambanova/toolbench|ToolBench|https://github.com/sambanova/toolbench
CREATOR: Disentangling Abstract and Concrete Reasonings of Large
Language Models through Tool Creation|https://arxiv.org/pdf/2305.14318.pdf|code||MATH|https://github.com/hendrycks/math/|abMWP|https://promptpg.github.io/
HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace|https://arxiv.org/pdf/2303.17580.pdf|huggingGPT|https://github.com/microsoft/JARVIS|data|https://github.com/microsoft/JARVIS|
ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings|https://arxiv.org/pdf/2305.11554.pdf|/||/||
WebGPT: Browser-assisted question-answering with human feedback|https://arxiv.org/abs/2112.09332|/||/||
WebCPM: Interactive Web Search for Chinese Long-form Question Answering|https://arxiv.org/abs/2305.06849|webcpm|https://github.com/thunlp/WebCPM|data|https://github.com/thunlp/WebCPM
 -->


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
|  [Can LLM Already Serve as A Database Interface? A BIg Bench for Large-Scale Database Grounded Text-to-SQL](https://arxiv.org/abs/2305.03111)  | [BIRD](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/bird) | [data](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/bird) |

# Related Fields

## Hallucination Evaluation

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/pdf/2305.10355.pdf)  | [code](https://anonymous.4open.science/r/StructuredLLM-76F3) | [MSCOCO](https://cocodataset.org/) / [SQA](https://www.microsoft.com/en-us/download/details.aspx?id=54253) / [A-OKVQA](https://allenai.org/project/a-okvqa/home) / [GQA](https://cs.stanford.edu/people/dorarad/gqa/) |
|  [HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models](https://arxiv.org/pdf/2305.11747.pdf)  | [code](https://github.com/RUCAIBox/HaluEval) | [data](https://github.com/RUCAIBox/HaluEval) |
<!-- 
HISTALIGN: Improving Context Dependency in Language Generation by Aligning with History|https://arxiv.org/pdf/2305.04782.pdf|histalign|https://github.com/meetdavidwan/histalign|FactCC|https://github.com/salesforce/factCC|DAE|https://github.com/tagoyal/factuality-datasets|LogicNLG|https://github.com/wenhuchen/LogicNLG/tree/master/data
Inference-Time Intervention: Eliciting Truthful Answers from a Language Model|https://arxiv.org/pdf/2306.03341.pdf|honest_llama|https://github.com/likenneth/honest_llama|TruthfulQA|https://github.com/sylinrl/TruthfulQA

 -->

## benchmark

| Paper | code | data |
| :---------------------------------------------- | :---------------------------------------------- | :---------------------------------------------- |
|  [Chain-of-Thought Hub: A Continuous Effort to Measure Large Language Models' Reasoning Performance](https://arxiv.org/pdf/2305.17306.pdf)  | [chain-of-thought-hub](https://github.com/FranxYao/chain-of-thought-hub) | [chain-of-thought-hub]([https://github.com/OpenBMB/ToolBench](https://github.com/FranxYao/chain-of-thought-hub)) |

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
- **[Tool Learning Papers](https://github.com/thunlp/ToolLearningPapers)** Awesome tool learning paper collection from THUNLP.
