# Remington 870 — каталог референсов (web_refs)

Обновлено: 2026-10-14. Цель — фотореалистичная 3D-модель (только визуал) **Remington 870 Hardwood Home Defense, заказной № 81197** (12 к., ствол 18,5″, дерево, заводской удлинитель магазина +2 с хомутом). Выбор варианта и все размеры — в `variant_and_dimensions.md`.

**Безопасность.** Все скачанные файлы — только изображения и PDF. Сигнатура каждого проверена при скачивании. Каждый источник лежит в своей подпапке, из этих папок ничего не запускалось, а Python читал их только с `-I` из другой директории. Файлы пользователя (`1.webp`…`5.jpg`) не изменялись.

**Как использовать (колонка «Применение»):** **Г** — геометрия/пропорции, **М** — маркировки, **Ф** — отделка/материалы/цвет, **О** — общее (конфигурация, контекст), **✗** — не использовать для нашей модели.

**Эпохи одного и того же 81197:**
- **R-эпоха** — Remington Arms Co., Ilion NY, 2016–2020. Ровно как на `2.webp`.
- **RA-эпоха** — RemArms LLC, артикул R81197, с 2021 г. Та же геометрия, но другие мелочи: узор насечки с «лилией» (fleur-de-lis), задняя антабка на прикладе, клеймо «Remington 870», серийник RA….

---

## 0. Референсы пользователя (папка `Remington 870\`)

| Файл | Что это | Вердикт | Применение |
|---|---|---|---|
| `2.webp` (800×161) | **Официальное каталожное фото Remington** «Model 870 Hardwood Home Defense», правый бок. Пиксельно совпадает с `official_remington_wayback/o01_870WoodHomeProtection_2016_1200.png` с remington.com (январь–март 2016; средняя разница 0,68/255). На фото удлинитель +2 и хомут со стойкой антабки, значит это № 81197 | **Главная цель.** R-эпоха (2016–2020): насечка — простые остроконечные панели без «лилии», задней антабки нет, светлее-тёплый тон дерева | Г (силуэт), Ф (тон дерева), О |
| `1.webp` (1024×576) | 870 Express с синтетикой: фиксированный приклад с пистолетной рукоятью (тип SpeedFeed/Knoxx), короткое рифлёное синтетическое цевьё, **стандартный магазин на 4** с колпачком-антабкой за кольцом ствола. Удлинителя и хомута нет, мушка-бусина | Другая фурнитура и другой перед. Ствольная коробка и ствол те же | Г (коробка, ствол) — с осторожностью; ✗ фурнитура/перед |
| `3.jpg` (1920×1080) | Чужой 3D-рендер: 870 с деревом, удлинителем, муфтой и хомутом-антабкой. На стволе справа надпись вида «REM… ILION, NY» | Конфигурация верная (81197). Пропорции и детали — чужая интерпретация | О (конфигурация, ракурс 3/4); ✗ размеры |
| `4.jpg` (1920×1080) | Игровой рендер: 870 с длинным стволом и **вымышленной** маркировкой «HUNTER 870» + номер на коробке, рифлёное цевьё «кукуруза» | Не наш вариант (другое цевьё, другой ствол, выдуманные надписи) | ✗ (только общее настроение износа) |
| `5.jpg` (1500×982) | Помповое ружьё с **золотистым спусковым крючком**, «плоской» ствольной коробкой без выраженного скоса сзади, синтетической ложей; цевьё и колпачок магазина другой формы | **Не Remington 870.** Признаки: золотистый спуск, прямой скос коробки к прикладу вместо характерного «горба» 870, другая форма цевья и колпачка. Вероятнее всего Winchester 1300 (Defender) или его клон; виден только левый бок, так что точную модель не определял. У 870 спуск чёрный | ✗ |

---

## 1. Официальные изображения Remington / RemArms (через Wayback Machine)

Авторские права у Remington Arms / RemArms. Только как референс.

