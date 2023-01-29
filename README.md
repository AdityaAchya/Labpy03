# Labpy03
Repository ini dibuat untuk memenuhi tugas pertemuan 7- Bahasa Pemrograman

Nama    :   Aditya Achya Ananta Nur

NIM     :   312210714

Kelas   :   TI.22.C.9

## Latihan1
* Tampilkan **n** bilangan acak yang lebih kecil dari 0.5
* Nilai **n** di isi pada saat runtime
* Anda dapat mengkombinasikan **while** dan **for** untuk menyelesaikannya
* Gunakan fungsi *random()* yang dapat di import terlebih dahulu
-----------

### Latihan1.py

![1](https://user-images.githubusercontent.com/123864099/215340203-9f6b4ddf-c639-4614-8b70-3c628acca98c.PNG)


```Python
print ("Masukan Nilai N: 5")
import random
jumlah = 5
a = 0
for x in range(jumlah):
    i = random.uniform(.0,.5)
    a+=1
    print("Data Ke : ",a,"==>",i)
print("Selesai")
```
### Hasil

![2](https://user-images.githubusercontent.com/123864099/215340222-eacc95b1-7e2b-4de9-a8ff-7c6012162710.PNG)

## Latihan2

* Buat program untuk menampilkan bilangan **Terbesar** dari **n** buah data yang diinputkan.
* Masukan angka *0* untuk berhenti.
-----------

### Latihan2.py

![3](https://user-images.githubusercontent.com/123864099/215340317-ccb0016c-055a-4239-8066-f7513d6287a7.PNG)

```Python
max=0
while True:
    a=int(input("Masukan Bilangan : "))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar adalah :",max)
```
### Hasil

![4](https://user-images.githubusercontent.com/123864099/215340390-85f71b72-71dc-4a3d-9fe3-4e7b1f79fdc4.PNG)

-----------
## Program1
* Buat repository baru **labpy03** 
* Masukkan *latihan1.py* dan *latihan2.py* ke dalam repository. 
* Buat program sederhana dengan perulangan: *program1.py*

Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

* Buat file **README.md**, yang berisi penjelasan alur algoritma program *latihan1.py*, *latihan2.py*, dan *program1.py* beserta screenshot hasilnya.
* Kemudian commit dan push ke repository (github) 
* Kirim url repository ke classroom. 
-----------

### Program1.py

![5](https://user-images.githubusercontent.com/123864099/215340500-98c3cfe4-929c-4a21-9b7c-3f0e32ab53f6.PNG)

```Python
a=1000000000
for x in range(1,9):
    if(x>=1 and x<=2):
        b=a*0
        print("Laba bulan ke-",x, " : ",b)
    if(x>=3 and x<=4):
        c=a*0.1
        print("Laba bulan ke-",x, " : ",c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("Laba bulan ke-",x, " : ",d)
    if(x==8):
        e=a*0.2
        print("Laba bulan ke-",x, " : ",e)
total = b+b+c+c+d+d+e
print("\nTotal : ",total)
```
### Hasil

![6](https://user-images.githubusercontent.com/123864099/215340547-9854dfab-dee6-438f-ba68-a3e149c898b0.PNG)

-----------

Sekian yang dapat saya sampaikan.

## TERIMA KASIH
### ADITYA ACHYA ANANTA NUR - 312210714 - TI.22.C. - TEKNIK INFORMATIKA - UNIVERSITAS PELITA BANGSA
