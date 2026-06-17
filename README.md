# Sentimen-Analysis-MBG-makan-bergizi-gratis-

Analisis sentimen terhadap program **MBG (Makan Bergizi Gratis)** pada media sosial **X (Twitter)** menggunakan metode **Support Vector Machine (SVM)** untuk mengklasifikasikan opini masyarakat ke dalam kategori sentimen positif, negatif, dan netral.

## 📌 Deskripsi Proyek

Penelitian ini bertujuan untuk menganalisis sentimen masyarakat terhadap program Makan Bergizi Gratis (MBG) berdasarkan data yang diperoleh dari media sosial X (Twitter). Model klasifikasi yang digunakan adalah **Support Vector Machine (SVM)** dengan tahapan preprocessing teks dan evaluasi performa model.

---

## 📂 Dataset

Data diperoleh dari media sosial X (Twitter) menggunakan proses crawling dengan kata kunci terkait program **Makan Bergizi Gratis (MBG)**.

Contoh atribut dataset:

* `username`
* `date`
* `text`
* `sentiment`

---

## ⚙️ Tahapan Analisis Sentimen Menggunakan SVM

### 1. Data Collection

Mengumpulkan data tweet terkait topik MBG (Makan Bergizi Gratis) dari media sosial X (Twitter).

### 2. Data Labeling

Memberikan label sentimen pada data menjadi:

* Positif
* Negatif
* Netral

### 3. Text Preprocessing

Tahapan preprocessing meliputi:

* Case Folding
* Cleaning (menghapus URL, hashtag, mention, emoji, tanda baca)
* Tokenizing
* Stopword Removal
* Stemming

### 4. Feature Extraction

Mengubah teks menjadi representasi numerik menggunakan metode:

* TF-IDF (Term Frequency-Inverse Document Frequency)

### 5. Data Splitting

Membagi dataset menjadi:

* Data Training (80%)
* Data Testing (20%)

### 6. Support Vector Machine (SVM)

Melakukan klasifikasi sentimen menggunakan algoritma **Support Vector Machine (SVM)**.

Parameter yang dapat digunakan:

* Kernel: Linear
* C = 1.0

### 7. Model Evaluation

Evaluasi model dilakukan menggunakan:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🛠️ Library yang Digunakan

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* nltk
* sastrawi

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk sastrawi
```

---

## 📊 Alur Penelitian

```text
Data Crawling
      ↓
Data Labeling
      ↓
Text Preprocessing
      ↓
TF-IDF
      ↓
Split Data
      ↓
Support Vector Machine (SVM)
      ↓
Evaluasi Model
      ↓
Hasil Klasifikasi Sentimen
```

---

## 📈 Output

Model menghasilkan klasifikasi sentimen masyarakat terhadap program Makan Bergizi Gratis (MBG) menjadi:

* Positif
* Negatif
* Netral

beserta nilai akurasi dan metrik evaluasi lainnya.

---

## 👨‍💻 Author

Nelsi

---

