1. Implementasi MPI
Program menggunakan MPI untuk menjalankan tugas secara bersamaan melalui proses yang terpisah. Setiap proses bekerja mandiri dan berkomunikasi dengan mengirimkan pesan.

2. Proses Memory Sharing (Fork-Join)
Proses berbagi memori mengikuti alur berikut:

Single Start: Program berjalan di satu alur utama.

Fork: Memecah diri menjadi beberapa threads yang berbagi RAM yang sama.

Parallel: Semua threads bekerja secara bersamaan pada data yang sama.

Join: Menunggu semua thread selesai sebelum kembali ke alur tunggal.

3. Perbedaan Singkat
Memory Sharing: Menggunakan RAM yang sama (satu komputer).

MPI: Menggunakan memori terpisah (bisa antar banyak komputer).
