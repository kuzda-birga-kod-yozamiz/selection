# Python Basics I

Savollar

### Birinchi topshiriq:  
Berilgan sonning juft yoki toq ekanligini tekshiradigan dastur yozing.  

Yechim:

```python
son = int(input("Son kiriting: "))
if son%2==0:
    print("Bu son Juft!")
else:
    print("Bu son Toq!")
```

---

### Ikkinchi topshiriq:  
Foydalanuvchi kiritgan sondan 1gacha bo‘lgan sonlarni teskari tartibda ekranga chiqaradigan dastur yozing.  

Yechim:


```python
n = int(input("Son kiriting: "))
for i in range(n, 1, -1):
    print(i)
```

---

### Uchinchi topshiriq:  
Foydalanuvchidan so‘z kiritib, shu so‘zning teskarisini chiqaring.  

Yechim:

```python
soz = input("So'z kiriting: ")
print(a[::-1])
```

---

### To‘rtinchi topshiriq:  
Foydalanuvchi kiritgan sonning raqamlar yig‘indisini toping.  

Yechim:

```python
n = input("Son kiriting: ")
yigindi = 0
for raqam in son:
    yigindi += int(raqam)

print("Yig'indi: ", yigindi)
```
