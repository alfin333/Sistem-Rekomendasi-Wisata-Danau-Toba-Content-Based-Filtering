# 🎯 Sistem Rekomendasi Wisata Berbasis Content-Based Filtering

Proyek ini merupakan implementasi sistem rekomendasi tempat wisata menggunakan pendekatan **Content-Based Filtering**. Sistem ini merekomendasikan wisata berdasarkan kemiripan konten (deskripsi dan aktivitas) dan riwayat kunjungan pengguna, serta mengevaluasi performanya menggunakan teknik validasi silang **K-Fold Cross Validation**.

---

## 🚀 Fitur

- **Text Preprocessing**: tokenisasi, lowercasing, stopword removal, dan stemming.
- **Item-to-Item Recommendation**: Merekomendasikan wisata serupa berdasarkan tempat yang dipilih.
- **User-to-Item Recommendation**: Memberikan rekomendasi berdasarkan riwayat wisata pengguna.
- **Evaluasi Sistem**: Menggunakan **K-Fold Cross Validation** dengan metrik **Hit Rate**.

---

## 🗂️ Struktur Folder
```
├───0. Dataset <br>
├───1. Text Preprocessing<br>
│   └───Save Model<br>
├───2. Rekomendasi Item to Item<br>
├───3. Rekomendasi User to Item (CBF)<br>
└───4. Evaluasi User to Item<br>
```

## ⚙️ Instalasi
# Jalankan perintah berikut <br>
**1. Clone repository ini**
```
git clone https://github.com/alfin333/Sistem-Rekomendasi-Wisata-Danau-Toba-Content-Based-Filtering .
```
**2. Buat virtual environment**
```
python -m venv venv
```
**3. Aktifkan virtual environment**
```
source venv/bin/activate       # Untuk Linux/macOS
venv\Scripts\activate          # Untuk Windows ```
```
**4. Install Library yang diperlukan**
```
pip install -r requirements.txt 
```

