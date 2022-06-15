# Python Tutorial
### Pengenalan Python

Apa itu Python?

Python adalah bahasa pemrograman yang populer. Dibuat oleh Guido Van Rossum yang dirilis pada tahun 1991. 

**Digunakan untuk:**
- pengembangan web(sisi server)
- pengembangan perangkat lunak
- matematika
- script
  
**Apa yang bisa dilakukan python?**
- Python dapat digunakan di server untuk membuat aplikasi web.
- python dapat digunakan bersama perangkat lunak untuk membuat alur kerja.
- python dapat terhubung ke system database. Serta dapat membaca dan memodifikasi file.
- python dapat digunakan untuk menangani data besar dan melakukan matematika yang kompleks.
- python dapat digunakan untuk pembuatan prototype cepat, atau pengembangan perangkat lunak siap produksi.
  
**Mengapa python?**
- python bekerja pada platform yang berbeda(windows, mac, linux, rassberry pi, dll).
- python memiliki syntax sederhana yang mirip dengan bahasa inggris.
- python memiliki syntax yang memungkinkan pengembang untuk menulis program dan lebih sedikit baris dari beberapa bahasa pemrograman lainnya.
- python berjalan pada system interpreter, artinya kode dapat dieksekusi segera setelah ditulis. Ini berarti bahwa pembuatan prototype bisa sangat cepat.
- python dapat diperlakukan dengan cara prosedural, cara berorientasi objek atau cara fungsional.
  
**Senang mendengarnya**
- Versi utama terbaru dari Python adalah Python 3, yang akan kita gunakan dalam tutorial ini. Namun, Python 2, meskipun tidak diperbarui dengan apa pun selain pembaruan keamanan, masih cukup populer.
- Dalam tutorial ini Python akan ditulis dalam editor teks. Dimungkinkan untuk menulis Python dalam Lingkungan Pengembangan Terintegrasi, seperti Thonny, Pycharm, Netbeans atau Eclipse yang sangat berguna saat mengelola koleksi file Python yang lebih besar.

**Sintaks Python dibandingkan dengan bahasa pemrograman lain**
- Python dirancang agar mudah dibaca, dan memiliki beberapa kesamaan dengan bahasa Inggris dengan pengaruh dari matematika.
- Python menggunakan baris baru untuk menyelesaikan perintah, berbeda dengan bahasa pemrograman lain yang sering menggunakan titik koma atau tanda kurung.
- Python bergantung pada lekukan, menggunakan spasi, untuk mendefinisikan ruang lingkup; seperti ruang lingkup loop, fungsi dan kelas. Bahasa pemrograman lain sering menggunakan kurung kurawal untuk tujuan ini.

contoh
```python
print('Hello, World!')
```

---
# Memulai dengan Python

### install python

Banyak PC dan Mac yang sudah menginstal python.

Untuk memeriksa apakah Anda telah menginstal python pada PC Windows, cari di bilah mulai untuk Python atau jalankan yang berikut ini di Command Line (cmd.exe):

```
C:\Users\Your Name>python --version
```

Untuk memeriksa apakah Anda telah menginstal python di Linux atau Mac, lalu di linux buka baris perintah atau di Mac buka Terminal dan ketik:

```
python --version
```

Jika ternyata Anda tidak menginstal Python di komputer Anda, maka Anda dapat mengunduhnya secara gratis dari situs web berikut: https://www.python.org/

**Python Quickstart**

Python adalah bahasa pemrograman yang ditafsirkan, artinya sebagai pengembang Anda menulis file Python (.py) dalam editor teks dan kemudian memasukkan file-file itu ke dalam interpreter python untuk dieksekusi.

Cara menjalankan file python adalah seperti ini pada baris perintah:

```
C:\Users\Your Name>python helloworld.py
```

Di mana "helloworld.py" adalah nama file python Anda.

Mari kita tulis file Python pertama kita, bernama helloworld.py, yang dapat dilakukan di editor teks apa pun.

> helloworld.py
> ```python
> print("Hello, World!")
> ```

Simpan file Anda. Buka baris perintah Anda, navigasikan ke direktori tempat Anda menyimpan file Anda, dan jalankan:

```
C:\Users\Your Name>python helloworld.py
```

Output
```
Hello, World!
```

**Baris perintah python**

Untuk menguji sejumlah kecil kode dalam python terkadang tercepat dan termudah untuk tidak menulis kode dalam file. Ini dimungkinkan karena Python dapat dijalankan sebagai baris perintah itu sendiri.

Ketik baris perintah berikut pada mac, windows dan linux:

> C:\Users\Your Name>python

Atau, jika perintah "python" tidak berfungsi, Anda dapat mencoba "py":

> C:\Users\Your Name>py

Dari sana Anda dapat menulis python apa pun, termasuk contoh hello world kami dari tutorial sebelumnya:

```
C:\Users\Your Name>python
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>print("Hello, World!")
```

Yang akan menulis "hello, World!" di baris perintah:

