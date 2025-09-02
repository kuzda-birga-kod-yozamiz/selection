# Permission — Bosqichma-bosqich amaliy topshiriqlar

Siz kompaniya tizimida xavfsizlik va ruxsatlar bilan ishlash bo'yicha bilimlaringizni ko'rsatishingiz kerak. Diqqat va aniqlik talab etiladi!
Birinchi topshiriq:
>Sizga sir.txt nomli fayl beriladi. Ushbu faylning ruxsatlarini ko'ring.
```shell
ls -l sir.txt
```

Yaxshi! Siz fayl haqida kerakli ma'lumotlarni ko'rdingiz. Ikkinchi topshiriqqa o'tamiz.
Ikkinchi topshiriq:
>sir.txt faylini faqat egasi o'qiy oladigan qilib, ruxsatini o'zgartiring.
```shell
chmod 400 sir.txt
```

Zo'r ishladingiz! Uchinchi bosqichga o'tamiz.
Uchinchi topshiriq:
>Sizda hisobot.txt fayli bor. Bu fayl egasini root foydalanuvchisiga o'zgartiring. (Foydalanuvchi huquqlari bilan ishlayotganingizni faraz qilamiz.)
```shell
chown root hisobot.txt
```

Barakalla! Oxirgi topshiriqqa yetib keldingiz.
To'rtinchi topshiriq:
>Siz joriy papkadagi barcha fayl va kataloglar haqida kengaytirilgan ma'lumot ko'rishni xohlaysiz.
```shell
ls -l
```

✅ Siz Permission bosqichini ham a'lo darajada bajardingiz!