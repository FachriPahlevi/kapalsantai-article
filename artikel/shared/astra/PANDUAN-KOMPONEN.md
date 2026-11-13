# Komponen header dan footer Astra

## Nama header yang direncanakan

- **Header · Classic:** satu bentuk yang tetap sama saat halaman digulir.
- **Header · Floating to Full:** kapsul mengambang saat halaman berada di atas, lalu berubah menjadi bilah penuh saat halaman digulir, mengikuti referensi Kanawa.

Keduanya perlu responsif dan disiapkan sebagai template terpisah dengan aturan tampilan yang tidak saling bertumpuk. Nama ini adalah keputusan penamaan; kedua template belum dibuat atau diuji di situs. File ekspor Astra sebelumnya bukan dua template tersebut.

Nama bawaan di Customizer mengikuti label Astra; ekspor yang tersedia tidak menyediakan nama kustom untuk komponen ini.

- **HTML 1 — Navigasi Kapalsantai:** dua tautan About Us dan Book a Boat di desktop, serta dropdown dengan tautan yang sama di mobile.
- **Site Title & Logo — Logo Kapalsantai:** logo di sisi kiri header.
- **HTML 1 di Footer Builder — Footer Kapalsantai:** konten footer, berbeda dari HTML 1 pada Header Builder.
- **Additional CSS — Tampilan Kapalsantai:** CSS header, dropdown, dan footer. CSS harus dipertahankan di Additional CSS; ekspor Astra ini tidak membuktikan bahwa CSS tersebut ikut terimpor.

File `astra-navbar-mobile-dropdown.json` adalah salinan ekspor Astra terbaru dengan susunan mobile yang disesuaikan. File ini tetap memuat pengaturan Customizer lain sehingga impor dapat menimpanya. Belum diuji dengan mengimpor ke situs. Pastikan HTML 1 benar-benar tampil pada desktop dan mobile dan dropdown terbuka tanpa menu layar penuh.
