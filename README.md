# 📊 Projeto de Análise de Dados - Análise Exploratória 
# Análise Salarial em Empregos Relacionados a Tecnologia

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green?style=for-the-badge)

## 📌 Visão Geral
Este projeto consiste em uma Análise Exploratória de Dados robusta sobre um conjunto de dados com mais de 22.000 registros salariais do mercado de tecnologia na Índia. O objetivo principal foi responder algumas perguntas com o projeto, sobre valorização de cargos, polos tecnológicos e suas respectivas médias salariais, influência da reputação da empresa nos salários, impacto do tipo de contrato na média salarial, salários reportados por cargo, empresas com maiores salários e avaliações na capital da Índia.

## 🛠️ Metodologia e Limpeza de Dados

Antes de responder às perguntas de negócio, fiz alguns tratamentos e limpezas no dataset:
* **Tratamento de Nulos:** Identificação e preenchimento de dados faltantes em nomes de empresas.
* **Padronização:** Unificação de cargos similares (ex: *SDE* e *Software Development Engineer*) para evitar fragmentação da análise.
* **Remoção de Outliers (IQR):** Aplicação do método do Intervalo Interquartil para remover salários extremos que distorciam a média, focando a análise na realidade da maior parte do mercado.

# Observação:
O dataset original provém do mercado indiano. Os valores numéricos apresentados nas análises representam Rúpias Indianas (₹ / INR). A análise foca nas tendências relativas e distribuições, independente da conversão cambial.
<br />

## 💡 Principais Insights de Negócio

### 1. Onde está o dinheiro? (Top Cidades)
A análise geográfica revelou que **Mumbai** e **Bangalore** e **Pune** atuam como os grandes polos financeiros de tech na região, apresentando médias salariais superiores a capitais administrativas como New Delhi.
