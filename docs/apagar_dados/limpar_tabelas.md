---
sidebar_position: 2
---

# Apagar dados

## Apagar todos os dados

Nesta secção do tutorial é explicada a funcionalidade Apagar todos os dados da aplicação.

Esta opção permite ao utilizador eliminar todos os registos de uma tabela, mantendo a estrutura da tabela intacta. Ou seja, a tabela continua a existir na base de dados, mas fica sem qualquer informação armazenada.

## Como aceder à opção

No menu principal da aplicação, o utilizador deve selecionar a opção “Apagar dados”.  
De seguida, é apresentado um menu com duas possibilidades:

- Apagar todos os dados
- Apagar dado específico

![Menu apagar dados](/img/aplicacao/apagar_dados.png)

Ao escolher Apagar todos os dados, a aplicação inicia o processo de limpeza completa de uma tabela.

## Escolha da tabela

A aplicação apresenta uma lista com todas as tabelas disponíveis na base de dados.  
O utilizador deve escolher a tabela da qual pretende apagar todos os dados, como por exemplo:

- Cliente
- Hospede
- Quarto

![Menu apagar dados](/img/aplicacao/apagar_dados_todos.png)

Esta escolha é importante, pois todos os registos dessa tabela serão removidos.

## Execução da limpeza

Depois da seleção da tabela, a aplicação executa uma instrução que elimina todas as linhas existentes nessa tabela.  
Este processo é automático e não requer a introdução de condições ou valores adicionais.

![Menu apagar dados](/img/aplicacao/apagar_dados_todos2.png)

A estrutura da tabela não é apagada, apenas os dados nela contidos.

## Cuidados a ter

A opção Apagar todos os dados deve ser utilizada com cuidado, pois não é possível recuperar os dados eliminados após a execução da operação.  
Por esse motivo, esta funcionalidade é indicada apenas quando é realmente necessário limpar completamente uma tabela.










