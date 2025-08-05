# 📁 Dados

Esta pasta contém os arquivos necessários para execução dos notebooks do projeto principal, voltado à análise de tweets sobre filmes de terror.

---

## 🔗 Acesso aos dados

Os arquivos estão hospedados externamente devido ao tamanho.  
O link para download via OneDrive está disponível no arquivo [`link_dados.txt`](./link_dados.txt).

---

## 📄 Arquivos disponíveis

- **`all_movies.csv`**  
  Base com informações dos filmes analisados: título, ano de lançamento, existência de sequência, entre outros atributos.

- **`base_completa_separada_filtrada-003.csv`**  
  Tweets coletados em inglês, organizados por filme e filtrados conforme critérios temporais definidos na pesquisa.

- **`combined_tweets_emotion-004.csv`**  
  Tweets anotados com emoções, identificadas por meio do modelo RoBERTa.

- **`combined_tweets_sentiment_emotion-002.csv`**  
  Tweets com informações combinadas de emoções e polaridade de sentimento (positivo, negativo, neutro), extraídas com o mesmo modelo.

- **`mestrado_scrapper.py`**  
  Script em Python utilizado para coleta dos tweets via scraping (pode não estar mais funcional devido a mudanças nas APIs).

- **`new-scrapper-tt-query.ipynb`**  
  Notebook usado para executar o scraper em ambiente Jupyter. Também sujeito a desatualização.

---

## 📌 Observações

- Os arquivos devem ser baixados manualmente e carregados nos notebooks conforme instruções.
- Os tweets analisados são exclusivamente em inglês, com foco em títulos de filmes de terror pré-definidos.

---
