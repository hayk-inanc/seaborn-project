# Seaborn Project

Проект с примерами анализа и визуализации данных на Python с использованием библиотеки Seaborn.

## Что используется в проекте

В проекте применяются следующие библиотеки:

* pandas — работа с таблицами и обработка данных
* numpy — математические операции и работа с массивами
* scipy — статистические методы
* seaborn — визуализация данных
* matplotlib — построение графиков
* tqdm — отображение прогресса выполнения
* warnings — управление предупреждениями

## Установка проекта

Склонируйте репозиторий:

```bash
git clone https://github.com/hayk-inanc/seaborn-project.git
```

Перейдите в папку проекта:

```bash
cd seaborn-project
```

Создайте виртуальное окружение.

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

Установите зависимости:

```bash
pip install -r requirements.txt
```

## Пример импортов, используемых в проекте

```python
import pandas as pd
import numpy as np
import scipy.stats as st
import seaborn as sns
import matplotlib.pyplot as plt

from scipy.stats import ttest_ind
from tqdm.notebook import tqdm as tqdm_notebook
```

## Основные возможности проекта

Проект демонстрирует:

* построение линейных графиков
* scatterplot-графики
* barplot и countplot
* boxplot и violinplot
* анализ распределений
* визуализацию зависимостей между признаками
* использование доверительных интервалов
* статистический анализ данных

## Используемые технологии

* Python 3
* Seaborn
* Matplotlib
* Pandas
* NumPy
* SciPy