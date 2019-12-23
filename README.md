# watershedPKB, Algorith 4.6 implementation in python
terdapat pada halaman 22 (The Watershed Transform)

pada "Algorithm 4-6.py" terdapat fungsi bernama MinimaDetc
input parameternya adalah V, E, dan im.
V = vertices
E = (un)ordered pairs
im = image

untuk hal-hal lain diluar fungsi digunakan definisi-
definisi pada algoritma sebelumnya, yaitu algoritma 4.1 dst.

Codingan yang penulis buat ini belum bisa dijalankan, karena masih harus
membuat codingan dari algoritma sebelumnya dan harus menyesuaikannya.

1. fungsi ini diawali dengan INIT yang berarti nilai awal untuk label
2. kemudian varialbel label yang berisi list kosong
3. dilanjutkan pendefinisian label[p] dengan nilai INIT
4. lalu mendefinisikan curent_label = 1
5. fifo_init(queue) --> fungsi dari algoritma sebelumnya yang harus didefinisikan terlebih dahulu
6. berikutnya ada langkah untuk mengubah label[p],
          label[p] berubah apabila nilainya sama dengan INIT, 
          kemudian dirubah ke nilai curent_value
          lalu p dimasukkan ke queue
7. Jika queue tidak kosong, kita akan mengubah Neighbor dari nilai q
          kemudian, label[q] dimasukkan ke dalam queue
          
Output dari fungsi ini adalah gambar yang sudah berlabel
          
keterangan: Ng = Neighbor
