# Studi_Kasus_5_030_Bintang-Dzikri-Al-Bukhari
Nama : Bintang Dzikri Al Bukhari
NIM : 2609116030
Program Studi : Sistem Informasi

## Tentang Program Ini.
Program ini saya buat untuk menghitung total biaya parkir kendaraan berdasarkan jenis kendaraan (Mobil atau Motor) dan durasi parkir. Pengguna memasukkan jenis kendaraan serta jam masuk dan jam keluar (format 24 jam). Program kemudian menghitung lama waktu parkir dan mengkalkulasi total biaya berdasarkan tarif per jam yang telah ditentukan (Mobil: Rp5.000/jam, Motor: Rp3.000/jam), lalu menampilkan rincian biaya parkir secara lengkap.

## Materi yang ada di program ini.
#### Function (def)
dipergunakan untuk membungkus logika perhitungan biaya parkir dan mengembalikan nilai total biaya (return total_biaya) agar kode program lebih terstruktur dan modular.
#### If/Elif/Else
digunakan dalam menentukan tarif per jam berdasarkan jenis kendaraan yang diinputkan pengguna.
#### String Method (lower)
digunakan untuk mengubah huruf pada input jenis kendaraan menjadi huruf kecil semua, sehingga input bersifat case-insensitive (misal: "MOBIL", "Mobil", maupun
"mobil" tetap terdeteksi sebagai mobil).
#### Konversi Tipe Data (int)
digunakan untuk mengubah input jam masuk dan jam keluar dari bentuk teks (string) menjadi angka bulat (integer) agar dapat dilakukan operasi matematika.
#### Input & Output (input dan print)
digunakan untuk menerima masukan data dari pengguna dan menampilkan rincian detail biaya parkir ke layar.

### Hasil Output
<img width="647" height="70" alt="Screenshot 2026-09-22 184416" src="https://github.com/user-attachments/assets/4d3f17e6-82aa-4178-9dc8-0485a699c6f8" />

Ini adalah hasil output dimana pengguna diminta memasukan jam dan jenis kendaraan

<img width="643" height="237" alt="Screenshot 2026-09-22 184431" src="https://github.com/user-attachments/assets/fc83a428-2345-4d93-9366-39d9cb63010b" />

ini adalah hasil output yang menampilkan semua data yang telah di masukan seperti struk 

## Proses Program di Kode ini.
* Menerima input data pengguna
Pada proses ini, pengguna diminta untuk memasukkan jenis kendaraan, jam masuk, dan jam keluar.
* Menghitung durasi / lama parkir
Pada proses ini, program menghitung selisih antara jam keluar dan jam masuk (keluar - masuk) untuk memperoleh total lama parkir dalam satuan jam.
* Memproses perhitungan biaya via fungsi
Pada proses ini, program memanggil fungsi hitung_biaya_parkir() yang akan mengecek tarif per jam berdasarkan jenis kendaraan, lalu mengalikan tarif tersebut dengan lama parkir untuk menghasilkan nilai total_biaya.
* Menampilkan detail hasil perhitungan
Pada proses ini, program menampilkan seluruh informasi rincian parkir seperti jenis kendaraan, jam masuk, jam keluar, lama parkir, serta total biaya parkir yang harus dibayar.
