ПОРТФОЛИО: АНАЛИТИК ДАННЫХ

ОБО МНЕ

Привет! Меня зовут Ольга, я начинающий аналитик данных. В настоящий момент я обучаюсь в онлайн-университете СкайПро по специальности Аналитик данных уже 5 месяцев. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

НАВЫКИ И ТЕХНОЛОГИИ

Инструменты анализа данных: SQL, Excel:
Системы управления базами данных: MySQL, PostgreSQL

ПРОЕКТ 1: Калькулятор юнит-экономики онлайн-школы

Что нужно было сделать:
Задача 1
На какую сумму мы могли бы увеличить расходы на основных сотрудников в апреле 2021 года при условии, что маржинальность в этом месяце не должна упасть ниже 11%?
Задача 2
Какой станет маржинальность за март 2021, если доля бесплатных уроков в нем упадет на 10 процентных пунктов*?
P. S. При этом общее количество уроков не изменится — просто часть бесплатных уроков мы «продадим» за полную цену в 1 200 рублей.
Задача 3
Насколько увеличится LTR и маржинальность апреля 2021 года, если средний Retention будет на 2 процентных пункта выше?

что было сделано:
1. Используя инструменты (ВПР, сводные таблицы, фильтры и модель данных) приводим данные к удобноу виду
2. Сначала считаем расходы на привлечение одного юнита.  
3. Затем узнаем, какую выручку приносит в среднем 1 юнит за все время «жизни» (то есть за время взаимодействия с нашим продуктом). Для этого считаем уже знакомый нам Retention. 
4. Считаем, сколько в среднем стоит наш продукт. 
5. Считаем переменные и постоянные затраты, формирующиеся из окладов наших сотрудников.
6. Сводим все полученные метрики воедино и вычисляем маржинальность нашего продукта.
   
ссылка на проект:
https://docs.google.com/spreadsheets/d/1CCWdx-7BKV3_IpjxM0nJoj5edL1W0Ozr/edit?usp=sharing&ouid=105543503263826879770&rtpof=true&sd=true

Выводы по задачам представлены в отдельных вкладках файла по ссылке выше.

ПРОЕКТ 2: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:
Задачи:
1. Определить, что является юнитом в нашей экономике.
2. Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.
3. Выбрать оптимальный вариант расчета Retention. 
4. Собрать визуализации основных бизнес-показателей.
5. Исследовать данные о пользователях и их поведении.

что было сделано:
1. данные приведены к удобному виду
2. рассчитаны поазатели, построен калькулятор юнит-экономики
3. визуализированы бизнес-показатели с помощью диаграмм в Excel
4. сделана презентация с основными выводами

ссылка на проект:
https://drive.google.com/drive/folders/1OftucpgKER95Pda1AxhCQae_c6cTDbmY?usp=sharing

Выводы по задачам представлены в презентации по ссылке выше

ПРОЕКТ 3: Когортный анализ онлайн-кинотеатра с помощью SQL

Что нужно было сделать:
1. постройте распределение количества первых покупок клиента по полям is_trial и name_partner
2. Скачайте результаты (по всем покупкам с проставленными рангами) в Excel. Постройте гистограмму с накоплением и добавьте к графику срез, на котором можно выбрать, на каких по счету покупках в рамках клиента построена гистограмма (только на первых; только на вторых; на всех, кроме первых, и т. д.).
3. Дополните код таким образом, чтобы у вас получились винтажные доходимости, т. е. для каждого партнера необходимо рассчитать, какой процент клиентов дошел до второй покупки, до третьей покупки и т. д.
4. Выведите полученные результаты в Excel и нарисуйте график, на котором каждая линия показывает своего партнера.

ссылка на проект:
- часть 1: https://metabase.sky.pro/question/74975
- часть 2: https://metabase.sky.pro/question/74983
- часть 3: https://metabase.sky.pro/question/75136
- результаты в Excel: https://drive.google.com/drive/folders/1P9EQmg9Qn3dmSqsVVPmDlpJYWb7-X2eI?usp=sharing
   
ПРОЕКТ 4: Построение витрины для модели машинного обучения в банке

Что нужно было сделать: составить витрину для модели машинного обучения.
Возьмите таблицу skybank.late_collection_clients и напишите скрипт, который сделает витрину со следующими полями:
- Внутренний идентификатор клиента — поле id_client.
- Название города — поле name_city
- Числовой признак, который принимает значение 1 для мужчин и 0 для женщин — новое поле nflag_gender на основании поля gender.
- Возраст — поле age.
- Числовая переменная, которая показывает, в первый ли раз клиент обратился к нам за кредитом, — поле first_time.
- Числовой признак, который принимает значение 1 при наличии мобильного телефона и 0 при его отсутствии — новое поле nflag_cellphone на основании поля cellphone.
- Числовая переменная, которая показывает, активен ли клиент, — поле is_active;
- Номер клиентского сегмента — поле cl_segm.
- Размер выданного кредита — поле amt_loan.
- Дата выдачи кредита — поле date_loan. Необходимо привести к формату даты.
- Тип выданного кредита — поле credit_type.
- Суммарный объем кредитов, выданных в этом городе.
- Доля данного кредита среди всех кредитов, выданных в этом городе.
- Суммарный объем кредитов, выданных в рамках указанного типа кредита.
- Доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита.
- Суммарный объем кредитов, выданных в рамках указанного типа кредита и города.
- Доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита и города.
- Количество кредитов, выданных в этом городе.
- Количество кредитов, выданных в рамках указанного типа кредита.
- Количество кредитов, выданных в рамках указанного типа кредита и города.

Свой код оформите в Metabase.

ссылка на проект: https://metabase.sky.pro/question/75336

ПРОЕКТ 5: Моделирование изменения балансов студентов

Что нужно было сделать:
1. смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента. В результате должен получиться запрос, который собирает данные о балансах студентов за каждый прожитый ими день.
2. Посмотрите на изменения балансов студентов (на примере топ-1000 строк), собранных из CTE. Какие данные вас смущают? Какие вопросы стоит задавать дата-инженерам и владельцам таблиц? 
3. Создайте визуализацию (линейную диаграмму) итогового результата. Какие выводы можно сделать из получившейся визуализации?

ссылка на проект:
- https://metabase.sky.pro/question/76938
- https://metabase.sky.pro/question/76972
- результаты в Excel https://drive.google.com/drive/folders/1b4b42Dgz8jDm96UAhBZF5xq2-GO3q_pw?usp=sharing
