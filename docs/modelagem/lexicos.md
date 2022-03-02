# Léxicos

## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 24/02 | Abertura do documento Lexico | Paulo Henrique e Luiz Henrique |
| 1.1 | 27/02 | Criação e Adição Lexicos Verbos | Luiz Henrique Fernandes |
| 1.2 | 27/02 | Adição do léxicos Objetos | Paulo Henrique |
| 1.3 | 28/02 | Adição introdução e referências | Luiz Henrique Fernandes |
| 1.4 | 02/03 | Adição da tabela de estados | Luiz Henrique e Paulo Henrique |



*Tabela 1: Versionamento da modelagem*

## Introdução

<p style="text-align: justify;"> O Léxico é uma técnica de modelagem que permite a descrição de símbolos de uma determinada linguagem, o mesmo se assemelha a um dicionário e auxiliará na identificação de palavras ou frases peculiares relativas ao meio social do projeto. Estes símbolos são descritos considerando dois principais aspectos, noção e impacto, onde noção representa o significado do símbolo e impacto descreve o efeito do símbolo na aplicação ou o efeito de algo na aplicação sobre o símbolo. </p>

*Tabela 2: Introdução sobre o que é o Léxicos*

## Metodologia
<p style="text-align: justify;">Para representar os léxicos, foram definidas tabelas contendo o seguinte formato:</p>

|LCXX|**Nome do léxico**|
|:----:|:--------------------:|
|**Sinônimos**|Sinônimos do léxico|
|**Noção**|Explicação ou noção do léxico|
|**Impacto**|Ocorrência ou impacto do léxico na aplicação|

|Legenda||
|:----:|:--------------------:|
|**L**|Léxico|
|**C**|Classificação (Estado(E),Verbo(V) ou Ofbjeto(O))|
|**XX**|Numeração|

*Tabela 3: Metodologia do léxicos*

## Resultados

### Léxicos

#### Objetos 

|LO01|**Artefato**|
|---|------------------|
|**Sinônimos**|Atividade, "Task", Artifício|
|**Noção**| Atividade que será entregue para incremento da documentação ao final da sprint |
|**Impacto**| O artefato irá acrescentar no desenvolvimento da documentação a fim enterdemos melhor sobre o aplicativo |

|LO02|**Back-end**|
|---|------------------|
|**Sinônimos**| "Por-trás", "Parte de trás" |
|**Noção**| Programa que roda por trás do software, fica entre o usuário e o que possível ser visto por ele |
|**Impacto**| Ele conectará o usuário com o banco de dados, isso fará com que usuário possa consumir os seus própios dados e os dados sobre as bicicletas |

|LO03|**Clone**|
|---|------------------|
|**Sinônimos**| Cópia |
|**Noção**| Cópia do código da docuementação que está guardado no repositório |
|**Impacto**| Com o clone da documentação será possível versionar o projeto para que o incremento dos artefatos sejam entregue mais rápido e com maior eficiência |

|LO04|**Usuário**|
|---|------------------|
|**Sinônimos**|Cliente|
|**Noção**|Pessoa que irá usar o aplicativo tembici|
|**Impacto**|O usuário pederá pagar o plano que a plataforma oferece para que possa usufruir do serviço e consequentemente andar de bicicleta pela cidade|

|LO05|**Requisito**|
|---|------------------|
|**Sinônimos**|Exigência, Premissas|
|**Noção**| Premissas que irão ser usadas para desenvolver a melhor aplicação possível |
|**Impacto**| Premissas essas que irão impactar e agregar valor no produto final para o cliente |

|LO06|**Repositório**|
|---|------------------|
|**Sinônimos**|Depósito, Armazenamento|
|**Noção**|Lugar aonde guardamos de forma online todos as nossas documentações|
|**Impacto**| Pessoas que precisarem da documentação para entender melhor o que o software oferece, poderão acessar o repositório do projeto a fim de conhcer um pouco mais sobre o aplicativo |

|LO07|**Software**|
|---|------------------|
|**Sinônimos**|Programa, Aplicativo, App|
|**Noção**|Referência para algum aplicativo, muitas das vezes usadas no projeto para fazer menção ao Tembici|
|**Impacto**| O usuário poderá acessar o software e usar o aplicativo para olhar o local mais próximo que tenha bicleta disponível |

