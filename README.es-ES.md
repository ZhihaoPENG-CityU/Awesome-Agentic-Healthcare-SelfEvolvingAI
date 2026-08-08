

<h1 align="center">
  <strong>Awesome-Self-Evolving-AI-for-Agentic-Healthcare</strong>
</h1>
<!-- Self-evolving AI for agentic healthcare: LLM agents, care workflows, multimodal clinical AI, and harness engineering -->
<p align="center">
  <sub>Artículos seleccionados y recursos de código abierto · Atención sanitaria basada en agentes · IA autoevolutiva · IA clínica multimodal · Ingeniería de arneses (harness)</sub>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <!-- <a href="https://github.com/ZhihaoPENG-CityU/Awesome-Self-Evolving-AI-for-Agentic-Healthcare/stargazers"><img src="https://img.shields.io/github/stars/ZhihaoPENG-CityU/Awesome-Self-Evolving-AI-for-Agentic-Healthcare?style=social" alt="GitHub stars"></a> -->
  <a href="#-contributing"><img src="https://img.shields.io/badge/Contribuciones-Bienvenidas-brightgreen?style=flat-square" alt="Contribuciones welcome"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Atenci%C3%B3n%20sanitaria%20basada%20en%20agentes-1d4ed8?style=flat-square" alt="Agentic healthcare">&nbsp;
  <img src="https://img.shields.io/badge/IA%20autoevolutiva-6d28d9?style=flat-square" alt="Self-evolving AI">&nbsp;
  <img src="https://img.shields.io/badge/Multimodal%20%26%20VLM-0f766e?style=flat-square" alt="Multimodal y VLM">&nbsp;
  <img src="https://img.shields.io/badge/Harness%20%26%20seguridad-b91c1c?style=flat-square" alt="Harness y seguridad">
</p>

<p align="center">
  Una lista curada de <strong>artículos</strong> y <strong>recursos de código abierto</strong> sobre
  <strong>IA autoevolutiva</strong> para <strong>atención sanitaria basada en agentes</strong>:
  sistemas de LLM y multiagente para <strong>flujos de trabajo clínicos, apoyo a la decisión, simulación y pipelines biomédicos</strong>,
  junto con <strong>adaptación, memoria, habilidades y mejora en tiempo de prueba</strong>,
  métodos <strong>multimodales y de visión–lenguaje</strong> cuando apoyan la entrega de cuidados,
  e <strong>ingeniería de harness</strong> (evaluación, seguridad, orquestación, benchmarks).
  La cobertura abarca <strong>diagnóstico médico</strong>, <strong>imágenes e informes</strong>, <strong>investigación biomédica</strong> y <strong>entornos clínicos virtuales</strong>.
</p>

<table align="center">
  <tr>
    <td align="center" width="25%"><b>Cuidado basado en agentes</b><br/><sub>Agentes, herramientas, flujos de trabajo multiagente en salud</sub></td>
    <td align="center" width="25%"><b>Autoevolución</b><br/><sub>Memoria, habilidades, adaptación, mejora sin fin</sub></td>
    <td align="center" width="25%"><b>Multimodal &amp; VLM</b><br/><sub>Imágenes, patología, visión–lenguaje clínica</sub></td>
    <td align="center" width="25%"><b>Harness</b><br/><sub>Evaluación, rúbricas, seguridad, orquestación</sub></td>
  </tr>
</table>

<br/>

---

<a id="contents"></a>

## 📌 Conten

