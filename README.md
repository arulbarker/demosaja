# Stok Gudang — Demo Aplikasi Stok Gudang Profesional

Aplikasi demo (dummy) manajemen stok gudang berbasis satu file `index.html`. Semua fitur bisa diklik dan terlihat berfungsi — untuk keperluan konten/peraga (iklan Meta Ads). Tidak ada backend atau data asli.

**Live:** https://arulbarker.github.io/demosaja/

## Fitur
Beranda (KPI nilai stok, stok menipis + kirim PO WA), Barang (cari, kategori, detail, tambah), Scan barcode (simulasi), Transaksi (masuk/keluar/retur dengan konversi satuan pcs/dus/karton), Stock opname, WhatsApp (notif stok menipis, laporan harian, template pesan), Pengguna & peran, Log aktivitas, Export laporan (Excel CSV / PDF).

## Cara pakai
- Buka `index.html` langsung di browser (double-click), atau buka URL live di HP.
- Di HP: menu browser → **Add to Home Screen** untuk tampilan fullscreen seperti app asli.
- Tombol **Reset demo** (pojok kanan atas) mengembalikan ke kondisi awal untuk take berikutnya.
- Uji kalkulasi kritis: buka `index.html?test` lalu lihat Console (13 test konversi satuan, validasi stok, nilai stok).

Panduan deploy: lihat [docs/deploy-github-pages.md](docs/deploy-github-pages.md).
