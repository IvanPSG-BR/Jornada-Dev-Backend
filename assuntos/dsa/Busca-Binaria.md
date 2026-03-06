## Recapitulação

Pegando o gancho do início da explicação de [tempo logarítmico](./Big-O.md) do meu outro arquivo:

>"***Um sistema de E-commerce.***
>
>Digamos que a loja que usa esse sistema possui milhares de produtos diferentes, e, para fins didáticos, digamos também que o sistema só funciona buscando por ordem alfabética decrescente (A-Z).
>
>Agora, raciocine um pouco: o que você acha que aconteceria caso o sistema lesse um por um quando você pesquisasse "xícara", por exemplo? Quanto tempo acha que demoraria pra percorrer TODOS os produtos de TODAS as letras até o X?"

Com a busca binária, isso não é *nenhum* problema.

## Resumo

Busca Binária é um algoritmo que tem como objetivo reduzir o número de etapas/operações necessárias para encontrar um item específico em uma *lista ordenada* (isso é importante!). Ela funciona "cortando" o número de itens pela metade até obter o item desejado, possuindo assim um tempo de execução logarítmico (muito baixo!).

> Se não lembra o que é um logaritmo, vou tirar a explicação diretamente da minha fonte atual principal de estudo de DSA, o livro "Entendendo Algoritmos":
> 
> "[...] mas provavelmente lembra-se de como calcular exponenciais. A expressão log(10) 100 basicamente diz "Quantos 10s conseguimos multiplicar para chegar a 100?". A resposta é 2: 10 x 10. [...] Logaritmos são o oposto de exponenciais"
>
> PS: Se tratando de Notação Big O, apenas "log" sempre significa log(2).

E se você estiver se perguntando por quê a lista precisa ser ordenada, a resposta é simples: se você não tiver um critério para "cortar fora" metade de uma lista, como você poderia saber onde está o item que quer?

## Retomando o Exemplo

Para aplicar a Binary Search (cansei de escrever sempre do mesmo jeito) no contexto do problema do e-commerce, devemos executar os seguintes passos:

1. Pula para a metade dos produtos
2. Verifica se passou de onde estaria a palavra "xícara"
	1. Passou? Ignora tudo à "direita"
	2. Não passou? Ignora tudo à "esquerda"
3. Repete até chegar no item desejado

Simples, não?

E repara que, se não houvesse ordenação por alfabeto (ou qualquer outro tipo de ordenação), seria IMPOSSÍVEL de fazer essa verificação.

Ou seja, se a loja tiver 10000 produtos, ao invés de "verifica se é xícara; não é? Passa pro próximo" 10000 vezes no máximo, esse número é reduzido para incríveis cerca de 13 vezes (no pior dos casos)!

---
*Essa é a Busca Binária!*
