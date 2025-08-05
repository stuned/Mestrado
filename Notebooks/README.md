# 🎬 Análise de Emoções em Tweets sobre Filmes de Terror

Este repositório reúne uma série de notebooks desenvolvidos com o objetivo de investigar se métricas derivadas de tweets em inglês — contendo menções a filmes de terror pré-selecionados — podem indicar alguma influência na possibilidade de produção de sequências (sequels).

A análise considera tweets coletados dentro de recortes específicos de tempo e aplica técnicas de NLP para identificar sentimentos e emoções, agregando essas informações por filme.

Mais detalhes sobre o escopo da pesquisa, critérios de seleção e fundamentação teórica estão disponíveis no [PDF da dissertação](../Dissertação%20Mestrado/Mestrado_Brenno_Ruschioni_de_Oliveira.pdf).

---

## 📚 Notebooks

1. **`BERT-Tweets.ipynb`**  
   Pré-processamento dos tweets e aplicação do modelo RoBERTa para análise de sentimentos e emoções, tweet a tweet.

2. **`Merge_Movies_and_Tweet_Data.ipynb`**  
   Integra os dados dos tweets com os dados dos filmes, agregando informações por obra.

3. **`Random_Forest_Tweets_Movies.ipynb`**  
   Treinamento de modelo Random Forest para avaliar a influência das variáveis emocionais na classificação dos filmes.

4. **`XGBoost_Tweets_Movies.ipynb`**  
   Abordagem semelhante à anterior, utilizando XGBoost para fins comparativos.

---

## 🚀 Como executar

Todos os notebooks foram desenvolvidos para execução via **Google Colab**.

### 📁 Dados

Os arquivos necessários estão disponíveis na pasta [`Dados/`](../Dados/link_dados.txt), com links de download via OneDrive indicados nos notebooks.

> Ao abrir o notebook no Colab, siga as instruções e faça upload dos arquivos conforme solicitado.

---

## 🛠️ Ferramentas utilizadas

- Python (Jupyter Notebooks)
- RoBERTa (via HuggingFace Transformers)
- Pandas, Scikit-learn, XGBoost
- Google Colab

---

## 👨‍💻 Autor

[Brenno Ruschioni de Oliveira](https://www.linkedin.com/in/brennoruschioni/)  
Universidade de São Paulo – Mestrado em Ciência da Informação

---
