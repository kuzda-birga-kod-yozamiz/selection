# Text Processing and Pipes — Qiziqarli, ketma-ket amaliy topshiriqlar

Siz katta kompaniyaning log fayllari, matn fayllari va tahlil ishlariga mas'ul bo‘ldingiz. Ishingiz — katta hajmdagi matn bilan ishlash, filtrlash, qirqish va natijani kerakli shaklda tayyorlash. Shell yordamida buni oson hal qilishingiz mumkin!
Birinchi topshiriq: Matndan ma’lumot ajratish
>Sizda xodimlar.txt fayli bor. Har bir qatorda ism va yosh yozilgan. Har bir qatordan faqat ismlarni ajratib ko‘rsating.

**Fayl namunasi:**
```nginx
Ali 25
Vali 30
Sardor 28
```

**Buyruq:**
```shell
awk '{print $1}' xodimlar.txt
```

Ikkinchi topshiriq: Matndagi so‘zni avtomatik o‘zgartirish
>xodimlar.txt faylida "Vali" so‘zini "Javlon" ga o‘zgartiring va natijani console'ga chiqaring.
```shell
sed 's/Vali/Javlon/g' xodimlar.txt
```

Uchinchi topshiriq: Pipe orqali ketma-ket amallar bajarish
>xodimlar.txt faylidan faqat ismlarni ajratib, ularni alifbo tartibida saralang.
```shell
awk '{print $1}' xodimlar.txt | sort
```
To‘rtinchi topshiriq: Natijani faylga yozish
>Ismlarni ajratib, saralang va natijani tartiblangan.txt fayliga yozib qo‘ying.
```shell
awk '{print $1}' xodimlar.txt | sort > tartiblangan.txt
```

Beshinchi topshiriq: Faylga qo‘shimcha yozish
>Yangi ismni tartiblangan.txt fayliga qo‘shing (avvalgi ma’lumot o‘chmasligi kerak).
```shell
echo "Diyor" >> tartiblangan.txt
```

Oltinchi topshiriq: Fayldan ma’lumot o‘qib ishlatish
>tartiblangan.txt faylidagi ma’lumotlarni ekranga chiqarish uchun input fayldan foydalaning.
```shell
cat < tartiblangan.txt
```

✅ Siz matn ishlash va quvurlar bilan ishlash bo‘yicha sinovlarni ham muvaffaqiyatli yakunladingiz! Endi katta hajmdagi ma’lumotni samarali boshqara olasiz.