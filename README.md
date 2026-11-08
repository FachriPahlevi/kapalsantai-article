# Artikel WordPress Kapalsantai

Repository ini menyimpan template Elementor, gambar, dan catatan SEO artikel Kapalsantai.

## Komodo Island Tour

- `artikel/komodo-island-tour/templates/`: template Elementor v2, v3, dan v4. V4 adalah revisi terbaru yang disiapkan; tampilannya perlu diperiksa di situs.
- `artikel/komodo-island-tour/gambar/`: lima gambar WebP yang dapat diunggah ke WordPress Media Library.
- `artikel/komodo-island-tour/seo/`: nilai Yoast SEO yang perlu diisi pada halaman WordPress.

Impor template JSON melalui ikon folder di editor Elementor. Beberapa gambar dalam template merujuk ke Media Library situs sementara dan satu gambar tertanam sebagai HTML; periksa dan hubungkan ulang gambar setelah impor bila diperlukan. Pengaturan Yoast tidak otomatis terisi oleh template JSON.

Core WordPress, konfigurasi lokal, media, dan plugin/tema pihak ketiga dikecualikan dari Git. Plugin atau tema khusus baru di `public_html/wp-content/plugins/` atau `public_html/wp-content/themes/` dapat dilacak; simpan hasil artikel di `artikel/`.
