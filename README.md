# Лабораторные работы по машинному обучению — НГУ

## Установка

Зависимости — в `requirements.txt`. Для загрузки датасетов с Kaggle записать API-токен в `~/.kaggle/access_token`.

## Содержание

### Блок 1 — Регрессия и деревья решений
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Построение линии регрессии](regression/) | — | [notebook](regression/dataset_regression.ipynb) |
| [Классификационное дерево и Random Forest](classification_tree_rf/) | — | [notebook](classification_tree_rf/dataset_classification_tree_rf.ipynb) |
| [Дерево решений — регрессор](decision_tree_regressor/) | California Housing, Diabetes, sin(x) — 3 датасета для сравнения поведения дерева | [notebook](decision_tree_regressor/dataset_decision_tree_regressor.ipynb) |

### Блок 2 — Классические методы классификации
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Наивный Байес](naive_bayes/) | [Russian Sentiment Dataset](https://www.kaggle.com/datasets/mar1mba/russian-sentiment-dataset) — классификация тональности русскоязычных текстов | [notebook](naive_bayes/sentiment_nb.ipynb) |
| [K ближайших соседей (KNN)](knn/) | [Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) — 114k треков, классификация жанров по аудио-признакам | [notebook](knn/spotify_knn.ipynb) |
| [Машины опорных векторов (SVM)](svm/) | — | [notebook](svm/dataset_svm.ipynb) |

### Блок 3 — Кластеризация
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Mean Shift](mean_shift/) | — | [notebook](mean_shift/dataset_mean_shift.ipynb) |
| [K-Means, K-Means++](kmeans/) | — | [notebook](kmeans/dataset_kmeans.ipynb) · [презентация](kmeans/kmeans_presentation.pptx) |
| [DBSCAN](dbscan/) | — | [notebook](dbscan/dataset_dbscan.ipynb) |

### Блок 4 — Снижение размерности и нейросети
| Тема | Датасет | Материалы |
|------|---------|-----------|
| [Метод главных компонент (PCA)](pca/) | — | [notebook](pca/dataset_pca.ipynb) |
| [Нейронная сеть — классификация](nn_classification/) | — | [notebook](nn_classification/dataset_nn_classification.ipynb) |
| [Нейронная сеть — регрессия](nn_regression/) | — | [notebook](nn_regression/dataset_nn_regression.ipynb) |
