# Agent Office

Prototipe kantor virtual pixel-art berbahasa Indonesia. Arah visual kini mengikuti **format visualisasi kantor game/pixel-art** yang menjadi ciri Claude-Office, bukan ilustrasi bangunan 3D berbentuk kartu atau denah SVG isometrik.

## Jalankan

Tidak perlu proses build atau dependency. Buka `index.html` langsung, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Buka http://localhost:8000.

## Yang tersedia

- Canvas pixel-art dengan ruangan kantor dan furnitur yang digambar secara original di browser.
- Pilih kantor utama, ruangan bos, keuangan, meeting, diskusi, konten, pengembangan website, API, cafe, pantry, taman, kolam renang, atau parkiran.
- Karakter pixel-art punya tampilan berbeda, gerak idle/mengetik sederhana, dan dapat diklik untuk membuka detail serta memberi tugas demo.
- Mode siang/malam, zoom, status ringkas, panel obrolan demo, dan aktivitas.
- Layout responsif untuk desktop dan layar ponsel.

## Catatan lisensi dan aset

Karya ini menggunakan ilustrasi pixel-art yang digambar sendiri dengan canvas; sprite dan aset visual dari Claude-Office tidak disalin. Kodenya juga tidak menyalin implementasi aplikasi tersebut. Gambar kantor dan karakter yang dilampirkan dalam percakapan belum tersedia di repo sebagai file aset sehingga belum bisa dipasang. Untuk menggunakan karakter persis dari gambar Anda, tambahkan gambar sebagai aset repo.

## Batasan prototipe

Status agent, percakapan, gerakan, dan aktivitas masih simulasi frontend. Belum ada koneksi ke Claude Code, model AI, backend, WebSocket, persistensi data, atau autentikasi. Tombol suara hanya memberi umpan balik demo, belum memutar audio.
