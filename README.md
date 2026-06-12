# Indonesian-Dictionary-Dataset-KBBI
Dataset Kamus Besar Bahasa Indonesia (KBBI) yang telah dibersihkan untuk keperluan NLP.
Dataset sumber (mentah) yang digunakan dalam proyek ini bersumber dari repositori [aryakdaniswara/kbbi-dataset-kbbi-v](https://github.com/aryakdaniswara/kbbi-dataset-kbbi-v).

* `kamus_kbbi.json`: Kumpulan kata unik dalam bentuk dictionary/objek.
* `normalization.json`: Pemetaan `{kata_tidak_baku: kata_baku}`.
* `lemmatization.json`: Pemetaan `{token_berimbuhan: kata_dasar}`.
* `pos.json`: Pemetaan kata ke kelas katanya (Primary POS dan All POS tags).

Cleaned Indonesian Dictionary (KBBI) Dataset for NLP purposes. The raw source dataset used in this project is derived from the [aryakdaniswara/kbbi-dataset-kbbi-v] repository (https://github.com/aryakdaniswara/kbbi-dataset-kbbi-v).

* `kamus_kbbi.json`: A collection of unique Indonesian words stored as a dictionary/object.
* `normalization.json`: A mapping of `{non_standard_word: standard_word}`.
* `lemmatization.json`: A mapping of `{inflected_token: root_word}`.
* `pos.json`: A mapping of words to their part-of-speech classes (Primary POS and All POS tags).
