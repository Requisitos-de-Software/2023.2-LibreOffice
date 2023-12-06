# Backlog

## Introdução

"O Product Backlog é uma lista contendo todas as funcionalidades desejadas para um produto. O conteúdo desta lista é definido pelo Product Owner" Milene Serrano e Maurício Serrano (2017) [[1]](#referencias-bibliograficas). Aprofundando a explicação, o backlog do produto permite organizar os itens de acordo com sua prioridade. As prioridades e outras gerências do  backlog é realizado pelo *Product Owner* (PO), visando garantir que o produto final atenda às necessidades do cliente. Os itens listados em um backlog podem ser requisitos, funcionalidades, correções de bugs ou melhorias e podem ser modificados ao longo do projeto. Além disso, o backlog é um importante artefato para o sucesso de um produto pois permite:

* Comunicação e alinhamento: O backlog do produto ajuda a equipe de desenvolvimento e o cliente a se comunicar e alinhar suas expectativas.
* Planejamento e execução: O backlog do produto fornece uma base para o planejamento e a execução do desenvolvimento do produto.
* Flexibilidade: O backlog do produto pode ser alterado à medida que as necessidades do cliente ou do mercado mudam



## Metodologia 

Durante a entrevista com o Product Owner (PO) ([que está neste artefato](./historiasDeUsuario.md)), os desenvolvedores e entrevistadores registraram as histórias de usuário conforme o PO as descrevia. Após isso, estabeleceram critérios de aceitação e o PO classificou as histórias em três níveis de prioridade: Alta, Média ou Baixa, utilizando o método Three Level Scale. Em seguida, categorizaram as histórias em temas, épicos e features. A [Tabela 7](#product-backlog)
(seção Resultados obtidos) fornece o backlog do produto, com detalhes de cada história de usuário disponíveis no artefato correspondente. O restante deste documento explica mais detalhadamente o processo de definição de temas, épicos e features, juntamente com o significado de cada termo.


## Resultados Obtidos
### Temas

Analisando a gravação com o PO, foi possível organizar inicialmente em dois grandes temas.

- **Documentos**: Engloba as funcionalidades relacionadas aos documentos do aplicativo como criação, visuzlização, edição e exclusão.
- **Sistema**: Trata sobre as funcionalidades do sistema em si, envolvendo aspectos técnicos e de suporte.

### Épicos

Após a definição dos temas, eles são subdivididos em épicos para tornar as atividades do projeto mais concretas. Para esse projeto, os épicos foram escritos no formato de histórias de usuário e possuem um nível de abstração ainda menor, chamado de *Features*.

### Features

Após a definição de um épico, são geradas *features*, que representam descrições de alto nível das funcionalidades do produto. As *features* são mais conceituais do que as histórias de usuário, pois elas delimitam o que o produto deve realizar, em vez de detalhar como isso deve ser feito.

### Histórias de Usuário

As histórias de usuário refinam ainda mais as features e são abordadas em maior detalhe nas **Tabelas 1 a 6**. Elas consistem em descrições concisas e abstratas de funcionalidades desejadas do ponto de vista do cliente. Geralmente, seguem o formato 
"Eu, como usuário, desejo _______ para _______.".

### Épicos

<details>
   <summary>E01 - Criação de documentos</summary>
   <div><p>Esse épico apresenta as funcionalidades que permite aos usuários criar documentos com configurações específicas (como tipo de folha), com base em modelos pré-definidos (como currículo) ou, simplesmente, um arquivo em branco. A história de usuário a seguir o generaliza:
 "Como usuário típico, eu desejo funcionalidades que me permitam criar documentos com base nas configurações que eu preciso."</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Criação de documentos</td>
        <td>EP01</td>
        <td>
        <ul>
            <li id="ST01">ST01: Eu, como usuário, desejo criar um novo documento utilizando modelos pré-definidos, como currículos, folhetos ou calendários ou até mesmo um documento em branco para economizar tempo e facilitar a formatação do meu conteúdo.</li>
            <li id="ST02">ST02: Eu, como usuário, desejo personalizar as margens do meu documento para atender às minhas necessidades específicas de layout e formato.</li>
            <li id="ST03">ST03: Eu, como usuário, desejo ter a capacidade de selecionar o tamanho de papel do meu documento, como A4, A3, Carta, entre outros, ao criar um novo arquivo, para que eu possa escolher o formato que melhor atende às minhas necessidades de escrita e impressão.</li>
            <li id="ST04">ST04: Eu, como usuário, desejo personalizar o cabeçalho e rodapé do meu documento para  adicionar informações como números de página, datas e outros elementos personalizados que eu julgar necessário</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 1: Épico 1: criação de documentos com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details> 
<br/>


<details>
   <summary>E02 - Estilização do documentos</summary>
   <div><p>Esse épico apresenta as funcionalidades que permite aos usuários estilizarem o documento de acordo com os seus gostos ou necessidades. A história de usuário a seguir o generaliza:

"Como usuário típico, eu desejo modificar o documento de acordo com as minhas preferências."</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Estilização do documentos</td>
        <td>EP02</td>
        <td>
        <ul>
            <li id="ST05">ST05: Eu, como usuário, desejo ter a capacidade de alterar a fonte do texto no meu documento, escolhendo entre uma variedade de opções de fonte para melhorar a aparência do meu conteúdo.</li>
            <li id="ST06">ST06: Eu, como usuário, desejo poder ajustar o tamanho da fonte, aumentando ou diminuindo o tamanho do texto para enfatizar partes específicas do meu documento.</li>
            <li id="ST07">ST07: Eu, como usuário, desejo poder aplicar cores ao texto no meu documento, para destacar informações importantes e melhorar a apresentação visual do meu conteúdo.</li>
            <li id="ST08">ST08: Eu, como usuário, desejo utilizar formatação de texto, como negrito, itálico, sublinhado, tachado, entre outros, para dar ênfase e estilo ao meu texto de acordo com as necessidades do meu projeto.</li>
            <li id="ST09">ST09: Eu, como usuário, desejo poder alinhar o texto no meu documento, incluindo opções de alinhamento à esquerda, à direita, centralizado e justificado, para garantir que o layout do texto se ajuste às minhas preferências e requisitos de design.</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 2: Épico 2: estilização do documento com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details><br/>


<details>
   <summary>E03 - Escrita do documento</summary>
   <div><p>Esse épico apresenta as funcionalidades para uma boa redação do documento de acordo com os seus gostos ou necessidades. A história de usuário a seguir o generaliza:

"Como usuário típico, eu desejo escrever o documento de acordo com as minhas preferências ou necessidades."</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Escrita do documento</td>
        <td>EP03</td>
        <td>
        <ul>
            <li id="ST10">ST10: Eu, como usuário, desejo poder inserir imagens de diversas extensões, como .jpeg, .png, .webp, .svg, etc., no meu documento, para melhorar o conteúdo do texto com elementos visuais.</li>
            <li id="ST11">ST11: Eu, como usuário, desejo a capacidade de inserir listas ordenadas ou não, para estruturar meu texto de maneira clara e organizada.</li>
            <li id="ST12">ST12: Eu, como usuário, desejo inserir tabelas em meu documento, criando e formatando tabelas para apresentar informações de maneira tabular e organizada.</li>
            <li id="ST13">ST13: Eu, como usuário, desejo poder inserir gráficos no meu documento, incorporando representações visuais de dados, como gráficos de barras, pizza, ou linhas, para ilustrar conceitos e informações.</li>
            <li id="ST14">ST14: Eu, como usuário, desejo a capacidade de inserir formas, como setas, retângulos, circunferências, elipses, etc., no meu documento, possibilitando a criação de diagramas e ilustrações personalizadas para complementar o texto.</li>
            <li id="ST15">ST15: Eu, como usuário, desejo contar com uma funcionalidade de autocomplete, que sugira palavras ou frases à medida que digito, para acelerar o processo de escrita e evitar erros de digitação.</li>
            <li id="ST16">ST16: Eu, como usuário, desejo que o LibreOffice Writer verifique automaticamente os erros ortográficos no meu texto, destacando palavras mal escritas ou com erros e fornecendo correções sugeridas.</li>
            <li id="ST17">ST17: Eu, como usuário, desejo receber sugestões para melhorar a escrita do meu texto, incluindo dicas de gramática, estilo e clareza, para aprimorar a qualidade do meu conteúdo.</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 3: Épico 3: escrita do documento com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details><br/>

<details>
   <summary>E04 - Ferramentas do sistema</summary>
   <div><p>Esse épico apresenta as funcionalidades que auxiliam os usuários a realizarem tarefas dentro do sistema através de ferramentas que permite que usuário consigam utilizar o sistema de forma eficaz. A história de usuário a seguir o generaliza:

"Como usuário, eu desejo recursos que me permitam realizar com velocidade tarefas no LibreOffice Writter."
`</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Ferramentas do sistema</td>
        <td>EP04</td>
        <td>
        <ul>
            <li id="ST18">ST18: Eu, como usuário, desejo a capacidade de salvar o documento em meu disco local, armazenando meus trabalhos de forma segura e acessível.</li>
            <li id="ST19">ST19: Eu, como usuário, desejo poder salvar o documento em diversas extensões, como .pdf, .doc, .docx, .odt, .txt, etc., para facilitar o compartilhamento e a compatibilidade com outros softwares.</li>
            <li id="ST20">ST20: Eu, como usuário, desejo ser capaz de editar textos com extensões de softwares concorrentes, como documentos originalmente criados no Word ou Docs, garantindo a interoperabilidade e a edição sem problemas.</li>
            <li id="ST21">ST21: Eu, como usuário, desejo ter ferramentas de pesquisa avançadas que me permitam escolher se a pesquisa deve diferenciar letras maiúsculas e minúsculas, acentos e pesquisar a palavra completa ou parte dela, para encontrar informações com precisão.</li>
            <li id="ST22">ST22: Eu, como usuário, desejo integração com inteligência artificial para realizar pesquisas avançadas, como pesquisa semântica, sugestões contextuais e busca de informações relacionadas ao conteúdo do meu documento.</li>
            <li id="ST23">ST23: Eu, como usuário, desejo a capacidade de usar plugins que se conectem à internet, estendendo as funcionalidades do LibreOffice Writer com extensões que atendam às minhas necessidades específicas.</li>
            <li id="ST24">ST24: Eu, como usuário, desejo que o LibreOffice Writer ofereça ferramentas de acessibilidade, como um leitor de tela e a capacidade de escolher temas que ajudem pessoas com daltonismo a utilizar o software de forma eficaz.</li>
            <li id="ST25">ST25: Eu, como usuário, desejo suporte múltiplos idiomas, com foco nos principais idiomas, como Inglês (US), Português (BR) e Espanhol (América Latina), para atender a uma base de usuários global e diversificada.</li>
            <li id="ST26">ST26: Eu, como usuário, desejo que, ao clicar com o botão direito do mouse em qualquer ferramenta do sistema no LibreOffice Writer, seja exibida uma explicação sucinta daquela ferramenta ou recurso, proporcionando-me informações contextuais e ajudando a entender como usar a funcionalidade de maneira eficaz.</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 4: Épico 4: ferramentas do sistema com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details><br/>

<details>
   <summary>E05 - Integração com a nuvem e configurações de compartilhamentos</summary>
   <div><p>Este épico apresenta funcionalidades que garantem aos usuários a capacidade de compartilhar documentos, juntamente com regras de negócio e integração na nuvem, para evitar erros e atividades indesejadas. A seguinte história do usuário exemplifica isso:
   A história de usuário a seguir o generaliza:

"Como usuário, desejo ter recursos que me permitam salvar documentos na nuvem e controlar como eles são compartilhados."
`</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Integração com a nuvem e configurações de compartilhamentos</td>
        <td>EP05</td>
        <td>
        <ul>
            <li id="ST27">ST27: Eu, como usuário, desejo a capacidade de salvar o documento diretamente em um serviço de nuvem, como o Google Drive, para armazenar meus documentos de forma segura e acessível de qualquer lugar.</li>
            <li id="ST28">ST28: Eu, como usuário, desejo compartilhar o documento por meio de um link, e-mail ou aplicativos de mensagens como o Whatsapp e Telegram, compartilhando meu trabalho de maneira rápida e conveniente com outras pessoas.</li>
            <li id="ST29">ST29: Eu, como usuário, gostaria de ter um sistema de backup contínuo que automaticamente salva versões anteriores do meu documento, para fornecer uma camada extra de segurança contra perda de dados.</li>
            <li id="ST30">ST30: Eu, como usuário, desejo compartilhar o documento com terceiros e ter a capacidade de editar configurações de administrador e colaborador, controlando as permissões de edição e acesso de diferentes usuários.</li>
            <li id="ST31">ST31: Eu, como usuário, desejo que os colaboradores não possam apagar ou exportar o texto sem autorização do administrador, para garantir a integridade do documento compartilhado.</li>
            <li id="ST32">ST32: Eu, como usuário, desejo que o administrador tenha a capacidade de aceitar ou rejeitar as alterações feitas por um colaborador no texto principal, para manter o controle sobre o conteúdo final do documento.</li>
            <li id="ST33">ST33: Eu, como usuário, gostaria de ver versões anteriores do documento, semelhante ao Git no GitHub, permitindo-me acessar e restaurar versões anteriores do meu trabalho, se necessário, para rastrear alterações e evolução ao longo do tempo.</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 5: Épico 5: Operações e segurança com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details><br/>

<details>
   <summary>E06 - Segurança e Operabilidade</summary>
   <div><p>Este épico apresenta requisitos operacionais e requisitos de segurança que garantem aos usuários uma maior variedade de acesso e uso da plataforma de forma segura. A história de usuário a seguir o generaliza:

"Como usuário, desejo acessar a plataforma em determinado sistema operacional de forma segura."
</p> </div>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Segurança e Operabilidade</td>
        <td>EP06</td>
        <td>
        <ul>
            <li id="ST34">ST34: Eu, como usuário, desejo poder definir o nível de confidencialidade do meu documento, escolhendo entre público ou privado, para garantir a segurança das informações contidas no texto.</li>
            <li id="ST35">ST35: Eu, como usuário, desejo proteger o acesso ao documento com uma senha, proporcionando uma camada adicional de segurança, especialmente para documentos com níveis de confidencialidade mais elevados.</li>
            <li id="ST36">ST36: Eu, como usuário, desejo que a plataforma do LibreOffice Writer seja acessível em diversos sistemas operacionais, como Windows, sistemas baseados no modelo Unix/Linux e MacOS, garantindo que eu possa utilizar o software em qualquer ambiente de trabalho.</li>
            <li id="ST37">ST37: Eu, como usuário, desejo poder acessar o LibreOffice Writer em uma plataforma web, criando, editando e colaborando em documentos diretamente no navegador, tornando-o acessível de qualquer lugar.</li>
            <li id="ST38">ST38: Eu, como usuário, espero que o acesso à plataforma web seja responsivo, adaptando-se a diferentes tamanhos de tela e dispositivos, para uma experiência de uso confortável em smartphones, tablets e computadores de mesa.</li>
        </ul>
        </td>
    </tr>
    </table>

<font><div style="text-align: center"><p>Tabela 6: Épico 6: Segurança e operabilidade com a história de usuário.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</details><br/>

## Product Backlog

### Legenda

Para realizar o mapeamento dos requisitos, será utilizada a seguinte legenda na qual contém todos os simbolos necessários para o bom entendimento da <a href="#tabela7">Tabela 7</a>:
> [B: brainstorming](../../elicitacao/tecnicas/brainstorming.md])
>
> C: cenários
>
> E: épico
> 
> [ES: especificação Suplementar](../../modelagem/especificacaoSuplementar.md)
> 
> [INT: introspecção](../../elicitacao/introspeccao.md)
>
> L: léxico
> 
> ST: História de usuário
> 
> UC: caso de uso

<table id="tabela7">
<thead>
  <tr>
    <th>Épico</th>
    <th>Feature</th>
    <th>História de usuário</th>
    <th>Priorização</th>
    <th>Requisitos</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="4" style="vertical-align: middle;">Épico 1 - Criação de documentos</td>
    <td rowspan="2" style="vertical-align: middle;">Feature 1 - Modelos Pré-Definidos</td>
    <td><a href="#ST01"> ST01 </a> - Criar um novo documento utilizando modelos pré-definidos, como currículos, folhetos ou calendários </td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">BS01, INT01</td>
  </tr>
  <tr>
    <td><a href="#ST03"> ST03 </a> - Personalização do documento</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;"> INT02, BS02 </td>
  </tr>
  <tr>
    <td rowspan="2" style="vertical-align: middle;">Feature 2 - Personalização de Cabeçalho e Rodapé</td>
  </tr>
  <tr>
    <td><a href="#ST04"> ST04 </a> - Personalização do documento</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;">INT09, BS02</td>
  </tr>
  <tr>
    <td rowspan="4" style="vertical-align: middle;">Épico 2 - Estilização do documentos</td>
    <td rowspan="2" style="vertical-align: middle;">Feature 3 - Paletas de Cores Personalizadas</td>
    <td><a href="#ST07"> ST07 </a> - Aplicar cores ao documento</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;">INT02, BS02</td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td rowspan="2" style="vertical-align: middle;">Feature 4 - Estilos de Parágrafo e Caracteres Avançados</td>
    <td><a href="#ST08"> ST08 </a> - Opção de formatação de texto</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">INT03, BS02</td>
  </tr>
  <tr>
    <td><a href="#ST09"> ST09 </a> - Alinhamento do texto</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">INT04, BS02</td>
  </tr>
  <tr>
    <td rowspan="7" style="vertical-align: middle;">Épico 3 - Escrita do documento</td>
    <td rowspan="4" style="vertical-align: middle;">Feature 5 - Inserção de imagens, tabelas, gráficos e formas</td>
    <td><a href="#ST10"> ST10 </a> - Inserir imagens</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">INT08, BS07, BS23</td>
  </tr>
  <tr>
    <td><a href="#ST12"> ST12 </a> - Inserir e formatar tabelas</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;">INT08, , BS08</td>
  </tr>
  <tr>
    <td><a href="#ST13"> ST13 </a> - Inserir e formatar gráficos</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;">INT08, BS08</td>
  </tr>
  <tr>
    <td><a href="#ST14"> ST14 </a> - Inserir formas</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;">INT07</td>
  </tr>
  <tr>
    <td rowspan="3" style="vertical-align: middle;">Feature 6 - Auto-completar e corretor automático</td>
    <td><a href="#ST15"> ST15 </a> - Opção de auto-complete</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;"> - </td>
  </tr>
  <tr>
    <td><a href="#ST16"> ST16 </a> - Verificador de erros ortográficos</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;">INT10, BS04, USA03</td>
  </tr>
  <tr>
    <td><a href="#ST17"> ST17 </a> - Sugestões de melhoria da escrita do texto</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;"> - </td>
  </tr>
  <tr>
    <td rowspan="5" style="vertical-align: middle;">Épico 4 -  Ferramentas do sistema</td>
    <td rowspan="3" style="vertical-align: middle;">Feature 8 -  Conexão e compatibilidade com outros sistemas e softwares</td>
    <td><a href="#ST19"> ST19 </a> - Salvar documentos com extensões diversas</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">INT14, BS03</td>
  </tr>
  <tr>
    <td><a href="#ST20"> ST20 </a> - Editar textos vindos de outros softwares</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;">INT20, SUP02</td>
  </tr>
  <tr>
    <td><a href="#ST23"> ST23 </a> - Plugins que se conectem a internet</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;"> - </td>
  </tr>
  <tr>
    <td rowspan="2" style="vertical-align: middle;">Feature 9 - Acessibilidade</td>
    <td><a href="#ST24"> ST24 </a> - Ferramentas de acessibilidade para, por exemplo, baixa visão, daltonismo e surdez</td>
    <td style="vertical-align: middle;">Alta</td>
        <td style="vertical-align: middle;"> INT28, BS17, USA02, USA04</td>
  </tr>
  <tr>
    <td><a href="#ST26"> ST26 </a> - Suporte para múltiplos idiomas</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;">INT17, BS14</td>
  </tr>
  <tr>
    <td rowspan="5" style="vertical-align: middle;">Épico 5 - Integração com a Nuvem e Configurações de Compartilhamento</td>
    <td rowspan="3">Feature 10 -  Opções de salvar o documento</td>
    <td><a href="#ST29"> ST29 </a> - Sistema de backup</td>
    <td style="vertical-align: middle;">Alta</td>
                <td style="vertical-align: middle;">INT27, CONF04, SUP04</td>
  </tr>
  <tr>
    <td><a href="#ST27"> ST27 </a> - Salvar o documento na nuvem</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;"> BS15, BS24 </td>
  </tr>
  <tr>
    <td><a href="#ST33"> ST33 </a> - Acessar e restaurar versões anteriores</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;">INT26, SUP03</td>
  </tr>
  <tr>
    <td rowspan="2">Feature 11 -  Compartilhamentos</td>
    <td><a href="#ST30"> ST30 </a>- Compartilhar um documento com terceiros e ter acesso as modificações</td>
    <td style="vertical-align: middle;">Alta</td>
            <td style="vertical-align: middle;"> INT19, BS15</td>
  </tr>
  <tr>
    <td><a href="#ST34"> ST34 </a> - Limitar as modificações feitas por terceiros</td>
    <td style="vertical-align: middle;">Média</td>
            <td style="vertical-align: middle;"> - </td>
  </tr>
  <tr>
    <td rowspan="7" style="vertical-align: middle;">Épico 6 - Segurança e Operabilidade</td>
    <td rowspan="2">Feature 8 -  Autenticação Segura</td>
    <td><a href="#ST34"> ST34 </a> - Definir o nível de confidencialidade do documento</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;">INT22</td>
  </tr>
  <tr>
    <td><a href="#ST35"> ST35 </a> - Proteger o acesso com senha</td>
    <td style="vertical-align: middle;">Alta</td>
            <td style="vertical-align: middle;">INT22</td>
  </tr>
  <tr>
    <td rowspan="7">Feature 9 - Compatibilidade</td>
    <td><a href="#ST36"> ST36 </a> - Compatibilidade com diversos sistemas operacionais</td>
    <td style="vertical-align: middle;">Alta</td>
            <td style="vertical-align: middle;">INT21, BS27</td>
  </tr>
  <tr>
    <td><a href="#ST37"> ST37 </a> - Possibilidade de uso em plataforma web</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;"> - </td>
  </tr>
  <tr>
    <td><a href="#ST38"> ST38 </a> - Responsividade na plataforma de edição web</td>
    <td style="vertical-align: middle;">Baixa</td>
            <td style="vertical-align: middle;">BS27</td>
  </tr>
</tbody>
</table>

<font><div style="text-align: center"><p>Tabela 7: Product Backlog Elaborado com o Product Owner.<br/> (Fonte: Edilberto Almeida Cantuaria e Ana Letícia Melo Pereira, 2023)</p></div></font>

</center>

### Validação do cliente
 A fim de confirmar os requisitos elicitados, gravou-se um vídeo com um cliente que possui o seguinte perfil:

**Perfil do cliente entrevistado**

```
Idade: 20 anos;
Ocupação: estudante universitário e estagiário;
Região: Brasília-DF;
Experiência com dispositivos eletrônicos (tablets, smartphones, computadores, etc.): muita experiência;
Sistemas Operacionais: Windows, Linux, Android, iOS;
Usa o LibreOffice Writter com frequência.
Usa aplicação semelhante de uma empresa concorrente com frequência.
```
Este perfil converge com a maioria dos dados coletados no [Questionário](../elicitacao/questionario.md).

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/PQ4U2_Tz210?si=DrgP8hEo9Vh0oXrX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<div style="text-align: center">
<p> Gravação 1: Inspeção do documento. (Fonte: Edilberto Cantuaria, 2023). </p>
</div>

</center>



## Referências Bibliográficas

> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 46 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 06 de nov. 2023.
>

## Bibliografia


> CARNEIRO, Caio Vitor. Especificação Suplementar. Repositório do Grupo Grasshopper da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Grasshopper/modelagem/especificao-suplementar/>>. Acesso em: 06 de nov. 2023.

> FERREIRA, Rafaela. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/especificacao-suplementar.md>>. Acesso em: 06 de nov. 2023


> MATIAS, Davi. Especificação Suplementar. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/especificacao_suplementar/>>. Acesso em: 06 de nov. 2023.

> PERILLO, Matheus. Especificação Suplementar. Repositório do Grupo TikTok da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/especificao-suplementar.md>>. Acesso em: 06 de nov. 2023.

> SALES, Wildemberg; Repositório do Grupo Grasshopper da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<hhttps://github.com/Requisitos-de-Software/2022.2-Grasshopper/blob/main/docs/modelagem/especificao-suplementar.md/>>. Acesso em: 06 de nov. 2023.

> SANTOS, Eduardo; Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/EspecificacaoSuplementar/>>. Acesso em: 06 de nov. 2023.
## Histórico de Versão

| Versão | Data       | Descrição                                | Autor(es)                         | Revisor(es)           |
| ------ | ---------- | ---------------------------------------- | --------------------------------- | --------------------- |
| 1.0    | 06/11/2023 | Criação do documento.                    | Edilberto Cantuaria , Ana Letícia | Artur Seppa, Raphaela |
| 1.1    | 06/11/2023 | Atualização das referências das tabelas. | Artur Seppa Reiman                | Raphaela              |
| 1.2    | 06/12/2023 | Correção do documento                    | Artur Seppa Reiman                | Raphaela              |
