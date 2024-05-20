Struktur Node mendefinisikan elemen dalam linked list dengan tiga komponen:
data: Menyimpan data integer.
next: Pointer ke node berikutnya.
prev: Pointer ke node sebelumnya.
Fungsi createNode membuat node baru:
Mengalokasikan memori untuk node baru.
Menginisialisasi data dengan nilai yang diberikan.
Mengatur next dan prev menunjuk ke dirinya sendiri (karena ini adalah daftar melingkar).
Fungsi insertNode menambahkan node baru ke dalam linked list:
Membuat node baru.
Jika linked list kosong (*head == NULL), node baru menjadi head.
Jika tidak, node baru ditempatkan di akhir linked list, dengan memperbarui pointer next dan prev node terkait.
Fungsi printList mencetak isi linked list:
Memeriksa apakah linked list kosong.
Jika tidak kosong, mencetak data dan alamat setiap node mulai dari head hingga kembali ke head (menggunakan loop do-while).
Fungsi removeDuplicates menghapus node duplikat dari linked list:
Memeriksa apakah linked list kosong.
Menggunakan dua loop untuk membandingkan setiap node dengan node lainnya.
Jika ditemukan duplikat, node tersebut dihapus dengan memperbarui pointer next dan prev dari node tetangganya.
Fungsi sortList mengurutkan linked list menggunakan algoritma bubble sort:
Memeriksa apakah linked list kosong.
Menggunakan dua loop untuk membandingkan dan menukar data antar node jika tidak berurutan.
Fungsi main mengatur jalannya program:
Menginisialisasi head linked list ke NULL.
Meminta jumlah node yang ingin dimasukkan dan datanya.
Memasukkan data ke dalam linked list.
Mencetak linked list sebelum dan sesudah pengurutan dan penghapusan duplikat.
Penjelasan ini mencakup semua aspek penting dari kode, termasuk bagaimana fungsi-fungsi tersebut bekerja bersama untuk mengelola linked list melingkar ganda.
