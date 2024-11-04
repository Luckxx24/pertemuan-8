# pertemuan-8
login dengan ionic

1.Pengguna Memasukkan Data:

-Pengguna mengisi username dan password, lalu menekan tombol "Login".

2.Validasi Input:

-Sistem memeriksa apakah data login diisi. Jika kosong, notifikasi peringatan ditampilkan.

3.Mengirim Data ke Backend:

-Jika data lengkap, aplikasi mengirim data ke backend melalui API.

4.Respons dari Backend:

-Jika login berhasil, backend mengirimkan token dan nama pengguna.

-Data ini disimpan di Preferences, dan status isAuthenticated diatur menjadi true.

5.Pengarahan Halaman:

-Jika login berhasil, pengguna diarahkan ke halaman home.

-Jika gagal, notifikasi error ditampilkan.

6.Guard Autentikasi:

-authGuard memastikan pengguna sudah login untuk mengakses halaman home.
-autoLoginGuard mencegah akses halaman login jika pengguna sudah login.
7.Logout:
-Di halaman home, pengguna dapat logout, yang menghapus data login dan mengarahkan kembali ke halaman login.
