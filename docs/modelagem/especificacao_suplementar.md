# Especificação Suplementar 
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 25/02/2022 | Criação do artefato | Victor Eduardo |
| 1.1 | 21/02/2022 | Atualização do artefato | Victor Eduardo |
| 1.2 | 28/02/2022 | Revisão | Livia Rodriges, Victor Eduardo |
| 1.3 | 04/03/2022 | Adição revisor | Luiz Henrique |

*Tabela 1: versionamento*

## Introdução
<p align="justify">&emsp;&emsp;Trata-se de um documento em linguagem natural, no qual são descritos os requisitos não funcionais [1]. Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design [2].</p>

## Metodologia
<p align="justify">&emsp;&emsp;Como metologia será usada a FURPS+, que é um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos, assim como representa atributos de Qualidade de Software, sendo ele parte do Rational Unified Process (RUP): Functionality (Funcionalidade), Usability (Usabilidade), Reliability (Confiabilidade), Performance (Desempenho), Supportability (Suportabilidade). O “+” do acrônimo engloba outros requisitos não-funcionais que devem ser lembrados [3].</p>

### Funcionalidade
&emsp;&emsp;Todas as funcionalidades do aplicativo Tembici podem ser encontradas na [lista de priorização](https://requisitos-de-software.github.io/2021.2-Tembici/elicitacao/priorizacao/moscow/) e nos [casos de usos](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/casos_de_uso/) do projeto.</p>

### Usabilidade
#### Facilidade de uso
- O usuário executa ações críticas em no máximo 7 clicks.
    - Levando em conta usuários já assinantes de algum dos planos do app. O número pode aumentar para usuários que não tiverem assinados algum dos planos ainda.   
- A interface gráfica possui cores que destacam para cada opção.
- A interfaze possui ícones intuitivos que direcionam o uso do usuário.
- Mapa disponível
    - Mostrando localização do usuário
    - Mostrando estações
    - Mostrando quantidade de bicicletas
    - Disponível sem login
#### Pequena curva de aprendizado
- Fluxos de trabalho simples e padronizados
- Usabilidade com pouca variação de uma versão para outra
#### Conhecimentos prévios
- A aplicação exigirá que o usuário saiba usar sistemas móveis Android ou iOS.
#### Feedbacks
- O usuário deve ter acesso a uma central de ajuda com
    - Perguntas feitas com frequência
    - A opção de abrir um chat com funcionário do suporte
        - Em tempo real
        - Assíncrono 
- O usuário deve ter acesso a guias de uso:
    - Simples
    - De fácil entendimento

### Confiabilidade
#### Disponibilidade
- Os servidores do aplicativo devem mantê-lo disponível o maior tempo possível enquanto instalado no celular do usuário. Se houver indisponibilidade por motivos de manutenção ou atualização, o usuário deve ser previamente avisado.
#### Segurança mínima no armazenamento de dados
- O aplicativo afirma estar em conformidade com o Artigo 19 N°4 da Constituição Política a República e Lei 19.628 do Chile, sobre Proteção de Dados de Caráter Pessoal.
#### Suporte a falhas
- No caso de falhas, o aplicativo deve dar segurança ao usuário de que a falha vai ser identificada e corrigida, gerando um feedback ao usuário e relatando que não haverão consequências negativas aos dados sensíveis do usuário.

### Desempenho
#### Rapidez de Resposta
- O tempo de resposta deverá ser o mínimo possível.
#### Acessos simultâneos
- A aplicação deve ter uma lógica de balanceamento de carga de requisições ao servidor, para ser capaz de atender acessos simultâneos de diferentes usuários, que estiverem logados em suas contas ou não.
#### Armazenamento
- O aplicativo precisa de 60MB(megabyte) de armazenamento em sistemas Android e 59MB em sistemas iOS.

### Suportabilidade
- O sistema do Tembici está disponível para plataforma Mobile. Funcionando nos sistemas operacionais mobile Android, nas versões 5.0 ou superior, e iOS nas versões iOS 12.0 ou posterior.

### Restrições de Design
#### Suporte a Idiomas
- O sistema fornece uma grande variedade de línguas, e a linguagem do app varia de acordo com a linguagem utilizada no aparelho
#### Conteudo
- O sistema deve disponibilizar a visuzalização dos locais das estações bem como a quantidade de bicicletas em cada em um mapa

### Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line
#### Sessão de Ajuda
- O aplicativo possui um botão chamado "Ajuda", localizado na aba lateral. Ele possui um conjunto FAQ - Frequently Asked Questions -, ou seja, um conjunto de perguntas frequentes com suas soluções, para cada cidade a qual o app atua, além da opcão de abri um chat para solucionar a dúvida.

#### Demais informações
- No site do App é possível achar diversas outras informações sobre o app, e a empresa criadora desse. 

### Interfaces
#### Interfaces de Usuário
- O usuário utilizará as versões do aplicativo disponíveis nas lojas mobile para visualizar e utilizar sua interface.
#### Interface de Hardware
- O hardware deve ser capaz de disponibilizar a localização atual para o usuário e ter conexão com a internet para o aplicativo gerar o trajeto até uma estação, a partir da localização atual do usuário.
- O hardware deve ter conexão com a internet para mostrar ao usuário as estações e quantidade de bicicletas em cada uma.
#### Interface de Software
- A interface do aplicativo é desenvolvida para atender as plataformas Mobile, que utilizam Android ou iOS. 

### Requisitos de Licenciamento
#### Termos de Uso
- O aplicativo apresenta seus termos de uso para que o usuário concorde em utilizar o aplicativo e suas informações dentro dos limites apresentados.

### Observações Legais, de Copyright e Outras
- Os usuários do software estarão sujeitos à lei de direitos autorais. Assim, o software será desenvolvido para um aplicativo de aluguel de bicicletas, não sendo autorizada a cópia de trechos do programa para utilizações diversas.

## Referências 
<p>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. 2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 26 de fevereiro de 2022.</p>

<p>GOIS, Samily Rocha; SOBRINHO, Francisco Luiz. PHP SOFTWARE COMPANY. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 26 de fevereiro de 2022.</p>

<p> FURPS+. QualidadeBR, 10 de julho de 2008. Disponível em: <https://qualidadebr.wordpress.com/2008/07/10/furps/#:~:text=FURPS%2B%20%C3%A9%20um%20sistema%20para,Rational%20Unified%20Process%20(RUP)%3A>. Acesso em: 26 de fevereiro de 2022.</p>

<p> Aplicativo Tembici. Disponível em: https://www.tembici.com.br. Acesso em: 26 de fevereiro de 2022. </p>