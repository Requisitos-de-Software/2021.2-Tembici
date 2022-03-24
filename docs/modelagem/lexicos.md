# Léxicos

## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 24/02 | Abertura do documento Lexico | Paulo Henrique e Luiz Henrique |
| 1.1 | 27/02 | Criação e Adição Lexicos Verbos | Luiz Henrique Fernandes |
| 1.2 | 27/02 | Adição do léxicos Objetos | Paulo Henrique |
| 1.3 | 28/02 | Adição introdução e referências | Luiz Henrique Fernandes |
| 1.4 | 02/03 | Adição da tabela de estados | Luiz Henrique e Paulo Henrique |
| 1.5 | 02/03 | Adição links para rastreabilidade | Luiz Henrique e Paulo Henrique |
| 1.6 | 21/02 | Revisão | Victor Eduardo, Luiz Henrique, Gabriel Sabanai |
| 1.7 | 04/03 | Adição revisor | Luiz Henrique |
| 2.0 | 11/03 | Adição novos Léxicos | Luiz Henrique |
| 3.0 | 22/03 | Correção pós verificação | Paulo Henrique |

*Tabela 1: Versionamento da modelagem*

## Introdução

<p style="text-align: justify;"> O Léxico é uma técnica de modelagem que permite a descrição de símbolos de uma determinada linguagem, o mesmo se assemelha a um dicionário e auxiliará na identificação de palavras ou frases peculiares relativas ao meio social do projeto. Estes símbolos são descritos considerando dois principais aspectos, noção e impacto, onde noção representa o significado do símbolo e impacto descreve o efeito do símbolo na aplicação ou o efeito de algo na aplicação sobre o símbolo. [1]</p> 

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

<div id="artefato"></div>

|LO01|**Artefato**|
|---|------------------|
|**Sinônimos**|Atividade, "Task", Artifício|
|**Noção**| Atividade que será entregue para incremento da documentação ao final da <a href="#sprint" > sprint </a> |
|**Impacto**| O <a href="#artefato" > artefato </a> irá acrescentar no desenvolvimento da documentação a fim de enterdemos melhor sobre o aplicativo |

<div id="back-end"></div>

|LO02|**Back-end**|
|---|------------------|
|**Sinônimos**| "Por-trás", "Parte de trás" |
|**Noção**| Programa que roda por trás do software, fica entre o que é possível ser visto pelo<a href="#usuario" > usuário </a> e aonde armazena os dados da plataforma |
|**Impacto**| Ele conectará o usuário com o banco de dados, isso fará com que usuário possa consumir os seus própios dados e os dados sobre as bicicletas |

<div id="clone"></div>

|LO03|**Clone**|
|---|------------------|
|**Sinônimos**| Cópia |
|**Noção**| Cópia do código da docuementação que está guardado no <a href="#repositório" > repositório</a> |
|**Impacto**| Com o <a href="#clone" > clone </a> da documentação será possível versionar o projeto para que o incremento dos <a href="#artefato" > artefatos </a>  sejam entregue mais rápido e com maior eficiência |

<div id="estacao"></div>

|LO03|**Estação**|
|---|------------------|
|**Sinônimos**| Posto, Estação de <a href="#devolver-bicicleta" >devolução </a>, Estação de bicicletas |
|**Noção**| Local onde é realizado o aluguel e devolução das biciletas |
|**Impacto**| O <a href="#estacao" > posto </a> representa fisicamente o serviço prestado pelo aplicativo, é o local responsavel pela <a href="#devolver-bicicleta" >devolução </a> e <a href="#plano"> aluguel</a> das blicletas |

<div id="usuario"></div>

|LO04|**Usuário**|
|---|------------------|
|**Sinônimos**|Cliente|
|**Noção**|Pessoa que irá usar o aplicativo tembici|
|**Impacto**|O <a href="#usuario" > usuário </a> pederá pagar o<a href="#plano"> plano</a> que a plataforma oferece para que possa usufruir do serviço e consequentemente andar de bicicleta pela cidade| 

<div id="requisito"></div>

|LO05|**Requisito**|
|---|------------------|
|**Sinônimos**|Exigência, Premissas|
|**Noção**| Premissas que irão ser usadas para desenvolver a melhor aplicação possível |
|**Impacto**| Premissas essas que irão impactar e agregar valor no produto final para o cliente |

<div id="repositório"></div>

