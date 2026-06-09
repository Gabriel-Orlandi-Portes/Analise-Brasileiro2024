# 📊 Análise Exploratória - Campeonato Brasileiro Série A 2024

## 📌 Sobre o projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados utilizando informações das partidas do Campeonato Brasileiro Série A de 2024.

Através da análise dos dados, foram investigados padrões relacionados ao público dos jogos, resultados das partidas e desempenho dos clubes como mandantes, utilizando técnicas de manipulação, tratamento e visualização de dados.

O projeto foi desenvolvido em Python utilizando o Google Colab.

---

## 🎯 Objetivos

* Realizar uma análise exploratória sobre os dados do campeonato;
* Compreender a estrutura do dataset;
* Criar um dicionário de dados;
* Realizar tratamento e transformação das variáveis;
* Analisar variáveis individuais e relações entre variáveis;
* Criar visualizações para identificar padrões nos dados.

---

## 📂 Dataset

Os dados foram obtidos através do Kaggle:

🔗 Dataset:
https://www.kaggle.com/datasets/fabioschirmann/brasileiro-2024-srie-a-dataset

O conjunto de dados contém informações sobre partidas do Campeonato Brasileiro Série A 2024, incluindo:

* Data da partida;
* Horário;
* Time mandante;
* Time visitante;
* Placar;
* Público presente;
* Estádio.

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* Google Colab

---

## 🔎 Tratamento dos dados

Durante a análise inicial foi identificado que a variável `Publico` estava armazenada como texto (`object`) devido ao formato dos valores com separador de milhar.

Foi realizado o tratamento da variável para conversão para formato numérico (`int64`), permitindo a aplicação de análises estatísticas e visualizações.

---

## 📊 Análises realizadas

### 1. Resultados mais frequentes

**Pergunta analisada:**

>  Quais foram os placares mais comuns nas partidas do Brasileirão 2024?

Foi analisada a frequência dos resultados utilizando a variável `Placar`, identificando quais placares apareceram mais vezes durante o campeonato.

Visualização criada:

* Gráfico dos resultados mais frequentes.

---


### 2. Relação entre time mandante e público

**Pergunta analisada:**

> Quais times tiveram as maiores médias de público jogando como mandantes?

Foi realizado um agrupamento entre as variáveis:

* `Mandante`
* `Publico`

Calculando a média de público por equipe para identificar quais clubes tiveram maior presença de torcida em seus estádios.

Visualização criada:

* Ranking dos times com maior média de público como mandantes.

---

## 📈 Principais insights encontrados

A análise permitiu observar diferenças na presença de torcedores entre os clubes, identificando equipes com maior capacidade de atrair público quando jogam em casa.

Também foi possível analisar padrões nos resultados das partidas e compreender a distribuição do público durante o campeonato.

---

## 👨‍💻 Autor

Gabriel Orlandi

Projeto desenvolvido como atividade de análise de dados utilizando Python.
