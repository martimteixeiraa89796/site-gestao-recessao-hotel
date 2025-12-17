---
sidebar_position: 1
---

# Apagar dado específico

Nesta secção do tutorial é explicado como funciona a opção Apagar dado específico da aplicação.

Esta funcionalidade permite ao utilizador apagar apenas uma linha específica de uma tabela, em vez de eliminar todos os dados existentes. É uma opção útil quando se pretende remover apenas um registo incorreto ou desatualizado.

## Como aceder à opção

No menu principal da aplicação, o utilizador deve escolher a opção “Apagar dados”.  
De seguida, é apresentado um novo menu com duas opções:

- Apagar todos os dados
- Apagar dado específico

![Menu apagar dados](/img/aplicacao/apagar_dados.png)

Ao selecionar Apagar dado específico, a aplicação inicia um processo interativo para remover uma linha concreta da base de dados.

## Escolha da tabela

A aplicação começa por mostrar uma lista com todas as tabelas existentes na base de dados.  
O utilizador deve escolher a tabela onde se encontra o dado que pretende apagar (por exemplo, Cliente, Quarto ou Hospede).

![Menu apagar dados](/img/aplicacao/apagar_dados_especifico.png)

Esta escolha é importante, pois define onde a operação de remoção será realizada.

## Escolha do campo de condição

Depois de selecionar a tabela, a aplicação apresenta os campos dessa tabela (como nome, NIF ou telefone).  
O utilizador escolhe um campo que servirá como condição para identificar o registo a apagar.

![Menu apagar dados](/img/aplicacao/apagar_dados_especifico_tbCliente.png)

Por exemplo, pode escolher o campo Nome para apagar um cliente específico.

## Introdução do valor

Após a escolha do campo, o utilizador deve introduzir o valor correspondente ao dado que deseja apagar.

![Menu apagar dados](/img/aplicacao/apagar_dados_especifico_tbCliente_nomeCliente.png)

A aplicação pede ainda para escolher o tipo de dado (inteiro, decimal ou texto), garantindo que o valor inserido seja compatível com a base de dados.

![Menu apagar dados](/img/aplicacao/apagar_dados_especifico_tbCliente_nomeCliente_sql.png)

## Execução da operação

Com todas as informações recolhidas (tabela, campo e valor), a aplicação executa a instrução de remoção, apagando apenas a linha que corresponde à condição definida.  
Desta forma, o sistema garante que apenas o dado pretendido é removido, mantendo os restantes registos intactos.
