# 📊 Projeto de Análise de Dados - Análise Exploratória 
# Análise Salarial em Empregos Relacionados a Tecnologia

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green?style=for-the-badge)

## 📌 Visão Geral
Este projeto consiste em uma Análise Exploratória de Dados robusta sobre um conjunto de dados com mais de 22.000 registros salariais do mercado de tecnologia na Índia. O objetivo principal foi responder algumas perguntas com o projeto, sobre valorização de cargos, polos tecnológicos e suas respectivas médias salariais, influência da reputação da empresa nos salários, impacto do tipo de contrato na média salarial, salários reportados por cargo, empresas com maiores salários e avaliações, na capital da Índia, visando a criação de insights e percepções acerca do resultado das análises.

## 🛠️ Metodologia e Limpeza de Dados

Antes de responder às perguntas de negócio, fiz alguns tratamentos e limpezas no dataset:
* **Tratamento de Nulos:** Identificação e preenchimento de dados faltantes em nomes de empresas.
* **Padronização:** Unificação de cargos similares (ex: *SDE* e *Software Development Engineer*) para evitar fragmentação da análise.
* **Remoção de Outliers (IQR):** Aplicação do método do Intervalo Interquartil para remover salários extremos que distorciam a média, focando a análise na realidade da maior parte do mercado.

# Observação:
O dataset original provém do mercado indiano. Os valores numéricos apresentados nas análises representam Rúpias Indianas (₹ / INR). A análise foca nas tendências relativas e distribuições, independente da conversão cambial.

👉 [Clique Aqui para visualizar o projeto Completo](https://github.com/lucasgerc/Analise_salarios/blob/main/Projeto%20Analise%20de%20dados.ipynb)

<br />

## 💡 Principais Percepções após a análise

## 1. Onde está o dinheiro? (Top Cidades)
A análise geográfica revelou que **Mumbai**, **Bangalore** e **Pune** atuam como os grandes polos financeiros de tech na região, apresentando médias salariais superiores a capitais administrativas como New Delhi.

![Médias salariais por cidade](/img/media_salarial_cidade.png)

## 2. Cargos mais valorizados
Os dados mostraram que cargos técnicos especializados, especificamente em **Banco de Dados (Database)** e **Engenharia de Software (SDE)**, lideram o ranking de remuneração média.

![Média salarial por cargo](/img/media_salarial_cargo.png)

## 3. Análise de causalidade entre nota da empresa e remuneração
Uma análise de correlação entre a nota da empresa (Rating) e a remuneração média provou que **não existe correlação linear forte**. Empresas com nota 3.0 pagam, em média, valores competitivos comparados a empresas "5 estrelas".
A reputação da marca empregadora (Branding) não é um preditor direto de salário alto.

![Rating vs sálario](/img/media_salarial_por_rating.png)

## 🔒 Conclusão do Projeto

Este projeto reforça que o setor de tecnologia não é apenas um dos mais dinâmicos, mas também um dos mais estruturados da economia global. Através da análise, pudemos concluir que:
* **A especialização técnica é recompensada: Áreas fundamentais como Engenharia de Software (SDE) e Gerenciamento de Dados (Database) apresentam estruturas salariais robustas, refletindo a alta demanda por profissionais que sustentam a infraestrutura digital das empresas.**
* **O mercado de tecnologia na Índia (assim como o global) é polarizado em centros de excelência. Profissionais em hubs como Mumbai e Bangalore têm acesso a ecossistemas que valorizam a senioridade com pacotes de remuneração agressivos.**
* **Cultura vs. Compensação: O fato de não haver correlação direta entre o Rating da empresa e o salário médio desmistifica a ideia de que "boas empresas para se trabalhar" são necessariamente as que pagam mais.**
