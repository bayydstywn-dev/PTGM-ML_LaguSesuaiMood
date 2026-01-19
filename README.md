# 🎧 Klasifikasi Mood Lagu Menggunakan Decision Tree

Proyek ini merupakan aplikasi **Machine Learning** untuk mengklasifikasikan **mood lagu** berdasarkan fitur audio dari Spotify.  
Model yang digunakan adalah **Decision Tree** untuk memprediksi mood lagu seperti **Happy, Sad, Chill, dan Energetic**.

Proyek ini dibuat untuk **keperluan pembelajaran dan tugas sekolah**.

---

## 📌 Gambaran Umum Proyek

Musik sering digunakan untuk menyesuaikan suasana hati, seperti saat belajar, bersantai, atau beraktivitas. Namun, dengan banyaknya lagu yang tersedia, sering kali sulit menentukan lagu yang sesuai dengan mood tertentu.

Oleh karena itu, proyek ini bertujuan untuk membangun model Machine Learning yang dapat **mengklasifikasikan mood lagu secara otomatis** berdasarkan karakteristik audio lagu.

---

## 🎯 Tujuan
- Membangun model Machine Learning untuk klasifikasi mood lagu  
- Menerapkan algoritma **Decision Tree**  
- Menggunakan fitur audio Spotify sebagai data input  
- Memahami alur kerja pembuatan Machine Learning dari awal hingga evaluasi  

---

## 📊 Dataset
- **Nama Dataset:** Spotify Audio Features  
- **Sumber:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/tomigelo/spotify-audio-features  

Dataset ini berisi berbagai fitur audio lagu yang disediakan oleh Spotify.

---

## 🧠 Pendekatan Machine Learning
- **Jenis Pembelajaran:** Supervised Learning  
- **Tugas:** Klasifikasi  
- **Algoritma:** Decision Tree Classifier  

### Fitur Input:
- `valence` (tingkat keceriaan lagu)
- `energy` (tingkat energi lagu)
- `tempo` (kecepatan lagu)
- `danceability` (tingkat kenyamanan untuk menari)

### Output (Target):
- Mood Lagu:
  - Happy
  - Sad
  - Chill
  - Energetic

---

## ⚙️ Pra-pemrosesan Data (Data Preprocessing)
- Memilih fitur audio yang relevan  
- Membuat label mood lagu menggunakan aturan sederhana berbasis fitur audio  
- Membagi dataset menjadi data latih dan data uji (80% data latih dan 20% data uji)  

---

## 📈 Evaluasi Model
Evaluasi model dilakukan menggunakan:
- **Akurasi**
- **Classification Report** (precision, recall, f1-score)

Hasil evaluasi menunjukkan bahwa model Decision Tree mampu mempelajari pola data dengan baik.

---

## 🧪 Contoh Prediksi
Model dapat digunakan untuk memprediksi mood lagu baru berdasarkan fitur audionya.  
Sebagai contoh, lagu dengan nilai valence dan energy yang tinggi cenderung diprediksi sebagai **Happy**.

---

## 🗂️ Struktur Proyek
.
├── SpotifyAudioFeatures.csv
├── song_mood_classification.ipynb
├── README.md

---

## 🚀 Cara Menjalankan Proyek
1. Clone repository ini
2. Buka file notebook menggunakan Google Colab atau Jupyter Notebook
3. Upload file dataset (`SpotifyAudioFeatures.csv`)
4. Jalankan setiap cell secara berurutan

---

## 📚 Teknologi yang Digunakan
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## 📝 Catatan
- Label mood dibuat menggunakan aturan sederhana berbasis fitur audio  
- Proyek ini **tidak digunakan untuk keperluan komersial**  
- Proyek ini bertujuan untuk pembelajaran Machine Learning dasar  

---

## 👤 Penulis
**Bayu Adi Setyawan**

---

## 📄 Lisensi
Proyek ini dibuat untuk keperluan pendidikan dan pembelajaran.



