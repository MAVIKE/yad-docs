# Yet Another Delivery

# Техническое задание

## Описание предметной области

Cервис осуществляет прием заказов на доставку и распределяет их по ресторанам и курьерам.

Основные сущности:
* Ресторан - стороннее лицо, предоставляющее приложению доступное меню, принимающее от сервиса заявки на приготовление заказов.
* Меню - список доступных позиций, предоставляемых рестораном.
* Позиция - блюдо или иная продукция с определенной стоимостью, производимая рестораном и доступная к доставке через приложение.
* Заказ - набор позиций из одного ресторана, сформированный пользователем для единовременной доставки.
* Пользователь - человек, осуществляющий заказы через мобильное приложение.
* Курьер - человек, назначаемый приложением для забора заказа из ресторана и доставки его пользователю.
* Администратор - доверенное лицо, обладающее правами внесения новых курьеров и ресторанов в систему.


## Функциональные требования

Первоначально пользователю необходимо осуществить регистрацию учетной записи и вход в нее.

Авторизованный пользователь может выбрать определенный ресторан, просмотреть список доступных в нем позиций и сформировать заказ, добавив блюда в корзину. Оформление заказа завершается оплатой. 
Дополнительно пользователь может просматривать историю заказов и отслеживать статус своего текущего заказа, отправить сообщение в службу поддержки через специальную форму.

Информация о сформированном заказе поступает в ресторан, статус заказа обозначается “Готовится”. Ближайший к ресторану свободный курьер получает заявку на доставку заказа.

Авторизованный курьер может устанавливать статус работы (работает/не работает). Получив заказ и забрав готовые блюда из ресторана, курьер меняет статус заказа на “В пути”. После доставки заказа конечному пользователю курьер меняет статус на “Доставлен”.

Администратор добавляет в систему новых курьеров и информацию о ресторанах.

# Технологии

## Репозитории

:computer: [Backend](https://github.com/MAVIKE/yad-backend)

:iphone: [Mobile](https://github.com/MAVIKE/yad-android)

## Стек

### Backend

- [Golang](https://golang.org/)
- [Echo framework](https://github.com/labstack/echo)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

### Mobile
 - [Java](https://www.java.com/ru/)
 - [JUnit](https://junit.org/junit4/javadoc/4.12/overview-summary.html)
 - [Gradle](https://gradle.org/)
 - [SQLite](https://www.sqlite.org/index.html)

## Регламенты кодирования

[Backend](backend/rules.md)

[Mobile](https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md)

## Правила ветвления

[Шпаргалка по git-flow](https://danielkummer.github.io/git-flow-cheatsheet/index.ru_RU.html)

<img src="docs/git-flow.png" alt="git-flow" width="1000"/>

## Правила версионирования

[Semantic Versioning 2.0](https://semver.org/)

# Участники команды

## Backend

<table>
<tr>
<td>

<img src="docs/vasyukov.jpg" alt="Vasyukov Alexey" width="200"/>

</td>
<td>

<img src="docs/volkov.jpg" alt="Volkov Egor" width="200"/>

</td>
<td>

<img src="docs/kolesnikov.jpg" alt="Kolesnikov Daniil" width="200"/>

</td>
<td>

<img src="docs/moskovskiy.jpg" alt="Moskovskiy Dmitriy" width="200"/>

</td>
</tr>

<tr>
<td>

**Васюков Алексей**
a.vasyukov1@yandex.ru

</td>
<td>

**Волков Егор**
volkovegor2000@yandex.ru

</td>
<td>

**Колесников Даниил**
daniil.kolesnikoff@gmail.com

</td>
<td>

**Московский Дмитрий**
dimez77@mail.ru

</td>
</tr>
</table>

## Android application

<table>
<tr>
<td>

<img src="docs/ryazanov.png" alt="Ryazanov Maxim" width="200"/>

</td>
<td>

<img src="docs/stepanenko.jpg" alt="Stepanenko Vladimir" width="200"/>

</td>
<td>

<img src="docs/polyakova.jpg" alt="Polyakova Kseniya" width="200"/>

</td>
<td>

<img src="docs/gopher.jpg" alt="Levushkin Ilya" width="200"/>

</td>
</tr>

<tr>
<td>

**Рязанов Максим**
ryazanovms@yandex.ru

</td>
<td>

**Степаненко Владимир**
vovac12@gmail.com

</td>
<td>

**Полякова Ксения**
KsenyaPolyakovaaa@gmail.com

</td>
<td>

**Левушкин Илья**
levushkinik@yandex.ru

</td>
</tr>
</table>
