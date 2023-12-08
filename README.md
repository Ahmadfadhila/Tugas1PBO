# Tugas1PBO
Python adalah bahasa pemrograman tingkat tinggi yang populer, mudah dipelajari, dan serbaguna. Diciptakan oleh Guido van Rossum pada akhir 1980-an, Python dirancang dengan fokus pada keterbacaan kode dan kesederhanaan sintaksnya, membuatnya menjadi salah satu bahasa yang digunakan luas di berbagai bidang seperti pengembangan web, pengembangan perangkat lunak, analisis data, kecerdasan buatan, dan banyak lagi.

Beberapa ciri khas Python meliputi:
1. Sintaks Mudah Dipahami:

    Penggunaan indentasi (spasi) untuk menandai blok kode, yang membuatnya lebih mudah dibaca dibandingkan dengan menggunakan kurung kurawal atau tanda kurung lainnya.

2. Serbaguna:

    Python digunakan dalam berbagai bidang, seperti pengembangan web (Flask, Django), ilmu data (paket seperti Pandas, NumPy), kecerdasan buatan (TensorFlow, PyTorch), pengembangan permainan (Pygame), dan banyak lagi.

3. Ekosistem yang Kaya:

    Python memiliki banyak perpustakaan dan modul yang memudahkan pengembangan, memungkinkan penggunaan kode yang sudah ada (modularitas), dan mempercepat proses pembuatan aplikasi atau proyek.

4. Dukungan Komunitas yang Kuat:

    Python didukung oleh komunitas besar pengembang yang aktif. Hal ini menghasilkan dokumentasi yang baik, sumber daya pembelajaran yang melimpah, serta dukungan dari berbagai forum dan komunitas online.

5. Portabilitas:

    Kode Python dapat dijalankan di berbagai platform, termasuk Windows, macOS, dan berbagai distribusi Linux.

Kelebihan Python termasuk kemudahan pemahaman, fleksibilitas, serta cepatnya dalam pengembangan prototipe dan produksi. Kekurangannya mungkin terletak pada kecepatan relatifnya dibandingkan bahasa pemrograman lain yang lebih teroptimasi secara langsung untuk kecepatan tertentu. Meskipun demikian, kemampuan Python untuk bekerja dengan banyak perpustakaan yang dioptimalkan secara khusus dapat mengatasi kekurangan ini dalam banyak kasus.


