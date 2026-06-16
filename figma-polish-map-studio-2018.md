# Studio Design 20:18 — карта ручной доработки Figma-макета

## 0. Цель

Доработать **текущий Figma-макет лендинга Studio Design 20:18**, не создавая новый сайт с нуля и не делая альтернативные концепции.

Главная идея лендинга:

> Дизайн интерьера квартиры в СПб, который реально можно построить без хаоса на стройке.

Файл должен быть пригоден для ручного переноса в **Tilda / Zero Block**: понятные editable-блоки, системные отступы, единые карточки, desktop 1440 и mobile 390.

---

## 1. Что оставить без перестройки

Оставить текущую структуру:

1. Первый экран.
2. Боль ремонта.
3. Визуализация → Чертёж → Реализация.
4. Проектная папка.
5. Проект глазами строителя.
6. Портфолио.
7. Стоимость + калькулятор.
8. Что фиксируем до старта.
9. Основатели.
10. FAQ + финальная форма.

Не добавлять новые большие секции, отзывы, инфобизнес-блоки, агрессивные анимации, глянец, кислотные цвета, Instagram / Facebook / Meta / WhatsApp.

---

## 2. Базовые фреймы и сетка

### Desktop

```text
Frame: Desktop 1440 — Landing Final
Width: 1440 px
Background: #F4EEE7
Container: 1180 px
Left/right margins: 130 px
Grid: 12 columns
Column width: 80 px
Gutter: 20 px
```

### Mobile

```text
Frame: Mobile 390 — Landing Final
Width: 390 px
Background: #F4EEE7
Container: 358 px
Left/right margins: 16 px
Grid: 4 columns
Gutter: 12 px
```

---

## 3. Цвета

```text
Background / Warm:        #F4EEE7
Background / Stone:       #E8DED5
Card / Paper:             #FFFAF3
Card / Soft:              #F7F0E9
Text / Primary:           #151312
Text / Muted:             #6B625B
Text / Soft:              #948A82
Line / Light:             rgba(21, 19, 18, 0.10)
Line / Medium:            rgba(21, 19, 18, 0.16)
Accent / Coral:           #FF6B66
Accent / Coral Dark:      #DF5C58
Accent / Soft:            rgba(255, 107, 102, 0.12)
Dark / Graphite:          #1B1816
Dark / Graphite 2:        #28231F
White:                    #FFFFFF
```

Коралловый использовать только для CTA, активных вкладок, маленьких бейджей, линий и hover-состояний.

---

## 4. Типографика

Основной шрифт: **Inter**. Если Inter нет — Manrope. Не смешивать больше 2 семейств.

### Desktop styles

```text
H1: 58 px / 62 px, weight 700–760, letter spacing -4.5%, color #151312
H2: 44 px / 48 px, weight 700–760, letter spacing -4%, color #151312
H3: 22 px / 27 px, weight 700, letter spacing -2.5%, color #151312
Lead: 20 px / 30 px, weight 400, color #413A35
Body: 17 px / 27 px, weight 400, color #6B625B
Small label: 12 px / 16 px, weight 700, uppercase, letter spacing 12–16%, color #DF5C58
```

### Mobile styles

```text
H1: 36 px / 40 px, letter spacing -4%
H2: 30 px / 34 px, letter spacing -3.5%
H3: 21 px / 26 px
Lead: 17 px / 25 px
Body: 16 px / 24 px
Small label: 11 px / 15 px
```

---

## 5. Карточки и CTA

### Светлая карточка

```text
Fill: #FFFAF3
Stroke: rgba(21, 19, 18, 0.10), 1 px
Radius: 24–30 px
Shadow: 0 / 16 / 46 / rgba(31, 25, 21, 0.075)
```

Hover:

```text
Y: -4 to -6 px
Stroke: rgba(255, 107, 102, 0.24)
Shadow: 0 / 34 / 90 / rgba(31, 25, 21, 0.16)
```

### Тёмная карточка

```text
Fill: #1B1816 или gradient #28231F → #1B1816
Stroke: rgba(255, 255, 255, 0.12)
Radius: 24–30 px
Primary text: #FFFFFF
Secondary text: rgba(255,255,255,.68)
```

### Primary CTA

```text
Height: 58–60 px
Padding: 28–30 px left/right
Radius: 999 px
Fill: #FF6B66
Text: #FFFFFF, 14–15 px, weight 700
Shadow: 0 / 16 / 34 / rgba(255, 107, 102, 0.25)
```

