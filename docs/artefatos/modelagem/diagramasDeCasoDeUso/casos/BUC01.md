# BUC01 - Cadastrar como usuário beneficiário

# Diagrama
![BUC01](../../assets/images/casosDeUso/BUC01.png)

## Descrição
O usuário beneficiário deve poder se cadastrar no aplicativo.

## Atores
Usuário beneficiário.
Suporte técnico.

## Pré-requisitos
O usuário beneficiário deve possuir um endereço de e-mail.
O e-mail utilizado para cadastro não pode ter sido utilizado no cadastro de outra conta.
O usuário beneficiário deve se enquadrar nos [critérios de cadastro](https://doarti.com.br/#criterios).

## Fluxo de Eventos

### Fluxo Principal
1. O usuário beneficiário entra no site do Doarti (https://doarti.com.br/).
2. O usuário beneficiário clica em “Pré-cadastro”.
3. O usuário beneficiário é redirecionado para um formulário de pré-cadastro.
4. O usuário beneficiário preenche o formulário.
5. O usuário beneficiário seleciona a opção “Solicitar cadastro”.
6. O formulário é enviado ao suporte técnico.
7. O suporte técnico valida o beneficiário e verifica se ele se enquadra nos critérios para o cadastro.
8. O suporte técnico aprova o cadastro do usuário beneficiário.

### Fluxos Alternativos
Não há fluxos alternativos.

### Fluxos de Exceção
**FE01**: Usuário beneficiário não se enquadra nos critérios de cadastro.
   1. O usuário beneficiário entra no site do Doarti (https://doarti.com.br/).
   2. O usuário beneficiário clica em “Pré-cadastro”.
   3. O usuário beneficiário é redirecionado para um formulário de pré-cadastro.
   4. O usuário beneficiário preenche o formulário.
   5. O usuário beneficiário seleciona a opção “Solicitar cadastro”.
   6. O formulário é enviado ao suporte técnico.
   7. O suporte técnico valida o beneficiário e verifica se ele se enquadra nos critérios para o cadastro.
   8. O suporte técnico reprova o cadastro do usuário beneficiário.

## Pós-condição
O usuário beneficiário agora pode realizar login no Doarti, gerenciar campanhas, ver doações recebidas e conversar com o usuário doador pelo chat.

## Referências
https://doarti.com.br/#criterios
