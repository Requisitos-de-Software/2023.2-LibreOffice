# Especificação Suplementar

## Introdução

A Especificação Suplementar [¹](#referencias-bibliograficas) em requisitos de software é um documento que fornece informações adicionais sobre os requisitos de um determinado sistema ou aplicativo de software. Esse documento pode incluir detalhes adicionais sobre como o sistema deve ser projetado e implementado, bem como quaisquer requisitos específicos que devem ser atendidos. É usado também para complementar a especificação de requisitos principal, que fornece uma visão geral dos requisitos do sistema.

O objetivo da especificação suplementar é capturar os requisitos do sistema que não são facilmente definidos pela modelagem de casos de uso. De modo que a especificação suplementar em conjunto com a modelagem de Casos de Uso define, se não todos, a maioria dos requisitos do sistema.



## Metodologia FURPS+

A metodologia FURPS+ [²](#referencias-bibliograficas) é utilizada para avaliar os requisitos de software e identificar quais devem ser incluídos em um projeto de desenvolvimento. A sigla FURPS+ representa cinco categorias de requisitos, sendo eles: Funcionalidade, Usabilidade, Confiabilidade, Performance e Suportabilidade. Essas categorias descrevem aspectos essenciais do software e ajudam a classificar os requisitos de acordo com suas características:
    
* Funcionalidade: refere-se aos requisitos funcionais do software, ou seja, as funcionalidades e recursos que o software deve oferecer, muitas vezes já explicitados nos casos de uso.

* Usabilidade: está relacionada à avaliação da interface do usuário e o quão fácil é para o usuário realizar suas demandas por meio do software, seguindo princípios de usabilidade.

* Confiabilidade: diz respeito à integridade, conformidade e interoperabilidade do software. Requisitos nessa categoria abordam aspectos como frequência e gravidade de falhas, tempo médio entre falhas e possibilidade de recuperação.

* Performance: avalia os requisitos de desempenho do software, incluindo aspectos como tempo de resposta, consumo de memória e disponibilidade da aplicação.

* Suportabilidade: abrange requisitos relacionados a características como testabilidade, adaptabilidade, manutenibilidade, compatibilidade, escalabilidade e localizabilidade.

* O símbolo "+": engloba outros requisitos não-funcionais que devem ser considerados, como requisitos de design, requisitos de implementação, requisitos de interface e requisitos físicos. Esses requisitos adicionais podem restringir o design, a construção e o funcionamento do sistema, incluindo limitações físicas do hardware.

Concluindo, o modelo FURPS+ é uma abordagem abrangente para classificar e definir requisitos de software, considerando diferentes dimensões de qualidade e funcionalidade. É uma ferramenta útil para orientar o processo de desenvolvimento de software e garantir que todos os requisitos essenciais sejam contemplados

## Metodologia FURPS+ aplicada ao LibreOffice Witter
<!-- Para melhor as tabelas seguintes, temos a tabela 1 que é uma legenda para as tabelas seguintes.


<font><p style="text-align: center">**Tabela 1** - Legenda.</p></font>
<center>

| ID  | Significado                                                            |
| --- | ---------------------------------------------------------------------- |
| BR  | [Brainstorming](../elicitacao/tecnicas/brainstorming.md)               |
| ES  | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| INT | [Introspecção](../elicitacao/Introspec%C3%A7%C3%A3o.md)                |

</center>

<font size="3"><p style="text-align: center">Fonte: [Edilberto Almeida Cantuaria, 2023](https://github.com/edilbertocantuaria).</p></font> -->


### Funcionalidade  
Na seção de `elicitacao`, foram identificados os requisitos funcionais, e a Tabela 2 na página de requisitos elicitados por introspecção apresenta uma lista de todos os requisitos priorizados que pode ser acessaod [clicando aqui](../elicitacao/introspeccao.md/)

### Usabilidade 

<center>

| ID    | Descrição                                                                                                                                                                                                                                                   |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O sistema deve ser compatível com a opção de alto contraste, exibindo cores adequadas para essa configuração.                                                                                                                                               |
| USA02 | O aplicativo deve destacar e enfatizar recursos de acessibilidade em seu design.                                                                                                                                                                            |
| USA03 | Palavras desconhecidas que possivelmente são erros ortográficos ou erros gramaticais devem ser identificadas pela cor vermelha.                                                                                                                                                                                       |
| USA04 | O sistema deve incluir recursos de acessibilidade, como um teclado virtual e a capacidade de aumentar o tamanho da fonte.                                                                                                                                   |
| USA05 | O aplicativo deve apresentar uma interface padronizada que proporcione conforto ao usuário  |
| USA06 | O sistema deve oferecer caminhos curtos para a realização de tarefas complexas, garantindo que estas possam ser concluídas em no máximo 5 cliques.                                                                                                          |
| USA07 | O aplicativo deve permitir a identificação fácil das funcionalidades disponíveis.                                                                                                                                                                           |
</center>

<font><p style="text-align: center">**Tabela 1:** Requisitos de Usabilidade. Fonte: Edilberto Almeida Cantuaria .</p></font>


### Confiabilidade 


<center>

| ID      | Descrição                                                                                                                                                                          |
| ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CONFA01 | O aplicativo deve contar com um sistema de suporte ao usuário.                                                                                                                     |
| CONF02  | Os servidores devem garantir disponibilidade ininterrupta para o usuário. Em caso de manutenção programada ou problemas no sistema, o usuário deve ser informado com antecedência. |
| CONF03  | O sistema deve oferecer a funcionalidade de salvamento automático (autosave) após um determinado período de uso da plataforma pelo usuário.                                        |
| CONF04  | O aplicativo deve ter a capacidade de se recuperar de falhas de maneira eficiente e possibilitar possibilitar que o usuário se recupere de problemas e erros com poucos cliques.   |
| CONF05  | O sistema deve manter as informações atualizadas e em conformidade com a realidade.                                                                                                |
| CONF06  | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                                                                  |
| CONF07  | O aplicativo deve permitir a identificação fácil das funcionalidades disponíveis.                                                                                                  |
</center>

<font><p style="text-align: center">**Tabela 2:** Requisitos de Confiabilidade. Fonte: Edilberto Almeida Cantuaria .</p></font>



### Performance 

<center>

| ID      | Descrição                                                                                                                                                             |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PERFA01 | O aplicativo deve contar com uma interface de design simplificado.                                                                                                    |
| PERF02  | O aplicativo deve incluir armazenamento em cache para dados essenciais.                                                                                               |
| PERF03  | O aplicativo deve garantir acesso eficiente a dados locais.                                                                                                           |
| PERF04  | O sistema deve proporcionar uma navegação suave, sem interrupções, com caminhos que sigam uma sequência lógica.                                                       |
| PERF05  | É fundamental que a aplicação mantenha um consumo de memória razoável para evitar possíveis problemas em dispositivos cujo sistema operacional não esteja atualizado. |
</center>

<font><p style="text-align: center">**Tabela 3:** Requisitos de Performance. Fonte: Edilberto Almeida Cantuaria .</p></font>


### Suportabilidade



<center>

| ID     | Descrição                                                                                                                                                                                                                                                                                                   |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUPA01 | O site oficial do LibreOffice Writer deve incluir uma seção dedicada ao Suporte ao Usuário, oferecendo serviços de Atendimento ao Consumidor (SAC) ou equivalentes.                                                                                                                                         |
| SUP02  | O sistema do LibreOffice Writer deve ser projetado com capacidade de extensibilidade, permitindo a adição de novas funcionalidades, adaptação às mudanças e interoperação entre sistemas semelhantes (Como o *Word*  da Microsoft Office e o *Docs* da Google) .                                            |
| SUP03  | O sistema do LibreOffice Writer deve ser dotado de recursos de rastreabilidade, incluindo mecanismos para registrar e acompanhar mudanças e correções ao longo do tempo, juntamente com controle de versão e registros de alterações.                                                                       |
| SUP04  | O sistema do LibreOffice Writer deve incorporar tolerância a falhas para assegurar que possa lidar com problemas de maneira eficaz, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, realização de backups regulares e rápida restauração em caso de falhas. |

</center>

<font><p style="text-align: center">**Tabela 4:** Requisitos de Suportabilidade. Fonte: Edilberto Almeida Cantuaria .</p></font>



### Outros requisitos não-funcionais (+)
* Requisito de Licenciamento: O LibreOffice Writer deve exigir que os usuários aceitem um termo de licenciamento para utilizar a plataforma. Este termo de uso Pode ser encontrado [clicando aqui](../termoDeConsentimento/termoDeConsentimento.pdf).

* Observações Legais, de Copyright e Outra: O sistema está sujeito às leis de direitos autorais, portanto, a utilização de marcas registradas requer autorização prévia dos detentores dos direitos. É importante também observar as leis de proteção de dados, como a Lei Geral de Proteção de Dados (LGPD), e as regulamentações específicas para serviços financeiros.

* Requisitos Físicos: O LibreOffice Writer deve ser compatível com computadores desktop, laptops, tablets e smartphones que utilizem navegadores de internet compatíveis.
  
* Restrições de Design: O design do sistema deve aderir aos atuais padrões de boas práticas adotados pela indústria, seguindo princípios de arquitetura limpa, microserviços e componentização. Além disso, o design deve incorporar paletas de cores que permitam que pessoas com restrições visuais, como daltonismo, possam distinguir elementos, sem prejudicar a identidade visual da marca, garantindo compatibilidade com diferentes sistemas operacionais.


## Referências Bibliográficas

> [1] SERRANO, Milene - Slides da aula 11. Disponibilizados pelo Professor.
>
> [2] FERRARI, Fabrício. FURPS+. Qualidade BR, 06 de maio de 2023. Disponível em: <https://qualidadebr.wordpress.com/2008/07/10/furps/>. Acesso em: 22 de outubro de 2023



## Bibliografia


> CARNEIRO, Caio Vitor. Especificação Suplementar. Repositório do Grupo Grasshopper da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Grasshopper/modelagem/especificao-suplementar/>>. Acesso em: 09 maio 2023.

> FERREIRA, Rafaela. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/especificacao-suplementar.md>>. Acesso em: 22 de outubro de 2023


> MATIAS, Davi. Especificação Suplementar. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/especificacao_suplementar/>>. Acesso em: 22 de outubro de 2023.

> PERILLO, Matheus. Especificação Suplementar. Repositório do Grupo TikTok da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/especificao-suplementar.md>>. Acesso em: 22 de outubro de 2023.

> SALES, Wildemberg; Repositório do Grupo Grasshopper da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<hhttps://github.com/Requisitos-de-Software/2022.2-Grasshopper/blob/main/docs/modelagem/especificao-suplementar.md/>>. Acesso em: 22 de outubro de 2023.

> SANTOS, Eduardo; Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/EspecificacaoSuplementar/>>. Acesso em: 22 de outubro de 2023.
## Histórico de Versão

| Versão | Data       | Descrição             | Edilberto Almeida Cantuaria(es) | Revisor(es)   |
| ------ | ---------- | --------------------- | ------------------------------- | ------------- |
| `1.0`  | 22/10/2023 | Criação do documento. | Edilberto Cantuaria             | Rafael Xavier |
