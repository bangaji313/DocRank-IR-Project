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

## Instalasi Library yang Dibutuhkan
Untuk menjalankan aplikasi ini, Anda perlu menginstal library berikut. Jalankan perintah berikut di terminal atau command prompt Anda:
```bash
pip install flask
pip install sastrawi
pip install PyPDF2
pip install python-docx
pip install rank-bm25

## Cara Menjalankan
1. **Clone Repository**
   git clone https://github.com/bangaji313/DocRank-IR-Project.git


## Rencana Pengembangan ke Depan
- Dukungan untuk pencarian berbasis gambar atau suara.
- Implementasi pencarian berbasis semantik untuk hasil yang lebih mendalam.
