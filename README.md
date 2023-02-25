# Tugas 1 Pemograman Terstruktur
1. Saya mengikuti praktikum di mata kuliah Pemrograman terstruktur pertemuan pertama. Praktikum ini bertujuan untuk memperkenalkan kami dengan bahasa pemograman javascript. Saat pertama kali mulai praktikum, saya merasa sangat canggung dengan bahasa pemograman javascript. Namun, dengan bantuan pembimbing praktikum dan teman-teman sekelas, saya mulai memahami bagaimana menjalankan javascript di browser dan juga di node js. Saya menghadapi beberapa kesulitan selama praktikum, terutama saat mencoba memunculkan 

``` javacript
console.log("Hello World")

```

   Namun, dengan bantuan pembimbing praktikum dan teman-teman sekelas, saya akhirnya bisa mengatasi kesulitan tersebut dengan mengsave file code yang saya tulis.

2. Adapun kelebihan dan kekurangan menggunakan browser dan Node.js adalah sebagai berikut : 

- Browser:

Kelebihan: 
* Memungkinkan untuk membuat halaman web yang interaktif
* Memiliki kemampuan untuk memanipulasi struktur dan tampilan halaman web
* Memiliki akses ke berbagai API web, memiliki dukungan luas untuk JavaScript
* Banyak perangkat lunak dan alat bantu yang tersedia untuk pengembangan web di browser.

Kekurangan: 
* Tidak memiliki akses langsung ke sistem operasi
* Keterbatasan dalam hal memori dan penggunaan CPU
* Perbedaan antara browser dalam hal implementasi dan dukungan terhadap teknologi web tertentu
* Tidak dapat berjalan di luar lingkungan browser
* Penggunaan browser tergantung pada dukungan pengguna.

- Node.js:

Kelebihan: 
* Memungkinkan untuk menjalankan kode JavaScript di luar browser
* Memiliki kinerja yang cepat dan efisien
* Memiliki dukungan yang kuat dari komunitas pengembang
* Mudah untuk diinstal dan digunakan
* Memungkinkan untuk memanipulasi berkas
* Melakukan operasi I/O.

Kekurangan: 
* Tidak memiliki akses ke API web seperti yang dimiliki oleh browser
* Tidak dapat memanipulasi struktur dan tampilan halaman web
* Memiliki kurva belajar yang lebih tinggi untuk pemula
* Tidak cocok untuk pengembangan aplikasi web yang membutuhkan interaksi dengan pengguna secara langsung
* Memiliki risiko keamanan karena akses langsung ke sistem operasi.

3. Ketika menjalankan baris kode di bawah ini pada node.js

``` javascript
let randomQuote;
const quotes = [
    "The best way to predict the future is to create it.",
    "Be the change you wish to see in the world.",
    "Innovation distinguishes between a leader and a follower.",
    "Believe you can and you're halfway there.",
    "Your time is limited, don't waste it living someone else's life."];
randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
console.log(randomQuote);
```

selanjutnya apakah yang terjadi jika secara terus menerus hanya menjalankan dua baris terakhir? 
Jika hanya dua baris terakhir yang diulang terus menerus, maka hanya akan mencetak kutipan acak di terminal secara berulang-ulang.
