# ANALISIS CODE

- Unit test untuk mengecek kualitas komponen kode
- pyramid pytest digunakan untuk membantu melakukan testing.

## Extra Credit

1. pytest tidak berada di library pyramid sehingga perlu diinstal terpisah, selain itu pytest menyediakan fitur dan plugins yang bagus untuk testing.

2. tests.py disini berfungsi sebagai unit testing terhadap aplikasi yang sedang kita buat, selain itu juga kenapa dibuat file baru itu juga bertujuan untuk membuat kode lebih terorganisir.

3. Jalankan pytest di terminal dengan mereferensikan file tests.py seperti berikut : ```pytest tests.py -q```

4. agar dapat melakukan uji test html, kita bisa lakukan dengan menambahkan body content berikut

```self.assertEqual(response.body, b'<body><h1>Hello World!</h1></body>')```

5. ada beberapa alasan salah satunya untuk memastikan apakah pengujian di environment pyramid siap sebelum mengimpor kode aplikasi, selain itu untuk menjaga isolasi pengujian sehingga code terlihat bersih dan memudahkan dalam melakukan debugging.