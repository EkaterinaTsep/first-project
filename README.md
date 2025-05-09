Название проекта: "Обучение с учителем: качество модели".

Постановка задачи.
В условиях снижения активности покупателей интернет-магазина «В один клик» возникла необходимость в разработке системы,
способной предсказывать вероятность снижения покупательской активности постоянных клиентов и предлагать им
персонализированные предложения. Цель проекта заключается в анализе данных о клиентах и их поведении для создания
модели, которая поможет удерживать активность постоянных клиентов и повысить финансовые показатели компании.

Используемые данные.
Проект основывается на четырех таблицах данных:
market_file.csv: Информация о поведении покупателей на сайте, коммуникациях и предпочтениях.
market_money.csv: Данные о выручке от каждого покупателя за определенные периоды.
market_time.csv: Время, проведенное покупателями на сайте.
money.csv: Среднемесячная прибыль от каждого покупателя за последние три месяца.

Этапы работы.
Загрузка и предобработка данных: Проверка на наличие пропусков, дубликатов и корректность типов данных.
Исследовательский анализ данных: Статистический анализ признаков и отбор клиентов с активностью за последние три месяца.
Объединение таблиц: Создание единой таблицы для анализа.
Корреляционный анализ: Выявление взаимосвязей между признаками.
Моделирование: Обучение четырех моделей машинного обучения:
KNeighborsClassifier,
DecisionTreeClassifier,
LogisticRegression,
SVC.
Анализ важности признаков: Оценка значимости факторов, влияющих на покупательское поведение.
Сегментация покупателей: Разработка персонализированных предложений для различных групп клиентов.

Результаты применения моделей.
Наилучшей моделью оказалась KNeighborsClassifier с оптимальными гиперпараметрами. Результаты показали:
ROC-AUC на обучающей выборке: 0.90.
ROC-AUC на тестовой выборке: 0.92.
F1-score на тестовой выборке: 0.88.
Эти показатели подтверждают высокую эффективность модели в предсказании снижения активности клиентов.

Заключение.
Результаты проекта позволят интернет-магазину «В один клик» более эффективно удерживать постоянных клиентов, 
предлагая им персонализированные предложения, что в свою очередь должно привести к увеличению покупательской активности
и улучшению финансовых показателей компании. Проект стал основой для стратегически выверенных бизнес-решений,
направленных на оптимизацию маркетинговых стратегий и повышение уровня удовлетворенности клиентов.
