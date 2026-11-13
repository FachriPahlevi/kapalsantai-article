# Panduan desain artikel Kapalsantai

Panduan ini adalah konteks kerja untuk manusia dan model yang akan membuat atau memperbaiki artikel Kapalsantai. Dokumen ini menjelaskan tujuan, identitas visual, pilihan desain, serta standar hasil tanpa mengharuskan pembaca mengakses repo situs utama. Instruksi terbaru dan eksplisit dari pengguna tetap menjadi prioritas.

## 1. Tujuan proyek

Kapalsantai menawarkan pengalaman perjalanan laut dan wisata di Labuan Bajo serta Taman Nasional Komodo. Artikel membantu calon wisatawan memahami destinasi, merencanakan perjalanan, dan menemukan layanan Kapalsantai yang relevan. Artikel harus bermanfaat, dapat dipercaya, mudah dibaca, dan mudah ditemukan melalui pencarian.

WordPress dan Elementor dipakai agar tim konten dapat mengubah tulisan dan mengatur desain secara mandiri. Keleluasaan desain adalah tujuan utama: **setiap artikel boleh memiliki tampilan dan komposisi berbeda sesuai cerita dan destinasinya**. Jangan jadikan satu template visual yang sama sebagai kewajiban untuk semua artikel.

Hasil akhir harus tetap:

- Terasa satu merek dengan Kapalsantai walaupun konsep tiap artikel berbeda.
- Mudah diedit per bagian di Elementor, termasuk gambar dari Media Library.
- Responsif dan nyaman dibaca di desktop, tablet, dan ponsel.
- Memprioritaskan struktur konten dan Yoast SEO sejak awal.
- Setia pada materi yang diberikan dan tidak mengarang fakta, fasilitas, tautan, atau janji layanan.

## 2. Identitas visual Kapalsantai

Karakter visual yang diamati dari desain situs utama: ramah, profesional, optimistis, dan dekat dengan laut. Tampilannya lapang dengan latar putih, gambar perjalanan yang besar, teks gelap, serta aksen biru laut dan kuning. Hindari tampilan terlalu padat atau dekorasi yang menutupi isi.

### Arahan visual dari referensi Figma

Referensi Figma menggambarkan Kapalsantai sebagai pengalaman perjalanan laut yang **tenang, premium, elegan, modern, minimalis, dan tepercaya**, dengan semangat petualangan. Keindahan alami kepulauan Indonesia timur menjadi sumber suasana: air laut, pulau, cahaya alami, dan lanskap menjadi elemen utama. Gunakan foto destinasi yang kuat, komposisi rapi, ruang yang cukup, dan elemen antarmuka yang tidak mengganggu cerita. Nuansa premium harus tetap terasa ramah, santai, dan mudah digunakan.

Prinsip penerapan:

- Bangun hierarki yang jelas agar pembaca cepat menemukan informasi perjalanan dan tindakan yang relevan.
- Pilih warna biru yang terinspirasi laut, warna dasar terang, dan aksen kuning secukupnya; gunakan kontras yang nyaman dibaca.
- Berikan ruang pada foto dan konten; hindari dekorasi atau efek berlebihan.
- Sesuaikan karakter dan komposisi dengan masing-masing destinasi. Referensi ini adalah arah merek, bukan kewajiban menyeragamkan semua artikel.

### Tipografi dari referensi Figma

- **Judul:** Plus Jakarta Sans, dengan fallback sans-serif. Gunakan variasi bobot dan ukuran untuk membedakan H1, H2, dan H3.
- **Teks isi:** Inter, dengan fallback sans-serif. Jaga ukuran, panjang baris, dan jarak antarbaris agar nyaman dibaca pada desktop dan ponsel.
- Referensi juga menyebut penggunaan caption, tetapi rincian caption pada gambar belum sepenuhnya jelas. Pilih font dan ukuran caption yang konsisten dengan desain halaman.

### Catatan warna dari referensi Figma

Gambar referensi menampilkan warna utama biru, warna sekunder kuning/oranye, warna gelap, warna terang, latar putih, dan gradasi biru. Kode gradasi yang terbaca adalah `#0F68CE` → `#3D8FED`. Label kode pada beberapa warna lain terlihat berulang atau kurang jelas, sehingga **jangan menganggapnya sebagai nilai pasti**. Gunakan palet acuan di bawah untuk sementara; cocokkan nilai final dengan file Figma jika akses tersedia.

