1. Struktur Proyek
Direktori proyek disusun menjadi beberapa folder untuk mengelompokkan kode berdasarkan fungsinya:
model untuk kelas yang mewakili data akun pengguna/ pemilik (Account).
transaction untuk kelas-kelas yang menangani transaksi seperti penarikan uang (Withdrawal), deposit uang (Deposit), dan transfer uang (Transfer).
2. Fitur yang Diimplementasikan
Penarikan - Mengurangi saldo akun jika saldo mencukupi. jika saldo dibawah minimal maka tidak bisa melakukan penarikan
Deposit - Menambah saldo ke akun.
Transfer - Memindahkan saldo antar akun yang berbeda. ( akun yang sudah terdaftar )
Cek Saldo - Menampilkan saldo akun saat ini.
Ubah PIN - Mengganti PIN akun dengan melakukan verifikasi PIN lama dan konfirmasi PIN baru, jika pin yang dimasukan salah maka gagal
Validasi Saldo Minimal - Memastikan saldo akun tetap di atas batas minimum setelah penarikan (Rp50,000).
3. Menambahkan Fitur "Ubah PIN"
Opsi ini memungkinkan pengguna untuk mengubah PIN setelah memverifikasi PIN lama.
PIN baru harus dimasukkan dua kali untuk memastikan tidak ada kesalahan dalam input.
4. Validasi Saldo Minimal untuk Penarikan
Fitur ini menambahkan batas saldo minimum untuk mencegah pengguna menarik seluruh saldo yang tersisa.
Jika saldo setelah penarikan kurang dari batas minimum (Rp50,000), transaksi akan dibatalkan.

![image](https://github.com/user-attachments/assets/15ac00ed-c329-404d-80e8-181b7dd4cbc8)

![image](https://github.com/user-attachments/assets/469e2279-27c6-46db-8850-681ab7017077)

![image](https://github.com/user-attachments/assets/965a9532-7f68-4435-b3ff-6c6c44de3827)

![image](https://github.com/user-attachments/assets/88c1acc9-a522-4371-81ff-0ce34f3960ed)



