# Labirin Koding — Visual Coding

Platform coding visual berbasis HTML, CSS, dan JavaScript murni. Tidak membutuhkan Node.js, database, API key, atau proses build. Bisa langsung dipublikasikan melalui GitHub Pages.

## Fitur
- Antarmuka labirin dan area program yang terinspirasi dari platform belajar coding visual.
- Tambah blok dengan klik atau drag-and-drop.
- Blok maju, belok kiri, belok kanan, pengulangan, dan kondisi jalur.
- Jalankan program dengan animasi atau uji langkah demi langkah.
- Representasi teks program, log eksekusi, reset robot, hapus blok, dan desain responsif.
- Metadata sharing dan favicon SVG.

## Menjalankan lokal
Buka `index.html` langsung di browser. Tidak ada dependency eksternal.

## Deploy ke GitHub Pages
1. Buat repository GitHub baru.
2. Upload `index.html`, `favicon.svg`, dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu deployment selesai, lalu buka URL GitHub Pages yang ditampilkan.

## Catatan
Versi ini adalah prototipe pembelajaran mandiri. Blok kondisi melakukan pemeriksaan saat dieksekusi; blok pengulangan mengulang perintah maju. Untuk pengalaman Blockly penuh dengan blok bertingkat yang dapat diedit di dalam loop/kondisi, perlu ditambahkan model AST dan editor visual bersarang.
