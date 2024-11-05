# CapstoneModule2
# Latar Belakang
Airbnb bukanlah situs yang asing bagi para orang yang sering melakukan traveling. Startup ini menyediakan jasa sewa properti, seperti hotel, apartemen, hostel dan juga villa di seluruh dunia. Startup ini tentunya memudahkan wisatawan atau traveller untuk mencari penginapan di destinasi yang menjadi tempat tujuan.

Seperti yang kita ketahui bahwa Ibu kota Thailand, Bangkok menduduk peringkat teratas atau pertama sebagai kota yang paling banyak di kunjungi di dunia sepanjang tahun 2023 (sumber CNN Indonesia). Tentunya Airbnb bisa memudahkan para wisatawan yang berkunjung ke Bangkok untuk mendapatkan penginapan dengan kriteria yang di inginkan.
# Pernyataan Masalah
Pada listing Airbnb di Bangkok ini, untuk meningkatkan revenue kita bisa mencari tahu wilayah mana saja dan juga ruangan tipe apa yang paling sering dan paling jarang di pilih oleh para tamu(guest) sebagai tempat untuk menginap. Kita juga perlu mencari tahu apakah harga mahal dan murah mempengaruhi pemilihan wilayah dan tipe ruangan.
# Dataset yang digunakan
dataset ini berisi tentang informasi yang dapat membantu kita dalam mengolah dan menganalisis data. dataset ini sendiri terdiri dari 16 kolom dengan penjelasan sebagai berikut :
- id : Pengidentifikasi unik Airbnb untuk listing.
- name : Nama dari listing.
- host_id : Pengidentifikasi unik Airbnb untuk host/pengguna.
- host_name : Nama host. Biasanya hanya nama depan.
- neighborhood : Wilayah lingkungan digeokode menggunakan garis lintang dan bujur terhadap lingkungan yang ditentukan oleh shapefile digital terbuka atau publik.
- latitude : Menggunakan proyeksi World Geodetic System (WGS84) untuk garis lintang dan bujur.
- longitude : Menggunakan proyeksi World Geodetic System (WGS84) untuk garis lintang dan bujur.
- room_type : [Entirehome/apt |Privateroom|Sharedroom|Hotel]
- price	: Harga harian dalam mata uang lokal. Perhatikan bahwa simbol $ mungkin digunakan terlepas dari lokasi.
- minimum_nights : Jumlah minimum malam menginap untuk listing (aturan kalender dapat berbeda).
- number_of_reviews : Jumlah ulasan yang dimiliki listing tersebut.
- last_review : Tanggal ulasan terakhir atau terbaru.
- reviews_per_month : review per bulan
- calculated_host_listings_count : Jumlah listing yang dimiliki host dalam pengambilan data saat ini di geografi kota/region.
- availability_365 : availability_x. Kalender menentukan ketersediaan listing x hari ke depan. Perhatikan bahwa sebuah listing mungkin tersedia karena telah dipesan oleh tamu atau diblokir oleh host.
- number_of_reviews_ltm	: Jumlah ulasan yang dimiliki listing dalam 12 bulan terakhir.
# Data Cleaning
Menganalisis data yang perlu di hapus, Memeriksa dan Menangani missing value, Duplicate data, data anomali dan outliers.
# Data Analysis
Setelah kita melakukan data cleaning, kita bisa mulai analisis untuk menjawab permasalahan dan juga untuk mencari tahu karakteristik apa saja yang berpengaruh dalam meningkatkan revenue.
analisa akan berfokus pada wilayah dan jenis kamar yang paling banyak dan paling sedikit diminati berdasarkan review dan juga harga. berikut adalah hal yang perlu di analisis : 