Hover:

```text
Fill: #DF5C58
Y: -2 px
Shadow: 0 / 24 / 54 / rgba(255, 107, 102, 0.32)
```

### Secondary CTA

```text
Height: 58–60 px
Radius: 999 px
Fill: rgba(255, 250, 243, 0.70)
Stroke: rgba(21, 19, 18, 0.13)
Text: #151312
```

---

## 6. Первый экран — главная правка

### Desktop hero

```text
Section: 01 / Hero
Width: 1440 px
Height: 820–860 px
Top padding from page top: 112–124 px
Bottom padding: 72 px
Container: 1180 px
```

Hero layout:

```text
Container X: 130
Container Y: 124
Container W: 1180
Container H: 650
Left column: 560 px
Gap: 60 px
Right column: 560 px
```

### Header

```text
Header height: 72 px
Fill: rgba(246, 240, 233, 0.74)
Background blur: 18 px
Bottom stroke: rgba(21, 19, 18, 0.075)
Logo X: 130
Menu center, gap 32 px
Phone right: 130 px from edge
```

### Hero left column

Layer order:

1. Eyebrow.
2. H1.
3. Подзаголовок.
4. CTA row.
5. Facts grid.

H1 оставить:

```text
Дизайн интерьера квартиры в СПб, который реально можно построить
```

H1 параметры:

```text
W: 560–590 px
Font: 58 px / 62 px
Weight: 700–760
Letter spacing: -4.5%
Margin bottom: 24 px
```

Важно: не использовать 70–76 px. Сейчас H1 давит.

Подзаголовок оставить:

```text
Проектируем, комплектуем и реализуем интерьеры одной командой: рабочие чертежи, мебель на заказ, поставщики, строительная бригада и авторский надзор.
```

Параметры:

```text
W: 540–560 px
Font: 20 px / 30 px
Color: #413A35
Margin bottom: 34 px
```

CTA row:

```text
Direction: horizontal
Gap: 12 px
Height: 60 px
Margin bottom: 34 px
```

Кнопки:

```text
Primary: “Рассчитать стоимость проекта”, W 252–270 px
Secondary: “Получить пример полного проекта”, W 270–292 px
```

Facts grid: сделать 2×2, а не приклеенную нижнюю полосу.

```text
Grid: 2 columns
Card W: 274 px
Card H: 88–96 px
Gap: 12 px
```

Факты:

```text
10 лет — опыта в проектах и реализации
100+ — объектов в портфолио студии
от 5 000 ₽ — за м² дизайн-проекта
СПб / Москва — проектирование и сопровождение
```

### Hero right column

```text
X: 750
Y: 126
W: 560
H: 650
```

Hero image:

```text
Frame: Hero / Image
W: 560 px
H: 620 px
Radius: 34 px
Fill: #D8CEC3
Stroke: rgba(21, 19, 18, 0.08)
Clip content: true
```

Внутренняя рамка:

```text
X: 12
Y: 12
W: 536
H: 596
Radius: 24 px
Stroke: rgba(255, 255, 255, 0.22)
Fill: none
```

Карточка “Рабочий комплект проекта” должна быть внутри изображения, а не случайно наложена на стык колонок.

```text
Parent: Hero / Image
X: 28
Y: 362
W: 376
H: 230
Radius: 24 px
Fill: rgba(255, 250, 243, 0.92)
Background blur: 18–20 px
Stroke: rgba(21, 19, 18, 0.10)
Shadow: 0 / 24 / 60 / rgba(31, 25, 21, 0.20)
```

Внутри карточки:

```text
Title: Рабочий комплект проекта
Badge: 25 листов
Rows:
- Планировочное решение — утверждено
- Электрика и сценарии света — привязки
- Мебель на заказ — чертежи
- Плитка, ведомости, материалы — комплектация
```

Строки:

```text
Height: 34–38 px
Top border: rgba(21, 19, 18, 0.085)
Left text: 14 px, weight 650, #393430
Right badge: 10–11 px, #DF5C58, fill rgba(255,107,102,.09), radius 999
```

### Mobile hero 390

Порядок строго:

1. H1 + текст.
2. CTA.
3. Фото.
4. Факты.

```text
Section width: 390 px
Padding top: 94 px
Padding left/right: 16 px
Padding bottom: 56–64 px
```

Mobile H1:

```text
W: 358 px
Font: 36 px / 40 px
Letter spacing: -4%
Margin bottom: 18–22 px
```

