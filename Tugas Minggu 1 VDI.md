# Tugas Minggu 1 Visualisasi Data dan Informasi - Review Jurnal
Nama: Randa Andriana Putra\
NIM: 122450083\
Kelas: RB

# Judul Jurnal: Making data visualization more efficient and effective: a survey
## Pendahuluan
Seiring berkembangnya zaman, data yang tersedia semakin banyak. Sehingga dibutuhkan suatu teknik dan metode yang tepat untuk mengolah data tersebut menjadi suatu cerita yang menarik dan visual yang baik. Maka dari itu, teknik visualisasi data sangatlah cocok untuk memproses banjir data tersebut agar memberikan gambaran umum yang baik tentang data tersebut dan memudahkan pengambilan kesimpulan hasil analisisnya.
## Pembahasan
Dalam jurnal ini dibahas 3 aspek utama agar visualisasi data yang dilakukan dapat menjadi lebih efektif dan mudah dipahami, yang pertama yaitu dengan memastikan spesifikasi visualisasi yang tepat, yang kedua pendekatan yang efisien untuk proses visualisasi, dan yang terakhir rekomendasi visualisasi data.
### Spesifikasi Visualisasi
Spesifikasi visualisasi adalah langkah awal untuk menentukan cara dan bagaimana sebuah data itu akan divisualisasikan, misalnya dimulai dari data tersebut diambil dari mananya, lalu diimport, setelahnya dimanipulasi (preprocessing), selanjutnya barulah diubah ke dalam bentuk visual.
Dalam visualisasi tentunya terdapat elemen penting, yaitu datanya itu sendiri, marks atau elemen visual misalnya batang, garis, titik, legenda (keterangan), dan warna serta juga pemetaannya yaitu menyambungkan data dengan elemen visual tersebut.

Tools atau software yang akan digunakan juga ditentukan dalam penentuan spesifikasi visualisasi di sini. Software untuk visualisasi banyak sekali, dan jika dibedakan berdasarkan kemudahan penggunaannya ada 4 yaitu:
1. Low-level language: Prefuse, Flare, Protvis, D3, Vega, Reactive Vega
2. High-level language: ggplot2, Vega-Lite, Altair, Echarts, VizQL, ZQL
3. GUI-based Tools (ini yang familiar dan biasa digunakan banyak orang): Tableu, Excel, Google Sheets, Microsoft Power BI, dan lainnya.
4. Underspecified Language: zenvisage, DeepEye, APT, SW, Eviza, Evizeon

### Pendekatan efisien untuk proses visualisasi
Dibahas 3 pendekatan yaitu:
1. Data asli yang langsung divisualisasikan secara cepat dan tepat.
2. Data perkiraan yang divisualisasikan karena menghemat sumber daya komputasi.
3. Progressive data visualization atau memvisualisasikan datanya secara progresif dan bertahap.

Contoh dari pendekatan yang pertama adalah Query Translation, dimana membutuhkan DBMS untuk membuat query yang dapat memvisualisasikan data. (data langsung divisualisasikan)
Contoh dari pendekatan yang kedua adalah AQP (Approximate Query Processing), cara kerjanya dengan menggunakan sebagian data yang merepresentasikan sehingga memberikan perkiraan visualisasi. Kelebihan pendekatan ini cepat dilakukan komputasinya, walaupun dengan mengorbankan sedikit kualitas visualisasi datanya.
Contoh dari pendekatan yang ketiga adalah Hierarchical Aggregation, cara kerjanya dengan membuat struktur hirarki dengan mengagregasi data dalam tingkatan yang berbeda seperti 
