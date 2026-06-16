# TUGAS MATA KULIAH STATISTIKA DAN PROBABILITAS : ANALISIS REGRESI
Nama : Zaskia Dian Amanda 
Nim : F5512510031
Kelas : Teknik Informatika A Angkatan 2025 

# IDENTITAS DATASET
Judul Analisis     : Analisis Regresi Linear Produksi Perikanan Tangkap Laut Indonesia
Nama Dataset       : Panel Data Perikanan Indonesia 2019-2024
Nama File          : fix.panel data perikanan 2019-2024.xlsx
Link File          : https://docs.google.com/spreadsheets/d/1jvLY5h10XNeN6CJtAmFzR0Cp9Sofmgu9/edit?usp=sharing
Sumber Dataset     : Badan Pusat Statistik (BPS) & Kementerian Kelautan dan Perikanan (KKP)
Jenis Data         : Data panel produksi perikanan tangkap laut per provinsi
Studi Kasus        : Analisis produksi perikanan tangkap Indonesia berdasarkan tren tahun, jumlah nelayan, jumlah kapal, dan ukuran kapal
Metode             : Regresi Linear Berganda
Variabel Target Y  : Produksi Perikanan Tangkap Laut (Ton)
Variabel X         : Tahun, Provinsi, Jumlah Nelayan, Jumlah Kapal Total, dan Ukuran Kapal (GT)

# KESIMPULAM HASIL ANALISIS

Penelitian ini menganalisis produksi perikanan tangkap laut Indonesia menggunakan metode regresi linear berganda dengan variabel independen berupa tahun, jumlah nelayan, jumlah kapal, dan ukuran kapal (GT), serta variabel dependen berupa total produksi perikanan tangkap laut dalam satuan ton.

Hasil evaluasi model menunjukkan nilai R² sebesar 0.6778, yang berarti model mampu menjelaskan 67.78% variasi produksi perikanan tangkap laut di Indonesia. Sementara itu, nilai RMSE sebesar 80.851 ton menunjukkan rata-rata selisih antara nilai prediksi dan nilai aktual, yang cukup wajar mengingat terdapat perbedaan produksi yang sangat besar antar provinsi di Indonesia.

Berdasarkan analisis korelasi, variabel jumlah nelayan memiliki korelasi paling kuat terhadap produksi perikanan dengan nilai 0.74, diikuti oleh jumlah kapal dengan nilai 0.56. Hal ini menunjukkan bahwa semakin banyak nelayan dan kapal yang beroperasi, semakin tinggi produksi perikanan yang dihasilkan. Sebaliknya, variabel tahun dan ukuran kapal menunjukkan korelasi yang sangat lemah terhadap produksi perikanan.

Dari sisi tren, produksi perikanan tangkap Indonesia mengalami peningkatan dari tahun 2019 hingga mencapai puncaknya pada tahun 2023, kemudian mengalami penurunan pada tahun 2024. Penurunan ini perlu mendapat perhatian lebih lanjut dari pemangku kebijakan sektor perikanan.

Secara keseluruhan, model regresi linear yang dibangun cukup memadai untuk memprediksi produksi perikanan tangkap Indonesia. Namun demikian, terdapat sekitar 32% faktor lain yang belum tercakup dalam model ini, seperti kondisi cuaca, kebijakan penangkapan ikan, dan kondisi ekosistem laut, yang turut mempengaruhi produksi perikanan tangkap di Indonesia.
