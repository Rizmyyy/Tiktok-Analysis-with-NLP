🧠 Analisis Sentimen Ulasan Produk TikTok Shop

📌 Deskripsi
Proyek ini bertujuan untuk menganalisis sentimen dari ulasan pengguna terhadap produk TikTok. Ulasan berbahasa Indonesia diterjemahkan ke dalam bahasa Inggris dan kemudian dianalisis menggunakan **VADER Sentiment Analyzer** dari NLTK. Hasil analisis diklasifikasikan menjadi sentimen **Positif**, **Negatif**, dan **Netral**, lalu divisualisasikan dalam bentuk grafik.

🔧 Teknologi yang Digunakan
- Python
- pandas
- nltk (VADER)
- deep_translator
- matplotlib

## 📂 Struktur File
├── Reviews.csv # Dataset ulasan TikTok
├── Tiktok-analysis.ipynb # Notebook utama untuk analisis
├── requirements.txt # Daftar dependensi Python
└── README.md # Dokumentasi proyek

## 🚀 Cara Menjalankan Proyek
1. Clone Repository melalui Command Prompt
cmd:
   git clone https://github.com/Rizmyyy/TiktokShop-Analysis-with-NLP.git
   cd nama-repo
   
Install semua dependensi (cmd):
pip install -r requirements.txt

Jalankan notebook:
Buka Tiktok-analysis.ipynb menggunakan Jupyter Notebook atau JupyterLab.

📊 Hasil yang Diperoleh
Setiap ulasan diklasifikasi ke dalam sentimen:
Positif (compound score ≥ 0.05)
Netral (compound score antara -0.05 dan 0.05)
Negatif (compound score ≤ -0.05)
Visualisasi menunjukkan distribusi jumlah ulasan berdasarkan kategori sentimen.
