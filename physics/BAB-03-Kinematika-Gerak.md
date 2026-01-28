# BAB III. Kinematika Gerak

---

## 1. Pengantar: Mengapa Kita Belajar Gerak?

Gerak adalah salah satu topik paling mendasar dalam fisika. Setiap benda yang ada di sekitar kita bergerak. Orang berjalan, sepeda motor bergerak, daun di pohon berayun, itu adalah contoh dari gerak. Bahkan, jika dilihat lebih jauh lagi, tubuh kita pun sekarang juga sedang bergerak mengikuti rotasi Bumi. Begitu pun Bumi yang sedang bergerak revolusi mengelilingi matahari.

Dalam dunia teknik, "gerak" bukanlah sekadar benda berpindah tempat. Gerak adalah nyawa dari sebuah sistem mekanis. Coba perhatikan sekeliling bengkel atau lingkungan kerja industri. Sepeda motor dapat berfungsi karena adanya gerak resiprokal piston yang diubah menjadi gerak rotasi roda. Sebuah mesin CNC (*Computer Numerical Control*) dapat memahat logam dengan presisi mikron karena adanya kontrol gerak yang sangat akurat pada sumbu X, Y, dan Z. Bahkan, efisiensi sebuah *jet engine* sangat bergantung pada bagaimana aliran udara bergerak melewati bilah-bilah turbin.

Memahami bagaimana benda bergerak, seberapa cepat ia berpindah, dan bagaimana kecepatannya berubah, adalah fondasi utama bagi seorang *engineer*.

---

## 2. Definisi Gerak dan Titik Acuan

Secara definisi fisika, sebuah benda dikatakan bergerak jika **posisinya berubah dari satu tempat ke tempat lain relatif terhadap waktu dan titik acuan tertentu**. Kata kunci di sini adalah "Titik Acuan" (*Frame of Reference*). Gerak itu bersifat relatif, artinya status bergerak atau diamnya suatu benda bergantung pada dari mana kita melihatnya.

**Contoh Gerak Relatif:** Bayangkan Anda sedang duduk di dalam sebuah mobil yang melaju di jalan tol.

- **Jika titik acuannya adalah jalan raya:** Anda sedang bergerak dengan kecepatan tinggi bersama mobil tersebut.
- **Jika titik acuannya adalah mobil itu sendiri:** Anda diam. Anda tidak berpindah posisi dari kursi Anda.

---

## 3. Kecepatan (*Velocity*)

Dalam istilah sederhana, kecepatan adalah ukuran seberapa cepat posisi benda berubah. Jika Anda menempuh jarak tertentu dalam waktu yang singkat, artinya Anda memiliki kecepatan tinggi.

Secara matematis, kecepatan $v$ didefinisikan sebagai perubahan jarak $\Delta s$ dibagi dengan perubahan waktu $\Delta t$.

$$v = \frac{\Delta s}{\Delta t}$$

Dimana:
- $v$ = Kecepatan (m/s atau km/jam)
- $\Delta s$ = Perubahan posisi/jarak (m atau km)
- $\Delta t$ = Waktu tempuh (detik atau jam)

### Memahami Nilai Kecepatan

Jika sebuah kendaraan tertulis memiliki kecepatan **50 km/jam**, ini artinya: *Dalam kurun waktu 1 jam, kendaraan tersebut akan menempuh jarak sejauh 50 kilometer.* Sehingga dalam waktu dua jam, maka jarak yang ditempuh adalah 100 kilometer. Dan jika jarak 50 km dapat ditempuh dalam waktu 1 jam, berapa waktu yang dibutuhkan untuk menempuh jarak 500 km? 10 jam jawabannya. Logikanya hanya sesederhana itu.

### Aplikasi di Teknik Mesin

Konsep kecepatan ini tidak terbatas pada gerak kendaraan saja. Konsep kecepatan ini pun sangat krusial dalam operasional mesin. Sebagai contohnya:

