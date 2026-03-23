<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:58a6ff&height=200&section=header&text=Atharva%20Mate&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20%7C%20Deep%20Learning%20%7C%20Builder&descAlignY=60&descSize=20&animation=fadeIn" width="100%"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Building+AI+that+actually+works+%F0%9F%A7%A0;From+Transformers+to+Chrome+Extensions+%F0%9F%9A%80;B.Tech+IT+%40+RCOEM+Nagpur+%E2%80%A2+GPA+8.71%2F10" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/atharvamate2004)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtharvaMate)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atharvamate2004@gmail.com)
[![CodeChef](https://img.shields.io/badge/CodeChef_2★-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com)

</div>

---

## 🧠 About Me

```python
class AtharvaDeepakMate:
    def __init__(self):
        self.name        = "Atharva Deepak Mate"
        self.college     = "RCOEM Nagpur — B.Tech IT (2023–Present)"
        self.gpa         = 8.71
        self.focus       = ["Deep Learning", "NLP", "Computer Vision", "Full-Stack"]
        self.current     = "Building things at the intersection of AI and UX"
        self.fun_fact    = "I built a GPT from scratch and trained it on Shakespeare 📜"

    def stack(self):
        return {
            "deep_learning"  : ["TensorFlow", "Keras", "KerasHub", "Transfer Learning", "LoRA"],
            "computer_vision": ["OpenCV", "YuNet ONNX", "Xception"],
            "nlp_llms"       : ["Transformers", "Seq2Seq", "LLM Fine-Tuning", "T5/Gemma"],
            "backend"        : ["Java J2EE", "Servlets", "Spring Boot", "JDBC", "MySQL"],
            "tools"          : ["GCP", "Streamlit", "Docker", "Git", "MongoDB"],
        }
```

---

## 🚀 Featured Projects

### 🔍 DeepfakeDetection — Vision AI
> *Xception · Transfer Learning · OpenCV YuNet · Streamlit*

Replaced a vanilla CNN baseline with an **Xception Transfer Learning** pipeline featuring face-centric temporal sampling. Achieved a **+14pp accuracy jump** (71% → 85%), **+18% precision**, and **−22% false positives** using OpenCV YuNet ONNX for precise face localization. Deployed as a real-time Streamlit web app with per-frame confidence scoring.

[![Repo](https://img.shields.io/badge/Repo-DeepfakeDetection-58a6ff?style=flat-square&logo=github)](https://github.com/AtharvaMate/DeepfakeDetection)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

| Metric | Baseline CNN | Xception Model |
|---|---|---|
| Accuracy | 71% | **85%** (+14pp) |
| Precision | — | **+18%** |
| False Positives | — | **−22%** |

---

### 🧬 MiniGPT — Decoder-Only Transformer from Scratch
> *TensorFlow · Keras · Causal Self-Attention · NLP*

Built a **GPT-style decoder-only Transformer** entirely from scratch — causal self-attention, positional embeddings, and residual feed-forward blocks across **4 stacked layers** for character-level generation on Shakespeare. Modularized as clean Keras `Layer` subclasses.

[![Repo](https://img.shields.io/badge/Repo-MiniGPT-58a6ff?style=flat-square&logo=github)](https://github.com/AtharvaMate/MiniGPT)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)

> 📊 Cross-entropy loss **1.08** · Token accuracy **~66%** · Trained over **15 epochs**  
> ✅ Learned dialogue structure, character attribution & period-accurate vocabulary from raw character sequences

---

### 💬 NL-SQL — Natural Language → SQL with LoRA Fine-Tuning
> *KerasHub · T5GemmaSeq2SeqLM · LoRA · Spider Benchmark*

Fine-tuned **T5GemmaSeq2SeqLM** on the Spider NL-to-SQL benchmark using **LoRA (rank=16)**. Built an end-to-end pipeline with AdamW, early stopping, and best-weight restoration. Deployed Beam Search decoding and serialized in KerasHub's preset format.

[![Repo](https://img.shields.io/badge/Repo-NL--SQL-58a6ff?style=flat-square&logo=github)](https://github.com/AtharvaMate/NL-SQL)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)

> 📊 **~83.5% token-level validation accuracy** · Training loss 0.082 → **0.015** over 8 epochs  
> 🗃 850-sample Spider dataset · Beam Search inference

---

### 📚 NotePilot — AI-Powered YouTube Study Chrome Extension
> *JavaScript · Chrome MV3 · Groq (Llama 4 Scout + 3.3 70B) · KaTeX · jsPDF*

A Chrome extension that turns any YouTube video into an interactive study session. Capture frames at any timestamp, AI extracts on-screen content (OCR), an AI tutor answers questions using your notes as context, and exports everything as a polished A4 PDF — with **fully rendered LaTeX math equations**.

[![Repo](https://img.shields.io/badge/Repo-NotePilot-58a6ff?style=flat-square&logo=github)](https://github.com/AtharvaMate/NotePilot)
[![Live Demo](https://img.shields.io/badge/Demo-note--pilot--ten.vercel.app-28a745?style=flat-square&logo=vercel)](https://note-pilot-ten.vercel.app)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chrome](https://img.shields.io/badge/-Chrome_MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Groq](https://img.shields.io/badge/-Groq_AI-F55036?style=flat-square)

**Key Features:**
- 🎯 Frame capture injected directly into YT player controls
- 🔬 Vision AI OCR via **Llama 4 Scout** — extracts equations, diagrams, text
- 💡 Instant AI explanations with live **KaTeX** math rendering
- 🤖 Context-aware multi-turn AI chat scoped to the video
- 📄 Polished A4 PDF export — cover page, AI summary, capture cards, Q&A section

---

### 🏦 SmartBank — Secure Digital Banking Backend
> *Java J2EE · Servlets · JSP · BCrypt · MySQL · JDBC*

Full-stack digital banking system with **ACID-compliant transaction management** (JDBC commit/rollback), BCrypt password hashing, fraud detection checks, session-based auth, P2P transfers, and complete transaction history.

[![Repo](https://img.shields.io/badge/Repo-SmartBank-58a6ff?style=flat-square&logo=github)](https://github.com/AtharvaMate)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## 🛠 Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Deep Learning & AI
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Tools & Platforms
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AtharvaMate&show_icons=true&theme=github_dark&border_color=30363d&hide_border=false&rank_icon=github&include_all_commits=true&count_private=true" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AtharvaMate&layout=compact&theme=github_dark&border_color=30363d&langs_count=8" height="165"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=AtharvaMate&theme=github-dark-blue&border=30363d&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff" height="165"/>

</div>

---

## 🏅 Certifications

| Certification | Issuer | Focus |
|---|---|---|
| 🧠 Machine Learning Specialization | IBM / Coursera | Supervised & unsupervised learning, feature engineering |
| 🤖 TensorFlow Developer Specialization | DeepLearning.AI / Coursera | CNNs, Transfer Learning, RNNs, NLP |
| ☁️ AI/ML Virtual Internship | Google for Developers (EduSkills) · Jul–Sep 2025 | TensorFlow, data preprocessing, fine-tuning |

---

## 🎯 What I'm Working On

- 🔬 Exploring **LLM fine-tuning** pipelines with LoRA/QLoRA on domain-specific data
- 🛠 Extending **NotePilot** — RAG-based context retrieval over long video sessions
- 📐 Deepening knowledge in **efficient Transformer architectures**

---

<div align="center">

<!-- Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,100:0d1117&height=100&section=footer" width="100%"/>

*"The best way to understand a model is to build one from scratch."*

</div>
