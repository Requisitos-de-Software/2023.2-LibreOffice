# Moscow

## Introdução

<div style="text-align:justify">Depois de coletarmos uma variedade de requisitos utilizando abordagens como narrativas, autorreflexão, exame de documentos e questionários, surge a necessidade de empregar estratégias de hierarquização. Isso nos permite avaliar a relevância de cada um desses requisitos de forma mais precisa.</div> 

<div style="text-align:justify">Assim, nesta seção, a abordagem escolhida para classificar a importância dos requisitos é o Método MoSCoW.</div>

## Metodologia

<div style="text-align:justify">O Método MoSCoW representa uma estratégia de priorização de requisitos concebida para auxiliar a equipe de desenvolvimento a tomar decisões de maneira mais eficaz. Essa metodologia está estruturada em quatro categorias fundamentais:</div>

 - **M** -> Must-Have (Deve ter)
 - **S** -> Should (Deveria ter)
 - **C** -> Could-Have (Poderia ter)
 - **W** -> Would/Want/Won't-Have (Não precisa ter)


### Must-Have

<div style="text-align:justify">A classificação Must-Have identifica as tarefas essenciais para o sucesso do projeto e que demandam priorização máxima. Esses requisitos têm um impacto significativo e agregam valor ao produto; caso sejam negligenciados, podem comprometer a experiência do cliente. As atividades classificadas como Must-Have são as mais urgentes e devem ser tratadas como prioridade absoluta pela equipe.</div>


### Should-Have

<div style="text-align:justify">A categoria Should-Have abrange as tarefas que são relevantes para o sucesso do projeto, embora não sejam tão críticas quanto as atividades Must-Have.</div>


### Could-Have

<div style="text-align:justify">A categoria Could-Have engloba tarefas que são menos prioritárias do que as atividades Should-Have. Embora esses requisitos contribuam para o valor do projeto, sua falta não afeta de forma substancial o andamento do mesmo.</div>


### Would/Want/Won't

<div style="text-align:justify">Finalmente, a categoria Would/Want/Won't-Have engloba tarefas que têm pouca ou nenhuma relevância para o projeto. Tanto a presença quanto a ausência desses requisitos não afetam de maneira significativa a conclusão bem-sucedida do projeto.</div>

## Objetivo

<div style="text-align:justify">O objetivo do Método MoSCoW é facilitar a harmonização entre a equipe de desenvolvimento e os stakeholders quanto ao que precisa ser realizado, com base na hierarquia de importância atribuída a cada elemento. Mediante o uso dessa técnica, o time de desenvolvimento é capaz de discernir o nível de prioridade das tarefas em um projeto e direcionar seus esforços para atender às demandas mais cruciais.</div>

## Requisitos 

<div style="text-align:justify">A Tabela 1 a seguir contém a priorização dos Requisitos elicitados. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.</div>
<br>
Legenda:

- INT: Requisitos de Introspecção
- ST: Requisitos de Brainstorming
- QUE: Requisitos do Questionário
- RF: Requisito Funcional
- RNF: Requisito Não Funcional


