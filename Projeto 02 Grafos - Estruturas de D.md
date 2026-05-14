# Projeto 02: Grafos - Estruturas de Dados II

Este projeto consiste na implementação de um grafo não direcionado utilizando Lista de Adjacência e o desenvolvimento de algoritmos clássicos de percurso e identificação de componentes.

## Funcionalidades

O código está estruturado de forma modular e contempla:
- Criação do Grafo: Estrutura baseada em dicionário e listas.
- Busca em Largura (BFS): Exploração por camadas utilizando fila.
- Busca em Profundidade (DFS): Exploração recursiva por ramos.
- Componentes Conexas: Identificação e contagem de subgrafos isolados.

## Grafo de Teste Utilizado

O programa utiliza o grafo obrigatório solicitado no roteiro:
- Vértices: 0 a 9 (10 vértices).
- Arestas: (0-1), (1-2), (2-3), (4-5), (6-7), (7-8), (8-6).
- Nó Isolado: O vértice 9 não possui conexões.

## Como Executar

O projeto foi desenvolvido para ser executado no Google Colab ou em qualquer ambiente Python 3.x.

1. Copie o código do arquivo principal.
2. Cole em uma célula de código no Colab.
3. Clique em "Executar".

## Exemplo de Saída

Ao rodar o código, você verá a lista de adjacência detalhada, seguida pela ordem de visita das buscas e a separação das 4 componentes conexas encontradas.

## Desenvolvido para a disciplina de Estruturas de Dados II