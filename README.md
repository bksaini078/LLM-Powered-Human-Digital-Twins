# LLM-Powered Human Digital Twins

A curated, community-maintained bibliography of research on LLM-based and multi-agent human digital twins, with special focus on market research, consumer modeling, organizational decision making, and decision support.

This repository is a public contribution project. The list is intentionally selective rather than exhaustive: it prioritizes papers that directly model humans, consumers, workers, teams, or organizations with LLMs or multi-agent systems, especially when the work evaluates behavioral fidelity, survey simulation, preference elicitation, strategic reasoning, or organizational utility.

## Scope

Included:

- Peer-reviewed papers
- arXiv preprints
- Workshop papers
- High-quality technical reports or platform papers when they are directly useful to this research area

Preferred ordering:

- Topic first
- Latest papers first within each topic
- Foundational papers kept near the end of a section when they still matter for context

## Topic Map

| Topic | What belongs here |
| --- | --- |
| Market research and synthetic respondents | Survey simulation, consumer modeling, preference estimation, public opinion emulation, Likert-style response generation |
| Organizational decision making | Strategic reasoning, management support, business process reasoning, alignment for enterprise settings |
| Human digital twins and personas | Persona construction, stable human-like memory, belief modeling, behavioral proxies |
| Multi-agent simulation | Team coordination, group dynamics, social simulation, organizational behavior |
| Evaluation and benchmarks | Benchmarks for survey questions, persona fidelity, reasoning quality, decision support |
| Surveys and perspectives | Overviews of agentic LLMs, alignment, and related methodology |
| Tools and platforms | Open-source systems that help build, deploy, or evaluate decision-support agents |

## Recommended Citation Format

Use this pattern for each entry:

> Title. Authors. Year. Venue or type. URL. Short note on relevance.

Example:

> Generative Agents: Interactive Simulacra of Human Behavior. Joon Sung Park et al. 2023. CHI 2023 / arXiv. https://arxiv.org/abs/2304.03442. Foundational paper for LLM-based human-like agents with memory, reflection, and interaction.

## Market Research and Synthetic Respondents

- **Simulation of Human Survey Responses for Market Research: The Role of Contextualization in LLM-Based Agents**. Bhupender Kumar Saini, Chandan Kumar, Kathrin Pollmann, Janina Bierkandt, Doris Janssen, Christian Knecht, Nora Fronemann. 2026. Proceedings of the Extended Abstracts of the 2026 CHI Conference on Human Factors in Computing Systems / CHI EA '26. https://dl.acm.org/doi/10.1145/3772363.3798991. Directly relevant to market research because it studies how contextualization changes LLM-based survey-response simulation.
- **LLMs Reproduce Human Purchase Intent via Semantic Similarity Elicitation of Likert Ratings**. Benjamin F. Maier et al. 2025. arXiv preprint. https://arxiv.org/abs/2510.08338. Directly evaluates whether LLMs can reproduce purchase-intent signals from Likert-style responses.
- **Large Language Models as Virtual Survey Respondents: Evaluating Sociodemographic Response Generation**. Jianpeng Zhao et al. 2025. arXiv preprint. https://arxiv.org/abs/2509.06337. Studies synthetic survey respondents and demographic response fidelity.
- **Emulating Public Opinion: A Proof-of-Concept of AI-Generated Synthetic Survey Responses for the Chilean Case**. Bastián González-Bustamante, Nando Verelst, Carla Cisternas. 2025. Working paper / Empiria Lab Method Series. https://arxiv.org/abs/2509.09871. Applied example of synthetic respondents for public-opinion research.
- **Using LLMs to Model the Beliefs and Preferences of Targeted Populations**. Keiichi Namikoshi, Alex Filipowicz, David A. Shamma, Rumen Iliev, Candice L. Hogan, Nikos Arechiga. 2024. arXiv preprint. https://arxiv.org/abs/2403.20252. Strong fit for virtual focus groups and population-specific preference modeling.

## Organizational Decision Making

- **Can LLMs Help Improve Analogical Reasoning for Strategic Decisions? Experimental Evidence from Humans and GPT-4**. Phanish Puranam, Prothit Sen, Maciej Workiewicz. 2025. arXiv preprint. https://arxiv.org/abs/2505.00603. Directly tests whether LLMs can support strategic decision making.
- **Evaluating Intra-firm LLM Alignment Strategies in Business Contexts**. Noah Broestl et al. 2025. arXiv preprint. https://arxiv.org/abs/2505.18779. Relevant to aligning LLM behavior for internal organizational use.
- **Embodied LLM Agents Learn to Cooperate in Organized Teams**. Xudong Guo et al. 2024. arXiv preprint. https://arxiv.org/abs/2403.12482. Useful for modeling teamwork, coordination, and group decision processes.
- **Towards a Benchmark for Causal Business Process Reasoning with LLMs**. Fabiana Fournier, Lior Limonad, Inna Skarbovsky. 2024. NLP4BPM workshop at BPM 2024. https://arxiv.org/abs/2406.05506. Practical benchmark for enterprise process reasoning.
- **FinRobot: An Open-Source AI Agent Platform for Financial Applications using Large Language Models**. Hongyang Yang et al. 2024. Technical report / platform paper. https://arxiv.org/abs/2405.14767. Useful decision-support platform reference for business and finance workflows.

