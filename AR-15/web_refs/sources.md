# AR-15 (LMT R20 RAHE Reference, CQBMLK143PW-MARS-EST) — источники референсов

Правила: все скачанные файлы — только изображения и PDF, каждый источник лежит в своей подпапке. Ничего из этих папок не запускать.
«Сторона» определена по положению дула: дуло вправо — правая сторона оружия; проверено по окну выброса.
Файлы Wikimedia скачаны как миниатюры 3840 px (сервер миниатюр Wikimedia). Оригиналы с upload.wikimedia.org отдавали HTTP 429. Ссылки на страницы файлов ниже.

## 1. Референсы пользователя (папка `AR-15\`, не изменялись)

| Файл | Что это | Вердикт | Как использовать |
|---|---|---|---|
| `1.jpg` (1000×1000) | **Тот же кадр, что фото товара Silencer Shop** для LMT R20 RAHE Reference (`CQBMLK143PW-MARS-EST`): правая сторона, слегка сверху; корреляция с `silencershop/…right.jpg` 0.990 | точная модель подтверждена | конфигурация и освещение; размеры не снимать (низкое разрешение, перспектива) |
| `2.jpg` (1920×1080) | Каркас чужой Blender-модели (не LMT): длинное цевьё M-LOK почти до дула, приклад типа SL, магазин типа PMAG; дуло влево, значит **левая сторона** | не реальное оружие | только плотность сетки и топология (подразбиение, фаски) |
| `3.webp` (1280×431) | **Уменьшенная копия официального изображения LMT** этого же артикула (корреляция 0.987) | лучший референс пользователя | заменить оригиналом `lmt/LMT_CQBMLK143PW-MARS-EST_R20_RAHE_reference_right_official.png` (5449 px) |
| `4.jpg` (1024×656) | Sionics (не LMT), обе стороны, цевьё M-LOK, MOE SL, MOE-рукоять, без магазина | другой производитель | только общая логика левой стороны AR-15. У MARS-L левая сторона отличается (амби-селектор, пиктограммы, рычаги), брать фото DVIDS ниже |
| `5.jpg` (1300×1171, водяной знак Alamy) | Типовой AR-15 с коммерческим прикладом типа M4, обе стороны | не LMT | не использовать для размеров, только общие формы |

## 2. Официальные материалы LMT — `lmt\`

| Файл | Источник (URL) | Что показывает | Вариант | Как использовать |
|---|---|---|---|---|
| `LMT_CQBMLK143PW-MARS-EST_R20_RAHE_reference_right_official.png` (5449×1834, PNG с альфой) | https://lmtdefense.com/wp-content/uploads/2024/07/EstoniaRefRifle.png (страница https://lmtdefense.com/product/estonia-reference-rifle/) | Правая сторона, почти ортографическая, студия; читаются «LMT DEFENSE», патентный блок, пиктограммы селектора, MOE SL-K | **ВЫБРАННЫЙ** | **Главный ортореференс правой стороны.** Масштаб 64.5 px на 10 мм (шаг Picatinny), то есть 6.45 px/мм |
| `LMT_CQBMLK16PS-MARS_MARS-L_piston_right_official.png` (6090×1680) | https://lmtdefense.com/wp-content/uploads/2024/07/CQBMLK16PS-MARS.png | MARS-L Piston 16″: поршневой блок без штыкового упора, A2 ПГ, SOPMOD, без прицелов | соседняя модель | детали ресиверов, болтов фиксации, окна выброса (очень высокое разрешение); ствол, ПГ и приклад не брать |
| `LMT_CQBMLK16-MARS_MARS-L_MLC_right_official.png` (2560×1108) | https://lmtdefense.com/wp-content/uploads/2021/01/CQBMLK16-MARS-2-scaled.png | MARS-L MLC DI 16″ | соседняя модель | цевьё MLC и нижний MARS-L для сверки |
| `LMT_MRPMLK16-MARS_MARS-L_MLR_right_official.png` (1800×533) | https://lmtdefense.com/wp-content/uploads/2024/07/MRPMLK16-MARS.png | MARS-L с длинным цевьём MLR 18.5″ | не наш | только сравнение (длинное цевьё не наше) |
| `LMT_CQB16-MARS_MARS-L_quadrail_right_official.png` (2560×1106) | https://lmtdefense.com/wp-content/uploads/2021/01/CQB16-MARS-REV2-scaled.png | MARS-L CQB с квадрейлом | не наш | только сравнение |
| `LMT_sights_thumbnail_official.png` (1000×1000) | https://lmtdefense.com/wp-content/uploads/2021/02/Sights-Thumbnail-PNG.png | Складные прицелы LMT (мушка и целик с барабанами), поднятые | прицелы как на R20 | форма прицелов крупно |