CTA:

```text
Direction: vertical
Gap: 10 px
W: 358 px
Button H: 56–58 px
Margin bottom: 28 px
```

Image:

```text
W: 358 px
H: 430–460 px
Radius: 26 px
```

Mobile document card:

```text
W: 326 px
X: 16 px
Bottom inset: 16 px
Radius: 22 px
Content: максимум 3 строки, без мелких подписей
```

Facts:

```text
Grid: 2 columns
Card W: 173 px
Card H: 86–92 px
Gap: 10 px
Margin top: 18 px
```

---

## 7. Блок “Боль ремонта”

Desktop:

```text
Section padding: 96–104 px
Container: 1180 px
Left column: 500 px
Right column: 620 px
Gap: 60 px
```

Карточки “До проекта” / “После проекта”:

```text
Equal height
Radius: 28 px
Padding: 32 px
Gap: 18 px
```

“После проекта” оставить тёмной:

```text
Fill: gradient #28231F → #1B1816
Text secondary: rgba(255,255,255,.72)
Bullets: #FF6B66
```

---

## 8. Блок “Визуализация → Чертёж → Реализация”

Сделать одним из ключевых визуальных блоков.

Desktop:

```text
Section padding: 104 px
Header row: left H2, right text W 390 px
Journey card W: 1180 px
Journey card H: 440–470 px
Radius: 36 px
Fill: rgba(255, 250, 243, 0.92)
Stroke: rgba(21, 19, 18, 0.10)
Padding: 16 px
```

Tabs:

```text
H: 58–62 px
Fill: rgba(232, 222, 213, 0.60)
Radius: 999 px
Padding: 7 px
Gap: 8 px
```

Active tab:

```text
Fill: #151312
Text: #FFFFFF
Shadow: 0 / 10 / 26 / rgba(21,19,18,.18)
```

Content:

```text
Left text area: W 420 px, padding 32 px
Right visual area: remaining width, H 340–365 px, radius 28 px
```

Содержательно:

```text
Визуализация — согласовываем образ, пропорции, материалы, сценарии жизни.
Чертёж — переводим решения в планы, развертки, узлы, мебель.
Реализация — сопровождаем стройку, поставки и соответствие проекту.
```

Визуально должно быть понятно: картинка → документация → объект.

Mobile:

```text
Tabs horizontal scroll
Text above visual
Visual H: 300 px
```

---

## 9. Блок “Проектная папка”

Desktop:

```text
Frame W: 1180 px
H: 580–620 px
Radius: 36 px
Fill: #EBE2D9
Stroke: rgba(21,19,18,.10)
Padding: 18 px
```

Grid:

```text
Left tabs: 330 px
Gap: 18 px
Right content: 796–814 px
```

Tabs:

```text
W: 330 px
H: 96–108 px
Radius: 20 px
Padding: 20–21 px
Gap: 9–10 px
```

Tabs:

1. Чертежи — планировка, потолки, свет, электрика, развертки.
2. Мебель — ниши, фасады, габариты, встроенные решения.
3. Материалы — ведомости, спецификации, аналоги.
4. Надзор — комментарии, контроль решений, стройка.

Right content:

```text
Radius: 28 px
Fill: #FFFAF3
Stroke: rgba(21,19,18,.08)
Grid: visual 55% / text 45%
```

Внутри показать:

```text
Чертежи → план
Мебель → мебельный чертёж
Материалы → ведомость
Надзор → комментарий для строителей
```

Mobile:

```text
Tabs vertical
Document visual H: 300–320 px
Info below
```

---

## 10. Блок “Проект глазами строителя”

Desktop:

```text
Background: #1B1816
Padding: 96–104 px
H2 max W: 820 px
Lead max W: 760 px
Cards grid: 2 columns
Gap: 14–16 px
```

Card:

```text
W: 582 px
Min H: 138–150 px
Radius: 26 px
Padding: 28 px
Fill: rgba(255,255,255,.055)
Stroke: rgba(255,255,255,.12)
```

Контент:

```text
Где заканчивается плитка и начинается окраска? → есть развертка.
Куда выводить розетки для кухни и подсветки? → есть привязки.
Какой размер ниши под шкаф и фасады? → есть чертёж мебели.
Что покупать и где искать аналоги? → есть комплектация.
```

Не добавлять лишние иконки. Допустима тонкая коралловая стрелка `→`.

---

## 11. Портфолио

Desktop:

