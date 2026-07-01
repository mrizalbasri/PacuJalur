# Pacu Jalur — Preserving Heritage Through Design (Culture Verse)

> Sebuah landing page edukatif-promosional premium yang mengangkat **Pacu Jalur**, tradisi dayung perahu panjang bersejarah dari Kuantan Singingi, Riau — ditetapkan sebagai Warisan Budaya Takbenda (WBTb) Nasional Indonesia sejak 2014.

Dibuat khusus untuk **SDGs Creative Web Competition — BytesFest 2026**
* **Sub Tema:** *Culture Verse — Preserving Heritage Through Design* (SDG 11 - Kota dan Pemukiman yang Berkelanjutan)
* **Kategori:** Web Statis (Front-End Only)

---

## 🎨 Konsep Visual & Desain Premium

Desain landing page ini dirancang dengan gaya **Editorial Premium** menggunakan sentuhan budaya khas Melayu Riau:
- **Palet Warna Budaya:** Warna dasar krem hangat (`#F4F3EE`), emerald hijau tua khas Melayu (`#0C3E3B`), aksen merah berani (`#C83E4D`), dan emas kejayaan (`#E5A93B`).
- **Watermark Tenun Songket Riau:** Pola geometris Songket Melayu tradisional yang diintegrasikan secara elegan menggunakan data-URI SVG ringan sebagai latar belakang.
- **Ornamen Pucuk Rebung:** Ilustrasi ornamen tradisional Melayu *Pucuk Rebung* (simbol pertumbuhan dan kekuatan gotong royong) disematkan pada kartu-kartu informasi.
- **Glassmorphism Modern:** Penerapan efek frosted-glass (`backdrop-filter: blur`) pada komponen kartu interaktif untuk menghadirkan kesan mewah dan kontemporer bagi juri.

---

## 🚀 Kepatuhan Regulasi & Kinerja Tinggi

Sesuai dengan **Ketentuan Karya Poin 5** kompetisi BytesFest 2026:
- **Bebas Penyimpanan Klien (LocalStorage/SessionStorage/Database):** Seluruh fungsionalitas web berjalan 100% statis. Fitur toggle bahasa dikontrol menggunakan *in-memory state* Javascript biasa (tanpa menyentuh `localStorage` atau `sessionStorage` untuk menghindari diskualifikasi).
- **Performa Ringkas & Modern (Tailwind CSS v4):** Terintegrasi penuh menggunakan **Tailwind CSS v4** melalui Vite plugin resmi Astro. Gaya visual dikompilasi secara ultra-cepat, menggabungkan kepraktisan *utility classes* dengan ornamen budaya tradisional yang tersemat rapi.

---

## ✨ Fitur Utama

- [x] **Akurasi Budaya:** Bebas dari kesalahan istilah populer (menggunakan "perahu panjang tradisional", bukan "perahu naga" yang merupakan tradisi lain).
- [x] **Bilingual Toggle (ID/EN):** Perpindahan bahasa instan menggunakan tombol geser *pill slider* yang interaktif.
- [x] **Jam Live WIB:** Penunjuk waktu lokal Tepian Narosa, Kuantan Singingi yang berjalan secara real-time.
- [x] **Linimasa Sejarah 400 Tahun:** Slider horizontal visual dengan kontrol navigasi kustom dan efek gradasi tepi (*gradient mask fade*) yang melacak sejarah jalur dari Abad ke-17 hingga era viralitas global.
- [x] **Interactive Anatomy Explorer:** Membedah 4 peran penting kru di atas perahu (Tukang Concang, Tukang Onjai, Tukang Tari, dan Tukang Pinggang) menggunakan panel tab interaktif.
- [x] **Elders Philosophy Testimonials:** Kumpulan kutipan mendalam dari pemuka adat setempat tentang filosofi gotong-royong.
- [x] **SDG Impact Grid:** Pemetaan visual manfaat festival terhadap target SDG 15 (Konservasi), SDG 11 (Warisan Budaya), SDG 8 (Ekonomi Lokal), dan SDG 16 (Kohesi Sosial).

---

## 📁 Struktur Berkas Modular

Proyek ini telah direfaktorisasi dari berkas tunggal menjadi struktur komponen Astro yang bersih dan modular:

```
.
├── src/
│   ├── components/
│   │   ├── Hero.astro         # Navbar, jam WIB, bilingual toggle, & visual Hero
│   │   ├── History.astro      # Grid sejarah & linimasa sejarah 400 tahun
│   │   ├── Anatomy.astro      # Panel tab peran kru perahu Jalur
│   │   ├── Philosophy.astro   # Testimoni & kutipan adat gotong-royong
│   │   ├── Benefits.astro     # Grid dampak festival terhadap SDGs
│   │   └── Footer.astro       # CTA newsletter form & footer pacu jalur
│   ├── layouts/
│   │   └── Layout.astro       # Template HTML dasar & CSS Variables global
│   └── pages/
│       └── index.astro        # Berkas halaman utama (hanya mengimpor komponen)
├── public/
│   └── images/                # Aset gambar orisinal Pacu Jalur hasil generate AI
├── astro.config.mjs           # Konfigurasi Astro
├── README.md
└── DESIGN.md                  # Dokumen konsep visual & filosofi detail
```

---

## 💻 Cara Menjalankan Proyek Secara Lokal

1. **Unduh Dependensi:**
   ```bash
   npm install
   ```

2. **Jalankan Server Development:**
   ```bash
   npm run dev
   ```
   Buka `http://localhost:4321` di browser Anda.

3. **Build Kompilasi Produksi:**
   ```bash
   npm run build
   ```
   Kompilasi statis akan dihasilkan di folder `/dist` dalam waktu kurang dari 1 detik.

---

## 👤 Author

**Muhammad Rizal Basri**
*Informatics — President University (Pekanbaru Campus)*

*Dibuat dengan cinta untuk pelestarian budaya Kuantan Singingi, Riau.*