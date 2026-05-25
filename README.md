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