# Praktikum4 Fardhilan Galang Priarto
# LAB 2
# Latihan 1 Program Menentukan dua bilangan terbesar
- Penjelasan x dan y sebagai int 
- Perintah If X>Y jika anga X lebih besar dari y maka akan memunculkan angka X
- Begitu juga dengan perintah else jika angka Y lebih besar dari X maka angka Y 
```
x = int(input('Masukan bilangan pertama : '))
y = int(input('Masukan bilangan kedua : '))
if x > y:
    print('Bilangan terbesar = ', x)
else:
    print('Bilangan terbesar = ', y)
```
![Gambar1](gambar/latihan1.png)
# Latihan 2 Program Mengurutkan 3 Variable dari kecil ke terbesar
- A,B,C menjadi int
- Lalu perintah dengan menggunakan metode if else kepada setiap int
```
a = int(input('Bilangan ke-1 = '))
b = int(input('Bilangan ke-2 = '))
c = int(input('Bilangan ke-3 = '))
if a < b:
    if b < c: 
        print('Urutan bilangan : ', a, b, c)
    else:
        if a < c:
            print('Urutan bilangan : ', a, c, b)
        else:
            print('Urutan bilangan : ', c, a, b)
else:
    if a < c:
        print('Urutan bilangan : ', b, a, c)
    else:
        if b < c:
            print('Urutan bilangan : ', b, c, a)
        else:
            print('Urutan bilangan : ', c, b, a)
```
![Gambar1](gambar/latihan2.png)
# LAB 3
# Latihan 1 Bertingkat
- for i in range membuat angka menjadi vertikal dari angka 0 ke 10
- for j in range membuat angka menjadi horizontal
```
for i in range(0, 10):
    for j in range(0, 10):
        product = i+j
        print(f"{product:>3}", end='')
    print()
print("Fardhilan Galang Priarto")
```
![Gambar1](gambar/latihan3.png)
# Latihan 2 Lebih kecil dari 0.5
- Fungsi uniform(x,y) digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.
```
import random
n = int(input("Masukan nilai N : "))
for i in range(n):
    a = random.uniform(0.0, 0.5)
    print("Data ke :", i+1, "=> ", a)
print('Selesai Fardhilan Galang Priarto')
```
![Gambar1](gambar/latihan4.png)

# Modul Praktikum 2
# Tugas Praktikum 2

- x,y,z sebagai int
- jika x lebih besar dari z akan muncul x
- jika y lebih besar dari z vmaka akan muncul y
- begitu sebaliknya
```
x = int(input('Masukan bilangan pertama : '))
y = int(input('Masukan bilangan kedua : '))
z = int(input('Masukan bilangan ketiga : '))
if x > y:
    if x > z:
        print('\nBilangan Terbesar = ', x)
    elif y > z:
        print('\nBilangan terbesar = ', y)
    else:
        print('\nBilangan terbesar = ', z)
```
![latihan5](https://user-images.githubusercontent.com/93815689/199686333-a19fb4b6-7a49-42d5-84e5-e276709c1383.png)

# Modul Praktikum 3
# Latihan1
```
n = int(input("Masukan nilai N : "))
for i in range(n):
    a = random.uniform(0.0, 0.5)
    print("Data ke :", i+1, "=> ", a)
```
![Gambar1](gambar/latihan4.png)

# Latihan2
- Program akan terus mencari angka terbesar tapi ketika sudah memasukkan angka 0 program akan berhenti dan menampilkan angka terbesar
```
print("Fardhilan Galang Priarto")
n=1
a=0
while n !=0:

    if n > a:
        a = n
    n = int(input("Masukan bilangan: "))
	
    if n == 0:
        break
print("Nilai terbesarnya adalah:", a)
```
![latihan6](https://user-images.githubusercontent.com/93815689/199686386-4791408e-f445-469a-ac7c-43705bf5478a.png)

# Latihan3
- buat rumus presentase keuntungan tiap bulannya 
```
n = 100000000
sum = 0
y = 0
laba = [int(0), int(0), int(n) * 0.01, int(n) * 0.01, int(n) *
    0.05, int(n) * 0.05, int(n) * 0.05, int(n) * 0.02]
for i in laba:
    sum = sum+i
    y += 1
    print('Laba bulan ke-', y, 'sebesar : ', i)
print('Total laba adalah : ', sum)

```
![latihan7](https://user-images.githubusercontent.com/93815689/199686597-b83e6756-a2cc-456a-b626-ac5d021a0609.png)
