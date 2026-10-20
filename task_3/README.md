# Tugas Individu 3 - Pemrograman Web

Nama: Richard Halim
NIM: 124140084
Kelas: RA

## Cara menjalankan
Buka index.html dengan browser. Isi formulir menggunakan data contoh, lalu klik Lihat detail pendaftar. Browser berpindah ke detail.html dengan query string. Halaman detail sengaja statis dan tidak mengambil parameter URL. Tidak ada JavaScript, backend, atau database.

## Struktur
- index.html: formulir pendaftaran dengan method="get" dan action="detail.html".
- detail.html: tabel informasi pendaftar dummy.
- style.css: desain layout, box, tabel, form, serta tampilan responsif.
- RA-Richard Halim-124140084-Tugas3-Pemweb.pdf: laporan tugas.

## Contoh query string
detail.html?nama=Nadia+Putri&nim=123456789&kelas=RC&email=nadia%40example.com&prodi=informatika&jenis_kelamin=perempuan&alasan=Belajar+HTML+dan+CSS&persetujuan=ya

Query dibentuk otomatis oleh form GET melalui atribut name. Spasi dapat dikodekan menjadi + dan @ menjadi %40. Halaman detail tidak memakai URLSearchParams atau kode pembaca query lainnya.

## Selector CSS
Selector elemen: body, table, input. Selector class: .card, .layout, .fields. Selector ID: #detail-title. Selector atribut: input[type=radio]. Pseudo-class: button:hover dan input:focus.

## Pemeriksaan manual
1. Buka kedua halaman dan coba tautan kembali.
2. Kirim formulir kosong: browser meminta kolom wajib.
3. Coba email tidak valid dan NIM selain angka: browser menolak.
4. Isi data valid: URL detail berisi query string.
5. Ubah parameter nama di URL: tabel tetap menampilkan Nadia Putri (dummy).
6. Persempit jendela: layout berubah menjadi satu kolom.

## Pengumpulan
Unggah folder task_3 beserta isinya ke repository GitHub masing-masing. Laporan telah diberi nama sesuai format kelas-Nama-Nim-Tugas3-Pemweb.pdf. Paket ini belum diunggah ke GitHub.
