# Estudo de Caso Cyclistic: Como um serviço de compartilhamento de bicicletas pode alcançar o sucesso?

## 📌 Sobre o Projeto

Este projeto faz parte do curso Capstone do **Certificado Profissional em Análise de Dados do Google (Coursera)**. O objetivo foi aplicar o processo de análise de dados completo para ajudar a empresa fictícia **Cyclistic** a aumentar sua base de assinantes, convertendo usuários casuais em membros anuais.

## 🎯 Objetivo de Negócio

A equipe de marketing da Cyclistic deseja entender como ciclistas casuais se comportam em comparação com os assinantes, a fim de formular estratégias que incentivem a conversão para o plano de associação anual.

## 🔍 Processo de Análise de Dados

Este projeto seguiu o processo de análise em 6 etapas:

1. **Perguntar (Ask)**  
   - Como o comportamento dos usuários casuais difere dos assinantes?
   - Que tipo de campanhas poderiam ser eficazes na conversão?

2. **Preparar (Prepare)**  
   - Fonte dos dados: [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html) (dados públicos de Chicago).
   - Período analisado: últimos 12 meses (dados limpos para consistência).

3. **Processar (Process)**  
   - Remoção de valores ausentes e duplicados.
   - Padronização de tipos de dados e formatação de colunas de datas.

4. **Analisar (Analyze)**  
   - Comparação de tempo médio de viagem, tipo de bicicleta, e horário de uso entre os grupos.
   - Identificação de padrões de uso por estação e dia da semana.

5. **Compartilhar (Share)**  
   - Visualizações desenvolvidas em R (ggplot2) e Tableau.
   - Insights apresentados abaixo e também no Tableau Public.

6. **Agir (Act)**  
   - Recomendações de marketing baseadas em dados (ver seção de Conclusões).

## 📊 Principais Insights

- Assinantes tendem a usar as bicicletas durante os dias úteis e horários de pico (provavelmente para ir ao trabalho).
- Casuais utilizam mais nos fins de semana e feriados, com foco em lazer.
- Assinantes preferem bicicletas tradicionais, enquanto casuais usam mais as elétricas.

## 🧠 Conclusões e Recomendações

- Criar campanhas focadas em lazer para finais de semana com incentivos à associação anual.
- Oferecer vantagens como quilômetros extras, descontos ou planos flexíveis para novos assinantes.
- Reforçar a presença da Cyclistic em eventos ao ar livre e locais turísticos nos fins de semana.

## 🧰 Ferramentas Utilizadas

- **R**: limpeza, manipulação e análise de dados (`tidyverse`, `lubridate`, `janitor`)
- **SQL**: consultas exploratórias
- **Tableau**: visualizações interativas ([veja no Tableau Public](https://public.tableau.com/))
- **Excel**: revisão preliminar e validação de estrutura

## 📁 Estrutura do Projeto

