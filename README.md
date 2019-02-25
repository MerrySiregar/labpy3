# labpy3
# Latihan 1

![](https://github.com/MerrySiregar/labpy3/blob/master/Untitled1.png)

## Codingan
```import random
jumlah = int(input("Masukan Nilai N :"))
for i in range(jumlah):
    i=random.uniform(0.0,0.5)
    print("Data ke : 1 =>",i)

print("*******************")
print("Selesai")
print("*******************")
```
# Latihan 2

![](https://github.com/MerrySiregar/labpy3/blob/master/Untitled2.png)

## Codingan
```print("\nMenentukan Bilangan Terbesar")
print("\n")
max=0
while True:
    a=int(input("Masukan Bilangan :"))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar = ", max)
```

# Program 1

![](https://github.com/MerrySiregar/labpy3/blob/master/Untitled.png)

## Codingan
```a=100000000
for x in range(0,9):
        if(x>0 and x<=2):
                b=a*0
                print("laba bulan ke-",x," :",b)
        if(x>=3 and x<=4):
                c=a*0.1
                print("laba bulan ke-",x," :",c)
        if(x>=5 and x<=7):
                d=a*0.5
                print("laba bulan ke-",x," :",d)
        if(x==8):
                e=a*0.2
                print("laba bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)
```

## Sekian Terima Kasih
## Merry Siregar
## NIM 311810850
