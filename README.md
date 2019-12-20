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

    ├── LICENÇA
    Make── Makefile <- Makefile com comandos como `make data` ou` make train`
    RE── README.md <- O README de nível superior para desenvolvedores que usam este projeto.
    ├── dados
    External ├── externo <- Dados de fontes de terceiros.
    Inter ├── interim <- Dados intermediários que foram transformados.
    Processed ├── processado <- Os conjuntos de dados canônicos finais para modelagem.
    Raw └── raw <- O despejo de dados imutável original.
    │
    Doc── docs <- Um projeto padrão do Sphinx; veja sphinx-doc.org para detalhes
    │
    Models── modelos <- Modelos treinados e serializados, previsões de modelos ou resumos de modelos
    │
    ├── cadernos <- cadernos Jupyter. Convenção de nomenclatura é um número (para pedidos),
    Initial as iniciais do criador e uma breve descrição delimitada por `-`, p.
    │ `1.0-jqp-initial-data-exploração`.
    │
    ├── referências <- Dicionários de dados, manuais e todos os outros materiais explicativos.
    │
    ├── reports <- Análise gerada como HTML, PDF, LaTeX, etc.
    │ └── figuras <- Gráficos e figuras gerados para serem usados ​​nos relatórios
    │
    ├── requirements.txt <- O arquivo de requisitos para reproduzir o ambiente de análise, por exemplo
    │ gerado com `pip freeze> requirements.txt`
    │
    Setup── setup.py <- torna o pip do projeto instalável (pip install -e.) Para que o src possa ser importado
    Sr── src <- Código fonte para uso neste projeto.
    │ ├── __init__.py <- Torna o src um módulo Python
    │ │
    │ ├── data <- scripts para baixar ou gerar dados
    Make │ └── make_dataset.py
    │ │
    Features ├── features <- Scripts para transformar dados brutos em recursos para modelagem
    Build │ └── build_features.py
    │ │
    │ ├── modelos <- scripts para treinar modelos e depois usar modelos treinados para criar
    │ │ │ previsões
    │ │ ├── predict_model.py
    _ │ └── train_model.py
    │ │
    │ └── visualização <- scripts para criar visualizações exploratórias e orientadas a resultados
    Visualize └── visualize.py
    │
    Tox── arquivo tox.ini <- tox com configurações para executar o tox; veja tox.testrun.org


--------

<p> <small> Projeto baseado no <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/"> modelo de projeto de ciência de dados do cookiecutter </a>. #cookiecutterdatascience </small> </p>
