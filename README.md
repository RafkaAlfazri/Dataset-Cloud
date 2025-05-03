# Dataset-Cloud
Notebook ini digunakan untuk melakukan analisis data awan (Cloud) menggunakan dataset dari UCI Machine Learning Repository, dengan pendekatan unsupervised learning (clustering).
Dataset yang Digunakan
Dataset diambil dari UCI ML Repository dengan ID 155, yaitu:
Cloud Dataset – Berisi data pengamatan awan, kemungkinan dari sensor atau citra satelit, yang dapat dianalisis untuk pengelompokan awan, segmentasi citra, atau deteksi pola tertentu.
Dataset diunduh langsung dari URL: https://archive.ics.uci.edu/static/public/155/data.csv
Langkah-Langkah Analisis Data
Instalasi dan Import Library
Eksplorasi Dataset
Setelah data diambil:
Biasanya dilanjutkan dengan melihat struktur data: df.info(), df.describe(), dll.
Pra-pemrosesan Data
Normalisasi fitur dengan StandardScaler.
Reduksi dimensi dengan PCA (Principal Component Analysis) untuk visualisasi 2D/3D dan efisiensi model.

Algoritma Machine Learning yang Digunakan
Notebook ini menggunakan pendekatan unsupervised learning (tanpa label):
K-Means Clustering
DBSCAN (density-based)
Agglomerative Clustering
Isolation Forest untuk deteksi outlier atau data tak normal

Evaluasi Model
Evaluasi hasil clustering menggunakan Silhouette Score.
Visualisasi cluster menggunakan plot dari matplotlib dan seaborn.
