# BelajarPython
Kumpulan file untuk belajar python

# Indeks
  - [Menginstall Requirements](#Requirements)
  - [Memulai Latihan](#Latihan)

## Requirements

### Linux
OS linux kebanyakan sudah menyediakan program python. Untuk mengecek versi python yang terinstall, buka terminal menggunakan (CTRL + Shift + T) dan ketik.

```
python --version
```
atau
```
python3 --version
```
Jika python3 belum terinstall. Silahkan ikuti petunjuk [ini](https://realpython.com/installing-python/#how-to-install-python-on-linux).

### MacOs

Seperti linux, MacOs kebanyakan sudah terinstall python. Hanya saja versi yang dibutuhkan (python 3) belum terinstall. Untuk menginstall python3 di MacOs [klik tautan](https://docs.python-guide.org/starting/install3/osx/)

### Windows

Pada umumnya, windows belum memiliki native python. Akan tetapi python bisa diinstall melalui Microsoft Store, Full Installer atau menggunakan Windows Subsystem for Linux.

Untuk menginstall python3 pada windows, silahkan baca [link ini](https://realpython.com/installing-python/#how-to-install-python-on-windows) dan [ini](https://docs.microsoft.com/en-us/windows/python/web-frameworks).

Cara terbaik adalah untuk menggunakan dual OS atau mengganti windows anda dengan linux.


### pip
Pip adalah module untuk menginstall module-module lain yang ada di python. Pip adalah salah satu bagian penting pada pemrograman python. 

Untuk menginstall pip pada linux. Silahkan baca [link ini](https://pip.pypa.io/en/stable/installation/)

### Virtual Environment
Saat mengembangkan program python. Sangat dianjurkan untuk menggunakan virtualenvironment.
Virtual Environment adalah modul/software untuk memanage versi python yang digunakan dan requirements module yang dibutuhkan project/program yang sedang dikembangkan.

Tanpa virtual environment, akan terjadi dependencies conflict antar program yang dibuat.

Misalkan kita memiliki dua project yang berbeda, yaitu project A dan project B.

Project A membutuhkan module request versi 1 dan menggunakan python versi 3.6
Project B membutuhkan module request versi 2 dan menggunakan python versi 3.6

Tanpa virtual environment, saat kita memulai project B, module request yang terinstall akan berubah versi menjadi versi 2, sehingga akan memuncul kan conflict / Error saat kita menjalankan Project A.

Dengan virtual environment, kita bisa bebas memilih versi module dan python yang akan digunakan karena tidak akan menimbulkan conflict dengan project lain.

**Tanpa Virtual Environment**
```
--|Project A
     |_main.py
--|Project B
     |_main.py
```
**Dengan Virtual Environment**
```
--|Project A
     | env
     |  |_ bin
     |      |_ python3
     |_main.py
--|Project B
     | env
     |  |_ bin
     |      |_ python3
     |_main.py
```

#### [Mengapa kita membutuhkan virtual environment](https://www.petanikode.com/python-virtualenv)

#### [Menginstall Virtual Environment](https://virtualenv.pypa.io/en/latest/installation.html)

Setelah virtual environement terinstall. Buat virtual environment dengan membuka terminal pada direktori program python dengan mengetik.
```
virtualenv -p python3 env
```

Gunakan versi python yang dibutuhkan. Dan aktifkan virtual environment dengan command
```
source env/bin/activate
```

Setelah terinstall, prompt terminal akan berubah dari
```
mfrszk@throbbinWilliams:~/Mengajar/python
```
menjadi
```
(env) mfrszk@throbbinWilliams:~/Mengajar/python$ 
```



## Latihan