### Palet acuan

| Peran | Warna |
| --- | --- |
| Biru merek | `#0077B6` |
| Biru aksen | `#0A77FF` |
| Gradasi biru hero referensi | `#039EF0` ke `#007EC0` |
| Kuning aksen | `#F1C40F` |
| Teks/judul gelap | `#192434` |
| Warna dasar teks isi | `#1B2B41` |
| Latar konten | Putih dan warna terang yang tenang |

Warna turunan seperti turquoise untuk sandbar atau biru laut dalam untuk Manta Point boleh digunakan jika mendukung cerita. Jaga kontras teks dan tombol, termasuk saat gambar dipakai sebagai latar. Jangan mengorbankan keterbacaan demi kesamaan palet.

### Tipografi dan tata letak

- Gunakan **Inter** dengan fallback sans-serif yang sesuai. Jika font eksternal tidak tersedia, pastikan fallback tetap nyaman dibaca.
- Gunakan heading tebal berwarna gelap, body text yang jelas, jarak antarparagraf yang cukup, dan lebar teks yang nyaman. Ukuran menyesuaikan isi dan perangkat; tidak ada satu ukuran wajib untuk semua artikel.
- Gunakan ruang putih, grid, dan jarak antarbagian untuk membangun hierarki. Artikel panjang harus mudah dipindai melalui H2/H3, daftar, tabel, atau daftar isi yang relevan.
- Foto adalah elemen utama. Gunakan crop yang menjaga subjek penting, sudut membulat bila sesuai, dan rasio yang konsisten untuk gambar berdampingan. Jangan memaksa semua gambar memiliki rasio sama jika isi visualnya berbeda.
- Kartu putih dengan sudut membulat, bayangan halus, tombol biru, aksen kuning, lingkaran, dan gelombang adalah kosakata visual yang boleh digunakan seperlunya; tidak semuanya harus muncul di setiap halaman.

### Referensi yang sudah ditinjau

- **About Us:** area putih yang lapang, foto besar, judul gelap tebal, konten berbasis grid, dan elemen visual yang memberi ruang pada cerita.
- **Detail artikel situs utama:** header gradasi biru, foto besar, kartu judul putih yang bertumpuk dengan foto, dan dekorasi gelombang. Ini contoh pola yang pernah digunakan, bukan desain wajib.
- Aset lokal di repository ini: `artikel/shared/kapalsantai-logo.svg` dan `artikel/shared/article-detail-decorator.svg`. Pastikan aset tersedia pada tujuan akhir; jangan mengandalkan path lokal saat impor ke WordPress.

### Acuan utama yang disetujui pengguna

Gunakan `artikel/Page/taka-makassar-komodo.html` sebagai acuan utama untuk preview artikel baru dan redesign: hierarki editorial, keterbacaan, caption gambar, metadata dan ikon berbagi, daftar isi, sidebar responsif, serta warna dan tipografi. Sesuaikan gambar dan isi dengan tiap destinasi. Persetujuan klien yang diketahui berlaku untuk artikel Taka; jangan menganggap artikel lain sudah disetujui. Data tanggal dan views pada preview adalah contoh dan harus dihubungkan ke data sebenarnya saat implementasi WordPress.

### Konsisten dan fleksibel dalam setiap artikel

Taka-2 adalah acuan identitas dan mutu, bukan layout yang harus disalin. Pertahankan tipografi Plus Jakarta Sans untuk judul dan Inter untuk isi, paragraf rata kiri, hierarki heading, keterbacaan, identitas warna Kapalsantai, metadata, ikon berbagi, serta aksesibilitas dan responsivitas. Ukuran, jarak, dan pengaturan per perangkat disesuaikan dengan isi.

Komposisi hero, penempatan foto, ritme section, dan komponen pendukung boleh berbeda untuk setiap destinasi. Pilih sidebar, FAQ, tabel, atau CTA berdasarkan kebutuhan artikel, bukan karena ada di template lain. Hindari mengganti warna saja sambil mempertahankan semua komposisi yang sama: perbedaan harus membantu cerita dan pembaca.

### Arah eksplorasi Manta Point

