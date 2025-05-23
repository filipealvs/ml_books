# Airflow DAG - Scraping de Livros do Mercado Livre

Este projeto consiste em uma **DAG do Apache Airflow** que realiza o scraping de dados de livros relacionados à engenharia de dados no site **Mercado Livre**. O objetivo é extrair títulos e preços de livros e armazená-los em um banco de dados SQL para análise futura.

## Funcionalidades

- Raspagem de dados com `requests` e `BeautifulSoup`
- Tratamento e limpeza de dados com `pandas`
- Armazenamento dos dados em uma tabela SQL
- Agendamento automático com Airflow (`@daily`)
- Evita duplicação de títulos com controle de páginas

## Tecnologias utilizadas

- [Apache Airflow](https://airflow.apache.org/)
- [Python 3.9+](https://www.python.org/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)
- [PostgreSQL](https://www.postgresql.org/)