| Identificador | Requisito | Tipo | Prioridade | 
| :---: | :---------------: | :--: | :--------: | 
| INT01 | Ao abrir o aplicativo, deve aparecer uma tela com um documento em branco pronto para ser editado | RF  | Could |
| INT02 | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte | RF | Must |
| INT03 | Deve ser possível aplicar estilos de formatação de fonte, como negrito, itálico, sublinhado, tachado, sobrescrito e subscrito | RF | Must |
| INT04 | O usuário deve ter a opção de alinhar o texto: centralizar, justificar, alinhar à direita ou alinhar à esquerda | RF | Must |
| INT05 | O software deve permitir a criação de tópicos ordenados (numeração, letras), não ordenados (marcadores) e seus subtópicos | RF | Must |
| INT06 | Deve ser possível aumentar ou diminuir o recúo, bem como regular o espaçamento entre linhas e o espaço entre parágrafos | RF | Must |
| INT07 | O software deve permitir a inserção de desenhos e formas geométricas, como retas, setas, círculos, elipses, quadrados, retângulos, etc. | RF | Should |
| INT08 | Deve ser possível incluir arquivos de mídia, gráficos, tabelas e caixas de texto ao longo do documento que está sendo editado | RF | Should |
| INT09 | Deve ser possível inserir hiperlinks, notas de rodapé, notas de fim, marca-páginas, referências cruzadas e anotações (comentários) | RF | Should |
| INT10 | Deve haver um mecanismo para verificar a ortografia do texto | RF | Could |
| INT11 | Deve ser possível localizar e substituir partes do texto no documento | RF | Could | 
| INT12 | O software deve permitir a visualização da impressão e a impressão do documento | RF | Should |
| INT13 | Deve ser possível abrir um arquivo já existente no formato apropriado | RF | Wont't |
| INT14 | O usuário deve ter a capacidade de salvar o arquivo em pelo menos quatro extensões: `.pdf`, `.odt`, `.docx` e `.txt` | RF | Should |
| INT15 | Deve ser possível inserir quebras de página, permitindo ao usuário controlar a formatação do documento | RF | Should |
| INT16 | Deve ser possível inserir símbolos especiais e equações matemáticas no texto | RF | Could |
| INT17 | O software deve oferecer suporte a múltiplos idiomas, permitindo a edição de documentos em diferentes línguas | RF | Should |
| INT18 | O software deve permitir o controle de revisões, rastreando as alterações feitas no documento ao longo do tempo e possibilitando a aceitação ou rejeição das revisões | RF | Could | 
| INT19 | Deve ser possível colaborar em documentos em tempo real com outros usuários, permitindo a edição simultânea de um documento compartilhado | RF | Could |
| INT20 | O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo | RF | Must |
| INT21 | O software deve ser portável, funcionando em diferentes sistemas operacionais, como Windows, macOS e Linux | RNF | Must |
| INT22 | O LibreOffice Writer deve garantir a segurança dos documentos do usuário, incluindo a capacidade de criptografar documentos sensíveis e proteger com senha o acesso a arquivos | RNF | Could |
| INT23 | O software deve ser acessível a pessoas com deficiências, atendendo a padrões de acessibilidade e oferecendo suporte a leitores de tela e outras tecnologias assistivas | RNF | Should |
| INT24 | O LibreOffice Writer deve ser eficiente em termos de consumo de recursos do sistema, como CPU e memória, para garantir um desempenho responsivo mesmo em sistemas menos poderosos | RNF | Could |
| INT25 | Deve haver documentação abrangente disponível para os usuários, além de suporte técnico eficaz, incluindo fóruns, tutoriais e recursos de ajuda | RNF | Should |
| INT26 | O software deve ser capaz de abrir documentos criados em versões anteriores do LibreOffice Writer sem perda significativa de formatação ou conteúdo | RNF | Could |
| INT27 | Deve ser possível configurar facilmente opções de backup e restauração de documentos para evitar perda de dados acidental | RNF | Should |
| INT28 | Os usuários devem ter a capacidade de personalizar a interface do LibreOffice Writer de acordo com suas preferências | RNF | Won't |
| INT29 | O software deve promover o uso de formatos de arquivo abertos e padrões abertos para garantir a interoperabilidade com outros aplicativos e evitar bloqueio de fornecedor | RNF | Should |
| INT30 | O LibreOffice Writer deve ser tolerante a falhas, minimizando o impacto de erros do usuário ou falhas do sistema | RNF | Should |
| BS01  | O usuário deve poder criar documentos de texto.      | RF   | Must |
| BS02  |  O usuário deve poder editar documentos de texto.       | RF   | Must |
| BS03  | O usuário deve poder salvar documentos em vários formatos, incluindo ODF, .doc, e HTML.      | RF   | Must |
| BS04  | O usuário deve ter acesso a recursos como verificador ortográfico, dicionário de sinônimos e autocorreção. | RF  | Should |
| BS05  | O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas.   | RF | Must |
| BS06  | O usuário deve poder criar índices e sumários em documentos de texto.     | RF  | Must |
| BS07  | O usuário deve poder inserir figuras de diferentes formatos nos documentos.      | RF   | Should |
| BS08  | O usuário deve poder criar desenhos diretamente em documentos de texto.   | RF   | Should |
| BS09  | O usuário deve ter a capacidade de executar cálculos sofisticados em tabelas em documentos de texto.        | RF   | Should |
| BS10  | O usuário deve poder personalizar a interface do programa, incluindo ícones e menus.    | RF   | Won't |
| BS11  | O usuário deve poder utilizar a função de arrastar e soltar para trabalhar eficientemente com objetos nos documentos. | RF  |Could |
| BS12  | O usuário deve poder acessar um sistema de Ajuda na rede abrangente.   | RF   | Must |
| BS13  | O usuário deve ser capaz de colaborar em tempo real com outros usuários, permitindo a edição simultânea de documentos por várias pessoas. | RF   | Could |
| BS14  | O usuário deve ter a capacidade de traduzir automaticamente documentos para diferentes idiomas diretamente no aplicativo.    | RF | Won't |
| BS15  | O usuário deve poder integrar de maneira eficaz o aplicativo com serviços de armazenamento em nuvem, tornando o compartilhamento e o acesso a documentos mais simples e ágeis.    | RF  | Won't|
| BS16  | O usuário deve ter à disposição ferramentas avançadas de reconhecimento de fala para realizar ditado de texto nos documentos com precisão.      | RF   | Won't |
| BS17  | O usuário deve experimentar uma melhoria significativa na acessibilidade do aplicativo, atendendo a diretrizes rigorosas de acessibilidade.    | RF   | Should |
| BS18  | O usuário deve se beneficiar de recursos de análise de texto e IA que oferecem sugestões avançadas de formatação e conteúdo.      | RF   | Won't |
| BS19  | O usuário deve ter acesso a modelos específicos para diferentes tipos de documentos, como artigos acadêmicos e relatórios técnicos.      | RF   |  Won't |
| BS20  | O usuário deve poder realizar pesquisas avançadas para localizar informações em documentos extensos.    | RF   | Should |
| BS21  | O usuário deve ter a capacidade de editar documentos offline para facilitar o trabalho sem conexão à internet.  | RF   | Must |
| BS22  | O usuário deve poder utilizar uma função de voz para ouvir o texto lido em voz alta, especialmente útil para usuários com deficiência visual. | RF  | Should |
| BS23  | O LibreOffice Writer deve ser compatível com uma variedade de formatos de documento, incluindo ODF, .doc e HTML.                                    | RNF | Should |
| BS24  |  O aplicativo deve ser capaz de se integrar de forma eficaz com serviços de armazenamento em nuvem para facilitar o compartilhamento e o acesso a documentos. | RNF | Should |
| BS25  |    O LibreOffice Writer deve funcionar de forma eficiente, mesmo em documentos longos e complexos.   | RNF  | Should |
| BS26  | Deve ser acessível para pessoas com deficiência, seguindo diretrizes de acessibilidade para facilitar o uso por leitores de tela e outras tecnologias assistivas.  | RNF | Should |
| BS27  | O aplicativo deve ser compatível com sistemas mobile.                                           | RNF  | Should |
<div style="text-align:center"> Tabela 1: Priorização dos requisitos de acordo com método Moscow</div>


## Bibliografia

1. BARROS, André - Disponível em <https://aprender3.unb.br/pluginfile.php/2523073/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acessado em 04/10/2023

## Histórico de versão

| Versão | Data de execução  | Data de revisão |  Descrição    | Autor(es)     |  Revisor(es)  |
| :----: | :---------------: | :-------------: | :-----------: | :-----------: | :-----------: |
| `1.0` | 04/10/2023 | 04/10/2023 | Criação do documento | Raphaela Guimararães  | Rafael Xavier |
