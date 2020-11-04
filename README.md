# LatihanPython
# Tugas Ini Untuk Melengkapi Pertemuan 5 & 6 <br>

**Nama : Syahru Raga Ramdhani** <br>
**Nim : 312010354** <br>
**KELAS : TI.20.A.2** <br>
**TUGAS : BAHASA PEMOGRAMAN** <br>

## DAFTAR ISI <br>

| NO | Description | Link |
| ----- | ----- | ---- |
| 1. | Pertemuan 5 - Latihan| [silahkan klik](#pertemuan-5---latihan) |
| 2. | Pertemuan 6 - Lab 1 | [silahkan klik](#pertemuan-6---lab-1) |
| 3. | Pertemuan 6 - Lab 1-2 | [silahkan klik](#pertemuan-6---lab-1-2) |
| 4. | Pertemuan 6 - Lab 2 | [silahkan klik](#pertemuan-6---lab-2) |
### Pertemuan 5 - Latihan

Pada pertemuan 5 bahasa pemograman, saya diberi soal untuk latihan oleh Dosen untuk membuat Aplikasi Biodata dengan python (Seperti gambar di bawah ini:)
![image](https://user-images.githubusercontent.com/73059731/98119094-b8fb9300-1ede-11eb-9d32-9bda95c609df.png)
Saat ini saya akan menjelaskan hasil dari tugas tersebut. <br>
Berikut *source code* nya atau klik berikut ([latihan 5](biodata.py)): <br>
``` python
print ("  ====================================")
print ("       Latihan Biodata Syahru       ")
print ("  ====================================")
#variabel
namalengkap   = input ("Masukan Nama Lengkap Anda: ")
panggilan     = input ("Masukan Nama Panggilan: ")
nim           = input ("Masukan Nim Anda: ")
ttl           = input ("Masukan Tempat Tanggal Lahir Anda: ")
umur          = input ("Masukan umur Anda: ")
telepone      = input ("Masukan No Telpon Anda: ")
alamat        = input ("Masukan Alamat Anda: ")

#Menampilkan Inputan User
print ("\nAssalamu'alaikum Wr.Wb.")
print ("Let me introduce my self. My name is",namalengkap,\
", but you can call me",panggilan,". My NIM is ",nim,\
". I was born in",ttl,\
"and I am ",umur,"years old",\
"i am very glad if you want to invite my house in",alamat,\
". So, don't forget to call me before with the number",telepone,".")
```

* Berikut penjelasan :<br>
``` python
print("please your full name : ")
```
source code fiatas berfungsi untuk mencetak hasil / output berupa " **Masukan Nama Anda :** ". <br>
 Untuk menampilkan output string, saya menggunakan *tanda petik dua* didalam fungsi print(), sedangkan jika saya ingin menampilkan output / hasil berupa angka / interger saya tidak perlu menggunakan *tanda petik dua*. Contohnya:
 ``` python 
 print("masukan nama anda ...")
print(4646)
```
<br>(Seperti gambar berikut ini) <br>
![image](https://user-images.githubusercontent.com/73059731/98119532-4b039b80-1edf-11eb-927c-0db9d5d52014.png) <br>
* Untuk source code berikutnya adalah inputan atau membuat variable. Seperti syntax dibawah ini:

``` python
nama= input()
```
Keterangan : <br>
1. Variable adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan. Yang berfungsi sebagai variable dalam source code diatas adalah **fullname** . <br>

2. Fungsi **input()** adalah untuk memasukan nilai dar layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter *(newline)* <br>
![image](https://user-images.githubusercontent.com/73059731/98124800-3d9ddf80-1ee6-11eb-89c6-8ef96155c72b.png) <br>
Pada gambar diatas, hasil dari inputan tersebut berwarna *putih* <br>
* Untuk memasukan perintah lain seperti *Nama, NIM, Tempat Lahir, Umur, No Telpon,* mengikuti perintah yang sama seperti memasukan *fullname* <br>

Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen. <br>
Output pertama yang di minta Dosen adalah menampilkan salam, yaitu dengan mengetikkan syntax / source code berikut : 
``` python
print("\n Asalammualaikum.")
```
Keterangan :
1. Fungsi **\n** pada source code diatas adalah untuk memberi baris baru / enter / *newline*
2. Fungsi print() seperti dijelaskan pada point **Output** diatas
Hasil source code diatas adalah seperti gambar dibawah ini : <br>
![image](https://user-images.githubusercontent.com/73059731/98124456-cbc59600-1ee5-11eb-9972-e2825eff2e23.png) <br>
* Langkah terakhir menampilkan semua hasil dari inputan diatas. Dengan mengetikan source code berikut : <br>
``` python
print ("Let me introduce my self. My name is",namalengkap,\
", but you can call me",panggilan,". My NIM is ",nim,\
". I was born in",ttl,\
"and I am ",umur,"years old",\
"i am very glad if you want to invite my house in",alamat,\
". So, don't forget to call me before with the number",telepone,".")
```
Keterangan : <br>
* Fungsi huruf **f** pada perintah *print(f"....")* adalah fungsi print atau bisa memudahkan program dalam mencetak statement dalam suatu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan symbol koma ( , ) atau plus ( + ) <br>
* Sedangkan fungsi {} pada output tersebut menampilkan hasil variable <br>
Hasil dari output tersebut seperti berikut : <br>
![image](https://user-images.githubusercontent.com/73059731/98125535-2c090780-1ee7-11eb-97ae-b43b858137cc.png)
<br>
<br>
<br>

### Pertemuan 6 - lab 1

Pada halaman ini Saya di berikan tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan bahasa pemograman python. Berikut source yang di berikan oleh Dosen [lab 1](lab1.py) <br>
![image](https://user-images.githubusercontent.com/73059731/98128529-9ec7b200-1eea-11eb-9278-66eed691f78d.png)
``` python
#Penggunaan End
print("A", end="")
print("B", end="")
print("C", end="")

print()
print("X")
print("Y")
print("Z")

#Penggunaan Separator
w,x,y,z=10,15,20,25
print(w,x,y,z)
print(w,x,y,z,sep=",")
print(w,x,y,z,sep="")
print(w,x,y,z,sep=":")
print(w,x,y,z,sep="-----")
```
Oke, kali ini saya menjelaskan materi yang dijelaskan oleh Dosen. <br><br>

* Penggunaan END
Penggunaan end digunakan untuk menambahkan kata yang dicetak di akhir baris

``` python
print("A", end="")
print("B", end="")
print("C", end="")
```

> Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini : <br>
``` python 
print()
```
> Syntax dibawah ini digunakan untuk menampilkan output berupa string
``` python
print("X")
print("Y")
print("Z")
```
Hasil dari source code terseut seperti gambar di bawah ini: 
![image](https://user-images.githubusercontent.com/73059731/98129441-b5223d80-1eeb-11eb-85ad-5feb87184144.png)

* Pengertian separaktor <br>
Sepaktor adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda sepasi <br><br>
> Pendeklarasian beberapa variable berserta nilainya
``` python
w,x,y,z=10,15,20,25
```
> Menampilkan hasil setiap variable tiap-tiap variable
``` python
print(w,x,y,z)
```
> Menampilkan hasil variable dari tiap-tiap variable menggunakan pemisah , (koma)
``` python
print(w,x,y,z,sep=",")
```
> Menampilkan hasil variable dari tiap-tiap variable tanpa menggunakan pemisah
``` python
print(w,x,y,z,sep="")
```
> Menampilkan hasil variable dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)
``` python
print(w,x,y,z,sep=":")
```
> Menampilkan hasil variable dari tiap-tiap variable dengan menggunakan pemisah ----
``` python
print(w,x,y,z,sep="-----")
```

Hasil dari syntax / source code diatas adalah seperti berikut iniL: <br>
![image](https://user-images.githubusercontent.com/73059731/98129844-3083ef00-1eec-11eb-857a-2e238d38f640.png)
<br>
<br>
<br>
### Pertemuan 6 - lab 1-2 
* String format <br>
String formatting atau pemformatan string memungkinkan kita menyuntikkan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.<br>
Penggunaan pada source yang di berikan Dosen sebagai berikut : <br>
``` python
# string format 1
print(0, 10 ** 0)
print(1, 10 ** 1)
print(2, 10 ** 2)
print(3, 10 ** 3)
print(4, 10 ** 4)
print(5, 10 ** 5)
print(6, 10 ** 6)
print(7, 10 ** 7)
print(8, 10 ** 8)
print(9, 10 ** 9)
print(10, 10 ** 10)

# string format 2
print('{0:>3}{1:>16})'.format(0, 10 ** 0))
print('{0:>3}{1:>16})'.format(1, 10 ** 1))
print('{0:>3}{1:>16})'.format(2, 10 ** 2))
print('{0:>3}{1:>16})'.format(3, 10 ** 3))
print('{0:>3}{1:>16})'.format(4, 10 ** 4))
print('{0:>3}{1:>16})'.format(5, 10 ** 5))
print('{0:>3}{1:>16})'.format(6, 10 ** 6))
print('{0:>3}{1:>16})'.format(7, 10 ** 7))
print('{0:>3}{1:>16})'.format(8, 10 ** 8))
print('{0:>3}{1:>16})'.format(9, 10 ** 9))
print('{0:>3}{1:>16})'.format(10, 10 ** 10))
```
<br>
Saat ini saya akan menjelaskan satu persatu dari syntax yang diberikan oleh Dosen <br>
Tugas yang di berikan oleh Dosen bisa di temukan dengan link berikut : [lab1-2](https://github.com/syahruraga05/Latihan2/blob/master/lab1-2.py)

1. **String Format 1** <br><br>
Pada syntax / source code string format 1 akan menampilkan output berupa 2 outputan. <br>
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan sebelah kanan akan menampilkan Oprasi Aritmatika Pangkat. <br>
Dengan ketentuan sebagau berikut, oprasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [Bintang dua]) <br>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10. Dengan output sebagai berikut : <br>

![image](https://user-images.githubusercontent.com/73059731/98131114-8ad17f80-1eed-11eb-93a5-942b4e541e3a.png) <br><br>

2. **String Format 2** <br><br>
Pada syntax / source code string format 2 akan menampilkan output berupa 2 output'an juga (Seperti string format 1, yaitu kanan dan kiri) <br>
Dengan ketentuan sebagai berikut : <br>
> > Alignment, padding, dan precesion dengan **.format()** dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Contoh lain seperti berikut :
``` python
print('{0:8} | {1:9}'.format('sepatu','Jumlah'))
print('{0:8} | {1:9}'.format('dalas', 3.))
print('{0:8} | {1:9}'.format('NB',10))
```
Hasil dari source code contoh di atas akan seperti berikut : <br>
![image](https://user-images.githubusercontent.com/73059731/98132788-61b1ee80-1eef-11eb-9a28-9b0c753b6410.png) <br><br>
> Secara default, **.format()** menggunakan rata text kiri, angka ke kanan. <,^, atau > untuk perataan kiri, tengah , atau kanan. Contoh lain dari penggunaan **.format()** sebagai berikut : <br>
``` python
print('{:<30}{:^30}{:>30}'.format('Kiri','Tengah','Kanan'))
print('{:<30}{:^30}{:>30}'.format(15,33,51))
```
Hasil dari source code contohdiatas akan muncul seperti ini : <br>
![image](https://user-images.githubusercontent.com/73059731/98133328-0a604e00-1ef0-11eb-968c-5ca4a2714103.png)
<br>
<br>
Hasil string format 2 adalah : <br>
![image](https://user-images.githubusercontent.com/73059731/98133580-53b09d80-1ef0-11eb-9506-f04d1dbee909.png)
<br>
<br>

### Pertemuan 6 - Lab 2

* Konversi Nilai Variable
Untuk pembahasan terakhir, kali ini akan myenyelesaikan tugas Lab 2 dari Dosen, yaitu Konversi Nilai Variable <br>
Tugas yang di berikan oleh Dosen adalah seperti gambar dibawah ini atau bisa di temukan dengan link berikut : ([lab 2](lab2.py))
``` python
a=int(input("Masukkan Nilai A : "))
b=int(input("Masukkan Nilai B : "))
print("Variable A : ",a)
print("Variable B : ",b)
print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#Konversi nilai variable
a=int(a)
b=int(b)
print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
<br>
Hasil dari source / code diatas : <br>

![image](https://user-images.githubusercontent.com/73059731/98135163-1baa5a00-1ef2-11eb-9687-1ad0c0e757b4.png)
<br>
<br>
