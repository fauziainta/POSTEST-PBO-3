# POSTEST-PBO-3
# Reservasi Klinik Kecantikan

# Fauzia Inanta Aurelia/2409116044/Sistem Informasi'B

## Deskripsi
Program ini ialah aplikasi Java untuk melakukan sebuah program CRUD sederhana untuk mengelola resevasi di Klinik Kecantikan. Program ini dikembangkan dengan ketentuan baru

a. Menerapkan encapsulation (getter dan setter)

b. Menerapkan inheritance (minimal memiliki 1 superclass dengan 2 subclass) : Person (superclass), Customer (subclass), & VIP Customer (subclass)

## Fitur
1. Tambah Reservasi

<img width="402" height="588" alt="image" src="https://github.com/user-attachments/assets/7656cc90-6df7-47e1-bd73-acb55a1890b7" />

<img width="396" height="595" alt="image" src="https://github.com/user-attachments/assets/50e7ec31-ef94-4c17-84a6-0d9cf5a1864c" />

2. Lihat Reservasi

<img width="1306" height="279" alt="image" src="https://github.com/user-attachments/assets/2d5bd466-f95c-481c-9808-07e85c5be44d" />

3. Ubah Reservasi

<img width="1306" height="607" alt="image" src="https://github.com/user-attachments/assets/796ef021-7568-4e79-bc43-1dff16972e48" />

4. Hapus Reservasi

<img width="1298" height="318" alt="image" src="https://github.com/user-attachments/assets/1f833bd4-0326-4e4c-875a-e45a6b809228" />

5. Cari Reservasi

<img width="377" height="352" alt="image" src="https://github.com/user-attachments/assets/0ed0fd01-e834-4875-a81d-f62016ddd3db" />

6. Keluar

<img width="435" height="200" alt="image" src="https://github.com/user-attachments/assets/2170c06c-d0a0-42ba-bfff-b5a4fd97656d" />

## Ketentuan Baru
1. Encapsulation
   - Pada class `Person`, `Customer`, `VIP Customer` bersifat private.
   - Penerapan getter untuk membaca nilai atribut yg bersifat private dan setter untuk mengubah nilai baru pada atribut yg bersifat private.


   <img width="441" height="591" alt="image" src="https://github.com/user-attachments/assets/d7a09c79-e943-4aff-8789-2daa37900f88" />

1. Inheritance
   - Pewarisan dengan membuat superclass dan subclass
     - superclass : `Person`
     - subclass : `Customer` & `VIPCustomer`

# POSTEST 4
1. Abstraction
- Abstract class yaitu kelass yang hanya sebagai kerangka, tidak bisa langsung dibuat objeknya. Memiliki metode abstract yang harus diisi oleh kelas turunannya  dan  membuat kode yg lebih rapi dan terorganisir. Penerapan abstract class dilakukan di superclass person.

<img width="452" height="472" alt="image" src="https://github.com/user-attachments/assets/b96971a9-9d60-436e-861f-4879537132eb" />

2. Overloading
- Penerapan method overloading dilakukan dalam banyak metode dengan nama sama tapi mwiliki parameter yang berbeda.
Penerapan overloading ini saya terapkan dalam menambahkan data reservasi custumer baru.

<img width="914" height="80" alt="image" src="https://github.com/user-attachments/assets/f42a8bfd-4daf-45b7-acab-7bbab0cbc62a" />

Output:

<img width="1198" height="279" alt="image" src="https://github.com/user-attachments/assets/243e8aec-f4e3-4f9a-b78f-e17d59eb4039" />


3. Overriding
- Saya telah melakukan penerapan overriding pada postest 3 (Penjelasan beradi di Penerapan Nilai Tambah)


    
## Penerapan Nilai Tambah
1. Overriding
Method overriding = kelas turunan mengubah metode yang sudah ada di superclass. Nama, tipe kembalian, dan parameter harus sama.
   - Method `getRole()` di Person diioverride oleh Customer, dan VIPCustomer.
   - Method `toString()` juga dioverride sehinga menampilkan informasi berbeda (misalnya ada tambahan (VIP) untuk customer VIP).


   <img width="623" height="635" alt="image" src="https://github.com/user-attachments/assets/dc4a2cba-386d-469c-9375-da0d20033ef8" />

   <img width="738" height="619" alt="image" src="https://github.com/user-attachments/assets/6968dafa-ee4f-439a-8f43-5fbb595da3c2" />


## Struktur Project

<img width="276" height="247" alt="image" src="https://github.com/user-attachments/assets/e781ae49-9382-4736-9820-bf5cdbe76376" />








