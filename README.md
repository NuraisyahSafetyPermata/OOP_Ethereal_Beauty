# OOP_Ethereal_Beauty
Proyek aplikasi Point of Sale (POS) Java untuk Ethereal Beauty memungkinkan manajemen efisien penjualan produk kecantikan. Fiturnya mencakup tambah, hapus produk, cetak struk, hitung transaksi, dan kelola pembayaran dengan antarmuka menggunakan JFrame, JTable, JButton, JLabel, JTextArea, JTextField, dan JScrollPane.

A.	Deksipsi Project
"Ethereal Beauty" adalah sebuah project yang dikembangkan untuk menangani transaksi penjualan produk kecantikan secara efisien dan mudah. Project ini bertujuan untuk membantu toko kecantikan dalam memproses penjualan harian dengan lebih cepat dan akurat, mengurangi kesalahan manusia, dan meningkatkan pengalaman pelanggan. Project ini merupakan sistem Point of Sale (POS) yang dirancang untuk toko kecantikan dengan fitur utama sebagai berikut: 
  1.	Total
       Fitur ini berfungsi untuk menghitung total harga dari semua barang yang ditambahkan ke dalam keranjang belanja. Setiap kali barang ditambahkan, sistem akan         memperbarui total harga secara otomatis.
  2.	Cash
      Fitur ini memungkinkan kasir untuk mencatat jumlah uang tunai yang diberikan oleh pelanggan. Dengan memasukkan jumlah uang tunai yang diterima, sistem dapat        menghitung kembalian yang harus diberikan.
  3.	Balance
      Setelah jumlah uang tunai dimasukkan, fitur balance akan menghitung selisih antara uang tunai yang diterima dan total harga, sehingga kasir dapat mengetahui        jumlah kembalian yang harus diberikan kepada pelanggan.
  4.	Pay
      Fitur ini memproses pembayaran setelah kasir memasukkan uang tunai. Sistem akan mencatat transaksi, mengurangi stok barang yang terjual, dan mencetak struk         pembayaran yang berisi detail transaksi.
  5.	Add
      Fitur ini memungkinkan kasir untuk menambahkan barang ke dalam keranjang belanja.
  6.	Delete
      Fitur ini memungkinkan kasir untuk menghapus barang dari keranjang belanja jika ada kesalahan dalam memasukkan barang atau jika pelanggan berubah pikiran.
  7.	Print
      Setelah pembayaran diproses, fitur ini mencetak struk pembayaran yang berisi detail transaksi seperti daftar barang yang dibeli, total harga, jumlah uang           tunai yang diterima, dan jumlah kembalian. Struk juga menampilkan informasi toko seperti nama, alamat, dan nomor telepon.

B.	Teknologi atau Framework yang Digunakan
  1.	Bahasa Pemrograman
      Project ini dikembangkan menggunakan bahasa pemrograman Java, karena sifatnya yang platform-independent, memungkinkan aplikasi untuk berjalan pada berbagai         sistem operasi tanpa perlu modifikasi besar.
  2.	Library dan API
      Untuk pengembangan antarmuka pengguna (GUI), project ini menggunakan Java Swing. Swing adalah bagian dari Java Foundation Classes (JFC) yang menyediakan             serangkaian komponen GUI yang kaya dan dapat disesuaikan. Swing memungkinkan pengembang untuk membuat antarmuka pengguna yang responsif dan user-friendly.
  3.	Struktur Kode
      Struktur kode dalam project ini diorganisir dengan baik untuk memisahkan logika bisnis dari antarmuka pengguna. Beberapa kelas utama yang biasanya ditemukan        dalam project seperti ini antara lain:
      a.	Main Class
          Kelas ini berfungsi sebagai titik masuk aplikasi, menginisialisasi komponen utama dan menampilkan GUI.
      b.	Item Class
          Kelas ini mewakili barang-barang yang dijual, menyimpan informasi seperti nama barang, harga, dan kode barang.
      c.	Cart Class
          Kelas ini mengelola keranjang belanja, menambah dan menghapus barang, serta menghitung total harga.
      d.	Payment Class
          Kelas ini mengelola proses pembayaran, mencatat uang tunai yang diterima dan menghitung kembalian.
      e.	Receipt Class
          Kelas ini bertanggung jawab untuk mencetak struk pembayaran dengan detail transaksi.
  4.	Platform 
      Project ini dikembangkan sebagai aplikasi desktop. Aplikasi desktop dipilih untuk memberikan performa yang cepat dan dapat diandalkan, serta tidak tergantung       pada koneksi internet yang stabil, berbeda dengan aplikasi web yang memerlukan akses internet terus-menerus.

C.	SS Program
    •	Output Awal
       ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/6a7eef11-48c0-4a51-962b-4b4653db6937)
    •	Output ketika ditambahkan barang, secara otomatis harga total berubah mengikuti jumlah produk yang ditambahkan, kemudian pelanggan akan memasukan cash yaitu         jumlah saldo yang ada, dan balance adalah kembalian dari harga total.
       ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/adcdb006-71d7-4258-9c1e-5c6edec8441d)
    •	Output ketika barang dikurangi, maka secara otomatis total, cash, dan balance berubah
       ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/a7122206-a6e2-4704-8cc5-987528d416d9)
    •	Ketika klik tombol pay & print maka secara otomatis akan tercetak struknya
      ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/1fb6dd59-d876-4ffd-830d-0fd2258d998c)
      ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/4e021217-d6e7-4e1f-9771-286cc96d6a2c)
      ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/5b0de687-91a2-42e8-8ee4-4262db81ab7a)
      ![image](https://github.com/NuraisyahSafetyPermata/OOP_Ethereal_Beauty/assets/130532356/10fa3974-9526-4830-8a5a-36265524ba86)





 
 
 

