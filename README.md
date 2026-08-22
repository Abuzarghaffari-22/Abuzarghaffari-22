<a name="top"></a>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:000000,35:0D1117,100:1A1A2E&height=195&section=header&text=Abuzar%20Ghaffari&fontSize=42&fontColor=D4AF37&fontAlignY=34&desc=AI%20Engineer%20%7C%20Computer%20Vision%2C%20Generative%20AI%2C%20Agentic%20Systems&descAlignY=52&descSize=14&descColor=00E5FF&animation=fadeIn">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:FDFBF7,35:F3EFE4,100:EAE0C8&height=195&section=header&text=Abuzar%20Ghaffari&fontSize=42&fontColor=0A2540&fontAlignY=34&desc=AI%20Engineer%20%7C%20Computer%20Vision%2C%20Generative%20AI%2C%20Agentic%20Systems&descAlignY=52&descSize=14&descColor=6C2BD9&animation=fadeIn">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FDFBF7,35:F3EFE4,100:EAE0C8&height=195&section=header&text=Abuzar%20Ghaffari&fontSize=42&fontColor=0A2540&fontAlignY=34&desc=AI%20Engineer%20%7C%20Computer%20Vision%2C%20Generative%20AI%2C%20Agentic%20Systems&descAlignY=52&descSize=14&descColor=6C2BD9&animation=fadeIn" alt="Abuzar Ghaffari — AI Engineer header banner" />
</picture>

<sub><i>Adapts automatically between light &amp; dark — switch under <b>GitHub Settings → Appearance</b>.</i></sub>

<br/><br/>

