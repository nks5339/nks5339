<div align="center">
  <img src="https://github.com/nks5339/nks5339/blob/main/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" />
</div>

<div align="center">

<!-- Typing banner -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3200&pause=900&color=0E75B6&center=true&vCenter=true&width=720&lines=Hi+there%2C+I'm+Nikunj+Kumar+%F0%9F%91%8B;AI%2FML+%26+Generative+AI+Developer;LLMs+%C2%B7+RAG+Pipelines+%C2%B7+Vector+Search;Building+enterprise+AI+that+ships+to+production" alt="Nikunj Kumar" />

<br>

<img src="https://komarev.com/ghpvc/?username=nks5339&label=Profile%20views&color=0e75b6&style=flat-square" alt="profile views" />
<img src="https://img.shields.io/badge/Associate%20Consultant-EY%20Technology%20Consulting-FFE600?style=flat-square&labelColor=2E2E38" alt="EY" />
<img src="https://img.shields.io/badge/Focus-Generative%20AI%20%26%20RAG-0E75B6?style=flat-square" alt="focus" />

</div>

---

### 🧭 About

> AI/ML and Generative AI Developer building intelligent systems with **Large Language Models**, **RAG pipelines**, and **vector databases**. I ship scalable Gen-AI applications that blend natural language processing, computer vision, and speech recognition — and I care about the boring parts: token cost, latency, uptime, and not hallucinating in front of a government client.

```yaml
name:        Nikunj Kumar
role:        Associate Consultant, Technology Consulting @ EY (Ernst & Young)
since:       January 2024
education:   B.Tech CSE, Sikkim Manipal Institute of Technology (2020–2024) · CGPA 8.12/10
domains:     [ Public Procurement, Healthcare Diagnostics, Enterprise Automation ]
goal:        Production-grade Generative AI that solves real enterprise problems at scale
mission:     Bridge rigorous ML/DL fundamentals with bleeding-edge LLM orchestration
```

---

### ⚙️ Core Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 Generative AI & RAG
Retrieval-augmented chatbots and evaluation systems on **LangChain**, **LlamaIndex**, **Gemini 2.5 Flash**, and **LLaMA 3** — using context caching and hybrid retrieval to cut hallucinations and token spend.

</td>
<td width="50%" valign="top">

#### 🕸️ Vector Search & Semantic Matching
**Sentence-BERT** similarity and fraud-detection engines backed by **Qdrant**, with cross-encoder reranking and anomaly detection (Isolation Forest, DBSCAN) for high-precision matching.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📄 Document Intelligence & OCR
Dual-OCR pipelines (**Gemini Vision** primary → **Tesseract** fallback) via PyMuPDF for scanned, image-heavy RFPs — plus automated compliance scoring and Excel/Word report generation.

</td>
<td width="50%" valign="top">

#### 🧠 Applied Deep Learning
CNN + LSTM hybrids and transfer learning (**VGG16**, **ResNet-50**, **DenseNet**) in PyTorch/TensorFlow for healthcare diagnostics — ECG stroke prediction and knee disease classification.

</td>
</tr>
</table>

---

### 📊 Work That Shipped

| Project | Stack | Impact |
|---|---|---|
| **RFP Analyzer** — AI-Powered Bid Evaluation | Gemini 2.5 Flash · FastAPI · Tesseract · PyMuPDF | `−60%` token usage per vendor via context caching · 5-status compliance framework · 11-combo OCR fallback |
| **Match Detection System** — GeM Portal | Sentence-BERT · Qdrant · Docker · Kubernetes | `92%` precision on fraudulent bids · `−38%` search latency · `87%` recall on anomalies · `50k+` req/day |
| **PDF Chatbot** — Rajasthan Finance Dept. | LLaMA 3 · LangChain · Qdrant · Bhashini | `10k+` policy docs · `94%` answer accuracy · `3×` faster inference (sub-1.2s) · `99.8%` uptime |
| **Text-to-SQL BI Platform** | LangChain SQL Agents · Oracle SQL · Streamlit | `91%` query accuracy · `200+` tables auto-parsed · `−70%` manual query time · `10k+` queries/month |
| **ECG Classification** | TensorFlow · Keras · SciPy · CUDA | `93.4%` accuracy · `50k+` samples · training `10h → 3.5h` · `200+` signals/min at `<1s` latency |
| **Knee Disease Diagnostics** | PyTorch · ResNet-50 · DenseNet | `95%` classification accuracy via transfer learning |

<details>
<summary><b>🔍 Detailed architectural breakdown</b></summary>