## 3. PDF LMT — `lmt_pdf\`

| Файл | Источник | Что внутри | Как использовать |
|---|---|---|---|
| `LMT_MARS-L_Spec_Sheet.pdf` | https://www.lmtdealer.com/wp-content/uploads/2021/03/MARS-L-Spec-Sheet-1.pdf | Таблица: стволы 10.5–20″, длины со SOPMOD сложен/разложен, массы; типы верхних ресиверов (CQB/LM8/MLC/MRP/SLK/MLR) с длинами планок; разница прикладов (M4 −1″, DMR +1.4″) | сверка размеров; см. `variant_and_dimensions.md` |
| `LMT_2021_MRP_Operators_Manual.pdf` | https://www.lmtdealer.com/wp-content/uploads/2021/08/2021-MRP-Operators-Manual.pdf | Руководство по семейству MRP/MARS: органы управления, неполная разборка, названия деталей, иллюстрации | неполная разборка (затворная группа), названия и расположение органов |
| `LMT_Defense_Catalog_2023.pdf` | https://mexarmory.pl/wp-content/uploads/2023/03/LMT-defense-catalog-2023.pdf (каталог LMT, выложен дистрибьютором) | Каталог 2023: модели, прицелы, приклады, комплектующие | справка по комплектующим |

## 4. Фото дилера — `silencershop\`

| Файл | Источник | Что показывает | Как использовать |
|---|---|---|---|
| `SilencerShop_LMT_R20_RAHE_reference_right.jpg` (590×570) | https://www.silencershop.com/media/catalog/product/cache/cdd5c223aaa6ee0617a78cf32133f732/l/m/lmt-cqbmlk143pw-mars-est-silencer-shop-central-texas-right.jpg (страница https://www.silencershop.com/lmt-r20-rahe-estonian-reference-rifle.html) | Тот же кадр, что `1.jpg` | доказательство идентичности `1.jpg` |
| `SilencerShop_LMT_R20_RAHE_reference_right_1000px_v2.jpg` (1000×337) | https://www.silencershop.com/media/catalog/product/l/m/lmt-cqbmlk143pw-mars-est-silencer-shop-central-texas-right.jpg | Тот же кадр без полей, чуть крупнее | то же |

## 5. Реальные фото (Wikimedia Commons; армейская R20 «Rahe» Эстонии) — `wikimedia\`

На армейской R20 те же ресиверы, ствол 14.3″, поршень, SL-K и прицелы LMT. Отличия от Reference: маркировка «EST-MIL», наклейки UID/штрих-код, часто стоит оптика.