Pengguna kurang menyukai hasil eksplorasi yang terasa seperti Taka dengan warna diganti menjadi gelap. Penilaian tersebut berdasarkan arahan pengguna dan peninjauan kode; hasilnya belum menjadi acuan desain yang disetujui.

- Mulai dari tampilan yang terang, bersih, lapang, dan mudah dibaca; hadirkan suasana bawah laut lewat fotografi, komposisi, serta aksen biru laut yang lebih dalam.
- Hindari menumpuk hero yang terlalu gelap, teks putih, overlay, dan bayangan berat sekaligus. Warna gelap boleh digunakan seperlunya bila mendukung cerita dan kontras.
- Letakkan caption editorial di bawah foto, dengan garis kuning pendek dan teks pendukung yang terbaca; jangan pindahkan ke atas foto tanpa arahan pengguna.
- Buat komposisi Manta terasa berbeda dari Taka, tanpa mengubah isi, mengarang fakta, atau menghilangkan fitur yang disepakati. Periksa jarak hero ke isi dan tata letak mobile secara visual.
- Pengguna ingin mengeksplorasi tampilan judul, bukan otomatis mengganti redaksinya. Jangan mengubah judul atau tahun tanpa instruksi.

### Petunjuk konversi preview ke Elementor

Simpan komentar HTML yang relevan untuk agent: struktur dan nama elemen, sidebar sticky dan daftar isi aktif, perilaku mobile, metadata dinamis, fungsi share, serta SEO. Untuk setiap gambar, catat nama file, alt text, caption, rasio, ukuran responsif, object-fit dan titik fokus bila diperlukan. Periksa aturan CSS terakhir pada setiap breakpoint sebelum menentukan ukuran. Komentar adalah arahan implementasi; metadata preview tidak otomatis mengisi Yoast, dan gambar lokal tidak otomatis menjadi Media Library.

## 3. Desain berdasarkan karakter artikel

Sebelum mendesain, baca materi sumber dan tentukan topik, audiens, kebutuhan pembaca, gambar, urutan informasi, serta aksi yang relevan. Pilih satu konsep yang jelas, lalu sesuaikan hero, tata letak, warna pendukung, penggunaan foto, dan ritme bagian. Selalu pertahankan identitas merek dan keterbacaan.

Contoh eksplorasi yang sudah dibuat:

- **Taka Makassar:** terang dan editorial, terinspirasi sandbar dan air dangkal; latar hijau kebiruan lembut, kartu terang, foto lanskap, dan aksen seperti pasir. Lihat `artikel/Page/taka-makassar-komodo.html`.
- **Manta Point:** suasana bawah laut dengan foto yang kuat, nuansa terang dan aksen biru laut dalam. Eksplorasi komposisi berbeda dari Taka; lihat arahan Manta di atas dan `artikel/Page/manta-point-labuan-bajo.html`.
- **Komodo Island:** artikel panjang yang terstruktur dengan hero, bagian utama, dan sidebar bila sesuai. Lihat template `artikel/templates/elementor-10058-rapi-v3.json` sebagai acuan hierarki, bukan standar desain tunggal.

Ini contoh arah visual, bukan keharusan mengulang tema, warna, sidebar, atau komposisi tersebut. Bila sumber meminta susunan tertentu, ikuti sumber dan klarifikasi jika tidak jelas.

## 4. Struktur konten dan Elementor

