# ANALISIS CODE

Pada bagian ini dijelaskan bahwa aplikasi web bekerja dengan cara:
- Menerima request dari klien
- Memprosesnya dengan logika aplikasi
-  mengembalikan response ke klien. 
- Framework Pyramid memanfaatkan pustaka Web Ob untuk menangani objek request dan response, sehingga pemrosesan HTTP jadi lebih handal dan konsisten.

## Extra Credit

Kita dapat menggunakna raise sebagai ganti return

perbedaanya:
- return mengembalikan objek respon dari fungsi view
- raise memberi exception khusus yang akan langsung ditangani oleh pyramid untuk mengirimkan respons redirect, tanpa melanjutkan eksekusi kode selanjutnya.