# Cenários
## Versionamento

| Versão | Data | Descrição | Autor |
| -- | -- | -- | -- |
| 1.0 | 02/03/2022 | Criação do documento | João Victor Batista |
| 1.1 | 04/03/2022 | Revisão | Luiz Henrique, Gabriel Sabanai |
| 1.2 | 04/03/2022 | Adição revisor | Luiz Henrique |
| 1.3 | 09/04/2022 | Padronização de Legendas e Metodologias | Victor Eduardo |
| 2.0 | 10/04/2022 | Melhorias de rastreabilidade | Paulo Henrique |
| 2.1 | 11/04/2022 | Continuação de melhorias da rastreabilidade | Paulo Henrique |


*Tabela 1: Versionamento*

<div id="introducao"></div>

## Introdução
<div align="justify">&emsp;&emsp; Um cenário se trata de uma descrição curta de como um evento (ou eventos futuros) pode impactar as operações de um sistema. Eles constituem exemplos da vida real de como o sistema é ou será utilizado.
</div>
<div align="justify">&emsp;&emsp; Os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações pontuais do usuário com o sistema, onde cada cenário cobre um pequeno número das possíveis variações de determinada interação.
</div>
<div align="justify">&emsp;&emsp; Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em diferentes níveis de detalhamento sobre o sistema. Neste artefato estão registrados todos os cenários criados.
</div>

## Metodologia
<div align="justify">&emsp;&emsp; Cada cenário descreve uma situação de uso do sistema e é representado por uma tabela conforme o seguinte formato:</div>

| Título | Título do Cenário |
| -- | -- |
| Objetivo | Objetivo/meta do cenarios |
| Contexto | pré-condição:<br>pós-condição: |
| Atore | Atores envolvidos |
| Recursos | Recursos envolvidos |
| Episódios | Detalhes do cenários |
| Restrições | Descrição da retrição | 
| Exceção | Descrição da exceção |

<p align="justify">&emsp;&emsp;Os casos de uso abaixo foram feitos pelo integrante do grupo João Victor, após levantar os cenários possíveis no app. Para cada cenário é feita uma tabela igual a citada acima com preenchida de acordo com o cenário.</p>

## Resultados

<div id="cadastro"></div>

### C01 - [Cadastrar usuário](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#cadastrar-usuario) por email
| Título | Cadastrar usuário por email |
| -- | -- |
| Objetivo | Criar perfil para o usuário no Tembici utilizando email |
| Contexto | pré-condição: Possuir email válido<br>pós-condição: Perfil do usuário é criado |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário não cadastrado acessa o aplicativo Tembici<br>2. O usuário não cadastrado seleciona a opção de criar conta<br>3. O usuário não cadastrado insere email e senha e seleciona o botão "Continuar"<br> |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 2: Descrição do Cenário Cadastrar usuário por email*

<div id="login"></div>

### C02 - [Acessar a conta](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#logar)
| Título | Acessar a conta |
| -- | -- |
| Objetivo | Acessar a conta usuário no Tembici |
| Contexto | pré-condição: Não estar logado na conta<br>pós-condição: Usuário logado no Tembici |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Possuir conta criada |
| Episódios | 1. O usuário acessa o aplicativo Tembici<br>2. O usuário seleciona a opção de "Fazer seu login"<br>3. O usuário insere email e senha e seleciona o botão "Continuar"<br> |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 3: Descrição do Cenário Acessar a conta*

<div id="sair"></div>

