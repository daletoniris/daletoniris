<div align="center">

### 🔬 Robotics Research & Information Security | 🛡️ Hacking y Seguridad de la Información

**📍 Puerto Madryn, Chubut, Argentina**  
**🏢 Tokio AI Security Research, Inc**

[![GitHub](https://img.shields.io/badge/GitHub-daletoniris-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daletoniris)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-dieser)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/daletoniris)
[![Website](https://img.shields.io/badge/Website-TokioAI-4ECDC4?style=for-the-badge)](https://tokioia.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daletoniris@gmail.com)

</div>

---

## 🚀 Sobre Mí

Soy un **investigador independiente de robótica e inteligencia artificial** con pasión por el **hacking y la seguridad de la información** y el desarrollo de tecnologías innovadoras. Mi trabajo se centra en crear soluciones que tengan un impacto real, especialmente en **Latinoamérica**.

> *"El bit defectuoso del fin del mundo..."* 🌎

He desarrollado sistemas completos de seguridad, asistentes de voz, y plataformas de IA que combinan investigación académica con aplicaciones prácticas del mundo real.

---

## 🛡️ TokioAI - Autonomous Security Operations Center

**🔒 Repositorio Privado (próximamente público)** | [🌐 Sitio Web](https://tokioia.com)

Plataforma completa de nivel SOC que despliega, protege y opera toda tu infraestructura de seguridad mediante un agente de IA autónomo.

### 🎯 Características Principales

**Intelligent WAF (Web Application Firewall)**
- Proxy reverso basado en Nginx con **15+ firmas WAF**
- Detección en tiempo real de: SQL Injection, XSS (reflejado/almacenado), path traversal, command injection, SSRF, Log4Shell, scanners (Nikto, sqlmap, Nmap), exploits de WordPress, configuraciones expuestas (.env, .git)
- Inspección de cada petición HTTP en tiempo real

**ML Threat Classification (OWASP Top 10)**
- Procesador en tiempo real con **machine learning**
- Clasificación por severidad (critical, high, medium, low, normal)
- Mapeo a categorías **OWASP Top 10 2021**: A01 (Broken Access Control), A03 (Injection), A05 (Security Misconfiguration), A06 (Vulnerable Components), A07 (Auth Failures), A10 (SSRF)
- Minimización de falsos positivos con exclusiones inteligentes de paths

**3-Tier Auto-Blocking Engine**
- Bloqueo inmediato en coincidencias críticas de firmas WAF (SQLi, RCE)
- Bloqueo basado en episodios cuando se detectan patrones de ataque sostenidos
- Bloqueo por rate-limit cuando se exceden umbrales de volumen
- Bloqueos escritos en blocklist de Nginx con recarga automática (**zero downtime**)

**Episode Detection & Attack Correlation**
- Agrupa eventos de ataque relacionados de la misma IP en ventanas de tiempo configurables
- Correlaciona ataques multi-vector (scanning → injection → config probing → exfiltration)
- Escalación automática de severidad basada en conteo y tipos de eventos

**One-Command GCP Deployment**
- Despliegue completo de WAF + ML + Dashboard en **Google Cloud Platform** con un solo comando
- Crea automáticamente: VPC network + subnet, firewall rules, static IP, Compute Engine VM, contenedores Docker (Nginx, Kafka, Zookeeper, PostgreSQL, ML Processor, Dashboard API, Blocklist Sync), certificados SSL vía Let's Encrypt con auto-renovación, y configuración DNS

**Real-Time Security Dashboard**
- Dashboard con tema oscuro, login JWT, gráficos de tráfico en vivo (Chart.js)
- Distribución de severidad, tabla de tráfico reciente con filtros avanzados
- Gestión de IPs bloqueadas (bloquear/desbloquear desde UI)
- Visor de episodios con risk scores
- Filtros por IP, patrón de URL, y rango de fecha/hora

**Autonomous AI Agent (Natural Language)**
- Agente de IA (tokio-cli) que acepta comandos en lenguaje natural en cualquier idioma
- Entiende contexto, ejecuta herramientas, encadena operaciones multi-paso
- Maneja errores y reintentos inteligentemente
- Requiere confirmación explícita para acciones peligrosas
- Soporta **OpenAI (GPT-4), Anthropic (Claude), y Google Gemini** con fallback automático

**Integraciones Completas**
- **Telegram Bot**: Control completo desde Telegram, alertas en tiempo real, ACL de seguridad
- **Home Assistant + Alexa**: Control por voz de operaciones SOC vía Alexa Media Player
- **SSH Host Control**: Administración remota completa vía SSH (cron, scripts, systemctl, logs, paquetes)
- **Router Control**: Gestión de routers OpenWrt/GL.iNet (firewall, DNS, DHCP, VPN, clientes)
- **DNS Management**: Gestión automatizada de DNS vía API de Hostinger

**Infrastructure as Code**
- Crea y destruye infraestructura completa con comandos en lenguaje natural
- Usa **Google Cloud Python SDK** (sin necesidad de Terraform o gcloud CLI)
- Auto-scaling con Managed Instance Groups (MIG)
- Pipeline de **Kafka** que maneja millones de eventos por minuto

**Stack Tecnológico Completo**
- **Backend**: Python 3.11+, FastAPI, Uvicorn, PyJWT, Psycopg2, kafka-python, Paramiko, Google Cloud SDK
- **Infrastructure**: Docker, Docker Compose, Nginx, Apache Kafka, Zookeeper, PostgreSQL, Let's Encrypt
- **Cloud**: Google Cloud Platform, Compute Engine, VPC Networking, Managed Instance Groups
- **AI/LLM**: OpenAI GPT-4, Anthropic Claude, Google Gemini, MCP Protocol
- **Frontend**: Chart.js, Vanilla JS, CSS3 Animations, Dark Theme

---

## 🤖 JarvisIA - Primer Asistente de Voz en Español

[![GitHub](https://img.shields.io/github/stars/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA) [![Forks](https://img.shields.io/github/forks/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA)

El **primer asistente de voz en español** creado para fomentar el desarrollo de IA en Latinoamérica.

**Características:**
- 🎤 Reconocimiento de voz en español usando **Wit.ai** y **TensorFlow**
- 🧠 Procesamiento de lenguaje natural (NLP)
- 🏠 Control de dispositivos IoT y domótica
- 📱 Compatible con **Raspberry Pi**
- 🎯 Totalmente modular y extensible
- 🔌 Integración con **Google Speech API** para voz natural

**Impacto:**
- Proyecto educativo que ha inspirado a desarrolladores en toda Latinoamérica
- Código abierto para aprendizaje y experimentación
- Colaboración con estudiantes de programación y hacking en Puerto Madryn

---

## 🛡️ Web Application Firewall Enhanced with AI

[![GitHub](https://img.shields.io/github/stars/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper) [![Forks](https://img.shields.io/github/forks/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)

Sistema híbrido de WAF que combina **Naive Bayes** con **ChatGPT** para detección autónoma de amenazas.

**Innovación:**
- Combina clasificador estático (Naive Bayes) con modelo generativo (ChatGPT)
- **Aprendizaje dinámico y autónomo** que reduce dependencia del modelo generativo
- Detección de ataques **zero-day** y vectores emergentes
- Retrenamiento continuo basado en feedback del modelo generativo
- **Paper académico publicado** sobre el enfoque

**Capacidades:**
- Detección de XSS, SQL Injection, Path Traversal, Command Injection, RFI, LDAP Injection, Code Injection
- Clasificación en tiempo real con mapeo a OWASP Top 10
- Sistema de memoria para aprendizaje progresivo
- Operación autónoma después del entrenamiento inicial

---

## 🌱 Detección de Plagas en Plantas con TensorFlow

[![GitHub](https://img.shields.io/github/stars/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow?style=flat-square)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow) [![Forks](https://img.shields.io/badge/Forks-7-blue)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow)

Sistema de visión por computadora para detección automática de plagas en plantas comestibles.

**Características:**
- 🔍 Detección en tiempo real con cámara
- 📸 Análisis de imágenes estáticas
- 🎥 Procesamiento de video
- 🤖 Modelo entrenado con **MobileNet v1.0_224**
- 📱 Compatible con **Android** (TensorFlow Lite)
- 🍓 Soporta **30+ tipos de plantas y plagas**

**Aplicación:**
- Papa, tomate, cereza, naranjo, maíz, uva, manzana, durazno, arándano, pimiento, fresa, soja
- Detección de enfermedades: tizón, mosaico, manchas bacterianas, moho, podredumbre, etc.
- Aplicación práctica en agricultura (AgTech)

---

## 💻 Stack Tecnológico Completo

<div align="center">

### Lenguajes y Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### IA y Machine Learning
![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-FF6B35?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

### Seguridad y DevOps
![WAF](https://img.shields.io/badge/WAF-FF6B6B?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Integraciones
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)
![Alexa](https://img.shields.io/badge/Alexa-00CAFF?style=for-the-badge&logo=amazon-alexa&logoColor=white)

</div>

---

## 🎯 Habilidades Técnicas Detalladas

### Seguridad y Ciberseguridad
- **WAF Development**: Desarrollo de Web Application Firewalls con detección de firmas, ML, y modelos generativos
- **Threat Detection**: Detección de amenazas OWASP Top 10, zero-day attacks, y análisis de comportamiento
- **Auto-Mitigation**: Sistemas de bloqueo automático multi-capa con correlación de episodios
- **Security Operations**: Operaciones de seguridad automatizadas, respuesta a incidentes, y análisis forense
- **Penetration Testing**: Testing de vulnerabilidades, análisis de seguridad, y hacking ético
- **Network Security**: Configuración de firewalls, routers, VPN, y seguridad perimetral

### Machine Learning e IA
- **NLP**: Procesamiento de lenguaje natural para asistentes de voz y comandos en lenguaje natural
- **Computer Vision**: Visión por computadora para detección de plagas, object detection (YOLO, SSD, Faster R-CNN)
- **ML Classification**: Clasificación de amenazas con Naive Bayes, modelos generativos (ChatGPT), y aprendizaje autónomo
- **Deep Learning**: TensorFlow, PyTorch, MobileNet para modelos optimizados para móviles
- **LLM Integration**: Integración con GPT-4, Claude, Gemini para análisis y automatización

### Infraestructura y DevOps
- **Cloud Architecture**: Diseño e implementación en GCP (Compute Engine, VPC, Managed Instance Groups)
- **Containerization**: Docker, Docker Compose, orquestación de servicios
- **Event Streaming**: Apache Kafka, Zookeeper para pipelines de alto rendimiento
- **Database Design**: PostgreSQL con esquemas multi-tenant, optimización de queries, y análisis de datos
- **Infrastructure as Code**: Automatización completa con Google Cloud Python SDK
- **CI/CD**: Pipelines de despliegue automatizados

### Desarrollo de Software
- **Backend**: Python (FastAPI, Flask), Go, arquitecturas RESTful y APIs
- **Frontend**: JavaScript, Chart.js, dashboards en tiempo real, diseño responsive
- **Integrations**: Telegram Bot API, Home Assistant, Alexa, SSH, APIs de DNS
- **Security**: JWT authentication, ACL, prompt injection guards, manejo seguro de secretos
- **Testing**: Testing de seguridad, validación de vulnerabilidades, pruebas de penetración

---

## 🏆 Logros y Contribuciones

- 🥇 **Primer asistente de voz en español** (JarvisIA) - Proyecto pionero en Latinoamérica
- 📄 **Paper académico publicado** - WAF mejorado con IA y modelos generativos
- 🌍 **Fomento del desarrollo de IA en Latinoamérica** - Código abierto y educación
- 👨‍🏫 **Mentor** - Estudiantes de programación y hacking ético en Puerto Madryn
- 🛡️ **TokioAI** - Plataforma completa de nivel SOC con agente de IA autónomo
- 🤝 **Colaborador activo** - @initiasur, @NiperiaLab, Tokio AI Security Research, Inc

---

## 📝 Publicaciones y Papers

- **Web Application Firewall (WAF) Enhanced with AI through Autonomous Dynamic Learning and Generative Models**
  - Combina Naive Bayes con ChatGPT para detección de amenazas
  - Sistema de aprendizaje autónomo y dinámico
  - Reducción progresiva de dependencia del modelo generativo
  - [Ver Paper](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)

---

## 🌟 Proyectos Destacados

<table>
<tr>
<td width="50%">

### 🛡️ [TokioAI - Autonomous SOC](https://tokioia.com)
**🔒 Repositorio Privado (próximamente público)**

Plataforma completa de nivel SOC con agente de IA autónomo que despliega, protege y opera toda tu infraestructura de seguridad.

- 🤖 Agente de IA con comandos en lenguaje natural
- 🛡️ WAF inteligente con 15+ firmas y ML
- 🧠 Clasificación OWASP Top 10 en tiempo real
- 🔒 Auto-bloqueo de IPs en 3 capas
- 📊 Dashboard en tiempo real
- ☁️ Deploy automático en GCP
- 💬 Integraciones: Telegram, Alexa, Home Assistant

</td>
<td width="50%">

### 🤖 [JarvisIA](https://github.com/daletoniris/JarvisIA)
El **primer asistente de voz en español**.

- 🎤 Reconocimiento de voz en español
- 🧠 Procesamiento de lenguaje natural
- 🏠 Control de dispositivos IoT
- 📱 Compatible con Raspberry Pi

[![Stars](https://img.shields.io/github/stars/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA)
[![Forks](https://img.shields.io/github/forks/daletoniris/JarvisIA?style=flat-square)](https://github.com/daletoniris/JarvisIA)

</td>
</tr>
<tr>
<td width="50%">

### 🛡️ [WAF Enhanced with AI](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)
Sistema híbrido que combina Naive Bayes + ChatGPT.

- 🤖 Aprendizaje dinámico autónomo
- 🔄 Retrenamiento continuo
- ⚡ Detección en tiempo real
- 🎯 Protección zero-day

[![Stars](https://img.shields.io/github/stars/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)
[![Forks](https://img.shields.io/github/forks/daletoniris/Web-Application-Firewall-Purple-AI-Paper?style=flat-square)](https://github.com/daletoniris/Web-Application-Firewall-Purple-AI-Paper)

</td>
<td width="50%">

### 🌱 [Detección de Plagas](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow)
Sistema de visión por computadora con TensorFlow.

- 🔍 Detección en tiempo real
- 📸 Análisis de imágenes y video
- 🤖 Modelo MobileNet optimizado
- 📱 Compatible con Android

[![Stars](https://img.shields.io/github/stars/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow?style=flat-square)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow)
[![Forks](https://img.shields.io/badge/Forks-7-blue)](https://github.com/daletoniris/deteccion-de-plagas-en-plantas-con-tensorflow)

</td>
</tr>
</table>

---

## 📊 Estadísticas de GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=daletoniris&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&icon_color=4ECDC4&text_color=9f9f9f&hide_title=false&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=daletoniris&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&text_color=9f9f9f&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.demolab.com/?user=daletoniris&theme=radical&hide_border=true&background=0D1117&ring=4ECDC4&fire=4ECDC4&currStreakLabel=4ECDC4)

</div>

---

## 🤝 Colaboraciones y Organizaciones

Trabajo con organizaciones como:
- **@initiasur** - Iniciativas de investigación en robótica e IA
- **@NiperiaLab** - Laboratorio de investigación
- **Tokio AI Security Research, Inc** - Investigación en seguridad, robotica, IA y desarrollo de TokioAI

---

## 💬 Contacto

<div align="center">

**¿Tienes un proyecto interesante o quieres colaborar?**

[![Email](https://img.shields.io/badge/Email-me-blue?style=for-the-badge&logo=gmail)](mailto:daletoniris@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Contact-181717?style=for-the-badge&logo=github)](https://github.com/daletoniris)
[![Website](https://img.shields.io/badge/Website-TokioAI-4ECDC4?style=for-the-badge)](https://tokioia.com)

</div>

---

<div align="center">

### 🌍 Puerto Madryn, Chubut, Argentina

**Desarrollando el futuro con IA y seguridad** 🚀

[⭐ Dáme una estrella](https://github.com/daletoniris) si te gustan mis proyectos

![Visitor Count](https://profile-counter.glitch.me/daletoniris/count.svg)

</div>