- **Feedrate (Kecepatan Makan):** Pada mesin CNC, *feedrate* sering dinyatakan dalam mm/menit. Ini adalah kecepatan linier pahat saat menyayat benda kerja.
- **Spindle Speed (Kecepatan Putar):** Dinyatakan dalam RPM (*Revolutions Per Minute*). Meskipun ini gerak melingkar, konsep dasarnya tetap perubahan posisi sudut per satuan waktu.

---

## 4. Kecepatan Rata-rata (*Average Velocity*)

Dalam dunia nyata, jarang sekali sebuah benda bergerak dengan kecepatan yang konstan terus-menerus. Sebuah motor mungkin melaju cepat, lalu melambat saat tikungan, dan berhenti saat lampu merah. Oleh karena itu, kita menggunakan konsep **Kecepatan Rata-rata**.

Kecepatan rata-rata tidak peduli seberapa sering Anda mengerem atau mengegas di tengah jalan. Ia hanya peduli pada **Total Jarak** yang ditempuh dibagi dengan **Total Waktu** yang dihabiskan.

$$v_{\text{rata-rata}} = \frac{\Delta s_{\text{total}}}{\Delta t_{\text{total}}}$$

Mari kita bedah konsep ini melalui studi kasus perhitungan.

### Studi Kasus 1: Perjalanan Andi

**Soal:** Andi naik motor dengan kecepatan 20 km/jam selama 2 jam, lalu 60 km/jam selama 1 jam, dan 100 km/jam selama 1 jam. Berapa nilai kecepatan rata-rata Andi?

**Penyelesaian:** Untuk mencari kecepatan rata-rata, kita harus mencari **Total Jarak** dan **Total Waktu** terlebih dahulu. Jangan merata-rata kecepatannya (jangan: (20+60+100)/3), itu cara yang salah!

1. **Hitung Jarak per Segmen:**
   - Segmen 1: 20 × 2 = 40 km
   - Segmen 2: 60 × 1 = 60 km
   - Segmen 3: 100 × 1 = 100 km

2. **Hitung Total Jarak $\Delta s$:**
   $$\Delta s = 40 + 60 + 100 = 200 \text{ km}$$

3. **Hitung Total Waktu $\Delta t$:**
   $$\Delta t = 2 + 1 + 1 = 4 \text{ jam}$$

4. **Hitung Kecepatan Rata-rata:**
   $$v_{\text{rata-rata}} = \frac{200}{4} = 50 \text{ km/jam}$$

Atau jika ditulis dalam bentuk formal, maka penyelesaiannya adalah:

$$\begin{aligned}
v &= \frac{\Delta s_{\text{total}}}{\Delta t_{\text{total}}} = \frac{\Delta s_1 + \Delta s_2 + \Delta s_3}{\Delta t_1 + \Delta t_2 + \Delta t_3} = \frac{v_1\Delta t_1 + v_2\Delta t_2 + v_3\Delta t_3}{\Delta t_1 + \Delta t_2 + \Delta t_3} \\[8pt]
&= \frac{(20)(2) + (60)(1) + (100)(1)}{2 + 1 + 1} = \frac{200}{4} = 50 \text{ km/jam}
\end{aligned}$$

---

### Studi Kasus 2: Perjalanan Salatiga - Semarang

**Soal:** Jarak Salatiga-Semarang adalah 60 km. Jika Budi naik motor dengan kecepatan 50 km/jam, berapa menit waktu yang dibutuhkan untuk sampai Semarang dari Salatiga?

**Penyelesaian:** Kita menggunakan rumus dasar $v = \Delta s / \Delta t$, yang bisa kita ubah posisinya menjadi $\Delta t = \Delta s / v$.

1. **Masukkan Nilai:**
   $$\Delta t = \frac{60}{50} = 1,2 \text{ jam}$$

2. **Konversi ke Menit:**
   
   (Mahasiswa teknik harus teliti dengan satuan. 0,2 jam bukan berarti 20 menit.)
   
   $$1,2 \text{ jam} = 1,2 \times 60 \text{ menit} = 72 \text{ menit}$$

Sehingga disimpulkan Budi membutuhkan waktu perjalanan selama **72 menit** atau selama **1 jam 12 menit**.

---

### Studi Kasus 3: Perjalanan Joko (Dengan Istirahat)