```
C:\Users\Your Name>python
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello, World!")
Hello, World!
```
Setiap kali Anda selesai di baris perintah python, Anda cukup mengetik yang berikut ini untuk keluar dari antarmuka baris perintah python:

```
exit()
```

---
# Python Syntax

### Menjalankan Sintaks Python

Seperti yang kita pelajari di halaman sebelumnya, sintaks Python dapat dieksekusi dengan menulis langsung di Command Line:

```
>>> print("Hello, World!")
Hello, World!
```

Atau dengan membuat file python di server, menggunakan ekstensi file .py, dan menjalankannya di Command Line:

```
C:\Users\Your Name>python myfile.py
```

**Indentasi**

Indentasi mengacu pada spasi di awal baris kode.

Di mana dalam bahasa pemrograman lain lekukan dalam kode hanya untuk keterbacaan, lekukan dalam Python sangat penting.

Python menggunakan lekukan untuk menunjukkan blok kode.

> Contoh
> ```python
> if 5 > 2:
> 	print("Five is greater than two!")
> ```

Python akan memberi Anda kesalahan jika Anda melewatkan lekukan:

> Contoh
> Kesalahan syntax
> ```python
> if 5 > 2:
> print("Five is greater than two!")
> ```

Jumlah spasi terserah Anda sebagai programmer, penggunaan yang paling umum adalah empat, tetapi harus setidaknya lebih dari satu.

> Contoh
> ```python
> if 5 > 2:
> 	print("Five is greater than two!") 
> if 5 > 2:
> 	print("Five is greater than two!")
> ```

Anda harus menggunakan jumlah spasi yang sama di blok kode yang sama, jika tidak Python akan memberi Anda kesalahan:

> Contoh
> 
> kesalahan syntax
> ```python
> if 5 > 2:
> 	print("Five is greater than two!")
> 		print("Five is greater than two!")
> ```

**Variabel**

Dalam Python, variabel dibuat saat Anda menetapkan nilai padanya:

> Contoh
>
> Variabel dalam Python:
> ```python
> x = 5
> y = "Hello, World!"
> ```

Python tidak memiliki perintah untuk mendeklarasikan variabel.

Anda akan mempelajari lebih lanjut tentang variabel di bab Variabel Python .

**Komentar**

Python memiliki kemampuan berkomentar untuk tujuan dokumentasi dalam kode.

Komentar dimulai dengan #, dan Python akan merender sisa baris sebagai komentar:

> Contoh
> 
> komentar dengan python:
> ```py
> #This is a comment.
> print("Hello, World!")
> ```

---
# Komentar Python

Komentar dapat digunakan untuk menjelaskan kode Python.

Komentar dapat digunakan untuk membuat kode lebih mudah dibaca.

Komentar dapat digunakan untuk mencegah eksekusi saat menguji kode.

**Membuat Komentar**

Komentar dimulai dengan `#`, dan Python akan mengabaikannya:

> Contoh
> ```py
> # this is comment
> print("Hello, World!")
> ```

Komentar dapat ditempatkan di akhir baris, dan Python akan mengabaikan sisa baris:

> Contoh
> ```py
> print("Hello, World!") #This is a comment
> ```

Komentar tidak harus berupa teks yang menjelaskan kode, tetapi juga dapat digunakan untuk mencegah Python mengeksekusi kode:

> Contoh
> ```py
> #print("Hello, World!")
> print("Cheers, Mate!")
> ```

**Komentar Multi Baris**

Python tidak benar-benar memiliki sintaks untuk komentar multi baris.

Untuk menambahkan komentar multiline, Anda dapat menyisipkan a `#` untuk setiap baris:

> Contoh
> ```py
> #This is a comment
> #written in
> #more than just one line
> print("Hello, World!")
> ```

Atau, tidak seperti yang dimaksudkan, Anda dapat menggunakan string multiline.

Karena Python akan mengabaikan literal string yang tidak ditetapkan ke variabel, Anda dapat menambahkan string multiline (tanda kutip tiga) dalam kode Anda, dan menempatkan komentar Anda di dalamnya:

> Contoh
> ```py
> """
> This is a comment
> written in
> more than just one line
> """
> print("Hello, World!")
> ```

Selama string tidak ditetapkan ke variabel, Python akan membaca kode, tetapi kemudian mengabaikannya, dan Anda telah membuat komentar multiline.

# Variabel Python

### Variables

Variabel adalah wadah untuk menyimpan nilai data.

**Membuat Variabel**

Python tidak memiliki perintah untuk mendeklarasikan variabel.

Variabel dibuat saat Anda pertama kali menetapkan nilai padanya.

> Contoh
> ```py
> x = 5
> y = "John"
> print(x)
> print(y)
> ```

Variabel tidak perlu dideklarasikan dengan tipe tertentu , dan bahkan dapat diubah tipenya setelah ditetapkan.

> Contoh
> ```py
> x = 4       # x is of type int
> x = "Sally" # x is now of type str
> print(x)
> ```

**Pengecoran**

Jika Anda ingin menentukan tipe data dari suatu variabel, ini dapat dilakukan dengan casting.

