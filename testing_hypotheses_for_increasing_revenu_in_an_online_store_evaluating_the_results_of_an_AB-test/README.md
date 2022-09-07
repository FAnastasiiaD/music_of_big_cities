# Описание проекта Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста
Крупный интернет-магазин. Вместе с отделом маркетинга подготовлен список гипотез для увеличения выручки.

## Данные

Данные интернет-магазина.

**Документация к данным:**

*Таблица `hypothesis`:*

- `Hypothesis` — краткое описание гипотезы;
- `Reach` — охват пользователей по 10-балльной шкале;
- `Impact` — влияние на пользователей по 10-балльной шкале;
- `Confidence` — уверенность в гипотезе по 10-балльной шкале;
- `Efforts` — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

*Таблица `orders`:*

- `transactionId` — идентификатор заказа;
- `visitorId` — идентификатор пользователя, совершившего заказ;
- `date` — дата, когда был совершён заказ;
- `revenue` — выручка заказа;
- `group` — группа A/B-теста, в которую попал заказ.

*Таблица `visitors`:*

- `date` — дата;
- `group` — группа A/B-теста;
- `visitors` — количество пользователей в указанную дату в указанной группе A/B-теста

## Задачи

* Приоритизация гипотез; 
* запуск A/B-теста;
* анализи результатов.

## Ход исследования

 1. Обзор данных.
 2. Предобработка данных.
 3. Пиоретизация гипотез.
 4. Анализ A/B-теста.
 5. Решение по результатам теста.

## Используемые библиотеки
- *Pandas*
- *Matplotlib*
- *NumPy*
- *SciPy*
- *Math*
- *DateTime*