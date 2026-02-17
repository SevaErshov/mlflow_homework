# Отчет по экспериментам коллеги (Мария Поздеева)

## Solver логистической регрессии
__Гипотеза__: выбор solver влияет на сходимость модели и ее итоговое качество
Изменялся параметр solver по следующим значениям: lgbfs, saga, liblinear.
![График solver](https://github.com/SevaErshov/mlflow_homework/blob/ershov/artifacts/roc_auc_solver.png)

Действительно, разные solver в результате давали разное качество на тестовой выборке (метрика ROC-AUC). Лучшим оказался liblinear, худшим - saga.


