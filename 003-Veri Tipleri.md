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
## Kullanıcıdan Input Alırken
```python
kullanıcı_yasi=input("Lütfen Yasinizi Giriniz: ") #sonuç default olarak str cinsinden verilir int'e çevirmemiz gerekir
[out] Lütfen Yasinizi Giriniz: 
```
---
## Fonksiyonlar 
#. koyup "tab"a basarsak çalıştırılabilecek fonksiyonları gösterir
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
---
## STRING'I INT'E ÇEVIRME
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
---
## STRING'I FLOAT'A ÇEVİRME
```python
x=input("x: ")
[out] x: 3.14
```
```python
float(x)=x
type(x)
[out] float
```
---
#len() kelimenin kaç karakterden oluştuğunu söyler, boşluğuda karakterden sayar
```python
benim_adim="ahmet uysal"
len(benim_adim)
[out] 11
```
