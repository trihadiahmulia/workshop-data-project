# Workshop Data Project
Proyek latihan untuk memahami kolaborasi data menggunakan Git, Github, dan Kaggle Notebook.

## Tujuan
- Memahami struktur proyek data yang baik
- Belajar kolaborasi menggunakan Git dan Github
- Melakukan eksplorasi data dengan Kaggle Notebook
- Mendokumentasikan analisis dengan Markdown

## Dataset
- **Nama**: Iris Species
- **Sumber**: [UCI ML Repository via Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- **Lisensi**: Public Domain
- **Deskripsi**: dataset klasifikasi 3 spesies bunga Iris berdasarkan 4 fitur morfologis (`sepal lenghth`, `sepal width`, `petal lenghth`, `petal width`).
- **Jumlah data**: 150 sampel dengan 3 spesies (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)

## Struktur Proyek
- `data/raw/`         : data mentah dari sumber eksternal (mis. dataset_1)
- `data/interim/`     : data hasil langkah persiapan awal
- `data/processed/`   : data siap pakai untuk training / evaluasi
- `notebooks/`        : eksplorasi data & eksperimen awal
- `src/config/`       : konfigurasi proyek (config, logging)
- `src/data/`         : script loading, split, dan persiapan dataset
- `src/models/`       : script training, evaluasi, dan prediksi model
- `src/pipelines/`    : pipeline end-to-end untuk training
- `src/utils/`        : fungsi pendukung (seed, metrics, dll.)
- `experiments/`      : konfigurasi & catatan tiap eksperimen
- `models_artifacts/` : checkpoint dan model final
- `reports/`          : hasil analisis, gambar, dan ringkasan
- `scripts/`          : script command-line (train, evaluate, dll.)

## Analisa dan Insight
Notebook eksplorasi data lengkap tersedia di Kaggle:
- [EDA: Iris Species - Visualisasi & Storytelling](https://www.kaggle.com/username/notebook-name)

### Ringkasan Insight
- Fitur petal sangat diskriminatif untuk membedakan spesies.
- Iris-setosa terpisah sempurna dari Iris-versicolor dan Iris-virginica.
- Tidak ada missing value pada dataset ==> dataset siap digunakan untuk modeling.

## Cara Menggunakan Repositori Ini
1. Clone repository: `git clone <url-repository>`
2. Navigasi ke folder: `cd workshop-data-project`
3. Buka Kaggle Notebook dari link di atas untuk melihat analisis
4. Untuk berkontribusi: Buat branch baru, commit perubahan, dan buat pull request

## Best Practices
- ✅ Jangan ubah file di `data/raw/` -- gunakan `data/processed/` untuk data hasil olahan
- ✅ Dokumentasikan setiap notebook dengan markdown cells
- ✅ Gunakan nama file yang deskriptif
- ✅ Commit dengan pesan yang jelas dan singkat
- ✅ Update README seiring perkembangan proyek

## Tim Kontributor
- [Tri Hadiah Muliawati] - Owner
