# 🌿 Sistem Monitoring Kesiapan Pupuk Organik Berbasis IoT dan Klasifikasi KNN
**Sistem klasifikasi kesiapan pupuk organik dari limbah ternak menggunakan algoritma K-Nearest Neighbors (KNN) pada mikrokontroler ESP32 dengan integrasi IoT dan protokol Modbus.**

## 📌 Ringkasan Proyek

Proyek ini mengembangkan sistem real-time untuk **menganalisis kesiapan pupuk organik** yang berasal dari limbah ternak. Sistem menggunakan **algoritma K-Nearest Neighbors (KNN)** yang ditanamkan langsung ke dalam **mikrokontroler ESP32**. Data dibaca dari sensor DIY untuk **suhu, kelembaban, dan pH**, kemudian diklasifikasikan apakah **pupuk siap atau belum siap digunakan**.

### Fitur Utama
- 🔍 **Algoritma KNN** berjalan langsung di ESP32
- 📡 **Pembacaan data sensor real-time** (Suhu, Kelembaban, pH)
- 🌐 **Integrasi IoT dengan Firebase** dan penyimpanan lokal di SD Card
- 📊 **Komunikasi Modbus** untuk pemantauan alat secara bersamaan
- 📱 **Dashboard Mobile** menggunakan aplikasi Blynk IoT
- 💾 **Web Server & Data Logger** yang tetap berjalan meski tanpa internet

---

## 🛠️ Komponen Perangkat Keras
- ESP32 sebagai mikrokontroler utama
- Arduino UNO
- Sensor Suhu 
- Sensor Kelembaban DIY
- Sensor pH DIY
- LCD Display
- Modul SD Card
- Koneksi WiFi
- Firebase Realtime Database

---

## 🔄 Alur Kerja Sistem

1. Pengguna menekan tombol "Baca"
2. ESP32 mengumpulkan data dari sensor
3. Data diklasifikasikan menggunakan algoritma KNN
4. Hasil tampil di LCD (Siap / Belum Siap)
5. Data disimpan ke Firebase dan juga ke SD Card
6. Sistem mendukung komunikasi **Modbus** untuk integrasi skala industri

---
## 📂 File yang Disertakan

- `main.ino` – Kode Arduino untuk ESP32
- `dataset.csv` – Dataset contoh untuk KNN
- `dokumentasi.pdf` – Laporan akhir dan penjelasan teknis
- `presentasi.pptx` – Materi presentasi
- `demo.mp4` – Video demonstrasi alat

---

## 🌱 Dampak Proyek

Dirancang untuk kebutuhan nyata di sektor pertanian, sistem ini mendukung **pertanian organik berkelanjutan** dan bisa dikembangkan ke skala industri dengan **komunikasi Modbus dan integrasi IoT**.

> "Bukan sekadar alat praktikum, tapi solusi nyata menuju pertanian digital."

---

## 🙋‍♂️ Tentang Saya

**Mohamad Nawal Taufiqurohman**  
Seorang **AI-Assisted Technologist** dengan fokus pada teknologi tepat guna dan pertanian pintar.  
> Mengubah ide menjadi alat nyata dengan bantuan AI, sensor, dan mikrokontroler.


## 📬 Kontak & Kolaborasi

Untuk kolaborasi, konsultasi, atau pertanyaan:  
📧 Email: **nawaltaufiq8@gmail.com**

---

