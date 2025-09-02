# File Manipulation I

Siz FAANG kompaniyalaridan biriga kirish suhbatining navbatdagi bosqichidasiz. Endi fayllarni tahrirlash va manipulyatsiya qilish bo‘yicha bilimlaringiz sinovdan o‘tkaziladi. Tayyormisiz? Unda boshladik!
Birinchi topshiriq:
>Sizga data.txt fayli beriladi. Bu fayl ichidagi barcha ma’lumotlarni console'ga chiqaring.

``` shell
cat data.txt
```

Tabriklayman! Siz ikkinchi topshiriqqa o‘tdingiz.
Ikkinchi topshiriq:
>data.txt faylining faqat birinchi 3 qatordagi ma'lumotlarni ko‘rsating.
```shell
head -n 3 data.txt
```

Zo‘r ishladingiz! Endi uchinchi bosqichga o‘tamiz.
Uchinchi topshiriq:
>data.txt faylining oxirgi 2 qatordagi ma’lumotlarni ko‘rsating.
```shell
tail -n 2 data.txt
```

Barakalla! Siz keyingi sinovga tayyorsiz.
To‘rtinchi topshiriq:
>data.txt faylida har bir qatordan faqat 2-chi ustunni ajratib ko‘rsating. So‘zlar bo‘sh joy bilan ajratilgan deb hisoblanadi.
```shell
cut -d' ' -f2 data.txt
```

Ajoyib! Demak, keyingi sinov biroz murakkabroq.
Beshinchi topshiriq:
>data.txt faylidagi barcha qatordagi so‘zlarni alifbo tartibida saralang.
```shell
sort data.txt
```

Tabriklayman! Oxirgi topshiriqga yetib keldingiz.
Oltinchi topshiriq:
>data.txt faylidagi takroriy qatordan qutuling, ya’ni faqat noyob qatordan iborat ro‘yxat chiqaring.
```shell
uniq data.txt
```

✅ Tayyor! Siz bu bosqichni ham muvaffaqiyatli yakunladingiz!