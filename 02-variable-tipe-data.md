Variable mempunyai tipe data

# tipe dasar

himpunan dari nilai dan himpunan dari operator terhadap nilai/data

1. bilangan bulat. integer
1. bilangan riiil. float. floating point
1. string. untaian karakter
2. boolean. nilai kebenaran (true/false)

## integer / bilangan bulat

## float / riil / floating point

Pada pemrograman, umumnya tipe data floating point dihindari karena kurang akurat. Representasi `3` pada floating point bisa jadi `2.99999999999999` atau `3.000000000000001` karena keterbatasan pada struktur penyimpanan bilangan pecahan pada komputer.

## char / karakter

Merupakan tipe data untuk merepresentasikan karakter menurut ASCII (American Standard Code for Information Interchange).
- Dalam ASCII, terdapat 128 karakter yang direpresentasikan dengan angka dari 0 sampai 127.
- Misalnya, kode ASCII untuk karakter spasi (’ ’) adalah 32, huruf ’A’ adalah 65, ’B’ adalah 66, huruf ’a’ adalah 97, dan huruf ’b’ adalah 98.

## string

untaian karakter

## boolean

true or false

# contoh program

```py
p1 = 100
p2 = p1

print(p1, p2)

x = 3.1418
y = 234.432

print(x)
print(y)

teks = 'ini adalah string'
print(teks)
```

- Perhatikan bahwa perintah p2 = p1 sama artinya dengan p2 = 100, karena p1 sendiri mengacu pada nilai 100.
- Untuk tipe data floating point, bilangan tercetak dalam notasi scientific, yaitu `3.1418 × 100` dan `2.34432 × 102`.

# tipe data komposit

- Kadang-kadang, kita membutuhkan suatu tipe data yang sifatnya komposit; terdiri dari beberapa data lainnya.
- Contoh kasusnya adalah ketika kita butuh suatu representasi dari titik. Setiap titik pada bidang memiliki dua komponen, yaitu x dan y.
-  Memang bisa saja kita mendeklarasi dua variabel, yaitu x dan y. Namun bagaimana jika kita hendak membuat beberapa titik? Apakah kita harus membuat x1, y1, x2, y2, ...? Sungguh melelahkan!
- Karena itulah Pascal memiliki suatu tipe data komposit, yaitu class.

```py
class Titik:
    def __init__(self):
        self.x = 0
        self.y = 0

p = Titik()
p.x = 5
p.y = 7

print(p.x, p.y)
```
