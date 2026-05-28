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



---------------------------------------------------------
---------------------------------------------------------
DS latex


%-------------------------
% Resume — Kushagra Bhargava
% ATS-Optimized | Single Page | Data Scientist / GenAI
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
    \resumeItem{\textbf{Coursework:} Machine Learning, Statistics \& Probability, Linear Algebra, DSA, DBMS, Operating Systems}
  \resumeItemListEnd
\resumeSubHeadingListEnd

\vspace{-5pt}

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}, itemsep=1pt, topsep=1pt, parsep=0pt]\small
  \item \textbf{Languages:} Python, SQL, C++

  \item \textbf{Data Science \& ML:} scikit-learn, XGBoost, LightGBM, SARIMA, SMOTE, SHAP, hypothesis testing,
        A/B testing, feature engineering, ensemble methods, clustering (K-Means), time-series analysis

  \item \textbf{Data Analysis \& Visualization:} Pandas, NumPy, Matplotlib, Seaborn, Plotly Dash, cohort analysis,
        RFM segmentation, exploratory data analysis (EDA), statistical modelling

  \item \textbf{NLP \& LLMs:} HuggingFace Transformers, LoRA/PEFT, fine-tuning, RAG pipelines, prompt engineering

  \item \textbf{Deployment \& MLOps:} FastAPI, Docker, MLflow, Apache Airflow, Streamlit, CI/CD, Git

  \item \textbf{Databases \& Cloud:} PostgreSQL, MySQL, MongoDB, AWS EC2, S3, GitHub Actions
\end{itemize}

\vspace{-5pt}

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Fitin}{Jan 2026 -- Mar 2026}
    {Data Science Intern}{Bengaluru, India}
    \resumeItemListStart
      \resumeItem{Lifted churn prediction ROC-AUC to \textbf{0.85} (\textbf{15\% above baseline}) across \textbf{100K+ records} by conducting structured EDA, engineering interaction features, applying SMOTE, and evaluating 7 classifiers via 5-fold Stratified CV.}
      \resumeItem{Cut stakeholder time-to-insight from days to \textbf{under 30 seconds} by shipping an automated batch inference pipeline (Airflow + PostgreSQL) paired with a Streamlit dashboard exposing churn scores and segment breakdowns.}
      \resumeItem{Translated model outputs into actionable business narratives using SHAP summary and waterfall plots, surfacing top revenue-at-risk drivers for non-technical stakeholders.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

\vspace{-5pt}

%-----------PROJECTS-----------
%-----------PROJECTS-----------
\section{Key Projects}
\resumeSubHeadingListStart

  \resumeProjectHeading
    {\textbf{RevenueLens --- E-Commerce Customer Analytics \& Churn Prediction} $|$ \emph{XGBoost, K-Means, SHAP}}{\href{https://github.com/Kushagra651/}{GitHub} $|$ Mar 2026}
  \resumeItemListStart
    \resumeItem{Merged \textbf{8 relational tables} from the Olist dataset (\textbf{100K+ orders}) and conducted EDA to surface revenue trends, delivery lag patterns, and category-level drop-offs.}
    \resumeItem{Segmented customers into Champions, At-Risk, and Lost cohorts via RFM feature engineering and K-Means (elbow + silhouette validated); trained an XGBoost churn classifier with SHAP-driven revenue-at-risk narratives.}
    \resumeItem{Shipped a Plotly Dash dashboard with cohort retention heatmaps, a churn risk leaderboard, and actionable recommendation cards; deployed FastAPI inference endpoint via Docker on Render.}
  \resumeItemListEnd

  \vspace{-3pt}

  \resumeProjectHeading
    {\textbf{MediFlow --- Healthcare Demand Forecasting \& Resource Optimisation} $|$ \emph{XGBoost, SHAP, PuLP}}{\href{https://github.com/Kushagra651/MediFlow}{GitHub} $|$ Nov 2025}
  \resumeItemListStart
    \resumeItem{Forecasted 7-day patient inflow with \textbf{RMSE 1.28} across \textbf{5K+ EHR records} by decomposing admission seasonality and ensembling SARIMA residuals with XGBoost on lag and rolling-window features.}
    \resumeItem{Identified top 6 admission drivers via SHAP feature importance, translating statistical outputs into clinical risk narratives for non-technical stakeholders.}
    \resumeItem{Cut projected ICU overcapacity by \textbf{18\%} using PuLP linear programming under hard capacity constraints; surfaced scenario plans via an interactive Streamlit--Plotly dashboard.}
  \resumeItemListEnd

  \vspace{-3pt}

  \resumeProjectHeading
    {\textbf{LexRA --- Domain-Adapted Legal Reasoning LLM} $|$ \emph{HuggingFace, LoRA/PEFT, bitsandbytes}}{\href{https://github.com/Kushagra651/}{GitHub} $|$ Jan 2026}
  \resumeItemListStart
    \resumeItem{Fine-tuned TinyLlama-1.1B on \textbf{22K+ Supreme Court judgements} via LoRA/PEFT, cutting trainable parameters by \textbf{94\%}; 4-bit NF4 quantisation reduced GPU memory from 4\,GB to $\sim$700\,MB.}
    \resumeItem{Achieved \textbf{52.8\% perplexity reduction} (6.51 $\to$ 3.07) on held-out legal text, quantifying domain adaptation gain over the base model on a structured evaluation set.}
    \resumeItem{Deployed on HuggingFace Spaces with a live base-vs-fine-tuned comparison interface for interactive legal clause reasoning.}
  \resumeItemListEnd

\resumeSubHeadingListEnd
%-----------ACHIEVEMENTS-----------
\section{Achievements}
\begin{itemize}[leftmargin=0.15in, itemsep=1pt, topsep=1pt, parsep=0pt]
  \resumeItem{Ranked \textbf{35th / 2,247} in Kaggle Spaceship Titanic using ensemble modelling, feature engineering, and cross-validation.}
  \resumeItem{Open-source contributor to \textbf{Giskard AI} --- merged Bias LLM Judge evaluation check for LLM reliability testing (PR \#2440).}
  \resumeItem{Publish technical blogs on data science, ML systems, and LLMs on \href{https://substack.com/@kushagrabhargava}{Substack} \textbar{} \textbf{Oracle Data Science Professional} certified (2025).}
\end{itemize}

\end{document}
-----------------------------------------------------------------------
-----------------------------------------------------------------------
-----------------------------------------------------------------------
