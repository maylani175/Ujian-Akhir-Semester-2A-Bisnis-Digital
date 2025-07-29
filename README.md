# Ujian-Akhir-Semester-2A-Bisnis-Digital

Aplikasi Toko Makeup GlowStore ini adalah program berbasis command line (CLI) menggunakan bahasa Python. Aplikasi ini membantu proses pembelian produk makeup dengan fitur keranjang belanja, manajemen stok, perhitungan total belanja, input uang dari pembeli, perhitungan kembalian, dan penyimpanan struk pembelian dalam format JSON.

1. Fitur Utama 📌
   
| Fitur                    | Deskripsi                                                                  |
| ------------------------ | -------------------------------------------------------------------------- |
| 🛍️ Daftar Produk         | Menampilkan daftar produk makeup beserta harga dan stok.                   |
| 🧺 Keranjang Belanja     | Menambahkan produk ke keranjang dengan jumlah sesuai stok.                 |
| 📉 Manajemen Stok        | Stok otomatis berkurang setelah produk dibeli.                             |
| 💸 Input Pembayaran      | Pembeli menginputkan jumlah uang; validasi jika kurang dari total belanja. |
| 💰 Perhitungan Kembalian | Menghitung selisih antara total belanja dan uang yang dibayarkan.          |
| 🧾 Simpan Struk JSON     | Menyimpan struk pembelian ke file `struk_belanja.json`.                    |

2. Alur Penggunaan
   -Program menampilkan daftar produk.
   -Pengguna memilih produk berdasarkan kode dan jumlah.
   -Total belanja ditampilkan.
   -Pengguna memasukkan uang.
   -Program menampilkan kembalian.
   -Struk pembelian otomatis disimpan dalam file struk_belanja.json.
   
3. Daftar Produk Di awal program akan menampilkan daftar produk yang tersedia, Tiap produk punya nomor/kode unik (1, 2, 3, dst.), Dan setiap produk juga punya nama dan         harga.
   Contohnya:
    Nomor 1: Lipstik Matte, harganya Rp75.000
    Nomor 2: Foundation Cair, harganya Rp120.000
  Tujuan bagian ini adalah agar program tahu produk apa saja yang tersedia dan bisa ditampilkan ke pengguna.

4. Keranjang Belanja Ini adalah tempat untuk menyimpan semua produk yang dibeli pengguna. Setiap kali pengguna pilih produk dan masukkan jumlah, produk itu akan dimasukkan     ke dalam keranjang.

5. Menampilkan Daftar Produk Program akan menampilkan semua produk yang tersedia, dengan format seperti:
   Lipstik Matte - Rp75.000
   Foundation Cair - Rp120.000 Supaya pengguna tahu nomor mana yang harus diketik saat ingin membeli.
   
7. Memasukkan Produk yang Ingin Dibeli. Di bagian ini, pengguna diminta untuk: -Mengetik kode produk -Mengetik berapa banyak jumlah produk yang mau dibeli Setelah itu,         produk akan disimpan ke dalam keranjang Kalau pengguna memasukkan 0, maka artinya mereka selesai belanja, dan program akan lanjut ke tahap berikutnya.

8. Menampilkan Isi Keranjang dan Total Belanja Setelah pengguna selesai memilih produk, program akan menampilkan isi keranjang (produk apa yang dibeli dan berapa               jumlahnya), Menghitung total belanja (dengan menjumlahkan semua harga produk yang dipilih × jumlahnya).
   Contoh:
   Lipstik Matte x2 = Rp150.000
   Bedak Padat x1 = Rp65.000
   Total Belanja: Rp215.000

9. Setelah itu pengguna akan memasukan jumlah uang, misalnya total belanja Rp. 250.000 lalu pengguna memasukan jumlah uang sebesar Rp.300.000 makan program akan menampilkan    kembalian uang dan struk belanja.
