# MosCoW
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 19/02/2022 | Criação da introdução da técnica de Priorização | Gabriel Sabanai, Paulo Henrique |
| 1.1 | 20/02/2022 | Adição dos requisitos coletados | Gabriel Sabanai, Paulo Henrique |
| 1.2 | 24/02/2022 | Padronização da página | Luiz Henrique, Victor Eduardo|
| 1.3 | 21/02/2022 | Revisão | Luiz Henrique |
| 1.4 | 04/03/2022 | Adição revisor | Luiz Henrique |
| 1.5 | 09/04/2022 | Padronização de Legendas e Metodologias | Victor Eduardo |
| 1.6 | 11/04/2022 | Adição de novos requisitos | João Victor |
| 2.0 | 19/04/2022 | Atualizando documento | Luiz Henrique |

*Tabela 1: versionamento*

## Introdução
<p align="justify">&emsp;&emsp;MoSCoW é uma técnica que ajuda na construção de priorização de atividades de um sistema, esta técnica é muito utilizada na engenharia de requisitos a fim de definir a importância/prioridade entre as partes interessadas dos requisitos levantados por um sistema/projeto.</p>

## Metodologia
<p align="justify">&emsp;&emsp;A metodologia MosCoW está muito ligada à metodologias àgeis por se tratar de uma técnica de priorização e faz o acrônimo de de 4 letras que representam 4 verbos, utilizamos esses verbos para a classificação e identificação das prioridades de cada atividade/requisito, sendo elas:</p>
- Must: Este verbo representa uma atividade que irá agregar muito favolr ao projeto finale que indispensável para a sua construção.
- Should: Este verbo representa as tarefas que são importantes porém não são fundamentais para a construção do software.
- Could: Este verbo representa as tarefas que não são tão muito importantes, não são fundamentais para o sistema e são desejáveis para o software, um exemplo seria, colocar a atividade na entrega final, após o MVP como plus na agregação de valor.</p>
- Would/Want/Won't: Estes verbos são para os requisitos menos críticos e que possuem um valor/retorno menor do que os outros para o software.
<p align="justify">&emsp;&emsp;Este artefato foi feito pelos integrantes Luiz e Gabriel através de uma reunião via Google Meet.</p>

## Resultados
### Proporção de Must, Should, Could e Would

| Prioridade | Quantidade de Requisitos |
|-|-|
|Must| 13 |
|Should| 6 |
|Could| 4 |
|Would| 1 |

*Tabela 2: Distribuição de requisitos*

### Requisitos e suas prioridades

| Identificação | Requisito | Prioridade |
|---|---|---|
| RF01 | O aplicativo deve permitir o cadastro/login do usuario | MUST |
| RF02 | O aplicativo deve aceitar utilizar a localização geográfica do usuario para que posso utilizar o aplicativo | MUST |
| RF03 | O aplicativo deve mostrar uma visualização do mapa e o ponto que o usuário se encontra para que tenha noção de onde está | SHOULD |
| RF04 | O aplicativo deve mostrar os pontos de bicicleta próximos ao usuário para que ele tenha noção de onde pegá-las | MUST |
| RF05 | O aplicativo deve mostrar a quantidade de bicicletas disponíveis em cada estação para que o usuário consiga saber se há bicicletas disponíveis  MUST |
| RF06 | O aplicativo deve permitir que o usuário faça a escolha de um plano de aluguel para que realizar o pagamento | MUST |
| RF07 |  O aplicativo deve permitir que o usuário consiga realizar o pagamento do plano de aluguel para que possa utilizar as bicicletas | MUST |
| RF08 | O aplicativo deve permitir que o usuário consiga ver seu histórico de viagens para que ele consiga ver o quanto já andou com o uso do aplicativo | SHOULD |
| RF09 | O aplicativo deve cobrar o usuário caso ele passe do tempo limite de uso da bicicleta para que tenha controle do uso e do plano do usuário | MUST |
| RF10 | O aplicativo deve avisar o usuário caso o seu tempo esteja acabando para que ele tenha noção do tempo de uso  | SHOULD |
| RF11 | O aplicativo deve conter premiações e recompensas gamificadas para que o usuário se sinta mais engajado em usá-lo  | WOULD |
| RNF12 | O aplicativo deve funcionar em dispositivos de tamanhos diferentes  | SHOULD |
| RNF13 | O sistema e as estações de bicicleta devem ter uma comunicação prática  | SHOULD |
| RNF14 | O aplicativo pode possuir um sistema gamificado que apresentará de maneira simples o progresso diário de km e calorias em corridas  | COULD |
| RF15 | O aplicativo pode possuir uma seção fomentando os pontos positivos de se utilizar as bicicletas no dia-a-dia, como melhorar a saúde, ser menos poluente e ser mais barato quando comparados a outros meios de locomoção  | COULD |
| RF16 | O aplicativo pode possuir uma função de bloquear um usuário de alugar bicicletas dado um certo número de infrações | COULD |
| RF17 | O usuário deverá poder acessar o aplicativo utilizando seu aparelho móvel| MUST |
| RF18 | O usuário deverá estar logado e possuir um plano para conseguir pegar uma bicicleta | MUST |
| RF19 | O usuário poderá desbloquear uma bicicleta utilizando um código do aplicativo a ser digitado em teclado localizado no posto de bicicleta | MUST |
| RF20 | O usuário poderá verificar a quantidade de vagas em cada ponto para devolver sua bicicleta | MUST |
| RF21 | O usuário poderá visualizar enquanto estiver em viagem o tempo que está sobre posse da bicicleta | SHOULD |
| RF22 | O usuário poderá utilizar um cupom de desconto caso possua, para diminuir o valor de seu plano | COULD |
| RF23 | O app deve permitir que usuário assinante consiga retirar uma bicicleta em uma estação | MUST |
| RF24 | O app deve permitir que usuário assinante consiga retirar uma bicicleta em uma estação | MUST |
| RF25 | O usuário poderá consultar informações sobre o sistema e como funciona sua utilização | SHOULD |
| RF26 | O usuário poderá entrar em contato com algum atendente para tirar dúvidas sobre o sistema |  SHOULD |
| RF27 | O usuário deve ser capaz de tirar dúvidas com a equipe de atendimento online e por telefone | SHOULD |
| RF28 | O usuário deve ser capaz de reportar problemas mecânicos com a bicicleta, problemas mecânicos com a estação e problemas no pagamento | SHOULD |

*Tabela 3: Tabela de requisitos priorizados*

## Referências
<p> Aprenda a usar a técnica MoSCoW nos projetos da sua agência!. Disponível em: https://rockcontent.com/br/blog/metodo-moscow/. Acesso em: 19 de feereiro de 2022.</p>
<p>Aplicativo Tembici. Disponível em: https://www.tembici.com.br. Acesso em: 19 de fevereiro de 2022.</p>