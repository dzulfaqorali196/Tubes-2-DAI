# Tugas Besar 2 IF3170 Dasar Artificial Intelligence
Repository ini berisi implementasi model machine learning untuk klasifikasi URL phishing menggunakan dataset dari [jurnal ini](https://www.sciencedirect.com/science/article/abs/pii/S0167404823004558?via%3Dihub).

## Deskripsi Singkat
Program ini mengimplementasikan proses data cleaning dan preprocessing untuk dataset URL phishing. Proses yang dilakukan meliputi:
1. Handling missing values dengan berbagai teknik imputasi
2. Handling outliers dengan pendekatan domain knowledge
3. Penghapusan data duplikat
4. Feature engineering dan feature selection
5. Model training dan evaluasi menggunakan KNN dan Gaussian Naive Bayes

## Setup dan Menjalankan Program
1. Clone repository ini
```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

2. Install dependencies yang diperlukan
```bash
pip install -r requirements.txt
```

3. Buka notebook `[UPDATED] Tugas_Besar_2_Notebook_Template.ipynb` menggunakan Jupyter Notebook atau Google Colab

4. Jalankan sel-sel kode secara berurutan dari atas ke bawah

## Pembagian Tugas

| Nama | NIM | Tugas |
|------|-----|-------|
| Dzulfaqor Ali D | 18222017 | - Notebook membuat Model KNN yang from the scratch<br>- Notebook Save and Load KNN model<br>- Membuat repo github, foldering, dan membuat readme |
| Billy Samuel S | 18222039 | - Notebook bagian Data Preprocessing<br>- Formatting laporan<br>- Laporan bagian implementasi algoritma |
| Dama D. Daliman | 18222047 | - Notebook bagian data cleaning & error analysis<br>- Laporan bagian Data Cleaning, Perbandingan<br>- Notebook Split Training Set and Validation Set<br>- Notebook Modeling and Validation |
| Steven Adrian Corne | 18222101 | - Notebook bagian Data Preprocessing<br>- Notebook bagian Save and Load Gaussian Naive Bayes Model<br>- Laporan bagian Data Preprocessing dan formating |

## Teknologi yang Digunakan
- Python 3.8+
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Referensi
- [Dataset: PhiUSIiL Phishing URL Dataset](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)
- [Jurnal: Phishing URL detection using machine learning: A comprehensive analysis of machine learning techniques](https://www.sciencedirect.com/science/article/abs/pii/S0167404823004558?via%3Dihub)
- [Dokumentasi scikit-learn: Nearest Neighbors](https://scikit-learn.org/1.5/modules/neighbors.html)
- [Dokumentasi scikit-learn: Naive Bayes](https://scikit-learn.org/1.5/modules/naive_bayes.html)