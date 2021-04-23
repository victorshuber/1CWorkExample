# 1CWorkExample
My work examination example. Created after complete top-soft public examitation tasks. Task was complete at 1C v8.3 (Учебная версия)

Задачи из таск листа:

Время на выполнение 1,5 часа.
- Получить от экзаменатора файл с описанием задания и pdf файл с методичкой.
- Создать пустую БД в каталоге DB на рабочем столе.

ЗАДАНИЕ:
//
Создать документ "Продажа".
Создать таблицу "Товары" с реквизитами: "Товар", "Цена", "Количество", "Сумма", "Склад".
При изменении суммы и количества пересчитывать цену. Код вынести в общий модуль.

//
Создать справочник "Товары".
Настроить длину и тип кода исходя из того, что на практике создаётся не более чем пару десятков тысяч товаров и код состоит из серии и номера которые оператор вносит вручную.
В режиме "Предприятие" внести только 2 группы в каждой по 2 элемента.
Добавить таблицу "Состав" с колонками: "Ингредиент" (Строка), "Количество". Разместить таблицу на форме элемента и показывать итог по колонке "Количество".

//
Создать регистр накопления "Остатки товаров".
Регистр должен хранить количественные и суммовые остатки товаров на складах.
Оба документа должны при проведении делать движения по регистру. Провести документы в режиме "Предприятие".

//
Создать документ "Поступление".
Создать реквизиты шапки документа: "Склад". Создать табличную часть "Товары" с колонками: "Товар", "Цена", "Количество", "Сумма".
Создать кнопку при нажатии которой во всех строках таблицы пересчитает "Сумму" по "Количеству" и "Цене". Код вынести в общий модуль.
При помощи конструктора создать печатную форму документа.
Добавить область "Информация поставщика" в которой по центру документа должно быть написано: Получено от (здесь должно быть название поставщика) по накладной номер (здесь должен быть номер текущего документа).
В подвале таблицы выводить область с итогом числовых колонок.

//
Создать отчет "Остатки товаров на складах".
Отчет должен быть по типу "Оборотно-сальдовая ведомость" и должен показывать остатки и обороты по всем ресурсам регистра.
Настроить итоги и группировки по Товарам и Складам.

//
Создать справочник "Склады".
Настроить длину и тип кода исходя из того, что на практике создаётся не более чем половина тысячи складов и в качестве кода используется порядковый номер.
Создать предопределённый склад с названием "Это главный склад на который должны поступать все покупки".