## Human Digital Twins and Personas

- **Deep Binding of Language Model Virtual Personas: a Study on Approximating Political Partisan Misperceptions**. Minwoo Kang et al. 2025. COLM 2025 / arXiv preprint. https://arxiv.org/abs/2504.11673. Strong persona-fidelity paper focused on belief consistency.
- **Virtual Personas for Language Models via an Anthology of Backstories**. Suhong Moon et al. 2024. EMNLP 2024. https://arxiv.org/abs/2407.06576. Useful for constructing consistent virtual personas with richer backstories.
- **Can LLMs Capture Human Preferences?** Ali Goli, Amandeep Singh. 2023. arXiv preprint. https://arxiv.org/abs/2305.02531. Early evidence on whether LLMs can stand in for human preference judgments.
- **Generative Agents: Interactive Simulacra of Human Behavior**. Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein. 2023. CHI 2023 / arXiv preprint. https://arxiv.org/abs/2304.03442. Canonical starting point for LLM-based human-like agents with memory and reflection.

## Multi-Agent Simulation and Group Behavior

- **Embodied LLM Agents Learn to Cooperate in Organized Teams**. Xudong Guo et al. 2024. arXiv preprint. https://arxiv.org/abs/2403.12482. Team coordination and cooperation in organized settings.
- **Generative Agents: Interactive Simulacra of Human Behavior**. Joon Sung Park et al. 2023. CHI 2023 / arXiv preprint. https://arxiv.org/abs/2304.03442. Social simulation foundation for group-level behavior.

## Evaluation and Benchmarks

- **Questionnaire Meets LLM: A Benchmark and Empirical Study of Structural Skills for Understanding Questions and Responses**. Duc-Hai Nguyen et al. 2025. arXiv preprint. https://arxiv.org/abs/2510.26238. Useful for testing whether models can structure survey questions and answers correctly.
- **Towards a Benchmark for Causal Business Process Reasoning with LLMs**. Fabiana Fournier, Lior Limonad, Inna Skarbovsky. 2024. NLP4BPM workshop at BPM 2024. https://arxiv.org/abs/2406.05506. Business-process reasoning benchmark with enterprise relevance.

## Surveys and Perspectives

- **Agentic Large Language Models, a Survey**. Aske Plaat et al. 2025. Journal of Artificial Intelligence Research. https://doi.org/10.1613/jair.1.18675. Helpful overview of agentic LLM methods and design choices.
- **Aligning Large Language Models with Human: A Survey**. Yufei Wang et al. 2023. arXiv survey. https://arxiv.org/abs/2307.12966. Useful background on alignment and human-centered LLM behavior.

## Tools and Platforms

- **FinRobot: An Open-Source AI Agent Platform for Financial Applications using Large Language Models**. Hongyang Yang et al. 2024. Technical report / platform paper. https://arxiv.org/abs/2405.14767. Open-source platform relevant to decision-support workflows.

## Expanded Verified Related Literature

### Market Research, Survey Modeling, and Digital Twins

- **Redefining Research Crowdsourcing Incorporating Human Feedback with LLM-Powered Digital Twins**. Amanda Chan, Catherine Di, Joseph Rupertus, et al. 2025. CHI 2025. https://doi.org/10.1145/3706599.3720269. Directly relevant to crowdsourcing, human feedback, and digital twins in research workflows.
- **Synthetic Replacements for Human Survey Data? The Perils of Large Language Models**. James Bisbee, Joshua D. Clinton, Cassy Dorff, Brenton Kenkel, and Jennifer M. Larson. 2024. Political Analysis 32(4). https://doi.org/10.1017/pan.2024.5. Important cautionary paper on replacing human survey data with LLM outputs.
- **AI-Augmented Surveys: Leveraging Large Language Models and Surveys for Opinion Prediction**. Junsol Kim, Byungkyu Lee, Peter Bearman, et al. 2023. arXiv preprint. https://arxiv.org/abs/2305.09620. Uses surveys and LLMs for opinion prediction.
- **Simulating Human Opinions with Large Language Models: Opportunities and Challenges for Personalized Survey Data Modeling**. Carolin Kaiser, Jakob Kaiser, Vladimir Manewitsch, Lea Rau, and Rene Schallner. 2025. UMAP 2025 Adjunct Proceedings. https://doi.org/10.1145/3708319.3733685. Focuses on personalized survey-data modeling with LLMs.
- **PersonaBOT: Bringing Customer Personas to Life with LLMs and RAG**. Muhammed Rizwan, Lars Carlsson, and Mohammad Loni. 2025. arXiv preprint. https://arxiv.org/pdf/2505.17156. Customer-persona generation for applied market research.
- **Twin-2K-500: A Dataset for Building Digital Twins of over 2,000 People Based on Their Answers to over 500 Questions**. Olivier Toubia, George Z. Gui, Tianyi Peng, Daniel J. Merlau, Ang Li, and Haozhe Chen. 2025. arXiv preprint. https://arxiv.org/pdf/2505.17479. Key dataset for building person-level digital twins.
- **Random Silicon Sampling: Simulating Human Sub-Population Opinion Using a Large Language Model Based on Group-Level Demographic Information**. Seungjong Sun, Eungu Lee, Dongyan Nan, Xiangying Zhao, Wonbyung Lee, Bernard J. Jansen, and Jang Hyun Kim. 2024. arXiv preprint. https://arxiv.org/pdf/2402.18144. Simulates sub-population opinion from demographic signals.
- **SimUser: Generating Usability Feedback by Simulating Various Users Interacting with Mobile Applications**. Wei Xiang, Hanfei Zhu, Suqi Lou, et al. 2024. CHI 2024. https://doi.org/10.1145/3613904.3642481. Strong adjacent work on simulated user feedback.
- **Measuring Financial Wellbeing with Self-Reported and Bank Record Data**. Carole Comerton-Forde, John de New, Nicolás Salamanca, David C. Ribar, Andrea Nicastro, and James Ross. 2022. Economic Record 98(321). https://doi.org/10.1111/1475-4932.12664. Useful measurement context for self-report validation.

