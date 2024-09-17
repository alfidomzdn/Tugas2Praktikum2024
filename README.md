# Tugas Pertemuan 2

Fork dan clone repository ini, lalu jalankan perintah 
```
flutter pub get
```
Buatlah tampilan form yang berisi nama, nim, dan tahun lahir pada file `ui/form_data.dart`, lalu buatlah tampilan hasil dari input data tersebut pada file `ui/tampil_data.dart`

JELASKAN PROSES PASSING DATA DARI FORM MENUJU TAMPILAN DENGAN FILE `README.md`

Penjelasan Proses Passing Data dari Form Menuju Tampilan:
File form_data.dart: File ini berfungsi sebagai form input yang memungkinkan pengguna untuk memasukkan nama, NIM, dan tahun lahir. Setelah diisi, data ini dikirim ke layar lain melalui mekanisme navigasi. Fungsi ini mengambil input teks dan menggunakan Navigator.of(context).push() untuk membuka layar baru (TampilData) sambil membawa data yang dimasukkan oleh pengguna (nama, NIM, dan tahun lahir) ke layar berikutnya.
File tampil_data.dart: File ini menampilkan data yang dikirim dari form. Setelah menerima data, widget ini menghitung usia berdasarkan tahun lahir yang diinput. Kemudian, informasi yang diterima ditampilkan dengan visual yang diatur menggunakan CircleAvatar dan Card, yang berisi data seperti nama, NIM, dan umur pengguna.


Nama : Alfido Mazdan Marsyadi

NIM : H1D022084

Shift Baru: B

## Screenshot
Contoh :
![form](https://github.com/user-attachments/assets/6fff1ac0-cdb4-42c5-8bac-20e38c802257)

![hasil](https://github.com/user-attachments/assets/87af3c56-4cbf-4780-9142-f30a278891d4)

