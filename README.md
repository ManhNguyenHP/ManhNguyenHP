<h1 align="center">Nguyen Duc Manh</h1>

<p align="center">
  <b>B.Sc. Mathematics &amp; Informatics</b> · Hanoi University of Science and Technology<br>
  Machine Learning · Physics-Informed Neural Networks · Agentic AI · Applied Mathematics
</p>

<p align="center">
  <a href="https://manhnguyenhp.github.io/"><img src="https://img.shields.io/badge/Portfolio-manhnguyenhp.github.io-0a66c2?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/manh-nguyen-duc-68753b322"><img src="https://img.shields.io/badge/LinkedIn-manh--nguyen--duc-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:manh.nd2824@gmail.com"><img src="https://img.shields.io/badge/Email-manh.nd2824%40gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://doi.org/10.1016/j.euromechsol.2025.105844"><img src="https://img.shields.io/badge/DOI-10.1016%2Fj.euromechsol.2025.105844-fcb426?style=flat-square&logo=doi&logoColor=white" alt="DOI"></a>
</p>

<p align="center"><i>Bản tiếng Việt: <a href="README.vi.md">README.vi.md</a></i></p>

---

## About

Final-year B.Sc. student in Mathematical Informatics at Hanoi University of Science and Technology
(GPA **3.67/4.0**, expected July 2026), working at the intersection of **machine learning and applied
mathematics**. My research sits where numerical analysis meets deep learning: surrogate models for
structural mechanics, physics-informed neural networks for PDE solving, and LLM-driven multi-agent
systems for scientific workflows.

I like problems where the mathematics has to be right *and* the system has to run on real hardware.

## Research &amp; Publications

