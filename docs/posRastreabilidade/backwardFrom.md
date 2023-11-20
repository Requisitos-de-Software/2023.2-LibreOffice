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

Para realizar o mapeamento dos requisitos, será utilizado a tabela 3 na qual contém todos os simbolos necessários para o bom entendimento dos tópicos abaixo:

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
  <p> Tabela 3: Sigla de cada etapa (Fonte: Ana Luíza, 2023).</p>
</div>

### Requisitos Funcionais

<details>
  <summary>RF01 - Salvar o arquivo em pelo menos quatro extensões</summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT14</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
  <td>Tabela 4: RF01. (Fonte: Ana Letícia, 2023)</td>
</details>

<details>
  <summary>RF02 - Inserir quebras de página </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT15</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 5: RF02 (Fonte: Ana Letícia, 2023).</td>
</details>

  <details>
  <summary>RF03 - Inserir símbolos especiais e equações matemáticas no texto </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT16</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 6: RF03 (Fonte: Ana Letícia, 2023).</td>
</details>

  <details>
  <summary>RF04 - O software deve oferecer suporte a múltiplos idiomas, permitindo a edição de documentos em diferentes línguas </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT17</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 7: RF04 (Fonte: Ana Letícia, 2023).</td>
</details>

  <details>
  <summary>RF05 - O software deve permitir o controle de revisões </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT18</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 8: RF05 (Fonte: Ana Letícia, 2023).</td>
</details>

  <details>
  <summary>RF06 - Deve ser possível colaborar em documentos em tempo real com outros usuários, permitindo a edição simultânea de um documento compartilhado </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT19</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 9: RF06 (Fonte: Ana Letícia, 2023).</td>
</details>

  <details>
  <summary>RF07 - O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo. </summary>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT20</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 10: RF07 (Fonte: Ana Letícia, 2023).</td>
</details>

### Requisitos Não Funcionais

<details>
  <summary>RNF01 - O software deve ser portável</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT21</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 11: RNF01 (Fonte: Ana Letícia, 2023).</td>
</details>

<details>
  <summary>RNF02 - O software deve garantir a segurança dos documentos do usuário com senha e criptografia.
</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT22</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 12: RNF02 (Fonte: Ana Letícia, 2023).</td>
</details>

<details>
  <summary>RNF03 - O software deve ser eficiente em termos de consumo de recursos do sistema, como CPU e memória, para garantir um desempenho responsivo mesmo em sistemas menos poderosos.
</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT24</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 13: RNF03 (Fonte: Ana Letícia, 2023).</td>
</details>

<details>
  <summary>RNF04 - O aplicativo deve ser compatível com sistemas mobile.
</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Origem</td>
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>BS27</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
<td>Tabela 14: RNF04 (Fonte: Ana Letícia, 2023).</td>
</details>
## Histórico de Versão

| Versão  | Data       | Descrição                  | Autor                    | Revisor   |
|---------|------------|----------------------------|-------------|-----------|
| 1.0     | 20/11/20233 | Criação do documento | Ana Luíza, Ana Letícia e Artur | Edilberto, Rafael e Raphaela |