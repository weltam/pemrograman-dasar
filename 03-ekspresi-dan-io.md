# Kilas Balik: Assignment

- Membosankan sekali jika kita hanya bisa mengisi variabel dengan nilai yang pasti.
- Kadang-kadang dibutuhkan hal yang lebih ekspresif. Contoh:
```py
  a = 5
  b = 2
  jumlah = a + b
```

- Kenyataannya, hal ini dapat diwujudkan pada pemrograman!
- Perintah ”a + b” biasa disebut sebagai ekspresi.

# Mengenal Ekspresi

![image](https://user-images.githubusercontent.com/242694/140295665-740a990b-67cb-4c17-b764-3dc041c90c49.png)

![image](https://user-images.githubusercontent.com/242694/140295703-9b74be6f-e6e9-4d1e-803f-60450decc07f.png)

# integer

## operasi aritmatika (binary)

- penjumlahan ( + )
- pengurangan ( - )
- perkalian ( * )
- pembagian hasil bilangan riil ( / )
- pembagiaan bulat ( // )
- sisa bagi ( % )
- pangkat ( ** )

## operator tanda (unary)

- plus ( + )
- minus ( - )

```py
import sys
import stdio
a = int(sys.argv[1])
b = int(sys.argv[2])

total =a + b 
diff = a - b 
prod = a * b 
quot = a // b 
em = a % b 
exp = a ** b

stdio.writeln(str(a) + ' +  ' + str(b) + ' = ' + str(total))
stdio.writeln(str(a) + ' -  ' + str(b) + ' = ' + str(diff))
stdio.writeln(str(a) + ' *  ' + str(b) + ' = ' + str(prod))
stdio.writeln(str(a) + ' // ' + str(b) + ' = ' + str(quot))
stdio.writeln(str(a) + ' %  ' + str(b) + ' = ' + str(rem))
stdio.writeln(str(a) + ' ** ' + str(b) + ' = ' + str(exp))

```
