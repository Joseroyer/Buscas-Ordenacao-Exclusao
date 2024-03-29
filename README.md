# Buscas, Ordenação e Exclusão


### Métodos de Busca: <h3>
  - **Desordenados:** Pode estar em qualquer ordem.
    * Busca Exaustiva: Acessa de forma sequencial até encontrar o elemento ou até todos os elementos serem verificados.
    * Busca Exaustiva com Sentinela: Insere o elemento a ser encontrado após a última posição do array de forma sequencial, assim, verificando as posições até achar o mesmo.
  - **Ordenados:** O array necessita estar ordenado.
    * Busca Sequencial Indexada: Realizado de forma sequencial até encontrarar o elemento maior ou idêntico, ou até todos os elementos do vetor forem verificados.
    * Busca Binária: A busca se inicia pelo elemento do meio. Se o elemento procurado for menor, procura-se pela primeira metade, senão na segunda metade.

  
### Métodos de Ordenação: <h3>
  - **Inserção Direta (Insertion Sort):** Percorre-se os itens já ordenado da direita para esquerda, comparando cada item com aquele que vai ser inserido. Enquanto o item inserido for menor, o item que está sendo comparado se descola a direita.
  - **Ordenação por Bolhas (Bubble Sorte):** Efetua varreduras repetidas sobre o vetor, deslocando para sua extremidade a esquerda, o menor dos elementos.
  - **Seleção Direta (Selection Sort):**
    * Encontrar o maior elemento da lista e sua posição.
    * Se a posição do maior elemento for menor que o tamanho do vetor, faz a troca, assim, coloca o maior elemento na última posição.
    * Decrementa o tamanho até que o tamanho for maior que 0. (TL > 0)
  
### Exclusão <h3>
  * **Exclusão Física:** A Física faz a remoção do registro.
  * **Exclusão Lógica:** A Lógica utiliza uma coluna de status, se o statuso for ativo ele é true ou 1, senão é false ou 0 para inativo.
