# Yujiem Rookie Datathon 2025

> **End-to-end Data Science Pipeline for Influencer-Brand Matching**

## Deskripsi

Repositori ini berisi solusi lengkap untuk tantangan datathon yang berfokus pada pemilihan influencer Instagram terbaik untuk brand, berdasarkan data caption, komentar, bio, dan profil brand. Proyek ini menggabungkan pemodelan machine learning (fine-tuning BERT), pemrosesan data, serta algoritma matching dan ranking multi-kriteria.

## Struktur Repo

- `FineTunedBert.ipynb` — Notebook untuk fine-tuning BERT pada data komentar & caption Instagram, serta deployment model ke HuggingFace Hub.
- `InfluencerMatcher.ipynb` — Notebook utama untuk pipeline matching influencer, mulai dari data loading, scoring, hingga rekomendasi influencer terbaik untuk brand tertentu.
- `README.md` — Dokumentasi dan petunjuk penggunaan repo.

## Fitur Utama

- **Fine-tuning BERT** untuk klasifikasi caption & komentar Instagram (analisis sentimen, engagement, dsb).
- **Influencer Matching & Ranking** berbasis:
  - Kecocokan persona (semantic matching dengan Sentence Transformers)
  - Kecocokan demografi & psikografi
  - Prediksi performa kampanye (engagement, reach, authenticity)
  - Optimasi budget & strategi konten
- **Visualisasi & Insight**: Analisis mendalam untuk setiap influencer (komentar, caption, strategi campaign, dsb).

## Cara Menjalankan

1. **Clone repo & install dependencies**
   ```bash
   git clone <repo-url>
   cd yujiem-rookie-datathon-2025
   pip install -r requirements.txt
   ```
2. **Jalankan notebook**
   - Buka `FineTunedBert.ipynb` untuk training & export model BERT.
   - Buka `InfluencerMatcher.ipynb` untuk pipeline matching & rekomendasi influencer.

- Model BERT hasil fine-tuning diunggah ke HuggingFace Hub.

## Kontributor
- Tim Yujiem Rookie

## Lisensi
MIT License
