# Matriz Geral

## Introdução
Esse artefato tem por objetivo associar os resultados obtidos na rastreabilidade [_Forward-from_](/docs/posRastreabilidade/fowardFrom.md)
e na rastreabilidade [_Backward-from_](/docs/posRastreabilidade/backwardFrom.md) através de uma matriz geral de rastreabilidade.

## Metodologia
A abordagem utilizada envolve a criação de uma tabela com 5 colunas, conforme descritas abaixo, que têm o objetivo de apresentar os dados do requisito de forma estruturada e resumida.

### Colunas a serem incluídas na tabela de rastreabilidade:
- ID: Identificação do requisito;
- Descrição: Breve explicação do requisito;
- Origem: Método que o requisito foi elicitado;
- Artefatos: Documentos/Artefatos relacionados ao requisito;
- Implementação: Descreve o status de implementação do requisito após a conclusão do projeto.

### Mapeamento

Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o
bom entendimento dos tópicos abaixo:

<center>

| Legenda | Artefato                  |
| ------- | ------------------------- |
| E       | Épico                     |
| P       | Personas                  |
| US      | Histórias de usuário      |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| Q       | Questionário              |
| GLO     | Glossário                 |
| B       | Brainstorming             |
| ENT     | Entrevista                |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

</center>

<div style="text-align: center">
  <p> Tabela 1: Sigla de cada etapa (Fonte: Ana Letícia, 2023).</p>
</div>

## Matriz Geral
A matriz geral pode ser observada na _Tabela 1_ a seguir.

| ID | Descrição | Origem | Artefatos | Implementação |
| -- | --------- | ------ | --- |--- |
| RF01 | O usuário deve ter a capacidade de salvar o arquivo em pelo menos quatro extensões: .pdf, .odt, .docx e .txt | INT14 | E03 US11  | Implementado |
| RF02 | Deve ser possível inserir quebras de página, permitindo ao usuário controlar a formatação do documento | INT15 | E03 US15 US16 US17  | Implementado |
| RF03 | Deve ser possível inserir símbolos especiais e equações matemáticas no texto | INT16 | UC02 L06 E04 US20  | Implementado |
| RF04 | O software deve oferecer suporte a múltiplos idiomas, permitindo a edição de documentos em diferentes línguas | INT17 | L14  | Implementado |
| RF05 | O software deve permitir o controle de revisões, rastreando as alterações feitas no documento ao longo do tempo e possibilitando a aceitação ou rejeição das revisões | INT18 | L07  | Implementado |
| RF06 | Deve ser possível colaborar em documentos em tempo real com outros usuários, permitindo a edição simultânea de um documento compartilhado | INT19 | C10 E05 US27  | Implementado |
| RF07 |  O software deve ser capaz de recuperar automaticamente documentos em caso de falha, como uma queda de energia ou travamento do aplicativo. | INT20 | US05 C02  | Implementado |
| RF08 | O usuário deve poder editar documentos de texto. | BS02 | 	UC02 L06 E04 US20  | Implementado |
| RF09 | O usuário deve poder criar estilos para parágrafos, caracteres individuais, quadros e páginas. | BS05 | INT06 E02 US05 C02  | Implementado |
| RF10 | O usuário deve poder criar índices e sumários em documentos de texto. | BS06 | L07  | Implementado |
| RF11 | O usuário deve poder personalizar a interface do programa, incluindo ícones e menus. | BS10 | INT28 C09 L10  | Implementado |
| RF12 | O usuário deve poder utilizar uma função de voz para ouvir o texto lido em voz alta, especialmente útil para usuários com deficiência visual. | BS22 | L04 E02 US08  | Implementado |
| RF13 | O software deve fornecer ferramentas/opções para formatar o texto, como alterar o estilo e o tamanho da fonte. | INT02 | L04 E02 US08  | Implementado |
| RF14 | O software deve permitir a criação de tópicos ordenados, não ordenados e seus subtópicos no texto. | INT05 | E03 US11  | Implementado |
| RF15 | Deve ser possível modificar o recúo regular o espaçamento entre linhas e o espaço entre parágrafos. | INT06 | E02 US09  | Implementado |
| RF16 | Deve ser possível incluir anexos de mídia, gráficos, tabelas, além de poder efetuar a construção deles no documento. | INT08 | L03 L09 L13 E03 US10 US12 US13 US14  | Implementado |
| RF17 | Deve haver um mecanismo para verificar e ajustar a ortografia do texto. | INT10 |  E03 US15 US16 US17  | Implementado |
| RNF01 | O software deve ser portável | INT21 |  E03 US15 US16 US17  | Implementado |
| RNF02 | O software deve garantir a segurança dos documentos do usuário com senha e criptografia. | INT22 |  E03 US15 US16 US17  | Implementado |
| RNF03 | O software deve ser eficiente em termos de consumo de recursos do sistema, como CPU e memória, para garantir um desempenho responsivo mesmo em sistemas menos poderosos. | INT24 |  E03 US15 US16 US17  | Implementado |
| RNF04 | O aplicativo deve ser compatível com sistemas mobile. | BS27 |  E03 US15 US16 US17  | Implementado |
| RNF05 | O aplicativo deve ser capaz de se integrar de forma eficaz com serviços de armazenamento em nuvem para facilitar o compartilhamento e o acesso a documentos. | BS24 |  C10 E05 US27  | Implementado |
| RNF06 | O LibreOffice Writer deve funcionar de forma eficiente, mesmo em documentos longos e complexos. | BS25 |  C10 E05 US27  | Implementado |
| RNF07 | Deve ser acessível para pessoas com deficiência, seguindo diretrizes de acessibilidade para facilitar o uso por leitores de tela e outras tecnologias assistivas. | BS26 |  INT23 E04 US24  | Implementado |
| RNF08 | Deve ser assegurado a existência de uma infraestrutura de suporte aos usuários, contendo uma documentação abrangente, suporte técnico e recursos adicionais, tais como fóruns, tutoriais e mecanismos de ajuda.| INT25 | L14  | Implementado |

Tabela 1: Matriz-Geral de Rastreabilidade (Fonte: Raphaela Guimarães, 2023).

## Bibliografia

> Leite, Julio .Ratreabilidade de Requisitos.Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf). </br>
> Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals. Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf). </br>
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019 </br>




### Histórico de versão

| Versão | Data       | Descrição                | Autor(es)               | Revisor(es)         |
| ------ | ---------- | ------------------------ | ----------------------- | ------------------- |
| `1.0`  | 20/11/2023 | Criação do documento     | Ana Letícia | Raphaela Guimarães |
| `1.1`  | 04/12/2023 | Adição dos requisitos na matriz geral | Raphaela Guimarães | Ana Luiza |
| `1.2`  | 04/12/2023 | Correções | Raphaela Guimarães | Ana Luiza |
