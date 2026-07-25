# otimizacao-combinatoria-mochila

# Implementação em Otimização Combinatória

## Problema da Mochila utilizando Heurística Gulosa

### Aluno

- Nome: Mateus Vital
- Disciplina: Tópicos Especiais em Computação
- Professor: João Paulo
- Link do Colab: https://colab.research.google.com/drive/1ZGsE9nY6kkdm-p9yiOwEQmx8rxtKwR4B?usp=sharing
---

## Introdução

O Problema da Mochila (Knapsack Problem) é um dos problemas clássicos da Otimização Combinatória. Seu objetivo é selecionar um conjunto de itens de forma que o valor total seja maximizado sem ultrapassar a capacidade máxima da mochila.

Neste trabalho foi utilizada uma heurística gulosa, que seleciona os itens de acordo com a melhor relação entre valor e peso. Essa abordagem busca encontrar uma boa solução com baixo custo computacional, embora não garanta a solução ótima em todos os casos.

---

## Desenvolvimento

### Problema

Foi considerada uma mochila com capacidade máxima de 5 kg e um conjunto de itens com pesos e valores previamente definidos.

### Função Objetivo

Maximizar o valor total dos itens transportados sem exceder a capacidade da mochila.

### Variáveis

Cada item possui:

- Nome
- Peso
- Valor

### Estratégia Algorítmica

A estratégia utilizada foi uma heurística gulosa.

Inicialmente é calculada a razão entre valor e peso de cada item. Em seguida, os itens são ordenados em ordem decrescente dessa razão. O algoritmo percorre a lista e adiciona cada item à mochila apenas se sua inclusão não ultrapassar a capacidade máxima.

### Linguagem

- Python
- Google Colab

### Como executar

1. Abra o notebook no Google Colab.
2. Execute todas as células na ordem.
3. O programa exibirá os itens selecionados, o peso total e o valor total da mochila.

---

## Resultados

Após a execução do algoritmo, foram selecionados os itens que apresentaram a melhor relação entre valor e peso, respeitando a capacidade máxima da mochila.

Ao final da execução são exibidos:

- Itens escolhidos
- Peso total
- Valor total

---

## Conclusão

A heurística gulosa apresentou uma solução viável para o Problema da Mochila de maneira simples e eficiente. Embora não garanta a solução ótima em todos os cenários, sua implementação possui baixa complexidade e produz bons resultados para o exemplo utilizado neste trabalho.

---

## Referências

GOLDBARG, Marco Cesar; LUNA, Henrique Pacca. Otimização Combinatória e Programação Linear. Elsevier.

TALBI, El-Ghazali. Metaheuristics: From Design to Implementation. Wiley.
