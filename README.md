# Методы, средства и технологии мультимедиа
Лабораторные работы по предмету "Методы, средства и технологии мультимедиа", 7 семестр, 806 кафедра, МАИ

**ФИО**: Овчинников Дмитрий Максимович

**Группа**: М8О-406Б-21

**Датасет для задачи классификации**: Machine failure prediction. https://www.kaggle.com/datasets/umerrtx/machine-failure-prediction-using-sensor-data/data 

**Датасет для задачи регрессии**: Student Performance. https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/data

**Сравнительная таблица метрик обучения моделей из всех ЛР**:

| Алгоритм              | Задача          | baseLine                                                                 | Improved baseLine                                                   | self        impl                                       | Improved self umpl                            |
|------------------------|-----------------|-------------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|
| KNN               | Классификация  | Accuracy : 0.852 <br> F1 : 0.852 | Accuracy : 0.857 <br> F1 : 0.857 | Accuracy : 0.852 <br> F1 : 0.852 | Accuracy : 0.857 <br> F1 : 0.857 |
|                        | Регрессия      | MAE: 1.967 <br> R2: 0.983                     | MAE: 1.961 <br> R2: 0.983                   | MAE: 1.959 <br> R2: 0.983                  | MAE: 2.312 <br> R2: 0.976                   |
| Линейные модели    | Классификация  | Accuracy : 0.873 <br> F1 : 0.873 | Accuracy : 0.884 <br> F1 : 0.884 | Accuracy : 0.873 <br> F1 : 0.873 | Accuracy : 0.884 <br> F1  : 0.884 |
|                        | Регрессия      | MAE: 1.611 <br> R2: 0.989                     | MAE: 1.611 <br> R2: 0.989                   | MAE: 1.611 <br> R2: 0.989                   | MAE: 1.652 <br> R2: 0.988                   |
| Решающее дерево    | Классификация  | Accuracy : 0.810 <br> F1  : 0.809 | Accuracy : 0.868 <br> F1  : 0.868 | Accuracy : 0.820 <br> F1  : 0.820 | Accuracy : 0.831 <br> F1  : 0.830 |
|                        | Регрессия      | MAE: 2.318 <br> R2: 0.976                     | MAE: 1.939 <br> R2: 0.983                   | MAE: 1.982 <br> R2: 0.982                   | MAE: 1.958 <br> R2: 0.983                   |
| Случайный лес      | Классификация  | Accuracy : 0.873 <br> F1  : 0.873 | Accuracy : 0.878 <br> F1  : 0.878 | Accuracy : 0.878 <br> F1  : 0.878 | Accuracy : 0.878 <br> F1  : 0.878 |
|                        | Регрессия      | MAE: 1.817 <br> R2: 0.986                     | MAE: 1.743 <br> R2: 0.987                   | MAE: 2.394 <br> R2: 0.974                   | MAE: 2.369 <br> R2: 0.975                   |
| Градиентный бустинг| Классификация  | Accuracy : 0.884 <br> F1  : 0.884 | Accuracy : 0.884 <br> F1  : 0.884 | Accuracy : 0.852 <br> F1  : 0.852 | Accuracy : 0.847 <br> F1  : 0.847 |
|                        | Регрессия      | MAE: 1.658 <br> R2: 0.988                     | MAE: 1.640 <br> R2: 0.988                   | MAE: 2.256 <br> R2: 0.978                   | MAE: 2.244 <br> R2: 0.977                   |