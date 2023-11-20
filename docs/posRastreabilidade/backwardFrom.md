# Backward-From

## Introdução

A rastreabilidade é uma propriedade de sistemas que permite que os requisitos sejam conectados às suas origens e aos artefatos criados durante o ciclo de vida do desenvolvimento do sistema. É importante notar que a produção desses artefatos é guiada pela linha de base dos requisitos. A rastreabilidade “Backward From” estabelece a ligação dos requisitos com suas fontes em outros documentos ou pessoas. Este artefato tem como objetivo documentar as conexões entre os requisitos, seus desenhos e sua implementação.

Elos de rastreabilidade referem-se à relação estabelecida entre artefatos ou elementos de um processo, sistema ou projeto ao longo de seu ciclo de vida. Esses elos são usados para rastrear e documentar as relações e dependências entre diferentes componentes, como requisitos. Eles permitem que os profissionais acompanhem e compreendam as relações entre os elementos do sistema. Isso facilita a análise de impacto de mudanças, a verificação do cumprimento dos requisitos e a identificação de possíveis lacunas ou inconsistências ao longo do desenvolvimento.

## Metodologia

Usaremos o Meta-modelo de Toranzo, aplicado à rastreabilidade de requisitos, que inclui a classificação dos requisitos em quatro níveis: ambiental, organizacional, gerencial e desenvolvimento, onde cada nivel é apresentado na tabela 1. O meta-modelo é usado para identificar os tipos de ligações entre os requisitos, como: satisfação, recurso, responsabilidade, representação, alocação e agregação, onde os tipos de relações são melhor descritos na tabela 2.

<center>

| Classificação    | Descrição                                                                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ambiental        | Congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido.                                |
| Organizacional   | Reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema.                                     |
| Gerencial        | Agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto.                                                           |
| Desenvolvimento. | abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...). |

<div style="text-align: center">
<p> Tabela 1: Classificação dos requisitos de acordo com o Meta-modelo de Toranzo.  (Fonte: Ana Luíza, 2023). </p>
</div>

| Tipo de ligação  | descrição                                                                           |
| ---------------- | ----------------------------------------------------------------------------------- |
| Satisfação       | indica que a classe de origem tem dependência de satisfação com classe de destino   |
| Recurso          | indica que a classe de origem tem dependência de recurso com classe de destino      |
| Responsabilidade | registra a participação, responsabilidade e ação de pessoas sobre artefatos         |
| Representação    | captura a representação ou modelagem dos requisitos em outras linguagens            |
| Alocação         | classe de origem está relacionada à classe de destino, que representa um subsistema |
| Agregação        | indica composição de elementos.                                                     |

<div style="text-align: center">
<p> Tabela 2: Tipos de ligação entre requisitos de acordo com o Meta-modelo de Toranzo.  (Fonte: Ana Luíza, 2023). </p>
</div>

</center>

## Legenda

Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o bom entendimento dos tópicos abaixo:

<center>

| Legenda | Artefato                  |
| ------- | ------------------------- |
| E       | Épico                     |
| US      | Histórias de usuário      |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| B       | Brainstorming             |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

</center>

<div style="text-align: center">
  <p> Tabela 1: Sigla de cada etapa (Fonte: Ana Luíza, 2023).</p>
</div>

## Histórico de Versão

| Versão  | Data       | Descrição                  | Autor                    | Revisor   |
|---------|------------|----------------------------|-------------|-----------|
| 1.0     | 20/11/20233 | Criação do documento | Ana Luíza, Ana Letícia e Artur | Rafael |