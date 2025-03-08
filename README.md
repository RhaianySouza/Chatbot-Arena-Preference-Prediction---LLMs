# Chatbot Arena Preference Prediction

Este projeto tem como objetivo prever qual resposta os usuários preferem em uma batalha entre respostas de chatbots, alimentados por Modelos de Linguagem Grande (LLMs). Utilizando dados coletados do *Chatbot Arena*, onde os usuários interagem com dois chatbots anônimos e escolhem a resposta que preferem, o projeto busca melhorar a interação dos chatbots com os usuários, alinhando as respostas às preferências humanas.

## Desafio

A competição propõe o desenvolvimento de um modelo de aprendizado de máquina que preveja qual das respostas geradas por dois modelos de chatbot será a preferida por um usuário, baseado em diversos atributos. O modelo será avaliado com base na perda logarítmica entre as probabilidades previstas e os valores reais.

## Estrutura do Projeto

Este repositório contém o código necessário para pré-processamento, modelagem e análise dos dados coletados da *Chatbot Arena*. O objetivo é criar um modelo robusto que preveja qual resposta será preferida, com base nos seguintes componentes:

- **Dados de entrada**: Conversas entre usuários e chatbots, onde o usuário escolhe entre duas respostas geradas por dois modelos de LLM.
- **Modelo de Machine Learning**: Um modelo treinado para prever qual resposta é preferida, levando em consideração fatores como viés de posição, verbosidade e auto-promoção.
- **Avaliação**: O modelo é avaliado com base na métrica de perda logarítmica (log loss) entre as previsões e as respostas reais.

## Objetivo

O objetivo principal deste projeto é desenvolver um modelo de machine learning que possa:

1. Prever qual das duas respostas geradas por chatbots será preferida pelo usuário.
2. Minimizar os vieses como *position bias*, *verbosity bias* e *self-enhancement bias*.
3. Contribuir para a melhoria das interações de chatbots com base nas preferências reais dos usuários.

## Como Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/RhaianySouza/Chatbot-Arena-Preference-Prediction-LLMs/edit/main/README.md
