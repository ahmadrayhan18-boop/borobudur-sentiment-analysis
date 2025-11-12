🎓 Analisis Sentimen Ulasan Candi Borobudur Menggunakan Support Vector Machine dan Naïve Bayes

Repositori ini berisi kode, dataset, dan hasil eksperimen dari penelitian skripsi berjudul:"Perbandingan Algoritma Support Vector Machine dan Naïve Bayes pada Analisis Sentimen Ulasan Candi Borobudur"oleh Muhammad Rayhan (202110715241)Fakultas Ilmu Komputer, Universitas Bhayangkara Jakarta Raya (2025)

📘 Deskripsi Proyek

Pertumbuhan ulasan wisatawan di platform daring seperti Tiket.com dan Tripadvisor menghasilkan data teks yang besar dan tidak terstruktur. Penelitian ini bertujuan untuk menganalisis sentimen wisatawan terhadap Candi Borobudur secara otomatis menggunakan pendekatan machine learning.

Dua algoritma dibandingkan:
🧠 Naïve Bayes
⚙️ Support Vector Machine (SVM)

Model dievaluasi menggunakan metrik accuracy, precision, recall, dan F1-score untuk menentukan algoritma yang paling efektif dalam klasifikasi sentimen positif dan negatif.

🧩 Arsitektur dan Metodologi

Tahapan utama dalam penelitian ini:
1. Data Collection
Mengambil 4.341 ulasan dari Tiket.com dan Tripadvisor (periode 2010–2025).
2. Data Preprocessing
-Case folding
-Cleansing
-Normalisasi slang & emoticon
-Tokenizing
-Stopword removal
-Stemming (menggunakan Sastrawi)
3. Feature Extraction
Menggunakan TF-IDF (Term Frequency–Inverse Document Frequency)
4. Model Training & Evaluation
Naïve BayesSupport Vector Machine (Linear Kernel)
5.Evaluasi dengan Confusion Matrix, Accuracy, Precision, Recall, dan F1-Score

📊 Hasil Penelitian

Hasil Kinerja Model (Diuji pada Data Testing)

Support Vector Machine (SVM):
-Akurasi: 88%
-Presisi: 91%
-Recall: 95%
-F1-Score: 93%

Naïve Bayes:
-Akurasi: 83%
-Presisi: 82%
-Recall: 100%
-F1-Score: 90%

Kesimpulan:
Algoritma SVM menunjukkan performa yang lebih stabil dan akurat (88%) dibandingkan Naïve Bayes, menjadikannya model yang optimal.

🧠 Teknologi yang Digunakan

Bahasa Pemrograman: Python
Platform: Google Colab
Library Utama: scikit-learn, pandas, numpy, matplotlib, nltk, Sastrawi
Metode Pembobotan: TF-IDF
Algoritma ML: Naïve Bayes, Support Vector Machine (SVM)
