# AKino. Страница подборок. Страница премьер. Страница жанров. Профиль. Шапка

## Страница подборок

Пример: https://park-akino.ru/collections


1. По нажатию на подборку из списка подборок происходит переход на страницу соответствующей подборки.
2. На странице должно быть 12 видов подборок.

## Страница премьер

Пример: https://park-akino.ru/premiers

1. По нажатию на премьеру из списка премьер происходит переход на страницу соответствующей премьеры.
2. На странице 

## Страница жанров

Пример: https://park-akino.ru/genres

1. По нажатию на жанр из списка жанров происходит переход на страницу соответствующего жанра.
2. На странице должно быть 20 видов подборок по жанрам.

## Шапка

### Если не авторизован
1. При нажатии на кнопку "Войти" происходит переход на страницу авторизации.

### Если авторизован

2. Если пользователь авторизован, то вместо кнопки "Войти" находится кнопка в виде аватарки пользователя.
3. При наведении на аватарку пользователя появляется выпадающий список с двумя кнопками "Профиль" и "Выйти".
4. При нажатии на аватарку пользователя происходит переход в профиль пользователя.
5. При нажатии на кнопку "Профиль" в выпадающем списке после наведения на аватарку пользователя происходит переход на страницу пользователя.
6. При нажатии на кнопку "Выйти" в выпадающем списке после наведения на аватарку пользователя происходит выход из аккаунта, а аватарка пользователя заменяется на кнопку "Войти".

### Общие проверки

7. При нажатии на кнопку "Подборки" она окрашивается в розовый цвет.
8. При нажатии на кнопку "Премьеры" она окрашивается в розовый цвет.
9. При нажатии на кнопку "Жанры" она окрашивается в розовый цвет.
10. При нажатии на логотип происходит переход на главную страницу (https://park-akino.ru).
11. При нажатии на иконку лупы происходит переход на страницу поиска.

## Профиль

Пример: https://park-akino.ru/profile/38

### Если пользователь авторизован и находится на своей странице

1. По нажатию на аватарку открывается форма для загрузки файлов.
2. Имеется кнопка "Изменить", по нажатию на которую появляется поле ввода и две кнопки "Сохранить" и "Отменить".
3. Если нажать на кнопку "Отменить", то поле ввода, кнопки  "Сохранить" и "Отменить" пропадут, появится кнопка "Изменить".
4. Если нажать на кнопку "Сохранить" при пустом поле ввода, то появится надпись "Заполните поле!".
5. Если ввести текст в поле ввода и нажать на кнопку "Сохранить", то имя профиля изменится на введенное в поле, а поле ввода, кнопки  "Сохранить" и "Отменить" пропадут, появится кнопка "Изменить".
6. При нажатии на подборку из списка подборок происходит переход на страницу личной подборки (https://park-akino.ru/bookmarks/120).
7. При нажатии на кнопку "+" появляется popup форма с полем ввода, кнопкой "Создать подборку"  и кнопкой с иконкой "x".
8. При нажатии на кнопку "Создать подборку" при пустом поле ввода подборка не создается, popup форма не закрывается.
9. При нажатии на кнопку с иконкой "x" popup форма закрывается.
10. При вводе названия новой подборки и нажатии кнопки "Создать подборку", подборка создается и добавляется в список "Мои подборки", popup закрывается.
11. При нажатии на область вне popup формы происходит закрытие popup формы.
12. При нажатии на постер или название фильма происходит переход на страницу соответствующего фильма.

### Если пользователь находится не на своей странице

13. Если пользователь находится на странице не своего профиля, то ему видны только открытые для всех личные подборки.

