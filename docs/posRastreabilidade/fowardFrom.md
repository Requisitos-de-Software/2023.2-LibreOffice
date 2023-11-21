## Introdução

"O rastreamento de requisitos é utilizado para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema e possibilita uma adequada compreensão dos relacionamentos de dependência entre requisitos e através dos artefatos de requisitos, de arquitetura e de implementação." (SAYÃO; LEITE, 2005)<br>
Apresentaremos nesse documento a técnica de pós-rastreabilidade "Forward-from", que tem como objetivo "ligar requisitos a artefatos de desenho e implementação" (SAYÃO; LEITE, 2005)

## Metodologia

Faremos a rastreabilidade dos requisitos priorizados como "Must" na nossa tabela de priorização [MoSCoW](https://requisitos-de-software.github.io/2023.2-LibreOffice/elicitacao/priorizacao/moscow/), fazendo uma demonstração da sua funcionalidade e elaborando uma tabela para cada requisito para explicitar seu épico, feature, por que meio foi elicitado e sua identificação.

## Pós-Rastreabilidade

### Matriz de Rastreabilidade

**Legenda:** 

> - RF: Requisito funcional
> - RNF: Requisito não funcional
> - BS: Brainstorm
> - INT: Instrospecção

</br>

| ID   | Requisito |
| ---- | ------------------------------------------------------------------------------------------------------------------------ |
|<a href="#RF01">RF01(INT02)</a> | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte
| <a href="#RF02">RF02(INT03)</a>| Deve ser possível aplicar estilos de formatação de fonte, como negrito, itálico, sublinhado, tachado, sobrescrito e subscrito
| <a href="#RF03">RF03(INT04)</a>| O usuário deve ter a opção de alinhar o texto: centralizar, justificar, alinhar à direita ou alinhar à esquerda
| <a href="#RF04">RF04(INT05)</a>| O software deve permitir a criação de tópicos ordenados (numeração, letras), não ordenados (marcadores) e seus subtópicos
| <a href="#RF05">RF05(INT06)</a>| Deve ser possível aumentar ou diminuir o recúo, bem como regular o espaçamento entre linhas e o espaço entre parágrafos
| <a href="#RF06">RF06(INT20)</a> | O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo
| <a href="#RNF01">RNF01(INT21)</a>| O software deve ser portável, funcionando em diferentes sistemas operacionais, como Windows, macOS e Linux	
| <a href="#RF07">RF07(BS01)</a> |  O usuário deve poder criar documentos de texto.
| <a href="#RF08">RF08(BS02)</a>| O usuário deve poder editar documentos de texto
| <a href="#RF09">RF09(BS03)</a>| O usuário deve poder salvar documentos em vários formatos, incluindo ODF, .doc, e HTML.
| <a href="#RF10">RF10 (BS05)</a> | O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas.
| <a href="#RF11">RF11(BS06)</a> | O usuário deve poder criar índices e sumários em documentos de texto.
| <a href="#RF12">RF12(BS12)</a>|  O usuário deve poder acessar um sistema de Ajuda na rede abrangente.
| <a href="#RF13">RF13(BS21)</a>|  O usuário deve ter a capacidade de editar documentos offline para facilitar o trabalho sem conexão à internet.

<font size="3"><p style="text-align: center">Tabela 1: Matriz de rastreabilidade (Fonte: Rafael Xavier, 2023)</p></font>

### Especificações

<a id="RF01">**RF01**</a>

|        RF01(INT02)   | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  [E02 - Estilização do documentos]((https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/))  |
|       Feature       |  [FT03, FT04](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
| História de Usuário | [US07, US08, US09](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  [Video](https://youtu.be/DSSUF2rwC6Q) |

<a id="RF02">**RF02**</a>

|        RF02(INT03)   | Deve ser possível aplicar estilos de formatação de fonte, como negrito, itálico, sublinhado, tachado, sobrescrito e subscrito. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  2 - Estilização do documento  |
|       Feature       |  4 - Estilos de Parágrafo e Caracteres Avançados |
| História de Usuário | [US08](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  --- |

<a id="RF03">**RF03**</a>

|        RF03(INT04)   | O usuário deve ter a opção de alinhar o texto: centralizar, justificar, alinhar à direita ou alinhar à esquerda. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  2 - Estilização do documento  |
|       Feature       | 4 - Estilos de Parágrafo e Caracteres Avançados |
| História de Usuário | [US08](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  --- |

<a id="RF04">**RF04**</a>

|       RF04(INT05)   | O software deve permitir a criação de tópicos ordenados (numeração, letras), não ordenados (marcadores) e seus subtópicos. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  2 - Estilização do documento  |
|       Feature       |  4 - Estilos de Parágrafo e Caracteres Avançados |
| História de Usuário | [US09](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  --- |

<a id="RF05">**RF05**</a>

|        RF05(INT06)   | Deve ser possível aumentar ou diminuir o recúo, bem como regular o espaçamento entre linhas e o espaço entre parágrafos. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  2 - Estilização do documento  |
|       Feature       |  4 - Estilos de Parágrafo e Caracteres Avançados |
| História de Usuário | [US09](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  --- |

<a id="RF06">**RF06**</a>

|     RF06(INT20)     | O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E06 - Segurança e Operabilidade](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT10 - Opções de salvar o documento](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US27, US29, US33](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |                                                      [Vídeo]()                                                       |

<a id="RNF01">**RNF01**</a>

|    RNF01(INT21)     |O software deve ser portável, funcionando em diferentes sistemas operacionais, como Windows, macOS e Linux |
| :-----------------: | :------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E06 - Segurança e Operabilidade](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT09 - Compatibilidade](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US36](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |                                                      Requisitos do sistema para instalar o LibreOffice ([página do fabricante aqui](https://pt-br.libreoffice.org/ajuda/requisitos-dos-sistemas/))                                                       |


<a id="RF07">**RF07**</a>

|     RF07(BS01)      | O usuário deve poder criar documentos de texto. |
| :-----------------: | :------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E01 - Criação de documentos](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT01 - Modelos Pré-Definidos](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US01](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |                                                      [Vídeo](https://drive.google.com/file/d/1_FjjjTvU_NuqbvIpja-NqJGRHgjgrO1a/view?usp=drive_link)                                                    |

<a id="RF08">**RF08**</a>

|     RF08(BS02)      |O usuário deve poder editar documentos de texto |
| :-----------------: | :------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E04 - Ferramentas do sistema](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT08 - Conexão e compatibilidade com outros sistemas e softwares](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US20](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |                                                      [Vídeo](https://drive.google.com/file/d/1Umv_IUOkzqeleZCbAqhe9BxtI7B7wnRk/view?usp=drive_link)                                                         |

<a id="RF09">**RF09**</a>

|     RF09(BS03)      | O usuário deve poder salvar documentos em vários formatos, incluindo ODF, .doc, e HTML. |
| :-----------------: | :------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E04 - Ferramentas do sistema](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT08 - Conexão e compatibilidade com outros sistemas e softwares](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US19](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |                                                      [Vídeo](https://drive.google.com/file/d/1Ybt82IIX3TOidIac5OAE_gN9t0KcwnWf/view?usp=drive_link)                                                     |

<a id="RF10">**RF10**</a>

|     RF10 (BS05)     | O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas. |
| :-----------------: | :------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                    [E02 - Estilização do documentos](https://github.com/Requisitos-de-Software/2023.2-LibreOffice/blob/77-forward-from/docs/modelagem/agil/backlog.md)                                                    |
|       Feature       |   [FT04 - Estilos de Parágrafo e Caracteres Avançados](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)                                                                                |
| História de Usuário |          [US08, US09](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/)           |
|    Demonstração     |[Vídeo](https://drive.google.com/file/d/1VTLXJ2g7FJ_K25yYWdq1eSEW3HXScAtK/view?usp=drive_link)                                 |


<a id="RF11">**RF11**</a>

|        RF11(BS06)   | O usuário deve poder criar índices e sumários em documentos de texto. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  [E03 - Escrita do documento](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|       Feature       |  --- |
| História de Usuário | --- |
|   Demonstração    |  [video](https://youtu.be/9KvXCWzDVu4) |


<a id="RF12">**RF12**</a>

|        RF12(BS12)   | O usuário deve poder acessar um sistema de Ajuda na rede abrangente.|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  [E04 - Ferramentas do sistema](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|       Feature       |  [FT09 -  Acessibilidade](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
| História de Usuário | [US26](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  [---]() |


<a id="RF13">**RF13**</a>

|        RF13(BS21)   | O usuário deve ter a capacidade de editar documentos offline para facilitar o trabalho sem conexão à internet.|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  [E04 - Ferramentas do sistema](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|       Feature       |  [FT09 -  Acessibilidade](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
| História de Usuário | --- |
|   Demonstração    |  [---]() |



## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 23 de agosto 2022.
>
> POHL, Klaus; RUPP, Chris. Requirements Engeneering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam Foundation Level / IREB compliant. 1. ed. [S. l.]: O'Reilly Media, Inc., 2011. 183 p.
>
> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. 2005. 26 f. Tese (Doutorado) - Curso de Ciência da Computação, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005.


## Histórico de Versões

Versão  |   Data    | Descrição | Autor(es) | Revisor(es)
--------- | ------- | ------ | ---------- | ----------
 1.0 | 20/11/2023 | Criação do documento | Rafael | Edilberto e Rapahela
 1.1 | 20/22/2023 | Adição das especificações | Edilberto, Rafael , Raphaela | 