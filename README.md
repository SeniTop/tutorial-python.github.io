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