| Файл | Источник | Что показывает | Вариант | Применение |
|---|---|---|---|---|
| `official_remington_wayback/o01_870WoodHomeProtection_2016_1200.png` (800×161, RGBA) | https://web.archive.org/web/20160320191457/http://www.remington.com/sites/default/files/styles/product_gallery_1200/public/product/shotgun/images/870WoodHomeProtection.png | Первоисточник `2.webp`: правый бок 81197 | 81197, R-эпоха | Г, Ф, О |
| `official_remington_wayback/o02_870_HHD_Right_Side_orig.jpg` (1740×347) | https://web.archive.org/web/2018id_/https://www.remington.com/sites/default/files/product/shotgun/images/870_Hard%20Wood_Home%20Defense_Right_Side%20(2)_0.jpg | Оригинал со страницы remington.com 2017–2020, правый бок. Видны клеймо на стволе справа (≈«REMINGTON ARMS COMPANY ILION NY»), хомут со стойкой, муфта, торец удлинителя вровень с дулом, бусина, 2 штифта, насечка без «лилии». Масштаб ≈44,1 px/″ | 81197, R-эпоха | Г, М (частично читается), Ф |
| `official_remington_wayback/o03_870_express_syn_2shot_ext_25077_RV.png` (800×149) | https://web.archive.org/web/20160320173617/http://www.remington.com/sites/default/files/styles/product_gallery_1200/public/product/shotgun/images/870ExpressSyn2ShotExt_25077_RV.png?itok=cZrlaDxG | 870 Express Synthetic с тем же заводским удлинителем +2 (№ 25077) | Сравнение удлинителя/хомута | О |
| `official_remarms_wayback/ra03_R81197_named_870_Tactical.jpg` (**7533×1902**) | https://web.archive.org/web/20250720024138/https://www.remarms.com/assets/imagesRA/870%20Home%20Defense/R81197%20-%20Remington%20870%20Tactical.jpg | **Лучший чертёж-подложка.** Правый бок R81197, ось ствола горизонтальна (≤0,15°), изображение изотропно (штифты круглые). Видны окно выброса с затвором и экстрактором, муфта, хомут, стойка, ступенчатый колпачок, бусина на основании, клеймо «REMINGTON ILION, NY» на стволе справа, задняя антабка на прикладе, насечка с «лилией». Масштаб **187,3 px/″ (7,374 px/мм)**, дуло x≈7352, пятка x≈142 | 81197, RA-эпоха | **Г** (главный), М, Ф |
| `official_remarms_wayback/ra01_870HD_18.5_bead_LEFT.png` (**7464×1872**, прозрачный фон) | https://web.archive.org/web/20250720024137/https://www.remarms.com/assets/imagesRA/870%20Home%20Defense/870%20Home%20Defence%2018.5%20bead%20sight_left%20(2).png | **Левый бок** «870 Home Defense 18.5 bead». Это вариант без удлинителя (как № 25559): колпачок магазина у кольца ствола. Видны клеймо «Remington 870» (курсив), DataMatrix + серийник RAS0xxxxx между штифтами, рычаг затворной задержки, левая насечка, «★ 12GA. 2 3/4 OR 3» на стволе слева | 25559/R-HD, RA-эпоха (коробка/ложа/ствол те же) | **Г** (левый бок), **М** |
| `official_remarms_wayback/ra02_870HD_18.5_bead_RIGHT.png` (7469×1561, прозрачный фон) | https://web.archive.org/web/20230122022344/https://www.remarms.com/assets/imagesRA/870%20Home%20Defense/870%20Home%20Defence%2018.5%20bead%20sight_right%20(2).png | Правый бок того же варианта без удлинителя | 25559, RA-эпоха | Г (контроль), Ф |
| `retail_impactguns/i01_81197_product_R_2560px.png` (2500×667) | Страница: https://www.impactguns.com/pump-shotguns/remington-model-870-home-defense-12-ga-18-50-barrel-3-chamber-black-satin-hardwood-stock-6rd-810070683900-r81197 ; файл: https://cdn11.bigcommerce.com/s-1kqh9qmybo/images/stencil/2560w/products/80086/190077/SSI138753__96114.1670259763.png | Студийное фото дистрибьютора (Sports South), правый бок 81197. Внешне R-эпоха (насечка без «лилии», нет задней антабки), но **это другой кадр**, не o02 | 81197, R-эпоха | Г (2-й R-эпохи), Ф |

