Вкладка "Мои курсы"
===================

Ссылка: [https://academyopen.ru/lk](https://academyopen.ru/lk)

Дизайн: [https://www.figma.com/file/VGj0ApfoPj2GDLwxDvT56M/open_academy-LK?node-id=16%3A2](https://www.figma.com/file/VGj0ApfoPj2GDLwxDvT56M/open_academy-LK?node-id=16%3A2)

Отображает активные Курсы пользователя, добавленные им на вкладке **[Бизнес-цели](/Website/Control_logic/Business_goals.md)** .

**Общая информация:**

1.  Пользователь не может иметь более 3-ех активных Курсов

2.  Пользователь может удалить активный Курс в любой момент обучения. При повторном добавлении Курса в активные - пройденные уроки не сбрасываются, а далее считаются пройденными

3.  **Активный Курс -** Курс, который пользователь изучает в данный момент. Курс считается активным, пока пользователь не просмотрел все его уроки и не прошел Тест (успешно или два раза неуспешно).

Блоки
-----

Состоит из одного блока, отображающего список активных Курсов пользователя по дизайну. Структура плашки Курса:

1.  Цель / [Изображения](./Image.md) - поле сущности Цели, привязанной к Курсу

2.  Цель / [Название](./Name.md) - поле сущности Цели, привязанной к Курсу

3.  Количество уроков в виде: кол-во пройденных уроков / общее кол-во уроков

4.  _**Кнопки с иконкой "Крестик"**_

Выводиться попап с текстом "Вы собираетесь закрыть курс. Вновь добавить этот или другой курс вы можете из раздела "Бизнес-цели" и кнопкой "Хорошо".

1) При закрытии попапа - ничего не происходит

2) При нажатии на кнопку "Хорошо" - Курс удаляется из активных (Мои курсы). Пользователь имеет возможность вернуться к нему, выбрав заново в списке Курсов на вкладке Бизнес-цели.

5. _**Кнопки перехода на страницу Курса**_

5.1. Если пользователь не прошел ни одного урока Курса, текст кнопки - "Начать" и при клике происходит переход на страницу Курса

5.2. Если пользователь прошел один или более урок, либо просмотрел все уроки и прошел тест неуспешно (один раз) - текст кнопки "Продолжить" и при клике происходит переход на страницу Курса