> Contoh
> ```py
> x = str(3)    # x will be '3'
> y = int(3)    # y will be 3
> z = float(3)  # z will be 3.0
> ```

**Melihat type data**

Anda bisa mendapatkan tipe data variabel dengan method `type()`.

> Contoh
> ```py
> x = 5
> y = "John"
> print(type(x))
> print(type(y))
> ```

Anda akan mempelajari lebih lanjut tentang tipe data dan casting nanti dalam tutorial ini.

**Kutipan Tunggal atau Ganda?**

Variabel string dapat dideklarasikan dengan menggunakan tanda kutip tunggal atau ganda:

> Contoh
> ```py
> x = "John"
> # is the same as
> x = 'John'
> ```

**case sensitif**

Nama variabel peka huruf besar/kecil.

> Contoh
> 
> Ini akan membuat dua variabel:
>
> ```py
> a = 4
> A = "Sally"
> #A will not overwrite a
> ```

---
# Python Variable Names

**Variable name**

Sebuah variabel dapat memiliki nama pendek (seperti x dan y) atau nama yang lebih deskriptif (umur, carname, total_volume). Aturan untuk variabel Python:

- Nama variabel harus dimulai dengan huruf atau karakter garis bawah
- Nama variabel tidak boleh dimulai dengan angka
- Nama variabel hanya boleh berisi karakter alfanumerik dan garis bawah (Az, 0-9, dan _ )
- Nama variabel peka huruf besar/kecil (usia, Usia, dan AGE adalah tiga variabel berbeda)

> Contoh
>
> Ketentuan Penulisan nama variable
> ```py
> myvar = "John"
> my_var = "John"
> _my_var = "John"
> myVar = "John"
> MYVAR = "John"
> myvar2 = "John"
> ```

> Contoh
> 
> Nama variabel ilegal:
> ```py
> 2myvar = "John"
> my-var = "John"
> my var = "John"
> ```

`Ingat bahwa nama variabel peka terhadap huruf besar-kecil`

**Nama Variabel Multi Kata**

Nama variabel dengan lebih dari satu kata bisa jadi sulit dibaca.

Ada beberapa teknik yang dapat Anda gunakan untuk membuatnya lebih mudah dibaca:

**Camel case**

Setiap kata, kecuali yang pertama, dimulai dengan huruf kapital:

```py
myVariableName = "John"
```

**Pascal Case**

Setiap kata dimulai dengan huruf kapital:

```py
MyVariableName = "John"
```

**Snake Case**

Setiap kata dipisahkan oleh karakter garis bawah:

```py
my_variable_name = "John"
```

# Variabel Python - Menetapkan Beberapa Nilai

**Banyak Nilai ke Beberapa Variabel**

Python memungkinkan Anda untuk menetapkan nilai ke beberapa variabel dalam satu baris:

> Contoh
> ```py
> x, y, z = "Orange", "Banana", "Cherry"
> print(x)
> print(y)
> print(z)
> ```

`Catatan: Pastikan jumlah variabel sesuai dengan jumlah nilai, atau Anda akan mendapatkan kesalahan.`

**Satu Nilai ke Beberapa Variabel**

Dan Anda dapat menetapkan nilai yang sama ke beberapa variabel dalam satu baris:

> Contoh
> ```py
> x = y = z = "Orange"
> print(x)
> print(y)
> print(z)
> ```

**Membongkar Koleksi**

Jika Anda memiliki kumpulan nilai dalam daftar, tupel dll. Python memungkinkan Anda untuk mengekstrak nilai ke dalam variabel. Ini disebut membongkar.

> Contoh
> 
> Buka kemasan daftar:
> ```py
> fruits = ["apple", "banana", "cherry"]
> x, y, z = fruits
> print(x)
> print(y)
> print(z)
> ```

# Python - Output Variables

**Output Variables**

Fungsi `print()` pada python sering digunakan untuk mengeluarkan variable.

Contoh
```py
x = "Python is awesome"
print(x)
```

Dalam fungsi `print()` tersebut anda dapat menampilkan beberapa variable, dipisahkan dengan koma:

Contoh
```py
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
```

Anda juga dapat menggunakan operator `+` untuk menampilkan beberapa variable:

Contoh
```py
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
```

Perhatikan karakter spasi setelah `"Python "` dan `"is "`, tanpa spasi hasilnya akan menjadi "Pythonisawesome".

Untuk angka, karakter `+` berfungsi sebagai operator matematika:

Contoh
```py
x = 5
y = 10
print(x + y)
```

Dalam fungsi `print()` ketika anda mencoba menggabungkan string dan angka dengan operator `+`, python akan menghasilkan kesalahan:

Contoh
```py
x = 5
y = "John"
print(x + y)
```

Cara terbaik untuk menampilkan banyak variable dalam fungsi `print()` adalah dengan memisahkannya dengan koma, yang bahkan mendukung type data yang berbeda:

Contoh
```py
x = 5
y = "John"
print(x, y)
```

---
# Python - Global Variables

