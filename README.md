# Pertemuan 4 — Connect the Network (TKA TJKT)

Modul pembelajaran interaktif **Teknik Komputer dan Jaringan (TKJ/TJKT)** untuk Pertemuan 4 dengan tema **Connect the Network** (Media Transmisi, Perangkat Jaringan, OSI/TCP-IP, dan Topologi), dilengkapi **Quiz Engine TKA** berbasis bank soal acak.

🔗 **Live Demo (GitHub Pages):** https://hendrazulpiadi.github.io/pertemuan-4-materi-TKA/

---

## ✨ Fitur

### 1. Presentasi Materi Interaktif (7 Slide)
- **Slide 1 — Cover:** tujuan pembelajaran.
- **Slide 2 — Konsep Dasar:** Node, Link, Protokol, serta skala jaringan LAN/MAN/WAN.
- **Slide 3 — Media Transmisi:** UTP/STP, Koaksial, Fiber Optik, dan Nirkabel (klik untuk detail).
- **Slide 4 — Perangkat Jaringan:** Hub, Switch, Router, Access Point, Modem/ONT, Firewall (flip card).
- **Slide 5 — OSI & TCP/IP:** layer interaktif + **simulasi enkapsulasi** Data → Segment → Packet → Frame → Bit.
- **Slide 6 — Topologi:** Star, Mesh, Bus, Ring (diagram SVG interaktif).
- **Slide 7 — Rangkuman:** status kesiapan menuju quiz.

Navigasi: tombol bawah, titik indikator, atau tombol panah keyboard ◀ ▶.

### 2. Quiz Engine
- **Bank soal 20 butir**: Pilihan Ganda (PG), PGK Kategori (Benar/Salah), dan PGK MCMA (jawaban lebih dari satu).
- Setiap sesi menampilkan **5 soal** (2 PG + 2 Kategori + 1 MCMA) dengan **komposisi dan soal berbeda per siswa** (diacak berbasis nama).
- Skor total **100**; kategori & MCMA memakai penilaian parsial.
- Halaman hasil menampilkan skor, nama peserta, dan ID paket soal.

### 3. Anti-Cheat
- Mendeteksi perpindahan tab/jendela melalui `visibilitychange`.
- Penalti berlipat: 5 menit, 10 menit, 20 menit, dst., bertahan meski halaman di-refresh (kecuali mode privat).

### 4. Gate Pembelajaran
Tombol **Mulai Quiz** baru aktif setelah siswa menyelesaikan 3 interaksi: Media Transmisi, Simulasi OSI, dan Topologi.

---

## 🚀 Cara Menjalankan

Cukup buka file `index.html` di browser (tanpa server, tanpa build).

Untuk mode nama tetap (mis. agar set soal stabil per siswa):
```
index.html?nama=NamaSiswa
```

---

## 🛠️ Teknologi
- HTML5, CSS3, dan JavaScript murni (vanilla) — tanpa dependensi eksternal.
- Satu file `index.html` (self-contained).

---

## 📁 Struktur
```
.
├── index.html    # seluruh aplikasi (materi + quiz)
├── .nojekyll     # menonaktifkan pemrosesan Jekyll di GitHub Pages
└── README.md
```

---

## 🌐 Deploy ke GitHub Pages
1. Push ke branch `main`.
2. Buka **Settings → Pages**.
3. **Source:** Deploy from a branch → **Branch:** `main` → **/ (root)** → Save.
4. Situs tayang di `https://<username>.github.io/<nama-repo>/`.

---

## 👤 Penyusun
**Hendra Zulpiadi** — SMK Al Azhar Batam · Program Keahlian TKJ
