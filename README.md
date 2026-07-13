<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=22&duration=3200&pause=900&color=F0A020&center=true&vCenter=true&width=780&lines=Data+Scientist+%E2%80%94+Marketing+%26+Measurement+Analytics;Verification-first+ML%2C+forecasting+and+NLP;A+number+is+only+worth+what+its+source+can+survive." alt="Hande Gabrali-Knobloch" />

<br>

**Bremen, Germany** · Working language: English <br> Five years measuring what advertising actually returned — now building the systems that predict it.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-33495F?style=flat-square&logo=linkedin&logoColor=F0A020)](https://www.linkedin.com/in/hande-gabrali-knobloch) [![Portfolio](https://img.shields.io/badge/Portfolio-33495F?style=flat-square&logo=githubpages&logoColor=F0A020)](https://hgabrali.github.io/) [![Email](https://img.shields.io/badge/Email-33495F?style=flat-square&logo=gmail&logoColor=F0A020)](mailto:hande.gabrali@gmail.com)

</div>

---

### The problem I work on

Most model failures are not loud. They pass every automated check and are quietly wrong — a metric carrying two incompatible definitions, a validator silently running only a self-test, a baseline computed inside the event it was supposed to measure. These are the errors that survive the pipeline and reach the decision.

My work is built around catching them before they do.

```mermaid
flowchart LR
    A[Raw source] --> B{Source verified<br/>against canonical?}
    B -->|no| X[HALT · return with evidence]
    B -->|yes| C[Schema + typed fields]
    C --> D{Reproducible from<br/>its own evidence?}
    D -->|no| X
    D -->|yes| E[Calibration anchor]
    E --> F[Forecast / decision]
    X -.->|corrected, additively| A

    style X fill:#33495F,stroke:#F0A020,stroke-width:2px,color:#fff
    style E fill:#F0A020,stroke:#33495F,stroke-width:2px,color:#1b1b1b
    style F fill:#33495F,stroke:#F0A020,stroke-width:2px,color:#fff
```

Applied most recently at **Huggin Munin / Agricom**, as sole owner of the intelligence layer feeding a production price-prediction pipeline: a 25-year EU market-shock retrospective, the automated validator extended from **17 → 29 rules**, and **5 classes of silent error** caught that every mechanical check had waved through.

---

### Selected work

| Project | What it does | Stack |
|---|---|---|
| **[Ranker AI](https://github.com/hgabrali/ranker-ai-demo)** | Measures how brands surface inside AI answer engines. Mixture-of-Agents across 5 LLMs, XGBoost visibility scoring, embedding-based semantic drift detection. | FastAPI XGBoost XLM-RoBERTa AWS ECS Docker |
| **[Media Science & Strategy Analytics Stack](https://github.com/hgabrali/Media-Science-Strategy-Analytics-Stack)** | Statistical and ML methods for advertising — Media Mix Modeling, targeting, marketing automation. | Python MMM Econometrics |
| **[Retail Demand Forecasting — Favorita](https://github.com/hgabrali/Favorita-Quant-Regional-Sales-Forecasting-Project)** | Prophet (MAPE 14.56%) vs SARIMA (RMSE 20.07) vs XGBoost (RMSE 20.15). Benchmarked, not assumed. | Prophet SARIMA XGBoost |
| **[Disaster Tweet NLP Pipeline](https://github.com/hgabrali/Disaster-Tweet-Classification_High-Precision-NLP-Pipeline)** | DeBERTa-v3 vs TF-IDF + LogReg (F1 0.778) — establishing whether transformer cost is justified by measured gain. | HuggingFace DeBERTa-v3 scikit-learn |
| **[TravelTide Segmentation](https://github.com/hgabrali/TravelTide_Customer_Retention_Mastery_Project)** | K-Means into 3 personas; surfaced a +30% weekend spend uplift and a 15% churn-risk cohort. | scikit-learn K-Means Tableau |
| **[Coca-Cola 2020 Media Investment](https://github.com/hgabrali/Coca-Cola-2020-Media-Investment-Brand-Strategy-Analysis)** | Econometric and MMM analysis of brand resilience through a demand shock. | Python Econometrics MMM |

---

### Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-33495F?style=flat-square&logo=python&logoColor=F0A020) ![SQL](https://img.shields.io/badge/SQL-33495F?style=flat-square&logo=postgresql&logoColor=F0A020) ![pandas](https://img.shields.io/badge/pandas-33495F?style=flat-square&logo=pandas&logoColor=F0A020) ![scikit-learn](https://img.shields.io/badge/scikit--learn-33495F?style=flat-square&logo=scikitlearn&logoColor=F0A020) ![PyTorch](https://img.shields.io/badge/PyTorch-33495F?style=flat-square&logo=pytorch&logoColor=F0A020) ![XGBoost](https://img.shields.io/badge/XGBoost-33495F?style=flat-square&logo=xgboost&logoColor=F0A020) ![HuggingFace](https://img.shields.io/badge/HuggingFace-33495F?style=flat-square&logo=huggingface&logoColor=F0A020) ![FastAPI](https://img.shields.io/badge/FastAPI-33495F?style=flat-square&logo=fastapi&logoColor=F0A020) ![Docker](https://img.shields.io/badge/Docker-33495F?style=flat-square&logo=docker&logoColor=F0A020) ![AWS](https://img.shields.io/badge/AWS-33495F?style=flat-square&logo=amazonwebservices&logoColor=F0A020) ![Tableau](https://img.shields.io/badge/Tableau-33495F?style=flat-square&logo=tableau&logoColor=F0A020) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-33495F?style=flat-square&logo=githubactions&logoColor=F0A020)

</div>

---

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=hgabrali&show_icons=true&hide_border=true&bg_color=00000000&title_color=F0A020&text_color=8A97A5&icon_color=F0A020&hide=issues" /> <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hgabrali&layout=compact&hide_border=true&bg_color=00000000&title_color=F0A020&text_color=8A97A5&langs_count=6" />

<br>

<img src="https://github.com/hgabrali/hgabrali/blob/output/github-contribution-grid-snake-dark.svg" alt="contribution activity" />

</div>

---

<div align="center">
<sub><b>Background:</b> Coca-Cola · Reckitt Benckiser · Ülker — media investment at Havas Creative Network, Carat (dentsu) and Starcom MediaVest Group. 2× Effie Gold · 4× Kristal Elma · Kristal Elma Grand Prix.</sub>
</div>
