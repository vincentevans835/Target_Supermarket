## Analisis Supermarket
#### Latar Belakang: Melakukan analisis terhadap efektivitas promosi suatu supermarket dan bagaiman penerimaan nya oleh pelanggan
Sumber Data: [Supermarket Customers.csv](https://github.com/vincentevans835/Target_Supermarket/blob/main/Supermarket%20Customers.csv)  
Tableu: [Link](https://public.tableau.com/views/Capstone_17067620251360/Capstone2?:language=en-GB&:display_count=n&:origin=viz_share_link)




### Masalah  
1.Bagaimana Tingkat Penerimaan Konsumen terhadap Promosi di Supermarket?  
2.Profil dan Karakteristik Pelanggan  
3.Pengaruh Pendapatan terhadap Total Pengeluaran Produk  
4.Lebih mengutamakan promosi di toko fisik atau platform online  
5.Product apa yang yang di harus diutamakan untuk dipromosikan

### Goals  
1.Mengukur sejauh mana konsumen merespon dan menerima berbagai jenis promosi yang ditawarkan oleh supermarket  
2.Bagaimana profil dan karakteristik pelanggan (usia, pendidikan, status perkawinan, pendapatan) berhubungan dengan kecenderungan partisipasi dalam program pemasaran atau respons terhadap promosi  
3.Sejauh mana pendapatan pelanggan memengaruhi total pengeluaran pada berbagai kategori produk (anggur, buah-buahan, daging, ikan, produk-manis, emas)?  
4.Bagaimana pola perilaku pembelian konsumen di toko fisik dan platform online berkontribusi terhadap keputusan promosi yang tepat?  
5.Prioritaskan promosi untuk produk yang kurang sering dibeli oleh konsumen, dengan tujuan meningkatkan kesadaran dan penjualan produk tersebut.

### Setiap baris mewakili riwayat belanja 1 pelanggan dalam periode 2 tahun

### Data yang digunakan untuk analisis:  
1.Income : Pendapatan pelanggan pertahun  
2.Year_Birth : tahun lahir pelanggan. nanti akan dibuat kolom baru umur  
3.AcceptedCmp1,AcceptedCmp2,AcceptedCmp3,AcceptedCmp4,AcceptedCmp5,Response: Apakah pelanggan menerima promosi atau tidak, 0 itu tidak, 1 itu iya. nanti akana digabungkan menjadi satu kolom yang menandakan pernah atau tidak menerima promosi  
4.NumWebPurchases:Jumlah frekuensi belanja di website per pelanggan  
5.NumStorePurchase:Jumlah frekuensi belanja di toko per pelanggan  


