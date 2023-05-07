# Feature_Engineering_ML

## Оглавление

- [Оглавление](#оглавление)
- [Автор](#авторы)
- [Описание](#описание)
- [Технологии](#технологии)
- [Проекты](#проекты)

### Автор

[Максим Савилов](https://github.com/msavilov/)

### Описание

Учебные проекты курса "Работа с признаками и построение моделей" профессии Data Science от Нетология.

### Технологии

![](https://img.shields.io/badge/-Python--3.11-blue)
![](https://img.shields.io/badge/-Scikit--Learn-blue)
![](https://img.shields.io/badge/pandas-blue)
![](https://img.shields.io/badge/numpy-blue)
![](https://img.shields.io/badge/matplotlib-blue)

## Проекты

  [1. Classification](#сlassification)
  
  [2. Loss_function_and_optimization](#loss_function_and_optimization)
  
### Classification
  Решение задачи классификации физических лиц по уровню дохода. Данные для обучения модели хранятся в файле adult.csv.
Целевая переменная – уровень дохода income, который принимает два значения <=50K и >50K, поэтому классификация бинарная. Остальные признаки описывают персональную информацию – возраст, образование, семейное положение и т. д.
Задачу классификации нужно решить при помощи обучения модели логистической регрессии и модели опорных векторов.

  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/1_Classification/classification.ipynb)
 
### Loss_function_and_optimization
  Используйте датасет с ирисами. В данных оставьте только 2 класса: Iris Versicolor, Iris Virginica. Реализуйте логистическую регрессию, без использования метода LogisticRegression из библиотеки. Можно использовать библиотеки pandas, numpy, math для реализации. Оформите в виде функции. 
Реализуйте метод градиентного спуска, Root Mean Square Propagation, Nesterov–accelerated Adaptive Moment Estimation. Обучить модели этим методом. Выбрать и посчитайте метрику качества. Метрики должна быть одинакова для всех пунктов задания. Напишите вывод.

  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/2_Loss_function_and_optimization/loss_function_and_optimization.ipynb)
    
  