**[About](#about)** &nbsp;·&nbsp; **[Expertise](#core-expertise)** &nbsp;·&nbsp; **[Stack](#technology-stack)** &nbsp;·&nbsp; **[Projects](#featured-projects)** &nbsp;·&nbsp; **[Approach](#engineering-approach)** &nbsp;·&nbsp; **[Contact](#contact)**

</div>

<br/>

## About

I design and build machine learning, computer vision, and generative AI systems — then take them past the notebook stage into working software: FastAPI and Node.js backends, real-time data pipelines, and deployable APIs.

My toolset spans PyTorch and YOLO for model work, OpenCV for vision pipelines, and TypeScript/Next.js on the application side, with LLM-based and agentic architectures on the generative side. The throughline stays the same across all of it: models that are evaluated, integrated, and shipped as part of a real system, not isolated experiments.

<br/>

## Core Expertise

- **Computer Vision** — real-time object detection, OCR, and visual perception using YOLO and OpenCV
- **Generative AI & LLMs** — LLM-powered applications, Retrieval-Augmented Generation, and prompt engineering
- **Agentic AI** — AI agents that plan, reason, and execute multi-step tasks
- **Deep Learning** — model design, training, and evaluation with PyTorch
- **Robotics (ROS2)** — YOLO-based perception pipelines for autonomous systems
- **AI Deployment & Backend** — serving models through FastAPI/Node.js with real-time WebSocket streaming

<br/>

---

## Technology Stack

**AI / Machine Learning**
Python · PyTorch · OpenCV · NumPy · Pandas · Scikit-learn · YOLO · OCR

**Generative AI**
LLM Applications · RAG · Prompt Engineering · AI Agents · Agentic AI · Multimodal AI

**Backend**
FastAPI · Node.js · Express.js · REST APIs · WebSockets · Socket.IO

**Frontend**
TypeScript · JavaScript · React · Next.js

**Databases**
MySQL · PostgreSQL · MongoDB

**Robotics**
ROS2 · OpenCV · YOLO-based Perception · Autonomous Systems

**Tools / DevOps**
Git · GitHub · Docker · Linux · VS Code · Google Colab · Roboflow

<br/>

---

## Featured Projects

### AI-Powered ANPR System
*Final Year Project (BSCS)*

Real-time Automatic Number Plate Recognition platform built around Pakistani road and plate conditions.

**Stack:** YOLOv11 · Tesseract OCR · FastAPI · MySQL · Next.js 14 · TailwindCSS · WebSockets · JWT

- Custom-trained YOLOv11 model detects plates from a live webcam or IP camera feed
- Multi-variant OCR voting pipeline improves read accuracy on Pakistani plates
- Fuzzy-matching engine reconciles OCR output against the MySQL vehicle registry — owner, dues, authorization status
- JWT-secured REST API with a WebSocket channel streaming detections to the dashboard in real time
- Next.js admin dashboard with live camera feed, detection logs, vehicle registry, and alerting — dark/light theme built in

**Repository:** [github.com/Abuzarghaffari-22/AI_Powered_ANPR_System](https://github.com/Abuzarghaffari-22/AI_Powered_ANPR_System)

<br/>

### MediCare Clinic — AI Medical Assistant Platform

Full-stack healthcare platform pairing an AI symptom-triage assistant with everyday clinic operations.

**Stack:** React 18 · Vite · TailwindCSS · Node.js · Express · MongoDB · Python · FastAPI · HuggingFace Inference API · JWT

- Conversational AI service classifies patient intent — booking, symptom triage, or general Q&A — and routes accordingly
- Three independent services (React frontend, Express API, Python AI service) composed via Docker Compose
- Full appointment lifecycle for patients — book, view, cancel — with a dedicated oversight dashboard for admins
- JWT authentication with refresh tokens, rate limiting, and input validation across every layer

**Repository:** [github.com/Abuzarghaffari-22/Medical_Website_With_Chatbot](https://github.com/Abuzarghaffari-22/Medical_Website_With_Chatbot)

<br/>

### Bella Cucina — AI Restaurant Chatbot

Full-stack conversational ordering and reservations assistant, built as three independent services communicating over REST and WebSockets.

**Stack:** React 18 · Vite · Zustand · Socket.IO · Node.js · Express · MongoDB · Python · FastAPI · HuggingFace Inference API · JWT

- Real-time chat over Socket.IO — the backend assembles live menu, hours, and policy context into the LLM prompt
- Deterministic REST shortcuts for common questions (menu, hours) bypass the LLM entirely for instant, quota-free replies
- Prompt-injection guard filters off-topic and jailbreak attempts before they ever reach the model
- JWT-protected admin panel for staff to manage reservations and credentials

**Repository:** [github.com/Abuzarghaffari-22/Restaurant_Chatbot](https://github.com/Abuzarghaffari-22/Restaurant_Chatbot)

<br/>

### DoDo Bot

ROS2-based robotic perception system performing real-time multi-class object detection for autonomous navigation and environment awareness.

**Stack:** ROS2 · Python · YOLO11 · OpenCV · Linux

- Real-time detection across six object classes: Person, Chair, Table, Tray, Trolley, Bag
- ROS2 node architecture for sensor and perception integration
- YOLO11-based inference pipeline, built and tested on Linux

**Repository:** Private — architecture and demo available on request

<br/>

### NovaMind

Multimodal AI platform focused on generative AI and intelligent application development.

**Stack:** LLMs · Multimodal AI · Agentic AI · GenAI APIs · Python

- LLM-powered application architecture
- Multimodal AI processing and agentic workflows
- API-driven integration for generative AI features

**Repository:** Private — architecture and demo available on request

<br/>

---

## Engineering Approach

`Data` → `Preprocessing` → `Model Development` → `Training & Evaluation` → `Inference / API` → `Deployment` → `Monitoring`

- Build reproducible systems, not isolated notebooks
- Evaluate models with meaningful, task-appropriate metrics
- Design inference for the target hardware and latency budget
- Separate model logic from application infrastructure
- Favor maintainable APIs and modular architecture over one-off scripts
- Treat deployment and monitoring as part of AI engineering, not an afterthought

<br/>

## Current Focus

- Agentic AI systems and multi-step LLM workflows
- Retrieval-Augmented Generation for domain-specific assistants
- Real-time computer vision inference pipelines
- AI deployment and MLOps practices for production systems
- ROS2-based robotics perception

<br/>

---

## Contact

- **GitHub:** [github.com/Abuzarghaffari-22](https://github.com/Abuzarghaffari-22)
- **LinkedIn:** `[ADD LINKEDIN URL]`
- **Email:** `[ADD EMAIL]`
- **Portfolio:** `[ADD PORTFOLIO URL]`

<br/>

<p align="center"><a href="#top">↑ Back to top</a></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:1A1A2E,50:0D1117,100:000000&height=110&section=footer&animation=fadeIn">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:EAE0C8,50:F3EFE4,100:FDFBF7&height=110&section=footer&animation=fadeIn">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:EAE0C8,50:F3EFE4,100:FDFBF7&height=110&section=footer&animation=fadeIn" alt="" />
</picture>
