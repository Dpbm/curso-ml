# Algoritmos de busca e otimização.

algoritmos que visam busacar a melhor solução possivel para determinado problema, geralmente para problemas que não possuem uma solução exata (como uma equação matemática). Para isso o algoritmo deve tentar encontrar a melhor solução dentre o espaço de soluções.

exemplos de problema: 
1. caixeiro viajante
2. xadrez
3. labirintos

técnicas:
1. redução do espaço de busca
2. algoritmos heurísticos 
3. elementos estocásticos

classificação dos algoritmos:
* solução: encontra uma solução
* solução ótima: encontra uma solução ótima
* complexidade de tempo: qual o tempo levará para encontrar uma solução 
* complexidade de espaço: quanto de memória o algoritmo precisa

elementos de um problema de busca:
* S: espaço de busca
* I: estados iniciais
* O: conjunto de objetivos
* FS: função que pega o estado atual e retorna os estados alcançaveis
* FC: (função de custo/avalição/objetiva) pega o estado atual e um possivel estado próximo e retorna o custo

Busca local:
* melhor solução em uma vizinhança (um espaço pequeno)
* não garante a melhor solução (mas pode conseguir)

Busca global:
* explora todo o espaço de busca
* procura a melhor solução global

Local Optima:
* Busca solução nas proximidades
* Melhor solucão da busca local


Função de custo
* pode em alguns casos dizer se uma solução é a melhor global e em outros a melhor local

