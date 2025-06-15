# Stellar Burger

Веб-приложение для создания и заказа вкусных бургеров онлайн.

![Превью проекта](https://github.com/dianaMatas/stellar-burger/assets/38656496/f5939c71-7f4b-44d6-ab49-e5bac1b40b11)

## Деплой проекта

Проект доступен по ссылке:
[https://dianaMatas.github.io/stellar-burger/](https://dianaMatas.github.io/stellar-burger/)

## Технологии

* React + TypeScript
* Redux Toolkit для управления состоянием
* React Router (HashRouter) для маршрутизации
* Webpack для сборки проекта
* Cypress для функционального тестирования
* ESLint + Prettier для поддержания качества кода

## Особенности

* Авторизация и регистрация пользователей
* Защищённые маршруты (доступ только для авторизованных)
* Хранение токенов в cookie
* Тестирование бизнес-логики и UI-компонентов

## Установка и запуск

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/dianaMatas/stellar-burger.git
   ```
2. Установите зависимости:

   ```bash
   npm install
   ```
3. Запустите проект в режиме разработки:

   ```bash
   npm start
   ```
4. Для сборки и деплоя:

   ```bash
   npm run build
   npm run deploy
   ```

## Структура проекта

* `src/components` — React-компоненты
* `src/services` — Redux store и слайсы
* `src/hooks` — кастомные хуки
* `src/utils` — вспомогательные функции и API-запросы

