ML
Итоговый проект (пример) курса "Машинное обучение в бизнесе"

Стек:

ML: sklearn, pandas, numpy API: flask Данные: с kaggle - https://www.kaggle.com/fedesoriano/heart-failure-prediction

Задача: предсказать по имеющимся данным предсказать есть ли заболевание или нет. Бинарная классификация

Используемые признаки:

'Age' (int64), 
'RestingBP' (int64),
'MaxHR' (int64),
'Oldpeak' (float)

Преобразования признаков: StandardScaler()

Модель: GradientBoostingClassifier