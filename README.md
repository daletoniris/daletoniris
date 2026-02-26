# Hi, I'm Daniel 👋

📍 **Puerto Madryn, Chubut, Argentina** | 🛡️ **Hacking y Seguridad de la Información** | 🤖 **Robotics & AI Researcher**

`Python` `TypeScript` `JavaScript` `Go` `TensorFlow` `OpenCV` `PostgreSQL` `Docker` `GCP` `Kafka` `Nginx`

> Deep in building autonomous security systems with AI. After years of research, shipping production-grade WAFs and voice assistants feels like the future is here.

🔒 **tokioia.com** – Autonomous Security Operations Center powered by AI agents.

## Current Projects

* 🛡️ **TokioAI** – The SOC that actually protects you; autonomous WAF with ML threat detection, real-time dashboard, and natural language agent control
* 🤖 **JarvisIA** – First Spanish voice assistant; NLP, IoT control, Raspberry Pi compatible
* 🧠 **WAF Enhanced with AI** – Hybrid system combining Naive Bayes + ChatGPT for autonomous threat detection (academic paper published)
* 🌱 **Plant Pest Detection** – Computer vision system with TensorFlow; real-time detection for 30+ plant species and diseases
* 📱 **Jarvis-V2-Telegram** – Telegram bot integration for voice assistant control
* 🔬 **Research Projects** – Ongoing work in robotics, AI, and cybersecurity applications

## GitHub Activity

![GitHub Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=daletoniris&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&line=4ECDC4&point=4ECDC4)

## What I'm Doing

* **Building autonomous security systems** – Creating AI-powered SOC platforms that deploy, protect, and operate infrastructure automatically
* **Researching AI applications** – Exploring how generative models (GPT-4, Claude, Gemini) can enhance security operations
* **Open source contributions** – Sharing tools and knowledge to foster AI development in Latin America
* **Mentoring** – Teaching programming and ethical hacking to students in Puerto Madryn

## Featured Work

### 🛡️ TokioAI - Autonomous Security Operations Center

