# Penjualan Mobil Bekas - Objektif:

1. Design Database penjualan mobil bekas yang menyimpan data user, data mobil bekas, data kota, data iklan dan data bid 
2. Menambahkan data dummy ke dalam tabel
3. Melakukan backup database
4. Melakukan query transaksional 
5. melakukan query analytical


# Business Rules:
1. Setiap user dapat menawarkan lebih dari satu produk mobil bekasnya.
2. user wajib mengisi nama, kontak, dan domisili lokasi.
3. User menawarkan produknya melalui iklan yang berisikan judul, detail informasi produk yang ditawarkan, serta kontak penjual.
4. Detail informasi dari iklan tersebut adalah sebagai berrikut:
   - merek mobil
   - Model
   - Jenis body mobil
   - Tipe mobil: manual atau automatic
   - Tahun pembuatan mobil
5. Setiap user bisa mencari mobil yg ditawarkan berdasarkan lokasi user penjual, merk mobil, dan jenis body mobil.
6. Jika calon pembeli tertarik terhadap sebuah mobil, ia dapat menawar (bid) harga produk.

# Design Database:
