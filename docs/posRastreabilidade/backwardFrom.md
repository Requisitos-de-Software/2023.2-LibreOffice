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

<details>
  <summary>RF08 - O usuário deve poder editar documentos de texto. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming/#requisitos-elicitados>BS02</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/casosDeUso/#caso-de-uso-2-editar-documento>UC02</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l06-editar-documentos-de-texto>L06</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#epicos_1>E04</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#epicos_1>US20</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF08</td>
  </table>
  <div>
    <p> Tabela 11: Requisito Funcional 08. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RF09 - O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming/#requisitos-elicitados>BS05</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT06</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>E02</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>US05</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/cenarios/#cenario-2>C02</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF09</td>
  </table>
  <div>
    <p> Tabela 12: Requisito Funcional 09. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RF10 - O usuário deve poder criar índices e sumários em documentos de texto. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming/#requisitos-elicitados>BS06</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l07-criar-indices-e-sumarios>L07</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF10</td>
  </table>
  <div>
    <p> Tabela 13: Requisito Funcional 10. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RF11 - O usuário deve poder personalizar a interface do programa, incluindo ícones e menus. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming>BS10</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT28</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/cenarios/#cenario-9>C09</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l10-personalizar-a-interface-do-aplicativo>L10</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF11</td>
  </table>
  <div>
    <p> Tabela 14: Requisito Funcional 11. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RF12 - O usuário deve poder utilizar uma função de voz para ouvir o texto lido em voz alta, especialmente útil para usuários com deficiência visual. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming>BS22</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
  <div>
    <p> Tabela 15: Requisito Funcional 12. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RF13 - O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT02</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l04-estilo-de-texto>L04</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>E02</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>US08</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF12</td>
  </table>
  <div>
    <p> Tabela 16: Requisito Funcional 13. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<!-------------------------------------------------------------------- Requisitos ARTUR --------------------------------------------------------------------------------->

<details>
  <summary>RF14 - O software deve permitir a criação de tópicos ordenados, não ordenados e seus subtópicos no texto.</summary>
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
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT05</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#epicos_1>E03</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#product-backlog>US11</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF13</td>
  </table>
<p> Tabela 17: Requisito Funcional 14. (Fonte: Artur Seppa Reiman, 2023). </p>
</details>

<details>
  <summary>RF15 - Deve ser possível modificar o recúo regular o espaçamento entre linhas e o espaço entre parágrafos. </summary>
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
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT06</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>E02</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US09</a>.
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF14</td>
  </table>
<p> Tabela 18: Requisito Funcional 15. (Fonte: Artur Seppa Reiman, 2023). </p>
</details>

<details>
  <summary>RF16 - Deve ser possível incluir anexos de mídia, gráficos, tabelas, além de poder efetuar a construção deles no documento. </summary>
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
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT08</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l03-inserir-grafico>L03</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l09-criacao-de-desenhos-em-documentos-de-texto>L09</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l13-documento>L13</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>E03</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US10</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US12</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US13</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US14</a>.
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF15</td>
  </table>
<p> Tabela 19: Requisito Funcional 16. (Fonte: Artur Seppa Reiman, 2023). </p>
</details>

<details>
  <summary>RF17 - Deve haver um mecanismo para verificar e ajustar a ortografia do texto. </summary>
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
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT10</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT11</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>E03</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US15</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US16</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/#historias-de-usuario>US17</a>.
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF16</td>
  </table>
<p> Tabela 20: Requisito Funcional 17. (Fonte: Artur Seppa Reiman, 2023). </p>
</details>

<!-------------------------------------------------------------------- Requisitos ARTUR --------------------------------------------------------------------------------->

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

<details>
  <summary>RNF05 - O aplicativo deve ser capaz de se integrar de forma eficaz com serviços de armazenamento em nuvem para facilitar o compartilhamento e o acesso a documentos. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming>BS24</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/cenarios/#cenario-10>C10</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>E05</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>US27</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>ENF05</td>
  </table>
  <div>
    <p> Tabela 28: Requisito Não Funcional 05. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RNF06 - O LibreOffice Writer deve funcionar de forma eficiente, mesmo em documentos longos e complexos. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming/#requisitos-elicitados>BS25</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>
        </td>
  </table>
  <div>
    <p> Tabela 29: Requisito Não Funcional 06. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RNF07 - Deve ser acessível para pessoas com deficiência, seguindo diretrizes de acessibilidade para facilitar o uso por leitores de tela e outras tecnologias assistivas. </summary>
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
        <td>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/tecnicas/brainstorming/#requisitos-elicitados>BS26</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT23</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>E04</a>
          <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog>US24</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>ENF06</td>
  </table>
  <div>
    <p> Tabela 30: Requisito Não Funcional 07. (Fonte: Ana Luíza, 2023). </p>
  </div>
