## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|08/02|<center>Adição da política de contribuição</center>|<center>Paulo Henrique</center>|

### 1.1 Políticas de Branch

<p style="text-align: justify; text-indent: 20px">As branches serão nomeadas seguindo um padrão para a melhor organização do projeto. Por se tratar de um projeto baseado em documentos, terá apenas um tipo de nomenclatura de branch. Todas as branchs devem ser criadas a partir da <b>main</b> e devem estar nomeadas da seguinte maneira:</p>

``` 
X-NomeDocumento 
Exemplo: 4-PoliticaDeContribuicao
```

<p style="text-align: justify; text-indent: 20px"> Sendo X o número da issue atribuída seguido pelo nome do documento, como destacado anteriormente. Em ocasiões em que não se está trabalhando com nenhum documento em específico, então deve-se colocar o nome da issue correspondente.</p>

### 1.2 Políticas de Commits

<p style="text-align: justify; text-indent: 20px">Os commits devem ser feitos de maneira clara e objetiva respeitando os padrões comentados a seguir: </p>

<ul>
    <li> Devem estar escritos em português. </li>
    <li> Os verbos devem estar no gerúndio. </li>
    <li> Devem apresentar o número base da issue. </li>
</ul>

&emsp;&emsp;Portanto a formatação do commit será: ` #4 Corrigindo documento de planejamento `

<p style="text-align: justify; text-indent: 20px"> Nas ocasiões em que o commit foi realizado por duas ou mais pessoas, deve ser acrescentado à mensagem do commit o seguinte texto: </p>

```
#4 -Corrigindo documento de politicas


Co-authored-by: Paulo Henrique <ph@gmail.com>
```

&emsp;&emsp;<b>Observação:</b> O caracter '#' representa, por padrão, um comentário na mensagem de commit. Para evitar problemas basta digitar o comando: `git config --local core.commentChar auto`
