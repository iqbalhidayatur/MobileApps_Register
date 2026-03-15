Mobile Register App

Link Video : https://youtu.be/nD72h0SqCd0

Aplikasi Android untuk proses registrasi pengguna. Aplikasi dibuat menggunakan Android Studio dan menerapkan berbagai komponen input serta validasi form.

Deskripsi

Aplikasi ini menampilkan form registrasi lengkap. Pengguna mengisi data diri, memilih jenis kelamin, memilih beberapa hobi, dan memilih data tambahan melalui spinner. Sistem melakukan validasi input sebelum data dapat dikirim.

Proyek ini dibuat untuk mempraktikkan penggunaan komponen form Android dan teknik validasi input pada aplikasi mobile.

Fitur
Complete Form

Form registrasi menggunakan TextInputLayout.

Field yang tersedia
Nama
Email
Password
Confirm Password

Advanced Validation

Validasi dilakukan secara langsung saat pengguna mengisi form.

Validasi yang digunakan
Field tidak boleh kosong
Format email harus valid
Password dan confirm password harus sama
Validasi berjalan secara real time

Selection Controls

Aplikasi menggunakan beberapa komponen pilihan.

RadioGroup untuk memilih jenis kelamin
Checkbox untuk memilih hobi

Pengguna harus memilih minimal 3 hobi.

Spinner dan Dialog

Spinner digunakan untuk memilih data tambahan.

Contoh data pada spinner
Kota
Jurusan
Pekerjaan

Saat tombol submit ditekan, aplikasi menampilkan AlertDialog untuk konfirmasi data.

Gesture Interaction

Aplikasi mendukung interaksi Long Press pada tombol submit untuk menjalankan aksi tambahan.

Teknologi

Android Studio
Java atau Kotlin
XML Layout
Material Design Components

Struktur Form

Data yang dimasukkan pengguna

Nama
Email
Password
Confirm Password
Jenis Kelamin
Hobi
Pilihan Spinner

Cara Menjalankan Project

Clone repository ini

git clone https://github.com/iqbalhidayatur/MobileApps_Register

Buka project menggunakan Android Studio

Tunggu proses Gradle Sync selesai

Jalankan aplikasi menggunakan emulator atau perangkat Android
