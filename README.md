# Giocrisrai Godoy Bonillo

**English** · [Español](README.es.md)

**AI Engineer** · LLM Agents in Production · LLM Security & Red Teaming · Puerto Montt, Chile (UTC-3/-4) · Remote worldwide

I build, ship and **operate** LLM systems in production: agents, RAG and multi-model pipelines with real users. I also audit them — security assessments of LLM agents mapped to the OWASP Top 10 for LLM Applications.

[![Portfolio](https://img.shields.io/badge/Portfolio-giocrisrai.com-0a6a79?style=flat-square)](https://giocrisrai.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Giocrisrai-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/giocrisrai)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Giocrisrai-FF6C00?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/giocrisrai)
[![Email](https://img.shields.io/badge/Email-contact@giocrisrai.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@giocrisrai.com)

---

AI engineer with a Mechatronics Engineering background, an MSc in Artificial Intelligence and an MSc in Mathematical Engineering & Computation (thesis defended, 2026). 10+ years of engineering across manufacturing, mining, environmental consulting and education. Currently professor and applied researcher at Duoc UC, and Data Engineer at MTsolutions (IIoT for manufacturing).

What I care about: **I don't only test AI systems, I keep them running — with real users and real incidents.**

Open to senior AI Engineer, LLM Engineer and AI Security roles, and to consulting engagements. English and Spanish.

---

## What I work on

| | |
|---|---|
| **LLM security & assurance** | Audits of conversational agents mapped to the OWASP Top 10 for LLM Applications and NIST AI RMF: prompt injection, system-prompt leakage, excessive agency, unbounded consumption. → [`agent-assurance`](https://github.com/Giocrisrai/agent-assurance) |
| **Generative AI in production** | An AI grading platform with human-in-the-loop, developed with Duoc UC on Azure. Conversational clinical triage (web + WhatsApp). Generative video with Veo 3.1. |
| **Agentic software development** | I work daily with AI coding agents (Claude Code CLI, subagents, MCP tools), backed by automated tests and code review. I also teach it: [`taller-ia-agentes-biblioteca`](https://github.com/Giocrisrai/taller-ia-agentes-biblioteca). |
| **Computer vision & robotics** | 6-DoF pose estimation with Transformers (FoundationPose) and Diffusion Models on BOP benchmarks. Autonomous Duckiebot: YOLO26 → TensorRT on a Jetson Nano (mAP50 0.937). |
| **AI for regulated industries** | Predictive environmental models for aquaculture (oceanographic time series, CROCO-OCEAN model) and industrial predictive maintenance. |
| **Data engineering & MLOps** | Kedro, Airflow, Docker, FastAPI, CI/CD, observability. Reproducible systems from prototype to production. |

---

## Featured projects

### [agent-assurance](https://github.com/Giocrisrai/agent-assurance) — Security testing for LLM agents
Methodology and test harness for assessing the security of LLM agents and applications in production, distilled from real audits. Mapped to the OWASP LLM Top 10. Five probes, a CLI, a client-ready report, CI on Python 3.11–3.13, on PyPI as [`llm-agent-assurance`](https://pypi.org/project/llm-agent-assurance/). **[See a sample report →](https://giocrisrai.github.io/agent-assurance/)**

`OWASP LLM` `Red Teaming` `Prompt Injection` `Python` `Security`

### [pose6dof-transformers-diffusion](https://github.com/Giocrisrai/pose6dof-transformers-diffusion) — 6-DoF pose estimation
MSc thesis (UNIR, 2026). End-to-end pipeline: FoundationPose (Transformers, CVPR 2024) vs GDR-Net++ on BOP benchmarks, with Diffusion Policy for multi-modal grasp trajectory generation. 293 tests, bootstrap 95% confidence intervals, and a package on PyPI ([`bop-bootstrap-ci`](https://pypi.org/project/bop-bootstrap-ci/)). **[Live results dashboard →](https://giocrisrai.github.io/pose6dof-transformers-diffusion/)**

`Transformers` `Diffusion Models` `PyTorch` `SE(3) Lie Groups` `BOP Benchmark` `ROS 2`

### krinoInsight — AI grading platform (applied research with Duoc UC)
A platform that helps instructors grade student work against course rubrics. No feedback reaches a student without the instructor's approval. An institutional applied-research project with Duoc UC, where I am lead engineer. *Code and internal details are private.*

`LLMs` `Human-in-the-loop` `Azure` `EdTech`

### [Duckietown DB21-J4](https://github.com/Giocrisrai/duckietown-db21j4-autonomy) — Modernized autonomy stack
YOLO26 detection trained off-robot and deployed with TensorRT on an end-of-life Jetson Nano (mAP50 0.937), classical-vision lane following, A*/BFS planning, a Gymnasium + PPO environment. 397 tests and simulation without the robot.

`YOLO` `TensorRT` `ROS` `Jetson` `RL`

### [AI Code Reviewer](https://github.com/Giocrisrai/teaching_assistant_in_code_review) — Rubric-based grading of student code
A web app that grades student code against a rubric with Google Gemini and returns per-criterion scores, feedback and a final grade, exportable to PDF. React 19 + TypeScript, 24 tests, CI. **[Live demo →](https://giocrisrai.github.io/teaching_assistant_in_code_review/)**

`React` `TypeScript` `Gemini` `EdTech` `Vitest`

### [guitar-practice-trainer](https://github.com/Giocrisrai/guitar-practice-trainer) — Real-time audio for guitar practice
Free software to practice guitar on macOS with the Rocksmith Real Tone cable: real-time pitch detection, a tuner and fretboard monitor, exercises graded on note, intonation and tempo, and a play-along lane for full pieces. Python audio core + React 19, 1,500+ tests.

`DSP` `Pitch Detection` `Python` `FastAPI` `React`

### [chatpdfgio](https://github.com/Giocrisrai/chatpdfgio) — Full-stack RAG
Chat with PDFs, Word files, slides and audio. Answers are grounded on the retrieved passages and cite their source pages. FastAPI + OpenAI + Pinecone + Streamlit, with a local backend that runs offline, 34 tests and CI. **[Try the in-browser retrieval demo →](https://giocrisrai.github.io/chatpdfgio/)**

`RAG` `FastAPI` `OpenAI` `Pinecone` `Docker`

---

## Open teaching

I publish my Duoc UC course material as repositories that students run in Colab or Docker (in Spanish):
[Machine Learning](https://github.com/Giocrisrai/mly1101-machine-learning) · [Reinforcement Learning](https://github.com/Giocrisrai/aprendizaje-refuerzo-duoc) · [Big Data](https://github.com/Giocrisrai/proyecto-big-data) · [AI agents workshop](https://github.com/Giocrisrai/taller-ia-agentes-biblioteca) · [Blockchain](https://github.com/Giocrisrai/blockchain-cripto-lab).
Mentor and template author for the [Applied AI Hackathon at Congreso Social UC 2026](https://github.com/Giocrisrai/hackathon-ia-congreso-social-2026-desafio2).

---

## Stack

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kedro](https://img.shields.io/badge/Kedro-43C0F6?style=flat-square&logo=kedro&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FF6C00?style=flat-square&logo=huggingface&logoColor=white)
