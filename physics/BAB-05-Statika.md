# BAB V. STATIKA

---

Statika adalah cabang mekanika yang mempelajari benda yang berada dalam keadaan diam (statis). Pembahasan ini penting untuk mengetahui bagaimana interaksi gaya pada suatu sistem. Sebagai contoh, ketika ada seseorang yang sedang naik motor, maka di sini ada gaya normal yang berasal dari roda depan dan roda belakang, dengan nilai keduanya yang berbeda. Pembahasan statika ini dapat digunakan untuk mengetahui nilai gaya normal pada masing-masing roda, yang ini penting pada proses perancangannya.

![Soal 2](LECTURE%20NOTES_files/Image_050.jpg)

Dalam analisis statika, dua komponen yang paling penting adalah **gaya** dan **torsi**. Kita sudah membahas mengenai gaya pada pembahasan sebelumnya, selanjutnya kita akan membahas mengenai torsi.

---

## 1. Torsi

Torsi adalah gaya yang menyebabkan putaran. Sebagai contoh, ketika kita mendorong pintu engsel, maka di sini kita memberikan torsi karena gaya yang kita berikan menyebabkan gerakan memutar. Begitu juga ketika kita mengencangkan baut, ini juga adalah torsi. Nilai torsi bergantung dengan jarak dari sumbu putar dan gaya yang diberikan, dengan formula:

$$\tau = r \times F$$

dengan $\tau$ adalah torsi (N.m), $r$ adalah jarak sumbu putar (m), dan $F$ adalah gaya (N).

**Sebagai contoh**, ketika diberikan gaya sebesar 10 N dengan jarak 0,5 m dari sumbu putar, maka nilai torsinya adalah:

$$\tau = r \times F = (0,5) \times (10) = 5 \text{ Nm}$$

![Contoh Torsi](LECTURE%20NOTES_files/Image_051.gif)

Dari formula tersebut, dapat diketahui bahwa nilai torsi akan semakin besar seiring dengan besarnya jarak dan gaya yang diberikan. Oleh karena itu, jika kita mendorong pintu, prosesnya akan lebih mudah jika kita mendorong di ujung daun pintu, dibandingkan ketika kita mendorong di dekat engsel.

![Torsi pada Pintu](LECTURE%20NOTES_files/Image_052.gif)

Dalam memperhitungkan nilai torsi, gaya yang diperhitungkan adalah komponen gaya yang arahnya **tegak lurus** dengan sumbu putar. Hal ini bisa dipahami di mana ketika gaya diberikan dengan arah sejajar sumbu putar, benda tidak bergerak. Seperti ketika kamu mendorong pintu ke arah dalam sumbu putarnya.

![Torsi Tegak Lurus](LECTURE%20NOTES_files/Image_053.gif)

Adapun untuk komponen gaya yang arahnya serong, di sini kita perlu mempertimbangkan komponen tegak lurusnya dalam menghitung torsi (*ini topik lanjutan yang tidak dibahas di sini*).

Kemudian, nilai arah dari torsi dipertimbangkan dari arah putaran yang dihasilkan, bukan dari arah gayanya. Untuk gaya yang menyebabkan putaran di arah **berlawanan jarum jam**, maka nilai torsi **positif**. Sementara jika putaran **searah jarum jam**, maka nilai torsi **negatif**.

![Arah Torsi](LECTURE%20NOTES_files/Image_054.png)

---

## 2. Kesetimbangan Benda

Agar suatu benda mengalami kesetimbangan, maka syarat yang harus dipenuhi ada dua. Pada pembahasan sebelumnya kita telah mengetahui satu syaratnya, yaitu $\Sigma F = 0$. Adapun syarat kedua adalah $\Sigma \tau = 0$.

> **Agar benda seimbang, maka total gaya dan total torsinya harus sama dengan nol.**

![Kesetimbangan](LECTURE%20NOTES_files/Image_055.gif)

### Contoh:

Berapa nilai gaya $F_2$ jika sistem berikut seimbang?

**Penyelesaian:**

$$\begin{aligned}
\Sigma \tau &= 0 \\
\tau_1 - \tau_2 &= 0 \\
\tau_1 &= \tau_2 \\
r_1 F_1 &= r_2 F_2 \\
(3)(30) &= (1) F_2 \\
F_2 &= 90 \text{ N}
\end{aligned}$$

---

## LATIHAN SOAL STATIKA

### Soal 1
Berapa massa benda X agar sistem di bawah ini seimbang? Berapa gaya dorong yang diberikan oleh penahan jungkat-jungkit?

![Soal 1](LECTURE%20NOTES_files/Image_056.jpg)

**Penyelesaian:**

Pertama-tama kita melakukan analisis torsi untuk mengetahui nilai massa dari benda X. Perhatikan bahwa gaya yang muncul dari benda adalah berupa gaya berat, sehingga $F = mg$.

$$\begin{aligned}
\Sigma \tau &= 0 \\
\tau_1 &= \tau_2 \\
r_1 m_1 g &= r_2 m_2 g \\
r_1 m_1 &= r_2 m_2 \\
(2) m_X &= (1)(10) \\
m_X &= 5 \text{ kg}
\end{aligned}$$

Setelah mengetahui nilai massa tersebut, sekarang kita bisa mencari nilai gaya dorong dari sumbu jungkat-jungkit.
![Soal 2](LECTURE%20NOTES_files/Image_057.jpg)

$$\begin{aligned}
\Sigma F &= 0 \\
F_1 + F_2 - F &= 0 \\
F &= F_1 + F_2 \\
F &= m_1 g + m_2 g \\
F &= (5)(10) + (10)(10) \\
F &= 150 \text{ N}
\end{aligned}$$