**Highly Efficient Prediction of Beating Phenomena in Laminated Nanocomposite Plates Using a Hybrid Neural–Numerical–Analytical Framework**
*European Journal of Mechanics – A/Solids*, vol. 116 (2026), 105844 · Q1
[10.1016/j.euromechsol.2025.105844](https://doi.org/10.1016/j.euromechsol.2025.105844)
Contribution: neural network architecture design, model training and evaluation for the Stage 1 surrogate model.

**Adaptive Hard–Soft Physics-Informed Neural Networks for Robust Boundary-Constrained PDE Solving**
Manuscript under review.
Contribution: PINN implementation, formal analysis, writing review.

Research Student at the [Materials and Structures (MAS) Group](https://sites.google.com/view/mas-group-hust/home), HUST, since 2025.

## Selected Projects

### AgenticTS — Agentic AI Multi-Agent Framework for Time Series Forecasting
`Feb 2026 – May 2026` · Agentic AI · LLM reasoning · Multi-agent systems · Research paper

A reasoning-driven multi-agent framework that automates the end-to-end forecasting pipeline,
formalised as a constrained sequential decision process with hierarchical memory (episodic /
semantic / vector).

- **Nine specialised agents** — Orchestrator, Guardrail, Ingestion, Diagnostics, Feature, Model Strategy, Training, Evaluation, Report — reasoning via **Gemini 2.5 Flash Lite** on a containerised orchestration layer.
- **Diagnostic-constrained model selection**: ADF stationarity tests, ACF/PACF, Z-score outlier and seasonality detection dynamically narrow the search space over ARIMA, LSTM and DLinear, replacing brute-force grid/AIC search.
- Evaluated on Hanoi Energy, Hanoi Weather and ETTh1 across horizons 96/192/336/720. Against Auto-ARIMA on Hanoi Energy (H=96): **−10.6% MAE, −27.6% MSE**.
- Ablation study isolating the Feature / Diagnostics / Model Strategy agents. Every stage logs to a traceable JSON manifest for full reproducibility.

### Aviation Data Warehouse — Flight Delay &amp; Cancellation Analytics
`Sep 2025 – Jan 2026` · Big Data · deployed on a physical enterprise server (12 vCores, 31 GB RAM)

- Designed and deployed a **Galaxy Schema** data warehouse on a physical Hadoop cluster, with an automated end-to-end ingestion pipeline built on **Apache NiFi** and **Apache Oozie** — zero manual intervention.
- **91.47% storage reduction** via Parquet/Snappy compression and **6.1× query speedup** over row-based storage through partitioning and schema design.
- Benchmarked on live hardware rather than simulation. Resolved production-grade compatibility and permission issues in a real enterprise environment.
- Built analytical dashboards for delay patterns by airline, route, season and airport.

### Automatic Multiple-Choice Answer Sheet Grading System
`Mar 2025 – Jun 2025` · Computer Vision · **official faculty project, in production** at the Dept. of Mathematics &amp; Informatics, HUST

- End-to-end pipeline recognising filled and unfilled answer bubbles under real scan conditions: poor scan quality, partial erasures, varied lighting.
- Dataset built with Roboflow (collection, annotation, augmentation). **YOLOv8** trained and optimised to **mAP@0.5 ≈ 99%** on the held-out test set.
- OpenCV preprocessing (deskew, binarisation, noise removal) normalises diverse input quality before inference.
- **K-means clustering** post-processing spatially maps detected bubbles to logical answer positions, enabling fully automated scoring.
- Recognised with an official certificate of active participation from the Faculty.

## Experience

**Software Developer Intern** — 1C Vietnam, Ha Noi · `2025`
Built a retail pharmacy chain management system on **1C:Enterprise**, implementing modules for
inventory tracking, sales management, supplier orders and automated reporting. Hands-on with
enterprise software architecture, business process modelling and relational database configuration.

## Education

**B.Sc. Mathematics &amp; Informatics** — Hanoi University of Science and Technology · `2022 – 2026 (exp. July)`
GPA **3.67/4.0** (9.18/10)

Selected coursework: Optimization Methods (A+), Probability &amp; Statistics (A+), Data Structures &amp;
Algorithms (A), Database (A), Encryption &amp; Algorithm Complexity (A+), Numerical Analysis (B),
System Analysis &amp; Design (A).

## Awards, Scholarships &amp; Programs

| Year | Award |
| --- | --- |
| 2026 – | Participant, [VINIF Talent Program](https://vinif.org/en/sponsor-programs/talent-camps/) |
| 2025 | Mirae Asset Foundation Scholarship Program |
| 2025 | VIASM Student Summer School in Mathematics, Applied Mathematics track, FPT University Da Nang (competitive selection) |
| 2024, 2025 | Certificate of Achievement — Excellent Student, AY 2023–2024, Faculty of Mathematics &amp; Informatics, HUST |
| 2023 – | HUST Scholarship for Excellent Academic Performance (semesters 2023.1, 2023.2, 2024.1, 2024.2) |
| — | FAMI Scholarship · Bui Long Bien Teacher Scholarship · Silk Road Scholarship |

Member of the Applied Mathematics &amp; Informatics Club (AMIC), Faculty of Mathematics &amp; Informatics, HUST, since 2022.

## Certifications

- **WorldQuant** — BRAIN certificate · Challenge Gold Certificate · IQC 2026 Stage 1
- **DeepLearning.AI / Coursera** — Machine Learning Specialization: Supervised ML (Regression &amp; Classification), Advanced Learning Algorithms, Unsupervised Learning &amp; Recommenders
- **Mathematics for ML** — Calculus for Machine Learning and Data Science · Probability &amp; Statistics for Machine Learning
- **Data** — SQL for Data Science · Python for Everybody
- **Microsoft Office Specialist** — Excel

**Languages** — English (TOEIC 790) · Vietnamese (native)

## Tech Stack

**ML / DL**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Data &amp; Big Data**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![NiFi](https://img.shields.io/badge/NiFi-728E9B?style=flat-square&logo=apachenifi&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![1C:Enterprise](https://img.shields.io/badge/1C:Enterprise-FFCC00?style=flat-square&logoColor=black)

## Credentials

Transcripts, certificates, scholarship decisions, commendations and publication PDFs are collected here:
**[Proof of achievement (Google Drive)](https://drive.google.com/drive/folders/1Co7_COynE8MLSbvILPosyaCuAVKiTP4C?usp=sharing)**

## Contact

- Email — [manh.nd2824@gmail.com](mailto:manh.nd2824@gmail.com)
- LinkedIn — [manh-nguyen-duc](https://www.linkedin.com/in/manh-nguyen-duc-68753b322)
- Location — Ha Noi, Viet Nam

<p align="center"><sub>Open to research assistant, ML engineer and graduate research opportunities.</sub></p>
