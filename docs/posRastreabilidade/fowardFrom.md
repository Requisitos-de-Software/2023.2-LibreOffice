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
|        Épico        |  Alterar  |
|       Feature       |  Alterar fonte, cor, tamanho |
| História de Usuário | [EP02](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/agil/backlog/) |
|   Demonstração    |  --- |


## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 23 de agosto 2022.
>
> POHL, Klaus; RUPP, Chris. Requirements Engeneering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam Foundation Level / IREB compliant. 1. ed. [S. l.]: O'Reilly Media, Inc., 2011. 183 p.
>
> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. 2005. 26 f. Tese (Doutorado) - Curso de Ciência da Computação, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005.


## Histórico de Versões

Versão  |   Data    | Descrição | Autor(es) | Revisor(es)
--------- | ------- | ------ | ---------- | ----------
 1.0 | 20/11/2023 | Criação do documento | Rafael | a definir