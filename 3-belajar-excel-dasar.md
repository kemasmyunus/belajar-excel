## Catatan Belajar Excel

### 1. Menggunakan Excel untuk Mengolah Data Teks dan Angka
Excel tidak hanya digunakan untuk angka, tetapi juga bisa mengoperasikan data berbentuk teks atau kata. Salah satu cara utama dalam mengolah data adalah dengan menggunakan rumus.

### 2. Contoh Tabel Data
Berikut contoh tabel data yang dapat diolah menggunakan Excel:

| A        | B              | C            |
|----------|---------------|-------------|
| 1        | Nama Buah     | Stok Tersisa | Harga Satuan |
| 2        | Apel         | 10          | 10000 |
| 3        | Jeruk        | 20          | 5000  |
| 4        | Anggur       | 25          | 20000 |
| 5        | Melon        | 5           | 14000 |
| 6        | Semangka     | 10          | 6000  |

### 3. Dasar Penggunaan Rumus
- **Setiap rumus di Excel diawali dengan tanda `=`**.
- Misalnya, untuk menjumlahkan dua sel:
  ```excel
  =C4 + C5
  ```
  Jika nilai dalam C4 dan C5 berubah, hasilnya akan diperbarui secara otomatis.

- **Operasi dasar dalam Excel**:
  - Penjumlahan: `=C4 + C5`
  - Pengurangan: `=C4 - C5`
  - Perkalian: `=C4 * C5`
  - Pembagian: `=C4 / C5`

### 4. Rumus Sederhana yang Harus Diketahui
- **Mengedit Rumus**: Klik dua kali pada sel atau tekan `F2`.
- **Menjumlahkan Banyak Data**:
  ```excel
  =SUM(B4, B6, B8)  
  =SUM(B4:B8)  
  ```
- **Menghitung Rata-Rata Stok Perbulan**:
  ```excel
  =AVERAGE(B4, B6, B8)  
  =AVERAGE(B4:B8)  
  ```
- **Menghitung Banyaknya Data Berbentuk Angka**:
  ```excel
  =COUNT(B4:B8)  
  ```
  (Menghitung jumlah data angka dalam rentang tertentu, bukan menjumlahkan nilainya.)
- **Menghitung Banyaknya Data Berbentuk Teks**:
  ```excel
  =COUNTA(A4:A8)  
  ```
  (Menghitung jumlah sel yang berisi teks dalam rentang tertentu.)
- **Mencari Nilai Tertinggi**:
  ```excel
  =MAX(C4:C8)  
  ```
  (Mencari nilai tertinggi dalam suatu rentang data.)
- **Mencari Nilai Terendah**:
  ```excel
  =MIN(C4:C8)  
  ```
  (Mencari nilai terendah dalam suatu rentang data.)

Dengan memahami konsep dasar ini, pengguna dapat memanfaatkan Excel untuk mengelola data secara lebih efisien dan akurat.