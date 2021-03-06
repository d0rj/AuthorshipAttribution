# Authorship attribution

<a href="https://www.kaggle.com/d0rj3228/authorship-attribution"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" title="View full version on Kaggle" /></a>

## Overview

Coursework on data processing.

Convolutional neural networks with 3 and 4 parallel input layers are constructed, processing the trigram form of sentences.

## Execution pipeline

| 1 | 2 | 3 |
| :-: |:-:| :-:|
| [*create_dataset.ipynb*](/create_dataset.ipynb) | [*dataset_preprocessing.ipynb*](/dataset_preprocessing.ipynb) | [*analysys.ipynb*](/analysys.ipynb) |
| [![Create dataset](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://nbviewer.jupyter.org/github/d0rj/AuthorshipAttribution/blob/main/create_dataset.ipynb) | [![Preprocessing](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://nbviewer.jupyter.org/github/d0rj/AuthorshipAttribution/blob/main/dataset_preprocessing.ipynb) | [![Analysys](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://nbviewer.jupyter.org/github/d0rj/AuthorshipAttribution/blob/main/analysys.ipynb) |

The scripts are executed completely sequentially. The first two do not need computers more powerful than the average workforce (laptop, for example).

However, the * analysys.ipynb * block requires quite powerful machines, the ** GPU ** accelerator is recommended (the rendering was performed on [Kaggle](https://www.kaggle.com/d0rj3228/authorship-attribution), where the training time was already acceptable with the enabled GPU).

## Possible improvements

* 4 grams. Still, the results, as shown by the applications before, will be better;
* Increasing the volume of the training sample. Increases the cost of computing power.
