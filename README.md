# LLM-Powered Human Digital Twins

A curated, community-maintained bibliography of research on LLM-powered and multi-agent human digital twins, with special focus on market research, consumer modeling, organizational decision making, and decision support.

This public contribution project prioritizes papers that directly model people, consumers, workers, teams, organizations, or social systems with LLMs, agents, personas, or digital-twin methods. Entries are grouped by research use case so readers can move from applied market and organizational work into supporting methods, evaluation, and foundations.

## Contents

- [Scope](#scope)
- [Classification Guide](#classification-guide)
- [Core Bibliography](#core-bibliography)
  - [Market Research, Synthetic Respondents, and Consumer Insight](#market-research-synthetic-respondents-and-consumer-insight)
  - [Human Digital Twins, Personas, and Preference Models](#human-digital-twins-personas-and-preference-models)
  - [Organizational Decision Making, Strategy, and Enterprise Agents](#organizational-decision-making-strategy-and-enterprise-agents)
  - [Multi-Agent Social Simulation and Collective Behavior](#multi-agent-social-simulation-and-collective-behavior)
  - [Evaluation, Benchmarks, and LLM-as-Judge Methods](#evaluation-benchmarks-and-llm-as-judge-methods)
  - [Bias, Values, Culture, and Representation](#bias-values-culture-and-representation)
  - [Cognition, Psychology, and Human Behavior Foundations](#cognition-psychology-and-human-behavior-foundations)
  - [Applied Simulation Domains](#applied-simulation-domains)
  - [Surveys, Foundations, and Platform Papers](#surveys-foundations-and-platform-papers)
- [How To Contribute](#how-to-contribute)
- [Curation Notes](#curation-notes)

## Scope

Included work:

- Peer-reviewed papers, arXiv preprints, workshop papers, and high-quality technical reports.
- Research that models humans, consumers, workers, teams, organizations, social groups, or decision makers.
- Papers that evaluate behavioral fidelity, survey simulation, preference elicitation, persona consistency, collective behavior, organizational utility, or decision-support value.

Preferred ordering:

- Topic first.
- Latest and most directly relevant work first within each topic.
- Foundational papers retained when they are still useful context.

## Classification Guide

| Category | Use it for |
| --- | --- |
| Market research and synthetic respondents | Survey simulation, customer personas, consumer choice, purchase intent, public opinion, market-research workflows |
| Human digital twins and personas | Person-level twins, persona generation, preference models, belief models, personality emulation, backstories |
| Organizational decision making | Strategy, enterprise alignment, business-process reasoning, financial or managerial decision support |
| Multi-agent social simulation | Group dynamics, collective decision making, team behavior, simulated populations, social systems |
| Evaluation and benchmarks | Fidelity tests, LLM-as-judge methods, survey benchmarks, usability evaluation, task evaluation |
| Bias, values, and representation | Political, cultural, moral, gender, demographic, and sample-representation risks |
| Cognition and psychology foundations | Human choice, decision theory, cognition, psychology, and behavior-modeling background |
| Applied domains | Education, recommendation systems, economics, finance, politics, and other domain-specific simulations |
| Surveys and platforms | Broad surveys, platform papers, toolkits, and reusable systems |

## Core Bibliography

### Market Research, Synthetic Respondents, and Consumer Insight

- **Simulation of Human Survey Responses for Market Research: The Role of Contextualization in LLM-Based Agents**. Bhupender Kumar Saini, Chandan Kumar, Kathrin Pollmann, Janina Bierkandt, Doris Janssen, Christian Knecht, Nora Fronemann. 2026. CHI EA. https://doi.org/10.1145/3772363.3798991. Directly studies how contextualization changes LLM-based survey-response simulation for market research.
- **Augmenting Survey Data with Generative AI: An Application to Economic Research**. 2026. SSRN. https://doi.org/10.2139/ssrn.6343598. Uses generative AI to augment survey data for economic research.
- **When Can Digital Personas Reliably Approximate Human Survey Findings?** Mumin Jia, Yilin Chen, Divya Sharma, Jairo Diaz-Rodriguez. 2026. arXiv preprint. https://arxiv.org/abs/2605.10659. Tests when LLM-powered digital personas can approximate held-out human survey findings.
- **Improving Cross-Cultural Survey Simulation with Calibrated Value Personas**. Axel Abels, Elias Fernandez Domingos, Apurva Shah, Tom Lenaerts. 2026. arXiv preprint. https://arxiv.org/abs/2605.16193. Uses calibrated value personas to improve cross-cultural survey-response simulation.
- **Stochastic Parrots or Singing in Harmony? Testing Five Leading LLMs for their Ability to Replicate a Human Survey with Synthetic Data**. Jason Miklian, Kristian Hoelscher, John E. Katsos. 2026. arXiv preprint. https://arxiv.org/abs/2603.00059. Compares synthetic survey data from leading LLMs against human organizational-research survey responses.
- **Assessing the Reliability of Persona-Conditioned LLMs as Synthetic Survey Respondents**. Erika Elizabeth Taday Morocho, Lorenzo Cima, Tiziano Fagni, Marco Avvenuti, Stefano Cresci. 2026. arXiv preprint. https://arxiv.org/abs/2602.18462. Evaluates whether persona prompting improves or distorts synthetic survey responses.
- **Distorted Perspectives of LLM-Simulated Preferences: Can AI Mislead Design?** Eduard Kuric, Peter Demcak, Matus Krajcovic. 2026. arXiv preprint. https://arxiv.org/abs/2605.18311. Compares LLM-simulated design preferences with real user preference-test data.
- **What Would GPT Click: Practical Effects of Human-AI Behavioral Misalignment and the Cost of Synthetic Participants in User Experience**. Eduard Kuric, Peter Demcak, Matus Krajcovic. 2026. arXiv preprint. https://arxiv.org/abs/2605.18302. Studies practical risks of using synthetic participants in UX research and product decisions.
- **Sell More, Play Less: Benchmarking LLM Realistic Selling Skill**. Xuanbo Su, Wenhao Hu, Haibo Su, Yunzhang Chen, Le Zhan, Yanqi Yang, Leo Huang. 2026. arXiv preprint. https://arxiv.org/abs/2604.07054. Introduces a sales-dialogue benchmark with realistic consumer-goods and financial-services scenarios.
- **AI-Human Hybrids for Marketing Research: Leveraging Large Language Models (LLMs) as Collaborators**. 2025. Journal of Marketing. https://doi.org/10.1177/00222429241276529. Focuses on LLM collaboration in marketing research workflows.
- **LLMs Reproduce Human Purchase Intent via Semantic Similarity Elicitation of Likert Ratings**. Benjamin F. Maier et al. 2025. arXiv preprint. https://arxiv.org/abs/2510.08338. Evaluates whether LLMs can reproduce purchase-intent signals from Likert-style responses.
- **Large Language Models as Virtual Survey Respondents: Evaluating Sociodemographic Response Generation**. Jianpeng Zhao et al. 2025. arXiv preprint. https://arxiv.org/abs/2509.06337. Studies demographic response fidelity for synthetic survey respondents.
- **Emulating Public Opinion: A Proof-of-Concept of AI-Generated Synthetic Survey Responses for the Chilean Case**. Bastian Gonzalez-Bustamante, Nando Verelst, Carla Cisternas. 2025. Working paper. https://arxiv.org/abs/2509.09871. Applied synthetic-respondent study for public-opinion research.
- **How Many Human Survey Respondents is a Large Language Model Worth? An Uncertainty Quantification Perspective**. 2025. SSRN. https://doi.org/10.2139/ssrn.6131846. Quantifies uncertainty when comparing LLM responses with human survey respondents.
- **Simulating Human Opinions with Large Language Models: Opportunities and Challenges for Personalized Survey Data Modeling**. Carolin Kaiser, Jakob Kaiser, Vladimir Manewitsch, Lea Rau, Rene Schallner. 2025. UMAP Adjunct. https://doi.org/10.1145/3708319.3733685. Focuses on personalized survey-data modeling.
- **PersonaBOT: Bringing Customer Personas to Life with LLMs and RAG**. Muhammed Rizwan, Lars Carlsson, Mohammad Loni. 2025. arXiv preprint. https://arxiv.org/pdf/2505.17156. Applies LLMs and retrieval-augmented generation to customer-persona interaction.
- **Using LLMs to Model the Beliefs and Preferences of Targeted Populations**. Keiichi Namikoshi, Alex Filipowicz, David A. Shamma, Rumen Iliev, Candice L. Hogan, Nikos Arechiga. 2024. arXiv preprint. https://arxiv.org/abs/2403.20252. Relevant to virtual focus groups and population-specific preference modeling.
- **Synthetic Replacements for Human Survey Data? The Perils of Large Language Models**. James Bisbee, Joshua D. Clinton, Cassy Dorff, Brenton Kenkel, Jennifer M. Larson. 2024. Political Analysis. https://doi.org/10.1017/pan.2024.5. Important cautionary paper on replacing human survey data with LLM outputs.
- **Random Silicon Sampling: Simulating Human Sub-Population Opinion Using a Large Language Model Based on Group-Level Demographic Information**. Seungjong Sun, Eungu Lee, Dongyan Nan, Xiangying Zhao, Wonbyung Lee, Bernard J. Jansen, Jang Hyun Kim. 2024. arXiv preprint. https://arxiv.org/pdf/2402.18144. Simulates sub-population opinion from group-level demographic signals.
- **AI-Augmented Surveys: Leveraging Large Language Models and Surveys for Opinion Prediction**. Junsol Kim, Byungkyu Lee, Peter Bearman, et al. 2023. arXiv preprint. https://arxiv.org/abs/2305.09620. Combines survey data and LLMs for opinion prediction.
- **Using LLMs for Market Research**. 2023. Harvard Business School Marketing Unit Working Paper. https://doi.org/10.2139/ssrn.4395751. Early applied reference for using LLMs in market research.

### Human Digital Twins, Personas, and Preference Models

- **Copersona: Leveraging LLMs and Expert Collaboration to Understand User Personas Through Social Media Data Analysis**. Min Yin, Haoyu Liu, Boyi Lian, Ruiyi Cai. 2026. Design for Augmented Humanity. https://doi.org/10.1177/29776481261426454. Persona-development reference for consumer understanding and product design.
- **From Role to Person: Trust Calibration Challenges in Twin Agents**. Hugo Andersson, Niklas Elmqvist. 2026. arXiv preprint. https://arxiv.org/abs/2605.19838. Frames twin agents as personal digital representatives and identifies trust-calibration challenges.
- **SYN-DIGITS: A Synthetic Control Framework for Calibrated Digital Twin Simulation**. Grace Jiarui Fan, Chengpiao Huang, Tianyi Peng, Kaizheng Wang, Yuhang Wu. 2026. arXiv preprint. https://arxiv.org/abs/2604.07513. Proposes synthetic-control calibration for LLM-based digital-twin simulation in market research and social science.
- **PersonaArena: Dynamic Simulation for Evaluating and Enhancing Persona-Level Role-Playing in Large Language Models**. Wenlong Shi, Jianxun Lian, Mingqi Wu, Haiming Qin, Mingyang Zhou, Xing Xie, Naipeng Chao, Hao Liao. 2026. arXiv preprint. https://arxiv.org/abs/2605.17044. Evaluates persona-level role-playing in dynamic social scenarios.
- **Reinforcing Human Behavior Simulation via Verbal Feedback**. Weiwei Sun, Xuhui Zhou, Jiarui Liu, Weihua Du, Haojia Sun, Yiqing Xie, Qianou Ma, Sihao Chen. 2026. arXiv preprint. https://arxiv.org/abs/2605.20506. Uses subjective verbal feedback to improve human-like behavior simulation by LLMs.
- **The Illusion of Intervention: Your LLM-Simulated Experiment is an Observational Study**. Victoria Lin, Taedong Yun, Maja Mataric, John Canny, Arthur Gretton, Alexander D'Amour. 2026. arXiv preprint. https://arxiv.org/abs/2605.20767. Explains how user drift can bias intervention estimates in LLM-simulated experiments.
- **Modeling Pathology-Like Behavioral Patterns in Language Models Through Behavioral Fine-Tuning**. Nicola Milano, Davide Marocco. 2026. arXiv preprint. https://arxiv.org/abs/2605.22356. Fine-tunes language models on structured decision tasks to induce behavior-pattern simulations.
- **A Foundation Model to Predict and Capture Human Cognition**. Marcel Binz, Elif Akata, Matthias Bethge, et al. 2025. Nature. https://doi.org/10.1038/S41586-025-09215-4. Connects foundation models with cognition modeling.
- **Twin-2K-500: A Dataset for Building Digital Twins of over 2,000 People Based on Their Answers to over 500 Questions**. Olivier Toubia, George Z. Gui, Tianyi Peng, Daniel J. Merlau, Ang Li, Haozhe Chen. 2025. arXiv preprint. https://arxiv.org/pdf/2505.17479. Dataset for person-level digital twins.
- **A Mega-Study of Digital Twins Reveals Strengths, Weaknesses and Opportunities for Further Improvement**. 2025. SSRN. https://doi.org/10.2139/ssrn.5518418. Large-scale study of digital-twin performance and limitations.
- **LLM Generated Persona Is a Promise with a Catch**. Ang Li, Haozhe Chen, Hongseok Namkoong, Tianyi Peng. 2025. arXiv preprint. https://arxiv.org/pdf/2503.16527v1. Evaluates promise and limitations of generated personas.
- **PersonaFlow: Designing LLM-Simulated Expert Perspectives for Enhanced Research Ideation**. Yiren Liu, Pranav Sharma, Mehul Jitendra Oswal, Haijun Xia, Yun Huang. 2025. DIS. https://doi.org/10.1145/3715336.3735789. Uses simulated expert perspectives for ideation.
- **PersonaCraft: Leveraging Language Models for Data-Driven Persona Development**. Soon Gyo Jung, Joni Salminen, Kholoud Khalil Aldous, Bernard J. Jansen. 2025. International Journal of Human-Computer Studies. https://doi.org/10.1016/J.IJHCS.2025.103445. Practical pipeline for data-driven personas.
- **The Impostor Is Among Us: Can Large Language Models Capture the Complexity of Human Personas?** Christopher Lazik, Christopher Katins, Charlotte Kauter, et al. 2025. arXiv preprint. https://arxiv.org/pdf/2501.04543v1. Tests limits of persona complexity.
- **D-Twins: Your Digital Twin Designed for Real-Time Boredom Intervention**. I. Chen Lo, Pei Luen Patrick Rau. 2025. CHI. https://doi.org/10.1145/3706598.3714163. Digital-twin intervention system.
- **PersonalAI: Towards Digital Twins in the Graph Form**. Mikhail Menschikov, Dmitry Evseev, Ruslan Kostoev, et al. 2025. arXiv preprint. https://arxiv.org/pdf/2506.17001. Graph-based digital-twin approach.
- **Deep Binding of Language Model Virtual Personas: a Study on Approximating Political Partisan Misperceptions**. Minwoo Kang et al. 2025. COLM / arXiv preprint. https://arxiv.org/abs/2504.11673. Persona-fidelity paper focused on belief consistency.
- **Evaluating the Ability of Large Language Models to Emulate Personality**. Yilei Wang, Jiabao Zhao, Deniz S. Ones, Liang He, Xin Xu. 2025. Scientific Reports. https://doi.org/10.1038/S41598-024-84109-5. Evaluates personality emulation in LLMs.
- **Virtual Personas for Language Models via an Anthology of Backstories**. Suhong Moon et al. 2024. EMNLP. https://arxiv.org/abs/2407.06576. Constructs consistent virtual personas through backstories.
- **Beyond Demographics: Aligning Role-Playing LLM-Based Agents Using Human Belief Networks**. Yun-Shiuan Chuang, Zach Studdiford, Krirk Nirunwiroj, et al. 2024. EMNLP. https://doi.org/10.48550/arXiv.2406.17232. Uses belief networks rather than demographics alone.
- **Understanding Human-AI Workflows for Generating Personas**. Joongi Shin, Michael A. Hedderich, Bartlomiej Jakub Rey, Andres Lucero, Antti Oulasvirta. 2024. DIS. https://doi.org/10.1145/3643834.3660729. Workflow study for persona creation.
- **Can LLMs Capture Human Preferences?** Ali Goli, Amandeep Singh. 2023. arXiv preprint. https://arxiv.org/abs/2305.02531. Early evidence on LLMs as proxies for preference judgments.
- **Can AI Language Models Replace Human Participants?** Danica Dillion, Niket Tandon, Yuling Gu, Kurt Gray. 2023. Trends in Cognitive Sciences. https://doi.org/10.1016/j.tics.2023.04.008. Foundational context for the debate on LLMs as substitutes for human participants.
- **Persona Generation from Aggregated Social Media Data**. 2017. CHI EA. https://doi.org/10.1145/3027063.3053120. Earlier persona-generation reference using social media data.
- **Data-Driven Personas: Constructing Archetypal Users with Clickstreams and User Telemetry**. 2016. CHI. https://doi.org/10.1145/2858036.2858523. Foundational data-driven persona-construction paper.

### Organizational Decision Making, Strategy, and Enterprise Agents

- **Human Decision-Making with Persuasive and Narrative LLM Explanations**. Laura R. Marusich, Mary Grace Kozuch Dhooghe, Jonathan Z. Bakdash, Murat Kantarcioglu. 2026. arXiv preprint. https://arxiv.org/abs/2605.23867. Measures how persuasive and narrative LLM explanations affect objective human decision performance.
- **Beyond Text-to-SQL: An Agentic LLM System for Governed Enterprise Analytics APIs**. Gundeep Singh, Parsa Kavehzadeh, Jing Xia, Xue-Yong Fu, Julien Bouvier Tremblay, Md Tahmid Rahman Laskar, Vincent Lum, Shashi Bhushan TN. 2026. arXiv preprint. https://arxiv.org/abs/2605.21027. Agentic enterprise analytics system for governed APIs and organizational decision support.
- **Physics-Grounded Multi-Agent Architecture for Traceable, Risk-Aware Human-AI Decision Support in Manufacturing**. Danny Hoang, Ryan Matthiessen, Christopher Miller, Nasir Mannan, Ruby ElKharboutly, David Gorsich, Matthew P. Castanier, Farhad Imani. 2026. arXiv preprint. https://arxiv.org/abs/2605.04003. Human-in-the-loop multi-agent architecture for traceable manufacturing decisions.
- **Data-driven and distributed governance of building facilities management using decentralized autonomous organization, digital twin, and large language models**. Reachsak Ly, Alireza Shojaei, Xinghua Gao, Philip Agee, Abiola Akanmu. 2026. arXiv preprint. https://arxiv.org/abs/2605.16298. Combines DAOs, digital twins, and LLMs for distributed organizational governance.
- **EconAI: Dynamic Persona Evolution and Memory-Aware Agents in Evolving Economic Environments**. Annie Liu, Zane Cao, Lang Chen, Zongxin Xu, Zigan Wang. 2026. arXiv preprint. https://arxiv.org/abs/2605.13762. Models economic agents with dynamic personas, memory, sentiment, and decision mechanisms.
- **Can LLMs Help Improve Analogical Reasoning for Strategic Decisions? Experimental Evidence from Humans and GPT-4**. Phanish Puranam, Prothit Sen, Maciej Workiewicz. 2025. arXiv preprint. https://arxiv.org/abs/2505.00603. Directly tests LLM support for strategic decision making.
- **Evaluating Intra-firm LLM Alignment Strategies in Business Contexts**. Noah Broestl et al. 2025. arXiv preprint. https://arxiv.org/abs/2505.18779. Relevant to enterprise LLM alignment and internal organizational use.
- **An LLM-based Simulation Framework for Embodied Conversational Agents in Psychological Counseling**. 2026. AAAI. https://doi.org/10.1609/aaai.v40i35.40221. Agent simulation framework for counseling contexts.
- **Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?** 2024. ACM EC. https://doi.org/10.1145/3670865.3673513. Studies economic behavior with LLM-based simulated agents.
- **EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities**. 2024. ACL. https://doi.org/10.18653/v1/2024.acl-long.829. LLM agents for macroeconomic simulation.
- **Measuring Bargaining Abilities of LLMs: A Benchmark and A Buyer-Enhancement Method**. 2024. Findings of ACL. https://doi.org/10.18653/v1/2024.findings-acl.213. Evaluates bargaining behavior and buyer-agent improvement.
- **CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading**. 2024. EMNLP. https://doi.org/10.18653/v1/2024.emnlp-main.63. Financial decision-support agent example.
- **Designing Heterogeneous LLM Agents for Financial Sentiment Analysis**. 2024. ACM Transactions on Management Information Systems. https://doi.org/10.1145/3688399. Financial-sentiment agent system.
- **Towards a Benchmark for Causal Business Process Reasoning with LLMs**. Fabiana Fournier, Lior Limonad, Inna Skarbovsky. 2024. NLP4BPM workshop at BPM. https://arxiv.org/abs/2406.05506. Enterprise benchmark for causal process reasoning.
- **FinRobot: An Open-Source AI Agent Platform for Financial Applications using Large Language Models**. Hongyang Yang et al. 2024. Technical report. https://arxiv.org/abs/2405.14767. Open-source platform for finance and decision-support workflows.

### Multi-Agent Social Simulation and Collective Behavior

- **Benchmarking LLMs for Community Governance Simulation with Life-history Narratives**. Xu Chen, Yuanzi Li, Lei Wang, Nan Lu, Yang Wang, Anding Wang, Lei Shi, Xiaoxing Fu. 2026. arXiv preprint. https://arxiv.org/abs/2605.23783. Benchmarks LLM-simulated residents for community-governance decision contexts.
- **I Can't Believe It's Corrupt: Evaluating Corruption in Multi-Agent Governance Systems**. Vedanta S P, Ponnurangam Kumaraguru. 2026. arXiv preprint. https://arxiv.org/abs/2603.18894. Evaluates rule-breaking and abuse risks in multi-agent governance simulations.
- **PAVE: A Cognitive Architecture for Legitimate Violation in Generative Agent Societies**. Ahmad Yehia, Abduallah Mohamed, Kun Qian, Tianyi Wang, Jiseop Byeon, Omar Hassanin, Christian Claudel. 2026. arXiv preprint. https://arxiv.org/abs/2605.19351. Models how generative agents reason about legitimate rule violations in emergency-like social settings.
- **Do LLM Agents Mirror Socio-Cognitive Effects in Power-Asymmetric Conversations?** Anvesh Rao Vijjini, Sagar Manjunath, Snigdha Chaturvedi. 2026. arXiv preprint. https://arxiv.org/abs/2605.17694. Tests whether LLM agents reproduce socio-cognitive effects in power-asymmetric dialogues.
- **Towards an LLM-Powered Social Digital Twinning Platform**. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2505.10681. Platform direction for social digital twinning.
- **The Empty Chair: Using LLMs to Raise Missing Perspectives in Policy Deliberations**. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2503.13812. Uses LLMs to surface missing perspectives in deliberation.
- **Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations**. 2025. EMNLP. https://doi.org/10.18653/v1/2025.emnlp-main.1562. Studies behavior alignment in high-stakes crowd simulations.
- **Generative Agent Simulations of 1,000 People**. Joon Sung Park, Carolyn Q. Zou, Aaron Shaw, et al. 2024. arXiv preprint. https://doi.org/10.48550/arXiv.2411.10109. Large-scale generative-agent simulation.
- **ElectionSim: Massive Population Election Simulation Powered by Large Language Model Driven Agents**. Xinnong Zhang, Jiayu Lin, Libo Sun, et al. 2024. arXiv preprint. https://doi.org/10.48550/ARXIV.2410.20746. Large-population simulation for electoral behavior.
- **LLM Voting: Human Choices and AI Collective Decision-Making**. 2024. AIES. https://dl.acm.org/doi/10.5555/3716662.3716809. Collective decision-making with LLM voting.
- **An Electoral Approach to Diversify LLM-Based Multi-Agent Collective Decision-Making**. 2024. arXiv preprint. https://doi.org/10.48550/arXiv.2410.15168. Applies electoral mechanisms to diversify agent decisions.
- **Embodied LLM Agents Learn to Cooperate in Organized Teams**. Xudong Guo et al. 2024. arXiv preprint. https://arxiv.org/abs/2403.12482. Models cooperation and coordination in organized teams.
- **Unleashing the Emergent Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration**. Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji. 2024. arXiv preprint. https://arxiv.org/pdf/2307.05300v3. Multi-persona self-collaboration for task solving.
- **Social Simulacra: Creating Populated Prototypes for Social Computing Systems**. 2022. UIST. https://doi.org/10.1145/3526113.3545616. Social-computing prototype simulation with populated agents.
- **Generative Agents: Interactive Simulacra of Human Behavior**. Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein. 2023. CHI / arXiv preprint. https://doi.org/10.48550/arXiv.2304.03442. Canonical paper for LLM agents with memory, reflection, and interaction.

### Evaluation, Benchmarks, and LLM-as-Judge Methods

- **Questionnaire Meets LLM: A Benchmark and Empirical Study of Structural Skills for Understanding Questions and Responses**. Duc-Hai Nguyen et al. 2025. arXiv preprint. https://arxiv.org/abs/2510.26238. Benchmark for survey-question and response-structure understanding.
- **LLMs Instead of Human Judges? A Large Scale Empirical Study across 20 NLP Evaluation Tasks**. Anna Bavaresco, Raffaella Bernardi, Leonardo Bertolazzi, et al. 2025. ACL. https://doi.org/10.18653/v1/2025.acl-short.20. Tests when LLMs can stand in for human judges.
- **A Survey on LLM-as-a-Judge**. Jiawei Gu, Xuhui Jiang, Zhichao Shi, et al. 2025. arXiv preprint. https://doi.org/10.48550/arXiv.2411.15594. Survey of LLM-as-judge methods.
- **Can GPT-4o Evaluate Usability Like Human Experts? A Comparative Study on Issue Identification in Heuristic Evaluation**. Guilherme Guerino, Luiz Rodrigues, Bruna Capeleti, Rafael Ferreira Mello, Andre Freire, Luciana Zaina. 2025. arXiv preprint. https://arxiv.org/pdf/2506.16345. Compares LLM usability evaluation with human experts.
- **LLMs-as-Judges: A Comprehensive Survey on LLM-Based Evaluation Methods**. Haitao Li, Qian Dong, Junjie Chen, et al. 2024. arXiv survey. https://doi.org/10.48550/arXiv.2412.05579. Broad survey of LLM-based evaluation methods.
- **Automated Genre-Aware Article Scoring and Feedback Using Large Language Models**. Chihang Wang, Yuxin Dong, Zhenhong Zhang, Ruotong Wang, Shuo Wang, Jiajing Chen. 2024. arXiv preprint. https://doi.org/10.48550/arXiv.2410.14165. Automated scoring and feedback example.
- **SimUser: Generating Usability Feedback by Simulating Various Users Interacting with Mobile Applications**. Wei Xiang, Hanfei Zhu, Suqi Lou, et al. 2024. CHI. https://doi.org/10.1145/3613904.3642481. Simulated user feedback for usability evaluation.
- **PsychoGAT: A Novel Psychological Measurement Paradigm through Interactive Fiction Games with LLM Agents**. 2024. ACL. https://doi.org/10.18653/v1/2024.acl-long.779. Psychological measurement benchmark using interactive fiction and agents.
- **Quantifying the Persona Effect in LLM Simulations**. 2024. ACL. https://doi.org/10.18653/v1/2024.acl-long.554. Measures how persona prompting affects simulation outputs.

### Bias, Values, Culture, and Representation

- **It's the humans, not the data: Geopolitical bias in LLMs originates in post-training, amplified by the language of the prompt**. Stuart Bladon, Brinnae Bent. 2026. arXiv preprint. https://arxiv.org/abs/2605.23825. Studies post-training and prompt-language effects on geopolitical bias in LLMs.
- **Overstating Attitudes, Ignoring Networks: LLM Biases in Simulating Misinformation Susceptibility**. Eun Cheol Choi, Lindsay E. Young, Emilio Ferrara. 2026. arXiv preprint. https://arxiv.org/abs/2602.04674. Shows bias risks when LLM-simulated respondents model misinformation belief and sharing.
- **Measuring Opinion Bias and Sycophancy via LLM-based Persuasion**. Rodrigo Nogueira, Giovana Kerche Bonas, Thales Sales Almeida, Andrea Roque, Ramon Pires, Hugo Abonizio, Thiago Laitz, Celio Larcher. 2026. arXiv preprint. https://arxiv.org/abs/2604.21564. Measures hidden opinion bias and sycophancy through persuasion interactions.
- **Measuring Human and AI Values based on Generative Psychometrics with Large Language Models**. 2025. AAAI. https://doi.org/10.1609/aaai.v39i25.34839. Measures human and AI values with generative psychometrics.
- **Representation Bias in Political Sample Simulations with Large Language Models**. 2025. Web Conference. https://doi.org/10.1145/3701716.3715591. Studies representation bias in political simulations.
- **GermanPartiesQA: Benchmarking Commercial Large Language Models for Political Bias and Sycophancy**. 2025. AIES. https://doi.org/10.1609/aies.v8i1.36552. Political-bias benchmark for commercial LLMs.
- **New Job, New Gender? Measuring the Social Bias in Image Generation Models**. 2024. ACM MM. https://doi.org/10.1145/3664647.3681433. Measures gender bias in generated images.
- **Not All Countries Celebrate Thanksgiving: On the Cultural Dominance in Large Language Models**. 2024. ACL. https://doi.org/10.18653/v1/2024.acl-long.345. Cultural dominance and global representation risk.
- **Auditing Political Exposure Bias: Algorithmic Amplification on Twitter/X Approaching the 2024 US Presidential Election**. 2024. SSRN. https://doi.org/10.2139/ssrn.5018879. Auditing political exposure bias in social platforms.
- **Whose Opinions Do Language Models Reflect?** 2023. ICML. https://proceedings.mlr.press/v202/santurkar23a.html. Measures whose views are represented by LLM outputs.
- **Marked Personas: Using Natural Language Prompts to Measure Stereotypes in Language Models**. Myra Cheng, Esin Durmus, Dan Jurafsky. 2023. ACL. https://doi.org/10.18653/v1/2023.acl-long.84. Persona-based stereotype measurement.
- **Evaluating the Moral Beliefs Encoded in LLMs**. 2023. NeurIPS. https://doi.org/10.52202/075280-2256. Evaluates moral beliefs represented in LLMs.
- **Kelly Is a Warm Person, Joseph Is a Role Model: Gender Biases in LLM-Generated Reference Letters**. 2023. Findings of EMNLP. https://doi.org/10.18653/v1/2023.findings-emnlp.243. Measures gender bias in generated recommendation letters.
- **When to Make Exceptions: Exploring Language Models as Accounts of Human Moral Judgment**. 2022. NeurIPS. https://doi.org/10.52202/068431-2063. Compares language models with human moral-judgment patterns.

### Cognition, Psychology, and Human Behavior Foundations

- **Personality Traits in Large Language Models**. 2023. Research Square preprint. https://doi.org/10.21203/rs.3.rs-3296728/v1. Evaluates personality-trait expression in LLMs.
- **Role Play with Large Language Models**. 2023. Nature. https://doi.org/10.1038/s41586-023-06647-8. Foundational context for role-play behavior in LLMs.
- **The Challenge of Using LLMs to Simulate Human Behavior: A Causal Inference Perspective**. 2023. SSRN. https://doi.org/10.2139/ssrn.4650172. Causal-inference caution for behavior simulation.
- **Using Large Language Models in Psychology**. 2023. Nature Reviews Psychology. https://doi.org/10.1038/s44159-023-00241-5. Psychology-oriented guidance on LLM usage.
- **To Predict Human Choice, Consider the Context**. Ori Plonsky, Ido Erev. 2021. Trends in Cognitive Sciences. https://doi.org/10.1016/j.tics.2021.07.007. Context-sensitive choice modeling.
- **Dual-Process Theories of Decision-Making: A Selective Survey**. Isabelle Brocas, Juan D. Carrillo. 2014. Journal of Economic Psychology. https://doi.org/10.1016/J.JOEP.2013.01.004. Classical decision-making background.
- **Grounded Cognition**. 2008. Annual Review of Psychology. https://doi.org/10.1146/annurev.psych.59.103006.093639. Cognitive foundation for embodiment and situated reasoning.
- **A Cognition-Based View of Decision Processes in Complex Social-Ecological Systems**. 2007. Ecology and Society. https://doi.org/10.5751/ES-02103-120127. Cognition-based decision-process framework.
- **Agent-Based Modeling: A New Approach for Theory Building in Social Psychology**. 2007. Personality and Social Psychology Review. https://doi.org/10.1177/1088868306294789. Classic agent-based social-psychology modeling reference.
- **Simulated Experiments: Methodology for a Virtual World**. 2003. Philosophy of Science. https://doi.org/10.1086/367872. Methodological foundation for simulated experimentation.
- **Information, Incentives, and Proenvironmental Consumer Behavior**. 1999. Journal of Consumer Policy. https://doi.org/10.1023/A:1006211709570. Consumer-behavior background.
- **Neural Dynamics of Decision Making Under Risk: Affective Balance and Cognitive-Emotional Interactions**. 1987. Psychological Review. https://doi.org/10.1037/0033-295X.94.3.395. Foundational decision-making and risk reference.

### Applied Simulation Domains

#### Education and Learning

- **Simulating Classroom Education with LLM-Empowered Agents**. 2025. NAACL. https://doi.org/10.18653/v1/2025.naacl-long.520. Classroom simulation with LLM agents.
- **Large Language Model as an Assignment Evaluator: Insights, Feedback, and Challenges in a 1000+ Student Course**. 2024. EMNLP. https://doi.org/10.18653/v1/2024.emnlp-main.146. Large-course assignment evaluation with LLMs.
- **Generative Students: Using LLM-Simulated Student Profiles to Support Question Item Evaluation**. 2024. Learning @ Scale. https://doi.org/10.1145/3657604.3662031. Simulated student profiles for item evaluation.
- **PhysicsAssistant: An LLM-Powered Interactive Learning Robot for Physics Lab Investigations**. 2024. RO-MAN. https://doi.org/10.1109/ro-man60168.2024.10731312. Embodied learning assistant for physics labs.

#### Recommendation Systems and User Simulation

- **PUB: An LLM-Enhanced Personality-Driven User Behaviour Simulator for Recommender System Evaluation**. 2025. SIGIR. https://doi.org/10.1145/3726302.3730238. Personality-driven simulator for recommender evaluation.
- **LLM as User Simulator: Towards Training News Recommender without Real User Interactions**. 2025. SIGIR. https://doi.org/10.1145/3726302.3730224. News recommender training with LLM-simulated users.
- **Agentic Feedback Loop Modeling Improves Recommendation and User Simulation**. 2025. SIGIR. https://doi.org/10.1145/3726302.3729893. Agentic feedback-loop modeling for recommendation.
- **SimUSER: Simulating User Behavior with Large Language Models for Recommender System Evaluation**. 2025. ACL Industry. https://doi.org/10.18653/v1/2025.acl-industry.5. LLM-based recommender-system evaluation simulator.
- **A LLM-based Controllable, Scalable, Human-Involved User Simulator Framework for Conversational Recommender Systems**. 2025. WWW. https://doi.org/10.1145/3696410.3714858. User-simulator framework for conversational recommendation.
- **RecUserSim: A Realistic and Diverse User Simulator for Evaluating Conversational Recommender Systems**. 2025. WWW Companion. https://doi.org/10.1145/3701716.3715258. Diverse user simulator for conversational recommenders.
- **LLM-Powered User Simulator for Recommender System**. 2025. AAAI. https://doi.org/10.1609/aaai.v39i12.33456. LLM-powered user simulator for recommender systems.
- **RecAgent: User Behavior Simulation with Large Language Model-based Agents**. 2024. ACM Transactions on Information Systems. https://doi.org/10.1145/3708985. Agent-based user-behavior simulation.
- **BASES: Large-scale Web Search User Simulation with Large Language Model based Agents**. 2024. Findings of EMNLP. https://doi.org/10.18653/v1/2024.findings-emnlp.50. Web-search user simulation.
- **Reliable LLM-based User Simulator for Task-Oriented Dialogue Systems**. 2024. SCI-CHAT Workshop. https://doi.org/10.18653/v1/2024.scichat-1.3. User simulation for task-oriented dialogue.
- **A Survey on Large Language Models for Recommendation**. 2024. World Wide Web. https://doi.org/10.1007/s11280-024-01291-2. Survey of LLMs for recommendation.
- **LLM-Rec: Personalized Recommendation via Prompting Large Language Models**. 2024. Findings of NAACL. https://doi.org/10.18653/v1/2024.findings-naacl.39. Prompt-based personalized recommendation.

#### Politics, Society, and Media

- **Trump, Twitter, and Truth Social: How Trump Used Both Mainstream and Alt-Tech Social Media to Drive News Media Attention**. 2024. Journal of Information Technology & Politics. https://doi.org/10.1080/19331681.2024.2328156. Media-attention and social-platform context.
- **Meet Your Favorite Character: Open-Domain Chatbot Mimicking Fictional Characters with Only a Few Utterances**. 2022. NAACL. https://doi.org/10.18653/v1/2022.naacl-main.377. Character simulation with limited examples.

#### Human-AI Collaboration and Interaction

- **Understanding Nonlinear Collaboration between Human and AI Agents: A Co-Design Framework for Creative Design**. 2024. CHI. https://doi.org/10.1145/3613904.3642812. Co-design framework for human-AI collaboration.
- **The Benefits of Prosociality towards AI Agents: Examining the Effects of Helping AI Agents on Human Well-Being**. Zicheng Zhu, Yugin Tan, Naomi Yamashita, Yi Chieh Lee, Renwen Zhang. 2025. CHI. https://doi.org/10.1145/3706598.3713116. Human-agent interaction and well-being.
- **Qualitative Data-Driven Personas: Designing an Interactive System for Creating AI Personas**. Amir Reza Asadi, Jess Kropczynski. 2024. WSSE. https://doi.org/10.1145/3698062.3698096. Interactive system for AI persona creation.
- **She Was Useful, but a Bit Too Optimistic: Augmenting Design with Interactive Virtual Personas**. Deep Paluck, Monica Bharadhidasan, A. Baki Kocaballi. 2025. International Journal of Human-Computer Studies. https://doi.org/10.1016/j.ijhcs.2025.103646. Interactive virtual personas for design augmentation.

### Surveys, Foundations, and Platform Papers

- **Exploring the Frontiers of LLMs in Psychological Applications: A Comprehensive Review**. 2025. Artificial Intelligence Review. https://doi.org/10.1007/s10462-025-11297-5. Review of psychological applications of LLMs.
- **Agentic Large Language Models, a Survey**. Aske Plaat et al. 2025. Journal of Artificial Intelligence Research. https://doi.org/10.1613/jair.1.18675. Broad survey of agentic LLM methods and design choices.
- **Towards Lifelong Learning of Large Language Models: A Survey**. 2025. ACM Computing Surveys. https://doi.org/10.1145/3716629. Survey of lifelong-learning directions for LLMs.
- **Human Behavior Simulation: Objectives, Methodologies, and Open Problems**. Zhang Guozhen, Yu Zihan, Li Nian, et al. 2024. arXiv preprint. https://arxiv.org/pdf/2412.07788. Overview of human behavior simulation.
- **Can Large Language Models Transform Computational Social Science?** 2024. Computational Linguistics. https://doi.org/10.1162/coli_a_00502. Perspective on LLMs in computational social science.
- **Large Language Model Guided Tree-of-Thought**. Jieyi Long. 2023. arXiv preprint. https://arxiv.org/pdf/2305.08291. Reasoning method relevant to agentic planning.
- **Metacognitive Prompting Improves Understanding in Large Language Models**. Yuqing Wang, Yun Zhao. 2024. NAACL. https://doi.org/10.18653/V1/2024.NAACL-LONG.106. Prompting method relevant to reasoning and decision support.
- **Out of One, Many: Using Language Models to Simulate Human Samples**. 2023. Political Analysis. https://doi.org/10.1017/pan.2023.2. Foundational synthetic-sample paper.
- **Aligning Large Language Models with Human: A Survey**. Yufei Wang et al. 2023. arXiv survey. https://arxiv.org/abs/2307.12966. Background on human-centered LLM alignment.
- **Emergent Abilities of Large Language Models**. 2022. arXiv preprint. https://doi.org/10.48550/arXiv.2206.07682. Foundational scaling and capability paper.
- **Agentic AI for Digital Twin**. Alexander Timms, Abigail Langbridge, Antonis Antonopoulos, Antonis Mygiakis, Eleni Voulgari, Fearghal O'Donncha. 2025. AAAI. https://doi.org/10.1609/AAAI.V39I28.35373. Digital-twin systems perspective.
- **Which Experiences Are Influential for RL Agents? Efficiently Estimating The Influence of Experiences**. Takuya Hiraoka, Guanquan Wang, Takashi Onishi, Yoshimasa Tsuruoka. 2024. Reinforcement Learning Journal. https://arxiv.org/pdf/2405.14629. Adjacent reference for agent experience and memory influence.

## How To Contribute

Public contributions are welcome. When suggesting a paper, include:

- Title
- Authors
- Year
- Venue or paper type
- DOI link or canonical paper URL
- One-line reason it belongs in this list
- Suggested category from the classification guide

Contribution standards:

- Prefer papers that directly model humans, consumers, workers, teams, organizations, or social groups.
- Prefer work that evaluates fidelity, usefulness, risks, or decision-support value.
- Prefer DOI links in `https://doi.org/...` format when available.
- Use official publisher pages, arXiv pages, or stable PDF URLs when a DOI is unavailable.
- Keep entries concise and citation-like so the README remains easy to scan.

## Curation Notes

This is a living bibliography. Add new papers to the most relevant category and order them by recency and relevance. If a paper fits multiple categories, place it where it is most useful to readers working on market research, human digital twins, or organizational decision making.

Every paper entry should include a DOI link or canonical URL. Unverified title-only suggestions should stay out of the README until a reliable source is available.