**🔒 Private Repository (coming soon)** | [🌐 Website](https://tokioia.com)

Complete SOC-level platform that deploys, protects, and operates your entire security infrastructure through an autonomous AI agent.

**Key Features:**
- **Intelligent WAF** – Nginx-based reverse proxy with 15+ WAF signatures; real-time detection of SQLi, XSS, path traversal, command injection, SSRF, Log4Shell, scanners, WordPress exploits, exposed configs
- **ML Threat Classification** – Real-time processor with machine learning; severity classification (critical, high, medium, low, normal); OWASP Top 10 2021 mapping
- **3-Tier Auto-Blocking** – Immediate blocking on critical WAF matches; episode-based blocking for sustained attack patterns; rate-limit blocking; zero-downtime Nginx blocklist reloads
- **Episode Detection** – Groups related attack events from same IP in configurable time windows; correlates multi-vector attacks (scanning → injection → config probing → exfiltration)
- **One-Command GCP Deployment** – Full WAF + ML + Dashboard deployment on Google Cloud Platform; automatically creates VPC, firewall rules, static IP, Compute Engine VM, Docker containers, SSL certificates, DNS
- **Real-Time Dashboard** – Dark theme, JWT login, live traffic graphs (Chart.js), severity distribution, advanced filters, IP block management, episode viewer with risk scores
- **Autonomous AI Agent** – Natural language commands in any language; context understanding, multi-step operations, intelligent error handling, explicit confirmation for dangerous actions; supports OpenAI GPT-4, Anthropic Claude, Google Gemini with automatic fallback
- **Complete Integrations** – Telegram Bot (full control, real-time alerts, security ACL), Home Assistant + Alexa (voice control of SOC operations), SSH Host Control (remote administration), Router Control (OpenWrt/GL.iNet management), DNS Management (Hostinger API automation)
- **Infrastructure as Code** – Create and destroy complete infrastructure with natural language commands; uses Google Cloud Python SDK (no Terraform or gcloud CLI needed); auto-scaling with Managed Instance Groups; Kafka pipeline handling millions of events per minute

**Tech Stack:** Python 3.11+, FastAPI, Uvicorn, PyJWT, Psycopg2, kafka-python, Paramiko, Google Cloud SDK, Docker, Docker Compose, Nginx, Apache Kafka, Zookeeper, PostgreSQL, Let's Encrypt, GCP Compute Engine, VPC Networking, OpenAI GPT-4, Anthropic Claude, Google Gemini, MCP Protocol, Chart.js

### 🤖 JarvisIA - First Spanish Voice Assistant

[![GitHub Stars](https://img.shields.io/github/stars/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA) [![Forks](https://img.shields.io/github/forks/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA)

The **first Spanish voice assistant** created to foster AI development in Latin America.

- 🎤 Spanish voice recognition using **Wit.ai** and **TensorFlow**
- 🧠 Natural language processing (NLP)
- 🏠 IoT and home automation control
- 📱 **Raspberry Pi** compatible
- 🎯 Fully modular and extensible
- 🔌 **Google Speech API** integration for natural voice

**Impact:** Educational project that has inspired developers across Latin America; open source for learning and experimentation; collaboration with programming and ethical hacking students in Puerto Madryn.

### 🛡️ Web Application Firewall Enhanced with AI

[![GitHub Stars](https://img.shields.io/github/stars/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper) [![Forks](https://img.shields.io/github/forks/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)

Hybrid WAF system that combines **Naive Bayes** with **ChatGPT** for autonomous threat detection.

**Innovation:**
- Combines static classifier (Naive Bayes) with generative model (ChatGPT)
- **Dynamic and autonomous learning** that reduces dependency on the generative model
- **Zero-day attack** detection and emerging vectors
- Continuous retraining based on generative model feedback
- **Published academic paper** on the approach

**Capabilities:** XSS, SQL Injection, Path Traversal, Command Injection, RFI, LDAP Injection, Code Injection detection; real-time classification with OWASP Top 10 mapping; memory system for progressive learning; autonomous operation after initial training.

### 🌱 Plant Pest Detection with TensorFlow

[![GitHub Stars](https://img.shields.io/github/stars/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow?style=flat-square)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow) [![Forks](https://img.shields.io/badge/Forks-7-blue)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow)

Computer vision system for automatic pest detection in edible plants.

- 🔍 Real-time detection with camera
- 📸 Static image analysis
- 🎥 Video processing
- 🤖 Model trained with **MobileNet v1.0_224**
- 📱 **Android** compatible (TensorFlow Lite)
- 🍓 Supports **30+ plant and pest types**

**Application:** Potato, tomato, cherry, orange, corn, grape, apple, peach, blueberry, pepper, strawberry, soybean; disease detection: blight, mosaic, bacterial spots, mold, rot, etc.; practical application in agriculture (AgTech).

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=daletoniris&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&icon_color=4ECDC4&text_color=9f9f9f&hide_title=false&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=daletoniris&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&text_color=9f9f9f&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.demolab.com/?user=daletoniris&theme=radical&hide_border=true&background=0D1117&ring=4ECDC4&fire=4ECDC4&currStreakLabel=4ECDC4)

## Recognition

* 🥇 **First Spanish voice assistant** (JarvisIA) – Pioneer project in Latin America
* 📄 **Published academic paper** – WAF enhanced with AI and generative models
* 🌍 **Fostering AI development in Latin America** – Open source and education
* 👨‍🏫 **Mentor** – Programming and ethical hacking students in Puerto Madryn
* 🛡️ **TokioAI** – Complete SOC-level platform with autonomous AI agent
* 🤝 **Active collaborator** – @initiasur, @NiperiaLab, Tokio AI Security Research, Inc

## Publications

* **Web Application Firewall (WAF) Enhanced with AI through Autonomous Dynamic Learning and Generative Models**
  - Combines Naive Bayes with ChatGPT for threat detection
  - Autonomous and dynamic learning system
  - Progressive reduction of dependency on generative model
  - [View Paper](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)

## Philosophy

> "El bit defectuoso del fin del mundo..." 🌎

I build security systems and AI tools to solve real problems, then share them with the world. Currently exploring how AI changes everything about security operations and autonomous systems.

## Connect

[Website](https://tokioia.com) • [GitHub](https://github.com/daletoniris) • [LinkedIn](https://linkedin.com/in/daniel-dieser) • [Twitter](https://twitter.com/daletoniris) • [Email](mailto:admin.airesiliencehub+tokio@protonmail.com)

---

<div align="center">

**Building the future with AI and security** 🚀

[⭐ Star my repos](https://github.com/daletoniris) if you like my work

![Visitor Count](https://profile-counter.glitch.me/daletoniris/count.svg)

</div>
