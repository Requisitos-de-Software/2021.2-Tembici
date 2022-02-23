# Priorização

## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
|1.0| 19/02 | Criação da introdução da técnica de Priorização | Gabriel Sabanai e Paulo Henrique |
|1.0| 20/02 | Adição dos requisitos coletados | Gabriel Sabanai e Paulo Henrique |

## Introdução

MoSCoW é uma técnica que ajuda na construção de priorização de atividades de um sistema, esta técnica é muito utilizada na engenharia de requisitos a fim de definir a importância/prioridade   entre as partes interessadas dos requisitos levantados por um sistema/projeto.

## Metodologia

### MoSCoW

A metodologia MosCoW está muito ligada à metodologias àgeis por se tratar de uma técnica de priorização e faz o acrônimo de de 4 letras que representam 4 verbos, utilizamos esses verbos para a classificação e identificação das prioridades de cada atividade/requisito, sendo elas:

- Must: Este verbo representa uma atividade que irá agregar muito favolr ao projeto finale que indispensável para a sua construção.
- Should: Este verbo representa as tarefas que são importantes porém não são fundamentais para a construção do software.
- Could: Este verbo representa as tarefas que não são tão muito importantes, não são fundamentais para o sistema e são desejáveis para o software, um exemplo seria, colocar a atividade na entrega final, após o MVP como plus na agregação de valor.
- Would/Want/Won't: Estes verbos são para os requisitos menos críticos e que possuem um valor/retorno menor do que os outros para o software.


## Resultados

### Proporção de Must, Should, Could e Would

| Prioridade | Quantidade de Requisitos |
|-|-|
|Must| 13 |
|Should| 6 |
|Could| 4 |
|Would| 1 |

### Requisitos e suas prioridades

| Identificação | Requisito | Técnica | Prioridade |
|---|---|---|---|
| RF01 | O aplicativo deve permitir o cadastro/login do usuario | Brainstorm | MUST |
| RF02 | O aplicativo deve aceitar utilizar a localização geográfica do usuario para que posso utilizar o aplicativo  | Brainstorm | MUST |
| RF03 | O aplicativo deve mostrar uma visualização do mapa e o ponto que o usuário se encontra para que tenha noção de onde está | Brainstorm, Introspecção | SHOULD |
| RF04 | O aplicativo deve mostrar os pontos de bicicleta próximos ao usuário para que ele tenha noção de onde pegá-las | Brainstorm, Introspecção, Questionário | MUST |
| RF05 | O aplicativo deve mostrar a quantidade de bicicletas disponíveis em cada estação para que o usuário consiga saber se há bicicletas disponíveis | Brainstorm, Introspecção, Questionários | MUST |
| RF06 | O aplicativo deve permitir que o usuário faça a escolha de um plano de aluguel para que realizar o pagamento | Brainstorm, Introspecção, Questionário | MUST |
| RF07 |  O aplicativo deve permitir que o usuário consiga realizar o pagamento do plano de aluguel para que possa utilizar as bicicletas | Brainstorm, Introspecção | MUST |
| RF08 | O aplicativo deve permitir que o usuário consiga ver seu histórico de viagens para que ele consiga ver o quanto já andou com o uso do aplicativo | Brainstorm, Introspecção | SHOULD |
| RF09 | O aplicativo deve cobrar o usuário caso ele passe do tempo limite de uso da bicicleta para que tenha controle do uso e do plano do usuário | Brainstorm | MUST |
| RF10 | O aplicativo deve avisar o usuário caso o seu tempo esteja acabando para que ele tenha noção do tempo de uso  | Brainstorm | SHOULD |
| RF11 | O aplicativo deve conter premiações e recompensas gamificadas para que o usuário se sinta mais engajado em usá-lo  | Brainstorm | WOULD |
| RNF12 | O aplicativo deve funcionar em dispositivos de tamanhos diferentes  | Brainstorm | SHOULD |
| RNF13 | O sistema e as estações de bicicleta devem ter uma comunicação prática  | Brainstorm | SHOULD |
| RNF14 | O aplicativo pode possuir um sistema gamificado que apresentará de maneira simples o progresso diário de km e calorias em corridas  | Brainstorm, Introspecção, Questionário | COULD |
| RF15 | O aplicativo pode possuir uma seção fomentando os pontos positivos de se utilizar as bicicletas no dia-a-dia, como melhorar a saúde, ser menos poluente e ser mais barato quando comparados a outros meios de locomoção  | Brainstorm, Introspecção | COULD |
| RF16 | O aplicativo pode possuir uma função de bloquear um usuário de alugar bicicletas dado um certo número de infrações  | Brainstorm | COULD |
| RF17 | O usuário deverá poder acessar o aplicativo utilizando seu aparelho móvel| Introspecção | MUST |
| RF18 | O usuário deverá estar logado e possuir um plano para conseguir pegar uma bicicleta | Introspecção | MUST |
| RF19 | O usuário poderá desbloquear uma bicicleta utilizando um código do aplicativo a ser digitado em teclado localizado no posto de bicicleta | Introspecção | MUST |
| RF20 | O usuário poderá verificar a quantidade de vagas em cada ponto para devolver sua bicicleta | Introspecção | MUST |
| RF21 | O usuário poderá visualizar enquanto estiver em viagem o tempo que está sobre posse da bicicleta | Introspecção | SHOULD |
| RF22 | O usuário poderá utilizar um cupom de desconto caso possua, para diminuir o valor de seu plano | Introspecção | COULD |
| RF23 | O app deve permitir que usuário assinante consiga retirar uma bicicleta em uma estação | Questionário | MUST |
| RF24 | O app deve permitir que usuário assinante consiga retirar uma bicicleta em uma estação | Questionário | MUST |


## Referências
<p> Aprenda a usar a técnica MoSCoW nos projetos da sua agência!. Disponível em: https://rockcontent.com/br/blog/metodo-moscow/. Acesso em: 19 de feereiro de 2022.
<p>Aplicativo Tembici. Disponível em: https://www.tembici.com.br. Acesso em: 19 de fevereiro de 2022.