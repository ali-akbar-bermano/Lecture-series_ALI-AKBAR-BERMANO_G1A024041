# Informatics Practitioner Lecture Series 2026

Repositori ini berisi rangkuman komprehensif, materi perkuliahan, serta kode implementasi tugas praktis berbasis **Google Colab** dan **KNIME Analytics Platform** dari rangkaian perkuliahan praktisi (*Informatics Practitioner Lecture Series 2026*) yang diselenggarakan oleh **Program Studi Informatika, Universitas Bengkulu**.

---

## 👤 Identitas Mahasiswa

* **Nama** : Ali Akbar Bermano
* **NPM** : G1A024041
* **Program Studi** : Teknik Informatika
* **Instansi** : Universitas Bengkulu

---

## 📚 Daftar Sesi Perkuliahan & Rangkuman Materi

### 1. Bridging Global Infrastructure to Address Local Challenge with HPC
* **Narasumber**: Asst. Prof. Dr. Worawan Diaz Carballo (Thammasat University, Thailand)
* **Ringkasan**:
  Membahas peran krusial infrastruktur *High Performance Computing* (HPC) dan superkomputer global (seperti El Capitan, Fugaku, LUMI, dan Marenostrum 5) dalam menyelesaikan permasalahan lokal berskala besar (SDGs), seperti pemodelan prediksi cuaca, analisis kualitas udara (PM 2.5), simulasi penyebaran penyakit, serta formulasi obat-obatan.
* **Proyek Implementasi**:
  * **Topik**: *Benchmark* Perkalian Matriks Paralel (*Multi-Core Multiprocessing*) & Pengukuran GFLOPS di Google Colab.

---

### 2. Career and Competition in Industrial Era with GIS
* **Narasumber**: Widi Primadepa (Asset Management Analyst, City Care Property, Selandia Baru)
* **Ringkasan**:
  Mengupas keunggulan strategis lulusan IT (*Bachelor of IT*) di industri Sistem Informasi Geografis (GIS) sebagai pengembang (*developer*) sistem, integrasi basis data geospasial (PostGIS/SQL), penggunaan teknologi *open-source* (QGIS, GeoPandas), hingga penerapan GIS untuk *Smart Cities*, *Asset Management*, dan otomasi *remote sensing* berbasis AI.
* **Proyek Implementasi**:
  * **Topik**: Otomatisasi Analisis Spasial Keterjangkauan (*Spatial Buffer Analysis*) & Peta Web Interaktif Kota Bengkulu menggunakan Python (`GeoPandas` & `Folium`).

---

### 3. Cyber Security Awareness & Digital Forensics
* **Narasumber**: Praktisi Keamanan Siber
* **Ringkasan**:
  Membahas lanskap ancaman siber modern (*social engineering*, *phishing*, *ransomware*), prinsip pertahanan berlapis (*Defense-in-Depth* & *Zero Trust Architecture*), serta alur kerja forensik digital (*digital forensics workflow*) yang mencakup *forensic imaging*, *chain of custody*, hingga analisis artefak log untuk rekonstruksi kronologi serangan.
* **Proyek Implementasi**:
  * **Topik**: *Log Forensics Engine* — Analisis Log Server Mentah & Deteksi Serangan Siber (*Brute Force*, *SQL Injection*, dan *XSS*) menggunakan Python di Google Colab.

---

### 4. Introduction to Machine Learning
* **Narasumber**: Dr. Taniza binti Tajuddin (Universiti Teknologi MARA / UiTM Kedah, Malaysia)
* **Ringkasan**:
  Menjelaskan transisi dari *rule-based thinking* ke *data-driven thinking*, taksonomi *Machine Learning* (*Supervised*, *Unsupervised*, *Reinforcement*, dan *Semi-Supervised Learning*), alur kerja standar CRISP-DM, metrik evaluasi (*Accuracy*, *Precision*, *Recall*, *F1-Score*), serta prinsip *"Garbage In, Garbage Out"*.
