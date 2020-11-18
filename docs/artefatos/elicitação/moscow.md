# Priorização
A priorização de requisitos ajuda a resolver conflitos, a planejar entregas e a decidir sobre quais requisitos implementar e a ordem de implementação deles. A decisão de priorizar as necessidades de um projeto deve ser tomada a partir de uma parceria entre cliente e desenvolvedor.

## Metodologia
Como o Doarti tem dois tipos de usuário (doador e entidade) separamos os requisitos para cada tipo de usuário. A técnica utilizada foi o MoSCoW, através desse método classificamos os requisitos em quatro categorias:
- (M) - Must Have (Tenho que fazer): como o nome sugere, essa categoria consiste em requisitos que são uma obrigação (“a must” em inglês) para o time. Elas representam necessidades não-negociáveis para o projeto, serviço, produto ou lançamento.
- (S) - Should Have (Devo fazer): essa categoria consistem em requisitos que são importantes para o produto final, mas não são vitais. Se deixadas de lado, a entrega ainda funciona. Mas, quando incluídas, acrescentam um valor significativo. Essas tarefas podem ser adiadas para um release no futuro sem impactar o processo atual. 
- (C) - Could Have (Poderia fazer): Uma outra forma de descrever essa categoria é a frase “seria legal ter”, pois essas tarefas não são necessárias para o funcionamento do projeto. Comparadas com as tarefas Should Have, elas têm um impacto muito menor nos resultados se deixadas de lado. Então, iniciativas Could Have geralmente são as primeiras a serem excluídas se as tarefas nas duas categorias anteriores acabarem ficando maiores do que o esperado.
- (W) - Won’t Have (Não vou fazer): Colocar tarefas nesta categoria é uma forma de evitar o scope creep, ou seja, o crescimento desorganizado do projeto. Se algo está neste nível, o time sabe que ele não é prioridade para agora, mas até podem vir a ser em um futuro próximo.


## Requisitos
|Requisito| Classificação|
|------|:--------:|
|Ambos os tipos usuário deve poder se cadastrar no aplicativo|M|
|O usuário doador deve poder fazer login pelo Google|C|
|O usuário doador deve poder fazer login pelo Facebook|C|
|Ambos os tipos usuário devem poder recuperar sua senha através de seu e-mail cadastrado|M|
|Ambos os tipos usuário devem poder redefinir sua senha|S|
|Ambos os tipos de usuário devem poder visualizar e editar seu perfil|M|
|Ambos os tipos de usuário devem poder visualizar informações sobre o Doarti|C|
|O usuário doador deve poder visualizar seu histórico de doações|S|
|O usuário doador deve poder visualizar campanhas|M|
|O usuário doador deve poder pesquisar por itens a doar|M|
|O usuário doador deve poder pesquisar por entidades|M|
|O usuário doador deve poder fazer doações|M|
|O usuário doador deve poder conversar com a entidade pelo chat|M|
|O usuário entidade deve poder conversar com o doador pelo chat|M|
|O usuário entidade deve poder criar campanhas|M|
|O usuário entidade deve poder escolher o tipo de suprimento a ser doado|M|
|O usuário entidade deve poder visualizar informações do doador (nome, telefone, status)|M|
|O usuário entidade deve poder selecionar filtros para ordenar as doações|S|
|As entidades devem ser validades para ter cadastro aprovado|M|

### Referências
http://www.matera.com/blog/post/priorizacao-de-requisitos  
https://rockcontent.com/br/blog/metodo-moscow/

## Históricos de Revisões

|    Data    | Versão |                   Descrição                   |  Autor(es)  |
| :--------: | :----: | :-------------------------------------------: | :---------: |
| 28/09/2020 |  1.0   | Adição das informações, metodologia e requisitos  | Aline Lermen, [Ithalo Azevedo](https://github.com/ithaloazevedo)|

