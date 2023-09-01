# Sorting-algorithms-in-java
---
# Comparação de Algoritmos de Ordenação

Este repositório contém implementações em Java de três algoritmos de ordenação: Bubble Sort, Quick Sort e Insertion Sort. O objetivo é comparar a eficiência desses algoritmos em diferentes cenários.

## Algoritmos

### Bubble Sort

O Bubble Sort é um dos algoritmos de ordenação mais simples. Ele funciona trocando elementos adjacentes se estiverem na ordem errada. Este algoritmo tem uma complexidade de tempo de \(O(n^2)\).

### Quick Sort

O Quick Sort é um algoritmo de ordenação muito mais eficiente comparado ao Bubble Sort. Ele usa uma abordagem de dividir e conquistar para ordenar elementos. Este algoritmo tem uma complexidade de tempo médio de \(O(n \log n)\).

### Insertion Sort

O Insertion Sort é um algoritmo simples que constrói a matriz final um item de cada vez. É muito menos eficiente em listas grandes do que algoritmos mais avançados, como Quick Sort. Este algoritmo também tem uma complexidade de tempo de \(O(n^2)\).

## Como Executar

1. Clone este repositório.
2. Navegue até o diretório onde o código-fonte está localizado.
3. Compile e execute cada algoritmo individualmente.

Exemplo para compilar e executar o Bubble Sort:
```bash
javac BubbleSort.java
java BubbleSort
```

## Métricas de Comparação

Para uma comparação mais detalhada, considere os seguintes pontos:

- Tempo de execução
- Número de comparações
- Número de trocas (swaps)
