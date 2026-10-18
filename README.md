# Pagodev

Website portofolio Pagodev - Modern Software House & IT Solutions, Timika.

## Struktur
```
docs/                      # seluruh isi situs (GitHub Pages + hosting)
├─ index.html              # halaman utama
├─ foto/                   # logo dan gambar
├─ demo/siswa/index.html   # demo interaktif Sistem Informasi Siswa
└─ video/                  # video demo
.cpanel.yml                # instruksi deploy ke cPanel (Jagoan Hosting)
```

## Demo
- Akun demo: `admin` / `admin123` (data contoh, tersimpan di browser pengunjung)

## Deploy
1. Commit & push ke branch `main`.
2. cPanel > Git Version Control > Manage > **Update from Remote**.
3. Klik **Deploy HEAD Commit**. Isi `docs/` disalin ke `public_html/pagodev/`.

GitHub Pages juga membaca dari folder `docs/`.
