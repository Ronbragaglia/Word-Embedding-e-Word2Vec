# Word Embedding e Word2Vec

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![Topic](https://img.shields.io/badge/Topic-nlp-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Descrição

Implementação de Word2Vec com o dataset de avaliações de pedidos da Olist para análise semântica de reviews de produtos em português.

## Funcionalidades

- Treinamento de modelo Word2Vec com dados reais da Olist
- Análise de proximidade semântica entre palavras
- Exploração de reviews em português
- Visualização de embeddings em espaço vetorial
- Consulta de palavras similares (ex: "produto")

## Stack Tecnológico

| Tecnologia | Descrição |
|---|---|
| Python | Linguagem principal |
| Gensim | Treinamento do Word2Vec |
| Pandas | Manipulação do dataset |
| NumPy | Operações vetoriais |

## Como Usar

1. Instale as dependências: `pip install gensim pandas`
2. Adicione o arquivo `olist_order_reviews_dataset.csv` na pasta `data/`
3. Execute: `python word2vec_olist.py`

## Estrutura de Pastas

```
├── word2vec_olist.py
├── data/
│   └── olist_order_reviews_dataset.csv
└── requirements.txt
```

---

> Feito com ❤️ por Rone Bragaglia · ML Engineer & Fundador CobrançaAuto
