## 1. Versionamento
| Versão | Data  | Descrição                                     | Autor(es) |
| ------ | ----- | --------------------------------------------- | --------- |
| 1.0    | 21/03 | Abertura do documento de varificação do léxicos | Paulo henrique |
| 1.1    | 21/03 | Adição da tabela com as perguntas | Paulo henrique |
| 1.2    | 21/03 | Correção da tabela | Paulo henrique |

## 2. Introdução
<p style="text-align: justify; text-indent: 20px"> A verificação corresponde a uma metodologia que visa garantir que os produtos de um trabalho selecionado cumpram com seus requisitos especificados. Essa etapa, também consiste de uma técnica que não depende da intervenção humana dos usuários, sendo feita através do viés do desenvolvedor.</p>
<p style="text-align: justify; text-indent: 20px"> O escopo dessa verificação se limita ao documento de modelagem <a href="../modelagem/lexicos.md">Léxicos</a>.</p>

## 3. Metodologia
<p style="text-align: justify; text-indent: 20px"> Para a realização dessa verificação, será utilizada a técnica de inspeção pela estratégia de leitura e checklist, os critérios abordados tem o papel de contribuir para verificar se de fato os léxicos atendem a seu propósito e também apontando defeitos que permitem correções. Os critérios podem ser respondidos com "✅" (Sim) ou "❌" (Não), onde o Não provavelmente evidencia algum defeito que precisa ser melhorado.</p>

## 4. Inspeção

* Legenda

| Abreviação |                Descrição                |
| :--------: | :-------------------------------------: |
|   **L**    |                 Léxico                  |
| **O/V/E**  | Classificação (estado, verbo ou objeto) |
|   **XX**   |                Numeração                |
|   **✅**    |                   Sim                   |
|   **❌**    |                   Não                   |


| **Número** | **Critérios**                              | **LO01** | **LO02** | **LO03** | **LO04** | **LO05** | **LO06** | **LO07** | **LO08** | **LO09** | **LO10** | **LV01** | **LV02** | **LV03** | **LV04** | **LV05** | **LV06** | **LV07** | **LV08** | **LV09** | **LV10** | **LV11** | **LV12** | **LV13** | **LV14** | **LV15** | **LV16** | **LV17** | **LE01** | **LE02** | **LE03** | **LE04** | **LE05** | **LE06** | **LE07** | **LE08** |
| :--------: | ------------------------------------------ | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|     1      | **Está padronizado?**                      |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     2      | **Possui informações concisas?**           |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     3      | **Noção está compreensível?**              |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     4      | **Classificação está correta?**            |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     5      | **Impacto está correto?**                  |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     6      | **Sinônimos são compatíveis? (se houver)** |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |
|     7      | **Ortografia está correta?**               |    ❌     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ❌     |    ❌     |    ❌     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |    ✅     |


## 5. Conclusão


## 6. Bibliografia
