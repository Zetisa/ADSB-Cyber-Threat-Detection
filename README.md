\# 🛡️ ADS-B Cyber Threat Detection using Machine Learning



\## 📌 Project Overview

Project ini bertujuan untuk mendeteksi anomali dan serangan siber (\*Jamming\* \& \*Spoofing\*) pada data penerbangan \*\*Automatic Dependent Surveillance-Broadcast (ADS-B)\*\*. Menggunakan pendekatan \*Machine Learning\* (Unsupervised Learning), sistem ini mampu memproses dan menganalisis \*\*77 Juta baris data penerbangan\*\* dalam waktu kurang dari 6 menit menggunakan teknik \*Data Chunking\*.



\## 🛠️ Tech Stack \& Libraries

\* \*\*Language:\*\* Python

\* \*\*Data Processing:\*\* Pandas, NumPy, PyArrow (Parquet)

\* \*\*Machine Learning:\*\* Scikit-Learn (Isolation Forest, LOF, One-Class SVM)

\* \*\*Visualization:\*\* Plotly Express, Matplotlib, Seaborn



\## ⚙️ Methodology \& Pipeline

1\. \*\*Data Preprocessing \& Feature Engineering:\*\* Ekstraksi fitur fisika spasial (Haversine distance, perhitungan jeda waktu, elevasi, dll).

2\. \*\*Pseudo-Ground Truth Generation:\*\* Pembuatan label anomali berbasis \*Rule-Based Heuristic\* (Hukum Fisika Kinematik).

3\. \*\*Model Benchmarking:\*\* Komparasi 3 algoritma deteksi anomali:

&#x20;  \* 🏆 \*\*Isolation Forest\*\* (Dipilih sebagai model final)

&#x20;  \* ❌ Local Outlier Factor (LOF)

&#x20;  \* ❌ One-Class SVM

4\. \*\*Mass Inference:\*\* Pemindaian 77 Juta baris data organik menggunakan model terpilih.



\## 📊 Key Results

\* \*\*Akurasi Model:\*\* \*\*99%\*\* (berdasarkan evaluasi komparatif fisika absolut).

\* \*\*Total Deteksi:\*\* Berhasil mengisolasi \*\*\~4.2 Juta anomali\*\* (5.5% rasio ancaman) dari total 77 Juta data.

\* \*\*Dominasi Serangan:\*\* \*Jamming\* menjadi vektor serangan paling dominan dibandingkan \*Spoofing\*.



\## 📁 Repository Structure

\* `ADSB\_Anomaly\_Detection\_Final.ipynb` : Notebook utama berisi seluruh pipeline dari EDA hingga evaluasi model.

\* `SAMPLE\_HACKER\_DETECTED.csv` : Sampel hasil ekstraksi anomali yang ditangkap oleh AI.

\* `requirements.txt` : Daftar library yang dibutuhkan untuk menjalankan project ini.



\*\*Dataset Note:\*\* Mengingat batasan ukuran file GitHub (Max 100MB), file dataset utuh (2.2 GB) tidak disertakan di repository ini. Untuk menjalankan notebook secara penuh (Mass Inference), silakan unduh file `.parquet` melalui \*\*\[https://drive.google.com/file/d/129foVnBrO1WpVkudPNTJA9Es0p_6qW66/view?usp=sharing]\*\*.



\---

\*Project ini dikembangkan sebagai bagian dari tugas akhir (Skripsi) Program Studi Sistem Informasi.\*

\# 🛡️ ADS-B Cyber Threat Detection using Machine Learning



\## 📌 Project Overview

Project ini bertujuan untuk mendeteksi anomali dan serangan siber (\*Jamming\* \& \*Spoofing\*) pada data penerbangan \*\*Automatic Dependent Surveillance-Broadcast (ADS-B)\*\*. Menggunakan pendekatan \*Machine Learning\* (Unsupervised Learning), sistem ini mampu memproses dan menganalisis \*\*77 Juta baris data penerbangan\*\* dalam waktu kurang dari 6 menit menggunakan teknik \*Data Chunking\*.



\## 🛠️ Tech Stack \& Libraries

\* \*\*Language:\*\* Python

\* \*\*Data Processing:\*\* Pandas, NumPy, PyArrow (Parquet)

\* \*\*Machine Learning:\*\* Scikit-Learn (Isolation Forest, LOF, One-Class SVM)

\* \*\*Visualization:\*\* Plotly Express, Matplotlib, Seaborn



\## ⚙️ Methodology \& Pipeline

1\. \*\*Data Preprocessing \& Feature Engineering:\*\* Ekstraksi fitur fisika spasial (Haversine distance, perhitungan jeda waktu, elevasi, dll).

2\. \*\*Pseudo-Ground Truth Generation:\*\* Pembuatan label anomali berbasis \*Rule-Based Heuristic\* (Hukum Fisika Kinematik).

3\. \*\*Model Benchmarking:\*\* Komparasi 3 algoritma deteksi anomali:

&#x20;  \* 🏆 \*\*Isolation Forest\*\* (Dipilih sebagai model final)

&#x20;  \* ❌ Local Outlier Factor (LOF)

&#x20;  \* ❌ One-Class SVM

4\. \*\*Mass Inference:\*\* Pemindaian 77 Juta baris data organik menggunakan model terpilih.



\## 📊 Key Results

\* \*\*Akurasi Model:\*\* \*\*99%\*\* (berdasarkan evaluasi komparatif fisika absolut).

\* \*\*Total Deteksi:\*\* Berhasil mengisolasi \*\*\~4.2 Juta anomali\*\* (5.5% rasio ancaman) dari total 77 Juta data.

\* \*\*Dominasi Serangan:\*\* \*Jamming\* menjadi vektor serangan paling dominan dibandingkan \*Spoofing\*.



\## 📁 Repository Structure

\* `ADSB\_Anomaly\_Detection\_Final.ipynb` : Notebook utama berisi seluruh pipeline dari EDA hingga evaluasi model.

\* `SAMPLE\_HACKER\_DETECTED.csv` : Sampel hasil ekstraksi anomali yang ditangkap oleh AI.

\* `requirements.txt` : Daftar library yang dibutuhkan untuk menjalankan project ini.



\*\*Dataset Note:\*\* Mengingat batasan ukuran file GitHub (Max 100MB), file dataset utuh (2.2 GB) tidak disertakan di repository ini. Untuk menjalankan notebook secara penuh (Mass Inference), silakan unduh file `.parquet` melalui \*\*\[https://drive.google.com/file/d/129foVnBrO1WpVkudPNTJA9Es0p_6qW66/view?usp=sharing]\*\*.



\---

\*Project ini dikembangkan sebagai bagian dari tugas akhir (Skripsi) Program Studi Sistem Informasi.\*

e84427a8fcd2766a79424d0abef90ff3e13c349c
