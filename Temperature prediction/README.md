## Проект "Предсказание температуры стали"
### _Цель_
Построить модель, которая предскажет температуру стали.
### _Данные_
Имеется данные по технологическим процессам: подогрев расплавленной стали, легирование, продувание.
### _Используемые в работе библиотеки:_
- pandas,
- matplotlib (модель pyplot),
- seaborn,
- numpy,
- scikit-learn (sklearn): модель LinearRegression
- catboost: модель CatBoostRegressor.

### _Вывод:_
В итоге лучшей моделью по метрике MAE = 5.99 на тестовой выборке стала модель CatBoostRegressor. Этот результат показывает, что модель может ошибаться на 6 градусов.