<br>

#### 🤖 Generative AI & RAG Systems
- **RFP Analyzer:** GenAI bid evaluation on Gemini 2.5 Flash with context caching, async parallel vendor evaluation via `asyncio.gather`, and a 5-status compliance framework (Compliant → Partially Compliant → Not Evidenced → Non-Compliant → Conditionally Compliant) with false-positive prevention. Full-stack SPA: FastAPI backend, vanilla JS frontend, multi-format ingestion (PDF, DOCX, XLSX), real-time progress tracking, and report generation through `openpyxl` / `python-docx`.
- **PDF Intelligence Chatbots:** Multilingual RAG over 10k+ policy documents (LLaMA 3 + LangChain + Qdrant), hybrid retrieval with Hugging Face embeddings that cut irrelevant responses by 41%, Bhashini-powered Hindi–English translation serving 5k+ government employees, and CUDA/TensorRT-optimized sub-1.2s inference on GPU-backed servers.

#### 🕸️ Vector Search & Fraud Detection
- **Semantic Bid Matching:** Sentence-BERT embeddings with cosine similarity and cross-encoder reranking on Qdrant, reducing search latency 38% while improving fraud-detection precision to 92%.
- **Anomaly Detection:** Isolation Forest and DBSCAN layered over embedding search to flag irregular bidding patterns at 87% recall.
- **Scale:** FastAPI microservices on Docker + Kubernetes, horizontally scaled to 50k+ requests/day; end-to-end cloud deployment lifted fraud monitoring efficiency 65%.

#### 🧠 Text-to-SQL & BI Platforms
- **Natural Language → SQL:** LangChain SQL Agents with automated Oracle schema parsing across 200+ complex tables, paired with Streamlit dashboards that drove a 50% adoption increase among non-technical stakeholders. Visualization workflows in Pandas/Matplotlib/Plotly cut report generation time 45%.

#### 🩺 Applied Deep Learning for Healthcare
- **ECG Classification:** Hybrid CNN (VGG16) + LSTM pipeline with STFT/FFT and Butterworth filtering for 60% noise reduction, CUDA-accelerated training, and real-time inference on streaming ECG signals — improving stroke prediction efficiency 47%.
- **Diagnostic Imaging:** Transfer-learning CNNs (ResNet-50, DenseNet) for knee disease classification at 95% accuracy.

#### 🏛️ Enterprise & Full-Stack Delivery
- **Companies Office of Jamaica:** Responsive React frontend modernization with Redux, Formik, and Tailwind.
- **WB Health Surrogacy Project:** Licensing workflows on Spring Boot microservices with a React frontend.

</details>

---

<div align="center">

### 🛠️ Languages & Tools

<img src="https://skillicons.dev/icons?i=python,java,js,r,html,css,react,fastapi,flask,spring,docker,kubernetes,mongodb,postgres,git,github,vscode,linux&perline=9" />

<br><br>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LlamaIndex-3D1E68?style=for-the-badge" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge" />
<img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle%20SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />

</div>

---

<div align="center">

### 📈 GitHub Stats

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nks5339&show_icons=true&theme=react&hide_border=true&bg_color=0D1117&title_color=0E75B6&icon_color=0E75B6" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nks5339&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=0E75B6&langs_count=8" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=nks5339&theme=react&hide_border=true&background=0D1117&ring=0E75B6&fire=0E75B6" />

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=nks5339&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

---

### 🎓 Licenses & Certifications

| Certification | Issuer | Date |
|---|---|---|
| Artificial Intelligence – AI Engineering *(Silver Learning)* | EY | Dec 2025 |
| Cybersecurity Fundamentals *(Bronze Learning)* | EY | Dec 2024 |
| Artificial Intelligence in Cybersecurity *(Bronze Learning)* | EY | Nov 2024 |
| Exploratory Data Analysis for Machine Learning | IBM | Oct 2024 |
| AI For Everyone | DeepLearning.AI | Apr 2024 |
| Python Essentials for MLOps | Duke University | Mar 2024 |

---

<div align="center">

### 🤝 Connect

<a href="https://www.linkedin.com/in/nikunj5339/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/nks5339" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:nikunjkumar5339@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br><br>

<i>Random dev joke for you!</i>
<br>
<img src="https://readme-jokes.vercel.app/api?hideBorder&theme=react&bgColor=0D1117&qColor=0E75B6" alt="Jokes Card" />

<br><br>

<a href=# ><img src="contributions.svg"></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0E75B6,100:2E2E38&height=100&section=footer" />

</div>
