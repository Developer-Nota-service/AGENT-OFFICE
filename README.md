# Agent Office

Dashboard web responsif berbahasa Indonesia untuk memvisualisasikan tim AI di kantor virtual. Terinspirasi oleh konsep kantor agent real-time dari [Claude-Office](https://github.com/W17ant/Claude-Office), dengan tata ruang yang mengikuti referensi kantor pada permintaan: ruang bos, keuangan, meeting, diskusi, konten, pengembangan website, API, cafe, pantry, taman, kolam renang, dan parkiran.

## Jalankan

Aplikasi ini berupa situs statis tanpa proses build atau dependency. Buka `index.html` langsung di browser, atau jalankan server lokal sederhana:

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000.

## Fitur demo

- Denah kantor interaktif: pilih ruangan untuk melihat agent yang ada di sana.
- Ringkasan jumlah agent, agent yang bekerja, tugas selesai, dan ruangan aktif.
- Daftar dan profil agent, pencarian, serta filter agent aktif.
- Tambah agent dan berikan tugas melalui dialog demo. Perubahan hanya tersimpan sementara di browser dan akan kembali ke data awal saat halaman dimuat ulang.
- Tampilan responsif untuk desktop dan ponsel.

## Tentang gambar referensi

Gambar yang dikirim di percakapan tidak tersedia sebagai berkas yang dapat disalin oleh alat GitHub pada sesi ini, jadi keduanya belum disematkan sebagai aset repo. Denah interaktif dan avatar pada versi awal ini dibuat langsung dengan HTML/CSS/emoji, mengikuti susunan ruangan dan karakter dari referensi. Jika ingin menggunakan gambar asli, tambahkan file gambar ke repo lalu kita dapat memasangnya sebagai ilustrasi denah dan avatar.

## Batasan

Ini adalah prototipe frontend statis. Status agent dan aktivitas masih berupa data contoh; integrasi AI sungguhan, penyimpanan persisten, autentikasi, dan pembaruan real-time memerlukan backend/API.
