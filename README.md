# Aplikasi Perhitungan Hari

## **Deskripsi Program**
Aplikasi Perhitungan Hari adalah aplikasi berbasis Java Swing yang memungkinkan pengguna untuk menghitung jumlah hari dalam suatu bulan berdasarkan tahun tertentu. Aplikasi ini juga menawarkan fitur tambahan seperti menampilkan hari pertama dan terakhir dari bulan yang dipilih serta menghitung selisih hari antara dua tanggal.

---

## **Fitur Utama**
1. **Perhitungan Jumlah Hari**  
   - Pengguna dapat memilih bulan melalui **JComboBox** dan memasukkan tahun menggunakan **JSpinner** atau **JCalendar**.
   - Setelah menekan tombol **Hitung**, aplikasi akan menampilkan jumlah hari dalam bulan tersebut.

2. **Informasi Tambahan**  
   - Menampilkan hari pertama dan hari terakhir dari bulan yang dipilih.

3. **Perhitungan Tahun Kabisat**  
   - Aplikasi secara otomatis mempertimbangkan tahun kabisat dalam perhitungan jumlah hari pada bulan Februari.

4. **Penghitungan Selisih Hari** (Variasi)  
   - Aplikasi menyediakan fitur untuk menghitung selisih hari antara dua tanggal.

---

## **Logika Program**
1. Menggunakan API **LocalDate** untuk menghitung jumlah hari dalam bulan tertentu dan menentukan apakah tahun tersebut adalah tahun kabisat.
2. Memanfaatkan event handler untuk menangani interaksi pengguna seperti klik tombol atau perubahan nilai pada **JSpinner**.
3. Mengimplementasikan metode untuk menghitung hari pertama dan terakhir dari bulan yang dipilih.

---

## **Screen Shot**
![penghari](https://github.com/user-attachments/assets/579f744a-998b-4a09-9273-4a2185a9c00d)
