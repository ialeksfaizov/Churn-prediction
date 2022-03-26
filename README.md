# Прогнозирование оттока клиентов банка

## Описание проекта
Из условного банка стали уходить клиенты. Необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. 

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Stack
- Pandas
- Numpy
- Scikit-learn 
- Matplotlib

## Вывод
- лучшая модель основана на `RandomForestClassifier`;
- лучшая выборка, где пропуски были удалены - `df_nopasses`;
- наилучшая техника выравнимания - `Upsampling`;
- F1-мера по тестовой выборке равна - `0.6192358366271411`;
- метрика AUC-ROC по тестовой выборке равна - `0.8645410919693625`;
- гиперпараметры `n_estimators=100`, `max_depth=13`.
