# 🧠 Sistem Pakar dengan Certainty Factor & Fuzzy Logic

**Vito Gunawan** (NIM 2306149),
ini adalah repositori implementasi **Sistem Pakar** menggunakan dua metode kecerdasan buatan populer:

1. ✅ **Certainty Factor (CF)** – untuk diagnosis berdasarkan gejala dan keyakinan pengguna.
2. 🌀 **Fuzzy Logic** – untuk pengambilan keputusan berbasis input numerik seperti suhu & kelembaban.

Repositori ini ditujukan sebagai media pembelajaran interaktif untuk memahami penerapan metode CF dan Fuzzy dalam konteks sistem pakar sederhana namun powerful.

---

## 📝 Deskripsi Metode

### 🔷 Certainty Factor
Digunakan untuk menangani ketidakpastian dalam proses diagnosis, di mana sistem menggabungkan tingkat keyakinan pengguna terhadap suatu gejala dengan nilai keyakinan dari pakar.

### 🔷 Fuzzy Logic
Digunakan untuk mengambil keputusan berdasarkan data numerik yang bersifat samar, seperti suhu dan kelembaban. Output ditentukan berdasarkan aturan fuzzy untuk menghasilkan kontrol seperti kecepatan kipas.

---

## ✨ Fitur Utama

- 📌 **Diagnosa penyakit sederhana** menggunakan Certainty Factor
- 🌡️ **Pengontrol kecepatan kipas otomatis** berdasarkan suhu & kelembaban dengan Fuzzy Logic
- 📈 **Visualisasi fungsi keanggotaan** (temperature, humidity, fan speed)
- 🧪 **Simulasi interaktif** melalui Jupyter Notebook
- ⚙️ **Aturan fuzzy fleksibel** dan mudah dimodifikasi

---

## 📂 Struktur File

| File | Deskripsi |
|------|-----------|
| `Fuzzy_Logic.ipynb` | Sistem pengatur kecepatan kipas berdasarkan fuzzy logic (input: suhu & kelembaban) |
| `Certainty_Factor.ipynb` | Sistem pakar diagnosa penyakit berbasis gejala & tingkat keyakinan pengguna |

---

## 🚀 Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/vitogunawan2306149/sistem-pakar-cf-fuzzy.git
   cd sistem-pakar-cf-fuzzy