### Human Digital Twins, Personas, and Cognition

- **A Foundation Model to Predict and Capture Human Cognition**. Marcel Binz, Elif Akata, Matthias Bethge, et al. 2025. Nature. https://doi.org/10.1038/S41586-025-09215-4. Important bridge between foundation models and cognition modeling.
- **Marked Personas: Using Natural Language Prompts to Measure Stereotypes in Language Models**. Myra Cheng, Esin Durmus, and Dan Jurafsky. 2023. ACL 2023. https://doi.org/10.18653/v1/2023.acl-long.84. Useful for persona measurement and stereotype analysis.
- **Beyond Demographics: Aligning Role-Playing LLM-Based Agents Using Human Belief Networks**. Yun-Shiuan Chuang, Zach Studdiford, Krirk Nirunwiroj, et al. 2024. EMNLP 2024. https://doi.org/10.48550/arXiv.2406.17232. Focuses on belief networks rather than just demographics.
- **PersonaCraft: Leveraging Language Models for Data-Driven Persona Development**. Soon Gyo Jung, Joni Salminen, Kholoud Khalil Aldous, and Bernard J. Jansen. 2025. International Journal of Human-Computer Studies 197. https://doi.org/10.1016/J.IJHCS.2025.103445. Practical persona development pipeline.
- **The Impostor Is Among Us: Can Large Language Models Capture the Complexity of Human Personas?**. Christopher Lazik, Christopher Katins, Charlotte Kauter, et al. 2025. arXiv preprint. https://arxiv.org/pdf/2501.04543v1. Tests complexity limits of persona simulation.
- **LLM Generated Persona Is a Promise with a Catch**. Ang Li, Haozhe Chen, Hongseok Namkoong, and Tianyi Peng. 2025. arXiv preprint. https://arxiv.org/pdf/2503.16527v1. Evaluates both promise and limitations of generated personas.
- **LLMs Instead of Human Judges? A Large Scale Empirical Study across 20 NLP Evaluation Tasks**. Anna Bavaresco, Raffaella Bernardi, Leonardo Bertolazzi, et al. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2406.18403. Relevant for understanding when model judgments substitute for human judgment.
- **LLMs-as-Judges: A Comprehensive Survey on LLM-Based Evaluation Methods**. Haitao Li, Qian Dong, Junjie Chen, et al. 2024. arXiv survey. https://doi.org/10.48550/arXiv.2412.05579. Useful survey for evaluation and judging methods.
- **PersonaFlow: Designing LLM-Simulated Expert Perspectives for Enhanced Research Ideation**. Yiren Liu, Pranav Sharma, Mehul Jitendra Oswal, Haijun Xia, and Yun Huang. 2025. DIS 2025. https://doi.org/10.1145/3715336.3735789. Shows expert-perspective simulation for ideation.
- **D-Twins: Your Digital Twin Designed for Real-Time Boredom Intervention**. I. Chen Lo and Pei Luen Patrick Rau. 2025. CHI 2025. https://doi.org/10.1145/3706598.3714163. Explicit digital-twin intervention system.
- **PersonalAI: Towards Digital Twins in the Graph Form**. Mikhail Menschikov, Dmitry Evseev, Ruslan Kostoev, et al. 2025. arXiv preprint. https://arxiv.org/pdf/2506.17001. Graph-based digital twin approach.
- **Evaluating the Ability of Large Language Models to Emulate Personality**. Yilei Wang, Jiabao Zhao, Deniz S. Ones, Liang He, and Xin Xu. 2025. Scientific Reports 15(1). https://doi.org/10.1038/S41598-024-84109-5. Direct personality-emulation evaluation.
- **Understanding Human-AI Workflows for Generating Personas**. Joongi Shin, Michael A. Hedderich, Bartłomiej Jakub Rey, Andrés Lucero, and Antti Oulasvirta. 2024. DIS 2024. https://doi.org/10.1145/3643834.3660729. Useful workflow study for persona creation.
- **Copersona: Leveraging LLMs and Expert Collaboration to Understand User Personas Through Social Media Data Analysis**. Min Yin, Haoyu Liu, Boyi Lian, and Ruiyi Cai. 2026. Design for Augmented Humanity 1(1). https://doi.org/10.1177/29776481261426454. Strong public-facing persona-development reference for consumer understanding and product design.
- **Can AI Language Models Replace Human Participants?**. Danica Dillion, Niket Tandon, Yuling Gu, and Kurt Gray. 2023. Trends in Cognitive Sciences 27(7). https://doi.org/10.1016/j.tics.2023.04.008. Foundational context for the debate on LLMs as substitutes for human participants.
- **Deep Binding of Language Model Virtual Personas: a Study on Approximating Political Partisan Misperceptions**. Minwoo Kang et al. 2025. COLM 2025 / arXiv preprint. https://arxiv.org/abs/2504.11673. Persona fidelity under politically sensitive beliefs.
- **Virtual Personas for Language Models via an Anthology of Backstories**. Suhong Moon et al. 2024. EMNLP 2024. https://arxiv.org/abs/2407.06576. Persona construction with backstories.