Текстовые официальные страницы (спецификации, без файлов):
- remington.com, «Model 870 Hardwood Home Defense», снимки Wayback: https://web.archive.org/web/20160121132937/http://www.remington.com/shotguns/pump-action/model-870/model-870-hardwood-home-defense , https://web.archive.org/web/20180326102803/https://www.remington.com/shotguns/pump-action/model-870/model-870-hardwood-home-defense , https://web.archive.org/web/20200731045203/https://www.remington.com/shotguns/pump-action/model-870/model-870-hardwood-home-defense
- remarms.com, та же страница: https://web.archive.org/web/20210228172320/https://www.remarms.com/shotguns/pump-action/model-870/model-870-hardwood-home-defense
- Каталог Remington 2016 (текст): https://idoc.pub/documents/2016-remington-catalog-pnxk238z8x4v — «NEW MODEL 870 EXPRESS HARDWOOD HOME DEFENSE».

---

## 2. Руководство владельца (`manual/`)

| Файл | Источник | Что показывает | Применение |
|---|---|---|---|
| `m01_remarms_2021_870_manual_archiveorg.pdf` | https://archive.org/details/remington-model-870-manual (копия https://www.remarms.com/sites/default/files/documents/870%20Manual%20Final.pdf ; оригинал на remarms.com во время работы отдавал HTTP 522) | Руководство RemArms 2021: детали, сборка/разборка, деталировка, перечень деталей | Г (устройство), О |
| `m02_rem870com_870_manual_old.pdf` | https://www.rem870.com/remington_model_870_manual.pdf (идентична http://pdf.textfiles.com/manuals/FIREARMS/remington_870.pdf) | Руководство Remington-эпохи («12 Ga. Express listed below») | Г, О |
| `m01_p16_exploded_view_400dpi.png` (2200×3400) | рендер стр. 16 из m01 | **Деталировка** (детали 1–70, в т.ч. 3 ствол с кольцом, 27/28/29 цевьё/труба/гайка, 39 колпачок, 46 коробка, 58 приклад, 65 спусковая скоба) | **Г** (состав и формы деталей) |
| `m01_p17_parts_list_200dpi.png` | стр. 17 из m01 | Перечень деталей с номерами | О (названия) |
| `m01_p07_main_parts_picA_300dpi.png` | стр. 7 | Picture A: названия частей; Picture 1: предохранитель за спуском | О |
| `m01_p10_assembly_pics5-9_200dpi.png` | стр. 10 | Picture 5–9: кольцо ствола (barrel guide ring), рычаг затворной задержки, вырез под отражатель, окно выброса | Г, О |
| `m01_p12…p14_*.png` | стр. 12–14 | Разборка: защёлки патронов, затвор и слайд, штифты спусковой скобы, Picture 19–22 | Г (внутренности), О |
| `m02_p16_exploded_view_old_400dpi.png`, `m02_p17_parts_list_old_200dpi.png` | m02 | То же в версии Remington-эпохи | О |

---

## 3. Обзор заводского удлинителя +2 на rem870.com (`rem870com_ext_review/`)

Статья: «Remington 870 +2 Magazine Extension Tube Review» (2014-10-08) — https://www.rem870.com/2014/10/08/remington-870-2-magazine-extension-review/ . Файлы взяты из `https://www.rem870.com/wp-content/uploads/2014/10/<имя>`, все 600 px по ширине. Это **тот же заводской удлинитель Remington +2**, что стоит на 81197.

| Файл | Исходное имя | Что показывает | Применение |
|---|---|---|---|
| `e01_factory_plus2_extension_parts.jpg` | Remington870extension_plus2.jpg | Комплект: труба со ступенчатым колпачком и **вентиляционным отверстием**, муфта, хомут, стык | **Г**, Ф |
| `e02_extension_coupling.jpg` | Remington_extension_coupling.jpg | Муфта: наружные продольные рёбра, буртик, пазы под фиксатор колпачка | **Г** |
| `e03_extension_tube.jpg` | extension_tube.jpg | Схема стыка трубы и муфты (разрез) | Г |
| `e04_bracket_clamp.jpg` | magazine_extension_bracket_clamp.jpg | **Заводской хомут** — гнутая стальная лента «восьмёркой», 2 исполнения: без стойки и со стойкой антабки | **Г**, Ф |
| `e05_bracket_clamp_screw.jpg` | magazine_extension_bracket_clamp_screw.jpg | Хомут на стволе и трубе, стяжной винт | **Г** |
| `e06_bracket_sling_stud.jpg` | Remington_extension_bracket_sling.jpg | Стойка антабки на хомуте (положение «6 часов») с ремнём | Г, О |
| `e07_magazine_tube_joint.jpg` | magazine_tube_joint.jpg | Вид внутрь трубы, стык | О |
| `e08_extension_installed_full.jpg` | magazine_extension_installation.jpg | Пошаговая установка (муфта → пружина → труба → хомут → винт) | Г, О |
| `e09_extension_on_gun_clamp.jpg` | remington870extension_magazine_clamp.jpg | Детали хомута: две полуленты, стопорное кольцо, стойка | Г |
| `e10_extension_finish.jpg` | remington870extension_finish.jpg | Сравнение отделки труб разных удлинителей | Ф |
| `e11_factory_extension_box.jpg` | remington870factory_magazine_extension.JPG.jpg | 870 с деревом и заводским удлинителем на гравии | Г, Ф |
| `e12_factory_follower.jpg` | remington870factory_follower.jpg | Оранжевый подаватель | Ф (деталь) |
| `e13…e22` | см. исходные имена в статье | Сравнения удлинителей, вес деталей (e17: труба 4,08 oz, муфта 0,95, пружина 0,93, хомут со стойкой 1,72), пружины, штык-переходник (e15 — не наш) | О |

---

## 4. Rem870.com, 2010: 870 Police Magnum с орехом (`rem870com/`, ранее)

Статья Jonathan Paul: https://www.rem870.com/2010/04/28/home-defense-remington-870-shotgun/ . Ружьё — **870 Police Magnum**: паркеризация, орех, ствол 18,5″, **без заводского удлинителя**. Удлинитель и хомут на фото — **неоригинальные** (Mesa Tactical, анодированный алюминий).

| Файл | Что показывает | Вариант | Применение |
|---|---|---|---|
| `r01_police_magnum.jpg` | Клеймо «Remington 870 POLICE MAGNUM» на левом боку коробки (Police) | 870P | М (стиль шрифта; ✗ текст для 81197) |
| `r02_with_barrel.jpg` | Ружьё целиком + второй ствол | 870P | О |
| `r03_buttstock.jpg` | Приклад из ореха, затыльник, задняя антабка | 870P | Ф (дерево), Г (форма приклада — близка) |
| `r04_forend.jpg` | **Полицейское цевьё с поперечными рёбрами** — у 81197 цевьё другое | 870P | ✗ для 81197 |
| `r05_magext_clamp.jpg` | Алюминиевый хомут Mesa Tactical | aftermarket | ✗ |
| `r06_follower.jpg` | Открытый затвор, подаватель, цевьё отведено к коробке | 870P | Г (положение «открыто»), О |
| `r07_safety.jpg` | Кнопка предохранителя крупным планом (увеличенная, aftermarket?) | 870P | Ф (текстура), осторожно |
| `r08_870.jpg` | Общий вид 3/4 | 870P | О |

