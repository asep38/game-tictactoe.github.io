# game-tictactoe.github.io
live preview
https://asep38.github.io/game-tictactoe.github.io/

<img src="https://user-images.githubusercontent.com/112145050/255478004-7b74d0c4-6421-4828-b786-88113e6e708c.png" />

# Deskripsi
Tic-tac-toe, juga dikenal sebagai "Xs and Os" atau "Noughts and Crosses" di beberapa wilayah, adalah permainan papan klasik yang dimainkan oleh dua pemain dengan tanda yang berbeda, biasanya "X" dan "O", pada sebuah papan 3x3. Tujuan permainan ini adalah untuk mencoba menempatkan tiga tanda yang sama secara berurutan baik horizontal, vertikal, atau diagonal di papan permainan. Permainan ini berakhir dengan imbang jika papan penuh tanpa ada tiga tanda yang sama berurutan.

# fungsi yang saya gunakan
1. createBoard(): Fungsi ini digunakan untuk membuat papan permainan dengan mengisi 9 sel kosong dalam elemen gameBoard. Setiap sel akan mendapatkan event listener yang memanggil fungsi addGo saat diklik.

2. addGo(e): Fungsi ini dipanggil ketika pemain mengklik sebuah sel pada papan permainan. Fungsi ini akan menambahkan tanda (lingkaran atau silang) ke sel yang diklik, bergantian antara lingkaran ("circle") dan silang ("cross"). Fungsi ini juga memeriksa hasil permainan dengan memanggil checkScore() setiap kali tanda ditambahkan ke papan.

3. checkScore(): Fungsi ini digunakan untuk memeriksa apakah ada pemenang dalam permainan tic-tac-toe. Ia akan memeriksa kombinasi kemenangan (winningCombos) dan mengecek apakah ada tiga tanda yang sama (lingkaran atau silang) dalam kombinasi tersebut. Jika ada pemenang, maka fungsi akan mengganti teks di elemen infoDisplay dengan pesan "O === Circle Wins === O" atau "X === cross Wins === X" tergantung pada pemenangnya. Selain itu, fungsi ini juga melakukan reset papan permainan dengan menggandakan ulang setiap sel menggunakan cloneNode(true).

# Cerita
Tic-tac-toe merupakan salah satu permainan tertua di dunia, dengan sejarah yang panjang dan beragam. Asal usul pasti permainan ini sulit dilacak, tetapi beberapa teori menyatakan bahwa permainan ini bisa berasal dari Mesir kuno, Romawi, atau Cina kuno.

Ada bukti bahwa versi sederhana dari tic-tac-toe telah dimainkan di Mesir kuno pada sekitar abad ke-1 Masehi. Dinding batu yang ditemukan di kuil Karnak, Luxor, menunjukkan gambar dari apa yang tampak seperti permainan X dan O.

Selain itu, ada juga permainan yang mirip dengan tic-tac-toe yang disebut "Terni Lapilli" yang dimainkan oleh orang Romawi pada zaman kuno. Permainan ini dimainkan dengan menggambar garis-garis pada tanah untuk membuat papan 3x3 dan pemain harus mencoba menempatkan tiga batu secara berurutan di papan.

Di Cina kuno, ada sebuah permainan bernama "Gomoku Narabe" yang mirip dengan tic-tac-toe, dimana pemain harus mencoba menempatkan lima batu secara berurutan di papan permainan 15x15.

Seiring berjalannya waktu, permainan ini menyebar ke berbagai budaya dan negara, dan bentuk modern tic-tac-toe yang paling dikenal mulai muncul pada abad ke-19. Permainan ini menjadi sangat populer sebagai permainan sederhana untuk anak-anak di sekolah dan rumah, serta sebagai teka-teki di koran dan majalah.
