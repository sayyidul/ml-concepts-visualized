# ML Concepts Visualized

Kumpulan notebook yang menjelaskan **cara kerja internal berbagai model machine learning** lewat visualisasi langsung, bukan sekadar pemanggilan `fit()` dan `predict()`. Tujuannya untuk memahami *mengapa* sebuah model mengambil keputusan tertentu, bukan hanya *bahwa* model itu bekerja.

Repo ini adalah bagian dari portofolio saya di bidang Data Science / Machine Learning, dan beberapa notebook di sini terhubung dengan riset tesis saya tentang perbandingan model ML untuk klasifikasi kesehatan mental mahasiswa.

## Isi Repository

| Model | Notebook | Topik yang Divisualisasikan |
|---|---|---|
| XGBoost | [`xgboost/tree_visualization.ipynb`](xgboost/tree_visualization.ipynb) | Struktur satu decision tree dalam XGBoost (split, gain, leaf value) |
| Random Forest | *(segera menyusul)* | Perbandingan antar-tree, feature importance |
| SVM | *(segera menyusul)* | Decision boundary & margin pada data 2D |
| Logistic Regression | *(segera menyusul)* | Sigmoid, decision boundary, interpretasi koefisien |
| Ensemble (Voting/Stacking) | *(segera menyusul)* | Bagaimana prediksi individual digabung menjadi prediksi akhir |

Setiap notebook memakai dataset sintetis sederhana (biasanya 2 fitur) agar visualisasi tetap mudah dibaca, dengan penjelasan konsep di setiap tahap.

## Struktur Folder

```
ml-concepts-visualized/
├── xgboost/
│   └── tree_visualization.ipynb
├── random_forest/
├── svm/
├── logistic_regression/
├── ensemble/
└── README.md
```

## Cara Menjalankan

```bash
git clone https://github.com/sayyidul/ml-concepts-visualized.git
cd ml-concepts-visualized
pip install -r requirements.txt
jupyter notebook
```

Dependensi utama: `xgboost`, `scikit-learn`, `matplotlib`.

## Latar Belakang

Repo ini dibuat sebagai pendamping dari riset tesis saya (S2 Informatika, UIN Maulana Malik Ibrahim Malang) yang membandingkan enam model ML — Logistic Regression, SVM, Random Forest, XGBoost, Ensemble Majority Voting, dan Ensemble Stacking — untuk klasifikasi kesehatan mental mahasiswa. Notebook di sini fokus membedah cara kerja tiap model secara terpisah, sebagai pelengkap dari studi perbandingan performa di tesis.

## Kontak

- GitHub: [@sayyidul](https://github.com/sayyidul)
- LinkedIn: [sayyidul30](https://linkedin.com/in/sayyidul30)