| Файл | Страница файла (лицензия) | Что показывает | Как использовать |
|---|---|---|---|
| `Commons_DVIDS8558653_R20_LEFT_side_irons_prone_Sebastiani_3840.jpg` | https://commons.wikimedia.org/wiki/File:Lt_Col_Thomas_Sebastiani_practices_with_an_LMT_R20_RAHE_(8558653).jpg (PD, US Air Force / DVIDS) | **ЛЕВАЯ сторона** целиком, прицелы подняты, без оптики; «EST-MIL / EELA2110793» на монолите слева; пиктограммы селектора и рычаги слева | **главный референс левой стороны** (нет ортофото LMT слева) |
| `Commons_DVIDS8558620_R20_RIGHT_side_closeup_Williams_3840.jpg` | https://commons.wikimedia.org/wiki/File:Staff_Sgt_Conner_Williams_adjusts_the_buttstock_of_a_LMT_R20_RAHE_rifle_(8558620).jpg (PD, DVIDS) | Правая сторона крупно, дневной свет: ствол, поршневой блок, ПГ, прицелы, «LMT DEFENSE», патенты, UID-наклейка | материалы и износ, реальные блики |
| `Commons_DVIDS8554970_R20_RIGHT_side_background_Williams_3840.jpg` | https://commons.wikimedia.org/wiki/File:Staff_Sgt_Conner_Williams_practices_with_an_LMT_Defense_R20_RAHE_rifle_(8554970).jpg (PD, DVIDS) | Правая сторона (резкая винтовка на заднем плане), ракурс сверху-сбоку | верх монолита, планка, прицелы |
| `Commons_SwiftResponse23_R20_LEFT_side_optic_3840.jpg` | https://commons.wikimedia.org/wiki/File:Estonian_Defense_League_soldier_with_R20_rifle_during_Swift_Response_23.jpg (PD, US Army) | Левая сторона с оптикой и ремнём, близко | левая сторона цевья M-LOK, приклад |
| `Commons_Sookoll2021_R20_RIGHT_side_optic_CCBY_3840.jpg` | https://commons.wikimedia.org/wiki/File:Sookoll_2021_(51627531781).jpg (CC BY 2.0, фото: Asso Puidet, Силы обороны Эстонии) | Правая сторона с коллиматором, ремень, полевые условия | внешний вид в эксплуатации |
| `Commons_LMT_R-20_Rahe_RIGHT_side_soldier_CC0_1280.png` | https://commons.wikimedia.org/wiki/File:LMT_R-20_Rahe.png (CC0) | Правая сторона с оптикой, в руках стрелка | дополнительный ракурс |

## 6. Текстовые источники (без скачивания)

- LMT R20 Reference: https://lmtdefense.com/product/estonia-reference-rifle/
- LMT MARS-L MLC: https://lmtdefense.com/product/mlc/
- LMT MARS-L CQB: https://lmtdefense.com/product/mars-l-5-56-quad/
- Silencer Shop: https://www.silencershop.com/lmt-r20-rahe-estonian-reference-rifle.html
- Wikipedia: https://en.wikipedia.org/wiki/LMT_R-20_Rahe , https://en.wikipedia.org/wiki/LMT_Modular_Ambidextrous_Rifle_System
- Forgotten Weapons (R20 в армии Эстонии): https://www.forgottenweapons.com/r20-rahe-estonia-modernizes-its-infantry-rifles/
- Magpul PMAG M3: https://magpul.com/pmag-30-ar-m4-gen-m3.html
- MOE SL-K: https://www.brownells.com/gun-parts/rifle-parts/rifle-stocks-parts/ar-15-moe-sl-k-stock-collapsible-mil-spec/ , https://www.primaryarms.com/magpul-moe-sl-k-mil-spec-stock-black-mag626-blk

## 7. Чего не хватает

- Ортографического фото **левой** стороны и вида **сверху, снизу, спереди, сзади** именно Reference-версии у LMT нет. Сайты дилеров с галереями (Rifle Gear, Brownells, PSA, KYGunCo, Titan, Battlehawk) отдавали HTTP 403.
- Нет крупного плана PMAG M3 и рукояти LMT Gen 2. Брать с magpul.com / lmtdefense.com вручную.
- Неполная разборка (затворная группа LMT F-A, поршень) есть только как иллюстрации в `LMT_2021_MRP_Operators_Manual.pdf`.
