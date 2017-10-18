WebStore
=====================

### 45VVJ:
1. SDFS
2. SDFSDF
3. ASD
4. ASDASG

**Структура страниц**

INDEX PAGE     | CATEGORY PAGE    | PRODUCT PAGE
---------------|------------------|---------------
HEADER         | HEADER           | HEADER
CAROUSEL       | CATEGORY-WRAP >  | SLIDER
NEW-ARRIVALS   | > OVERLAY        | RELATED
---            | > SIDEBAR        | ---
KIT            | ---              | ---
BEST-SALES     | ---              | ---
NEWS-LETTER    | NEWS-LETTER      | NEWS-LETTER
FOOTER         | FOOTER           | FOOTER


@MEDIA
Название папок  | Содержание файла
----------------|----------------------
app             | Директория с готовым проектом
app/css         | Готовые стили к продакшену
app/js          | Готовый js к продакшену
app/img         | Готовые картинки к продакшену
app/fonts       | Шрифты
src             | Директория с исходными файлыми
src/css         | Исходные стили, здесь мы пишем наши стили и они будут конвертироваться в app/css
src/img         | Исходные картинки, они будут минифицироваться и перегоняться в app/img
src/js          | Исходный js будет минифицироваться и переносится в app/js
src/sprite      | Папка для нарезанных картинок под будущие спрайты, после конветрации попадут в app/img