# Cenários

Trata-se de uma estratégia reconhecida por compreender as interações entre ambiêntes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou fluxo.

### Cenário 01 - Fazer Login

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Fazer Login |
| Metas | | Conectar-se à plataforma ao fornecer usuário e senha |
| Contexto | | Local: Aplicativo, Doações e Chat <br /> Tempo: Em qualquer momento <br /> Pré-condição: O usuário deve estar cadastrado |
| Ator | | Usuário |
| Recursos | | Smartphone e acesso à internet |
| Exceção | | Usuário não é cadastrado ou não possuir qualquer um dos recursos descritos <br /> Usuário já está logado |
| Episódios | | - Usuário entra na tela Perfil ou Doações ou Chat <br /> - Usuário preenche seus dados nos campos de e-mail e senha |

### Cenário 02 - Fazer Doação

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Fazer doação |
| Metas | | Fazer uma doação para uma instituição |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: O usuário deve estar cadastrado |
| Ator(es) | | Usuário |
| Recursos | | Smartphone, acesso à internet e conta na plataforma |
| Exceção | | Usuário não é cadastrado ou não possuir qualquer um dos recursos descritos <br /> Usuário já está logado |
| Episódios | | - O usuário entra na tela Home <br /> - Escolhe uma doação para fazer - Se não estiver conectado, usuário se conecta <br /> - O usuário preenche as informações sobre a doação e se pode entregar a doação na entidade <br />|

### Cenário 03 - Cadastro Doador

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Fazer Cadastro como doador |
| Metas | | Cadastrar-se como usuário doador |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: Nenhuma |
| Ator(es) | | Usuário |
| Recursos | | Smartphone e acesso à internet |
| Exceção | | Usuário já é cadastrado, e-mail já está em uso |
| Episódios | | - O usuário entra na tela de Perfil <br /> - Clica em "Cadastre-se aqui" <br /> - O usuário preenche as informações sobre a conta <br />|

### Cenário 04 - Cadastro Entidade

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Fazer Cadastro como entidade |
| Metas | | Cadastrar-se como usuário uma entidade |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: Nenhuma |
| Ator(es) | | Entidade |
| Recursos | | Smartphone e acesso à internet |
| Exceção | | Entidade já é cadastrada, e-mail já está em uso |
| Episódios | | - A entidade entra na tela de Perfil <br /> - Copia o e-mail para entrar em contato com a equipe do Doarti <br />|

### Cenário 05 - Entrar usando redes sociais

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Fazer Login com redes sociais |
| Metas | | Entrar como doador |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: Ter conta nas redes sociais suportadas (Google, Facebook) |
| Ator(es) | | Usuário |
| Recursos | | Smartphone, acesso à internet e conta nas redes sociais |
| Exceção | | Conta na rede social já está em uso |
| Episódios | | - O usuário entra na tela de Perfil <br /> - Seleciona se quer entrar com conta do Google ou Facebook <br /> - Aguarda a rede social processar a requisição, tomando os passos necessários que a mesma possa requerer do usuário |

### Cenário 06 - Recuperar conta

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Recuperar conta do usuário/entidade |
| Metas | | Receber e-mail para recuperação de conta |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: Ter conta no Doarti |
| Ator(es) | | Usuário/Entidade |
| Recursos | | Smartphone, acesso à internet e conta no Doarti |
| Exceção | | Nenhuma |
| Episódios | | - O usuário entra na tela de Perfil <br /> - Clica em "Esqueceu sua senha?" <br /> - Fornece o e-mail de sua conta <br /> - Clica em "Recuperar senha" |

### Cenário 07 - Redefinir senha (usuário doador)

| | | |
| -------- | | ---------------------------------------------------- |
| Título | | Redefinir a senha do usuário doador |
| Metas | | Redefinir a senha de acesso do usuário doador |
| Contexto | | Local: Aplicativo <br /> Tempo: Em qualquer momento <br /> Pré-condição: Ter conta no Doarti |
| Ator(es) | | Usuário |
| Recursos | | Smartphone, acesso à internet e conta no Doarti |
| Exceção | | Nenhuma |
| Episódios | | - O usuário entra na tela de Perfil <br /> - Clica em "Alterar Senha" <br /> - Recebe e-mail com instruções para redefinição de senha |

| Data | Versão | Descrição | Autor(es) |
|:----:|:------:|:---------:|:---------:|
| 08/10/2020 | 1.0 | Criação do documento, adição de cenários 1 e 2 | [Marcos Cabeceira](https://github.com/Foxtrot40) |
| 26/11/2020 | 1.1 | Adição de cenários 3, 4, 5, 6 e 7 | [Marcos Cabeceira](https://github.com/Foxtrot40) |