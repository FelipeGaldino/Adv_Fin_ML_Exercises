Avanços nos exercícios de aprendizado de máquina financeiro
==============================

Soluções experimentais para exercícios selecionados do livro [Avanços no aprendizado de máquinas financeiras de Marcos Lopez De Prado] (https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482109)

Certifique-se de usar o `python setup.py install` em seu ambiente, para que os scripts` src`, que incluem `bars.py` e` snippets.py`, possam ser encontrados pelos blocos de anotações do jupyter e outros scripts que você possa desenvolver.

## Projetos e recursos adicionais da AFML
Existem outros projetos e links do github que as pessoas compartilham e que são inspirados no livro. Eu gostaria de colecioná-los aqui para compartilhar com outras pessoas no espírito de colaboração e compartilhamento de idéias. Se você tiver mais a acrescentar, entre em contato.

Projetos do Github

- [The Open Source Hedge Fund Project] (http://www.quantsportal.com/the-open-source-hedge-fund-project/)
- [Github MLFinLab Repo] (https://github.com/hudson-and-thames/mlfinlab)
- [Notebooks Github] (https://github.com/hudson-and-thames/research)

- [rspadim Github] (https://github.com/rspadim/Adv_Fin_ML/)

### Links de artigos

- [Aprendizado de máquina financeira parte 0: barras de Maks Ivanov] (https://towardsdatascience.com/financial-machine-learning-part-0-bars-745897d4e4ba)
- [Taxa de Sharpe deflacionada] (https://gmarti.gitlab.io/qfin/2018/05/30/deflated-sharpe-ratio.html) - [Blog do Gautier Marti] (https://gmarti.gitlab.io/ )


Organização do projeto
------------
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p> <small> Projeto baseado no <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/"> modelo de projeto de ciência de dados do cookiecutter </a>. #cookiecutterdatascience </small> </p>
