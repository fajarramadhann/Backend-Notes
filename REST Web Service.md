
REST atau **RE**presentational **S**tate **T**ransfer adalah sebuah cara untuk membangun aplikasi web yang memanfaatkan protokol HTTP dan memanfaatkan sumber daya ( resources ) sebagai objek yang dapat diakses dan dapat di modifikasi melalui operasi standar HTTP seperti **GET** ( mengambil data ), **POST** ( mengirim data ), **PUT** ( memperbarui data ), **DELETE** ( menghapus data ).

Contoh sederhana dari konsep REST kaya sebuah toko online yang nyediain daftar produk yang bisa dipesan sama pelanggan, nah setiap produk yang ada di dalem sistem toko online itu bisa disebut URI ( Uniform Resources Identifier ), contohnya https://fajarrmdhn.me/products/123. Pas pelanggan mau pesen produk itu, aplikasi bakal ngirimin permintaan HTTP POST ke URI dengan data yang di perluin kaya jumlah pesanan, alamat pengiriman, informasi pembayaran, dll.

Analogi gampang nya, REST bisa disamain dengan restoran cepat saji. Setiap menu makanan yang ada di restoran itu bisa di identifikasi sama nomor yang unik, kaya **nomor 1 buat burger** & **nomor 2 buat kentang goreng**, terus misalnya pelanggan mau pesen burger dia bakal bilang ke pelayan nomor **1** misalnya, terus bakal disiapin burger itu dan di kasihin ke pelanggan. nah **nomor 1** itu kaya URI yang ngidentifikasi sumber daya atau menu burger dan pesanan pelanggan adalah operasi HTTP yang sesuai ( GET ).