|LO08|**Sprint**|
|---|------------------|
|**Sinônimos**| Disparada, Corrida |
|**Noção**| Tempo determinado pelo time do projeto para a execução e entrega de um ou mais artefatos |
|**Impacto**| A sprint trará impacto significativo para a entrega da documentação dos requisitos, com incrementos graduais, em um curto prazo |

|LO09|**Thumbnail**|
|---|------------------|
|**Sinônimos**| Miniatura |
|**Noção**| Imagem que represente algo que será assistido |
|**Impacto**| A thumbnail será útil para pré-visualização as apresentações da dusciplina |

*Tabela 4: Léxicos Objetos*

#### Verbos

| LV01 | **Alugar bicicleta** |
| ------ | ---- | 
| **Sinônimos** | Retirar bicicleta, Desbloquear bicicleta |
| **Noção** | O usuário irá, através do aluguel da bicicleta, poder utiliza a bicicleta escolhida para se locomover |
| **Impacto**| O desbloqueará para uso uma bicileta |

| LV02 | **Aplicar cupom** |
| ------ | ---- | 
| **Sinônimos** | Utilizar desconto, Aplicar desconto |
| **Noção** | O usuário poderá, caso possua um cupom, ter descontos nas compras dentro do app |
| **Impacto**| O usuário terá variados descontos ao realizar o pagamento de uma compra |

| LV03 | **Assinar plano** |
| ------ | ---- | 
| **Sinônimos** | Contratar plano, Comprar Plano, Escolher plano |
| **Noção** | O usuário poderá assinar um plano no app para receber benefícios a mais |
| **Impacto**| O usuário com plano tem direito a alguns beneficos a mais nas funcionalidade do aplicativo |

| LV04 | **Cadastrar cartão** |
| ------ | ---- | 
| **Sinônimos** |<center> --- </center> |
| **Noção** | O usuário irá, caso queira realizar uma compra, cadastrar um cartão onde será comprado o pagamento |
| **Impacto**| O usuário será capaz de efutar uma compra utilizando o cartão como seu meio de pagamento |

| LV05 | **Cadastrar usuário** |
| ------ | ---- | 
| **Sinônimos** | Realizar Cadastro |
| **Noção** | O usuário poderá se cadastrar no app e receber alguns benefícios |
| **Impacto**| 	O usuário cadastrado tem direito a algumas funcionalidades a mais |

| LV06 | **Cancelar plano** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá cancelar um plano contrato seguindo as diretris estipuladas na contratação do plano |
| **Impacto**| O usuário após cancelar o plano perderá os bebficios do mesmo e estará sujeito a multas estipuladas nas diretrizes |

| LV07 | **Cobrar multa** |
| ------ | ---- | 
| **Sinônimos** | Aplicar multa, Ter custos adicionais |
| **Noção** | O usuário estará sujeito a multas caso infrinja algum acordo estipulado nas compras dentro da plataforma |
| **Impacto**|  |

| LV08 | **Começar a pedalar** |
| ------ | ---- | 
| **Sinônimos** | Realizar a primeira viagem |
| **Noção** | O usuário irá realizar sua primeira viagem no aplicativo |
| **Impacto**| O usuário após realizar sua primeira viagem poderá visualizar seu historico de viagens|

| LV09 | **Consultar Histórico de viagens** |
| ------ | ---- | 
| **Sinônimos** | Acessar Histórico de viagens, ver minhas viagens  |
| **Noção** | O usuário poderá consultar seu historico de viagens contendo detalhes das viagens realizadas pelo usuário |
| **Impacto**| O usuário poderá obter metricas quanto a suas viagens |

| LV10 | **Consultar bicicletas disponiveis** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá consultar no app em que postos possuem bicicletas disponiveis |
| **Impacto**| O usuário consiguirá encontrar bicicletas do app para desbloquear |

| LV11 | **Consultar vagas disponiveis** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá consultar no app em que postos há vagas disponiveis para a devolução de uma bicicleta |
| **Impacto**| O usuário consiguirá encontrar vagas para devolver a bicicleta após a viagem |

| LV12 | **Devolver bicicleta** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário irá, após uma viagem, devolver um bicicleta que alugou |
| **Impacto**| Após usuário devolver a bicicleta a mesma ficará disponivel para mais pessoas utilizarem |

| LV13 | **Iniciar rota** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá utilizar o app para guiar sua rota até o posto de retirada desejado |
| **Impacto**| O usuário consiguirá encontrar o posto para realizar o desbloqueo e/o devolução da uma bicicleta|