</details>

<details>
  <summary>RNF08 -  Deve ser assegurado a existência de uma infraestrutura de suporte aos usuários, contendo uma documentação abrangente, suporte técnico e recursos adicionais, tais como fóruns, tutoriais e mecanismos de ajuda. </summary>
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
        <td><a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/introspeccao>INT25</a>, <a href=https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/#l14-usuario>L14</a>.
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF17</td>
  </table>
<p> Tabela 21: Requisito Não Funcional 08. (Fonte: Artur Seppa Reiman, 2023). </p>
</details>

## Elos Funcionais

### EF08

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS02
    - Caso de uso: UC02
    - Léxico: L06
    - Épico: E04
    - História de usuário: US20
- **Elo**:
    - **Representação:**
        - UC02 representa BS02
        - L06 representa BS02
    - **Alocado:**
        - A US20 está alocada no E04

### EF09

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS05
    - Épico: E02
    - História de usuário: US05
    - Introspecção: INT06
    - Cenários: C02
- **Elo**:
    - **Representação:**
        - C02 representa BS05 e INT06
    - **Alocado:**
        - A US05 está alocada no E02

### EF10

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS06
    - Léxico: L07
- **Elo**:
    - **Representação:**
        - L07 representa BS06

### EF11

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS10
    - Léxico: L10
    - Introspecção: INT28
    - Cenários: C09
- **Elo**:
    - **Representação:**
        - L10 representa BS10 e INT28
        - C09 representa BS10 e INT28

### EF12

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Léxico: L04
    - Épico: E02
    - História de usuário: US08
    - Introspecção: INT02
- **Elo**:
    - **Representação:**
        - L04 representa INT02
    - **Alocado:**
        - A US08 está alocada no E02

### EF13

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Épico: E03
    - História de usuário: US11
    - Introspecção: INT05
- **Elo**:
    - **Alocado:**
        - A US11 está alocada no E03

### EF14

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Épico: E02
    - História de usuário: US09
    - Introspecção: INT06
- **Elo**:
    - **Alocado:**
        - A US09 está alocada no E02

### EF15

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Léxico: L03, L09, L13
    - Épico: E03
    - História de usuário: US10, US12, US13, US14
    - Introspecção: INT08
- **Elo**:
    - **Representação:**
        - L03, L09 e L13 representam INT08
    - **Alocado:**
        - A US10, US12, US13 e US14 estão alocadas no E03

### EF16

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Épico: E03
    - História de usuário: US15, US16, US17
    - Introspecção: INT10 e INT11
- **Elo**:
    - **Alocado:**
        - A US15, US16 e US17 estão alocadas no E03

### EF17

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Léxico: L14
    - Introspecção: INT25
- **Elo**:
    - **Representação:**
        - L14 representa INT25

## Elos Não Funcionais

### ENF05

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS24
    - Épico: E05
    - História de usuário: US27
    - Cenários: C10
- **Elo**:
    - **Representação:**
        - C10 representa BS24
    - **Alocado:**
        - A US27 está alocada no E05

### ENF06

- **Categoria:** Desenvolvimento
- **Elementos rastreáveis:**
    - Brainstorming: BS26
    - Épico: E04
    - História de usuário: US24
    - Introspecção: INT23
- **Elo**:
    - **Representação:**
        - US24 representa BS26 e INT23
    - **Alocado:**
        - A US24 está alocada no E04

## Histórico de Versão

| Versão | Data        | Descrição            | Autor                          | Revisor                      |
| ------ | ----------- | -------------------- | ------------------------------ | ---------------------------- |
| 1.0    | 20/11/2023 | Criação do documento | Ana Luíza, Ana Letícia e Artur | Edilberto, Rafael e Raphaela |
