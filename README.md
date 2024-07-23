# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)




## 🚀 Passo a Passo

### 1. Selecionando o Dataset

-   O dataset selecionado foi uma opção disponibilizada pelo sagemaker com dados relacionados a logistica de entregas no periodo de 2020-21 por determinadas empresas.

### 2. Construção/Treinamento

-   Na etapa de construção do modelo, como referência para a predição, decidi escolher a coluna de código do produto com a configuração do tipo de modelo definido para classificar em 3 ou mais categorias. Dessa forma, é possivel entender o tempo da entrega, antecipar a correção de erros e analisar a recorrência em que o cliente consome determinado produto.

### 3. Analise

-   Ao analisar, o modelo levará em consideração a precisão e acurácia como principais metricas no processo. Apontando quantas vezes e o quão correto foram os resultados.

### 4. Prever

-   Logo na primeira previsão, apresenta divergência no resultado, na qual a quantidade de encomendas em tempo hábil foi superior ao previsto.
