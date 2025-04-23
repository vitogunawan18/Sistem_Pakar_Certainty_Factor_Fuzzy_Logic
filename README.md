# 🧠 Sistem Pakar Certainty Factor & Fuzzy Logic

Repositori ini berisi implementasi **Sistem Pakar** menggunakan dua pendekatan metode kecerdasan buatan populer, yaitu:

1. **Certainty Factor (CF)** – untuk membantu diagnosis berbasis gejala dengan tingkat keyakinan tertentu.
2. **Fuzzy Logic** – untuk pengambilan keputusan berbasis nilai input numerik seperti suhu dan kelembaban.

Repositori ini ditujukan sebagai media pembelajaran interaktif dalam memahami bagaimana metode CF dan Fuzzy Logic dapat digunakan dalam pengambilan keputusan cerdas di berbagai kasus sederhana.

---

## 📝 Deskripsi Singkat

### ✅ Certainty Factor
Digunakan untuk menangani ketidakpastian dalam sistem pakar diagnosis, dengan cara mengalikan keyakinan pengguna terhadap nilai pakar untuk menghasilkan nilai kepastian (CF akhir).

### ✅ Fuzzy Logic
Digunakan untuk menangani data numerik yang tidak pasti atau bersifat samar, seperti suhu dan kelembaban, kemudian menentukan output (misalnya kecepatan kipas) secara fleksibel berdasarkan aturan fuzzy.

---

## ✨ Fitur

- 📌 **Diagnosa penyakit sederhana** menggunakan metode Certainty Factor
- 🌀 **Pengaturan kecepatan kipas otomatis** menggunakan Fuzzy Logic
- 📈 Visualisasi fungsi keanggotaan fuzzy (temperature, humidity, fan speed)
- 🧪 Simulasi input-output secara interaktif di Jupyter Notebook
- 🛠️ Penambahan aturan fuzzy secara fleksibel dan mudah dipahami

---

## 📂 Daftar File

| File | Deskripsi |
|------|-----------|
| `Fuzzy_Logic.ipynb` | Simulasi sistem pengatur kipas otomatis berbasis suhu dan kelembaban menggunakan metode fuzzy |
| `Certainty_Factor.ipynb` | Sistem pakar untuk diagnosa berbasis gejala dan keyakinan menggunakan metode certainty factor |

---

## ⚙️ Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo
