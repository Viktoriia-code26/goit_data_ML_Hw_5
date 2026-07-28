# goit_data_ML_Hw_5
Support Vector Machinen and Random Forest

# Human Activity Recognition

## Описание

В данном проекте выполнена классификация активности человека по данным акселерометра мобильного телефона.

Рассматривались четыре класса активности:
- Walking
- Running
- Stairs
- Idle

## Используемые модели

- Random Forest
- SVM (Support Vector Machine)

## Подготовка данных

Для улучшения качества классификации были рассчитаны временные признаки (time-domain features), такие как:
- Mean
- Standard Deviation
- Minimum
- Maximum
- Median
- Range
- RMS

## Оценка моделей

Для оценки качества моделей использовался `classification_report`, включающий метрики:
- Precision
- Recall
- F1-score

Также были построены матрицы ошибок и графики для сравнения результатов.

## Результат

По итогам экспериментов модель **Random Forest** показала лучшие результаты по сравнению с **SVM** и обеспечила наиболее точную классификацию активности человека.
