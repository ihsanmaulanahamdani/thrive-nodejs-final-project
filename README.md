# NodeJs Marketplace Server

Buatkan server menggunakan ORM `Sequelize` dan Database `MySQL`

## Ketentuan
1. Gunakan fungsi `addColumn` untuk menambahkan column ke table
2. Tambahkan `seeder` Products untuk menambahkan 5 data product
3. Buat validasi untuk `Email` (format email dan unique email) dan `Password` (panjang minimal 6 karakter, minimal satu huruf kapital, minimal satu nomor dan satu symbol)
4. Authentication menggunakan `bcryptjs` dan `jsonwebtoken`
5. Authorization `SELLER` dan `BUYER` (tentukan privileges dari `SELLER` dan `BUYER`)
6. Buat Transaksi (gunakan `Sequelize Transaction` - Optional)
