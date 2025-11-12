# ANALISIS CODE

- pserve akan mencari app:main dengan membaca use nya yang artinya gunakan entry point main dari package python dari folder tutorial.
- didalam file __init__ terdapat program main yang dimana merupakan entry point dari tutorial
- .ini format sebagai file setting
- configurasi yang dipisah dengan code produksi untuk memudahkan perubahan variable tertentu

## Extra Credit

1. Sebenarnya bisa jika ingin menggunakan pure python dikarenakan .ini bertujuan untuk load WSGI app dan memulai servernya. Untuk codenya itu sudah ada pada tutorial 2 pada app.py yang dimana merupakan pure code python

2. yap kita bisa melakukan itu, biasanya dilakukan jika ingin dijalankan ditahap berbeda seperti tahap pengembangan, produksi dan test, selain itu juga kita tidak perlu mengubah 1 file cukup buat 2 file berbeda dan jalankan 1 file yang memiliki fitur tertentu yang ingin dijalankan.

3.  Pyramid akan mencari fungsi aplikasi didalam package tutorial dan juga __init__ merupakan file default sehingga otomatis akan mencari entry_point di file __init__

4. setting merupakan kamus yang menyimpan semua configurasi dari file ini kamu yang ada, ** syntax ini digunakan untuk mengambil semua keyword yang ada dan masukan dalam satu dictionary bernama settings. syntax tersebut merupakan syntax pure python.