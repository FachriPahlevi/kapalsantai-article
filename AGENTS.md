# Konteks proyek artikel Kapalsantai

## Bahasa dan komunikasi
- Jawab dalam bahasa Indonesia dengan instruksi yang jelas dan mudah diikuti. Jika pengguna menulis dalam bahasa Inggris, awali dengan koreksi bahasa Inggris singkat hanya jika diperlukan, lalu jawab dalam bahasa Indonesia. Ikuti instruksi bahasa eksplisit pengguna.
- Saat memandu WordPress, jelaskan langkah berdasarkan tampilan pengguna dan gunakan nama tombol yang terlihat. Jangan mengasumsikan menu tertentu tersedia.

## Hasil yang diharapkan
- Artikel harus siap dipakai di Elementor dan mudah diedit: susun konten menjadi container dan widget terpisah untuk judul, bagian teks, dan gambar sesuai kebutuhan desain. Jangan memasukkan seluruh artikel ke dalam satu widget Text Editor.
- Pertahankan isi, gambar, desain responsif, dan kebutuhan SEO dari materi dan arahan pengguna. Jangan mengklaim gambar dapat diedit melalui Media Library jika sebenarnya tertanam dalam HTML.
- Utamakan hasil lengkap yang menyertakan gambar. Jika ada keterbatasan teknis, jelaskan sebelum menawarkan versi tanpa gambar.

## Alur impor Elementor
- Siapkan template Elementor berformat JSON untuk dimasukkan melalui editor Elementor. Dari halaman yang sedang diedit: klik ikon folder di area konten, gunakan fitur import template di jendela library, pilih file JSON, lalu masukkan template.
- Tools → Import → WordPress menerima ekspor WXR berformat XML; jangan arahkan pengguna mengunggah template JSON ke sana. Ekspor XML yang hanya menyimpan data Elementor di metadata dapat menghasilkan halaman kosong setelah impor, sehingga jangan menjanjikan bahwa jalur itu akan bekerja tanpa verifikasi.
- Jangan menyuruh pengguna menempel seluruh artikel ke editor kode WordPress ketika yang diminta adalah struktur widget Elementor terpisah.
- Validasi JSON dan struktur elemen sebelum menyerahkan file. Bedakan validasi file dari pengujian impor dan tampilan di situs; nyatakan bila belum diuji.

## Acuan pekerjaan Komodo Island Tour
- Template lengkap: /home/fachri/Downloads/kapalsantai-komodo-template-elementor.json. Isinya 42 container, 44 widget, dan lima gambar tertanam dalam widget HTML; gambar belum terdaftar di Media Library.
- Template ringan: /home/fachri/Downloads/kapalsantai-komodo-template-ringan.json. Gambar diganti penanda dan disimpan terpisah di /home/fachri/Downloads/kapalsantai-komodo-gambar. Gunakan hanya jika pengguna menginginkan atau membutuhkan alternatif ringan.
- Pengguna menyetujui alur template lengkap melalui Elementor. Belum ada bukti eksplisit dalam percakapan bahwa impor dan tampilan akhir telah diuji di situs.

## Acuan struktur template Elementor
Gunakan `/home/fachri/Downloads/elementor-10058-rapi-v2.json` sebagai referensi konkret hierarki dan keterbacaan Structure/Navigator, sesuaikan dengan kebutuhan artikel; jangan menyalin klaim atau isi spesifiknya tanpa diminta.

- Susun hierarki: container pendukung CSS/schema bila diperlukan → wrapper halaman → container artikel utama dan sidebar bila dibutuhkan → hero dan section bernomor → subsection → widget individual. Jangan membuat puluhan container sejajar tanpa pengelompokan semantik.
- Beri label deskriptif melalui `_title` untuk container dan widget, misalnya `Hero · Judul & Intro`, `Section 01 · ...`, `Sub · ...`, `H2 · ...`, `Teks · ...`, `FAQ · ...`, dan `Tombol · ...`. Beri label gambar yang jelas juga; referensi belum melabeli semua widget gambarnya.
- Pisahkan heading H1/H2/H3, paragraf, daftar, tabel, FAQ, dan tombol agar mudah ditemukan dan diedit. Kelompokkan gambar berdampingan dalam container baris, dengan penyesuaian responsif di perangkat kecil.
- Pertahankan satu H1 yang terlihat; periksa judul bawaan tema agar tidak duplikat. Paragraf pengantar Komodo mengikuti referensi satu kolom; kotak biru di dokumen sumber adalah metadata gambar, bukan konten atau instruksi dua kolom.
- Gunakan widget gambar yang terhubung ke Media Library bila aset dan ID tersedia; bila belum tersedia, jelaskan keterbatasannya dan beri penanda yang mudah diganti. Template referensi masih memiliki satu gambar HTML base64, sehingga jangan menganggap seluruh gambarnya sudah terhubung ke Media Library.
- Template referensi memiliki sidebar berisi artikel terbaru, topik, fakta, dan CTA; gunakan sidebar hanya bila diminta atau sesuai desain. CSS global/schema dikelompokkan dan diberi label jelas bila diperlukan, bukan memindahkan seluruh konten artikel ke HTML.
- Pastikan struktur, gambar, lebar konten, dan tampilan mobile diperiksa sesuai lingkungan; jangan mengklaim sudah diuji secara visual jika hanya memvalidasi JSON.