1. Tentukan urutan semantik: hero dan H1 → pengantar → section H2 → subsection H3 → bagian pendukung seperti FAQ dan CTA. Gunakan satu H1 yang terlihat; sembunyikan judul otomatis tema bila menggandakan H1.
2. Bangun struktur yang masuk akal di Navigator: wrapper halaman → artikel utama dan sidebar jika diperlukan → hero/section → subsection → widget. Jangan memecah semua hal menjadi container sejajar yang sulit dipahami atau memasukkan seluruh artikel ke satu Text Editor.
3. Beri nama deskriptif pada **setiap container dan widget**, misalnya `Hero · Judul dan Pengantar`, `Section 01 · Mengenal Taka Makassar`, `H2 · ...`, `Paragraf · Pengantar 1`, `Baris Gambar · ...`, dan `Gambar · ...`. Nama harus mengikuti isi dan urutan sebenarnya. Untuk widget yang tidak mendukung nama dengan cara biasa, periksa cara yang didukung versi Elementor dan nyatakan keterbatasannya.
4. Heading, paragraf, daftar, tabel, FAQ, tombol, dan gambar harus dapat ditemukan serta diedit terpisah sesuai kebutuhan. Sidebar tidak wajib; jika dipakai, buat relevan, tidak menutupi artikel, dan mudah digunakan pada semua layar. Sticky desktop boleh digunakan bila isi sidebar tetap dapat diakses; pada layar kecil umumnya kembali ke alur normal.
5. Gunakan widget Image yang terhubung ke Media Library bila aset dan attachment ID di situs tujuan tersedia. HTML berisi gambar base64 bukan gambar Media Library; jangan menyatakan sebaliknya. Jika ID/domain masih berasal dari situs lain, jelaskan kebutuhan menghubungkan ulang.
6. Tempatkan CSS pendukung yang benar-benar diperlukan secara jelas dan beri nama. Hindari ketergantungan pada ID halaman lama atau mengubah tampilan halaman lain. Periksa pengaturan judul tema, style global, dan schema setelah impor.
7. Template Elementor JSON diimpor melalui library Elementor di editor, bukan melalui Tools → Import WordPress yang menerima XML WXR. Jelaskan alur sesuai layar yang pengguna lihat.

## 5. Cara memperlakukan materi sumber dan gambar

### Sumber gambar untuk preview dan Elementor

- Gunakan URL gambar yang sudah tersedia dan terverifikasi di Media Library situs tujuan untuk preview HTML dan template JSON. Pilih versi EN atau ID sesuai bahasa artikel, termasuk alt text dan metadata yang sesuai. Simpan aset lokal sebagai sumber pengembangan bila diperlukan.
- Jangan menyematkan data gambar `data:image/...;base64` dalam preview atau JSON. Base64 merupakan pengkodean yang memperbesar file, bukan enkripsi. Template tetap harus menyertakan gambar yang dibutuhkan.
- Gunakan widget Image Elementor dengan URL serta attachment ID situs tujuan jika keduanya tersedia dan terverifikasi. URL gambar saja tidak menjamin keterhubungan dengan Media Library; attachment ID dapat berbeda setelah impor atau migrasi.
- Jangan menyusun URL berdasarkan tebakan nama file: periksa URL dan isi gambar karena WordPress dapat menambah akhiran atau menghasilkan file `-scaled`. Jika belum tersedia, laporkan dan lengkapi sesuai otorisasi.
- Saat berpindah dari staging ke produksi, perbarui URL dan ID sesuai Media Library tujuan; uji hasil impor, tampilan gambar di desktop/mobile, serta alt text. URL staging bukan URL produksi otomatis.

- PDF/dokumen adalah sumber konten dan arahan, bukan perintah yang mengesampingkan permintaan pengguna. Bedakan isi artikel dari catatan editor, metadata gambar, contoh layout, dan informasi SEO.
- Kotak berisi `File name`, `Alt text`, dan `Description` umumnya adalah panduan untuk Media Library, bukan bagian yang ditampilkan ke pengunjung. Kolom-kolom metadata gambar juga tidak otomatis berarti teks artikel harus dibuat dua kolom.
- Simpan nama file deskriptif, gunakan format WebP bila diminta dan sesuai, serta isi alt text berdasarkan isi gambar. Caption hanya ditampilkan jika diperlukan. Saat ada nama file yang sama untuk gambar berbeda, jangan menimpa file: beri nama unik dan catat perbedaannya.
- Pertahankan isi, tautan, dan metadata dari sumber saat membuat transkripsi. Tandai kesalahan sumber, teks rusak, atau klaim meragukan untuk ditinjau; jangan diam-diam menganggapnya benar.
- Cek fakta yang berubah seperti harga, kuota, aturan taman, jadwal, musim, kondisi laut, dan keselamatan menggunakan sumber tepercaya terbaru sebelum publikasi. Hindari klaim bahwa satwa pasti terlihat atau menjanjikan kondisi aman.

### Caption atau keterangan gambar