- [Etiquetas](#-tags)
- [Artículos de IA Autoevolutiva](#-self-evolving-ai-papers-2023-Now)
- [Artículos de Revisión / Survey](#-survey-papers)
- [Atención sanitaria basada en agentes clásica (2002–2008)](#classic-agent-based-health-care-2002-2008)
- [Sistemas de atención sanitaria basados en agentes (2009–2014)](#agent-based-healthcare-systems-2009-2014)
- [Sistemas de atención sanitaria basados en agentes (2015–2022)](#agent-based-healthcare-systems-2015-2022)
- [Por tema](#-by-topic)
- [Repositorios relacionados](#-related-repositories)
- [Contribuir](#-contributing)
- [Contacto](#-contact-us)

---

<a id="tags"></a>

## 🏷️ Etiquetas

Las entradas en las siguientes secciones están etiquetadas como **`[Core]`** o **`[Related·X]`**. Las etiquetas aparecen en la **lista cronológica de artículos**, **Artículos de Revisión**, **secciones históricas de agentes** y **Por tema** (el mismo título conserva la misma etiqueta).

| Etiqueta | Significado |
|-----|---------|
| **`[Core]`** | Contexto de **atención sanitaria** con sistemas **basados en agentes** (LLM / multiagente / herramientas) **y/o autoevolución explícita** (memoria, habilidades, adaptación en tiempo de prueba, mejora continua), **o** **harness / evaluación** centrado en el cuidado. Los trabajos **multimodales y VLM médicos** cuentan como Core cuando apoyan claramente **pipelines clínicos agénticos o de automej�mejora**, no modelos solo de visión genéricos. |
| **`[Related·A]`** | Métodos **generales** de agente, autoevolución o harness — transferibles, no específicos de salud. |
| **`[Related·B]`** | **Agentes de salud** cuya señal principal es **texto, EHR, codificación, ómicas, operaciones o simulación de diálogo�diálogo** (no principalmente imagen / VLM). |
| **`[Related·C]`** | Modelos o benchmarks de **visión clínica / multimodal** sin un ángulo claro de **agencia o autoevolución**. |
| **`[Related·D]`** | **Revisiones, perspectivas, regulación y comentarios** (incluyendo la mayoría de las entradas bajo Artículos de Revisión). |
| **`[Related·E]`** | Sistemas de atención sanitaria basados en agentes **históricos** (**2002–2022**), era previa a LLM / VLM. |

> **Nota:** Las etiquetas son **curatoriales**, no juicios de calidad. Las entradas relacionadas siguen siendo valiosas para el contexto, métodos métodos e historial de literatura. Reetiquete tras cambios mayores de alcance con `python scripts/tag_readme_scope.py`.

---

## 📝 Artículos de IA Autoevolutiva (2023–Now)

> **Orden por defecto (cronológico):** Dentro de cada año `###`, las entradas están en **orden descendente**, usando el orden numérico del primer id `arxiv.org/abs/` o `arxiv.org/pdf/` `YYMM.NNNNN` cuando está presente (ej. `2605.*` antes de `2604.*` antes de `2603.*`). Las entradas con una ruta bioRxiv/medRxiv `/10.1101/YYYY.MM.DD` usan esa fecha del calendario; los viñetas sin id de ese tipo se ordenan al **final** de ese año. Los artículos cuyo id de arXiv implica otro año calendario se agrupan bajo el encabezado `###` correspondiente. Las etiquetas de venue usan **`(*Venue'YY_MM*)`** cuando el mes es conocido por los enlaces, de lo contrario la forma legada **`(*Venue'YY*)`** (sin `_MM`).
>
> **Etiquetas:** Véase [Etiquetas](#-tags) para definiciones de `[Core]` / `[Related·A]`–`[Related·E]`.
>
> **Otros órdenes:** El Markdown plano de GitHub **no** tiene controles de ordenación interactivos. Tras ediciones masivas, ejecute `python scripts/tag_readme_scope.py` para actualizar las etiquetas `[Core]` / `[Related·X]`.

### 2026

- [Related·B] (*arXiv'26_07*) **A Multi-Agent System for Autonomous, Fine-Tuning-Free Clinical Symptom Detection: Development and Validation Study**
  [[📝 Paper](https://arxiv.org/abs/2607.12886)]

- [Core] (*Meta-Radiology'26*) **Toward Vibe Medicine: A Self-Evolving Multi-Agent Framework for Clinical Decision Support**
  [[📝 Paper](https://arxiv.org/abs/2606.15504)] [[DOI](https://doi.org/10.1016/j.metrad.2026.100223)]

- [Core] (*arXiv'26_06*) **Baichuan-M4: A Clinical-Grade Medical Agent System for Continuous Care**
  [[📝 Paper](https://arxiv.org/abs/2606.08982)]

- [Related·B] (*arXiv'26_06*) **An Infectious Disease Spread Simulation Based on Large Language Model Decision Making**
  [[📝 Paper](https://arxiv.org/abs/2606.06360)]

- [Core] (*arXiv'26_06*) **D2MDT: Department-aware Multidisciplinary Team Consultation with Deliberation for Efficient Clinical Prediction**
  [[📝 Paper](https://arxiv.org/abs/2606.03543)] [[💻 Code](https://github.com/GigiResearch/D2MDT)]

- [Core] (*arXiv'26_06*) **MeDxAgent: Multi-Agent Consultation for Interactive Medical Diagnosis**
  [[📝 Paper](https://arxiv.org/abs/2606.03416)]

- [Core] (*arXiv'26_06*) **Traj-Evolve: A Self-Evolving Multi-Agent System for Patient Trajectory Modeling in Lung Cancer Early Detection**
  [[📝 Paper](https://arxiv.org/abs/2606.02812)]

- [Core] (*arXiv'26_06*) **Better with Experience: Self-Evolving LLM Agents for Evidence-Grounded Health Community Notes (EvoNote)**
  [[📝 Paper](https://arxiv.org/abs/2606.02215)]

- [Related·B] (*arXiv'26_06*) **Probe Before You Edit: Probing-Guided Molecular Optimization for LLM Agents in Structure-Based Drug Design**
  [[📝 Paper](https://arxiv.org/abs/2606.00555)]

- [Core] (*arXiv'26_05*) **SafeRx-Agent: A Knowledge-Grounded Multi-Agent Framework for Safe and Explainable Medication Recommendation**
  [[📝 Paper](https://arxiv.org/abs/2605.29146)]

- [Related·B] (*arXiv'26_05*) **LipoAgent: Coordinating Fine-Tuned LLM Agents for Safer Lipid Design**
  [[📝 Paper](https://arxiv.org/abs/2605.25250)] [[💻 Code](https://github.com/SAI-Lab-NYU/LipoAgent)]

- [Related·A] (*arXiv'26_05*) **A Sober Look at Agentic Misalignment in Automated Workflows**
  [[📝 Paper](https://arxiv.org/abs/2605.24197)]

- [Related·A] (*arXiv'26_05*) **SkillEvolBench: Benchmarking the Evolution from Episodic Experience to Procedural Skills**
  [[📝 Paper](https://arxiv.org/abs/2605.24117)]

- [Related·D] (*arXiv'26_05*) **Towards Trustworthy Agentic AI: A Comprehensive Survey of Safety, Robustness, Privacy, and System Security**
  [[📝 Paper](https://arxiv.org/abs/2605.23989)]

- [Core] (*arXiv'26_05*) **MEMOR-E: In-Context and Fine-Tuned LLM Personalization for Alzheimer's Assistive Robotics**
  [[📝 Paper](https://arxiv.org/abs/2605.23941)]

- [Core] (*arXiv'26_05*) **MedExpMem: Adapting Experience Memory for Differential Diagnosis**
  [[📝 Paper](https://arxiv.org/abs/2605.22872)]

- [Core] (*arXiv'26_05*) **ClinSeekAgent: Automating Multimodal Evidence Seeking for Agentic Clinical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2605.20176)]

- [Core] (*arXiv'26_05*) **SEMA-RAG: A Self-Evolving Multi-Agent Retrieval-Augmented Generation Framework for Medical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2605.17101)]

- [Core] (*arXiv'26_05*) **DrugSAGE: Self-evolving Agent Experience for Efficient State-of-the-Art Drug Discovery**
  [[📝 Paper](https://arxiv.org/abs/2605.15461)]

- [Related·A] (*arXiv'26_05*) **GraphFlow: An Architecture for Formally Verifiable Visual Workflows Enabling Reliable Agentic AI Automation**
  [[📝 Paper](https://arxiv.org/abs/2605.14968)]

- [Related·A] (*arXiv'26_05*) **Holistic Evaluation and Failure Diagnosis of AI Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.14865)]

- [Related·B] (*arXiv'26_05*) **Agentifying Patient Dynamics within LLMs through Interacting with Clinical World Model**
  [[📝 Paper](https://arxiv.org/abs/2605.14723)] [[💻 Code](https://github.com/FreedomIntelligence/SepsisAgent)]

- [Core] (*arXiv'26_05*) **DermAgent: A Self-Reflective Agentic System for Dermatological Image Analysis with Multi-Tool Reasoning and Traceable Decision-Making**
  [[📝 Paper](https://arxiv.org/abs/2605.14403)] [[💻 Code](https://github.com/YizeezLiu/DermAgent)]

- [Related·A] (*arXiv'26_05*) **LongMemEval-V2: Evaluating Long-Term Agent Memory Toward Experienced Colleagues**
  [[📝 Paper](https://arxiv.org/abs/2605.12493)]

- [Related·A] (*arXiv'26_05*) **SAGE: A Self-Evolving Agentic Graph-Memory Engine for Structure-Aware Associative Memory**
  [[📝 Paper](https://arxiv.org/abs/2605.12061)]

- [Related·A] (*arXiv'26_05*) **On-Policy Self-Evolution via Failure Trajectories for Agentic Safety Alignment (FATE)**
  [[📝 Paper](https://arxiv.org/abs/2605.11882)] [[💻 Code](https://github.com/YinBo0927/FATE)]

- [Core] (*arXiv'26_05*) **MedMemoryBench: Benchmarking Agent Memory in Personalized Healthcare**
  [[📝 Paper](https://arxiv.org/abs/2605.11814)]

- [Related·A] (*arXiv'26_05*) **Agent-ValueBench: A Comprehensive Benchmark for Evaluating Agent Values**
  [[📝 Paper](https://arxiv.org/abs/2605.10365)]

- [Core] (*arXiv'26_05*) **AgentRx: A Benchmark Study of LLM Agents for Multimodal Clinical Prediction Tasks**
  [[📝 Paper](https://arxiv.org/abs/2605.10286)] [[💻 Code](https://github.com/nyuad-cai/AgentRX)]

- [Related·A] (*arXiv'26_05*) **Continual Harness: Online Adaptation for Self-Improving Foundation Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.09998)]

- [Core] (*arXiv'26_05*) **CodeClinic: Evaluating Automation of Coding Skills for Clinical Reasoning Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.09675)]

- [Related·A] (*arXiv'26_05*) **MCP-Cosmos: World Model-Augmented Agents for Complex Task Execution in MCP Environments**
  [[📝 Paper](https://arxiv.org/abs/2605.09131)]

- [Related·D] (*arXiv'26_05*) **Measuring What Matters: Benchmarking Generative, Multimodal, and Agentic AI in Healthcare**
  [[📝 Paper](https://arxiv.org/abs/2605.08445)]

- [Related·A] (*arXiv'26_05*) **MASPO: Joint Prompt Optimization for LLM-based Multi-Agent Systems**
  [[📝 Paper](https://arxiv.org/abs/2605.06623)] [[💻 Code](https://github.com/wangzx1219/MASPO)]

- [Related·A] (*arXiv'26_05*) **SkillOS: Learning Skill Curation for Self-Evolving Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.06614)] [[💻 Code](https://github.com/EvolvingAgentsLabs/skillos)]

- [Core] (*arXiv'26_05*) **NeuroAgent: LLM Agents for Multimodal Neuroimaging Analysis and Research**
  [[📝 Paper](https://arxiv.org/abs/2605.06584)]

- [Related·B] (*arXiv'26_05*) **A Versatile AI Agent for Rare Disease Diagnosis and Risk Gene Prioritization**
  [[📝 Paper](https://arxiv.org/abs/2605.06226)]

- [Related·A] (*arXiv'26_05*) **TheraAgent: Self-Improving Therapeutic Agent for Precise and Comprehensive Treatment Planning**
  [[📝 Paper](https://arxiv.org/abs/2605.05963)]

- [Related·A] (*arXiv'26_05*) **MemTier: Tiered Memory Architecture and Retrieval Bottleneck Analysis for Long-Running Autonomous AI Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.03675)]

- [Related·B] (*arXiv'26_05*) **CuraView: A Multi-Agent Framework for Medical Hallucination Detection with GraphRAG-Enhanced Knowledge Verification**
  [[📝 Paper](https://arxiv.org/abs/2605.03476)]

- [Related·B] (*arXiv'26_05*) **Healthcare AI GYM for Medical Agents**
  [[📝 Paper](https://arxiv.org/abs/2605.02943)] [[💻 Code](https://github.com/minstar/Healthcare_GYM)]

- [Related·B] (*arXiv'26_05*) **An Empirical Study of Agent Skills for Healthcare: Practice, Gaps, and Governance**
  [[📝 Paper](https://arxiv.org/abs/2605.02709)]

- [Related·A] (*arXiv'26_05*) **ARA: Agentic Reproducibility Assessment for Scalable Support of Scientific Peer-Review**
  [[📝 Paper](https://arxiv.org/abs/2605.02651)] [[💻 Code](https://github.com/AndresLaverdeMarin/agentic_reproducibility_assessment)]

- [Related·B] (*arXiv'26_05*) **PhysicianBench: Evaluating LLM Agents in Real-World EHR Environments**
  [[📝 Paper](https://arxiv.org/abs/2605.02240)]

- [Related·B] (*arXiv'26_05*) **Virtual Speech Therapist: A Clinician-in-the-Loop AI Speech Therapy Agent for Personalized and Supervised Therapy**
  [[📝 Paper](https://arxiv.org/abs/2605.01101)]

- [Related·C] (*arXiv'26_04*) **LLM as Clinical Graph Structure Refiner: Enhancing Representation Learning in EEG Seizure Diagnosis**
  [[📝 Paper](https://arxiv.org/abs/2604.28178)]

- [Related·B] (*arXiv'26_04*) **Modeling Clinical Concern Trajectories in Language Model Agents**
  [[📝 Paper](https://arxiv.org/abs/2604.27872)]

- [Related·C] (*arXiv'26_04*) **Iterative Multimodal Retrieval-Augmented Generation for Medical Question Answering**
  [[📝 Paper](https://arxiv.org/abs/2604.27724)]

- [Core] (*arXiv'26_04*) **Detecting Clinical Discrepancies in Health Coaching Agents: A Dual-Stream Memory and Reconciliation Architecture**
  [[📝 Paper](https://arxiv.org/abs/2604.27045)]

- [Related·C] (*arXiv'26_04*) **MedSynapse-V: Bridging Visual Perception and Clinical Intuition via Latent Memory Evolution**
  [[📝 Paper](https://arxiv.org/abs/2604.26283)]

- [Related·C] (*arXiv'26_04*) **Case-Specific Rubrics for Clinical AI Evaluation: Methodology, Validation, and LLM-Clinician Agreement Across 823 Encounters**
  [[📝 Paper](https://arxiv.org/abs/2604.24710)]

- [Core] (*arXiv'26_04*) **NeuroClaw Technical Report: Closed-Loop Agentic AI for Executable and Reproducible Neuroimaging Research**
  [[📝 Paper](https://arxiv.org/abs/2604.24696)] [[🌐 Project](https://cuhk-aim-group.github.io/NeuroClaw/index.html)] [[💻 Code](https://github.com/CUHK-AIM-Group/NeuroClaw)]

- [Related·A] (*arXiv'26_04*) **Skill Retrieval Augmentation for Agentic AI**
  [[📝 Paper](https://arxiv.org/abs/2604.24594)] [[💻 Code](https://github.com/oneal2000/SR-Agents)]

- [Related·A] (*arXiv'26_04*) **FastOMOP: A Foundational Architecture for Reliable Agentic Real-World Evidence Generation on OMOP CDM Data**
  [[📝 Paper](https://arxiv.org/abs/2604.24572)] [[💻 Code](https://github.com/fastomop)]

- [Core] (*arXiv'26_04*) **Agentic Clinical Reasoning over Longitudinal Myeloma Records: A Retrospective Evaluation Against Expert Consensus**
  [[📝 Paper](https://arxiv.org/abs/2604.24473)]

- [Core] (*arXiv'26_04*) **Agentic AI Platforms for Autonomous Training and Rule Induction of Human-Human and Virus-Human Protein-Protein Interactions**
  [[📝 Paper](https://arxiv.org/abs/2604.23924)]

- [Related·A] (*arXiv'26_04*) **ClawTrace: Cost-Aware Tracing for LLM Agent Skill Distillation**
  [[📝 Paper](https://arxiv.org/abs/2604.23853)] [[💻 Code](https://github.com/epsilla-cloud/clawtrace)]

- [Related·B] (*arXiv'26_04*) **EndoGov: A knowledge-governed multi-agent expert system for endometrial cancer risk stratification**
  [[📝 Paper](https://arxiv.org/abs/2604.23802)]

- [Related·D] (*arXiv'26_04*) **Vibe Medicine: Redefining Biomedical Research Through Human-AI Co-Work**
  [[📝 Paper](https://arxiv.org/abs/2604.23674)]

- [Related·C] (*arXiv'26_04*) **VeriLLMed: Interactive Visual Debugging of Medical Large Language Models with Knowledge Graphs**
  [[📝 Paper](https://arxiv.org/abs/2604.23356)]

- [Related·A] (*arXiv'26_04*) **From Research Question to Scientific Workflow: Leveraging Agentic AI for Science Automation**
  [[📝 Paper](https://arxiv.org/abs/2604.21910)]

- [Related·A] (*arXiv'26_04*) **Transient Turn Injection: Exposing Stateless Multi-Turn Vulnerabilities in Large Language Models**
  [[📝 Paper](https://arxiv.org/abs/2604.21860)]

- [Related·A] (*arXiv'26_04*) **AEL: Agent Evolving Learning for Open-Ended Environments**
  [[📝 Paper](https://arxiv.org/abs/2604.21725)] [[💻 Code](https://github.com/WujiangXu/AEL)]

- [Related·B] (*arXiv'26_04*) **Trustworthy Clinical Decision Support Using Meta-Predicates and Domain-Specific Languages**
  [[📝 Paper](https://arxiv.org/abs/2604.21263)]

- [Core] (*arXiv'26_04*) **Agentic AI for Personalized Physiotherapy: A Multi-Agent Framework for Generative Video Training and Real-Time Pose Correction**
  [[📝 Paper](https://arxiv.org/abs/2604.21154)]

- [Related·A] (*arXiv'26_04*) **Co-Evolving LLM Decision and Skill Bank Agents for Long-Horizon Tasks**
  [[📝 Paper](https://arxiv.org/abs/2604.20987)] [[🌐 Project](https://wuxiyang1996.github.io/COSPLAY_page/)] [[💻 Code](https://github.com/wuxiyang1996/cos-play)]

- [Related·D] (*arXiv'26_04*) **Can "AI" Be a Doctor? A Study of Empathy, Readability, and Alignment in Clinical LLMs**
  [[📝 Paper](https://arxiv.org/abs/2604.20791)]

- [Related·A] (*arXiv'26_04*) **Learning to Evolve: A Self-Improving Framework for Multi-Agent Systems via Textual Parameter Graph Optimization**
  [[📝 Paper](https://arxiv.org/abs/2604.20714)]

- [Related·B] (*arXiv'26_04*) **MedSkillAudit: A Domain-Specific Audit Framework for Medical Research Agent Skills**
  [[📝 Paper](https://arxiv.org/abs/2604.20441)]

- [Related·B] (*arXiv'26_04*) **From Fuzzy to Formal: Scaling Hospital Quality Improvement with AI**
  [[📝 Paper](https://arxiv.org/abs/2604.20055)]

- [Core] (*arXiv'26_04*) **AblateCell: A Reproduce-then-Ablate Agent for Virtual Cell Repositories**
  [[📝 Paper](https://arxiv.org/abs/2604.19606)]

- [Related·A] (*arXiv'26_04*) **A Self-Evolving Framework for Efficient Terminal Agents via Observational Context Compression**
  [[📝 Paper](https://arxiv.org/abs/2604.19572)]

- [Related·A] (*ACL'26_04*) **From Experience to Skill: Multi-Agent Generative Engine Optimization via Reusable Strategy Learning**
  [[📝 Paper](https://arxiv.org/abs/2604.19516)] [[💻 Code](https://github.com/Wu-beining/MAGEO)]

- [Related·A] (*arXiv'26_04*) **MDAgent: A Multi-Agent Framework for End-to-End Molecular Dynamics Research**
  [[📝 Paper](https://arxiv.org/abs/2604.18622)]

- [Related·A] (*arXiv'26_04*) **First, Do No Harm (With LLMs): Mitigating Racial Bias via Agentic Workflows**
  [[📝 Paper](https://arxiv.org/abs/2604.18038)]

- [Related·B] (*arXiv'26_04*) **Neuro-Symbolic Resolution of Recommendation Conflicts in Multimorbidity Clinical Guidelines**
  [[📝 Paper](https://arxiv.org/abs/2604.17340)]

- [Core] (*arXiv'26_04*) **From Clinical Intent to Clinical Model: An Autonomous Coding-Agent Framework for Clinician-driven AI Development**
  [[📝 Paper](https://arxiv.org/abs/2604.17110)] [[💻 Code](https://github.com/zhaozh10/clinical-automata)]

- [Related·A] (*arXiv'26_04*) **GenericAgent: A Token-Efficient Self-Evolving LLM Agent via Contextual Information Density Maximization**
  [[📝 Paper](https://arxiv.org/abs/2604.17091)] [[💻 Code](https://github.com/lsdefine/GenericAgent)]

- [Core] (*arXiv'26_04*) **Agentic Large Language Models for Training-Free Neuro-Radiological Image Analysis**
  [[📝 Paper](https://arxiv.org/abs/2604.16729)]

- [Related·A] (*arXiv'26_04*) **DeepER-Med: Advancing Deep Evidence-Based Research in Medicine Through Agentic AI**
  [[📝 Paper](https://arxiv.org/abs/2604.15456)]

- [Core] (*arXiv'26_04*) **RadAgent: A Tool-Using AI Agent for Stepwise Interpretation of Chest Computed Tomography**
  [[📝 Paper](https://arxiv.org/abs/2604.15231)] [[🌐 Project](https://rad-agent.github.io/)]

- [Related·A] (*arXiv'26_04*) **Autogenesis: A Self-Evolving Agent Protocol**
  [[📝 Paper](https://arxiv.org/abs/2604.15034)]

- [Related·D] (*arXiv'26_04*) **Can LLMs Score Medical Diagnoses and Clinical Reasoning as well as Expert Panels?**
  [[📝 Paper](https://arxiv.org/abs/2604.14892)]

- [Related·C] (*arXiv'26_04*) **Rethinking Patient Education as Multi-turn Multi-modal Interaction**
  [[📝 Paper](https://arxiv.org/abs/2604.14656)]

- [Core] (*arXiv'26_04*) **Evo-MedAgent: Beyond One-Shot Diagnosis with Agents That Remember, Reflect, and Improve**
  [[📝 Paper](https://arxiv.org/abs/2604.14475)]

- [Related·C] (*arXiv'26_04*) **Seeing Through Experts' Eyes: A Foundational Vision Language Model Trained on Radiologists' Gaze and Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2604.14316)]

- [Related·C] (*arXiv'26_04*) **Enhancing Reinforcement Learning for Radiology Report Generation with Evidence-aware Rewards and Self-correcting Preference Learning**
  [[📝 Paper](https://arxiv.org/abs/2604.13598)]

- [Related·B] (*arXiv'26_04*) **QuarkMedSearch: A Long-Horizon Deep Search Agent for Exploring Medical Intelligence**
  [[📝 Paper](https://arxiv.org/pdf/2604.12867)]

- [Related·B] (*arXiv'26_04*) **CARIS: Coding-Free and Privacy-Preserving MCP Framework for Clinical Agentic Research Intelligence System**
  [[📝 Paper](https://arxiv.org/abs/2604.12258)]

- [Core] (*arXiv'26_04*) **Development, Evaluation, and Deployment of a Multi-Agent System for Thoracic Tumor Board**
  [[📝 Paper](https://arxiv.org/abs/2604.12161)]

- [Core] (*ACL'26_04*) **Dialectic-Med: Mitigating Diagnostic Hallucinations via Counterfactual Adversarial Multi-Agent Debate**
  [[📝 Paper](https://arxiv.org/abs/2604.11258)]

- [Related·A] (*arXiv'26_04*) **Mem^2Evolve: Towards Self-Evolving Agents via Co-Evolutionary Capability Expansion and Experience Distillation**
  [[📝 Paper](https://arxiv.org/abs/2604.10923)] [[💻 Code](https://buaa-irip-llm.github.io/Mem2Evolve)]

- [Core] (*arXiv'26_04*) **CAMYLA: Scaling Autonomous Research in Medical Image Segmentation**
  [[📝 Paper](https://arxiv.org/abs/2604.10696)] [[🌐 Project](https://yifangao112.github.io/camyla-page/)]

- [Related·B] (*arXiv'26_04*) **Constraint-Aware Corrective Memory for Language-Based Drug Discovery Agents (CACM)**
  [[📝 Paper](https://arxiv.org/abs/2604.09308)]

- [Related·A] (*arXiv'26_04*) **SEA-Eval: A Benchmark for Evaluating Self-Evolving Agents Beyond Episodic Assessment**
  [[📝 Paper](https://arxiv.org/abs/2604.08988)]

- [Related·A] (*arXiv'26_04*) **Multi-Agent Decision-Focused Learning via Value-Aware Sequential Communication (SeqComm-DFL)**
  [[📝 Paper](https://arxiv.org/abs/2604.08944)]

- [Related·D] (*arXiv'26_04*) **Grounding Clinical AI Competency in Human Cognition Through the Clinical World Model and Skill-Mix Framework**
  [[📝 Paper](https://arxiv.org/abs/2604.08226)]

- [Related·A] (*arXiv'26_04*) **SEARL: Joint Optimization of Policy and Tool Graph Memory for Self-Evolving Agents**
  [[📝 Paper](https://arxiv.org/abs/2604.07791)]

- [Related·B] (*arXiv'26_04*) **EMSDialog: Synthetic Multi-person Emergency Medical Service Dialogue Generation from Electronic Patient Care Reports via Multi-LLM Agents**
  [[📝 Paper](https://arxiv.org/abs/2604.07549)]

- [Related·B] (*arXiv'26_04*) **Joint Optimization of Reasoning and Dual-Memory for Self-Learning Diagnostic Agent**
  [[📝 Paper](https://arxiv.org/pdf/2604.07269)]

- [Core] (*arXiv'26_04*) **LungCURE: Benchmarking Multimodal Real-World Clinical Reasoning for Precision Lung Cancer Diagnosis and Treatment**
  [[📝 Paper](https://arxiv.org/pdf/2604.06925)]

- [Related·A] (*arXiv'26_04*) **SymptomWise: A Deterministic Reasoning Layer for Reliable and Efficient AI Systems**
  [[📝 Paper](https://arxiv.org/pdf/2604.06375)]

- [Core] (*arXiv'26_04*) **Evidence-Based Actor-Verifier Reasoning for Echocardiographic Agents**
  [[📝 Paper](https://arxiv.org/pdf/2604.06347)]

- [Related·B] (*arXiv'26_04*) **MAT-Cell: A Multi-Agent Tree-Structured Reasoning Framework for Batch-Level Single-Cell Annotation**
  [[📝 Paper](https://arxiv.org/abs/2604.06269)] [[💻 Code](https://github.com/jiangliu91/MAT-Cell-A-Multi-Agent-Tree-Structured-Reasoning-Framework-for-Batch-Level-Single-Cell-Annotation)]

- [Related·B] (*arXiv'26_04*) **From Exposure to Internalization: Dual-Stream Calibration for In-context Clinical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2604.06262)]

- [Core] (*arXiv'26_04*) **BAAI Cardiac Agent: An intelligent multimodal agent for automated reasoning and diagnosis of cardiovascular diseases from cardiac magnetic resonance imaging**
  [[📝 Paper](https://arxiv.org/abs/2604.04078)] [[💻 Code](https://github.com/plantain-herb/Cardiac-Agent)]

- [Related·A] (*arXiv'26_04*) **SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources**
  [[📝 Paper](https://arxiv.org/abs/2604.03964)]

- [Core] (*arXiv'26_04*) **XrayClaw: Cooperative-Competitive Multi-Agent Alignment for Trustworthy Chest X-ray Diagnosis**
  [[📝 Paper](https://arxiv.org/pdf/2604.02695)]

- [Related·A] (*arXiv'26_04*) **CoEvoSkills: Self-Evolving Agent Skills via Co-Evolutionary Verification**
  [[📝 Paper](https://arxiv.org/abs/2604.01687)]

- [Related·A] (*arXiv'26_04*) **CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery**
  [[📝 Paper](https://arxiv.org/abs/2604.01658)] [[💻 Code](https://github.com/Human-Agent-Society/CORAL)]

- [Core] (*arXiv'26_04*) **CARE: Privacy-Compliant Agentic Reasoning with Evidence Discordance**
  [[📝 Paper](https://arxiv.org/abs/2604.01113)]

- [Related·B] (*arXiv'26_04*) **PsychAgent: An Experience-Driven Lifelong Learning Agent for Self-Evolving Psychological Counselor**
  [[📝 Paper](https://arxiv.org/abs/2604.00931)]

- [Related·B] (*arXiv'26_04*) **Can Large Language Models Self-Correct in Medical Question Answering? An Exploratory Study**
  [[📝 Paper](https://arxiv.org/abs/2604.00261)]

- [Core] (*arXiv'26_04*) **A Safety-Aware Role-Orchestrated Multi-Agent LLM Framework for Behavioral Health Communication Simulation**
  [[📝 Paper](https://arxiv.org/abs/2604.00249)]

- [Related·B] (*arXiv'26_04*) **Agentic AI for Clinical Urgency Mapping and Queue Optimization in High-Volume Outpatient Departments: A Simulation-Based Evaluation**
  [[📝 Paper](https://arxiv.org/abs/2604.00215)]

- [Core] (*bioRxiv'26_04*) **A Unified Agent-Enabled Platform for Drug Repurposing across Molecular, Phenotypic, and Clinical Scales**
  [[📝 Paper](https://www.biorxiv.org/content/10.64898/2026.04.19.719462v1)]

- [Core] (*medRxiv'26_04*) **Artificial Intelligence Agents in Mental Health: A Systematic Review and Meta Analysis**
  [[📝 Paper](https://www.medrxiv.org/content/10.64898/2026.04.21.26351365v1)]

- [Related·D] (*medRxiv'26_04*) **Dissecting clinical reasoning failures in frontier artificial intelligence using 10,000 synthetic cases**
  [[📝 Paper](https://www.medrxiv.org/content/10.64898/2026.04.22.26351488v1)]

- [Related·D] (*medRxiv'26_04*) **HAARF: Healthcare AI Agents Regulatory Framework**
  [[📝 Paper](https://www.medrxiv.org/content/10.64898/2026.04.09.26350519v1)] [[💻 Code](https://github.com/Task-force-for-AI-agents-in-Healthcare/haarf)]

- [Related·B] (*arXiv'26_04*) **One Panel Does Not Fit All: Case-Adaptive Multi-Agent Deliberation for Clinical Prediction (CAMP)**
  [[📝 Paper](https://arxiv.org/abs/2604.00085)]

- [Related·A] (*arXiv'26_03*) **Cognitive Friction: A Decision-Theoretic Framework for Bounded Deliberation in Tool-Using Agents**
  [[📝 Paper](https://arxiv.org/abs/2603.30031)]

- [Related·B] (*arXiv'26_03*) **Perfecting Human–AI Interaction at Clinical Scale: Turning Production Signals into Safer, More Human Conversations**
  [[📝 Paper](https://arxiv.org/abs/2603.29893)]

- [Related·B] (*arXiv'26_03*) **Symphony for Medical Coding: A Next-Generation Agentic System for Scalable and Explainable Medical Coding**
  [[📝 Paper](https://arxiv.org/abs/2603.29709)]

- [Related·A] (*arXiv'26_03*) **Meta-Harness: End-to-End Optimization of Model Harnesses**
  [[📝 Paper](https://arxiv.org/pdf/2603.28052)]

- [Core] (*arXiv'26_03*) **Improving Clinical Diagnosis with Counterfactual Multi-Agent Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2603.27820)]

- [Related·B] (*arXiv'26_03*) **Self-evolving AI agents for protein discovery and directed evolution**
  [[📝 Paper](https://arxiv.org/abs/2603.27303)] [[💻 Code](https://github.com/ai4protein/VenusFactory2)]

- [Related·B] (*arXiv'26_03*) **MediHive: A Decentralized Agent Collective for Medical Question Answering**
  [[📝 Paper](https://arxiv.org/abs/2603.27150)]

- [Related·A] (*arXiv'26_03*) **AIRA_2: Overcoming Bottlenecks in AI Research Agents**
  [[📝 Paper](https://arxiv.org/pdf/2603.26499)]

- [Related·A] (*arXiv'26_03*) **Reflect to Inform: Boosting Multimodal Reasoning via Information-Gain-Driven Verification**
  [[📝 Paper](https://arxiv.org/pdf/2603.26348v1)]

- [Core] (*arXiv'26_03*) **SkinGPT-X: A Self-Evolving Collaborative Multi-Agent System for Transparent and Trustworthy Dermatological Diagnosis**
  [[📝 Paper](https://arxiv.org/abs/2603.26122)]

- [Related·B] (*arXiv'26_03*) **Doctorina MedBench: End-to-End Evaluation of Agent-Based Medical AI**
  [[📝 Paper](https://arxiv.org/pdf/2603.25821)]

- [Related·A] (*arXiv'26_03*) **UI-Voyager: A Self-Evolving GUI Agent Learning via Failed Experience**
  [[📝 Paper](https://arxiv.org/pdf/2603.24533v1)]

- [Core] (*arXiv'26_03*) **CarePilot: A Multi-Agent Framework for Long-Horizon Computer Task Automation in Healthcare**
  [[📝 Paper](https://arxiv.org/abs/2603.24157)] [[🌐 Project](https://akashghosh.github.io/Care-Pilot/)] [[💻 Code](https://github.com/AkashGhosh/CarePilot)]

- [Related·B] (*arXiv'26_03*) **GSEM: Graph-based Self-Evolving Memory for Experience Augmented Clinical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2603.22096)]

- [Related·A] (*arXiv'26_03*) **When Models Judge Themselves: Unsupervised Self-Evolution for Multimodal Reasoning**
  [[📝 Paper](https://arxiv.org/pdf/2603.21289v1)]

- [Related·A] (*arXiv'26_03*) **MemMA: Coordinating the Memory Cycle through Multi-Agent Reasoning and In-Situ Self-Evolution**
  [[📝 Paper](https://arxiv.org/abs/2603.18718)]

- [Related·A] (*arXiv'26_03*) **AgentFactory: A Self-Evolving Framework Through Executable Subagent Accumulation and Reuse**
  [[📝 Paper](https://arxiv.org/abs/2603.18000)] [[💻 Code](https://github.com/zzatpku/AgentFactory)]

- [Related·A] (*arXiv'26_03*) **SkillEvolver: Dynamic Skill Lifecycle Management for Agentic RL**
  [[📝 Paper](https://arxiv.org/abs/2603.17187)] [[💻 Code](https://github.com/aiming-lab/MetaClaw)]

- [Core] (*arXiv'26_03*) **OpenHospital: A Thing-in-itself Arena for Evolving and Benchmarking LLM-based Collective Intelligence**
  [[📝 Paper](https://arxiv.org/abs/2603.14771)] [[💻 Code](https://github.com/ZJU-LLMs/Agent-Kernel/tree/main/demo/OpenHospital)]

- [Core] (*arXiv'26_03*) **EviAgent: Evidence-Driven Agent for Radiology Report Generation**
  [[📝 Paper](https://arxiv.org/pdf/2603.13956)]

- [Core] (*arXiv'26_03*) **TheraAgent: Multi-Agent Framework with Self-Evolving Memory and Evidence-Calibrated Reasoning for PET Theranostics**
  [[📝 Paper](https://arxiv.org/abs/2603.13676)]

- [Related·A] (*arXiv'26_03*) **CreativeBench: Benchmarking and Enhancing Machine Creativity via Self-Evolving Challenges**
  [[📝 Paper](https://arxiv.org/pdf/2603.11863)]

- [Related·B] (*arXiv'26_03*) **Emulating Clinician Cognition via Self-Evolving Deep Clinical Research**
  [[📝 Paper](https://arxiv.org/abs/2603.10677)]

- [Core] (*arXiv'26_03*) **Skill-Evolving Grounded Reasoning for Free-Text Promptable 3D Medical Image Segmentation**
  [[📝 Paper](https://arxiv.org/abs/2603.08215)]

- [Related·A] (*arXiv'26_03*) **EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery**
  [[📝 Paper](https://arxiv.org/pdf/2603.08127)]

- [Core] (*arXiv'26_03*) **Med-Evo: Test-time Self-evolution for Medical Multimodal Large Language Models**
  [[📝 Paper](https://arxiv.org/abs/2603.07443)]

- [Core] (*arXiv'26_03*) **Evolving Medical Imaging Agents via Experience-driven Self-skill Discovery (MACRO)**
  [[📝 Paper](https://arxiv.org/abs/2603.05860)]

- [Related·A] (*arXiv'26_03*) **Tool-Genesis: A Task-Driven Tool Creation Benchmark for Self-Evolving Language Agent**
  [[📝 Paper](https://arxiv.org/pdf/2603.05578)]

- [Related·A] (*arXiv'26_03*) **AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution**
  [[📝 Paper](https://arxiv.org/abs/2603.01145)] [[💻 Code](https://github.com/ECNU-ICALK/AutoSkill)]

- [Related·C] (*arXiv'26_03*) **How Well Do Multimodal Models Reason on ECG Signals?**
  [[📝 Paper](https://arxiv.org/abs/2603.00312)]

- [Related·D] (*arXiv'26_02*) **The Doctor Will (Still) See You Now: On the Structural Limits of Agentic AI in Healthcare**
  [[📝 Paper](https://arxiv.org/abs/2602.18460)]

- [Related·D] (*arXiv'26_02*) **Agentic AI, Medical Morality, and the Transformation of the Clinic**
  [[📝 Paper](https://arxiv.org/abs/2602.16553)]

- [Core] (*arXiv'26_02*) **Closing Reasoning Gaps in Clinical Agents with Differential Reasoning Learning**
  [[📝 Paper](https://arxiv.org/abs/2602.09945)]

- [Related·A] (*arXiv'26_02*) **S1-NexusAgent: a Self-Evolving Agent Framework for Multidisciplinary Scientific Research**
  [[📝 Paper](https://arxiv.org/abs/2602.01550)]

- [Related·A] (*arXiv'26_02*) **Position: Agentic Evolution is the Path to Evolving LLMs**
  [[📝 Paper](https://arxiv.org/pdf/2602.00359v2)]

- [Related·B] (*bioRxiv'26_02*) **PantheonOS: An Evolvable Multi-Agent Framework for Automatic Genomics Discovery**
  [[📝 Paper](https://www.biorxiv.org/content/10.64898/2026.02.26.707870v1)] [[🌐 Project](https://pantheonos.stanford.edu)] [[💻 Code](https://github.com/aristoteleo)]

- [Related·B] (*arXiv'26_01*) **EvoClinician: A Self-Evolving Agent for Multi-Turn Medical Diagnosis via Test-Time Evolutionary Learning**
  [[📝 Paper](https://arxiv.org/abs/2601.22964)] [[💻 Code](https://github.com/yf-he/EvoClinician)]

- [Core] (*arXiv'26_01*) **Route, Retrieve, Reflect, Repair (R⁴): Self-Improving Agentic Framework for Visual Detection and Linguistic Reasoning in Medical Imaging**
  [[📝 Paper](https://arxiv.org/abs/2601.08192)] [[💻 Code](https://github.com/faiyazabdullah/MultimodalMedAgent)]

- [Core] (*arXiv'26_01*) **IBISAgent: Reinforcing Pixel-Level Visual Reasoning in MLLMs for Universal Biomedical Object Referring and Segmentation**
  [[📝 Paper](https://arxiv.org/abs/2601.03054)]

- [Related·B] (*arXiv'26_01*) **ClinicalReTrial: A Self-Evolving AI Agent for Clinical Trial Protocol Optimization**
  [[📝 Paper](https://arxiv.org/abs/2601.00290)]

- [Related·B] (*bioRxiv'26_01*) **Agentomics: An Agentic System that Autonomously Develops Novel State-of-the-art Solutions for Biomedical Machine Learning Tasks**
  [[📝 Paper](https://www.biorxiv.org/content/10.64898/2026.01.27.702049v1)]

- [Core] (*AACR Annual Meeting'26*) **Agentic AI as the Cancer Researcher: Autonomous Discovery in Oncology**
  [[🌐 Program](https://www.aacr.org/meeting/aacr-annual-meeting-2026/program/)]

- [Core] (*CEEM'26*) **From Non-Agentic LLMs to Multi-Agent Systems in Emergency Medicine: A Scoping Review**
  [[📝 Paper](https://doi.org/10.15441/ceem.26.136)]

- [Core] (*Expert Syst. Appl.'26*) **CARE: A clinical agentic reasoning engine to enhance real-World diagnostic accuracy via structured medical reasoning**
  [[📝 Paper](https://doi.org/10.1016/j.eswa.2026.131476)]

- [Core] (*Nat. Health'26*) **A multi-agent framework combining large language models with medical flowcharts for self-triage**
  [[📝 Paper](https://www.nature.com/articles/s44360-026-00112-2)] [[💻 Code](https://github.com/digihealthucsd/Multi-agent-self-triage-system)]

- [Core] (*Nat. Med.'26*) **An agentic framework for autonomous scientific discovery in cancer pathology**
  [[📝 Paper](https://www.nature.com/articles/s41591-026-04357-y)]

- [Core] (*Nature Biomedical Engineering'26*) **BioMedAgent: A Self-Evolving LLM Multi-Agent Framework for Autonomous, Tool-Aware Biomedical Data Analyses**
  [[📝 Paper](https://www.nature.com/articles/s41551-026-01634-6)] [[🌐 Project](http://biomed.drai.cn)] [[💻 Code](https://github.com/BOBQWERA/BioMedAgent)]

- [Core] (*npj Digital Medicine'26*) **Human-AI co-design for clinical prediction models (HACHI)**
  [[📝 Paper](https://www.nature.com/articles/s41746-026-02838-5)] [[💻 Code](https://github.com/jjfenglab/HACHI)]

- [Related·A] (*GitHub'26*) **EverOS: Build, evaluate, and integrate long-term memory for self-evolving agents**
  [[💻 Code](https://github.com/EverMind-AI/EverOS)]

- [Related·A] (*GitHub'26*) **NanoResearch: Co-Evolving Skills, Memory, and Policy for Personalized Research Automation**
  [[💻 Code](https://github.com/OpenRaiser/NanoResearch)]

- [Related·A] (*ICLR'26 Rejected*) **SkillEvo: An Experience Learning Framework with Reinforcement Learning for Skill Evolution**
  [[📝 Paper](https://openreview.net/forum?id=S1cIE9pe3k)]

- [Related·A] (*arXiv'26*) **MAGE: Multi-Agent Self-Evolution with Co-Evolutionary Knowledge Graphs**
  [[🌐 arXiv](https://arxiv.org/search/?searchtype=all&query=MAGE%3A%20Multi-Agent%20Self-Evolution%20with%20Co-Evolutionary%20Knowledge%20Graphs&abstracts=show&order=-announced_date_first&size=25)]

- [Related·B] (*Cambridge Open Engage'26*) **Artificial Epidemiology: How Self-Evolving Clinical AI Manufactures Disease Prevalence from Administrative Coding Artifacts**
  [[📝 Paper](https://doi.org/10.33774/coe-2026-ssm1q)]

- [Related·B] (*npj Digital Medicine'26*) **EvoMDT: A Self-Evolving Multi-Agent System for Structured Clinical Decision-Making in Multi-Cancer**
  [[📝 Paper](https://www.nature.com/articles/s41746-025-02304-8)] [[💻 Code](https://github.com/KesselZ/EvoMDT)]

- [Related·D] (*Health Inf Sci Syst'26*) **Enhancing LLM-based medical decision-making by test-time knowledge acquisition**
  [[📝 Paper](https://doi.org/10.1007/s13755-026-00449-8)]

- [Core] (*bioRxiv'26_07*) **STELLA: Towards a Biomedical World Model with Self-Evolving Multimodal Agents**
  [[📝 Paper](https://www.biorxiv.org/content/10.1101/2025.07.01.662467v2)]

- [Related·B] (*bioRxiv'26_06*) **OriGene: A Self-Evolving Virtual Disease Biologist Automating Therapeutic Target Discovery**
  [[📝 Paper](https://www.biorxiv.org/content/10.1101/2025.06.03.657658v2)]

### 2025

- [Core] (*arXiv'25_10*) **Evolving Diagnostic Agents in a Virtual Clinical Environment**
  [[📝 Paper](https://arxiv.org/abs/2510.24654)]

- [Core] (*Radiology: Artificial Intelligence'26_10*) **ReclAIm: A Multi-Agent Framework for Monitoring and Correcting Performance Decline in Medical Imaging AI**
  [[📝 Paper](https://arxiv.org/abs/2510.17004)] [[DOI](https://doi.org/10.1148/ryai.250923)]

- [Core] (*bioRxiv'25_10*) **LabOS: The AI-XR Co-Scientist That Sees and Works With Humans**
  [[📝 Paper](https://www.biorxiv.org/content/10.1101/2025.10.16.679418v2)] [[💻 Code](https://github.com/zaixizhang/LabOS)] [[🌐 Project](https://ai4labos.com/)]

- [Core] (*arXiv'25_10*) **GenCellAgent: Generalizable, Training-Free Cellular Image Segmentation via Large Language Model Agents**
  [[📝 Paper](https://arxiv.org/abs/2510.13896)]

- [Related·A] (*ICLR'26_10*) **EvoTest: Evolutionary Test-Time Learning for Self-Improving Agentic Systems**
  [[📝 Paper](https://arxiv.org/abs/2510.13220)] [[💻 Code](https://github.com/yf-he/EvoTest)]

- [Related·A] (*ICLR'26_10*) **CoT-Evo: Evolutionary Distillation of CoT for Scientific Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2510.13166)] [[💻 Code](https://github.com/Irving-Feng/CoT-Evo)]

- [Related·B] (*arXiv'25_10*) **RareAgent: Self-Evolving Reasoning for Drug Repurposing in Rare Diseases**
  [[📝 Paper](https://arxiv.org/abs/2510.05764)]

- [Core] (*ICLR'26_10*) **Doctor-R1: Mastering Clinical Inquiry with Experiential Agentic Reinforcement Learning**
  [[📝 Paper](https://arxiv.org/abs/2510.04284)] [[🌐 ICLR](https://iclr.cc/virtual/2026/poster/10006814)] [[💻 Code](https://github.com/thu-unicorn/Doctor-R1)]

- [Related·B] (*ICLR'26_09*) **KnowGuard: Knowledge-Driven Abstention for Multi-Round Clinical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2509.24816)] [[🌐 ICLR](https://iclr.cc/virtual/2026/poster/10008150)] [[💻 Code](https://github.com/IcecreamArtist/KnowGuard)]

- [Core] (*arXiv'25_09*) **MedLA: A Logic-Driven Multi-Agent Framework for Complex Medical Reasoning with Large Language Models**
  [[📝 Paper](https://arxiv.org/abs/2509.23725)]

- [Core] (*arXiv'25_09*) **A Co-evolving Agentic AI System for Medical Imaging Analysis (TissueLab)**
  [[📝 Paper](https://arxiv.org/abs/2509.20279)] [[🖥️ Platform](https://tissuelab.org)]

- [Core] (*arXiv'25_09*) **MACD: Multi-Agent Clinical Diagnosis with Self-Learned Knowledge for LLM**
  [[📝 Paper](https://arxiv.org/abs/2509.20067)]

- [Related·B] (*arXiv'25_09*) **Evaluation of Causal Reasoning for Large Language Models in Contextualized Clinical Scenarios of Laboratory Test Interpretation**
  [[📝 Paper](https://arxiv.org/abs/2509.16372)]

- [Related·A] (*arXiv'25_09*) **Evolving-RL: End-to-End Optimization of Experience-Driven Self-Evolving Capability**
  [[📝 Paper](https://arxiv.org/abs/2509.15194)] [[💻 Code](https://github.com/YujunZhou/EVOL-RL)]

- [Related·D] (*medRxiv'25_08*) **Automation Bias in Large Language Model Assisted Diagnostic Reasoning Among AI-Trained Physicians**
  [[📝 Paper](https://www.medrxiv.org/content/10.1101/2025.08.23.25334280v2)]

- [Related·B] (*arXiv'25_08*) **HealthFlow: A Self-Evolving AI Agent with Meta Planning for Autonomous Healthcare Research**
  [[📝 Paper](https://arxiv.org/abs/2508.02621)] [[💻 Code](https://github.com/yhzhu99/HealthFlow)]

- [Related·B] (*arXiv'25_06*) **Integrating Dynamical Systems Learning with Foundational Models: A Meta-Evolutionary AI Framework for Clinical Trials**
  [[📝 Paper](https://arxiv.org/abs/2506.14782)]

- [Core] (*ICLR'26_06*) **Language Agents for Hypothesis-driven Clinical Decision Making with Reinforcement Learning**
  [[📝 Paper](https://arxiv.org/abs/2506.13474)] [[🌐 ICLR](https://iclr.cc/virtual/2026/poster/10011252)] [[💻 Code](https://github.com/dharouni/LA-CDM)]

- [Related·B] (*arXiv'25_06*) **CounselBench: A Large-Scale Expert Evaluation and Adversarial Benchmarking of Large Language Models in Mental Health Question Answering**
  [[📝 Paper](https://arxiv.org/abs/2506.08584)]

- [Related·B] (*arXiv'25_06*) **Agentomics-ML: Autonomous Machine Learning Experimentation Agent for Genomic and Transcriptomic Data**
  [[📝 Paper](https://arxiv.org/abs/2506.05542)] [[💻 Code](https://github.com/BioGeMT/Agentomics-ML)]

- [Related·B] (*arXiv'25_06*) **MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science**
  [[📝 Paper](https://arxiv.org/abs/2506.04405)]

- [Core] (*ICLR'26_06*) **MMedAgent-RL: Optimizing Multi-Agent Collaboration for Multimodal Medical Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2506.00555)] [[🌐 ICLR](https://iclr.cc/virtual/2026/poster/10011724)]

- [Related·B] (*arXiv'25_05*) **Silence is Not Consensus: Disrupting Agreement Bias in Multi-Agent LLMs via Catfish Agent for Clinical Decision Making**
  [[📝 Paper](https://arxiv.org/abs/2505.21503)]

- [Core] (*arXiv'25_05*) **MedSentry: Understanding and Mitigating Safety Risks in Medical LLM Multi-Agent Systems**
  [[📝 Paper](https://arxiv.org/abs/2505.20824)] [[💻 Code](https://github.com/KaiChenNJ/MedSentry)]

- [Related·B] (*arXiv'25_05*) **DoctorAgent-RL: A Multi-Agent Collaborative Reinforcement Learning System for Multi-Turn Clinical Dialogue**
  [[📝 Paper](https://arxiv.org/abs/2505.19630)]

- [Related·A] (*arXiv'25_05*) **Nature's Insight: A Novel Framework and Comprehensive Analysis of Agentic Reasoning Through the Lens of Neuroscience**
  [[📝 Paper](https://arxiv.org/abs/2505.05515)] [[💻 Code](https://github.com/BioRAILab/Awesome-Neuroscience-Agent-Reasoning)]

- [Core] (*MICCAI'25_03*) **MedAgentSim: Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions**
  [[📝 Paper](https://arxiv.org/pdf/2503.22678)] [[💻 Code](https://github.com/MAXNORM8650/MedAgentSim)]

- [Core] (*arXiv'25_03*) **PharmAgents: Building a Virtual Pharma with Large Language Model Agents**
  [[📝 Paper](https://arxiv.org/abs/2503.22164)]

- [Core] (*ICLR'26_03*) **MedAgent-Pro: Towards Evidence-based Multi-modal Medical Diagnosis via Reasoning Agentic Workflow**
  [[📝 Paper](https://arxiv.org/abs/2503.18968)] [[🌐 ICLR](https://iclr.cc/virtual/2026/poster/10008810)] [[💻 Code](https://github.com/jinlab-imvr/MedAgent-Pro)]

- [Related·B] (*arXiv'25_03*) **MDTeamGPT: A Self-Evolving LLM-based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation**
  [[📝 Paper](https://arxiv.org/abs/2503.13856)] [[🌐 Project](https://kaichennj.github.io/MDTeamGPT-Main/)]

- [Related·B] (*arXiv'25_03*) **MAP: Evaluation and Multi-Agent Enhancement of Large Language Models for Inpatient Pathways**
  [[📝 Paper](https://arxiv.org/abs/2503.13205)]

- [Core] (*arXiv'25_02*) **PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology**
  [[📝 Paper](https://arxiv.org/pdf/2502.08916)]

- [Related·A] (*arXiv'25_02*) **EvoAgent: Self-evolving Agent with Continual World Model for Long-Horizon Tasks**
  [[📝 Paper](https://arxiv.org/abs/2502.05907)] [[💻 Code](https://github.com/siyuyuan/evoagent)]

- [Related·A] (*NeurIPS'25*) **SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2502.04780)] [[💻 Code](https://github.com/zou-group/sirius)]

- [Related·A] (*EMNLP'25 Demo*) **EvoAgentX: An Automated Framework for Evolving Agentic Workflows**
  [[📝 Paper](https://aclanthology.org/2025.emnlp-demos.47/)] [[💻 Code](https://github.com/EvoAgentX/EvoAgentX)]

- [Related·A] (*IJISAE'25*) **Self-Evolving LLM Ecosystems for Precision Medicine**
  [[📝 Paper](https://ijisae.org/index.php/IJISAE/article/view/7793)]

- [Related·B] (*Advanced Science'25*) **Autonomous Self-Evolving Research on Biomedical Data: The DREAM Paradigm**
  [[📝 Paper](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202417066)]

- [Related·B] (*IEEE ICASSP'25*) **SeM-Agents: A Self-Evolving Framework for Multi-Agent Medical Consultation Based on Large Language Models**
  [[📝 Paper](https://ieeexplore.ieee.org/abstract/document/10889517)]

- [Related·B] (*NeurIPS'25 Workshop*) **HealthAlign-Agents: Self-Play Reflective Prompting for Culturally Aligned Health Communication in Low-Resource Languages**
  [[📝 Paper](https://neurips.cc/virtual/2025/135933)]

### 2024

- [Core] (*arXiv'24_12*) **KG4Diagnosis: A Hierarchical Multi-Agent LLM Framework with Knowledge Graph Enhancement for Medical Diagnosis**
  [[📝 Paper](https://arxiv.org/abs/2412.16833)]

- [Core] (*arXiv'24_10*) **Adaptive Reasoning and Acting in Medical Language Agents**
  [[📝 Paper](https://arxiv.org/abs/2410.10020)]

- [Related·B] (*arXiv'24_09*) **Depression Diagnosis Dialogue Simulation: Self-improving Psychiatrist with Tertiary Memory**
  [[📝 Paper](https://arxiv.org/abs/2409.15084)]

- [Core] (*arXiv'24_05*) **AgentClinic: A Multimodal Agent Benchmark to Evaluate AI in Simulated Clinical Environments**
  [[📝 Paper](https://arxiv.org/abs/2405.07960)] [[🌐 Project](https://agentclinic.github.io)] [[💻 Code](https://github.com/samuelschmidgall/agentclinic)]

- [Core] (*arXiv'24_05*) **Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents**
  [[📝 Paper](https://arxiv.org/abs/2405.02957)]

- [Core] (*ACM-BCB'24_04*) **ClinicalAgent: Clinical Trial Multi-Agent System with LLM-based Reasoning**
  [[📝 Paper](https://arxiv.org/abs/2404.14777)] [[💻 Code](https://github.com/LeoYML/clinical-agent)]

- [Core] (*arXiv'24*) **Towards Conversational Diagnostic AI (AMIE)**
  [[📝 Paper](https://www.nature.com/articles/s41586-025-08866-7)]

### 2023

- [Related·A] (*arXiv'23_12*) **ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent**
  [[📝 Paper](https://arxiv.org/abs/2312.10003)]

- [Related·A] (*arXiv'23_06*) **SELFEVOLVE: A Code Evolution Framework via Large Language Models**
  [[📝 Paper](https://arxiv.org/abs/2306.02907)]

---


## 📚 Artículos de Revisión / Survey

> Las entradas en esta sección están etiquetadas **`[Related·D]`** por defecto (revisiones y perspectivas). Véase [Etiquetas](#-tags) para las definiciones.

- [Related·D] (*npj AI'26*) **AI agent in healthcare: applications, evaluations, and future directions**
  [[📝 Paper](https://www.nature.com/articles/s44387-026-00076-4)]

- [Related·D] (*arXiv'26_05*) **Beyond Individual Intelligence: Surveying Collaboration, Failure Attribution, and Self-Evolution in LLM-based Multi-Agent Systems**
  [[📝 Paper](https://arxiv.org/abs/2605.14892)]

- [Related·D] (*J. Med. Syst.'26*) **When Chatbots Become Agents: The Next Phase of Healthcare AI**
  [[📝 Paper](https://doi.org/10.1007/s10916-026-02402-4)]

- [Related·D] (*arXiv'26_02*) **Agentic AI in Healthcare & Medicine: A Seven-Dimensional Taxonomy for Empirical Evaluation of LLM-based Agents**
  [[📝 Paper](https://arxiv.org/abs/2602.04813)]

- [Related·D] (*arXiv'26_05*) **An Empirical Study of Agent Skills for Healthcare: Practice, Gaps, and Governance**
  [[📝 Paper](https://arxiv.org/abs/2605.02709)]

- [Related·D] (*medRxiv'26_04*) **Artificial Intelligence Agents in Mental Health: A Systematic Review and Meta Analysis**
  [[📝 Paper](https://www.medrxiv.org/content/10.64898/2026.04.21.26351365v1)]

- [Related·D] (*CEEM'26*) **From Non-Agentic LLMs to Multi-Agent Systems in Emergency Medicine: A Scoping Review**
  [[📝 Paper](https://doi.org/10.15441/ceem.26.136)]

- [Related·D] (*arXiv'25_08*) **A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems**
  [[📝 Paper](https://arxiv.org/abs/2508.07407)] [[💻 Code](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents)]

- [Related·D] (*arXiv'25_07*) **A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence**
  [[📝 Paper](https://arxiv.org/abs/2507.21046)]

- [Related·D] (*arXiv'25_05*) **Nature's Insight: A Novel Framework and Comprehensive Analysis of Agentic Reasoning Through the Lens of Neuroscience**
  [[📝 Paper](https://arxiv.org/abs/2505.05515)] [[💻 Code](https://github.com/BioRAILab/Awesome-Neuroscience-Agent-Reasoning)]

- [Related·D] (*Comput Methods Programs Biomed'23*) **A Survey on Agents Applications in Healthcare: Opportunities, Challenges and Trends**
  [[📝 Paper](https://www.sciencedirect.com/science/article/pii/S0169260723001906)]

- [Related·D] (*J. Med. Syst.'16*) **A Systematic Literature Review of Agents Applied in Healthcare**
  [[📝 Paper](https://doi.org/10.1007/s10916-015-0376-2)] [[Scopus](https://www.scopus.com/pages/publications/84947560681)]

- [Related·D] (*Int. J. Med. Inf.'10*) **Agents applied in health care: A review**
  [[📝 Paper](https://www.sciencedirect.com/science/article/pii/S138650561000016X)] [[PubMed](https://pubmed.ncbi.nlm.nih.gov/20129820/)]

### Atención sanitaria basada en agentes clásica (2002–2008)

> Las entradas en las secciones históricas usan la etiqueta **`[Related·E]`**. Véase [Etiquetas](#-tags).

> Trabajo representativo de **agentes de software / multiagente** dirigido a **sistemas de información clínica, telecuidado, flujos de trabajo hospitalarios, cumplimiento de guías o vigilancia**, con **primera publicación entre 2002 y 2008** (alineado con la ventana de literatura en Isern & Sánchez & Moreno, *Int. J. Med. Inf.*, 2010).  
> **No listado aquí (razones típicas):** teoría general de agentes o libros de texto SMA sin despliegue médico (#1, #6–7, #38–40, #50); piezas de posición o revisiones de IA en medicina **fechadas en 2009** (#5); artículos de agentes **fechados en 2009** (#24 artículo de revista HealthAgents, #54 encuesta de interoperabilidad); revisiones de bioinformática no centradas en agentes (#17); programación hospitalaria clásica **ICMAS 1998** (#9); líneas incompletas / de venue poco claro en la lista original (#16).

- [Related·E] (*Birkhäuser'03*) **Applications of Software Agent Technology in the Health Care Domain**
  [[📝 Book](https://link.springer.com/book/10.1007/978-3-0348-7976-7)]

- [Related·E] (*PDCAT'04*) **Architecture of Agent-Based Healthcare Intelligent Assistant on Grid Environment**
  [[📝 Paper](https://doi.org/10.1007/978-3-540-30501-9_15)]

- [Related·E] (*TELECARE'04*) **Aingeru: an Innovating System for Tele Assistance of Elderly People**
  [[📝 Paper](https://doi.org/10.5220/0002681100270036)]

- [Related·E] (*Appl. Intell.'04*) **UCTx: A Multi-Agent System to Assist a Transplant Coordination Unit**
  [[📝 Paper](https://doi.org/10.1023/B:APIN.0000011142.91514.57)]

- [Related·E] (*ISMIS'05*) **An Intelligent System for Assisting Elderly People**
  [[📝 Paper](https://doi.org/10.1007/11425274_48)]

- [Related·E] (*AI Commun.'05*) **Integration of hospital data using agent technologies: A case study**
  [[📝 Paper](https://content.iospress.com/articles/ai-communications/aic342)]

- [Related·E] (*AI Commun.'05*) **Agent-based ambient intelligence for healthcare**
  [[📝 Paper](https://content.iospress.com/articles/ai-communications/aic344)]

- [Related·E] (*SGAI'05*) **Web-based Medical Teaching using a Multi-Agent System**
  [[📝 Paper](https://doi.org/10.1007/1-84628-224-1_14)]

- [Related·E] (*IEEE Trans. IT Biomed.'05*) **A multiagent system enhancing home-care health services for chronic disease management**
  [[📝 Paper](https://doi.org/10.1109/TITB.2005.847511)]

- [Related·E] (*IEEE Intell. Syst.'06*) **Secure integration of distributed medical data using mobile agents**
  [[📝 Paper](https://doi.org/10.1109/MIS.2006.120)]

- [Related·E] (*IEEE Intell. Syst.'06*) **Privacy-aware autonomous agents for pervasive healthcare**
  [[📝 Paper](https://doi.org/10.1109/MIS.2006.118)]

- [Related·E] (*IEEE Intell. Syst.'06*) **Increasing Human-Organ Transplant Availability: Argumentation-Based Agent Deliberation**
  [[📝 Paper](https://doi.org/10.1109/MIS.2006.116)]

- [Related·E] (*Stud. Comput. Intell.'07*) **Assistive Wheelchair Navigation: A Cognitive View**
  [[📝 Paper](https://doi.org/10.1007/978-3-540-47527-9_7)]

- [Related·E] (*CEEMAS'07*) **HeCaSe2: A Multi-agent Ontology-Driven Guideline Enactment Engine**
  [[📝 Paper](https://doi.org/10.1007/978-3-540-75254-7_38)]

- [Related·E] (*KES-AMSTA'07*) **Mobile Agents Using Data Mining for Diagnosis Support in Ubiquitous Healthcare**
  [[📝 Paper](https://doi.org/10.1007/978-3-540-72830-6_83)]

- [Related·E] (*AIME'07*) **Adaptive Optimization of Hospital Resource Calendars**
  [[📝 Paper](https://doi.org/10.1007/978-3-540-73599-1_41)]

- [Related·E] (*Int. J. Med. Inf.'07*) **Towards patient-related information needs**
  [[📝 Paper](https://doi.org/10.1016/j.ijmedinf.2006.11.006)]

- [Related·E] (*Artificial Intelligence in Medicine'08*) **A cognitive architecture for robot self-consciousness**
  [[📝 Paper](https://doi.org/10.1016/j.artmed.2008.07.004)]

- [Related·E] (*Int. J. Med. Inf.'08*) **Computer-based execution of clinical guidelines: A review**
  [[📝 Paper](https://doi.org/10.1016/j.ijmedinf.2008.05.010)]

- [Related·E] (*IEEE Intell. Syst.'08*) **GerAmI: Improving Healthcare Delivery in Geriatric Residences**
  [[📝 Paper](https://doi.org/10.1109/MIS.2008.27)]

- [Related·E] (*Birkhäuser'08*) **Agent Technology and e-Health**
  [[📝 Book](https://link.springer.com/book/10.1007/978-3-7643-8547-7)]

- [Related·E] (*AAMAS Industry'08*) **Agent-based patient admission scheduling in hospitals**
  [[📝 Paper](https://dl.acm.org/citation.cfm?id=1402804)]

### Sistemas de atención sanitaria basados en agentes (2009–2014)

> **Sistemas de agentes de software / multiagent** para la prestación atención, integración de TI sanitaria, telemedicina, AAL o apoyo a la decisión clínica, con **primera publicación entre 2009 y 2014**.  
> **Excluidos** de este bloque (según la curaduría del repositorio): ABM epidémicas/biológicas y papers fronterizos solo de plataforma; véase **Alcance de la curaduría** en [Contribuir](#-contributing).

#### 2014

- [Related·E] (*IJAIT'14*) **A multi-agent care system to support independent living**
  [[📝 Paper](https://doi.org/10.1142/S0218213014400016)]

- [Related·E] (*J. Intell. Inf. Syst.'14*) **OBCAS: an agent-based system and ontology for mobile context aware interactions**
  [[📝 Paper](https://doi.org/10.1007/s10844-014-0305-8)]

- [Related·E] (*IJAIT'14*) **Abductive agents for human activity monitoring**
  [[📝 Paper](https://doi.org/10.1142/S0218213014400028)]

- [Related·E] (*IJAIT'14*) **Agent-based reasoning in medical planning and diagnosis combining multiple strategies**
  [[📝 Paper](https://doi.org/10.1142/S0218213014400041)]

- [Related·E] (*IJAIT'14*) **Towards a simulator of integrated long-term care systems for elderly people**
  [[📝 Paper](https://doi.org/10.1142/S0218213014400053)]

- [Related·E] (*J. Med. Syst.'14*) **Designing an architectural style for dynamic medical cross-organizational workflow management system: an approach based on agents and web services**
  [[📝 Paper](https://doi.org/10.1007/s10916-014-0032-2)]

- [Related·E] (*ISCON'14*) **Architectural design of a multi agent enterprise knowledge management system (MAEKMS) for e-health**
  [[📝 Paper](https://doi.org/10.1109/iciscon.2014.6965225)]

- [Related·E] (*Int. J. Environ. Res. Public Health'14*) **The next generation of interoperability agents in healthcare**
  [[📝 Paper](https://doi.org/10.3390/ijerph110505349)]

- [Related·E] (*Procedia Technol.'14*) **Healthcare interoperability through intelligent agent technology**
  [[📝 Paper](https://doi.org/10.1016/j.protcy.2014.10.150)]

- [Related·E] (*PAAMS'14*) **Assessment of agent architectures for telehealth**
  [[📝 Paper](https://doi.org/10.1007/978-3-319-07767-3_8)]

- [Related·E] (*IJMLC'14*) **Multi-agent decision-making support model for the management of pre-hospital emergency services**
  [[📝 Paper](https://doi.org/10.7763/ijmlc.2014.v4.412)]

- [Related·E] (*Stud. Comput. Intell.'14*) **Negotiation-based patient scheduling in hospitals — reengineering message-based interactions with services**
  [[📝 Paper](https://doi.org/10.1007/978-3-319-00467-9_10)]

- [Related·E] (*Int. J. Simul. Process Model.'14*) **Evaluating policies using agent-based simulations: investigating policies for continuity of
