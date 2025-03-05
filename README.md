# Classificador com Rede Neural Artificial - Base de Dados Iris

## Descrição
Este projeto foi desenvolvido como atividade da matéria de Inteligência Computacional do Curso de Mestrado em Informática da Universidade Federal do Espírito Santo. O objetivo é desenvolver um classificador baseado em Rede Neural Artificial do tipo feed-forward aplicado à base de dados Iris.

## Estrutura do Notebook

### 1. Coleta de Dados
Instalação das bibliotecas necessárias e carregamento da base de dados Iris.

### 2. Pré-processamento
Análise e balanceamento dos dados, além de normalização para melhorar a convergência do modelo.

### 3. Definição da Arquitetura da Rede
Configuração da rede neural com camadas de entrada, ocultas e de saída, utilizando funções de ativação adequadas e otimizadores.

### 4. Treinamento e Avaliação
Treinamento do modelo utilizando cross-validation e avaliação do desempenho utilizando o F1-score macro.

### 5. Otimização com Grid Search
Utilização de Grid Search para encontrar a melhor combinação de hiperparâmetros para a rede neural.

## Resultados
O modelo apresentou um desempenho satisfatório com um F1-score macro de 0.982 no conjunto de teste. A matriz de confusão mostra que o modelo teve apenas uma classificação incorreta, mostrando a robustez de redes neurais.

## Autor
Antonio Victor de Oliveira Borssato