**Soal:** Joko melakukan perjalanan dari Salatiga ke Jakarta. Kecepatan mobil Joko adalah 100 km/jam selama 2 jam, 80 km/jam selama 3,5 jam, dan dia beristirahat selama 1 jam di Rest Area. Berapa kecepatan rata-rata Joko?

**Penyelesaian:** Ini adalah jebakan umum. Apakah waktu istirahat dihitung? **Ya.** Dalam fisika, kecepatan rata-rata memperhitungkan waktu total sampai perjalanan selesai.

1. **Hitung Jarak Tempuh:**
   - Sesi 1: 100 × 2 jam = 200 km
   - Sesi 2: 80 × 3,5 jam = 280 km
   - Sesi 3 (istirahat): 0 × 1 jam = 0 km (karena dia diam)
   - **Total Jarak:** 200 + 280 = 480 km

2. **Hitung Total Waktu:**
   - Waktu jalan 1: 2 jam
   - Waktu jalan 2: 3,5 jam
   - Waktu istirahat: 1 jam
   - **Total Waktu:** 2 + 3,5 + 1 = 6,5 jam

3. **Hitung Kecepatan Rata-rata:**
   $$v_{\text{rata-rata}} = \frac{480}{6,5} = 73,85 \text{ km/jam}$$

Perhatikan bahwa meskipun Joko sempat mengebut 100 km/jam, istirahat dan perlambatan membuat rata-rata efisiensi perjalanannya turun menjadi sekitar 73 km/jam.

---

## 5. Percepatan (*Acceleration*)

Jika kecepatan adalah perubahan posisi, maka **Percepatan (Akselerasi) adalah perubahan kecepatan dalam waktu tertentu.**

Ketika Anda menekan gas mobil atau menarik tuas gas motor, jarum speedometer bergerak naik. Pergerakan jarum dari angka rendah ke tinggi itulah visualisasi dari percepatan. Sebaliknya, pengereman disebut sebagai perlambatan (akselerasi negatif).

### Rumus Percepatan $a$:

$$a = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1}$$

Satuan standar dari percepatan adalah **meter per sekon kuadrat** ($\text{m/s}^2$).

### Memahami Arti Nilai Percepatan

Jika tertulis percepatan sebuah benda adalah **5 m/s²**, artinya: *Setiap 1 detik berlalu, kecepatan benda tersebut bertambah sebesar 5 m/s.*

- Detik ke-0: Diam (0 m/s)
- Detik ke-1: Kecepatan jadi 5 m/s
- Detik ke-2: Kecepatan jadi 10 m/s
- Detik ke-3: Kecepatan jadi 15 m/s, dan seterusnya.

**Percepatan Gravitasi Bumi:** Bumi menarik semua benda dengan percepatan gravitasi rata-rata **9,8 m/s²**. Artinya, jika Anda menjatuhkan baut dari ketinggian gedung (tanpa hambatan udara), setiap detiknya kecepatan jatuh baut tersebut bertambah 9,8 m/s. Semakin lama jatuhnya, semakin kencang hantamannya.

---

### Studi Kasus: Akselerasi Mobil Tesla

**Soal:** Mobil Tesla Model S dapat mencapai kecepatan dari 0 sampai 100 km/jam dalam waktu 1,99 detik. Berapa nilai percepatannya?

**Penyelesaian:** Tantangan di soal ini adalah perbedaan satuan. Kecepatan dalam km/jam, sedangkan waktu dalam detik. Kita harus menyamakan satuan ke Satuan Internasional (SI) yaitu meter dan detik.

1. **Konversi Kecepatan $v$:**
   - Kecepatan awal, $v_0 = 0$
   - Kecepatan akhir, $v_t = 100$ km/jam
   
   Ingat: 1 km = 1000 m dan 1 jam = 3600 s, sehingga nilai kecepatan akhirnya dapat dikonversi menjadi:
   $$100 \text{ km/jam} = \frac{100 \times (1000 \text{ m})}{(3600 \text{ s})} = 27,78 \text{ m/s}$$

