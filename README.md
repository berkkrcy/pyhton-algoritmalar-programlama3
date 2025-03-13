degisken1 = 10
degisken2 = 20
degisken3 = 35
degisken4 = 45
berk="eyyberk"
x = 5
y = "Merhaba Dünya"
print(degisken1)
print(degisken2)
print(degisken3)
print(degisken4)
print(berk)
print(x)
print(y)

a = 10
print(type(a), a)#type komutu değişkenin tipini verir

b = 20.5
print(type(b), b)
print (type(degisken1)); print ("degisken 1 kodunun tipi")
# int veri tipinden float'a çevirim işlemi örneği

y = 10

x = float(y)

print(x, type(x))

# float veri tipinden int veri tipine çevirim örneği

y = 10.74

x = int(y)

print(x, type(x))

# Boolean (True / Doğru - False / Yanlış) Değişken tanımlaması

d = True # 1 - Aktif
e = False # 0 - Pasif

print(d)
print(type(e))


# List - liste --> Dizi tanımlaması

liste = [1, 2, 3, 4, 5]

print(type(liste), liste)

# Demet - Tuple Veri Tipi Tanımlaması

demet = (1, 2, 3, 4, 5)

print(type(demet), demet)


notlar = {
    "Ali": 85,
    "Veli": 90,
    "Ayşe": 78
}

notlar["Fatma"] = 95 # yeni öğrenci ekleme yöntemi
notlar["Ali"] = 88 # mevucttaki öğrencinin notunu günleme işlemi

print(notlar)


print(notlar.keys())
print(notlar.values())
print(notlar.items())

     
kodyazanlar = {"Ahmet", "Mehmet", "Ayşe"}
kodyazmayanlar = {"Ayşe", "Fatma", "Veli"}

ortak = kodyazanlar.intersection(kodyazmayanlar)
print("Kafasına Göre Takılan Arkadaşlar: ", ortak)

kod_yazmayanlar = kodyazmayanlar.difference(kodyazanlar)
print("Kod çalışması yapmayanlar: ", kod_yazmayanlar)

imzalistesi = kodyazanlar.union(kodyazmayanlar)
print("Sınıf İmza Listesi: ", imzalistesi)
giris = input("Bir Sayı Giriniz:")
try:
    numara = float(giris)
    print("Girilen Sayı: ", numara)
except ValueError:
    print("Hatalı Bilgi Girişi Yaptınız Lütfen Tekrar Deneyiniz!")


    

import random

rastgele = random.random() # random fonksiyonu bize 0 ile 1 arasında rastgele bir sayı üreten fonksiyondur.

print("Rastgele Gelen Deger: ", rastgele)
import random

rastgele2 = random.randint(1, 100) # randint fonksiyonu bize istediğimiz aralıkta rastgele bir sayı üreten fonksiyondur.

print("Rastgele Gelen Deger: ", rastgele2)
