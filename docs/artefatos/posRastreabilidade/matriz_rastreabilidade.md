# Matriz geral de pós-rastreabilidade

## Introdução
A rastreabilidade é uma característica de sistemas, nas quais requisitos são claramente ligados às suas fontes, bem como aos artefatos criados durante o ciclo de vida do sistema. Na matriz geral de pós-rastreabilidade a seguir, são apresentados os requisitos, as suas respectivas origens, e os artefatos ao qual está ligado.


### Legenda
Q - [questionário](artefatos/elicitação/questionario.md)  
B - [brainstorming](artefatos/elicitação/brainstorming.md)   
E - [entrevista](artefatos/elicitação/entrevistas.md)  
S - [storyboard](artefatos/elicitação/storyboard.md)

## Requisitos Funcionais

|  ID  | Descrição | Origem | Product Backlog | Caso de uso | Cenário | Léxico |
| :-:  | :-------- | :----: | :-------------: | :---------: | :-----: | :----: |
| RF01 | Ambos os tipos usuário devem poder se cadastrar no aplicativo | B | F01, F07 | DUC01 | - | L11 |
| RF02 | O usuário doador deve poder fazer login pelo Google | B | F07 | DUC02 | - | L18 |
| RF03 | O usuário doador deve poder fazer login pelo Facebook | B | F07 | DUC02 | - | L18 |
| RF04 | Ambos os tipos usuário deve poder fazer login pelo seu email cadastrado | B | F01, F07 | DUC02, BUC02 | C01 | L17,L18 |
| RF05 | Ambos os tipos usuário devem poder recuperar sua senha através de seu e-mail cadastrado | B | - | - | - | - |
| RF06 | Ambos os tipos de usuário devem poder redefinir sua senha | B | F02, F08 | - | - | L01 |
| RF07 | Ambos os tipos de usuário devem poder visualizar e editar seu perfil | B | F02, F08 | DUC04, BUC04 | - | L20 |
| RF08 | Ambos os tipos de usuário devem poder visualizar informações sobre o Doarti | B | F06, F12 | DUC10 | - | L21 |
| RF09 | O usuário doador deve poder visualizar seu histórico de doações | B | F10 | DUC05 | - | - |
| RF10 | O usuário doador deve poder visualizar campanhas | B, S | F09 | DUC07 | - | L06, L08 |
| RF11 | O usuário doador deve poder pesquisar por itens a doar | Q, B, E | F09 | DUC06 | - | L03, L05 |
| RF12 | O usuário doador deve poder pesquisar por entidades  | Q | F09 | DUC06 | - | L03, L04 |
| RF13 | O usuário doador deve poder fazer doações | B, S | F10 | DUC08 | C02 | - |
| RF14 | O usuário doador deve poder conversar com a entidade pelo chat | Q, B, E, S | F11 | DUC09 | - | L07, L10, L19 |
| RF15 | O usuário beneficiário deve poder conversar com o doador pelo chat | B, E, S | F05 | BUC11 | - | L07, L10, L19 |
| RF16 | O usuário beneficiário deve poder criar campanhas | B, S | F03 | BUC06 | - | L06 |
| RF17 | O usuário beneficiário deve poder escolher o tipo de suprimento a ser doado | B, E | F03 | BUC06 | - | - |
| RF18 | O usuário beneficiário deve poder visualizar informações do doador (nome, telefone, status) | B, S | F05 | BUC09 | - | - |
| RF19 | O usuário beneficiário deve poder selecionar filtros para ordenar as doações | B | F04 | - | - | - |
| RF20 | O usuário beneficiário deve poder editar campanhas | B | F03 | BUC07 | - | - |
| RF21 | O usuário beneficiário deve poder excluir campanhas | B | F03 | BUC08 | - | - |

## Requisitos Não Funcionais
|  ID  | Descrição | Origem | NFR |
| :-:  | :-------- | :----: | :-: |
| RNF01 | O usuário beneficiário deve ser validado para ter cadastro aprovado | B | - |
| RNF02 | A aplicação deve armazenar os dados de seus usuários de forma segura para evitar vazamento de informações | B | - |
| RNF03 | A aplicação deve fornecer uma forma dos usuários enviarem feedbacks para os desenvolvedores. | B | - |
| RNF04 | A aplicação deve dar feedback em caso de falhas, caso não consiga se recuperar dessa falha a mesma deve instruir o usuário de como faze-lo. | B | NFR02 |
| RNF05 | A aplicação deve apresentar respostas rápidas para as ações feitas pelo usuário. | B | - |
| RNF06 | A aplicação deve estar disponível na forma de aplicativo móvel para Android e iOS. | B | NFR03 |


## Referências
SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Revisões

| Data | Versão | Descrição | Autor(es) |
|:---:|:---:|:---:|:---:|
| 24/11/2020 | 1.0 | Criação do documento e adição da tabela | [Aline Lermen](https://github.com/AlineLermen) |
| 26/11/2020 | 1.1 | Adição da tabela de requisitos não funcionais | [Aline Lermen](https://github.com/AlineLermen) |