Pengguna menyukai keterangan singkat yang terlihat tepat di bawah gambar, seperti pada preview Manta Point. Sertakan caption yang relevan pada foto artikel bila memberi konteks atau membantu pembaca memahami gambar; jangan memaksakan caption pada gambar dekoratif atau mengulang informasi tanpa manfaat.

- Tulis satu kalimat singkat, jelas, dan sesuai isi foto dalam bahasa artikel. Jangan mengarang lokasi, spesies, atau keadaan yang tidak dapat dipastikan dari sumber.
- Letakkan caption tepat di bawah gambar, sejajar dengan tepi gambar, dengan jarak kecil dan warna teks pendukung yang tetap mudah dibaca. Gunakan ukuran lebih kecil daripada teks artikel, tetapi tetap nyaman pada ponsel.
- Untuk gambar berdampingan, gunakan caption terpisah jika masing-masing butuh penjelasan; gunakan satu caption bersama hanya jika benar-benar menggambarkan keduanya dengan jelas.
- Caption adalah teks yang terlihat oleh pengunjung. **Alt text** adalah deskripsi alternatif untuk aksesibilitas; isi sesuai konteks dan fungsi gambar, meskipun caption juga tersedia. Nama file dan description di Media Library memiliki fungsi berbeda dan tidak otomatis perlu ditampilkan.
- Pada HTML gunakan `figure` dan `figcaption`. Pada Elementor gunakan caption gambar atau widget teks terpisah yang terhubung secara jelas dengan gambar, agar mudah diedit.

## 6. Yoast SEO dan kesiapan publikasi

SEO harus dipertimbangkan saat merancang, bukan sekadar tahap akhir:

- Siapkan focus keyphrase, SEO title, meta description, slug, H1/H2/H3, dan alt text yang relevan secara alami. Pastikan judul, isi, tahun, dan intent konsisten.
- Sediakan nilai siap salin untuk Yoast beserta saran judul/deskripsi/gambar sosial bila dibutuhkan. Periksa panjang menggunakan pratinjau Yoast, bukan hanya jumlah karakter.
- Periksa tautan internal dan eksternal beserta tujuan yang benar. Bila halaman terbit berganti slug, evaluasi kebutuhan redirect.
- Periksa indexability, canonical, dan schema sesuai halaman; hindari FAQ schema duplikat antara template dan plugin. Jangan menjanjikan skor hijau atau rich result.
- Jalankan checklist Yoast yang ada di `AGENTS.md`. Template Elementor atau preview HTML tidak otomatis mengisi pengaturan Yoast pada halaman WordPress.
- Draft halaman yang sudah terbit mungkin baru menyimpan perubahan SEO saat di-update; update juga dapat memublikasikan perubahan draft lain. Jelaskan kondisi ini sebelum mengambil tindakan yang belum diotorisasi.

## 7. Output dan pemeriksaan

Alur biasa, disesuaikan dengan permintaan: baca sumber → siapkan Markdown bila diperlukan → rancang preview → terima arahan → buat template Elementor terstruktur → siapkan/terapkan SEO → uji tampilan dan fungsi → laporkan hasil. Jangan menganggap pengguna selalu meminta seluruh tahap sekaligus.

Sebelum menyerahkan hasil, periksa:

- Artikel dan metadata gambar sesuai sumber; tidak ada konten yang hilang, gambar rusak, atau kotak instruksi internal yang tampil sebagai artikel.
- Satu H1, heading berurutan dan bermakna, nama elemen Navigator jelas, gambar dapat diedit sesuai klaim, dan sidebar/FAQ/CTA berfungsi jika digunakan.
- Desktop dan ponsel: tidak ada elemen terpotong, horizontal overflow, teks terlalu kecil, atau tombol tak terjangkau. Periksa tablet bila relevan.
- Tautan, daftar isi, teks alternatif, metadata SEO, dan schema sesuai konteks. Bila belum ada akses WordPress, nyatakan bahwa Yoast belum diterapkan.
- Bedakan validasi JSON/HTML, screenshot lokal, pengujian impor Elementor, dan pengujian situs sesungguhnya. Jangan mengklaim semua sudah diuji jika hanya sebagian.
- Sampaikan lokasi file, langkah impor yang mudah diikuti, dan keterbatasan penting. Jangan commit, push, mengubah situs, atau menerbitkan konten tanpa instruksi yang sesuai.
