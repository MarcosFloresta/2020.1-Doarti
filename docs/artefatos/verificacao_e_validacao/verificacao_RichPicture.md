# Verificação do RichPicture

## Indrodução

A verificação dos RichPictures tem como objetivo principal a detecção de defeitos antes de encaminhar o produto à produção final. Para esse fim, um checklist mostrou-se mais prático e eficaz para a verificação. O checklist tem questões comuns para os modelos a serem documentados e avaliados e busca capturar as questões relevantes.

## Metodologia

Para analisar os modelos dos RichPicture, foram levantadas questões a respeito de aspectos importantes para a modelagem de requisitos com cenários. As questões serão usadas como critérios de sucesso e só há duas respostas possíveis pra essas questões: Sim, sendo representado pelo símbolo de :heavy_check_mark: e indicará sucesso, e não, sendo representado por um :x:, que indicará falha. 

## Questões e Justificativas

| Questão |Justificativa & Referência |
|--|--|
| **1** - A simbologia está coerente? | O uso de ícones ou imagens que remetam ao que se quer descrever é opcional, porém ajuda os leitores a entenderem com mais facilidade a mensagem a ser passada. De acordo com [Pinheiro.M](http://www.fmemoria.com.br/entrevistas/entrevista_icones.pdf), a iconografia reforça visualmente alguma informação que o sistema apresenta. |
| **2** - Existe equilíbrio entre palavras e desenhos?|   De acordo com [Monk.A e Howard.S](https://dl.acm.org/citation.cfm?id=274434), é importante que o RP contenha sua estrutura bem padronizada para o modelo não ficar sobrecarregado com informações detalhadas, podendo ocasionar em um modelo incompreensível. |
| **3** - O atores estão bem definidos? | Para manter a estrutura do diagrama adequada, todos os participantes da ação desejada devem constar no diagrama, com suas respectivas atribuições, como afirmam [Monk.A e Howard.S](https://dl.acm.org/citation.cfm?id=274434) em seu material.  |
| **4** - O centro está claro e bem definido?| A estratégia de colocar o ator ou ação principal no centro permite que todas as ações possam ter ligações com ele de forma compreensível, focando a atenção do leitor nele, como descreve [Monk](https://dl.acm.org/citation.cfm?id=274434). |
| **5** - O centro está coerente com o título?| Para contextualizar o tema do modelo para o leitor, um título intuitivo acrescenta no entendimento de forma mais rápida. |
| **6** - O fluxo e as operações fazem sentido?| Usar as setas e impactos nas ações são essenciais para o entendimento da mensagem a ser passada. [Howard](https://dl.acm.org/citation.cfm?id=274434) afirma que manter o fluxo com as setas condizentes com o real ajudam a evitar duplas interpretações. |
| **7** - Usa linguagem compreensível?| De acordo com [Monk.A e Howard.S](https://dl.acm.org/citation.cfm?id=274434), desenhar o diagrama com linguagem clara e comum é essencial, pois aumentará a quantidade de pessoas que poderão revisar seu artefato. |
| **8** - Possui versionamento?| Com versionamento, é possível melhorar a comunicação entre um grupo, permitindo que pessoas diferentes possam ver alterações, medir o impacto delas e também de aperfeiçoar o modelo, como descreve o material de [versionamento](http://gnmd.webgrupos.com.br/arquivo_downloads/Apresenta__oSVN.pdf). |
| **9** - Os ícones correspondem à identidade visual proposta?| Para padronizar a identidade visual da empresa em questão, é disposto um material com seus ícones e paleta de cores, disponíveis no site da [Guira](https://guira.com.br/icons-illustrations-for-guiabolso). Com essa padronização é possível manter um fluxo com interpretações a funcionalidades já conhecidas.  |
| **10** - Há relação clara entre atores e objetos?| Segundo [Monk.A e Howard.S](https://dl.acm.org/citation.cfm?id=274434), a relação entre stakeholders e as ações mostram o que deve ser alcançado, sendo essencial no modelo. |
| **11** - Está com as funcionalidades atualizadas?| As empresas evoluem funcionalidades e regras de negócio, sendo necessária, a frequente atualização do modelo em questão. |

## Inspeção

| Critério de Sucesso | [RP1](../preRastreabilidade/richPicture.md) | [RP2](../preRastreabilidade/richPicture.md) |
| -- | -- | -- |
| **01** | :x: | :heavy_check_mark: |
| **02** | :heavy_check_mark: | :heavy_check_mark: |
| **03** | :x: | :heavy_check_mark: |
| **04** | :heavy_check_mark: | :heavy_check_mark: |
| **05** | :heavy_check_mark: | :heavy_check_mark: |
| **06** | :heavy_check_mark: | :heavy_check_mark: |
| **07** | :heavy_check_mark: | :heavy_check_mark: |
| **08** | :heavy_check_mark: | :heavy_check_mark: |
| **09** | :x: | :heavy_check_mark: |
| **10** | :heavy_check_mark: | :heavy_check_mark: |
| **11** | :x: | :x: |
| **Quantidade de Sucessos** | 64% | 91% |
| **Classificação** |  Regular | Bom |

## Conclusão

O RichPicture pode ser avaliado como **Bom** de acordo com os critérios de qualidade estabelecidos pelo grupo. Contudo um Rich específico estão regulares. Um novo Rich Picture refatorado é nescessário. 

## Referências
HORAN, Pat.Using Rich Pictures in Information System Teaching. Disponível em: http://ceur-ws.org/Vol-72/039%20Horan%20SSM.pdf. 

Leadership for change. Complexity and rich pictures. Disponível em: <http://leadershipforchange.org.uk/wp-content/uploads/Complexity-and-rich-pictures.pdf>. 

Requisitos Uber. Verificação - Inspeção RichPicture e Cenários e Léxicos. Disponível em: <https://github.com/victorhdcoelho/Requisitos-uber-2018.2/wiki/Inspe%C3%A7%C3%A3o-RichPicture---Cen%C3%A1rios-e-L%C3%A9xicos>.

HOWARD, Andrew Monk. Steve." The Rich Picture: A Tool for Reasoning About Work Context." Interactions.

## Histórico de Revisões

|    Data    | Versão |        Descrição         |                                               Autor(es)                                                |
| :--------: | :----: | :----------------------: | :----------------------------------------------------------------------------------------------------: |
| 08/11/2020 |  1.0   | Criação do documento com a analise do Rich Picture | [Marcos Raimundo](https://github.com/MarcosFloresta)|