### Multi-Agent Simulation and Collective Behavior

- **Human Behavior Simulation: Objectives, Methodologies, and Open Problems**. Zhang Guozhen, Yu Zihan, Li Nian, et al. 2024. arXiv preprint. https://arxiv.org/pdf/2412.07788. Broad overview of human behavior simulation.
- **Generative Agent Simulations of 1,000 People**. Joon Sung Park, Carolyn Q. Zou, Aaron Shaw, et al. 2024. arXiv preprint. https://arxiv.org/pdf/2411.10109. Large-scale generative agent simulation.
- **ElectionSim: Massive Population Election Simulation Powered by Large Language Model Driven Agents**. Xinnong Zhang, Jiayu Lin, Libo Sun, et al. 2024. arXiv preprint. https://doi.org/10.48550/ARXIV.2410.20746. Large population simulation for electoral behavior.
- **Unleashing the Emergent Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration**. Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, and Heng Ji. 2024. arXiv preprint. https://arxiv.org/pdf/2307.05300v3. Multi-persona collaboration for task solving.
- **Agentic AI for Digital Twin**. Alexander Timms, Abigail Langbridge, Antonis Antonopoulos, Antonis Mygiakis, Eleni Voulgari, and Fearghal O'Donncha. 2025. AAAI 2025. https://doi.org/10.1609/AAAI.V39I28.35373. Relevant digital-twin systems perspective.
- **The Benefits of Prosociality towards AI Agents: Examining the Effects of Helping AI Agents on Human Well-Being**. Zicheng Zhu, Yugin Tan, Naomi Yamashita, Yi Chieh Lee, and Renwen Zhang. 2025. CHI 2025. https://doi.org/10.1145/3706598.3713116. Human-agent interaction and well-being context.
- **Which Experiences Are Influential for RL Agents? Efficiently Estimating The Influence of Experiences**. Takuya Hiraoka, Guanquan Wang, Takashi Onishi, and Yoshimasa Tsuruoka. 2024. Reinforcement Learning Journal. https://arxiv.org/pdf/2405.14629. Adjacent context for experience influence and agent memory.
- **Large Language Model Guided Tree-of-Thought**. Jieyi Long. 2023. arXiv preprint. https://arxiv.org/pdf/2305.08291. Broader reasoning context for agentic systems.

### Evaluation, Judges, and Benchmarks

- **LLMs Instead of Human Judges? A Large Scale Empirical Study across 20 NLP Evaluation Tasks**. Anna Bavaresco, Raffaella Bernardi, Leonardo Bertolazzi, et al. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2406.18403. Tests when LLMs can stand in for human judges.
- **A Survey on LLM-as-a-Judge**. Jiawei Gu, Xuhui Jiang, Zhichao Shi, et al. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2411.15594. Survey of judge-model techniques.
- **Can GPT-4o Evaluate Usability Like Human Experts? A Comparative Study on Issue Identification in Heuristic Evaluation**. Guilherme Guerino, Luiz Rodrigues, Bruna Capeleti, Rafael Ferreira Mello, André Freire, and Luciana Zaina. 2025. arXiv preprint. https://arxiv.org/pdf/2506.16345. Human-expert comparison in usability evaluation.
- **Automated Genre-Aware Article Scoring and Feedback Using Large Language Models**. Chihang Wang, Yuxin Dong, Zhenhong Zhang, Ruotong Wang, Shuo Wang, and Jiajing Chen. 2024. arXiv preprint. https://doi.org/10.48550/arXiv.2410.14165. Example of automated evaluation and feedback generation.
- **LLMs-as-Judges: A Comprehensive Survey on LLM-Based Evaluation Methods**. Haitao Li, Qian Dong, Junjie Chen, et al. 2024. arXiv survey. https://doi.org/10.48550/arXiv.2412.05579. Broader evaluation-method survey.

### Broader Decision-Making Context

- **Dual-Process Theories of Decision-Making: A Selective Survey**. Isabelle Brocas and Juan D. Carrillo. 2014. Journal of Economic Psychology 41. https://doi.org/10.1016/J.JOEP.2013.01.004. Classical decision-making background.
- **To Predict Human Choice, Consider the Context**. Ori Plonsky and Ido Erev. 2021. Trends in Cognitive Sciences 25(10). https://doi.org/10.1016/j.tics.2021.07.007. Context-sensitive choice modeling.
- **Metacognitive Prompting Improves Understanding in Large Language Models**. Yuqing Wang and Yun Zhao. 2024. NAACL 2024. https://doi.org/10.18653/V1/2024.NAACL-LONG.106. Helpful prompting context for understanding and decision support.

