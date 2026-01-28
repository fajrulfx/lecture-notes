# BAB I. Pengantar Fisika

**Fisika dan Mekanika Teknik TRM 1002**  
**Fajrul Falah, S.Si, M.Sc**

---

## 1. Definisi dan Filosofi Dasar

Apa itu fisika? Pertanyaan ini telah diajukan sejak zaman filsuf Yunani kuno. Secara etimologis, istilah fisika berakar dari kata Yunani *physikos* yang bermakna "alamiah". Dalam konteks akademis modern, fisika adalah cabang ilmu pengetahuan alam yang paling fundamental yang mempelajari sifat dasar materi (*matter*) dan energi (*energy*), serta interaksinya dalam ruang (*space*) dan waktu (*time*).

Jika kita membandingkannya dengan ilmu lain: biologi mempelajari kompleksitas kehidupan, kimia mempelajari reaksi antar zat, sementara fisika mempelajari fondasi dasar yang memungkinkan reaksi kimia dan kehidupan itu terjadi.

Cakupan studi fisika sangat luas, yang secara umum dapat dibagi menjadi tiga skala utama:

- **Skala Mikroskopis**: Dunia partikel sub-atom (proton, neutron, elektron, quark). Di sini berlaku hukum Mekanika Kuantum.
- **Skala Makroskopis**: Fenomena sehari-hari yang kita lihat (gerak mobil, aliran air). Di sini berlaku Mekanika Klasik Newton.
- **Skala Kosmik**: Struktur terbesar di alam semesta (bintang, galaksi, *black hole*). Di sini berlaku Teori Relativitas.

Fisika tidak hanya mendeskripsikan *apa* yang terjadi, melainkan juga menjelaskan *bagaimana* fenomena tersebut terjadi melalui hukum alam yang universal.

---

## 2. Pola Pikir Fisika

Salah satu hambatan siswa dalam belajar fisika adalah merasa materinya terlalu abstrak. Sebagai contoh, untuk sebuah kasus bola yang jatuh dari meja, seringkali muncul pertanyaan: *"Kenapa harus menghitung bola jatuh? Apa gunanya?"*

![Tangga Satuan](LECTURE%20NOTES_files/Image_001.jpg)

Jawabannya terletak pada pola pikir fisika, yaitu: **memecah masalah kompleks menjadi prinsip dasar sederhana.**

Dalam fisika, kasus bola yang jatuh akan memberi ruang untuk beberapa analisis: Mengapa bola jatuh ke bawah, bukan ke atas? Berapa lama waktu yang dibutuhkan sampai menyentuh lantai? Berapa kecepatan saat sampai di tanah? dan lain sebagainya. Sekilas ini seperti hal yang tidak penting, namun sebenarnya ini adalah hal yang sangat krusial dalam fisika.

**Mengapa ini penting?** Prinsip fisika bersifat universal. Hukum yang mengatur jatuhnya bola dari meja adalah hukum yang sama persis yang digunakan untuk sistem yang jauh lebih kompleks, seperti:

- Merancang jembatan yang kuat
- Perhitungan kekuatan untuk lift di dalam gedung
- dan lain sebagainya.

Dengan memahami mempelajari kasus sederhana, kita bisa menggunakan pemahamannya untuk menyelesaikan berbagai persoalan lain yang lebih besar.

---

## 3. Matematika sebagai Bahasa Fisika

Fisika ditulis dalam bahasa matematika. Persamaan matematika (atau rumus matematika) dalam fisika ini bukan untuk mempersulit, melainkan karena matematika adalah alat komunikasi yang paling presisi. Sebagai contoh, jika interaksi antara gaya dan benda dijelaskan dengan bahasa verbal, maka ia akan perlu ditulis:

> *"Jika sebuah gaya luar total didorongkan kepada sebuah benda yang memiliki massa inersia tertentu, maka benda tersebut akan mengalami perubahan kecepatan (percepatan) yang arahnya sama dengan gaya tersebut..."*
>
> (Terlalu panjang dan rawan salah tafsir).

