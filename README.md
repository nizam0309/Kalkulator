# Kalkulator
Ini adalah aplikasi kalkulator sederhana yang dibangun menggunakan HTML, CSS, dan JavaScript. Kalkulator ini memungkinkan pengguna untuk melakukan operasi matematika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian.

Fitur
Desain Responsif: Menggunakan flexbox dan grid layout untuk memastikan kalkulator terlihat baik di berbagai ukuran layar.
Input Angka dan Operator: Pengguna dapat memasukkan angka dan operator matematika menggunakan tombol yang tersedia.
Hasil Perhitungan: Setelah pengguna mengetikkan ekspresi matematika, tombol "=" akan menampilkan hasil perhitungan.
Clear dan Backspace: Tombol AC untuk menghapus seluruh input dan tombol C untuk menghapus satu karakter terakhir.

Struktur File
1.HTML: Bagian struktur dasar dari kalkulator, dengan tombol untuk angka dan operator.
2.CSS: Digunakan untuk memberikan gaya visual, seperti warna latar belakang, tata letak tombol, dan font.
3.JavaScript: Digunakan untuk mengelola interaksi pengguna dan menghitung hasil perhitungan.

Penjelasan Kode

HTML:
Kalkulator dibangun di dalam elemen <div class="calculator">.
Input teks untuk menampilkan angka dan hasil perhitungan berada di dalam elemen <input type="text" id="display">.
Tombol-tombol kalkulator (angka dan operator) dibangun menggunakan elemen <button> dengan fungsi onclick yang memanggil fungsi JavaScript untuk menambahkan nilai ke layar atau menghitung hasilnya.

CSS:

Mengatur tampilan kalkulator agar terlihat lebih modern dengan latar belakang biru, dan elemen kalkulator berwarna merah dengan sudut membulat.
Tombol-tombol menggunakan desain grid untuk memastikan tombol-tombolnya tersusun rapi.
Mengatur gaya elemen input agar tampil lebih besar dan nyaman untuk digunakan.
JavaScript:

appendToDisplay(value): Menambahkan angka atau operator ke layar kalkulator.
ClearDisplay(): Menghapus seluruh input.
backspace(): Menghapus satu karakter terakhir dari layar.
calculateResult(): Menghitung hasil dari ekspresi yang dimasukkan menggunakan fungsi eval(), dan menampilkan hasilnya di layar kalkulator. Jika ada kesalahan, menampilkan "Error Boss" di layar.

Cara Menggunakan

1.Buka file HTML di browser.
2.Gunakan tombol angka dan operator untuk memasukkan ekspresi matematika.
3.Tekan tombol "=" untuk menghitung hasilnya.
4.Gunakan tombol "AC" untuk menghapus semua input atau tombol "C" untuk menghapus satu karakter terakhir.

Catatan

Keamanan: Fungsi eval() digunakan untuk menghitung ekspresi, namun perlu hati-hati karena fungsi ini dapat mengevaluasi kode JavaScript yang tidak aman. Untuk aplikasi lebih lanjut, lebih baik menggunakan metode lain untuk evaluasi ekspresi yang lebih aman.

Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan lakukan perubahan atau perbaikan sesuai kebutuhan Anda.