```text
Grid: 3 columns
Gap: 16–18 px
Card W: 381–382 px
Card H: 460–480 px
Radius: 28–30 px
Image H: 250–266 px
Body padding: 24–26 px
```

Hover:

```text
Y: -6 / -7 px
Image scale: 104%
Stroke: rgba(255,107,102,.25)
Shadow: 0 / 34 / 90 / rgba(31,25,21,.16)
```

Тексты карточек:

```text
ЖК Чёрная речка
Meta: СПб · квартира · проект + сопровождение
Text: Планировка кухни-гостиной, хранение и рабочие чертежи для реализации без уточнений на стройке.

GloraX Premium
Meta: СПб · квартира · дизайн-проект
Text: Мебель на заказ, световые сценарии и комплектация под согласованный бюджет.

Project 6/3
Meta: Квартира · рабочая документация
Text: Визуальная концепция переведена в планы, узлы, привязки и ведомости для строителей.

Ботаника 2
Meta: СПб · квартира · комплектация
Text: Хранение, встроенная мебель и ведомости материалов для спокойной реализации.

ЖК Граф Орлов
Meta: СПб · квартира · авторский надзор
Text: Контроль стыков материалов, заказных элементов и соответствия проекту на объекте.

Дом в Репино
Meta: Репино · дом · реализация
Text: Имиджевый загородный проект: масштаб, архитектура, комплектация и реализация.
```

Mobile:

```text
Cards: 1 column
W: 358 px
Image H: 220–230 px
```

---

## 12. Стоимость + калькулятор

Desktop:

```text
Section padding: 104 px
Grid: left tariffs 560 px / gap 24 px / right calculator 596 px
```

Tariff cards:

```text
W: 560 px
Radius: 30 px
Padding: 32 px
Gap: 14–16 px
```

Карточки:

```text
Дизайн-проект — от 5 000 ₽/м²
Проект с сопровождением — от 8 000 ₽/м²
```

Мелко под тарифами:

```text
Технический формат — по запросу.
```

Calculator:

```text
W: 596 px
Radius: 36 px
Padding: 36 px
Fill: gradient #28231F → #1B1816
```

Поля:

```text
Площадь квартиры
Формат работы
Стоимость проекта
Ориентир реализации 130–160 тыс. ₽/м²
CTA: Получить точный расчёт
```

---

## 13. Что фиксируем до старта

Сделать компактным.

```text
Section padding: 80–96 px
Grid: 3 columns × 2 rows
Gap: 14–16 px
Card H: 150–170 px
```

Пункты:

```text
01 Состав проекта
02 Стоимость проектирования
03 Сроки этапов
04 Формат сопровождения
05 Порядок согласований
06 Зоны ответственности
```

---

## 14. Основатели

Заголовок:

```text
Проект ведут основатели студии — Антон и Наталия
```

Desktop:

```text
Grid: left image 470–500 px / gap 58 px / right text remaining
Image: circle or soft rounded square, 460–500 px
```

Тезисы:

```text
Прямая коммуникация — обсуждение решений без лишних посредников.
Контроль ключевых решений — ключевые этапы остаются в фокусе основателей.
С учётом реализации — проектируем так, чтобы интерьер можно было построить.
```

Mobile:

```text
Фото сверху
Текст ниже
3 карточки одна под другой
```

---

## 15. FAQ + форма

Desktop:

```text
Section background: #E9DED4
Padding: 104 px
Grid: FAQ 560 px / gap 24 px / form 596 px
```

FAQ — 5 вопросов:

```text
Сколько стоит дизайн-проект?
Можно ли заказать только проект без ремонта?
Делаете ли чертежи мебели?
Можно ли работать с нашей бригадой?
Когда лучше обращаться — до ключей или после?
```

Form title:

```text
Обсудим вашу квартиру до старта ремонта
```

Поля:

```text
Имя
Телефон
Комментарий / площадь квартиры
```

Checkbox:

```text
Я даю согласие на обработку моих персональных данных в соответствии с Согласием на обработку персональных данных и Политикой в отношении обработки персональных данных.
```

Ссылки:

```text
/consent
/privacy
```

Контакты:

```text
+7 904 337 18 18
studio20.18@mail.ru
```

---

## 16. Mobile sticky CTA

```text
Frame: Mobile Sticky CTA
Position: fixed bottom in prototype
X: 16 px
Bottom: 14 px
W: 358 px
H: 64 px
Radius: 999 px
Fill: #FF6B66
Stroke: rgba(255,255,255,.32)
Shadow: 0 / 20 / 54 / rgba(255,107,102,.38)
```

