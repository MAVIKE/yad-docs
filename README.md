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

# Технологии

## Стек

### Backend

- [Golang](https://golang.org/)
- [Echo framework](https://github.com/labstack/echo)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

### Mobile

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

<img src="docs/ryazanov.png" 
     alt="Maxim Ryazanov"
     width="200"
/>

<div style="text-align: center">

**Максим Рязанов**

ryazanovms@yandex.ru

</div>

</td>
<td>

<img src="docs/stepanenko.jpg" 
     alt="Vladimir Stepanenko"
     width="200"
/>

<div style="text-align: center">

**Владимир Степаненко**

vovac12@gmail.com

</div>

</td>
</tr>
</table>
