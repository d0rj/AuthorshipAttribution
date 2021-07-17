# Атрибуция текста авторством

[English version of README](/README_en.md)

<a href="https://www.kaggle.com/d0rj3228/authorship-attribution"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" title="View full version on Kaggle" /></a>

## Описание

Курсовая работа по обработке данных. 

Строются свёрточные НС с 3мя и 4мя параллельными входными слоями, обрабатывающие триграммную форму предложений.


## Ход выполнения скриптов

[*create_dataset.ipynb*](/create_dataset.ipynb) -> [*dataset_preprocessing.ipynb*](/dataset_preprocessing.ipynb) -> [*analysys.ipynb*](/analysys.ipynb)

Скрипты выплняются полностью последовательно. Первые два не нуждаются в вычислителях мощнее средней рабочей санции (ноутбука, к примеру).

Однако для блока *analysys.ipynb* необходимы довольно мощные машины, рекомендуется ускоритель **GPU** (просчёт выполнялся на [Kaggle](https://www.kaggle.com/d0rj3228/authorship-attribution), где с включённым GPU время обучения уже было приемлимым).

## Возможные улучшения

* 4-граммы. Всё же результаты, как показывают применения до этого, будут получше;
* Увеличение объёма обучающей выборки. Влечёт увеличение затрат на вычислительные мощности.
