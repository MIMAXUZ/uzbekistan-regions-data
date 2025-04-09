
# 🌍 Viloyat, Tuman va Mahalla fuqarolar yig'inlari nomlari ma'lumotlar bazasi

Ushbu ma'lumotlar bazasi JSON, SQL CSV formatida barcha viloyatlar, tumanlar va MHF ma'lumotlari lotin, kirill va rus tillarida jamlangan umumiy ro'yxati.
Ushbu ma'lumotlar bazasi yordamida siz O'zbekiston hududagi barcha viloyat va tumanlarni, bundan tashqari MHF (Mahalla fuqarolar yig'inlari) nomlarini uch xil ko'rinishda olishingiz mumkin. Barcha ma'lumotlar to'liq ochiq kodli va istalgan foydalanuvchi o'ziga moslay olishi uchun optimal shaklga keltirilgan holatda jamlangan. 


## Qo'llab quvvatlanadigan fayl turlari
- JSON
- SQL
- XML
- PLIST (Rejada)
- YAML (Rejada)
- CSV

## Fayl tarkibiy qisimlari haqida ma'lumot
File | JSON | SQL | XML | PLIST | YAML | CSV
:------------ | :-------------| :-------------| :------------- |:-------------|:-------------|:-------------
Viloyatlar / Shaharlar | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:
Tumanlar | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:
MHF | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:

## Ma'lumotlar bazasining zaxira nusxalari
File | MySQL >= 5.6 | SQL Server >= 2017
:------------ | :-------------| :-------------
regions_mysql.sql | :white_check_mark: | N/A 
UzbekistanDB.bak | N/A | :white_check_mark: 

# Ma'lumotlar bazasi sxemasi diagrammasi

![O'zbekistonning viloyatlari, shaharlari, qishloqlari, ro'yxati ](../database_scheme.png )

## Jamlangan ma'lumotlar
Umumiy hududlar : 14 <br>
Umumiy tumanlar / shaharlar : 210 <br>
Umumiy Qishloq va Shaharchalar : 2,641+ <br>
Umumiy MFY lar : 0 <br>

Oxirgi yangilanish sanasi : 08.04.2025

## O'zgarishlar
Ko'p yangilanishlarni o'z ichiga olgan yangi versiya mavjud.

- SOATO (maʼmuriy-hududiy tuzilmalarni belgilash tizimi) qoʻshildi.
- Eskirgan **Quarters** jadvali ma'lumotlari (MSSQL zaxira nusxalarida mavjud) olib tashlandi,
- va boshqalar...

Barcha yangilanishlar va o'zgarishlar haqida to'liq ma'lumot olish uchun  **[Ushbu havolaga](https://github.com/MIMAXUZ/uzbekistan-regions-data/wiki/Update-History)** bosing.

## Eslatma
```
Ayrim tumanlar va shaharlar, mahallalar bundan mustasno bo'lishi mumkin.
Agarda MB bilan bog'liq muammo bo'ladigan bo'lsa bizga xabar berishingizni so'raymiz
```

## Hissa qo'shish
Istalgan hissa qo'shish istagida bo'lganlarni taklif qilib qolamiz.
Buning uchun siz ushbu repository ni klon qilib olasiz va o'zgarishlarni amalga oshirib push qilasiz. Va biz 
ko'rib chiqib sizni loyihaga qo'shamiz.

## Bizga qo'shiling!
<a href="https://github.com/mimaxuz/"><img alt="Github @mimaxuz" src="https://img.shields.io/static/v1?logo=github&message=Github&color=black&style=flat-square&label=" /></a> 
<a href="https://www.linkedin.com/in/mimaxuz/"><img alt="LinkedIn @mimaxuz" src="https://img.shields.io/static/v1?logo=linkedin&message=LinkedIn&color=black&style=flat-square&label=&link=https://twitter.com/mimaxuz" /></a>

## Takliflar / mulohazalar
```
Takliflar va mulohazalar mavjud bo'lgan taqdirda bizga murojat qiling
oktam[at]yaqubov[dot]info
```
