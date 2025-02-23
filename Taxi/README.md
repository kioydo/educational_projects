# Прогнозирование заказов такси
[ipynb](https://github.com/kioydo/educational_projects/blob/main/Taxi/Прогнозирование_заказов_такси.ipynb)

## Описание проекта
Чтобы привлекать больше водителей в период пиковой нагрузки в аэропортах, необходимо спрогнозировать количество заказов такси на следующий час.

## Стек
- python
- pandas
- seaborn
- statsmodels.tsa.seasonal.seasonal_decompose
- sklearn.model_selection.TimeSeriesSplit
- sklearn.linear_model.LinearRegression
- lightgbm.LGBMRegressor
- sklearn.tree.DecisionTreeRegressor
- sklearn.neighbors.KNeighborsRegressor

## Вывод 
Выявлен и проанализирован ряд закономерностей временного ряда. Выбрана модель Линейной регрессии.
