# Verificação First Things First

## Introdução
Neste documento, será realizada a verificação do artefato de [First Things First](https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/tecnicas-priorizacao/first-thing-first/) desenvolvido pela equipe 1, Economia-DF. Sendo realizado a técnica de inspeção como forma de avaliação deste documento, além de seguir o planejamento previamente estabelecido. Na tabela 1, se encontra os metadados do arquivo desenvolvido, enquanto que nas tabelas 2 e 3 pode ser vista as questões a serem avaliadas.

<center>

<<<<<<< Updated upstream
| Versão |     Autor(es)      |    Revisor(es)  |
| :----: | :-------------: | :-------------------: |
| `1.1`  | Zenilda Vieira | Gabriel Rosa e  Izabella Alves |
=======
| Versão |    Data    |         Descrição          |                      Autor(es)                      |                                              Revisor(es)                                               |
| :----: | :--------: | :------------------------: | :-------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
| `1.1`  | 01/10/2023 | Adiçao do link da gravação | Zenilda Vieira | Gabriel Rosa e  Izabella Alves |
>>>>>>> Stashed changes

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato produzido. (Fonte: Edilberto Cantuaria, 2023). </p>
</div>

</center>

<center>

|  ID   |                                 Questão                                  | Inspeção | Observações |
| :---: | :----------------------------------------------------------------------: | :------: | ----------- |
|   1   |                 As legendas estão no padrão do projeto?                  |    🟢     |             |
|   2   |                  Possui links para os outros artefatos?                  |    🟢     |             |
|   3   |                    Existe uma introdução no artefato?                    |    🟢     |             |
|   4   |               Existe tabela de versionamento padronizado?                |    🟢     |             |
|   5   |        Há referências bibliográficas ou referências no artefato?         |    🟢     |             |
|   6   | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟢     |             |
|   7   |                         O artefato possui autor?                         |    🟢     |             |
|   8   |                        O artefato possui revisor?                        |    🟢     |             |

</center>
<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação das verificações gerais do artefato. (Fonte: Edilberto Cantuaria, 2023). </p>
</div>

</center>

<center>

|  ID   |                                     Critério de Avaliação                                     | Inspeção |                    Observação                     |
| :---: | :-------------------------------------------------------------------------------------------: | :------: | :-----------------------------------------------: |
|   9   |                   A técnica que foi utilizada para priorização é descrita?                    |    🟢     |                                                   |
|  10   |              Há participação do cliente e/ou persona no processo de priorização?              |    🟢     |                                                   |
|  11   |                          Os requisitos são únicos e não se repetem?                           |    🟡     |                Ver nos comentários                |
|  12   |             Os requisitos estão ordenados em ordem de prioridade na técnica FTF?              |    🟢     |                                                   |
|  13   | A tabela possui as colunas de benefício, penalidade, valor, custo, risco e suas porcentagens? |    🟢     |                                                   |
|  14   |                         Há uma explicação de cada tipo de prioridade?                         |    🟢     |                                                   |
|  15   |                        A fórmula para o cálculo do valor está correta?                        |    🟢     |                Ver nos comentários                |
|  16   |                    A tabela possui os pesos relativos e sua justificativa?                    |    🟢     | A justificativa está presente apenas na gravação. |
|  17   | Participação dos representantes dos desenvolvedores na classificação dos custos e dos riscos? |    🟢     |                                                   |
|  18   |                                  Os cálculos estão corretos?                                  |    🟢     |                                                   |



  
<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação das verificações específicas do artefato. (Fonte: Edilberto Cantuaria, 2023). </p>
</div>

</center>

## Comentários

### ID 11 - Os requisitos são únicos e não se repetem?  

Os requisitos são referenciados por ID e, pelo o que aparenta, foram obtidos através da técnica de introspecção. A sugestão para a equipe é colocar um link que redireciona para estes requisitos elicitados, uma vez que acompanhar pelo ID pode acabar gerando uma confusão.  


### ID 15 - A fórmula para o cálculo do valor está correta?  

Seria agradável utilizar `LaTeX` para escrever as equações, dando um ar mais profissional. Para utilizar, basta seguir o seguinte exemplo:
```
//quebra de linha obrigatória 

$$
\int_{a}^{b} x^2 dx
$$

//quebra de linha obrigatória 
```

O resultado final será:

$$
\int_{a}^{b} x^2 dx
$$

### Sugestão
Utilizar um *embedded* da tabela ajudaria a melhorar a resolução da imagem que está no projeto.  

## Resultados

Para saber a porcentagem de aproveitamento do artefato, será utilizado a Equação 1:

$$ 
\frac{100}{Qtde}\cdot(EC+ NA + 0.5\cdot EI - EE)
$$
<div style="text-align: center">
<p>Equação 1: Fórmula de avaliação (Fonte: Ana Luíza, 2023). Para mais detalhes, visite a nossa <a href="../metodologia.md">metodologia</a>.</p>

</div>


Através dos checklists realizados podemos observar que:

- 17/18 exigências são atendidas;
- 1/18 exigências estão incompletas;
- 0/18 exigências estão erradas ou não foram realizadas.
- 0/18 não se aplica.

onde 18  é a quantidade de exigências.

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 97.2%.

## Bibliografia

> [Projeto Simplenote 2023.1](https://requisitos-de-software.github.io/2023.1-Simplenote/analise/verificacao/verificacao-Grupo5/modelagem/lexicos/). Acesso em: 12 de novembro de 2023

> [Projeto VLC 2023.1](https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_3/lexicos). Acesso em: 12 de novembro de 2023

> SALES, ANDRÉ B. [Plano de ensino da disciplina de Requisitos de Software](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf). Universidade de Brasília. 2023-2. Acesso em: 12 de novembro de 2023

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 12 de novembro de 2023

>WIEGERS, Karl; BEATTY, Joy. Software Requiriments. Disponível em: https://aprender3.unb.br/pluginfile.php/2692778/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf. Acesso em 20 de jun de 2023.



## Histórico de versão

|    Data    | Versão |      Descrição       |      Autor(es)      | Revisor(es) |
| :--------: | :----: | :------------------: | :-----------------: | :---------: |
| 12/11/2023 |  1.0   | Criação do documento | Edilberto Cantuaria |    Ana Luiza   |
