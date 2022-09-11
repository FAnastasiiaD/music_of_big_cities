# Описание проекта Прогнозирование вероятности оттока пользователей для фитнес-центров
Сеть фитнес-центров «Культурист-датасаентист» разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.
Распространённая проблема фитнес-клубов и других сервисов — отток клиентов. Клиенты не всегда уходят закрыв договор: чаще перестают пользоваться сервисом тихо. Для фитнес-центра можно считать, что клиент попал в отток, если за последний месяц ни разу не посетил спортзал.

## Данные

Данных о посетителях сети фитнес-центров.

**Предоставленные данные:**

***Данные клиента за предыдущий до проверки факта оттока месяц:***
- Пол;
- Проживание или работа в районе, где находится фитнес-центр;
- Сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
- Факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
- Наличие контактного телефона;
- Возраст;
- Время с момента первого обращения в фитнес-центр (в месяцах).

***Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента:***
- Длительность текущего действующего абонемента (месяц, 6 месяцев, год);
- Срок до окончания текущего действующего абонемента (в месяцах);
- Факт посещения групповых занятий;
- Средняя частота посещений в неделю за все время с начала действия абонемента;
- Средняя частота посещений в неделю за предыдущий месяц;
- Суммарная выручка от других услуг фитнес-центра: кафе, спорттовары, косметический и массажный салон.
- Факт оттока в текущем месяце.

## Задачи

Провести анализ и подготовить план действий по удержанию клиентов.

- научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
- сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
- проанализировать основные признаки, наиболее сильно влияющие на отток;
- сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами:
     - выделить целевые группы клиентов;
     - предложить меры по снижению оттока;
     - определить другие особенности взаимодействия с клиентами. 

## Ход исследования

 1. Обзор данных.
 2. Предобработка данных.
 3. Анализ данных.
 4. Модель прогнозирования оттока клиентов.
 5. Кластеризация клиентов.
 6. Выводы и базовае рекомендации по работе с клиентами.

## Используемые библиотеки
- *Pandas*
- *Scikit-learn*
- *Matplotlib*
- *Seaborn*