В проекте решается задача прогнозирования оттока клиентов методами машинного обучения.
В нашем распоряжении: исторические данные о поведении клиентов и расторжении договоров с банком.

Проводится сравнение работы двух моделей: RandomForestClassifier и LogisticRegression.
Наилучший результат на тестовых данных показала модель RandomForestClassifier, с метриками качества f1_score≈0.625 и auc_roc≈0.876.