2. **Masukkan ke Formula Percepatan:**
   - $\Delta v = 27,78 \text{ m/s} - 0 = 27,78 \text{ m/s}$
   - $\Delta t = 1,99 \text{ s}$

   Sehingga nilai percepatannya adalah:
   $$a = \frac{\Delta v}{\Delta t} = \frac{27,78}{1,99} = 13,96 \text{ m/s}^2$$

Nilai 13,96 m/s² ini sangat besar, bahkan lebih besar dari gravitasi bumi (9,8 m/s²) yang menyebabkan pengemudi akan merasa terdorong sangat kuat ke sandaran kursi (G-force).

---

## 6. Jarak Tempuh Pada Gerak Dipercepat

Berbeda dengan jarak tempuh pada gerak dengan kecepatan konstan, jarak tempuh pada gerak yang dipercepat tidak bersifat linear. Hal ini bisa dipahami karena setiap detiknya, kecepatan gerak benda akan selalu berubah seiring dengan nilai kecepatannya.

Nilai jarak pada gerak dipercepat dapat dihitung dengan formula berikut:

$$s = v_0 t + \frac{1}{2}at^2$$

dengan $s$ adalah jarak (m), $v_0$ adalah kecepatan awal (m/s), $t$ adalah waktu tempuh (s), dan $a$ adalah percepatan (m/s²).

---

> **Informasi pendalaman (bukan materi wajib)**
>
> Asal usul formula jarak tempuh pada gerak dipercepat tersebut adalah sebagai berikut.
>
> Pada kasus khusus gerak dengan percepatan konstan, nilai kecepatan rata-rata dapat dihitung dengan formula:
> $$v_{\text{rata-rata}} = \frac{v_0 + v}{2}$$
>
> Berdasarkan formula percepatan, didapatkan hubungan:
> $$a = \frac{v - v_0}{t} \quad \Rightarrow \quad v = v_0 + at$$
>
> Dengan demikian, nilai jarak tempuh benda yang bergerak dengan percepatan $a$, dengan kecepatan awal $v_0$ dan kecepatan akhir $v$ adalah:
> $$s = v_{\text{rata-rata}} \cdot t = \left(\frac{v_0 + v}{2}\right) t = \left(\frac{v_0 + v_0 + at}{2}\right) t = \left(\frac{2v_0 + at}{2}\right) t = v_0 t + \frac{1}{2}at^2$$

---

## LATIHAN SOAL KINEMATIKA

### Soal 1
Usain berlari ke arah utara dengan kecepatan 2 m/s selama 1 menit. Lalu berlari dengan kecepatan yang sama ke arah selatan selama 30 detik. Berapa nilai kecepatan rata-rata Usain?

**Penyelesaian:** Soal ini menguji pemahaman tentang arti dari perpindahan. Pada contoh-contoh sebelumnya, kasusnya adalah gerakan satu arah meskipun terdapat perubahan kecepatan. Namun pada soal ini, ternyata gerakannya berbalik arah sehingga terdapat faktor pengurangan jarak pada perpindahan akhir.

![Alat Ukur Panjang](LECTURE%20NOTES_files/Image_023.png)

**Segmen 1 (ke utara):**
Jarak tempuhnya, $\Delta s_1 = (2 \text{ m/s})(1 \text{ menit}) = (2 \text{ m/s})(60 \text{ s}) = 120 \text{ m}$

**Segmen 2 (ke selatan):**
Jarak tempuhnya, $\Delta s_2 = (-2 \text{ m/s})(30 \text{ s}) = -60 \text{ m}$
(Perhatikan bahwa nilainya negatif karena gerakannya berbalik arah).

**Kecepatan rata-rata:**
$$v_{\text{rata-rata}} = \frac{\Delta s_{\text{total}}}{\Delta t_{\text{total}}} = \frac{\Delta s_1 + \Delta s_2}{\Delta t_1 + \Delta t_2} = \frac{120 - 60}{60 + 30} = 0,67 \text{ m/s}$$

---

### Soal 2
Sebuah mesin CNC memiliki feedrate 1200 mm/min. Jika jarak pemotongan adalah 300 mm, berapa lama proses pemotongan berlangsung?

**Penyelesaian:** Soal ini bisa diselesaikan dengan definisi dari kecepatan.

