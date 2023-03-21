# Тестовое задание на позицию python developer (odoo)

Необходимо разработать модуль (приложение) Odoo_<ваш никнейм> для платформы Odoo Community Edition v. 15.

## Задача 1

**Описание функционала модуля**: Модуль устанавливается в чистый инстанс Odoo Community Edition v.15, после установки становится доступен следующий функционал модуля.

В модуле Sale, который присутствует по умолчанию в Odoo в Quotations  вид form появляется новое текстовое поле «Test».

- По умолчанию, когда пользователь создает новый Quotation поле «Test» заполняется случайным числом.

- Если пользователь меняет строки (продукты) Quotations или изменяет Quotation Date, то значение меняется на лету на текст в формате «Total - Date» (пример значения: 8,287.50 - 02/06/2022 16:33:53)

- Новое поле «Test» доступно для редактирования только если  Quotations на этапе Draft

- Если пользователь вручную вводит текст длиной более 50 символов, то появляется сообщение «Длина текста должна быть меньше 50 символов!»

- Значение поля «Test», если оно не пустое, тогда данное поле отображается в печатной форме Print > Quotation / Order, в любом месте над таблицей товаров. Если поле «Test» пустое, то оно не отображается.

Для создания интерфейса используются стандартные средства UI Odoo.

Поставка модуля осуществляется в стандартном для Odoo формате, готовом для установки в чистый инстанс Odoo Community Edition v.15.
