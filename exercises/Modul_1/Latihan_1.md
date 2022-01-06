# Latihan 1

# Sebelum Memulai

Buatlah project folder dan virtual environment untuk setiap Modul. Misalkan jika kita akan mengerjakan 3 modul, buat 3 folder untuk modul tersebut.
```
---- latihan1
    |   |_env
    |   |_ latihan1_1.py
    |   |_ latihan1_2.py
---- latihan2
    |   |_env
    |   |_ latihan2_1.py
---- latihan3
    |   |_env

```

## Syntax
Sebelumnya, sangat disarankan untuk membaca aturan penulisan sintaks pada python dengan membaca tautan berikut.
[Bahasa Indonesia](https://jagongoding.com/python/dasar/aturan-sintaks-python/)
[English](https://www.studytonight.com/python/python-syntax-and-example)




## Menampilkan Output, Variabel dan Input. Hello World

Pada Programming dan matematika, variable adalah tempat kita menyimpan suatu data atau nilai. Misalkan kita memiliki fungsi berikut.

```
x = 1
```

Pada fungsi di atas, **x** merupakan **variabel** dan **1** adalah **nilai**.

Salah satu fungsi terpenting di python adalah fungsi **print**.
**print** berfungsi untuk mencetak variabel pada terminal output.

Contoh:
- Buat file bernama latihan1_1.py di dalam direktori project.
- Masukkan code berikut:
```python3
w = "Hello World but from variable"
print("Hello World")
print(w)
```
- Masukkan command berikut dari terminal:
```
python3 latihan1_1.py
```

Pada terminal, akan muncul kalimat ini:
```
Hello World
Hello World but from variable
```

### Penjelasan
- Masukkan code berikut:
```python3
w = "Hello World but from variable"
print("Hello World")
print(w)
```

Pada code di atas, variabel w akan diisi oleh nilai "Hello World but from variable".
Setelah itu, kita menampilkan nilai "Hello World" tanpa dimasukkan ke dalam variable.
Setelah itu kita menampilkan isi variabel w

Lalu, kita memanggil script latihan1_1.py menggunakan command
```
python3 latihan1_1.py
```


-----------
Pada python, kita dapat mengganti isi variabel sesuai keinginan kita.
Ganti isi file latihan1_1.py dengan

```python3
w = "Hello World but from variable"
w = "Goodbye World"
print("Hello World")
print(w)
```
Pada code di atas, kita mengubah isi variabel w yang tadinya berisi nilai "Hello World but from variable" menjadi "Goodbye World"

Jalankan script di atas dan kita akan mendapatkan
```
Hello World
Goodbye World
```
-----
Selanjutnya, kita dapat menjumlahkan dua kalimat / kata. Ubah isi file latihan1_1.py menjadi
```
text_1 = "Hello "
text_2 = "World"
full_text = text_1 + text_2
print(full_text)
print(text_1 + text_2)
print("Hola" + " " + text_2)
print(text_2 + text_1)
```
code di atas akan menghasilkan output
```
Hello World
Hello World
Hola World
WorldHello
```
Dari code di atas, kita bisa melihat bahwa:
- Kita bisa menaruh teks dalam variabel dan menyambung teks tersebut dengan variabel lain.
- Kita bisa menggabungkan text tanpa harus memasukkan teks ke dalam variabel.
- Kita bisa menggabungkan teks sebagai argumen fungsi print (baris 6-7)

-----------------
#### Fungsi Input
Kita juga dapat membaca input dari terminal menggunakan fungsi **input()**
```python3
w = input("Masukkan input : ")
print(w)
x = input()
print(x)
```
akan menghasilkan
```
Masukkan input : pop
pop
q
q
```

- "Masukkan input : " pada argumen input menjadi prompt pada terminal
- input dimasukkan pada variabel w dan dicetak


## Latihan

Buatlah program yang membaca input user dan mencetaknya pada terminal.
Input yang dibutuhkan adalah:
    - nama
    - alamat
    - umur
    - email

Contoh Input dari terminal:
```
nama : John Doe
alamat : Jakarta
umur : 20
email : johndoe@gmail.com
```

Output
```
Name: John Doe, Address: Jakarta
Age: 20, Email: johndoe@gmail.com
```


