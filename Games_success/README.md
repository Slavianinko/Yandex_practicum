# Анализ успешности игр.

Статус проекта: | В плане :black_square_button: | Выполняется :black_square_button: | Завершён :white_check_mark: | 
:------------ | :-------------| :-------------| :-------------

## Задача:

Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Наша цель - выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Перед нами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и мы планируем кампанию на 2017-й.

## Данные:
Входные о играх:
- название игры
- платформа
- год выпуска
- жанр игры
- продажи в Северной Америке
- продажи в Европе
- продажи в Японии
- продажи в других странах
- оценка критиков
- оценка пользователей
- рейтинг от организации ESRB

## Используемые библиотеки:
- pandas
- matplotlib
- numpy
- seaborn
- scipy

## Отработанные методы и навыки
- Предобработка данных;
- Исследовательский анализ данных;
- Визуализация данных.
- Проверка гипотез с помощью t-теста.

## Итоги исследования

Главный вывод, который можно сделать по результатам анализа, это то, что в 2017 году перспективными игровыми платформами можно считать только PS4, XOne. Однако, продажи игр в сегменте игровых платформ падают на протяжении последних восьми лет. Выход новых игровых платформ ситуацию не меняет. Это связано, скорее всего, с переходом пользователей на игры на мобильных телефонах. По крайней мере это справедливо для портативных игровых платформ. Поэтому интернет магазину «Стримчик», в 2017 году, необходимо направить рекламный бюджет на стационарные игровые платформы PS4 и XOne, а с портативных ировых платформ, переориентировать бизнес на продажу игр для мобильных телефонов. Как это сделать, с учётом того, что большинство игр для мобильных телефонов продаются с помощью AppleStore и GooglePlay - тема отдельного исследования.
