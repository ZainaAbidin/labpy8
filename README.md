# DIAGRAM CLASS

![Cuplikan layar 2024-12-08 145653](https://github.com/user-attachments/assets/6655e94e-3c85-4c7e-89b3-85468f31a6e3)

Penjelasan! Atribut: mahasiswa: Dictionary untuk menyimpan data mahasiswa (nama sebagai key, nilai sebagai value). Metode:

1. init(): Menginisialisasi atribut mahasiswa sebagai dictionary kosong.
2. tambah(nama, nilai): Menambahkan data mahasiswa.
3. tampilkan(): Menampilkan semua data mahasiswa.
4.  hapus(nama): Menghapus data berdasarkan nama.
5. ubah(nama, nilai_baru): Memperbarui nilai mahasiswa.


# FLAWCHART

![Cuplikan layar 2024-12-08 151445](https://github.com/user-attachments/assets/e66b87b5-3089-4d04-82b9-82cef9dc70be)



# PENJELASAN CODE

1. Definisi Kelas Mahasiswa
Kelas Mahasiswa berfungsi untuk menyimpan dan mengelola daftar mahasiswa. Kelas ini memiliki satu atribut dan beberapa metode:

Atribut:
daftar_mahasiswa: Sebuah list kosong yang berfungsi untuk menyimpan data mahasiswa. Setiap mahasiswa disimpan dalam bentuk dictionary dengan dua kunci: 'nama' untuk menyimpan nama mahasiswa dan 'nilai' untuk menyimpan nilai mahasiswa.

Metode:
__init__(): Ini adalah konstruktor kelas yang otomatis dipanggil saat objek kelas Mahasiswa dibuat. 
Pada konstruktor ini, atribut daftar_mahasiswa diinisialisasi sebagai list kosong.

tambah(nama, nilai): Metode ini digunakan untuk menambahkan data mahasiswa ke dalam list daftar_mahasiswa. Data mahasiswa 
yang ditambahkan disimpan dalam bentuk dictionary dengan key 'nama' dan 'nilai'. setelah data berhasil ditambahkan, program akan mencetak pesan konfirmasi.

tampilkan(): Metode ini digunakan untuk menampilkan seluruh data mahasiswa yang ada dalam daftar_mahasiswa. Jika 
tidak ada data mahasiswa (list kosong), program akan memberikan pesan bahwa daftar mahasiswa kosong. Jika ada data, program akan mencetak setiap mahasiswa beserta nilainya satu per satu.

hapus(nama): Metode ini digunakan untuk menghapus data mahasiswa berdasarkan nama. Program akan mencari mahasiswa dengan nama yang diberikan dalam list daftar_mahasiswa. Jika ditemukan, data mahasiswa tersebut akan dihapus. Jika nama tidak ditemukan, program akan memberikan pesan bahwa data mahasiswa tidak ditemukan.

ubah(nama, nilai_baru): Metode ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama. Program 
mencari mahasiswa dengan nama yang diberikan, dan jika ditemukan, nilai mahasiswa tersebut akan diperbarui 
dengan nilai baru yang dimasukkan oleh pengguna. Jika nama tidak ditemukan, program akan memberi tahu bahwa data mahasiswa tersebut tidak ada.

2. Bagian Utama Program (Program Loop)
Setelah mendefinisikan kelas Mahasiswa, program memasuki bagian utama (loop) yang menyediakan antarmuka pengguna berbasis teks untuk berinteraksi dengan pengguna.
Menu Pilihan: Program akan menampilkan menu dengan lima pilihan:
Tambah Data Mahasiswa - Pengguna diminta memasukkan nama dan nilai mahasiswa untuk ditambahkan ke dalam daftar.
Tampilkan Data Mahasiswa - Program akan menampilkan semua data mahasiswa yang sudah ada.
Hapus Data Mahasiswa - Pengguna diminta untuk memasukkan nama mahasiswa yang ingin dihapus.
Ubah Data Mahasiswa - Pengguna diminta untuk memasukkan nama mahasiswa yang ingin diubah nilainya, serta nilai baru yang akan diberikan.
Keluar - Program akan berhenti dan keluar.
Interaksi Pengguna:

Setiap kali pengguna memilih menu, program akan mengeksekusi metode yang sesuai dengan pilihan tersebut:
Jika memilih 1, program akan meminta pengguna memasukkan nama dan nilai mahasiswa untuk ditambahkan.
Jika memilih 2, program akan menampilkan daftar seluruh mahasiswa.
Jika memilih 3, program akan meminta pengguna untuk memasukkan nama mahasiswa yang ingin dihapus.
Jika memilih 4, program akan meminta nama mahasiswa yang ingin diubah nilainya dan nilai baru yang diinginkan.
Jika memilih 5, program akan keluar dan menampilkan pesan "Keluar dari program."
Looping: Program akan terus berjalan dalam loop hingga pengguna memilih opsi 5 untuk keluar. Setiap kali pengguna memasukkan pilihan, program akan memeriksa input tersebut dan mengeksekusi tindakan yang sesuai. Jika input tidak valid (misalnya angka selain 1-5), program akan menampilkan pesan bahwa pilihan tidak valid dan meminta pengguna untuk mencoba lagi.