Pembahasan
![image](https://github.com/Ahmadfadhila/Tugas1PBO/assets/150579766/e8dae0e0-04c8-419c-84dc-5888ec85dd43)
for i in range(1, 101):

Kode ini membuat loop for yang akan iterasi dari angka 1 hingga 100. Variabel i akan merepresentasikan setiap angka di dalam rentang ini.
if i % 10 == 0:

Ini adalah kondisi if yang memeriksa apakah nilai i habis dibagi 10 (tanpa sisa). % adalah operator modulo yang memberikan sisa dari pembagian.
for _ in range(3):

Ini adalah loop for di dalam kondisi if yang akan dijalankan ketika nilai i adalah kelipatan 10. Loop ini akan dijalankan tiga kali karena range(3).
print("Ahmadfadhila")

Statement ini akan mencetak teks "Ahmadfadhila" ke layar. Ketika kondisi di atas terpenuhi (nilai i habis dibagi 10), teks ini akan dicetak sebanyak tiga kali.
else:

Bagian ini adalah bagian alternatif dari kondisi if. Jika nilai i tidak habis dibagi 10, maka eksekusi akan melanjutkan ke sini.
print(i)

Jika nilai i tidak habis dibagi 10, baris ini akan mencetak nilai i ke layar.
Jadi, kode tersebut akan mencetak angka dari 1 hingga 100 kecuali untuk kelipatan 10, di mana akan mencetak "Ahmadfadhila" sebanyak tiga kali.

![image](https://github.com/Ahmadfadhila/Tugas1PBO/assets/150579766/5a20b891-598b-48aa-9745-391aa163a826)
jumlah_prima = 0

Ini adalah inisialisasi variabel jumlah_prima yang akan digunakan untuk menghitung jumlah bilangan prima yang ditemukan.
for i in range(2, 24):

Ini adalah loop for yang akan mengiterasi nilai i dari 2 hingga 23 (24 tidak termasuk). Loop ini akan memeriksa setiap bilangan dalam rentang tersebut.
prima = True

Di sini, variabel prima diinisialisasi sebagai True, yang akan digunakan untuk menandai apakah bilangan i adalah bilangan prima.
for j in range(2, int(i ** 0.5) + 1):

Ini adalah loop di dalam loop. Loop ini akan melakukan iterasi dari 2 hingga akar dari i (dijumlahkan 1) untuk memeriksa apakah i adalah bilangan prima.
if i % j == 0:

Pernyataan ini memeriksa apakah i habis dibagi oleh j (dalam rentang dari 2 hingga akar dari i). Jika sisa bagi adalah 0, maka i bukan bilangan prima karena memiliki pembagi selain 1 dan dirinya sendiri.
prima = False

Jika ditemukan pembagi selain 1 dan i sendiri, prima diubah menjadi False untuk menandai bahwa i bukanlah bilangan prima.
break

Ini adalah perintah untuk keluar dari loop for j saat ditemukan pembagi, karena sudah cukup untuk membuktikan bahwa i bukan bilangan prima.
if prima:

Setelah loop selesai, kode ini memeriksa apakah variabel prima tetap True. Jika ya, maka i adalah bilangan prima.
jumlah_prima += 1

Jika i adalah bilangan prima, maka jumlah bilangan prima yang ditemukan akan ditambah satu.
print(i)

Mengeluarkan nilai i ke layar jika i adalah bilangan prima.
print("Jumlah angka prima:", jumlah_prima)

Setelah selesai mengiterasi semua bilangan dari 2 hingga 23, kode ini akan mencetak jumlah total bilangan prima yang ditemukan.
Jadi, kode tersebut akan mencetak semua bilangan prima antara 2 dan 23 (tidak termasuk 24), serta menampilkan jumlah total bilangan prima yang ditemukan

![image](https://github.com/Ahmadfadhila/Tugas1PBO/assets/150579766/43b9cc86-c44e-4018-ba13-eb605a71e3e1)

j = 1

Inisialisasi variabel j dengan nilai 1. Variabel ini akan digunakan sebagai penghitung atau pengontrol loop.
while j <= 24:

Ini adalah loop while yang akan berjalan selama nilai j kurang dari atau sama dengan 24. Loop akan terus berlanjut sampai kondisi ini tidak terpenuhi lagi.
if j % 3 == 0:

Pernyataan if ini memeriksa apakah nilai j habis dibagi 3. Jika sisa bagi adalah 0, berarti j adalah kelipatan dari 3.
print("Kelipatan 3")

Jika nilai j habis dibagi 3, pernyataan ini akan mencetak teks "Kelipatan 3" ke layar.
else:

Bagian else ini menangani kondisi saat nilai j tidak habis dibagi 3.
print(j)

Jika nilai j tidak habis dibagi 3, nilai j akan dicetak ke layar.
j += 1

Ini adalah operasi penambahan yang dilakukan setelah setiap iterasi loop. Nilai j akan bertambah satu setiap kali iterasi berakhir untuk mempersiapkan iterasi berikutnya.
Jadi, dengan menggunakan loop while, program ini mencetak angka dari 1 hingga 24. Jika angka tersebut habis dibagi 3, program mencetak "Kelipatan 3" sebagai gantinya.

![image](https://github.com/Ahmadfadhila/Tugas1PBO/assets/150579766/f189ab96-993d-47a3-82c0-446e221bb1f6)


angka = [...]

Inisialisasi sebuah list yang disebut angka yang berisi nama-nama bulan dalam bahasa Indonesia, mulai dari "Januari" hingga "Oktober".
for i in angka:

Ini adalah loop for yang akan mengiterasi setiap elemen dalam list angka. Saat setiap iterasi, nilai dari elemen saat ini (dalam hal ini direpresentasikan oleh variabel i) akan diambil dari list.
print(i)

Pernyataan ini mencetak nilai dari variabel i. Dalam konteks ini, i akan mewakili nama bulan dari setiap iterasi dalam loop for.
Jadi, menggunakan loop for ini, kode tersebut akan mencetak nama-nama bulan yang ada dalam list angka, yaitu nama-nama bulan dalam bahasa Indonesia dari "Januari" hingga "Oktober".

Berikut tugas dari Ahmad Fadhila dengan NPM G1F022005 dibuat untuk memenuhi nilai Tugas 1 Mata Kuliah PBO , Prodi Sistem Informasi , Fakultas Teknik , Universitas Bengkulu. Sekian Terima Kasih
