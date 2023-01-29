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
