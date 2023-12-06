# Introspecção

## Introdução

O presente documento apresenta os requisitos elicitados por meio da técnica de introspecção. De acordo com o DICIO (Dicionário Online de Português) [1], o vocábulo **introspecção** significa:

> Análise íntima e reflexiva que alguém faz sobre si mesmo.

> Exame profundo sobre as próprias experiências ou sobre o que ocorre de mais íntimo em si próprio; introversão.

> `Psicologia` Análise observativa e descritiva sobre os conteúdos da própria mente.


Ainda, segundo Maurício e Milene Serrano [2], a introspecção é uma técnica de elicitação rica e profunda, consistindo basicamente em um engenheiro de requisitos entender quais propriedades são desejáveis para o sistema possuir sucesso. Toda a análise é feita com o engenheiro pensando em como desempenhar uma tarefa de forma satisfatória com determinados recursos e ferramentas. Apesar de ser muito útil, essa técnica possui um grande problema: um especilista da área pode não refletir a experiência que um usuário real teria na utilização do sistema, podendo gerar dados errôneos. Por outro lado, se utilizada em conjunto com outras técnicas, pode ser muito útil para ajudar a complementar as outras metodologias.

Assim, a finalidade da elicitação de requisitos através da técnica de introspecção consiste em listar os requisitos fundamentais do sistema a partir da perspectiva dos participantes durante um momento de introspecção.


## Metodologia para a elicitação de requisitos através da introspecção

A abordagem da introspecção na elicitação de requisitos é um método que envolve uma análise pessoal e profunda para identificar o que é essencial para um software de determinada natureza. Nesse contexto, o responsável por aplicar essa estratégia deve imaginar uma situação hipotética na qual uma tarefa específica seria executada.

### Perfil do Engenheiro de Requisitos
O Engenheiro de Requisitos responsável pela introspecção apresenta o seguinte perfil:


```
Idade: 25 anos;
Ocupação: estudante universitário e estagiário;
Reegião: Brasília-DF;
Experiência com dispositivos eletrônicos (tablets, smartphones, computadores, etc.): muita experiência;
Sistemas Operacionais: Windows, Linux e Android;
Usa o LibreOffice Writter com alguma frequência.
Usa aplicação semelhante de uma empresa concorrente com frequência.
```
Este perfil converge com a maioria dos dados coletados no [Questionário](../elicitacao/questionario.md).



## Realizando a introspecção

### Planejamento
A técnica foi aplicada em um local com as seguintes características:
* Ambiente: sala fechada com uma boa iluminação natural e temperatura confortável;
* Horário: de manhã, aproximadamente às 10 horas.
* Cronograma: dia 01/10/2023, de acordo com a data prevista e dentro do prazo da entrega.
* Situação hipotética: escrita de um artigo acadêmico, imaginando desde o momento em que o usuário incializa o LibreOffice Writter até sua versão final e imaginando algumas falhas durante a atividade. 

### Execução
Aplicando a técnica para o software LibreOffice Writer obteve-se os resultados que estão registrados a seguir que apresenta os cenários de utilização do sistema e o comportamento esperado.

|                  Cenário de uso | Observações                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Abertura do aplicativo**      | A tela inicial deve apresentar um documento em branco pronto para ser editado ou alguns modelos disponíveis, como: convite, currículos, calendário, etc.                                                                                                                                                                                                                                                                                           |
| **Formatação do texto (fonte)** | Ao escrever um texto ou abrir um arquivo pré-existente, pode-se alterar a fonte, seu tamanho, além de poder realçar o texto colocando-o em negrito, itálico, sublinhado, tachado e a cor de realce.                                                                                                                                                                                                                                                 |
| **Formatação do texto (corpo)** | Deve possibilitar que o usuário escolha o alinhamento do texto (centralizado, justificado, à esquerda, à direita), bem como aumentar e reduzir o tamanho do recuo e personalizar o tamanho das margens.                                                                                                                                                                                                                                             |
| **Inserção de arquivos**        | Deve possibilitar a inclusão de imagens, hiperlinks e conteúdo textual de outras fontes (como páginas web e PDFs) ou de outra parte do mesmo arquivo.                                                                                                                                                                                                                                                                                             |
| **Salvar arquivos**             | O usuário pode salvar o arquivo com diversas extensões.                                                                                                                                                                                                                                                                                                                                                                                         |
| **Compatibilidade**             | Deve ser compatível com os sistemas operacionais mais amplamente utilizados no mercado.                                                                                                                                                                                                                                                                                                                                                        |
| **Usabilidade**                 | O tempo de resposta do aplicativo deve estar diretamente relacionado ao tamanho do arquivo gerado. Portanto, é natural que um documento contendo várias imagens e tabelas leve mais tempo para processar do que um simples texto com uma única frase. Além disso, o aplicativo deve incorporar medidas de prevenção contra falhas, como a funcionalidade de salvamento automático.                                                                                                                                            
<div style="text-align: center">
<p> Tabela 1: Registro da introspecção (Fonte: Edilberto Almeida Cantuaria, 2023).</p>
</div>


