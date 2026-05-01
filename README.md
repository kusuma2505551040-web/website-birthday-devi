# 🎂 Birthday Web — Panduan Penggunaan

## Struktur Folder
```
birthday/
├── index.html       ← file utama, buka ini di browser
├── assets/          ← taruh foto-foto kamu di sini
│   ├── foto1.jpg
│   ├── foto2.jpg
│   └── ...
└── README.md
```

---

## Cara Menggunakan

### 1. Tambahkan Foto
Taruh semua foto ke dalam folder **`assets/`**.
Format yang didukung: `.jpg`, `.jpeg`, `.png`, `.webp`, `.gif`

### 2. Edit `index.html`
Buka `index.html` dengan teks editor (Notepad, VS Code, dll).
Cari bagian **CONFIG** (baris ~180):

```js
// Ganti nama pacarmu:
const PARTNER_NAME = "Sayangku";

// Daftar nama file foto di folder assets/:
const PHOTOS = [
  "foto1.jpg",
  "foto2.jpg",
  "foto3.jpg",
];

// Caption untuk tiap foto (urutan sama):
const CAPTIONS = [
  "Ini momen favoritku bareng kamu 💕",
  "Nggak akan pernah aku lupa ✨",
  "Kamu selalu bikin aku senyum 🌹",
];

// Tanggal/keterangan (opsional, boleh dikosongkan ""):
const DATES = [
  "2023",
  "Liburan bareng",
  "",
];
```

### 3. Buka di Browser
Klik dua kali `index.html` — langsung jalan di browser!

> **Catatan:** Kalau foto tidak muncul, pastikan kamu membuka file dari folder yang sama (jangan pindahkan `index.html` terpisah dari folder `assets/`).

---

## Cara Kerja Web

1. **Layar intro** — ada tulisan romantis & tombol hati yang berdetak
2. **Tekan tombol hati** → muncul fireworks + confetti + tulisan **Happy Birthday**
3. **Tekan "Buka Scrapbook"** → scrapbook terbuka dengan cover
4. **Navigasi foto** dengan tombol Prev/Next (atau tombol ← → di keyboard)
5. **Tekan ✕** atau **Esc** untuk menutup scrapbook

---

Selamat, semoga pacarmu suka! 🌹
