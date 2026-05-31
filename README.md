<div align="center">

# castle9612

### AI & Backend Developer  
Building machine learning systems, data-driven experiments, and production-oriented web services.

[![GitHub](https://img.shields.io/badge/GitHub-castle9612-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/castle9612)
[![Focus](https://img.shields.io/badge/Focus-AI%20Research%20%7C%20Backend%20Engineering-2563EB?style=for-the-badge)](#)
[![Location](https://img.shields.io/badge/Location-South%20Korea-0F766E?style=for-the-badge)](#)

</div>

---

## About Me

I am a developer focused on **AI modeling, experiment engineering, and backend service development**.  
My work spans molecular property prediction, drug side-effect prediction, fake voice detection, tabular medical classification, sales conversion prediction, and Spring Boot-based web services.

I care about more than simply running models. I focus on building reproducible pipelines, designing validation strategies, comparing feature representations, and connecting experimental results to practical systems. Apparently that is what humans call “being responsible with code.”

---

## Core Strengths

<table>
<tr>
<td width="33%" valign="top">

### AI Research & Modeling
- Molecular prediction with SMILES data
- Audio classification and feature extraction
- Medical and business tabular classification
- Model comparison and performance tracking

</td>
<td width="33%" valign="top">

### Experiment Engineering
- Feature engineering and preprocessing
- Validation metric design
- k-fold and split strategy experiments
- Reproducible training scripts

</td>
<td width="33%" valign="top">

### Backend Development
- Spring Boot REST/service architecture
- JPA-based database design
- Authentication and authorization
- Docker-based deployment structure

</td>
</tr>
</table>

---

## Tech Stack

### AI / Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![RDKit](https://img.shields.io/badge/RDKit-Chemoinformatics-0F766E?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square)

### Backend / Web

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Selected Projects

### 1. Drug Discovery Prediction

[![Repo](https://img.shields.io/badge/Repository-dacon--drug--discovery--prediction2-181717?style=flat-square&logo=github)](https://github.com/castle9612/dacon-drug-discovery-prediction2)

Molecular activity prediction project based on a drug discovery competition dataset.

**What I worked on**
- Built prediction pipelines using SMILES-based molecular data.
- Compared RDKit descriptors, fingerprints, GNN-based representations, ChemBERTa, MolCLR, and tabular ensemble models.
- Tested XGBoost, LightGBM, CatBoost, AutoGluon, and deep learning approaches.
- Organized visual outputs such as feature importance, prediction scatter plots, and experimental result summaries.

**Keywords**  
`Molecular Prediction` · `SMILES` · `RDKit` · `GNN` · `ChemBERTa` · `MolCLR` · `XGBoost` · `AutoGluon`

---

### 2. Drug Side Effect Prediction

[![Repo](https://img.shields.io/badge/Repository-drug--side--effect-181717?style=flat-square&logo=github)](https://github.com/castle9612/drug-side-effect)

Research-oriented project for predicting drug side effects by combining molecular structure and target action features.

**What I worked on**
- Combined SMILES-based drug representations with target action matrix features.
- Compared MLP, LightGBM, XGBoost, and Two-Tower architectures.
- Applied AutoEncoder-based dimensionality reduction, Tanimoto similarity, k-fold validation, and drug-based split strategies.
- Recorded final benchmark performance of **F1 0.6711 / Accuracy 0.7273**.

**Keywords**  
`Drug Side Effect` · `SMILES` · `Target Action` · `AutoEncoder` · `Tanimoto Similarity` · `Two-Tower` · `LightGBM` · `XGBoost`

---

### 3. Fake Voice Detection

[![Repo](https://img.shields.io/badge/Repository-fake__voice__detect-181717?style=flat-square&logo=github)](https://github.com/castle9612/fake_voice_detect)

Audio classification project for detecting fake or manipulated voices.

**What I worked on**
- Designed preprocessing pipelines for MFCC, mel-spectrogram, spectrum, and statistical audio features.
- Compared CNN/RCNN-based audio classifiers with TabNet-based tabular feature classification.
- Structured the repository around reproducible scripts while excluding large regenerated arrays and checkpoints.
- Included data quality checks such as zero-feature filtering.

**Keywords**  
`Audio Classification` · `MFCC` · `Mel-Spectrogram` · `Librosa` · `CNN` · `RCNN` · `TabNet`

---

### 4. KMU Brain TabNet

[![Repo](https://img.shields.io/badge/Repository-kmu--brain-181717?style=flat-square&logo=github)](https://github.com/castle9612/kmu-brain)

Medical and biological tabular classification experiment using TabNet.  
**Award: 3rd Place**

**What I worked on**
- Built TabNet-based classification experiments for medical/biological tabular features.
- Compared preprocessing strategies using RobustScaler, MinMaxScaler, and StandardScaler.
- Tracked validation AUC, logloss, best epoch, and best validation performance.
- Managed feature-drop candidates to support repeated feature selection experiments.

**Keywords**  
`Tabular Classification` · `TabNet` · `PyTorch` · `AUC` · `Feature Selection` · `Medical Data`

---

### 5. LG Aimers Sales Conversion

[![Repo](https://img.shields.io/badge/Repository-lg__Aimers-181717?style=flat-square&logo=github)](https://github.com/castle9612/lg_Aimers)

Machine learning project for predicting sales opportunity conversion.

**What I worked on**
- Modeled sales conversion using customer, product, and inquiry-related features.
- Tested XGBoost and Gradient Boosting based classification models.
- Built validation flows using accuracy, F1-score, and AUROC.
- Created a Tkinter-based GUI for quick column distribution analysis during EDA.

**Keywords**  
`Sales Conversion` · `Classification` · `XGBoost` · `Gradient Boosting` · `Feature Importance` · `Tkinter`

---

### 6. Reservation Web Service

[![Repo](https://img.shields.io/badge/Repository-reservation-181717?style=flat-square&logo=github)](https://github.com/castle9612/reservation)

Full-stack reservation management service for therapy/body care scheduling.

**What I worked on**
- Developed a backend using Spring Boot 3.2, Java 17, Spring Security, Spring Data JPA, and MySQL 8.
- Implemented reservation flow, user management, admin features, and database-backed service logic.
- Built a hybrid structure with React + Vite for user-facing pages and server-rendered admin pages.
- Added Docker Compose, `.env.example`, Nginx reverse proxy examples, and deployment documentation.

**Keywords**  
`Spring Boot` · `Spring Security` · `JPA` · `MySQL` · `React` · `Docker` · `Reservation System`

---

### 7. KakaoTalk Chat Analyzer

[![Repo](https://img.shields.io/badge/Repository-kakaotalk__analyze-181717?style=flat-square&logo=github)](https://github.com/castle9612/kakaotalk_analyze)

GUI tool for analyzing exported KakaoTalk chat logs.

**What I worked on**
- Parsed KakaoTalk text exports and analyzed chat count, activity by period, user-level statistics, word frequency, and word clouds.
- Built a Tkinter GUI for file selection, date range filtering, and user-specific analysis.
- Organized execution guidance for Windows distribution using PyInstaller.

**Keywords**  
`Python` · `Tkinter` · `Pandas` · `WordCloud` · `Matplotlib` · `Text Analysis`

---

## Algorithm & Computer Science Practice

[![Repo](https://img.shields.io/badge/Repository-backjoon-181717?style=flat-square&logo=github)](https://github.com/castle9612/backjoon)

I maintain algorithm problem-solving records to strengthen computer science fundamentals, including data structures, implementation, search, sorting, and dynamic programming.

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=castle9612&show_icons=true&theme=transparent&hide_border=true&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=castle9612&layout=compact&theme=transparent&hide_border=true)

</div>

---

## Portfolio Direction

My projects can be summarized into three main directions.

| Direction | Description |
|---|---|
| **AI Research & Modeling** | Experimenting with molecular, audio, medical, business, and tabular data across multiple model families. |
| **Experiment Engineering** | Managing preprocessing, feature extraction, validation metrics, model comparison, visualization, and reproducible scripts. |
| **Backend Service Development** | Building Spring Boot-based services with authentication, database design, admin workflows, frontend integration, and deployment structure. |

---

## Contact

- GitHub: [github.com/castle9612](https://github.com/castle9612)

