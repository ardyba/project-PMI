# **Business Intelligence Model for PMI Emergency Warehouse**

## **Backgrounds**
Palang Merah Indonesia (PMI) adalah sebuah organisasi nasional yang bergerak dalam bidang sosial kemanusiaan. Pada masa pandemi Covid-19 ini, sejak awal PMI telah membangun 7 gudang darurat serta 4 gudang tambahan. Tujuan dibangunnya gudang ini untuk dapat menyimpan, mendistribusikan segala macam logistik, dan tentunya untuk mendukung operasi percepatan penanganan Covid-19. Untuk dapat memaksimalkan aktivitas logistik PMI ini, diperlukan sebuah Business Intelligence model untuk membantu pemantauan dan analisa aktivitas gudang darurat. Untuk itu, diberikan suatu dataset yang berisi beberapa informasi terkait gudang darurat tersebut untuk diolah dan dianalisa.


## **Objectives**
Berdasarkan data-data yang dihimpun, berikut adalah permasalahan-permasalahan yang hendak dipenuhi/dijawab:
- Bagaimana cara kita melakukan monitoring terhadap stok barang masuk dan keluar di PMI?
- Bagaimana distribusi stok barang yang masuk dan keluar di tiap provinsi di Indonesia?
- Apa jenis barang yang paling banyak dikeluarkan oleh atau dikirim ke PMI?
- Apakah setiap gudang menerima dan mengeluarkan jenis barang yang sama?



## **Exploratory Data Analysis (EDA)**
- Mencari unique value pada data dan menciptakan kategori baru yang relevan (data definition & validation)
Hal ini dilakukan untuk melihat apakah data yang unik memiliki kemiripan. Jika memiliki kemiripan, data-data tersebut dapat dikelompokkan menjadi kategori-kategori yang unik. Hal ini akan membantu menyederhanakan seseorang untuk mengerti terkait persoalan yang dapat timbul.

![image](https://user-images.githubusercontent.com/55777261/167309451-02c80c0d-09f9-4cb2-90c3-431659b3f357.png)


- Meninjau data harian dan bulanan aktivitas gudang
Untuk tetap memberikan insight yang detail, data-data tetap harus ditinjau berdasarkan unique value dari data mentah atau berdasarkan kategori yang kita ciptakan.

![image](https://user-images.githubusercontent.com/55777261/167309564-dbf29303-64ee-43ba-bdf1-eedee919e1e2.png)


- Meninjau intensitas donor berdasarkan letak geografisnya
Data stok gudang yang diberikan PMI menyertakan nama-nama geografis dari cabang PMI. Selain melakukan pengolahan agar nama-nama geografis yang melekat di kolom nama data PMI, perlu dilakukan visualisasi agar presentasi menjadi jauh lebih mudah dipahami. 

![image](https://user-images.githubusercontent.com/55777261/167309577-1273404c-7e89-4a03-8b91-e09772cdedf5.png)


- Melakukan pencarian nilai-nilai ekstrim
Terakhir, untuk memberikan insights terkait stok yang berlebih atau kurang, dapat pula dihasilkan tabel/visualisasi yang menampilkan rangking dari jenis stok terbanyak dan terminim dari data stok gudang PMI. Selain stok gudang, termasuk pula dapat dilakukan pencarian barang yang paling sering diterima PMI dari donor, barang yang paling sering dikirimkan PMI sebagai donor, dan lain sebagainya.



## **Dashboard**
- Berikut hasil dashboard yang telah dibuat menggunakan Tableau

![image](https://user-images.githubusercontent.com/55777261/167309597-4f7e3fbe-ebdb-4dda-a0ad-ae835bef12a4.png)

- [Link Dashboard](https://public.tableau.com/app/profile/ardy.insan.hakim/viz/PMI-Dashboard/Dashboard1)
