# Técnica dos 100 dólares

## Introdução

Após a coleta dos requisitos utilizando as técnicas de brainstorming, introspecção e questionários, é necessário estabelecer uma priorização para compreender a importância de cada um deles. Nesse contexto, o artefato desenvolvido emprega a técnica dos 100 dólares como uma abordagem eficaz para priorizar os requisitos levantados.

## Metodologia

A técnica citada consiste em atribuir uma quantidade fictícia de "dólares" a cada requisito, representando o valor relativo que ele possui para o projeto. Dessa forma, é possível identificar quais requisitos são considerados mais cruciais ou valiosos para a sua implementação e quais são considerados os menos valiosos, contendo uma forma limitada e acertiva de recursos para escolher as exigências necessárias. Ademais, essa é uma abordagem que proporciona uma visão clara das prioridades e auxilia na alocação eficiente dos recursos disponíveis no projeto. [[1]](#RP1)

## Requisitos

Com base na metodologia descrita e os requisitos elicitados, a priorização de requisitos pode ser representada a seguir pela tabela abaixo. Nota-se que o identificador de cada requisito é formatado por um PR + um número, sendo PR uma abreviação de priorização de requisitos e o número indica a enumeração do grau de prioridade de requisito para o sistema.

| Identificador | Requisito | Tipo | Valor ($) |
| :-: | :-: | :-: | :-: |
| PR01 | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte | RF | $5,00 |
| PR02 | Deve ser possível aplicar estilos de formatação de fonte, como negrito, itálico, sublinhado, tachado, sobrescrito e subscrito | RF | $5,00 |
| PR03 | O usuário deve ter a opção de alinhar o texto: centralizar, justificar, alinhar à direita ou alinhar à esquerda | RF | $5,00 |
| PR04 | O software deve permitir a criação de tópicos ordenados (numeração, letras), não ordenados (marcadores) e seus subtópicos | RF | $5,00 |
| PR05 | Deve ser possível aumentar ou diminuir o recúo, bem como regular o espaçamento entre linhas e o espaço entre parágrafos | RF |  $5,00 |
| PR06 | O software deve permitir a inserção de desenhos e formas geométricas, como retas, setas, círculos, elipses, quadrados, retângulos, etc. | RF | $5,00 |
| PR07 | Deve ser possível incluir arquivos de mídia, gráficos, tabelas e caixas de texto ao longo do documento que está sendo editado | RF | $5,00 |
| PR08 | Deve haver um mecanismo para verificar a ortografia do texto | RF | $5,00 |
| PR09 | Deve ser possível abrir um arquivo já existente no formato apropriado | RF | $5,00 |
| PR10 | O usuário deve ter a capacidade de salvar o arquivo em pelo menos quatro extensões: `.pdf`, `.odt`, `.docx` e `.txt` | RF | $5,00 |
| PR11 | Deve ser possível colaborar em documentos em tempo real com outros usuários, permitindo a edição simultânea de um documento compartilhado | RF |  $5,00 |
| PR12 | O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo | RF |  $5,00 |
| PR13 | O software deve ser portável, funcionando em diferentes sistemas operacionais, como Windows, macOS e Linux | RNF |  $5,00 |
| PR14 | O LibreOffice Writer deve garantir a segurança dos documentos do usuário, incluindo a capacidade de criptografar documentos sensíveis e proteger com senha o acesso a arquivos | RNF | $5,00 |
| PR15 | Deve ser possível inserir hiperlinks, notas de rodapé, notas de fim, marca-páginas, referências cruzadas e anotações (comentários) | RF | $4,00 |
| PR16 | O software deve permitir a visualização da impressão e a impressão do documento | RF | $4,00 |
| PR17 | Deve ser possível inserir quebras de página, permitindo ao usuário controlar a formatação do documento | RF |  $4,00 |
| PR18 | O software deve permitir o controle de revisões, rastreando as alterações feitas no documento ao longo do tempo e possibilitando a aceitação ou rejeição das revisões | RF |  $4,00 |
| PR19 | O software deve ser acessível a pessoas com deficiências, atendendo a padrões de acessibilidade e oferecendo suporte a leitores de tela e outras tecnologias assistivas | RNF | $4,00 |
| PR20 | O software deve oferecer suporte a múltiplos idiomas, permitindo a edição de documentos em diferentes línguas | RF |  $2,00 |
| PR21 | O LibreOffice Writer deve ser eficiente em termos de consumo de recursos do sistema, como CPU e memória, para garantir um desempenho responsivo mesmo em sistemas menos poderosos | RNF | $2,00 |
| PR22 | Ao abrir o aplicativo, deve aparecer uma tela com um documento em branco pronto para ser editado | RF  | $2,00 |
| PR23 | O LibreOffice Writer deve ser tolerante a falhas, minimizando o impacto de erros do usuário ou falhas do sistema | RNF | $2,00 |
| PR24 | Os usuários devem ter a capacidade de personalizar a interface do LibreOffice Writer de acordo com suas preferências | RNF | $2,00 |
| PR25 | Deve haver documentação abrangente disponível para os usuários, além de suporte técnico eficaz, incluindo fóruns, tutoriais e recursos de ajuda | RNF | $0,00 |
| PR26 | O software deve ser capaz de abrir documentos criados em versões anteriores do LibreOffice Writer sem perda significativa de formatação ou conteúdo | RNF | $0,00 |
| PR27 | Deve ser possível configurar facilmente opções de backup e restauração de documentos para evitar perda de dados acidental | RNF | $0,00 |
| PR28 | O software deve promover o uso de formatos de arquivo abertos e padrões abertos para garantir a interoperabilidade com outros aplicativos e evitar bloqueio de fornecedor | RNF | $0,00 |
| PR29 | Deve ser possível localizar e substituir partes do texto no documento | RF | $0,00 |
| PR30 | Deve ser possível inserir símbolos especiais e equações matemáticas no texto | RF |  $0,00 |

<div style="text-align: center">
<p> Tabela 1: Priorização de Requisitos (Fonte: Artur Seppa Reiman, 2023).</p>
</div>

## Referências bibliográficas

> <a id="RP1" href="#TEC1">1.</a> L. Dean and W. Don. 2003. Managing software requirements: A use case approach. In Addison Wesley. Disponível em: https://aprender3.unb.br/pluginfile.php/2523050/mod_resource/content/4. Acesso em: 02/10/2023.


## Histórico de Versão

| Versão  | Data       | Descrição                  | Autor                    | Revisor   |
|---------|------------|----------------------------|-------------|-----------|
| 1.0     | 02/10/20233 | Criação do documento | Artur Seppa Reiman | Rafael |
