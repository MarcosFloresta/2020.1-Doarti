# Analise Casos de Uso

## Introdução

Neste documento o objetivo é avaliar os diagramas de casos de uso, que foram criados durante a diaciplina de Requisitos de Software durante a modelagem de requisitos.

## Metodologia

Para realizar a analise, criamos um checklist levando em cinsideração os topicos relevantes para a qualidade dos casos de uso. 

## Questões e Justificativas

|ID|Questão|Justificativa|
|--|--|--|
| **1** | A descrição de caso de uso está consistente com a representação no diagrama?|Para se ter uma boa descrição ela deve ser condizente com a imagem que representa o caso de uso|
| **2** | O caso de uso mostra o fluxo principal? |E necessário deixar claro qual é o fluxo principal e distinguilos dos demais|
| **3** | O caso de uso possui fluxos alternativos? |O app guiaBolso possui muitos fluxos alternativos, logo caso não possua pode ser uma exceção ou um erro|
| **4** | A descrição do caso de uso possui fluxos de exceção? |pelo que foi visto o app em geral possui muitos fluxos de exceção caso não possua pode ser uma exceção ou um erro|
| **5** | As frases representam um diálogo entre ator e sistema, evideciando a ação do ator? |E necessário para que se possa ter uma compreenção facilitada.|
| **6** | As frases utilizam o tempo presente? |por padrão os casos de uso utilizam este tempo.|
| **7** | As frases procuram ser objetivas, evitando redundâncias ou informações desnecessárias?|O caso de uso deve ser objetivo e claro no que pretende mostrar|
| **8** | O caso de uso segue a formatação padrão no modelo proposto?|Foi preparado um card de modelo, e a padronização e um ponto considerado importante|
| **9** | O caso de uso possui a data nas suas versões?|O versionamento possuindo as datas são de grande importancia em alguns casos|
| **10** | Os icones presentes no diagrama seguem a padronização das cores? |Foi decidido pelo grupo seguir o padrão de icones logo caso não esteja no padrão deve ser corrigido|
| **11** | O caso de uso possui alguma rastreabilidade?|Isto ajuda e visualizar a rastreabilidade dos casos de uso |

## Inspeção

| UC | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | Qualidade |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|BUC01 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|Bom|
|BUC02 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|Bom|
|BUC03 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC04 |:x:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Regular|
|BUC05 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC06 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC07 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC08 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC09 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC10 |:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|BUC11 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC01 |:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC02 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC03 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC04 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC05 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC06 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC07 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC08 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|Bom|
|DUC09 |:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC10 |:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Regular|
|DUC11 |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|DUC12 |:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|TOTAL| 19/23 | 23/23 | 20/23 | 18/23 | 23/23 | 23/23 | 23/23 | 23/23 | 23/23 | 21/23 | 21/23 |

## Conclusão

