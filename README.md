
---


# 🎂 Keya's 20th Birthday Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

> *"Happy Birthday, Love. Hello, Chapter 20."*

Proyek ini adalah sebuah **Website Ucapan Ulang Tahun Interaktif** yang dibuat khusus untuk merayakan ulang tahun ke-20 Keya. Website ini dirancang sebagai "kado digital" abadi yang berisi surat, galeri foto, dan harapan-harapan, dikemas dengan animasi yang halus dan desain yang elegan.

---

## ✨ Fitur Utama

Website ini bukan sekadar halaman statis, melainkan memiliki beberapa fitur interaktif:

### 🔒 1. "The Archive" Login Gate
Pengunjung tidak bisa langsung melihat konten utama. Terdapat halaman pembuka (*overlay*) yang meminta "kunci" berupa tanggal spesial.
* **Fitur**: Validasi password sederhana.
* **Efek**: Jika password benar, layar akan terbuka dengan efek ledakan **Confetti** 🎉.

### 🎵 2. Background Music Player
* Dilengkapi dengan pemutar musik otomatis (Autoplay setelah interaksi user).
* Tombol kontrol (Play/Pause) yang melayang (*floating button*) di pojok kanan bawah dengan animasi piringan hitam (*spin*).

### 🎬 3. Animasi & Interaktivitas
* **Typewriter Effect**: Teks pembuka diketik secara otomatis huruf demi huruf untuk kesan sinematik.
* **Scroll Animations (AOS)**: Elemen (foto/teks) akan muncul (*fade in/zoom*) secara elegan saat pengguna menggulir ke bawah.
* **Responsive Design**: Tampilan menyesuaikan secara otomatis baik di Laptop maupun Smartphone.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan teknologi web standar tanpa *framework* berat, sehingga sangat ringan dan cepat.

* **Core**: HTML5, CSS3 (Custom Variables & Flexbox/Grid), JavaScript (Vanilla).
* **Libraries (via CDN)**:
    * `AOS` (Animate On Scroll) - Untuk animasi masuk elemen.
    * `TypeIt` - Untuk efek mengetik teks.
    * `Canvas Confetti` - Untuk efek ledakan kertas warna-warni.
    * `Font Awesome` - Untuk ikon (Crown, Music, Pin).
* **Fonts**: Menggunakan *Google Fonts* ('Cormorant Garamond' untuk kesan mewah & 'Montserrat' untuk keterbacaan modern).

---

## 📂 Struktur Proyek

```bash
keya-turn-20/
├── assets/             # Folder penyimpanan media
│   ├── image-1.jpg     # Foto kenangan
│   ├── image-5.png     # Foto utama (Hero)
│   └── musik.mp3       # Lagu latar belakang
├── index.html          # File struktur utama halaman
├── style.css           # Styling, layout, dan animasi CSS
└── script.js           # Logika password, musik, dan inisialisasi plugin

```

---

## 🚀 Cara Menjalankan

Karena ini adalah website statis (*static site*), Anda bisa menjalankannya dengan sangat mudah:

1. **Download/Clone** repositori ini.
2. Buka folder proyek.
3. Klik dua kali file `index.html` (akan terbuka di browser default Anda).

### ⚙️ Konfigurasi (Opsional)

Jika Anda ingin menggunakan kode ini untuk orang lain, Anda perlu mengubah beberapa bagian di `script.js`:

**Mengganti Password:**
Buka `script.js` dan cari baris berikut:

```javascript
// --- KONFIGURASI ---
const correctPass = "240924"; // Ganti dengan tanggal/password pilihanmu

```

**Mengganti Lagu:**
Ganti file `musik.mp3` di folder `assets` dengan lagu pilihan Anda (pastikan namanya tetap sama atau ubah `src` di `index.html`).

---

## 📱 Pratinjau Tampilan

| Halaman Login | Halaman Utama | Surat Digital |
| --- | --- | --- |
| *Input password dengan validasi* | *Hero section dengan animasi* | *Desain kertas surat miring* |

---

## 💝 Credits

Dibuat dengan sepenuh hati oleh **Farhan** untuk **Keya**.

> *"Bunga bisa layu, cokelat bisa habis, tapi tulisan di sini akan tetap ada selama internet masih menyala."*

---

<div align="center">
<small>Copyright © 2024 - All Rights Reserved</small>
</div>

```

```
