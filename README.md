# KBBI-NLP-Dataset
Dataset Kamus Besar Bahasa Indonesia (KBBI) yang telah dibersihkan untuk keperluan NLP.
Dataset sumber (mentah) yang digunakan dalam proyek ini bersumber dari repositori [aryakdaniswara/kbbi-dataset-kbbi-v](https://github.com/aryakdaniswara/kbbi-dataset-kbbi-v).

* `kamus_kbbi.json`: Kumpulan kata unik dalam bentuk dictionary/objek.
* `normalization.json`: Pemetaan `{kata_tidak_baku: kata_baku}`.
* `lemmatization.json`: Pemetaan `{token_berimbuhan: kata_dasar}`.
* `pos.json`: Pemetaan kata ke kelas katanya (Primary POS dan All POS tags).
