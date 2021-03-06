Тактика действий на командных контестах
=======================================

Сначала отметим, что обсуждение каждой задачи должно состоять из следующих
этапов (не обязательно при этом задача решена):

-   Прочтение задачи каждым из обсуждающих (если оно длинное, то можно
    рассказать условие)

-   Не менее 1–2 минут на размышления над ними

-   Непосредственно обсуждение идейной части решения

-   Если решение трудоёмкое (для его написания нужно более получаса), то
    обсуждается и каркас решения. 

Разделим все задачи на три типа в зависимости от ожидаемого времени написания:

-   Простые (до 10 минут)

-   Средние (10–30 минут)

-   Сложные (от 30 минут)

Типичный контест делится на четыре важные части:

1.  Начало контеста (00:00 – 01:00)

2.  Первая половина контеста после начала (01:00 – 02:30)

3.  Вторая половина контеста до заморозки (02:30 – 04:00)

4.  Заморозка (04:00 – 05:00)

 

Начало контеста (00:00–01:00)
-----------------------------

-   Условия делятся на три части для всех участников

-   При прочтении задачи нужно подумать 1–2 минуты над ней

-   После прочтения последней задачи в блоке следует выбрать задачу которая
    кажется самой простой и думать над ней

-   Если задача решена, то в зависимости от сложности:

    -   Простая — стоит начать писать сразу

    -   Средняя — нужно дочитать остальные задачи а потом она становится простой

    -   Сложная — отложить её и искать простые

### Итог:

1.  Каждый знает задачи в своём блоке

2.  Некоторые простые задачи уже сданы

3.  Некоторые сложные уже идейно решены

 

Первая половина контеста (01:00–02:30)
--------------------------------------

-   При наличии идейно решённой (и обсуждённой) задачи, сразу начинать её писать

-   Когда кто-то пишет задачу, остальные два рассказывают друг другу задачи из
    своих блоков

-   После того как произошёл обмен задачами, каждый выбирает себе задачу которая
    кажется простой и начинает думать над ней

-   При наличии решения средней или сложной задачи, оно обсуждается и попадает в
    очередь

### Итог:

1.  Некоторые средние (сложные) задачи сданы

2.  Каждую задачу знают хотябы двое(\*)

3.  Намечен план сдачи следующих нескольких задач

(\*) Кроме случаев когда кто-то один сидел за компьютером всю эту фазу.

 

Вторая половина контеста (02:30–04:00)
--------------------------------------

-   Если есть ещё решённые задачи, то они пишутся, остальные двое думают каждый
    над своей задачей

-   Если у одного из сокомандников нет идей, но есть идеи относительно
    нерешённых задач у пишущего, то (если это не увеличивает время написания
    больше чем на 5–10 минут) происходит замена

-   Если нет решённых задач, над одной из текущих думают двое

-   Если нерешённых задач мало, то каждый должен знать все задачи

### Итог:

1.  Над решением задач думали по меньшей мере двое

2.  Если не было решённых задач, то над одной из задач думали комплексно

 

Заморозка (04:00–05:00)
-----------------------

-   В этот период решается (и сдается) не более двух задач

-   Над остальными даже не пытаются думать — на все времени не хватит

-   В написании первой задачи участвуют минимум двое

-   В написании последней задачи участвует вся команда

### Итог

1.  Оптимальный результат команды

2.  Отсутсвие большого количества решённых задач во вред несданным.

 

Тактика действий с одной задачей
================================

 

Решение одной задачи должно происходить по сценарию:

1.  Придумано решение задачи

2.  Если задача не простая, то обсуждение решения с сокомандником

3.  Ожидание места за компьютером

4.  Написание решения задачи

5.  Если задача сложная и это не очень тяжело (менее 10 минут), вместе с
    стресс-тестом

6.  Поверхностное тестирование

7.  Беглая проверка другим сокомандником (типы, файлы, константы)

 

Если над задачей сразу работает два и более членов команды (преимущественно на поздних стадиях), то остальные члены команды (которые не заняты непоредственно кодированием, но работают над этой же задачей) могут заняться:

-   придумывание тестов

-   продумывание генератора / чекера

-   проверка кода

