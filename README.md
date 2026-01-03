# gamezone_data_cleaning
Cleaning sales data using Excel

Langkah-langkah pembersihan data yang akan dilakukan yaitu:
1. Change Date Format
   Format tanggal yang digunakan pada dataset ini tidak konsisten, maka akan digunakan formula berikut untuk menyeragamkan tipe datanya
    ```
    DATE(YEAR(serial_number),MONTH(serial_number),DAY(serial_number)
    ```
3. Handle Value Error
   Mengatasi value yang error menggunakan ```IFFERROR```
5. Fix Inconsistent Spelling
7. Handle Blank Cells
8. Remove Duplicate Values
   Pada dataset ini kolom ORDER_ID tidak boleh duplikat. Mengecek duplikat values digunakan pivot table, dan ternyata terdapat 145 ORDER_ID yang duplikat.
   Untuk menghapus duplikat menggunakan cara: Data → Remove Duplicates
   <img width="1499" height="827" alt="image" src="https://github.com/user-attachments/assets/fb8561ca-c9da-4f0a-baf9-a656de0128ee" />

