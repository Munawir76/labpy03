##Latihan1.py

n = int(input("Masukan nilai N :"))
from random import random
a = random()

jumlah = n+1
start = 1
stop = jumlah
step = 1
for i in range(start, stop, step):
    print("data ke :", i,"=>", (a))
print("Selesai")


##Latihan2.py

a = 1
max = 0
while a !=0:
    if a > max:
        max = a
    a = int(input("Masukkan Bilangan :"))
    if a == 0:
        break
print("Nilai terbesar adalah :", max)


##Program1.py

a = 100000000
b = 0
c = 0
range = [int(0), int(0), int(a) * .1, int (a) * .1, int(a) * .5, int(a) * .5, int(a) * .5, int(a) * .2,]
for i in range :
    b = b+i
    c+=1
    print("Laba bulan ke-",c,"sebesar:", i)
print("Total laba adalah:", b)