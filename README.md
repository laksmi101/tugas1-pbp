# Portofolio Personal Website - Ni Putu Laksmi Priya Dewi Dasi

Website ini adalah tugas pembuatan portofolio pribadi menggunakan HTML dan CSS murni. Berikut adalah penjelasan komponen yang digunakan dalam pengembangan website ini:

## 1. Daftar Tag HTML yang Digunakan beserta Fungsinya
Berikut adalah daftar tag HTML yang dipakai:

*   **`<html>`** : Tag perintis utama untuk membuat seluruh halaman web.
*   **`<head>`** : Berisi informasi meta dokumen seperti judul tab layar dan tautan ke file CSS (tak terlihat langsung di halaman web).
*   **`<title>`** : Memberikan judul teks yang muncul di _tab browser_.
*   **`<meta>`** : Memberikan deskripsi dan pengaturan kamera layar (_viewport_) agar selalu tampil pas ketika dibuka dari perangkat mobile (HP).
*   **`<link>`** : Menyambungkan file HTML ini dengan desain di file eksternal (seperti `style.css` dan fon / huruf _Outfit_ dari penyimpanan Google Font).
*   **`<body>`** : Tubuh utama web yang membungkus seluruh konten yang akan dilihat pengunjung di layar.
*   **`<nav>`** : Berfungsi sebagai wadah khusus untuk meletakkan menu navigasi (tombol-tombol akses perpindahan halaman utama).
*   **`<header>`** : Bagian kepala halaman. Umumnya dipakai memuat logo kampus atau judul utama bagian paling awal halaman.
*   **`<main>`** : Membungkus konten atau isi inti profil pada halaman tersebut.
*   **`<section>`** : Memisah dan membagi konten-konten web menjadi bagian-bagian (seksi) area tertentu.
*   **`<h1>`, `<h2>`, `<h3>`** : Digunakan untuk menuliskan Judul Teks dengan peringkat ukuran (H1 paling besar tebal untuk judul utama yang paling penting).
*   **`<div>`** : Tag serbaguna berupa kotak maya pembungkus. Berguna untuk mengelompokkan elemen secara paksa guna memudahkan pengaturan modifikasi jarak atau grid dari CSS.
*   **`<img>`** : Menampilkan file foto/gambar (*Image*), seperti foto profil personal maupun logo kampus universitas kita.
*   **`<span>`** : Membungkus teks pendek di antara baris teks panjang (misal untuk memberikan warna berbeda atau menebalkan pada ujung kolom label dan nilai spesifik).
*   **`<a>`** : _Anchor_ (Jangkar) yang membuat tautan/link yang bisa diklik untuk meloncat pindah ke halaman beranda/pendidikan, maupun meluncur cepat membuka tautan keluar ke aplikasi WhatsApp dan situs Google Maps.
*   **`<iframe>`** : Menyematkan atau melekatkan seluruh halaman utuh dari milik alamat luar untuk diintegrasikan masuk bekerja kedalam web kita (dipakai langsung menampilkan peta lokasi jalan hidup/pabrik Maps).
*   **`<svg>`, `<path>`, `<polyline>`, `<line>`** : Kumpulan tag perintis pembuat kode garis coretan ikon visual vektor matematika ringan (seperti grafik ikon panah keluar situs di tomboh tautan _Maps_).
*   **`<ol>`** : _Ordered List_, membuat daftar berurutan terstruktur (mulai berhuruf abjad atau bernomor secara eksak). Dipakai membuat alur waktu di halaman `pendidikan.html`.
*   **`<ul>`** : _Unordered List_, membuat serangkaian daftar catatan tidak berurutan poin berbentuk titik-titik poin (Bullet) secara natural. Dipakai pada spesifikasi keahlian ranah `skil.html`.
*   **`<li>`** : _List Item_, tag wajib di dalam unsur `<ol>` maupun `<ul>` tempat Anda mulai mengetik satu per satu nama/jenis item daftar rinci yang dikehendaki.
*   **`<table>`, `<tr>`, `<td>`** : Trilogi tag standar untuk mendirikan ruang Tabel _grid kotak-kotak struktur statis_ tempo dulu (membuat Header, Main, Sidebar, Footer) yang spesifik diwajibkan dalam pengerjaan `layout.html`. (`<table>` untuk bingkai luar, `<tr>` khusus membangun baris datar, dan `<td>` khusus ruang kolom isian sel vertikalnya).
*   **`<style>`** : Mengizinkan kode *Internal CSS* dihembuskan berpadu kental di dalam sebuah tubuh HTML (Diterapkan spesifik pada sebagian elemen `skil.html` dan `layout.html`).

