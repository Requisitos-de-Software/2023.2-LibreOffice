# Verificação do artefato do Aplicativo Escolhido

## Introdução

Este documento apresentará a verificação do artefato [Aplicativo Escolhido](https://requisitos-de-software.github.io/2023.2-LibreOffice/planejamento/appEscolhido/), desenvolvido pelo nosso grupo, LibreOffice. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1 , se encontram os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

</br>

<center>

| Versão |       Autor(es)     |     Revisor(es)   |
| :----: | :-----------------: | :----------: |
| 1.0  | Ana Luíza | Rafael |

</center>

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato Aplicativo Escolhido (Fonte: Rafael Xavier, 2023). </p>
</div>

<center>

|  ID   |                                 Questão                                  | Inspeção |
| :---: | :----------------------------------------------------------------------: | :------: |
|   1   |                 As legendas estão no padrão do projeto?                  |    🟢     |    
|   2   |                  Possui links para os outros artefatos?                  |    N/A     |            
|   3   |                    Existe uma introdução no artefato?                    |    🟢     |             
|   4   |               Existe tabela de versionamento padronizado?                |    🟢     |             
|   5   |        Há referências bibliográficas ou referências no artefato?         |    🟢     |             
|   6   | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟢    |             
|   7   |                         O artefato possui autor?                         |    🟢     |             
|   8   |                        O artefato possui revisor?                        |    🟢     |          

</center>

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação das verificações gerais do artefato (Fonte: Rafael Xavier, 2023). </p>
</div>

</br>

<center>

|  ID   |                                 Questão                                  | Inspeção | 
| :---: | :----------------------------------------------------------------------: | :------: | 
|   9   |              O aplicativo não foi trabalhado no semestre anterior?       |    🟢    |             
|   10 |                O APP é do governo ou comunidade?                |   🟢    |                
|   11   |         É levado em consideração o acesso aos usuários?                 |    🟢     |   
|   12   |               São descritos os motivos de escolha do App?                |    🟢     |             
|   13   |               Há especificações sobre o Termo de Uso do app selecionado?        | 🟢     |             

</center>

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação das verificações específicas do artefato (Fonte: Rafael Xavier, 2023). </p>
</div>

## Tarefas

Na tabela 4, se encontram os ajustes a serem feitos no artefato.

<center>

| ID Correção | Tarefa         |
| ------------- | -------------- |
| IDC1          | Corrigir dois erros na escrita  |

</center>

<div style="text-align: center">
<p> Tabela 4: Tabela de ajustes a serem feitos (Fonte: Rafael Xavier, 2023). </p>
</div>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Rafael Xavier, 2023). </p>
</div>

<center>

| Acrônimo  | Descrição                      |
| --------- | ------------------------------ |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Rafael Xavier, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 13/13 exigências são atendidas;
- 0/13 exigências estão incompletas;
- 0/13 exigências estão erradas ou não foram realizadas.

onde 13 é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 13},
      {"legenda": "Incompleto", "value": 0},
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Rafael Xavier, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 100% correto conforme consta no gráfico 1.

## Correção 

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4.

<center>

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi corrigido os erros de escrita |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Rafael Xavier, 2023). </p>
</div>

</center>


## Bibliografia

> SERRANO, Milene. Requisitos – Aula 15. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 12/11/2023.

## Histórico de versão

|    Data    | Versão |      Descrição       | Autor(es) | Revisor(es) |
| :--------: | :----: | :------------------: | :-------: | :---------: |
| 26/11/2023 |  1.0   | Criação do documento | Rafael Xavier |   Ana Luíza    |