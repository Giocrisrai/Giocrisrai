# Giocrisrai Godoy Bonillo

[English](README.md) · **Español**

**AI Engineer** · LLM Security & Assurance · Puerto Montt, Chile

Ingeniería de IA para **sistemas en producción** — no prototipos, no demos.
Verificación y seguridad de agentes LLM, visión por computador para robótica, y modelos predictivos para industrias reguladas.

[![Portfolio](https://img.shields.io/badge/Portfolio-giocrisrai.com-0a6a79?style=flat-square)](https://giocrisrai.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Giocrisrai-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/giocrisrai)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Giocrisrai-FF6C00?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/giocrisrai)
[![Email](https://img.shields.io/badge/Email-contact@giocrisrai.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@giocrisrai.com)

---

Ingeniero de IA con formación en Mecatrónica, Magíster en Inteligencia Artificial y Magíster en Ingeniería Matemática y Computación (tesis defendida, 2026). Construyo y **opero** sistemas de IA en producción: una plataforma de evaluación con LLM que corre en Azure, desarrollada como investigación aplicada con Duoc UC, auditorías de seguridad de agentes conversacionales para empresas chilenas, robótica autónoma en el borde (Jetson + TensorRT) y estimación de pose 6-DoF con Transformers. Hoy soy profesor e investigador en Duoc UC e ingeniero de datos en MTsolutions (IIoT para manufactura).

La diferencia que me importa: **no solo pruebo sistemas de IA, los mantengo corriendo con SLA, incidentes reales y usuarios de verdad.**

---

## En qué trabajo

| | |
|---|---|
| **AI Assurance & Seguridad de LLM** | Auditoría de agentes conversacionales mapeada a OWASP Top 10 for LLM Applications y NIST AI RMF: prompt injection, fuga de system prompt, agencia excesiva, consumo no acotado. → [`agent-assurance`](https://github.com/Giocrisrai/agent-assurance) |
| **IA generativa en producción** | Plataforma de corrección con IA y human-in-the-loop, desarrollada con Duoc UC sobre Azure. Triage clínico conversacional (web + WhatsApp). Video generativo con Veo 3.1. |
| **Computer Vision & Robótica** | Estimación de pose 6-DoF con Transformers (FoundationPose) y Diffusion Models sobre benchmarks BOP. Duckiebot autónomo: YOLO26 → TensorRT en Jetson Nano (mAP50 0.937). |
| **IA para industrias reguladas** | Modelos predictivos ambientales para acuicultura (series temporales oceanográficas, modelo CROCO-OCEAN), mantenimiento predictivo industrial. |
| **Desarrollo con agentes de IA** | Trabajo a diario con agentes de programación (Claude Code CLI, subagentes, herramientas MCP), respaldado por tests automatizados y revisión de código. También enseño a usarlos: [`taller-ia-agentes-biblioteca`](https://github.com/Giocrisrai/taller-ia-agentes-biblioteca). |
| **Data Engineering & MLOps** | Kedro, Airflow, Docker, FastAPI, CI/CD, observabilidad. Sistemas reproducibles de prototipo a producción. |

---

## Proyectos destacados

### [agent-assurance](https://github.com/Giocrisrai/agent-assurance) — Seguridad de agentes LLM
Metodología y arnés de pruebas para evaluar la seguridad de agentes y aplicaciones LLM en producción, destilado de auditorías reales. Mapeado a OWASP LLM Top 10. 5 sondas, CLI, informe listo para cliente, CI en Python 3.11–3.13. **[Ver un informe de ejemplo →](https://giocrisrai.github.io/agent-assurance/)**

`OWASP LLM` `Red Teaming` `Prompt Injection` `Python` `Security`

### [pose6dof-transformers-diffusion](https://github.com/Giocrisrai/pose6dof-transformers-diffusion) — Estimación de Pose 6-DoF
Tesis de Máster (UNIR 2026). Pipeline end-to-end: FoundationPose (Transformers, CVPR 2024) vs GDR-Net++ en benchmarks BOP, con Diffusion Policy para generación multi-modal de trayectorias de agarre. 293 tests, bootstrap CI 95%, paquete publicado en PyPI ([`bop-bootstrap-ci`](https://pypi.org/project/bop-bootstrap-ci/)). **[Dashboard de resultados en vivo →](https://giocrisrai.github.io/pose6dof-transformers-diffusion/)**

`Transformers` `Diffusion Models` `PyTorch` `SE(3) Lie Groups` `BOP Benchmark` `ROS 2`

### krinoInsight — Plataforma de corrección con IA (investigación aplicada con Duoc UC)
Plataforma que apoya a los docentes en la corrección de entregas con rúbricas por asignatura. Ningún feedback llega al estudiante sin el visto bueno del docente. Proyecto institucional de investigación aplicada con Duoc UC, donde soy ingeniero principal. *Código y detalles internos privados.*

`LLMs` `Human-in-the-loop` `Azure` `EdTech`

### [Duckietown DB21-J4](https://github.com/Giocrisrai/duckietown-db21j4-autonomy) — Stack de autonomía modernizado
Detección YOLO26 entrenada fuera del robot y desplegada con TensorRT en una Jetson Nano EOL (mAP50 0.937), seguimiento de carril por visión clásica, planificación A*/BFS, entorno Gymnasium + PPO. 393 tests y simulación sin robot.

`YOLO` `TensorRT` `ROS` `Jetson` `RL`

### [Revisor de código con IA](https://github.com/Giocrisrai/teaching_assistant_in_code_review) — Corrección de código con rúbrica
Aplicación web que evalúa código de estudiantes contra una rúbrica con Google Gemini y entrega puntaje por criterio, retroalimentación y nota final, exportable a PDF. React 19 + TypeScript, 24 pruebas, CI. **[Demo en vivo →](https://giocrisrai.github.io/teaching_assistant_in_code_review/)**

`React` `TypeScript` `Gemini` `EdTech` `Vitest`

### [guitar-practice-trainer](https://github.com/Giocrisrai/guitar-practice-trainer) — Audio en tiempo real para practicar guitarra
Software libre para practicar guitarra en macOS con el cable Rocksmith Real Tone: detección de notas en tiempo real, afinador y monitor del mástil, ejercicios corregidos en nota, afinación y tempo, y un carril para tocar piezas completas. Núcleo de audio en Python + React 19, más de 1.500 pruebas.

`DSP` `Detección de tono` `Python` `FastAPI` `React`

### [chatpdfgio](https://github.com/Giocrisrai/chatpdfgio) — RAG full-stack
Chatbot para conversar con documentos PDF. FastAPI + LangChain + Streamlit, contenerizado con Docker. **[Probar la demo de búsqueda en el navegador →](https://giocrisrai.github.io/chatpdfgio/)**

`RAG` `FastAPI` `LangChain` `Docker`

---

## Docencia abierta

Publico el material de mis asignaturas en Duoc UC como repositorios que los estudiantes ejecutan en Colab o Docker:
[Machine Learning](https://github.com/Giocrisrai/mly1101-machine-learning) · [Aprendizaje por refuerzo](https://github.com/Giocrisrai/aprendizaje-refuerzo-duoc) · [Big Data](https://github.com/Giocrisrai/proyecto-big-data) · [Taller de agentes de IA](https://github.com/Giocrisrai/taller-ia-agentes-biblioteca) · [Blockchain](https://github.com/Giocrisrai/blockchain-cripto-lab).
Mentor y autor de las plantillas de la [Hackathon IA Aplicada del Congreso Social UC 2026](https://github.com/Giocrisrai/hackathon-ia-congreso-social-2026-desafio2).

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

---

> *Construyo sistemas de IA de nivel producción — no prototipos, no demos. Sistemas reales que resuelven problemas reales.*