---

## 5. Обзор The Mag Life (GunMag Warehouse), 2023 (`review_maglife_2023/`)

«Remington 870 HHD: The New Older», Jim Davis, 2023-03-22 — https://gunmagwarehouse.com/blog/remington-870-hhd-the-new-older/ (сайт закрыт для ботов, взят снимок Wayback https://web.archive.org/web/20230322233936/https://gunmagwarehouse.com/blog/remington-870-hhd-the-new-older/ ). Реальное ружьё **HHD RA-эпохи**.

| Файл | Исходный URL | Что показывает | Применение |
|---|---|---|---|
| `g01_hhd_receiver_slide_release.jpg` (800×600) | …/wp-content/uploads/2023/02/870-Remington-Slide-Release.jpg | **Реальное фото** левого бока коробки: «Remington 870» (курсив), DataMatrix + «RAS…», 2 штифта, рычаг затворной задержки перед скобой, насечка с «лилией», фактура матового покрытия | **М, Ф**, Г |
| `g02_hhd_author_range.jpg` | …/Remington-870-HHD-12-Gauge.jpg | Ружьё у плеча (левый бок, ракурс) | О (масштаб к человеку) |
| `g03_hhd_with_ammo.jpg` | …/Remington-870-12-gauge-HHD-Buckshot-Sellier-Bellot-Federal.jpg | Правый бок сверху, окно выброса, цевьё, патроны (Federal, Remington, Herter's, S&B) | Ф, О (патроны) |

Ключевые факты из текста: металл матово-чёрный, бусина **латунная**, спусковая скоба **полимерная**, на прикладе RA-выпуска **добавлена задняя антабка** (у ранних не было), отделка дерева сатиновая, тёмная; 38,5″; 7,25 фунта пустое.

---

## 6. Wikimedia Commons (`commons/`)

Файлы — оригиналы с upload.wikimedia.org. Страница каждого: `https://commons.wikimedia.org/wiki/File:<имя>`. Лицензии указаны. Ни на одном нет именно 81197, но ствольная коробка 12 к. одинакова у всех 870.

| Файл | Файл на Commons | Лицензия | Что показывает | Вариант | Применение |
|---|---|---|---|---|---|
| `c01_870_sighted_cyl_bore_R_4793px.jpg` | File:870bad.jpg | CC BY-SA 4.0 | 870 с прицельным стволом (цилиндр), дерево, правый бок, на ящике | 870 с винтовочными прицелами | Г (коробка, приклад), Ф |
| `c02_870_wingmaster_profile_5228px.jpg` | File:Remington_870_Wmaster.jpg | CC BY-SA 4.0 | Wingmaster, правый бок, глянцевый орех, рифлёное цевьё | Wingmaster | Г (коробка), Ф (контраст) |
| `c03_870_fieldmaster_2023_profile_3988px.jpg` | File:Remington_870_Fieldmaster.jpg | CC BY-SA 4.0 | Fieldmaster 2023 (RemArms), правый бок, насечка с «лилией». Снято телефоном близко, перспектива | Fieldmaster | Ф, М (стиль насечки RA); ✗ точные пропорции |
| `c04_870P_WTS_museum_3208px.jpg` | File:0028228352_Remington_Model_870_P_in_Wehrtechnische_Studiensammlung.jpg | CC BY-SA 4.0 | 870P (синтетика, фонарь-цевьё) в музее WTS Кобленц | 870P | О |
| `c05_870_shotgun_2048px.jpg` | File:Remington_870_Shotgun.jpg | CC BY-SA 4.0 | Полицейский с 870 (ч/б) | — | О |
| `c06_870_hunter_barrel_3200px.jpg` | File:Remington_870_with_hunter_barrel.jpg | CC BY-SA 4.0 | 870 Express со светлой «hardwood» фурнитурой и вент. планкой | 870 Express | Ф (светлая древесина Express) |
| `c07_870_recoil_pad_2032px.jpg` | File:Recoil_Pad_Remington_870.jpg | CC BY-SA 3.0 | Затыльник 870 на камуфляжном прикладе (вентилируемый, другой) | — | О (тип затыльника не наш) |
| `c08_shells_loading_port_3087px.jpg` | File:Shotgun_shells_and_loading_port.jpg | CC BY 2.0 | **Низ коробки и окно заряжания**, подаватель/лоток, патроны 12 к., дерево Express | 870 Express | **Г** (низ коробки), Ф |
| `c09_870_express_my3guns_2592px.jpg` | File:My_three_guns.JPG | Public domain | 870 Express (12 к.) в кейсе с другими ружьями | 870 Express | О, Ф |
| `c10_870_profile_png_990px.png` | File:Remington_Model_870.png | CC BY-SA 4.0 | Тактический 870, вырезанный профиль | тактический | О |
| `c11_870_police_magnum_14in_1150px.jpg` | File:Rem-870-Police.jpg | CC BY-SA 4.0 | 870 Police Magnum 14″, Cerakote, ореховая полицейская фурнитура | 870P | Ф (орех), ✗ цевьё |
| `c12_870_express_tactical_1150px.jpg` | File:Remington-870-Express-Tactical.jpg | CC BY-SA 4.0 | Express Tactical с прикладом thumbhole | Express Tactical | О |
| `c13_870_police_vangcomp_5470px.jpg` | File:Remington_870_Police_(55284788188).jpg | CC BY-SA 4.0 | 870 Police Vang Comp, вырезанный профиль, патронташ на коробке | 870P custom | О |
| `c14_mossberg500_vs_870_2475px.jpg` | File:Mossberg500-remington870.jpg | CC BY-SA 2.0 | Mossberg 500 и 870 рядом | — | О (отличия) |
| `c15_870_wingmaster_sbs_4038px.jpg` | File:Remington_870_Wingmaster_(55416542561).jpg | CC BY-SA 4.0 | Wingmaster 14″ с фурнитурой Woox | custom | О |
| `c17_shotgun_reloading_1468px.jpg` | File:Shotgun_reloading.jpg | CC BY 2.0 | Перезарядка 870 (деревянное рифлёное цевьё) | — | О (руки, ракурс) |
| `c18_shell_ejecting_4256px.jpg` | File:Shotgun_shell_ejecting.JPG | Public domain (USAF) | **Затвор открыт, гильза вылетает**, цевьё в заднем положении у коробки | Wingmaster/Express | **Г** (положение «открыто»), О |
| `c19_870_express_dlask_1962px.jpg` | File:Dlask870.jpg | CC BY-SA 3.0 | Dlask 870 Express со стволом 8,5″ | custom | ✗ |
| `c20_870_steveZ_1002px.jpg` | File:Flickr_-_~Steve_Z~_-_870.jpg | CC BY-SA 2.0 | Тактический 870 с телескопическим прикладом | custom | ✗ |

Не скачаны из-за ограничения HTTP 429, решено не повторять: `Remington_870_Police_model_(23745298808).png`, `Remington870-police-1.jpg`, `Ithaca_37-Browning_BPS_Trap-Remington_870.jpg`. Фото дела Aaron Alexis (640 px) исключены сознательно.

---

## 7. Текстовые источники размеров и фактов (без файлов)

| Источник | URL | Что взято |
|---|---|---|
| Remington, страница HHD (2016/2018/2020) | см. раздел 1 | 25559 и 81197: 12 к., магазин 4 / 6, ствол 18½″ fixed CYL, одна бусина, Matte Blue, OAL 38½″, LOP 14″, drop 1½″ / 2½″ (на странице 2020 значения перепутаны местами), Hardwood Satin, 7½ фунта, MSRP $443 (2016) / $465 (2020) |
| RemArms, та же страница (2021) | см. раздел 1 | Та же таблица (drop тоже перепутан) |
| Каталог Remington 2016 | https://idoc.pub/documents/2016-remington-catalog-pnxk238z8x4v | «NEW Model 870 Express Hardwood Home Defense», «receiver machined from a block of solid steel» |
| Форум rem870, t=2664 (Synchronizor) | https://rem870.com/forum/viewtopic.php?t=2664 | 81197 = HHD с **заводским Remington +2** на стандартной трубе на 4; 25559 — без удлинителя; ружьё с отделкой Express |
| Rem870.com, обзор удлинителя +2 | https://www.rem870.com/2014/10/08/remington-870-2-magazine-extension-review/ | Труба 1″ OD, длина ≈6 7/16″, вровень с дулом 18,5″; колпачок 7/8″ × чуть больше ½″ с вентотверстием; муфта ≈0,73″ длиной, буртик ≈1,4″; хомут стальной, один винт, есть версии со стойкой на «6 часов» (стопорное кольцо) |
| The Mag Life 2023 | см. раздел 5 | 38,5″; 7,25 фунта пустое; 6+1; до 3″; латунная бусина; полимерная скоба; задняя антабка у RA-выпуска; матово-чёрный металл |
| Guntoters, обзор 81197 (2018) | https://guntoters.com/blog/2018/07/29/remington-870-home-defense/ (сайт недоступен ботам; данные по поисковой выдаче) | 6+1, 3″, 38,5″, 7,25 фунта пустое; коробка не сверлена под планку |
| Glocktalk (владельцы HHD) | https://www.glocktalk.com/threads/thoughts-on-remington-hard-wood-home-defense-870.1640879/ (по поисковой выдаче) | Пластиковая спусковая скоба; цевьё «Field», а не короткое Police |
| Blue Book of Gun Values | https://bluebookofgunvalues.com/products/remington-model-870-express-hardwood-home-defense (по выдаче) | Годы выпуска 2016–2020 (Remington) |
| Ритейлеры (Sportsman's Warehouse, Palmetto SA, Gunbuyer, Able Ammo, Eldersburg, Impact Guns) | напр. https://www.sportsmans.com/shooting-gear-gun-supplies/shotguns/remington-870-hardwood-home-defense-matte-blued-12-gauge-3in-pump-action-shotgun-185in/p/1707740 | 3″ патронник, Matte Blued, Satin Hardwood, UPC 047700811970 (Remington) / 810070683900 (RemArms R81197) |
| 16ga.com, «Win Mod 12 vs Rem 870 Receiver Dimensions» (2009) | http://16ga.com/forum/viewtopic.php?t=1697&view=next | Штангенциркуль, 870 16 к. 1952 г. на коробке размера 12 к.: высота у окна заряжания 2,302″, перед окном 2,338″, ширина 1,325″; длина коробки = 6 13/16″ + 1″ = **7 13/16″**; LOP 14″, drop 1½/2½ |
| notpurfect.com | https://www.notpurfect.com/main/87020.htm | Штангенциркуль: коробка 12 к. — высота 2,5″, ширина 1,4″ (20 к. — 2,25 × 1,25; длина одинакова) |
| Canadian Gun Nutz | https://www.canadiangunnutz.com/forum/threads/remington-870-trigger-group-pins-spacing.1808225/ | Межцентровое расстояние штифтов спусковой скобы **2,025″** (штангенциркуль) |
| Форум rem870, t=3011 (по выдаче) | http://rem870.com/forum/viewtopic.php?t=3011 | Штифты: передний 3/16″, задний 1/4″ |
| Gunboards | https://www.gunboards.com/threads/od-of-remington-870-mag-tube-12-16-gauge.1177533/ (по выдаче) | Магазинная труба 12/16 к. — **0,998–0,999″** OD |
| AR15.com (по выдаче) | https://www.ar15.com/forums/armory/11_87_and_870_barrel_outside_diameter/1-184553/ | Дульный OD стволов 870: 0,830–0,890″; Express и Police 18–18,5″ — **≈0,880″** |
| Форум rem870, t=2237 | https://rem870.com/forum/viewtopic.php?t=2237 | Канал fixed-cylinder у дула 0,728–0,729″ |
| truegunvalue (по выдаче) | https://truegunvalue.com/shotgun/remington-870-hardwood-home-defense/price-historical-value | В данных листинга HHD встречается «Model Express Magnum» — намёк на клеймо коробки R-эпохи (не подтверждено) |

---

## 8. Пробелы покрытия

- **Вид сверху** (ширина коробки, ствол сверху): фото нет. Есть только цифры ширины коробки 1,325–1,4″.
- **Вид снизу**: только `c08` (окно заряжания) и чертежи руководства.
- **Спереди** (дуло, торец колпачка): только `e01` (вентотверстие колпачка) и `ra03` в профиль. **Сзади** (торец затыльника): фото нет.
- **Левый бок 81197 R-эпохи** (клеймо коробки, серийник): официальных снимков нет. Нужен листинг GunBroker или фото владельца.

---

## 9. Дополнительные источники (2026-10-14, сборка и проверка пропорций)

| Источник | URL | Что взято |
|---|---|---|
| Remington Society, форум (p=38185) | https://www.remingtonsociety.org/forums/viewtopic.php?p=38185 | Детали конструкции коробки/затвора 870 (обсуждение) |
| Rem870.com, форум (p=14502, p=14490) | https://rem870.com/forum/viewtopic.php?p=14502 , https://rem870.com/forum/viewtopic.php?p=14490 | Обсуждения ствола и окна выброса HD-моделей |
| Rem870.com, форум (p=8888) | https://rem870.com/forum/viewtopic.php?p=8888 | Детали заводского удлинителя и хомута |
| Rem870.com, форум (p=19310) | https://rem870.com/forum/viewtopic.php?p=19310 | Колодка и предохранитель |
| Remington Society, форум (p=6551) | https://www.remingtonsociety.org/forums/viewtopic.php?p=6551 | Маркировки стволов 870 |
| LSB Auctions (лоты 870) | https://lsbauctions.com/?p=97125 , https://lsbauctions.com/?p=54339 , https://lsbauctions.com/?p=79800 | Фото деталей коробки и маркировок |
| Monterey County Sheriff, armorer school (PDF) | https://www.montereysheriff.org/ (armorer_school_shotguns) | Разборка 870: колодка, подаватель, задержка тяг |
| Wikipedia, Remington Model 870 | https://en.wikipedia.org/wiki/Remington_Model_870 | Общие данные, эпохи выпуска |
| Outdoor Life, обзор 870 Express | https://www.outdoorlife.com/gear/remington-870-express-review.md | Ход цевья ≈3″ («travel of the fore-end is a short 3 inches») → ход помпы 76 мм |
| Tractor Supply, Magpul MOE M-LOK forend для 870 | https://www.tractorsupply.com/tsc/product/magpul-moe-m-lok-12-gauge-shotgun-forend-for-remington-870-black-polymer | «Does not overlap receiver for sidesaddle compatibility» → штатные цевья в заднем положении наезжают на коробку |
| Rem870.com, форум (p=7413) | https://rem870.com/forum/viewtopic.php?p=7413 | Посадка цевья на тягах (зазоры) — справочно |

Проверка пропорций по фото самого варианта: `retail_impactguns\i01_81197_product_R_2560px.png` (ортографичный снимок дистрибьютора, 2.53 px/мм) и `official_remington_wayback\o02_870_HHD_Right_Side_orig.jpg`; контрольные — `official_remarms_wayback\ra02_870HD_18.5_bead_RIGHT.png`, `commons\c01`, `c02` (затвор заполняет окно выброса).
