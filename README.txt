VOLT — WEBSITE MOBIL 3D

CARA MEMBUKA DI ANTIGRAVITY IDE
1. Ekstrak folder car-3d-website.zip.
2. Buka Antigravity IDE.
3. Pilih Open Folder, lalu pilih folder car-3d-website.
4. Buka index.html.
5. Jalankan dengan Live Server atau server lokal yang mendukung ES modules. Jangan hanya membuka index.html dengan double-click, karena browser dapat memblokir pemuatan file GLB.

STRUKTUR
- index.html: tampilan website dan kode Three.js.
- assets/futuristic-car.glb: model mobil 3D yang kamu unggah.

FITUR
- Model 3D interaktif: drag untuk memutar, scroll untuk zoom.
- Tombol Reset 3D View.
- Desain responsif untuk desktop dan HP.
- Tema futuristik dark navy dengan aksen cyan.

CATATAN
Website memuat Three.js dan font dari CDN menggunakan import map agar modul Three.js dapat ditemukan oleh browser, jadi koneksi internet diperlukan saat menjalankan. Jika model gagal dimuat, lihat tulisan Detail di area model: sekarang website menampilkan alamat file dan status HTTP yang gagal. Pastikan folder assets berada sejajar dengan index.html, bukan berada di dalam folder lain. Jika model terlihat terlalu besar/kecil atau menghadap arah yang kurang pas, sesuaikan skala dan rotasi model di index.html.
