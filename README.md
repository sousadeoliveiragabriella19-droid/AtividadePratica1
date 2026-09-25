# AtividadePratica1
aluno: Gabriella Sousa de Oliveira RA:2869704

O projeto apresentado consiste na aplicação prática dos algoritmos de busca BFS e DFS em um sistema de rotas de metrô. Esses algoritmos são utilizados para realizar buscas dentro de uma estrutura, permitindo encontrar caminhos entre diferentes pontos.

O sistema desenvolvido tem como objetivo possibilitar a consulta de rotas entre estações de metrô. Através dele, é possível verificar possíveis caminhos para chegar ao destino, identificar baldeações e também realizar simulações de rotas em situações em que determinadas estações ou linhas estejam fechadas.

Nesse sistema, cada estação do metrô é representada como um nó, enquanto as conexões entre as estações representam as arestas. Dessa forma, o metrô pode ser representado como um grafo, permitindo que os algoritmos de busca analisem as conexões existentes e encontrem um caminho entre a estação de origem e a estação de destino.

Como cada algoritmo funciona

BFS: O algoritmo BFS realiza a busca por níveis, analisando primeiro as estações que estão mais próximas do ponto de partida. Ele visita as possibilidades de caminho de forma organizada, avançando para as próximas estações até encontrar o destino. Em um grafo não ponderado, o BFS consegue encontrar o caminho com o menor número de trechos entre a origem e o destino.

Uma das vantagens do BFS é justamente encontrar o caminho mais curto nesse tipo de situação. Porém, uma de suas desvantagens é o consumo maior de memória, pois o algoritmo precisa armazenar as estações que ainda serão analisadas durante a busca.

DFS: O algoritmo DFS funciona de uma maneira diferente. Ele escolhe um caminho e continua seguindo por ele até chegar ao destino ou até encontrar uma situação em que não seja mais possível continuar. Quando isso acontece, o algoritmo retorna para uma estação anterior e tenta outro caminho.

Uma das principais vantagens do DFS é o menor consumo de memória em comparação ao BFS. Porém, ele não garante que o caminho encontrado seja o mais curto. Além disso, o resultado da busca pode variar dependendo da ordem em que as estações estão organizadas e são analisadas pelo algoritmo.

Dessa forma, os dois algoritmos podem ser utilizados no sistema de rotas, mas apresentam comportamentos diferentes. O BFS é mais adequado quando o objetivo é encontrar o caminho com menor número de trechos, enquanto o DFS pode ser utilizado para explorar diferentes possibilidades de caminhos, utilizando uma quantidade menor de memória.