## How To Contribute

Public contributions are welcome.

When suggesting a paper, include:

- Title
- Authors
- Year
- Venue or paper type
- Canonical URL
- One-line reason it belongs in this list
- Suggested category

Contribution standards:

- Prefer papers that directly model humans, consumers, workers, teams, or organizations.
- Prefer work that evaluates fidelity, usefulness, or decision support, not generic agent demos.
- Prefer the newest relevant work when multiple papers cover the same angle.
- Keep entries concise and citation-like so the README remains easy to scan.

## Curation Notes

This is a living bibliography. As the field changes, new papers should be added to the most relevant topic section and ordered by recency. If a paper could fit multiple sections, place it where it is most useful to a reader working on market research or organizational decision making.

If you are contributing for the first time, open a pull request with the paper metadata in plain text. A short note explaining why the paper matters is usually enough for review.

## Contributor-Supplied Research Index

This supplemental index captures the broader literature set requested by contributors. Some items are already listed above; they are included here to make the taxonomy easy to scan from the repository homepage.

### 1. Foundations and Surveys

- Out of One, Many: Using Language Models to Simulate Human Samples. Political Analysis, 2023. https://doi.org/10.1017/pan.2023.2.
- From Persona to Personalization: A Survey on Role-Playing Language Agents. arXiv, 2024.04.
- Can Large Language Models Transform Computational Social Science?. Computational Linguistics, 2024.03.
- Exploring the Frontiers of LLMs in Psychological Applications: A Comprehensive Review. arXiv, 2024.01.
- Towards a Psychological Generalist AI: A Survey of Current Applications of Large Language Models and Future Prospects. arXiv, 2023.12.
- Using Large Language Models in Psychology. Nature Reviews Psychology, 2023.10.
- Emergent Abilities of Large Language Models. arXiv, 2022.06.

### 2. LLM for Human Behavior Simulation

- Generative Agents: Interactive Simulacra of Human Behavior. arXiv:2304.03442. Preprint, arXiv, August 6, 2023. https://doi.org/10.48550/arXiv.2304.03442.
- Social Simulacra: Creating Populated Prototypes for Social Computing Systems. arXiv:2208.04024. Preprint, arXiv, August 8, 2022. https://doi.org/10.48550/arXiv.2208.04024.
- Lost in Simulation: LLM-Simulated Users are Unreliable Proxies for Human Users in Agentic Evaluations. arXiv, 2026.01.
- Consistently Simulating Human Personas with Multi-Turn Reinforcement Learning. NeurIPS, 2025. [Code].
- A Mega-Study of Digital Twins Reveals Strengths, Weaknesses and Opportunities for Further Improvement. arXiv, 2025.09.
- How Many Human Survey Respondents is a Large Language Model Worth? An Uncertainty Quantification Perspective. arXiv, 2025.02. [Code].
- Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations. EMNLP, 2025. [Code].
- Generative Agent Simulations of 1,000 People. arXiv, 2024.11.
- Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers. arXiv, 2024.09. [Code].
- Language Models Show Stable Value Orientations Across Diverse Role-Plays. arXiv, 2024.08.
- PsychoGAT: A Novel Psychological Measurement Paradigm through Interactive Fiction Games with LLM Agents. ACL, 2024.
- Limited Ability of LLMs to Simulate Human Psychological Behaviours: A Psychometric Analysis. arXiv, 2024.05.
- Is Cognition and Action Consistent or Not: Investigating Large Language Model's Personality. arXiv, 2024.02.
- LLM Agents for Psychology: A Study on Gamified Assessments. arXiv, 2024.02.
- Quantifying the Persona Effect in LLM Simulations. arXiv, 2024.02. [Code].
- The Empty Chair: Using LLMs to Raise Missing Perspectives in Policy Deliberations. arXiv:2503.13812. Version 2. Preprint, arXiv, November 14, 2025. https://doi.org/10.48550/arXiv.2503.13812.
- "Kelly Is a Warm Person, Joseph Is a Role Model": Gender Biases in LLM-Generated Reference Letters. arXiv, 2023.10. [Code].
- Personality Traits in Large Language Models. arXiv, 2023.07. [Code].
- Role Play with Large Language Models. Nature, 2023.11.
- The Challenge of Using LLMs to Simulate Human Behavior: A Causal Inference Perspective. arXiv, 2023.12.
- Meet Your Favorite Character: Open-Domain Chatbot Mimicking Fictional Characters with Only a Few Utterances. arXiv, 2022.04.

### 3. LLM Agents

- Towards an LLM-Powered Social Digital Twinning Platform. arXiv:2505.10681. Preprint, arXiv, May 15, 2025. https://doi.org/10.48550/arXiv.2505.10681.
- An LLM-based Simulation Framework for Embodied Conversational Agents in Psychological Counseling. arXiv, 2024.10. [Code].
- MegaAgent: A Practical Framework for Autonomous Cooperation in Large-Scale LLM Agent Systems. arXiv, 2024.08.
- Hello Again! LLM-powered Personalized Agent for Long-term Dialogue. arXiv, 2024.06. [Code].
- Towards Lifelong Learning of Large Language Models: A Survey. arXiv, 2024.06. [Code].
- Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents. arXiv, 2024.05.
- MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-Oriented Coordination via Collaborative Generative Agents. arXiv, 2023.10.
- Agents: An Open-Source Framework for Autonomous Language Agents. arXiv, 2023.09. [Code].
- AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework. arXiv, 2023.08. [Code].
- MetaGPT: Meta Programming for Multi-Agent Collaborative Framework. arXiv, 2023.08. [Code].
- AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents. arXiv, 2023.

