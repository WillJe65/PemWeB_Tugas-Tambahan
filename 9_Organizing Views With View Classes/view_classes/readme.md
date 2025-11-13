# ANALISIS CODE

- Untuk memudahkan transisi ke kelas tampilan, kita tidak perlu fungsionalitas baru. kita hanya perlu mengubah fungsi tampilan menjadi fungsi pada kelas tampilan, lalu memperbarui pengujian.

- Di kelas tampilan TutorialViews, kita dapat melihat bahwa kedua fungsi tampilan kita dikelompokkan secara logis sebagai fungsi pada kelas yang sama. Karena kedua tampilan menggunakan template yang sama, kita dapat memindahkannya ke dekorator @view_defaults di tingkat kelas.

- Jika Pengujian perlu diubah ,kita perlu mengimpor kelas tampilan. Namun, kita juga dapat melihat pola dalam pengujian yang membuat instance kelas tampilan dengan permintaan dummy terlebih dahulu, lalu memanggil fungsi tampilan yang sedang diuji.