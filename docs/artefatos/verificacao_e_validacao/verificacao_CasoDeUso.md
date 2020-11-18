# Analise Casos de Uso

## Introdução

O objetivo deste documento é avaliar os diagramas de casos de uso, que foram criados durante a disciplina de Requisitos de Software durante a modelagem de requisitos.

## Metodologia

Para realizar a analise, criamos um checklist levando em consideração os tópicos relevantes para a qualidade dos casos de uso. 

## Questões e Justificativas

| ID     | Questão                                                                                | Justificativa                                                                                                     |
| ------ | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **1**  | A descrição de caso de uso está consistente com a representação no diagrama?           | Para se ter uma boa descrição ela deve ser condizente com a imagem que representa o caso de uso                   |
| **2**  | O caso de uso mostra o fluxo principal?                                                | E necessário deixar claro qual é o fluxo principal e distinguilos dos demais                                      |
| **3**  | O caso de uso possui fluxos alternativos?                                              | O Doarti possui alguns fluxos alternativos.           |
| **4**  | A descrição do caso de uso possui fluxos de exceção?                                   | Pelo que foi visto o app em geral possui muitos fluxos de exceção caso não possua pode ser uma exceção ou um erro |
| **5**  | As frases representam um diálogo entre ator e sistema, evideciando a ação do ator?     | E necessário para que se possa ter uma compreenção facilitada.                                                    |
| **6**  | As frases utilizam o tempo presente?                                                   | Por padrão os casos de uso utilizam este tempo.                                                                   |
| **7**  | As frases procuram ser objetivas, evitando redundâncias ou informações desnecessárias? | O caso de uso deve ser objetivo e claro no que pretende mostrar                                                   |
| **8**  | O caso de uso segue a formatação padrão no modelo proposto?                            | Foi preparado um card de modelo, e a padronização e um ponto considerado importante                               |
| **9**  | O caso de uso possui a data nas suas versões?                                          | O versionamento possuindo as datas são de grande importancia em alguns casos                                      |
| **10** | Os icones presentes no diagrama seguem a padronização das cores?                       | Foi decidido pelo grupo seguir o padrão de icones logo caso não esteja no padrão deve ser corrigido               |
| **11** | O caso de uso possui alguma rastreabilidade?                                           | Isto ajuda e visualizar a rastreabilidade dos casos de uso                                                        |

## Inspeção

| UC                                                        | 1                  | 2                  | 3                  | 4                  | 5                  | 6                  | 7                  | 8                  | 9                  | 10                 | 11                 | Qualidade |
| --------------------------------------------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | --------- |
| [BUC01](../modelagem/diagramasDeCasoDeUso/casos/BUC01.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :x:                | Bom       |
| [BUC02](../modelagem/diagramasDeCasoDeUso/casos/BUC02.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | Bom       |
| [BUC03](../modelagem/diagramasDeCasoDeUso/casos/BUC03.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC04](../modelagem/diagramasDeCasoDeUso/casos/BUC04.md) | :x:                | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Regular   |
| [BUC05](../modelagem/diagramasDeCasoDeUso/casos/BUC05.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC06](../modelagem/diagramasDeCasoDeUso/casos/BUC06.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC07](../modelagem/diagramasDeCasoDeUso/casos/BUC07.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC08](../modelagem/diagramasDeCasoDeUso/casos/BUC08.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC09](../modelagem/diagramasDeCasoDeUso/casos/BUC09.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC10](../modelagem/diagramasDeCasoDeUso/casos/BUC10.md) | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [BUC11](../modelagem/diagramasDeCasoDeUso/casos/BUC11.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC01](../modelagem/diagramasDeCasoDeUso/casos/DUC01.md) | :heavy_check_mark: | :heavy_check_mark: | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC02](../modelagem/diagramasDeCasoDeUso/casos/DUC02.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC03](../modelagem/diagramasDeCasoDeUso/casos/DUC03.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC04](../modelagem/diagramasDeCasoDeUso/casos/DUC04.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC05](../modelagem/diagramasDeCasoDeUso/casos/DUC05.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC06](../modelagem/diagramasDeCasoDeUso/casos/DUC06.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC07](../modelagem/diagramasDeCasoDeUso/casos/DUC07.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC08](../modelagem/diagramasDeCasoDeUso/casos/DUC08.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | Bom       |
| [DUC09](../modelagem/diagramasDeCasoDeUso/casos/DUC09.md) | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC10](../modelagem/diagramasDeCasoDeUso/casos/DUC10.md) | :x:                | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Regular   |
| [DUC11](../modelagem/diagramasDeCasoDeUso/casos/DUC11.md) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| [DUC12](../modelagem/diagramasDeCasoDeUso/casos/DUC12.md) | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Bom       |
| TOTAL                                                     | 19/23              | 23/23              | 20/23              | 18/23              | 23/23              | 23/23              | 23/23              | 23/23              | 23/23              | 21/23              | 21/23              |

## Conclusão

Os casos de uso foram a valiados de acordo com os critérios estabelecidos em "Questões e Justificativas" e mesmo com alguns recebendo :x: a qualidade foi declarada como "Bom", mas alguns UC's foram avaliados como "Regular" e seria nescessário uma refatoração.

## Referências

SERRANO, Milene. Simules Jogo de Cartas e Tabuleiro - Especificação em Cenários

## Histórico de Revisões

|    Data    | Versão |                      Descrição                      |                      Autor(es)                       |
| :--------: | :----: | :-------------------------------------------------: | :--------------------------------------------------: |
| 07/11/2020 |  1.0   | Criação do documento com a analise dos Casos de Uso | [Marcos Raimundo](https://github.com/MarcosFloresta) |
| 07/11/2020 |  1.0   | Criação do documento com a analise dos Casos de Uso | [Marcos Raimundo](https://github.com/MarcosFloresta) |
| 18/11/2020 |  1.1   |                 Revisão do artefato                 |  [Ithalo Azevedo](https://github.com/ithaloazevedo)  |

