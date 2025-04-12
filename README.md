# 🧠 Sentiment Analysis Classification Application — Dana, SVM, RF, CNN

Proyek ini merupakan aplikasi analisis sentimen yang bertujuan untuk mengklasifikasikan opini atau ulasan ke dalam tiga kategori: **positif**, **netral**, dan **negatif**. Model yang digunakan meliputi **Support Vector Machine (SVM)**, **Random Forest (RF)**, dan **Convolutional Neural Network (CNN)**. Dataset yang digunakan adalah hasil scraping dari aplikasi **Dana** atau sumber serupa.

---

## 📁 Struktur File

| File              | Deskripsi                                                   |
|-------------------|-------------------------------------------------------------|
| `Scrapping.ipynb` | Scraping ulasan dari aplikasi Dana (atau sumber lain)       |
| `model.ipynb`     | Training model menggunakan SVM, RF, dan CNN dengan berbagai skema |
| `Inference.ipynb` | Proses inference untuk prediksi sentimen dari input baru    |
| `requirements.txt`| Library Python yang diperlukan                              |
| `README.md`       | Dokumentasi proyek ini                                      |

---

## ⚙️ Cara Menjalankan Proyek

### 1. Clone Repository dan Install Dependensi

```bash
git clone <URL-repo-anda>
cd sentiment-analysis-classification
pip install -r requirements.txt
```

### 2. Jalankan Notebook secara Berurutan

✅ `Scrapping.ipynb`  
✅ `model.ipynb`  
✅ `Inference.ipynb`