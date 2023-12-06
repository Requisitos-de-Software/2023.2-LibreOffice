## Introdução

O Brainstorming é uma abordagem que visa obter insights sobre os tipos de conteúdo e funcionalidades que os usuários demandam e desejam em um produto ou serviço. Essa técnica é aplicável a uma ampla gama de produtos e serviços, e resulta na criação de uma lista organizada das necessidades e preferências dos usuários. Em geral, o Brainstorming é utilizado para identificar requisitos e identificar novas características que seriam bem recebidas pelos usuários em um produto. Essa técnica é particularmente valiosa quando aplicada na fase inicial do desenvolvimento do produto. Durante uma sessão de brainstorming, os participantes são encorajados a expressar livremente suas ideias e opiniões em torno de um tópico específico. Os resultados dessa atividade podem ser diretamente incorporados às especificações funcionais e à documentação de design.

## Metodologia

O processo de brainstorming foi realizado via Teams na data de 28/09/2023 de 12:30 até 13:20, onde a integrante Ana Luíza assumiu o papel de moderadora, e os integrantes Ana Letícia, Rafael e Raphaela davam respostas ou ideias com base nos temas que a moderadora colocava em pauta. O processo contou somente com a participação de 3 usuários, mesmo que no livro Interação Humano-Computador (Barbosa e Silva. Página 153)<a id="anchor_1" href="#FRM1">^1^</a> recomenda-se envolver entre 8 e 12 usuários em uma sessão, foram escolhidos somente 3 pela dificuldade de conseguir mais participantes, além da disponibilidade de tempo para realizar a sessão. Os participantes estão listados na Tabela 1.

## Participantes

<center>

| Nome                                                      | Função     |
| --------------------------------------------------------- | ---------- |
| <span style = "color: red"> Ana Luíza Rodrigues </span>         | Mediadora  |
| <span style = "color: orange"> Ana Letícia Melo </span>        | Usuário    |
| <span style = "color: orange"> Rafael Xavier </span>        | Usuário    |
| <span style = "color: orange"> Raphaela Guimarães </span> | Usuário    |

Tabela 1: Participantes do brainstorming (Fonte: Rafael Xavier, 2023)

</center>

Ao longo da sessão, a moderadora lançava um tema sobre o aplicativo para que os participantes dessem suas respostas em um quadro na ferramenta Miro em dois minutos, como mostrado na Figura 1.

<center>

![teste](../../images/quadro_brainstorm/brainstormingprint.jpg)

Figura 1: Quadro de respostas (Fonte: Participantes do brainstorming, 2023)
</center>

## Temas/Respostas

### Quem seria o público-alvo do aplicativo?

<span style = "color: orange"> Rafael </span> 
- Alguém que presta algum tipo de serviço pode usar o app para fazer um recibo informal, por exemplo.
- Estudantes, professores.

<span style = "color: orange"> Ana Letícia </span> 
- Jornalistas, escritores, estudantes, empresas, organizações e pesquisadores.

<span style = "color: orange"> Raphaela </span>
- Escritores, autores, gestores, assistentes administrativos, secretarios, jornalistas

### Quais são os principais objetivos e funcionalidades do aplicativo?

<span style = "color: orange"> Rafael </span> 
- Redigir,formatar, editar e salvar textos,sejam eles formais, informais, acadêmicos ou empresariais.
- Fazer moldes de letras( ou quaisquer outras formas) para artesanato

<span style = "color: orange"> Ana Letícia </span> 
- Criar, editar e formatar documentos de texto, facilitar a colaboração (várias pessoas editando juntas)... criação de índices, tabelas de conteúdo, estilos de formatação, correção ortográfica e gramatical

<span style = "color: orange"> Raphaela </span>
- Documentação, educação, registro

### Quais são os principais concorrentes do LibreOffice Writer?

<span style = "color: orange"> Ana Letícia, Rafael e Raphaela </span>
- Google Docs
- Microsoft Word

### Quais são os principais problemas encontrados ao usar as funcionalidades do aplicativo?

<span style = "color: orange"> Ana Letícia </span> 
- Interface menos intuitiva e moderna que a dos concorrentes
- Layout poluido e símbolos não tão intuitivos

<span style = "color: orange"> Raphaela </span>
- Muitas opções/ funcionalidades, falta de acessibilidade

### Quais seriam possíveis soluções para esses problemas?

<span style = "color: orange"> Ana Letícia, Rafael e Raphaela </span>

- Painel de Navegação: Implementar um painel de navegação que facilite a movimentação e a localização de partes específicas do documento, tornando-o mais acessível para pessoas com deficiência visual ou mobilidade reduzida.

- Menu de Cabeçalho e Rodapé: Revisar e melhorar o menu de cabeçalho e rodapé, tornando-o mais intuitivo e fácil de usar, o que beneficiará os usuários que precisam acessar e editar essas partes do documento.

- Reduzir a Quantidade de Ícones no Menu de Funcionalidades: Simplificar o menu de funcionalidades, eliminando ícones desnecessários e organizando as funcionalidades em abas no topo, com base em seu escopo (por exemplo, formatar, inserir, exibir, estilos, etc.), para melhorar a usabilidade e a acessibilidade.

- Menu Minimalista: Oferecer um menu minimalista com as principais funcionalidades visíveis, para tornar mais fácil para todos os usuários encontrar e utilizar as funções essenciais do LibreOffice Writer.

- Utilizar Símbolos Mais Intuitivos: Substituir ou aprimorar os símbolos usados na interface do usuário, tornando-os mais intuitivos e compreensíveis, especialmente em comparação com os concorrentes, para que os usuários possam facilmente identificar as funcionalidades.

