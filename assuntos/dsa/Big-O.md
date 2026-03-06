## Resumo

A notação Big O é algo de extrema importância no mundo da computação. Apesar de ser frequentemente associada à performance de forma direta, não é bem isso que ela mede.

Essa notação é uma métrica de *o quão bem um algoritmo escala conforme o número de operações cresce*, levando em conta (geralmente) o pior caso.

O que isso significa, na prática?

## Exemplos

### Tempo Linear - O(n)

Digamos que você é uma celebridade e está fazendo uma sessão de autógrafos (*eu literalmente acabei de pensar nesse exemplo!*). Para mostrar que se importa com os fãs, você pergunta o nome de cada um, coisinha simples.

Para saber o nome de **todos** os fãs, que é seu objetivo, você precisa perguntar um por um, certo? Logo, o "tempo de execução" desse "algoritmo" (percorrer uma lista de fãs perguntando o nome de cada um) é de O(n)

O(n) significa que o tempo cresce de forma linear de acordo com o número de "entradas" (fãs, nesse caso). Se um fã demora 10s para saber o nome, 10 fãs demoram 100s, 100 fãs são 1000s e assim sucessivamente.

![](big-o-exemplo-1.png|610)

### Tempo Constante - O(1)

Ok, vamos exercitar um pouco mais a imaginação. Você é dono de um negócio recém inaugurado, e pensou em fazer uma promoção para os 20 primeiros clientes, aquela coisa pra já puxar gente pra conhecer seu trabalho.

Não importa se vão aparecer 20, 50, 100, 1000 clientes, ***a promoção só cobre os 20 primeiros.***

Portanto, o número de entradas (clientes) pode ser de toda a população humana, mas não vai importar, porque esse "Algoritmo" vai pegar APENAS os 20 primeiros; isso é O(1)

![](big-o-exemplo-2.png|610)

### Tempo Logarítmico - O(log n)

Mais uma vez, vamos imaginar o cenário, dessa vez um pouco mais voltado ao âmbito de *software*:

***Um sistema de E-commerce.***

Digamos que a loja que usa esse sistema possui milhares de produtos diferentes, e, para fins didáticos, digamos também que o sistema só funciona buscando por ordem alfabética decrescente (A-Z).

Agora, raciocine um pouco: o que você acha que aconteceria caso o sistema lesse um por um quando você pesquisasse "xícara", por exemplo? Quanto tempo acha que demoraria pra percorrer TODOS os produtos de TODAS as letras até o X?

Porém, existe uma maneira mais rápido do que essa denominada "busca simples". A **[Busca Binária](./Busca-Binaria.md)**...

Spoiler:
![](big-o-exemplo-3.png)

### Tempo Linear-Logarítmico - O(n log n)

**TODO**

### Tempo Quadrático - O(n²)

**TODO**

---
*Essa é a Notação Big O!*
