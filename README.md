# Laporan Proyek Machine Learning - Fawzan Ibnu Fajar

# **Business Understanding**

Business Understanding berisi mengenai pemaparan tema melalui sudut pandang objektif bisnis meliputi Latar Belakang Masalah, Identifikasi Masalah, Metode atau Pendekatan Penyelesaian Masalah, Tujuan Teknis dan Kriteria Kesuksesan. Setelah seluruh pemaparan tersebut disampaikan terdapat Timeline riset guna memberi tenggat waktu dalam mencapai hasil akhir riset.

#**Latar Belakang**

Diskriminasi gender dalam berbagai hal di kehidupan bermasyarakat
menimbulkan perbedaan capaian pembangunan antara laki-laki dan
perempuan. Jepang memiliki ekonomi terbesar ketiga di dunia berdasarkan produk domestik bruto (PDB). Meskipun demikian, ada kesenjangan upah gender yang signifikan di Jepang. Menurut Organisation for Economic Co-operation and Development (OECD) atau Organisasi untuk Kerja Sama dan Pembangunan Ekonomi, perempuan yang bekerja di Jepang memperoleh penghasilan rata-rata 22% lebih rendah daripada laki-laki pada tahun 2020. Lalu, Laporan Kesenjangan Gender Global Forum Ekonomi Dunia 2021 menempatkan Jepang di peringkat 120 dari 156 negara. Tujuan penelitian ini, yaitu untuk memprediksi upaya apa saja yang dapat dilakukan untuk menurunkan kesenjangan penghasilan perempuan di Jepang menggunakan model analisis forecasting.

# **Identifikasi Masalah**

Berikut merupakan identifikasi masalah dalam awal rancangan pembuatan riset Gender Equality In Japan:

1. Kesenjangan penghasilan sebesar 22% yang dialami pekerja perempuan di Jepang
2. Jepang menduduki peringkat 120 dari total 156 negara dengan kesenjangan gaji gender terbesar di dunia dari data the World Economic Forum’s pada tahun 2021.
3. Pengaruh tenaga kerja perempuan dinilai berhubungan erat dengan kesenjangan penghasilan yang terjadi di Jepang, sehingga membutuhkan persentase peningkatkan jumlah perempuan yang masuk ke dunia kerja.


Rumusan masalah diatas dapat diolah kembali untuk digunakan dalam menemukan hasil riset apa yang ingin diketahui. Berikut adalah wisdom yang ingin dicapai saat melakukan riset Gender Equality In Jepang:

1. Mengetahui persentase tingkat kesenjangan pendapatan gender perempuan di Jepang menurut OECD
2. Mengetahui cara penurunan tingkat kesenjangan pendapatan gender di Jepang
3. Mengetahui berapa persentasi dibutuhkannya peningkatkan jumlah perempuan yang masuk ke dunia kerja sehingga kesenjangan penghasilan gender di Jepang dapat menurun
4. Sehingga selanjutnya dapat merancang suatu solusi yang tepat guna memecahkan permasalahan gender pada 3 sektor diatas.

# **Metode/ Pendekatan Penyelesaian Masalah**

Dalam riset Gender Equality In Japan saya menggunakan metode Regresi Linier. Metode ini akan digunakan untuk menganalisis berapa rentang 'Gap' gaji berdasarkan gender di Jepang serta prediksi apa yang harus ditingkatkan untuk meminimalisir 'Gap' Gaji tersebut.

Saya menggunakan data dari https://data.oecd.org sebagai acuan awal informasi riset kedepannya.

# **Data Understanding**

Pada mini riset ini, saya menggunakan dataset yang bersumber dari https://data.oecd.org. Berikut beberapa data yang akan saya gunakan :

* Location             : Negara Asal
* Indicator            : Alat Ukur Penelitian
* Subject              : Bagian Penelitian
* Measure              : Ukuran Penelitian
* Frequency            : Kekerapan Jumlah 
* Time                 : Tahun Pemrosesan Data
* Value                : Persentase Gap Gaji berdasarkan Gender
* JAP/JPN              : Data Gender Equality di Negara Jepang
* Average Wage         : Rata-rata Gaji
* Female Labour        : Jumlah Ketenagakerjaan Perempuan
* Total Labour         : Jumlah Ketenagakerjaan
* Female Labour Ratio  : Rasio Ketenagakerjaan Perempuan

Jumlah row sebanyak 1245 baris