| LV14 | **Gerar código** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá, para realizar o desbloqueio de uma bicleta, utilizar um código gereado em seu app que será digitado no posto de retirada |
| **Impacto**| O usuário consiguirá, utilizando código, desbloquear uma bicicleta para realizar uma viagem |

| LV15 | **Ler QR Code** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O usuário poderá, para realizar o desbloqueio de uma bicleta, realizar a leitura um código QR Code locaçlizado no posto de retirada |
| **Impacto**| O usuário consiguirá, lendo o QR Code, desbloquear uma bicicleta para realizar uma viagem |


| LV16 | **Logar no sistema** |
| ------ | ---- | 
| **Sinônimos** | Acessar sistema |
| **Noção** | O usuário já cadastrado, utilizando suas credenciais, poderá logar no sistema |
| **Impacto**| Ao logar, o usuário poderá ter acesso às informações sobre sua conta, bem como os benefícios de um usuário cadastrado |

| LV17 | **Realizar pagamento** |
| ------ | ---- | 
| **Sinônimos** | Efetuar pagamento |
| **Noção** | O usuário irá, efetivar o processo de compra de um item, realizando o pagamento do valor correspondente ao mesmo  |
| **Impacto**| O pagará e poderá disfrutar do item comprado |

*Tabela 5: Léxicos Verbos*

#### Estados

| LE01 | **Bicicleta Disponível** |
| ------ | ---- | 
| **Sinônimos** | A bicicleta não está sendo usada |
| **Noção** | A bicicleta estar disponível significa que ela poderá ser usada pelo usuário |
| **Impacto**| O usuário poderá pegar a bicleta que estiver diponível no posto de bicletas para poder andar pela cidade |

| LE02 | **Bicicleta Indisponível** |
| ------ | ---- | 
| **Sinônimos** | A bicicleta está sendo usada |
| **Noção** | A bicicleta estar indisponível significa que ela não está sendo usada por um usuárío |
| **Impacto**| O usuário não poderá pegar as bicletas que não estiverem diponíveis, dendo que esperar sua devolução no posto de bicletas para poder utiliza-la |

| LE03 | **Não cadastrado** |
| ------ | ---- | 
| **Sinônimos** | Usuário sem cadastro |
| **Noção** | Estado em que o usuário ainda não realizou o cadastro no sistema |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não possuir credenciais para se logar no sistema |

| LE04 | **Não logado** |
| ------ | ---- | 
| **Sinônimos** | Usuário deslogado |
| **Noção** | Estado em que o usuário ainda não realizou o login no sistema |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não estar com os beficios realacionados a um usuário logado |

| LE05 | **O Tempo está acabando** |
| ------ | ---- | 
| **Sinônimos** | O Tempo do aluguel está acabando |
| **Noção** | O Tempo está acabando significa que o tempo que previsto pelo aplicaticativo está chegando ao fim e você deverá procurar o posto de bicicletas mais próximo |
| **Impacto**| O usuário pode estar com o tempo de uso da bicicleta acabando e assim, poderá deveolve-lá ao posto mais próximo ou poderá continuar usando, porém terá que pagar uma taxa pelo tempo excedidio |

| LE06 | **O Tempo acabou** |
| ------ | ---- | 
| **Sinônimos** | O Tempo do aluguel chegou ao fim |
| **Noção** | O Tempo acabou significa que tempo de aluguel da bicicleta chegou ao fim |
| **Impacto**| O usuário poderá ter o tempo acabado conforme a escolha do plano/aluguel escolhido no aplicativo |

| LE07 | **Planos disponíveis** |
| ------ | ---- | 
| **Sinônimos** | Opções de plano |
| **Noção** | Opções de planos disponiveis para a contratação, definidas pela localização do usuário |
| **Impacto**| Os planos disponiveis limitam as opções de escolha de plano do usuário, podendo apenas contratar os planos disponiveis para a cidade selecionada |

| LE08 | **Sem plano** |
| ------ | ---- | 
| **Sinônimos** | Não possui plano |
| **Noção** | Estado em que o usuário não contratou um plano |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não possuir os beneficios realacionados a um plano |


*Tabela 6: Léxicos Estados*

## Referências

<p>Wiki Requisitos - Lexicos - Ingresso.com. Disponível em: https://requisitos-de-software.github.io/2021.1-Ingresso.com/modelagem/lexicos/. Acesso em: 25 de fevereiro de 2022.</p>
