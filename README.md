<h1 style="font-weight: bold;">
  LAPORAN PRAKTIKUM 2 JARINGAN KOMPUTER
</h1 >
<hr>
<h2>Sharing File with LAN Cable</h2>

<h3> Alat dan Bahan </h3> 
<h4>Kabel UTP</h4>
 <img  src="kabel UTP.jpeg" alt="cable"  width="300px">
 

<br>
 <h4>2 Device</h4>
 <img  src="20.jpeg" alt="Laptop"  width="300px">

<hr>

<h2>Langkah-Langkah Konfigurasi</h2>

<ol>
  <h2> <li>Laptop 1</li></h2>
  <ul>
    <li>Buat folder baru, contoh JARKOM</li>
    <img  src="1.png" alt="cable"  width="300px">
    <li>Klik kanan pada folder, cari "Give access to" lalu pilih "specific poeple..."</li>
    <img  src="2.png" alt="cable"  width="300px">
    <li>Agar folder dapat diakses siapapun, pilih "everyone"</li>
    <img  src="3.png" alt="cable"  width="300px">
    <li>Lalu ubah permission level dari "Read" menjadi "Read/Write" agar siapapun dapat mengubah isi folder</li>
    <img  src="4.png" alt="cable"  width="300px">
    <li>Kemudian klik kanan lagi pada folder, lalu propertis dan ke Sharing pilih bagian "Advenced Sharing..."</li>
    <img  src="5.png" alt="cable"  width="300px">
    <li>Lalu centang  bagian "Share this folder"</li>
    <img  src="6.png" alt="cable"  width="300px">
    <li>Colok kabel UTP ke masing-masing laptop</li>
    <img  src="connect kabel.jpeg" alt="cable"  width="200px">
    <li>Buka control panel, pada Network and Internet di klik </li>
    <img  src="7.png" alt="cable"  width="300px">
    <li>Lalu klik bagian "change advanced sharing setting"</li>
    <img  src="8.png" alt="cable"  width="300px">
    <li>Pada bagian Public Network, centang bagian network discovery dan file and printer sharing
    Pada bagian All networks, aktifkan "public folder sharing" dan non-aktifkan "password protected sharing"
    Hal ini berfungsi untuk mengaktifkan permission laptop agar bisa kita berbagi file dengan all devices yang terhubung</li>
    <img  src="9.png" alt="cable"  width="300px">
    <li>Kembali ke control panel, klik bagian "Ethernet"</li>
    <img  src="10.png" alt="cable"  width="300px">
    <li>Cari Internet Protocol Version 4, lalu klik 2 kali</li>
    <img  src="11.png" alt="cable"  width="300px">
    <li>Centang Use the following IP address, dan ketik IP address dan default gatewaynya
    IP address berfungsi sebagai alamat laptop dan default gateway berfungsi sebagai alamat IP laptop yang terhubung</li>
    <img  src="12.png" alt="cable"  width="300px">
  </ul>

  <hr>
  <h2><li>Laptop 2</li></h2>
  <ul>
    <li>Buka control panel, lalu klik Network and Internet</li>
    <img  src="13.png" alt="cable"  width="300px">
    <li>Lalu klik bagian change advanced sharing setting</li>
    <img  src="14.png" alt="cable"  width="300px">
    <li>Sama seperti langkah ke-9</li>
    <img  src="9.png" alt="cable"  width="300px">
    <li>Lalu kembali ke control panel klik ethernet, lalu cari IPV 4 dan klik 2 kali</li>
    <img  src="15.jpeg" alt="cable"  width="300px">
    <li>Ketik IP address yang sama dengan IP Laptop 1, tapi bedakan angka paling belakang</li>
    <img  src="16.jpeg" alt="cable"  width="300px">
    <li>Kembali ke dekstop, tekan "Windows+R" dan ketik cmd
    Lalu ketik ping IP Laptop 1 tadi. Hal ini berfungsi untuk mengetahui apakah Laptop 2 terhubung atau tidak ke Laptop 1</li>
    <img  src="17.jpeg" alt="cable"  width="300px">
    <li>Buka File eksplorer, lalu scroll kebawah dan klik Network, lalu ketik path dari folder yang di sharing Laptop 1</li>
    <img  src="18.png" alt="cable"  width="300px">
    <li>Sekarang folder sudah bisa di lihat dan di edit oleh Laptop 2</li>
    <img  src="19.png" alt="cable"  width="300px">
    <img  src="20.jpeg" alt="cable"  width="300px">
  </ul>
</ol>

<hr>
<h2>Analisis Percobaan</h2>
<p>Berdasarkan hasil percobaan, penggunaan kabel LAN dengan konfigurasi IP Address IPv4 memungkinkan komunikasi langsung antar komputer tanpa memerlukan koneksi internet. Kecepatan transfer data yang tinggi menjadi keunggulan utama dibandingkan metode lain seperti penggunaan flash drive atau transfer melalui jaringan Wi-Fi yang lebih lambat dan rentan terhadap gangguan sinyal.</p>

<hr>

<h2>Kesimpulan</h2>
<p>Praktikum ini membuktikan bahwa transfer file antar komputer menggunakan kabel LAN dengan IP Address IPv4 adalah metode yang efisien dan stabil. Kecepatan tinggi dan keamanan menjadi keunggulan utama, meskipun terdapat keterbatasan dalam jangkauan dan fleksibilitas. Metode ini ideal digunakan dalam lingkungan jaringan lokal yang membutuhkan kecepatan dan keamanan tanpa perlu koneksi internet.</p>
