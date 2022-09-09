# Identificação de Níveis de CO<sub>2</sub>

Este programa analise um dicionário cujas chaves são estados brasileiros e cujos valores são listas. Cada lista contém cinco valores, cada um representando o nível de CO<sub>2</sub> lido por um sensor durante um certo período.

O programa tem o objetivo de criar um alerta caso o nível médio de CO<sub>2</sub> seja superior ao limite estabelecido, que é de 450.

Para cada chave do dicionário — que é uma sigla de um estado brasileiro —, o programa calcula a média dos valores da lista e verifica se o mesmo é superior ao limite especificado. Em caso afirmativo, o programa identifica que o estado está em estado de alerto; caso contrário, o estado está em estado normal.

Ao término de sua execução o programa exibe uma tabela com a situação de cada estado.
