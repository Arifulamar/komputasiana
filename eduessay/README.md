# EduEssay MVP 0.1

Prototipe frontend statis untuk platform ujian esai SMA/SMK/SLB.

## Isi versi ini
- Dashboard ringkasan.
- Pembuatan ujian dan soal esai demo.
- Ruang siswa untuk mengirim jawaban demo.
- Penilaian manual dan umpan balik.
- Rekap hasil serta ekspor CSV.
- Data demo disimpan di `localStorage` browser.

## Publikasi GitHub Pages
Folder ini berada di `eduessay/` dalam repository Komputasiana. Jika GitHub Pages repository menerbitkan root branch `main`, halaman akan tersedia di:

https://arifulamar.github.io/komputasiana/eduessay/

Jika Pages memakai GitHub Actions yang hanya menerbitkan folder build tertentu, folder ini tidak otomatis ikut terbit. Periksa Settings → Pages dan workflow repository.

## Batasan keamanan
Ini hanya prototipe frontend. Peran yang dipilih pada UI tidak mengamankan data. Jangan masukkan data pribadi siswa atau gunakan untuk ujian resmi. Belum ada autentikasi server, backend API, database cloud, token ujian, timer server, AI, atau audit log yang terlindungi.

## Langkah berikutnya
1. Buat backend Rust + Actix Web.
2. Tambahkan PostgreSQL dan isolasi data antar-sekolah.
3. Implementasikan login dan RBAC di server.
4. Simpan jawaban ke server dengan versi/autosave dan idempotensi.
5. Tambahkan penilaian AI berbasis rubrik dengan persetujuan guru.
6. Uji keamanan, aksesibilitas, backup/restore, dan beban ujian bersamaan.