### 4. LLM Bias and Value

- Gender Bias of LLM in Economics: An Existentialism Perspective. arXiv, 2024.10.
- Measuring Human and AI Values based on Generative Psychometrics with Large Language Models. arXiv, 2024.09. [Code].
- United in Diversity? Contextual Biases in LLM-Based Predictions of the 2024 European Parliament Elections. arXiv, 2024.08.
- Representation Bias in Political Sample Simulations with Large Language Models. arXiv, 2024.07.
- New Job, New Gender? Measuring the Social Bias in Image Generation Models. MM, 2024.
- Whose Opinions Do Language Models Reflect?. ICML, 2023.
- Not All Countries Celebrate Thanksgiving: On the Cultural Dominance in Large Language Models. arXiv, 2023.10.
- Probing Explicit and Implicit Gender Bias through LLM Conditional Text Generation. arXiv, 2023.11.
- Evaluating the Moral Beliefs Encoded in LLMs. NeurIPS, 2023. [Code].
- When to Make Exceptions: Exploring Language Models as Accounts of Human Moral Judgment. NeurIPS, 2022. [Code].

### 5. LLM Simulation Applications

#### 5.1 Economics and Finance

- Augmenting Survey Data with Generative AI: An Application to Economic Research. SSRN, 2026.
- AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions. arXiv, 2026.02. [Code].
- Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?. ACM EC, 2024.
- Measuring Bargaining Abilities of LLMs: A Benchmark and A Buyer-Enhancement Method. Findings of ACL, 2024.
- CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading. arXiv, 2024.06. [Code].
- Simulating Financial Market via Large Language Model Based Agents. arXiv, 2024.06.
- EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities. ACL, 2024. [Code].
- Designing Heterogeneous LLM Agents for Financial Sentiment Analysis. ACM TMIS, 2024.08.

#### 5.2 Politics and Society

- Auditing Political Exposure Bias: Algorithmic Amplification on Twitter/X Approaching the 2024 US Presidential Election. arXiv, 2024.11.
- GermanPartiesQA: Benchmarking Commercial Large Language Models for Political Bias and Sycophancy. arXiv, 2024.07.
- Simulating The U.S. Senate: An LLM-Driven Agent Approach to Modeling Legislative Behavior and Bipartisanship. arXiv, 2024.06.
- Trump, Twitter, and Truth Social: How Trump Used Both Mainstream and Alt-Tech Social Media to Drive News Media Attention. Journal of Information Technology & Politics, 2024.03.
- War and Peace (WarAgent): Large Language Model-Based Multi-Agent Simulation of World Wars. arXiv, 2023.11. [Code].

#### 5.3 Education

- Large Language Model as an Assignment Evaluator: Insights, Feedback, and Challenges in a 1000+ Student Course. arXiv, 2024.07.
- Simulating Classroom Education with LLM-Empowered Agents. arXiv, 2024.06.
- Generative Students: Using LLM-Simulated Student Profiles to Support Question Item Evaluation. arXiv, 2024.05.
- MathVC: An LLM-Simulated Multi-Character Virtual Classroom for Mathematics Education. arXiv, 2024.04.
- PhysicsAssistant: An LLM-Powered Interactive Learning Robot for Physics Lab Investigations. arXiv, 2024.03.

#### 5.4 Recommendation Systems and User Simulation

- Beyond Offline A/B Testing: Context-Aware Agent Simulation for Recommender System Evaluation. arXiv, 2026.04.
- PUB: An LLM-Enhanced Personality-Driven User Behaviour Simulator for Recommender System Evaluation. SIGIR, 2025.
- LLM as User Simulator: Towards Training News Recommender without Real User Interactions. SIGIR, 2025.
- Agentic Feedback Loop Modeling Improves Recommendation and User Simulation. SIGIR, 2025. [Code].
- SimUSER: Simulating User Behavior with Large Language Models for Recommender System Evaluation. ACL Industry, 2025.
- A LLM-based Controllable, Scalable, Human-Involved User Simulator Framework for Conversational Recommender Systems. WWW, 2025.
- RecUserSim: A Realistic and Diverse User Simulator for Evaluating Conversational Recommender Systems. WWW Companion, 2025.
- LLM-Powered User Simulator for Recommender System. AAAI, 2025.
- RecAgent: User Behavior Simulation with Large Language Model-based Agents. ACM TOIS, 2024. [Code].
- BASES: Large-scale Web Search User Simulation with Large Language Model based Agents. Findings of EMNLP, 2024.
- Reliable LLM-based User Simulator for Task-Oriented Dialogue Systems. SCI-CHAT Workshop, 2024.
- A Survey on Large Language Models for Recommendation. arXiv, 2024.08. [Code].
- LLM-Rec: Personalized Recommendation via Prompting Large Language Models. arXiv, 2024.07.
- Generating Personalized Recommendations via Large Language Models (LLMs). Technical Disclosure Commons, 2022.12.

