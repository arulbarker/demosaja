# Cara Deploy ke GitHub Pages

Repo: `https://github.com/arulbarker/demosaja`
URL live: `https://arulbarker.github.io/demosaja/`

## Sekali setup (aktifkan Pages)
1. Buka repo `demosaja` di GitHub → **Settings** → **Pages**.
2. Bagian **Build and deployment** → Source: **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Tunggu ±1 menit. URL muncul: `https://arulbarker.github.io/demosaja/`.

## Update aplikasi (setelah ada perubahan)
File yang wajib ada di root repo: `index.html`.

```bash
git add index.html
git commit -m "update demo"
git push
```

GitHub Pages otomatis memperbarui situs dalam ±1 menit. URL tetap sama.

## Buka di HP seperti app asli
1. Buka `https://arulbarker.github.io/demosaja/` di Chrome/Safari HP.
2. Menu browser → **Add to Home Screen** (Tambahkan ke Layar Utama).
3. Ikon muncul di homescreen → dibuka jadi **fullscreen tanpa address bar**.

## Catatan
- Repo publik. Ini demo dummy tanpa data/rahasia asli, jadi aman.
- Tombol **Reset demo** di app mengembalikan data ke kondisi awal (berguna sebelum tiap rekaman).
