## V2.1.0.1.1 Українська версія (11.01.2016)
#### Виправлено
* Усунена помилка додавання виробника
* Усунена помилка при створенні банерів
* Правки некоректного перекладу
* Усунення помилки при відправленні розсилки
* Виправлена проблема, що виникала в сторонніх модулях, нічого не знаючих про CKEditor в ocStore, у випадку, якщо редактором за замовчуванням вибрано CKEditor.
* Виправлення заголовка в статтях
* Виправлення помилки з вибором виробника при редагуванні товару
* Відновлення роботи модуля доставки
* Виправлені дрібні помилки

#### Змінено
* У головній категорії можна вибрати категорію з усіх категорій
* Видалення зайвих нулів в ДxШxВ та інших місцях

#### Додано
* Фільтр по категоріях на сторінці списку товарів в адмінці
* Доданий український мовний пакет


## V2.1.0.1 (16.10.2015)
#### Виправлено
* Виправлена ​​пагінація (видалено дубль першої сторінки, прибрано дублювання мета) (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)

#### Змінено
* У логотипі на головній прибрано посилання на саму себе (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Виправлена ​​пагінація (видалено дубль першої сторінки, прибрано дублювання мета) (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Приховано Владки Google через дублювання функціоналу (https://github.com/myopencart/ocStore/commit/8c69328587afed7314ccc16be2dd6c33825a97aa)
* Змінена організація виведення категорій в адмінці (https://github.com/myopencart/ocStore/commit/ce3a87686f409bc27afbba93066948ab73ae66b2)
* Змінений сервіс отримання інформації про IP-адресу покупців з www.geoiptool.com на ipgeobase.ru
* У списку замовлень кнопки редагування замовлення стає не активною, якщо немає дозволеного IP в API

#### Додано
* Доданий російський мовний пакет
* Локалізація бази (схеми, статуси, повернення)
* Додана мультимовність календаря
* Доданий редактор CKEditor, з'явилася можливість вибору редактора (https://github.com/myopencart/ocStore/commit/12133094f78ef255e8c54e284492514581e3fde9)
* Додана мультимовність редактора summernote (https://github.com/myopencart/ocStore/commit/a3c9fc8ae3a276f3bc35b4a870051c05ac265141)
* Модуль оплати Qiwi (https://github.com/myopencart/ocStore/commit/6f3c823144f5177465c8392c4664444b8daf53e3)
* Модуль для створення розсилок через сервіс Unisender (https://github.com/myopencart/ocStore/commit/6008dbe82466afd80fb9e461d705aa7442ef7403)
* Модуль доставки - доставка в залежності від суми замовлення (https://github.com/myopencart/ocStore/commit/94cdb34c5e6cc5ae16527d084044e7490f8579fc)
* Можливість самостійного введення регулярного виразу для валідації email (https://github.com/myopencart/ocStore/commit/614b8ea91d0820835c5e8839542ae41bce754ce5) (https://github.com/myopencart/ocStore/commit/e2f13036e3dd5b4f77d7c0114f078c040a38dee3)
* Додавання мета-тегів og: url, og: image, og: type, og: title (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Додавання файлу robots.txt (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Додані title і h1 для товарів (https://github.com/myopencart/ocStore/commit/1fcdc182c0ec079a73ca97ac9bdb685cdbdab089)
* Додані title і h1 для категорій (https://github.com/myopencart/ocStore/commit/a653a171e03e111a423b4ddcec65607bacb49291)
* Для статей додані title, h1, meta keywords і meta description; (https://github.com/myopencart/ocStore/commit/b01352a7e52f3faab7155a903a77576a75138cce)
* Для виробників додані мультимовні імена, title, h1, meta keywords, meta description і description; (https://github.com/myopencart/ocStore/commit/6f3da8c5d059a08fb3ea07fd1dc3f555a6a24cbb)
* Доданий альтернативний метод формування ЧПУ виключає формування різних посилань для однієї сторінки; (https://github.com/myopencart/ocStore/commit/2bbb96c5ec2fd09821cf33c6b19e70ffb8fd303f) (https://github.com/myopencart/ocStore/commit/1bec354689300dfbd2dcf6242ccafcde06316419)
* Додано url alias для базових сторінок
* Доданий SeoPro
* Додана відправка SMS повідомлень
* Додано корисні інструменти від OC Team (https://github.com/myopencart/ocStore/commit/6ad5ef1f9b33727e9d27ca16142036400770787f)
* Додана можливість видалення кеша системи і зображень
* Додано можливість приховування не часто використовуваних полів через настройки магазину (MPN, ISBN, JAN і т.д.) (https://github.com/myopencart/ocStore/commit/ae421d72af8545a9e7194cbe43c84330950f84e7)
* Додана можливість приховування що не використовуються модулів, методів оплат і доставок (https://github.com/myopencart/ocStore/commit/36a616f3cc613dcb4fd491772c41f7966cd0ea22)
