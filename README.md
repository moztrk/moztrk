<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=33C4FF&background=00000000&center=true&vCenter=true&width=435&lines=Hello!+I'm+Mustafa+Ozturk;Selam!+Ben+Mustafa+%C3%96zt%C3%BCrk;Software+Engineer;Backend+%26+Applied+AI+%2F+ML;Building+with+LLMs+%26+Kubernetes" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <h3>🧠 Understanding Data, Training Models, Coding Solutions.</h3>
  <p><i>Veriyi Anlama, Modeli Eğitme, Çözümü Kodlama.</i></p>
  <p>Building scalable backend systems on Kubernetes & integrating LLMs and NLP models into production.</p>
</div>

---

<table align="center" style="border: none;">
<tr>
<td align="left" width="55%" valign="top" style="border: none;">

### 👨‍💻 About Me / Hakkımda

**[EN]** Software Engineering graduate. I design systems end to end — from architecture to containerized deployment and autoscaling. I specialize in **backend development (Java/Spring Boot, Python/FastAPI)** and **applied AI/ML**: running local LLMs (vLLM, Ollama), building RAG & retrieval pipelines, and fine-tuning NLP models.

**[TR]** Yazılım Mühendisliği mezunu. Sistemleri uçtan uca tasarlıyorum — mimariden konteyner tabanlı dağıtım ve otomatik ölçeklemeye kadar. **Backend geliştirme (Java/Spring Boot, Python/FastAPI)** ve **uygulamalı yapay zeka** üzerine uzmanlaşıyorum: yerel LLM'ler (vLLM, Ollama), RAG hatları ve NLP model fine-tuning.

- 🔭 **Focus:** **MapRays** (Kubernetes orchestration) & **GIS Data Hub** (local-LLM deep-research agent).
- 🌱 **Learning:** **LLM serving & inference optimization** and **cloud platforms (AWS)**.
- 💼 **Experience:** Long-term SWE Intern @ **Ekinoks Software** (Java 21, Spring Boot, K8s) · Full-Stack Intern @ **Intellium** (ASP.NET Core, React).
- 📫 **Contact:** [moztrk4444@gmail.com](mailto:moztrk4444@gmail.com)

</td>
<td align="center" width="45%" style="border: none;">

### 🛠️ Tech Stack
<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" />
  <br/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/🤗_Transformers-FFD21E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
</div>

</td>
</tr>
</table>

---

### 🚀 Featured Projects / Öne Çıkanlar

#### 🗺️ **[MapRays Analysis Orchestrator](https://github.com/moztrk/maprays-analyzer-java)** — Multi-Tenant Geospatial Analysis Platform
*(Çok Kiracılı Coğrafi Analiz Platformu — Kontrol Düzlemi)*
Runs untrusted user code safely at scale: every job executes in a fully isolated, network-less sandbox pod on Kubernetes.
> *Java control-plane + Python analysis runtime — a polyglot architecture.*

* **Tech:** Java 21 (virtual threads), Spring Boot, Kubernetes (fabric8), Redis queue, KEDA, PostgreSQL.
* **Highlights:**
    * Deny-all `NetworkPolicy`, plan-isolated RBAC & strict CPU/memory/timeout quotas per tier.
    * Queue-depth-based autoscaling with `KEDA` — scale-to-zero for idle tenants.
    * OOM-aware billing: fair metering even when a job exceeds its memory limit.
    * Verified with a 16-scenario end-to-end system test.

#### 🔍 **[GIS Data Hub](https://github.com/moztrk/gisdata)** — Local-LLM Deep-Research Agent
*(Yerel LLM ile Otonom Derin Araştırma Ajanı)*
An offline counterpart to Gemini Deep Research: an autonomous agent that searches the web, scrapes pages (`Playwright`) and verifies findings with local LLMs.

* **Tech:** Python, FastAPI, Streamlit, PostgreSQL, vLLM / Ollama / LM Studio.
* **AI Core:**
    * RAG-like **semantic + keyword search** over PostgreSQL with multilingual `sentence-transformers`.
    * `vLLM` chosen for **PagedAttention** KV-cache management — higher throughput & batch concurrency on limited GPU memory.

#### 🛡️ **[Sentinel Moderation Engine](https://github.com/moztrk/TextClassification)** — Turkish Content Moderation Pipeline
*(Türkçe İçerik Moderasyon Hattı)*

* Fine-tuned **BERTurk** on a curated 42K dataset for Turkish offensive language detection.
* Multi-stage pipeline: blacklist early-exit → BERTurk → Detoxify (EN/multilingual).
* Scaled with batch GPU inference & INT8 dynamic quantization — **sub-50ms latency** on the fast path.

#### 🧠 **[DailyMind](https://github.com/moztrk/Daily)** — AI-Powered Journaling App *(Live)*
*(Yapay Zeka Destekli Günlük Uygulaması — Yayında)*

* **Tech:** Python (FastAPI), React Native (Expo), Supabase, Scikit-learn.
* `BERT` sentiment analysis, `SBERT` hybrid topic modeling, `Random Forest` mood prediction trained on 3,000+ labeled entries.
* Generates personal insights like *"Work topics tend to lower your mood on Mondays."*

<details>
<summary>📦 More projects / Diğer projeler</summary>

#### 📚 LGS English Question Generator (AI-Exam-Gen)
Generative AI project analyzing past exam data to create curriculum-aligned question templates — GPT-2 / TinyLlama fine-tuning, 3,000+ analyzed rows.

#### 🌦️ MGM Weather Forecast (Time Series Analysis)
End-to-end pipeline scraping MGM data (`Selenium`) and forecasting with `SARIMAX`; optimized via AIC/BIC evaluation.

</details>

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=moztrk&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=moztrk&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="48%" />
</div>
<br>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=moztrk&theme=tokyonight&hide_border=true" width="98%" />
</div>

---

<div align="center">
  <a href="mailto:moztrk4444@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/mustafa-öztürk-155643250/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/moztrk">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>
