1. Struktur Proyek
Direktori proyek disusun menjadi beberapa folder untuk mengelompokkan kode berdasarkan fungsinya:
model untuk kelas yang mewakili data akun (Account).
transaction untuk kelas-kelas yang menangani transaksi seperti penarikan (Withdrawal), deposit (Deposit), dan transfer (Transfer).
ATM sebagai kelas utama yang mengelola antarmuka pengguna dan opsi transaksi.
2. Fitur yang Diimplementasikan
Penarikan - Mengurangi saldo akun jika saldo mencukupi.
Deposit - Menambah saldo ke akun.
Transfer - Memindahkan saldo antar akun yang berbeda.
Cek Saldo - Menampilkan saldo akun saat ini.
Ubah PIN - Mengganti PIN akun dengan melakukan verifikasi PIN lama dan konfirmasi PIN baru.
Validasi Saldo Minimal - Memastikan saldo akun tetap di atas batas minimum setelah penarikan (Rp50,000).
3. Menambahkan Fitur "Ubah PIN"
Opsi ini memungkinkan pengguna untuk mengubah PIN setelah memverifikasi PIN lama.
PIN baru harus dimasukkan dua kali untuk memastikan tidak ada kesalahan dalam input.
4. Validasi Saldo Minimal untuk Penarikan
Fitur ini menambahkan batas saldo minimum untuk mencegah pengguna menarik seluruh saldo yang tersisa.
Jika saldo setelah penarikan kurang dari batas minimum (Rp50,000), transaksi akan dibatalkan.
