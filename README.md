# Algoritmo Genético: otimizando o Problema do Caixeiro Viajante

O algoritmo genético é uma aplicação da abordagem evolutiva (seleção natural das espécies) para a aprendizagem de máquina indutiva. Ou seja, ele aplica princípios evolutivos, como seleção, recombinação e mutação, em uma população de soluções candidatas. Então, basicamente, o algoritmo vai tentar encontrar várias soluções e usar a informação obtida (função objetivo) para conseguir soluções cada vez melhores.

Para isso, vamos usar a [biblioteca deap](https://deap.readthedocs.io/en/master/overview.html).

## Problema do Caixeiro-Viajante
O TSP, ou problema do caixeiro-viajante em português, representado na figura, consiste na procura de um circuito que possua a menor distância, começando numa cidade (ou local) qualquer, entre várias, visitando cada cidade (local) precisamente uma vez e regressando à cidade (local) inicial.