|LO06|**Repositório**|
|---|------------------|
|**Sinônimos**|Depósito, Armazenamento|
|**Noção**|Lugar aonde guardamos de forma online todos as nossas documentações|
|**Impacto**| Pessoas que precisarem da documentação para entender melhor o que o <a href="#tembici" > software </a> oferece, poderão acessar o repositório do projeto a fim de conhecer um pouco mais sobre o aplicativo |

<div id="software"></div>

|LO07|**Software**|
|---|------------------|
|**Sinônimos**|Programa, Aplicativo, App|
|**Noção**|Referência para algum aplicativo, muitas das vezes usadas no projeto para fazer menção ao Tembici|
|**Impacto**| O <a href="#usuario" > usuário </a> poderá acessar o software e usar o aplicativo para olhar o local mais próximo que tenha bicleta disponível |

<div id="sprint"></div>

|LO08|**Sprint**|
|---|------------------|
|**Sinônimos**| Disparada, Corrida |
|**Noção**| Tempo determinado pelo time do projeto para a execução e entrega de um ou mais <a href="#artefato" > artefatos </a> |
|**Impacto**| A sprint trará impacto significativo para a entrega da documentação dos <a href="#requisito" > requisitos </a>, com incrementos graduais, em um curto prazo |

<div id="plano"></div>

|LO08|**Plano**|
|---|------------------|
|**Sinônimos**| Aluguel, assinatura, bilhete |
|**Noção**| Modalidades de serviço que os <a href="#usuario" > usuários </a>s podem contratar, podendo variar o contrato dependendo da localização do usuário |
|**Impacto**| O<a href="#plano"> plano</a> escolhido libera uma categoria de benefício para o Usuário, podendo variar o preço de acordo com o plano escolhido |


<div id="Tembici"></div>

|LO09|**Tembici**|
|---|------------------|
|**Sinônimos**| App, Aplicativo, Software |
|**Noção**| Aplicativo de aluguel de bicicletas sobre o qual a documentação do projeto se trata |
|**Impacto**| A aplicação é o serne do serviço ofertado pela empresa. Por meio do aplicativo é realizado, dentre outras coisas, o aluguel e devolução da bicicleta |

*Tabela 4: Léxicos Objetos*

<div id="thumbnail"></div>

|LO10|**Thumbnail**|
|---|------------------|
|**Sinônimos**| Miniatura |
|**Noção**| Imagem que represente algo que será assistido |
|**Impacto**| A thumbnail será útil para pré-visualização as apresentações da dusciplina |

*Tabela 4: Léxicos Objetos*

#### Verbos

<div id="alugar"></div>

| LV01 | **Alugar bicicleta** |
| ------ | ---- | 
| **Sinônimos** | Retirar bicicleta, Desbloquear bicicleta |
| **Noção** | O <a href="#usuario" > usuário </a> irá, através do aluguel da bicicleta, poder utilizar a bicicleta escolhida para se locomover |
| **Impacto**| Após um cliente alugar uma bicicleta ele desbloqueará para uso |

<div id="aplicar"></div>

| LV02 | **Aplicar cupom** |
| ------ | ---- | 
| **Sinônimos** | Utilizar desconto, Aplicar desconto |
| **Noção** | O <a href="#usuario" > usuário </a> poderá, caso possua um cupom, ter descontos nas compras dentro do app |
| **Impacto**| O usuário terá variados descontos ao realizar o pagamento de uma compra |

<div id="assinar"></div>

| LV03 | **Assinar plano** |
| ------ | ---- | 
| **Sinônimos** | Contratar<a href="#plano"> plano</a>, Comprar<a href="#plano"> plano</a>, Escolher<a href="#plano"> plano</a> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá assinar um plano no app para receber benefícios a mais |
| **Impacto**| O usuário com plano tem direito a alguns beneficos a mais nas funcionalidade do aplicativo |

<div id="cadastrar-cartao"></div>

| LV04 | **Cadastrar cartão** |
| ------ | ---- | 
| **Sinônimos** |<center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> irá, caso queira realizar uma compra, cadastrar um cartão onde será comprado o pagamento |
| **Impacto**| O usuário será capaz de efutar uma compra utilizando o cartão como seu meio de pagamento |

<div id="cadastrar-usuario"></div>

| LV05 | **Cadastrar usuário** |
| ------ | ---- | 
| **Sinônimos** | Realizar Cadastro, Registrar, Criar Conta |
| **Noção** | O <a href="#usuario" > usuário </a> poderá se cadastrar no aplicativo e receber alguns benefícios |
| **Impacto**| 	O usuário cadastrado tem direito a algumas funcionalidades que entregues a qualquer cliente |

<div id="cancelar"></div>

