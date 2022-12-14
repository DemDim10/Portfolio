# Проект - Прогнозирование оттока клиентов

## Описание и цели
Из банка в небольшом количестве, но стабильно уходят клиенты. Маркетологи банка выяснили, что сохранять имеющихся клиентов выгоднее, чем заниматься привлечением новых. Необходимо спрогнозировать вероятность ухода клиента в ближайшее время, основываясь на данных банка. 


## Данные
Исторические данные о поведении клиентов банка. 
Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Задачи
- Загрузить и подготовить данные
- Исследовать баланс классов
- Обучить модель, не учитывая дисбаланс классов
- Кратко описать выводы 
- Улучшить модель, взяв во внимание дисбаланс классов
- Использовать разные модели, чтобы определить лучшую
- Провести финальное тестирование
- Написать общий вывод

## Полученные выводы
Применив уменьшение выборки, устновив максимальную глубину в **5** и сбалансировав классы, мы смогли достичь значения `F1` метрики **0.6** на модели **DecisionTreeClassifier**. 

## Используемые инструменты
*python*, *pandas*, *markdown*, *matplotlib*, *SKlearn*

## Ключевые слова
классификация, подбор гиперпараметров, выбор модели МО
