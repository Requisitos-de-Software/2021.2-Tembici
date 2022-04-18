# Viewpoint 
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 18/04 | Criação do artefato | Victor Eduardo |

*Tabela 1: versionamento*

## Introdução
<p align="justify">&emsp;&emsp;A técnica é baseada no fato de que os requisitos de software podem e devem ser eliciados de diferentes pontos de vista, e que a avaliação resultante das diferenças deles pode ser usada como uma forma de auxiliar na validação inicial dos requisitos. É também uma linguagem para expressar diferentes pontos de vista, além de prover um conjunto de heurísticas para realizar uma análise sintaticamente orientada às visões propostas. Essa análise de pontos de vista é capaz de diferenciar entre informações ausentes e informações conflitantes, fornecendo, assim, suporte para a resolução de pontos de vista.</p>

## Metodologia
<p align="justify">&emsp;&emsp;A metodologia adotada para a execução da validação por pontos de vista foi proposta por Julio Cesar Sampaio do Prado Leite e Peter A. Freeman. Além de ser recomendada para a disciplina, se adequa ao escopo do nosso projeto. Desse modo, o domínio utilizado para os pontos de vistas apresentados é o próprio domínio geral da aplicação, tendo como base todos os artefatos gerados até então. O escopo será reduzido e irá desconsiderar documentos propostos pelo próprio app, visto que não foram elaborados pelos integrantes do trabalho e foram criados sobre diferentes lincensas.</p>
<p align="justify">&emsp;&emsp;Cada viewpoint adotará uma perspectiva diferente visando validar diferentes pontos de vista. A Viewpoint Viewpoint A adotará a perspectiva de processo, enquanto a Viewpoint B adotará a perspectiva do autor, nesse caso sendo o Victor Eduardo no dia 18/04/2022.</p>

## Resultados
### View Point A
```
Perspectiva de Processo:
    ((usuario =usuario-id =email =imagem-perfil)
     (mapa =mapa-id 
        (=localização-atual) 
        (=trajeto) 
        (=estações =desbloquear-bike (=qr-code) (=código)))
     (plano =plano-id =comprar-plano =cidade =categoria =escolher-plano =forma-de-pagamento)
     (caminho =caminho-id =buscar-destino =iniciar =instruções =desbloquer-bike =detalhes)
     (menu =menu-id 
        (=ajuda =cidade =central-ajuda) 
        (=viagens =histórico) 
        (=plano-id) 
        (=notificações)))

Hierarquia:
 (é um
       (agente (usuario))
       (objeto (bike para desbloquear)))
 
 (parte de
       (objeto (plano =plano-id cidade categoria)
               (assinar plano =plano-id))
       (objeto (mapa mapa-id localização atual localização estação)
               (seleciona estação))
       (objeto (trajeto estação =mapa-id)
               (descrição e expectativa de chegada))
       (objeto (desbloquear-bike =mapa-id)
               ((=qrcode)(=código)))
       (objeto (menu =menu-id)
               (viagens =histórico)))
```

### View Point B
```
Perspectiva do Autor:
    ((usuario =usuario-id =email =imagem-perfil)
     (mapa =mapa-id =estações =desbloquear-bikes)
     (desbloquear-bikes-id 
        (=qr-code =plano-id =desbloqueada) 
        (=código =plano-id =desbloqueada))
     (plano =plano-id =comprar-plano =cidade =categoria =escolher-plano =forma-de-pagamento)
     (menu =menu-id 
        (=ajuda =cidade =central-ajuda) 
        (=viagens =histórico) 
        (=plano-id) 
        (=notificações)))

Hierarquia:
 (é um
       (agente (usuario))
       (objeto (desbloquear bike)))
 
 (parte de
       (objeto (plano =plano-id cidade categoria)
               (assinar plano =plano-id))
       (objeto (mapa mapa-id localização atual localização estação)
               (seleciona estação))
       (objeto (trajeto estação =mapa-id)
               (descrição e expectativa de chegada))
       (objeto (desbloquear-bike =mapa-id)
               ((=qrcode)(=código)))
       (objeto (menu =menu-id)
               (viagens =histórico)))
```

### Análise de Resultados
<p align="justify">&emsp;&emsp;Após serem feitas ambas as views, foi feita a comparação de ambas para que assim fosse gerada as inconsistências e discrepâncias entre ambas.</p>

#### Inconsistência
##### Fatos em A
- Não há inconsistência em A.
##### Fatos em B
- Não é possível definir um fluxo para as ações.
- O momento em que se assina o plano é diferente para cada viewpoint
#### Fatos Faltantes
##### Os fatos abaixo estão em falta em ambas perspectivas:
- Andar-de-bike(Ação).
- Fazer cadastro(Ação)

### Conclusão e Integração
<p align="justify">&emsp;&emsp;Os elementos da viewpoint A estão bem mais detalhados, e pode-se traçar um fluxo bem definido com ele, diferente da viewpoint B, na qual não é possível traçar um fluxo bem definido, porém nessa última os elementos estão menos repetitivos.</p>
<p align="justify">&emsp;&emsp;Ao conciliar as duas é possível obter um resultado que deixe claro o fluxo de elementos mas que não seja repetitivo, sendo a melhor opção.</p>

## Referências 
> LEITE, Julio Cesar Sampaio do Prado;FREEMAN, Peter A. "Requirements validation through viewpoint resolution." IEEE Trans. Software Eng. 17.12 (1991): 1253-1269.

> Thiago, Grupo Ingresso.com. Disponível em:<https://requisitos-de-software.github.io/2021.1-Ingresso.com/validacao/viewpoint/>. Acesso em: 18/04/2022.