| LV06 | **Cancelar plano** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá cancelar um<a href="#plano"> plano</a> contrato seguindo as diretris estipuladas na contratação do<a href="#plano"> plano</a> |
| **Impacto**| O usuário após cancelar o<a href="#plano"> plano</a> perderá os bebficios do mesmo e estará sujeito a multas estipuladas nas diretrizes |

<div id="cobrar"></div>

| LV07 | **Cobrar multa** |
| ------ | ---- | 
| **Sinônimos** | Aplicar multa, Ter custos adicionais |
| **Noção** | O <a href="#usuario" > usuário </a> estará sujeito a multas caso infrinja algum acordo estipulado nas compras dentro da plataforma |
| **Impacto**|  |

<div id="começar"></div>

| LV08 | **Começar a pedalar** |
| ------ | ---- | 
| **Sinônimos** | Realizar a primeira viagem |
| **Noção** | O <a href="#usuario" > usuário </a> irá realizar sua primeira viagem no aplicativo |
| **Impacto**| O usuário após realizar sua primeira viagem poderá visualizar seu historico de viagens|

<div id="consultar-historico"></div>

| LV09 | **Consultar Histórico de viagens** |
| ------ | ---- | 
| **Sinônimos** | Acessar Histórico de viagens, ver minhas viagens  |
| **Noção** | O <a href="#usuario" > usuário </a> poderá consultar seu historico de viagens contendo detalhes das viagens realizadas pelo usuário |
| **Impacto**| O usuário poderá obter métricas sobre as suas viagens |

<div id="consultar-bicicleta"></div>

| LV10 | **Consultar bicicletas disponiveis** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá consultar no app em que <a href="#estacao" > postos </a> possuem bicicletas disponiveis |
| **Impacto**| O usuário consiguirá encontrar bicicletas do app para desbloquear |

<div id="cadastrar-vagas"></div>

| LV11 | **Consultar vagas disponiveis** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá consultar no app em que <a href="#estacao" > postos </a> há vagas disponiveis para a <a href="#devolver-bicicleta" >devolução </a> de uma bicicleta |
| **Impacto**| O usuário consiguirá encontrar vagas para <a href="#devolver-bicicleta" >devolver a bicicleta </a> após a viagem |

<div id="devolver-bicicleta"></div>

| LV12 | **Devolver bicicleta** |
| ------ | ---- | 
| **Sinônimos** | Devolução, Devolver a bicicleta |
| **Noção** | O <a href="#usuario" > usuário </a> irá, após uma viagem, devolver um bicicleta que alugou |
| **Impacto**| Após o usuário devolver a bicicleta o mesma ficará disponível para mais pessoas utilizarem |

<div id="iniciar-rota"></div>

| LV13 | **Iniciar rota** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá utilizar o aplicativo para guiar sua rota até a <a href="#estacao" > estação </a>de retirada desejado |
| **Impacto**| O usuário consiguirá encontrar o <a href="#estacao" > posto </a> para realizar o desbloqueo e/a <a href="#devolver-bicicleta" >devolução </a> da uma bicicleta|

<div id="gerar-codigo"></div>

| LV14 | **Gerar código** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá, para realizar o desbloqueio de uma bicleta, utilizar um código gereado em seu app que será digitado no <a href="#estacao" > posto </a> de retirada |
| **Impacto**| O usuário consiguirá, utilizando código, desbloquear uma bicicleta para realizar uma viagem |

<div id="qr-code"></div>

| LV15 | **Ler QR Code** |
| ------ | ---- | 
| **Sinônimos** | <center> --- </center> |
| **Noção** | O <a href="#usuario" > usuário </a> poderá, realizar o desbloqueio de uma bicleta e realizar a leitura de um código no QR Code localizado no <a href="#estacao" > posto </a> de retirada |
| **Impacto**| O <a href="#usuario" > usuário </a> consiguirá, lendo o QR Code, desbloquear uma bicicleta para realizar uma viagem |

<div id="logar"></div>

| LV16 | **Logar no sistema** |
| ------ | ---- | 
| **Sinônimos** | Acessar sistema, logado |
| **Noção** | O <a href="#usuario" > usuário </a> já cadastrado, utilizando suas credenciais, poderá<a href="#logar"> logar</a> no sistema |
| **Impacto**| Ao<a href="#logar"> logar</a>, o usuário poderá ter acesso às informações sobre sua conta, bem como os benefícios de um usuário cadastrado |

<div id="realizar-pagamento"></div>

