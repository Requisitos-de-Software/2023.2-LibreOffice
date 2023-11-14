# Verificação da Especificação Suplementar

## Introdução

Neste documento, será realizada a verificação do artefato da especificação suplementar desenvolvido pela equipe 1, Economia-DF. Sendo realizado a técnica de inspeção como forma de avaliação deste documento, além de seguir o planejamento previamente estabelecido. Na tabela 1, se encontra os metadados do arquivo desenvolvido, enquanto que nas tabelas 2 e 3 pode ser vista as questões a serem avaliadas.

<center>

|Versão|Autor|Revisor|
|:----:|----|---------|
|`1.9`|Lucas de Oliveira|-|

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato produzido. (Fonte: Artur Seppa Reiman, 2023). </p>
</div>

</center>

<center>

| ID |                                 Questão                                 | Inspeção | Observações                      |
| :-: | :-----------------------------------------------------------------------: | :--------: | ---------------------------------- |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |                                    |
| 2 |                  Possui links para os outros artefatos?                  |    🔴      |  Será justificado nos comentários |
| 3 |                   Existe uma introdução no artefato?                   |     🟢     |  |
| 4 |                Existe tabela de versionamento padronizado?                |     🟡     |                 Dentro do versionamento 1.9 o revisor está omitido no artefato.              |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟡      |       Na seção de Usabilidade há uma referência sem base citando Nielsen.     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟢     |                                    |
| 7 |                         O artefato possui autor?                         |     🟢     |                                    |
| 8 |                        O artefato possui revisor?                        |     🟡    |         Na maior parte das versões obtém pelo menos um revisor citado. Entretanto como previamente visto, na versão 1.9 o registro está sem revisor.      |

</center>
<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação das verificações gerais do artefato. (Fonte: Artur Seppa Reiman, 2023). </p>
</div>

</center>

<center>

| ID  |                                                 Questão                                                  | Inspeção | Obersevação                                                                                                                                                                        |
| :-: | :------------------------------------------------------------------------------------------------------: | :------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  9  |                                    O artefato segue o modelo FURPS+?                                     |    🟢    |                                                                                                                                                                                    |
| 10  |                                  O documento aborda as funcionalidades?                                  |    🟢    |                                                                                                                                                                                    |
| 11  | O documento aborda a Usabilidade do sistema ? |    🟢    |                                                                                                             |
| 12  | O requisitos apresentados no tópico de Usabilidade são testáveis? |    🟡    | Será justificado nos comentários.                         |
| 13  |       O documento aborda a confiabilidade do sistema ?                |    🟢    |                                                                                                                                                                                    |
| 14  |      O documento apresenta os requisitos de segurança de dados dentro do tópico de confiabilidade ?                 |    🟢    |                                                                                                                                                                                    |
| 15  |      Em confiabilidade os requisitos podem ser testáveis ?                 |    🟡    |            Será justificado nos comentários.                                                                                                                                                                  |
| 16  |          O documento retrata sobre o Desempenho do sistema ?           |    🟢    |                                                                                                                                                                                    |
| 17  |          O artefato aborda sobre do tempo de resposta e uso de recursos no tópico de Desempenho de sistema ?           |    🟢    |                                                                                                                                                                                    |
| 18  |           O documento retrata a Suportabilidade do sistema ?           |    🟡    | Será justificado nos comentários.  |
| 19  |                        O documento aborda as funcionalidades adicionais no sistema ?                         |    🟡    |                 Será justificado nos comentários.                                                             |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação das verificações específicas do artefato. (Fonte: Artur Seppa Reiman, 2023). </p>
</div>

</center>

## Comentários

### ID 2 - Possui links para os outros artefatos?

 Há links com redirecionamento incorreto no documento, a maior parte deles efetua o redirecionamento do usuário para o artefato dentro do github e não para a página do gitpages. Além disso os links de "Requisitos Elicitados" e "usuário" estão incorretos, no primeiro caso ele redireciona para uma página inexistente e o outro redireciona para o documento de léxicos.

### ID 12 - O requisitos apresentados no tópico de Usabilidade são testáveis?

O requisito RU01 é apresentado de forma imprecisa, carecendo de uma especificação mais detalhada. O uso de termos como "fácil de usar" e "ser intuitivo" torna esses requisitos difíceis de serem testados. 

### ID 15 - Em confiabilidade os requisitos podem ser testáveis ?

O requisito RE01 é apresentado de forma imprecisa, carecendo de uma especificação mais detalhada. A forma como o aplicativo deve lidar sem falhas ou interrupções pode ser melhor retratada.

### 18 - O documento retrata a Suportabilidade do sistema ?

As funcionalidades relacionadas à portabilidade, testabilidade, extensibilidade, configurabilidade e instabilidade no tópico mencionado. No entanto, não há especificação dos requisitos a serem implementados no sistema, assim como nem a rastreabilidade deles.

### 19 - O documento aborda as funcionalidades adicionais no sistema ?          

 O artefato aborda os requisitos adicionais sobre a restrição de design, ajuda e documentação e interfaces. Entretando, não há a rastreabilidade dos requisitos na parte de restrição de design e interfaces. 

## Resultados

Para saber a porcentagem de aproveitamento do artefato, será utilizado a Equação 1:

$$
\frac{100}{Qtde}\cdot(EC+ NA + 0.5\cdot EI - EE)
$$

<div style="text-align: center">
<p>Equação 1: Fórmula de avaliação (Fonte: Ana Luíza, 2023). Para mais detalhes, visite a nossa <a href="../metodologia.md">metodologia</a>.</p>

</div>

Através dos checklists realizados podemos observar que:

- 11/19 exigências são atendidas;
- 7/19 exigências estão incompletas;
- 1/19 exigências estão erradas ou não foram realizadas.
- 0/19 não se aplica.

onde 19 é a quantidade de exigências.

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 71.05%.

## Bibliografia

> HENRIQUE, Matheus. Verificação da Especificação Suplementar do Grupo 2. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega3/especificacao-suplementar/. Acesso em: 13 novembro 2023.

## Histórico de Versão

| Versão | Data       | Descrição                           | Autor      | Revisor |
| ------ | ---------- | ----------------------------------- | -------------- |-------------- |
| 1.0    | 13/11/2023 | Criação e desenvolvimento do documento de verificação | Artur Seppa Reiman | Rafael Xavier |