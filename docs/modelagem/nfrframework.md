# NFR Framework 
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 28/02/2022 | Criação do artefato | Victor Eduardo |
| 1.1 | 03/03/2022 | Revisão e padronização | Luiz Henrique |

*Tabela 1: versionamento*

## Introdução
<p align="justify">&emsp;&emsp;Este framework é utilizado neste trabalho para representar os Requisitos Não-Funcionais presentes no Catálogo NFR4Es, onde estes Requisitos Não-Funcionais serão expressados através de um grafo SIG. O NFR framework criado por (CHUNG et al., 2000), foi adotado por propor uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornecer uma rica representação para expressar esses requisitos, além de suas relações e correlações.</p>

## Metodologia
<p align="justify">&emsp;&emsp;Essa técnica de modelagem trata de decompor os requisitos não funcionais a niveis operacionais, facilitando a compreensão, priorização e garantindo que as expectativas dos stakeholders sejam atendidas. Cada tema de diagrama NFR elaborado nesse documento foi retirado dos requisitos não funcionais levantados na <a href="https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/especificacao_suplementar/">especificação suplementar</a>.</p>
Os tipos de contribuição utilizados nos diagramas foram:

- AND: Caso os softgoals descendentes sejam satisfeitos, serão também os ascendentes.
- OR: Caso algum softgoal descendentes seja satisfeitos, será também os ascendente.
- MAKE (++): Caso o softgoal descendente for suficientemente satisfeito, será também o ascendente, porém, a contribuição é fornecida como suficientemente positiva concebida no nível mais alto de satisfação.
- HELP (+): Caso o softgoal descendente seja parcialmente satisfeito, será parcialmente satisfeito o ascendente.
- HURT (-): Caso o softgoal descendente seja satisfeito, o softgoal ascendente será parcialmente negado.

Os rótulos utilizados foram:

| Rótulo | Descrição |
|   -    |     -     |
| ![Satisfeito](../assets/modelagem/nfr-framework/rotulos/Untitled.png){width="100"} | <br>Satisfeito | {justify-self="center"}
| ![Negado](../assets/modelagem/nfr-framework/rotulos/Untitledn.png){width="100"} | <br>Negado |
| ![Parcialmente Satisfeito](../assets/modelagem/nfr-framework/rotulos/parcialmentesatisfeito.png) | <br>Parcialmente Satisfeito |
| ![Parcialmente Negado](../assets/modelagem/nfr-framework/rotulos/parcialmentenegado.png) | <br>Parcialmente Negado |

*Tabela 2: Rótulos*

## Resultados

### Gráfico de Interdependência de Softgoal (SIG)
#### Usabilidade 
![NFR Usabilidade](../assets/modelagem/nfr-framework/usabilidade/usabilidade.jpg)<br>
*Imagem 1: NFR Usabilidade*

#### Usabilidade Propagação
![NFR Usabilidade Propagação](../assets/modelagem/nfr-framework/usabilidade/usabilidadeprop.jpg)<br>
*Imagem 2: NFR Usabilidade Propagação*

#### Confiabilidade
![NFR Confiabilidade](../assets/modelagem/nfr-framework/confiabilidade/confiabilidade.jpg)<br>
*Imagem 3: NFR Confiabilidade*

#### Confiabilidade Propagação
![NFR Confiabilidade Propagação](../assets/modelagem/nfr-framework/confiabilidade/confiabilidadeprop.jpg)<br>
*Imagem 4: NFR Confiabilidade Propagação*

#### Desempenho
![NFR Desempenho](../assets/modelagem/nfr-framework/desempenho/desempenho.jpg)<br>
*Imagem 5: NFR Desempenho*

#### Desempenho Propagação
![NFR Desempenho Propagação](../assets/modelagem/nfr-framework/desempenho/desempenhoprop.jpg)<br>
*Imagem 6: NFR Desempenho Propagação*

#### Suportabilidade
![NFR Suportabilidade](../assets/modelagem/nfr-framework/suportabilidade/suportabilidade.jpg)<br>
*Imagem 7: NFR Suportabilidade*

#### Suportabilidade Propagação
![NFR Suportabilidade Propagação](../assets/modelagem/nfr-framework/suportabilidade/suportabilidadeprop.jpg)<br>
*Imagem 8: NFR Suportabilidade Propagação* 

## Referências 
- SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Universidade Federal de Pernambuco, Recife, 2019. 2.4 - NFR Framework. Acesso em 01 de Março de 2022.