| LV17 | **Realizar pagamento** |
| ------ | ---- | 
| **Sinônimos** | Efetuar pagamento |
| **Noção** | O <a href="#usuario" > usuário </a> irá, efetivar o processo de compra de plano ou diária, realizando o pagamento do valor correspondente ao mesmo  |
| **Impacto**| O usuário pagará a diária ou plano e poderá disfrutar dos beneficíos proposto por aquela diária ou plano |

*Tabela 5: Léxicos Verbos*

#### Estados

<div id="bicleta-disponivel"></div>

| LE01 | **Bicicleta Disponível** |
| ------ | ---- | 
| **Sinônimos** | A bicicleta não está sendo usada |
| **Noção** | A bicicleta estar disponível significa que ela poderá ser usada pelo <a href="#usuario" > usuário </a> |
| **Impacto**| O usuário poderá pegar a bicleta que estiver diponível no <a href="#estacao" > posto </a> de bicletas para poder andar pela cidade |

<div id="bicleta-indisponivel"></div>

| LE02 | **Bicicleta Indisponível** |
| ------ | ---- | 
| **Sinônimos** | A bicicleta está sendo usada |
| **Noção** | A bicicleta estar indisponível significa que ela não está sendo usada por um usuárío |
| **Impacto**| O <a href="#usuario" > usuário </a> não poderá pegar as bicletas que não estiverem diponíveis, tendo que esperar sua <a href="#devolver-bicicleta" >devolução </a> no <a href="#estacao" > posto </a> de bicletas para poder utiliza-lá |

<div id="nao-cadastrado"></div>

| LE03 | **Não cadastrado** |
| ------ | ---- | 
| **Sinônimos** | Usuário sem <a href="#cadastrar-usuario" > cadastro </a> |
| **Noção** | Estado em que o <a href="#usuario" > usuário </a> ainda não realizou o cadastro no sistema |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não possuir credenciais para se<a href="#logar"> logar</a> no sistema |

<div id="nao-logado"></div>

| LE04 | **Não logado** |
| ------ | ---- | 
| **Sinônimos** | Usuário deslogado |
| **Noção** | Estado em que o <a href="#usuario" > usuário </a> ainda não realizou o login no sistema |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não estar com os beficios realacionados a um usuário<a href="#logar"> logado</a> |

<div id="tempo-acabando"></div>

| LE05 | **O Tempo está acabando** |
| ------ | ---- | 
| **Sinônimos** | O Tempo do aluguel está acabando |
| **Noção** | O Tempo está acabando significa que o tempo que previsto pelo aplicaticativo está chegando ao fim e você deverá procurar o <a href="#estacao" > posto </a> de bicicletas mais próximo |
| **Impacto**| O <a href="#usuario" > usuário </a> pode estar com o tempo de uso da bicicleta acabando e assim, poderá deveolve-lá ao <a href="#estacao" > posto </a> mais próximo ou poderá continuar usando, porém terá que pagar uma taxa pelo <a href="#tempo-acabou">tempo excedidio</a> |

<div id="tempo-acabou"></div>

| LE06 | **O Tempo acabou** |
| ------ | ---- | 
| **Sinônimos** | O Tempo do aluguel chegou ao fim, Tempo excedido|
| **Noção** | O Tempo acabou significa que tempo de aluguel da bicicleta chegou ao fim |
| **Impacto**| O <a href="#usuario" > usuário </a> poderá ter o tempo acabado conforme a escolha do<a href="#plano">  plano/aluguel</a> escolhido no aplicativo |

<div id="planos-disponiveis"></div>

| LE07 | **Planos disponíveis** |
| ------ | ---- | 
| **Sinônimos** | Opções de <a href="#plano">  plano</a> |
| **Noção** | Opções de planos disponiveis para a contratação, definidas pela localização do <a href="#usuario" > usuário </a> |
| **Impacto**| Os planos disponiveis limitam as opções de escolha de<a href="#plano">  plano</a> do usuário, podendo apenas contratar os planos disponiveis para a cidade selecionada |

<div id="sem-plano"></div>

| LE08 | **Sem plano** |
| ------ | ---- | 
| **Sinônimos** | Não possui<a href="#plano">  plano</a> |
| **Noção** | Estado em que o <a href="#usuario" > usuário </a> não contratou um<a href="#plano">  plano</a> |
| **Impacto**| O usuário estará restrito ao uso de algumas funcionalidades por ainda não possuir os beneficios realacionados a um<a href="#plano">  plano</a> |


*Tabela 6: Léxicos Estados*

## Referências

<p>[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. 2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA. Acesso em: 25 de fevereiro de 2022.</p>

