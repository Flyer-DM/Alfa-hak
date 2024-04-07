<a id='ENG'></a>
<a href="#RUS"><img src='https://img.shields.io/badge/ENG -Go to RUS description-blue'></a>

# Alfa x FinU Hack

==============================

_From anpilove_

- Do not touch the file `models/baseline.ipynb`.
- Had an issue with installing lightgbm - solved it with `brew install libomp`.
- Run `pip install pyarrow` # for reading `.pqt` files.
- Runtime is 310 seconds in Collab. For some reason, I'm having issues with Jupyter for now.
  ```python
  model = LGBMClassifier(verbosity=-1, random_state=42, n_jobs=-1)
  model.fit(x_train, y_train)
  ```

## Project Organization

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   ├── raw            <- The original, immutable data dump.
    │   └── submissions    <- All submissions
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    └──requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                             generated with `pip freeze > requirements.txt`

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

---

<a id='RUS'></a>
<a href="#ENG"><img src='https://img.shields.io/badge/RUS -Go to ENG description-blue'></a>

# Alfa x FinU Hack

==============================

_From anpilove_

- файл `models/baseline.ipynb` не трогать.
- С установкой lightgbm была проблема решил - brew install libomp.
- pip install pyarrow # for read file .pqt
- Время работы - 310 секунд в Collab. Почему-то у меня пока проблемы с Jupyter.

```python
model = LGBMClassifier(verbosity=-1, random_state=42, n_jobs=-1)
model.fit(x_train, y_train)
```

## Организация проекта

    ├── README.md          <- Основной README для разработчиков, использующих этот проект.
    ├── data
    │   ├── external       <- Данные из сторонних источников.
    │   ├── interim        <- Промежуточные данные, которые были преобразованы.
    │   ├── processed      <- Финальные, канонические наборы данных для моделирования.
    │   ├── raw            <- Оригинальные, неизменные данные.
    │   └── submissions    <- Все представления
    │
    ├── models             <- Обученные модели
    │
    ├── notebooks          <- Jupyter ноутбуки. Соглашение о наименовании - это номер (для упорядочивания),
    │                         инициалы создателя и краткое описание с разделителем `-`, например
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Сгенерированный анализ в форматах HTML, PDF, LaTeX и т. д.
    │   └── figures        <- Сгенерированные графики и изображения для использования в отчетах
    │
    ├── requirements.txt   <- Файл с требованиями для воспроизведения окружения анализа, например
    │                         созданный с помощью `pip freeze > requirements.txt`
    │
    └── tox.ini            <- Файл tox с настройками для запуска tox; см. tox.readthedocs.io

<p><small>Проект основан на <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">шаблоне проекта DS Cookiecutter</a>. #cookiecutterdatascience</small></p>
