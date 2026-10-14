# Awesome-Aviation-Predictive-Maintenance-Schedulers

## Top Aviation Predictive Maintenance Schedulers Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Fleet Health Analytics, RUL Prediction & MRO Optimization*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Aviation Predictive Maintenance Schedulers**. These tools enable airlines, MROs, and lessors to match parts fatigue data with upcoming flight lines—turning full-flight sensor data, maintenance logs, and component histories into actionable predictions that reduce unplanned maintenance and optimize aircraft availability.



**Examples** include Airbus Skywise, Boeing AnalytX, GE Digital Aviation, Lufthansa Technik AVIATAR, Collins Aerospace Ascentia, Rolls-Royce R2 Data Labs, Ramco Aviation, AMOS, Honeywell Forge Aviation, and Uptake Aviation (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, remaining-useful-life (RUL) prediction, and open MRO infrastructure—ideal for aviation engineers, data scientists, and developers seeking transparent, vendor-independent maintenance scheduling.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Airbus Skywise](https://www.skywise.com/en/digital-solutions/technical-operations/fleet-performance)**  

  Aviation data platform connecting **12,300+ aircraft** with **55,000+ users** worldwide. **Skywise Fleet Performance+** detects faults even before the aircraft triggers any alert, using in-flight sensor data and maintenance information. **S.FP+** includes **Natural Language Processing** that detects repetitive faults, identifies associated technical documentation, and determines a defect's most probable cause—significantly reducing investigation time. Powered by the **Digital Alliance** (Airbus, Delta Tech Ops, GE Aerospace, Liebherr, Collins) for nose-to-tail failure anticipation. ISO 27001:2022 certified .



- **[Boeing AnalytX](https://boeing.mediaroom.com/2018-09-04-Boeing-Expands-Australian-Data-Analytics-Services)**  

  Platform-agnostic data analytics engine providing predictive maintenance insights across Boeing and non-Boeing systems. Uses international fleet data patterns to provide strategic insights for smaller local fleets. Features **Airplane Health Management**, **Fuel Dashboard**, **Flight Planning**, and **In-Service Data Program**. Estimates airlines can save **2-2.5% of total global operating costs** (US$5M-$6B annually) .



- **[GE Digital Aviation (Maintenance Insight)](https://www.geaerospace.com/sites/default/files/2024-02/maintenance-insight-overview.pdf)**  

  Predictive maintenance platform built on Microsoft Power BI and Azure Machine Learning. Ingests full-flight data, classifies flight signatures, identifies root-cause issues, and delivers fleet health reports, atypical tails reports, and condition indicator charts. Airlines spent **$20.2 billion on unplanned maintenance in 2018**; **$10.3B could have been avoided** using data and analytics for predictive maintenance .



- **[Lufthansa Technik AVIATAR](https://newsroom.lufthansa-technik.com/download/401711ef-3f42-4b79-b34d-203ffa009a31/251215_pr_lufthansa-technik-frontier-dtoe_en.pdf)**  

  Digital Tech Ops ecosystem with **Predictive Health Analytics** (uses full-flight data to anticipate technical issues, transform unscheduled maintenance into scheduled), **Condition Monitoring** (real-time fleet technical status from multiple data sources), and **Technical Repetitives Examination (TRE)** — AI combined with engineering knowledge to analyze flight crew technical logbook write-ups. Rolled out at **20+ international airlines** across Airbus and Boeing types. Seamlessly integrates with AMOS and flydocs .



- **[Collins Aerospace Ascentia](https://www.nasdaq.com/articles/qatar-airways-selects-collins-aerospace-ascentia-optimize-boeing-787-fleet-maintenance)**  

  Analytics solution selected by **Qatar Airways** for its **52 Boeing 787 aircraft**. Harnesses aircraft sensor data, compares real-time information with historic fleet records and statistical models for continuous monitoring of system conditions. Generates predictive insights into component health, reduces unscheduled maintenance, minimizes downtime, optimizes resource allocation, and refines spare parts provisioning .



- **[Rolls-Royce R2 Data Labs (IntelligentEngine)](https://www.rolls-royce.com/media/our-stories/discover/2018/what-makes-the-intelligentengine-tick.aspx)**  

  Digital environment creating **Digital Twins** that replicate and simulate the full operational lifecycle of engines and fleets. Four capability areas: **Design optimisation** (simulate component designs in service), **Integrated lifing** (predict remaining life of engines/components), **Fleet planning** (analyze 25+ years of in-service data), and **MRO insight** (capture actual condition of used parts to inform improvements) .



- **[Ramco Aviation](https://www.ramco.com/blog/aviation/aviation-mro-software-digital-transformation-ramco)**  

  AI-powered MRO platform integrating maintenance, engineering, supply chain, finance, and compliance. Predictive analytics and real-time insights optimize planning and minimize errors. Paperless operations with mobile access for technicians. Integrated contract and compliance management ensures regulatory requirements are embedded in workflows .



- **[AMOS (Swiss AviationSoftware)](https://aeronewsglobal.com/ana-launches-multi-year-maintenance-system-modernization-initiative/)**  

  Industry-leading maintenance and engineering software selected by **ANA** for multi-year modernization, consolidating 10+ independent systems into a unified platform. Will integrate with **AVIATAR** and **flydocs** for complete digital tech ops ecosystem. Go-live projected for fiscal year 2027 .



- **[Honeywell Forge Aviation / Ensemble](https://www.honeywellaerospace.com/us/en/insights/articles/how-honeywell-ensemble-uses-ai-to-predict-engine-health)**  

  AI-powered engine health monitoring integrated with Honeywell's Maintenance Service Plan (MSP). **EngineCompressorAI algorithm** tracks vibration, inter-turbine temperature, engine pressures, and fuel consumption. Post-flight data transmitted to Honeywell Forge and CAMP for analysis. Case study: detected compressor issue **10 weeks before** an incident that caused a takeoff rejection .



- **[Uptake Aviation](https://uptake.com/)**  

  Predictive analytics platform for fleet maintenance. Identifies problems in real time without touching the vehicle, filters alerts by time/severity/location, and turns warranty data into dollars. **United Road** achieved **4x ROI** with increased fleet uptime. **Acquired by Bosch (March 2026)** to scale AI-powered fleet maintenance globally .



## Open-Source GitHub Projects



- **[GAIA (Digital Twin Pipeline)](https://github.com/esd-univr/GAIA)**  

  First comprehensive pipeline enabling creation of **digital twins** to support predictive maintenance in aviation (IEEE 2025, with Leonardo S.p.A.). Combines multi-physics modeling and data-driven techniques. Introduces **DSLG D/R dataset** specifically designed for landing gear system fault classification. Achieves **10.56% improvement** in fault classification accuracy vs. other augmentation methods. Code and dataset available on GitHub .



- **[NASA Prognostics Python Packages (progpy)](https://github.com/nasa/progpy)**  

  NASA's open-source Python framework for defining and building models and algorithms for **prognostics (computation of Remaining Useful Life)** of engineering systems. Provides models and algorithms suitable for use in prognostic applications. **121 GitHub stars**. Includes **Prognostic Model Package** (prog_models), **Prognostic Algorithm Package** (prog_algs), and **Prognostics As-A-Service (PaaS) Sandbox** .



- **[AI-PMS (AI Predictive Maintenance System)](https://github.com/jerry-felipe/AI-PredictiveMaintenanceSystem)**  

  Modular microservice using AI to predict aircraft system failures before they occur. Features **real-time data processing** (temperature, vibration, pressure), **predictive analytics** using ML models, **automated alert system**, **RESTful API** for fleet management system integration, and **Docker/Kubernetes** deployment. Tech stack: Java/Spring Boot, Python (TensorFlow/PyTorch), Oracle Database .



- **[OpenAirport](https://github.com/thunderai/openairport)**  

  Open-source **Computer Maintenance and Management System (CMMS)** designed from the ground up for airports. Modular architecture focused on FAA Part 139 requirements (sections 139.327, 333, 337, 339). Tracks discrepancies from global issues down to individual light fixtures. **Note**: Not completed—development underway, not ready for airport use .



- **[Apache OFBiz MRO Solution (HotWax Systems)](https://www.hotwaxsystems.com/industry-case-studies/manufacturing-maintenance-repair-overhaul-services-for-aviation-mro-defence-aerospace-using-apache-ofbiz)**  

  Bespoke MRO solution built on open-source **Apache OFBiz** platform. Features **traveler-based work order management** (sequence of operations, material requirements, sign-offs, documentation), **dependency-driven operation execution** (operations can begin only after others complete), **attribute-based inventory promising** (materials matched by condition, ownership, certification status), and **inventory visibility and traceability**. Significantly improved parts repair and maintenance turn-around time .



- **[AirNav Logistics](https://github.com/DP2-C1-027/AirNav-Logistics-C3)**  

  Web-based information system for airports managing **charter flight logistics**. Assists airports in managing flight logistics operations. Tech stack: Hack language .



- **[aviation-engine-maintenance-rag](https://github.com/suniltyagi/aviation-engine-maintenance-rag)**  

  Retrieval-Augmented Generation pipeline for **aircraft engine maintenance manuals (FAA)** enabling accurate Q&A. Python-based. Enables natural language querying of FAA maintenance documentation for troubleshooting and reference .



### Additional Strong Open-Source Options



- **[openairport_v3t](https://github.com/thunderai/openairport)** — Development branch of OpenAirport CMMS with modules for Part 139 compliance tracking .

- **[Airplane Manuals Collection](https://github.com/shiroinekotfs/airplane-manuals-collection)** — Collection of airplane manuals (3.39 GB). 14 GitHub stars .

- **[OOP-Aviation-Aircraft](https://github.com/michaelmml/OOP-Aviation-Aircraft)** — Object-oriented programming for aviation routes and aircraft utilization/maintenance forecasting .

- **[Awesome Prognostics Health Management](https://github.com/topics/prognostics-health-management)** — Curated collection of PHM papers, articles, and datasets for anticipating failures using sensor historical data .

- Community **n8n** workflows for maintenance alert routing and MRO scheduling automation.



**Frameworks for building custom systems**: Combine **NASA progpy** for RUL prediction models with **GAIA** for digital twin creation, **AI-PMS** for real-time sensor processing and alerting, **Apache OFBiz** for MRO work order management, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade aviation predictive maintenance platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Aviation maintenance systems must comply with airworthiness regulations (FAA, EASA, and equivalent authorities) and manufacturer maintenance programs. Predictive maintenance outputs are advisory—qualified maintenance personnel make final airworthiness determinations.

- **Open-source aviation MRO is early-stage.** OpenAirport is not completed and not ready for airport use . GAIA and NASA progpy are research frameworks, not production MRO platforms. Commercial platforms like AMOS, Skywise, and AVIATAR provide certified, production-grade capabilities that open-source alternatives do not yet match.

- **Full-flight data access is a competitive advantage.** Airlines and OEMs with exclusive access to complete sensor data streams (Airbus, Boeing, GE, Rolls-Royce) can train superior models. Open-source projects rely on public datasets (NASA C-MAPSS, FEMTO) or simulated data—generalization to specific fleets requires validation.

- **Regulatory acceptance matters.** Predictive maintenance recommendations must be integrated into approved maintenance programs. Using AI to adjust maintenance intervals requires regulatory approval (e.g., FAA/EASA certification of new maintenance procedures).

- Self-hosted open-source solutions require proper security hardening, domain expertise for model validation, and ongoing maintenance. Aviation safety-critical decisions demand rigorous validation before deployment.



---



**Made for aviation engineers, MRO managers, fleet reliability analysts, and developers building transparent predictive maintenance solutions.**  

Let's make Aviation Predictive Maintenance Schedulers more open, data-driven, and reliable.
