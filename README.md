“Разработка web-приложения “Платформа для изучения иностранных языков” с использованием технологий HTML, CSS, JavaScript, JQuery”
Цели
Разработать web-приложение (SPA) для изучения иностранного языка. В качестве объекта изучаемого языка используем английский. 
Задачи
1.	Разработать сайт (SPA) с описанием методики обучения
2.	Разработать модуль “Обучение”
3.	Разработать модуль “Тестирование”
4.	Разработать модуль “Обратной связи”
5.	Разработать модуль “Регистрации и Авторизации”
Технические подробности
Используемые технологии
1.	Гипертекстовый язык разметки HTML ;
2.	Каскадные таблицы стилей CSS;
3.	Фреймворк Bootstrap 4;
4.	Язык программирования JavaScript;
5.	Библиотека React JS;
6.	Библиотека jQuery;
7.	База данных MySQL;
8.	Язык программирования PHP;
Технические особенности
1.	Разработка приложения выполнена с помощью библиотеки React JS и скомпилирован для работы на сервере. 
2.	Используемый хостинг для разработки:  http://beget.tech
3.	Сайт с web-приложением доступен по адресу: http://u915186o.beget.tech/
4.	Исходный код проекта: https://github.com/hillel88/finishproject
Интерфейс и дизайн
Сайт с web-приложением был создан, как растягивающийся под любую
ширину экрана. Интерфейс web-приложения имеет адаптивный дизайн для просмотра на мобильных устройства, планшетных компьютерах и перснональных компьютерах.
Обзор web-приложения
Все страницы сайта состоят из Menu, Body и Footer.
Главная страница
Содержит первичное описание сервиса и предложения получить “Больше информации”.
Страница “Методика”
Содержит краткое описание “Как это работает” и кнопки с предложением “Начать обучение”. Предусмотрен переход на страницы “Обучение” и “Тестирование.”
Страница “Обучение”
Содержит краткую информацию по описанию процесса обучения.
Также, страница генерирует 10 случайных слов из таблицы базы данных (далее-БД) для обучения иностранным словам. Пользователю предоставлена возможность управления: изученные слова могут быть удалены из базы данных и со страницы сайта.
Страница “Тестирование”
Содержит систему тестирования. На страницу в кнопки выводятся 4 случайных русских слова из таблицы БД, а также английское слово, являющееся переводом одного из русских слов. По клику пользователя на русское слово становится возможным получить вывод перевода выбранного слова из таблицы БД в отдельную кнопку. 
Страница “Категории”
Предоставляет возможность выбрать категорию изучаемых слов. Переход на страницу “Категории” возможен также со страницы “Обучение” по клику на слово «категория» в табличной части страницы.
Страница “Обратная связь”
Содержит форму обратной связи для получения контактных данных и сообщения на стороне сервера. Данные отправляются в таблицу в БД.
Страница “Вход”
На данной странице реализована авторизация на сайте.  
Страница “Регистрация”
На данной странице реализована система регистрации на сайте. Данные передаются в таблицу в БД. Повторная регистрация с одинаковым email не возможна. В данном случае на экран выводится запись о том, что такой  email уже существует. После регистрации осуществляется редирект на страницу “Авторизация”.
а данной странице реализована авторизация на сайте.  
