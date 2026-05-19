#RELATORIO

Eu escolhi usar o método recursivo para a remoção dos nós da árvore binária. A escolha da recursividade foi feita porque ela deixa o código mais organizado e facilita o percurso pela árvore, já que cada nó pode possuir outras subárvores.
O método recursivo percorre a árvore comparando os valores até encontrar o nó que será removido. Depois de localizar o elemento, o algoritmo resolve 3 formas de remoções: remoção de nó folha, nó com apenas um filho e nó com dois filhos.
No caso de nós com dois filhos, foi utilizado o método do sucessor conforme foi solicitado na atividade, pegando o menor valor da subárvore direita para substituir o nó removido, mantendo a organização da árvore binária de busca.
A implementação recursiva também facilitou a atualização das referências entre os nós da árvore, tornando o código mais simples de entender e prático.