-   проверка крайних случаев

 

Но так бывает, что задача не сдаётся сразу:

1.  Первые 5 минут ошибка ищется как есть

2.  Печатается код и ошибка ищется на листике

3.  Если прошло уже 10 минут поиска её на листике, то

    1.  Перечитывается условие предельно внимательно

    2.  Ещё раз доказывается корректность решения

    3.  Обсуждается решение с свободным сокомандником

    4.  Пишется стресс-тест

Очень важно придерживаться следующих правил при написании задачи:

-   Все отступы, пробелы, переносы строк расставляются в соответсвии с принятым
    code-style-guide

-   Большое количество пустых строк разительно увеличивает читаемость, если они
    расположены в уместных местах.

-   Между top-level блоками следует ставить не менее двух пустых строк. К
    top-level блокам относятся:

    -   Список type-alias'ов

    -   Список прототипов

    -   Интерфейс класса(структуры)

    -   Код функции/реализации метода

-   Вся система блочная, морально разные вещи должны происходить в разных блоках
    кода и должны иметь возможность быть заменены на другие реализации если
    необходимо

-   Название переменных человекопонятны и говорят сами за себя, это нужно в
    ситуациях:

    -   Сейчас вы пытаетесь исправить проблему и бегло разбираетесь в коде

    -   Вы дописываете чужую задачу

    -   Возвращаетесь к задаче через долгое время

    -   Вы не читали условие задачи (сокомандник сам вам его рассказал)

-   Написание кода начинается с архитектуры сверху-вниз:

    1.  Начать с абстракции необходимых типов. Это нужно для того чтобы  
        не путаться самому и иметь возможность на лету заменить underlying-типы:

        -   Заменить `int` на `int64_t` в борьбе с переполнением

        -   Заменить `std::vector<Node>` на `std::set<Node>` внутри определения
            графа чтобы сделать поиск ребра за `O(log n)` сохранив при этом
            линейный обход

        -   Заменить беззнаковый тип на знаковый если нужна арифметика с
            отрицательными числами

    2.  Изначально единственная ненаписанная функция — `main`

    3.  При написании каждой функции следует:

        1.  Над функцией поместить весь необходимый ей функционал: интерфейсы
            классов, прототипы фукций

        2.  Реализовать саму функцию настолько просто, насколько это возможно

    4.  Потом следует переходить к следующей нереализованной функции

-   При написании стресс-теста необходимо соблюдать следующее:

    -   Прототипы считывания и генерации тестов совпадают

    -   Прототипы решения и наивного решения совпадают

-   (С++) Весь дебажный код помещается в блок `#ifdef DEBUG ... #endif`. Для
    некоторых тестирующих систем не зазорно рассчитывать на `#ifndef
    ONLINE_JUDGE`. Первое время это может казаться пустой тратой времени, но на
    деле это достаточно быстро и позволяет вам отправлять задачу сразу как она
    решена

-   (C++) Не помешает перед началом контеста найти где выставить современный
    стандарт языка (тот же что и на сервере), включить санитайзеры: на
    переполнение `-fsanitize=integer` и память `-fsanitize=address`

-   (C++) [experimental] В 64-битных компиляторах есть 128-битные инты
    (`__int128`) они очень криво поддерживаются — например не поддерживается
    работа с стандартными потоками, однако проверено — gcc 64-bit
    (соответственно, на ejudge и ddots, codeforces) поддеживает его и это может быть
    полезно.

(*) Помните, лучшие ошибки это ошибки компиляции — они сами вам всё расскажут.

 

Случайные замечания
===================

-   Компьютер всегда стоит с краю для того чтобы те кто не пишут задачу могли
    общаться независимо ни от чего.

-   Если видно что можно написать сложную задачу в 1,5–2 раза быстрее сделав
    замену, её стоит сделать

-   Никакого напряжения быть не должно, если возникают конфликты, их нужно
    обсудить после контеста

-   Самое ценное время на контесте — компьютерное, поэтому если сейчас решенных
    задач нет, но есть идеи которые можно проверить при помощи компьютера, стоит
    этим заняться (посмотреть на первые 100 значений, найти закономерность, etc)
