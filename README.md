# Sistem Pendaftaran Konser Post-test-4
Nama: Nur Aliyya

Kelas: C

Nim: 2409116094

# Penerapan Abstraction
Pada program ini, abstraction diterapkan dengan membuat abstract class Peserta yang menjadi induk bagi class PesertaVIP dan PesertaReguler. Peserta memiliki method abstract tampilkanInfo() yang wajib di-override oleh setiap subclass. Dengan abstraction, kita hanya mendefinisikan struktur umum peserta tanpa detail implementasi, dan detailnya diberikan pada subclass sesuai jenis peserta.

# Penerapan Polymorphism

Polymorphism diterapkan dalam dua bentuk:

Overriding

Method tampilkanInfo() di-override pada PesertaVIP dan PesertaReguler. Masing-masing class memberikan implementasi berbeda sesuai data tambahan yang dimiliki (fasilitas untuk VIP, nomor kursi untuk Reguler).

Overloading

Method cariPeserta() pada PesertaService dibuat dalam dua versi:

cariPeserta(int id) mencari peserta berdasarkan ID. Dan cariPeserta(String nama) mencari peserta berdasarkan Nama.

Ini contoh method overloading karena nama method sama, tetapi parameter berbeda.


<img width="1408" height="845" alt="image" src="https://github.com/user-attachments/assets/4ae2204f-2250-4c83-85ab-dc36a2f84d12" />

<img width="1474" height="847" alt="image" src="https://github.com/user-attachments/assets/e2046e02-3ac8-4d59-8e3a-f905e6b0daf7" />

<img width="1458" height="885" alt="image" src="https://github.com/user-attachments/assets/a164d85e-0ece-4c95-b245-3d30283ed351" />

<img width="1521" height="887" alt="image" src="https://github.com/user-attachments/assets/e23c0e69-aa79-49d6-bb97-a88162539cf9" />



