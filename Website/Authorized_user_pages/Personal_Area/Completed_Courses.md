"Завершенные курсы"
===================

Ссылка: [https://academyopen.ru/lk](https://academyopen.ru/lk)

Дизайн: [https://www.figma.com/file/VGj0ApfoPj2GDLwxDvT56M/open_academy-LK?node-id=16%3A2](https://www.figma.com/file/VGj0ApfoPj2GDLwxDvT56M/open_academy-LK?node-id=16%3A2)

**Общая информация:**

1.  **Завершенный Курс** - Курс, в котором пользователь просмотрел все уроки и прошел Тест хотя бы один раз (успешно или два раза неуспешно).

Блоки
-----

Состоит из одного блока, отображающего список Завершенных Курсов пользователя по дизайну. Структура плашки Курса:

1.  Цель / [Изображения](./Image.md) - поле сущности Цели, привязанной к Курсу

2.  Цель / [Название](./Name.md) - поле сущности Цели, привязанной к Курсу

3.  Количество уроков в виде: кол-во пройденных уроков / общее кол-во уроков

5. Кнопки повторного прохождения

5.1. Если пользователь не прошел ни одного урока Курса, текст кнопки - "Начать" и при клике происходит переход на страницу Курса

5.2. Если пользователь прошел один или более урок, либо просмотрел все уроки и прошел тест неуспешно (один раз) - текст кнопки "Продолжить" и при клике происходит переход на страницу Курса