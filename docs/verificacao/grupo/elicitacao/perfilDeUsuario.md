# Verificação do Perfil de Usuário

## Introdução

Para a verificação do artefato perfil de usuário será utilizada a técnica de inspeção. A tabela 1 mostra os metadados do perfil de usuário, e nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor  | Revisor       |
| --------------- | ------ | ------------- |
| 1.0             | Ana Luiza | Edilberto |

</center>
<div style="text-align: center">
<p> Tabela 1: Metadados do artefato (Fonte: Ana Letícia, 2023). </p>
</div>

Como dito, para a verificação, será adotada a técnica de inspeção, a qual será realizada por meio de uma checklist. Essa checklist consiste em uma série de perguntas que têm como objetivo avaliar se o artefato foi desenvolvido de acordo com as exigências da disciplina.

A checklist será preenchida com base em diferentes classificações, que incluem:

- 🟢: Completamente Satisfatório;
- 🟡: Incompleto;
- 🔴: Não realizado ou Errado;
- N/A: Não se aplica.

| ID  |                                 Questão                                  | Inspeção |
| :-: | :----------------------------------------------------------------------: | :------: | 
|  1  |                 As legendas estão no padrão do projeto?                  |    N/A    |                                                                              
|  2  |                  Possui links para os outros artefatos?                  |   🟢    |                                                                              
|  3  |                    Existe uma introdução no artefato?                    |    🟢    |    
|  4  |               Existe tabela de versionamento padronizado?                |    🟢    |                                                                              
|  5  |        Há referências bibliográficas ou referências no artefato?         |    🟢    |  
|  6  | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    N/A    |                                   
|  7  |                         O artefato possui autor?                         |    🟢    |                                                                              
|  8  |                        O artefato possui revisor?                        |    🟢    |                                                                              

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as questões padroẽs (Fonte: Ana Letícia, 2023). </p>
</div>

| ID  |                                                    Questão                                                     | Inspeção  | 
| :-: | :------------------------------------------------------------------------------------------------------------: | :------:  | 
| 9  | Os dados para o perfil de usuário foram coletados por meio de algum estudo, como entrevistas ou questionários?[1] |    🟢      | 
| 10  |                            A proporção de usuários em cada perfil foi determinada?[1]                            |    🔴     |  
| 11  |   Os perfis de usuário são agrupados por faixa etária, experiência, atitude e tarefas primárias no sistema?[1]    |    🟢     |  
| 12  |                           Possui termo de consentimento esclarecedor e bem descrito?[1]                           |    🟢     |  
| 13  |                            Os dados levantados fazem sentido no escopo do projeto?[1]                           |    🟢     |   
| 14  |               Possui e considera aspectos éticos de toda e qualquer pesquisa envolvendo pessoas?[1]               |    🟢     |  

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Ana Letícia, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa         |
| ------------- | -------------- |
| IDC1          | Determinar a proporção de usuários em cada perfil     |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Ana Letícia, 2023). </p>
</div>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão citada na metodologia

### Porcentagem

Nos checklists realizados, podemos observar que:

- 11/14 exigências são atendidas;
- 0/14 exigências estão incompletas;
- 2/14 não se aplicam
- 1/14 exigências estão erradas ou não foram realizadas.

Portanto, com base no cálculo realizado, pode-se dizer que o aproveitamento deste artefato está em 92.86%.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 11},
      {"legenda": "Incompleto", "value": 0},
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Ana Letícia, 2023). </p>
</div>


## Referência Bibliográfica 

>[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. p. 166.

## Histórico de versão

|    Data    | Versão |         Descrição         |    Autor(es)     |  Revisor(es)
| :--------: | :----: | :-----------------------: | :--------------: |  ---------------
| 30/11/2023 |  1.0   |   Criação do documento    | Ana Letícia      |  Ana Luiza
|02/12/2023  |   1.1  |   Padronização da página  | Ana Letícia      |  Ana Luiza