#### Parecer do Avaliador 

Durante o uso do software, foi possível identificar as principais ferramentas que fazem parte da edição e criação de um arquivo de texto. Porém as divisões que os ícones aparecem não colaboram para um melhor aproveitamento do usuário, uma vez que a página contém diversos itens, alguns deles até mesmo em que o usuário já está habituado a utilizar os atalhos como, por exemplo, o recortar, copiar e colar que já possuem os atalhos `ctrl+x`, `ctrl+c` e `ctrl+v`. Além do mais, para uma edição mais robusta, com a inserção de sumários, numeração de figuras e tabelas, acaba não sedo indicado por dar retrabalho ao usuário: figuras e tabelas saem do local que foi colocado, a numeração acaba saindo de ordem ao incluir ou excluir uma figura ou tabela.


### Requisitos elicitados (documentação):

A partir das observações descritas acima, foram elicitados os requisitos da sessão de introspecção representados na tabela a seguir. O identificador de cada requisito é formado por INT + um número, sendo INT uma abreviação de introspecção, e o tipo de requisito refere-se a classificação entre requisitos funcionais (RF) e não funcionais (RNF).


#### Acesso ao aplicativo

Ao abrir o aplicativo deve aparecer uma tela com um documento em branco pronto para ser editado;

#### Ao escrever ou editar um texto

Possuir ferramentas/opções:
 
- Para formatar o texto, tais como:
  - Alterar o tamanho da fonte;
  - Alterar a cor do texto;
  - Realçar o texto com uma cor em específica;
  - Ferramentas de estilização da fonte (negrito, itálico, sublinhado, tachado e outras fontes);
  - Opções de adicionar sobrescrito e subscrito;

- Alinhamento do texto: 
  - à direita;
  - centralizar;
  - justificar;
  - à esquerda;

- Criar tópicos ordenados (numeração, letras), não ordenados ("bolinhas" e outros símbolos) e seus subtópicos;

- Aumentar ou diminuir recúo, bem como regular o espaçamento entrelinhas e espaço entre parágrafos;

- Inserir desenhos e formas geométricas (como retas, setas, círculos, elipses, quadrados, retângulos, etc. );

- Possibilitem a inclusão de arquivos de mídia, gráficos, tabelas e caixa de texto;

- Inserir hiperlinks, nota de rodapé, nota de fim, marca-página, referência cruzada, anotações (comentários);

- Verificar a ortografia;

- Localizar e substituir partes do texto;

- Quebra de página, símbolos e equações;
  
- Visualizar a impressão e imprimir;
  
- Abrir um arquivo já existente;

- Salvar o arquivo em, pelo menos, quatro extensões:
  - `.pdf`
  - `.odt`
  - `.docx`
  - `.txt` 


#### Requisitos obtidos com a técnica Introspecção

<center>



