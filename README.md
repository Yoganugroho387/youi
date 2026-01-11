
# Youi Framework

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-2.0.0-green.svg)
![Size](https://img.shields.io/badge/size-12kb-orange.svg)

**Youi** (Yo-UI) adalah framework CSS modern, ringan, dan responsif yang dirancang khusus untuk mempercepat pengembangan antarmuka Web, SaaS, dan Dashboard IoT.

Dikembangkan sebagai bagian dari ekosistem **YoBase**.

## ✨ Fitur Utama

* **⚡ Lightweight:** Tanpa JavaScript berat, hanya CSS murni yang optimal.
* **📱 Fully Responsive:** Sistem Grid 12-kolom yang fleksibel (mirip Bootstrap).
* **🌙 Dark Mode Ready:** Otomatis menyesuaikan tema gelap/terang perangkat pengguna.
* **🎨 CSS Variables:** Mudah dikustomisasi (ganti warna tema dalam hitungan detik).
* **🧩 Component Based:** Menyediakan komponen siap pakai (Navbar, Card, Button, Form).

## 🚀 Cara Penggunaan (Quick Start)

Cara tercepat menggunakan Youi adalah melalui CDN (jsDelivr). Tambahkan kode ini di dalam tag `<head>` website Anda.

### Via CDN (Reccomended)
Ganti `USERNAME_GITHUB` dan `REPO_NAME` dengan detail repository Anda.

```html
<link rel="stylesheet" href="[https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.css](https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.css)">

<link rel="stylesheet" href="[https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.min.css](https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.min.css)">

Starter Template
Salin kode HTML di bawah ini untuk memulai proyek baru:
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youi Starter</title>
    <link rel="stylesheet" href="[https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.css](https://cdn.jsdelivr.net/gh/USERNAME_GITHUB/REPO_NAME/youi.css)">
</head>
<body>
    <div class="container mt-5">
        <h1>Halo, Youi!</h1>
        <p class="text-muted">Website ini menggunakan Youi Framework.</p>
        <button class="btn btn-primary">Mulai Sekarang</button>
    </div>
</body>
</html>

📚 Dokumentasi Singkat
1. Grid System
Youi menggunakan sistem 12 kolom yang responsif.
<div class="row">
  <div class="col-12 col-md-6">...</div> <div class="col-12 col-md-6">...</div>
</div>

2. Buttons
Gunakan class .btn diikuti dengan varian warna.
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-danger">Danger</button>
<button class="btn btn-block">Full Width Button</button>

3. Cards
Komponen kartu dengan header, body, dan footer.
<div class="card">
  <div class="card-header">Judul Kartu</div>
  <div class="card-body">
    <p>Isi konten kartu di sini...</p>
  </div>
</div>

4. Forms
Input form modern dengan efek focus ring.
<div class="mb-3">
  <label class="form-label">Email Address</label>
  <input type="email" class="form-control" placeholder="name@example.com">
</div>

🎨 Kustomisasi Tema
Youi dibangun di atas CSS Variables. Anda dapat mengubah tema warna secara global hanya dengan menimpa variabel di CSS Anda sendiri:
:root {
    --primary: #ff0000; /* Mengubah warna utama menjadi Merah */
    --radius-md: 0px;   /* Mengubah tombol menjadi kotak tajam */
}

🤝 Kontribusi
Pull requests dipersilakan. Untuk perubahan besar, harap buka issue terlebih dahulu untuk mendiskusikan apa yang ingin Anda ubah.
📝 Lisensi
MIT
Built with ❤️ by Yoga Nugroho (YoBase)
