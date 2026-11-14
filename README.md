# Adli Anara Sofian — Personal Student Dashboard

Website profil pribadi dan Dashboard Tugas Praktikum yang dibuat menggunakan HTML, CSS, dan JavaScript murni.

## Struktur proyek

```text
adli-anara-sofian/
├── index.html
├── style.css
├── script.js
├── profile.jpeg
└── README.md
```

## Menjalankan secara lokal

1. Buka folder proyek ini di VS Code.
2. Pastikan `index.html`, `style.css`, `script.js`, dan `profile.jpeg` berada pada folder yang sama.
3. Buka `index.html` menggunakan browser atau ekstensi Live Server.
4. Coba tambah tugas, tandai selesai, hapus tugas, dan gunakan filter status.

## Fitur

- Profil mahasiswa dan foto pribadi.
- Ringkasan total tugas, tugas aktif, dan tugas selesai.
- Menambah tugas beserta mata kuliah dan tenggat opsional.
- Menandai tugas selesai atau aktif kembali.
- Menghapus tugas.
- Filter Semua, Aktif, dan Selesai.
- Statistik dan progress bar otomatis.
- Penyimpanan data melalui `localStorage`.
- Tampilan responsif untuk laptop dan perangkat mobile.

## Deployment melalui GitHub dan Vercel

1. Buat repository GitHub baru.
2. Unggah seluruh file proyek ke root repository.
3. Impor repository tersebut ke Vercel.
4. Pilih Framework Preset: `Other`.
5. Pastikan Root Directory mengarah ke folder yang berisi `index.html`.
6. Untuk proyek HTML/CSS/JavaScript statis, Build Command dikosongkan.
7. Klik Deploy dan uji URL produksi.

## Catatan

Data tugas disimpan di `localStorage` pada browser dan perangkat yang digunakan. Data tidak otomatis tersinkronisasi ke browser atau perangkat lain.

Jangan membagikan informasi pribadi yang tidak diperlukan pada repository atau website publik.