* **Proyek Implementasi**:
  * **Topik**: Prediksi Kelayakan Pinjaman / Kredit Bank (*Loan Approval Prediction*) menggunakan algoritma *Logistic Regression* & *Decision Tree*.

---

### 5. Human-Computer Interaction & Data Visualization
* **Narasumber**: Arafat Febriandirza, S.T., M.T.I., Ph.D. (Pusat Riset Sains Data dan Informasi, BRIN)
* **Ringkasan**:
  Membahas konsep *User-Centered Design* (UCD), psikologi kognitif dan beban memori pengguna (*extraneous load*), 10 *Heuristic Evaluation* Jakob Nielsen, prinsip Edward Tufte (*high data-ink ratio*), serta taksonomi visualisasi interaktif Ben Shneiderman (*Overview first, zoom and filter, details-on-demand*).
* **Proyek Implementasi**:
  * **Topik**: *Interactive Usability Testing Dashboard* untuk menganalisis metrik *User Persona*, durasi tugas, *error rate*, dan *System Usability Scale* (SUS) berbasis `Plotly`.

---

### 6. Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI
* **Narasumber**: Dr. Bart Slagter (Wageningen University and Research, Belanda)
* **Ringkasan**:
  Membahas integrasi citra satelit optik (Sentinel-2) dan radar (Sentinel-1) dengan model *Deep Learning* (*Convolutional Neural Network* / CNN) untuk mengklasifikasikan penyebab langsung (*direct drivers*) di balik titik peringatan deforestasi (seperti pertanian skala besar/kecil, *selective logging*, pertambangan, dan kebakaran hutan).
* **Proyek Implementasi**:
  * **Topik**: Atribusi Pendorong Deforestasi dan Hilangnya Tutupan Pohon berdasarkan Fitur Spektral Satelit menggunakan *Random Forest Classifier*.

---

### 7. Make Sense of Data with Analysis and AI
* **Narasumber**: Andria Arisal, S.T., M.Eng. (Pusat Riset Sains Data dan Informasi, BRIN & Pengelola HPC Mahameru)
* **Ringkasan**:
  Membahas hierarki pengolahan data (*Data -> Information -> Insight -> Decision*), 4 tingkat analisis (Deskriptif, Diagnostik, Prediktif, Preskriptif), pentingnya *data preparation* (80–90% waktu proyek), konsep *Human-in-the-Loop*, serta pemanfaatan KNIME Analytics Platform.
* **Proyek Implementasi**:
  * **Topik**: *Workflow* KNIME untuk Prediksi Keterlambatan Pembayaran Tagihan (*Invoice Late Payment Prediction*) berbasis *Decision Tree*.

---

## 🛠️ Teknologi & Library yang Digunakan

* **Bahasa Pemrograman**: Python 3.x
* **Platform & Environment**: Google Colab, KNIME Analytics Platform
* **Library Geospasial**: `GeoPandas`, `Folium`, `Shapely`
* **Library Data & Machine Learning**: `Pandas`, `NumPy`, `Scikit-Learn`
* **Library Visualisasi**: `Matplotlib`, `Seaborn`, `Plotly Express`

---

## 🚀 Cara Menjalankan Proyek

1. **Google Colab Notebooks (`.ipynb`)**:
   * Buka salah satu file `.ipynb` yang ada pada repositori ini.
   * Klik tombol **Open in Colab** atau unduh file dan buka melalui [colab.research.google.com](https://colab.research.google.com).
   * Jalankan sel kode secara berurutan dari atas ke bawah.

2. **KNIME Analytics Platform**:
   * Unduh dan buka aplikasi **KNIME Analytics Platform**.
   * Impor file *workflow* (`.knwf`) atau buat *workflow* baru menggunakan prompt K-AI Assistant yang tersedia pada rangkuman materi.
