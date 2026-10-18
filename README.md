# Pagodev

Website portofolio Pagodev - Modern Software House & IT Solutions, Timika.

## Struktur
```
docs/                      # seluruh isi situs (GitHub Pages + hosting)
├─ index.html              # halaman utama
├─ foto/                   # logo yang dipakai di halaman
├─ demo/                   # demo interaktif: erp, rekam-medis, siswa, kasir, desa, gereja
└─ video/                  # video demo (diputar dari GitHub Pages)
aset-logo/                 # arsip logo yang belum dipakai (tidak dipublikasikan)
.cpanel.yml                # instruksi deploy ke cPanel (Jagoan Hosting)
```

## Demo
- Enam demo: ERP & Inventory, Rekam Medis, Smart Campus (siswa, LMS, RFID), Kasir/POS, Sistem Informasi Kampung, Sistem Informasi Gereja
- Akun demo: `admin` / `admin123` (data contoh, tersimpan di browser pengunjung)

## Deploy
1. Commit & push ke branch `main`.
2. cPanel > Git Version Control > Manage > **Update from Remote**.
3. Klik **Deploy HEAD Commit**. Isi `docs/` disalin ke `public_html/pagodev/` (folder `video/` tidak disalin karena hosting memblokir file video; video diputar dari GitHub Pages).

GitHub Pages juga membaca dari folder `docs/`.
