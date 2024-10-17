1. Program ini ditulis dalam bahasa Go dan menghitung permutasi, kombinasi, dan faktorial dari bilangan bulat.
Fungsi Faktorial:
factorial(n int) int: Fungsi ini menghitung faktorial dari sebuah bilangan bulat n.
Basis kasus: Jika n adalah 0, maka faktorialnya adalah 1.
Kasus rekursi: Jika n lebih besar dari 0, maka faktorialnya adalah hasil perkalian dari n dengan faktorial dari n-1.
Fungsi Permutasi:

permutation(n, r int) int: Fungsi ini menghitung permutasi dari n objek yang diambil r sekaligus.
Pemeriksaan: Jika n lebih besar dari atau sama dengan r, maka permutasi dihitung menggunakan rumus n! / (n-r)!.
Jika n kurang dari r, maka permutasi tidak mungkin, sehingga hasilnya adalah 0.
Fungsi Kombinasi:

`combination(n, r int) int

2. Program ini didefinisikan dalam paket main dan mengimpor paket fmt. Program ini memiliki tiga fungsi: fx, gx, dan hx.

Fungsi fx menerima sebuah integer x sebagai input dan mengembalikan nilai x dikalikan dengan dirinya sendiri. Fungsi gx menerima sebuah integer x sebagai input dan mengembalikan nilai x dikurangi 2. Fungsi hx menerima sebuah integer x sebagai input dan mengembalikan nilai x ditambah 1.

Fungsi main mendeklarasikan tiga variabel integer: a, b, dan c. Program kemudian menggunakan fmt.Scan untuk menerima nilai dari user untuk setiap variabel tersebut.

Kemudian program menggunakan fmt.Println untuk mencetak hasil dari tiga operasi:

fx(gx(hx(a))): Fungsi hx diterapkan pada variabel a, lalu hasil dari fungsi hx digunakan sebagai input untuk fungsi gx, lalu hasil dari fungsi gx digunakan sebagai input untuk fungsi fx.
gx(hx(fx(b))): Fungsi fx diterapkan pada variabel b, lalu hasil dari fungsi fx digunakan sebagai input untuk fungsi hx, lalu hasil dari fungsi hx digunakan sebagai input untuk fungsi gx.
hx(fx(gx(c))): Fungsi gx diterapkan pada variabel c, lalu hasil dari fungsi gx digunakan sebagai input untuk fungsi fx, lalu hasil dari fungsi fx digunakan sebagai input untuk fungsi hx.

3. Deklarasi Variabel:

jarakPertama dan jarakkedua: Untuk menyimpan jarak titik ke pusat lingkaran pertama dan kedua.
x1, y1, r1: Koordinat pusat dan radius lingkaran pertama.
x2, y2, r2: Koordinat pusat dan radius lingkaran kedua.
x, y: Koordinat titik yang ingin diuji.
Input Data:

Program meminta input dari pengguna untuk nilai x1, y1, r1, x2, y2, r2, x, dan y.
Hitung Jarak:

Fungsi jarak() menghitung jarak antara dua titik menggunakan rumus jarak Euclidean.
Jarak titik ke pusat lingkaran pertama dihitung dan disimpan dalam jarakPertama.
Jarak titik ke pusat lingkaran kedua dihitung dan disimpan dalam jarakkedua.
Uji Titik:

Program memeriksa apakah titik tersebut berada di dalam atau di luar lingkaran pertama dan kedua.
Jika jarakPertama lebih kecil atau sama dengan r1 dan jarakkedua lebih kecil atau sama dengan r2, maka titik berada di dalam kedua lingkaran.
Jika jarakPertama lebih kecil atau sama dengan r1, maka titik berada di dalam lingkaran pertama.
Jika jarakkedua lebih kecil atau sama dengan r2, maka titik berada di dalam lingkaran kedua.
Jika kondisi di atas tidak terpenuhi, maka titik berada di luar lingkaran pertama dan kedua.
Cetak Hasil:

Program mencetak hasil berupa pesan yang menginformasikan posisi titik relative terhadap kedua lingkaran.
Jadi, program ini menerima tiga input integer dari user dan mencetak tiga hasil operasi yang melibatkan fungsi fx, gx, dan hx dengan urutan penerapan yang berbeda.
