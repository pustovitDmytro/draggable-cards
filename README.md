# draggable cards
react-redux SPA with drag and drop integration
test assignment for taking position of Front End Software Engineer at [zakaz](https://zakaz.ua) company.

## How to Install:

To download and launch project run theese commands in console:
```sh
git clone https://github.com/pustovitDmytro/draggable-cards app
cd app
```
```sh
yarn assemble
yarn start:http-server
```
browse [localhost:7000](http.localhost:7000).

To start webpack dev-server launch:
```
yarn start:dev-server
```
browse [localhost:5000](http.localhost:5000).

If you need just to build the app (without running a dev server), simply run:
```
yarn build
```

## Boilerplate

check mine [repo](https://github.com/pustovitDmytro/react) for tiny and fast boilerplate.

## Task:
Необходимо реализовать приложение доски задач. Пример UI:

![Sample screenshot](http://i.imgur.com/IDWXA55.png "Sample screenshot")

Пользовательские сценарии:
- создать колонку и назвать ее
- перемещать колонки местами
- создать карточку в колонке и назвать ее
- удалить карточку из колонки
- переносить карточку из колонки в колонку
- удалить колонку и все карточки в ней
- перемещать карточки внутри колонки местами
- отредактировать имя карточки
- отредактировать имя колонки
- использовать горизонтальную и вертикальную прокрутку, если доска не влазит на экран

Обязательные требования:
- Использование React + Redux/MobX или другой state management tool
- Использование webpack или аналога

Будет плюсом:
- Адаптивно-отзывчивая верстка под разные устройства (в первую очередь мобильные)
- Использование SCSS/SASS или аналогичного

Публикация результата:
- написать README для разворачивания проекта
