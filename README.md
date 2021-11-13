# Relatório Descritivo do *Goodreads' Best Books Ever*

Trabalho Prático 1 da disciplina de Ciência de Dados - UFC 2021.1, feito no [Google Colab](https://research.google.com/colaboratory/faq.html). Colocamos em um repositório para facilitar o acesso e a correção.

## Crie seu *environment*

Use o [`virtualenv`](https://virtualenv.pypa.io/en/latest/) para criar um ambiente Python.

```bash
virtualenv benv --python=python3

source benv/bin/activate
```

## Usage

Use o *package manager* [`pip`](https://pip.pypa.io/en/stable/) para instalar os pacotes necessários através do comando abaixo.

```bash
pip install -r requirements.txt
```

Depois, basta executar: 

```bash
jupyter notebook
```
Em seguida, clique no arquivo [GoodreadsDatasetAnalysis.ipynb](https://github.com/samirbraga/GoodreadsDatasetAnalysis/blob/main/GoodreadsDatasetAnalysis.ipynb).

## Dados Utilizados

O *dataset* utilizado está disponível [nesta página do Kaggle](https://www.kaggle.com/meetnaren/goodreads-best-books). O dado textual está presente no arquivo `./Dataset/book_data.csv`. As imagens podem ser baixadas na mesma página do *dataset*.

## Autores

- Alunos de Pós-Graduação em Ciência da Computação (MDCC/UFC): Bárbara Neves, Lucas Benjamim e Samir Braga; e,
- Aluno de Graduação em Ciência da Computação: Vinicius Bernardo.
