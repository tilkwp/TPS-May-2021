# TPS-May-2021
____
Tabular Playground Series - May 2021
Набор данных, используемый для этого соревнования, является синтетическим, но основан на реальном наборе данных и сгенерирован с использованием CTGAN. Исходный набор данных предназначен для прогнозирования категории продукта электронной коммерции с учетом различных атрибутов листинга. Хотя функции анонимны, у них есть свойства, относящиеся к реальным функциям. https://www.kaggle.com/c/tabular-playground-series-may-2021/overview
____

В данном соревнованиии решается задача мультиклассовой классификации. В качестве метрики рассматриваются функция логистических потерь

<img src="https://latex.codecogs.com/png.image?\dpi{110}&space;\bg_white&space;\text{log&space;loss}&space;=&space;-\frac{1}{N}\sum_{i=1}^N\sum_{j=1}^My_{ij}\log(p_{ij}),&space;" title="\bg_white \text{log loss} = -\frac{1}{N}\sum_{i=1}^N\sum_{j=1}^My_{ij}\log(p_{ij}), " />

____

| Модель | Public Score|
|----------------|:---------:|
| LightGBM |1.08770 |
| XGBoost | 1.08674 | 

Были использованы следующие библиотеки: Pandas, Numpy, Matplotlib, Seaborn, XGBoost, LightGBM, Sklearn, Optuna
