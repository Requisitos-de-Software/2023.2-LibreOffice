# Verificação Backlog

## Introdução

O presente documento apresentará a verificação do artefato [Backlog](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontram os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

<center>

| Versão |  Autor(es) | Revisor(es) | 
| :----: | :--------: | :---------: |
|   1.1  | Atualização das referências das tabelas | Artur Seppa Reiman | Artur Seppa, Raphaela |

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato produzido. (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

</center>

## Cronograma e planejamento

Para efetuar a inspeção e verificação do documento os integrantes Ana Luíza e Rafael realizaram uma gravação dessa atividade para ter uma melhor elucidação e visão da inspeção efetuada do documento. Portanto como cronograma seguido, foi efetuado uma gravação via Teams às 21:50 do dia 26 de novembro de 2023, como pode ser visto no vídeo 1.

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/uSTVB2Motyg?si=vUzHpMYfoiw0DnYn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div style="text-align: center">
<p> Vídeo 1: Gravação da verificação do Backlog. (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>
</center>

## Verificação

<center>

| ID |                                 Questão                                 | Inspeção |
| :-: | :--------------------------------------------------------------------: | :------: |
| 1 |                 As legendas estão no padrão do projeto?                  |    🟡    |
| 2 |                  Possui links para os outros artefatos?                  |    🔴    |
| 3 |                   Existe uma introdução no artefato?                     |    🟢    |
| 4 |                Existe tabela de versionamento padronizado?               |    🟡    |
| 5 |      Há referências bibliográficas ou referências no artefato?           |    🟢    |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟡    |
| 7 |                         O artefato possui autor?                         |    🟢    |
| 8 |                        O artefato possui revisor?                        |    🟡    |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as questões padroẽs (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

</center>

<center>

|  ID   |                                      Questão                              | Inspeção |
| :---: | :-----------------------------------------------------------------------: | :------: |
|   9   |               Os épicos estão priorizados e ordenados?                    |    🔴    |
|   10  |                      O backlog foi validado com o usuário ou PO?          |    🟡    |
|   11  |         O backlog possui funcionalidades desejadas para o produto?        |    🟢    |
|   12  |  A especificação dos itens do backlog é baseada em histórias de usuários  |    🟢    |
|   13  | As historias de usuário tem relação com o épico no qual estão contidas?   |    🟢    |
|   14  | Os épicos possuem histórias de usuários suficientes e condizentes para levar mais de uma sprint para ser concluída? |    🟢    |
|   15  |                     O backlog possui rastreabilidade?                     |    🔴    |

</center>

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato. (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

## Tarefas

<center>

| ID Correção | Tarefa         |
| ------------- | -------------- |
| IDC1          | Corrigir as legendas de acordo com o padrão do projeto  |
| IDC2          | Corrigir, ou retirar o link para as histórias de usuário  |
| IDC3          | Retirar todo e qualquer link de github de membros do grupo |
| IDC4          | Corrigir o histórico de versão de acordo com o padrão do projeto, especificamente a parte da versão que tem um fundo cinza, não compatível com o padrão do projeto |
| IDC5          | Corrigir a chamada da tabela 7 na metodologia, que está referênciada como tabela 1 |
| IDC6          | Ordenar os épicos de acordo com a prioridade |
| IDC7          | Remover o vídeo de validação com o usuário, pois o vídeo está mais relacionado com as histórias de usuário |
| IDC8          | Incluir a rastreabilidade do backlog |

</center>
<div style="text-align: center">
<p> Tabela 4: Tabela de ajustes a serem feitos. (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 4 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Ana Luíza, 2023). </p>
</div>

<center>

| Acrônimo  | Descrição                      |
| --------- | ------------------------------ |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Ana Luíza, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 7/15 exigências são atendidas;
- 5/15 exigências estão incompletas;
- 3/15 exigências estão erradas ou não foram realizadas.

onde 15 é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 7},
      {"legenda": "Incompleto", "value": 5},
      {"legenda": "Errado", "value": 3}
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 46,7% correto.

## Correção 

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4.

<center>

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi ajustado x realizando... |
| IDC2          | Foi incluido x em ...        |
| IDC3          | Foi removido x ...           |
| IDC4          | X foi especificaod melhor... |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Ana Luíza e Rafael, 2023). </p>
</div>

</center>


## Bibliografia

> SERRANO, Milene. Requisitos – Aula 15. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 12/11/2023.

## Histórico de versão

|    Data    | Versão |      Descrição       | Autor(es) | Revisor(es) |
| :--------: | :----: | :------------------: | :-------: | :---------: |
| 26/11/2023 |  1.0   | Criação do documento | Ana Luíza e Rafael |   Artur    |