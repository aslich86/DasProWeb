# DasProWeb

Proyek website profil profesional statis yang dibangun sebagai Submission Tugas Akhir Dicoding. Website ini menampilkan biodata, deskripsi diri, dan proyek unggulan milik Iwan Aslich.

---

## Struktur Proyek

```
DasproWeb/
├── index.html          # Halaman utama website
├── styles/
│   └── style.css       # Stylesheet utama
└── images/
    └── profile.jpg     # Foto profil
```

---

## Fitur

- **Header** — Menampilkan nama, jabatan, dan navigasi antar seksi.
- **Tentang Saya** — Deskripsi singkat latar belakang dan fokus bidang.
- **Proyek Unggulan** — Daftar proyek yang telah dikerjakan beserta deskripsinya.
- **Biodata (Aside)** — Foto profil bulat, domisili, fokus, dan misi pribadi.
- **Footer** — Informasi hak cipta dan keterangan submission.
- **Responsif** — Layout menyesuaikan tampilan di layar kecil (≤800px) menggunakan media query.

---

## Teknologi

| Teknologi | Keterangan |
|-----------|------------|
| HTML5 | Struktur dan semantik halaman |
| CSS3 | Styling, Flexbox layout, dan media query |

Tidak ada framework atau library eksternal yang digunakan. Semua dibangun dengan HTML dan CSS murni.

---

## Layout

Layout utama menggunakan **CSS Flexbox** dengan dua kolom:

- **Kolom kiri (`#content`, flex: 3)** — Berisi artikel "Tentang Saya" dan "Proyek Unggulan".
- **Kolom kanan (`aside`, flex: 1)** — Berisi biodata dan foto profil.

Pada layar dengan lebar ≤800px, layout berubah menjadi satu kolom vertikal dan biodata dipindahkan ke atas konten.

---

## Proyek yang Ditampilkan

### MerpatiApp
Aplikasi komunikasi dengan fitur AI terintegrasi dan sistem anti-hoax. Dibangun untuk menciptakan ekosistem komunikasi yang aman dan cerdas bagi masyarakat.

### Ringkas.in
Aplikasi peringkas teks otomatis berbasis model bahasa lokal **mT5**. Dirancang untuk privasi tinggi dan efisiensi pemrosesan data tanpa bergantung pada API eksternal.

---

## Cara Menjalankan

Tidak diperlukan instalasi apapun. Cukup buka file `index.html` langsung di browser:

```bash
# Buka dengan browser default
xdg-open index.html

# Atau gunakan ekstensi Live Server di VS Code / Kiro
```

---

## Tautan

- [Profil Dicoding](https://www.dicoding.com/users/aslich)

---

## Lisensi

&copy; 2026 Iwan Aslich. Submission Tugas Akhir Dicoding.

