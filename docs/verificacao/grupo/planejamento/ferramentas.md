# Verificação Ferramentas

## Introdução

O presente documento apresentará a verificação do artefato [Ferramentas](https://requisitos-de-software.github.io/2023.2-LibreOffice/planejamento/ferramentas/), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

## Cronograma e participantes

Para efetuar a inspeção e verificação do documento a integrante Ana Luíza juntamente com o autor do artefato, Artur Seppa Reiman, realizou uma gravação dessa atividade para ter uma melhor elucidação e visão da inspeção efetuada do documento. Portanto como cronograma seguido, foi efetuado uma gravação via Teams às 19:15 do dia 27 de novembro de 2023, como pode ser visto no vídeo 1.

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/mNNOT7cJ4pA?si=z1AO50z9ifuTUl64" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div style="text-align: center">
<p> Vídeo 1: Gravação da verificação das ferramentas. (Fonte: Ana Luíza e Artur, 2023). </p>
</div>

</center>

## Verificação

<center>

| Versão |  Autor(es) | Revisor(es) | 
| :----: | :--------: | :---------: |
| 0.1   | Artur Seppa Reiman | Edilberto |

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato produzido. (Fonte: Ana Luíza, 2023). </p>
</div>

</center>

<center>

| ID |                                 Questão                                 | Inspeção |
| :-: | :--------------------------------------------------------------------: | :------: |
| 1 |                 As legendas estão no padrão do projeto?                  |    🔴    |
| 2 |                  Possui links para os outros artefatos?                  |    N/A   |
| 3 |                   Existe uma introdução no artefato?                     |    🟢    |
| 4 |                Existe tabela de versionamento padronizado?               |    🟡    |
| 5 |      Há referências bibliográficas ou referências no artefato?           |    🟡    |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟡    |
| 7 |                         O artefato possui autor?                         |    🟢    |
| 8 |                        O artefato possui revisor?                        |    🟢    |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as questões padroẽs (Fonte: Ana Luíza, 2023). </p>
</div>

</center>

<center>

|  ID   |                                      Questão                              | Inspeção |
| :---: | :-----------------------------------------------------------------------: | :------: |
|   9   | Todas as ferramentas são acompanhadas por uma descrição que descreve seu propósito de uso ? |  🟢 |
|   10   | Todas as ferramentas são acompanhadas por uma logo que representa a identidade visual da ferramenta ? |    🟢     |
|   11   |            O nome, ícone e finalidade das ferramentas estão corretas ?      |    🟢     |
|   12   |      Todas as ferramentas utilizadas contém as devidas referências?       |    🟢     |

</center>

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato. (Fonte: Ana Luíza, 2023). </p>
</div>

## Tarefas

<center>

| ID Correção | Tarefa         |
| ------------- | -------------- |
| IDC1          | Corrigir as legendas de acordo com o padrão do projeto  |
| IDC2          | Corrigir a tabela de versionamento de acordo com o padrão do projeto  |
| IDC3          | Corrigir a bibliografia tirando os números e colocando em ordem alfabética |
| IDC4          | Incluir a chamada da tabela 1 no texto |
| IDC5          | Ajustar o tamanho dos ícones das ferramentas |

</center>
<div style="text-align: center">
<p> Tabela 4: Tabela de ajustes a serem feitos. (Fonte: Ana Luíza, 2023). </p>
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

- 7/12 exigências são atendidas;
- 3/12 exigências estão incompletas;
- 1/12 exigências estão erradas ou não foram realizadas.
- 1/12 exigências não se aplica.

onde 12 é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 7},
      {"legenda": "Incompleto", "value": 3},
      {"legenda": "Errado", "value": 1}
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Ana Luíza, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 58,3% correto.

## Correção 

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4.

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi ajustado as legendas de acordo com o padrão do projeto |
| IDC2          | Foi ajustado a tabela de versionamento de acordo com o padrão do projeto       |
| IDC3          | Foi ajustado a bibliografia tirando os números e colocando em ordem alfabética           |
| IDC4          | Foi ajustado o tamanho dos ícones das ferramentas para o valor de 70 pixels. |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Artur Seppa Reiman, 2023). </p>
</div>

</center>


## Bibliografia

> WHEELER, Alina. Design de identidade de marca. Porto Alegre: Bookman, 2013.

## Histórico de versão

|    Data    | Versão |      Descrição       | Autor(es) | Revisor(es) |
| :--------: | :----: | :------------------: | :-------: | :---------: |
| 26/11/2023 |  1.0   | Criação do documento | Ana Luíza |   Artur    |
| 05/12/2023 |  1.1   | Indicação de ajustes feitos nas ferramentas | Artur Seppa Reiman |   -    |

