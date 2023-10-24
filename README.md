## Membuat aplikasi e-library (perpustakaan digital) dengan figma, java script, vscode, SQLite
Idha Hamidaturrosadi 24 Oktober 2023

## Intro
Perpustakaan digital (digital library atau E – Library) adalah tempat di mana kita dapat membaca koleksi buku dan sumber edukatif lainnya secara digital atau daring. Di era sekarang ini, perpustakaan digital sudah umum dimiliki oleh setiap lembaga pendidikan atau organisasi, seperti yang ada di kampus kita yaitu Digital Library UIN Sunan Gunung Djati. E-library ini dibuat agar orang yang rata-rata tidak mampu membeli buku sekian banyaknya  bisa tetap membaca dan dapat memberikan,kemudahan, praktis dan tidak terbatas oleh waktu dan tempat. Motivasi saya membuat app ini yaitu sebagai sumber edukasi, karena menurut saya membaca itu adalah hal yang penting, apalagi bagi kita sebagai mahasiswa agar dapat memperoleh banyak pengetahuan dan informasi.

## Analysis : Branding

Pada tahap ini kita mengeksplorasi branding dari sistem yang dibuat. Branding meliputi:
•  Merk: Enjoy read/ knowladge
•  Tagline: happy membaca serta mendapat informasi/pengetahuan
•  Campaign: Bagaimana membuat aplikasi yang membuat penggunanya jadi banyak mengetahui segala hal/pengetahuan, serta happy saat membaca karena desainnya tidak terlalu formal
•  Target user:
o  Usia 12+
o  Seorang yang senang mencari inspirasi dan informasi baru
o  Seorang yang senang membaca tapi praktis
o  Seorang yang ingin mendapatkan pengetahuan banyak
o  Seorang yang senang membaca lewat gadget
o  Seorang yang kurang mampu membeli buku, tapi berkeinginan/excited untuk membaca
•  User experience theme:
o  Mudah
o  Memberikan banyak pengetahuan
o  Simpel
o  Menyenangkan
o  Warna: Lime fizz
o  Inspirasi desain:

<img width="614" alt="image" src="https://github.com/idhahamidaturrosadi19/App-web/assets/144808574/28c40678-8fe8-44e9-a8cd-08ca06aa4669">

## Analysis User Story :

Pada tahap ini kita mengeksplorasi kebutuhan prioritas dari para pengguna untuk kita wujudkan sebagai fitur pada sistem atau aplikasi yang akan dibuat. User story ini memudahkan kita membuat prioritas fitur-fitur untuk dikerjakan untuk jangka waktu tertentu.

| No | Sebagai |  Saya ingin bisa | Sehingga | Prioritas |
|----|---------|------------------|----------|-----------|
|1|Pengguna |Mencari buku berdasarkan judul, penulis, atau kategori|Saya bisa dengan mudah menemukan buku yang saya cari| ⭐⭐⭐⭐⭐ |
|2|Pengguna |Menyimpan daftar buku yang ingin saya baca di dalam aplikasi|Saya tidak lupa buku mana yang ingin dibaca berikutnya| ⭐⭐⭐⭐⭐ |
|3|Pengguna |Memiliki opsi untuk meminjam buku secara digital atau fisik|Kemudian bisa melacak tanggal pengembalian buku tersebut| ⭐⭐⭐⭐ |
|4|Pengguna |Melihat daftar buku populer atau baru yang ditambahkan ke perpustakaan|Saya bisa tetap up-to-date dengan koleksi perpustakaan| ⭐⭐⭐⭐⭐ |
|5|Pengguna |Saya ingin dapat mengakses buku-buku digital atau e-book|Bisa membacanya langsung melalui aplikasi| ⭐⭐⭐ |
|6|Pengguna |Memiliki opsi untuk memberikan ulasan atau peringkat buku yang sudah saya baca|Pengguna lain dapat mendapatkan rekomendasi| ⭐⭐ |
|7|Pengguna |Memiliki opsi untuk melihat detail buku, termasuk sinopsis, penulis, ulasan, dan informasi lainnya|Saya bisa mengetahuinya sebelum saya meminjam atau membeli buku tersebut| ⭐⭐⭐⭐ |
|8|Pengguna |Menerima pemberitahuan atau peringatan ketika batas waktu pengembalian buku hampir habis|Saya tidak melewatkan kesempatan untuk membacanya| ⭐⭐⭐⭐ |
|9|Pengguna |Mengatur notifikasi tentang acara khusus, promosi, atau perubahan dalam layanan perpustakaan|Saya  bisa mengetahuinya| ⭐ |
|10|Pengguna |Melihat acara atau program yang diadakan oleh perpustakaan, seperti pertemuan buku|Mendaftar untuk acara tersebut| ⭐⭐⭐⭐ |
|11|Pengguna |Memiliki opsi untuk mendaftar sebagai anggota perpustakaan melalui aplikasi|Bisa menjadi anggota perpustakaan dan dapat mengelola data anggota saya| ⭐⭐⭐ |
|12|Pengguna |Memiliki fitur baca bersama yang memungkinkan saya untuk bergabung dengan kelompok pembaca lainnya|Kami bisa berdiskusi tentang buku yang sedang kami baca| ⭐⭐⭐⭐⭐ |
|13|Pengguna |Mengakses perpustakaan saya secara offline|Dapat membaca buku tanpa koneksi internet| ⭐⭐ |
|14|Pengguna |Memiliki fitur penyimpanan bookmark yang memungkinkan saya untuk menandai halaman|Saya dapat dengan mudah kembali ke tempat yang saya tinggalkan| ⭐⭐⭐⭐⭐ |
|15|Pengguna |Menerima rekomendasi buku berdasarkan minat saya dan histori bacaan saya|Saya dapat menemukan buku-buku baru yang menarik| ⭐⭐⭐⭐ |

## Analysis : Structure Data
•  Pada tahap ini kita mengeksplorasi dan menganalisis bentuk struktur data yang mampu memfasilitasi user story yang ada, maupun yang kemungkinan besar dibutuhkan di kemudian hari
•  Kita akan merepresentasikan Entitas pada aplikasi dalam bentuk tabel Entitas dan Atribut

## Design : Arsitektur Berbasis Client-Server
Pada tahap ini kita merancang arsitektur berikut teknologi yang terdapat pada setiap komponen pembentuk aplikasi.

## Design : User Experience (UX) Design
•  Pada tahap ini kita mengeksplorasi alur interaksi pengguna yang paling praktis dan efektif untuk setiap fitur.
•  Ada banyak tools yang bisa digunakan mulai dari yang open source seperti Inkscape (yang saya gunakan), Penpot, lalu yang gratis hingga berbayar seperti Figma.
•  Desain yang dibuat di atas adalah low fidelity design dimana kualitas desainnya paling sederhana tapi cepat untuk dibuat.

![image](https://github.com/idhahamidaturrosadi19/App-web/assets/144808574/cac0767b-78d3-4442-95cb-03ff9dca8f04)

