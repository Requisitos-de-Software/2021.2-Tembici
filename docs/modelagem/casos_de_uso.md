## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|-|-|
| 1.0 | 12/02 | Criação da seção Casos de Uso e template | Victor Eduardo |
| 1.1 | 25/02 | Adição dos casos de Uso 1 a 4 | Victor Eduardo |

*Tabela 1: Versionamento*

# Casos de Uso
## Introdução
<p align="justify">&emsp;&emsp;Também chamados de diagramas comportamentais, na notação da UML, os casos de uso são usados para descrever um conjunto de ações (uses cases - casos de uso) que um sistema ou um conjunto de sistemas (subject - sujeito) deve desempenhar em colaboração com um ou mais indivíduos externos ao sistema (actors - atores). Cada caso de uso deverá prover algum resultado observável e de valor para os atores ou outros interessados do sistema.

## Metodologia
<p align="justify">&emsp;&emsp;Para cada caso de uso é colocado um diagrama feito no site Lucidchart, e uma tabela descrevendo o diagrama, sendo composta de:

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------- |
| 1   | Versão                | Versão do caso de uso                                                                              |
| 2   | Autor                 | Nomes dos autores envolvidos nessa descrição de caso                                               |
| 3   | Descrição             | Breve descrição do caso de uso                                                                     |
| 4   | Atores                | Lista dos atores envolvidos no caso de uso                                                         |
| 5   | Pré-condições         | Todas as restrições que devem ser atendidas antes que o caso de uso possa iniciar sua execução     |
| 6   | Pós-condições         | Lista do estado em que o sistemas se encontrará imediatamente após a execução do cenário principal |
| 7   | Cenários Principais   | Descrição do cenário, ou fluxo, principal do caso de uso                                           |
| 8   | Cenários alternativos | Descrição dos cenários, ou fluxos, alternativos do caso de uso                                     |
| 9   | Cenários de exceção   | Descrição dos cenários, ou fluxos, de exceção do caso de uso                                       |

## Casos de Uso e Especificações
### 1 - Caso de Uso: Fazer cadastro
![Fazer Cadastro](../assets/modelagem/casos-de-uso/cadastro.png)
*Imagem 1: Diagrama 1*

| Item | Sigla | Definição |
| :-- | :-------------------- | :----------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                                        |
| 2   | Autor                 | Victor Eduardo                                                                             |
| 3   | Descrição             | O usuário deverá conseguir fazer cadastro de sua conta                                     |
| 4   | Atores                | Usuário                                                                                    |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto   |
| 6   | Pós-condições         | Usuário estar devidamente cadastrado no sistema com sua conta                              |
| 7   | Cenários Principais   | Usuário selecionar a opção fazer criar conta                                               |
| 8   | Cenários alternativos | Usuário abrir a aba lateral e selecionar a opção fazer cadastro                            |    
| 9   | Cenários de exceção   | Usuário preencher algum dos campos de forma inválida ou não preencher um campo obrigatório | 

*Tabela 2: Caso de Uso 1*

### 2 - Caso de Uso: Fazer login
![Fazer Login](../assets/modelagem/casos-de-uso/login.png)
*Imagem 2: Diagrama 2*

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                                                            |
| 2   | Autor                 | Victor Eduardo                                                                                                 |
| 3   | Descrição             | O usuário deverá conseguir logar em sua conta                                                                  |
| 4   | Atores                | Usuário                                                                                                        |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto                       |
| 6   | Pós-condições         | Usuário estar logado no sistema com sua conta                                                                  |
| 7   | Cenários Principais   | Usuário selecionar a opção fazer login                                                                         |
| 8   | Cenários alternativos | Usuário abrir a aba lateral e selecionar a opção fazer login                                                   |
| 9   | Cenários de exceção   | Usuário digitar a senha ou e-mail errados                                                                      | 

*Tabela 3: Caso de Uso 2*

### 2 - Caso de Uso: Assinar plano
![Assinar Plano](../assets/modelagem/casos-de-uso/planos_pagamento.png)
*Imagem 3: Diagrama 3*

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | Versão                | 1.0                                                                                                                                               |
| 2   | Autor                 | Victor Eduardo                                                                                                                                    |
| 3   | Descrição             | O usuário deverá conseguir assinar um dos planos disponíveis                                                                                      |
| 4   | Atores                | Usuário                                                                                                                                           |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet e estar logado em sua conta                                                                     |
| 6   | Pós-condições         | Usuário ter assinado um plano e poder retirar uma bicicleta                                                                                       |
| 7   | Cenários Principais   | Usuário selecionar a opção comprar plano, selecionar a cidade, a categoria do plano e o plano desejado, e realizar pagamento                      |
| 8   | Cenários alternativos | Usuário abrir a aba lateral, selecionar a opção comprar plano, selecionar a cidade, a categoria do plano e o plano desejado, e realizar pagamento |
| 9   | Cenários de exceção   | Pagamento ser recusado                                                                                                                            | 

*Tabela 4: Caso de Uso 3*

### 3 - Caso de Uso: Ver mapa com as estações
![Ver Mapa](../assets/modelagem/casos-de-uso/ver_mapa.png)
*Imagem 4: Diagrama 4*

| Item | Sigla | Definição |
| :-- | :-------------------- | :------------------------------------------------------------------------------------------------------------- |
| 1   | Versão                | 1.0                                                                                                            |
| 2   | Autor                 | Victor Eduardo                                                                                                 |
| 3   | Descrição             | O usuário deverá conseguir ver o mapa com as estações e bicicletas disponíveis em cada uma                     |
| 4   | Atores                | Usuário                                                                                                        |
| 5   | Pré-condições         | Dispositivo do usuário ter conexão com a internet, usuário estar com o aplicativo aberto                       |
| 6   | Pós-condições         | Usuário visualizar as bicicletas disponíveis em cada estação na localiação desejada                            |
| 7   | Cenários Principais   | Usuário navegar até a localização desejada                                                                     |
| 8   | Cenários alternativos | -                                                                                                              |
| 9   | Cenários de exceção   | Mapa estar indisponível                                                                                        |

*Tabela 5: Diagrama 4*

## Referências Bibliográficas
- POHL, Klaus; RUPP, Chris. Fundamentos da Engenharia de Requisitos. Massachusetts: Rockynoock, 2012. (Páginas 92 - 98)
- Tutorial de Caso de Uso UML, Lucidchart Português, Youtube, Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA&ab_channel=LucidchartPortugu%C3%AAs, Acesso em 25/02/2022
