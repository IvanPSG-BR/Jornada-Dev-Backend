# [Tasksmith](https://github.com/IvanPSG-BR/Tasksmith-TCC/)

## 1. Visão Geral e Contexto

### 1.1. Propósito Original

* Desenvolver um sistema CRUD completo como TCC do Curso Técnico de Informática para gerenciar tarefas de forma gamificada.
* Combater a procrastinação e falta de motivação em realizar tarefas do cotidiano ao recompensar o usuário e penalizá-lo quando necessário, em forma de uma narrativa e com elementos comumente encontrados em jogos.

### 1.2. Funcionalidades Implementadas

* Autenticação;
* CRUD de tarefas;
* Ganho de níveis por pontos adquiridos ao completar uma tarefa;
* Melhoria do personagem.

### 1.3. Status Atual

* Finalizado e arquivado.

## 2. Stack Técnica & Arquitetura Inicial

### 2.1. Tecnologias Utilizadas

* **Backend:** PHP Vanilla
* **Frontend:** HTML, CSS + TailwindCSS, JS Vanilla, Vite
* **Banco de Dados:** MySQL

### 2.2. A Decisão Crítica da Época

* PHP foi a linguagem que estava sendo ensinada. Não utilizei framework pois não fomos instruídos a usar (se fosse pelo curso eu nem saberia o que é um framework). Ademais, achei que a curva de aprendizado seria alta e demorada, e que se eu utilizasse a tecnologia "pura" teria um maior aprendizado.

## 3. O Campo de Batalha: Desafios e Erros

### 3.1. Falta de Princípios Básicos de Código Limpo

* A arquitetura escolhida foi um Monolito + MVC (com Services), o que não foi má escolha. Entretanto, por causa da experiência 0 com desenvolvimento de website por completo (backend + frontend), o resultado foi um código spaghetti totalmente desorganizado, mesmo com os diretórios teoricamente servindo para organização.
* **Consequência:** Dificuldade em encontrar erros, confusão com o próprio código.

### 3.2. Uso de Tecnologias Puras

* Ao utilizar PHP puro para o desenvolvimento do backend, dificultei MUITO minha vida, pois a maior parte das coisas tive que implementar do zero. Durante a maior parte do desenvolvimento, nem mesmo utilizei uma ORM, ao invés disso, havia criado a minha própria "Query Builder". PS: *eu não sabia direito nem o que era ORM.*
* **Consequência:** O desenvolvimento ficou lento, maçante, me fez perder tempo com o que eu não precisava.

### 3.3. Overengineering

* Eu estava num período de achar que quanto mais complexamente organizado fosse o código, melhor. Péssima escolha.
* **Consequência:** Desacelerou o desenvolvimento, gerou muitos erros pela minha falta de base técnica e me rendeu muito estresse por causa do prazo e do quão difícil era mexer no código.

### 3.4. Definição do Escopo e Planejamento Tardios

* Demora para definir o escopo exato do TCC e fazer o planejamento adequado desde o início.
* **Consequência:** Me senti perdido ou desfocado durante muito tempo. Não sabia exatamente o quê ou como fazer, quando, onde e por que aplicar.

### 3.5 Base de Conhecimento Rasa

* Falta de uma orientação decente desde o início, inexperiência e colegas de equipe desinteressados na área de informática/programação.
* **Consequência:** A responsabilidade do website recaiu toda sobre mim, alguém que mesmo gostando da área e sabendo mais que a maioria da sala, ainda não tinha um nível de conhecimento suficiente para entregar algo minimamente bom, gerando um resultado medíocre.

## 4. O Que Não Fazer Novamente

| Desafio no Tasksmith  | Não Repetir em Hipótese Alguma                                   |
| :-------------------- | :--------------------------------------------------------------- |
| Código Limpo          | Embolar e misturar as camadas e responsabilidades da aplicação.  |
| Tecnologias Puras     | Temer a curva de aprendizado de um framework.                    |
| Overengineering       | Utilizar arquitetura e padrões complexos, não importa o projeto. |
| Escopo e Planejamento | Ter uma ideia e já sair codando.                                 |
| Base de Conhecimento  | Achar que sabe o suficiente e empacar.                           |

## 5. Regras de Ouro para o Próximo Projeto

* *Lição 1:* Separar estritamente as camadas e responsabilidades em geral da aplicação.
* *Lição 2:* Não temer a curva de aprendizado de um framework, afinal, eles são feitos para acelerar e facilitar a vida do desenvolvedor.
* *Lição 3:* Analisar o projeto para decidir o quão complexa deve ser a arquitetura dele e o porquê.
* *Lição 4:* Antes de pensar em tocar no código, definir muito bem escopo, tecnologias, métodos e tudo o que for necessário para não ficar perdido depois.
* *Lição 5:* Estar sempre se forçando e esforçando para aprender o necessário para trabalhar na área sem fazer burrada.

## 6. Reflexão Final e Impacto na Carreira

Apesar de ter sido uma experiência estressante, ela foi transformadora. Pude sentir na pele o aperto de um prazo, o custo de decisões erradas e ter minha primeira experiência criando um website "sério".

* **Maior Ganho:** Creio que 95% dos problemas derivaram da falta de um planejamento decente. Logo, diria que os impactos negativos que acarretaram disso foi a maior experiência.
* **Como este projeto me preparou para o NerdOS?** Sentei, me organizei, e desenhei (ou melhor, digitei) um plano de execução. Pontuei a arquitetura e estrutura necessárias para o projeto *entendendo* o impacto delas. Comecei a aprender um Framework. Estou constantemente buscando orientação de pessoas mais experientes e aprendendo como funcionam as coisas.