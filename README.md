# Awesome Aviation Predictive Maintenance Schedulers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of production-grade SaaS platforms, enterprise MRO suites, and open-source GitHub projects for **Aviation Predictive Maintenance Schedulers**, fleet health analytics, Remaining Useful Life (RUL) estimation, and condition-based aircraft maintenance.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ishandutta2007/Awesome-Aviation-Predictive-Maintenance-Schedulers/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ishandutta2007/Awesome-Aviation-Predictive-Maintenance-Schedulers/graphs/commit-activity)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/ishandutta2007/Awesome-Aviation-Predictive-Maintenance-Schedulers/blob/main/README.md#how-to-contribute)
[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Aviation-Predictive-Maintenance-Schedulers.svg?style=social&label=Star)](https://github.com/ishandutta2007/Awesome-Aviation-Predictive-Maintenance-Schedulers/stargazers)

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Commercial Enterprise Platforms](#saas--commercial-enterprise-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Key Industry Datasets & Benchmarks](#key-industry-datasets--benchmarks)
- [Architecture Blueprint for Custom Schedulers](#architecture-blueprint-for-custom-schedulers)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & Regulatory Notice](#disclaimer--regulatory-notice)

---

## Sector Overview & Market Dynamics

The global **aviation predictive maintenance market** is valued at approximately **$4.2 billion to $5.5 billion in 2025–2026** and is projected to surpass **$6.9 billion before 2030**, expanding at a compound annual growth rate (CAGR) of over 11%.

The sector exhibits **moderate concentration at the top**—dominated by heavyweight aerospace OEMs and engine manufacturers (such as GE Aerospace, RTX Collins Aerospace, Boeing, Airbus, and Rolls-Royce) that bundle proprietary predictive analytics into long-term aftermarket flight-hour and MRO support contracts—while remaining **highly fragmented across independent MRO software, specialized diagnostic IoT tools, and modular fleet scheduling analytics** where airlines operating heterogeneous, multi-vendor fleets integrate neutral third-party systems.

---

## SaaS & Commercial Enterprise Platforms

The table below catalogs leading commercial SaaS platforms and enterprise MRO suites powering predictive health analytics, fleet scheduling, and aircraft turnaround optimization. Entries are sorted descending by the vendor's scale (**Market Valuation / Annual Revenue**).

| Platform | Provider / Parent Organization | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limits | Core Focus & Predictive Capabilities |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[GE Digital Aviation (Maintenance Insight)](https://www.geaerospace.com/sites/default/files/2024-02/maintenance-insight-overview.pdf)** | GE Aerospace (NYSE: GE) | ~$315B Market Cap / $38B+ Rev | From $1,500/aircraft/month (base fleet analytics tier) | 30-day guided Proof of Concept (PoC) trial on up to 5 aircraft tails | Full-flight sensor analytics, condition indicators, root-cause diagnosis, and atypical flight signature detection built on Microsoft Azure ML. |
| **[Collins Aerospace Ascentia](https://www.nasdaq.com/articles/qatar-airways-selects-collins-aerospace-ascentia-optimize-boeing-787-fleet-maintenance)** | RTX Corporation (NYSE: RTX) | ~$250B Market Cap / $74B+ Rev | From $2,200/tail/month (entry sensor analytics package) | 60-day enterprise evaluation trial limited to 2 sub-fleets / 10 aircraft | Continuous flight condition monitoring, statistical degradation modeling, and proactive component health alerts for commercial widebody and narrowbody fleets. |
| **[Airbus Skywise](https://www.skywise.com/en/digital-solutions/technical-operations/fleet-performance)** | Airbus SE (EPA: AIR) | ~$167B Market Cap (€150B) / €65B+ Rev | **Skywise Core:** $0 (data-sharing agreement); **Fleet Performance+:** From $1,800/aircraft/month | **Free forever (Skywise Core)**: Full platform infrastructure and OEM benchmark analytics access in exchange for sharing fleet operational data; paid modules provide 30-day pilot testing | OEM digital aircraft backbone tracking 12,300+ aircraft with NLP for defect logbooks, fault anticipation, and maintenance scheduling. |
| **[Boeing AnalytX](https://boeing.mediaroom.com/2018-09-04-Boeing-Expands-Australian-Data-Analytics-Services)** | The Boeing Company (NYSE: BA) | ~$148B Market Cap / $89.5B Rev | From $2,000/aircraft/month (Airplane Health Management suite) | 30-day technical trial program restricted to 1 aircraft type / 5 tail numbers | Airplane Health Management (AHM), predictive alert management, fuel analytics, and global fleet operational benchmarking. |
| **[Honeywell Forge Aviation / Ensemble](https://www.honeywellaerospace.com/us/en/insights/articles/how-honeywell-ensemble-uses-ai-to-predict-engine-health)** | Honeywell International (NASDAQ: HON) | ~$67B Market Cap / $38B+ Rev | From $1,250/engine/month (integrated into Honeywell MSP) | 30-day pilot trial limited to 4 engine tails / APUs with historical flight replay | EngineCompressorAI algorithm tracking vibrations, inter-turbine temperatures, pressures, and fuel burns to forecast failures up to 10 weeks prior. |
| **[Uptake Aviation](https://uptake.com/)** | Robert Bosch GmbH (Acquired March 2026) | €91B Parent Annual Revenue ($98B+) | From $120/monitored component/month (commercial fleet telematics package) | 14-day full feature trial capped at 10 tracked assets / components | Real-time sensor anomaly scoring, multi-sensor telematics correlation, and automated work order dispatching. |
| **[Lufthansa Technik AVIATAR](https://newsroom.lufthansa-technik.com/download/401711ef-3f42-4b79-b34d-203ffa009a31/251215_pr_lufthansa-technik-frontier-dtoe_en.pdf)** | Lufthansa Group (ETR: LHA) | €8.8B Parent Market Cap / €8B+ MRO Rev | From $1,400/aircraft/month (Condition Monitoring & TRE module tier) | 45-day managed PoC trial capped at 10 aircraft and 3 predictive modules | Independent airline tech ops ecosystem featuring Condition Monitoring, Predictive Health Analytics, and AI Technical Repetitives Examination (TRE). |
| **[Rolls-Royce IntelligentEngine](https://www.rolls-royce.com/media/our-stories/discover/2018/what-makes-the-intelligentengine-tick.aspx)** | Rolls-Royce Holdings (LSE: RR) | ~$155B Market Cap (£112B) / £16.5B Rev | From $250/flight-hour (bundled in TotalCare / IntelligentEngine contracts) | 90-day shadow telemetry evaluation on up to 2 engine test-beds | Digital Twins modeling complete operational lifecycles, integrated lifing calculations, RUL estimation, and smart line-replacement provisioning. |
| **[AMOS (Swiss AviationSoftware)](https://aeronewsglobal.com/ana-launches-multi-year-maintenance-system-modernization-initiative/)** | Swiss AviationSoftware AG (Lufthansa Technik) | €65M Annual Revenue / 320+ Staff | From €90,000/year (base cloud tier for regional operators, ~€350/user/month) | 30-day sandbox demo environment with preloaded sample fleet data (up to 5 concurrent user accounts) | Industry-standard Maintenance, Repair, and Overhaul (MRO) ERP suite coordinating CAMO compliance, work orders, material supply chains, and line maintenance schedules. |
| **[Ramco Aviation](https://www.ramco.com/blog/aviation/aviation-mro-software-digital-transformation-ramco)** | Ramco Systems (NSE: RAMCOSYS) | ~$245M Market Cap (₹2,050 Cr) / $80M Rev | From $185/concurrent user/month (minimum 25 seats base contract) | 30-day interactive staging demo environment limited to 3 user licenses | End-to-end AI-powered MRO and ERP platform managing traveler-based execution, maintenance forecasting, component tracking, and compliance. |

---

## Open-Source GitHub Projects

Explore community-driven, transparent, and self-hosted tools for Remaining Useful Life (RUL) modeling, C-MAPSS benchmark training, digital twins, and MRO scheduling. 

Repositories are sorted descending by GitHub stargazers count, with real-time social badges linking directly to their respective stargazers pages.

- **[PyTorch-Transformer-for-RUL-Prediction](https://github.com/jiaxiang-cheng/PyTorch-Transformer-for-RUL-Prediction)** [![GitHub stars](https://img.shields.io/github/stars/jiaxiang-cheng/PyTorch-Transformer-for-RUL-Prediction?style=social&color=white)](https://github.com/jiaxiang-cheng/PyTorch-Transformer-for-RUL-Prediction/stargazers)  
  *PyTorch Transformer Architecture for Turbofan Remaining Useful Life (RUL) Prediction.*  
  State-of-the-art transformer encoder architecture enhanced with gated convolutional units for turbofan engine degradation estimation on the NASA C-MAPSS dataset.

- **[PyTorch-LSTM-for-RUL-Prediction](https://github.com/jiaxiang-cheng/PyTorch-LSTM-for-RUL-Prediction)** [![GitHub stars](https://img.shields.io/github/stars/jiaxiang-cheng/PyTorch-LSTM-for-RUL-Prediction?style=social&color=white)](https://github.com/jiaxiang-cheng/PyTorch-LSTM-for-RUL-Prediction/stargazers)  
  *Deep Recurrent Neural Network for CMAPSS Engine Degradation.*  
  PyTorch implementation of Long Short-Term Memory (LSTM) sequence networks for Remaining Useful Life prediction across multi-sensor turbofan degradation time-series.

- **[Predictive-Maintenance-of-Aircraft-Engine](https://github.com/archd3sai/Predictive-Maintenance-of-Aircraft-Engine)** [![GitHub stars](https://img.shields.io/github/stars/archd3sai/Predictive-Maintenance-of-Aircraft-Engine?style=social&color=white)](https://github.com/archd3sai/Predictive-Maintenance-of-Aircraft-Engine/stargazers)  
  *End-to-End Aircraft Engine Failure Prediction.*  
  Comprehensive machine learning pipeline applying multiple predictive maintenance classifiers and regression models to detect impending turbofan engine failures.

- **[exploring-nasas-turbofan-dataset](https://github.com/kpeters/exploring-nasas-turbofan-dataset)** [![GitHub stars](https://img.shields.io/github/stars/kpeters/exploring-nasas-turbofan-dataset?style=social&color=white)](https://github.com/kpeters/exploring-nasas-turbofan-dataset/stargazers)  
  *Comparative Benchmark Suite for NASA Turbofan Telemetry.*  
  Collection of exploratory data analysis (EDA), feature engineering pipelines, and regression models benchmarked against the standard NASA C-MAPSS dataset.

- **[progpy (NASA Prognostics Python Packages)](https://github.com/nasa/progpy)** [![GitHub stars](https://img.shields.io/github/stars/nasa/progpy?style=social&color=white)](https://github.com/nasa/progpy/stargazers)  
  *NASA's Official Unified Framework for Prognostics & Health Management.*  
  Unified Python architecture defining degradation models, state estimation (EKF, UKF, Particle Filters), and Remaining Useful Life (RUL) computation algorithms for engineering systems.

- **[prog_models (NASA Prognostics Model Package)](https://github.com/nasa/prog_models)** [![GitHub stars](https://img.shields.io/github/stars/nasa/prog_models?style=social&color=white)](https://github.com/nasa/prog_models/stargazers)  
  *Physics-Informed & Data-Driven Component Degradation Models.*  
  NASA's specialized library for physics-based and data-driven modeling of aircraft components, batteries, valves, actuators, and rotating turbomachinery.

- **[Turbofan-engine-RUL-prediction](https://github.com/zhmou/Turbofan-engine-RUL-prediction)** [![GitHub stars](https://img.shields.io/github/stars/zhmou/Turbofan-engine-RUL-prediction?style=social&color=white)](https://github.com/zhmou/Turbofan-engine-RUL-prediction/stargazers)  
  *Attention-Mechanism Neural Networks for Turbofan RUL Estimation.*  
  Reproducible deep learning research benchmark leveraging self-attention mechanisms to isolate critical sensor cycles during engine degradation.

- **[N-CMAPSS_DL](https://github.com/mohyunho/N-CMAPSS_DL)** [![GitHub stars](https://img.shields.io/github/stars/mohyunho/N-CMAPSS_DL?style=social&color=white)](https://github.com/mohyunho/N-CMAPSS_DL/stargazers)  
  *Next-Generation Commercial Aircraft Turbofan Degradation Pipeline.*  
  Data preparation, feature extraction, and deep learning architectures tailored for NASA's new New-CMAPSS (N-CMAPSS) realistic commercial flight-cycle dataset.

- **[airplane-manual-collection](https://github.com/shiroinekotfs/airplane-manual-collection)** [![GitHub stars](https://img.shields.io/github/stars/shiroinekotfs/airplane-manual-collection?style=social&color=white)](https://github.com/shiroinekotfs/airplane-manual-collection/stargazers)  
  *Comprehensive Aircraft Maintenance Documentation & Manual Repository.*  
  Curated archive (3.4 GB) of aircraft operations and maintenance flight manuals, providing essential baseline domain reference material for technical teams.

- **[PyTorch-CNN-for-RUL-Prediction](https://github.com/jiaxiang-cheng/PyTorch-CNN-for-RUL-Prediction)** [![GitHub stars](https://img.shields.io/github/stars/jiaxiang-cheng/PyTorch-CNN-for-RUL-Prediction?style=social&color=white)](https://github.com/jiaxiang-cheng/PyTorch-CNN-for-RUL-Prediction/stargazers)  
  *Deep Convolutional Neural Networks for RUL Estimation.*  
  Convolutional feature extractor in PyTorch implementing multi-scale 1D convolutions across raw time-series sensor feeds for aircraft maintenance forecasting.

- **[Turbofan-Federated-Learning-POC](https://github.com/matthiaslau/Turbofan-Federated-Learning-POC)** [![GitHub stars](https://img.shields.io/github/stars/matthiaslau/Turbofan-Federated-Learning-POC?style=social&color=white)](https://github.com/matthiaslau/Turbofan-Federated-Learning-POC/stargazers)  
  *Privacy-Preserving Collaborative Fleet Prognostics.*  
  Federated learning proof-of-concept demonstrating how competing airlines and operators can jointly train robust RUL models without sharing proprietary in-flight telemetry.

- **[c-mapss-full-dataset-](https://github.com/huster123/c-mapss-full-dataset-)** [![GitHub stars](https://img.shields.io/github/stars/huster123/c-mapss-full-dataset-?style=social&color=white)](https://github.com/huster123/c-mapss-full-dataset-/stargazers)  
  *1D CNN Training Models for Aviation Turbofans.*  
  End-to-end 1D convolutional neural network implementation for engine lifecycle forecasting trained on all sub-datasets (FD001–FD004).

- **[Predicting-of-Turbofan-Engine-Degradation-Using-the-NASA-C-MAPSS-Dataset](https://github.com/shining0611armor/Predicting-of-Turbofan-Engine-Degradation-Using-the-NASA-C-MAPSS-Dataset)** [![GitHub stars](https://img.shields.io/github/stars/shining0611armor/Predicting-of-Turbofan-Engine-Degradation-Using-the-NASA-C-MAPSS-Dataset?style=social&color=white)](https://github.com/shining0611armor/Predicting-of-Turbofan-Engine-Degradation-Using-the-NASA-C-MAPSS-Dataset/stargazers)  
  *Reproducible Benchmarking Pipeline for C-MAPSS.*  
  Step-by-step pipeline implementing modern feature selection, outlier cleaning, and multi-regressor comparison for engine wear prognosis.

- **[prog_algs (NASA Prognostics Algorithms Package)](https://github.com/nasa/prog_algs)** [![GitHub stars](https://img.shields.io/github/stars/nasa/prog_algs?style=social&color=white)](https://github.com/nasa/prog_algs/stargazers)  
  *Estimation, Prediction, and Uncertainty Quantification Algorithms.*  
  NASA algorithm repository supplying Unscented Kalman Filters (UKF), Monte Carlo predictors, and Bayesian estimation tools designed for prognostic models.

- **[predictive-maintenance-lstm](https://github.com/sabderra/predictive-maintenance-lstm)** [![GitHub stars](https://img.shields.io/github/stars/sabderra/predictive-maintenance-lstm?style=social&color=white)](https://github.com/sabderra/predictive-maintenance-lstm/stargazers)  
  *Keras / TensorFlow LSTM Sequence Modeling for Turbofans.*  
  Clean and accessible notebook pipeline demonstrating sequence framing, windowing, and LSTM regression for remaining engine life.

- **[turbofan-remaining-life-prediction](https://github.com/delta1epsilon/turbofan-remaining-life-prediction)** [![GitHub stars](https://img.shields.io/github/stars/delta1epsilon/turbofan-remaining-life-prediction?style=social&color=white)](https://github.com/delta1epsilon/turbofan-remaining-life-prediction/stargazers)  
  *Gradient Boosting & Random Forest Engine Life Regression.*  
  Comparative tree-based regression implementation evaluating XGBoost, Random Forests, and LightGBM for turbofan maintenance intervals.

- **[predictive-maintenance-spark](https://github.com/sabderra/predictive-maintenance-spark)** [![GitHub stars](https://img.shields.io/github/stars/sabderra/predictive-maintenance-spark?style=social&color=white)](https://github.com/sabderra/predictive-maintenance-spark/stargazers)  
  *Distributed Streaming Telemetry Processing with Apache Spark & Kafka.*  
  Scalable big data streaming architecture processing continuous aircraft engine telemetry with Spark ML and Structured Streaming.

- **[AI-PMS (AI Predictive Maintenance System)](https://github.com/jerry-felipe/AI-PredictiveMaintenanceSystem)** [![GitHub stars](https://img.shields.io/github/stars/jerry-felipe/AI-PredictiveMaintenanceSystem?style=social&color=white)](https://github.com/jerry-felipe/AI-PredictiveMaintenanceSystem/stargazers)  
  *Microservices Architecture for Fleet Telemetry & Alerts.*  
  Modular containerized microservices (Java Spring Boot, Python PyTorch/TensorFlow, Docker) processing real-time sensor streams and dispatching automated maintenance alerts.

- **[predictive-maintenance-mlops](https://github.com/MuhammedSinanHQ/predictive-maintenance-mlops)** [![GitHub stars](https://img.shields.io/github/stars/MuhammedSinanHQ/predictive-maintenance-mlops?style=social&color=white)](https://github.com/MuhammedSinanHQ/predictive-maintenance-mlops/stargazers)  
  *Production-Ready MLOps Pipeline with FastAPI Inference.*  
  End-to-end MLOps workflow covering automated feature validation, model tracking, containerization, and a low-latency FastAPI inference service for turbofan RUL.

- **[openairport](https://github.com/thunderai/openairport)** [![GitHub stars](https://img.shields.io/github/stars/thunderai/openairport?style=social&color=white)](https://github.com/thunderai/openairport/stargazers)  
  *Open-Source Airfield & Airport CMMS.*  
  Open-source Computerized Maintenance Management System tailored to FAA Part 139 airfield operations, tracking discrepancies across lighting and pavement assets.

- **[aviation-engine-maintenance-rag](https://github.com/suniltyagi/aviation-engine-maintenance-rag)** [![GitHub stars](https://img.shields.io/github/stars/suniltyagi/aviation-engine-maintenance-rag?style=social&color=white)](https://github.com/suniltyagi/aviation-engine-maintenance-rag/stargazers)  
  *RAG Pipeline for FAA Aircraft Engine Maintenance Manuals.*  
  Retrieval-Augmented Generation (RAG) assistant indexing regulatory documents, FAA repair manuals, and airworthiness directives for instant technician Q&A.

- **[GAIA (Digital Twin Pipeline)](https://github.com/esd-univr/GAIA)** [![GitHub stars](https://img.shields.io/github/stars/esd-univr/GAIA?style=social&color=white)](https://github.com/esd-univr/GAIA/stargazers)  
  *Digital Twin Pipeline for Landing Gear Fault Diagnosis.*  
  Physics-informed digital twin pipeline (developed in collaboration with Leonardo S.p.A.) featuring the DSLG D/R landing gear dataset for fault classification.

- **[OOP-Aviation-Aircraft](https://github.com/michaelmml/OOP-Aviation-Aircraft)** [![GitHub stars](https://img.shields.io/github/stars/michaelmml/OOP-Aviation-Aircraft?style=social&color=white)](https://github.com/michaelmml/OOP-Aviation-Aircraft/stargazers)  
  *Aviation Fleet Utilization & Maintenance Scheduler.*  
  Object-oriented Python library modeling route planning, aircraft rotations, line maintenance scheduling, and utilization forecasting.

- **[AirNav-Logistics-C3](https://github.com/DP2-C1-027/AirNav-Logistics-C3)** [![GitHub stars](https://img.shields.io/github/stars/DP2-C1-027/AirNav-Logistics-C3?style=social&color=white)](https://github.com/DP2-C1-027/AirNav-Logistics-C3/stargazers)  
  *Airport Charter Logistics & Gate Management System.*  
  Web management application designed to organize flight operations, ground handling, and turnaround logistics.

- **[Apache OFBiz Aviation MRO Framework](https://www.hotwaxsystems.com/industry-case-studies/manufacturing-maintenance-repair-overhaul-services-for-aviation-mro-defence-aerospace-using-apache-ofbiz)** [![Open-Source Guide](https://img.shields.io/badge/Guide-MRO%20Framework-blue.svg?style=social)](https://www.hotwaxsystems.com/industry-case-studies/manufacturing-maintenance-repair-overhaul-services-for-aviation-mro-defence-aerospace-using-apache-ofbiz)  
  *Enterprise Work Order & Traveler Routing Architecture.*  
  Open-source enterprise resource framework providing dependency-driven operation scheduling, certified inventory promising, and traveler execution for heavy aviation MROs.

---

## Key Industry Datasets & Benchmarks

Model training and validation rely on recognized aviation industry telemetry datasets:

- **NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)**: The gold-standard dataset covering 4 degradation scenarios (FD001–FD004) under various operating conditions and fault modes.
- **NASA N-CMAPSS**: Next-generation dataset capturing realistic flight-envelope transitions, altitude variances, and multi-subsystem degradation.
- **DSLG D/R (Leonardo S.p.A. / GAIA)**: Real and synthetic time-series sensor traces for commercial aircraft landing gear retraction/extension anomalies.
- **FEMTO Bearing Dataset**: Experimental bearing run-to-failure vibration data widely used for rotary component degradation validation.

---

## Architecture Blueprint for Custom Schedulers

```
   ┌────────────────────────────────────────────────────────┐
   │        In-Flight Telemetry & QAR Data Streams          │
   └──────────────────────────┬─────────────────────────────┘
                              │ (Kafka / MQTT)
                              ▼
   ┌────────────────────────────────────────────────────────┐
   │   Stream Processing & Feature Engineering (Spark/Flink)│
   └──────────────────────────┬─────────────────────────────┘
                              │
               ┌──────────────┴──────────────┐
               ▼                             ▼
 ┌───────────────────────────┐ ┌───────────────────────────┐
 │   RUL & Prognostic Models │ │ Digital Twin Simulation   │
 │   (NASA progpy / PyTorch) │ │ (GAIA / Multiphysics)     │
 └─────────────┬─────────────┘ └─────────────┬─────────────┘
               └──────────────┬──────────────┘
                              ▼
   ┌────────────────────────────────────────────────────────┐
   │     Optimization & Constraint Scheduling Engine        │
   │       (Flight lines, AOG Risk, Crew & Hangar slots)    │
   └──────────────────────────┬─────────────────────────────┘
                              ▼
   ┌────────────────────────────────────────────────────────┐
   │      MRO Work Orders & Discrepancy Tracking (ERP)      │
   │            (AMOS / Apache OFBiz / CMMS)                │
   └────────────────────────────────────────────────────────┘
```

---

## How to Contribute

Contributions are highly appreciated! Help keep this ecosystem comprehensive, current, and valuable to aerospace engineers and developers worldwide:

1. **Fork the repository** to your personal GitHub account.
2. **Add or refine an entry** in `README.md`:
   - For **SaaS platforms**, ensure starting tier pricing, free trial duration/limits, and vendor valuation/revenue figures are included.
   - For **Open-Source projects**, include the repository link, description, and the social stargazers badge linked to `/stargazers`.
3. Verify formatting and alphabetical or metric-based sorting.
4. **Submit a Pull Request (PR)** with a clear explanation of your additions.

---

## Disclaimer & Regulatory Notice

- **Information Only**: This repository is a community-curated directory compiled for technical research, benchmarking, and architectural evaluation. It does not constitute formal operational or airworthiness advice.
- **Regulatory Compliance**: All modifications to aircraft maintenance schedules, interval escalations, and line operations must comply with certified airworthiness authorities (FAA, EASA, CAAC, UK CAA) and approved Aircraft Maintenance Programs (AMP).
- **Advisory Role**: Machine learning predictions and RUL estimations are advisory decision-support tools. Certified licensed aircraft maintenance engineers (LAME / A&P mechanics) retain final authority on airworthiness and release to service (CRS).

---

<sub>Maintained by [ishandutta2007](https://github.com/ishandutta2007). Star the repository if you find it helpful!</sub>
