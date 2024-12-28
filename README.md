# DocRank: Aplikasi Temu Balik Informasi dengan BM25

**DocRank** adalah aplikasi berbasis web yang dirancang untuk melakukan temu balik informasi (information retrieval) pada dokumen bertema **pengobatan dan kesehatan herbal**. Aplikasi ini menggunakan metode **BM25** untuk menghitung relevansi dokumen terhadap query pengguna.

## Fitur Utama
1. **Proses Ekstraksi dan Preprocessing Dokumen**
   - Mendukung berbagai format dokumen: `.txt`, `.docx`, dan `.pdf`.
   - Tokenizing, stop word removal, dan stemming untuk menghasilkan kata dasar.

2. **Sistem Pencarian yang Efisien**
   - Menggunakan metode **BM25** untuk menghitung skor relevansi dokumen.
   - Menampilkan daftar dokumen yang relevan berdasarkan query pengguna.

3. **Antarmuka Pengguna Sederhana**
   - User-friendly interface untuk memudahkan pengguna melakukan pencarian.

## Teknologi yang Digunakan
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, dan JavaScript
- **Metode Information Retrieval**: BM25

## Cara Menggunakan
1. Upload dokumen ke folder dataset aplikasi.
2. Masukkan query pencarian di antarmuka pengguna.
3. Aplikasi akan menampilkan dokumen yang paling relevan beserta skor relevansinya.

## Tujuan Pengembangan
- Meningkatkan efisiensi temu balik informasi berbasis teks.
- Mendukung penelitian dan edukasi terkait pengobatan herbal di Indonesia.

## Rencana Pengembangan ke Depan
- Dukungan untuk pencarian berbasis gambar atau suara.
- Implementasi pencarian berbasis semantik untuk hasil yang lebih mendalam.