Text:

```text
Main: Рассчитать стоимость
Font: 15 px / 700 / white
Sub: быстрый расчёт по квартире
Font: 11 px / 600 / rgba(255,255,255,.78)
```

Добавить нижний safe area у mobile page:

```text
Bottom padding: 92 px
```

---

## 17. Порядок слоёв

```text
01 / Hero
  01. Background
  02. Header
  03. Container
    03.1 Left content
    03.2 Right visual
      Image
      Inner stroke
      Project set card

02 / Pain
03 / Journey
04 / Project Folder
05 / Builder View
06 / Portfolio
07 / Pricing
08 / Fixed Before Start
09 / Founders
10 / FAQ + Form
11 / Mobile Sticky CTA
12 / Tilda Transfer Notes
```

Переименовать ключевые группы. Не оставлять `Frame 123`, `Rectangle 45`, `Text 96`.

---

## 18. Мини-компоненты

Не делать большую дизайн-систему. Достаточно:

```text
Button / Primary
Button / Secondary
Card / Light
Card / Dark
Fact Card
Project Card
Tariff Card
FAQ Item
Tab / Default
Tab / Active
Folder Tab / Default
Folder Tab / Active
Input Field
Mobile Sticky CTA
```

---

## 19. Tilda transfer notes

Создать отдельный frame:

```text
Frame name: Tilda transfer notes
Width: 1180 px
Background: #FFFAF3
Radius: 28 px
Padding: 40 px
```

### Zero Block

Собирать в Zero Block:

```text
01 Hero
03 Визуализация → Чертёж → Реализация
04 Проектная папка
05 Проект глазами строителя
06 Портфолио
07 Стоимость + калькулятор
09 Основатели
```

### Standard Tilda blocks

Можно собрать стандартными блоками и донастроить:

```text
FAQ
Форма
Footer / contacts
```

### T123

Нужен T123 / HTML-code block для:

```text
калькулятора стоимости;
tabs, если стандартная логика Tilda не подходит;
mobile sticky CTA, если не получается штатными средствами;
дополнительных hover-состояний.
```

---

## 20. Изображения, которые нужно подготовить

```text
1. Hero-фото интерьера — горизонтальное, спокойное, архитектурное.
2. 6 фото / визуализаций проектов:
   - ЖК Чёрная речка
   - GloraX Premium
   - Project 6/3
   - Ботаника 2
   - ЖК Граф Орлов
   - Дом в Репино
3. Фрагмент рабочего чертежа — план.
4. Фрагмент чертежа мебели.
5. Фрагмент ведомости / спецификации материалов.
6. Фото Антона и Наталии / фото на объекте.
7. При наличии — фото со стройки / авторского надзора без визуального шума.
```

---

## 21. GitHub structure

```text
/docs/
  figma-polish-map.md
  tilda-transfer-notes.md

/assets/
  hero/
    hero-interior.jpg
  portfolio/
    chernaya-rechka.jpg
    glorax-premium.jpg
    project-6-3.jpg
    botanika-2.jpg
    graf-orlov.jpg
    repino-house.jpg
  documents/
    drawing-plan.jpg
    furniture-drawing.jpg
    material-schedule.jpg
  founders/
    anton-natalia.jpg

/prototype/
  studio-2018-landing-preview-polished.html
```

---

## 22. Финальный чек-лист

```text
[ ] Первый экран не давит H1.
[ ] Правая часть hero не пустая.
[ ] Карточка “Рабочий комплект проекта” встроена в композицию.
[ ] Факты не выглядят приклеенной полосой.
[ ] Все карточки имеют одинаковые радиусы, stroke, shadow.
[ ] Коралловый используется только как акцент.
[ ] Инфографика выглядит частью дизайн-системы.
[ ] Desktop 1440 читается без перегруза.
[ ] Mobile 390: сначала H1 + CTA, потом фото, потом факты.
[ ] Sticky CTA не перекрывает важный контент.
[ ] FAQ компактный.
[ ] Форма содержит checkbox и ссылки /consent /privacy.
[ ] Нет Instagram / Facebook / Meta / WhatsApp.
[ ] Нет фейковых отзывов.
[ ] Нет фраз: “интерьер мечты”, “уникальный дизайн”, “индивидуальный подход”, “создаём уют”.
```