### C03 - Sair da Conta
| Título | Sair da Conta |
| -- | -- |
| Objetivo | Sair da conta logada no app |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: [Logout da conta](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#nao-logado) |
| Atore | Usuário |
| Recursos | Acesso à internet<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Sair" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 4: Descrição do Cenário Sair da Conta*

<div id="ajuda"></div>

### C04 - Escolher Ajuda
| Título | Escolher Ajuda |
| -- | -- |
| Objetivo | Consultar informações sobre os serviços do Tembici |
| Contexto | pré-condição: [Usuário logado](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#logar) no Tembici<br>pós-condição: Ver informações sobre o funcionamento do app |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Ajuda"<br>3. O usuário seleciona sua cidade<br>4. O usuário seleciona o tópico que quer consultar |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 5: Descrição do Cenário Escolher Ajuda*

<div id="escolher-planos"></div>

### C05 - Escolher Planos e Pagamento
| Título | Escolher Planos e Pagamento |
| -- | -- |
| Objetivo | Consultar as opções de planos de [assinatura](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#plano) do Tembici |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: Ver informações sobre os planos do app |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Planos e pagamento"<br>3. O usuário seleciona sua cidade<br>4. O usuário seleciona o botão de "Conheça os planos Tembici" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 6: Descrição do Cenário Escolher Planos e Pagamento*

<div id="assinar-planos"></div>

### C06 - [Assinar Plano](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#assinar)
| Título | Assinar Plano |
| -- | -- |
| Objetivo | Comprar um plano para utilizar os serviços do app |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: Plano comprado |
| Atore | [Usuário](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#usuario) |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Comprar Plano"<br>3. O usuário seleciona sua cidade<br>4. O usuário seleciona o botão de "Conheça os planos Tembici"<br>5. O usuário seleciona o plano de sua escolha<br>6. O usuário cadastra um cartão ou seleciona um cartão cadastrado<br>7. O usuário seleciona o botão de "Comprar Plano" |
| Restrições | Fluxo intuitivo | 
| Exceção | Cartão inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 7: Descrição do Cenário Assinar Plano*

<div id="bicicleta-disponivel"></div>

### C07 -  Vizualizar [Bicicletas Disponíveis](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#consultar-bicicleta)
| Título |  Vizualizar Bicicletas Disponíveis |
| -- | -- |
| Objetivo | Poder ver o número de bicicletas disponíveis em cada estação |
| Contexto | pré-condição: App instalado<br>pós-condição: Ver localização das estações e o número de bicicletas disponíveis em cada uma |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário acessa o Tembici<br>2. O usuário navega pelo mapa da tela inicial |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 8: Descrição do Cenário Vizualizar Bicicletas Disponíveis*

<div id="vagas-disponivel"></div>

### C08 -  Vizualizar Vagas Disponíveis
| Título |  Vizualizar [Vagas Disponíveis](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#cadastrar-vagas) |
| -- | -- |
| Objetivo | Poder ver o número de vagas disponíveis em cada estação |
| Contexto | pré-condição: App instalado<br>pós-condição: Ver localização das estações e o número de vagas disponíveis em cada uma |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário acessa o Tembici<br>2. O usuário seleciona uma estação |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 9: Descrição do Cenário Vizualizar Vagas Disponíveis*

<div id="informaçao-estaçao"></div>

### C09 -  Vizualizar Informações de uma [Estação](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#estacao)
| Título |  Vizualizar Informações de uma Estação |
| -- | -- |
| Objetivo | Poder ver informações sobre uma estação |
| Contexto | pré-condição: App instalado<br>pós-condição: Ver informações sobre uma estação |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado |
| Episódios | 1. O usuário acessa o [Tembici](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#software)<br>2. O usuário seleciona uma estação |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 10: Descrição do Cenário Vizualizar Informações de uma Estação*

<div id="historico-viagens"></div>

### C10 -  Vizualizar [Histórico de Viagens](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#consultar-historico)
| Título |  Vizualizar Histórico de Viagens |
| -- | -- |
| Objetivo | Consultar informações sobre as viagens realizadas pelo usuário |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: Ver informações sobre as viagens realizadas |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado no app |
| Episódios | 1. O usuário acessa a tela de opções<br>2. O usuário seleciona o botão de "Viagens" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 11: Descrição do Cenário Vizualizar Histórico de Viagens*

<div id="desbloquear-bicicleta"></div>

### C11 - [Desbloquear Bicicleta](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#alugar) por [QR Code](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#qr-code)
| Título | Desbloquear Bicicleta por QR Code |
| -- | -- |
| Objetivo | Poder utilizar a camera para escanear um QR Code e desbloquear uma bicicleta |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: Desbloquear uma bicicleta |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado |
| Episódios | 1. O usuário acessa o Tembici<br>2. O usuário seleciona uma estação<br>2. O usuário seleciona o botão de "Ler QR Code" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 12: Descrição do Cenário Desbloquear Bicicleta por QR Code*

<div id="codigo-desbloqueio"></div>

### C12 - Desbloquear Bicicleta por [código](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/lexicos/#gerar-codigo) de acesso
| Título | Desbloquear Bicicleta por código de acesso |
| -- | -- |
| Objetivo | Poder gerar um código de acesso para desbloquear uma bicicleta |
| Contexto | pré-condição: Usuário logado no Tembici<br>pós-condição: Desbloquear uma bicicleta |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Usuário logado |
| Episódios | 1. O usuário acessa o Tembici<br>2. O usuário seleciona uma estação<br>2. O usuário seleciona o botão de "Gerar código" |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |

*Tabela 13: Descrição do Cenário Desbloquear Bicicleta por código de acesso*

## Referências
<a href="https://requisitos-de-software.github.io/2021.1-TesouroDireto/modelagem/cenarios/">Documento de Cenário do grupo Tesouro Direto</a>