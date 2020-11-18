# BUC06 - Criar campanha

## Diagrama
![BUC06](../../../../assets/images/casosDeUso/BUC06.png)

## Descrição
O usuário beneficiário deve poder criar campanhas.

## Atores
Usuário beneficiário.

## Pré-requisitos
O usuário beneficiário deve estar logado na aplicação.
Não deve existir outra campanha do mesmo tipo já criada.

## Fluxo de Eventos

### Fluxo Principal
1. O usuário beneficiário seleciona o botão “CAMPANHAS”.
2. O usuário beneficiário é redirecionado para a página de campanhas.
3. O usuário beneficiário seleciona o tipo de campanha que quer criar.
4. O usuário beneficiário preenche o formulário da campanha.
5. O usuário beneficiário clica no botão “SALVAR”.
6. O formulário é submetido.

### Fluxo Alternativo
Não há fluxos alternativos.

### Fluxos de Exceção
**FE01**: Algum dos campos obrigatórios do formulário não foi preenchido.
1. O usuário beneficiário seleciona o botão “CAMPANHAS”.
3. O usuário beneficiário é redirecionado para a página de campanhas.
4. O usuário beneficiário seleciona o tipo de campanha que quer criar.
5. O usuário beneficiário preenche o formulário da campanha.
6. O usuário beneficiário clica no botão “SALVAR”.
7. O sistema retorna um erro informando o(s) campo(s) obrigatório(s) que não foi(foram) preenchido(s).


## Pós-condição
A campanha será criada e poderá ser visualizada por usuários do tipo doador.

## Versionamento
|    Data    | Versão |                        Descrição                         |                            Autor(es)                             |
| :--------: | :----: | :------------------------------------------------------: | :--------------------------------------------------------------: |
| 06/10/2020 | 1.0 | Criação do caso de uso | [Ithalo Azevedo](https://github.com/ithaloazevedo) |
| 06/10/2020 | 1.0 | Revisão do caso de uso | Aline Lermen |
