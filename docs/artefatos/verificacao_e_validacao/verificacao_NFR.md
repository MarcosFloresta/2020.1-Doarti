# NFR
A verificação dos NFR(_Non-Functional requiriments_) tem como objetivo principal a detecção de defeitos antes de encaminhar o produto à produção final. Para esse fim, um checklist mostrou-se mais prático e eficaz para a verificação. O checklist tem questões comuns para os modelos a serem documentados e avaliados, também busca capturar as questões relevantes.

## Objetivo
Verificar a qualidade e a validação dos artefatos levantados ao longo do processo de desenvolvimento dos requisitos do aplicativo Doarti.

## Questões & Justificativas

| Questão |Justificativa & Referência |
|--|--|
| 1 - Respeita as regras da metodologia?| As operações de NFR's seguem uma metologia. Portanto essa metodologia possui algumas regras que são importantes para tornar o uso do framework efetivo. |
| 2 - Softgoals autoexplicativo? | De acordo com as regras do framework de modelagem, não se faz necessário quando é complexo descrever uma meta, entretanto ter um softgoal com uma nomenclatura autoexplicativa diminui a complexidade do diagrama. |
| 3 - Operadores com finalidades definidas?| Os operadores devem causar algum tipo de impacto ao restante do diagrama, de acordo com a finalidade que ele apresentar. |
| 4 - Existe impactos colaterais?| Os impactos podem refletir tanto em softgoals quanto em operadores que estiverem ao lado. |
| 5 - Existe impactos em ancestrais?| Geralmente os impactos refletem em quem está acima do que está sendo analisado. |
| 6 - Operadores geram impactos nos softgoals?| Normalmente e de acordo com o Framework, é uma função que é padrão de ocorrer dentro do diagrama. |
| 7 - Operadores geram impactos em outros operadores?| Dependendo do nivel de complexidade e granulação do diagrama, podem acarretar em impactos entre operadores. |
| 8 - SoftGoals geram impacto em outros softgoals? | Softgoals normalmente refletem em outros softgoals, pois estes compõe, uma estrutura, para contribuir com um softgoal maior. |
| 9 - Existe ao menos um operador que tenha dependências (AND/OR) para atender o softgoal?| De acordo com as regras de NFR Framework, há a ocorrencia de dependência com as análise, pois para que certor criterios sejam atendidos, faz-se necessário a existencia de outros critérios para então atender um critério maior. |
| 10 - Softgoals escritos como nome? | Como regra do NFR Framework, todo softgoal deve ser descrito como um objeto. |
| 11 - Operadores escritos como verbos? | Como regra do NFR Framework, todo operador deve ser descrito como uma ação e no infinitivo. |
| 12 - Existência de prioridade no NFR, seja operador ou softgoal?| Dependendo da complexidade da modelagem, faz-se necessário a existencia de alguns softgoals ou operadores com maior prioridade a que outros. |
| 13 - Os critérios são parcialmente satisfatórios? | Isso ocorre quando existe na modelagem critérios que atende parcialmente aos critérios. |
| 14 - Os critérios não são satisfatórios?| Ocorre quando a modelagem não atende ao critério principal a quem define o NFR. |
| 15 - Existência de softgoals ou operadores que não são satisfatórios?| Isso ocorre quando exite na modelagem critérios que não foram atendidos. |
| 16 - Possui versionamento?| Está por sua vez está ligado a organização da equipe de trabalho, a fim de não perder versões anterios, para realizar comparações. |
| 17 - NFR condiz com requisitos já apresentados?| O NFR's que estão sendo apresentados já foram estipulados anteriormente com outras metodologias de aplicação ao desenvolvimento do requisito e elicitação. Portanto, na fase de modelagem de NFR, sendo este o mais abstrato para modelagem dos requisitos não funcionais, é o momento para verificar e validar se está coerente. |
|__Referência__|[NFR Framework - UFPE](https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf)|

## Inspeção

|Critério de sucesso|[NFR Suportabilidade](../../assets/images/nfr/nfr-suportabilidade.jpg)|[NFR Confiabilidade](../../assets/images/nfr/nfr-confiabilidade.jpg)|[NFR Usabilidade](../../assets/images/nfr/nfr-usabilidade.jpg)|
|--|--|--|--|--|--|--|--|--|
| 1 - Respeita as regras da metodologia?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| 2 - Softgoals autoexplicativo? | :x: | :heavy_check_mark: | :heavy_check_mark: |
| 3 - Operadores com finalidades definidas?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 4 - Existe impactos colaterais?| :x: | :x: | :x: |
| 5 - Existe impactos em ancestrais?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 6 - Operadores geram impactos nos softgoals?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:| 
| 7 - Operadores geram impactos em outros operadores?| :x: | :x: | :x: |
| 8 - SoftGoals geram impacto em outros softgoals? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| 9 - Existe ao menos um operador que tenha dependencias (AND/OR) para atender o softgoal?| :heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| 10 - Softgoals escritos como nome? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| 11 - Operadores escritos como verbos?| :x: | :x: | :x: |
| 12 - Existência de prioridade no NFR, seja operador ou softgoal?| :x: | :x: | :x: |
| 13 - Os critérios são parcialmente satisfatórios?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| 14 - Os critérios não são satisfatórios?| - | - | :heavy_check_mark: |
| 15 - Existência de softgoals ou operadores que não são satisfatórios?| - | - | :heavy_check_mark: |
| 16 - Possui versionamento?| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 17 - NFR condiz com requisitos já apresentados?| :heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| *Classificação* | **Bom**  | **Bom** | **Falta detalhamento** |


## Parecer

| **SR/SD** | **Autor** | **Parecer**|
|--|--|--|
|[NFR Usabilidade](../../assets/images/nfr/nfr-usabilidade.jpg)| [Ithalo Azevedo](https://github.com/ithaloazevedo)| O NFR precisa ser melhorado para detalhar todas as possibilidades existentes de impactos dos requisitos não funcionais. |

## Conclusão

O NFR pode ser avaliado como Bom de acordo com os critérios de qualidade estabelecidos pelo grupo. Contudo alguns NFR específicos estão regulares, sendo necessários refatorá-los.

## Referência

SERRANO, Maurício. Desenvolvimento Intencional de Software Transparente Baseado em Argumentação. 2011. Tese de Doutorado. PUC-Rio. Disponível em: <http://www-di.inf.puc-rio.br/~julio/Mauricio.pdf>

COUTO, Anselmo; MARTINS, Luiz Eduardo. (2009). Um Processo de Validação de Requisitos Não-Funcionais Baseado no NFR-Framework. Disponível em: <https://fga-disciplinas.github.io/2019.1-Guia-Bolso/analise/analise_nfr>

## Versionamento

| Data | Versão | Descrição | Autor |
|--|--|--|--|
| 07/11/2020 | 1.0 | Adicionando inspeção | [Ithalo Azevedo](https://github.com/ithaloazevedo) |