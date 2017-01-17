### array.js

File ini berisikan demonstrasi array satu dimensi dan dua dimensi 
di JavaScript.

Pada demonstrasi untuk variable `arrMembers` diisikan 4 data, yang 
salah satunya sengaja dikosongkan. Ketika di cek, ternyata isi dari 
data di index yang dikosongkan di tengah sama dengan yang tidak 
terdaftar di array, yakni `undefined`.

Demonstrasi kedua adalah mencoba mengeluarkan data untuk variable 
`multiArray`.

### boolean.js

Dalam file ini didefinisikan satu variable bernama `isActive` yang 
berisi data default yakni `true`. Tipe data untuk variable 
`isActive` menjadi boolean.

### breakContinue.js

File ini berisikan operasi looping menggunakan `while` yang 
mendemonstrasikan kegunaan dari `break` dan `continue`.

Dalam demonstrasi ini ada dua buah variable, yakni n dan x yang 
masinng-masing diinisialisasi nilai `0`. Looping 
akan berhenti jika nilai n kurang dari 5 (`while(n < 5)`) dan atau 
jika nilai dari x lebih dari 10 (`if (x > 10) { break; } `). Pada 
setiap iterasinya, nilai n akan ditambah 1, dan nilai x akan 
ditambah dengan nilai n yang terbaru. Jika kemudian nilai x habis 
dibagi 2 (`if (x % 2 == 0) { continue; }`), maka iterasi akan 
loncat ke iterasi selanjutnya, dan operasi dibawahnya akan 
di_skip_.

### breakWithLabel.js

File ini mendemonstrasikan penggunaan `break` yang menggunakan 
label.

Didalamnya terdapat _nested-loop_ yang jika dalam kondisi tertentu 
dalam looping terdalam terpenuhi, maka iterasi teratas akan 
berhenti. Hal ini terjadi akibat dipanggilnya baris program `break 
topLabel`, yang akan menghentikan _looping_ yang terdapat di bawah 
`topLabel:`.


### const.js

Di dalam file ini didemonstrasikan penggunaan `const`.

Jika file ini dijalankan, akan terjadi error pada saat 
mengevaluasi baris program ke-7, karena `const` bersifat _immutable_ atau hanya bisa 
di-_assign_ pada saat pendefinisian variable.

### doWhile.js

File ini berisikan demonstrasi untuk penggunaan `do-while`. 
_Looping_ menggunakan `do-while` akan mengeksekusi blok program 
didalamnya minimal 1 kali, walaupun kondisi tidak terpenuhi 
sekalipun.

File ini akan menampilkan bilangan genap jika dieksekusi.

### dynamic.js

Didalamnya berisi demonstrasi tentang sifat tipe data 
dalam bahasa pemrograman JavaScript yang dinamis. Hal ini dapat 
dilihat pada baris `console.log(...)`, yang berisi String dan 
Integer yang dapat langsung digabung tanpa dilakukan _casting_ 
terlebih dahulu.

### floatingPoint.js

Didalamnya terdapat beberapa variable yang berisi `floating point 
number`.

Pada variable `fpPertama` diisi dengan bilangan real bernilai 
positif. Variable `fpKedua` diisi dengan bilangan real bernilai 
negatif. Variable `fpKetiga` diisi dengan angka dengan angka dan 
notasi E+ (_Positive Exponent_). Variable `fpKeempat` diisi dengan 
angka dan notasi e- (_Negative Exponent_).

### forIn.js

File ini mendemonstrasikan penggunaan `for-in`. Masing-masing 
atribut dalam _Object_ `data` akan dimunculkan beserta _key_-nya.

### for.js

File ini berisikan penggunaan looping `for`. Iterasi akan 
dijalankan sebanyak 9 kali, dan nilai `i` akan berubah dari dari 
asalnya 0 menjadi 9 pada iterasi terakhir.

### fungsiAnonim.js

File ini berisikan demonstrasi penggunaan _anonymous function_ yang 
di _assign_ ke variable `pangkat`. Fungsi ini memiliki 1 argumen 
dan menghasilkan nilai pangkat 2 dari inputan argumennya.

### fungsiRekursif.js

File ini berisikan demonstrasi fungsi rekursif. Fungsi rekursif 
adalah fungsi yang didalamnya memanggil fungsi itu sendiri.

Didemonstrasikan didalamnya penggunaan rekursif untuk operasi 
faktorial, sehingga jika dipanggil `factorial(6)`, akan 
menghasilkan nilai 720.

### if.js

File ini mendemonstrasikan pengkondisian menggunakan `if`.

Kondisi pertama dan kedua masing-masing bernilai `false` dan 
`true`, sehingga hanya blok program di kondisi kedua saja yang akan 
dijalankan.

Kondisi ketiga menggunakan pengkondisian berdasarkan inputan dari 
user.

Jika inputan lebih dari 80, maka akan muncul output "A".
Jika inputan lebih dari 70, maka akan muncul output "B".
Jika inputan lebih dari 60, maka akan muncul output "C".
Jika inputan lebih dari 30, maka akan muncul output "D".
Jika inputan kurang dari 30, maka akan muncul output "Tidak 
Lulus".

### integers.js

File ini berisikan pengunaan tipe data Integer dan jenis-jenisnya.

### json.js

File ini berisikan demonstrasi JSON (JavaScript Object Notation).

### nested.js

File ini berisikan demonstrasi _nested function_. fungsi 
`tambahkan()` hanya bisa dieksekusi di dalam _scope_ fungsi 
`induk()` karena didefinisikan di dalam.

### readline.js

File ini berisikan demonstrasi penggunaan _module_ `readline`.

### switch.js

File ini berisikan demonstrasi penggunaan kondisi `switch`.

### throw.js

File ini berisikan demonstrasi penggunaan `try-catch`. Jika terjadi 
error pada block `try`, maka akan ditangkap oleh `catch`.

### while.js

File ini berisikan demonstrasi untuk penggunaan _looping_ `while`.