#### 5.5 Customer and Consumer Simulation

- Persona Generation from Aggregated Social Media Data. Proceedings of the 2017 CHI Conference Extended Abstracts on Human Factors in Computing Systems (New York, NY, USA), CHI EA '17, May 6, 2017, 1748–55. https://doi.org/10.1145/3027063.3053120.
- Data-Driven Personas: Constructing Archetypal Users with Clickstreams and User Telemetry. Proceedings of the 2016 CHI Conference on Human Factors in Computing Systems (New York, NY, USA), CHI '16, May 7, 2016, 5350–59. https://doi.org/10.1145/2858036.2858523.
- Asadi, Amir Reza, and Jess Kropczynski. Qualitative Data-Driven Personas: Designing an Interactive System for Creating AI Personas. Proceedings of the 2024 The 6th World Symposium on Software Engineering (WSSE) (New York, NY, USA), WSSE '24, December 8, 2024, 232–36. https://doi.org/10.1145/3698062.3698096.
- Deep, Paluck, Monica Bharadhidasan, and A. Baki Kocaballi. 'She Was Useful, but a Bit Too Optimistic': Augmenting Design with Interactive Virtual Personas. International Journal of Human-Computer Studies 205 (November 2025): 103646. https://doi.org/10.1016/j.ijhcs.2025.103646.
- Towards an LLM-Powered Social Digital Twinning Platform. arXiv:2505.10681. Preprint, arXiv, May 15, 2025. https://doi.org/10.48550/arXiv.2505.10681.
- ShopSimulator: Evaluating and Exploring RL-Driven LLM Agent for Shopping Assistants. arXiv, 2026.01.
- Customer-R1: Personalized Simulation of Human Behaviors via RL-based LLM Agent in Online Shopping. arXiv, 2025.10.
- See, Think, Act: Online Shopper Behavior Simulation with VLM Agents. NeurIPS, 2025.
- Shop-R1: Rewarding LLMs to Simulate Human Behavior in Online Shopping via Reinforcement Learning. NeurIPS SEA Workshop, 2025.
- LLMs Reproduce Human Purchase Intent via Semantic Similarity Elicitation of Likert Ratings. arXiv, 2025.10. [Code].
- LLM Agent Meets Agentic AI: Can LLM Agents Simulate Customers to Evaluate Agentic-AI-based Shopping Assistants?. arXiv, 2025.09.
- What Is Your AI Agent Buying? Evaluation, Biases, Model Dependence, and Emerging Implications for Agentic E-Commerce. arXiv, 2025.08.
- ShoppingBench: A Real-World Intent-Grounded Shopping Benchmark for LLM-based Agents. arXiv, 2025.08.
- LLM-Based Multi-Agent System for Simulating and Analyzing Marketing and Consumer Behavior. IEEE ICEBE, 2025.
- Predicting Behaviors with Large Language Model (LLM)-Powered Digital Twins of Consumers. MSI Working Paper, 2025.
- AI-Human Hybrids for Marketing Research: Leveraging Large Language Models (LLMs) as Collaborators. Journal of Marketing, 2025.
- Large Language Models for Market Research: A Data-augmentation Approach. arXiv, 2024.12.
- Can Large Language Models Capture Human Preferences?. Marketing Science, 2024.
- Can LLM Agents Simulate Multi-Turn Human Behavior? Evidence from Real Online Customer Behavior Data. arXiv, 2025.03.
- Using LLMs for Market Research. Harvard Business School Working Paper, 2025.
- Challenges and Opportunities of LLM-Based Synthetic Personae and Data in HCI. CHI EA, 2024.
- LLM Voting: Human Choices and AI Collective Decision-Making. Proceedings of the 2024 AAAI/ACM Conference on AI, Ethics, and Society (San Jose, California, USA), AIES '24, February 7, 2025, 1696–708. https://dl.acm.org/doi/10.5555/3716662.3716809.
- An Electoral Approach to Diversify LLM-Based Multi-Agent Collective Decision-Making. arXiv:2410.15168. Preprint, arXiv, October 19, 2024. https://doi.org/10.48550/arXiv.2410.15168.
- Understanding Nonlinear Collaboration between Human and AI Agents: A Co-Design Framework for Creative Design. Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems (New York, NY, USA), CHI '24, May 11, 2024, 1–16. https://doi.org/10.1145/3613904.3642812.

#### 5.6 Others

- Improve Temporal Awareness of LLMs for Sequential Recommendation. arXiv, 2024.05.
- How Far Are We on the Decision-Making of LLMs? Evaluating LLMs' Gaming Ability in Multi-Agent Environments. arXiv, 2024.03. [Code].
- Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf. arXiv, 2023.09.
- The SocialAI School: Insights from Developmental Psychology towards Artificial Socio-Cultural Agents. arXiv, 2023.07. [Code].

### 6. LLM Evaluation

