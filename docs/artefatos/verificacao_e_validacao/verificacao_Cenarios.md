# Cenários

## Introdução

A verificação dos cenários tem como objetivo principal a detecção de defeitos antes de encaminhar o produto à produção final. Para os cenários, o itens mais relevante a se analisar é a notação dos modelos. Para esse fim, um checklist mostrou-se mais prático e eficaz para a verificação.

## Metodologia

Para analisar os modelos dos Cenários, foram levantadas questões a respeito de aspectos importantes para a modelagem de requisitos com cenários. As questões serão usadas como critérios de sucesso e só há duas respostas possíveis pra essas questões: Sim, sendo representado pelo símbolo de "check" e indicará sucesso, e não, sendo representado por um "X", que indicará insucesso. Em específico nas questões de linkagem de léxicos e cenários, se o cenário em questão conter somente 1 link faltante, será aribuida símbolo positivo.

### Questões & justificativas

| Questão                                                                          | Justificativa & Referência                                                                                                                                                                                                    |
| -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1** - Possui título?                                                           | O Cenário deve ter título para que o leitor já saiba do que se trata sem precisar ler o cenário inteiro, conforme **Jogo de Cartas e Tabuleiro - Especificação em Cenários**.                                                 |
| **2** - Possui metas/objetivos?                                                  | O cenário descreve a realização de uma meta, então é essencial que fique claro qual é essa meta. Conforme **Enhancing a requirements baseline with scenarios**, pg 4.                                                         |
| **3** - Os atores estão bem definidos?                                           | É importante que fique claro quem são os responsáveis e os envolvidos na realização da meta. Conforme **Enhancing a requirements baseline with scenarios**, pg 5.                                                             |
| **4** - Possui contexto?                                                         | O contexto descreve a localização, noção e o estado do cenário. Conforme **Enhancing a requirements baseline with scenarios**, pg 4.                                                                                          |
| **5** - Há descrição dos recursos?                                               | É importante deixar claro quais são os recursos e serviços necessários para realização do cenário. Conforme **Enhancing a requirements baseline with scenarios**, pg 4.                                                       |
| **6** - Responde o 5W2H?                                                         | O grupo concordou em responder as perguntas do 5W2H para contextualizar o cenário pois fica mais fácil e direta a leitura.                                                                                                    |
| **7** - Descreve exceções?                                                       | É preciso deixar claro o que pode interromper a realização do cenário. Conforme **Enhancing a requirements baseline with scenarios**, pg 4.                                                                                   |
| **8** - Descreve as restrições?                                                  | É preciso deixar claro ao que se restringe o cenário. Conforme **Enhancing a requirements baseline with scenarios**, pg 4.                                                                                                    |
| **9** - Possui ligações suficientes com léxicos e/ou cenários por meio de links? | É preciso que haja linkagem com as coisas que são relevantes para o cenário para que as informações fiquem mas evidentes e mais fácil de ser encontrada. Conforme **Enhancing a requirements baseline with scenarios**, pg 3. |
| **10** - Caso haja subcenários, há a ligação deles com os episódios?             | Se há subcenário ele precisa está associado a algum episódio para que faça sentindo sua ligação. Conforme **Jogo de Cartas e Tabuleiro - Especificação em Cenários**.                                                         |
| **11** - Possui rastreabilidade?                                                 | É importante saber as origens do cenário, qual o artefato que levou a contrução dele e onde o requisito pode ser encontrado. Conforme orientado pelos professores da disciplina.                                              |
| **12** - Possui versionamento?                                                   | É conhecer as versões anteriores do cenário para acompanhar sua evolução e identificar melhorias. Conforme orientado pelos professores da disciplina.                                                                         |

## Inspeção

| Critério de sucesso                                                          | [C01](../modelagem/cenarios.md) | [C02](../modelagem/cenarios.md)                            |
|:----|:------|:---------|
| 1 - Possui título?                                                           | :heavy_check_mark:              | :heavy_check_mark:                                         |
| 2 - Possui metas/objetivos?                                                  | :heavy_check_mark:              | :heavy_check_mark:                                         |
| 3 - Os atores estão bem definidos?                                           | :heavy_check_mark:              | :heavy_check_mark:                                         |
| 4 - Possui contexto?                                                         | :x:                             | :x:                                                        |
| 5 - Há descrição dos recursos?                                               | :heavy_check_mark:              | :heavy_check_mark:                                         |
| 6 - Descreve exceções?                                                       | :heavy_check_mark:              | :heavy_check_mark:                                         |
| 7 - Descreve as restrições?                                                  | :x:                             | :x:                                                        |
| 8 - Possui ligações suficientes com léxicos e/ou cenários por meio de links? | :x:                             | :x:                                                        |
| 9 - Caso haja subcenários, há a ligação deles com os episódios?              | -                               | -                                                          |
| 10 - Possui rastreabilidade?                                                 | :x:                             | :x:                                                        |
| 11 - Possui versionamento?                                                   | :heavy_check_mark:              | :heavy_check_mark:                                         |
| -                                                                            | Classificação                   | **Bom**                                                    | **Bom**                                                    |
| -                                                                            | Melhorias                       | Linkar léxicos em alguns termos, adicionar rastreabilidade | Linkar léxicos em alguns termos, adicionar rastreabilidade |

## Conclusão

Pela verificação feita a partir do checkList, os cenários gerados pelo grupo ficaram bons. O que mais deixou a desejar foi a questão da rastreabilidade e linkagem dos léxicos.

## Referências

<https://fga-disciplinas.github.io/2019.1-Guia-Bolso/analise/analise_cenarios/>

## Versionamento

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:---------:|
|08/11/2020 |1.0|Adicionando inspeção | [Ithalo Azevedo](https://github.com/ithaloazevedo)|