- wilayah mana yang paling banyak memiliki tamu(guest) berdasarkan review?
- wilayah mana yang memiliki review paling banyak dalam 12 bulan terakhir?
- tipe ruangan apa yang paling banyak dipilih tamu(guest) dari wilayah yang paling banyak dipilih tamu(guest)?
- tipe ruangan apa yang paling banyak dipilih tamu(guest) dari wilayah yang paling banyak dipilih tamu(guest) selama 12 bulan terakhir?
- wilayah mana yang paling sedikit memiliki tamu(guest) berdasarkan review?
- wilayah mana yang memiliki review paling sedikit dalam 12 bulan terakhir?
- tipe ruangan apa yang paling banyak dipilih tamu(guest) dari wilayah yang paling sedikit dipilih tamu(guest)?
- tipe ruangan apa yang paling banyak dipilih tamu(guest) dari wilayah yang paling sedikit dipilih tamu(guest) selama 12 bulan terakhir?
- apakah harga berpengaruh pada pemilihan tipe ruangan?
# Kesimpulan dan Rekomendasi
### **Kesimpulan**
- Terdapat 9 wilayah yang selalu menjadi tempat paling banyak di pilih tamu(guest) baik secara keseluruhan maupun selama 12 bulan terakhir.
- Terdapat 9 wilayah yang selalu menjadi tempat paling sedikit di pilih tamu(guest) baik secara keseluruhan maupun selama 12 bulan terakhir.
- Selain karena tempat wisata yang populer dan terkenal, Wilayah-wilayah yang paling banyak di pilih oleh tamu(guest) terletak di dekat pusat kota Bangkok.
- Wilayah-wilayah yang paling sedikit di pilih oleh tamu(guest) terletak cukup jauh dari pusat kota Bangkok.
- Jenis kamar Entire Home/apt lebih banyak di pilih oleh tamu(guest) yang berada di dekat pusat kota (wilayah paling banyak di pilih tamu(guest)).
- Jenis kamar Private Room lebih banyak di pilih oleh tamu(guest) yang berada jauh dari pusat kota (wilayah paling sedikit di pilih tamu(guest)).
- Di wilayah yang dekat dari pusat kota, harga Jenis kamar Hotel Room cukup tinggi sehingga tidak terlalu banyak di pilih oleh tamu(guest).
- Di wilayah yang dekat dari pusat kota, meskipun harga Jenis kamar Entire Home/apt juga cukup tinggi namun tamu(guest) banyak memilih Jenis kamar tersebut.
- Di wilayah yang jauh dari pusat kota, harga Jenis kamar Private Room lebih murah sehingga banyak tamu(guest) yang memilih jenis kamar tersebut.
- Di wilayah yang jauh dari pusat kota, meskipun harga Jenis kamar Entire Home/apt juga cukup tinggi namun tamu(guest) banyak memilih Jenis kamar tersebut.

### **Rekomendasi**
1. Membuat promosi untuk menarik perhatian pemilik properti di sekitar pusat kota bangkok untuk meningkatkan maupun menambah listing di sekitar pusat kota.
2. Melakukan riset lokasi-lokasi wisata paling dekat dari listing dan menambahkan pada keterangan pada promosi listing di Airbnb agar wisatawan yang berminat untuk melihat listing tersebut jadi tertarik ketika melihat lokasi-lokasi wisata tersebut.
3. Memperbanyak promosi listing dengan jenis kamar Entire Home/apt baik di dekat pusat kota maupun jauh dari pusat kota. Karena meskipun harga dari jenis kamar Entire Home/apt cukup tinggi, jenis kamar tersebut banyak di minati oleh tamu(guest) baik yang di dekat pusat kota maupun jauh dari pusat kota.
4. Pemilik Listing dengan jenis kamar Hotel Room bisa memberikan promo/diskon pada waktu-waktu tertentu untuk menarik peminat tamu(guest).
5. Pemilik listing mungkin bisa meminta tamu(guest) untuk menulis review untuk listing setelah di sewa agar bisa menarik tamu(guest) lain saat akan memilih listing. Penulisan review juga bisa membuat pemilik listing mengetahui apa saja hal yang perlu di perbaiki dan apa saja hal yang perlu ditingkatkan.

Diharapkan analisis ini bisa membantu para pemilik listing untuk meningkatkan revenue dan membantu bisnis listing Airbnb di daerah Bangkok.
