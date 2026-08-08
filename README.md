# Portofolio — Ni Putu Dita Ari Pratiwi

## Struktur folder
```
portfolio-project/
├── index.html          → halaman utama
├── styles.css           → semua styling
├── assets/images/       → semua gambar (foto, mockup, sertifikat, screenshot IG)
└── README.md
```

## Cara pakai di VS Code
1. Extract/buka folder ini di VS Code.
2. Install extension **Live Server** (kalau belum ada).
3. Klik kanan `index.html` → **Open with Live Server**.
   (Atau cukup buka `index.html` langsung di browser — semua sudah pakai path relatif, jadi tidak akan rusak.)

## Mengganti gambar
Semua gambar ada di `assets/images/`. Untuk mengganti:
1. Simpan gambar baru dengan nama yang sama (atau ubah nama filenya).
2. Kalau ganti nama, update juga `src="assets/images/nama-file.jpg"` di `index.html`.

File yang saat ini dipakai:
- `portrait.jpg` — foto hero
- `lelangin-mockup.jpg` — studi kasus LelangIN
- `sutra-mockup.jpg` — proyek Sutra (Learn Balinese)
- `cert-bangkit.jpg`, `cert-cdmp.jpg`, `cert-kompetensi.jpg` — sertifikat
- `ig-sic.jpg`, `ig-gdsc.jpg`, `ig-genbi.jpg` — screenshot Instagram

## Bagian yang masih placeholder
Studi kasus **Nasi Padang** dan **SOMATCH** belum punya gambar mockup asli (tidak berhasil diekstrak bersih dari PDF sumber) — saat ini ditampilkan sebagai kotak label warna hijau muda. Tinggal:
1. Taruh gambar mockup di `assets/images/` (misal `nasi-padang-mockup.jpg`).
2. Ganti blok placeholder di `index.html` (cari komentar `Nasi Padang` / `SOMATCH`) dengan `<img src="assets/images/nama-file.jpg" alt="...">`.

## Font
Pakai Google Fonts via CDN (Space Grotesk, IBM Plex Sans, IBM Plex Mono) — butuh koneksi internet saat dibuka. Kalau mau offline, download font-nya dan ubah `@font-face` di `styles.css`.
