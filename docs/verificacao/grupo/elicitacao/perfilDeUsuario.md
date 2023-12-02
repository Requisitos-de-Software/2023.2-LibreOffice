# Verificação do Perfil de Usuário e Questionário

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
<p> Tabela 2: Tabela de avaliação com as gerais para todos os artefatos (Fonte: Ana Letícia, 2023). </p>
</div>

| ID  |                                                    Questão                                                     | Inspeção  | Referência |
| :-: | :------------------------------------------------------------------------------------------------------------: | :------:  | ---------------------------------
| 9  | Os dados para o perfil de usuário foram coletados por meio de algum estudo, como entrevistas ou questionários? |    🟢                                          | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166|
| 10  |                            A proporção de usuários em cada perfil foi determinada?                             |    🔴     | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166 |
| 11  |   Os perfis de usuário são agrupados por faixa etária, experiência, atitude e tarefas primárias no sistema?    |    🟢     | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166 |
| 12  |                           Possui termo de consentimento esclarecedor e bem descrito?                           |    🟢                                          | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166 |
| 13  |                            Os dados levantados fazem sentido no escopo do projeto?                             |    🟢                                          | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166 | 
| 14  |               Possui e considera aspectos éticos de toda e qualquer pesquisa envolvendo pessoas?               |    🟢                                         | Barbosa e Silva. Interação Humano Computador e Experiência do Usuário, 2021. p. 166 |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Ana Letícia, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa         |
| ------------- | -------------- |
| ID10          | Determinar a proporção de usuários em cada perfil     |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Ana Letícia, 2023). </p>
</div>


Os perfis de usuário estão bem definidos, mas faltou trazer as proporções referentes a cada grupo. Por exemplo, citar que de x pessoas que responderam o questionário, y possuem ensino superior completo. Essas proporções existem dentro da página de questionário, então pode apenas referenciá-la. 

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizada a fórmula que foi definida na metodologia.

Por meio dessa verificação, observamos que:

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

### Cronograma

A tabela 5, contém o cronograma para a correção dos problemas identficiados nos artefatos.

<center>

| Data início | Data fim |
| ------------ | -------- |
| 02/12        | 04/12    |

<div style="text-align: center">
<p> Tabela 5: Tabela de cronograma dos ajustes (Fonte: Ana Letícia, 2023). </p>
</div>


## Bibliografia

>[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1

## Referência Bibliográfica 

>[1] EICKELMANN, Nancy S. et al. An empirical study of modifying the Fagan inspection process and the resulting main effects and interaction effects among defects found, effort required, rate of preparation and inspection, number of team members and product 1st pass quality. In: 27th Annual NASA Goddard/IEEE Software Engineering Workshop, 2002. Proceedings. IEEE, 2002. p. 58-64.

## Histórico de versão

|    Data    | Versão |         Descrição         |    Autor(es)     |  Revisor(es)
| :--------: | :----: | :-----------------------: | :--------------: |  ---------------
| 30/11/2023 |  1.0   |   Criação do documento    | Ana Letícia      |  Ana Luiza
|02/12/2023  |   1.1  |   Padronização da página  | Ana Letícia      |  Ana Luiza