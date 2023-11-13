# Классификация клиентов телеком компании
# Задача 
На основе данных предложить клиенту тариф. Построить модель машинного обучения с максимально большим значением accuracy.

# Стек
Pandas, NumPy, Matplotlib, Scikit-Leatn

[Ноутбук с исследованием](04_user_behaviour.ipynb)

# Выводы
Задачей проекта было построение модеи машинного обучения с максимально большим значением accuracy минимум 0.75.

В ходе анализа были исследованы 3 типа моделей:
* Дерево решений
* Случайны лес
* Логистическая регрессия

Проверку на адекватность прошли все модели.

Наиболее качественный результат показала модель случайного леса с 9-ю деревьями, которая при проверке на тестовой выборке достигла показателя accuracy 0.802.