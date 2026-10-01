# Panel Admin yang Ringkas dan Mudah Dicari

## Hasil yang akan dibuat
- Merapikan tampilan panel admin agar setiap bagian memiliki susunan, jarak, dan tombol yang konsisten di ponsel maupun desktop.
- Mengubah daftar setoran menjadi **satu kotak per pengguna**, bukan satu kotak per Gmail.
- Menampilkan ringkasan pada setiap kotak: nama pengguna, jumlah Gmail, jumlah per status, total nilai, dan waktu setoran terbaru.
- Menambahkan tombol **Lihat Email** untuk membuka atau menutup seluruh Gmail milik pengguna tersebut.
- Menambahkan kolom pencarian dengan dua mode: cari berdasarkan email setoran atau cari berdasarkan username/email akun.
- Mempertahankan tindakan massal: admin dapat memilih semua Gmail dalam satu kotak atau memilih Gmail tertentu setelah daftar dibuka, lalu ACC/tolak.
- Merapikan bagian pengguna, penarikan, pengaturan, tiket, dan log tanpa mengubah aturan bisnisnya.
- Memasang pengumuman otomatis yang sudah dibuat agar muncul saat pengguna membuka aplikasi.

## Detail teknis
- Pengelompokan dilakukan dari data setoran yang sudah tersedia berdasarkan ID pengguna, sehingga tidak memerlukan perubahan tabel.
- Pencarian email mencocokkan isi `account_ref`; pencarian akun mencocokkan username dan email profil.
- Data admin akan menyertakan email profil agar pencarian akun bekerja akurat.
- Kontrol tab dan tombol menggunakan komponen tombol aplikasi yang sudah ada.
- Metadata sosial halaman admin akan dilengkapi dengan tipe halaman dan kartu ringkasan.

## Pemeriksaan
- Pastikan akun dengan 50+ setoran tetap tampil sebagai satu kotak ringkas.
- Uji buka/tutup daftar Gmail, pencarian dua mode, pemilihan per pengguna, ACC, dan tolak.
- Uji tampilan panel admin pada ukuran ponsel dan desktop.
- Pastikan aplikasi berhasil dimuat tanpa kesalahan.
