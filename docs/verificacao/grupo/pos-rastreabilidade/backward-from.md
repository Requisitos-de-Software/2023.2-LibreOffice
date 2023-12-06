# Verificação do backward-from

## Introdução
Neste documento, será realizada a verificação da rastreabilidade Backward-from desenvolvida pela equipe. Sendo realizado a técnica de inspeção como forma de avaliação deste documento, além de seguir o planejamento previamente estabelecido.
<center>

| Versão | Autor(es)              | Revisor(es)         |
| :----: | ---------------------- | ------------------- |
| `1.0`  | Ana Luíza, Ana Letícia e Artur | Edilberto, Rafael e Raphaela |

<div style="text-align: center">
<p> Tabela 1: Versionamento, autores e revisores no artefato (Fonte: Raphaela Guimarães, 2023). </p>
</div>

</center>

<center>

| ID  |                                 Questão                                  | Inspeção |
| :-: | :----------------------------------------------------------------------: | :------: |
|  1  |                 As legendas estão no padrão do projeto?                  |    🟢    |
|  2  |                  Possui links para os outros artefatos?                  |    N/A    |
|  3  |                    Existe uma introdução no artefato?                    |    🟢    |
|  4  |               Existe tabela de versionamento padronizado?                |    🟢    |
|  5  |        Há referências bibliográficas ou referências no artefato?         |    🟢    |
|  6  | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟢    |
|  7  |                         O artefato possui autor?                         |    🟢    |
|  8  |                        O artefato possui revisor?                        |    🟢    |

</center>


<div style="text-align: center">
<p> Tabela 2: Verificações gerais (Fonte: Raphaela Guimarães, 2023). </p>
</div>

</center>

<center>

| ID  |                                                     Questão                                                       | Inspeção |
| :-: | :---------------------------------------------------------------------------------------------------------------: | :------: |
|  9  |                 A metodologia de rastreabilidade "backward-from" está detalhada e compreensível?                  |    🟢    |
|  10  |                  Os quatro níveis e seis elos de rastreabilidade estão claramente apresentados?                  |    🟢    |
|  11  |             Os elos entre os requisitos funcionais e não-funcionais estão corretamente identificados?            |    🟡    |
|  12  |   Os tipos de elos utilizados são: Satisfação, Recurso, Responsabilidade, Representação, Alocação e Agregação?   |    🟢    |
|  13  |                   O artefato utiliza os requisitos funcionais e os requisitos não funcionais?                    |    🟢    |
|  14  |                                  Existe a linkagem dos requisitos a sua origem?                                  |    🟢    |
|  15  |                               Existe legendas para ajudar na leitura do artefato?                                |    🟢    |
|  16  |                          A Legenda está de acordo com os símbolos presentes no artefato?                         |    🟢    |
|  17  |                       Os elos informam a Categoria, Elementos Rastreáveis e o tipo de Elo?                       |    🟢    |

<div style="text-align: center">
<p> Tabela 3: Verificações específicas (Fonte: Raphaela Guimarães, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa                                                                   |
| ----------- | ------------------------------------------------------------------------ |
| IDC1        | Adicionar elos entre os requisitos funcionais e não-funcionais faltantes |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Raphaela Guimarães, 2023). </p>
</div>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 4 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Raphaela Guimarães, 2023). </p>
</div>

<center>

| Acrônimo  | Descrição                      |
| --------- | ------------------------------ |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Raphaela Guimarães, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 16/17 exigências são atendidas;
- 1/17 exigências estão incompletas;
- 0/17 exigências estão erradas ou não foram realizadas.

onde 17 é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 16},
      {"legenda": "Incompleto", "value": 1},
      {"legenda": "Errado", "value": 0}
    ]
  },
  "mark": {"type": "arc", "innerRadius": 50, "tooltip": true},
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {
      "field": "legenda",
      "type": "nominal",
      "scale": {
        "domain": ["Completo", "Incompleto", "Errado"],
        "range": ["green", "yellow", "red"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Raphaela Guimarães, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 94,12% correto.


## Histórico de versão

|    Data    | Versão |      Descrição       | Autor(es) | Revisor(es) |
| :--------: | :----: | :------------------: | :-------: | :---------: |
| 04/12/2023 |  1.0   | Criação do documento | Raphaela Guimarães |   Rafael Xavier    | 
| 06/12/2023 |  1.1   | Correção do documento | Raphaela Guimarães |   Rafael Xavier    | 