| Identificador | Requisito                                                                                                                                                                         | Tipo  |
| :-----------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---: |
|     INT01     | Ao abrir o aplicativo, deve aparecer uma tela com um documento em branco pronto para ser editado                                                                                  |  RF   |
|     INT02     | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo, o tamanho da fonte, bem como o tamanho do papel (A4, A3, Carta, entre outros)                                                                 |  RF   |
|     INT03     | Deve ser possível aplicar estilos de formatação de fonte, como negrito, itálico, sublinhado, tachado, sobrescrito, subscrito, escolher cores, etc.                                                   |  RF   |
|     INT04     | O usuário deve ter a opção de alinhar o texto: centralizar, justificar, alinhar à direita ou alinhar à esquerda                                                                   |  RF   |
|     INT05     | O software deve permitir a criação de tópicos ordenados (numeração, letras), não ordenados (marcadores) e seus subtópicos                                                         |  RF   |
|     INT06     | Deve ser possível aumentar ou diminuir o recúo, bem como regular o espaçamento entre linhas e o espaço entre parágrafos                                                           |  RF   |
|     INT07     | O software deve permitir a inserção de desenhos e formas geométricas, como retas, setas, círculos, elipses, quadrados, retângulos, etc.                                           |  RF   |
|     INT08     | Deve ser possível incluir arquivos de mídia, gráficos, tabelas e caixas de texto ao longo do documento que está sendo editado                                                     |  RF   |
|     INT09     | Deve ser possível inserir hiperlinks, notas de rodapé, notas de fim, marca-páginas, referências cruzadas e anotações (comentários)                                                |  RF   |
|     INT10     | Deve haver um mecanismo para verificar a ortografia do texto                                                                                                                      |  RF   |
|     INT11     | Deve ser possível localizar e substituir partes do texto no documento                                                                                                             |  RF   |
|     INT12     | O software deve permitir a visualização da impressão e a impressão do documento                                                                                                   |  RF   |
|     INT13     | Deve ser possível abrir um arquivo já existente no formato apropriado                                                                                                             |  RF   |
|     INT14     | O usuário deve ter a capacidade de salvar o arquivo em pelo menos quatro extensões: `.pdf`, `.odt`, `.docx` e `.txt`                                                              |  RF   |
|     INT15     | Deve ser possível inserir quebras de página, permitindo ao usuário controlar a formatação do documento                                                                            |  RF   |
|     INT16     | Deve ser possível inserir símbolos especiais e equações matemáticas no texto                                                                                                      |  RF   |
|     INT17     | O software deve oferecer suporte a múltiplos idiomas, permitindo a edição de documentos em diferentes línguas                                                                     |  RF   |
|     INT18     | O software deve permitir o controle de revisões, rastreando as alterações feitas no documento ao longo do tempo e possibilitando a aceitação ou rejeição das revisões             |  RF   |
|     INT19     | Deve ser possível colaborar em documentos em tempo real com outros usuários, permitindo a edição simultânea de um documento compartilhado                                         |  RF   |
|     INT20     | O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo                                         |  RF   |
|     INT21     | O software deve ser portável, funcionando em diferentes sistemas operacionais, como Windows, macOS e Linux                                                                        |  RNF  |
|     INT22     | O LibreOffice Writer deve garantir a segurança dos documentos do usuário, incluindo a capacidade de criptografar documentos sensíveis e proteger com senha o acesso a arquivos    |  RNF  |
|     INT23     | O software deve ser acessível a pessoas com deficiências, atendendo a padrões de acessibilidade e oferecendo suporte a leitores de tela e outras tecnologias assistivas           |  RNF  |
|     INT24     | O LibreOffice Writer deve ser eficiente em termos de consumo de recursos do sistema, como CPU e memória, para garantir um desempenho responsivo mesmo em sistemas menos poderosos |  RNF  |
|     INT25     | Deve haver documentação abrangente disponível para os usuários, além de suporte técnico eficaz, incluindo fóruns, tutoriais e recursos de ajuda                                   |  RNF  |
|     INT26     | O software deve ser capaz de abrir documentos criados em versões anteriores do LibreOffice Writer sem perda significativa de formatação ou conteúdo                               |  RNF  |
|     INT27     | Deve ser possível configurar facilmente opções de backup e restauração de documentos para evitar perda de dados acidental                                                         |  RNF  |
|     INT28     | Os usuários devem ter a capacidade de personalizar a interface do LibreOffice Writer de acordo com suas preferências                                                              |  RNF  |
|     INT29     | O software deve promover o uso de formatos de arquivo abertos e padrões abertos para garantir a interoperabilidade com outros aplicativos e evitar bloqueio de fornecedor         |  RNF  |
|     INT30     | O LibreOffice Writer deve ser tolerante a falhas, minimizando o impacto de erros do usuário ou falhas do sistema                                                                  |  RNF  |



<font><p style="text-align: center">Tabela 2: Requisitos elicitados. (Fonte: Edilberto Almeida Cantuaria, 2023).</p></font>


</center>

### Confirmação
 A fim de confirmar os requisitos elicitados, gravou-se um vídeo com um cliente que possui o seguinte perfil:

**Perfil do cliente entrevistado**

```
Idade: 24 anos;
Ocupação: estudante universitário e estagiário;
Reegião: Valparaíso-GO;
Experiência com dispositivos eletrônicos (tablets, smartphones, computadores, etc.): muita experiência;
Sistemas Operacionais: Windows, Linux e Android;
Usa o LibreOffice Writter com alguma frequência.
Usa aplicação semelhante de uma empresa concorrente com frequência.
```
Este perfil converge com a maioria dos dados coletados no [Questionário](../elicitacao/questionario.md).

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/PQ4U2_Tz210?si=DrgP8hEo9Vh0oXrX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<div style="text-align: center">
<p> Gravação 1: Inspeção do documento. (Fonte: Edilberto Cantuaria, 2023). </p>
</div>

</center>



## Referências
[1] DICIO: Dicionário Online de Português, disponível no [link](https://www.dicio.com.br/introspeccao/), acesso em out. 2023.

[2] SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível [clicando aqui](https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em: out. 2023.

## Histórico de Versão

| Versão | Data       | Descrição             | Autor | Revisor   |
| ------ | ---------- | --------------------- | ------------------------------- | ------------- |
| `1.0`  | 01/10/2023 | Criação do documento. | Edilberto Cantuaria             | Rafael Xavier |
| `1.1`  | 06/12/2023 | Correção do documento. | Edilberto Cantuaria             | Rafael Xavier |