- Seção de Ajuda: Incluir uma seção de ajuda dedicada com as principais dúvidas e dificuldades dos usuários, proporcionando um recurso de suporte acessível para orientar os usuários e resolver problemas comuns.

- Essas sugestões podem melhorar significativamente a acessibilidade e a usabilidade do LibreOffice Writer, tornando-o mais inclusivo e amigável para todos os tipos de usuários.

### Requisitos elicitados

Após a sessão de brainstorming, foi possível fazer a elicitação dos requisitos funcionais listados na Tabela 2 e os requisitos não funcionais listados na Tabela 3.

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- BSx: Requisito nºx elicitado pelo Brainstorming.

<br>

<center>

| <a id="anchor_BS" style="color:black;"> ID</a> | Descrição                                                       | Código | Implementado |
| ---------------------------------------------- | ------------------------------------------------------------------------------ | ------ | :------: |
| BS01       | O usuário deve poder criar documentos de texto.      | RF01   | Sim |
| BS02       |  O usuário deve poder editar documentos de texto.       | RF02   | Sim |
| BS03     | O usuário deve poder salvar documentos em vários formatos, incluindo ODF, .doc, e HTML.      | RF03   | Sim |
| BS04    | O usuário deve ter acesso a recursos como verificador ortográfico, dicionário de sinônimos e autocorreção.                                               | RF04   | Sim|
| BS05  | O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas.   | RF05   | Sim |
| BS06      | O usuário deve poder criar índices e sumários em documentos de texto.     | RF06   | Sim |
| BS07   | O usuário deve poder inserir figuras de diferentes formatos nos documentos.      | RF07   | Sim |
| BS08    | O usuário deve poder criar desenhos diretamente em documentos de texto.   | RF08   | Nåo |
| BS09     | O usuário deve ter a capacidade de executar cálculos sofisticados em tabelas em documentos de texto.        | RF09   | Sim |
| BS10   | O usuário deve poder personalizar a interface do programa, incluindo ícones e menus.    | RF10   | Sim |
| BS11  | O usuário deve poder utilizar a função de arrastar e soltar para trabalhar eficientemente com objetos nos documentos. | RF11   | Não |
| BS12   | O usuário deve poder acessar um sistema de Ajuda na rede abrangente.   | RF12   | Não |
| BS13      | O usuário deve ser capaz de colaborar em tempo real com outros usuários, permitindo a edição simultânea de documentos por várias pessoas. | RF13   | Não |
| BS14     | O usuário deve ter a capacidade de traduzir automaticamente documentos para diferentes idiomas diretamente no aplicativo.    | RF14   | Não |
| BS15     | O usuário deve poder integrar de maneira eficaz o aplicativo com serviços de armazenamento em nuvem, tornando o compartilhamento e o acesso a documentos mais simples e ágeis.    | RF15   | Não |
| BS16   | O usuário deve ter à disposição ferramentas avançadas de reconhecimento de fala para realizar ditado de texto nos documentos com precisão.      | RF16   | Não |
| BS17  | O usuário deve experimentar uma melhoria significativa na acessibilidade do aplicativo, atendendo a diretrizes rigorosas de acessibilidade.    | RF17   | Não |
| BS18    | O usuário deve se beneficiar de recursos de análise de texto e IA que oferecem sugestões avançadas de formatação e conteúdo.      | RF18   | Não |
| BS19   | O usuário deve ter acesso a modelos específicos para diferentes tipos de documentos, como artigos acadêmicos e relatórios técnicos.      | RF19   | Não |
| BS20    | O usuário deve poder realizar pesquisas avançadas para localizar informações em documentos extensos.    | RF20   | Não |
| BS21    | O usuário deve ter a capacidade de editar documentos offline para facilitar o trabalho sem conexão à internet.  | RF21   | Não |
| BS22    | O usuário deve poder utilizar uma função de voz para ouvir o texto lido em voz alta, especialmente útil para usuários com deficiência visual.                    | RF22   | Não |

Tabela 2: Requisitos funcionais (Fonte: Rafael Xavier, 2023)
</center>

<br>
<center>

| <a id="anchor_BSNF" style="color:black;">ID</a> | Descrição                                                                 | Código | Implementado |
| ----------------------------------------------- | ------------------------------------------------------------------------- | ------ | :------: |
| BS23           | O LibreOffice Writer deve ser compatível com uma variedade de formatos de documento, incluindo ODF, .doc e HTML.                                    | RNF01  | Sim |
| BS24      |  O aplicativo deve ser capaz de se integrar de forma eficaz com serviços de armazenamento em nuvem para facilitar o compartilhamento e o acesso a documentos. | RNF02  | Não |
| BS25   |    O LibreOffice Writer deve funcionar de forma eficiente, mesmo em documentos longos e complexos.   | RNF03  | Sim |
| BS26   | Deve ser acessível para pessoas com deficiência, seguindo diretrizes de acessibilidade para facilitar o uso por leitores de tela e outras tecnologias assistivas.  | RNF04  | Não |
| BS27   | O aplicativo deve ser compatível com sistemas mobile.                                           | RNF05  | Não |

Tabela 3: Requisitos não funcionais (Fonte: Rafael Xavier, 2023)
</center>

## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.


## Bibliografia

> Técnicas de Elicitação de Requisitos - Brainstorming. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-brainstorming. Acesso em: 02/10/2023.

## Histórico de Versões

| Versão | Data       | Descrição                            | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ------------------------------------ | ---------------------------------------------- | ---------------------------------------------- |
| 1.0    | 28/04/2023 | Criação do artefato       | Rafael Xavier   | Ana Luíza |