## 2. Fitur Parameter CSS (Cascading Style Sheet) Utama & Kegunaannya
File `style.css` memberikan polesan riasan estetika dekorasi untuk desain tata letak (layout) dan warna dominan, sehingga web tidak kering/usang hitam putih kaku saja.

*   **`color` & `background-color` / `background`** : Memberikan warna padat / pola gradasi ke kanvas latar belakang dokumen `body` sekaligus mencerahkan font pewarna cerah di kartu ruang gelap profil.
*   **`font-family`** : Mengubah tulisan dasar Arial / Times New Roman menjadi jenis gaya huruf (_font_) estetik dan segar moderen (menggunakan integrasi *Outfit* API Google Fonts).
*   **`display: flex` / `grid`** : Teknologi penataan elastis canggih era kini untuk memblok tata letak kotak menyejajarkan sentral terpusat (rata tengah) secara instan. Fiturnya juga menyajilkan _grid_ petak memecah lajur 2 arah (digunakan untuk tabel info personal) membuahkan simetri yang pas saat responsif merespon layar mengecil.
*   **`border-radius`** : Melunakkan sudut-sudut kaku keras tajam 90° menjadi elegan melengkung atau bulat rapi sempurna membalut (seperti sisi pada tombol pinggiran kotak utama, map peta lokasi lokasi dan bingkai foto sirkular bulat lonjong).
*   **`box-shadow`** : Mentransfer sentuhan efek riak / penciptaan bayangan lembut gelap tebal jatuh pada sisi kartu bagian belakang tubuh layar monitor, ilusi 3D menjolkan kartu profil depan terbang seakan mengambang / "melayang".
*   **`margin` & `padding`** : Mengendalikan jeda spasi napas kelonggaran letak batas. `Margin` menghalau objek menjauh merenggang ke batas daerah tetangga di sisi luar bingkai. `Padding` bekerja berlawanan dari sumbu terdalam mengisi kedalaman bernapas sisi ketebalan dalam box ruang kosong elemen.
*   **`:hover`** : Fungsi penyaji interaktivitas dinamis. Ketika kita letakkan jari _pointer mouse_ di atas suatu benda tombol/teks namun tidak kita tekan, sekunder warna sorotan memudar berubah perlahan untuk menyajikan sentuhan isyarat respons mesin yang ramah ("Silahkan klik saya").
*   **`position: sticky`** : Menciptakan sekat panel navigasi (`<nav>`) super lekat ajaib yang menetap merekat pada plafon dinding _header_ tinggi (tidak lenyap tertelan bumi), sehingga para musafir tak kesulitan mencar tombol kembali kala berselancar gulir jauh berparagraf menelusuri ke bawah halaman.
*   **`@media (max-width: ...)`** : Modul Kueri *Responsive / Media Query*. Sensor cerdik agar saat website dicek lebar ukurannya dipaksa sempit mengerucut pada dimensi saku Handphone, maka susunan menyamping yang memanjang digeser menumpuk sejajar horizontal menyusun deret kolom panjang memanjang runtuh mendatar. Semua bagian tetap termuat terbaca presisi rapi menyesuaikan.
*   **`list-style-type` & `::before`** : Operasi bedah mahir menimpa spesifisitas standar CSS pada unsur item *bullet*. Kita memaksimalkan keping "::before" (menyelipkan ornamen buatan sebelum teks list utama terangkat) untuk menginjeksi bentuk elemen non-standar dan menciptakan simbol hiasan mahkota emas ekslusif " ✦ " mandiri merias senarai (*Unordered*) rincian *skil.html*.

## 3. JavaScript (JS) & Interaktivitas
File `script.js` pada struktur ini difokuskan sebagai cadangan dasar. 
Pada rilis tahapan tugas situs kali ini sengaja dibiarkan statis tak banyak memproses logika logika komputasi kerjawi matematika aktif berat, dikarenakan ragam pesona gawai sentuhan seperti animasi halus warna disaat bergeser maupun gerak gulir adaptif diakomodasi seutuhnya ditangani oleh arsitektur kekuatan keunggulan bawaan CSS.
