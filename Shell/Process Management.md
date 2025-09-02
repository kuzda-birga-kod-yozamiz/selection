# Process Management — Qiziqarli Syujetli Amaliy Topshiriqlar

Siz katta kompaniya serveriga administrator sifatida ulanib oldingiz. Lekin serverda muammoli jarayonlar ko‘paygan. Sizdan ularni to‘g‘rilash, kuzatish va boshqarish so‘raladi. Ehtiyot bo‘ling, noto‘g‘ri harakat qilsangiz, tizim ishlashdan to‘xtashi mumkin!
Birinchi topshiriq: Jarayonlarni kuzatish
>Serverda ayni damda qaysi jarayonlar ishlayotganini ko‘ring.
```shell
ps aux
```
Ajoyib! Siz serverdagi barcha faol jarayonlarni ko‘rdingiz. Davom etamiz.
Ikkinchi topshiriq: Server holatini real vaqt kuzatish
>Jarayonlar va resurslardan foydalanish holatini jonli ko‘rinishda kuzating.
```shell
top
```

Endi siz server qanday ishlayotganini ko‘rib turibsiz. Keyingi vazifa biroz xavfliroq!
Uchinchi topshiriq: Muammoli jarayonni o‘chirish
>Faraz qilaylik, firefox jarayoni serverda ishlamoqda va bu serverni sekinlashtiryapti. Uni topib, o‘chiring. (Jarayon nomini topgach, uning PID raqamini ishlatishingiz kerak.)
```shell
ps aux | grep firefox
kill PID
```

Eslatma: PID o‘rniga topilgan real jarayon raqami yoziladi.
To‘rtinchi topshiriq: Uyqudagi dastur
>Bash orqali 10 soniyaga uxlaydigan jarayon yarating.
```shell
sleep 10
```

Jarayon ishlamoqda... Ammo, uni keyingi topshiriqda boshqaramiz.
Beshinchi topshiriq: Jarayonni background rejimida ishlatish
>10 soniyali uxlaydigan jarayonni fonda ishga tushiring.
```shell
sleep 10 &
```

Zo‘r! U fonda ishlamoqda. Endi uni qayta oldinga olib chiqamiz.
Oltinchi topshiriq: Jarayonni foreground rejimiga qaytarish
>Backgroundda ishlayotgan jarayonni oldinga qaytaring.
```shell
fg
```
✅ Siz Process Management sinovlarini ham a'lo darajada bajardingiz! Endi tizim xavfsiz va barqaror ishlaydi!