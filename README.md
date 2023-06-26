# Max Drawndown

O Max Drawdown é uma métrica importante para avaliar o risco e o desempenho de um investimento. Neste repositório, apresento uma implementação em Python para calcular o Max Drawdown de uma série temporal de retornos de um ativo financeiro. Ele é definido como a maior queda observada entre o pico de um investimento e o ponto mais baixo subsequente antes de atingir um novo pico. É uma medida comumente usada para avaliar a volatilidade e o risco associados a um investimento.

# Como Calcular o Drawndown

O Drawdown é calculado considerando o valor máximo e mínimo da cotação, ou o pico e vale, respectivamente. Esses dados são primeiramente subtraídos e depois divididos:
* Drawndown = (Cotação Máxima - Cotação Mínima)/Cotação Máxima
* Max Drawndown = Drawndown mínimo

# Interpretação do Dranwdown

O drawdown representa a porcentagem da queda desde o mais recente ponto máximo de lucro. Assim, analisar o Drawndown é essencial para definir e monitorar estratégias de investimento, por indicar o quão estável ou instável se mostra um ativo. Isso porque ele é útil para comparar a volatilidade histórica de diferentes investimentos. Quanto menor o drawdown, maior a estabilidade do ativo, e vice-versa.

