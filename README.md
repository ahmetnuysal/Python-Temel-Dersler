# Python-Temel
--TEMEL PYTHON KONULARI VE ÖRNEKLERİ İÇERİR--
- [Hello World](#Hello-World)
- [Matematiksel İşlemler](#Matematiksel-İşlemler)
  - [Toplama](#Toplama)
  - [Çıkartma](#Çıkartma)
  - [Çarpma](#Çarpma)
  - [Bölme](#Bölme)
  - [Üstlü](#Üstlü)
  - [Mod](#Mod)
  - [Örnekler](#Örnekler)
- [Veri Tipleri](#Veri-Tipleri)
  - [Kullanıcıdan Input Almak](#Kullanıcıdan-Input-Almak)
  - [Fonksiyonlar](#Fonksiyonlar)
  - [String'i Int'e Çevirme](#String'i-Int'e-Çevirme)
  - [String'i Float'a Çevirme](#String'i-Float'a-Çevirme)
  - [len()](#len())
- [Stringlerde İşlemler](#Stringlerde-İşlemler)
- [Listeler](#Listeler)
- [İç İçe Listeler](#İç-İç-Listeler)
- [Sözlükler](#Sözlükler)
- [Set'ler](#Set'ler)
- [Tuple](#Tuple)
- [Boolean](#Boolean)
- [If Koşulu](#If-Koşulu)
- [For Döngüsü](#For-Döngüsü)
- [While Döngüsü](#While-Döngüsü)
- [Fonksiyonlar](#Fonksiyonlar)
  - [Fonksiyonlarda Girdi Almak](#Fonksiyonlarda-Girdi-Almak)
  - [Fonksiyonlarda Çıktı Almak](#Fonksiyonlarda-Çıktı-Almak)
  - [Args Kwargs](#Args-Kwargs)
  - [Map Filter Lambda](#Map-Filter-Lambda)
  - [Scope](#Scope)
  - [Hata Mesajı](#Hata-Mesajı)
  - [Class ve Inıt Methodu](#Class-ve-Inıt-Methodu)
  - [Inherıtance](#Inherıtance)
  - [Polymorphism](#Polymorphism)

# Hello World

``` python
print("Hello world")
```

# Matematiksel İşlemler

> ## Toplama

```python
print(3+5)
```

> ## Çıkartma
```python
print(5-2)
```

> ## Çarpma 
```python
print(3*5)
```

> ## Bölme
```python
print(10/2)
[out] 5.0 
```

> ## Üstlü
```python
print(2**3)
[out] 8 
```

> ## Mod  
```python
print(10%3)
[out] 1
```

> ## Örnekler
```python
KullaniciYasi=15    #Kullanıcı adını tanımlıyoruz
print(KullanıcıYasi * 3)
[out] 45
```

```python
yari_cap=10
dairein_cevresi=2*3.14*yari_cap  #Yarı çapı yukarda tanımladığımız için direkt yarı çap diyebiliriz
print(dairenin_cevresi)
[out] 62.80000004
```

# Veri Tipleri

* int (integer) : Tam Sayı
* float : Kesirli Sayı
* str (sting) : Kelime
---
```python
x=10
y=20
sonuc=x/y
print(sonuc)
[out] 0.5
```
```python
type(sonuc) #type komutu sonucun türünü söyler
[out] float
```
---
> ## Kullanıcıdan Input Alırken
```python
kullanıcı_yasi=input("Lütfen Yasinizi Giriniz: ") #sonuç default olarak str cinsinden verilir int'e çevirmemiz gerekir
[out] Lütfen Yasinizi Giriniz: 
```

> ## Fonksiyonlar 
! . koyup "tab"a basarsak çalıştırılabilecek fonksiyonları gösterir
```python x="merhaba"
print(x.captalize())  #captalize kelimenin ilk harfini büyük yazdırır
[out]Merhaba
```
```python
x="34"
x.endswitch(2)   #endswitch(2) kelimenin sonu 2 ile mi bitiyor kontrol eder
[out] false
```
```python
benim_adim="ahmet"
benim_adim.islower()  #islower bütün harfler küçük mü kontrol eder
[out]True
```
```python
x="MerHaBA"
x.lower()   #lower bütüh harfleri küçük yazar
[out]merhaba 
```

> ## String'i Int'e Çevirme
```python
x=input("x değerini giriniz: ")
[out] x değerini giriniz: 7
```
```python 
type(x)
[out] str
```
```python
x=int(x)  #x değerini intiger'a çeviri
type(x)
[out] int
```

> ## String'i Float'a Çevirme
```python
x=input("x: ")
[out] x: 3.14
```
```python
float(x)=x
type(x)
[out] float
```

> ## len()
```python
benim_adim="ahmet uysal"
len(benim_adim)  #len() kelimenin kaç karakterden oluştuğunu söyler, boşluğuda karakterden sayar
[out] 11
```

