# Especificação Suplementar

## Introdução

O presente documento reúne os requisitos não funcionais, aqueles não identificados nos demais processos de elicitação de requisitos e que não foram atendidos pelo contato direto com o aplicativo mas com a percepção de usuários e membros da equipe.
O método de avaliação que será usado para elicitar esses requisitos é o FURPS+.

## Finalidade

Esse documento visa descrever requisitos não funcionais do Doarti. Entende-se por requisito não funcional todo aquele requisito que especifica critérios que podem ser usados para julgar a **operação** de um sistema, ao invés de **comportamentos específicos**.

## Escopo

O Doarti é um aplicativo mobile que possibilita o encontro entre doadores e entidades filantrópicas. Usuários doadores podem escolher entre uma lista de doações disponíveis, podendo filtrar essa lista por diversos parâmetros e entidades podem criar doações com critérios específicos.

## Método FURPS+

Um modelo para classificação de atributos de qualidade de software. Desenvolvido pela Hewlett-Packard. O símbolo `+` foi adicionado posteriormente por pressão da comunidade para estender a sigla e sua definição.

- **F - Funcionality (Funcionalidade)** <br />
  Especifica as funcionalidades que não se relacionam com os casos de uso, nomeadamente: auditoria, reporte, interoperabilidade e segurança.

- **U - Usability (Usabilidade)** <br />
  Avalia a interface com o utilizador. Possui diversas subcategorias, entre elas: prevenção de erros, estética e design, documentação, consistência e padrões.

- **R - Reliability (Confiabilidade)** <br />
  Refere-se à integridade, conformidade e interoperabilidade do software. Os requisitos a serem considerados são: frequência e gravidade de falhas, possibilidade de recuperação, extensão e duração da falha (valorização/sobrevivência) e previsibilidade (estabilidade).

- **P - Performance (Performance)** <br />
  Avalia os requisitos de desempenho do software nomeadamente: tempo de resposta, consumo de recursos (energia, RAM, CPU, cache, etc), capacidade e escalabilidade.

- **S - Suportability (Suportabilidade)** <br />
  Os requisitos de suportabilidade agrupam várias características, tais como: testabilidade, adaptabilidade, manutenabilidade, campatibilidade, configurabilidade, instalabilidade, escalabilidade, entre outros.

## Doarti

- **Funcionalidade** <br />
  - Segurança: A aplicação deve armazenar os dados de seus usuários de forma segura para evitar vazamento de informações;
  - Reporte: A aplicação fornece uma forma dos usuários enviarem feedbacks para os desenvolvedores.

- **Usabilidade** <br />
  - A aplicação utiliza de linguagem simples para o publico alvo;
  - A aplicação segue padrões para cores, espaçamentos e formas;
  - A aplicação da feedbacks de erros para seus usuários.
- **Confiabilidade** <br />
  - A aplicação deve dar feedback em caso de falhas, caso não consiga se recuperar dessa falha a mesma deve instruir o usuário de como faze-lo.
- **Performance** <br />
  - A aplicação não aparenta consumir muito dos recursos do dispositivo móvel, tendo respostas rápidas para as ações feitas pelo usuário.
- **Suportabilidade** <br />
  - A aplicação está disponível na forma de aplicativo móvel para os maiores sistemas operacionais, Android e iOS.

| Data | Versão | Descrição | Autor(es) |
|:----:|:------:|:---------:|:---------:|
| 06/10/2020 | 1.0 | Criação do documento, adição de Introdução, Finalidade, Escopo e Método de avaliação | [Marcos Cabeceira](https://github.com/Foxtrot40) |
| 24/11/2020 | 1.1 | Adição dos casos para o Doarti | [Marcos Cabeceira](https://github.com/Foxtrot40) |