# gamezone_data_cleaning
Cleaning sales data using Excel

Langkah-langkah pembersihan data yang akan dilakukan yaitu:
1. Change Date Format
   Format tanggal yang digunakan pada dataset ini tidak konsisten, maka akan digunakan formula berikut untuk menyeragamkan tipe datanya
   '''
   DATE(YEAR(serial_number),MONTH(serial_number),DAY(serial_number)
   '''
3. Handle Value Error
4. Fix Inconsistent Spelling
5. Handle Blank Cells
6. Remove Duplicate Value
