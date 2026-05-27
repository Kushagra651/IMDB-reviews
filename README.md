%-------------------------
% Resume — Kushagra Bhargava
% ATS-Optimized | Single Page | ML Engineer / MLOps
%-------------------------

\documentclass[letterpaper,10.5pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{textcomp}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.55in}
\addtolength{\evensidemargin}{-0.45in}
\addtolength{\textwidth}{1.1in}
\addtolength{\topmargin}{-0.72in}
\addtolength{\textheight}{1.65in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule\vspace{-4pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{
  \item\small{#1\vspace{-1pt}}
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeProjectHeading}[2]{
  \item
  \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
    \small#1 & \textbf{\small #2}\\
  \end{tabular*}\vspace{-2pt}
}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}[leftmargin=0.15in, itemsep=0pt, topsep=0.5pt]}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-2pt}}

%-------------------------------------------
\begin{document}

%----------HEADING----------
%----------HEADING----------
\begin{center}
    {\Huge \scshape Kushagra Bhargava} \\[3pt]
    \small
    \faMapMarker* \ Bengaluru 560078, India
    \enspace\textbar\enspace
    \faPhone \ +91\,6350655535
    \enspace\textbar\enspace
    \faEnvelope \ 
    \href{mailto:kushagrabhargava93@gmail.com}{kushagrabhargava93@gmail.com}
    \enspace\textbar\enspace
    \faLinkedin \ 
    \href{https://linkedin.com/in/kushagrabhargava651}{linkedin.com/in/kushagra651} \\[1pt]
    
    \faGithub \ 
    \href{https://github.com/kushagra651}{github.com/kushagra651}
    \enspace\textbar\enspace
    \faPenNib \ 
    \href{https://substack.com/@kushagrabhargava}{substack.com/@kushagrabhargava}
\end{center}
%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
\resumeSubheading
  {Dayananda Sagar College of Engineering}{CGPA: 8.57 / 10}
  {B.E. in Information Science and Engineering}{2023 -- 2027}
  \resumeItemListStart
    \resumeItem{\textbf{Coursework:} Machine Learning, DSA, DBMS, Statistics \& Probability, Linear Algebra, Operating Systems}
  \resumeItemListEnd
\resumeSubHeadingListEnd

\vspace{-5pt}

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}, itemsep=1pt, topsep=1pt, parsep=0pt]\small
  \item \textbf{Languages:} Python, SQL, C++

  \item \textbf{ML \& Deep Learning:} scikit-learn, XGBoost, LightGBM, PyTorch, SARIMA, SMOTE, SHAP,
        feature engineering, ensemble methods

  \item \textbf{NLP \& LLMs:} HuggingFace Transformers, LoRA/PEFT, 4-bit quantization, RAG pipelines,
        Qdrant, Ollama, prompt engineering

  \item \textbf{MLOps \& Deployment:} MLflow, Apache Airflow, Docker, FastAPI, Prometheus, Grafana,
        Evidently AI, CI/CD, Git

  \item \textbf{Cloud \& DevOps:} AWS EC2, S3, GitHub Actions, Docker Compose

  \item \textbf{Data \& Infrastructure:} Pandas, NumPy, Plotly, Streamlit, PostgreSQL, MySQL, MongoDB
\end{itemize}

\vspace{-5pt}

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Fitin}{Jan 2026 -- Mar 2026}
    {ML \& Analytics Intern}{Bengaluru, India}
    \resumeItemListStart
      \resumeItem{Improved churn model performance by \textbf{18\% over baseline} (ROC-AUC 0.91) across \textbf{100K+ records} by engineering interaction features, applying SMOTE, and benchmarking 7 classifiers via 5-fold Stratified CV.}
      \resumeItem{Reduced stakeholder time-to-insight from days to \textbf{under 30 seconds} by shipping a 4-tier FastAPI scoring service and Streamlit dashboard with fully automated Airflow ingestion and batch inference.}
      \resumeItem{Delivered end-to-end pipeline using Python, XGBoost, Airflow, FastAPI, Streamlit, and PostgreSQL --- owning full implementation from raw data ingestion to production-ready scoring endpoint.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

\vspace{-5pt}

%-----------PROJECTS-----------
\section{Key Projects}
\resumeSubHeadingListStart

  \resumeProjectHeading
    {\textbf{SentinelML --- Production ML Monitoring \& Retraining System} $|$ \emph{Airflow, Prometheus, Grafana}}{\href{https://github.com/Kushagra651/Monitoring-pipeline}{GitHub} $|$ Jan 2025}
  \resumeItemListStart
    \resumeItem{Reduced model degradation across \textbf{7 drift types} by implementing KS-test and chi-squared drift detection, triggering Airflow-orchestrated retraining on threshold breach with zero manual intervention.}
    \resumeItem{Strengthened deployment safety via a 3-gate MLflow promotion system --- accuracy threshold, champion-challenger, stability check --- with symlink-based zero-downtime swaps and append-only audit logs.}
    \resumeItem{Improved observability by instrumenting FastAPI endpoints with Prometheus tracking p99 latency, prediction confidence, and per-class request volume visualised across Grafana dashboards.}
  \resumeItemListEnd

  \vspace{-3pt}

  \resumeProjectHeading
    {\textbf{MediFlow --- Hospital Resource Forecasting System} $|$ \emph{XGBoost, SARIMA, FastAPI, PuLP}}{\href{https://github.com/Kushagra651/MediFlow}{GitHub} $|$ Oct 2024}
  \resumeItemListStart
    \resumeItem{Achieved \textbf{RMSE 1.28} on 7-day patient inflow forecasting on synthetic EHR data by building a hybrid SARIMA--XGBoost pipeline with SHAP explainability across \textbf{5K+ records}.}
    \resumeItem{Reduced projected ICU overcapacity by \textbf{18\%} under resource-constrained scenarios using PuLP linear programming optimisation with hard capacity constraints.}
    \resumeItem{Surfaced forecasts via FastAPI and a real-time Streamlit--Plotly dashboard enabling interactive scenario planning with drill-down ICU risk and bed allocation views.}
  \resumeItemListEnd

  \vspace{-3pt}

  \resumeProjectHeading
    {\textbf{EnterpriseRAG --- Production Document Retrieval System} $|$ \emph{Qdrant, Ollama, Docker, RAG}}{\href{https://github.com/Kushagra651/Enterprise-RAG}{GitHub} $|$ Aug 2024}
  \resumeItemListStart
    \resumeItem{Improved retrieval Precision@5 from 0.62 to 0.81 across a 30-query evaluation set by building a metadata-filtered RAG pipeline using 768-dim Qdrant embeddings over \textbf{50+ enterprise documents}.}
    \resumeItem{Achieved \textbf{91\% query routing accuracy} across multi-domain queries via an LLM decomposition layer with parallel sub-query execution and targeted metadata filtering served through FastAPI.}
    \resumeItem{Engineered document ingestion processing \textbf{16 documents into 301 searchable chunks} with automated metadata extraction --- achieving \textbf{95\%+ classification accuracy} and \textbf{under 2s} query latency.}
  \resumeItemListEnd

\resumeSubHeadingListEnd

\vspace{-5pt}

%-----------ACHIEVEMENTS-----------
\section{Achievements}
\begin{itemize}[leftmargin=0.15in, itemsep=1pt, topsep=1pt, parsep=0pt]
  \resumeItem{Ranked \textbf{35th / 2,247} in Kaggle Spaceship Titanic using ensemble modelling, feature engineering, and cross-validation.}
  \resumeItem{Open-source contributor to \textbf{Giskard AI} --- merged Bias LLM Judge evaluation check for LLM reliability testing (PR \#2440).}
  \resumeItem{Publish technical blogs on ML systems, RAG pipelines, and MLOps on \href{https://substack.com/@kushagrabhargava}{Substack} \textbar{} \textbf{Oracle Data Science Professional} certified (2025).}
\end{itemize}

\end{document}