$$v = \frac{\Delta s}{\Delta t} \quad \Rightarrow \quad \Delta t = \frac{\Delta s}{v}$$

Waktu yang dibutuhkan untuk proses pemotongan adalah:
$$\Delta t = \frac{300 \text{ mm}}{1200 \text{ mm/min}} = 0,25 \text{ menit} = 15 \text{ detik}$$

---

### Soal 3
Sebuah mesin CNC menggerakkan spindle ke arah X dengan percepatan 10 m/s² sehingga spindle berpindah sejauh 150 mm dalam waktu 3 detik. Berapa kecepatan rata-ratanya?

**Penyelesaian:** Tidak perlu terkecoh dengan detail yang tidak perlu. Definisi dari kecepatan rata-rata adalah perpindahan total dibagi waktu. Jadi kita hanya peduli dengan total perpindahannya dan total waktu yang dibutuhkan, selain itu hanya *noise*.

$$v_{\text{rata-rata}} = \frac{\Delta s_{\text{total}}}{\Delta t_{\text{total}}} = \frac{150 \text{ mm}}{3 \text{ s}} = 50 \text{ mm/s}$$

Atau jika diubah dalam satuan mm/min, maka nilainya adalah:
$$v_{\text{rata-rata}} = 3000 \text{ mm/min}$$

---

### Soal 4
Sebuah mobil bergerak dengan kecepatan 70 km/jam lalu digas dengan percepatan 5 m/s². Dalam waktu 1 jam, apakah jarak yang ditempuh lebih atau kurang dari 70 km?

**Penyelesaian:** Soal ini bisa saja diselesaikan dengan menghitung jarak yang ditempuh dengan formula $s = v_0 t + (1/2)at^2$, atau soal ini juga bisa diselesaikan dengan analisis yang lebih sederhana.

Jika kita perhatikan, kecepatan awal mobil adalah 70 km/jam. Jika mobil tersebut bergerak tanpa dipercepat dalam 1 jam, maka jarak yang ditempuh adalah:
$$\Delta s = (70 \text{ km/jam})(1 \text{ jam}) = 70 \text{ km}$$

Tanpa mobil tersebut dipercepat, jarak yang ditempuh dalam 1 jam adalah 70 km. Maka, jika mobil tersebut dipercepat, **jaraknya pasti lebih dari 70 km**.

---

### Soal 5
Pada mesin CNC, gerakan rapid move (G00) memiliki kecepatan lebih tinggi dibanding feed move (G01). Jika mesin melakukan rapid move (G00) sejauh 100 mm dan feed move (G01) sejauh 100 mm, mana yang membutuhkan waktu lebih lama?

**Penyelesaian:** Pada jarak yang sama, waktu yang dibutuhkan bergantung pada kecepatan geraknya. Jika kita perhatikan pada formula gerak,

$$\Delta t = \frac{\Delta s}{v}$$

Waktu yang dibutuhkan berbanding terbalik dengan kecepatan. Sehingga, pada jarak yang sama, kecepatan yang lebih besar akan memberikan waktu yang lebih pendek. Sementara kecepatan yang lebih kecil akan memberikan waktu yang lebih lama.

Kesimpulannya, karena gerakan *feed move* (G01) memiliki kecepatan yang lebih rendah, maka **waktu tempuh yang dibutuhkan lebih lama**.

---

### Soal 6
Sebuah baut jatuh dari mesin setinggi 20 meter. Jika diasumsikan jatuh bebas tanpa hambatan, berapa kecepatan baut setelah 1,5 detik jatuh? (Gunakan percepatan gravitasi g = 9,8 m/s²)

**Penyelesaian:** Gunakan formula percepatan untuk menghitung kecepatan geraknya setelah jangka waktu tertentu.

$$\begin{aligned}
a &= \frac{\Delta v}{\Delta t} \quad \Rightarrow \quad \Delta v = a \cdot \Delta t \\[6pt]
v - v_0 &= a \cdot \Delta t \\[6pt]
v &= v_0 + a \cdot \Delta t = (0) + (9,8)(1,5) = 14,7 \text{ m/s}
\end{aligned}$$
