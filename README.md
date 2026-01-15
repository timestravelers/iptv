# IQ-TV — Lightweight Single-File IPTV Player

![Preview]([https://via.placeholder.com/800x400?text=IQ-TV+Preview](https://iptv-eight-orpin.vercel.app/)) <!-- Ganti dengan screenshot asli jika ada -->

**IQ-TV** adalah pemutar IPTV ringan, modern, dan responsif yang dibangun dalam **satu file HTML**. Aplikasi ini mendukung format playlist M3U/M3U8, kompatibel dengan Smart TV, dan siap di-deploy langsung ke platform seperti **Vercel**, **Netlify**, atau GitHub Pages.

---

## ✨ Fitur Utama

- 📺 **Pemutaran IPTV universal**: Mendukung HLS (`.m3u8`) dan stream lainnya via [hls.js](https://github.com/video-dev/hls.js).
- 📁 **Input fleksibel**: Muat playlist dari **file lokal** atau **URL eksternal**.
- 🔍 **Pencarian & Kategori**: Filter channel berdasarkan nama atau kategori (news, sports, movies, dll).
- 🎨 **UI Modern & Smart TV Friendly**: Desain minimalis, fullscreen-ready, dan optimal untuk remote control.

---

## 🚀 Cara Menggunakan

### 1. Jalankan Langsung
Buka file `index.html` di browser modern (Chrome, Firefox, Edge, Safari).

### 2. Deploy ke Vercel / Netlify
1. Fork atau clone repositori ini.
2. Upload file `index.html`.
3. Deploy sebagai proyek statis — **tidak perlu backend!**

> 💡 Untuk penggunaan publik, pastikan URL M3U yang dimuat **tidak diblokir oleh CORS**. Gunakan proxy CORS jika diperlukan.

---

## 🛠 Teknologi yang Digunakan

- **HTML5 + CSS3 + JavaScript (Vanilla)**
- **hls.js** – untuk dukungan HLS di browser non-Safari
- **Responsive Design** – kompatibel desktop, tablet, dan Smart TV

---

## 📂 Struktur File
iptv/
├── index.html        # Aplikasi utama (semua dalam 1 file)
└── README.md

> Tidak ada dependensi build, framework, atau server — **100% client-side**.

---

## 🤝 Kontribusi & Kustomisasi

Aplikasi ini dirancang agar mudah dimodifikasi:
- Tambahkan fitur login/password di bagian awal.
- Integrasi thumbnail channel via JSON tambahan.
- Tambahkan resolusi/audio selector di menu pengaturan.
- Kembangkan sistem donasi otomatis.

Pull request dan saran fitur sangat dipersilakan!

---

## ❤️ Dukung Pengembangan

Jika Anda merasa aplikasi ini bermanfaat, pertimbangkan untuk memberikan **donasi** melalui menu **[About]** di aplikasi. Setiap dukungan membantu pengembangan fitur baru dan pemeliharaan jangka panjang.

---

## 📜 Lisensi

MIT License — bebas digunakan, dimodifikasi, dan didistribusikan, bahkan untuk komersial.

---

Dibuat dengan ❤️ oleh **M Thorik**  


> **Catatan**: Pastikan Anda memiliki hak legal atas playlist M3U yang digunakan. Pengembang tidak bertanggung jawab atas pelanggaran hak cipta konten streaming.
