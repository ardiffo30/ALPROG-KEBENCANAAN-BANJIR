# 🌊 Sistem Monitoring Banjir & Portal SOS

Aplikasi kebencanaan lintas platform (*cross-platform*) berbasis **.NET MAUI** yang bekerja secara *offline* (*local-first*). Aplikasi ini mendeteksi dan memprediksi risiko banjir menggunakan **AI Hibrida (Logika Fuzzy & Jaringan Saraf Tiruan)**, dilengkapi **AI NLP Assistant** untuk mempermudah instruksi bagi warga awam, fitur login **Biometrik Wajah**, serta manajemen log data **SQLite** dengan fitur ekspor ke **Excel & JPG HD**.

---

## ✨ Fitur Utama

* **🧠 AI Hibrida (Fuzzy Logic & Neural Network):** Penentuan status siaga darurat (Aman, Waspada, Siaga) secara *real-time* dan kalkulasi persentase indeks risiko banjir menggunakan algoritma *Backpropagation*.
* **💬 NLP Disaster Assistant:** Asisten AI cerdas yang otomatis menerjemahkan data sensor mentah (TMA & Curah Hujan) menjadi instruksi evakuasi verbal yang mudah dipahami oleh masyarakat.
* **🔐 Autentikasi Biometrik Wajah:** Sistem proteksi akses aman untuk memisahkan wewenang antara Operator Lapangan (SAR/BNPB) dan pengguna awam.
* **📂 Dashboard Database Lokal (SQLite):** Manajemen riwayat log simulasi tangguh yang dapat diakses penuh tanpa koneksi internet.
* **📊 Ekspor Laporan Instan:** Fitur unduh riwayat data ke dalam format dokumen **Excel (XLSX)** dan visual grafik resolusi tinggi (**JPG HD**) hanya dengan satu klik.

---

## 🛠️ Teknologi & Dependencies

* **Framework Utama:** .NET 8 / .NET MAUI
* **Bahasa Pemrograman:** C# & XAML
* **Database Lokal:** SQLite (`sqlite-net-pcl`)
* **Kecerdasan Buatan:** Custom Fuzzy Math Engine, JST Feedforward & Backpropagation, API NLP Integration
* **IDE:** Visual Studio 2022

---

## 🚀 Cara Menjalankan Project (Local Setup)

1. Pastikan **Visual Studio 2022** sudah terinstal dengan *workload* **.NET Multi-platform App UI development**.
2. *Clone repository* ini ke komputer lokal:
```bash
   git clone [https://github.com/username/repo-name.git](https://github.com/username/repo-name.git)
3. Buka Project: Jalankan Visual Studio 2022, pilih Open a project or solution, lalu arahkan ke file .sln (Solution) di dalam folder hasil clone.

4. Restore Packages: Tunggu beberapa saat hingga Visual Studio selesai melakukan restore NuGet packages secara otomatis.

5. Pilih Target Device: Pada menu top bar, pilih target device untuk running aplikasi (misalnya: Windows Machine atau Android Emulator).

6. Build & Run: Tekan tombol F5 atau klik ikon Play/Run. Aplikasi akan dikompilasi dan langsung terbuka di perangkat target.