### Penamaan wajib di Structure/Navigator
- Setiap container, section, dan widget harus diberi `_title` yang unik dan menjelaskan fungsi atau isinya. Jangan tinggalkan label generik seperti `Container`, `Section`, `Image`, atau `Text Editor` tanpa konteks.
- Gunakan nama ringkas dengan hierarki yang mudah dibaca, misalnya `01 · Wrapper Halaman` → `02 · Artikel Utama` → `Hero · Judul dan Pengantar` → `Baris Gambar Utama` → `Gambar · Komodo Beristirahat`; untuk teks gunakan `Paragraf · Pengantar 1` atau label isi yang relevan.
- Nama mengikuti konten sebenarnya dan urutan halaman. Sebelum menyerahkan template, telusuri seluruh struktur termasuk elemen bersarang untuk memeriksa label kosong, generik, atau membingungkan dan memperbaikinya.

## Checklist Yoast SEO untuk artikel
Gunakan checklist ini saat diminta menyiapkan atau melengkapi SEO. Sesuaikan dengan topik, isi aktual, tahun, bahasa, dan tujuan pencarian artikel; jangan mengarang fakta, URL, atau mengklaim skor hijau sudah tercapai tanpa memeriksa Yoast di situs.

- [ ] Tentukan satu focus keyphrase utama yang relevan dengan judul dan maksud pencarian; gunakan secara alami di konten.
- [ ] Siapkan SEO title yang deskriptif, memuat keyphrase, dan sesuai tahun artikel; periksa pratinjau lebar judul di Yoast.
- [ ] Siapkan meta description yang merangkum isi dan manfaat bagi pembaca; periksa pratinjau panjang di Yoast.
- [ ] Tentukan slug ringkas, unik, dan relevan; periksa konflik dengan halaman lain, termasuk Trash. Catat URL lama dan kebutuhan redirect jika mengubah halaman yang sudah dipublikasikan.
- [ ] Periksa satu H1 yang terlihat, hierarki H2/H3, keyphrase dalam pengantar dan subjudul jika alami, serta relevansi dan kelengkapan isi.
- [ ] Periksa SEO analysis dan readability analysis di Yoast; tindak lanjuti masalah yang relevan tanpa memaksakan skor atau merusak kualitas tulisan.
- [ ] Periksa alt text yang menggambarkan gambar sesuai isinya, nama file yang relevan, serta caption bila diperlukan. Jangan memasukkan keyphrase secara paksa.
- [ ] Tambahkan tautan internal dan eksternal yang relevan setelah memastikan tujuan dan URL benar; periksa tautan dan anchor internal.
- [ ] Periksa Search appearance: SEO title, meta description, slug, dan pratinjau. Periksa Social media appearance: judul, deskripsi, dan gambar sosial bila diperlukan dan tersedia.
- [ ] Periksa Schema sesuai jenis halaman dan kontennya; hindari schema FAQ duplikat jika template atau plugin lain sudah menghasilkan schema serupa. Jangan menjanjikan rich result.
- [ ] Periksa Advanced: pengindeksan, pengaturan tautan, dan canonical sesuai kebutuhan situs; gunakan default jika tidak ada alasan jelas untuk mengubahnya.
- [ ] Tandai Cornerstone content hanya jika pengguna menginginkannya atau halaman memang merupakan artikel pilar; jangan aktifkan otomatis.
- [ ] Related keyphrase, pelacakan performa, saran internal, dan Insights bergantung pada fitur/plugin atau akun yang tersedia; kerjakan jika tersedia dan relevan, laporkan jika terbatas.
- [ ] Simpan/update hanya sesuai otorisasi pengguna. Yoast dapat memperingatkan bahwa perubahan SEO pada draft halaman yang telah dipublikasikan tidak tersimpan sampai halaman di-update; jelaskan dampaknya karena update dapat menerbitkan perubahan draft juga.
- [ ] Laporkan nilai yang diisi, apa yang telah diperiksa, dan hal yang belum bisa diverifikasi pada situs.

### Data yang disiapkan agent
Untuk setiap artikel sediakan daftar siap salin: focus keyphrase, SEO title, slug, meta description, social title/description jika dibutuhkan, saran alt text per gambar, tautan internal yang benar-benar tersedia, dan jenis schema yang disarankan. Bila data atau akses belum tersedia, buat rekomendasi dan tandai sebagai belum diterapkan.
