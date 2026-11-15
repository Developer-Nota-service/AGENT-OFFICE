# Agent Office

Prototipe web responsif berbahasa Indonesia untuk menjelajahi kantor virtual tim AI. Versi ini memakai pendekatan **kantor isometrik interaktif**: tiap area kantor digambar sebagai ilustrasi vektor 2.5D langsung di browser, dan karakter agent ditampilkan di ruangan masing-masing. Terinspirasi konsep visualisasi kantor agent dari [Claude-Office](https://github.com/W17ant/Claude-Office), tetapi implementasinya dibuat mandiri.

## Jalankan

Tidak membutuhkan proses build ataupun dependency. Buka `index.html` langsung, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Kemudian buka http://localhost:8000.

## Yang bisa dicoba

- Klik ruangan pada denah isometrik untuk memilih area dan melihat agent di sana.
- Klik agent untuk membuka profil, lalu berikan tugas demo.
- Tambahkan agent baru dan pilih ruangan penugasannya.
- Pantau hitungan agent, status, daftar aktivitas, dan isi ruangan.
- Gunakan pada desktop maupun ponsel; pada layar kecil denah dapat digeser horizontal.

## Ruangan

Ruangan Bos, Divisi Keuangan, Ruang Meeting, Ruang Diskusi Agent, Divisi Konten, Pengembangan Website, Divisi API, Cafe, Pantry & Istirahat, Taman, Kolam Renang, dan Parkiran.

## Catatan

Ilustrasi kantor dan karakter pada prototipe ini digambar dengan SVG, bentuk CSS, serta emoji. Gambar referensi yang dikirim di percakapan tidak tersedia sebagai berkas yang dapat disalin ke repositori pada sesi ini, jadi belum disematkan sebagai aset asli. Perubahan data agent dan tugas hanya berlaku sementara selama halaman terbuka. Status serta aktivitas masih berupa demo—integrasi dengan model AI, backend persisten, atau pembaruan real-time belum termasuk.