---

### Soal 2
Bayu dan adik perempuannya, Clara, sedang duduk di sebuah jungkat-jungkit. Panjang jungkat-jungkit dari ujung ke ujung adalah 6 m. Jika Clara yang bermassa 40 kg duduk di sisi ujung, berapakah jarak Bayu (massa 60 kg) dari titik pusat agar jungkat-jungkit tersebut seimbang?

![Soal 2](LECTURE%20NOTES_files/Image_058.gif)

**Penyelesaian:**

$$\begin{aligned}
\Sigma \tau &= 0 \\
\tau_B &= \tau_C \\
r_B m_B g &= r_C m_C g \\
r_B m_B &= r_C m_C \\
r_B (60) &= (3)(40) \\
r_B &= \frac{120}{60} = 2 \text{ m}
\end{aligned}$$

**Jarak Bayu dari titik pusat adalah 2 m agar seimbang.**

---

### Soal 3
Jika posisi duduk Clara mendekat ke sisi tengah mendekati Bayu, ke arah mana putaran gerakan dari jungkat-jungkit tersebut? Gunakan analisis torsi.

**Penyelesaian:**

Untuk mempermudah analisa, kita asumsikan Clara mendekat ke tengah di jarak 2 m dari pusat. Maka dengan analisa torsi:

$$\begin{aligned}
\Sigma \tau &= \tau_B - \tau_C \\
&= r_B m_B g - r_C m_C g \\
&= (2)(60)(10) - (2)(40)(10) \\
&= 1200 - 800 \\
&= 400 \text{ Nm}
\end{aligned}$$

Dikarenakan nilai total torsi adalah **positif**, itu artinya gerakan dari jungkat-jungkit tersebut adalah **berlawanan arah jarum jam**. Yaitu Bayu bergerak turun dan Clara bergerak naik.

---

### Soal 4
Sebuah papan terhubung dengan engsel dan sisi ujungnya ditahan dengan tali. Kemudian diletakkan benda bermassa 10 kg dan 5 kg pada papan tersebut seperti pada gambar berikut. Berapakah nilai gaya tarik dari tali tersebut jika sistem ini seimbang?

![Soal 4](LECTURE%20NOTES_files/Image_059.jpg)

**Penyelesaian:**

Kita akan mencari nilai gaya tarik tali ($T$) dengan menggunakan analisis torsi dengan titik pusat pada engsel. Oleh karena itu, jarak pada masing-masing perhitungan torsi dihitung terhadap jarak terhadap engsel tersebut.

![Soal 4 - Diagram](LECTURE%20NOTES_files/Image_060.jpg)

$$\begin{aligned}
\Sigma \tau &= 0 \\
\tau_1 + \tau_2 - \tau_3 &= 0 \\
r_1 m_1 g + r_2 m_2 g - r_3 T &= 0 \\
(1)(5)(10) + (2)(10)(10) - (3)T &= 0 \\
50 + 200 - 3T &= 0 \\
3T &= 250 \\
T &= 83,3 \text{ N}
\end{aligned}$$

> **Perhatian:** Dalam kasus ini, kita tidak bisa secara langsung menggunakan analisis gaya untuk mendapatkan nilai tegangan tali. Hal ini disebabkan karena pada analisis gaya, kita perlu untuk mempertimbangkan gaya $F$ yang muncul pada engsel, yang juga tidak diketahui nilainya. Oleh karena itu di sini kita menggunakan analisis torsi karena variabel yang tidak diketahui hanya gaya tegangan pada tali.

---

### Soal 5
Sebuah mesin forklift dengan massa 2 ton digunakan untuk mengangkat suatu benda. Perhatikan gambar di bawah. Titik pusat massa forklift berada pada jarak 0,5 meter dari ban belakang dan 1 meter dari ban depan. Sementara titik pusat massa benda yang diangkat berada pada jarak mendatar 0,8 m dari ban depan. Berapakah nilai massa maksimal dari benda yang diangkat sebelum forklift tersebut oleng?

![Soal 5](LECTURE%20NOTES_files/Image_061.jpg)

**Penyelesaian:**

Ketika kondisi oleng (beban depan terlalu besar), truk forklift akan terguling ke depan. Dalam kondisi ini, bagian belakang akan terangkat dan titik tumpu pada sistem ini hanya ada pada roda depan saja.

Dengan demikian, kasus forklift oleng sebenarnya tidak jauh berbeda dengan sistem jungkat-jungkit pada soal sebelumnya. Kita bisa menyelesaikan perhitungannya dengan analisis torsi.

![Soal 5 - Diagram](LECTURE%20NOTES_files/Image_062.jpg)

$$\begin{aligned}
\Sigma \tau &= 0 \\
r_1 m_1 g - r_2 m_2 g &= 0 \\
(1)(2.000)(10) - (0,8) m_2 (10) &= 0 \\
8 m_2 &= 20.000 \\
m_2 &= 2.500 \text{ kg}
\end{aligned}$$

**Massa maksimal benda yang diangkat adalah 2.500 kg (atau 2,5 ton).**

---

### Soal 6
Jika massa benda yang diangkat terlalu besar, bagaimana solusi teoritis agar forklift tersebut tidak oleng ke depan?

**Penyelesaian:**

Agar tidak oleng ke depan, salah satu solusi teoritis yang bisa dilakukan adalah dengan cara **menambah beban pada bagian belakang forklift** (counterweight).

Adapun solusi yang lebih baik adalah dengan **menggunakan forklift lain yang memiliki spesifikasi sesuai** dengan beban yang akan diangkat.
