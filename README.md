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
![](https://img.shields.io/badge/seaborn-blue)

## Проекты

  [1. Classification](#classification)
  
  [2. Loss_function_and_optimization](#loss_function_and_optimization)
  
  [3. Metrics_and_Model_selection](#metrics_and_model_selection)
  
  [4. Data_problems](#data_problems)
  
  [5. Work_with_variables](#work_with_variables)
  
  [6. Decision_trees](#decision_trees)
  
  [7. Work_with_outliers](#work_with_outliers)
  
  [8. Feature_selection](#feature_selection)
  
  [9. Ensemble_methods](#ensemble_methods)
  
### Classification
  Решение задачи классификации физических лиц по уровню дохода. Данные для обучения модели хранятся в файле adult.csv.
Целевая переменная – уровень дохода income, который принимает два значения <=50K и >50K, поэтому классификация бинарная. Остальные признаки описывают персональную информацию – возраст, образование, семейное положение и т. д.
Задачу классификации нужно решить при помощи обучения модели логистической регрессии и модели опорных векторов.

  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/1_Classification/classification.ipynb)
 
### Loss_function_and_optimization
  Используйте датасет с ирисами. В данных оставьте только 2 класса: Iris Versicolor, Iris Virginica. Реализуйте логистическую регрессию, без использования метода LogisticRegression из библиотеки. Можно использовать библиотеки pandas, numpy, math для реализации. Оформите в виде функции. 
Реализуйте метод градиентного спуска, Root Mean Square Propagation, Nesterov–accelerated Adaptive Moment Estimation. Обучить модели этим методом. Выбрать и посчитайте метрику качества. Метрики должна быть одинакова для всех пунктов задания. Напишите вывод.

  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/2_Loss_function_and_optimization/loss_function_and_optimization.ipynb)
    
### Metrics_and_model_selection
  Решить задачу классификации при помощи обучения модели логистической регрессии. Качество модели оценивается путем подсчета метрик TPR, FPR и построения графиков ROC-кривой, Precision-Recall.
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/3_Metrics_and_Model_selection/metrics_and_model_selection.ipynb)

### Data_problems
  Решить задачу по очистке данных на примере датасета с информацией о пассажирах корабля Титаник. На данных обучить модель классификации, с целевым признаком Survived (1 – пассажир выжил, 0 – погиб). Обучить модели на необработанных и обработанных данных, посчитать и сравнить метрики качества этих моделей.
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/4_Data_problems/data_problems.ipynb)
 
### Work_with_variables

  Проработать улучшение метрики RMSE, R2 модели линейной регрессии путем работы с данными, а именно проведения разведочного анализа данных. В качестве датасета необходимо загрузить данные о недвижимости Калифорнии из библиотеки sklearn.datasets. Целевая переменная – MedHouseVal.
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/5_Work_with_variables/work_with_variables.ipynb)
  
### Decision_trees

  Решить задачу регрессии используя деревья решений. В качестве датасета необходимо взять данные о недвижимости Калифорнии из библиотеки sklearn.datasets. Целевая переменная – MedHouseVal
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/6_Decision_trees/decision_trees.ipynb)
  
### Work_with_outliers
  
  Решить задачу классификации типа стекол. Данные для обучения моделей можно скачать с [сайта](https://www.kaggle.com/datasets/uciml/glass). Целевая переменная – тип стекла «Type»
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/7_Work_with_outliers/work_with_outliers.ipynb)

### Feature_selection

  Решить задачу классификации точек наиболее эффективно. Для этого в работе необходимо применить различные методы по отбору признаков. Отбор признаков предпочтительнее осуществлять основываясь на математическом аппарате, поэтому данные для этого задания будут сгенерированы, чтобы избежать признаков с физическим смыслом.
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/8_Feature_Selection/feature_selection.ipynb)

### Ensemble_methods

  Решить задачу классификации наличия болезни сердца у пациентов, применяя базовые ансамблевые методы. Целевая переменная – наличие болезни сердца (HeartDisease), принимает значения 0 или 1 в зависимости от отсутствия или наличия болезни соответственно.
  
  [Решение](https://github.com/msavilov/Feature_Engineering_ML/blob/main/9_Ensemble_methods/ensemble_methods.ipynb)
