# Catatan Belajar Excel 5

## 1. Membuat Grafik atau Chart

Grafik atau chart digunakan untuk menampilkan data dalam bentuk visual agar lebih mudah dipahami, dibandingkan hanya melihat angka dalam tabel. Dengan grafik, pola tren, perbandingan, dan distribusi data bisa lebih cepat dianalisis.

### **Langkah-langkah membuat grafik di Excel:**
1. **Blok data** yang ingin dijadikan grafik, termasuk judul kolomnya agar lebih mudah dipahami.
2. Klik tab **Insert**.
3. Pada grup **Charts**, pilih jenis grafik yang sesuai dengan data yang dimiliki.
4. Jika bingung memilih jenis grafik yang cocok, gunakan **Recommended Charts** agar Excel memberikan rekomendasi grafik yang paling sesuai berdasarkan pola data yang dipilih.
5. Setelah memilih jenis grafik, Excel akan langsung membuat grafik berdasarkan data yang telah diblok.
6. Gunakan tab **Chart Tools** untuk menyesuaikan tampilan grafik, seperti mengubah warna, menambahkan label data, mengedit judul grafik, dan lain sebagainya.

### **Jenis-jenis grafik di Excel:**
- **Column Chart (Diagram Batang Vertikal):** Cocok untuk membandingkan nilai di beberapa kategori.
- **Bar Chart (Diagram Batang Horizontal):** Digunakan ketika label kategori panjang atau lebih mudah dibaca dalam format horizontal.
- **Line Chart (Diagram Garis):** Berguna untuk menampilkan tren data dari waktu ke waktu.
- **Pie Chart (Diagram Lingkaran):** Menunjukkan proporsi masing-masing bagian terhadap keseluruhan.
- **Scatter Plot (Diagram Titik):** Cocok untuk melihat hubungan antara dua variabel.
- **Area Chart:** Mirip dengan line chart tetapi dengan area di bawah garis yang diisi warna untuk menunjukkan volume data.

> **Catatan:** Pastikan memilih jenis grafik yang sesuai agar data lebih mudah dipahami oleh pengguna.

---

## 2. Filtering dan Conditional Formatting

### a) **Filtering (Menyaring Data)**

Filtering adalah fitur Excel yang memungkinkan kita untuk menyaring dan menampilkan hanya data yang diperlukan, sementara data lainnya tetap ada tetapi tidak terlihat.

### **Cara menggunakan Filtering:**
1. **Blok data** yang ingin difilter.
2. Klik tab **Home**.
3. Pilih **Sort & Filter**, lalu klik **Filter**.
4. Tanda panah kecil akan muncul di setiap judul kolom, yang menandakan bahwa filter telah aktif.

### **Fitur Filtering:**
- **Sort A to Z**: Mengurutkan data dari yang terkecil ke terbesar (misalnya urutan abjad A-Z atau angka dari kecil ke besar).
- **Sort Z to A**: Mengurutkan data dari yang terbesar ke terkecil.
- **Sort by Color**: Jika sel memiliki warna latar belakang yang berbeda, kita bisa mengurutkan atau menyaring berdasarkan warna tersebut.
- **Filter berdasarkan kategori**: Dapat memilih kategori tertentu dengan mencentang atau menghapus centang pada kategori yang tersedia.
  - Contoh: Jika memiliki data jenis kelamin, dan hanya ingin menampilkan data laki-laki, cukup hapus centang pada "Perempuan".
- **Filter berdasarkan angka**: Bisa memilih kondisi seperti:
  - **Greater Than** (Lebih besar dari...)
  - **Less Than** (Kurang dari...)
  - **Equal To** (Sama dengan...)
  - **Between** (Di antara dua nilai tertentu)
  - **Top 10** (Menampilkan data tertinggi)
- **Filter berdasarkan teks**: Bisa digunakan untuk mencari kata tertentu dalam sebuah kolom, seperti hanya menampilkan data yang mengandung kata "Lulus".

### **Keuntungan menggunakan Filtering:**
✔ Memudahkan analisis data dengan hanya menampilkan informasi yang relevan.
✔ Menghemat waktu dalam mencari data spesifik dalam tabel besar.
✔ Dapat digunakan bersamaan dengan fitur sorting untuk menyusun data dengan lebih rapi.

---

### b) **Conditional Formatting (Pewarnaan Otomatis)**

**Conditional Formatting** adalah fitur yang memungkinkan kita memberikan warna secara otomatis pada sel berdasarkan aturan tertentu. Ini sangat berguna untuk menyoroti data penting, mendeteksi tren, atau mengidentifikasi nilai ekstrim dalam dataset.

### **Cara menggunakan Conditional Formatting:**
1. **Blok sel** yang ingin diberi warna otomatis.
2. Klik tab **Home**.
3. Pilih **Conditional Formatting**.
4. Pilih aturan yang sesuai:
   - **Highlight Cells Rules → Equal To**: Misalnya, "Laki-laki" diberi warna biru dan "Perempuan" diberi warna pink.
   - **Greater Than / Less Than**: Misalnya, angka di atas 80 diberi warna hijau.
   - **Top/Bottom Rules**: Misalnya, menyoroti 10 nilai tertinggi dalam dataset.
   - **Data Bars**: Memberikan bar visual yang proporsional terhadap angka dalam sel.
   - **Color Scales**: Mewarnai data dengan gradasi berdasarkan nilai tertinggi dan terendah.
   - **Icon Sets**: Menampilkan simbol seperti panah naik/turun atau bintang untuk menunjukkan tren.

### **Contoh Penggunaan Conditional Formatting:**
✔ **Menandai nilai tinggi dan rendah:** Misalnya, nilai ujian di atas 90 diberi warna hijau, sedangkan di bawah 60 diberi warna merah.
✔ **Mewarnai kategori berbeda:** Misalnya, data pelanggan VIP diberi warna emas.
✔ **Menyoroti duplikasi data:** Berguna untuk menemukan data yang sama dalam satu kolom.
✔ **Menandai tugas yang overdue:** Jika tanggal jatuh tempo sudah lewat dari hari ini, maka sel akan berwarna merah otomatis.

> **Catatan:** Fitur ini dapat dikustomisasi lebih lanjut dengan menggunakan **New Rule** di menu Conditional Formatting.

---

Dengan memahami cara membuat grafik, menyaring data, dan menggunakan conditional formatting, kita bisa menganalisis data lebih cepat dan membuat tampilan lebih menarik serta mudah dipahami.