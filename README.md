# Implementações de Algoritmos de Otimização de Rotas

Este repositório contém exemplos de implementação em Python para diferentes algoritmos de otimização de rotas no transporte escolar. O objetivo é comparar a eficácia de diferentes abordagens na solução do problema de roteamento de veículos escolares.

## Objetivo

O objetivo deste projeto é fornecer implementações práticas e comparativas de algoritmos utilizados para otimização de rotas no transporte escolar. Os algoritmos abordados incluem:

- Iterated Local Search (ILS)
- Métodos Exatos (Branch and Bound)
- Hybrid Iterated Local Search (HILS)
- Greedy Randomized Adaptive Search Procedure (GRASP)
- Logic-based Benders Decomposition
- Biased Random-Key Genetic Algorithm (BRKGA)

## Configurações Básicas

### Pré-requisitos

Para executar os códigos deste repositório, você precisará ter o Python 3 instalado, além de instalar algumas bibliotecas adicionais. Você pode instalá-las utilizando `pip`:

```bash
pip install pulp
```

## Clonando o Repositório
### Clone o repositório para a sua máquina local:

```bash
git clone https://github.com/seu_usuario/algoritmos_otimizacao_rotas.git
cd algoritmos_otimizacao_rotas
```
## Executando o Notebook
### Para executar o notebook, você pode utilizar o Jupyter Notebook ou Jupyter Lab. Se você não os tiver instalados, pode instalá-los utilizando pip:

```bash
pip install notebook jupyterlab
```
## Inicie o Jupyter Notebook:

```bash
jupyter notebook Algoritmos_Otimizacao_Rotas.ipynb
```

# Descrição dos Algoritmos Implementados

### Iterated Local Search (ILS)
Iterated Local Search (ILS) é uma meta-heurística baseada na aplicação iterativa de uma busca local para encontrar soluções melhores. A cada iteração, uma perturbação é aplicada para escapar de ótimos locais e explorar melhor o espaço de solução.

### Métodos Exatos (Branch and Bound)
Os métodos exatos, como Branch and Bound, são algoritmos que garantem encontrar a solução ótima ao explorar o espaço de soluções de maneira sistemática e eliminar subespaços que não contêm soluções ótimas.

### Hybrid Iterated Local Search (HILS)
Hybrid Iterated Local Search (HILS) combina ILS com algoritmos genéticos. A busca local é aplicada a uma população de soluções, onde a seleção e a recombinação são utilizadas para explorar o espaço de soluções.

### Greedy Randomized Adaptive Search Procedure (GRASP)
GRASP é uma meta-heurística que consiste em duas fases: construção e busca local. Na fase de construção, uma solução inicial é criada de forma gulosa e aleatória. Na fase de busca local, essa solução é iterativamente melhorada.

### Logic-based Benders Decomposition
Logic-based Benders Decomposition é uma técnica de decomposição utilizada para resolver problemas de otimização grandes e complexos, dividindo-os em um problema mestre e vários subproblemas que são resolvidos iterativamente.

### Biased Random-Key Genetic Algorithm (BRKGA)
Biased Random-Key Genetic Algorithm (BRKGA) é uma variante dos algoritmos genéticos que utiliza chaves aleatórias para representar soluções. A recombinação é influenciada por um viés para selecionar melhores combinações de genes.
