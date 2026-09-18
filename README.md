# ⚡ Big Data Processing Architectures Showcase & Interactive Infographic

Repositori web interaktif modern yang menjelaskan **4 Arsitektur Pemrosesan Big Data Utama**:
1. **Batch Processing Architecture**
2. **Lambda Architecture (Dual-Pipeline)**
3. **Kappa Architecture (Stream-First)**
4. **Lakehouse Medallion Architecture (Bronze-Silver-Gold)**

Lengkap dengan:
* 🎨 **Poster Infografis AI (3D Blueprint)** beresolusi tinggi di `assets/bigdata_poster.jpg`.
* 💡 **Analogi Kehidupan Sehari-hari** yang mudah dipahami mahasiswa.
* 💻 **Contoh Kode PySpark** untuk masing-masing paradigma.
* 📊 **Matriks Perbandingan Lengkap** (Latensi, Codebase, ACID, Maintenance).
* 🎯 **Panduan Arsitektur untuk Capstone Project**.

---

## 🚀 Cara Menjalankan Secara Lokal (Preview)

### Opsi 1: Langsung Buka di Browser
Cukup klik ganda (*double click*) file [`index.html`](./index.html) pada File Explorer laptop Anda. Web akan langsung terbuka di Google Chrome / Microsoft Edge.

### Opsi 2: Menggunakan Local Server (Python)
Jika ingin menggunakan localhost:
```bash
cd "d:\Matkul baru\Big Data infrastructure\bigdata_architecture_infographics"
python -m http.server 8000
```
Buka browser di: `http://localhost:8000`

---

## 🌐 Cara Deploy ke GitHub Pages (Online & Publik)

Anda bisa meng-online-kan web ini secara gratis menggunakan **GitHub Pages**:

1. Buat repositori baru di GitHub Anda (misal beri nama `bigdata-architecture-infographics`).
2. Jalankan perintah berikut di terminal:
```bash
cd "d:\Matkul baru\Big Data infrastructure\bigdata_architecture_infographics"
git init
git add .
git commit -m "feat: initial commit Big Data Architecture Infographic web"
git branch -M main
git remote add origin https://github.com/<USERNAME_GITHUB_ANDA>/bigdata-architecture-infographics.git
git push -u origin main
```
3. Buka repositori Anda di web GitHub:
   * Masuk ke tab **Settings** -> **Pages** (di menu kiri).
   * Pada bagian **Branch**, pilih `main` dan folder `/ (root)`.
   * Klik tombol **Save**.
4. Dalam 1-2 menit, web Anda akan online di domain:  
   `https://<USERNAME_GITHUB_ANDA>.github.io/bigdata-architecture-infographics/`

---

## 📂 Struktur Berkas
```
bigdata_architecture_infographics/
├── assets/
│   └── bigdata_poster.jpg      # Master Poster Infografis AI (3D Blueprint)
├── index.html                  # Aplikasi Web Interaktif (Tailwind CSS)
└── README.md                   # Dokumentasi dan panduan hosting
```
