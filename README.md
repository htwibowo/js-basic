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

File ini mendemonstrasikan penggunaan `for-in`. _Object_ `data` 
berisikan 
