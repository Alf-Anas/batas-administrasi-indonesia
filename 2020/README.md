# batas-administrasi-indonesia
Batas administrasi indonesia dalam format ShapeFile(SHP) dan GeoJSON.

Batas Administrasi yang meliputi :
- Batas Provinsi (SHP, GeoJSON, KML)
- Batas Kabupaten / Kota (SHP)
- Batas Kecamatan (SHP)
- Batas Desa (SHP)

Data ini diekstrak dari portal GIS Kemendagri https://gis.dukcapil.kemendagri.go.id/arcgis/home/
Data tersebut merupakan data paling baru yang dapat diambil pada saat repo ini dibuat (data 2018Semester1).

Untuk data provinsi memiliki ukuran file yang lebih kecil namun dengan ketelitian yang kurang baik dibandingkan dengan data batas kabupaten dan kecamatan, perbandingan dapat dilihat pada gambar Banding.png, namun jika digunakan hanya untuk visualisasi data secara keseluruhan, maka data tersebut masih cukup baik. 

Data Kabupaten/Kota (514 Kab dan Kota) memiliki ketelitian yang hampir sama dengan data Kecamatan, data tersebut cukup besar sehingga tidak dapat diupload disini, sehingga diupload melalui google drive di link di bawah.

Data Kecamatan dengan total 7207 Kecamatan di seluruh Indonesia, dan 16 objek hutan dan danau.

Data Desa Seluruh Indonesia yang masih belum seluruhnya sepakat. 
Data Desa di extract dari portal GIS PPBW BIG https://portal.ina-sdi.or.id/gis/rest/services/PPBW/BATASWILAYAH_10K_ADMINISTRASI_AR_KELDESA/MapServer 
Data ini masih data kotor, sehingga ada batas desa yang sudah definitif, ada juga yang masih indikatif, dan batas desa yang tidak terdefinisi ataupun tidak disepakati antar desa. 
