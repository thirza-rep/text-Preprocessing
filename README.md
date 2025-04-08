📝 Text Preprocessing dengan Python, NLTK, dan Sastrawi

Repositori ini berisi contoh implementasi sederhana dari tahapan Text Preprocessing dalam Bahasa Indonesia, meliputi:

Case Folding

Tokenizing

Stemming (menggunakan Sastrawi)

Stopword Removal (Filtering)

📌 Deskripsi

Program ini menerima input berupa satu kalimat ulasan pengguna (dokumen), kemudian memprosesnya melalui tahapan-tahapan pre-processing untuk membersihkan dan menormalisasi teks sebelum dianalisis lebih lanjut (misalnya untuk analisis sentimen, klasifikasi, dll).

📂 Struktur Proyek

.
├── preprocessing.py      # Script utama yang berisi proses pembersihan teks
├── README.md             # Dokumentasi ini

📦 Kebutuhan

Pastikan kamu telah menginstall pustaka berikut:

pip install nltk
pip install Sastrawi

▶️ Cara Menjalankan

python preprocessing.py

🔍 Contoh Output

# Dokumen awal
Dokumen: Barangnya sesuai harapan, cakep dan mulus. Penjualnya juga baik dan ramah. Overall, puas banget belanja di sini.

# Case Folding
Case Folding : barangnya sesuai harapan, cakep dan mulus. penjualnya juga baik dan ramah. overall, puas banget belanja di sini.

# Tokenizing
Token:
['barangnya', 'sesuai', 'harapan', 'cakep', 'dan', 'mulus', 'penjualnya', 'juga', 'baik', 'dan', 'ramah', 'overall', 'puas', 'banget', 'belanja', 'di', 'sini']

# Stemming
Hasil Stemming:
barang sesuai harap cakep dan mulus jual juga baik dan rah overall puas banget belanja di sini

# Stopword Removal
Hasil Setelah Stopword Removal:
['barang', 'harap', 'cakep', 'mulus', 'jual', 'baik', 'rah', 'overall', 'puas', 'banget', 'belanja']

📖 Penjelasan Tahapan

Tahapan

Deskripsi

Case Folding

Mengubah semua huruf menjadi huruf kecil (lowercase)

Tokenizing

Memecah teks menjadi token kata menggunakan RegexpTokenizer

Stemming

Mengembalikan kata ke bentuk dasarnya menggunakan Sastrawi Stemmer

Stopword Removal

Menghapus kata-kata umum yang tidak memiliki makna penting (stopwords)

📚 Referensi

NLTK Documentation

Sastrawi: Indonesian Stemmer

👨‍💻 Author

M. Thirza Salendra📧 Thirza1104@gmail.com🌐 GitHub @thirza-rep

