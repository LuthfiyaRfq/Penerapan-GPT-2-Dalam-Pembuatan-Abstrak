# Penerapan GPT-2 dalam Pembuatan Abstrak pada Dokumen Jurnal

## Deskripsi

Projek ini bertujuan untuk mengimplementasikan model bahasa GPT-2 dalam pembuatan abstrak untuk dokumen jurnal ilmiah. Dengan menggunakan dataset berupa jurnal yang telah dipreprocessing dan diekstrak dari format PDF menjadi teks menggunakan library PDF Miner, kami melatih model GPT-2 dengan menggunakan model pre-trained dari HuggingFace yang disediakan oleh "Cahya/GPT-2-small-Indonesian-522M".

## Fitur Utama

1. **Pengolahan Data**: Konversi jurnal dari format PDF ke teks menggunakan PDF Miner.
2. **Pelatihan Model**: Menggunakan model pre-trained GPT-2 dari HuggingFace untuk melatih model pada dataset jurnal yang telah dipreprocessing.
3. **Generasi Abstrak**: Menggunakan model GPT-2 untuk menghasilkan abstrak untuk setiap jurnal.
4. **Evaluasi Kualitas Abstrak**: Menggunakan metrik BLEU untuk mengevaluasi kesesuaian dan kualitas abstrak yang dihasilkan oleh model.

## Teknologi yang Digunakan

- **Python**: Bahasa pemrograman utama untuk pengembangan.
- **PDF Miner**: Untuk ekstraksi teks dari dokumen PDF.
- **HuggingFace Transformers**: Library untuk model bahasa GPT-2 dan pengolahan bahasa lainnya.
- **BLEU Score**: Metrik evaluasi untuk mengukur kualitas abstrak yang dihasilkan.

## Cara Penggunaan

1. **Pra-Pengolahan Data**: Ekstraksi teks dari jurnal PDF menggunakan PDF Miner.
2. **Pelatihan Model**: Menggunakan script pelatihan untuk melatih model GPT-2 dengan dataset yang telah dipreprocessing.
3. **Generasi Abstrak**: Menjalankan script generasi untuk menghasilkan abstrak berdasarkan teks jurnal.
4. **Evaluasi Kualitas Abstrak**: Menggunakan skor BLEU untuk mengevaluasi kualitas abstrak yang dihasilkan.

## Kontribusi

Kami mengundang kontribusi dari komunitas untuk pengembangan dan perbaikan projek ini. Anda dapat membantu dengan mengirimkan pull request untuk fitur baru, perbaikan bug, atau peningkatan dokumentasi.
