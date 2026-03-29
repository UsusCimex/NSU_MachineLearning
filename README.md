# Методы машинного обучения. Магистратура 1 курс НГУ.

## Установка

Зависимости - в `requirements.txt`. Для загрузки датасетов с Kaggle записать API-токен в `~/.kaggle/access_token`.

## Содержание

### Блок 1 - Регрессия и деревья решений
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Построение линии регрессии](regression/) | [Auto MPG](https://www.kaggle.com/datasets/uciml/autompg-dataset) - характеристики автомобилей, предсказание расхода топлива | [notebook](regression/auto_mpg_regression.ipynb) |
| [Классификационное дерево и Random Forest](classification_tree_rf/) | [Mobile Price Classification](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification) - 2000 смартфонов, классификация по 4 ценовым категориям (RF accuracy=0.88) | [notebook](classification_tree_rf/mobile_price_classification_tree_rf.ipynb) |
| [Дерево решений - регрессор](decision_tree_regressor/) | California Housing, Diabetes, sin(x) - 3 датасета для сравнения поведения дерева | [notebook](decision_tree_regressor/dataset_decision_tree_regressor.ipynb) |

### Блок 2 - Классические методы классификации
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Наивный Байес](naive_bayes/) | [Russian Sentiment Dataset](https://www.kaggle.com/datasets/mar1mba/russian-sentiment-dataset) - классификация тональности русскоязычных текстов | [notebook](naive_bayes/sentiment_nb.ipynb) |
| [K ближайших соседей (KNN)](knn/) | [Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) - 114k треков, классификация жанров по аудио-признакам | [notebook](knn/spotify_knn.ipynb) |
| [Машины опорных векторов (SVM)](svm/) | - | [notebook](svm/dataset_svm.ipynb) |

### Блок 3 - Кластеризация
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Mean Shift](mean_shift/) | - | [notebook](mean_shift/dataset_mean_shift.ipynb) |
| [K-Means, K-Means++](kmeans/) | sklearn.datasets.load_digits - рукописные цифры 8x8, кластеризация | [notebook](kmeans/dataset_kmeans.ipynb) · [презентация](kmeans/kmeans_presentation.pptx) |
| [DBSCAN](dbscan/) | - | [notebook](dbscan/dataset_dbscan.ipynb) |

### Блок 4 - Снижение размерности и нейросети
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Метод главных компонент (PCA)](pca/) | [Human Activity Recognition](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones) - 10299 записей с акселерометра/гироскопа, 561 признак, 6 видов активности | [notebook](pca/har_pca.ipynb) |
| [Нейронная сеть - классификация](nn_classification/) | Fashion MNIST - 70k изображений одежды 28x28, 10 классов | [notebook](nn_classification/fashion_mnist_nn_classification.ipynb) |
| [Нейронная сеть - регрессия](nn_regression/) | [Used Cars Price Prediction](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction) - 6019 автомобилей, предсказание цены по характеристикам (R2=0.90) | [notebook](nn_regression/used_cars_nn_regression.ipynb) |
