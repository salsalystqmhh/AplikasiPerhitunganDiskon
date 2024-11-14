# Aplikasi Perhitungan Diskon

Aplikasi Perhitungan Diskon adalah aplikasi berbasis Java yang memungkinkan pengguna menghitung diskon dari harga asli berdasarkan kupon, diskon tambahan, atau slider yang dipilih. Aplikasi ini memberikan antarmuka sederhana untuk memasukkan harga asli, kupon diskon, dan diskon tambahan serta menampilkan harga akhir setelah diskon.

## Keunggulan Aplikasi

- **Penggunaan Kupon Diskon**: Mendukung penggunaan kupon diskon yang valid dengan nilai diskon yang beragam.
- **Diskon Tambahan**: Menyediakan opsi untuk memilih diskon tambahan melalui dropdown atau slider.
- **Riwayat Diskon**: Mencatat riwayat transaksi diskon untuk referensi pengguna.
- **Antarmuka yang Sederhana**: Didesain dengan Java Swing untuk memudahkan penggunaan.

## Pembuat Aplikasi

Salsa Alya Istiqamah - 2210010089 - Tugas 3

## Fitur

Aplikasi Perhitungan Diskon memiliki fitur-fitur berikut:

1. **Validasi Kupon Diskon**  
   Pengguna dapat memasukkan kode kupon untuk mendapatkan diskon tertentu. Aplikasi akan menampilkan pesan jika kupon yang dimasukkan tidak valid.

2. **Diskon Tambahan**  
   Pengguna dapat memilih diskon tambahan melalui dropdown atau slider. Aplikasi memastikan bahwa diskon tambahan dapat dikombinasikan dengan kupon diskon untuk hasil yang optimal.

3. **Hitung Harga Akhir**  
   Aplikasi menghitung harga akhir setelah diskon dan menampilkan potongan harga beserta total harga yang perlu dibayar.

4. **Riwayat Transaksi**  
   Setiap perhitungan diskon yang dilakukan dicatat dalam sebuah area teks sebagai riwayat untuk membantu pengguna melacak diskon yang diterapkan.

5. **Antarmuka yang Mudah Digunakan**  
   Antarmuka berbasis Java Swing yang memungkinkan pengguna memasukkan harga, kupon, dan melihat hasil akhir dengan mudah.

## Cara Menjalankan

1. Clone atau unduh repositori ini ke komputer Anda.
2. Buka proyek di IDE pilihan Anda (misalnya, NetBeans, IntelliJ, atau Eclipse).
3. Pastikan JDK sudah terkonfigurasi dengan benar di IDE Anda.
4. Jalankan `Tugas3` untuk memulai aplikasi.

## Struktur Kode

- **Tugas3**: Kelas utama yang mengelola antarmuka dan logika perhitungan diskon.
- **initComponents**: Metode untuk menginisialisasi komponen GUI, termasuk pengaturan tombol, label, dan slider.
- **hitungDiskon**: Metode utama yang menangani logika perhitungan diskon berdasarkan harga asli, kupon diskon, dan diskon tambahan. Juga mencatat riwayat transaksi di `jTextArea1`.
- **Daftar Kupon**: Menggunakan `HashMap` untuk menyimpan dan memvalidasi kode kupon beserta diskonnya.
- **Riwayat Transaksi**: Menampilkan hasil perhitungan diskon pada area teks sebagai riwayat.

## Demo


note : Aplikasi ini dirancang untuk memudahkan pengguna dalam menghitung harga akhir setelah diskon dengan berbagai kombinasi kupon dan diskon tambahan.

