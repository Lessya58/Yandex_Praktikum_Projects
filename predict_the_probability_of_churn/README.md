# Прогнозирование вероятности оттока пользователей для фитнес-центров

#### Задачи проекта:
На основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей

#### Описание проекта:
В данном проекте использовано машинное обучение. Спрогнозирована вероятность
оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные
портреты пользователей: выделены наиболее яркие группы, охарактеризованы их
основные свойства; проанализированы основные признаки, наиболее сильно влияющие
на отток.

#### Инструменты: 

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- машинное обучение
- классификация
- кластеризация

#### Описание данных:

- 'Churn' — факт оттока в текущем месяце;
- 'gender' — пол
- 'Near_Location' — проживание или работа в районе, где находится фитнес-центр
- 'Partner' — сотрудник компании-партнёра клуба
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга»
- 'Phone' — наличие контактного телефона
- 'Age' — возраст
- 'Lifetime' — время с момента первого обращения в фитнес-центр (в месяцах)
- 'Contract_period' — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год)
- 'Month_to_end_contract' — срок до окончания текущего действующего абонемента (в месяцах)
- 'Group_visits' — факт посещения групповых занятий
- 'Avg_class_frequency_total' — средняя частота посещений в неделю за все время с начала действия абонемента
- 'Avg_class_frequency_current_month' — средняя частота посещений в неделю за предыдущий месяц
- 'Avg_additional_charges_total' — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон
