# Artikel WordPress Kapalsantai

Repository ini menyimpan template Elementor, gambar, dan catatan SEO artikel Kapalsantai.

## Komodo Island Tour

- `artikel/komodo-island-tour/templates/`: template Elementor v2, v3, dan v4. V4 adalah revisi terbaru yang disiapkan; tampilannya perlu diperiksa di situs.
- `artikel/komodo-island-tour/gambar/`: lima gambar WebP yang dapat diunggah ke WordPress Media Library.
- `artikel/komodo-island-tour/seo/`: nilai Yoast SEO yang perlu diisi pada halaman WordPress.

Impor template JSON melalui ikon folder di editor Elementor. Beberapa gambar dalam template merujuk ke Media Library situs sementara dan satu gambar tertanam sebagai HTML; periksa dan hubungkan ulang gambar setelah impor bila diperlukan. Pengaturan Yoast tidak otomatis terisi oleh template JSON.

Core WordPress, konfigurasi lokal, media, dan plugin/tema pihak ketiga dikecualikan dari Git. Plugin atau tema khusus baru di `public_html/wp-content/plugins/` atau `public_html/wp-content/themes/` dapat dilacak; simpan hasil artikel di `artikel/`.

## Menjalankan WordPress lokal untuk rekan tim

Persyaratan: Docker dan Docker Compose. Dari folder repository jalankan:

```bash
docker compose up -d
```

Buka `http://localhost:8080`, lalu selesaikan instalasi WordPress. Instal plugin Elementor dan tema Astra melalui dashboard WordPress, lalu impor template dari folder `artikel/komodo-island-tour/templates/` melalui library Elementor. Unggah gambar dari folder `artikel/komodo-island-tour/gambar/` ke Media Library dan hubungkan kembali gambar yang diperlukan. Data Docker disimpan dalam volume lokal; hentikan layanan dengan `docker compose stop`.

Setup ini membuat **WordPress baru**, bukan salinan situs yang sudah ada. Isi halaman, pengaturan, pengguna, plugin lain, dan media situs lama tersimpan pada database/instalasi lama dan tidak ada di repository. Untuk replika yang sama, diperlukan ekspor database dan media yang telah ditinjau untuk informasi sensitif, serta penyesuaian URL dengan alat migrasi WordPress. Template saat ini juga dapat merujuk ke ID media dan URL situs asal; periksa setiap gambar setelah impor.

Port dapat diubah melalui variabel `WORDPRESS_PORT`. Kata sandi database bawaan hanya untuk pengembangan lokal; atur `LOCAL_DB_NAME`, `LOCAL_DB_USER`, `LOCAL_DB_PASSWORD`, dan `LOCAL_DB_ROOT_PASSWORD` melalui environment atau file `.env` lokal jika perlu. File `.env` tidak dimasukkan ke Git.
