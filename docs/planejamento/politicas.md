# Políticas de contribuição
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 08/02 | Adição da política de contribuição | Paulo Henrique |
| 1.1 | 24/02 | Padronização da página | Victor Eduardo |
| 1.2 | 06/03 | Revisão | Luiz Henrique  |

*Tabela 1: versionamento*

## Introdução
<p style="text-align: justify; text-indent: 20px">As políticas de contribuição são essenciais para a padronização e boas praticas no versionamento do projeto, para o mesmo será utilizado a plataforma github.

## Política de Branch

<p style="text-align: justify; text-indent: 20px">As branches serão nomeadas seguindo um padrão para a melhor organização do projeto. Por se tratar de um projeto baseado em documentos, terá apenas um tipo de nomenclatura de branch. Todas as branchs devem ser criadas a partir da <b>main</b> e devem estar nomeadas da seguinte maneira:</p>

``` 
X-NomeDocumento 
Exemplo: 4-PoliticaDeContribuicao
```

<p style="text-align: justify; text-indent: 20px"> Sendo X o número da issue atribuída seguido pelo nome do documento, como destacado anteriormente. Em ocasiões em que não se está trabalhando com nenhum documento em específico, então deve-se colocar o nome da issue correspondente.</p>

### Política de Commit

<p style="text-align: justify; text-indent: 20px">Os commits devem ser feitos de maneira clara e objetiva respeitando os padrões comentados a seguir: </p>

<ul>
    <li> Devem estar escritos em português. </li>
    <li> Os verbos devem estar no gerúndio. </li>
    <li> Devem apresentar o número base da issue. </li>
</ul>

&emsp;&emsp;Portanto a formatação do commit será: ` #4 Corrigindo documento de planejamento `

<p style="text-align: justify; text-indent: 20px"> Nas ocasiões em que o commit foi realizado por duas ou mais pessoas, deve ser acrescentado à mensagem do commit o seguinte texto: </p>

```
#4 - Corrigindo documento de politicas


Co-authored-by: Paulo Henrique <ph@gmail.com>
```

&emsp;&emsp;<b>Observação:</b> O caracter '#' representa, por padrão, um comentário na mensagem de commit. Para evitar problemas basta digitar o comando: `git config --local core.commentChar auto`

## Referências

Git Breakdown. Politicas de Commit. Disponível em: https://fga-eps-mds.github.io/2019.2-Git-Breakdown/docs/commits. Acesso em 8 Fevereiro de 2022.