# Kaggle Challenges

Repositório pessoal para explorar e resolver desafios do Kaggle.

## Desafios

| Competição | Tipo | Melhor Score | Status |
|---|---|---|---|
| — | — | — | — |

## Estrutura

```
competitions/
└── nome-do-desafio/
    ├── README.md       # descrição, abordagem e resultados
    ├── notebooks/      # exploração e experimentação
    ├── src/            # scripts e pipelines
    └── submissions/    # arquivos de submissão gerados
utils/                  # funções reutilizáveis entre desafios
```

## Setup

```bash
pip install -r requirements.txt
```

> Datasets não estão versionados. Baixe via Kaggle CLI:
> ```bash
> kaggle competitions download -c nome-da-competicao -p competitions/nome-do-desafio/data/
> ```

## Tecnologias

- Python 3.x
- pandas, numpy, scikit-learn
- Jupyter Notebooks
