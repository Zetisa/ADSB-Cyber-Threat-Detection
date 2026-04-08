# ADSB-Cyber-Threat-Detection

**Data Analysis and Anomaly Detection Framework for ADS-B Flight Data.**

This project was developed during my internship at **AirNav Indonesia** as a research initiative into aviation cybersecurity. It focuses on analyzing publicly available **ADS-B (Automatic Dependent Surveillance-Broadcast)** data to detect potential cyber threats, data inconsistencies, and flight anomalies using Python-based data science techniques.

---

## Project Overview
As the backbone of modern air traffic surveillance, ADS-B is vulnerable to various cyber-attacks. This project provides a reliable pipeline to:

*   **Large-scale Processing:** Efficiently handle and clean massive flight datasets (70M+ rows).
*   **Threat Identification:** Detect flight patterns that deviate from normal operational standards (Anomalies).
*   **Security Analysis:** Analyze potential cyber-attacks such as **GPS Spoofing** or **Jamming** based on trajectory and signal inconsistencies.

**Built by:** Zetisa (Information Systems Student)  
**Context:** Internship Research Project @ AirNav Indonesia

---

## Features & Capabilities
*   **Big Data Optimization:** High-performance preprocessing and filtering for large datasets using **PyArrow** and **Parquet**.
*   **Trajectory Tracking:** Visualizes flight paths to detect "jumps" or illogical movements indicative of signal tampering.
*   **ML-based Anomaly Scoring:** Implements Unsupervised Learning models (e.g., **Isolation Forest**) to flag suspicious behaviors like altitude spoofing.
*   **Automated Insights:** Generates summary reports of detected threats for further aviation safety investigation.

---

## Tech Stack
*   **Language:** Python 3.x
*   **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, PyArrow.
*   **Data Handling:** Optimized for Large CSV/Parquet files.

---

## Getting Started

### 1. Prerequisites
Ensure you have the required libraries installed:

```bash
pip install pandas numpy matplotlib scikit-learn pyarrow
```

### 2. Preparing the Data
Place your raw ADS-B datasets (CSV or Parquet format) into the `data/` folder. This framework is compatible with open-access data (e.g., **OpenSky Network**). Ensure the dataset contains standard fields:

*   `icao24`, `callsign`, `latitude`, `longitude`, `altitude`, and `velocity`.

### 3. Running the Analysis
Open and run the main notebook to start the detection pipeline:

```bash
jupyter notebook notebooks/ADS_B_Anomaly_Detection.ipynb
```

---

## Results & Impact
*   Successfully processed **77 million rows** of flight data.
*   Identified and isolated over **4 million data anomalies**.
*   Achieved high detection accuracy for simulated spoofing patterns, providing a base for further cybersecurity research in aviation.