- Benchmarking LLMs' Judgments with No Gold Standard. arXiv, 2024.11.
- Cognitive Overload Attack: Prompt Injection for Long Context. arXiv, 2024.10.
- Moral Alignment for LLM Agents. arXiv, 2024.10.
- Revealing the Challenge of Detecting Character Knowledge Errors in LLM Role-Playing. arXiv, 2024.09. [Code].
- InCharacter: Evaluating Personality Fidelity in Role-Playing Agents through Psychological Interviews. ACL, 2024. [Code].
- Regurgitative Training: The Value of Real Data in Training Large Language Models. arXiv, 2024.07.
- Evaluating the Performance of Large Language Models via Debates. arXiv, 2024.06.
- Auto-Arena: Automating LLM Evaluations with Agent Peer Battles and Committee Discussions. arXiv, 2024.05. [Code].
- AgentClinic: A Multimodal Agent Benchmark to Evaluate AI in Simulated Clinical Environments. arXiv, 2024.05. [Code].
- How Reliable is Your Simulator? Analysis on the Limitations of Current LLM-based User Simulators for Conversational Recommendation. arXiv, 2024.03. [Code].
- Humans or LLMs as the Judge? A Study on Judgement Bias. arXiv, 2024.02. [Code].
- LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games. CoRR, 2023.09.
- AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback. NeurIPS, 2023. [Code].
- AgentSims: An Open-Source Sandbox for Large Language Model Evaluation. arXiv, 2023.08. [Code].

### 7. Cognition and Psychology

- Grounded Cognition. Annual Review of Psychology, 2008.
- Language and Simulation in Conceptual Processing. Symbols, Embodiment, and Meaning, 2008.
- Dual Coding Theory: Retrospect and Current Status. Canadian Journal of Psychology, 1991.
- How and Why Thoughts Change: Foundations of Cognitive Psychotherapy. Oxford University Press, 2015.
- Emotion and Social Theory: Corporeal Reflections on the (Ir)rational. Sage, 2000.
- Neural Dynamics of Decision Making Under Risk: Affective Balance and Cognitive-Emotional Interactions. Psychological Review, 1987.
- A Cognition-Based View of Decision Processes in Complex Social-Ecological Systems. Ecology and Society, 2007.06.
- Information, Incentives, and Proenvironmental Consumer Behavior. Journal of Consumer Policy, 1999.
- Human Incentives. The Greek Economy and the Crisis, 2012.

### 8. Social Simulation

- AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society. arXiv, 2025.02. [Code].
- OASIS: Open Agent Social Interaction Simulations with One Million Agents. arXiv, 2024.11. [Code].
- Multi-Agents Are Social Groups: Investigating Social Influence of Multiple Agents in Human-Agent Interactions. CSCW, 2025.
- Unpacking a Black Box: A Conceptual Anatomy Framework for Agent-Based Social Simulation Models. JASSS, 2023.
- Simulation: A Tool for System Design and Analysis. GPH-IJSSHR, 2023.
- Analysing the Combined Health, Social and Economic Impacts of the Coronavirus Pandemic Using Agent-Based Social Simulation. Minds and Machines, 2020.06.
- The Termination Risks of Simulation Science. Erkenntnis, 2020.
- Simulating Societies: The Computer Simulation of Social Phenomena. 2018.
- Computer Simulations of Space Societies. 2018.
- Can Robots Be Lawyers? Computers, Lawyers, and the Practice of Law. Georgetown Journal of Legal Ethics, 2017.
- Ethics in Planning. 2017.
- Social Self-Organization: Agent-Based Simulations and Experiments to Study Emergent Social Behavior. 2012.
- Analyzing and Modeling Real-World Phenomena with Complex Networks: A Survey of Applications. Advances in Physics, 2011.03.
- A Simulation System of Social Economic. Computer and Information Science, 2011.07.
- A Methodology for Complex Social Simulations. JASSS, 2010.
- Agent-Based Modeling: A New Approach for Theory Building in Social Psychology. Personality and Social Psychology Review, 2007.
- Simulated Experiments: Methodology for a Virtual World. Philosophy of Science, 2003.01.
- Understanding Climate Policy Using Participatory Agent-Based Social Simulation. MABS, 2000.
- System Dynamics: Simulation for Policy Analysis from a Feedback Perspective. Qualitative Simulation Modeling and Analysis, 1991.
- Policy Exploration through Microanalytic Simulation. 1976.

### 9. Conference

- The Multi-hub Academic Conference: Global, Inclusive, Culturally Diverse, Creative, Sustainable. Frontiers in Research Metrics and Analytics, 2021.07.
- Ten Simple Rules to Host an Inclusive Conference. PLOS Computational Biology, 2022.07.
- Transitioning to Sustainable Academic Conferences Needs More Experimentation and Reflection. Global Sustainability, 2023.09.
- Creative Destruction in Academia: A Time to Reimagine Practices in Alignment with Sustainability Values. Sustainability Science, 2023.07.

### 10. Others

- Can Generative AI Improve Social Science?. PNAS, 2024.03.
- Do LLMs Exhibit Human-like Response Biases? A Case Study in Survey Design. TACL, 2024. [Code].
- Employing Large Language Models in Survey Research. NLP Journal, 2023.09.
- Sequential Modeling Enables Scalable Learning for Large Vision Models. CVPR, 2024. [Code].
- "You Are Not the Expert Here": How Large Language Models Impact Help-Seeking in Online Communities. CHI, 2024.