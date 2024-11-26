# Projeto Telecomm

Status: Em desenvolvimento

 O Objetivo deste projeto é, através do tratamento e análise de uma base dados de vendas de uma empresa de telecomunicações, extrair informações sobre Taxa de Churn (Churn Rate) e perfil dos clientes. Dessa forma, através da visualização desses dados, seria possível tomar decisões de forma facilitada e assertiva.
A Taxa de Churn é um importante indicador para empresas pois apontam a quantidade de clientes que deixaram de fazer negócios em um período de tempo. Avaliando estes números, avaliando o perfil dos clientes e outras informações é possível, em muitos casos, reverter cancelamentos. 

## Sobre o projeto

 A base foi tratada através do curso "Pandas - Limpeza e Tratamento de Dados" da plataforma Alura. O tratamento foi realizados em três grandes etapas (ETL):
  1. Extração dos dados;
  2. Limpeza dos dados: Identificando e tratando dados nulos, duplicados e vazio;
  3. Análise exploratória
  4. Análise de Churn
  5. Preparação para modelo de predição

## Tecnologias

O tratamento foi realizado utilizando Python (Python 3.10.12), principalmente biblioteca Pandas, Numpy, seaborn e matplotilib, em um Jupyter Notebook. 

## Dashboard

O dashboard foi construído utilizando Power BI e Figma para construção do Layout.
![image](https://github.com/user-attachments/assets/7f628d0b-7e78-47c9-9a1f-0a2b83b7ebc0)


## Conclusões

Obtivemos uma taxa de churn igual a 26,49%, o que pode ser visto como um valor alto para o período. Porém, através das nossas análises podemos identificar possíveis contribuidores para esse número.

Percebemos que grande parte dos número de churn se encontravam em situações como, clientes que não optaram pelo suporte técnico do serviço de internet, que possuem uma modalidade de contrato mês a mês e também que optaram pelo pagamento via cheque eletrônico.

Outra variável interessante de se analisar também seria o período ativo dos clientes, como no último gráfico. Através dele podemos perceber que o índice de churn é bem maior no caso de clientes no começo do relacionamento com a empresa, ou seja, menores que 12 meses de atividade. O número de Churn, de forma geral, passa a diminuir conforme o passar do tempo de relacionamento. Esses números podem indicar falhas de comunicação ou problemas no onboarding desse cliente, porém, essa análise pode evidenciar oportunidades de melhorias e construção de planos de ação nesses pontos.
