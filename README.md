<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=220&section=header&text=Le%20Gia%20Van&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20RAG%20%C2%B7%20Document%20AI%20%C2%B7%20Data%20Infra&descSize=20&descAlignY=58" width="100%" alt="Le Gia Van" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=7AA2F7&center=true&vCenter=true&width=760&height=50&lines=Bridging+AI+Research+%26+Production+%E2%9A%99%EF%B8%8F;OpenBCTC%3A+50+pages+of+reports+in+5+mins+%E2%9A%A1;First+author+%C2%B7+ICCVR+2026+(Vector+Search)+%F0%9F%93%84;Open+for+AI+%2F+Data+Engineering+Internships+%F0%9F%9A%80" alt="Typing animation" />
</a>

<br>

[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:legiavan.forwork@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LeGiaVan)
![ICCVR](https://img.shields.io/badge/ICCVR_2026-First_Author-FF4081?style=for-the-badge)
![GPA](https://img.shields.io/badge/UEL-GPA_8.13-306EE8?style=for-the-badge)

</div>

---

## ⚡ Quick look

<div align="center">

| 📄 OCR | 🤖 Copilot | 🔭 Monitoring | 🔬 Research |
|:---:|:---:|:---:|:---:|
| **~50 pages**<br>in under **5 min**<br>zero cost | **95%** SQL accuracy<br>**90%** citation precision<br>**96%** faithfulness | **5** data-quality failures<br>+ freshness breach<br>auto-resolved | **1st author**<br>**ICCVR 2026**<br>FAISS benchmark |

</div>

<sub>Copilot numbers come from a 50-question benchmark I built myself over one 54-page audited report, so read them as a development check.</sub>

---

## 👨‍💻 About me

- 🎓 Studying **Management Information Systems** at UEL, VNU-HCM (expected May 2027, GPA 8.13/10)
- 🧪 **BAAI Lab:** built the web platform for predicting Metal-Organic Framework properties and integrated the lab's models (I did not train the models)
- 🏫 **ITAC (UEL):** studying the core of the deployed admissions chatbot and onboarding other team members; designated main developer of the core RAG for the department chatbots (Academic Affairs, Quality Assurance, Administration, HR) once that phase begins
- 📚 I like reading scientific research, economics, politics and culture
- 🤝 Open to internships and research collaborations in AI Engineering, Data Engineering and Applied ML

---

## 🛠️ Toolbox

<div align="center">

**Languages**<br>
<img src="https://skillicons.dev/icons?i=python,postgres,bash,js,ts" />

**LLM apps · Document AI · Search**<br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![MinerU](https://img.shields.io/badge/MinerU-OCR-007396?style=for-the-badge)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-2932E1?style=for-the-badge)

**Data engineering · Backend · Ops**<br>
<img src="https://skillicons.dev/icons?i=fastapi,docker,kafka,prometheus,grafana,git,gitlab" />

</div>

---

## 🚀 Featured projects

| Project | What it does | Highlight |
|---|---|---|
| 📄 **OpenBCTC** | Multi-stage OCR for Vietnamese financial statements. Main statements go to SQL and are validated by accounting rules; notes are reviewed in a browser interface and exported to Markdown. | ~50 pages in under 5 min, zero cost |
| 🤖 **OpenBCTC Copilot** | LangGraph chatbot on top of OpenBCTC data: SQL engine for figures, hybrid retrieval for notes, fact-check step, page-level citations with a highlighted PDF viewer. | 95% SQL accuracy, 96% faithfulness |
| 🔭 **NorthStream** *(team of 3, my part: monitoring and alerting)* | Prometheus and Grafana dashboards, alerts for lag, stalled jobs, freshness and data quality, delivered to PagerDuty with auto-resolve. | Tested with simulated failures end to end |
| 🚢 **Zero-stop e-Border** | Customs platform with an HS-code assistant, document verification and a risk dashboard. | 🥈 2nd Prize (team leader), AI in Business S3 |
| 🍅 **TomatoAI** | v1 greenhouse assistant prototype: sensor alerts, leaf disease diagnosis, ripeness grading, voice consultation over Telegram. Coursework, team lead. | n8n, Telegram, computer vision |

```mermaid
flowchart LR
    A["📄 PDF report"] --> B["Multi-stage OCR"]
    B --> C["3 main statements<br/>to SQL, accounting checks"]
    B --> D["Notes<br/>human review"]
    C --> E["🤖 Copilot"]
    D --> E
    E --> F["✅ Answer + page citation<br/>numbers checked vs SQL"]
```

---

## 📝 Research

> **When Does Approximate Search Preserve Composed Image Retrieval Quality? A Scale-Aware FAISS Benchmark**
> 🥇 First author · Accepted at **ICCVR 2026** (Paper ID: V377)

- Reproduced three zero-shot CIR models (CLIP4Cir, SEARLE, Pic2Word) under one evaluation harness and fixed two reproducibility bugs that would have invalidated the measurements.
- Benchmarked FAISS **HNSWFlat**, **IVFFlat** and **IVFPQ** on FashionIQ, CIRR and CIRCO, sweeping parameters to find the sweet spot between quality and query cost.
- 📉 Large speedups on the 123K-image CIRCO gallery, but only **1 to 5x** on 2 to 6K-image galleries.
- ⚖️ HNSWFlat is usually, but not always, faster than IVFFlat at matched retention, so the best index is **model-dependent**.
- 🚫 No tested IVFPQ configuration reached **95%** retention.

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=LeGiaVan&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&hide_rank=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeGiaVan&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://streak-stats.demolab.com?user=LeGiaVan&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

*Let's connect and build something good together.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%" alt="" />

</div>
