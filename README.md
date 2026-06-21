🌊 Ocean Wave Anomaly Detection in Thai Waters using Unsupervised Deep Learning
This repository contains the source code and methodology for an AI-driven anomaly detection system for ocean wave conditions in the Gulf of Thailand and Andaman Sea.

Due to the absence of continuous ground-truth buoy observations in this region, this project leverages ERA5 reanalysis data and state-of-the-art unsupervised deep learning to identify unusual or extreme marine conditions.

📌 Project Overview
Objective: Detect and flag spatio-temporal anomalies in ocean wave and atmospheric patterns to improve maritime safety and climate monitoring.

Data Sources: * Primary: Multi-decade hourly ERA5 reanalysis data (Wave height, wind speed, etc.).

Validation: IBTrACS (International Best Track Archive for Climate Stewardship) tropical cyclone database.

Methodology: Unsupervised Deep Learning models trained on high-resolution spatio-temporal datasets to learn "normal" sea behaviors and detect deviations.

Infrastructure: Powered by Chalawan HPC/GPU resources to handle intensive deep learning training on massive climate datasets.

🛠️ Key Features
Data Pipelines: Automated preprocessing of high-resolution ERA5 NetCDF/GRIB datasets.

Spatio-Temporal Modeling: Deep learning architecture designed to capture complex ocean-atmosphere interactions over time and space.

Validation Framework: Cross-referencing detected anomalies with historical storm events for reliable performance assessment.