Sementara itu, penulisan menggunakan bahasa matematika hanya membutuhkan 3 huruf saja, yaitu:

$$\vec{F} = m\vec{a}$$

Keunggulan menggunakan bahasa matematika dalam fisika antara lain:

- **Ringkas**: Menyederhanakan paragraf panjang menjadi beberapa simbol saja.
- **Presisi**: Menghilangkan ambiguitas makna kata.
- **Analitis**: Memudahkan proses analisis logika sebab-akibat dalam persamaan.

---

## 4. Ruang Lingkup Fisika

Fisika adalah ilmu empiris yang berbasis pada pengukuran (*measurement*). Itu berarti, fisika hanya berurusan dengan besaran fisik yang bisa diukur, baik melalui pengukuran langsung ataupun tidak langsung. Pengukuran langsung misalnya adalah yang terjadi ketika mengukur panjang meja dengan mistar, sementara pengukuran tidak langsung misalnya mengukur jari-jari atom lewat difraksi sinar-X.

Fisika tidak bisa mempelajari hal yang tidak bisa diukur (*non-measurable*). Itu berarti, segala sesuatu yang tidak memiliki besaran fisik dan subjektif berada di luar ranah fisika, seperti: perasaan, emosi, nilai estetika, metafisika, dan lain sebagainya.

---

## 5. Peran Fisika dalam Bidang Teknik

### 5.1 Landasan Perancangan

Dalam dunia teknik mesin, proses perancangan (*engineering design process*) adalah tahapan krusial di mana ide diubah menjadi produk nyata. Tanggung jawab utama dalam proses ini adalah menjamin bahwa produk tersebut berfungsi, aman, dan efisien *sebelum* diproduksi.

Di sinilah fisika berperan sebagai landasan utama. Sebuah rancangan tidak boleh hanya mengandalkan estetika visual (gambar 3D di CAD), tetapi setiap keputusan desain harus didasarkan pada analisis fisika yang dapat dipertanggungjawabkan:

- Mengapa poros ini diameternya harus 50mm? (Berdasarkan mekanika kekuatan material agar tidak patah saat menerima torsi/puntiran).
- Mengapa bentuk sirip pendingin harus seperti ini? (Berdasarkan perpindahan panas agar mesin tidak *overheat*).
- Apakah mekanisme ini akan macet saat bergerak cepat? (Berdasarkan kinematika & dinamika).

Tanpa perhitungan fisika, sebuah desain hanyalah gambar artistik, bukan produk rekayasa (*engineering product*) yang layak dan aman untuk diproduksi.

### 5.2 Validasi Simulasi dengan Fisika

Dalam perancangan modern, insinyur sering menggunakan perangkat lunak CAE (*Computer-Aided Engineering*) seperti FEA dan CFD untuk mensimulasikan kinerja produk secara virtual.

Namun, ketergantungan pada *software* tanpa pemahaman dasar dapat menyebabkan kesalahan fatal yang dikenal sebagai **"Garbage In, Garbage Out"**:

- Komputer hanyalah alat hitung. Jika input parameter fisik yang diberikan salah (misalnya tumpuan gaya tidak realistis), komputer tetap akan memprosesnya dan menghasilkan grafik yang hanya terlihat meyakinkan secara visual, namun nilainya keliru.
- Hasil simulasi yang keliru ini berbahaya jika langsung dijadikan dasar produksi komponen kritis, seperti sistem pengereman atau struktur penahan beban.

Seorang *engineer* yang kompeten menggunakan fisika dasar untuk memverifikasi hasil simulasi komputer. Sebelum mempercayai hasil *software* sepenuhnya, perlu dilakukan validasi logika atau perhitungan kasar:

> *"Software memprediksi tegangan maksimum hanya 20 MPa. Namun, perhitungan kasar menggunakan rumus dasar (P/A) menunjukkan seharusnya sekitar 150 MPa. Pasti ada kesalahan dalam pengaturan simulasi ini."*

Kemampuan untuk melakukan validasi (*sanity check*) menggunakan prinsip fisika dasar inilah yang membedakan seorang insinyur sejati dengan sekadar operator aplikasi.
