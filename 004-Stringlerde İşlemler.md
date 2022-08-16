
## stringleri toplayabiliriz
```python
benim_adim="ahmet"
benim_soyadim="uysal"
print(benim_adim + " " + benim_soyadim)
[out] ahmet uysal
```
---
## stingler sayılmaya 0'dan başlarlar
```python
baskent="ankara"
print(baskent[0])
[out] 'a'
```
---
## -1'inci karakteri istersek eğer son karakteri bastırır
```python
örnek="bu bir örnek cümledir"
print(örnek[-1])
[out] 'r'
```
---

## starting index-stopping index-slicing
```python   
   0123
x="python test"
print(x[4:])          #sonucu 4. karakterden itibaren basmaya başlar
[out] on test

   012345678
x="python test"
print(x[2:5])      #sonucu 2. karakterden basmaya başlar ve 5. karaktere kadar yazdırır
[out] tho

   01234
x="python test"
print(x[:4])      #4. karaktere kadar olan kısımı bastırır
[out] pyth

   012345678910
x="python test"
print(x[3:11:4]   #bastırmaya 3. karakterden başlar 11. karaktere kadar 4 karakter atlayarak bastırır
[out] ht

x="python test"
print(x[::-1])   #kelimeyi tersden yazdırır
[out] tset nohtyp
```
