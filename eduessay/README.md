# EduEssay MVP 0.2

Prototipe sederhana bergaya Google Forms untuk ujian esai SMA/SMK/SLB.

## Fitur prototipe
- Form builder: judul, petunjuk, mata pelajaran, durasi, pertanyaan esai, rubrik, dan nilai maksimum.
- Pratinjau formulir siswa.
- Pengiriman jawaban demo.
- Daftar jawaban untuk ditinjau guru.
- Kolom nilai akhir dan umpan balik guru.
- Ekspor jawaban dan nilai ke CSV.
- Penyimpanan demo di localStorage browser.

## Buka melalui GitHub Pages
Jika repository menerbitkan root branch `main`, coba:
https://arifulamar.github.io/komputasiana/eduessay/

File sumber:
https://github.com/Arifulamar/komputasiana/blob/main/eduessay/index.html

## Penting tentang AI dan keamanan
Tombol "Simulasikan pemeriksaan AI" hanya mendemonstrasikan alur UI. Skor simulasi berdasarkan panjang jawaban, bukan analisis AI dan tidak boleh digunakan untuk penilaian akademik. AI sesungguhnya belum terhubung.

Data hanya tersimpan pada browser yang digunakan dan tidak tersinkron ke guru atau perangkat lain. Jangan memasukkan data pribadi siswa atau menggunakan versi ini untuk ujian resmi. Pemilihan menu/peran bukan pengamanan akses.

## Langkah menuju produksi
1. Backend Rust + Actix Web dan PostgreSQL.
2. Autentikasi, peran, dan isolasi data per sekolah.
3. Penyimpanan jawaban server-side dengan autosave, versi, dan pemulihan koneksi.
4. Integrasi AI di backend; simpan API key sebagai secret, jangan pernah di frontend.
5. Penilaian AI menggunakan rubrik, penjelasan skor, versi model, dan persetujuan guru.
6. Uji keamanan, aksesibilitas, beban, backup/restore, serta kepatuhan perlindungan data.
